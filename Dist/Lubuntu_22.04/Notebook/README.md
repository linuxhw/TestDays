Lubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 444

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | S6421 MD60703               | [609c73a176](https://linux-hardware.org/?probe=609c73a176) | Dec 19, 2024 |
| HP            | 2000                        | [3c20e6e18c](https://linux-hardware.org/?probe=3c20e6e18c) | Dec 11, 2024 |
| Dell          | Inspiron 15-3567            | [cbf6bf1b48](https://linux-hardware.org/?probe=cbf6bf1b48) | Dec 06, 2024 |
| Apple         | MacBookPro8,1               | [ba64567726](https://linux-hardware.org/?probe=ba64567726) | Nov 18, 2024 |
| Dell          | Inspiron 15-3567            | [815225e627](https://linux-hardware.org/?probe=815225e627) | Nov 18, 2024 |
| Dell          | Latitude E7240              | [82e1ee846b](https://linux-hardware.org/?probe=82e1ee846b) | Nov 02, 2024 |
| Lenovo        | ThinkPad E15 20RD005VRT     | [0faadd1106](https://linux-hardware.org/?probe=0faadd1106) | Oct 24, 2024 |
| HP            | EliteBook 2540p             | [53c668190f](https://linux-hardware.org/?probe=53c668190f) | Oct 23, 2024 |
| Lenovo        | Z70-80 80FG                 | [df61da6a87](https://linux-hardware.org/?probe=df61da6a87) | Oct 22, 2024 |
| Medion        | S6421 MD60703               | [c92c3514b3](https://linux-hardware.org/?probe=c92c3514b3) | Oct 22, 2024 |
| Dell          | Vostro 1500                 | [6680201494](https://linux-hardware.org/?probe=6680201494) | Oct 06, 2024 |
| HP            | EliteBook 2540p             | [582f0a4f04](https://linux-hardware.org/?probe=582f0a4f04) | Oct 04, 2024 |
| Toshiba       | Satellite C660              | [1ce63743fd](https://linux-hardware.org/?probe=1ce63743fd) | Oct 01, 2024 |
| Lenovo        | ThinkPad T480s 20L8S3SW0... | [d3f2558562](https://linux-hardware.org/?probe=d3f2558562) | Sep 28, 2024 |
| Dell          | Latitude E6410              | [92cd0e0eee](https://linux-hardware.org/?probe=92cd0e0eee) | Sep 17, 2024 |
| Dell          | Latitude E6410              | [d9385745e8](https://linux-hardware.org/?probe=d9385745e8) | Sep 17, 2024 |
| Acer          | Aspire ES1-571              | [a5aeb5f264](https://linux-hardware.org/?probe=a5aeb5f264) | Sep 10, 2024 |
| Samsung       | RV415                       | [e3d0816997](https://linux-hardware.org/?probe=e3d0816997) | Sep 07, 2024 |
| HP            | EliteBook 8440p             | [70ad6eb824](https://linux-hardware.org/?probe=70ad6eb824) | Sep 03, 2024 |
| Dell          | Latitude 5285               | [ece411e4e4](https://linux-hardware.org/?probe=ece411e4e4) | Aug 27, 2024 |
| HP            | Pavilion dv6                | [8745b6a8a6](https://linux-hardware.org/?probe=8745b6a8a6) | Aug 22, 2024 |
| Acer          | Aspire E5-571G              | [5d217cd410](https://linux-hardware.org/?probe=5d217cd410) | Aug 22, 2024 |
| HP            | Compaq Presario CQ60        | [d0e97b8772](https://linux-hardware.org/?probe=d0e97b8772) | Aug 13, 2024 |
| SK hynix      | HT14CCIC42E                 | [eb41114fc3](https://linux-hardware.org/?probe=eb41114fc3) | Aug 10, 2024 |
| Acer          | Aspire 5715Z                | [32b3360c63](https://linux-hardware.org/?probe=32b3360c63) | Aug 07, 2024 |
| Acer          | Aspire 5715Z                | [387c8e5fe4](https://linux-hardware.org/?probe=387c8e5fe4) | Aug 07, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [ef1df870ea](https://linux-hardware.org/?probe=ef1df870ea) | Aug 07, 2024 |
| Dell          | Inspiron N5110              | [c390f98098](https://linux-hardware.org/?probe=c390f98098) | Aug 03, 2024 |
| HP            | Pavilion x2 Detachable      | [f5fb19db6b](https://linux-hardware.org/?probe=f5fb19db6b) | Jul 27, 2024 |
| HP            | Pavilion x2 Detachable      | [8f6ba78b79](https://linux-hardware.org/?probe=8f6ba78b79) | Jul 25, 2024 |
| Acer          | Aspire A515-57G             | [e7fba30a89](https://linux-hardware.org/?probe=e7fba30a89) | Jul 23, 2024 |
| HP            | 240 G4                      | [74ad43cd86](https://linux-hardware.org/?probe=74ad43cd86) | Jul 19, 2024 |
| Lenovo        | ThinkPad L13 Gen 1 20R4S... | [4cc52bfb25](https://linux-hardware.org/?probe=4cc52bfb25) | Jul 07, 2024 |
| Notebook      | PB50_70EF,ED,EC             | [9d7e31a9f6](https://linux-hardware.org/?probe=9d7e31a9f6) | Jul 06, 2024 |
| Dell          | XPS M1330                   | [a01b178b3a](https://linux-hardware.org/?probe=a01b178b3a) | Jul 06, 2024 |
| Acer          | Aspire V5-471P              | [f8a09477f0](https://linux-hardware.org/?probe=f8a09477f0) | Jul 05, 2024 |
| ASUSTek       | K50AD                       | [0fd561ca3c](https://linux-hardware.org/?probe=0fd561ca3c) | Jul 05, 2024 |
| Dell          | Latitude E6410              | [6f8ffa83ce](https://linux-hardware.org/?probe=6f8ffa83ce) | Jul 01, 2024 |
| HP            | Pavilion 10 TS              | [c2bd71447d](https://linux-hardware.org/?probe=c2bd71447d) | Jun 30, 2024 |
| Dell          | Inspiron 15-3567            | [3eed7f4afe](https://linux-hardware.org/?probe=3eed7f4afe) | Jun 30, 2024 |
| HP            | Laptop 15-bw0xx             | [3a1445300b](https://linux-hardware.org/?probe=3a1445300b) | Jun 28, 2024 |
| Dell          | Latitude 3190               | [41e83ac5c5](https://linux-hardware.org/?probe=41e83ac5c5) | Jun 27, 2024 |
| RWC           | DA-T118-SR                  | [05f141e671](https://linux-hardware.org/?probe=05f141e671) | Jun 26, 2024 |
| Teclast       | tPAD                        | [7fcbabfefd](https://linux-hardware.org/?probe=7fcbabfefd) | Jun 25, 2024 |
| Insyde        | Braswell                    | [fb1a3d94f3](https://linux-hardware.org/?probe=fb1a3d94f3) | Jun 19, 2024 |
| HP            | Laptop 15-bs0xx             | [3e4d7f9fbc](https://linux-hardware.org/?probe=3e4d7f9fbc) | Jun 01, 2024 |
| ASUSTek       | X550WAK                     | [1a64c5c27f](https://linux-hardware.org/?probe=1a64c5c27f) | May 31, 2024 |
| Lenovo        | ThinkPad X200 2024B67       | [6d2d7fbbb5](https://linux-hardware.org/?probe=6d2d7fbbb5) | May 28, 2024 |
| ASUSTek       | GL552VX                     | [9f2697991a](https://linux-hardware.org/?probe=9f2697991a) | May 26, 2024 |
| Lenovo        | ThinkPad L490 20Q5002GGE    | [c92390a81b](https://linux-hardware.org/?probe=c92390a81b) | May 15, 2024 |
| Dell          | Inspiron 13-5378            | [fcb1c00cb1](https://linux-hardware.org/?probe=fcb1c00cb1) | May 15, 2024 |
| Sony          | VPCW216AG                   | [0e3674f67f](https://linux-hardware.org/?probe=0e3674f67f) | May 14, 2024 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [abf8f16050](https://linux-hardware.org/?probe=abf8f16050) | May 13, 2024 |
| Dell          | Vostro 3400                 | [345ddaf7ed](https://linux-hardware.org/?probe=345ddaf7ed) | May 13, 2024 |
| Dell          | Vostro 3400                 | [93da978d38](https://linux-hardware.org/?probe=93da978d38) | May 04, 2024 |
| ASUSTek       | X540YA                      | [e163aa8e32](https://linux-hardware.org/?probe=e163aa8e32) | May 03, 2024 |
| HP            | Pavilion dm1                | [ba07809953](https://linux-hardware.org/?probe=ba07809953) | May 02, 2024 |
| ASUSTek       | K45A                        | [7bed7e12ab](https://linux-hardware.org/?probe=7bed7e12ab) | Apr 27, 2024 |
| Dell          | Inspiron 15-3567            | [e93fe83f01](https://linux-hardware.org/?probe=e93fe83f01) | Apr 24, 2024 |
| Acer          | Aspire E5-573G              | [216cd2fc72](https://linux-hardware.org/?probe=216cd2fc72) | Apr 24, 2024 |
| ASUSTek       | X555QG                      | [c905efd379](https://linux-hardware.org/?probe=c905efd379) | Apr 23, 2024 |
| ASUSTek       | X555QG                      | [26b8da2305](https://linux-hardware.org/?probe=26b8da2305) | Apr 23, 2024 |
| ASUSTek       | K42F                        | [f29299723c](https://linux-hardware.org/?probe=f29299723c) | Apr 23, 2024 |
| ASUSTek       | K42F                        | [63b454fa02](https://linux-hardware.org/?probe=63b454fa02) | Apr 23, 2024 |
| Dell          | Inspiron 15-3567            | [bf1e4f8d6a](https://linux-hardware.org/?probe=bf1e4f8d6a) | Apr 20, 2024 |
| HP            | EliteBook 6930p             | [263d72f3c6](https://linux-hardware.org/?probe=263d72f3c6) | Apr 17, 2024 |
| Unknown       | Unknown                     | [10d92e98c0](https://linux-hardware.org/?probe=10d92e98c0) | Apr 16, 2024 |
| HP            | 250 G4 Notebook PC          | [2fcb542c43](https://linux-hardware.org/?probe=2fcb542c43) | Apr 14, 2024 |
| Unknown       | M-140BI3                    | [491b1013ab](https://linux-hardware.org/?probe=491b1013ab) | Apr 11, 2024 |
| HP            | Pavilion g7                 | [6d84e70e34](https://linux-hardware.org/?probe=6d84e70e34) | Apr 10, 2024 |
| Lenovo        | ThinkPad X201 3680A44       | [db6aadf372](https://linux-hardware.org/?probe=db6aadf372) | Apr 10, 2024 |
| Dell          | Latitude E6410              | [7c4144e1df](https://linux-hardware.org/?probe=7c4144e1df) | Apr 05, 2024 |
| Acer          | Extensa 5630                | [224d74c060](https://linux-hardware.org/?probe=224d74c060) | Apr 04, 2024 |
| Acer          | Aspire E1-572G              | [7a19eed833](https://linux-hardware.org/?probe=7a19eed833) | Apr 03, 2024 |
| HP            | Laptop 15s-eq2xxx           | [b4e434bb17](https://linux-hardware.org/?probe=b4e434bb17) | Mar 27, 2024 |
| Acer          | Extensa 2540                | [3e49d36612](https://linux-hardware.org/?probe=3e49d36612) | Mar 26, 2024 |
| HP            | 15 Notebook PC              | [46b79e7d26](https://linux-hardware.org/?probe=46b79e7d26) | Mar 26, 2024 |
| HP            | Laptop 14-em0xxx            | [3f937a527b](https://linux-hardware.org/?probe=3f937a527b) | Mar 23, 2024 |
| Samsung       | N100                        | [d7a66b3835](https://linux-hardware.org/?probe=d7a66b3835) | Mar 22, 2024 |
| Sony          | VGN-TZ21MN_N                | [1e1a62727b](https://linux-hardware.org/?probe=1e1a62727b) | Mar 19, 2024 |
| Unknown       | Unknown                     | [27317f4bcf](https://linux-hardware.org/?probe=27317f4bcf) | Mar 18, 2024 |
| Sony          | VPCW216AG                   | [c607fc8a6b](https://linux-hardware.org/?probe=c607fc8a6b) | Mar 16, 2024 |
| HP            | Split 13 x2 PC              | [447e4a6951](https://linux-hardware.org/?probe=447e4a6951) | Mar 14, 2024 |
| Lenovo        | ThinkPad L520 5015AH2       | [c63473fd10](https://linux-hardware.org/?probe=c63473fd10) | Mar 12, 2024 |
| HP            | Notebook                    | [51a929c53a](https://linux-hardware.org/?probe=51a929c53a) | Mar 08, 2024 |
| Sony          | SVF1521NSTB                 | [b9f4d235c9](https://linux-hardware.org/?probe=b9f4d235c9) | Mar 06, 2024 |
| HP            | Notebook                    | [025b54a984](https://linux-hardware.org/?probe=025b54a984) | Mar 06, 2024 |
| HP            | Notebook                    | [5f90d8f25b](https://linux-hardware.org/?probe=5f90d8f25b) | Mar 06, 2024 |
| Fujitsu       | FMVC05005                   | [af1cd1c78b](https://linux-hardware.org/?probe=af1cd1c78b) | Mar 04, 2024 |
| Sony          | VPCEB3C4R                   | [f63a65b29f](https://linux-hardware.org/?probe=f63a65b29f) | Mar 04, 2024 |
| MSI           | MS-168A                     | [1625072479](https://linux-hardware.org/?probe=1625072479) | Mar 02, 2024 |
| MSI           | MS-168A                     | [cae162bcad](https://linux-hardware.org/?probe=cae162bcad) | Mar 02, 2024 |
| HP            | 250 G1                      | [805489bf43](https://linux-hardware.org/?probe=805489bf43) | Feb 26, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [7c9a199867](https://linux-hardware.org/?probe=7c9a199867) | Feb 21, 2024 |
| Sony          | VPCEB3C4R                   | [93a9016bf3](https://linux-hardware.org/?probe=93a9016bf3) | Feb 20, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d18785d54f](https://linux-hardware.org/?probe=d18785d54f) | Feb 16, 2024 |
| Digibras      | NH4CU53                     | [1e3d9f1795](https://linux-hardware.org/?probe=1e3d9f1795) | Feb 10, 2024 |
| Dell          | Latitude E5430 vPro         | [9e120d90b8](https://linux-hardware.org/?probe=9e120d90b8) | Feb 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5fa467241b](https://linux-hardware.org/?probe=5fa467241b) | Feb 05, 2024 |
| Itautec       | Infoway w7430               | [4928095170](https://linux-hardware.org/?probe=4928095170) | Feb 05, 2024 |
| Acer          | Aspire 5951G                | [e583f21b3a](https://linux-hardware.org/?probe=e583f21b3a) | Feb 05, 2024 |
| HP            | Pavilion dv6                | [52c0814c31](https://linux-hardware.org/?probe=52c0814c31) | Feb 03, 2024 |
| HP            | Pavilion dv6                | [d477732dfa](https://linux-hardware.org/?probe=d477732dfa) | Feb 03, 2024 |
| Lenovo        | G405 20239                  | [7afc820794](https://linux-hardware.org/?probe=7afc820794) | Feb 01, 2024 |
| Acer          | Swift SF314-43              | [793c3d3b4c](https://linux-hardware.org/?probe=793c3d3b4c) | Jan 31, 2024 |
| Lenovo        | G575 20081                  | [162e1f81cf](https://linux-hardware.org/?probe=162e1f81cf) | Jan 31, 2024 |
| Lenovo        | V310-15ISK 80SY             | [a72292c97b](https://linux-hardware.org/?probe=a72292c97b) | Jan 31, 2024 |
| Lenovo        | ThinkPad T60p 20078JU       | [6c83cf1141](https://linux-hardware.org/?probe=6c83cf1141) | Jan 25, 2024 |
| Acer          | Aspire E1-572G              | [d94fb0b47b](https://linux-hardware.org/?probe=d94fb0b47b) | Jan 24, 2024 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [82175efff8](https://linux-hardware.org/?probe=82175efff8) | Jan 14, 2024 |
| iRU           | 15TLI                       | [d318923a72](https://linux-hardware.org/?probe=d318923a72) | Jan 09, 2024 |
| ASUSTek       | K53U                        | [df631caaa2](https://linux-hardware.org/?probe=df631caaa2) | Jan 09, 2024 |
| Lenovo        | ThinkPad T430 23477C7       | [db1c43a6a6](https://linux-hardware.org/?probe=db1c43a6a6) | Jan 09, 2024 |
| HP            | 240 G6 Notebook PC          | [52fa49b647](https://linux-hardware.org/?probe=52fa49b647) | Jan 08, 2024 |
| HP            | Notebook                    | [79932769a2](https://linux-hardware.org/?probe=79932769a2) | Jan 08, 2024 |
| Digibras      | NH4CU03                     | [be0eab4038](https://linux-hardware.org/?probe=be0eab4038) | Jan 05, 2024 |
| Google        | Electro                     | [74ed1caffe](https://linux-hardware.org/?probe=74ed1caffe) | Jan 04, 2024 |
| Packard Be... | EasyNote LM85               | [e756bb57ba](https://linux-hardware.org/?probe=e756bb57ba) | Jan 03, 2024 |
| HP            | Notebook                    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| Apple         | MacBook6,1                  | [ba4ad2bc18](https://linux-hardware.org/?probe=ba4ad2bc18) | Dec 31, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [af69ec2d33](https://linux-hardware.org/?probe=af69ec2d33) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [143c6b4161](https://linux-hardware.org/?probe=143c6b4161) | Dec 29, 2023 |
| Chuwi         | GemiBook Plus               | [acb06bb39a](https://linux-hardware.org/?probe=acb06bb39a) | Dec 29, 2023 |
| Google        | Swanky                      | [12fd273db1](https://linux-hardware.org/?probe=12fd273db1) | Dec 27, 2023 |
| Acer          | Extensa 215-55              | [54ca5c9e74](https://linux-hardware.org/?probe=54ca5c9e74) | Dec 25, 2023 |
| Acer          | Aspire 1810TZ               | [0b4e0e5e2b](https://linux-hardware.org/?probe=0b4e0e5e2b) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | [3ba98d8db9](https://linux-hardware.org/?probe=3ba98d8db9) | Dec 24, 2023 |
| HP            | ZBook 17                    | [d1269ca08c](https://linux-hardware.org/?probe=d1269ca08c) | Dec 13, 2023 |
| Dell          | Inspiron 3421               | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [5a628a7b0f](https://linux-hardware.org/?probe=5a628a7b0f) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3b82362902](https://linux-hardware.org/?probe=3b82362902) | Nov 29, 2023 |
| SGIN          | M15                         | [c7fb994367](https://linux-hardware.org/?probe=c7fb994367) | Nov 28, 2023 |
| Dell          | Latitude E6520              | [a03b74a3d3](https://linux-hardware.org/?probe=a03b74a3d3) | Nov 28, 2023 |
| ASUSTek       | X550ZE                      | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| Chuwi         | X312B                       | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| MSI           | Raider GE76 12UE            | [bad07cc00d](https://linux-hardware.org/?probe=bad07cc00d) | Nov 20, 2023 |
| Packard Be... | ENLE11BZ                    | [905ad855b3](https://linux-hardware.org/?probe=905ad855b3) | Nov 19, 2023 |
| ASUSTek       | X201E                       | [3532136698](https://linux-hardware.org/?probe=3532136698) | Nov 18, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [d297e1365c](https://linux-hardware.org/?probe=d297e1365c) | Nov 16, 2023 |
| HP            | 250 G5 Notebook PC          | [dde4f98b29](https://linux-hardware.org/?probe=dde4f98b29) | Nov 16, 2023 |
| Acer          | Extensa 5620                | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| ASUSTek       | T100TAS                     | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fa680be8d9](https://linux-hardware.org/?probe=fa680be8d9) | Nov 10, 2023 |
| ASUSTek       | X550ZE                      | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| ASUSTek       | K50IJ                       | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| Dixonsxp      | Unknown                     | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [8c9d16e737](https://linux-hardware.org/?probe=8c9d16e737) | Oct 22, 2023 |
| HP            | Compaq Presario CQ40        | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| Acer          | Aspire A314-23P             | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| HP            | Laptop 14-dq0xxx            | [1f161ae269](https://linux-hardware.org/?probe=1f161ae269) | Oct 16, 2023 |
| Google        | Careena                     | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| HP            | Notebook                    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| Google        | Sasuke                      | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| Insyde        | Braswell                    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| Getac         | X500G3                      | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| HP            | Laptop 14-ck0xxx            | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| ASUSTek       | X451MA                      | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| Mini PC       | Cherry Trail CR             | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| Dell          | Precision 3570              | [fd3441ff1d](https://linux-hardware.org/?probe=fd3441ff1d) | Sep 18, 2023 |
| HP            | 15                          | [03e1207549](https://linux-hardware.org/?probe=03e1207549) | Sep 12, 2023 |
| HP            | 2000                        | [48790bd831](https://linux-hardware.org/?probe=48790bd831) | Sep 09, 2023 |
| HP            | 2000                        | [ce9ba2b7c4](https://linux-hardware.org/?probe=ce9ba2b7c4) | Sep 09, 2023 |
| eMachines     | eM350                       | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Dell          | Latitude 3190               | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| HP            | 255 G2                      | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| ASUSTek       | X75VD                       | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| Packard Be... | EasyNote TJ65               | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| Toshiba       | Satellite P770              | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Google        | Robo                        | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| Compal        | PBL20                       | [ae09076b4e](https://linux-hardware.org/?probe=ae09076b4e) | Aug 22, 2023 |
| HP            | Notebook                    | [11d2993965](https://linux-hardware.org/?probe=11d2993965) | Aug 20, 2023 |
| Google        | Madoo                       | [8eea1017dc](https://linux-hardware.org/?probe=8eea1017dc) | Aug 20, 2023 |
| HP            | Notebook                    | [f6e4865586](https://linux-hardware.org/?probe=f6e4865586) | Aug 19, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| HP            | Pavilion g7                 | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Samsung       | N150P/N210P/N220P           | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Toshiba       | Satellite L875D             | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| Dell          | Inspiron 5720               | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| HP            | Pavilion 15                 | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Dell          | Inspiron 1520               | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Dell          | Inspiron 5576               | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| Dell          | Inspiron N5110              | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Google        | Pyro                        | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| Lenovo        | Z70-80 80FG                 | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Sony          | VPCEB37FD                   | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| Dell          | Precision 3570              | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 240 G3                      | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Lenovo        | G580 2189                   | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Dell          | Latitude E6430              | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| ASUSTek       | X450CC                      | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| Google        | Snappy                      | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| Dell          | XPS 13 9305                 | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| Apple         | MacBook4,1                  | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| HP            | Laptop 15-bs2xx             | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Toshiba       | Satellite C660              | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| GPU Compan... | GWTN116-3                   | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion 15                 | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| HP            | Laptop 17-ak0xx             | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| Dell          | Latitude 7480               | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| MSI           | S12T 3M/S12 3M              | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Latitude E6230              | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Intel         | W7650                       | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Google        | Celes                       | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Positivo      | Q232A                       | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| Acer          | Extensa 2540                | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Acer          | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Acer          | AO756                       | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| Dell          | Latitude E6410              | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Acer          | Aspire ES1-711              | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| ASUSTek       | F50SV                       | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Acer          | Aspire SW3-013              | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Google        | Candy                       | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Acer          | Aspire SW3-013              | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| Apple         | MacBookPro8,1               | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | K70IO                       | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Unknown       | Unknown                     | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| HP            | Pavilion g6                 | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| HP            | Pavilion g6                 | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| Lenovo        | G50-45 80E3                 | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Acer          | Aspire E1-571               | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| OEM           | Unknown                     | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Dell          | Precision 3510              | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Sony          | VPCEB15FM                   | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Lenovo        | G50-30 80G0                 | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Gateway       | Sonic-C                     | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Dell          | Latitude XT                 | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Intel         | W7650                       | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Dell          | Latitude 7480               | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-43-generic | 23        | 6.28%   |
| 5.15.0-56-generic | 14        | 3.83%   |
| 5.15.0-25-generic | 12        | 3.28%   |
| 6.2.0-26-generic  | 10        | 2.73%   |
| 6.2.0-34-generic  | 9         | 2.46%   |
| 5.15.0-58-generic | 9         | 2.46%   |
| 6.5.0-41-generic  | 8         | 2.19%   |
| 6.5.0-18-generic  | 8         | 2.19%   |
| 6.2.0-39-generic  | 8         | 2.19%   |
| 5.19.0-32-generic | 8         | 2.19%   |
| 5.15.0-60-generic | 8         | 2.19%   |
| 5.15.0-30-generic | 8         | 2.19%   |
| 5.19.0-41-generic | 7         | 1.91%   |
| 5.15.0-47-generic | 7         | 1.91%   |
| 5.15.0-46-generic | 7         | 1.91%   |
| 6.5.0-28-generic  | 6         | 1.64%   |
| 6.5.0-27-generic  | 6         | 1.64%   |
| 6.5.0-25-generic  | 6         | 1.64%   |
| 6.5.0-15-generic  | 6         | 1.64%   |
| 5.19.0-35-generic | 6         | 1.64%   |
| 5.15.0-52-generic | 6         | 1.64%   |
| 5.15.0-27-generic | 6         | 1.64%   |
| 6.5.0-45-generic  | 5         | 1.37%   |
| 6.2.0-37-generic  | 5         | 1.37%   |
| 5.19.0-43-generic | 5         | 1.37%   |
| 5.15.0-73-generic | 5         | 1.37%   |
| 5.15.0-53-generic | 5         | 1.37%   |
| 6.8.0-40-generic  | 4         | 1.09%   |
| 6.5.0-35-generic  | 4         | 1.09%   |
| 6.5.0-26-generic  | 4         | 1.09%   |
| 6.5.0-17-generic  | 4         | 1.09%   |
| 6.2.0-36-generic  | 4         | 1.09%   |
| 6.2.0-33-generic  | 4         | 1.09%   |
| 5.19.0-46-generic | 4         | 1.09%   |
| 5.19.0-40-generic | 4         | 1.09%   |
| 5.19.0-38-generic | 4         | 1.09%   |
| 5.15.0-71-generic | 4         | 1.09%   |
| 5.15.0-57-generic | 4         | 1.09%   |
| 5.15.0-50-generic | 4         | 1.09%   |
| 5.15.0-41-generic | 4         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 166       | 48.54%  |
| 6.5.0   | 62        | 18.13%  |
| 6.2.0   | 48        | 14.04%  |
| 5.19.0  | 47        | 13.74%  |
| 6.8.0   | 10        | 2.92%   |
| 6.7.8   | 1         | 0.29%   |
| 6.4.12  | 1         | 0.29%   |
| 6.10.6  | 1         | 0.29%   |
| 6.1.12  | 1         | 0.29%   |
| 6.0.12  | 1         | 0.29%   |
| 5.4.0   | 1         | 0.29%   |
| 5.19.8  | 1         | 0.29%   |
| 5.18.0  | 1         | 0.29%   |
| 5.14.0  | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 166       | 48.54%  |
| 6.5     | 62        | 18.13%  |
| 6.2     | 48        | 14.04%  |
| 5.19    | 48        | 14.04%  |
| 6.8     | 10        | 2.92%   |
| 6.7     | 1         | 0.29%   |
| 6.4     | 1         | 0.29%   |
| 6.10    | 1         | 0.29%   |
| 6.1     | 1         | 0.29%   |
| 6.0     | 1         | 0.29%   |
| 5.4     | 1         | 0.29%   |
| 5.18    | 1         | 0.29%   |
| 5.14    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 331       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXQt       | 319       | 96.37%  |
| LXDE       | 7         | 2.11%   |
| X-Cinnamon | 2         | 0.6%    |
| Lubuntu    | 1         | 0.3%    |
| KDE5       | 1         | 0.3%    |
| i3         | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 323       | 97.58%  |
| Tty     | 7         | 2.11%   |
| Wayland | 1         | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 290       | 86.83%  |
| Unknown | 25        | 7.49%   |
| LightDM | 14        | 4.19%   |
| GDM3    | 5         | 1.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 99        | 29.73%  |
| fr_FR  | 39        | 11.71%  |
| it_IT  | 21        | 6.31%   |
| C      | 20        | 6.01%   |
| en_GB  | 19        | 5.71%   |
| de_DE  | 17        | 5.11%   |
| pt_BR  | 15        | 4.5%    |
| ru_RU  | 13        | 3.9%    |
| es_MX  | 11        | 3.3%    |
| pl_PL  | 9         | 2.7%    |
| en_AG  | 8         | 2.4%    |
| en_CA  | 7         | 2.1%    |
| en_AU  | 5         | 1.5%    |
| tr_TR  | 4         | 1.2%    |
| nl_BE  | 3         | 0.9%    |
| es_ES  | 3         | 0.9%    |
| es_CO  | 3         | 0.9%    |
| es_CL  | 3         | 0.9%    |
| es_AR  | 3         | 0.9%    |
| en_PH  | 3         | 0.9%    |
| sk_SK  | 2         | 0.6%    |
| nl_NL  | 2         | 0.6%    |
| ja_JP  | 2         | 0.6%    |
| fr_CA  | 2         | 0.6%    |
| es_CR  | 2         | 0.6%    |
| zh_CN  | 1         | 0.3%    |
| vi_VN  | 1         | 0.3%    |
| sv_SE  | 1         | 0.3%    |
| ro_RO  | 1         | 0.3%    |
| lzh_TW | 1         | 0.3%    |
| hu_HU  | 1         | 0.3%    |
| fr_CH  | 1         | 0.3%    |
| fi_FI  | 1         | 0.3%    |
| es_UY  | 1         | 0.3%    |
| es_EC  | 1         | 0.3%    |
| en_ZA  | 1         | 0.3%    |
| en_DE  | 1         | 0.3%    |
| el_GR  | 1         | 0.3%    |
| de_CH  | 1         | 0.3%    |
| da_DK  | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 200       | 59.88%  |
| EFI  | 134       | 40.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 260       | 76.7%   |
| Tmpfs   | 56        | 16.52%  |
| Overlay | 19        | 5.6%    |
| Btrfs   | 2         | 0.59%   |
| Xfs     | 1         | 0.29%   |
| Ext2    | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 187       | 55.65%  |
| MBR     | 104       | 30.95%  |
| Unknown | 45        | 13.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 304       | 90.75%  |
| Yes       | 31        | 9.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 248       | 74.03%  |
| Yes       | 87        | 25.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 61        | 18.43%  |
| Lenovo              | 57        | 17.22%  |
| Dell                | 40        | 12.08%  |
| Acer                | 34        | 10.27%  |
| ASUSTek Computer    | 28        | 8.46%   |
| Google              | 13        | 3.93%   |
| Apple               | 9         | 2.72%   |
| Toshiba             | 8         | 2.42%   |
| Sony                | 8         | 2.42%   |
| Unknown             | 8         | 2.42%   |
| Samsung Electronics | 5         | 1.51%   |
| Fujitsu             | 5         | 1.51%   |
| Packard Bell        | 4         | 1.21%   |
| Mediacom            | 4         | 1.21%   |
| MSI                 | 3         | 0.91%   |
| Chuwi               | 3         | 0.91%   |
| Thomson             | 2         | 0.6%    |
| SGIN                | 2         | 0.6%    |
| Positivo            | 2         | 0.6%    |
| Intel               | 2         | 0.6%    |
| HUAWEI              | 2         | 0.6%    |
| Hampoo              | 2         | 0.6%    |
| GPU Company         | 2         | 0.6%    |
| Getac               | 2         | 0.6%    |
| Gateway             | 2         | 0.6%    |
| Digibras            | 2         | 0.6%    |
| TrekStor            | 1         | 0.3%    |
| Teclast             | 1         | 0.3%    |
| SK hynix            | 1         | 0.3%    |
| RWC                 | 1         | 0.3%    |
| Pretech             | 1         | 0.3%    |
| Prestigio           | 1         | 0.3%    |
| Panasonic           | 1         | 0.3%    |
| OEM                 | 1         | 0.3%    |
| Notebook            | 1         | 0.3%    |
| Mini PC             | 1         | 0.3%    |
| Medion              | 1         | 0.3%    |
| Kiano               | 1         | 0.3%    |
| Itautec             | 1         | 0.3%    |
| Insyde              | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 10        | 3.02%   |
| HP Notebook                            | 5         | 1.51%   |
| Dell Latitude E6410                    | 4         | 1.21%   |
| Apple MacBookPro8,1                    | 4         | 1.21%   |
| Mediacom WinPad 11,6 FullHD- WPU11     | 3         | 0.91%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 3         | 0.91%   |
| HP Pavilion 15                         | 3         | 0.91%   |
| HP 2000                                | 3         | 0.91%   |
| Toshiba Satellite C660                 | 2         | 0.6%    |
| Lenovo G50-30 80G0                     | 2         | 0.6%    |
| HP Pavilion g6                         | 2         | 0.6%    |
| HP Pavilion dv6                        | 2         | 0.6%    |
| HP 255 G2                              | 2         | 0.6%    |
| Fujitsu LIFEBOOK A3510                 | 2         | 0.6%    |
| Dell XPS M1330                         | 2         | 0.6%    |
| Dell Latitude 3190                     | 2         | 0.6%    |
| Dell Inspiron N5110                    | 2         | 0.6%    |
| Apple MacBook4,1                       | 2         | 0.6%    |
| Acer Aspire SW3-013                    | 2         | 0.6%    |
| Acer Aspire A314-23P                   | 2         | 0.6%    |
| TrekStor SurfTab wintron 7.0 ST70416-6 | 1         | 0.3%    |
| Toshiba Satellite Radius P55W-B        | 1         | 0.3%    |
| Toshiba Satellite Pro S500             | 1         | 0.3%    |
| Toshiba Satellite P770                 | 1         | 0.3%    |
| Toshiba Satellite P70-A                | 1         | 0.3%    |
| Toshiba Satellite L875D                | 1         | 0.3%    |
| Toshiba Satellite L40                  | 1         | 0.3%    |
| Thomson NEO14-4W64                     | 1         | 0.3%    |
| Thomson N14C4WH64                      | 1         | 0.3%    |
| Teclast tPAD                           | 1         | 0.3%    |
| Sony VPCW216AG                         | 1         | 0.3%    |
| Sony VPCEH2E1R                         | 1         | 0.3%    |
| Sony VPCEB3C4R                         | 1         | 0.3%    |
| Sony VPCEB15FM                         | 1         | 0.3%    |
| Sony VGN-TZ21MN_N                      | 1         | 0.3%    |
| Sony VGN-SZ71WN_C                      | 1         | 0.3%    |
| Sony SVF1521NSTB                       | 1         | 0.3%    |
| Sony SVE14A2V1EW                       | 1         | 0.3%    |
| SK hynix HT14CCIC42E                   | 1         | 0.3%    |
| SGIN M15                               | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 25        | 7.55%   |
| Lenovo ThinkPad       | 24        | 7.25%   |
| Lenovo IdeaPad        | 20        | 6.04%   |
| Dell Latitude         | 17        | 5.14%   |
| HP Pavilion           | 14        | 4.23%   |
| Unknown               | 10        | 3.02%   |
| HP Laptop             | 9         | 2.72%   |
| Dell Inspiron         | 9         | 2.72%   |
| Toshiba Satellite     | 8         | 2.42%   |
| HP EliteBook          | 6         | 1.81%   |
| HP Notebook           | 5         | 1.51%   |
| Dell XPS              | 5         | 1.51%   |
| HP ProBook            | 4         | 1.21%   |
| HP 250                | 4         | 1.21%   |
| Fujitsu LIFEBOOK      | 4         | 1.21%   |
| Dell Vostro           | 4         | 1.21%   |
| ASUS VivoBook         | 4         | 1.21%   |
| Apple MacBookPro8     | 4         | 1.21%   |
| Acer Extensa          | 4         | 1.21%   |
| Packard Bell EasyNote | 3         | 0.91%   |
| Mediacom WinPad       | 3         | 0.91%   |
| HP Compaq             | 3         | 0.91%   |
| HP 240                | 3         | 0.91%   |
| HP 2000               | 3         | 0.91%   |
| Dell Precision        | 3         | 0.91%   |
| Lenovo G50-30         | 2         | 0.6%    |
| HP ZBook              | 2         | 0.6%    |
| HP 255                | 2         | 0.6%    |
| HP 15                 | 2         | 0.6%    |
| Chuwi GemiBook        | 2         | 0.6%    |
| Apple MacBook4        | 2         | 0.6%    |
| Acer Swift            | 2         | 0.6%    |
| TrekStor SurfTab      | 1         | 0.3%    |
| Thomson NEO14-4W64    | 1         | 0.3%    |
| Thomson N14C4WH64     | 1         | 0.3%    |
| Teclast tPAD          | 1         | 0.3%    |
| Sony VPCW216AG        | 1         | 0.3%    |
| Sony VPCEH2E1R        | 1         | 0.3%    |
| Sony VPCEB3C4R        | 1         | 0.3%    |
| Sony VPCEB15FM        | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 33        | 9.97%   |
| 2011 | 31        | 9.37%   |
| 2012 | 29        | 8.76%   |
| 2010 | 29        | 8.76%   |
| 2016 | 27        | 8.16%   |
| 2021 | 26        | 7.85%   |
| 2015 | 20        | 6.04%   |
| 2022 | 18        | 5.44%   |
| 2014 | 18        | 5.44%   |
| 2008 | 16        | 4.83%   |
| 2017 | 15        | 4.53%   |
| 2019 | 14        | 4.23%   |
| 2009 | 13        | 3.93%   |
| 2007 | 13        | 3.93%   |
| 2020 | 10        | 3.02%   |
| 2018 | 10        | 3.02%   |
| 2023 | 8         | 2.42%   |
| 2006 | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 331       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 309       | 92.51%  |
| Enabled  | 25        | 7.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 317       | 95.77%  |
| Yes  | 14        | 4.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 127       | 38.02%  |
| 4.01-8.0    | 88        | 26.35%  |
| 1.01-2.0    | 46        | 13.77%  |
| 8.01-16.0   | 29        | 8.68%   |
| 16.01-24.0  | 22        | 6.59%   |
| 2.01-3.0    | 13        | 3.89%   |
| 32.01-64.0  | 5         | 1.5%    |
| 24.01-32.0  | 2         | 0.6%    |
| 64.01-256.0 | 1         | 0.3%    |
| 0.51-1.0    | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 168       | 48.14%  |
| 0.51-1.0  | 73        | 20.92%  |
| 2.01-3.0  | 72        | 20.63%  |
| 3.01-4.0  | 17        | 4.87%   |
| 4.01-8.0  | 15        | 4.3%    |
| 8.01-16.0 | 2         | 0.57%   |
| 0.01-0.5  | 2         | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 272       | 80.95%  |
| 2      | 53        | 15.77%  |
| 3      | 8         | 2.38%   |
| 0      | 3         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 179       | 54.08%  |
| Yes       | 152       | 45.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 261       | 78.14%  |
| No        | 73        | 21.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 307       | 92.75%  |
| No        | 24        | 7.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 66.17%  |
| No        | 113       | 33.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 48        | 14.5%   |
| France       | 40        | 12.08%  |
| Italy        | 28        | 8.46%   |
| Germany      | 28        | 8.46%   |
| Russia       | 20        | 6.04%   |
| Brazil       | 17        | 5.14%   |
| Poland       | 12        | 3.63%   |
| UK           | 11        | 3.32%   |
| Canada       | 11        | 3.32%   |
| Turkey       | 6         | 1.81%   |
| Mexico       | 6         | 1.81%   |
| Netherlands  | 5         | 1.51%   |
| Colombia     | 5         | 1.51%   |
| Belgium      | 5         | 1.51%   |
| Argentina    | 5         | 1.51%   |
| Ukraine      | 4         | 1.21%   |
| Spain        | 4         | 1.21%   |
| Indonesia    | 4         | 1.21%   |
| Hungary      | 4         | 1.21%   |
| Chile        | 4         | 1.21%   |
| Australia    | 4         | 1.21%   |
| Vietnam      | 3         | 0.91%   |
| Sweden       | 3         | 0.91%   |
| Slovakia     | 3         | 0.91%   |
| Portugal     | 3         | 0.91%   |
| Philippines  | 3         | 0.91%   |
| Japan        | 3         | 0.91%   |
| Czechia      | 3         | 0.91%   |
| Costa Rica   | 3         | 0.91%   |
| UAE          | 2         | 0.6%    |
| Thailand     | 2         | 0.6%    |
| Switzerland  | 2         | 0.6%    |
| South Africa | 2         | 0.6%    |
| Romania      | 2         | 0.6%    |
| Peru         | 2         | 0.6%    |
| Pakistan     | 2         | 0.6%    |
| Finland      | 2         | 0.6%    |
| Uruguay      | 1         | 0.3%    |
| Taiwan       | 1         | 0.3%    |
| Serbia       | 1         | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Paris            | 10        | 2.92%   |
| Moscow           | 5         | 1.46%   |
| Santiago         | 4         | 1.17%   |
| Milan            | 4         | 1.17%   |
| Bruhl            | 4         | 1.17%   |
| Rome             | 3         | 0.88%   |
| New York         | 3         | 0.88%   |
| Kyiv             | 3         | 0.88%   |
| Ghent            | 3         | 0.88%   |
| Bogotá          | 3         | 0.88%   |
| Uberlândia      | 2         | 0.58%   |
| St Petersburg    | 2         | 0.58%   |
| Sarospatak       | 2         | 0.58%   |
| Porto Alegre     | 2         | 0.58%   |
| Ottawa           | 2         | 0.58%   |
| Novosibirsk      | 2         | 0.58%   |
| Munich           | 2         | 0.58%   |
| Montreal         | 2         | 0.58%   |
| Minato-ku        | 2         | 0.58%   |
| Milano           | 2         | 0.58%   |
| Lyon             | 2         | 0.58%   |
| Lisbon           | 2         | 0.58%   |
| Lansing          | 2         | 0.58%   |
| Krakow           | 2         | 0.58%   |
| Istanbul         | 2         | 0.58%   |
| Ho Chi Minh City | 2         | 0.58%   |
| Heredia          | 2         | 0.58%   |
| Fortaleza        | 2         | 0.58%   |
| Flushing         | 2         | 0.58%   |
| Eugene           | 2         | 0.58%   |
| Dubai            | 2         | 0.58%   |
| Curitiba         | 2         | 0.58%   |
| Columbus         | 2         | 0.58%   |
| Buffalo          | 2         | 0.58%   |
| Bratislava       | 2         | 0.58%   |
| Zizur Mayor      | 1         | 0.29%   |
| Zevenbergen      | 1         | 0.29%   |
| Zawiercie        | 1         | 0.29%   |
| Zagreb           | 1         | 0.29%   |
| Yoshkar-Ola      | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Unknown                   | 57        | 78     | 15.41%  |
| WDC                       | 44        | 53     | 11.89%  |
| Seagate                   | 39        | 46     | 10.54%  |
| Samsung Electronics       | 34        | 45     | 9.19%   |
| Toshiba                   | 30        | 33     | 8.11%   |
| Kingston                  | 18        | 18     | 4.86%   |
| Hitachi                   | 17        | 21     | 4.59%   |
| SanDisk                   | 14        | 14     | 3.78%   |
| SK hynix                  | 9         | 10     | 2.43%   |
| Micron Technology         | 9         | 10     | 2.43%   |
| HGST                      | 9         | 10     | 2.43%   |
| Crucial                   | 8         | 9      | 2.16%   |
| Unknown                   | 7         | 8      | 1.89%   |
| Intel                     | 6         | 6      | 1.62%   |
| A-DATA Technology         | 5         | 5      | 1.35%   |
| Transcend                 | 4         | 5      | 1.08%   |
| China                     | 4         | 5      | 1.08%   |
| SPCC                      | 3         | 4      | 0.81%   |
| PNY                       | 3         | 3      | 0.81%   |
| NGFF                      | 3         | 3      | 0.81%   |
| Fujitsu                   | 3         | 3      | 0.81%   |
| UMIS                      | 2         | 2      | 0.54%   |
| Silicon Motion            | 2         | 2      | 0.54%   |
| Patriot                   | 2         | 2      | 0.54%   |
| Netac                     | 2         | 2      | 0.54%   |
| LITEON                    | 2         | 2      | 0.54%   |
| GOODRAM                   | 2         | 2      | 0.54%   |
| Apacer                    | 2         | 2      | 0.54%   |
| W800S                     | 1         | 1      | 0.27%   |
| USB3.0                    | 1         | 1      | 0.27%   |
| Teclast                   | 1         | 1      | 0.27%   |
| Team                      | 1         | 1      | 0.27%   |
| SSSTC                     | 1         | 1      | 0.27%   |
| Rogueware                 | 1         | 1      | 0.27%   |
| Plextor                   | 1         | 1      | 0.27%   |
| Phison                    | 1         | 1      | 0.27%   |
| Neo Forza                 | 1         | 1      | 0.27%   |
| MidasForce                | 1         | 1      | 0.27%   |
| Micron/Crucial Technology | 1         | 1      | 0.27%   |
| LITEONIT                  | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  32GB             | 11        | 2.84%   |
| Unknown MMC Card  64GB             | 10        | 2.58%   |
| Kingston SA400S37240G 240GB SSD    | 7         | 1.8%    |
| Unknown                            | 7         | 1.8%    |
| Unknown NCard  32GB                | 5         | 1.29%   |
| Seagate ST9500325AS 500GB          | 5         | 1.29%   |
| SanDisk DF4032  32GB               | 5         | 1.29%   |
| Micron 2450_MTFDKBA512TFK 512GB    | 5         | 1.29%   |
| Unknown SD/MMC/MS PRO 128GB        | 4         | 1.03%   |
| Unknown DA4032  32GB               | 4         | 1.03%   |
| Toshiba MQ01ABD050 500GB           | 4         | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 1.03%   |
| HGST HTS545050A7E680 500GB         | 4         | 1.03%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 3         | 0.77%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 0.77%   |
| Unknown MMC Card  16GB             | 3         | 0.77%   |
| Unknown DA4064  64GB               | 3         | 0.77%   |
| Toshiba MQ01ABF050 500GB           | 3         | 0.77%   |
| Toshiba MQ01ABD100 1TB             | 3         | 0.77%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 0.77%   |
| Samsung SSD 850 EVO 250GB          | 3         | 0.77%   |
| Kingston SV300S37A120G 120GB SSD   | 3         | 0.77%   |
| Crucial CT240BX500SSD1 240GB       | 3         | 0.77%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 2         | 0.52%   |
| WDC WD10SPZX-24Z10 1TB             | 2         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.52%   |
| Unknown SC64G  64GB                | 2         | 0.52%   |
| Unknown SC256  256GB               | 2         | 0.52%   |
| Unknown MMC64G  64GB               | 2         | 0.52%   |
| Unknown Biwin  64GB                | 2         | 0.52%   |
| Toshiba MQ01ABD075 752GB           | 2         | 0.52%   |
| Toshiba MK2576GSX 250GB            | 2         | 0.52%   |
| SPCC Solid State Disk 120GB        | 2         | 0.52%   |
| SK hynix HFM001TD3JX013N 1024GB    | 2         | 0.52%   |
| SK hynix HBG4e  32GB               | 2         | 0.52%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 0.52%   |
| Seagate ST1000LM048-2E7172 1TB     | 2         | 0.52%   |
| Seagate Expansion 1TB              | 2         | 0.52%   |
| Seagate BUP Portable 5TB           | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 45     | 27.14%  |
| WDC                 | 36        | 40     | 25.71%  |
| Toshiba             | 27        | 30     | 19.29%  |
| Hitachi             | 17        | 21     | 12.14%  |
| HGST                | 9         | 10     | 6.43%   |
| Samsung Electronics | 6         | 12     | 4.29%   |
| Unknown             | 4         | 4      | 2.86%   |
| Fujitsu             | 3         | 3      | 2.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 19     | 15.52%  |
| Kingston            | 15        | 15     | 12.93%  |
| SanDisk             | 7         | 7      | 6.03%   |
| Crucial             | 7         | 8      | 6.03%   |
| WDC                 | 5         | 8      | 4.31%   |
| A-DATA Technology   | 5         | 5      | 4.31%   |
| Transcend           | 4         | 5      | 3.45%   |
| Intel               | 4         | 4      | 3.45%   |
| Toshiba             | 3         | 3      | 2.59%   |
| SPCC                | 3         | 4      | 2.59%   |
| PNY                 | 3         | 3      | 2.59%   |
| NGFF                | 3         | 3      | 2.59%   |
| Patriot             | 2         | 2      | 1.72%   |
| Netac               | 2         | 2      | 1.72%   |
| Micron Technology   | 2         | 2      | 1.72%   |
| LITEON              | 2         | 2      | 1.72%   |
| GOODRAM             | 2         | 2      | 1.72%   |
| China               | 2         | 2      | 1.72%   |
| Apacer              | 2         | 2      | 1.72%   |
| W800S               | 1         | 1      | 0.86%   |
| USB3.0              | 1         | 1      | 0.86%   |
| Teclast             | 1         | 1      | 0.86%   |
| Team                | 1         | 1      | 0.86%   |
| SK hynix            | 1         | 2      | 0.86%   |
| Rogueware           | 1         | 1      | 0.86%   |
| Plextor             | 1         | 1      | 0.86%   |
| Neo Forza           | 1         | 1      | 0.86%   |
| MidasForce          | 1         | 1      | 0.86%   |
| LITEONIT            | 1         | 1      | 0.86%   |
| Lexar               | 1         | 1      | 0.86%   |
| Leqixiang           | 1         | 1      | 0.86%   |
| Lenovo              | 1         | 1      | 0.86%   |
| KingSpec            | 1         | 1      | 0.86%   |
| KINGPOWER           | 1         | 1      | 0.86%   |
| Kingmax             | 1         | 1      | 0.86%   |
| Kimtigo             | 1         | 1      | 0.86%   |
| JAMESDONKEY         | 1         | 1      | 0.86%   |
| HUSKY               | 1         | 1      | 0.86%   |
| HS-SSD-C100         | 1         | 1      | 0.86%   |
| Hewlett-Packard     | 1         | 1      | 0.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 138       | 165    | 37.7%   |
| SSD     | 113       | 124    | 30.87%  |
| MMC     | 66        | 89     | 18.03%  |
| NVMe    | 43        | 49     | 11.75%  |
| Unknown | 6         | 9      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 239       | 283    | 66.39%  |
| MMC  | 66        | 89     | 18.33%  |
| NVMe | 43        | 49     | 11.94%  |
| SAS  | 12        | 15     | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 188       | 214    | 75.2%   |
| 0.51-1.0   | 56        | 69     | 22.4%   |
| 1.01-2.0   | 4         | 4      | 1.6%    |
| 4.01-10.0  | 2         | 2      | 0.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 123       | 36.39%  |
| 251-500        | 77        | 22.78%  |
| 501-1000       | 36        | 10.65%  |
| 51-100         | 36        | 10.65%  |
| 1-20           | 29        | 8.58%   |
| 21-50          | 24        | 7.1%    |
| More than 3000 | 5         | 1.48%   |
| 1001-2000      | 3         | 0.89%   |
| Unknown        | 3         | 0.89%   |
| 2001-3000      | 2         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 176       | 50.72%  |
| 21-50          | 74        | 21.33%  |
| 51-100         | 37        | 10.66%  |
| 101-250        | 29        | 8.36%   |
| 251-500        | 15        | 4.32%   |
| 501-1000       | 5         | 1.44%   |
| 1001-2000      | 4         | 1.15%   |
| More than 3000 | 3         | 0.86%   |
| Unknown        | 3         | 0.86%   |
| 2001-3000      | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 4      | 8.51%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 4.26%   |
| Seagate ST9500325AS 500GB          | 2         | 2      | 4.26%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 4.26%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 2.13%   |
| WDC WD5000BPVT-75HXZT1 500GB       | 1         | 1      | 2.13%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 2.13%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 2.13%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 2.13%   |
| WDC WD10SPCX-21KHST0 1TB           | 1         | 1      | 2.13%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 2.13%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 2.13%   |
| Transcend TS256GSSD720 256GB       | 1         | 1      | 2.13%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 2.13%   |
| Toshiba MK6459GSXP 640GB           | 1         | 1      | 2.13%   |
| Toshiba MK2556GSY 250GB            | 1         | 1      | 2.13%   |
| Toshiba MK1652GSX 160GB            | 1         | 1      | 2.13%   |
| Seagate ST9500420AS 500GB          | 1         | 1      | 2.13%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 2.13%   |
| Seagate ST640LM000 HM641JI 640GB   | 1         | 1      | 2.13%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 1      | 2.13%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 2.13%   |
| Seagate ST320LT012-9WS14C 320GB    | 1         | 1      | 2.13%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 2.13%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 2.13%   |
| Seagate ST1000DM003-1SB102 1TB     | 1         | 1      | 2.13%   |
| Samsung Electronics HM121HI 120GB  | 1         | 6      | 2.13%   |
| Plextor PX-128M6M 128GB SSD        | 1         | 1      | 2.13%   |
| NGFF 2280 512GB SSD                | 1         | 1      | 2.13%   |
| Kingmax SSD 120GB                  | 1         | 1      | 2.13%   |
| Intel SSDSC2KW512G8 512GB          | 1         | 1      | 2.13%   |
| Intel SSDSA2M080G2LE 80GB          | 1         | 1      | 2.13%   |
| Hitachi HTS723216L9SA60 160GB      | 1         | 1      | 2.13%   |
| Hitachi HTS722080K9SA00 80GB       | 1         | 1      | 2.13%   |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 2.13%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 2.13%   |
| Hitachi HTS542516K9SA00 160GB      | 1         | 1      | 2.13%   |
| HGST HTS725032A7E630 320GB         | 1         | 1      | 2.13%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 2.13%   |
| Fujitsu MHY2120BH 120GB            | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 17     | 36.17%  |
| WDC                 | 8         | 8      | 17.02%  |
| Toshiba             | 6         | 6      | 12.77%  |
| Hitachi             | 5         | 5      | 10.64%  |
| Intel               | 2         | 2      | 4.26%   |
| HGST                | 2         | 2      | 4.26%   |
| Transcend           | 1         | 1      | 2.13%   |
| Samsung Electronics | 1         | 6      | 2.13%   |
| Plextor             | 1         | 1      | 2.13%   |
| NGFF                | 1         | 1      | 2.13%   |
| Kingmax             | 1         | 1      | 2.13%   |
| Fujitsu             | 1         | 1      | 2.13%   |
| Apacer              | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 17     | 42.5%   |
| WDC                 | 8         | 8      | 20%     |
| Toshiba             | 6         | 6      | 15%     |
| Hitachi             | 5         | 5      | 12.5%   |
| HGST                | 2         | 2      | 5%      |
| Samsung Electronics | 1         | 6      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 45     | 85.11%  |
| SSD  | 7         | 7      | 14.89%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 176       | 243    | 50.57%  |
| Works    | 125       | 141    | 35.92%  |
| Malfunc  | 47        | 52     | 13.51%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 229       | 72.01%  |
| AMD                              | 43        | 13.52%  |
| Samsung Electronics              | 10        | 3.14%   |
| Micron Technology                | 8         | 2.52%   |
| SK hynix                         | 5         | 1.57%   |
| SanDisk                          | 5         | 1.57%   |
| Nvidia                           | 4         | 1.26%   |
| Kingston Technology Company      | 3         | 0.94%   |
| Union Memory (Shenzhen)          | 2         | 0.63%   |
| Silicon Motion                   | 2         | 0.63%   |
| Micron/Crucial Technology        | 2         | 0.63%   |
| Solid State Storage Technology   | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Silicon Image                    | 1         | 0.31%   |
| Phison Electronics               | 1         | 0.31%   |
| KIOXIA                           | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 35        | 10.06%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 32        | 9.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 18        | 5.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 4.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 15        | 4.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 4.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 13        | 3.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 3.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 12        | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 2.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 10        | 2.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 2.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8         | 2.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 1.72%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 6         | 1.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 1.72%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 1.15%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.15%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 0.86%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.57%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.57%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                             | 2         | 0.57%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 2         | 0.57%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 0.57%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 0.57%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.57%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 2         | 0.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 252       | 74.34%  |
| NVMe | 42        | 12.39%  |
| IDE  | 30        | 8.85%   |
| RAID | 15        | 4.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 277       | 83.69%  |
| AMD    | 54        | 16.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 9         | 2.72%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 8         | 2.42%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 2.11%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 1.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 1.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.51%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 5         | 1.51%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 1.51%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 5         | 1.51%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 4         | 1.21%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.21%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 1.21%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 1.21%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 1.21%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 4         | 1.21%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 1.21%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 1.21%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 4         | 1.21%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 4         | 1.21%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 3         | 0.91%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 3         | 0.91%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 3         | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.91%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.91%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.91%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 0.91%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.91%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.91%   |
| Intel Celeron N4120 CPU @ 1.10GHz             | 3         | 0.91%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 3         | 0.91%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.91%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.91%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.91%   |
| AMD E-300 APU with Radeon HD Graphics         | 3         | 0.91%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 3         | 0.91%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 0.6%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.6%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.6%    |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 2         | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 68        | 20.54%  |
| Intel Celeron           | 64        | 19.34%  |
| Intel Core i7           | 30        | 9.06%   |
| Intel Core i3           | 29        | 8.76%   |
| Intel Atom              | 26        | 7.85%   |
| Intel Core 2 Duo        | 25        | 7.55%   |
| Intel Pentium           | 11        | 3.32%   |
| Other                   | 10        | 3.02%   |
| AMD A6                  | 8         | 2.42%   |
| AMD Ryzen 7             | 6         | 1.81%   |
| AMD E1                  | 6         | 1.81%   |
| AMD E                   | 6         | 1.81%   |
| AMD Ryzen 5             | 5         | 1.51%   |
| Intel Pentium Dual-Core | 4         | 1.21%   |
| Intel Core 2            | 4         | 1.21%   |
| AMD E2                  | 4         | 1.21%   |
| Intel Pentium Dual      | 3         | 0.91%   |
| AMD A8                  | 3         | 0.91%   |
| AMD A4                  | 3         | 0.91%   |
| AMD A10                 | 3         | 0.91%   |
| Intel Genuine           | 2         | 0.6%    |
| AMD C-60                | 2         | 0.6%    |
| AMD Athlon              | 2         | 0.6%    |
| Intel Pentium Silver    | 1         | 0.3%    |
| Intel Celeron Dual-Core | 1         | 0.3%    |
| AMD Sempron             | 1         | 0.3%    |
| AMD Ryzen 9             | 1         | 0.3%    |
| AMD Ryzen 7 PRO         | 1         | 0.3%    |
| AMD Athlon II Dual-Core | 1         | 0.3%    |
| AMD Athlon II           | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 222       | 67.07%  |
| 4      | 82        | 24.77%  |
| 1      | 10        | 3.02%   |
| 8      | 8         | 2.42%   |
| 6      | 4         | 1.21%   |
| 10     | 3         | 0.91%   |
| 14     | 1         | 0.3%    |
| 12     | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 331       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 171       | 51.66%  |
| 2      | 160       | 48.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 331       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 183       | 54.79%  |
| 0x306a9    | 18        | 5.39%   |
| 0x206a7    | 12        | 3.59%   |
| 0x406c3    | 8         | 2.4%    |
| 0x0700010f | 8         | 2.4%    |
| 0x706a8    | 7         | 2.1%    |
| 0x05000119 | 6         | 1.8%    |
| 0x6fd      | 5         | 1.5%    |
| 0x406c4    | 5         | 1.5%    |
| 0x30678    | 5         | 1.5%    |
| 0x20655    | 5         | 1.5%    |
| 0x1067a    | 5         | 1.5%    |
| 0x40651    | 4         | 1.2%    |
| 0x0a50000c | 4         | 1.2%    |
| 0x806ec    | 3         | 0.9%    |
| 0x806ea    | 3         | 0.9%    |
| 0x706a1    | 3         | 0.9%    |
| 0x506c9    | 3         | 0.9%    |
| 0x406e3    | 3         | 0.9%    |
| 0x07030105 | 3         | 0.9%    |
| 0x06006705 | 3         | 0.9%    |
| 0x906c0    | 2         | 0.6%    |
| 0x906a4    | 2         | 0.6%    |
| 0x806c1    | 2         | 0.6%    |
| 0x706e5    | 2         | 0.6%    |
| 0x306c3    | 2         | 0.6%    |
| 0x106ca    | 2         | 0.6%    |
| 0x08a00008 | 2         | 0.6%    |
| 0x08608103 | 2         | 0.6%    |
| 0x06006704 | 2         | 0.6%    |
| 0x06001119 | 2         | 0.6%    |
| 0x906ed    | 1         | 0.3%    |
| 0x806eb    | 1         | 0.3%    |
| 0x806e9    | 1         | 0.3%    |
| 0x6fb      | 1         | 0.3%    |
| 0x6fa      | 1         | 0.3%    |
| 0x6f6      | 1         | 0.3%    |
| 0x506e3    | 1         | 0.3%    |
| 0x306d4    | 1         | 0.3%    |
| 0x20652    | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 46        | 13.9%   |
| IvyBridge        | 32        | 9.67%   |
| Westmere         | 26        | 7.85%   |
| SandyBridge      | 26        | 7.85%   |
| KabyLake         | 22        | 6.65%   |
| Penryn           | 21        | 6.34%   |
| Goldmont plus    | 19        | 5.74%   |
| Haswell          | 18        | 5.44%   |
| Core             | 18        | 5.44%   |
| Goldmont         | 11        | 3.32%   |
| Skylake          | 10        | 3.02%   |
| Excavator        | 10        | 3.02%   |
| Jaguar           | 9         | 2.72%   |
| Bobcat           | 9         | 2.72%   |
| Unknown          | 9         | 2.72%   |
| Bonnell          | 7         | 2.11%   |
| Zen 3            | 6         | 1.81%   |
| Broadwell        | 6         | 1.81%   |
| Alderlake Hybrid | 5         | 1.51%   |
| Puma             | 4         | 1.21%   |
| Piledriver       | 4         | 1.21%   |
| Tremont          | 3         | 0.91%   |
| TigerLake        | 3         | 0.91%   |
| IceLake          | 3         | 0.91%   |
| K10              | 2         | 0.6%    |
| K8 & K10 hybrid  | 1         | 0.3%    |
| Gracemont        | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 256       | 67.9%   |
| AMD    | 75        | 19.89%  |
| Nvidia | 46        | 12.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 8%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29        | 7.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 6.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 5.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 4.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 4.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 3%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 3%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 3%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3%      |
| Intel HD Graphics 500                                                                    | 11        | 2.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 1.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.5%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 6         | 1.5%    |
| Intel UHD Graphics 620                                                                   | 5         | 1.25%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.25%   |
| AMD Lucienne                                                                             | 5         | 1.25%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1%      |
| Intel HD Graphics 620                                                                    | 4         | 1%      |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 1%      |
| AMD Mendocino                                                                            | 4         | 1%      |
| AMD Kabini [Radeon HD 8210]                                                              | 4         | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1%      |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 3         | 0.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.75%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.75%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 0.75%   |
| Nvidia GT218M [GeForce 310M]                                                             | 2         | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.5%    |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 0.5%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.5%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.5%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 208       | 62.65%  |
| 1 x AMD        | 49        | 14.76%  |
| Intel + Nvidia | 28        | 8.43%   |
| 1 x Nvidia     | 16        | 4.82%   |
| Intel + AMD    | 15        | 4.52%   |
| 2 x AMD        | 9         | 2.71%   |
| Other          | 5         | 1.51%   |
| AMD + Nvidia   | 2         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 317       | 95.77%  |
| Proprietary | 10        | 3.02%   |
| Unknown     | 4         | 1.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 256       | 76.65%  |
| 0.01-0.5   | 42        | 12.57%  |
| 1.01-2.0   | 18        | 5.39%   |
| 0.51-1.0   | 11        | 3.29%   |
| 3.01-4.0   | 4         | 1.2%    |
| 5.01-6.0   | 2         | 0.6%    |
| 2.01-3.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 74        | 21.76%  |
| LG Display              | 59        | 17.35%  |
| BOE                     | 50        | 14.71%  |
| Chimei Innolux          | 37        | 10.88%  |
| Samsung Electronics     | 36        | 10.59%  |
| Apple                   | 10        | 2.94%   |
| Lenovo                  | 9         | 2.65%   |
| Chi Mei Optoelectronics | 7         | 2.06%   |
| Sharp                   | 6         | 1.76%   |
| CPT                     | 5         | 1.47%   |
| Acer                    | 5         | 1.47%   |
| Toshiba                 | 4         | 1.18%   |
| Goldstar                | 4         | 1.18%   |
| LG Philips              | 3         | 0.88%   |
| Hewlett-Packard         | 3         | 0.88%   |
| Dell                    | 3         | 0.88%   |
| BenQ                    | 3         | 0.88%   |
| InnoLux Display         | 2         | 0.59%   |
| InfoVision              | 2         | 0.59%   |
| Vizio                   | 1         | 0.29%   |
| ViewSonic               | 1         | 0.29%   |
| Sony                    | 1         | 0.29%   |
| Philips                 | 1         | 0.29%   |
| PANDA                   | 1         | 0.29%   |
| Panasonic               | 1         | 0.29%   |
| LLL                     | 1         | 0.29%   |
| KDC                     | 1         | 0.29%   |
| JVC                     | 1         | 0.29%   |
| JDI                     | 1         | 0.29%   |
| Insignia                | 1         | 0.29%   |
| HKC                     | 1         | 0.29%   |
| HannStar                | 1         | 0.29%   |
| CS_                     | 1         | 0.29%   |
| CMN                     | 1         | 0.29%   |
| ASUSTek Computer        | 1         | 0.29%   |
| AOC                     | 1         | 0.29%   |
| Ancor Communications    | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 6         | 1.76%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 1.47%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 4         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 1.18%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 4         | 1.18%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.88%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 3         | 0.88%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.88%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.88%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.88%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.88%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 2         | 0.59%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.59%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 2         | 0.59%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.59%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch              | 2         | 0.59%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.59%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.59%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                    | 2         | 0.59%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.59%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                     | 2         | 0.59%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO243C 1366x768 309x173mm 13.9-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 2         | 0.59%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 2         | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 160       | 48.34%  |
| 1920x1080 (FHD)    | 77        | 23.26%  |
| 1280x800 (WXGA)    | 36        | 10.88%  |
| 1600x900 (HD+)     | 24        | 7.25%   |
| 3840x2160 (4K)     | 8         | 2.42%   |
| 2560x1440 (QHD)    | 4         | 1.21%   |
| 1440x900 (WXGA+)   | 4         | 1.21%   |
| 3200x1800 (QHD+)   | 2         | 0.6%    |
| 2160x1440          | 2         | 0.6%    |
| 1920x1200 (WUXGA)  | 2         | 0.6%    |
| 1680x1050 (WSXGA+) | 2         | 0.6%    |
| 1024x600           | 2         | 0.6%    |
| 3000x2000          | 1         | 0.3%    |
| 2560x1080          | 1         | 0.3%    |
| 1920x540           | 1         | 0.3%    |
| 1920x1280          | 1         | 0.3%    |
| 1528x1222          | 1         | 0.3%    |
| 1400x1050          | 1         | 0.3%    |
| 1360x768           | 1         | 0.3%    |
| 1280x1024 (SXGA)   | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 127       | 37.35%  |
| 14      | 54        | 15.88%  |
| 13      | 48        | 14.12%  |
| 11      | 24        | 7.06%   |
| 17      | 22        | 6.47%   |
| 12      | 17        | 5%      |
| 27      | 6         | 1.76%   |
| 24      | 6         | 1.76%   |
| 10      | 6         | 1.76%   |
| 23      | 4         | 1.18%   |
| 21      | 4         | 1.18%   |
| 19      | 3         | 0.88%   |
| 84      | 2         | 0.59%   |
| 72      | 2         | 0.59%   |
| 31      | 2         | 0.59%   |
| 28      | 2         | 0.59%   |
| Unknown | 2         | 0.59%   |
| 60      | 1         | 0.29%   |
| 54      | 1         | 0.29%   |
| 44      | 1         | 0.29%   |
| 42      | 1         | 0.29%   |
| 26      | 1         | 0.29%   |
| 22      | 1         | 0.29%   |
| 18      | 1         | 0.29%   |
| 16      | 1         | 0.29%   |
| 9       | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 204       | 60.18%  |
| 201-300     | 69        | 20.35%  |
| 351-400     | 26        | 7.67%   |
| 501-600     | 16        | 4.72%   |
| 401-500     | 8         | 2.36%   |
| 601-700     | 5         | 1.47%   |
| 1501-2000   | 4         | 1.18%   |
| 1001-1500   | 2         | 0.59%   |
| 901-1000    | 2         | 0.59%   |
| Unknown     | 2         | 0.59%   |
| 101-200     | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 259       | 82.75%  |
| 16/10   | 42        | 13.42%  |
| 3/2     | 7         | 2.24%   |
| 4/3     | 2         | 0.64%   |
| 5/4     | 1         | 0.32%   |
| 21/9    | 1         | 0.32%   |
| Unknown | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 126       | 37.06%  |
| 81-90          | 92        | 27.06%  |
| 51-60          | 24        | 7.06%   |
| 121-130        | 20        | 5.88%   |
| 61-70          | 17        | 5%      |
| 201-250        | 13        | 3.82%   |
| 71-80          | 9         | 2.65%   |
| 41-50          | 7         | 2.06%   |
| 301-350        | 7         | 2.06%   |
| More than 1000 | 6         | 1.76%   |
| 351-500        | 3         | 0.88%   |
| 251-300        | 3         | 0.88%   |
| 151-200        | 3         | 0.88%   |
| 131-140        | 3         | 0.88%   |
| 501-1000       | 2         | 0.59%   |
| 91-100         | 2         | 0.59%   |
| Unknown        | 2         | 0.59%   |
| 141-150        | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 164       | 48.96%  |
| 121-160       | 104       | 31.04%  |
| 51-100        | 44        | 13.13%  |
| 161-240       | 15        | 4.48%   |
| 1-50          | 4         | 1.19%   |
| More than 240 | 2         | 0.6%    |
| Unknown       | 2         | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 296       | 88.89%  |
| 2     | 31        | 9.31%   |
| 0     | 5         | 1.5%    |
| 3     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 170       | 33.33%  |
| Intel                             | 125       | 24.51%  |
| Qualcomm Atheros                  | 84        | 16.47%  |
| Broadcom                          | 44        | 8.63%   |
| Marvell Technology Group          | 11        | 2.16%   |
| Ralink                            | 8         | 1.57%   |
| MediaTek                          | 8         | 1.57%   |
| Broadcom Limited                  | 7         | 1.37%   |
| Samsung Electronics               | 6         | 1.18%   |
| ASIX Electronics                  | 5         | 0.98%   |
| Xiaomi                            | 4         | 0.78%   |
| TP-Link                           | 4         | 0.78%   |
| Ralink Technology                 | 4         | 0.78%   |
| OPPO Electronics                  | 3         | 0.59%   |
| Nvidia                            | 3         | 0.59%   |
| Dell                              | 3         | 0.59%   |
| Qualcomm Atheros Communications   | 2         | 0.39%   |
| Qualcomm                          | 2         | 0.39%   |
| JMicron Technology                | 2         | 0.39%   |
| ASUSTek Computer                  | 2         | 0.39%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.2%    |
| Spreadtrum Communications         | 1         | 0.2%    |
| Sierra Wireless                   | 1         | 0.2%    |
| NetGear                           | 1         | 0.2%    |
| Motorola PCS                      | 1         | 0.2%    |
| Microsoft                         | 1         | 0.2%    |
| Micro Star International          | 1         | 0.2%    |
| ICS Advent                        | 1         | 0.2%    |
| Fibocom                           | 1         | 0.2%    |
| Ericsson Business Mobile Networks | 1         | 0.2%    |
| Dresden Elektronik                | 1         | 0.2%    |
| DisplayLink                       | 1         | 0.2%    |
| D-Link                            | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 75        | 12.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 47        | 7.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 20        | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 2.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12        | 1.95%   |
| Intel Wireless 7260                                                    | 12        | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 1.95%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 1.95%   |
| Intel Wireless 7265                                                    | 11        | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 10        | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 9         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 1.3%    |
| Intel Wireless 8265 / 8275                                             | 8         | 1.3%    |
| Realtek 802.11n WLAN Adapter                                           | 7         | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 7         | 1.14%   |
| Intel Centrino Advanced-N 6200                                         | 7         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 6         | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 6         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.98%   |
| Intel Wireless 3165                                                    | 6         | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 6         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 5         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 5         | 0.81%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 5         | 0.81%   |
| Intel Centrino Ultimate-N 6300                                         | 5         | 0.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 4         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 4         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 4         | 0.65%   |
| Intel Wireless 8260                                                    | 4         | 0.65%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 0.65%   |
| Intel Centrino Wireless-N 2230                                         | 4         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 116       | 35.37%  |
| Qualcomm Atheros                | 75        | 22.87%  |
| Realtek Semiconductor           | 67        | 20.43%  |
| Broadcom                        | 32        | 9.76%   |
| Ralink                          | 8         | 2.44%   |
| MediaTek                        | 8         | 2.44%   |
| Ralink Technology               | 4         | 1.22%   |
| TP-Link                         | 3         | 0.91%   |
| Broadcom Limited                | 3         | 0.91%   |
| Qualcomm Atheros Communications | 2         | 0.61%   |
| Dell                            | 2         | 0.61%   |
| ASUSTek Computer                | 2         | 0.61%   |
| Sierra Wireless                 | 1         | 0.3%    |
| NetGear                         | 1         | 0.3%    |
| Microsoft                       | 1         | 0.3%    |
| Micro Star International        | 1         | 0.3%    |
| Fibocom                         | 1         | 0.3%    |
| D-Link                          | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 20        | 6.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 4.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 14        | 4.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 3.63%   |
| Intel Wireless 7260                                            | 12        | 3.63%   |
| Intel Wireless 7265                                            | 11        | 3.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 10        | 3.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 2.72%   |
| Intel Wireless 8265 / 8275                                     | 8         | 2.42%   |
| Realtek 802.11n WLAN Adapter                                   | 7         | 2.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 7         | 2.11%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 2.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 1.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 1.81%   |
| Intel Wireless 3165                                            | 6         | 1.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 1.81%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 1.51%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 5         | 1.51%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.51%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 1.21%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.21%   |
| Intel Wireless 8260                                            | 4         | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.21%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 1.21%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 1.21%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 4         | 1.21%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 0.91%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 3         | 0.91%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 3         | 0.91%   |
| Intel Wireless 3160                                            | 3         | 0.91%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 0.91%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.91%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 139       | 50%     |
| Intel                      | 52        | 18.71%  |
| Qualcomm Atheros           | 23        | 8.27%   |
| Broadcom                   | 19        | 6.83%   |
| Marvell Technology Group   | 11        | 3.96%   |
| Samsung Electronics        | 5         | 1.8%    |
| ASIX Electronics           | 5         | 1.8%    |
| Xiaomi                     | 4         | 1.44%   |
| Broadcom Limited           | 4         | 1.44%   |
| OPPO Electronics           | 3         | 1.08%   |
| Nvidia                     | 3         | 1.08%   |
| Qualcomm                   | 2         | 0.72%   |
| JMicron Technology         | 2         | 0.72%   |
| ZTE WCDMA Technologies MSM | 1         | 0.36%   |
| TP-Link                    | 1         | 0.36%   |
| Spreadtrum Communications  | 1         | 0.36%   |
| Motorola PCS               | 1         | 0.36%   |
| ICS Advent                 | 1         | 0.36%   |
| DisplayLink                | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 75        | 26.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 47        | 16.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 4.3%    |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 4.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 2.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 2.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 2.15%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 5         | 1.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 1.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 1.43%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 3         | 1.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 1.08%   |
| OPPO OnePlus Nord 4                                                            | 3         | 1.08%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.08%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.72%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.72%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.72%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.72%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 2         | 0.72%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 2         | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.72%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 0.72%   |
| ASIX AX88772B                                                                  | 2         | 0.72%   |
| ZTE WCDMA MSM Unisoc Phone                                                     | 1         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.36%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.36%   |
| Spreadtrum Unisoc Phone                                                        | 1         | 0.36%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 308       | 53.85%  |
| Ethernet | 260       | 45.45%  |
| Modem    | 4         | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 247       | 74.4%   |
| Ethernet | 85        | 25.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 223       | 67.37%  |
| 1     | 75        | 22.66%  |
| 0     | 30        | 9.06%   |
| 3     | 2         | 0.6%    |
| 4     | 1         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 236       | 70.66%  |
| Yes  | 98        | 29.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 32.59%  |
| Realtek Semiconductor           | 34        | 15.18%  |
| Qualcomm Atheros Communications | 25        | 11.16%  |
| Broadcom                        | 16        | 7.14%   |
| Lite-On Technology              | 15        | 6.7%    |
| IMC Networks                    | 11        | 4.91%   |
| Foxconn / Hon Hai               | 9         | 4.02%   |
| Dell                            | 8         | 3.57%   |
| Apple                           | 8         | 3.57%   |
| Ralink                          | 6         | 2.68%   |
| Hewlett-Packard                 | 6         | 2.68%   |
| Cambridge Silicon Radio         | 3         | 1.34%   |
| Alps Electric                   | 3         | 1.34%   |
| Toshiba                         | 2         | 0.89%   |
| Syntek                          | 1         | 0.45%   |
| Qcom                            | 1         | 0.45%   |
| MediaTek                        | 1         | 0.45%   |
| Integrated System Solution      | 1         | 0.45%   |
| ASUSTek Computer                | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 45        | 20%     |
| Realtek Bluetooth Radio                                                             | 23        | 10.22%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 5.33%   |
| Intel AX201 Bluetooth                                                               | 8         | 3.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 3.11%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 2.67%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.67%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 2.67%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.22%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.22%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 1.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.78%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.78%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 1.78%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.33%   |
| Lite-On Wireless_Device                                                             | 3         | 1.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.33%   |
| Intel AX200 Bluetooth                                                               | 3         | 1.33%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.33%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.33%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 1.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 1.33%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.89%   |
| Intel AX211 Bluetooth                                                               | 2         | 0.89%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.89%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.89%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.89%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.89%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.89%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.89%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.44%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.44%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.44%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.44%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 254       | 73.62%  |
| AMD                  | 58        | 16.81%  |
| Nvidia               | 26        | 7.54%   |
| MosArt Semiconductor | 1         | 0.29%   |
| KTMicro              | 1         | 0.29%   |
| JMTek                | 1         | 0.29%   |
| GN Netcom            | 1         | 0.29%   |
| EGO SYStems          | 1         | 0.29%   |
| C-Media Electronics  | 1         | 0.29%   |
| ASUSTek Computer     | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 9.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 6.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 19        | 4.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 4.6%    |
| AMD FCH Azalia Controller                                                                         | 19        | 4.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 18        | 4.36%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 4.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 3.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 16        | 3.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 3.39%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 14        | 3.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.91%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 2.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 11        | 2.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 2.18%   |
| AMD High Definition Audio Controller                                                              | 7         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.45%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.45%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.21%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 0.97%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.97%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.97%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 4         | 0.97%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.73%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.73%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.48%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 64        | 24.71%  |
| SK hynix            | 60        | 23.17%  |
| Micron Technology   | 26        | 10.04%  |
| Unknown             | 25        | 9.65%   |
| Kingston            | 13        | 5.02%   |
| Unknown (ABCD)      | 12        | 4.63%   |
| Nanya Technology    | 9         | 3.47%   |
| Elpida              | 8         | 3.09%   |
| Smart               | 4         | 1.54%   |
| Ramaxel Technology  | 4         | 1.54%   |
| Crucial             | 4         | 1.54%   |
| A-DATA Technology   | 4         | 1.54%   |
| Unknown             | 3         | 1.16%   |
| High Bridge         | 2         | 0.77%   |
| G.Skill             | 2         | 0.77%   |
| fef5                | 2         | 0.77%   |
| Corsair             | 2         | 0.77%   |
| Wilk                | 1         | 0.39%   |
| Transcend           | 1         | 0.39%   |
| Toshiba             | 1         | 0.39%   |
| Timetec             | 1         | 0.39%   |
| Teikon              | 1         | 0.39%   |
| TakeMS              | 1         | 0.39%   |
| PUSKILL             | 1         | 0.39%   |
| PNY                 | 1         | 0.39%   |
| Novatech            | 1         | 0.39%   |
| Kllisre             | 1         | 0.39%   |
| Kingmax             | 1         | 0.39%   |
| HMD                 | 1         | 0.39%   |
| ASint Technology    | 1         | 0.39%   |
| Apacer              | 1         | 0.39%   |
| AMD                 | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 10        | 3.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 2.55%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 4         | 1.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 1.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.46%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 1.09%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 3         | 1.09%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.09%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.09%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.09%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 3         | 1.09%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 3         | 1.09%   |
| Unknown                                                          | 3         | 1.09%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 2         | 0.73%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.73%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 2         | 0.73%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 2         | 0.73%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.73%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.73%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 2         | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.73%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.73%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 2         | 0.73%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.73%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 2         | 0.73%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.73%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 2         | 0.73%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR 800MT/s               | 2         | 0.73%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.73%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 0.73%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 0.73%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 113       | 50.22%  |
| DDR4    | 55        | 24.44%  |
| LPDDR4  | 21        | 9.33%   |
| DDR2    | 16        | 7.11%   |
| SDRAM   | 7         | 3.11%   |
| LPDDR5  | 5         | 2.22%   |
| LPDDR3  | 3         | 1.33%   |
| DDR5    | 2         | 0.89%   |
| Unknown | 2         | 0.89%   |
| DDR     | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 198       | 89.59%  |
| Row Of Chips | 14        | 6.33%   |
| Unknown      | 5         | 2.26%   |
| DIMM         | 4         | 1.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 82        | 33.33%  |
| 8192  | 71        | 28.86%  |
| 2048  | 62        | 25.2%   |
| 1024  | 15        | 6.1%    |
| 16384 | 12        | 4.88%   |
| 32768 | 2         | 0.81%   |
| 12288 | 1         | 0.41%   |
| 512   | 1         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 77        | 32.08%  |
| 2400    | 27        | 11.25%  |
| 3200    | 21        | 8.75%   |
| 1333    | 17        | 7.08%   |
| 2667    | 16        | 6.67%   |
| 1334    | 14        | 5.83%   |
| 667     | 12        | 5%      |
| 1066    | 7         | 2.92%   |
| 1067    | 6         | 2.5%    |
| Unknown | 6         | 2.5%    |
| 3266    | 5         | 2.08%   |
| 6400    | 4         | 1.67%   |
| 2048    | 4         | 1.67%   |
| 1866    | 3         | 1.25%   |
| 975     | 3         | 1.25%   |
| 800     | 3         | 1.25%   |
| 4800    | 2         | 0.83%   |
| 4267    | 2         | 0.83%   |
| 4266    | 2         | 0.83%   |
| 4199    | 2         | 0.83%   |
| 2133    | 2         | 0.83%   |
| 1867    | 2         | 0.83%   |
| 5500    | 1         | 0.42%   |
| 2933    | 1         | 0.42%   |
| 533     | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| HP LaserJet P1102 | 1         | 33.33%  |
| Canon MF3110      | 1         | 33.33%  |
| Brother MFC-7340  | 1         | 33.33%  |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 73        | 27.14%  |
| Realtek Semiconductor                  | 30        | 11.15%  |
| Microdia                               | 22        | 8.18%   |
| Sunplus Innovation Technology          | 17        | 6.32%   |
| Suyin                                  | 12        | 4.46%   |
| IMC Networks                           | 12        | 4.46%   |
| Bison Electronics                      | 12        | 4.46%   |
| Syntek                                 | 11        | 4.09%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 4.09%   |
| Quanta                                 | 10        | 3.72%   |
| Apple                                  | 8         | 2.97%   |
| Alcor Micro                            | 8         | 2.97%   |
| Silicon Motion                         | 7         | 2.6%    |
| Lite-On Technology                     | 5         | 1.86%   |
| Lenovo                                 | 4         | 1.49%   |
| ALi                                    | 4         | 1.49%   |
| Ricoh                                  | 3         | 1.12%   |
| icSpring                               | 3         | 1.12%   |
| Z-Star Microelectronics                | 2         | 0.74%   |
| USB Camera CS                          | 2         | 0.74%   |
| OmniVision Technologies                | 2         | 0.74%   |
| Luxvisions Innotech Limited            | 2         | 0.74%   |
| GEMBIRD                                | 2         | 0.74%   |
| Y Media                                | 1         | 0.37%   |
| SunplusIT                              | 1         | 0.37%   |
| Sonix Technology                       | 1         | 0.37%   |
| Logitech                               | 1         | 0.37%   |
| KYT-221229-A                           | 1         | 0.37%   |
| Cubeternet                             | 1         | 0.37%   |
| Acer                                   | 1         | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 11        | 4.07%   |
| Chicony HD WebCam                                       | 8         | 2.96%   |
| Sunplus HD WebCam                                       | 6         | 2.22%   |
| Chicony HP TrueVision HD Camera                         | 6         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 5         | 1.85%   |
| Silicon Motion 300k Pixel Camera                        | 4         | 1.48%   |
| Realtek Integrated_Webcam_HD                            | 4         | 1.48%   |
| Microdia Integrated Webcam                              | 4         | 1.48%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 1.48%   |
| Chicony HP TrueVision HD                                | 4         | 1.48%   |
| Apple FaceTime HD Camera                                | 4         | 1.48%   |
| Alcor Micro USB 2.0 Camera                              | 4         | 1.48%   |
| Syntek USB Camera Device                                | 3         | 1.11%   |
| Syntek Lenovo EasyCamera                                | 3         | 1.11%   |
| Realtek USB Camera                                      | 3         | 1.11%   |
| Realtek Integrated Webcam HD                            | 3         | 1.11%   |
| Microdia Lenovo EasyCamera                              | 3         | 1.11%   |
| Microdia Integrated_Webcam_HD                           | 3         | 1.11%   |
| Lenovo Integrated Webcam                                | 3         | 1.11%   |
| icSpring camera                                         | 3         | 1.11%   |
| Chicony VGA Webcam                                      | 3         | 1.11%   |
| Chicony FJ Camera                                       | 3         | 1.11%   |
| Chicony EasyCamera                                      | 3         | 1.11%   |
| Chicony ACER HD User Facing                             | 3         | 1.11%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 3         | 1.11%   |
| Bison Lenovo EasyCamera                                 | 3         | 1.11%   |
| Bison Integrated Camera                                 | 3         | 1.11%   |
| ALi WebCam                                              | 3         | 1.11%   |
| Z-Star Webcam                                           | 2         | 0.74%   |
| USB Camera CS USB Camera CS                             | 2         | 0.74%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 0.74%   |
| Silicon Motion WebCam SCB-1100N                         | 2         | 0.74%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870]     | 2         | 0.74%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 0.74%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.74%   |
| Realtek HP Truevision HD                                | 2         | 0.74%   |
| Realtek EasyCamera                                      | 2         | 0.74%   |
| Realtek Asus laptop camera                              | 2         | 0.74%   |
| Quanta HD User Facing                                   | 2         | 0.74%   |
| OmniVision OV2640 Webcam                                | 2         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 31.25%  |
| Upek                       | 6         | 18.75%  |
| AuthenTec                  | 5         | 15.63%  |
| STMicroelectronics         | 4         | 12.5%   |
| Synaptics                  | 3         | 9.38%   |
| Shenzhen Goodix Technology | 2         | 6.25%   |
| LighTuning Technology      | 2         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 6         | 18.75%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 6.25%   |
| AuthenTec AES2810                                      | 2         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 3.13%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 3.13%   |
| Validity Sensors VFS300 Fingerprint Reader             | 1         | 3.13%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 3.13%   |
| Synaptics WBDI                                         | 1         | 3.13%   |
| Synaptics TouchPad                                     | 1         | 3.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 3.13%   |
| LighTuning Fingerprint Reader                          | 1         | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.13%   |
| AuthenTec Fingerprint Sensor                           | 1         | 3.13%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 3.13%   |
| AuthenTec AES1600                                      | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 10        | 47.62%  |
| Alcor Micro           | 6         | 28.57%  |
| O2 Micro              | 2         | 9.52%   |
| Lenovo                | 2         | 9.52%   |
| Gemalto (was Gemplus) | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 23.81%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 23.81%  |
| Broadcom 5880                                                                | 3         | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 9.52%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 9.52%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |
| Broadcom 58200                                                               | 1         | 4.76%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 239       | 72.21%  |
| 1     | 77        | 23.26%  |
| 2     | 13        | 3.93%   |
| 4     | 1         | 0.3%    |
| 3     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 31        | 28.97%  |
| Chipcard              | 20        | 18.69%  |
| Graphics card         | 16        | 14.95%  |
| Bluetooth             | 11        | 10.28%  |
| Camera                | 10        | 9.35%   |
| Net/wireless          | 7         | 6.54%   |
| Storage               | 3         | 2.8%    |
| Multimedia controller | 3         | 2.8%    |
| Dvb card              | 3         | 2.8%    |
| Network               | 2         | 1.87%   |
| Net/ethernet          | 1         | 0.93%   |


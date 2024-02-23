Linux in Philippines - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Philippines.

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

Total: 599

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X450CA                      | [701cfd5c41](https://linux-hardware.org/?probe=701cfd5c41) | Feb 02, 2024 |
| HP            | ProBook 4540s               | [ba6e31a8d3](https://linux-hardware.org/?probe=ba6e31a8d3) | Jan 29, 2024 |
| Valve         | Jupiter                     | [ad91e418c3](https://linux-hardware.org/?probe=ad91e418c3) | Jan 25, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [00c6aa68c6](https://linux-hardware.org/?probe=00c6aa68c6) | Jan 22, 2024 |
| HP            | Laptop 15s-fq4xxx           | [4b0eb86898](https://linux-hardware.org/?probe=4b0eb86898) | Jan 15, 2024 |
| Acer          | Predator PH16-71            | [e2d230f52c](https://linux-hardware.org/?probe=e2d230f52c) | Jan 14, 2024 |
| MSI           | GT62VR 7RE                  | [11a6fc29dd](https://linux-hardware.org/?probe=11a6fc29dd) | Jan 14, 2024 |
| Acer          | Swift SF314-54              | [c947abcab4](https://linux-hardware.org/?probe=c947abcab4) | Jan 11, 2024 |
| Acer          | Aspire V3-471G              | [d96fe50b0e](https://linux-hardware.org/?probe=d96fe50b0e) | Jan 07, 2024 |
| Lenovo        | ThinkPad X270 20HMS22H00    | [302c8659c3](https://linux-hardware.org/?probe=302c8659c3) | Jan 06, 2024 |
| Acer          | Aspire A315-51              | [753ed1e625](https://linux-hardware.org/?probe=753ed1e625) | Jan 05, 2024 |
| Apple         | MacBookPro9,2               | [b301f85af7](https://linux-hardware.org/?probe=b301f85af7) | Jan 04, 2024 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [00e99b0067](https://linux-hardware.org/?probe=00e99b0067) | Jan 02, 2024 |
| Acer          | Predator PH16-71            | [deae7730f2](https://linux-hardware.org/?probe=deae7730f2) | Dec 31, 2023 |
| Acer          | Predator PHN16-71           | [f7d4fcd885](https://linux-hardware.org/?probe=f7d4fcd885) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | [865ecc4a8b](https://linux-hardware.org/?probe=865ecc4a8b) | Dec 27, 2023 |
| Apple         | MacBookAir3,1               | [860a7b9b4c](https://linux-hardware.org/?probe=860a7b9b4c) | Dec 23, 2023 |
| Dell          | Inspiron 3501               | [2fcf77279a](https://linux-hardware.org/?probe=2fcf77279a) | Dec 23, 2023 |
| Acer          | Predator PH16-71            | [403fcc076f](https://linux-hardware.org/?probe=403fcc076f) | Dec 21, 2023 |
| Lenovo        | ThinkPad X220 4286AQ7       | [ffea6e3dbe](https://linux-hardware.org/?probe=ffea6e3dbe) | Dec 17, 2023 |
| Lenovo        | ThinkPad X220 4286AQ7       | [a09d44706c](https://linux-hardware.org/?probe=a09d44706c) | Dec 17, 2023 |
| Acer          | Aspire A314-35              | [ece32548bb](https://linux-hardware.org/?probe=ece32548bb) | Dec 12, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [dfe75293a5](https://linux-hardware.org/?probe=dfe75293a5) | Dec 12, 2023 |
| Unknown       | Unknown                     | [130b4fa28a](https://linux-hardware.org/?probe=130b4fa28a) | Dec 09, 2023 |
| Acer          | Predator PH16-71            | [234562596d](https://linux-hardware.org/?probe=234562596d) | Dec 09, 2023 |
| Valve         | Jupiter                     | [326f2a7596](https://linux-hardware.org/?probe=326f2a7596) | Dec 08, 2023 |
| Google        | Chell                       | [b19b6452e3](https://linux-hardware.org/?probe=b19b6452e3) | Dec 07, 2023 |
| MSI           | CX62 7QL                    | [33cd9ad75d](https://linux-hardware.org/?probe=33cd9ad75d) | Dec 07, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [997c250e85](https://linux-hardware.org/?probe=997c250e85) | Dec 05, 2023 |
| Acer          | Aspire E5-473               | [f3b2c01ef7](https://linux-hardware.org/?probe=f3b2c01ef7) | Dec 01, 2023 |
| ASUSTek       | GL553VW                     | [dba63ed53c](https://linux-hardware.org/?probe=dba63ed53c) | Nov 26, 2023 |
| Gigabyte      | B550M AORUS ELITE AX        | [6ec8b667b0](https://linux-hardware.org/?probe=6ec8b667b0) | Nov 23, 2023 |
| Gigabyte      | B550M AORUS ELITE AX        | [4e71e8e7b7](https://linux-hardware.org/?probe=4e71e8e7b7) | Nov 20, 2023 |
| Acer          | TMP215-52-32DT              | [582fca0005](https://linux-hardware.org/?probe=582fca0005) | Nov 15, 2023 |
| Acer          | TMP215-52-32DT              | [1aec98605f](https://linux-hardware.org/?probe=1aec98605f) | Nov 15, 2023 |
| Acer          | Predator PH16-71            | [5fcac9e7de](https://linux-hardware.org/?probe=5fcac9e7de) | Nov 08, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| HP            | ProBook 4330s               | [046f30b044](https://linux-hardware.org/?probe=046f30b044) | Nov 03, 2023 |
| HP            | ProBook 4330s               | [0d3ba579b4](https://linux-hardware.org/?probe=0d3ba579b4) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | [56bbf7c0bb](https://linux-hardware.org/?probe=56bbf7c0bb) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | [249ea48334](https://linux-hardware.org/?probe=249ea48334) | Oct 30, 2023 |
| Valve         | Jupiter                     | [3e84a41deb](https://linux-hardware.org/?probe=3e84a41deb) | Oct 28, 2023 |
| Lenovo        | Flex 2-14 20404             | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| Valve         | Jupiter                     | [a524108535](https://linux-hardware.org/?probe=a524108535) | Oct 26, 2023 |
| Valve         | Jupiter                     | [ae2eee1640](https://linux-hardware.org/?probe=ae2eee1640) | Oct 26, 2023 |
| Unknown       | Unknown                     | [251baa33d7](https://linux-hardware.org/?probe=251baa33d7) | Oct 23, 2023 |
| Unknown       | Unknown                     | [a06cdb13fc](https://linux-hardware.org/?probe=a06cdb13fc) | Oct 23, 2023 |
| Lenovo        | XiaoXin Air 15IKBR 81GY     | [755849af68](https://linux-hardware.org/?probe=755849af68) | Oct 20, 2023 |
| Acer          | Aspire A514-55              | [f25a7d5b9e](https://linux-hardware.org/?probe=f25a7d5b9e) | Oct 18, 2023 |
| Unknown       | Unknown                     | [6bb8ddbcda](https://linux-hardware.org/?probe=6bb8ddbcda) | Oct 14, 2023 |
| HP            | EliteBook 8460p             | [80b914414e](https://linux-hardware.org/?probe=80b914414e) | Oct 07, 2023 |
| Lenovo        | ThinkPad T450 20BUA007SG    | [85af04a1cc](https://linux-hardware.org/?probe=85af04a1cc) | Oct 03, 2023 |
| Toshiba       | Satellite C55-C             | [e9ce3eada7](https://linux-hardware.org/?probe=e9ce3eada7) | Oct 02, 2023 |
| Acer          | Predator PH16-71            | [a07278dc43](https://linux-hardware.org/?probe=a07278dc43) | Oct 01, 2023 |
| HUAWEI        | BOHB-WAX9                   | [054707cbd2](https://linux-hardware.org/?probe=054707cbd2) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7c547aa37a](https://linux-hardware.org/?probe=7c547aa37a) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [eef80142a9](https://linux-hardware.org/?probe=eef80142a9) | Sep 24, 2023 |
| ASUSTek       | X451MA                      | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| Acer          | Aspire A314-35              | [5f584efb57](https://linux-hardware.org/?probe=5f584efb57) | Sep 19, 2023 |
| Valve         | Jupiter                     | [2c3f76de4d](https://linux-hardware.org/?probe=2c3f76de4d) | Sep 18, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | [e60aae9a1b](https://linux-hardware.org/?probe=e60aae9a1b) | Sep 17, 2023 |
| Acer          | Aspire E5-473G              | [936a48fb5a](https://linux-hardware.org/?probe=936a48fb5a) | Sep 16, 2023 |
| Dell          | Inspiron 3501               | [c0723e7eae](https://linux-hardware.org/?probe=c0723e7eae) | Sep 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [426914b6e5](https://linux-hardware.org/?probe=426914b6e5) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [820a13876a](https://linux-hardware.org/?probe=820a13876a) | Sep 14, 2023 |
| Acer          | Predator PH16-71            | [f0b0cc7736](https://linux-hardware.org/?probe=f0b0cc7736) | Sep 09, 2023 |
| Dell          | Precision M6800             | [b50e95f460](https://linux-hardware.org/?probe=b50e95f460) | Sep 07, 2023 |
| HUAWEI        | BoDE-WXX9                   | [06a65572fe](https://linux-hardware.org/?probe=06a65572fe) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [af78cafb1a](https://linux-hardware.org/?probe=af78cafb1a) | Sep 01, 2023 |
| HP            | Laptop 14-bs1xx             | [335b828114](https://linux-hardware.org/?probe=335b828114) | Aug 31, 2023 |
| ASUSTek       | K55VD                       | [7bdfc94045](https://linux-hardware.org/?probe=7bdfc94045) | Aug 27, 2023 |
| Acer          | Predator PH16-71            | [ef267bc627](https://linux-hardware.org/?probe=ef267bc627) | Aug 26, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [f429d18938](https://linux-hardware.org/?probe=f429d18938) | Aug 23, 2023 |
| HUAWEI        | BoDE-WXX9                   | [d23fefd908](https://linux-hardware.org/?probe=d23fefd908) | Aug 22, 2023 |
| Valve         | Jupiter                     | [692495c520](https://linux-hardware.org/?probe=692495c520) | Aug 20, 2023 |
| ASUSTek       | X510UQ                      | [169472a4fa](https://linux-hardware.org/?probe=169472a4fa) | Aug 19, 2023 |
| HUAWEI        | BoDE-WXX9                   | [0a747fe196](https://linux-hardware.org/?probe=0a747fe196) | Aug 19, 2023 |
| Acer          | Aspire 7560G                | [a4a5ddf1b0](https://linux-hardware.org/?probe=a4a5ddf1b0) | Aug 13, 2023 |
| MSI           | GT62VR 7RE                  | [105839bee0](https://linux-hardware.org/?probe=105839bee0) | Aug 13, 2023 |
| Valve         | Jupiter                     | [c34cb54bc8](https://linux-hardware.org/?probe=c34cb54bc8) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [22fc28c382](https://linux-hardware.org/?probe=22fc28c382) | Aug 11, 2023 |
| HUAWEI        | KLVL-WXXW                   | [1a3b5297dd](https://linux-hardware.org/?probe=1a3b5297dd) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | [18208500ee](https://linux-hardware.org/?probe=18208500ee) | Aug 08, 2023 |
| HP            | ProBook 650 G1              | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Acer          | Aspire V3-371               | [5d5a4b489b](https://linux-hardware.org/?probe=5d5a4b489b) | Aug 03, 2023 |
| ASUSTek       | K55VD                       | [6478fd4e76](https://linux-hardware.org/?probe=6478fd4e76) | Aug 03, 2023 |
| Dell          | Vostro 5515                 | [0e031a4729](https://linux-hardware.org/?probe=0e031a4729) | Aug 02, 2023 |
| Samsung       | 535U3C                      | [8d0ebb957a](https://linux-hardware.org/?probe=8d0ebb957a) | Jul 31, 2023 |
| Samsung       | 535U3C                      | [030fc15fac](https://linux-hardware.org/?probe=030fc15fac) | Jul 31, 2023 |
| Dell          | Inspiron 3501               | [42ca7b346e](https://linux-hardware.org/?probe=42ca7b346e) | Jul 29, 2023 |
| Dell          | Inspiron 3501               | [fdcac9e445](https://linux-hardware.org/?probe=fdcac9e445) | Jul 29, 2023 |
| HUAWEI        | MACHC-WAX9                  | [bf3f7b4c2d](https://linux-hardware.org/?probe=bf3f7b4c2d) | Jul 27, 2023 |
| HP            | Laptop 15-fc0xxx            | [ba305b3271](https://linux-hardware.org/?probe=ba305b3271) | Jul 26, 2023 |
| Acer          | Nitro AN515-55              | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Dell          | Latitude E6330              | [32dbf41885](https://linux-hardware.org/?probe=32dbf41885) | Jul 24, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fdbe29a1db](https://linux-hardware.org/?probe=fdbe29a1db) | Jul 22, 2023 |
| Unknown       | Unknown                     | [516853cca9](https://linux-hardware.org/?probe=516853cca9) | Jul 21, 2023 |
| ASUSTek       | X756UXK                     | [746e141543](https://linux-hardware.org/?probe=746e141543) | Jul 10, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [59f06e2baf](https://linux-hardware.org/?probe=59f06e2baf) | Jul 09, 2023 |
| Dell          | Latitude E5470              | [ac0f0dd893](https://linux-hardware.org/?probe=ac0f0dd893) | Jul 08, 2023 |
| MSI           | Modern 14 B4MW              | [210a7aea7f](https://linux-hardware.org/?probe=210a7aea7f) | Jul 05, 2023 |
| ASUSTek       | X455LJ                      | [60c1acd1fc](https://linux-hardware.org/?probe=60c1acd1fc) | Jul 04, 2023 |
| Dell          | XPS 13 9370                 | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| HUAWEI        | MACHC-WAX9                  | [a5dd94faa7](https://linux-hardware.org/?probe=a5dd94faa7) | Jun 28, 2023 |
| ASUSTek       | X455LJ                      | [c147d5716d](https://linux-hardware.org/?probe=c147d5716d) | Jun 27, 2023 |
| Dell          | Vostro 5515                 | [350e1d5a7b](https://linux-hardware.org/?probe=350e1d5a7b) | Jun 23, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d5c387d28e](https://linux-hardware.org/?probe=d5c387d28e) | Jun 18, 2023 |
| MSI           | GL62M 7RDX                  | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7c9662b5eb](https://linux-hardware.org/?probe=7c9662b5eb) | Jun 10, 2023 |
| Lenovo        | ThinkPad L430 24655Q7       | [7b45c0777e](https://linux-hardware.org/?probe=7b45c0777e) | Jun 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS2292K    | [380ffe6574](https://linux-hardware.org/?probe=380ffe6574) | Jun 06, 2023 |
| Dell          | Inspiron 7472               | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 2325SLU       | [3a1d630346](https://linux-hardware.org/?probe=3a1d630346) | Jun 03, 2023 |
| Valve         | Jupiter                     | [49135876a9](https://linux-hardware.org/?probe=49135876a9) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [1334997a22](https://linux-hardware.org/?probe=1334997a22) | Jun 01, 2023 |
| HP            | Laptop 17-cn0xxx            | [f688bc50e0](https://linux-hardware.org/?probe=f688bc50e0) | Jun 01, 2023 |
| Acer          | Nitro AN515-58              | [c9d2b44907](https://linux-hardware.org/?probe=c9d2b44907) | May 17, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [53a5e2e7d7](https://linux-hardware.org/?probe=53a5e2e7d7) | May 16, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a7c2953571](https://linux-hardware.org/?probe=a7c2953571) | May 15, 2023 |
| HP            | Laptop 14-dq2xxx            | [274fbdb43e](https://linux-hardware.org/?probe=274fbdb43e) | May 14, 2023 |
| HP            | EliteBook 840 G6            | [80158c51fb](https://linux-hardware.org/?probe=80158c51fb) | May 12, 2023 |
| Acer          | Aspire E5-521G              | [9ddcbd7a95](https://linux-hardware.org/?probe=9ddcbd7a95) | May 01, 2023 |
| Valve         | Jupiter                     | [cf4ff7fcb1](https://linux-hardware.org/?probe=cf4ff7fcb1) | Apr 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6ce11cef12](https://linux-hardware.org/?probe=6ce11cef12) | Apr 18, 2023 |
| HP            | Laptop 14-bs1xx             | [1bc4428cb1](https://linux-hardware.org/?probe=1bc4428cb1) | Apr 17, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [c5c1b213f2](https://linux-hardware.org/?probe=c5c1b213f2) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0120f0db62](https://linux-hardware.org/?probe=0120f0db62) | Apr 12, 2023 |
| HP            | Pavilion (EH737UA#ABA)      | [cc8ff92529](https://linux-hardware.org/?probe=cc8ff92529) | Apr 11, 2023 |
| Dell          | Inspiron 5584               | [5ca9178d00](https://linux-hardware.org/?probe=5ca9178d00) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | [93e9be5f34](https://linux-hardware.org/?probe=93e9be5f34) | Apr 09, 2023 |
| Acer          | Aspire A315-59              | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| MSI           | Modern 14 B4MW              | [c81d9f3b07](https://linux-hardware.org/?probe=c81d9f3b07) | Mar 24, 2023 |
| Jumper        | EZbook                      | [a6114c514f](https://linux-hardware.org/?probe=a6114c514f) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| HP            | Laptop 17-cn0xxx            | [a3d866a82b](https://linux-hardware.org/?probe=a3d866a82b) | Mar 09, 2023 |
| Toshiba       | Satellite L855              | [3832889508](https://linux-hardware.org/?probe=3832889508) | Mar 09, 2023 |
| ASUSTek       | X556UQ                      | [c124d02c5b](https://linux-hardware.org/?probe=c124d02c5b) | Mar 09, 2023 |
| HP            | Dev One Notebook PC         | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Acer          | Aspire A514-55              | [97e8238d87](https://linux-hardware.org/?probe=97e8238d87) | Mar 05, 2023 |
| Acer          | Aspire A314-35              | [3e4fdfbb73](https://linux-hardware.org/?probe=3e4fdfbb73) | Mar 05, 2023 |
| HP            | ProBook 440 G7              | [ada5bd893b](https://linux-hardware.org/?probe=ada5bd893b) | Mar 04, 2023 |
| Lenovo        | ThinkPad X230 23255SM       | [2f5cd26eae](https://linux-hardware.org/?probe=2f5cd26eae) | Mar 04, 2023 |
| HP            | ProBook 440 G7              | [ce3d086582](https://linux-hardware.org/?probe=ce3d086582) | Mar 04, 2023 |
| HP            | ENVY Sleekbook 4            | [d771874d8b](https://linux-hardware.org/?probe=d771874d8b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| Acer          | Aspire A314-35              | [587096ec48](https://linux-hardware.org/?probe=587096ec48) | Mar 03, 2023 |
| Acer          | TravelMate P633-V           | [b4841d9589](https://linux-hardware.org/?probe=b4841d9589) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | [fd426b6c71](https://linux-hardware.org/?probe=fd426b6c71) | Feb 25, 2023 |
| NEC Comput... | PC-VY25AAZR7                | [bc17a98c15](https://linux-hardware.org/?probe=bc17a98c15) | Feb 24, 2023 |
| HP            | ProBook 440 G7              | [9caa421a49](https://linux-hardware.org/?probe=9caa421a49) | Feb 19, 2023 |
| Dell          | Latitude E4200              | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [22b77a1f78](https://linux-hardware.org/?probe=22b77a1f78) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | [0a6d50bc2a](https://linux-hardware.org/?probe=0a6d50bc2a) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | [75980f2f55](https://linux-hardware.org/?probe=75980f2f55) | Feb 13, 2023 |
| Acer          | Aspire ES1-572              | [24c1c37b05](https://linux-hardware.org/?probe=24c1c37b05) | Feb 13, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [94c0fadd44](https://linux-hardware.org/?probe=94c0fadd44) | Feb 10, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [e3bbec75c5](https://linux-hardware.org/?probe=e3bbec75c5) | Feb 10, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | [5d2f191a6f](https://linux-hardware.org/?probe=5d2f191a6f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | [668b9a0bfe](https://linux-hardware.org/?probe=668b9a0bfe) | Feb 09, 2023 |
| Valve         | Jupiter                     | [f7f1655bc2](https://linux-hardware.org/?probe=f7f1655bc2) | Feb 08, 2023 |
| Valve         | Jupiter                     | [df167dd152](https://linux-hardware.org/?probe=df167dd152) | Feb 08, 2023 |
| Unknown       | Unknown                     | [83e2eaf929](https://linux-hardware.org/?probe=83e2eaf929) | Feb 07, 2023 |
| Acer          | Aspire V3-574G              | [5ce729f67f](https://linux-hardware.org/?probe=5ce729f67f) | Feb 04, 2023 |
| HP            | Laptop 17-cn0xxx            | [4029c64aec](https://linux-hardware.org/?probe=4029c64aec) | Feb 02, 2023 |
| HP            | Laptop 17-cn0xxx            | [71bfc02926](https://linux-hardware.org/?probe=71bfc02926) | Feb 01, 2023 |
| Dell          | Inspiron 13-5368            | [4e74651840](https://linux-hardware.org/?probe=4e74651840) | Jan 20, 2023 |
| Unknown       | X133                        | [ad31153d58](https://linux-hardware.org/?probe=ad31153d58) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [907784afb2](https://linux-hardware.org/?probe=907784afb2) | Jan 12, 2023 |
| MSI           | Modern 14 B4MW              | [815ee96451](https://linux-hardware.org/?probe=815ee96451) | Jan 11, 2023 |
| Dell          | Inspiron 3583               | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| Acer          | Aspire 4738                 | [62914eb5f1](https://linux-hardware.org/?probe=62914eb5f1) | Jan 09, 2023 |
| Dell          | Inspiron 14-3462            | [99d81ca38e](https://linux-hardware.org/?probe=99d81ca38e) | Jan 06, 2023 |
| Dell          | Inspiron 14-3462            | [582d8bfa18](https://linux-hardware.org/?probe=582d8bfa18) | Jan 06, 2023 |
| MSI           | Modern 14 B4MW              | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| Acer          | Aspire A515-57T             | [bc905f86da](https://linux-hardware.org/?probe=bc905f86da) | Jan 02, 2023 |
| Dell          | Inspiron 14-3462            | [1a8ed5998a](https://linux-hardware.org/?probe=1a8ed5998a) | Dec 30, 2022 |
| HP            | 431 Notebook                | [6a8d323e0c](https://linux-hardware.org/?probe=6a8d323e0c) | Dec 30, 2022 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | [e133481ab3](https://linux-hardware.org/?probe=e133481ab3) | Dec 29, 2022 |
| Dell          | Inspiron 5505               | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| Acer          | Aspire 4738                 | [ffbbc9ecb5](https://linux-hardware.org/?probe=ffbbc9ecb5) | Dec 26, 2022 |
| Acer          | Aspire 4738                 | [f5277ba6a0](https://linux-hardware.org/?probe=f5277ba6a0) | Dec 26, 2022 |
| Dell          | Inspiron 14-3462            | [f95fd7ca72](https://linux-hardware.org/?probe=f95fd7ca72) | Dec 25, 2022 |
| Dell          | Inspiron 14-3462            | [7b38daddb5](https://linux-hardware.org/?probe=7b38daddb5) | Dec 25, 2022 |
| MSI           | Modern 14 B4MW              | [e9dbd838ec](https://linux-hardware.org/?probe=e9dbd838ec) | Dec 25, 2022 |
| Dell          | Inspiron 3583               | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| MSI           | Modern 14 B4MW              | [2d446beedf](https://linux-hardware.org/?probe=2d446beedf) | Dec 21, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [06d690e9fe](https://linux-hardware.org/?probe=06d690e9fe) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [fe7f585504](https://linux-hardware.org/?probe=fe7f585504) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [63cbf5d0e9](https://linux-hardware.org/?probe=63cbf5d0e9) | Dec 13, 2022 |
| MSI           | Modern 14 B4MW              | [8489ca12d8](https://linux-hardware.org/?probe=8489ca12d8) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [3c5a5379a4](https://linux-hardware.org/?probe=3c5a5379a4) | Dec 13, 2022 |
| Lenovo        | G470 20078                  | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| MSI           | Modern 14 B4MW              | [03c0b9e50d](https://linux-hardware.org/?probe=03c0b9e50d) | Dec 05, 2022 |
| MSI           | Modern 14 B4MW              | [6890b98eeb](https://linux-hardware.org/?probe=6890b98eeb) | Dec 03, 2022 |
| HP            | Laptop 15-da3xxx            | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | Pavilion Power Laptop 15... | [913b35d3f0](https://linux-hardware.org/?probe=913b35d3f0) | Nov 25, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [09285b9428](https://linux-hardware.org/?probe=09285b9428) | Nov 13, 2022 |
| Unknown       | X133                        | [f89481552e](https://linux-hardware.org/?probe=f89481552e) | Nov 11, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [abbb784ea9](https://linux-hardware.org/?probe=abbb784ea9) | Nov 09, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [fbe5c4578c](https://linux-hardware.org/?probe=fbe5c4578c) | Nov 04, 2022 |
| HP            | EliteBook 745 G2            | [6eca80dabf](https://linux-hardware.org/?probe=6eca80dabf) | Nov 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [28cc86118e](https://linux-hardware.org/?probe=28cc86118e) | Nov 03, 2022 |
| Dell          | Vostro 5515                 | [881cd60670](https://linux-hardware.org/?probe=881cd60670) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HUAWEI        | KLVD-WXX9                   | [e9ce57f1c1](https://linux-hardware.org/?probe=e9ce57f1c1) | Oct 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| HP            | 431 Notebook                | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Lenovo        | ThinkPad X230 2325CF6       | [622d37f892](https://linux-hardware.org/?probe=622d37f892) | Oct 15, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [fbb018d1ef](https://linux-hardware.org/?probe=fbb018d1ef) | Oct 14, 2022 |
| Acer          | Swift SF314-57              | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [5eafc7c12c](https://linux-hardware.org/?probe=5eafc7c12c) | Oct 13, 2022 |
| HP            | Laptop 14s-dk1xxx           | [1eb06e8e12](https://linux-hardware.org/?probe=1eb06e8e12) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| Toshiba       | TECRA Z50-C                 | [fc6e63a30a](https://linux-hardware.org/?probe=fc6e63a30a) | Oct 11, 2022 |
| HP            | ENVY Sleekbook 4            | [c14c5b1ee3](https://linux-hardware.org/?probe=c14c5b1ee3) | Oct 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| HP            | ENVY Sleekbook 4            | [0b820a1c7e](https://linux-hardware.org/?probe=0b820a1c7e) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Dell          | Latitude 5490               | [4c59654ea9](https://linux-hardware.org/?probe=4c59654ea9) | Sep 29, 2022 |
| Acer          | Aspire E3-111               | [6646e09597](https://linux-hardware.org/?probe=6646e09597) | Sep 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| Acer          | AOD257                      | [35ca1c0b33](https://linux-hardware.org/?probe=35ca1c0b33) | Sep 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6c34753f58](https://linux-hardware.org/?probe=6c34753f58) | Sep 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Google        | Treeya                      | [0553290711](https://linux-hardware.org/?probe=0553290711) | Sep 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ecadc5740](https://linux-hardware.org/?probe=1ecadc5740) | Sep 11, 2022 |
| ASUSTek       | X441NA                      | [40f5cb1550](https://linux-hardware.org/?probe=40f5cb1550) | Sep 10, 2022 |
| Google        | Treeya                      | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Acer          | Aspire A314-22G             | [b6f9c0a0e7](https://linux-hardware.org/?probe=b6f9c0a0e7) | Sep 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [85d4f11486](https://linux-hardware.org/?probe=85d4f11486) | Sep 01, 2022 |
| Dell          | Inspiron MM061              | [7d69c012fb](https://linux-hardware.org/?probe=7d69c012fb) | Aug 28, 2022 |
| Dell          | Inspiron 5577               | [b40621d5f6](https://linux-hardware.org/?probe=b40621d5f6) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| Dell          | Inspiron 7472               | [d9ff6dc8b4](https://linux-hardware.org/?probe=d9ff6dc8b4) | Aug 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| realme        | RMNBXXXX                    | [d98be8821f](https://linux-hardware.org/?probe=d98be8821f) | Aug 20, 2022 |
| HP            | Laptop 14-bs1xx             | [4b603b6b08](https://linux-hardware.org/?probe=4b603b6b08) | Aug 15, 2022 |
| ASUSTek       | K56CB                       | [0ec4449fe2](https://linux-hardware.org/?probe=0ec4449fe2) | Aug 09, 2022 |
| HP            | Laptop 14s-dk0xxx           | [49ab4e0197](https://linux-hardware.org/?probe=49ab4e0197) | Aug 08, 2022 |
| Dell          | Precision 3510              | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Dell          | Precision 3510              | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [93ae3bfcfd](https://linux-hardware.org/?probe=93ae3bfcfd) | Aug 02, 2022 |
| Lenovo        | ThinkPad E590 20NB0032CD    | [502b0eeb39](https://linux-hardware.org/?probe=502b0eeb39) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| HP            | Pavilion Notebook           | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [f47a0ecbf5](https://linux-hardware.org/?probe=f47a0ecbf5) | Jul 25, 2022 |
| MSI           | CX62 6QD                    | [d0c23fefca](https://linux-hardware.org/?probe=d0c23fefca) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| Unknown       | Unknown                     | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| Dell          | Vostro 3700                 | [2b7a37d662](https://linux-hardware.org/?probe=2b7a37d662) | Jul 16, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [24c803a5fc](https://linux-hardware.org/?probe=24c803a5fc) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| HP            | Laptop 15-ef1xxx            | [b6a7451086](https://linux-hardware.org/?probe=b6a7451086) | Jul 11, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [b9c939b2e2](https://linux-hardware.org/?probe=b9c939b2e2) | Jul 09, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [88cc242e02](https://linux-hardware.org/?probe=88cc242e02) | Jul 09, 2022 |
| HP            | Laptop 15-ef1xxx            | [264b084b00](https://linux-hardware.org/?probe=264b084b00) | Jul 08, 2022 |
| Acer          | Aspire E5-473G              | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [c9d2a76068](https://linux-hardware.org/?probe=c9d2a76068) | Jul 03, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [b7fedc25e4](https://linux-hardware.org/?probe=b7fedc25e4) | Jul 01, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [78eaeff700](https://linux-hardware.org/?probe=78eaeff700) | Jun 27, 2022 |
| Acer          | Predator PH315-53           | [c23e943030](https://linux-hardware.org/?probe=c23e943030) | Jun 21, 2022 |
| Dell          | Inspiron 3531               | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| Dell          | Vostro 5515                 | [b884e51280](https://linux-hardware.org/?probe=b884e51280) | May 21, 2022 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | [a3e1bf045d](https://linux-hardware.org/?probe=a3e1bf045d) | May 20, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | TravelMate P249-G2-MG       | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Unknown       | Unknown                     | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Aspire E5-576G              | [27f577ec86](https://linux-hardware.org/?probe=27f577ec86) | May 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5b877349c1](https://linux-hardware.org/?probe=5b877349c1) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [07ed7fd709](https://linux-hardware.org/?probe=07ed7fd709) | May 08, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [443d537d91](https://linux-hardware.org/?probe=443d537d91) | May 05, 2022 |
| Apple         | MacBookAir5,1               | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Acer          | TravelMate P249-G2-MG       | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Acer          | Aspire E5-551G              | [8dd5e105d1](https://linux-hardware.org/?probe=8dd5e105d1) | Apr 21, 2022 |
| Toshiba       | TECRA R940                  | [e7dc07a41c](https://linux-hardware.org/?probe=e7dc07a41c) | Apr 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1f3827f38e](https://linux-hardware.org/?probe=1f3827f38e) | Apr 18, 2022 |
| Unknown       | Unknown                     | [cfd3bd53a8](https://linux-hardware.org/?probe=cfd3bd53a8) | Apr 18, 2022 |
| Acer          | Nitro AN515-57              | [b824b88050](https://linux-hardware.org/?probe=b824b88050) | Apr 15, 2022 |
| Toshiba       | Satellite E45t-A            | [3698a21b91](https://linux-hardware.org/?probe=3698a21b91) | Apr 15, 2022 |
| Toshiba       | dynabook B45/A              | [f430a05b2d](https://linux-hardware.org/?probe=f430a05b2d) | Apr 09, 2022 |
| Samsung       | RC420/RC520/RC720           | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Lenovo        | G50-45 80E3                 | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [1a9459872a](https://linux-hardware.org/?probe=1a9459872a) | Mar 13, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | [2f136d5bf5](https://linux-hardware.org/?probe=2f136d5bf5) | Mar 11, 2022 |
| Unknown       | Unknown                     | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Unknown       | Unknown                     | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [809dad2888](https://linux-hardware.org/?probe=809dad2888) | Mar 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Acer          | AOD270                      | [491fbe6832](https://linux-hardware.org/?probe=491fbe6832) | Feb 21, 2022 |
| Acer          | AOD270                      | [90f9f56240](https://linux-hardware.org/?probe=90f9f56240) | Feb 21, 2022 |
| ASUSTek       | 900                         | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [1e700d65ea](https://linux-hardware.org/?probe=1e700d65ea) | Feb 17, 2022 |
| HP            | Unknown                     | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Lenovo        | ThinkPad X220 4290MN4       | [c0c3368738](https://linux-hardware.org/?probe=c0c3368738) | Feb 08, 2022 |
| Acer          | Aspire V5-471               | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | [c8f0deedbc](https://linux-hardware.org/?probe=c8f0deedbc) | Feb 03, 2022 |
| Acer          | Nitro AN515-55              | [ca4c953595](https://linux-hardware.org/?probe=ca4c953595) | Jan 27, 2022 |
| Acer          | Aspire A315-42              | [e01afda31f](https://linux-hardware.org/?probe=e01afda31f) | Jan 22, 2022 |
| HP            | Notebook                    | [826345f64e](https://linux-hardware.org/?probe=826345f64e) | Jan 13, 2022 |
| Acer          | Aspire A315-41G             | [647b2f2da2](https://linux-hardware.org/?probe=647b2f2da2) | Jan 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Dell          | Inspiron 5555               | [5f4e7a5f4b](https://linux-hardware.org/?probe=5f4e7a5f4b) | Dec 28, 2021 |
| HP            | Pavilion tx1000             | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Unknown       | Unknown                     | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Dell          | XPS 15 9570                 | [448cdcb300](https://linux-hardware.org/?probe=448cdcb300) | Dec 17, 2021 |
| HP            | Pavilion tx1000             | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| Dell          | MXG061                      | [72d7e58977](https://linux-hardware.org/?probe=72d7e58977) | Nov 28, 2021 |
| Sony          | SVT13115FGS                 | [a5821de326](https://linux-hardware.org/?probe=a5821de326) | Nov 22, 2021 |
| HP            | ProBook 4730s               | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Acer          | TravelMate P249-G2-M        | [7dbc9e305c](https://linux-hardware.org/?probe=7dbc9e305c) | Nov 11, 2021 |
| Toshiba       | NB255                       | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [bfd4d51591](https://linux-hardware.org/?probe=bfd4d51591) | Nov 09, 2021 |
| HP            | Unknown                     | [4ce778dffc](https://linux-hardware.org/?probe=4ce778dffc) | Nov 06, 2021 |
| HP            | Unknown                     | [285c5d9c85](https://linux-hardware.org/?probe=285c5d9c85) | Nov 06, 2021 |
| Acer          | Aspire E5-411               | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| PERSONA       | MYBOOK 14                   | [bf2929c7e3](https://linux-hardware.org/?probe=bf2929c7e3) | Nov 03, 2021 |
| Acer          | Aspire E5-411               | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [fd3aefd54a](https://linux-hardware.org/?probe=fd3aefd54a) | Oct 27, 2021 |
| Dell          | Vostro 1400                 | [ba2e7123ba](https://linux-hardware.org/?probe=ba2e7123ba) | Oct 24, 2021 |
| Jumper        | EZbook                      | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HASEE Comp... | HNX4S                       | [aba8e89b9a](https://linux-hardware.org/?probe=aba8e89b9a) | Oct 17, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ec3329e68a](https://linux-hardware.org/?probe=ec3329e68a) | Oct 17, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [b8292ace4e](https://linux-hardware.org/?probe=b8292ace4e) | Oct 14, 2021 |
| HP            | Unknown                     | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| HP            | 14                          | [71ed61e3e0](https://linux-hardware.org/?probe=71ed61e3e0) | Oct 02, 2021 |
| HP            | 14                          | [8fc4fceaa1](https://linux-hardware.org/?probe=8fc4fceaa1) | Oct 02, 2021 |
| HP            | EliteBook 745 G2            | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| HP            | G60                         | [36ad0dc4bc](https://linux-hardware.org/?probe=36ad0dc4bc) | Sep 22, 2021 |
| HP            | Unknown                     | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| ASUSTek       | X510UQ                      | [ffeab1f23c](https://linux-hardware.org/?probe=ffeab1f23c) | Sep 16, 2021 |
| Toshiba       | Satellite P845              | [27d8557047](https://linux-hardware.org/?probe=27d8557047) | Sep 12, 2021 |
| Toshiba       | Satellite C55D-B            | [e9f2b0ceda](https://linux-hardware.org/?probe=e9f2b0ceda) | Sep 11, 2021 |
| Dell          | Latitude E7450              | [531e888c8b](https://linux-hardware.org/?probe=531e888c8b) | Sep 04, 2021 |
| Lenovo        | ThinkPad X220 42863MJ       | [68cbfb3edb](https://linux-hardware.org/?probe=68cbfb3edb) | Sep 04, 2021 |
| Cubix         | Morph                       | [ffc9d93c9b](https://linux-hardware.org/?probe=ffc9d93c9b) | Aug 30, 2021 |
| Gigabyte      | Q2006                       | [754a3fc1b5](https://linux-hardware.org/?probe=754a3fc1b5) | Aug 23, 2021 |
| Gigabyte      | Q2006                       | [a384b10b00](https://linux-hardware.org/?probe=a384b10b00) | Aug 23, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Acer          | Aspire V3-772G              | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Apple         | MacBookAir4,1               | [cc00e74712](https://linux-hardware.org/?probe=cc00e74712) | Aug 09, 2021 |
| Toshiba       | Satellite C650              | [3b5f090e84](https://linux-hardware.org/?probe=3b5f090e84) | Aug 01, 2021 |
| Acer          | Aspire E3-111               | [29d6febd6e](https://linux-hardware.org/?probe=29d6febd6e) | Jul 24, 2021 |
| Acer          | Aspire E3-111               | [f9c8b1d3ff](https://linux-hardware.org/?probe=f9c8b1d3ff) | Jul 24, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [9576a81942](https://linux-hardware.org/?probe=9576a81942) | Jul 23, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d86a6d7c9a](https://linux-hardware.org/?probe=d86a6d7c9a) | Jul 23, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Lenovo        | ThinkPad X220 4291LL6       | [3e8ed9be02](https://linux-hardware.org/?probe=3e8ed9be02) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | [ceedeef480](https://linux-hardware.org/?probe=ceedeef480) | Jul 01, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ca6df82553](https://linux-hardware.org/?probe=ca6df82553) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | [69031eda12](https://linux-hardware.org/?probe=69031eda12) | Jun 18, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | [d7b3c8fc20](https://linux-hardware.org/?probe=d7b3c8fc20) | Jun 18, 2021 |
| Lenovo        | ThinkPad L530 24811K2       | [3517541065](https://linux-hardware.org/?probe=3517541065) | Jun 11, 2021 |
| Toshiba       | Satellite L515              | [72858b36e6](https://linux-hardware.org/?probe=72858b36e6) | Jun 02, 2021 |
| NEC Comput... | PC-VK25MXZCB                | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Acer          | Aspire 4750                 | [5f6a294b7d](https://linux-hardware.org/?probe=5f6a294b7d) | May 12, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [cbe08b6f59](https://linux-hardware.org/?probe=cbe08b6f59) | May 09, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b2e6deb92e](https://linux-hardware.org/?probe=b2e6deb92e) | May 09, 2021 |
| ASUSTek       | X450MD                      | [b77e4abcd8](https://linux-hardware.org/?probe=b77e4abcd8) | May 06, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [bb346e5b0c](https://linux-hardware.org/?probe=bb346e5b0c) | Apr 26, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ff01911cb6](https://linux-hardware.org/?probe=ff01911cb6) | Apr 22, 2021 |
| Acer          | Aspire ES1-132              | [2e91d0c330](https://linux-hardware.org/?probe=2e91d0c330) | Apr 20, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [f8a3bc6b1d](https://linux-hardware.org/?probe=f8a3bc6b1d) | Apr 19, 2021 |
| Acer          | Nitro AN715-51              | [1cd3975ffa](https://linux-hardware.org/?probe=1cd3975ffa) | Apr 16, 2021 |
| HP            | Notebook                    | [023066c915](https://linux-hardware.org/?probe=023066c915) | Apr 08, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [b11b4274e4](https://linux-hardware.org/?probe=b11b4274e4) | Apr 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [2870ee333f](https://linux-hardware.org/?probe=2870ee333f) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [43b581a270](https://linux-hardware.org/?probe=43b581a270) | Apr 07, 2021 |
| Dell          | Inspiron 15-3567            | [40b47343b7](https://linux-hardware.org/?probe=40b47343b7) | Mar 28, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | [4f1b6f18bf](https://linux-hardware.org/?probe=4f1b6f18bf) | Mar 26, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | [aec0de9a30](https://linux-hardware.org/?probe=aec0de9a30) | Mar 26, 2021 |
| Acer          | TravelMate B117-M           | [c205b164c5](https://linux-hardware.org/?probe=c205b164c5) | Mar 26, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | [4b98fb1e80](https://linux-hardware.org/?probe=4b98fb1e80) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [42dd14b17d](https://linux-hardware.org/?probe=42dd14b17d) | Mar 09, 2021 |
| MSI           | CX62 7QL                    | [8241c594e5](https://linux-hardware.org/?probe=8241c594e5) | Mar 07, 2021 |
| eMachines     | eM250                       | [e20e648698](https://linux-hardware.org/?probe=e20e648698) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [ec866fbb40](https://linux-hardware.org/?probe=ec866fbb40) | Mar 04, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Acer          | TravelMate B115-M           | [46b6080608](https://linux-hardware.org/?probe=46b6080608) | Mar 02, 2021 |
| Acer          | TravelMate B115-M           | [4567b99e4e](https://linux-hardware.org/?probe=4567b99e4e) | Mar 02, 2021 |
| Acer          | TravelMate B113             | [5ff9f9bb03](https://linux-hardware.org/?probe=5ff9f9bb03) | Feb 23, 2021 |
| Lenovo        | G450 20022                  | [a98aa9041e](https://linux-hardware.org/?probe=a98aa9041e) | Feb 17, 2021 |
| Sony          | VPCEA36FA                   | [050c395bd5](https://linux-hardware.org/?probe=050c395bd5) | Feb 16, 2021 |
| Lenovo        | ThinkPad L530 24812K6       | [d78f3099e4](https://linux-hardware.org/?probe=d78f3099e4) | Feb 14, 2021 |
| Apple         | MacBookPro5,5               | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| Acer          | TravelMate B113             | [7e439b847d](https://linux-hardware.org/?probe=7e439b847d) | Feb 04, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [4c9b44d2d4](https://linux-hardware.org/?probe=4c9b44d2d4) | Jan 26, 2021 |
| Acer          | Aspire ES1-132              | [1e55ffedfe](https://linux-hardware.org/?probe=1e55ffedfe) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | [6f9868755e](https://linux-hardware.org/?probe=6f9868755e) | Jan 15, 2021 |
| Toshiba       | dynabook R73/W              | [b84a72cace](https://linux-hardware.org/?probe=b84a72cace) | Jan 02, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [459afa05c1](https://linux-hardware.org/?probe=459afa05c1) | Dec 26, 2020 |
| HP            | ZBook Create G7 Notebook... | [e40ffb436c](https://linux-hardware.org/?probe=e40ffb436c) | Dec 20, 2020 |
| HP            | ZBook Create G7 Notebook... | [b1a2ee65e0](https://linux-hardware.org/?probe=b1a2ee65e0) | Dec 20, 2020 |
| Acer          | Aspire ES1-431              | [6a99509d25](https://linux-hardware.org/?probe=6a99509d25) | Dec 16, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [e315898f10](https://linux-hardware.org/?probe=e315898f10) | Dec 16, 2020 |
| Toshiba       | dynabook R73/W              | [96710da884](https://linux-hardware.org/?probe=96710da884) | Dec 14, 2020 |
| Samsung       | RF511/RF411/RF711           | [db8ffa8342](https://linux-hardware.org/?probe=db8ffa8342) | Dec 06, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [4dd4445d4d](https://linux-hardware.org/?probe=4dd4445d4d) | Nov 29, 2020 |
| Acer          | Aspire A315-53G             | [9498233954](https://linux-hardware.org/?probe=9498233954) | Nov 26, 2020 |
| eMachines     | eM350                       | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| Apple         | MacBookPro5,5               | [d63213adad](https://linux-hardware.org/?probe=d63213adad) | Nov 22, 2020 |
| ASUSTek       | K43SD                       | [869c3395e8](https://linux-hardware.org/?probe=869c3395e8) | Nov 20, 2020 |
| ASUSTek       | K43SD                       | [3ce330e163](https://linux-hardware.org/?probe=3ce330e163) | Nov 19, 2020 |
| HP            | Unknown                     | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | X540NA                      | [7c1cb4cac0](https://linux-hardware.org/?probe=7c1cb4cac0) | Nov 02, 2020 |
| Lenovo        | ThinkPad X220 4290MN4       | [f305f22059](https://linux-hardware.org/?probe=f305f22059) | Oct 29, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [80d72786c1](https://linux-hardware.org/?probe=80d72786c1) | Oct 26, 2020 |
| Acer          | Aspire SW3-016              | [e110233803](https://linux-hardware.org/?probe=e110233803) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | [ecf79444ac](https://linux-hardware.org/?probe=ecf79444ac) | Oct 21, 2020 |
| HP            | EliteBook 840 G6            | [bfe2deec18](https://linux-hardware.org/?probe=bfe2deec18) | Oct 17, 2020 |
| Acer          | Aspire SW3-016              | [2f0952fbb5](https://linux-hardware.org/?probe=2f0952fbb5) | Oct 15, 2020 |
| Lenovo        | ThinkPad X260 20F5S04206    | [147c40fe70](https://linux-hardware.org/?probe=147c40fe70) | Oct 12, 2020 |
| HP            | Notebook                    | [8cbf9133f7](https://linux-hardware.org/?probe=8cbf9133f7) | Oct 11, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9c83568b79](https://linux-hardware.org/?probe=9c83568b79) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| HP            | 15                          | [c44a5eaea1](https://linux-hardware.org/?probe=c44a5eaea1) | Oct 07, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | [c1812f8ee0](https://linux-hardware.org/?probe=c1812f8ee0) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | [4e98739f72](https://linux-hardware.org/?probe=4e98739f72) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [73fd7565f6](https://linux-hardware.org/?probe=73fd7565f6) | Oct 05, 2020 |
| ASUSTek       | X540NA                      | [a2cee62097](https://linux-hardware.org/?probe=a2cee62097) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| HP            | Pavilion Laptop 15-cc0xx    | [a8678813c5](https://linux-hardware.org/?probe=a8678813c5) | Oct 01, 2020 |
| ASUSTek       | K75DE                       | [b4cb493794](https://linux-hardware.org/?probe=b4cb493794) | Sep 28, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | [72f627fd0e](https://linux-hardware.org/?probe=72f627fd0e) | Sep 21, 2020 |
| Apple         | MacBookAir3,1               | [73e9128968](https://linux-hardware.org/?probe=73e9128968) | Sep 21, 2020 |
| Fujitsu       | FMVA05008                   | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| Lenovo        | V110-14IAP 80TF             | [f0ac65615d](https://linux-hardware.org/?probe=f0ac65615d) | Sep 14, 2020 |
| Lenovo        | V110-14IAP 80TF             | [5acf002102](https://linux-hardware.org/?probe=5acf002102) | Sep 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1cf35a6180](https://linux-hardware.org/?probe=1cf35a6180) | Sep 13, 2020 |
| Lenovo        | V110-14IAP 80TF             | [d2fde2a21e](https://linux-hardware.org/?probe=d2fde2a21e) | Sep 13, 2020 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | [5a3c4a23bb](https://linux-hardware.org/?probe=5a3c4a23bb) | Sep 12, 2020 |
| ASUSTek       | X441URK                     | [f883ed5e4b](https://linux-hardware.org/?probe=f883ed5e4b) | Sep 12, 2020 |
| Dell          | Latitude E4300              | [8b163ddf1e](https://linux-hardware.org/?probe=8b163ddf1e) | Sep 09, 2020 |
| Apple         | MacBookAir2,1               | [c4b26d8019](https://linux-hardware.org/?probe=c4b26d8019) | Sep 08, 2020 |
| HP            | EliteBook 840 G6            | [809af585ab](https://linux-hardware.org/?probe=809af585ab) | Sep 08, 2020 |
| Lenovo        | ThinkPad E580 20KSA00UAU    | [becbbe530b](https://linux-hardware.org/?probe=becbbe530b) | Sep 07, 2020 |
| Acer          | Aspire 4752                 | [9c779dc588](https://linux-hardware.org/?probe=9c779dc588) | Sep 04, 2020 |
| Acer          | Aspire 4752                 | [efeb5dd920](https://linux-hardware.org/?probe=efeb5dd920) | Sep 04, 2020 |
| Acer          | Aspire A315-41G             | [ec1a232ba9](https://linux-hardware.org/?probe=ec1a232ba9) | Sep 03, 2020 |
| Acer          | Aspire A315-41G             | [3cff1527be](https://linux-hardware.org/?probe=3cff1527be) | Sep 03, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0fda90e55c](https://linux-hardware.org/?probe=0fda90e55c) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [4a5f93ed76](https://linux-hardware.org/?probe=4a5f93ed76) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [e11793b02c](https://linux-hardware.org/?probe=e11793b02c) | Sep 02, 2020 |
| ASUSTek       | X441URK                     | [35b06d497e](https://linux-hardware.org/?probe=35b06d497e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | [100fc7862e](https://linux-hardware.org/?probe=100fc7862e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | [6d9f5403eb](https://linux-hardware.org/?probe=6d9f5403eb) | Sep 02, 2020 |
| Lenovo        | IdeaPad Z460 20059          | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS0SA0J    | [5e85d0fa0e](https://linux-hardware.org/?probe=5e85d0fa0e) | Aug 31, 2020 |
| Clevo         | M7x0S                       | [7efc902d33](https://linux-hardware.org/?probe=7efc902d33) | Aug 31, 2020 |
| Clevo         | M7x0S                       | [58b7846f61](https://linux-hardware.org/?probe=58b7846f61) | Aug 30, 2020 |
| Dell          | Latitude E7450              | [7b6b25e684](https://linux-hardware.org/?probe=7b6b25e684) | Aug 27, 2020 |
| Acer          | Swift SF314-41              | [290159761f](https://linux-hardware.org/?probe=290159761f) | Aug 27, 2020 |
| HP            | Pavilion g4                 | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| ASUSTek       | X540NA                      | [8747f9eb75](https://linux-hardware.org/?probe=8747f9eb75) | Aug 22, 2020 |
| ASUSTek       | X540NA                      | [b1d91b9932](https://linux-hardware.org/?probe=b1d91b9932) | Aug 21, 2020 |
| Sony          | SVF14216SGP                 | [31495e375f](https://linux-hardware.org/?probe=31495e375f) | Aug 19, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | [56702de7d4](https://linux-hardware.org/?probe=56702de7d4) | Aug 15, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | [d868e4a7f9](https://linux-hardware.org/?probe=d868e4a7f9) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [a5e0d02669](https://linux-hardware.org/?probe=a5e0d02669) | Aug 12, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [aa6089eda7](https://linux-hardware.org/?probe=aa6089eda7) | Aug 06, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [86ee9f7736](https://linux-hardware.org/?probe=86ee9f7736) | Aug 06, 2020 |
| MSI           | GV62 8RD                    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| HP            | Pavilion g4                 | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| Acer          | Aspire ES1-521              | [64a762e6b8](https://linux-hardware.org/?probe=64a762e6b8) | Jul 26, 2020 |
| HP            | Notebook                    | [7dd7f12bb9](https://linux-hardware.org/?probe=7dd7f12bb9) | Jul 25, 2020 |
| HP            | Notebook                    | [55ab6c06c5](https://linux-hardware.org/?probe=55ab6c06c5) | Jul 25, 2020 |
| Acer          | Aspire ES1-521              | [23d8c2d2cf](https://linux-hardware.org/?probe=23d8c2d2cf) | Jul 25, 2020 |
| Samsung       | RF511/RF411/RF711           | [ca9dc81053](https://linux-hardware.org/?probe=ca9dc81053) | Jul 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [d486d4bc03](https://linux-hardware.org/?probe=d486d4bc03) | Jul 24, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [f12d8d16e5](https://linux-hardware.org/?probe=f12d8d16e5) | Jul 16, 2020 |
| Acer          | Aspire ES1-132              | [d1bc3c3a8a](https://linux-hardware.org/?probe=d1bc3c3a8a) | Jul 10, 2020 |
| Acer          | Aspire ES1-132              | [cb26f9925f](https://linux-hardware.org/?probe=cb26f9925f) | Jul 09, 2020 |
| ASUSTek       | X540NA                      | [2e3aac14fe](https://linux-hardware.org/?probe=2e3aac14fe) | Jul 02, 2020 |
| Acer          | Aspire V5-431               | [0287b85983](https://linux-hardware.org/?probe=0287b85983) | Jun 30, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | [fb0a45d925](https://linux-hardware.org/?probe=fb0a45d925) | Jun 27, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | [99e750162d](https://linux-hardware.org/?probe=99e750162d) | Jun 27, 2020 |
| eMachines     | eM350                       | [b699bf9fb6](https://linux-hardware.org/?probe=b699bf9fb6) | Jun 25, 2020 |
| HP            | Pavilion Notebook           | [1107791eab](https://linux-hardware.org/?probe=1107791eab) | Jun 22, 2020 |
| Acer          | Aspire ES1-132              | [7c1783588a](https://linux-hardware.org/?probe=7c1783588a) | Jun 12, 2020 |
| Acer          | Aspire ES1-132              | [cbbefff0a6](https://linux-hardware.org/?probe=cbbefff0a6) | Jun 12, 2020 |
| HP            | 15                          | [a4b90e7ad1](https://linux-hardware.org/?probe=a4b90e7ad1) | Jun 05, 2020 |
| ASUSTek       | X540UP                      | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Dell          | Latitude 7490               | [b7b69c9cbf](https://linux-hardware.org/?probe=b7b69c9cbf) | Jun 05, 2020 |
| MSI           | MS-N014                     | [e9fd398a70](https://linux-hardware.org/?probe=e9fd398a70) | Jun 04, 2020 |
| Google        | Caroline                    | [4e305a0551](https://linux-hardware.org/?probe=4e305a0551) | May 31, 2020 |
| Samsung       | N150P/N210P/N220P           | [2a2f1b6680](https://linux-hardware.org/?probe=2a2f1b6680) | May 27, 2020 |
| ASUSTek       | N45SF                       | [a73c8a7057](https://linux-hardware.org/?probe=a73c8a7057) | May 24, 2020 |
| Acer          | Aspire A315-51              | [8d5860b41f](https://linux-hardware.org/?probe=8d5860b41f) | May 23, 2020 |
| Acer          | Aspire A315-51              | [931084ae9c](https://linux-hardware.org/?probe=931084ae9c) | May 23, 2020 |
| ASUSTek       | N45SF                       | [e35a078b83](https://linux-hardware.org/?probe=e35a078b83) | May 23, 2020 |
| HP            | EliteBook 745 G3            | [ebd5778f8c](https://linux-hardware.org/?probe=ebd5778f8c) | May 22, 2020 |
| Lenovo        | ThinkPad X280 20KES69A00    | [c1fc46e405](https://linux-hardware.org/?probe=c1fc46e405) | May 21, 2020 |
| Acer          | Aspire ES1-431              | [58ad8d0b01](https://linux-hardware.org/?probe=58ad8d0b01) | May 18, 2020 |
| Samsung       | RF511/RF411/RF711           | [9e80b645d9](https://linux-hardware.org/?probe=9e80b645d9) | May 17, 2020 |
| Toshiba       | Satellite Pro U400          | [7114a6459c](https://linux-hardware.org/?probe=7114a6459c) | May 17, 2020 |
| Acer          | Aspire ES1-431              | [32fb20af11](https://linux-hardware.org/?probe=32fb20af11) | May 16, 2020 |
| Lenovo        | IdeaPad S540-15IML 81NG     | [89e361466e](https://linux-hardware.org/?probe=89e361466e) | May 14, 2020 |
| HP            | Notebook                    | [142457c9ea](https://linux-hardware.org/?probe=142457c9ea) | May 12, 2020 |
| Acer          | Aspire M5-481PT             | [772cc038ae](https://linux-hardware.org/?probe=772cc038ae) | May 09, 2020 |
| Acer          | Aspire M5-481PT             | [332e871ec3](https://linux-hardware.org/?probe=332e871ec3) | May 09, 2020 |
| Acer          | Aspire ES1-431              | [429d4a7720](https://linux-hardware.org/?probe=429d4a7720) | May 03, 2020 |
| Samsung       | RF511/RF411/RF711           | [028f510367](https://linux-hardware.org/?probe=028f510367) | May 03, 2020 |
| HP            | EliteBook 745 G2            | [60ee09d8aa](https://linux-hardware.org/?probe=60ee09d8aa) | May 02, 2020 |
| Lenovo        | ThinkPad T460s 20F9004FU... | [8eacfd828e](https://linux-hardware.org/?probe=8eacfd828e) | Apr 21, 2020 |
| Clevo         | M7x0S                       | [7ba28306d0](https://linux-hardware.org/?probe=7ba28306d0) | Apr 16, 2020 |
| Clevo         | M7x0S                       | [23aa6b7beb](https://linux-hardware.org/?probe=23aa6b7beb) | Apr 16, 2020 |
| Dell          | Inspiron 3442               | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| Clevo         | E412X                       | [0cca012f20](https://linux-hardware.org/?probe=0cca012f20) | Apr 09, 2020 |
| Acer          | Aspire ES1-431              | [3bf24f9dd6](https://linux-hardware.org/?probe=3bf24f9dd6) | Apr 07, 2020 |
| HP            | EliteBook 745 G2            | [68ecbaa367](https://linux-hardware.org/?probe=68ecbaa367) | Apr 03, 2020 |
| Acer          | Aspire V3-772G              | [9e4c202def](https://linux-hardware.org/?probe=9e4c202def) | Apr 03, 2020 |
| Acer          | Aspire ES1-431              | [3959954db3](https://linux-hardware.org/?probe=3959954db3) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Dell          | Latitude E6430              | [e38eb04918](https://linux-hardware.org/?probe=e38eb04918) | Mar 23, 2020 |
| ASUSTek       | N45SF                       | [17ec9504f1](https://linux-hardware.org/?probe=17ec9504f1) | Mar 22, 2020 |
| Sony          | SVP13215CDB                 | [0aac039fdc](https://linux-hardware.org/?probe=0aac039fdc) | Mar 06, 2020 |
| Dell          | Precision 3540              | [b30c51350c](https://linux-hardware.org/?probe=b30c51350c) | Mar 05, 2020 |
| ASUSTek       | X441SA                      | [e06798387f](https://linux-hardware.org/?probe=e06798387f) | Mar 05, 2020 |
| Acer          | Aspire V3-772G              | [162a9b6da7](https://linux-hardware.org/?probe=162a9b6da7) | Feb 22, 2020 |
| Acer          | Aspire V5-471G              | [85eca92a3b](https://linux-hardware.org/?probe=85eca92a3b) | Feb 22, 2020 |
| Acer          | Aspire ES1-132              | [7994c923a0](https://linux-hardware.org/?probe=7994c923a0) | Feb 21, 2020 |
| Acer          | Aspire V3-772G              | [5cce680c2e](https://linux-hardware.org/?probe=5cce680c2e) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [de6eba23f1](https://linux-hardware.org/?probe=de6eba23f1) | Feb 09, 2020 |
| Lenovo        | IdeaPad Y460                | [ece975c659](https://linux-hardware.org/?probe=ece975c659) | Feb 01, 2020 |
| Lenovo        | IdeaPad Y460                | [1a614a42a8](https://linux-hardware.org/?probe=1a614a42a8) | Jan 30, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [298e5dbad9](https://linux-hardware.org/?probe=298e5dbad9) | Jan 20, 2020 |
| Dell          | Inspiron N4030              | [f3d828d4b1](https://linux-hardware.org/?probe=f3d828d4b1) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | [600afa3fd4](https://linux-hardware.org/?probe=600afa3fd4) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | [57c3c5d09b](https://linux-hardware.org/?probe=57c3c5d09b) | Jan 11, 2020 |
| ASUSTek       | X540SAA                     | [1e5c712f0b](https://linux-hardware.org/?probe=1e5c712f0b) | Jan 05, 2020 |
| Acer          | Aspire A311-31              | [1db743caaf](https://linux-hardware.org/?probe=1db743caaf) | Dec 24, 2019 |
| Dell          | Inspiron 5567               | [eecdfa47b7](https://linux-hardware.org/?probe=eecdfa47b7) | Dec 15, 2019 |
| Acer          | Aspire A315-51              | [44ecc526a8](https://linux-hardware.org/?probe=44ecc526a8) | Dec 12, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| HP            | ProBook 440 G6              | [20bcca591f](https://linux-hardware.org/?probe=20bcca591f) | Dec 03, 2019 |
| HP            | Stream Laptop 14-ax0XX      | [777d549872](https://linux-hardware.org/?probe=777d549872) | Nov 22, 2019 |
| Acer          | Aspire A315-51              | [c5d4684f24](https://linux-hardware.org/?probe=c5d4684f24) | Nov 11, 2019 |
| Acer          | AO722                       | [a54b8c9315](https://linux-hardware.org/?probe=a54b8c9315) | Nov 08, 2019 |
| Acer          | Aspire A315-51              | [ac217a032c](https://linux-hardware.org/?probe=ac217a032c) | Nov 03, 2019 |
| Toshiba       | PORTEGE R30-A               | [619b0ce294](https://linux-hardware.org/?probe=619b0ce294) | Oct 09, 2019 |
| Acer          | Aspire A315-51              | [0f199af685](https://linux-hardware.org/?probe=0f199af685) | Sep 22, 2019 |
| Toshiba       | PORTEGE R30-A               | [8d497813d1](https://linux-hardware.org/?probe=8d497813d1) | Sep 19, 2019 |
| Acer          | TravelMate P249-G2-M        | [7c06f63670](https://linux-hardware.org/?probe=7c06f63670) | Sep 18, 2019 |
| ASUSTek       | X540NA                      | [36b5c905d1](https://linux-hardware.org/?probe=36b5c905d1) | Sep 16, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | [35b92b56a8](https://linux-hardware.org/?probe=35b92b56a8) | Sep 03, 2019 |
| Acer          | Aspire A315-51              | [eaadda80df](https://linux-hardware.org/?probe=eaadda80df) | Aug 25, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | [e57d7bb95a](https://linux-hardware.org/?probe=e57d7bb95a) | Aug 14, 2019 |
| HP            | Pavilion dm4                | [42df53b120](https://linux-hardware.org/?probe=42df53b120) | Jul 28, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [7957c03703](https://linux-hardware.org/?probe=7957c03703) | Jul 28, 2019 |
| ASUSTek       | X540NA                      | [ac8f1708fb](https://linux-hardware.org/?probe=ac8f1708fb) | Jun 30, 2019 |
| Acer          | Aspire 3935                 | [2288125313](https://linux-hardware.org/?probe=2288125313) | Jun 27, 2019 |
| Acer          | Aspire 3935                 | [fbb934cec8](https://linux-hardware.org/?probe=fbb934cec8) | Jun 27, 2019 |
| Acer          | Aspire 5516                 | [92691e9024](https://linux-hardware.org/?probe=92691e9024) | Jun 13, 2019 |
| ASUSTek       | N550JK                      | [d3769c3f4d](https://linux-hardware.org/?probe=d3769c3f4d) | Apr 16, 2019 |
| ASUSTek       | N550JK                      | [31f0b418f9](https://linux-hardware.org/?probe=31f0b418f9) | Apr 16, 2019 |
| HP            | ENVY 4                      | [97135eda99](https://linux-hardware.org/?probe=97135eda99) | Mar 31, 2019 |
| Dell          | Inspiron 5567               | [18266bd48a](https://linux-hardware.org/?probe=18266bd48a) | Jan 06, 2019 |
| ASUSTek       | X540NA                      | [d3d3b75d21](https://linux-hardware.org/?probe=d3d3b75d21) | Jan 04, 2019 |
| ASUSTek       | X540NA                      | [6f63118ade](https://linux-hardware.org/?probe=6f63118ade) | Jan 04, 2019 |
| Acer          | TravelMate B113             | [fea3b127ea](https://linux-hardware.org/?probe=fea3b127ea) | Dec 25, 2018 |
| ASUSTek       | GL553VD                     | [d43361263c](https://linux-hardware.org/?probe=d43361263c) | Dec 24, 2018 |
| ASUSTek       | X540NA                      | [03eadbe056](https://linux-hardware.org/?probe=03eadbe056) | Nov 20, 2018 |
| ASUSTek       | X540NA                      | [f06d9e94e9](https://linux-hardware.org/?probe=f06d9e94e9) | Nov 20, 2018 |
| MSI           | GT70 2PC                    | [020492bfa1](https://linux-hardware.org/?probe=020492bfa1) | Jul 04, 2017 |
| MSI           | GT70 2PC                    | [a5dafd1181](https://linux-hardware.org/?probe=a5dafd1181) | Jul 04, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Philippines/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 37        | 8.69%   |
| Ubuntu 22.04                 | 32        | 7.51%   |
| Pop!_OS 22.04                | 22        | 5.16%   |
| Ubuntu 18.04                 | 15        | 3.52%   |
| Pop!_OS 20.04                | 15        | 3.52%   |
| Fedora 38                    | 12        | 2.82%   |
| OpenMandriva 4.2             | 11        | 2.58%   |
| KDE neon 20.04               | 11        | 2.58%   |
| Arch Rolling                 | 9         | 2.11%   |
| Fedora 39                    | 8         | 1.88%   |
| ArcoLinux Rolling            | 8         | 1.88%   |
| Arch                         | 7         | 1.64%   |
| Zorin 16                     | 6         | 1.41%   |
| Zorin 15                     | 6         | 1.41%   |
| Pop!_OS 21.04                | 6         | 1.41%   |
| KDE neon 22.04               | 6         | 1.41%   |
| Fedora 36                    | 6         | 1.41%   |
| Debian 11                    | 6         | 1.41%   |
| Manjaro                      | 5         | 1.17%   |
| Linux Mint 21.1              | 5         | 1.17%   |
| Kubuntu 22.04                | 5         | 1.17%   |
| Ubuntu 23.04                 | 4         | 0.94%   |
| OpenMandriva 4.3             | 4         | 0.94%   |
| Linux Mint 20.2              | 4         | 0.94%   |
| Linux Mint 20.1              | 4         | 0.94%   |
| Fedora 37                    | 4         | 0.94%   |
| Fedora 35                    | 4         | 0.94%   |
| EndeavourOS Rolling          | 4         | 0.94%   |
| Debian 12                    | 4         | 0.94%   |
| Ubuntu 20.10                 | 3         | 0.7%    |
| SteamOS 3.4.8                | 3         | 0.7%    |
| Pop!_OS 21.10                | 3         | 0.7%    |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.7%    |
| LMDE 4                       | 3         | 0.7%    |
| Linux Mint 19.3              | 3         | 0.7%    |
| KDE neon 18.04               | 3         | 0.7%    |
| Fedora 33                    | 3         | 0.7%    |
| Xubuntu 23.04                | 2         | 0.47%   |
| Xubuntu 20.04                | 2         | 0.47%   |
| Xubuntu 18.04                | 2         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 97        | 24.25%  |
| Pop!_OS       | 47        | 11.75%  |
| Fedora        | 37        | 9.25%   |
| Linux Mint    | 25        | 6.25%   |
| OpenMandriva  | 20        | 5%      |
| KDE neon      | 19        | 4.75%   |
| Arch          | 16        | 4%      |
| Endless       | 15        | 3.75%   |
| Zorin         | 12        | 3%      |
| Debian        | 12        | 3%      |
| Manjaro       | 10        | 2.5%    |
| ArcoLinux     | 10        | 2.5%    |
| Xubuntu       | 8         | 2%      |
| SteamOS       | 8         | 2%      |
| Kubuntu       | 7         | 1.75%   |
| Kali          | 7         | 1.75%   |
| EndeavourOS   | 5         | 1.25%   |
| openSUSE      | 4         | 1%      |
| Nobara        | 4         | 1%      |
| Lubuntu       | 4         | 1%      |
| LMDE          | 4         | 1%      |
| Elementary    | 4         | 1%      |
| Ubuntu MATE   | 3         | 0.75%   |
| Xero          | 2         | 0.5%    |
| Pikaos        | 2         | 0.5%    |
| Peppermint    | 2         | 0.5%    |
| Linux Lite    | 2         | 0.5%    |
| Clear Linux   | 2         | 0.5%    |
| BlackPanther  | 2         | 0.5%    |
| Ubuntu Unity  | 1         | 0.25%   |
| Ubuntu Budgie | 1         | 0.25%   |
| Sparky        | 1         | 0.25%   |
| Slackware     | 1         | 0.25%   |
| ROSA          | 1         | 0.25%   |
| MX            | 1         | 0.25%   |
| Gentoo        | 1         | 0.25%   |
| BunsenLabs    | 1         | 0.25%   |
| Archcraft     | 1         | 0.25%   |
| Alpine        | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 17        | 3.67%   |
| 5.10.14-desktop-1omv4002 | 11        | 2.38%   |
| 6.2.6-76060206-generic   | 6         | 1.3%    |
| 5.13.0-valve36-1-neptune | 6         | 1.3%    |
| 6.2.0-26-generic         | 5         | 1.08%   |
| 5.4.0-7634-generic       | 5         | 1.08%   |
| 5.4.0-48-generic         | 5         | 1.08%   |
| 5.4.0-47-generic         | 5         | 1.08%   |
| 5.15.0-58-generic        | 5         | 1.08%   |
| 5.15.0-56-generic        | 5         | 1.08%   |
| 6.2.9-300.fc38.x86_64    | 4         | 0.86%   |
| 6.2.0-33-generic         | 4         | 0.86%   |
| 5.4.0-19-generic         | 4         | 0.86%   |
| 5.3.0-28-generic         | 4         | 0.86%   |
| 5.19.0-32-generic        | 4         | 0.86%   |
| 5.16.7-desktop-1omv4003  | 4         | 0.86%   |
| 5.15.0-52-generic        | 4         | 0.86%   |
| 5.15.0-50-generic        | 4         | 0.86%   |
| 5.15.0-41-generic        | 4         | 0.86%   |
| 5.13.0-28-generic        | 4         | 0.86%   |
| 5.11.0-7620-generic      | 4         | 0.86%   |
| 6.2.0-37-generic         | 3         | 0.65%   |
| 6.2.0-32-generic         | 3         | 0.65%   |
| 6.2.0-20-generic         | 3         | 0.65%   |
| 6.0.6-76060006-generic   | 3         | 0.65%   |
| 5.8.0-14-generic         | 3         | 0.65%   |
| 5.4.0-7642-generic       | 3         | 0.65%   |
| 5.4.0-58-generic         | 3         | 0.65%   |
| 5.4.0-45-generic         | 3         | 0.65%   |
| 5.3.0-23-generic         | 3         | 0.65%   |
| 5.15.0-60-generic        | 3         | 0.65%   |
| 5.15.0-43-generic        | 3         | 0.65%   |
| 5.13.0-7614-generic      | 3         | 0.65%   |
| 5.13.0-40-generic        | 3         | 0.65%   |
| 5.0.0-37-generic         | 3         | 0.65%   |
| 4.18.0-25-generic        | 3         | 0.65%   |
| 6.7.0-cb1.0.fc39.x86_64  | 2         | 0.43%   |
| 6.6.9-200.fc39.x86_64    | 2         | 0.43%   |
| 6.6.6-76060606-generic   | 2         | 0.43%   |
| 6.5.0-14-generic         | 2         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 69        | 15.65%  |
| 5.15.0  | 41        | 9.3%    |
| 5.13.0  | 24        | 5.44%   |
| 6.2.0   | 20        | 4.54%   |
| 5.3.0   | 17        | 3.85%   |
| 5.11.0  | 15        | 3.4%    |
| 5.19.0  | 13        | 2.95%   |
| 5.8.0   | 11        | 2.49%   |
| 5.10.14 | 11        | 2.49%   |
| 4.15.0  | 11        | 2.49%   |
| 6.2.6   | 8         | 1.81%   |
| 5.0.0   | 7         | 1.59%   |
| 6.1.0   | 6         | 1.36%   |
| 5.10.0  | 6         | 1.36%   |
| 4.18.0  | 6         | 1.36%   |
| 6.0.6   | 5         | 1.13%   |
| 4.19.0  | 5         | 1.13%   |
| 6.2.9   | 4         | 0.91%   |
| 5.16.7  | 4         | 0.91%   |
| 6.7.0   | 3         | 0.68%   |
| 6.5.5   | 3         | 0.68%   |
| 6.5.0   | 3         | 0.68%   |
| 5.9.16  | 3         | 0.68%   |
| 5.17.5  | 3         | 0.68%   |
| 4.9.20  | 3         | 0.68%   |
| 4.4.0   | 3         | 0.68%   |
| 6.6.9   | 2         | 0.45%   |
| 6.6.6   | 2         | 0.45%   |
| 6.6.4   | 2         | 0.45%   |
| 6.6.3   | 2         | 0.45%   |
| 6.5.7   | 2         | 0.45%   |
| 6.5.6   | 2         | 0.45%   |
| 6.4.7   | 2         | 0.45%   |
| 6.4.11  | 2         | 0.45%   |
| 6.3.5   | 2         | 0.45%   |
| 6.3.0   | 2         | 0.45%   |
| 6.1.52  | 2         | 0.45%   |
| 6.1.39  | 2         | 0.45%   |
| 6.1.1   | 2         | 0.45%   |
| 6.0.12  | 2         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 77        | 17.78%  |
| 5.15    | 55        | 12.7%   |
| 6.2     | 35        | 8.08%   |
| 5.13    | 25        | 5.77%   |
| 5.10    | 20        | 4.62%   |
| 6.1     | 19        | 4.39%   |
| 5.3     | 19        | 4.39%   |
| 5.11    | 18        | 4.16%   |
| 5.19    | 17        | 3.93%   |
| 5.8     | 15        | 3.46%   |
| 6.0     | 14        | 3.23%   |
| 5.16    | 13        | 3%      |
| 6.5     | 12        | 2.77%   |
| 4.15    | 11        | 2.54%   |
| 6.6     | 10        | 2.31%   |
| 6.4     | 9         | 2.08%   |
| 5.18    | 8         | 1.85%   |
| 5.0     | 8         | 1.85%   |
| 4.18    | 7         | 1.62%   |
| 6.3     | 6         | 1.39%   |
| 5.9     | 5         | 1.15%   |
| 5.17    | 5         | 1.15%   |
| 4.19    | 5         | 1.15%   |
| 6.7     | 3         | 0.69%   |
| 5.6     | 3         | 0.69%   |
| 5.14    | 3         | 0.69%   |
| 4.9     | 3         | 0.69%   |
| 4.4     | 3         | 0.69%   |
| 5.12    | 2         | 0.46%   |
| 5.7     | 1         | 0.23%   |
| 5.2     | 1         | 0.23%   |
| 3.8     | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 377       | 97.42%  |
| i686   | 9         | 2.33%   |
| armv7l | 1         | 0.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 197       | 48.64%  |
| KDE5          | 75        | 18.52%  |
| XFCE          | 36        | 8.89%   |
| X-Cinnamon    | 25        | 6.17%   |
| Unknown       | 23        | 5.68%   |
| KDE           | 12        | 2.96%   |
| MATE          | 7         | 1.73%   |
| LXQt          | 5         | 1.23%   |
| Pantheon      | 4         | 0.99%   |
| Hyprland      | 3         | 0.74%   |
| Budgie        | 3         | 0.74%   |
| Cinnamon      | 2         | 0.49%   |
| Unity         | 1         | 0.25%   |
| sway          | 1         | 0.25%   |
| river         | 1         | 0.25%   |
| pika:GNOME    | 1         | 0.25%   |
| Openbox       | 1         | 0.25%   |
| LXDE          | 1         | 0.25%   |
| GNOME Classic | 1         | 0.25%   |
| dwm           | 1         | 0.25%   |
| default       | 1         | 0.25%   |
| Deepin        | 1         | 0.25%   |
| Cutefish      | 1         | 0.25%   |
| BunsenLabs    | 1         | 0.25%   |
| bspwm         | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 294       | 74.06%  |
| Wayland | 88        | 22.17%  |
| Unknown | 12        | 3.02%   |
| Tty     | 3         | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 203       | 50.37%  |
| SDDM    | 55        | 13.65%  |
| GDM3    | 52        | 12.9%   |
| GDM     | 47        | 11.66%  |
| LightDM | 37        | 9.18%   |
| TDM     | 6         | 1.49%   |
| SLiM    | 1         | 0.25%   |
| MDM     | 1         | 0.25%   |
| LXDM    | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_PH   | 176       | 44.56%  |
| en_US   | 166       | 42.03%  |
| Unknown | 23        | 5.82%   |
| C       | 9         | 2.28%   |
| de_DE   | 6         | 1.52%   |
| en_GB   | 5         | 1.27%   |
| en_AU   | 2         | 0.51%   |
| zh_HK   | 1         | 0.25%   |
| zh_CN   | 1         | 0.25%   |
| tl_PH   | 1         | 0.25%   |
| en_ZA   | 1         | 0.25%   |
| en_NZ   | 1         | 0.25%   |
| en_IN   | 1         | 0.25%   |
| en_DK   | 1         | 0.25%   |
| en_CA   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 213       | 53.25%  |
| BIOS | 187       | 46.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 277       | 69.6%   |
| Btrfs   | 63        | 15.83%  |
| Overlay | 33        | 8.29%   |
| Tmpfs   | 9         | 2.26%   |
| Unknown | 7         | 1.76%   |
| Xfs     | 4         | 1.01%   |
| Ext2    | 3         | 0.75%   |
| Zfs     | 2         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 210       | 52.37%  |
| GPT     | 155       | 38.65%  |
| MBR     | 36        | 8.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 358       | 91.79%  |
| Yes       | 32        | 8.21%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 282       | 71.76%  |
| Yes       | 111       | 28.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 85        | 22.02%  |
| Acer                | 73        | 18.91%  |
| Hewlett-Packard     | 55        | 14.25%  |
| ASUSTek Computer    | 44        | 11.4%   |
| Dell                | 41        | 10.62%  |
| Toshiba             | 14        | 3.63%   |
| MSI                 | 10        | 2.59%   |
| Valve               | 8         | 2.07%   |
| Apple               | 8         | 2.07%   |
| Unknown             | 8         | 2.07%   |
| Samsung Electronics | 7         | 1.81%   |
| HUAWEI              | 5         | 1.3%    |
| Sony                | 4         | 1.04%   |
| Clevo               | 4         | 1.04%   |
| NEC Computers       | 3         | 0.78%   |
| Google              | 3         | 0.78%   |
| eMachines           | 3         | 0.78%   |
| Jumper              | 2         | 0.52%   |
| Gigabyte Technology | 2         | 0.52%   |
| realme              | 1         | 0.26%   |
| PERSONA             | 1         | 0.26%   |
| Notebook            | 1         | 0.26%   |
| HASEE Computer      | 1         | 0.26%   |
| Fujitsu             | 1         | 0.26%   |
| Cubix               | 1         | 0.26%   |
| ALLDOCUBE           | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 11        | 2.85%   |
| Valve Jupiter                            | 8         | 2.07%   |
| Acer Aspire ES1-132                      | 6         | 1.55%   |
| HP Notebook                              | 3         | 0.78%   |
| Clevo M7x0S                              | 3         | 0.78%   |
| Acer Aspire A315-51                      | 3         | 0.78%   |
| MSI Modern 14 B4MW                       | 2         | 0.52%   |
| Lenovo V110-14IAP 80TF                   | 2         | 0.52%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 2         | 0.52%   |
| Lenovo IdeaPad 100-15IBY 80MJ            | 2         | 0.52%   |
| Jumper EZbook                            | 2         | 0.52%   |
| HP Pavilion Notebook                     | 2         | 0.52%   |
| HP Pavilion Gaming Laptop 15-ec2xxx      | 2         | 0.52%   |
| HP Pavilion Gaming Laptop 15-dk2xxx      | 2         | 0.52%   |
| HP EliteBook 840 G6                      | 2         | 0.52%   |
| eMachines eM350                          | 2         | 0.52%   |
| Dell Vostro 5515                         | 2         | 0.52%   |
| Dell Latitude E7450                      | 2         | 0.52%   |
| Dell Inspiron 7472                       | 2         | 0.52%   |
| Dell Inspiron 5567                       | 2         | 0.52%   |
| ASUS X540NA                              | 2         | 0.52%   |
| ASUS X510UQ                              | 2         | 0.52%   |
| ASUS VivoBook_ASUSLaptop M1603QA_M1603QA | 2         | 0.52%   |
| Apple MacBookPro5,5                      | 2         | 0.52%   |
| Apple MacBookAir3,1                      | 2         | 0.52%   |
| Acer TravelMate P249-G2-M                | 2         | 0.52%   |
| Acer TravelMate B113                     | 2         | 0.52%   |
| Acer Swift SF314-57                      | 2         | 0.52%   |
| Acer Nitro AN515-55                      | 2         | 0.52%   |
| Acer Aspire E5-551G                      | 2         | 0.52%   |
| Acer Aspire E5-473G                      | 2         | 0.52%   |
| Acer Aspire E3-111                       | 2         | 0.52%   |
| Acer Aspire A315-41G                     | 2         | 0.52%   |
| Toshiba TECRA Z50-C                      | 1         | 0.26%   |
| Toshiba TECRA R940                       | 1         | 0.26%   |
| Toshiba Satellite Pro U400               | 1         | 0.26%   |
| Toshiba Satellite P845                   | 1         | 0.26%   |
| Toshiba Satellite L855                   | 1         | 0.26%   |
| Toshiba Satellite L515                   | 1         | 0.26%   |
| Toshiba Satellite E45t-A                 | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 49        | 12.69%  |
| Lenovo ThinkPad   | 40        | 10.36%  |
| Lenovo IdeaPad    | 32        | 8.29%   |
| Dell Inspiron     | 20        | 5.18%   |
| HP Pavilion       | 16        | 4.15%   |
| Unknown           | 11        | 2.85%   |
| ASUS VivoBook     | 10        | 2.59%   |
| HP Laptop         | 9         | 2.33%   |
| Dell Latitude     | 9         | 2.33%   |
| Valve Jupiter     | 8         | 2.07%   |
| Toshiba Satellite | 8         | 2.07%   |
| Acer TravelMate   | 8         | 2.07%   |
| HP ProBook        | 6         | 1.55%   |
| HP EliteBook      | 6         | 1.55%   |
| Acer Nitro        | 5         | 1.3%    |
| Lenovo Legion     | 4         | 1.04%   |
| Dell Vostro       | 4         | 1.04%   |
| ASUS TUF          | 4         | 1.04%   |
| ASUS ROG          | 4         | 1.04%   |
| Acer Swift        | 4         | 1.04%   |
| HP Notebook       | 3         | 0.78%   |
| Dell XPS          | 3         | 0.78%   |
| Dell Precision    | 3         | 0.78%   |
| Clevo M7x0S       | 3         | 0.78%   |
| Acer Predator     | 3         | 0.78%   |
| Toshiba TECRA     | 2         | 0.52%   |
| Toshiba dynabook  | 2         | 0.52%   |
| MSI Modern        | 2         | 0.52%   |
| MSI CX62          | 2         | 0.52%   |
| Lenovo V110-14IAP | 2         | 0.52%   |
| Jumper EZbook     | 2         | 0.52%   |
| HP Stream         | 2         | 0.52%   |
| HP OMEN           | 2         | 0.52%   |
| HP ENVY           | 2         | 0.52%   |
| eMachines eM350   | 2         | 0.52%   |
| ASUS X540NA       | 2         | 0.52%   |
| ASUS X510UQ       | 2         | 0.52%   |
| ASUS ASUS         | 2         | 0.52%   |
| Apple MacBookPro5 | 2         | 0.52%   |
| Apple MacBookAir3 | 2         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 34        | 8.81%   |
| 2016    | 34        | 8.81%   |
| 2012    | 34        | 8.81%   |
| 2017    | 32        | 8.29%   |
| 2021    | 31        | 8.03%   |
| 2018    | 29        | 7.51%   |
| 2020    | 28        | 7.25%   |
| 2014    | 25        | 6.48%   |
| 2011    | 25        | 6.48%   |
| 2022    | 22        | 5.7%    |
| 2010    | 20        | 5.18%   |
| 2015    | 19        | 4.92%   |
| 2013    | 14        | 3.63%   |
| 2009    | 12        | 3.11%   |
| 2008    | 12        | 3.11%   |
| 2023    | 7         | 1.81%   |
| 2007    | 3         | 0.78%   |
| 2006    | 3         | 0.78%   |
| Unknown | 2         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 386       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 335       | 86.12%  |
| Enabled  | 54        | 13.88%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 383       | 99.22%  |
| Yes  | 3         | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 107       | 27.23%  |
| 3.01-4.0    | 85        | 21.63%  |
| 8.01-16.0   | 73        | 18.58%  |
| 16.01-24.0  | 58        | 14.76%  |
| 1.01-2.0    | 41        | 10.43%  |
| 32.01-64.0  | 14        | 3.56%   |
| 2.01-3.0    | 8         | 2.04%   |
| 0.51-1.0    | 4         | 1.02%   |
| 24.01-32.0  | 2         | 0.51%   |
| 64.01-256.0 | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 142       | 32.42%  |
| 1.01-2.0  | 137       | 31.28%  |
| 4.01-8.0  | 62        | 14.16%  |
| 3.01-4.0  | 56        | 12.79%  |
| 0.51-1.0  | 26        | 5.94%   |
| 8.01-16.0 | 13        | 2.97%   |
| 0.01-0.5  | 1         | 0.23%   |
| Unknown   | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 283       | 71.28%  |
| 2      | 96        | 24.18%  |
| 3      | 14        | 3.53%   |
| 0      | 2         | 0.5%    |
| 5      | 1         | 0.25%   |
| 4      | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 266       | 68.21%  |
| Yes       | 124       | 31.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 302       | 78.04%  |
| No        | 85        | 21.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 378       | 97.93%  |
| No        | 8         | 2.07%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 314       | 80.31%  |
| No        | 77        | 19.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Philippines | 386       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Quezon City         | 57        | 13.35%  |
| Cebu City           | 35        | 8.2%    |
| Manila              | 22        | 5.15%   |
| Davao City          | 21        | 4.92%   |
| Angeles City        | 17        | 3.98%   |
| Pasig               | 14        | 3.28%   |
| Paranaque City      | 14        | 3.28%   |
| Makati City         | 13        | 3.04%   |
| Caloocan City       | 13        | 3.04%   |
| Bacolod City        | 12        | 2.81%   |
| Lahug               | 11        | 2.58%   |
| Cagayan de Oro      | 9         | 2.11%   |
| Bacoor              | 9         | 2.11%   |
| San Jose del Monte  | 8         | 1.87%   |
| Iloilo City         | 8         | 1.87%   |
| Mandaluyong City    | 7         | 1.64%   |
| Santa Rosa          | 6         | 1.41%   |
| San Miguel          | 6         | 1.41%   |
| San Fernando City   | 6         | 1.41%   |
| Las Pinas           | 6         | 1.41%   |
| Imus                | 6         | 1.41%   |
| Tarlac City         | 5         | 1.17%   |
| San Pablo City      | 5         | 1.17%   |
| Manajao             | 5         | 1.17%   |
| Dasmarinas          | 5         | 1.17%   |
| City of Muntinglupa | 5         | 1.17%   |
| Calamba             | 5         | 1.17%   |
| Malolos             | 4         | 0.94%   |
| Legazpi             | 4         | 0.94%   |
| Baguio City         | 4         | 0.94%   |
| San Pedro           | 3         | 0.7%    |
| San Juan            | 3         | 0.7%    |
| Lucena City         | 3         | 0.7%    |
| La Trinidad         | 3         | 0.7%    |
| Iligan City         | 3         | 0.7%    |
| General Santos      | 3         | 0.7%    |
| Zamboanga City      | 2         | 0.47%   |
| Taytay              | 2         | 0.47%   |
| Talisay City        | 2         | 0.47%   |
| Tagbilaran          | 2         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 65        | 88     | 13.05%  |
| WDC                         | 61        | 68     | 12.25%  |
| Toshiba                     | 54        | 71     | 10.84%  |
| Samsung Electronics         | 48        | 64     | 9.64%   |
| SanDisk                     | 29        | 38     | 5.82%   |
| Unknown                     | 28        | 35     | 5.62%   |
| Kingston                    | 26        | 28     | 5.22%   |
| SK hynix                    | 20        | 27     | 4.02%   |
| Intel                       | 15        | 18     | 3.01%   |
| Hitachi                     | 15        | 21     | 3.01%   |
| HGST                        | 13        | 14     | 2.61%   |
| Micron Technology           | 11        | 17     | 2.21%   |
| Ramsta                      | 8         | 9      | 1.61%   |
| China                       | 7         | 8      | 1.41%   |
| Crucial                     | 6         | 6      | 1.2%    |
| A-DATA Technology           | 6         | 10     | 1.2%    |
| Phison                      | 4         | 4      | 0.8%    |
| Apple                       | 4         | 4      | 0.8%    |
| Team                        | 3         | 5      | 0.6%    |
| Silicon Motion              | 3         | 4      | 0.6%    |
| Phison Electronics          | 3         | 4      | 0.6%    |
| Micron/Crucial Technology   | 3         | 3      | 0.6%    |
| LITEONIT                    | 3         | 5      | 0.6%    |
| Kingston Technology Company | 3         | 3      | 0.6%    |
| JMicron Technology          | 3         | 6      | 0.6%    |
| Fujitsu                     | 3         | 4      | 0.6%    |
| USB3.0                      | 2         | 2      | 0.4%    |
| TAMMUZ                      | 2         | 5      | 0.4%    |
| ShiJi                       | 2         | 2      | 0.4%    |
| O2 Micro                    | 2         | 2      | 0.4%    |
| Netac                       | 2         | 2      | 0.4%    |
| Lite-On                     | 2         | 4      | 0.4%    |
| KingSpec                    | 2         | 3      | 0.4%    |
| Indilinx                    | 2         | 2      | 0.4%    |
| HS-SSD-E100                 | 2         | 2      | 0.4%    |
| HS-SSD-C100                 | 2         | 3      | 0.4%    |
| Unknown                     | 2         | 2      | 0.4%    |
| WALRAM                      | 1         | 1      | 0.2%    |
| Vaseky                      | 1         | 2      | 0.2%    |
| UMIS                        | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                          | 17        | 3.28%   |
| Seagate ST1000LM035-1RK172 1TB                    | 15        | 2.9%    |
| WDC WD5000LPCX-21VHAT0 500GB                      | 7         | 1.35%   |
| Unknown MMC Card  32GB                            | 7         | 1.35%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 6         | 1.16%   |
| Toshiba MQ04ABF100 1TB                            | 6         | 1.16%   |
| Kingston SA400S37240G 240GB SSD                   | 6         | 1.16%   |
| Toshiba MQ01ABD100 1TB                            | 5         | 0.97%   |
| Seagate ST500LT012-9WS142 500GB                   | 5         | 0.97%   |
| Seagate ST500LT012-1DG142 500GB                   | 5         | 0.97%   |
| HGST HTS721010A9E630 1TB                          | 5         | 0.97%   |
| Unknown MMC Card  128GB                           | 4         | 0.77%   |
| Seagate ST2000LM007-1R8174 2TB                    | 4         | 0.77%   |
| Seagate ST1000LM049-2GH172 1TB                    | 4         | 0.77%   |
| Kingston SA400S37120G 120GB SSD                   | 4         | 0.77%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 3         | 0.58%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 3         | 0.58%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 3         | 0.58%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 3         | 0.58%   |
| Unknown MMC Card  64GB                            | 3         | 0.58%   |
| SK hynix NVMe SSD Drive 512GB                     | 3         | 0.58%   |
| Seagate ST9500325AS 500GB                         | 3         | 0.58%   |
| Seagate ST500LM030-2E717D 500GB                   | 3         | 0.58%   |
| Seagate ST500LM030-1RK17D 500GB                   | 3         | 0.58%   |
| Seagate ST1000LM048-2E7172 1TB                    | 3         | 0.58%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB  | 3         | 0.58%   |
| Samsung NVMe SSD Drive 512GB                      | 3         | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 0.58%   |
| Phison PS5013 E13 NVMe Controller 256GB           | 3         | 0.58%   |
| Micron NVMe SSD Drive 512GB                       | 3         | 0.58%   |
| Intel SSDPEKNU512GZ 512GB                         | 3         | 0.58%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 2         | 0.39%   |
| WDC WD5000LPVX-80V0TT0 500GB                      | 2         | 0.39%   |
| WDC WD5000LPCX-24C6HT0 500GB                      | 2         | 0.39%   |
| WDC WD10SPZX-24Z10 1TB                            | 2         | 0.39%   |
| USB3.0 Super Speed 500GB SSD                      | 2         | 0.39%   |
| Unknown SD/MMC/MS PRO 256GB                       | 2         | 0.39%   |
| Unknown MMC Card  7GB                             | 2         | 0.39%   |
| Unknown MMC Card  256GB                           | 2         | 0.39%   |
| Unknown DA4032  32GB                              | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 88     | 32.34%  |
| WDC                 | 51        | 57     | 25.37%  |
| Toshiba             | 46        | 60     | 22.89%  |
| Hitachi             | 15        | 21     | 7.46%   |
| HGST                | 13        | 14     | 6.47%   |
| Fujitsu             | 3         | 4      | 1.49%   |
| Unknown             | 2         | 2      | 1%      |
| Samsung Electronics | 2         | 2      | 1%      |
| JMicron Technology  | 2         | 2      | 1%      |
| SAGE                | 1         | 1      | 0.5%    |
| HGST HTS            | 1         | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 23     | 13.97%  |
| Kingston            | 18        | 18     | 13.24%  |
| SanDisk             | 13        | 16     | 9.56%   |
| Ramsta              | 8         | 9      | 5.88%   |
| China               | 7         | 8      | 5.15%   |
| WDC                 | 5         | 6      | 3.68%   |
| Micron Technology   | 5         | 5      | 3.68%   |
| Crucial             | 5         | 5      | 3.68%   |
| Toshiba             | 4         | 6      | 2.94%   |
| SK hynix            | 4         | 9      | 2.94%   |
| Apple               | 4         | 4      | 2.94%   |
| A-DATA Technology   | 4         | 7      | 2.94%   |
| Team                | 3         | 5      | 2.21%   |
| LITEONIT            | 3         | 5      | 2.21%   |
| USB3.0              | 2         | 2      | 1.47%   |
| TAMMUZ              | 2         | 5      | 1.47%   |
| Netac               | 2         | 2      | 1.47%   |
| KingSpec            | 2         | 3      | 1.47%   |
| Intel               | 2         | 2      | 1.47%   |
| HS-SSD-E100         | 2         | 2      | 1.47%   |
| Vaseky              | 1         | 2      | 0.74%   |
| Transcend           | 1         | 1      | 0.74%   |
| Teclast             | 1         | 4      | 0.74%   |
| ShiJi               | 1         | 1      | 0.74%   |
| SADAYU              | 1         | 1      | 0.74%   |
| PNY                 | 1         | 1      | 0.74%   |
| Plextor             | 1         | 1      | 0.74%   |
| Phison              | 1         | 1      | 0.74%   |
| OCZ                 | 1         | 1      | 0.74%   |
| NT-512              | 1         | 1      | 0.74%   |
| Kingmax             | 1         | 1      | 0.74%   |
| KimMiDi             | 1         | 1      | 0.74%   |
| Indilinx            | 1         | 1      | 0.74%   |
| HS-SSD-C100         | 1         | 1      | 0.74%   |
| Hikvision           | 1         | 1      | 0.74%   |
| Gigabyte Technology | 1         | 1      | 0.74%   |
| GALAX               | 1         | 1      | 0.74%   |
| DTGC-C              | 1         | 1      | 0.74%   |
| Colorful            | 1         | 1      | 0.74%   |
| CERVVO              | 1         | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 192       | 252    | 40.94%  |
| SSD     | 126       | 169    | 26.87%  |
| NVMe    | 115       | 165    | 24.52%  |
| MMC     | 29        | 36     | 6.18%   |
| Unknown | 7         | 11     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 289       | 406    | 63.24%  |
| NVMe | 115       | 164    | 25.16%  |
| MMC  | 29        | 36     | 6.35%   |
| SAS  | 24        | 27     | 5.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 225       | 299    | 70.98%  |
| 0.51-1.0   | 83        | 109    | 26.18%  |
| 1.01-2.0   | 7         | 11     | 2.21%   |
| 3.01-4.0   | 2         | 2      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 112       | 27.79%  |
| 251-500        | 111       | 27.54%  |
| 501-1000       | 62        | 15.38%  |
| 1001-2000      | 34        | 8.44%   |
| 1-20           | 34        | 8.44%   |
| 51-100         | 22        | 5.46%   |
| 21-50          | 15        | 3.72%   |
| More than 3000 | 5         | 1.24%   |
| 2001-3000      | 4         | 0.99%   |
| Unknown        | 4         | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 165       | 38.28%  |
| 21-50     | 90        | 20.88%  |
| 51-100    | 64        | 14.85%  |
| 101-250   | 59        | 13.69%  |
| 251-500   | 31        | 7.19%   |
| 501-1000  | 14        | 3.25%   |
| Unknown   | 4         | 0.93%   |
| 1001-2000 | 3         | 0.7%    |
| 2001-3000 | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB                       | 2         | 2      | 6.45%   |
| Seagate ST2000LM007-1R8174 2TB                 | 2         | 3      | 6.45%   |
| Seagate ST1000LM048-2E7172 1TB                 | 2         | 2      | 6.45%   |
| WDC WD5000LPVT-75G33T0 500GB                   | 1         | 1      | 3.23%   |
| WDC WD5000LPVT-22G33T0 500GB                   | 1         | 1      | 3.23%   |
| WDC WD3200BEVT-22A23T0 320GB                   | 1         | 1      | 3.23%   |
| WDC WD1600BEVT-24A23T0 160GB                   | 1         | 1      | 3.23%   |
| WDC WD10JPVX-60JC3T1 1TB                       | 1         | 2      | 3.23%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 3.23%   |
| Toshiba MK6465GSX 640GB                        | 1         | 1      | 3.23%   |
| Toshiba MK3259GSXP 320GB                       | 1         | 1      | 3.23%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD          | 1         | 1      | 3.23%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 3.23%   |
| Seagate ST9120821AS 120GB                      | 1         | 1      | 3.23%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 3.23%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1         | 1      | 3.23%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 3.23%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 3.23%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 3.23%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 3.23%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 2      | 3.23%   |
| Hitachi HTS545050B9SA00 500GB                  | 1         | 1      | 3.23%   |
| Hitachi HTS542525K9SA00 250GB                  | 1         | 1      | 3.23%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 3.23%   |
| Fujitsu MHY2120BH 120GB                        | 1         | 1      | 3.23%   |
| Colorful SL300 128GB SSD                       | 1         | 1      | 3.23%   |
| A-DATA Technology SX6000PNP 512GB              | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 9         | 10     | 29.03%  |
| WDC               | 6         | 7      | 19.35%  |
| Toshiba           | 5         | 5      | 16.13%  |
| Hitachi           | 3         | 4      | 9.68%   |
| SK hynix          | 1         | 1      | 3.23%   |
| Ramsta            | 1         | 1      | 3.23%   |
| Micron Technology | 1         | 1      | 3.23%   |
| Kingston          | 1         | 1      | 3.23%   |
| HGST              | 1         | 1      | 3.23%   |
| Fujitsu           | 1         | 1      | 3.23%   |
| Colorful          | 1         | 1      | 3.23%   |
| A-DATA Technology | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 36%     |
| WDC     | 6         | 7      | 24%     |
| Toshiba | 5         | 5      | 20%     |
| Hitachi | 3         | 4      | 12%     |
| HGST    | 1         | 1      | 4%      |
| Fujitsu | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 28     | 80%     |
| SSD  | 5         | 5      | 16.67%  |
| NVMe | 1         | 1      | 3.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 243       | 398    | 58.13%  |
| Works    | 145       | 200    | 34.69%  |
| Malfunc  | 29        | 34     | 6.94%   |
| Failed   | 1         | 1      | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 287       | 63.78%  |
| AMD                              | 43        | 9.56%   |
| Samsung Electronics              | 28        | 6.22%   |
| SanDisk                          | 17        | 3.78%   |
| SK hynix                         | 16        | 3.56%   |
| Kingston Technology Company      | 10        | 2.22%   |
| Nvidia                           | 8         | 1.78%   |
| Phison Electronics               | 7         | 1.56%   |
| Micron Technology                | 6         | 1.33%   |
| Toshiba America Info Systems     | 4         | 0.89%   |
| Micron/Crucial Technology        | 4         | 0.89%   |
| Silicon Motion                   | 3         | 0.67%   |
| Silicon Integrated Systems [SiS] | 3         | 0.67%   |
| Solid State Storage Technology   | 2         | 0.44%   |
| O2 Micro                         | 2         | 0.44%   |
| Lite-On Technology               | 2         | 0.44%   |
| ADATA Technology                 | 2         | 0.44%   |
| Union Memory (Shenzhen)          | 1         | 0.22%   |
| Shenzhen Longsys Electronics     | 1         | 0.22%   |
| Realtek Semiconductor            | 1         | 0.22%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.22%   |
| Lenovo                           | 1         | 0.22%   |
| KIOXIA                           | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 40        | 8.15%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 38        | 7.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 32        | 6.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 30        | 6.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 20        | 4.07%   |
| Intel Volume Management Device NVMe RAID Controller                              | 17        | 3.46%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 16        | 3.26%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 14        | 2.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 2.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 10        | 2.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 2.04%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 8         | 1.63%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 8         | 1.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 1.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 1.43%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 1.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 1.43%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 1.22%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 5         | 1.02%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 5         | 1.02%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 4         | 0.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 4         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.81%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.61%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.61%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.61%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3         | 0.61%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 3         | 0.61%   |
| Intel SSD 660P Series                                                            | 3         | 0.61%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 3         | 0.61%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 2         | 0.41%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 2         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 285       | 60.38%  |
| NVMe | 115       | 24.36%  |
| RAID | 49        | 10.38%  |
| IDE  | 23        | 4.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 317       | 82.12%  |
| AMD    | 68        | 17.62%  |
| ARM    | 1         | 0.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 2.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 2.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 2.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 2.07%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 8         | 2.07%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 2.07%   |
| AMD Custom APU 0405                           | 8         | 2.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 1.55%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 1.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.3%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 5         | 1.3%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 1.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 1.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.04%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.04%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.04%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.04%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.78%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 3         | 0.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.78%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 3         | 0.78%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.78%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.78%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 3         | 0.78%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.78%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.78%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.78%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 102       | 26.42%  |
| Intel Core i7           | 62        | 16.06%  |
| Intel Celeron           | 40        | 10.36%  |
| Intel Core i3           | 37        | 9.59%   |
| Other                   | 35        | 9.07%   |
| AMD Ryzen 5             | 16        | 4.15%   |
| Intel Core 2 Duo        | 13        | 3.37%   |
| Intel Atom              | 12        | 3.11%   |
| AMD Ryzen 7             | 10        | 2.59%   |
| Intel Pentium           | 9         | 2.33%   |
| AMD Ryzen 3             | 8         | 2.07%   |
| Intel Pentium Silver    | 4         | 1.04%   |
| Intel Pentium Dual-Core | 4         | 1.04%   |
| AMD A8                  | 4         | 1.04%   |
| AMD A6                  | 4         | 1.04%   |
| AMD Athlon              | 3         | 0.78%   |
| Intel Genuine           | 2         | 0.52%   |
| Intel Core m3           | 2         | 0.52%   |
| AMD Turion 64 X2 Mobile | 2         | 0.52%   |
| AMD A10                 | 2         | 0.52%   |
| Intel Pentium Dual      | 1         | 0.26%   |
| Intel Core m5           | 1         | 0.26%   |
| Intel Core 2            | 1         | 0.26%   |
| Intel Celeron M         | 1         | 0.26%   |
| AMD Turion 64 Mobile    | 1         | 0.26%   |
| AMD Ryzen 9             | 1         | 0.26%   |
| AMD Ryzen 7 PRO         | 1         | 0.26%   |
| AMD Quad-Core           | 1         | 0.26%   |
| AMD PRO A10             | 1         | 0.26%   |
| AMD FX                  | 1         | 0.26%   |
| AMD E2                  | 1         | 0.26%   |
| AMD E1                  | 1         | 0.26%   |
| AMD E                   | 1         | 0.26%   |
| AMD C-60                | 1         | 0.26%   |
| AMD A4                  | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 196       | 50.78%  |
| 4      | 141       | 36.53%  |
| 6      | 19        | 4.92%   |
| 8      | 11        | 2.85%   |
| 1      | 11        | 2.85%   |
| 14     | 3         | 0.78%   |
| 10     | 3         | 0.78%   |
| 24     | 1         | 0.26%   |
| 12     | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 386       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 283       | 73.32%  |
| 1      | 103       | 26.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 377       | 97.42%  |
| Unknown        | 6         | 1.55%   |
| 32-bit         | 4         | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 143       | 35.48%  |
| 0x306a9    | 24        | 5.96%   |
| 0x206a7    | 18        | 4.47%   |
| 0x406e3    | 14        | 3.47%   |
| 0x506c9    | 13        | 3.23%   |
| 0x806ea    | 11        | 2.73%   |
| 0x1067a    | 11        | 2.73%   |
| 0x806ec    | 10        | 2.48%   |
| 0x806e9    | 10        | 2.48%   |
| 0x30678    | 10        | 2.48%   |
| 0x306d4    | 8         | 1.99%   |
| 0x0a50000c | 7         | 1.74%   |
| 0x806c1    | 6         | 1.49%   |
| 0x906ea    | 5         | 1.24%   |
| 0x706e5    | 5         | 1.24%   |
| 0x406c4    | 5         | 1.24%   |
| 0x40651    | 5         | 1.24%   |
| 0x306c3    | 5         | 1.24%   |
| 0x20655    | 5         | 1.24%   |
| 0x106ca    | 5         | 1.24%   |
| 0xa0652    | 4         | 0.99%   |
| 0x706a1    | 4         | 0.99%   |
| 0x10676    | 4         | 0.99%   |
| 0x08608103 | 4         | 0.99%   |
| 0x08108109 | 4         | 0.99%   |
| 0x906e9    | 3         | 0.74%   |
| 0x906a4    | 3         | 0.74%   |
| 0x806eb    | 3         | 0.74%   |
| 0x406c3    | 3         | 0.74%   |
| 0x20652    | 3         | 0.74%   |
| 0x08600104 | 3         | 0.74%   |
| 0x07030105 | 3         | 0.74%   |
| 0x06003106 | 3         | 0.74%   |
| 0x906c0    | 2         | 0.5%    |
| 0x906a3    | 2         | 0.5%    |
| 0x706a8    | 2         | 0.5%    |
| 0x6ec      | 2         | 0.5%    |
| 0x506e3    | 2         | 0.5%    |
| 0x30661    | 2         | 0.5%    |
| 0x0a50000d | 2         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 72        | 18.56%  |
| IvyBridge        | 38        | 9.79%   |
| Skylake          | 24        | 6.19%   |
| SandyBridge      | 23        | 5.93%   |
| Silvermont       | 20        | 5.15%   |
| Unknown          | 19        | 4.9%    |
| Penryn           | 18        | 4.64%   |
| Haswell          | 16        | 4.12%   |
| Goldmont         | 16        | 4.12%   |
| TigerLake        | 15        | 3.87%   |
| Broadwell        | 15        | 3.87%   |
| Zen 3            | 12        | 3.09%   |
| Zen+             | 10        | 2.58%   |
| Westmere         | 10        | 2.58%   |
| Bonnell          | 9         | 2.32%   |
| Alderlake Hybrid | 9         | 2.32%   |
| Goldmont plus    | 8         | 2.06%   |
| CometLake        | 8         | 2.06%   |
| Zen 2            | 6         | 1.55%   |
| IceLake          | 6         | 1.55%   |
| Puma             | 5         | 1.29%   |
| K8 Hammer        | 4         | 1.03%   |
| Zen              | 3         | 0.77%   |
| Steamroller      | 3         | 0.77%   |
| P6               | 3         | 0.77%   |
| Excavator        | 3         | 0.77%   |
| Core             | 3         | 0.77%   |
| Tremont          | 2         | 0.52%   |
| Piledriver       | 2         | 0.52%   |
| Jaguar           | 2         | 0.52%   |
| Bobcat           | 2         | 0.52%   |
| K8 & K10 hybrid  | 1         | 0.26%   |
| K10 Llano        | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 303       | 60.84%  |
| Nvidia                           | 100       | 20.08%  |
| AMD                              | 92        | 18.47%  |
| Silicon Integrated Systems [SiS] | 3         | 0.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 38        | 7.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 4.5%    |
| Intel UHD Graphics 620                                                                   | 19        | 3.72%   |
| Intel HD Graphics 620                                                                    | 17        | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 3.13%   |
| Intel HD Graphics 500                                                                    | 14        | 2.74%   |
| Intel HD Graphics 5500                                                                   | 13        | 2.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 2.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 2.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 2.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.76%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 1.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.57%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 8         | 1.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 1.37%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 7         | 1.37%   |
| Intel HD Graphics 630                                                                    | 7         | 1.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.37%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 1.37%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.17%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 6         | 1.17%   |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 0.98%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.98%   |
| AMD Lucienne                                                                             | 5         | 0.98%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.78%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 4         | 0.78%   |
| Intel HD Graphics 530                                                                    | 4         | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.78%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 198       | 51.03%  |
| Intel + Nvidia | 78        | 20.1%   |
| 1 x AMD        | 49        | 12.63%  |
| Intel + AMD    | 25        | 6.44%   |
| 1 x Nvidia     | 13        | 3.35%   |
| AMD + Nvidia   | 10        | 2.58%   |
| 2 x AMD        | 9         | 2.32%   |
| 1 x SiS        | 3         | 0.77%   |
| 2 x Intel      | 2         | 0.52%   |
| Other          | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 326       | 83.38%  |
| Proprietary | 58        | 14.83%  |
| Unknown     | 7         | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 280       | 70.35%  |
| 1.01-2.0   | 38        | 9.55%   |
| 0.01-0.5   | 37        | 9.3%    |
| 3.01-4.0   | 19        | 4.77%   |
| 0.51-1.0   | 16        | 4.02%   |
| 7.01-8.0   | 4         | 1.01%   |
| 5.01-6.0   | 3         | 0.75%   |
| 8.01-16.0  | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 77        | 17.99%  |
| AU Optronics            | 69        | 16.12%  |
| BOE                     | 68        | 15.89%  |
| LG Display              | 56        | 13.08%  |
| Samsung Electronics     | 35        | 8.18%   |
| Lenovo                  | 14        | 3.27%   |
| InfoVision              | 9         | 2.1%    |
| Valve                   | 8         | 1.87%   |
| Philips                 | 7         | 1.64%   |
| Goldstar                | 7         | 1.64%   |
| Apple                   | 7         | 1.64%   |
| Sharp                   | 6         | 1.4%    |
| PANDA                   | 6         | 1.4%    |
| AOC                     | 6         | 1.4%    |
| Sony                    | 5         | 1.17%   |
| Chi Mei Optoelectronics | 5         | 1.17%   |
| Acer                    | 5         | 1.17%   |
| RTK                     | 3         | 0.7%    |
| ASUSTek Computer        | 3         | 0.7%    |
| LG Philips              | 2         | 0.47%   |
| InnoLux Display         | 2         | 0.47%   |
| Hewlett-Packard         | 2         | 0.47%   |
| Gigabyte Technology     | 2         | 0.47%   |
| Dell                    | 2         | 0.47%   |
| BenQ                    | 2         | 0.47%   |
| Ancor Communications    | 2         | 0.47%   |
| ___                     | 1         | 0.23%   |
| Unknown                 | 1         | 0.23%   |
| Toshiba                 | 1         | 0.23%   |
| TMX                     | 1         | 0.23%   |
| Quanta Display          | 1         | 0.23%   |
| Pixio                   | 1         | 0.23%   |
| Panasonic               | 1         | 0.23%   |
| MYS                     | 1         | 0.23%   |
| MDA                     | 1         | 0.23%   |
| JDI                     | 1         | 0.23%   |
| IPS                     | 1         | 0.23%   |
| HKC                     | 1         | 0.23%   |
| HannStar                | 1         | 0.23%   |
| GreenWood               | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 8         | 1.87%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 7         | 1.64%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 6         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 1.17%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 4         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 4         | 0.93%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 0.7%    |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch           | 3         | 0.7%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 3         | 0.7%    |
| Lenovo LCD Monitor LEN40A0 1366x768 309x173mm 13.9-inch               | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 3         | 0.7%    |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 3         | 0.7%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO2992 1920x1080 344x193mm 15.5-inch        | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 0.7%    |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 3         | 0.7%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3549 1366x768 309x174mm 14.0-inch  | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 2         | 0.47%   |
| RTK 32V3H-H6A RTK4C54 1440x900 697x392mm 31.5-inch                    | 2         | 0.47%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 2         | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.47%   |
| LG Display LP101WSA-TLN1 LGD0295 1024x600 224x126mm 10.1-inch         | 2         | 0.47%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 2         | 0.47%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.47%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 2         | 0.47%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 2         | 0.47%   |
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch           | 2         | 0.47%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch      | 2         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 174       | 43.28%  |
| 1920x1080 (FHD)    | 142       | 35.32%  |
| 1600x900 (HD+)     | 14        | 3.48%   |
| 800x1280           | 8         | 1.99%   |
| 3840x2160 (4K)     | 7         | 1.74%   |
| 2560x1440 (QHD)    | 7         | 1.74%   |
| 1920x1200 (WUXGA)  | 7         | 1.74%   |
| 1280x800 (WXGA)    | 7         | 1.74%   |
| 1024x600           | 7         | 1.74%   |
| 2560x1600          | 5         | 1.24%   |
| 1280x1024 (SXGA)   | 5         | 1.24%   |
| 1440x900 (WXGA+)   | 4         | 1%      |
| 1360x768           | 4         | 1%      |
| 2160x1440          | 3         | 0.75%   |
| 2560x1080          | 2         | 0.5%    |
| 3840x2400          | 1         | 0.25%   |
| 3000x2000          | 1         | 0.25%   |
| 2400x1600          | 1         | 0.25%   |
| 1680x1050 (WSXGA+) | 1         | 0.25%   |
| 1280x768           | 1         | 0.25%   |
| 1024x768 (XGA)     | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 151       | 35.45%  |
| 13      | 72        | 16.9%   |
| 14      | 64        | 15.02%  |
| 11      | 21        | 4.93%   |
| 17      | 20        | 4.69%   |
| 12      | 15        | 3.52%   |
| 18      | 12        | 2.82%   |
| 27      | 10        | 2.35%   |
| 23      | 10        | 2.35%   |
| 21      | 8         | 1.88%   |
| 7       | 8         | 1.88%   |
| 10      | 7         | 1.64%   |
| 16      | 6         | 1.41%   |
| 72      | 5         | 1.17%   |
| 31      | 5         | 1.17%   |
| 24      | 4         | 0.94%   |
| 34      | 2         | 0.47%   |
| Unknown | 2         | 0.47%   |
| 84      | 1         | 0.23%   |
| 54      | 1         | 0.23%   |
| 20      | 1         | 0.23%   |
| 8       | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 266       | 63.18%  |
| 201-300     | 67        | 15.91%  |
| 401-500     | 21        | 4.99%   |
| 501-600     | 19        | 4.51%   |
| 351-400     | 19        | 4.51%   |
| 601-700     | 9         | 2.14%   |
| 1-100       | 8         | 1.9%    |
| 1501-2000   | 6         | 1.43%   |
| 701-800     | 2         | 0.48%   |
| Unknown     | 2         | 0.48%   |
| 101-200     | 1         | 0.24%   |
| 1001-1500   | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 341       | 89.27%  |
| 16/10   | 20        | 5.24%   |
| 0.67    | 8         | 2.09%   |
| 3/2     | 5         | 1.31%   |
| 5/4     | 3         | 0.79%   |
| 21/9    | 2         | 0.52%   |
| 4/3     | 1         | 0.26%   |
| 0.62    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 148       | 34.91%  |
| 81-90          | 118       | 27.83%  |
| 51-60          | 21        | 4.95%   |
| 71-80          | 18        | 4.25%   |
| 201-250        | 17        | 4.01%   |
| 121-130        | 16        | 3.77%   |
| 61-70          | 15        | 3.54%   |
| 141-150        | 15        | 3.54%   |
| 301-350        | 10        | 2.36%   |
| 1-40           | 9         | 2.12%   |
| More than 1000 | 7         | 1.65%   |
| 351-500        | 7         | 1.65%   |
| 41-50          | 7         | 1.65%   |
| 111-120        | 7         | 1.65%   |
| 151-200        | 4         | 0.94%   |
| 91-100         | 2         | 0.47%   |
| Unknown        | 2         | 0.47%   |
| 131-140        | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 171       | 40.71%  |
| 101-120       | 167       | 39.76%  |
| 51-100        | 44        | 10.48%  |
| 161-240       | 21        | 5%      |
| 1-50          | 8         | 1.9%    |
| More than 240 | 7         | 1.67%   |
| Unknown       | 2         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 333       | 83.88%  |
| 2     | 50        | 12.59%  |
| 0     | 8         | 2.02%   |
| 3     | 6         | 1.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 230       | 37.95%  |
| Intel                            | 170       | 28.05%  |
| Qualcomm Atheros                 | 104       | 17.16%  |
| Broadcom                         | 47        | 7.76%   |
| Ralink Technology                | 7         | 1.16%   |
| MediaTek                         | 6         | 0.99%   |
| Nvidia                           | 5         | 0.83%   |
| Broadcom Limited                 | 5         | 0.83%   |
| TP-Link                          | 3         | 0.5%    |
| Silicon Integrated Systems [SiS] | 3         | 0.5%    |
| Ralink                           | 3         | 0.5%    |
| Qualcomm Atheros Communications  | 3         | 0.5%    |
| Marvell Technology Group         | 3         | 0.5%    |
| ASIX Electronics                 | 3         | 0.5%    |
| OPPO Electronics                 | 2         | 0.33%   |
| JMicron Technology               | 2         | 0.33%   |
| DisplayLink                      | 2         | 0.33%   |
| NetGear                          | 1         | 0.17%   |
| Hewlett-Packard                  | 1         | 0.17%   |
| Encore Electronics               | 1         | 0.17%   |
| Dell                             | 1         | 0.17%   |
| BUFFALO                          | 1         | 0.17%   |
| ASUSTek Computer                 | 1         | 0.17%   |
| Apple                            | 1         | 0.17%   |
| AMD                              | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 137       | 19.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 42        | 5.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 23        | 3.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 20        | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 18        | 2.54%   |
| Intel Wireless 7265                                                    | 18        | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 18        | 2.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 15        | 2.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 14        | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 13        | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 12        | 1.69%   |
| Intel Wireless 3165                                                    | 12        | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 11        | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 11        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.41%   |
| Intel Wi-Fi 6 AX201                                                    | 10        | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 10        | 1.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 9         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 9         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                          | 9         | 1.27%   |
| Intel Wireless 8260                                                    | 8         | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 1.13%   |
| Realtek Killer E2600 GbE Controller                                    | 7         | 0.99%   |
| Ralink MT7601U Wireless Adapter                                        | 7         | 0.99%   |
| Intel Wireless 8265 / 8275                                             | 7         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 6         | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.71%   |
| Intel Wireless 7260                                                    | 5         | 0.71%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 0.71%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 4         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 163       | 41.16%  |
| Qualcomm Atheros                | 91        | 22.98%  |
| Realtek Semiconductor           | 76        | 19.19%  |
| Broadcom                        | 37        | 9.34%   |
| Ralink Technology               | 7         | 1.77%   |
| MediaTek                        | 6         | 1.52%   |
| TP-Link                         | 3         | 0.76%   |
| Ralink                          | 3         | 0.76%   |
| Qualcomm Atheros Communications | 3         | 0.76%   |
| Broadcom Limited                | 2         | 0.51%   |
| NetGear                         | 1         | 0.25%   |
| Encore Electronics              | 1         | 0.25%   |
| Dell                            | 1         | 0.25%   |
| BUFFALO                         | 1         | 0.25%   |
| ASUSTek Computer                | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 5.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 5.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 4.53%   |
| Intel Wireless 7265                                                     | 18        | 4.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 3.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 3.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 3.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 3.02%   |
| Intel Wireless 3165                                                     | 12        | 3.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 2.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 2.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.52%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 2.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 2.27%   |
| Intel Wireless 8260                                                     | 8         | 2.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.02%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1.76%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.76%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.26%   |
| Intel Wireless 7260                                                     | 5         | 1.26%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.01%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 4         | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.01%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.01%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.01%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 4         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.76%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.76%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 194       | 63.19%  |
| Intel                            | 52        | 16.94%  |
| Qualcomm Atheros                 | 23        | 7.49%   |
| Broadcom                         | 14        | 4.56%   |
| Nvidia                           | 5         | 1.63%   |
| Silicon Integrated Systems [SiS] | 3         | 0.98%   |
| Marvell Technology Group         | 3         | 0.98%   |
| Broadcom Limited                 | 3         | 0.98%   |
| ASIX Electronics                 | 3         | 0.98%   |
| OPPO Electronics                 | 2         | 0.65%   |
| JMicron Technology               | 2         | 0.65%   |
| DisplayLink                      | 2         | 0.65%   |
| Apple                            | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 137       | 44.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 42        | 13.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 18        | 5.81%   |
| Realtek Killer E2600 GbE Controller                                    | 7         | 2.26%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 1.61%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 1.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 1.29%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 1.29%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 1.29%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 1.29%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 3         | 0.97%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.97%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.65%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 2         | 0.65%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.65%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.65%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.65%   |
| Intel Ethernet Connection (3) I218-V                                   | 2         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.65%   |
| Intel 82577LC Gigabit Network Connection                               | 2         | 0.65%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 0.65%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.65%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 2         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.32%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.32%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.32%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.32%   |
| Nvidia MCP77 Ethernet                                                  | 1         | 0.32%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 378       | 55.51%  |
| Ethernet | 301       | 44.2%   |
| Modem    | 2         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 328       | 82.83%  |
| Ethernet | 68        | 17.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 279       | 72.28%  |
| 1     | 99        | 25.65%  |
| 0     | 6         | 1.55%   |
| 3     | 2         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 352       | 89.8%   |
| Yes  | 40        | 10.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 122       | 38.36%  |
| Realtek Semiconductor           | 40        | 12.58%  |
| IMC Networks                    | 31        | 9.75%   |
| Qualcomm Atheros Communications | 28        | 8.81%   |
| Lite-On Technology              | 26        | 8.18%   |
| Broadcom                        | 21        | 6.6%    |
| Foxconn / Hon Hai               | 18        | 5.66%   |
| Apple                           | 8         | 2.52%   |
| Toshiba                         | 4         | 1.26%   |
| Hewlett-Packard                 | 4         | 1.26%   |
| Cambridge Silicon Radio         | 4         | 1.26%   |
| Dell                            | 3         | 0.94%   |
| Chicony Electronics             | 3         | 0.94%   |
| Ralink                          | 2         | 0.63%   |
| TP-Link                         | 1         | 0.31%   |
| Realtek                         | 1         | 0.31%   |
| Ralink Technology               | 1         | 0.31%   |
| Foxconn International           | 1         | 0.31%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 48        | 15.09%  |
| Realtek Bluetooth Radio                             | 30        | 9.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 7.23%   |
| Intel AX201 Bluetooth                               | 22        | 6.92%   |
| IMC Networks Bluetooth Radio                        | 16        | 5.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 3.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 3.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 3.14%   |
| IMC Networks Bluetooth Device                       | 10        | 3.14%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 2.2%    |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 2.2%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.57%   |
| Lite-On Bluetooth Device                            | 5         | 1.57%   |
| Intel Bluetooth Device                              | 5         | 1.57%   |
| Intel AX200 Bluetooth                               | 5         | 1.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.26%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 1.26%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.26%   |
| Intel AX210 Bluetooth                               | 4         | 1.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.26%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.26%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.26%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.94%   |
| IMC Networks Wireless_Device                        | 3         | 0.94%   |
| Chicony Bluetooth Radio                             | 3         | 0.94%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.63%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.63%   |
| Lite-On Wireless_Device                             | 2         | 0.63%   |
| Lite-On BCM43142A0                                  | 2         | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.63%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.63%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.63%   |
| Broadcom HP Portable Valentine                      | 2         | 0.63%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.63%   |
| Apple Bluetooth Host Controller                     | 2         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 305       | 68.23%  |
| AMD                              | 66        | 14.77%  |
| Nvidia                           | 50        | 11.19%  |
| Silicon Integrated Systems [SiS] | 3         | 0.67%   |
| Plantronics                      | 3         | 0.67%   |
| Logitech                         | 3         | 0.67%   |
| JMTek                            | 3         | 0.67%   |
| C-Media Electronics              | 3         | 0.67%   |
| Realtek Semiconductor            | 2         | 0.45%   |
| SteelSeries ApS                  | 1         | 0.22%   |
| Stadium USB microphone           | 1         | 0.22%   |
| Sony                             | 1         | 0.22%   |
| OPPO Electronics                 | 1         | 0.22%   |
| Micronas                         | 1         | 0.22%   |
| Hewlett-Packard                  | 1         | 0.22%   |
| Generalplus Technology           | 1         | 0.22%   |
| Creative Technology              | 1         | 0.22%   |
| Audeze                           | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 56        | 10.69%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 7.44%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 35        | 6.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 4.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 3.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 3.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 2.86%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 2.86%   |
| AMD FCH Azalia Controller                                                                         | 13        | 2.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.1%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 1.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 1.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.72%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 9         | 1.72%   |
| Nvidia Audio device                                                                               | 8         | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.53%   |
| Intel CM238 HD Audio Controller                                                                   | 8         | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 1.53%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.53%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.34%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.76%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 3         | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.57%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 62        | 24.8%   |
| SK hynix            | 53        | 21.2%   |
| Kingston            | 39        | 15.6%   |
| Micron Technology   | 26        | 10.4%   |
| Unknown             | 16        | 6.4%    |
| Crucial             | 12        | 4.8%    |
| Ramaxel Technology  | 9         | 3.6%    |
| Team                | 5         | 2%      |
| Unknown (ABCD)      | 4         | 1.6%    |
| Nanya Technology    | 4         | 1.6%    |
| Elpida              | 4         | 1.6%    |
| Transcend           | 3         | 1.2%    |
| Unknown (8A5D)      | 2         | 0.8%    |
| G.Skill             | 2         | 0.8%    |
| A-DATA Technology   | 2         | 0.8%    |
| Qimonda             | 1         | 0.4%    |
| Patriot             | 1         | 0.4%    |
| ChangXin Memory     | 1         | 0.4%    |
| Avant               | 1         | 0.4%    |
| ASint Technology    | 1         | 0.4%    |
| Apacer              | 1         | 0.4%    |
| Unknown             | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 6         | 2.28%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 6         | 2.28%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 5         | 1.9%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 1.9%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 5         | 1.9%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 4         | 1.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 1.52%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 4         | 1.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 4         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 1.52%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 4         | 1.52%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s          | 4         | 1.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.14%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 1.14%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 1.14%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s             | 3         | 1.14%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                         | 2         | 0.76%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s                | 2         | 0.76%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s           | 2         | 0.76%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 0.76%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 0.76%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 2         | 0.76%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s               | 2         | 0.76%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.76%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.76%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.76%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 2         | 0.76%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s             | 2         | 0.76%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                  | 2         | 0.76%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.76%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 2         | 0.76%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s             | 2         | 0.76%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s              | 2         | 0.76%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s               | 2         | 0.76%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s             | 2         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 97        | 48.26%  |
| DDR3    | 70        | 34.83%  |
| LPDDR4  | 12        | 5.97%   |
| DDR2    | 9         | 4.48%   |
| DDR5    | 5         | 2.49%   |
| LPDDR3  | 2         | 1%      |
| Unknown | 2         | 1%      |
| SDRAM   | 1         | 0.5%    |
| LPDDR5  | 1         | 0.5%    |
| DRAM    | 1         | 0.5%    |
| DDR     | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 184       | 92.46%  |
| Row Of Chips | 14        | 7.04%   |
| Unknown      | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 94        | 40.87%  |
| 4096  | 69        | 30%     |
| 2048  | 29        | 12.61%  |
| 16384 | 20        | 8.7%    |
| 1024  | 12        | 5.22%   |
| 32768 | 6         | 2.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 49        | 21.97%  |
| 2667    | 48        | 21.52%  |
| 3200    | 44        | 19.73%  |
| 2400    | 16        | 7.17%   |
| 667     | 11        | 4.93%   |
| 1334    | 10        | 4.48%   |
| 2133    | 9         | 4.04%   |
| 1333    | 8         | 3.59%   |
| 4800    | 4         | 1.79%   |
| 1067    | 4         | 1.79%   |
| 8400    | 2         | 0.9%    |
| 4267    | 2         | 0.9%    |
| 3733    | 2         | 0.9%    |
| 1066    | 2         | 0.9%    |
| Unknown | 2         | 0.9%    |
| 5600    | 1         | 0.45%   |
| 5500    | 1         | 0.45%   |
| 4266    | 1         | 0.45%   |
| 3266    | 1         | 0.45%   |
| 2048    | 1         | 0.45%   |
| 1867    | 1         | 0.45%   |
| 1866    | 1         | 0.45%   |
| 800     | 1         | 0.45%   |
| 533     | 1         | 0.45%   |
| 400     | 1         | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 50%     |
| Seiko Epson        | 1         | 25%     |
| Unknown            | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L360 Series | 1         | 25%     |
| Brother DCP-T710W       | 1         | 25%     |
| Brother DCP-T310        | 1         | 25%     |
| Unknown                 | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 95        | 28.36%  |
| IMC Networks                           | 33        | 9.85%   |
| Realtek Semiconductor                  | 30        | 8.96%   |
| Quanta                                 | 25        | 7.46%   |
| Microdia                               | 20        | 5.97%   |
| Sunplus Innovation Technology          | 16        | 4.78%   |
| Bison Electronics                      | 15        | 4.48%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.18%   |
| Lite-On Technology                     | 11        | 3.28%   |
| Apple                                  | 9         | 2.69%   |
| Syntek                                 | 7         | 2.09%   |
| Suyin                                  | 7         | 2.09%   |
| Silicon Motion                         | 7         | 2.09%   |
| Acer                                   | 7         | 2.09%   |
| Luxvisions Innotech Limited            | 6         | 1.79%   |
| Alcor Micro                            | 5         | 1.49%   |
| Samsung Electronics                    | 3         | 0.9%    |
| ALi                                    | 3         | 0.9%    |
| Z-Star Microelectronics                | 2         | 0.6%    |
| USB Camera                             | 2         | 0.6%    |
| OmniVision Technologies                | 2         | 0.6%    |
| Importek                               | 2         | 0.6%    |
| Y Media                                | 1         | 0.3%    |
| vivo                                   | 1         | 0.3%    |
| SunplusIT                              | 1         | 0.3%    |
| Sunplus Technology                     | 1         | 0.3%    |
| Ricoh                                  | 1         | 0.3%    |
| Owon                                   | 1         | 0.3%    |
| OPPO Electronics                       | 1         | 0.3%    |
| Logitech                               | 1         | 0.3%    |
| Lenovo                                 | 1         | 0.3%    |
| kingcome                               | 1         | 0.3%    |
| Goertek Electronics                    | 1         | 0.3%    |
| GEMBIRD                                | 1         | 0.3%    |
| DigiTech                               | 1         | 0.3%    |
| Alpha Imaging Technology               | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 22        | 6.57%   |
| Chicony HD WebCam                                               | 19        | 5.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 10        | 2.99%   |
| Microdia Integrated_Webcam_HD                                   | 9         | 2.69%   |
| Realtek Integrated_Webcam_HD                                    | 7         | 2.09%   |
| Realtek Acer 640 x 480 laptop camera                            | 7         | 2.09%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 7         | 2.09%   |
| Chicony VGA WebCam                                              | 6         | 1.79%   |
| Quanta VGA WebCam                                               | 5         | 1.49%   |
| Quanta HD WebCam                                                | 5         | 1.49%   |
| Quanta ACER HD User Facing                                      | 5         | 1.49%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 4         | 1.19%   |
| Realtek Integrated Webcam                                       | 4         | 1.19%   |
| Lite-On Integrated Camera                                       | 4         | 1.19%   |
| IMC Networks Integrated Camera                                  | 4         | 1.19%   |
| Chicony Integrated Camera [ThinkPad]                            | 4         | 1.19%   |
| Chicony HP Truevision HD                                        | 4         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 1.19%   |
| Bison Lenovo EasyCamera                                         | 4         | 1.19%   |
| Bison Integrated Camera                                         | 4         | 1.19%   |
| Syntek Lenovo EasyCamera                                        | 3         | 0.9%    |
| Sunplus Integrated_Webcam_HD                                    | 3         | 0.9%    |
| Sunplus HD WebCam                                               | 3         | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)                         | 3         | 0.9%    |
| Quanta HD User Facing                                           | 3         | 0.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 0.9%    |
| IMC Networks EasyCamera                                         | 3         | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                                   | 3         | 0.9%    |
| Chicony TOSHIBA Web Camera - HD                                 | 3         | 0.9%    |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 3         | 0.9%    |
| Chicony Lenovo EasyCamera                                       | 3         | 0.9%    |
| Chicony HP Wide Vision HD Camera                                | 3         | 0.9%    |
| Chicony HP HD Camera                                            | 3         | 0.9%    |
| Bison ThinkPad Integrated Camera                                | 3         | 0.9%    |
| Apple FaceTime Camera                                           | 3         | 0.9%    |
| Apple Built-in iSight                                           | 3         | 0.9%    |
| ALi WebCam                                                      | 3         | 0.9%    |
| USB Camera USB Camera                                           | 2         | 0.6%    |
| Syntek Integrated Camera                                        | 2         | 0.6%    |
| Syntek EasyCamera                                               | 2         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 33.33%  |
| Shenzhen Goodix Technology | 10        | 20.83%  |
| Synaptics                  | 6         | 12.5%   |
| LighTuning Technology      | 5         | 10.42%  |
| Elan Microelectronics      | 4         | 8.33%   |
| Upek                       | 3         | 6.25%   |
| AuthenTec                  | 3         | 6.25%   |
| GDMicroelectronics         | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                       | 8         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor               | 4         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                | 3         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 3         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 3         | 6.25%   |
| Elan ELAN:Fingerprint                                     | 3         | 6.25%   |
| Validity Sensors Synaptics WBDI                           | 2         | 4.17%   |
| Synaptics Fingerprint reader [HP G6]                      | 2         | 4.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 2.08%   |
| Validity Sensors VFS491                                   | 1         | 2.08%   |
| Validity Sensors VFS300 Fingerprint Reader                | 1         | 2.08%   |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 2.08%   |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 2.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 1         | 2.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 2.08%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 2.08%   |
| Shenzhen Goodix FingerPrint                               | 1         | 2.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 2.08%   |
| GDMicroelectronics Touch Fingerprint Sensor               | 1         | 2.08%   |
| Elan ELAN:ARM-M4                                          | 1         | 2.08%   |
| AuthenTec Fingerprint Sensor                              | 1         | 2.08%   |
| AuthenTec AES2810                                         | 1         | 2.08%   |
| AuthenTec AES1600                                         | 1         | 2.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 7         | 46.67%  |
| Upek             | 3         | 20%     |
| O2 Micro         | 2         | 13.33%  |
| SCM Microsystems | 1         | 6.67%   |
| Lenovo           | 1         | 6.67%   |
| Alcor Micro      | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 20%     |
| Broadcom 5880                                                                | 3         | 20%     |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 6.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 6.67%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 280       | 70%     |
| 1     | 100       | 25%     |
| 2     | 18        | 4.5%    |
| 3     | 2         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 34.06%  |
| Graphics card            | 32        | 23.19%  |
| Chipcard                 | 14        | 10.14%  |
| Net/wireless             | 11        | 7.97%   |
| Camera                   | 11        | 7.97%   |
| Multimedia controller    | 7         | 5.07%   |
| Net/ethernet             | 4         | 2.9%    |
| Sound                    | 3         | 2.17%   |
| Bluetooth                | 3         | 2.17%   |
| Storage/nvme             | 1         | 0.72%   |
| Storage                  | 1         | 0.72%   |
| Network                  | 1         | 0.72%   |
| Modem                    | 1         | 0.72%   |
| Communication controller | 1         | 0.72%   |
| Card reader              | 1         | 0.72%   |


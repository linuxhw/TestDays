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

Total: 587

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 37        | 8.92%   |
| Ubuntu 22.04                 | 32        | 7.71%   |
| Pop!_OS 22.04                | 20        | 4.82%   |
| Ubuntu 18.04                 | 15        | 3.61%   |
| Pop!_OS 20.04                | 15        | 3.61%   |
| Fedora 38                    | 12        | 2.89%   |
| OpenMandriva 4.2             | 11        | 2.65%   |
| KDE neon 20.04               | 11        | 2.65%   |
| ArcoLinux Rolling            | 8         | 1.93%   |
| Arch Rolling                 | 8         | 1.93%   |
| Arch                         | 7         | 1.69%   |
| Zorin 16                     | 6         | 1.45%   |
| Zorin 15                     | 6         | 1.45%   |
| Pop!_OS 21.04                | 6         | 1.45%   |
| Fedora 36                    | 6         | 1.45%   |
| Debian 11                    | 6         | 1.45%   |
| Manjaro                      | 5         | 1.2%    |
| Linux Mint 21.1              | 5         | 1.2%    |
| Kubuntu 22.04                | 5         | 1.2%    |
| KDE neon 22.04               | 5         | 1.2%    |
| Fedora 39                    | 5         | 1.2%    |
| Ubuntu 23.04                 | 4         | 0.96%   |
| OpenMandriva 4.3             | 4         | 0.96%   |
| Linux Mint 20.2              | 4         | 0.96%   |
| Linux Mint 20.1              | 4         | 0.96%   |
| Fedora 37                    | 4         | 0.96%   |
| Fedora 35                    | 4         | 0.96%   |
| EndeavourOS Rolling          | 4         | 0.96%   |
| Debian 12                    | 4         | 0.96%   |
| Ubuntu 20.10                 | 3         | 0.72%   |
| SteamOS 3.4.8                | 3         | 0.72%   |
| Pop!_OS 21.10                | 3         | 0.72%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.72%   |
| LMDE 4                       | 3         | 0.72%   |
| Linux Mint 19.3              | 3         | 0.72%   |
| KDE neon 18.04               | 3         | 0.72%   |
| Fedora 33                    | 3         | 0.72%   |
| Xubuntu 23.04                | 2         | 0.48%   |
| Xubuntu 20.04                | 2         | 0.48%   |
| Xubuntu 18.04                | 2         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 97        | 24.87%  |
| Pop!_OS       | 45        | 11.54%  |
| Fedora        | 35        | 8.97%   |
| Linux Mint    | 25        | 6.41%   |
| OpenMandriva  | 20        | 5.13%   |
| KDE neon      | 18        | 4.62%   |
| Endless       | 15        | 3.85%   |
| Arch          | 15        | 3.85%   |
| Zorin         | 12        | 3.08%   |
| Debian        | 12        | 3.08%   |
| Manjaro       | 10        | 2.56%   |
| ArcoLinux     | 10        | 2.56%   |
| Xubuntu       | 7         | 1.79%   |
| SteamOS       | 7         | 1.79%   |
| Kubuntu       | 7         | 1.79%   |
| Kali          | 6         | 1.54%   |
| EndeavourOS   | 5         | 1.28%   |
| openSUSE      | 4         | 1.03%   |
| Nobara        | 4         | 1.03%   |
| Lubuntu       | 4         | 1.03%   |
| LMDE          | 4         | 1.03%   |
| Elementary    | 4         | 1.03%   |
| Ubuntu MATE   | 3         | 0.77%   |
| Pikaos        | 2         | 0.51%   |
| Peppermint    | 2         | 0.51%   |
| Linux Lite    | 2         | 0.51%   |
| Clear Linux   | 2         | 0.51%   |
| BlackPanther  | 2         | 0.51%   |
| Xero          | 1         | 0.26%   |
| Ubuntu Unity  | 1         | 0.26%   |
| Ubuntu Budgie | 1         | 0.26%   |
| Sparky        | 1         | 0.26%   |
| Slackware     | 1         | 0.26%   |
| ROSA          | 1         | 0.26%   |
| MX            | 1         | 0.26%   |
| Gentoo        | 1         | 0.26%   |
| BunsenLabs    | 1         | 0.26%   |
| Archcraft     | 1         | 0.26%   |
| Alpine        | 1         | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 17        | 3.77%   |
| 5.10.14-desktop-1omv4002 | 11        | 2.44%   |
| 6.2.6-76060206-generic   | 6         | 1.33%   |
| 5.13.0-valve36-1-neptune | 6         | 1.33%   |
| 6.2.0-26-generic         | 5         | 1.11%   |
| 5.4.0-7634-generic       | 5         | 1.11%   |
| 5.4.0-48-generic         | 5         | 1.11%   |
| 5.4.0-47-generic         | 5         | 1.11%   |
| 5.15.0-58-generic        | 5         | 1.11%   |
| 5.15.0-56-generic        | 5         | 1.11%   |
| 6.2.9-300.fc38.x86_64    | 4         | 0.89%   |
| 6.2.0-33-generic         | 4         | 0.89%   |
| 5.4.0-19-generic         | 4         | 0.89%   |
| 5.3.0-28-generic         | 4         | 0.89%   |
| 5.19.0-32-generic        | 4         | 0.89%   |
| 5.16.7-desktop-1omv4003  | 4         | 0.89%   |
| 5.15.0-52-generic        | 4         | 0.89%   |
| 5.15.0-50-generic        | 4         | 0.89%   |
| 5.15.0-41-generic        | 4         | 0.89%   |
| 5.13.0-28-generic        | 4         | 0.89%   |
| 5.11.0-7620-generic      | 4         | 0.89%   |
| 6.2.0-37-generic         | 3         | 0.67%   |
| 6.2.0-32-generic         | 3         | 0.67%   |
| 6.2.0-20-generic         | 3         | 0.67%   |
| 6.0.6-76060006-generic   | 3         | 0.67%   |
| 5.8.0-14-generic         | 3         | 0.67%   |
| 5.4.0-7642-generic       | 3         | 0.67%   |
| 5.4.0-58-generic         | 3         | 0.67%   |
| 5.4.0-45-generic         | 3         | 0.67%   |
| 5.3.0-23-generic         | 3         | 0.67%   |
| 5.15.0-60-generic        | 3         | 0.67%   |
| 5.15.0-43-generic        | 3         | 0.67%   |
| 5.13.0-7614-generic      | 3         | 0.67%   |
| 5.13.0-40-generic        | 3         | 0.67%   |
| 5.0.0-37-generic         | 3         | 0.67%   |
| 4.18.0-25-generic        | 3         | 0.67%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.44%   |
| 6.1.39-1-lts             | 2         | 0.44%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.44%   |
| 6.1.0-10-amd64           | 2         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 69        | 16.08%  |
| 5.15.0  | 41        | 9.56%   |
| 5.13.0  | 24        | 5.59%   |
| 6.2.0   | 20        | 4.66%   |
| 5.3.0   | 17        | 3.96%   |
| 5.11.0  | 15        | 3.5%    |
| 5.19.0  | 13        | 3.03%   |
| 5.8.0   | 11        | 2.56%   |
| 5.10.14 | 11        | 2.56%   |
| 4.15.0  | 10        | 2.33%   |
| 6.2.6   | 8         | 1.86%   |
| 5.0.0   | 7         | 1.63%   |
| 6.1.0   | 6         | 1.4%    |
| 5.10.0  | 6         | 1.4%    |
| 4.18.0  | 6         | 1.4%    |
| 6.0.6   | 5         | 1.17%   |
| 4.19.0  | 5         | 1.17%   |
| 6.2.9   | 4         | 0.93%   |
| 5.16.7  | 4         | 0.93%   |
| 6.5.5   | 3         | 0.7%    |
| 5.9.16  | 3         | 0.7%    |
| 5.17.5  | 3         | 0.7%    |
| 4.9.20  | 3         | 0.7%    |
| 4.4.0   | 3         | 0.7%    |
| 6.6.3   | 2         | 0.47%   |
| 6.5.7   | 2         | 0.47%   |
| 6.5.6   | 2         | 0.47%   |
| 6.4.7   | 2         | 0.47%   |
| 6.4.11  | 2         | 0.47%   |
| 6.3.5   | 2         | 0.47%   |
| 6.3.0   | 2         | 0.47%   |
| 6.1.39  | 2         | 0.47%   |
| 6.1.1   | 2         | 0.47%   |
| 6.0.12  | 2         | 0.47%   |
| 6.0.0   | 2         | 0.47%   |
| 5.8.14  | 2         | 0.47%   |
| 5.19.12 | 2         | 0.47%   |
| 5.18.13 | 2         | 0.47%   |
| 5.18.10 | 2         | 0.47%   |
| 5.18.0  | 2         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 77        | 18.29%  |
| 5.15    | 55        | 13.06%  |
| 6.2     | 35        | 8.31%   |
| 5.13    | 25        | 5.94%   |
| 5.10    | 20        | 4.75%   |
| 5.3     | 19        | 4.51%   |
| 6.1     | 18        | 4.28%   |
| 5.11    | 18        | 4.28%   |
| 5.19    | 17        | 4.04%   |
| 5.8     | 15        | 3.56%   |
| 6.0     | 14        | 3.33%   |
| 5.16    | 13        | 3.09%   |
| 6.5     | 10        | 2.38%   |
| 4.15    | 10        | 2.38%   |
| 6.4     | 9         | 2.14%   |
| 5.18    | 8         | 1.9%    |
| 5.0     | 8         | 1.9%    |
| 4.18    | 7         | 1.66%   |
| 6.3     | 6         | 1.43%   |
| 6.6     | 5         | 1.19%   |
| 5.9     | 5         | 1.19%   |
| 5.17    | 5         | 1.19%   |
| 4.19    | 5         | 1.19%   |
| 5.6     | 3         | 0.71%   |
| 5.14    | 3         | 0.71%   |
| 4.9     | 3         | 0.71%   |
| 4.4     | 3         | 0.71%   |
| 5.12    | 2         | 0.48%   |
| 5.7     | 1         | 0.24%   |
| 5.2     | 1         | 0.24%   |
| 3.8     | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 367       | 97.35%  |
| i686   | 9         | 2.39%   |
| armv7l | 1         | 0.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 194       | 49.11%  |
| KDE5          | 70        | 17.72%  |
| XFCE          | 34        | 8.61%   |
| X-Cinnamon    | 25        | 6.33%   |
| Unknown       | 23        | 5.82%   |
| KDE           | 12        | 3.04%   |
| MATE          | 7         | 1.77%   |
| LXQt          | 5         | 1.27%   |
| Pantheon      | 4         | 1.01%   |
| Hyprland      | 3         | 0.76%   |
| Budgie        | 3         | 0.76%   |
| Cinnamon      | 2         | 0.51%   |
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
| X11     | 289       | 74.87%  |
| Wayland | 83        | 21.5%   |
| Unknown | 12        | 3.11%   |
| Tty     | 2         | 0.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 199       | 50.64%  |
| SDDM    | 53        | 13.49%  |
| GDM3    | 51        | 12.98%  |
| GDM     | 46        | 11.7%   |
| LightDM | 35        | 8.91%   |
| TDM     | 6         | 1.53%   |
| SLiM    | 1         | 0.25%   |
| MDM     | 1         | 0.25%   |
| LXDM    | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_PH   | 171       | 44.42%  |
| en_US   | 162       | 42.08%  |
| Unknown | 23        | 5.97%   |
| C       | 8         | 2.08%   |
| de_DE   | 6         | 1.56%   |
| en_GB   | 5         | 1.3%    |
| en_AU   | 2         | 0.52%   |
| zh_HK   | 1         | 0.26%   |
| zh_CN   | 1         | 0.26%   |
| tl_PH   | 1         | 0.26%   |
| en_ZA   | 1         | 0.26%   |
| en_NZ   | 1         | 0.26%   |
| en_IN   | 1         | 0.26%   |
| en_DK   | 1         | 0.26%   |
| en_CA   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 207       | 53.08%  |
| BIOS | 183       | 46.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 270       | 69.59%  |
| Btrfs   | 61        | 15.72%  |
| Overlay | 33        | 8.51%   |
| Tmpfs   | 8         | 2.06%   |
| Unknown | 7         | 1.8%    |
| Xfs     | 4         | 1.03%   |
| Ext2    | 3         | 0.77%   |
| Zfs     | 2         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 206       | 52.69%  |
| GPT     | 150       | 38.36%  |
| MBR     | 35        | 8.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 349       | 91.84%  |
| Yes       | 31        | 8.16%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 275       | 71.8%   |
| Yes       | 108       | 28.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 84        | 22.34%  |
| Acer                | 70        | 18.62%  |
| Hewlett-Packard     | 52        | 13.83%  |
| ASUSTek Computer    | 43        | 11.44%  |
| Dell                | 41        | 10.9%   |
| Toshiba             | 14        | 3.72%   |
| MSI                 | 10        | 2.66%   |
| Unknown             | 8         | 2.13%   |
| Valve               | 7         | 1.86%   |
| Samsung Electronics | 7         | 1.86%   |
| Apple               | 7         | 1.86%   |
| HUAWEI              | 5         | 1.33%   |
| Sony                | 4         | 1.06%   |
| Clevo               | 4         | 1.06%   |
| NEC Computers       | 3         | 0.8%    |
| Google              | 3         | 0.8%    |
| eMachines           | 3         | 0.8%    |
| Jumper              | 2         | 0.53%   |
| Gigabyte Technology | 2         | 0.53%   |
| realme              | 1         | 0.27%   |
| PERSONA             | 1         | 0.27%   |
| Notebook            | 1         | 0.27%   |
| HASEE Computer      | 1         | 0.27%   |
| Fujitsu             | 1         | 0.27%   |
| Cubix               | 1         | 0.27%   |
| ALLDOCUBE           | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 11        | 2.93%   |
| Valve Jupiter                            | 7         | 1.86%   |
| Acer Aspire ES1-132                      | 6         | 1.6%    |
| HP Notebook                              | 3         | 0.8%    |
| Clevo M7x0S                              | 3         | 0.8%    |
| MSI Modern 14 B4MW                       | 2         | 0.53%   |
| Lenovo V110-14IAP 80TF                   | 2         | 0.53%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 2         | 0.53%   |
| Lenovo IdeaPad 100-15IBY 80MJ            | 2         | 0.53%   |
| Jumper EZbook                            | 2         | 0.53%   |
| HP Pavilion Notebook                     | 2         | 0.53%   |
| HP Pavilion Gaming Laptop 15-ec2xxx      | 2         | 0.53%   |
| HP Pavilion Gaming Laptop 15-dk2xxx      | 2         | 0.53%   |
| HP EliteBook 840 G6                      | 2         | 0.53%   |
| eMachines eM350                          | 2         | 0.53%   |
| Dell Vostro 5515                         | 2         | 0.53%   |
| Dell Latitude E7450                      | 2         | 0.53%   |
| Dell Inspiron 7472                       | 2         | 0.53%   |
| Dell Inspiron 5567                       | 2         | 0.53%   |
| ASUS X540NA                              | 2         | 0.53%   |
| ASUS X510UQ                              | 2         | 0.53%   |
| ASUS VivoBook_ASUSLaptop M1603QA_M1603QA | 2         | 0.53%   |
| Apple MacBookPro5,5                      | 2         | 0.53%   |
| Apple MacBookAir3,1                      | 2         | 0.53%   |
| Acer TravelMate P249-G2-M                | 2         | 0.53%   |
| Acer TravelMate B113                     | 2         | 0.53%   |
| Acer Swift SF314-57                      | 2         | 0.53%   |
| Acer Nitro AN515-55                      | 2         | 0.53%   |
| Acer Aspire E5-551G                      | 2         | 0.53%   |
| Acer Aspire E5-473G                      | 2         | 0.53%   |
| Acer Aspire E3-111                       | 2         | 0.53%   |
| Acer Aspire A315-51                      | 2         | 0.53%   |
| Acer Aspire A315-41G                     | 2         | 0.53%   |
| Toshiba TECRA Z50-C                      | 1         | 0.27%   |
| Toshiba TECRA R940                       | 1         | 0.27%   |
| Toshiba Satellite Pro U400               | 1         | 0.27%   |
| Toshiba Satellite P845                   | 1         | 0.27%   |
| Toshiba Satellite L855                   | 1         | 0.27%   |
| Toshiba Satellite L515                   | 1         | 0.27%   |
| Toshiba Satellite E45t-A                 | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 47        | 12.5%   |
| Lenovo ThinkPad   | 39        | 10.37%  |
| Lenovo IdeaPad    | 32        | 8.51%   |
| Dell Inspiron     | 20        | 5.32%   |
| HP Pavilion       | 16        | 4.26%   |
| Unknown           | 11        | 2.93%   |
| ASUS VivoBook     | 10        | 2.66%   |
| Dell Latitude     | 9         | 2.39%   |
| Toshiba Satellite | 8         | 2.13%   |
| HP Laptop         | 8         | 2.13%   |
| Acer TravelMate   | 8         | 2.13%   |
| Valve Jupiter     | 7         | 1.86%   |
| HP ProBook        | 5         | 1.33%   |
| HP EliteBook      | 5         | 1.33%   |
| Acer Nitro        | 5         | 1.33%   |
| Lenovo Legion     | 4         | 1.06%   |
| Dell Vostro       | 4         | 1.06%   |
| ASUS TUF          | 4         | 1.06%   |
| ASUS ROG          | 4         | 1.06%   |
| HP Notebook       | 3         | 0.8%    |
| Dell XPS          | 3         | 0.8%    |
| Dell Precision    | 3         | 0.8%    |
| Clevo M7x0S       | 3         | 0.8%    |
| Acer Swift        | 3         | 0.8%    |
| Acer Predator     | 3         | 0.8%    |
| Toshiba TECRA     | 2         | 0.53%   |
| Toshiba dynabook  | 2         | 0.53%   |
| MSI Modern        | 2         | 0.53%   |
| MSI CX62          | 2         | 0.53%   |
| Lenovo V110-14IAP | 2         | 0.53%   |
| Jumper EZbook     | 2         | 0.53%   |
| HP Stream         | 2         | 0.53%   |
| HP OMEN           | 2         | 0.53%   |
| HP ENVY           | 2         | 0.53%   |
| eMachines eM350   | 2         | 0.53%   |
| ASUS X540NA       | 2         | 0.53%   |
| ASUS X510UQ       | 2         | 0.53%   |
| ASUS ASUS         | 2         | 0.53%   |
| Apple MacBookPro5 | 2         | 0.53%   |
| Apple MacBookAir3 | 2         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 36        | 9.57%   |
| 2019    | 34        | 9.04%   |
| 2016    | 34        | 9.04%   |
| 2021    | 29        | 7.71%   |
| 2018    | 29        | 7.71%   |
| 2017    | 29        | 7.71%   |
| 2020    | 28        | 7.45%   |
| 2014    | 25        | 6.65%   |
| 2011    | 25        | 6.65%   |
| 2022    | 22        | 5.85%   |
| 2010    | 20        | 5.32%   |
| 2015    | 19        | 5.05%   |
| 2013    | 13        | 3.46%   |
| 2009    | 12        | 3.19%   |
| 2008    | 7         | 1.86%   |
| 2023    | 6         | 1.6%    |
| 2007    | 3         | 0.8%    |
| 2006    | 3         | 0.8%    |
| Unknown | 2         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 376       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 326       | 86.02%  |
| Enabled  | 53        | 13.98%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 373       | 99.2%   |
| Yes  | 3         | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 103       | 26.89%  |
| 3.01-4.0    | 83        | 21.67%  |
| 8.01-16.0   | 71        | 18.54%  |
| 16.01-24.0  | 56        | 14.62%  |
| 1.01-2.0    | 41        | 10.7%   |
| 32.01-64.0  | 14        | 3.66%   |
| 2.01-3.0    | 8         | 2.09%   |
| 0.51-1.0    | 4         | 1.04%   |
| 24.01-32.0  | 2         | 0.52%   |
| 64.01-256.0 | 1         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 141       | 33.1%   |
| 1.01-2.0  | 136       | 31.92%  |
| 4.01-8.0  | 56        | 13.15%  |
| 3.01-4.0  | 53        | 12.44%  |
| 0.51-1.0  | 26        | 6.1%    |
| 8.01-16.0 | 12        | 2.82%   |
| 0.01-0.5  | 1         | 0.23%   |
| Unknown   | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 275       | 71.06%  |
| 2      | 94        | 24.29%  |
| 3      | 14        | 3.62%   |
| 0      | 2         | 0.52%   |
| 5      | 1         | 0.26%   |
| 4      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 261       | 68.68%  |
| Yes       | 119       | 31.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 294       | 77.98%  |
| No        | 83        | 22.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 368       | 97.87%  |
| No        | 8         | 2.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 304       | 79.79%  |
| No        | 77        | 20.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Philippines | 376       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Quezon City         | 56        | 13.43%  |
| Cebu City           | 35        | 8.39%   |
| Davao City          | 21        | 5.04%   |
| Manila              | 20        | 4.8%    |
| Angeles City        | 17        | 4.08%   |
| Pasig               | 14        | 3.36%   |
| Paranaque City      | 14        | 3.36%   |
| Makati City         | 13        | 3.12%   |
| Caloocan City       | 13        | 3.12%   |
| Bacolod City        | 12        | 2.88%   |
| Lahug               | 10        | 2.4%    |
| Bacoor              | 9         | 2.16%   |
| San Jose del Monte  | 8         | 1.92%   |
| Iloilo City         | 8         | 1.92%   |
| Cagayan de Oro      | 8         | 1.92%   |
| Mandaluyong City    | 7         | 1.68%   |
| Santa Rosa          | 6         | 1.44%   |
| San Miguel          | 6         | 1.44%   |
| San Fernando City   | 6         | 1.44%   |
| Las Pinas           | 6         | 1.44%   |
| Imus                | 6         | 1.44%   |
| Tarlac City         | 5         | 1.2%    |
| Manajao             | 5         | 1.2%    |
| Dasmarinas          | 5         | 1.2%    |
| City of Muntinglupa | 5         | 1.2%    |
| San Pablo City      | 4         | 0.96%   |
| Malolos             | 4         | 0.96%   |
| Legazpi             | 4         | 0.96%   |
| Calamba             | 4         | 0.96%   |
| Baguio City         | 4         | 0.96%   |
| San Pedro           | 3         | 0.72%   |
| San Juan            | 3         | 0.72%   |
| Lucena City         | 3         | 0.72%   |
| La Trinidad         | 3         | 0.72%   |
| Iligan City         | 3         | 0.72%   |
| Zamboanga City      | 2         | 0.48%   |
| Taytay              | 2         | 0.48%   |
| Talisay City        | 2         | 0.48%   |
| Tagbilaran          | 2         | 0.48%   |
| San Marcelino       | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 63        | 86     | 12.96%  |
| WDC                         | 61        | 68     | 12.55%  |
| Toshiba                     | 54        | 71     | 11.11%  |
| Samsung Electronics         | 46        | 61     | 9.47%   |
| SanDisk                     | 29        | 38     | 5.97%   |
| Unknown                     | 27        | 34     | 5.56%   |
| Kingston                    | 25        | 27     | 5.14%   |
| SK hynix                    | 20        | 27     | 4.12%   |
| Hitachi                     | 15        | 21     | 3.09%   |
| Intel                       | 14        | 17     | 2.88%   |
| HGST                        | 13        | 13     | 2.67%   |
| Micron Technology           | 11        | 17     | 2.26%   |
| Ramsta                      | 8         | 9      | 1.65%   |
| Crucial                     | 6         | 6      | 1.23%   |
| A-DATA Technology           | 6         | 10     | 1.23%   |
| China                       | 5         | 6      | 1.03%   |
| Phison                      | 4         | 4      | 0.82%   |
| Apple                       | 4         | 4      | 0.82%   |
| Team                        | 3         | 5      | 0.62%   |
| Silicon Motion              | 3         | 4      | 0.62%   |
| Phison Electronics          | 3         | 4      | 0.62%   |
| Micron/Crucial Technology   | 3         | 3      | 0.62%   |
| LITEONIT                    | 3         | 5      | 0.62%   |
| JMicron Technology          | 3         | 6      | 0.62%   |
| Fujitsu                     | 3         | 4      | 0.62%   |
| USB3.0                      | 2         | 2      | 0.41%   |
| TAMMUZ                      | 2         | 5      | 0.41%   |
| ShiJi                       | 2         | 2      | 0.41%   |
| O2 Micro                    | 2         | 2      | 0.41%   |
| Netac                       | 2         | 2      | 0.41%   |
| Lite-On                     | 2         | 4      | 0.41%   |
| Kingston Technology Company | 2         | 2      | 0.41%   |
| KingSpec                    | 2         | 3      | 0.41%   |
| Indilinx                    | 2         | 2      | 0.41%   |
| HS-SSD-E100                 | 2         | 2      | 0.41%   |
| HS-SSD-C100                 | 2         | 3      | 0.41%   |
| Unknown                     | 2         | 2      | 0.41%   |
| WALRAM                      | 1         | 1      | 0.21%   |
| Vaseky                      | 1         | 2      | 0.21%   |
| UMIS                        | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                            | 17        | 3.36%   |
| Seagate ST1000LM035-1RK172 1TB                      | 14        | 2.77%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 7         | 1.38%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 6         | 1.19%   |
| Unknown MMC Card  32GB                              | 6         | 1.19%   |
| Toshiba MQ04ABF100 1TB                              | 6         | 1.19%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 1.19%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 0.99%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 0.99%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 0.99%   |
| HGST HTS721010A9E630 1TB                            | 5         | 0.99%   |
| Unknown MMC Card  128GB                             | 4         | 0.79%   |
| Seagate ST2000LM007-1R8174 2TB                      | 4         | 0.79%   |
| Seagate ST1000LM049-2GH172 1TB                      | 4         | 0.79%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 0.79%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 3         | 0.59%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 3         | 0.59%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 3         | 0.59%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 3         | 0.59%   |
| Unknown MMC Card  64GB                              | 3         | 0.59%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.59%   |
| Seagate ST9500325AS 500GB                           | 3         | 0.59%   |
| Seagate ST500LM030-2E717D 500GB                     | 3         | 0.59%   |
| Seagate ST500LM030-1RK17D 500GB                     | 3         | 0.59%   |
| Seagate ST1000LM048-2E7172 1TB                      | 3         | 0.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 3         | 0.59%   |
| Samsung NVMe SSD Drive 512GB                        | 3         | 0.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3         | 0.59%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 3         | 0.59%   |
| Micron NVMe SSD Drive 512GB                         | 3         | 0.59%   |
| Intel SSDPEKNU512GZ 512GB                           | 3         | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.4%    |
| WDC WD5000LPVX-80V0TT0 500GB                        | 2         | 0.4%    |
| WDC WD5000LPCX-24C6HT0 500GB                        | 2         | 0.4%    |
| WDC WD10SPZX-24Z10 1TB                              | 2         | 0.4%    |
| USB3.0 Super Speed 1TB                              | 2         | 0.4%    |
| Unknown SD/MMC/MS PRO 512GB                         | 2         | 0.4%    |
| Unknown MMC Card  7GB                               | 2         | 0.4%    |
| Unknown MMC Card  256GB                             | 2         | 0.4%    |
| Unknown DA4032  32GB                                | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 86     | 31.82%  |
| WDC                 | 51        | 57     | 25.76%  |
| Toshiba             | 46        | 60     | 23.23%  |
| Hitachi             | 15        | 21     | 7.58%   |
| HGST                | 13        | 13     | 6.57%   |
| Fujitsu             | 3         | 4      | 1.52%   |
| USB3.0              | 2         | 2      | 1.01%   |
| Unknown             | 2         | 2      | 1.01%   |
| Samsung Electronics | 1         | 1      | 0.51%   |
| SAGE                | 1         | 1      | 0.51%   |
| HGST HTS            | 1         | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 23     | 14.5%   |
| Kingston            | 17        | 17     | 12.98%  |
| SanDisk             | 13        | 16     | 9.92%   |
| Ramsta              | 8         | 9      | 6.11%   |
| WDC                 | 5         | 6      | 3.82%   |
| Micron Technology   | 5         | 5      | 3.82%   |
| Crucial             | 5         | 5      | 3.82%   |
| China               | 5         | 6      | 3.82%   |
| Toshiba             | 4         | 6      | 3.05%   |
| SK hynix            | 4         | 9      | 3.05%   |
| Apple               | 4         | 4      | 3.05%   |
| A-DATA Technology   | 4         | 7      | 3.05%   |
| Team                | 3         | 5      | 2.29%   |
| LITEONIT            | 3         | 5      | 2.29%   |
| TAMMUZ              | 2         | 5      | 1.53%   |
| Netac               | 2         | 2      | 1.53%   |
| KingSpec            | 2         | 3      | 1.53%   |
| JMicron Technology  | 2         | 2      | 1.53%   |
| Intel               | 2         | 2      | 1.53%   |
| HS-SSD-E100         | 2         | 2      | 1.53%   |
| Vaseky              | 1         | 2      | 0.76%   |
| Transcend           | 1         | 1      | 0.76%   |
| Teclast             | 1         | 4      | 0.76%   |
| ShiJi               | 1         | 1      | 0.76%   |
| SADAYU              | 1         | 1      | 0.76%   |
| PNY                 | 1         | 1      | 0.76%   |
| Plextor             | 1         | 1      | 0.76%   |
| Phison              | 1         | 1      | 0.76%   |
| OCZ                 | 1         | 1      | 0.76%   |
| NT-512              | 1         | 1      | 0.76%   |
| Kingmax             | 1         | 1      | 0.76%   |
| Indilinx            | 1         | 1      | 0.76%   |
| HS-SSD-C100         | 1         | 1      | 0.76%   |
| Hikvision           | 1         | 1      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| GALAX               | 1         | 1      | 0.76%   |
| DTGC-C              | 1         | 1      | 0.76%   |
| Colorful            | 1         | 1      | 0.76%   |
| BR                  | 1         | 1      | 0.76%   |
| ASUS-PHISON         | 1         | 2      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 189       | 248    | 41.27%  |
| SSD     | 122       | 164    | 26.64%  |
| NVMe    | 112       | 160    | 24.45%  |
| MMC     | 28        | 35     | 6.11%   |
| Unknown | 7         | 11     | 1.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 282       | 398    | 63.37%  |
| NVMe | 112       | 159    | 25.17%  |
| MMC  | 28        | 35     | 6.29%   |
| SAS  | 23        | 26     | 5.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 216       | 287    | 68.79%  |
| 0.51-1.0   | 85        | 108    | 27.07%  |
| 1.01-2.0   | 12        | 16     | 3.82%   |
| 3.01-4.0   | 1         | 1      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 110       | 27.99%  |
| 251-500        | 106       | 26.97%  |
| 501-1000       | 61        | 15.52%  |
| 1-20           | 34        | 8.65%   |
| 1001-2000      | 33        | 8.4%    |
| 51-100         | 21        | 5.34%   |
| 21-50          | 15        | 3.82%   |
| More than 3000 | 5         | 1.27%   |
| 2001-3000      | 4         | 1.02%   |
| Unknown        | 4         | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 165       | 39.19%  |
| 21-50     | 85        | 20.19%  |
| 51-100    | 62        | 14.73%  |
| 101-250   | 58        | 13.78%  |
| 251-500   | 29        | 6.89%   |
| 501-1000  | 14        | 3.33%   |
| Unknown   | 4         | 0.95%   |
| 1001-2000 | 3         | 0.71%   |
| 2001-3000 | 1         | 0.24%   |

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
| Detected | 237       | 391    | 58.23%  |
| Works    | 140       | 192    | 34.4%   |
| Malfunc  | 29        | 34     | 7.13%   |
| Failed   | 1         | 1      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 278       | 63.33%  |
| AMD                              | 43        | 9.79%   |
| Samsung Electronics              | 27        | 6.15%   |
| SanDisk                          | 17        | 3.87%   |
| SK hynix                         | 16        | 3.64%   |
| Kingston Technology Company      | 9         | 2.05%   |
| Nvidia                           | 8         | 1.82%   |
| Phison Electronics               | 7         | 1.59%   |
| Micron Technology                | 6         | 1.37%   |
| Toshiba America Info Systems     | 4         | 0.91%   |
| Micron/Crucial Technology        | 4         | 0.91%   |
| Silicon Motion                   | 3         | 0.68%   |
| Silicon Integrated Systems [SiS] | 3         | 0.68%   |
| Solid State Storage Technology   | 2         | 0.46%   |
| O2 Micro                         | 2         | 0.46%   |
| Lite-On Technology               | 2         | 0.46%   |
| ADATA Technology                 | 2         | 0.46%   |
| Union Memory (Shenzhen)          | 1         | 0.23%   |
| Shenzhen Longsys Electronics     | 1         | 0.23%   |
| Realtek Semiconductor            | 1         | 0.23%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.23%   |
| Lenovo                           | 1         | 0.23%   |
| KIOXIA                           | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 38        | 7.95%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 38        | 7.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 29        | 6.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 29        | 6.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 20        | 4.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 16        | 3.35%   |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 3.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 2.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 13        | 2.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 10        | 2.09%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 2.09%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 8         | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 1.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 1.46%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 1.46%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 7         | 1.46%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 1.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 1.46%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 1.26%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 5         | 1.05%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 5         | 1.05%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 4         | 0.84%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 4         | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.63%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.63%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3         | 0.63%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 3         | 0.63%   |
| Intel SSD 660P Series                                                            | 3         | 0.63%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 3         | 0.63%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 2         | 0.42%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 2         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 280       | 60.87%  |
| NVMe | 112       | 24.35%  |
| RAID | 46        | 10%     |
| IDE  | 22        | 4.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 308       | 81.91%  |
| AMD    | 67        | 17.82%  |
| ARM    | 1         | 0.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 2.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 2.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 2.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 2.13%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 8         | 2.13%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 2.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.86%   |
| AMD Custom APU 0405                           | 7         | 1.86%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 1.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.33%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.33%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 5         | 1.33%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 1.33%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.33%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.06%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.06%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.06%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.06%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.06%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.06%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.8%    |
| Intel Core i5-8365U CPU @ 1.60GHz             | 3         | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.8%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.8%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.8%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.8%    |
| Intel Celeron CPU N3160 @ 1.60GHz             | 3         | 0.8%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.8%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.8%    |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 3         | 0.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.8%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.8%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.8%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 99        | 26.33%  |
| Intel Core i7           | 61        | 16.22%  |
| Intel Celeron           | 40        | 10.64%  |
| Intel Core i3           | 34        | 9.04%   |
| Other                   | 32        | 8.51%   |
| AMD Ryzen 5             | 16        | 4.26%   |
| Intel Core 2 Duo        | 13        | 3.46%   |
| Intel Atom              | 12        | 3.19%   |
| AMD Ryzen 7             | 10        | 2.66%   |
| Intel Pentium           | 9         | 2.39%   |
| AMD Ryzen 3             | 8         | 2.13%   |
| Intel Pentium Silver    | 4         | 1.06%   |
| Intel Pentium Dual-Core | 4         | 1.06%   |
| AMD A8                  | 4         | 1.06%   |
| AMD A6                  | 4         | 1.06%   |
| AMD Athlon              | 3         | 0.8%    |
| Intel Genuine           | 2         | 0.53%   |
| Intel Core m3           | 2         | 0.53%   |
| AMD Turion 64 X2 Mobile | 2         | 0.53%   |
| AMD A10                 | 2         | 0.53%   |
| Intel Pentium Dual      | 1         | 0.27%   |
| Intel Core m5           | 1         | 0.27%   |
| Intel Core 2            | 1         | 0.27%   |
| Intel Celeron M         | 1         | 0.27%   |
| AMD Turion 64 Mobile    | 1         | 0.27%   |
| AMD Ryzen 9             | 1         | 0.27%   |
| AMD Ryzen 7 PRO         | 1         | 0.27%   |
| AMD Quad-Core           | 1         | 0.27%   |
| AMD PRO A10             | 1         | 0.27%   |
| AMD FX                  | 1         | 0.27%   |
| AMD E2                  | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD E                   | 1         | 0.27%   |
| AMD C-60                | 1         | 0.27%   |
| AMD A4                  | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 189       | 50.27%  |
| 4      | 138       | 36.7%   |
| 6      | 19        | 5.05%   |
| 8      | 11        | 2.93%   |
| 1      | 11        | 2.93%   |
| 14     | 3         | 0.8%    |
| 10     | 3         | 0.8%    |
| 24     | 1         | 0.27%   |
| 12     | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 376       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 273       | 72.61%  |
| 1      | 103       | 27.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 367       | 97.35%  |
| Unknown        | 6         | 1.59%   |
| 32-bit         | 4         | 1.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 34.1%   |
| 0x306a9    | 24        | 6.11%   |
| 0x206a7    | 18        | 4.58%   |
| 0x506c9    | 13        | 3.31%   |
| 0x406e3    | 13        | 3.31%   |
| 0x806ea    | 11        | 2.8%    |
| 0x1067a    | 11        | 2.8%    |
| 0x806ec    | 10        | 2.54%   |
| 0x806e9    | 10        | 2.54%   |
| 0x30678    | 10        | 2.54%   |
| 0x306d4    | 8         | 2.04%   |
| 0x0a50000c | 7         | 1.78%   |
| 0x806c1    | 6         | 1.53%   |
| 0x906ea    | 5         | 1.27%   |
| 0x706e5    | 5         | 1.27%   |
| 0x406c4    | 5         | 1.27%   |
| 0x40651    | 5         | 1.27%   |
| 0x306c3    | 5         | 1.27%   |
| 0x20655    | 5         | 1.27%   |
| 0x106ca    | 5         | 1.27%   |
| 0xa0652    | 4         | 1.02%   |
| 0x706a1    | 4         | 1.02%   |
| 0x10676    | 4         | 1.02%   |
| 0x08608103 | 4         | 1.02%   |
| 0x08108109 | 4         | 1.02%   |
| 0x906e9    | 3         | 0.76%   |
| 0x906a4    | 3         | 0.76%   |
| 0x806eb    | 3         | 0.76%   |
| 0x406c3    | 3         | 0.76%   |
| 0x20652    | 3         | 0.76%   |
| 0x08600104 | 3         | 0.76%   |
| 0x07030105 | 3         | 0.76%   |
| 0x06003106 | 3         | 0.76%   |
| 0x906c0    | 2         | 0.51%   |
| 0x906a3    | 2         | 0.51%   |
| 0x706a8    | 2         | 0.51%   |
| 0x6ec      | 2         | 0.51%   |
| 0x506e3    | 2         | 0.51%   |
| 0x30661    | 2         | 0.51%   |
| 0x0a50000d | 2         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 70        | 18.52%  |
| IvyBridge        | 34        | 8.99%   |
| Skylake          | 23        | 6.08%   |
| SandyBridge      | 23        | 6.08%   |
| Silvermont       | 20        | 5.29%   |
| Penryn           | 18        | 4.76%   |
| Unknown          | 18        | 4.76%   |
| Haswell          | 16        | 4.23%   |
| Goldmont         | 16        | 4.23%   |
| Broadwell        | 15        | 3.97%   |
| TigerLake        | 13        | 3.44%   |
| Zen 3            | 12        | 3.17%   |
| Zen+             | 10        | 2.65%   |
| Westmere         | 10        | 2.65%   |
| Bonnell          | 9         | 2.38%   |
| Alderlake Hybrid | 9         | 2.38%   |
| Goldmont plus    | 8         | 2.12%   |
| CometLake        | 8         | 2.12%   |
| Zen 2            | 6         | 1.59%   |
| IceLake          | 6         | 1.59%   |
| Puma             | 5         | 1.32%   |
| K8 Hammer        | 4         | 1.06%   |
| Zen              | 3         | 0.79%   |
| Steamroller      | 3         | 0.79%   |
| P6               | 3         | 0.79%   |
| Excavator        | 3         | 0.79%   |
| Core             | 3         | 0.79%   |
| Tremont          | 2         | 0.53%   |
| Piledriver       | 2         | 0.53%   |
| Jaguar           | 2         | 0.53%   |
| Bobcat           | 2         | 0.53%   |
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
| Intel                            | 294       | 60.25%  |
| Nvidia                           | 100       | 20.49%  |
| AMD                              | 91        | 18.65%  |
| Silicon Integrated Systems [SiS] | 3         | 0.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 34        | 6.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 4.59%   |
| Intel UHD Graphics 620                                                                   | 19        | 3.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 2.99%   |
| Intel HD Graphics 620                                                                    | 15        | 2.99%   |
| Intel HD Graphics 500                                                                    | 14        | 2.79%   |
| Intel HD Graphics 5500                                                                   | 13        | 2.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 2.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.8%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 1.4%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 7         | 1.4%    |
| Intel HD Graphics 630                                                                    | 7         | 1.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.4%    |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 7         | 1.4%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 1.4%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.2%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 6         | 1.2%    |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 1%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1%      |
| AMD Lucienne                                                                             | 5         | 1%      |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.8%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 4         | 0.8%    |
| Intel HD Graphics 530                                                                    | 4         | 0.8%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 189       | 50%     |
| Intel + Nvidia | 78        | 20.63%  |
| 1 x AMD        | 48        | 12.7%   |
| Intel + AMD    | 25        | 6.61%   |
| 1 x Nvidia     | 13        | 3.44%   |
| AMD + Nvidia   | 10        | 2.65%   |
| 2 x AMD        | 9         | 2.38%   |
| 1 x SiS        | 3         | 0.79%   |
| 2 x Intel      | 2         | 0.53%   |
| Other          | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 316       | 82.94%  |
| Proprietary | 58        | 15.22%  |
| Unknown     | 7         | 1.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 271       | 69.85%  |
| 1.01-2.0   | 38        | 9.79%   |
| 0.01-0.5   | 37        | 9.54%   |
| 3.01-4.0   | 18        | 4.64%   |
| 0.51-1.0   | 16        | 4.12%   |
| 7.01-8.0   | 4         | 1.03%   |
| 5.01-6.0   | 3         | 0.77%   |
| 8.01-16.0  | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 77        | 18.47%  |
| AU Optronics            | 69        | 16.55%  |
| BOE                     | 67        | 16.07%  |
| LG Display              | 51        | 12.23%  |
| Samsung Electronics     | 35        | 8.39%   |
| Lenovo                  | 14        | 3.36%   |
| InfoVision              | 8         | 1.92%   |
| Valve                   | 7         | 1.68%   |
| Philips                 | 7         | 1.68%   |
| Goldstar                | 7         | 1.68%   |
| Sharp                   | 6         | 1.44%   |
| PANDA                   | 6         | 1.44%   |
| Apple                   | 6         | 1.44%   |
| AOC                     | 6         | 1.44%   |
| Sony                    | 5         | 1.2%    |
| Acer                    | 5         | 1.2%    |
| Chi Mei Optoelectronics | 4         | 0.96%   |
| RTK                     | 3         | 0.72%   |
| ASUSTek Computer        | 3         | 0.72%   |
| LG Philips              | 2         | 0.48%   |
| InnoLux Display         | 2         | 0.48%   |
| Hewlett-Packard         | 2         | 0.48%   |
| Gigabyte Technology     | 2         | 0.48%   |
| Dell                    | 2         | 0.48%   |
| BenQ                    | 2         | 0.48%   |
| Ancor Communications    | 2         | 0.48%   |
| ___                     | 1         | 0.24%   |
| Unknown                 | 1         | 0.24%   |
| Toshiba                 | 1         | 0.24%   |
| TMX                     | 1         | 0.24%   |
| Quanta Display          | 1         | 0.24%   |
| Pixio                   | 1         | 0.24%   |
| Panasonic               | 1         | 0.24%   |
| MYS                     | 1         | 0.24%   |
| JDI                     | 1         | 0.24%   |
| IPS                     | 1         | 0.24%   |
| HKC                     | 1         | 0.24%   |
| HannStar                | 1         | 0.24%   |
| GreenWood               | 1         | 0.24%   |
| GDH                     | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 7         | 1.68%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 7         | 1.68%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 6         | 1.44%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 1.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 4         | 0.96%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 4         | 0.96%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.72%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 3         | 0.72%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 3         | 0.72%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 3         | 0.72%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO2992 1920x1080 344x193mm 15.5-inch        | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 0.72%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 3         | 0.72%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3549 1366x768 309x174mm 14.0-inch  | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 2         | 0.48%   |
| RTK 32V3H-H6A RTK4C54 1440x900 697x392mm 31.5-inch                    | 2         | 0.48%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 2         | 0.48%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.48%   |
| LG Display LP101WSA-TLN1 LGD0295 1024x600 224x126mm 10.1-inch         | 2         | 0.48%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 2         | 0.48%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.48%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 2         | 0.48%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch           | 2         | 0.48%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch          | 2         | 0.48%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch      | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 169       | 43.22%  |
| 1920x1080 (FHD)    | 139       | 35.55%  |
| 1600x900 (HD+)     | 14        | 3.58%   |
| 800x1280           | 7         | 1.79%   |
| 3840x2160 (4K)     | 7         | 1.79%   |
| 1920x1200 (WUXGA)  | 7         | 1.79%   |
| 1024x600           | 7         | 1.79%   |
| 2560x1440 (QHD)    | 6         | 1.53%   |
| 1280x800 (WXGA)    | 6         | 1.53%   |
| 2560x1600          | 5         | 1.28%   |
| 1280x1024 (SXGA)   | 5         | 1.28%   |
| 1440x900 (WXGA+)   | 4         | 1.02%   |
| 1360x768           | 4         | 1.02%   |
| 2160x1440          | 3         | 0.77%   |
| 2560x1080          | 2         | 0.51%   |
| 3840x2400          | 1         | 0.26%   |
| 3000x2000          | 1         | 0.26%   |
| 2400x1600          | 1         | 0.26%   |
| 1680x1050 (WSXGA+) | 1         | 0.26%   |
| 1280x768           | 1         | 0.26%   |
| 1024x768 (XGA)     | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 147       | 35.42%  |
| 13      | 71        | 17.11%  |
| 14      | 61        | 14.7%   |
| 11      | 21        | 5.06%   |
| 17      | 20        | 4.82%   |
| 12      | 14        | 3.37%   |
| 18      | 12        | 2.89%   |
| 23      | 10        | 2.41%   |
| 27      | 9         | 2.17%   |
| 21      | 8         | 1.93%   |
| 10      | 7         | 1.69%   |
| 7       | 7         | 1.69%   |
| 16      | 6         | 1.45%   |
| 72      | 5         | 1.2%    |
| 31      | 5         | 1.2%    |
| 24      | 4         | 0.96%   |
| 34      | 2         | 0.48%   |
| Unknown | 2         | 0.48%   |
| 84      | 1         | 0.24%   |
| 54      | 1         | 0.24%   |
| 20      | 1         | 0.24%   |
| 8       | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 259       | 63.17%  |
| 201-300     | 65        | 15.85%  |
| 401-500     | 21        | 5.12%   |
| 351-400     | 19        | 4.63%   |
| 501-600     | 18        | 4.39%   |
| 601-700     | 9         | 2.2%    |
| 1-100       | 7         | 1.71%   |
| 1501-2000   | 6         | 1.46%   |
| 701-800     | 2         | 0.49%   |
| Unknown     | 2         | 0.49%   |
| 101-200     | 1         | 0.24%   |
| 1001-1500   | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 332       | 89.49%  |
| 16/10   | 19        | 5.12%   |
| 0.67    | 7         | 1.89%   |
| 3/2     | 5         | 1.35%   |
| 5/4     | 3         | 0.81%   |
| 21/9    | 2         | 0.54%   |
| 4/3     | 1         | 0.27%   |
| 0.62    | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 144       | 34.87%  |
| 81-90          | 114       | 27.6%   |
| 51-60          | 21        | 5.08%   |
| 71-80          | 18        | 4.36%   |
| 201-250        | 17        | 4.12%   |
| 121-130        | 16        | 3.87%   |
| 141-150        | 15        | 3.63%   |
| 61-70          | 14        | 3.39%   |
| 301-350        | 9         | 2.18%   |
| 1-40           | 8         | 1.94%   |
| More than 1000 | 7         | 1.69%   |
| 351-500        | 7         | 1.69%   |
| 41-50          | 7         | 1.69%   |
| 111-120        | 7         | 1.69%   |
| 151-200        | 4         | 0.97%   |
| 91-100         | 2         | 0.48%   |
| Unknown        | 2         | 0.48%   |
| 131-140        | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 167       | 40.83%  |
| 101-120       | 163       | 39.85%  |
| 51-100        | 42        | 10.27%  |
| 161-240       | 20        | 4.89%   |
| 1-50          | 8         | 1.96%   |
| More than 240 | 7         | 1.71%   |
| Unknown       | 2         | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 324       | 83.72%  |
| 2     | 49        | 12.66%  |
| 0     | 8         | 2.07%   |
| 3     | 6         | 1.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 224       | 37.9%   |
| Intel                            | 165       | 27.92%  |
| Qualcomm Atheros                 | 103       | 17.43%  |
| Broadcom                         | 46        | 7.78%   |
| Ralink Technology                | 7         | 1.18%   |
| MediaTek                         | 6         | 1.02%   |
| Nvidia                           | 5         | 0.85%   |
| Broadcom Limited                 | 5         | 0.85%   |
| TP-Link                          | 3         | 0.51%   |
| Silicon Integrated Systems [SiS] | 3         | 0.51%   |
| Qualcomm Atheros Communications  | 3         | 0.51%   |
| Marvell Technology Group         | 3         | 0.51%   |
| ASIX Electronics                 | 3         | 0.51%   |
| Ralink                           | 2         | 0.34%   |
| JMicron Technology               | 2         | 0.34%   |
| DisplayLink                      | 2         | 0.34%   |
| OPPO Electronics                 | 1         | 0.17%   |
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


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133       | 19.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 6.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 18        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 18        | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 2.6%    |
| Intel Wireless 7265                                               | 17        | 2.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 1.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 1.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 12        | 1.74%   |
| Intel Wireless 3165                                               | 12        | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 10        | 1.45%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 1.16%   |
| Intel Wireless 8260                                               | 8         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.16%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 1.01%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 6         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.72%   |
| Intel Wireless 7260                                               | 5         | 0.72%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 158       | 40.93%  |
| Qualcomm Atheros                | 90        | 23.32%  |
| Realtek Semiconductor           | 74        | 19.17%  |
| Broadcom                        | 36        | 9.33%   |
| Ralink Technology               | 7         | 1.81%   |
| MediaTek                        | 6         | 1.55%   |
| TP-Link                         | 3         | 0.78%   |
| Qualcomm Atheros Communications | 3         | 0.78%   |
| Ralink                          | 2         | 0.52%   |
| Broadcom Limited                | 2         | 0.52%   |
| NetGear                         | 1         | 0.26%   |
| Encore Electronics              | 1         | 0.26%   |
| Dell                            | 1         | 0.26%   |
| BUFFALO                         | 1         | 0.26%   |
| ASUSTek Computer                | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 5.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 4.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 4.65%   |
| Intel Wireless 7265                                                     | 17        | 4.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 3.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 3.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 13        | 3.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 3.1%    |
| Intel Wireless 3165                                                     | 12        | 3.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 2.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 2.58%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 2.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 2.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 2.07%   |
| Intel Wireless 8260                                                     | 8         | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.07%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1.81%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.29%   |
| Intel Wireless 7260                                                     | 5         | 1.29%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.29%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.03%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.03%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 4         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.78%   |
| Intel Centrino Wireless-N 2200                                          | 3         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 189       | 63.21%  |
| Intel                            | 51        | 17.06%  |
| Qualcomm Atheros                 | 23        | 7.69%   |
| Broadcom                         | 13        | 4.35%   |
| Nvidia                           | 5         | 1.67%   |
| Silicon Integrated Systems [SiS] | 3         | 1%      |
| Marvell Technology Group         | 3         | 1%      |
| Broadcom Limited                 | 3         | 1%      |
| ASIX Electronics                 | 3         | 1%      |
| JMicron Technology               | 2         | 0.67%   |
| DisplayLink                      | 2         | 0.67%   |
| OPPO Electronics                 | 1         | 0.33%   |
| Apple                            | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133       | 44.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 13.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 5.96%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 2.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 1.66%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 1.32%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.32%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.32%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.99%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.99%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.66%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.66%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.66%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.66%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.66%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.33%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.33%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.33%   |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 1         | 0.33%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.33%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.33%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 368       | 55.42%  |
| Ethernet | 294       | 44.28%  |
| Modem    | 2         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 319       | 82.43%  |
| Ethernet | 68        | 17.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 273       | 72.61%  |
| 1     | 95        | 25.27%  |
| 0     | 6         | 1.6%    |
| 3     | 2         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 344       | 90.05%  |
| Yes  | 38        | 9.95%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 117       | 37.99%  |
| Realtek Semiconductor           | 39        | 12.66%  |
| IMC Networks                    | 30        | 9.74%   |
| Qualcomm Atheros Communications | 28        | 9.09%   |
| Lite-On Technology              | 26        | 8.44%   |
| Broadcom                        | 21        | 6.82%   |
| Foxconn / Hon Hai               | 17        | 5.52%   |
| Apple                           | 7         | 2.27%   |
| Toshiba                         | 4         | 1.3%    |
| Hewlett-Packard                 | 4         | 1.3%    |
| Cambridge Silicon Radio         | 4         | 1.3%    |
| Dell                            | 3         | 0.97%   |
| Chicony Electronics             | 3         | 0.97%   |
| TP-Link                         | 1         | 0.32%   |
| Realtek                         | 1         | 0.32%   |
| Ralink Technology               | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |
| Foxconn International           | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 46        | 14.94%  |
| Realtek Bluetooth Radio                             | 25        | 8.12%   |
| Intel Bluetooth Device                              | 24        | 7.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 7.47%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 3.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 3.57%   |
| IMC Networks Bluetooth Device                       | 10        | 3.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 2.92%   |
| IMC Networks Bluetooth Radio                        | 8         | 2.6%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 2.27%   |
| IMC Networks 802.11ac WLAN Adapter                  | 7         | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 2.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.62%   |
| Lite-On Bluetooth Device                            | 5         | 1.62%   |
| Intel AX200 Bluetooth                               | 5         | 1.62%   |
| Realtek RTL8821A Bluetooth                          | 4         | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.3%    |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 1.3%    |
| Intel AX210 Bluetooth                               | 4         | 1.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.3%    |
| Realtek RTL8723B Bluetooth                          | 3         | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 0.97%   |
| IMC Networks Wireless_Device                        | 3         | 0.97%   |
| Chicony Bluetooth (RTL8723BE)                       | 3         | 0.97%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.97%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.65%   |
| Lite-On Wireless_Device                             | 2         | 0.65%   |
| Lite-On BCM43142A0                                  | 2         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.65%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.65%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.65%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.65%   |
| Broadcom HP Portable Valentine                      | 2         | 0.65%   |
| Broadcom Broadcom BCM2070 Bluetooth Device          | 2         | 0.65%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 296       | 67.73%  |
| AMD                              | 65        | 14.87%  |
| Nvidia                           | 50        | 11.44%  |
| Silicon Integrated Systems [SiS] | 3         | 0.69%   |
| Plantronics                      | 3         | 0.69%   |
| Logitech                         | 3         | 0.69%   |
| JMTek                            | 3         | 0.69%   |
| C-Media Electronics              | 3         | 0.69%   |
| Realtek Semiconductor            | 2         | 0.46%   |
| SteelSeries ApS                  | 1         | 0.23%   |
| Stadium USB microphone           | 1         | 0.23%   |
| Sony                             | 1         | 0.23%   |
| OPPO Electronics                 | 1         | 0.23%   |
| Micronas                         | 1         | 0.23%   |
| Hewlett-Packard                  | 1         | 0.23%   |
| Generalplus Technology           | 1         | 0.23%   |
| Creative Technology              | 1         | 0.23%   |
| Audeze                           | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 53        | 10.31%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 35        | 6.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 35        | 6.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 4.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 3.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 3.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 2.92%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 2.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 2.53%   |
| AMD FCH Azalia Controller                                                                         | 13        | 2.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 1.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.75%   |
| Nvidia Audio device                                                                               | 8         | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.56%   |
| Intel CM238 HD Audio Controller                                                                   | 8         | 1.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 1.56%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.56%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.36%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.36%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.78%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 3         | 0.58%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.58%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.58%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 61        | 25.1%   |
| SK hynix            | 52        | 21.4%   |
| Kingston            | 39        | 16.05%  |
| Micron Technology   | 24        | 9.88%   |
| Unknown             | 15        | 6.17%   |
| Crucial             | 12        | 4.94%   |
| Ramaxel Technology  | 9         | 3.7%    |
| Team                | 5         | 2.06%   |
| Unknown (ABCD)      | 4         | 1.65%   |
| Nanya Technology    | 4         | 1.65%   |
| Elpida              | 4         | 1.65%   |
| Transcend           | 3         | 1.23%   |
| A-DATA Technology   | 2         | 0.82%   |
| Unknown (8A5D)      | 1         | 0.41%   |
| Qimonda             | 1         | 0.41%   |
| Patriot             | 1         | 0.41%   |
| G.Skill             | 1         | 0.41%   |
| ChangXin Memory     | 1         | 0.41%   |
| Avant               | 1         | 0.41%   |
| ASint Technology    | 1         | 0.41%   |
| Apacer              | 1         | 0.41%   |
| Unknown             | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 2.34%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 6         | 2.34%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 1.95%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.56%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 1.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.56%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 1.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 1.17%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.17%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s          | 3         | 1.17%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 2         | 0.78%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s        | 2         | 0.78%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.78%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 2         | 0.78%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 2         | 0.78%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.78%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.78%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.78%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 0.78%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4267MT/s               | 2         | 0.78%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.78%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 47.94%  |
| DDR3    | 68        | 35.05%  |
| LPDDR4  | 11        | 5.67%   |
| DDR2    | 9         | 4.64%   |
| DDR5    | 5         | 2.58%   |
| LPDDR3  | 2         | 1.03%   |
| Unknown | 2         | 1.03%   |
| SDRAM   | 1         | 0.52%   |
| LPDDR5  | 1         | 0.52%   |
| DRAM    | 1         | 0.52%   |
| DDR     | 1         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 178       | 92.23%  |
| Row Of Chips | 14        | 7.25%   |
| Unknown      | 1         | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 91        | 40.81%  |
| 4096  | 66        | 29.6%   |
| 2048  | 29        | 13%     |
| 16384 | 19        | 8.52%   |
| 1024  | 12        | 5.38%   |
| 32768 | 6         | 2.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 48        | 22.12%  |
| 2667    | 46        | 21.2%   |
| 3200    | 43        | 19.82%  |
| 2400    | 16        | 7.37%   |
| 667     | 11        | 5.07%   |
| 1334    | 9         | 4.15%   |
| 2133    | 8         | 3.69%   |
| 1333    | 8         | 3.69%   |
| 4800    | 4         | 1.84%   |
| 1067    | 4         | 1.84%   |
| 8400    | 2         | 0.92%   |
| 4267    | 2         | 0.92%   |
| 3733    | 2         | 0.92%   |
| 1066    | 2         | 0.92%   |
| Unknown | 2         | 0.92%   |
| 5600    | 1         | 0.46%   |
| 5500    | 1         | 0.46%   |
| 4266    | 1         | 0.46%   |
| 3266    | 1         | 0.46%   |
| 2048    | 1         | 0.46%   |
| 1867    | 1         | 0.46%   |
| 1866    | 1         | 0.46%   |
| 800     | 1         | 0.46%   |
| 533     | 1         | 0.46%   |
| 400     | 1         | 0.46%   |

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
| Chicony Electronics                    | 90        | 27.52%  |
| IMC Networks                           | 33        | 10.09%  |
| Realtek Semiconductor                  | 29        | 8.87%   |
| Quanta                                 | 25        | 7.65%   |
| Microdia                               | 20        | 6.12%   |
| Bison Electronics                      | 16        | 4.89%   |
| Sunplus Innovation Technology          | 15        | 4.59%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.28%   |
| Lite-On Technology                     | 11        | 3.36%   |
| Apple                                  | 8         | 2.45%   |
| Syntek                                 | 7         | 2.14%   |
| Suyin                                  | 7         | 2.14%   |
| Silicon Motion                         | 7         | 2.14%   |
| Luxvisions Innotech Limited            | 6         | 1.83%   |
| Acer                                   | 6         | 1.83%   |
| Alcor Micro                            | 5         | 1.53%   |
| Samsung Electronics                    | 3         | 0.92%   |
| ALi                                    | 3         | 0.92%   |
| Z-Star Microelectronics                | 2         | 0.61%   |
| OmniVision Technologies                | 2         | 0.61%   |
| Importek                               | 2         | 0.61%   |
| icSpring                               | 2         | 0.61%   |
| Y Media                                | 1         | 0.31%   |
| vivo                                   | 1         | 0.31%   |
| SunplusIT                              | 1         | 0.31%   |
| Sunplus Technology                     | 1         | 0.31%   |
| Ricoh                                  | 1         | 0.31%   |
| Owon                                   | 1         | 0.31%   |
| OPPO Electronics                       | 1         | 0.31%   |
| Logitech                               | 1         | 0.31%   |
| Lenovo                                 | 1         | 0.31%   |
| kingcome                               | 1         | 0.31%   |
| Goertek Electronics                    | 1         | 0.31%   |
| GEMBIRD                                | 1         | 0.31%   |
| DigiTech                               | 1         | 0.31%   |
| Alpha Imaging Technology               | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 21        | 6.42%   |
| Chicony HD WebCam                                               | 18        | 5.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                              | 10        | 3.06%   |
| Microdia Integrated_Webcam_HD                                   | 9         | 2.75%   |
| Realtek Integrated_Webcam_HD                                    | 7         | 2.14%   |
| Realtek Acer 640 x 480 laptop camera                            | 7         | 2.14%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 7         | 2.14%   |
| Quanta VGA WebCam                                               | 5         | 1.53%   |
| Quanta HD WebCam                                                | 5         | 1.53%   |
| Quanta ACER HD User Facing                                      | 5         | 1.53%   |
| Chicony VGA Webcam                                              | 5         | 1.53%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 4         | 1.22%   |
| Realtek Integrated Webcam                                       | 4         | 1.22%   |
| Lite-On Integrated Camera                                       | 4         | 1.22%   |
| IMC Networks Integrated Camera                                  | 4         | 1.22%   |
| Chicony Integrated Camera [ThinkPad]                            | 4         | 1.22%   |
| Chicony HP Truevision HD                                        | 4         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 1.22%   |
| Bison Lenovo EasyCamera                                         | 4         | 1.22%   |
| Bison Integrated Camera                                         | 4         | 1.22%   |
| Syntek Lenovo EasyCamera                                        | 3         | 0.92%   |
| Sunplus Integrated_Webcam_HD                                    | 3         | 0.92%   |
| Sunplus HD WebCam                                               | 3         | 0.92%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 3         | 0.92%   |
| Quanta HD User Facing                                           | 3         | 0.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 0.92%   |
| IMC Networks EasyCamera                                         | 3         | 0.92%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 3         | 0.92%   |
| Chicony TOSHIBA Web Camera - HD                                 | 3         | 0.92%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 3         | 0.92%   |
| Chicony Lenovo EasyCamera                                       | 3         | 0.92%   |
| Chicony HP Wide Vision HD Camera                                | 3         | 0.92%   |
| Bison ThinkPad Integrated Camera                                | 3         | 0.92%   |
| Apple FaceTime Camera                                           | 3         | 0.92%   |
| Apple Built-in iSight                                           | 3         | 0.92%   |
| ALi WebCam                                                      | 3         | 0.92%   |
| Syntek Integrated Camera                                        | 2         | 0.61%   |
| Syntek EasyCamera                                               | 2         | 0.61%   |
| Suyin HP Webcam                                                 | 2         | 0.61%   |
| Sunplus Laptop Integrated WebCam HD                             | 2         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 31.11%  |
| Shenzhen Goodix Technology | 10        | 22.22%  |
| Synaptics                  | 6         | 13.33%  |
| LighTuning Technology      | 4         | 8.89%   |
| Elan Microelectronics      | 4         | 8.89%   |
| Upek                       | 3         | 6.67%   |
| AuthenTec                  | 3         | 6.67%   |
| GDMicroelectronics         | 1         | 2.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                       | 8         | 17.78%  |
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                | 3         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 3         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 3         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 3         | 6.67%   |
| Elan ELAN:Fingerprint                                     | 3         | 6.67%   |
| Synaptics Fingerprint reader [HP G6]                      | 2         | 4.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 2.22%   |
| Validity Sensors VFS300 Fingerprint Reader                | 1         | 2.22%   |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 2.22%   |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 2.22%   |
| Validity Sensors Synaptics WBDI                           | 1         | 2.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.22%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 1         | 2.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 2.22%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 2.22%   |
| Shenzhen Goodix FingerPrint                               | 1         | 2.22%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 2.22%   |
| GDMicroelectronics Touch Fingerprint Sensor               | 1         | 2.22%   |
| Elan ELAN:ARM-M4                                          | 1         | 2.22%   |
| AuthenTec Fingerprint Sensor                              | 1         | 2.22%   |
| AuthenTec AES2810                                         | 1         | 2.22%   |
| AuthenTec AES1600                                         | 1         | 2.22%   |

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
| 0     | 274       | 70.26%  |
| 1     | 96        | 24.62%  |
| 2     | 18        | 4.62%   |
| 3     | 2         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 32.84%  |
| Graphics card            | 32        | 23.88%  |
| Chipcard                 | 14        | 10.45%  |
| Net/wireless             | 11        | 8.21%   |
| Camera                   | 11        | 8.21%   |
| Multimedia controller    | 7         | 5.22%   |
| Net/ethernet             | 4         | 2.99%   |
| Sound                    | 3         | 2.24%   |
| Bluetooth                | 2         | 1.49%   |
| Storage/nvme             | 1         | 0.75%   |
| Storage                  | 1         | 0.75%   |
| Network                  | 1         | 0.75%   |
| Modem                    | 1         | 0.75%   |
| Communication controller | 1         | 0.75%   |
| Card reader              | 1         | 0.75%   |


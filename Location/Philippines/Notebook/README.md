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

Total: 563

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 37        | 9.25%   |
| Ubuntu 22.04                 | 30        | 7.5%    |
| Pop!_OS 22.04                | 18        | 4.5%    |
| Ubuntu 18.04                 | 15        | 3.75%   |
| Pop!_OS 20.04                | 15        | 3.75%   |
| Fedora 38                    | 12        | 3%      |
| OpenMandriva 4.2             | 11        | 2.75%   |
| KDE neon 20.04               | 11        | 2.75%   |
| Arch Rolling                 | 8         | 2%      |
| ArcoLinux Rolling            | 7         | 1.75%   |
| Arch                         | 7         | 1.75%   |
| Zorin 16                     | 6         | 1.5%    |
| Zorin 15                     | 6         | 1.5%    |
| Pop!_OS 21.04                | 6         | 1.5%    |
| Fedora 36                    | 6         | 1.5%    |
| Debian 11                    | 6         | 1.5%    |
| Manjaro                      | 5         | 1.25%   |
| Linux Mint 21.1              | 5         | 1.25%   |
| Kubuntu 22.04                | 5         | 1.25%   |
| KDE neon 22.04               | 5         | 1.25%   |
| OpenMandriva 4.3             | 4         | 1%      |
| Linux Mint 20.2              | 4         | 1%      |
| Fedora 37                    | 4         | 1%      |
| Fedora 35                    | 4         | 1%      |
| EndeavourOS Rolling          | 4         | 1%      |
| Debian 12                    | 4         | 1%      |
| Ubuntu 23.04                 | 3         | 0.75%   |
| Ubuntu 20.10                 | 3         | 0.75%   |
| SteamOS 3.4.8                | 3         | 0.75%   |
| Pop!_OS 21.10                | 3         | 0.75%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.75%   |
| LMDE 4                       | 3         | 0.75%   |
| Linux Mint 20.1              | 3         | 0.75%   |
| Linux Mint 19.3              | 3         | 0.75%   |
| KDE neon 18.04               | 3         | 0.75%   |
| Fedora 33                    | 3         | 0.75%   |
| Xubuntu 23.04                | 2         | 0.5%    |
| Xubuntu 20.04                | 2         | 0.5%    |
| Xubuntu 18.04                | 2         | 0.5%    |
| Ubuntu MATE 20.04            | 2         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 95        | 25%     |
| Pop!_OS       | 43        | 11.32%  |
| Fedora        | 33        | 8.68%   |
| Linux Mint    | 24        | 6.32%   |
| OpenMandriva  | 20        | 5.26%   |
| KDE neon      | 18        | 4.74%   |
| Endless       | 15        | 3.95%   |
| Arch          | 15        | 3.95%   |
| Zorin         | 12        | 3.16%   |
| Debian        | 12        | 3.16%   |
| Manjaro       | 10        | 2.63%   |
| ArcoLinux     | 9         | 2.37%   |
| Xubuntu       | 7         | 1.84%   |
| Kubuntu       | 7         | 1.84%   |
| SteamOS       | 6         | 1.58%   |
| Kali          | 6         | 1.58%   |
| EndeavourOS   | 5         | 1.32%   |
| openSUSE      | 4         | 1.05%   |
| Lubuntu       | 4         | 1.05%   |
| LMDE          | 4         | 1.05%   |
| Elementary    | 4         | 1.05%   |
| Ubuntu MATE   | 3         | 0.79%   |
| Nobara        | 3         | 0.79%   |
| Pikaos        | 2         | 0.53%   |
| Peppermint    | 2         | 0.53%   |
| Linux Lite    | 2         | 0.53%   |
| Clear Linux   | 2         | 0.53%   |
| BlackPanther  | 2         | 0.53%   |
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
| 5.4.0-42-generic         | 17        | 3.93%   |
| 5.10.14-desktop-1omv4002 | 11        | 2.54%   |
| 6.2.6-76060206-generic   | 6         | 1.39%   |
| 5.13.0-valve36-1-neptune | 6         | 1.39%   |
| 6.2.0-26-generic         | 5         | 1.15%   |
| 5.4.0-7634-generic       | 5         | 1.15%   |
| 5.4.0-48-generic         | 5         | 1.15%   |
| 5.4.0-47-generic         | 5         | 1.15%   |
| 5.15.0-58-generic        | 5         | 1.15%   |
| 5.15.0-56-generic        | 5         | 1.15%   |
| 6.2.9-300.fc38.x86_64    | 4         | 0.92%   |
| 6.2.0-33-generic         | 4         | 0.92%   |
| 5.4.0-19-generic         | 4         | 0.92%   |
| 5.3.0-28-generic         | 4         | 0.92%   |
| 5.19.0-32-generic        | 4         | 0.92%   |
| 5.16.7-desktop-1omv4003  | 4         | 0.92%   |
| 5.15.0-52-generic        | 4         | 0.92%   |
| 5.15.0-50-generic        | 4         | 0.92%   |
| 5.15.0-41-generic        | 4         | 0.92%   |
| 5.13.0-28-generic        | 4         | 0.92%   |
| 5.11.0-7620-generic      | 4         | 0.92%   |
| 6.2.0-32-generic         | 3         | 0.69%   |
| 6.2.0-20-generic         | 3         | 0.69%   |
| 6.0.6-76060006-generic   | 3         | 0.69%   |
| 5.8.0-14-generic         | 3         | 0.69%   |
| 5.4.0-7642-generic       | 3         | 0.69%   |
| 5.4.0-45-generic         | 3         | 0.69%   |
| 5.3.0-23-generic         | 3         | 0.69%   |
| 5.15.0-60-generic        | 3         | 0.69%   |
| 5.15.0-43-generic        | 3         | 0.69%   |
| 5.13.0-7614-generic      | 3         | 0.69%   |
| 5.13.0-40-generic        | 3         | 0.69%   |
| 5.0.0-37-generic         | 3         | 0.69%   |
| 4.18.0-25-generic        | 3         | 0.69%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.46%   |
| 6.1.39-1-lts             | 2         | 0.46%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.46%   |
| 6.1.0-10-amd64           | 2         | 0.46%   |
| 6.0.12-76060006-generic  | 2         | 0.46%   |
| 6.0.0-kali6-amd64        | 2         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 16.46%  |
| 5.15.0  | 41        | 9.93%   |
| 5.13.0  | 24        | 5.81%   |
| 6.2.0   | 18        | 4.36%   |
| 5.3.0   | 17        | 4.12%   |
| 5.11.0  | 15        | 3.63%   |
| 5.19.0  | 12        | 2.91%   |
| 5.8.0   | 11        | 2.66%   |
| 5.10.14 | 11        | 2.66%   |
| 4.15.0  | 10        | 2.42%   |
| 6.2.6   | 8         | 1.94%   |
| 5.0.0   | 7         | 1.69%   |
| 6.1.0   | 6         | 1.45%   |
| 5.10.0  | 6         | 1.45%   |
| 4.18.0  | 6         | 1.45%   |
| 6.0.6   | 5         | 1.21%   |
| 4.19.0  | 5         | 1.21%   |
| 6.2.9   | 4         | 0.97%   |
| 5.16.7  | 4         | 0.97%   |
| 6.5.5   | 3         | 0.73%   |
| 5.9.16  | 3         | 0.73%   |
| 5.17.5  | 3         | 0.73%   |
| 4.9.20  | 3         | 0.73%   |
| 4.4.0   | 3         | 0.73%   |
| 6.5.7   | 2         | 0.48%   |
| 6.4.7   | 2         | 0.48%   |
| 6.4.11  | 2         | 0.48%   |
| 6.3.5   | 2         | 0.48%   |
| 6.3.0   | 2         | 0.48%   |
| 6.1.39  | 2         | 0.48%   |
| 6.1.1   | 2         | 0.48%   |
| 6.0.12  | 2         | 0.48%   |
| 6.0.0   | 2         | 0.48%   |
| 5.8.14  | 2         | 0.48%   |
| 5.19.12 | 2         | 0.48%   |
| 5.18.13 | 2         | 0.48%   |
| 5.18.10 | 2         | 0.48%   |
| 5.18.0  | 2         | 0.48%   |
| 5.15.10 | 2         | 0.48%   |
| 5.14.0  | 2         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 18.72%  |
| 5.15    | 55        | 13.55%  |
| 6.2     | 33        | 8.13%   |
| 5.13    | 25        | 6.16%   |
| 5.10    | 20        | 4.93%   |
| 5.3     | 19        | 4.68%   |
| 5.11    | 18        | 4.43%   |
| 6.1     | 16        | 3.94%   |
| 5.19    | 16        | 3.94%   |
| 5.8     | 15        | 3.69%   |
| 6.0     | 14        | 3.45%   |
| 5.16    | 13        | 3.2%    |
| 4.15    | 10        | 2.46%   |
| 6.4     | 9         | 2.22%   |
| 5.18    | 8         | 1.97%   |
| 5.0     | 8         | 1.97%   |
| 4.18    | 7         | 1.72%   |
| 6.5     | 6         | 1.48%   |
| 6.3     | 6         | 1.48%   |
| 5.9     | 5         | 1.23%   |
| 5.17    | 5         | 1.23%   |
| 4.19    | 5         | 1.23%   |
| 5.6     | 3         | 0.74%   |
| 5.14    | 3         | 0.74%   |
| 4.9     | 3         | 0.74%   |
| 4.4     | 3         | 0.74%   |
| 5.12    | 2         | 0.49%   |
| 5.7     | 1         | 0.25%   |
| 5.2     | 1         | 0.25%   |
| 3.8     | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 357       | 97.28%  |
| i686   | 9         | 2.45%   |
| armv7l | 1         | 0.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 190       | 49.35%  |
| KDE5       | 67        | 17.4%   |
| XFCE       | 32        | 8.31%   |
| X-Cinnamon | 25        | 6.49%   |
| Unknown    | 23        | 5.97%   |
| KDE        | 12        | 3.12%   |
| MATE       | 7         | 1.82%   |
| LXQt       | 5         | 1.3%    |
| Pantheon   | 4         | 1.04%   |
| Hyprland   | 3         | 0.78%   |
| Budgie     | 3         | 0.78%   |
| Cinnamon   | 2         | 0.52%   |
| Unity      | 1         | 0.26%   |
| sway       | 1         | 0.26%   |
| river      | 1         | 0.26%   |
| pika:GNOME | 1         | 0.26%   |
| Openbox    | 1         | 0.26%   |
| LXDE       | 1         | 0.26%   |
| dwm        | 1         | 0.26%   |
| default    | 1         | 0.26%   |
| Deepin     | 1         | 0.26%   |
| Cutefish   | 1         | 0.26%   |
| BunsenLabs | 1         | 0.26%   |
| bspwm      | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 283       | 75.27%  |
| Wayland | 79        | 21.01%  |
| Unknown | 12        | 3.19%   |
| Tty     | 2         | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 194       | 50.79%  |
| SDDM    | 52        | 13.61%  |
| GDM3    | 47        | 12.3%   |
| GDM     | 46        | 12.04%  |
| LightDM | 34        | 8.9%    |
| TDM     | 6         | 1.57%   |
| SLiM    | 1         | 0.26%   |
| MDM     | 1         | 0.26%   |
| LXDM    | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_PH   | 168       | 44.8%   |
| en_US   | 156       | 41.6%   |
| Unknown | 23        | 6.13%   |
| C       | 8         | 2.13%   |
| de_DE   | 6         | 1.6%    |
| en_GB   | 5         | 1.33%   |
| en_AU   | 2         | 0.53%   |
| zh_HK   | 1         | 0.27%   |
| zh_CN   | 1         | 0.27%   |
| tl_PH   | 1         | 0.27%   |
| en_ZA   | 1         | 0.27%   |
| en_NZ   | 1         | 0.27%   |
| en_IN   | 1         | 0.27%   |
| en_CA   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 201       | 53.03%  |
| BIOS | 178       | 46.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 266       | 70.56%  |
| Btrfs   | 57        | 15.12%  |
| Overlay | 33        | 8.75%   |
| Unknown | 7         | 1.86%   |
| Tmpfs   | 5         | 1.33%   |
| Xfs     | 4         | 1.06%   |
| Ext2    | 3         | 0.8%    |
| Zfs     | 2         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 201       | 52.89%  |
| GPT     | 144       | 37.89%  |
| MBR     | 35        | 9.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 339       | 91.62%  |
| Yes       | 31        | 8.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 268       | 71.85%  |
| Yes       | 105       | 28.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 83        | 22.68%  |
| Acer                | 67        | 18.31%  |
| Hewlett-Packard     | 51        | 13.93%  |
| ASUSTek Computer    | 42        | 11.48%  |
| Dell                | 41        | 11.2%   |
| Toshiba             | 14        | 3.83%   |
| MSI                 | 10        | 2.73%   |
| Unknown             | 8         | 2.19%   |
| Samsung Electronics | 7         | 1.91%   |
| Valve               | 6         | 1.64%   |
| Apple               | 6         | 1.64%   |
| HUAWEI              | 5         | 1.37%   |
| Sony                | 4         | 1.09%   |
| Clevo               | 4         | 1.09%   |
| NEC Computers       | 3         | 0.82%   |
| eMachines           | 3         | 0.82%   |
| Jumper              | 2         | 0.55%   |
| Google              | 2         | 0.55%   |
| realme              | 1         | 0.27%   |
| PERSONA             | 1         | 0.27%   |
| Notebook            | 1         | 0.27%   |
| HASEE Computer      | 1         | 0.27%   |
| Gigabyte Technology | 1         | 0.27%   |
| Fujitsu             | 1         | 0.27%   |
| Cubix               | 1         | 0.27%   |
| ALLDOCUBE           | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 11        | 3.01%   |
| Valve Jupiter                            | 6         | 1.64%   |
| Acer Aspire ES1-132                      | 6         | 1.64%   |
| HP Notebook                              | 3         | 0.82%   |
| Clevo M7x0S                              | 3         | 0.82%   |
| MSI Modern 14 B4MW                       | 2         | 0.55%   |
| Lenovo V110-14IAP 80TF                   | 2         | 0.55%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 2         | 0.55%   |
| Lenovo IdeaPad 100-15IBY 80MJ            | 2         | 0.55%   |
| Jumper EZbook                            | 2         | 0.55%   |
| HP Pavilion Notebook                     | 2         | 0.55%   |
| HP Pavilion Gaming Laptop 15-ec2xxx      | 2         | 0.55%   |
| HP Pavilion Gaming Laptop 15-dk2xxx      | 2         | 0.55%   |
| HP EliteBook 840 G6                      | 2         | 0.55%   |
| eMachines eM350                          | 2         | 0.55%   |
| Dell Vostro 5515                         | 2         | 0.55%   |
| Dell Latitude E7450                      | 2         | 0.55%   |
| Dell Inspiron 7472                       | 2         | 0.55%   |
| Dell Inspiron 5567                       | 2         | 0.55%   |
| ASUS X540NA                              | 2         | 0.55%   |
| ASUS X510UQ                              | 2         | 0.55%   |
| ASUS VivoBook_ASUSLaptop M1603QA_M1603QA | 2         | 0.55%   |
| Apple MacBookPro5,5                      | 2         | 0.55%   |
| Acer TravelMate P249-G2-M                | 2         | 0.55%   |
| Acer TravelMate B113                     | 2         | 0.55%   |
| Acer Swift SF314-57                      | 2         | 0.55%   |
| Acer Nitro AN515-55                      | 2         | 0.55%   |
| Acer Aspire E5-551G                      | 2         | 0.55%   |
| Acer Aspire E5-473G                      | 2         | 0.55%   |
| Acer Aspire E3-111                       | 2         | 0.55%   |
| Acer Aspire A315-51                      | 2         | 0.55%   |
| Acer Aspire A315-41G                     | 2         | 0.55%   |
| Toshiba TECRA Z50-C                      | 1         | 0.27%   |
| Toshiba TECRA R940                       | 1         | 0.27%   |
| Toshiba Satellite Pro U400               | 1         | 0.27%   |
| Toshiba Satellite P845                   | 1         | 0.27%   |
| Toshiba Satellite L855                   | 1         | 0.27%   |
| Toshiba Satellite L515                   | 1         | 0.27%   |
| Toshiba Satellite E45t-A                 | 1         | 0.27%   |
| Toshiba Satellite C650                   | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 46        | 12.57%  |
| Lenovo ThinkPad   | 38        | 10.38%  |
| Lenovo IdeaPad    | 32        | 8.74%   |
| Dell Inspiron     | 20        | 5.46%   |
| HP Pavilion       | 15        | 4.1%    |
| Unknown           | 11        | 3.01%   |
| ASUS VivoBook     | 10        | 2.73%   |
| Dell Latitude     | 9         | 2.46%   |
| Toshiba Satellite | 8         | 2.19%   |
| HP Laptop         | 8         | 2.19%   |
| Acer TravelMate   | 8         | 2.19%   |
| Valve Jupiter     | 6         | 1.64%   |
| HP ProBook        | 5         | 1.37%   |
| HP EliteBook      | 5         | 1.37%   |
| Acer Nitro        | 5         | 1.37%   |
| Lenovo Legion     | 4         | 1.09%   |
| Dell Vostro       | 4         | 1.09%   |
| ASUS TUF          | 4         | 1.09%   |
| ASUS ROG          | 4         | 1.09%   |
| HP Notebook       | 3         | 0.82%   |
| Dell XPS          | 3         | 0.82%   |
| Dell Precision    | 3         | 0.82%   |
| Clevo M7x0S       | 3         | 0.82%   |
| Acer Swift        | 3         | 0.82%   |
| Toshiba TECRA     | 2         | 0.55%   |
| Toshiba dynabook  | 2         | 0.55%   |
| MSI Modern        | 2         | 0.55%   |
| MSI CX62          | 2         | 0.55%   |
| Lenovo V110-14IAP | 2         | 0.55%   |
| Jumper EZbook     | 2         | 0.55%   |
| HP Stream         | 2         | 0.55%   |
| HP OMEN           | 2         | 0.55%   |
| HP ENVY           | 2         | 0.55%   |
| eMachines eM350   | 2         | 0.55%   |
| ASUS X540NA       | 2         | 0.55%   |
| ASUS X510UQ       | 2         | 0.55%   |
| ASUS ASUS         | 2         | 0.55%   |
| Apple MacBookPro5 | 2         | 0.55%   |
| Acer Predator     | 2         | 0.55%   |
| Toshiba PORTEGE   | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 36        | 9.84%   |
| 2012    | 34        | 9.29%   |
| 2016    | 33        | 9.02%   |
| 2021    | 29        | 7.92%   |
| 2017    | 29        | 7.92%   |
| 2018    | 28        | 7.65%   |
| 2020    | 27        | 7.38%   |
| 2014    | 25        | 6.83%   |
| 2011    | 24        | 6.56%   |
| 2022    | 22        | 6.01%   |
| 2010    | 19        | 5.19%   |
| 2015    | 18        | 4.92%   |
| 2013    | 13        | 3.55%   |
| 2009    | 12        | 3.28%   |
| 2008    | 7         | 1.91%   |
| 2007    | 3         | 0.82%   |
| 2006    | 3         | 0.82%   |
| 2023    | 2         | 0.55%   |
| Unknown | 2         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 366       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 316       | 85.64%  |
| Enabled  | 53        | 14.36%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 364       | 99.45%  |
| Yes  | 2         | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 101       | 27.15%  |
| 3.01-4.0    | 82        | 22.04%  |
| 8.01-16.0   | 70        | 18.82%  |
| 16.01-24.0  | 52        | 13.98%  |
| 1.01-2.0    | 40        | 10.75%  |
| 32.01-64.0  | 12        | 3.23%   |
| 2.01-3.0    | 8         | 2.15%   |
| 0.51-1.0    | 4         | 1.08%   |
| 24.01-32.0  | 2         | 0.54%   |
| 64.01-256.0 | 1         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 138       | 33.58%  |
| 1.01-2.0  | 134       | 32.6%   |
| 4.01-8.0  | 51        | 12.41%  |
| 3.01-4.0  | 49        | 11.92%  |
| 0.51-1.0  | 25        | 6.08%   |
| 8.01-16.0 | 12        | 2.92%   |
| 0.01-0.5  | 1         | 0.24%   |
| Unknown   | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 271       | 72.07%  |
| 2      | 87        | 23.14%  |
| 3      | 14        | 3.72%   |
| 0      | 2         | 0.53%   |
| 5      | 1         | 0.27%   |
| 4      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 254       | 68.65%  |
| Yes       | 116       | 31.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 286       | 78.14%  |
| No        | 80        | 21.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 358       | 97.81%  |
| No        | 8         | 2.19%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 296       | 79.78%  |
| No        | 75        | 20.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Philippines | 366       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Quezon City         | 53        | 13.15%  |
| Cebu City           | 35        | 8.68%   |
| Manila              | 19        | 4.71%   |
| Davao City          | 19        | 4.71%   |
| Angeles City        | 17        | 4.22%   |
| Pasig               | 14        | 3.47%   |
| Paranaque City      | 14        | 3.47%   |
| Makati City         | 13        | 3.23%   |
| Caloocan City       | 13        | 3.23%   |
| Bacolod City        | 11        | 2.73%   |
| Lahug               | 10        | 2.48%   |
| Bacoor              | 9         | 2.23%   |
| San Jose del Monte  | 8         | 1.99%   |
| Iloilo City         | 8         | 1.99%   |
| Mandaluyong City    | 7         | 1.74%   |
| Cagayan de Oro      | 7         | 1.74%   |
| San Miguel          | 6         | 1.49%   |
| San Fernando City   | 6         | 1.49%   |
| Las Pinas           | 6         | 1.49%   |
| Imus                | 6         | 1.49%   |
| Tarlac City         | 5         | 1.24%   |
| Santa Rosa          | 5         | 1.24%   |
| Manajao             | 5         | 1.24%   |
| Dasmarinas          | 5         | 1.24%   |
| City of Muntinglupa | 5         | 1.24%   |
| San Pablo City      | 4         | 0.99%   |
| Malolos             | 4         | 0.99%   |
| Legazpi             | 4         | 0.99%   |
| Calamba             | 4         | 0.99%   |
| Baguio City         | 4         | 0.99%   |
| San Pedro           | 3         | 0.74%   |
| San Juan            | 3         | 0.74%   |
| Lucena City         | 3         | 0.74%   |
| La Trinidad         | 3         | 0.74%   |
| Iligan City         | 3         | 0.74%   |
| Zamboanga City      | 2         | 0.5%    |
| Taytay              | 2         | 0.5%    |
| Talisay City        | 2         | 0.5%    |
| Tagbilaran          | 2         | 0.5%    |
| Pasay               | 2         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 63        | 86     | 13.43%  |
| WDC                       | 61        | 68     | 13.01%  |
| Toshiba                   | 54        | 71     | 11.51%  |
| Samsung Electronics       | 45        | 56     | 9.59%   |
| Sandisk                   | 27        | 33     | 5.76%   |
| Unknown                   | 24        | 31     | 5.12%   |
| Kingston                  | 22        | 24     | 4.69%   |
| SK hynix                  | 19        | 26     | 4.05%   |
| Hitachi                   | 15        | 21     | 3.2%    |
| Intel                     | 14        | 16     | 2.99%   |
| HGST                      | 12        | 12     | 2.56%   |
| Micron Technology         | 11        | 16     | 2.35%   |
| Ramsta                    | 7         | 8      | 1.49%   |
| Crucial                   | 6         | 6      | 1.28%   |
| A-DATA Technology         | 6         | 10     | 1.28%   |
| China                     | 5         | 6      | 1.07%   |
| Phison                    | 4         | 4      | 0.85%   |
| Team                      | 3         | 5      | 0.64%   |
| Silicon Motion            | 3         | 4      | 0.64%   |
| Micron/Crucial Technology | 3         | 3      | 0.64%   |
| LITEONIT                  | 3         | 5      | 0.64%   |
| JMicron Technology        | 3         | 6      | 0.64%   |
| Fujitsu                   | 3         | 4      | 0.64%   |
| Apple                     | 3         | 3      | 0.64%   |
| TAMMUZ                    | 2         | 5      | 0.43%   |
| ShiJi                     | 2         | 2      | 0.43%   |
| Phison Electronics        | 2         | 2      | 0.43%   |
| O2 Micro                  | 2         | 2      | 0.43%   |
| Netac                     | 2         | 2      | 0.43%   |
| Lite-On                   | 2         | 4      | 0.43%   |
| KingSpec                  | 2         | 3      | 0.43%   |
| Indilinx                  | 2         | 2      | 0.43%   |
| HS-SSD-E100               | 2         | 2      | 0.43%   |
| HS-SSD-C100               | 2         | 3      | 0.43%   |
| Unknown                   | 2         | 2      | 0.43%   |
| WALRAM                    | 1         | 1      | 0.21%   |
| Vaseky                    | 1         | 2      | 0.21%   |
| USB3.0                    | 1         | 1      | 0.21%   |
| UMIS                      | 1         | 1      | 0.21%   |
| Transcend                 | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                          | 17        | 3.49%   |
| Seagate ST1000LM035-1RK172 1TB                    | 14        | 2.87%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 7         | 1.44%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 6         | 1.23%   |
| Toshiba MQ04ABF100 1TB                            | 6         | 1.23%   |
| Unknown MMC Card  32GB                            | 5         | 1.03%   |
| Toshiba MQ01ABD100 1TB                            | 5         | 1.03%   |
| Seagate ST500LT012-9WS142 500GB                   | 5         | 1.03%   |
| Seagate ST500LT012-1DG142 500GB                   | 5         | 1.03%   |
| Kingston SA400S37240G 240GB SSD                   | 5         | 1.03%   |
| Seagate ST2000LM007-1R8174 2TB                    | 4         | 0.82%   |
| Seagate ST1000LM049-2GH172 1TB                    | 4         | 0.82%   |
| HGST HTS721010A9E630 1TB                          | 4         | 0.82%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 3         | 0.62%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 3         | 0.62%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 3         | 0.62%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 3         | 0.62%   |
| Unknown MMC Card  64GB                            | 3         | 0.62%   |
| SK hynix NVMe SSD Drive 512GB                     | 3         | 0.62%   |
| Seagate ST9500325AS 500GB                         | 3         | 0.62%   |
| Seagate ST500LM030-2E717D 500GB                   | 3         | 0.62%   |
| Seagate ST500LM030-1RK17D 500GB                   | 3         | 0.62%   |
| Seagate ST1000LM048-2E7172 1TB                    | 3         | 0.62%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB | 3         | 0.62%   |
| Samsung NVMe SSD Drive 512GB                      | 3         | 0.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 0.62%   |
| Micron NVMe SSD Drive 512GB                       | 3         | 0.62%   |
| Kingston SA400S37120G 120GB SSD                   | 3         | 0.62%   |
| Intel SSDPEKNU512GZ 512GB                         | 3         | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 2         | 0.41%   |
| WDC WD5000LPVX-80V0TT0 500GB                      | 2         | 0.41%   |
| WDC WD5000LPCX-24C6HT0 500GB                      | 2         | 0.41%   |
| WDC WD10SPZX-24Z10 1TB                            | 2         | 0.41%   |
| Unknown SD/MMC/MS PRO 16GB                        | 2         | 0.41%   |
| Unknown MMC Card  7GB                             | 2         | 0.41%   |
| Unknown MMC Card  256GB                           | 2         | 0.41%   |
| Unknown MMC Card  128GB                           | 2         | 0.41%   |
| Unknown DA4032  32GB                              | 2         | 0.41%   |
| Toshiba MK2555GSX 250GB                           | 2         | 0.41%   |
| TAMMUZ SSD 500GB                                  | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 86     | 32.14%  |
| WDC                 | 51        | 57     | 26.02%  |
| Toshiba             | 46        | 60     | 23.47%  |
| Hitachi             | 15        | 21     | 7.65%   |
| HGST                | 12        | 12     | 6.12%   |
| Fujitsu             | 3         | 4      | 1.53%   |
| Unknown             | 2         | 2      | 1.02%   |
| USB3.0              | 1         | 1      | 0.51%   |
| Samsung Electronics | 1         | 1      | 0.51%   |
| SAGE                | 1         | 1      | 0.51%   |
| HGST HTS            | 1         | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 21     | 14.63%  |
| Kingston            | 15        | 15     | 12.2%   |
| SanDisk             | 12        | 15     | 9.76%   |
| Ramsta              | 7         | 8      | 5.69%   |
| WDC                 | 5         | 6      | 4.07%   |
| Micron Technology   | 5         | 5      | 4.07%   |
| Crucial             | 5         | 5      | 4.07%   |
| China               | 5         | 6      | 4.07%   |
| Toshiba             | 4         | 6      | 3.25%   |
| SK hynix            | 4         | 9      | 3.25%   |
| A-DATA Technology   | 4         | 7      | 3.25%   |
| Team                | 3         | 5      | 2.44%   |
| LITEONIT            | 3         | 5      | 2.44%   |
| Apple               | 3         | 3      | 2.44%   |
| TAMMUZ              | 2         | 5      | 1.63%   |
| Netac               | 2         | 2      | 1.63%   |
| KingSpec            | 2         | 3      | 1.63%   |
| Intel               | 2         | 2      | 1.63%   |
| HS-SSD-E100         | 2         | 2      | 1.63%   |
| Vaseky              | 1         | 2      | 0.81%   |
| Transcend           | 1         | 1      | 0.81%   |
| Teclast             | 1         | 4      | 0.81%   |
| ShiJi               | 1         | 1      | 0.81%   |
| SADAYU              | 1         | 1      | 0.81%   |
| PNY                 | 1         | 1      | 0.81%   |
| Plextor             | 1         | 1      | 0.81%   |
| Phison              | 1         | 1      | 0.81%   |
| OCZ                 | 1         | 1      | 0.81%   |
| NT-512              | 1         | 1      | 0.81%   |
| Kingmax             | 1         | 1      | 0.81%   |
| Indilinx            | 1         | 1      | 0.81%   |
| HS-SSD-C100         | 1         | 1      | 0.81%   |
| Hikvision           | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 1      | 0.81%   |
| GALAX               | 1         | 1      | 0.81%   |
| DTGC-C              | 1         | 1      | 0.81%   |
| Colorful            | 1         | 1      | 0.81%   |
| BR                  | 1         | 1      | 0.81%   |
| ASUS-PHISON         | 1         | 2      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 187       | 246    | 42.21%  |
| SSD     | 114       | 155    | 25.73%  |
| NVMe    | 110       | 146    | 24.83%  |
| MMC     | 25        | 32     | 5.64%   |
| Unknown | 7         | 11     | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 276       | 391    | 64.34%  |
| NVMe | 108       | 144    | 25.17%  |
| MMC  | 25        | 32     | 5.83%   |
| SAS  | 20        | 23     | 4.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 212       | 282    | 69.74%  |
| 0.51-1.0   | 80        | 103    | 26.32%  |
| 1.01-2.0   | 10        | 14     | 3.29%   |
| 3.01-4.0   | 1         | 1      | 0.33%   |
| 4.01-10.0  | 1         | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 107       | 27.94%  |
| 251-500        | 101       | 26.37%  |
| 501-1000       | 61        | 15.93%  |
| 1-20           | 34        | 8.88%   |
| 1001-2000      | 32        | 8.36%   |
| 51-100         | 21        | 5.48%   |
| 21-50          | 15        | 3.92%   |
| More than 3000 | 4         | 1.04%   |
| 2001-3000      | 4         | 1.04%   |
| Unknown        | 4         | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 164       | 40.1%   |
| 21-50     | 82        | 20.05%  |
| 51-100    | 59        | 14.43%  |
| 101-250   | 56        | 13.69%  |
| 251-500   | 27        | 6.6%    |
| 501-1000  | 13        | 3.18%   |
| Unknown   | 4         | 0.98%   |
| 1001-2000 | 3         | 0.73%   |
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
| Detected | 229       | 370    | 57.68%  |
| Works    | 138       | 185    | 34.76%  |
| Malfunc  | 29        | 34     | 7.3%    |
| Failed   | 1         | 1      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 272       | 64%     |
| AMD                              | 42        | 9.88%   |
| Samsung Electronics              | 26        | 6.12%   |
| SanDisk                          | 16        | 3.76%   |
| SK hynix                         | 15        | 3.53%   |
| Nvidia                           | 7         | 1.65%   |
| Kingston Technology Company      | 7         | 1.65%   |
| Phison Electronics               | 6         | 1.41%   |
| Micron Technology                | 6         | 1.41%   |
| Toshiba America Info Systems     | 4         | 0.94%   |
| Micron/Crucial Technology        | 4         | 0.94%   |
| Silicon Motion                   | 3         | 0.71%   |
| Silicon Integrated Systems [SiS] | 3         | 0.71%   |
| Solid State Storage Technology   | 2         | 0.47%   |
| O2 Micro                         | 2         | 0.47%   |
| Lite-On Technology               | 2         | 0.47%   |
| ADATA Technology                 | 2         | 0.47%   |
| Union Memory (Shenzhen)          | 1         | 0.24%   |
| Shenzhen Longsys Electronics     | 1         | 0.24%   |
| Realtek Semiconductor            | 1         | 0.24%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.24%   |
| Lenovo                           | 1         | 0.24%   |
| KIOXIA                           | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 38        | 8.21%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 38        | 8.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 29        | 6.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 27        | 5.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 19        | 4.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 16        | 3.46%   |
| Intel Volume Management Device NVMe RAID Controller                              | 14        | 3.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 2.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 12        | 2.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 2.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 9         | 1.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 8         | 1.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 1.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 1.51%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 1.51%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 7         | 1.51%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 1.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 1.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 1.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 1.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 1.51%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 1.3%    |
| Intel Alder Lake-P SATA AHCI Controller                                          | 5         | 1.08%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 4         | 0.86%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 4         | 0.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 0.86%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 4         | 0.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.86%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.65%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.65%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.65%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3         | 0.65%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 3         | 0.65%   |
| Intel SSD 660P Series                                                            | 3         | 0.65%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 3         | 0.65%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 2         | 0.43%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 2         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 275       | 61.52%  |
| NVMe | 107       | 23.94%  |
| RAID | 43        | 9.62%   |
| IDE  | 22        | 4.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 300       | 81.97%  |
| AMD    | 65        | 17.76%  |
| ARM    | 1         | 0.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 2.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 2.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 2.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 2.19%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 8         | 2.19%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 2.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.91%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 1.64%   |
| AMD Custom APU 0405                           | 6         | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.37%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.37%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 5         | 1.37%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 1.37%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.37%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.09%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 1.09%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.09%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.09%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.09%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 1.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.82%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 3         | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.82%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.82%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 3         | 0.82%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.82%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.82%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 3         | 0.82%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.82%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.82%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.82%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.82%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 96        | 26.23%  |
| Intel Core i7           | 60        | 16.39%  |
| Intel Celeron           | 40        | 10.93%  |
| Intel Core i3           | 33        | 9.02%   |
| Other                   | 30        | 8.2%    |
| AMD Ryzen 5             | 16        | 4.37%   |
| Intel Core 2 Duo        | 12        | 3.28%   |
| Intel Atom              | 12        | 3.28%   |
| Intel Pentium           | 9         | 2.46%   |
| AMD Ryzen 7             | 9         | 2.46%   |
| AMD Ryzen 3             | 8         | 2.19%   |
| Intel Pentium Silver    | 4         | 1.09%   |
| Intel Pentium Dual-Core | 4         | 1.09%   |
| AMD A8                  | 4         | 1.09%   |
| AMD A6                  | 4         | 1.09%   |
| AMD Athlon              | 3         | 0.82%   |
| Intel Genuine           | 2         | 0.55%   |
| Intel Core m3           | 2         | 0.55%   |
| AMD Turion 64 X2 Mobile | 2         | 0.55%   |
| AMD A10                 | 2         | 0.55%   |
| Intel Pentium Dual      | 1         | 0.27%   |
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
| 2      | 184       | 50.27%  |
| 4      | 135       | 36.89%  |
| 6      | 19        | 5.19%   |
| 1      | 11        | 3.01%   |
| 8      | 10        | 2.73%   |
| 10     | 3         | 0.82%   |
| 14     | 2         | 0.55%   |
| 24     | 1         | 0.27%   |
| 12     | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 366       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 264       | 72.13%  |
| 1      | 102       | 27.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 357       | 97.28%  |
| Unknown        | 6         | 1.63%   |
| 32-bit         | 4         | 1.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 125       | 32.81%  |
| 0x306a9    | 24        | 6.3%    |
| 0x206a7    | 17        | 4.46%   |
| 0x506c9    | 13        | 3.41%   |
| 0x406e3    | 13        | 3.41%   |
| 0x806ea    | 11        | 2.89%   |
| 0x806ec    | 10        | 2.62%   |
| 0x806e9    | 10        | 2.62%   |
| 0x30678    | 10        | 2.62%   |
| 0x1067a    | 10        | 2.62%   |
| 0x306d4    | 8         | 2.1%    |
| 0x0a50000c | 7         | 1.84%   |
| 0x806c1    | 6         | 1.57%   |
| 0x906ea    | 5         | 1.31%   |
| 0x706e5    | 5         | 1.31%   |
| 0x406c4    | 5         | 1.31%   |
| 0x40651    | 5         | 1.31%   |
| 0x306c3    | 5         | 1.31%   |
| 0x20655    | 5         | 1.31%   |
| 0x106ca    | 5         | 1.31%   |
| 0xa0652    | 4         | 1.05%   |
| 0x706a1    | 4         | 1.05%   |
| 0x10676    | 4         | 1.05%   |
| 0x08608103 | 4         | 1.05%   |
| 0x08108109 | 4         | 1.05%   |
| 0x906e9    | 3         | 0.79%   |
| 0x906a4    | 3         | 0.79%   |
| 0x806eb    | 3         | 0.79%   |
| 0x406c3    | 3         | 0.79%   |
| 0x20652    | 3         | 0.79%   |
| 0x08600104 | 3         | 0.79%   |
| 0x07030105 | 3         | 0.79%   |
| 0x06003106 | 3         | 0.79%   |
| 0x906c0    | 2         | 0.52%   |
| 0x906a3    | 2         | 0.52%   |
| 0x706a8    | 2         | 0.52%   |
| 0x6ec      | 2         | 0.52%   |
| 0x506e3    | 2         | 0.52%   |
| 0x30661    | 2         | 0.52%   |
| 0x0a50000d | 2         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 69        | 18.8%   |
| IvyBridge        | 33        | 8.99%   |
| SandyBridge      | 22        | 5.99%   |
| Skylake          | 21        | 5.72%   |
| Silvermont       | 20        | 5.45%   |
| Penryn           | 17        | 4.63%   |
| Haswell          | 16        | 4.36%   |
| Goldmont         | 16        | 4.36%   |
| Unknown          | 16        | 4.36%   |
| Broadwell        | 14        | 3.81%   |
| TigerLake        | 13        | 3.54%   |
| Zen 3            | 11        | 3%      |
| Zen+             | 10        | 2.72%   |
| Westmere         | 10        | 2.72%   |
| Bonnell          | 9         | 2.45%   |
| Goldmont plus    | 8         | 2.18%   |
| CometLake        | 8         | 2.18%   |
| Alderlake Hybrid | 8         | 2.18%   |
| Zen 2            | 6         | 1.63%   |
| Icelake          | 6         | 1.63%   |
| Puma             | 5         | 1.36%   |
| K8 Hammer        | 4         | 1.09%   |
| Zen              | 3         | 0.82%   |
| Steamroller      | 3         | 0.82%   |
| P6               | 3         | 0.82%   |
| Excavator        | 3         | 0.82%   |
| Core             | 3         | 0.82%   |
| Tremont          | 2         | 0.54%   |
| Piledriver       | 2         | 0.54%   |
| Jaguar           | 2         | 0.54%   |
| Bobcat           | 2         | 0.54%   |
| K8 & K10 hybrid  | 1         | 0.27%   |
| K10 Llano        | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 287       | 60.29%  |
| Nvidia                           | 97        | 20.38%  |
| AMD                              | 89        | 18.7%   |
| Silicon Integrated Systems [SiS] | 3         | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 6.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 4.5%    |
| Intel UHD Graphics 620                                                                   | 19        | 3.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 3.07%   |
| Intel HD Graphics 620                                                                    | 15        | 3.07%   |
| Intel HD Graphics 500                                                                    | 14        | 2.86%   |
| Intel HD Graphics 5500                                                                   | 12        | 2.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 2.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 2.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.84%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 1.43%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 7         | 1.43%   |
| Intel HD Graphics 630                                                                    | 7         | 1.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.43%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.43%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 1.43%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.23%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 6         | 1.23%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 6         | 1.23%   |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 1.02%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.02%   |
| AMD Lucienne                                                                             | 5         | 1.02%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.82%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 4         | 0.82%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.82%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 184       | 50.14%  |
| Intel + Nvidia | 75        | 20.44%  |
| 1 x AMD        | 46        | 12.53%  |
| Intel + AMD    | 25        | 6.81%   |
| 1 x Nvidia     | 12        | 3.27%   |
| AMD + Nvidia   | 10        | 2.72%   |
| 2 x AMD        | 9         | 2.45%   |
| 1 x SiS        | 3         | 0.82%   |
| 2 x Intel      | 2         | 0.54%   |
| Other          | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 307       | 82.97%  |
| Proprietary | 56        | 15.14%  |
| Unknown     | 7         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 263       | 69.58%  |
| 1.01-2.0   | 38        | 10.05%  |
| 0.01-0.5   | 36        | 9.52%   |
| 3.01-4.0   | 18        | 4.76%   |
| 0.51-1.0   | 16        | 4.23%   |
| 7.01-8.0   | 4         | 1.06%   |
| 5.01-6.0   | 3         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 75        | 18.52%  |
| AU Optronics            | 68        | 16.79%  |
| BOE                     | 67        | 16.54%  |
| LG Display              | 48        | 11.85%  |
| Samsung Electronics     | 34        | 8.4%    |
| Lenovo                  | 14        | 3.46%   |
| InfoVision              | 8         | 1.98%   |
| Valve                   | 6         | 1.48%   |
| Sharp                   | 6         | 1.48%   |
| Philips                 | 6         | 1.48%   |
| PANDA                   | 6         | 1.48%   |
| AOC                     | 6         | 1.48%   |
| Sony                    | 5         | 1.23%   |
| Goldstar                | 5         | 1.23%   |
| Apple                   | 5         | 1.23%   |
| Acer                    | 5         | 1.23%   |
| Chi Mei Optoelectronics | 4         | 0.99%   |
| RTK                     | 3         | 0.74%   |
| ASUSTek Computer        | 3         | 0.74%   |
| LG Philips              | 2         | 0.49%   |
| InnoLux Display         | 2         | 0.49%   |
| Hewlett-Packard         | 2         | 0.49%   |
| Gigabyte Technology     | 2         | 0.49%   |
| Dell                    | 2         | 0.49%   |
| BenQ                    | 2         | 0.49%   |
| Ancor Communications    | 2         | 0.49%   |
| ___                     | 1         | 0.25%   |
| Unknown                 | 1         | 0.25%   |
| Toshiba                 | 1         | 0.25%   |
| TMX                     | 1         | 0.25%   |
| Quanta Display          | 1         | 0.25%   |
| Pixio                   | 1         | 0.25%   |
| Panasonic               | 1         | 0.25%   |
| MYS                     | 1         | 0.25%   |
| JDI                     | 1         | 0.25%   |
| IPS                     | 1         | 0.25%   |
| HKC                     | 1         | 0.25%   |
| HannStar                | 1         | 0.25%   |
| GreenWood               | 1         | 0.25%   |
| GDH                     | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 7         | 1.73%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 1.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 6         | 1.48%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 4         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 4         | 0.99%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 3         | 0.74%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 3         | 0.74%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 3         | 0.74%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO2992 1920x1080 344x193mm 15.5-inch        | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 0.74%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3549 1366x768 309x174mm 14.0-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 2         | 0.49%   |
| RTK 32V3H-H6A RTK4C54 1280x1024 697x392mm 31.5-inch                   | 2         | 0.49%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 2         | 0.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.49%   |
| LG Display LP101WSA-TLN1 LGD0295 1024x600 224x126mm 10.1-inch         | 2         | 0.49%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 2         | 0.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 0.49%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.49%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 2         | 0.49%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 2         | 0.49%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch      | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 164       | 43.16%  |
| 1920x1080 (FHD)    | 137       | 36.05%  |
| 1600x900 (HD+)     | 14        | 3.68%   |
| 3840x2160 (4K)     | 7         | 1.84%   |
| 1024x600           | 7         | 1.84%   |
| 800x1280           | 6         | 1.58%   |
| 2560x1440 (QHD)    | 6         | 1.58%   |
| 1920x1200 (WUXGA)  | 6         | 1.58%   |
| 1280x800 (WXGA)    | 6         | 1.58%   |
| 2560x1600          | 5         | 1.32%   |
| 1280x1024 (SXGA)   | 5         | 1.32%   |
| 1440x900 (WXGA+)   | 4         | 1.05%   |
| 1360x768           | 4         | 1.05%   |
| 2160x1440          | 3         | 0.79%   |
| 3000x2000          | 1         | 0.26%   |
| 2560x1080          | 1         | 0.26%   |
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
| 15      | 145       | 35.98%  |
| 13      | 71        | 17.62%  |
| 14      | 58        | 14.39%  |
| 17      | 20        | 4.96%   |
| 11      | 20        | 4.96%   |
| 12      | 13        | 3.23%   |
| 18      | 12        | 2.98%   |
| 27      | 9         | 2.23%   |
| 23      | 9         | 2.23%   |
| 21      | 8         | 1.99%   |
| 10      | 7         | 1.74%   |
| 7       | 6         | 1.49%   |
| 72      | 5         | 1.24%   |
| 31      | 5         | 1.24%   |
| 16      | 5         | 1.24%   |
| 24      | 3         | 0.74%   |
| Unknown | 2         | 0.5%    |
| 84      | 1         | 0.25%   |
| 54      | 1         | 0.25%   |
| 34      | 1         | 0.25%   |
| 20      | 1         | 0.25%   |
| 8       | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 253       | 63.41%  |
| 201-300     | 63        | 15.79%  |
| 401-500     | 21        | 5.26%   |
| 351-400     | 19        | 4.76%   |
| 501-600     | 17        | 4.26%   |
| 601-700     | 9         | 2.26%   |
| 1501-2000   | 6         | 1.5%    |
| 1-100       | 6         | 1.5%    |
| Unknown     | 2         | 0.5%    |
| 701-800     | 1         | 0.25%   |
| 101-200     | 1         | 0.25%   |
| 1001-1500   | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 325       | 90.28%  |
| 16/10   | 17        | 4.72%   |
| 0.67    | 6         | 1.67%   |
| 3/2     | 5         | 1.39%   |
| 5/4     | 3         | 0.83%   |
| 4/3     | 1         | 0.28%   |
| 21/9    | 1         | 0.28%   |
| 0.62    | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 142       | 35.32%  |
| 81-90          | 111       | 27.61%  |
| 51-60          | 20        | 4.98%   |
| 71-80          | 18        | 4.48%   |
| 201-250        | 16        | 3.98%   |
| 121-130        | 16        | 3.98%   |
| 141-150        | 15        | 3.73%   |
| 61-70          | 13        | 3.23%   |
| 301-350        | 9         | 2.24%   |
| More than 1000 | 7         | 1.74%   |
| 41-50          | 7         | 1.74%   |
| 1-40           | 7         | 1.74%   |
| 351-500        | 6         | 1.49%   |
| 111-120        | 6         | 1.49%   |
| 151-200        | 4         | 1%      |
| 91-100         | 2         | 0.5%    |
| Unknown        | 2         | 0.5%    |
| 131-140        | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 163       | 40.95%  |
| 101-120       | 160       | 40.2%   |
| 51-100        | 40        | 10.05%  |
| 161-240       | 19        | 4.77%   |
| 1-50          | 8         | 2.01%   |
| More than 240 | 6         | 1.51%   |
| Unknown       | 2         | 0.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 315       | 84%     |
| 2     | 48        | 12.8%   |
| 0     | 8         | 2.13%   |
| 3     | 4         | 1.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 216       | 37.63%  |
| Intel                            | 160       | 27.87%  |
| Qualcomm Atheros                 | 101       | 17.6%   |
| Broadcom                         | 45        | 7.84%   |
| Ralink Technology                | 7         | 1.22%   |
| MediaTek                         | 6         | 1.05%   |
| Nvidia                           | 5         | 0.87%   |
| Broadcom Limited                 | 5         | 0.87%   |
| TP-Link                          | 3         | 0.52%   |
| Silicon Integrated Systems [SiS] | 3         | 0.52%   |
| Qualcomm Atheros Communications  | 3         | 0.52%   |
| Marvell Technology Group         | 3         | 0.52%   |
| ASIX Electronics                 | 3         | 0.52%   |
| Ralink                           | 2         | 0.35%   |
| JMicron Technology               | 2         | 0.35%   |
| OPPO Electronics                 | 1         | 0.17%   |
| NetGear                          | 1         | 0.17%   |
| Hewlett-Packard                  | 1         | 0.17%   |
| Encore Electronics               | 1         | 0.17%   |
| DisplayLink                      | 1         | 0.17%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 129       | 19.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 6.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 3.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 18        | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 17        | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 2.53%   |
| Intel Wireless 7265                                               | 15        | 2.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 14        | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 1.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 1.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 12        | 1.79%   |
| Intel Wireless 3165                                               | 12        | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 10        | 1.49%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 1.34%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 1.19%   |
| Intel Wireless 8260                                               | 8         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.19%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 1.04%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 0.89%   |
| Intel Wireless 8265 / 8275                                        | 6         | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.74%   |
| Intel Wireless 7260                                               | 5         | 0.74%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 153       | 40.69%  |
| Qualcomm Atheros                | 88        | 23.4%   |
| Realtek Semiconductor           | 72        | 19.15%  |
| Broadcom                        | 35        | 9.31%   |
| Ralink Technology               | 7         | 1.86%   |
| MediaTek                        | 6         | 1.6%    |
| TP-Link                         | 3         | 0.8%    |
| Qualcomm Atheros Communications | 3         | 0.8%    |
| Ralink                          | 2         | 0.53%   |
| Broadcom Limited                | 2         | 0.53%   |
| NetGear                         | 1         | 0.27%   |
| Encore Electronics              | 1         | 0.27%   |
| Dell                            | 1         | 0.27%   |
| BUFFALO                         | 1         | 0.27%   |
| ASUSTek Computer                | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 5.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 4.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 4.51%   |
| Intel Wireless 7265                                                     | 15        | 3.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 3.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 13        | 3.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 3.18%   |
| Intel Wireless 3165                                                     | 12        | 3.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 2.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 2.65%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 2.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 2.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 2.12%   |
| Intel Wireless 8260                                                     | 8         | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 2.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.12%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1.86%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.33%   |
| Intel Wireless 7260                                                     | 5         | 1.33%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.8%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.8%    |
| Intel Centrino Wireless-N 2200                                          | 3         | 0.8%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 182       | 62.76%  |
| Intel                            | 50        | 17.24%  |
| Qualcomm Atheros                 | 23        | 7.93%   |
| Broadcom                         | 13        | 4.48%   |
| Nvidia                           | 5         | 1.72%   |
| Silicon Integrated Systems [SiS] | 3         | 1.03%   |
| Marvell Technology Group         | 3         | 1.03%   |
| Broadcom Limited                 | 3         | 1.03%   |
| ASIX Electronics                 | 3         | 1.03%   |
| JMicron Technology               | 2         | 0.69%   |
| OPPO Electronics                 | 1         | 0.34%   |
| DisplayLink                      | 1         | 0.34%   |
| Apple                            | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 129       | 44.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 13.99%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 5.8%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 2.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 1.71%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 1.37%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.37%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.02%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.68%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.68%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.68%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.68%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.68%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.68%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.68%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.34%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.34%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.34%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.34%   |
| OPPO RMX2027                                                      | 1         | 0.34%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.34%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.34%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 358       | 55.42%  |
| Ethernet | 286       | 44.27%  |
| Modem    | 2         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 310       | 82.45%  |
| Ethernet | 66        | 17.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 266       | 72.68%  |
| 1     | 92        | 25.14%  |
| 0     | 6         | 1.64%   |
| 3     | 2         | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 335       | 90.3%   |
| Yes  | 36        | 9.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 37.79%  |
| Realtek Semiconductor           | 38        | 12.71%  |
| IMC Networks                    | 29        | 9.7%    |
| Qualcomm Atheros Communications | 28        | 9.36%   |
| Lite-On Technology              | 26        | 8.7%    |
| Broadcom                        | 21        | 7.02%   |
| Foxconn / Hon Hai               | 16        | 5.35%   |
| Apple                           | 6         | 2.01%   |
| Toshiba                         | 4         | 1.34%   |
| Hewlett-Packard                 | 4         | 1.34%   |
| Cambridge Silicon Radio         | 4         | 1.34%   |
| Dell                            | 3         | 1%      |
| Chicony Electronics             | 3         | 1%      |
| Realtek                         | 1         | 0.33%   |
| Ralink Technology               | 1         | 0.33%   |
| Ralink                          | 1         | 0.33%   |
| Foxconn International           | 1         | 0.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 44        | 14.72%  |
| Realtek Bluetooth Radio                             | 24        | 8.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 7.69%   |
| Intel AX201 Bluetooth                               | 19        | 6.35%   |
| IMC Networks Bluetooth Radio                        | 14        | 4.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 3.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 3.68%   |
| IMC Networks Bluetooth Device                       | 10        | 3.34%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 3.01%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 2.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 2.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.67%   |
| Lite-On Bluetooth Device                            | 5         | 1.67%   |
| Intel Bluetooth Device                              | 5         | 1.67%   |
| Intel AX200 Bluetooth                               | 5         | 1.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.67%   |
| Realtek RTL8821A Bluetooth                          | 4         | 1.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.34%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 1.34%   |
| Intel AX210 Bluetooth                               | 4         | 1.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.34%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.34%   |
| Realtek RTL8723B Bluetooth                          | 3         | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1%      |
| IMC Networks Wireless_Device                        | 3         | 1%      |
| Chicony Bluetooth (RTL8723BE)                       | 3         | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.67%   |
| Lite-On Wireless_Device                             | 2         | 0.67%   |
| Lite-On BCM43142A0                                  | 2         | 0.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.67%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.67%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.67%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.67%   |
| Broadcom HP Portable Valentine                      | 2         | 0.67%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.67%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.67%   |
| Apple Bluetooth Host Controller                     | 2         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 289       | 68.32%  |
| AMD                              | 63        | 14.89%  |
| Nvidia                           | 48        | 11.35%  |
| Silicon Integrated Systems [SiS] | 3         | 0.71%   |
| Plantronics                      | 3         | 0.71%   |
| Logitech                         | 3         | 0.71%   |
| JMTek                            | 3         | 0.71%   |
| Realtek Semiconductor            | 2         | 0.47%   |
| C-Media Electronics              | 2         | 0.47%   |
| SteelSeries ApS                  | 1         | 0.24%   |
| OS AS700 USB                     | 1         | 0.24%   |
| OPPO Electronics                 | 1         | 0.24%   |
| Micronas                         | 1         | 0.24%   |
| Hewlett-Packard                  | 1         | 0.24%   |
| Generalplus Technology           | 1         | 0.24%   |
| Creative Technology              | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 52        | 10.44%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 35        | 7.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 34        | 6.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 4.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 3.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 3.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 2.81%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 2.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 2.61%   |
| AMD FCH Azalia Controller                                                                         | 13        | 2.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 2.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 2.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 2.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.61%   |
| Intel CM238 HD Audio Controller                                                                   | 8         | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.41%   |
| Nvidia Audio device                                                                               | 7         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 1.41%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 7         | 1.41%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.8%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 3         | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.6%    |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 25.1%   |
| SK hynix            | 52        | 21.76%  |
| Kingston            | 38        | 15.9%   |
| Micron Technology   | 24        | 10.04%  |
| Unknown             | 15        | 6.28%   |
| Crucial             | 12        | 5.02%   |
| Ramaxel Technology  | 9         | 3.77%   |
| Team                | 5         | 2.09%   |
| Unknown (ABCD)      | 4         | 1.67%   |
| Nanya Technology    | 4         | 1.67%   |
| Elpida              | 3         | 1.26%   |
| Transcend           | 2         | 0.84%   |
| A-DATA Technology   | 2         | 0.84%   |
| Unknown (8A5D)      | 1         | 0.42%   |
| Qimonda             | 1         | 0.42%   |
| Patriot             | 1         | 0.42%   |
| G.Skill             | 1         | 0.42%   |
| ChangXin Memory     | 1         | 0.42%   |
| Avant               | 1         | 0.42%   |
| ASint Technology    | 1         | 0.42%   |
| Apacer              | 1         | 0.42%   |
| Unknown             | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 2.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 2.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 1.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.98%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.59%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 1.59%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.59%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 1.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.19%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.19%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.19%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.19%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s          | 3         | 1.19%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 2         | 0.79%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s        | 2         | 0.79%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.79%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.79%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.79%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 2         | 0.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.79%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.79%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.79%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4267MT/s               | 2         | 0.79%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.79%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 0.79%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.79%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 0.79%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 0.79%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 48.69%  |
| DDR3    | 66        | 34.55%  |
| LPDDR4  | 11        | 5.76%   |
| DDR2    | 9         | 4.71%   |
| DDR5    | 4         | 2.09%   |
| LPDDR3  | 2         | 1.05%   |
| Unknown | 2         | 1.05%   |
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
| SODIMM       | 175       | 92.11%  |
| Row Of Chips | 14        | 7.37%   |
| Unknown      | 1         | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 89        | 40.45%  |
| 4096  | 66        | 30%     |
| 2048  | 29        | 13.18%  |
| 16384 | 19        | 8.64%   |
| 1024  | 11        | 5%      |
| 32768 | 6         | 2.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 48        | 22.43%  |
| 2667    | 46        | 21.5%   |
| 3200    | 43        | 20.09%  |
| 2400    | 16        | 7.48%   |
| 667     | 11        | 5.14%   |
| 1334    | 9         | 4.21%   |
| 2133    | 8         | 3.74%   |
| 1333    | 7         | 3.27%   |
| 4800    | 3         | 1.4%    |
| 1067    | 3         | 1.4%    |
| 8400    | 2         | 0.93%   |
| 4267    | 2         | 0.93%   |
| 3733    | 2         | 0.93%   |
| 1066    | 2         | 0.93%   |
| Unknown | 2         | 0.93%   |
| 5600    | 1         | 0.47%   |
| 5500    | 1         | 0.47%   |
| 4266    | 1         | 0.47%   |
| 3266    | 1         | 0.47%   |
| 2048    | 1         | 0.47%   |
| 1867    | 1         | 0.47%   |
| 1866    | 1         | 0.47%   |
| 800     | 1         | 0.47%   |
| 533     | 1         | 0.47%   |
| 400     | 1         | 0.47%   |

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
| Chicony Electronics                    | 87        | 27.27%  |
| IMC Networks                           | 32        | 10.03%  |
| Realtek Semiconductor                  | 29        | 9.09%   |
| Quanta                                 | 23        | 7.21%   |
| Microdia                               | 20        | 6.27%   |
| Bison Electronics                      | 19        | 5.96%   |
| Sunplus Innovation Technology          | 14        | 4.39%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.39%   |
| Lite-On Technology                     | 11        | 3.45%   |
| Syntek                                 | 7         | 2.19%   |
| Suyin                                  | 7         | 2.19%   |
| Silicon Motion                         | 7         | 2.19%   |
| Apple                                  | 7         | 2.19%   |
| Luxvisions Innotech Limited            | 6         | 1.88%   |
| Alcor Micro                            | 5         | 1.57%   |
| Samsung Electronics                    | 3         | 0.94%   |
| ALi                                    | 3         | 0.94%   |
| Acer                                   | 3         | 0.94%   |
| Z-Star Microelectronics                | 2         | 0.63%   |
| OmniVision Technologies                | 2         | 0.63%   |
| Importek                               | 2         | 0.63%   |
| icSpring                               | 2         | 0.63%   |
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
| Chicony Integrated Camera                                       | 21        | 6.58%   |
| Chicony HD WebCam                                               | 18        | 5.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 10        | 3.13%   |
| Quanta VGA WebCam                                               | 9         | 2.82%   |
| Microdia Integrated_Webcam_HD                                   | 9         | 2.82%   |
| Realtek Integrated_Webcam_HD                                    | 7         | 2.19%   |
| Realtek Acer 640 x 480 laptop camera                            | 7         | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 7         | 2.19%   |
| Chicony VGA Webcam                                              | 5         | 1.57%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 4         | 1.25%   |
| Realtek Integrated Webcam                                       | 4         | 1.25%   |
| Quanta ACER HD User Facing                                      | 4         | 1.25%   |
| Lite-On Integrated Camera                                       | 4         | 1.25%   |
| IMC Networks Integrated Camera                                  | 4         | 1.25%   |
| Chicony Integrated Camera [ThinkPad]                            | 4         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 1.25%   |
| Bison Lenovo EasyCamera                                         | 4         | 1.25%   |
| Syntek Lenovo EasyCamera                                        | 3         | 0.94%   |
| Sunplus Integrated_Webcam_HD                                    | 3         | 0.94%   |
| Sunplus HD WebCam                                               | 3         | 0.94%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 3         | 0.94%   |
| Quanta HD User Facing                                           | 3         | 0.94%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 0.94%   |
| IMC Networks EasyCamera                                         | 3         | 0.94%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 3         | 0.94%   |
| Chicony TOSHIBA Web Camera - HD                                 | 3         | 0.94%   |
| Chicony Lenovo EasyCamera                                       | 3         | 0.94%   |
| Chicony HP Wide Vision HD Camera                                | 3         | 0.94%   |
| Chicony HP Truevision HD                                        | 3         | 0.94%   |
| Bison ThinkPad Integrated Camera                                | 3         | 0.94%   |
| Bison Integrated Camera                                         | 3         | 0.94%   |
| Bison EasyCamera                                                | 3         | 0.94%   |
| Apple Built-in iSight                                           | 3         | 0.94%   |
| ALi WebCam                                                      | 3         | 0.94%   |
| Syntek Integrated Camera                                        | 2         | 0.63%   |
| Syntek EasyCamera                                               | 2         | 0.63%   |
| Suyin HP Webcam                                                 | 2         | 0.63%   |
| Sunplus Integrated Webcam                                       | 2         | 0.63%   |
| Sunplus HP Truevision HD                                        | 2         | 0.63%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 0.63%   |

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
| 0     | 263       | 69.39%  |
| 1     | 96        | 25.33%  |
| 2     | 18        | 4.75%   |
| 3     | 2         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 32.84%  |
| Graphics card            | 34        | 25.37%  |
| Chipcard                 | 14        | 10.45%  |
| Net/wireless             | 11        | 8.21%   |
| Camera                   | 9         | 6.72%   |
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


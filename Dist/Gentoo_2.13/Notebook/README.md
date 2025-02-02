Gentoo 2.13 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.13.

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

Total: 186

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude D630               | [8af88f25f0](https://linux-hardware.org/?probe=8af88f25f0) | Nov 10, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [475563b8b4](https://linux-hardware.org/?probe=475563b8b4) | Aug 24, 2023 |
| HP            | EliteBook 8540w             | [c61948c95e](https://linux-hardware.org/?probe=c61948c95e) | Aug 23, 2023 |
| Apple         | MacBookPro11,1              | [a6ad62b671](https://linux-hardware.org/?probe=a6ad62b671) | Aug 15, 2023 |
| HP            | EliteBook 8540w             | [c24cfbc475](https://linux-hardware.org/?probe=c24cfbc475) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | [6077ff7606](https://linux-hardware.org/?probe=6077ff7606) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | [25f4c96f7b](https://linux-hardware.org/?probe=25f4c96f7b) | Aug 14, 2023 |
| Dell          | Latitude E7450              | [057d88b470](https://linux-hardware.org/?probe=057d88b470) | Aug 13, 2023 |
| HP            | EliteBook 8540w             | [3048a8eb60](https://linux-hardware.org/?probe=3048a8eb60) | Aug 12, 2023 |
| HP            | EliteBook 8540w             | [2df5a4bd58](https://linux-hardware.org/?probe=2df5a4bd58) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | [1bf7b69b0f](https://linux-hardware.org/?probe=1bf7b69b0f) | Aug 11, 2023 |
| Apple         | MacBookPro10,1              | [ed97e2ea3e](https://linux-hardware.org/?probe=ed97e2ea3e) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1d6bf926f6](https://linux-hardware.org/?probe=1d6bf926f6) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [41b594c2c7](https://linux-hardware.org/?probe=41b594c2c7) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [ae42e537d2](https://linux-hardware.org/?probe=ae42e537d2) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [51f2c38666](https://linux-hardware.org/?probe=51f2c38666) | Aug 05, 2023 |
| Alienware     | x17 R1                      | [bcdf52a63e](https://linux-hardware.org/?probe=bcdf52a63e) | Aug 01, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [451cbfaee5](https://linux-hardware.org/?probe=451cbfaee5) | Jul 29, 2023 |
| Apple         | MacBookPro12,1              | [bc3cb3cbfd](https://linux-hardware.org/?probe=bc3cb3cbfd) | Jul 28, 2023 |
| HP            | EliteBook 8540w             | [96a30f2f21](https://linux-hardware.org/?probe=96a30f2f21) | Jul 27, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [c73107bcac](https://linux-hardware.org/?probe=c73107bcac) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [1aeabb238f](https://linux-hardware.org/?probe=1aeabb238f) | Jul 25, 2023 |
| A-DATA Tec... | XENIA 15                    | [21edb88f94](https://linux-hardware.org/?probe=21edb88f94) | Jul 23, 2023 |
| HP            | 255 G6 Notebook PC          | [5c5147b82d](https://linux-hardware.org/?probe=5c5147b82d) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | [9c64742080](https://linux-hardware.org/?probe=9c64742080) | Jul 23, 2023 |
| HP            | ProBook 450 G5              | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| HP            | ProBook 440 G7              | [48cf81576d](https://linux-hardware.org/?probe=48cf81576d) | Jul 17, 2023 |
| HP            | EliteBook 8540w             | [b86a3c24df](https://linux-hardware.org/?probe=b86a3c24df) | Jul 16, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a5cdc8bb58](https://linux-hardware.org/?probe=a5cdc8bb58) | Jul 13, 2023 |
| HP            | EliteBook 8540w             | [26c6ceb0a6](https://linux-hardware.org/?probe=26c6ceb0a6) | Jul 13, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [2a37881afa](https://linux-hardware.org/?probe=2a37881afa) | Jul 11, 2023 |
| Apple         | MacBookPro11,1              | [7256e6a7b2](https://linux-hardware.org/?probe=7256e6a7b2) | Jul 11, 2023 |
| Dell          | XPS 15 7590                 | [ca41a9886a](https://linux-hardware.org/?probe=ca41a9886a) | Jul 09, 2023 |
| HP            | EliteBook 8540w             | [a760e46715](https://linux-hardware.org/?probe=a760e46715) | Jul 08, 2023 |
| Fujitsu       | LIFEBOOK U758               | [eaa8bbf9da](https://linux-hardware.org/?probe=eaa8bbf9da) | Jul 07, 2023 |
| HP            | EliteBook 8540w             | [1a53ce97b8](https://linux-hardware.org/?probe=1a53ce97b8) | Jul 07, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Jumper        | EZbook                      | [735e20e770](https://linux-hardware.org/?probe=735e20e770) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [68daff498d](https://linux-hardware.org/?probe=68daff498d) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [f587b9a46c](https://linux-hardware.org/?probe=f587b9a46c) | Jul 02, 2023 |
| HP            | EliteBook 8540w             | [465b44efff](https://linux-hardware.org/?probe=465b44efff) | Jul 01, 2023 |
| HP            | EliteBook 8540w             | [826e649d7a](https://linux-hardware.org/?probe=826e649d7a) | Jul 01, 2023 |
| Dell          | Inspiron 16 5625            | [bf36f89d32](https://linux-hardware.org/?probe=bf36f89d32) | Jul 01, 2023 |
| Dell          | Inspiron 16 5625            | [cbbe256fa2](https://linux-hardware.org/?probe=cbbe256fa2) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [2d16f5be74](https://linux-hardware.org/?probe=2d16f5be74) | Jun 29, 2023 |
| HP            | EliteBook 8540w             | [d675031e74](https://linux-hardware.org/?probe=d675031e74) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [178ed56625](https://linux-hardware.org/?probe=178ed56625) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | [37e828b0b6](https://linux-hardware.org/?probe=37e828b0b6) | Jun 24, 2023 |
| HP            | EliteBook 8540w             | [e1678729ff](https://linux-hardware.org/?probe=e1678729ff) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [094d8e8ecf](https://linux-hardware.org/?probe=094d8e8ecf) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | [a013e4866a](https://linux-hardware.org/?probe=a013e4866a) | Jun 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [12153cd235](https://linux-hardware.org/?probe=12153cd235) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | [6c766e53cb](https://linux-hardware.org/?probe=6c766e53cb) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | [91e2324734](https://linux-hardware.org/?probe=91e2324734) | Jun 20, 2023 |
| HP            | EliteBook 8540w             | [cd78108f1f](https://linux-hardware.org/?probe=cd78108f1f) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4d509da42f](https://linux-hardware.org/?probe=4d509da42f) | Jun 18, 2023 |
| HP            | ENVY m6                     | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP            | EliteBook 8540w             | [eb29f214f3](https://linux-hardware.org/?probe=eb29f214f3) | Jun 17, 2023 |
| Dell          | Precision 5530              | [29ec4c7e1d](https://linux-hardware.org/?probe=29ec4c7e1d) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [7e699d65f7](https://linux-hardware.org/?probe=7e699d65f7) | Jun 16, 2023 |
| Dell          | Precision 5530              | [cff5125fb6](https://linux-hardware.org/?probe=cff5125fb6) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | [a7728ed657](https://linux-hardware.org/?probe=a7728ed657) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | [03c8eed64b](https://linux-hardware.org/?probe=03c8eed64b) | Jun 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [ec46ef5f36](https://linux-hardware.org/?probe=ec46ef5f36) | Jun 15, 2023 |
| HP            | EliteBook 8540w             | [9b08f8189d](https://linux-hardware.org/?probe=9b08f8189d) | Jun 15, 2023 |
| Google        | Nightfury                   | [02badb166b](https://linux-hardware.org/?probe=02badb166b) | Jun 14, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [fc0318992c](https://linux-hardware.org/?probe=fc0318992c) | Jun 12, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [272de7ad6b](https://linux-hardware.org/?probe=272de7ad6b) | Jun 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Acer          | Swift SF314-511             | [60bf4b0442](https://linux-hardware.org/?probe=60bf4b0442) | Jun 05, 2023 |
| Dell          | Precision 5530              | [8b4e10b85a](https://linux-hardware.org/?probe=8b4e10b85a) | Jun 05, 2023 |
| Apple         | MacBookPro11,1              | [4192000802](https://linux-hardware.org/?probe=4192000802) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | [168fa7f541](https://linux-hardware.org/?probe=168fa7f541) | Jun 04, 2023 |
| Dell          | Precision 5530              | [151584f5aa](https://linux-hardware.org/?probe=151584f5aa) | Jun 02, 2023 |
| MSI           | GE76 Raider 11UH            | [64a17da7a3](https://linux-hardware.org/?probe=64a17da7a3) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [f4889c41be](https://linux-hardware.org/?probe=f4889c41be) | May 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [852932c13b](https://linux-hardware.org/?probe=852932c13b) | May 26, 2023 |
| HP            | Pavilion Notebook           | [08eec5e6ca](https://linux-hardware.org/?probe=08eec5e6ca) | May 26, 2023 |
| HP            | EliteBook 8570w             | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [2b6c863711](https://linux-hardware.org/?probe=2b6c863711) | May 15, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| Fujitsu       | CELSIUS H760                | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [4b3b94a776](https://linux-hardware.org/?probe=4b3b94a776) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [b1b041ac47](https://linux-hardware.org/?probe=b1b041ac47) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [870c85a9ac](https://linux-hardware.org/?probe=870c85a9ac) | May 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [847d86e573](https://linux-hardware.org/?probe=847d86e573) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Unknown       | Unknown                     | [82281ca3d5](https://linux-hardware.org/?probe=82281ca3d5) | May 06, 2023 |
| HUAWEI        | CREM-WXX9                   | [8ebf347e24](https://linux-hardware.org/?probe=8ebf347e24) | May 03, 2023 |
| Acer          | Swift SF314-41              | [520066013b](https://linux-hardware.org/?probe=520066013b) | May 03, 2023 |
| HP            | EliteBook 840 G3            | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [eeb1550b82](https://linux-hardware.org/?probe=eeb1550b82) | Apr 29, 2023 |
| HP            | G62                         | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| Dell          | Inspiron N5010              | [78b4f0cd2f](https://linux-hardware.org/?probe=78b4f0cd2f) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a16e963c10](https://linux-hardware.org/?probe=a16e963c10) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8bc0a29b23](https://linux-hardware.org/?probe=8bc0a29b23) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [fe2d361db9](https://linux-hardware.org/?probe=fe2d361db9) | Apr 25, 2023 |
| Dell          | Precision 7770              | [e9208415d5](https://linux-hardware.org/?probe=e9208415d5) | Apr 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [3d88744f22](https://linux-hardware.org/?probe=3d88744f22) | Apr 20, 2023 |
| Dell          | Latitude 7420               | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [21c928caeb](https://linux-hardware.org/?probe=21c928caeb) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [1c99075a1d](https://linux-hardware.org/?probe=1c99075a1d) | Apr 16, 2023 |
| Toshiba       | Satellite L850              | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| HP            | OMEN by Laptop              | [8a1ef40351](https://linux-hardware.org/?probe=8a1ef40351) | Apr 15, 2023 |
| Dell          | Inspiron 5415               | [83ec457b1d](https://linux-hardware.org/?probe=83ec457b1d) | Apr 14, 2023 |
| Dell          | Inspiron 5415               | [ccf77bf033](https://linux-hardware.org/?probe=ccf77bf033) | Apr 14, 2023 |
| MAXDATA       | o.max_5xs                   | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [2ecd45a19e](https://linux-hardware.org/?probe=2ecd45a19e) | Apr 13, 2023 |
| Acer          | Aspire one                  | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Dell          | Precision 7770              | [5091c10fa2](https://linux-hardware.org/?probe=5091c10fa2) | Apr 11, 2023 |
| HUAWEI        | KPL-W0X                     | [2cf04d07fb](https://linux-hardware.org/?probe=2cf04d07fb) | Apr 09, 2023 |
| HP            | Laptop 17-cp0xxx            | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | [c1f70c64ad](https://linux-hardware.org/?probe=c1f70c64ad) | Apr 01, 2023 |
| Dell          | XPS 13 9305                 | [9e60f40931](https://linux-hardware.org/?probe=9e60f40931) | Mar 30, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [85fb1a6778](https://linux-hardware.org/?probe=85fb1a6778) | Mar 26, 2023 |
| Acer          | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| HP            | EliteBook 745 G6            | [96fe7c184c](https://linux-hardware.org/?probe=96fe7c184c) | Mar 24, 2023 |
| Dell          | Latitude 7480               | [35b30305ec](https://linux-hardware.org/?probe=35b30305ec) | Mar 23, 2023 |
| HP            | EliteBook 745 G6            | [caf636a252](https://linux-hardware.org/?probe=caf636a252) | Mar 22, 2023 |
| Lenovo        | ThinkPad X200 7459L61       | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| HP            | EliteBook 8570p             | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| HP            | ZBook 17 G3                 | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [135aa0e418](https://linux-hardware.org/?probe=135aa0e418) | Mar 18, 2023 |
| Unknown       | Unknown                     | [d2af864fbb](https://linux-hardware.org/?probe=d2af864fbb) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Star Labs     | StarBook                    | [0b249699ba](https://linux-hardware.org/?probe=0b249699ba) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Dell          | Precision 7770              | [b13d6bed73](https://linux-hardware.org/?probe=b13d6bed73) | Mar 14, 2023 |
| Dell          | Precision 7770              | [38f84c4cfc](https://linux-hardware.org/?probe=38f84c4cfc) | Mar 14, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| HP            | Victus by Gaming Laptop ... | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| Dell          | Precision 7770              | [7d5207e1c1](https://linux-hardware.org/?probe=7d5207e1c1) | Mar 09, 2023 |
| Dell          | Latitude E6540              | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [ad6e1bbda5](https://linux-hardware.org/?probe=ad6e1bbda5) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e455dce9f3](https://linux-hardware.org/?probe=e455dce9f3) | Mar 07, 2023 |
| Dell          | Precision 7770              | [dea25f9c87](https://linux-hardware.org/?probe=dea25f9c87) | Mar 07, 2023 |
| Dell          | Precision 7770              | [aa1ff5150c](https://linux-hardware.org/?probe=aa1ff5150c) | Mar 06, 2023 |
| Acer          | Aspire 7750G                | [f0cde07b9f](https://linux-hardware.org/?probe=f0cde07b9f) | Mar 05, 2023 |
| MSI           | GS66 Stealth 10UE           | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| MSI           | GS66 Stealth 10UE           | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| realme        | RMNBXXXX                    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| Valve         | Jupiter                     | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| MSI           | GS66 Stealth 10UE           | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| HP            | Pavilion Notebook           | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| Dell          | Precision 7770              | [d8db6fecdd](https://linux-hardware.org/?probe=d8db6fecdd) | Feb 20, 2023 |
| Valve         | Jupiter                     | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | [6424058c59](https://linux-hardware.org/?probe=6424058c59) | Feb 19, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [48ca6dc3eb](https://linux-hardware.org/?probe=48ca6dc3eb) | Feb 19, 2023 |
| MSI           | GS66 Stealth 10UE           | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Timi          | RedmiBook Pro 15S           | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| Unknown       | Unknown                     | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| HP            | Pavilion Notebook           | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Dell          | Precision 7770              | [69b0982ad7](https://linux-hardware.org/?probe=69b0982ad7) | Feb 08, 2023 |
| Dell          | Precision 7770              | [28ba6f72d0](https://linux-hardware.org/?probe=28ba6f72d0) | Feb 07, 2023 |
| Dell          | Precision 7770              | [d05aabf7a5](https://linux-hardware.org/?probe=d05aabf7a5) | Feb 06, 2023 |
| Dell          | Precision 7770              | [20f6b87742](https://linux-hardware.org/?probe=20f6b87742) | Feb 03, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                              | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| 6.1.19-gentoo-x86_64                 | 7         | 6.09%   |
| 6.1.41-gentoo-dist                   | 5         | 4.35%   |
| 6.1.31-gentoo-dist                   | 5         | 4.35%   |
| 6.1.19-gentoo                        | 4         | 3.48%   |
| 6.1.12-gentoo                        | 4         | 3.48%   |
| 6.1.38-gentoo                        | 3         | 2.61%   |
| 6.1.31-gentoo-x86_64                 | 3         | 2.61%   |
| 6.1.12-gentoo-dist                   | 3         | 2.61%   |
| 6.4.0-gentoo                         | 2         | 1.74%   |
| 6.3.8-gentoo-dist                    | 2         | 1.74%   |
| 6.3.0-gentoo                         | 2         | 1.74%   |
| 6.2.8-gentoo-x86_64                  | 2         | 1.74%   |
| 6.1.9-gentoo-x86_64                  | 2         | 1.74%   |
| 6.1.38-gentoo-x86_64                 | 2         | 1.74%   |
| 6.1.24-gentoo-dist                   | 2         | 1.74%   |
| 6.1.22-gentoo-dist                   | 2         | 1.74%   |
| 6.1.19-gentoo-dist                   | 2         | 1.74%   |
| 6.1.12-gentoo-x86_64                 | 2         | 1.74%   |
| 6.1.10-gentoo-x86_64                 | 2         | 1.74%   |
| 6.4.1-gentoo-r1-x86_64               | 1         | 0.87%   |
| 6.4.1-gentoo-r1                      | 1         | 0.87%   |
| 6.3.8-gentoo                         | 1         | 0.87%   |
| 6.3.6-gentoo-dist                    | 1         | 0.87%   |
| 6.3.5-ivybridge-xanmod1              | 1         | 0.87%   |
| 6.3.4-gentoo-r1                      | 1         | 0.87%   |
| 6.3.4-gentoo                         | 1         | 0.87%   |
| 6.3.2-gentoo-dist                    | 1         | 0.87%   |
| 6.3.0                                | 1         | 0.87%   |
| 6.2.9-gentoo                         | 1         | 0.87%   |
| 6.2.8-gentoo                         | 1         | 0.87%   |
| 6.2.7-gentoo-dist                    | 1         | 0.87%   |
| 6.2.6-gentoo-dist                    | 1         | 0.87%   |
| 6.2.3-gentoo                         | 1         | 0.87%   |
| 6.2.2-gentoo-x86_64                  | 1         | 0.87%   |
| 6.2.2-gentoo                         | 1         | 0.87%   |
| 6.2.2-dist                           | 1         | 0.87%   |
| 6.2.14-gentoo-dist                   | 1         | 0.87%   |
| 6.2.12-gentoo-x86_642023-04-24--2109 | 1         | 0.87%   |
| 6.2.11-zen1                          | 1         | 0.87%   |
| 6.2.11-tkg-cfs                       | 1         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.19  | 15        | 13.04%  |
| 6.1.31  | 12        | 10.43%  |
| 6.1.12  | 10        | 8.7%    |
| 6.1.38  | 9         | 7.83%   |
| 6.1.41  | 6         | 5.22%   |
| 6.2.11  | 5         | 4.35%   |
| 6.3.8   | 3         | 2.61%   |
| 6.3.0   | 3         | 2.61%   |
| 6.2.8   | 3         | 2.61%   |
| 6.2.2   | 3         | 2.61%   |
| 6.1.9   | 3         | 2.61%   |
| 6.1.11  | 3         | 2.61%   |
| 6.1.10  | 3         | 2.61%   |
| 6.4.1   | 2         | 1.74%   |
| 6.4.0   | 2         | 1.74%   |
| 6.3.4   | 2         | 1.74%   |
| 6.1.28  | 2         | 1.74%   |
| 6.1.24  | 2         | 1.74%   |
| 6.1.22  | 2         | 1.74%   |
| 5.15.88 | 2         | 1.74%   |
| 5.15.80 | 2         | 1.74%   |
| 6.3.6   | 1         | 0.87%   |
| 6.3.5   | 1         | 0.87%   |
| 6.3.2   | 1         | 0.87%   |
| 6.2.9   | 1         | 0.87%   |
| 6.2.7   | 1         | 0.87%   |
| 6.2.6   | 1         | 0.87%   |
| 6.2.3   | 1         | 0.87%   |
| 6.2.14  | 1         | 0.87%   |
| 6.2.12  | 1         | 0.87%   |
| 6.2.10  | 1         | 0.87%   |
| 6.2.1   | 1         | 0.87%   |
| 6.2.0   | 1         | 0.87%   |
| 6.1.4   | 1         | 0.87%   |
| 6.1.30  | 1         | 0.87%   |
| 6.1.27  | 1         | 0.87%   |
| 6.1.2   | 1         | 0.87%   |
| 6.1.13  | 1         | 0.87%   |
| 5.15.94 | 1         | 0.87%   |
| 5.15.93 | 1         | 0.87%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 65        | 60.75%  |
| 6.2     | 19        | 17.76%  |
| 6.3     | 11        | 10.28%  |
| 5.15    | 8         | 7.48%   |
| 6.4     | 4         | 3.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 99        | 98.02%  |
| i686   | 2         | 1.98%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 30        | 29.13%  |
| Unknown   | 30        | 29.13%  |
| GNOME     | 13        | 12.62%  |
| XFCE      | 9         | 8.74%   |
| MATE      | 5         | 4.85%   |
| DWM       | 4         | 3.88%   |
| Trinity   | 2         | 1.94%   |
| i3        | 2         | 1.94%   |
| Xsession  | 1         | 0.97%   |
| sway      | 1         | 0.97%   |
| ratpoison | 1         | 0.97%   |
| LXQt      | 1         | 0.97%   |
| KDE       | 1         | 0.97%   |
| ICEWM     | 1         | 0.97%   |
| Hyprland  | 1         | 0.97%   |
| awesome   | 1         | 0.97%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 47        | 45.63%  |
| Wayland | 27        | 26.21%  |
| Unknown | 16        | 15.53%  |
| Tty     | 13        | 12.62%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 35        | 34.31%  |
| Unknown | 30        | 29.41%  |
| LightDM | 13        | 12.75%  |
| GDM     | 13        | 12.75%  |
| TDM     | 3         | 2.94%   |
| SLiM    | 3         | 2.94%   |
| GREETD  | 3         | 2.94%   |
| XDM     | 1         | 0.98%   |
| LXDM    | 1         | 0.98%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 40        | 39.22%  |
| Unknown | 14        | 13.73%  |
| en_GB   | 9         | 8.82%   |
| C.UTF8  | 9         | 8.82%   |
| ru_RU   | 5         | 4.9%    |
| fr_FR   | 4         | 3.92%   |
| de_DE   | 4         | 3.92%   |
| cs_CZ   | 4         | 3.92%   |
| C       | 3         | 2.94%   |
| it_IT   | 2         | 1.96%   |
| ro_RO   | 1         | 0.98%   |
| pt_BR   | 1         | 0.98%   |
| pl_PL   | 1         | 0.98%   |
| fr_CA   | 1         | 0.98%   |
| es_AR   | 1         | 0.98%   |
| en_AU   | 1         | 0.98%   |
| el_GR   | 1         | 0.98%   |
| ca_ES   | 1         | 0.98%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 83        | 82.18%  |
| BIOS | 18        | 17.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 61        | 60.4%   |
| Btrfs   | 33        | 32.67%  |
| F2fs    | 3         | 2.97%   |
| Xfs     | 2         | 1.98%   |
| XXXXXXX | 1         | 0.99%   |
| Jfs     | 1         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 88        | 86.27%  |
| MBR     | 12        | 11.76%  |
| Unknown | 2         | 1.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 74.51%  |
| Yes       | 26        | 25.49%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 66.67%  |
| Yes       | 34        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo            | 20        | 19.8%   |
| Hewlett-Packard   | 20        | 19.8%   |
| ASUSTek Computer  | 16        | 15.84%  |
| Dell              | 13        | 12.87%  |
| Acer              | 6         | 5.94%   |
| Apple             | 4         | 3.96%   |
| MSI               | 3         | 2.97%   |
| HUAWEI            | 3         | 2.97%   |
| Fujitsu           | 2         | 1.98%   |
| Unknown           | 2         | 1.98%   |
| Valve             | 1         | 0.99%   |
| TUXEDO            | 1         | 0.99%   |
| Toshiba           | 1         | 0.99%   |
| Timi              | 1         | 0.99%   |
| Star Labs         | 1         | 0.99%   |
| realme            | 1         | 0.99%   |
| Panasonic         | 1         | 0.99%   |
| MAXDATA           | 1         | 0.99%   |
| Jumper            | 1         | 0.99%   |
| Google            | 1         | 0.99%   |
| Alienware         | 1         | 0.99%   |
| A-DATA Technology | 1         | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| ASUS ROG Zephyrus G14 GA401II_GA401II            | 3         | 2.97%   |
| Lenovo IdeaPad 5 15ABA7 82SG                     | 2         | 1.98%   |
| Dell Precision 7770                              | 2         | 1.98%   |
| ASUS ROG Strix G513QY_G513QY                     | 2         | 1.98%   |
| Apple MacBookPro11,1                             | 2         | 1.98%   |
| Unknown                                          | 2         | 1.98%   |
| Valve Jupiter                                    | 1         | 0.99%   |
| TUXEDO Polaris AMD Gen3 (CZN)                    | 1         | 0.99%   |
| Toshiba Satellite L850                           | 1         | 0.99%   |
| Timi RedmiBook Pro 15S                           | 1         | 0.99%   |
| Star Labs StarBook                               | 1         | 0.99%   |
| realme RMNBXXXX                                  | 1         | 0.99%   |
| Panasonic CF-53ASCZGFG                           | 1         | 0.99%   |
| MSI Vector GP66 12UEO                            | 1         | 0.99%   |
| MSI GS66 Stealth 10UE                            | 1         | 0.99%   |
| MSI GE76 Raider 11UH                             | 1         | 0.99%   |
| MAXDATA o.max_5xs                                | 1         | 0.99%   |
| Lenovo ThinkPad X200 7459L61                     | 1         | 0.99%   |
| Lenovo ThinkPad X13 Gen 3 21CM0024US             | 1         | 0.99%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001JUS      | 1         | 0.99%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW        | 1         | 0.99%   |
| Lenovo ThinkPad T470p 20J7S25C00                 | 1         | 0.99%   |
| Lenovo ThinkPad T430 2344BZU                     | 1         | 0.99%   |
| Lenovo ThinkPad T16 Gen 1 21CH000FUS             | 1         | 0.99%   |
| Lenovo ThinkPad T14 Gen 2i 20W1SCBN00            | 1         | 0.99%   |
| Lenovo ThinkPad P51 20HHCTO1WW                   | 1         | 0.99%   |
| Lenovo ThinkPad P15 Gen 1 20SUS0S000             | 1         | 0.99%   |
| Lenovo ThinkPad P14s Gen 3 21J5001NUS            | 1         | 0.99%   |
| Lenovo ThinkPad P14s Gen 2a 21A0000JMH           | 1         | 0.99%   |
| Lenovo ThinkPad Edge E330 3354AMG                | 1         | 0.99%   |
| Lenovo ThinkPad E15 Gen 2 20T9S00K00             | 1         | 0.99%   |
| Lenovo Legion Y530-15ICH-1060 81LB               | 1         | 0.99%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF                 | 1         | 0.99%   |
| Lenovo Legion 5 15ACH6H 82JU                     | 1         | 0.99%   |
| Lenovo IdeaPad Yoga 13 20175                     | 1         | 0.99%   |
| Jumper EZbook                                    | 1         | 0.99%   |
| HUAWEI NBLK-WAX9X                                | 1         | 0.99%   |
| HUAWEI KPL-W0X                                   | 1         | 0.99%   |
| HUAWEI CREM-WXX9                                 | 1         | 0.99%   |
| HP ZBook Studio 16 inch G9 Mobile Workstation PC | 1         | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 14        | 13.86%  |
| ASUS ROG               | 8         | 7.92%   |
| HP EliteBook           | 5         | 4.95%   |
| Dell Latitude          | 4         | 3.96%   |
| Acer Aspire            | 4         | 3.96%   |
| Lenovo Legion          | 3         | 2.97%   |
| Lenovo IdeaPad         | 3         | 2.97%   |
| HP Pavilion            | 3         | 2.97%   |
| Dell XPS               | 3         | 2.97%   |
| Dell Precision         | 3         | 2.97%   |
| Dell Inspiron          | 3         | 2.97%   |
| HP ZBook               | 2         | 1.98%   |
| HP Victus              | 2         | 1.98%   |
| HP ProBook             | 2         | 1.98%   |
| HP Laptop              | 2         | 1.98%   |
| ASUS VivoBook          | 2         | 1.98%   |
| ASUS ASUS              | 2         | 1.98%   |
| Apple MacBookPro11     | 2         | 1.98%   |
| Acer Swift             | 2         | 1.98%   |
| Unknown                | 2         | 1.98%   |
| Valve Jupiter          | 1         | 0.99%   |
| TUXEDO Polaris         | 1         | 0.99%   |
| Toshiba Satellite      | 1         | 0.99%   |
| Timi RedmiBook         | 1         | 0.99%   |
| Star Labs StarBook     | 1         | 0.99%   |
| realme RMNBXXXX        | 1         | 0.99%   |
| Panasonic CF-53ASCZGFG | 1         | 0.99%   |
| MSI Vector             | 1         | 0.99%   |
| MSI GS66               | 1         | 0.99%   |
| MSI GE76               | 1         | 0.99%   |
| MAXDATA o.max          | 1         | 0.99%   |
| Jumper EZbook          | 1         | 0.99%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.99%   |
| HUAWEI KPL-W0X         | 1         | 0.99%   |
| HUAWEI CREM-WXX9       | 1         | 0.99%   |
| HP OMEN                | 1         | 0.99%   |
| HP G62                 | 1         | 0.99%   |
| HP ENVY                | 1         | 0.99%   |
| HP 255                 | 1         | 0.99%   |
| Google Nightfury       | 1         | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 23        | 22.77%  |
| 2022 | 17        | 16.83%  |
| 2019 | 10        | 9.9%    |
| 2018 | 9         | 8.91%   |
| 2020 | 8         | 7.92%   |
| 2012 | 8         | 7.92%   |
| 2017 | 5         | 4.95%   |
| 2010 | 4         | 3.96%   |
| 2016 | 3         | 2.97%   |
| 2015 | 3         | 2.97%   |
| 2014 | 3         | 2.97%   |
| 2023 | 2         | 1.98%   |
| 2011 | 2         | 1.98%   |
| 2008 | 2         | 1.98%   |
| 2013 | 1         | 0.99%   |
| 2007 | 1         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 101       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 101       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 98        | 97.03%  |
| Yes  | 3         | 2.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 26        | 25.49%  |
| 4.01-8.0    | 21        | 20.59%  |
| 32.01-64.0  | 19        | 18.63%  |
| 16.01-24.0  | 19        | 18.63%  |
| 24.01-32.0  | 6         | 5.88%   |
| 64.01-256.0 | 5         | 4.9%    |
| 3.01-4.0    | 4         | 3.92%   |
| 2.01-3.0    | 1         | 0.98%   |
| 0.51-1.0    | 1         | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 23        | 20.72%  |
| 2.01-3.0   | 21        | 18.92%  |
| 4.01-8.0   | 17        | 15.32%  |
| 0.51-1.0   | 16        | 14.41%  |
| 3.01-4.0   | 13        | 11.71%  |
| 0.01-0.5   | 11        | 9.91%   |
| 8.01-16.0  | 9         | 8.11%   |
| 32.01-64.0 | 1         | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 69        | 66.99%  |
| 2      | 29        | 28.16%  |
| 3      | 4         | 3.88%   |
| 4      | 1         | 0.97%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 86.14%  |
| Yes       | 14        | 13.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 79.41%  |
| No        | 21        | 20.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 91.09%  |
| No        | 9         | 8.91%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 27        | 26.47%  |
| Russia      | 10        | 9.8%    |
| France      | 6         | 5.88%   |
| Canada      | 6         | 5.88%   |
| UK          | 5         | 4.9%    |
| Spain       | 5         | 4.9%    |
| Germany     | 5         | 4.9%    |
| Slovakia    | 3         | 2.94%   |
| Poland      | 3         | 2.94%   |
| Italy       | 3         | 2.94%   |
| Czechia     | 3         | 2.94%   |
| Turkey      | 2         | 1.96%   |
| Romania     | 2         | 1.96%   |
| Netherlands | 2         | 1.96%   |
| China       | 2         | 1.96%   |
| Brazil      | 2         | 1.96%   |
| Belgium     | 2         | 1.96%   |
| Portugal    | 1         | 0.98%   |
| Norway      | 1         | 0.98%   |
| New Zealand | 1         | 0.98%   |
| Lithuania   | 1         | 0.98%   |
| Iran        | 1         | 0.98%   |
| Indonesia   | 1         | 0.98%   |
| Iceland     | 1         | 0.98%   |
| Hungary     | 1         | 0.98%   |
| Hong Kong   | 1         | 0.98%   |
| Greece      | 1         | 0.98%   |
| Belarus     | 1         | 0.98%   |
| Australia   | 1         | 0.98%   |
| Argentina   | 1         | 0.98%   |
| Algeria     | 1         | 0.98%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| St Petersburg | 3         | 2.86%   |
| Berlin        | 3         | 2.86%   |
| Taganrog      | 2         | 1.9%    |
| Sun Prairie   | 2         | 1.9%    |
| Šlapanice    | 2         | 1.9%    |
| Oviedo        | 2         | 1.9%    |
| Milan         | 2         | 1.9%    |
| Kippens       | 2         | 1.9%    |
| Bratislava    | 2         | 1.9%    |
| Barcelona     | 2         | 1.9%    |
| Wlodawa       | 1         | 0.95%   |
| Whitby        | 1         | 0.95%   |
| Wandsworth    | 1         | 0.95%   |
| Vilnius       | 1         | 0.95%   |
| Urbana        | 1         | 0.95%   |
| Ulm           | 1         | 0.95%   |
| Trakai        | 1         | 0.95%   |
| Toronto       | 1         | 0.95%   |
| Thousand Oaks | 1         | 0.95%   |
| Târgu Mureş | 1         | 0.95%   |
| Shrewsbury    | 1         | 0.95%   |
| Shenzhen      | 1         | 0.95%   |
| Seattle       | 1         | 0.95%   |
| Sao Paulo     | 1         | 0.95%   |
| Rome          | 1         | 0.95%   |
| Roland        | 1         | 0.95%   |
| Reykjavik     | 1         | 0.95%   |
| Rapid City    | 1         | 0.95%   |
| Québec       | 1         | 0.95%   |
| Prague        | 1         | 0.95%   |
| Pittsburgh    | 1         | 0.95%   |
| Piraeus       | 1         | 0.95%   |
| Paris         | 1         | 0.95%   |
| Oslo          | 1         | 0.95%   |
| Omsk          | 1         | 0.95%   |
| Omaha         | 1         | 0.95%   |
| Nea Artaki    | 1         | 0.95%   |
| Nampa         | 1         | 0.95%   |
| Moscow        | 1         | 0.95%   |
| Monroe        | 1         | 0.95%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 33        | 49     | 25.78%  |
| Sandisk                     | 16        | 20     | 12.5%   |
| Seagate                     | 9         | 10     | 7.03%   |
| Intel                       | 9         | 12     | 7.03%   |
| SK hynix                    | 8         | 9      | 6.25%   |
| Micron Technology           | 6         | 6      | 4.69%   |
| Unknown                     | 5         | 6      | 3.91%   |
| WDC                         | 3         | 4      | 2.34%   |
| Phison Electronics          | 3         | 4      | 2.34%   |
| KIOXIA                      | 3         | 4      | 2.34%   |
| Kingston Technology Company | 3         | 3      | 2.34%   |
| HGST                        | 3         | 3      | 2.34%   |
| Apple                       | 3         | 3      | 2.34%   |
| Toshiba                     | 2         | 2      | 1.56%   |
| Micron/Crucial Technology   | 2         | 4      | 1.56%   |
| Kingston                    | 2         | 2      | 1.56%   |
| GOODRAM                     | 2         | 2      | 1.56%   |
| Crucial                     | 2         | 2      | 1.56%   |
| China                       | 2         | 5      | 1.56%   |
| A-DATA Technology           | 2         | 2      | 1.56%   |
| XPG                         | 1         | 1      | 0.78%   |
| Teleplan                    | 1         | 3      | 0.78%   |
| PNY                         | 1         | 2      | 0.78%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.78%   |
| Lexar                       | 1         | 1      | 0.78%   |
| Intenso                     | 1         | 1      | 0.78%   |
| Hitachi                     | 1         | 1      | 0.78%   |
| Dogfish                     | 1         | 1      | 0.78%   |
| ASMT                        | 1         | 2      | 0.78%   |
| ADATA Technology            | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 12        | 8.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 12        | 8.96%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 5         | 3.73%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 4         | 2.99%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 2.24%   |
| Samsung SSD 980 1TB                                 | 3         | 2.24%   |
| Unknown MMC Card  128GB                             | 2         | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.49%   |
| Micron MTFDKBA512TFH 512GB                          | 2         | 1.49%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 2         | 1.49%   |
| Intel SSDPEKNU512GZ 512GB                           | 2         | 1.49%   |
| HGST HTS725050A7E630 500GB                          | 2         | 1.49%   |
| China SSD 1TB                                       | 2         | 1.49%   |
| XPG GAMMIX S70 1TB                                  | 1         | 0.75%   |
| WDC WDS500G1B0B-00AS40 500GB SSD                    | 1         | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.75%   |
| WDC WD20 SPZX-22CRAT0 2TB                           | 1         | 0.75%   |
| Unknown NVMe SSD Drive 1TB                          | 1         | 0.75%   |
| Unknown MMC Card  8GB                               | 1         | 0.75%   |
| Unknown MMC Card  512GB                             | 1         | 0.75%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 0.75%   |
| Toshiba MK5056GSY 500GB                             | 1         | 0.75%   |
| Teleplan TP1000G 1TB                                | 1         | 0.75%   |
| SK hynix SKHynix_HFS001TDE9X081N 1024GB             | 1         | 0.75%   |
| SK hynix SC311 SATA 128GB SSD                       | 1         | 0.75%   |
| SK hynix PC801 NVMe 1TB                             | 1         | 0.75%   |
| SK hynix PC711 NVMe 1TB                             | 1         | 0.75%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 0.75%   |
| SK hynix HFM001TD3JX013N 1024GB                     | 1         | 0.75%   |
| SK hynix BC711 NVMe 512GB                           | 1         | 0.75%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 0.75%   |
| Seagate ST500LX025-1U717D 500GB                     | 1         | 0.75%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 0.75%   |
| Seagate ST2000LX001-1RG174 2TB                      | 1         | 0.75%   |
| Seagate ST2000LM015-2E8174 2TB                      | 1         | 0.75%   |
| Sandisk WD_BLACK SN850X 2000GB                      | 1         | 0.75%   |
| Sandisk WD_BLACK SN850X 1000GB                      | 1         | 0.75%   |
| Sandisk WDC PC SN530 SDBPTPZ-512G-1002 512GB        | 1         | 0.75%   |
| Sandisk WD PC SN735 SDBPNHH-512G-1002 512GB         | 1         | 0.75%   |
| SanDisk SDSSDHII960G 960GB                          | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 9         | 10     | 50%     |
| HGST     | 3         | 3      | 16.67%  |
| Toshiba  | 2         | 2      | 11.11%  |
| WDC      | 1         | 1      | 5.56%   |
| Teleplan | 1         | 3      | 5.56%   |
| Hitachi  | 1         | 1      | 5.56%   |
| ASMT     | 1         | 2      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 24.24%  |
| SanDisk             | 3         | 4      | 9.09%   |
| Apple               | 3         | 3      | 9.09%   |
| WDC                 | 2         | 3      | 6.06%   |
| Intel               | 2         | 2      | 6.06%   |
| GOODRAM             | 2         | 2      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| China               | 2         | 5      | 6.06%   |
| A-DATA Technology   | 2         | 2      | 6.06%   |
| SK hynix            | 1         | 1      | 3.03%   |
| PNY                 | 1         | 2      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Lexar               | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| Dogfish             | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 66        | 99     | 55.46%  |
| SSD  | 31        | 40     | 26.05%  |
| HDD  | 18        | 22     | 15.13%  |
| MMC  | 4         | 5      | 3.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 66        | 99     | 55.93%  |
| SATA | 45        | 58     | 38.14%  |
| MMC  | 4         | 5      | 3.39%   |
| SAS  | 3         | 4      | 2.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 32     | 56%     |
| 0.51-1.0   | 16        | 23     | 32%     |
| 1.01-2.0   | 4         | 4      | 8%      |
| 3.01-4.0   | 2         | 3      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 26        | 25.24%  |
| 501-1000       | 22        | 21.36%  |
| 101-250        | 21        | 20.39%  |
| 1001-2000      | 10        | 9.71%   |
| More than 3000 | 7         | 6.8%    |
| 2001-3000      | 5         | 4.85%   |
| 51-100         | 5         | 4.85%   |
| 1-20           | 4         | 3.88%   |
| Unknown        | 2         | 1.94%   |
| 21-50          | 1         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 22.73%  |
| 21-50          | 21        | 19.09%  |
| 101-250        | 17        | 15.45%  |
| 251-500        | 15        | 13.64%  |
| 51-100         | 14        | 12.73%  |
| 501-1000       | 9         | 8.18%   |
| 1001-2000      | 5         | 4.55%   |
| More than 3000 | 2         | 1.82%   |
| Unknown        | 2         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 3      | 22.22%  |
| HGST HTS725050A7E630 500GB           | 2         | 2      | 22.22%  |
| Toshiba MK5056GSY 500GB              | 1         | 1      | 11.11%  |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 2      | 11.11%  |
| Intel SSDSC2BF180A5L 180GB           | 1         | 1      | 11.11%  |
| Intel SSDSA2M080G2GC 80GB            | 1         | 1      | 11.11%  |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| HGST     | 3         | 3      | 33.33%  |
| Seagate  | 2         | 3      | 22.22%  |
| Intel    | 2         | 2      | 22.22%  |
| Toshiba  | 1         | 1      | 11.11%  |
| SK hynix | 1         | 2      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 3         | 3      | 50%     |
| Seagate | 2         | 3      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 66.67%  |
| SSD  | 2         | 2      | 22.22%  |
| NVMe | 1         | 2      | 11.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 88        | 136    | 80%     |
| Detected | 12        | 18     | 10.91%  |
| Malfunc  | 9         | 11     | 8.18%   |
| Failed   | 1         | 1      | 0.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 51        | 37.23%  |
| Samsung Electronics         | 28        | 20.44%  |
| AMD                         | 17        | 12.41%  |
| SanDisk                     | 13        | 9.49%   |
| SK hynix                    | 7         | 5.11%   |
| Micron Technology           | 5         | 3.65%   |
| Kingston Technology Company | 4         | 2.92%   |
| Phison Electronics          | 3         | 2.19%   |
| KIOXIA                      | 3         | 2.19%   |
| Micron/Crucial Technology   | 2         | 1.46%   |
| INNOGRIT                    | 2         | 1.46%   |
| MAXIO Technology (Hangzhou) | 1         | 0.73%   |
| ADATA Technology            | 1         | 0.73%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 16        | 10.81%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 12        | 8.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 12        | 8.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 8         | 5.41%   |
| Intel Volume Management Device NVMe RAID Controller                          | 6         | 4.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 6         | 4.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 5         | 3.38%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 5         | 3.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 5         | 3.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 5         | 3.38%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 4         | 2.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 4         | 2.7%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 3         | 2.03%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 3         | 2.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 3         | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 2.03%   |
| Sandisk WD Black SN850X NVMe SSD                                             | 2         | 1.35%   |
| Micron 3400 NVMe SSD [Hendrix]                                               | 2         | 1.35%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 2         | 1.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 1.35%   |
| Intel Tiger Lake-LP SATA Controller                                          | 2         | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 1.35%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 2         | 1.35%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 1.35%   |
| INNOGRIT NVMe SSD Controller IG5236                                          | 2         | 1.35%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                           | 1         | 0.68%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 0.68%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                        | 1         | 0.68%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                        | 1         | 0.68%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 1         | 0.68%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                           | 1         | 0.68%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 0.68%   |
| Phison E8 PCIe3 NVMe Controller                                              | 1         | 0.68%   |
| Phison E12 NVMe Controller                                                   | 1         | 0.68%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)         | 1         | 0.68%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                    | 1         | 0.68%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                 | 1         | 0.68%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                   | 1         | 0.68%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 0.68%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                       | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 66        | 48.53%  |
| SATA | 57        | 41.91%  |
| RAID | 12        | 8.82%   |
| IDE  | 1         | 0.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 70.3%   |
| AMD    | 30        | 29.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                 | 5         | 4.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 4.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.94%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 2.94%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 3         | 2.94%   |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 3         | 2.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.96%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.96%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.96%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 1.96%   |
| Intel 12th Gen Core i7-12850HX                | 2         | 1.96%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.96%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.96%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics    | 2         | 1.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.96%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.98%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.98%   |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 0.98%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.98%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.98%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.98%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.98%   |
| Intel Core i7-5557U CPU @ 3.10GHz             | 1         | 0.98%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.98%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.98%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.98%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 0.98%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.98%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.98%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.98%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.98%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.98%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 0.98%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.98%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 22        | 21.78%  |
| Other                | 21        | 20.79%  |
| Intel Core i5        | 16        | 15.84%  |
| AMD Ryzen 7          | 14        | 13.86%  |
| AMD Ryzen 5          | 6         | 5.94%   |
| Intel Core i3        | 4         | 3.96%   |
| AMD Ryzen 7 PRO      | 4         | 3.96%   |
| Intel Core i9        | 2         | 1.98%   |
| AMD Ryzen 9          | 2         | 1.98%   |
| Intel Xeon           | 1         | 0.99%   |
| Intel Pentium Silver | 1         | 0.99%   |
| Intel Pentium        | 1         | 0.99%   |
| Intel Core Duo       | 1         | 0.99%   |
| Intel Core 2 Duo     | 1         | 0.99%   |
| Intel Celeron        | 1         | 0.99%   |
| Intel Atom           | 1         | 0.99%   |
| AMD Ryzen 5 PRO      | 1         | 0.99%   |
| AMD Athlon II        | 1         | 0.99%   |
| AMD A6               | 1         | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 27        | 26.73%  |
| 2      | 27        | 26.73%  |
| 8      | 24        | 23.76%  |
| 6      | 14        | 13.86%  |
| 14     | 5         | 4.95%   |
| 16     | 2         | 1.98%   |
| 12     | 1         | 0.99%   |
| 1      | 1         | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 93        | 92.08%  |
| 1      | 8         | 7.92%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 98.02%  |
| 32-bit         | 2         | 1.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 29.52%  |
| 0x0a50000c | 9         | 8.57%   |
| 0x806c1    | 8         | 7.62%   |
| 0x906ea    | 6         | 5.71%   |
| 0xa0652    | 3         | 2.86%   |
| 0x906e9    | 3         | 2.86%   |
| 0x806d1    | 3         | 2.86%   |
| 0x306d4    | 3         | 2.86%   |
| 0x306a9    | 3         | 2.86%   |
| 0x206a7    | 3         | 2.86%   |
| 0x08600104 | 3         | 2.86%   |
| 0x906a3    | 2         | 1.9%    |
| 0x90672    | 2         | 1.9%    |
| 0x806ec    | 2         | 1.9%    |
| 0x806ea    | 2         | 1.9%    |
| 0x406e3    | 2         | 1.9%    |
| 0x40651    | 2         | 1.9%    |
| 0x20655    | 2         | 1.9%    |
| 0x0a50000d | 2         | 1.9%    |
| 0x0a404102 | 2         | 1.9%    |
| 0x08608103 | 2         | 1.9%    |
| 0x08108109 | 2         | 1.9%    |
| 0x806e9    | 1         | 0.95%   |
| 0x506e3    | 1         | 0.95%   |
| 0x406c4    | 1         | 0.95%   |
| 0x08900201 | 1         | 0.95%   |
| 0x08701021 | 1         | 0.95%   |
| 0x08600106 | 1         | 0.95%   |
| 0x08600103 | 1         | 0.95%   |
| 0x08101007 | 1         | 0.95%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 16        | 15.84%  |
| Zen 3            | 12        | 11.88%  |
| TigerLake        | 8         | 7.92%   |
| Alderlake Hybrid | 8         | 7.92%   |
| Unknown          | 8         | 7.92%   |
| SandyBridge      | 6         | 5.94%   |
| IvyBridge        | 6         | 5.94%   |
| Zen 2            | 5         | 4.95%   |
| Skylake          | 4         | 3.96%   |
| Icelake          | 4         | 3.96%   |
| Haswell          | 4         | 3.96%   |
| CometLake        | 4         | 3.96%   |
| Broadwell        | 4         | 3.96%   |
| Zen+             | 3         | 2.97%   |
| Westmere         | 2         | 1.98%   |
| Zen              | 1         | 0.99%   |
| Silvermont       | 1         | 0.99%   |
| Penryn           | 1         | 0.99%   |
| P6               | 1         | 0.99%   |
| K10              | 1         | 0.99%   |
| Excavator        | 1         | 0.99%   |
| Bonnell          | 1         | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 44.29%  |
| Nvidia | 43        | 30.71%  |
| AMD    | 35        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 5.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 4.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 6         | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 4.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 5         | 3.4%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 5         | 3.4%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 5         | 3.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 4         | 2.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 2.72%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 2.72%   |
| AMD Rembrandt [Radeon 680M]                                                   | 4         | 2.72%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                    | 3         | 2.04%   |
| Intel HD Graphics 5500                                                        | 3         | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 2.04%   |
| AMD Barcelo                                                                   | 3         | 2.04%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 1.36%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 1.36%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 2         | 1.36%   |
| Nvidia GA104GLM [RTX A3000 12GB Laptop GPU]                                   | 2         | 1.36%   |
| Intel UHD Graphics 620                                                        | 2         | 1.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.36%   |
| Intel HD Graphics 630                                                         | 2         | 1.36%   |
| Intel HD Graphics 530                                                         | 2         | 1.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.36%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 2         | 1.36%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 2         | 1.36%   |
| AMD Lucienne                                                                  | 2         | 1.36%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.68%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.68%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                         | 1         | 0.68%   |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.68%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 0.68%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.68%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                      | 1         | 0.68%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 0.68%   |
| Nvidia GM204GLM [Quadro M3000M]                                               | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 30        | 29.41%  |
| 1 x Intel      | 25        | 24.51%  |
| 1 x AMD        | 22        | 21.57%  |
| 1 x Nvidia     | 9         | 8.82%   |
| AMD + Nvidia   | 5         | 4.9%    |
| 2 x AMD        | 4         | 3.92%   |
| Intel + AMD    | 4         | 3.92%   |
| 2 x Intel      | 3         | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 77        | 76.24%  |
| Proprietary | 22        | 21.78%  |
| Unknown     | 2         | 1.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 55.34%  |
| 1.01-2.0   | 10        | 9.71%   |
| 3.01-4.0   | 9         | 8.74%   |
| 0.51-1.0   | 9         | 8.74%   |
| 0.01-0.5   | 9         | 8.74%   |
| 8.01-16.0  | 4         | 3.88%   |
| 7.01-8.0   | 3         | 2.91%   |
| 5.01-6.0   | 2         | 1.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 19.49%  |
| Chimei Innolux          | 18        | 15.25%  |
| BOE                     | 17        | 14.41%  |
| LG Display              | 10        | 8.47%   |
| Samsung Electronics     | 6         | 5.08%   |
| Sharp                   | 4         | 3.39%   |
| Dell                    | 4         | 3.39%   |
| Apple                   | 4         | 3.39%   |
| PANDA                   | 3         | 2.54%   |
| Goldstar                | 3         | 2.54%   |
| ASUSTek Computer        | 3         | 2.54%   |
| Philips                 | 2         | 1.69%   |
| Eizo                    | 2         | 1.69%   |
| CSO                     | 2         | 1.69%   |
| Chi Mei Optoelectronics | 2         | 1.69%   |
| BOE Technology Group    | 2         | 1.69%   |
| Valve                   | 1         | 0.85%   |
| TMX                     | 1         | 0.85%   |
| Sony                    | 1         | 0.85%   |
| MSI                     | 1         | 0.85%   |
| Mi                      | 1         | 0.85%   |
| Lenovo                  | 1         | 0.85%   |
| InfoVision              | 1         | 0.85%   |
| Hewlett-Packard         | 1         | 0.85%   |
| ELSA                    | 1         | 0.85%   |
| CTO                     | 1         | 0.85%   |
| BenQ                    | 1         | 0.85%   |
| AOC                     | 1         | 0.85%   |
| Unknown                 | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 2         | 1.65%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 1.65%   |
| BOE Technology Group LCD Monitor 1920x1080                            | 2         | 1.65%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 2         | 1.65%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 2         | 1.65%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 1.65%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch          | 2         | 1.65%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.83%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                 | 1         | 0.83%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                         | 1         | 0.83%   |
| Sharp LQ173M1JW03 SHP14DC 1920x1080 382x215mm 17.3-inch               | 1         | 0.83%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 0.83%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.83%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 0.83%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1         | 0.83%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch               | 1         | 0.83%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| MSI G273Q MSI3CA8 3840x2160 596x335mm 26.9-inch                       | 1         | 0.83%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                | 1         | 0.83%   |
| LG Display LCD Monitor LGD06D6 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05CF 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD058C 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 0.83%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 0.83%   |
| InfoVision LCD Monitor IVO8C69 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 337x270mm 17.0-inch            | 1         | 0.83%   |
| Goldstar ULTRAFINE GSM5BC2 3840x2160 697x392mm 31.5-inch              | 1         | 0.83%   |
| Goldstar LG ULTRAWIDE GSM5A6E 2560x1080 670x280mm 28.6-inch           | 1         | 0.83%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1         | 0.83%   |
| ELSA EL271Q ELS0270 1920x1080 597x336mm 27.0-inch                     | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 60        | 54.05%  |
| 2560x1440 (QHD)   | 9         | 8.11%   |
| 1366x768 (WXGA)   | 9         | 8.11%   |
| 3840x2160 (4K)    | 7         | 6.31%   |
| 2560x1600         | 6         | 5.41%   |
| 1600x900 (HD+)    | 4         | 3.6%    |
| 1920x1200 (WUXGA) | 3         | 2.7%    |
| 800x1280          | 1         | 0.9%    |
| 3840x2400         | 1         | 0.9%    |
| 3456x2160         | 1         | 0.9%    |
| 3440x1440         | 1         | 0.9%    |
| 3200x2000         | 1         | 0.9%    |
| 2880x1800         | 1         | 0.9%    |
| 2560x1080         | 1         | 0.9%    |
| 2520x1680         | 1         | 0.9%    |
| 2160x1440         | 1         | 0.9%    |
| 1920x540          | 1         | 0.9%    |
| 1280x800 (WXGA)   | 1         | 0.9%    |
| 1280x1024 (SXGA)  | 1         | 0.9%    |
| 1024x600          | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 41        | 34.45%  |
| 14      | 16        | 13.45%  |
| 17      | 14        | 11.76%  |
| 13      | 14        | 11.76%  |
| 27      | 7         | 5.88%   |
| 16      | 6         | 5.04%   |
| 24      | 4         | 3.36%   |
| 23      | 4         | 3.36%   |
| Unknown | 3         | 2.52%   |
| 34      | 1         | 0.84%   |
| 31      | 1         | 0.84%   |
| 28      | 1         | 0.84%   |
| 25      | 1         | 0.84%   |
| 21      | 1         | 0.84%   |
| 18      | 1         | 0.84%   |
| 12      | 1         | 0.84%   |
| 10      | 1         | 0.84%   |
| 8       | 1         | 0.84%   |
| 7       | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 58.12%  |
| 501-600     | 14        | 11.97%  |
| 351-400     | 14        | 11.97%  |
| 201-300     | 11        | 9.4%    |
| Unknown     | 3         | 2.56%   |
| 601-700     | 2         | 1.71%   |
| 401-500     | 2         | 1.71%   |
| 701-800     | 1         | 0.85%   |
| 101-200     | 1         | 0.85%   |
| 1-100       | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 81        | 77.88%  |
| 16/10   | 13        | 12.5%   |
| 3/2     | 2         | 1.92%   |
| 21/9    | 2         | 1.92%   |
| Unknown | 2         | 1.92%   |
| 5/4     | 1         | 0.96%   |
| 32/9    | 1         | 0.96%   |
| 0.67    | 1         | 0.96%   |
| 0.62    | 1         | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 42        | 35.29%  |
| 81-90          | 23        | 19.33%  |
| 121-130        | 13        | 10.92%  |
| 201-250        | 8         | 6.72%   |
| 71-80          | 7         | 5.88%   |
| 301-350        | 7         | 5.88%   |
| 111-120        | 5         | 4.2%    |
| Unknown        | 3         | 2.52%   |
| 351-500        | 2         | 1.68%   |
| 1-40           | 2         | 1.68%   |
| 251-300        | 2         | 1.68%   |
| 141-150        | 2         | 1.68%   |
| 61-70          | 1         | 0.84%   |
| 41-50          | 1         | 0.84%   |
| 91-100         | 1         | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 48.72%  |
| 161-240       | 19        | 16.24%  |
| 101-120       | 16        | 13.68%  |
| 51-100        | 14        | 11.97%  |
| More than 240 | 8         | 6.84%   |
| Unknown       | 3         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 81        | 78.64%  |
| 2     | 16        | 15.53%  |
| 3     | 4         | 3.88%   |
| 0     | 2         | 1.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 40.37%  |
| Realtek Semiconductor | 53        | 32.92%  |
| MediaTek              | 7         | 4.35%   |
| Qualcomm Atheros      | 6         | 3.73%   |
| Broadcom              | 6         | 3.73%   |
| Xiaomi                | 4         | 2.48%   |
| Broadcom Limited      | 4         | 2.48%   |
| Qualcomm              | 3         | 1.86%   |
| ASIX Electronics      | 3         | 1.86%   |
| Sierra Wireless       | 2         | 1.24%   |
| TP-Link               | 1         | 0.62%   |
| Samsung Electronics   | 1         | 0.62%   |
| Lenovo                | 1         | 0.62%   |
| ICS Advent            | 1         | 0.62%   |
| Edimax Technology     | 1         | 0.62%   |
| Dell                  | 1         | 0.62%   |
| ASUSTek Computer      | 1         | 0.62%   |
| Arduino SA            | 1         | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 34        | 17.44%  |
| Intel Wi-Fi 6 AX200                                                  | 13        | 6.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 6         | 3.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 6         | 3.08%   |
| Intel Wireless 8265 / 8275                                           | 6         | 3.08%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 3.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 5         | 2.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 4         | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 4         | 2.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 4         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 4         | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 4         | 2.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 3         | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                    | 3         | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3         | 1.54%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 3         | 1.54%   |
| Intel Wireless 8260                                                  | 3         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 1.54%   |
| Intel Centrino Advanced-N 6235                                       | 3         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 1.54%   |
| ASIX AX88179 Gigabit Ethernet                                        | 3         | 1.54%   |
| Sierra Wireless EM7305 Modem                                         | 2         | 1.03%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 2         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.03%   |
| Realtek Killer E3000 2.5GbE Controller                               | 2         | 1.03%   |
| Intel Wireless 7265                                                  | 2         | 1.03%   |
| Intel Ethernet Connection (5) I219-LM                                | 2         | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                                | 2         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                                | 2         | 1.03%   |
| Intel Ethernet Connection (17) I219-LM                               | 2         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.03%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2         | 1.03%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.03%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]      | 1         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 0.51%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                               | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 59.43%  |
| Realtek Semiconductor | 15        | 14.15%  |
| MediaTek              | 7         | 6.6%    |
| Qualcomm Atheros      | 5         | 4.72%   |
| Broadcom Limited      | 4         | 3.77%   |
| Broadcom              | 4         | 3.77%   |
| Qualcomm              | 3         | 2.83%   |
| Sierra Wireless       | 2         | 1.89%   |
| Edimax Technology     | 1         | 0.94%   |
| Dell                  | 1         | 0.94%   |
| ASUSTek Computer      | 1         | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 13        | 12.26%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 5.66%   |
| Intel Wireless 8265 / 8275                                              | 6         | 5.66%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 5.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 4.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 3.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 3.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 2.83%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 2.83%   |
| Intel Wireless 8260                                                     | 3         | 2.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 2.83%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.83%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 1.89%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.89%   |
| Intel Wireless 7265                                                     | 2         | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.89%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.89%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 1.89%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 2         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.89%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.94%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                  | 1         | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.94%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.94%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.94%   |
| Intel Wireless 7260                                                     | 1         | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.94%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.94%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 0.94%   |
| Dell Hub of E-Port Replicator                                           | 1         | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 47        | 54.65%  |
| Intel                 | 24        | 27.91%  |
| Xiaomi                | 4         | 4.65%   |
| ASIX Electronics      | 3         | 3.49%   |
| Qualcomm Atheros      | 2         | 2.33%   |
| Broadcom              | 2         | 2.33%   |
| TP-Link               | 1         | 1.16%   |
| Samsung Electronics   | 1         | 1.16%   |
| Lenovo                | 1         | 1.16%   |
| ICS Advent            | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 38.64%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.27%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.27%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 2.27%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.14%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.14%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 1.14%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.14%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.14%   |
| Intel Ethernet Controller (2) I225-LMvP                           | 1         | 1.14%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.14%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.14%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.14%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.14%   |
| ICS Advent 10/100M LAN                                            | 1         | 1.14%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.14%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 55.19%  |
| Ethernet | 81        | 44.26%  |
| Modem    | 1         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 70.75%  |
| Ethernet | 31        | 29.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 67        | 65.69%  |
| 1     | 31        | 30.39%  |
| 3     | 3         | 2.94%   |
| 0     | 1         | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 71.57%  |
| Yes  | 29        | 28.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 56        | 60.22%  |
| Realtek Semiconductor   | 10        | 10.75%  |
| IMC Networks            | 5         | 5.38%   |
| Broadcom                | 4         | 4.3%    |
| Apple                   | 4         | 4.3%    |
| USI                     | 3         | 3.23%   |
| Lite-On Technology      | 3         | 3.23%   |
| Foxconn / Hon Hai       | 3         | 3.23%   |
| Realtek                 | 2         | 2.15%   |
| Dell                    | 1         | 1.08%   |
| Cambridge Silicon Radio | 1         | 1.08%   |
| Alps Electric           | 1         | 1.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 16        | 17.2%   |
| Intel AX200 Bluetooth                               | 13        | 13.98%  |
| Intel Bluetooth wireless interface                  | 12        | 12.9%   |
| Realtek Bluetooth Radio                             | 9         | 9.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 5.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 4.3%    |
| Intel AX210 Bluetooth                               | 4         | 4.3%    |
| IMC Networks Wireless_Device                        | 4         | 4.3%    |
| Apple Bluetooth Host Controller                     | 4         | 4.3%    |
| USI Bluetooth Device                                | 3         | 3.23%   |
| Realtek Bluetooth Radio                             | 2         | 2.15%   |
| Broadcom HP Portable SoftSailing                    | 2         | 2.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.08%   |
| Lite-On Wireless_Device                             | 1         | 1.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.08%   |
| Lite-On Bluetooth Device                            | 1         | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.08%   |
| IMC Networks 802.11ac WLAN Adapter                  | 1         | 1.08%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.08%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1         | 1.08%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.08%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.08%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.08%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 71        | 49.65%  |
| Nvidia              | 32        | 22.38%  |
| AMD                 | 32        | 22.38%  |
| Lenovo              | 2         | 1.4%    |
| ASUSTek Computer    | 2         | 1.4%    |
| Razer USA           | 1         | 0.7%    |
| Kingston Technology | 1         | 0.7%    |
| C-Media Electronics | 1         | 0.7%    |
| AudioQuest          | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 27        | 14.84%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 8.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 4.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 4.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 4.4%    |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 3.3%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 3.3%    |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 2.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.2%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 2.2%    |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.2%    |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.2%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 2.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.2%    |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.65%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.65%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.1%    |
| Nvidia Audio device                                                        | 2         | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.1%    |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.1%    |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.1%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.1%    |
| Razer USA Razer Kraken X USB                                               | 1         | 0.55%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.55%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 32.74%  |
| SK hynix            | 28        | 24.78%  |
| Micron Technology   | 16        | 14.16%  |
| Crucial             | 8         | 7.08%   |
| Unknown             | 5         | 4.42%   |
| Kingston            | 3         | 2.65%   |
| G.Skill             | 3         | 2.65%   |
| Corsair             | 3         | 2.65%   |
| Nanya Technology    | 2         | 1.77%   |
| Elpida              | 2         | 1.77%   |
| A-DATA Technology   | 2         | 1.77%   |
| Team                | 1         | 0.88%   |
| Patriot             | 1         | 0.88%   |
| GSkill              | 1         | 0.88%   |
| Apacer              | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 4         | 3.45%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 3         | 2.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 2.59%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s     | 3         | 2.59%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s       | 2         | 1.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 1.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 1.72%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s   | 2         | 1.72%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.72%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 2         | 1.72%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 2         | 1.72%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 1.72%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 1.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.72%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 2         | 1.72%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s         | 2         | 1.72%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 0.86%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.86%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.86%   |
| Unknown RAM Module 1GB SODIMM DDR2                           | 1         | 0.86%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s    | 1         | 0.86%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s        | 1         | 0.86%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 0.86%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 0.86%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                 | 1         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.86%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.86%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.86%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.86%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s    | 1         | 0.86%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s    | 1         | 0.86%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 0.86%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 0.86%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.86%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 0.86%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 0.86%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.86%   |
| SK hynix RAM HMA82GS7AFR8N-UH 16GB SODIMM DDR4 2400MT/s      | 1         | 0.86%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s   | 1         | 0.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 55        | 56.12%  |
| DDR3   | 24        | 24.49%  |
| DDR5   | 8         | 8.16%   |
| LPDDR4 | 5         | 5.1%    |
| LPDDR5 | 3         | 3.06%   |
| DDR2   | 2         | 2.04%   |
| LPDDR3 | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 86.87%  |
| Row Of Chips | 12        | 12.12%  |
| DIMM         | 1         | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 42        | 39.25%  |
| 16384 | 25        | 23.36%  |
| 4096  | 23        | 21.5%   |
| 32768 | 10        | 9.35%   |
| 2048  | 6         | 5.61%   |
| 1024  | 1         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 32        | 31.68%  |
| 1600    | 16        | 15.84%  |
| 2667    | 15        | 14.85%  |
| 4800    | 8         | 7.92%   |
| 4267    | 5         | 4.95%   |
| 2400    | 5         | 4.95%   |
| 6400    | 3         | 2.97%   |
| 2133    | 3         | 2.97%   |
| 1334    | 3         | 2.97%   |
| 1333    | 3         | 2.97%   |
| 8400    | 2         | 1.98%   |
| 3600    | 1         | 0.99%   |
| 3467    | 1         | 0.99%   |
| 1867    | 1         | 0.99%   |
| 1067    | 1         | 0.99%   |
| 533     | 1         | 0.99%   |
| Unknown | 1         | 0.99%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 24        | 28.57%  |
| Microdia                      | 11        | 13.1%   |
| Quanta                        | 7         | 8.33%   |
| IMC Networks                  | 6         | 7.14%   |
| Bison Electronics             | 5         | 5.95%   |
| Sunplus Innovation Technology | 4         | 4.76%   |
| Realtek Semiconductor         | 3         | 3.57%   |
| Luxvisions Innotech Limited   | 3         | 3.57%   |
| Apple                         | 3         | 3.57%   |
| Logitech                      | 2         | 2.38%   |
| Acer                          | 2         | 2.38%   |
| 8SSC21D67422V1SR28902JL       | 2         | 2.38%   |
| Suyin                         | 1         | 1.19%   |
| SunplusIT                     | 1         | 1.19%   |
| Sunplus Technology            | 1         | 1.19%   |
| Sonix Technology              | 1         | 1.19%   |
| Silicon Motion                | 1         | 1.19%   |
| ShineTech                     | 1         | 1.19%   |
| Microsoft                     | 1         | 1.19%   |
| Lite-On Technology            | 1         | 1.19%   |
| kingcome                      | 1         | 1.19%   |
| icSpring                      | 1         | 1.19%   |
| Holitech                      | 1         | 1.19%   |
| Genesys Logic                 | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 8         | 9.52%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 5         | 5.95%   |
| Microdia Integrated_Webcam_HD                        | 4         | 4.76%   |
| Microdia Integrated_Webcam_FHD                       | 3         | 3.57%   |
| Chicony HP HD Camera                                 | 3         | 3.57%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.38%   |
| Quanta HD User Facing                                | 2         | 2.38%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 2.38%   |
| Chicony HD WebCam                                    | 2         | 2.38%   |
| Apple iPhone 5/5C/5S/6/SE                            | 2         | 2.38%   |
| Acer Integrated Camera                               | 2         | 2.38%   |
| 8SSC21D67422V1SR28902JL Integrated RGB Camera        | 2         | 2.38%   |
| Suyin HP Truevision HD                               | 1         | 1.19%   |
| SunplusIT 720p HD Camera                             | 1         | 1.19%   |
| Sunplus 1.3M HD WebCam                               | 1         | 1.19%   |
| Sunplus XiaoMi USB 2.0 Webcam                        | 1         | 1.19%   |
| Sunplus Integrated_Webcam_FHD                        | 1         | 1.19%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 1.19%   |
| Silicon Motion 300k Pixel Camera                     | 1         | 1.19%   |
| ShineTech HD Camera                                  | 1         | 1.19%   |
| Realtek USB Camera                                   | 1         | 1.19%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.19%   |
| Realtek HP Webcam                                    | 1         | 1.19%   |
| Quanta VGA WebCam                                    | 1         | 1.19%   |
| Quanta HP Webcam                                     | 1         | 1.19%   |
| Quanta HP TrueVision HD Camera                       | 1         | 1.19%   |
| Quanta HP HD Camera                                  | 1         | 1.19%   |
| Quanta hm1091_techfront                              | 1         | 1.19%   |
| Microsoft MicrosoftÂ LifeCam Cinema                 | 1         | 1.19%   |
| Microdia USB Camera                                  | 1         | 1.19%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.19%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam       | 1         | 1.19%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.19%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.19%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.19%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.19%   |
| Lite-On HP HD Camera                                 | 1         | 1.19%   |
| kingcome 720p HD Camera                              | 1         | 1.19%   |
| IMC Networks ov9734_azurewave_camera                 | 1         | 1.19%   |
| icSpring camera                                      | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 36.36%  |
| Synaptics                  | 7         | 31.82%  |
| Shenzhen Goodix Technology | 6         | 27.27%  |
| LighTuning Technology      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                      | 6         | 27.27%  |
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 13.64%  |
| Synaptics UWP WBDI Device                                | 3         | 13.64%  |
| Validity Sensors Synaptics WBDI                          | 2         | 9.09%   |
| Validity Sensors Fingerprint scanner                     | 2         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 9.09%   |
| Validity Sensors VFS491                                  | 1         | 4.55%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.55%   |
| Synaptics Fingerprint reader [HP G6]                     | 1         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 46.15%  |
| Alcor Micro | 4         | 30.77%  |
| Upek        | 1         | 7.69%   |
| O2 Micro    | 1         | 7.69%   |
| Clay Logic  | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 30.77%  |
| Broadcom 58200                                                               | 3         | 23.08%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom 5880                                                                | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 41        | 38.68%  |
| 1     | 33        | 31.13%  |
| 2     | 14        | 13.21%  |
| 4     | 7         | 6.6%    |
| 3     | 6         | 5.66%   |
| 5     | 3         | 2.83%   |
| 6     | 2         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 17.21%  |
| Graphics card            | 18        | 14.75%  |
| Bluetooth                | 16        | 13.11%  |
| Camera                   | 14        | 11.48%  |
| Multimedia controller    | 12        | 9.84%   |
| Communication controller | 12        | 9.84%   |
| Chipcard                 | 12        | 9.84%   |
| Net/wireless             | 9         | 7.38%   |
| Sound                    | 3         | 2.46%   |
| Card reader              | 2         | 1.64%   |
| Network                  | 1         | 0.82%   |
| Net/ethernet             | 1         | 0.82%   |
| Modem                    | 1         | 0.82%   |


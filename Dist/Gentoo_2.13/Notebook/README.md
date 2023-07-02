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

Total: 142

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | Inspiron 16 5625            | [bf36f89d32](https://linux-hardware.org/?probe=bf36f89d32) | Jul 01, 2023 |
| Dell      | Inspiron 16 5625            | [cbbe256fa2](https://linux-hardware.org/?probe=cbbe256fa2) | Jun 30, 2023 |
| ASUSTek   | ASUS TUF Gaming F15 FX50... | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| Lenovo    | ThinkPad P14s Gen 3 21J5... | [2d16f5be74](https://linux-hardware.org/?probe=2d16f5be74) | Jun 29, 2023 |
| HP        | EliteBook 8540w             | [d675031e74](https://linux-hardware.org/?probe=d675031e74) | Jun 26, 2023 |
| Lenovo    | ThinkPad X1 Extreme 2nd ... | [178ed56625](https://linux-hardware.org/?probe=178ed56625) | Jun 26, 2023 |
| HP        | EliteBook 8540w             | [37e828b0b6](https://linux-hardware.org/?probe=37e828b0b6) | Jun 24, 2023 |
| HP        | EliteBook 8540w             | [e1678729ff](https://linux-hardware.org/?probe=e1678729ff) | Jun 23, 2023 |
| HP        | EliteBook 8540w             | [094d8e8ecf](https://linux-hardware.org/?probe=094d8e8ecf) | Jun 22, 2023 |
| HP        | EliteBook 8540w             | [a013e4866a](https://linux-hardware.org/?probe=a013e4866a) | Jun 22, 2023 |
| Lenovo    | ThinkPad P14s Gen 3 21J5... | [12153cd235](https://linux-hardware.org/?probe=12153cd235) | Jun 21, 2023 |
| HP        | EliteBook 8540w             | [6c766e53cb](https://linux-hardware.org/?probe=6c766e53cb) | Jun 21, 2023 |
| HP        | EliteBook 8540w             | [91e2324734](https://linux-hardware.org/?probe=91e2324734) | Jun 20, 2023 |
| HP        | EliteBook 8540w             | [cd78108f1f](https://linux-hardware.org/?probe=cd78108f1f) | Jun 19, 2023 |
| ASUSTek   | X555LJ                      | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| Lenovo    | ThinkPad P15 Gen 1 20SUS... | [4d509da42f](https://linux-hardware.org/?probe=4d509da42f) | Jun 18, 2023 |
| HP        | ENVY m6                     | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP        | EliteBook 8540w             | [eb29f214f3](https://linux-hardware.org/?probe=eb29f214f3) | Jun 17, 2023 |
| Dell      | Precision 5530              | [29ec4c7e1d](https://linux-hardware.org/?probe=29ec4c7e1d) | Jun 16, 2023 |
| HP        | Pavilion dv6                | [7e699d65f7](https://linux-hardware.org/?probe=7e699d65f7) | Jun 16, 2023 |
| Dell      | Precision 5530              | [cff5125fb6](https://linux-hardware.org/?probe=cff5125fb6) | Jun 16, 2023 |
| HP        | EliteBook 8540w             | [a7728ed657](https://linux-hardware.org/?probe=a7728ed657) | Jun 16, 2023 |
| HP        | EliteBook 8540w             | [03c8eed64b](https://linux-hardware.org/?probe=03c8eed64b) | Jun 16, 2023 |
| HP        | Victus by Laptop 16-e0xx... | [ec46ef5f36](https://linux-hardware.org/?probe=ec46ef5f36) | Jun 15, 2023 |
| HP        | EliteBook 8540w             | [9b08f8189d](https://linux-hardware.org/?probe=9b08f8189d) | Jun 15, 2023 |
| Google    | Nightfury                   | [02badb166b](https://linux-hardware.org/?probe=02badb166b) | Jun 14, 2023 |
| ASUSTek   | ROG G703GI_G7BI             | [fc0318992c](https://linux-hardware.org/?probe=fc0318992c) | Jun 12, 2023 |
| ASUSTek   | ROG G703GI_G7BI             | [272de7ad6b](https://linux-hardware.org/?probe=272de7ad6b) | Jun 11, 2023 |
| Lenovo    | Legion 5 15ACH6H 82JU       | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| Panasonic | CF-53ASCZGFG                | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Acer      | Swift SF314-511             | [60bf4b0442](https://linux-hardware.org/?probe=60bf4b0442) | Jun 05, 2023 |
| Dell      | Precision 5530              | [8b4e10b85a](https://linux-hardware.org/?probe=8b4e10b85a) | Jun 05, 2023 |
| Apple     | MacBookPro11,1              | [4192000802](https://linux-hardware.org/?probe=4192000802) | Jun 04, 2023 |
| Apple     | MacBookPro11,1              | [168fa7f541](https://linux-hardware.org/?probe=168fa7f541) | Jun 04, 2023 |
| Dell      | Precision 5530              | [151584f5aa](https://linux-hardware.org/?probe=151584f5aa) | Jun 02, 2023 |
| MSI       | GE76 Raider 11UH            | [64a17da7a3](https://linux-hardware.org/?probe=64a17da7a3) | May 28, 2023 |
| ASUSTek   | ROG Strix G513QY_G513QY     | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| Lenovo    | ThinkPad X13 Gen 3 21CM0... | [f4889c41be](https://linux-hardware.org/?probe=f4889c41be) | May 27, 2023 |
| ASUSTek   | ROG Strix G513QY_G513QY     | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| Lenovo    | ThinkPad T14 Gen 2i 20W1... | [852932c13b](https://linux-hardware.org/?probe=852932c13b) | May 26, 2023 |
| HP        | Pavilion Notebook           | [08eec5e6ca](https://linux-hardware.org/?probe=08eec5e6ca) | May 26, 2023 |
| HP        | EliteBook 8570w             | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| ASUSTek   | ROG Zephyrus G14 GA401II... | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| ASUSTek   | ROG Zephyrus G14 GA401II... | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| ASUSTek   | ROG Strix G513QY_G513QY     | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| HUAWEI    | NBLK-WAX9X                  | [2b6c863711](https://linux-hardware.org/?probe=2b6c863711) | May 15, 2023 |
| ASUSTek   | ROG Strix G513QY_G513QY     | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| Fujitsu   | CELSIUS H760                | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo    | ThinkPad X1 Extreme 2nd ... | [4b3b94a776](https://linux-hardware.org/?probe=4b3b94a776) | May 14, 2023 |
| Fujitsu   | CELSIUS H760                | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| HUAWEI    | CREM-WXX9                   | [b1b041ac47](https://linux-hardware.org/?probe=b1b041ac47) | May 12, 2023 |
| Lenovo    | ThinkPad E15 Gen 2 20T9S... | [870c85a9ac](https://linux-hardware.org/?probe=870c85a9ac) | May 12, 2023 |
| HUAWEI    | CREM-WXX9                   | [847d86e573](https://linux-hardware.org/?probe=847d86e573) | May 11, 2023 |
| ASUSTek   | ROG Zephyrus G14 GA401II... | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Unknown   | Unknown                     | [82281ca3d5](https://linux-hardware.org/?probe=82281ca3d5) | May 06, 2023 |
| HUAWEI    | CREM-WXX9                   | [8ebf347e24](https://linux-hardware.org/?probe=8ebf347e24) | May 03, 2023 |
| Acer      | Swift SF314-41              | [520066013b](https://linux-hardware.org/?probe=520066013b) | May 03, 2023 |
| HP        | EliteBook 840 G3            | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| ASUSTek   | ROG Zephyrus G14 GA401II... | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| Lenovo    | ThinkPad X13 Gen 3 21CM0... | [eeb1550b82](https://linux-hardware.org/?probe=eeb1550b82) | Apr 29, 2023 |
| HP        | G62                         | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek   | N550JX                      | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| Dell      | Inspiron N5010              | [78b4f0cd2f](https://linux-hardware.org/?probe=78b4f0cd2f) | Apr 27, 2023 |
| TUXEDO    | Polaris AMD Gen3 (CZN)      | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Acer      | Aspire A315-35              | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| HP        | Pavilion Gaming Laptop 1... | [a16e963c10](https://linux-hardware.org/?probe=a16e963c10) | Apr 26, 2023 |
| HP        | Pavilion Gaming Laptop 1... | [8bc0a29b23](https://linux-hardware.org/?probe=8bc0a29b23) | Apr 26, 2023 |
| HP        | EliteBook 840 G3            | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| HUAWEI    | CREM-WXX9                   | [fe2d361db9](https://linux-hardware.org/?probe=fe2d361db9) | Apr 25, 2023 |
| Dell      | Precision 7770              | [e9208415d5](https://linux-hardware.org/?probe=e9208415d5) | Apr 24, 2023 |
| Lenovo    | IdeaPad Yoga 13 20175       | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| HUAWEI    | NBLK-WAX9X                  | [3d88744f22](https://linux-hardware.org/?probe=3d88744f22) | Apr 20, 2023 |
| Dell      | Latitude 7420               | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| ASUSTek   | ROG Strix G513RM_G513RM     | [21c928caeb](https://linux-hardware.org/?probe=21c928caeb) | Apr 17, 2023 |
| ASUSTek   | ASUS TUF Gaming F17 FX70... | [1c99075a1d](https://linux-hardware.org/?probe=1c99075a1d) | Apr 16, 2023 |
| Toshiba   | Satellite L850              | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| MAXDATA   | o.max_5xs                   | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| HP        | OMEN by Laptop              | [8a1ef40351](https://linux-hardware.org/?probe=8a1ef40351) | Apr 15, 2023 |
| Dell      | Inspiron 5415               | [83ec457b1d](https://linux-hardware.org/?probe=83ec457b1d) | Apr 14, 2023 |
| Dell      | Inspiron 5415               | [ccf77bf033](https://linux-hardware.org/?probe=ccf77bf033) | Apr 14, 2023 |
| MAXDATA   | o.max_5xs                   | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| HUAWEI    | CREM-WXX9                   | [2ecd45a19e](https://linux-hardware.org/?probe=2ecd45a19e) | Apr 13, 2023 |
| Acer      | Aspire one                  | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Dell      | Precision 7770              | [5091c10fa2](https://linux-hardware.org/?probe=5091c10fa2) | Apr 11, 2023 |
| HUAWEI    | KPL-W0X                     | [2cf04d07fb](https://linux-hardware.org/?probe=2cf04d07fb) | Apr 09, 2023 |
| HP        | Laptop 17-cp0xxx            | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek   | ROG Zephyrus G14 GA401II... | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| Lenovo    | ThinkPad P14s Gen 2a 21A... | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| ASUSTek   | ROG Zephyrus G14 GA401II... | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Lenovo    | ThinkPad T470p 20J7S25C0... | [c1f70c64ad](https://linux-hardware.org/?probe=c1f70c64ad) | Apr 01, 2023 |
| Dell      | XPS 13 9305                 | [9e60f40931](https://linux-hardware.org/?probe=9e60f40931) | Mar 30, 2023 |
| Lenovo    | ThinkPad P51 20HHCTO1WW     | [85fb1a6778](https://linux-hardware.org/?probe=85fb1a6778) | Mar 26, 2023 |
| Acer      | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| HP        | EliteBook 745 G6            | [96fe7c184c](https://linux-hardware.org/?probe=96fe7c184c) | Mar 24, 2023 |
| Dell      | Latitude 7480               | [35b30305ec](https://linux-hardware.org/?probe=35b30305ec) | Mar 23, 2023 |
| HP        | EliteBook 745 G6            | [caf636a252](https://linux-hardware.org/?probe=caf636a252) | Mar 22, 2023 |
| Lenovo    | ThinkPad X200 7459L61       | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| HP        | EliteBook 8570p             | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| HP        | ZBook 17 G3                 | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Lenovo    | ThinkPad X1 Extreme 2nd ... | [135aa0e418](https://linux-hardware.org/?probe=135aa0e418) | Mar 18, 2023 |
| Unknown   | Unknown                     | [d2af864fbb](https://linux-hardware.org/?probe=d2af864fbb) | Mar 17, 2023 |
| Lenovo    | Legion 5 Pro 16IAH7H 82R... | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Star Labs | StarBook                    | [0b249699ba](https://linux-hardware.org/?probe=0b249699ba) | Mar 16, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop X571... | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Dell      | Precision 7770              | [b13d6bed73](https://linux-hardware.org/?probe=b13d6bed73) | Mar 14, 2023 |
| Dell      | Precision 7770              | [38f84c4cfc](https://linux-hardware.org/?probe=38f84c4cfc) | Mar 14, 2023 |
| Lenovo    | ThinkPad Edge E330 3354A... | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| HP        | Victus by Gaming Laptop ... | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| Dell      | Precision 7770              | [7d5207e1c1](https://linux-hardware.org/?probe=7d5207e1c1) | Mar 09, 2023 |
| Dell      | Latitude E6540              | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | [ad6e1bbda5](https://linux-hardware.org/?probe=ad6e1bbda5) | Mar 08, 2023 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | [e455dce9f3](https://linux-hardware.org/?probe=e455dce9f3) | Mar 07, 2023 |
| Dell      | Precision 7770              | [dea25f9c87](https://linux-hardware.org/?probe=dea25f9c87) | Mar 07, 2023 |
| Dell      | Precision 7770              | [aa1ff5150c](https://linux-hardware.org/?probe=aa1ff5150c) | Mar 06, 2023 |
| Acer      | Aspire 7750G                | [f0cde07b9f](https://linux-hardware.org/?probe=f0cde07b9f) | Mar 05, 2023 |
| MSI       | GS66 Stealth 10UE           | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| MSI       | GS66 Stealth 10UE           | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI       | GS66 Stealth 10UE           | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| realme    | RMNBXXXX                    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| Valve     | Jupiter                     | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| MSI       | GS66 Stealth 10UE           | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI       | Vector GP66 12UEO           | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| MSI       | GS66 Stealth 10UE           | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| HP        | Pavilion Notebook           | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| Dell      | Precision 7770              | [d8db6fecdd](https://linux-hardware.org/?probe=d8db6fecdd) | Feb 20, 2023 |
| Valve     | Jupiter                     | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| ASUSTek   | ROG Strix G732LXS_G732LX... | [6424058c59](https://linux-hardware.org/?probe=6424058c59) | Feb 19, 2023 |
| ASUSTek   | Strix 17 GL703GE            | [48ca6dc3eb](https://linux-hardware.org/?probe=48ca6dc3eb) | Feb 19, 2023 |
| MSI       | GS66 Stealth 10UE           | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Timi      | RedmiBook Pro 15S           | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| Unknown   | Unknown                     | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown   | Unknown                     | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Dell      | XPS 15 9520                 | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| HP        | Pavilion Notebook           | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Timi      | RedmiBook Pro 15S           | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Timi      | RedmiBook Pro 15S           | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Dell      | Precision 7770              | [69b0982ad7](https://linux-hardware.org/?probe=69b0982ad7) | Feb 08, 2023 |
| Dell      | Precision 7770              | [28ba6f72d0](https://linux-hardware.org/?probe=28ba6f72d0) | Feb 07, 2023 |
| Dell      | Precision 7770              | [d05aabf7a5](https://linux-hardware.org/?probe=d05aabf7a5) | Feb 06, 2023 |
| Dell      | Precision 7770              | [20f6b87742](https://linux-hardware.org/?probe=20f6b87742) | Feb 03, 2023 |
| HP        | Victus by Laptop 16-e0xx... | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| Lenovo    | ThinkPad T16 Gen 1 21CH0... | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                              | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| 6.1.19-gentoo-x86_64                 | 7         | 7.61%   |
| 6.1.19-gentoo                        | 4         | 4.35%   |
| 6.1.12-gentoo                        | 4         | 4.35%   |
| 6.1.31-gentoo-x86_64                 | 3         | 3.26%   |
| 6.1.31-gentoo-dist                   | 3         | 3.26%   |
| 6.1.12-gentoo-dist                   | 3         | 3.26%   |
| 6.3.8-gentoo-dist                    | 2         | 2.17%   |
| 6.3.0-gentoo                         | 2         | 2.17%   |
| 6.2.8-gentoo-x86_64                  | 2         | 2.17%   |
| 6.1.9-gentoo-x86_64                  | 2         | 2.17%   |
| 6.1.24-gentoo-dist                   | 2         | 2.17%   |
| 6.1.22-gentoo-dist                   | 2         | 2.17%   |
| 6.1.19-gentoo-dist                   | 2         | 2.17%   |
| 6.1.12-gentoo-x86_64                 | 2         | 2.17%   |
| 6.1.10-gentoo-x86_64                 | 2         | 2.17%   |
| 6.4.0-gentoo                         | 1         | 1.09%   |
| 6.3.8-gentoo                         | 1         | 1.09%   |
| 6.3.6-gentoo-dist                    | 1         | 1.09%   |
| 6.3.5-ivybridge-xanmod1              | 1         | 1.09%   |
| 6.3.4-gentoo-r1                      | 1         | 1.09%   |
| 6.3.4-gentoo                         | 1         | 1.09%   |
| 6.3.2-gentoo-dist                    | 1         | 1.09%   |
| 6.3.0                                | 1         | 1.09%   |
| 6.2.9-gentoo                         | 1         | 1.09%   |
| 6.2.8-gentoo                         | 1         | 1.09%   |
| 6.2.7-gentoo-dist                    | 1         | 1.09%   |
| 6.2.6-gentoo-dist                    | 1         | 1.09%   |
| 6.2.3-gentoo                         | 1         | 1.09%   |
| 6.2.2-gentoo-x86_64                  | 1         | 1.09%   |
| 6.2.2-gentoo                         | 1         | 1.09%   |
| 6.2.2-dist                           | 1         | 1.09%   |
| 6.2.14-gentoo-dist                   | 1         | 1.09%   |
| 6.2.12-gentoo-x86_642023-04-24--2109 | 1         | 1.09%   |
| 6.2.11-zen1                          | 1         | 1.09%   |
| 6.2.11-tkg-cfs                       | 1         | 1.09%   |
| 6.2.11-gentoo-x86_64                 | 1         | 1.09%   |
| 6.2.11-gentoo-dist                   | 1         | 1.09%   |
| 6.2.11-gentoo                        | 1         | 1.09%   |
| 6.2.10-gentoo-dist                   | 1         | 1.09%   |
| 6.2.1-gentoo-x86_64                  | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.19  | 15        | 16.3%   |
| 6.1.12  | 10        | 10.87%  |
| 6.1.31  | 9         | 9.78%   |
| 6.2.11  | 5         | 5.43%   |
| 6.3.8   | 3         | 3.26%   |
| 6.3.0   | 3         | 3.26%   |
| 6.2.8   | 3         | 3.26%   |
| 6.2.2   | 3         | 3.26%   |
| 6.1.9   | 3         | 3.26%   |
| 6.1.11  | 3         | 3.26%   |
| 6.1.10  | 3         | 3.26%   |
| 6.3.4   | 2         | 2.17%   |
| 6.1.28  | 2         | 2.17%   |
| 6.1.24  | 2         | 2.17%   |
| 6.1.22  | 2         | 2.17%   |
| 5.15.88 | 2         | 2.17%   |
| 5.15.80 | 2         | 2.17%   |
| 6.4.0   | 1         | 1.09%   |
| 6.3.6   | 1         | 1.09%   |
| 6.3.5   | 1         | 1.09%   |
| 6.3.2   | 1         | 1.09%   |
| 6.2.9   | 1         | 1.09%   |
| 6.2.7   | 1         | 1.09%   |
| 6.2.6   | 1         | 1.09%   |
| 6.2.3   | 1         | 1.09%   |
| 6.2.14  | 1         | 1.09%   |
| 6.2.12  | 1         | 1.09%   |
| 6.2.10  | 1         | 1.09%   |
| 6.2.1   | 1         | 1.09%   |
| 6.2.0   | 1         | 1.09%   |
| 6.1.4   | 1         | 1.09%   |
| 6.1.30  | 1         | 1.09%   |
| 6.1.27  | 1         | 1.09%   |
| 6.1.13  | 1         | 1.09%   |
| 5.15.94 | 1         | 1.09%   |
| 5.15.93 | 1         | 1.09%   |
| 5.15.72 | 1         | 1.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 49        | 56.32%  |
| 6.2     | 19        | 21.84%  |
| 6.3     | 11        | 12.64%  |
| 5.15    | 7         | 8.05%   |
| 6.4     | 1         | 1.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 79        | 97.53%  |
| i686   | 2         | 2.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 25        | 30.12%  |
| Unknown   | 24        | 28.92%  |
| XFCE      | 8         | 9.64%   |
| GNOME     | 8         | 9.64%   |
| MATE      | 4         | 4.82%   |
| DWM       | 4         | 4.82%   |
| Trinity   | 2         | 2.41%   |
| Xsession  | 1         | 1.2%    |
| sway      | 1         | 1.2%    |
| ratpoison | 1         | 1.2%    |
| LXQt      | 1         | 1.2%    |
| KDE       | 1         | 1.2%    |
| ICEWM     | 1         | 1.2%    |
| i3        | 1         | 1.2%    |
| awesome   | 1         | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 42        | 50.6%   |
| Wayland | 21        | 25.3%   |
| Unknown | 11        | 13.25%  |
| Tty     | 9         | 10.84%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 29        | 35.37%  |
| Unknown | 24        | 29.27%  |
| LightDM | 12        | 14.63%  |
| GDM     | 8         | 9.76%   |
| TDM     | 3         | 3.66%   |
| SLiM    | 2         | 2.44%   |
| GREETD  | 2         | 2.44%   |
| XDM     | 1         | 1.22%   |
| LXDM    | 1         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 33        | 40.24%  |
| Unknown | 12        | 14.63%  |
| en_GB   | 7         | 8.54%   |
| C.UTF8  | 7         | 8.54%   |
| ru_RU   | 4         | 4.88%   |
| fr_FR   | 4         | 4.88%   |
| cs_CZ   | 4         | 4.88%   |
| de_DE   | 3         | 3.66%   |
| C       | 2         | 2.44%   |
| ro_RO   | 1         | 1.22%   |
| pl_PL   | 1         | 1.22%   |
| it_IT   | 1         | 1.22%   |
| fr_CA   | 1         | 1.22%   |
| en_AU   | 1         | 1.22%   |
| el_GR   | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 64        | 79.01%  |
| BIOS | 17        | 20.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 46        | 56.79%  |
| Btrfs   | 30        | 37.04%  |
| F2fs    | 2         | 2.47%   |
| XXXXXXX | 1         | 1.23%   |
| Xfs     | 1         | 1.23%   |
| Jfs     | 1         | 1.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 69        | 84.15%  |
| MBR     | 11        | 13.41%  |
| Unknown | 2         | 2.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 71.95%  |
| Yes       | 23        | 28.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 64.63%  |
| Yes       | 29        | 35.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 16        | 19.75%  |
| Hewlett-Packard  | 15        | 18.52%  |
| ASUSTek Computer | 14        | 17.28%  |
| Dell             | 11        | 13.58%  |
| Acer             | 6         | 7.41%   |
| MSI              | 3         | 3.7%    |
| HUAWEI           | 3         | 3.7%    |
| Unknown          | 2         | 2.47%   |
| Valve            | 1         | 1.23%   |
| TUXEDO           | 1         | 1.23%   |
| Toshiba          | 1         | 1.23%   |
| Timi             | 1         | 1.23%   |
| Star Labs        | 1         | 1.23%   |
| realme           | 1         | 1.23%   |
| Panasonic        | 1         | 1.23%   |
| MAXDATA          | 1         | 1.23%   |
| Google           | 1         | 1.23%   |
| Fujitsu          | 1         | 1.23%   |
| Apple            | 1         | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ASUS ROG Zephyrus G14 GA401II_GA401II       | 3         | 3.7%    |
| Dell Precision 7770                         | 2         | 2.47%   |
| ASUS ROG Strix G513QY_G513QY                | 2         | 2.47%   |
| Unknown                                     | 2         | 2.47%   |
| Valve Jupiter                               | 1         | 1.23%   |
| TUXEDO Polaris AMD Gen3 (CZN)               | 1         | 1.23%   |
| Toshiba Satellite L850                      | 1         | 1.23%   |
| Timi RedmiBook Pro 15S                      | 1         | 1.23%   |
| Star Labs StarBook                          | 1         | 1.23%   |
| realme RMNBXXXX                             | 1         | 1.23%   |
| Panasonic CF-53ASCZGFG                      | 1         | 1.23%   |
| MSI Vector GP66 12UEO                       | 1         | 1.23%   |
| MSI GS66 Stealth 10UE                       | 1         | 1.23%   |
| MSI GE76 Raider 11UH                        | 1         | 1.23%   |
| MAXDATA o.max_5xs                           | 1         | 1.23%   |
| Lenovo ThinkPad X200 7459L61                | 1         | 1.23%   |
| Lenovo ThinkPad X13 Gen 3 21CM0024US        | 1         | 1.23%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001JUS | 1         | 1.23%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW   | 1         | 1.23%   |
| Lenovo ThinkPad T470p 20J7S25C00            | 1         | 1.23%   |
| Lenovo ThinkPad T16 Gen 1 21CH000FUS        | 1         | 1.23%   |
| Lenovo ThinkPad T14 Gen 2i 20W1SCBN00       | 1         | 1.23%   |
| Lenovo ThinkPad P51 20HHCTO1WW              | 1         | 1.23%   |
| Lenovo ThinkPad P15 Gen 1 20SUS0S000        | 1         | 1.23%   |
| Lenovo ThinkPad P14s Gen 3 21J5001NUS       | 1         | 1.23%   |
| Lenovo ThinkPad P14s Gen 2a 21A0000JMH      | 1         | 1.23%   |
| Lenovo ThinkPad Edge E330 3354AMG           | 1         | 1.23%   |
| Lenovo ThinkPad E15 Gen 2 20T9S00K00        | 1         | 1.23%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF            | 1         | 1.23%   |
| Lenovo Legion 5 15ACH6H 82JU                | 1         | 1.23%   |
| Lenovo IdeaPad Yoga 13 20175                | 1         | 1.23%   |
| HUAWEI NBLK-WAX9X                           | 1         | 1.23%   |
| HUAWEI KPL-W0X                              | 1         | 1.23%   |
| HUAWEI CREM-WXX9                            | 1         | 1.23%   |
| HP ZBook 17 G3                              | 1         | 1.23%   |
| HP Victus by Laptop 16-e0xxx                | 1         | 1.23%   |
| HP Victus by Gaming Laptop 15-fb0xxx        | 1         | 1.23%   |
| HP Pavilion Notebook                        | 1         | 1.23%   |
| HP Pavilion Gaming Laptop 15-ec1xxx         | 1         | 1.23%   |
| HP Pavilion dv6                             | 1         | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 16.05%  |
| ASUS ROG               | 8         | 9.88%   |
| HP EliteBook           | 5         | 6.17%   |
| Acer Aspire            | 4         | 4.94%   |
| HP Pavilion            | 3         | 3.7%    |
| Dell Precision         | 3         | 3.7%    |
| Dell Latitude          | 3         | 3.7%    |
| Dell Inspiron          | 3         | 3.7%    |
| Lenovo Legion          | 2         | 2.47%   |
| HP Victus              | 2         | 2.47%   |
| Dell XPS               | 2         | 2.47%   |
| ASUS ASUS              | 2         | 2.47%   |
| Acer Swift             | 2         | 2.47%   |
| Unknown                | 2         | 2.47%   |
| Valve Jupiter          | 1         | 1.23%   |
| TUXEDO Polaris         | 1         | 1.23%   |
| Toshiba Satellite      | 1         | 1.23%   |
| Timi RedmiBook         | 1         | 1.23%   |
| Star Labs StarBook     | 1         | 1.23%   |
| realme RMNBXXXX        | 1         | 1.23%   |
| Panasonic CF-53ASCZGFG | 1         | 1.23%   |
| MSI Vector             | 1         | 1.23%   |
| MSI GS66               | 1         | 1.23%   |
| MSI GE76               | 1         | 1.23%   |
| MAXDATA o.max          | 1         | 1.23%   |
| Lenovo IdeaPad         | 1         | 1.23%   |
| HUAWEI NBLK-WAX9X      | 1         | 1.23%   |
| HUAWEI KPL-W0X         | 1         | 1.23%   |
| HUAWEI CREM-WXX9       | 1         | 1.23%   |
| HP ZBook               | 1         | 1.23%   |
| HP OMEN                | 1         | 1.23%   |
| HP Laptop              | 1         | 1.23%   |
| HP G62                 | 1         | 1.23%   |
| HP ENVY                | 1         | 1.23%   |
| Google Nightfury       | 1         | 1.23%   |
| Fujitsu CELSIUS        | 1         | 1.23%   |
| ASUS X555LJ            | 1         | 1.23%   |
| ASUS VivoBook          | 1         | 1.23%   |
| ASUS Strix             | 1         | 1.23%   |
| ASUS N550JX            | 1         | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 20        | 24.69%  |
| 2022 | 13        | 16.05%  |
| 2020 | 8         | 9.88%   |
| 2019 | 7         | 8.64%   |
| 2018 | 6         | 7.41%   |
| 2012 | 6         | 7.41%   |
| 2010 | 4         | 4.94%   |
| 2017 | 3         | 3.7%    |
| 2016 | 3         | 3.7%    |
| 2023 | 2         | 2.47%   |
| 2015 | 2         | 2.47%   |
| 2011 | 2         | 2.47%   |
| 2008 | 2         | 2.47%   |
| 2014 | 1         | 1.23%   |
| 2013 | 1         | 1.23%   |
| 2007 | 1         | 1.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 81        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 81        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 97.53%  |
| Yes  | 2         | 2.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 19        | 23.17%  |
| 4.01-8.0    | 17        | 20.73%  |
| 16.01-24.0  | 16        | 19.51%  |
| 32.01-64.0  | 15        | 18.29%  |
| 24.01-32.0  | 6         | 7.32%   |
| 3.01-4.0    | 4         | 4.88%   |
| 64.01-256.0 | 3         | 3.66%   |
| 2.01-3.0    | 1         | 1.22%   |
| 0.51-1.0    | 1         | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 18        | 20.22%  |
| 1.01-2.0   | 15        | 16.85%  |
| 4.01-8.0   | 13        | 14.61%  |
| 0.51-1.0   | 13        | 14.61%  |
| 3.01-4.0   | 11        | 12.36%  |
| 8.01-16.0  | 9         | 10.11%  |
| 0.01-0.5   | 9         | 10.11%  |
| 32.01-64.0 | 1         | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 69.51%  |
| 2      | 23        | 28.05%  |
| 3      | 2         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 83.95%  |
| Yes       | 13        | 16.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 79.27%  |
| No        | 17        | 20.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 88.89%  |
| No        | 9         | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 22        | 27.16%  |
| Russia      | 9         | 11.11%  |
| France      | 6         | 7.41%   |
| Canada      | 6         | 7.41%   |
| Spain       | 4         | 4.94%   |
| Germany     | 4         | 4.94%   |
| UK          | 3         | 3.7%    |
| Poland      | 3         | 3.7%    |
| Czechia     | 3         | 3.7%    |
| Italy       | 2         | 2.47%   |
| China       | 2         | 2.47%   |
| Romania     | 1         | 1.23%   |
| Portugal    | 1         | 1.23%   |
| Norway      | 1         | 1.23%   |
| New Zealand | 1         | 1.23%   |
| Netherlands | 1         | 1.23%   |
| Lithuania   | 1         | 1.23%   |
| Iran        | 1         | 1.23%   |
| Indonesia   | 1         | 1.23%   |
| Iceland     | 1         | 1.23%   |
| Hungary     | 1         | 1.23%   |
| Hong Kong   | 1         | 1.23%   |
| Greece      | 1         | 1.23%   |
| Brazil      | 1         | 1.23%   |
| Belgium     | 1         | 1.23%   |
| Belarus     | 1         | 1.23%   |
| Australia   | 1         | 1.23%   |
| Algeria     | 1         | 1.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| St Petersburg | 3         | 3.57%   |
| Berlin        | 3         | 3.57%   |
| Taganrog      | 2         | 2.38%   |
| Šlapanice    | 2         | 2.38%   |
| Oviedo        | 2         | 2.38%   |
| Milan         | 2         | 2.38%   |
| Kippens       | 2         | 2.38%   |
| Wlodawa       | 1         | 1.19%   |
| Whitby        | 1         | 1.19%   |
| Wandsworth    | 1         | 1.19%   |
| Vilnius       | 1         | 1.19%   |
| Urbana        | 1         | 1.19%   |
| Trakai        | 1         | 1.19%   |
| Toronto       | 1         | 1.19%   |
| Sun Prairie   | 1         | 1.19%   |
| Shenzhen      | 1         | 1.19%   |
| Seattle       | 1         | 1.19%   |
| Roland        | 1         | 1.19%   |
| Reykjavik     | 1         | 1.19%   |
| Rapid City    | 1         | 1.19%   |
| Québec       | 1         | 1.19%   |
| Prague        | 1         | 1.19%   |
| Pittsburgh    | 1         | 1.19%   |
| Piraeus       | 1         | 1.19%   |
| Paris         | 1         | 1.19%   |
| Oslo          | 1         | 1.19%   |
| Omsk          | 1         | 1.19%   |
| Nea Artaki    | 1         | 1.19%   |
| Nampa         | 1         | 1.19%   |
| Moscow        | 1         | 1.19%   |
| Monroe        | 1         | 1.19%   |
| Minsk         | 1         | 1.19%   |
| Miami         | 1         | 1.19%   |
| Melbourne     | 1         | 1.19%   |
| Mangalia      | 1         | 1.19%   |
| Majadahonda   | 1         | 1.19%   |
| Madrid        | 1         | 1.19%   |
| Madison       | 1         | 1.19%   |
| Lomme         | 1         | 1.19%   |
| Lisbon        | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 27        | 41     | 27.55%  |
| Sandisk                     | 15        | 18     | 15.31%  |
| Seagate                     | 8         | 9      | 8.16%   |
| SK hynix                    | 7         | 8      | 7.14%   |
| Intel                       | 6         | 8      | 6.12%   |
| WDC                         | 3         | 4      | 3.06%   |
| Unknown                     | 3         | 4      | 3.06%   |
| Phison Electronics          | 3         | 4      | 3.06%   |
| Micron Technology           | 3         | 3      | 3.06%   |
| Kingston Technology Company | 3         | 3      | 3.06%   |
| HGST                        | 3         | 3      | 3.06%   |
| KIOXIA                      | 2         | 3      | 2.04%   |
| Kingston                    | 2         | 2      | 2.04%   |
| GOODRAM                     | 2         | 2      | 2.04%   |
| China                       | 2         | 5      | 2.04%   |
| A-DATA Technology           | 2         | 2      | 2.04%   |
| Toshiba                     | 1         | 1      | 1.02%   |
| Teleplan                    | 1         | 1      | 1.02%   |
| Micron/Crucial Technology   | 1         | 3      | 1.02%   |
| Intenso                     | 1         | 1      | 1.02%   |
| Hitachi                     | 1         | 1      | 1.02%   |
| Dogfish                     | 1         | 1      | 1.02%   |
| Crucial                     | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 12        | 11.76%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 9         | 8.82%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 4         | 3.92%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 4         | 3.92%   |
| Samsung SSD 980 1TB                                 | 3         | 2.94%   |
| Unknown MMC Card  128GB                             | 2         | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.96%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 2         | 1.96%   |
| Intel SSDPEKNU512GZ 512GB                           | 2         | 1.96%   |
| HGST HTS725050A7E630 500GB                          | 2         | 1.96%   |
| China SSD 1TB                                       | 2         | 1.96%   |
| WDC WDS500G1B0B-00AS40 500GB SSD                    | 1         | 0.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.98%   |
| WDC WD20 SPZX-22CRAT0 2TB                           | 1         | 0.98%   |
| Unknown NVMe SSD Drive 1TB                          | 1         | 0.98%   |
| Toshiba MK5056GSY 500GB                             | 1         | 0.98%   |
| Teleplan TP1000G 1TB                                | 1         | 0.98%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB                | 1         | 0.98%   |
| SK hynix SC311 SATA 128GB SSD                       | 1         | 0.98%   |
| SK hynix PC801 NVMe 1TB                             | 1         | 0.98%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 0.98%   |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 0.98%   |
| SK hynix BC711 NVMe 512GB                           | 1         | 0.98%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 0.98%   |
| Seagate ST500LX025-1U717D 500GB                     | 1         | 0.98%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 0.98%   |
| Seagate ST2000LX001-1RG174 2TB                      | 1         | 0.98%   |
| Seagate ST2000LM015-2E8174 2TB                      | 1         | 0.98%   |
| Sandisk WD_BLACK SN850X 2000GB                      | 1         | 0.98%   |
| Sandisk WD_BLACK SN850X 1000GB                      | 1         | 0.98%   |
| Sandisk WDC PC SN530 SDBPTPZ-512G-1002 512GB        | 1         | 0.98%   |
| Sandisk WD PC SN735 SDBPNHH-512G-1002 512GB         | 1         | 0.98%   |
| SanDisk SDSSDHII960G 960GB                          | 1         | 0.98%   |
| SanDisk SD9SN8W256G1027 256GB SSD                   | 1         | 0.98%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                 | 1         | 0.98%   |
| Samsung SSD 850 EVO 250GB                           | 1         | 0.98%   |
| Samsung SSD 840 EVO 250GB                           | 1         | 0.98%   |
| Samsung MZVLQ512HBLU-00B00 512GB                    | 1         | 0.98%   |
| Samsung MZVLQ1T0HBLB-00B00 1TB                      | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 8         | 9      | 53.33%  |
| HGST     | 3         | 3      | 20%     |
| WDC      | 1         | 1      | 6.67%   |
| Toshiba  | 1         | 1      | 6.67%   |
| Teleplan | 1         | 1      | 6.67%   |
| Hitachi  | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 19.05%  |
| SanDisk             | 3         | 4      | 14.29%  |
| WDC                 | 2         | 3      | 9.52%   |
| GOODRAM             | 2         | 2      | 9.52%   |
| China               | 2         | 5      | 9.52%   |
| A-DATA Technology   | 2         | 2      | 9.52%   |
| SK hynix            | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| Intenso             | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| Dogfish             | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 54        | 82     | 59.34%  |
| SSD  | 20        | 27     | 21.98%  |
| HDD  | 15        | 16     | 16.48%  |
| MMC  | 2         | 3      | 2.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 54        | 82     | 60%     |
| SATA | 33        | 42     | 36.67%  |
| MMC  | 2         | 3      | 2.22%   |
| SAS  | 1         | 1      | 1.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 23     | 54.29%  |
| 0.51-1.0   | 11        | 12     | 31.43%  |
| 1.01-2.0   | 5         | 8      | 14.29%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 20        | 24.39%  |
| 501-1000       | 20        | 24.39%  |
| 101-250        | 17        | 20.73%  |
| 1001-2000      | 8         | 9.76%   |
| More than 3000 | 4         | 4.88%   |
| 2001-3000      | 4         | 4.88%   |
| 51-100         | 4         | 4.88%   |
| 1-20           | 2         | 2.44%   |
| Unknown        | 2         | 2.44%   |
| 21-50          | 1         | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 21.59%  |
| 21-50          | 18        | 20.45%  |
| 101-250        | 14        | 15.91%  |
| 251-500        | 12        | 13.64%  |
| 51-100         | 11        | 12.5%   |
| 501-1000       | 8         | 9.09%   |
| 1001-2000      | 3         | 3.41%   |
| Unknown        | 2         | 2.27%   |
| More than 3000 | 1         | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 3      | 25%     |
| HGST HTS725050A7E630 500GB           | 2         | 2      | 25%     |
| Toshiba MK5056GSY 500GB              | 1         | 1      | 12.5%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 2      | 12.5%   |
| Intel SSDSC2BF180A5L 180GB           | 1         | 1      | 12.5%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| HGST     | 3         | 3      | 37.5%   |
| Seagate  | 2         | 3      | 25%     |
| Toshiba  | 1         | 1      | 12.5%   |
| SK hynix | 1         | 2      | 12.5%   |
| Intel    | 1         | 1      | 12.5%   |

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
| HDD  | 6         | 7      | 75%     |
| NVMe | 1         | 2      | 12.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Works    | 69        | 105    | 81.18%  |
| Malfunc  | 8         | 10     | 9.41%   |
| Detected | 7         | 12     | 8.24%   |
| Failed   | 1         | 1      | 1.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 36.11%  |
| Samsung Electronics         | 23        | 21.3%   |
| AMD                         | 14        | 12.96%  |
| SanDisk                     | 12        | 11.11%  |
| SK hynix                    | 6         | 5.56%   |
| Kingston Technology Company | 4         | 3.7%    |
| Phison Electronics          | 3         | 2.78%   |
| Micron Technology           | 3         | 2.78%   |
| KIOXIA                      | 2         | 1.85%   |
| Micron/Crucial Technology   | 1         | 0.93%   |
| INNOGRIT                    | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 13        | 11.21%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 12        | 10.34%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 9         | 7.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 6         | 5.17%   |
| Samsung NVMe SSD Controller 980                                               | 5         | 4.31%   |
| Intel Volume Management Device NVMe RAID Controller                           | 5         | 4.31%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 4         | 3.45%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 4         | 3.45%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 4         | 3.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 3.45%   |
| Micron 2450 NVMe SSD (DRAM-less)                                              | 3         | 2.59%   |
| Intel Non-Volatile memory controller                                          | 3         | 2.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 3         | 2.59%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                              | 2         | 1.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 1.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                | 2         | 1.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 1.72%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                            | 1         | 0.86%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 1         | 0.86%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 1         | 0.86%   |
| SanDisk Non-Volatile memory controller                                        | 1         | 0.86%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 0.86%   |
| Phison NVMe Storage Controller                                                | 1         | 0.86%   |
| Phison E12 NVMe Controller                                                    | 1         | 0.86%   |
| Micron/Crucial P1 NVMe PCIe SSD                                               | 1         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4                                                | 1         | 0.86%   |
| KIOXIA Non-Volatile memory controller                                         | 1         | 0.86%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 0.86%   |
| Kingston Company OM3PDP3 NVMe SSD                                             | 1         | 0.86%   |
| Kingston Company NVMe Controller                                              | 1         | 0.86%   |
| Kingston Company FURY Renegade NVMe SSD                                       | 1         | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 0.86%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 1         | 0.86%   |
| Intel SSD 660P Series                                                         | 1         | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.86%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 1         | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 54        | 50.94%  |
| SATA | 42        | 39.62%  |
| RAID | 9         | 8.49%   |
| IDE  | 1         | 0.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 66.67%  |
| AMD    | 27        | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 6.1%    |
| Intel 12th Gen Core i7-12700H                 | 4         | 4.88%   |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 3         | 3.66%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 2.44%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 2.44%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 2.44%   |
| Intel 12th Gen Core i7-12850HX                | 2         | 2.44%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 2.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.44%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 2.44%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics    | 2         | 2.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.44%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 1.22%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.22%   |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 1.22%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 1.22%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 1.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.22%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.22%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 1.22%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1.22%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.22%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.22%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.22%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.22%   |
| Intel Core i5-4258U CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.22%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 1.22%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 17        | 20.99%  |
| Intel Core i7        | 16        | 19.75%  |
| AMD Ryzen 7          | 12        | 14.81%  |
| Intel Core i5        | 11        | 13.58%  |
| AMD Ryzen 5          | 6         | 7.41%   |
| AMD Ryzen 7 PRO      | 4         | 4.94%   |
| Intel Core i3        | 3         | 3.7%    |
| Intel Core i9        | 2         | 2.47%   |
| AMD Ryzen 9          | 2         | 2.47%   |
| Intel Xeon           | 1         | 1.23%   |
| Intel Pentium Silver | 1         | 1.23%   |
| Intel Pentium        | 1         | 1.23%   |
| Intel Core Duo       | 1         | 1.23%   |
| Intel Core 2 Duo     | 1         | 1.23%   |
| Intel Atom           | 1         | 1.23%   |
| AMD Ryzen 5 PRO      | 1         | 1.23%   |
| AMD Athlon II        | 1         | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 22        | 27.16%  |
| 8      | 20        | 24.69%  |
| 2      | 20        | 24.69%  |
| 6      | 11        | 13.58%  |
| 14     | 4         | 4.94%   |
| 16     | 2         | 2.47%   |
| 12     | 1         | 1.23%   |
| 1      | 1         | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 81        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 75        | 92.59%  |
| 1      | 6         | 7.41%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 79        | 97.53%  |
| 32-bit         | 2         | 2.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 31.76%  |
| 0x806c1    | 7         | 8.24%   |
| 0x0a50000c | 7         | 8.24%   |
| 0x906ea    | 4         | 4.71%   |
| 0xa0652    | 3         | 3.53%   |
| 0x906e9    | 3         | 3.53%   |
| 0x206a7    | 3         | 3.53%   |
| 0x08600104 | 3         | 3.53%   |
| 0x906a3    | 2         | 2.35%   |
| 0x90672    | 2         | 2.35%   |
| 0x806d1    | 2         | 2.35%   |
| 0x20655    | 2         | 2.35%   |
| 0x0a50000d | 2         | 2.35%   |
| 0x0a404102 | 2         | 2.35%   |
| 0x08608103 | 2         | 2.35%   |
| 0x08108109 | 2         | 2.35%   |
| 0x806ec    | 1         | 1.18%   |
| 0x806e9    | 1         | 1.18%   |
| 0x506e3    | 1         | 1.18%   |
| 0x406e3    | 1         | 1.18%   |
| 0x40651    | 1         | 1.18%   |
| 0x306d4    | 1         | 1.18%   |
| 0x306a9    | 1         | 1.18%   |
| 0x08900201 | 1         | 1.18%   |
| 0x08701021 | 1         | 1.18%   |
| 0x08600106 | 1         | 1.18%   |
| 0x08600103 | 1         | 1.18%   |
| 0x08101007 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Zen 3            | 10        | 12.35%  |
| KabyLake         | 10        | 12.35%  |
| Unknown          | 8         | 9.88%   |
| TigerLake        | 7         | 8.64%   |
| Alderlake Hybrid | 7         | 8.64%   |
| SandyBridge      | 6         | 7.41%   |
| Zen 2            | 5         | 6.17%   |
| IvyBridge        | 4         | 4.94%   |
| CometLake        | 4         | 4.94%   |
| Zen+             | 3         | 3.7%    |
| Skylake          | 3         | 3.7%    |
| Haswell          | 3         | 3.7%    |
| Westmere         | 2         | 2.47%   |
| Icelake          | 2         | 2.47%   |
| Broadwell        | 2         | 2.47%   |
| Zen              | 1         | 1.23%   |
| Penryn           | 1         | 1.23%   |
| P6               | 1         | 1.23%   |
| K10              | 1         | 1.23%   |
| Bonnell          | 1         | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 40.18%  |
| Nvidia | 35        | 31.25%  |
| AMD    | 32        | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 6.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 5.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 5         | 4.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 4.2%    |
| Intel Alder Lake-P Integrated Graphics Controller                             | 5         | 4.2%    |
| AMD Renoir                                                                    | 5         | 4.2%    |
| AMD Rembrandt [Radeon 680M]                                                   | 4         | 3.36%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                    | 3         | 2.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 2.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 3         | 2.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 2.52%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 1.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 1.68%   |
| Nvidia GA104GLM [RTX A3000 12GB Laptop GPU]                                   | 2         | 1.68%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 1.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.68%   |
| Intel HD Graphics 630                                                         | 2         | 1.68%   |
| Intel HD Graphics 5500                                                        | 2         | 1.68%   |
| Intel HD Graphics 530                                                         | 2         | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.68%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 1.68%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 2         | 1.68%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 2         | 1.68%   |
| AMD Lucienne                                                                  | 2         | 1.68%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.84%   |
| Nvidia TU117M                                                                 | 1         | 0.84%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.84%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                         | 1         | 0.84%   |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 0.84%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 0.84%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                      | 1         | 0.84%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 0.84%   |
| Nvidia GM204GLM [Quadro M3000M]                                               | 1         | 0.84%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.84%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.84%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 0.84%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 1         | 0.84%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 22        | 26.83%  |
| 1 x AMD        | 19        | 23.17%  |
| 1 x Intel      | 16        | 19.51%  |
| 1 x Nvidia     | 9         | 10.98%  |
| AMD + Nvidia   | 5         | 6.1%    |
| 2 x AMD        | 4         | 4.88%   |
| Intel + AMD    | 4         | 4.88%   |
| 2 x Intel      | 3         | 3.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 62        | 76.54%  |
| Proprietary | 17        | 20.99%  |
| Unknown     | 2         | 2.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 50.6%   |
| 3.01-4.0   | 9         | 10.84%  |
| 1.01-2.0   | 8         | 9.64%   |
| 0.51-1.0   | 8         | 9.64%   |
| 0.01-0.5   | 8         | 9.64%   |
| 8.01-16.0  | 4         | 4.82%   |
| 7.01-8.0   | 2         | 2.41%   |
| 5.01-6.0   | 2         | 2.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 18        | 19.35%  |
| AU Optronics            | 15        | 16.13%  |
| BOE                     | 12        | 12.9%   |
| LG Display              | 7         | 7.53%   |
| Samsung Electronics     | 5         | 5.38%   |
| Sharp                   | 4         | 4.3%    |
| Dell                    | 4         | 4.3%    |
| PANDA                   | 3         | 3.23%   |
| Goldstar                | 2         | 2.15%   |
| Eizo                    | 2         | 2.15%   |
| CSO                     | 2         | 2.15%   |
| Chi Mei Optoelectronics | 2         | 2.15%   |
| BOE Technology Group    | 2         | 2.15%   |
| ASUSTek Computer        | 2         | 2.15%   |
| Valve                   | 1         | 1.08%   |
| TMX                     | 1         | 1.08%   |
| Sony                    | 1         | 1.08%   |
| Philips                 | 1         | 1.08%   |
| Lenovo                  | 1         | 1.08%   |
| InfoVision              | 1         | 1.08%   |
| Hewlett-Packard         | 1         | 1.08%   |
| ELSA                    | 1         | 1.08%   |
| CTO                     | 1         | 1.08%   |
| BenQ                    | 1         | 1.08%   |
| Apple                   | 1         | 1.08%   |
| AOC                     | 1         | 1.08%   |
| Unknown                 | 1         | 1.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 2         | 2.08%   |
| BOE Technology Group LCD Monitor 1920x1080                            | 2         | 2.08%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 2.08%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.04%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 1.04%   |
| Sony BW8 MS_9001 2560x1600                                            | 1         | 1.04%   |
| Sharp LQ173M1JW03 SHP14DC 1920x1080 382x215mm 17.3-inch               | 1         | 1.04%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 1         | 1.04%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 1.04%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 1.04%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 1.04%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch               | 1         | 1.04%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.04%   |
| LG Display LCD Monitor LGD06D6 1920x1080 309x174mm 14.0-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD058C 1920x1080 344x194mm 15.5-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 1.04%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 1.04%   |
| InfoVision LCD Monitor IVO8C69 1920x1080 309x174mm 14.0-inch          | 1         | 1.04%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch            | 1         | 1.04%   |
| Goldstar ULTRAFINE GSM5BC2 3840x2160 697x392mm 31.5-inch              | 1         | 1.04%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1         | 1.04%   |
| ELSA EL271Q ELS0270 1920x1080 597x336mm 27.0-inch                     | 1         | 1.04%   |
| Eizo FS2434 ENC2635 1920x1080 528x297mm 23.9-inch                     | 1         | 1.04%   |
| Eizo FS2434 ENC2634 1920x1080 528x297mm 23.9-inch                     | 1         | 1.04%   |
| Eizo EV2450 ENC2531 1920x1080 528x297mm 23.9-inch                     | 1         | 1.04%   |
| Dell U2520D DELA150 2560x1440 553x311mm 25.0-inch                     | 1         | 1.04%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 1         | 1.04%   |
| Dell S3422DW DELD104 3440x1440 797x334mm 34.0-inch                    | 1         | 1.04%   |
| Dell S2415H DELA0B5 1920x1080 527x296mm 23.8-inch                     | 1         | 1.04%   |
| Dell P2721Q DELF125 3840x2160 597x336mm 27.0-inch                     | 1         | 1.04%   |
| CTO LCD Monitor CTO3391 1920x1200 286x179mm 13.3-inch                 | 1         | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 49        | 55.06%  |
| 2560x1440 (QHD)   | 8         | 8.99%   |
| 1366x768 (WXGA)   | 7         | 7.87%   |
| 3840x2160 (4K)    | 5         | 5.62%   |
| 2560x1600         | 4         | 4.49%   |
| 1600x900 (HD+)    | 3         | 3.37%   |
| 1920x1200 (WUXGA) | 2         | 2.25%   |
| 800x1280          | 1         | 1.12%   |
| 3840x2400         | 1         | 1.12%   |
| 3456x2160         | 1         | 1.12%   |
| 3440x1440         | 1         | 1.12%   |
| 3200x2000         | 1         | 1.12%   |
| 2520x1680         | 1         | 1.12%   |
| 2160x1440         | 1         | 1.12%   |
| 1920x540          | 1         | 1.12%   |
| 1280x800 (WXGA)   | 1         | 1.12%   |
| 1280x1024 (SXGA)  | 1         | 1.12%   |
| 1024x600          | 1         | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 31        | 32.98%  |
| 17      | 12        | 12.77%  |
| 13      | 12        | 12.77%  |
| 14      | 11        | 11.7%   |
| 27      | 5         | 5.32%   |
| 16      | 5         | 5.32%   |
| 24      | 3         | 3.19%   |
| 23      | 3         | 3.19%   |
| Unknown | 3         | 3.19%   |
| 34      | 1         | 1.06%   |
| 31      | 1         | 1.06%   |
| 25      | 1         | 1.06%   |
| 21      | 1         | 1.06%   |
| 18      | 1         | 1.06%   |
| 12      | 1         | 1.06%   |
| 10      | 1         | 1.06%   |
| 8       | 1         | 1.06%   |
| 7       | 1         | 1.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 56.52%  |
| 351-400     | 12        | 13.04%  |
| 501-600     | 10        | 10.87%  |
| 201-300     | 9         | 9.78%   |
| Unknown     | 3         | 3.26%   |
| 401-500     | 2         | 2.17%   |
| 701-800     | 1         | 1.09%   |
| 601-700     | 1         | 1.09%   |
| 101-200     | 1         | 1.09%   |
| 1-100       | 1         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 65        | 78.31%  |
| 16/10   | 9         | 10.84%  |
| 3/2     | 2         | 2.41%   |
| Unknown | 2         | 2.41%   |
| 5/4     | 1         | 1.2%    |
| 32/9    | 1         | 1.2%    |
| 21/9    | 1         | 1.2%    |
| 0.67    | 1         | 1.2%    |
| 0.62    | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 34.04%  |
| 81-90          | 17        | 18.09%  |
| 121-130        | 11        | 11.7%   |
| 71-80          | 6         | 6.38%   |
| 201-250        | 6         | 6.38%   |
| 301-350        | 5         | 5.32%   |
| 111-120        | 4         | 4.26%   |
| Unknown        | 3         | 3.19%   |
| 351-500        | 2         | 2.13%   |
| 1-40           | 2         | 2.13%   |
| 141-150        | 2         | 2.13%   |
| 61-70          | 1         | 1.06%   |
| 41-50          | 1         | 1.06%   |
| 251-300        | 1         | 1.06%   |
| 91-100         | 1         | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 44        | 47.83%  |
| 161-240       | 15        | 16.3%   |
| 101-120       | 12        | 13.04%  |
| 51-100        | 11        | 11.96%  |
| More than 240 | 7         | 7.61%   |
| Unknown       | 3         | 3.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 66        | 79.52%  |
| 2     | 11        | 13.25%  |
| 3     | 4         | 4.82%   |
| 0     | 2         | 2.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 40.31%  |
| Realtek Semiconductor | 43        | 33.33%  |
| MediaTek              | 7         | 5.43%   |
| Qualcomm Atheros      | 6         | 4.65%   |
| Xiaomi                | 4         | 3.1%    |
| Qualcomm              | 3         | 2.33%   |
| Broadcom              | 3         | 2.33%   |
| Broadcom Limited      | 2         | 1.55%   |
| ASIX Electronics      | 2         | 1.55%   |
| Sierra Wireless       | 1         | 0.78%   |
| Samsung Electronics   | 1         | 0.78%   |
| Lenovo                | 1         | 0.78%   |
| ICS Advent            | 1         | 0.78%   |
| Edimax Technology     | 1         | 0.78%   |
| Dell                  | 1         | 0.78%   |
| Arduino SA            | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 28        | 17.83%  |
| Intel Wi-Fi 6 AX200                                                     | 12        | 7.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 3.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 3.18%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 3.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 2.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.55%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 2.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.91%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 1.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 1.91%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 1.91%   |
| Intel Wireless 8260                                                     | 3         | 1.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.91%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.91%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.91%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 1.27%   |
| Intel Ethernet Connection (17) I219-LM                                  | 2         | 1.27%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.27%   |
| ASIX AX88179 Gigabit Ethernet                                           | 2         | 1.27%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.64%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                  | 1         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.64%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 59.52%  |
| Realtek Semiconductor | 11        | 13.1%   |
| MediaTek              | 7         | 8.33%   |
| Qualcomm Atheros      | 5         | 5.95%   |
| Qualcomm              | 3         | 3.57%   |
| Broadcom              | 3         | 3.57%   |
| Broadcom Limited      | 2         | 2.38%   |
| Sierra Wireless       | 1         | 1.19%   |
| Edimax Technology     | 1         | 1.19%   |
| Dell                  | 1         | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 12        | 14.29%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 7.14%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 5.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.76%   |
| Intel Wireless 8265 / 8275                                              | 4         | 4.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 4.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 3.57%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 3.57%   |
| Intel Wireless 8260                                                     | 3         | 3.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 3.57%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 3.57%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 2.38%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.38%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.19%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                  | 1         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.19%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.19%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.19%   |
| Intel Wireless 7265                                                     | 1         | 1.19%   |
| Intel Wireless 7260                                                     | 1         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.19%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.19%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.19%   |
| Dell Hub of E-Port Replicator                                           | 1         | 1.19%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.19%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.19%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 39        | 55.71%  |
| Intel                 | 20        | 28.57%  |
| Xiaomi                | 4         | 5.71%   |
| Qualcomm Atheros      | 2         | 2.86%   |
| ASIX Electronics      | 2         | 2.86%   |
| Samsung Electronics   | 1         | 1.43%   |
| Lenovo                | 1         | 1.43%   |
| ICS Advent            | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 38.89%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 6.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.17%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 2.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.78%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 2.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.39%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.39%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 1.39%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.39%   |
| Intel Ethernet Controller (2) I225-LMvP                           | 1         | 1.39%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.39%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.39%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.39%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.39%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.39%   |
| ICS Advent 10/100M LAN                                            | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 81        | 55.1%   |
| Ethernet | 65        | 44.22%  |
| Modem    | 1         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 71.43%  |
| Ethernet | 24        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 54        | 65.85%  |
| 1     | 24        | 29.27%  |
| 3     | 3         | 3.66%   |
| 0     | 1         | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 71.95%  |
| Yes  | 23        | 28.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 44        | 60.27%  |
| Realtek Semiconductor   | 6         | 8.22%   |
| IMC Networks            | 5         | 6.85%   |
| USI                     | 3         | 4.11%   |
| Lite-On Technology      | 3         | 4.11%   |
| Foxconn / Hon Hai       | 3         | 4.11%   |
| Broadcom                | 3         | 4.11%   |
| Realtek                 | 2         | 2.74%   |
| Dell                    | 1         | 1.37%   |
| Cambridge Silicon Radio | 1         | 1.37%   |
| Apple                   | 1         | 1.37%   |
| Alps Electric           | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 12        | 16.44%  |
| Intel Bluetooth wireless interface                  | 9         | 12.33%  |
| Intel AX201 Bluetooth                               | 8         | 10.96%  |
| Realtek Bluetooth Radio                             | 6         | 8.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 6.85%   |
| Intel Bluetooth Device                              | 5         | 6.85%   |
| IMC Networks Wireless_Device                        | 4         | 5.48%   |
| USI Bluetooth Device                                | 3         | 4.11%   |
| Intel AX210 Bluetooth                               | 3         | 4.11%   |
| Realtek Bluetooth Radio                             | 2         | 2.74%   |
| Broadcom HP Portable SoftSailing                    | 2         | 2.74%   |
| Lite-On Wireless_Device                             | 1         | 1.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.37%   |
| Lite-On Bluetooth Device                            | 1         | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.37%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.37%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.37%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1         | 1.37%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.37%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.37%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.37%   |
| Apple Bluetooth Host Controller                     | 1         | 1.37%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 54        | 46.15%  |
| AMD                 | 29        | 24.79%  |
| Nvidia              | 26        | 22.22%  |
| Lenovo              | 2         | 1.71%   |
| ASUSTek Computer    | 2         | 1.71%   |
| Razer USA           | 1         | 0.85%   |
| Kingston Technology | 1         | 0.85%   |
| C-Media Electronics | 1         | 0.85%   |
| AudioQuest          | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 16.67%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 9.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 4.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.67%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 3.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 3.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 3.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 2.67%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 2.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.67%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 2%      |
| Intel CM238 HD Audio Controller                                            | 3         | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 1.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.33%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.33%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.33%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.67%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.67%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.67%   |
| Nvidia Audio device                                                        | 1         | 0.67%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 0.67%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 33.33%  |
| SK hynix            | 22        | 24.44%  |
| Micron Technology   | 14        | 15.56%  |
| Crucial             | 6         | 6.67%   |
| Unknown             | 4         | 4.44%   |
| G.Skill             | 3         | 3.33%   |
| Corsair             | 3         | 3.33%   |
| Nanya Technology    | 2         | 2.22%   |
| Elpida              | 2         | 2.22%   |
| Team                | 1         | 1.11%   |
| Patriot             | 1         | 1.11%   |
| Kingston            | 1         | 1.11%   |
| GSkill              | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 4         | 4.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 3.23%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s     | 3         | 3.23%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s       | 2         | 2.15%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 2.15%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 2.15%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s   | 2         | 2.15%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s   | 2         | 2.15%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.15%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 2         | 2.15%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 2.15%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 2         | 2.15%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s         | 2         | 2.15%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 1.08%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.08%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.08%   |
| Unknown RAM Module 1GB SODIMM DDR2                           | 1         | 1.08%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s        | 1         | 1.08%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.08%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 1.08%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 1.08%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 1.08%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.08%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 1.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 1.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 1         | 1.08%   |
| SK hynix RAM HMA82GS7AFR8N-UH 16GB SODIMM DDR4 2400MT/s      | 1         | 1.08%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.08%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.08%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.08%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.08%   |
| Samsung RAM M471B5173BH0-CK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.08%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 1         | 1.08%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 53.85%  |
| DDR3   | 18        | 23.08%  |
| DDR5   | 7         | 8.97%   |
| LPDDR4 | 5         | 6.41%   |
| LPDDR5 | 3         | 3.85%   |
| DDR2   | 2         | 2.56%   |
| LPDDR3 | 1         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 86.08%  |
| Row Of Chips | 10        | 12.66%  |
| DIMM         | 1         | 1.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 33        | 39.29%  |
| 16384 | 18        | 21.43%  |
| 4096  | 18        | 21.43%  |
| 32768 | 8         | 9.52%   |
| 2048  | 6         | 7.14%   |
| 1024  | 1         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 27        | 33.33%  |
| 1600    | 12        | 14.81%  |
| 2667    | 11        | 13.58%  |
| 4800    | 7         | 8.64%   |
| 4267    | 5         | 6.17%   |
| 2400    | 4         | 4.94%   |
| 6400    | 3         | 3.7%    |
| 1334    | 3         | 3.7%    |
| 2133    | 2         | 2.47%   |
| 1333    | 2         | 2.47%   |
| 8400    | 1         | 1.23%   |
| 3600    | 1         | 1.23%   |
| 1067    | 1         | 1.23%   |
| 533     | 1         | 1.23%   |
| Unknown | 1         | 1.23%   |

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
| Chicony Electronics           | 19        | 27.94%  |
| Microdia                      | 10        | 14.71%  |
| Quanta                        | 5         | 7.35%   |
| Luxvisions Innotech Limited   | 5         | 7.35%   |
| IMC Networks                  | 5         | 7.35%   |
| Bison Electronics             | 4         | 5.88%   |
| Sunplus Innovation Technology | 3         | 4.41%   |
| Realtek Semiconductor         | 2         | 2.94%   |
| Logitech                      | 2         | 2.94%   |
| Apple                         | 2         | 2.94%   |
| Suyin                         | 1         | 1.47%   |
| SunplusIT                     | 1         | 1.47%   |
| Sunplus Technology            | 1         | 1.47%   |
| Silicon Motion                | 1         | 1.47%   |
| ShineTech                     | 1         | 1.47%   |
| Microsoft                     | 1         | 1.47%   |
| Lite-On Technology            | 1         | 1.47%   |
| kingcome                      | 1         | 1.47%   |
| Holitech                      | 1         | 1.47%   |
| Genesys Logic                 | 1         | 1.47%   |
| Acer                          | 1         | 1.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 8         | 11.76%  |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 5.88%   |
| Microdia Integrated_Webcam_HD                        | 3         | 4.41%   |
| Microdia Integrated_Webcam_FHD                       | 3         | 4.41%   |
| Quanta HD User Facing                                | 2         | 2.94%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 2         | 2.94%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 2.94%   |
| Chicony HP HD Camera                                 | 2         | 2.94%   |
| Chicony HD WebCam                                    | 2         | 2.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 2         | 2.94%   |
| Suyin HP Truevision HD                               | 1         | 1.47%   |
| SunplusIT 720p HD Camera                             | 1         | 1.47%   |
| Sunplus 1.3M HD WebCam                               | 1         | 1.47%   |
| Sunplus XiaoMi USB 2.0 Webcam                        | 1         | 1.47%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.47%   |
| Sunplus Integrated_Webcam_FHD                        | 1         | 1.47%   |
| Silicon Motion 300k Pixel Camera                     | 1         | 1.47%   |
| ShineTech HD Camera                                  | 1         | 1.47%   |
| Realtek USB Camera                                   | 1         | 1.47%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.47%   |
| Quanta VGA WebCam                                    | 1         | 1.47%   |
| Quanta HP TrueVision HD Camera                       | 1         | 1.47%   |
| Quanta hm1091_techfront                              | 1         | 1.47%   |
| Microsoft MicrosoftÂ LifeCam Cinema                 | 1         | 1.47%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.47%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam       | 1         | 1.47%   |
| Microdia REDRAGON Live Camera Audio                  | 1         | 1.47%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.47%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.47%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.47%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.47%   |
| Lite-On HP HD Camera                                 | 1         | 1.47%   |
| kingcome 720p HD Camera                              | 1         | 1.47%   |
| IMC Networks ov9734_azurewave_camera                 | 1         | 1.47%   |
| Holitech USB2.0 HD UVC WebCam                        | 1         | 1.47%   |
| Genesys Logic Digital Microscope                     | 1         | 1.47%   |
| Chicony Webcam-101                                   | 1         | 1.47%   |
| Chicony TOSHIBA Web Camera - HD                      | 1         | 1.47%   |
| Chicony Lenovo EasyCamera                            | 1         | 1.47%   |
| Chicony HP Wide Vision HD                            | 1         | 1.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 38.89%  |
| Synaptics                  | 6         | 33.33%  |
| Shenzhen Goodix Technology | 4         | 22.22%  |
| LighTuning Technology      | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                        | 4         | 22.22%  |
| Synaptics UWP WBDI Device                                  | 3         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 11.11%  |
| Validity Sensors Synaptics WBDI                            | 2         | 11.11%  |
| Validity Sensors Fingerprint scanner                       | 2         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 11.11%  |
| Validity Sensors VFS491                                    | 1         | 5.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 50%     |
| Alcor Micro | 3         | 30%     |
| O2 Micro    | 1         | 10%     |
| Clay Logic  | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 3         | 30%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 30%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Clay Logic Nitrokey Pro                                                      | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 35        | 41.18%  |
| 1     | 25        | 29.41%  |
| 2     | 8         | 9.41%   |
| 4     | 6         | 7.06%   |
| 3     | 6         | 7.06%   |
| 5     | 3         | 3.53%   |
| 6     | 2         | 2.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 17.35%  |
| Bluetooth                | 16        | 16.33%  |
| Graphics card            | 14        | 14.29%  |
| Camera                   | 12        | 12.24%  |
| Multimedia controller    | 9         | 9.18%   |
| Chipcard                 | 9         | 9.18%   |
| Net/wireless             | 8         | 8.16%   |
| Communication controller | 7         | 7.14%   |
| Sound                    | 3         | 3.06%   |
| Card reader              | 2         | 2.04%   |
| Network                  | 1         | 1.02%   |


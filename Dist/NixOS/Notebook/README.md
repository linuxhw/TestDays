NixOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

Total: 810

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga Pro 7 14AKP10 83KG     | [edc589aee0](https://linux-hardware.org/?probe=edc589aee0) | Jan 03, 2026 |
| MSI           | B450M BAZOOKA MAX WIFI      | [7a3b401066](https://linux-hardware.org/?probe=7a3b401066) | Jan 01, 2026 |
| HP            | EliteBook 855 G8 Noteboo... | [d966eaa4db](https://linux-hardware.org/?probe=d966eaa4db) | Jan 01, 2026 |
| HP            | ENVY TS 15                  | [bfb610c8d2](https://linux-hardware.org/?probe=bfb610c8d2) | Dec 31, 2025 |
| HP            | EliteBook 840 G3            | [4afb089451](https://linux-hardware.org/?probe=4afb089451) | Dec 29, 2025 |
| HUAWEI        | MDF-XX                      | [d168addfd2](https://linux-hardware.org/?probe=d168addfd2) | Dec 28, 2025 |
| Alienware     | 16X Aurora AC16251          | [841ce2264d](https://linux-hardware.org/?probe=841ce2264d) | Dec 27, 2025 |
| Framework     | Laptop 13 (AMD Ryzen AI ... | [584690970f](https://linux-hardware.org/?probe=584690970f) | Dec 26, 2025 |
| Lenovo        | ThinkPad T490 20N3S64000    | [f93206844c](https://linux-hardware.org/?probe=f93206844c) | Dec 26, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [5a928c58ee](https://linux-hardware.org/?probe=5a928c58ee) | Dec 25, 2025 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [0baaeb9bc9](https://linux-hardware.org/?probe=0baaeb9bc9) | Dec 25, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [1b81a103ac](https://linux-hardware.org/?probe=1b81a103ac) | Dec 24, 2025 |
| Acer          | Aspire 7750ZG               | [d91ab9d5c0](https://linux-hardware.org/?probe=d91ab9d5c0) | Dec 24, 2025 |
| Dell          | XPS 9320                    | [42f3e12a5b](https://linux-hardware.org/?probe=42f3e12a5b) | Dec 21, 2025 |
| Dell          | XPS 13 9360                 | [d6cab5950f](https://linux-hardware.org/?probe=d6cab5950f) | Dec 21, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [d4b3104c88](https://linux-hardware.org/?probe=d4b3104c88) | Dec 20, 2025 |
| Lenovo        | ThinkBook 14 G7+ ASP 21Q... | [2c3b0e220b](https://linux-hardware.org/?probe=2c3b0e220b) | Dec 16, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [c4539640af](https://linux-hardware.org/?probe=c4539640af) | Dec 16, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f4148167f2](https://linux-hardware.org/?probe=f4148167f2) | Dec 13, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [d6851aa06f](https://linux-hardware.org/?probe=d6851aa06f) | Dec 12, 2025 |
| Acer          | AOD270                      | [0705275e8c](https://linux-hardware.org/?probe=0705275e8c) | Dec 12, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | [c2257a2e4d](https://linux-hardware.org/?probe=c2257a2e4d) | Dec 11, 2025 |
| Dell          | XPS 15 9520                 | [4e3150adf5](https://linux-hardware.org/?probe=4e3150adf5) | Dec 10, 2025 |
| Lenovo        | Yoga Pro 7 14AKP10 83KG     | [4552d0c2aa](https://linux-hardware.org/?probe=4552d0c2aa) | Dec 09, 2025 |
| Lenovo        | ThinkBook 14 G7+ ASP 21Q... | [276308b156](https://linux-hardware.org/?probe=276308b156) | Dec 09, 2025 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | [39ddbe5930](https://linux-hardware.org/?probe=39ddbe5930) | Dec 09, 2025 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [8b01aac7b4](https://linux-hardware.org/?probe=8b01aac7b4) | Dec 08, 2025 |
| Apple         | MacBookAir9,1               | [850efc3c46](https://linux-hardware.org/?probe=850efc3c46) | Dec 07, 2025 |
| Lenovo        | ThinkPad X250 20CLS78N00    | [11106583c4](https://linux-hardware.org/?probe=11106583c4) | Dec 07, 2025 |
| Framework     | Laptop (13th Gen Intel C... | [e4b0af63ab](https://linux-hardware.org/?probe=e4b0af63ab) | Dec 07, 2025 |
| HUAWEI        | HVY-WXX9                    | [82c933cd15](https://linux-hardware.org/?probe=82c933cd15) | Dec 07, 2025 |
| Acer          | Nitro AN515-45              | [0fe5be90d4](https://linux-hardware.org/?probe=0fe5be90d4) | Dec 06, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [3ddb77ec99](https://linux-hardware.org/?probe=3ddb77ec99) | Dec 06, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [4d4406ff68](https://linux-hardware.org/?probe=4d4406ff68) | Dec 06, 2025 |
| HP            | OMEN by Gaming Laptop 16... | [377e5eb19e](https://linux-hardware.org/?probe=377e5eb19e) | Dec 06, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [78367b63d2](https://linux-hardware.org/?probe=78367b63d2) | Dec 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [8310635b74](https://linux-hardware.org/?probe=8310635b74) | Dec 03, 2025 |
| HP            | OmniBook Ultra Laptop 14... | [7463166445](https://linux-hardware.org/?probe=7463166445) | Dec 03, 2025 |
| Timi          | TM1701                      | [0fd10cdb5e](https://linux-hardware.org/?probe=0fd10cdb5e) | Dec 03, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [a4c0b80f77](https://linux-hardware.org/?probe=a4c0b80f77) | Dec 03, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [6cddb5814e](https://linux-hardware.org/?probe=6cddb5814e) | Dec 01, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [0331177d7a](https://linux-hardware.org/?probe=0331177d7a) | Nov 29, 2025 |
| Apple         | MacBook10,1                 | [7828326f0c](https://linux-hardware.org/?probe=7828326f0c) | Nov 27, 2025 |
| HONOR         | FRI-HXX                     | [08706b033a](https://linux-hardware.org/?probe=08706b033a) | Nov 26, 2025 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [0fb9f5057e](https://linux-hardware.org/?probe=0fb9f5057e) | Nov 24, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [48afe7dc29](https://linux-hardware.org/?probe=48afe7dc29) | Nov 20, 2025 |
| HP            | EliteBook 855 G7 Noteboo... | [d268f7d786](https://linux-hardware.org/?probe=d268f7d786) | Nov 19, 2025 |
| TUXEDO        | Pulse 14 Gen4               | [293e9fd05d](https://linux-hardware.org/?probe=293e9fd05d) | Nov 17, 2025 |
| Casper        | EXCALIBUR G770              | [1028580712](https://linux-hardware.org/?probe=1028580712) | Nov 16, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [c9a95e4f34](https://linux-hardware.org/?probe=c9a95e4f34) | Nov 15, 2025 |
| Acer          | Nitro AN515-58              | [1e67beafb2](https://linux-hardware.org/?probe=1e67beafb2) | Nov 12, 2025 |
| HP            | EliteBook 855 G7 Noteboo... | [1e5665630f](https://linux-hardware.org/?probe=1e5665630f) | Nov 12, 2025 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [a723a6a441](https://linux-hardware.org/?probe=a723a6a441) | Nov 11, 2025 |
| MSI           | GP60 2QF                    | [393e5011b1](https://linux-hardware.org/?probe=393e5011b1) | Nov 09, 2025 |
| Dell          | XPS 15 9570                 | [5a34471f10](https://linux-hardware.org/?probe=5a34471f10) | Nov 06, 2025 |
| Dell          | XPS 15 9570                 | [45335b5277](https://linux-hardware.org/?probe=45335b5277) | Nov 06, 2025 |
| IT Channel... | NH5x_7xEDx,RCx,RDx          | [fc599d83eb](https://linux-hardware.org/?probe=fc599d83eb) | Nov 02, 2025 |
| ASUSTek       | ASUS Zenbook 14 UM3406HA... | [0b400e7ba0](https://linux-hardware.org/?probe=0b400e7ba0) | Oct 27, 2025 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [1599bb6750](https://linux-hardware.org/?probe=1599bb6750) | Oct 26, 2025 |
| HP            | Victus by Laptop 16-d0xx... | [9a701184f8](https://linux-hardware.org/?probe=9a701184f8) | Oct 25, 2025 |
| HP            | Victus by Gaming Laptop ... | [81e1973822](https://linux-hardware.org/?probe=81e1973822) | Oct 23, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ca00cff375](https://linux-hardware.org/?probe=ca00cff375) | Oct 23, 2025 |
| HP            | 250 15.6 inch G9 Noteboo... | [f1c7c84c88](https://linux-hardware.org/?probe=f1c7c84c88) | Oct 23, 2025 |
| Dell          | XPS 15 9570                 | [e90104aa30](https://linux-hardware.org/?probe=e90104aa30) | Oct 21, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [9bab3c0d27](https://linux-hardware.org/?probe=9bab3c0d27) | Oct 18, 2025 |
| Dell          | XPS 15 9570                 | [873f1297b2](https://linux-hardware.org/?probe=873f1297b2) | Oct 17, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9d83d4183e](https://linux-hardware.org/?probe=9d83d4183e) | Oct 15, 2025 |
| Dell          | Precision 5560              | [4e5d82046b](https://linux-hardware.org/?probe=4e5d82046b) | Oct 15, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4e828982c9](https://linux-hardware.org/?probe=4e828982c9) | Oct 15, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [39923e202a](https://linux-hardware.org/?probe=39923e202a) | Oct 15, 2025 |
| Dell          | Inspiron 14 5440            | [4f63aec401](https://linux-hardware.org/?probe=4f63aec401) | Oct 15, 2025 |
| Dell          | Inspiron 14 5440            | [b9438f806f](https://linux-hardware.org/?probe=b9438f806f) | Oct 15, 2025 |
| Unknown       | Unknown                     | [9ac985ec78](https://linux-hardware.org/?probe=9ac985ec78) | Oct 14, 2025 |
| ASUSTek       | ZenBook Pro Duo UX582ZM_... | [ce4beb33f9](https://linux-hardware.org/?probe=ce4beb33f9) | Oct 12, 2025 |
| HP            | Pavilion Laptop 15-eg100    | [b9e72af19d](https://linux-hardware.org/?probe=b9e72af19d) | Oct 10, 2025 |
| Dell          | XPS 15 9570                 | [c481e5f842](https://linux-hardware.org/?probe=c481e5f842) | Oct 10, 2025 |
| Lenovo        | G50-80 80E5                 | [e2ac1616ee](https://linux-hardware.org/?probe=e2ac1616ee) | Oct 09, 2025 |
| HUAWEI        | VGHH-XX                     | [fd64e58a18](https://linux-hardware.org/?probe=fd64e58a18) | Oct 06, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [b162c12f9b](https://linux-hardware.org/?probe=b162c12f9b) | Oct 02, 2025 |
| Acer          | Nitro AN515-46              | [4fa0e63acb](https://linux-hardware.org/?probe=4fa0e63acb) | Oct 01, 2025 |
| Toshiba       | IS-1462                     | [c545674c73](https://linux-hardware.org/?probe=c545674c73) | Sep 29, 2025 |
| ASUSTek       | X751LAB                     | [689d08acec](https://linux-hardware.org/?probe=689d08acec) | Sep 28, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [6440969cb1](https://linux-hardware.org/?probe=6440969cb1) | Sep 28, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [76808f5ee3](https://linux-hardware.org/?probe=76808f5ee3) | Sep 26, 2025 |
| Lenovo        | Yoga Pro 7 14IAH10 83KF     | [f94fced166](https://linux-hardware.org/?probe=f94fced166) | Sep 25, 2025 |
| Google        | Jinlon                      | [f2dbc6e2bc](https://linux-hardware.org/?probe=f2dbc6e2bc) | Sep 24, 2025 |
| HONOR         | FRI-HXX                     | [dc447f5149](https://linux-hardware.org/?probe=dc447f5149) | Sep 24, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d17492fca0](https://linux-hardware.org/?probe=d17492fca0) | Sep 22, 2025 |
| Lenovo        | ThinkPad X280 20KF001HIV    | [bb0c43da1d](https://linux-hardware.org/?probe=bb0c43da1d) | Sep 21, 2025 |
| HP            | OMEN Laptop 15-en1xxx       | [f54a9e39f6](https://linux-hardware.org/?probe=f54a9e39f6) | Sep 20, 2025 |
| SLIMBOOK      | HERO-RPL-RTX                | [c8b23b79d6](https://linux-hardware.org/?probe=c8b23b79d6) | Sep 20, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [081027cab8](https://linux-hardware.org/?probe=081027cab8) | Sep 19, 2025 |
| Lenovo        | ThinkPad L380 Yoga 20M7S... | [93eb90f7ec](https://linux-hardware.org/?probe=93eb90f7ec) | Sep 19, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [739e1d9d8f](https://linux-hardware.org/?probe=739e1d9d8f) | Sep 17, 2025 |
| Lenovo        | ThinkBook X G2 IAH 21TU     | [bea3a76385](https://linux-hardware.org/?probe=bea3a76385) | Sep 17, 2025 |
| ASUSTek       | ZenBook Pro Duo UX582ZM_... | [61775de04a](https://linux-hardware.org/?probe=61775de04a) | Sep 17, 2025 |
| Framework     | Laptop                      | [aa9d79982f](https://linux-hardware.org/?probe=aa9d79982f) | Sep 14, 2025 |
| HP            | Pavilion 15                 | [5513973630](https://linux-hardware.org/?probe=5513973630) | Sep 13, 2025 |
| Dell          | Latitude 5450               | [e68170b5d0](https://linux-hardware.org/?probe=e68170b5d0) | Sep 12, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [fca82d34a4](https://linux-hardware.org/?probe=fca82d34a4) | Sep 11, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | [0ac959506f](https://linux-hardware.org/?probe=0ac959506f) | Sep 10, 2025 |
| HP            | Pavilion Laptop 15-eg100    | [dbbdaa39b8](https://linux-hardware.org/?probe=dbbdaa39b8) | Sep 09, 2025 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [da0dcd0ea1](https://linux-hardware.org/?probe=da0dcd0ea1) | Sep 09, 2025 |
| MSI           | Alpha 15 B5EEK              | [2dc9392182](https://linux-hardware.org/?probe=2dc9392182) | Sep 08, 2025 |
| Lenovo        | ThinkPad T480 20L6S04000    | [956334c969](https://linux-hardware.org/?probe=956334c969) | Sep 08, 2025 |
| HP            | Pavilion Laptop 15-eg100    | [c2422ea14a](https://linux-hardware.org/?probe=c2422ea14a) | Sep 07, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [583e4debcd](https://linux-hardware.org/?probe=583e4debcd) | Sep 05, 2025 |
| XIAOMI        | Redmi Book Pro 15 2023      | [1c72f56d8d](https://linux-hardware.org/?probe=1c72f56d8d) | Sep 04, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [aabb572570](https://linux-hardware.org/?probe=aabb572570) | Aug 27, 2025 |
| HONOR         | BMH-WDX9                    | [9bdf195339](https://linux-hardware.org/?probe=9bdf195339) | Aug 25, 2025 |
| Google        | Jinlon                      | [c92df5e23b](https://linux-hardware.org/?probe=c92df5e23b) | Aug 25, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [c54fe13da6](https://linux-hardware.org/?probe=c54fe13da6) | Aug 22, 2025 |
| Lenovo        | IdeaPad Z560 0914           | [e16f46ec1c](https://linux-hardware.org/?probe=e16f46ec1c) | Aug 16, 2025 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [f4c9cb9661](https://linux-hardware.org/?probe=f4c9cb9661) | Aug 15, 2025 |
| HP            | ZBook Ultra G1a 14 inch ... | [75f2f20672](https://linux-hardware.org/?probe=75f2f20672) | Aug 13, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [831a1ebf42](https://linux-hardware.org/?probe=831a1ebf42) | Aug 13, 2025 |
| Dell          | Pro 14 Plus PB14255         | [5fef8a90c9](https://linux-hardware.org/?probe=5fef8a90c9) | Aug 12, 2025 |
| Dell          | Pro 14 Plus PB14255         | [6c65058ea8](https://linux-hardware.org/?probe=6c65058ea8) | Aug 12, 2025 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [9dd6c3f028](https://linux-hardware.org/?probe=9dd6c3f028) | Aug 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [107a9184d2](https://linux-hardware.org/?probe=107a9184d2) | Aug 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [643268677f](https://linux-hardware.org/?probe=643268677f) | Aug 05, 2025 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [2ef145f349](https://linux-hardware.org/?probe=2ef145f349) | Aug 01, 2025 |
| Timi          | Redmi Book Pro 14 2022      | [f178df6629](https://linux-hardware.org/?probe=f178df6629) | Aug 01, 2025 |
| Lenovo        | ThinkPad T440 20B7000WUS    | [ecd27a6f01](https://linux-hardware.org/?probe=ecd27a6f01) | Jul 31, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [3ebd7d23d0](https://linux-hardware.org/?probe=3ebd7d23d0) | Jul 30, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [62f44f6c6b](https://linux-hardware.org/?probe=62f44f6c6b) | Jul 29, 2025 |
| Dell          | Inspiron 5767               | [e31117e688](https://linux-hardware.org/?probe=e31117e688) | Jul 28, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [3f690161be](https://linux-hardware.org/?probe=3f690161be) | Jul 27, 2025 |
| Dell          | XPS 9315                    | [cabf09323e](https://linux-hardware.org/?probe=cabf09323e) | Jul 27, 2025 |
| HP            | ProBook 450 G3              | [5d185ca929](https://linux-hardware.org/?probe=5d185ca929) | Jul 24, 2025 |
| HP            | ProBook 450 G3              | [c50bd4247e](https://linux-hardware.org/?probe=c50bd4247e) | Jul 24, 2025 |
| Apple         | MacBookAir6,2               | [1c718e02dd](https://linux-hardware.org/?probe=1c718e02dd) | Jul 23, 2025 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [e779601bb3](https://linux-hardware.org/?probe=e779601bb3) | Jul 22, 2025 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [1eab1af538](https://linux-hardware.org/?probe=1eab1af538) | Jul 21, 2025 |
| HP            | ZBook Ultra G1a 14 inch ... | [eea49d9def](https://linux-hardware.org/?probe=eea49d9def) | Jul 21, 2025 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [9eff834a0a](https://linux-hardware.org/?probe=9eff834a0a) | Jul 18, 2025 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [6264caf2b6](https://linux-hardware.org/?probe=6264caf2b6) | Jul 15, 2025 |
| Apple         | MacBookAir6,2               | [670fca5b0c](https://linux-hardware.org/?probe=670fca5b0c) | Jul 07, 2025 |
| Lenovo        | XiaoXinPro 14 IAH10 83JK    | [104eb72159](https://linux-hardware.org/?probe=104eb72159) | Jul 07, 2025 |
| HP            | EliteBook X G1a 14 inch ... | [b1f335663f](https://linux-hardware.org/?probe=b1f335663f) | Jul 03, 2025 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [fdd424b69b](https://linux-hardware.org/?probe=fdd424b69b) | Jul 03, 2025 |
| Dell          | Latitude 7330 Rugged Ext... | [1ecd360930](https://linux-hardware.org/?probe=1ecd360930) | Jun 28, 2025 |
| Dell          | Latitude 7330 Rugged Ext... | [ba548690d0](https://linux-hardware.org/?probe=ba548690d0) | Jun 28, 2025 |
| Apple         | MacBookPro9,2               | [1f09f16866](https://linux-hardware.org/?probe=1f09f16866) | Jun 27, 2025 |
| Dell          | Latitude 7330 Rugged Ext... | [2e1dfd5dc9](https://linux-hardware.org/?probe=2e1dfd5dc9) | Jun 27, 2025 |
| Maibenben     | Business Style              | [92b51e42de](https://linux-hardware.org/?probe=92b51e42de) | Jun 26, 2025 |
| Toshiba       | Satellite P50-A             | [e058f6f756](https://linux-hardware.org/?probe=e058f6f756) | Jun 26, 2025 |
| HP            | Casablanca H710             | [b8efd38b1f](https://linux-hardware.org/?probe=b8efd38b1f) | Jun 24, 2025 |
| HP            | Casablanca H710             | [16148a0270](https://linux-hardware.org/?probe=16148a0270) | Jun 24, 2025 |
| Star Labs     | StarBook                    | [03113167fa](https://linux-hardware.org/?probe=03113167fa) | Jun 18, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a6f4321da2](https://linux-hardware.org/?probe=a6f4321da2) | Jun 17, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [83a35b99e4](https://linux-hardware.org/?probe=83a35b99e4) | Jun 14, 2025 |
| Lenovo        | ThinkPad S5 Yoga 15 20DQ... | [8c4a93c28d](https://linux-hardware.org/?probe=8c4a93c28d) | Jun 14, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [14bf557fb9](https://linux-hardware.org/?probe=14bf557fb9) | Jun 13, 2025 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [f3ae3cbdea](https://linux-hardware.org/?probe=f3ae3cbdea) | Jun 12, 2025 |
| Lenovo        | ThinkBook X G2 IAH 21TU     | [a5c185d3d3](https://linux-hardware.org/?probe=a5c185d3d3) | Jun 11, 2025 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [6431202732](https://linux-hardware.org/?probe=6431202732) | Jun 11, 2025 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [1752a9fe93](https://linux-hardware.org/?probe=1752a9fe93) | Jun 11, 2025 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [057ea6a2cd](https://linux-hardware.org/?probe=057ea6a2cd) | Jun 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [854cfb5e7a](https://linux-hardware.org/?probe=854cfb5e7a) | Jun 10, 2025 |
| Lenovo        | ThinkPad T480 20L6S29E25    | [3339901412](https://linux-hardware.org/?probe=3339901412) | Jun 10, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [21d77047f8](https://linux-hardware.org/?probe=21d77047f8) | Jun 09, 2025 |
| Gigabyte      | AERO 15 KD                  | [5ea03ba828](https://linux-hardware.org/?probe=5ea03ba828) | Jun 09, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21AJ0... | [127f3adaf4](https://linux-hardware.org/?probe=127f3adaf4) | Jun 09, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [8c03c5fb14](https://linux-hardware.org/?probe=8c03c5fb14) | Jun 08, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [93129aa44b](https://linux-hardware.org/?probe=93129aa44b) | Jun 06, 2025 |
| HP            | EliteBook X G1a 14 inch ... | [50f035192e](https://linux-hardware.org/?probe=50f035192e) | Jun 06, 2025 |
| HP            | Pavilion Laptop 15-cs0xx... | [3a0365d7ee](https://linux-hardware.org/?probe=3a0365d7ee) | Jun 04, 2025 |
| Acer          | Aspire F5-573G              | [d6d7b937b7](https://linux-hardware.org/?probe=d6d7b937b7) | Jun 03, 2025 |
| HP            | EliteBook 2760p             | [cc394c851e](https://linux-hardware.org/?probe=cc394c851e) | Jun 03, 2025 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [b8e9137b79](https://linux-hardware.org/?probe=b8e9137b79) | Jun 03, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8ca4eb3d77](https://linux-hardware.org/?probe=8ca4eb3d77) | Jun 01, 2025 |
| Lenovo        | Legion Y540-15IRH 81SX      | [cdc559bde7](https://linux-hardware.org/?probe=cdc559bde7) | May 31, 2025 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [40d8ccfd05](https://linux-hardware.org/?probe=40d8ccfd05) | May 30, 2025 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [e83cd00959](https://linux-hardware.org/?probe=e83cd00959) | May 29, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [f3fb213141](https://linux-hardware.org/?probe=f3fb213141) | May 27, 2025 |
| Framework     | Laptop 13 (AMD Ryzen AI ... | [d3025cf660](https://linux-hardware.org/?probe=d3025cf660) | May 25, 2025 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [2b7b773af0](https://linux-hardware.org/?probe=2b7b773af0) | May 24, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [445fb4a269](https://linux-hardware.org/?probe=445fb4a269) | May 24, 2025 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [45461181ba](https://linux-hardware.org/?probe=45461181ba) | May 23, 2025 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7f5c21ffe7](https://linux-hardware.org/?probe=7f5c21ffe7) | May 23, 2025 |
| Fujitsu       | LIFEBOOK T901               | [b4586ec9c3](https://linux-hardware.org/?probe=b4586ec9c3) | May 17, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [3d27df6c79](https://linux-hardware.org/?probe=3d27df6c79) | May 15, 2025 |
| Acer          | Aspire A315-44P             | [d05868bfa0](https://linux-hardware.org/?probe=d05868bfa0) | May 14, 2025 |
| Lenovo        | IdeaPad Slim 5 15ARP10 8... | [5e98384d41](https://linux-hardware.org/?probe=5e98384d41) | May 12, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [1b8739d275](https://linux-hardware.org/?probe=1b8739d275) | May 12, 2025 |
| Fujitsu       | LIFEBOOK T901               | [9fb6e5f404](https://linux-hardware.org/?probe=9fb6e5f404) | May 12, 2025 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fbe84180a8](https://linux-hardware.org/?probe=fbe84180a8) | May 11, 2025 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [1142416d54](https://linux-hardware.org/?probe=1142416d54) | May 11, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [e1fd489d7a](https://linux-hardware.org/?probe=e1fd489d7a) | May 10, 2025 |
| HP            | EliteBook X G1a 14 inch ... | [0b7bc2e8d9](https://linux-hardware.org/?probe=0b7bc2e8d9) | May 05, 2025 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [9a2f785812](https://linux-hardware.org/?probe=9a2f785812) | May 05, 2025 |
| HP            | EliteBook X G1a 14 inch ... | [096e508042](https://linux-hardware.org/?probe=096e508042) | May 05, 2025 |
| Google        | Bard                        | [8426eb03bd](https://linux-hardware.org/?probe=8426eb03bd) | May 04, 2025 |
| HP            | ZBook Fury 15.6 inch G8 ... | [bdf09cd14f](https://linux-hardware.org/?probe=bdf09cd14f) | May 02, 2025 |
| Lenovo        | Legion 5 16IRX9 83DG        | [98dce77ed9](https://linux-hardware.org/?probe=98dce77ed9) | May 02, 2025 |
| Lenovo        | Yoga Slim 7 14IMH9 83CV     | [37c61d1c43](https://linux-hardware.org/?probe=37c61d1c43) | May 02, 2025 |
| Lenovo        | Yoga Slim 7 14IMH9 83CV     | [29c57c9f3a](https://linux-hardware.org/?probe=29c57c9f3a) | May 02, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [68a561612e](https://linux-hardware.org/?probe=68a561612e) | Apr 30, 2025 |
| Dell          | XPS 13 7390                 | [0ae08dee26](https://linux-hardware.org/?probe=0ae08dee26) | Apr 30, 2025 |
| Lenovo        | Yoga Pro 7 14IAH10 83KF     | [1f56981d74](https://linux-hardware.org/?probe=1f56981d74) | Apr 30, 2025 |
| Lenovo        | Yoga Pro 7 14IAH10 83KF     | [e47636808b](https://linux-hardware.org/?probe=e47636808b) | Apr 29, 2025 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c26c536ae1](https://linux-hardware.org/?probe=c26c536ae1) | Apr 29, 2025 |
| Lenovo        | Legion S7 15ACH6 82K8       | [028fab4d57](https://linux-hardware.org/?probe=028fab4d57) | Apr 28, 2025 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [19768ea881](https://linux-hardware.org/?probe=19768ea881) | Apr 27, 2025 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [c128aa3bca](https://linux-hardware.org/?probe=c128aa3bca) | Apr 27, 2025 |
| Lenovo        | Yoga Slim 7 14IMH9 83CV     | [99b5da6557](https://linux-hardware.org/?probe=99b5da6557) | Apr 26, 2025 |
| Lenovo        | Yoga Slim 7 15ILL9 83HM     | [d38f839bf0](https://linux-hardware.org/?probe=d38f839bf0) | Apr 25, 2025 |
| Dell          | Inspiron 14 5430            | [6ab22ab7dd](https://linux-hardware.org/?probe=6ab22ab7dd) | Apr 24, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [9daa09d379](https://linux-hardware.org/?probe=9daa09d379) | Apr 20, 2025 |
| Lenovo        | ThinkPad T490 20N3S64000    | [186461e404](https://linux-hardware.org/?probe=186461e404) | Apr 19, 2025 |
| Dell          | Inspiron 14 5430            | [15d50a33bb](https://linux-hardware.org/?probe=15d50a33bb) | Apr 18, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [b89399b8b4](https://linux-hardware.org/?probe=b89399b8b4) | Apr 18, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [54c717ef5d](https://linux-hardware.org/?probe=54c717ef5d) | Apr 16, 2025 |
| Fujitsu       | FMVUH01007                  | [a33cc5ce4b](https://linux-hardware.org/?probe=a33cc5ce4b) | Apr 15, 2025 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [c77acb480d](https://linux-hardware.org/?probe=c77acb480d) | Apr 14, 2025 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [0b40780bb0](https://linux-hardware.org/?probe=0b40780bb0) | Apr 14, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [0936f097cd](https://linux-hardware.org/?probe=0936f097cd) | Apr 14, 2025 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | [9b53991d11](https://linux-hardware.org/?probe=9b53991d11) | Apr 14, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6895dbc794](https://linux-hardware.org/?probe=6895dbc794) | Apr 13, 2025 |
| Lenovo        | ThinkPad T410 2537V2F       | [c00af7f001](https://linux-hardware.org/?probe=c00af7f001) | Apr 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3442f91b67](https://linux-hardware.org/?probe=3442f91b67) | Apr 12, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [b7f9431692](https://linux-hardware.org/?probe=b7f9431692) | Apr 11, 2025 |
| Dell          | Precision 5760              | [7cf2fecab6](https://linux-hardware.org/?probe=7cf2fecab6) | Apr 11, 2025 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [1293a3b6d0](https://linux-hardware.org/?probe=1293a3b6d0) | Apr 09, 2025 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [5fd3bd9368](https://linux-hardware.org/?probe=5fd3bd9368) | Apr 09, 2025 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | [355f169946](https://linux-hardware.org/?probe=355f169946) | Apr 07, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [aa963970fe](https://linux-hardware.org/?probe=aa963970fe) | Apr 07, 2025 |
| Lenovo        | ThinkBook 14 G6 IRL 21NQ    | [af9905813e](https://linux-hardware.org/?probe=af9905813e) | Apr 07, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [b32d221adc](https://linux-hardware.org/?probe=b32d221adc) | Apr 06, 2025 |
| Lenovo        | ThinkPad T490 20N3S64000    | [d097cd4276](https://linux-hardware.org/?probe=d097cd4276) | Apr 05, 2025 |
| HUAWEI        | CREM-WXX9                   | [a55634789b](https://linux-hardware.org/?probe=a55634789b) | Apr 05, 2025 |
| Apple         | MacBookPro11,5              | [e8a6c03faa](https://linux-hardware.org/?probe=e8a6c03faa) | Apr 05, 2025 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [1e8baeba0d](https://linux-hardware.org/?probe=1e8baeba0d) | Apr 04, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [df8c1a2ef1](https://linux-hardware.org/?probe=df8c1a2ef1) | Apr 02, 2025 |
| HP            | ProBook 450 G3              | [84b5d1db24](https://linux-hardware.org/?probe=84b5d1db24) | Mar 29, 2025 |
| Dell          | Latitude 7330 Rugged Ext... | [ff3944b669](https://linux-hardware.org/?probe=ff3944b669) | Mar 23, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [6a016ebec9](https://linux-hardware.org/?probe=6a016ebec9) | Mar 22, 2025 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [c8d7f37d6b](https://linux-hardware.org/?probe=c8d7f37d6b) | Mar 22, 2025 |
| Acer          | Swift SFG14-73T             | [e64a96af80](https://linux-hardware.org/?probe=e64a96af80) | Mar 21, 2025 |
| Apple         | MacBookPro16,2              | [e323a2014b](https://linux-hardware.org/?probe=e323a2014b) | Mar 20, 2025 |
| HP            | ProBook 450 15.6 inch G1... | [c401eeb4b5](https://linux-hardware.org/?probe=c401eeb4b5) | Mar 20, 2025 |
| HUAWEI        | BOHK-WAX9X                  | [543adfe120](https://linux-hardware.org/?probe=543adfe120) | Mar 20, 2025 |
| Lenovo        | Legion S7 16IAH7 82TF       | [75784550d0](https://linux-hardware.org/?probe=75784550d0) | Mar 17, 2025 |
| Lenovo        | Legion S7 16IAH7 82TF       | [2291ab8e83](https://linux-hardware.org/?probe=2291ab8e83) | Mar 17, 2025 |
| HP            | Laptop 15-dy2xxx            | [fe9a8b543f](https://linux-hardware.org/?probe=fe9a8b543f) | Mar 17, 2025 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [614e348118](https://linux-hardware.org/?probe=614e348118) | Mar 17, 2025 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [e3c8448c50](https://linux-hardware.org/?probe=e3c8448c50) | Mar 16, 2025 |
| MECHREVO      | WUJIE14XA                   | [d9af608109](https://linux-hardware.org/?probe=d9af608109) | Mar 16, 2025 |
| Lenovo        | ThinkBook 14 G7+ ASP 21Q... | [e9373e84e9](https://linux-hardware.org/?probe=e9373e84e9) | Mar 16, 2025 |
| Valve         | Jupiter                     | [ffcfda6117](https://linux-hardware.org/?probe=ffcfda6117) | Mar 15, 2025 |
| Lenovo        | ThinkPad T495 20NKS00100    | [e71346e854](https://linux-hardware.org/?probe=e71346e854) | Mar 14, 2025 |
| Lenovo        | ThinkBook 14 G6+ IMH 21L... | [8b223477d0](https://linux-hardware.org/?probe=8b223477d0) | Mar 12, 2025 |
| Lenovo        | ThinkBook 14 G7+ ASP 21Q... | [db0daabda2](https://linux-hardware.org/?probe=db0daabda2) | Mar 10, 2025 |
| Lenovo        | ThinkBook 14 G7+ ASP 21Q... | [2bd9c59427](https://linux-hardware.org/?probe=2bd9c59427) | Mar 09, 2025 |
| Lenovo        | Legion Y530-15ICH 81FV      | [478b937083](https://linux-hardware.org/?probe=478b937083) | Mar 09, 2025 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f694744b99](https://linux-hardware.org/?probe=f694744b99) | Mar 09, 2025 |
| HP            | EliteBook 850 G6            | [b3ca2eec42](https://linux-hardware.org/?probe=b3ca2eec42) | Mar 05, 2025 |
| Google        | Markarth                    | [ed3185ecb8](https://linux-hardware.org/?probe=ed3185ecb8) | Mar 04, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [c54ac48db7](https://linux-hardware.org/?probe=c54ac48db7) | Mar 02, 2025 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [b028b113e4](https://linux-hardware.org/?probe=b028b113e4) | Mar 02, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [b17ed4634d](https://linux-hardware.org/?probe=b17ed4634d) | Mar 02, 2025 |
| Google        | Markarth                    | [e04006d209](https://linux-hardware.org/?probe=e04006d209) | Mar 01, 2025 |
| Apple         | MacBookPro11,4              | [9fb67e9042](https://linux-hardware.org/?probe=9fb67e9042) | Feb 27, 2025 |
| HP            | OMEN by Transcend 16 inc... | [5ecdd1b28c](https://linux-hardware.org/?probe=5ecdd1b28c) | Feb 27, 2025 |
| Gigabyte      | AERO 15 KD                  | [ed0aedae46](https://linux-hardware.org/?probe=ed0aedae46) | Feb 27, 2025 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [09aef34007](https://linux-hardware.org/?probe=09aef34007) | Feb 24, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [2776c55951](https://linux-hardware.org/?probe=2776c55951) | Feb 20, 2025 |
| ADVAN         | 1701                        | [3041f37c41](https://linux-hardware.org/?probe=3041f37c41) | Feb 20, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA... | [55268ea610](https://linux-hardware.org/?probe=55268ea610) | Feb 07, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [addf883006](https://linux-hardware.org/?probe=addf883006) | Feb 06, 2025 |
| HP            | Victus by Laptop 16-e0xx... | [7b8d82d9f4](https://linux-hardware.org/?probe=7b8d82d9f4) | Feb 05, 2025 |
| Dell          | Precision 5690              | [20d7235736](https://linux-hardware.org/?probe=20d7235736) | Feb 04, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [05d88905af](https://linux-hardware.org/?probe=05d88905af) | Feb 04, 2025 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [b6857afb91](https://linux-hardware.org/?probe=b6857afb91) | Feb 04, 2025 |
| Acer          | Nitro AN515-42              | [70d7ce0304](https://linux-hardware.org/?probe=70d7ce0304) | Jan 31, 2025 |
| Google        | Bard                        | [ad2454ed6f](https://linux-hardware.org/?probe=ad2454ed6f) | Jan 30, 2025 |
| Unknown       | Apple MacBook Air (M1, 2... | [ba20322364](https://linux-hardware.org/?probe=ba20322364) | Jan 29, 2025 |
| Unknown       | Unknown                     | [fe8f7c3720](https://linux-hardware.org/?probe=fe8f7c3720) | Jan 27, 2025 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | [f99b4b70c4](https://linux-hardware.org/?probe=f99b4b70c4) | Jan 24, 2025 |
| GPD           | G1619-04                    | [b028392f3a](https://linux-hardware.org/?probe=b028392f3a) | Jan 19, 2025 |
| GPD           | G1628-04                    | [7419ac8d1c](https://linux-hardware.org/?probe=7419ac8d1c) | Jan 16, 2025 |
| Gigabyte      | AERO 15 KD                  | [f7721fcb66](https://linux-hardware.org/?probe=f7721fcb66) | Jan 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [65c1dfe05f](https://linux-hardware.org/?probe=65c1dfe05f) | Jan 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ebeadb242a](https://linux-hardware.org/?probe=ebeadb242a) | Jan 13, 2025 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [47ff076cec](https://linux-hardware.org/?probe=47ff076cec) | Jan 09, 2025 |
| Standard      | Unknown                     | [d39dc0e3e7](https://linux-hardware.org/?probe=d39dc0e3e7) | Jan 08, 2025 |
| Framework     | Laptop (12th Gen Intel C... | [965b509fd4](https://linux-hardware.org/?probe=965b509fd4) | Jan 07, 2025 |
| Lenovo        | ThinkPad T490 20N20030US    | [d4dd35d7dc](https://linux-hardware.org/?probe=d4dd35d7dc) | Jan 04, 2025 |
| HP            | Pavilion Laptop 14-ec0xx... | [9bb39e061b](https://linux-hardware.org/?probe=9bb39e061b) | Jan 04, 2025 |
| Lenovo        | Legion 7 16IRX9 83FD        | [7bb0cafb81](https://linux-hardware.org/?probe=7bb0cafb81) | Jan 04, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [041f977a25](https://linux-hardware.org/?probe=041f977a25) | Jan 03, 2025 |
| Framework     | Laptop                      | [a74fd192f3](https://linux-hardware.org/?probe=a74fd192f3) | Jan 03, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [0793ac2320](https://linux-hardware.org/?probe=0793ac2320) | Dec 31, 2024 |
| Acer          | Aspire 5742Z                | [0cda57368f](https://linux-hardware.org/?probe=0cda57368f) | Dec 28, 2024 |
| Dell          | Precision 5690              | [5219297c0d](https://linux-hardware.org/?probe=5219297c0d) | Dec 26, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [95d37ca286](https://linux-hardware.org/?probe=95d37ca286) | Dec 25, 2024 |
| Apple         | MacBookPro11,3              | [b6aa51489b](https://linux-hardware.org/?probe=b6aa51489b) | Dec 22, 2024 |
| ASUSTek       | ROG Zephyrus G16 GA605WI... | [0b5149cbce](https://linux-hardware.org/?probe=0b5149cbce) | Dec 18, 2024 |
| HP            | EliteBook 2560p             | [084e229e45](https://linux-hardware.org/?probe=084e229e45) | Dec 18, 2024 |
| Samsung       | 900X3N                      | [672751a071](https://linux-hardware.org/?probe=672751a071) | Dec 17, 2024 |
| GPD           | G1622-01                    | [daa5825210](https://linux-hardware.org/?probe=daa5825210) | Dec 17, 2024 |
| GPD           | G1622-01                    | [bd716cf271](https://linux-hardware.org/?probe=bd716cf271) | Dec 17, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21ML0... | [063c4b21a8](https://linux-hardware.org/?probe=063c4b21a8) | Dec 16, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21NQ    | [5c45e2bfee](https://linux-hardware.org/?probe=5c45e2bfee) | Dec 16, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [083f4404b5](https://linux-hardware.org/?probe=083f4404b5) | Dec 14, 2024 |
| Apple         | MacBookPro11,5              | [76bab8abed](https://linux-hardware.org/?probe=76bab8abed) | Dec 14, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [b5059cca85](https://linux-hardware.org/?probe=b5059cca85) | Dec 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [c43e0a8e7d](https://linux-hardware.org/?probe=c43e0a8e7d) | Dec 10, 2024 |
| HP            | Laptop 15-dy2xxx            | [5fd9df1c27](https://linux-hardware.org/?probe=5fd9df1c27) | Dec 07, 2024 |
| Lenovo        | G570 20079                  | [d7ca5ffb0b](https://linux-hardware.org/?probe=d7ca5ffb0b) | Dec 06, 2024 |
| Dell          | Precision 3591              | [af761ba6a9](https://linux-hardware.org/?probe=af761ba6a9) | Dec 05, 2024 |
| Lenovo        | ThinkPad X230 23252CG       | [614068917c](https://linux-hardware.org/?probe=614068917c) | Dec 04, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [12db03cac4](https://linux-hardware.org/?probe=12db03cac4) | Dec 01, 2024 |
| Lenovo        | ThinkPad T450s 20BWS3TM0... | [c32b3f2dd0](https://linux-hardware.org/?probe=c32b3f2dd0) | Nov 28, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | [773e88d3be](https://linux-hardware.org/?probe=773e88d3be) | Nov 27, 2024 |
| Dell          | XPS 15 9530                 | [df0fd1e685](https://linux-hardware.org/?probe=df0fd1e685) | Nov 27, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [032327d915](https://linux-hardware.org/?probe=032327d915) | Nov 26, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [24a75e17ae](https://linux-hardware.org/?probe=24a75e17ae) | Nov 26, 2024 |
| HP            | OmniBook Ultra Laptop 14... | [5c64854b38](https://linux-hardware.org/?probe=5c64854b38) | Nov 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21ML0... | [59205e96b5](https://linux-hardware.org/?probe=59205e96b5) | Nov 25, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [fa8c5128c6](https://linux-hardware.org/?probe=fa8c5128c6) | Nov 25, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [de16a781fa](https://linux-hardware.org/?probe=de16a781fa) | Nov 24, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [e7b45b99c1](https://linux-hardware.org/?probe=e7b45b99c1) | Nov 23, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [1d2005d912](https://linux-hardware.org/?probe=1d2005d912) | Nov 23, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [bdcf6c541a](https://linux-hardware.org/?probe=bdcf6c541a) | Nov 21, 2024 |
| Lenovo        | ThinkPad T450s 20BWS3TM0... | [0e39a0bdbe](https://linux-hardware.org/?probe=0e39a0bdbe) | Nov 21, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [81b39da9fd](https://linux-hardware.org/?probe=81b39da9fd) | Nov 19, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [24d0062e37](https://linux-hardware.org/?probe=24d0062e37) | Nov 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [fe024604b1](https://linux-hardware.org/?probe=fe024604b1) | Nov 17, 2024 |
| Dell          | Vostro 3500                 | [48169a4553](https://linux-hardware.org/?probe=48169a4553) | Nov 17, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [cf12d8256f](https://linux-hardware.org/?probe=cf12d8256f) | Nov 15, 2024 |
| PC Special... | NS50MU                      | [65a6da58c1](https://linux-hardware.org/?probe=65a6da58c1) | Nov 14, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [68df2e0f71](https://linux-hardware.org/?probe=68df2e0f71) | Nov 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [665265a239](https://linux-hardware.org/?probe=665265a239) | Nov 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3a28af2ad6](https://linux-hardware.org/?probe=3a28af2ad6) | Nov 13, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [193f9b2369](https://linux-hardware.org/?probe=193f9b2369) | Nov 12, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [6370e4afbb](https://linux-hardware.org/?probe=6370e4afbb) | Nov 10, 2024 |
| Dell          | G5 5590                     | [b797a36b4c](https://linux-hardware.org/?probe=b797a36b4c) | Nov 10, 2024 |
| Apple         | MacBookPro11,5              | [43a210e9cb](https://linux-hardware.org/?probe=43a210e9cb) | Nov 08, 2024 |
| Apple         | MacBookPro11,5              | [502004fe3d](https://linux-hardware.org/?probe=502004fe3d) | Nov 08, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [142462821d](https://linux-hardware.org/?probe=142462821d) | Nov 03, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [f1282c521a](https://linux-hardware.org/?probe=f1282c521a) | Oct 30, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [712493f433](https://linux-hardware.org/?probe=712493f433) | Oct 28, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [7e5bbb938b](https://linux-hardware.org/?probe=7e5bbb938b) | Oct 28, 2024 |
| Framework     | Laptop                      | [072ab62076](https://linux-hardware.org/?probe=072ab62076) | Oct 27, 2024 |
| HP            | ZBook Fury 16 G10 Mobile... | [e903944a84](https://linux-hardware.org/?probe=e903944a84) | Oct 26, 2024 |
| HUAWEI        | HVY-WXX9                    | [9dcb081b32](https://linux-hardware.org/?probe=9dcb081b32) | Oct 25, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [3d80b9eead](https://linux-hardware.org/?probe=3d80b9eead) | Oct 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [51f11aa9f2](https://linux-hardware.org/?probe=51f11aa9f2) | Oct 25, 2024 |
| Dell          | XPS 13 9310                 | [56d5b77e54](https://linux-hardware.org/?probe=56d5b77e54) | Oct 25, 2024 |
| HUAWEI        | HVY-WXX9                    | [04f2f2787e](https://linux-hardware.org/?probe=04f2f2787e) | Oct 25, 2024 |
| Acer          | Aspire A315-24PT            | [5e327ea424](https://linux-hardware.org/?probe=5e327ea424) | Oct 22, 2024 |
| Acer          | Swift SFG14-71              | [3cfedf7732](https://linux-hardware.org/?probe=3cfedf7732) | Oct 21, 2024 |
| Dell          | Latitude 5550               | [31ec440570](https://linux-hardware.org/?probe=31ec440570) | Oct 16, 2024 |
| Lenovo        | Legion 7 16IRX9 83FD        | [bf913685ba](https://linux-hardware.org/?probe=bf913685ba) | Oct 16, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4dbeafbd5f](https://linux-hardware.org/?probe=4dbeafbd5f) | Oct 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [329cd43769](https://linux-hardware.org/?probe=329cd43769) | Oct 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [661649b768](https://linux-hardware.org/?probe=661649b768) | Oct 13, 2024 |
| Lenovo        | ThinkPad T420 4180DY4       | [5afcda3ff3](https://linux-hardware.org/?probe=5afcda3ff3) | Oct 13, 2024 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | [20b06b0861](https://linux-hardware.org/?probe=20b06b0861) | Oct 13, 2024 |
| Lenovo        | Yoga 500-14IBD 80N4         | [634a88ef95](https://linux-hardware.org/?probe=634a88ef95) | Oct 12, 2024 |
| Lenovo        | ThinkPad L380 20M6S3UN00    | [8b17bec7be](https://linux-hardware.org/?probe=8b17bec7be) | Oct 12, 2024 |
| Dell          | Latitude E6540              | [ea8afd6f6b](https://linux-hardware.org/?probe=ea8afd6f6b) | Oct 12, 2024 |
| Dell          | Inspiron 5580               | [6e246c56fb](https://linux-hardware.org/?probe=6e246c56fb) | Oct 12, 2024 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [3d7009833d](https://linux-hardware.org/?probe=3d7009833d) | Oct 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [491f1090ca](https://linux-hardware.org/?probe=491f1090ca) | Oct 10, 2024 |
| Lenovo        | ThinkPad T480s 20L7S0BM0... | [64ef0dbb14](https://linux-hardware.org/?probe=64ef0dbb14) | Oct 09, 2024 |
| Acer          | Aspire A315-44P             | [65b854b6d3](https://linux-hardware.org/?probe=65b854b6d3) | Oct 08, 2024 |
| Dell          | G15 5511                    | [ed9b86e723](https://linux-hardware.org/?probe=ed9b86e723) | Oct 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [160ad6e49e](https://linux-hardware.org/?probe=160ad6e49e) | Oct 07, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [1e2e268764](https://linux-hardware.org/?probe=1e2e268764) | Oct 06, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [728d0f4561](https://linux-hardware.org/?probe=728d0f4561) | Oct 06, 2024 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [d44dc9b966](https://linux-hardware.org/?probe=d44dc9b966) | Oct 04, 2024 |
| Acer          | Aspire A315-44P             | [3aaeee6d1b](https://linux-hardware.org/?probe=3aaeee6d1b) | Oct 03, 2024 |
| Lenovo        | ThinkPad X250 20CLS02000    | [bb75759114](https://linux-hardware.org/?probe=bb75759114) | Sep 26, 2024 |
| Acer          | Aspire A715-41G             | [28630e6b4e](https://linux-hardware.org/?probe=28630e6b4e) | Sep 26, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2fc188f296](https://linux-hardware.org/?probe=2fc188f296) | Sep 25, 2024 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [2282ce51ba](https://linux-hardware.org/?probe=2282ce51ba) | Sep 25, 2024 |
| Dell          | Inspiron N5110              | [cf26c5a0b7](https://linux-hardware.org/?probe=cf26c5a0b7) | Sep 25, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [34bb43620b](https://linux-hardware.org/?probe=34bb43620b) | Sep 24, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [fd06da7fc1](https://linux-hardware.org/?probe=fd06da7fc1) | Sep 22, 2024 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [6cdf2f1f7f](https://linux-hardware.org/?probe=6cdf2f1f7f) | Sep 22, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [ab1b90b470](https://linux-hardware.org/?probe=ab1b90b470) | Sep 21, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [3febc58555](https://linux-hardware.org/?probe=3febc58555) | Sep 21, 2024 |
| MSI           | Alpha 15 B5EEK              | [404017af65](https://linux-hardware.org/?probe=404017af65) | Sep 20, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [fdcd6421d6](https://linux-hardware.org/?probe=fdcd6421d6) | Sep 20, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [a3f44fecb0](https://linux-hardware.org/?probe=a3f44fecb0) | Sep 18, 2024 |
| Lenovo        | ThinkPad X250 20CLS02000    | [add0feabb8](https://linux-hardware.org/?probe=add0feabb8) | Sep 17, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [28e8212852](https://linux-hardware.org/?probe=28e8212852) | Sep 16, 2024 |
| Acer          | Swift SF314-43              | [58150ad2bf](https://linux-hardware.org/?probe=58150ad2bf) | Sep 11, 2024 |
| Acer          | Predator PT316-51s          | [6115a8c519](https://linux-hardware.org/?probe=6115a8c519) | Sep 11, 2024 |
| Acer          | Predator PH315-54           | [c781f9222b](https://linux-hardware.org/?probe=c781f9222b) | Sep 10, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [97358eeb4e](https://linux-hardware.org/?probe=97358eeb4e) | Sep 09, 2024 |
| Dell          | Precision 3520              | [860ad42896](https://linux-hardware.org/?probe=860ad42896) | Sep 09, 2024 |
| Dell          | XPS 17 9700                 | [c91858771e](https://linux-hardware.org/?probe=c91858771e) | Sep 09, 2024 |
| Dell          | Inspiron 7548               | [150c9ec14f](https://linux-hardware.org/?probe=150c9ec14f) | Sep 09, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [cc11d84cd6](https://linux-hardware.org/?probe=cc11d84cd6) | Sep 09, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [b06892eff4](https://linux-hardware.org/?probe=b06892eff4) | Sep 09, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [062d642cdc](https://linux-hardware.org/?probe=062d642cdc) | Sep 09, 2024 |
| Framework     | Laptop                      | [2e42d66339](https://linux-hardware.org/?probe=2e42d66339) | Sep 09, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [a9c678a896](https://linux-hardware.org/?probe=a9c678a896) | Sep 08, 2024 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [224c031297](https://linux-hardware.org/?probe=224c031297) | Sep 08, 2024 |
| Dell          | Inspiron 7577               | [fd08888941](https://linux-hardware.org/?probe=fd08888941) | Sep 08, 2024 |
| MSI           | Modern 14 B5M               | [9978e53d19](https://linux-hardware.org/?probe=9978e53d19) | Sep 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [69d9359729](https://linux-hardware.org/?probe=69d9359729) | Sep 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K3C... | [5d86305564](https://linux-hardware.org/?probe=5d86305564) | Sep 08, 2024 |
| Apple         | MacBookAir5,2               | [c0b8fe17cd](https://linux-hardware.org/?probe=c0b8fe17cd) | Sep 08, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [1ef6ad8d15](https://linux-hardware.org/?probe=1ef6ad8d15) | Sep 08, 2024 |
| Razer         | Blade                       | [b0a9880c36](https://linux-hardware.org/?probe=b0a9880c36) | Sep 08, 2024 |
| Dell          | Inspiron 7570               | [8487de4413](https://linux-hardware.org/?probe=8487de4413) | Sep 08, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [b44174619d](https://linux-hardware.org/?probe=b44174619d) | Sep 08, 2024 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [e23fc38add](https://linux-hardware.org/?probe=e23fc38add) | Sep 08, 2024 |
| Dell          | Latitude 7390 2-in-1        | [0acf653766](https://linux-hardware.org/?probe=0acf653766) | Sep 08, 2024 |
| Dell          | G5 5500                     | [047302a678](https://linux-hardware.org/?probe=047302a678) | Sep 08, 2024 |
| Razer         | Blade Stealth 13 (Early ... | [55cb30169f](https://linux-hardware.org/?probe=55cb30169f) | Sep 08, 2024 |
| Timi          | Redmi Book Pro 14 2022      | [7dfc2463f0](https://linux-hardware.org/?probe=7dfc2463f0) | Sep 06, 2024 |
| Apple         | MacBookPro11,5              | [62a1441324](https://linux-hardware.org/?probe=62a1441324) | Sep 05, 2024 |
| MSI           | Modern 14 B5M               | [3d4ad593f5](https://linux-hardware.org/?probe=3d4ad593f5) | Sep 02, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [7b534afcea](https://linux-hardware.org/?probe=7b534afcea) | Sep 02, 2024 |
| HP            | ZBook 14 G2                 | [7f0dc8a5ee](https://linux-hardware.org/?probe=7f0dc8a5ee) | Aug 30, 2024 |
| HP            | ZBook 14 G2                 | [0afb138cf7](https://linux-hardware.org/?probe=0afb138cf7) | Aug 30, 2024 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [62b809ea1a](https://linux-hardware.org/?probe=62b809ea1a) | Aug 28, 2024 |
| Samsung       | 960XFH                      | [a7b8e567a2](https://linux-hardware.org/?probe=a7b8e567a2) | Aug 23, 2024 |
| TUXEDO        | Pulse 15 Gen2               | [cb12a91b1e](https://linux-hardware.org/?probe=cb12a91b1e) | Aug 23, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [179947d1fc](https://linux-hardware.org/?probe=179947d1fc) | Aug 23, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [06ff184117](https://linux-hardware.org/?probe=06ff184117) | Aug 23, 2024 |
| Dell          | XPS 15 9530                 | [ac9fcbda82](https://linux-hardware.org/?probe=ac9fcbda82) | Aug 20, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [e0af5cb80e](https://linux-hardware.org/?probe=e0af5cb80e) | Aug 19, 2024 |
| Acer          | Nitro AN515-42              | [87094d4adb](https://linux-hardware.org/?probe=87094d4adb) | Aug 18, 2024 |
| Lenovo        | ThinkPad L13 Gen 2a 21AB... | [01ce920620](https://linux-hardware.org/?probe=01ce920620) | Aug 16, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [4168e29e3b](https://linux-hardware.org/?probe=4168e29e3b) | Aug 16, 2024 |
| Unknown       | Unknown                     | [00173eebcb](https://linux-hardware.org/?probe=00173eebcb) | Aug 16, 2024 |
| System76      | Darter Pro                  | [1fbb688f8e](https://linux-hardware.org/?probe=1fbb688f8e) | Aug 16, 2024 |
| Razer         | Blade 14 - RZ09-0370        | [aec3920dda](https://linux-hardware.org/?probe=aec3920dda) | Aug 15, 2024 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [aa503d6674](https://linux-hardware.org/?probe=aa503d6674) | Aug 15, 2024 |
| Dell          | Vostro 3500                 | [647b4d4e05](https://linux-hardware.org/?probe=647b4d4e05) | Aug 14, 2024 |
| Acer          | Aspire A715-42G             | [59afb561de](https://linux-hardware.org/?probe=59afb561de) | Aug 14, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [e7ab69fde0](https://linux-hardware.org/?probe=e7ab69fde0) | Aug 11, 2024 |
| System76      | Pangolin                    | [322cfe0ba1](https://linux-hardware.org/?probe=322cfe0ba1) | Aug 09, 2024 |
| Chuwi         | MiniBook X                  | [6440423423](https://linux-hardware.org/?probe=6440423423) | Aug 08, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [9465561e04](https://linux-hardware.org/?probe=9465561e04) | Aug 08, 2024 |
| Google        | Bard                        | [73af4eb516](https://linux-hardware.org/?probe=73af4eb516) | Aug 07, 2024 |
| Acer          | Aspire A515-56              | [79f287dfa8](https://linux-hardware.org/?probe=79f287dfa8) | Aug 06, 2024 |
| HP            | Laptop 15s-eq2xxx           | [851c57320e](https://linux-hardware.org/?probe=851c57320e) | Aug 06, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [22d2660f10](https://linux-hardware.org/?probe=22d2660f10) | Aug 04, 2024 |
| Dell          | XPS 9315                    | [0532ec9631](https://linux-hardware.org/?probe=0532ec9631) | Aug 03, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [2f0fc05b00](https://linux-hardware.org/?probe=2f0fc05b00) | Aug 01, 2024 |
| Dell          | Latitude E7240              | [11f88b9caf](https://linux-hardware.org/?probe=11f88b9caf) | Jul 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [9f8143243c](https://linux-hardware.org/?probe=9f8143243c) | Jul 29, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [1038ccd86b](https://linux-hardware.org/?probe=1038ccd86b) | Jul 28, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [a717781b71](https://linux-hardware.org/?probe=a717781b71) | Jul 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a158056c57](https://linux-hardware.org/?probe=a158056c57) | Jul 27, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [0219498bb7](https://linux-hardware.org/?probe=0219498bb7) | Jul 26, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [2a25ba03a4](https://linux-hardware.org/?probe=2a25ba03a4) | Jul 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7ddcc47c13](https://linux-hardware.org/?probe=7ddcc47c13) | Jul 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4c5754c4b3](https://linux-hardware.org/?probe=4c5754c4b3) | Jul 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [08c05a5904](https://linux-hardware.org/?probe=08c05a5904) | Jul 24, 2024 |
| Apple         | MacBookPro16,1              | [45cee76121](https://linux-hardware.org/?probe=45cee76121) | Jul 21, 2024 |
| Acer          | Predator PH315-51           | [f36e31d89f](https://linux-hardware.org/?probe=f36e31d89f) | Jul 20, 2024 |
| Lenovo        | ThinkBook 14 G5+ APO 21J... | [c544d39f9f](https://linux-hardware.org/?probe=c544d39f9f) | Jul 20, 2024 |
| MSI           | Katana GF76 11UC            | [8ef6e6c1ae](https://linux-hardware.org/?probe=8ef6e6c1ae) | Jul 20, 2024 |
| HP            | EliteBook 840 14 inch G1... | [90031d618e](https://linux-hardware.org/?probe=90031d618e) | Jul 18, 2024 |
| Acer          | Predator PH315-51           | [c0fb0f5d78](https://linux-hardware.org/?probe=c0fb0f5d78) | Jul 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [aed926371d](https://linux-hardware.org/?probe=aed926371d) | Jul 15, 2024 |
| Lenovo        | Legion Y7000 81FW           | [828ea2e910](https://linux-hardware.org/?probe=828ea2e910) | Jul 13, 2024 |
| Lenovo        | ThinkPad P51s 20HB000VPG    | [fc2a09d595](https://linux-hardware.org/?probe=fc2a09d595) | Jul 11, 2024 |
| Lenovo        | ThinkPad T495 20NKS2JD00    | [c4c6fededf](https://linux-hardware.org/?probe=c4c6fededf) | Jul 11, 2024 |
| Apple         | MacBookPro11,1              | [ea25c8dde3](https://linux-hardware.org/?probe=ea25c8dde3) | Jul 11, 2024 |
| HUAWEI        | BOM-WXX9                    | [e1097cce91](https://linux-hardware.org/?probe=e1097cce91) | Jul 10, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [2d96a14cd7](https://linux-hardware.org/?probe=2d96a14cd7) | Jul 07, 2024 |
| Acer          | Nitro AN515-52              | [96d82e2cb3](https://linux-hardware.org/?probe=96d82e2cb3) | Jul 06, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f846e6d9a0](https://linux-hardware.org/?probe=f846e6d9a0) | Jul 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JS0... | [8aec324881](https://linux-hardware.org/?probe=8aec324881) | Jul 03, 2024 |
| Dynabook      | PORTEGE X30L-K              | [20e1176fed](https://linux-hardware.org/?probe=20e1176fed) | Jul 03, 2024 |
| HUAWEI        | VGHH-XX                     | [3676bfc771](https://linux-hardware.org/?probe=3676bfc771) | Jun 24, 2024 |
| Apple         | MacBookPro11,4              | [e77b8b7c1a](https://linux-hardware.org/?probe=e77b8b7c1a) | Jun 22, 2024 |
| HP            | OMEN by Transcend Gaming... | [f95edc487c](https://linux-hardware.org/?probe=f95edc487c) | Jun 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [238ea6a5e2](https://linux-hardware.org/?probe=238ea6a5e2) | Jun 16, 2024 |
| PC Special... | Recoil II                   | [9003dfdb47](https://linux-hardware.org/?probe=9003dfdb47) | Jun 12, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [021499aed9](https://linux-hardware.org/?probe=021499aed9) | Jun 08, 2024 |
| HP            | EliteBook Folio 9470m       | [d9e925bab3](https://linux-hardware.org/?probe=d9e925bab3) | Jun 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1be0efeb19](https://linux-hardware.org/?probe=1be0efeb19) | Jun 07, 2024 |
| Dell          | G3 3500                     | [e7ad9fe987](https://linux-hardware.org/?probe=e7ad9fe987) | Jun 06, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | [2c59b90cde](https://linux-hardware.org/?probe=2c59b90cde) | Jun 06, 2024 |
| HP            | Laptop 15-dy2xxx            | [5ef8fbaf58](https://linux-hardware.org/?probe=5ef8fbaf58) | Jun 06, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [0e6ffaf99b](https://linux-hardware.org/?probe=0e6ffaf99b) | Jun 02, 2024 |
| Lenovo        | ThinkPad X250 20CLS1EW00    | [6f51b55a35](https://linux-hardware.org/?probe=6f51b55a35) | Jun 01, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [12df9c0f8e](https://linux-hardware.org/?probe=12df9c0f8e) | Jun 01, 2024 |
| PC Special... | Recoil II                   | [0e6bc15b29](https://linux-hardware.org/?probe=0e6bc15b29) | May 30, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [38e45316b1](https://linux-hardware.org/?probe=38e45316b1) | May 28, 2024 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [e63220aa5e](https://linux-hardware.org/?probe=e63220aa5e) | May 27, 2024 |
| Dell          | G3 3779                     | [26ce6cbc7d](https://linux-hardware.org/?probe=26ce6cbc7d) | May 25, 2024 |
| Dell          | Inspiron 7577               | [db403a9f18](https://linux-hardware.org/?probe=db403a9f18) | May 21, 2024 |
| Apple         | MacBookAir7,2               | [3caec5604a](https://linux-hardware.org/?probe=3caec5604a) | May 20, 2024 |
| Google        | Babytiger                   | [9fe14fb0f5](https://linux-hardware.org/?probe=9fe14fb0f5) | May 14, 2024 |
| Google        | Babytiger                   | [b0f37ce546](https://linux-hardware.org/?probe=b0f37ce546) | May 14, 2024 |
| Lenovo        | ThinkPad X395 20NM0002GE    | [2deda1aba0](https://linux-hardware.org/?probe=2deda1aba0) | May 13, 2024 |
| Apple         | MacBookPro8,1               | [3598463988](https://linux-hardware.org/?probe=3598463988) | May 12, 2024 |
| Acer          | Predator PH315-51           | [a065a819ff](https://linux-hardware.org/?probe=a065a819ff) | May 11, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [9c7ba4a173](https://linux-hardware.org/?probe=9c7ba4a173) | May 10, 2024 |
| Razer         | Blade 14 - RZ09-0508        | [2f6237a9a5](https://linux-hardware.org/?probe=2f6237a9a5) | May 10, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [161509c62b](https://linux-hardware.org/?probe=161509c62b) | May 09, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [44f44fe800](https://linux-hardware.org/?probe=44f44fe800) | May 06, 2024 |
| Apple         | MacBookPro16,2              | [fe05b165fb](https://linux-hardware.org/?probe=fe05b165fb) | May 04, 2024 |
| Acer          | Predator PH315-51           | [6cadb88b1d](https://linux-hardware.org/?probe=6cadb88b1d) | May 01, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [90807317fb](https://linux-hardware.org/?probe=90807317fb) | May 01, 2024 |
| Apple         | MacBookPro11,2              | [5cd273406c](https://linux-hardware.org/?probe=5cd273406c) | Apr 30, 2024 |
| ASUSTek       | K53SJ                       | [45bc744085](https://linux-hardware.org/?probe=45bc744085) | Apr 28, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [86305e383e](https://linux-hardware.org/?probe=86305e383e) | Apr 25, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [113c93d444](https://linux-hardware.org/?probe=113c93d444) | Apr 25, 2024 |
| Dell          | Latitude 7330 Rugged Ext... | [787276b922](https://linux-hardware.org/?probe=787276b922) | Apr 25, 2024 |
| Dell          | XPS 15 9530                 | [e1d4486b51](https://linux-hardware.org/?probe=e1d4486b51) | Apr 24, 2024 |
| HP            | ProBook 440 G2              | [e5a4a84406](https://linux-hardware.org/?probe=e5a4a84406) | Apr 23, 2024 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [bf31c1e8e2](https://linux-hardware.org/?probe=bf31c1e8e2) | Apr 22, 2024 |
| Razer         | Blade 14 - RZ09-0508        | [cc1f5421e7](https://linux-hardware.org/?probe=cc1f5421e7) | Apr 21, 2024 |
| MSI           | GE60 2PE                    | [38cce299c6](https://linux-hardware.org/?probe=38cce299c6) | Apr 18, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ba533ecb3a](https://linux-hardware.org/?probe=ba533ecb3a) | Apr 18, 2024 |
| Lenovo        | ThinkPad P50 20EN0007MH     | [d56c554eed](https://linux-hardware.org/?probe=d56c554eed) | Apr 16, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [6a7d29fe24](https://linux-hardware.org/?probe=6a7d29fe24) | Apr 15, 2024 |
| Razer         | Blade                       | [8ff543883a](https://linux-hardware.org/?probe=8ff543883a) | Apr 14, 2024 |
| Apple         | MacBookPro11,3              | [159bfe4be5](https://linux-hardware.org/?probe=159bfe4be5) | Apr 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [90946053e1](https://linux-hardware.org/?probe=90946053e1) | Apr 11, 2024 |
| Apple         | MacBookPro11,5              | [d48fd50ca7](https://linux-hardware.org/?probe=d48fd50ca7) | Apr 11, 2024 |
| Apple         | MacBookPro10,1              | [c468075794](https://linux-hardware.org/?probe=c468075794) | Apr 11, 2024 |
| MSI           | GL65 9SC                    | [7bc8965c5e](https://linux-hardware.org/?probe=7bc8965c5e) | Apr 10, 2024 |
| Google        | Redrix                      | [6dd8afed85](https://linux-hardware.org/?probe=6dd8afed85) | Apr 10, 2024 |
| Apple         | MacBookPro12,1              | [50c4a83180](https://linux-hardware.org/?probe=50c4a83180) | Apr 07, 2024 |
| System76      | Oryx Pro                    | [4592d774b4](https://linux-hardware.org/?probe=4592d774b4) | Apr 06, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | [81925bcc23](https://linux-hardware.org/?probe=81925bcc23) | Apr 05, 2024 |
| Acer          | Swift SF514-54GT            | [c0a1536935](https://linux-hardware.org/?probe=c0a1536935) | Mar 28, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [57aabe3115](https://linux-hardware.org/?probe=57aabe3115) | Mar 26, 2024 |
| Dell          | Latitude 7420               | [511721b690](https://linux-hardware.org/?probe=511721b690) | Mar 23, 2024 |
| Lenovo        | V15-ADA 82C7                | [9fce956c50](https://linux-hardware.org/?probe=9fce956c50) | Mar 23, 2024 |
| HONOR         | BMH-WDX9                    | [4445879c66](https://linux-hardware.org/?probe=4445879c66) | Mar 21, 2024 |
| Timi          | Redmi Book Pro 14 2022      | [164d9ccd8d](https://linux-hardware.org/?probe=164d9ccd8d) | Mar 21, 2024 |
| HONOR         | BMH-WDX9                    | [01284be05a](https://linux-hardware.org/?probe=01284be05a) | Mar 20, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [027fecc047](https://linux-hardware.org/?probe=027fecc047) | Mar 18, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [def7c584ff](https://linux-hardware.org/?probe=def7c584ff) | Mar 17, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [3906b06830](https://linux-hardware.org/?probe=3906b06830) | Mar 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [5bad97c6ec](https://linux-hardware.org/?probe=5bad97c6ec) | Mar 15, 2024 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [06ecea6114](https://linux-hardware.org/?probe=06ecea6114) | Mar 12, 2024 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [10e971349c](https://linux-hardware.org/?probe=10e971349c) | Mar 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [25074d4407](https://linux-hardware.org/?probe=25074d4407) | Mar 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c2b5dc013f](https://linux-hardware.org/?probe=c2b5dc013f) | Mar 03, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | [8a0a1f3b4a](https://linux-hardware.org/?probe=8a0a1f3b4a) | Mar 01, 2024 |
| Lenovo        | ThinkPad T480s 20L7S3750... | [ce625cdb1a](https://linux-hardware.org/?probe=ce625cdb1a) | Feb 29, 2024 |
| HP            | Pavilion Power Laptop 15... | [43919c6c44](https://linux-hardware.org/?probe=43919c6c44) | Feb 29, 2024 |
| Lenovo        | ThinkPad T480s 20L7S3750... | [7b3b02bc41](https://linux-hardware.org/?probe=7b3b02bc41) | Feb 28, 2024 |
| MSI           | GL65 9SC                    | [6981398659](https://linux-hardware.org/?probe=6981398659) | Feb 28, 2024 |
| Lenovo        | ThinkPad T480s 20L7S3750... | [8bdc7efaf7](https://linux-hardware.org/?probe=8bdc7efaf7) | Feb 28, 2024 |
| Dell          | Latitude 7420               | [fd13235e39](https://linux-hardware.org/?probe=fd13235e39) | Feb 27, 2024 |
| Lenovo        | Yoga 2 Pro 20266            | [6185ab568b](https://linux-hardware.org/?probe=6185ab568b) | Feb 27, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | [f6c8d11592](https://linux-hardware.org/?probe=f6c8d11592) | Feb 26, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [848c852446](https://linux-hardware.org/?probe=848c852446) | Feb 25, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [f4e1c02b92](https://linux-hardware.org/?probe=f4e1c02b92) | Feb 21, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [bccce50111](https://linux-hardware.org/?probe=bccce50111) | Feb 21, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [d8f261643b](https://linux-hardware.org/?probe=d8f261643b) | Feb 21, 2024 |
| Lenovo        | Y720-15IKB 81CQ             | [c62e8797a8](https://linux-hardware.org/?probe=c62e8797a8) | Feb 19, 2024 |
| Lenovo        | ThinkPad Edge E531 68859... | [45a495ee7d](https://linux-hardware.org/?probe=45a495ee7d) | Feb 14, 2024 |
| Acer          | AOD270                      | [a0b7e5e68a](https://linux-hardware.org/?probe=a0b7e5e68a) | Feb 11, 2024 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | [66c0cc51e3](https://linux-hardware.org/?probe=66c0cc51e3) | Feb 06, 2024 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [ea8930c46e](https://linux-hardware.org/?probe=ea8930c46e) | Feb 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [fe7dfd8247](https://linux-hardware.org/?probe=fe7dfd8247) | Feb 02, 2024 |
| Apple         | MacBookPro11,5              | [55197489b0](https://linux-hardware.org/?probe=55197489b0) | Feb 02, 2024 |
| Corsair       | Voyager a1600               | [86aec463cc](https://linux-hardware.org/?probe=86aec463cc) | Jan 30, 2024 |
| Corsair       | Voyager a1600               | [00605bf92c](https://linux-hardware.org/?probe=00605bf92c) | Jan 28, 2024 |
| Sony          | VGN-CS11S_Q                 | [df687ca726](https://linux-hardware.org/?probe=df687ca726) | Jan 26, 2024 |
| Apple         | MacBookPro11,5              | [d7308911e4](https://linux-hardware.org/?probe=d7308911e4) | Jan 26, 2024 |
| Framework     | Laptop                      | [64d0e147fe](https://linux-hardware.org/?probe=64d0e147fe) | Jan 25, 2024 |
| Sony          | VGN-CS11S_Q                 | [4c9e427a30](https://linux-hardware.org/?probe=4c9e427a30) | Jan 25, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [4a41cdcc67](https://linux-hardware.org/?probe=4a41cdcc67) | Jan 25, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c2be9790ea](https://linux-hardware.org/?probe=c2be9790ea) | Jan 25, 2024 |
| Lenovo        | ThinkPad T495 20NJ0016MX    | [31aa08c915](https://linux-hardware.org/?probe=31aa08c915) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [553986db8b](https://linux-hardware.org/?probe=553986db8b) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f73bc25ab5](https://linux-hardware.org/?probe=f73bc25ab5) | Jan 17, 2024 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [ca16a763c8](https://linux-hardware.org/?probe=ca16a763c8) | Jan 17, 2024 |
| System76      | Oryx Pro                    | [db771e1a08](https://linux-hardware.org/?probe=db771e1a08) | Jan 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8578d3d843](https://linux-hardware.org/?probe=8578d3d843) | Jan 15, 2024 |
| Apple         | MacBookPro3,1               | [87d8854210](https://linux-hardware.org/?probe=87d8854210) | Jan 12, 2024 |
| Apple         | MacBookPro11,3              | [9297ef72df](https://linux-hardware.org/?probe=9297ef72df) | Jan 12, 2024 |
| Apple         | MacBookPro11,3              | [17fa0ca044](https://linux-hardware.org/?probe=17fa0ca044) | Jan 12, 2024 |
| Timi          | Xiaomi Book Pro 16 2022     | [ee3988fb25](https://linux-hardware.org/?probe=ee3988fb25) | Jan 09, 2024 |
| Dell          | XPS 15 9530                 | [40a1d7ca08](https://linux-hardware.org/?probe=40a1d7ca08) | Jan 08, 2024 |
| HUAWEI        | WRT-WX9                     | [5b9a494436](https://linux-hardware.org/?probe=5b9a494436) | Jan 08, 2024 |
| Dell          | XPS 9315                    | [af18bb67fd](https://linux-hardware.org/?probe=af18bb67fd) | Jan 08, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [00c7d53339](https://linux-hardware.org/?probe=00c7d53339) | Jan 08, 2024 |
| Fujitsu       | LIFEBOOK U7412              | [e7b60f15e8](https://linux-hardware.org/?probe=e7b60f15e8) | Jan 08, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | [739eae84a2](https://linux-hardware.org/?probe=739eae84a2) | Jan 07, 2024 |
| Dell          | Inspiron 5767               | [460e0f5fa4](https://linux-hardware.org/?probe=460e0f5fa4) | Jan 05, 2024 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [8d22dafe25](https://linux-hardware.org/?probe=8d22dafe25) | Jan 03, 2024 |
| Dynabook      | PORTEGE X30L-K              | [9c965e61f4](https://linux-hardware.org/?probe=9c965e61f4) | Jan 02, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [5ea7f924df](https://linux-hardware.org/?probe=5ea7f924df) | Jan 02, 2024 |
| Lenovo        | ThinkPad Twist 33476LU      | [bb88a71510](https://linux-hardware.org/?probe=bb88a71510) | Jan 01, 2024 |
| System76      | Serval WS                   | [3dd4d45859](https://linux-hardware.org/?probe=3dd4d45859) | Dec 30, 2023 |
| Acer          | Aspire A515-54G             | [35e2f8c10c](https://linux-hardware.org/?probe=35e2f8c10c) | Dec 29, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Dell          | XPS 13 9380                 | [541f2d959f](https://linux-hardware.org/?probe=541f2d959f) | Dec 26, 2023 |
| Fujitsu       | LIFEBOOK U7412              | [a2797ec36b](https://linux-hardware.org/?probe=a2797ec36b) | Dec 26, 2023 |
| HP            | ZBook 17 G5                 | [ad6c489ffc](https://linux-hardware.org/?probe=ad6c489ffc) | Dec 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [ef18e09b69](https://linux-hardware.org/?probe=ef18e09b69) | Dec 23, 2023 |
| Lenovo        | Legion Y7000 81FW           | [f67367aa62](https://linux-hardware.org/?probe=f67367aa62) | Dec 23, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [fb187c2fa4](https://linux-hardware.org/?probe=fb187c2fa4) | Dec 20, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [73693b1a91](https://linux-hardware.org/?probe=73693b1a91) | Dec 17, 2023 |
| Lenovo        | Legion Y7000 81FW           | [71c27a1bf6](https://linux-hardware.org/?probe=71c27a1bf6) | Dec 17, 2023 |
| Medion        | M14L-256                    | [6cd85934b3](https://linux-hardware.org/?probe=6cd85934b3) | Dec 15, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [87be870a89](https://linux-hardware.org/?probe=87be870a89) | Dec 09, 2023 |
| MSI           | Prestige 14 A10SC           | [85d6d037cc](https://linux-hardware.org/?probe=85d6d037cc) | Dec 09, 2023 |
| Dell          | G5 5590                     | [6970987854](https://linux-hardware.org/?probe=6970987854) | Dec 08, 2023 |
| HP            | EliteBook 850 G5            | [aae20908c5](https://linux-hardware.org/?probe=aae20908c5) | Dec 05, 2023 |
| Dell          | Latitude 5290 2-in-1        | [525166f0d5](https://linux-hardware.org/?probe=525166f0d5) | Dec 04, 2023 |
| Apple         | MacBookPro9,2               | [1784c4c5b0](https://linux-hardware.org/?probe=1784c4c5b0) | Dec 01, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [9f7f83e1ee](https://linux-hardware.org/?probe=9f7f83e1ee) | Nov 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [05c1dddd8d](https://linux-hardware.org/?probe=05c1dddd8d) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450s 20BX001MU... | [80d4678e90](https://linux-hardware.org/?probe=80d4678e90) | Nov 23, 2023 |
| HP            | EliteBook 850 G5            | [602aeb4101](https://linux-hardware.org/?probe=602aeb4101) | Nov 22, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [4065934176](https://linux-hardware.org/?probe=4065934176) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [fbde674650](https://linux-hardware.org/?probe=fbde674650) | Nov 22, 2023 |
| Apple         | MacBookPro11,4              | [f21a42a965](https://linux-hardware.org/?probe=f21a42a965) | Nov 16, 2023 |
| Apple         | MacBookPro9,2               | [ac7deed0de](https://linux-hardware.org/?probe=ac7deed0de) | Nov 16, 2023 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [455efd5541](https://linux-hardware.org/?probe=455efd5541) | Nov 15, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [ce6a10d6a3](https://linux-hardware.org/?probe=ce6a10d6a3) | Nov 15, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [789eee99a6](https://linux-hardware.org/?probe=789eee99a6) | Nov 12, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [c55053fa25](https://linux-hardware.org/?probe=c55053fa25) | Nov 12, 2023 |
| HP            | EliteBook 845 14 inch G1... | [dfbaeb29c5](https://linux-hardware.org/?probe=dfbaeb29c5) | Nov 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [79e23fd44a](https://linux-hardware.org/?probe=79e23fd44a) | Nov 07, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [2f6078ab72](https://linux-hardware.org/?probe=2f6078ab72) | Nov 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [49b3b70e38](https://linux-hardware.org/?probe=49b3b70e38) | Nov 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | [0e5f976d6b](https://linux-hardware.org/?probe=0e5f976d6b) | Nov 02, 2023 |
| Dell          | XPS 9315                    | [6f3e496918](https://linux-hardware.org/?probe=6f3e496918) | Oct 29, 2023 |
| HP            | EliteBook 850 G4            | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Apple         | MacBookPro9,2               | [b075cf8841](https://linux-hardware.org/?probe=b075cf8841) | Oct 28, 2023 |
| HP            | EliteBook Folio 9470m       | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | [a80fcc753e](https://linux-hardware.org/?probe=a80fcc753e) | Oct 25, 2023 |
| MSI           | GE70 2PE                    | [c0bcd133c9](https://linux-hardware.org/?probe=c0bcd133c9) | Oct 22, 2023 |
| HP            | EliteBook Folio 9470m       | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Framework     | Laptop                      | [e765d5da63](https://linux-hardware.org/?probe=e765d5da63) | Oct 18, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ba690b36a3](https://linux-hardware.org/?probe=ba690b36a3) | Oct 12, 2023 |
| MSI           | Prestige 16Studio A13VE     | [0209063983](https://linux-hardware.org/?probe=0209063983) | Oct 12, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [7ff5fe9fdd](https://linux-hardware.org/?probe=7ff5fe9fdd) | Oct 11, 2023 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | [a4d6af03fe](https://linux-hardware.org/?probe=a4d6af03fe) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [801a2a4abf](https://linux-hardware.org/?probe=801a2a4abf) | Oct 09, 2023 |
| Dell          | Latitude E6540              | [fc3ea4bb32](https://linux-hardware.org/?probe=fc3ea4bb32) | Oct 08, 2023 |
| Dell          | Inspiron 3542               | [90f777d9cc](https://linux-hardware.org/?probe=90f777d9cc) | Oct 07, 2023 |
| Dell          | Latitude E6540              | [a4fbd5793d](https://linux-hardware.org/?probe=a4fbd5793d) | Oct 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [c67f66f5e3](https://linux-hardware.org/?probe=c67f66f5e3) | Oct 01, 2023 |
| Dell          | Latitude E6540              | [8fdc000f7e](https://linux-hardware.org/?probe=8fdc000f7e) | Oct 01, 2023 |
| Dell          | Latitude E6540              | [a5de8b78e7](https://linux-hardware.org/?probe=a5de8b78e7) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1135ddac8e](https://linux-hardware.org/?probe=1135ddac8e) | Sep 30, 2023 |
| Dell          | Latitude 5430               | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| Dell          | Latitude E6540              | [1478e1265d](https://linux-hardware.org/?probe=1478e1265d) | Sep 29, 2023 |
| Dell          | XPS 15 9560                 | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Dell          | Latitude E6540              | [7d9885cd7c](https://linux-hardware.org/?probe=7d9885cd7c) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | [bf71bcd90e](https://linux-hardware.org/?probe=bf71bcd90e) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Apple         | MacBookPro9,2               | [4d2c8f9f07](https://linux-hardware.org/?probe=4d2c8f9f07) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| Dell          | Latitude E6540              | [ff29b23e60](https://linux-hardware.org/?probe=ff29b23e60) | Sep 13, 2023 |
| Acer          | Aspire E5-575G              | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S4RV00    | [8ae7288bf3](https://linux-hardware.org/?probe=8ae7288bf3) | Sep 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | [5778731f85](https://linux-hardware.org/?probe=5778731f85) | Sep 10, 2023 |
| Dell          | Precision 5680              | [fdcb7ce5d4](https://linux-hardware.org/?probe=fdcb7ce5d4) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 20HES2RC00    | [390104a086](https://linux-hardware.org/?probe=390104a086) | Aug 28, 2023 |
| Dell          | Wyse 5470                   | [6d45205020](https://linux-hardware.org/?probe=6d45205020) | Aug 27, 2023 |
| Lenovo        | G50-70 20351                | [aed7eacff0](https://linux-hardware.org/?probe=aed7eacff0) | Aug 20, 2023 |
| HP            | EliteBook 8470p             | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | [c384115725](https://linux-hardware.org/?probe=c384115725) | Aug 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| System76      | Pangolin                    | [3b37a9bedb](https://linux-hardware.org/?probe=3b37a9bedb) | Jul 29, 2023 |
| Alienware     | 17                          | [25f67e59b8](https://linux-hardware.org/?probe=25f67e59b8) | Jul 26, 2023 |
| Apple         | MacBookPro11,3              | [8d48a50003](https://linux-hardware.org/?probe=8d48a50003) | Jul 22, 2023 |
| Apple         | MacBookPro11,3              | [c29abaca55](https://linux-hardware.org/?probe=c29abaca55) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | 1005HA                      | [59a0d6a7bb](https://linux-hardware.org/?probe=59a0d6a7bb) | Jul 19, 2023 |
| MSI           | Alpha 15 B5EEK              | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4d377fc8b8](https://linux-hardware.org/?probe=4d377fc8b8) | Jul 01, 2023 |
| Dell          | Latitude E5470              | [fd56f44c38](https://linux-hardware.org/?probe=fd56f44c38) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Microtech     | CoreBook Lite               | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [2812cf43d0](https://linux-hardware.org/?probe=2812cf43d0) | Jun 23, 2023 |
| HP            | EliteBook 820 G3            | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| MECHREVO      | WUJIE 14                    | [a55e31b287](https://linux-hardware.org/?probe=a55e31b287) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| MACHENIKE     | F117-7P                     | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| Dell          | Latitude 5290 2-in-1        | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Lenovo        | G50-70 20351                | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Apple         | MacBookPro11,5              | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| UNOWHY        | Y13G011S4EI                 | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| Lenovo        | G50-70 20351                | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| Apple         | MacBookPro11,3              | [7fd17e2245](https://linux-hardware.org/?probe=7fd17e2245) | Apr 22, 2023 |
| Avell High... | A70 MOB                     | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Dell          | XPS 9320                    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| GPD           | G1621-02                    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| ASUSTek       | 1005HA                      | [3326423f04](https://linux-hardware.org/?probe=3326423f04) | Mar 06, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Toshiba       | Satellite L50-B             | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| Blackview     | AceBook 1                   | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| Dell          | Latitude 7420               | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| Dell          | Precision M4800             | [505f1b47dc](https://linux-hardware.org/?probe=505f1b47dc) | Dec 30, 2022 |
| GPD           | WIN2                        | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| MSI           | Raider GE67HX 12UGS         | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| Dell          | XPS 15 7590                 | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| Acer          | Aspire A315-54K             | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| Dell          | Precision 5760              | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Dell          | XPS 13 9310                 | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| Dell          | Inspiron 15 7510            | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Dell          | Precision M4800             | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Apple         | MacBookPro11,5              | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| Apple         | MacBookPro11,5              | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| Dell          | XPS 13 9310                 | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| Apple         | MacBookPro11,5              | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| GPD           | MicroPC                     | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| MSI           | Bravo 15 B5DD               | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Dell          | Latitude 7420               | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | ProBook 445 G7              | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Latitude 7420               | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| HP            | ZBook Studio G5             | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| Lenovo        | ThinkPad T580 20L90024PB    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| Dell          | XPS 15 9550                 | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| Acer          | Aspire E5-576G              | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/NixOS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| NixOS 24.11                      | 148       | 22.46%  |
| NixOS 24.05                      | 115       | 17.45%  |
| NixOS 25.05                      | 105       | 15.93%  |
| NixOS 23.11                      | 73        | 11.08%  |
| NixOS 25.11                      | 67        | 10.17%  |
| NixOS 23.05                      | 62        | 9.41%   |
| NixOS 22.11                      | 27        | 4.1%    |
| NixOS 26.05                      | 21        | 3.19%   |
| NixOS 22.05                      | 18        | 2.73%   |
| NixOS 21.11                      | 9         | 1.37%   |
| NixOS                            | 2         | 0.3%    |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.15%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.15%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.15%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.15%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.15%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.15%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.15%   |
| NixOS 20.09pre-git               | 1         | 0.15%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.15%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.15%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.15%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 596       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Notebooks | Percent |
|----------------|-----------|---------|
| 6.6.32         | 8         | 1.14%   |
| 6.1.69         | 8         | 1.14%   |
| 6.6.63         | 7         | 1%      |
| 6.6.45         | 7         | 1%      |
| 6.6.48         | 6         | 0.86%   |
| 6.12.47        | 6         | 0.86%   |
| 6.12.30        | 6         | 0.86%   |
| 6.10.1-zen1    | 6         | 0.86%   |
| 6.6.8          | 5         | 0.72%   |
| 6.6.54         | 5         | 0.72%   |
| 6.6.49         | 5         | 0.72%   |
| 6.6.28         | 5         | 0.72%   |
| 6.18.0         | 5         | 0.72%   |
| 6.16.0         | 5         | 0.72%   |
| 6.13.1         | 5         | 0.72%   |
| 6.12.57        | 5         | 0.72%   |
| 6.12.1         | 5         | 0.72%   |
| 6.10.8         | 5         | 0.72%   |
| 6.10.6         | 5         | 0.72%   |
| 6.1.82         | 5         | 0.72%   |
| 6.1.55         | 5         | 0.72%   |
| 6.6.87         | 4         | 0.57%   |
| 6.6.43         | 4         | 0.57%   |
| 6.6.41         | 4         | 0.57%   |
| 6.6.39         | 4         | 0.57%   |
| 6.6.30         | 4         | 0.57%   |
| 6.5.5          | 4         | 0.57%   |
| 6.3.8          | 4         | 0.57%   |
| 6.18.1         | 4         | 0.57%   |
| 6.18.0-cachyos | 4         | 0.57%   |
| 6.12.33        | 4         | 0.57%   |
| 6.1.68         | 4         | 0.57%   |
| 6.1.64         | 4         | 0.57%   |
| 6.1.53         | 4         | 0.57%   |
| 6.1.51         | 4         | 0.57%   |
| 6.9.8          | 3         | 0.43%   |
| 6.8.9          | 3         | 0.43%   |
| 6.8.1          | 3         | 0.43%   |
| 6.6.88         | 3         | 0.43%   |
| 6.6.85         | 3         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.18.0  | 9         | 1.29%   |
| 6.6.32  | 8         | 1.15%   |
| 6.10.6  | 8         | 1.15%   |
| 6.1.69  | 8         | 1.15%   |
| 6.6.63  | 7         | 1%      |
| 6.6.45  | 7         | 1%      |
| 6.12.47 | 7         | 1%      |
| 6.10.8  | 7         | 1%      |
| 6.6.8   | 6         | 0.86%   |
| 6.6.48  | 6         | 0.86%   |
| 6.16.0  | 6         | 0.86%   |
| 6.14.0  | 6         | 0.86%   |
| 6.13.1  | 6         | 0.86%   |
| 6.12.30 | 6         | 0.86%   |
| 6.10.1  | 6         | 0.86%   |
| 6.6.54  | 5         | 0.72%   |
| 6.6.49  | 5         | 0.72%   |
| 6.6.28  | 5         | 0.72%   |
| 6.17.7  | 5         | 0.72%   |
| 6.12.57 | 5         | 0.72%   |
| 6.12.1  | 5         | 0.72%   |
| 6.11.5  | 5         | 0.72%   |
| 6.10.7  | 5         | 0.72%   |
| 6.1.82  | 5         | 0.72%   |
| 6.1.55  | 5         | 0.72%   |
| 6.6.87  | 4         | 0.57%   |
| 6.6.43  | 4         | 0.57%   |
| 6.6.41  | 4         | 0.57%   |
| 6.6.39  | 4         | 0.57%   |
| 6.6.30  | 4         | 0.57%   |
| 6.5.5   | 4         | 0.57%   |
| 6.3.8   | 4         | 0.57%   |
| 6.18.1  | 4         | 0.57%   |
| 6.17.9  | 4         | 0.57%   |
| 6.16.8  | 4         | 0.57%   |
| 6.15.0  | 4         | 0.57%   |
| 6.13.7  | 4         | 0.57%   |
| 6.12.33 | 4         | 0.57%   |
| 6.12.0  | 4         | 0.57%   |
| 6.10.5  | 4         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6     | 148       | 22.29%  |
| 6.12    | 99        | 14.91%  |
| 6.1     | 96        | 14.46%  |
| 6.10    | 42        | 6.33%   |
| 5.15    | 31        | 4.67%   |
| 6.17    | 23        | 3.46%   |
| 6.14    | 22        | 3.31%   |
| 6.16    | 21        | 3.16%   |
| 6.13    | 19        | 2.86%   |
| 6.11    | 18        | 2.71%   |
| 6.18    | 16        | 2.41%   |
| 6.15    | 15        | 2.26%   |
| 6.9     | 14        | 2.11%   |
| 6.8     | 14        | 2.11%   |
| 6.7     | 14        | 2.11%   |
| 6.5     | 11        | 1.66%   |
| 6.3     | 11        | 1.66%   |
| 6.4     | 7         | 1.05%   |
| 6.2     | 6         | 0.9%    |
| 6.0     | 6         | 0.9%    |
| 5.16    | 6         | 0.9%    |
| 5.8     | 3         | 0.45%   |
| 5.4     | 3         | 0.45%   |
| 5.19    | 3         | 0.45%   |
| 5.13    | 3         | 0.45%   |
| 5.10    | 3         | 0.45%   |
| 5.7     | 2         | 0.3%    |
| 5.18    | 2         | 0.3%    |
| 5.17    | 2         | 0.3%    |
| 4.19    | 2         | 0.3%    |
| 5.12    | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 593       | 99.5%   |
| aarch64 | 2         | 0.34%   |
| i686    | 1         | 0.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| GNOME        | 152       | 23.94%  |
| Hyprland     | 110       | 17.32%  |
| Unknown      | 88        | 13.86%  |
| KDE6         | 72        | 11.34%  |
| sway         | 50        | 7.87%   |
| KDE          | 47        | 7.4%    |
| KDE5         | 32        | 5.04%   |
| niri         | 22        | 3.46%   |
| none+i3      | 17        | 2.68%   |
| XFCE         | 10        | 1.57%   |
| none+awesome | 5         | 0.79%   |
| COSMIC       | 5         | 0.79%   |
| X-Cinnamon   | 3         | 0.47%   |
| qtile        | 3         | 0.47%   |
| Pantheon     | 3         | 0.47%   |
| none+xmonad  | 3         | 0.47%   |
| LXQt         | 3         | 0.47%   |
| Budgie       | 3         | 0.47%   |
| MATE         | 2         | 0.31%   |
| Unity        | 1         | 0.16%   |
| river        | 1         | 0.16%   |
| none+qtile   | 1         | 0.16%   |
| none+bspwm   | 1         | 0.16%   |
| cwc          | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 377       | 59.75%  |
| Unknown | 153       | 24.25%  |
| X11     | 77        | 12.2%   |
| Tty     | 24        | 3.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| GDM                   | 180       | 28.99%  |
| SDDM                  | 176       | 28.34%  |
| Unknown               | 134       | 21.58%  |
| LightDM               | 60        | 9.66%   |
| GREETD                | 60        | 9.66%   |
| DISPLAY-MANAGER-START | 10        | 1.61%   |
| LEMURS                | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 415       | 68.6%   |
| en_GB      | 47        | 7.77%   |
| Unknown    | 40        | 6.61%   |
| de_DE      | 17        | 2.81%   |
| fr_FR      | 11        | 1.82%   |
| en_CA      | 10        | 1.65%   |
| en_DK      | 8         | 1.32%   |
| en_IN      | 6         | 0.99%   |
| en_AU      | 5         | 0.83%   |
| zh_CN      | 4         | 0.66%   |
| ru_RU      | 4         | 0.66%   |
| pt_PT      | 4         | 0.66%   |
| en_NZ      | 4         | 0.66%   |
| pt_BR      | 3         | 0.5%    |
| pl_PL      | 3         | 0.5%    |
| it_IT      | 3         | 0.5%    |
| C          | 3         | 0.5%    |
| sv_SE      | 2         | 0.33%   |
| en_IE      | 2         | 0.33%   |
| cs_CZ      | 2         | 0.33%   |
| sl_SI      | 1         | 0.17%   |
| ro_RO      | 1         | 0.17%   |
| nb_NO      | 1         | 0.17%   |
| lv_LV      | 1         | 0.17%   |
| lt_LT      | 1         | 0.17%   |
| ja_JP      | 1         | 0.17%   |
| es_MX      | 1         | 0.17%   |
| es_ES      | 1         | 0.17%   |
| en_US.UTF8 | 1         | 0.17%   |
| en_SG      | 1         | 0.17%   |
| en_PH      | 1         | 0.17%   |
| en_EU      | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 566       | 94.65%  |
| BIOS | 32        | 5.35%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 363       | 60%     |
| Btrfs    | 140       | 23.14%  |
| Tmpfs    | 42        | 6.94%   |
| Zfs      | 36        | 5.95%   |
| Xfs      | 13        | 2.15%   |
| Bcachefs | 5         | 0.83%   |
| Unknown  | 4         | 0.66%   |
| F2fs     | 2         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 573       | 95.5%   |
| MBR     | 22        | 3.67%   |
| Unknown | 5         | 0.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 532       | 88.08%  |
| Yes       | 72        | 11.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 467       | 77.7%   |
| Yes       | 134       | 22.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 202       | 33.89%  |
| ASUSTek Computer    | 73        | 12.25%  |
| Hewlett-Packard     | 65        | 10.91%  |
| Dell                | 63        | 10.57%  |
| Framework           | 37        | 6.21%   |
| Apple               | 31        | 5.2%    |
| Acer                | 26        | 4.36%   |
| MSI                 | 13        | 2.18%   |
| HUAWEI              | 10        | 1.68%   |
| TUXEDO              | 6         | 1.01%   |
| GPD                 | 6         | 1.01%   |
| Timi                | 5         | 0.84%   |
| Razer               | 5         | 0.84%   |
| Google              | 5         | 0.84%   |
| System76            | 4         | 0.67%   |
| Gigabyte Technology | 4         | 0.67%   |
| Unknown             | 4         | 0.67%   |
| Samsung Electronics | 3         | 0.5%    |
| MECHREVO            | 3         | 0.5%    |
| Fujitsu             | 3         | 0.5%    |
| Toshiba             | 2         | 0.34%   |
| PC Specialist       | 2         | 0.34%   |
| HONOR               | 2         | 0.34%   |
| Alienware           | 2         | 0.34%   |
| XIAOMI              | 1         | 0.17%   |
| Valve               | 1         | 0.17%   |
| Star Labs           | 1         | 0.17%   |
| Sony                | 1         | 0.17%   |
| SLIMBOOK            | 1         | 0.17%   |
| Semp Toshiba        | 1         | 0.17%   |
| OBSIDIAN-PC         | 1         | 0.17%   |
| Microtech           | 1         | 0.17%   |
| Medion              | 1         | 0.17%   |
| Maibenben           | 1         | 0.17%   |
| MACHENIKE           | 1         | 0.17%   |
| IT Channel Pty      | 1         | 0.17%   |
| Intel               | 1         | 0.17%   |
| Dynabook            | 1         | 0.17%   |
| Corsair             | 1         | 0.17%   |
| Chuwi               | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Framework Laptop 16 (AMD Ryzen 7040 Series)          | 11        | 1.85%   |
| Framework Laptop 13 (AMD Ryzen 7040Series)           | 11        | 1.85%   |
| Apple MacBookPro11,5                                 | 9         | 1.51%   |
| Framework Laptop                                     | 7         | 1.17%   |
| Framework Laptop (12th Gen Intel Core)               | 5         | 0.84%   |
| Apple MacBookPro11,3                                 | 4         | 0.67%   |
| Unknown                                              | 4         | 0.67%   |
| Lenovo ThinkPad T480 20L5CTO1WW                      | 3         | 0.5%    |
| Lenovo ThinkPad T14s Gen 4 21F8CTO1WW                | 3         | 0.5%    |
| Lenovo IdeaPad 3 14ITL05 81X7                        | 3         | 0.5%    |
| HP EliteBook X G1a 14 inch Notebook Next Gen AI PC   | 3         | 0.5%    |
| Dell XPS 9315                                        | 3         | 0.5%    |
| ASUS Zenbook 15 UM3504DA_UM3504DA                    | 3         | 0.5%    |
| ASUS ASUS Zenbook S 16 UM5606WA_UM5606WA             | 3         | 0.5%    |
| TUXEDO InfinityBook Pro Gen7 (MK1)                   | 2         | 0.34%   |
| Timi Redmi Book Pro 14 2022                          | 2         | 0.34%   |
| Razer Blade                                          | 2         | 0.34%   |
| MSI Modern 14 B5M                                    | 2         | 0.34%   |
| MSI Alpha 15 B5EEK                                   | 2         | 0.34%   |
| Lenovo Yoga Pro 7 14AKP10 83KG                       | 2         | 0.34%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW          | 2         | 0.34%   |
| Lenovo Legion Y540-15IRH 81SX                        | 2         | 0.34%   |
| Lenovo Legion Y530-15ICH 81FV                        | 2         | 0.34%   |
| Lenovo Legion S7 15ACH6 82K8                         | 2         | 0.34%   |
| Lenovo Legion R9000P ARX8 82WM                       | 2         | 0.34%   |
| Lenovo Legion 7 16IRX9 83FD                          | 2         | 0.34%   |
| Lenovo IdeaPad Pro 5 14IMH9 83D2                     | 2         | 0.34%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2                  | 2         | 0.34%   |
| Lenovo IdeaPad 5 14ALC05 82LM                        | 2         | 0.34%   |
| HUAWEI VGHH-XX                                       | 2         | 0.34%   |
| HUAWEI HVY-WXX9                                      | 2         | 0.34%   |
| HP ZBook Firefly 14 inch G10 A Mobile Workstation PC | 2         | 0.34%   |
| HP Victus by Laptop 16-e0xxx                         | 2         | 0.34%   |
| HP ProBook 450 G3                                    | 2         | 0.34%   |
| HP Pavilion Laptop 15-eh1xxx                         | 2         | 0.34%   |
| HP OmniBook Ultra Laptop 14-fd0xxx                   | 2         | 0.34%   |
| HP Laptop 15-dy2xxx                                  | 2         | 0.34%   |
| HP EliteBook 8470p                                   | 2         | 0.34%   |
| Gigabyte AERO 15 KD                                  | 2         | 0.34%   |
| Framework Laptop 13 (AMD Ryzen AI 300 Series)        | 2         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 120       | 20.13%  |
| Framework Laptop    | 37        | 6.21%   |
| Lenovo IdeaPad      | 27        | 4.53%   |
| ASUS ROG            | 23        | 3.86%   |
| Lenovo Legion       | 22        | 3.69%   |
| Dell XPS            | 20        | 3.36%   |
| ASUS ASUS           | 19        | 3.19%   |
| HP EliteBook        | 18        | 3.02%   |
| Apple MacBookPro11  | 17        | 2.85%   |
| Lenovo ThinkBook    | 13        | 2.18%   |
| HP Pavilion         | 13        | 2.18%   |
| Dell Latitude       | 13        | 2.18%   |
| Lenovo Yoga         | 12        | 2.01%   |
| Dell Inspiron       | 12        | 2.01%   |
| ASUS Zenbook        | 12        | 2.01%   |
| ASUS Vivobook       | 12        | 2.01%   |
| Acer Aspire         | 12        | 2.01%   |
| Dell Precision      | 9         | 1.51%   |
| HP ZBook            | 8         | 1.34%   |
| HP ProBook          | 8         | 1.34%   |
| Acer Nitro          | 6         | 1.01%   |
| Razer Blade         | 5         | 0.84%   |
| TUXEDO InfinityBook | 4         | 0.67%   |
| HP Victus           | 4         | 0.67%   |
| HP OMEN             | 4         | 0.67%   |
| Acer Swift          | 4         | 0.67%   |
| Unknown             | 4         | 0.67%   |
| Timi Redmi          | 3         | 0.5%    |
| HP Laptop           | 3         | 0.5%    |
| Dell G5             | 3         | 0.5%    |
| Acer Predator       | 3         | 0.5%    |
| TUXEDO Pulse        | 2         | 0.34%   |
| Toshiba Satellite   | 2         | 0.34%   |
| MSI Prestige        | 2         | 0.34%   |
| MSI Modern          | 2         | 0.34%   |
| MSI Alpha           | 2         | 0.34%   |
| HUAWEI VGHH-XX      | 2         | 0.34%   |
| HUAWEI HVY-WXX9     | 2         | 0.34%   |
| HP OmniBook         | 2         | 0.34%   |
| HP ENVY             | 2         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2023    | 94        | 15.77%  |
| 2021    | 87        | 14.6%   |
| 2022    | 72        | 12.08%  |
| 2024    | 65        | 10.91%  |
| 2020    | 46        | 7.72%   |
| 2018    | 42        | 7.05%   |
| 2019    | 36        | 6.04%   |
| 2016    | 27        | 4.53%   |
| 2013    | 22        | 3.69%   |
| 2017    | 19        | 3.19%   |
| 2015    | 18        | 3.02%   |
| 2025    | 15        | 2.52%   |
| 2014    | 14        | 2.35%   |
| 2011    | 13        | 2.18%   |
| 2012    | 11        | 1.85%   |
| 2008    | 5         | 0.84%   |
| 2010    | 3         | 0.5%    |
| 2009    | 2         | 0.34%   |
| 2007    | 2         | 0.34%   |
| Unknown | 2         | 0.34%   |
| 2006    | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 596       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 564       | 93.84%  |
| Enabled  | 37        | 6.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 585       | 98.15%  |
| Yes  | 11        | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 156       | 26.09%  |
| 8.01-16.0   | 152       | 25.42%  |
| 16.01-24.0  | 125       | 20.9%   |
| 4.01-8.0    | 75        | 12.54%  |
| 24.01-32.0  | 41        | 6.86%   |
| 64.01-256.0 | 29        | 4.85%   |
| 3.01-4.0    | 17        | 2.84%   |
| 2.01-3.0    | 1         | 0.17%   |
| 1.01-2.0    | 1         | 0.17%   |
| 0.51-1.0    | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 218       | 33.13%  |
| 8.01-16.0  | 117       | 17.78%  |
| 2.01-3.0   | 107       | 16.26%  |
| 3.01-4.0   | 106       | 16.11%  |
| 1.01-2.0   | 51        | 7.75%   |
| 16.01-24.0 | 25        | 3.8%    |
| 0.51-1.0   | 13        | 1.98%   |
| 24.01-32.0 | 11        | 1.67%   |
| 0.01-0.5   | 6         | 0.91%   |
| 32.01-64.0 | 4         | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 466       | 77.41%  |
| 2      | 121       | 20.1%   |
| 3      | 11        | 1.83%   |
| 0      | 2         | 0.33%   |
| 6      | 1         | 0.17%   |
| 4      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 559       | 93.48%  |
| Yes       | 39        | 6.52%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 401       | 66.61%  |
| No        | 201       | 33.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 555       | 93.12%  |
| No        | 41        | 6.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 555       | 92.81%  |
| No        | 43        | 7.19%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| USA             | 113       | 18.77%  |
| Germany         | 72        | 11.96%  |
| Russia          | 30        | 4.98%   |
| France          | 27        | 4.49%   |
| UK              | 20        | 3.32%   |
| Netherlands     | 19        | 3.16%   |
| Poland          | 17        | 2.82%   |
| Italy           | 17        | 2.82%   |
| Canada          | 16        | 2.66%   |
| Czechia         | 14        | 2.33%   |
| Brazil          | 13        | 2.16%   |
| Spain           | 12        | 1.99%   |
| Portugal        | 12        | 1.99%   |
| India           | 12        | 1.99%   |
| Japan           | 11        | 1.83%   |
| Sweden          | 9         | 1.5%    |
| Romania         | 8         | 1.33%   |
| Austria         | 8         | 1.33%   |
| Thailand        | 7         | 1.16%   |
| Switzerland     | 7         | 1.16%   |
| Norway          | 7         | 1.16%   |
| Ukraine         | 6         | 1%      |
| Turkey          | 6         | 1%      |
| Hong Kong       | 6         | 1%      |
| Denmark         | 6         | 1%      |
| Australia       | 6         | 1%      |
| Vietnam         | 5         | 0.83%   |
| Singapore       | 5         | 0.83%   |
| New Zealand     | 5         | 0.83%   |
| Indonesia       | 5         | 0.83%   |
| Finland         | 5         | 0.83%   |
| Belgium         | 5         | 0.83%   |
| Uruguay         | 4         | 0.66%   |
| Saudi Arabia    | 4         | 0.66%   |
| Hungary         | 4         | 0.66%   |
| Georgia         | 4         | 0.66%   |
| China           | 4         | 0.66%   |
| Argentina       | 4         | 0.66%   |
| Tunisia         | 3         | 0.5%    |
| The Netherlands | 3         | 0.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 13        | 2.05%   |
| Warsaw           | 7         | 1.11%   |
| Vienna           | 7         | 1.11%   |
| Berlin           | 7         | 1.11%   |
| Tokyo            | 6         | 0.95%   |
| Prague           | 6         | 0.95%   |
| Amsterdam        | 6         | 0.95%   |
| Singapore        | 5         | 0.79%   |
| London           | 5         | 0.79%   |
| Cologne          | 5         | 0.79%   |
| Bangkok          | 5         | 0.79%   |
| Tbilisi          | 4         | 0.63%   |
| St Petersburg    | 4         | 0.63%   |
| Seattle          | 4         | 0.63%   |
| Porto            | 4         | 0.63%   |
| Paris            | 4         | 0.63%   |
| Oslo             | 4         | 0.63%   |
| Los Angeles      | 4         | 0.63%   |
| Ho Chi Minh City | 4         | 0.63%   |
| Chicago          | 4         | 0.63%   |
| Central          | 4         | 0.63%   |
| Zurich           | 3         | 0.47%   |
| Tiefenbach       | 3         | 0.47%   |
| Tallinn          | 3         | 0.47%   |
| San Diego        | 3         | 0.47%   |
| Salt Lake City   | 3         | 0.47%   |
| Rochester        | 3         | 0.47%   |
| Richmond         | 3         | 0.47%   |
| Montevideo       | 3         | 0.47%   |
| Izmir            | 3         | 0.47%   |
| Hanover          | 3         | 0.47%   |
| Hamburg          | 3         | 0.47%   |
| Haarlem          | 3         | 0.47%   |
| Enschede         | 3         | 0.47%   |
| Dresden          | 3         | 0.47%   |
| Craigsville      | 3         | 0.47%   |
| Bothell          | 3         | 0.47%   |
| Bengaluru        | 3         | 0.47%   |
| Belgrade         | 3         | 0.47%   |
| Bedford          | 3         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 170       | 226    | 23.45%  |
| Unknown                      | 71        | 77     | 9.79%   |
| SK hynix                     | 58        | 71     | 8%      |
| SanDisk                      | 56        | 59     | 7.72%   |
| Micron Technology            | 41        | 48     | 5.66%   |
| WDC                          | 36        | 38     | 4.97%   |
| Crucial                      | 27        | 29     | 3.72%   |
| Apple                        | 27        | 36     | 3.72%   |
| Kingston                     | 24        | 31     | 3.31%   |
| Seagate                      | 22        | 25     | 3.03%   |
| Intel                        | 22        | 24     | 3.03%   |
| Toshiba                      | 21        | 23     | 2.9%    |
| KIOXIA                       | 18        | 27     | 2.48%   |
| Kingston Technology Company  | 10        | 11     | 1.38%   |
| A-DATA Technology            | 8         | 10     | 1.1%    |
| UMIS                         | 7         | 9      | 0.97%   |
| MAXIO Technology (Hangzhou)  | 7         | 8      | 0.97%   |
| Union Memory (Shenzhen)      | 6         | 8      | 0.83%   |
| Phison Electronics           | 6         | 8      | 0.83%   |
| Silicon Motion               | 5         | 5      | 0.69%   |
| Phison                       | 5         | 5      | 0.69%   |
| Unknown                      | 5         | 5      | 0.69%   |
| Micron/Crucial Technology    | 4         | 4      | 0.55%   |
| HGST                         | 4         | 5      | 0.55%   |
| Yangtze Memory Technologies  | 3         | 5      | 0.41%   |
| Shenzhen Longsys Electronics | 3         | 4      | 0.41%   |
| Realtek                      | 3         | 3      | 0.41%   |
| LITEONIT                     | 3         | 3      | 0.41%   |
| Lexar                        | 3         | 3      | 0.41%   |
| Corsair                      | 3         | 3      | 0.41%   |
| Transcend                    | 2         | 2      | 0.28%   |
| SPCC                         | 2         | 2      | 0.28%   |
| SOLIDIGM                     | 2         | 3      | 0.28%   |
| PNY                          | 2         | 4      | 0.28%   |
| LITEON                       | 2         | 2      | 0.28%   |
| Hitachi                      | 2         | 3      | 0.28%   |
| GOODRAM                      | 2         | 2      | 0.28%   |
| China                        | 2         | 2      | 0.28%   |
| YMTC                         | 1         | 1      | 0.14%   |
| Union Memory                 | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown NVMe SSD Drive 1TB                         | 31        | 4.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 22        | 2.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 22        | 2.92%   |
| Unknown NVMe SSD Drive 2TB                         | 12        | 1.59%   |
| Apple SSD SM0512G 500GB                            | 9         | 1.19%   |
| Micron MTFDKBA1T0QFM-1BD1AABGB 1024GB              | 8         | 1.06%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 7         | 0.93%   |
| Samsung SSD 990 PRO 1TB                            | 7         | 0.93%   |
| Intel SSDPEKNU512GZ 512GB                          | 7         | 0.93%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1024GB            | 6         | 0.8%    |
| Kingston OM8PCP3512F-AI1 512GB                     | 6         | 0.8%    |
| Unknown MMC Card  32GB                             | 5         | 0.66%   |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 5         | 0.66%   |
| SK hynix HFM001TD3JX013N 1024GB                    | 5         | 0.66%   |
| Sandisk WD_BLACK SN770 1TB                         | 5         | 0.66%   |
| Samsung SSD 870 EVO 500GB                          | 5         | 0.66%   |
| Samsung SSD 850 EVO 250GB                          | 5         | 0.66%   |
| KIOXIA KBG50ZNV512G 512GB                          | 5         | 0.66%   |
| Unknown                                            | 5         | 0.66%   |
| Unknown NVMe SSD Drive 512GB                       | 4         | 0.53%   |
| Seagate ST1000LM035-1RK172 1TB                     | 4         | 0.53%   |
| Samsung SSD 990 PRO 4TB                            | 4         | 0.53%   |
| Samsung SSD 980 1TB                                | 4         | 0.53%   |
| Samsung SSD 850 EVO 500GB                          | 4         | 0.53%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                   | 4         | 0.53%   |
| Micron 3400_MTFDKBA1T0TFH 1024GB                   | 4         | 0.53%   |
| Kingston SNVS500G 500GB                            | 4         | 0.53%   |
| Unknown MMC Card  64GB                             | 3         | 0.4%    |
| Unknown MMC Card  128GB                            | 3         | 0.4%    |
| SK hynix SKHynix_HFS001TEJ9X162N 1024GB            | 3         | 0.4%    |
| SK hynix SKHynix_HFS001TEJ4X112N 1024GB            | 3         | 0.4%    |
| SK hynix PC801 NVMe 512GB                          | 3         | 0.4%    |
| SK hynix PC711 HFS512GDE9X073N 512GB               | 3         | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB                     | 3         | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 3         | 0.4%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB    | 3         | 0.4%    |
| Samsung SSD 990 PRO 2TB                            | 3         | 0.4%    |
| Samsung SSD 860 EVO 500GB                          | 3         | 0.4%    |
| Samsung PM9F1 1024GB                               | 3         | 0.4%    |
| Samsung MZVLQ512HBLU-00B00 512GB                   | 3         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 42%     |
| WDC                 | 13        | 13     | 26%     |
| Toshiba             | 6         | 6      | 12%     |
| HGST                | 4         | 5      | 8%      |
| Hitachi             | 2         | 3      | 4%      |
| Unknown             | 1         | 1      | 2%      |
| Samsung Electronics | 1         | 1      | 2%      |
| External            | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 41     | 26.12%  |
| Apple               | 20        | 23     | 14.93%  |
| Crucial             | 15        | 16     | 11.19%  |
| SanDisk             | 11        | 11     | 8.21%   |
| Kingston            | 9         | 13     | 6.72%   |
| SK hynix            | 4         | 5      | 2.99%   |
| LITEONIT            | 3         | 3      | 2.24%   |
| A-DATA Technology   | 3         | 3      | 2.24%   |
| WDC                 | 2         | 2      | 1.49%   |
| Transcend           | 2         | 2      | 1.49%   |
| Toshiba             | 2         | 2      | 1.49%   |
| PNY                 | 2         | 4      | 1.49%   |
| Micron Technology   | 2         | 2      | 1.49%   |
| Lexar               | 2         | 2      | 1.49%   |
| Corsair             | 2         | 2      | 1.49%   |
| China               | 2         | 2      | 1.49%   |
| Unknown             | 2         | 2      | 1.49%   |
| Unknown             | 1         | 1      | 0.75%   |
| Team                | 1         | 1      | 0.75%   |
| SPCC                | 1         | 1      | 0.75%   |
| S3+                 | 1         | 1      | 0.75%   |
| Ramaxel Technology  | 1         | 1      | 0.75%   |
| Phison              | 1         | 1      | 0.75%   |
| Patriot             | 1         | 1      | 0.75%   |
| Netac               | 1         | 1      | 0.75%   |
| Neo Forza           | 1         | 1      | 0.75%   |
| LITEON              | 1         | 1      | 0.75%   |
| INNOVATION IT       | 1         | 1      | 0.75%   |
| Indilinx            | 1         | 1      | 0.75%   |
| GOODRAM             | 1         | 1      | 0.75%   |
| Dogfish             | 1         | 1      | 0.75%   |
| BIWIN               | 1         | 1      | 0.75%   |
| Apacer              | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 473       | 637    | 70.7%   |
| SSD     | 126       | 151    | 18.83%  |
| HDD     | 49        | 55     | 7.32%   |
| MMC     | 19        | 22     | 2.84%   |
| Unknown | 2         | 2      | 0.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 473       | 631    | 71.99%  |
| SATA | 145       | 191    | 22.07%  |
| SAS  | 20        | 23     | 3.04%   |
| MMC  | 19        | 22     | 2.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 135    | 64%     |
| 0.51-1.0   | 51        | 57     | 29.14%  |
| 1.01-2.0   | 11        | 13     | 6.29%   |
| 4.01-10.0  | 1         | 1      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 185       | 30.18%  |
| 251-500        | 101       | 16.48%  |
| 501-1000       | 89        | 14.52%  |
| 101-250        | 72        | 11.75%  |
| 1001-2000      | 49        | 7.99%   |
| Unknown        | 47        | 7.67%   |
| More than 3000 | 41        | 6.69%   |
| 2001-3000      | 25        | 4.08%   |
| 51-100         | 3         | 0.49%   |
| 21-50          | 1         | 0.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 234       | 36.91%  |
| 101-250        | 88        | 13.88%  |
| 251-500        | 63        | 9.94%   |
| 21-50          | 57        | 8.99%   |
| 51-100         | 55        | 8.68%   |
| Unknown        | 47        | 7.41%   |
| 501-1000       | 38        | 5.99%   |
| 1001-2000      | 23        | 3.63%   |
| 2001-3000      | 15        | 2.37%   |
| More than 3000 | 14        | 2.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Notebooks | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS512GDE9X073N 512GB                          | 3         | 3      | 8.11%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                         | 2         | 3      | 5.41%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                          | 2         | 2      | 5.41%   |
| A-DATA Technology IM2P33F3A NVMe 256GB                        | 2         | 4      | 5.41%   |
| WDC WD5000BEVT-24A0RT0 500GB                                  | 1         | 1      | 2.7%    |
| WDC WD10SPZX-21Z10T0 1TB                                      | 1         | 1      | 2.7%    |
| WDC WD10JPVX-08JC3T5 1TB                                      | 1         | 1      | 2.7%    |
| WDC WD10 JPLX-00MBPT0 1TB                                     | 1         | 1      | 2.7%    |
| Union Memory UMIS RPITJ512PED2OWX 512GB                       | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD100 1TB                                        | 1         | 1      | 2.7%    |
| Toshiba MK2565GSXV 250GB                                      | 1         | 1      | 2.7%    |
| SK hynix SC210 2.5 7MM 256GB SSD                              | 1         | 1      | 2.7%    |
| SK hynix BC501 NVMe Solid State Drive 512GB                   | 1         | 1      | 2.7%    |
| Seagate ST9320325AS 320GB                                     | 1         | 2      | 2.7%    |
| Seagate ST500LT012-9WS142 500GB                               | 1         | 1      | 2.7%    |
| Seagate ST2000LM015-2E8174 2TB                                | 1         | 1      | 2.7%    |
| Seagate ST1000LM049-2GH172 1TB                                | 1         | 1      | 2.7%    |
| Seagate ST1000LM035-1RK172 1TB                                | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 870 EVO 500GB                         | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 870 EVO 2TB                           | 1         | 1      | 2.7%    |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 1      | 2.7%    |
| Samsung Electronics HM160HI 160GB                             | 1         | 1      | 2.7%    |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB                | 1         | 1      | 2.7%    |
| Micron Technology MTFDKBA512TFK-1BC1AABHA 512GB               | 1         | 2      | 2.7%    |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD                | 1         | 1      | 2.7%    |
| LITEON CV8-8E128-HP 128GB SSD                                 | 1         | 1      | 2.7%    |
| Kingston SNV425S2128GB SSD                                    | 1         | 1      | 2.7%    |
| Intel SSDPEKKF512G8L 512GB                                    | 1         | 1      | 2.7%    |
| Hitachi HTS723232A7A364 320GB                                 | 1         | 1      | 2.7%    |
| HGST HTS725050A7E630 500GB                                    | 1         | 1      | 2.7%    |
| Crucial CT120M500SSD3 120GB                                   | 1         | 1      | 2.7%    |
| Corsair Force GS 240GB SSD                                    | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| SK hynix                  | 9         | 10     | 24.32%  |
| Seagate                   | 5         | 6      | 13.51%  |
| WDC                       | 4         | 4      | 10.81%  |
| Samsung Electronics       | 4         | 4      | 10.81%  |
| Toshiba                   | 2         | 2      | 5.41%   |
| Micron Technology         | 2         | 3      | 5.41%   |
| A-DATA Technology         | 2         | 4      | 5.41%   |
| Union Memory              | 1         | 1      | 2.7%    |
| Micron/Crucial Technology | 1         | 1      | 2.7%    |
| LITEON                    | 1         | 1      | 2.7%    |
| Kingston                  | 1         | 1      | 2.7%    |
| Intel                     | 1         | 1      | 2.7%    |
| Hitachi                   | 1         | 1      | 2.7%    |
| HGST                      | 1         | 1      | 2.7%    |
| Crucial                   | 1         | 1      | 2.7%    |
| Corsair                   | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 35.71%  |
| WDC                 | 4         | 4      | 28.57%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 15     | 37.84%  |
| NVMe | 13        | 16     | 35.14%  |
| SSD  | 10        | 11     | 27.03%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 50%     |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| HGST                | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 526       | 722    | 80.43%  |
| Detected | 91        | 101    | 13.91%  |
| Malfunc  | 35        | 42     | 5.35%   |
| Failed   | 2         | 2      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 206       | 27.76%  |
| Samsung Electronics                     | 150       | 20.22%  |
| SanDisk                                 | 112       | 15.09%  |
| SK hynix                                | 54        | 7.28%   |
| Micron Technology                       | 44        | 5.93%   |
| AMD                                     | 27        | 3.64%   |
| Kingston Technology Company             | 26        | 3.5%    |
| KIOXIA                                  | 18        | 2.43%   |
| Toshiba America Info Systems            | 14        | 1.89%   |
| Phison Electronics                      | 13        | 1.75%   |
| Micron/Crucial Technology               | 11        | 1.48%   |
| MAXIO Technology (Hangzhou)             | 11        | 1.48%   |
| Shenzhen Unionmemory Information System | 9         | 1.21%   |
| ADATA Technology                        | 6         | 0.81%   |
| Union Memory (Shenzhen)                 | 5         | 0.67%   |
| Silicon Motion                          | 5         | 0.67%   |
| Yangtze Memory Technologies             | 4         | 0.54%   |
| Shenzhen Longsys Electronics            | 4         | 0.54%   |
| Apple                                   | 4         | 0.54%   |
| Solidigm                                | 3         | 0.4%    |
| Solid State Storage Technology          | 2         | 0.27%   |
| Realtek Semiconductor                   | 2         | 0.27%   |
| Lite-On Technology                      | 2         | 0.27%   |
| VIA Technologies                        | 1         | 0.13%   |
| TenaFe                                  | 1         | 0.13%   |
| Shenzhen Shichuangyi Electronics        | 1         | 0.13%   |
| O2 Micro                                | 1         | 0.13%   |
| Netac Technology                        | 1         | 0.13%   |
| Marvell Technology Group                | 1         | 0.13%   |
| Lenovo                                  | 1         | 0.13%   |
| INNOGRIT                                | 1         | 0.13%   |
| Biwin Storage Technology                | 1         | 0.13%   |
| Unknown                                 | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 37        | 4.84%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 34        | 4.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 34        | 4.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 25        | 3.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 24        | 3.14%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 3.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 23        | 3.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 22        | 2.88%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 21        | 2.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 20        | 2.62%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 16        | 2.09%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 16        | 2.09%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 14        | 1.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 1.83%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 14        | 1.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 1.7%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 12        | 1.57%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 11        | 1.44%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 11        | 1.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 1.44%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 10        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 1.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 1.18%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 9         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 1.18%   |
| KIOXIA NVMe SSD Controller XG8                                                 | 8         | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 1.05%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 7         | 0.92%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                 | 7         | 0.92%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7         | 0.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 0.92%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 6         | 0.79%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 6         | 0.79%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 6         | 0.79%   |
| Micron 2550 NVMe SSD (DRAM-less)                                               | 6         | 0.79%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 6         | 0.79%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 6         | 0.79%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 6         | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 6         | 0.79%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 6         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 469       | 65.96%  |
| SATA | 192       | 27%     |
| RAID | 47        | 6.61%   |
| IDE  | 3         | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 380       | 63.76%  |
| AMD     | 214       | 35.91%  |
| Unknown | 2         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                 | 11        | 1.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 11        | 1.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 1.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.68%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics    | 10        | 1.68%   |
| AMD Ryzen AI 9 HX 370 w/ Radeon 890M          | 9         | 1.51%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 9         | 1.51%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 1.51%   |
| Intel Core Ultra 7 155H                       | 8         | 1.34%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.34%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 8         | 1.34%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 8         | 1.34%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.17%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 7         | 1.17%   |
| AMD Ryzen 7 PRO 7840U w/ Radeon 780M Graphics | 7         | 1.17%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 7         | 1.17%   |
| AMD Ryzen 5 7640U w/ Radeon 760M Graphics     | 7         | 1.17%   |
| Intel Core Ultra 9 185H                       | 6         | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.01%   |
| Intel 12th Gen Core i7-1260P                  | 6         | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 1.01%   |
| Intel Core Ultra 7 258V                       | 5         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.84%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 0.84%   |
| AMD Ryzen 7 5800HS with Radeon Graphics       | 5         | 0.84%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 0.84%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 4         | 0.67%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 0.67%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.67%   |
| Intel 13th Gen Core i9-13900HX                | 4         | 0.67%   |
| Intel 13th Gen Core i9-13900H                 | 4         | 0.67%   |
| Intel 13th Gen Core i7-13700H                 | 4         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Other              | 151       | 25.34%  |
| Intel Core i7      | 121       | 20.3%   |
| AMD Ryzen 7        | 82        | 13.76%  |
| Intel Core i5      | 69        | 11.58%  |
| AMD Ryzen 5        | 40        | 6.71%   |
| AMD Ryzen 7 PRO    | 32        | 5.37%   |
| Intel Core         | 31        | 5.2%    |
| AMD Ryzen 9        | 25        | 4.19%   |
| AMD Ryzen 5 PRO    | 8         | 1.34%   |
| Intel Celeron      | 7         | 1.17%   |
| Intel Core i3      | 6         | 1.01%   |
| Intel Core i9      | 5         | 0.84%   |
| Intel Pentium      | 4         | 0.67%   |
| AMD Ryzen 3        | 4         | 0.67%   |
| Intel Xeon         | 2         | 0.34%   |
| Intel Core 2 Duo   | 2         | 0.34%   |
| Intel Atom         | 2         | 0.34%   |
| Intel Pentium Gold | 1         | 0.17%   |
| Intel Core m3      | 1         | 0.17%   |
| Intel Celeron M    | 1         | 0.17%   |
| AMD Ryzen 3 PRO    | 1         | 0.17%   |
| AMD A12            | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 162       | 27.18%  |
| 8      | 159       | 26.68%  |
| 2      | 89        | 14.93%  |
| 6      | 59        | 9.9%    |
| 12     | 36        | 6.04%   |
| 14     | 29        | 4.87%   |
| 10     | 26        | 4.36%   |
| 16     | 25        | 4.19%   |
| 24     | 9         | 1.51%   |
| 1      | 2         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 596       | 99.83%  |
| 16     | 1         | 0.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 561       | 94.13%  |
| 1      | 35        | 5.87%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 593       | 99.33%  |
| 64-bit         | 2         | 0.34%   |
| 32-bit         | 1         | 0.17%   |
| Unknown        | 1         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 425       | 69.33%  |
| 0x0a50000c | 18        | 2.94%   |
| 0x08600106 | 12        | 1.96%   |
| 0x806ea    | 9         | 1.47%   |
| 0x40661    | 9         | 1.47%   |
| 0x906ea    | 7         | 1.14%   |
| 0x806c1    | 7         | 1.14%   |
| 0x306d4    | 7         | 1.14%   |
| 0x0a50000d | 6         | 0.98%   |
| 0x08608103 | 6         | 0.98%   |
| 0x906a3    | 5         | 0.82%   |
| 0x806e9    | 5         | 0.82%   |
| 0x306c3    | 5         | 0.82%   |
| 0x0a704104 | 5         | 0.82%   |
| 0x0a704103 | 5         | 0.82%   |
| 0x08108109 | 5         | 0.82%   |
| 0x906e9    | 4         | 0.65%   |
| 0x806ec    | 4         | 0.65%   |
| 0x806eb    | 4         | 0.65%   |
| 0x406e3    | 4         | 0.65%   |
| 0x40651    | 4         | 0.65%   |
| 0x306a9    | 4         | 0.65%   |
| 0x0a404102 | 4         | 0.65%   |
| 0x506e3    | 3         | 0.49%   |
| 0x0a404101 | 3         | 0.49%   |
| 0xb06a3    | 2         | 0.33%   |
| 0xb06a2    | 2         | 0.33%   |
| 0xb0671    | 2         | 0.33%   |
| 0xa0660    | 2         | 0.33%   |
| 0x906ed    | 2         | 0.33%   |
| 0x906a4    | 2         | 0.33%   |
| 0x706a8    | 2         | 0.33%   |
| 0x706a1    | 2         | 0.33%   |
| 0x0b204037 | 2         | 0.33%   |
| 0x0a704107 | 2         | 0.33%   |
| 0x0a500011 | 2         | 0.33%   |
| 0x0a404105 | 2         | 0.33%   |
| 0x08a00008 | 2         | 0.33%   |
| 0x08600104 | 2         | 0.33%   |
| 0x08108102 | 2         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Unknown            | 142       | 23.75%  |
| KabyLake           | 91        | 15.22%  |
| Alderlake Hybrid   | 75        | 12.54%  |
| Zen 3              | 50        | 8.36%   |
| Haswell            | 37        | 6.19%   |
| TigerLake          | 36        | 6.02%   |
| Zen 2              | 21        | 3.51%   |
| Meteorlake Hybrid  | 20        | 3.34%   |
| Icelake            | 18        | 3.01%   |
| Skylake            | 17        | 2.84%   |
| Broadwell          | 16        | 2.68%   |
| IvyBridge          | 13        | 2.17%   |
| Zen+               | 11        | 1.84%   |
| SandyBridge        | 11        | 1.84%   |
| CometLake          | 10        | 1.67%   |
| Lunarlake Hybrid   | 6         | 1%      |
| Goldmont plus      | 4         | 0.67%   |
| ArrowLake-H Hybrid | 4         | 0.67%   |
| Westmere           | 3         | 0.5%    |
| Zen                | 2         | 0.33%   |
| Gracemont          | 2         | 0.33%   |
| Goldmont           | 2         | 0.33%   |
| Core               | 2         | 0.33%   |
| Bonnell            | 2         | 0.33%   |
| Silvermont         | 1         | 0.17%   |
| Penryn             | 1         | 0.17%   |
| Excavator          | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 356       | 46.11%  |
| AMD              | 234       | 30.31%  |
| Nvidia           | 181       | 23.45%  |
| VIA Technologies | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Phoenix1                                                              | 39        | 4.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 39        | 4.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 31        | 3.9%    |
| AMD Rembrandt [Radeon 680M]                                               | 28        | 3.53%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 26        | 3.27%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 26        | 3.27%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 24        | 3.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 22        | 2.77%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 20        | 2.52%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 19        | 2.39%   |
| AMD Lucienne                                                              | 18        | 2.27%   |
| AMD Strix [Radeon 880M / 890M]                                            | 17        | 2.14%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                  | 16        | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 14        | 1.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 14        | 1.76%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 13        | 1.64%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                           | 12        | 1.51%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 12        | 1.51%   |
| AMD HawkPoint1                                                            | 12        | 1.51%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 11        | 1.39%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 11        | 1.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 11        | 1.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 11        | 1.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 11        | 1.39%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 10        | 1.26%   |
| Intel Raptor Lake-S UHD Graphics                                          | 10        | 1.26%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 10        | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 10        | 1.26%   |
| AMD Barcelo                                                               | 10        | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 9         | 1.13%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                           | 9         | 1.13%   |
| Nvidia GP108M [GeForce MX150]                                             | 8         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 8         | 1.01%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 8         | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 8         | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 8         | 1.01%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]     | 8         | 1.01%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                   | 7         | 0.88%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 7         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 6         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 219       | 36.68%  |
| 1 x AMD        | 159       | 26.63%  |
| Intel + Nvidia | 122       | 20.44%  |
| AMD + Nvidia   | 42        | 7.04%   |
| 2 x AMD        | 20        | 3.35%   |
| 1 x Nvidia     | 17        | 2.85%   |
| Intel + AMD    | 13        | 2.18%   |
| Other          | 2         | 0.34%   |
| 2 x Intel      | 2         | 0.34%   |
| 1 x VIA        | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 489       | 80.96%  |
| Proprietary | 91        | 15.07%  |
| Unknown     | 24        | 3.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 365       | 60.13%  |
| 0.01-0.5   | 106       | 17.46%  |
| 1.01-2.0   | 44        | 7.25%   |
| 3.01-4.0   | 35        | 5.77%   |
| 0.51-1.0   | 27        | 4.45%   |
| 7.01-8.0   | 19        | 3.13%   |
| 8.01-16.0  | 6         | 0.99%   |
| 5.01-6.0   | 4         | 0.66%   |
| 2.01-3.0   | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 145       | 19.67%  |
| AU Optronics         | 109       | 14.79%  |
| Samsung Electronics  | 74        | 10.04%  |
| LG Display           | 65        | 8.82%   |
| Chimei Innolux       | 63        | 8.55%   |
| Apple                | 31        | 4.21%   |
| Dell                 | 29        | 3.93%   |
| Lenovo               | 28        | 3.8%    |
| Sharp                | 25        | 3.39%   |
| Goldstar             | 24        | 3.26%   |
| Hewlett-Packard      | 13        | 1.76%   |
| CSO                  | 13        | 1.76%   |
| PANDA                | 12        | 1.63%   |
| TMX                  | 10        | 1.36%   |
| InfoVision           | 10        | 1.36%   |
| ASUSTek Computer     | 9         | 1.22%   |
| Acer                 | 8         | 1.09%   |
| Philips              | 6         | 0.81%   |
| AOC                  | 6         | 0.81%   |
| Ancor Communications | 6         | 0.81%   |
| CSOT                 | 5         | 0.68%   |
| MSI                  | 4         | 0.54%   |
| HKC                  | 3         | 0.41%   |
| ViewSonic            | 2         | 0.27%   |
| Toshiba              | 2         | 0.27%   |
| TMA                  | 2         | 0.27%   |
| Panasonic            | 2         | 0.27%   |
| Mi                   | 2         | 0.27%   |
| JDI                  | 2         | 0.27%   |
| Iiyama               | 2         | 0.27%   |
| HannStar             | 2         | 0.27%   |
| Gigabyte Technology  | 2         | 0.27%   |
| BenQ                 | 2         | 0.27%   |
| VXN                  | 1         | 0.14%   |
| VLK                  | 1         | 0.14%   |
| Vestel Elektronik    | 1         | 0.14%   |
| Valve                | 1         | 0.14%   |
| SKG                  | 1         | 0.14%   |
| SGT                  | 1         | 0.14%   |
| Sceptre Tech         | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0BC9 2560x1600 345x215mm 16.0-inch                  | 10        | 1.35%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 10        | 1.35%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                  | 9         | 1.21%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                  | 8         | 1.08%   |
| BOE NE135A1M-NY1 BOE0CB4 2880x1920 285x190mm 13.5-inch                 | 6         | 0.81%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 6         | 0.81%   |
| Samsung Electronics LCD Monitor SDC419D 2880x1800 302x189mm 14.0-inch  | 5         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 5         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1614 1920x1200 344x215mm 16.0-inch       | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch          | 4         | 0.54%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SDC41B3 2880x1800 302x189mm 14.0-inch  | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SDC419F 2880x1800 302x189mm 14.0-inch  | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch  | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 3         | 0.4%    |
| Samsung Electronics ATNA60CL10-0 SDC41AF 2880x1800 344x215mm 16.0-inch | 3         | 0.4%    |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch           | 3         | 0.4%    |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 3         | 0.4%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 3         | 0.4%    |
| Lenovo B140UAN02.7 LEN403A 1920x1200 302x188mm 14.0-inch               | 3         | 0.4%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 3         | 0.4%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 3         | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3         | 0.4%    |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch       | 3         | 0.4%    |
| BOE NE160WUM-NX2 BOE0B33 1920x1200 345x215mm 16.0-inch                 | 3         | 0.4%    |
| BOE LCD Monitor BOE0B56 1920x1080 309x174mm 14.0-inch                  | 3         | 0.4%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                  | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch         | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch         | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO0B93 1920x1080 309x174mm 14.0-inch         | 3         | 0.4%    |
| Apple Color LCD APPA02F 2880x1800 331x207mm 15.4-inch                  | 3         | 0.4%    |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                  | 3         | 0.4%    |
| Toshiba ScreenXpert TSB8888 1080x2160                                  | 2         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 270       | 38.46%  |
| 1920x1200 (WUXGA)  | 65        | 9.26%   |
| 2880x1800          | 57        | 8.12%   |
| 3840x2160 (4K)     | 54        | 7.69%   |
| 2560x1600          | 53        | 7.55%   |
| 2560x1440 (QHD)    | 52        | 7.41%   |
| 1366x768 (WXGA)    | 40        | 5.7%    |
| 2256x1504          | 20        | 2.85%   |
| 3440x1440          | 10        | 1.42%   |
| Unknown            | 8         | 1.14%   |
| 3840x2400          | 7         | 1%      |
| 2880x1920          | 7         | 1%      |
| 1600x900 (HD+)     | 7         | 1%      |
| 3200x2000          | 5         | 0.71%   |
| 2240x1400          | 5         | 0.71%   |
| 1280x800 (WXGA)    | 5         | 0.71%   |
| 1440x900 (WXGA+)   | 4         | 0.57%   |
| 3072x1920          | 3         | 0.43%   |
| 2560x1080          | 3         | 0.43%   |
| 1680x1050 (WSXGA+) | 3         | 0.43%   |
| 3840x1600          | 2         | 0.28%   |
| 3840x1080          | 2         | 0.28%   |
| 2944x1840          | 2         | 0.28%   |
| 2880x1620          | 2         | 0.28%   |
| 1920x1280          | 2         | 0.28%   |
| 1280x1024 (SXGA)   | 2         | 0.28%   |
| 1024x600           | 2         | 0.28%   |
| 800x1280           | 1         | 0.14%   |
| 3840x1200          | 1         | 0.14%   |
| 3840x1100          | 1         | 0.14%   |
| 3456x2160          | 1         | 0.14%   |
| 3200x1800 (QHD+)   | 1         | 0.14%   |
| 2520x1680          | 1         | 0.14%   |
| 2304x1440          | 1         | 0.14%   |
| 2160x1440          | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1600x2560          | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 196       | 26.81%  |
| 14      | 153       | 20.93%  |
| 13      | 104       | 14.23%  |
| 16      | 68        | 9.3%    |
| 27      | 47        | 6.43%   |
| 24      | 27        | 3.69%   |
| 31      | 22        | 3.01%   |
| 17      | 18        | 2.46%   |
| 12      | 17        | 2.33%   |
| 21      | 13        | 1.78%   |
| 34      | 12        | 1.64%   |
| 23      | 12        | 1.64%   |
| Unknown | 7         | 0.96%   |
| 86      | 3         | 0.41%   |
| 84      | 3         | 0.41%   |
| 22      | 3         | 0.41%   |
| 48      | 2         | 0.27%   |
| 37      | 2         | 0.27%   |
| 32      | 2         | 0.27%   |
| 26      | 2         | 0.27%   |
| 25      | 2         | 0.27%   |
| 20      | 2         | 0.27%   |
| 18      | 2         | 0.27%   |
| 10      | 2         | 0.27%   |
| 63      | 1         | 0.14%   |
| 60      | 1         | 0.14%   |
| 46      | 1         | 0.14%   |
| 43      | 1         | 0.14%   |
| 40      | 1         | 0.14%   |
| 39      | 1         | 0.14%   |
| 36      | 1         | 0.14%   |
| 35      | 1         | 0.14%   |
| 8       | 1         | 0.14%   |
| 7       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 426       | 58.92%  |
| 201-300     | 105       | 14.52%  |
| 501-600     | 82        | 11.34%  |
| 601-700     | 26        | 3.6%    |
| 351-400     | 24        | 3.32%   |
| 401-500     | 19        | 2.63%   |
| 701-800     | 14        | 1.94%   |
| 1001-1500   | 8         | 1.11%   |
| Unknown     | 7         | 0.97%   |
| 801-900     | 5         | 0.69%   |
| 1501-2000   | 4         | 0.55%   |
| 101-200     | 1         | 0.14%   |
| 901-1000    | 1         | 0.14%   |
| 1-100       | 1         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 377       | 57.91%  |
| 16/10   | 209       | 32.1%   |
| 3/2     | 32        | 4.92%   |
| 21/9    | 16        | 2.46%   |
| Unknown | 6         | 0.92%   |
| 32/9    | 3         | 0.46%   |
| 5/4     | 2         | 0.31%   |
| 0.56    | 2         | 0.31%   |
| 3.40    | 1         | 0.15%   |
| 3.20    | 1         | 0.15%   |
| 0.67    | 1         | 0.15%   |
| 0.63    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 209       | 28.75%  |
| 101-110        | 198       | 27.24%  |
| 111-120        | 65        | 8.94%   |
| 301-350        | 49        | 6.74%   |
| 71-80          | 43        | 5.91%   |
| 201-250        | 38        | 5.23%   |
| 351-500        | 37        | 5.09%   |
| 61-70          | 17        | 2.34%   |
| 121-130        | 16        | 2.2%    |
| 251-300        | 13        | 1.79%   |
| More than 1000 | 8         | 1.1%    |
| 501-1000       | 8         | 1.1%    |
| Unknown        | 7         | 0.96%   |
| 151-200        | 5         | 0.69%   |
| 141-150        | 4         | 0.55%   |
| 91-100         | 4         | 0.55%   |
| 41-50          | 2         | 0.28%   |
| 1-40           | 2         | 0.28%   |
| 51-60          | 1         | 0.14%   |
| 131-140        | 1         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 271       | 38.17%  |
| 161-240       | 192       | 27.04%  |
| 101-120       | 83        | 11.69%  |
| 51-100        | 81        | 11.41%  |
| More than 240 | 70        | 9.86%   |
| Unknown       | 7         | 0.99%   |
| 1-50          | 6         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 445       | 71.89%  |
| 2     | 131       | 21.16%  |
| 0     | 24        | 3.88%   |
| 3     | 19        | 3.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 344       | 38.61%  |
| Realtek Semiconductor                  | 272       | 30.53%  |
| MediaTek                               | 103       | 11.56%  |
| Qualcomm Atheros                       | 34        | 3.82%   |
| Broadcom                               | 31        | 3.48%   |
| Qualcomm                               | 17        | 1.91%   |
| ASIX Electronics                       | 17        | 1.91%   |
| Lenovo                                 | 9         | 1.01%   |
| Shenzhen Goodix Technology             | 7         | 0.79%   |
| Broadcom Limited                       | 7         | 0.79%   |
| Qualcomm Technologies                  | 4         | 0.45%   |
| Framework Computer                     | 4         | 0.45%   |
| Apple                                  | 4         | 0.45%   |
| Xiaomi                                 | 3         | 0.34%   |
| TP-Link                                | 3         | 0.34%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.22%   |
| Realtek                                | 2         | 0.22%   |
| QinHeng Electronics                    | 2         | 0.22%   |
| Marvell Technology Group               | 2         | 0.22%   |
| Ericsson Business Mobile Networks      | 2         | 0.22%   |
| DisplayLink                            | 2         | 0.22%   |
| Winbond Electronics                    | 1         | 0.11%   |
| VIA Technologies                       | 1         | 0.11%   |
| Samsung Electronics                    | 1         | 0.11%   |
| Raspberry Pi                           | 1         | 0.11%   |
| Ralink                                 | 1         | 0.11%   |
| Quectel Wireless Solutions             | 1         | 0.11%   |
| Qualcomm Atheros Communications        | 1         | 0.11%   |
| Motorcomm Microelectronics.            | 1         | 0.11%   |
| Microsoft                              | 1         | 0.11%   |
| ICS Advent                             | 1         | 0.11%   |
| Hewlett-Packard                        | 1         | 0.11%   |
| Google                                 | 1         | 0.11%   |
| Fibocom                                | 1         | 0.11%   |
| Espressif                              | 1         | 0.11%   |
| Edimax Technology                      | 1         | 0.11%   |
| Dell                                   | 1         | 0.11%   |
| D-Link                                 | 1         | 0.11%   |
| Comneon                                | 1         | 0.11%   |
| ASUSTek Computer                       | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 155       | 14.9%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 57        | 5.48%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 47        | 4.52%   |
| Intel Wi-Fi 6 AX200                                                             | 37        | 3.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 33        | 3.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                | 30        | 2.88%   |
| Intel Wireless 8265 / 8275                                                      | 29        | 2.79%   |
| Intel Raptor Lake PCH CNVi WiFi                                                 | 25        | 2.4%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 22        | 2.12%   |
| Intel Wi-Fi 6 AX201                                                             | 18        | 1.73%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 17        | 1.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 16        | 1.54%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                      | 15        | 1.44%   |
| Intel Wireless 7265                                                             | 15        | 1.44%   |
| Intel Meteor Lake PCH CNVi WiFi                                                 | 15        | 1.44%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 14        | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                                  | 13        | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 13        | 1.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                        | 12        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                        | 12        | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                               | 12        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                        | 12        | 1.15%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                     | 12        | 1.15%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]            | 11        | 1.06%   |
| Intel Wireless 8260                                                             | 11        | 1.06%   |
| Intel Ethernet Connection (4) I219-V                                            | 11        | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 10        | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 10        | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                           | 10        | 0.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 9         | 0.87%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 9         | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                    | 9         | 0.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 9         | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                               | 8         | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                                  | 8         | 0.77%   |
| Intel 700 Series Chipset CNVi WiFi                                              | 8         | 0.77%   |
| Realtek USB 10/100/1G/2.5 LAN                                                   | 7         | 0.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 7         | 0.67%   |
| Intel Wireless 7260                                                             | 7         | 0.67%   |
| Intel Wireless 3160                                                             | 7         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 322       | 56.69%  |
| MediaTek                        | 91        | 16.02%  |
| Realtek Semiconductor           | 58        | 10.21%  |
| Qualcomm Atheros                | 31        | 5.46%   |
| Broadcom                        | 29        | 5.11%   |
| Qualcomm                        | 15        | 2.64%   |
| Broadcom Limited                | 7         | 1.23%   |
| Qualcomm Technologies           | 4         | 0.7%    |
| TP-Link                         | 2         | 0.35%   |
| Ralink                          | 1         | 0.18%   |
| Quectel Wireless Solutions      | 1         | 0.18%   |
| Qualcomm Atheros Communications | 1         | 0.18%   |
| Microsoft                       | 1         | 0.18%   |
| Fibocom                         | 1         | 0.18%   |
| Edimax Technology               | 1         | 0.18%   |
| Dell                            | 1         | 0.18%   |
| D-Link                          | 1         | 0.18%   |
| Unknown                         | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 39        | 6.85%   |
| Intel Wi-Fi 6 AX200                                                             | 37        | 6.5%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 33        | 5.8%    |
| Intel Wireless 8265 / 8275                                                      | 29        | 5.1%    |
| Intel Raptor Lake PCH CNVi WiFi                                                 | 24        | 4.22%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 22        | 3.87%   |
| Intel Wi-Fi 6 AX201                                                             | 18        | 3.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                | 18        | 3.16%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 16        | 2.81%   |
| Intel Wireless 7265                                                             | 15        | 2.64%   |
| Intel Meteor Lake PCH CNVi WiFi                                                 | 15        | 2.64%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                      | 14        | 2.46%   |
| Intel Tiger Lake PCH CNVi WiFi                                                  | 13        | 2.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 13        | 2.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                        | 12        | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                        | 12        | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                        | 12        | 2.11%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                     | 12        | 2.11%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]            | 11        | 1.93%   |
| Intel Wireless 8260                                                             | 11        | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 10        | 1.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 10        | 1.76%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 10        | 1.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 9         | 1.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                    | 9         | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                               | 8         | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                                  | 8         | 1.41%   |
| Intel 700 Series Chipset CNVi WiFi                                              | 8         | 1.41%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 7         | 1.23%   |
| Intel Wireless 7260                                                             | 7         | 1.23%   |
| Intel Wireless 3160                                                             | 7         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 6         | 1.05%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                 | 5         | 0.88%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]                | 4         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                  | 4         | 0.7%    |
| Intel Wireless 3165                                                             | 4         | 0.7%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter            | 4         | 0.7%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                    | 4         | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                      | 3         | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                 | 3         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 239       | 55.45%  |
| Intel                                  | 114       | 26.45%  |
| ASIX Electronics                       | 17        | 3.94%   |
| MediaTek                               | 12        | 2.78%   |
| Lenovo                                 | 9         | 2.09%   |
| Qualcomm Atheros                       | 8         | 1.86%   |
| Broadcom                               | 6         | 1.39%   |
| Apple                                  | 4         | 0.93%   |
| Xiaomi                                 | 3         | 0.7%    |
| Suzhou Motorcomm Electronic Technology | 2         | 0.46%   |
| Realtek                                | 2         | 0.46%   |
| Qualcomm                               | 2         | 0.46%   |
| Marvell Technology Group               | 2         | 0.46%   |
| DisplayLink                            | 2         | 0.46%   |
| VIA Technologies                       | 1         | 0.23%   |
| TP-Link                                | 1         | 0.23%   |
| Samsung Electronics                    | 1         | 0.23%   |
| Raspberry Pi                           | 1         | 0.23%   |
| QinHeng Electronics                    | 1         | 0.23%   |
| Motorcomm Microelectronics.            | 1         | 0.23%   |
| ICS Advent                             | 1         | 0.23%   |
| Google                                 | 1         | 0.23%   |
| ASUSTek Computer                       | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 155       | 34.44%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 57        | 12.67%  |
| ASIX AX88179 Gigabit Ethernet                                                   | 17        | 3.78%   |
| Realtek RTL8125 2.5GbE Controller                                               | 12        | 2.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                | 12        | 2.67%   |
| Intel Ethernet Connection (4) I219-V                                            | 11        | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                                           | 10        | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 9         | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 9         | 2%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 8         | 1.78%   |
| Realtek USB 10/100/1G/2.5 LAN                                                   | 7         | 1.56%   |
| Intel Ethernet Connection I219-LM                                               | 6         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                                           | 6         | 1.33%   |
| Intel Ethernet Connection (18) I219-LM                                          | 6         | 1.33%   |
| Realtek Killer E2600 GbE Controller                                             | 5         | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 4         | 0.89%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 4         | 0.89%   |
| Lenovo USB-C Dock Ethernet                                                      | 4         | 0.89%   |
| Intel Ethernet Connection I218-LM                                               | 4         | 0.89%   |
| Intel Ethernet Connection I217-LM                                               | 4         | 0.89%   |
| Intel Ethernet Connection (6) I219-V                                            | 4         | 0.89%   |
| Intel Ethernet Connection (23) I219-V                                           | 4         | 0.89%   |
| Intel Ethernet Connection (10) I219-V                                           | 4         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 3         | 0.67%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                     | 3         | 0.67%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                                | 3         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                           | 3         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                           | 3         | 0.67%   |
| Intel Ethernet Connection (16) I219-V                                           | 3         | 0.67%   |
| Intel Ethernet Connection (16) I219-LM                                          | 3         | 0.67%   |
| Intel Ethernet Connection (13) I219-V                                           | 3         | 0.67%   |
| Intel Ethernet Connection (13) I219-LM                                          | 3         | 0.67%   |
| Intel BE201 320MHz                                                              | 3         | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                               | 3         | 0.67%   |
| Apple iBridge                                                                   | 3         | 0.67%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller                  | 2         | 0.44%   |
| Realtek USB 10/100/1000 LAN                                                     | 2         | 0.44%   |
| Realtek PCIe GbE Family Controller                                              | 2         | 0.44%   |
| Lenovo ThinkPad TBT 3 Dock                                                      | 2         | 0.44%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                                | 2         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 555       | 56.86%  |
| Ethernet | 400       | 40.98%  |
| Modem    | 17        | 1.74%   |
| Unknown  | 4         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 494       | 78.16%  |
| Ethernet | 138       | 21.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 294       | 49.33%  |
| 2     | 288       | 48.32%  |
| 3     | 13        | 2.18%   |
| 0     | 1         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 405       | 65.85%  |
| Yes  | 210       | 34.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 316       | 56.63%  |
| Realtek Semiconductor           | 42        | 7.53%   |
| MediaTek                        | 41        | 7.35%   |
| IMC Networks                    | 38        | 6.81%   |
| Foxconn / Hon Hai               | 37        | 6.63%   |
| Apple                           | 27        | 4.84%   |
| Qualcomm Atheros Communications | 14        | 2.51%   |
| USI                             | 11        | 1.97%   |
| Lite-On Technology              | 11        | 1.97%   |
| Broadcom                        | 7         | 1.25%   |
| Realtek                         | 4         | 0.72%   |
| Opticis                         | 2         | 0.36%   |
| TP-Link                         | 1         | 0.18%   |
| Toshiba                         | 1         | 0.18%   |
| Ralink                          | 1         | 0.18%   |
| Quectel Wireless Solutions      | 1         | 0.18%   |
| Integrated System Solution      | 1         | 0.18%   |
| Chicony Electronics             | 1         | 0.18%   |
| ASUSTek Computer                | 1         | 0.18%   |
| Alps Electric                   | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                       | 78        | 13.98%  |
| Intel Bluetooth wireless interface                           | 67        | 12.01%  |
| Intel AX201 Bluetooth                                        | 50        | 8.96%   |
| MediaTek Wireless_Device                                     | 41        | 7.35%   |
| Realtek Bluetooth Radio                                      | 39        | 6.99%   |
| Intel AX200 Bluetooth                                        | 37        | 6.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 34        | 6.09%   |
| Intel AX210 Bluetooth                                        | 33        | 5.91%   |
| IMC Networks Wireless_Device                                 | 30        | 5.38%   |
| Foxconn / Hon Hai Wireless_Device                            | 22        | 3.94%   |
| Apple Bluetooth Host Controller                              | 20        | 3.58%   |
| USI Bluetooth Device                                         | 11        | 1.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 8         | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                           | 7         | 1.25%   |
| Qualcomm Atheros  Bluetooth Device                           | 6         | 1.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                       | 5         | 0.9%    |
| Lite-On Wireless_Device                                      | 5         | 0.9%    |
| IMC Networks Bluetooth Radio                                 | 5         | 0.9%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                 | 5         | 0.9%    |
| Apple Bluetooth USB Host Controller                          | 5         | 0.9%    |
| Realtek Bluetooth Radio                                      | 4         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                   | 4         | 0.72%   |
| Intel Wireless-AC 3168 Bluetooth                             | 3         | 0.54%   |
| Intel Centrino Bluetooth Wireless Transceiver                | 3         | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                      | 2         | 0.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                        | 2         | 0.36%   |
| Opticis Bluetooth Radio                                      | 2         | 0.36%   |
| Lite-On Bluetooth Device                                     | 2         | 0.36%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter             | 2         | 0.36%   |
| IMC Networks Bluetooth Device                                | 2         | 0.36%   |
| Broadcom HP Portable SoftSailing                             | 2         | 0.36%   |
| Broadcom BCM20702A0                                          | 2         | 0.36%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                   | 2         | 0.36%   |
| TP-Link TP-T@- UB500 Adapter                                 | 1         | 0.18%   |
| Toshiba Bluetooth Device                                     | 1         | 0.18%   |
| Realtek RTL8821A Bluetooth                                   | 1         | 0.18%   |
| Ralink RT3290 Bluetooth                                      | 1         | 0.18%   |
| Quectel Wireless Solutions Quectel Wireless Bluetooth Device | 1         | 0.18%   |
| Qualcomm Atheros AR9462 Bluetooth                            | 1         | 0.18%   |
| Intel Bluetooth                                              | 1         | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 379       | 46.67%  |
| AMD                                  | 224       | 27.59%  |
| Nvidia                               | 111       | 13.67%  |
| Lenovo                               | 14        | 1.72%   |
| C-Media Electronics                  | 12        | 1.48%   |
| Realtek Semiconductor                | 5         | 0.62%   |
| Logitech                             | 5         | 0.62%   |
| Kingston Technology                  | 5         | 0.62%   |
| JMTek                                | 5         | 0.62%   |
| Razer USA                            | 4         | 0.49%   |
| Hewlett-Packard                      | 4         | 0.49%   |
| Focusrite-Novation                   | 3         | 0.37%   |
| Apple                                | 3         | 0.37%   |
| Trust                                | 2         | 0.25%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.25%   |
| Texas Instruments                    | 2         | 0.25%   |
| Synaptics                            | 2         | 0.25%   |
| SteelSeries ApS                      | 2         | 0.25%   |
| Native Instruments                   | 2         | 0.25%   |
| GN Netcom                            | 2         | 0.25%   |
| Generalplus Technology               | 2         | 0.25%   |
| DSEA A/S                             | 2         | 0.25%   |
| VIA Technologies                     | 1         | 0.12%   |
| Van Ooijen Technische Informatica    | 1         | 0.12%   |
| Sony                                 | 1         | 0.12%   |
| Sennheiser                           | 1         | 0.12%   |
| Satechi                              | 1         | 0.12%   |
| Samson Technologies                  | 1         | 0.12%   |
| RODE Microphones                     | 1         | 0.12%   |
| Lautsprecher Teufel                  | 1         | 0.12%   |
| KTMicro                              | 1         | 0.12%   |
| Jieli Technology                     | 1         | 0.12%   |
| Goldvish                             | 1         | 0.12%   |
| FiiO Electronics Technology          | 1         | 0.12%   |
| ESS Technology                       | 1         | 0.12%   |
| EDFIER                               | 1         | 0.12%   |
| Creative Technology                  | 1         | 0.12%   |
| Corsair                              | 1         | 0.12%   |
| BEHRINGER International              | 1         | 0.12%   |
| AudioQuest                           | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 205       | 19.21%  |
| AMD Radeon High Definition Audio Controller                                | 106       | 9.93%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 80        | 7.5%    |
| Intel Sunrise Point-LP HD Audio                                            | 49        | 4.59%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 38        | 3.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 36        | 3.37%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 29        | 2.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 26        | 2.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 23        | 2.16%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 20        | 1.87%   |
| Nvidia GA106 High Definition Audio Controller                              | 18        | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 16        | 1.5%    |
| Intel Broadwell-U Audio Controller                                         | 16        | 1.5%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 15        | 1.41%   |
| Nvidia AD107 High Definition Audio Controller                              | 14        | 1.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 1.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 1.03%   |
| Intel Raptor Lake High Definition Audio Controller                         | 11        | 1.03%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 1.03%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 1.03%   |
| Nvidia GA107 High Definition Audio Controller                              | 10        | 0.94%   |
| Nvidia AD106M High Definition Audio Controller                             | 10        | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 0.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9         | 0.84%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 0.75%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 0.75%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 8         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 0.66%   |
| Intel CM238 HD Audio Controller                                            | 7         | 0.66%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7         | 0.66%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 0.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 0.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.47%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 185       | 26.58%  |
| SK hynix                     | 154       | 22.13%  |
| Micron Technology            | 140       | 20.11%  |
| Kingston                     | 58        | 8.33%   |
| Crucial                      | 45        | 6.47%   |
| Unknown                      | 21        | 3.02%   |
| A-DATA Technology            | 17        | 2.44%   |
| Unknown                      | 14        | 2.01%   |
| Ramaxel Technology           | 14        | 2.01%   |
| Team                         | 9         | 1.29%   |
| Corsair                      | 7         | 1.01%   |
| G.Skill                      | 6         | 0.86%   |
| Unknown (ABCD)               | 3         | 0.43%   |
| Avant                        | 3         | 0.43%   |
| Transcend                    | 2         | 0.29%   |
| Patriot                      | 2         | 0.29%   |
| Lexar                        | 2         | 0.29%   |
| GOODRAM                      | 2         | 0.29%   |
| Timetec                      | 1         | 0.14%   |
| Smart Brazil                 | 1         | 0.14%   |
| Silicon Power                | 1         | 0.14%   |
| PNY                          | 1         | 0.14%   |
| Patriot Memory (PDP Systems) | 1         | 0.14%   |
| Hikvision                    | 1         | 0.14%   |
| GSkill                       | 1         | 0.14%   |
| fef5                         | 1         | 0.14%   |
| Elpida                       | 1         | 0.14%   |
| Apacer                       | 1         | 0.14%   |
| AMD                          | 1         | 0.14%   |
| 8F94000080CE                 | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Unknown                                                       | 21        | 2.91%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 14        | 1.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s        | 14        | 1.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 10        | 1.39%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GiB SODIMM LPDDR5 7500MT/s   | 10        | 1.39%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s         | 8         | 1.11%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s         | 7         | 0.97%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s        | 7         | 0.97%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 7         | 0.97%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 7         | 0.97%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s        | 7         | 0.97%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s     | 7         | 0.97%   |
| Micron RAM MT62F2G32D4DS-026 4GB Row Of Chips LPDDR5 7500MT/s | 7         | 0.97%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 6         | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 6         | 0.83%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 6         | 0.83%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.69%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 5         | 0.69%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s    | 5         | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 5         | 0.69%   |
| Samsung RAM K3KL9L90CM-MGCT 4GB Row Of Chips LPDDR5 7500MT/s  | 5         | 0.69%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s       | 5         | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 5         | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s    | 5         | 0.69%   |
| SK hynix RAM Module 8GB LPDDR5 8000MT/s                       | 4         | 0.55%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s        | 4         | 0.55%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s         | 4         | 0.55%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s       | 4         | 0.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 4         | 0.55%   |
| SK hynix RAM H58G66BK7BX067 8GB Row Of Chips LPDDR5 7500MT/s  | 4         | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 4         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s         | 4         | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 4         | 0.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 4         | 0.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 4         | 0.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s         | 4         | 0.55%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s       | 4         | 0.55%   |
| Samsung RAM K3KL9L90DM-MGCU 8GiB Row Of Chips LPDDR5 8533MT/s | 4         | 0.55%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s       | 4         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 260       | 44.14%  |
| LPDDR5  | 109       | 18.51%  |
| DDR5    | 87        | 14.77%  |
| DDR3    | 78        | 13.24%  |
| LPDDR4  | 31        | 5.26%   |
| LPDDR3  | 15        | 2.55%   |
| SDRAM   | 4         | 0.68%   |
| DDR2    | 2         | 0.34%   |
| Unknown | 2         | 0.34%   |
| DRAM    | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 467       | 76.94%  |
| Row Of Chips | 121       | 19.93%  |
| Unknown      | 10        | 1.65%   |
| Chip         | 5         | 0.82%   |
| DIMM         | 4         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 286       | 44.69%  |
| 16384 | 159       | 24.84%  |
| 4096  | 106       | 16.56%  |
| 32768 | 65        | 10.16%  |
| 2048  | 14        | 2.19%   |
| 49152 | 3         | 0.47%   |
| 1024  | 3         | 0.47%   |
| 65536 | 1         | 0.16%   |
| 12288 | 1         | 0.16%   |
| 6144  | 1         | 0.16%   |
| 3072  | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 160       | 25.56%  |
| 2667    | 88        | 14.06%  |
| 1600    | 67        | 10.7%   |
| 5600    | 56        | 8.95%   |
| 7500    | 42        | 6.71%   |
| 6400    | 41        | 6.55%   |
| 4800    | 31        | 4.95%   |
| 2400    | 30        | 4.79%   |
| 2133    | 25        | 3.99%   |
| 4267    | 14        | 2.24%   |
| 8533    | 11        | 1.76%   |
| 4266    | 9         | 1.44%   |
| 1867    | 8         | 1.28%   |
| 7467    | 6         | 0.96%   |
| 8000    | 4         | 0.64%   |
| 3266    | 4         | 0.64%   |
| 1333    | 4         | 0.64%   |
| 8400    | 3         | 0.48%   |
| 4199    | 3         | 0.48%   |
| Unknown | 3         | 0.48%   |
| 6000    | 2         | 0.32%   |
| 5500    | 2         | 0.32%   |
| 3733    | 2         | 0.32%   |
| 1334    | 2         | 0.32%   |
| 12800   | 1         | 0.16%   |
| 8600    | 1         | 0.16%   |
| 5200    | 1         | 0.16%   |
| 3666    | 1         | 0.16%   |
| 3600    | 1         | 0.16%   |
| 1067    | 1         | 0.16%   |
| 800     | 1         | 0.16%   |
| 667     | 1         | 0.16%   |
| 533     | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Dymo-CoStar | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Dymo-CoStar DYMO LabelPOINT 350 | 1         | 100%    |

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
| Chicony Electronics                    | 119       | 22.54%  |
| IMC Networks                           | 60        | 11.36%  |
| Bison Electronics                      | 46        | 8.71%   |
| Microdia                               | 38        | 7.2%    |
| Luxvisions Innotech Limited            | 37        | 7.01%   |
| Realtek Semiconductor                  | 35        | 6.63%   |
| Quanta                                 | 31        | 5.87%   |
| Shinetech                              | 23        | 4.36%   |
| Sunplus Innovation Technology          | 21        | 3.98%   |
| Logitech                               | 17        | 3.22%   |
| Syntek                                 | 16        | 3.03%   |
| Lite-On Technology                     | 12        | 2.27%   |
| Apple                                  | 10        | 1.89%   |
| Sonix Technology                       | 8         | 1.52%   |
| Framework                              | 6         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 1.14%   |
| SunplusIT                              | 5         | 0.95%   |
| Acer                                   | 4         | 0.76%   |
| Silicon Motion                         | 3         | 0.57%   |
| Samsung Electronics                    | 2         | 0.38%   |
| Primax Electronics                     | 2         | 0.38%   |
| MacroSilicon                           | 2         | 0.38%   |
| kingcome                               | 2         | 0.38%   |
| Hopewin Electronic Material            | 2         | 0.38%   |
| Alcor Micro                            | 2         | 0.38%   |
| Z-Star Microelectronics                | 1         | 0.19%   |
| webcamvendor                           | 1         | 0.19%   |
| webcam                                 | 1         | 0.19%   |
| USB CAMERA                             | 1         | 0.19%   |
| Tripath Technology                     | 1         | 0.19%   |
| Suyin                                  | 1         | 0.19%   |
| ShineOptics                            | 1         | 0.19%   |
| Ricoh                                  | 1         | 0.19%   |
| Razer USA                              | 1         | 0.19%   |
| OmniVision Technologies                | 1         | 0.19%   |
| Microsoft                              | 1         | 0.19%   |
| Lenovo                                 | 1         | 0.19%   |
| icSpring                               | 1         | 0.19%   |
| HYGD-220831-A                          | 1         | 0.19%   |
| globaloptics                           | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 50        | 9.35%   |
| IMC Networks Integrated Camera                       | 30        | 5.61%   |
| Microdia Integrated_Webcam_HD                        | 21        | 3.93%   |
| Bison Integrated Camera                              | 20        | 3.74%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 18        | 3.36%   |
| Luxvisions Innotech Limited Integrated Camera        | 15        | 2.8%    |
| Syntek Integrated Camera                             | 14        | 2.62%   |
| Realtek Laptop Camera                                | 11        | 2.06%   |
| Shinetech USB2.0 FHD UVC WebCam                      | 10        | 1.87%   |
| Lite-On Integrated Camera                            | 10        | 1.87%   |
| Chicony HP HD Camera                                 | 10        | 1.87%   |
| ShineTech USB2.0 HD UVC WebCam                       | 7         | 1.31%   |
| Realtek Integrated_Webcam_HD                         | 7         | 1.31%   |
| Sunplus Integrated_Webcam_HD                         | 6         | 1.12%   |
| Sonix USB2.0 HD UVC WebCam                           | 6         | 1.12%   |
| Shinetech ASUS FHD webcam                            | 6         | 1.12%   |
| Quanta USB2.0 HD UVC WebCam                          | 6         | 1.12%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 6         | 1.12%   |
| Framework Laptop Webcam Module (2nd Gen)             | 6         | 1.12%   |
| Chicony Integrated Camera (1280x720@30)              | 6         | 1.12%   |
| Bison SunplusIT Integrated Camera                    | 6         | 1.12%   |
| Sunplus Integrated_Webcam_FHD                        | 5         | 0.93%   |
| Quanta HD Webcam                                     | 5         | 0.93%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.93%   |
| Logitech HD Pro Webcam C920                          | 5         | 0.93%   |
| Chicony HP Wide Vision HD Camera                     | 5         | 0.93%   |
| Chicony HD User Facing                               | 5         | 0.93%   |
| Bison Integrated RGB Camera                          | 5         | 0.93%   |
| Apple FaceTime HD Camera (Built-in)                  | 5         | 0.93%   |
| Realtek Integrated_Webcam_FHD                        | 4         | 0.75%   |
| Quanta HP HD Camera                                  | 4         | 0.75%   |
| Microdia Integrated Webcam                           | 4         | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 4         | 0.75%   |
| Luxvisions Innotech Limited HP 5MP Camera            | 4         | 0.75%   |
| IMC Networks HD Camera                               | 4         | 0.75%   |
| Chicony ThinkPad T490 Webcam                         | 4         | 0.75%   |
| Chicony Integrated IR Camera                         | 4         | 0.75%   |
| Chicony HP 5MP Camera                                | 4         | 0.75%   |
| Chicony HD Webcam                                    | 4         | 0.75%   |
| Chicony FHD Webcam                                   | 4         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 64        | 50%     |
| Validity Sensors                   | 26        | 20.31%  |
| Shenzhen Goodix Technology         | 20        | 15.63%  |
| Elan Microelectronics              | 7         | 5.47%   |
| HOLTEK                             | 3         | 2.34%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.56%   |
| Focal-systems.Corp                 | 2         | 1.56%   |
| Upek                               | 1         | 0.78%   |
| Samsung Electronics                | 1         | 0.78%   |
| LighTuning Technology              | 1         | 0.78%   |
| AuthenTec                          | 1         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 20.31%  |
| Synaptics UWP WBDI Device                                                  | 10        | 7.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 7.81%   |
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 7.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 7.03%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 6.25%   |
| Synaptics Prometheus Fingerprint Reader                                    | 6         | 4.69%   |
| Elan ELAN:ARM-M4                                                           | 6         | 4.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 3.91%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 3.13%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.13%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.34%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 2.34%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.56%   |
| Validity Sensors VFS491                                                    | 2         | 1.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.56%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 1.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.78%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.78%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 0.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.78%   |
| Synaptics UWP WBDI                                                         | 1         | 0.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.78%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.78%   |
| Samsung Fingerprint Device                                                 | 1         | 0.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.78%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.78%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 42        | 64.62%  |
| Broadcom    | 12        | 18.46%  |
| Yubico.com  | 7         | 10.77%  |
| Upek        | 2         | 3.08%   |
| O2 Micro    | 1         | 1.54%   |
| Bit4id      | 1         | 1.54%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 42        | 64.62%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 6         | 9.23%   |
| Broadcom 5880                                                                | 3         | 4.62%   |
| Broadcom 58200                                                               | 3         | 4.62%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.08%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 3.08%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 2         | 3.08%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                                          | 1         | 1.54%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.54%   |
| Bit4id miniLector EVO                                                        | 1         | 1.54%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 345       | 56.1%   |
| 1     | 185       | 30.08%  |
| 2     | 70        | 11.38%  |
| 3     | 13        | 2.11%   |
| 4     | 2         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 126       | 35.2%   |
| Multimedia controller    | 70        | 19.55%  |
| Chipcard                 | 51        | 14.25%  |
| Graphics card            | 44        | 12.29%  |
| Net/wireless             | 18        | 5.03%   |
| Camera                   | 14        | 3.91%   |
| Communication controller | 8         | 2.23%   |
| Card reader              | 7         | 1.96%   |
| Modem                    | 4         | 1.12%   |
| Bluetooth                | 4         | 1.12%   |
| Sound                    | 3         | 0.84%   |
| Network                  | 3         | 0.84%   |
| Firewire controller      | 2         | 0.56%   |
| Unassigned class         | 1         | 0.28%   |
| Storage/raid             | 1         | 0.28%   |
| Storage                  | 1         | 0.28%   |
| Net/ethernet             | 1         | 0.28%   |


Linux in New Zealand - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in New Zealand.

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

Total: 509

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T530 24294A1       | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| HP            | Pavilion 15                 | [a8bd7a401e](https://linux-hardware.org/?probe=a8bd7a401e) | Apr 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| Lenovo        | N22 80S6                    | [e915245bfd](https://linux-hardware.org/?probe=e915245bfd) | Apr 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [78c8b8578f](https://linux-hardware.org/?probe=78c8b8578f) | Apr 19, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [41e83eedd0](https://linux-hardware.org/?probe=41e83eedd0) | Apr 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ec36fe087a](https://linux-hardware.org/?probe=ec36fe087a) | Apr 17, 2023 |
| Apple         | MacBookPro5,3               | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Toshiba       | Satellite U940              | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | [488dc3a686](https://linux-hardware.org/?probe=488dc3a686) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | [bf1af4af46](https://linux-hardware.org/?probe=bf1af4af46) | Mar 31, 2023 |
| Apple         | MacBookPro11,3              | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| Google        | Swanky                      | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| HP            | ProBook 6550b               | [4629264a10](https://linux-hardware.org/?probe=4629264a10) | Mar 27, 2023 |
| HP            | EliteBook 850 G1            | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| Dell          | Latitude E5570              | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX431FN             | [0185de4fa6](https://linux-hardware.org/?probe=0185de4fa6) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| HP            | Victus by Gaming Laptop ... | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| HP            | Notebook                    | [06e805be3d](https://linux-hardware.org/?probe=06e805be3d) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Valve         | Jupiter                     | [b0b2b55298](https://linux-hardware.org/?probe=b0b2b55298) | Mar 04, 2023 |
| Valve         | Jupiter                     | [da5eea6a75](https://linux-hardware.org/?probe=da5eea6a75) | Mar 03, 2023 |
| Acer          | Aspire F5-573G              | [ce2bc0c00d](https://linux-hardware.org/?probe=ce2bc0c00d) | Feb 27, 2023 |
| HP            | EliteBook 840 14 inch G9... | [8ce6b54b09](https://linux-hardware.org/?probe=8ce6b54b09) | Feb 24, 2023 |
| MSI           | GE63VR 7RF                  | [b9aeb1ce18](https://linux-hardware.org/?probe=b9aeb1ce18) | Feb 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| Dell          | G3 3590                     | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| Dell          | Latitude E6400              | [d9fc10c008](https://linux-hardware.org/?probe=d9fc10c008) | Feb 17, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [d1c4626fd3](https://linux-hardware.org/?probe=d1c4626fd3) | Feb 13, 2023 |
| Dell          | Studio XPS 1640             | [dfb8064df6](https://linux-hardware.org/?probe=dfb8064df6) | Feb 12, 2023 |
| Dell          | Studio XPS 1640             | [deff8d7055](https://linux-hardware.org/?probe=deff8d7055) | Feb 11, 2023 |
| ASUSTek       | UX430UNR                    | [f0b972d056](https://linux-hardware.org/?probe=f0b972d056) | Feb 10, 2023 |
| Dell          | System XPS L702X            | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| HP            | EliteBook 8570p             | [93c3d6c151](https://linux-hardware.org/?probe=93c3d6c151) | Feb 06, 2023 |
| HP            | EliteBook 8540p             | [1614d002e0](https://linux-hardware.org/?probe=1614d002e0) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Lenovo        | ThinkPad T480 20L5001KAU    | [4b7046e26c](https://linux-hardware.org/?probe=4b7046e26c) | Jan 30, 2023 |
| Acer          | E1-510                      | [659bb96537](https://linux-hardware.org/?probe=659bb96537) | Jan 29, 2023 |
| Gigabyte      | A5 K1                       | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [567ae7f5ba](https://linux-hardware.org/?probe=567ae7f5ba) | Jan 21, 2023 |
| Toshiba       | PORTEGE M780                | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| HP            | ProBook 4740s               | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| HP            | EliteBook 850 G5            | [4afba6f67d](https://linux-hardware.org/?probe=4afba6f67d) | Jan 18, 2023 |
| Sony          | VGN-SR16GN_B                | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| HP            | EliteBook 840 G5            | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| HP            | EliteBook 840 G5            | [bcb3fca0a2](https://linux-hardware.org/?probe=bcb3fca0a2) | Jan 10, 2023 |
| HP            | ZBook Firefly 14 G7 Mobi... | [20bfe72df5](https://linux-hardware.org/?probe=20bfe72df5) | Jan 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444G... | [29331861b5](https://linux-hardware.org/?probe=29331861b5) | Jan 09, 2023 |
| Lenovo        | N22 80S6                    | [a5638d3bf2](https://linux-hardware.org/?probe=a5638d3bf2) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | [ad72a0fad1](https://linux-hardware.org/?probe=ad72a0fad1) | Jan 08, 2023 |
| Sony          | VGN-Z16GN_B                 | [63bb6c7c43](https://linux-hardware.org/?probe=63bb6c7c43) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [45c8b096c5](https://linux-hardware.org/?probe=45c8b096c5) | Jan 08, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| HP            | ProBook 470 G5              | [aa8715fc5c](https://linux-hardware.org/?probe=aa8715fc5c) | Jan 03, 2023 |
| HP            | ENVY TS 15                  | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| Dell          | Precision 7740              | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Unknown       | Unknown                     | [56781f9824](https://linux-hardware.org/?probe=56781f9824) | Dec 19, 2022 |
| HP            | EliteBook 8460p             | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Google        | Laser14                     | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Dell          | Inspiron N5110              | [b333e1030f](https://linux-hardware.org/?probe=b333e1030f) | Dec 16, 2022 |
| HP            | Pavilion dv6                | [d6d4bd4dcd](https://linux-hardware.org/?probe=d6d4bd4dcd) | Dec 14, 2022 |
| HP            | Pavilion dv6                | [2472ce95cb](https://linux-hardware.org/?probe=2472ce95cb) | Dec 14, 2022 |
| Lenovo        | B50-30 20382                | [e2ecbddf15](https://linux-hardware.org/?probe=e2ecbddf15) | Dec 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| HP            | Laptop 17-bs0xx             | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| Dell          | Inspiron 5459               | [d9cc4844ac](https://linux-hardware.org/?probe=d9cc4844ac) | Dec 12, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| Acer          | E1-510                      | [8aadf699f9](https://linux-hardware.org/?probe=8aadf699f9) | Nov 30, 2022 |
| Dell          | G7 7700                     | [16407c6485](https://linux-hardware.org/?probe=16407c6485) | Nov 27, 2022 |
| MSI           | Stealth GS77 12UHS          | [462cb0ce56](https://linux-hardware.org/?probe=462cb0ce56) | Nov 21, 2022 |
| Google        | Swanky                      | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| HP            | ProBook 430 G3              | [e69d9794fd](https://linux-hardware.org/?probe=e69d9794fd) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | [d8bae2c402](https://linux-hardware.org/?probe=d8bae2c402) | Nov 08, 2022 |
| Toshiba       | Satellite C660              | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Unknown       | Unknown                     | [6702cb2ca7](https://linux-hardware.org/?probe=6702cb2ca7) | Oct 25, 2022 |
| Google        | Swanky                      | [375d986028](https://linux-hardware.org/?probe=375d986028) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Google        | Swanky                      | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [d5b2d74cd8](https://linux-hardware.org/?probe=d5b2d74cd8) | Oct 21, 2022 |
| Dell          | Latitude E7440              | [5c81fc2db0](https://linux-hardware.org/?probe=5c81fc2db0) | Oct 19, 2022 |
| Toshiba       | Satellite C660              | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Toshiba       | Satellite L750              | [9998a32d98](https://linux-hardware.org/?probe=9998a32d98) | Oct 09, 2022 |
| Dell          | Inspiron 3521               | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Dell          | Precision 3570              | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Apple         | MacBookPro14,3              | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| HP            | Pavilion g7                 | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| Toshiba       | Satellite C660              | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Google        | Snappy                      | [e428dec368](https://linux-hardware.org/?probe=e428dec368) | Sep 14, 2022 |
| HP            | Laptop 17-bs0xx             | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| HP            | Pavilion dv6                | [5877abaab3](https://linux-hardware.org/?probe=5877abaab3) | Sep 07, 2022 |
| Acer          | Aspire F5-573G              | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| The Wareho... | E2037                       | [e9599d1061](https://linux-hardware.org/?probe=e9599d1061) | Aug 31, 2022 |
| Lenovo        | V145-15AST 81MT             | [40b9d37c2a](https://linux-hardware.org/?probe=40b9d37c2a) | Aug 29, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [0a08f13779](https://linux-hardware.org/?probe=0a08f13779) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | Latitude 5420               | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| HP            | ProBook 450 G6              | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| ASUSTek       | P81IJ                       | [7ab324abea](https://linux-hardware.org/?probe=7ab324abea) | Aug 25, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Acer          | Aspire M5-581TG             | [03ec19b37d](https://linux-hardware.org/?probe=03ec19b37d) | Aug 23, 2022 |
| Google        | Galtic                      | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | Latitude E6500              | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| Dell          | Vostro 7500                 | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| HP            | ProBook 6570b               | [335eb52112](https://linux-hardware.org/?probe=335eb52112) | Aug 12, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| Dell          | Latitude E6420              | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| Dell          | Latitude E6430s             | [542db6380a](https://linux-hardware.org/?probe=542db6380a) | Aug 04, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| HP            | 2000                        | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| HP            | Notebook                    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| Lenovo        | 14w 81MQ0013AU              | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| Lenovo        | G40-30 80FY                 | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| ASUSTek       | GL703VD                     | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [36fdd87ff3](https://linux-hardware.org/?probe=36fdd87ff3) | Jun 21, 2022 |
| HP            | ProBook 450 G1              | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
| HP            | 550                         | [1db816d0b2](https://linux-hardware.org/?probe=1db816d0b2) | Jun 19, 2022 |
| Dell          | Precision 3571              | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| HP            | EliteBook 830 G5            | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Toshiba       | Satellite Pro C665          | [23fd853a45](https://linux-hardware.org/?probe=23fd853a45) | May 24, 2022 |
| Acer          | TravelMate 7750G            | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| Toshiba       | Satellite L50D-C            | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [60d56e6b15](https://linux-hardware.org/?probe=60d56e6b15) | May 13, 2022 |
| Alienware     | x17 R2                      | [0a81fc619e](https://linux-hardware.org/?probe=0a81fc619e) | May 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bd6e42ac60](https://linux-hardware.org/?probe=bd6e42ac60) | May 07, 2022 |
| Toshiba       | Satellite C660              | [2b4d9cbd0c](https://linux-hardware.org/?probe=2b4d9cbd0c) | May 03, 2022 |
| Lenovo        | B50-30 20382                | [1eb95bb123](https://linux-hardware.org/?probe=1eb95bb123) | May 01, 2022 |
| Toshiba       | Satellite C660              | [c3bb583347](https://linux-hardware.org/?probe=c3bb583347) | Apr 24, 2022 |
| Lenovo        | B50-70 20384                | [35cf0f09e4](https://linux-hardware.org/?probe=35cf0f09e4) | Apr 22, 2022 |
| Dell          | XPS 13 9360                 | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell          | XPS 15 9510                 | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | [5ad4aa0994](https://linux-hardware.org/?probe=5ad4aa0994) | Apr 13, 2022 |
| HP            | ProBook 650 G1              | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| Dell          | Latitude 7480               | [ccc8107d39](https://linux-hardware.org/?probe=ccc8107d39) | Apr 01, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| eMachines     | eM350                       | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [9b194b03b4](https://linux-hardware.org/?probe=9b194b03b4) | Mar 25, 2022 |
| HP            | Laptop 15-bs0xx             | [e12f0f1eed](https://linux-hardware.org/?probe=e12f0f1eed) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [24d5a323cc](https://linux-hardware.org/?probe=24d5a323cc) | Mar 23, 2022 |
| ASUSTek       | G75VX                       | [4673f4edd8](https://linux-hardware.org/?probe=4673f4edd8) | Mar 21, 2022 |
| HP            | EliteBook 8460p             | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [33980f3303](https://linux-hardware.org/?probe=33980f3303) | Mar 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [5b83093837](https://linux-hardware.org/?probe=5b83093837) | Mar 15, 2022 |
| Dell          | Inspiron 5770               | [fc12718113](https://linux-hardware.org/?probe=fc12718113) | Mar 13, 2022 |
| Dell          | Inspiron 5770               | [8a7c1daf70](https://linux-hardware.org/?probe=8a7c1daf70) | Mar 13, 2022 |
| Dell          | XPS 15 9550                 | [c39fe1a3e3](https://linux-hardware.org/?probe=c39fe1a3e3) | Mar 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Acer          | Aspire E1-571G              | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [96aa797713](https://linux-hardware.org/?probe=96aa797713) | Feb 21, 2022 |
| Toshiba       | Satellite Pro R50-C         | [d185900f87](https://linux-hardware.org/?probe=d185900f87) | Feb 16, 2022 |
| Dell          | Inspiron 5415               | [3324e66890](https://linux-hardware.org/?probe=3324e66890) | Feb 15, 2022 |
| Dell          | Inspiron 5415               | [c2bd021f7e](https://linux-hardware.org/?probe=c2bd021f7e) | Feb 13, 2022 |
| ASUSTek       | K55A                        | [e88dba3a7e](https://linux-hardware.org/?probe=e88dba3a7e) | Feb 12, 2022 |
| System76      | Lemur Pro                   | [a0e5f04131](https://linux-hardware.org/?probe=a0e5f04131) | Feb 12, 2022 |
| Acer          | Aspire ES1-411              | [e534d71dc2](https://linux-hardware.org/?probe=e534d71dc2) | Feb 12, 2022 |
| Lenovo        | ThinkPad T470 20HES23B0U    | [c080812ddb](https://linux-hardware.org/?probe=c080812ddb) | Feb 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Acer          | Aspire A715-42G             | [f9c872ec0c](https://linux-hardware.org/?probe=f9c872ec0c) | Jan 30, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| Toshiba       | PORTEGE R930                | [1ee5471d24](https://linux-hardware.org/?probe=1ee5471d24) | Jan 20, 2022 |
| HP            | ProBook 450 G2              | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Star Labs     | LabTop                      | [c7cc8bae59](https://linux-hardware.org/?probe=c7cc8bae59) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [2e7edfda25](https://linux-hardware.org/?probe=2e7edfda25) | Jan 04, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Acer          | Swift SF314-41              | [d7b4fd099d](https://linux-hardware.org/?probe=d7b4fd099d) | Jan 01, 2022 |
| ASUSTek       | UX303LAB                    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| Google        | Kip                         | [8c60d949d0](https://linux-hardware.org/?probe=8c60d949d0) | Dec 20, 2021 |
| Acer          | Aspire 4830T                | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Dell          | System XPS L702X            | [805619ba8c](https://linux-hardware.org/?probe=805619ba8c) | Nov 25, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| HP            | Laptop 15-bs0xx             | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| Acer          | Aspire 4830T                | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9fc484d01e](https://linux-hardware.org/?probe=9fc484d01e) | Nov 11, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [edc363bc59](https://linux-hardware.org/?probe=edc363bc59) | Nov 11, 2021 |
| Timi          | A30                         | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek       | K52Jc                       | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| Dell          | Vostro 14 5410              | [b6966ebc42](https://linux-hardware.org/?probe=b6966ebc42) | Oct 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [94e0e3f047](https://linux-hardware.org/?probe=94e0e3f047) | Oct 27, 2021 |
| HP            | Spectre x2 Detachable       | [d20c059f3d](https://linux-hardware.org/?probe=d20c059f3d) | Oct 24, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [01ca7ca744](https://linux-hardware.org/?probe=01ca7ca744) | Oct 23, 2021 |
| Dell          | Latitude 7490               | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| HP            | Pavilion tx2500             | [1410381a3d](https://linux-hardware.org/?probe=1410381a3d) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | [e420777c94](https://linux-hardware.org/?probe=e420777c94) | Oct 16, 2021 |
| Dell          | Latitude 7285               | [5097e0f8c8](https://linux-hardware.org/?probe=5097e0f8c8) | Oct 14, 2021 |
| Acer          | Aspire VN7-593G             | [d9f2adbdfc](https://linux-hardware.org/?probe=d9f2adbdfc) | Oct 11, 2021 |
| HP            | Pavilion g6                 | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| HP            | EliteBook 2170p             | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| MSI           | GE66 Raider 10SF            | [9d11ef435a](https://linux-hardware.org/?probe=9d11ef435a) | Sep 16, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [8f19930d07](https://linux-hardware.org/?probe=8f19930d07) | Sep 15, 2021 |
| Acer          | TravelMate 5760             | [eb8b4b37a4](https://linux-hardware.org/?probe=eb8b4b37a4) | Sep 13, 2021 |
| Acer          | TravelMate 5760             | [a0376eeefc](https://linux-hardware.org/?probe=a0376eeefc) | Sep 13, 2021 |
| Dell          | XPS 15 9500                 | [83bf40cb1d](https://linux-hardware.org/?probe=83bf40cb1d) | Sep 12, 2021 |
| Dell          | XPS 15 9500                 | [65102530f5](https://linux-hardware.org/?probe=65102530f5) | Sep 12, 2021 |
| HP            | EliteBook 8560p             | [48828ad0d3](https://linux-hardware.org/?probe=48828ad0d3) | Sep 10, 2021 |
| Dell          | System XPS L702X            | [e0ff0245fb](https://linux-hardware.org/?probe=e0ff0245fb) | Sep 10, 2021 |
| Toshiba       | Satellite C50D-C            | [af1933f8ad](https://linux-hardware.org/?probe=af1933f8ad) | Sep 09, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [35c6eb0703](https://linux-hardware.org/?probe=35c6eb0703) | Aug 31, 2021 |
| Lenovo        | B50-30 20382                | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| Medion        | P6815                       | [e3e586bafe](https://linux-hardware.org/?probe=e3e586bafe) | Aug 29, 2021 |
| Medion        | P6815                       | [46b6aaf8c5](https://linux-hardware.org/?probe=46b6aaf8c5) | Aug 29, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| HP            | Pavilion dv6                | [c1ad958c3f](https://linux-hardware.org/?probe=c1ad958c3f) | Aug 28, 2021 |
| Lenovo        | B50-30 20382                | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| Sony          | VPCEB43FG                   | [4a81e892f0](https://linux-hardware.org/?probe=4a81e892f0) | Aug 26, 2021 |
| Dell          | Latitude 7490               | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [efeb81eaea](https://linux-hardware.org/?probe=efeb81eaea) | Aug 21, 2021 |
| Dell          | XPS 15 9500                 | [1216df6214](https://linux-hardware.org/?probe=1216df6214) | Aug 19, 2021 |
| TWG           | E2017                       | [3f335e736c](https://linux-hardware.org/?probe=3f335e736c) | Aug 18, 2021 |
| Dell          | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| Toshiba       | Satellite C50D-C            | [dda3acac30](https://linux-hardware.org/?probe=dda3acac30) | Aug 08, 2021 |
| Samsung       | RC410/RC510/RC710           | [4e03a59c3f](https://linux-hardware.org/?probe=4e03a59c3f) | Aug 03, 2021 |
| Samsung       | RC410/RC510/RC710           | [37550654db](https://linux-hardware.org/?probe=37550654db) | Aug 03, 2021 |
| Lenovo        | V15-IIL 82C5                | [20007580cb](https://linux-hardware.org/?probe=20007580cb) | Aug 01, 2021 |
| Lenovo        | V15-IIL 82C5                | [359e3c40ca](https://linux-hardware.org/?probe=359e3c40ca) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [812ba32a31](https://linux-hardware.org/?probe=812ba32a31) | Aug 01, 2021 |
| HP            | Pavilion g6                 | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [cc238ca2aa](https://linux-hardware.org/?probe=cc238ca2aa) | Jul 30, 2021 |
| HP            | Spectre x2 Detachable       | [7b96d53aa9](https://linux-hardware.org/?probe=7b96d53aa9) | Jul 29, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [2a54318c46](https://linux-hardware.org/?probe=2a54318c46) | Jul 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [c499631e7e](https://linux-hardware.org/?probe=c499631e7e) | Jul 19, 2021 |
| HP            | Laptop 14s-dk0xxx           | [0acaedd30c](https://linux-hardware.org/?probe=0acaedd30c) | Jul 13, 2021 |
| HP            | Laptop 14s-dk0xxx           | [f655e1ca50](https://linux-hardware.org/?probe=f655e1ca50) | Jul 12, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [331968a8d9](https://linux-hardware.org/?probe=331968a8d9) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [59e9a66bff](https://linux-hardware.org/?probe=59e9a66bff) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [e20b747527](https://linux-hardware.org/?probe=e20b747527) | Jul 03, 2021 |
| Sony          | SVE14A15FGS                 | [adb8d0cc94](https://linux-hardware.org/?probe=adb8d0cc94) | Jun 14, 2021 |
| Acer          | Aspire A715-71G             | [cb59081351](https://linux-hardware.org/?probe=cb59081351) | Jun 14, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [e82b7b36f2](https://linux-hardware.org/?probe=e82b7b36f2) | Jun 12, 2021 |
| ASUSTek       | K52Jc                       | [4b93dc4ee8](https://linux-hardware.org/?probe=4b93dc4ee8) | Jun 07, 2021 |
| HP            | ProBook 650 G1              | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| HP            | EliteBook 8560p             | [ea1bd5e314](https://linux-hardware.org/?probe=ea1bd5e314) | May 30, 2021 |
| Sony          | SVE11126CGB                 | [b7ee22588d](https://linux-hardware.org/?probe=b7ee22588d) | May 29, 2021 |
| Toshiba       | Satellite S70t-B            | [33d64c7a69](https://linux-hardware.org/?probe=33d64c7a69) | May 26, 2021 |
| Toshiba       | Satellite S70t-B            | [60c1bab5d9](https://linux-hardware.org/?probe=60c1bab5d9) | May 26, 2021 |
| HP            | Pavilion Notebook           | [37695077ba](https://linux-hardware.org/?probe=37695077ba) | May 21, 2021 |
| HP            | ENVY 15                     | [2a23609955](https://linux-hardware.org/?probe=2a23609955) | May 15, 2021 |
| Acer          | E5-571-551U                 | [152105400d](https://linux-hardware.org/?probe=152105400d) | May 05, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Lenovo        | V110-15IAP 80TG             | [76ac42ca9c](https://linux-hardware.org/?probe=76ac42ca9c) | Apr 30, 2021 |
| MSI           | GS63VR 7RF                  | [4a7125aec0](https://linux-hardware.org/?probe=4a7125aec0) | Apr 18, 2021 |
| MSI           | GS63VR 7RF                  | [76126cd5fd](https://linux-hardware.org/?probe=76126cd5fd) | Apr 18, 2021 |
| Toshiba       | PORTEGE M930                | [aac37423e5](https://linux-hardware.org/?probe=aac37423e5) | Apr 13, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d65bc55ad0](https://linux-hardware.org/?probe=d65bc55ad0) | Apr 11, 2021 |
| Apple         | MacBook7,1                  | [9b4e89202e](https://linux-hardware.org/?probe=9b4e89202e) | Apr 09, 2021 |
| HP            | ProBook 650 G1              | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP            | EliteBook 2560p             | [ecdecf72ec](https://linux-hardware.org/?probe=ecdecf72ec) | Mar 30, 2021 |
| HP            | ProBook 650 G1              | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| HP            | ZBook Firefly 15 G7 Mobi... | [0653cc5343](https://linux-hardware.org/?probe=0653cc5343) | Mar 29, 2021 |
| Metabox       | X170SM                      | [eb5af1bbd3](https://linux-hardware.org/?probe=eb5af1bbd3) | Mar 26, 2021 |
| Metabox       | X170SM                      | [544b6cd3d5](https://linux-hardware.org/?probe=544b6cd3d5) | Mar 26, 2021 |
| HP            | ProBook 4540s               | [4fe9e650c2](https://linux-hardware.org/?probe=4fe9e650c2) | Mar 13, 2021 |
| HP            | ProBook 4540s               | [d2c0c69a0d](https://linux-hardware.org/?probe=d2c0c69a0d) | Mar 13, 2021 |
| Acer          | Aspire 5750                 | [6aaf201a58](https://linux-hardware.org/?probe=6aaf201a58) | Mar 10, 2021 |
| Toshiba       | Satellite U920t             | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | [b1088bed99](https://linux-hardware.org/?probe=b1088bed99) | Feb 26, 2021 |
| Dell          | XPS 13 9360                 | [7de34c9abe](https://linux-hardware.org/?probe=7de34c9abe) | Feb 26, 2021 |
| HP            | ZBook 14                    | [042b4b4a48](https://linux-hardware.org/?probe=042b4b4a48) | Feb 26, 2021 |
| Dell          | Latitude E6430s             | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| Dell          | Latitude 7285               | [844392cd2c](https://linux-hardware.org/?probe=844392cd2c) | Feb 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [d20e5c1f85](https://linux-hardware.org/?probe=d20e5c1f85) | Feb 15, 2021 |
| HP            | EliteBook 820 G3            | [e1a72b607e](https://linux-hardware.org/?probe=e1a72b607e) | Feb 14, 2021 |
| Dell          | Latitude E4300              | [a09ca20174](https://linux-hardware.org/?probe=a09ca20174) | Feb 14, 2021 |
| HP            | Notebook                    | [e5bc3a0317](https://linux-hardware.org/?probe=e5bc3a0317) | Feb 12, 2021 |
| MSI           | GE66 Raider 10SF            | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| HP            | 355 G2                      | [ac856a41b8](https://linux-hardware.org/?probe=ac856a41b8) | Feb 03, 2021 |
| Acer          | ES1-512-P8NA                | [c393cb6ad4](https://linux-hardware.org/?probe=c393cb6ad4) | Jan 24, 2021 |
| HP            | ProBook 450 G3              | [c5e2124079](https://linux-hardware.org/?probe=c5e2124079) | Jan 21, 2021 |
| Toshiba       | Satellite U920t             | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [ecc872dc4a](https://linux-hardware.org/?probe=ecc872dc4a) | Jan 16, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [3c308a7199](https://linux-hardware.org/?probe=3c308a7199) | Jan 15, 2021 |
| Acer          | ConceptD CN315-71P          | [7d1c394d7a](https://linux-hardware.org/?probe=7d1c394d7a) | Dec 26, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| Lenovo        | ThinkPad P52 20M9000KUS     | [ed51fc90e5](https://linux-hardware.org/?probe=ed51fc90e5) | Dec 19, 2020 |
| HP            | ZBook Studio G5             | [af0417cef5](https://linux-hardware.org/?probe=af0417cef5) | Dec 10, 2020 |
| Dell          | Precision 7530              | [c82b4c0f51](https://linux-hardware.org/?probe=c82b4c0f51) | Dec 03, 2020 |
| HP            | Pavilion dv6                | [2c1cf2da53](https://linux-hardware.org/?probe=2c1cf2da53) | Nov 30, 2020 |
| eMachines     | eM350                       | [0ba740f085](https://linux-hardware.org/?probe=0ba740f085) | Nov 28, 2020 |
| Dell          | XPS 15 9560                 | [463c0c961e](https://linux-hardware.org/?probe=463c0c961e) | Nov 15, 2020 |
| Dell          | Latitude D630               | [4b5f3f19ae](https://linux-hardware.org/?probe=4b5f3f19ae) | Nov 14, 2020 |
| Toshiba       | Satellite Pro L830          | [97a68dd7c5](https://linux-hardware.org/?probe=97a68dd7c5) | Nov 14, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [3ffb0e062e](https://linux-hardware.org/?probe=3ffb0e062e) | Nov 13, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [7e7b6fe785](https://linux-hardware.org/?probe=7e7b6fe785) | Nov 13, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [0001b76ceb](https://linux-hardware.org/?probe=0001b76ceb) | Nov 10, 2020 |
| Acer          | Aspire ES1-511              | [13485ce10c](https://linux-hardware.org/?probe=13485ce10c) | Nov 08, 2020 |
| Acer          | Aspire ES1-511              | [903c4d5729](https://linux-hardware.org/?probe=903c4d5729) | Nov 08, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [c4d3f6f37d](https://linux-hardware.org/?probe=c4d3f6f37d) | Nov 07, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [841d75822e](https://linux-hardware.org/?probe=841d75822e) | Nov 04, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | [41c93bb503](https://linux-hardware.org/?probe=41c93bb503) | Oct 29, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | [7678291690](https://linux-hardware.org/?probe=7678291690) | Oct 28, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [bacac44e9d](https://linux-hardware.org/?probe=bacac44e9d) | Oct 26, 2020 |
| HP            | ProBook 6550b               | [d93b3bfeac](https://linux-hardware.org/?probe=d93b3bfeac) | Oct 22, 2020 |
| Toshiba       | Satellite C660              | [d8ac831c61](https://linux-hardware.org/?probe=d8ac831c61) | Oct 20, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [8720432e33](https://linux-hardware.org/?probe=8720432e33) | Oct 16, 2020 |
| ASUSTek       | X550EP                      | [f13a8d8d9b](https://linux-hardware.org/?probe=f13a8d8d9b) | Oct 15, 2020 |
| Dell          | XPS 13 9360                 | [8cf28e044c](https://linux-hardware.org/?probe=8cf28e044c) | Oct 11, 2020 |
| HP            | Compaq Presario A900        | [352f29d57c](https://linux-hardware.org/?probe=352f29d57c) | Oct 08, 2020 |
| HP            | Laptop 15s-fq1xxx           | [b3ae2a4d2c](https://linux-hardware.org/?probe=b3ae2a4d2c) | Oct 06, 2020 |
| ASUSTek       | 1015PX                      | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | Swift SF314-41              | [26350d0806](https://linux-hardware.org/?probe=26350d0806) | Oct 04, 2020 |
| HP            | Compaq CQ45                 | [ea61076771](https://linux-hardware.org/?probe=ea61076771) | Sep 30, 2020 |
| MSI           | GP75 Leopard 9SD            | [9c152a1117](https://linux-hardware.org/?probe=9c152a1117) | Sep 30, 2020 |
| HP            | Compaq CQ45                 | [f62190e31d](https://linux-hardware.org/?probe=f62190e31d) | Sep 29, 2020 |
| HP            | EliteBook 850 G5            | [86422636a2](https://linux-hardware.org/?probe=86422636a2) | Sep 25, 2020 |
| Apple         | MacBook5,1                  | [fb2f9dd279](https://linux-hardware.org/?probe=fb2f9dd279) | Sep 24, 2020 |
| HP            | EliteBook Folio 1040 G1     | [0848bad0d4](https://linux-hardware.org/?probe=0848bad0d4) | Sep 23, 2020 |
| Apple         | MacBook5,1                  | [ad39052e7a](https://linux-hardware.org/?probe=ad39052e7a) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [616e26ca49](https://linux-hardware.org/?probe=616e26ca49) | Sep 20, 2020 |
| HP            | ProBook 450 G5              | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| HP            | ProBook 6560b               | [109cd57459](https://linux-hardware.org/?probe=109cd57459) | Sep 12, 2020 |
| Dell          | Latitude E6430s             | [bd8ab4dd1c](https://linux-hardware.org/?probe=bd8ab4dd1c) | Sep 08, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [b673064c0f](https://linux-hardware.org/?probe=b673064c0f) | Sep 08, 2020 |
| Acer          | Aspire 5750                 | [b65a1db938](https://linux-hardware.org/?probe=b65a1db938) | Sep 07, 2020 |
| Toshiba       | Satellite C50-B             | [167e9daeb7](https://linux-hardware.org/?probe=167e9daeb7) | Sep 05, 2020 |
| HP            | Pavilion dv6                | [4c2298d7bb](https://linux-hardware.org/?probe=4c2298d7bb) | Sep 05, 2020 |
| Dell          | Latitude E7440              | [0db3907088](https://linux-hardware.org/?probe=0db3907088) | Sep 05, 2020 |
| HP            | Laptop 15-db0xxx            | [3949b5f183](https://linux-hardware.org/?probe=3949b5f183) | Sep 04, 2020 |
| Dell          | Inspiron 5567               | [ab299d27a4](https://linux-hardware.org/?probe=ab299d27a4) | Sep 04, 2020 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [9c1bd6b943](https://linux-hardware.org/?probe=9c1bd6b943) | Sep 03, 2020 |
| MSI           | GT80S 6QD                   | [e14f86e038](https://linux-hardware.org/?probe=e14f86e038) | Sep 03, 2020 |
| Acer          | Aspire 5750                 | [6c84136b17](https://linux-hardware.org/?probe=6c84136b17) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [c9cf3aef22](https://linux-hardware.org/?probe=c9cf3aef22) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [65612b9b8f](https://linux-hardware.org/?probe=65612b9b8f) | Sep 03, 2020 |
| Toshiba       | Satellite C660              | [e7791768a3](https://linux-hardware.org/?probe=e7791768a3) | Sep 02, 2020 |
| Toshiba       | Satellite C50-B             | [186e22ea8c](https://linux-hardware.org/?probe=186e22ea8c) | Sep 01, 2020 |
| Dell          | XPS 15 9570                 | [cb17688de8](https://linux-hardware.org/?probe=cb17688de8) | Sep 01, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [4d92725c5a](https://linux-hardware.org/?probe=4d92725c5a) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [1707834024](https://linux-hardware.org/?probe=1707834024) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [db76b91e62](https://linux-hardware.org/?probe=db76b91e62) | Aug 21, 2020 |
| HP            | Pavilion dv6                | [65033f4392](https://linux-hardware.org/?probe=65033f4392) | Aug 19, 2020 |
| MSI           | GE66 Raider 10SF            | [3bcf471b04](https://linux-hardware.org/?probe=3bcf471b04) | Aug 15, 2020 |
| Dell          | Latitude E6430              | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| System76      | Lemur Pro                   | [c2619f1014](https://linux-hardware.org/?probe=c2619f1014) | Aug 14, 2020 |
| MSI           | GT72 2PC                    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [fb69c1f324](https://linux-hardware.org/?probe=fb69c1f324) | Aug 10, 2020 |
| Apple         | MacBookPro5,5               | [37d32b3bac](https://linux-hardware.org/?probe=37d32b3bac) | Aug 03, 2020 |
| Apple         | MacBookPro5,5               | [6aee03b649](https://linux-hardware.org/?probe=6aee03b649) | Jul 31, 2020 |
| HP            | Pavilion dv4                | [ec2bd27559](https://linux-hardware.org/?probe=ec2bd27559) | Jul 25, 2020 |
| MSI           | GE66 Raider 10SF            | [3dcde22239](https://linux-hardware.org/?probe=3dcde22239) | Jul 25, 2020 |
| HP            | Laptop 15-dy0xxx            | [cad2dbb88f](https://linux-hardware.org/?probe=cad2dbb88f) | Jul 25, 2020 |
| HP            | ProBook 450 G5              | [a8dfd5a806](https://linux-hardware.org/?probe=a8dfd5a806) | Jul 21, 2020 |
| HP            | Laptop 15-dy0xxx            | [e471bc69b2](https://linux-hardware.org/?probe=e471bc69b2) | Jul 21, 2020 |
| Dell          | Latitude E5570              | [6408e82f4f](https://linux-hardware.org/?probe=6408e82f4f) | Jul 20, 2020 |
| HP            | EliteBook 840 G1            | [75a2e58b47](https://linux-hardware.org/?probe=75a2e58b47) | Jun 30, 2020 |
| HP            | EliteBook 8560p             | [e83d7e33f2](https://linux-hardware.org/?probe=e83d7e33f2) | Jun 29, 2020 |
| HP            | EliteBook 840 G6            | [9fccdcc42f](https://linux-hardware.org/?probe=9fccdcc42f) | Jun 25, 2020 |
| HP            | ProBook 650 G1              | [d8e10f56ec](https://linux-hardware.org/?probe=d8e10f56ec) | Jun 24, 2020 |
| MSI           | GE66 Raider 10SF            | [ca5d80f8f9](https://linux-hardware.org/?probe=ca5d80f8f9) | Jun 16, 2020 |
| MSI           | GE66 Raider 10SF            | [220b2a94c8](https://linux-hardware.org/?probe=220b2a94c8) | Jun 10, 2020 |
| HP            | ProBook 4540s               | [b28f2f3b8a](https://linux-hardware.org/?probe=b28f2f3b8a) | Jun 05, 2020 |
| HP            | Presario CQ56               | [4eed3fc6f6](https://linux-hardware.org/?probe=4eed3fc6f6) | Jun 05, 2020 |
| MSI           | GE66 Raider 10SF            | [8c0b76c629](https://linux-hardware.org/?probe=8c0b76c629) | Jun 01, 2020 |
| Acer          | Aspire E1-571               | [25ca966875](https://linux-hardware.org/?probe=25ca966875) | Jun 01, 2020 |
| MSI           | GE66 Raider 10SF            | [1cb7bb7ad9](https://linux-hardware.org/?probe=1cb7bb7ad9) | May 23, 2020 |
| MSI           | GE66 Raider 10SF            | [afec91ff4d](https://linux-hardware.org/?probe=afec91ff4d) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| HP            | EliteBook 8560p             | [5439d2f06b](https://linux-hardware.org/?probe=5439d2f06b) | May 22, 2020 |
| Dell          | Latitude E6430s             | [891fd84ed1](https://linux-hardware.org/?probe=891fd84ed1) | May 21, 2020 |
| Dell          | Latitude E6430s             | [b2f67f2744](https://linux-hardware.org/?probe=b2f67f2744) | May 20, 2020 |
| Sony          | VPCEH28FG                   | [f241603946](https://linux-hardware.org/?probe=f241603946) | May 17, 2020 |
| Lenovo        | ThinkPad E590 20NBS0SC00    | [50ca962181](https://linux-hardware.org/?probe=50ca962181) | May 14, 2020 |
| HP            | EliteBook 8570p             | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| HP            | EliteBook 8560p             | [605660fceb](https://linux-hardware.org/?probe=605660fceb) | May 11, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | [d1258905c6](https://linux-hardware.org/?probe=d1258905c6) | May 10, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | [51adfc765c](https://linux-hardware.org/?probe=51adfc765c) | May 10, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [8ca322cd11](https://linux-hardware.org/?probe=8ca322cd11) | May 06, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [e0d0592e34](https://linux-hardware.org/?probe=e0d0592e34) | May 05, 2020 |
| HP            | ProBook 650 G1              | [ed42eb842d](https://linux-hardware.org/?probe=ed42eb842d) | May 04, 2020 |
| HP            | ProBook 650 G1              | [d29d76cb5c](https://linux-hardware.org/?probe=d29d76cb5c) | May 04, 2020 |
| HP            | Presario CQ57               | [df09ee9161](https://linux-hardware.org/?probe=df09ee9161) | Apr 26, 2020 |
| Toshiba       | TECRA Z50-A                 | [ff5b768627](https://linux-hardware.org/?probe=ff5b768627) | Apr 21, 2020 |
| Acer          | Aspire A315-21G             | [7f9e52f0dd](https://linux-hardware.org/?probe=7f9e52f0dd) | Apr 20, 2020 |
| Acer          | Aspire A315-21G             | [4409c8dae5](https://linux-hardware.org/?probe=4409c8dae5) | Apr 20, 2020 |
| HP            | Pavilion g6                 | [15ad84ee0f](https://linux-hardware.org/?probe=15ad84ee0f) | Apr 15, 2020 |
| Dell          | XPS 13 9360                 | [89cce1b8b6](https://linux-hardware.org/?probe=89cce1b8b6) | Apr 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e4ed30a655](https://linux-hardware.org/?probe=e4ed30a655) | Apr 04, 2020 |
| Toshiba       | Satellite L750              | [391a50ded4](https://linux-hardware.org/?probe=391a50ded4) | Apr 03, 2020 |
| ASUSTek       | N56VZ                       | [04666ab26e](https://linux-hardware.org/?probe=04666ab26e) | Apr 01, 2020 |
| HP            | Pavilion 10 TS              | [87484a7033](https://linux-hardware.org/?probe=87484a7033) | Mar 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0c505fcd69](https://linux-hardware.org/?probe=0c505fcd69) | Mar 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [fc12fa3a4d](https://linux-hardware.org/?probe=fc12fa3a4d) | Mar 25, 2020 |
| Dell          | Precision M6800             | [adb3b768f7](https://linux-hardware.org/?probe=adb3b768f7) | Mar 24, 2020 |
| ASUSTek       | TAICHI21                    | [608a903011](https://linux-hardware.org/?probe=608a903011) | Mar 11, 2020 |
| HP            | EliteBook 840 G6            | [a26150e202](https://linux-hardware.org/?probe=a26150e202) | Mar 07, 2020 |
| HP            | EliteBook 840 G6            | [0d6d26562c](https://linux-hardware.org/?probe=0d6d26562c) | Mar 07, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [f49a66ef1e](https://linux-hardware.org/?probe=f49a66ef1e) | Feb 25, 2020 |
| HP            | Pavilion 15                 | [72784962fe](https://linux-hardware.org/?probe=72784962fe) | Feb 25, 2020 |
| HP            | Pavilion 15                 | [a1e89aa309](https://linux-hardware.org/?probe=a1e89aa309) | Feb 25, 2020 |
| Dell          | Latitude E4300              | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| HP            | EliteBook x360 1040 G6      | [a838427772](https://linux-hardware.org/?probe=a838427772) | Feb 12, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [5f61d3d553](https://linux-hardware.org/?probe=5f61d3d553) | Feb 09, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [10d5285055](https://linux-hardware.org/?probe=10d5285055) | Feb 07, 2020 |
| HP            | ProBook 650 G1              | [b5d441afe1](https://linux-hardware.org/?probe=b5d441afe1) | Feb 01, 2020 |
| Lenovo        | V110-14IAP 80TF             | [85b3202273](https://linux-hardware.org/?probe=85b3202273) | Jan 30, 2020 |
| Dell          | XPS 13 9360                 | [c770de6326](https://linux-hardware.org/?probe=c770de6326) | Jan 25, 2020 |
| Lenovo        | ThinkPad X131e 33691A4      | [a30712cd7d](https://linux-hardware.org/?probe=a30712cd7d) | Jan 22, 2020 |
| HP            | Notebook                    | [8f2fc8e2ec](https://linux-hardware.org/?probe=8f2fc8e2ec) | Jan 09, 2020 |
| ASUSTek       | K46CB                       | [45b756e92d](https://linux-hardware.org/?probe=45b756e92d) | Jan 04, 2020 |
| ASUSTek       | K46CB                       | [1a25890709](https://linux-hardware.org/?probe=1a25890709) | Jan 04, 2020 |
| HP            | ProBook 650 G1              | [0763c1c109](https://linux-hardware.org/?probe=0763c1c109) | Jan 02, 2020 |
| HP            | ProBook 650 G1              | [023556890d](https://linux-hardware.org/?probe=023556890d) | Jan 02, 2020 |
| Acer          | Aspire F5-573G              | [ead658852a](https://linux-hardware.org/?probe=ead658852a) | Jan 01, 2020 |
| Acer          | Aspire F5-573G              | [e19db7603d](https://linux-hardware.org/?probe=e19db7603d) | Jan 01, 2020 |
| HP            | ProBook 6550b               | [65a8d66fb9](https://linux-hardware.org/?probe=65a8d66fb9) | Dec 31, 2019 |
| HP            | ProBook 650 G1              | [0085227124](https://linux-hardware.org/?probe=0085227124) | Dec 30, 2019 |
| HP            | EliteBook 850 G5            | [65b1eb0ca1](https://linux-hardware.org/?probe=65b1eb0ca1) | Dec 26, 2019 |
| Lenovo        | ThinkPad T420 4180AQ3       | [4da7aff7a2](https://linux-hardware.org/?probe=4da7aff7a2) | Dec 23, 2019 |
| ASUSTek       | UL50Ag                      | [ba1e7f648c](https://linux-hardware.org/?probe=ba1e7f648c) | Dec 19, 2019 |
| MSI           | GT72 2PC                    | [dbe1269ea7](https://linux-hardware.org/?probe=dbe1269ea7) | Dec 11, 2019 |
| HP            | Pavilion g6                 | [3acb153d5d](https://linux-hardware.org/?probe=3acb153d5d) | Dec 06, 2019 |
| HP            | EliteBook 6930p             | [94af8c86b1](https://linux-hardware.org/?probe=94af8c86b1) | Dec 03, 2019 |
| HP            | Pavilion g6                 | [034500d792](https://linux-hardware.org/?probe=034500d792) | Nov 26, 2019 |
| Dell          | Latitude 7285               | [87a44ef029](https://linux-hardware.org/?probe=87a44ef029) | Nov 22, 2019 |
| Dell          | Latitude 7285               | [34937530ea](https://linux-hardware.org/?probe=34937530ea) | Nov 21, 2019 |
| HP            | Notebook                    | [31d1bef6c1](https://linux-hardware.org/?probe=31d1bef6c1) | Nov 11, 2019 |
| HP            | ProBook 4540s               | [5cc8316a85](https://linux-hardware.org/?probe=5cc8316a85) | Nov 08, 2019 |
| HP            | ProBook 4730s               | [ed03fd8077](https://linux-hardware.org/?probe=ed03fd8077) | Oct 29, 2019 |
| HP            | ProBook 4730s               | [cd284908ca](https://linux-hardware.org/?probe=cd284908ca) | Oct 28, 2019 |
| HP            | Notebook                    | [1bccff3cda](https://linux-hardware.org/?probe=1bccff3cda) | Sep 25, 2019 |
| Toshiba       | PORTEGE M780                | [64824e5a04](https://linux-hardware.org/?probe=64824e5a04) | Sep 21, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [8e78a0ebf5](https://linux-hardware.org/?probe=8e78a0ebf5) | Sep 11, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [fd27e8c70f](https://linux-hardware.org/?probe=fd27e8c70f) | Sep 11, 2019 |
| HP            | Notebook                    | [776ffefbc2](https://linux-hardware.org/?probe=776ffefbc2) | Sep 11, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [f5b3521c55](https://linux-hardware.org/?probe=f5b3521c55) | Sep 11, 2019 |
| HP            | Notebook                    | [cf646ad1f2](https://linux-hardware.org/?probe=cf646ad1f2) | Sep 11, 2019 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [873e28fce7](https://linux-hardware.org/?probe=873e28fce7) | Sep 02, 2019 |
| HP            | Compaq 6910p (GM903PA#AB... | [2724623348](https://linux-hardware.org/?probe=2724623348) | Aug 12, 2019 |
| ASUSTek       | X542UQ                      | [7a4797b166](https://linux-hardware.org/?probe=7a4797b166) | Aug 11, 2019 |
| HP            | ProBook 6570b               | [4f80f9ba3c](https://linux-hardware.org/?probe=4f80f9ba3c) | Aug 04, 2019 |
| Lenovo        | ThinkPad T440p 20AWS1J00... | [31bcd5a103](https://linux-hardware.org/?probe=31bcd5a103) | Jul 31, 2019 |
| HP            | ProBook 450 G3              | [b9e21a89da](https://linux-hardware.org/?probe=b9e21a89da) | Jul 23, 2019 |
| HP            | ProBook 650 G1              | [6d584d5dab](https://linux-hardware.org/?probe=6d584d5dab) | Jul 22, 2019 |
| HP            | ProBook 450 G3              | [10b8987b19](https://linux-hardware.org/?probe=10b8987b19) | Jul 17, 2019 |
| HP            | ProBook 6550b               | [801f83247c](https://linux-hardware.org/?probe=801f83247c) | Jul 06, 2019 |
| HP            | ProBook 4730s               | [ed98a45d81](https://linux-hardware.org/?probe=ed98a45d81) | Jul 01, 2019 |
| Acer          | Aspire 5100                 | [a28f7b2623](https://linux-hardware.org/?probe=a28f7b2623) | Jun 27, 2019 |
| Acer          | Aspire 5100                 | [aa61fb2b9c](https://linux-hardware.org/?probe=aa61fb2b9c) | Jun 11, 2019 |
| YJKC          | vBOOK Plus                  | [80eae9ed5f](https://linux-hardware.org/?probe=80eae9ed5f) | Jun 09, 2019 |
| HP            | Unknown                     | [ef6ea82cf5](https://linux-hardware.org/?probe=ef6ea82cf5) | May 20, 2019 |
| ASUSTek       | K84L                        | [231a7d9bc6](https://linux-hardware.org/?probe=231a7d9bc6) | Apr 18, 2019 |
| HP            | ProBook 6570b               | [42129ed417](https://linux-hardware.org/?probe=42129ed417) | Mar 23, 2019 |
| HP            | ProBook 6570b               | [25a7d4cca8](https://linux-hardware.org/?probe=25a7d4cca8) | Mar 03, 2019 |
| Acer          | Aspire E5-721               | [e6dca4d6fd](https://linux-hardware.org/?probe=e6dca4d6fd) | Feb 28, 2019 |
| HP            | Mini 110-1100               | [1ba5e0d0b2](https://linux-hardware.org/?probe=1ba5e0d0b2) | Feb 23, 2019 |
| HP            | ProBook 6570b               | [82e153050f](https://linux-hardware.org/?probe=82e153050f) | Jan 28, 2019 |
| HP            | ProBook 650 G1              | [2756a314e5](https://linux-hardware.org/?probe=2756a314e5) | Jan 14, 2019 |
| HP            | ProBook 650 G1              | [f81c16faea](https://linux-hardware.org/?probe=f81c16faea) | Jan 14, 2019 |
| Lenovo        | B590 20208                  | [7c06278f98](https://linux-hardware.org/?probe=7c06278f98) | Dec 28, 2018 |
| Lenovo        | B590 20208                  | [d4897cc9d7](https://linux-hardware.org/?probe=d4897cc9d7) | Dec 28, 2018 |
| HP            | Pavilion 15                 | [5407e9ab05](https://linux-hardware.org/?probe=5407e9ab05) | Dec 22, 2018 |
| HP            | Pavilion 15                 | [a47a651328](https://linux-hardware.org/?probe=a47a651328) | Dec 22, 2018 |
| HP            | 14                          | [553085d233](https://linux-hardware.org/?probe=553085d233) | Jul 06, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/New_Zealand/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 37        | 10.08%  |
| Ubuntu 22.04        | 18        | 4.9%    |
| Ubuntu 18.04        | 15        | 4.09%   |
| Pop!_OS 22.04       | 14        | 3.81%   |
| OpenMandriva 4.3    | 11        | 3%      |
| Zorin 16            | 10        | 2.72%   |
| Zorin 15            | 10        | 2.72%   |
| Arch Rolling        | 10        | 2.72%   |
| Arch                | 10        | 2.72%   |
| Pop!_OS 20.04       | 8         | 2.18%   |
| OpenMandriva 4.2    | 8         | 2.18%   |
| Debian 11           | 8         | 2.18%   |
| OpenMandriva 23.01  | 7         | 1.91%   |
| Ubuntu 21.10        | 6         | 1.63%   |
| Ubuntu 20.10        | 6         | 1.63%   |
| Linux Mint 20.2     | 6         | 1.63%   |
| Fedora 31           | 6         | 1.63%   |
| Debian 10           | 6         | 1.63%   |
| Pop!_OS 20.10       | 5         | 1.36%   |
| Linux Mint 21.1     | 5         | 1.36%   |
| Linux Mint 21       | 5         | 1.36%   |
| Linux Mint 20.3     | 5         | 1.36%   |
| Fedora 35           | 5         | 1.36%   |
| Ubuntu 21.04        | 4         | 1.09%   |
| Pop!_OS 21.04       | 4         | 1.09%   |
| Manjaro             | 4         | 1.09%   |
| Linux Mint 19.2     | 4         | 1.09%   |
| Kubuntu 22.04       | 4         | 1.09%   |
| Kubuntu 20.04       | 4         | 1.09%   |
| Fedora 34           | 4         | 1.09%   |
| Fedora 33           | 4         | 1.09%   |
| EndeavourOS Rolling | 4         | 1.09%   |
| Ubuntu 19.10        | 3         | 0.82%   |
| MX 21               | 3         | 0.82%   |
| Linux Mint 20       | 3         | 0.82%   |
| Linux Mint 19.3     | 3         | 0.82%   |
| Linux Mint 19.1     | 3         | 0.82%   |
| Fedora 37           | 3         | 0.82%   |
| Fedora 36           | 3         | 0.82%   |
| Fedora 32           | 3         | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 90        | 25.71%  |
| Linux Mint       | 35        | 10%     |
| Pop!_OS          | 32        | 9.14%   |
| OpenMandriva     | 28        | 8%      |
| Fedora           | 27        | 7.71%   |
| Zorin            | 20        | 5.71%   |
| Arch             | 20        | 5.71%   |
| Debian           | 18        | 5.14%   |
| Manjaro          | 9         | 2.57%   |
| Kubuntu          | 9         | 2.57%   |
| Endless          | 5         | 1.43%   |
| EndeavourOS      | 5         | 1.43%   |
| Elementary       | 5         | 1.43%   |
| Gentoo           | 4         | 1.14%   |
| Xubuntu          | 3         | 0.86%   |
| Ubuntu Unity     | 3         | 0.86%   |
| Nobara           | 3         | 0.86%   |
| MX               | 3         | 0.86%   |
| LMDE             | 3         | 0.86%   |
| Kali             | 3         | 0.86%   |
| Ubuntu MATE      | 2         | 0.57%   |
| SteamOS          | 2         | 0.57%   |
| Solus            | 2         | 0.57%   |
| ROSA             | 2         | 0.57%   |
| Peppermint       | 2         | 0.57%   |
| openSUSE         | 2         | 0.57%   |
| Lubuntu          | 2         | 0.57%   |
| KDE neon         | 2         | 0.57%   |
| ArcoLinux        | 2         | 0.57%   |
| Void Linux       | 1         | 0.29%   |
| Sparky           | 1         | 0.29%   |
| Parrot           | 1         | 0.29%   |
| org.kde.Platform | 1         | 0.29%   |
| BlackPanther     | 1         | 0.29%   |
| Archman          | 1         | 0.29%   |
| antiX            | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 2.98%   |
| 5.16.7-desktop-1omv4003  | 10        | 2.48%   |
| 5.15.0-46-generic        | 8         | 1.99%   |
| 5.10.14-desktop-1omv4002 | 8         | 1.99%   |
| 6.1.1-desktop-1omv2290   | 7         | 1.74%   |
| 6.0.12-76060006-generic  | 6         | 1.49%   |
| 5.4.0-48-generic         | 5         | 1.24%   |
| 5.3.0-28-generic         | 5         | 1.24%   |
| 5.3.16-300.fc31.x86_64   | 4         | 0.99%   |
| 5.17.5-76051705-generic  | 4         | 0.99%   |
| 5.15.0-58-generic        | 4         | 0.99%   |
| 5.15.0-56-generic        | 4         | 0.99%   |
| 5.11.0-7620-generic      | 4         | 0.99%   |
| 5.11.0-27-generic        | 4         | 0.99%   |
| 5.8.0-53-generic         | 3         | 0.74%   |
| 5.4.0-81-generic         | 3         | 0.74%   |
| 5.4.0-7642-generic       | 3         | 0.74%   |
| 5.4.0-74-generic         | 3         | 0.74%   |
| 5.4.0-65-generic         | 3         | 0.74%   |
| 5.4.0-45-generic         | 3         | 0.74%   |
| 5.4.0-26-generic         | 3         | 0.74%   |
| 5.15.0-60-generic        | 3         | 0.74%   |
| 5.15.0-57-generic        | 3         | 0.74%   |
| 5.15.0-53-generic        | 3         | 0.74%   |
| 5.13.0-37-generic        | 3         | 0.74%   |
| 5.10.0-18-amd64          | 3         | 0.74%   |
| 5.10.0-16-amd64          | 3         | 0.74%   |
| 5.0.0-37-generic         | 3         | 0.74%   |
| 4.19.0-9-amd64           | 3         | 0.74%   |
| 6.1.1-arch1-1            | 2         | 0.5%    |
| 5.8.11-1-MANJARO         | 2         | 0.5%    |
| 5.8.0-7630-generic       | 2         | 0.5%    |
| 5.8.0-48-generic         | 2         | 0.5%    |
| 5.8.0-43-generic         | 2         | 0.5%    |
| 5.4.0-91-generic         | 2         | 0.5%    |
| 5.4.0-88-generic         | 2         | 0.5%    |
| 5.4.0-72-generic         | 2         | 0.5%    |
| 5.4.0-40-generic         | 2         | 0.5%    |
| 5.4.0-39-generic         | 2         | 0.5%    |
| 5.4.0-29-generic         | 2         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 58        | 15.1%   |
| 5.15.0  | 36        | 9.38%   |
| 5.13.0  | 22        | 5.73%   |
| 5.11.0  | 17        | 4.43%   |
| 5.3.0   | 16        | 4.17%   |
| 5.8.0   | 15        | 3.91%   |
| 4.15.0  | 14        | 3.65%   |
| 5.10.0  | 12        | 3.13%   |
| 5.0.0   | 12        | 3.13%   |
| 5.16.7  | 10        | 2.6%    |
| 6.1.1   | 9         | 2.34%   |
| 5.10.14 | 9         | 2.34%   |
| 5.19.0  | 7         | 1.82%   |
| 4.19.0  | 7         | 1.82%   |
| 6.0.12  | 6         | 1.56%   |
| 4.18.0  | 6         | 1.56%   |
| 5.3.16  | 4         | 1.04%   |
| 5.17.5  | 4         | 1.04%   |
| 5.15.4  | 3         | 0.78%   |
| 6.2.8   | 2         | 0.52%   |
| 6.1.0   | 2         | 0.52%   |
| 6.0.10  | 2         | 0.52%   |
| 6.0.0   | 2         | 0.52%   |
| 5.8.11  | 2         | 0.52%   |
| 5.7.0   | 2         | 0.52%   |
| 5.6.8   | 2         | 0.52%   |
| 5.6.19  | 2         | 0.52%   |
| 5.3.8   | 2         | 0.52%   |
| 5.19.7  | 2         | 0.52%   |
| 5.18.6  | 2         | 0.52%   |
| 5.18.10 | 2         | 0.52%   |
| 5.18.0  | 2         | 0.52%   |
| 5.17.15 | 2         | 0.52%   |
| 5.16.11 | 2         | 0.52%   |
| 5.15.15 | 2         | 0.52%   |
| 5.15.12 | 2         | 0.52%   |
| 5.14.15 | 2         | 0.52%   |
| 5.11.12 | 2         | 0.52%   |
| 6.2.7   | 1         | 0.26%   |
| 6.2.6   | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 63        | 16.76%  |
| 5.15    | 48        | 12.77%  |
| 5.10    | 27        | 7.18%   |
| 5.13    | 25        | 6.65%   |
| 5.11    | 22        | 5.85%   |
| 5.8     | 21        | 5.59%   |
| 5.3     | 21        | 5.59%   |
| 5.16    | 18        | 4.79%   |
| 6.1     | 15        | 3.99%   |
| 4.15    | 14        | 3.72%   |
| 6.0     | 13        | 3.46%   |
| 5.0     | 12        | 3.19%   |
| 5.19    | 10        | 2.66%   |
| 5.18    | 9         | 2.39%   |
| 5.17    | 8         | 2.13%   |
| 4.19    | 7         | 1.86%   |
| 4.18    | 7         | 1.86%   |
| 5.6     | 6         | 1.6%    |
| 5.14    | 6         | 1.6%    |
| 6.2     | 5         | 1.33%   |
| 5.7     | 5         | 1.33%   |
| 5.9     | 4         | 1.06%   |
| 4.9     | 3         | 0.8%    |
| 5.5     | 2         | 0.53%   |
| 4.20    | 2         | 0.53%   |
| 5.2     | 1         | 0.27%   |
| 4.13    | 1         | 0.27%   |
| 4.11    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 323       | 97.29%  |
| i686   | 9         | 2.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 164       | 46.99%  |
| KDE5             | 49        | 14.04%  |
| Unknown          | 34        | 9.74%   |
| X-Cinnamon       | 27        | 7.74%   |
| XFCE             | 25        | 7.16%   |
| KDE              | 10        | 2.87%   |
| MATE             | 9         | 2.58%   |
| Pantheon         | 5         | 1.43%   |
| i3               | 5         | 1.43%   |
| Cinnamon         | 4         | 1.15%   |
| Unity            | 3         | 0.86%   |
| LXDE             | 3         | 0.86%   |
| LXQt             | 2         | 0.57%   |
| Hyprland         | 2         | 0.57%   |
| Budgie           | 2         | 0.57%   |
| lightdm-xsession | 1         | 0.29%   |
| KDE4             | 1         | 0.29%   |
| icewm            | 1         | 0.29%   |
| i3-with-shmlog   | 1         | 0.29%   |
| Deepin           | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 261       | 75.87%  |
| Wayland | 64        | 18.6%   |
| Unknown | 16        | 4.65%   |
| Tty     | 3         | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 183       | 52.29%  |
| SDDM    | 44        | 12.57%  |
| GDM     | 39        | 11.14%  |
| GDM3    | 34        | 9.71%   |
| LightDM | 33        | 9.43%   |
| TDM     | 11        | 3.14%   |
| Ly      | 2         | 0.57%   |
| LXDM    | 2         | 0.57%   |
| XDM     | 1         | 0.29%   |
| KDM     | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_NZ   | 210       | 60.17%  |
| en_US   | 73        | 20.92%  |
| Unknown | 28        | 8.02%   |
| en_GB   | 16        | 4.58%   |
| C       | 10        | 2.87%   |
| en_AU   | 7         | 2.01%   |
| mi_NZ   | 2         | 0.57%   |
| zh_CN   | 1         | 0.29%   |
| pt_BR   | 1         | 0.29%   |
| de_DE   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 177       | 52.37%  |
| BIOS | 161       | 47.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 265       | 76.81%  |
| Overlay | 30        | 8.7%    |
| Btrfs   | 28        | 8.12%   |
| Unknown | 14        | 4.06%   |
| Ext2    | 3         | 0.87%   |
| Zfs     | 2         | 0.58%   |
| Xfs     | 2         | 0.58%   |
| Ext3    | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 186       | 54.39%  |
| GPT     | 117       | 34.21%  |
| MBR     | 39        | 11.4%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 299       | 87.68%  |
| Yes       | 42        | 12.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 257       | 76.04%  |
| Yes       | 81        | 23.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 101       | 30.42%  |
| Lenovo              | 52        | 15.66%  |
| Dell                | 47        | 14.16%  |
| ASUSTek Computer    | 34        | 10.24%  |
| Acer                | 28        | 8.43%   |
| Toshiba             | 18        | 5.42%   |
| MSI                 | 10        | 3.01%   |
| Apple               | 9         | 2.71%   |
| Sony                | 6         | 1.81%   |
| Google              | 5         | 1.51%   |
| Samsung Electronics | 4         | 1.2%    |
| Valve               | 2         | 0.6%    |
| System76            | 2         | 0.6%    |
| YJKC                | 1         | 0.3%    |
| TWG                 | 1         | 0.3%    |
| Timi                | 1         | 0.3%    |
| The Warehouse Group | 1         | 0.3%    |
| Star Labs           | 1         | 0.3%    |
| Metabox             | 1         | 0.3%    |
| Medion              | 1         | 0.3%    |
| Kogan               | 1         | 0.3%    |
| IBM                 | 1         | 0.3%    |
| HUAWEI              | 1         | 0.3%    |
| Gigabyte Technology | 1         | 0.3%    |
| eMachines           | 1         | 0.3%    |
| Alienware           | 1         | 0.3%    |
| Unknown             | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Dell XPS 13 9360                          | 5         | 1.51%   |
| HP ProBook 6550b                          | 4         | 1.2%    |
| HP Pavilion dv6                           | 4         | 1.2%    |
| HP Notebook                               | 4         | 1.2%    |
| HP ProBook 4540s                          | 3         | 0.9%    |
| HP Pavilion 15                            | 3         | 0.9%    |
| HP EliteBook 8560p                        | 3         | 0.9%    |
| Acer Aspire F5-573G                       | 3         | 0.9%    |
| Valve Jupiter                             | 2         | 0.6%    |
| Toshiba Satellite L750                    | 2         | 0.6%    |
| MSI GE66 Raider 10SF                      | 2         | 0.6%    |
| Lenovo ThinkPad T460 20FMS2FR00           | 2         | 0.6%    |
| Lenovo ThinkPad T420 4180AQ3              | 2         | 0.6%    |
| HP ZBook Firefly 15 G7 Mobile Workstation | 2         | 0.6%    |
| HP ProBook 6570b                          | 2         | 0.6%    |
| HP ProBook 450 G5                         | 2         | 0.6%    |
| HP ProBook 450 G3                         | 2         | 0.6%    |
| HP EliteBook 8570p                        | 2         | 0.6%    |
| Dell XPS 15 9500                          | 2         | 0.6%    |
| Dell System XPS L702X                     | 2         | 0.6%    |
| Dell Latitude E7440                       | 2         | 0.6%    |
| Dell Latitude E6430s                      | 2         | 0.6%    |
| Dell Latitude E5570                       | 2         | 0.6%    |
| Dell Latitude E4300                       | 2         | 0.6%    |
| Dell Latitude 7490                        | 2         | 0.6%    |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR     | 2         | 0.6%    |
| ASUS ROG Strix G513QY_G513QY              | 2         | 0.6%    |
| ASUS K52Jc                                | 2         | 0.6%    |
| ASUS ASUS TUF Dash F15 FX516PM_FX516PM    | 2         | 0.6%    |
| ASUS ASUS EXPERTBOOK P2451FA_P2451FA      | 2         | 0.6%    |
| Acer Swift SF314-41                       | 2         | 0.6%    |
| Unknown                                   | 2         | 0.6%    |
| YJKC vBOOK Plus                           | 1         | 0.3%    |
| TWG E2017                                 | 1         | 0.3%    |
| Toshiba TECRA Z50-A                       | 1         | 0.3%    |
| Toshiba Satellite U940                    | 1         | 0.3%    |
| Toshiba Satellite U920t                   | 1         | 0.3%    |
| Toshiba Satellite S70t-B                  | 1         | 0.3%    |
| Toshiba Satellite Pro R50-C               | 1         | 0.3%    |
| Toshiba Satellite Pro L830                | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 36        | 10.84%  |
| HP ProBook                | 24        | 7.23%   |
| HP EliteBook              | 23        | 6.93%   |
| HP Pavilion               | 19        | 5.72%   |
| Dell Latitude             | 18        | 5.42%   |
| Acer Aspire               | 18        | 5.42%   |
| Toshiba Satellite         | 13        | 3.92%   |
| Dell XPS                  | 11        | 3.31%   |
| HP ZBook                  | 8         | 2.41%   |
| HP Laptop                 | 6         | 1.81%   |
| Dell Inspiron             | 6         | 1.81%   |
| ASUS ROG                  | 6         | 1.81%   |
| Dell Precision            | 5         | 1.51%   |
| ASUS ASUS                 | 5         | 1.51%   |
| Toshiba PORTEGE           | 4         | 1.2%    |
| HP Notebook               | 4         | 1.2%    |
| Acer TravelMate           | 4         | 1.2%    |
| HP Compaq                 | 3         | 0.9%    |
| ASUS VivoBook             | 3         | 0.9%    |
| Apple MacBookPro5         | 3         | 0.9%    |
| Valve Jupiter             | 2         | 0.6%    |
| MSI GE66                  | 2         | 0.6%    |
| Lenovo Yoga               | 2         | 0.6%    |
| Lenovo IdeaPad            | 2         | 0.6%    |
| HP Presario               | 2         | 0.6%    |
| HP ENVY                   | 2         | 0.6%    |
| Dell Vostro               | 2         | 0.6%    |
| Dell System               | 2         | 0.6%    |
| ASUS ZenBook              | 2         | 0.6%    |
| ASUS K52Jc                | 2         | 0.6%    |
| Apple MacBook5            | 2         | 0.6%    |
| Acer Swift                | 2         | 0.6%    |
| Unknown                   | 2         | 0.6%    |
| YJKC vBOOK                | 1         | 0.3%    |
| TWG E2017                 | 1         | 0.3%    |
| Toshiba TECRA             | 1         | 0.3%    |
| Timi A30                  | 1         | 0.3%    |
| The Warehouse Group E2037 | 1         | 0.3%    |
| System76 Pangolin         | 1         | 0.3%    |
| System76 Lemur            | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 38        | 11.45%  |
| 2011 | 35        | 10.54%  |
| 2020 | 27        | 8.13%   |
| 2021 | 26        | 7.83%   |
| 2018 | 26        | 7.83%   |
| 2019 | 23        | 6.93%   |
| 2016 | 22        | 6.63%   |
| 2017 | 21        | 6.33%   |
| 2013 | 20        | 6.02%   |
| 2022 | 18        | 5.42%   |
| 2014 | 17        | 5.12%   |
| 2008 | 16        | 4.82%   |
| 2015 | 15        | 4.52%   |
| 2010 | 14        | 4.22%   |
| 2009 | 9         | 2.71%   |
| 2007 | 2         | 0.6%    |
| 2006 | 2         | 0.6%    |
| 2005 | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 332       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 294       | 88.02%  |
| Enabled  | 40        | 11.98%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 325       | 97.89%  |
| Yes  | 7         | 2.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 93        | 27.27%  |
| 16.01-24.0  | 65        | 19.06%  |
| 3.01-4.0    | 62        | 18.18%  |
| 8.01-16.0   | 62        | 18.18%  |
| 32.01-64.0  | 31        | 9.09%   |
| 1.01-2.0    | 9         | 2.64%   |
| 64.01-256.0 | 7         | 2.05%   |
| 24.01-32.0  | 5         | 1.47%   |
| 2.01-3.0    | 4         | 1.17%   |
| 0.51-1.0    | 3         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 127       | 34.32%  |
| 2.01-3.0   | 99        | 26.76%  |
| 3.01-4.0   | 55        | 14.86%  |
| 4.01-8.0   | 49        | 13.24%  |
| 0.51-1.0   | 20        | 5.41%   |
| 8.01-16.0  | 11        | 2.97%   |
| 16.01-24.0 | 5         | 1.35%   |
| 24.01-32.0 | 2         | 0.54%   |
| 0.01-0.5   | 2         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 257       | 75.15%  |
| 2      | 71        | 20.76%  |
| 3      | 12        | 3.51%   |
| 0      | 2         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 199       | 59.58%  |
| Yes       | 135       | 40.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 82.39%  |
| No        | 59        | 17.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 329       | 99.1%   |
| No        | 3         | 0.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 270       | 80.12%  |
| No        | 67        | 19.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| New Zealand | 332       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Auckland         | 166       | 47.98%  |
| Wellington       | 37        | 10.69%  |
| Christchurch     | 33        | 9.54%   |
| Hamilton         | 20        | 5.78%   |
| Tauranga         | 12        | 3.47%   |
| Dunedin          | 10        | 2.89%   |
| Whangarei        | 7         | 2.02%   |
| Cambridge        | 7         | 2.02%   |
| New Plymouth     | 6         | 1.73%   |
| Palmerston North | 5         | 1.45%   |
| Nelson           | 5         | 1.45%   |
| Napier City      | 4         | 1.16%   |
| Lower Hutt       | 4         | 1.16%   |
| Invercargill     | 4         | 1.16%   |
| Hastings         | 4         | 1.16%   |
| Whanganui        | 2         | 0.58%   |
| Otaki            | 2         | 0.58%   |
| Grafton          | 2         | 0.58%   |
| Whitianga        | 1         | 0.29%   |
| Whatawhata       | 1         | 0.29%   |
| Tutukaka         | 1         | 0.29%   |
| Tokanui          | 1         | 0.29%   |
| Saint Andrews    | 1         | 0.29%   |
| Rotorua          | 1         | 0.29%   |
| Pakuranga        | 1         | 0.29%   |
| Masterton        | 1         | 0.29%   |
| Levin            | 1         | 0.29%   |
| Khandallah       | 1         | 0.29%   |
| Kerikeri         | 1         | 0.29%   |
| Katikati         | 1         | 0.29%   |
| Gordonton        | 1         | 0.29%   |
| Edgecumbe        | 1         | 0.29%   |
| Bulls            | 1         | 0.29%   |
| Ashburton        | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 81        | 108    | 20.15%  |
| Seagate                     | 51        | 55     | 12.69%  |
| WDC                         | 42        | 59     | 10.45%  |
| Toshiba                     | 37        | 45     | 9.2%    |
| Crucial                     | 25        | 41     | 6.22%   |
| SanDisk                     | 20        | 22     | 4.98%   |
| Unknown                     | 19        | 28     | 4.73%   |
| SK hynix                    | 18        | 20     | 4.48%   |
| Intel                       | 16        | 20     | 3.98%   |
| Hitachi                     | 12        | 14     | 2.99%   |
| Kingston                    | 11        | 14     | 2.74%   |
| HGST                        | 10        | 10     | 2.49%   |
| Micron Technology           | 9         | 13     | 2.24%   |
| KingSpec                    | 4         | 4      | 1%      |
| A-DATA Technology           | 4         | 4      | 1%      |
| Team                        | 3         | 3      | 0.75%   |
| LITEON                      | 3         | 3      | 0.75%   |
| China                       | 3         | 3      | 0.75%   |
| ASMT                        | 3         | 3      | 0.75%   |
| Apple                       | 3         | 3      | 0.75%   |
| Transcend                   | 2         | 2      | 0.5%    |
| TO Exter                    | 2         | 2      | 0.5%    |
| Silicon Motion              | 2         | 3      | 0.5%    |
| ROG                         | 2         | 2      | 0.5%    |
| O2 Micro                    | 2         | 2      | 0.5%    |
| Micron/Crucial Technology   | 2         | 2      | 0.5%    |
| KIOXIA                      | 2         | 3      | 0.5%    |
| Hewlett-Packard             | 2         | 4      | 0.5%    |
| XPG                         | 1         | 1      | 0.25%   |
| Star Drive                  | 1         | 1      | 0.25%   |
| ShiJi                       | 1         | 1      | 0.25%   |
| Phison Electronics          | 1         | 2      | 0.25%   |
| Phison                      | 1         | 1      | 0.25%   |
| Netac                       | 1         | 1      | 0.25%   |
| LITEONIT                    | 1         | 3      | 0.25%   |
| Kingston Technology Company | 1         | 1      | 0.25%   |
| KINGBANK                    | 1         | 1      | 0.25%   |
| JMicron Technology          | 1         | 1      | 0.25%   |
| HGST HTS                    | 1         | 1      | 0.25%   |
| Fujitsu                     | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 7         | 1.67%   |
| Intel NVMe SSD Drive 512GB             | 7         | 1.67%   |
| Seagate ST1000LM035-1RK172 970GB       | 6         | 1.43%   |
| Samsung NVMe SSD Drive 512GB           | 6         | 1.43%   |
| Seagate Expansion 4TB                  | 5         | 1.19%   |
| Samsung SSD 860 EVO 500GB              | 5         | 1.19%   |
| Samsung SSD 850 EVO 500GB              | 5         | 1.19%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 4         | 0.95%   |
| Toshiba MQ01ABF050 500GB               | 4         | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 4         | 0.95%   |
| SanDisk NVMe SSD Drive 512GB           | 4         | 0.95%   |
| Samsung NVMe SSD Drive 256GB           | 4         | 0.95%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.95%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 3         | 0.71%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.71%   |
| Unknown MMC Card  64GB                 | 3         | 0.71%   |
| Toshiba XG6 NVMe SSD Controller 1024GB | 3         | 0.71%   |
| Toshiba NVMe SSD Drive 512GB           | 3         | 0.71%   |
| Seagate ST9500420AS 500GB              | 3         | 0.71%   |
| Samsung SSD 870 EVO 1TB                | 3         | 0.71%   |
| Samsung SSD 850 EVO 1TB                | 3         | 0.71%   |
| Samsung MZVL21T0HCLR-00B00 1TB         | 3         | 0.71%   |
| Kingston SV300S37A240G 240GB SSD       | 3         | 0.71%   |
| Kingston SV300S37A120G 120GB SSD       | 3         | 0.71%   |
| Intel SSDPEKNU512GZ 512GB              | 3         | 0.71%   |
| Crucial CT240BX200SSD1 240GB           | 3         | 0.71%   |
| Crucial CT1000MX500SSD1 1TB            | 3         | 0.71%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 2         | 0.48%   |
| WDC WD5000BPVT-22HXZT3 500GB           | 2         | 0.48%   |
| WDC WD10SPZX-22Z10T1 1TB               | 2         | 0.48%   |
| WDC WD10SPZX-21Z10T0 1TB               | 2         | 0.48%   |
| WDC WD10JPVX-60JC3T0 1TB               | 2         | 0.48%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB   | 2         | 0.48%   |
| Unknown MMC Card  32GB                 | 2         | 0.48%   |
| Unknown MMC Card  2GB                  | 2         | 0.48%   |
| Unknown MMC Card  128GB                | 2         | 0.48%   |
| Toshiba NVMe SSD Drive 256GB           | 2         | 0.48%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.48%   |
| Toshiba MQ01ABD075 752GB               | 2         | 0.48%   |
| Toshiba MK5076GSX 500GB                | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 53     | 38.28%  |
| WDC                 | 31        | 39     | 24.22%  |
| Toshiba             | 18        | 23     | 14.06%  |
| Hitachi             | 12        | 14     | 9.38%   |
| HGST                | 10        | 10     | 7.81%   |
| Samsung Electronics | 2         | 2      | 1.56%   |
| Unknown             | 1         | 3      | 0.78%   |
| JMicron Technology  | 1         | 1      | 0.78%   |
| HGST HTS            | 1         | 1      | 0.78%   |
| Fujitsu             | 1         | 1      | 0.78%   |
| ASMT                | 1         | 1      | 0.78%   |
| Apple               | 1         | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 45     | 26.61%  |
| Crucial             | 21        | 37     | 16.94%  |
| SanDisk             | 13        | 13     | 10.48%  |
| Kingston            | 9         | 12     | 7.26%   |
| Micron Technology   | 7         | 10     | 5.65%   |
| KingSpec            | 4         | 4      | 3.23%   |
| Intel               | 4         | 7      | 3.23%   |
| A-DATA Technology   | 4         | 4      | 3.23%   |
| WDC                 | 3         | 10     | 2.42%   |
| Toshiba             | 3         | 4      | 2.42%   |
| Team                | 3         | 3      | 2.42%   |
| SK hynix            | 3         | 3      | 2.42%   |
| China               | 3         | 3      | 2.42%   |
| Transcend           | 2         | 2      | 1.61%   |
| TO Exter            | 2         | 2      | 1.61%   |
| Seagate             | 2         | 2      | 1.61%   |
| LITEON              | 2         | 2      | 1.61%   |
| Apple               | 2         | 2      | 1.61%   |
| Netac               | 1         | 1      | 0.81%   |
| LITEONIT            | 1         | 3      | 0.81%   |
| Hewlett-Packard     | 1         | 3      | 0.81%   |
| ASMT                | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 121       | 149    | 31.84%  |
| NVMe    | 119       | 155    | 31.32%  |
| SSD     | 117       | 173    | 30.79%  |
| MMC     | 19        | 26     | 5%      |
| Unknown | 4         | 4      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 216       | 304    | 58.06%  |
| NVMe | 119       | 154    | 31.99%  |
| MMC  | 19        | 26     | 5.11%   |
| SAS  | 18        | 23     | 4.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 158       | 221    | 65.56%  |
| 0.51-1.0   | 69        | 87     | 28.63%  |
| 1.01-2.0   | 8         | 8      | 3.32%   |
| 3.01-4.0   | 5         | 5      | 2.07%   |
| 4.01-10.0  | 1         | 1      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 96        | 27.75%  |
| 101-250        | 91        | 26.3%   |
| 501-1000       | 53        | 15.32%  |
| 1-20           | 31        | 8.96%   |
| 1001-2000      | 22        | 6.36%   |
| 51-100         | 22        | 6.36%   |
| 21-50          | 9         | 2.6%    |
| More than 3000 | 8         | 2.31%   |
| Unknown        | 8         | 2.31%   |
| 2001-3000      | 6         | 1.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 148       | 41%     |
| 21-50          | 68        | 18.84%  |
| 101-250        | 44        | 12.19%  |
| 51-100         | 41        | 11.36%  |
| 251-500        | 23        | 6.37%   |
| 501-1000       | 23        | 6.37%   |
| Unknown        | 8         | 2.22%   |
| 1001-2000      | 3         | 0.83%   |
| More than 3000 | 2         | 0.55%   |
| 2001-3000      | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 2      | 6.45%   |
| WDC WD7500BPKX-00HPJT0 752GB                        | 1         | 1      | 3.23%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.23%   |
| Toshiba MK5076GSX 500GB                             | 1         | 1      | 3.23%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 1      | 3.23%   |
| Toshiba MK3256GSY 320GB                             | 1         | 1      | 3.23%   |
| SK hynix SC308 SATA 128GB SSD                       | 1         | 1      | 3.23%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 2      | 3.23%   |
| SK hynix BC501 HFM512GDJTNG-8310A 512GB             | 1         | 1      | 3.23%   |
| ShiJi 512GB M.2-NVMe                                | 1         | 1      | 3.23%   |
| Seagate ST9500420ASG 500GB                          | 1         | 1      | 3.23%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 3.23%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 3.23%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 3.23%   |
| Seagate ST1000LM035-1RK172 970GB                    | 1         | 1      | 3.23%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 3.23%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 3.23%   |
| Intel SSDSCKKW240H6 240GB                           | 1         | 1      | 3.23%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 3.23%   |
| Hitachi HTS545032B9SA00 320GB                       | 1         | 1      | 3.23%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 3.23%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 3.23%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 3.23%   |
| HGST HTS 541075A9E680 752GB                         | 1         | 1      | 3.23%   |
| HGST HCC545050A7E380 500GB                          | 1         | 1      | 3.23%   |
| Crucial CT275MX300SSD1 275GB                        | 1         | 1      | 3.23%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 3.23%   |
| ASMT ASM105x 2TB                                    | 1         | 1      | 3.23%   |
| Apple HDD HTS547550A9E384 500GB                     | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 16.67%  |
| Toshiba             | 4         | 4      | 13.33%  |
| HGST                | 4         | 4      | 13.33%  |
| WDC                 | 2         | 2      | 6.67%   |
| SK hynix            | 2         | 4      | 6.67%   |
| Samsung Electronics | 2         | 2      | 6.67%   |
| Micron Technology   | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| Crucial             | 2         | 2      | 6.67%   |
| ShiJi               | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| HGST HTS            | 1         | 1      | 3.33%   |
| ASMT                | 1         | 1      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 5      | 26.32%  |
| Toshiba  | 4         | 4      | 21.05%  |
| HGST     | 4         | 4      | 21.05%  |
| WDC      | 2         | 2      | 10.53%  |
| Hitachi  | 2         | 2      | 10.53%  |
| HGST HTS | 1         | 1      | 5.26%   |
| Apple    | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 63.33%  |
| SSD  | 8         | 8      | 26.67%  |
| NVMe | 3         | 5      | 10%     |

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
| Detected | 205       | 321    | 57.75%  |
| Works    | 121       | 154    | 34.08%  |
| Malfunc  | 29        | 32     | 8.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 231       | 59.69%  |
| Samsung Electronics          | 49        | 12.66%  |
| AMD                          | 33        | 8.53%   |
| Toshiba America Info Systems | 17        | 4.39%   |
| SK hynix                     | 15        | 3.88%   |
| SanDisk                      | 14        | 3.62%   |
| Nvidia                       | 6         | 1.55%   |
| Micron/Crucial Technology    | 6         | 1.55%   |
| Phison Electronics           | 3         | 0.78%   |
| Kingston Technology Company  | 3         | 0.78%   |
| Silicon Motion               | 2         | 0.52%   |
| O2 Micro                     | 2         | 0.52%   |
| Micron Technology            | 2         | 0.52%   |
| KIOXIA                       | 2         | 0.52%   |
| Lite-On Technology           | 1         | 0.26%   |
| ADATA Technology             | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 35        | 8.56%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 30        | 7.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 28        | 6.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 6.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 5.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 13        | 3.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 2.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 2.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 2.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 2.44%   |
| Samsung NVMe SSD Controller 980                                                | 9         | 2.2%    |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 2.2%    |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 8         | 1.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 1.47%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.47%   |
| Intel SSD 660P Series                                                          | 6         | 1.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.47%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 5         | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.22%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 4         | 0.98%   |
| SK hynix Non-Volatile memory controller                                        | 4         | 0.98%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 0.98%   |
| Intel Non-Volatile memory controller                                           | 4         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 0.98%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.73%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.73%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.73%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 3         | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.73%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 0.49%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.49%   |
| SK hynix BC511                                                                 | 2         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 235       | 59.95%  |
| NVMe | 120       | 30.61%  |
| RAID | 23        | 5.87%   |
| IDE  | 14        | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 282       | 84.94%  |
| AMD    | 50        | 15.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 2.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 1.81%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 6         | 1.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 1.51%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.51%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 5         | 1.51%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.2%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.2%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.2%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 1.2%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 4         | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.9%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.9%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.9%    |
| Intel Core i3-3227U CPU @ 1.90GHz             | 3         | 0.9%    |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 3         | 0.9%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.9%    |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 3         | 0.9%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.9%    |
| Intel Pentium M processor 2.00GHz             | 2         | 0.6%    |
| Intel Core i9-10885H CPU @ 2.40GHz            | 2         | 0.6%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.6%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 99        | 29.82%  |
| Intel Core i7                  | 86        | 25.9%   |
| Other                          | 28        | 8.43%   |
| Intel Core 2 Duo               | 22        | 6.63%   |
| Intel Celeron                  | 19        | 5.72%   |
| Intel Core i3                  | 16        | 4.82%   |
| AMD Ryzen 5                    | 7         | 2.11%   |
| AMD A6                         | 7         | 2.11%   |
| AMD Ryzen 7                    | 6         | 1.81%   |
| AMD Ryzen 9                    | 5         | 1.51%   |
| AMD E2                         | 5         | 1.51%   |
| Intel Pentium                  | 3         | 0.9%    |
| Intel Core i9                  | 3         | 0.9%    |
| Intel Atom                     | 3         | 0.9%    |
| AMD Ryzen 5 PRO                | 3         | 0.9%    |
| AMD A8                         | 3         | 0.9%    |
| Intel Pentium M                | 2         | 0.6%    |
| AMD E1                         | 2         | 0.6%    |
| AMD A4                         | 2         | 0.6%    |
| Intel Xeon                     | 1         | 0.3%    |
| Intel Pentium Silver           | 1         | 0.3%    |
| Intel Genuine                  | 1         | 0.3%    |
| Intel Core m7                  | 1         | 0.3%    |
| Intel Celeron Dual-Core        | 1         | 0.3%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.3%    |
| AMD Turion 64 X2 Mobile        | 1         | 0.3%    |
| AMD Ryzen 7 PRO                | 1         | 0.3%    |
| AMD Ryzen 3                    | 1         | 0.3%    |
| AMD E                          | 1         | 0.3%    |
| AMD A10                        | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 171       | 51.35%  |
| 4      | 102       | 30.63%  |
| 6      | 22        | 6.61%   |
| 8      | 19        | 5.71%   |
| 1      | 7         | 2.1%    |
| 14     | 6         | 1.8%    |
| 10     | 6         | 1.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 332       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 253       | 75.98%  |
| 1      | 79        | 23.72%  |
| 8      | 1         | 0.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 324       | 96.14%  |
| Unknown        | 10        | 2.97%   |
| 32-bit         | 3         | 0.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 85        | 24.93%  |
| 0x206a7    | 30        | 8.8%    |
| 0x306a9    | 25        | 7.33%   |
| 0x806ea    | 15        | 4.4%    |
| 0x806ec    | 12        | 3.52%   |
| 0x406e3    | 11        | 3.23%   |
| 0x1067a    | 10        | 2.93%   |
| 0x806e9    | 9         | 2.64%   |
| 0x20655    | 9         | 2.64%   |
| 0x30678    | 8         | 2.35%   |
| 0xa0652    | 7         | 2.05%   |
| 0x40651    | 7         | 2.05%   |
| 0x306c3    | 7         | 2.05%   |
| 0x10676    | 7         | 2.05%   |
| 0x906e9    | 5         | 1.47%   |
| 0x906a4    | 5         | 1.47%   |
| 0x306d4    | 5         | 1.47%   |
| 0x07030105 | 5         | 1.47%   |
| 0x906ea    | 4         | 1.17%   |
| 0x906a3    | 4         | 1.17%   |
| 0x806c1    | 4         | 1.17%   |
| 0x506e3    | 4         | 1.17%   |
| 0x0a50000d | 4         | 1.17%   |
| 0x806d1    | 3         | 0.88%   |
| 0x706a8    | 3         | 0.88%   |
| 0x6fd      | 3         | 0.88%   |
| 0x506c9    | 3         | 0.88%   |
| 0x0a50000c | 3         | 0.88%   |
| 0x08600106 | 3         | 0.88%   |
| 0x08108102 | 3         | 0.88%   |
| 0x06006705 | 3         | 0.88%   |
| 0xa0660    | 2         | 0.59%   |
| 0x806eb    | 2         | 0.59%   |
| 0x6d8      | 2         | 0.59%   |
| 0x106e5    | 2         | 0.59%   |
| 0x106ca    | 2         | 0.59%   |
| 0x08608103 | 2         | 0.59%   |
| 0x08108109 | 2         | 0.59%   |
| 0x0700010f | 2         | 0.59%   |
| 0x06001119 | 2         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 63        | 18.98%  |
| SandyBridge      | 37        | 11.14%  |
| IvyBridge        | 33        | 9.94%   |
| Skylake          | 21        | 6.33%   |
| Penryn           | 20        | 6.02%   |
| Haswell          | 19        | 5.72%   |
| Silvermont       | 12        | 3.61%   |
| CometLake        | 12        | 3.61%   |
| Westmere         | 11        | 3.31%   |
| Zen 3            | 10        | 3.01%   |
| Puma             | 9         | 2.71%   |
| Alderlake Hybrid | 9         | 2.71%   |
| Unknown          | 9         | 2.71%   |
| TigerLake        | 8         | 2.41%   |
| Excavator        | 7         | 2.11%   |
| Broadwell        | 7         | 2.11%   |
| Zen+             | 6         | 1.81%   |
| Icelake          | 6         | 1.81%   |
| Goldmont plus    | 4         | 1.2%    |
| Goldmont         | 4         | 1.2%    |
| Core             | 4         | 1.2%    |
| Zen 2            | 3         | 0.9%    |
| Nehalem          | 3         | 0.9%    |
| Jaguar           | 3         | 0.9%    |
| Bonnell          | 3         | 0.9%    |
| Piledriver       | 2         | 0.6%    |
| P6               | 2         | 0.6%    |
| Bobcat           | 2         | 0.6%    |
| Tremont          | 1         | 0.3%    |
| K8 Hammer        | 1         | 0.3%    |
| K8 & K10 hybrid  | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 248       | 58.77%  |
| Nvidia | 87        | 20.62%  |
| AMD    | 87        | 20.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 32        | 7.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 28        | 6.35%   |
| Intel UHD Graphics 620                                                                | 16        | 3.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 14        | 3.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 11        | 2.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 10        | 2.27%   |
| Intel Core Processor Integrated Graphics Controller                                   | 10        | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 10        | 2.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 10        | 2.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 9         | 2.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 8         | 1.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 8         | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 8         | 1.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 1.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 1.59%   |
| Intel HD Graphics 630                                                                 | 7         | 1.59%   |
| Intel HD Graphics 620                                                                 | 7         | 1.59%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 6         | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 6         | 1.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 6         | 1.36%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 6         | 1.36%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 1.36%   |
| Intel HD Graphics 5500                                                                | 5         | 1.13%   |
| Intel HD Graphics 530                                                                 | 5         | 1.13%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 5         | 1.13%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 5         | 1.13%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 4         | 0.91%   |
| Nvidia C79 [GeForce 9400M]                                                            | 4         | 0.91%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 0.91%   |
| Intel HD Graphics 500                                                                 | 4         | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 0.91%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 4         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 3         | 0.68%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 3         | 0.68%   |
| Nvidia GK107M [GeForce GT 650M]                                                       | 3         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 162       | 48.8%   |
| Intel + Nvidia | 62        | 18.67%  |
| 1 x AMD        | 47        | 14.16%  |
| Intel + AMD    | 22        | 6.63%   |
| 1 x Nvidia     | 17        | 5.12%   |
| 2 x AMD        | 12        | 3.61%   |
| AMD + Nvidia   | 6         | 1.81%   |
| 2 x Nvidia     | 2         | 0.6%    |
| Other          | 1         | 0.3%    |
| 2 x Intel      | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 281       | 84.38%  |
| Proprietary | 44        | 13.21%  |
| Unknown     | 8         | 2.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 220       | 65.09%  |
| 0.01-0.5   | 35        | 10.36%  |
| 1.01-2.0   | 31        | 9.17%   |
| 0.51-1.0   | 24        | 7.1%    |
| 3.01-4.0   | 14        | 4.14%   |
| 5.01-6.0   | 6         | 1.78%   |
| 7.01-8.0   | 5         | 1.48%   |
| 2.01-3.0   | 2         | 0.59%   |
| 8.01-16.0  | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 65        | 16.67%  |
| LG Display              | 56        | 14.36%  |
| Chimei Innolux          | 52        | 13.33%  |
| Samsung Electronics     | 48        | 12.31%  |
| BOE                     | 33        | 8.46%   |
| Dell                    | 17        | 4.36%   |
| Chi Mei Optoelectronics | 16        | 4.1%    |
| Sharp                   | 15        | 3.85%   |
| Goldstar                | 14        | 3.59%   |
| AOC                     | 11        | 2.82%   |
| Apple                   | 8         | 2.05%   |
| InfoVision              | 6         | 1.54%   |
| Philips                 | 4         | 1.03%   |
| PANDA                   | 4         | 1.03%   |
| Lenovo                  | 4         | 1.03%   |
| ViewSonic               | 3         | 0.77%   |
| Sony                    | 3         | 0.77%   |
| Hewlett-Packard         | 3         | 0.77%   |
| Valve                   | 2         | 0.51%   |
| Quanta Display          | 2         | 0.51%   |
| Panasonic               | 2         | 0.51%   |
| InnoLux Display         | 2         | 0.51%   |
| HannStar                | 2         | 0.51%   |
| Denver                  | 2         | 0.51%   |
| Ancor Communications    | 2         | 0.51%   |
| Acer                    | 2         | 0.51%   |
| Wacom                   | 1         | 0.26%   |
| TMX                     | 1         | 0.26%   |
| SANYO                   | 1         | 0.26%   |
| PRISM+                  | 1         | 0.26%   |
| MiTAC                   | 1         | 0.26%   |
| Mi                      | 1         | 0.26%   |
| LG Philips              | 1         | 0.26%   |
| Kogan                   | 1         | 0.26%   |
| IBM                     | 1         | 0.26%   |
| HYD                     | 1         | 0.26%   |
| HKC                     | 1         | 0.26%   |
| CPT                     | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 6         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 1%      |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 1%      |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 3         | 0.75%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 3         | 0.75%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 3         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 3         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 3         | 0.75%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 0.75%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.75%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 2         | 0.5%    |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 2         | 0.5%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.5%    |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch        | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch     | 2         | 0.5%    |
| Panasonic TV MEIA0A6 1920x1080 698x392mm 31.5-inch                       | 2         | 0.5%    |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch              | 2         | 0.5%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.5%    |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.5%    |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 0.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.5%    |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 2         | 0.5%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 2         | 0.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.5%    |
| Goldstar 23EN43 GSM59DC 1920x1080 510x290mm 23.1-inch                    | 2         | 0.5%    |
| Dell U3818DW DELA0F3 3840x1600 880x367mm 37.5-inch                       | 2         | 0.5%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.5%    |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 2         | 0.5%    |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO41ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch            | 2         | 0.5%    |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                          | 2         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 144       | 39.02%  |
| 1366x768 (WXGA)    | 107       | 29%     |
| 1600x900 (HD+)     | 26        | 7.05%   |
| 2560x1440 (QHD)    | 15        | 4.07%   |
| 1280x800 (WXGA)    | 15        | 4.07%   |
| 3840x2160 (4K)     | 13        | 3.52%   |
| 3440x1440          | 8         | 2.17%   |
| 1920x1200 (WUXGA)  | 6         | 1.63%   |
| 1440x900 (WXGA+)   | 6         | 1.63%   |
| 3200x1800 (QHD+)   | 4         | 1.08%   |
| 2880x1800          | 4         | 1.08%   |
| 1280x1024 (SXGA)   | 3         | 0.81%   |
| 1024x600           | 3         | 0.81%   |
| 800x1280           | 2         | 0.54%   |
| 3840x1600          | 2         | 0.54%   |
| 3456x2160          | 2         | 0.54%   |
| 2560x1600          | 2         | 0.54%   |
| 1680x1050 (WSXGA+) | 2         | 0.54%   |
| 3840x2400          | 1         | 0.27%   |
| 2880x1920          | 1         | 0.27%   |
| 2560x1080          | 1         | 0.27%   |
| 1920x1280          | 1         | 0.27%   |
| 1360x768           | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 155       | 39.44%  |
| 13      | 50        | 12.72%  |
| 14      | 49        | 12.47%  |
| 17      | 31        | 7.89%   |
| 27      | 22        | 5.6%    |
| 23      | 12        | 3.05%   |
| 21      | 8         | 2.04%   |
| 24      | 7         | 1.78%   |
| 11      | 6         | 1.53%   |
| 34      | 5         | 1.27%   |
| 31      | 5         | 1.27%   |
| 12      | 5         | 1.27%   |
| 10      | 5         | 1.27%   |
| 16      | 4         | 1.02%   |
| 37      | 3         | 0.76%   |
| 20      | 3         | 0.76%   |
| 18      | 3         | 0.76%   |
| Unknown | 3         | 0.76%   |
| 72      | 2         | 0.51%   |
| 40      | 2         | 0.51%   |
| 35      | 2         | 0.51%   |
| 22      | 2         | 0.51%   |
| 19      | 2         | 0.51%   |
| 7       | 2         | 0.51%   |
| 84      | 1         | 0.25%   |
| 60      | 1         | 0.25%   |
| 33      | 1         | 0.25%   |
| 29      | 1         | 0.25%   |
| 25      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 234       | 60.15%  |
| 501-600     | 38        | 9.77%   |
| 201-300     | 36        | 9.25%   |
| 351-400     | 35        | 9%      |
| 401-500     | 16        | 4.11%   |
| 601-700     | 8         | 2.06%   |
| 801-900     | 7         | 1.8%    |
| 701-800     | 6         | 1.54%   |
| 1501-2000   | 3         | 0.77%   |
| Unknown     | 3         | 0.77%   |
| 1-100       | 2         | 0.51%   |
| 1001-1500   | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 278       | 82.49%  |
| 16/10   | 38        | 11.28%  |
| 21/9    | 11        | 3.26%   |
| 5/4     | 3         | 0.89%   |
| 3/2     | 3         | 0.89%   |
| 0.67    | 2         | 0.59%   |
| Unknown | 2         | 0.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 153       | 38.83%  |
| 81-90          | 82        | 20.81%  |
| 121-130        | 28        | 7.11%   |
| 201-250        | 26        | 6.6%    |
| 301-350        | 22        | 5.58%   |
| 71-80          | 17        | 4.31%   |
| 351-500        | 13        | 3.3%    |
| 151-200        | 8         | 2.03%   |
| 51-60          | 6         | 1.52%   |
| 61-70          | 5         | 1.27%   |
| 41-50          | 5         | 1.27%   |
| 111-120        | 5         | 1.27%   |
| 501-1000       | 5         | 1.27%   |
| More than 1000 | 4         | 1.02%   |
| 141-150        | 4         | 1.02%   |
| 251-300        | 3         | 0.76%   |
| Unknown        | 3         | 0.76%   |
| 1-40           | 2         | 0.51%   |
| 131-140        | 2         | 0.51%   |
| 91-100         | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 139       | 36.2%   |
| 121-160       | 134       | 34.9%   |
| 51-100        | 67        | 17.45%  |
| 161-240       | 23        | 5.99%   |
| More than 240 | 15        | 3.91%   |
| 1-50          | 3         | 0.78%   |
| Unknown       | 3         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 256       | 74.85%  |
| 2     | 65        | 19.01%  |
| 0     | 10        | 2.92%   |
| 3     | 9         | 2.63%   |
| 4     | 2         | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 197       | 37.38%  |
| Realtek Semiconductor             | 164       | 31.12%  |
| Qualcomm Atheros                  | 66        | 12.52%  |
| Broadcom                          | 33        | 6.26%   |
| MediaTek                          | 9         | 1.71%   |
| Ralink                            | 8         | 1.52%   |
| TP-Link                           | 6         | 1.14%   |
| Nvidia                            | 6         | 1.14%   |
| Hewlett-Packard                   | 6         | 1.14%   |
| Broadcom Limited                  | 6         | 1.14%   |
| DisplayLink                       | 4         | 0.76%   |
| Lenovo                            | 3         | 0.57%   |
| Sierra Wireless                   | 2         | 0.38%   |
| Marvell Technology Group          | 2         | 0.38%   |
| JMicron Technology                | 2         | 0.38%   |
| Dell                              | 2         | 0.38%   |
| STMicroelectronics                | 1         | 0.19%   |
| Samsung Electronics               | 1         | 0.19%   |
| Qualcomm                          | 1         | 0.19%   |
| OPPO Electronics                  | 1         | 0.19%   |
| NetGear                           | 1         | 0.19%   |
| Lite-On Technology                | 1         | 0.19%   |
| ICS Advent                        | 1         | 0.19%   |
| Espressi                          | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| Attansic Technology               | 1         | 0.19%   |
| ASIX Electronics                  | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 96        | 14.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 4.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 3.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 2.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 17        | 2.63%   |
| Intel Wireless 8265 / 8275                                        | 16        | 2.48%   |
| Intel Wireless 7260                                               | 15        | 2.32%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 2.17%   |
| Intel Wireless 8260                                               | 13        | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 1.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.24%   |
| Intel Wireless 3165                                               | 8         | 1.24%   |
| Intel Centrino Ultimate-N 6300                                    | 8         | 1.24%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 1.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 1.24%   |
| Intel Wireless 7265                                               | 7         | 1.08%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.08%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.93%   |
| Intel Centrino Wireless-N 2230                                    | 6         | 0.93%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 6         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.77%   |
| Nvidia MCP79 Ethernet                                             | 5         | 0.77%   |
| Intel WiFi Link 5100                                              | 5         | 0.77%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.77%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.77%   |
| Intel 82577LC Gigabit Network Connection                          | 5         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 189       | 54.47%  |
| Qualcomm Atheros      | 59        | 17%     |
| Realtek Semiconductor | 35        | 10.09%  |
| Broadcom              | 26        | 7.49%   |
| MediaTek              | 9         | 2.59%   |
| Ralink                | 8         | 2.31%   |
| TP-Link               | 6         | 1.73%   |
| Broadcom Limited      | 6         | 1.73%   |
| Hewlett-Packard       | 3         | 0.86%   |
| Dell                  | 2         | 0.58%   |
| Sierra Wireless       | 1         | 0.29%   |
| Qualcomm              | 1         | 0.29%   |
| NetGear               | 1         | 0.29%   |
| Lite-On Technology    | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 17        | 4.89%   |
| Intel Wireless 8265 / 8275                                     | 16        | 4.6%    |
| Intel Wireless 7260                                            | 15        | 4.31%   |
| Intel Wi-Fi 6 AX200                                            | 14        | 4.02%   |
| Intel Wireless 8260                                            | 13        | 3.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 3.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 3.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 3.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 2.87%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 2.3%    |
| Intel Wireless 3165                                            | 8         | 2.3%    |
| Intel Centrino Ultimate-N 6300                                 | 8         | 2.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 2.3%    |
| Intel Wireless 7265                                            | 7         | 2.01%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.72%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 1.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 6         | 1.72%   |
| Intel WiFi Link 5100                                           | 5         | 1.44%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.44%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 4         | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 1.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.86%   |
| Intel Wireless-AC 9260                                         | 3         | 0.86%   |
| Intel Wireless 3160                                            | 3         | 0.86%   |
| HP lt4112 Gobi 4G Module Network Device                        | 3         | 0.86%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.86%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 2         | 0.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 152       | 52.6%   |
| Intel                    | 86        | 29.76%  |
| Qualcomm Atheros         | 18        | 6.23%   |
| Broadcom                 | 10        | 3.46%   |
| Nvidia                   | 6         | 2.08%   |
| DisplayLink              | 4         | 1.38%   |
| Lenovo                   | 3         | 1.04%   |
| Marvell Technology Group | 2         | 0.69%   |
| JMicron Technology       | 2         | 0.69%   |
| Sierra Wireless          | 1         | 0.35%   |
| Samsung Electronics      | 1         | 0.35%   |
| OPPO Electronics         | 1         | 0.35%   |
| ICS Advent               | 1         | 0.35%   |
| Attansic Technology      | 1         | 0.35%   |
| ASIX Electronics         | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 96        | 32.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 8.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 7.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 6.19%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 2.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.72%   |
| Nvidia MCP79 Ethernet                                             | 5         | 1.72%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.72%   |
| Intel 82577LC Gigabit Network Connection                          | 5         | 1.72%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.72%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.03%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 1.03%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.03%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.03%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.69%   |
| Realtek PCIe GbE Family Controller                                | 2         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.69%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.69%   |
| Intel Killer E3100 2.5 Gigabit Ethernet Controller                | 2         | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.69%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.69%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 0.69%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.69%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.34%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 328       | 53.68%  |
| Ethernet | 276       | 45.17%  |
| Modem    | 7         | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 289       | 79.18%  |
| Ethernet | 76        | 20.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 249       | 75%     |
| 1     | 78        | 23.49%  |
| 3     | 3         | 0.9%    |
| 0     | 2         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 290       | 86.31%  |
| Yes  | 46        | 13.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 140       | 51.66%  |
| Qualcomm Atheros Communications | 24        | 8.86%   |
| Realtek Semiconductor           | 14        | 5.17%   |
| Lite-On Technology              | 14        | 5.17%   |
| IMC Networks                    | 14        | 5.17%   |
| Broadcom                        | 14        | 5.17%   |
| Foxconn / Hon Hai               | 13        | 4.8%    |
| Hewlett-Packard                 | 12        | 4.43%   |
| Apple                           | 8         | 2.95%   |
| Toshiba                         | 4         | 1.48%   |
| Ralink Technology               | 3         | 1.11%   |
| Dell                            | 3         | 1.11%   |
| Ralink                          | 2         | 0.74%   |
| ASUSTek Computer                | 2         | 0.74%   |
| Alps Electric                   | 2         | 0.74%   |
| Realtek                         | 1         | 0.37%   |
| Edimax Technology               | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 57        | 21.03%  |
| Intel AX201 Bluetooth                            | 24        | 8.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 16        | 5.9%    |
| Qualcomm Atheros  Bluetooth Device               | 15        | 5.54%   |
| Intel AX200 Bluetooth                            | 14        | 5.17%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 12        | 4.43%   |
| Realtek Bluetooth Radio                          | 8         | 2.95%   |
| HP Broadcom 2070 Bluetooth Combo                 | 8         | 2.95%   |
| IMC Networks Wireless_Device                     | 7         | 2.58%   |
| Realtek  Bluetooth 4.2 Adapter                   | 6         | 2.21%   |
| Intel Bluetooth Device                           | 6         | 2.21%   |
| Apple Bluetooth Host Controller                  | 6         | 2.21%   |
| Lite-On Atheros AR3012 Bluetooth                 | 5         | 1.85%   |
| IMC Networks Bluetooth Radio                     | 5         | 1.85%   |
| Foxconn / Hon Hai Bluetooth Device               | 5         | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 4         | 1.48%   |
| Lite-On Bluetooth Device                         | 4         | 1.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 4         | 1.48%   |
| Qualcomm Atheros AR3011 Bluetooth                | 3         | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 3         | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 3         | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                 | 3         | 1.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 3         | 1.11%   |
| Foxconn / Hon Hai Acer Module                    | 3         | 1.11%   |
| Broadcom HP Portable SoftSailing                 | 3         | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                      | 3         | 1.11%   |
| Toshiba Bluetooth Radio                          | 2         | 0.74%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter     | 2         | 0.74%   |
| Ralink RT3290 Bluetooth                          | 2         | 0.74%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 2         | 0.74%   |
| Broadcom BCM20702A0                              | 2         | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 2         | 0.74%   |
| Alps Electric BCM2046 Bluetooth Device           | 2         | 0.74%   |
| Toshiba BRCM Bluetooth Controller BCM2070        | 1         | 0.37%   |
| Toshiba Bluetooth USB Host Controller            | 1         | 0.37%   |
| Realtek 802.11ac WLAN Adapter                    | 1         | 0.37%   |
| Ralink CSR BS8510                                | 1         | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 0.37%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 0.37%   |
| Lite-On Wireless_Device                          | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 276       | 64.19%  |
| AMD                      | 66        | 15.35%  |
| Nvidia                   | 54        | 12.56%  |
| Hewlett-Packard          | 7         | 1.63%   |
| Realtek Semiconductor    | 5         | 1.16%   |
| Logitech                 | 4         | 0.93%   |
| Lenovo                   | 3         | 0.7%    |
| Plantronics              | 2         | 0.47%   |
| Generalplus Technology   | 2         | 0.47%   |
| Texas Instruments        | 1         | 0.23%   |
| SteelSeries ApS          | 1         | 0.23%   |
| Micro Star International | 1         | 0.23%   |
| Harman                   | 1         | 0.23%   |
| GYROCOM C&C              | 1         | 0.23%   |
| Google                   | 1         | 0.23%   |
| DSEA A/S                 | 1         | 0.23%   |
| CMX Systems              | 1         | 0.23%   |
| ClearOne Communications  | 1         | 0.23%   |
| Belkin Components        | 1         | 0.23%   |
| AST Research             | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 40        | 7.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 39        | 7.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 31        | 6.19%   |
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 4.59%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 2.99%   |
| AMD FCH Azalia Controller                                                  | 15        | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 2.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 2.59%   |
| AMD Kabini HDMI/DP Audio                                                   | 13        | 2.59%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 2.2%    |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.2%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 2.2%    |
| Intel 8 Series HD Audio Controller                                         | 11        | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 2%      |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 1.6%    |
| Intel CM238 HD Audio Controller                                            | 8         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 1.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.4%    |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.4%    |
| Hewlett-Packard USB Audio                                                  | 7         | 1.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 7         | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.2%    |
| AMD High Definition Audio Controller                                       | 6         | 1.2%    |
| Realtek Semiconductor USB Audio                                            | 5         | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1%      |
| Nvidia MCP79 High Definition Audio                                         | 5         | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1%      |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5         | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.8%    |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 29.17%  |
| SK hynix            | 56        | 25.93%  |
| Micron Technology   | 35        | 16.2%   |
| Kingston            | 16        | 7.41%   |
| Crucial             | 16        | 7.41%   |
| Unknown             | 6         | 2.78%   |
| A-DATA Technology   | 5         | 2.31%   |
| Elpida              | 4         | 1.85%   |
| Team                | 2         | 0.93%   |
| Strontium           | 2         | 0.93%   |
| Shenzhen Mic        | 2         | 0.93%   |
| Ramaxel Technology  | 2         | 0.93%   |
| Unknown (ABCD)      | 1         | 0.46%   |
| Transcend           | 1         | 0.46%   |
| Neo Forza           | 1         | 0.46%   |
| Nanya Technology    | 1         | 0.46%   |
| fef5                | 1         | 0.46%   |
| Corsair             | 1         | 0.46%   |
| Apacer              | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 6         | 2.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 2.2%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s       | 4         | 1.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 4         | 1.76%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 4         | 1.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 4         | 1.76%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                 | 3         | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 3         | 1.32%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                  | 3         | 1.32%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.32%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s        | 3         | 1.32%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s      | 3         | 1.32%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s       | 3         | 1.32%   |
| Unknown RAM Module 4096MB SODIMM DDR3                         | 2         | 0.88%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s         | 2         | 0.88%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s          | 2         | 0.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 0.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s        | 2         | 0.88%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s   | 2         | 0.88%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                  | 2         | 0.88%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 2         | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 0.88%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 0.88%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 2         | 0.88%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s     | 2         | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 2         | 0.88%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 0.88%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.88%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 2         | 0.88%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 2         | 0.88%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s        | 2         | 0.88%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s         | 2         | 0.88%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s        | 2         | 0.88%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM 1334MT/s              | 2         | 0.88%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 2         | 0.88%   |
| Unknown RAM Module 8192MB SODIMM DDR3                         | 1         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3                            | 1         | 0.44%   |
| Unknown RAM Module 4GB SODIMM 1067MT/s                        | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 42.86%  |
| DDR3    | 65        | 37.14%  |
| DDR2    | 8         | 4.57%   |
| LPDDR3  | 7         | 4%      |
| SDRAM   | 6         | 3.43%   |
| DDR5    | 6         | 3.43%   |
| LPDDR4  | 5         | 2.86%   |
| Unknown | 2         | 1.14%   |
| LPDDR5  | 1         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 91.38%  |
| Row Of Chips | 9         | 5.17%   |
| Chip         | 3         | 1.72%   |
| Unknown      | 3         | 1.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 65        | 35.71%  |
| 4096  | 54        | 29.67%  |
| 16384 | 33        | 18.13%  |
| 2048  | 23        | 12.64%  |
| 32768 | 6         | 3.3%    |
| 1024  | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 44        | 23.4%   |
| 3200    | 34        | 18.09%  |
| 2667    | 25        | 13.3%   |
| 1334    | 14        | 7.45%   |
| 2400    | 13        | 6.91%   |
| 2133    | 9         | 4.79%   |
| 1333    | 7         | 3.72%   |
| 1067    | 7         | 3.72%   |
| 4800    | 6         | 3.19%   |
| 667     | 5         | 2.66%   |
| 1867    | 4         | 2.13%   |
| Unknown | 4         | 2.13%   |
| 8400    | 3         | 1.6%    |
| 4199    | 3         | 1.6%    |
| 3733    | 2         | 1.06%   |
| 2048    | 2         | 1.06%   |
| 975     | 2         | 1.06%   |
| 800     | 2         | 1.06%   |
| 6400    | 1         | 0.53%   |
| 4267    | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 50%     |
| HP DeskJet 2300 series        | 1         | 50%     |

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


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 86        | 29.05%  |
| IMC Networks                           | 28        | 9.46%   |
| Microdia                               | 24        | 8.11%   |
| Sunplus Innovation Technology          | 22        | 7.43%   |
| Realtek Semiconductor                  | 20        | 6.76%   |
| Quanta                                 | 15        | 5.07%   |
| Acer                                   | 12        | 4.05%   |
| Suyin                                  | 11        | 3.72%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.72%   |
| Lite-On Technology                     | 10        | 3.38%   |
| Bison Electronics                      | 8         | 2.7%    |
| Apple                                  | 7         | 2.36%   |
| Luxvisions Innotech Limited            | 6         | 2.03%   |
| Logitech                               | 6         | 2.03%   |
| Syntek                                 | 4         | 1.35%   |
| Ricoh                                  | 4         | 1.35%   |
| Primax Electronics                     | 4         | 1.35%   |
| Alcor Micro                            | 4         | 1.35%   |
| Silicon Motion                         | 3         | 1.01%   |
| Samsung Electronics                    | 2         | 0.68%   |
| Importek                               | 2         | 0.68%   |
| Z-Star Microelectronics                | 1         | 0.34%   |
| Yealink Network Technology             | 1         | 0.34%   |
| Sonix Technology                       | 1         | 0.34%   |
| Intel                                  | 1         | 0.34%   |
| DigiTech                               | 1         | 0.34%   |
| AVer Information                       | 1         | 0.34%   |
| ALi                                    | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony integrated camera                | 15        | 5.05%   |
| IMC Networks USB2.0 HD UVC WebCam        | 14        | 4.71%   |
| Chicony HP HD Camera                     | 11        | 3.7%    |
| Chicony HD WebCam                        | 9         | 3.03%   |
| Realtek Integrated_Webcam_HD             | 8         | 2.69%   |
| Sunplus HP HD Webcam [Fixed]             | 7         | 2.36%   |
| IMC Networks Integrated Camera           | 7         | 2.36%   |
| Sunplus Integrated_Webcam_HD             | 6         | 2.02%   |
| Microdia Integrated_Webcam_HD            | 6         | 2.02%   |
| Microdia Integrated Webcam HD            | 6         | 2.02%   |
| Chicony HP HD Webcam                     | 6         | 2.02%   |
| Acer Integrated Camera                   | 6         | 2.02%   |
| Chicony TOSHIBA Web Camera - HD          | 5         | 1.68%   |
| Apple Built-in iSight                    | 5         | 1.68%   |
| Realtek HP Truevision HD                 | 4         | 1.35%   |
| Quanta HP TrueVision HD Camera           | 4         | 1.35%   |
| Sunplus HD WebCam                        | 3         | 1.01%   |
| Quanta HP HD Camera                      | 3         | 1.01%   |
| Luxvisions Innotech Limited HP HD Camera | 3         | 1.01%   |
| Lite-On Integrated Camera                | 3         | 1.01%   |
| Lite-On HP HD Camera                     | 3         | 1.01%   |
| Chicony VGA Webcam                       | 3         | 1.01%   |
| Chicony USB2.0 Camera                    | 3         | 1.01%   |
| Chicony Integrated HP HD Webcam          | 3         | 1.01%   |
| Chicony HP Wide Vision HD Camera         | 3         | 1.01%   |
| Bison SunplusIT Integrated Camera        | 3         | 1.01%   |
| Syntek EasyCamera                        | 2         | 0.67%   |
| Suyin HP Webcam                          | 2         | 0.67%   |
| Suyin HP TrueVision HD Integrated Webcam | 2         | 0.67%   |
| Suyin HP Truevision HD                   | 2         | 0.67%   |
| Suyin 1.3M HD WebCam                     | 2         | 0.67%   |
| Sunplus ASUS Webcam                      | 2         | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)  | 2         | 0.67%   |
| Realtek Integrated Webcam_HD             | 2         | 0.67%   |
| Quanta Laptop_Integrated_Webcam_2HDM     | 2         | 0.67%   |
| Primax Villem                            | 2         | 0.67%   |
| Primax HP HD Webcam [Fixed]              | 2         | 0.67%   |
| Microdia Laptop_Integrated_Webcam_1.3M   | 2         | 0.67%   |
| Logitech HD Webcam C510                  | 2         | 0.67%   |
| Chicony USB2.0 0.3M UVC WebCam           | 2         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 48        | 52.17%  |
| Synaptics                  | 23        | 25%     |
| Shenzhen Goodix Technology | 5         | 5.43%   |
| AuthenTec                  | 5         | 5.43%   |
| Upek                       | 4         | 4.35%   |
| Elan Microelectronics      | 4         | 4.35%   |
| LighTuning Technology      | 2         | 2.17%   |
| STMicroelectronics         | 1         | 1.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 13.04%  |
| Validity Sensors VFS491                                                    | 7         | 7.61%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 6.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 5.43%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 5.43%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 4.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 4.35%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 4.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 4.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.26%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 3.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.26%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 3.26%   |
| Elan ELAN:Fingerprint                                                      | 3         | 3.26%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 2.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.17%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.17%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.17%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 2.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.17%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.17%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.09%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.09%   |
| AuthenTec AES2810                                                          | 1         | 1.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.09%   |
| AuthenTec AES1600                                                          | 1         | 1.09%   |
| Unknown                                                                    | 1         | 1.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 14        | 63.64%  |
| Lenovo      | 3         | 13.64%  |
| Alcor Micro | 3         | 13.64%  |
| Upek        | 1         | 4.55%   |
| O2 Micro    | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 7         | 31.82%  |
| Broadcom 58200                                             | 4         | 18.18%  |
| Lenovo Integrated Smart Card Reader                        | 3         | 13.64%  |
| Broadcom 5880                                              | 3         | 13.64%  |
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 13.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 189       | 55.26%  |
| 1     | 121       | 35.38%  |
| 2     | 27        | 7.89%   |
| 6     | 2         | 0.58%   |
| 3     | 2         | 0.58%   |
| 5     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 90        | 47.37%  |
| Graphics card            | 29        | 15.26%  |
| Net/wireless             | 20        | 10.53%  |
| Chipcard                 | 20        | 10.53%  |
| Multimedia controller    | 9         | 4.74%   |
| Net/ethernet             | 4         | 2.11%   |
| Camera                   | 4         | 2.11%   |
| Communication controller | 3         | 1.58%   |
| Bluetooth                | 3         | 1.58%   |
| Sound                    | 2         | 1.05%   |
| Card reader              | 2         | 1.05%   |
| Storage                  | 1         | 0.53%   |
| Network                  | 1         | 0.53%   |
| Modem                    | 1         | 0.53%   |
| Flash memory             | 1         | 0.53%   |


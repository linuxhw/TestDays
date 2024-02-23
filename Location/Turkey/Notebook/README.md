Linux in Turkey - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Turkey.

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

Total: 2182

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Nitro AN515-58              | [1fe97c9103](https://linux-hardware.org/?probe=1fe97c9103) | Feb 02, 2024 |
| Toshiba       | Satellite L750              | [a1e1f9075d](https://linux-hardware.org/?probe=a1e1f9075d) | Feb 01, 2024 |
| HP            | Pavilion g6                 | [acd0ae9c04](https://linux-hardware.org/?probe=acd0ae9c04) | Jan 31, 2024 |
| Valve         | Jupiter                     | [574ab05eb4](https://linux-hardware.org/?probe=574ab05eb4) | Jan 31, 2024 |
| Dell          | Inspiron 1520               | [371f061c1d](https://linux-hardware.org/?probe=371f061c1d) | Jan 31, 2024 |
| ARCELIK       | GNB 1150 B1 N2 V1.0         | [eb35406b7e](https://linux-hardware.org/?probe=eb35406b7e) | Jan 29, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [765673ce15](https://linux-hardware.org/?probe=765673ce15) | Jan 27, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [1f1d3ff8f9](https://linux-hardware.org/?probe=1f1d3ff8f9) | Jan 27, 2024 |
| ASUSTek       | K52JT                       | [dd44051584](https://linux-hardware.org/?probe=dd44051584) | Jan 27, 2024 |
| Monster       | ABRA A7 V13.3               | [08516ca0c2](https://linux-hardware.org/?probe=08516ca0c2) | Jan 26, 2024 |
| HP            | Victus by Gaming Laptop ... | [9a3ff54cf8](https://linux-hardware.org/?probe=9a3ff54cf8) | Jan 26, 2024 |
| Toshiba       | Satellite P50T-A-114        | [5286decec5](https://linux-hardware.org/?probe=5286decec5) | Jan 26, 2024 |
| Lenovo        | Unknown                     | [ae59a4d618](https://linux-hardware.org/?probe=ae59a4d618) | Jan 25, 2024 |
| HP            | OMEN by Laptop 15-ce0xx     | [90a5837b3c](https://linux-hardware.org/?probe=90a5837b3c) | Jan 24, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [cf3c2deee4](https://linux-hardware.org/?probe=cf3c2deee4) | Jan 23, 2024 |
| Dell          | Latitude 5480               | [45ac237d79](https://linux-hardware.org/?probe=45ac237d79) | Jan 23, 2024 |
| Acer          | Predator PH315-53           | [74ca3f63e2](https://linux-hardware.org/?probe=74ca3f63e2) | Jan 22, 2024 |
| HP            | ProBook 450 G5              | [ea8cc27b1a](https://linux-hardware.org/?probe=ea8cc27b1a) | Jan 21, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [97e1f1353f](https://linux-hardware.org/?probe=97e1f1353f) | Jan 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [73fe1f94d6](https://linux-hardware.org/?probe=73fe1f94d6) | Jan 20, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [c765a21a05](https://linux-hardware.org/?probe=c765a21a05) | Jan 18, 2024 |
| AZW           | SEi                         | [b144837b91](https://linux-hardware.org/?probe=b144837b91) | Jan 18, 2024 |
| Acer          | Aspire A315-57G             | [8c8ccb9324](https://linux-hardware.org/?probe=8c8ccb9324) | Jan 17, 2024 |
| Acer          | Aspire A315-57G             | [f7eb7dc2e9](https://linux-hardware.org/?probe=f7eb7dc2e9) | Jan 17, 2024 |
| Monster       | ABRA A5 V16.6               | [181ed8314a](https://linux-hardware.org/?probe=181ed8314a) | Jan 17, 2024 |
| HP            | Victus by Gaming Laptop ... | [e6e63ec982](https://linux-hardware.org/?probe=e6e63ec982) | Jan 17, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [d2b4053179](https://linux-hardware.org/?probe=d2b4053179) | Jan 16, 2024 |
| Lenovo        | ThinkPad T490 20N3S3XR00    | [63ec999c70](https://linux-hardware.org/?probe=63ec999c70) | Jan 16, 2024 |
| HP            | Laptop 15-da1xxx            | [cd726b3a5a](https://linux-hardware.org/?probe=cd726b3a5a) | Jan 15, 2024 |
| Casper        | EXCALIBUR G900              | [8531ff6e44](https://linux-hardware.org/?probe=8531ff6e44) | Jan 15, 2024 |
| Casper        | EXCALIBUR G900              | [efb49fa361](https://linux-hardware.org/?probe=efb49fa361) | Jan 15, 2024 |
| AZW           | SEi                         | [b8f32bfbbc](https://linux-hardware.org/?probe=b8f32bfbbc) | Jan 14, 2024 |
| HONOR         | BMH-WCX9                    | [11d4c3f75d](https://linux-hardware.org/?probe=11d4c3f75d) | Jan 14, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [569afd2c6a](https://linux-hardware.org/?probe=569afd2c6a) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [53a45b597e](https://linux-hardware.org/?probe=53a45b597e) | Jan 13, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [a3e108e50d](https://linux-hardware.org/?probe=a3e108e50d) | Jan 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [f35fb9dd1c](https://linux-hardware.org/?probe=f35fb9dd1c) | Jan 13, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [df073dcede](https://linux-hardware.org/?probe=df073dcede) | Jan 12, 2024 |
| HP            | Victus by Gaming Laptop ... | [1bad1acfa2](https://linux-hardware.org/?probe=1bad1acfa2) | Jan 11, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [513efe6ed6](https://linux-hardware.org/?probe=513efe6ed6) | Jan 09, 2024 |
| Acer          | Extensa 215-54G             | [3c25dd10dd](https://linux-hardware.org/?probe=3c25dd10dd) | Jan 06, 2024 |
| Acer          | Aspire A715-43G             | [023677517d](https://linux-hardware.org/?probe=023677517d) | Jan 06, 2024 |
| Acer          | Extensa 215-54G             | [031b668bcb](https://linux-hardware.org/?probe=031b668bcb) | Jan 06, 2024 |
| ASUSTek       | P553UJ                      | [6e0de808da](https://linux-hardware.org/?probe=6e0de808da) | Jan 05, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [de57acd268](https://linux-hardware.org/?probe=de57acd268) | Jan 03, 2024 |
| Apple         | MacBook5,1                  | [2c8c483194](https://linux-hardware.org/?probe=2c8c483194) | Jan 03, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [68e2ccb6e6](https://linux-hardware.org/?probe=68e2ccb6e6) | Jan 03, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [934f756965](https://linux-hardware.org/?probe=934f756965) | Dec 31, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [76869cc8d4](https://linux-hardware.org/?probe=76869cc8d4) | Dec 31, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [ff8e890649](https://linux-hardware.org/?probe=ff8e890649) | Dec 30, 2023 |
| Dell          | Inspiron 3542               | [06e3a35d05](https://linux-hardware.org/?probe=06e3a35d05) | Dec 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | [0f8be1187e](https://linux-hardware.org/?probe=0f8be1187e) | Dec 28, 2023 |
| Packard Be... | EasyNote MH35               | [2b8b39d335](https://linux-hardware.org/?probe=2b8b39d335) | Dec 27, 2023 |
| ASUSTek       | GL753VD                     | [73bbd42b1f](https://linux-hardware.org/?probe=73bbd42b1f) | Dec 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S24N3J    | [b6b0c2c889](https://linux-hardware.org/?probe=b6b0c2c889) | Dec 27, 2023 |
| Lenovo        | B51-35 80LH                 | [85a89b00af](https://linux-hardware.org/?probe=85a89b00af) | Dec 26, 2023 |
| HUAWEI        | BoDE-WXX9                   | [a8acfd11f6](https://linux-hardware.org/?probe=a8acfd11f6) | Dec 25, 2023 |
| Lenovo        | G50-70 20351                | [3ac6a566ab](https://linux-hardware.org/?probe=3ac6a566ab) | Dec 24, 2023 |
| Lenovo        | G50-70 20351                | [dc269fb33a](https://linux-hardware.org/?probe=dc269fb33a) | Dec 24, 2023 |
| Acer          | Nitro AN515-43              | [b1342e1524](https://linux-hardware.org/?probe=b1342e1524) | Dec 23, 2023 |
| MSI           | Creator 15M A10SD           | [5ed074ddfb](https://linux-hardware.org/?probe=5ed074ddfb) | Dec 19, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [3a2290dbe0](https://linux-hardware.org/?probe=3a2290dbe0) | Dec 16, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [a2a4eb520c](https://linux-hardware.org/?probe=a2a4eb520c) | Dec 16, 2023 |
| Acer          | Aspire A315-58              | [15c3d23fc9](https://linux-hardware.org/?probe=15c3d23fc9) | Dec 15, 2023 |
| Apple         | MacBookPro8,1               | [d32726759c](https://linux-hardware.org/?probe=d32726759c) | Dec 15, 2023 |
| Dell          | Precision 7560              | [0f83098df3](https://linux-hardware.org/?probe=0f83098df3) | Dec 15, 2023 |
| Acer          | Aspire A315-58              | [0b19e954c5](https://linux-hardware.org/?probe=0b19e954c5) | Dec 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [cc4a45597c](https://linux-hardware.org/?probe=cc4a45597c) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [ef4cd6f316](https://linux-hardware.org/?probe=ef4cd6f316) | Dec 12, 2023 |
| Acer          | Nitro AN515-58              | [16bb3367f0](https://linux-hardware.org/?probe=16bb3367f0) | Dec 11, 2023 |
| Casper        | *SP*                        | [5fb7fac59d](https://linux-hardware.org/?probe=5fb7fac59d) | Dec 10, 2023 |
| Casper        | *SP*                        | [5a1d880754](https://linux-hardware.org/?probe=5a1d880754) | Dec 10, 2023 |
| HP            | Notebook                    | [19c87ca6c5](https://linux-hardware.org/?probe=19c87ca6c5) | Dec 10, 2023 |
| Lenovo        | G50-70 20351                | [fab1403ca7](https://linux-hardware.org/?probe=fab1403ca7) | Dec 10, 2023 |
| HUAWEI        | HN-WX9X                     | [d9d22e25cb](https://linux-hardware.org/?probe=d9d22e25cb) | Dec 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [1435c0e9db](https://linux-hardware.org/?probe=1435c0e9db) | Dec 09, 2023 |
| HP            | Pavilion Gaming Notebook    | [7824421836](https://linux-hardware.org/?probe=7824421836) | Dec 08, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [b21bc9aa81](https://linux-hardware.org/?probe=b21bc9aa81) | Dec 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c6f72287f3](https://linux-hardware.org/?probe=c6f72287f3) | Dec 07, 2023 |
| Toshiba       | Satellite C55D-C            | [888584071d](https://linux-hardware.org/?probe=888584071d) | Dec 05, 2023 |
| ASUSTek       | P553UJ                      | [e5ed994bf9](https://linux-hardware.org/?probe=e5ed994bf9) | Dec 05, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [b8a831d450](https://linux-hardware.org/?probe=b8a831d450) | Dec 04, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [6c7f7fe382](https://linux-hardware.org/?probe=6c7f7fe382) | Dec 04, 2023 |
| Monster       | TULPAR T7 V20.2             | [1d83d3589e](https://linux-hardware.org/?probe=1d83d3589e) | Dec 03, 2023 |
| Monster       | TULPAR T7 V21.8             | [0f6162aabe](https://linux-hardware.org/?probe=0f6162aabe) | Dec 02, 2023 |
| Sony          | VPCF11M1E                   | [f185cc14da](https://linux-hardware.org/?probe=f185cc14da) | Dec 01, 2023 |
| Casper        | EXCALIBUR G770              | [f5e978e47d](https://linux-hardware.org/?probe=f5e978e47d) | Dec 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [8524905e3f](https://linux-hardware.org/?probe=8524905e3f) | Nov 30, 2023 |
| Toshiba       | Satellite L850D-131         | [483c7cfdf6](https://linux-hardware.org/?probe=483c7cfdf6) | Nov 30, 2023 |
| Dell          | Precision M6800             | [0112706077](https://linux-hardware.org/?probe=0112706077) | Nov 29, 2023 |
| Acer          | Aspire E5-521G              | [d639f77bd9](https://linux-hardware.org/?probe=d639f77bd9) | Nov 28, 2023 |
| Acer          | Aspire A315-42G             | [bd498a1e04](https://linux-hardware.org/?probe=bd498a1e04) | Nov 27, 2023 |
| Acer          | Aspire A315-42G             | [e86c1bf644](https://linux-hardware.org/?probe=e86c1bf644) | Nov 27, 2023 |
| ASUSTek       | X550ZE                      | [d597be352c](https://linux-hardware.org/?probe=d597be352c) | Nov 27, 2023 |
| ASUSTek       | X550ZE                      | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| HP            | Pavilion 13 x360 PC         | [088789a558](https://linux-hardware.org/?probe=088789a558) | Nov 27, 2023 |
| HP            | Pavilion 13 x360 PC         | [fa45cae3d1](https://linux-hardware.org/?probe=fa45cae3d1) | Nov 27, 2023 |
| Lenovo        | V340-17IWL 81RG             | [c2a7190ba8](https://linux-hardware.org/?probe=c2a7190ba8) | Nov 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [ce68d047a6](https://linux-hardware.org/?probe=ce68d047a6) | Nov 26, 2023 |
| HUAWEI        | HVY-WXX9                    | [c686cc4ca0](https://linux-hardware.org/?probe=c686cc4ca0) | Nov 26, 2023 |
| HUAWEI        | HVY-WXX9                    | [fbec470224](https://linux-hardware.org/?probe=fbec470224) | Nov 26, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [1e4a3ed089](https://linux-hardware.org/?probe=1e4a3ed089) | Nov 25, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [a2fbff15e7](https://linux-hardware.org/?probe=a2fbff15e7) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | [7c92224aed](https://linux-hardware.org/?probe=7c92224aed) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | [57a3d9064a](https://linux-hardware.org/?probe=57a3d9064a) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | [a4c63ff9b4](https://linux-hardware.org/?probe=a4c63ff9b4) | Nov 25, 2023 |
| Acer          | Aspire A515-47              | [6e47e7fce4](https://linux-hardware.org/?probe=6e47e7fce4) | Nov 24, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [2127112b3a](https://linux-hardware.org/?probe=2127112b3a) | Nov 23, 2023 |
| Toshiba       | Satellite L850D-131         | [8810505a5a](https://linux-hardware.org/?probe=8810505a5a) | Nov 23, 2023 |
| Acer          | Aspire A515-45G             | [1ec9d0635f](https://linux-hardware.org/?probe=1ec9d0635f) | Nov 23, 2023 |
| Dell          | Vostro 15 5501              | [ebb962a4ff](https://linux-hardware.org/?probe=ebb962a4ff) | Nov 21, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [b528cb2139](https://linux-hardware.org/?probe=b528cb2139) | Nov 19, 2023 |
| ASUSTek       | TP500LB                     | [697dfb4387](https://linux-hardware.org/?probe=697dfb4387) | Nov 19, 2023 |
| ASUSTek       | X553MA                      | [1ee7faaeb4](https://linux-hardware.org/?probe=1ee7faaeb4) | Nov 18, 2023 |
| Monster       | ABRA A5 V17.2               | [130ef88703](https://linux-hardware.org/?probe=130ef88703) | Nov 17, 2023 |
| Monster       | ABRA A5 V17.2               | [76653a926b](https://linux-hardware.org/?probe=76653a926b) | Nov 17, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | [be914025c2](https://linux-hardware.org/?probe=be914025c2) | Nov 17, 2023 |
| HUAWEI        | HBB-WX9                     | [d3d635372e](https://linux-hardware.org/?probe=d3d635372e) | Nov 15, 2023 |
| Monster       | ABRA A5 V17.4               | [2645ae8296](https://linux-hardware.org/?probe=2645ae8296) | Nov 15, 2023 |
| Acer          | Aspire A715-43G             | [e0e5d2b93e](https://linux-hardware.org/?probe=e0e5d2b93e) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [392c269f06](https://linux-hardware.org/?probe=392c269f06) | Nov 14, 2023 |
| Dell          | G5 5505                     | [be553804bd](https://linux-hardware.org/?probe=be553804bd) | Nov 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [c7be71a544](https://linux-hardware.org/?probe=c7be71a544) | Nov 13, 2023 |
| Dell          | G5 5505                     | [574ccd4e6f](https://linux-hardware.org/?probe=574ccd4e6f) | Nov 13, 2023 |
| HUAWEI        | RLEF-XX                     | [5a7374e5b0](https://linux-hardware.org/?probe=5a7374e5b0) | Nov 13, 2023 |
| Google        | Hanawl                      | [39b8f28b8e](https://linux-hardware.org/?probe=39b8f28b8e) | Nov 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [3172a3c77c](https://linux-hardware.org/?probe=3172a3c77c) | Nov 12, 2023 |
| Google        | Hana                        | [80ae861cdf](https://linux-hardware.org/?probe=80ae861cdf) | Nov 12, 2023 |
| Acer          | Aspire E5-573               | [c1b89d8187](https://linux-hardware.org/?probe=c1b89d8187) | Nov 12, 2023 |
| HUAWEI        | RLEFG-XX                    | [5f413be4fc](https://linux-hardware.org/?probe=5f413be4fc) | Nov 12, 2023 |
| MSI           | Delta 15 A5EFK              | [091eaf746f](https://linux-hardware.org/?probe=091eaf746f) | Nov 12, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [0ba73e8306](https://linux-hardware.org/?probe=0ba73e8306) | Nov 11, 2023 |
| ASUSTek       | X550ZE                      | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| Dell          | G3 3779                     | [74ef4d1941](https://linux-hardware.org/?probe=74ef4d1941) | Nov 06, 2023 |
| Acer          | Aspire 5750G                | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| HP            | 250 G8 Notebook PC          | [a2fbd58a8c](https://linux-hardware.org/?probe=a2fbd58a8c) | Nov 05, 2023 |
| Dell          | Inspiron 14 5401            | [124c666940](https://linux-hardware.org/?probe=124c666940) | Nov 05, 2023 |
| Dell          | Inspiron 14 5401            | [9eeeda059e](https://linux-hardware.org/?probe=9eeeda059e) | Nov 05, 2023 |
| Dell          | Inspiron 15 3511            | [4c97723997](https://linux-hardware.org/?probe=4c97723997) | Nov 04, 2023 |
| Toshiba       | Satellite C650              | [6844fc4fcf](https://linux-hardware.org/?probe=6844fc4fcf) | Nov 03, 2023 |
| ASUSTek       | X580VD                      | [5bb358c66e](https://linux-hardware.org/?probe=5bb358c66e) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G634JZ            | [62ed235c2f](https://linux-hardware.org/?probe=62ed235c2f) | Nov 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [9422d2efb5](https://linux-hardware.org/?probe=9422d2efb5) | Nov 01, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [c90dd43290](https://linux-hardware.org/?probe=c90dd43290) | Oct 29, 2023 |
| Acer          | Aspire A715-43G             | [d9337e90a8](https://linux-hardware.org/?probe=d9337e90a8) | Oct 28, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | [4f120347b7](https://linux-hardware.org/?probe=4f120347b7) | Oct 27, 2023 |
| HP            | 250 G8 Notebook PC          | [609cfbdfa5](https://linux-hardware.org/?probe=609cfbdfa5) | Oct 26, 2023 |
| ASUSTek       | X555UB                      | [f501faa5ac](https://linux-hardware.org/?probe=f501faa5ac) | Oct 25, 2023 |
| Dell          | Vostro 3500                 | [d105da96dd](https://linux-hardware.org/?probe=d105da96dd) | Oct 25, 2023 |
| Dell          | Vostro 3500                 | [5a0abfcf6f](https://linux-hardware.org/?probe=5a0abfcf6f) | Oct 24, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [1f4b7f796f](https://linux-hardware.org/?probe=1f4b7f796f) | Oct 21, 2023 |
| Acer          | Aspire A315-58G             | [248f2fa5c4](https://linux-hardware.org/?probe=248f2fa5c4) | Oct 21, 2023 |
| Toshiba       | Satellite A500              | [15b78585e0](https://linux-hardware.org/?probe=15b78585e0) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | [0d2e2856a9](https://linux-hardware.org/?probe=0d2e2856a9) | Oct 19, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [f10e780f12](https://linux-hardware.org/?probe=f10e780f12) | Oct 19, 2023 |
| Acer          | Nitro AN515-58              | [011e35b011](https://linux-hardware.org/?probe=011e35b011) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | [4e2a3f7606](https://linux-hardware.org/?probe=4e2a3f7606) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | [94d47a3e29](https://linux-hardware.org/?probe=94d47a3e29) | Oct 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [00d3c32a60](https://linux-hardware.org/?probe=00d3c32a60) | Oct 13, 2023 |
| Toshiba       | Satellite C55D-C            | [2d067797db](https://linux-hardware.org/?probe=2d067797db) | Oct 12, 2023 |
| Toshiba       | Satellite C870-D7K          | [150f57bc3d](https://linux-hardware.org/?probe=150f57bc3d) | Oct 11, 2023 |
| MSI           | Bravo 15 B5DD               | [b7f6af41f9](https://linux-hardware.org/?probe=b7f6af41f9) | Oct 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [d400853f78](https://linux-hardware.org/?probe=d400853f78) | Oct 08, 2023 |
| Toshiba       | Satellite L655              | [3f3879060f](https://linux-hardware.org/?probe=3f3879060f) | Oct 07, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [2b58fa8ba6](https://linux-hardware.org/?probe=2b58fa8ba6) | Oct 06, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [c5c7ad01ed](https://linux-hardware.org/?probe=c5c7ad01ed) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [e627afd34e](https://linux-hardware.org/?probe=e627afd34e) | Oct 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [204a97a06f](https://linux-hardware.org/?probe=204a97a06f) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [25aa854661](https://linux-hardware.org/?probe=25aa854661) | Oct 03, 2023 |
| Toshiba       | KIRAbook                    | [802a0e1afd](https://linux-hardware.org/?probe=802a0e1afd) | Oct 02, 2023 |
| IX1401        | Unknown                     | [8014a1028b](https://linux-hardware.org/?probe=8014a1028b) | Oct 02, 2023 |
| Acer          | Aspire V3-772               | [6e0e08c45e](https://linux-hardware.org/?probe=6e0e08c45e) | Oct 01, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [16354c8d94](https://linux-hardware.org/?probe=16354c8d94) | Oct 01, 2023 |
| Acer          | Aspire SW5-173              | [b990067acf](https://linux-hardware.org/?probe=b990067acf) | Oct 01, 2023 |
| Dell          | Latitude 5520               | [024af71640](https://linux-hardware.org/?probe=024af71640) | Oct 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [1a9c5d539b](https://linux-hardware.org/?probe=1a9c5d539b) | Oct 01, 2023 |
| IX1401        | Unknown                     | [c77c1d010e](https://linux-hardware.org/?probe=c77c1d010e) | Sep 30, 2023 |
| Casper        | NIRVANA N240                | [fa2c4e6569](https://linux-hardware.org/?probe=fa2c4e6569) | Sep 29, 2023 |
| Toshiba       | Satellite P50-B-117         | [cecfba4e8f](https://linux-hardware.org/?probe=cecfba4e8f) | Sep 28, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [0a51882a60](https://linux-hardware.org/?probe=0a51882a60) | Sep 28, 2023 |
| Lenovo        | G570 20079                  | [cf0c9cc177](https://linux-hardware.org/?probe=cf0c9cc177) | Sep 28, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [96ee1b2b2a](https://linux-hardware.org/?probe=96ee1b2b2a) | Sep 28, 2023 |
| HP            | EliteBook 820 G2            | [a32eb9fe02](https://linux-hardware.org/?probe=a32eb9fe02) | Sep 28, 2023 |
| Toshiba       | Satellite P50-B-117         | [3931144171](https://linux-hardware.org/?probe=3931144171) | Sep 27, 2023 |
| Lenovo        | S10-3c 20074                | [b8adc3cf3e](https://linux-hardware.org/?probe=b8adc3cf3e) | Sep 27, 2023 |
| Acer          | Aspire E1-572G              | [45b934b885](https://linux-hardware.org/?probe=45b934b885) | Sep 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [b6cd63eedc](https://linux-hardware.org/?probe=b6cd63eedc) | Sep 26, 2023 |
| ASUSTek       | X555UB                      | [8496a9f79f](https://linux-hardware.org/?probe=8496a9f79f) | Sep 26, 2023 |
| HP            | Notebook                    | [b59281115b](https://linux-hardware.org/?probe=b59281115b) | Sep 25, 2023 |
| HP            | Notebook                    | [896e2216de](https://linux-hardware.org/?probe=896e2216de) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| ASUSTek       | N56VZ                       | [3d727dfaf6](https://linux-hardware.org/?probe=3d727dfaf6) | Sep 24, 2023 |
| Acer          | TravelMate P215-53G         | [ddda10c87f](https://linux-hardware.org/?probe=ddda10c87f) | Sep 23, 2023 |
| Casper        | NIRVANA NB F500             | [1f66f22544](https://linux-hardware.org/?probe=1f66f22544) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | [d21f140b5e](https://linux-hardware.org/?probe=d21f140b5e) | Sep 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [11ce4105e1](https://linux-hardware.org/?probe=11ce4105e1) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | [c40dbfbd1d](https://linux-hardware.org/?probe=c40dbfbd1d) | Sep 23, 2023 |
| Acer          | Aspire A515-47              | [2676f29c41](https://linux-hardware.org/?probe=2676f29c41) | Sep 22, 2023 |
| ASUSTek       | N56VZ                       | [86c85c5aab](https://linux-hardware.org/?probe=86c85c5aab) | Sep 22, 2023 |
| Dell          | Vostro 5481                 | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [0f097b1b88](https://linux-hardware.org/?probe=0f097b1b88) | Sep 22, 2023 |
| HP            | Victus by Gaming Laptop ... | [152021b3b1](https://linux-hardware.org/?probe=152021b3b1) | Sep 22, 2023 |
| Monster       | ABRA A7 V11.3               | [7d1ed0e1c5](https://linux-hardware.org/?probe=7d1ed0e1c5) | Sep 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [9fdc142c76](https://linux-hardware.org/?probe=9fdc142c76) | Sep 19, 2023 |
| HP            | Pavilion Notebook           | [3b365e2d8e](https://linux-hardware.org/?probe=3b365e2d8e) | Sep 18, 2023 |
| Hometech      | Ultra Tab 8W                | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [1b2e11b609](https://linux-hardware.org/?probe=1b2e11b609) | Sep 16, 2023 |
| ASUSTek       | X405UQ                      | [d642c4640f](https://linux-hardware.org/?probe=d642c4640f) | Sep 16, 2023 |
| HUAWEI        | KLVL-WXXW                   | [d8716b2645](https://linux-hardware.org/?probe=d8716b2645) | Sep 16, 2023 |
| Lenovo        | G550 20023                  | [054463900e](https://linux-hardware.org/?probe=054463900e) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | [cdc9163353](https://linux-hardware.org/?probe=cdc9163353) | Sep 15, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [430657ed88](https://linux-hardware.org/?probe=430657ed88) | Sep 14, 2023 |
| Monster       | TULPAR T7 V20.4             | [d83fee9f1b](https://linux-hardware.org/?probe=d83fee9f1b) | Sep 14, 2023 |
| ASUSTek       | GL552VW                     | [8e517319b7](https://linux-hardware.org/?probe=8e517319b7) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | [02b6e4991e](https://linux-hardware.org/?probe=02b6e4991e) | Sep 13, 2023 |
| Apple         | MacBookPro11,2              | [d4a65d06e2](https://linux-hardware.org/?probe=d4a65d06e2) | Sep 13, 2023 |
| HUAWEI        | WRT-WX9                     | [6bc54e3a67](https://linux-hardware.org/?probe=6bc54e3a67) | Sep 13, 2023 |
| HP            | Victus by Gaming Laptop ... | [ac50c36768](https://linux-hardware.org/?probe=ac50c36768) | Sep 13, 2023 |
| Acer          | TravelMate P215-53G         | [eaa5b75106](https://linux-hardware.org/?probe=eaa5b75106) | Sep 13, 2023 |
| ASUSTek       | GL552VW                     | [5ea02e4106](https://linux-hardware.org/?probe=5ea02e4106) | Sep 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [3ef24a5b48](https://linux-hardware.org/?probe=3ef24a5b48) | Sep 12, 2023 |
| HP            | Victus by Gaming Laptop ... | [053a34d1f9](https://linux-hardware.org/?probe=053a34d1f9) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | [fea8aeff9e](https://linux-hardware.org/?probe=fea8aeff9e) | Sep 10, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [1285b4583d](https://linux-hardware.org/?probe=1285b4583d) | Sep 10, 2023 |
| Acer          | Aspire A315-35              | [9ad28d6747](https://linux-hardware.org/?probe=9ad28d6747) | Sep 09, 2023 |
| Packard Be... | EasyNote ENTG71BM           | [35f1ceedcb](https://linux-hardware.org/?probe=35f1ceedcb) | Sep 09, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [c320e0c618](https://linux-hardware.org/?probe=c320e0c618) | Sep 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [97fc2d4d2c](https://linux-hardware.org/?probe=97fc2d4d2c) | Sep 09, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [4e756a7c7d](https://linux-hardware.org/?probe=4e756a7c7d) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [905f93bc0a](https://linux-hardware.org/?probe=905f93bc0a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [e87517b925](https://linux-hardware.org/?probe=e87517b925) | Sep 08, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [db6d9f2293](https://linux-hardware.org/?probe=db6d9f2293) | Sep 08, 2023 |
| Dell          | Inspiron 1525               | [6b0747dcb4](https://linux-hardware.org/?probe=6b0747dcb4) | Sep 07, 2023 |
| Dell          | Inspiron 1525               | [56a481c501](https://linux-hardware.org/?probe=56a481c501) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f59dbec9af](https://linux-hardware.org/?probe=f59dbec9af) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [83c77f6733](https://linux-hardware.org/?probe=83c77f6733) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [dd18138503](https://linux-hardware.org/?probe=dd18138503) | Sep 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [a1c2c12b6f](https://linux-hardware.org/?probe=a1c2c12b6f) | Sep 06, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [5b7ab92e89](https://linux-hardware.org/?probe=5b7ab92e89) | Sep 06, 2023 |
| Dell          | Latitude 3190               | [7be68f9c9a](https://linux-hardware.org/?probe=7be68f9c9a) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Sony          | SVE1513B1EW                 | [82fd19c99e](https://linux-hardware.org/?probe=82fd19c99e) | Sep 05, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [5dbf7515d1](https://linux-hardware.org/?probe=5dbf7515d1) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [229ca6e8cb](https://linux-hardware.org/?probe=229ca6e8cb) | Sep 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | [13b7789482](https://linux-hardware.org/?probe=13b7789482) | Sep 04, 2023 |
| Monster       | Huma H5 V3.2                | [75d95e264e](https://linux-hardware.org/?probe=75d95e264e) | Sep 04, 2023 |
| Acer          | Aspire ES1-533              | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [2da95fb8e8](https://linux-hardware.org/?probe=2da95fb8e8) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3900a91c0b](https://linux-hardware.org/?probe=3900a91c0b) | Sep 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | [13ea608a94](https://linux-hardware.org/?probe=13ea608a94) | Sep 03, 2023 |
| Dell          | Inspiron 5559               | [b53be4cf36](https://linux-hardware.org/?probe=b53be4cf36) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [d00f64dfcf](https://linux-hardware.org/?probe=d00f64dfcf) | Sep 02, 2023 |
| Apple         | MacBook5,1                  | [78037f5e38](https://linux-hardware.org/?probe=78037f5e38) | Sep 02, 2023 |
| Dell          | G3 3779                     | [56fa43078f](https://linux-hardware.org/?probe=56fa43078f) | Sep 02, 2023 |
| Apple         | MacBookPro11,2              | [04acccf8e2](https://linux-hardware.org/?probe=04acccf8e2) | Sep 02, 2023 |
| Casper        | EXCALIBUR G770              | [9224e20101](https://linux-hardware.org/?probe=9224e20101) | Sep 01, 2023 |
| HP            | Pavilion 13                 | [ccf98e410b](https://linux-hardware.org/?probe=ccf98e410b) | Sep 01, 2023 |
| HP            | Pavilion 13                 | [b3e756ad21](https://linux-hardware.org/?probe=b3e756ad21) | Sep 01, 2023 |
| HP            | EliteBook 860 16 inch G9... | [5e0da96bdd](https://linux-hardware.org/?probe=5e0da96bdd) | Sep 01, 2023 |
| Dell          | Precision 7730              | [11c494a20e](https://linux-hardware.org/?probe=11c494a20e) | Aug 30, 2023 |
| Dell          | Inspiron 15 3511            | [3713bc7b70](https://linux-hardware.org/?probe=3713bc7b70) | Aug 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [8c492a4b3d](https://linux-hardware.org/?probe=8c492a4b3d) | Aug 29, 2023 |
| Dell          | Inspiron 3542               | [320e8d218f](https://linux-hardware.org/?probe=320e8d218f) | Aug 28, 2023 |
| Dell          | G5 5505                     | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V805    | [ec4b2fa095](https://linux-hardware.org/?probe=ec4b2fa095) | Aug 28, 2023 |
| ASUSTek       | GL753VD                     | [3903bc9e14](https://linux-hardware.org/?probe=3903bc9e14) | Aug 27, 2023 |
| Apple         | MacBookAir7,2               | [bb8b8a594d](https://linux-hardware.org/?probe=bb8b8a594d) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| HUAWEI        | HN-WX9X                     | [d526f12390](https://linux-hardware.org/?probe=d526f12390) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [0bda6b93da](https://linux-hardware.org/?probe=0bda6b93da) | Aug 27, 2023 |
| Dell          | Vostro 5468                 | [2ee2b86d87](https://linux-hardware.org/?probe=2ee2b86d87) | Aug 27, 2023 |
| HP            | Laptop 14-em0xxx            | [b59ee89595](https://linux-hardware.org/?probe=b59ee89595) | Aug 26, 2023 |
| HUAWEI        | HN-WX9X                     | [95ff13464e](https://linux-hardware.org/?probe=95ff13464e) | Aug 25, 2023 |
| Casper        | NIRVANA NB X400             | [e8aa46ffbc](https://linux-hardware.org/?probe=e8aa46ffbc) | Aug 25, 2023 |
| HP            | Laptop 15-da2xxx            | [01636af413](https://linux-hardware.org/?probe=01636af413) | Aug 25, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [ab538d0486](https://linux-hardware.org/?probe=ab538d0486) | Aug 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [f7580a556b](https://linux-hardware.org/?probe=f7580a556b) | Aug 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [c86d5e890a](https://linux-hardware.org/?probe=c86d5e890a) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [68d28831a5](https://linux-hardware.org/?probe=68d28831a5) | Aug 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [a1d2ccf421](https://linux-hardware.org/?probe=a1d2ccf421) | Aug 22, 2023 |
| Acer          | TravelMate P215-52G         | [e8673e8d9c](https://linux-hardware.org/?probe=e8673e8d9c) | Aug 21, 2023 |
| HP            | Pavilion g6                 | [ccecca0639](https://linux-hardware.org/?probe=ccecca0639) | Aug 21, 2023 |
| Apple         | MacBookAir7,2               | [c62fc8773a](https://linux-hardware.org/?probe=c62fc8773a) | Aug 21, 2023 |
| Pegatron      | A15                         | [624757036f](https://linux-hardware.org/?probe=624757036f) | Aug 20, 2023 |
| HP            | Pavilion g6                 | [45830a7769](https://linux-hardware.org/?probe=45830a7769) | Aug 20, 2023 |
| HP            | Pavilion g6                 | [d4ba2c046d](https://linux-hardware.org/?probe=d4ba2c046d) | Aug 20, 2023 |
| Acer          | Aspire A715-51G             | [19ecc69fc4](https://linux-hardware.org/?probe=19ecc69fc4) | Aug 19, 2023 |
| Dell          | XPS 17 9730                 | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| ASUSTek       | N53SV                       | [684ece88c0](https://linux-hardware.org/?probe=684ece88c0) | Aug 17, 2023 |
| ASUSTek       | N53SV                       | [8ddf822ac7](https://linux-hardware.org/?probe=8ddf822ac7) | Aug 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGS... | [52f2042a47](https://linux-hardware.org/?probe=52f2042a47) | Aug 14, 2023 |
| ASUSTek       | GL752VW                     | [17d837907e](https://linux-hardware.org/?probe=17d837907e) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | [a65f824e07](https://linux-hardware.org/?probe=a65f824e07) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | [2da924ecb2](https://linux-hardware.org/?probe=2da924ecb2) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ab5728ee52](https://linux-hardware.org/?probe=ab5728ee52) | Aug 13, 2023 |
| Monster       | ABRA A5 V17.2               | [0049202ca7](https://linux-hardware.org/?probe=0049202ca7) | Aug 13, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [def5f9423e](https://linux-hardware.org/?probe=def5f9423e) | Aug 12, 2023 |
| Sony          | SVE1712W1EB                 | [e65db8d147](https://linux-hardware.org/?probe=e65db8d147) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3a7d1d1f9b](https://linux-hardware.org/?probe=3a7d1d1f9b) | Aug 11, 2023 |
| Sony          | SVE1712W1EB                 | [6f323e0954](https://linux-hardware.org/?probe=6f323e0954) | Aug 11, 2023 |
| Lenovo        | ThinkPad L520 5017BW5       | [1a9bbdc058](https://linux-hardware.org/?probe=1a9bbdc058) | Aug 11, 2023 |
| MSI           | Bravo 15 C7VE               | [a58ca66b2f](https://linux-hardware.org/?probe=a58ca66b2f) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | [52bf9ffa35](https://linux-hardware.org/?probe=52bf9ffa35) | Aug 06, 2023 |
| Dell          | Latitude E7270              | [e7209c4bb7](https://linux-hardware.org/?probe=e7209c4bb7) | Aug 06, 2023 |
| HP            | Laptop 15-ra0xx             | [41b594c2c7](https://linux-hardware.org/?probe=41b594c2c7) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [ae42e537d2](https://linux-hardware.org/?probe=ae42e537d2) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [51f2c38666](https://linux-hardware.org/?probe=51f2c38666) | Aug 05, 2023 |
| MSI           | GF75 Thin 10SCXR            | [21d2f0b558](https://linux-hardware.org/?probe=21d2f0b558) | Aug 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| Lenovo        | ThinkPad T400 6475R1G       | [481e1aa044](https://linux-hardware.org/?probe=481e1aa044) | Aug 03, 2023 |
| Dell          | Inspiron 3542               | [33674f8b81](https://linux-hardware.org/?probe=33674f8b81) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Packard Be... | EasyNote TJ65               | [e5193cc5d3](https://linux-hardware.org/?probe=e5193cc5d3) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| Unknown       | HP Chromebook 14            | [ef963f6148](https://linux-hardware.org/?probe=ef963f6148) | Jul 31, 2023 |
| Google        | Snow                        | [422a01e612](https://linux-hardware.org/?probe=422a01e612) | Jul 31, 2023 |
| Google        | Peach Pit Rev 6+            | [18fff1679c](https://linux-hardware.org/?probe=18fff1679c) | Jul 31, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7486c0a60b](https://linux-hardware.org/?probe=7486c0a60b) | Jul 31, 2023 |
| Google        | Mighty                      | [6ed9cfe2d0](https://linux-hardware.org/?probe=6ed9cfe2d0) | Jul 31, 2023 |
| Google        | Hanawl                      | [08995c0e52](https://linux-hardware.org/?probe=08995c0e52) | Jul 31, 2023 |
| MSI           | U90/U100                    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Google        | Kevin                       | [ca1037f6ca](https://linux-hardware.org/?probe=ca1037f6ca) | Jul 31, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [961a4eebbd](https://linux-hardware.org/?probe=961a4eebbd) | Jul 31, 2023 |
| Toshiba       | Satellite L755              | [9e9caad8ea](https://linux-hardware.org/?probe=9e9caad8ea) | Jul 31, 2023 |
| I-Life Dig... | ZED Air CX7                 | [2c897f0413](https://linux-hardware.org/?probe=2c897f0413) | Jul 30, 2023 |
| Sony          | SVE14A2V2RS                 | [adc151e590](https://linux-hardware.org/?probe=adc151e590) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [f7dce38938](https://linux-hardware.org/?probe=f7dce38938) | Jul 28, 2023 |
| HP            | 250 G3                      | [49b5a143cf](https://linux-hardware.org/?probe=49b5a143cf) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| HP            | Pavilion g6                 | [6d6fe6a05b](https://linux-hardware.org/?probe=6d6fe6a05b) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| ASUSTek       | K52JT                       | [c2cf59f878](https://linux-hardware.org/?probe=c2cf59f878) | Jul 25, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [c49c2e7a5a](https://linux-hardware.org/?probe=c49c2e7a5a) | Jul 24, 2023 |
| Apple         | MacBook5,1                  | [83d48bc8eb](https://linux-hardware.org/?probe=83d48bc8eb) | Jul 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5d3e13fc77](https://linux-hardware.org/?probe=5d3e13fc77) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [13ba381894](https://linux-hardware.org/?probe=13ba381894) | Jul 17, 2023 |
| Dell          | Inspiron 5521               | [16715e16b9](https://linux-hardware.org/?probe=16715e16b9) | Jul 17, 2023 |
| Dell          | Latitude D610               | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| Dell          | G3 3779                     | [87b8ecffa4](https://linux-hardware.org/?probe=87b8ecffa4) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [14b5fe64fa](https://linux-hardware.org/?probe=14b5fe64fa) | Jul 14, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | [db28c39c19](https://linux-hardware.org/?probe=db28c39c19) | Jul 14, 2023 |
| Dell          | Inspiron 7577               | [a9b5963254](https://linux-hardware.org/?probe=a9b5963254) | Jul 13, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | [91d748c376](https://linux-hardware.org/?probe=91d748c376) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| Apple         | MacBookPro11,1              | [7256e6a7b2](https://linux-hardware.org/?probe=7256e6a7b2) | Jul 11, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [a14d8855bc](https://linux-hardware.org/?probe=a14d8855bc) | Jul 10, 2023 |
| ASUSTek       | X550DP                      | [4cfcff7d7e](https://linux-hardware.org/?probe=4cfcff7d7e) | Jul 10, 2023 |
| Dell          | Latitude E6220              | [5e17659f32](https://linux-hardware.org/?probe=5e17659f32) | Jul 09, 2023 |
| Monster       | ABRA A5 V17.3               | [2b65146842](https://linux-hardware.org/?probe=2b65146842) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ae008e5343](https://linux-hardware.org/?probe=ae008e5343) | Jul 07, 2023 |
| Apple         | MacBookPro8,3               | [c93db722a7](https://linux-hardware.org/?probe=c93db722a7) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | [d1a5adf1ef](https://linux-hardware.org/?probe=d1a5adf1ef) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | [cda93de5a6](https://linux-hardware.org/?probe=cda93de5a6) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d8206bf6c6](https://linux-hardware.org/?probe=d8206bf6c6) | Jul 05, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [53bd77d836](https://linux-hardware.org/?probe=53bd77d836) | Jul 05, 2023 |
| Google        | Lick                        | [f2b9397a8b](https://linux-hardware.org/?probe=f2b9397a8b) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [19a254cdee](https://linux-hardware.org/?probe=19a254cdee) | Jul 03, 2023 |
| ASUSTek       | X553MA                      | [969994628c](https://linux-hardware.org/?probe=969994628c) | Jun 30, 2023 |
| ASUSTek       | X553MA                      | [53a5b9567e](https://linux-hardware.org/?probe=53a5b9567e) | Jun 30, 2023 |
| ASUSTek       | K501UX                      | [a7fb172b7d](https://linux-hardware.org/?probe=a7fb172b7d) | Jun 30, 2023 |
| Monster       | TULPAR T7 V21.7             | [046803a297](https://linux-hardware.org/?probe=046803a297) | Jun 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [8ef6f6f24a](https://linux-hardware.org/?probe=8ef6f6f24a) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [253fb546a2](https://linux-hardware.org/?probe=253fb546a2) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | [e5b49b2807](https://linux-hardware.org/?probe=e5b49b2807) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | [49c7e22c1e](https://linux-hardware.org/?probe=49c7e22c1e) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [29203c5ffe](https://linux-hardware.org/?probe=29203c5ffe) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c6edbe5681](https://linux-hardware.org/?probe=c6edbe5681) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| HP            | G62                         | [e8187f4fb6](https://linux-hardware.org/?probe=e8187f4fb6) | Jun 24, 2023 |
| Apple         | MacBookPro9,2               | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | [6609cc4a31](https://linux-hardware.org/?probe=6609cc4a31) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| Toshiba       | Satellite L755              | [eea8633642](https://linux-hardware.org/?probe=eea8633642) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [bff08fbf94](https://linux-hardware.org/?probe=bff08fbf94) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1595a5adbd](https://linux-hardware.org/?probe=1595a5adbd) | Jun 20, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [f49534dfa4](https://linux-hardware.org/?probe=f49534dfa4) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | [d09c902c57](https://linux-hardware.org/?probe=d09c902c57) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | [6e1e0b2f1c](https://linux-hardware.org/?probe=6e1e0b2f1c) | Jun 19, 2023 |
| Apple         | MacBook5,1                  | [4681ff2f7d](https://linux-hardware.org/?probe=4681ff2f7d) | Jun 19, 2023 |
| Acer          | Aspire 5750G                | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| Acer          | Aspire A515-57              | [e7f63885d1](https://linux-hardware.org/?probe=e7f63885d1) | Jun 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [fe97518345](https://linux-hardware.org/?probe=fe97518345) | Jun 17, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| Dell          | Latitude E6410              | [5eff7cff21](https://linux-hardware.org/?probe=5eff7cff21) | Jun 15, 2023 |
| Sony          | SVE1513B1EW                 | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [dc3b9443ef](https://linux-hardware.org/?probe=dc3b9443ef) | Jun 13, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [ceae8212bf](https://linux-hardware.org/?probe=ceae8212bf) | Jun 12, 2023 |
| Toshiba       | Satellite R630              | [aac5cdbb4f](https://linux-hardware.org/?probe=aac5cdbb4f) | Jun 12, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [d71e612bbb](https://linux-hardware.org/?probe=d71e612bbb) | Jun 11, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [1de48a4515](https://linux-hardware.org/?probe=1de48a4515) | Jun 10, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | [c31b0e5f30](https://linux-hardware.org/?probe=c31b0e5f30) | Jun 10, 2023 |
| Toshiba       | Satellite C650              | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| ASUSTek       | GL752VW                     | [662e292b55](https://linux-hardware.org/?probe=662e292b55) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | [024a1f80a1](https://linux-hardware.org/?probe=024a1f80a1) | Jun 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [53cb8df21f](https://linux-hardware.org/?probe=53cb8df21f) | Jun 06, 2023 |
| Acer          | AO722                       | [b8f2636f02](https://linux-hardware.org/?probe=b8f2636f02) | Jun 04, 2023 |
| Hometech      | Alfa 470C                   | [ee3bd9eb81](https://linux-hardware.org/?probe=ee3bd9eb81) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3a51aa06b9](https://linux-hardware.org/?probe=3a51aa06b9) | Jun 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [a7c067f896](https://linux-hardware.org/?probe=a7c067f896) | Jun 02, 2023 |
| Dell          | G3 3579                     | [4e5b0f9800](https://linux-hardware.org/?probe=4e5b0f9800) | May 31, 2023 |
| Apple         | MacBook5,1                  | [bb8f972443](https://linux-hardware.org/?probe=bb8f972443) | May 31, 2023 |
| Toshiba       | Satellite R630              | [5bf801ac1f](https://linux-hardware.org/?probe=5bf801ac1f) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [5839982a52](https://linux-hardware.org/?probe=5839982a52) | May 29, 2023 |
| HP            | Laptop 15-bs1xx             | [5bd3cb3a3a](https://linux-hardware.org/?probe=5bd3cb3a3a) | May 29, 2023 |
| Dell          | Latitude 5430               | [a0697218cc](https://linux-hardware.org/?probe=a0697218cc) | May 27, 2023 |
| Monster       | Huma H5 V3.1                | [ed569fe821](https://linux-hardware.org/?probe=ed569fe821) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| HP            | Pavilion g6                 | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| IX1401        | Unknown                     | [f1799b6c3a](https://linux-hardware.org/?probe=f1799b6c3a) | May 24, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [0c665ebdd8](https://linux-hardware.org/?probe=0c665ebdd8) | May 23, 2023 |
| Casper        | EXCALIBUR G770              | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S3XR00    | [0f80e19e5b](https://linux-hardware.org/?probe=0f80e19e5b) | May 23, 2023 |
| Medion        | E6224                       | [65c26a4a09](https://linux-hardware.org/?probe=65c26a4a09) | May 23, 2023 |
| Medion        | E6224                       | [8e10b22b1f](https://linux-hardware.org/?probe=8e10b22b1f) | May 23, 2023 |
| Lenovo        | Unknown                     | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| HP            | Pavilion g6                 | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| Acer          | Nitro AN515-45              | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| ASUSTek       | X555LNB                     | [a1aa3cf4b2](https://linux-hardware.org/?probe=a1aa3cf4b2) | May 22, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [3a448141db](https://linux-hardware.org/?probe=3a448141db) | May 21, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [6bce5f1ff0](https://linux-hardware.org/?probe=6bce5f1ff0) | May 20, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cb9ac11e18](https://linux-hardware.org/?probe=cb9ac11e18) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | [d07aa12d74](https://linux-hardware.org/?probe=d07aa12d74) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | [d2908ee6a9](https://linux-hardware.org/?probe=d2908ee6a9) | May 17, 2023 |
| HP            | Pavilion dv6                | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| MSI           | GS75 Stealth 10SFS          | [a2116b61ea](https://linux-hardware.org/?probe=a2116b61ea) | May 14, 2023 |
| ASUSTek       | S451LB                      | [f43e2b2679](https://linux-hardware.org/?probe=f43e2b2679) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Acer          | Aspire A315-58G             | [996701dcbd](https://linux-hardware.org/?probe=996701dcbd) | May 12, 2023 |
| HP            | Victus by Gaming Laptop ... | [6b9e3d06b1](https://linux-hardware.org/?probe=6b9e3d06b1) | May 11, 2023 |
| HP            | 250 G6 Notebook PC          | [a7cc3561af](https://linux-hardware.org/?probe=a7cc3561af) | May 10, 2023 |
| HUAWEI        | KLVL-WXX9                   | [68720e9d6b](https://linux-hardware.org/?probe=68720e9d6b) | May 10, 2023 |
| Acer          | Extensa 215-54              | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Acer          | Extensa 215-54              | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| HP            | Laptop 15-da0xxx            | [6a93900fb9](https://linux-hardware.org/?probe=6a93900fb9) | May 07, 2023 |
| HT            | C20C WSTKA001               | [a7ffbb2fe3](https://linux-hardware.org/?probe=a7ffbb2fe3) | May 07, 2023 |
| HUAWEI        | CREM-WXX9                   | [93aaae065b](https://linux-hardware.org/?probe=93aaae065b) | May 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [2a8bbbef3d](https://linux-hardware.org/?probe=2a8bbbef3d) | May 06, 2023 |
| Monster       | ABRA A5 V16.4               | [a5507638d0](https://linux-hardware.org/?probe=a5507638d0) | May 06, 2023 |
| Packard Be... | EasyNote TE69HW             | [fff5650658](https://linux-hardware.org/?probe=fff5650658) | May 05, 2023 |
| Acer          | Nitro AN515-58              | [e788d3fee0](https://linux-hardware.org/?probe=e788d3fee0) | May 04, 2023 |
| Apple         | MacBook5,1                  | [99870f2da6](https://linux-hardware.org/?probe=99870f2da6) | May 02, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [6f6a016997](https://linux-hardware.org/?probe=6f6a016997) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Monster       | TULPAR T5 V21.7             | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [8c4ba894b4](https://linux-hardware.org/?probe=8c4ba894b4) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [f9671dc0a4](https://linux-hardware.org/?probe=f9671dc0a4) | Apr 26, 2023 |
| HP            | 240 G8                      | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| HP            | 240 G8                      | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Dell          | Latitude E5530 non-vPro     | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| HP            | ProBook 4540s               | [854f17fcac](https://linux-hardware.org/?probe=854f17fcac) | Apr 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [bb1a40d839](https://linux-hardware.org/?probe=bb1a40d839) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8b18bb529f](https://linux-hardware.org/?probe=8b18bb529f) | Apr 21, 2023 |
| Lenovo        | Unknown                     | [99a0c76ea9](https://linux-hardware.org/?probe=99a0c76ea9) | Apr 18, 2023 |
| Lenovo        | Unknown                     | [653cf225b8](https://linux-hardware.org/?probe=653cf225b8) | Apr 17, 2023 |
| HUAWEI        | HVY-WXX9                    | [3d14cefd78](https://linux-hardware.org/?probe=3d14cefd78) | Apr 17, 2023 |
| ASUSTek       | X55A                        | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [3f719938aa](https://linux-hardware.org/?probe=3f719938aa) | Apr 14, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [cc0b87e611](https://linux-hardware.org/?probe=cc0b87e611) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [8152bff1b3](https://linux-hardware.org/?probe=8152bff1b3) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| Sony          | VPCEB3J1E                   | [1405405cbb](https://linux-hardware.org/?probe=1405405cbb) | Apr 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fc305814c4](https://linux-hardware.org/?probe=fc305814c4) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [11ecb91fec](https://linux-hardware.org/?probe=11ecb91fec) | Apr 09, 2023 |
| ASUSTek       | GL552VW                     | [396850fd22](https://linux-hardware.org/?probe=396850fd22) | Apr 09, 2023 |
| ASUSTek       | GL552VW                     | [ab450c0ddd](https://linux-hardware.org/?probe=ab450c0ddd) | Apr 06, 2023 |
| Acer          | Aspire A315-42              | [5d0731fb7a](https://linux-hardware.org/?probe=5d0731fb7a) | Apr 05, 2023 |
| Acer          | Extensa 215-54              | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| Acer          | Aspire 5220                 | [d22076fd54](https://linux-hardware.org/?probe=d22076fd54) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b55be43d4c](https://linux-hardware.org/?probe=b55be43d4c) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [e6a732e9b0](https://linux-hardware.org/?probe=e6a732e9b0) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [78bda6a16c](https://linux-hardware.org/?probe=78bda6a16c) | Apr 03, 2023 |
| Valve         | Jupiter                     | [38dc8922e4](https://linux-hardware.org/?probe=38dc8922e4) | Apr 03, 2023 |
| HP            | Pavilion 15                 | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [804bf25c27](https://linux-hardware.org/?probe=804bf25c27) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [6eb533f1d7](https://linux-hardware.org/?probe=6eb533f1d7) | Apr 01, 2023 |
| Toshiba       | Satellite L655              | [d527726a1c](https://linux-hardware.org/?probe=d527726a1c) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| HP            | 250 G6 Notebook PC          | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [b960038661](https://linux-hardware.org/?probe=b960038661) | Mar 27, 2023 |
| ASUSTek       | X540UP                      | [39802560c1](https://linux-hardware.org/?probe=39802560c1) | Mar 27, 2023 |
| ASUSTek       | E502NA                      | [a116400859](https://linux-hardware.org/?probe=a116400859) | Mar 27, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [d7b97732fa](https://linux-hardware.org/?probe=d7b97732fa) | Mar 26, 2023 |
| Monster       | TULPAR T7 V19.5             | [4a4933c183](https://linux-hardware.org/?probe=4a4933c183) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| Dell          | Vostro 5581                 | [d2ebb46bea](https://linux-hardware.org/?probe=d2ebb46bea) | Mar 25, 2023 |
| HONOR         | BBR-WAX9                    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| HP            | Pavilion dv6                | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [54cda388d8](https://linux-hardware.org/?probe=54cda388d8) | Mar 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [5207701ff8](https://linux-hardware.org/?probe=5207701ff8) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Lenovo        | Unknown                     | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| ASUSTek       | TP500LB                     | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| ASUSTek       | S551LB                      | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Acer          | Aspire 5935                 | [0634ed91ba](https://linux-hardware.org/?probe=0634ed91ba) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [88b7883383](https://linux-hardware.org/?probe=88b7883383) | Mar 19, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [32ba732ef0](https://linux-hardware.org/?probe=32ba732ef0) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [d79a6ae160](https://linux-hardware.org/?probe=d79a6ae160) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [691f338c53](https://linux-hardware.org/?probe=691f338c53) | Mar 17, 2023 |
| Lenovo        | Flex 2-15                   | [6bea7b508e](https://linux-hardware.org/?probe=6bea7b508e) | Mar 16, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [66f69d578c](https://linux-hardware.org/?probe=66f69d578c) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite C55-A-1K4         | [3ba10eda08](https://linux-hardware.org/?probe=3ba10eda08) | Mar 11, 2023 |
| MSI           | Alpha 15 A3DC               | [feabd7f5bf](https://linux-hardware.org/?probe=feabd7f5bf) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | [44db3bc5ec](https://linux-hardware.org/?probe=44db3bc5ec) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [96e374345a](https://linux-hardware.org/?probe=96e374345a) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b5f8598cfd](https://linux-hardware.org/?probe=b5f8598cfd) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| HUAWEI        | HN-WX9X                     | [e55325be18](https://linux-hardware.org/?probe=e55325be18) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [5535b412ed](https://linux-hardware.org/?probe=5535b412ed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | [39805e4790](https://linux-hardware.org/?probe=39805e4790) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | [d12e99f5d2](https://linux-hardware.org/?probe=d12e99f5d2) | Mar 09, 2023 |
| Acer          | Aspire A315-58              | [f4de2d1a2a](https://linux-hardware.org/?probe=f4de2d1a2a) | Mar 08, 2023 |
| Sony          | SVD11225CXB                 | [b5b755e185](https://linux-hardware.org/?probe=b5b755e185) | Mar 07, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [8961f32cc5](https://linux-hardware.org/?probe=8961f32cc5) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [d1a37d82cb](https://linux-hardware.org/?probe=d1a37d82cb) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [80ee932665](https://linux-hardware.org/?probe=80ee932665) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [c112aacdb6](https://linux-hardware.org/?probe=c112aacdb6) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [ccd91fb0c7](https://linux-hardware.org/?probe=ccd91fb0c7) | Mar 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | [4cb64cfa8f](https://linux-hardware.org/?probe=4cb64cfa8f) | Mar 03, 2023 |
| Dell          | Inspiron 3542               | [e230d5c136](https://linux-hardware.org/?probe=e230d5c136) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e0864b4a50](https://linux-hardware.org/?probe=e0864b4a50) | Mar 02, 2023 |
| HP            | 15                          | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| Apple         | MacBook5,1                  | [0242801bbc](https://linux-hardware.org/?probe=0242801bbc) | Mar 01, 2023 |
| ASUSTek       | X55A                        | [1429627725](https://linux-hardware.org/?probe=1429627725) | Feb 28, 2023 |
| Alienware     | 15 R2                       | [5e29609544](https://linux-hardware.org/?probe=5e29609544) | Feb 28, 2023 |
| Dell          | Venue 11 Pro 7130           | [68a816d082](https://linux-hardware.org/?probe=68a816d082) | Feb 28, 2023 |
| Dell          | Venue 11 Pro 7130           | [bbb8c4e905](https://linux-hardware.org/?probe=bbb8c4e905) | Feb 28, 2023 |
| Lenovo        | G510 20238                  | [2dd6ac17cf](https://linux-hardware.org/?probe=2dd6ac17cf) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Lenovo        | G510 20238                  | [2954f1a3c5](https://linux-hardware.org/?probe=2954f1a3c5) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7ff7ca240](https://linux-hardware.org/?probe=c7ff7ca240) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [be36fee6eb](https://linux-hardware.org/?probe=be36fee6eb) | Feb 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [40468a72ce](https://linux-hardware.org/?probe=40468a72ce) | Feb 20, 2023 |
| Sony          | VPCCB16FG                   | [0a6224bcc3](https://linux-hardware.org/?probe=0a6224bcc3) | Feb 19, 2023 |
| Valve         | Jupiter                     | [3543a34ca0](https://linux-hardware.org/?probe=3543a34ca0) | Feb 19, 2023 |
| HP            | Notebook                    | [2d03543f4c](https://linux-hardware.org/?probe=2d03543f4c) | Feb 18, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [75db698bfd](https://linux-hardware.org/?probe=75db698bfd) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [02d91d3f00](https://linux-hardware.org/?probe=02d91d3f00) | Feb 17, 2023 |
| Lenovo        | ThinkPad X220 4291ZD8       | [9dbad47bf0](https://linux-hardware.org/?probe=9dbad47bf0) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [514bbe20b5](https://linux-hardware.org/?probe=514bbe20b5) | Feb 15, 2023 |
| ASUSTek       | X505BP                      | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| Pegatron      | H36ST                       | [2b0e74ca00](https://linux-hardware.org/?probe=2b0e74ca00) | Feb 13, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [a4b4558244](https://linux-hardware.org/?probe=a4b4558244) | Feb 12, 2023 |
| Toshiba       | PORTEGE Z830                | [a384bb740c](https://linux-hardware.org/?probe=a384bb740c) | Feb 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [18cd6aad2c](https://linux-hardware.org/?probe=18cd6aad2c) | Feb 11, 2023 |
| HP            | 15                          | [162c6f9186](https://linux-hardware.org/?probe=162c6f9186) | Feb 11, 2023 |
| Lenovo        | ThinkPad X280 20KES2WC06    | [794dcaf42d](https://linux-hardware.org/?probe=794dcaf42d) | Feb 11, 2023 |
| Google        | Blooguard                   | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [a410a7b784](https://linux-hardware.org/?probe=a410a7b784) | Feb 09, 2023 |
| Timi          | TM1701                      | [b3015735e6](https://linux-hardware.org/?probe=b3015735e6) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [edc2a0bc35](https://linux-hardware.org/?probe=edc2a0bc35) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [8d1a082e35](https://linux-hardware.org/?probe=8d1a082e35) | Feb 09, 2023 |
| Sony          | VPCEH1M1E                   | [43f51d50c1](https://linux-hardware.org/?probe=43f51d50c1) | Feb 09, 2023 |
| HUAWEI        | BOD-WXX9                    | [1d05e35623](https://linux-hardware.org/?probe=1d05e35623) | Feb 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [ffce390164](https://linux-hardware.org/?probe=ffce390164) | Feb 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [7fd90f29c1](https://linux-hardware.org/?probe=7fd90f29c1) | Feb 08, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e1fc422565](https://linux-hardware.org/?probe=e1fc422565) | Feb 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [234f1c81c2](https://linux-hardware.org/?probe=234f1c81c2) | Feb 07, 2023 |
| Packard Be... | SJV50MV                     | [930ac749ca](https://linux-hardware.org/?probe=930ac749ca) | Feb 07, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [295fd70d70](https://linux-hardware.org/?probe=295fd70d70) | Feb 05, 2023 |
| ASUSTek       | UX32LN                      | [5b16a4a572](https://linux-hardware.org/?probe=5b16a4a572) | Feb 05, 2023 |
| Packard Be... | SJV50MV                     | [ff862a12ae](https://linux-hardware.org/?probe=ff862a12ae) | Feb 04, 2023 |
| Monster       | TULPAR T5 V20.3             | [82f58f57c0](https://linux-hardware.org/?probe=82f58f57c0) | Feb 04, 2023 |
| Monster       | TULPAR T5 V20.1             | [b224ac6a46](https://linux-hardware.org/?probe=b224ac6a46) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8c9b8348a4](https://linux-hardware.org/?probe=8c9b8348a4) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | [d839e9036f](https://linux-hardware.org/?probe=d839e9036f) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | [ed1785494a](https://linux-hardware.org/?probe=ed1785494a) | Feb 02, 2023 |
| HP            | Notebook                    | [82068da14b](https://linux-hardware.org/?probe=82068da14b) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| Toshiba       | Satellite R630              | [52ffe609b8](https://linux-hardware.org/?probe=52ffe609b8) | Jan 31, 2023 |
| Dell          | Latitude E6530              | [140543c98c](https://linux-hardware.org/?probe=140543c98c) | Jan 31, 2023 |
| Sony          | VPCCB16FG                   | [837588c9eb](https://linux-hardware.org/?probe=837588c9eb) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Sony          | VPCCB16FG                   | [7307480466](https://linux-hardware.org/?probe=7307480466) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [e789456756](https://linux-hardware.org/?probe=e789456756) | Jan 28, 2023 |
| ASUSTek       | X550VX                      | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| HP            | ProBook 6460b               | [81a1748477](https://linux-hardware.org/?probe=81a1748477) | Jan 25, 2023 |
| Toshiba       | QOSMIO X70-B                | [a7219ed5ef](https://linux-hardware.org/?probe=a7219ed5ef) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b37f2fcaba](https://linux-hardware.org/?probe=b37f2fcaba) | Jan 22, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [0e29c1dd04](https://linux-hardware.org/?probe=0e29c1dd04) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2f02d895e2](https://linux-hardware.org/?probe=2f02d895e2) | Jan 22, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [395d565464](https://linux-hardware.org/?probe=395d565464) | Jan 22, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [fcce46f618](https://linux-hardware.org/?probe=fcce46f618) | Jan 21, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [f79928ed4d](https://linux-hardware.org/?probe=f79928ed4d) | Jan 21, 2023 |
| ASUSTek       | X556UQK                     | [54cf7414fd](https://linux-hardware.org/?probe=54cf7414fd) | Jan 20, 2023 |
| HP            | Pavilion g6                 | [d828f8f4a8](https://linux-hardware.org/?probe=d828f8f4a8) | Jan 19, 2023 |
| HP            | Pavilion g6                 | [282b1007ac](https://linux-hardware.org/?probe=282b1007ac) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Acer          | Nitro AN515-46              | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | ThinkPad SL500 2746A18      | [5535380e6c](https://linux-hardware.org/?probe=5535380e6c) | Jan 16, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [b5b29198b0](https://linux-hardware.org/?probe=b5b29198b0) | Jan 15, 2023 |
| Monster       | TULPAR T5 V19.2             | [46bd0385fa](https://linux-hardware.org/?probe=46bd0385fa) | Jan 15, 2023 |
| Acer          | Swift SF314-43              | [e292f699eb](https://linux-hardware.org/?probe=e292f699eb) | Jan 14, 2023 |
| Acer          | Nitro AN515-54              | [ea080033f1](https://linux-hardware.org/?probe=ea080033f1) | Jan 14, 2023 |
| Acer          | Aspire E5-575G              | [4332a351bf](https://linux-hardware.org/?probe=4332a351bf) | Jan 13, 2023 |
| Acer          | Aspire A315-58              | [fc41631096](https://linux-hardware.org/?probe=fc41631096) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Apple         | MacBookPro9,2               | [2a71b87b09](https://linux-hardware.org/?probe=2a71b87b09) | Jan 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [93ffaa0920](https://linux-hardware.org/?probe=93ffaa0920) | Jan 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [010a4fc9bd](https://linux-hardware.org/?probe=010a4fc9bd) | Jan 10, 2023 |
| ASUSTek       | K55VD                       | [401e0c3743](https://linux-hardware.org/?probe=401e0c3743) | Jan 10, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [179af39858](https://linux-hardware.org/?probe=179af39858) | Jan 08, 2023 |
| ODM           | MS-16K2                     | [f9a7d267e5](https://linux-hardware.org/?probe=f9a7d267e5) | Jan 08, 2023 |
| MSI           | GF63 8RC                    | [9222c5a0a6](https://linux-hardware.org/?probe=9222c5a0a6) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [ef45fa4056](https://linux-hardware.org/?probe=ef45fa4056) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| HP            | Laptop 15-bw0xx             | [36c97306ae](https://linux-hardware.org/?probe=36c97306ae) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Apple         | MacBook5,1                  | [ed1bc83961](https://linux-hardware.org/?probe=ed1bc83961) | Jan 04, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [c7d37a7616](https://linux-hardware.org/?probe=c7d37a7616) | Jan 04, 2023 |
| Monster       | Huma H5 V3.2                | [cab22e2b7b](https://linux-hardware.org/?probe=cab22e2b7b) | Jan 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [113d6b92d1](https://linux-hardware.org/?probe=113d6b92d1) | Jan 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [7783f397ec](https://linux-hardware.org/?probe=7783f397ec) | Jan 03, 2023 |
| HUAWEI        | MACH-WX9                    | [525ea65bc1](https://linux-hardware.org/?probe=525ea65bc1) | Jan 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [b1d353931a](https://linux-hardware.org/?probe=b1d353931a) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| HUAWEI        | KLVL-WXX9                   | [20e752831c](https://linux-hardware.org/?probe=20e752831c) | Jan 01, 2023 |
| Dell          | G3 3500                     | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Packard Be... | EasyNote TE69HW             | [9613dfc76b](https://linux-hardware.org/?probe=9613dfc76b) | Dec 28, 2022 |
| Dell          | Inspiron 3521               | [9d544fbcd4](https://linux-hardware.org/?probe=9d544fbcd4) | Dec 26, 2022 |
| ASUSTek       | GL752VW                     | [021903d3d7](https://linux-hardware.org/?probe=021903d3d7) | Dec 25, 2022 |
| Dell          | Latitude 5521               | [32d3e87886](https://linux-hardware.org/?probe=32d3e87886) | Dec 25, 2022 |
| Hometech      | Alfa 420C                   | [9dcf2c28b3](https://linux-hardware.org/?probe=9dcf2c28b3) | Dec 23, 2022 |
| Hometech      | Alfa 420C                   | [5a4f33dd7b](https://linux-hardware.org/?probe=5a4f33dd7b) | Dec 22, 2022 |
| Monster       | ABRA A5 V18.1               | [d151d1eb82](https://linux-hardware.org/?probe=d151d1eb82) | Dec 21, 2022 |
| HP            | Pavilion Power Laptop 15... | [12bb45433d](https://linux-hardware.org/?probe=12bb45433d) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4906017260](https://linux-hardware.org/?probe=4906017260) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [085b8c23b4](https://linux-hardware.org/?probe=085b8c23b4) | Dec 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [87d3186549](https://linux-hardware.org/?probe=87d3186549) | Dec 20, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [d79e681980](https://linux-hardware.org/?probe=d79e681980) | Dec 19, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [72bfd0a0f6](https://linux-hardware.org/?probe=72bfd0a0f6) | Dec 19, 2022 |
| Dell          | Latitude 5521               | [3d3be9c8e9](https://linux-hardware.org/?probe=3d3be9c8e9) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| Pegatron      | H36FF                       | [f27fc61f18](https://linux-hardware.org/?probe=f27fc61f18) | Dec 18, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [2a39f517ef](https://linux-hardware.org/?probe=2a39f517ef) | Dec 18, 2022 |
| Pegatron      | H36FF                       | [692955be3d](https://linux-hardware.org/?probe=692955be3d) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [df49d0114f](https://linux-hardware.org/?probe=df49d0114f) | Dec 17, 2022 |
| Acer          | Aspire A315-41G             | [8641a184ad](https://linux-hardware.org/?probe=8641a184ad) | Dec 17, 2022 |
| Toshiba       | Satellite C660              | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Lenovo        | Flex 2-15                   | [38670ac27c](https://linux-hardware.org/?probe=38670ac27c) | Dec 16, 2022 |
| HP            | Laptop 14-cm0xxx            | [a5bdc5f3c9](https://linux-hardware.org/?probe=a5bdc5f3c9) | Dec 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| Monster       | HUMA H4 V4.1                | [e4f2e85204](https://linux-hardware.org/?probe=e4f2e85204) | Dec 14, 2022 |
| Acer          | Aspire A515-41G             | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| HP            | 250 G8 Notebook PC          | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| Toshiba       | Satellite C660              | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| Toshiba       | Satellite L655              | [741c3e22b7](https://linux-hardware.org/?probe=741c3e22b7) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [92f4bd5ee1](https://linux-hardware.org/?probe=92f4bd5ee1) | Dec 06, 2022 |
| Dell          | Inspiron 15-3567            | [ab7d61cced](https://linux-hardware.org/?probe=ab7d61cced) | Dec 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [cf810b2e09](https://linux-hardware.org/?probe=cf810b2e09) | Dec 04, 2022 |
| Monster       | TULPAR T7 V21.6             | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| HP            | Pavilion 13 x360 PC         | [50bcdd33eb](https://linux-hardware.org/?probe=50bcdd33eb) | Dec 04, 2022 |
| MSI           | GL65 Leopard 10SDR          | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Dell          | Inspiron 15-3567            | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| HP            | ProBook 450 G6              | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Acer          | Nitro AN515-58              | [02f4319195](https://linux-hardware.org/?probe=02f4319195) | Nov 29, 2022 |
| Acer          | Nitro AN515-58              | [77ad02b5bd](https://linux-hardware.org/?probe=77ad02b5bd) | Nov 29, 2022 |
| Toshiba       | Satellite C660              | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Dell          | G3 3500                     | [291b53ea79](https://linux-hardware.org/?probe=291b53ea79) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [415a8f0d8b](https://linux-hardware.org/?probe=415a8f0d8b) | Nov 27, 2022 |
| Lenovo        | V15-IIL 82C5                | [ceda4dbb46](https://linux-hardware.org/?probe=ceda4dbb46) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| Notebook      | NL40_50CU                   | [a116300d12](https://linux-hardware.org/?probe=a116300d12) | Nov 27, 2022 |
| Notebook      | NL40_50CU                   | [a30ad69ac2](https://linux-hardware.org/?probe=a30ad69ac2) | Nov 27, 2022 |
| Toshiba       | Satellite C660              | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| MSI           | Modern 14 B5M               | [bf3c55e13b](https://linux-hardware.org/?probe=bf3c55e13b) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | [408158ed97](https://linux-hardware.org/?probe=408158ed97) | Nov 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [dce27f6d43](https://linux-hardware.org/?probe=dce27f6d43) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [ef46869de3](https://linux-hardware.org/?probe=ef46869de3) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [10e706472c](https://linux-hardware.org/?probe=10e706472c) | Nov 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [f02593fc75](https://linux-hardware.org/?probe=f02593fc75) | Nov 23, 2022 |
| HP            | Pavilion g6                 | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| HP            | ZBook 15 G2                 | [5f040880ce](https://linux-hardware.org/?probe=5f040880ce) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | Pavilion g6                 | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Acer          | TravelMate 5360             | [c2dfb8625b](https://linux-hardware.org/?probe=c2dfb8625b) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [af679e6195](https://linux-hardware.org/?probe=af679e6195) | Nov 17, 2022 |
| Apple         | MacBook5,1                  | [7139ac864a](https://linux-hardware.org/?probe=7139ac864a) | Nov 17, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d3d2afd2c3](https://linux-hardware.org/?probe=d3d2afd2c3) | Nov 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [450e658685](https://linux-hardware.org/?probe=450e658685) | Nov 16, 2022 |
| Lenovo        | Z50-70 20354                | [15087fec90](https://linux-hardware.org/?probe=15087fec90) | Nov 16, 2022 |
| Acer          | Aspire 5720Z                | [930beb6857](https://linux-hardware.org/?probe=930beb6857) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | [3f95d3f191](https://linux-hardware.org/?probe=3f95d3f191) | Nov 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [1cb724a4d5](https://linux-hardware.org/?probe=1cb724a4d5) | Nov 15, 2022 |
| HP            | 530                         | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [700e2ffc46](https://linux-hardware.org/?probe=700e2ffc46) | Nov 15, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [9506350a75](https://linux-hardware.org/?probe=9506350a75) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b966d9e8c9](https://linux-hardware.org/?probe=b966d9e8c9) | Nov 13, 2022 |
| Toshiba       | Satellite C870-D7K          | [b2f60a1b4d](https://linux-hardware.org/?probe=b2f60a1b4d) | Nov 11, 2022 |
| Monster       | ABRA A5 V15.6               | [3bf45390cc](https://linux-hardware.org/?probe=3bf45390cc) | Nov 10, 2022 |
| Acer          | Nitro AN515-46              | [741209999d](https://linux-hardware.org/?probe=741209999d) | Nov 10, 2022 |
| HP            | ZBook 15 G2                 | [02944a1b38](https://linux-hardware.org/?probe=02944a1b38) | Nov 10, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [7638b6abf6](https://linux-hardware.org/?probe=7638b6abf6) | Nov 09, 2022 |
| MSI           | GP76 Leopard 11UG           | [5bccf91e38](https://linux-hardware.org/?probe=5bccf91e38) | Nov 09, 2022 |
| Monster       | TULPAR T7 V21.7             | [1106dc2d92](https://linux-hardware.org/?probe=1106dc2d92) | Nov 07, 2022 |
| ASUSTek       | UX490UAR                    | [dc90947100](https://linux-hardware.org/?probe=dc90947100) | Nov 07, 2022 |
| Acer          | Swift SF314-42              | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| Dell          | Inspiron N5010              | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| Acer          | Aspire 4820T                | [300aa32e45](https://linux-hardware.org/?probe=300aa32e45) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [80dbecb998](https://linux-hardware.org/?probe=80dbecb998) | Nov 04, 2022 |
| HP            | Pavilion 15                 | [93ef42ccbf](https://linux-hardware.org/?probe=93ef42ccbf) | Nov 03, 2022 |
| HP            | ZBook 15 G2                 | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [73aa3e4a7e](https://linux-hardware.org/?probe=73aa3e4a7e) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| MSI           | Prestige 14 A10SC           | [1504398ef8](https://linux-hardware.org/?probe=1504398ef8) | Oct 29, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [c2d1799732](https://linux-hardware.org/?probe=c2d1799732) | Oct 29, 2022 |
| Apple         | MacBookPro5,3               | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| MSI           | Prestige 14 A10SC           | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| Monster       | HUMA H4 V4.1                | [b086433e61](https://linux-hardware.org/?probe=b086433e61) | Oct 26, 2022 |
| Acer          | Aspire 5720Z                | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| Acer          | Aspire A715-42G             | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| Monster       | HUMA H4 V4.1                | [06a31b0132](https://linux-hardware.org/?probe=06a31b0132) | Oct 24, 2022 |
| Monster       | TULPAR T7                   | [5d01101cee](https://linux-hardware.org/?probe=5d01101cee) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| Monster       | ABRA A5 V15.2               | [cb1a5559dc](https://linux-hardware.org/?probe=cb1a5559dc) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| Dell          | Latitude E6220              | [66badd4e9a](https://linux-hardware.org/?probe=66badd4e9a) | Oct 18, 2022 |
| Monster       | TULPAR T5 V21.6             | [eaeb6f6610](https://linux-hardware.org/?probe=eaeb6f6610) | Oct 17, 2022 |
| Acer          | Aspire 5750G                | [f7e44be1b5](https://linux-hardware.org/?probe=f7e44be1b5) | Oct 17, 2022 |
| HUAWEI        | BOD-WXX9                    | [cf556bb7f7](https://linux-hardware.org/?probe=cf556bb7f7) | Oct 16, 2022 |
| HUAWEI        | BOD-WXX9                    | [a8a52af0f4](https://linux-hardware.org/?probe=a8a52af0f4) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| ASUSTek       | X550VX                      | [adbd1fa089](https://linux-hardware.org/?probe=adbd1fa089) | Oct 14, 2022 |
| MSI           | GS40 6QE Phantom            | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| ASUSTek       | X550VX                      | [c0fefb30fe](https://linux-hardware.org/?probe=c0fefb30fe) | Oct 12, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [bf2c25a350](https://linux-hardware.org/?probe=bf2c25a350) | Oct 12, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [09225a1f01](https://linux-hardware.org/?probe=09225a1f01) | Oct 10, 2022 |
| Apple         | MacBookPro8,1               | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [582de9d5d6](https://linux-hardware.org/?probe=582de9d5d6) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [f1b7cbae01](https://linux-hardware.org/?probe=f1b7cbae01) | Oct 09, 2022 |
| HP            | 340S G7                     | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| Toshiba       | Satellite L655              | [3f310e92ed](https://linux-hardware.org/?probe=3f310e92ed) | Oct 07, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2109e3f7b1](https://linux-hardware.org/?probe=2109e3f7b1) | Oct 06, 2022 |
| Toshiba       | Satellite C855-1WX          | [78c5bb7120](https://linux-hardware.org/?probe=78c5bb7120) | Oct 06, 2022 |
| HP            | Laptop 15-ra0xx             | [d81190b4e7](https://linux-hardware.org/?probe=d81190b4e7) | Oct 06, 2022 |
| HP            | ElitePad 1000 G2            | [5794de3528](https://linux-hardware.org/?probe=5794de3528) | Oct 06, 2022 |
| HP            | ElitePad 1000 G2            | [ed89b0d272](https://linux-hardware.org/?probe=ed89b0d272) | Oct 05, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [bd8ce563ff](https://linux-hardware.org/?probe=bd8ce563ff) | Oct 03, 2022 |
| HUAWEI        | HVY-WXX9                    | [4ce296ba38](https://linux-hardware.org/?probe=4ce296ba38) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | [5f1d0e6142](https://linux-hardware.org/?probe=5f1d0e6142) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | [70a80b4201](https://linux-hardware.org/?probe=70a80b4201) | Sep 30, 2022 |
| Apple         | MacBookPro15,2              | [2e6164b675](https://linux-hardware.org/?probe=2e6164b675) | Sep 28, 2022 |
| Toshiba       | QOSMIO X70-B                | [04589a6a6c](https://linux-hardware.org/?probe=04589a6a6c) | Sep 27, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Dell          | Precision 7550              | [347372a20a](https://linux-hardware.org/?probe=347372a20a) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [23f17e2f91](https://linux-hardware.org/?probe=23f17e2f91) | Sep 19, 2022 |
| Dell          | Vostro 3500                 | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| Acer          | Aspire A515-41G             | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| HP            | EliteBook 1040 G4           | [9b4136a781](https://linux-hardware.org/?probe=9b4136a781) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| ASUSTek       | N61Vn                       | [788cf883c5](https://linux-hardware.org/?probe=788cf883c5) | Sep 10, 2022 |
| Toshiba       | Satellite A200              | [ce084887f1](https://linux-hardware.org/?probe=ce084887f1) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [2f23958df0](https://linux-hardware.org/?probe=2f23958df0) | Sep 09, 2022 |
| HP            | ProBook 450 G6              | [be18103b06](https://linux-hardware.org/?probe=be18103b06) | Sep 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Acer          | Swift SF314-43              | [57235f1260](https://linux-hardware.org/?probe=57235f1260) | Sep 05, 2022 |
| Acer          | Swift SF314-43              | [7d505ec2d3](https://linux-hardware.org/?probe=7d505ec2d3) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9a637495](https://linux-hardware.org/?probe=aa9a637495) | Sep 02, 2022 |
| Apple         | MacBookAir7,2               | [73b50385f0](https://linux-hardware.org/?probe=73b50385f0) | Sep 01, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [7a5978071e](https://linux-hardware.org/?probe=7a5978071e) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [eb79e6b28e](https://linux-hardware.org/?probe=eb79e6b28e) | Aug 31, 2022 |
| HUAWEI        | CREF-XX                     | [4ea2674cd8](https://linux-hardware.org/?probe=4ea2674cd8) | Aug 31, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| Monster       | Huma H5 V3.2                | [ea050f24db](https://linux-hardware.org/?probe=ea050f24db) | Aug 29, 2022 |
| ASUSTek       | X542URR                     | [11867009b0](https://linux-hardware.org/?probe=11867009b0) | Aug 26, 2022 |
| ASUSTek       | X542URR                     | [909b7dcd37](https://linux-hardware.org/?probe=909b7dcd37) | Aug 26, 2022 |
| Acer          | TravelMate 5742G            | [37418dc2c7](https://linux-hardware.org/?probe=37418dc2c7) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [98b92cfe3a](https://linux-hardware.org/?probe=98b92cfe3a) | Aug 21, 2022 |
| Timi          | TM1701                      | [4591dee526](https://linux-hardware.org/?probe=4591dee526) | Aug 21, 2022 |
| ASUSTek       | X550LN                      | [e762245df3](https://linux-hardware.org/?probe=e762245df3) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | [8dd3a87210](https://linux-hardware.org/?probe=8dd3a87210) | Aug 20, 2022 |
| Toshiba       | QOSMIO X70-B                | [9d599f3d84](https://linux-hardware.org/?probe=9d599f3d84) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7f3311afd4](https://linux-hardware.org/?probe=7f3311afd4) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f1d6bc684c](https://linux-hardware.org/?probe=f1d6bc684c) | Aug 17, 2022 |
| Dell          | Latitude 3510               | [97e3f5102d](https://linux-hardware.org/?probe=97e3f5102d) | Aug 15, 2022 |
| HP            | Laptop 15-da1xxx            | [dd375c139f](https://linux-hardware.org/?probe=dd375c139f) | Aug 14, 2022 |
| HONOR         | BMH-WCX9                    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| Acer          | Aspire 5732Z                | [20746ad23d](https://linux-hardware.org/?probe=20746ad23d) | Aug 09, 2022 |
| ASUSTek       | X555UB                      | [db33232b90](https://linux-hardware.org/?probe=db33232b90) | Aug 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [9855f862c2](https://linux-hardware.org/?probe=9855f862c2) | Aug 08, 2022 |
| ASUSTek       | N550JV                      | [f0c5f6a834](https://linux-hardware.org/?probe=f0c5f6a834) | Aug 07, 2022 |
| HUAWEI        | KLVD-WXX9                   | [ba034abead](https://linux-hardware.org/?probe=ba034abead) | Aug 07, 2022 |
| ASUSTek       | X555LN                      | [77092711a0](https://linux-hardware.org/?probe=77092711a0) | Aug 06, 2022 |
| Monster       | ABRA A5 V13.1               | [557923ae7f](https://linux-hardware.org/?probe=557923ae7f) | Aug 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [157da4bcd2](https://linux-hardware.org/?probe=157da4bcd2) | Aug 05, 2022 |
| ASUSTek       | X556UQK                     | [55af061736](https://linux-hardware.org/?probe=55af061736) | Aug 05, 2022 |
| HP            | Pavilion Notebook           | [705f31df94](https://linux-hardware.org/?probe=705f31df94) | Aug 05, 2022 |
| Samsung       | NC210/NC110                 | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [9edf66f0ec](https://linux-hardware.org/?probe=9edf66f0ec) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [06852d59ac](https://linux-hardware.org/?probe=06852d59ac) | Aug 04, 2022 |
| HUAWEI        | HVY-WXX9                    | [057187b6c9](https://linux-hardware.org/?probe=057187b6c9) | Aug 04, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [d3163f70f3](https://linux-hardware.org/?probe=d3163f70f3) | Aug 02, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [b4d00ecb36](https://linux-hardware.org/?probe=b4d00ecb36) | Aug 02, 2022 |
| Sony          | SVE1113M1EW                 | [7a18b67232](https://linux-hardware.org/?probe=7a18b67232) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [110c94eb72](https://linux-hardware.org/?probe=110c94eb72) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [65d5b19d40](https://linux-hardware.org/?probe=65d5b19d40) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [35304c2321](https://linux-hardware.org/?probe=35304c2321) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| HP            | 250 G7 Notebook PC          | [6204ce9d95](https://linux-hardware.org/?probe=6204ce9d95) | Jul 31, 2022 |
| HP            | Pavilion g6                 | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ce2ecc0fd8](https://linux-hardware.org/?probe=ce2ecc0fd8) | Jul 24, 2022 |
| Dell          | Inspiron 14 5401            | [eaf315be72](https://linux-hardware.org/?probe=eaf315be72) | Jul 24, 2022 |
| Dell          | Latitude E5420              | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| Monster       | ABRA A5 V16.6               | [d26a2b3f0a](https://linux-hardware.org/?probe=d26a2b3f0a) | Jul 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [8bf5cae166](https://linux-hardware.org/?probe=8bf5cae166) | Jul 23, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ARCELIK       | 1S7-GNB1586B1I5             | [e9a81688b3](https://linux-hardware.org/?probe=e9a81688b3) | Jul 20, 2022 |
| ASUSTek       | X555LN                      | [f74458bf19](https://linux-hardware.org/?probe=f74458bf19) | Jul 19, 2022 |
| ASUSTek       | X555LN                      | [720cc9c1ce](https://linux-hardware.org/?probe=720cc9c1ce) | Jul 19, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [5528f26010](https://linux-hardware.org/?probe=5528f26010) | Jul 19, 2022 |
| ASUSTek       | X556UQK                     | [2ddc53797a](https://linux-hardware.org/?probe=2ddc53797a) | Jul 19, 2022 |
| Pegatron      | D15K                        | [7f8fa03161](https://linux-hardware.org/?probe=7f8fa03161) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [ebcca43b7f](https://linux-hardware.org/?probe=ebcca43b7f) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [e94cde9ec6](https://linux-hardware.org/?probe=e94cde9ec6) | Jul 17, 2022 |
| ASUSTek       | X553SA                      | [f28ef11fe2](https://linux-hardware.org/?probe=f28ef11fe2) | Jul 15, 2022 |
| HP            | Laptop 15-ra0xx             | [2ba7d6af57](https://linux-hardware.org/?probe=2ba7d6af57) | Jul 15, 2022 |
| Dell          | Vostro 15 3510              | [b44d77c9a0](https://linux-hardware.org/?probe=b44d77c9a0) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d25b4ecc69](https://linux-hardware.org/?probe=d25b4ecc69) | Jul 11, 2022 |
| Sony          | SVE1513R1EB                 | [9d74a4a9cb](https://linux-hardware.org/?probe=9d74a4a9cb) | Jul 10, 2022 |
| HUAWEI        | BOD-WXX9                    | [f4d2c6bb1e](https://linux-hardware.org/?probe=f4d2c6bb1e) | Jul 08, 2022 |
| Acer          | Aspire 5560                 | [e9615585f6](https://linux-hardware.org/?probe=e9615585f6) | Jul 07, 2022 |
| Pegatron      | H36FF                       | [87eac99d1b](https://linux-hardware.org/?probe=87eac99d1b) | Jul 06, 2022 |
| Apple         | MacBookAir7,2               | [f852861149](https://linux-hardware.org/?probe=f852861149) | Jul 06, 2022 |
| Apple         | MacBookAir7,2               | [6b942bfd10](https://linux-hardware.org/?probe=6b942bfd10) | Jul 05, 2022 |
| ASUSTek       | G550JK                      | [ab366fcbe6](https://linux-hardware.org/?probe=ab366fcbe6) | Jul 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [7bb2a0b59a](https://linux-hardware.org/?probe=7bb2a0b59a) | Jul 04, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [2ed808bbcc](https://linux-hardware.org/?probe=2ed808bbcc) | Jul 04, 2022 |
| ASUSTek       | X553SA                      | [e3cd0aa8d4](https://linux-hardware.org/?probe=e3cd0aa8d4) | Jul 02, 2022 |
| Sony          | SVE1513R1EB                 | [d352a1c731](https://linux-hardware.org/?probe=d352a1c731) | Jul 02, 2022 |
| HUAWEI        | BOD-WXX9                    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| HP            | 340S G7                     | [6695a6a5ed](https://linux-hardware.org/?probe=6695a6a5ed) | Jun 28, 2022 |
| HUAWEI        | BOD-WXX9                    | [d306afd176](https://linux-hardware.org/?probe=d306afd176) | Jun 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [f3742fcee5](https://linux-hardware.org/?probe=f3742fcee5) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Apple         | MacBook5,1                  | [1860dff362](https://linux-hardware.org/?probe=1860dff362) | Jun 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8a530af324](https://linux-hardware.org/?probe=8a530af324) | Jun 21, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d4896fb036](https://linux-hardware.org/?probe=d4896fb036) | Jun 21, 2022 |
| Apple         | MacBook5,1                  | [28147965c3](https://linux-hardware.org/?probe=28147965c3) | Jun 21, 2022 |
| Acer          | Aspire ES1-571              | [cfbc040f69](https://linux-hardware.org/?probe=cfbc040f69) | Jun 21, 2022 |
| Alienware     | m17 R3                      | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [df2017f7d5](https://linux-hardware.org/?probe=df2017f7d5) | Jun 19, 2022 |
| HP            | Pavilion 13 x360 PC         | [3bc36209d6](https://linux-hardware.org/?probe=3bc36209d6) | Jun 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [f2b6d46056](https://linux-hardware.org/?probe=f2b6d46056) | Jun 18, 2022 |
| Dell          | Inspiron N5010              | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| HUAWEI        | BOM-WXX9                    | [afc1d78a8f](https://linux-hardware.org/?probe=afc1d78a8f) | Jun 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Nokia         | Booklet 3G                  | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| Dell          | Precision 7550              | [bffea13d72](https://linux-hardware.org/?probe=bffea13d72) | Jun 14, 2022 |
| Monster       | HUMA H5 V2.2                | [062a54a327](https://linux-hardware.org/?probe=062a54a327) | Jun 13, 2022 |
| HUAWEI        | BOM-WXX9                    | [f58bb7a98a](https://linux-hardware.org/?probe=f58bb7a98a) | Jun 11, 2022 |
| HUAWEI        | KLVL-WXX9                   | [4ce4c3ad20](https://linux-hardware.org/?probe=4ce4c3ad20) | Jun 08, 2022 |
| Dell          | Inspiron 3542               | [8fcf9a9913](https://linux-hardware.org/?probe=8fcf9a9913) | Jun 07, 2022 |
| ASUSTek       | X553MA                      | [2a3ac45d9c](https://linux-hardware.org/?probe=2a3ac45d9c) | Jun 05, 2022 |
| Monster       | TULPAR T7                   | [d7001b6ceb](https://linux-hardware.org/?probe=d7001b6ceb) | Jun 05, 2022 |
| Acer          | Swift SF314-41G             | [aad6ae85d1](https://linux-hardware.org/?probe=aad6ae85d1) | Jun 04, 2022 |
| ASUSTek       | N61Vg                       | [5593b63d10](https://linux-hardware.org/?probe=5593b63d10) | Jun 04, 2022 |
| Acer          | AO722                       | [73850c23ac](https://linux-hardware.org/?probe=73850c23ac) | Jun 02, 2022 |
| Monster       | ABRA A5 V15.8               | [a284d50bb9](https://linux-hardware.org/?probe=a284d50bb9) | Jun 01, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [cf41cc78f7](https://linux-hardware.org/?probe=cf41cc78f7) | May 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [96bc0699c3](https://linux-hardware.org/?probe=96bc0699c3) | May 28, 2022 |
| HP            | 250 G3                      | [bddc428262](https://linux-hardware.org/?probe=bddc428262) | May 28, 2022 |
| HP            | 250 G3                      | [911bf39209](https://linux-hardware.org/?probe=911bf39209) | May 28, 2022 |
| Hometech      | Alfa 430C                   | [4f0e4e240d](https://linux-hardware.org/?probe=4f0e4e240d) | May 26, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2b5ef1dbe5](https://linux-hardware.org/?probe=2b5ef1dbe5) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [647e502881](https://linux-hardware.org/?probe=647e502881) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [0db0bd7aa8](https://linux-hardware.org/?probe=0db0bd7aa8) | May 25, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [21c0d575b0](https://linux-hardware.org/?probe=21c0d575b0) | May 23, 2022 |
| Toshiba       | Satellite A100              | [a789d51565](https://linux-hardware.org/?probe=a789d51565) | May 23, 2022 |
| Dell          | Inspiron 15-3552            | [a97b4f8a75](https://linux-hardware.org/?probe=a97b4f8a75) | May 22, 2022 |
| Sony          | SVS1512U1RW                 | [491818d2e0](https://linux-hardware.org/?probe=491818d2e0) | May 18, 2022 |
| HP            | EliteBook 2570p             | [70ba6585e8](https://linux-hardware.org/?probe=70ba6585e8) | May 16, 2022 |
| Clevo         | M540SS                      | [9860619027](https://linux-hardware.org/?probe=9860619027) | May 15, 2022 |
| Clevo         | M540SS                      | [e2fa8573fb](https://linux-hardware.org/?probe=e2fa8573fb) | May 15, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [0a28329f7a](https://linux-hardware.org/?probe=0a28329f7a) | May 12, 2022 |
| MSI           | Alpha 15 B5EEK              | [ea8ce36bef](https://linux-hardware.org/?probe=ea8ce36bef) | May 12, 2022 |
| HP            | Pavilion dv6                | [9e5da14b9f](https://linux-hardware.org/?probe=9e5da14b9f) | May 11, 2022 |
| Sony          | SVE14A2V2ES                 | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
| Sony          | SVE1513R1EB                 | [c378efbd3d](https://linux-hardware.org/?probe=c378efbd3d) | May 11, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [0e3079b5a1](https://linux-hardware.org/?probe=0e3079b5a1) | May 11, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [65e46938b9](https://linux-hardware.org/?probe=65e46938b9) | May 10, 2022 |
| Acer          | AO722                       | [645156f92d](https://linux-hardware.org/?probe=645156f92d) | May 10, 2022 |
| Monster       | HUMA H4 V3.1                | [38372af132](https://linux-hardware.org/?probe=38372af132) | May 10, 2022 |
| HP            | Pavilion g6                 | [267b134fdd](https://linux-hardware.org/?probe=267b134fdd) | May 09, 2022 |
| HP            | Pavilion 13 x360 PC         | [78b977ea42](https://linux-hardware.org/?probe=78b977ea42) | May 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8c1fedaa4b](https://linux-hardware.org/?probe=8c1fedaa4b) | May 06, 2022 |
| Vestel        | V Note 1341                 | [d5a260dc00](https://linux-hardware.org/?probe=d5a260dc00) | May 05, 2022 |
| MSI           | Prestige 15 A12UC           | [2b86e2ca60](https://linux-hardware.org/?probe=2b86e2ca60) | May 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Turkey/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 166       | 10.59%  |
| Ubuntu 18.04                 | 116       | 7.4%    |
| Ubuntu 22.04                 | 115       | 7.33%   |
| Arch Rolling                 | 44        | 2.81%   |
| Fedora 38                    | 35        | 2.23%   |
| Pop!_OS 22.04                | 30        | 1.91%   |
| ArcoLinux Rolling            | 30        | 1.91%   |
| Fedora 37                    | 28        | 1.79%   |
| Debian 11                    | 28        | 1.79%   |
| Fedora 36                    | 27        | 1.72%   |
| Arch                         | 26        | 1.66%   |
| Zorin 16                     | 24        | 1.53%   |
| OpenMandriva 4.3             | 24        | 1.53%   |
| Manjaro                      | 22        | 1.4%    |
| EndeavourOS Rolling          | 20        | 1.28%   |
| Linux Mint 21.2              | 19        | 1.21%   |
| Linux Mint 21.1              | 19        | 1.21%   |
| Fedora 33                    | 18        | 1.15%   |
| Debian 12                    | 18        | 1.15%   |
| Ubuntu 21.10                 | 16        | 1.02%   |
| OpenMandriva 23.01           | 16        | 1.02%   |
| Fedora 35                    | 16        | 1.02%   |
| Linux Mint 20.3              | 15        | 0.96%   |
| Fedora 39                    | 15        | 0.96%   |
| KDE neon 20.04               | 13        | 0.83%   |
| Fedora 34                    | 13        | 0.83%   |
| Elementary 6.1               | 13        | 0.83%   |
| Linux Mint 21                | 12        | 0.77%   |
| Linux Mint 20.2              | 12        | 0.77%   |
| Linux Mint 20.1              | 12        | 0.77%   |
| Ubuntu 22.10                 | 11        | 0.7%    |
| Ubuntu 21.04                 | 11        | 0.7%    |
| Linux Mint 20                | 11        | 0.7%    |
| Zorin 15                     | 10        | 0.64%   |
| Ubuntu 23.10                 | 10        | 0.64%   |
| Ubuntu 23.04                 | 10        | 0.64%   |
| ROSA R10                     | 10        | 0.64%   |
| Pop!_OS 21.10                | 10        | 0.64%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.64%   |
| Linux Mint 19.3              | 10        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 475       | 32.01%  |
| Fedora        | 139       | 9.37%   |
| Linux Mint    | 115       | 7.75%   |
| OpenMandriva  | 71        | 4.78%   |
| Arch          | 68        | 4.58%   |
| Debian        | 66        | 4.45%   |
| Pop!_OS       | 57        | 3.84%   |
| Manjaro       | 48        | 3.23%   |
| Zorin         | 35        | 2.36%   |
| Pardus        | 34        | 2.29%   |
| ArcoLinux     | 33        | 2.22%   |
| Kali          | 28        | 1.89%   |
| Kubuntu       | 27        | 1.82%   |
| Elementary    | 23        | 1.55%   |
| ROSA          | 22        | 1.48%   |
| KDE neon      | 22        | 1.48%   |
| EndeavourOS   | 21        | 1.42%   |
| Xubuntu       | 18        | 1.21%   |
| Endless       | 18        | 1.21%   |
| openSUSE      | 13        | 0.88%   |
| Lubuntu       | 13        | 0.88%   |
| Ubuntu Unity  | 11        | 0.74%   |
| Gentoo        | 11        | 0.74%   |
| Ubuntu MATE   | 10        | 0.67%   |
| Xero          | 8         | 0.54%   |
| Garuda Linux  | 7         | 0.47%   |
| Clear Linux   | 7         | 0.47%   |
| LMDE          | 6         | 0.4%    |
| PostmarketOS  | 5         | 0.34%   |
| Nobara        | 5         | 0.34%   |
| Deepin        | 5         | 0.34%   |
| Artix         | 5         | 0.34%   |
| Archman       | 5         | 0.34%   |
| SteamOS       | 4         | 0.27%   |
| Parrot        | 4         | 0.27%   |
| MX            | 4         | 0.27%   |
| Ubuntu Budgie | 3         | 0.2%    |
| CachyOS       | 3         | 0.2%    |
| BunsenLabs    | 3         | 0.2%    |
| Void Linux    | 2         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003 | 23        | 1.36%   |
| 5.4.0-58-generic        | 18        | 1.06%   |
| 6.1.1-desktop-1omv2290  | 16        | 0.94%   |
| 5.4.0-42-generic        | 16        | 0.94%   |
| 5.15.0-58-generic       | 16        | 0.94%   |
| 6.2.0-26-generic        | 15        | 0.88%   |
| 5.3.0-40-generic        | 12        | 0.71%   |
| 5.15.0-56-generic       | 12        | 0.71%   |
| 5.15.0-52-generic       | 11        | 0.65%   |
| 5.15.0-43-generic       | 10        | 0.59%   |
| 6.4.11-desktop-1omv2390 | 9         | 0.53%   |
| 6.2.0-32-generic        | 9         | 0.53%   |
| 5.4.0-37-generic        | 9         | 0.53%   |
| 5.4.0-26-generic        | 9         | 0.53%   |
| 5.19.0-32-generic       | 9         | 0.53%   |
| 5.0.0-37-generic        | 9         | 0.53%   |
| 5.4.0-74-generic        | 8         | 0.47%   |
| 5.4.0-48-generic        | 8         | 0.47%   |
| 5.4.0-47-generic        | 8         | 0.47%   |
| 5.3.0-28-generic        | 8         | 0.47%   |
| 5.15.0-48-generic       | 8         | 0.47%   |
| 5.15.0-46-generic       | 8         | 0.47%   |
| 5.13.0-30-generic       | 8         | 0.47%   |
| 5.13.0-28-generic       | 8         | 0.47%   |
| 4.18.0-15-generic       | 8         | 0.47%   |
| 6.4.12-arch1-1          | 7         | 0.41%   |
| 5.8.0-44-generic        | 7         | 0.41%   |
| 5.8.0-14-generic        | 7         | 0.41%   |
| 5.19.0-35-generic       | 7         | 0.41%   |
| 5.15.0-53-generic       | 7         | 0.41%   |
| 5.15.0-47-generic       | 7         | 0.41%   |
| 5.15.0-27-generic       | 7         | 0.41%   |
| 5.13.0-39-generic       | 7         | 0.41%   |
| 5.11.0-27-generic       | 7         | 0.41%   |
| 5.10.0-21-amd64         | 7         | 0.41%   |
| 4.18.0-25-generic       | 7         | 0.41%   |
| 6.6.2-desktop-1omv2390  | 6         | 0.35%   |
| 6.5.0-14-generic        | 6         | 0.35%   |
| 6.2.6-desktop-1omv2390  | 6         | 0.35%   |
| 6.2.6-76060206-generic  | 6         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 199       | 12.23%  |
| 5.15.0  | 147       | 9.04%   |
| 5.10.0  | 64        | 3.93%   |
| 4.15.0  | 62        | 3.81%   |
| 5.8.0   | 61        | 3.75%   |
| 5.11.0  | 61        | 3.75%   |
| 6.2.0   | 56        | 3.44%   |
| 5.13.0  | 52        | 3.2%    |
| 5.3.0   | 49        | 3.01%   |
| 5.19.0  | 45        | 2.77%   |
| 5.0.0   | 38        | 2.34%   |
| 4.18.0  | 31        | 1.91%   |
| 6.1.0   | 29        | 1.78%   |
| 5.16.7  | 25        | 1.54%   |
| 6.5.0   | 22        | 1.35%   |
| 6.1.1   | 18        | 1.11%   |
| 6.2.6   | 16        | 0.98%   |
| 4.19.0  | 16        | 0.98%   |
| 6.4.12  | 14        | 0.86%   |
| 6.4.11  | 12        | 0.74%   |
| 6.0.12  | 11        | 0.68%   |
| 6.4.6   | 9         | 0.55%   |
| 5.17.5  | 9         | 0.55%   |
| 6.6.2   | 8         | 0.49%   |
| 5.14.0  | 8         | 0.49%   |
| 5.6.0   | 7         | 0.43%   |
| 5.17.1  | 7         | 0.43%   |
| 5.10.14 | 7         | 0.43%   |
| 6.5.5   | 6         | 0.37%   |
| 6.3.8   | 6         | 0.37%   |
| 6.2.9   | 6         | 0.37%   |
| 4.9.60  | 6         | 0.37%   |
| 6.5.4   | 5         | 0.31%   |
| 6.5.11  | 5         | 0.31%   |
| 6.2.8   | 5         | 0.31%   |
| 6.0.8   | 5         | 0.31%   |
| 6.0.2   | 5         | 0.31%   |
| 5.18.13 | 5         | 0.31%   |
| 5.11.11 | 5         | 0.31%   |
| 6.5.6   | 4         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 213       | 13.39%  |
| 5.15    | 192       | 12.07%  |
| 6.2     | 101       | 6.35%   |
| 5.10    | 97        | 6.1%    |
| 6.1     | 85        | 5.34%   |
| 5.11    | 81        | 5.09%   |
| 5.8     | 73        | 4.59%   |
| 5.13    | 64        | 4.02%   |
| 4.15    | 62        | 3.9%    |
| 5.19    | 58        | 3.65%   |
| 6.4     | 55        | 3.46%   |
| 5.3     | 54        | 3.39%   |
| 6.5     | 53        | 3.33%   |
| 5.16    | 51        | 3.21%   |
| 6.0     | 43        | 2.7%    |
| 5.0     | 40        | 2.51%   |
| 4.18    | 32        | 2.01%   |
| 6.6     | 31        | 1.95%   |
| 5.17    | 26        | 1.63%   |
| 6.3     | 25        | 1.57%   |
| 5.18    | 25        | 1.57%   |
| 5.9     | 23        | 1.45%   |
| 5.14    | 17        | 1.07%   |
| 4.19    | 16        | 1.01%   |
| 4.9     | 15        | 0.94%   |
| 5.12    | 13        | 0.82%   |
| 5.7     | 12        | 0.75%   |
| 5.6     | 12        | 0.75%   |
| 5.5     | 4         | 0.25%   |
| 5.2     | 4         | 0.25%   |
| 5.1     | 4         | 0.25%   |
| 6.7     | 3         | 0.19%   |
| 4.4     | 2         | 0.13%   |
| 6.0.5   | 1         | 0.06%   |
| 4.16    | 1         | 0.06%   |
| 4.13    | 1         | 0.06%   |
| 4.10    | 1         | 0.06%   |
| 4.1     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1357      | 96.72%  |
| i686    | 37        | 2.64%   |
| armv7l  | 5         | 0.36%   |
| aarch64 | 4         | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 689       | 46.78%  |
| KDE5             | 223       | 15.14%  |
| XFCE             | 148       | 10.05%  |
| Unknown          | 147       | 9.98%   |
| X-Cinnamon       | 79        | 5.36%   |
| MATE             | 33        | 2.24%   |
| Pantheon         | 23        | 1.56%   |
| KDE              | 22        | 1.49%   |
| LXQt             | 19        | 1.29%   |
| Cinnamon         | 13        | 0.88%   |
| KDE4             | 12        | 0.81%   |
| i3               | 12        | 0.81%   |
| Unity            | 11        | 0.75%   |
| LXDE             | 8         | 0.54%   |
| sway             | 6         | 0.41%   |
| Deepin           | 5         | 0.34%   |
| Hyprland         | 4         | 0.27%   |
| Trinity          | 3         | 0.2%    |
| DWM              | 3         | 0.2%    |
| Budgie           | 3         | 0.2%    |
| bspwm            | 2         | 0.14%   |
| xmonad           | 1         | 0.07%   |
| qtile            | 1         | 0.07%   |
| openbox          | 1         | 0.07%   |
| Lingmo           | 1         | 0.07%   |
| lightdm-xsession | 1         | 0.07%   |
| GNOME Flashback  | 1         | 0.07%   |
| GNOME Classic    | 1         | 0.07%   |
| awesome          | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1045      | 71.58%  |
| Wayland | 333       | 22.81%  |
| Unknown | 63        | 4.32%   |
| Tty     | 19        | 1.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 666       | 45.03%  |
| SDDM    | 198       | 13.39%  |
| GDM     | 198       | 13.39%  |
| GDM3    | 197       | 13.32%  |
| LightDM | 155       | 10.48%  |
| TDM     | 48        | 3.25%   |
| KDM     | 12        | 0.81%   |
| XDM     | 2         | 0.14%   |
| SLiM    | 1         | 0.07%   |
| Ly      | 1         | 0.07%   |
| LXDM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 661       | 46.13%  |
| tr_TR       | 533       | 37.19%  |
| Unknown     | 133       | 9.28%   |
| en_GB       | 41        | 2.86%   |
| C           | 22        | 1.54%   |
| ru_RU       | 16        | 1.12%   |
| de_DE       | 6         | 0.42%   |
| POSIX       | 2         | 0.14%   |
| en_CA       | 2         | 0.14%   |
| ar_EG       | 2         | 0.14%   |
| zh_CN       | 1         | 0.07%   |
| tr_TR.UTF8  | 1         | 0.07%   |
| tr_CY       | 1         | 0.07%   |
| ru_UA       | 1         | 0.07%   |
| nl_BE       | 1         | 0.07%   |
| fr_FR       | 1         | 0.07%   |
| fa_IR       | 1         | 0.07%   |
| en_US.UTF8  | 1         | 0.07%   |
| en_US-UTF-8 | 1         | 0.07%   |
| en_NZ       | 1         | 0.07%   |
| en_IE       | 1         | 0.07%   |
| en_GB.UTF8  | 1         | 0.07%   |
| en_DK       | 1         | 0.07%   |
| en_150      | 1         | 0.07%   |
| de_AT       | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 825       | 57.37%  |
| BIOS | 613       | 42.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1057      | 72.5%   |
| Btrfs   | 192       | 13.17%  |
| Overlay | 89        | 6.1%    |
| Tmpfs   | 44        | 3.02%   |
| Unknown | 36        | 2.47%   |
| Xfs     | 14        | 0.96%   |
| Ext2    | 11        | 0.75%   |
| Zfs     | 8         | 0.55%   |
| F2fs    | 3         | 0.21%   |
| Ext3    | 2         | 0.14%   |
| Aufs    | 2         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 705       | 48.76%  |
| GPT     | 619       | 42.81%  |
| MBR     | 122       | 8.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1258      | 87.85%  |
| Yes       | 174       | 12.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 973       | 67.62%  |
| Yes       | 466       | 32.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 274       | 19.54%  |
| Hewlett-Packard             | 227       | 16.19%  |
| ASUSTek Computer            | 188       | 13.41%  |
| Dell                        | 138       | 9.84%   |
| Acer                        | 115       | 8.2%    |
| Monster                     | 62        | 4.42%   |
| Toshiba                     | 61        | 4.35%   |
| HUAWEI                      | 47        | 3.35%   |
| MSI                         | 40        | 2.85%   |
| Apple                       | 36        | 2.57%   |
| Samsung Electronics         | 33        | 2.35%   |
| Sony                        | 31        | 2.21%   |
| Casper                      | 29        | 2.07%   |
| Packard Bell                | 18        | 1.28%   |
| Clevo                       | 11        | 0.78%   |
| Pegatron                    | 10        | 0.71%   |
| Hometech                    | 10        | 0.71%   |
| Unknown                     | 10        | 0.71%   |
| Google                      | 8         | 0.57%   |
| ARCELIK                     | 6         | 0.43%   |
| Notebook                    | 4         | 0.29%   |
| Alienware                   | 4         | 0.29%   |
| Valve                       | 3         | 0.21%   |
| HONOR                       | 3         | 0.21%   |
| Fujitsu                     | 3         | 0.21%   |
| Quanta                      | 2         | 0.14%   |
| Medion                      | 2         | 0.14%   |
| LG Electronics              | 2         | 0.14%   |
| IX1401                      | 2         | 0.14%   |
| Intel                       | 2         | 0.14%   |
| Insyde                      | 2         | 0.14%   |
| I-Life Digital Technologies | 2         | 0.14%   |
| HT                          | 2         | 0.14%   |
| Vestel                      | 1         | 0.07%   |
| Timi                        | 1         | 0.07%   |
| System76                    | 1         | 0.07%   |
| Schenker                    | 1         | 0.07%   |
| Razer                       | 1         | 0.07%   |
| Pine Microsystems           | 1         | 0.07%   |
| ODM                         | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP Pavilion g6                       | 21        | 1.5%    |
| Unknown                              | 18        | 1.28%   |
| Casper NIRVANA NOTEBOOK              | 10        | 0.71%   |
| HP Pavilion dv6                      | 9         | 0.64%   |
| HP Notebook                          | 9         | 0.64%   |
| HP Pavilion 15                       | 7         | 0.5%    |
| HP 15                                | 7         | 0.5%    |
| ASUS X550VX                          | 7         | 0.5%    |
| Acer Aspire 5750G                    | 7         | 0.5%    |
| Lenovo V15 G2 ALC 82KD               | 6         | 0.43%   |
| HUAWEI BOD-WXX9                      | 6         | 0.43%   |
| HP Pavilion Notebook                 | 6         | 0.43%   |
| Casper EXCALIBUR G770                | 6         | 0.43%   |
| ASUS X555UB                          | 6         | 0.43%   |
| Acer Nitro AN515-58                  | 6         | 0.43%   |
| Toshiba Satellite L655               | 5         | 0.36%   |
| HUAWEI NBLK-WAX9X                    | 5         | 0.36%   |
| HUAWEI KLVL-WXX9                     | 5         | 0.36%   |
| HUAWEI BOHK-WAX9X                    | 5         | 0.36%   |
| HP 250 G3                            | 5         | 0.36%   |
| Dell Inspiron 7577                   | 5         | 0.36%   |
| Dell Inspiron 3542                   | 5         | 0.36%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 5         | 0.36%   |
| ASUS N550JV                          | 5         | 0.36%   |
| Apple MacBookAir7,2                  | 5         | 0.36%   |
| Toshiba Satellite C650               | 4         | 0.29%   |
| Monster ABRA A5 V16.6                | 4         | 0.29%   |
| Lenovo Legion Y530-15ICH 81FV        | 4         | 0.29%   |
| Lenovo IdeaPad S145-15API 81UT       | 4         | 0.29%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 4         | 0.29%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 4         | 0.29%   |
| Lenovo G50-70 20351                  | 4         | 0.29%   |
| HUAWEI HVY-WXX9                      | 4         | 0.29%   |
| HUAWEI HN-WX9X                       | 4         | 0.29%   |
| HP Pavilion Gaming Laptop 15-cx0xxx  | 4         | 0.29%   |
| HP Laptop 15-da1xxx                  | 4         | 0.29%   |
| HP G62                               | 4         | 0.29%   |
| HP ElitePad 1000 G2                  | 4         | 0.29%   |
| Dell Vostro 3500                     | 4         | 0.29%   |
| Dell Inspiron MM061                  | 4         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 103       | 7.35%   |
| Lenovo IdeaPad        | 71        | 5.06%   |
| HP Pavilion           | 70        | 4.99%   |
| Acer Aspire           | 69        | 4.92%   |
| Dell Inspiron         | 63        | 4.49%   |
| Toshiba Satellite     | 56        | 3.99%   |
| Monster ABRA          | 32        | 2.28%   |
| Dell Latitude         | 32        | 2.28%   |
| HP Laptop             | 29        | 2.07%   |
| ASUS VivoBook         | 27        | 1.93%   |
| HP ProBook            | 21        | 1.5%    |
| HP EliteBook          | 21        | 1.5%    |
| Monster TULPAR        | 19        | 1.36%   |
| Unknown               | 18        | 1.28%   |
| Packard Bell EasyNote | 17        | 1.21%   |
| Acer Nitro            | 17        | 1.21%   |
| HP 250                | 16        | 1.14%   |
| Dell Vostro           | 16        | 1.14%   |
| ASUS ROG              | 16        | 1.14%   |
| Casper NIRVANA        | 15        | 1.07%   |
| Lenovo Legion         | 14        | 1%      |
| HP Victus             | 14        | 1%      |
| Monster HUMA          | 10        | 0.71%   |
| ASUS ASUS             | 10        | 0.71%   |
| Acer Swift            | 10        | 0.71%   |
| Lenovo V15            | 9         | 0.64%   |
| Lenovo ThinkBook      | 9         | 0.64%   |
| HP Notebook           | 9         | 0.64%   |
| Dell Precision        | 9         | 0.64%   |
| Dell G3               | 9         | 0.64%   |
| Casper EXCALIBUR      | 9         | 0.64%   |
| Lenovo Yoga           | 7         | 0.5%    |
| HP 15                 | 7         | 0.5%    |
| ASUS X550VX           | 7         | 0.5%    |
| ASUS TUF              | 7         | 0.5%    |
| Acer TravelMate       | 7         | 0.5%    |
| HUAWEI BOD-WXX9       | 6         | 0.43%   |
| Hometech ALFA         | 6         | 0.43%   |
| HP OMEN               | 6         | 0.43%   |
| Dell XPS              | 6         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 153       | 10.91%  |
| 2019    | 131       | 9.34%   |
| 2021    | 124       | 8.84%   |
| 2018    | 111       | 7.92%   |
| 2011    | 103       | 7.35%   |
| 2017    | 87        | 6.21%   |
| 2012    | 84        | 5.99%   |
| 2013    | 83        | 5.92%   |
| 2015    | 81        | 5.78%   |
| 2016    | 78        | 5.56%   |
| 2014    | 78        | 5.56%   |
| 2010    | 78        | 5.56%   |
| 2022    | 65        | 4.64%   |
| 2009    | 44        | 3.14%   |
| 2008    | 32        | 2.28%   |
| 2023    | 24        | 1.71%   |
| 2007    | 21        | 1.5%    |
| 2006    | 11        | 0.78%   |
| Unknown | 9         | 0.64%   |
| 2005    | 5         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1402      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1300      | 91.1%   |
| Enabled  | 127       | 8.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1399      | 99.79%  |
| Yes  | 3         | 0.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 416       | 29.28%  |
| 3.01-4.0    | 266       | 18.72%  |
| 16.01-24.0  | 262       | 18.44%  |
| 8.01-16.0   | 259       | 18.23%  |
| 32.01-64.0  | 76        | 5.35%   |
| 1.01-2.0    | 73        | 5.14%   |
| 2.01-3.0    | 33        | 2.32%   |
| 64.01-256.0 | 14        | 0.99%   |
| 24.01-32.0  | 13        | 0.91%   |
| 0.51-1.0    | 9         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 468       | 29.85%  |
| 2.01-3.0   | 422       | 26.91%  |
| 3.01-4.0   | 259       | 16.52%  |
| 4.01-8.0   | 257       | 16.39%  |
| 0.51-1.0   | 83        | 5.29%   |
| 8.01-16.0  | 57        | 3.64%   |
| 0.01-0.5   | 16        | 1.02%   |
| 16.01-24.0 | 4         | 0.26%   |
| 32.01-64.0 | 2         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1008      | 70.54%  |
| 2      | 375       | 26.24%  |
| 3      | 30        | 2.1%    |
| 0      | 7         | 0.49%   |
| 4      | 6         | 0.42%   |
| 5      | 2         | 0.14%   |
| 6      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 943       | 66.78%  |
| Yes       | 469       | 33.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1169      | 82.97%  |
| No        | 240       | 17.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1369      | 97.65%  |
| No        | 33        | 2.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1154      | 81.32%  |
| No        | 265       | 18.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Turkey  | 1402      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Istanbul            | 533       | 35.27%  |
| Ankara              | 216       | 14.3%   |
| Izmir               | 140       | 9.27%   |
| Antalya             | 77        | 5.1%    |
| Bursa               | 64        | 4.24%   |
| Adana               | 28        | 1.85%   |
| Kosekoy             | 26        | 1.72%   |
| Gaziantep           | 19        | 1.26%   |
| Konya               | 18        | 1.19%   |
| Balıkesir          | 17        | 1.13%   |
| Mersin              | 16        | 1.06%   |
| İzmit              | 16        | 1.06%   |
| Kayseri             | 14        | 0.93%   |
| Denizli             | 13        | 0.86%   |
| Antakya             | 13        | 0.86%   |
| Samsun              | 11        | 0.73%   |
| Adapazarı          | 11        | 0.73%   |
| Tekirdağ           | 10        | 0.66%   |
| Magnesia ad Sipylum | 10        | 0.66%   |
| Mugla               | 9         | 0.6%    |
| Şişli             | 8         | 0.53%   |
| Diyarbakır         | 8         | 0.53%   |
| Aydin               | 8         | 0.53%   |
| Yalova              | 7         | 0.46%   |
| Osmaniye            | 7         | 0.46%   |
| Kartal              | 7         | 0.46%   |
| Batman              | 7         | 0.46%   |
| Ordu                | 6         | 0.4%    |
| Çanakkale          | 6         | 0.4%    |
| Trabzon             | 5         | 0.33%   |
| Isparta             | 5         | 0.33%   |
| Eskişehir          | 5         | 0.33%   |
| Erzurum             | 5         | 0.33%   |
| Sanliurfa           | 4         | 0.26%   |
| Çorum              | 4         | 0.26%   |
| Umraniye            | 3         | 0.2%    |
| Tarsus              | 3         | 0.2%    |
| OEdemis             | 3         | 0.2%    |
| Maltepe             | 3         | 0.2%    |
| Malatya             | 3         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 274       | 367    | 15.19%  |
| WDC                         | 193       | 247    | 10.7%   |
| Seagate                     | 182       | 215    | 10.09%  |
| Toshiba                     | 171       | 208    | 9.48%   |
| SanDisk                     | 159       | 181    | 8.81%   |
| Kingston                    | 97        | 137    | 5.38%   |
| Unknown                     | 72        | 91     | 3.99%   |
| SK hynix                    | 65        | 83     | 3.6%    |
| HGST                        | 61        | 69     | 3.38%   |
| Micron Technology           | 59        | 69     | 3.27%   |
| Intel                       | 45        | 58     | 2.49%   |
| Hitachi                     | 45        | 49     | 2.49%   |
| Crucial                     | 30        | 38     | 1.66%   |
| Apple                       | 23        | 29     | 1.27%   |
| KIOXIA                      | 22        | 25     | 1.22%   |
| China                       | 22        | 29     | 1.22%   |
| A-DATA Technology           | 22        | 26     | 1.22%   |
| Phison                      | 14        | 14     | 0.78%   |
| KIOXIA-EXCERIA              | 14        | 16     | 0.78%   |
| Fujitsu                     | 14        | 14     | 0.78%   |
| Kingston Technology Company | 12        | 14     | 0.67%   |
| Corsair                     | 12        | 12     | 0.67%   |
| HS-SSD-C100                 | 11        | 11     | 0.61%   |
| Micron/Crucial Technology   | 10        | 11     | 0.55%   |
| Silicon Motion              | 8         | 9      | 0.44%   |
| UMIS                        | 7         | 9      | 0.39%   |
| OCZ                         | 7         | 7      | 0.39%   |
| LITEON                      | 7         | 8      | 0.39%   |
| Union Memory                | 6         | 11     | 0.33%   |
| Pioneer                     | 6         | 22     | 0.33%   |
| Phison Electronics          | 6         | 8      | 0.33%   |
| Netac                       | 6         | 7      | 0.33%   |
| JMicron Technology          | 6         | 6      | 0.33%   |
| Unknown                     | 6         | 7      | 0.33%   |
| Union Memory (Shenzhen)     | 5         | 8      | 0.28%   |
| TwinMOS                     | 5         | 5      | 0.28%   |
| Lexar                       | 5         | 11     | 0.28%   |
| Gigabyte Technology         | 5         | 12     | 0.28%   |
| Transcend                   | 4         | 4      | 0.22%   |
| Team                        | 4         | 4      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 37        | 1.97%   |
| HGST HTS721010A9E630 1TB                           | 32        | 1.71%   |
| Toshiba MQ04ABF100 1TB                             | 23        | 1.23%   |
| Toshiba MQ01ABD100 1TB                             | 23        | 1.23%   |
| SanDisk SSD PLUS 240GB                             | 23        | 1.23%   |
| Toshiba MQ01ABF050 500GB                           | 20        | 1.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 20        | 1.07%   |
| Unknown MMC Card  32GB                             | 16        | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 16        | 0.85%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 16        | 0.85%   |
| Seagate ST500LT012-1DG142 500GB                    | 14        | 0.75%   |
| Samsung NVMe SSD Drive 512GB                       | 14        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 13        | 0.69%   |
| Seagate ST1000LM049-2GH172 1TB                     | 12        | 0.64%   |
| SanDisk SSD PLUS 120GB                             | 11        | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 10        | 0.53%   |
| Toshiba MQ01ABD075 752GB                           | 10        | 0.53%   |
| HGST HTS541010A9E680 1TB                           | 10        | 0.53%   |
| Toshiba TR200 240GB SSD                            | 9         | 0.48%   |
| Seagate ST9500325AS 500GB                          | 9         | 0.48%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 9         | 0.48%   |
| SanDisk NVMe SSD Drive 512GB                       | 9         | 0.48%   |
| SanDisk NVMe SSD Drive 256GB                       | 9         | 0.48%   |
| Kingston SA400S37240G 240GB SSD                    | 9         | 0.48%   |
| Intel NVMe SSD Drive 512GB                         | 9         | 0.48%   |
| SK hynix NVMe SSD Drive 512GB                      | 8         | 0.43%   |
| Seagate ST1000LM048-2E7172 1TB                     | 7         | 0.37%   |
| Samsung SSD 860 EVO 500GB                          | 7         | 0.37%   |
| Samsung SSD 860 EVO 250GB                          | 7         | 0.37%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 7         | 0.37%   |
| Kingston SA400S37120G 120GB SSD                    | 7         | 0.37%   |
| HGST HTS545050A7E680 500GB                         | 7         | 0.37%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 6         | 0.32%   |
| Unknown MMC Card  128GB                            | 6         | 0.32%   |
| SK hynix NVMe SSD Drive 256GB                      | 6         | 0.32%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                   | 6         | 0.32%   |
| Samsung MZVLQ512HBLU-00B00 512GB                   | 6         | 0.32%   |
| Samsung MZVLB256HBHQ-00000 256GB                   | 6         | 0.32%   |
| Phison 311CD0512GB                                 | 6         | 0.32%   |
| Micron NVMe SSD Drive 512GB                        | 6         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 177       | 204    | 30.15%  |
| WDC                 | 134       | 174    | 22.83%  |
| Toshiba             | 126       | 143    | 21.47%  |
| HGST                | 61        | 69     | 10.39%  |
| Hitachi             | 45        | 49     | 7.67%   |
| Samsung Electronics | 19        | 19     | 3.24%   |
| Fujitsu             | 14        | 14     | 2.39%   |
| Unknown             | 4         | 4      | 0.68%   |
| JMicron Technology  | 3         | 3      | 0.51%   |
| TO Exter            | 1         | 3      | 0.17%   |
| Intenso             | 1         | 1      | 0.17%   |
| External            | 1         | 1      | 0.17%   |
| Apple               | 1         | 2      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 99        | 115    | 18.47%  |
| Samsung Electronics | 92        | 116    | 17.16%  |
| Kingston            | 67        | 100    | 12.5%   |
| WDC                 | 29        | 34     | 5.41%   |
| Crucial             | 21        | 28     | 3.92%   |
| Toshiba             | 19        | 20     | 3.54%   |
| China               | 19        | 23     | 3.54%   |
| Micron Technology   | 17        | 21     | 3.17%   |
| A-DATA Technology   | 15        | 18     | 2.8%    |
| Apple               | 14        | 16     | 2.61%   |
| SK hynix            | 13        | 16     | 2.43%   |
| Corsair             | 12        | 12     | 2.24%   |
| KIOXIA-EXCERIA      | 10        | 12     | 1.87%   |
| Intel               | 8         | 14     | 1.49%   |
| Seagate             | 7         | 8      | 1.31%   |
| OCZ                 | 7         | 7      | 1.31%   |
| LITEON              | 7         | 8      | 1.31%   |
| Pioneer             | 6         | 22     | 1.12%   |
| Netac               | 6         | 7      | 1.12%   |
| TwinMOS             | 5         | 5      | 0.93%   |
| HS-SSD-C100         | 5         | 5      | 0.93%   |
| SPCC                | 4         | 4      | 0.75%   |
| LITEONIT            | 4         | 5      | 0.75%   |
| Lexar               | 4         | 10     | 0.75%   |
| KingSpec            | 4         | 4      | 0.75%   |
| JAMESDONKEY         | 4         | 4      | 0.75%   |
| Team                | 3         | 3      | 0.56%   |
| Patriot             | 3         | 4      | 0.56%   |
| KingFast            | 3         | 5      | 0.56%   |
| Gigabyte Technology | 3         | 9      | 0.56%   |
| EZCOOL              | 3         | 4      | 0.56%   |
| Indilinx            | 2         | 4      | 0.37%   |
| HI-LEVEL            | 2         | 2      | 0.37%   |
| GOODRAM             | 2         | 5      | 0.37%   |
| WDC WDS2            | 1         | 1      | 0.19%   |
| Transcend           | 1         | 1      | 0.19%   |
| SABRENT             | 1         | 1      | 0.19%   |
| PNY                 | 1         | 1      | 0.19%   |
| Mushkin             | 1         | 2      | 0.19%   |
| Leven               | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 567       | 686    | 33.1%   |
| NVMe    | 550       | 757    | 32.11%  |
| SSD     | 498       | 689    | 29.07%  |
| MMC     | 71        | 90     | 4.14%   |
| Unknown | 27        | 36     | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 929       | 1355   | 58.35%  |
| NVMe | 550       | 757    | 34.55%  |
| MMC  | 71        | 90     | 4.46%   |
| SAS  | 42        | 56     | 2.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 699       | 950    | 67.15%  |
| 0.51-1.0   | 325       | 400    | 31.22%  |
| 1.01-2.0   | 11        | 19     | 1.06%   |
| 4.01-10.0  | 5         | 5      | 0.48%   |
| 2.01-3.0   | 1         | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 452       | 29.83%  |
| 251-500        | 356       | 23.5%   |
| 501-1000       | 212       | 13.99%  |
| 51-100         | 121       | 7.99%   |
| 1-20           | 114       | 7.52%   |
| 1001-2000      | 104       | 6.86%   |
| 21-50          | 87        | 5.74%   |
| 2001-3000      | 27        | 1.78%   |
| More than 3000 | 21        | 1.39%   |
| Unknown        | 21        | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 631       | 40.14%  |
| 21-50          | 318       | 20.23%  |
| 101-250        | 202       | 12.85%  |
| 51-100         | 189       | 12.02%  |
| 251-500        | 101       | 6.42%   |
| 501-1000       | 73        | 4.64%   |
| 1001-2000      | 23        | 1.46%   |
| Unknown        | 21        | 1.34%   |
| 2001-3000      | 8         | 0.51%   |
| More than 3000 | 6         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB              | 5         | 6      | 4%      |
| Toshiba MQ01ABD100 1TB                | 4         | 4      | 3.2%    |
| Seagate ST500LT012-1DG142 500GB       | 4         | 6      | 3.2%    |
| Toshiba MQ01ABF050 500GB              | 3         | 4      | 2.4%    |
| Toshiba MQ01ABD075 752GB              | 3         | 3      | 2.4%    |
| Toshiba MQ01ABD050 500GB              | 3         | 4      | 2.4%    |
| Toshiba MK3252GSX 320GB               | 3         | 3      | 2.4%    |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 2.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 2.4%    |
| SanDisk SSD PLUS 240GB                | 3         | 3      | 2.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 3      | 1.6%    |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 2      | 1.6%    |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 1.6%    |
| Toshiba MQ02ABD100H 1TB               | 2         | 4      | 1.6%    |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.6%    |
| Seagate ST9160821AS 160GB             | 2         | 2      | 1.6%    |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.6%    |
| JMicron Technology Tech 250GB         | 2         | 2      | 1.6%    |
| Indilinx IND-S325S120G 120GB SSD      | 2         | 4      | 1.6%    |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 1.6%    |
| Hitachi HTS543232A7A384 320GB         | 2         | 2      | 1.6%    |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 1.6%    |
| Fujitsu MHY2120BH 120GB               | 2         | 2      | 1.6%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.8%    |
| WDC WD7500BPVT-55HXZT3 752GB          | 1         | 1      | 0.8%    |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1      | 0.8%    |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 1      | 0.8%    |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 0.8%    |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 0.8%    |
| WDC WD10JPVT-75A1YT0 1TB              | 1         | 1      | 0.8%    |
| Toshiba MQ01ABF050M 500GB             | 1         | 1      | 0.8%    |
| Toshiba MK4058GSX 400GB               | 1         | 1      | 0.8%    |
| Toshiba MK3265GSX 320GB               | 1         | 1      | 0.8%    |
| Toshiba MK3263GSXN 320GB              | 1         | 1      | 0.8%    |
| Toshiba MK1665GSX 160GB               | 1         | 1      | 0.8%    |
| Toshiba MK1011GAH 100GB               | 1         | 1      | 0.8%    |
| SK hynix HFS512G39TND-N210A 512GB SSD | 1         | 2      | 0.8%    |
| SK hynix HFS256G32MND-2200A 256GB SSD | 1         | 1      | 0.8%    |
| Seagate ST9750420AS 752GB             | 1         | 1      | 0.8%    |
| Seagate ST9500325AS 500GB             | 1         | 1      | 0.8%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 26        | 30     | 20.8%   |
| Seagate             | 23        | 25     | 18.4%   |
| Hitachi             | 14        | 14     | 11.2%   |
| WDC                 | 11        | 12     | 8.8%    |
| HGST                | 11        | 12     | 8.8%    |
| SanDisk             | 7         | 8      | 5.6%    |
| A-DATA Technology   | 6         | 6      | 4.8%    |
| Samsung Electronics | 5         | 7      | 4%      |
| Kingston            | 4         | 4      | 3.2%    |
| Fujitsu             | 4         | 4      | 3.2%    |
| SK hynix            | 2         | 3      | 1.6%    |
| JMicron Technology  | 2         | 2      | 1.6%    |
| Indilinx            | 2         | 4      | 1.6%    |
| China               | 2         | 2      | 1.6%    |
| LITEONIT            | 1         | 2      | 0.8%    |
| LITEON              | 1         | 1      | 0.8%    |
| JD                  | 1         | 1      | 0.8%    |
| Intel               | 1         | 1      | 0.8%    |
| Crucial             | 1         | 1      | 0.8%    |
| Apple               | 1         | 2      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 26        | 30     | 29.21%  |
| Seagate             | 23        | 25     | 25.84%  |
| Hitachi             | 14        | 14     | 15.73%  |
| HGST                | 11        | 12     | 12.36%  |
| WDC                 | 8         | 8      | 8.99%   |
| Fujitsu             | 4         | 4      | 4.49%   |
| Samsung Electronics | 2         | 2      | 2.25%   |
| Apple               | 1         | 2      | 1.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 87        | 97     | 70.73%  |
| SSD     | 31        | 39     | 25.2%   |
| NVMe    | 3         | 3      | 2.44%   |
| Unknown | 2         | 2      | 1.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 33.33%  |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 33.33%  |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 841       | 1286   | 55.47%  |
| Works    | 552       | 828    | 36.41%  |
| Malfunc  | 120       | 141    | 7.92%   |
| Failed   | 3         | 3      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 972       | 57.28%  |
| Samsung Electronics              | 181       | 10.67%  |
| AMD                              | 147       | 8.66%   |
| SanDisk                          | 84        | 4.95%   |
| SK hynix                         | 50        | 2.95%   |
| Kingston Technology Company      | 42        | 2.47%   |
| Micron Technology                | 41        | 2.42%   |
| KIOXIA                           | 32        | 1.89%   |
| Phison Electronics               | 23        | 1.36%   |
| Toshiba America Info Systems     | 21        | 1.24%   |
| Micron/Crucial Technology        | 18        | 1.06%   |
| Union Memory (Shenzhen)          | 16        | 0.94%   |
| Silicon Motion                   | 12        | 0.71%   |
| Silicon Integrated Systems [SiS] | 12        | 0.71%   |
| Nvidia                           | 9         | 0.53%   |
| ADATA Technology                 | 8         | 0.47%   |
| Apple                            | 7         | 0.41%   |
| Realtek Semiconductor            | 5         | 0.29%   |
| Yangtze Memory Technologies      | 4         | 0.24%   |
| Marvell Technology Group         | 3         | 0.18%   |
| Lite-On Technology               | 3         | 0.18%   |
| Transcend                        | 2         | 0.12%   |
| Seagate Technology               | 2         | 0.12%   |
| Solidigm                         | 1         | 0.06%   |
| Solid State Storage Technology   | 1         | 0.06%   |
| OCZ Technology Group             | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 134       | 7.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 110       | 6.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 101       | 5.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 80        | 4.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 69        | 3.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 57        | 3.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 56        | 3.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 53        | 2.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 52        | 2.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 47        | 2.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 44        | 2.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 39        | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 39        | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                              | 38        | 2.11%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 37        | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 35        | 1.95%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 27        | 1.5%    |
| Intel Tiger Lake-LP SATA Controller                                              | 25        | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 25        | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 24        | 1.33%   |
| Intel SSD 660P Series                                                            | 19        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 18        | 1%      |
| Intel Tiger Lake SATA AHCI Controller                                            | 17        | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 16        | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 16        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 0.89%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 15        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 15        | 0.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 14        | 0.78%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 14        | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 0.78%   |
| SK hynix BC511 NVMe SSD                                                          | 13        | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 13        | 0.72%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 13        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13        | 0.72%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                   | 12        | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 0.67%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 11        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1014      | 58.41%  |
| NVMe | 550       | 31.68%  |
| RAID | 97        | 5.59%   |
| IDE  | 75        | 4.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1130      | 80.6%   |
| AMD    | 263       | 18.76%  |
| ARM    | 9         | 0.64%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 38        | 2.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 2.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 1.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 27        | 1.93%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 24        | 1.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 23        | 1.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 22        | 1.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 1.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 1.36%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 19        | 1.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 1.28%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 18        | 1.28%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.21%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 17        | 1.21%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 17        | 1.21%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 1.14%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 16        | 1.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 1.07%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 15        | 1.07%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 1.07%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 1%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 14        | 1%      |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 13        | 0.93%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 13        | 0.93%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 0.93%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 12        | 0.86%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 12        | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 0.78%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 11        | 0.78%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 11        | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 0.78%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 11        | 0.78%   |
| Intel 12th Gen Core i7-12700H                 | 11        | 0.78%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 11        | 0.78%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 11        | 0.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 378       | 26.96%  |
| Intel Core i7           | 314       | 22.4%   |
| Other                   | 149       | 10.63%  |
| AMD Ryzen 5             | 91        | 6.49%   |
| Intel Core i3           | 87        | 6.21%   |
| AMD Ryzen 7             | 74        | 5.28%   |
| Intel Celeron           | 55        | 3.92%   |
| Intel Core 2 Duo        | 54        | 3.85%   |
| Intel Atom              | 34        | 2.43%   |
| Intel Pentium           | 22        | 1.57%   |
| AMD A8                  | 18        | 1.28%   |
| AMD Ryzen 3             | 15        | 1.07%   |
| Intel Pentium Dual-Core | 12        | 0.86%   |
| AMD A10                 | 12        | 0.86%   |
| Intel Core 2            | 11        | 0.78%   |
| Intel Pentium Dual      | 10        | 0.71%   |
| AMD Ryzen 7 PRO         | 6         | 0.43%   |
| AMD A6                  | 6         | 0.43%   |
| Intel Pentium Silver    | 5         | 0.36%   |
| Intel Genuine           | 4         | 0.29%   |
| Intel Core i9           | 4         | 0.29%   |
| AMD A4                  | 4         | 0.29%   |
| AMD A12                 | 4         | 0.29%   |
| AMD Ryzen 9             | 3         | 0.21%   |
| AMD Ryzen 5 PRO         | 3         | 0.21%   |
| AMD E2                  | 3         | 0.21%   |
| AMD C-60                | 3         | 0.21%   |
| Intel Xeon              | 2         | 0.14%   |
| Intel Pentium M         | 2         | 0.14%   |
| Intel Core M            | 2         | 0.14%   |
| Intel Celeron Dual-Core | 2         | 0.14%   |
| AMD E                   | 2         | 0.14%   |
| Intel Pentium 4         | 1         | 0.07%   |
| Intel Core              | 1         | 0.07%   |
| Intel Celeron M         | 1         | 0.07%   |
| AMD Turion II Neo       | 1         | 0.07%   |
| AMD Turion 64 X2 Mobile | 1         | 0.07%   |
| AMD Mobile Athlon 64    | 1         | 0.07%   |
| AMD E1                  | 1         | 0.07%   |
| AMD C-70                | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 640       | 45.65%  |
| 4      | 478       | 34.09%  |
| 6      | 133       | 9.49%   |
| 8      | 92        | 6.56%   |
| 1      | 19        | 1.36%   |
| 14     | 17        | 1.21%   |
| 10     | 15        | 1.07%   |
| 12     | 6         | 0.43%   |
| 24     | 2         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1401      | 99.93%  |
| 2      | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1108      | 78.97%  |
| 1      | 294       | 20.96%  |
| 8      | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1368      | 97.44%  |
| Unknown        | 24        | 1.71%   |
| 32-bit         | 11        | 0.78%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 453       | 31.09%  |
| 0x206a7    | 74        | 5.08%   |
| 0x306a9    | 71        | 4.87%   |
| 0x40651    | 42        | 2.88%   |
| 0x806ea    | 37        | 2.54%   |
| 0x306d4    | 35        | 2.4%    |
| 0xa0652    | 34        | 2.33%   |
| 0x806c1    | 34        | 2.33%   |
| 0x906ea    | 33        | 2.26%   |
| 0x806ec    | 32        | 2.2%    |
| 0x806e9    | 32        | 2.2%    |
| 0x406e3    | 31        | 2.13%   |
| 0x306c3    | 30        | 2.06%   |
| 0x906e9    | 28        | 1.92%   |
| 0x20655    | 28        | 1.92%   |
| 0x1067a    | 28        | 1.92%   |
| 0x08608103 | 23        | 1.58%   |
| 0x08108109 | 22        | 1.51%   |
| 0x08108102 | 22        | 1.51%   |
| 0x30678    | 20        | 1.37%   |
| 0x506e3    | 19        | 1.3%    |
| 0x0a50000c | 19        | 1.3%    |
| 0x706e5    | 17        | 1.17%   |
| 0x6fd      | 17        | 1.17%   |
| 0x08600106 | 17        | 1.17%   |
| 0x406c4    | 15        | 1.03%   |
| 0x20652    | 15        | 1.03%   |
| 0x0a50000d | 13        | 0.89%   |
| 0x906a3    | 12        | 0.82%   |
| 0x506c9    | 11        | 0.75%   |
| 0x07030105 | 10        | 0.69%   |
| 0x06006705 | 10        | 0.69%   |
| 0x906a4    | 9         | 0.62%   |
| 0x10676    | 9         | 0.62%   |
| 0x08600103 | 9         | 0.62%   |
| 0x806eb    | 8         | 0.55%   |
| 0x806d1    | 8         | 0.55%   |
| 0x106ca    | 8         | 0.55%   |
| 0x08600104 | 8         | 0.55%   |
| 0x706a8    | 6         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 250       | 17.81%  |
| SandyBridge      | 103       | 7.34%   |
| Haswell          | 98        | 6.98%   |
| IvyBridge        | 94        | 6.7%    |
| Unknown          | 84        | 5.98%   |
| Skylake          | 75        | 5.34%   |
| TigerLake        | 63        | 4.49%   |
| Westmere         | 59        | 4.2%    |
| Penryn           | 53        | 3.77%   |
| Zen+             | 51        | 3.63%   |
| Silvermont       | 50        | 3.56%   |
| CometLake        | 50        | 3.56%   |
| Broadwell        | 47        | 3.35%   |
| Zen 2            | 44        | 3.13%   |
| Zen 3            | 40        | 2.85%   |
| IceLake          | 37        | 2.64%   |
| Core             | 37        | 2.64%   |
| Alderlake Hybrid | 34        | 2.42%   |
| Excavator        | 21        | 1.5%    |
| Puma             | 19        | 1.35%   |
| Goldmont plus    | 17        | 1.21%   |
| Bonnell          | 15        | 1.07%   |
| Goldmont         | 12        | 0.85%   |
| Zen              | 9         | 0.64%   |
| Bobcat           | 9         | 0.64%   |
| Piledriver       | 7         | 0.5%    |
| Nehalem          | 7         | 0.5%    |
| P6               | 6         | 0.43%   |
| K8 Hammer        | 4         | 0.28%   |
| K10 Llano        | 4         | 0.28%   |
| Steamroller      | 2         | 0.14%   |
| NetBurst         | 1         | 0.07%   |
| K10              | 1         | 0.07%   |
| Jaguar           | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1002      | 49.88%  |
| Nvidia                           | 569       | 28.32%  |
| AMD                              | 428       | 21.3%   |
| Silicon Integrated Systems [SiS] | 10        | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 88        | 4.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 88        | 4.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 59        | 2.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 56        | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 2.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 50        | 2.39%   |
| Intel HD Graphics 620                                                                    | 46        | 2.2%    |
| Intel UHD Graphics 620                                                                   | 45        | 2.15%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 44        | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 43        | 2.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 41        | 1.96%   |
| Intel HD Graphics 5500                                                                   | 39        | 1.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 38        | 1.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 36        | 1.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 35        | 1.67%   |
| Intel HD Graphics 630                                                                    | 32        | 1.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 32        | 1.53%   |
| AMD Lucienne                                                                             | 32        | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 1.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 30        | 1.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 30        | 1.43%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 1.34%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 25        | 1.19%   |
| Intel HD Graphics 530                                                                    | 24        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 1.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 21        | 1%      |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 21        | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 20        | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 20        | 0.95%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 20        | 0.95%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 20        | 0.95%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 19        | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 19        | 0.91%   |
| Nvidia GM108M [GeForce 840M]                                                             | 18        | 0.86%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 18        | 0.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 0.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 18        | 0.86%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 17        | 0.81%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 16        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 446       | 31.68%  |
| 1 x Intel      | 432       | 30.68%  |
| 1 x AMD        | 197       | 13.99%  |
| Intel + AMD    | 122       | 8.66%   |
| 1 x Nvidia     | 76        | 5.4%    |
| 2 x AMD        | 62        | 4.4%    |
| AMD + Nvidia   | 47        | 3.34%   |
| Other          | 10        | 0.71%   |
| 1 x SiS        | 10        | 0.71%   |
| 2 x Intel      | 5         | 0.36%   |
| 2 x Nvidia     | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1111      | 77.42%  |
| Proprietary | 277       | 19.3%   |
| Unknown     | 47        | 3.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 814       | 56.18%  |
| 1.01-2.0   | 223       | 15.39%  |
| 0.01-0.5   | 148       | 10.21%  |
| 0.51-1.0   | 120       | 8.28%   |
| 3.01-4.0   | 99        | 6.83%   |
| 5.01-6.0   | 31        | 2.14%   |
| 7.01-8.0   | 7         | 0.48%   |
| 2.01-3.0   | 5         | 0.35%   |
| 8.01-16.0  | 2         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 287       | 19.13%  |
| BOE                     | 248       | 16.53%  |
| LG Display              | 242       | 16.13%  |
| Chimei Innolux          | 211       | 14.07%  |
| Samsung Electronics     | 134       | 8.93%   |
| Chi Mei Optoelectronics | 37        | 2.47%   |
| Apple                   | 36        | 2.4%    |
| PANDA                   | 32        | 2.13%   |
| Lenovo                  | 24        | 1.6%    |
| Sharp                   | 19        | 1.27%   |
| Goldstar                | 19        | 1.27%   |
| Philips                 | 17        | 1.13%   |
| Dell                    | 17        | 1.13%   |
| ViewSonic               | 15        | 1%      |
| ASUSTek Computer        | 15        | 1%      |
| Hewlett-Packard         | 13        | 0.87%   |
| LG Philips              | 11        | 0.73%   |
| AOC                     | 10        | 0.67%   |
| Ancor Communications    | 10        | 0.67%   |
| CPT                     | 9         | 0.6%    |
| Acer                    | 9         | 0.6%    |
| InfoVision              | 8         | 0.53%   |
| LGD                     | 6         | 0.4%    |
| CSO                     | 6         | 0.4%    |
| BenQ                    | 6         | 0.4%    |
| Vestel Elektronik       | 4         | 0.27%   |
| MSI                     | 4         | 0.27%   |
| HannStar                | 4         | 0.27%   |
| Valve                   | 3         | 0.2%    |
| Unknown                 | 3         | 0.2%    |
| Sony                    | 3         | 0.2%    |
| JDI                     | 2         | 0.13%   |
| HUAWEI                  | 2         | 0.13%   |
| Fujitsu Siemens         | 2         | 0.13%   |
| CS_                     | 2         | 0.13%   |
| VIE                     | 1         | 0.07%   |
| Unknown (XXX)           | 1         | 0.07%   |
| TXD                     | 1         | 0.07%   |
| Toshiba                 | 1         | 0.07%   |
| TMX                     | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 24        | 1.58%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 20        | 1.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 18        | 1.19%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 17        | 1.12%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 17        | 1.12%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 16        | 1.05%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 15        | 0.99%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 0.92%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 0.86%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 11        | 0.72%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 11        | 0.72%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 10        | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 9         | 0.59%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.59%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 9         | 0.59%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 8         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.53%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 8         | 0.53%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 8         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 7         | 0.46%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 7         | 0.46%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 7         | 0.46%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 7         | 0.46%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 7         | 0.46%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 6         | 0.4%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 6         | 0.4%    |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 6         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 6         | 0.4%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 6         | 0.4%    |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 6         | 0.4%    |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 5         | 0.33%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.33%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 661       | 46.65%  |
| 1366x768 (WXGA)    | 475       | 33.52%  |
| 1280x800 (WXGA)    | 42        | 2.96%   |
| 2560x1440 (QHD)    | 31        | 2.19%   |
| 1600x900 (HD+)     | 28        | 1.98%   |
| 3840x2160 (4K)     | 27        | 1.91%   |
| 1920x1200 (WUXGA)  | 24        | 1.69%   |
| 1440x900 (WXGA+)   | 22        | 1.55%   |
| 2560x1600          | 14        | 0.99%   |
| 2160x1440          | 14        | 0.99%   |
| 1024x600           | 11        | 0.78%   |
| 2880x1800          | 8         | 0.56%   |
| Unknown            | 8         | 0.56%   |
| 1680x1050 (WSXGA+) | 7         | 0.49%   |
| 3200x1800 (QHD+)   | 5         | 0.35%   |
| 800x1280           | 3         | 0.21%   |
| 3840x1080          | 3         | 0.21%   |
| 2560x1080          | 3         | 0.21%   |
| 1680x945           | 3         | 0.21%   |
| 1360x768           | 3         | 0.21%   |
| 1280x1024 (SXGA)   | 3         | 0.21%   |
| 3840x2400          | 2         | 0.14%   |
| 3000x2000          | 2         | 0.14%   |
| 2520x1680          | 2         | 0.14%   |
| 1920x540           | 2         | 0.14%   |
| 1024x768 (XGA)     | 2         | 0.14%   |
| 800x600            | 1         | 0.07%   |
| 3840x2560          | 1         | 0.07%   |
| 3200x2000          | 1         | 0.07%   |
| 3072x1920          | 1         | 0.07%   |
| 3046x1050          | 1         | 0.07%   |
| 2944x1840          | 1         | 0.07%   |
| 2880x1620          | 1         | 0.07%   |
| 2806x900           | 1         | 0.07%   |
| 2646x1024          | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |
| 1280x720 (HD)      | 1         | 0.07%   |
| 1280x1080          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 838       | 55.79%  |
| 13      | 161       | 10.72%  |
| 14      | 94        | 6.26%   |
| 17      | 67        | 4.46%   |
| 16      | 43        | 2.86%   |
| 23      | 39        | 2.6%    |
| 24      | 36        | 2.4%    |
| 27      | 35        | 2.33%   |
| 12      | 26        | 1.73%   |
| 21      | 25        | 1.66%   |
| 11      | 21        | 1.4%    |
| 18      | 20        | 1.33%   |
| Unknown | 20        | 1.33%   |
| 10      | 16        | 1.07%   |
| 31      | 13        | 0.87%   |
| 19      | 9         | 0.6%    |
| 20      | 5         | 0.33%   |
| 84      | 4         | 0.27%   |
| 32      | 4         | 0.27%   |
| 22      | 4         | 0.27%   |
| 34      | 3         | 0.2%    |
| 7       | 3         | 0.2%    |
| 57      | 2         | 0.13%   |
| 46      | 2         | 0.13%   |
| 43      | 2         | 0.13%   |
| 40      | 2         | 0.13%   |
| 28      | 2         | 0.13%   |
| 86      | 1         | 0.07%   |
| 72      | 1         | 0.07%   |
| 54      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 33      | 1         | 0.07%   |
| 25      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1014      | 67.87%  |
| 201-300     | 149       | 9.97%   |
| 501-600     | 104       | 6.96%   |
| 351-400     | 98        | 6.56%   |
| 401-500     | 62        | 4.15%   |
| 601-700     | 20        | 1.34%   |
| Unknown     | 20        | 1.34%   |
| 701-800     | 9         | 0.6%    |
| 1001-1500   | 6         | 0.4%    |
| 1501-2000   | 5         | 0.33%   |
| 1-100       | 3         | 0.2%    |
| 801-900     | 2         | 0.13%   |
| 901-1000    | 2         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1163      | 86.86%  |
| 16/10   | 122       | 9.11%   |
| 3/2     | 21        | 1.57%   |
| Unknown | 17        | 1.27%   |
| 4/3     | 5         | 0.37%   |
| 5/4     | 3         | 0.22%   |
| 21/9    | 3         | 0.22%   |
| 0.67    | 3         | 0.22%   |
| 6/5     | 1         | 0.07%   |
| 0.56    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 850       | 56.78%  |
| 81-90          | 195       | 13.03%  |
| 201-250        | 87        | 5.81%   |
| 121-130        | 68        | 4.54%   |
| 71-80          | 59        | 3.94%   |
| 301-350        | 35        | 2.34%   |
| 61-70          | 24        | 1.6%    |
| 351-500        | 23        | 1.54%   |
| 151-200        | 23        | 1.54%   |
| 111-120        | 22        | 1.47%   |
| 51-60          | 21        | 1.4%    |
| 141-150        | 20        | 1.34%   |
| Unknown        | 20        | 1.34%   |
| 41-50          | 16        | 1.07%   |
| More than 1000 | 9         | 0.6%    |
| 501-1000       | 7         | 0.47%   |
| 251-300        | 6         | 0.4%    |
| 91-100         | 6         | 0.4%    |
| 1-40           | 3         | 0.2%    |
| 131-140        | 3         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 654       | 44.31%  |
| 101-120       | 441       | 29.88%  |
| 51-100        | 235       | 15.92%  |
| 161-240       | 98        | 6.64%   |
| Unknown       | 20        | 1.36%   |
| More than 240 | 19        | 1.29%   |
| 1-50          | 9         | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1183      | 82.21%  |
| 2     | 196       | 13.62%  |
| 0     | 52        | 3.61%   |
| 3     | 8         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 920       | 39.78%  |
| Intel                                  | 614       | 26.55%  |
| Qualcomm Atheros                       | 334       | 14.44%  |
| Broadcom                               | 157       | 6.79%   |
| MediaTek                               | 50        | 2.16%   |
| Broadcom Limited                       | 32        | 1.38%   |
| Ralink                                 | 28        | 1.21%   |
| Marvell Technology Group               | 28        | 1.21%   |
| Ralink Technology                      | 22        | 0.95%   |
| Samsung Electronics                    | 14        | 0.61%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.56%   |
| TP-Link                                | 12        | 0.52%   |
| Xiaomi                                 | 11        | 0.48%   |
| ASIX Electronics                       | 8         | 0.35%   |
| Qualcomm Atheros Communications        | 7         | 0.3%    |
| Nvidia                                 | 7         | 0.3%    |
| ASUSTek Computer                       | 6         | 0.26%   |
| JMicron Technology                     | 5         | 0.22%   |
| Ericsson Business Mobile Networks      | 5         | 0.22%   |
| Qualcomm                               | 3         | 0.13%   |
| Huawei Technologies                    | 3         | 0.13%   |
| Dell                                   | 3         | 0.13%   |
| ZyXEL Communications                   | 2         | 0.09%   |
| Lenovo                                 | 2         | 0.09%   |
| ICS Advent                             | 2         | 0.09%   |
| Attansic Technology                    | 2         | 0.09%   |
| Apple                                  | 2         | 0.09%   |
| U-Blox                                 | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Sierra Wireless                        | 1         | 0.04%   |
| Qcom                                   | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| Motorola PCS                           | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| LSI                                    | 1         | 0.04%   |
| Linksys                                | 1         | 0.04%   |
| IMC Networks                           | 1         | 0.04%   |
| Hex/ProfiCNC                           | 1         | 0.04%   |
| Hewlett-Packard                        | 1         | 0.04%   |
| Fibocom                                | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 597       | 22.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 162       | 6.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 65        | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 65        | 2.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 62        | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 53        | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 52        | 1.95%   |
| Intel Wi-Fi 6 AX201                                                    | 52        | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 47        | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 46        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 43        | 1.61%   |
| Intel Wi-Fi 6 AX200                                                    | 42        | 1.57%   |
| Intel Wireless 7265                                                    | 39        | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 35        | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 35        | 1.31%   |
| Intel Wireless 8265 / 8275                                             | 33        | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 29        | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 29        | 1.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 27        | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                          | 26        | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 25        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 23        | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 22        | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 21        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 21        | 0.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 0.75%   |
| Intel Wireless 7260                                                    | 19        | 0.71%   |
| Intel Wireless 3160                                                    | 18        | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 18        | 0.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 18        | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 17        | 0.64%   |
| Intel Wireless 3165                                                    | 17        | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 16        | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 16        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 15        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 15        | 0.56%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                        | 14        | 0.52%   |
| Intel Wireless 8260                                                    | 14        | 0.52%   |
| Realtek Killer E2600 GbE Controller                                    | 13        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 595       | 41.23%  |
| Realtek Semiconductor             | 280       | 19.4%   |
| Qualcomm Atheros                  | 279       | 19.33%  |
| Broadcom                          | 129       | 8.94%   |
| MediaTek                          | 49        | 3.4%    |
| Ralink                            | 28        | 1.94%   |
| Ralink Technology                 | 22        | 1.52%   |
| Broadcom Limited                  | 22        | 1.52%   |
| TP-Link                           | 10        | 0.69%   |
| Qualcomm Atheros Communications   | 7         | 0.49%   |
| ASUSTek Computer                  | 6         | 0.42%   |
| Ericsson Business Mobile Networks | 3         | 0.21%   |
| ZyXEL Communications              | 2         | 0.14%   |
| Dell                              | 2         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.07%   |
| Sierra Wireless                   | 1         | 0.07%   |
| Qcom                              | 1         | 0.07%   |
| Marvell Technology Group          | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |
| IMC Networks                      | 1         | 0.07%   |
| Fibocom                           | 1         | 0.07%   |
| Belkin Components                 | 1         | 0.07%   |
| Accton Technology                 | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 65        | 4.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 65        | 4.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 62        | 4.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 53        | 3.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 52        | 3.6%    |
| Intel Wi-Fi 6 AX201                                            | 52        | 3.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 47        | 3.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 46        | 3.18%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 43        | 2.97%   |
| Intel Wi-Fi 6 AX200                                            | 42        | 2.9%    |
| Intel Wireless 7265                                            | 39        | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 35        | 2.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 35        | 2.42%   |
| Intel Wireless 8265 / 8275                                     | 33        | 2.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 29        | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 29        | 2.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 27        | 1.87%   |
| Broadcom BCM43142 802.11b/g/n                                  | 26        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 25        | 1.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 23        | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22        | 1.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 21        | 1.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 21        | 1.45%   |
| Intel Wireless 7260                                            | 19        | 1.31%   |
| Intel Wireless 3160                                            | 18        | 1.24%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 18        | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 1.24%   |
| Intel Wireless 3165                                            | 17        | 1.18%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 15        | 1.04%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 14        | 0.97%   |
| Intel Wireless 8260                                            | 14        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 13        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 0.9%    |
| Intel WiFi Link 5100                                           | 12        | 0.83%   |
| Intel Centrino Wireless-N 2230                                 | 12        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                | 11        | 0.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11        | 0.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 11        | 0.76%   |
| Intel Centrino Advanced-N 6235                                 | 11        | 0.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 10        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 823       | 68.41%  |
| Intel                                  | 111       | 9.23%   |
| Qualcomm Atheros                       | 99        | 8.23%   |
| Broadcom                               | 54        | 4.49%   |
| Marvell Technology Group               | 27        | 2.24%   |
| Samsung Electronics                    | 14        | 1.16%   |
| Silicon Integrated Systems [SiS]       | 12        | 1%      |
| Xiaomi                                 | 11        | 0.91%   |
| Broadcom Limited                       | 10        | 0.83%   |
| ASIX Electronics                       | 8         | 0.67%   |
| Nvidia                                 | 6         | 0.5%    |
| JMicron Technology                     | 5         | 0.42%   |
| Qualcomm                               | 3         | 0.25%   |
| Huawei Technologies                    | 3         | 0.25%   |
| TP-Link                                | 2         | 0.17%   |
| ICS Advent                             | 2         | 0.17%   |
| Attansic Technology                    | 2         | 0.17%   |
| Apple                                  | 2         | 0.17%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.08%   |
| Motorola PCS                           | 1         | 0.08%   |
| Microchip Technology                   | 1         | 0.08%   |
| MediaTek                               | 1         | 0.08%   |
| LSI                                    | 1         | 0.08%   |
| Lenovo                                 | 1         | 0.08%   |
| Davicom Semiconductor                  | 1         | 0.08%   |
| Aquantia                               | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 597       | 49.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 162       | 13.38%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 20        | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                              | 17        | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 16        | 1.32%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 16        | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 16        | 1.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 15        | 1.24%   |
| Realtek Killer E2600 GbE Controller                                            | 13        | 1.07%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 12        | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                                          | 12        | 0.99%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 0.99%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 11        | 0.91%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 10        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 9         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 9         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 8         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 8         | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 8         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 7         | 0.58%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 6         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 6         | 0.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 6         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 6         | 0.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 5         | 0.41%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 0.41%   |
| Intel Ethernet Connection (13) I219-V                                          | 5         | 0.41%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 0.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 5         | 0.41%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 5         | 0.41%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 5         | 0.41%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.33%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1369      | 53.75%  |
| Ethernet | 1164      | 45.7%   |
| Modem    | 13        | 0.51%   |
| Unknown  | 1         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1157      | 81.02%  |
| Ethernet | 271       | 18.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1096      | 78.06%  |
| 1     | 269       | 19.16%  |
| 0     | 36        | 2.56%   |
| 3     | 3         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1373      | 97.44%  |
| Yes  | 36        | 2.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 488       | 42%     |
| Realtek Semiconductor           | 143       | 12.31%  |
| IMC Networks                    | 108       | 9.29%   |
| Qualcomm Atheros Communications | 103       | 8.86%   |
| Lite-On Technology              | 53        | 4.56%   |
| Broadcom                        | 51        | 4.39%   |
| Foxconn / Hon Hai               | 46        | 3.96%   |
| Toshiba                         | 27        | 2.32%   |
| Apple                           | 27        | 2.32%   |
| Realtek                         | 24        | 2.07%   |
| Ralink                          | 21        | 1.81%   |
| Cambridge Silicon Radio         | 17        | 1.46%   |
| Dell                            | 14        | 1.2%    |
| ASUSTek Computer                | 12        | 1.03%   |
| Hewlett-Packard                 | 11        | 0.95%   |
| MediaTek                        | 6         | 0.52%   |
| Ralink Technology               | 3         | 0.26%   |
| Foxconn International           | 3         | 0.26%   |
| Alps Electric                   | 3         | 0.26%   |
| Qcom                            | 1         | 0.09%   |
| Marvell Semiconductor           | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 155       | 13.33%  |
| Intel AX201 Bluetooth                               | 120       | 10.32%  |
| Realtek Bluetooth Radio                             | 99        | 8.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 86        | 7.39%   |
| Qualcomm Atheros  Bluetooth Device                  | 52        | 4.47%   |
| Intel AX200 Bluetooth                               | 42        | 3.61%   |
| IMC Networks Bluetooth Radio                        | 35        | 3.01%   |
| Intel Bluetooth Device                              | 28        | 2.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 24        | 2.06%   |
| Realtek Bluetooth Radio                             | 24        | 2.06%   |
| Ralink RT3290 Bluetooth                             | 21        | 1.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 1.81%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 1.72%   |
| IMC Networks Wireless_Device                        | 19        | 1.63%   |
| IMC Networks Bluetooth Device                       | 19        | 1.63%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 1.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17        | 1.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.38%   |
| Apple Bluetooth Host Controller                     | 16        | 1.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 15        | 1.29%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1.29%   |
| Lite-On Bluetooth Device                            | 14        | 1.2%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 12        | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 1.03%   |
| IMC Networks Bluetooth USB Host Controller          | 12        | 1.03%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 12        | 1.03%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.86%   |
| Apple Bluetooth USB Host Controller                 | 10        | 0.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 0.77%   |
| Realtek RTL8723B Bluetooth                          | 8         | 0.69%   |
| IMC Networks Bluetooth                              | 8         | 0.69%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 8         | 0.69%   |
| Lite-On Wireless_Device                             | 7         | 0.6%    |
| Intel AX210 Bluetooth                               | 7         | 0.6%    |
| ASUS BT-253 Bluetooth Adapter                       | 7         | 0.6%    |
| Toshiba Askey Bluetooth Module                      | 6         | 0.52%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 6         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.52%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.52%   |
| Dell DW375 Bluetooth Module                         | 6         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1092      | 62.47%  |
| AMD                                          | 308       | 17.62%  |
| Nvidia                                       | 285       | 16.3%   |
| Silicon Integrated Systems [SiS]             | 12        | 0.69%   |
| C-Media Electronics                          | 5         | 0.29%   |
| Barco Display Systems                        | 5         | 0.29%   |
| Realtek Semiconductor                        | 4         | 0.23%   |
| Logitech                                     | 4         | 0.23%   |
| Kingston Technology                          | 4         | 0.23%   |
| Apple                                        | 4         | 0.23%   |
| LG Electronics                               | 2         | 0.11%   |
| GYROCOM C&C                                  | 2         | 0.11%   |
| GN Netcom                                    | 2         | 0.11%   |
| DSEA A/S                                     | 2         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.06%   |
| Yamaha                                       | 1         | 0.06%   |
| Trust                                        | 1         | 0.06%   |
| Texas Instruments                            | 1         | 0.06%   |
| Tenx Technology                              | 1         | 0.06%   |
| JMTek                                        | 1         | 0.06%   |
| Hewlett-Packard                              | 1         | 0.06%   |
| Google                                       | 1         | 0.06%   |
| Generalplus Technology                       | 1         | 0.06%   |
| FiiO Electronics Technology                  | 1         | 0.06%   |
| DigiTech                                     | 1         | 0.06%   |
| Creative Technology                          | 1         | 0.06%   |
| CMX Systems                                  | 1         | 0.06%   |
| BEHRINGER International                      | 1         | 0.06%   |
| Audient                                      | 1         | 0.06%   |
| ASUSTek Computer                             | 1         | 0.06%   |
| A4Tech                                       | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 184       | 8.65%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 141       | 6.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 109       | 5.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 104       | 4.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 88        | 4.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 66        | 3.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 63        | 2.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 57        | 2.68%   |
| Intel 8 Series HD Audio Controller                                                                | 57        | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 55        | 2.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 52        | 2.44%   |
| Intel Comet Lake PCH cAVS                                                                         | 47        | 2.21%   |
| Intel Broadwell-U Audio Controller                                                                | 47        | 2.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 46        | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 46        | 2.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 43        | 2.02%   |
| Nvidia Audio device                                                                               | 41        | 1.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 40        | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 36        | 1.69%   |
| Intel CM238 HD Audio Controller                                                                   | 35        | 1.64%   |
| AMD FCH Azalia Controller                                                                         | 35        | 1.64%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 34        | 1.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 34        | 1.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 33        | 1.55%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 30        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 29        | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 29        | 1.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 28        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 27        | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 24        | 1.13%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 23        | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 21        | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 20        | 0.94%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 19        | 0.89%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 18        | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 17        | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 15        | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 15        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 290       | 31.18%  |
| SK hynix            | 193       | 20.75%  |
| Kingston            | 113       | 12.15%  |
| Micron Technology   | 106       | 11.4%   |
| Unknown             | 61        | 6.56%   |
| Crucial             | 43        | 4.62%   |
| Ramaxel Technology  | 22        | 2.37%   |
| A-DATA Technology   | 21        | 2.26%   |
| Nanya Technology    | 14        | 1.51%   |
| Corsair             | 9         | 0.97%   |
| Elpida              | 8         | 0.86%   |
| Unknown             | 7         | 0.75%   |
| Unknown (ABCD)      | 5         | 0.54%   |
| Transcend           | 5         | 0.54%   |
| Timetec             | 4         | 0.43%   |
| Apacer              | 4         | 0.43%   |
| Goldkey             | 3         | 0.32%   |
| G.Skill             | 3         | 0.32%   |
| Team                | 2         | 0.22%   |
| ChangXin Memory     | 2         | 0.22%   |
| Unknown (F288)      | 1         | 0.11%   |
| Unknown (0x4509)    | 1         | 0.11%   |
| Unknown (0B38)      | 1         | 0.11%   |
| Unifosa             | 1         | 0.11%   |
| pqi                 | 1         | 0.11%   |
| Patriot             | 1         | 0.11%   |
| Lexar Co Limited    | 1         | 0.11%   |
| Kllisre             | 1         | 0.11%   |
| Hikvision           | 1         | 0.11%   |
| ff                  | 1         | 0.11%   |
| Avant               | 1         | 0.11%   |
| ASint Technology    | 1         | 0.11%   |
| AMD                 | 1         | 0.11%   |
| 4ea5                | 1         | 0.11%   |
| 48spaces            | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 20        | 2.03%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 15        | 1.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 13        | 1.32%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 12        | 1.22%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 12        | 1.22%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 12        | 1.22%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 11        | 1.12%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 11        | 1.12%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s  | 11        | 1.12%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 11        | 1.12%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 10        | 1.01%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 9         | 0.91%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 9         | 0.91%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 9         | 0.91%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 8         | 0.81%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 8         | 0.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 8         | 0.81%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 7         | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 7         | 0.71%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s     | 7         | 0.71%   |
| Unknown                                                      | 7         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 6         | 0.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 6         | 0.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 6         | 0.61%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 6         | 0.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 6         | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 6         | 0.61%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 6         | 0.61%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 6         | 0.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 6         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 6         | 0.61%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s       | 6         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR2                           | 5         | 0.51%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 0.51%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 5         | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 5         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 5         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 5         | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 5         | 0.51%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 5         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 412       | 53.3%   |
| DDR3    | 243       | 31.44%  |
| LPDDR4  | 31        | 4.01%   |
| DDR2    | 21        | 2.72%   |
| SDRAM   | 16        | 2.07%   |
| LPDDR3  | 16        | 2.07%   |
| DDR5    | 15        | 1.94%   |
| DDR     | 7         | 0.91%   |
| LPDDR5  | 6         | 0.78%   |
| DRAM    | 4         | 0.52%   |
| Unknown | 2         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 688       | 89.47%  |
| Row Of Chips | 72        | 9.36%   |
| DIMM         | 4         | 0.52%   |
| Unknown      | 4         | 0.52%   |
| Chip         | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 358       | 41.72%  |
| 4096    | 245       | 28.55%  |
| 16384   | 107       | 12.47%  |
| 2048    | 89        | 10.37%  |
| 32768   | 27        | 3.15%   |
| 1024    | 26        | 3.03%   |
| 1536    | 2         | 0.23%   |
| 512     | 2         | 0.23%   |
| 256     | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 200       | 24.21%  |
| 2667    | 176       | 21.31%  |
| 1600    | 167       | 20.22%  |
| 2400    | 64        | 7.75%   |
| 1334    | 35        | 4.24%   |
| 2133    | 32        | 3.87%   |
| 1333    | 26        | 3.15%   |
| Unknown | 23        | 2.78%   |
| 667     | 15        | 1.82%   |
| 4199    | 14        | 1.69%   |
| 1067    | 14        | 1.69%   |
| 4800    | 11        | 1.33%   |
| 4267    | 7         | 0.85%   |
| 4266    | 6         | 0.73%   |
| 800     | 5         | 0.61%   |
| 6400    | 4         | 0.48%   |
| 5600    | 4         | 0.48%   |
| 3266    | 4         | 0.48%   |
| 1867    | 4         | 0.48%   |
| 8400    | 3         | 0.36%   |
| 5500    | 2         | 0.24%   |
| 3733    | 2         | 0.24%   |
| 1066    | 2         | 0.24%   |
| 533     | 2         | 0.24%   |
| 2048    | 1         | 0.12%   |
| 1866    | 1         | 0.12%   |
| 1639    | 1         | 0.12%   |
| 975     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 33.33%  |
| Canon               | 4         | 33.33%  |
| Seiko Epson         | 2         | 16.67%  |
| Samsung Electronics | 1         | 8.33%   |
| QinHeng Electronics | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP Officejet 4500 G510g-m            | 2         | 16.67%  |
| Canon LBP6030w/6018w                 | 2         | 16.67%  |
| Seiko Epson L3110 Series             | 1         | 8.33%   |
| Seiko Epson FX-2190IIN               | 1         | 8.33%   |
| Samsung ML-216x Series Laser Printer | 1         | 8.33%   |
| QinHeng CH340S                       | 1         | 8.33%   |
| HP DeskJet 2600 series               | 1         | 8.33%   |
| HP Deskjet 1050 J410                 | 1         | 8.33%   |
| Canon PIXMA MX340                    | 1         | 8.33%   |
| Canon LBP6020                        | 1         | 8.33%   |

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
| Chicony Electronics                    | 314       | 24.51%  |
| IMC Networks                           | 156       | 12.18%  |
| Realtek Semiconductor                  | 120       | 9.37%   |
| Quanta                                 | 83        | 6.48%   |
| Microdia                               | 81        | 6.32%   |
| Bison Electronics                      | 80        | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 69        | 5.39%   |
| Sunplus Innovation Technology          | 50        | 3.9%    |
| Acer                                   | 45        | 3.51%   |
| Syntek                                 | 38        | 2.97%   |
| Suyin                                  | 34        | 2.65%   |
| Luxvisions Innotech Limited            | 28        | 2.19%   |
| Apple                                  | 27        | 2.11%   |
| Silicon Motion                         | 24        | 1.87%   |
| Lite-On Technology                     | 19        | 1.48%   |
| Alcor Micro                            | 17        | 1.33%   |
| Ricoh                                  | 12        | 0.94%   |
| Sonix Technology                       | 9         | 0.7%    |
| Importek                               | 9         | 0.7%    |
| Z-Star Microelectronics                | 8         | 0.62%   |
| ALi                                    | 7         | 0.55%   |
| Samsung Electronics                    | 6         | 0.47%   |
| Logitech                               | 4         | 0.31%   |
| SunplusIT                              | 3         | 0.23%   |
| Lenovo                                 | 3         | 0.23%   |
| Hy-UXGA(B5M2)-Camera                   | 3         | 0.23%   |
| Foxconn / Hon Hai                      | 3         | 0.23%   |
| Sunplus Technology                     | 2         | 0.16%   |
| Primax Electronics                     | 2         | 0.16%   |
| LG Electronics                         | 2         | 0.16%   |
| Generalplus Technology                 | 2         | 0.16%   |
| DigiTech                               | 2         | 0.16%   |
| 8SSC20F27114V1SR0BK1X4S                | 2         | 0.16%   |
| USB Camera                             | 1         | 0.08%   |
| Tripath Technology                     | 1         | 0.08%   |
| ShineTech                              | 1         | 0.08%   |
| Shine-optics                           | 1         | 0.08%   |
| Philips (or NXP)                       | 1         | 0.08%   |
| OmniVision Technologies                | 1         | 0.08%   |
| Novatek Microelectronics               | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                       | 47        | 3.66%   |
| Chicony Integrated Camera                               | 46        | 3.58%   |
| Microdia Integrated_Webcam_HD                           | 39        | 3.04%   |
| IMC Networks Integrated Camera                          | 39        | 3.04%   |
| Realtek Integrated_Webcam_HD                            | 29        | 2.26%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 29        | 2.26%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 28        | 2.18%   |
| Bison Integrated Camera                                 | 26        | 2.02%   |
| Chicony USB2.0 VGA UVC WebCam                           | 21        | 1.64%   |
| Syntek Integrated Camera                                | 20        | 1.56%   |
| Chicony USB2.0 Camera                                   | 17        | 1.32%   |
| Quanta HD User Facing                                   | 15        | 1.17%   |
| Chicony USB2.0 HD UVC WebCam                            | 15        | 1.17%   |
| IMC Networks HD Camera                                  | 14        | 1.09%   |
| Realtek USB2.0 VGA UVC WebCam                           | 13        | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                         | 13        | 1.01%   |
| Chicony USB 2.0 Camera                                  | 12        | 0.93%   |
| Chicony HP HD Camera                                    | 12        | 0.93%   |
| Realtek USB Camera                                      | 11        | 0.86%   |
| IMC Networks ov9734_azurewave_camera                    | 11        | 0.86%   |
| Sunplus Integrated_Webcam_HD                            | 10        | 0.78%   |
| Quanta ACER HD User Facing                              | 10        | 0.78%   |
| Lite-On Integrated Camera                               | 10        | 0.78%   |
| Chicony Lenovo EasyCamera                               | 10        | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 10        | 0.78%   |
| Bison Lenovo EasyCamera                                 | 10        | 0.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 10        | 0.78%   |
| Realtek USB2.0 HD UVC WebCam                            | 9         | 0.7%    |
| Quanta USB HD Webcam                                    | 9         | 0.7%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera    | 9         | 0.7%    |
| Chicony HD User Facing                                  | 9         | 0.7%    |
| Chicony EasyCamera                                      | 9         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera        | 9         | 0.7%    |
| Acer SunplusIT Integrated Camera                        | 9         | 0.7%    |
| Acer BisonCam, NB Pro                                   | 9         | 0.7%    |
| Syntek EasyCamera                                       | 8         | 0.62%   |
| Sunplus Asus Webcam                                     | 8         | 0.62%   |
| Realtek Integrated Webcam                               | 8         | 0.62%   |
| Quanta ov9734_techfront_camera                          | 8         | 0.62%   |
| Quanta HP TrueVision HD Camera                          | 8         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 67        | 38.07%  |
| Synaptics                          | 37        | 21.02%  |
| Validity Sensors                   | 35        | 19.89%  |
| LighTuning Technology              | 14        | 7.95%   |
| AuthenTec                          | 9         | 5.11%   |
| Upek                               | 8         | 4.55%   |
| Elan Microelectronics              | 5         | 2.84%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 51        | 28.98%  |
| Shenzhen Goodix Fingerprint Reader                              | 15        | 8.52%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 11        | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 8         | 4.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 8         | 4.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 6         | 3.41%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 6         | 3.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 6         | 3.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 6         | 3.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 2.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 5         | 2.84%   |
| Validity Sensors Fingerprint scanner                            | 4         | 2.27%   |
| Synaptics WBDI                                                  | 4         | 2.27%   |
| Synaptics  WBDI                                                 | 4         | 2.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 3         | 1.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 3         | 1.7%    |
| Elan ELAN:Fingerprint                                           | 3         | 1.7%    |
| AuthenTec AES2810                                               | 3         | 1.7%    |
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 1.7%    |
| AuthenTec AES1600                                               | 3         | 1.7%    |
| Validity Sensors VFS491                                         | 2         | 1.14%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 1.14%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 1.14%   |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 1.14%   |
| Elan ELAN:ARM-M4                                                | 2         | 1.14%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 0.57%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 0.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 0.57%   |
| Synaptics UWP WBDI Device                                       | 1         | 0.57%   |
| Synaptics UWP WBDI                                              | 1         | 0.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 0.57%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 0.57%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 0.57%   |
| LighTuning Fingerprint Reader                                   | 1         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 46.67%  |
| Alcor Micro           | 15        | 33.33%  |
| Advanced Card Systems | 3         | 6.67%   |
| Upek                  | 2         | 4.44%   |
| O2 Micro              | 2         | 4.44%   |
| Lenovo                | 1         | 2.22%   |
| Gemalto (was Gemplus) | 1         | 2.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 17.78%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 13.33%  |
| Broadcom 58200                                                               | 4         | 8.89%   |
| Broadcom 5880                                                                | 3         | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.44%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.44%   |
| Advanced Card Systems ACR39U                                                 | 2         | 4.44%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.22%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.22%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 924       | 63.81%  |
| 1     | 415       | 28.66%  |
| 2     | 90        | 6.22%   |
| 3     | 11        | 0.76%   |
| 4     | 5         | 0.35%   |
| 6     | 2         | 0.14%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 192       | 30.43%  |
| Fingerprint reader       | 176       | 27.89%  |
| Net/wireless             | 52        | 8.24%   |
| Camera                   | 44        | 6.97%   |
| Chipcard                 | 39        | 6.18%   |
| Multimedia controller    | 38        | 6.02%   |
| Bluetooth                | 33        | 5.23%   |
| Communication controller | 20        | 3.17%   |
| Net/ethernet             | 12        | 1.9%    |
| Storage                  | 9         | 1.43%   |
| Sound                    | 9         | 1.43%   |
| Flash memory             | 2         | 0.32%   |
| Card reader              | 2         | 0.32%   |
| Wireless                 | 1         | 0.16%   |
| Network                  | 1         | 0.16%   |
| Modem                    | 1         | 0.16%   |


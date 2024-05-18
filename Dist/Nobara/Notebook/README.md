Nobara - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Nobara.

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

Total: 539

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S510p 20298         | [b941b8d062](https://linux-hardware.org/?probe=b941b8d062) | May 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [84cc2abe63](https://linux-hardware.org/?probe=84cc2abe63) | May 06, 2024 |
| PC Special... | NH5x_7xDPx                  | [35a25ffdfd](https://linux-hardware.org/?probe=35a25ffdfd) | May 06, 2024 |
| Samsung       | 370E4K                      | [f0c626e7ca](https://linux-hardware.org/?probe=f0c626e7ca) | May 05, 2024 |
| Dell          | Inspiron 5502               | [43fee6a80f](https://linux-hardware.org/?probe=43fee6a80f) | May 05, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [55d15ed397](https://linux-hardware.org/?probe=55d15ed397) | May 05, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | [901ee2545c](https://linux-hardware.org/?probe=901ee2545c) | Apr 30, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | [a9b063c17b](https://linux-hardware.org/?probe=a9b063c17b) | Apr 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f619fc2cb1](https://linux-hardware.org/?probe=f619fc2cb1) | Apr 26, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [551ccdf911](https://linux-hardware.org/?probe=551ccdf911) | Apr 26, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [14164a1cf6](https://linux-hardware.org/?probe=14164a1cf6) | Apr 23, 2024 |
| HP            | 8876 11                     | [a276feeb19](https://linux-hardware.org/?probe=a276feeb19) | Apr 22, 2024 |
| HP            | 8876 11                     | [17290d87ba](https://linux-hardware.org/?probe=17290d87ba) | Apr 22, 2024 |
| Apple         | MacBookPro14,1              | [743a3ab71e](https://linux-hardware.org/?probe=743a3ab71e) | Apr 22, 2024 |
| HP            | EliteBook 8570p             | [98d15b6d8d](https://linux-hardware.org/?probe=98d15b6d8d) | Apr 20, 2024 |
| Apple         | MacBookPro16,1              | [af2c346bb9](https://linux-hardware.org/?probe=af2c346bb9) | Apr 20, 2024 |
| Notebook      | W330SU2                     | [7efde9ff70](https://linux-hardware.org/?probe=7efde9ff70) | Apr 20, 2024 |
| Dell          | Latitude E6440              | [82713456e1](https://linux-hardware.org/?probe=82713456e1) | Apr 19, 2024 |
| Acer          | Nitro AN517-52              | [da7720d0f0](https://linux-hardware.org/?probe=da7720d0f0) | Apr 16, 2024 |
| Acer          | Nitro AN517-52              | [a65d6b6abb](https://linux-hardware.org/?probe=a65d6b6abb) | Apr 16, 2024 |
| ASUSTek       | G751JM                      | [78bd2126e9](https://linux-hardware.org/?probe=78bd2126e9) | Apr 15, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [b160ab4b5b](https://linux-hardware.org/?probe=b160ab4b5b) | Apr 15, 2024 |
| Dell          | G15 5530                    | [8f4e471788](https://linux-hardware.org/?probe=8f4e471788) | Apr 14, 2024 |
| Unknown       | X570 Phantom Gaming-ITX/... | [44b48f5aa1](https://linux-hardware.org/?probe=44b48f5aa1) | Apr 13, 2024 |
| A-DATA Tec... | XENIA 15                    | [08552dc593](https://linux-hardware.org/?probe=08552dc593) | Apr 13, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1b09cf1322](https://linux-hardware.org/?probe=1b09cf1322) | Apr 10, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [46ec5edae0](https://linux-hardware.org/?probe=46ec5edae0) | Apr 10, 2024 |
| HP            | Laptop 15-fd0xxx            | [344cb034bc](https://linux-hardware.org/?probe=344cb034bc) | Apr 08, 2024 |
| System76      | Gazelle                     | [969d376558](https://linux-hardware.org/?probe=969d376558) | Apr 07, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [6c1225353c](https://linux-hardware.org/?probe=6c1225353c) | Apr 04, 2024 |
| MSI           | GF65 Thin 10UE              | [92304837ec](https://linux-hardware.org/?probe=92304837ec) | Apr 03, 2024 |
| Alienware     | 17 R4                       | [0c83302e22](https://linux-hardware.org/?probe=0c83302e22) | Apr 02, 2024 |
| HUAWEI        | BOM-WXX9                    | [55199df248](https://linux-hardware.org/?probe=55199df248) | Mar 31, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | [67f6104365](https://linux-hardware.org/?probe=67f6104365) | Mar 30, 2024 |
| HP            | EliteBook 840 G6            | [5750434b60](https://linux-hardware.org/?probe=5750434b60) | Mar 30, 2024 |
| Dell          | Inspiron 1750               | [0c73b8ab73](https://linux-hardware.org/?probe=0c73b8ab73) | Mar 29, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [d689049633](https://linux-hardware.org/?probe=d689049633) | Mar 28, 2024 |
| Lenovo        | ThinkPad P50 20EN001SUS     | [0d5d136c74](https://linux-hardware.org/?probe=0d5d136c74) | Mar 27, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 3 2... | [6ddc89666f](https://linux-hardware.org/?probe=6ddc89666f) | Mar 26, 2024 |
| THUNDEROBO... | 911 Plus                    | [26658bfa2e](https://linux-hardware.org/?probe=26658bfa2e) | Mar 25, 2024 |
| HP            | Pavilion Notebook           | [9599687d82](https://linux-hardware.org/?probe=9599687d82) | Mar 25, 2024 |
| Dell          | Latitude 3120               | [82d08cfae1](https://linux-hardware.org/?probe=82d08cfae1) | Mar 25, 2024 |
| Notebook      | W330SU2                     | [5228fe58bf](https://linux-hardware.org/?probe=5228fe58bf) | Mar 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [59e0f44e00](https://linux-hardware.org/?probe=59e0f44e00) | Mar 23, 2024 |
| Lenovo        | ThinkPad P50 20EN001SUS     | [42607732cf](https://linux-hardware.org/?probe=42607732cf) | Mar 23, 2024 |
| Apple         | MacBookAir8,1               | [d0c0446bb2](https://linux-hardware.org/?probe=d0c0446bb2) | Mar 19, 2024 |
| Acer          | TM8573T                     | [f60d5f0213](https://linux-hardware.org/?probe=f60d5f0213) | Mar 18, 2024 |
| A-DATA Tec... | XENIA 15                    | [0abdf7ee8f](https://linux-hardware.org/?probe=0abdf7ee8f) | Mar 14, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [34dc8eb985](https://linux-hardware.org/?probe=34dc8eb985) | Mar 09, 2024 |
| Genuine       | ZEUS 15H (GNB15H-9G650)     | [1cdfbc79db](https://linux-hardware.org/?probe=1cdfbc79db) | Mar 09, 2024 |
| HP            | Pavilion Notebook           | [4e9cbe8d8c](https://linux-hardware.org/?probe=4e9cbe8d8c) | Mar 07, 2024 |
| HUAWEI        | BOD-WXX9                    | [1fc0257c17](https://linux-hardware.org/?probe=1fc0257c17) | Mar 05, 2024 |
| HP            | 14                          | [6e6138e521](https://linux-hardware.org/?probe=6e6138e521) | Mar 04, 2024 |
| Dell          | Latitude 3540               | [bec924d898](https://linux-hardware.org/?probe=bec924d898) | Mar 02, 2024 |
| HP            | Pavilion 15                 | [15858caed0](https://linux-hardware.org/?probe=15858caed0) | Mar 01, 2024 |
| ASUSTek       | G73Sw                       | [4587c66de2](https://linux-hardware.org/?probe=4587c66de2) | Mar 01, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [fd1c373201](https://linux-hardware.org/?probe=fd1c373201) | Mar 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [120d90cd85](https://linux-hardware.org/?probe=120d90cd85) | Mar 01, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [08024a8cef](https://linux-hardware.org/?probe=08024a8cef) | Mar 01, 2024 |
| Valve         | Jupiter                     | [aabae1e88f](https://linux-hardware.org/?probe=aabae1e88f) | Mar 01, 2024 |
| ASUSTek       | G73Sw                       | [3605d5ddc7](https://linux-hardware.org/?probe=3605d5ddc7) | Mar 01, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [18a5671738](https://linux-hardware.org/?probe=18a5671738) | Feb 29, 2024 |
| MSI           | Modern 14 B5M               | [565e6c2d46](https://linux-hardware.org/?probe=565e6c2d46) | Feb 29, 2024 |
| Gigabyte      | B85M-D3H                    | [dbbdc72e8a](https://linux-hardware.org/?probe=dbbdc72e8a) | Feb 27, 2024 |
| Dell          | Latitude E5470              | [10ab411f6f](https://linux-hardware.org/?probe=10ab411f6f) | Feb 25, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [3015e2635f](https://linux-hardware.org/?probe=3015e2635f) | Feb 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [987f6afe4b](https://linux-hardware.org/?probe=987f6afe4b) | Feb 25, 2024 |
| HP            | ProBook 470 G1              | [2ad493fb2d](https://linux-hardware.org/?probe=2ad493fb2d) | Feb 24, 2024 |
| HP            | Laptop 14-dk0xxx            | [e0a472d706](https://linux-hardware.org/?probe=e0a472d706) | Feb 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3b3a145c76](https://linux-hardware.org/?probe=3b3a145c76) | Feb 23, 2024 |
| Acer          | Aspire VN7-592G             | [dd6617c3d7](https://linux-hardware.org/?probe=dd6617c3d7) | Feb 23, 2024 |
| A-DATA Tec... | XENIA 15                    | [6a3f5e5947](https://linux-hardware.org/?probe=6a3f5e5947) | Feb 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [da357b8940](https://linux-hardware.org/?probe=da357b8940) | Feb 22, 2024 |
| Acer          | Nitro AN517-52              | [a5af54a5aa](https://linux-hardware.org/?probe=a5af54a5aa) | Feb 20, 2024 |
| MSI           | Bravo 15 C7VF               | [82ee626dbd](https://linux-hardware.org/?probe=82ee626dbd) | Feb 19, 2024 |
| Acer          | Aspire ES1-572              | [7c61f04e95](https://linux-hardware.org/?probe=7c61f04e95) | Feb 18, 2024 |
| Acer          | Nitro AN515-44              | [f5476226be](https://linux-hardware.org/?probe=f5476226be) | Feb 15, 2024 |
| Dell          | Precision M4800             | [c5630bb66f](https://linux-hardware.org/?probe=c5630bb66f) | Feb 15, 2024 |
| Infinix       | INBOOK X2 PLUS              | [ef58804464](https://linux-hardware.org/?probe=ef58804464) | Feb 15, 2024 |
| Infinix       | INBOOK X2 PLUS              | [bf574e4c09](https://linux-hardware.org/?probe=bf574e4c09) | Feb 15, 2024 |
| Dell          | XPS 13 9305                 | [cf602689fb](https://linux-hardware.org/?probe=cf602689fb) | Feb 14, 2024 |
| Dell          | XPS 13 9305                 | [531e1ffb52](https://linux-hardware.org/?probe=531e1ffb52) | Feb 14, 2024 |
| Acer          | Nitro AN515-44              | [1edc94c98a](https://linux-hardware.org/?probe=1edc94c98a) | Feb 14, 2024 |
| Acer          | Aspire A115-31              | [118a35f68d](https://linux-hardware.org/?probe=118a35f68d) | Feb 13, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [8cab6ebd29](https://linux-hardware.org/?probe=8cab6ebd29) | Feb 12, 2024 |
| HP            | Compaq 615                  | [1761631f89](https://linux-hardware.org/?probe=1761631f89) | Feb 11, 2024 |
| Acer          | TravelMate 7520             | [2cdca7160b](https://linux-hardware.org/?probe=2cdca7160b) | Feb 11, 2024 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [9b3e403b41](https://linux-hardware.org/?probe=9b3e403b41) | Feb 11, 2024 |
| Lenovo        | Z50-70 20354                | [9ceb699fc1](https://linux-hardware.org/?probe=9ceb699fc1) | Feb 07, 2024 |
| Lenovo        | Z50-70 20354                | [021c8aa71a](https://linux-hardware.org/?probe=021c8aa71a) | Feb 07, 2024 |
| Dell          | Precision M4800             | [8b1cccf4c2](https://linux-hardware.org/?probe=8b1cccf4c2) | Feb 07, 2024 |
| Lenovo        | G500 20236                  | [ef9f082a81](https://linux-hardware.org/?probe=ef9f082a81) | Feb 03, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d2b295447b](https://linux-hardware.org/?probe=d2b295447b) | Feb 03, 2024 |
| Toshiba       | Satellite L55-C             | [f32d9dc51a](https://linux-hardware.org/?probe=f32d9dc51a) | Feb 02, 2024 |
| Acer          | Aspire A315-54              | [3621142f4d](https://linux-hardware.org/?probe=3621142f4d) | Feb 02, 2024 |
| HP            | 240 G8 Notebook PC          | [d4c61a6527](https://linux-hardware.org/?probe=d4c61a6527) | Feb 01, 2024 |
| Lenovo        | G500 20236                  | [8b5fd80f76](https://linux-hardware.org/?probe=8b5fd80f76) | Feb 01, 2024 |
| Lenovo        | G500 20236                  | [31fc253b87](https://linux-hardware.org/?probe=31fc253b87) | Feb 01, 2024 |
| HP            | 240 G8 Notebook PC          | [02a1844f63](https://linux-hardware.org/?probe=02a1844f63) | Jan 31, 2024 |
| Toshiba       | Satellite C55-B             | [cfd7031cd9](https://linux-hardware.org/?probe=cfd7031cd9) | Jan 31, 2024 |
| MSI           | GE62 6QE                    | [6d6f9ba002](https://linux-hardware.org/?probe=6d6f9ba002) | Jan 30, 2024 |
| Lenovo        | IdeaPad Z500 20202          | [88efa5aca1](https://linux-hardware.org/?probe=88efa5aca1) | Jan 27, 2024 |
| HP            | 240 G8 Notebook PC          | [68364930e7](https://linux-hardware.org/?probe=68364930e7) | Jan 27, 2024 |
| HP            | Laptop 14s-fq0xxx           | [96bce63bad](https://linux-hardware.org/?probe=96bce63bad) | Jan 27, 2024 |
| Unknown       | Unknown                     | [9e979ee4e4](https://linux-hardware.org/?probe=9e979ee4e4) | Jan 26, 2024 |
| Unknown       | Unknown                     | [3e9fd3e31a](https://linux-hardware.org/?probe=3e9fd3e31a) | Jan 26, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | [ec87598c40](https://linux-hardware.org/?probe=ec87598c40) | Jan 26, 2024 |
| Gigabyte      | H510M H                     | [88b87b3353](https://linux-hardware.org/?probe=88b87b3353) | Jan 22, 2024 |
| HP            | Laptop 17z-cp000            | [51e7d942bc](https://linux-hardware.org/?probe=51e7d942bc) | Jan 22, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [871f86a545](https://linux-hardware.org/?probe=871f86a545) | Jan 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e07a558ed5](https://linux-hardware.org/?probe=e07a558ed5) | Jan 20, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [12e32cbc19](https://linux-hardware.org/?probe=12e32cbc19) | Jan 19, 2024 |
| Gigabyte      | A5 K1                       | [219882fa36](https://linux-hardware.org/?probe=219882fa36) | Jan 19, 2024 |
| Gigabyte      | A5 K1                       | [2270b0b961](https://linux-hardware.org/?probe=2270b0b961) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [96aa415cee](https://linux-hardware.org/?probe=96aa415cee) | Jan 18, 2024 |
| Lenovo        | ThinkPad X131e 3371AF5      | [1741e3b346](https://linux-hardware.org/?probe=1741e3b346) | Jan 18, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c8e849a73](https://linux-hardware.org/?probe=0c8e849a73) | Jan 15, 2024 |
| Digibras      | NH4CU03                     | [7cccdf824c](https://linux-hardware.org/?probe=7cccdf824c) | Jan 13, 2024 |
| A-DATA Tec... | XENIA 15                    | [e1560ce8a3](https://linux-hardware.org/?probe=e1560ce8a3) | Jan 13, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | [e4f7fe0969](https://linux-hardware.org/?probe=e4f7fe0969) | Jan 13, 2024 |
| ASRock        | X570 Steel Legend           | [2dc1dca01f](https://linux-hardware.org/?probe=2dc1dca01f) | Jan 13, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8e72c34b9e](https://linux-hardware.org/?probe=8e72c34b9e) | Jan 11, 2024 |
| HP            | Laptop 15s-eq2xxx           | [b0705704b0](https://linux-hardware.org/?probe=b0705704b0) | Jan 11, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [0df1250b28](https://linux-hardware.org/?probe=0df1250b28) | Jan 10, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [9cfcebcd8c](https://linux-hardware.org/?probe=9cfcebcd8c) | Jan 09, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [0306a42404](https://linux-hardware.org/?probe=0306a42404) | Jan 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [91485ca232](https://linux-hardware.org/?probe=91485ca232) | Jan 09, 2024 |
| Dell          | Latitude E6440              | [bb917628b1](https://linux-hardware.org/?probe=bb917628b1) | Jan 09, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [513efe6ed6](https://linux-hardware.org/?probe=513efe6ed6) | Jan 09, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | [9ff97bbae7](https://linux-hardware.org/?probe=9ff97bbae7) | Jan 09, 2024 |
| HP            | ENVY TS 14 Sleekbook        | [48871db703](https://linux-hardware.org/?probe=48871db703) | Jan 08, 2024 |
| Apple         | MacBookPro8,3               | [4e246bdbaa](https://linux-hardware.org/?probe=4e246bdbaa) | Jan 07, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | [b753b7e847](https://linux-hardware.org/?probe=b753b7e847) | Jan 06, 2024 |
| Apple         | MacBookPro8,3               | [6ced1e30f9](https://linux-hardware.org/?probe=6ced1e30f9) | Jan 06, 2024 |
| Dell          | G7 7700                     | [126b71c515](https://linux-hardware.org/?probe=126b71c515) | Jan 05, 2024 |
| Dell          | XPS 13 9360                 | [6971ec53cd](https://linux-hardware.org/?probe=6971ec53cd) | Jan 05, 2024 |
| Notebook      | P7xxTM1                     | [9ed3be2a69](https://linux-hardware.org/?probe=9ed3be2a69) | Jan 04, 2024 |
| HP            | Pavilion Notebook           | [bb19b91823](https://linux-hardware.org/?probe=bb19b91823) | Jan 04, 2024 |
| Acer          | Aspire A315-54              | [50c718d2c6](https://linux-hardware.org/?probe=50c718d2c6) | Jan 04, 2024 |
| ASUSTek       | Q500A                       | [c3f961d8be](https://linux-hardware.org/?probe=c3f961d8be) | Jan 03, 2024 |
| Monster       | ABRA A5 V13.4               | [8cb3a2ee0a](https://linux-hardware.org/?probe=8cb3a2ee0a) | Dec 30, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ebdb840dba](https://linux-hardware.org/?probe=ebdb840dba) | Dec 30, 2023 |
| HP            | Laptop 15-db0xxx            | [bacd120c51](https://linux-hardware.org/?probe=bacd120c51) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | [274f6e86fc](https://linux-hardware.org/?probe=274f6e86fc) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [988bd71a05](https://linux-hardware.org/?probe=988bd71a05) | Dec 29, 2023 |
| HP            | Laptop 14-dk0xxx            | [754b2e0faf](https://linux-hardware.org/?probe=754b2e0faf) | Dec 27, 2023 |
| HP            | Laptop 14-dk0xxx            | [be356bc929](https://linux-hardware.org/?probe=be356bc929) | Dec 27, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [18788fe1ea](https://linux-hardware.org/?probe=18788fe1ea) | Dec 22, 2023 |
| Dell          | G3 3590                     | [15decf2dfc](https://linux-hardware.org/?probe=15decf2dfc) | Dec 18, 2023 |
| HP            | Pavilion dv5                | [cf88cdfeb2](https://linux-hardware.org/?probe=cf88cdfeb2) | Dec 18, 2023 |
| Acer          | Aspire A515-56T             | [9579acc8a0](https://linux-hardware.org/?probe=9579acc8a0) | Dec 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [6855d17ce1](https://linux-hardware.org/?probe=6855d17ce1) | Dec 14, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2c8846a637](https://linux-hardware.org/?probe=2c8846a637) | Dec 12, 2023 |
| Dell          | G7 7700                     | [9d4e191ab5](https://linux-hardware.org/?probe=9d4e191ab5) | Dec 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [f49dd0f010](https://linux-hardware.org/?probe=f49dd0f010) | Dec 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [bc8d773d9d](https://linux-hardware.org/?probe=bc8d773d9d) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [04e25c9660](https://linux-hardware.org/?probe=04e25c9660) | Dec 10, 2023 |
| Gigabyte      | G5 GE                       | [e63d83327b](https://linux-hardware.org/?probe=e63d83327b) | Dec 09, 2023 |
| Dell          | G5 5505                     | [74d0a53db4](https://linux-hardware.org/?probe=74d0a53db4) | Dec 06, 2023 |
| Exo           | Smart XQ7                   | [f1ebc77dfc](https://linux-hardware.org/?probe=f1ebc77dfc) | Dec 05, 2023 |
| Exo           | Smart XQ7                   | [3d56eb720e](https://linux-hardware.org/?probe=3d56eb720e) | Dec 05, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [6cd3d66979](https://linux-hardware.org/?probe=6cd3d66979) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [e9e31f8aaa](https://linux-hardware.org/?probe=e9e31f8aaa) | Dec 03, 2023 |
| GPU Compan... | GWNR71517                   | [4f3cfed57b](https://linux-hardware.org/?probe=4f3cfed57b) | Dec 02, 2023 |
| Acer          | Aspire E5-473               | [f3b2c01ef7](https://linux-hardware.org/?probe=f3b2c01ef7) | Dec 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [37545bd915](https://linux-hardware.org/?probe=37545bd915) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d385ea9309](https://linux-hardware.org/?probe=d385ea9309) | Nov 29, 2023 |
| Acer          | Aspire E5-575               | [b4fbd61258](https://linux-hardware.org/?probe=b4fbd61258) | Nov 28, 2023 |
| Dell          | Precision 7740              | [50b0f0be08](https://linux-hardware.org/?probe=50b0f0be08) | Nov 25, 2023 |
| Dell          | Inspiron 15 3520            | [4f1d1d579c](https://linux-hardware.org/?probe=4f1d1d579c) | Nov 24, 2023 |
| ASRock        | X370 Gaming X               | [0c39910834](https://linux-hardware.org/?probe=0c39910834) | Nov 23, 2023 |
| Dell          | Latitude E6430              | [dc02cb2409](https://linux-hardware.org/?probe=dc02cb2409) | Nov 20, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [1048b240d5](https://linux-hardware.org/?probe=1048b240d5) | Nov 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [74162bf452](https://linux-hardware.org/?probe=74162bf452) | Nov 19, 2023 |
| LG Electro... | 16Z90R-G.AD75F              | [83d650792f](https://linux-hardware.org/?probe=83d650792f) | Nov 18, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [adf1b0c27a](https://linux-hardware.org/?probe=adf1b0c27a) | Nov 16, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [168e0af4e6](https://linux-hardware.org/?probe=168e0af4e6) | Nov 16, 2023 |
| MSI           | Cyborg 15 A12VF             | [ca5d20d4a4](https://linux-hardware.org/?probe=ca5d20d4a4) | Nov 16, 2023 |
| MSI           | Cyborg 15 A12VF             | [914e24f740](https://linux-hardware.org/?probe=914e24f740) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [aca7636589](https://linux-hardware.org/?probe=aca7636589) | Nov 16, 2023 |
| MSI           | GF62 8RC                    | [8e186cf8b9](https://linux-hardware.org/?probe=8e186cf8b9) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [7856865861](https://linux-hardware.org/?probe=7856865861) | Nov 16, 2023 |
| HP            | Pavilion dv9700             | [0b039b15e7](https://linux-hardware.org/?probe=0b039b15e7) | Nov 15, 2023 |
| HP            | Pavilion dv9700             | [b5e651a2bf](https://linux-hardware.org/?probe=b5e651a2bf) | Nov 15, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [f0db6bb1ae](https://linux-hardware.org/?probe=f0db6bb1ae) | Nov 11, 2023 |
| Chuwi         | GemiBook Pro                | [9f1e875996](https://linux-hardware.org/?probe=9f1e875996) | Nov 07, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [12b6cd2d09](https://linux-hardware.org/?probe=12b6cd2d09) | Nov 04, 2023 |
| Dell          | Precision 7740              | [71b262696a](https://linux-hardware.org/?probe=71b262696a) | Nov 02, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | [b89ceef38d](https://linux-hardware.org/?probe=b89ceef38d) | Nov 01, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [70e4b3b007](https://linux-hardware.org/?probe=70e4b3b007) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [352bf34e3b](https://linux-hardware.org/?probe=352bf34e3b) | Oct 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0eae5ed294](https://linux-hardware.org/?probe=0eae5ed294) | Oct 31, 2023 |
| System76      | Gazelle                     | [3bc4a66a13](https://linux-hardware.org/?probe=3bc4a66a13) | Oct 29, 2023 |
| HP            | Notebook                    | [b6f188a1fe](https://linux-hardware.org/?probe=b6f188a1fe) | Oct 27, 2023 |
| Dell          | Latitude E5470              | [fbbcdd8d9f](https://linux-hardware.org/?probe=fbbcdd8d9f) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [3d7ad8a1d6](https://linux-hardware.org/?probe=3d7ad8a1d6) | Oct 26, 2023 |
| Dell          | Latitude E5470              | [cac52e6eaf](https://linux-hardware.org/?probe=cac52e6eaf) | Oct 25, 2023 |
| ASUSTek       | GL502VSK                    | [5f455e693f](https://linux-hardware.org/?probe=5f455e693f) | Oct 24, 2023 |
| Dell          | Inspiron 7375               | [451317bd25](https://linux-hardware.org/?probe=451317bd25) | Oct 22, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [fa46708f8f](https://linux-hardware.org/?probe=fa46708f8f) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| Lenovo        | ThinkPad T450 20BUS1K50X    | [11ccdc870b](https://linux-hardware.org/?probe=11ccdc870b) | Oct 16, 2023 |
| ASUSTek       | X541UV                      | [c5183a57ce](https://linux-hardware.org/?probe=c5183a57ce) | Oct 16, 2023 |
| MSI           | GT72S 6QE                   | [9a2d87eb4c](https://linux-hardware.org/?probe=9a2d87eb4c) | Oct 12, 2023 |
| MSI           | GT72S 6QE                   | [4927bfc263](https://linux-hardware.org/?probe=4927bfc263) | Oct 12, 2023 |
| Toshiba       | Satellite C55D-C            | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| Acer          | Aspire A315-42              | [c0e071789f](https://linux-hardware.org/?probe=c0e071789f) | Oct 09, 2023 |
| Acer          | Aspire A315-41              | [85d999063f](https://linux-hardware.org/?probe=85d999063f) | Oct 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e087628f2a](https://linux-hardware.org/?probe=e087628f2a) | Oct 07, 2023 |
| MSI           | Modern 14 B5M               | [65ae20098f](https://linux-hardware.org/?probe=65ae20098f) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81JN     | [747f0d45fe](https://linux-hardware.org/?probe=747f0d45fe) | Sep 28, 2023 |
| Acer          | Nitro AN515-42              | [dd4a3f701c](https://linux-hardware.org/?probe=dd4a3f701c) | Sep 27, 2023 |
| Dell          | G5 5505                     | [787ccf4559](https://linux-hardware.org/?probe=787ccf4559) | Sep 25, 2023 |
| GPU Compan... | GWNR71517                   | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| HP            | Victus by Gaming Laptop ... | [d21f140b5e](https://linux-hardware.org/?probe=d21f140b5e) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | [c40dbfbd1d](https://linux-hardware.org/?probe=c40dbfbd1d) | Sep 23, 2023 |
| Dell          | G3 3579                     | [eff563e086](https://linux-hardware.org/?probe=eff563e086) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [4c854cc233](https://linux-hardware.org/?probe=4c854cc233) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [cd2fb41835](https://linux-hardware.org/?probe=cd2fb41835) | Sep 15, 2023 |
| Dell          | Latitude E6440              | [591c479a8d](https://linux-hardware.org/?probe=591c479a8d) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3900a91c0b](https://linux-hardware.org/?probe=3900a91c0b) | Sep 03, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [0bda6b93da](https://linux-hardware.org/?probe=0bda6b93da) | Aug 27, 2023 |
| ASUSTek       | G751JM                      | [7cdb0c52e4](https://linux-hardware.org/?probe=7cdb0c52e4) | Aug 23, 2023 |
| Acer          | Nitro AN515-56              | [530e70e1ab](https://linux-hardware.org/?probe=530e70e1ab) | Aug 22, 2023 |
| Acer          | Nitro AN515-56              | [45264bf6e6](https://linux-hardware.org/?probe=45264bf6e6) | Aug 20, 2023 |
| Infinix       | INBOOK X2 GEN11             | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | [9c5e7cc1fb](https://linux-hardware.org/?probe=9c5e7cc1fb) | Aug 16, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [da3036b8e3](https://linux-hardware.org/?probe=da3036b8e3) | Aug 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [f9d07e4f97](https://linux-hardware.org/?probe=f9d07e4f97) | Aug 12, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [ecbc3827d1](https://linux-hardware.org/?probe=ecbc3827d1) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3a7d1d1f9b](https://linux-hardware.org/?probe=3a7d1d1f9b) | Aug 11, 2023 |
| Dell          | Inspiron 3180               | [40c31ab8e5](https://linux-hardware.org/?probe=40c31ab8e5) | Aug 11, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d6b7da58e7](https://linux-hardware.org/?probe=d6b7da58e7) | Aug 08, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | [101c521941](https://linux-hardware.org/?probe=101c521941) | Aug 08, 2023 |
| Micro Comp... | NUCXI7                      | [96d3ade9eb](https://linux-hardware.org/?probe=96d3ade9eb) | Aug 07, 2023 |
| Lenovo        | ThinkPad T450 20BUS3ES0A    | [1038e99486](https://linux-hardware.org/?probe=1038e99486) | Aug 04, 2023 |
| Dell          | Inspiron 15 3520            | [49cbe32874](https://linux-hardware.org/?probe=49cbe32874) | Jul 28, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| Dell          | Inspiron 15 3520            | [319cb6659d](https://linux-hardware.org/?probe=319cb6659d) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| Toshiba       | Satellite S55t-C            | [be8777b248](https://linux-hardware.org/?probe=be8777b248) | Jul 17, 2023 |
| Acer          | Predator PH315-52           | [8231c1b7c0](https://linux-hardware.org/?probe=8231c1b7c0) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | [91f38d0ab5](https://linux-hardware.org/?probe=91f38d0ab5) | Jul 16, 2023 |
| Acer          | Nitro AN515-54              | [ac55f32c4e](https://linux-hardware.org/?probe=ac55f32c4e) | Jul 16, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| MSI           | GT70 2PE                    | [9e49d96293](https://linux-hardware.org/?probe=9e49d96293) | Jul 13, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [f273c7ffee](https://linux-hardware.org/?probe=f273c7ffee) | Jul 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| Dell          | G7 7790                     | [a6dd0d72f7](https://linux-hardware.org/?probe=a6dd0d72f7) | Jul 06, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [afa2978397](https://linux-hardware.org/?probe=afa2978397) | Jul 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9472db0bf4](https://linux-hardware.org/?probe=9472db0bf4) | Jul 04, 2023 |
| Dell          | Latitude E5440              | [03ed0e9ebb](https://linux-hardware.org/?probe=03ed0e9ebb) | Jul 03, 2023 |
| ASUSTek       | X541SA                      | [be7a8d9ce0](https://linux-hardware.org/?probe=be7a8d9ce0) | Jul 02, 2023 |
| Dell          | G7 7790                     | [6345fbbe32](https://linux-hardware.org/?probe=6345fbbe32) | Jul 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c1051d3ef0](https://linux-hardware.org/?probe=c1051d3ef0) | Jul 01, 2023 |
| HP            | ProBook 650 G1              | [593959e6f3](https://linux-hardware.org/?probe=593959e6f3) | Jun 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [bbd5ba331d](https://linux-hardware.org/?probe=bbd5ba331d) | Jun 30, 2023 |
| Lenovo        | G50-80 80L0                 | [9979e7a733](https://linux-hardware.org/?probe=9979e7a733) | Jun 29, 2023 |
| Apple         | MacBookPro8,3               | [4846eae54f](https://linux-hardware.org/?probe=4846eae54f) | Jun 28, 2023 |
| Apple         | MacBookPro8,3               | [f5c922b6d3](https://linux-hardware.org/?probe=f5c922b6d3) | Jun 28, 2023 |
| Dell          | Inspiron 15 3520            | [c77b479e22](https://linux-hardware.org/?probe=c77b479e22) | Jun 27, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | [5e67041129](https://linux-hardware.org/?probe=5e67041129) | Jun 26, 2023 |
| Google        | Blooglet                    | [88fae074d1](https://linux-hardware.org/?probe=88fae074d1) | Jun 25, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | [305e202fd3](https://linux-hardware.org/?probe=305e202fd3) | Jun 22, 2023 |
| MSI           | GT70 2OC/2OD                | [d8d81f0614](https://linux-hardware.org/?probe=d8d81f0614) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | [f7a3caaef1](https://linux-hardware.org/?probe=f7a3caaef1) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | [f11d231c6a](https://linux-hardware.org/?probe=f11d231c6a) | Jun 20, 2023 |
| Timi          | A30                         | [34d77f385a](https://linux-hardware.org/?probe=34d77f385a) | Jun 19, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | [10cf405f89](https://linux-hardware.org/?probe=10cf405f89) | Jun 17, 2023 |
| Dell          | Precision 7510              | [cbbfdafd46](https://linux-hardware.org/?probe=cbbfdafd46) | Jun 17, 2023 |
| Google        | Blooglet                    | [80ce635393](https://linux-hardware.org/?probe=80ce635393) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [42722d78d8](https://linux-hardware.org/?probe=42722d78d8) | Jun 10, 2023 |
| Infinix       | INBook X1 Pro               | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| ASUSTek       | X550JK                      | [ae3bf8f79c](https://linux-hardware.org/?probe=ae3bf8f79c) | Jun 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Alienware     | m17 R5 AMD                  | [f5eeb72c4d](https://linux-hardware.org/?probe=f5eeb72c4d) | May 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0cb4af5367](https://linux-hardware.org/?probe=0cb4af5367) | May 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S06Q0... | [e54e204b28](https://linux-hardware.org/?probe=e54e204b28) | May 29, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | [9496942a44](https://linux-hardware.org/?probe=9496942a44) | May 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0aba7a98b9](https://linux-hardware.org/?probe=0aba7a98b9) | May 24, 2023 |
| Packard Be... | EasyNote LS11HR             | [a5df8ea9d7](https://linux-hardware.org/?probe=a5df8ea9d7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d1c4b3ee44](https://linux-hardware.org/?probe=d1c4b3ee44) | May 22, 2023 |
| Lenovo        | ThinkPad X140e 20BLS0040... | [1e648e8f50](https://linux-hardware.org/?probe=1e648e8f50) | May 21, 2023 |
| Apple         | MacBookPro8,1               | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| HP            | Pavilion 15                 | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [71f1904bc6](https://linux-hardware.org/?probe=71f1904bc6) | May 13, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d2d1037c9d](https://linux-hardware.org/?probe=d2d1037c9d) | May 09, 2023 |
| HP            | Laptop 17-ca1xxx            | [5c506f94e0](https://linux-hardware.org/?probe=5c506f94e0) | May 05, 2023 |
| Samsung       | 535U3C                      | [5f2e46be0a](https://linux-hardware.org/?probe=5f2e46be0a) | May 05, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [b54238dc33](https://linux-hardware.org/?probe=b54238dc33) | May 01, 2023 |
| HP            | Unknown                     | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [fc22fb4921](https://linux-hardware.org/?probe=fc22fb4921) | Apr 23, 2023 |
| Acer          | Nitro AN515-52              | [e3dc4788e7](https://linux-hardware.org/?probe=e3dc4788e7) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | [edf0d6d941](https://linux-hardware.org/?probe=edf0d6d941) | Apr 21, 2023 |
| Apple         | MacBookPro8,3               | [4004491274](https://linux-hardware.org/?probe=4004491274) | Apr 21, 2023 |
| Fujitsu       | LIFEBOOK A557               | [712657fa81](https://linux-hardware.org/?probe=712657fa81) | Apr 20, 2023 |
| Dell          | Vostro 7590                 | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| GEO           | GeoBook 120                 | [2e51a1bab5](https://linux-hardware.org/?probe=2e51a1bab5) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Unknown       | ACB20                       | [16543ac693](https://linux-hardware.org/?probe=16543ac693) | Apr 12, 2023 |
| Unknown       | ACB20                       | [4c0422096b](https://linux-hardware.org/?probe=4c0422096b) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
| Unknown       | ACB20                       | [6e70bacda5](https://linux-hardware.org/?probe=6e70bacda5) | Apr 01, 2023 |
| Gigabyte      | AERO 15 XD                  | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| ASUSTek       | GL752VW                     | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Intel         | powered classmate PC        | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| Lenovo        | Unknown                     | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| Acer          | Nitro AN515-52              | [6ad4034797](https://linux-hardware.org/?probe=6ad4034797) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7e6ae6ba16](https://linux-hardware.org/?probe=7e6ae6ba16) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | X580VD                      | [8c4023bd5d](https://linux-hardware.org/?probe=8c4023bd5d) | Mar 16, 2023 |
| ASUSTek       | X580VD                      | [26b62abfc9](https://linux-hardware.org/?probe=26b62abfc9) | Mar 16, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [7637d41bf3](https://linux-hardware.org/?probe=7637d41bf3) | Mar 14, 2023 |
| Dell          | Vostro 3400                 | [01bfc3e026](https://linux-hardware.org/?probe=01bfc3e026) | Mar 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| Dell          | Vostro 3400                 | [ed7724b921](https://linux-hardware.org/?probe=ed7724b921) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | [6605d9e257](https://linux-hardware.org/?probe=6605d9e257) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0c14a418fb](https://linux-hardware.org/?probe=0c14a418fb) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [aa31db4d3f](https://linux-hardware.org/?probe=aa31db4d3f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| HP            | ZBook 17                    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Acer          | Aspire A515-51              | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| HP            | ZBook 17 G2                 | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Dell          | Latitude 7390               | [892100e074](https://linux-hardware.org/?probe=892100e074) | Mar 05, 2023 |
| Acer          | Aspire VX5-591G             | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| MSI           | GP65 Leopard 9SF            | [45f56a0c5b](https://linux-hardware.org/?probe=45f56a0c5b) | Mar 03, 2023 |
| Schenker      | XMG NEO (M19, RTX 2070)     | [c45dbeb188](https://linux-hardware.org/?probe=c45dbeb188) | Mar 02, 2023 |
| MSI           | P65 Creator 8RD             | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Dell          | Inspiron 3542               | [686db926da](https://linux-hardware.org/?probe=686db926da) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| Sony          | SVF1521N6EW                 | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Dell          | G3 3590                     | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | ENVY 15                     | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| HP            | EliteBook Revolve 810 G1    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| Dell          | Inspiron 5555               | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| Acer          | TravelMate P256-M           | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | K52Jc                       | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | Katana GF76 11UD            | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| Apple         | MacBook5,1                  | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| Medion        | GUARDIAN X10                | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| Unknown       | X570 Phantom Gaming-ITX/... | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | EliteBook 8570p             | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| Dynabook      | PORTEGE X30L-K              | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| Lenovo        | Z50-70 20354                | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| HP            | Laptop 14-cm1xxx            | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| Valve         | Jupiter                     | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Coradir       | Coradir/ES10IS5             | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Dell          | Studio 1737                 | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Acer          | Swift SFX14-41G             | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ASUSTek       | GL753VD                     | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| ASUSTek       | GL502VMK                    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Toshiba       | Satellite L850              | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| Casper        | EXCALIBUR G770              | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| HP            | 2000                        | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| Apple         | MacBookPro5,5               | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| HP            | 2000                        | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| Acer          | Aspire VX5-591G             | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Dell          | Inspiron 3542               | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| Gateway       | NE56R                       | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| Alienware     | Area-51m R2 A00             | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| ASUSTek       | TP500LA                     | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| Dell          | G15 5511                    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| Notebook      | P7xxDM2(-G)                 | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Apple         | MacBookPro14,2              | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| Razer         | Blade                       | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Nobara/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Nobara 36 | 113       | 27.36%  |
| Nobara 37 | 111       | 26.88%  |
| Nobara 39 | 97        | 23.49%  |
| Nobara 38 | 92        | 22.28%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Nobara | 399       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 6.7.0-204.fsync.fc39.x86_64   | 34        | 7.91%   |
| 6.0.10-201.fc36.x86_64        | 19        | 4.42%   |
| 6.4.10-202.fsync.fc38.x86_64  | 18        | 4.19%   |
| 6.7.6-201.fsync.fc39.x86_64   | 16        | 3.72%   |
| 5.19.14-201.fsync.fc36.x86_64 | 16        | 3.72%   |
| 6.1.11-201.fsync.fc37.x86_64  | 14        | 3.26%   |
| 6.0.14-201.fsync.fc36.x86_64  | 11        | 2.56%   |
| 6.2.14-300.fsync.fc37.x86_64  | 10        | 2.33%   |
| 6.1.4-203.fsync.fc37.x86_64   | 10        | 2.33%   |
| 6.7.5-200.fsync.fc39.x86_64   | 9         | 2.09%   |
| 6.5.9-201.fsync.fc38.x86_64   | 9         | 2.09%   |
| 6.3.12-204.fsync.fc38.x86_64  | 9         | 2.09%   |
| 6.1.14-201.fsync.fc37.x86_64  | 9         | 2.09%   |
| 6.8.5-201.fsync.fc39.x86_64   | 8         | 1.86%   |
| 6.5.6-200.fsync.fc38.x86_64   | 8         | 1.86%   |
| 6.6.9-200.fsync.fc39.x86_64   | 7         | 1.63%   |
| 6.1.9-200.fsync.fc37.x86_64   | 7         | 1.63%   |
| 6.0.16-301.fsync.fc37.x86_64  | 7         | 1.63%   |
| 5.19.9-201.fsync.fc36.x86_64  | 7         | 1.63%   |
| 5.19.7-204.fsync.fc36.x86_64  | 7         | 1.63%   |
| 6.3.5-201.fsync.fc37.x86_64   | 6         | 1.4%    |
| 6.2.11-201.fsync.fc37.x86_64  | 6         | 1.4%    |
| 6.0.7-201.fsync.fc36.x86_64   | 6         | 1.4%    |
| 6.8.7-201.fsync.fc39.x86_64   | 5         | 1.16%   |
| 6.7.6-200.fsync.fc39.x86_64   | 5         | 1.16%   |
| 6.6.8-200.fsync.fc39.x86_64   | 5         | 1.16%   |
| 6.6.7-203.fsync.fc38.x86_64   | 5         | 1.16%   |
| 6.3.7-200.fsync.fc37.x86_64   | 5         | 1.16%   |
| 6.3.10-200.fsync.fc38.x86_64  | 5         | 1.16%   |
| 6.0.5-201.fsync.fc36.x86_64   | 5         | 1.16%   |
| 5.19.12-201.fsync.fc36.x86_64 | 5         | 1.16%   |
| 6.8.2-201.fsync.fc39.x86_64   | 4         | 0.93%   |
| 6.7.0-201.fsync.fc39.x86_64   | 4         | 0.93%   |
| 6.6.4-202.fsync.fc38.x86_64   | 4         | 0.93%   |
| 6.5.5-202.fsync.fc38.x86_64   | 4         | 0.93%   |
| 6.5.5-200.fsync.fc38.x86_64   | 4         | 0.93%   |
| 6.2.6-201.fsync.fc37.x86_64   | 4         | 0.93%   |
| 6.2.12-200.fsync.fc37.x86_64  | 4         | 0.93%   |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 0.93%   |
| 5.19.16-201.fsync.fc36.x86_64 | 4         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.7.0   | 41        | 9.58%   |
| 6.4.10  | 22        | 5.14%   |
| 6.7.6   | 20        | 4.67%   |
| 6.0.10  | 19        | 4.44%   |
| 6.3.12  | 17        | 3.97%   |
| 5.19.14 | 16        | 3.74%   |
| 6.1.11  | 14        | 3.27%   |
| 6.5.9   | 12        | 2.8%    |
| 6.0.14  | 11        | 2.57%   |
| 6.2.14  | 10        | 2.34%   |
| 6.1.4   | 10        | 2.34%   |
| 6.7.5   | 9         | 2.1%    |
| 6.5.5   | 9         | 2.1%    |
| 6.3.10  | 9         | 2.1%    |
| 6.1.14  | 9         | 2.1%    |
| 6.8.5   | 8         | 1.87%   |
| 6.5.6   | 8         | 1.87%   |
| 5.19.7  | 8         | 1.87%   |
| 6.6.9   | 7         | 1.64%   |
| 6.6.7   | 7         | 1.64%   |
| 6.2.11  | 7         | 1.64%   |
| 6.1.9   | 7         | 1.64%   |
| 6.1.6   | 7         | 1.64%   |
| 6.0.7   | 7         | 1.64%   |
| 6.0.16  | 7         | 1.64%   |
| 5.19.9  | 7         | 1.64%   |
| 6.6.8   | 6         | 1.4%    |
| 6.3.5   | 6         | 1.4%    |
| 6.0.9   | 6         | 1.4%    |
| 6.8.7   | 5         | 1.17%   |
| 6.3.7   | 5         | 1.17%   |
| 6.1.8   | 5         | 1.17%   |
| 6.0.5   | 5         | 1.17%   |
| 5.19.12 | 5         | 1.17%   |
| 6.8.2   | 4         | 0.93%   |
| 6.6.4   | 4         | 0.93%   |
| 6.5.3   | 4         | 0.93%   |
| 6.3.9   | 4         | 0.93%   |
| 6.2.6   | 4         | 0.93%   |
| 6.2.12  | 4         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.7     | 70        | 16.59%  |
| 6.0     | 59        | 13.98%  |
| 5.19    | 54        | 12.8%   |
| 6.1     | 52        | 12.32%  |
| 6.3     | 42        | 9.95%   |
| 6.5     | 36        | 8.53%   |
| 6.2     | 30        | 7.11%   |
| 6.6     | 29        | 6.87%   |
| 6.4     | 23        | 5.45%   |
| 6.8     | 17        | 4.03%   |
| 5.18    | 10        | 2.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 399       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GNOME    | 239       | 59.16%  |
| KDE5     | 134       | 33.17%  |
| KDE6     | 22        | 5.45%   |
| Unknown  | 8         | 1.98%   |
| Hyprland | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 333       | 82.84%  |
| X11     | 63        | 15.67%  |
| Unknown | 5         | 1.24%   |
| Tty     | 1         | 0.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 317       | 78.08%  |
| GDM     | 53        | 13.05%  |
| SDDM    | 33        | 8.13%   |
| LightDM | 3         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 203       | 50.62%  |
| en_GB   | 24        | 5.99%   |
| de_DE   | 21        | 5.24%   |
| ru_RU   | 14        | 3.49%   |
| es_MX   | 14        | 3.49%   |
| es_ES   | 14        | 3.49%   |
| pt_BR   | 13        | 3.24%   |
| it_IT   | 12        | 2.99%   |
| pl_PL   | 10        | 2.49%   |
| en_IN   | 10        | 2.49%   |
| en_CA   | 6         | 1.5%    |
| en_AU   | 6         | 1.5%    |
| fr_FR   | 5         | 1.25%   |
| es_AR   | 5         | 1.25%   |
| en_NZ   | 5         | 1.25%   |
| tr_TR   | 3         | 0.75%   |
| pt_PT   | 3         | 0.75%   |
| hu_HU   | 3         | 0.75%   |
| en_DK   | 3         | 0.75%   |
| Unknown | 3         | 0.75%   |
| zh_TW   | 2         | 0.5%    |
| uk_UA   | 2         | 0.5%    |
| sv_SE   | 1         | 0.25%   |
| ro_RO   | 1         | 0.25%   |
| nl_BE   | 1         | 0.25%   |
| nb_NO   | 1         | 0.25%   |
| hr_HR   | 1         | 0.25%   |
| fr_BE   | 1         | 0.25%   |
| fi_FI   | 1         | 0.25%   |
| es_VE   | 1         | 0.25%   |
| es_US   | 1         | 0.25%   |
| es_CR   | 1         | 0.25%   |
| es_CO   | 1         | 0.25%   |
| es_CL   | 1         | 0.25%   |
| en_ZA   | 1         | 0.25%   |
| en_SG   | 1         | 0.25%   |
| en_PH   | 1         | 0.25%   |
| en_NG   | 1         | 0.25%   |
| en_IE   | 1         | 0.25%   |
| en_BW   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 332       | 82.38%  |
| BIOS | 71        | 17.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 327       | 81.55%  |
| Ext4  | 73        | 18.2%   |
| Xfs   | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 311       | 76.6%   |
| GPT     | 92        | 22.66%  |
| MBR     | 3         | 0.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 374       | 93.27%  |
| Yes       | 27        | 6.73%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 353       | 88.25%  |
| Yes       | 47        | 11.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 85        | 21.3%   |
| Hewlett-Packard                  | 66        | 16.54%  |
| ASUSTek Computer                 | 66        | 16.54%  |
| Dell                             | 43        | 10.78%  |
| Acer                             | 32        | 8.02%   |
| MSI                              | 21        | 5.26%   |
| Apple                            | 14        | 3.51%   |
| Toshiba                          | 7         | 1.75%   |
| Gigabyte Technology              | 7         | 1.75%   |
| Samsung Electronics              | 4         | 1%      |
| Notebook                         | 4         | 1%      |
| Infinix                          | 3         | 0.75%   |
| Alienware                        | 3         | 0.75%   |
| Unknown                          | 3         | 0.75%   |
| Valve                            | 2         | 0.5%    |
| Positivo                         | 2         | 0.5%    |
| Monster                          | 2         | 0.5%    |
| HUAWEI                           | 2         | 0.5%    |
| GPU Company                      | 2         | 0.5%    |
| ASRock                           | 2         | 0.5%    |
| TUXEDO                           | 1         | 0.25%   |
| Timi                             | 1         | 0.25%   |
| THUNDEROBOT                      | 1         | 0.25%   |
| System76                         | 1         | 0.25%   |
| Sony                             | 1         | 0.25%   |
| Schenker                         | 1         | 0.25%   |
| Razer                            | 1         | 0.25%   |
| PC Specialist                    | 1         | 0.25%   |
| Packard Bell                     | 1         | 0.25%   |
| ONE-NETBOOK TECHNOLOGY           | 1         | 0.25%   |
| ONE-NETBOOK                      | 1         | 0.25%   |
| Micro Electronics                | 1         | 0.25%   |
| Micro Computer (HK) Tech Limited | 1         | 0.25%   |
| Medion                           | 1         | 0.25%   |
| LG Electronics                   | 1         | 0.25%   |
| Intel                            | 1         | 0.25%   |
| Google                           | 1         | 0.25%   |
| GEO                              | 1         | 0.25%   |
| Genuine                          | 1         | 0.25%   |
| Gateway                          | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 1.75%   |
| Lenovo Legion 5 15ARH05 82B5               | 3         | 0.75%   |
| Lenovo IdeaPad Y700-15ISK 80NV             | 3         | 0.75%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2        | 3         | 0.75%   |
| Lenovo IdeaPad C340-14API 81N6             | 3         | 0.75%   |
| HP Pavilion Notebook                       | 3         | 0.75%   |
| HP Pavilion Gaming Laptop 15-ec1xxx        | 3         | 0.75%   |
| HP Pavilion 15                             | 3         | 0.75%   |
| Dell Inspiron 15 3520                      | 3         | 0.75%   |
| Dell G5 5505                               | 3         | 0.75%   |
| ASUS ROG Strix G513QY_G513QY               | 3         | 0.75%   |
| Valve Jupiter                              | 2         | 0.5%    |
| Lenovo Z50-70 20354                        | 2         | 0.5%    |
| Lenovo Legion 5 15ARH05H 82B1              | 2         | 0.5%    |
| Lenovo Legion 5 15ACH6H 82JU               | 2         | 0.5%    |
| Lenovo IdeaPad 5 15ITL05 82FG              | 2         | 0.5%    |
| Lenovo IdeaPad 320-15ISK 80XH              | 2         | 0.5%    |
| Lenovo G500 20236                          | 2         | 0.5%    |
| HP ZBook 15u G3                            | 2         | 0.5%    |
| HP Pavilion Gaming Laptop 15-ec2xxx        | 2         | 0.5%    |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.5%    |
| HP Laptop 14s-fq0xxx                       | 2         | 0.5%    |
| HP EliteBook 8570p                         | 2         | 0.5%    |
| GPU Company GWNR71517                      | 2         | 0.5%    |
| Dell Vostro 3400                           | 2         | 0.5%    |
| Dell Latitude E6440                        | 2         | 0.5%    |
| Dell Inspiron 3542                         | 2         | 0.5%    |
| Dell G3 3590                               | 2         | 0.5%    |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 2         | 0.5%    |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV      | 2         | 0.5%    |
| ASUS ROG Strix G713RM_G713RM               | 2         | 0.5%    |
| ASUS ROG Strix G512LW_G512LW               | 2         | 0.5%    |
| ASUS ROG Flow X13 GV301QE_GV301QE          | 2         | 0.5%    |
| ASUS ASUS TUF Gaming F15 FX506LHB_FX506LHB | 2         | 0.5%    |
| Apple MacBookPro8,3                        | 2         | 0.5%    |
| Apple MacBookPro8,1                        | 2         | 0.5%    |
| Acer Nitro AN517-52                        | 2         | 0.5%    |
| Acer Nitro AN515-52                        | 2         | 0.5%    |
| Acer Nitro AN515-42                        | 2         | 0.5%    |
| Acer Aspire VX5-591G                       | 2         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 31        | 7.77%   |
| Lenovo ThinkPad       | 23        | 5.76%   |
| ASUS ROG              | 23        | 5.76%   |
| HP Pavilion           | 19        | 4.76%   |
| Acer Aspire           | 15        | 3.76%   |
| Lenovo Legion         | 14        | 3.51%   |
| ASUS VivoBook         | 14        | 3.51%   |
| HP Laptop             | 10        | 2.51%   |
| Dell Inspiron         | 10        | 2.51%   |
| Acer Nitro            | 10        | 2.51%   |
| ASUS ASUS             | 9         | 2.26%   |
| HP EliteBook          | 8         | 2.01%   |
| Dell Latitude         | 8         | 2.01%   |
| Unknown               | 7         | 1.75%   |
| Toshiba Satellite     | 6         | 1.5%    |
| Dell Precision        | 6         | 1.5%    |
| HP ZBook              | 5         | 1.25%   |
| HP OMEN               | 5         | 1.25%   |
| HP ENVY               | 4         | 1%      |
| Dell Vostro           | 4         | 1%      |
| Apple MacBookPro8     | 4         | 1%      |
| Infinix INBook        | 3         | 0.75%   |
| HP ProBook            | 3         | 0.75%   |
| Dell XPS              | 3         | 0.75%   |
| Dell G5               | 3         | 0.75%   |
| Dell G3               | 3         | 0.75%   |
| Dell G15              | 3         | 0.75%   |
| ASUS TUF              | 3         | 0.75%   |
| Valve Jupiter         | 2         | 0.5%    |
| MSI GT70              | 2         | 0.5%    |
| Monster ABRA          | 2         | 0.5%    |
| Lenovo Z50-70         | 2         | 0.5%    |
| Lenovo ThinkBook      | 2         | 0.5%    |
| Lenovo G580           | 2         | 0.5%    |
| Lenovo G500           | 2         | 0.5%    |
| HP 240                | 2         | 0.5%    |
| GPU Company GWNR71517 | 2         | 0.5%    |
| Gigabyte AERO         | 2         | 0.5%    |
| Dell G7               | 2         | 0.5%    |
| Apple MacBookPro5     | 2         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 65        | 16.29%  |
| 2020 | 50        | 12.53%  |
| 2019 | 41        | 10.28%  |
| 2022 | 37        | 9.27%   |
| 2018 | 35        | 8.77%   |
| 2013 | 28        | 7.02%   |
| 2023 | 23        | 5.76%   |
| 2014 | 23        | 5.76%   |
| 2012 | 21        | 5.26%   |
| 2017 | 17        | 4.26%   |
| 2016 | 17        | 4.26%   |
| 2015 | 17        | 4.26%   |
| 2011 | 7         | 1.75%   |
| 2009 | 7         | 1.75%   |
| 2010 | 5         | 1.25%   |
| 2008 | 3         | 0.75%   |
| 2024 | 2         | 0.5%    |
| 2007 | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 399       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 399       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 397       | 99.5%   |
| Yes  | 2         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 101       | 25.06%  |
| 8.01-16.0   | 94        | 23.33%  |
| 16.01-24.0  | 89        | 22.08%  |
| 32.01-64.0  | 55        | 13.65%  |
| 3.01-4.0    | 39        | 9.68%   |
| 24.01-32.0  | 13        | 3.23%   |
| 64.01-256.0 | 7         | 1.74%   |
| 1.01-2.0    | 3         | 0.74%   |
| 2.01-3.0    | 2         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 173       | 41.19%  |
| 2.01-3.0   | 100       | 23.81%  |
| 3.01-4.0   | 86        | 20.48%  |
| 8.01-16.0  | 34        | 8.1%    |
| 1.01-2.0   | 26        | 6.19%   |
| 16.01-24.0 | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 262       | 64.69%  |
| 2      | 116       | 28.64%  |
| 3      | 17        | 4.2%    |
| 4      | 8         | 1.98%   |
| 5      | 2         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 315       | 78.95%  |
| Yes       | 84        | 21.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 321       | 80.05%  |
| No        | 80        | 19.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 391       | 97.99%  |
| No        | 8         | 2.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 358       | 89.28%  |
| No        | 43        | 10.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 104       | 26.07%  |
| Germany     | 29        | 7.27%   |
| Brazil      | 20        | 5.01%   |
| Russia      | 18        | 4.51%   |
| Poland      | 17        | 4.26%   |
| UK          | 16        | 4.01%   |
| Spain       | 15        | 3.76%   |
| India       | 15        | 3.76%   |
| Italy       | 14        | 3.51%   |
| Mexico      | 12        | 3.01%   |
| Indonesia   | 8         | 2.01%   |
| Canada      | 8         | 2.01%   |
| Australia   | 7         | 1.75%   |
| Argentina   | 7         | 1.75%   |
| Turkey      | 5         | 1.25%   |
| Portugal    | 5         | 1.25%   |
| New Zealand | 5         | 1.25%   |
| France      | 5         | 1.25%   |
| Austria     | 5         | 1.25%   |
| Romania     | 4         | 1%      |
| Philippines | 4         | 1%      |
| Hungary     | 4         | 1%      |
| Chile       | 4         | 1%      |
| Belgium     | 4         | 1%      |
| Vietnam     | 3         | 0.75%   |
| Sweden      | 3         | 0.75%   |
| Norway      | 3         | 0.75%   |
| Malaysia    | 3         | 0.75%   |
| Colombia    | 3         | 0.75%   |
| Venezuela   | 2         | 0.5%    |
| Taiwan      | 2         | 0.5%    |
| Pakistan    | 2         | 0.5%    |
| Morocco     | 2         | 0.5%    |
| Greece      | 2         | 0.5%    |
| Finland     | 2         | 0.5%    |
| El Salvador | 2         | 0.5%    |
| Egypt       | 2         | 0.5%    |
| Czechia     | 2         | 0.5%    |
| Croatia     | 2         | 0.5%    |
| Belarus     | 2         | 0.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fortaleza             | 4         | 0.96%   |
| Wroclaw               | 3         | 0.72%   |
| Warsaw                | 3         | 0.72%   |
| Sydney                | 3         | 0.72%   |
| San Francisco         | 3         | 0.72%   |
| Milano                | 3         | 0.72%   |
| Madrid                | 3         | 0.72%   |
| Kuala Lumpur          | 3         | 0.72%   |
| Houston               | 3         | 0.72%   |
| Berlin                | 3         | 0.72%   |
| Auckland              | 3         | 0.72%   |
| Wasilla               | 2         | 0.48%   |
| Vienna                | 2         | 0.48%   |
| Stockholm             | 2         | 0.48%   |
| Schmalkalden          | 2         | 0.48%   |
| Sao Paulo             | 2         | 0.48%   |
| San Jose              | 2         | 0.48%   |
| Salem                 | 2         | 0.48%   |
| Poznan                | 2         | 0.48%   |
| Perm                  | 2         | 0.48%   |
| Panama City           | 2         | 0.48%   |
| Ochsenfurt            | 2         | 0.48%   |
| Mumbai                | 2         | 0.48%   |
| Minsk                 | 2         | 0.48%   |
| Milan                 | 2         | 0.48%   |
| Michigan City         | 2         | 0.48%   |
| Mexico City           | 2         | 0.48%   |
| Maipu                 | 2         | 0.48%   |
| Lüneburg             | 2         | 0.48%   |
| Lucknow               | 2         | 0.48%   |
| Los Angeles           | 2         | 0.48%   |
| Lisbon                | 2         | 0.48%   |
| Kursk                 | 2         | 0.48%   |
| Jakarta               | 2         | 0.48%   |
| Hamburg               | 2         | 0.48%   |
| Gustavo Adolfo Madero | 2         | 0.48%   |
| Guadalajara           | 2         | 0.48%   |
| Gainesville           | 2         | 0.48%   |
| Davao City            | 2         | 0.48%   |
| Chennai               | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 106       | 122    | 19.06%  |
| Sandisk                      | 47        | 55     | 8.45%   |
| Seagate                      | 39        | 42     | 7.01%   |
| WDC                          | 33        | 35     | 5.94%   |
| SK hynix                     | 33        | 35     | 5.94%   |
| Kingston                     | 28        | 29     | 5.04%   |
| Toshiba                      | 27        | 33     | 4.86%   |
| Intel                        | 24        | 27     | 4.32%   |
| Micron Technology            | 23        | 28     | 4.14%   |
| Crucial                      | 23        | 28     | 4.14%   |
| Unknown                      | 15        | 16     | 2.7%    |
| Micron/Crucial Technology    | 15        | 16     | 2.7%    |
| HGST                         | 14        | 14     | 2.52%   |
| KIOXIA                       | 13        | 14     | 2.34%   |
| Phison Electronics           | 12        | 13     | 2.16%   |
| Hitachi                      | 8         | 10     | 1.44%   |
| China                        | 7         | 8      | 1.26%   |
| Apple                        | 7         | 9      | 1.26%   |
| Kingston Technology Company  | 6         | 8      | 1.08%   |
| A-DATA Technology            | 6         | 6      | 1.08%   |
| PNY                          | 5         | 5      | 0.9%    |
| Unknown                      | 5         | 5      | 0.9%    |
| Team                         | 4         | 4      | 0.72%   |
| Shenzhen Longsys Electronics | 4         | 4      | 0.72%   |
| Realtek Semiconductor        | 4         | 4      | 0.72%   |
| SABRENT                      | 3         | 3      | 0.54%   |
| Wibtek                       | 2         | 2      | 0.36%   |
| Solid State Storage          | 2         | 2      | 0.36%   |
| Realtek                      | 2         | 2      | 0.36%   |
| MAXIO Technology (Hangzhou)  | 2         | 2      | 0.36%   |
| LITEON                       | 2         | 2      | 0.36%   |
| Lexar                        | 2         | 2      | 0.36%   |
| KingSpec                     | 2         | 3      | 0.36%   |
| Intenso                      | 2         | 2      | 0.36%   |
| HS-SSD-C100                  | 2         | 2      | 0.36%   |
| ADATA Technology             | 2         | 2      | 0.36%   |
| XPG                          | 1         | 4      | 0.18%   |
| V-GeN                        | 1         | 1      | 0.18%   |
| Union Memory                 | 1         | 2      | 0.18%   |
| T-FORCE                      | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 24        | 4.17%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 11        | 1.91%   |
| Kingston SA400S37240G 240GB SSD                    | 11        | 1.91%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                | 10        | 1.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 7         | 1.22%   |
| Toshiba MQ04ABF100 1TB                             | 6         | 1.04%   |
| Micron 2210_MTFDHBA512QFD 512GB                    | 6         | 1.04%   |
| Intel SSDPEKNU512GZ 512GB                          | 6         | 1.04%   |
| Crucial CT500MX500SSD1 500GB                       | 6         | 1.04%   |
| Unknown MMC Card  64GB                             | 5         | 0.87%   |
| Toshiba MQ01ABF050 500GB                           | 5         | 0.87%   |
| Toshiba MQ01ABD100 1TB                             | 5         | 0.87%   |
| Samsung SSD 980 1TB                                | 5         | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 5         | 0.87%   |
| HGST HTS721010A9E630 1TB                           | 5         | 0.87%   |
| Crucial CT1000BX500SSD1 1TB                        | 5         | 0.87%   |
| Unknown                                            | 5         | 0.87%   |
| Unknown MMC Card  32GB                             | 4         | 0.69%   |
| SK hynix BC511 256GB                               | 4         | 0.69%   |
| SK hynix BC501 NVMe Solid State Drive 512GB        | 4         | 0.69%   |
| Seagate ST1000LX015-1U7172 1TB                     | 4         | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 4         | 0.69%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 4         | 0.69%   |
| Samsung MZVLQ1T0HBLB-00B00 1024GB                  | 4         | 0.69%   |
| Phison PS5013 E13 NVMe Controller 512GB            | 4         | 0.69%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                      | 4         | 0.69%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                     | 4         | 0.69%   |
| Intel SSD 660P Series 1024GB                       | 4         | 0.69%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB          | 3         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                    | 3         | 0.52%   |
| Sandisk WD Green SN350 2TB                         | 3         | 0.52%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB      | 3         | 0.52%   |
| Samsung MZALQ512HBLU-00BL2 512GB                   | 3         | 0.52%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 3         | 0.52%   |
| SABRENT Disk 1TB                                   | 3         | 0.52%   |
| Phison E16 PCIe4 NVMe Controller 1TB               | 3         | 0.52%   |
| Phison E12 NVMe Controller 2TB                     | 3         | 0.52%   |
| Kingston Company SNV2S1000G 1TB                    | 3         | 0.52%   |
| Kingston SA400S37480G 480GB SSD                    | 3         | 0.52%   |
| Intel SSDPEKNU010TZ 1024GB                         | 3         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 41     | 34.23%  |
| WDC                 | 21        | 22     | 18.92%  |
| Toshiba             | 20        | 24     | 18.02%  |
| HGST                | 14        | 14     | 12.61%  |
| Hitachi             | 8         | 10     | 7.21%   |
| SABRENT             | 3         | 3      | 2.7%    |
| Unknown             | 2         | 2      | 1.8%    |
| Samsung Electronics | 1         | 1      | 0.9%    |
| HGST HTS            | 1         | 1      | 0.9%    |
| Fujitsu             | 1         | 1      | 0.9%    |
| ASMT                | 1         | 4      | 0.9%    |
| Apple               | 1         | 1      | 0.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 40     | 23.72%  |
| Crucial             | 22        | 27     | 14.1%   |
| Kingston            | 19        | 19     | 12.18%  |
| SanDisk             | 12        | 15     | 7.69%   |
| China               | 7         | 8      | 4.49%   |
| WDC                 | 6         | 7      | 3.85%   |
| A-DATA Technology   | 6         | 6      | 3.85%   |
| PNY                 | 5         | 5      | 3.21%   |
| Team                | 4         | 4      | 2.56%   |
| SK hynix            | 4         | 4      | 2.56%   |
| Micron Technology   | 3         | 3      | 1.92%   |
| Intel               | 3         | 3      | 1.92%   |
| Wibtek              | 2         | 2      | 1.28%   |
| Toshiba             | 2         | 3      | 1.28%   |
| LITEON              | 2         | 2      | 1.28%   |
| KingSpec            | 2         | 3      | 1.28%   |
| Intenso             | 2         | 2      | 1.28%   |
| Apple               | 2         | 2      | 1.28%   |
| V-GeN               | 1         | 1      | 0.64%   |
| SPCC                | 1         | 1      | 0.64%   |
| Seagate             | 1         | 1      | 0.64%   |
| Ramsta              | 1         | 1      | 0.64%   |
| Plextor             | 1         | 1      | 0.64%   |
| Patriot             | 1         | 1      | 0.64%   |
| OCZ                 | 1         | 1      | 0.64%   |
| Netac               | 1         | 1      | 0.64%   |
| Mushkin             | 1         | 1      | 0.64%   |
| Lexar               | 1         | 1      | 0.64%   |
| GOODRAM             | 1         | 1      | 0.64%   |
| Firebat             | 1         | 1      | 0.64%   |
| Emtec               | 1         | 1      | 0.64%   |
| Dell                | 1         | 1      | 0.64%   |
| Corsair             | 1         | 1      | 0.64%   |
| Apacer              | 1         | 1      | 0.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 234       | 308    | 46.15%  |
| SSD     | 141       | 171    | 27.81%  |
| HDD     | 109       | 124    | 21.5%   |
| MMC     | 13        | 13     | 2.56%   |
| Unknown | 10        | 10     | 1.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 233       | 306    | 48.24%  |
| SATA | 212       | 276    | 43.89%  |
| SAS  | 25        | 31     | 5.18%   |
| MMC  | 13        | 13     | 2.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 130       | 150    | 51.59%  |
| 0.51-1.0   | 97        | 115    | 38.49%  |
| 1.01-2.0   | 22        | 27     | 8.73%   |
| 3.01-4.0   | 3         | 3      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 106       | 25.79%  |
| 251-500        | 83        | 20.19%  |
| 1001-2000      | 63        | 15.33%  |
| 101-250        | 59        | 14.36%  |
| More than 3000 | 35        | 8.52%   |
| 2001-3000      | 20        | 4.87%   |
| Unknown        | 19        | 4.62%   |
| 21-50          | 11        | 2.68%   |
| 51-100         | 11        | 2.68%   |
| 1-20           | 4         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 100       | 23.81%  |
| 1-20           | 72        | 17.14%  |
| 101-250        | 70        | 16.67%  |
| 251-500        | 52        | 12.38%  |
| 51-100         | 45        | 10.71%  |
| 501-1000       | 34        | 8.1%    |
| 1001-2000      | 19        | 4.52%   |
| Unknown        | 19        | 4.52%   |
| 2001-3000      | 5         | 1.19%   |
| More than 3000 | 4         | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 980 1TB       | 1         | 1      | 12.5%   |
| Ramsta SSD S800 240GB                 | 1         | 1      | 12.5%   |
| Hitachi HTS54323 320GB                | 1         | 1      | 12.5%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 12.5%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 12.5%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 12.5%   |
| ASMT ASM1156-PM 2TB                   | 1         | 2      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 3         | 3      | 37.5%   |
| SK hynix            | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Ramsta              | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |
| ASMT                | 1         | 2      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 3         | 3      | 60%     |
| Hitachi | 1         | 1      | 20%     |
| ASMT    | 1         | 2      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 62.5%   |
| SSD  | 2         | 2      | 25%     |
| NVMe | 1         | 1      | 12.5%   |

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
| Detected | 321       | 498    | 76.79%  |
| Works    | 90        | 119    | 21.53%  |
| Malfunc  | 7         | 9      | 1.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 235       | 41.81%  |
| Samsung Electronics                  | 72        | 12.81%  |
| AMD                                  | 72        | 12.81%  |
| SanDisk                              | 42        | 7.47%   |
| SK hynix                             | 29        | 5.16%   |
| Micron Technology                    | 20        | 3.56%   |
| Micron/Crucial Technology            | 16        | 2.85%   |
| Kingston Technology Company          | 15        | 2.67%   |
| KIOXIA                               | 13        | 2.31%   |
| Phison Electronics                   | 12        | 2.14%   |
| Toshiba America Info Systems         | 5         | 0.89%   |
| Shenzhen Longsys Electronics         | 4         | 0.71%   |
| Realtek Semiconductor                | 4         | 0.71%   |
| Nvidia                               | 4         | 0.71%   |
| Apple                                | 4         | 0.71%   |
| Solid State Storage Technology       | 3         | 0.53%   |
| MAXIO Technology (Hangzhou)          | 2         | 0.36%   |
| Marvell Technology Group             | 2         | 0.36%   |
| ADATA Technology                     | 2         | 0.36%   |
| Union Memory (Shenzhen)              | 1         | 0.18%   |
| Silicon Motion                       | 1         | 0.18%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.18%   |
| Lenovo                               | 1         | 0.18%   |
| INNOGRIT                             | 1         | 0.18%   |
| ASMedia Technology                   | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 67        | 11.36%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 29        | 4.92%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 23        | 3.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 22        | 3.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 21        | 3.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 21        | 3.56%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 17        | 2.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 17        | 2.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 17        | 2.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 15        | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 15        | 2.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                                               | 14        | 2.37%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 13        | 2.2%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                                                          | 12        | 2.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 10        | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 10        | 1.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                                               | 10        | 1.69%   |
| Intel SSD 670p Series [Keystone Harbor]                                                                            | 10        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 10        | 1.69%   |
| Micron 2210 NVMe SSD [Cobain]                                                                                      | 9         | 1.53%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 9         | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 7         | 1.19%   |
| Intel SSD 660P Series                                                                                              | 6         | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 6         | 1.02%   |
| SK hynix BC501 NVMe Solid State Drive                                                                              | 5         | 0.85%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                                            | 5         | 0.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 5         | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 5         | 0.85%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                                                        | 5         | 0.85%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                                                 | 4         | 0.68%   |
| SK hynix BC511 NVMe SSD                                                                                            | 4         | 0.68%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 4         | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                                              | 4         | 0.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 4         | 0.68%   |
| Intel Alder Lake-P SATA AHCI Controller                                                                            | 4         | 0.68%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                                               | 3         | 0.51%   |
| SK hynix PC611 NVMe Solid State Drive                                                                              | 3         | 0.51%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 3         | 0.51%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                                                        | 3         | 0.51%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                                              | 3         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 260       | 47.79%  |
| NVMe | 233       | 42.83%  |
| RAID | 45        | 8.27%   |
| IDE  | 6         | 1.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 274       | 68.67%  |
| AMD    | 125       | 31.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 2.5%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 10        | 2.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 2.25%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 2.25%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 9         | 2.25%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 8         | 2%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 1.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.5%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 6         | 1.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.5%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 1.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.25%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 5         | 1.25%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 1.25%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 1.25%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 5         | 1.25%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.25%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.25%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 1.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.25%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 1.25%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 4         | 1%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1%      |
| AMD Ryzen 7 6800H with Radeon Graphics        | 4         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.75%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.75%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 3         | 0.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.75%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 3         | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.75%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.75%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.75%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 87        | 21.8%   |
| Intel Core i5           | 83        | 20.8%   |
| Other                   | 57        | 14.29%  |
| AMD Ryzen 5             | 42        | 10.53%  |
| AMD Ryzen 7             | 41        | 10.28%  |
| Intel Core i3           | 21        | 5.26%   |
| Intel Celeron           | 15        | 3.76%   |
| AMD Ryzen 9             | 14        | 3.51%   |
| AMD Ryzen 3             | 6         | 1.5%    |
| Intel Pentium           | 4         | 1%      |
| Intel Core 2 Duo        | 4         | 1%      |
| AMD A6                  | 4         | 1%      |
| AMD A10                 | 3         | 0.75%   |
| Intel Pentium Dual-Core | 2         | 0.5%    |
| AMD Turion 64 X2 Mobile | 2         | 0.5%    |
| AMD A4                  | 2         | 0.5%    |
| Intel Xeon              | 1         | 0.25%   |
| Intel Pentium Silver    | 1         | 0.25%   |
| Intel Core 2 Extreme    | 1         | 0.25%   |
| Intel Atom              | 1         | 0.25%   |
| AMD Turion              | 1         | 0.25%   |
| AMD Ryzen 7 PRO         | 1         | 0.25%   |
| AMD Ryzen 5 PRO         | 1         | 0.25%   |
| AMD Phenom II           | 1         | 0.25%   |
| AMD FX                  | 1         | 0.25%   |
| AMD E2                  | 1         | 0.25%   |
| AMD E                   | 1         | 0.25%   |
| AMD Athlon              | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 132       | 33%     |
| 2      | 122       | 30.5%   |
| 8      | 63        | 15.75%  |
| 6      | 57        | 14.25%  |
| 14     | 13        | 3.25%   |
| 12     | 6         | 1.5%    |
| 10     | 4         | 1%      |
| 24     | 1         | 0.25%   |
| 16     | 1         | 0.25%   |
| 1      | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 399       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 354       | 88.5%   |
| 1      | 46        | 11.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 399       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 190       | 46.57%  |
| 0x0a50000c | 24        | 5.88%   |
| 0xa0652    | 12        | 2.94%   |
| 0x40651    | 12        | 2.94%   |
| 0x08108109 | 11        | 2.7%    |
| 0x08600106 | 9         | 2.21%   |
| 0x906ea    | 8         | 1.96%   |
| 0x906a3    | 8         | 1.96%   |
| 0x306a9    | 8         | 1.96%   |
| 0x206a7    | 8         | 1.96%   |
| 0x08608103 | 8         | 1.96%   |
| 0x08600104 | 8         | 1.96%   |
| 0x906e9    | 7         | 1.72%   |
| 0x806c1    | 7         | 1.72%   |
| 0x0a404102 | 7         | 1.72%   |
| 0x0a50000d | 6         | 1.47%   |
| 0x806d1    | 5         | 1.23%   |
| 0x506e3    | 5         | 1.23%   |
| 0x306c3    | 5         | 1.23%   |
| 0x806e9    | 4         | 0.98%   |
| 0x406e3    | 4         | 0.98%   |
| 0x806ea    | 3         | 0.74%   |
| 0x10676    | 3         | 0.74%   |
| 0x08108102 | 3         | 0.74%   |
| 0x0810100b | 3         | 0.74%   |
| 0x08101007 | 3         | 0.74%   |
| 0x806ec    | 2         | 0.49%   |
| 0x706e5    | 2         | 0.49%   |
| 0x306d4    | 2         | 0.49%   |
| 0x30678    | 2         | 0.49%   |
| 0x1067a    | 2         | 0.49%   |
| 0x0a404101 | 2         | 0.49%   |
| 0x06006110 | 2         | 0.49%   |
| 0xa0655    | 1         | 0.25%   |
| 0x906ed    | 1         | 0.25%   |
| 0x706a1    | 1         | 0.25%   |
| 0x506c9    | 1         | 0.25%   |
| 0x30661    | 1         | 0.25%   |
| 0x20655    | 1         | 0.25%   |
| 0x20652    | 1         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 64        | 16%     |
| Haswell          | 41        | 10.25%  |
| Zen 3            | 36        | 9%      |
| Unknown          | 33        | 8.25%   |
| Skylake          | 24        | 6%      |
| CometLake        | 24        | 6%      |
| Zen 2            | 22        | 5.5%    |
| Alderlake Hybrid | 22        | 5.5%    |
| TigerLake        | 20        | 5%      |
| Zen+             | 16        | 4%      |
| SandyBridge      | 15        | 3.75%   |
| IvyBridge        | 15        | 3.75%   |
| IceLake          | 12        | 3%      |
| Zen              | 9         | 2.25%   |
| Penryn           | 7         | 1.75%   |
| Goldmont plus    | 7         | 1.75%   |
| Broadwell        | 7         | 1.75%   |
| Silvermont       | 5         | 1.25%   |
| Excavator        | 5         | 1.25%   |
| Westmere         | 2         | 0.5%    |
| Puma             | 2         | 0.5%    |
| K8 Hammer        | 2         | 0.5%    |
| Bobcat           | 2         | 0.5%    |
| Tremont          | 1         | 0.25%   |
| Steamroller      | 1         | 0.25%   |
| Piledriver       | 1         | 0.25%   |
| K8 & K10 hybrid  | 1         | 0.25%   |
| K10              | 1         | 0.25%   |
| Jaguar           | 1         | 0.25%   |
| Goldmont         | 1         | 0.25%   |
| Bonnell          | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 247       | 42.66%  |
| Nvidia | 190       | 32.82%  |
| AMD    | 142       | 24.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 28        | 4.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 28        | 4.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 24        | 4.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 21        | 3.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 20        | 3.35%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 20        | 3.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 18        | 3.02%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 17        | 2.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 17        | 2.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 15        | 2.51%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 13        | 2.18%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 13        | 2.18%   |
| AMD Rembrandt [Radeon 680M]                                               | 13        | 2.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 12        | 2.01%   |
| Intel HD Graphics 530                                                     | 11        | 1.84%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 10        | 1.68%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 10        | 1.68%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 9         | 1.51%   |
| AMD Lucienne                                                              | 9         | 1.51%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 8         | 1.34%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 8         | 1.34%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 8         | 1.34%   |
| Intel HD Graphics 620                                                     | 8         | 1.34%   |
| Intel UHD Graphics 620                                                    | 7         | 1.17%   |
| Intel HD Graphics 5500                                                    | 7         | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 7         | 1.17%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 7         | 1.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 6         | 1.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 1.01%   |
| Intel HD Graphics 630                                                     | 6         | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 6         | 1.01%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 5         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 4         | 0.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 4         | 0.67%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 4         | 0.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 0.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 4         | 0.67%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 3         | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                               | 3         | 0.5%    |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                  | 3         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel + Nvidia     | 119       | 29.82%  |
| 1 x Intel          | 105       | 26.32%  |
| 1 x AMD            | 72        | 18.05%  |
| AMD + Nvidia       | 38        | 9.52%   |
| 1 x Nvidia         | 31        | 7.77%   |
| 2 x AMD            | 16        | 4.01%   |
| Intel + AMD        | 16        | 4.01%   |
| Other              | 1         | 0.25%   |
| Intel + 2 x Nvidia | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 248       | 61.85%  |
| Proprietary | 151       | 37.66%  |
| Unknown     | 2         | 0.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 237       | 58.81%  |
| 0.01-0.5   | 67        | 16.63%  |
| 1.01-2.0   | 36        | 8.93%   |
| 0.51-1.0   | 21        | 5.21%   |
| 7.01-8.0   | 15        | 3.72%   |
| 3.01-4.0   | 11        | 2.73%   |
| 5.01-6.0   | 10        | 2.48%   |
| 8.01-16.0  | 6         | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 93        | 18.94%  |
| BOE                     | 74        | 15.07%  |
| LG Display              | 62        | 12.63%  |
| Chimei Innolux          | 61        | 12.42%  |
| Samsung Electronics     | 46        | 9.37%   |
| PANDA                   | 19        | 3.87%   |
| Apple                   | 13        | 2.65%   |
| Dell                    | 12        | 2.44%   |
| Goldstar                | 11        | 2.24%   |
| Sharp                   | 10        | 2.04%   |
| Hewlett-Packard         | 9         | 1.83%   |
| MSI                     | 6         | 1.22%   |
| HKC                     | 5         | 1.02%   |
| Chi Mei Optoelectronics | 5         | 1.02%   |
| Acer                    | 5         | 1.02%   |
| AOC                     | 4         | 0.81%   |
| ViewSonic               | 3         | 0.61%   |
| TMX                     | 3         | 0.61%   |
| Sony                    | 3         | 0.61%   |
| Philips                 | 3         | 0.61%   |
| Lenovo                  | 3         | 0.61%   |
| InfoVision              | 3         | 0.61%   |
| BenQ                    | 3         | 0.61%   |
| ASUSTek Computer        | 3         | 0.61%   |
| Ancor Communications    | 3         | 0.61%   |
| Vizio                   | 2         | 0.41%   |
| Valve                   | 2         | 0.41%   |
| Eizo                    | 2         | 0.41%   |
| CSO                     | 2         | 0.41%   |
| ___                     | 1         | 0.2%    |
| XUE                     | 1         | 0.2%    |
| Xiaomi                  | 1         | 0.2%    |
| VIE                     | 1         | 0.2%    |
| Unknown                 | 1         | 0.2%    |
| SNC                     | 1         | 0.2%    |
| Ruijiang                | 1         | 0.2%    |
| Roku                    | 1         | 0.2%    |
| Pixio                   | 1         | 0.2%    |
| Panasonic               | 1         | 0.2%    |
| NEC Computers           | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 7         | 1.42%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch              | 5         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 5         | 1.01%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 5         | 1.01%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 4         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 4         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 4         | 0.81%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 4         | 0.81%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch     | 3         | 0.61%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                   | 3         | 0.61%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch              | 3         | 0.61%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 3         | 0.61%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch            | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch             | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch             | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.61%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 2         | 0.41%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                   | 2         | 0.41%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                   | 2         | 0.41%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                   | 2         | 0.41%   |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                           | 2         | 0.41%   |
| LG Display LCD Monitor LGD0738 1920x1080 344x194mm 15.5-inch              | 2         | 0.41%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch              | 2         | 0.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 2         | 0.41%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 2         | 0.41%   |
| HKC LCD Monitor HKC3CFB 1920x1080 344x194mm 15.5-inch                     | 2         | 0.41%   |
| HKC LCD Monitor HKC36BB 1366x768 309x174mm 14.0-inch                      | 2         | 0.41%   |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                        | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch          | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch          | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch          | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch          | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch           | 2         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.41%   |
| BOE LCD Monitor BOE0A00 1920x1080 382x215mm 17.3-inch                     | 2         | 0.41%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                     | 2         | 0.41%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                     | 2         | 0.41%   |
| BOE LCD Monitor BOE0931 2240x1400 302x189mm 14.0-inch                     | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 239       | 53.59%  |
| 1366x768 (WXGA)    | 87        | 19.51%  |
| 2560x1440 (QHD)    | 25        | 5.61%   |
| 3840x2160 (4K)     | 21        | 4.71%   |
| 2560x1600          | 12        | 2.69%   |
| 1920x1200 (WUXGA)  | 12        | 2.69%   |
| 2880x1800          | 6         | 1.35%   |
| 1600x900 (HD+)     | 6         | 1.35%   |
| 1440x900 (WXGA+)   | 6         | 1.35%   |
| 1280x800 (WXGA)    | 4         | 0.9%    |
| 2240x1400          | 3         | 0.67%   |
| 800x1280           | 2         | 0.45%   |
| 3840x2400          | 2         | 0.45%   |
| 3440x1440          | 2         | 0.45%   |
| 3200x2000          | 2         | 0.45%   |
| 2560x1080          | 2         | 0.45%   |
| 1680x1050 (WSXGA+) | 2         | 0.45%   |
| 1360x768           | 2         | 0.45%   |
| 3456x2160          | 1         | 0.22%   |
| 3200x1800 (QHD+)   | 1         | 0.22%   |
| 3072x1920          | 1         | 0.22%   |
| 2520x1680          | 1         | 0.22%   |
| 2160x1440          | 1         | 0.22%   |
| 1920x540           | 1         | 0.22%   |
| 1600x2560          | 1         | 0.22%   |
| 1600x1200          | 1         | 0.22%   |
| 1280x960           | 1         | 0.22%   |
| 1280x720 (HD)      | 1         | 0.22%   |
| 1280x1024 (SXGA)   | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 213       | 43.56%  |
| 17      | 49        | 10.02%  |
| 13      | 45        | 9.2%    |
| 14      | 40        | 8.18%   |
| 27      | 22        | 4.5%    |
| 23      | 20        | 4.09%   |
| 16      | 18        | 3.68%   |
| 31      | 17        | 3.48%   |
| 24      | 17        | 3.48%   |
| 21      | 6         | 1.23%   |
| 34      | 4         | 0.82%   |
| 18      | 4         | 0.82%   |
| 11      | 4         | 0.82%   |
| 72      | 3         | 0.61%   |
| Unknown | 3         | 0.61%   |
| 84      | 2         | 0.41%   |
| 48      | 2         | 0.41%   |
| 43      | 2         | 0.41%   |
| 32      | 2         | 0.41%   |
| 20      | 2         | 0.41%   |
| 8       | 2         | 0.41%   |
| 7       | 2         | 0.41%   |
| 86      | 1         | 0.2%    |
| 69      | 1         | 0.2%    |
| 54      | 1         | 0.2%    |
| 44      | 1         | 0.2%    |
| 40      | 1         | 0.2%    |
| 36      | 1         | 0.2%    |
| 26      | 1         | 0.2%    |
| 19      | 1         | 0.2%    |
| 12      | 1         | 0.2%    |
| 10      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 292       | 60.21%  |
| 351-400     | 55        | 11.34%  |
| 501-600     | 53        | 10.93%  |
| 201-300     | 26        | 5.36%   |
| 601-700     | 20        | 4.12%   |
| 401-500     | 12        | 2.47%   |
| 701-800     | 6         | 1.24%   |
| 1501-2000   | 6         | 1.24%   |
| 1001-1500   | 3         | 0.62%   |
| 901-1000    | 3         | 0.62%   |
| Unknown     | 3         | 0.62%   |
| 801-900     | 2         | 0.41%   |
| 101-200     | 2         | 0.41%   |
| 1-100       | 2         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 347       | 84.43%  |
| 16/10 | 50        | 12.17%  |
| 21/9  | 4         | 0.97%   |
| 5/4   | 2         | 0.49%   |
| 3/2   | 2         | 0.49%   |
| 0.67  | 2         | 0.49%   |
| 0.62  | 2         | 0.49%   |
| 4/3   | 1         | 0.24%   |
| 1.96  | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 216       | 44.35%  |
| 81-90          | 73        | 14.99%  |
| 121-130        | 45        | 9.24%   |
| 201-250        | 31        | 6.37%   |
| 351-500        | 22        | 4.52%   |
| 301-350        | 22        | 4.52%   |
| 111-120        | 14        | 2.87%   |
| 71-80          | 12        | 2.46%   |
| 251-300        | 9         | 1.85%   |
| More than 1000 | 8         | 1.64%   |
| 151-200        | 6         | 1.23%   |
| 501-1000       | 6         | 1.23%   |
| 141-150        | 5         | 1.03%   |
| 131-140        | 5         | 1.03%   |
| 51-60          | 4         | 0.82%   |
| 1-40           | 4         | 0.82%   |
| Unknown        | 3         | 0.62%   |
| 61-70          | 1         | 0.21%   |
| 41-50          | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 228       | 47.7%   |
| 101-120       | 98        | 20.5%   |
| 51-100        | 80        | 16.74%  |
| 161-240       | 44        | 9.21%   |
| More than 240 | 16        | 3.35%   |
| 1-50          | 9         | 1.88%   |
| Unknown       | 3         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 308       | 75.49%  |
| 2     | 85        | 20.83%  |
| 3     | 9         | 2.21%   |
| 0     | 6         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 255       | 38.23%  |
| Intel                           | 205       | 30.73%  |
| Qualcomm Atheros                | 66        | 9.9%    |
| Broadcom                        | 39        | 5.85%   |
| MediaTek                        | 33        | 4.95%   |
| Xiaomi                          | 7         | 1.05%   |
| ASIX Electronics                | 7         | 1.05%   |
| Samsung Electronics             | 6         | 0.9%    |
| Broadcom Limited                | 6         | 0.9%    |
| Ralink Technology               | 4         | 0.6%    |
| Qualcomm                        | 4         | 0.6%    |
| Nvidia                          | 4         | 0.6%    |
| Marvell Technology Group        | 4         | 0.6%    |
| TP-Link                         | 3         | 0.45%   |
| Ralink                          | 3         | 0.45%   |
| Lenovo                          | 3         | 0.45%   |
| Sierra Wireless                 | 2         | 0.3%    |
| Qualcomm Atheros Communications | 2         | 0.3%    |
| Microsoft                       | 2         | 0.3%    |
| ASUSTek Computer                | 2         | 0.3%    |
| Panasonic (Matsushita)          | 1         | 0.15%   |
| OPPO Electronics                | 1         | 0.15%   |
| Motorola PCS                    | 1         | 0.15%   |
| JMicron Technology              | 1         | 0.15%   |
| Huawei Technologies             | 1         | 0.15%   |
| Hewlett-Packard                 | 1         | 0.15%   |
| Google                          | 1         | 0.15%   |
| DisplayLink                     | 1         | 0.15%   |
| Apple                           | 1         | 0.15%   |
| Afatech                         | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 171       | 22.59%  |
| Intel Wi-Fi 6 AX200                                                    | 34        | 4.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 23        | 3.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 2.77%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 2.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 18        | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 17        | 2.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 16        | 2.11%   |
| Intel Wi-Fi 6 AX201                                                    | 16        | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 14        | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 12        | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 12        | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 12        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 1.45%   |
| Intel Wireless 8265 / 8275                                             | 11        | 1.45%   |
| Intel Wireless 8260                                                    | 11        | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                          | 11        | 1.45%   |
| Intel Wireless 7260                                                    | 10        | 1.32%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 10        | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 9         | 1.19%   |
| Intel Wireless 7265                                                    | 9         | 1.19%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 7         | 0.92%   |
| Realtek Killer E2600 GbE Controller                                    | 7         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 6         | 0.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.66%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 5         | 0.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 0.53%   |
| Intel Wireless 3165                                                    | 4         | 0.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 0.53%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 4         | 0.53%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.53%   |
| Intel Ethernet Controller I225-V                                       | 4         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 197       | 48.64%  |
| Realtek Semiconductor           | 64        | 15.8%   |
| Qualcomm Atheros                | 52        | 12.84%  |
| Broadcom                        | 35        | 8.64%   |
| MediaTek                        | 33        | 8.15%   |
| Broadcom Limited                | 5         | 1.23%   |
| Ralink Technology               | 4         | 0.99%   |
| TP-Link                         | 3         | 0.74%   |
| Ralink                          | 3         | 0.74%   |
| Sierra Wireless                 | 2         | 0.49%   |
| Qualcomm Atheros Communications | 2         | 0.49%   |
| Microsoft                       | 2         | 0.49%   |
| ASUSTek Computer                | 2         | 0.49%   |
| Panasonic (Matsushita)          | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 34        | 8.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 5.65%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 4.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 18        | 4.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 4.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 16        | 3.93%   |
| Intel Wi-Fi 6 AX201                                            | 16        | 3.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14        | 3.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 2.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 2.95%   |
| Intel Wireless 8265 / 8275                                     | 11        | 2.7%    |
| Intel Wireless 8260                                            | 11        | 2.7%    |
| Broadcom BCM43142 802.11b/g/n                                  | 11        | 2.7%    |
| Intel Wireless 7260                                            | 10        | 2.46%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 10        | 2.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 2.21%   |
| Intel Wireless 7265                                            | 9         | 2.21%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 7         | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 1.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.23%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 5         | 1.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 0.98%   |
| Intel Wireless 3165                                            | 4         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.98%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 4         | 0.98%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 0.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 0.74%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 3         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.74%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.74%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.49%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 225       | 65.41%  |
| Intel                    | 48        | 13.95%  |
| Qualcomm Atheros         | 21        | 6.1%    |
| Broadcom                 | 8         | 2.33%   |
| Xiaomi                   | 7         | 2.03%   |
| ASIX Electronics         | 7         | 2.03%   |
| Samsung Electronics      | 5         | 1.45%   |
| Qualcomm                 | 4         | 1.16%   |
| Nvidia                   | 4         | 1.16%   |
| Marvell Technology Group | 4         | 1.16%   |
| Lenovo                   | 3         | 0.87%   |
| OPPO Electronics         | 1         | 0.29%   |
| Motorola PCS             | 1         | 0.29%   |
| JMicron Technology       | 1         | 0.29%   |
| Huawei Technologies      | 1         | 0.29%   |
| Google                   | 1         | 0.29%   |
| DisplayLink              | 1         | 0.29%   |
| Broadcom Limited         | 1         | 0.29%   |
| Apple                    | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 171       | 49.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 6.05%   |
| Realtek RTL8125 2.5GbE Controller                                      | 12        | 3.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 3.17%   |
| Realtek Killer E2600 GbE Controller                                    | 7         | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 1.73%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 1.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 1.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 1.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 1.15%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 1.15%   |
| Intel Ethernet Controller I225-V                                       | 4         | 1.15%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.15%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 3         | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.86%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.86%   |
| Intel Ethernet Connection I217-V                                       | 3         | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.58%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 2         | 0.58%   |
| Qualcomm Nokia G42 5G                                                  | 2         | 0.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.58%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 0.58%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.58%   |
| Intel Ethernet Connection (23) I219-V                                  | 2         | 0.58%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.29%   |
| Qualcomm SAMSUNG_Android                                               | 1         | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.29%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 391       | 54.53%  |
| Ethernet | 323       | 45.05%  |
| Modem    | 2         | 0.28%   |
| Unknown  | 1         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 312       | 74.46%  |
| Ethernet | 107       | 25.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 286       | 71.5%   |
| 1     | 109       | 27.25%  |
| 0     | 4         | 1%      |
| 3     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 290       | 72.14%  |
| Yes  | 112       | 27.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 189       | 52.07%  |
| Realtek Semiconductor           | 44        | 12.12%  |
| IMC Networks                    | 24        | 6.61%   |
| Qualcomm Atheros Communications | 23        | 6.34%   |
| Foxconn / Hon Hai               | 18        | 4.96%   |
| Lite-On Technology              | 17        | 4.68%   |
| Broadcom                        | 16        | 4.41%   |
| Apple                           | 9         | 2.48%   |
| Toshiba                         | 4         | 1.1%    |
| MediaTek                        | 4         | 1.1%    |
| Cambridge Silicon Radio         | 4         | 1.1%    |
| Ralink                          | 3         | 0.83%   |
| TP-Link                         | 2         | 0.55%   |
| Realtek                         | 2         | 0.55%   |
| Foxconn International           | 2         | 0.55%   |
| Hewlett-Packard                 | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 40        | 11.02%  |
| Intel AX200 Bluetooth                               | 34        | 9.37%   |
| Intel Bluetooth wireless interface                  | 32        | 8.82%   |
| Realtek Bluetooth Radio                             | 28        | 7.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 27        | 7.44%   |
| Intel Bluetooth Device                              | 20        | 5.51%   |
| Intel AX211 Bluetooth                               | 15        | 4.13%   |
| IMC Networks Wireless_Device                        | 13        | 3.58%   |
| Intel AX210 Bluetooth                               | 11        | 3.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 2.48%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 2.2%    |
| Apple Bluetooth Host Controller                     | 8         | 2.2%    |
| Realtek 802.11ac WLAN Adapter                       | 7         | 1.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 1.93%   |
| IMC Networks Bluetooth Radio                        | 7         | 1.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.65%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.38%   |
| Lite-On Bluetooth Device                            | 4         | 1.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.1%    |
| Ralink RT3290 Bluetooth                             | 3         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.83%   |
| MediaTek Wireless_Device                            | 3         | 0.83%   |
| IMC Networks Bluetooth Device                       | 3         | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.83%   |
| Broadcom BCM20702A0                                 | 3         | 0.83%   |
| TP-Link UB500 Adapter                               | 2         | 0.55%   |
| Toshiba BCM43142A0                                  | 2         | 0.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.55%   |
| Realtek Bluetooth Radio                             | 2         | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.55%   |
| Lite-On Wireless_Device                             | 2         | 0.55%   |
| Lite-On Bluetooth Radio                             | 2         | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.55%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.55%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 2         | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.55%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 270       | 44.93%  |
| AMD                         | 138       | 22.96%  |
| Nvidia                      | 133       | 22.13%  |
| Sony                        | 9         | 1.5%    |
| C-Media Electronics         | 6         | 1%      |
| Lenovo                      | 5         | 0.83%   |
| Logitech                    | 4         | 0.67%   |
| SteelSeries ApS             | 3         | 0.5%    |
| Razer USA                   | 3         | 0.5%    |
| TTGK Technology             | 2         | 0.33%   |
| Hewlett-Packard             | 2         | 0.33%   |
| Creative Technology         | 2         | 0.33%   |
| Apple                       | 2         | 0.33%   |
| XMOS                        | 1         | 0.17%   |
| Turtle Beach                | 1         | 0.17%   |
| Texas Instruments           | 1         | 0.17%   |
| Tenx Technology             | 1         | 0.17%   |
| Silicon Motion              | 1         | 0.17%   |
| Samsung Electronics         | 1         | 0.17%   |
| RODE Microphones            | 1         | 0.17%   |
| ROCCAT                      | 1         | 0.17%   |
| Realtek Semiconductor       | 1         | 0.17%   |
| PreSonus Audio Electronics  | 1         | 0.17%   |
| Native Instruments          | 1         | 0.17%   |
| Micro Star International    | 1         | 0.17%   |
| Kingston Technology         | 1         | 0.17%   |
| Goldvish                    | 1         | 0.17%   |
| GN Netcom                   | 1         | 0.17%   |
| Generalplus Technology      | 1         | 0.17%   |
| FiiO Electronics Technology | 1         | 0.17%   |
| Corsair                     | 1         | 0.17%   |
| BR25                        | 1         | 0.17%   |
| Blue Microphones            | 1         | 0.17%   |
| Audio-Technica              | 1         | 0.17%   |
| ASUSTek Computer            | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 99        | 13.32%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 43        | 5.79%   |
| Intel Cannon Lake PCH cAVS                                                 | 29        | 3.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 28        | 3.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 24        | 3.23%   |
| Intel Comet Lake PCH cAVS                                                  | 24        | 3.23%   |
| Intel 8 Series HD Audio Controller                                         | 24        | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 23        | 3.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 2.96%   |
| Nvidia GA106 High Definition Audio Controller                              | 21        | 2.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 20        | 2.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 2.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 2.29%   |
| Nvidia TU106 High Definition Audio Controller                              | 16        | 2.15%   |
| Nvidia Audio device                                                        | 16        | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15        | 2.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12        | 1.62%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 12        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 1.48%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 1.35%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 1.21%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 9         | 1.21%   |
| Intel CM238 HD Audio Controller                                            | 9         | 1.21%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 1.08%   |
| Sony DualSense wireless controller (PS5)                                   | 7         | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 0.94%   |
| AMD FCH Azalia Controller                                                  | 7         | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 0.67%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 0.67%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 0.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 31.4%   |
| Micron Technology   | 24        | 19.83%  |
| SK hynix            | 22        | 18.18%  |
| Kingston            | 6         | 4.96%   |
| Crucial             | 5         | 4.13%   |
| Unknown             | 4         | 3.31%   |
| Corsair             | 4         | 3.31%   |
| Ramaxel Technology  | 3         | 2.48%   |
| G.Skill             | 3         | 2.48%   |
| Unknown (ABCD)      | 2         | 1.65%   |
| Team                | 2         | 1.65%   |
| A-DATA Technology   | 2         | 1.65%   |
| Transcend           | 1         | 0.83%   |
| Nanya Technology    | 1         | 0.83%   |
| Gowe                | 1         | 0.83%   |
| Elpida              | 1         | 0.83%   |
| AMD                 | 1         | 0.83%   |
| Unknown             | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 5         | 3.97%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 3.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.38%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.59%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 1.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.59%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s         | 2         | 1.59%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 1.59%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 2         | 1.59%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 2         | 1.59%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.59%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.59%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.59%   |
| Corsair RAM CMSX32GX4M2A2400C16 16GB SODIMM DDR4 2400MT/s        | 2         | 1.59%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.79%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.79%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.79%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.79%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 0.79%   |
| Team RAM TEAMGROUP-SD4-3200 16384MB SODIMM DDR4 3200MT/s         | 1         | 0.79%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.79%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.79%   |
| SK hynix RAM HMCG88MEBSA095N 32GB SODIMM DDR5 4800MT/s           | 1         | 0.79%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 0.79%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.79%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.79%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.79%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 61        | 61%     |
| DDR5    | 13        | 13%     |
| DDR3    | 13        | 13%     |
| LPDDR4  | 9         | 9%      |
| LPDDR5  | 1         | 1%      |
| LPDDR3  | 1         | 1%      |
| DDR2    | 1         | 1%      |
| Unknown | 1         | 1%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 86.14%  |
| Row Of Chips | 13        | 12.87%  |
| DIMM         | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 54        | 49.54%  |
| 4096  | 21        | 19.27%  |
| 16384 | 20        | 18.35%  |
| 32768 | 9         | 8.26%   |
| 2048  | 5         | 4.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 35        | 33.65%  |
| 2667  | 22        | 21.15%  |
| 1600  | 11        | 10.58%  |
| 4800  | 9         | 8.65%   |
| 2400  | 6         | 5.77%   |
| 5600  | 3         | 2.88%   |
| 4267  | 3         | 2.88%   |
| 2133  | 3         | 2.88%   |
| 6400  | 2         | 1.92%   |
| 3266  | 2         | 1.92%   |
| 1333  | 2         | 1.92%   |
| 5200  | 1         | 0.96%   |
| 4266  | 1         | 0.96%   |
| 3600  | 1         | 0.96%   |
| 3333  | 1         | 0.96%   |
| 1334  | 1         | 0.96%   |
| 975   | 1         | 0.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Samsung Composite Device | 1         | 100%    |

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
| Chicony Electronics                    | 80        | 23.05%  |
| IMC Networks                           | 39        | 11.24%  |
| Realtek Semiconductor                  | 25        | 7.2%    |
| Quanta                                 | 22        | 6.34%   |
| Microdia                               | 21        | 6.05%   |
| Bison Electronics                      | 20        | 5.76%   |
| Syntek                                 | 18        | 5.19%   |
| Sunplus Innovation Technology          | 17        | 4.9%    |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.03%   |
| Sonix Technology                       | 13        | 3.75%   |
| Lite-On Technology                     | 10        | 2.88%   |
| Apple                                  | 10        | 2.88%   |
| Logitech                               | 9         | 2.59%   |
| Suyin                                  | 8         | 2.31%   |
| Luxvisions Innotech Limited            | 8         | 2.31%   |
| Acer                                   | 8         | 2.31%   |
| Samsung Electronics                    | 4         | 1.15%   |
| Silicon Motion                         | 3         | 0.86%   |
| Tobii Technology AB                    | 2         | 0.58%   |
| SunplusIT                              | 2         | 0.58%   |
| Intel                                  | 2         | 0.58%   |
| HRY                                    | 2         | 0.58%   |
| Z-Star Microelectronics                | 1         | 0.29%   |
| Shine-optics                           | 1         | 0.29%   |
| Ruision                                | 1         | 0.29%   |
| Ricoh                                  | 1         | 0.29%   |
| Lenovo                                 | 1         | 0.29%   |
| Importek                               | 1         | 0.29%   |
| Google                                 | 1         | 0.29%   |
| Goodong Industry                       | 1         | 0.29%   |
| Alcor Micro                            | 1         | 0.29%   |
| Unknown                                | 1         | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 18        | 5.16%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 15        | 4.3%    |
| Realtek Integrated_Webcam_HD                        | 13        | 3.72%   |
| Syntek Integrated Camera                            | 12        | 3.44%   |
| IMC Networks Integrated Camera                      | 10        | 2.87%   |
| Sonix USB2.0 HD UVC WebCam                          | 9         | 2.58%   |
| Microdia Integrated_Webcam_HD                       | 9         | 2.58%   |
| Chicony HD Webcam                                   | 9         | 2.58%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 2.01%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 6         | 1.72%   |
| Bison HD Webcam                                     | 6         | 1.72%   |
| Quanta HP TrueVision HD Camera                      | 5         | 1.43%   |
| Quanta HD User Facing                               | 5         | 1.43%   |
| Chicony HD User Facing                              | 5         | 1.43%   |
| Sunplus HD WebCam                                   | 4         | 1.15%   |
| Sonix USB2.0 FHD UVC WebCam                         | 4         | 1.15%   |
| Samsung Galaxy series, misc. (MTP mode)             | 4         | 1.15%   |
| Quanta HP Wide Vision HD Camera                     | 4         | 1.15%   |
| Microdia USB 2.0 Camera                             | 4         | 1.15%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 1.15%   |
| Chicony USB2.0 Camera                               | 4         | 1.15%   |
| Chicony HP TrueVision HD                            | 4         | 1.15%   |
| Bison Lenovo Integrated Webcam                      | 4         | 1.15%   |
| Bison BisonCam,NB Pro                               | 4         | 1.15%   |
| Apple FaceTime HD Camera                            | 4         | 1.15%   |
| Syntek Lenovo EasyCamera                            | 3         | 0.86%   |
| Realtek USB Camera                                  | 3         | 0.86%   |
| Quanta VGA WebCam                                   | 3         | 0.86%   |
| Microdia Laptop_Integrated_Webcam_HD                | 3         | 0.86%   |
| Lite-On HP HD Webcam                                | 3         | 0.86%   |
| Chicony VGA Webcam                                  | 3         | 0.86%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 0.86%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 0.86%   |
| Chicony Integrated IR Camera                        | 3         | 0.86%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 3         | 0.86%   |
| Apple Built-in iSight                               | 3         | 0.86%   |
| Acer Integrated Camera                              | 3         | 0.86%   |
| Tobii AB EyeChip                                    | 2         | 0.57%   |
| Syntek EasyCamera                                   | 2         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 16        | 32.65%  |
| Synaptics                          | 12        | 24.49%  |
| Shenzhen Goodix Technology         | 9         | 18.37%  |
| Elan Microelectronics              | 6         | 12.24%  |
| Realtek USB2.0 Finger Print Bridge | 3         | 6.12%   |
| Focal-systems.Corp                 | 2         | 4.08%   |
| LighTuning Technology              | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 9         | 18.37%  |
| Shenzhen Goodix  Fingerprint Device                             | 7         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 3         | 6.12%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 6.12%   |
| Elan ELAN:Fingerprint                                           | 3         | 6.12%   |
| Elan ELAN:ARM-M4                                                | 3         | 6.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 4.08%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 4.08%   |
| Synaptics WBDI Device                                           | 2         | 4.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 4.08%   |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 4.08%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 4.08%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 2         | 4.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 2.04%   |
| Validity Sensors VFS491                                         | 1         | 2.04%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 2.04%   |
| Synaptics WBDI                                                  | 1         | 2.04%   |
| Synaptics UWP WBDI Device                                       | 1         | 2.04%   |
| Synaptics  WBDI                                                 | 1         | 2.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 7         | 70%     |
| Alcor Micro           | 2         | 20%     |
| Gemalto (was Gemplus) | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 58200                                                               | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 268       | 66.01%  |
| 1     | 115       | 28.33%  |
| 2     | 21        | 5.17%   |
| 3     | 2         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 29.01%  |
| Graphics card            | 40        | 24.69%  |
| Multimedia controller    | 35        | 21.6%   |
| Net/wireless             | 26        | 16.05%  |
| Bluetooth                | 4         | 2.47%   |
| Chipcard                 | 2         | 1.23%   |
| Camera                   | 2         | 1.23%   |
| Storage/nvme             | 1         | 0.62%   |
| Storage                  | 1         | 0.62%   |
| Sound                    | 1         | 0.62%   |
| Modem                    | 1         | 0.62%   |
| Communication controller | 1         | 0.62%   |
| Card reader              | 1         | 0.62%   |


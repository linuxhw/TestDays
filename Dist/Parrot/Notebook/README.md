Parrot - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Parrot.

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

Total: 661

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | XPS 13 9305                 | [5b06a32fea](https://linux-hardware.org/?probe=5b06a32fea) | Jan 06, 2025 |
| Acer          | Nitro AN515-55              | [87f960a021](https://linux-hardware.org/?probe=87f960a021) | Jan 05, 2025 |
| HP            | Laptop 17-cn0xxx            | [63b427416a](https://linux-hardware.org/?probe=63b427416a) | Jan 02, 2025 |
| Acer          | Aspire A315-510P            | [f3fd803275](https://linux-hardware.org/?probe=f3fd803275) | Jan 01, 2025 |
| Acer          | Aspire A315-510P            | [b079131625](https://linux-hardware.org/?probe=b079131625) | Dec 30, 2024 |
| Acer          | Aspire A315-510P            | [ede893e1e1](https://linux-hardware.org/?probe=ede893e1e1) | Dec 30, 2024 |
| HP            | Laptop 17-cn0xxx            | [f1382538df](https://linux-hardware.org/?probe=f1382538df) | Dec 28, 2024 |
| HP            | ProBook 440 G7              | [205f2940e7](https://linux-hardware.org/?probe=205f2940e7) | Dec 24, 2024 |
| ASUSTek       | S400CA                      | [a076c3dca9](https://linux-hardware.org/?probe=a076c3dca9) | Dec 20, 2024 |
| HP            | EliteBook Folio 9480m       | [7d0e5bbe48](https://linux-hardware.org/?probe=7d0e5bbe48) | Dec 14, 2024 |
| HP            | Laptop 15-fd0xxx            | [e96ccf6429](https://linux-hardware.org/?probe=e96ccf6429) | Dec 10, 2024 |
| MSI           | Katana GF66 11UE            | [b74e19bf4f](https://linux-hardware.org/?probe=b74e19bf4f) | Dec 10, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [cb5e7488d1](https://linux-hardware.org/?probe=cb5e7488d1) | Dec 07, 2024 |
| Apple         | MacBookPro9,2               | [bd90895fef](https://linux-hardware.org/?probe=bd90895fef) | Dec 07, 2024 |
| ASUSTek       | S400CA                      | [6b626eb981](https://linux-hardware.org/?probe=6b626eb981) | Dec 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [8a363e4242](https://linux-hardware.org/?probe=8a363e4242) | Nov 29, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | [e55906c344](https://linux-hardware.org/?probe=e55906c344) | Nov 28, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [fd5c871a74](https://linux-hardware.org/?probe=fd5c871a74) | Nov 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4da22094eb](https://linux-hardware.org/?probe=4da22094eb) | Nov 25, 2024 |
| Google        | Caroline                    | [3783098457](https://linux-hardware.org/?probe=3783098457) | Nov 23, 2024 |
| Dell          | Latitude 7490               | [47d677a13e](https://linux-hardware.org/?probe=47d677a13e) | Nov 22, 2024 |
| HP            | EliteBook 2560p             | [84d5a17ce2](https://linux-hardware.org/?probe=84d5a17ce2) | Nov 12, 2024 |
| Panasonic     | FZ55-2                      | [72e6f447fd](https://linux-hardware.org/?probe=72e6f447fd) | Nov 09, 2024 |
| HP            | 250 G7 Notebook PC          | [a3e0d131dc](https://linux-hardware.org/?probe=a3e0d131dc) | Nov 01, 2024 |
| Lenovo        | ThinkPad X260 20F5A13P00    | [4ac4d50f73](https://linux-hardware.org/?probe=4ac4d50f73) | Oct 17, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [5a97215ee3](https://linux-hardware.org/?probe=5a97215ee3) | Oct 15, 2024 |
| HP            | Pavilion Laptop 15-cc5xx    | [7cdb58b80e](https://linux-hardware.org/?probe=7cdb58b80e) | Oct 10, 2024 |
| Acer          | Aspire A515-51G             | [020774040e](https://linux-hardware.org/?probe=020774040e) | Oct 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [38d2b1b15c](https://linux-hardware.org/?probe=38d2b1b15c) | Oct 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [d52e4fc3c0](https://linux-hardware.org/?probe=d52e4fc3c0) | Oct 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [cb3a3420ad](https://linux-hardware.org/?probe=cb3a3420ad) | Oct 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [a0adceb41d](https://linux-hardware.org/?probe=a0adceb41d) | Sep 26, 2024 |
| Apple         | MacBookPro11,1              | [22961f031e](https://linux-hardware.org/?probe=22961f031e) | Sep 24, 2024 |
| HP            | Laptop 15-dw2xxx            | [08230cbafb](https://linux-hardware.org/?probe=08230cbafb) | Sep 03, 2024 |
| Lenovo        | ThinkPad T450s 20BX001EU... | [fd7ece1b23](https://linux-hardware.org/?probe=fd7ece1b23) | Sep 01, 2024 |
| Panasonic     | CF-31-5                     | [3dc2b9bef7](https://linux-hardware.org/?probe=3dc2b9bef7) | Aug 30, 2024 |
| Panasonic     | CF-31-5                     | [15b61b0ba5](https://linux-hardware.org/?probe=15b61b0ba5) | Aug 30, 2024 |
| HP            | ProBook 650 G8 Notebook ... | [faf752e7d5](https://linux-hardware.org/?probe=faf752e7d5) | Aug 27, 2024 |
| HP            | ProBook 650 G8 Notebook ... | [4870c26466](https://linux-hardware.org/?probe=4870c26466) | Aug 27, 2024 |
| HP            | EliteBook 830 G6            | [453f8f7b00](https://linux-hardware.org/?probe=453f8f7b00) | Aug 25, 2024 |
| HP            | EliteBook 830 G6            | [082baba5be](https://linux-hardware.org/?probe=082baba5be) | Aug 25, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [a10bc8baff](https://linux-hardware.org/?probe=a10bc8baff) | Aug 23, 2024 |
| Dell          | Inspiron 7559               | [1b8c70c653](https://linux-hardware.org/?probe=1b8c70c653) | Aug 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [752156b44a](https://linux-hardware.org/?probe=752156b44a) | Aug 16, 2024 |
| Acer          | Aspire ES1-431              | [7dd0a748d7](https://linux-hardware.org/?probe=7dd0a748d7) | Aug 14, 2024 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [f01ca35d63](https://linux-hardware.org/?probe=f01ca35d63) | Aug 05, 2024 |
| HP            | Victus by Gaming Laptop ... | [22c0d405de](https://linux-hardware.org/?probe=22c0d405de) | Aug 01, 2024 |
| Acer          | Predator PT314-51s          | [8eda2b6d8a](https://linux-hardware.org/?probe=8eda2b6d8a) | Jul 28, 2024 |
| HP            | 250 G7 Notebook PC          | [154385f06a](https://linux-hardware.org/?probe=154385f06a) | Jul 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [224fdf8c28](https://linux-hardware.org/?probe=224fdf8c28) | Jul 23, 2024 |
| HP            | EliteBook 850 G3            | [5a3d8f3ce0](https://linux-hardware.org/?probe=5a3d8f3ce0) | Jul 23, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [34fa837cb3](https://linux-hardware.org/?probe=34fa837cb3) | Jul 18, 2024 |
| Dell          | Latitude 5511               | [6094708e32](https://linux-hardware.org/?probe=6094708e32) | Jul 14, 2024 |
| MSI           | Prestige 13 AI Evo A1MG     | [f201feeb20](https://linux-hardware.org/?probe=f201feeb20) | Jul 14, 2024 |
| HUAWEI        | HVY-WXX9                    | [6ad8913d16](https://linux-hardware.org/?probe=6ad8913d16) | Jul 09, 2024 |
| HUAWEI        | HVY-WXX9                    | [4d4543ae64](https://linux-hardware.org/?probe=4d4543ae64) | Jul 09, 2024 |
| HP            | 250 G7 Notebook PC          | [38b439c526](https://linux-hardware.org/?probe=38b439c526) | Jul 06, 2024 |
| Lenovo        | E50-80 80J2                 | [6ef0c878e3](https://linux-hardware.org/?probe=6ef0c878e3) | Jul 06, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [290e8e87d1](https://linux-hardware.org/?probe=290e8e87d1) | Jun 28, 2024 |
| Razer         | Blade 15 (2022) - RZ09-0... | [c22d1433bf](https://linux-hardware.org/?probe=c22d1433bf) | Jun 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e570948d49](https://linux-hardware.org/?probe=e570948d49) | Jun 10, 2024 |
| HP            | Laptop 15-dy2xxx            | [d5de03918b](https://linux-hardware.org/?probe=d5de03918b) | Jun 05, 2024 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [93ed456d67](https://linux-hardware.org/?probe=93ed456d67) | Jun 02, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [3779586782](https://linux-hardware.org/?probe=3779586782) | May 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7642e68170](https://linux-hardware.org/?probe=7642e68170) | May 16, 2024 |
| Lenovo        | ThinkPad T410 2537VXX       | [a5aa605397](https://linux-hardware.org/?probe=a5aa605397) | May 10, 2024 |
| Toshiba       | Satellite E55-A             | [b77667e33a](https://linux-hardware.org/?probe=b77667e33a) | May 08, 2024 |
| HP            | 2000                        | [71d3942f81](https://linux-hardware.org/?probe=71d3942f81) | May 06, 2024 |
| Acer          | Aspire E1-522               | [b1c41ef5a0](https://linux-hardware.org/?probe=b1c41ef5a0) | May 04, 2024 |
| Dell          | Latitude E6430              | [3ea51c9416](https://linux-hardware.org/?probe=3ea51c9416) | May 04, 2024 |
| Dell          | Latitude E6430              | [0e3b2e7c55](https://linux-hardware.org/?probe=0e3b2e7c55) | May 04, 2024 |
| Toshiba       | Satellite E55-A             | [66fc7bf95a](https://linux-hardware.org/?probe=66fc7bf95a) | Apr 30, 2024 |
| Acidanther... | MacBookAir9,1               | [ba60edeb99](https://linux-hardware.org/?probe=ba60edeb99) | Apr 25, 2024 |
| MSI           | GL75 9SEK                   | [3d679e4ec2](https://linux-hardware.org/?probe=3d679e4ec2) | Apr 17, 2024 |
| MSI           | GL75 9SEK                   | [b2d528d9b4](https://linux-hardware.org/?probe=b2d528d9b4) | Apr 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [6291093e82](https://linux-hardware.org/?probe=6291093e82) | Apr 16, 2024 |
| Lenovo        | E41-25 81FS                 | [ee47604b55](https://linux-hardware.org/?probe=ee47604b55) | Apr 13, 2024 |
| HP            | Laptop 14-cf2xxx            | [bc17e5113b](https://linux-hardware.org/?probe=bc17e5113b) | Apr 13, 2024 |
| HP            | Laptop 14-cf2xxx            | [bef6cb8975](https://linux-hardware.org/?probe=bef6cb8975) | Apr 13, 2024 |
| Lenovo        | Z50-70 20354                | [4469cb6e76](https://linux-hardware.org/?probe=4469cb6e76) | Apr 10, 2024 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [2c23a28e81](https://linux-hardware.org/?probe=2c23a28e81) | Apr 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c737a816f3](https://linux-hardware.org/?probe=c737a816f3) | Apr 04, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [d0eac00952](https://linux-hardware.org/?probe=d0eac00952) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c498cd96d4](https://linux-hardware.org/?probe=c498cd96d4) | Mar 31, 2024 |
| Razer         | Blade 15 - RZ09-0485        | [24980909b2](https://linux-hardware.org/?probe=24980909b2) | Mar 26, 2024 |
| HP            | EliteBook 830 G6            | [955e65cc0f](https://linux-hardware.org/?probe=955e65cc0f) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | [c5ada253ab](https://linux-hardware.org/?probe=c5ada253ab) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | [2ab6329c32](https://linux-hardware.org/?probe=2ab6329c32) | Mar 22, 2024 |
| Acer          | Extensa 5230                | [790672cb92](https://linux-hardware.org/?probe=790672cb92) | Mar 22, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | [700d8c6016](https://linux-hardware.org/?probe=700d8c6016) | Mar 18, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | [63c84de71e](https://linux-hardware.org/?probe=63c84de71e) | Mar 15, 2024 |
| Dell          | Latitude 5420 Rugged        | [f9c7c915c9](https://linux-hardware.org/?probe=f9c7c915c9) | Mar 08, 2024 |
| Apple         | MacBookAir7,2               | [58e64cec89](https://linux-hardware.org/?probe=58e64cec89) | Mar 06, 2024 |
| Apple         | MacBookAir7,2               | [74faba00a3](https://linux-hardware.org/?probe=74faba00a3) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | [16326b521f](https://linux-hardware.org/?probe=16326b521f) | Mar 01, 2024 |
| Dell          | XPS 13 9370                 | [086a1782c7](https://linux-hardware.org/?probe=086a1782c7) | Feb 22, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | [da65aaff1d](https://linux-hardware.org/?probe=da65aaff1d) | Feb 20, 2024 |
| Samsung       | 750XDA                      | [0aed547d08](https://linux-hardware.org/?probe=0aed547d08) | Feb 18, 2024 |
| HP            | Pavilion dv4                | [20e9de9ad8](https://linux-hardware.org/?probe=20e9de9ad8) | Feb 08, 2024 |
| ASUSTek       | UX430UAR                    | [cc89a20253](https://linux-hardware.org/?probe=cc89a20253) | Feb 04, 2024 |
| Apple         | MacBookPro11,1              | [fcabd4a1f4](https://linux-hardware.org/?probe=fcabd4a1f4) | Feb 01, 2024 |
| Apple         | MacBookPro11,1              | [b31d7d9323](https://linux-hardware.org/?probe=b31d7d9323) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480s 20L70028U... | [7acd38748f](https://linux-hardware.org/?probe=7acd38748f) | Jan 30, 2024 |
| Apple         | MacBookPro11,1              | [7c4514376b](https://linux-hardware.org/?probe=7c4514376b) | Jan 27, 2024 |
| Apple         | MacBookPro11,1              | [f1117537a5](https://linux-hardware.org/?probe=f1117537a5) | Jan 27, 2024 |
| Acer          | Aspire A715-51G             | [fad23c2b03](https://linux-hardware.org/?probe=fad23c2b03) | Jan 27, 2024 |
| Dell          | XPS 13 9350                 | [fb1c7c4cab](https://linux-hardware.org/?probe=fb1c7c4cab) | Jan 26, 2024 |
| Lenovo        | ThinkPad T460s 20FAS2JW0... | [59d637113b](https://linux-hardware.org/?probe=59d637113b) | Jan 26, 2024 |
| Acer          | Aspire E1-522               | [a43c97b66c](https://linux-hardware.org/?probe=a43c97b66c) | Jan 26, 2024 |
| HP            | ProBook 455 G4              | [6490d02d72](https://linux-hardware.org/?probe=6490d02d72) | Jan 22, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [bb5610a4f5](https://linux-hardware.org/?probe=bb5610a4f5) | Jan 17, 2024 |
| Acer          | Aspire E1-522               | [538c5ee96f](https://linux-hardware.org/?probe=538c5ee96f) | Jan 16, 2024 |
| HP            | Victus by Gaming Laptop ... | [feaf3edd58](https://linux-hardware.org/?probe=feaf3edd58) | Jan 10, 2024 |
| Acer          | Aspire A715-51G             | [2a3ea77b7a](https://linux-hardware.org/?probe=2a3ea77b7a) | Jan 10, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | [ce82358c06](https://linux-hardware.org/?probe=ce82358c06) | Jan 04, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | [ffe96991b4](https://linux-hardware.org/?probe=ffe96991b4) | Jan 04, 2024 |
| HP            | ProBook 450 G5              | [b80a7c9287](https://linux-hardware.org/?probe=b80a7c9287) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [1f44330bcf](https://linux-hardware.org/?probe=1f44330bcf) | Dec 31, 2023 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [0afd47e9fc](https://linux-hardware.org/?probe=0afd47e9fc) | Dec 31, 2023 |
| Google        | Blorb                       | [4e0c068a82](https://linux-hardware.org/?probe=4e0c068a82) | Dec 30, 2023 |
| HP            | Pavilion g6                 | [62a002d063](https://linux-hardware.org/?probe=62a002d063) | Dec 26, 2023 |
| Apple         | MacBookAir5,1               | [5c7029f981](https://linux-hardware.org/?probe=5c7029f981) | Dec 23, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [980280224f](https://linux-hardware.org/?probe=980280224f) | Dec 18, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [41f03f0699](https://linux-hardware.org/?probe=41f03f0699) | Dec 18, 2023 |
| Toshiba       | PORTEGE R930                | [e341599417](https://linux-hardware.org/?probe=e341599417) | Dec 14, 2023 |
| HP            | EliteBook 850 G3            | [baf21dcbce](https://linux-hardware.org/?probe=baf21dcbce) | Dec 06, 2023 |
| ASUSTek       | X540SAA                     | [86295630b8](https://linux-hardware.org/?probe=86295630b8) | Dec 06, 2023 |
| Alienware     | 17 R5                       | [e0fdc679e3](https://linux-hardware.org/?probe=e0fdc679e3) | Dec 04, 2023 |
| Alienware     | 17 R5                       | [1e44992982](https://linux-hardware.org/?probe=1e44992982) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [30c19ab13f](https://linux-hardware.org/?probe=30c19ab13f) | Dec 04, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [d416d62cf1](https://linux-hardware.org/?probe=d416d62cf1) | Nov 29, 2023 |
| Acer          | Nitro AN517-55              | [91df918363](https://linux-hardware.org/?probe=91df918363) | Nov 28, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [a54c387b5f](https://linux-hardware.org/?probe=a54c387b5f) | Nov 27, 2023 |
| Apple         | MacBookAir6,1               | [e22c72e9d4](https://linux-hardware.org/?probe=e22c72e9d4) | Nov 26, 2023 |
| Apple         | MacBookAir6,1               | [dfa296fd96](https://linux-hardware.org/?probe=dfa296fd96) | Nov 25, 2023 |
| Lenovo        | Flex 2-15 20405             | [8ad2369936](https://linux-hardware.org/?probe=8ad2369936) | Nov 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a8e951e3b6](https://linux-hardware.org/?probe=a8e951e3b6) | Nov 20, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B30... | [5685f17122](https://linux-hardware.org/?probe=5685f17122) | Nov 19, 2023 |
| Acer          | TravelMate 5760             | [f90be838c9](https://linux-hardware.org/?probe=f90be838c9) | Nov 18, 2023 |
| Acer          | TravelMate 5760             | [db234d226d](https://linux-hardware.org/?probe=db234d226d) | Nov 18, 2023 |
| Dell          | Latitude E6530              | [f43bd72db4](https://linux-hardware.org/?probe=f43bd72db4) | Nov 16, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [20394838bd](https://linux-hardware.org/?probe=20394838bd) | Nov 11, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [e7b5bfa0b4](https://linux-hardware.org/?probe=e7b5bfa0b4) | Nov 06, 2023 |
| Unknown       | Unknown                     | [2c2d291f54](https://linux-hardware.org/?probe=2c2d291f54) | Nov 05, 2023 |
| MSI           | Prestige 14Evo A12M         | [98e32e98bf](https://linux-hardware.org/?probe=98e32e98bf) | Oct 31, 2023 |
| HP            | EliteBook 850 G3            | [be57c0ce22](https://linux-hardware.org/?probe=be57c0ce22) | Oct 29, 2023 |
| Google        | Reef                        | [819e00dd76](https://linux-hardware.org/?probe=819e00dd76) | Oct 22, 2023 |
| Acer          | Extensa 215-54              | [4e2a3f7606](https://linux-hardware.org/?probe=4e2a3f7606) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | [94d47a3e29](https://linux-hardware.org/?probe=94d47a3e29) | Oct 15, 2023 |
| HP            | ENVY m6 Notebook            | [fb0b3ea9e7](https://linux-hardware.org/?probe=fb0b3ea9e7) | Oct 12, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [30b0879baa](https://linux-hardware.org/?probe=30b0879baa) | Oct 07, 2023 |
| Dell          | XPS 15 9500                 | [ee251b10d4](https://linux-hardware.org/?probe=ee251b10d4) | Oct 07, 2023 |
| Samsung       | 550XBE/350XBE               | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | [3185dde146](https://linux-hardware.org/?probe=3185dde146) | Oct 04, 2023 |
| HP            | ENVY m6 Notebook            | [5ef983c393](https://linux-hardware.org/?probe=5ef983c393) | Oct 01, 2023 |
| Lenovo        | Z51-70 80K6                 | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [37ecdee3d3](https://linux-hardware.org/?probe=37ecdee3d3) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [ecc0e92fb0](https://linux-hardware.org/?probe=ecc0e92fb0) | Sep 24, 2023 |
| HP            | Laptop 15-dy2xxx            | [faa9a71ce1](https://linux-hardware.org/?probe=faa9a71ce1) | Sep 17, 2023 |
| MSI           | Stealth 15M B12UE           | [2f99528572](https://linux-hardware.org/?probe=2f99528572) | Sep 16, 2023 |
| HP            | Laptop 17-cn0xxx            | [6495df6735](https://linux-hardware.org/?probe=6495df6735) | Sep 15, 2023 |
| ASUSTek       | S550CB                      | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| Toshiba       | Satellite L775D             | [681dab0969](https://linux-hardware.org/?probe=681dab0969) | Sep 09, 2023 |
| Dell          | Latitude 7280               | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| HP            | EliteBook 840 14 inch G9... | [ec33c11aa1](https://linux-hardware.org/?probe=ec33c11aa1) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [101a39c37a](https://linux-hardware.org/?probe=101a39c37a) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [da3ab01b3a](https://linux-hardware.org/?probe=da3ab01b3a) | Aug 25, 2023 |
| MSI           | Katana 15 B13VGK            | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| MSI           | Summit E14Evo A12M          | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [324819c88d](https://linux-hardware.org/?probe=324819c88d) | Aug 08, 2023 |
| Acer          | Aspire 4810T                | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [d3999a626a](https://linux-hardware.org/?probe=d3999a626a) | Aug 07, 2023 |
| Dell          | Precision 7730              | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| HP            | EliteBook 850 G3            | [ad4e7cf4ad](https://linux-hardware.org/?probe=ad4e7cf4ad) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | [36d9df3244](https://linux-hardware.org/?probe=36d9df3244) | Jul 31, 2023 |
| MSI           | Katana 17 B13VFK            | [8bc597da6e](https://linux-hardware.org/?probe=8bc597da6e) | Jul 29, 2023 |
| MSI           | Katana GF66 11UE            | [78e12df29a](https://linux-hardware.org/?probe=78e12df29a) | Jul 28, 2023 |
| HP            | ProBook 650 G2              | [cea811cc5f](https://linux-hardware.org/?probe=cea811cc5f) | Jul 25, 2023 |
| HP            | Laptop 15-dy2xxx            | [d047b35269](https://linux-hardware.org/?probe=d047b35269) | Jul 25, 2023 |
| HP            | ProBook 650 G2              | [affdd0a6f9](https://linux-hardware.org/?probe=affdd0a6f9) | Jul 25, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [af539103c5](https://linux-hardware.org/?probe=af539103c5) | Jul 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [58882ecdfe](https://linux-hardware.org/?probe=58882ecdfe) | Jul 20, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8abec746f7](https://linux-hardware.org/?probe=8abec746f7) | Jul 19, 2023 |
| HP            | Laptop 15-dy2xxx            | [3e6412c30b](https://linux-hardware.org/?probe=3e6412c30b) | Jul 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8e533f69a9](https://linux-hardware.org/?probe=8e533f69a9) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [c4b019ee7f](https://linux-hardware.org/?probe=c4b019ee7f) | Jul 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d7c21e7889](https://linux-hardware.org/?probe=d7c21e7889) | Jul 13, 2023 |
| Acer          | Aspire A515-47              | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Aspire A315-23              | [b5a021ae8a](https://linux-hardware.org/?probe=b5a021ae8a) | Jul 10, 2023 |
| Samsung       | 750XED                      | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| Dell          | Latitude 3410               | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| HP            | EliteBook 860 16 inch G9... | [4a4b49a909](https://linux-hardware.org/?probe=4a4b49a909) | Jul 03, 2023 |
| HP            | Laptop 15-dy2xxx            | [12871de62d](https://linux-hardware.org/?probe=12871de62d) | Jun 30, 2023 |
| HP            | Laptop 15-dy2xxx            | [ea4a5ccb1a](https://linux-hardware.org/?probe=ea4a5ccb1a) | Jun 29, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [a4b38b88cc](https://linux-hardware.org/?probe=a4b38b88cc) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [e28a0d43ed](https://linux-hardware.org/?probe=e28a0d43ed) | Jun 27, 2023 |
| HP            | ENVY m6 Notebook            | [ee31bf4efe](https://linux-hardware.org/?probe=ee31bf4efe) | Jun 26, 2023 |
| Unknown       | Unknown                     | [9c8513ff31](https://linux-hardware.org/?probe=9c8513ff31) | Jun 25, 2023 |
| HONOR         | BMH-WCX9                    | [f40cb826de](https://linux-hardware.org/?probe=f40cb826de) | Jun 25, 2023 |
| Samsung       | 530XBB                      | [51007aebd3](https://linux-hardware.org/?probe=51007aebd3) | Jun 24, 2023 |
| HP            | EliteBook 850 G3            | [3055046330](https://linux-hardware.org/?probe=3055046330) | Jun 20, 2023 |
| Lenovo        | ThinkPad L490 20Q5001YMX    | [c04ebf8de3](https://linux-hardware.org/?probe=c04ebf8de3) | Jun 20, 2023 |
| HP            | EliteBook 850 G3            | [2102fc8523](https://linux-hardware.org/?probe=2102fc8523) | Jun 19, 2023 |
| HP            | ENVY m6 Notebook            | [464db6c1df](https://linux-hardware.org/?probe=464db6c1df) | Jun 18, 2023 |
| Lenovo        | ThinkPad L520 78595GJ       | [52faa96ad0](https://linux-hardware.org/?probe=52faa96ad0) | Jun 17, 2023 |
| Dell          | Latitude 7430               | [e25ec87b40](https://linux-hardware.org/?probe=e25ec87b40) | Jun 17, 2023 |
| Dell          | Latitude 7430               | [35c6e2b80e](https://linux-hardware.org/?probe=35c6e2b80e) | Jun 17, 2023 |
| ASUSTek       | X550CL                      | [20a66afa75](https://linux-hardware.org/?probe=20a66afa75) | Jun 14, 2023 |
| Dell          | Vostro 3550                 | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| HP            | ENVY m6 Notebook            | [dbf4a1d57c](https://linux-hardware.org/?probe=dbf4a1d57c) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Onda TLC      | ONDA Oliver                 | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | ENVY m6 Notebook            | [f72410be27](https://linux-hardware.org/?probe=f72410be27) | Jun 08, 2023 |
| HP            | Laptop 15-dy2xxx            | [f0e52437a7](https://linux-hardware.org/?probe=f0e52437a7) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [c359b173f6](https://linux-hardware.org/?probe=c359b173f6) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [a0efed7ee2](https://linux-hardware.org/?probe=a0efed7ee2) | Jun 04, 2023 |
| Acer          | Nitro AN515-42              | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | Laptop 15s-fq1xxx           | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| Dell          | Latitude 7370               | [4c3bfe7a9d](https://linux-hardware.org/?probe=4c3bfe7a9d) | May 26, 2023 |
| Dell          | Latitude 7280               | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell          | Latitude 7280               | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| ASUSTek       | X551MA                      | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASUSTek       | X551MA                      | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| HP            | ProBook 4540s               | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| HP            | EliteBook 8760w             | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| Lenovo        | ThinkPad E14 20RA0059VA     | [72280fb1c5](https://linux-hardware.org/?probe=72280fb1c5) | May 14, 2023 |
| Dell          | Latitude 7370               | [78654593c7](https://linux-hardware.org/?probe=78654593c7) | May 10, 2023 |
| Acer          | Extensa 215-54              | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Acer          | Extensa 215-54              | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| Dell          | Latitude 7370               | [4ea44288b5](https://linux-hardware.org/?probe=4ea44288b5) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| Dell          | Precision 7720              | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| HP            | Notebook                    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| ASUSTek       | K42Jc                       | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| MSI           | GF63 Thin 11UC              | [e9c446ce66](https://linux-hardware.org/?probe=e9c446ce66) | May 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [f3b5a181df](https://linux-hardware.org/?probe=f3b5a181df) | May 02, 2023 |
| Dell          | Inspiron N5110              | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Dell          | XPS 13 9350                 | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Acer          | Nitro AN515-57              | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| HP            | ProBook 4540s               | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Dell          | Inspiron 14 5410            | [89017780fa](https://linux-hardware.org/?probe=89017780fa) | Apr 25, 2023 |
| HP            | ProBook 4540s               | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Gigabyte      | AORUS 15P KD                | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [04c16989b3](https://linux-hardware.org/?probe=04c16989b3) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [b307524661](https://linux-hardware.org/?probe=b307524661) | Apr 06, 2023 |
| Acer          | Extensa 215-54              | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| Google        | Lillipup                    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 23253Z5       | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| Dell          | Inspiron 3421               | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| Google        | Robo360                     | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |
| Apple         | MacBookPro9,2               | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| Apple         | MacBookAir7,2               | [91e33f05ed](https://linux-hardware.org/?probe=91e33f05ed) | Jan 24, 2023 |
| MSI           | Katana GF66 12UC            | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Lenovo        | ThinkPad E590 20NB0003AD    | [fe3de007e1](https://linux-hardware.org/?probe=fe3de007e1) | Jan 16, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Dell          | Latitude E6520              | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Acer          | Aspire A315-58              | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| HUAWEI        | BOD-WXX9                    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Dell          | G3 3500                     | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Dell          | Latitude 3350               | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Acer          | Aspire ES1-111M             | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Dell          | Latitude E5500              | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| Clevo         | W25xHPx                     | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| HP            | Presario CQ58               | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410            | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| Dell          | Latitude E6400              | [1de889aa64](https://linux-hardware.org/?probe=1de889aa64) | Sep 05, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| Acer          | Predator PT516-51s          | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Acer          | Aspire A517-52              | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| HP            | 250 G2                      | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| HP            | Laptop 15-dy2xxx            | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| Unknown       | Unknown                     | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| HP            | Pavilion dv6                | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| HP            | ProBook 440 G5              | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Dell          | Latitude E6410              | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | GE62 6QE                    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| Lenovo        | V330-15IKB 81AX             | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| MSI           | Modern 15 A5M               | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ASUSTek       | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Toshiba       | Satellite L775D             | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | X75VC                       | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| Dell          | Latitude XT2                | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Jumper        | EZbook                      | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Samsung       | 550P5C/550P7C               | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Toshiba       | Satellite C75D-B            | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Dell          | Inspiron N5110              | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Dell          | Latitude 7480               | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| HP            | EliteBook 8470p             | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo        | IdeaPad Y580                | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Toshiba       | Satellite L655              | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| HP            | EliteBook 840 G3            | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| HP            | Pavilion dv6700             | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| HP            | Pavilion dv7                | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ASUSTek       | G74Sx                       | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| Dell          | Latitude E7440              | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| MSI           | GE73 Raider RGB 8RE         | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Apple         | MacBookPro11,1              | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| HP            | HDX PREMIUM SERIES          | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| Acer          | Aspire E1-571G              | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Dell          | Inspiron 5420               | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| HP            | ENVY 15                     | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Dell          | Latitude 7390               | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| Acer          | Aspire 5250                 | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | X540YA                      | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| Toshiba       | Satellite L750              | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Alienware     | 17 R4                       | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Dell          | Latitude 3400               | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Dell          | G7 7790                     | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Google        | Celes                       | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| Dell          | Inspiron MM061              | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| ASUSTek       | N56VZ                       | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| ASUSTek       | X442URR                     | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | Latitude E6420              | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| Dell          | Latitude E6420              | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Dell          | XPS 12-9Q33                 | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| Acer          | Aspire 5250                 | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | Inspiron 5721               | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| HP            | Laptop 17-by0xxx            | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Notebook      | W510TU                      | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| HUAWEI        | WRT-WX9                     | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| Apple         | MacBookAir7,2               | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Parrot/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Parrot 5.3   | 82        | 16.57%  |
| Parrot 5.0   | 82        | 16.57%  |
| Parrot 4.11  | 70        | 14.14%  |
| Parrot 5.1   | 52        | 10.51%  |
| Parrot 4.10  | 45        | 9.09%   |
| Parrot 6.0   | 39        | 7.88%   |
| Parrot 6.2   | 32        | 6.46%   |
| Parrot 5.2   | 26        | 5.25%   |
| Parrot 6.1   | 22        | 4.44%   |
| Parrot 4.8   | 15        | 3.03%   |
| Parrot 4.9   | 14        | 2.83%   |
| Parrot 4.7   | 10        | 2.02%   |
| Parrot 4.6   | 2         | 0.4%    |
| Parrot 4.5   | 1         | 0.2%    |
| Parrot 4.4   | 1         | 0.2%    |
| Parrot 4.2.2 | 1         | 0.2%    |
| Parrot 3.10  | 1         | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 467       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 6.1.0-1parrot1-amd64      | 82        | 16.4%   |
| 6.5.0-13parrot1-amd64     | 51        | 10.2%   |
| 5.14.0-9parrot1-amd64     | 37        | 7.4%    |
| 5.16.0-12parrot1-amd64    | 35        | 7%      |
| 6.0.0-12parrot1-amd64     | 33        | 6.6%    |
| 5.18.0-14parrot1-amd64    | 28        | 5.6%    |
| 5.7.0-2parrot2-amd64      | 26        | 5.2%    |
| 5.10.0-6parrot1-amd64     | 26        | 5.2%    |
| 6.0.0-2parrot1-amd64      | 22        | 4.4%    |
| 6.10.11-amd64             | 18        | 3.6%    |
| 6.9.7-amd64               | 15        | 3%      |
| 5.18.0-1parrot1-amd64     | 14        | 2.8%    |
| 5.10.0-8parrot1-amd64     | 14        | 2.8%    |
| 5.5.0-1parrot1-amd64      | 13        | 2.6%    |
| 5.4.0-4parrot1-amd64      | 11        | 2.2%    |
| 5.6.0-2parrot1-amd64      | 9         | 1.8%    |
| 5.14.0-2parrot1-amd64     | 9         | 1.8%    |
| 5.9.0-2parrot1-amd64      | 7         | 1.4%    |
| 6.5.0-3parrot1-amd64      | 5         | 1%      |
| 5.15.0-15parrot1-amd64    | 5         | 1%      |
| 5.8.0-2parrot1-amd64      | 3         | 0.6%    |
| 5.4.0-2parrot1-amd64      | 3         | 0.6%    |
| 5.2.0-2parrot1-amd64      | 3         | 0.6%    |
| 5.10.0-5parrot1-amd64     | 3         | 0.6%    |
| 5.10.0-3parrot1-amd64     | 3         | 0.6%    |
| 4.19.0-parrot4-28t-amd64  | 3         | 0.6%    |
| 5.8.0-1parrot1-amd64      | 2         | 0.4%    |
| 5.4.0-3parrot1-amd64      | 2         | 0.4%    |
| 4.18.0-parrot10-amd64     | 2         | 0.4%    |
| 6.11.5+bpo-amd64          | 1         | 0.2%    |
| 6.1.27chrultrabook-fixups | 1         | 0.2%    |
| 6.1.0-0.deb11.5-amd64     | 1         | 0.2%    |
| 5.7.0-rc6-galliumos       | 1         | 0.2%    |
| 5.4.0-2parrot1-686-pae    | 1         | 0.2%    |
| 5.4.0-1parrot1-amd64      | 1         | 0.2%    |
| 5.3.0-3parrot3-amd64      | 1         | 0.2%    |
| 5.3.0-3parrot3-686-pae    | 1         | 0.2%    |
| 5.3.0-1parrot1-amd64      | 1         | 0.2%    |
| 5.15.0-5parrot1-amd64     | 1         | 0.2%    |
| 5.10.0-kali6-amd64        | 1         | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 83        | 16.7%   |
| 6.5.0   | 55        | 11.07%  |
| 6.0.0   | 55        | 11.07%  |
| 5.10.0  | 48        | 9.66%   |
| 5.14.0  | 45        | 9.05%   |
| 5.18.0  | 41        | 8.25%   |
| 5.16.0  | 35        | 7.04%   |
| 5.7.0   | 27        | 5.43%   |
| 6.10.11 | 18        | 3.62%   |
| 5.4.0   | 18        | 3.62%   |
| 6.9.7   | 15        | 3.02%   |
| 5.5.0   | 13        | 2.62%   |
| 5.6.0   | 9         | 1.81%   |
| 5.9.0   | 7         | 1.41%   |
| 5.15.0  | 6         | 1.21%   |
| 5.8.0   | 5         | 1.01%   |
| 4.19.0  | 4         | 0.8%    |
| 5.3.0   | 3         | 0.6%    |
| 5.2.0   | 3         | 0.6%    |
| 4.18.0  | 2         | 0.4%    |
| 6.11.5  | 1         | 0.2%    |
| 6.1.27  | 1         | 0.2%    |
| 5.1.0   | 1         | 0.2%    |
| 4.14.0  | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 84        | 16.9%   |
| 6.5     | 55        | 11.07%  |
| 6.0     | 55        | 11.07%  |
| 5.10    | 48        | 9.66%   |
| 5.14    | 45        | 9.05%   |
| 5.18    | 41        | 8.25%   |
| 5.16    | 35        | 7.04%   |
| 5.7     | 27        | 5.43%   |
| 6.10    | 18        | 3.62%   |
| 5.4     | 18        | 3.62%   |
| 6.9     | 15        | 3.02%   |
| 5.5     | 13        | 2.62%   |
| 5.6     | 9         | 1.81%   |
| 5.9     | 7         | 1.41%   |
| 5.15    | 6         | 1.21%   |
| 5.8     | 5         | 1.01%   |
| 4.19    | 4         | 0.8%    |
| 5.3     | 3         | 0.6%    |
| 5.2     | 3         | 0.6%    |
| 4.18    | 2         | 0.4%    |
| 6.11    | 1         | 0.2%    |
| 5.1     | 1         | 0.2%    |
| 4.14    | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 466       | 99.79%  |
| i686   | 1         | 0.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 359       | 75.58%  |
| KDE5          | 71        | 14.95%  |
| Unknown       | 18        | 3.79%   |
| KDE           | 13        | 2.74%   |
| XFCE          | 8         | 1.68%   |
| X-Cinnamon    | 3         | 0.63%   |
| LXDE          | 1         | 0.21%   |
| GNOME Classic | 1         | 0.21%   |
| GNOME         | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 457       | 97.86%  |
| Wayland | 7         | 1.5%    |
| Tty     | 2         | 0.43%   |
| Unknown | 1         | 0.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 265       | 55.67%  |
| Unknown | 143       | 30.04%  |
| TDM     | 50        | 10.5%   |
| SDDM    | 13        | 2.73%   |
| GDM     | 5         | 1.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 260       | 55.44%  |
| en_GB   | 34        | 7.25%   |
| fr_FR   | 22        | 4.69%   |
| Unknown | 14        | 2.99%   |
| ru_RU   | 12        | 2.56%   |
| de_DE   | 12        | 2.56%   |
| it_IT   | 11        | 2.35%   |
| es_ES   | 11        | 2.35%   |
| en_IN   | 11        | 2.35%   |
| pt_BR   | 10        | 2.13%   |
| pl_PL   | 9         | 1.92%   |
| es_MX   | 8         | 1.71%   |
| en_AU   | 8         | 1.71%   |
| en_CA   | 6         | 1.28%   |
| cs_CZ   | 4         | 0.85%   |
| tr_TR   | 3         | 0.64%   |
| es_CO   | 3         | 0.64%   |
| es_AR   | 3         | 0.64%   |
| ja_JP   | 2         | 0.43%   |
| es_PE   | 2         | 0.43%   |
| en_NG   | 2         | 0.43%   |
| en_IE   | 2         | 0.43%   |
| sk_SK   | 1         | 0.21%   |
| pt_PT   | 1         | 0.21%   |
| nl_NL   | 1         | 0.21%   |
| nl_BE   | 1         | 0.21%   |
| nb_NO   | 1         | 0.21%   |
| lt_LT   | 1         | 0.21%   |
| id_ID   | 1         | 0.21%   |
| fr_CH   | 1         | 0.21%   |
| fr_CA   | 1         | 0.21%   |
| fi_FI   | 1         | 0.21%   |
| es_CL   | 1         | 0.21%   |
| en_ZW   | 1         | 0.21%   |
| en_ZM   | 1         | 0.21%   |
| en_ZA   | 1         | 0.21%   |
| en_NZ   | 1         | 0.21%   |
| en_DK   | 1         | 0.21%   |
| de_CH   | 1         | 0.21%   |
| C       | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 249       | 52.53%  |
| EFI  | 225       | 47.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 362       | 76.69%  |
| Ext4    | 54        | 11.44%  |
| Tmpfs   | 21        | 4.45%   |
| Overlay | 18        | 3.81%   |
| Xfs     | 10        | 2.12%   |
| Unknown | 7         | 1.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 239       | 50.32%  |
| Unknown | 158       | 33.26%  |
| MBR     | 78        | 16.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 412       | 87.47%  |
| Yes       | 59        | 12.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 313       | 66.45%  |
| Yes       | 158       | 33.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 106       | 22.7%   |
| Hewlett-Packard       | 91        | 19.49%  |
| Dell                  | 65        | 13.92%  |
| ASUSTek Computer      | 50        | 10.71%  |
| Acer                  | 37        | 7.92%   |
| MSI                   | 23        | 4.93%   |
| Apple                 | 16        | 3.43%   |
| Toshiba               | 12        | 2.57%   |
| Samsung Electronics   | 8         | 1.71%   |
| HUAWEI                | 6         | 1.28%   |
| Google                | 5         | 1.07%   |
| Alienware             | 4         | 0.86%   |
| Unknown               | 4         | 0.86%   |
| Sony                  | 3         | 0.64%   |
| Razer                 | 3         | 0.64%   |
| Panasonic             | 3         | 0.64%   |
| Fujitsu               | 3         | 0.64%   |
| Quanta                | 2         | 0.43%   |
| Notebook              | 2         | 0.43%   |
| Gateway               | 2         | 0.43%   |
| Wortmann AG           | 1         | 0.21%   |
| Toxic                 | 1         | 0.21%   |
| Timi                  | 1         | 0.21%   |
| System76              | 1         | 0.21%   |
| Standard              | 1         | 0.21%   |
| Positivo Bahia - VAIO | 1         | 0.21%   |
| Positivo              | 1         | 0.21%   |
| Onda TLC              | 1         | 0.21%   |
| Metabox               | 1         | 0.21%   |
| Jumper                | 1         | 0.21%   |
| Irbis                 | 1         | 0.21%   |
| Intel Client Systems  | 1         | 0.21%   |
| HONOR                 | 1         | 0.21%   |
| GPU Company           | 1         | 0.21%   |
| Gigabyte Technology   | 1         | 0.21%   |
| eMachines             | 1         | 0.21%   |
| Eluktronics           | 1         | 0.21%   |
| Digma                 | 1         | 0.21%   |
| Clevo                 | 1         | 0.21%   |
| Chuwi                 | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 6         | 1.28%   |
| HP Laptop 15-dy2xxx                     | 5         | 1.07%   |
| HP Notebook                             | 4         | 0.86%   |
| MSI Modern 15 A5M                       | 3         | 0.64%   |
| Lenovo IdeaPad 3 15IIL05 81WE           | 3         | 0.64%   |
| HP Pavilion 15                          | 3         | 0.64%   |
| HP EliteBook 8470p                      | 3         | 0.64%   |
| HP 250 G7 Notebook PC                   | 3         | 0.64%   |
| Dell Latitude E6420                     | 3         | 0.64%   |
| Dell Inspiron MM061                     | 3         | 0.64%   |
| Apple MacBookAir7,2                     | 3         | 0.64%   |
| Toshiba Satellite L775D                 | 2         | 0.43%   |
| Quanta TW9/SW9                          | 2         | 0.43%   |
| MSI Katana GF66 12UC                    | 2         | 0.43%   |
| MSI Katana GF66 11UE                    | 2         | 0.43%   |
| Lenovo ThinkPad E15 Gen 3 20YG0041MX    | 2         | 0.43%   |
| Lenovo Legion Pro 5 16IRX8 82WK         | 2         | 0.43%   |
| Lenovo E41-25 81FS                      | 2         | 0.43%   |
| HUAWEI HVY-WXX9                         | 2         | 0.43%   |
| HP ProBook 650 G1                       | 2         | 0.43%   |
| HP Pavilion g6                          | 2         | 0.43%   |
| HP Pavilion dv6                         | 2         | 0.43%   |
| HP Pavilion dv4                         | 2         | 0.43%   |
| HP Laptop 17-cn0xxx                     | 2         | 0.43%   |
| HP EliteBook Folio 9480m                | 2         | 0.43%   |
| HP EliteBook 830 G6                     | 2         | 0.43%   |
| Dell XPS 13 9350                        | 2         | 0.43%   |
| Dell Latitude E7440                     | 2         | 0.43%   |
| Dell Latitude E6410                     | 2         | 0.43%   |
| Dell Latitude 7280                      | 2         | 0.43%   |
| Dell Inspiron N5110                     | 2         | 0.43%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA | 2         | 0.43%   |
| ASUS ROG Strix G513QR_G513QR            | 2         | 0.43%   |
| ASUS Q524UQ                             | 2         | 0.43%   |
| Apple MacBookPro9,2                     | 2         | 0.43%   |
| Apple MacBookPro8,1                     | 2         | 0.43%   |
| Apple MacBookPro11,1                    | 2         | 0.43%   |
| Acer Nitro AN515-57                     | 2         | 0.43%   |
| Acer Nitro AN515-54                     | 2         | 0.43%   |
| Acer Extensa 215-54                     | 2         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 58        | 12.42%  |
| Dell Latitude      | 28        | 6%      |
| Lenovo IdeaPad     | 26        | 5.57%   |
| Dell Inspiron      | 20        | 4.28%   |
| HP Pavilion        | 19        | 4.07%   |
| HP Laptop          | 19        | 4.07%   |
| HP EliteBook       | 18        | 3.85%   |
| Acer Aspire        | 18        | 3.85%   |
| HP ProBook         | 11        | 2.36%   |
| Toshiba Satellite  | 10        | 2.14%   |
| ASUS VivoBook      | 10        | 2.14%   |
| ASUS ASUS          | 8         | 1.71%   |
| Acer Nitro         | 8         | 1.71%   |
| MSI Katana         | 7         | 1.5%    |
| Dell XPS           | 7         | 1.5%    |
| Lenovo Legion      | 6         | 1.28%   |
| ASUS ROG           | 6         | 1.28%   |
| Unknown            | 6         | 1.28%   |
| HP ZBook           | 4         | 0.86%   |
| HP Victus          | 4         | 0.86%   |
| HP Notebook        | 4         | 0.86%   |
| HP 250             | 4         | 0.86%   |
| Dell Precision     | 4         | 0.86%   |
| ASUS Zenbook       | 4         | 0.86%   |
| Razer Blade        | 3         | 0.64%   |
| MSI Modern         | 3         | 0.64%   |
| Fujitsu LIFEBOOK   | 3         | 0.64%   |
| Dell Vostro        | 3         | 0.64%   |
| Apple MacBookPro11 | 3         | 0.64%   |
| Apple MacBookAir7  | 3         | 0.64%   |
| Acer Swift         | 3         | 0.64%   |
| Acer Predator      | 3         | 0.64%   |
| Acer Extensa       | 3         | 0.64%   |
| Quanta TW9         | 2         | 0.43%   |
| MSI Prestige       | 2         | 0.43%   |
| MSI GT60           | 2         | 0.43%   |
| Lenovo E41-25      | 2         | 0.43%   |
| HUAWEI HVY-WXX9    | 2         | 0.43%   |
| HP ENVY            | 2         | 0.43%   |
| ASUS TUF           | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 56        | 11.99%  |
| 2019 | 54        | 11.56%  |
| 2020 | 43        | 9.21%   |
| 2011 | 40        | 8.57%   |
| 2022 | 35        | 7.49%   |
| 2018 | 32        | 6.85%   |
| 2012 | 32        | 6.85%   |
| 2017 | 28        | 6%      |
| 2016 | 27        | 5.78%   |
| 2013 | 26        | 5.57%   |
| 2014 | 22        | 4.71%   |
| 2023 | 16        | 3.43%   |
| 2015 | 16        | 3.43%   |
| 2008 | 12        | 2.57%   |
| 2010 | 11        | 2.36%   |
| 2007 | 6         | 1.28%   |
| 2009 | 4         | 0.86%   |
| 2006 | 4         | 0.86%   |
| 2024 | 3         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 467       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 467       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 462       | 98.93%  |
| Yes  | 5         | 1.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 135       | 28.72%  |
| 16.01-24.0  | 99        | 21.06%  |
| 8.01-16.0   | 98        | 20.85%  |
| 3.01-4.0    | 72        | 15.32%  |
| 32.01-64.0  | 38        | 8.09%   |
| 1.01-2.0    | 9         | 1.91%   |
| 24.01-32.0  | 8         | 1.7%    |
| 64.01-256.0 | 8         | 1.7%    |
| 2.01-3.0    | 3         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 162       | 32.53%  |
| 1.01-2.0   | 159       | 31.93%  |
| 4.01-8.0   | 76        | 15.26%  |
| 3.01-4.0   | 73        | 14.66%  |
| 0.51-1.0   | 16        | 3.21%   |
| 8.01-16.0  | 10        | 2.01%   |
| 16.01-24.0 | 1         | 0.2%    |
| 0.01-0.5   | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 341       | 71.94%  |
| 2      | 119       | 25.11%  |
| 3      | 11        | 2.32%   |
| 0      | 3         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 347       | 74.15%  |
| Yes       | 121       | 25.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 371       | 79.1%   |
| No        | 98        | 20.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 459       | 98.29%  |
| No        | 8         | 1.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 387       | 81.99%  |
| No        | 85        | 18.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 141       | 29.94%  |
| Germany      | 24        | 5.1%    |
| France       | 22        | 4.67%   |
| UK           | 18        | 3.82%   |
| Italy        | 16        | 3.4%    |
| Russia       | 15        | 3.18%   |
| Netherlands  | 15        | 3.18%   |
| Spain        | 14        | 2.97%   |
| India        | 14        | 2.97%   |
| Brazil       | 13        | 2.76%   |
| Canada       | 11        | 2.34%   |
| Mexico       | 10        | 2.12%   |
| Kenya        | 9         | 1.91%   |
| Australia    | 8         | 1.7%    |
| Sweden       | 7         | 1.49%   |
| Poland       | 6         | 1.27%   |
| Indonesia    | 6         | 1.27%   |
| Czechia      | 6         | 1.27%   |
| Egypt        | 5         | 1.06%   |
| Turkey       | 4         | 0.85%   |
| Switzerland  | 4         | 0.85%   |
| Portugal     | 4         | 0.85%   |
| Peru         | 4         | 0.85%   |
| Finland      | 4         | 0.85%   |
| Denmark      | 4         | 0.85%   |
| Argentina    | 4         | 0.85%   |
| UAE          | 3         | 0.64%   |
| South Africa | 3         | 0.64%   |
| Nepal        | 3         | 0.64%   |
| Namibia      | 3         | 0.64%   |
| Iraq         | 3         | 0.64%   |
| Colombia     | 3         | 0.64%   |
| Bangladesh   | 3         | 0.64%   |
| Algeria      | 3         | 0.64%   |
| Slovakia     | 2         | 0.42%   |
| Saudi Arabia | 2         | 0.42%   |
| Puerto Rico  | 2         | 0.42%   |
| Pakistan     | 2         | 0.42%   |
| Norway       | 2         | 0.42%   |
| Nigeria      | 2         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Nairobi           | 8         | 1.61%   |
| Amsterdam         | 8         | 1.61%   |
| Seattle           | 6         | 1.21%   |
| Rome              | 6         | 1.21%   |
| Moscow            | 6         | 1.21%   |
| Houston           | 6         | 1.21%   |
| Los Angeles       | 5         | 1.01%   |
| Dallas            | 5         | 1.01%   |
| San Antonio       | 4         | 0.8%    |
| Saint Paul        | 4         | 0.8%    |
| Prague            | 4         | 0.8%    |
| Paris             | 4         | 0.8%    |
| New York          | 4         | 0.8%    |
| Melbourne         | 4         | 0.8%    |
| London            | 4         | 0.8%    |
| Dublin            | 4         | 0.8%    |
| Toronto           | 3         | 0.6%    |
| Sydney            | 3         | 0.6%    |
| Stockholm         | 3         | 0.6%    |
| San Jose          | 3         | 0.6%    |
| Minneapolis       | 3         | 0.6%    |
| Lyon              | 3         | 0.6%    |
| Lima              | 3         | 0.6%    |
| Helsinki          | 3         | 0.6%    |
| Frankfurt am Main | 3         | 0.6%    |
| Dhaka             | 3         | 0.6%    |
| Chicago           | 3         | 0.6%    |
| Cairo             | 3         | 0.6%    |
| Berlin            | 3         | 0.6%    |
| Barcelona         | 3         | 0.6%    |
| Alexandria        | 3         | 0.6%    |
| Zurich            | 2         | 0.4%    |
| Windhoek          | 2         | 0.4%    |
| Warsaw            | 2         | 0.4%    |
| Visalia           | 2         | 0.4%    |
| Ulan Bator        | 2         | 0.4%    |
| St Petersburg     | 2         | 0.4%    |
| San Juan          | 2         | 0.4%    |
| Ruskin            | 2         | 0.4%    |
| Rho               | 2         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 99        | 127    | 17.04%  |
| WDC                         | 66        | 79     | 11.36%  |
| Toshiba                     | 58        | 66     | 9.98%   |
| Unknown                     | 40        | 43     | 6.88%   |
| Seagate                     | 36        | 37     | 6.2%    |
| Kingston                    | 33        | 33     | 5.68%   |
| SanDisk                     | 31        | 37     | 5.34%   |
| SK hynix                    | 27        | 32     | 4.65%   |
| Micron Technology           | 22        | 22     | 3.79%   |
| Crucial                     | 18        | 24     | 3.1%    |
| Hitachi                     | 16        | 18     | 2.75%   |
| HGST                        | 14        | 17     | 2.41%   |
| Intel                       | 13        | 20     | 2.24%   |
| A-DATA Technology           | 11        | 11     | 1.89%   |
| KIOXIA                      | 9         | 10     | 1.55%   |
| Apple                       | 9         | 9      | 1.55%   |
| China                       | 8         | 8      | 1.38%   |
| Team                        | 5         | 6      | 0.86%   |
| LITEON                      | 4         | 4      | 0.69%   |
| YMTC                        | 3         | 3      | 0.52%   |
| PNY                         | 3         | 3      | 0.52%   |
| KingFast                    | 3         | 4      | 0.52%   |
| Unknown                     | 3         | 3      | 0.52%   |
| Silicon Motion              | 2         | 2      | 0.34%   |
| Phison                      | 2         | 2      | 0.34%   |
| Netac                       | 2         | 2      | 0.34%   |
| Lexar                       | 2         | 2      | 0.34%   |
| Kingston Technology Company | 2         | 3      | 0.34%   |
| HUAWEI                      | 2         | 2      | 0.34%   |
| Corsair                     | 2         | 3      | 0.34%   |
| BR                          | 2         | 2      | 0.34%   |
| Zheino                      | 1         | 1      | 0.17%   |
| Wdxsky                      | 1         | 1      | 0.17%   |
| W800SH                      | 1         | 1      | 0.17%   |
| Unknown (583)               | 1         | 1      | 0.17%   |
| Union Memory                | 1         | 1      | 0.17%   |
| TSA 256G                    | 1         | 1      | 0.17%   |
| Transcend                   | 1         | 1      | 0.17%   |
| TO Exter                    | 1         | 1      | 0.17%   |
| Teclast                     | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                              | 12        | 1.96%   |
| Toshiba MQ01ABF050 500GB                            | 8         | 1.31%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 1.14%   |
| Samsung SSD 860 EVO 500GB                           | 6         | 0.98%   |
| Unknown MMC Card  64GB                              | 5         | 0.82%   |
| Unknown MMC Card  32GB                              | 5         | 0.82%   |
| Toshiba MQ01ABD075 752GB                            | 5         | 0.82%   |
| SanDisk NVMe SSD Drive 1TB                          | 5         | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 5         | 0.82%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 0.82%   |
| Kingston NVMe SSD Drive 512GB                       | 5         | 0.82%   |
| Unknown SD/MMC/MS PRO 128GB                         | 4         | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 0.65%   |
| SanDisk NVMe SSD Drive 256GB                        | 4         | 0.65%   |
| Kingston OM8PCP3512F-AB 512GB                       | 4         | 0.65%   |
| Intel SSDPEKNU512GZ 512GB                           | 4         | 0.65%   |
| HGST HTS721010A9E630 1TB                            | 4         | 0.65%   |
| HGST HTS541010A9E680 1TB                            | 4         | 0.65%   |
| Crucial CT500MX500SSD1 500GB                        | 4         | 0.65%   |
| WDC WD10SPZX-75Z10T2 1TB                            | 3         | 0.49%   |
| Toshiba KXG6AZNV256G 256GB                          | 3         | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 0.49%   |
| Seagate ST320LT007-9ZV142 320GB                     | 3         | 0.49%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 3         | 0.49%   |
| SanDisk SSD PLUS 1000GB                             | 3         | 0.49%   |
| Samsung SSD 980 PRO 1TB                             | 3         | 0.49%   |
| Samsung SSD 980 1TB                                 | 3         | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.49%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.49%   |
| Samsung MZVL21T0HCLR-00B00 1TB                      | 3         | 0.49%   |
| Micron 2400_MTFDKBA512QFM 512GB                     | 3         | 0.49%   |
| KIOXIA KBG40ZNV256G 256GB                           | 3         | 0.49%   |
| Apple SSD SM0128G 121GB                             | 3         | 0.49%   |
| Unknown                                             | 3         | 0.49%   |
| YMTC PC005 256GB                                    | 2         | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.33%   |
| WDC WDS480G2G0C-00AJM0 480GB                        | 2         | 0.33%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 2         | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.33%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 43        | 49     | 27.04%  |
| WDC                 | 39        | 45     | 24.53%  |
| Seagate             | 34        | 35     | 21.38%  |
| Hitachi             | 16        | 18     | 10.06%  |
| HGST                | 14        | 17     | 8.81%   |
| Samsung Electronics | 5         | 5      | 3.14%   |
| Unknown             | 4         | 5      | 2.52%   |
| TO Exter            | 1         | 1      | 0.63%   |
| Fujitsu             | 1         | 1      | 0.63%   |
| ASMT                | 1         | 1      | 0.63%   |
| ASMedia             | 1         | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 37     | 16.46%  |
| SanDisk             | 15        | 17     | 9.15%   |
| Kingston            | 15        | 15     | 9.15%   |
| Crucial             | 14        | 19     | 8.54%   |
| WDC                 | 13        | 15     | 7.93%   |
| China               | 8         | 8      | 4.88%   |
| Apple               | 8         | 8      | 4.88%   |
| Toshiba             | 5         | 6      | 3.05%   |
| SK hynix            | 4         | 4      | 2.44%   |
| Micron Technology   | 4         | 4      | 2.44%   |
| LITEON              | 4         | 4      | 2.44%   |
| Team                | 3         | 4      | 1.83%   |
| PNY                 | 3         | 3      | 1.83%   |
| KingFast            | 3         | 3      | 1.83%   |
| A-DATA Technology   | 3         | 3      | 1.83%   |
| Seagate             | 2         | 2      | 1.22%   |
| Intel               | 2         | 2      | 1.22%   |
| BR                  | 2         | 2      | 1.22%   |
| Unknown             | 2         | 2      | 1.22%   |
| Zheino              | 1         | 1      | 0.61%   |
| Wdxsky              | 1         | 1      | 0.61%   |
| W800SH              | 1         | 1      | 0.61%   |
| Unknown             | 1         | 1      | 0.61%   |
| TSA 256G            | 1         | 1      | 0.61%   |
| Transcend           | 1         | 1      | 0.61%   |
| Teclast             | 1         | 1      | 0.61%   |
| SCY                 | 1         | 1      | 0.61%   |
| S3+                 | 1         | 1      | 0.61%   |
| RZX                 | 1         | 1      | 0.61%   |
| Rogueware           | 1         | 1      | 0.61%   |
| Patriot             | 1         | 1      | 0.61%   |
| Netac               | 1         | 1      | 0.61%   |
| LITEONIT            | 1         | 1      | 0.61%   |
| Lexar               | 1         | 1      | 0.61%   |
| KingSpec            | 1         | 2      | 0.61%   |
| Kingmax             | 1         | 1      | 0.61%   |
| Intenso             | 1         | 2      | 0.61%   |
| HS-SSD-C100         | 1         | 1      | 0.61%   |
| Hewlett-Packard     | 1         | 1      | 0.61%   |
| GOODRAM             | 1         | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 205       | 263    | 37.21%  |
| HDD     | 155       | 178    | 28.13%  |
| SSD     | 153       | 189    | 27.77%  |
| MMC     | 33        | 37     | 5.99%   |
| Unknown | 5         | 5      | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 276       | 349    | 51.4%   |
| NVMe | 205       | 262    | 38.18%  |
| MMC  | 33        | 37     | 6.15%   |
| SAS  | 23        | 24     | 4.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 195       | 241    | 64.36%  |
| 0.51-1.0   | 97        | 114    | 32.01%  |
| 1.01-2.0   | 10        | 11     | 3.3%    |
| 3.01-4.0   | 1         | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 122       | 25.58%  |
| 101-250        | 98        | 20.55%  |
| 501-1000       | 92        | 19.29%  |
| Unknown        | 48        | 10.06%  |
| 1001-2000      | 44        | 9.22%   |
| 51-100         | 28        | 5.87%   |
| 21-50          | 17        | 3.56%   |
| 1-20           | 14        | 2.94%   |
| More than 3000 | 10        | 2.1%    |
| 2001-3000      | 4         | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 153       | 31.35%  |
| 51-100         | 100       | 20.49%  |
| 1-20           | 69        | 14.14%  |
| 101-250        | 61        | 12.5%   |
| Unknown        | 48        | 9.84%   |
| 251-500        | 38        | 7.79%   |
| 501-1000       | 11        | 2.25%   |
| 1001-2000      | 4         | 0.82%   |
| 0              | 2         | 0.41%   |
| More than 3000 | 1         | 0.2%    |
| 2001-3000      | 1         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 4.55%   |
| Samsung Electronics HM500JI 500GB                   | 2         | 2      | 4.55%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 2         | 2      | 4.55%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 2.27%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 2.27%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 2.27%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.27%   |
| Toshiba MK6475GSX 640GB                             | 1         | 1      | 2.27%   |
| Toshiba MK5059GSXP 500GB                            | 1         | 1      | 2.27%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 2.27%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 1      | 2.27%   |
| SK hynix PC711 HFS256GDE9X073N 256GB                | 1         | 1      | 2.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.27%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 2.27%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 2.27%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.27%   |
| SanDisk SSD U110 16GB                               | 1         | 1      | 2.27%   |
| SanDisk SSD U100 24GB                               | 1         | 1      | 2.27%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                 | 1         | 1      | 2.27%   |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 1         | 1      | 2.27%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 2.27%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.27%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.27%   |
| Kingston SUV400S37480G 480GB SSD                    | 1         | 1      | 2.27%   |
| Intel HBRPEKNX0202AHO 32GB                          | 1         | 1      | 2.27%   |
| Hitachi HTS725050A9A364 500GB                       | 1         | 1      | 2.27%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 2.27%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2.27%   |
| Hitachi HTS723216L9SA60 160GB                       | 1         | 1      | 2.27%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 2.27%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 2.27%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.27%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.27%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.27%   |
| Hewlett-Packard SSD S700 Pro 1TB                    | 1         | 1      | 2.27%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 2.27%   |
| Crucial CT525MX300SSD1 528GB                        | 1         | 1      | 2.27%   |
| China SSD 120GB                                     | 1         | 1      | 2.27%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 2.27%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 15.91%  |
| Hitachi             | 5         | 5      | 11.36%  |
| Seagate             | 4         | 4      | 9.09%   |
| SanDisk             | 4         | 4      | 9.09%   |
| Samsung Electronics | 4         | 4      | 9.09%   |
| HGST                | 4         | 4      | 9.09%   |
| WDC                 | 3         | 3      | 6.82%   |
| LITEON              | 2         | 2      | 4.55%   |
| A-DATA Technology   | 2         | 2      | 4.55%   |
| SK hynix            | 1         | 1      | 2.27%   |
| Micron Technology   | 1         | 1      | 2.27%   |
| Kingston            | 1         | 1      | 2.27%   |
| Intel               | 1         | 1      | 2.27%   |
| Hewlett-Packard     | 1         | 1      | 2.27%   |
| Fujitsu             | 1         | 1      | 2.27%   |
| Crucial             | 1         | 1      | 2.27%   |
| China               | 1         | 1      | 2.27%   |
| Unknown             | 1         | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 25.93%  |
| Hitachi             | 5         | 5      | 18.52%  |
| Seagate             | 4         | 4      | 14.81%  |
| HGST                | 4         | 4      | 14.81%  |
| WDC                 | 3         | 3      | 11.11%  |
| Samsung Electronics | 3         | 3      | 11.11%  |
| Fujitsu             | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 27     | 61.36%  |
| SSD  | 14        | 14     | 31.82%  |
| NVMe | 3         | 3      | 6.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba MK2565GSXN 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 251       | 317    | 48.93%  |
| Detected | 218       | 310    | 42.5%   |
| Malfunc  | 43        | 44     | 8.38%   |
| Failed   | 1         | 1      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 316       | 54.48%  |
| Samsung Electronics            | 73        | 12.59%  |
| AMD                            | 44        | 7.59%   |
| SanDisk                        | 31        | 5.34%   |
| SK hynix                       | 23        | 3.97%   |
| Kingston Technology Company    | 20        | 3.45%   |
| Micron Technology              | 18        | 3.1%    |
| KIOXIA                         | 10        | 1.72%   |
| Toshiba America Info Systems   | 9         | 1.55%   |
| ADATA Technology               | 8         | 1.38%   |
| Silicon Motion                 | 5         | 0.86%   |
| Phison Electronics             | 4         | 0.69%   |
| Micron/Crucial Technology      | 4         | 0.69%   |
| Yangtze Memory Technologies    | 3         | 0.52%   |
| Nvidia                         | 3         | 0.52%   |
| Solidigm                       | 2         | 0.34%   |
| Realtek Semiconductor          | 2         | 0.34%   |
| Union Memory (Shenzhen)        | 1         | 0.17%   |
| Solid State Storage Technology | 1         | 0.17%   |
| Netac Technology               | 1         | 0.17%   |
| Marvell Technology Group       | 1         | 0.17%   |
| Apple                          | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 45        | 7.17%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 38        | 6.05%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 35        | 5.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 30        | 4.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 29        | 4.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 27        | 4.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 24        | 3.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 16        | 2.55%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 15        | 2.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 15        | 2.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 14        | 2.23%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 13        | 2.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 13        | 2.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 11        | 1.75%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)              | 10        | 1.59%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 8         | 1.27%   |
| Intel Alder Lake-P SATA AHCI Controller                                                | 8         | 1.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 8         | 1.27%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 7         | 1.11%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                          | 7         | 1.11%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 7         | 1.11%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 7         | 1.11%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 7         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 7         | 1.11%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                | 6         | 0.96%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 6         | 0.96%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 6         | 0.96%   |
| Intel Tiger Lake SATA AHCI Controller                                                  | 6         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 6         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 6         | 0.96%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 5         | 0.8%    |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 5         | 0.8%    |
| Intel SSD 670p Series [Keystone Harbor]                                                | 5         | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 5         | 0.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 0.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 4         | 0.64%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                   | 4         | 0.64%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                  | 4         | 0.64%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 4         | 0.64%   |
| Micron 2210 NVMe SSD [Cobain]                                                          | 4         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 286       | 48.56%  |
| NVMe | 204       | 34.63%  |
| RAID | 68        | 11.54%  |
| IDE  | 31        | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 397       | 85.01%  |
| AMD    | 70        | 14.99%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 2.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 2.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 1.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.5%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 7         | 1.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.28%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 1.28%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 6         | 1.28%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 1.07%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 1.07%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.07%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 1.07%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 1.07%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 1.07%   |
| Intel 12th Gen Core i5-12500H                 | 5         | 1.07%   |
| Intel 12th Gen Core i5-1235U                  | 5         | 1.07%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 1.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 1.07%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.86%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.86%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.86%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 0.86%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 0.86%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.86%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.64%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 0.64%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 0.64%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 3         | 0.64%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 123       | 26.34%  |
| Intel Core i7           | 95        | 20.34%  |
| Other                   | 85        | 18.2%   |
| Intel Core i3           | 38        | 8.14%   |
| Intel Celeron           | 24        | 5.14%   |
| AMD Ryzen 7             | 21        | 4.5%    |
| AMD Ryzen 5             | 16        | 3.43%   |
| Intel Core 2 Duo        | 11        | 2.36%   |
| AMD A6                  | 8         | 1.71%   |
| AMD Ryzen 3             | 6         | 1.28%   |
| Intel Pentium           | 4         | 0.86%   |
| Intel Core 2            | 4         | 0.86%   |
| AMD A4                  | 4         | 0.86%   |
| Intel Pentium Silver    | 3         | 0.64%   |
| Intel Core              | 3         | 0.64%   |
| AMD E1                  | 3         | 0.64%   |
| Intel Core i9           | 2         | 0.43%   |
| Intel Atom              | 2         | 0.43%   |
| AMD E                   | 2         | 0.43%   |
| Intel Pentium Dual-Core | 1         | 0.21%   |
| Intel Genuine           | 1         | 0.21%   |
| Intel Core m5           | 1         | 0.21%   |
| Intel Core m3           | 1         | 0.21%   |
| Intel Core 2 Quad       | 1         | 0.21%   |
| Intel Core 2 Extreme    | 1         | 0.21%   |
| AMD Ryzen 9             | 1         | 0.21%   |
| AMD Ryzen 5 PRO         | 1         | 0.21%   |
| AMD FX                  | 1         | 0.21%   |
| AMD E2                  | 1         | 0.21%   |
| AMD C-50                | 1         | 0.21%   |
| AMD Athlon X2           | 1         | 0.21%   |
| AMD Athlon              | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 217       | 46.47%  |
| 4      | 136       | 29.12%  |
| 6      | 42        | 8.99%   |
| 8      | 27        | 5.78%   |
| 10     | 14        | 3%      |
| 14     | 12        | 2.57%   |
| 12     | 12        | 2.57%   |
| 1      | 4         | 0.86%   |
| 16     | 3         | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 467       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 356       | 76.07%  |
| 1      | 111       | 23.72%  |
| 8      | 1         | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 462       | 98.93%  |
| Unknown        | 5         | 1.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 236       | 49.37%  |
| 0x206a7    | 23        | 4.81%   |
| 0x906a3    | 18        | 3.77%   |
| 0x306a9    | 17        | 3.56%   |
| 0x806ec    | 16        | 3.35%   |
| 0x806c1    | 13        | 2.72%   |
| 0x406e3    | 13        | 2.72%   |
| 0xa0652    | 10        | 2.09%   |
| 0x906ea    | 9         | 1.88%   |
| 0x806e9    | 9         | 1.88%   |
| 0x906a4    | 8         | 1.67%   |
| 0x806ea    | 7         | 1.46%   |
| 0x706a8    | 7         | 1.46%   |
| 0x806d1    | 6         | 1.26%   |
| 0x706e5    | 5         | 1.05%   |
| 0x40651    | 5         | 1.05%   |
| 0x08608103 | 5         | 1.05%   |
| 0x08600106 | 5         | 1.05%   |
| 0x6f6      | 4         | 0.84%   |
| 0x306d4    | 4         | 0.84%   |
| 0x306c3    | 4         | 0.84%   |
| 0x1067a    | 4         | 0.84%   |
| 0x0a50000c | 4         | 0.84%   |
| 0x06006705 | 4         | 0.84%   |
| 0x08108109 | 3         | 0.63%   |
| 0x07030105 | 3         | 0.63%   |
| 0x03000027 | 3         | 0.63%   |
| 0xb06a2    | 2         | 0.42%   |
| 0x906e9    | 2         | 0.42%   |
| 0x806eb    | 2         | 0.42%   |
| 0x806c2    | 2         | 0.42%   |
| 0x706a1    | 2         | 0.42%   |
| 0x6fd      | 2         | 0.42%   |
| 0x506c9    | 2         | 0.42%   |
| 0x406c4    | 2         | 0.42%   |
| 0x30678    | 2         | 0.42%   |
| 0x08108102 | 2         | 0.42%   |
| 0xb06f2    | 1         | 0.21%   |
| 0xa0660    | 1         | 0.21%   |
| 0x906ed    | 1         | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 85        | 18.2%   |
| SandyBridge       | 39        | 8.35%   |
| IvyBridge         | 33        | 7.07%   |
| Alderlake Hybrid  | 33        | 7.07%   |
| TigerLake         | 31        | 6.64%   |
| Skylake           | 28        | 6%      |
| Haswell           | 27        | 5.78%   |
| Unknown           | 25        | 5.35%   |
| Broadwell         | 18        | 3.85%   |
| IceLake           | 16        | 3.43%   |
| CometLake         | 16        | 3.43%   |
| Goldmont plus     | 13        | 2.78%   |
| Penryn            | 12        | 2.57%   |
| Zen 3             | 11        | 2.36%   |
| Silvermont        | 11        | 2.36%   |
| Zen+              | 10        | 2.14%   |
| Zen 2             | 10        | 2.14%   |
| Excavator         | 8         | 1.71%   |
| Core              | 8         | 1.71%   |
| Westmere          | 7         | 1.5%    |
| Jaguar            | 4         | 0.86%   |
| Zen               | 3         | 0.64%   |
| Puma              | 3         | 0.64%   |
| Meteorlake Hybrid | 3         | 0.64%   |
| K10 Llano         | 3         | 0.64%   |
| Goldmont          | 3         | 0.64%   |
| Bobcat            | 3         | 0.64%   |
| Piledriver        | 2         | 0.43%   |
| Nehalem           | 1         | 0.21%   |
| K8 & K10 hybrid   | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 378       | 61.17%  |
| Nvidia | 144       | 23.3%   |
| AMD    | 96        | 15.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 35        | 5.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 4.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 24        | 3.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 3.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 3.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 3.19%   |
| Intel UHD Graphics 620                                                                   | 18        | 2.88%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 17        | 2.72%   |
| Intel HD Graphics 5500                                                                   | 15        | 2.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 2.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 2.4%    |
| Intel HD Graphics 620                                                                    | 14        | 2.24%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 11        | 1.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 1.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.6%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 10        | 1.6%    |
| AMD Lucienne                                                                             | 10        | 1.6%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 9         | 1.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 1.44%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 8         | 1.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.12%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 7         | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.12%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.96%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 0.96%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.96%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 6         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.8%    |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.64%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 4         | 0.64%   |
| Intel HD Graphics 630                                                                    | 4         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 239       | 50.85%  |
| Intel + Nvidia | 119       | 25.32%  |
| 1 x AMD        | 61        | 12.98%  |
| Intel + AMD    | 18        | 3.83%   |
| AMD + Nvidia   | 14        | 2.98%   |
| 1 x Nvidia     | 13        | 2.77%   |
| 2 x AMD        | 3         | 0.64%   |
| Other          | 1         | 0.21%   |
| 2 x Nvidia     | 1         | 0.21%   |
| 2 x Intel      | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 418       | 89.32%  |
| Proprietary | 44        | 9.4%    |
| Unknown     | 6         | 1.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 369       | 78.51%  |
| 0.01-0.5   | 24        | 5.11%   |
| 1.01-2.0   | 23        | 4.89%   |
| 3.01-4.0   | 21        | 4.47%   |
| 0.51-1.0   | 18        | 3.83%   |
| 5.01-6.0   | 9         | 1.91%   |
| 7.01-8.0   | 4         | 0.85%   |
| 2.01-3.0   | 2         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 104       | 20.12%  |
| BOE                     | 89        | 17.21%  |
| LG Display              | 79        | 15.28%  |
| Chimei Innolux          | 75        | 14.51%  |
| Samsung Electronics     | 37        | 7.16%   |
| Sharp                   | 18        | 3.48%   |
| Apple                   | 17        | 3.29%   |
| Chi Mei Optoelectronics | 12        | 2.32%   |
| PANDA                   | 10        | 1.93%   |
| Dell                    | 7         | 1.35%   |
| InfoVision              | 6         | 1.16%   |
| Lenovo                  | 5         | 0.97%   |
| Goldstar                | 5         | 0.97%   |
| CSO                     | 5         | 0.97%   |
| Acer                    | 4         | 0.77%   |
| Sony                    | 3         | 0.58%   |
| Sceptre Tech            | 3         | 0.58%   |
| Hewlett-Packard         | 3         | 0.58%   |
| Philips                 | 2         | 0.39%   |
| Eizo                    | 2         | 0.39%   |
| BenQ                    | 2         | 0.39%   |
| Ancor Communications    | 2         | 0.39%   |
| Unknown                 | 2         | 0.39%   |
| ___                     | 1         | 0.19%   |
| Vizio                   | 1         | 0.19%   |
| VIZ                     | 1         | 0.19%   |
| ViewSonic               | 1         | 0.19%   |
| Unknown (AAA)           | 1         | 0.19%   |
| Unknown                 | 1         | 0.19%   |
| TMX                     | 1         | 0.19%   |
| STD                     | 1         | 0.19%   |
| STA                     | 1         | 0.19%   |
| SANYO                   | 1         | 0.19%   |
| Planar                  | 1         | 0.19%   |
| Pixio                   | 1         | 0.19%   |
| Panasonic               | 1         | 0.19%   |
| ONN                     | 1         | 0.19%   |
| Olidata                 | 1         | 0.19%   |
| NEC Computers           | 1         | 0.19%   |
| LG Philips              | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 1.35%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 1.16%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 4         | 0.77%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 0.77%   |
| Sony TV SNYF301 1920x1080                                             | 3         | 0.58%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 3         | 0.58%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.58%   |
| BOE LCD Monitor BOE0897 1366x768 344x194mm 15.5-inch                  | 3         | 0.58%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.58%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 3         | 0.58%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 3         | 0.58%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.39%   |
| LG Display LCD Monitor LGD06E4 1920x1080 344x194mm 15.5-inch          | 2         | 0.39%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 2         | 0.39%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.39%   |
| InfoVision LCD Monitor IVO857D 1920x1080 294x165mm 13.3-inch          | 2         | 0.39%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 0.39%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch       | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 225       | 45.45%  |
| 1366x768 (WXGA)    | 153       | 30.91%  |
| 1600x900 (HD+)     | 23        | 4.65%   |
| 1280x800 (WXGA)    | 16        | 3.23%   |
| 3840x2160 (4K)     | 14        | 2.83%   |
| 1920x1200 (WUXGA)  | 14        | 2.83%   |
| 2560x1440 (QHD)    | 8         | 1.62%   |
| 1440x900 (WXGA+)   | 8         | 1.62%   |
| 2560x1600          | 7         | 1.41%   |
| 2880x1800          | 4         | 0.81%   |
| 1680x1050 (WSXGA+) | 4         | 0.81%   |
| 3840x2400          | 2         | 0.4%    |
| 2560x1080          | 2         | 0.4%    |
| 2160x1440          | 2         | 0.4%    |
| 1920x540           | 2         | 0.4%    |
| 1024x768 (XGA)     | 2         | 0.4%    |
| 3200x1800 (QHD+)   | 1         | 0.2%    |
| 3200x1080          | 1         | 0.2%    |
| 2944x1080          | 1         | 0.2%    |
| 2400x1600          | 1         | 0.2%    |
| 2240x1400          | 1         | 0.2%    |
| 1920x515           | 1         | 0.2%    |
| 1360x768           | 1         | 0.2%    |
| 1280x1024 (SXGA)   | 1         | 0.2%    |
| Unknown            | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 218       | 42.33%  |
| 14      | 78        | 15.15%  |
| 13      | 68        | 13.2%   |
| 17      | 38        | 7.38%   |
| 12      | 18        | 3.5%    |
| 11      | 12        | 2.33%   |
| 27      | 11        | 2.14%   |
| 24      | 10        | 1.94%   |
| 16      | 10        | 1.94%   |
| 31      | 8         | 1.55%   |
| 21      | 7         | 1.36%   |
| Unknown | 6         | 1.17%   |
| 23      | 5         | 0.97%   |
| 72      | 4         | 0.78%   |
| 22      | 3         | 0.58%   |
| 19      | 3         | 0.58%   |
| 84      | 2         | 0.39%   |
| 40      | 2         | 0.39%   |
| 32      | 2         | 0.39%   |
| 26      | 2         | 0.39%   |
| 18      | 2         | 0.39%   |
| 69      | 1         | 0.19%   |
| 54      | 1         | 0.19%   |
| 48      | 1         | 0.19%   |
| 46      | 1         | 0.19%   |
| 34      | 1         | 0.19%   |
| 29      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 339       | 65.95%  |
| 201-300     | 59        | 11.48%  |
| 351-400     | 45        | 8.75%   |
| 501-600     | 28        | 5.45%   |
| 401-500     | 13        | 2.53%   |
| 601-700     | 9         | 1.75%   |
| 1501-2000   | 7         | 1.36%   |
| Unknown     | 6         | 1.17%   |
| 701-800     | 3         | 0.58%   |
| 1001-1500   | 3         | 0.58%   |
| 801-900     | 2         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 401       | 85.5%   |
| 16/10   | 55        | 11.73%  |
| 3/2     | 3         | 0.64%   |
| Unknown | 3         | 0.64%   |
| 4/3     | 2         | 0.43%   |
| 21/9    | 2         | 0.43%   |
| 6/5     | 1         | 0.21%   |
| 32/9    | 1         | 0.21%   |
| 3.73    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 221       | 43%     |
| 81-90          | 121       | 23.54%  |
| 121-130        | 35        | 6.81%   |
| 71-80          | 25        | 4.86%   |
| 201-250        | 22        | 4.28%   |
| 61-70          | 18        | 3.5%    |
| 301-350        | 13        | 2.53%   |
| 51-60          | 12        | 2.33%   |
| 351-500        | 11        | 2.14%   |
| More than 1000 | 9         | 1.75%   |
| 111-120        | 7         | 1.36%   |
| Unknown        | 6         | 1.17%   |
| 251-300        | 3         | 0.58%   |
| 151-200        | 3         | 0.58%   |
| 131-140        | 3         | 0.58%   |
| 501-1000       | 3         | 0.58%   |
| 141-150        | 2         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 231       | 45.29%  |
| 101-120       | 150       | 29.41%  |
| 51-100        | 63        | 12.35%  |
| 161-240       | 40        | 7.84%   |
| More than 240 | 11        | 2.16%   |
| 1-50          | 9         | 1.76%   |
| Unknown       | 6         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 407       | 85.86%  |
| 2     | 56        | 11.81%  |
| 3     | 6         | 1.27%   |
| 0     | 5         | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 267       | 34.77%  |
| Realtek Semiconductor                  | 256       | 33.33%  |
| Qualcomm Atheros                       | 85        | 11.07%  |
| Broadcom                               | 34        | 4.43%   |
| MediaTek                               | 22        | 2.86%   |
| Broadcom Limited                       | 13        | 1.69%   |
| TP-Link                                | 12        | 1.56%   |
| Samsung Electronics                    | 10        | 1.3%    |
| Xiaomi                                 | 8         | 1.04%   |
| Ralink Technology                      | 6         | 0.78%   |
| ASIX Electronics                       | 5         | 0.65%   |
| Qualcomm Atheros Communications        | 4         | 0.52%   |
| NetGear                                | 4         | 0.52%   |
| Huawei Technologies                    | 4         | 0.52%   |
| Ralink                                 | 3         | 0.39%   |
| Qualcomm                               | 3         | 0.39%   |
| OPPO Electronics                       | 3         | 0.39%   |
| ASUSTek Computer                       | 3         | 0.39%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.26%   |
| Sierra Wireless                        | 2         | 0.26%   |
| Nvidia                                 | 2         | 0.26%   |
| Linksys                                | 2         | 0.26%   |
| Lenovo                                 | 2         | 0.26%   |
| JMicron Technology                     | 2         | 0.26%   |
| Google                                 | 2         | 0.26%   |
| Ericsson Business Mobile Networks      | 2         | 0.26%   |
| Apple                                  | 2         | 0.26%   |
| ZyXEL Communications                   | 1         | 0.13%   |
| Sagem                                  | 1         | 0.13%   |
| Mercucys                               | 1         | 0.13%   |
| DisplayLink                            | 1         | 0.13%   |
| Dell                                   | 1         | 0.13%   |
| D-Link                                 | 1         | 0.13%   |
| Belkin Components                      | 1         | 0.13%   |
| Arduino SA                             | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 140       | 15.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 4.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 28        | 3.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 26        | 2.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 21        | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 20        | 2.15%   |
| Intel Wi-Fi 6 AX201                                                    | 19        | 2.04%   |
| Intel Wi-Fi 6 AX200                                                    | 19        | 2.04%   |
| Intel Wireless 8265 / 8275                                             | 18        | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 17        | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 16        | 1.72%   |
| Intel Wireless 7265                                                    | 14        | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 14        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 12        | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 11        | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 11        | 1.18%   |
| Intel Wireless 7260                                                    | 11        | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 11        | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 11        | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 9         | 0.97%   |
| Intel Wireless 8260                                                    | 9         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 8         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 0.86%   |
| Intel Wireless 3165                                                    | 7         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 7         | 0.75%   |
| Intel Ethernet Connection I218-LM                                      | 7         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6         | 0.65%   |
| Realtek Killer E2600 GbE Controller                                    | 6         | 0.65%   |
| Realtek 802.11ac NIC                                                   | 6         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                   | 6         | 0.65%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 6         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 259       | 49.62%  |
| Realtek Semiconductor           | 91        | 17.43%  |
| Qualcomm Atheros                | 69        | 13.22%  |
| Broadcom                        | 29        | 5.56%   |
| MediaTek                        | 20        | 3.83%   |
| TP-Link                         | 12        | 2.3%    |
| Broadcom Limited                | 11        | 2.11%   |
| Ralink Technology               | 6         | 1.15%   |
| Qualcomm Atheros Communications | 4         | 0.77%   |
| NetGear                         | 4         | 0.77%   |
| Ralink                          | 3         | 0.57%   |
| ASUSTek Computer                | 3         | 0.57%   |
| Sierra Wireless                 | 2         | 0.38%   |
| Linksys                         | 2         | 0.38%   |
| ZyXEL Communications            | 1         | 0.19%   |
| Sagem                           | 1         | 0.19%   |
| Qualcomm                        | 1         | 0.19%   |
| Mercucys                        | 1         | 0.19%   |
| Dell                            | 1         | 0.19%   |
| D-Link                          | 1         | 0.19%   |
| Belkin Components               | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                     | 26        | 4.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 21        | 4.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 20        | 3.82%   |
| Intel Wi-Fi 6 AX201                                                  | 19        | 3.63%   |
| Intel Wi-Fi 6 AX200                                                  | 19        | 3.63%   |
| Intel Wireless 8265 / 8275                                           | 18        | 3.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 17        | 3.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 16        | 3.05%   |
| Intel Wireless 7265                                                  | 14        | 2.67%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 14        | 2.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 12        | 2.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 11        | 2.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 11        | 2.1%    |
| Intel Wireless 7260                                                  | 11        | 2.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 11        | 2.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 11        | 2.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 9         | 1.72%   |
| Intel Wireless 8260                                                  | 9         | 1.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 8         | 1.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 8         | 1.53%   |
| Intel Wireless 3165                                                  | 7         | 1.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 7         | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 6         | 1.15%   |
| Realtek 802.11ac NIC                                                 | 6         | 1.15%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 6         | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                        | 6         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5         | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 5         | 0.95%   |
| Intel Centrino Advanced-N 6235                                       | 5         | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 4         | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 4         | 0.76%   |
| Qualcomm Atheros AR9271 802.11n                                      | 4         | 0.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 4         | 0.76%   |
| Intel Wireless 3160                                                  | 4         | 0.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 4         | 0.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 4         | 0.76%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 4         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 218       | 55.75%  |
| Intel                                  | 89        | 22.76%  |
| Qualcomm Atheros                       | 29        | 7.42%   |
| Broadcom                               | 11        | 2.81%   |
| Xiaomi                                 | 8         | 2.05%   |
| Samsung Electronics                    | 8         | 2.05%   |
| ASIX Electronics                       | 5         | 1.28%   |
| OPPO Electronics                       | 3         | 0.77%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.51%   |
| Qualcomm                               | 2         | 0.51%   |
| Nvidia                                 | 2         | 0.51%   |
| MediaTek                               | 2         | 0.51%   |
| Lenovo                                 | 2         | 0.51%   |
| JMicron Technology                     | 2         | 0.51%   |
| Google                                 | 2         | 0.51%   |
| Broadcom Limited                       | 2         | 0.51%   |
| Apple                                  | 2         | 0.51%   |
| Huawei Technologies                    | 1         | 0.26%   |
| DisplayLink                            | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 140       | 35.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 9.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 26        | 6.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 5.78%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 2.26%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 2.01%   |
| Intel Ethernet Connection I218-LM                                      | 7         | 1.76%   |
| Realtek Killer E2600 GbE Controller                                    | 6         | 1.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 1.51%   |
| Intel Ethernet Connection (6) I219-V                                   | 6         | 1.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 1.26%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 1.26%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 1.01%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 1.01%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.75%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.75%   |
| Intel Ethernet Connection (16) I219-V                                  | 3         | 0.75%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 3         | 0.75%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.5%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 2         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.5%    |
| OPPO CPH2477                                                           | 2         | 0.5%    |
| MediaTek Infinix SMART 5                                               | 2         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 0.5%    |
| Intel Ethernet Connection I217-V                                       | 2         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.5%    |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection (11) I219-LM                                 | 2         | 0.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 459       | 54.97%  |
| Ethernet | 368       | 44.07%  |
| Modem    | 8         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 372       | 77.02%  |
| Ethernet | 111       | 22.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 320       | 68.38%  |
| 1     | 137       | 29.27%  |
| 0     | 8         | 1.71%   |
| 3     | 3         | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 364       | 76.79%  |
| Yes     | 109       | 23%     |
| Unknown | 1         | 0.21%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 199       | 51.03%  |
| Realtek Semiconductor           | 46        | 11.79%  |
| Qualcomm Atheros Communications | 38        | 9.74%   |
| Broadcom                        | 21        | 5.38%   |
| IMC Networks                    | 19        | 4.87%   |
| Lite-On Technology              | 14        | 3.59%   |
| Foxconn / Hon Hai               | 14        | 3.59%   |
| Apple                           | 14        | 3.59%   |
| Dell                            | 4         | 1.03%   |
| Cambridge Silicon Radio         | 4         | 1.03%   |
| MediaTek                        | 3         | 0.77%   |
| Toshiba                         | 2         | 0.51%   |
| Realtek                         | 2         | 0.51%   |
| Ralink                          | 2         | 0.51%   |
| Hewlett-Packard                 | 2         | 0.51%   |
| ASUSTek Computer                | 2         | 0.51%   |
| TP-Link                         | 1         | 0.26%   |
| Dynex                           | 1         | 0.26%   |
| Alps Electric                   | 1         | 0.26%   |
| Unknown                         | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 62        | 15.9%   |
| Intel AX201 Bluetooth                               | 55        | 14.1%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 8.21%   |
| Realtek Bluetooth Radio                             | 28        | 7.18%   |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 4.62%   |
| Intel AX200 Bluetooth                               | 17        | 4.36%   |
| Intel AX211 Bluetooth                               | 14        | 3.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 3.33%   |
| IMC Networks Wireless_Device                        | 9         | 2.31%   |
| Apple Bluetooth USB Host Controller                 | 7         | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.54%   |
| Apple Bluetooth Host Controller                     | 6         | 1.54%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.28%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.28%   |
| IMC Networks Bluetooth Radio                        | 5         | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.28%   |
| IMC Networks Bluetooth Device                       | 4         | 1.03%   |
| Dell DW375 Bluetooth Module                         | 4         | 1.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.03%   |
| Broadcom HP Portable SoftSailing                    | 4         | 1.03%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.77%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.77%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.77%   |
| MediaTek Wireless_Device                            | 3         | 0.77%   |
| Lite-On Wireless_Device                             | 3         | 0.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.77%   |
| Intel AX210 Bluetooth                               | 3         | 0.77%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.77%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.77%   |
| Realtek Bluetooth Radio                             | 2         | 0.51%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.51%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.51%   |
| Lite-On Bluetooth Radio                             | 2         | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 391       | 68.72%  |
| Nvidia                 | 87        | 15.29%  |
| AMD                    | 75        | 13.18%  |
| JMTek                  | 3         | 0.53%   |
| Realtek Semiconductor  | 2         | 0.35%   |
| Razer USA              | 2         | 0.35%   |
| GN Netcom              | 2         | 0.35%   |
| Texas Instruments      | 1         | 0.18%   |
| Lenovo                 | 1         | 0.18%   |
| Guillemot              | 1         | 0.18%   |
| Generalplus Technology | 1         | 0.18%   |
| Conexant Systems       | 1         | 0.18%   |
| Apple                  | 1         | 0.18%   |
| Anker                  | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 57        | 8.42%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 43        | 6.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 38        | 5.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 34        | 5.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 33        | 4.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 31        | 4.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 27        | 3.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 2.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 2.95%   |
| Intel 8 Series HD Audio Controller                                                                | 20        | 2.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 18        | 2.66%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 2.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 16        | 2.36%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 2.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 1.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.77%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 1.77%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.77%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 11        | 1.62%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 11        | 1.62%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 10        | 1.48%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 1.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 1.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 9         | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 1.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.03%   |
| AMD High Definition Audio Controller                                                              | 7         | 1.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.74%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 5         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.59%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.59%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 0.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.59%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 114       | 30.56%  |
| SK hynix            | 69        | 18.5%   |
| Micron Technology   | 64        | 17.16%  |
| Crucial             | 26        | 6.97%   |
| Kingston            | 21        | 5.63%   |
| Unknown             | 11        | 2.95%   |
| Ramaxel Technology  | 11        | 2.95%   |
| Elpida              | 11        | 2.95%   |
| A-DATA Technology   | 8         | 2.14%   |
| Unknown (ABCD)      | 7         | 1.88%   |
| Nanya Technology    | 5         | 1.34%   |
| Team                | 4         | 1.07%   |
| Corsair             | 4         | 1.07%   |
| Smart               | 3         | 0.8%    |
| Transcend           | 2         | 0.54%   |
| PNY                 | 2         | 0.54%   |
| G.Skill             | 2         | 0.54%   |
| Unknown             | 2         | 0.54%   |
| Timetec             | 1         | 0.27%   |
| Teikon              | 1         | 0.27%   |
| Saikano             | 1         | 0.27%   |
| Lexar Co Limited    | 1         | 0.27%   |
| fef5                | 1         | 0.27%   |
| ChangXin Memory     | 1         | 0.27%   |
| Avant               | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 9         | 2.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 7         | 1.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.8%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.29%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.29%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.03%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.03%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.03%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 1.03%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.77%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.77%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.77%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.77%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.77%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 0.77%   |
| Crucial RAM CT8G4SFRA32A.M4FE 8GB SODIMM DDR4 3200MT/s           | 3         | 0.77%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.77%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.51%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 2         | 0.51%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.51%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 0.51%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 2         | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.51%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.51%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.51%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.51%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.51%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.51%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 153       | 48.88%  |
| DDR3    | 95        | 30.35%  |
| LPDDR4  | 23        | 7.35%   |
| LPDDR3  | 12        | 3.83%   |
| DDR5    | 10        | 3.19%   |
| LPDDR5  | 7         | 2.24%   |
| DDR2    | 6         | 1.92%   |
| Unknown | 5         | 1.6%    |
| SDRAM   | 1         | 0.32%   |
| DDR     | 1         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 270       | 86.54%  |
| Row Of Chips | 37        | 11.86%  |
| Unknown      | 4         | 1.28%   |
| Chip         | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 141       | 40.52%  |
| 4096  | 93        | 26.72%  |
| 16384 | 64        | 18.39%  |
| 2048  | 26        | 7.47%   |
| 32768 | 13        | 3.74%   |
| 1024  | 11        | 3.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 82        | 24.05%  |
| 1600    | 67        | 19.65%  |
| 2667    | 65        | 19.06%  |
| 2400    | 25        | 7.33%   |
| 1334    | 19        | 5.57%   |
| 2133    | 15        | 4.4%    |
| 4800    | 10        | 2.93%   |
| 1333    | 9         | 2.64%   |
| 6400    | 6         | 1.76%   |
| 4267    | 6         | 1.76%   |
| 1867    | 6         | 1.76%   |
| 5600    | 4         | 1.17%   |
| 1067    | 4         | 1.17%   |
| 1066    | 4         | 1.17%   |
| 3266    | 3         | 0.88%   |
| 667     | 3         | 0.88%   |
| 3733    | 2         | 0.59%   |
| 975     | 2         | 0.59%   |
| Unknown | 2         | 0.59%   |
| 8400    | 1         | 0.29%   |
| 7500    | 1         | 0.29%   |
| 4266    | 1         | 0.29%   |
| 2048    | 1         | 0.29%   |
| 1866    | 1         | 0.29%   |
| 800     | 1         | 0.29%   |
| 533     | 1         | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 66.67%  |
| Hewlett-Packard    | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP Deskjet 2050 J510    | 1         | 33.33%  |
| Brother HL-1210W series | 1         | 33.33%  |
| Brother DCP-T300        | 1         | 33.33%  |

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


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 104       | 24.7%   |
| IMC Networks                           | 47        | 11.16%  |
| Microdia                               | 32        | 7.6%    |
| Bison Electronics                      | 29        | 6.89%   |
| Quanta                                 | 25        | 5.94%   |
| Sunplus Innovation Technology          | 23        | 5.46%   |
| Realtek Semiconductor                  | 22        | 5.23%   |
| Luxvisions Innotech Limited            | 16        | 3.8%    |
| Acer                                   | 15        | 3.56%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 3.33%   |
| Apple                                  | 14        | 3.33%   |
| Syntek                                 | 13        | 3.09%   |
| Lite-On Technology                     | 9         | 2.14%   |
| Suyin                                  | 7         | 1.66%   |
| Sonix Technology                       | 7         | 1.66%   |
| Silicon Motion                         | 6         | 1.43%   |
| Samsung Electronics                    | 6         | 1.43%   |
| Ricoh                                  | 6         | 1.43%   |
| icSpring                               | 4         | 0.95%   |
| Alcor Micro                            | 4         | 0.95%   |
| Logitech                               | 3         | 0.71%   |
| SunplusIT                              | 2         | 0.48%   |
| Primax Electronics                     | 2         | 0.48%   |
| Importek                               | 2         | 0.48%   |
| USB Camera CS                          | 1         | 0.24%   |
| Tobii Technology AB                    | 1         | 0.24%   |
| ShineTech                              | 1         | 0.24%   |
| LG Electronics                         | 1         | 0.24%   |
| Lenovo                                 | 1         | 0.24%   |
| Goertek Electronics                    | 1         | 0.24%   |
| Genesys Logic                          | 1         | 0.24%   |
| AVerMedia Technologies                 | 1         | 0.24%   |
| ALi                                    | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 22        | 5.21%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 16        | 3.79%   |
| IMC Networks Integrated Camera                       | 12        | 2.84%   |
| Microdia Integrated_Webcam_HD                        | 11        | 2.61%   |
| Bison HD Webcam                                      | 11        | 2.61%   |
| Realtek Integrated_Webcam_HD                         | 9         | 2.13%   |
| Syntek Integrated Camera                             | 8         | 1.9%    |
| Chicony HD User Facing                               | 8         | 1.9%    |
| Sunplus Integrated_Webcam_HD                         | 6         | 1.42%   |
| Samsung Galaxy series, misc. (MTP mode)              | 6         | 1.42%   |
| Quanta HD User Facing                                | 6         | 1.42%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 6         | 1.42%   |
| Chicony HP Truevision HD                             | 6         | 1.42%   |
| Chicony HP HD Camera                                 | 6         | 1.42%   |
| Chicony HD Webcam                                    | 6         | 1.42%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 6         | 1.42%   |
| Quanta HP TrueVision HD Camera                       | 5         | 1.18%   |
| Chicony USB2.0 Camera                                | 5         | 1.18%   |
| Bison SunplusIT Integrated Camera                    | 5         | 1.18%   |
| Acer Integrated Camera                               | 5         | 1.18%   |
| Sonix USB2.0 HD UVC WebCam                           | 4         | 0.95%   |
| Realtek Integrated Webcam HD                         | 4         | 0.95%   |
| Quanta HP HD Camera                                  | 4         | 0.95%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 0.95%   |
| icSpring camera                                      | 4         | 0.95%   |
| Chicony USB2.0 HD UVC WebCam                         | 4         | 0.95%   |
| Chicony Integrated Camera (1280x720@30)              | 4         | 0.95%   |
| Bison Integrated Camera                              | 4         | 0.95%   |
| Apple FaceTime HD Camera                             | 4         | 0.95%   |
| Syntek Lenovo EasyCamera                             | 3         | 0.71%   |
| Quanta ACER HD User Facing                           | 3         | 0.71%   |
| Microdia Webcam Vitade AF                            | 3         | 0.71%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 0.71%   |
| Microdia Integrated Webcam HD                        | 3         | 0.71%   |
| Microdia Integrated Webcam                           | 3         | 0.71%   |
| Lite-On HP HD Camera                                 | 3         | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 0.71%   |
| IMC Networks HD Camera                               | 3         | 0.71%   |
| Chicony HP TrueVision HD Camera                      | 3         | 0.71%   |
| Chicony EasyCamera                                   | 3         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 33        | 37.08%  |
| Validity Sensors           | 28        | 31.46%  |
| Shenzhen Goodix Technology | 10        | 11.24%  |
| Elan Microelectronics      | 7         | 7.87%   |
| Upek                       | 4         | 4.49%   |
| AuthenTec                  | 3         | 3.37%   |
| LighTuning Technology      | 2         | 2.25%   |
| Samsung Electronics        | 1         | 1.12%   |
| HOLTEK                     | 1         | 1.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 11.24%  |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 8.99%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 6.74%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 5.62%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 5.62%   |
| Elan ELAN:Fingerprint                                                      | 5         | 5.62%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.49%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 4.49%   |
| Synaptics UWP WBDI Device                                                  | 4         | 4.49%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 3.37%   |
| Validity Sensors VFS491                                                    | 3         | 3.37%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.37%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 3.37%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.25%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.25%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.25%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.12%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.12%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.12%   |
| Synaptics WBDI                                                             | 1         | 1.12%   |
| Synaptics  WBDI                                                            | 1         | 1.12%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 1.12%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.12%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.12%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.12%   |
| Samsung Fingerprint Device                                                 | 1         | 1.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.12%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.12%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 1.12%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.12%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 17        | 58.62%  |
| Alcor Micro      | 8         | 27.59%  |
| Upek             | 1         | 3.45%   |
| SCM Microsystems | 1         | 3.45%   |
| OmniKey          | 1         | 3.45%   |
| O2 Micro         | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 27.59%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 24.14%  |
| Broadcom 5880                                                                | 6         | 20.69%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 10.34%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.45%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 3.45%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 3.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.45%   |
| Broadcom 58200                                                               | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 274       | 57.44%  |
| 1     | 162       | 33.96%  |
| 2     | 38        | 7.97%   |
| 3     | 2         | 0.42%   |
| 4     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 89        | 37.24%  |
| Graphics card         | 38        | 15.9%   |
| Chipcard              | 26        | 10.88%  |
| Multimedia controller | 22        | 9.21%   |
| Net/wireless          | 21        | 8.79%   |
| Net/ethernet          | 13        | 5.44%   |
| Camera                | 11        | 4.6%    |
| Storage               | 6         | 2.51%   |
| Bluetooth             | 5         | 2.09%   |
| Network               | 4         | 1.67%   |
| Sound                 | 2         | 0.84%   |
| Modem                 | 1         | 0.42%   |
| Card reader           | 1         | 0.42%   |


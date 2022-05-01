Fedora 35 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

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

Total: 1190

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15-3567            | [589f58c857](https://linux-hardware.org/?probe=589f58c857) | Apr 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [2065a3c2f3](https://linux-hardware.org/?probe=2065a3c2f3) | Apr 30, 2022 |
| Acer          | Aspire A514-54              | [70efbbb6c7](https://linux-hardware.org/?probe=70efbbb6c7) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9f5c24d3e8](https://linux-hardware.org/?probe=9f5c24d3e8) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [da73d0b77d](https://linux-hardware.org/?probe=da73d0b77d) | Apr 29, 2022 |
| Dell          | XPS 13 7390                 | [aadc641825](https://linux-hardware.org/?probe=aadc641825) | Apr 29, 2022 |
| Dell          | Inspiron N5110              | [fb1248d6be](https://linux-hardware.org/?probe=fb1248d6be) | Apr 29, 2022 |
| Acer          | Aspire A515-56              | [a10b79694f](https://linux-hardware.org/?probe=a10b79694f) | Apr 29, 2022 |
| MSI           | Katana GF76 11SC            | [15dcec28fc](https://linux-hardware.org/?probe=15dcec28fc) | Apr 29, 2022 |
| Lenovo        | ThinkPad X390 20Q1SCDR00    | [41a3cac1f4](https://linux-hardware.org/?probe=41a3cac1f4) | Apr 29, 2022 |
| Unknown       | X133                        | [b90d940d9e](https://linux-hardware.org/?probe=b90d940d9e) | Apr 29, 2022 |
| Lenovo        | ThinkPad T495 20NJ0012GM    | [81f7a796be](https://linux-hardware.org/?probe=81f7a796be) | Apr 28, 2022 |
| Dell          | Latitude 5310               | [b4e7215e3b](https://linux-hardware.org/?probe=b4e7215e3b) | Apr 28, 2022 |
| HP            | 255 G6 Notebook PC          | [d52cf822df](https://linux-hardware.org/?probe=d52cf822df) | Apr 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [6f26e0d7bd](https://linux-hardware.org/?probe=6f26e0d7bd) | Apr 28, 2022 |
| Dell          | XPS 13 9370                 | [349f8f5d64](https://linux-hardware.org/?probe=349f8f5d64) | Apr 27, 2022 |
| System76      | Pangolin                    | [d326fc9a39](https://linux-hardware.org/?probe=d326fc9a39) | Apr 27, 2022 |
| Lenovo        | IdeaPad Y470 0855           | [ee26833b58](https://linux-hardware.org/?probe=ee26833b58) | Apr 27, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f3c9dd19da](https://linux-hardware.org/?probe=f3c9dd19da) | Apr 26, 2022 |
| HP            | Notebook                    | [ec93418371](https://linux-hardware.org/?probe=ec93418371) | Apr 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [2b7f66b701](https://linux-hardware.org/?probe=2b7f66b701) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | [44714b01ff](https://linux-hardware.org/?probe=44714b01ff) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | [75188b99b5](https://linux-hardware.org/?probe=75188b99b5) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [e4c1fa069d](https://linux-hardware.org/?probe=e4c1fa069d) | Apr 26, 2022 |
| HP            | Pavilion Notebook           | [6a34230d87](https://linux-hardware.org/?probe=6a34230d87) | Apr 26, 2022 |
| Apple         | MacBookPro11,1              | [a8626eb701](https://linux-hardware.org/?probe=a8626eb701) | Apr 26, 2022 |
| HP            | ProBook 455R G6             | [3118a03e9b](https://linux-hardware.org/?probe=3118a03e9b) | Apr 25, 2022 |
| Google        | Bobba                       | [008afa9913](https://linux-hardware.org/?probe=008afa9913) | Apr 25, 2022 |
| Apple         | MacBookPro9,2               | [003f1099c2](https://linux-hardware.org/?probe=003f1099c2) | Apr 25, 2022 |
| Dell          | Inspiron 5567               | [9da2289998](https://linux-hardware.org/?probe=9da2289998) | Apr 24, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [85cc720515](https://linux-hardware.org/?probe=85cc720515) | Apr 24, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [ac10947315](https://linux-hardware.org/?probe=ac10947315) | Apr 24, 2022 |
| HP            | EliteBook 850 G6            | [438ad440d0](https://linux-hardware.org/?probe=438ad440d0) | Apr 24, 2022 |
| ASUSTek       | X750JN                      | [343a4c47a6](https://linux-hardware.org/?probe=343a4c47a6) | Apr 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [36f385210f](https://linux-hardware.org/?probe=36f385210f) | Apr 23, 2022 |
| Google        | Bobba                       | [a5c612d7ec](https://linux-hardware.org/?probe=a5c612d7ec) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Acer          | Swift SF514-51              | [d6c47a5367](https://linux-hardware.org/?probe=d6c47a5367) | Apr 23, 2022 |
| HP            | EliteBook 8570w             | [0a4b339d0f](https://linux-hardware.org/?probe=0a4b339d0f) | Apr 23, 2022 |
| Framework     | Laptop                      | [dbc00cbd42](https://linux-hardware.org/?probe=dbc00cbd42) | Apr 23, 2022 |
| Acer          | TravelMate P215-41-G2       | [dcfad64d9d](https://linux-hardware.org/?probe=dcfad64d9d) | Apr 23, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [ce0b6939ac](https://linux-hardware.org/?probe=ce0b6939ac) | Apr 22, 2022 |
| Google        | Bobba                       | [5ad66cbf53](https://linux-hardware.org/?probe=5ad66cbf53) | Apr 22, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Sony          | VPCEB3PGX                   | [1771623608](https://linux-hardware.org/?probe=1771623608) | Apr 22, 2022 |
| Timi          | TM1701                      | [dba97f1875](https://linux-hardware.org/?probe=dba97f1875) | Apr 21, 2022 |
| HP            | ZBook 15 G3                 | [664867989b](https://linux-hardware.org/?probe=664867989b) | Apr 21, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [37b1ff3685](https://linux-hardware.org/?probe=37b1ff3685) | Apr 21, 2022 |
| Gigabyte      | AERO 15XV8                  | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [4e2119abc8](https://linux-hardware.org/?probe=4e2119abc8) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d43a69ef63](https://linux-hardware.org/?probe=d43a69ef63) | Apr 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [aa8173a46a](https://linux-hardware.org/?probe=aa8173a46a) | Apr 20, 2022 |
| Dell          | XPS 13 9350                 | [ed27d7c06d](https://linux-hardware.org/?probe=ed27d7c06d) | Apr 20, 2022 |
| Dell          | XPS 13 9350                 | [2cd4849553](https://linux-hardware.org/?probe=2cd4849553) | Apr 20, 2022 |
| Dell          | Inspiron 7577               | [6843f2bcfe](https://linux-hardware.org/?probe=6843f2bcfe) | Apr 20, 2022 |
| HP            | ElitePad 1000 G2            | [05daf3f64b](https://linux-hardware.org/?probe=05daf3f64b) | Apr 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Lenovo        | Z50-70 20354                | [a7fcc96eb5](https://linux-hardware.org/?probe=a7fcc96eb5) | Apr 19, 2022 |
| Dell          | XPS 13 9310                 | [0f924d06d6](https://linux-hardware.org/?probe=0f924d06d6) | Apr 19, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [4fe85803b7](https://linux-hardware.org/?probe=4fe85803b7) | Apr 19, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| HP            | Laptop 15-dw0xxx            | [7f35172610](https://linux-hardware.org/?probe=7f35172610) | Apr 19, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [fa995794ba](https://linux-hardware.org/?probe=fa995794ba) | Apr 18, 2022 |
| Apple         | MacBookPro9,2               | [812afb255a](https://linux-hardware.org/?probe=812afb255a) | Apr 18, 2022 |
| Acer          | Swift SF114-34              | [068741773e](https://linux-hardware.org/?probe=068741773e) | Apr 18, 2022 |
| ASUSTek       | G551JW                      | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Timi          | TM1604                      | [2c182df836](https://linux-hardware.org/?probe=2c182df836) | Apr 18, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [2369e789c7](https://linux-hardware.org/?probe=2369e789c7) | Apr 18, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [08f9942632](https://linux-hardware.org/?probe=08f9942632) | Apr 18, 2022 |
| Dell          | Latitude E5520              | [1b428165cf](https://linux-hardware.org/?probe=1b428165cf) | Apr 18, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N70... | [db5f56be25](https://linux-hardware.org/?probe=db5f56be25) | Apr 18, 2022 |
| HP            | ElitePad 1000 G2            | [f7888cc252](https://linux-hardware.org/?probe=f7888cc252) | Apr 18, 2022 |
| HP            | Spectre Notebook            | [42d4ceac84](https://linux-hardware.org/?probe=42d4ceac84) | Apr 18, 2022 |
| HP            | Pavilion Laptop 15-cc6xx    | [42836ca452](https://linux-hardware.org/?probe=42836ca452) | Apr 17, 2022 |
| Chuwi         | HeroBook Air                | [647f782e9f](https://linux-hardware.org/?probe=647f782e9f) | Apr 17, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [382836d952](https://linux-hardware.org/?probe=382836d952) | Apr 16, 2022 |
| Positivo      | H14BU08                     | [43d44df3d2](https://linux-hardware.org/?probe=43d44df3d2) | Apr 16, 2022 |
| Alienware     | Area-51m R2                 | [e6a7b0ef42](https://linux-hardware.org/?probe=e6a7b0ef42) | Apr 16, 2022 |
| Dell          | Inspiron 5458               | [5f7dafa5b9](https://linux-hardware.org/?probe=5f7dafa5b9) | Apr 16, 2022 |
| Lenovo        | ThinkPad T490 20N3S19L00    | [5812cc4868](https://linux-hardware.org/?probe=5812cc4868) | Apr 16, 2022 |
| Dell          | XPS 13 9350                 | [d0e37d8bc1](https://linux-hardware.org/?probe=d0e37d8bc1) | Apr 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5bd22623b0](https://linux-hardware.org/?probe=5bd22623b0) | Apr 16, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b07e7e9974](https://linux-hardware.org/?probe=b07e7e9974) | Apr 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6454c55f08](https://linux-hardware.org/?probe=6454c55f08) | Apr 16, 2022 |
| HP            | Pavilion dv6500             | [064748981e](https://linux-hardware.org/?probe=064748981e) | Apr 15, 2022 |
| HP            | Pavilion dv6500             | [48350ccc67](https://linux-hardware.org/?probe=48350ccc67) | Apr 15, 2022 |
| Google        | Squawks                     | [a6dc68bba1](https://linux-hardware.org/?probe=a6dc68bba1) | Apr 15, 2022 |
| Notebook      | NH55RGQ                     | [a5b036d6a3](https://linux-hardware.org/?probe=a5b036d6a3) | Apr 15, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [c43bc1fcba](https://linux-hardware.org/?probe=c43bc1fcba) | Apr 15, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [c14702d147](https://linux-hardware.org/?probe=c14702d147) | Apr 15, 2022 |
| Toshiba       | Satellite P755              | [fc39ac9f46](https://linux-hardware.org/?probe=fc39ac9f46) | Apr 15, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e9969def2d](https://linux-hardware.org/?probe=e9969def2d) | Apr 15, 2022 |
| Acer          | Aspire A515-51              | [dcae73146f](https://linux-hardware.org/?probe=dcae73146f) | Apr 15, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0646755403](https://linux-hardware.org/?probe=0646755403) | Apr 15, 2022 |
| Getac         | S410                        | [a0ec8cd50e](https://linux-hardware.org/?probe=a0ec8cd50e) | Apr 14, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [832620cf67](https://linux-hardware.org/?probe=832620cf67) | Apr 14, 2022 |
| Framework     | Laptop                      | [a5950266d1](https://linux-hardware.org/?probe=a5950266d1) | Apr 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0000... | [50325a2b5c](https://linux-hardware.org/?probe=50325a2b5c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [cc1fade012](https://linux-hardware.org/?probe=cc1fade012) | Apr 14, 2022 |
| Framework     | Laptop                      | [8734154fb6](https://linux-hardware.org/?probe=8734154fb6) | Apr 14, 2022 |
| ASUSTek       | ROG Strix G713QC_G713QC     | [c54b458c01](https://linux-hardware.org/?probe=c54b458c01) | Apr 14, 2022 |
| Lenovo        | G500 20236                  | [2decdc1731](https://linux-hardware.org/?probe=2decdc1731) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| Lenovo        | ThinkPad P52 20MAS17228     | [dac73320e9](https://linux-hardware.org/?probe=dac73320e9) | Apr 14, 2022 |
| Dell          | XPS 13 9360                 | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell          | Latitude E6230              | [19e2fe3c97](https://linux-hardware.org/?probe=19e2fe3c97) | Apr 14, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [84815ec94e](https://linux-hardware.org/?probe=84815ec94e) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | [89de41a490](https://linux-hardware.org/?probe=89de41a490) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [5ef7e630fa](https://linux-hardware.org/?probe=5ef7e630fa) | Apr 14, 2022 |
| HP            | EliteBook 8570w             | [6faed9730c](https://linux-hardware.org/?probe=6faed9730c) | Apr 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7e6cb72711](https://linux-hardware.org/?probe=7e6cb72711) | Apr 13, 2022 |
| Dell          | XPS 13 9370                 | [20ed59527a](https://linux-hardware.org/?probe=20ed59527a) | Apr 13, 2022 |
| Acer          | Aspire A715-74G             | [9f5a2049e3](https://linux-hardware.org/?probe=9f5a2049e3) | Apr 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f365986dfc](https://linux-hardware.org/?probe=f365986dfc) | Apr 13, 2022 |
| Dell          | XPS 13 9360                 | [20f315a2e7](https://linux-hardware.org/?probe=20f315a2e7) | Apr 13, 2022 |
| Dell          | XPS 13 7390                 | [dcca838772](https://linux-hardware.org/?probe=dcca838772) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [bc22c713a7](https://linux-hardware.org/?probe=bc22c713a7) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [332355ddfa](https://linux-hardware.org/?probe=332355ddfa) | Apr 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [53ba287837](https://linux-hardware.org/?probe=53ba287837) | Apr 13, 2022 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [6dc94a82ab](https://linux-hardware.org/?probe=6dc94a82ab) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| Framework     | Laptop                      | [6de996aa1e](https://linux-hardware.org/?probe=6de996aa1e) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [0c40d42b4a](https://linux-hardware.org/?probe=0c40d42b4a) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| ASUSTek       | X75VCP                      | [21e0b65e1b](https://linux-hardware.org/?probe=21e0b65e1b) | Apr 13, 2022 |
| Acer          | Nitro AN517-41              | [b10d1a135d](https://linux-hardware.org/?probe=b10d1a135d) | Apr 13, 2022 |
| Dell          | Vostro 5470                 | [e79417a89e](https://linux-hardware.org/?probe=e79417a89e) | Apr 13, 2022 |
| Dell          | XPS 13 9380                 | [3385b17dd8](https://linux-hardware.org/?probe=3385b17dd8) | Apr 13, 2022 |
| Dell          | Latitude E6530              | [597013072b](https://linux-hardware.org/?probe=597013072b) | Apr 12, 2022 |
| HP            | 255 G6 Notebook PC          | [0d300b2fc3](https://linux-hardware.org/?probe=0d300b2fc3) | Apr 12, 2022 |
| HP            | EliteBook 2540p             | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [29c02b0294](https://linux-hardware.org/?probe=29c02b0294) | Apr 12, 2022 |
| HP            | 255 G6 Notebook PC          | [4d7659bd74](https://linux-hardware.org/?probe=4d7659bd74) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | [0809202e65](https://linux-hardware.org/?probe=0809202e65) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | [a3f3072035](https://linux-hardware.org/?probe=a3f3072035) | Apr 12, 2022 |
| HP            | ProBook 455 G7              | [153f53dadd](https://linux-hardware.org/?probe=153f53dadd) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2ce1788c33](https://linux-hardware.org/?probe=2ce1788c33) | Apr 11, 2022 |
| HP            | ProBook 455 G7              | [edebd20c8e](https://linux-hardware.org/?probe=edebd20c8e) | Apr 11, 2022 |
| Acer          | Aspire E5-571               | [b6c1c28521](https://linux-hardware.org/?probe=b6c1c28521) | Apr 11, 2022 |
| Apple         | MacBookPro4,1               | [40dd641006](https://linux-hardware.org/?probe=40dd641006) | Apr 10, 2022 |
| Apple         | MacBookPro4,1               | [2e80786e39](https://linux-hardware.org/?probe=2e80786e39) | Apr 10, 2022 |
| HP            | Pavilion 15                 | [f69f54968e](https://linux-hardware.org/?probe=f69f54968e) | Apr 10, 2022 |
| HP            | EliteBook 8570w             | [9d7c1a88d6](https://linux-hardware.org/?probe=9d7c1a88d6) | Apr 10, 2022 |
| ASUSTek       | X405UQ                      | [4b63447e77](https://linux-hardware.org/?probe=4b63447e77) | Apr 10, 2022 |
| Dell          | Latitude 7480               | [b235ce5f92](https://linux-hardware.org/?probe=b235ce5f92) | Apr 10, 2022 |
| ASUSTek       | X750JN                      | [703a4e77a3](https://linux-hardware.org/?probe=703a4e77a3) | Apr 09, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f8c3b429a2](https://linux-hardware.org/?probe=f8c3b429a2) | Apr 09, 2022 |
| Dell          | Latitude 7275               | [fe36710853](https://linux-hardware.org/?probe=fe36710853) | Apr 09, 2022 |
| Dell          | Latitude 7275               | [e6bc45d8d9](https://linux-hardware.org/?probe=e6bc45d8d9) | Apr 09, 2022 |
| Dell          | Inspiron 5458               | [7b3a49ec3c](https://linux-hardware.org/?probe=7b3a49ec3c) | Apr 09, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [eebc86ccbe](https://linux-hardware.org/?probe=eebc86ccbe) | Apr 09, 2022 |
| Dell          | Inspiron 15-3567            | [3ffa339c32](https://linux-hardware.org/?probe=3ffa339c32) | Apr 09, 2022 |
| Acer          | Aspire E1-531               | [9dbe75c090](https://linux-hardware.org/?probe=9dbe75c090) | Apr 09, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [e76eb71b7f](https://linux-hardware.org/?probe=e76eb71b7f) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [919af587bb](https://linux-hardware.org/?probe=919af587bb) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [3b16991947](https://linux-hardware.org/?probe=3b16991947) | Apr 08, 2022 |
| Dell          | XPS 13 7390                 | [03940a7514](https://linux-hardware.org/?probe=03940a7514) | Apr 08, 2022 |
| Acer          | Aspire A315-31              | [afd87f36b2](https://linux-hardware.org/?probe=afd87f36b2) | Apr 08, 2022 |
| Acer          | Nitro AN517-41              | [a9d4f38d23](https://linux-hardware.org/?probe=a9d4f38d23) | Apr 08, 2022 |
| Acer          | Nitro AN517-41              | [7d3cba901a](https://linux-hardware.org/?probe=7d3cba901a) | Apr 08, 2022 |
| ASUSTek       | N551JB                      | [edbf102771](https://linux-hardware.org/?probe=edbf102771) | Apr 08, 2022 |
| HP            | ProBook 445 G7 Notebook ... | [0d15f8a702](https://linux-hardware.org/?probe=0d15f8a702) | Apr 07, 2022 |
| Dell          | Latitude E6530              | [a99419647f](https://linux-hardware.org/?probe=a99419647f) | Apr 07, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [4a53e94722](https://linux-hardware.org/?probe=4a53e94722) | Apr 07, 2022 |
| Apple         | MacBookPro10,1              | [b53427c0f4](https://linux-hardware.org/?probe=b53427c0f4) | Apr 07, 2022 |
| ASUSTek       | N551JB                      | [e1f0b15197](https://linux-hardware.org/?probe=e1f0b15197) | Apr 07, 2022 |
| ASUSTek       | GL553VW                     | [779c7e3858](https://linux-hardware.org/?probe=779c7e3858) | Apr 07, 2022 |
| Framework     | Laptop                      | [bd5ea938e7](https://linux-hardware.org/?probe=bd5ea938e7) | Apr 07, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [158e261517](https://linux-hardware.org/?probe=158e261517) | Apr 07, 2022 |
| Apple         | MacBookPro8,1               | [6cd80e7357](https://linux-hardware.org/?probe=6cd80e7357) | Apr 07, 2022 |
| Acer          | Nitro AN517-41              | [4d7ea68368](https://linux-hardware.org/?probe=4d7ea68368) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| Dell          | Latitude 3520               | [1ec7dedd4c](https://linux-hardware.org/?probe=1ec7dedd4c) | Apr 06, 2022 |
| Dell          | Precision 7550              | [89df3f1bfd](https://linux-hardware.org/?probe=89df3f1bfd) | Apr 06, 2022 |
| Intel         | Shark Bay Client platfor... | [8b1a97afe3](https://linux-hardware.org/?probe=8b1a97afe3) | Apr 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | [8fe5122cdc](https://linux-hardware.org/?probe=8fe5122cdc) | Apr 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [a668b151a3](https://linux-hardware.org/?probe=a668b151a3) | Apr 06, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a6c37e7ee4](https://linux-hardware.org/?probe=a6c37e7ee4) | Apr 06, 2022 |
| Dell          | G3 3579                     | [9994b24cef](https://linux-hardware.org/?probe=9994b24cef) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [718b671125](https://linux-hardware.org/?probe=718b671125) | Apr 06, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [dbb3f589ad](https://linux-hardware.org/?probe=dbb3f589ad) | Apr 06, 2022 |
| Acer          | Nitro AN517-41              | [b7cc683cc7](https://linux-hardware.org/?probe=b7cc683cc7) | Apr 05, 2022 |
| Dell          | XPS 13 9305                 | [0e254bc578](https://linux-hardware.org/?probe=0e254bc578) | Apr 05, 2022 |
| Dell          | XPS 13 9370                 | [a2dd193a18](https://linux-hardware.org/?probe=a2dd193a18) | Apr 05, 2022 |
| Acer          | Aspire A315-31              | [219ae7c834](https://linux-hardware.org/?probe=219ae7c834) | Apr 05, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [00da75f071](https://linux-hardware.org/?probe=00da75f071) | Apr 05, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [18e1fc86be](https://linux-hardware.org/?probe=18e1fc86be) | Apr 05, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [5c28fb1391](https://linux-hardware.org/?probe=5c28fb1391) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [92130ffb61](https://linux-hardware.org/?probe=92130ffb61) | Apr 04, 2022 |
| Dell          | XPS 15 9570                 | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [bdd5a36f62](https://linux-hardware.org/?probe=bdd5a36f62) | Apr 04, 2022 |
| Apple         | MacBookPro15,1              | [1c4423ca19](https://linux-hardware.org/?probe=1c4423ca19) | Apr 04, 2022 |
| HP            | ElitePad 1000 G2            | [d479e2ae4a](https://linux-hardware.org/?probe=d479e2ae4a) | Apr 04, 2022 |
| ASUSTek       | UX301LAA                    | [1c631fdb63](https://linux-hardware.org/?probe=1c631fdb63) | Apr 04, 2022 |
| ASUSTek       | X550LC                      | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| Sony          | VPCEB4L1E                   | [358783a077](https://linux-hardware.org/?probe=358783a077) | Apr 03, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [3e8d03d8d6](https://linux-hardware.org/?probe=3e8d03d8d6) | Apr 03, 2022 |
| Dell          | Latitude 5520               | [0fc592dd2c](https://linux-hardware.org/?probe=0fc592dd2c) | Apr 03, 2022 |
| HP            | EliteBook 8770w             | [e826deade2](https://linux-hardware.org/?probe=e826deade2) | Apr 03, 2022 |
| Framework     | Laptop                      | [a0e35b1871](https://linux-hardware.org/?probe=a0e35b1871) | Apr 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [869407eb01](https://linux-hardware.org/?probe=869407eb01) | Apr 03, 2022 |
| Dell          | Precision 5530              | [96b22b6124](https://linux-hardware.org/?probe=96b22b6124) | Apr 03, 2022 |
| Dell          | Inspiron 5548               | [d187a0de09](https://linux-hardware.org/?probe=d187a0de09) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| Samsung       | 270E5J/2570EJ               | [2911dea3f0](https://linux-hardware.org/?probe=2911dea3f0) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | ProBook 650 G1              | [f13dbb1e06](https://linux-hardware.org/?probe=f13dbb1e06) | Apr 02, 2022 |
| Acer          | Swift SF114-34              | [5dcb0a1847](https://linux-hardware.org/?probe=5dcb0a1847) | Apr 02, 2022 |
| Dell          | Latitude 5500               | [798c0e5fa4](https://linux-hardware.org/?probe=798c0e5fa4) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| MSI           | GF63 Thin 9SCXR             | [3bc3694efb](https://linux-hardware.org/?probe=3bc3694efb) | Apr 02, 2022 |
| Timi          | TM1612                      | [7eb83bb23a](https://linux-hardware.org/?probe=7eb83bb23a) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [3c89c6c9d8](https://linux-hardware.org/?probe=3c89c6c9d8) | Apr 02, 2022 |
| ASUSTek       | X750JN                      | [11153fc9f1](https://linux-hardware.org/?probe=11153fc9f1) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [055b15c7a9](https://linux-hardware.org/?probe=055b15c7a9) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [8ae9fd4940](https://linux-hardware.org/?probe=8ae9fd4940) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| Gigabyte      | P65Q                        | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | [82ec2ff5f6](https://linux-hardware.org/?probe=82ec2ff5f6) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | [7aefa77b4b](https://linux-hardware.org/?probe=7aefa77b4b) | Apr 01, 2022 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | [97505bf353](https://linux-hardware.org/?probe=97505bf353) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | [9ebbf23e28](https://linux-hardware.org/?probe=9ebbf23e28) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | [95d2d82ede](https://linux-hardware.org/?probe=95d2d82ede) | Apr 01, 2022 |
| Dell          | Inspiron 14 5410            | [3acec795a6](https://linux-hardware.org/?probe=3acec795a6) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [d18cd45522](https://linux-hardware.org/?probe=d18cd45522) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [ec162ebae4](https://linux-hardware.org/?probe=ec162ebae4) | Apr 01, 2022 |
| Notebook      | NH55RGQ                     | [beed63b0d4](https://linux-hardware.org/?probe=beed63b0d4) | Apr 01, 2022 |
| GPU Compan... | GWTN141-4                   | [81e7639a72](https://linux-hardware.org/?probe=81e7639a72) | Apr 01, 2022 |
| HP            | ElitePad 1000 G2            | [b6da5f9629](https://linux-hardware.org/?probe=b6da5f9629) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Dell          | Inspiron 5548               | [06b3aacb51](https://linux-hardware.org/?probe=06b3aacb51) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [913c396bde](https://linux-hardware.org/?probe=913c396bde) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [6774f9f9c8](https://linux-hardware.org/?probe=6774f9f9c8) | Apr 01, 2022 |
| HP            | Laptop 17z-ca300            | [726d1e7b0f](https://linux-hardware.org/?probe=726d1e7b0f) | Mar 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [c01344bd43](https://linux-hardware.org/?probe=c01344bd43) | Mar 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| HP            | Pavilion Notebook           | [a18360bae8](https://linux-hardware.org/?probe=a18360bae8) | Mar 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [6ab27f6f88](https://linux-hardware.org/?probe=6ab27f6f88) | Mar 31, 2022 |
| Samsung       | RC420/RC520/RC720           | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | [2ce0540229](https://linux-hardware.org/?probe=2ce0540229) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | [f43d64639e](https://linux-hardware.org/?probe=f43d64639e) | Mar 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [43e45df9f5](https://linux-hardware.org/?probe=43e45df9f5) | Mar 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [b8716e4043](https://linux-hardware.org/?probe=b8716e4043) | Mar 30, 2022 |
| Toshiba       | TECRA Z50-A                 | [cd333e5720](https://linux-hardware.org/?probe=cd333e5720) | Mar 30, 2022 |
| Dell          | XPS 13 7390                 | [db3d70e53a](https://linux-hardware.org/?probe=db3d70e53a) | Mar 30, 2022 |
| HP            | EliteBook 840 G3            | [3a64f14cc4](https://linux-hardware.org/?probe=3a64f14cc4) | Mar 30, 2022 |
| HONOR         | NBD-WXX9                    | [dd51589f73](https://linux-hardware.org/?probe=dd51589f73) | Mar 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0f18e7b54b](https://linux-hardware.org/?probe=0f18e7b54b) | Mar 30, 2022 |
| HP            | Pavilion 17                 | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [fd1759c341](https://linux-hardware.org/?probe=fd1759c341) | Mar 29, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3e3c94b9f6](https://linux-hardware.org/?probe=3e3c94b9f6) | Mar 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HP            | OMEN by Laptop              | [88b64a12df](https://linux-hardware.org/?probe=88b64a12df) | Mar 29, 2022 |
| Hampoo        | C1W6_AP123C_6GB Reserved    | [ff622b910d](https://linux-hardware.org/?probe=ff622b910d) | Mar 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Dell          | Vostro 3580                 | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c1384b9063](https://linux-hardware.org/?probe=c1384b9063) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| MSI           | Delta 15 A5EFK              | [9c5efbe2a7](https://linux-hardware.org/?probe=9c5efbe2a7) | Mar 28, 2022 |
| HP            | Pavilion Notebook           | [ac807c9324](https://linux-hardware.org/?probe=ac807c9324) | Mar 27, 2022 |
| Dell          | Inspiron 3505               | [c472ae03f6](https://linux-hardware.org/?probe=c472ae03f6) | Mar 27, 2022 |
| HP            | ProBook 470 G5              | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| HP            | EliteBook 850 G6            | [084d60ff3b](https://linux-hardware.org/?probe=084d60ff3b) | Mar 27, 2022 |
| HP            | ElitePad 1000 G2            | [73be67de2c](https://linux-hardware.org/?probe=73be67de2c) | Mar 27, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [b557a2005c](https://linux-hardware.org/?probe=b557a2005c) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [64606b8247](https://linux-hardware.org/?probe=64606b8247) | Mar 26, 2022 |
| Fujitsu       | LIFEBOOK E746               | [dc5e0a376b](https://linux-hardware.org/?probe=dc5e0a376b) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [25ad4e35b9](https://linux-hardware.org/?probe=25ad4e35b9) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d5e927b59e](https://linux-hardware.org/?probe=d5e927b59e) | Mar 26, 2022 |
| Acer          | Aspire E5-575G              | [b47822d246](https://linux-hardware.org/?probe=b47822d246) | Mar 26, 2022 |
| HP            | Laptop 15s-eq2xxx           | [a640b0a024](https://linux-hardware.org/?probe=a640b0a024) | Mar 26, 2022 |
| ASUSTek       | N550JK                      | [a3ecefa43f](https://linux-hardware.org/?probe=a3ecefa43f) | Mar 26, 2022 |
| HP            | ElitePad 1000 G2            | [5861c8e75a](https://linux-hardware.org/?probe=5861c8e75a) | Mar 26, 2022 |
| Acer          | Aspire E5-573G              | [b78f0137ba](https://linux-hardware.org/?probe=b78f0137ba) | Mar 26, 2022 |
| Alienware     | m15 R6                      | [5505410995](https://linux-hardware.org/?probe=5505410995) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS09Y19    | [2602549f95](https://linux-hardware.org/?probe=2602549f95) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [1d0229f697](https://linux-hardware.org/?probe=1d0229f697) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [1ab1216e5b](https://linux-hardware.org/?probe=1ab1216e5b) | Mar 25, 2022 |
| Dell          | Vostro 5402                 | [b47655a721](https://linux-hardware.org/?probe=b47655a721) | Mar 25, 2022 |
| Sony          | VGN-FW180D                  | [9bbcb3d0ac](https://linux-hardware.org/?probe=9bbcb3d0ac) | Mar 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [da358bbf5c](https://linux-hardware.org/?probe=da358bbf5c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [4a6b3d619c](https://linux-hardware.org/?probe=4a6b3d619c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [7d1fa138d0](https://linux-hardware.org/?probe=7d1fa138d0) | Mar 25, 2022 |
| HP            | Pavilion 11 x360 PC         | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| Dell          | Inspiron 3542               | [870e407665](https://linux-hardware.org/?probe=870e407665) | Mar 25, 2022 |
| Lenovo        | G50-45 80E3                 | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| Dell          | XPS 15 9500                 | [911fd95d9f](https://linux-hardware.org/?probe=911fd95d9f) | Mar 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [1d606d499d](https://linux-hardware.org/?probe=1d606d499d) | Mar 24, 2022 |
| Dell          | Inspiron 5567               | [7c80283af3](https://linux-hardware.org/?probe=7c80283af3) | Mar 24, 2022 |
| Acer          | Aspire A515-43              | [52bc15cdf9](https://linux-hardware.org/?probe=52bc15cdf9) | Mar 24, 2022 |
| System76      | Gazelle                     | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| HP            | Laptop 15-db0xxx            | [ef1af7bbae](https://linux-hardware.org/?probe=ef1af7bbae) | Mar 23, 2022 |
| Dell          | XPS 13 9305                 | [1fb70f4b83](https://linux-hardware.org/?probe=1fb70f4b83) | Mar 23, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [912cb19656](https://linux-hardware.org/?probe=912cb19656) | Mar 23, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [55730a4af8](https://linux-hardware.org/?probe=55730a4af8) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| ASUSTek       | X75VCP                      | [54e978fcca](https://linux-hardware.org/?probe=54e978fcca) | Mar 23, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [6285900fd7](https://linux-hardware.org/?probe=6285900fd7) | Mar 22, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [f140780c32](https://linux-hardware.org/?probe=f140780c32) | Mar 22, 2022 |
| Acer          | Aspire A515-43              | [6934e641a4](https://linux-hardware.org/?probe=6934e641a4) | Mar 22, 2022 |
| Dell          | Latitude 5520               | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [2298f934bd](https://linux-hardware.org/?probe=2298f934bd) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| Razer         | Blade Stealth               | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| Dell          | Inspiron 15 5501            | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | [40767d2545](https://linux-hardware.org/?probe=40767d2545) | Mar 20, 2022 |
| HP            | Laptop 14-dk0xxx            | [bde47f2d75](https://linux-hardware.org/?probe=bde47f2d75) | Mar 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | [8366f92538](https://linux-hardware.org/?probe=8366f92538) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | [8f96005683](https://linux-hardware.org/?probe=8f96005683) | Mar 19, 2022 |
| HP            | EliteBook 8470p             | [3c40b29b63](https://linux-hardware.org/?probe=3c40b29b63) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| Dell          | Inspiron 5502               | [ce6b8e3716](https://linux-hardware.org/?probe=ce6b8e3716) | Mar 19, 2022 |
| Digibras      | NH4CU03                     | [7970a8e8d2](https://linux-hardware.org/?probe=7970a8e8d2) | Mar 19, 2022 |
| eMachines     | E725 V1.03                  | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| Acer          | Aspire A317-51G             | [f2a7cadaff](https://linux-hardware.org/?probe=f2a7cadaff) | Mar 18, 2022 |
| Toshiba       | Satellite C855-12R          | [96554352c8](https://linux-hardware.org/?probe=96554352c8) | Mar 18, 2022 |
| Lenovo        | ThinkPad P53 20QN000HGE     | [db71f4d011](https://linux-hardware.org/?probe=db71f4d011) | Mar 18, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c869642fe9](https://linux-hardware.org/?probe=c869642fe9) | Mar 18, 2022 |
| Dell          | Latitude E6420              | [e97e686e5e](https://linux-hardware.org/?probe=e97e686e5e) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| Lenovo        | G40-80 80JE                 | [c41639222f](https://linux-hardware.org/?probe=c41639222f) | Mar 17, 2022 |
| Dell          | Inspiron 5502               | [b5aeb18001](https://linux-hardware.org/?probe=b5aeb18001) | Mar 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6a5b5cd15e](https://linux-hardware.org/?probe=6a5b5cd15e) | Mar 17, 2022 |
| Dell          | XPS 15 9550                 | [f7eb058e61](https://linux-hardware.org/?probe=f7eb058e61) | Mar 17, 2022 |
| Lenovo        | G50-70 20351                | [16ced37ed8](https://linux-hardware.org/?probe=16ced37ed8) | Mar 17, 2022 |
| Lenovo        | ThinkPad X220 428767U       | [380351014b](https://linux-hardware.org/?probe=380351014b) | Mar 16, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | [1ac160aea7](https://linux-hardware.org/?probe=1ac160aea7) | Mar 15, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [66bda745cd](https://linux-hardware.org/?probe=66bda745cd) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | [62038e09e8](https://linux-hardware.org/?probe=62038e09e8) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | [cbebb0b476](https://linux-hardware.org/?probe=cbebb0b476) | Mar 15, 2022 |
| MSI           | GE75 Raider 10SE            | [affad66907](https://linux-hardware.org/?probe=affad66907) | Mar 14, 2022 |
| Acer          | Calpella                    | [038e7b15ee](https://linux-hardware.org/?probe=038e7b15ee) | Mar 14, 2022 |
| MSI           | GE75 Raider 10SE            | [79744a34f1](https://linux-hardware.org/?probe=79744a34f1) | Mar 14, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | ProBook 6465b               | [95ecc6cdbd](https://linux-hardware.org/?probe=95ecc6cdbd) | Mar 14, 2022 |
| Apple         | MacBookPro9,2               | [b400e8a455](https://linux-hardware.org/?probe=b400e8a455) | Mar 14, 2022 |
| Apple         | MacBook7,1                  | [5cdaea7c5a](https://linux-hardware.org/?probe=5cdaea7c5a) | Mar 14, 2022 |
| Dell          | Vostro 1014                 | [8df761ef60](https://linux-hardware.org/?probe=8df761ef60) | Mar 13, 2022 |
| Apple         | MacBookPro16,1              | [9cce5830b5](https://linux-hardware.org/?probe=9cce5830b5) | Mar 13, 2022 |
| Positivo      | N1250                       | [e0ac8b69f1](https://linux-hardware.org/?probe=e0ac8b69f1) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [739b74effe](https://linux-hardware.org/?probe=739b74effe) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Dell          | Latitude 7285               | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6e9075eebf](https://linux-hardware.org/?probe=6e9075eebf) | Mar 13, 2022 |
| Dell          | Latitude 5511               | [ec15afa8e7](https://linux-hardware.org/?probe=ec15afa8e7) | Mar 12, 2022 |
| Dell          | Precision 5540              | [99b2435d7a](https://linux-hardware.org/?probe=99b2435d7a) | Mar 12, 2022 |
| Lenovo        | G780 20138                  | [276b115350](https://linux-hardware.org/?probe=276b115350) | Mar 12, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| Acer          | Aspire 5250                 | [a3f9e83752](https://linux-hardware.org/?probe=a3f9e83752) | Mar 11, 2022 |
| Dell          | Latitude 7480               | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| Dell          | Latitude 5511               | [2372b12d5c](https://linux-hardware.org/?probe=2372b12d5c) | Mar 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [cbfe261386](https://linux-hardware.org/?probe=cbfe261386) | Mar 11, 2022 |
| HP            | Notebook                    | [de3091d5d4](https://linux-hardware.org/?probe=de3091d5d4) | Mar 11, 2022 |
| Apple         | MacBookPro10,1              | [2a4e580bd6](https://linux-hardware.org/?probe=2a4e580bd6) | Mar 11, 2022 |
| Dell          | G5 5505                     | [286d140bd5](https://linux-hardware.org/?probe=286d140bd5) | Mar 10, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [f4a2cbf25a](https://linux-hardware.org/?probe=f4a2cbf25a) | Mar 10, 2022 |
| HP            | ZBook 14u G4                | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| Acer          | Swift SF314-42              | [68e933e6a3](https://linux-hardware.org/?probe=68e933e6a3) | Mar 10, 2022 |
| Apple         | MacBookPro13,2              | [f1f2a94be9](https://linux-hardware.org/?probe=f1f2a94be9) | Mar 10, 2022 |
| Apple         | MacBookPro13,2              | [fc015f45ba](https://linux-hardware.org/?probe=fc015f45ba) | Mar 10, 2022 |
| HP            | EliteBook 850 G5            | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [849f4141ce](https://linux-hardware.org/?probe=849f4141ce) | Mar 09, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [49503537f5](https://linux-hardware.org/?probe=49503537f5) | Mar 09, 2022 |
| Positivo      | CHT12CP                     | [fa7f40245b](https://linux-hardware.org/?probe=fa7f40245b) | Mar 09, 2022 |
| Acer          | Aspire 4750                 | [0659469dbe](https://linux-hardware.org/?probe=0659469dbe) | Mar 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [4378396a20](https://linux-hardware.org/?probe=4378396a20) | Mar 08, 2022 |
| HP            | Pavilion g4                 | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [4eb9de0f3a](https://linux-hardware.org/?probe=4eb9de0f3a) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [02b4ade19f](https://linux-hardware.org/?probe=02b4ade19f) | Mar 08, 2022 |
| Acer          | Aspire A114-32              | [1260b41068](https://linux-hardware.org/?probe=1260b41068) | Mar 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [96833919d2](https://linux-hardware.org/?probe=96833919d2) | Mar 08, 2022 |
| Dell          | Inspiron 5458               | [16f5e2d856](https://linux-hardware.org/?probe=16f5e2d856) | Mar 08, 2022 |
| Apple         | MacBookPro11,4              | [f3eb9f941a](https://linux-hardware.org/?probe=f3eb9f941a) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | [2b8b852d07](https://linux-hardware.org/?probe=2b8b852d07) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| ASUSTek       | X550LC                      | [267fa2ca76](https://linux-hardware.org/?probe=267fa2ca76) | Mar 06, 2022 |
| Lenovo        | G40-80 80JE                 | [2bf4890b1b](https://linux-hardware.org/?probe=2bf4890b1b) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e14e313311](https://linux-hardware.org/?probe=e14e313311) | Mar 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [856cb873fc](https://linux-hardware.org/?probe=856cb873fc) | Mar 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [fc4d2904c3](https://linux-hardware.org/?probe=fc4d2904c3) | Mar 06, 2022 |
| Acer          | Aspire E1-522               | [1d4f09c200](https://linux-hardware.org/?probe=1d4f09c200) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| Dell          | Latitude E5470              | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| HP            | EliteBook 850 G5            | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| HP            | ProBook 430 G5              | [9b130dbcb5](https://linux-hardware.org/?probe=9b130dbcb5) | Mar 04, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [134d1cf65b](https://linux-hardware.org/?probe=134d1cf65b) | Mar 03, 2022 |
| Medion        | Akoya P6638                 | [102c7910e5](https://linux-hardware.org/?probe=102c7910e5) | Mar 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | [c5bf02a4d7](https://linux-hardware.org/?probe=c5bf02a4d7) | Mar 03, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [35507d8b67](https://linux-hardware.org/?probe=35507d8b67) | Mar 02, 2022 |
| HP            | ProBook 650 G1              | [89e589ec6b](https://linux-hardware.org/?probe=89e589ec6b) | Mar 02, 2022 |
| HP            | ProBook 650 G1              | [587195961c](https://linux-hardware.org/?probe=587195961c) | Mar 02, 2022 |
| Dell          | Latitude 5411               | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | G40-80 80JE                 | [476396ef7c](https://linux-hardware.org/?probe=476396ef7c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| System76      | Oryx Pro                    | [7c9f5c83cf](https://linux-hardware.org/?probe=7c9f5c83cf) | Mar 01, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [f61c04b0a8](https://linux-hardware.org/?probe=f61c04b0a8) | Mar 01, 2022 |
| Dell          | Latitude 7285               | [8d3fe46d72](https://linux-hardware.org/?probe=8d3fe46d72) | Mar 01, 2022 |
| HP            | EliteBook 840 G3            | [9ffc6b43ec](https://linux-hardware.org/?probe=9ffc6b43ec) | Feb 28, 2022 |
| Acer          | Aspire E1-522               | [4245cd910a](https://linux-hardware.org/?probe=4245cd910a) | Feb 28, 2022 |
| HP            | ProBook 650 G1              | [d58011c0f8](https://linux-hardware.org/?probe=d58011c0f8) | Feb 28, 2022 |
| HP            | ProBook 650 G1              | [6925ab1f20](https://linux-hardware.org/?probe=6925ab1f20) | Feb 28, 2022 |
| HP            | Notebook                    | [c8cd62d913](https://linux-hardware.org/?probe=c8cd62d913) | Feb 28, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [fa94978a0b](https://linux-hardware.org/?probe=fa94978a0b) | Feb 28, 2022 |
| Apple         | MacBookAir7,2               | [e2bc04b6f4](https://linux-hardware.org/?probe=e2bc04b6f4) | Feb 27, 2022 |
| Apple         | MacBookAir7,2               | [592d42e16c](https://linux-hardware.org/?probe=592d42e16c) | Feb 27, 2022 |
| Lenovo        | G70-70 80HW007LNX           | [a0ba78ccea](https://linux-hardware.org/?probe=a0ba78ccea) | Feb 27, 2022 |
| HP            | ProBook 640 G2              | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| HP            | Pavilion Notebook           | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | [24861666e2](https://linux-hardware.org/?probe=24861666e2) | Feb 27, 2022 |
| Lenovo        | IdeaPad S540-14IML Touch... | [22bb5f0b44](https://linux-hardware.org/?probe=22bb5f0b44) | Feb 27, 2022 |
| HUAWEI        | KLVL-WXX9                   | [efd62e1ed7](https://linux-hardware.org/?probe=efd62e1ed7) | Feb 26, 2022 |
| Dell          | XPS 13 9305                 | [36aacb1723](https://linux-hardware.org/?probe=36aacb1723) | Feb 26, 2022 |
| HP            | Pavilion g4                 | [0e40990ec2](https://linux-hardware.org/?probe=0e40990ec2) | Feb 26, 2022 |
| HP            | Pavilion 15                 | [463d26d75c](https://linux-hardware.org/?probe=463d26d75c) | Feb 26, 2022 |
| HP            | Pavilion 17                 | [d4a3fb2dfc](https://linux-hardware.org/?probe=d4a3fb2dfc) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| Acer          | Aspire E5-471               | [194baf83e9](https://linux-hardware.org/?probe=194baf83e9) | Feb 25, 2022 |
| Dell          | Latitude 3350               | [093650ba06](https://linux-hardware.org/?probe=093650ba06) | Feb 25, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [13b7868e73](https://linux-hardware.org/?probe=13b7868e73) | Feb 24, 2022 |
| Dell          | Inspiron 5567               | [0e9130cffe](https://linux-hardware.org/?probe=0e9130cffe) | Feb 24, 2022 |
| Google        | Snappy                      | [cf0b11bd65](https://linux-hardware.org/?probe=cf0b11bd65) | Feb 24, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [15df5df598](https://linux-hardware.org/?probe=15df5df598) | Feb 24, 2022 |
| ASUSTek       | X553MA                      | [020df21e37](https://linux-hardware.org/?probe=020df21e37) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| Lenovo        | IdeaPad 3 15IML05 U 81WB    | [73c7d63295](https://linux-hardware.org/?probe=73c7d63295) | Feb 23, 2022 |
| Google        | Edgar                       | [46f5948f03](https://linux-hardware.org/?probe=46f5948f03) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f09566c9ee](https://linux-hardware.org/?probe=f09566c9ee) | Feb 23, 2022 |
| Samsung       | 750XDA                      | [ad6823c08e](https://linux-hardware.org/?probe=ad6823c08e) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| MSI           | GE63VR 7RF                  | [68e1d81309](https://linux-hardware.org/?probe=68e1d81309) | Feb 23, 2022 |
| Apple         | MacBookPro12,1              | [677ffe54b5](https://linux-hardware.org/?probe=677ffe54b5) | Feb 23, 2022 |
| Dell          | Inspiron 7577               | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| HP            | ProBook 430 G5              | [b9cb7cad60](https://linux-hardware.org/?probe=b9cb7cad60) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ee3ef301c2](https://linux-hardware.org/?probe=ee3ef301c2) | Feb 22, 2022 |
| Jumper        | EZbook                      | [9cded25245](https://linux-hardware.org/?probe=9cded25245) | Feb 22, 2022 |
| Lenovo        | V14-ADA 82C6                | [94c0f0f3a3](https://linux-hardware.org/?probe=94c0f0f3a3) | Feb 22, 2022 |
| Panasonic     | CFSV9-1                     | [fa3b39bca1](https://linux-hardware.org/?probe=fa3b39bca1) | Feb 21, 2022 |
| HP            | Notebook                    | [d8dd214532](https://linux-hardware.org/?probe=d8dd214532) | Feb 21, 2022 |
| HP            | Laptop 14z-dk100            | [65130b9760](https://linux-hardware.org/?probe=65130b9760) | Feb 21, 2022 |
| eMachines     | E725 V1.03                  | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Acer          | Swift SFX14-41G             | [5eb9d81462](https://linux-hardware.org/?probe=5eb9d81462) | Feb 20, 2022 |
| Acer          | Aspire A515-54G             | [388a17923c](https://linux-hardware.org/?probe=388a17923c) | Feb 20, 2022 |
| ASUSTek       | G551JK                      | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [229a11c203](https://linux-hardware.org/?probe=229a11c203) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | [65c44b63d6](https://linux-hardware.org/?probe=65c44b63d6) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | [d8c4226f82](https://linux-hardware.org/?probe=d8c4226f82) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | [2a934577d6](https://linux-hardware.org/?probe=2a934577d6) | Feb 20, 2022 |
| HP            | Notebook                    | [b2bc5693f7](https://linux-hardware.org/?probe=b2bc5693f7) | Feb 20, 2022 |
| Apple         | MacBookAir5,2               | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Acer          | Aspire A515-54G             | [5d973743c8](https://linux-hardware.org/?probe=5d973743c8) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | [c73dc0aa9f](https://linux-hardware.org/?probe=c73dc0aa9f) | Feb 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [1ad67d12e0](https://linux-hardware.org/?probe=1ad67d12e0) | Feb 19, 2022 |
| Positivo      | CHT14B                      | [c2f39e4414](https://linux-hardware.org/?probe=c2f39e4414) | Feb 19, 2022 |
| Positivo      | CHT14B                      | [674256dc2a](https://linux-hardware.org/?probe=674256dc2a) | Feb 19, 2022 |
| HP            | ZBook 17 G4                 | [0ac02f47be](https://linux-hardware.org/?probe=0ac02f47be) | Feb 19, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [f988c3bfdc](https://linux-hardware.org/?probe=f988c3bfdc) | Feb 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1c65c7204d](https://linux-hardware.org/?probe=1c65c7204d) | Feb 18, 2022 |
| Acer          | Aspire E5-575G              | [4cbc6b81bf](https://linux-hardware.org/?probe=4cbc6b81bf) | Feb 18, 2022 |
| Avell High... | B.ON                        | [3b3e1a7730](https://linux-hardware.org/?probe=3b3e1a7730) | Feb 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3221ab6775](https://linux-hardware.org/?probe=3221ab6775) | Feb 17, 2022 |
| Dell          | Latitude E6330              | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| HP            | Dratini                     | [bb3f3445ee](https://linux-hardware.org/?probe=bb3f3445ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [c896752de0](https://linux-hardware.org/?probe=c896752de0) | Feb 17, 2022 |
| Inspire Te... | Trio Windows OD 1.0         | [a0f755c28a](https://linux-hardware.org/?probe=a0f755c28a) | Feb 17, 2022 |
| Avell High... | B.ON                        | [26b25d67d6](https://linux-hardware.org/?probe=26b25d67d6) | Feb 17, 2022 |
| Acer          | Predator G9-793             | [45ec93214f](https://linux-hardware.org/?probe=45ec93214f) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e03bf2b8a8](https://linux-hardware.org/?probe=e03bf2b8a8) | Feb 16, 2022 |
| System76      | Lemur Pro                   | [3a7527d1e3](https://linux-hardware.org/?probe=3a7527d1e3) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [faca13ef0b](https://linux-hardware.org/?probe=faca13ef0b) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [d2f55f9d63](https://linux-hardware.org/?probe=d2f55f9d63) | Feb 16, 2022 |
| ASUSTek       | T200TAC                     | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | [9a9f646438](https://linux-hardware.org/?probe=9a9f646438) | Feb 15, 2022 |
| HUAWEI        | KLVL-WXX9                   | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| ASUSTek       | X550WE                      | [beed529fc3](https://linux-hardware.org/?probe=beed529fc3) | Feb 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Dell          | XPS 15 9550                 | [701eeea0ed](https://linux-hardware.org/?probe=701eeea0ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [32022a8232](https://linux-hardware.org/?probe=32022a8232) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [372c231b58](https://linux-hardware.org/?probe=372c231b58) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | [e82c11b42e](https://linux-hardware.org/?probe=e82c11b42e) | Feb 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | [a4471fe730](https://linux-hardware.org/?probe=a4471fe730) | Feb 13, 2022 |
| Acer          | Aspire A514-54              | [1f5dd04a09](https://linux-hardware.org/?probe=1f5dd04a09) | Feb 13, 2022 |
| Apple         | MacBookPro12,1              | [aeec085062](https://linux-hardware.org/?probe=aeec085062) | Feb 13, 2022 |
| PC Special... | NH5xAx                      | [5e0b855dbf](https://linux-hardware.org/?probe=5e0b855dbf) | Feb 13, 2022 |
| Apple         | MacBookAir7,2               | [91fa01f5a6](https://linux-hardware.org/?probe=91fa01f5a6) | Feb 12, 2022 |
| Apple         | MacBookAir7,2               | [dc1249f2a1](https://linux-hardware.org/?probe=dc1249f2a1) | Feb 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [42674c38b2](https://linux-hardware.org/?probe=42674c38b2) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Acer          | Aspire A515-54G             | [f8e7f688a6](https://linux-hardware.org/?probe=f8e7f688a6) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | [4c500fd383](https://linux-hardware.org/?probe=4c500fd383) | Feb 11, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [2cfb1f14b9](https://linux-hardware.org/?probe=2cfb1f14b9) | Feb 10, 2022 |
| Dell          | Latitude 5511               | [7a45e17643](https://linux-hardware.org/?probe=7a45e17643) | Feb 10, 2022 |
| Dell          | Latitude 5511               | [bf3129ad00](https://linux-hardware.org/?probe=bf3129ad00) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b2d14e7f15](https://linux-hardware.org/?probe=b2d14e7f15) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2661cf0743](https://linux-hardware.org/?probe=2661cf0743) | Feb 10, 2022 |
| Acer          | Nitro AN515-42              | [4906efe7f4](https://linux-hardware.org/?probe=4906efe7f4) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | [83ab33660d](https://linux-hardware.org/?probe=83ab33660d) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | [52bec77385](https://linux-hardware.org/?probe=52bec77385) | Feb 09, 2022 |
| Acer          | Nitro AN515-42              | [52d6fa9b66](https://linux-hardware.org/?probe=52d6fa9b66) | Feb 09, 2022 |
| HP            | EliteBook 840 G6            | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [b7e0365760](https://linux-hardware.org/?probe=b7e0365760) | Feb 08, 2022 |
| ASUSTek       | X75VC                       | [55fda8de04](https://linux-hardware.org/?probe=55fda8de04) | Feb 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [b4cfe297d4](https://linux-hardware.org/?probe=b4cfe297d4) | Feb 08, 2022 |
| Lenovo        | ThinkPad X230 23257R2       | [4fa07e0a61](https://linux-hardware.org/?probe=4fa07e0a61) | Feb 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [b400a64d30](https://linux-hardware.org/?probe=b400a64d30) | Feb 07, 2022 |
| Acer          | Aspire E5-575               | [cb02bc65cc](https://linux-hardware.org/?probe=cb02bc65cc) | Feb 07, 2022 |
| HP            | Pavilion dv6                | [0ba10bc3bb](https://linux-hardware.org/?probe=0ba10bc3bb) | Feb 07, 2022 |
| Lenovo        | Unknown                     | [8f315e1abe](https://linux-hardware.org/?probe=8f315e1abe) | Feb 07, 2022 |
| Lenovo        | Unknown                     | [bf281646d9](https://linux-hardware.org/?probe=bf281646d9) | Feb 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5b6802c8e3](https://linux-hardware.org/?probe=5b6802c8e3) | Feb 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [61e4b1c45e](https://linux-hardware.org/?probe=61e4b1c45e) | Feb 06, 2022 |
| Lenovo        | G70-70 80HW007LNX           | [79e8d4895c](https://linux-hardware.org/?probe=79e8d4895c) | Feb 06, 2022 |
| Lenovo        | Ducati 5 82ES               | [3364f4de6b](https://linux-hardware.org/?probe=3364f4de6b) | Feb 06, 2022 |
| HP            | Compaq 6730s                | [8d1fa47bb0](https://linux-hardware.org/?probe=8d1fa47bb0) | Feb 06, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [73db0d90e9](https://linux-hardware.org/?probe=73db0d90e9) | Feb 06, 2022 |
| ASUSTek       | GL702VSK                    | [d3eb319919](https://linux-hardware.org/?probe=d3eb319919) | Feb 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a3397b67bd](https://linux-hardware.org/?probe=a3397b67bd) | Feb 05, 2022 |
| Dell          | Inspiron 5537               | [79e02b1ade](https://linux-hardware.org/?probe=79e02b1ade) | Feb 05, 2022 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [ce23fdbead](https://linux-hardware.org/?probe=ce23fdbead) | Feb 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [d457ee5311](https://linux-hardware.org/?probe=d457ee5311) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| HUAWEI        | NBM-WXX9                    | [5256293dec](https://linux-hardware.org/?probe=5256293dec) | Feb 05, 2022 |
| Framework     | Laptop                      | [64e6669cbc](https://linux-hardware.org/?probe=64e6669cbc) | Feb 04, 2022 |
| Dell          | Inspiron 5521               | [8d4968c10a](https://linux-hardware.org/?probe=8d4968c10a) | Feb 04, 2022 |
| Acer          | Aspire A515-43              | [6bc39a1855](https://linux-hardware.org/?probe=6bc39a1855) | Feb 04, 2022 |
| Toshiba       | Satellite C645              | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ca238c69a5](https://linux-hardware.org/?probe=ca238c69a5) | Feb 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [862367b523](https://linux-hardware.org/?probe=862367b523) | Feb 03, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| Dell          | XPS 13 9310                 | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [d9cc5f0548](https://linux-hardware.org/?probe=d9cc5f0548) | Feb 03, 2022 |
| Dell          | Latitude E6230              | [05d9080c0c](https://linux-hardware.org/?probe=05d9080c0c) | Feb 03, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [2cb72b3867](https://linux-hardware.org/?probe=2cb72b3867) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| Dell          | XPS 13 7390                 | [978273c0aa](https://linux-hardware.org/?probe=978273c0aa) | Feb 02, 2022 |
| Sony          | SVD1121Q2EB                 | [8e484b15d2](https://linux-hardware.org/?probe=8e484b15d2) | Feb 02, 2022 |
| HP            | ProBook 6465b               | [aca95b9f2d](https://linux-hardware.org/?probe=aca95b9f2d) | Feb 01, 2022 |
| Dell          | Vostro 3500                 | [c9cae610a6](https://linux-hardware.org/?probe=c9cae610a6) | Feb 01, 2022 |
| PC Special... | NH5xAx                      | [6c8a746762](https://linux-hardware.org/?probe=6c8a746762) | Feb 01, 2022 |
| Samsung       | RV409/RV509/RV709           | [535f5504f0](https://linux-hardware.org/?probe=535f5504f0) | Feb 01, 2022 |
| Dell          | Precision 5530              | [3bb85a7897](https://linux-hardware.org/?probe=3bb85a7897) | Jan 31, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [b7796bb104](https://linux-hardware.org/?probe=b7796bb104) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [8efcb72970](https://linux-hardware.org/?probe=8efcb72970) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [316ea97198](https://linux-hardware.org/?probe=316ea97198) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [940c2e990d](https://linux-hardware.org/?probe=940c2e990d) | Jan 31, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ebe757d792](https://linux-hardware.org/?probe=ebe757d792) | Jan 30, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N2000LFR    | [0c7293a8ec](https://linux-hardware.org/?probe=0c7293a8ec) | Jan 30, 2022 |
| Lenovo        | ThinkPad T420 4180F65       | [23a97a1da0](https://linux-hardware.org/?probe=23a97a1da0) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | [88eae6cdfb](https://linux-hardware.org/?probe=88eae6cdfb) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | [d8040d8fc4](https://linux-hardware.org/?probe=d8040d8fc4) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c1494af863](https://linux-hardware.org/?probe=c1494af863) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | [209156e57d](https://linux-hardware.org/?probe=209156e57d) | Jan 29, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | [2f9a17c907](https://linux-hardware.org/?probe=2f9a17c907) | Jan 29, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e06431af49](https://linux-hardware.org/?probe=e06431af49) | Jan 29, 2022 |
| Apple         | MacBookAir6,2               | [2440be23b6](https://linux-hardware.org/?probe=2440be23b6) | Jan 29, 2022 |
| HP            | ZBook 17 G2                 | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4a98af8b6c](https://linux-hardware.org/?probe=4a98af8b6c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [e6af97e09c](https://linux-hardware.org/?probe=e6af97e09c) | Jan 29, 2022 |
| Dell          | Latitude 5511               | [94f621a74b](https://linux-hardware.org/?probe=94f621a74b) | Jan 29, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c573633ba7](https://linux-hardware.org/?probe=c573633ba7) | Jan 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [bab2021d07](https://linux-hardware.org/?probe=bab2021d07) | Jan 28, 2022 |
| ASUSTek       | X510UNR                     | [64f7ad2ba1](https://linux-hardware.org/?probe=64f7ad2ba1) | Jan 27, 2022 |
| Toshiba       | Satellite C660              | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| Apple         | MacBookPro9,2               | [d112bf0361](https://linux-hardware.org/?probe=d112bf0361) | Jan 27, 2022 |
| Mediacom      | GTZS                        | [10a0d977b0](https://linux-hardware.org/?probe=10a0d977b0) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b930fcaa84](https://linux-hardware.org/?probe=b930fcaa84) | Jan 26, 2022 |
| Dell          | XPS 13 7390                 | [95d6e59e28](https://linux-hardware.org/?probe=95d6e59e28) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [738074142b](https://linux-hardware.org/?probe=738074142b) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1bd39d2b68](https://linux-hardware.org/?probe=1bd39d2b68) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [9613005856](https://linux-hardware.org/?probe=9613005856) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [36a39bf7eb](https://linux-hardware.org/?probe=36a39bf7eb) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [9d12ae4f9a](https://linux-hardware.org/?probe=9d12ae4f9a) | Jan 26, 2022 |
| Acer          | Nitro AN515-52              | [e9f06efa7a](https://linux-hardware.org/?probe=e9f06efa7a) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [041c78217d](https://linux-hardware.org/?probe=041c78217d) | Jan 26, 2022 |
| Dell          | Precision 5510              | [511eeac9a0](https://linux-hardware.org/?probe=511eeac9a0) | Jan 25, 2022 |
| Dell          | Latitude E7470              | [c47b0efb73](https://linux-hardware.org/?probe=c47b0efb73) | Jan 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | [5846d2031f](https://linux-hardware.org/?probe=5846d2031f) | Jan 25, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c7fbcbcd07](https://linux-hardware.org/?probe=c7fbcbcd07) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Acer          | Nitro AN515-45              | [34568da477](https://linux-hardware.org/?probe=34568da477) | Jan 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [d6ea0ad749](https://linux-hardware.org/?probe=d6ea0ad749) | Jan 23, 2022 |
| Acer          | Nitro AN515-45              | [1cb9ebbbd4](https://linux-hardware.org/?probe=1cb9ebbbd4) | Jan 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | [e10bf3d056](https://linux-hardware.org/?probe=e10bf3d056) | Jan 23, 2022 |
| SCHNEIDER     | SCL141CTP                   | [ff14e3fa97](https://linux-hardware.org/?probe=ff14e3fa97) | Jan 23, 2022 |
| Apple         | MacBookPro14,1              | [783456509a](https://linux-hardware.org/?probe=783456509a) | Jan 22, 2022 |
| HP            | ProBook 470 G5              | [6610c7d6e1](https://linux-hardware.org/?probe=6610c7d6e1) | Jan 22, 2022 |
| Dell          | Inspiron N5110              | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [427ce82d40](https://linux-hardware.org/?probe=427ce82d40) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [2c0f007811](https://linux-hardware.org/?probe=2c0f007811) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [636e98e6e5](https://linux-hardware.org/?probe=636e98e6e5) | Jan 21, 2022 |
| Dell          | XPS 13 9350                 | [485c5e0968](https://linux-hardware.org/?probe=485c5e0968) | Jan 21, 2022 |
| Notebook      | NH55RGQ                     | [92e8102b7d](https://linux-hardware.org/?probe=92e8102b7d) | Jan 21, 2022 |
| Dell          | Latitude E6530              | [bf71e70abb](https://linux-hardware.org/?probe=bf71e70abb) | Jan 21, 2022 |
| Dell          | Inspiron 7591               | [2f1c294587](https://linux-hardware.org/?probe=2f1c294587) | Jan 21, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [c63c055197](https://linux-hardware.org/?probe=c63c055197) | Jan 21, 2022 |
| HP            | Laptop 15s-fq2xxx           | [172a8a48ad](https://linux-hardware.org/?probe=172a8a48ad) | Jan 21, 2022 |
| Acer          | Aspire A315-41G             | [03a8c77758](https://linux-hardware.org/?probe=03a8c77758) | Jan 20, 2022 |
| Acer          | Aspire A315-41G             | [df698a1427](https://linux-hardware.org/?probe=df698a1427) | Jan 20, 2022 |
| Lenovo        | B490 37722QP                | [6b32b6b8ef](https://linux-hardware.org/?probe=6b32b6b8ef) | Jan 20, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | [0ae4377d83](https://linux-hardware.org/?probe=0ae4377d83) | Jan 19, 2022 |
| Acer          | Aspire E5-573G              | [30829ce42e](https://linux-hardware.org/?probe=30829ce42e) | Jan 19, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | [1a128aada0](https://linux-hardware.org/?probe=1a128aada0) | Jan 19, 2022 |
| Positivo      | H14BU08                     | [8fb0d7e730](https://linux-hardware.org/?probe=8fb0d7e730) | Jan 19, 2022 |
| Acer          | Swift SF314-42              | [a2e70fe7b1](https://linux-hardware.org/?probe=a2e70fe7b1) | Jan 19, 2022 |
| HP            | Pavilion Notebook           | [533f74b810](https://linux-hardware.org/?probe=533f74b810) | Jan 19, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [2407b5f5bb](https://linux-hardware.org/?probe=2407b5f5bb) | Jan 19, 2022 |
| Dell          | Latitude E6530              | [8559d4a5b0](https://linux-hardware.org/?probe=8559d4a5b0) | Jan 19, 2022 |
| Lenovo        | B490 37722QP                | [3113fb2078](https://linux-hardware.org/?probe=3113fb2078) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | [a168ef0aa5](https://linux-hardware.org/?probe=a168ef0aa5) | Jan 18, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [738f12d2e4](https://linux-hardware.org/?probe=738f12d2e4) | Jan 17, 2022 |
| Acer          | Predator PH315-51           | [d6edc6139f](https://linux-hardware.org/?probe=d6edc6139f) | Jan 17, 2022 |
| Jumper        | EZbook                      | [6c949f1929](https://linux-hardware.org/?probe=6c949f1929) | Jan 17, 2022 |
| HP            | ProBook 650 G1              | [8d78cc6770](https://linux-hardware.org/?probe=8d78cc6770) | Jan 16, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [a61f1b9d56](https://linux-hardware.org/?probe=a61f1b9d56) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [0c41cd2cd0](https://linux-hardware.org/?probe=0c41cd2cd0) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [750744f996](https://linux-hardware.org/?probe=750744f996) | Jan 16, 2022 |
| Acer          | Swift SF114-34              | [2098bc3881](https://linux-hardware.org/?probe=2098bc3881) | Jan 16, 2022 |
| HP            | ProBook 650 G1              | [829a2b8221](https://linux-hardware.org/?probe=829a2b8221) | Jan 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [779202413e](https://linux-hardware.org/?probe=779202413e) | Jan 15, 2022 |
| Dell          | Latitude 5480               | [6e363cb43c](https://linux-hardware.org/?probe=6e363cb43c) | Jan 15, 2022 |
| HP            | 15                          | [65d1bd3651](https://linux-hardware.org/?probe=65d1bd3651) | Jan 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [350fb6b638](https://linux-hardware.org/?probe=350fb6b638) | Jan 14, 2022 |
| Dell          | XPS 13 9310                 | [f695de13bf](https://linux-hardware.org/?probe=f695de13bf) | Jan 14, 2022 |
| Dell          | Inspiron M5010              | [21dddfe6a8](https://linux-hardware.org/?probe=21dddfe6a8) | Jan 14, 2022 |
| Apple         | MacBookPro11,3              | [0fbef723d5](https://linux-hardware.org/?probe=0fbef723d5) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b2ac4f1622](https://linux-hardware.org/?probe=b2ac4f1622) | Jan 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [ee8a872afd](https://linux-hardware.org/?probe=ee8a872afd) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS2CH0... | [7f440733c2](https://linux-hardware.org/?probe=7f440733c2) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | [e9f23e9f5f](https://linux-hardware.org/?probe=e9f23e9f5f) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | [85d81f357a](https://linux-hardware.org/?probe=85d81f357a) | Jan 13, 2022 |
| Lenovo        | ThinkPad T430u 3351CTO      | [41f9777fcf](https://linux-hardware.org/?probe=41f9777fcf) | Jan 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [45d63385d2](https://linux-hardware.org/?probe=45d63385d2) | Jan 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| Dell          | XPS 13 7390                 | [10dea3ac81](https://linux-hardware.org/?probe=10dea3ac81) | Jan 11, 2022 |
| Lenovo        | IdeaPad Y470 20090          | [29ff376953](https://linux-hardware.org/?probe=29ff376953) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [34bf588c0b](https://linux-hardware.org/?probe=34bf588c0b) | Jan 11, 2022 |
| Dell          | Venue 10 Pro 5055           | [22d084e747](https://linux-hardware.org/?probe=22d084e747) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [63c5a7136b](https://linux-hardware.org/?probe=63c5a7136b) | Jan 11, 2022 |
| HP            | EliteBook 820 G1            | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| Lenovo        | ThinkPad T530 239265U       | [5aba32fde1](https://linux-hardware.org/?probe=5aba32fde1) | Jan 11, 2022 |
| Toshiba       | Satellite L855              | [5668d7e463](https://linux-hardware.org/?probe=5668d7e463) | Jan 10, 2022 |
| Toshiba       | Satellite L855              | [f14ba2d184](https://linux-hardware.org/?probe=f14ba2d184) | Jan 10, 2022 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | [b6b9155c53](https://linux-hardware.org/?probe=b6b9155c53) | Jan 10, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [62bf8bc805](https://linux-hardware.org/?probe=62bf8bc805) | Jan 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [72db511d09](https://linux-hardware.org/?probe=72db511d09) | Jan 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [2fa4c0880f](https://linux-hardware.org/?probe=2fa4c0880f) | Jan 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [6b6c84515a](https://linux-hardware.org/?probe=6b6c84515a) | Jan 09, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [b9812a839e](https://linux-hardware.org/?probe=b9812a839e) | Jan 09, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [dc436bb38c](https://linux-hardware.org/?probe=dc436bb38c) | Jan 08, 2022 |
| Dell          | XPS 13 9310                 | [e0dfa537f4](https://linux-hardware.org/?probe=e0dfa537f4) | Jan 08, 2022 |
| Notebook      | P15SM                       | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Dell          | Precision 3551              | [73d2d759ba](https://linux-hardware.org/?probe=73d2d759ba) | Jan 07, 2022 |
| Dell          | XPS 13 9310                 | [aa1ce4d9ca](https://linux-hardware.org/?probe=aa1ce4d9ca) | Jan 07, 2022 |
| Dell          | Precision 5510              | [7a763a42bb](https://linux-hardware.org/?probe=7a763a42bb) | Jan 07, 2022 |
| Toshiba       | Satellite L755              | [df6cc34c45](https://linux-hardware.org/?probe=df6cc34c45) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | [a37ac164fb](https://linux-hardware.org/?probe=a37ac164fb) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | [51930e8d89](https://linux-hardware.org/?probe=51930e8d89) | Jan 06, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6c5e2e7851](https://linux-hardware.org/?probe=6c5e2e7851) | Jan 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cafe68988e](https://linux-hardware.org/?probe=cafe68988e) | Jan 06, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [8d8227634a](https://linux-hardware.org/?probe=8d8227634a) | Jan 06, 2022 |
| Panasonic     | CF-195FYCALM                | [19ad0002e5](https://linux-hardware.org/?probe=19ad0002e5) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| Samsung       | 550XDA                      | [1bdf544285](https://linux-hardware.org/?probe=1bdf544285) | Jan 05, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Dell          | Latitude E6520              | [f9c32b0bee](https://linux-hardware.org/?probe=f9c32b0bee) | Jan 05, 2022 |
| Dell          | Latitude E7440              | [c8811522dd](https://linux-hardware.org/?probe=c8811522dd) | Jan 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [270443c029](https://linux-hardware.org/?probe=270443c029) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | [b97121f86e](https://linux-hardware.org/?probe=b97121f86e) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | [9fa953475a](https://linux-hardware.org/?probe=9fa953475a) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8d492fa1d4](https://linux-hardware.org/?probe=8d492fa1d4) | Jan 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [56a85d54e4](https://linux-hardware.org/?probe=56a85d54e4) | Jan 04, 2022 |
| Dell          | Latitude E5550              | [8956b15ec8](https://linux-hardware.org/?probe=8956b15ec8) | Jan 04, 2022 |
| Acer          | Swift SF114-34              | [3d15bf4d48](https://linux-hardware.org/?probe=3d15bf4d48) | Jan 04, 2022 |
| Acer          | Extensa 2540                | [c3587d4c57](https://linux-hardware.org/?probe=c3587d4c57) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [9ac42b2131](https://linux-hardware.org/?probe=9ac42b2131) | Jan 04, 2022 |
| Acer          | Extensa 2540                | [0a39d6fe8c](https://linux-hardware.org/?probe=0a39d6fe8c) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [e8bc9392ff](https://linux-hardware.org/?probe=e8bc9392ff) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| Dell          | Inspiron 7591               | [4044cf11d2](https://linux-hardware.org/?probe=4044cf11d2) | Jan 04, 2022 |
| Dell          | Inspiron 5402               | [3cae008c9d](https://linux-hardware.org/?probe=3cae008c9d) | Jan 04, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [d5e7352413](https://linux-hardware.org/?probe=d5e7352413) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [8cd52a2f8f](https://linux-hardware.org/?probe=8cd52a2f8f) | Jan 03, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [3953d7ae46](https://linux-hardware.org/?probe=3953d7ae46) | Jan 03, 2022 |
| Dell          | XPS 15 7590                 | [b661a2cdf0](https://linux-hardware.org/?probe=b661a2cdf0) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [60514a96e4](https://linux-hardware.org/?probe=60514a96e4) | Jan 02, 2022 |
| ASUSTek       | X542URR                     | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [0692c6e121](https://linux-hardware.org/?probe=0692c6e121) | Jan 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Dell          | Latitude E5570              | [34af93663b](https://linux-hardware.org/?probe=34af93663b) | Dec 31, 2021 |
| Google        | Coral                       | [23a0352176](https://linux-hardware.org/?probe=23a0352176) | Dec 31, 2021 |
| ASUSTek       | TP300LD                     | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Dell          | XPS 13 9380                 | [cd66e486be](https://linux-hardware.org/?probe=cd66e486be) | Dec 31, 2021 |
| Apple         | MacBookPro8,2               | [298d5a0323](https://linux-hardware.org/?probe=298d5a0323) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | [c6dbec8e70](https://linux-hardware.org/?probe=c6dbec8e70) | Dec 31, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [c1eeaec01b](https://linux-hardware.org/?probe=c1eeaec01b) | Dec 30, 2021 |
| Google        | Chell                       | [9a2a4a03ed](https://linux-hardware.org/?probe=9a2a4a03ed) | Dec 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [bfd79da0e0](https://linux-hardware.org/?probe=bfd79da0e0) | Dec 30, 2021 |
| Dell          | Inspiron 3521               | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | [c3497fe5bd](https://linux-hardware.org/?probe=c3497fe5bd) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [c539559392](https://linux-hardware.org/?probe=c539559392) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [9ba0058839](https://linux-hardware.org/?probe=9ba0058839) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [dbcf70aced](https://linux-hardware.org/?probe=dbcf70aced) | Dec 29, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [41b463b6c4](https://linux-hardware.org/?probe=41b463b6c4) | Dec 28, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [433a512192](https://linux-hardware.org/?probe=433a512192) | Dec 28, 2021 |
| Lenovo        | ThinkPad E480 20KN001QPB    | [0615d7a112](https://linux-hardware.org/?probe=0615d7a112) | Dec 28, 2021 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [bea75ed7d5](https://linux-hardware.org/?probe=bea75ed7d5) | Dec 27, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [cc15a65a54](https://linux-hardware.org/?probe=cc15a65a54) | Dec 27, 2021 |
| Toshiba       | Satellite L12-C-104         | [fae8f8e1f9](https://linux-hardware.org/?probe=fae8f8e1f9) | Dec 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [23460afe38](https://linux-hardware.org/?probe=23460afe38) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [707835b4ff](https://linux-hardware.org/?probe=707835b4ff) | Dec 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | [f255947b6f](https://linux-hardware.org/?probe=f255947b6f) | Dec 27, 2021 |
| Dell          | XPS 13 7390                 | [572bbe8d7b](https://linux-hardware.org/?probe=572bbe8d7b) | Dec 27, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [86651ee07a](https://linux-hardware.org/?probe=86651ee07a) | Dec 26, 2021 |
| Lenovo        | Ducati 5 82ES               | [61dd257cc7](https://linux-hardware.org/?probe=61dd257cc7) | Dec 26, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [56c0a83ab8](https://linux-hardware.org/?probe=56c0a83ab8) | Dec 26, 2021 |
| MSI           | Alpha 15 B5EEK              | [e076af5bf8](https://linux-hardware.org/?probe=e076af5bf8) | Dec 26, 2021 |
| HP            | 2000                        | [e3408eb743](https://linux-hardware.org/?probe=e3408eb743) | Dec 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1e8ce2ec6d](https://linux-hardware.org/?probe=1e8ce2ec6d) | Dec 25, 2021 |
| Dell          | Inspiron 5558               | [58e49e7f72](https://linux-hardware.org/?probe=58e49e7f72) | Dec 25, 2021 |
| Dell          | Latitude 7410               | [71a96bfc8f](https://linux-hardware.org/?probe=71a96bfc8f) | Dec 25, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [6fe369b6b7](https://linux-hardware.org/?probe=6fe369b6b7) | Dec 25, 2021 |
| Cube          | i18-L                       | [6770cf2a44](https://linux-hardware.org/?probe=6770cf2a44) | Dec 24, 2021 |
| Lenovo        | V470 439627U                | [7c44d560dc](https://linux-hardware.org/?probe=7c44d560dc) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [a02655b4b8](https://linux-hardware.org/?probe=a02655b4b8) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [6e08796257](https://linux-hardware.org/?probe=6e08796257) | Dec 24, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [44dd4eee41](https://linux-hardware.org/?probe=44dd4eee41) | Dec 24, 2021 |
| HP            | Laptop 14-dk1xxx            | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| LDLC          | Mercure MH                  | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [abba53c091](https://linux-hardware.org/?probe=abba53c091) | Dec 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1962ddfdb4](https://linux-hardware.org/?probe=1962ddfdb4) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| HP            | 250 G1                      | [da8e31b740](https://linux-hardware.org/?probe=da8e31b740) | Dec 23, 2021 |
| Dell          | Inspiron 5447               | [83331a9c7c](https://linux-hardware.org/?probe=83331a9c7c) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| Apple         | MacBookPro11,3              | [1975ee2fc0](https://linux-hardware.org/?probe=1975ee2fc0) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Apple         | MacBookPro7,1               | [5994dbd498](https://linux-hardware.org/?probe=5994dbd498) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Notebook      | NH5x_NH7xHP                 | [0408aca941](https://linux-hardware.org/?probe=0408aca941) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7fc27f5255](https://linux-hardware.org/?probe=7fc27f5255) | Dec 21, 2021 |
| Apple         | MacBookPro7,1               | [5f47284626](https://linux-hardware.org/?probe=5f47284626) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| HP            | Laptop 15s-eq2xxx           | [8cd9d762c9](https://linux-hardware.org/?probe=8cd9d762c9) | Dec 20, 2021 |
| HP            | Pavilion 15                 | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| Notebook      | N24_25JU                    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ddb3571ec6](https://linux-hardware.org/?probe=ddb3571ec6) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | [bb28c266ec](https://linux-hardware.org/?probe=bb28c266ec) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [d335e16395](https://linux-hardware.org/?probe=d335e16395) | Dec 19, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [9c38b95aa0](https://linux-hardware.org/?probe=9c38b95aa0) | Dec 19, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [e380536aac](https://linux-hardware.org/?probe=e380536aac) | Dec 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [87399b5e8b](https://linux-hardware.org/?probe=87399b5e8b) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [85e3feaeba](https://linux-hardware.org/?probe=85e3feaeba) | Dec 19, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| Acer          | Nitro AN515-53              | [a9affc8e28](https://linux-hardware.org/?probe=a9affc8e28) | Dec 18, 2021 |
| Dell          | Precision 5540              | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [cda7a2c35c](https://linux-hardware.org/?probe=cda7a2c35c) | Dec 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [6bf6c57117](https://linux-hardware.org/?probe=6bf6c57117) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e985e04d6d](https://linux-hardware.org/?probe=e985e04d6d) | Dec 17, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [6deb57beb2](https://linux-hardware.org/?probe=6deb57beb2) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| AVITA         | NS14A1US                    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [290b1d081b](https://linux-hardware.org/?probe=290b1d081b) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | [aba6548652](https://linux-hardware.org/?probe=aba6548652) | Dec 16, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [30a4a58c5d](https://linux-hardware.org/?probe=30a4a58c5d) | Dec 16, 2021 |
| Dell          | XPS 15 9500                 | [4d52a02213](https://linux-hardware.org/?probe=4d52a02213) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | [ff779fe08f](https://linux-hardware.org/?probe=ff779fe08f) | Dec 16, 2021 |
| MSI           | GL63 9SC                    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| HP            | Pavilion dv7                | [0e0f0e3c23](https://linux-hardware.org/?probe=0e0f0e3c23) | Dec 15, 2021 |
| Dell          | Latitude 5500               | [5b9479065e](https://linux-hardware.org/?probe=5b9479065e) | Dec 15, 2021 |
| Lenovo        | ThinkPad E14 20RA007TUE     | [3edd54970c](https://linux-hardware.org/?probe=3edd54970c) | Dec 15, 2021 |
| ASUSTek       | K43U                        | [d7df2cd94e](https://linux-hardware.org/?probe=d7df2cd94e) | Dec 15, 2021 |
| Acer          | Swift SF314-43              | [2cabe8184b](https://linux-hardware.org/?probe=2cabe8184b) | Dec 15, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4290797f32](https://linux-hardware.org/?probe=4290797f32) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [fb79be9e00](https://linux-hardware.org/?probe=fb79be9e00) | Dec 14, 2021 |
| Dell          | Inspiron 15 5510            | [dd29feeb10](https://linux-hardware.org/?probe=dd29feeb10) | Dec 14, 2021 |
| Dell          | Latitude 7300               | [23f38f8a7d](https://linux-hardware.org/?probe=23f38f8a7d) | Dec 14, 2021 |
| Acer          | Aspire A515-55              | [8d121836c9](https://linux-hardware.org/?probe=8d121836c9) | Dec 14, 2021 |
| Dell          | Latitude 7490               | [ae8a45bc5a](https://linux-hardware.org/?probe=ae8a45bc5a) | Dec 14, 2021 |
| Dell          | Inspiron 16 7610            | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Acer          | Swift SF314-43              | [fd53be96e6](https://linux-hardware.org/?probe=fd53be96e6) | Dec 13, 2021 |
| Notebook      | NH5xAx                      | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| Dell          | Vostro 5402                 | [2074bdb7a5](https://linux-hardware.org/?probe=2074bdb7a5) | Dec 13, 2021 |
| MSI           | Modern 14 B5M               | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| Avell High... | A70 LIV                     | [3930fc87b1](https://linux-hardware.org/?probe=3930fc87b1) | Dec 12, 2021 |
| Acer          | Aspire A315-31              | [24c8e29d95](https://linux-hardware.org/?probe=24c8e29d95) | Dec 12, 2021 |
| Dell          | Latitude 7290               | [8a2ecfe430](https://linux-hardware.org/?probe=8a2ecfe430) | Dec 12, 2021 |
| Acer          | Nitro AN515-45              | [5975d86599](https://linux-hardware.org/?probe=5975d86599) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1H60... | [ffb1c97626](https://linux-hardware.org/?probe=ffb1c97626) | Dec 12, 2021 |
| Dell          | Inspiron 5515               | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [54058ac7e2](https://linux-hardware.org/?probe=54058ac7e2) | Dec 11, 2021 |
| HP            | Pavilion Power Laptop 15... | [6d5c35bf9f](https://linux-hardware.org/?probe=6d5c35bf9f) | Dec 11, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [584be17bec](https://linux-hardware.org/?probe=584be17bec) | Dec 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4fba952635](https://linux-hardware.org/?probe=4fba952635) | Dec 11, 2021 |
| HP            | ZBook 15 G2                 | [d7faa88624](https://linux-hardware.org/?probe=d7faa88624) | Dec 11, 2021 |
| Dell          | Latitude 7300               | [2bb3c232b6](https://linux-hardware.org/?probe=2bb3c232b6) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f3d37d4574](https://linux-hardware.org/?probe=f3d37d4574) | Dec 10, 2021 |
| Dell          | Inspiron 13 5310            | [7a721d2c05](https://linux-hardware.org/?probe=7a721d2c05) | Dec 10, 2021 |
| Dell          | Vostro 3400                 | [bcb885e52b](https://linux-hardware.org/?probe=bcb885e52b) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [4fe4d7393e](https://linux-hardware.org/?probe=4fe4d7393e) | Dec 10, 2021 |
| Acer          | Swift SFX14-41G             | [a81ed5c974](https://linux-hardware.org/?probe=a81ed5c974) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [4ba265c070](https://linux-hardware.org/?probe=4ba265c070) | Dec 10, 2021 |
| Lenovo        | G570 20079                  | [439a97ec9b](https://linux-hardware.org/?probe=439a97ec9b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [195283a93a](https://linux-hardware.org/?probe=195283a93a) | Dec 09, 2021 |
| Dell          | XPS 13 9305                 | [60e57ae6dd](https://linux-hardware.org/?probe=60e57ae6dd) | Dec 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [73645a62d6](https://linux-hardware.org/?probe=73645a62d6) | Dec 09, 2021 |
| HP            | Laptop 15s-eq2xxx           | [b673a5f067](https://linux-hardware.org/?probe=b673a5f067) | Dec 08, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [3880c485fb](https://linux-hardware.org/?probe=3880c485fb) | Dec 08, 2021 |
| Apple         | MacBookPro12,1              | [fcfdb2cedc](https://linux-hardware.org/?probe=fcfdb2cedc) | Dec 08, 2021 |
| Sony          | SVE1711Z1RB                 | [adb25167ea](https://linux-hardware.org/?probe=adb25167ea) | Dec 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | [9c98446833](https://linux-hardware.org/?probe=9c98446833) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [ad406a6f63](https://linux-hardware.org/?probe=ad406a6f63) | Dec 07, 2021 |
| Notebook      | NH5xAx                      | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| HP            | 15 Notebook PC              | [0523a58e8a](https://linux-hardware.org/?probe=0523a58e8a) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Lenovo        | G570 20079                  | [a6722f2ff3](https://linux-hardware.org/?probe=a6722f2ff3) | Dec 07, 2021 |
| Sony          | SVE1713S1RW                 | [41775b7503](https://linux-hardware.org/?probe=41775b7503) | Dec 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [8b704c0d3f](https://linux-hardware.org/?probe=8b704c0d3f) | Dec 06, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [b5a282abf6](https://linux-hardware.org/?probe=b5a282abf6) | Dec 06, 2021 |
| Apple         | MacBookPro9,2               | [4fc7bc5515](https://linux-hardware.org/?probe=4fc7bc5515) | Dec 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [42fe75c227](https://linux-hardware.org/?probe=42fe75c227) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e18de7567f](https://linux-hardware.org/?probe=e18de7567f) | Dec 06, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [40640fd92f](https://linux-hardware.org/?probe=40640fd92f) | Dec 06, 2021 |
| Framework     | Laptop                      | [64dc54fbc6](https://linux-hardware.org/?probe=64dc54fbc6) | Dec 06, 2021 |
| Acer          | Nitro AN515-45              | [8641f9b078](https://linux-hardware.org/?probe=8641f9b078) | Dec 05, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [50d1714228](https://linux-hardware.org/?probe=50d1714228) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Dell          | Inspiron 5405               | [91806303e6](https://linux-hardware.org/?probe=91806303e6) | Dec 05, 2021 |
| Dell          | Latitude E6530              | [de5ad42b2f](https://linux-hardware.org/?probe=de5ad42b2f) | Dec 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [15e8e28073](https://linux-hardware.org/?probe=15e8e28073) | Dec 04, 2021 |
| Acer          | Aspire E5-571G              | [b006a547c8](https://linux-hardware.org/?probe=b006a547c8) | Dec 04, 2021 |
| HP            | ProBook 470 G5              | [1cfd3aadd8](https://linux-hardware.org/?probe=1cfd3aadd8) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [be3c6c3e84](https://linux-hardware.org/?probe=be3c6c3e84) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [23d42021b2](https://linux-hardware.org/?probe=23d42021b2) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [6239b4eda5](https://linux-hardware.org/?probe=6239b4eda5) | Dec 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f90f047538](https://linux-hardware.org/?probe=f90f047538) | Dec 03, 2021 |
| Toshiba       | Satellite C70-A-K2W         | [8e46f67032](https://linux-hardware.org/?probe=8e46f67032) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [775ec45ab8](https://linux-hardware.org/?probe=775ec45ab8) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [b783f0a79d](https://linux-hardware.org/?probe=b783f0a79d) | Dec 03, 2021 |
| Gigabyte      | AERO 15 KB                  | [a7d3041cd2](https://linux-hardware.org/?probe=a7d3041cd2) | Dec 03, 2021 |
| HP            | Laptop 15s-eq2xxx           | [f53047cd0d](https://linux-hardware.org/?probe=f53047cd0d) | Dec 02, 2021 |
| Notebook      | NH55RGQ                     | [4189e1f255](https://linux-hardware.org/?probe=4189e1f255) | Dec 02, 2021 |
| Lenovo        | V15-ADA 82C7                | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Lenovo        | ThinkPad L390 20NSS43600    | [e9aae12812](https://linux-hardware.org/?probe=e9aae12812) | Dec 02, 2021 |
| Acer          | Nitro AN515-55              | [d5c6c6edee](https://linux-hardware.org/?probe=d5c6c6edee) | Dec 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | [94b9d8b093](https://linux-hardware.org/?probe=94b9d8b093) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | [240ca54dfb](https://linux-hardware.org/?probe=240ca54dfb) | Dec 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8cebf41624](https://linux-hardware.org/?probe=8cebf41624) | Dec 01, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9b11575394](https://linux-hardware.org/?probe=9b11575394) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | [610709bb66](https://linux-hardware.org/?probe=610709bb66) | Nov 30, 2021 |
| Acer          | Aspire E5-571G              | [f940ae414d](https://linux-hardware.org/?probe=f940ae414d) | Nov 30, 2021 |
| Dell          | Inspiron 7460               | [0a6feb58e7](https://linux-hardware.org/?probe=0a6feb58e7) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [b2d55bd445](https://linux-hardware.org/?probe=b2d55bd445) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [23ae32af07](https://linux-hardware.org/?probe=23ae32af07) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [074ec973ae](https://linux-hardware.org/?probe=074ec973ae) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [80bbba47f6](https://linux-hardware.org/?probe=80bbba47f6) | Nov 29, 2021 |
| Acer          | Aspire E5-571G              | [95cb3fe8b3](https://linux-hardware.org/?probe=95cb3fe8b3) | Nov 29, 2021 |
| Acer          | Predator G9-793             | [b9dc27ddac](https://linux-hardware.org/?probe=b9dc27ddac) | Nov 29, 2021 |
| Dell          | G5 5590                     | [e569e56450](https://linux-hardware.org/?probe=e569e56450) | Nov 29, 2021 |
| HP            | Laptop 15s-fq2xxx           | [959af2b8dd](https://linux-hardware.org/?probe=959af2b8dd) | Nov 29, 2021 |
| Acer          | Swift SF113-31              | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Notebook      | NB50TL                      | [15a716161c](https://linux-hardware.org/?probe=15a716161c) | Nov 28, 2021 |
| HP            | ProBook 470 G5              | [b75e21b247](https://linux-hardware.org/?probe=b75e21b247) | Nov 28, 2021 |
| Dell          | Inspiron 5558               | [b003366a2c](https://linux-hardware.org/?probe=b003366a2c) | Nov 28, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [8e5c4cc27b](https://linux-hardware.org/?probe=8e5c4cc27b) | Nov 28, 2021 |
| Apple         | MacBookPro7,1               | [6a4ed949e9](https://linux-hardware.org/?probe=6a4ed949e9) | Nov 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [0852350348](https://linux-hardware.org/?probe=0852350348) | Nov 28, 2021 |
| Dell          | Latitude 7420               | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [eabdd46893](https://linux-hardware.org/?probe=eabdd46893) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| HP            | Laptop 15s-fq2xxx           | [d559f82ee3](https://linux-hardware.org/?probe=d559f82ee3) | Nov 28, 2021 |
| Dell          | XPS 13 7390                 | [783b49e383](https://linux-hardware.org/?probe=783b49e383) | Nov 28, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | [67f32be00d](https://linux-hardware.org/?probe=67f32be00d) | Nov 27, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [968f938b4e](https://linux-hardware.org/?probe=968f938b4e) | Nov 27, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | [ef8336f76a](https://linux-hardware.org/?probe=ef8336f76a) | Nov 26, 2021 |
| Dell          | Precision 5550              | [41caa6a4a0](https://linux-hardware.org/?probe=41caa6a4a0) | Nov 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| ASUSTek       | K54C                        | [2604de426e](https://linux-hardware.org/?probe=2604de426e) | Nov 26, 2021 |
| Acer          | AP714-51T                   | [3fe9bcf889](https://linux-hardware.org/?probe=3fe9bcf889) | Nov 26, 2021 |
| Acer          | AP714-51T                   | [406001fc85](https://linux-hardware.org/?probe=406001fc85) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c207f61d91](https://linux-hardware.org/?probe=c207f61d91) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [96c90ad6c9](https://linux-hardware.org/?probe=96c90ad6c9) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [039dbf659a](https://linux-hardware.org/?probe=039dbf659a) | Nov 26, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [a000027ce6](https://linux-hardware.org/?probe=a000027ce6) | Nov 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [366fe373c9](https://linux-hardware.org/?probe=366fe373c9) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [beff046f56](https://linux-hardware.org/?probe=beff046f56) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [2a96a2a7af](https://linux-hardware.org/?probe=2a96a2a7af) | Nov 25, 2021 |
| Sony          | VPCF131FM                   | [f0ba5e0db2](https://linux-hardware.org/?probe=f0ba5e0db2) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| Dell          | XPS 13 9300                 | [a91462bd5a](https://linux-hardware.org/?probe=a91462bd5a) | Nov 24, 2021 |
| HP            | EliteBook 735 G5            | [d80b574cb4](https://linux-hardware.org/?probe=d80b574cb4) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b6bfa4b827](https://linux-hardware.org/?probe=b6bfa4b827) | Nov 24, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [44bf6f6d6f](https://linux-hardware.org/?probe=44bf6f6d6f) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3c3fbf498a](https://linux-hardware.org/?probe=3c3fbf498a) | Nov 23, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [5be975dd37](https://linux-hardware.org/?probe=5be975dd37) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [d29d6c2f61](https://linux-hardware.org/?probe=d29d6c2f61) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [6e361a8715](https://linux-hardware.org/?probe=6e361a8715) | Nov 23, 2021 |
| Acer          | Nitro AN515-54              | [b58b567113](https://linux-hardware.org/?probe=b58b567113) | Nov 22, 2021 |
| Apple         | MacBookPro11,4              | [7b9225653f](https://linux-hardware.org/?probe=7b9225653f) | Nov 22, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [365b3888e6](https://linux-hardware.org/?probe=365b3888e6) | Nov 22, 2021 |
| Fujitsu       | LIFEBOOK U747               | [ece0600e5d](https://linux-hardware.org/?probe=ece0600e5d) | Nov 22, 2021 |
| Apple         | MacBookPro7,1               | [c686d7d85c](https://linux-hardware.org/?probe=c686d7d85c) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | [a20fe0f647](https://linux-hardware.org/?probe=a20fe0f647) | Nov 21, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | [f779165258](https://linux-hardware.org/?probe=f779165258) | Nov 21, 2021 |
| Dell          | Latitude E5570              | [8cf8db7a89](https://linux-hardware.org/?probe=8cf8db7a89) | Nov 21, 2021 |
| Google        | Relm                        | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| HP            | Pavilion 17                 | [2d69072cdf](https://linux-hardware.org/?probe=2d69072cdf) | Nov 20, 2021 |
| Dell          | Latitude 5490               | [cbe23836bf](https://linux-hardware.org/?probe=cbe23836bf) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [8dfec492a4](https://linux-hardware.org/?probe=8dfec492a4) | Nov 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [78341a1a16](https://linux-hardware.org/?probe=78341a1a16) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [31cebd4e96](https://linux-hardware.org/?probe=31cebd4e96) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [0be43eb710](https://linux-hardware.org/?probe=0be43eb710) | Nov 19, 2021 |
| Acer          | Swift SF514-51              | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [a524ba65b5](https://linux-hardware.org/?probe=a524ba65b5) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7e7b7d381e](https://linux-hardware.org/?probe=7e7b7d381e) | Nov 19, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [d0aea280e7](https://linux-hardware.org/?probe=d0aea280e7) | Nov 19, 2021 |
| Dell          | Inspiron 3593               | [0e670dc090](https://linux-hardware.org/?probe=0e670dc090) | Nov 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d7a5775f61](https://linux-hardware.org/?probe=d7a5775f61) | Nov 19, 2021 |
| Notebook      | NH55RGQ                     | [d111fd1549](https://linux-hardware.org/?probe=d111fd1549) | Nov 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [01a15306b9](https://linux-hardware.org/?probe=01a15306b9) | Nov 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| ASUSTek       | X750JN                      | [bb6f44b058](https://linux-hardware.org/?probe=bb6f44b058) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f5a721bf24](https://linux-hardware.org/?probe=f5a721bf24) | Nov 19, 2021 |
| Dell          | Precision 5510              | [1d46cced08](https://linux-hardware.org/?probe=1d46cced08) | Nov 19, 2021 |
| HP            | Laptop 14s-fq0xxx           | [f9b7bdfef8](https://linux-hardware.org/?probe=f9b7bdfef8) | Nov 19, 2021 |
| Dell          | Inspiron 7572               | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [dc150f9fba](https://linux-hardware.org/?probe=dc150f9fba) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| Acer          | Swift SF314-43              | [46c44d537a](https://linux-hardware.org/?probe=46c44d537a) | Nov 18, 2021 |
| HP            | Pavilion Notebook           | [01f7a4c33d](https://linux-hardware.org/?probe=01f7a4c33d) | Nov 18, 2021 |
| Acer          | Swift SF314-42              | [05020e1e61](https://linux-hardware.org/?probe=05020e1e61) | Nov 18, 2021 |
| Toshiba       | Satellite C855-12R          | [dbde83db50](https://linux-hardware.org/?probe=dbde83db50) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [427ee1a6de](https://linux-hardware.org/?probe=427ee1a6de) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [585419cd38](https://linux-hardware.org/?probe=585419cd38) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [9dff5423c9](https://linux-hardware.org/?probe=9dff5423c9) | Nov 17, 2021 |
| Dell          | Latitude E7270              | [70a4c30534](https://linux-hardware.org/?probe=70a4c30534) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| Toshiba       | Satellite C855-12R          | [eefe2dc8be](https://linux-hardware.org/?probe=eefe2dc8be) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| HP            | ENVY Laptop 15t-ep000       | [02c2ed5954](https://linux-hardware.org/?probe=02c2ed5954) | Nov 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | [c4763ca2a5](https://linux-hardware.org/?probe=c4763ca2a5) | Nov 16, 2021 |
| Acer          | Swift SF314-43              | [db85b885ae](https://linux-hardware.org/?probe=db85b885ae) | Nov 16, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6b1f5ce8b7](https://linux-hardware.org/?probe=6b1f5ce8b7) | Nov 16, 2021 |
| ASUSTek       | S551LN                      | [53b3fced16](https://linux-hardware.org/?probe=53b3fced16) | Nov 16, 2021 |
| Toshiba       | Satellite C855-12R          | [ccf125eb47](https://linux-hardware.org/?probe=ccf125eb47) | Nov 16, 2021 |
| MSI           | Modern 15 A11M              | [6398858488](https://linux-hardware.org/?probe=6398858488) | Nov 16, 2021 |
| Notebook      | NH55RGQ                     | [b3cb30c28d](https://linux-hardware.org/?probe=b3cb30c28d) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | [1119a0805e](https://linux-hardware.org/?probe=1119a0805e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [dbaa27643e](https://linux-hardware.org/?probe=dbaa27643e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [aad4a92e0e](https://linux-hardware.org/?probe=aad4a92e0e) | Nov 16, 2021 |
| Apple         | MacBookPro6,2               | [75e80e1ea8](https://linux-hardware.org/?probe=75e80e1ea8) | Nov 15, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [06f896ff98](https://linux-hardware.org/?probe=06f896ff98) | Nov 15, 2021 |
| Acer          | Aspire A715-71G             | [dd0bfcd823](https://linux-hardware.org/?probe=dd0bfcd823) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | [516e448510](https://linux-hardware.org/?probe=516e448510) | Nov 14, 2021 |
| MSI           | Modern 15 A11M              | [8b02ecc2b6](https://linux-hardware.org/?probe=8b02ecc2b6) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | [70b84217bd](https://linux-hardware.org/?probe=70b84217bd) | Nov 14, 2021 |
| Dell          | Precision 3541              | [a21fd45ac3](https://linux-hardware.org/?probe=a21fd45ac3) | Nov 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [54bb479f64](https://linux-hardware.org/?probe=54bb479f64) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | [d88aea84ef](https://linux-hardware.org/?probe=d88aea84ef) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| Apple         | MacBookPro6,2               | [a778aba19c](https://linux-hardware.org/?probe=a778aba19c) | Nov 14, 2021 |
| Dell          | Vostro 3460                 | [3a6a636384](https://linux-hardware.org/?probe=3a6a636384) | Nov 14, 2021 |
| Dell          | Latitude 5511               | [dc7c10f4e2](https://linux-hardware.org/?probe=dc7c10f4e2) | Nov 13, 2021 |
| Dell          | Latitude 5511               | [b0ca679bc5](https://linux-hardware.org/?probe=b0ca679bc5) | Nov 13, 2021 |
| HP            | ProBook 430 G1              | [68633b9bf5](https://linux-hardware.org/?probe=68633b9bf5) | Nov 13, 2021 |
| MSI           | Delta 15 A5EFK              | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [9e8eab1073](https://linux-hardware.org/?probe=9e8eab1073) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| Dell          | Inspiron 14-3467            | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| Apple         | MacBookPro10,2              | [5cbec68d6e](https://linux-hardware.org/?probe=5cbec68d6e) | Nov 13, 2021 |
| Positivo      | V142N_4G                    | [6afdf02b96](https://linux-hardware.org/?probe=6afdf02b96) | Nov 13, 2021 |
| Acer          | Swift SFX14-41G             | [04e988d138](https://linux-hardware.org/?probe=04e988d138) | Nov 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [85929a9a18](https://linux-hardware.org/?probe=85929a9a18) | Nov 12, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3bbda8b194](https://linux-hardware.org/?probe=3bbda8b194) | Nov 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Dell          | Precision 5510              | [80bbc48bce](https://linux-hardware.org/?probe=80bbc48bce) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| System76      | Oryx Pro                    | [77cf902290](https://linux-hardware.org/?probe=77cf902290) | Nov 11, 2021 |
| Apple         | MacBookPro9,2               | [61afe68685](https://linux-hardware.org/?probe=61afe68685) | Nov 11, 2021 |
| Dell          | Latitude E7440              | [e907f0bbf1](https://linux-hardware.org/?probe=e907f0bbf1) | Nov 11, 2021 |
| ASUSTek       | X202EV                      | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Dell          | XPS 13 7390                 | [f5ceaaf6fe](https://linux-hardware.org/?probe=f5ceaaf6fe) | Nov 11, 2021 |
| Apple         | MacBookAir6,1               | [588c351d40](https://linux-hardware.org/?probe=588c351d40) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ac9d7f968f](https://linux-hardware.org/?probe=ac9d7f968f) | Nov 10, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| Acer          | Nitro AN515-55              | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| ASUSTek       | T102HA                      | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| LG Electro... | 14Z90P-G.AR53A              | [a1fb8771db](https://linux-hardware.org/?probe=a1fb8771db) | Nov 10, 2021 |
| HP            | ProBook 430 G1              | [99ece77400](https://linux-hardware.org/?probe=99ece77400) | Nov 10, 2021 |
| HUAWEI        | KPL-W0X                     | [807e59f1e3](https://linux-hardware.org/?probe=807e59f1e3) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c8fb558bb7](https://linux-hardware.org/?probe=c8fb558bb7) | Nov 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [81605538eb](https://linux-hardware.org/?probe=81605538eb) | Nov 09, 2021 |
| MSI           | GL62M 7RDX                  | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| HUAWEI        | HLYL-WXX9                   | [1c63b3b4ce](https://linux-hardware.org/?probe=1c63b3b4ce) | Nov 09, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | [cb4e2271c0](https://linux-hardware.org/?probe=cb4e2271c0) | Nov 09, 2021 |
| Toshiba       | NB255                       | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| HP            | Notebook                    | [e254c5c947](https://linux-hardware.org/?probe=e254c5c947) | Nov 08, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | [5f5424fe84](https://linux-hardware.org/?probe=5f5424fe84) | Nov 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005GMH    | [146b572cd0](https://linux-hardware.org/?probe=146b572cd0) | Nov 08, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [0812e26e5a](https://linux-hardware.org/?probe=0812e26e5a) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | [8988b7e735](https://linux-hardware.org/?probe=8988b7e735) | Nov 08, 2021 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [b996ce8823](https://linux-hardware.org/?probe=b996ce8823) | Nov 07, 2021 |
| Lenovo        | Ducati 5 82ES               | [6269149643](https://linux-hardware.org/?probe=6269149643) | Nov 07, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [b4d29007be](https://linux-hardware.org/?probe=b4d29007be) | Nov 07, 2021 |
| Dell          | Latitude E7440              | [b2560457a5](https://linux-hardware.org/?probe=b2560457a5) | Nov 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [af116b7c35](https://linux-hardware.org/?probe=af116b7c35) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ced169a0b1](https://linux-hardware.org/?probe=ced169a0b1) | Nov 06, 2021 |
| Apple         | MacBookPro6,2               | [bde89fd503](https://linux-hardware.org/?probe=bde89fd503) | Nov 06, 2021 |
| HP            | ProBook 455 G1              | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| HP            | 250 G1                      | [1c52b861c7](https://linux-hardware.org/?probe=1c52b861c7) | Nov 06, 2021 |
| Lenovo        | ThinkPad E14 20RA001XIX     | [98d8c0fbdb](https://linux-hardware.org/?probe=98d8c0fbdb) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Notebook      | W65_W67RZ                   | [153b2a920d](https://linux-hardware.org/?probe=153b2a920d) | Nov 05, 2021 |
| HONOR         | NBD-WXX9                    | [1030fbbff6](https://linux-hardware.org/?probe=1030fbbff6) | Nov 05, 2021 |
| Unknown       | Unknown                     | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| HP            | ZBook 14u G5                | [ec192642ba](https://linux-hardware.org/?probe=ec192642ba) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8e06f2617d](https://linux-hardware.org/?probe=8e06f2617d) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1a2dda8941](https://linux-hardware.org/?probe=1a2dda8941) | Nov 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | [f29c3d7003](https://linux-hardware.org/?probe=f29c3d7003) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | [a795236afd](https://linux-hardware.org/?probe=a795236afd) | Nov 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [cd291857e2](https://linux-hardware.org/?probe=cd291857e2) | Nov 04, 2021 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [6ee78bd50a](https://linux-hardware.org/?probe=6ee78bd50a) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HN0013UK    | [8454cff91f](https://linux-hardware.org/?probe=8454cff91f) | Nov 04, 2021 |
| Dell          | Studio 1537                 | [d040c159b8](https://linux-hardware.org/?probe=d040c159b8) | Nov 04, 2021 |
| HP            | ProBook 430 G3              | [1d421060d7](https://linux-hardware.org/?probe=1d421060d7) | Nov 03, 2021 |
| Dell          | Precision 5510              | [eb702ce1e6](https://linux-hardware.org/?probe=eb702ce1e6) | Nov 03, 2021 |
| Dell          | Inspiron 5502               | [c68c3a5c3b](https://linux-hardware.org/?probe=c68c3a5c3b) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [10bd49d9c0](https://linux-hardware.org/?probe=10bd49d9c0) | Nov 03, 2021 |
| Dell          | Latitude 5590               | [5bc1ed5978](https://linux-hardware.org/?probe=5bc1ed5978) | Nov 03, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| HP            | Laptop 14-dq2xxx            | [f30e20e67b](https://linux-hardware.org/?probe=f30e20e67b) | Nov 03, 2021 |
| Dell          | XPS 15 9570                 | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| Lenovo        | ThinkPad X395 20NL0005US    | [b65f4d5ba3](https://linux-hardware.org/?probe=b65f4d5ba3) | Nov 03, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [8c19662b7e](https://linux-hardware.org/?probe=8c19662b7e) | Nov 03, 2021 |
| Toshiba       | TECRA Z50-A                 | [4aae9bdc03](https://linux-hardware.org/?probe=4aae9bdc03) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [54b32173dd](https://linux-hardware.org/?probe=54b32173dd) | Nov 03, 2021 |
| Dell          | XPS 13 7390                 | [40df244ae9](https://linux-hardware.org/?probe=40df244ae9) | Nov 02, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1310b8abf4](https://linux-hardware.org/?probe=1310b8abf4) | Oct 30, 2021 |
| Framework     | Laptop                      | [04db6c2222](https://linux-hardware.org/?probe=04db6c2222) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | [1be6c8dc87](https://linux-hardware.org/?probe=1be6c8dc87) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [e9a8fb1275](https://linux-hardware.org/?probe=e9a8fb1275) | Oct 27, 2021 |
| BESSTAR Te... | X400                        | [9cfc0bb300](https://linux-hardware.org/?probe=9cfc0bb300) | Oct 27, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [d3720f9145](https://linux-hardware.org/?probe=d3720f9145) | Oct 25, 2021 |
| Alienware     | Area-51m R2                 | [c3f94d8599](https://linux-hardware.org/?probe=c3f94d8599) | Oct 24, 2021 |
| HP            | ProBook 470 G5              | [725627d16b](https://linux-hardware.org/?probe=725627d16b) | Oct 23, 2021 |
| HP            | EliteBook 8560w             | [98bd384a42](https://linux-hardware.org/?probe=98bd384a42) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1c91bc1deb](https://linux-hardware.org/?probe=1c91bc1deb) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [9932dd3c21](https://linux-hardware.org/?probe=9932dd3c21) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| Acer          | Swift SF114-32              | [faa49a332b](https://linux-hardware.org/?probe=faa49a332b) | Oct 20, 2021 |
| HP            | EliteBook 820 G1            | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | [4dbc231901](https://linux-hardware.org/?probe=4dbc231901) | Oct 18, 2021 |
| GPU Compan... | GWTN156-1                   | [3cb0b09b48](https://linux-hardware.org/?probe=3cb0b09b48) | Oct 17, 2021 |
| HP            | Laptop 14-df0xxx            | [ac488ba246](https://linux-hardware.org/?probe=ac488ba246) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [362e1d3b99](https://linux-hardware.org/?probe=362e1d3b99) | Oct 15, 2021 |
| Dell          | Precision 5550              | [15a0f61f84](https://linux-hardware.org/?probe=15a0f61f84) | Oct 14, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4bb5ac9410](https://linux-hardware.org/?probe=4bb5ac9410) | Oct 12, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | [d4acf59f3b](https://linux-hardware.org/?probe=d4acf59f3b) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b4efb9e18](https://linux-hardware.org/?probe=5b4efb9e18) | Oct 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| HP            | ProBook 450 G3              | [2eeb05ff03](https://linux-hardware.org/?probe=2eeb05ff03) | Oct 09, 2021 |
| HP            | ENVY Laptop 15t-ep000       | [f9b69ffa3d](https://linux-hardware.org/?probe=f9b69ffa3d) | Oct 08, 2021 |
| Dell          | Inspiron 5505               | [d136f5d8f7](https://linux-hardware.org/?probe=d136f5d8f7) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c62915e0](https://linux-hardware.org/?probe=26c62915e0) | Oct 07, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | [146866c629](https://linux-hardware.org/?probe=146866c629) | Oct 06, 2021 |
| Apple         | MacBookPro5,5               | [db435ab99c](https://linux-hardware.org/?probe=db435ab99c) | Oct 03, 2021 |
| Lenovo        | G580 20150                  | [08adba2c54](https://linux-hardware.org/?probe=08adba2c54) | Oct 02, 2021 |
| HUAWEI        | EUL-WX9                     | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | G580 20150                  | [1dbb7762f6](https://linux-hardware.org/?probe=1dbb7762f6) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Dell          | Studio 1537                 | [aae900457c](https://linux-hardware.org/?probe=aae900457c) | Oct 01, 2021 |
| Framework     | Laptop                      | [95576917c8](https://linux-hardware.org/?probe=95576917c8) | Sep 29, 2021 |
| Notebook      | N2x0WU                      | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [82e0f76133](https://linux-hardware.org/?probe=82e0f76133) | Sep 25, 2021 |
| Lenovo        | ThinkPad E480 20KNS0MC00    | [ba847bc0c4](https://linux-hardware.org/?probe=ba847bc0c4) | Sep 23, 2021 |
| Apple         | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| HP            | G42                         | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
| HP            | ZBook 15u G5                | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| Dell          | XPS 17 9700                 | [ebac1c499f](https://linux-hardware.org/?probe=ebac1c499f) | Sep 15, 2021 |
| ASUSTek       | G71V                        | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [2b21ef140a](https://linux-hardware.org/?probe=2b21ef140a) | Sep 05, 2021 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
| Dell          | Latitude E5470              | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
| Dell          | XPS 15 9550                 | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer          | Aspire ES1-572              | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell          | XPS 15 9570                 | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell          | XPS 13 9380                 | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| Notebook      | P377SM-A                    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Notebook      | P377SM-A                    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook      | P377SM-A                    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Lenovo        | ThinkPad W541 20EF000UMN    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| 5.16.18-200.fc35.x86_64                | 93        | 9.81%   |
| 5.14.10-300.fc35.x86_64                | 61        | 6.43%   |
| 5.14.16-301.fc35.x86_64                | 45        | 4.75%   |
| 5.15.6-200.fc35.x86_64                 | 43        | 4.54%   |
| 5.16.16-200.fc35.x86_64                | 42        | 4.43%   |
| 5.15.12-200.fc35.x86_64                | 40        | 4.22%   |
| 5.16.12-200.fc35.x86_64                | 39        | 4.11%   |
| 5.14.18-300.fc35.x86_64                | 38        | 4.01%   |
| 5.16.9-200.fc35.x86_64                 | 31        | 3.27%   |
| 5.14.17-301.fc35.x86_64                | 28        | 2.95%   |
| 5.15.16-200.fc35.x86_64                | 27        | 2.85%   |
| 5.15.11-200.fc35.x86_64                | 25        | 2.64%   |
| 5.16.11-200.fc35.x86_64                | 24        | 2.53%   |
| 5.16.20-200.fc35.x86_64                | 23        | 2.43%   |
| 5.15.10-200.fc35.x86_64                | 22        | 2.32%   |
| 5.16.19-200.fc35.x86_64                | 21        | 2.22%   |
| 5.14.14-300.fc35.x86_64                | 21        | 2.22%   |
| 5.16.5-200.fc35.x86_64                 | 20        | 2.11%   |
| 5.17.4-200.fc35.x86_64                 | 18        | 1.9%    |
| 5.16.8-200.fc35.x86_64                 | 16        | 1.69%   |
| 5.15.14-200.fc35.x86_64                | 16        | 1.69%   |
| 5.15.13-200.fc35.x86_64                | 16        | 1.69%   |
| 5.15.8-200.fc35.x86_64                 | 15        | 1.58%   |
| 5.15.4-201.fc35.x86_64                 | 15        | 1.58%   |
| 5.15.5-200.fc35.x86_64                 | 14        | 1.48%   |
| 5.15.18-200.fc35.x86_64                | 14        | 1.48%   |
| 5.16.15-201.fc35.x86_64                | 13        | 1.37%   |
| 5.14.15-300.fc35.x86_64                | 13        | 1.37%   |
| 5.16.14-200.fc35.x86_64                | 12        | 1.27%   |
| 5.15.7-200.fc35.x86_64                 | 12        | 1.27%   |
| 5.16.7-200.fc35.x86_64                 | 10        | 1.05%   |
| 5.15.17-200.fc35.x86_64                | 9         | 0.95%   |
| 5.14.9-300.fc35.x86_64                 | 9         | 0.95%   |
| 5.15.15-200.fc35.x86_64                | 7         | 0.74%   |
| 5.14.0-60.fc35.x86_64                  | 7         | 0.74%   |
| 5.16.10-200.fc35.x86_64                | 6         | 0.63%   |
| 5.16.17-200.fc35.x86_64                | 5         | 0.53%   |
| 5.14.11-300.fc35.x86_64                | 5         | 0.53%   |
| 5.14.0-0.rc5.42.fc35.x86_64            | 5         | 0.53%   |
| 5.16.13-200.fc35.x86_64                | 4         | 0.42%   |
| 5.14.7-300.fc35.x86_64                 | 3         | 0.32%   |
| 5.14.12-300.fc35.x86_64                | 3         | 0.32%   |
| 5.16.12-250.vanilla.1.fc35.x86_64      | 2         | 0.21%   |
| 5.15.6-200.rog.fc35.x86_64             | 2         | 0.21%   |
| 5.14.3-300.fc35.x86_64                 | 2         | 0.21%   |
| 5.11.12-300.fc34.x86_64                | 2         | 0.21%   |
| 5.17.4-lqx1.0.fc35.x86_64              | 1         | 0.11%   |
| 5.17.3-xm1.0.fc35.x86_64               | 1         | 0.11%   |
| 5.17.3-302.fc36.x86_64                 | 1         | 0.11%   |
| 5.17.1-xm1.0.fc35.x86_64               | 1         | 0.11%   |
| 5.17.1-200.fc35.x86_64                 | 1         | 0.11%   |
| 5.17.0-0.rc5.102.vanilla.1.fc35.x86_64 | 1         | 0.11%   |
| 5.16.20m.wael-beta.r2                  | 1         | 0.11%   |
| 5.16.2-200.fc35.x86_64                 | 1         | 0.11%   |
| 5.16.17-250.vanilla.1.fc35.x86_64      | 1         | 0.11%   |
| 5.16.16-xm1.0e20220113.fc35.x86_64     | 1         | 0.11%   |
| 5.16.16-lqx2.0.fc35.x86_64             | 1         | 0.11%   |
| 5.16.13-xm1.0.fc35.x86_64              | 1         | 0.11%   |
| 5.16.12-200.mbp.fc33.x86_64            | 1         | 0.11%   |
| 5.16.1-xm1.0.fc35.x86_64               | 1         | 0.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.18 | 93        | 9.82%   |
| 5.14.10 | 61        | 6.44%   |
| 5.15.6  | 46        | 4.86%   |
| 5.14.16 | 46        | 4.86%   |
| 5.16.16 | 44        | 4.65%   |
| 5.16.12 | 42        | 4.44%   |
| 5.15.12 | 41        | 4.33%   |
| 5.14.18 | 38        | 4.01%   |
| 5.16.9  | 31        | 3.27%   |
| 5.14.17 | 28        | 2.96%   |
| 5.15.16 | 27        | 2.85%   |
| 5.15.11 | 26        | 2.75%   |
| 5.16.20 | 24        | 2.53%   |
| 5.16.11 | 24        | 2.53%   |
| 5.15.10 | 22        | 2.32%   |
| 5.14.14 | 22        | 2.32%   |
| 5.16.19 | 21        | 2.22%   |
| 5.16.5  | 20        | 2.11%   |
| 5.17.4  | 19        | 2.01%   |
| 5.15.13 | 18        | 1.9%    |
| 5.15.8  | 17        | 1.8%    |
| 5.16.8  | 16        | 1.69%   |
| 5.15.14 | 16        | 1.69%   |
| 5.15.5  | 15        | 1.58%   |
| 5.15.4  | 15        | 1.58%   |
| 5.14.0  | 15        | 1.58%   |
| 5.15.18 | 14        | 1.48%   |
| 5.14.15 | 14        | 1.48%   |
| 5.16.15 | 13        | 1.37%   |
| 5.16.14 | 12        | 1.27%   |
| 5.15.7  | 12        | 1.27%   |
| 5.16.7  | 10        | 1.06%   |
| 5.15.17 | 9         | 0.95%   |
| 5.14.9  | 9         | 0.95%   |
| 5.15.15 | 8         | 0.84%   |
| 5.16.17 | 6         | 0.63%   |
| 5.16.10 | 6         | 0.63%   |
| 5.16.13 | 5         | 0.53%   |
| 5.14.11 | 5         | 0.53%   |
| 5.14.7  | 3         | 0.32%   |
| 5.14.12 | 3         | 0.32%   |
| 5.17.3  | 2         | 0.21%   |
| 5.17.1  | 2         | 0.21%   |
| 5.16.0  | 2         | 0.21%   |
| 5.14.3  | 2         | 0.21%   |
| 5.13.19 | 2         | 0.21%   |
| 5.12.0  | 2         | 0.21%   |
| 5.11.12 | 2         | 0.21%   |
| 5.17.0  | 1         | 0.11%   |
| 5.16.2  | 1         | 0.11%   |
| 5.16.1  | 1         | 0.11%   |
| 5.15.32 | 1         | 0.11%   |
| 5.15.2  | 1         | 0.11%   |
| 5.15.19 | 1         | 0.11%   |
| 5.14.8  | 1         | 0.11%   |
| 5.14.6  | 1         | 0.11%   |
| 5.14.5  | 1         | 0.11%   |
| 5.14.1  | 1         | 0.11%   |
| 5.13.9  | 1         | 0.11%   |
| 5.13.4  | 1         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 354       | 38.86%  |
| 5.15    | 275       | 30.19%  |
| 5.14    | 245       | 26.89%  |
| 5.17    | 24        | 2.63%   |
| 5.13    | 5         | 0.55%   |
| 5.12    | 3         | 0.33%   |
| 5.10    | 3         | 0.33%   |
| 5.11    | 2         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 852       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 668       | 77.31%  |
| KDE5            | 85        | 9.84%   |
| Unknown         | 28        | 3.24%   |
| MATE            | 15        | 1.74%   |
| Cinnamon        | 14        | 1.62%   |
| X-Cinnamon      | 12        | 1.39%   |
| XFCE            | 10        | 1.16%   |
| i3              | 8         | 0.93%   |
| GNOME Classic   | 6         | 0.69%   |
| sway            | 4         | 0.46%   |
| LXDE            | 3         | 0.35%   |
| Pantheon        | 2         | 0.23%   |
| LXQt            | 2         | 0.23%   |
| KDE             | 2         | 0.23%   |
| fluxbox         | 2         | 0.23%   |
| openbox         | 1         | 0.12%   |
| GNOME Flashback | 1         | 0.12%   |
| bspwm           | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 580       | 66.97%  |
| X11     | 263       | 30.37%  |
| Unknown | 15        | 1.73%   |
| Tty     | 8         | 0.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 408       | 47.44%  |
| GDM     | 344       | 40%     |
| LightDM | 54        | 6.28%   |
| SDDM    | 51        | 5.93%   |
| LXDM    | 2         | 0.23%   |
| XDM     | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 479       | 55.96%  |
| en_GB   | 72        | 8.41%   |
| pt_BR   | 46        | 5.37%   |
| ru_RU   | 34        | 3.97%   |
| fr_FR   | 25        | 2.92%   |
| de_DE   | 25        | 2.92%   |
| it_IT   | 20        | 2.34%   |
| pl_PL   | 14        | 1.64%   |
| en_CA   | 13        | 1.52%   |
| en_AU   | 13        | 1.52%   |
| es_ES   | 12        | 1.4%    |
| es_CL   | 7         | 0.82%   |
| en_IN   | 7         | 0.82%   |
| es_MX   | 6         | 0.7%    |
| C       | 6         | 0.7%    |
| tr_TR   | 5         | 0.58%   |
| nl_NL   | 5         | 0.58%   |
| zh_CN   | 4         | 0.47%   |
| sv_SE   | 4         | 0.47%   |
| fr_CA   | 4         | 0.47%   |
| es_AR   | 4         | 0.47%   |
| en_IL   | 4         | 0.47%   |
| uk_UA   | 3         | 0.35%   |
| en_NZ   | 3         | 0.35%   |
| cs_CZ   | 3         | 0.35%   |
| Unknown | 3         | 0.35%   |
| sk_SK   | 2         | 0.23%   |
| pt_PT   | 2         | 0.23%   |
| nb_NO   | 2         | 0.23%   |
| fr_CH   | 2         | 0.23%   |
| fi_FI   | 2         | 0.23%   |
| es_GT   | 2         | 0.23%   |
| es_CO   | 2         | 0.23%   |
| en_ZA   | 2         | 0.23%   |
| en_DE   | 2         | 0.23%   |
| de_AT   | 2         | 0.23%   |
| szl_PL  | 1         | 0.12%   |
| ru_UA   | 1         | 0.12%   |
| ro_RO   | 1         | 0.12%   |
| nl_BE   | 1         | 0.12%   |
| lt_LT   | 1         | 0.12%   |
| hu_HU   | 1         | 0.12%   |
| ga_IE   | 1         | 0.12%   |
| fr_BE   | 1         | 0.12%   |
| es_PE   | 1         | 0.12%   |
| es_EC   | 1         | 0.12%   |
| en_IE   | 1         | 0.12%   |
| en_DK   | 1         | 0.12%   |
| de_CH   | 1         | 0.12%   |
| da_DK   | 1         | 0.12%   |
| ca_ES   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 720       | 83.92%  |
| BIOS | 138       | 16.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 636       | 74.3%   |
| Ext4    | 194       | 22.66%  |
| Xfs     | 21        | 2.45%   |
| Overlay | 4         | 0.47%   |
| Unknown | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 415       | 48.09%  |
| GPT     | 404       | 46.81%  |
| MBR     | 44        | 5.1%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 773       | 89.68%  |
| Yes       | 89        | 10.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 709       | 82.44%  |
| Yes       | 151       | 17.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo                   | 247       | 28.99%  |
| Dell                     | 152       | 17.84%  |
| Hewlett-Packard          | 124       | 14.55%  |
| ASUSTek Computer         | 74        | 8.69%   |
| Acer                     | 62        | 7.28%   |
| Apple                    | 36        | 4.23%   |
| HUAWEI                   | 21        | 2.46%   |
| MSI                      | 14        | 1.64%   |
| Toshiba                  | 11        | 1.29%   |
| Notebook                 | 11        | 1.29%   |
| Framework                | 10        | 1.17%   |
| Sony                     | 9         | 1.06%   |
| Samsung Electronics      | 8         | 0.94%   |
| Google                   | 7         | 0.82%   |
| Positivo                 | 6         | 0.7%    |
| System76                 | 5         | 0.59%   |
| TUXEDO                   | 4         | 0.47%   |
| Razer                    | 4         | 0.47%   |
| Timi                     | 3         | 0.35%   |
| Gigabyte Technology      | 3         | 0.35%   |
| Fujitsu                  | 3         | 0.35%   |
| Avell High Performance   | 3         | 0.35%   |
| Alienware                | 3         | 0.35%   |
| PC Specialist            | 2         | 0.23%   |
| Panasonic                | 2         | 0.23%   |
| HONOR                    | 2         | 0.23%   |
| Hampoo                   | 2         | 0.23%   |
| GPU Company              | 2         | 0.23%   |
| Fujitsu Siemens          | 2         | 0.23%   |
| Unknown                  | 2         | 0.23%   |
| SiComputer               | 1         | 0.12%   |
| SCHNEIDER                | 1         | 0.12%   |
| Positivo Bahia - VAIO    | 1         | 0.12%   |
| Medion                   | 1         | 0.12%   |
| Mediacom                 | 1         | 0.12%   |
| Login Informatica        | 1         | 0.12%   |
| LG Electronics           | 1         | 0.12%   |
| LDLC                     | 1         | 0.12%   |
| Jumper                   | 1         | 0.12%   |
| Intel                    | 1         | 0.12%   |
| Inspire Technology Group | 1         | 0.12%   |
| Getac                    | 1         | 0.12%   |
| eMachines                | 1         | 0.12%   |
| Digibras                 | 1         | 0.12%   |
| Cube                     | 1         | 0.12%   |
| Chuwi                    | 1         | 0.12%   |
| BESSTAR Tech             | 1         | 0.12%   |
| AVITA                    | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Framework Laptop                            | 10        | 1.17%   |
| HP Notebook                                 | 6         | 0.7%    |
| HUAWEI KLVL-WXX9                            | 5         | 0.59%   |
| HP Pavilion Notebook                        | 5         | 0.59%   |
| Dell XPS 13 7390                            | 5         | 0.59%   |
| Lenovo ThinkBook 15 G2 ITL 20VE             | 4         | 0.47%   |
| Dell XPS 13 9370                            | 4         | 0.47%   |
| Dell XPS 13 9310                            | 4         | 0.47%   |
| Dell XPS 13 9305                            | 4         | 0.47%   |
| Dell Latitude E7440                         | 4         | 0.47%   |
| Apple MacBookPro9,2                         | 4         | 0.47%   |
| Lenovo IdeaPad S145-15API 81V7              | 3         | 0.35%   |
| Lenovo IdeaPad 530S-14IKB 81EU              | 3         | 0.35%   |
| Lenovo IdeaPad 3 14ALC6 82KT                | 3         | 0.35%   |
| HUAWEI HVY-WXX9                             | 3         | 0.35%   |
| HP Pavilion Aero Laptop 13-be0xxx           | 3         | 0.35%   |
| HP EliteBook 840 G3                         | 3         | 0.35%   |
| Dell XPS 17 9700                            | 3         | 0.35%   |
| Dell XPS 15 9570                            | 3         | 0.35%   |
| Dell XPS 15 9550                            | 3         | 0.35%   |
| Dell XPS 13 9380                            | 3         | 0.35%   |
| Dell XPS 13 9360                            | 3         | 0.35%   |
| Dell Precision 5510                         | 3         | 0.35%   |
| Dell Latitude E6530                         | 3         | 0.35%   |
| Dell Latitude 7490                          | 3         | 0.35%   |
| Dell Inspiron N5110                         | 3         | 0.35%   |
| Dell Inspiron 5567                          | 3         | 0.35%   |
| Dell Inspiron 5458                          | 3         | 0.35%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM       | 3         | 0.35%   |
| ASUS ROG Strix G513QY_G513QY                | 3         | 0.35%   |
| Apple MacBookPro14,1                        | 3         | 0.35%   |
| Apple MacBookPro11,3                        | 3         | 0.35%   |
| Acer Swift SF314-42                         | 3         | 0.35%   |
| Unknown                                     | 3         | 0.35%   |
| System76 Pangolin                           | 2         | 0.23%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 2         | 0.23%   |
| MSI GE75 Raider 10SE                        | 2         | 0.23%   |
| MSI Delta 15 A5EFK                          | 2         | 0.23%   |
| Lenovo Yoga S740-14IIL 81RS                 | 2         | 0.23%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW  | 2         | 0.23%   |
| Lenovo ThinkPad P1 Gen 3 20TJS53A00         | 2         | 0.23%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW        | 2         | 0.23%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 0.23%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ            | 2         | 0.23%   |
| Lenovo Legion 5 15ARH05H 82B1               | 2         | 0.23%   |
| Lenovo Legion 5 15ARH05 82B5                | 2         | 0.23%   |
| Lenovo IdeaPad Flex-14API 81SS              | 2         | 0.23%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7            | 2         | 0.23%   |
| Lenovo IdeaPad 320-15ISK 80XH               | 2         | 0.23%   |
| Lenovo IdeaPad 3 14ITL6 82H7                | 2         | 0.23%   |
| Lenovo G500 20236                           | 2         | 0.23%   |
| HUAWEI NBLK-WAX9X                           | 2         | 0.23%   |
| HUAWEI KLVL-WXXW                            | 2         | 0.23%   |
| HUAWEI BOHK-WAX9X                           | 2         | 0.23%   |
| HONOR NBD-WXX9                              | 2         | 0.23%   |
| HP ProBook 650 G1                           | 2         | 0.23%   |
| HP ProBook 470 G5                           | 2         | 0.23%   |
| HP ProBook 450 G3                           | 2         | 0.23%   |
| HP ProBook 430 G5                           | 2         | 0.23%   |
| HP Pavilion Laptop 15-eh0xxx                | 2         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 143       | 16.78%  |
| Lenovo IdeaPad              | 55        | 6.46%   |
| Dell Latitude               | 47        | 5.52%   |
| Dell Inspiron               | 44        | 5.16%   |
| Dell XPS                    | 38        | 4.46%   |
| Acer Aspire                 | 35        | 4.11%   |
| HP Pavilion                 | 32        | 3.76%   |
| HP ProBook                  | 20        | 2.35%   |
| HP EliteBook                | 20        | 2.35%   |
| ASUS ROG                    | 17        | 2%      |
| HP Laptop                   | 15        | 1.76%   |
| Lenovo ThinkBook            | 12        | 1.41%   |
| Lenovo Legion               | 12        | 1.41%   |
| ASUS VivoBook               | 12        | 1.41%   |
| Acer Swift                  | 11        | 1.29%   |
| Framework Laptop            | 10        | 1.17%   |
| Dell Precision              | 10        | 1.17%   |
| ASUS ASUS                   | 10        | 1.17%   |
| Acer Nitro                  | 10        | 1.17%   |
| Toshiba Satellite           | 9         | 1.06%   |
| HP ZBook                    | 9         | 1.06%   |
| Dell Vostro                 | 8         | 0.94%   |
| Lenovo Yoga                 | 6         | 0.7%    |
| HP Notebook                 | 6         | 0.7%    |
| HP ENVY                     | 6         | 0.7%    |
| Apple MacBookPro11          | 6         | 0.7%    |
| HUAWEI KLVL-WXX9            | 5         | 0.59%   |
| ASUS ZenBook                | 5         | 0.59%   |
| HP OMEN                     | 4         | 0.47%   |
| Apple MacBookPro9           | 4         | 0.47%   |
| Razer Blade                 | 3         | 0.35%   |
| HUAWEI HVY-WXX9             | 3         | 0.35%   |
| Fujitsu LIFEBOOK            | 3         | 0.35%   |
| Apple MacBookPro14          | 3         | 0.35%   |
| Apple MacBookPro10          | 3         | 0.35%   |
| Unknown                     | 3         | 0.35%   |
| TUXEDO InfinityBook         | 2         | 0.23%   |
| System76 Pangolin           | 2         | 0.23%   |
| Samsung RV411               | 2         | 0.23%   |
| Notebook NH5x               | 2         | 0.23%   |
| MSI Modern                  | 2         | 0.23%   |
| MSI GE75                    | 2         | 0.23%   |
| MSI Delta                   | 2         | 0.23%   |
| Lenovo G500                 | 2         | 0.23%   |
| HUAWEI NBLK-WAX9X           | 2         | 0.23%   |
| HUAWEI KLVL-WXXW            | 2         | 0.23%   |
| HUAWEI BOHK-WAX9X           | 2         | 0.23%   |
| HONOR NBD-WXX9              | 2         | 0.23%   |
| HP Compaq                   | 2         | 0.23%   |
| HP 15                       | 2         | 0.23%   |
| Gigabyte AERO               | 2         | 0.23%   |
| Fujitsu Siemens ESPRIMO     | 2         | 0.23%   |
| Dell G5                     | 2         | 0.23%   |
| Avell High Performance B.ON | 2         | 0.23%   |
| ASUS TUF                    | 2         | 0.23%   |
| Apple MacBookPro8           | 2         | 0.23%   |
| Apple MacBookPro7           | 2         | 0.23%   |
| Apple MacBookPro6           | 2         | 0.23%   |
| Apple MacBookAir7           | 2         | 0.23%   |
| Apple MacBookAir6           | 2         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 163       | 19.13%  |
| 2021 | 138       | 16.2%   |
| 2019 | 109       | 12.79%  |
| 2018 | 82        | 9.62%   |
| 2017 | 62        | 7.28%   |
| 2016 | 58        | 6.81%   |
| 2013 | 48        | 5.63%   |
| 2015 | 41        | 4.81%   |
| 2014 | 38        | 4.46%   |
| 2011 | 37        | 4.34%   |
| 2012 | 34        | 3.99%   |
| 2010 | 16        | 1.88%   |
| 2008 | 11        | 1.29%   |
| 2009 | 7         | 0.82%   |
| 2022 | 6         | 0.7%    |
| 2007 | 2         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 852       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 690       | 80.42%  |
| Enabled  | 168       | 19.58%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 843       | 98.94%  |
| Yes  | 9         | 1.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 248       | 29.01%  |
| 16.01-24.0  | 213       | 24.91%  |
| 8.01-16.0   | 164       | 19.18%  |
| 32.01-64.0  | 100       | 11.7%   |
| 3.01-4.0    | 88        | 10.29%  |
| 64.01-256.0 | 18        | 2.11%   |
| 24.01-32.0  | 10        | 1.17%   |
| 1.01-2.0    | 10        | 1.17%   |
| 2.01-3.0    | 4         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 260       | 28.48%  |
| 4.01-8.0   | 254       | 27.82%  |
| 3.01-4.0   | 201       | 22.02%  |
| 1.01-2.0   | 119       | 13.03%  |
| 8.01-16.0  | 67        | 7.34%   |
| 16.01-24.0 | 6         | 0.66%   |
| 0.51-1.0   | 3         | 0.33%   |
| 32.01-64.0 | 2         | 0.22%   |
| 24.01-32.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 615       | 71.59%  |
| 2      | 211       | 24.56%  |
| 3      | 23        | 2.68%   |
| 0      | 4         | 0.47%   |
| 4      | 3         | 0.35%   |
| 5      | 2         | 0.23%   |
| 6      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 695       | 81.38%  |
| Yes       | 159       | 18.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 622       | 72.66%  |
| No        | 234       | 27.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 839       | 98.47%  |
| No        | 13        | 1.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 731       | 85.1%   |
| No        | 128       | 14.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 139       | 16.26%  |
| Brazil       | 74        | 8.65%   |
| Russia       | 62        | 7.25%   |
| Germany      | 45        | 5.26%   |
| Italy        | 33        | 3.86%   |
| Canada       | 32        | 3.74%   |
| UK           | 31        | 3.63%   |
| France       | 31        | 3.63%   |
| India        | 28        | 3.27%   |
| Poland       | 23        | 2.69%   |
| Spain        | 21        | 2.46%   |
| Netherlands  | 19        | 2.22%   |
| Sweden       | 17        | 1.99%   |
| Turkey       | 15        | 1.75%   |
| Austria      | 14        | 1.64%   |
| Czechia      | 13        | 1.52%   |
| Australia    | 13        | 1.52%   |
| Mexico       | 12        | 1.4%    |
| Indonesia    | 12        | 1.4%    |
| Norway       | 11        | 1.29%   |
| Ukraine      | 10        | 1.17%   |
| Hungary      | 10        | 1.17%   |
| Romania      | 9         | 1.05%   |
| Greece       | 9         | 1.05%   |
| Belgium      | 9         | 1.05%   |
| Switzerland  | 8         | 0.94%   |
| Portugal     | 8         | 0.94%   |
| Israel       | 8         | 0.94%   |
| Chile        | 8         | 0.94%   |
| Argentina    | 7         | 0.82%   |
| Finland      | 6         | 0.7%    |
| China        | 6         | 0.7%    |
| Belarus      | 6         | 0.7%    |
| South Africa | 5         | 0.58%   |
| New Zealand  | 5         | 0.58%   |
| Japan        | 5         | 0.58%   |
| Denmark      | 5         | 0.58%   |
| Croatia      | 5         | 0.58%   |
| Bulgaria     | 5         | 0.58%   |
| Saudi Arabia | 4         | 0.47%   |
| Philippines  | 4         | 0.47%   |
| Iran         | 4         | 0.47%   |
| Georgia      | 4         | 0.47%   |
| Egypt        | 3         | 0.35%   |
| Colombia     | 3         | 0.35%   |
| Venezuela    | 2         | 0.23%   |
| Tunisia      | 2         | 0.23%   |
| Taiwan       | 2         | 0.23%   |
| Serbia       | 2         | 0.23%   |
| Peru         | 2         | 0.23%   |
| Panama       | 2         | 0.23%   |
| Myanmar      | 2         | 0.23%   |
| Malaysia     | 2         | 0.23%   |
| Kenya        | 2         | 0.23%   |
| Kazakhstan   | 2         | 0.23%   |
| Ireland      | 2         | 0.23%   |
| Guatemala    | 2         | 0.23%   |
| Cyprus       | 2         | 0.23%   |
| Armenia      | 2         | 0.23%   |
| Algeria      | 2         | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 26        | 2.93%   |
| Sao Paulo         | 13        | 1.47%   |
| Istanbul          | 12        | 1.35%   |
| Vienna            | 10        | 1.13%   |
| Milan             | 9         | 1.02%   |
| Warsaw            | 7         | 0.79%   |
| St Petersburg     | 7         | 0.79%   |
| Montreal          | 7         | 0.79%   |
| Sydney            | 6         | 0.68%   |
| Munich            | 6         | 0.68%   |
| Yekaterinburg     | 5         | 0.56%   |
| Prague            | 5         | 0.56%   |
| Minsk             | 5         | 0.56%   |
| Madrid            | 5         | 0.56%   |
| Jakarta           | 5         | 0.56%   |
| Fortaleza         | 5         | 0.56%   |
| Coimbatore        | 5         | 0.56%   |
| Chicago           | 5         | 0.56%   |
| Berlin            | 5         | 0.56%   |
| Belo Horizonte    | 5         | 0.56%   |
| Athens            | 5         | 0.56%   |
| Amsterdam         | 5         | 0.56%   |
| Zagreb            | 4         | 0.45%   |
| Sofia             | 4         | 0.45%   |
| Rotterdam         | 4         | 0.45%   |
| Rome              | 4         | 0.45%   |
| Rio de Janeiro    | 4         | 0.45%   |
| Paris             | 4         | 0.45%   |
| Oslo              | 4         | 0.45%   |
| Mumbai            | 4         | 0.45%   |
| Mexico City       | 4         | 0.45%   |
| Kyiv              | 4         | 0.45%   |
| K'alak'i T'bilisi | 4         | 0.45%   |
| Helsinki          | 4         | 0.45%   |
| Frankfurt am Main | 4         | 0.45%   |
| Budapest          | 4         | 0.45%   |
| Bucharest         | 4         | 0.45%   |
| Zurich            | 3         | 0.34%   |
| WÃ¶rgl          | 3         | 0.34%   |
| Vancouver         | 3         | 0.34%   |
| Ufa               | 3         | 0.34%   |
| Seattle           | 3         | 0.34%   |
| Santiago          | 3         | 0.34%   |
| Portland          | 3         | 0.34%   |
| Odessa            | 3         | 0.34%   |
| Nuremberg         | 3         | 0.34%   |
| Novosibirsk       | 3         | 0.34%   |
| Nizhniy Novgorod  | 3         | 0.34%   |
| New Delhi         | 3         | 0.34%   |
| Lyon              | 3         | 0.34%   |
| Los Angeles       | 3         | 0.34%   |
| Lawrenceville     | 3         | 0.34%   |
| Krakow            | 3         | 0.34%   |
| Gothenburg        | 3         | 0.34%   |
| East Longmeadow   | 3         | 0.34%   |
| Calgary           | 3         | 0.34%   |
| Brno              | 3         | 0.34%   |
| Bengaluru         | 3         | 0.34%   |
| Yerevan           | 2         | 0.23%   |
| Yangon            | 2         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 225       | 303    | 20.91%  |
| WDC                            | 120       | 129    | 11.15%  |
| Toshiba                        | 78        | 81     | 7.25%   |
| SK Hynix                       | 72        | 87     | 6.69%   |
| SanDisk                        | 72        | 89     | 6.69%   |
| Seagate                        | 70        | 84     | 6.51%   |
| Unknown                        | 57        | 67     | 5.3%    |
| Kingston                       | 54        | 59     | 5.02%   |
| Intel                          | 47        | 61     | 4.37%   |
| Micron Technology              | 34        | 42     | 3.16%   |
| Crucial                        | 27        | 30     | 2.51%   |
| KIOXIA                         | 25        | 33     | 2.32%   |
| Apple                          | 20        | 22     | 1.86%   |
| A-DATA Technology              | 16        | 17     | 1.49%   |
| HGST                           | 15        | 16     | 1.39%   |
| Transcend                      | 10        | 11     | 0.93%   |
| Phison                         | 10        | 11     | 0.93%   |
| LITEON                         | 10        | 10     | 0.93%   |
| Silicon Motion                 | 7         | 7      | 0.65%   |
| Hitachi                        | 7         | 7      | 0.65%   |
| XPG                            | 5         | 6      | 0.46%   |
| Corsair                        | 5         | 5      | 0.46%   |
| China                          | 5         | 5      | 0.46%   |
| PLEXTOR                        | 4         | 5      | 0.37%   |
| Lexar                          | 4         | 5      | 0.37%   |
| ADATA Technology               | 4         | 4      | 0.37%   |
| Unknown                        | 4         | 5      | 0.37%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.28%   |
| UMIS                           | 3         | 3      | 0.28%   |
| Team                           | 3         | 4      | 0.28%   |
| PNY                            | 3         | 4      | 0.28%   |
| Patriot                        | 3         | 3      | 0.28%   |
| Mushkin                        | 3         | 3      | 0.28%   |
| YMTC                           | 2         | 2      | 0.19%   |
| SPCC                           | 2         | 2      | 0.19%   |
| Realtek Semiconductor          | 2         | 3      | 0.19%   |
| Ramsta                         | 2         | 3      | 0.19%   |
| Netac                          | 2         | 2      | 0.19%   |
| LITEONIT                       | 2         | 2      | 0.19%   |
| Lenovo                         | 2         | 2      | 0.19%   |
| HPE                            | 2         | 4      | 0.19%   |
| Hewlett-Packard                | 2         | 1      | 0.19%   |
| FORESEE                        | 2         | 2      | 0.19%   |
| Zozt                           | 1         | 1      | 0.09%   |
| WDC WDS                        | 1         | 1      | 0.09%   |
| Vaseky                         | 1         | 1      | 0.09%   |
| USB3.1                         | 1         | 1      | 0.09%   |
| TO Exter                       | 1         | 1      | 0.09%   |
| Teclast                        | 1         | 1      | 0.09%   |
| TCSUNBOW                       | 1         | 1      | 0.09%   |
| SSSTC                          | 1         | 1      | 0.09%   |
| SSK                            | 1         | 1      | 0.09%   |
| Solid State Storage Technology | 1         | 1      | 0.09%   |
| MX                             | 1         | 1      | 0.09%   |
| Mass                           | 1         | 1      | 0.09%   |
| LDLC                           | 1         | 1      | 0.09%   |
| LaCie                          | 1         | 2      | 0.09%   |
| KingSpec                       | 1         | 1      | 0.09%   |
| JMicron                        | 1         | 1      | 0.09%   |
| JetFlash                       | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB         | 29        | 2.58%   |
| SK Hynix NVMe SSD Drive 512GB        | 15        | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB       | 15        | 1.33%   |
| Sandisk NVMe SSD Drive 512GB         | 15        | 1.33%   |
| Samsung NVMe SSD Drive 256GB         | 13        | 1.16%   |
| Samsung NVMe SSD Drive 500GB         | 12        | 1.07%   |
| Kingston SA400S37480G 480GB SSD      | 12        | 1.07%   |
| Sandisk NVMe SSD Drive 256GB         | 11        | 0.98%   |
| Samsung NVMe SSD Drive 1TB           | 11        | 0.98%   |
| Kingston SA400S37240G 240GB SSD      | 10        | 0.89%   |
| Unknown MMC Card  64GB               | 9         | 0.8%    |
| Unknown MMC Card  32GB               | 9         | 0.8%    |
| SK Hynix NVMe SSD Drive 256GB        | 9         | 0.8%    |
| Toshiba NVMe SSD Drive 512GB         | 8         | 0.71%   |
| Toshiba MQ04ABF100 1TB               | 8         | 0.71%   |
| Sandisk NVMe SSD Drive 500GB         | 8         | 0.71%   |
| Samsung NVMe SSD Drive 1024GB        | 8         | 0.71%   |
| KIOXIA NVMe SSD Drive 512GB          | 8         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 7         | 0.62%   |
| Sandisk NVMe SSD Drive 1TB           | 7         | 0.62%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 7         | 0.62%   |
| Intel NVMe SSD Drive 512GB           | 7         | 0.62%   |
| HGST HTS721010A9E630 1TB             | 7         | 0.62%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 6         | 0.53%   |
| Seagate ST1000LM048-2E7172 1TB       | 6         | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB         | 6         | 0.53%   |
| Samsung SSD 850 EVO 250GB            | 6         | 0.53%   |
| Unknown MMC Card  128GB              | 5         | 0.44%   |
| Toshiba MQ01ABD100 1TB               | 5         | 0.44%   |
| SK Hynix NVMe SSD Drive 1024GB       | 5         | 0.44%   |
| SK Hynix BC711 NVMe 512GB            | 5         | 0.44%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 0.44%   |
| Sandisk NVMe SSD Drive 1024GB        | 5         | 0.44%   |
| Samsung SSD 980 PRO 500GB            | 5         | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB       | 5         | 0.44%   |
| Samsung NVMe SSD Drive 2TB           | 5         | 0.44%   |
| Phison 311CD0512GB                   | 5         | 0.44%   |
| Micron 2210_MTFDHBA512QFD 512GB      | 5         | 0.44%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 5         | 0.44%   |
| WDC WD10SPZX-21Z10T0 1TB             | 4         | 0.36%   |
| Unknown SD128  128GB                 | 4         | 0.36%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.36%   |
| Toshiba KXG6AZNV512G 512GB           | 4         | 0.36%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 4         | 0.36%   |
| SK Hynix PC401 NVMe 512GB            | 4         | 0.36%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 4         | 0.36%   |
| Seagate ST1000LM014-1EJ164 1TB       | 4         | 0.36%   |
| Seagate Expansion+ 2TB               | 4         | 0.36%   |
| Samsung SSD 980 1TB                  | 4         | 0.36%   |
| Samsung SSD 970 EVO 1TB              | 4         | 0.36%   |
| Samsung SSD 860 EVO 500GB            | 4         | 0.36%   |
| Samsung SSD 860 EVO 250GB            | 4         | 0.36%   |
| Samsung MZALQ512HBLU-00BL2 512GB     | 4         | 0.36%   |
| Micron NVMe SSD Drive 512GB          | 4         | 0.36%   |
| KIOXIA NVMe SSD Drive 256GB          | 4         | 0.36%   |
| Kingston SA400S37120G 120GB SSD      | 4         | 0.36%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.36%   |
| Crucial CT1000MX500SSD1 1TB          | 4         | 0.36%   |
| Unknown                              | 4         | 0.36%   |
| XPG NVMe SSD Drive 1024GB            | 3         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 69        | 83     | 36.32%  |
| WDC                 | 58        | 61     | 30.53%  |
| Toshiba             | 34        | 35     | 17.89%  |
| HGST                | 15        | 16     | 7.89%   |
| Hitachi             | 7         | 7      | 3.68%   |
| Unknown             | 3         | 3      | 1.58%   |
| Apple               | 2         | 2      | 1.05%   |
| Samsung Electronics | 1         | 1      | 0.53%   |
| LaCie               | 1         | 2      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 65        | 90     | 21.45%  |
| Kingston            | 40        | 44     | 13.2%   |
| Crucial             | 24        | 27     | 7.92%   |
| SanDisk             | 23        | 34     | 7.59%   |
| WDC                 | 16        | 18     | 5.28%   |
| Intel               | 16        | 18     | 5.28%   |
| Apple               | 13        | 13     | 4.29%   |
| A-DATA Technology   | 11        | 12     | 3.63%   |
| Micron Technology   | 10        | 12     | 3.3%    |
| Transcend           | 8         | 9      | 2.64%   |
| LITEON              | 8         | 8      | 2.64%   |
| SK Hynix            | 7         | 8      | 2.31%   |
| Toshiba             | 6         | 7      | 1.98%   |
| China               | 5         | 5      | 1.65%   |
| PNY                 | 3         | 4      | 0.99%   |
| PLEXTOR             | 3         | 4      | 0.99%   |
| Patriot             | 3         | 3      | 0.99%   |
| Mushkin             | 3         | 3      | 0.99%   |
| Team                | 2         | 3      | 0.66%   |
| SPCC                | 2         | 2      | 0.66%   |
| Ramsta              | 2         | 3      | 0.66%   |
| Netac               | 2         | 2      | 0.66%   |
| LITEONIT            | 2         | 2      | 0.66%   |
| Lexar               | 2         | 3      | 0.66%   |
| FORESEE             | 2         | 2      | 0.66%   |
| Corsair             | 2         | 2      | 0.66%   |
| Zozt                | 1         | 1      | 0.33%   |
| WDC WDS             | 1         | 1      | 0.33%   |
| Vaseky              | 1         | 1      | 0.33%   |
| Unknown             | 1         | 1      | 0.33%   |
| TO Exter            | 1         | 1      | 0.33%   |
| Teclast             | 1         | 1      | 0.33%   |
| TCSUNBOW            | 1         | 1      | 0.33%   |
| MX                  | 1         | 1      | 0.33%   |
| KingSpec            | 1         | 1      | 0.33%   |
| JMicron             | 1         | 1      | 0.33%   |
| HUSKY               | 1         | 1      | 0.33%   |
| HPE                 | 1         | 3      | 0.33%   |
| Hewlett-Packard     | 1         | 1      | 0.33%   |
| GOODRAM             | 1         | 1      | 0.33%   |
| Gigabyte Technology | 1         | 1      | 0.33%   |
| External            | 1         | 1      | 0.33%   |
| CT1000P2            | 1         | 1      | 0.33%   |
| BIWIN               | 1         | 1      | 0.33%   |
| ASMT                | 1         | 1      | 0.33%   |
| Apacer              | 1         | 1      | 0.33%   |
| ADATA SU            | 1         | 1      | 0.33%   |
| 1TB                 | 1         | 1      | 0.33%   |
| Unknown             | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 481       | 620    | 47.16%  |
| SSD     | 287       | 363    | 28.14%  |
| HDD     | 185       | 210    | 18.14%  |
| MMC     | 53        | 69     | 5.2%    |
| Unknown | 14        | 14     | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 481       | 620    | 49.23%  |
| SATA | 407       | 543    | 41.66%  |
| MMC  | 53        | 69     | 5.42%   |
| SAS  | 36        | 44     | 3.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 307       | 368    | 64.9%   |
| 0.51-1.0   | 139       | 168    | 29.39%  |
| 1.01-2.0   | 25        | 35     | 5.29%   |
| 3.01-4.0   | 2         | 2      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 185       | 21.54%  |
| 251-500        | 167       | 19.44%  |
| 1-20           | 138       | 16.07%  |
| 101-250        | 128       | 14.9%   |
| 1001-2000      | 90        | 10.48%  |
| Unknown        | 76        | 8.85%   |
| 51-100         | 33        | 3.84%   |
| More than 3000 | 20        | 2.33%   |
| 21-50          | 12        | 1.4%    |
| 2001-3000      | 10        | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 294       | 33.18%  |
| 21-50          | 151       | 17.04%  |
| 101-250        | 134       | 15.12%  |
| 51-100         | 98        | 11.06%  |
| Unknown        | 76        | 8.58%   |
| 251-500        | 67        | 7.56%   |
| 501-1000       | 44        | 4.97%   |
| 1001-2000      | 19        | 2.14%   |
| More than 3000 | 2         | 0.23%   |
| 2001-3000      | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 5      | 6.67%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1      | 3.33%   |
| WDC WD1600BEVT-24A23T0 160GB                        | 1         | 1      | 3.33%   |
| WDC WD1600BEVS-60RST0 160GB                         | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD050V 500GB                           | 1         | 1      | 3.33%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1         | 1      | 3.33%   |
| Teclast 360GB A850 SSD                              | 1         | 1      | 3.33%   |
| SK Hynix SC308 SATA 256GB SSD                       | 1         | 1      | 3.33%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 3.33%   |
| Samsung Electronics MZNLH256HAJD-000H1 256GB SSD    | 1         | 1      | 3.33%   |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD    | 1         | 1      | 3.33%   |
| PLEXTOR PX-256M8PeG 256GB                           | 1         | 1      | 3.33%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 2      | 3.33%   |
| LITEON CV3-CE256 256GB SSD                          | 1         | 1      | 3.33%   |
| Intel SSDSC2CT240A3 240GB                           | 1         | 1      | 3.33%   |
| Intel SSDSC2BF180A5L 180GB                          | 1         | 1      | 3.33%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 3.33%   |
| Hitachi HTS545025B9SA02 250GB                       | 1         | 1      | 3.33%   |
| Hitachi HTS543225L9A300 250GB                       | 1         | 1      | 3.33%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 3.33%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 3.33%   |
| Crucial CT240BX500SSD1 240GB                        | 1         | 1      | 3.33%   |
| Crucial CT1050MX300SSD1 1TB                         | 1         | 1      | 3.33%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 3.33%   |
| A-DATA Technology IM2S3138E-128GM-B 128GB SSD       | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 4      | 13.33%  |
| WDC                 | 3         | 3      | 10%     |
| Seagate             | 3         | 6      | 10%     |
| Samsung Electronics | 3         | 3      | 10%     |
| Hitachi             | 3         | 3      | 10%     |
| Crucial             | 3         | 3      | 10%     |
| SK Hynix            | 2         | 2      | 6.67%   |
| Intel               | 2         | 2      | 6.67%   |
| HGST                | 2         | 2      | 6.67%   |
| Teclast             | 1         | 1      | 3.33%   |
| PLEXTOR             | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 2      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 21.43%  |
| Toshiba | 3         | 3      | 21.43%  |
| Seagate | 3         | 6      | 21.43%  |
| Hitachi | 3         | 3      | 21.43%  |
| HGST    | 2         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 14        | 15     | 46.67%  |
| HDD  | 14        | 17     | 46.67%  |
| NVMe | 2         | 2      | 6.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1         | 1      | 100%    |

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
| Detected | 460       | 691    | 50.61%  |
| Works    | 418       | 550    | 45.98%  |
| Malfunc  | 30        | 34     | 3.3%    |
| Failed   | 1         | 1      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 485       | 45.03%  |
| Samsung Electronics              | 170       | 15.78%  |
| AMD                              | 101       | 9.38%   |
| Sandisk                          | 89        | 8.26%   |
| SK Hynix                         | 63        | 5.85%   |
| Toshiba America Info Systems     | 39        | 3.62%   |
| Micron Technology                | 24        | 2.23%   |
| KIOXIA                           | 23        | 2.14%   |
| Kingston Technology Company      | 14        | 1.3%    |
| Phison Electronics               | 12        | 1.11%   |
| Silicon Motion                   | 11        | 1.02%   |
| ADATA Technology                 | 11        | 1.02%   |
| Nvidia                           | 6         | 0.56%   |
| Union Memory (Shenzhen)          | 5         | 0.46%   |
| Apple                            | 4         | 0.37%   |
| Realtek Semiconductor            | 3         | 0.28%   |
| Micron/Crucial Technology        | 3         | 0.28%   |
| Lite-On Technology               | 3         | 0.28%   |
| Yangtze Memory Technologies      | 2         | 0.19%   |
| Solid State Storage Technology   | 2         | 0.19%   |
| Marvell Technology Group         | 2         | 0.19%   |
| Lenovo                           | 2         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| JMicron Technology               | 1         | 0.09%   |
| Beijing Starblaze Technology     | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 97        | 8.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 92        | 8.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 86        | 7.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 49        | 4.37%   |
| Samsung NVMe SSD Controller 980                                                  | 44        | 3.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 37        | 3.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 32        | 2.85%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 29        | 2.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 28        | 2.5%    |
| SK Hynix Gold P31 SSD                                                            | 27        | 2.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 27        | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 26        | 2.32%   |
| Micron Non-Volatile memory controller                                            | 24        | 2.14%   |
| KIOXIA Non-Volatile memory controller                                            | 23        | 2.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 22        | 1.96%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 20        | 1.78%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 20        | 1.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 20        | 1.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 19        | 1.69%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 17        | 1.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 17        | 1.52%   |
| Sandisk Non-Volatile memory controller                                           | 16        | 1.43%   |
| SK Hynix Non-Volatile memory controller                                          | 15        | 1.34%   |
| Intel Comet Lake SATA AHCI Controller                                            | 14        | 1.25%   |
| Intel SSD 660P Series                                                            | 13        | 1.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 11        | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 0.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 0.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 10        | 0.89%   |
| Intel Non-Volatile memory controller                                             | 9         | 0.8%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 9         | 0.8%    |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 8         | 0.71%   |
| SK Hynix BC511                                                                   | 8         | 0.71%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 8         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8         | 0.71%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 7         | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 7         | 0.62%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 7         | 0.62%   |
| Phison PS5013 E13 NVMe Controller                                                | 7         | 0.62%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.62%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 6         | 0.53%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 6         | 0.53%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 6         | 0.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 0.53%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 6         | 0.53%   |
| ADATA Non-Volatile memory controller                                             | 6         | 0.53%   |
| Sandisk PC SN520 NVMe SSD                                                        | 5         | 0.45%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 5         | 0.45%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 4         | 0.36%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 0.36%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.36%   |
| Samsung Electronics SATA controller                                              | 4         | 0.36%   |
| Samsung Apple PCIe SSD                                                           | 4         | 0.36%   |
| Phison E12 NVMe Controller                                                       | 4         | 0.36%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 0.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 0.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 0.36%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 0.27%   |
| Toshiba America Info Systems NVMe Controller                                     | 3         | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 519       | 48.06%  |
| NVMe | 479       | 44.35%  |
| RAID | 68        | 6.3%    |
| IDE  | 14        | 1.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 671       | 78.76%  |
| AMD    | 181       | 21.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 34        | 3.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 29        | 3.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 23        | 2.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 1.88%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 16        | 1.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 1.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 1.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 14        | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 1.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 1.41%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 1.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 1.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 11        | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 1.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 1.06%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 1.06%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 1.06%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 1.06%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 9         | 1.06%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 8         | 0.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.94%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 8         | 0.94%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 8         | 0.94%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 8         | 0.94%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 8         | 0.94%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 8         | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 0.82%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.82%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 6         | 0.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 6         | 0.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 6         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 0.7%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 6         | 0.7%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 0.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 0.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 0.7%    |
| Intel Core i9-9880H CPU @ 2.30GHz             | 5         | 0.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.59%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.59%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.59%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 0.59%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 5         | 0.59%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 5         | 0.59%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.59%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 5         | 0.59%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 4         | 0.47%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 4         | 0.47%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 0.47%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 4         | 0.47%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 257       | 30.16%  |
| Intel Core i5           | 172       | 20.19%  |
| Other                   | 100       | 11.74%  |
| Intel Core i3           | 60        | 7.04%   |
| AMD Ryzen 7             | 57        | 6.69%   |
| AMD Ryzen 5             | 55        | 6.46%   |
| Intel Celeron           | 23        | 2.7%    |
| Intel Core 2 Duo        | 16        | 1.88%   |
| AMD Ryzen 9             | 16        | 1.88%   |
| Intel Core i9           | 11        | 1.29%   |
| Intel Atom              | 10        | 1.17%   |
| AMD Ryzen 3             | 10        | 1.17%   |
| Intel Pentium           | 9         | 1.06%   |
| AMD Ryzen 7 PRO         | 9         | 1.06%   |
| Intel Pentium Silver    | 5         | 0.59%   |
| AMD Ryzen 5 PRO         | 5         | 0.59%   |
| AMD A6                  | 4         | 0.47%   |
| AMD A4                  | 4         | 0.47%   |
| AMD A10                 | 4         | 0.47%   |
| AMD Athlon              | 3         | 0.35%   |
| AMD A8                  | 3         | 0.35%   |
| Intel Pentium Dual-Core | 2         | 0.23%   |
| Intel Pentium Dual      | 2         | 0.23%   |
| Intel Core m3           | 2         | 0.23%   |
| AMD E2                  | 2         | 0.23%   |
| AMD E                   | 2         | 0.23%   |
| Intel Xeon              | 1         | 0.12%   |
| Intel Genuine           | 1         | 0.12%   |
| Intel Core m7           | 1         | 0.12%   |
| Intel Core m5           | 1         | 0.12%   |
| AMD Ryzen 3 PRO         | 1         | 0.12%   |
| AMD PRO A10             | 1         | 0.12%   |
| AMD E1                  | 1         | 0.12%   |
| AMD C-60                | 1         | 0.12%   |
| AMD Athlon II           | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 360       | 42.25%  |
| 2      | 302       | 35.45%  |
| 8      | 91        | 10.68%  |
| 6      | 91        | 10.68%  |
| 14     | 2         | 0.23%   |
| 12     | 2         | 0.23%   |
| 10     | 2         | 0.23%   |
| 1      | 2         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 852       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 727       | 85.33%  |
| 1      | 125       | 14.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 852       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 78        | 9.08%   |
| 0x806ec    | 61        | 7.1%    |
| Unknown    | 53        | 6.17%   |
| 0x306a9    | 49        | 5.7%    |
| 0x806ea    | 47        | 5.47%   |
| 0x806e9    | 40        | 4.66%   |
| 0x406e3    | 38        | 4.42%   |
| 0x40651    | 35        | 4.07%   |
| 0xa0652    | 33        | 3.84%   |
| 0x0a50000c | 31        | 3.61%   |
| 0x206a7    | 30        | 3.49%   |
| 0x906ea    | 29        | 3.38%   |
| 0x08600106 | 28        | 3.26%   |
| 0x306d4    | 22        | 2.56%   |
| 0x306c3    | 19        | 2.21%   |
| 0x08108109 | 19        | 2.21%   |
| 0x08600104 | 16        | 1.86%   |
| 0x706e5    | 14        | 1.63%   |
| 0x08608103 | 14        | 1.63%   |
| 0x906ed    | 13        | 1.51%   |
| 0x506e3    | 13        | 1.51%   |
| 0x08108102 | 12        | 1.4%    |
| 0x906e9    | 11        | 1.28%   |
| 0x1067a    | 11        | 1.28%   |
| 0x506c9    | 10        | 1.16%   |
| 0x20655    | 10        | 1.16%   |
| 0x806d1    | 8         | 0.93%   |
| 0x706a8    | 8         | 0.93%   |
| 0x08608102 | 8         | 0.93%   |
| 0x806eb    | 7         | 0.81%   |
| 0x406c4    | 7         | 0.81%   |
| 0x30678    | 7         | 0.81%   |
| 0x40661    | 5         | 0.58%   |
| 0x10676    | 5         | 0.58%   |
| 0x08600103 | 5         | 0.58%   |
| 0x06001119 | 5         | 0.58%   |
| 0x706a1    | 3         | 0.35%   |
| 0x6fd      | 3         | 0.35%   |
| 0x08701013 | 3         | 0.35%   |
| 0x0810100b | 3         | 0.35%   |
| 0x07030105 | 3         | 0.35%   |
| 0x0700010b | 3         | 0.35%   |
| 0x06006705 | 3         | 0.35%   |
| 0xa0660    | 2         | 0.23%   |
| 0xa0655    | 2         | 0.23%   |
| 0x906c0    | 2         | 0.23%   |
| 0x906a3    | 2         | 0.23%   |
| 0x806c2    | 2         | 0.23%   |
| 0x406c3    | 2         | 0.23%   |
| 0x20652    | 2         | 0.23%   |
| 0x0a50000b | 2         | 0.23%   |
| 0x0a404101 | 2         | 0.23%   |
| 0x08600102 | 2         | 0.23%   |
| 0x08101016 | 2         | 0.23%   |
| 0x07030106 | 2         | 0.23%   |
| 0x0600611a | 2         | 0.23%   |
| 0x05000101 | 2         | 0.23%   |
| 0x906eb    | 1         | 0.12%   |
| 0x6fa      | 1         | 0.12%   |
| 0x106ca    | 1         | 0.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 218       | 25.59%  |
| TigerLake        | 87        | 10.21%  |
| Haswell          | 64        | 7.51%   |
| Zen 2            | 58        | 6.81%   |
| Skylake          | 57        | 6.69%   |
| IvyBridge        | 51        | 5.99%   |
| CometLake        | 40        | 4.69%   |
| Zen 3            | 34        | 3.99%   |
| Zen+             | 33        | 3.87%   |
| SandyBridge      | 32        | 3.76%   |
| Unknown          | 26        | 3.05%   |
| IceLake          | 22        | 2.58%   |
| Broadwell        | 22        | 2.58%   |
| Silvermont       | 17        | 2%      |
| Penryn           | 16        | 1.88%   |
| Westmere         | 13        | 1.53%   |
| Goldmont plus    | 11        | 1.29%   |
| Goldmont         | 10        | 1.17%   |
| Zen              | 7         | 0.82%   |
| Puma             | 5         | 0.59%   |
| Piledriver       | 5         | 0.59%   |
| Excavator        | 5         | 0.59%   |
| Core             | 5         | 0.59%   |
| Jaguar           | 3         | 0.35%   |
| Bobcat           | 3         | 0.35%   |
| Tremont          | 2         | 0.23%   |
| K10 Llano        | 2         | 0.23%   |
| Alderlake Hybrid | 2         | 0.23%   |
| K10              | 1         | 0.12%   |
| Bonnell          | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 631       | 57%     |
| Nvidia                           | 262       | 23.67%  |
| AMD                              | 213       | 19.24%  |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 79        | 7.02%   |
| AMD Renoir                                                                               | 54        | 4.8%    |
| Intel UHD Graphics 620                                                                   | 49        | 4.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 46        | 4.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 3.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 3.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 3.29%   |
| Intel HD Graphics 620                                                                    | 35        | 3.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 34        | 3.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 3.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 33        | 2.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 2.84%   |
| AMD Cezanne                                                                              | 31        | 2.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 2.22%   |
| AMD Lucienne                                                                             | 23        | 2.04%   |
| Intel HD Graphics 5500                                                                   | 19        | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 17        | 1.51%   |
| Intel HD Graphics 530                                                                    | 13        | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 1.07%   |
| Intel HD Graphics 630                                                                    | 12        | 1.07%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 11        | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 10        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 0.89%   |
| Nvidia TU117M                                                                            | 9         | 0.8%    |
| Nvidia GP108M [GeForce MX250]                                                            | 9         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.8%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 0.71%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 0.71%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 0.62%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 0.62%   |
| Intel HD Graphics 500                                                                    | 7         | 0.62%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 6         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.53%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 6         | 0.53%   |
| Intel Tiger Lake UHD Graphics                                                            | 6         | 0.53%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.53%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 5         | 0.44%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 5         | 0.44%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 0.44%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.44%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 5         | 0.44%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 5         | 0.44%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 0.36%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 4         | 0.36%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 0.36%   |
| Intel HD Graphics 615                                                                    | 4         | 0.36%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 3         | 0.27%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 3         | 0.27%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 3         | 0.27%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 3         | 0.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 405       | 47.54%  |
| Intel + Nvidia | 196       | 23%     |
| 1 x AMD        | 141       | 16.55%  |
| 1 x Nvidia     | 36        | 4.23%   |
| AMD + Nvidia   | 30        | 3.52%   |
| Intel + AMD    | 26        | 3.05%   |
| 2 x AMD        | 15        | 1.76%   |
| Other          | 2         | 0.23%   |
| 1 x SiS        | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 722       | 84.15%  |
| Proprietary | 128       | 14.92%  |
| Unknown     | 8         | 0.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 541       | 62.91%  |
| 0.01-0.5   | 107       | 12.44%  |
| 1.01-2.0   | 105       | 12.21%  |
| 3.01-4.0   | 43        | 5%      |
| 0.51-1.0   | 34        | 3.95%   |
| 7.01-8.0   | 13        | 1.51%   |
| 5.01-6.0   | 9         | 1.05%   |
| 8.01-16.0  | 6         | 0.7%    |
| 2.01-3.0   | 2         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 172       | 16.51%  |
| BOE                     | 159       | 15.26%  |
| Chimei Innolux          | 158       | 15.16%  |
| LG Display              | 132       | 12.67%  |
| Samsung Electronics     | 71        | 6.81%   |
| Sharp                   | 55        | 5.28%   |
| Dell                    | 47        | 4.51%   |
| Apple                   | 35        | 3.36%   |
| Goldstar                | 28        | 2.69%   |
| Lenovo                  | 23        | 2.21%   |
| PANDA                   | 18        | 1.73%   |
| Philips                 | 14        | 1.34%   |
| CSO                     | 14        | 1.34%   |
| Hewlett-Packard         | 13        | 1.25%   |
| Acer                    | 13        | 1.25%   |
| InfoVision              | 12        | 1.15%   |
| AOC                     | 11        | 1.06%   |
| Chi Mei Optoelectronics | 10        | 0.96%   |
| BenQ                    | 10        | 0.96%   |
| Ancor Communications    | 7         | 0.67%   |
| TMX                     | 5         | 0.48%   |
| Iiyama                  | 4         | 0.38%   |
| ViewSonic               | 3         | 0.29%   |
| MSI                     | 3         | 0.29%   |
| InnoLux Display         | 3         | 0.29%   |
| ASUSTek Computer        | 3         | 0.29%   |
| Sony                    | 2         | 0.19%   |
| Panasonic               | 2         | 0.19%   |
| JRY                     | 2         | 0.19%   |
| Gigabyte Technology     | 2         | 0.19%   |
| Vizio                   | 1         | 0.1%    |
| TIANMA XM               | 1         | 0.1%    |
| Targa Visionary         | 1         | 0.1%    |
| Sceptre Tech            | 1         | 0.1%    |
| ONN                     | 1         | 0.1%    |
| JDI                     | 1         | 0.1%    |
| INX                     | 1         | 0.1%    |
| HUAWEI                  | 1         | 0.1%    |
| Hitachi                 | 1         | 0.1%    |
| CPT                     | 1         | 0.1%    |
| AGO                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 1.41%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 10        | 0.94%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 8         | 0.75%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 7         | 0.66%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 7         | 0.66%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 6         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 6         | 0.56%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 6         | 0.56%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 6         | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.56%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 5         | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.47%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 5         | 0.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 5         | 0.47%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 5         | 0.47%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                 | 5         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.47%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 5         | 0.47%   |
| BOE LCD Monitor BOE0853 1920x1080 344x194mm 15.5-inch                    | 5         | 0.47%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 5         | 0.47%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 5         | 0.47%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 4         | 0.38%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 4         | 0.38%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 4         | 0.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 4         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 4         | 0.38%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 4         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.38%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 4         | 0.38%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 4         | 0.38%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 4         | 0.38%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.38%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 4         | 0.38%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 3         | 0.28%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.28%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 0.28%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 3         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 3         | 0.28%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch             | 3         | 0.28%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch             | 3         | 0.28%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.28%   |
| LG Display LCD Monitor LGD028E 1366x768 310x174mm 14.0-inch              | 3         | 0.28%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.28%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                        | 3         | 0.28%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 3         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 501       | 52.24%  |
| 1366x768 (WXGA)    | 172       | 17.94%  |
| 3840x2160 (4K)     | 63        | 6.57%   |
| 2560x1440 (QHD)    | 46        | 4.8%    |
| 1600x900 (HD+)     | 26        | 2.71%   |
| 1920x1200 (WUXGA)  | 24        | 2.5%    |
| 1280x800 (WXGA)    | 16        | 1.67%   |
| 2880x1800          | 14        | 1.46%   |
| 1440x900 (WXGA+)   | 13        | 1.36%   |
| 2560x1600          | 12        | 1.25%   |
| 3440x1440          | 10        | 1.04%   |
| 2256x1504          | 10        | 1.04%   |
| 2560x1080          | 7         | 0.73%   |
| 2160x1440          | 7         | 0.73%   |
| 3840x2400          | 6         | 0.63%   |
| 3200x1800 (QHD+)   | 5         | 0.52%   |
| 1680x1050 (WSXGA+) | 5         | 0.52%   |
| 2240x1400          | 3         | 0.31%   |
| 1280x1024 (SXGA)   | 3         | 0.31%   |
| 3200x2000          | 2         | 0.21%   |
| 3072x1920          | 2         | 0.21%   |
| 3000x2000          | 2         | 0.21%   |
| 2880x1920          | 2         | 0.21%   |
| 2160x1350          | 2         | 0.21%   |
| 3840x2560          | 1         | 0.1%    |
| 3840x1600          | 1         | 0.1%    |
| 2736x1824          | 1         | 0.1%    |
| 1360x768           | 1         | 0.1%    |
| 1024x600           | 1         | 0.1%    |
| Unknown            | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 373       | 35.49%  |
| 13      | 205       | 19.51%  |
| 14      | 148       | 14.08%  |
| 27      | 51        | 4.85%   |
| 24      | 48        | 4.57%   |
| 17      | 44        | 4.19%   |
| 23      | 33        | 3.14%   |
| 12      | 30        | 2.85%   |
| 21      | 27        | 2.57%   |
| 34      | 15        | 1.43%   |
| 11      | 15        | 1.43%   |
| 16      | 12        | 1.14%   |
| 31      | 8         | 0.76%   |
| 40      | 5         | 0.48%   |
| 18      | 5         | 0.48%   |
| 19      | 4         | 0.38%   |
| 84      | 3         | 0.29%   |
| 22      | 3         | 0.29%   |
| 10      | 3         | 0.29%   |
| Unknown | 3         | 0.29%   |
| 35      | 2         | 0.19%   |
| 28      | 2         | 0.19%   |
| 26      | 2         | 0.19%   |
| 25      | 2         | 0.19%   |
| 20      | 2         | 0.19%   |
| 54      | 1         | 0.1%    |
| 43      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 37      | 1         | 0.1%    |
| 32      | 1         | 0.1%    |
| 29      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 623       | 59.85%  |
| 201-300     | 156       | 14.99%  |
| 501-600     | 121       | 11.62%  |
| 351-400     | 52        | 5%      |
| 401-500     | 38        | 3.65%   |
| 601-700     | 18        | 1.73%   |
| 701-800     | 16        | 1.54%   |
| 801-900     | 8         | 0.77%   |
| 1501-2000   | 3         | 0.29%   |
| Unknown     | 3         | 0.29%   |
| 901-1000    | 2         | 0.19%   |
| 1001-1500   | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 734       | 82.94%  |
| 16/10   | 103       | 11.64%  |
| 3/2     | 25        | 2.82%   |
| 21/9    | 18        | 2.03%   |
| 5/4     | 3         | 0.34%   |
| 4/3     | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 376       | 35.81%  |
| 81-90          | 271       | 25.81%  |
| 201-250        | 93        | 8.86%   |
| 71-80          | 84        | 8%      |
| 301-350        | 52        | 4.95%   |
| 121-130        | 43        | 4.1%    |
| 351-500        | 29        | 2.76%   |
| 61-70          | 28        | 2.67%   |
| 251-300        | 17        | 1.62%   |
| 51-60          | 15        | 1.43%   |
| 151-200        | 11        | 1.05%   |
| 111-120        | 9         | 0.86%   |
| 501-1000       | 8         | 0.76%   |
| More than 1000 | 4         | 0.38%   |
| 41-50          | 3         | 0.29%   |
| 141-150        | 3         | 0.29%   |
| Unknown        | 3         | 0.29%   |
| 131-140        | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 481       | 47.2%   |
| 101-120       | 202       | 19.82%  |
| 51-100        | 143       | 14.03%  |
| 161-240       | 132       | 12.95%  |
| More than 240 | 57        | 5.59%   |
| Unknown       | 3         | 0.29%   |
| 1-50          | 1         | 0.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 641       | 74.45%  |
| 2     | 178       | 20.67%  |
| 3     | 27        | 3.14%   |
| 0     | 15        | 1.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 509       | 38.94%  |
| Realtek Semiconductor             | 426       | 32.59%  |
| Qualcomm Atheros                  | 140       | 10.71%  |
| Broadcom                          | 61        | 4.67%   |
| MEDIATEK                          | 31        | 2.37%   |
| Lenovo                            | 19        | 1.45%   |
| Broadcom Limited                  | 15        | 1.15%   |
| Ralink                            | 11        | 0.84%   |
| ASIX Electronics                  | 10        | 0.77%   |
| Dell                              | 9         | 0.69%   |
| Sierra Wireless                   | 8         | 0.61%   |
| DisplayLink                       | 8         | 0.61%   |
| Marvell Technology Group          | 7         | 0.54%   |
| TP-Link                           | 6         | 0.46%   |
| Qualcomm                          | 6         | 0.46%   |
| Xiaomi                            | 5         | 0.38%   |
| Ralink Technology                 | 4         | 0.31%   |
| Nvidia                            | 4         | 0.31%   |
| Hewlett-Packard                   | 3         | 0.23%   |
| ASUSTek Computer                  | 3         | 0.23%   |
| OPPO Electronics                  | 2         | 0.15%   |
| Linksys                           | 2         | 0.15%   |
| Huawei Technologies               | 2         | 0.15%   |
| Fibocom                           | 2         | 0.15%   |
| Ericsson Business Mobile Networks | 2         | 0.15%   |
| Cypress Semiconductor             | 2         | 0.15%   |
| Spreadtrum Communications         | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.08%   |
| Shenzhen Goodix Technology        | 1         | 0.08%   |
| Samsung Electronics               | 1         | 0.08%   |
| Qualcomm Atheros Communications   | 1         | 0.08%   |
| NetGear                           | 1         | 0.08%   |
| Motorola PCS                      | 1         | 0.08%   |
| HMD Global                        | 1         | 0.08%   |
| D-Link                            | 1         | 0.08%   |
| Apple                             | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 264       | 16.83%  |
| Intel Wi-Fi 6 AX200                                               | 81        | 5.16%   |
| Intel Wi-Fi 6 AX201                                               | 58        | 3.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 55        | 3.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 53        | 3.38%   |
| Intel Wireless 8265 / 8275                                        | 50        | 3.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 36        | 2.29%   |
| Intel Wireless 7260                                               | 33        | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 32        | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 31        | 1.98%   |
| Intel Wireless 8260                                               | 31        | 1.98%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 30        | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 27        | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 26        | 1.66%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 24        | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 24        | 1.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 1.27%   |
| Intel Wireless 7265                                               | 20        | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 1.08%   |
| Intel Wireless 3165                                               | 16        | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 16        | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 14        | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 12        | 0.76%   |
| Intel Wireless-AC 9260                                            | 12        | 0.76%   |
| Intel Ethernet Connection (6) I219-V                              | 12        | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 11        | 0.7%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 11        | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 11        | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.7%    |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 11        | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 10        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9         | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                             | 7         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 7         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.38%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.38%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.38%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 6         | 0.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.38%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 6         | 0.38%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.38%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5         | 0.32%   |
| Realtek 802.11ac NIC                                              | 5         | 0.32%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 5         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 501       | 56.93%  |
| Qualcomm Atheros                | 127       | 14.43%  |
| Realtek Semiconductor           | 111       | 12.61%  |
| Broadcom                        | 51        | 5.8%    |
| MEDIATEK                        | 30        | 3.41%   |
| Broadcom Limited                | 12        | 1.36%   |
| Ralink                          | 11        | 1.25%   |
| Sierra Wireless                 | 8         | 0.91%   |
| Dell                            | 6         | 0.68%   |
| Qualcomm                        | 5         | 0.57%   |
| TP-Link                         | 4         | 0.45%   |
| Ralink Technology               | 4         | 0.45%   |
| ASUSTek Computer                | 3         | 0.34%   |
| Fibocom                         | 2         | 0.23%   |
| Qualcomm Atheros Communications | 1         | 0.11%   |
| NetGear                         | 1         | 0.11%   |
| Linksys                         | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |
| D-Link                          | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 81        | 9.18%   |
| Intel Wi-Fi 6 AX201                                            | 58        | 6.58%   |
| Intel Wireless 8265 / 8275                                     | 50        | 5.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 36        | 4.08%   |
| Intel Wireless 7260                                            | 33        | 3.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 32        | 3.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 31        | 3.51%   |
| Intel Wireless 8260                                            | 31        | 3.51%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 30        | 3.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 27        | 3.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 26        | 2.95%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 24        | 2.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 24        | 2.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 2.27%   |
| Intel Wireless 7265                                            | 20        | 2.27%   |
| Intel Wireless 3165                                            | 16        | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 15        | 1.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 14        | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 1.36%   |
| Intel Wireless-AC 9260                                         | 12        | 1.36%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 1.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 1.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 11        | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 1.13%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 10        | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 1.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 0.79%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 6         | 0.68%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 6         | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 0.57%   |
| Realtek 802.11ac NIC                                           | 5         | 0.57%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 5         | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.57%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 5         | 0.57%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.45%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 4         | 0.45%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.45%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 4         | 0.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 3         | 0.34%   |
| Intel Wireless 3160                                            | 3         | 0.34%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 0.34%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.34%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 0.34%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.34%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.23%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 2         | 0.23%   |
| Sierra Wireless EM7345 4G LTE                                  | 2         | 0.23%   |
| Sierra Wireless EM7305                                         | 2         | 0.23%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.23%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.23%   |
| MEDIATEK WLAN controller                                       | 2         | 0.23%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                  | 2         | 0.23%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter            | 2         | 0.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 378       | 57.19%  |
| Intel                            | 167       | 25.26%  |
| Qualcomm Atheros                 | 24        | 3.63%   |
| Broadcom                         | 21        | 3.18%   |
| Lenovo                           | 19        | 2.87%   |
| ASIX Electronics                 | 10        | 1.51%   |
| DisplayLink                      | 8         | 1.21%   |
| Marvell Technology Group         | 7         | 1.06%   |
| Xiaomi                           | 5         | 0.76%   |
| Nvidia                           | 4         | 0.61%   |
| Broadcom Limited                 | 3         | 0.45%   |
| TP-Link                          | 2         | 0.3%    |
| OPPO Electronics                 | 2         | 0.3%    |
| Cypress Semiconductor            | 2         | 0.3%    |
| Spreadtrum Communications        | 1         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |
| Samsung Electronics              | 1         | 0.15%   |
| Qualcomm                         | 1         | 0.15%   |
| Motorola PCS                     | 1         | 0.15%   |
| MediaTek                         | 1         | 0.15%   |
| Linksys                          | 1         | 0.15%   |
| HMD Global                       | 1         | 0.15%   |
| Apple                            | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 264       | 39%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 55        | 8.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 53        | 7.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 23        | 3.4%    |
| Intel Ethernet Connection (4) I219-LM                                          | 17        | 2.51%   |
| Intel Ethernet Connection I219-LM                                              | 13        | 1.92%   |
| Intel Ethernet Connection (6) I219-V                                           | 12        | 1.77%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 11        | 1.62%   |
| Intel Ethernet Connection I218-LM                                              | 11        | 1.62%   |
| Intel Ethernet Connection (4) I219-V                                           | 11        | 1.62%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 1.48%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 10        | 1.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 8         | 1.18%   |
| Intel Ethernet Connection (6) I219-LM                                          | 7         | 1.03%   |
| Intel Ethernet Connection (13) I219-V                                          | 7         | 1.03%   |
| Intel Ethernet Connection (10) I219-V                                          | 7         | 1.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 0.89%   |
| Intel Ethernet Connection I219-V                                               | 6         | 0.89%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6         | 0.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 0.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 5         | 0.74%   |
| Intel Ethernet Connection (11) I219-LM                                         | 5         | 0.74%   |
| DisplayLink Dell Universal Dock D6000                                          | 5         | 0.74%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 5         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 0.59%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.44%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 3         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.44%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.44%   |
| Lenovo USB-C Dock Ethernet                                                     | 3         | 0.44%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 0.44%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.3%    |
| OPPO SDM665-IDP _SN:18689828                                                   | 2         | 0.3%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.3%    |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.3%    |
| Intel Ethernet Connection I217-V                                               | 2         | 0.3%    |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.3%    |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.3%    |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.3%    |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.3%    |
| Cypress K38231_03                                                              | 2         | 0.3%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.3%    |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe                        | 2         | 0.3%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.15%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 0.15%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.15%   |
| Spreadtrum Unisoc Phone                                                        | 1         | 0.15%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.15%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.15%   |
| Qualcomm Mobile Router                                                         | 1         | 0.15%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 839       | 57.04%  |
| Ethernet | 622       | 42.28%  |
| Modem    | 9         | 0.61%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 772       | 70.76%  |
| Ethernet | 319       | 29.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 547       | 64.13%  |
| 1     | 282       | 33.06%  |
| 0     | 15        | 1.76%   |
| 3     | 9         | 1.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 651       | 75.43%  |
| Yes  | 212       | 24.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 431       | 58.48%  |
| Realtek Semiconductor           | 66        | 8.96%   |
| Qualcomm Atheros Communications | 57        | 7.73%   |
| Lite-On Technology              | 33        | 4.48%   |
| IMC Networks                    | 31        | 4.21%   |
| Apple                           | 30        | 4.07%   |
| Foxconn / Hon Hai               | 25        | 3.39%   |
| Broadcom                        | 19        | 2.58%   |
| Realtek                         | 14        | 1.9%    |
| Ralink                          | 10        | 1.36%   |
| Cambridge Silicon Radio         | 6         | 0.81%   |
| Dell                            | 4         | 0.54%   |
| ASUSTek Computer                | 4         | 0.54%   |
| MediaTek                        | 2         | 0.27%   |
| Hewlett-Packard                 | 2         | 0.27%   |
| Foxconn International           | 2         | 0.27%   |
| Alps Electric                   | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 141       | 19.13%  |
| Intel Bluetooth Device                                                              | 113       | 15.33%  |
| Intel AX200 Bluetooth                                                               | 79        | 10.72%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 55        | 7.46%   |
| Realtek Bluetooth Radio                                                             | 43        | 5.83%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 33        | 4.48%   |
| Lite-On Bluetooth Device                                                            | 18        | 2.44%   |
| Apple Bluetooth Host Controller                                                     | 16        | 2.17%   |
| IMC Networks Wireless_Device                                                        | 15        | 2.04%   |
| Realtek Bluetooth Radio                                                             | 14        | 1.9%    |
| Intel AX210 Bluetooth                                                               | 14        | 1.9%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 12        | 1.63%   |
| Apple Bluetooth USB Host Controller                                                 | 12        | 1.63%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 11        | 1.49%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 1.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 9         | 1.22%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 1.22%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 8         | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 1.09%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 0.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 0.81%   |
| Lite-On Wireless_Device                                                             | 6         | 0.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.54%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 0.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.54%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 3         | 0.41%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.41%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 0.41%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.27%   |
| MediaTek Wireless_Device                                                            | 2         | 0.27%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.27%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.27%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.27%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.27%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 2         | 0.27%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.27%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.27%   |
| ASUS ASUS USB-BT500                                                                 | 2         | 0.27%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.14%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.14%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.14%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.14%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.14%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.14%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.14%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.14%   |
| IMC Networks Bluetooth                                                              | 1         | 0.14%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.14%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.14%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.14%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.14%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.14%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.14%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.14%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 652       | 57.85%  |
| AMD                              | 193       | 17.13%  |
| Nvidia                           | 157       | 13.93%  |
| Lenovo                           | 18        | 1.6%    |
| C-Media Electronics              | 16        | 1.42%   |
| GN Netcom                        | 11        | 0.98%   |
| Realtek Semiconductor            | 10        | 0.89%   |
| SteelSeries ApS                  | 6         | 0.53%   |
| Plantronics                      | 4         | 0.35%   |
| Logitech                         | 4         | 0.35%   |
| Kingston Technology              | 4         | 0.35%   |
| JMTek                            | 4         | 0.35%   |
| Hewlett-Packard                  | 4         | 0.35%   |
| Texas Instruments                | 3         | 0.27%   |
| Creative Technology              | 3         | 0.27%   |
| XMOS                             | 2         | 0.18%   |
| Sony                             | 2         | 0.18%   |
| Sennheiser Communications        | 2         | 0.18%   |
| RODE Microphones                 | 2         | 0.18%   |
| Razer USA                        | 2         | 0.18%   |
| PreSonus Audio Electronics       | 2         | 0.18%   |
| Generalplus Technology           | 2         | 0.18%   |
| CMX Systems                      | 2         | 0.18%   |
| Apple                            | 2         | 0.18%   |
| Tenx Technology                  | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| SAVITECH                         | 1         | 0.09%   |
| Samson Technologies              | 1         | 0.09%   |
| Micronas                         | 1         | 0.09%   |
| Magic Control Technology         | 1         | 0.09%   |
| M-Audio                          | 1         | 0.09%   |
| GYROCOM C&C                      | 1         | 0.09%   |
| Fujitsu                          | 1         | 0.09%   |
| FIFINE Microphones               | 1         | 0.09%   |
| EDFIER                           | 1         | 0.09%   |
| Dell                             | 1         | 0.09%   |
| Corsair                          | 1         | 0.09%   |
| Cooler Master                    | 1         | 0.09%   |
| Conexant Systems                 | 1         | 0.09%   |
| BY EDIFIER                       | 1         | 0.09%   |
| Blue Microphones                 | 1         | 0.09%   |
| Barco Display Systems            | 1         | 0.09%   |
| Arturia                          | 1         | 0.09%   |
| A4Tech                           | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 145       | 10.64%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 133       | 9.76%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 94        | 6.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 87        | 6.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 54        | 3.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 43        | 3.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 38        | 2.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 38        | 2.79%   |
| Intel 8 Series HD Audio Controller                                                                | 38        | 2.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 37        | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 37        | 2.71%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 34        | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 29        | 2.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 27        | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 26        | 1.91%   |
| Nvidia Audio device                                                                               | 23        | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 22        | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 22        | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 18        | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 1.32%   |
| AMD FCH Azalia Controller                                                                         | 16        | 1.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15        | 1.1%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 1.03%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 12        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 12        | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 0.88%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 11        | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 0.81%   |
| Realtek Semiconductor USB Audio                                                                   | 10        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 9         | 0.66%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 8         | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 8         | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 0.51%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 7         | 0.51%   |
| Nvidia TU104 HD Audio Controller                                                                  | 6         | 0.44%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 6         | 0.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.37%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.37%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 0.37%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 0.37%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.29%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.29%   |
| JMTek USB PnP Audio Device                                                                        | 4         | 0.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.29%   |
| Hewlett-Packard USB Audio                                                                         | 4         | 0.29%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 3         | 0.22%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 3         | 0.22%   |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.22%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.22%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.22%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.22%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 3         | 0.22%   |
| Intel Crystal Well HD Audio Controller                                                            | 3         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 171       | 30.21%  |
| SK Hynix            | 115       | 20.32%  |
| Micron Technology   | 94        | 16.61%  |
| Kingston            | 44        | 7.77%   |
| Crucial             | 41        | 7.24%   |
| Unknown             | 25        | 4.42%   |
| Ramaxel Technology  | 11        | 1.94%   |
| A-DATA Technology   | 11        | 1.94%   |
| Smart               | 6         | 1.06%   |
| Elpida              | 6         | 1.06%   |
| Team                | 5         | 0.88%   |
| Corsair             | 5         | 0.88%   |
| Unknown (ABCD)      | 3         | 0.53%   |
| Transcend           | 3         | 0.53%   |
| SMART Brazil        | 3         | 0.53%   |
| G.Skill             | 3         | 0.53%   |
| Avant               | 3         | 0.53%   |
| Nanya Technology    | 2         | 0.35%   |
| Goldkey             | 2         | 0.35%   |
| Unknown             | 2         | 0.35%   |
| Unknown (0x7301)    | 1         | 0.18%   |
| RZX                 | 1         | 0.18%   |
| Qimonda             | 1         | 0.18%   |
| PUSKILL             | 1         | 0.18%   |
| Patriot             | 1         | 0.18%   |
| Miron               | 1         | 0.18%   |
| GOODRAM             | 1         | 0.18%   |
| fef5                | 1         | 0.18%   |
| CSX                 | 1         | 0.18%   |
| ASint Technology    | 1         | 0.18%   |
| AMD                 | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 12        | 2%      |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 10        | 1.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 1.5%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.33%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 8         | 1.33%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 1.17%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 7         | 1.17%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 6         | 1%      |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1%      |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 6         | 1%      |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 1%      |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.83%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 5         | 0.83%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.83%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.83%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.83%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 5         | 0.83%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 5         | 0.83%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.83%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 4         | 0.67%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 4         | 0.67%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 4         | 0.67%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.67%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.67%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.67%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 4         | 0.67%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.67%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 0.67%   |
| Crucial RAM CT51264BF160BJ.C8F 4096MB SODIMM DDR3 1600MT/s       | 4         | 0.67%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16384MB SODIMM DDR4 3200MT/s    | 4         | 0.67%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.5%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.5%    |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 3         | 0.5%    |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.5%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.5%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.5%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 3         | 0.5%    |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 3         | 0.5%    |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                      | 3         | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.5%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.5%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.5%    |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 0.33%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 2         | 0.33%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 2         | 0.33%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 2         | 0.33%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.33%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 2         | 0.33%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 268       | 56.54%  |
| DDR3    | 117       | 24.68%  |
| LPDDR4  | 38        | 8.02%   |
| LPDDR3  | 35        | 7.38%   |
| DDR2    | 8         | 1.69%   |
| SDRAM   | 4         | 0.84%   |
| Unknown | 4         | 0.84%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 393       | 81.03%  |
| Row Of Chips | 81        | 16.7%   |
| Chip         | 7         | 1.44%   |
| DIMM         | 2         | 0.41%   |
| Unknown      | 2         | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 226       | 44.14%  |
| 4096  | 137       | 26.76%  |
| 16384 | 85        | 16.6%   |
| 2048  | 37        | 7.23%   |
| 32768 | 20        | 3.91%   |
| 1024  | 7         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 129       | 25.49%  |
| 2667    | 115       | 22.73%  |
| 1600    | 84        | 16.6%   |
| 2400    | 35        | 6.92%   |
| 2133    | 34        | 6.72%   |
| 4267    | 21        | 4.15%   |
| 1867    | 16        | 3.16%   |
| 1334    | 11        | 2.17%   |
| 1333    | 10        | 1.98%   |
| 1067    | 8         | 1.58%   |
| 3266    | 7         | 1.38%   |
| 1066    | 6         | 1.19%   |
| 667     | 6         | 1.19%   |
| 4266    | 5         | 0.99%   |
| 3733    | 5         | 0.99%   |
| 4199    | 4         | 0.79%   |
| 4800    | 2         | 0.4%    |
| 2933    | 2         | 0.4%    |
| 800     | 2         | 0.4%    |
| 8400    | 1         | 0.2%    |
| 1866    | 1         | 0.2%    |
| 975     | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 40%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-3200 Series         | 1         | 20%     |
| Samsung CLX-6260 Series         | 1         | 20%     |
| Prolific PL2305 Parallel Port   | 1         | 20%     |
| HP LaserJet 400 colorMFP M475dw | 1         | 20%     |
| Canon TR8500 series             | 1         | 20%     |

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
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 184       | 22.41%  |
| IMC Networks                           | 96        | 11.69%  |
| Realtek Semiconductor                  | 81        | 9.87%   |
| Acer                                   | 77        | 9.38%   |
| Microdia                               | 74        | 9.01%   |
| Quanta                                 | 57        | 6.94%   |
| Sunplus Innovation Technology          | 40        | 4.87%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 3.78%   |
| Logitech                               | 28        | 3.41%   |
| Syntek                                 | 22        | 2.68%   |
| Apple                                  | 22        | 2.68%   |
| Lite-On Technology                     | 21        | 2.56%   |
| Suyin                                  | 14        | 1.71%   |
| Luxvisions Innotech Limited            | 14        | 1.71%   |
| Samsung Electronics                    | 8         | 0.97%   |
| Silicon Motion                         | 7         | 0.85%   |
| Ricoh                                  | 4         | 0.49%   |
| Lenovo                                 | 4         | 0.49%   |
| Alcor Micro                            | 4         | 0.49%   |
| USB Camera                             | 3         | 0.37%   |
| Sonix Technology                       | 3         | 0.37%   |
| Primax Electronics                     | 3         | 0.37%   |
| ARC International                      | 3         | 0.37%   |
| Tobii Technology AB                    | 2         | 0.24%   |
| Microsoft                              | 2         | 0.24%   |
| MacroSilicon                           | 2         | 0.24%   |
| Importek                               | 2         | 0.24%   |
| Generalplus Technology                 | 2         | 0.24%   |
| webcam                                 | 1         | 0.12%   |
| WaveRider Communications               | 1         | 0.12%   |
| SunplusIT                              | 1         | 0.12%   |
| Razer USA                              | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| Omnivision                             | 1         | 0.12%   |
| Foxconn / Hon Hai                      | 1         | 0.12%   |
| DigiTech                               | 1         | 0.12%   |
| Creative Technology                    | 1         | 0.12%   |
| ANYKA                                  | 1         | 0.12%   |
| ALi                                    | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 62        | 7.51%   |
| Microdia Integrated_Webcam_HD                                   | 46        | 5.57%   |
| IMC Networks Integrated Camera                                  | 45        | 5.45%   |
| Acer Integrated Camera                                          | 34        | 4.12%   |
| Realtek Integrated_Webcam_HD                                    | 30        | 3.63%   |
| Sunplus Integrated_Webcam_HD                                    | 23        | 2.78%   |
| Quanta HD User Facing                                           | 20        | 2.42%   |
| Chicony HD WebCam                                               | 20        | 2.42%   |
| Syntek Integrated Camera                                        | 18        | 2.18%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 17        | 2.06%   |
| Quanta HP TrueVision HD Camera                                  | 11        | 1.33%   |
| Chicony Integrated Camera (1280x720@30)                         | 11        | 1.33%   |
| Lite-On HP HD Camera                                            | 9         | 1.09%   |
| IMC Networks HD Camera                                          | 9         | 1.09%   |
| Apple Built-in iSight                                           | 9         | 1.09%   |
| Samsung Galaxy A5 (MTP)                                         | 8         | 0.97%   |
| Microdia Integrated Webcam                                      | 8         | 0.97%   |
| Logitech Webcam C270                                            | 8         | 0.97%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 7         | 0.85%   |
| Chicony USB2.0 Camera                                           | 7         | 0.85%   |
| Acer SunplusIT Integrated Camera                                | 7         | 0.85%   |
| Acer HD Webcam                                                  | 7         | 0.85%   |
| Acer BisonCam,NB Pro                                            | 7         | 0.85%   |
| Realtek Laptop Camera                                           | 6         | 0.73%   |
| Realtek Integrated Webcam HD                                    | 6         | 0.73%   |
| Realtek Integrated Webcam                                       | 6         | 0.73%   |
| Quanta HP HD Camera                                             | 6         | 0.73%   |
| Logitech HD Pro Webcam C920                                     | 6         | 0.73%   |
| Chicony HP HD Camera                                            | 6         | 0.73%   |
| Chicony HD User Facing                                          | 6         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 6         | 0.73%   |
| Apple FaceTime HD Camera                                        | 6         | 0.73%   |
| Acer Lenovo EasyCamera                                          | 6         | 0.73%   |
| Sunplus HD WebCam                                               | 5         | 0.61%   |
| Realtek USB Camera                                              | 5         | 0.61%   |
| Realtek Integrated Camera                                       | 5         | 0.61%   |
| Logitech C922 Pro Stream Webcam                                 | 5         | 0.61%   |
| Lite-On Integrated Camera                                       | 5         | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                                    | 5         | 0.61%   |
| Chicony USB 2.0 Camera                                          | 5         | 0.61%   |
| Chicony HP Wide Vision HD Camera                                | 5         | 0.61%   |
| Chicony HP TrueVision HD                                        | 5         | 0.61%   |
| Chicony EasyCamera                                              | 5         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 0.61%   |
| Apple FaceTime HD Camera (Built-in)                             | 5         | 0.61%   |
| Suyin Integrated_Webcam_HD                                      | 4         | 0.48%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 4         | 0.48%   |
| Realtek Lenovo EasyCamera                                       | 4         | 0.48%   |
| Quanta VGA WebCam                                               | 4         | 0.48%   |
| Microdia Integrated Webcam HD                                   | 4         | 0.48%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 0.48%   |
| Luxvisions Innotech Limited HP HD Camera                        | 4         | 0.48%   |
| IMC Networks ov9734_azurewave_camera                            | 4         | 0.48%   |
| Chicony ThinkPad T490 Webcam                                    | 4         | 0.48%   |
| Chicony HP HD Webcam                                            | 4         | 0.48%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 4         | 0.48%   |
| Acer BisonCam, NB Pro                                           | 4         | 0.48%   |
| USB Camera USB Camera                                           | 3         | 0.36%   |
| Syntek EasyCamera                                               | 3         | 0.36%   |
| Realtek HD WebCam                                               | 3         | 0.36%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 80        | 38.83%  |
| Validity Sensors           | 57        | 27.67%  |
| Shenzhen Goodix Technology | 44        | 21.36%  |
| Elan Microelectronics      | 12        | 5.83%   |
| Upek                       | 6         | 2.91%   |
| LighTuning Technology      | 5         | 2.43%   |
| AuthenTec                  | 2         | 0.97%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 47        | 22.82%  |
| Shenzhen Goodix  Fingerprint Device                                        | 29        | 14.08%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 8.25%   |
| Unknown                                                                    | 13        | 6.31%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 4.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 4.37%   |
| Elan ELAN:Fingerprint                                                      | 8         | 3.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.91%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 2.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.91%   |
| Validity Sensors VFS491                                                    | 5         | 2.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.43%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 2.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.43%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.46%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.46%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.46%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.97%   |
| Synaptics  WBDI                                                            | 2         | 0.97%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.97%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.49%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.49%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.49%   |
| Synaptics WBDI Device                                                      | 1         | 0.49%   |
| AuthenTec AES2810                                                          | 1         | 0.49%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 35        | 48.61%  |
| Broadcom                  | 28        | 38.89%  |
| Lenovo                    | 3         | 4.17%   |
| Upek                      | 2         | 2.78%   |
| O2 Micro                  | 1         | 1.39%   |
| Hewlett-Packard           | 1         | 1.39%   |
| Gemalto (was Gemplus)     | 1         | 1.39%   |
| Aladdin Knowledge Systems | 1         | 1.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 48.61%  |
| Broadcom 58200                                                               | 10        | 13.89%  |
| Broadcom 5880                                                                | 8         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 5.56%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.17%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 2.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.39%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.39%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.39%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 502       | 57.83%  |
| 1     | 292       | 33.64%  |
| 2     | 61        | 7.03%   |
| 3     | 10        | 1.15%   |
| 4     | 2         | 0.23%   |
| 5     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 200       | 44.84%  |
| Graphics card            | 101       | 22.65%  |
| Multimedia controller    | 51        | 11.43%  |
| Net/wireless             | 35        | 7.85%   |
| Camera                   | 18        | 4.04%   |
| Bluetooth                | 14        | 3.14%   |
| Chipcard                 | 10        | 2.24%   |
| Card reader              | 7         | 1.57%   |
| Storage                  | 4         | 0.9%    |
| Net/ethernet             | 3         | 0.67%   |
| Sound                    | 1         | 0.22%   |
| Network                  | 1         | 0.22%   |
| Communication controller | 1         | 0.22%   |


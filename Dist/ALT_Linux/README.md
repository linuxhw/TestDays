ALT Linux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ALT Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ALT_Linux/Desktop/README.md) and [notebooks](/Dist/ALT_Linux/Notebook/README.md).

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

Total: 1234

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | G505 20240                  | Notebook    | [b6181c89ff](https://linux-hardware.org/?probe=b6181c89ff) | Jan 05, 2025 |
| Apple         | MacBookPro16,1              | Notebook    | [ba278c0390](https://linux-hardware.org/?probe=ba278c0390) | Jan 04, 2025 |
| Apple         | MacBookPro16,1              | Notebook    | [d49932671f](https://linux-hardware.org/?probe=d49932671f) | Jan 04, 2025 |
| ASUSTek       | K50IJ                       | Notebook    | [9c75aa0285](https://linux-hardware.org/?probe=9c75aa0285) | Jan 04, 2025 |
| Chuwi         | Hi10 Max                    | Tablet      | [2af3e8f0c5](https://linux-hardware.org/?probe=2af3e8f0c5) | Jan 03, 2025 |
| ICL           | H410SB                      | Desktop     | [a75155cf86](https://linux-hardware.org/?probe=a75155cf86) | Jan 02, 2025 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [da076eeaf3](https://linux-hardware.org/?probe=da076eeaf3) | Jan 02, 2025 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [884ad79ee5](https://linux-hardware.org/?probe=884ad79ee5) | Dec 29, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f5c01dc687](https://linux-hardware.org/?probe=f5c01dc687) | Dec 28, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [fbaccf3c9e](https://linux-hardware.org/?probe=fbaccf3c9e) | Dec 28, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [8c51d26687](https://linux-hardware.org/?probe=8c51d26687) | Dec 27, 2024 |
| Acer          | Extensa 215-23              | Notebook    | [97337ddb76](https://linux-hardware.org/?probe=97337ddb76) | Dec 26, 2024 |
| MSI           | 760G-P43                    | Desktop     | [faf4279015](https://linux-hardware.org/?probe=faf4279015) | Dec 25, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [6e86ec71a9](https://linux-hardware.org/?probe=6e86ec71a9) | Dec 23, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [8ccb1a5d52](https://linux-hardware.org/?probe=8ccb1a5d52) | Dec 23, 2024 |
| Infinix       | INBOOK Y4H Max              | Notebook    | [e5a91667f9](https://linux-hardware.org/?probe=e5a91667f9) | Dec 21, 2024 |
| MSI           | B450-A PRO MAX              | Desktop     | [697b67cc2a](https://linux-hardware.org/?probe=697b67cc2a) | Dec 20, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [0b9173adf1](https://linux-hardware.org/?probe=0b9173adf1) | Dec 19, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [7cf5f17079](https://linux-hardware.org/?probe=7cf5f17079) | Dec 18, 2024 |
| Lenovo        | B50-30 20382                | Notebook    | [4ccf2f7c9a](https://linux-hardware.org/?probe=4ccf2f7c9a) | Dec 17, 2024 |
| ASRock        | Z97 Pro4                    | Desktop     | [1aa9e4d9eb](https://linux-hardware.org/?probe=1aa9e4d9eb) | Dec 15, 2024 |
| HP            | 2B29                        | Desktop     | [9216921849](https://linux-hardware.org/?probe=9216921849) | Dec 14, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [991cc2d32a](https://linux-hardware.org/?probe=991cc2d32a) | Dec 13, 2024 |
| DEPO Compu... | DPH110S                     | Desktop     | [bf9bb46070](https://linux-hardware.org/?probe=bf9bb46070) | Dec 13, 2024 |
| LTD Delovo... | 14TLH                       | Notebook    | [8c4728d52e](https://linux-hardware.org/?probe=8c4728d52e) | Dec 12, 2024 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [b4a81ce6eb](https://linux-hardware.org/?probe=b4a81ce6eb) | Dec 11, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [90ff703a16](https://linux-hardware.org/?probe=90ff703a16) | Dec 09, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [5b43ecc284](https://linux-hardware.org/?probe=5b43ecc284) | Dec 08, 2024 |
| DEPO Compu... | DPA520S                     | Desktop     | [5231e4d20b](https://linux-hardware.org/?probe=5231e4d20b) | Dec 06, 2024 |
| ASRock        | A520M Pro4                  | Desktop     | [9b40494a18](https://linux-hardware.org/?probe=9b40494a18) | Nov 30, 2024 |
| Maibenben     | Perfectum Series            | Notebook    | [02a7c3fca7](https://linux-hardware.org/?probe=02a7c3fca7) | Nov 29, 2024 |
| Maibenben     | Perfectum Series            | Notebook    | [eb0de561cc](https://linux-hardware.org/?probe=eb0de561cc) | Nov 28, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5050024ce1](https://linux-hardware.org/?probe=5050024ce1) | Nov 26, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9f23908f61](https://linux-hardware.org/?probe=9f23908f61) | Nov 26, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [140d3172c1](https://linux-hardware.org/?probe=140d3172c1) | Nov 26, 2024 |
| ASRock        | N68-GS4 FX                  | Desktop     | [34007a1ee6](https://linux-hardware.org/?probe=34007a1ee6) | Nov 25, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [ab329aa759](https://linux-hardware.org/?probe=ab329aa759) | Nov 24, 2024 |
| ASUSTek       | X75VC                       | Notebook    | [806fb829db](https://linux-hardware.org/?probe=806fb829db) | Nov 23, 2024 |
| Samsung       | RV413/RV513                 | Notebook    | [fc599fadf9](https://linux-hardware.org/?probe=fc599fadf9) | Nov 21, 2024 |
| Samsung       | RV413/RV513                 | Notebook    | [5df100f2d2](https://linux-hardware.org/?probe=5df100f2d2) | Nov 21, 2024 |
| Acer          | Swift SF114-34              | Notebook    | [55147661fe](https://linux-hardware.org/?probe=55147661fe) | Nov 18, 2024 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [da3c0f73b4](https://linux-hardware.org/?probe=da3c0f73b4) | Nov 18, 2024 |
| Acer          | Aspire 3820                 | Notebook    | [166c3be5a7](https://linux-hardware.org/?probe=166c3be5a7) | Nov 16, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b270434bda](https://linux-hardware.org/?probe=b270434bda) | Nov 16, 2024 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [508795271f](https://linux-hardware.org/?probe=508795271f) | Nov 15, 2024 |
| ASUSTek       | H87M-PRO                    | Desktop     | [4cfc3ae5e0](https://linux-hardware.org/?probe=4cfc3ae5e0) | Nov 15, 2024 |
| Biostar       | A68MHE                      | Desktop     | [0d3e4beafb](https://linux-hardware.org/?probe=0d3e4beafb) | Nov 13, 2024 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [ab2d6d51bb](https://linux-hardware.org/?probe=ab2d6d51bb) | Nov 12, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [4a30303850](https://linux-hardware.org/?probe=4a30303850) | Nov 12, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [f898051323](https://linux-hardware.org/?probe=f898051323) | Nov 10, 2024 |
| HP            | 3397                        | Desktop     | [04fa6a24ee](https://linux-hardware.org/?probe=04fa6a24ee) | Nov 08, 2024 |
| HP            | 83EE                        | Desktop     | [491546c0fe](https://linux-hardware.org/?probe=491546c0fe) | Nov 05, 2024 |
| ASRock        | Z68M/USB3                   | Desktop     | [f39d49f78f](https://linux-hardware.org/?probe=f39d49f78f) | Oct 31, 2024 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [49f3ef7f7c](https://linux-hardware.org/?probe=49f3ef7f7c) | Oct 28, 2024 |
| Gigabyte      | B550M K                     | Desktop     | [dde963874f](https://linux-hardware.org/?probe=dde963874f) | Oct 27, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | Desktop     | [2a206ed000](https://linux-hardware.org/?probe=2a206ed000) | Oct 26, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [ee26c48295](https://linux-hardware.org/?probe=ee26c48295) | Oct 26, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [c97e55f524](https://linux-hardware.org/?probe=c97e55f524) | Oct 22, 2024 |
| HP            | 83EE                        | Desktop     | [8cbf62fc9b](https://linux-hardware.org/?probe=8cbf62fc9b) | Oct 21, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [0c2cc5321c](https://linux-hardware.org/?probe=0c2cc5321c) | Oct 20, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [6d016ec789](https://linux-hardware.org/?probe=6d016ec789) | Oct 20, 2024 |
| ASUSTek       | UX310UA                     | Notebook    | [104830f2b8](https://linux-hardware.org/?probe=104830f2b8) | Oct 20, 2024 |
| ASUSTek       | PN62                        | Mini pc     | [181ed93c2f](https://linux-hardware.org/?probe=181ed93c2f) | Oct 19, 2024 |
| ASUSTek       | PN62                        | Mini pc     | [89e7b6ede2](https://linux-hardware.org/?probe=89e7b6ede2) | Oct 19, 2024 |
| Biostar       | H61MHV3                     | Desktop     | [03f4106810](https://linux-hardware.org/?probe=03f4106810) | Oct 19, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [00e3458bd8](https://linux-hardware.org/?probe=00e3458bd8) | Oct 19, 2024 |
| HP            | ENVY x360 Convertible       | Convertible | [c8069846ef](https://linux-hardware.org/?probe=c8069846ef) | Oct 18, 2024 |
| HP            | ENVY x360 Convertible       | Convertible | [55d7422c39](https://linux-hardware.org/?probe=55d7422c39) | Oct 18, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [6e0c8954c4](https://linux-hardware.org/?probe=6e0c8954c4) | Oct 18, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [689b8ad5f4](https://linux-hardware.org/?probe=689b8ad5f4) | Oct 18, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [8e6ad7a9bc](https://linux-hardware.org/?probe=8e6ad7a9bc) | Oct 17, 2024 |
| Intel         | B560-AIO T5V E1.0G          | Desktop     | [b1aab7dcb2](https://linux-hardware.org/?probe=b1aab7dcb2) | Oct 17, 2024 |
| Intel         | B560-AIO T5V E1.0G          | Desktop     | [0b038153a1](https://linux-hardware.org/?probe=0b038153a1) | Oct 17, 2024 |
| Lenovo        | ThinkPad X240 20AMS3AE04    | Notebook    | [fcb1f007a5](https://linux-hardware.org/?probe=fcb1f007a5) | Oct 16, 2024 |
| HP            | 1497                        | Desktop     | [81bc95c34c](https://linux-hardware.org/?probe=81bc95c34c) | Oct 15, 2024 |
| Unknown       | Unknown                     | Notebook    | [af5eaabfc2](https://linux-hardware.org/?probe=af5eaabfc2) | Oct 14, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [394bacc9ee](https://linux-hardware.org/?probe=394bacc9ee) | Oct 12, 2024 |
| Maibenben     | Perfectum Series            | Notebook    | [055b2907a1](https://linux-hardware.org/?probe=055b2907a1) | Oct 12, 2024 |
| Digma         | ES6022EW                    | Notebook    | [9962907672](https://linux-hardware.org/?probe=9962907672) | Oct 10, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6c153457c0](https://linux-hardware.org/?probe=6c153457c0) | Oct 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [a64d1227cd](https://linux-hardware.org/?probe=a64d1227cd) | Oct 07, 2024 |
| Maibenben     | Perfectum Series            | Notebook    | [3ca7c3595a](https://linux-hardware.org/?probe=3ca7c3595a) | Oct 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [f8ec20365c](https://linux-hardware.org/?probe=f8ec20365c) | Oct 02, 2024 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [bd2ebeb7e0](https://linux-hardware.org/?probe=bd2ebeb7e0) | Sep 30, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [5cab2e516c](https://linux-hardware.org/?probe=5cab2e516c) | Sep 28, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [004f265b76](https://linux-hardware.org/?probe=004f265b76) | Sep 28, 2024 |
| HP            | 2B29                        | Desktop     | [f803e78e04](https://linux-hardware.org/?probe=f803e78e04) | Sep 27, 2024 |
| Dell          | Inspiron 5520               | Notebook    | [7674f2b4d4](https://linux-hardware.org/?probe=7674f2b4d4) | Sep 27, 2024 |
| Pegatron      | NM70-P1/ODM                 | Desktop     | [6a2f74fa01](https://linux-hardware.org/?probe=6a2f74fa01) | Sep 27, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [7983ebe0a8](https://linux-hardware.org/?probe=7983ebe0a8) | Sep 26, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b080df96d5](https://linux-hardware.org/?probe=b080df96d5) | Sep 26, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [7345591513](https://linux-hardware.org/?probe=7345591513) | Sep 26, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [169fa55862](https://linux-hardware.org/?probe=169fa55862) | Sep 26, 2024 |
| Gigabyte      | Z590 VISION G               | Desktop     | [e711388bf1](https://linux-hardware.org/?probe=e711388bf1) | Sep 20, 2024 |
| AZW           | MINI S                      | Desktop     | [26fedf82a8](https://linux-hardware.org/?probe=26fedf82a8) | Sep 18, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [11fe29956f](https://linux-hardware.org/?probe=11fe29956f) | Sep 18, 2024 |
| KUANLITU      | S series                    | Notebook    | [dfbb1b67c9](https://linux-hardware.org/?probe=dfbb1b67c9) | Sep 18, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [3f6b5da510](https://linux-hardware.org/?probe=3f6b5da510) | Sep 15, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [dd9c45fac7](https://linux-hardware.org/?probe=dd9c45fac7) | Sep 14, 2024 |
| ASUSTek       | Z97-K/USB                   | Desktop     | [5b3bbf6f3b](https://linux-hardware.org/?probe=5b3bbf6f3b) | Sep 14, 2024 |
| DEPO Compu... | DPC156                      | Notebook    | [a869ccaa68](https://linux-hardware.org/?probe=a869ccaa68) | Sep 13, 2024 |
| DEPO Compu... | DPC156                      | Notebook    | [4ce9fbc296](https://linux-hardware.org/?probe=4ce9fbc296) | Sep 13, 2024 |
| Graviton      | ONEGA                       | Server      | [d18f3de7aa](https://linux-hardware.org/?probe=d18f3de7aa) | Sep 11, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [f67b0818c6](https://linux-hardware.org/?probe=f67b0818c6) | Sep 11, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [e83c9c0dc1](https://linux-hardware.org/?probe=e83c9c0dc1) | Sep 09, 2024 |
| Kraftway      | KWH310                      | Desktop     | [14063d22e1](https://linux-hardware.org/?probe=14063d22e1) | Sep 07, 2024 |
| Acer          | Swift SF114-34              | Notebook    | [5024e5c57a](https://linux-hardware.org/?probe=5024e5c57a) | Sep 03, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [0232ff85b0](https://linux-hardware.org/?probe=0232ff85b0) | Sep 02, 2024 |
| HONOR         | GLO-GXXX                    | Notebook    | [a9c3bcdc17](https://linux-hardware.org/?probe=a9c3bcdc17) | Aug 28, 2024 |
| Maibenben     | Perfectum Series            | Notebook    | [174965af02](https://linux-hardware.org/?probe=174965af02) | Aug 27, 2024 |
| Maibenben     | Perfectum Series            | Notebook    | [5664d23a84](https://linux-hardware.org/?probe=5664d23a84) | Aug 26, 2024 |
| Digma         | Pro Fortis M DN15P3-8CXN... | Notebook    | [14b631992b](https://linux-hardware.org/?probe=14b631992b) | Aug 26, 2024 |
| Graviton      | ONEGA                       | Server      | [6139c08802](https://linux-hardware.org/?probe=6139c08802) | Aug 26, 2024 |
| HONOR         | GLO-GXXX                    | Notebook    | [2455c48ab5](https://linux-hardware.org/?probe=2455c48ab5) | Aug 25, 2024 |
| Lenovo        | ThinkPad T480 20L6S57T00    | Notebook    | [10256fb963](https://linux-hardware.org/?probe=10256fb963) | Aug 24, 2024 |
| HUAWEI        | RLEF-XX                     | Notebook    | [34f2013170](https://linux-hardware.org/?probe=34f2013170) | Aug 22, 2024 |
| ASUSTek       | ROG Strix G733QM_G733QM     | Notebook    | [598d872013](https://linux-hardware.org/?probe=598d872013) | Aug 20, 2024 |
| ASUSTek       | ROG Strix G733QM_G733QM     | Notebook    | [b969d73cb0](https://linux-hardware.org/?probe=b969d73cb0) | Aug 20, 2024 |
| ASRock        | A520M Pro4                  | Desktop     | [636eec8156](https://linux-hardware.org/?probe=636eec8156) | Aug 19, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d029537860](https://linux-hardware.org/?probe=d029537860) | Aug 19, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V5.1       | Desktop     | [c5b89ad433](https://linux-hardware.org/?probe=c5b89ad433) | Aug 18, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [82c857ca2e](https://linux-hardware.org/?probe=82c857ca2e) | Aug 17, 2024 |
| Sony          | VGN-AR51J                   | Notebook    | [68abb3faf1](https://linux-hardware.org/?probe=68abb3faf1) | Aug 15, 2024 |
| ASUSTek       | 1015BXO                     | Notebook    | [f842010ab4](https://linux-hardware.org/?probe=f842010ab4) | Aug 13, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [e85becff2f](https://linux-hardware.org/?probe=e85becff2f) | Aug 10, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7b569e1148](https://linux-hardware.org/?probe=7b569e1148) | Aug 09, 2024 |
| Gigabyte      | B650M DS3H                  | Desktop     | [2d11a234d5](https://linux-hardware.org/?probe=2d11a234d5) | Aug 06, 2024 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [7b98bc1efa](https://linux-hardware.org/?probe=7b98bc1efa) | Aug 03, 2024 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [52bfb9882c](https://linux-hardware.org/?probe=52bfb9882c) | Aug 03, 2024 |
| LG Electro... | 15Z90ST-G.AAW4U1            | Notebook    | [9cf11c7129](https://linux-hardware.org/?probe=9cf11c7129) | Aug 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [f08e885430](https://linux-hardware.org/?probe=f08e885430) | Aug 01, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4bdee79709](https://linux-hardware.org/?probe=4bdee79709) | Aug 01, 2024 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [28794c402f](https://linux-hardware.org/?probe=28794c402f) | Aug 01, 2024 |
| HONOR         | HYM-WXX                     | Notebook    | [497089dc56](https://linux-hardware.org/?probe=497089dc56) | Jul 30, 2024 |
| Apple         | MacBookPro14,3              | Notebook    | [4727ea5521](https://linux-hardware.org/?probe=4727ea5521) | Jul 29, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | Desktop     | [d7fcb0b28a](https://linux-hardware.org/?probe=d7fcb0b28a) | Jul 28, 2024 |
| Acer          | Aspire V3-571G              | Notebook    | [8db668cfb5](https://linux-hardware.org/?probe=8db668cfb5) | Jul 27, 2024 |
| MSI           | MS-B0A21                    | Desktop     | [52d37fde14](https://linux-hardware.org/?probe=52d37fde14) | Jul 26, 2024 |
| ICL Techno    | F140a                       | Notebook    | [6c9498bc2f](https://linux-hardware.org/?probe=6c9498bc2f) | Jul 24, 2024 |
| HONOR         | NMH-WCX9                    | Notebook    | [9d91f90ded](https://linux-hardware.org/?probe=9d91f90ded) | Jul 22, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [5b236846cf](https://linux-hardware.org/?probe=5b236846cf) | Jul 21, 2024 |
| Intel         | H81U                        | Notebook    | [db7284262b](https://linux-hardware.org/?probe=db7284262b) | Jul 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [a28e524a63](https://linux-hardware.org/?probe=a28e524a63) | Jul 20, 2024 |
| Acer          | Aspire XC-1660 V:1.1        | Desktop     | [31dbe1ce9e](https://linux-hardware.org/?probe=31dbe1ce9e) | Jul 19, 2024 |
| Sony          | VPCCA2S1R                   | Notebook    | [65ea977de0](https://linux-hardware.org/?probe=65ea977de0) | Jul 17, 2024 |
| MSI           | Z97 U3 PLUS                 | Desktop     | [bec2e23ba0](https://linux-hardware.org/?probe=bec2e23ba0) | Jul 13, 2024 |
| MSI           | X470 GAMING PRO             | Desktop     | [704b7ed845](https://linux-hardware.org/?probe=704b7ed845) | Jul 12, 2024 |
| Aquarius      | AQH310CM                    | Desktop     | [65ab62646c](https://linux-hardware.org/?probe=65ab62646c) | Jul 10, 2024 |
| Aquarius      | AQH310CM                    | Desktop     | [8dd8a81958](https://linux-hardware.org/?probe=8dd8a81958) | Jul 10, 2024 |
| MACHENIKE     | L17A                        | Notebook    | [5d481d8baf](https://linux-hardware.org/?probe=5d481d8baf) | Jul 09, 2024 |
| MACHENIKE     | L17A                        | Notebook    | [25167c9d0b](https://linux-hardware.org/?probe=25167c9d0b) | Jul 09, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [1b9c516078](https://linux-hardware.org/?probe=1b9c516078) | Jul 09, 2024 |
| Acer          | TDPS05                      | Desktop     | [69ec0ebb0e](https://linux-hardware.org/?probe=69ec0ebb0e) | Jul 05, 2024 |
| Biostar       | A68MHE                      | Desktop     | [8bfd525ace](https://linux-hardware.org/?probe=8bfd525ace) | Jul 05, 2024 |
| Acer          | Aspire E3-112               | Notebook    | [8dde0e933a](https://linux-hardware.org/?probe=8dde0e933a) | Jul 05, 2024 |
| Acer          | Aspire E3-112               | Notebook    | [9a9c5efccd](https://linux-hardware.org/?probe=9a9c5efccd) | Jul 04, 2024 |
| Aquarius      | AQH310CM                    | Desktop     | [5be2d7706e](https://linux-hardware.org/?probe=5be2d7706e) | Jul 01, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [bb05c5cd47](https://linux-hardware.org/?probe=bb05c5cd47) | Jul 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5ecae8cb36](https://linux-hardware.org/?probe=5ecae8cb36) | Jun 28, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [d8b58eedf8](https://linux-hardware.org/?probe=d8b58eedf8) | Jun 28, 2024 |
| Infinix       | INBOOK Y1 PLUS              | Notebook    | [2b099e1636](https://linux-hardware.org/?probe=2b099e1636) | Jun 26, 2024 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [5065fe29a2](https://linux-hardware.org/?probe=5065fe29a2) | Jun 26, 2024 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [b16d910164](https://linux-hardware.org/?probe=b16d910164) | Jun 26, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [c17442ac07](https://linux-hardware.org/?probe=c17442ac07) | Jun 23, 2024 |
| Gigabyte      | B365M D2V                   | Desktop     | [9a4ad817b1](https://linux-hardware.org/?probe=9a4ad817b1) | Jun 23, 2024 |
| Biostar       | A68MHE                      | Desktop     | [14c11d75cb](https://linux-hardware.org/?probe=14c11d75cb) | Jun 22, 2024 |
| MACHENIKE     | S16C                        | Notebook    | [6e918896fd](https://linux-hardware.org/?probe=6e918896fd) | Jun 20, 2024 |
| HONOR         | NMH-WCX9                    | Notebook    | [6b87d089e7](https://linux-hardware.org/?probe=6b87d089e7) | Jun 19, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [a6b39899a7](https://linux-hardware.org/?probe=a6b39899a7) | Jun 16, 2024 |
| ASUSTek       | K43SJ                       | Notebook    | [01cca13919](https://linux-hardware.org/?probe=01cca13919) | Jun 11, 2024 |
| Dell          | Inspiron M5110              | Notebook    | [fe89ff584f](https://linux-hardware.org/?probe=fe89ff584f) | Jun 10, 2024 |
| MSI           | PRO B660M-P DDR4            | Desktop     | [449ead260f](https://linux-hardware.org/?probe=449ead260f) | Jun 09, 2024 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [9170618489](https://linux-hardware.org/?probe=9170618489) | Jun 08, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [ae046e6c96](https://linux-hardware.org/?probe=ae046e6c96) | Jun 04, 2024 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fc313f3019](https://linux-hardware.org/?probe=fc313f3019) | Jun 04, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [7842abdb45](https://linux-hardware.org/?probe=7842abdb45) | Jun 03, 2024 |
| Unknown       | RG353M                      | Soc         | [5d5f227d5d](https://linux-hardware.org/?probe=5d5f227d5d) | Jun 02, 2024 |
| HP            | Pavilion 15                 | Notebook    | [5c070443f1](https://linux-hardware.org/?probe=5c070443f1) | Jun 01, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9696b9931a](https://linux-hardware.org/?probe=9696b9931a) | May 31, 2024 |
| HP            | EliteBook 850 G1            | Notebook    | [36e9f75edd](https://linux-hardware.org/?probe=36e9f75edd) | May 30, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [7d3f6f86dd](https://linux-hardware.org/?probe=7d3f6f86dd) | May 30, 2024 |
| ASUSTek       | K43SJ                       | Notebook    | [527d676304](https://linux-hardware.org/?probe=527d676304) | May 30, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [fcc722c5cb](https://linux-hardware.org/?probe=fcc722c5cb) | May 26, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [f26b84f0e9](https://linux-hardware.org/?probe=f26b84f0e9) | May 26, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a3e3a8bc39](https://linux-hardware.org/?probe=a3e3a8bc39) | May 25, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [5fcd94ffeb](https://linux-hardware.org/?probe=5fcd94ffeb) | May 25, 2024 |
| HP            | 8184 X4                     | Desktop     | [2d56e66964](https://linux-hardware.org/?probe=2d56e66964) | May 22, 2024 |
| Unknown       | Unknown                     | Notebook    | [63b860d0cc](https://linux-hardware.org/?probe=63b860d0cc) | May 22, 2024 |
| Unknown       | Unknown                     | Notebook    | [5aa1cb0e36](https://linux-hardware.org/?probe=5aa1cb0e36) | May 22, 2024 |
| Kraftway      | ACCORD                      | Notebook    | [73d302e1ec](https://linux-hardware.org/?probe=73d302e1ec) | May 21, 2024 |
| BESHTAU       | B560M-D V51                 | Desktop     | [51aab9354b](https://linux-hardware.org/?probe=51aab9354b) | May 20, 2024 |
| Gigabyte      | H610M S2H                   | Desktop     | [342949d0ba](https://linux-hardware.org/?probe=342949d0ba) | May 17, 2024 |
| ASUSTek       | P5PE-VM                     | Desktop     | [c453bf034c](https://linux-hardware.org/?probe=c453bf034c) | May 17, 2024 |
| Aquarius      | AQH310CM                    | Desktop     | [e6b335988e](https://linux-hardware.org/?probe=e6b335988e) | May 14, 2024 |
| ASRock        | H610M-ITX/ac                | Desktop     | [382c5161c1](https://linux-hardware.org/?probe=382c5161c1) | May 13, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [12c1f66b60](https://linux-hardware.org/?probe=12c1f66b60) | May 12, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f83dfd7434](https://linux-hardware.org/?probe=f83dfd7434) | May 11, 2024 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [2ecceda7ae](https://linux-hardware.org/?probe=2ecceda7ae) | May 09, 2024 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [93d7cc0722](https://linux-hardware.org/?probe=93d7cc0722) | May 09, 2024 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [bb1ae830e8](https://linux-hardware.org/?probe=bb1ae830e8) | May 09, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [47b8006c42](https://linux-hardware.org/?probe=47b8006c42) | May 05, 2024 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [9002e7e3c5](https://linux-hardware.org/?probe=9002e7e3c5) | May 04, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [178f62317e](https://linux-hardware.org/?probe=178f62317e) | May 04, 2024 |
| HP            | ProBook 6450b               | Notebook    | [c4d1788222](https://linux-hardware.org/?probe=c4d1788222) | May 03, 2024 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [d00e301298](https://linux-hardware.org/?probe=d00e301298) | May 03, 2024 |
| Echips Imp... | NX140A-S                    | Notebook    | [dec569991b](https://linux-hardware.org/?probe=dec569991b) | Apr 30, 2024 |
| Lenovo        | ThinkPad T480 20L6S7MP00    | Notebook    | [ea3db5dd3c](https://linux-hardware.org/?probe=ea3db5dd3c) | Apr 29, 2024 |
| ASUSTek       | N53Jf                       | Notebook    | [02cf0c80c7](https://linux-hardware.org/?probe=02cf0c80c7) | Apr 29, 2024 |
| Intel Clie... | LAPAC71H                    | Notebook    | [a1a6c57c02](https://linux-hardware.org/?probe=a1a6c57c02) | Apr 28, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [f4d652cc40](https://linux-hardware.org/?probe=f4d652cc40) | Apr 25, 2024 |
| Graviton      | DMB-H610-TMI01              | All in one  | [0a19edf36a](https://linux-hardware.org/?probe=0a19edf36a) | Apr 23, 2024 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [db4468debf](https://linux-hardware.org/?probe=db4468debf) | Apr 23, 2024 |
| Intel Clie... | LAPAC71H                    | Notebook    | [c365e08c03](https://linux-hardware.org/?probe=c365e08c03) | Apr 20, 2024 |
| ASRock        | B450M Pro4-F                | Desktop     | [d721e6ffa6](https://linux-hardware.org/?probe=d721e6ffa6) | Apr 18, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1291c4934f](https://linux-hardware.org/?probe=1291c4934f) | Apr 18, 2024 |
| Aquarius      | NS685U R11                  | Notebook    | [b5b6ca6e69](https://linux-hardware.org/?probe=b5b6ca6e69) | Apr 18, 2024 |
| ICL Techno    | F140a                       | Notebook    | [bd46cdda52](https://linux-hardware.org/?probe=bd46cdda52) | Apr 16, 2024 |
| Biostar       | A68MHE                      | Desktop     | [d8db2caef4](https://linux-hardware.org/?probe=d8db2caef4) | Apr 14, 2024 |
| Biostar       | A68MHE                      | Desktop     | [acdf6abfbf](https://linux-hardware.org/?probe=acdf6abfbf) | Apr 14, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [dce8bf4cbc](https://linux-hardware.org/?probe=dce8bf4cbc) | Apr 13, 2024 |
| IP3 Tech      | ZEN1                        | Notebook    | [d85ba98172](https://linux-hardware.org/?probe=d85ba98172) | Apr 13, 2024 |
| Biostar       | H610MH                      | Desktop     | [06dbe44a85](https://linux-hardware.org/?probe=06dbe44a85) | Apr 13, 2024 |
| AZW           | GTR V02                     | Desktop     | [120d648339](https://linux-hardware.org/?probe=120d648339) | Apr 12, 2024 |
| Dell          | 030VXY A01                  | Desktop     | [03bd29951c](https://linux-hardware.org/?probe=03bd29951c) | Apr 11, 2024 |
| HP            | ProBook 4520s               | Notebook    | [6886f7483d](https://linux-hardware.org/?probe=6886f7483d) | Apr 09, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a5ab134bcf](https://linux-hardware.org/?probe=a5ab134bcf) | Apr 07, 2024 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [ba96d62394](https://linux-hardware.org/?probe=ba96d62394) | Apr 04, 2024 |
| DEPO Compu... | DPC156                      | Notebook    | [9320cdbb02](https://linux-hardware.org/?probe=9320cdbb02) | Apr 04, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [6156db54ff](https://linux-hardware.org/?probe=6156db54ff) | Mar 31, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [5ac75aad7e](https://linux-hardware.org/?probe=5ac75aad7e) | Mar 28, 2024 |
| Unknown       | EZpad                       | Tablet      | [1a2b90cec3](https://linux-hardware.org/?probe=1a2b90cec3) | Mar 27, 2024 |
| Biostar       | IH61MF-Q5                   | Desktop     | [6f251f08e1](https://linux-hardware.org/?probe=6f251f08e1) | Mar 25, 2024 |
| Aquarius      | AQH310CM                    | Desktop     | [368d914e46](https://linux-hardware.org/?probe=368d914e46) | Mar 24, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [11f7843550](https://linux-hardware.org/?probe=11f7843550) | Mar 23, 2024 |
| HP            | Unknown                     | Notebook    | [8247de95f8](https://linux-hardware.org/?probe=8247de95f8) | Mar 22, 2024 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [693e93ff73](https://linux-hardware.org/?probe=693e93ff73) | Mar 22, 2024 |
| TECNO Mobi... | MEGABOOK T15DA              | Notebook    | [c9580df31c](https://linux-hardware.org/?probe=c9580df31c) | Mar 20, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [09805af67f](https://linux-hardware.org/?probe=09805af67f) | Mar 20, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [a8f9e94787](https://linux-hardware.org/?probe=a8f9e94787) | Mar 16, 2024 |
| Gigabyte      | A520M DS3H                  | Desktop     | [d999681595](https://linux-hardware.org/?probe=d999681595) | Mar 16, 2024 |
| Gigabyte      | A520M DS3H                  | Desktop     | [d6731a38c7](https://linux-hardware.org/?probe=d6731a38c7) | Mar 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [5685e8711f](https://linux-hardware.org/?probe=5685e8711f) | Mar 15, 2024 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [898f0686a4](https://linux-hardware.org/?probe=898f0686a4) | Mar 14, 2024 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [fa3d8709e3](https://linux-hardware.org/?probe=fa3d8709e3) | Mar 14, 2024 |
| HUAWEI        | DRR-WXX                     | Tablet      | [a19d185643](https://linux-hardware.org/?probe=a19d185643) | Mar 13, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [fd6b99b446](https://linux-hardware.org/?probe=fd6b99b446) | Mar 12, 2024 |
| Unknown       | Intel X79                   | Desktop     | [e88d0410c8](https://linux-hardware.org/?probe=e88d0410c8) | Mar 11, 2024 |
| ASUSTek       | D300TA                      | Desktop     | [a09321cd27](https://linux-hardware.org/?probe=a09321cd27) | Mar 11, 2024 |
| Dell          | G15 5511                    | Notebook    | [ff19732587](https://linux-hardware.org/?probe=ff19732587) | Mar 11, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [b6909c9a7a](https://linux-hardware.org/?probe=b6909c9a7a) | Mar 10, 2024 |
| HUAWEI        | DRR-WXX                     | Tablet      | [a4b92fe9a7](https://linux-hardware.org/?probe=a4b92fe9a7) | Mar 07, 2024 |
| HP            | Pavilion dv6                | Notebook    | [89a9407fb7](https://linux-hardware.org/?probe=89a9407fb7) | Mar 06, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1502CVA... | Notebook    | [0222a2f98a](https://linux-hardware.org/?probe=0222a2f98a) | Mar 05, 2024 |
| ICL Techno    | F140a                       | Notebook    | [2bdc9718e7](https://linux-hardware.org/?probe=2bdc9718e7) | Mar 03, 2024 |
| Biostar       | TB250-BTC                   | Desktop     | [c5edeef7fe](https://linux-hardware.org/?probe=c5edeef7fe) | Mar 03, 2024 |
| HP            | Pavilion dv6                | Notebook    | [4ed39c3833](https://linux-hardware.org/?probe=4ed39c3833) | Mar 03, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [606e8cea6a](https://linux-hardware.org/?probe=606e8cea6a) | Mar 02, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f082e7f93e](https://linux-hardware.org/?probe=f082e7f93e) | Feb 29, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [4f8e5147ba](https://linux-hardware.org/?probe=4f8e5147ba) | Feb 27, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [d9b2c3a575](https://linux-hardware.org/?probe=d9b2c3a575) | Feb 26, 2024 |
| Aquarius      | AQH310CM                    | Desktop     | [a255e64313](https://linux-hardware.org/?probe=a255e64313) | Feb 22, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [51188483df](https://linux-hardware.org/?probe=51188483df) | Feb 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [0b2da4684e](https://linux-hardware.org/?probe=0b2da4684e) | Feb 21, 2024 |
| TECNO Mobi... | MEGABOOK T14TA              | Notebook    | [9874f5d3c1](https://linux-hardware.org/?probe=9874f5d3c1) | Feb 20, 2024 |
| iRU           | 15TLI                       | Notebook    | [2af6577cf0](https://linux-hardware.org/?probe=2af6577cf0) | Feb 19, 2024 |
| HP            | ProBook 6450b               | Notebook    | [1a4b4a3788](https://linux-hardware.org/?probe=1a4b4a3788) | Feb 17, 2024 |
| HUAWEI        | DRR-WXX                     | Tablet      | [39393dda93](https://linux-hardware.org/?probe=39393dda93) | Feb 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [8317f520c9](https://linux-hardware.org/?probe=8317f520c9) | Feb 16, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [29a77bf074](https://linux-hardware.org/?probe=29a77bf074) | Feb 14, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [61b2aa976f](https://linux-hardware.org/?probe=61b2aa976f) | Feb 13, 2024 |
| HP            | ENVY 6                      | Notebook    | [ccd623bfad](https://linux-hardware.org/?probe=ccd623bfad) | Feb 13, 2024 |
| ASUSTek       | M4A77TD                     | Desktop     | [75afd83494](https://linux-hardware.org/?probe=75afd83494) | Feb 11, 2024 |
| ASRock        | H61M-HVGS                   | Desktop     | [dc3bd18c15](https://linux-hardware.org/?probe=dc3bd18c15) | Feb 09, 2024 |
| Lenovo        | ThinkPad E490 20N80017RT    | Notebook    | [bad3f7f138](https://linux-hardware.org/?probe=bad3f7f138) | Feb 09, 2024 |
| ASUSTek       | PN64                        | Mini pc     | [7cc769d543](https://linux-hardware.org/?probe=7cc769d543) | Feb 08, 2024 |
| Lenovo        | V370 HuronRiver Platform    | Notebook    | [1ad82367ba](https://linux-hardware.org/?probe=1ad82367ba) | Feb 07, 2024 |
| Sony          | VPCSA2Z9R                   | Notebook    | [88e21aee02](https://linux-hardware.org/?probe=88e21aee02) | Feb 06, 2024 |
| Aquarius      | CMP NS685U_4                | Notebook    | [1115097f9a](https://linux-hardware.org/?probe=1115097f9a) | Feb 05, 2024 |
| MSI           | Modern 14 B11MOU            | Notebook    | [a5b3665f64](https://linux-hardware.org/?probe=a5b3665f64) | Feb 02, 2024 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [b30373632d](https://linux-hardware.org/?probe=b30373632d) | Feb 01, 2024 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [21d91717a1](https://linux-hardware.org/?probe=21d91717a1) | Jan 31, 2024 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [8c79f36086](https://linux-hardware.org/?probe=8c79f36086) | Jan 29, 2024 |
| MSI           | MS-B0A21                    | Desktop     | [aebe283d41](https://linux-hardware.org/?probe=aebe283d41) | Jan 26, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [1f374d86d7](https://linux-hardware.org/?probe=1f374d86d7) | Jan 25, 2024 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [6a5faff8dd](https://linux-hardware.org/?probe=6a5faff8dd) | Jan 24, 2024 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [b628671631](https://linux-hardware.org/?probe=b628671631) | Jan 21, 2024 |
| Aquarius      | AQH310CM                    | Desktop     | [6172ad2c5d](https://linux-hardware.org/?probe=6172ad2c5d) | Jan 20, 2024 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [d8c6804097](https://linux-hardware.org/?probe=d8c6804097) | Jan 18, 2024 |
| ASRock        | J3355M                      | Desktop     | [40caff1c3c](https://linux-hardware.org/?probe=40caff1c3c) | Jan 18, 2024 |
| ASUSTek       | Q87M-E                      | Desktop     | [22cbd96a3b](https://linux-hardware.org/?probe=22cbd96a3b) | Jan 11, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [e658ae012b](https://linux-hardware.org/?probe=e658ae012b) | Jan 11, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [e371e895ec](https://linux-hardware.org/?probe=e371e895ec) | Jan 10, 2024 |
| Aquarius      | AQH310CM                    | Desktop     | [64bd83e185](https://linux-hardware.org/?probe=64bd83e185) | Jan 10, 2024 |
| SZMZ          | H61-ME V1.0                 | Desktop     | [4ca9bf9ced](https://linux-hardware.org/?probe=4ca9bf9ced) | Jan 09, 2024 |
| Unknown       | Unknown                     | Notebook    | [737a25372c](https://linux-hardware.org/?probe=737a25372c) | Jan 03, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1372c9e7e6](https://linux-hardware.org/?probe=1372c9e7e6) | Dec 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [a4d9a001ff](https://linux-hardware.org/?probe=a4d9a001ff) | Dec 29, 2023 |
| HP            | ProBook 6460b               | Notebook    | [4a6a6b9b9d](https://linux-hardware.org/?probe=4a6a6b9b9d) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7fdd8a3f38](https://linux-hardware.org/?probe=7fdd8a3f38) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a1fd8cc737](https://linux-hardware.org/?probe=a1fd8cc737) | Dec 26, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8bc6ac892f](https://linux-hardware.org/?probe=8bc6ac892f) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [188dea7b4b](https://linux-hardware.org/?probe=188dea7b4b) | Dec 19, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [cd3471d9e5](https://linux-hardware.org/?probe=cd3471d9e5) | Dec 17, 2023 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [cdebd77402](https://linux-hardware.org/?probe=cdebd77402) | Dec 16, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a53b2d9ba9](https://linux-hardware.org/?probe=a53b2d9ba9) | Dec 15, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [6225f2f85f](https://linux-hardware.org/?probe=6225f2f85f) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [84d4572994](https://linux-hardware.org/?probe=84d4572994) | Dec 12, 2023 |
| Lenovo        | G700                        | Notebook    | [97b63677f6](https://linux-hardware.org/?probe=97b63677f6) | Dec 11, 2023 |
| Gigabyte      | M55S-S3                     | Desktop     | [bf362d71c7](https://linux-hardware.org/?probe=bf362d71c7) | Dec 09, 2023 |
| Lenovo        | 3000 G410                   | Notebook    | [439199aff4](https://linux-hardware.org/?probe=439199aff4) | Dec 04, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [df56e68ebc](https://linux-hardware.org/?probe=df56e68ebc) | Dec 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [0f258ceffb](https://linux-hardware.org/?probe=0f258ceffb) | Dec 04, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [80b6f0b84a](https://linux-hardware.org/?probe=80b6f0b84a) | Dec 02, 2023 |
| ASUSTek       | P5QL-VM EPU                 | Desktop     | [c70c2ff27f](https://linux-hardware.org/?probe=c70c2ff27f) | Dec 01, 2023 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [d7367e7072](https://linux-hardware.org/?probe=d7367e7072) | Nov 30, 2023 |
| MSI           | GT70 2PC                    | Notebook    | [0806985a42](https://linux-hardware.org/?probe=0806985a42) | Nov 29, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [7d7541ceb2](https://linux-hardware.org/?probe=7d7541ceb2) | Nov 29, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [b64fc99109](https://linux-hardware.org/?probe=b64fc99109) | Nov 29, 2023 |
| Lenovo        | G700                        | Notebook    | [3c8ae88b16](https://linux-hardware.org/?probe=3c8ae88b16) | Nov 29, 2023 |
| Graviton      | DMB-A520-MCA01 1.o          | Desktop     | [f989b31edd](https://linux-hardware.org/?probe=f989b31edd) | Nov 28, 2023 |
| Graviton      | DMB-A520-MCA01 1.o          | Desktop     | [1dce0a4738](https://linux-hardware.org/?probe=1dce0a4738) | Nov 28, 2023 |
| ASUSTek       | P5K                         | Desktop     | [d5cb9ac79b](https://linux-hardware.org/?probe=d5cb9ac79b) | Nov 27, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [1af8016aed](https://linux-hardware.org/?probe=1af8016aed) | Nov 27, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [668b258270](https://linux-hardware.org/?probe=668b258270) | Nov 27, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [630d8838dc](https://linux-hardware.org/?probe=630d8838dc) | Nov 27, 2023 |
| MSI           | GT70 2PC                    | Notebook    | [c4589b53bb](https://linux-hardware.org/?probe=c4589b53bb) | Nov 26, 2023 |
| HP            | ProLiant BL460c Gen9        | Server      | [8c522ad38a](https://linux-hardware.org/?probe=8c522ad38a) | Nov 26, 2023 |
| HP            | ProLiant BL460c Gen9        | Server      | [a93d58ad56](https://linux-hardware.org/?probe=a93d58ad56) | Nov 26, 2023 |
| HP            | ProLiant SL230s Gen8        | Desktop     | [a0b680d2ac](https://linux-hardware.org/?probe=a0b680d2ac) | Nov 26, 2023 |
| HP            | ProLiant SL230s Gen8        | Desktop     | [b1d3f26e5d](https://linux-hardware.org/?probe=b1d3f26e5d) | Nov 26, 2023 |
| HP            | ProLiant SL230s Gen8        | Desktop     | [800b1eab76](https://linux-hardware.org/?probe=800b1eab76) | Nov 26, 2023 |
| HP            | ProLiant SL230s Gen8        | Desktop     | [35b226a480](https://linux-hardware.org/?probe=35b226a480) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [72915fd0dd](https://linux-hardware.org/?probe=72915fd0dd) | Nov 26, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [ecf8bf3010](https://linux-hardware.org/?probe=ecf8bf3010) | Nov 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [7078ba99e1](https://linux-hardware.org/?probe=7078ba99e1) | Nov 26, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [8fdcfb665c](https://linux-hardware.org/?probe=8fdcfb665c) | Nov 26, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [3914c7ac4f](https://linux-hardware.org/?probe=3914c7ac4f) | Nov 22, 2023 |
| Lenovo        | No DPK                      | Desktop     | [b569bd1d22](https://linux-hardware.org/?probe=b569bd1d22) | Nov 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [8b59b311ca](https://linux-hardware.org/?probe=8b59b311ca) | Nov 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [7d34e7f4b0](https://linux-hardware.org/?probe=7d34e7f4b0) | Nov 18, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [a0617305eb](https://linux-hardware.org/?probe=a0617305eb) | Nov 17, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [c5890b8a51](https://linux-hardware.org/?probe=c5890b8a51) | Nov 15, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [8d788a9b4d](https://linux-hardware.org/?probe=8d788a9b4d) | Nov 14, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [c04b52c00e](https://linux-hardware.org/?probe=c04b52c00e) | Nov 14, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [2c0511f79f](https://linux-hardware.org/?probe=2c0511f79f) | Nov 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b0bc13f5f8](https://linux-hardware.org/?probe=b0bc13f5f8) | Nov 12, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [59c09c7be1](https://linux-hardware.org/?probe=59c09c7be1) | Nov 11, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b29f519183](https://linux-hardware.org/?probe=b29f519183) | Nov 10, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [cf5ee36e07](https://linux-hardware.org/?probe=cf5ee36e07) | Nov 10, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [fa61fdff34](https://linux-hardware.org/?probe=fa61fdff34) | Nov 09, 2023 |
| Aquarius      | AQX300M                     | Desktop     | [b70a012245](https://linux-hardware.org/?probe=b70a012245) | Nov 01, 2023 |
| Dell          | Inspiron N5050              | Notebook    | [2ec8097b67](https://linux-hardware.org/?probe=2ec8097b67) | Oct 31, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [d7dd5dbdf7](https://linux-hardware.org/?probe=d7dd5dbdf7) | Oct 30, 2023 |
| Acer          | Extensa 2520G               | Notebook    | [bcc4e567f3](https://linux-hardware.org/?probe=bcc4e567f3) | Oct 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [856d9c4a75](https://linux-hardware.org/?probe=856d9c4a75) | Oct 28, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [63c6987bfa](https://linux-hardware.org/?probe=63c6987bfa) | Oct 28, 2023 |
| Huanan        | X99-T8 GAMING V2.0          | Desktop     | [27d22c45c8](https://linux-hardware.org/?probe=27d22c45c8) | Oct 26, 2023 |
| Acer          | Ferrari 3200                | Notebook    | [52f9e06bf9](https://linux-hardware.org/?probe=52f9e06bf9) | Oct 25, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [f8f7f85d08](https://linux-hardware.org/?probe=f8f7f85d08) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | Notebook    | [d0e546f6d6](https://linux-hardware.org/?probe=d0e546f6d6) | Oct 25, 2023 |
| Lenovo        | V580c 20160                 | Notebook    | [178fe3a497](https://linux-hardware.org/?probe=178fe3a497) | Oct 25, 2023 |
| HONOR         | NMH-WDX9                    | Notebook    | [3a0782c335](https://linux-hardware.org/?probe=3a0782c335) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | Notebook    | [1b58a52442](https://linux-hardware.org/?probe=1b58a52442) | Oct 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [1e239308b1](https://linux-hardware.org/?probe=1e239308b1) | Oct 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [125d0eedc8](https://linux-hardware.org/?probe=125d0eedc8) | Oct 21, 2023 |
| HP            | 255 G4                      | Notebook    | [0290beac3f](https://linux-hardware.org/?probe=0290beac3f) | Oct 19, 2023 |
| AZW           | MINI S                      | Desktop     | [0083fabd4c](https://linux-hardware.org/?probe=0083fabd4c) | Oct 15, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [901cc6bd8a](https://linux-hardware.org/?probe=901cc6bd8a) | Oct 14, 2023 |
| Biostar       | H510MHP                     | Desktop     | [1de1d57c17](https://linux-hardware.org/?probe=1de1d57c17) | Oct 13, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [d6cf338b8c](https://linux-hardware.org/?probe=d6cf338b8c) | Oct 12, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [b809251676](https://linux-hardware.org/?probe=b809251676) | Oct 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [52694348d2](https://linux-hardware.org/?probe=52694348d2) | Oct 10, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [7f32c31118](https://linux-hardware.org/?probe=7f32c31118) | Oct 09, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [7623527bdb](https://linux-hardware.org/?probe=7623527bdb) | Oct 08, 2023 |
| ROMBICA       | myBook Eclipse              | Notebook    | [d56fec4995](https://linux-hardware.org/?probe=d56fec4995) | Oct 07, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [1bbe75aa56](https://linux-hardware.org/?probe=1bbe75aa56) | Oct 04, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [61278c0720](https://linux-hardware.org/?probe=61278c0720) | Oct 04, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [06499eec7c](https://linux-hardware.org/?probe=06499eec7c) | Oct 04, 2023 |
| F-PLUS EQU... | Unknown                     | Notebook    | [104a5f30e4](https://linux-hardware.org/?probe=104a5f30e4) | Oct 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [90cb02d71d](https://linux-hardware.org/?probe=90cb02d71d) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | Notebook    | [aa9a99ccb5](https://linux-hardware.org/?probe=aa9a99ccb5) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | Notebook    | [200217831d](https://linux-hardware.org/?probe=200217831d) | Oct 04, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [38db8e9cf2](https://linux-hardware.org/?probe=38db8e9cf2) | Oct 04, 2023 |
| Lenovo        | G700                        | Notebook    | [7090569f96](https://linux-hardware.org/?probe=7090569f96) | Oct 03, 2023 |
| HIPER         | WORKBOOK                    | Notebook    | [902f508256](https://linux-hardware.org/?probe=902f508256) | Oct 03, 2023 |
| Biostar       | H510MHP                     | Desktop     | [1d6b309a9a](https://linux-hardware.org/?probe=1d6b309a9a) | Oct 02, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [b2a213cc18](https://linux-hardware.org/?probe=b2a213cc18) | Sep 30, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [60e32143f5](https://linux-hardware.org/?probe=60e32143f5) | Sep 29, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [7cc521d927](https://linux-hardware.org/?probe=7cc521d927) | Sep 29, 2023 |
| ROMBICA       | myBook Eclipse              | Notebook    | [004e1dc4fd](https://linux-hardware.org/?probe=004e1dc4fd) | Sep 28, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [2ac0204275](https://linux-hardware.org/?probe=2ac0204275) | Sep 28, 2023 |
| Pegatron      | IPMSB-H61                   | Desktop     | [d0e64d2ebf](https://linux-hardware.org/?probe=d0e64d2ebf) | Sep 28, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [1458dfe403](https://linux-hardware.org/?probe=1458dfe403) | Sep 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [8b0d086b89](https://linux-hardware.org/?probe=8b0d086b89) | Sep 27, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [45d07666f9](https://linux-hardware.org/?probe=45d07666f9) | Sep 26, 2023 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [a0fa16f85c](https://linux-hardware.org/?probe=a0fa16f85c) | Sep 25, 2023 |
| Kraftway      | ACCORD                      | Notebook    | [df4d5654d5](https://linux-hardware.org/?probe=df4d5654d5) | Sep 21, 2023 |
| iRU           | 17ALC                       | Notebook    | [2d0b23c813](https://linux-hardware.org/?probe=2d0b23c813) | Sep 18, 2023 |
| Lenovo        | ThinkPad X250 20CMS0A200    | Notebook    | [43df4bd3f3](https://linux-hardware.org/?probe=43df4bd3f3) | Sep 18, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [5e6499e724](https://linux-hardware.org/?probe=5e6499e724) | Sep 17, 2023 |
| HP            | 85A2                        | All in one  | [f1a642ea93](https://linux-hardware.org/?probe=f1a642ea93) | Sep 14, 2023 |
| ASRock        | K10N78D                     | Desktop     | [fa2852026b](https://linux-hardware.org/?probe=fa2852026b) | Sep 13, 2023 |
| ASRock        | K10N78D                     | Desktop     | [adf8e09915](https://linux-hardware.org/?probe=adf8e09915) | Sep 13, 2023 |
| on Gravito... | Graviton M42i               | All in one  | [3d738e533d](https://linux-hardware.org/?probe=3d738e533d) | Sep 12, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [53cdc3e4f0](https://linux-hardware.org/?probe=53cdc3e4f0) | Sep 12, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [5e87de3be1](https://linux-hardware.org/?probe=5e87de3be1) | Sep 11, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [d83ba68fcb](https://linux-hardware.org/?probe=d83ba68fcb) | Sep 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [439b7547a5](https://linux-hardware.org/?probe=439b7547a5) | Sep 04, 2023 |
| Acer          | Aspire 3690                 | Notebook    | [503b015d34](https://linux-hardware.org/?probe=503b015d34) | Sep 04, 2023 |
| ASUSTek       | V221IC                      | All in one  | [1abad6ed2e](https://linux-hardware.org/?probe=1abad6ed2e) | Sep 03, 2023 |
| ASUSTek       | V221IC                      | All in one  | [06240bab5b](https://linux-hardware.org/?probe=06240bab5b) | Sep 03, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6b33c9cb36](https://linux-hardware.org/?probe=6b33c9cb36) | Sep 02, 2023 |
| Intel         | B75                         | Desktop     | [55695d0962](https://linux-hardware.org/?probe=55695d0962) | Aug 31, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [b196e48c97](https://linux-hardware.org/?probe=b196e48c97) | Aug 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [861e741d6a](https://linux-hardware.org/?probe=861e741d6a) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [09ed405682](https://linux-hardware.org/?probe=09ed405682) | Aug 29, 2023 |
| Intel         | SKYBAY                      | Desktop     | [59cfa4ea58](https://linux-hardware.org/?probe=59cfa4ea58) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [ad478d48ad](https://linux-hardware.org/?probe=ad478d48ad) | Aug 27, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [d8f8a287e6](https://linux-hardware.org/?probe=d8f8a287e6) | Aug 27, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [dfc1f52af5](https://linux-hardware.org/?probe=dfc1f52af5) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1510eba46f](https://linux-hardware.org/?probe=1510eba46f) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [cc7efa7eba](https://linux-hardware.org/?probe=cc7efa7eba) | Aug 11, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [18ace46778](https://linux-hardware.org/?probe=18ace46778) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a43111576a](https://linux-hardware.org/?probe=a43111576a) | Aug 09, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [4b7e9a8b93](https://linux-hardware.org/?probe=4b7e9a8b93) | Aug 09, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [71b00682fc](https://linux-hardware.org/?probe=71b00682fc) | Aug 07, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [baf3a83d91](https://linux-hardware.org/?probe=baf3a83d91) | Aug 06, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [35853f5b92](https://linux-hardware.org/?probe=35853f5b92) | Aug 04, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [163708151e](https://linux-hardware.org/?probe=163708151e) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [28007801d5](https://linux-hardware.org/?probe=28007801d5) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [5e3a46dee8](https://linux-hardware.org/?probe=5e3a46dee8) | Aug 03, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [c12e9ed368](https://linux-hardware.org/?probe=c12e9ed368) | Aug 02, 2023 |
| ASUSTek       | P7F-M                       | Desktop     | [5c04bf12d0](https://linux-hardware.org/?probe=5c04bf12d0) | Aug 02, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [1096cf2959](https://linux-hardware.org/?probe=1096cf2959) | Jul 31, 2023 |
| HP            | 0AA8h                       | Desktop     | [76dbb0d0a3](https://linux-hardware.org/?probe=76dbb0d0a3) | Jul 31, 2023 |
| Acer          | Aspire V3-551G              | Notebook    | [a90eeb2fa3](https://linux-hardware.org/?probe=a90eeb2fa3) | Jul 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [c3523b3823](https://linux-hardware.org/?probe=c3523b3823) | Jul 29, 2023 |
| ASRock        | G41M-VS2                    | Desktop     | [74564d3418](https://linux-hardware.org/?probe=74564d3418) | Jul 28, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [543257c1b1](https://linux-hardware.org/?probe=543257c1b1) | Jul 25, 2023 |
| INSYS         | IP1-XN23                    | Notebook    | [4212432f00](https://linux-hardware.org/?probe=4212432f00) | Jul 24, 2023 |
| ASUSTek       | X55A                        | Notebook    | [6818ec7338](https://linux-hardware.org/?probe=6818ec7338) | Jul 21, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [6284551b74](https://linux-hardware.org/?probe=6284551b74) | Jul 20, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [4b683fcc22](https://linux-hardware.org/?probe=4b683fcc22) | Jul 18, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [0cf82c02d3](https://linux-hardware.org/?probe=0cf82c02d3) | Jul 18, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [da27044389](https://linux-hardware.org/?probe=da27044389) | Jul 17, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [a24026d3c6](https://linux-hardware.org/?probe=a24026d3c6) | Jul 14, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| Graviton      | N15I-T                      | Notebook    | [b457883ad3](https://linux-hardware.org/?probe=b457883ad3) | Jul 04, 2023 |
| Graviton      | N15I-T                      | Notebook    | [305390c16e](https://linux-hardware.org/?probe=305390c16e) | Jul 03, 2023 |
| Gigabyte      | MRHM3AP                     | Desktop     | [2d91c7c05a](https://linux-hardware.org/?probe=2d91c7c05a) | Jun 28, 2023 |
| Gigabyte      | MRHM3AP                     | Desktop     | [7007bb2db5](https://linux-hardware.org/?probe=7007bb2db5) | Jun 27, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [a2dbae939a](https://linux-hardware.org/?probe=a2dbae939a) | Jun 27, 2023 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [1f7adfe250](https://linux-hardware.org/?probe=1f7adfe250) | Jun 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [91bb626fa8](https://linux-hardware.org/?probe=91bb626fa8) | Jun 26, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [929fce049c](https://linux-hardware.org/?probe=929fce049c) | Jun 26, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [308ee62292](https://linux-hardware.org/?probe=308ee62292) | Jun 21, 2023 |
| ASUSTek       | V221IC                      | All in one  | [c54f07785e](https://linux-hardware.org/?probe=c54f07785e) | Jun 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0c4198042a](https://linux-hardware.org/?probe=0c4198042a) | Jun 18, 2023 |
| Alienware     | M14xR2                      | Notebook    | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [fb399aebb6](https://linux-hardware.org/?probe=fb399aebb6) | Jun 11, 2023 |
| Biostar       | H610MH                      | Desktop     | [a2c82f65b6](https://linux-hardware.org/?probe=a2c82f65b6) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [6d434209eb](https://linux-hardware.org/?probe=6d434209eb) | Jun 07, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [0d46480e90](https://linux-hardware.org/?probe=0d46480e90) | Jun 06, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [5a66eed08e](https://linux-hardware.org/?probe=5a66eed08e) | Jun 05, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [3ed00534ed](https://linux-hardware.org/?probe=3ed00534ed) | Jun 05, 2023 |
| HP            | Mini 210-1000               | Notebook    | [96f41af422](https://linux-hardware.org/?probe=96f41af422) | Jun 05, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [e4b62aaf28](https://linux-hardware.org/?probe=e4b62aaf28) | Jun 05, 2023 |
| ICL           | RAYbook Si1407              | Notebook    | [5956bb96ff](https://linux-hardware.org/?probe=5956bb96ff) | May 30, 2023 |
| Timi          | TM1701                      | Notebook    | [94105aa58f](https://linux-hardware.org/?probe=94105aa58f) | May 26, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [e34e6ab643](https://linux-hardware.org/?probe=e34e6ab643) | May 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [41f9a8d4b1](https://linux-hardware.org/?probe=41f9a8d4b1) | May 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [91ad90fd67](https://linux-hardware.org/?probe=91ad90fd67) | May 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9c184f4251](https://linux-hardware.org/?probe=9c184f4251) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [39fa0ce7e9](https://linux-hardware.org/?probe=39fa0ce7e9) | May 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [1bfbf34771](https://linux-hardware.org/?probe=1bfbf34771) | May 16, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d9cac69c4c](https://linux-hardware.org/?probe=d9cac69c4c) | May 16, 2023 |
| HP            | 8374 1100                   | All in one  | [2e31c0e1d5](https://linux-hardware.org/?probe=2e31c0e1d5) | May 12, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [0959f95f56](https://linux-hardware.org/?probe=0959f95f56) | May 12, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [b502077711](https://linux-hardware.org/?probe=b502077711) | May 12, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [ab733d41de](https://linux-hardware.org/?probe=ab733d41de) | May 12, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [dea48fc3fa](https://linux-hardware.org/?probe=dea48fc3fa) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [f0fbd1eda9](https://linux-hardware.org/?probe=f0fbd1eda9) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [096f897a80](https://linux-hardware.org/?probe=096f897a80) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [7a1acf3851](https://linux-hardware.org/?probe=7a1acf3851) | May 11, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [3c0893a822](https://linux-hardware.org/?probe=3c0893a822) | May 11, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [848dc775e0](https://linux-hardware.org/?probe=848dc775e0) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [ce24dc022b](https://linux-hardware.org/?probe=ce24dc022b) | May 10, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [1d50da2ba5](https://linux-hardware.org/?probe=1d50da2ba5) | May 05, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [3ed55d530a](https://linux-hardware.org/?probe=3ed55d530a) | May 04, 2023 |
| F-PLUS EQU... | FNB-140-P1                  | Notebook    | [f78d6739f5](https://linux-hardware.org/?probe=f78d6739f5) | May 03, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [67b2580836](https://linux-hardware.org/?probe=67b2580836) | May 03, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [1ba45b2b8f](https://linux-hardware.org/?probe=1ba45b2b8f) | May 03, 2023 |
| HP            | 8374 1100                   | All in one  | [68015b73d0](https://linux-hardware.org/?probe=68015b73d0) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a69dab4a99](https://linux-hardware.org/?probe=a69dab4a99) | Apr 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [583e105bbf](https://linux-hardware.org/?probe=583e105bbf) | Apr 28, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [9dfeeff104](https://linux-hardware.org/?probe=9dfeeff104) | Apr 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [37534616d7](https://linux-hardware.org/?probe=37534616d7) | Apr 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [4f2ffb4273](https://linux-hardware.org/?probe=4f2ffb4273) | Apr 26, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [0430d21b33](https://linux-hardware.org/?probe=0430d21b33) | Apr 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [2f1b310ca2](https://linux-hardware.org/?probe=2f1b310ca2) | Apr 21, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [a61ffc94f5](https://linux-hardware.org/?probe=a61ffc94f5) | Apr 18, 2023 |
| Unknown       | DMB-A520-MCA01              | Desktop     | [d0c1433d54](https://linux-hardware.org/?probe=d0c1433d54) | Apr 18, 2023 |
| Intel         | SKYBAY                      | Desktop     | [ec2b541d85](https://linux-hardware.org/?probe=ec2b541d85) | Apr 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [322f62ae77](https://linux-hardware.org/?probe=322f62ae77) | Apr 11, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [3504e8b3bd](https://linux-hardware.org/?probe=3504e8b3bd) | Apr 11, 2023 |
| Aquarius      | Cmp NS483                   | Convertible | [2a8ffe8e0d](https://linux-hardware.org/?probe=2a8ffe8e0d) | Apr 11, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [720eed31f6](https://linux-hardware.org/?probe=720eed31f6) | Apr 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [5fddb7053d](https://linux-hardware.org/?probe=5fddb7053d) | Apr 07, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [e734b33010](https://linux-hardware.org/?probe=e734b33010) | Apr 07, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [b0f85c7afd](https://linux-hardware.org/?probe=b0f85c7afd) | Apr 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [67615ec9ff](https://linux-hardware.org/?probe=67615ec9ff) | Apr 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bec5bda3bd](https://linux-hardware.org/?probe=bec5bda3bd) | Apr 05, 2023 |
| Timi          | TM1701                      | Notebook    | [5fc6e30961](https://linux-hardware.org/?probe=5fc6e30961) | Apr 04, 2023 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [68a8171c0a](https://linux-hardware.org/?probe=68a8171c0a) | Mar 31, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [9ec66a8f48](https://linux-hardware.org/?probe=9ec66a8f48) | Mar 31, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [45162c9123](https://linux-hardware.org/?probe=45162c9123) | Mar 30, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [c19cd604b3](https://linux-hardware.org/?probe=c19cd604b3) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | Notebook    | [fc942702db](https://linux-hardware.org/?probe=fc942702db) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | Notebook    | [ab5d4b339b](https://linux-hardware.org/?probe=ab5d4b339b) | Mar 30, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [69abc76758](https://linux-hardware.org/?probe=69abc76758) | Mar 29, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [9d7a43d81f](https://linux-hardware.org/?probe=9d7a43d81f) | Mar 29, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [60191a33b8](https://linux-hardware.org/?probe=60191a33b8) | Mar 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [b56bf816d5](https://linux-hardware.org/?probe=b56bf816d5) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [88a5d2eb30](https://linux-hardware.org/?probe=88a5d2eb30) | Mar 23, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [123e95cee1](https://linux-hardware.org/?probe=123e95cee1) | Mar 22, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [430f11129e](https://linux-hardware.org/?probe=430f11129e) | Mar 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [5d06af8741](https://linux-hardware.org/?probe=5d06af8741) | Mar 22, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9fbef1354b](https://linux-hardware.org/?probe=9fbef1354b) | Mar 21, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [24b07c4402](https://linux-hardware.org/?probe=24b07c4402) | Mar 21, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [8e021e8177](https://linux-hardware.org/?probe=8e021e8177) | Mar 21, 2023 |
| Intel         | NUC7JYB M37329-601          | Mini pc     | [b9649aaa48](https://linux-hardware.org/?probe=b9649aaa48) | Mar 21, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [1b993725aa](https://linux-hardware.org/?probe=1b993725aa) | Mar 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [743d04e5fc](https://linux-hardware.org/?probe=743d04e5fc) | Mar 16, 2023 |
| Biostar       | TB250-BTC                   | Desktop     | [59d148cedc](https://linux-hardware.org/?probe=59d148cedc) | Mar 11, 2023 |
| Gigabyte      | 965GM-S2                    | Desktop     | [8a58676b8d](https://linux-hardware.org/?probe=8a58676b8d) | Mar 10, 2023 |
| Gigabyte      | 965GM-S2                    | Desktop     | [e514c2892e](https://linux-hardware.org/?probe=e514c2892e) | Mar 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [9e620a10f2](https://linux-hardware.org/?probe=9e620a10f2) | Mar 09, 2023 |
| Intel         | SKYBAY                      | Desktop     | [226b8468d4](https://linux-hardware.org/?probe=226b8468d4) | Mar 09, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d62a6bc830](https://linux-hardware.org/?probe=d62a6bc830) | Mar 07, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [5fb80da27b](https://linux-hardware.org/?probe=5fb80da27b) | Mar 07, 2023 |
| ICL           | H310SB-TM                   | All in one  | [63dbb9394e](https://linux-hardware.org/?probe=63dbb9394e) | Mar 07, 2023 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [4b3689dc5c](https://linux-hardware.org/?probe=4b3689dc5c) | Mar 05, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [2e8dc3ddd2](https://linux-hardware.org/?probe=2e8dc3ddd2) | Mar 03, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [dcc115a880](https://linux-hardware.org/?probe=dcc115a880) | Mar 02, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [29df87f87f](https://linux-hardware.org/?probe=29df87f87f) | Feb 28, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [5ab1863f2b](https://linux-hardware.org/?probe=5ab1863f2b) | Feb 28, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [b91dfc602e](https://linux-hardware.org/?probe=b91dfc602e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [f8dd8a7ee9](https://linux-hardware.org/?probe=f8dd8a7ee9) | Feb 18, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [d15806c6c2](https://linux-hardware.org/?probe=d15806c6c2) | Feb 15, 2023 |
| MSI           | MS-7357                     | Desktop     | [84cadfbabc](https://linux-hardware.org/?probe=84cadfbabc) | Feb 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9606f5546e](https://linux-hardware.org/?probe=9606f5546e) | Feb 15, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [d7f1d6a937](https://linux-hardware.org/?probe=d7f1d6a937) | Feb 14, 2023 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [a9267dffac](https://linux-hardware.org/?probe=a9267dffac) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [516a173dcb](https://linux-hardware.org/?probe=516a173dcb) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [2809288f6f](https://linux-hardware.org/?probe=2809288f6f) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [56ecf82de8](https://linux-hardware.org/?probe=56ecf82de8) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [95af064bd1](https://linux-hardware.org/?probe=95af064bd1) | Feb 13, 2023 |
| ASUSTek       | P5B-E                       | Desktop     | [92bf62be3c](https://linux-hardware.org/?probe=92bf62be3c) | Feb 11, 2023 |
| Acer          | RS880M05                    | Desktop     | [c585589925](https://linux-hardware.org/?probe=c585589925) | Feb 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | Notebook    | [8fb9d5ae65](https://linux-hardware.org/?probe=8fb9d5ae65) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | Notebook    | [ced0a536d0](https://linux-hardware.org/?probe=ced0a536d0) | Feb 06, 2023 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [788d1d408b](https://linux-hardware.org/?probe=788d1d408b) | Feb 06, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [97252e199d](https://linux-hardware.org/?probe=97252e199d) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [95dac05397](https://linux-hardware.org/?probe=95dac05397) | Jan 31, 2023 |
| ASUSTek       | N53Ta                       | Notebook    | [30131c7409](https://linux-hardware.org/?probe=30131c7409) | Jan 31, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [ab13127567](https://linux-hardware.org/?probe=ab13127567) | Jan 29, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [86e493728f](https://linux-hardware.org/?probe=86e493728f) | Jan 27, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [560cc09a5a](https://linux-hardware.org/?probe=560cc09a5a) | Jan 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [82e558cf16](https://linux-hardware.org/?probe=82e558cf16) | Jan 25, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [347446f16f](https://linux-hardware.org/?probe=347446f16f) | Jan 25, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [831e02a268](https://linux-hardware.org/?probe=831e02a268) | Jan 24, 2023 |
| Lenovo        | B560                        | Notebook    | [b474faa82b](https://linux-hardware.org/?probe=b474faa82b) | Jan 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [0d2187e1bd](https://linux-hardware.org/?probe=0d2187e1bd) | Jan 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [1781c6451f](https://linux-hardware.org/?probe=1781c6451f) | Jan 23, 2023 |
| Acer          | Aspire E1-530G              | Notebook    | [b4f6567b3f](https://linux-hardware.org/?probe=b4f6567b3f) | Jan 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [43b8eec1e2](https://linux-hardware.org/?probe=43b8eec1e2) | Jan 18, 2023 |
| Eii           | P612F                       | All in one  | [29acda8f67](https://linux-hardware.org/?probe=29acda8f67) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [bb4c5c0f73](https://linux-hardware.org/?probe=bb4c5c0f73) | Jan 18, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [c1c0617217](https://linux-hardware.org/?probe=c1c0617217) | Jan 17, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [c531fbad47](https://linux-hardware.org/?probe=c531fbad47) | Jan 14, 2023 |
| Timi          | Redmi Book Pro 14S          | Notebook    | [911075716c](https://linux-hardware.org/?probe=911075716c) | Jan 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [fdf24274c5](https://linux-hardware.org/?probe=fdf24274c5) | Jan 13, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [8228b94c50](https://linux-hardware.org/?probe=8228b94c50) | Jan 11, 2023 |
| Yadro         | YadroB560                   | Desktop     | [9d45ee1c8c](https://linux-hardware.org/?probe=9d45ee1c8c) | Jan 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [45ea0a8983](https://linux-hardware.org/?probe=45ea0a8983) | Jan 11, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [3000408196](https://linux-hardware.org/?probe=3000408196) | Jan 11, 2023 |
| Intel         | SKYBAY                      | Desktop     | [b6402cdd5e](https://linux-hardware.org/?probe=b6402cdd5e) | Jan 11, 2023 |
| Intel         | SKYBAY                      | Desktop     | [c896f4d5ee](https://linux-hardware.org/?probe=c896f4d5ee) | Jan 11, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [808e7e41c5](https://linux-hardware.org/?probe=808e7e41c5) | Jan 10, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [914e3f30cc](https://linux-hardware.org/?probe=914e3f30cc) | Jan 08, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [bed374999d](https://linux-hardware.org/?probe=bed374999d) | Jan 06, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [2952e11cdb](https://linux-hardware.org/?probe=2952e11cdb) | Jan 01, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [6aaaf2e570](https://linux-hardware.org/?probe=6aaaf2e570) | Dec 28, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [4d7e3586e2](https://linux-hardware.org/?probe=4d7e3586e2) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0c71831ff4](https://linux-hardware.org/?probe=0c71831ff4) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [50c31f6b47](https://linux-hardware.org/?probe=50c31f6b47) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [190bb1537d](https://linux-hardware.org/?probe=190bb1537d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0574ad6c44](https://linux-hardware.org/?probe=0574ad6c44) | Dec 26, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [9a8967485d](https://linux-hardware.org/?probe=9a8967485d) | Dec 26, 2022 |
| LTD Delovo... | 15Y                         | Notebook    | [286aa3fb96](https://linux-hardware.org/?probe=286aa3fb96) | Dec 25, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [f9b6dc975b](https://linux-hardware.org/?probe=f9b6dc975b) | Dec 23, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [c93f96de9e](https://linux-hardware.org/?probe=c93f96de9e) | Dec 22, 2022 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [0456782550](https://linux-hardware.org/?probe=0456782550) | Dec 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [5ad56cab50](https://linux-hardware.org/?probe=5ad56cab50) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [e06ebbd650](https://linux-hardware.org/?probe=e06ebbd650) | Dec 19, 2022 |
| Pegatron      | C15B                        | Notebook    | [865b882e8a](https://linux-hardware.org/?probe=865b882e8a) | Dec 18, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [00dd0bc59e](https://linux-hardware.org/?probe=00dd0bc59e) | Dec 18, 2022 |
| Aquarius      | Pro, Std, Elt Series        | Notebook    | [59b7fca136](https://linux-hardware.org/?probe=59b7fca136) | Dec 18, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [afd0404144](https://linux-hardware.org/?probe=afd0404144) | Dec 17, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [e7e9b42211](https://linux-hardware.org/?probe=e7e9b42211) | Dec 16, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [26bb5af1a4](https://linux-hardware.org/?probe=26bb5af1a4) | Dec 16, 2022 |
| Irbis         | NB264                       | Notebook    | [14764ec4e5](https://linux-hardware.org/?probe=14764ec4e5) | Dec 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [24bebac773](https://linux-hardware.org/?probe=24bebac773) | Dec 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [643cb41a84](https://linux-hardware.org/?probe=643cb41a84) | Dec 15, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [25e63313c0](https://linux-hardware.org/?probe=25e63313c0) | Dec 13, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [b58d61f85f](https://linux-hardware.org/?probe=b58d61f85f) | Dec 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [2f5b88399a](https://linux-hardware.org/?probe=2f5b88399a) | Dec 13, 2022 |
| Graviton      | DMB-H610-TMI01              | All in one  | [0b2b77d521](https://linux-hardware.org/?probe=0b2b77d521) | Dec 12, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [af22c1db61](https://linux-hardware.org/?probe=af22c1db61) | Dec 08, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [317fdfd70b](https://linux-hardware.org/?probe=317fdfd70b) | Dec 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [619fd919a1](https://linux-hardware.org/?probe=619fd919a1) | Dec 07, 2022 |
| HP            | 255 G4                      | Notebook    | [33b2fb7f31](https://linux-hardware.org/?probe=33b2fb7f31) | Nov 30, 2022 |
| Pegatron      | C15B                        | Notebook    | [92271ab582](https://linux-hardware.org/?probe=92271ab582) | Nov 30, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [4dbcbc3b7a](https://linux-hardware.org/?probe=4dbcbc3b7a) | Nov 30, 2022 |
| Samsung       | R560                        | Notebook    | [936ae4b775](https://linux-hardware.org/?probe=936ae4b775) | Nov 29, 2022 |
| Timi          | TM1701                      | Notebook    | [64ee057496](https://linux-hardware.org/?probe=64ee057496) | Nov 28, 2022 |
| Acer          | TravelMate 4200             | Notebook    | [14b60c4afa](https://linux-hardware.org/?probe=14b60c4afa) | Nov 26, 2022 |
| MSI           | J1800I                      | Desktop     | [156269ae8c](https://linux-hardware.org/?probe=156269ae8c) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [52da79e88f](https://linux-hardware.org/?probe=52da79e88f) | Nov 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4a758bfcc8](https://linux-hardware.org/?probe=4a758bfcc8) | Nov 25, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0736d8a48f](https://linux-hardware.org/?probe=0736d8a48f) | Nov 24, 2022 |
| Panasonic     | CF-C2CH2CBMG                | Notebook    | [cf87bdba01](https://linux-hardware.org/?probe=cf87bdba01) | Nov 24, 2022 |
| Acer          | Aspire 5940                 | Notebook    | [33325564e7](https://linux-hardware.org/?probe=33325564e7) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | Notebook    | [27c34cd9df](https://linux-hardware.org/?probe=27c34cd9df) | Nov 22, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [bd18dfe05f](https://linux-hardware.org/?probe=bd18dfe05f) | Nov 20, 2022 |
| Intel         | H510SB-TM v2.0              | All in one  | [ece886e874](https://linux-hardware.org/?probe=ece886e874) | Nov 17, 2022 |
| Timi          | TM1701                      | Notebook    | [e77b655bb8](https://linux-hardware.org/?probe=e77b655bb8) | Nov 16, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [72ebef559b](https://linux-hardware.org/?probe=72ebef559b) | Nov 16, 2022 |
| HP            | Mini 110-3700               | Notebook    | [8ca62a1880](https://linux-hardware.org/?probe=8ca62a1880) | Nov 15, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [1a09a9bb5c](https://linux-hardware.org/?probe=1a09a9bb5c) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6e9bc709d9](https://linux-hardware.org/?probe=6e9bc709d9) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49162725d5](https://linux-hardware.org/?probe=49162725d5) | Nov 13, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [65226dd80a](https://linux-hardware.org/?probe=65226dd80a) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [a25dd1174c](https://linux-hardware.org/?probe=a25dd1174c) | Nov 11, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [b5965fce49](https://linux-hardware.org/?probe=b5965fce49) | Nov 11, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [d3d30c473e](https://linux-hardware.org/?probe=d3d30c473e) | Nov 10, 2022 |
| Gigabyte      | 8I915GMF                    | Desktop     | [76f5cb17ad](https://linux-hardware.org/?probe=76f5cb17ad) | Nov 10, 2022 |
| Acer          | TravelMate 6292             | Notebook    | [c7dcad2d0f](https://linux-hardware.org/?probe=c7dcad2d0f) | Nov 10, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [cc051268d8](https://linux-hardware.org/?probe=cc051268d8) | Nov 05, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [d409557d4b](https://linux-hardware.org/?probe=d409557d4b) | Nov 03, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [8983159779](https://linux-hardware.org/?probe=8983159779) | Oct 30, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [b388ac6776](https://linux-hardware.org/?probe=b388ac6776) | Oct 27, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [89e7931244](https://linux-hardware.org/?probe=89e7931244) | Oct 27, 2022 |
| Intel         | D34010WYK H14771-301        | Desktop     | [cea24a780a](https://linux-hardware.org/?probe=cea24a780a) | Oct 26, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a876af89ec](https://linux-hardware.org/?probe=a876af89ec) | Oct 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [25db5739b7](https://linux-hardware.org/?probe=25db5739b7) | Oct 24, 2022 |
| Toshiba       | dynabook Satellite T87/8... | Notebook    | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-301        | Desktop     | [18d8d35afa](https://linux-hardware.org/?probe=18d8d35afa) | Oct 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bfb6c03047](https://linux-hardware.org/?probe=bfb6c03047) | Oct 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae13c0bb6b](https://linux-hardware.org/?probe=ae13c0bb6b) | Oct 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [4820b94a4a](https://linux-hardware.org/?probe=4820b94a4a) | Oct 18, 2022 |
| Samsung       | R509                        | Notebook    | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [73145a883c](https://linux-hardware.org/?probe=73145a883c) | Oct 17, 2022 |
| Huanan        | H97-ZD3 V2.0                | Desktop     | [d0d194fbdc](https://linux-hardware.org/?probe=d0d194fbdc) | Oct 15, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [355974871d](https://linux-hardware.org/?probe=355974871d) | Oct 12, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [a28efd61d1](https://linux-hardware.org/?probe=a28efd61d1) | Oct 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fd73da4fee](https://linux-hardware.org/?probe=fd73da4fee) | Oct 11, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [02395d2c6f](https://linux-hardware.org/?probe=02395d2c6f) | Oct 07, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [79b160283f](https://linux-hardware.org/?probe=79b160283f) | Oct 05, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [8e3ee86b79](https://linux-hardware.org/?probe=8e3ee86b79) | Oct 05, 2022 |
| ASUSTek       | D300TA                      | Desktop     | [7c175e4db4](https://linux-hardware.org/?probe=7c175e4db4) | Oct 03, 2022 |
| Acer          | AOA150                      | Notebook    | [b8780da9ef](https://linux-hardware.org/?probe=b8780da9ef) | Oct 02, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c1c976ba69](https://linux-hardware.org/?probe=c1c976ba69) | Sep 27, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [b47b842550](https://linux-hardware.org/?probe=b47b842550) | Sep 25, 2022 |
| Acer          | AO722                       | Notebook    | [f2c6378873](https://linux-hardware.org/?probe=f2c6378873) | Sep 25, 2022 |
| ICL           | NLx0MU                      | Notebook    | [d8e7f39201](https://linux-hardware.org/?probe=d8e7f39201) | Sep 23, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [226bbaa11e](https://linux-hardware.org/?probe=226bbaa11e) | Sep 23, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [34db101d55](https://linux-hardware.org/?probe=34db101d55) | Sep 22, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [65a37e4802](https://linux-hardware.org/?probe=65a37e4802) | Sep 19, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [b8609443fe](https://linux-hardware.org/?probe=b8609443fe) | Sep 17, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [8391d18411](https://linux-hardware.org/?probe=8391d18411) | Sep 05, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [aee6f1bdbb](https://linux-hardware.org/?probe=aee6f1bdbb) | Sep 05, 2022 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [0384b171c7](https://linux-hardware.org/?probe=0384b171c7) | Sep 03, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [899d0fc360](https://linux-hardware.org/?probe=899d0fc360) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [7c97a519fe](https://linux-hardware.org/?probe=7c97a519fe) | Aug 26, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [ac9bf296d8](https://linux-hardware.org/?probe=ac9bf296d8) | Aug 25, 2022 |
| IP3 Tech      | TGLUP3                      | Notebook    | [a4f803f8a1](https://linux-hardware.org/?probe=a4f803f8a1) | Aug 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [57d5700736](https://linux-hardware.org/?probe=57d5700736) | Aug 21, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [cfa6cef53d](https://linux-hardware.org/?probe=cfa6cef53d) | Aug 18, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [840fa733f4](https://linux-hardware.org/?probe=840fa733f4) | Aug 18, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [a6a798ce96](https://linux-hardware.org/?probe=a6a798ce96) | Aug 16, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [3a9d682c2f](https://linux-hardware.org/?probe=3a9d682c2f) | Aug 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [315c1df30c](https://linux-hardware.org/?probe=315c1df30c) | Aug 16, 2022 |
| HP            | Pavilion g7                 | Notebook    | [93adb73648](https://linux-hardware.org/?probe=93adb73648) | Aug 08, 2022 |
| HP            | 83EB                        | All in one  | [beb4a8d108](https://linux-hardware.org/?probe=beb4a8d108) | Aug 03, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [7d9b8e0f96](https://linux-hardware.org/?probe=7d9b8e0f96) | Aug 01, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [982a6e3241](https://linux-hardware.org/?probe=982a6e3241) | Jul 30, 2022 |
| ICL           | NLx0MU                      | Notebook    | [af0922946a](https://linux-hardware.org/?probe=af0922946a) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f870753f2f](https://linux-hardware.org/?probe=f870753f2f) | Jul 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [42a2639fcf](https://linux-hardware.org/?probe=42a2639fcf) | Jul 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [337e6e0efa](https://linux-hardware.org/?probe=337e6e0efa) | Jul 18, 2022 |
| OEM           | KX-18 V1.0                  | Desktop     | [a68e653aa9](https://linux-hardware.org/?probe=a68e653aa9) | Jul 14, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [5df194f626](https://linux-hardware.org/?probe=5df194f626) | Jul 13, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [c8051cd18e](https://linux-hardware.org/?probe=c8051cd18e) | Jul 13, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [2faa8bf726](https://linux-hardware.org/?probe=2faa8bf726) | Jul 12, 2022 |
| HP            | ProBook 4710s               | Notebook    | [4fe41da4e8](https://linux-hardware.org/?probe=4fe41da4e8) | Jul 09, 2022 |
| HP            | ProBook 4710s               | Notebook    | [932822fdc7](https://linux-hardware.org/?probe=932822fdc7) | Jul 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5d2d940ec2](https://linux-hardware.org/?probe=5d2d940ec2) | Jul 07, 2022 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [7a95d588c4](https://linux-hardware.org/?probe=7a95d588c4) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a8888a6627](https://linux-hardware.org/?probe=a8888a6627) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b3da1e4cdb](https://linux-hardware.org/?probe=b3da1e4cdb) | Jul 05, 2022 |
| Intel         | H510SB-TM v2.0              | All in one  | [8598f1f5ee](https://linux-hardware.org/?probe=8598f1f5ee) | Jun 30, 2022 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [7411d7a561](https://linux-hardware.org/?probe=7411d7a561) | Jun 23, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2724c1558a](https://linux-hardware.org/?probe=2724c1558a) | Jun 20, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [8fe4a74fa3](https://linux-hardware.org/?probe=8fe4a74fa3) | Jun 10, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [31ab5150ea](https://linux-hardware.org/?probe=31ab5150ea) | Jun 06, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4fa81ba66a](https://linux-hardware.org/?probe=4fa81ba66a) | Jun 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [fb935ea1d0](https://linux-hardware.org/?probe=fb935ea1d0) | Jun 03, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [7bfddcecee](https://linux-hardware.org/?probe=7bfddcecee) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [acc0a6ae9c](https://linux-hardware.org/?probe=acc0a6ae9c) | May 31, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [4ad9ca01bd](https://linux-hardware.org/?probe=4ad9ca01bd) | May 31, 2022 |
| Panasonic     | CF-20-1                     | Notebook    | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [7d7a4c7536](https://linux-hardware.org/?probe=7d7a4c7536) | May 25, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [37a8e41d00](https://linux-hardware.org/?probe=37a8e41d00) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [ea7f269697](https://linux-hardware.org/?probe=ea7f269697) | May 24, 2022 |
| ICL           | Unknown                     | Notebook    | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [9450237ae3](https://linux-hardware.org/?probe=9450237ae3) | May 23, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [ad85836549](https://linux-hardware.org/?probe=ad85836549) | May 20, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| iRU           | LPGR.469559.012             | Desktop     | [9163b267bc](https://linux-hardware.org/?probe=9163b267bc) | May 19, 2022 |
| ICL           | H310SB-TM                   | All in one  | [72c2889a81](https://linux-hardware.org/?probe=72c2889a81) | May 18, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [8ededa12ef](https://linux-hardware.org/?probe=8ededa12ef) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [bedc08df5b](https://linux-hardware.org/?probe=bedc08df5b) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | Desktop     | [cfb12880a5](https://linux-hardware.org/?probe=cfb12880a5) | May 11, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [96e5d68181](https://linux-hardware.org/?probe=96e5d68181) | May 06, 2022 |
| ASRock        | H61M-GE                     | Desktop     | [fefe67c0d4](https://linux-hardware.org/?probe=fefe67c0d4) | May 05, 2022 |
| ICL           | H310SB-TM                   | All in one  | [8aca897292](https://linux-hardware.org/?probe=8aca897292) | May 05, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4891bdbd5c](https://linux-hardware.org/?probe=4891bdbd5c) | May 04, 2022 |
| ICL           | H310SB-TM                   | All in one  | [5e24e4a45d](https://linux-hardware.org/?probe=5e24e4a45d) | May 04, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [48af028244](https://linux-hardware.org/?probe=48af028244) | Apr 29, 2022 |
| Lenovo        | NOK                         | Desktop     | [4ea735896c](https://linux-hardware.org/?probe=4ea735896c) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [c75ef7f42d](https://linux-hardware.org/?probe=c75ef7f42d) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [af1b36d1f6](https://linux-hardware.org/?probe=af1b36d1f6) | Apr 28, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e612a2bab1](https://linux-hardware.org/?probe=e612a2bab1) | Apr 27, 2022 |
| Lenovo        | NOK                         | Desktop     | [6d17068770](https://linux-hardware.org/?probe=6d17068770) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| ICL           | H310SB-TM                   | All in one  | [11db07be56](https://linux-hardware.org/?probe=11db07be56) | Apr 25, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f1e5d5715f](https://linux-hardware.org/?probe=f1e5d5715f) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a0e3085b4c](https://linux-hardware.org/?probe=a0e3085b4c) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [9819b3fc78](https://linux-hardware.org/?probe=9819b3fc78) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [d27d03b7e4](https://linux-hardware.org/?probe=d27d03b7e4) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a8784c861a](https://linux-hardware.org/?probe=a8784c861a) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [b970feef75](https://linux-hardware.org/?probe=b970feef75) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [6bfffcf96a](https://linux-hardware.org/?probe=6bfffcf96a) | Apr 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [c7c9ed4c0e](https://linux-hardware.org/?probe=c7c9ed4c0e) | Apr 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ec99a4a73b](https://linux-hardware.org/?probe=ec99a4a73b) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [807bf178aa](https://linux-hardware.org/?probe=807bf178aa) | Apr 19, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [651d569b66](https://linux-hardware.org/?probe=651d569b66) | Apr 18, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b97ab9e5ca](https://linux-hardware.org/?probe=b97ab9e5ca) | Apr 18, 2022 |
| ICL           | H310SB-TM                   | All in one  | [75dab395ac](https://linux-hardware.org/?probe=75dab395ac) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [faeb46556e](https://linux-hardware.org/?probe=faeb46556e) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ce5f89e30](https://linux-hardware.org/?probe=5ce5f89e30) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [016707b662](https://linux-hardware.org/?probe=016707b662) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [1ec31e58eb](https://linux-hardware.org/?probe=1ec31e58eb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [558e7d71c5](https://linux-hardware.org/?probe=558e7d71c5) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [58d8d12597](https://linux-hardware.org/?probe=58d8d12597) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [352ed8f1aa](https://linux-hardware.org/?probe=352ed8f1aa) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [f23db30412](https://linux-hardware.org/?probe=f23db30412) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3fa8965015](https://linux-hardware.org/?probe=3fa8965015) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [287eb4cfbb](https://linux-hardware.org/?probe=287eb4cfbb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [8c69097ae0](https://linux-hardware.org/?probe=8c69097ae0) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [472e946f77](https://linux-hardware.org/?probe=472e946f77) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f227fe1fc7](https://linux-hardware.org/?probe=f227fe1fc7) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [49039d6324](https://linux-hardware.org/?probe=49039d6324) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [39553516dd](https://linux-hardware.org/?probe=39553516dd) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9f87ee8978](https://linux-hardware.org/?probe=9f87ee8978) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [bf274bc0f4](https://linux-hardware.org/?probe=bf274bc0f4) | Apr 15, 2022 |
| Timi          | TM1701                      | Notebook    | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [53137ae702](https://linux-hardware.org/?probe=53137ae702) | Apr 14, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [a98b8b4304](https://linux-hardware.org/?probe=a98b8b4304) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0d3978670a](https://linux-hardware.org/?probe=0d3978670a) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [3829d7dfca](https://linux-hardware.org/?probe=3829d7dfca) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [13122b16be](https://linux-hardware.org/?probe=13122b16be) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [567d83946c](https://linux-hardware.org/?probe=567d83946c) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [82df5d5154](https://linux-hardware.org/?probe=82df5d5154) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c55e8d0780](https://linux-hardware.org/?probe=c55e8d0780) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [46344da31f](https://linux-hardware.org/?probe=46344da31f) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [906a9f0a46](https://linux-hardware.org/?probe=906a9f0a46) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [482922befd](https://linux-hardware.org/?probe=482922befd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2cb7352d17](https://linux-hardware.org/?probe=2cb7352d17) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54f3bbf0af](https://linux-hardware.org/?probe=54f3bbf0af) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f7d3604a6b](https://linux-hardware.org/?probe=f7d3604a6b) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [40083e1990](https://linux-hardware.org/?probe=40083e1990) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ecf34aa4f0](https://linux-hardware.org/?probe=ecf34aa4f0) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [baf8cdeb1a](https://linux-hardware.org/?probe=baf8cdeb1a) | Apr 13, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eacb6915d](https://linux-hardware.org/?probe=1eacb6915d) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [84e70046d5](https://linux-hardware.org/?probe=84e70046d5) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [92f6d24bde](https://linux-hardware.org/?probe=92f6d24bde) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [8e924a50c1](https://linux-hardware.org/?probe=8e924a50c1) | Apr 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0fecbe6cdc](https://linux-hardware.org/?probe=0fecbe6cdc) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [99d19658b8](https://linux-hardware.org/?probe=99d19658b8) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b6bcbc6a65](https://linux-hardware.org/?probe=b6bcbc6a65) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [97d94278ea](https://linux-hardware.org/?probe=97d94278ea) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ebaca158a](https://linux-hardware.org/?probe=5ebaca158a) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7e40f60767](https://linux-hardware.org/?probe=7e40f60767) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ce83b095fe](https://linux-hardware.org/?probe=ce83b095fe) | Apr 12, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3e7d8951a2](https://linux-hardware.org/?probe=3e7d8951a2) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [105088d6de](https://linux-hardware.org/?probe=105088d6de) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [126b987221](https://linux-hardware.org/?probe=126b987221) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5d59afae00](https://linux-hardware.org/?probe=5d59afae00) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [442de26b34](https://linux-hardware.org/?probe=442de26b34) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9d7fc26276](https://linux-hardware.org/?probe=9d7fc26276) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e07ab03ffb](https://linux-hardware.org/?probe=e07ab03ffb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b4b977309d](https://linux-hardware.org/?probe=b4b977309d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bff39744bc](https://linux-hardware.org/?probe=bff39744bc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01cd534e80](https://linux-hardware.org/?probe=01cd534e80) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [669e6289c0](https://linux-hardware.org/?probe=669e6289c0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d49df4c170](https://linux-hardware.org/?probe=d49df4c170) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01aa1a4299](https://linux-hardware.org/?probe=01aa1a4299) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a85817bb6d](https://linux-hardware.org/?probe=a85817bb6d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [25955c9bb1](https://linux-hardware.org/?probe=25955c9bb1) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0c81aeca67](https://linux-hardware.org/?probe=0c81aeca67) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e72fe0a0a9](https://linux-hardware.org/?probe=e72fe0a0a9) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [33b61b457e](https://linux-hardware.org/?probe=33b61b457e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d6c6259cc0](https://linux-hardware.org/?probe=d6c6259cc0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f2444b315d](https://linux-hardware.org/?probe=f2444b315d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [aa745aba70](https://linux-hardware.org/?probe=aa745aba70) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [3b73c79a3c](https://linux-hardware.org/?probe=3b73c79a3c) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d1a4cd1698](https://linux-hardware.org/?probe=d1a4cd1698) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54713393ec](https://linux-hardware.org/?probe=54713393ec) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [56d2022832](https://linux-hardware.org/?probe=56d2022832) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [71dfb9a346](https://linux-hardware.org/?probe=71dfb9a346) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [7cf5bcdb89](https://linux-hardware.org/?probe=7cf5bcdb89) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [efbe0a9eca](https://linux-hardware.org/?probe=efbe0a9eca) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [60fbf7929d](https://linux-hardware.org/?probe=60fbf7929d) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [6aaab98810](https://linux-hardware.org/?probe=6aaab98810) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e9a0bae6e6](https://linux-hardware.org/?probe=e9a0bae6e6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4fb63d6dfe](https://linux-hardware.org/?probe=4fb63d6dfe) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [dde0916ae5](https://linux-hardware.org/?probe=dde0916ae5) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8ee5753b25](https://linux-hardware.org/?probe=8ee5753b25) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [6fb5a857e1](https://linux-hardware.org/?probe=6fb5a857e1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [613ea0ab6b](https://linux-hardware.org/?probe=613ea0ab6b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2aeec4566f](https://linux-hardware.org/?probe=2aeec4566f) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5751abaf6c](https://linux-hardware.org/?probe=5751abaf6c) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [31b40a1aa0](https://linux-hardware.org/?probe=31b40a1aa0) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d3bbe595ba](https://linux-hardware.org/?probe=d3bbe595ba) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [24d5b7f6c6](https://linux-hardware.org/?probe=24d5b7f6c6) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f94dbbfc1f](https://linux-hardware.org/?probe=f94dbbfc1f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [960168908f](https://linux-hardware.org/?probe=960168908f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [71610e6e10](https://linux-hardware.org/?probe=71610e6e10) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2407bd778](https://linux-hardware.org/?probe=d2407bd778) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [88fc4d57ec](https://linux-hardware.org/?probe=88fc4d57ec) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a1cbc192aa](https://linux-hardware.org/?probe=a1cbc192aa) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [66d94b1220](https://linux-hardware.org/?probe=66d94b1220) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e8c2f02ba1](https://linux-hardware.org/?probe=e8c2f02ba1) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [7ef15ed6c9](https://linux-hardware.org/?probe=7ef15ed6c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8bcad9c229](https://linux-hardware.org/?probe=8bcad9c229) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [a03ff53e01](https://linux-hardware.org/?probe=a03ff53e01) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5486388fa0](https://linux-hardware.org/?probe=5486388fa0) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [68041f0a96](https://linux-hardware.org/?probe=68041f0a96) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [87858c448c](https://linux-hardware.org/?probe=87858c448c) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a7e615a620](https://linux-hardware.org/?probe=a7e615a620) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [5b340e2b7f](https://linux-hardware.org/?probe=5b340e2b7f) | Apr 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [237634ce8d](https://linux-hardware.org/?probe=237634ce8d) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [83b01e222e](https://linux-hardware.org/?probe=83b01e222e) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a20cfb8d86](https://linux-hardware.org/?probe=a20cfb8d86) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c6f290816a](https://linux-hardware.org/?probe=c6f290816a) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [60c4fc315b](https://linux-hardware.org/?probe=60c4fc315b) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [faad64ac67](https://linux-hardware.org/?probe=faad64ac67) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [19d0ee846e](https://linux-hardware.org/?probe=19d0ee846e) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [9e2f7749b8](https://linux-hardware.org/?probe=9e2f7749b8) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3fe662dcb](https://linux-hardware.org/?probe=f3fe662dcb) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5293db1b11](https://linux-hardware.org/?probe=5293db1b11) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7d3b364ff0](https://linux-hardware.org/?probe=7d3b364ff0) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d8307a4138](https://linux-hardware.org/?probe=d8307a4138) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [bffde28b59](https://linux-hardware.org/?probe=bffde28b59) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d31dd74d7](https://linux-hardware.org/?probe=7d31dd74d7) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d03a291a2](https://linux-hardware.org/?probe=7d03a291a2) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [91f33b247d](https://linux-hardware.org/?probe=91f33b247d) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2628069096](https://linux-hardware.org/?probe=2628069096) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7c2a257e92](https://linux-hardware.org/?probe=7c2a257e92) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [868b030342](https://linux-hardware.org/?probe=868b030342) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4088112a18](https://linux-hardware.org/?probe=4088112a18) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [68820282cb](https://linux-hardware.org/?probe=68820282cb) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5a5a1a7ae6](https://linux-hardware.org/?probe=5a5a1a7ae6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [936252dfca](https://linux-hardware.org/?probe=936252dfca) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [67ed2ddd29](https://linux-hardware.org/?probe=67ed2ddd29) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fde95ea3ed](https://linux-hardware.org/?probe=fde95ea3ed) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [de01821ecf](https://linux-hardware.org/?probe=de01821ecf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [67f41bf764](https://linux-hardware.org/?probe=67f41bf764) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [77aadf6511](https://linux-hardware.org/?probe=77aadf6511) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [cb9ae4e880](https://linux-hardware.org/?probe=cb9ae4e880) | Apr 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [0199b0b388](https://linux-hardware.org/?probe=0199b0b388) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2a24f0327](https://linux-hardware.org/?probe=d2a24f0327) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [498dd8c409](https://linux-hardware.org/?probe=498dd8c409) | Apr 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ALT_Linux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Kometa P10         | 165       | 17.99%  |
| ALT Linux 10.1     | 144       | 15.7%   |
| ALT Linux 10.2     | 101       | 11.01%  |
| ALT Linux 9.1      | 65        | 7.09%   |
| ALT Linux 10.0     | 62        | 6.76%   |
| MOS 10             | 61        | 6.65%   |
| ALT Linux 20240122 | 47        | 5.13%   |
| ALT Linux 10.3     | 43        | 4.69%   |
| ALT Linux 9.0      | 31        | 3.38%   |
| ALT Linux 10.4     | 31        | 3.38%   |
| ALT Linux 9.2      | 18        | 1.96%   |
| ALT Linux 10       | 17        | 1.85%   |
| ALT Linux 8.4      | 13        | 1.42%   |
| ALT Linux P10      | 11        | 1.2%    |
| ALT Linux 11.0     | 10        | 1.09%   |
| ALT Linux 11       | 8         | 0.87%   |
| ALT Linux 10.1.900 | 8         | 0.87%   |
| ALT Linux 0.9.2    | 7         | 0.76%   |
| ALT Linux P9       | 6         | 0.65%   |
| ALT Linux 8.2      | 6         | 0.65%   |
| ALT Linux 10.0.900 | 6         | 0.65%   |
| ALT Linux P8       | 5         | 0.55%   |
| ALT Linux 20230819 | 5         | 0.55%   |
| ALT Linux 20201124 | 5         | 0.55%   |
| ALT Linux 10.1.990 | 5         | 0.55%   |
| ALT Linux 0.9.1    | 5         | 0.55%   |
| ALT Linux 20220110 | 4         | 0.44%   |
| ALT Linux 7.0.5    | 2         | 0.22%   |
| ALT Linux 20191026 | 2         | 0.22%   |
| ALT Linux 10.900   | 2         | 0.22%   |
| Kometa 1           | 1         | 0.11%   |
| ALT Linux 9.1.990  | 1         | 0.11%   |
| ALT Linux 9        | 1         | 0.11%   |
| ALT Linux 8.990    | 1         | 0.11%   |
| ALT Linux 8.93     | 1         | 0.11%   |
| ALT Linux 8.920    | 1         | 0.11%   |
| ALT Linux 8.3      | 1         | 0.11%   |
| ALT Linux 8.2.0    | 1         | 0.11%   |
| ALT Linux 8.0.0    | 1         | 0.11%   |
| ALT Linux 8.0      | 1         | 0.11%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ALT Linux | 857       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.109-std-def-alt1      | 85        | 8.82%   |
| 5.10.102-std-def-alt1      | 80        | 8.3%    |
| 5.10.164-std-def-alt1      | 25        | 2.59%   |
| 5.15.72-un-def-alt1        | 24        | 2.49%   |
| 5.15.34-un-def-alt1        | 21        | 2.18%   |
| 5.10.198-std-def-alt1      | 21        | 2.18%   |
| 5.10.139-std-def-alt1      | 18        | 1.87%   |
| 5.15.80-un-def-alt1        | 17        | 1.76%   |
| 5.10.82-std-def-alt1       | 17        | 1.76%   |
| 6.1.81-un-def-alt1         | 16        | 1.66%   |
| 5.10.88-std-def-alt1       | 15        | 1.56%   |
| 5.10.156-std-def-alt1      | 14        | 1.45%   |
| 5.10.123-std-def-alt1      | 14        | 1.45%   |
| 6.1.49-un-def-alt1         | 12        | 1.24%   |
| 5.4.51-std-def-alt1        | 12        | 1.24%   |
| 6.1.57-un-def-alt1         | 11        | 1.14%   |
| 4.19.79-std-def-alt1       | 11        | 1.14%   |
| 5.4.68-std-def-alt1.1      | 10        | 1.04%   |
| 6.1.55-un-def-alt1         | 9         | 0.93%   |
| 5.10.166-std-def-alt1      | 9         | 0.93%   |
| 6.1.79-un-def-alt1         | 8         | 0.83%   |
| 6.1.38-un-def-alt1         | 7         | 0.73%   |
| 5.4.28-std-def-alt1        | 7         | 0.73%   |
| 5.10.152-std-def-alt1      | 7         | 0.73%   |
| 6.6.21-un-def-alt1         | 6         | 0.62%   |
| 6.1.77-un-def-alt1         | 6         | 0.62%   |
| 5.15.76-un-def-alt1        | 6         | 0.62%   |
| 6.1.54-un-def-alt1         | 5         | 0.52%   |
| 6.1.111-un-def-alt1        | 5         | 0.52%   |
| 6.1.100-un-def-alt1        | 5         | 0.52%   |
| 5.15.32-un-def-alt1        | 5         | 0.52%   |
| 5.10.93-std-def-alt1       | 5         | 0.52%   |
| 5.10.83-std-def-alt0.c9f.2 | 5         | 0.52%   |
| 5.10.32-un-def-alt1        | 5         | 0.52%   |
| 5.10.145-std-def-alt1      | 5         | 0.52%   |
| 6.6.32-un-def-alt1         | 4         | 0.41%   |
| 6.1.83-un-def-alt1         | 4         | 0.41%   |
| 6.1.119-un-def-alt1        | 4         | 0.41%   |
| 5.7.19-un-def-alt1         | 4         | 0.41%   |
| 5.4.62-std-def-alt1        | 4         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.109 | 85        | 8.82%   |
| 5.10.102 | 80        | 8.3%    |
| 5.10.164 | 25        | 2.59%   |
| 5.15.72  | 24        | 2.49%   |
| 5.10.198 | 22        | 2.28%   |
| 5.15.34  | 21        | 2.18%   |
| 5.15.80  | 18        | 1.87%   |
| 5.10.139 | 18        | 1.87%   |
| 5.10.82  | 17        | 1.76%   |
| 6.1.81   | 16        | 1.66%   |
| 5.10.88  | 15        | 1.56%   |
| 5.10.156 | 15        | 1.56%   |
| 5.10.123 | 14        | 1.45%   |
| 6.1.49   | 12        | 1.24%   |
| 5.4.51   | 12        | 1.24%   |
| 6.1.57   | 11        | 1.14%   |
| 5.4.68   | 11        | 1.14%   |
| 4.19.79  | 11        | 1.14%   |
| 6.1.55   | 10        | 1.04%   |
| 5.10.166 | 9         | 0.93%   |
| 6.1.79   | 8         | 0.83%   |
| 6.1.38   | 7         | 0.73%   |
| 6.1.100  | 7         | 0.73%   |
| 5.4.28   | 7         | 0.73%   |
| 5.10.152 | 7         | 0.73%   |
| 6.6.21   | 6         | 0.62%   |
| 6.1.77   | 6         | 0.62%   |
| 5.15.76  | 6         | 0.62%   |
| 6.6.52   | 5         | 0.52%   |
| 6.6.32   | 5         | 0.52%   |
| 6.1.54   | 5         | 0.52%   |
| 6.1.111  | 5         | 0.52%   |
| 5.15.32  | 5         | 0.52%   |
| 5.10.93  | 5         | 0.52%   |
| 5.10.83  | 5         | 0.52%   |
| 5.10.35  | 5         | 0.52%   |
| 5.10.32  | 5         | 0.52%   |
| 5.10.145 | 5         | 0.52%   |
| 6.11.0   | 4         | 0.41%   |
| 6.1.85   | 4         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 423       | 46.79%  |
| 6.1     | 147       | 16.26%  |
| 5.15    | 117       | 12.94%  |
| 5.4     | 68        | 7.52%   |
| 6.6     | 64        | 7.08%   |
| 4.19    | 26        | 2.88%   |
| 4.9     | 7         | 0.77%   |
| 6.5     | 6         | 0.66%   |
| 6.12    | 6         | 0.66%   |
| 6.9     | 5         | 0.55%   |
| 6.11    | 5         | 0.55%   |
| 5.7     | 5         | 0.55%   |
| 6.2     | 3         | 0.33%   |
| 5.2     | 3         | 0.33%   |
| 5.18    | 3         | 0.33%   |
| 5.14    | 3         | 0.33%   |
| 5.13    | 3         | 0.33%   |
| 6.4     | 2         | 0.22%   |
| 4.14    | 2         | 0.22%   |
| 5.9     | 1         | 0.11%   |
| 5.3     | 1         | 0.11%   |
| 5.16    | 1         | 0.11%   |
| 5.12    | 1         | 0.11%   |
| 4.4     | 1         | 0.11%   |
| 4.20    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 831       | 96.97%  |
| i686        | 16        | 1.87%   |
| aarch64     | 5         | 0.58%   |
| e2k         | 4         | 0.47%   |
| loongarch64 | 1         | 0.12%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 494       | 56.01%  |
| XFCE            | 148       | 16.78%  |
| Unknown         | 114       | 12.93%  |
| GNOME           | 56        | 6.35%   |
| MATE            | 42        | 4.76%   |
| LXQt            | 10        | 1.13%   |
| Cinnamon        | 6         | 0.68%   |
| KDE             | 4         | 0.45%   |
| KDE6            | 3         | 0.34%   |
| X-Cinnamon      | 2         | 0.23%   |
| GNOME Flashback | 2         | 0.23%   |
| LXDE            | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 771       | 89.13%  |
| Wayland | 51        | 5.9%    |
| Unknown | 25        | 2.89%   |
| Tty     | 18        | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 330       | 37.63%  |
| LightDM | 269       | 30.67%  |
| Unknown | 185       | 21.09%  |
| TDM     | 62        | 7.07%   |
| GDM     | 27        | 3.08%   |
| XDM     | 2         | 0.23%   |
| WDM     | 1         | 0.11%   |
| CAPSH   | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| ru_RU      | 752       | 86.14%  |
| Unknown    | 83        | 9.51%   |
| en_US      | 27        | 3.09%   |
| POSIX      | 6         | 0.69%   |
| ru_RU.UTF8 | 1         | 0.11%   |
| ru         | 1         | 0.11%   |
| it_IT@euro | 1         | 0.11%   |
| el_GR      | 1         | 0.11%   |
| C          | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 511       | 59.01%  |
| BIOS | 355       | 40.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 696       | 79.91%  |
| Btrfs   | 121       | 13.89%  |
| Overlay | 48        | 5.51%   |
| Xfs     | 2         | 0.23%   |
| Tmpfs   | 2         | 0.23%   |
| Unknown | 2         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 504       | 57.93%  |
| MBR     | 189       | 21.72%  |
| Unknown | 177       | 20.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 779       | 89.75%  |
| Yes       | 89        | 10.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 625       | 71.84%  |
| Yes       | 245       | 28.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| ASUSTek Computer                  | 125       | 14.59%  |
| Hewlett-Packard                   | 100       | 11.67%  |
| Gigabyte Technology               | 69        | 8.05%   |
| Lenovo                            | 63        | 7.35%   |
| Intel                             | 60        | 7%      |
| Acer                              | 52        | 6.07%   |
| MSI                               | 47        | 5.48%   |
| ASRock                            | 36        | 4.2%    |
| Clevo                             | 32        | 3.73%   |
| 3Logic Group                      | 29        | 3.38%   |
| Unknown                           | 26        | 3.03%   |
| ICL                               | 22        | 2.57%   |
| Dell                              | 21        | 2.45%   |
| HUAWEI                            | 16        | 1.87%   |
| DEPO Computers                    | 16        | 1.87%   |
| Graviton                          | 10        | 1.17%   |
| Samsung Electronics               | 9         | 1.05%   |
| Aquarius                          | 9         | 1.05%   |
| Apple                             | 8         | 0.93%   |
| Biostar                           | 7         | 0.82%   |
| Kraftway                          | 5         | 0.58%   |
| iRU                               | 5         | 0.58%   |
| Supermicro                        | 4         | 0.47%   |
| Sony                              | 4         | 0.47%   |
| Pegatron                          | 4         | 0.47%   |
| MAINBRD                           | 4         | 0.47%   |
| Maibenben                         | 4         | 0.47%   |
| HONOR                             | 4         | 0.47%   |
| Toshiba                           | 3         | 0.35%   |
| Timi                              | 3         | 0.35%   |
| Infinix                           | 3         | 0.35%   |
| Huanan                            | 3         | 0.35%   |
| F-PLUS EQUIPMENT AND DEVELOPMENTS | 3         | 0.35%   |
| AZW                               | 3         | 0.35%   |
| TECNO Mobile Limited              | 2         | 0.23%   |
| Panasonic                         | 2         | 0.23%   |
| MACHENIKE                         | 2         | 0.23%   |
| LTD Delovoy Office                | 2         | 0.23%   |
| Irbis                             | 2         | 0.23%   |
| IP3 Tech                          | 2         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel SKYBAY                                                                             | 47        | 5.48%   |
| Clevo NL41MU2                                                                            | 32        | 3.73%   |
| Unknown                                                                                  | 30        | 3.5%    |
| 3Logic Group Graviton                                                                    | 21        | 2.45%   |
| HP 250 G7 Notebook PC                                                                    | 12        | 1.4%    |
| ASUS PRIME B450-PLUS                                                                     | 12        | 1.4%    |
| Lenovo V540-24IWL AIO 10YS0031RU                                                         | 10        | 1.17%   |
| Acer Veriton X2640G                                                                      | 10        | 1.17%   |
| HP ZBook 17 G5                                                                           | 9         | 1.05%   |
| HP ProBook 440 G5                                                                        | 8         | 0.93%   |
| DEPO Computers DPC156                                                                    | 7         | 0.82%   |
| ASUS All Series                                                                          | 7         | 0.82%   |
| ICL RAYbook Si1512                                                                       | 6         | 0.7%    |
| Lenovo ThinkSystem SR590 -[7X99CTO1WW]-                                                  | 5         | 0.58%   |
| MSI MS-7C56                                                                              | 4         | 0.47%   |
| MAINBRD OPS62A-SHA                                                                       | 4         | 0.47%   |
| Lenovo ThinkBook 15 G2 ITL 20VE                                                          | 4         | 0.47%   |
| ICL RAY Si105.Mi                                                                         | 4         | 0.47%   |
| ICL RAY S122.Mi                                                                          | 4         | 0.47%   |
| HP ProLiant SL230s Gen8                                                                  | 4         | 0.47%   |
| Gigabyte H110M-S2H                                                                       | 4         | 0.47%   |
| DEPO Computers DPA520S                                                                   | 4         | 0.47%   |
| 3Logic Group Graviton N15i                                                               | 4         | 0.47%   |
| MSI MS-7D46                                                                              | 3         | 0.35%   |
| MSI MS-7A38                                                                              | 3         | 0.35%   |
| Maibenben Perfectum Series                                                               | 3         | 0.35%   |
| Kraftway ACCORD                                                                          | 3         | 0.35%   |
| HUAWEI NBD-WXX9                                                                          | 3         | 0.35%   |
| HP Pavilion dv6                                                                          | 3         | 0.35%   |
| HP Laptop 15-bw0xx                                                                       | 3         | 0.35%   |
| HP EliteBook 8470p                                                                       | 3         | 0.35%   |
| HP EliteBook 840 G4                                                                      | 3         | 0.35%   |
| HP 250 G6 Notebook PC                                                                    | 3         | 0.35%   |
| Gigabyte A320M-S2H                                                                       | 3         | 0.35%   |
| Dell Latitude 3420                                                                       | 3         | 0.35%   |
| ASUS VivoBook_ASUSLaptop M1503QA_M1503QA                                                 | 3         | 0.35%   |
| ASUS H110M-R                                                                             | 3         | 0.35%   |
| 3Logic Group Graviton N15i-K2                                                            | 3         | 0.35%   |
| Supermicro Super Server                                                                  | 2         | 0.23%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 2         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Intel SKYBAY           | 47        | 5.48%   |
| Clevo NL41MU2          | 32        | 3.73%   |
| Unknown                | 30        | 3.5%    |
| 3Logic Group Graviton  | 29        | 3.38%   |
| Acer Aspire            | 22        | 2.57%   |
| ASUS PRIME             | 21        | 2.45%   |
| HP 250                 | 17        | 1.98%   |
| Acer Veriton           | 17        | 1.98%   |
| HP ProBook             | 15        | 1.75%   |
| HP Pavilion            | 15        | 1.75%   |
| ASUS VivoBook          | 12        | 1.4%    |
| Lenovo V540-24IWL      | 10        | 1.17%   |
| Lenovo ThinkPad        | 10        | 1.17%   |
| Lenovo IdeaPad         | 10        | 1.17%   |
| HP Laptop              | 10        | 1.17%   |
| HP EliteBook           | 10        | 1.17%   |
| HP ZBook               | 9         | 1.05%   |
| ASUS ASUS              | 9         | 1.05%   |
| ICL RAY                | 8         | 0.93%   |
| ICL RAYbook            | 7         | 0.82%   |
| DEPO Computers DPC156  | 7         | 0.82%   |
| ASUS All               | 7         | 0.82%   |
| HP ProLiant            | 6         | 0.7%    |
| Dell Inspiron          | 6         | 0.7%    |
| ASUS ROG               | 6         | 0.7%    |
| Lenovo ThinkSystem     | 5         | 0.58%   |
| Dell OptiPlex          | 5         | 0.58%   |
| Dell Latitude          | 5         | 0.58%   |
| MSI MS-7C56            | 4         | 0.47%   |
| MAINBRD OPS62A-SHA     | 4         | 0.47%   |
| Lenovo ThinkBook       | 4         | 0.47%   |
| HP Compaq              | 4         | 0.47%   |
| Gigabyte H110M-S2H     | 4         | 0.47%   |
| Gigabyte A320M-S2H     | 4         | 0.47%   |
| DEPO Computers DPA520S | 4         | 0.47%   |
| Acer TravelMate        | 4         | 0.47%   |
| MSI MS-7D46            | 3         | 0.35%   |
| MSI MS-7A38            | 3         | 0.35%   |
| MSI Modern             | 3         | 0.35%   |
| Maibenben Perfectum    | 3         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 123       | 14.35%  |
| 2018    | 91        | 10.62%  |
| 2020    | 87        | 10.15%  |
| 2021    | 82        | 9.57%   |
| 2017    | 73        | 8.52%   |
| 2019    | 64        | 7.47%   |
| 2016    | 38        | 4.43%   |
| 2023    | 36        | 4.2%    |
| 2011    | 35        | 4.08%   |
| 2013    | 32        | 3.73%   |
| 2012    | 31        | 3.62%   |
| 2010    | 29        | 3.38%   |
| 2014    | 26        | 3.03%   |
| 2009    | 22        | 2.57%   |
| 2015    | 20        | 2.33%   |
| 2008    | 20        | 2.33%   |
| 2007    | 15        | 1.75%   |
| 2006    | 12        | 1.4%    |
| 2024    | 8         | 0.93%   |
| Unknown | 7         | 0.82%   |
| 2005    | 3         | 0.35%   |
| 2004    | 2         | 0.23%   |
| 2003    | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 382       | 44.57%  |
| Desktop        | 381       | 44.46%  |
| All in one     | 58        | 6.77%   |
| Server         | 13        | 1.52%   |
| Mini pc        | 8         | 0.93%   |
| System on chip | 5         | 0.58%   |
| Convertible    | 5         | 0.58%   |
| Tablet         | 4         | 0.47%   |
| Stick pc       | 1         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 766       | 88.25%  |
| Enabled  | 102       | 11.75%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 857       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 283       | 32.75%  |
| 16.01-24.0      | 173       | 20.02%  |
| 8.01-16.0       | 170       | 19.68%  |
| 3.01-4.0        | 101       | 11.69%  |
| 32.01-64.0      | 54        | 6.25%   |
| 1.01-2.0        | 28        | 3.24%   |
| 64.01-256.0     | 23        | 2.66%   |
| 24.01-32.0      | 13        | 1.5%    |
| 2.01-3.0        | 11        | 1.27%   |
| More than 256.0 | 4         | 0.46%   |
| 0.51-1.0        | 4         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 386       | 41.91%  |
| 2.01-3.0   | 196       | 21.28%  |
| 4.01-8.0   | 111       | 12.05%  |
| 0.51-1.0   | 96        | 10.42%  |
| 3.01-4.0   | 86        | 9.34%   |
| 8.01-16.0  | 27        | 2.93%   |
| 0.01-0.5   | 13        | 1.41%   |
| 16.01-24.0 | 3         | 0.33%   |
| 32.01-64.0 | 2         | 0.22%   |
| 24.01-32.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 594       | 67.73%  |
| 2       | 171       | 19.5%   |
| 3       | 56        | 6.39%   |
| 4       | 27        | 3.08%   |
| 5       | 10        | 1.14%   |
| 0       | 6         | 0.68%   |
| 6       | 4         | 0.46%   |
| 8       | 3         | 0.34%   |
| 13      | 2         | 0.23%   |
| 7       | 2         | 0.23%   |
| 9       | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 625       | 72.42%  |
| Yes       | 238       | 27.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 775       | 90.43%  |
| No        | 82        | 9.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 539       | 62.6%   |
| No        | 322       | 37.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 471       | 54.64%  |
| No        | 391       | 45.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 812       | 94.53%  |
| Greece      | 10        | 1.16%   |
| Belarus     | 8         | 0.93%   |
| Ukraine     | 6         | 0.7%    |
| UK          | 2         | 0.23%   |
| Latvia      | 2         | 0.23%   |
| Kazakhstan  | 2         | 0.23%   |
| Egypt       | 2         | 0.23%   |
| Uzbekistan  | 1         | 0.12%   |
| USA         | 1         | 0.12%   |
| Switzerland | 1         | 0.12%   |
| Moldova     | 1         | 0.12%   |
| Italy       | 1         | 0.12%   |
| Germany     | 1         | 0.12%   |
| France      | 1         | 0.12%   |
| Finland     | 1         | 0.12%   |
| Estonia     | 1         | 0.12%   |
| Czechia     | 1         | 0.12%   |
| Costa Rica  | 1         | 0.12%   |
| Colombia    | 1         | 0.12%   |
| China       | 1         | 0.12%   |
| Bulgaria    | 1         | 0.12%   |
| Australia   | 1         | 0.12%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 435       | 49.43%  |
| St Petersburg     | 70        | 7.95%   |
| Novosibirsk       | 19        | 2.16%   |
| Samara            | 14        | 1.59%   |
| Barnaul           | 14        | 1.59%   |
| Krasnoyarsk       | 12        | 1.36%   |
| Krasnodar         | 10        | 1.14%   |
| Zheleznodorozhnyy | 8         | 0.91%   |
| Perm              | 8         | 0.91%   |
| Obninsk           | 8         | 0.91%   |
| Yekaterinburg     | 7         | 0.8%    |
| Rostov-on-Don     | 7         | 0.8%    |
| Surgut            | 6         | 0.68%   |
| Saratov           | 6         | 0.68%   |
| Irkutsk           | 6         | 0.68%   |
| Chelyabinsk       | 6         | 0.68%   |
| Voronezh          | 5         | 0.57%   |
| Astrakhan         | 5         | 0.57%   |
| Vladimir          | 4         | 0.45%   |
| Tyumen            | 4         | 0.45%   |
| Stavropol         | 4         | 0.45%   |
| Lipetsk           | 4         | 0.45%   |
| Kirov             | 4         | 0.45%   |
| Kemerovo          | 4         | 0.45%   |
| Kaliningrad       | 4         | 0.45%   |
| Belgorod          | 4         | 0.45%   |
| Vladivostok       | 3         | 0.34%   |
| Veliky Novgorod   | 3         | 0.34%   |
| Ufa               | 3         | 0.34%   |
| Tver              | 3         | 0.34%   |
| Tula              | 3         | 0.34%   |
| Thessaloniki      | 3         | 0.34%   |
| Sevastopol        | 3         | 0.34%   |
| Omsk              | 3         | 0.34%   |
| Nizhny Tagil      | 3         | 0.34%   |
| Kursk             | 3         | 0.34%   |
| Korolyov          | 3         | 0.34%   |
| Kazan’          | 3         | 0.34%   |
| Balashikha        | 3         | 0.34%   |
| Zhukovskiy        | 2         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 149       | 227    | 12.64%  |
| Seagate                     | 131       | 188    | 11.11%  |
| Samsung Electronics         | 122       | 168    | 10.35%  |
| Toshiba                     | 76        | 110    | 6.45%   |
| Kingston                    | 66        | 83     | 5.6%    |
| Apacer                      | 54        | 63     | 4.58%   |
| Intel                       | 42        | 56     | 3.56%   |
| A-DATA Technology           | 35        | 39     | 2.97%   |
| SK hynix                    | 34        | 36     | 2.88%   |
| BIWIN                       | 33        | 34     | 2.8%    |
| AXIOMTEK                    | 29        | 31     | 2.46%   |
| Sandisk                     | 24        | 25     | 2.04%   |
| China                       | 24        | 26     | 2.04%   |
| Hitachi                     | 20        | 21     | 1.7%    |
| Unknown                     | 19        | 33     | 1.61%   |
| Micron Technology           | 15        | 24     | 1.27%   |
| AMD                         | 13        | 13     | 1.1%    |
| Patriot                     | 12        | 16     | 1.02%   |
| HGST                        | 12        | 12     | 1.02%   |
| Gigabyte Technology         | 12        | 12     | 1.02%   |
| Crucial                     | 12        | 14     | 1.02%   |
| XPG                         | 11        | 14     | 0.93%   |
| Silicon Motion              | 11        | 12     | 0.93%   |
| Phison                      | 11        | 13     | 0.93%   |
| Foxline                     | 11        | 11     | 0.93%   |
| Netac                       | 10        | 10     | 0.85%   |
| SPCC                        | 8         | 8      | 0.68%   |
| MAXIO Technology (Hangzhou) | 8         | 8      | 0.68%   |
| FORESEE                     | 8         | 10     | 0.68%   |
| Team                        | 7         | 9      | 0.59%   |
| Smartbuy                    | 7         | 8      | 0.59%   |
| Hewlett-Packard             | 7         | 19     | 0.59%   |
| Unknown                     | 7         | 8      | 0.59%   |
| XrayDisk                    | 6         | 6      | 0.51%   |
| Transcend                   | 6         | 7      | 0.51%   |
| Plextor                     | 6         | 8      | 0.51%   |
| Phison Electronics          | 6         | 9      | 0.51%   |
| Kingston Technology Company | 6         | 12     | 0.51%   |
| KingSpec                    | 6         | 6      | 0.51%   |
| TMI                         | 5         | 6      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| BIWIN CE480T5D101-256 256GB                           | 32        | 2.56%   |
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD                  | 29        | 2.32%   |
| Apacer AS2280P4 256GB                                 | 21        | 1.68%   |
| Samsung MZVLW128HEGR-00000 128GB                      | 18        | 1.44%   |
| Toshiba HDWD110 1TB                                   | 14        | 1.12%   |
| Toshiba HDWD120 2TB                                   | 13        | 1.04%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB               | 13        | 1.04%   |
| Kingston SA400S37240G 240GB SSD                       | 12        | 0.96%   |
| Seagate ST1000LM049-2GH172 1TB                        | 11        | 0.88%   |
| WDC WD5000AZLX-21K2TA0 500GB                          | 10        | 0.8%    |
| Intel SSDPEKNU512GZ 512GB                             | 10        | 0.8%    |
| Foxline FLSSD256M80E13TCX5 256GB                      | 10        | 0.8%    |
| SK hynix SKHynix_HFS256GD9TNG-L5B0B 256GB             | 9         | 0.72%   |
| Samsung SSD 860 EVO 250GB                             | 9         | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 8         | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB                        | 8         | 0.64%   |
| Intel SSDPEMKF256G8H 256GB                            | 8         | 0.64%   |
| Intel SSDPEKKF256G7H 256GB                            | 8         | 0.64%   |
| Toshiba DT01ACA100 1TB                                | 7         | 0.56%   |
| Toshiba DT01ACA050 500GB                              | 7         | 0.56%   |
| Apacer AS350 256GB SSD                                | 7         | 0.56%   |
| A-DATA SU650 240GB SSD                                | 7         | 0.56%   |
| Unknown                                               | 7         | 0.56%   |
| Seagate ST500DM002-1BD142 500GB                       | 6         | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 6         | 0.48%   |
| Samsung SSD 970 EVO Plus 250GB                        | 6         | 0.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 6         | 0.48%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 6         | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 5         | 0.4%    |
| Seagate ST9250315AS 250GB                             | 5         | 0.4%    |
| Seagate ST1000LM048-2E7172 1TB                        | 5         | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB                        | 5         | 0.4%    |
| Phison 311CD0512GB                                    | 5         | 0.4%    |
| Kingston SA400S37120G 120GB SSD                       | 5         | 0.4%    |
| Kingston RBUSC180S37256GJ 256GB SSD                   | 5         | 0.4%    |
| HGST HTS721010A9E630 1TB                              | 5         | 0.4%    |
| Crucial CT240BX500SSD1 240GB                          | 5         | 0.4%    |
| Apacer AS2280P4 512GB                                 | 5         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 4         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 4         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 129       | 182    | 34.04%  |
| WDC                 | 119       | 190    | 31.4%   |
| Toshiba             | 71        | 103    | 18.73%  |
| Hitachi             | 20        | 21     | 5.28%   |
| HGST                | 12        | 12     | 3.17%   |
| Samsung Electronics | 8         | 9      | 2.11%   |
| Fujitsu             | 5         | 5      | 1.32%   |
| External            | 3         | 5      | 0.79%   |
| Maxtor              | 2         | 2      | 0.53%   |
| JMicron Technology  | 2         | 2      | 0.53%   |
| HPE                 | 2         | 16     | 0.53%   |
| Hewlett-Packard     | 2         | 10     | 0.53%   |
| XrayDisk            | 1         | 1      | 0.26%   |
| Unknown             | 1         | 2      | 0.26%   |
| SINTECHI            | 1         | 1      | 0.26%   |
| SABRENT             | 1         | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 65     | 11.65%  |
| Kingston            | 46        | 56     | 11.65%  |
| AXIOMTEK            | 29        | 31     | 7.34%   |
| Apacer              | 27        | 34     | 6.84%   |
| China               | 24        | 26     | 6.08%   |
| A-DATA Technology   | 24        | 26     | 6.08%   |
| WDC                 | 23        | 26     | 5.82%   |
| AMD                 | 12        | 12     | 3.04%   |
| Patriot             | 11        | 15     | 2.78%   |
| Crucial             | 11        | 13     | 2.78%   |
| SanDisk             | 10        | 10     | 2.53%   |
| Intel               | 8         | 13     | 2.03%   |
| Gigabyte Technology | 8         | 8      | 2.03%   |
| Team                | 7         | 9      | 1.77%   |
| Smartbuy            | 7         | 8      | 1.77%   |
| Transcend           | 6         | 7      | 1.52%   |
| Plextor             | 6         | 8      | 1.52%   |
| KingSpec            | 6         | 6      | 1.52%   |
| Unknown             | 6         | 7      | 1.52%   |
| XrayDisk            | 5         | 5      | 1.27%   |
| TMI                 | 5         | 6      | 1.27%   |
| SPCC                | 4         | 4      | 1.01%   |
| OCZ                 | 4         | 6      | 1.01%   |
| Netac               | 4         | 4      | 1.01%   |
| Micron Technology   | 4         | 9      | 1.01%   |
| GOODRAM             | 4         | 4      | 1.01%   |
| Qumo                | 3         | 3      | 0.76%   |
| Toshiba             | 2         | 2      | 0.51%   |
| SK hynix            | 2         | 2      | 0.51%   |
| Seagate             | 2         | 6      | 0.51%   |
| PNY                 | 2         | 2      | 0.51%   |
| Phison              | 2         | 2      | 0.51%   |
| mSTORE              | 2         | 4      | 0.51%   |
| KingDian            | 2         | 2      | 0.51%   |
| GS                  | 2         | 6      | 0.51%   |
| Foxline             | 2         | 2      | 0.51%   |
| Digma               | 2         | 3      | 0.51%   |
| DEXP                | 2         | 3      | 0.51%   |
| DEPO                | 2         | 2      | 0.51%   |
| SP-8                | 1         | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 367       | 466    | 34.24%  |
| SSD     | 353       | 482    | 32.93%  |
| HDD     | 328       | 562    | 30.6%   |
| MMC     | 15        | 24     | 1.4%    |
| Unknown | 9         | 12     | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 557       | 1007   | 57.84%  |
| NVMe | 367       | 466    | 38.11%  |
| SAS  | 24        | 49     | 2.49%   |
| MMC  | 15        | 24     | 1.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 437       | 621    | 62.79%  |
| 0.51-1.0   | 180       | 281    | 25.86%  |
| 1.01-2.0   | 53        | 101    | 7.61%   |
| 3.01-4.0   | 15        | 29     | 2.16%   |
| 2.01-3.0   | 6         | 7      | 0.86%   |
| 10.01-20.0 | 2         | 2      | 0.29%   |
| 4.01-10.0  | 2         | 2      | 0.29%   |
| 0          | 1         | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 377       | 42.08%  |
| 251-500        | 162       | 18.08%  |
| 501-1000       | 89        | 9.93%   |
| 1001-2000      | 83        | 9.26%   |
| 51-100         | 57        | 6.36%   |
| 21-50          | 35        | 3.91%   |
| 1-20           | 31        | 3.46%   |
| More than 3000 | 29        | 3.24%   |
| 2001-3000      | 21        | 2.34%   |
| Unknown        | 12        | 1.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 382       | 41.89%  |
| 21-50          | 212       | 23.25%  |
| 51-100         | 98        | 10.75%  |
| 101-250        | 76        | 8.33%   |
| 251-500        | 49        | 5.37%   |
| 501-1000       | 45        | 4.93%   |
| 1001-2000      | 22        | 2.41%   |
| Unknown        | 12        | 1.32%   |
| 2001-3000      | 9         | 0.99%   |
| More than 3000 | 7         | 0.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                  | Computers | Drives | Percent |
|--------------------------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB                              | 5         | 5      | 5.75%   |
| XrayDisk 240GB SSD                                     | 2         | 2      | 2.3%    |
| WDC WD5002AALX-00J37A0 500GB                           | 2         | 5      | 2.3%    |
| WDC WD5000AAKX-001CA0 500GB                            | 2         | 2      | 2.3%    |
| Toshiba MQ01ABD050 500GB                               | 2         | 2      | 2.3%    |
| Seagate ST380815AS 80GB                                | 2         | 2      | 2.3%    |
| Seagate ST250DM000-1BD141 250GB                        | 2         | 3      | 2.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 2         | 7      | 2.3%    |
| HGST HTS721010A9E630 1TB                               | 2         | 2      | 2.3%    |
| GS SSD 256-8 240GB                                     | 2         | 5      | 2.3%    |
| XrayDisk 512GB SSD                                     | 1         | 1      | 1.15%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                       | 1         | 1      | 1.15%   |
| WDC WD7501AALS-00E3A0 752GB                            | 1         | 1      | 1.15%   |
| WDC WD7500AAKS-00RBA0 752GB                            | 1         | 2      | 1.15%   |
| WDC WD5003ABYZ-011FA0 500GB                            | 1         | 1      | 1.15%   |
| WDC WD5000LPVX-60V0TT0 500GB                           | 1         | 1      | 1.15%   |
| WDC WD5000LPLX-60ZNTT2 500GB                           | 1         | 1      | 1.15%   |
| WDC WD5000BEVT-22A0RT0 500GB                           | 1         | 1      | 1.15%   |
| WDC WD3200AAKS-00V1A0 320GB                            | 1         | 1      | 1.15%   |
| WDC WD2500KS-00MJB0 250GB                              | 1         | 1      | 1.15%   |
| WDC WD2500BEVT-80A23T0 250GB                           | 1         | 2      | 1.15%   |
| WDC WD2500BEVT-60ZCT1 250GB                            | 1         | 3      | 1.15%   |
| WDC WD20EARX-008FB0 2TB                                | 1         | 1      | 1.15%   |
| WDC WD2005FBYZ-01YCBB3 2TB                             | 1         | 1      | 1.15%   |
| WDC WD1200BEVS-60UST0 120GB                            | 1         | 1      | 1.15%   |
| WDC WD10EZEX-22RKKA0 1TB                               | 1         | 1      | 1.15%   |
| WDC WD1003FZEX-00K3CA0 1TB                             | 1         | 1      | 1.15%   |
| WDC WD1003FBYX-01Y7B0 1TB                              | 1         | 2      | 1.15%   |
| Toshiba MQ04ABF100 1TB                                 | 1         | 1      | 1.15%   |
| Toshiba MK1637GSX 160GB                                | 1         | 1      | 1.15%   |
| Toshiba HDWD110 1TB                                    | 1         | 1      | 1.15%   |
| Toshiba DT01ACA050 500GB                               | 1         | 1      | 1.15%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                  | 1         | 1      | 1.15%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB                | 1         | 1      | 1.15%   |
| Shenzhen Longsys Electronics FORESEE XP1000F512G 512GB | 1         | 1      | 1.15%   |
| Seagate STM3500418AS 500GB                             | 1         | 1      | 1.15%   |
| Seagate ST9640320AS 640GB                              | 1         | 1      | 1.15%   |
| Seagate ST9500530NS 42D0743 42D0746IBM 500GB           | 1         | 1      | 1.15%   |
| Seagate ST9500325AS 500GB                              | 1         | 1      | 1.15%   |
| Seagate ST9320423AS 320GB                              | 1         | 1      | 1.15%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 24        | 31     | 27.59%  |
| WDC                          | 21        | 29     | 24.14%  |
| Hitachi                      | 10        | 11     | 11.49%  |
| Toshiba                      | 6         | 6      | 6.9%    |
| XrayDisk                     | 3         | 3      | 3.45%   |
| HGST                         | 3         | 3      | 3.45%   |
| SK hynix                     | 2         | 2      | 2.3%    |
| Samsung Electronics          | 2         | 2      | 2.3%    |
| Intel                        | 2         | 2      | 2.3%    |
| GS                           | 2         | 5      | 2.3%    |
| Fujitsu                      | 2         | 2      | 2.3%    |
| AMD                          | 2         | 2      | 2.3%    |
| A-DATA Technology            | 2         | 2      | 2.3%    |
| Shenzhen Longsys Electronics | 1         | 1      | 1.15%   |
| OCZ                          | 1         | 1      | 1.15%   |
| Netac                        | 1         | 1      | 1.15%   |
| Kingston                     | 1         | 2      | 1.15%   |
| DEPO                         | 1         | 1      | 1.15%   |
| Corsair                      | 1         | 4      | 1.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 31     | 36.36%  |
| WDC                 | 20        | 28     | 30.3%   |
| Hitachi             | 10        | 11     | 15.15%  |
| Toshiba             | 6         | 6      | 9.09%   |
| HGST                | 3         | 3      | 4.55%   |
| Fujitsu             | 2         | 2      | 3.03%   |
| Samsung Electronics | 1         | 1      | 1.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 59        | 82     | 74.68%  |
| SSD  | 17        | 25     | 21.52%  |
| NVMe | 3         | 3      | 3.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5001AALS-00E3A0 500GB     | 1         | 1      | 50%     |
| Seagate ST250DM000-1BD141 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 606       | 1010   | 66.23%  |
| Detected | 229       | 424    | 25.03%  |
| Malfunc  | 78        | 110    | 8.52%   |
| Failed   | 2         | 2      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 616       | 51.98%  |
| AMD                              | 140       | 11.81%  |
| Samsung Electronics              | 71        | 5.99%   |
| Phison Electronics               | 55        | 4.64%   |
| INNOGRIT                         | 33        | 2.78%   |
| SK hynix                         | 31        | 2.62%   |
| Kingston Technology Company      | 29        | 2.45%   |
| SanDisk                          | 24        | 2.03%   |
| MAXIO Technology (Hangzhou)      | 19        | 1.6%    |
| Nvidia                           | 18        | 1.52%   |
| Silicon Motion                   | 16        | 1.35%   |
| ADATA Technology                 | 16        | 1.35%   |
| JMicron Technology               | 12        | 1.01%   |
| Broadcom / LSI                   | 12        | 1.01%   |
| Micron Technology                | 11        | 0.93%   |
| Shenzhen Longsys Electronics     | 10        | 0.84%   |
| ASMedia Technology               | 10        | 0.84%   |
| Realtek Semiconductor            | 9         | 0.76%   |
| Marvell Technology Group         | 6         | 0.51%   |
| KIOXIA                           | 5         | 0.42%   |
| Toshiba America Info Systems     | 4         | 0.34%   |
| Netac Technology                 | 4         | 0.34%   |
| Micron/Crucial Technology        | 4         | 0.34%   |
| Yangtze Memory Technologies      | 3         | 0.25%   |
| VIA Technologies                 | 3         | 0.25%   |
| Solid State Storage Technology   | 3         | 0.25%   |
| MCST                             | 3         | 0.25%   |
| Zhaoxin                          | 2         | 0.17%   |
| LSI Logic / Symbios Logic        | 2         | 0.17%   |
| Hosin Global Electronics         | 2         | 0.17%   |
| Hewlett-Packard                  | 2         | 0.17%   |
| Apple                            | 2         | 0.17%   |
| Unknown                          | 2         | 0.17%   |
| Union Memory (Shenzhen)          | 1         | 0.08%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.08%   |
| OCZ Technology Group             | 1         | 0.08%   |
| Loongson Technology              | 1         | 0.08%   |
| Jiangsu Huacun Elec.             | 1         | 0.08%   |
| Adaptec                          | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 91        | 6.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 75        | 5.6%    |
| Intel Tiger Lake-LP SATA Controller                                            | 59        | 4.41%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 48        | 3.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 39        | 2.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 39        | 2.91%   |
| INNOGRIT NVMe SSD Controller IG5216 (DRAM-less)                                | 33        | 2.46%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 28        | 2.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 27        | 2.02%   |
| AMD 400 Series Chipset SATA Controller                                         | 27        | 2.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 26        | 1.94%   |
| AMD 500 Series Chipset SATA Controller                                         | 25        | 1.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 22        | 1.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 22        | 1.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 1.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 18        | 1.34%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 18        | 1.34%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 16        | 1.19%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 16        | 1.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 15        | 1.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 13        | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 13        | 0.97%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 12        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 0.9%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 11        | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11        | 0.82%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 10        | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 0.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 10        | 0.75%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 10        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 0.75%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 9         | 0.67%   |
| Intel SSD 600P Series                                                          | 9         | 0.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 0.67%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 9         | 0.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 0.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 671       | 56.06%  |
| NVMe | 365       | 30.49%  |
| IDE  | 101       | 8.44%   |
| RAID | 54        | 4.51%   |
| SAS  | 5         | 0.42%   |
| SCSI | 1         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 654       | 76.31%  |
| AMD          | 190       | 22.17%  |
| ARM          | 5         | 0.58%   |
| CentaurHauls | 3         | 0.35%   |
| Loongson     | 1         | 0.12%   |
| Elbrus-MCST  | 1         | 0.12%   |
| EL2S4        | 1         | 0.12%   |
| E8C/EATX     | 1         | 0.12%   |
| E8C-SWTX     | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 55        | 6.4%    |
| Intel Core i3-6100TE CPU @ 2.70GHz          | 46        | 5.36%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 25        | 2.91%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 19        | 2.21%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 14        | 1.63%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 14        | 1.63%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 13        | 1.51%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 12        | 1.4%    |
| Intel Core i3-7100U CPU @ 2.40GHz           | 12        | 1.4%    |
| Intel Pentium CPU G4560 @ 3.50GHz           | 10        | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 10        | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 8         | 0.93%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 8         | 0.93%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 8         | 0.93%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 8         | 0.93%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 8         | 0.93%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 7         | 0.81%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 7         | 0.81%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 6         | 0.7%    |
| Intel Core i3-10100 CPU @ 3.60GHz           | 6         | 0.7%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6         | 0.7%    |
| Intel Xeon Silver 4210 CPU @ 2.20GHz        | 5         | 0.58%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 5         | 0.58%   |
| Intel 12th Gen Core i5-1235U                | 5         | 0.58%   |
| ARM Processor                               | 5         | 0.58%   |
| AMD Ryzen 5 5600 6-Core Processor           | 5         | 0.58%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GHz          | 4         | 0.47%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 4         | 0.47%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 0.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4         | 0.47%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 3         | 0.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.35%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3         | 0.35%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 3         | 0.35%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3         | 0.35%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3         | 0.35%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 3         | 0.35%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 3         | 0.35%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 3         | 0.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 161       | 18.76%  |
| Other                   | 137       | 15.97%  |
| Intel Core i3           | 137       | 15.97%  |
| AMD Ryzen 5             | 62        | 7.23%   |
| Intel Core i7           | 57        | 6.64%   |
| AMD Ryzen 7             | 38        | 4.43%   |
| Intel Celeron           | 35        | 4.08%   |
| Intel Pentium           | 25        | 2.91%   |
| Intel Xeon              | 23        | 2.68%   |
| Intel Core 2 Duo        | 23        | 2.68%   |
| Intel Pentium Dual-Core | 10        | 1.17%   |
| Intel Atom              | 10        | 1.17%   |
| AMD A8                  | 9         | 1.05%   |
| AMD A6                  | 9         | 1.05%   |
| Intel Pentium Gold      | 8         | 0.93%   |
| AMD Ryzen 9             | 8         | 0.93%   |
| AMD Ryzen 3             | 8         | 0.93%   |
| AMD A10                 | 7         | 0.82%   |
| Intel Xeon Silver       | 6         | 0.7%    |
| Intel Core 2 Quad       | 6         | 0.7%    |
| AMD FX                  | 6         | 0.7%    |
| AMD Athlon              | 6         | 0.7%    |
| AMD Phenom II X4        | 5         | 0.58%   |
| AMD Athlon 64 X2        | 5         | 0.58%   |
| Intel Pentium Silver    | 4         | 0.47%   |
| Intel Genuine           | 4         | 0.47%   |
| Intel Core i9           | 4         | 0.47%   |
| Intel Core 2            | 4         | 0.47%   |
| AMD E1                  | 3         | 0.35%   |
| AMD Athlon II X2        | 3         | 0.35%   |
| AMD A12                 | 3         | 0.35%   |
| Intel Xeon Gold         | 2         | 0.23%   |
| Intel Pentium Dual      | 2         | 0.23%   |
| Intel Core              | 2         | 0.23%   |
| AMD Ryzen 5 PRO         | 2         | 0.23%   |
| AMD E                   | 2         | 0.23%   |
| AMD Athlon II X4        | 2         | 0.23%   |
| Intel Pentium D         | 1         | 0.12%   |
| Intel Pentium 4         | 1         | 0.12%   |
| Intel Core m5           | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 306       | 35.58%  |
| 4       | 289       | 33.6%   |
| 6       | 122       | 14.19%  |
| 8       | 58        | 6.74%   |
| 1       | 20        | 2.33%   |
| 12      | 14        | 1.63%   |
| 10      | 14        | 1.63%   |
| 16      | 11        | 1.28%   |
| 14      | 9         | 1.05%   |
| 20      | 5         | 0.58%   |
| 32      | 3         | 0.35%   |
| 3       | 3         | 0.35%   |
| 28      | 2         | 0.23%   |
| 18      | 2         | 0.23%   |
| 7       | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 837       | 97.67%  |
| 2       | 16        | 1.87%   |
| 4       | 3         | 0.35%   |
| Unknown | 1         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 615       | 71.68%  |
| 1       | 242       | 28.21%  |
| Unknown | 1         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 843       | 98.37%  |
| 32-bit         | 7         | 0.82%   |
| Unknown        | 7         | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 269       | 30.81%  |
| 0x806c1    | 62        | 7.1%    |
| 0x506e3    | 54        | 6.19%   |
| 0x906ea    | 38        | 4.35%   |
| 0x1067a    | 25        | 2.86%   |
| 0x806ec    | 22        | 2.52%   |
| 0x806ea    | 21        | 2.41%   |
| 0x806e9    | 21        | 2.41%   |
| 0xa0653    | 20        | 2.29%   |
| 0x306a9    | 17        | 1.95%   |
| 0x0a50000c | 17        | 1.95%   |
| 0x08108109 | 15        | 1.72%   |
| 0x906e9    | 14        | 1.6%    |
| 0x08001138 | 14        | 1.6%    |
| 0x306c3    | 13        | 1.49%   |
| 0x206a7    | 12        | 1.37%   |
| 0x906eb    | 11        | 1.26%   |
| 0x806eb    | 10        | 1.15%   |
| 0xa0660    | 8         | 0.92%   |
| 0x50657    | 8         | 0.92%   |
| 0xa0671    | 7         | 0.8%    |
| 0x906a4    | 7         | 0.8%    |
| 0x06001119 | 7         | 0.8%    |
| 0x906a3    | 6         | 0.69%   |
| 0x706e5    | 6         | 0.69%   |
| 0x906ed    | 5         | 0.57%   |
| 0x90675    | 5         | 0.57%   |
| 0x6fd      | 5         | 0.57%   |
| 0x506c9    | 5         | 0.57%   |
| 0x406e3    | 5         | 0.57%   |
| 0x20655    | 5         | 0.57%   |
| 0x08600106 | 5         | 0.57%   |
| 0x806c2    | 4         | 0.46%   |
| 0x40651    | 4         | 0.46%   |
| 0x30678    | 4         | 0.46%   |
| 0x206d7    | 4         | 0.46%   |
| 0x106ca    | 4         | 0.46%   |
| 0x10676    | 4         | 0.46%   |
| 0x0a50000d | 4         | 0.46%   |
| 0x0a20120a | 4         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 172       | 20.02%  |
| Skylake           | 77        | 8.96%   |
| TigerLake         | 74        | 8.61%   |
| Unknown           | 60        | 6.98%   |
| Zen 3             | 45        | 5.24%   |
| CometLake         | 42        | 4.89%   |
| IvyBridge         | 38        | 4.42%   |
| SandyBridge       | 37        | 4.31%   |
| Penryn            | 34        | 3.96%   |
| Haswell           | 31        | 3.61%   |
| Zen+              | 26        | 3.03%   |
| Alderlake Hybrid  | 25        | 2.91%   |
| Zen               | 19        | 2.21%   |
| Westmere          | 16        | 1.86%   |
| Piledriver        | 15        | 1.75%   |
| Core              | 15        | 1.75%   |
| Silvermont        | 14        | 1.63%   |
| Icelake           | 13        | 1.51%   |
| Zen 2             | 12        | 1.4%    |
| K10               | 12        | 1.4%    |
| K8 Hammer         | 9         | 1.05%   |
| Goldmont plus     | 9         | 1.05%   |
| Excavator         | 8         | 0.93%   |
| Broadwell         | 7         | 0.81%   |
| Bonnell           | 7         | 0.81%   |
| Goldmont          | 6         | 0.7%    |
| Steamroller       | 5         | 0.58%   |
| K10 Llano         | 5         | 0.58%   |
| Nehalem           | 4         | 0.47%   |
| Bobcat            | 4         | 0.47%   |
| Tremont           | 3         | 0.35%   |
| Puma              | 3         | 0.35%   |
| P6                | 3         | 0.35%   |
| NetBurst          | 3         | 0.35%   |
| Jaguar            | 3         | 0.35%   |
| Meteorlake Hybrid | 2         | 0.23%   |
| Bulldozer         | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 528       | 56.05%  |
| AMD                        | 199       | 21.13%  |
| Nvidia                     | 190       | 20.17%  |
| Matrox Electronics Systems | 11        | 1.17%   |
| ASPEED Technology          | 6         | 0.64%   |
| Silicon Motion             | 3         | 0.32%   |
| Zhaoxin                    | 2         | 0.21%   |
| Huawei Technologies        | 2         | 0.21%   |
| VIA Technologies           | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 62        | 6.36%   |
| Intel HD Graphics 530                                                                    | 54        | 5.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 39        | 4%      |
| Intel HD Graphics 620                                                                    | 29        | 2.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 27        | 2.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 27        | 2.77%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 24        | 2.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 2.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 21        | 2.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 2.15%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 14        | 1.44%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 12        | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.23%   |
| AMD Lucienne                                                                             | 11        | 1.13%   |
| Intel HD Graphics 610                                                                    | 10        | 1.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.03%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 9         | 0.92%   |
| Intel UHD Graphics 620                                                                   | 9         | 0.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 0.92%   |
| Intel HD Graphics 630                                                                    | 8         | 0.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 0.82%   |
| Intel Comet Lake UHD Graphics                                                            | 8         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 0.82%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 8         | 0.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.72%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 7         | 0.72%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 0.62%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 0.62%   |
| Matrox Electronics Systems MGA G200EH                                                    | 6         | 0.62%   |
| Intel HD Graphics 510                                                                    | 6         | 0.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.62%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 6         | 0.62%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6         | 0.62%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 5         | 0.51%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 5         | 0.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 0.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 452       | 52.44%  |
| 1 x AMD                 | 154       | 17.87%  |
| 1 x Nvidia              | 123       | 14.27%  |
| Intel + Nvidia          | 55        | 6.38%   |
| 2 x AMD                 | 22        | 2.55%   |
| 1 x Matrox              | 11        | 1.28%   |
| Intel + AMD             | 11        | 1.28%   |
| AMD + Nvidia            | 11        | 1.28%   |
| Other                   | 8         | 0.93%   |
| 1 x ASPEED              | 6         | 0.7%    |
| 1 x Silicon Motion      | 3         | 0.35%   |
| 1 x Huawei Technologies | 2         | 0.23%   |
| 2 x Intel               | 1         | 0.12%   |
| 1 x Zhaoxin             | 1         | 0.12%   |
| 1 x VIA                 | 1         | 0.12%   |
| Nvidia + Zhaoxin        | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 707       | 81.83%  |
| Proprietary | 114       | 13.19%  |
| Unknown     | 43        | 4.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 621       | 71.13%  |
| 0.01-0.5   | 78        | 8.93%   |
| 0.51-1.0   | 47        | 5.38%   |
| 3.01-4.0   | 43        | 4.93%   |
| 1.01-2.0   | 41        | 4.7%    |
| 7.01-8.0   | 18        | 2.06%   |
| 8.01-16.0  | 14        | 1.6%    |
| 5.01-6.0   | 8         | 0.92%   |
| 2.01-3.0   | 3         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 101       | 11.4%   |
| Samsung Electronics     | 88        | 9.93%   |
| Chimei Innolux          | 75        | 8.47%   |
| AU Optronics            | 58        | 6.55%   |
| Acer                    | 49        | 5.53%   |
| HHT                     | 48        | 5.42%   |
| BenQ                    | 45        | 5.08%   |
| LG Display              | 43        | 4.85%   |
| AOC                     | 38        | 4.29%   |
| Goldstar                | 34        | 3.84%   |
| Philips                 | 25        | 2.82%   |
| Dell                    | 25        | 2.82%   |
| ECS                     | 22        | 2.48%   |
| ViewSonic               | 16        | 1.81%   |
| PANDA                   | 16        | 1.81%   |
| Lenovo                  | 15        | 1.69%   |
| Hewlett-Packard         | 10        | 1.13%   |
| Chi Mei Optoelectronics | 10        | 1.13%   |
| Sharp                   | 9         | 1.02%   |
| Apple                   | 9         | 1.02%   |
| Ancor Communications    | 8         | 0.9%    |
| MSI                     | 7         | 0.79%   |
| Iiyama                  | 7         | 0.79%   |
| CHR                     | 7         | 0.79%   |
| STA                     | 6         | 0.68%   |
| RTK                     | 6         | 0.68%   |
| ASUSTek Computer        | 6         | 0.68%   |
| PRM                     | 5         | 0.56%   |
| AGO                     | 5         | 0.56%   |
| PRW                     | 4         | 0.45%   |
| NEC Computers           | 4         | 0.45%   |
| HannStar                | 4         | 0.45%   |
| WBT                     | 3         | 0.34%   |
| VIE                     | 3         | 0.34%   |
| TMX                     | 3         | 0.34%   |
| SKG                     | 3         | 0.34%   |
| OOO                     | 3         | 0.34%   |
| LG Electronics          | 3         | 0.34%   |
| HUAWEI                  | 3         | 0.34%   |
| HKC                     | 3         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch              | 48        | 5.34%   |
| ECS AIO PC ECS2486 1920x1080 520x300mm 23.6-inch                     | 22        | 2.45%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 13        | 1.45%   |
| AOC LCD Monitor 2778X 2560x1440                                      | 11        | 1.22%   |
| Lenovo LEN-M90a-3-BA LENE288 1920x1080 527x296mm 23.8-inch           | 10        | 1.11%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 10        | 1.11%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                    | 10        | 1.11%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch              | 9         | 1%      |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch     | 9         | 1%      |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 8         | 0.89%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                       | 8         | 0.89%   |
| BOE LCD Monitor BOE09C5 1920x1080 341x192mm 15.4-inch                | 7         | 0.78%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                | 6         | 0.67%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                    | 6         | 0.67%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                | 6         | 0.67%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 6         | 0.67%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 5         | 0.56%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 5         | 0.56%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch       | 5         | 0.56%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch        | 4         | 0.44%   |
| RTK HDMI RTK2380 1920x1080 530x290mm 23.8-inch                       | 4         | 0.44%   |
| PRW AP7_Titanium PRW4200 3840x2160                                   | 4         | 0.44%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 4         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 4         | 0.44%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 4         | 0.44%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                   | 4         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.44%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                     | 4         | 0.44%   |
| AOC 22P1W AOC2201 1920x1080 477x268mm 21.5-inch                      | 4         | 0.44%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                     | 3         | 0.33%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch              | 3         | 0.33%   |
| Sharp LCD Monitor SHP1540 1920x1080 309x174mm 14.0-inch              | 3         | 0.33%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 3         | 0.33%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 3         | 0.33%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch               | 3         | 0.33%   |
| Dell E2417H DELA0E2 1920x1080 527x296mm 23.8-inch                    | 3         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 3         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 476       | 56.07%  |
| 1366x768 (WXGA)    | 80        | 9.42%   |
| 3840x2160 (4K)     | 73        | 8.6%    |
| 2560x1440 (QHD)    | 49        | 5.77%   |
| 1280x1024 (SXGA)   | 40        | 4.71%   |
| 1680x1050 (WSXGA+) | 21        | 2.47%   |
| 1600x900 (HD+)     | 21        | 2.47%   |
| 1920x1200 (WUXGA)  | 16        | 1.88%   |
| 1280x800 (WXGA)    | 14        | 1.65%   |
| 1440x900 (WXGA+)   | 10        | 1.18%   |
| 2560x1600          | 5         | 0.59%   |
| Unknown            | 5         | 0.59%   |
| 1360x768           | 4         | 0.47%   |
| 1024x600           | 4         | 0.47%   |
| 2560x1080          | 3         | 0.35%   |
| 1600x1200          | 3         | 0.35%   |
| 3840x1080          | 2         | 0.24%   |
| 2880x1800          | 2         | 0.24%   |
| 2160x1440          | 2         | 0.24%   |
| 800x1280           | 1         | 0.12%   |
| 4480x1440          | 1         | 0.12%   |
| 3840x2560          | 1         | 0.12%   |
| 3840x1600          | 1         | 0.12%   |
| 3840x1440          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 3072x1920          | 1         | 0.12%   |
| 3000x2000          | 1         | 0.12%   |
| 2880x1920          | 1         | 0.12%   |
| 2880x1620          | 1         | 0.12%   |
| 2520x1680          | 1         | 0.12%   |
| 2288x1287          | 1         | 0.12%   |
| 2240x1400          | 1         | 0.12%   |
| 2160x1200          | 1         | 0.12%   |
| 1920x540           | 1         | 0.12%   |
| 1400x1050          | 1         | 0.12%   |
| 1280x960           | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |
| 1024x768 (XGA)     | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 183       | 20.75%  |
| 23      | 95        | 10.77%  |
| 24      | 88        | 9.98%   |
| 14      | 63        | 7.14%   |
| 13      | 62        | 7.03%   |
| 21      | 61        | 6.92%   |
| 17      | 53        | 6.01%   |
| 40      | 52        | 5.9%    |
| 27      | 49        | 5.56%   |
| Unknown | 44        | 4.99%   |
| 19      | 27        | 3.06%   |
| 31      | 14        | 1.59%   |
| 22      | 12        | 1.36%   |
| 12      | 12        | 1.36%   |
| 16      | 10        | 1.13%   |
| 18      | 7         | 0.79%   |
| 26      | 6         | 0.68%   |
| 20      | 6         | 0.68%   |
| 11      | 6         | 0.68%   |
| 32      | 4         | 0.45%   |
| 10      | 4         | 0.45%   |
| 28      | 3         | 0.34%   |
| 72      | 2         | 0.23%   |
| 54      | 2         | 0.23%   |
| 52      | 2         | 0.23%   |
| 142     | 1         | 0.11%   |
| 85      | 1         | 0.11%   |
| 59      | 1         | 0.11%   |
| 57      | 1         | 0.11%   |
| 50      | 1         | 0.11%   |
| 46      | 1         | 0.11%   |
| 42      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 37      | 1         | 0.11%   |
| 34      | 1         | 0.11%   |
| 33      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |
| 25      | 1         | 0.11%   |
| 8       | 1         | 0.11%   |
| 7       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 316       | 36.2%   |
| 501-600        | 227       | 26%     |
| 401-500        | 98        | 11.23%  |
| 901-1000       | 50        | 5.73%   |
| 351-400        | 47        | 5.38%   |
| Unknown        | 44        | 5.04%   |
| 201-300        | 43        | 4.93%   |
| 601-700        | 23        | 2.63%   |
| 701-800        | 7         | 0.8%    |
| 1001-1500      | 7         | 0.8%    |
| 801-900        | 5         | 0.57%   |
| 1501-2000      | 3         | 0.34%   |
| More than 2000 | 1         | 0.11%   |
| 101-200        | 1         | 0.11%   |
| 1-100          | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 600       | 72.64%  |
| 16/10   | 82        | 9.93%   |
| 21/9    | 52        | 6.3%    |
| 5/4     | 38        | 4.6%    |
| Unknown | 27        | 3.27%   |
| 4/3     | 14        | 1.69%   |
| 3/2     | 9         | 1.09%   |
| 6/5     | 1         | 0.12%   |
| 1.00    | 1         | 0.12%   |
| 0.67    | 1         | 0.12%   |
| 0.56    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 207       | 23.79%  |
| 101-110        | 188       | 21.61%  |
| 81-90          | 112       | 12.87%  |
| 501-1000       | 56        | 6.44%   |
| 301-350        | 55        | 6.32%   |
| 151-200        | 45        | 5.17%   |
| Unknown        | 44        | 5.06%   |
| 251-300        | 29        | 3.33%   |
| 121-130        | 29        | 3.33%   |
| 141-150        | 26        | 2.99%   |
| 351-500        | 23        | 2.64%   |
| 71-80          | 14        | 1.61%   |
| More than 1000 | 11        | 1.26%   |
| 61-70          | 8         | 0.92%   |
| 111-120        | 8         | 0.92%   |
| 51-60          | 6         | 0.69%   |
| 41-50          | 4         | 0.46%   |
| 1-40           | 2         | 0.23%   |
| 131-140        | 2         | 0.23%   |
| 91-100         | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 303       | 35.15%  |
| 121-160       | 271       | 31.44%  |
| 101-120       | 196       | 22.74%  |
| Unknown       | 44        | 5.1%    |
| 161-240       | 29        | 3.36%   |
| 1-50          | 14        | 1.62%   |
| More than 240 | 5         | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 738       | 84.83%  |
| 2     | 89        | 10.23%  |
| 0     | 41        | 4.71%   |
| 3     | 2         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 515       | 42.32%  |
| Intel                           | 416       | 34.18%  |
| Qualcomm Atheros                | 83        | 6.82%   |
| Broadcom                        | 42        | 3.45%   |
| MediaTek                        | 22        | 1.81%   |
| Nvidia                          | 15        | 1.23%   |
| Marvell Technology Group        | 14        | 1.15%   |
| Broadcom Limited                | 12        | 0.99%   |
| Ralink Technology               | 9         | 0.74%   |
| D-Link                          | 9         | 0.74%   |
| Ralink                          | 7         | 0.58%   |
| ASIX Electronics                | 7         | 0.58%   |
| TP-Link                         | 5         | 0.41%   |
| IBM                             | 5         | 0.41%   |
| Huawei Technologies             | 5         | 0.41%   |
| ASUSTek Computer                | 4         | 0.33%   |
| Xiaomi                          | 3         | 0.25%   |
| VIA Technologies                | 3         | 0.25%   |
| Qualcomm                        | 3         | 0.25%   |
| Microchip Technology            | 3         | 0.25%   |
| MCST                            | 3         | 0.25%   |
| JMicron Technology              | 3         | 0.25%   |
| ZTopInc                         | 2         | 0.16%   |
| U-Blox                          | 2         | 0.16%   |
| Sierra Wireless                 | 2         | 0.16%   |
| Mercucys                        | 2         | 0.16%   |
| Emulex                          | 2         | 0.16%   |
| D-Link System                   | 2         | 0.16%   |
| Attansic Technology             | 2         | 0.16%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.08%   |
| Vimtron Electronics             | 1         | 0.08%   |
| T & A Mobile Phones             | 1         | 0.08%   |
| Samsung Electronics             | 1         | 0.08%   |
| Qualcomm Atheros Communications | 1         | 0.08%   |
| Motorola PCS                    | 1         | 0.08%   |
| Microsoft                       | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| Mellanox Technologies           | 1         | 0.08%   |
| Loongson Technology             | 1         | 0.08%   |
| Lenovo                          | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 370       | 25.19%  |
| Intel Wi-Fi 6 AX201                                                    | 60        | 4.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 51        | 3.47%   |
| Intel Ethernet Connection (13) I219-V                                  | 48        | 3.27%   |
| Intel Ethernet Connection I219-LM                                      | 37        | 2.52%   |
| Intel Wi-Fi 6 AX200                                                    | 26        | 1.77%   |
| Intel Wireless 7265                                                    | 25        | 1.7%    |
| Intel Wireless 3165                                                    | 23        | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 21        | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                      | 21        | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 19        | 1.29%   |
| Intel Wireless 8265 / 8275                                             | 19        | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18        | 1.23%   |
| Intel Ethernet Connection (10) I219-V                                  | 17        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 17        | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 16        | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 13        | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 12        | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 0.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                                  | 12        | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 12        | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 0.75%   |
| Intel Ethernet Connection (6) I219-V                                   | 11        | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 11        | 0.75%   |
| Intel Ethernet Connection (14) I219-V                                  | 10        | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.61%   |
| Intel Ethernet Controller I225-V                                       | 9         | 0.61%   |
| Intel Ethernet Connection (17) I219-V                                  | 9         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.54%   |
| Intel I350 Gigabit Network Connection                                  | 8         | 0.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 0.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 7         | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 7         | 0.48%   |
| Intel Wireless 7260                                                    | 7         | 0.48%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 0.48%   |
| Intel Ethernet Connection X722 for 1GbE                                | 7         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 293       | 52.89%  |
| Realtek Semiconductor           | 105       | 18.95%  |
| Qualcomm Atheros                | 58        | 10.47%  |
| Broadcom                        | 32        | 5.78%   |
| MediaTek                        | 19        | 3.43%   |
| Ralink Technology               | 9         | 1.62%   |
| Broadcom Limited                | 8         | 1.44%   |
| Ralink                          | 7         | 1.26%   |
| TP-Link                         | 5         | 0.9%    |
| ASUSTek Computer                | 4         | 0.72%   |
| ZTopInc                         | 2         | 0.36%   |
| Sierra Wireless                 | 2         | 0.36%   |
| Qualcomm                        | 2         | 0.36%   |
| Mercucys                        | 2         | 0.36%   |
| D-Link                          | 2         | 0.36%   |
| Qualcomm Atheros Communications | 1         | 0.18%   |
| Microsoft                       | 1         | 0.18%   |
| Micro Star International        | 1         | 0.18%   |
| D-Link System                   | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 60        | 10.77%  |
| Intel Wi-Fi 6 AX200                                                     | 26        | 4.67%   |
| Intel Wireless 7265                                                     | 25        | 4.49%   |
| Intel Wireless 3165                                                     | 23        | 4.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 21        | 3.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 3.41%   |
| Intel Wireless 8265 / 8275                                              | 19        | 3.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 17        | 3.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 2.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 13        | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 2.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 12        | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 1.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 1.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 7         | 1.26%   |
| Intel Wireless 7260                                                     | 7         | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 1.08%   |
| Realtek 802.11ac NIC                                                    | 6         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 6         | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 0.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.72%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 4         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.72%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 480       | 55.17%  |
| Intel                    | 252       | 28.97%  |
| Qualcomm Atheros         | 38        | 4.37%   |
| Nvidia                   | 15        | 1.72%   |
| Marvell Technology Group | 14        | 1.61%   |
| Broadcom                 | 13        | 1.49%   |
| D-Link                   | 7         | 0.8%    |
| ASIX Electronics         | 7         | 0.8%    |
| IBM                      | 5         | 0.57%   |
| Huawei Technologies      | 5         | 0.57%   |
| Broadcom Limited         | 4         | 0.46%   |
| Xiaomi                   | 3         | 0.34%   |
| VIA Technologies         | 3         | 0.34%   |
| MediaTek                 | 3         | 0.34%   |
| MCST                     | 3         | 0.34%   |
| JMicron Technology       | 3         | 0.34%   |
| Emulex                   | 2         | 0.23%   |
| Attansic Technology      | 2         | 0.23%   |
| Vimtron Electronics      | 1         | 0.11%   |
| TP-Link                  | 1         | 0.11%   |
| Samsung Electronics      | 1         | 0.11%   |
| Qualcomm                 | 1         | 0.11%   |
| Motorola PCS             | 1         | 0.11%   |
| Mellanox Technologies    | 1         | 0.11%   |
| Loongson Technology      | 1         | 0.11%   |
| Lenovo                   | 1         | 0.11%   |
| DisplayLink              | 1         | 0.11%   |
| D-Link System            | 1         | 0.11%   |
| American Megatrends      | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 370       | 41.02%  |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 51        | 5.65%   |
| Intel Ethernet Connection (13) I219-V                                  | 48        | 5.32%   |
| Intel Ethernet Connection I219-LM                                      | 37        | 4.1%    |
| Realtek RTL8125 2.5GbE Controller                                      | 21        | 2.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18        | 2%      |
| Intel Ethernet Connection (10) I219-V                                  | 17        | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 1.33%   |
| Intel Ethernet Connection (7) I219-LM                                  | 12        | 1.33%   |
| Intel Ethernet Connection (6) I219-V                                   | 11        | 1.22%   |
| Intel Ethernet Connection (14) I219-V                                  | 10        | 1.11%   |
| Intel Ethernet Controller I225-V                                       | 9         | 1%      |
| Intel Ethernet Connection (17) I219-V                                  | 9         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.89%   |
| Intel I350 Gigabit Network Connection                                  | 8         | 0.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 0.89%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 7         | 0.78%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 0.78%   |
| Intel Ethernet Connection X722 for 1GbE                                | 7         | 0.78%   |
| Intel I210 Gigabit Network Connection                                  | 6         | 0.67%   |
| Intel Ethernet Connection X722 for 10GBASE-T                           | 6         | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.55%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                          | 5         | 0.55%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 0.55%   |
| IBM RNDIS/CDC ETHER                                                    | 5         | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.44%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 0.44%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.44%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                               | 4         | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.33%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3         | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 3         | 0.33%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 3         | 0.33%   |
| Nvidia MCP77 Ethernet                                                  | 3         | 0.33%   |
| Nvidia MCP51 Ethernet Controller                                       | 3         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 775       | 58.53%  |
| WiFi     | 539       | 40.71%  |
| Modem    | 9         | 0.68%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 486       | 55.42%  |
| WiFi     | 391       | 44.58%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 433       | 50.41%  |
| 1     | 391       | 45.52%  |
| 0     | 15        | 1.75%   |
| 3     | 7         | 0.81%   |
| 6     | 6         | 0.7%    |
| 4     | 4         | 0.47%   |
| 13    | 1         | 0.12%   |
| 12    | 1         | 0.12%   |
| 8     | 1         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 814       | 94.32%  |
| Yes  | 49        | 5.68%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 271       | 57.17%  |
| Realtek Semiconductor           | 50        | 10.55%  |
| IMC Networks                    | 27        | 5.7%    |
| Cambridge Silicon Radio         | 21        | 4.43%   |
| Broadcom                        | 18        | 3.8%    |
| Foxconn / Hon Hai               | 16        | 3.38%   |
| Lite-On Technology              | 12        | 2.53%   |
| Qualcomm Atheros Communications | 10        | 2.11%   |
| MediaTek                        | 8         | 1.69%   |
| Apple                           | 8         | 1.69%   |
| Hewlett-Packard                 | 7         | 1.48%   |
| Realtek                         | 5         | 1.05%   |
| ASUSTek Computer                | 5         | 1.05%   |
| TP-Link                         | 3         | 0.63%   |
| Ralink                          | 2         | 0.42%   |
| Foxconn International           | 2         | 0.42%   |
| Actions                         | 2         | 0.42%   |
| USI                             | 1         | 0.21%   |
| Toshiba                         | 1         | 0.21%   |
| Opticis                         | 1         | 0.21%   |
| Logitech                        | 1         | 0.21%   |
| HTC (High Tech Computer)        | 1         | 0.21%   |
| Dell                            | 1         | 0.21%   |
| Chicony Electronics             | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 82        | 17.3%   |
| Intel AX201 Bluetooth                               | 80        | 16.88%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 47        | 9.92%   |
| Realtek Bluetooth Radio                             | 34        | 7.17%   |
| Intel AX200 Bluetooth                               | 26        | 5.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21        | 4.43%   |
| Intel Wireless-AC 3168 Bluetooth                    | 17        | 3.59%   |
| IMC Networks Wireless_Device                        | 10        | 2.11%   |
| Intel AX211 Bluetooth                               | 9         | 1.9%    |
| MediaTek Wireless_Device                            | 8         | 1.69%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.48%   |
| IMC Networks Bluetooth Device                       | 7         | 1.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 1.27%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.27%   |
| Apple Bluetooth Host Controller                     | 6         | 1.27%   |
| Realtek Bluetooth Radio                             | 5         | 1.05%   |
| Realtek 802.11ac WLAN Adapter                       | 4         | 0.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.84%   |
| Intel AX210 Bluetooth                               | 4         | 0.84%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.84%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 0.84%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.84%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 3         | 0.63%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.63%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.42%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.42%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 2         | 0.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.42%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.42%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.42%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.42%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.42%   |
| ASUS 2045 Bluetooth 2.0 Device with trace filter    | 2         | 0.42%   |
| Actions general adapter                             | 2         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 623       | 56.08%  |
| AMD                                          | 216       | 19.44%  |
| Nvidia                                       | 150       | 13.5%   |
| C-Media Electronics                          | 46        | 4.14%   |
| JMTek                                        | 8         | 0.72%   |
| Promethean Limited                           | 7         | 0.63%   |
| Creative Technology                          | 5         | 0.45%   |
| Logitech                                     | 4         | 0.36%   |
| ASUSTek Computer                             | 4         | 0.36%   |
| VIA Technologies                             | 3         | 0.27%   |
| MCST                                         | 3         | 0.27%   |
| Creative Labs                                | 3         | 0.27%   |
| Apple                                        | 3         | 0.27%   |
| Zhaoxin                                      | 2         | 0.18%   |
| Realtek Semiconductor                        | 2         | 0.18%   |
| GN Netcom                                    | 2         | 0.18%   |
| Generalplus Technology                       | 2         | 0.18%   |
| Focusrite-Novation                           | 2         | 0.18%   |
| FIFINE Microphones                           | 2         | 0.18%   |
| A4Tech                                       | 2         | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.09%   |
| Texas Instruments                            | 1         | 0.09%   |
| Tenx Technology                              | 1         | 0.09%   |
| Sony                                         | 1         | 0.09%   |
| Plantronics                                  | 1         | 0.09%   |
| Onkyo                                        | 1         | 0.09%   |
| Micro Star International                     | 1         | 0.09%   |
| Loongson Technology                          | 1         | 0.09%   |
| Lenovo                                       | 1         | 0.09%   |
| KTMicro                                      | 1         | 0.09%   |
| Jieli Technology                             | 1         | 0.09%   |
| Huawei Technologies                          | 1         | 0.09%   |
| Hewlett-Packard                              | 1         | 0.09%   |
| Goldvish                                     | 1         | 0.09%   |
| Giga-Byte Technology                         | 1         | 0.09%   |
| Evolution Electronics                        | 1         | 0.09%   |
| ESI Audiotechnik                             | 1         | 0.09%   |
| EasyPass Industrial                          | 1         | 0.09%   |
| DSEA A/S                                     | 1         | 0.09%   |
| Cirrus Logic                                 | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 79        | 6.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 75        | 5.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 74        | 5.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 48        | 3.77%   |
| Intel Sunrise Point-LP HD Audio                                            | 45        | 3.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 41        | 3.22%   |
| Intel 200 Series PCH HD Audio                                              | 39        | 3.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 36        | 2.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 33        | 2.59%   |
| C-Media Electronics USB Advanced Audio Device                              | 33        | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 31        | 2.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 27        | 2.12%   |
| AMD FCH Azalia Controller                                                  | 27        | 2.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 22        | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 1.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 21        | 1.65%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 20        | 1.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 20        | 1.57%   |
| Intel Comet Lake PCH-LP cAVS                                               | 18        | 1.41%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 17        | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 16        | 1.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16        | 1.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 1.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 16        | 1.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 1.18%   |
| Intel Alder Lake-S HD Audio Controller                                     | 12        | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 11        | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10        | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 0.71%   |
| Nvidia High Definition Audio Controller                                    | 9         | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 9         | 0.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 0.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 0.71%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 0.71%   |
| AMD Trinity HDMI Audio Controller                                          | 9         | 0.71%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 123       | 18.11%  |
| Crucial                      | 84        | 12.37%  |
| Kingston                     | 75        | 11.05%  |
| SK hynix                     | 74        | 10.9%   |
| Unknown                      | 63        | 9.28%   |
| Micron Technology            | 45        | 6.63%   |
| ACPI Digital                 | 32        | 4.71%   |
| A-DATA Technology            | 24        | 3.53%   |
| Ramaxel Technology           | 16        | 2.36%   |
| Foxline                      | 15        | 2.21%   |
| Apacer                       | 13        | 1.91%   |
| Unknown                      | 13        | 1.91%   |
| Patriot                      | 11        | 1.62%   |
| Corsair                      | 10        | 1.47%   |
| AMD                          | 10        | 1.47%   |
| Elpida                       | 8         | 1.18%   |
| Unknown (ABCD)               | 7         | 1.03%   |
| G.Skill                      | 7         | 1.03%   |
| Hewlett-Packard              | 6         | 0.88%   |
| Nanya Technology             | 5         | 0.74%   |
| GOODRAM                      | 4         | 0.59%   |
| Lexar Co Limited             | 3         | 0.44%   |
| ChangXin Memory              | 3         | 0.44%   |
| Unknown (0x7FFF)             | 2         | 0.29%   |
| Unknown (0B7A)               | 2         | 0.29%   |
| Shenzhen Longsys             | 2         | 0.29%   |
| Qumo                         | 2         | 0.29%   |
| Goldkey                      | 2         | 0.29%   |
| Wilk                         | 1         | 0.15%   |
| Unknown (0x0B92)             | 1         | 0.15%   |
| Unknown (0x0B7A)             | 1         | 0.15%   |
| Unknown (081A)               | 1         | 0.15%   |
| Transcend                    | 1         | 0.15%   |
| tigo                         | 1         | 0.15%   |
| Shenzhen WODPOSIT            | 1         | 0.15%   |
| Shenzhen Jinge Information   | 1         | 0.15%   |
| Shenzhen Giant Hui Kang Tech | 1         | 0.15%   |
| SHARETRONIC                  | 1         | 0.15%   |
| Patriot Memory (PDP Systems) | 1         | 0.15%   |
| Patriot Memory               | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| ACPI Digital RAM CMB6-DHDA1BAR08D00 16GB SODIMM DDR4 3200MT/s    | 32        | 4.51%   |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s          | 17        | 2.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 1.83%   |
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2666MT/s             | 13        | 1.83%   |
| Unknown                                                          | 13        | 1.83%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 10        | 1.41%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                         | 10        | 1.41%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 9         | 1.27%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 7         | 0.99%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 7         | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 6         | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.85%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 6         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.71%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 5         | 0.71%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.71%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.71%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.71%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s           | 5         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.56%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 4         | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 4         | 0.56%   |
| Samsung RAM M393A2K43CB2-CVF 16384MB DIMM DDR4 2933MT/s          | 4         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.56%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 4         | 0.56%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s           | 4         | 0.56%   |
| HP RAM Module 4GB DIMM DDR3 1333MT/s                             | 4         | 0.56%   |
| Apacer RAM D12.2755BS.001 16GB DIMM DDR4 3200MT/s                | 4         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.42%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 0.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.42%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.42%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 3         | 0.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.42%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 3         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 402       | 64.32%  |
| DDR3    | 110       | 17.6%   |
| DDR2    | 31        | 4.96%   |
| LPDDR4  | 26        | 4.16%   |
| Unknown | 19        | 3.04%   |
| DDR5    | 16        | 2.56%   |
| SDRAM   | 8         | 1.28%   |
| LPDDR5  | 8         | 1.28%   |
| DDR     | 3         | 0.48%   |
| LPDDR3  | 1         | 0.16%   |
| DRAM    | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 351       | 56.25%  |
| DIMM         | 234       | 37.5%   |
| Row Of Chips | 39        | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 276       | 42.46%  |
| 4096  | 155       | 23.85%  |
| 16384 | 113       | 17.38%  |
| 2048  | 62        | 9.54%   |
| 1024  | 23        | 3.54%   |
| 32768 | 13        | 2%      |
| 512   | 5         | 0.77%   |
| 65536 | 2         | 0.31%   |
| 1536  | 1         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 146       | 22.05%  |
| 2667    | 134       | 20.24%  |
| 1600    | 68        | 10.27%  |
| 2400    | 58        | 8.76%   |
| 2133    | 30        | 4.53%   |
| 1333    | 21        | 3.17%   |
| 2666    | 17        | 2.57%   |
| 667     | 17        | 2.57%   |
| 1334    | 16        | 2.42%   |
| Unknown | 16        | 2.42%   |
| 2933    | 13        | 1.96%   |
| 800     | 13        | 1.96%   |
| 4800    | 9         | 1.36%   |
| 4267    | 9         | 1.36%   |
| 3733    | 8         | 1.21%   |
| 3266    | 8         | 1.21%   |
| 6400    | 6         | 0.91%   |
| 3600    | 6         | 0.91%   |
| 3466    | 4         | 0.6%    |
| 1866    | 4         | 0.6%    |
| 1067    | 4         | 0.6%    |
| 533     | 4         | 0.6%    |
| 400     | 4         | 0.6%    |
| 6000    | 3         | 0.45%   |
| 4000    | 3         | 0.45%   |
| 3800    | 3         | 0.45%   |
| 3000    | 3         | 0.45%   |
| 333     | 3         | 0.45%   |
| 5600    | 2         | 0.3%    |
| 4199    | 2         | 0.3%    |
| 3333    | 2         | 0.3%    |
| 3066    | 2         | 0.3%    |
| 2866    | 2         | 0.3%    |
| 2800    | 2         | 0.3%    |
| 1867    | 2         | 0.3%    |
| 1066    | 2         | 0.3%    |
| 8600    | 1         | 0.15%   |
| 7467    | 1         | 0.15%   |
| 6800    | 1         | 0.15%   |
| 5200    | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Canon                  | 13        | 26%     |
| Samsung Electronics    | 11        | 22%     |
| Hewlett-Packard        | 7         | 14%     |
| Pantum                 | 5         | 10%     |
| Brother Industries     | 4         | 8%      |
| Xerox                  | 2         | 4%      |
| Ricoh                  | 2         | 4%      |
| QinHeng Electronics    | 2         | 4%      |
| Kyocera                | 2         | 4%      |
| Seiko Epson            | 1         | 2%      |
| Panasonic (Matsushita) | 1         | 2%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SCX-3400 Series              | 4         | 8%      |
| Pantum P2200 series                  | 3         | 6%      |
| QinHeng CH340S                       | 2         | 4%      |
| HP LaserJet P1102                    | 2         | 4%      |
| HP LaserJet 1010                     | 2         | 4%      |
| Canon MF4410                         | 2         | 4%      |
| Canon MF4010 series                  | 2         | 4%      |
| Brother HL-L2300D series             | 2         | 4%      |
| Xerox WorkCentre 5222                | 1         | 2%      |
| Xerox WorkCentre 3220                | 1         | 2%      |
| Seiko Epson EPSON L132 Series        | 1         | 2%      |
| Samsung SCX-4200 series              | 1         | 2%      |
| Samsung SCX-4100 Scanner             | 1         | 2%      |
| Samsung SCX-3200 Series              | 1         | 2%      |
| Samsung ML-2010P Mono Laser Printer  | 1         | 2%      |
| Samsung ML-1640 Series Laser Printer | 1         | 2%      |
| Samsung M332x 382x 402x Series       | 1         | 2%      |
| Samsung CLX-3180 Series              | 1         | 2%      |
| Ricoh SP 213SUw                      | 1         | 2%      |
| Ricoh Aficio SP C240DN               | 1         | 2%      |
| Pantum M6500W series                 | 1         | 2%      |
| Pantum M6500-series                  | 1         | 2%      |
| Panasonic (Matsushita) KX-MB283RU    | 1         | 2%      |
| Kyocera FS-1135MFP                   | 1         | 2%      |
| Kyocera FS-1040                      | 1         | 2%      |
| HP LaserJet M402dn                   | 1         | 2%      |
| HP LaserJet 3055                     | 1         | 2%      |
| HP HP LaserJet Pro M428-M429         | 1         | 2%      |
| Canon PIXMA MP280                    | 1         | 2%      |
| Canon PIXMA MP190                    | 1         | 2%      |
| Canon MF420 Series                   | 1         | 2%      |
| Canon MF3110                         | 1         | 2%      |
| Canon imageRUNNER1133 series         | 1         | 2%      |
| Canon I-SENSYS MF4550d               | 1         | 2%      |
| Canon G3010 series                   | 1         | 2%      |
| Canon G1010 series                   | 1         | 2%      |
| Canon CanoScan LiDE 300              | 1         | 2%      |
| Brother DCP-7030                     | 1         | 2%      |
| Brother DCP-1510                     | 1         | 2%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 66.67%  |
| Canon CanoScan LIDE 25  | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 90        | 18.67%  |
| Bison Electronics                      | 46        | 9.54%   |
| IMC Networks                           | 36        | 7.47%   |
| Cheng Uei Precision Industry (Foxlink) | 36        | 7.47%   |
| Realtek Semiconductor                  | 33        | 6.85%   |
| Sunplus Innovation Technology          | 30        | 6.22%   |
| Logitech                               | 29        | 6.02%   |
| Alcor Micro                            | 27        | 5.6%    |
| Quanta                                 | 21        | 4.36%   |
| Microdia                               | 20        | 4.15%   |
| Suyin                                  | 12        | 2.49%   |
| Syntek                                 | 11        | 2.28%   |
| Acer                                   | 10        | 2.07%   |
| Sonix Technology                       | 8         | 1.66%   |
| Apple                                  | 8         | 1.66%   |
| Silicon Motion                         | 6         | 1.24%   |
| Luxvisions Innotech Limited            | 6         | 1.24%   |
| Z-Star Microelectronics                | 5         | 1.04%   |
| SunplusIT                              | 5         | 1.04%   |
| lihappe8                               | 5         | 1.04%   |
| Microsoft                              | 4         | 0.83%   |
| Ricoh                                  | 3         | 0.62%   |
| Lite-On Technology                     | 3         | 0.62%   |
| icSpring                               | 3         | 0.62%   |
| Unknown                                | 2         | 0.41%   |
| Samsung Electronics                    | 2         | 0.41%   |
| BRS 2Mp Camera                         | 2         | 0.41%   |
| ALi                                    | 2         | 0.41%   |
| Y Media                                | 1         | 0.21%   |
| Shinetech                              | 1         | 0.21%   |
| ShineOptics                            | 1         | 0.21%   |
| Primax Electronics                     | 1         | 0.21%   |
| MediaTek                               | 1         | 0.21%   |
| KYT-221229-A                           | 1         | 0.21%   |
| Importek                               | 1         | 0.21%   |
| Hewlett-Packard                        | 1         | 0.21%   |
| Generalplus Technology                 | 1         | 0.21%   |
| GEMBIRD                                | 1         | 0.21%   |
| DX-230705-A                            | 1         | 0.21%   |
| Creative Technology                    | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Bison BisonCam,NB Pro                                          | 33        | 6.78%   |
| Alcor Micro USB 2.0 PC Camera                                  | 21        | 4.31%   |
| Logitech Webcam C270                                           | 16        | 3.29%   |
| Chicony Integrated Camera                                      | 16        | 3.29%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 3.08%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 14        | 2.87%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 12        | 2.46%   |
| Realtek USB2.0 camera                                          | 11        | 2.26%   |
| Chicony HP HD Camera                                           | 11        | 2.26%   |
| Realtek USB Camera                                             | 9         | 1.85%   |
| Chicony HD Webcam                                              | 9         | 1.85%   |
| Syntek Integrated Camera                                       | 8         | 1.64%   |
| Sunplus Integrated_Webcam_HD                                   | 8         | 1.64%   |
| Sunplus BKX Usb FHD Camera                                     | 7         | 1.44%   |
| Microdia Webcam Vitade AF                                      | 7         | 1.44%   |
| Chicony USB2.0 FHD UVC WebCam                                  | 7         | 1.44%   |
| IMC Networks HD Camera                                         | 6         | 1.23%   |
| Chicony USB2.0 Camera                                          | 6         | 1.23%   |
| Quanta ov9734_techfront_camera                                 | 5         | 1.03%   |
| lihappe8 USB 2.0 Camera                                        | 5         | 1.03%   |
| IMC Networks Integrated Camera                                 | 5         | 1.03%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 0.82%   |
| Microdia USB 2.0 Camera                                        | 4         | 0.82%   |
| Acer BisonCam,NB Pro                                           | 4         | 0.82%   |
| Suyin 1.3M HD WebCam                                           | 3         | 0.62%   |
| SunplusIT USB Camera                                           | 3         | 0.62%   |
| Sunplus USB Microphone                                         | 3         | 0.62%   |
| Sunplus Asus Webcam                                            | 3         | 0.62%   |
| Sonix USB2.0 HD UVC WebCam                                     | 3         | 0.62%   |
| Ricoh USB2.0 Camera                                            | 3         | 0.62%   |
| Realtek Lenovo EasyCamera                                      | 3         | 0.62%   |
| Quanta FHD Camera                                              | 3         | 0.62%   |
| Microdia Integrated_Webcam_HD                                  | 3         | 0.62%   |
| Microdia Camera                                                | 3         | 0.62%   |
| Logitech HD Pro Webcam C920                                    | 3         | 0.62%   |
| IMC Networks UVC VGA Webcam                                    | 3         | 0.62%   |
| icSpring camera                                                | 3         | 0.62%   |
| Chicony USB2.0 HD UVC WebCam                                   | 3         | 0.62%   |
| Chicony USB2.0 FHD Camera                                      | 3         | 0.62%   |
| Chicony Integrated HP HD Webcam                                | 3         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 15        | 24.59%  |
| Shenzhen Goodix Technology         | 14        | 22.95%  |
| Elan Microelectronics              | 10        | 16.39%  |
| Synaptics                          | 6         | 9.84%   |
| LighTuning Technology              | 6         | 9.84%   |
| Upek                               | 3         | 4.92%   |
| Focal-systems.Corp                 | 3         | 4.92%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 3.28%   |
| FocalTech                          | 1         | 1.64%   |
| AuthenTec                          | 1         | 1.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 14        | 22.95%  |
| Elan ELAN:Fingerprint                                           | 6         | 9.84%   |
| Elan ELAN:ARM-M4                                                | 4         | 6.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 3         | 4.92%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 3         | 4.92%   |
| Validity Sensors VFS491                                         | 3         | 4.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 3         | 4.92%   |
| LighTuning Fingerprint Reader                                   | 3         | 4.92%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                       | 3         | 4.92%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 3.28%   |
| Validity Sensors Fingerprint scanner                            | 2         | 3.28%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 3.28%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 3.28%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 1.64%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.64%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.64%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 1.64%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.64%   |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 1.64%   |
| LighTuning Fingerprint Sensor                                   | 1         | 1.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.64%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 1.64%   |
| FocalTech FocalTech Fingerprint Device                          | 1         | 1.64%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 1.64%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 3         | 30%     |
| Aladdin R.D.              | 2         | 20%     |
| Aladdin Knowledge Systems | 2         | 20%     |
| Aktiv                     | 2         | 20%     |
| Broadcom                  | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 30%     |
| Aladdin Knowledge Systems Token JC  | 2         | 20%     |
| Aktiv Rutoken lite                  | 2         | 20%     |
| Broadcom 5880                       | 1         | 10%     |
| Aladdin R.D. JaCarta LT             | 1         | 10%     |
| Aladdin R.D. JaCarta                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 695       | 80.25%  |
| 1     | 124       | 14.32%  |
| 2     | 29        | 3.35%   |
| 4     | 8         | 0.92%   |
| 3     | 6         | 0.69%   |
| 5     | 4         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 61        | 27.6%   |
| Graphics card            | 52        | 23.53%  |
| Communication controller | 29        | 13.12%  |
| Multimedia controller    | 19        | 8.6%    |
| Net/wireless             | 14        | 6.33%   |
| Unassigned class         | 13        | 5.88%   |
| Net/ethernet             | 7         | 3.17%   |
| Chipcard                 | 7         | 3.17%   |
| Sound                    | 6         | 2.71%   |
| Camera                   | 5         | 2.26%   |
| Bluetooth                | 4         | 1.81%   |
| Flash memory             | 2         | 0.9%    |
| Storage/ide              | 1         | 0.45%   |
| Card reader              | 1         | 0.45%   |


Ubuntu MATE 22.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

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

Total: 145

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | NJx0MU                      | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [7ac222385a](https://linux-hardware.org/?probe=7ac222385a) | Dec 28, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [faf2c0e5d7](https://linux-hardware.org/?probe=faf2c0e5d7) | Dec 28, 2022 |
| HP            | ZBook 17 G5                 | [870deddfbe](https://linux-hardware.org/?probe=870deddfbe) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f113c7d475](https://linux-hardware.org/?probe=f113c7d475) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Acer          | TravelMate 7730             | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| HP            | Compaq Presario CQ61        | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | [ac787dc7dc](https://linux-hardware.org/?probe=ac787dc7dc) | Dec 17, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | [e47e7c18c9](https://linux-hardware.org/?probe=e47e7c18c9) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| ASUSTek       | X550LN                      | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| HUAWEI        | KPL-W0X                     | [8caca0975b](https://linux-hardware.org/?probe=8caca0975b) | Dec 15, 2022 |
| Notebook      | NJx0MU                      | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| HP            | 14                          | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Notebook      | NJx0MU                      | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| HP            | 14                          | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| HP            | ProBook 450 G6              | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Notebook      | NJx0MU                      | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Toshiba       | Satellite P50-B-10Z         | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Notebook      | NJx0MU                      | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Dell          | Latitude D630               | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Precision 7760              | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| HP            | ENVY Sleekbook 6            | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Acer          | Aspire 7750G                | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Chuwi         | GemiBook Pro                | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| Chuwi         | GemiBook Pro                | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| Intel         | H81U                        | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| Dell          | Precision 7760              | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| Acer          | Aspire 5050                 | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Dell          | Precision 7760              | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | Notebook                    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| LincPlus      | LINNCPLUS P1                | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| Dell          | Latitude 7420               | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| HP            | EliteBook 745 G5            | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| HP            | 15 Notebook PC              | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HONOR         | BOHK-WAX9X                  | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| Dell          | Latitude E4200              | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Compaq        | Presario CQ-23              | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| MicroByte     | ezbook                      | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Google        | Kled                        | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| Intel         | Kabylake Platform           | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| Dell          | Precision M6500             | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Apple         | MacBook5,1                  | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| Apple         | MacBookPro6,2               | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| Apple         | MacBookPro9,1               | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| IPASON        | MaxBook P1                  | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-56-generic     | 9         | 11.25%  |
| 5.15.0-53-generic     | 7         | 8.75%   |
| 5.15.0-52-generic     | 7         | 8.75%   |
| 5.15.0-47-generic     | 6         | 7.5%    |
| 5.15.0-46-generic     | 6         | 7.5%    |
| 5.15.0-43-generic     | 6         | 7.5%    |
| 5.15.0-25-generic     | 6         | 7.5%    |
| 5.15.0-48-generic     | 5         | 6.25%   |
| 5.15.0-40-generic     | 4         | 5%      |
| 5.15.0-41-generic     | 3         | 3.75%   |
| 5.15.0-30-generic     | 3         | 3.75%   |
| 5.15.0-27-generic     | 3         | 3.75%   |
| 5.15.0-52-lowlatency  | 2         | 2.5%    |
| 6.0.8-x64v1-xanmod1   | 1         | 1.25%   |
| 5.18.0-051800-generic | 1         | 1.25%   |
| 5.17.1-051701-generic | 1         | 1.25%   |
| 5.17.0-1003-oem       | 1         | 1.25%   |
| 5.15.0-56-lowlatency  | 1         | 1.25%   |
| 5.15.0-50-generic     | 1         | 1.25%   |
| 5.15.0-46-lowlatency  | 1         | 1.25%   |
| 5.15.0-39-generic     | 1         | 1.25%   |
| 5.15.0-37-generic     | 1         | 1.25%   |
| 5.15.0-35-generic     | 1         | 1.25%   |
| 5.15.0-33-generic     | 1         | 1.25%   |
| 5.15.0-18-generic     | 1         | 1.25%   |
| 5.14.0-1054-oem       | 1         | 1.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 69        | 93.24%  |
| 6.0.8   | 1         | 1.35%   |
| 5.18.0  | 1         | 1.35%   |
| 5.17.1  | 1         | 1.35%   |
| 5.17.0  | 1         | 1.35%   |
| 5.14.0  | 1         | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 69        | 93.24%  |
| 5.17    | 2         | 2.7%    |
| 6.0     | 1         | 1.35%   |
| 5.18    | 1         | 1.35%   |
| 5.14    | 1         | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 74        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MATE | 74        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 72        | 97.3%   |
| Wayland | 1         | 1.35%   |
| Tty     | 1         | 1.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 61        | 81.33%  |
| Unknown | 9         | 12%     |
| GDM3    | 5         | 6.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 29        | 39.19%  |
| de_DE | 10        | 13.51%  |
| fr_FR | 8         | 10.81%  |
| it_IT | 5         | 6.76%   |
| ru_RU | 4         | 5.41%   |
| pt_BR | 2         | 2.7%    |
| pl_PL | 2         | 2.7%    |
| fi_FI | 2         | 2.7%    |
| es_ES | 2         | 2.7%    |
| en_GB | 2         | 2.7%    |
| en_AU | 2         | 2.7%    |
| zh_CN | 1         | 1.35%   |
| hu_HU | 1         | 1.35%   |
| en_CA | 1         | 1.35%   |
| el_GR | 1         | 1.35%   |
| de_CH | 1         | 1.35%   |
| C     | 1         | 1.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 40        | 51.28%  |
| BIOS | 38        | 48.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 64        | 86.49%  |
| Overlay | 4         | 5.41%   |
| Zfs     | 3         | 4.05%   |
| Xfs     | 1         | 1.35%   |
| Jfs     | 1         | 1.35%   |
| Btrfs   | 1         | 1.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 53        | 69.74%  |
| Unknown | 16        | 21.05%  |
| MBR     | 7         | 9.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 83.78%  |
| Yes       | 12        | 16.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 66.67%  |
| Yes       | 25        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 16        | 21.62%  |
| Lenovo           | 15        | 20.27%  |
| ASUSTek Computer | 9         | 12.16%  |
| Dell             | 7         | 9.46%   |
| Acer             | 5         | 6.76%   |
| Apple            | 4         | 5.41%   |
| Toshiba          | 2         | 2.7%    |
| Intel            | 2         | 2.7%    |
| HUAWEI           | 2         | 2.7%    |
| TrekStor         | 1         | 1.35%   |
| Sony             | 1         | 1.35%   |
| Notebook         | 1         | 1.35%   |
| MicroByte        | 1         | 1.35%   |
| LincPlus         | 1         | 1.35%   |
| LG Electronics   | 1         | 1.35%   |
| IPASON           | 1         | 1.35%   |
| HYPERPC          | 1         | 1.35%   |
| HONOR            | 1         | 1.35%   |
| Google           | 1         | 1.35%   |
| Compaq           | 1         | 1.35%   |
| Chuwi            | 1         | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| TrekStor Surfbook A13B               | 1         | 1.35%   |
| Toshiba Satellite P50-B-10Z          | 1         | 1.35%   |
| Toshiba Satellite C50D-A-133         | 1         | 1.35%   |
| Sony VPCEA36FG                       | 1         | 1.35%   |
| Notebook NJx0MU                      | 1         | 1.35%   |
| MicroByte ezbook                     | 1         | 1.35%   |
| LincPlus LINNCPLUS P1                | 1         | 1.35%   |
| LG 17Z990-R.AAS8U1                   | 1         | 1.35%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 1.35%   |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 1.35%   |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 1.35%   |
| Lenovo ThinkPad T430 2347G5U         | 1         | 1.35%   |
| Lenovo ThinkPad T420 4238LY7         | 1         | 1.35%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 1.35%   |
| Lenovo ThinkPad R61 8918DEG          | 1         | 1.35%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 1.35%   |
| Lenovo ThinkBook 16p Gen 2 20YM      | 1         | 1.35%   |
| Lenovo ThinkBook 14 G2 ITL 20VD      | 1         | 1.35%   |
| Lenovo IdeaPad S145-14IIL 81W6       | 1         | 1.35%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 1         | 1.35%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 1.35%   |
| Lenovo IdeaPad 3 15ALC6 82KU         | 1         | 1.35%   |
| Lenovo IdeaPad 130-15AST 81H5        | 1         | 1.35%   |
| IPASON MaxBook P1                    | 1         | 1.35%   |
| Intel Kabylake Platform              | 1         | 1.35%   |
| Intel H81U                           | 1         | 1.35%   |
| HYPERPC PLAY                         | 1         | 1.35%   |
| HUAWEI KPL-W0X                       | 1         | 1.35%   |
| HUAWEI KLVD-WXX9                     | 1         | 1.35%   |
| HONOR BOHK-WAX9X                     | 1         | 1.35%   |
| HP ZBook 17 G5                       | 1         | 1.35%   |
| HP ZBook 14 G2                       | 1         | 1.35%   |
| HP Stream Laptop 14-cb1xxx           | 1         | 1.35%   |
| HP ProBook 640 G8 Notebook PC        | 1         | 1.35%   |
| HP ProBook 450 G6                    | 1         | 1.35%   |
| HP Pavilion Laptop 15-eh1xxx         | 1         | 1.35%   |
| HP Pavilion 15                       | 1         | 1.35%   |
| HP Notebook                          | 1         | 1.35%   |
| HP Laptop 15s-eq1xxx                 | 1         | 1.35%   |
| HP ENVY Sleekbook 6                  | 1         | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 7         | 9.46%   |
| Lenovo IdeaPad     | 5         | 6.76%   |
| HP EliteBook       | 3         | 4.05%   |
| Dell Latitude      | 3         | 4.05%   |
| Toshiba Satellite  | 2         | 2.7%    |
| Lenovo ThinkBook   | 2         | 2.7%    |
| HP ZBook           | 2         | 2.7%    |
| HP ProBook         | 2         | 2.7%    |
| HP Pavilion        | 2         | 2.7%    |
| Dell Precision     | 2         | 2.7%    |
| ASUS VivoBook      | 2         | 2.7%    |
| Acer TravelMate    | 2         | 2.7%    |
| Acer Aspire        | 2         | 2.7%    |
| TrekStor Surfbook  | 1         | 1.35%   |
| Sony VPCEA36FG     | 1         | 1.35%   |
| Notebook NJx0MU    | 1         | 1.35%   |
| MicroByte ezbook   | 1         | 1.35%   |
| LincPlus LINNCPLUS | 1         | 1.35%   |
| LG 17Z990-R.AAS8U1 | 1         | 1.35%   |
| Lenovo V15         | 1         | 1.35%   |
| IPASON MaxBook     | 1         | 1.35%   |
| Intel Kabylake     | 1         | 1.35%   |
| Intel H81U         | 1         | 1.35%   |
| HYPERPC PLAY       | 1         | 1.35%   |
| HUAWEI KPL-W0X     | 1         | 1.35%   |
| HUAWEI KLVD-WXX9   | 1         | 1.35%   |
| HONOR BOHK-WAX9X   | 1         | 1.35%   |
| HP Stream          | 1         | 1.35%   |
| HP Notebook        | 1         | 1.35%   |
| HP Laptop          | 1         | 1.35%   |
| HP ENVY            | 1         | 1.35%   |
| HP Compaq          | 1         | 1.35%   |
| HP 15              | 1         | 1.35%   |
| HP 14              | 1         | 1.35%   |
| Google Kled        | 1         | 1.35%   |
| Dell XPS           | 1         | 1.35%   |
| Dell Inspiron      | 1         | 1.35%   |
| Compaq Presario    | 1         | 1.35%   |
| Chuwi GemiBook     | 1         | 1.35%   |
| ASUS X555LAB       | 1         | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 24.32%  |
| 2020 | 7         | 9.46%   |
| 2019 | 7         | 9.46%   |
| 2018 | 7         | 9.46%   |
| 2012 | 7         | 9.46%   |
| 2014 | 4         | 5.41%   |
| 2013 | 3         | 4.05%   |
| 2011 | 3         | 4.05%   |
| 2010 | 3         | 4.05%   |
| 2009 | 3         | 4.05%   |
| 2022 | 2         | 2.7%    |
| 2016 | 2         | 2.7%    |
| 2015 | 2         | 2.7%    |
| 2008 | 2         | 2.7%    |
| 2007 | 2         | 2.7%    |
| 2017 | 1         | 1.35%   |
| 2006 | 1         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 74        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 70        | 90.91%  |
| Enabled  | 7         | 9.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 98.65%  |
| Yes  | 1         | 1.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 25        | 33.78%  |
| 3.01-4.0    | 16        | 21.62%  |
| 16.01-24.0  | 12        | 16.22%  |
| 8.01-16.0   | 12        | 16.22%  |
| 32.01-64.0  | 4         | 5.41%   |
| 64.01-256.0 | 3         | 4.05%   |
| 24.01-32.0  | 1         | 1.35%   |
| 2.01-3.0    | 1         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 23        | 29.49%  |
| 1.01-2.0  | 20        | 25.64%  |
| 4.01-8.0  | 14        | 17.95%  |
| 3.01-4.0  | 14        | 17.95%  |
| 8.01-16.0 | 4         | 5.13%   |
| 0.51-1.0  | 3         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 77.03%  |
| 2      | 12        | 16.22%  |
| 3      | 5         | 6.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 64.86%  |
| Yes       | 26        | 35.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 72.97%  |
| No        | 20        | 27.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 88%     |
| No        | 9         | 12%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 10        | 13.51%  |
| USA         | 9         | 12.16%  |
| Italy       | 7         | 9.46%   |
| France      | 7         | 9.46%   |
| Spain       | 5         | 6.76%   |
| Russia      | 4         | 5.41%   |
| Brazil      | 4         | 5.41%   |
| UK          | 3         | 4.05%   |
| Turkey      | 2         | 2.7%    |
| Serbia      | 2         | 2.7%    |
| Poland      | 2         | 2.7%    |
| Hungary     | 2         | 2.7%    |
| Greece      | 2         | 2.7%    |
| Finland     | 2         | 2.7%    |
| Estonia     | 2         | 2.7%    |
| Switzerland | 1         | 1.35%   |
| Romania     | 1         | 1.35%   |
| Paraguay    | 1         | 1.35%   |
| Netherlands | 1         | 1.35%   |
| India       | 1         | 1.35%   |
| Georgia     | 1         | 1.35%   |
| Colombia    | 1         | 1.35%   |
| China       | 1         | 1.35%   |
| Chile       | 1         | 1.35%   |
| Bulgaria    | 1         | 1.35%   |
| Australia   | 1         | 1.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Mannheim         | 3         | 4%      |
| Warsaw           | 2         | 2.67%   |
| Belgrade         | 2         | 2.67%   |
| Xining           | 1         | 1.33%   |
| Viroflay         | 1         | 1.33%   |
| Villeurbanne     | 1         | 1.33%   |
| Varna            | 1         | 1.33%   |
| Valenciennes     | 1         | 1.33%   |
| Turku            | 1         | 1.33%   |
| Tula             | 1         | 1.33%   |
| Thane            | 1         | 1.33%   |
| Tartu            | 1         | 1.33%   |
| Talcahuano       | 1         | 1.33%   |
| Seville          | 1         | 1.33%   |
| Settimo Torinese | 1         | 1.33%   |
| Sarospatak       | 1         | 1.33%   |
| Sao Paulo        | 1         | 1.33%   |
| Rostov-on-Don    | 1         | 1.33%   |
| Rennes           | 1         | 1.33%   |
| Porto Alegre     | 1         | 1.33%   |
| Pärnu           | 1         | 1.33%   |
| Paris            | 1         | 1.33%   |
| Ortuella         | 1         | 1.33%   |
| Olympia          | 1         | 1.33%   |
| Olathe           | 1         | 1.33%   |
| Norwich          | 1         | 1.33%   |
| North Wilkesboro | 1         | 1.33%   |
| Newport News     | 1         | 1.33%   |
| Naaldwijk        | 1         | 1.33%   |
| Moscow           | 1         | 1.33%   |
| Moosseedorf      | 1         | 1.33%   |
| Milan            | 1         | 1.33%   |
| Memphis          | 1         | 1.33%   |
| Medellín        | 1         | 1.33%   |
| Marseille        | 1         | 1.33%   |
| Magdeburg        | 1         | 1.33%   |
| Lindlar          | 1         | 1.33%   |
| Limbiate         | 1         | 1.33%   |
| Laubach          | 1         | 1.33%   |
| La Rochelle      | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 19        | 28     | 20.21%  |
| Toshiba               | 7         | 9      | 7.45%   |
| Seagate               | 7         | 7      | 7.45%   |
| SanDisk               | 7         | 9      | 7.45%   |
| Crucial               | 7         | 7      | 7.45%   |
| Unknown               | 4         | 4      | 4.26%   |
| Kingston              | 4         | 4      | 4.26%   |
| WDC                   | 3         | 3      | 3.19%   |
| SK hynix              | 2         | 2      | 2.13%   |
| Phison                | 2         | 2      | 2.13%   |
| Micron Technology     | 2         | 2      | 2.13%   |
| KingSpec              | 2         | 2      | 2.13%   |
| Intel                 | 2         | 2      | 2.13%   |
| HGST                  | 2         | 2      | 2.13%   |
| China                 | 2         | 2      | 2.13%   |
| A-DATA Technology     | 2         | 2      | 2.13%   |
| WDC WDS2              | 1         | 1      | 1.06%   |
| Verbatim              | 1         | 1      | 1.06%   |
| UMIS                  | 1         | 1      | 1.06%   |
| SPCC                  | 1         | 1      | 1.06%   |
| Realtek Semiconductor | 1         | 1      | 1.06%   |
| Patriot               | 1         | 1      | 1.06%   |
| Netac                 | 1         | 1      | 1.06%   |
| LITEONIT              | 1         | 1      | 1.06%   |
| Lenovo                | 1         | 1      | 1.06%   |
| Kston                 | 1         | 1      | 1.06%   |
| KIOXIA                | 1         | 1      | 1.06%   |
| JMicron Technology    | 1         | 1      | 1.06%   |
| Intenso               | 1         | 1      | 1.06%   |
| Hjwdz                 | 1         | 1      | 1.06%   |
| Hitachi               | 1         | 1      | 1.06%   |
| Gigabyte Technology   | 1         | 1      | 1.06%   |
| faspeed               | 1         | 1      | 1.06%   |
| Apple                 | 1         | 1      | 1.06%   |
| addlink               | 1         | 1      | 1.06%   |
| ADATA Technology      | 1         | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 2         | 2.06%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 2.06%   |
| Samsung MZVLQ512HBLU-00BH1 512GB     | 2         | 2.06%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 2.06%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 2.06%   |
| WDC WDS2 50G2B0B-00YS 250GB SSD      | 1         | 1.03%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 1         | 1.03%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 1.03%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB | 1         | 1.03%   |
| Verbatim Vi550 S3 256GB              | 1         | 1.03%   |
| Unknown SLD64G  64GB                 | 1         | 1.03%   |
| Unknown MMC Card  7GB                | 1         | 1.03%   |
| Unknown MMC Card  64GB               | 1         | 1.03%   |
| Unknown Biwin  64GB                  | 1         | 1.03%   |
| UMIS RPJTJ256MEE1OWX 256GB           | 1         | 1.03%   |
| Toshiba THNSNK256GVN8 256GB SSD      | 1         | 1.03%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.03%   |
| Toshiba MK3259GSXP 320GB             | 1         | 1.03%   |
| Toshiba KBG40ZNT256G MEMORY 256GB    | 1         | 1.03%   |
| Toshiba KBG30ZMV256G 256GB           | 1         | 1.03%   |
| SPCC Solid State Disk 1024GB         | 1         | 1.03%   |
| SK hynix SC311 SATA 256GB SSD        | 1         | 1.03%   |
| SK hynix HFM128GDJTNG-8310A 128GB    | 1         | 1.03%   |
| Seagate ST9500420AS 500GB            | 1         | 1.03%   |
| Seagate ST9250827AS 250GB            | 1         | 1.03%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.03%   |
| Seagate One Touch HDD 5TB            | 1         | 1.03%   |
| Seagate BUP BK 4TB                   | 1         | 1.03%   |
| SanDisk SSD U100 24GB                | 1         | 1.03%   |
| SanDisk SSD i100 24GB                | 1         | 1.03%   |
| SanDisk SD7TB3Q-256G-1006 256GB SSD  | 1         | 1.03%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD  | 1         | 1.03%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD  | 1         | 1.03%   |
| Sandisk PC SN520 NVMe SSD 128GB      | 1         | 1.03%   |
| SanDisk NVMe SSD Drive 512GB         | 1         | 1.03%   |
| SanDisk Extreme 55AE 1TB SSD         | 1         | 1.03%   |
| Samsung SSD PM830 mSATA 32GB         | 1         | 1.03%   |
| Samsung SSD PM800 TM 128GB           | 1         | 1.03%   |
| Samsung SSD 980 PRO 1TB              | 1         | 1.03%   |
| Samsung SSD 980 1TB                  | 1         | 1.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 46.67%  |
| Toshiba | 4         | 5      | 26.67%  |
| HGST    | 2         | 2      | 13.33%  |
| WDC     | 1         | 1      | 6.67%   |
| Hitachi | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 16.28%  |
| Crucial             | 7         | 7      | 16.28%  |
| SanDisk             | 5         | 6      | 11.63%  |
| Kingston            | 3         | 3      | 6.98%   |
| KingSpec            | 2         | 2      | 4.65%   |
| China               | 2         | 2      | 4.65%   |
| A-DATA Technology   | 2         | 2      | 4.65%   |
| WDC WDS2            | 1         | 1      | 2.33%   |
| Verbatim            | 1         | 1      | 2.33%   |
| Toshiba             | 1         | 2      | 2.33%   |
| SPCC                | 1         | 1      | 2.33%   |
| SK hynix            | 1         | 1      | 2.33%   |
| Patriot             | 1         | 1      | 2.33%   |
| Netac               | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| LITEONIT            | 1         | 1      | 2.33%   |
| Kston               | 1         | 1      | 2.33%   |
| JMicron Technology  | 1         | 1      | 2.33%   |
| Intenso             | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |
| addlink             | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 35        | 46     | 41.18%  |
| NVMe    | 30        | 39     | 35.29%  |
| HDD     | 14        | 16     | 16.47%  |
| MMC     | 4         | 4      | 4.71%   |
| Unknown | 2         | 2      | 2.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 58     | 52.94%  |
| NVMe | 30        | 39     | 35.29%  |
| SAS  | 6         | 6      | 7.06%   |
| MMC  | 4         | 4      | 4.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 43     | 67.31%  |
| 0.51-1.0   | 11        | 12     | 21.15%  |
| 1.01-2.0   | 4         | 5      | 7.69%   |
| 3.01-4.0   | 1         | 1      | 1.92%   |
| 4.01-10.0  | 1         | 1      | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 34.67%  |
| 251-500        | 19        | 25.33%  |
| 1001-2000      | 6         | 8%      |
| 1-20           | 6         | 8%      |
| 21-50          | 4         | 5.33%   |
| 501-1000       | 4         | 5.33%   |
| 51-100         | 4         | 5.33%   |
| 2001-3000      | 3         | 4%      |
| More than 3000 | 2         | 2.67%   |
| Unknown        | 1         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 28.95%  |
| 21-50          | 14        | 18.42%  |
| 101-250        | 14        | 18.42%  |
| 51-100         | 11        | 14.47%  |
| 251-500        | 4         | 5.26%   |
| 1001-2000      | 4         | 5.26%   |
| 501-1000       | 4         | 5.26%   |
| More than 3000 | 1         | 1.32%   |
| 2001-3000      | 1         | 1.32%   |
| Unknown        | 1         | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                    | 1         | 1      | 25%     |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 25%     |
| Netac SSD 256GB                              | 1         | 1      | 25%     |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Netac               | 1         | 1      | 25%     |
| Intel               | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| HDD  | 1         | 1      | 25%     |

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
| Works    | 46        | 58     | 56.1%   |
| Detected | 32        | 45     | 39.02%  |
| Malfunc  | 4         | 4      | 4.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 49        | 53.26%  |
| Samsung Electronics          | 12        | 13.04%  |
| AMD                          | 11        | 11.96%  |
| SanDisk                      | 4         | 4.35%   |
| Phison Electronics           | 3         | 3.26%   |
| Toshiba America Info Systems | 2         | 2.17%   |
| KIOXIA                       | 2         | 2.17%   |
| Union Memory (Shenzhen)      | 1         | 1.09%   |
| SK hynix                     | 1         | 1.09%   |
| Realtek Semiconductor        | 1         | 1.09%   |
| Nvidia                       | 1         | 1.09%   |
| Micron Technology            | 1         | 1.09%   |
| Marvell Technology Group     | 1         | 1.09%   |
| Lenovo                       | 1         | 1.09%   |
| Kingston Technology Company  | 1         | 1.09%   |
| ADATA Technology             | 1         | 1.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 10        | 10%     |
| Samsung NVMe SSD Controller 980                                                        | 8         | 8%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 7         | 7%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 5%      |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 4%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 3%      |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 3%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 3%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 3%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 2%      |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 2%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 2%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 2%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 2%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2%      |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1%      |
| Toshiba America Info Systems Toshiba America Info SATA controller                      | 1         | 1%      |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 1%      |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 1%      |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 1%      |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 1%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1%      |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 1%      |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1%      |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1%      |
| Micron Non-Volatile memory controller                                                  | 1         | 1%      |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 1         | 1%      |
| Lenovo Non-Volatile memory controller                                                  | 1         | 1%      |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1%      |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 1%      |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 1%      |
| Intel SSD 660P Series                                                                  | 1         | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 51        | 53.13%  |
| NVMe | 30        | 31.25%  |
| RAID | 9         | 9.38%   |
| IDE  | 6         | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 78.38%  |
| AMD    | 16        | 21.62%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-3517U CPU @ 1.90GHz           | 3         | 4.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 4.05%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 2.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.7%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 2.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 2.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 2.7%    |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 1.35%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.35%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.35%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.35%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.35%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 1.35%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 1         | 1.35%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.35%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.35%   |
| Intel Core i7 CPU X 920 @ 2.00GHz           | 1         | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.35%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.35%   |
| Intel Core i5-4300Y CPU @ 1.60GHz           | 1         | 1.35%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 1.35%   |
| Intel Core i5-3380M CPU @ 2.90GHz           | 1         | 1.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.35%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.35%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.35%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.35%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.35%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.35%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.35%   |
| Intel Core 2 Duo CPU U9600 @ 1.60GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T9550 @ 2.66GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.35%   |
| Intel Core 2 Duo CPU T5670 @ 1.80GHz        | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 14        | 18.92%  |
| Intel Core i5           | 11        | 14.86%  |
| Other                   | 10        | 13.51%  |
| Intel Core i3           | 6         | 8.11%   |
| Intel Core 2 Duo        | 6         | 8.11%   |
| Intel Celeron           | 6         | 8.11%   |
| AMD Ryzen 5             | 4         | 5.41%   |
| Intel Pentium           | 3         | 4.05%   |
| AMD Ryzen 7             | 3         | 4.05%   |
| AMD Ryzen 3             | 2         | 2.7%    |
| Intel Pentium Silver    | 1         | 1.35%   |
| Intel Pentium Dual-Core | 1         | 1.35%   |
| AMD Turion 64 Mobile    | 1         | 1.35%   |
| AMD Ryzen 9             | 1         | 1.35%   |
| AMD Ryzen 7 PRO         | 1         | 1.35%   |
| AMD E1                  | 1         | 1.35%   |
| AMD A8                  | 1         | 1.35%   |
| AMD A6                  | 1         | 1.35%   |
| AMD A4                  | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 33        | 44.59%  |
| 4      | 31        | 41.89%  |
| 8      | 5         | 6.76%   |
| 6      | 4         | 5.41%   |
| 1      | 1         | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 50        | 67.57%  |
| 1      | 24        | 32.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 74        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 39.24%  |
| 0x806c1    | 6         | 7.59%   |
| 0x306a9    | 5         | 6.33%   |
| 0x806d1    | 3         | 3.8%    |
| 0x1067a    | 3         | 3.8%    |
| 0x806ec    | 2         | 2.53%   |
| 0x706e5    | 2         | 2.53%   |
| 0x706a8    | 2         | 2.53%   |
| 0x506c9    | 2         | 2.53%   |
| 0x40651    | 2         | 2.53%   |
| 0x30678    | 2         | 2.53%   |
| 0x206a7    | 2         | 2.53%   |
| 0x08608103 | 2         | 2.53%   |
| 0x906c0    | 1         | 1.27%   |
| 0x806eb    | 1         | 1.27%   |
| 0x806ea    | 1         | 1.27%   |
| 0x806e9    | 1         | 1.27%   |
| 0x6fd      | 1         | 1.27%   |
| 0x6fb      | 1         | 1.27%   |
| 0x506e3    | 1         | 1.27%   |
| 0x20655    | 1         | 1.27%   |
| 0x10676    | 1         | 1.27%   |
| 0x0a50000c | 1         | 1.27%   |
| 0x08608102 | 1         | 1.27%   |
| 0x08108109 | 1         | 1.27%   |
| 0x08101016 | 1         | 1.27%   |
| 0x07030105 | 1         | 1.27%   |
| 0x0700010f | 1         | 1.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 8         | 10.67%  |
| TigerLake     | 7         | 9.33%   |
| KabyLake      | 7         | 9.33%   |
| IceLake       | 6         | 8%      |
| Unknown       | 6         | 8%      |
| Penryn        | 5         | 6.67%   |
| Haswell       | 5         | 6.67%   |
| Zen 2         | 3         | 4%      |
| Silvermont    | 3         | 4%      |
| SandyBridge   | 3         | 4%      |
| Goldmont plus | 3         | 4%      |
| Zen+          | 2         | 2.67%   |
| Zen           | 2         | 2.67%   |
| Westmere      | 2         | 2.67%   |
| Goldmont      | 2         | 2.67%   |
| Excavator     | 2         | 2.67%   |
| Core          | 2         | 2.67%   |
| Zen 3         | 1         | 1.33%   |
| Skylake       | 1         | 1.33%   |
| Puma          | 1         | 1.33%   |
| Nehalem       | 1         | 1.33%   |
| K8 Hammer     | 1         | 1.33%   |
| Jaguar        | 1         | 1.33%   |
| Broadwell     | 1         | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 56.67%  |
| AMD    | 20        | 22.22%  |
| Nvidia | 19        | 21.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 7.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 6.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 3.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 3.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 3.3%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 3.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 3.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.3%    |
| AMD Renoir                                                                | 3         | 3.3%    |
| AMD Lucienne                                                              | 3         | 3.3%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 2.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.2%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 2.2%    |
| Intel JasperLake [UHD Graphics]                                           | 2         | 2.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 2.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 2.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 2.2%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.1%    |
| Nvidia TU117M                                                             | 1         | 1.1%    |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 1.1%    |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 1.1%    |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 1.1%    |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 1.1%    |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 1.1%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 1.1%    |
| Nvidia GF108M [GeForce GT 635M]                                           | 1         | 1.1%    |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 1.1%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 1         | 1.1%    |
| Nvidia GA104GLM [RTX A3000 Mobile]                                        | 1         | 1.1%    |
| Nvidia G98M [GeForce G 103M]                                              | 1         | 1.1%    |
| Nvidia G92GLM [Quadro FX 2800M]                                           | 1         | 1.1%    |
| Nvidia G86M [Quadro NVS 140M]                                             | 1         | 1.1%    |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 1.1%    |
| Intel UHD Graphics 620                                                    | 1         | 1.1%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 1.1%    |
| Intel HD Graphics 620                                                     | 1         | 1.1%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 52.7%   |
| 1 x AMD        | 13        | 17.57%  |
| Intel + Nvidia | 9         | 12.16%  |
| 1 x Nvidia     | 6         | 8.11%   |
| AMD + Nvidia   | 4         | 5.41%   |
| Intel + AMD    | 3         | 4.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 86.49%  |
| Proprietary | 9         | 12.16%  |
| Unknown     | 1         | 1.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 77.33%  |
| 0.01-0.5   | 8         | 10.67%  |
| 0.51-1.0   | 4         | 5.33%   |
| 1.01-2.0   | 3         | 4%      |
| 5.01-6.0   | 1         | 1.33%   |
| 3.01-4.0   | 1         | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 14        | 15.73%  |
| Chimei Innolux          | 13        | 14.61%  |
| Samsung Electronics     | 10        | 11.24%  |
| LG Display              | 10        | 11.24%  |
| AU Optronics            | 9         | 10.11%  |
| Apple                   | 4         | 4.49%   |
| PANDA                   | 3         | 3.37%   |
| Chi Mei Optoelectronics | 3         | 3.37%   |
| Dell                    | 2         | 2.25%   |
| AOC                     | 2         | 2.25%   |
| ViewSonic               | 1         | 1.12%   |
| Unknown                 | 1         | 1.12%   |
| Toshiba                 | 1         | 1.12%   |
| Sony                    | 1         | 1.12%   |
| Sharp                   | 1         | 1.12%   |
| Sceptre Tech            | 1         | 1.12%   |
| Philips                 | 1         | 1.12%   |
| LG Philips              | 1         | 1.12%   |
| Lenovo                  | 1         | 1.12%   |
| Iiyama                  | 1         | 1.12%   |
| IBM                     | 1         | 1.12%   |
| Hitachi                 | 1         | 1.12%   |
| Hewlett-Packard         | 1         | 1.12%   |
| HannStar                | 1         | 1.12%   |
| Goldstar                | 1         | 1.12%   |
| CS_                     | 1         | 1.12%   |
| BenQ                    | 1         | 1.12%   |
| Ancor Communications    | 1         | 1.12%   |
| Acer                    | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 2.25%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 2         | 2.25%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch         | 1         | 1.12%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1         | 1.12%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch              | 1         | 1.12%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 1.12%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 1.12%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 1         | 1.12%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch   | 1         | 1.12%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch    | 1         | 1.12%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch | 1         | 1.12%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 1         | 1.12%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 1.12%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 1.12%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 1.12%   |
| LG Philips LCD Monitor LPLA106 1440x900 367x230mm 17.1-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD0724 1920x1080 309x174mm 14.0-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 1.12%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch               | 1         | 1.12%   |
| Iiyama PL2773H IVM660A 1920x1080 600x340mm 27.2-inch                  | 1         | 1.12%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 1         | 1.12%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                 | 1         | 1.12%   |
| Hewlett-Packard w2408 HWP26CE 1920x1200 518x324mm 24.1-inch           | 1         | 1.12%   |
| HannStar Hanns.G Hi221 HSD2469 1680x1050 474x297mm 22.0-inch          | 1         | 1.12%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39        | 46.99%  |
| 1366x768 (WXGA)    | 20        | 24.1%   |
| 1440x900 (WXGA+)   | 5         | 6.02%   |
| 1280x800 (WXGA)    | 4         | 4.82%   |
| 2560x1440 (QHD)    | 3         | 3.61%   |
| 3840x2160 (4K)     | 2         | 2.41%   |
| 2560x1600          | 2         | 2.41%   |
| 2160x1440          | 2         | 2.41%   |
| 1680x1050 (WSXGA+) | 2         | 2.41%   |
| 1600x900 (HD+)     | 2         | 2.41%   |
| 3840x2400          | 1         | 1.2%    |
| 1920x1200 (WUXGA)  | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 31        | 35.23%  |
| 14     | 11        | 12.5%   |
| 13     | 11        | 12.5%   |
| 17     | 10        | 11.36%  |
| 27     | 6         | 6.82%   |
| 24     | 4         | 4.55%   |
| 21     | 3         | 3.41%   |
| 54     | 2         | 2.27%   |
| 23     | 2         | 2.27%   |
| 12     | 2         | 2.27%   |
| 84     | 1         | 1.14%   |
| 25     | 1         | 1.14%   |
| 22     | 1         | 1.14%   |
| 18     | 1         | 1.14%   |
| 16     | 1         | 1.14%   |
| 11     | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 56.32%  |
| 501-600     | 12        | 13.79%  |
| 351-400     | 10        | 11.49%  |
| 201-300     | 8         | 9.2%    |
| 401-500     | 5         | 5.75%   |
| 1001-1500   | 2         | 2.3%    |
| 1501-2000   | 1         | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 58        | 76.32%  |
| 16/10 | 16        | 21.05%  |
| 3/2   | 2         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 34.48%  |
| 81-90          | 19        | 21.84%  |
| 121-130        | 8         | 9.2%    |
| 201-250        | 7         | 8.05%   |
| 301-350        | 6         | 6.9%    |
| More than 1000 | 3         | 3.45%   |
| 71-80          | 3         | 3.45%   |
| 251-300        | 3         | 3.45%   |
| 61-70          | 2         | 2.3%    |
| 131-140        | 2         | 2.3%    |
| 51-60          | 1         | 1.15%   |
| 141-150        | 1         | 1.15%   |
| 111-120        | 1         | 1.15%   |
| 91-100         | 1         | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 38.1%   |
| 101-120       | 25        | 29.76%  |
| 51-100        | 17        | 20.24%  |
| 161-240       | 7         | 8.33%   |
| 1-50          | 2         | 2.38%   |
| More than 240 | 1         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 58        | 78.38%  |
| 2     | 12        | 16.22%  |
| 3     | 2         | 2.7%    |
| 4     | 1         | 1.35%   |
| 0     | 1         | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 45        | 42.06%  |
| Realtek Semiconductor             | 38        | 35.51%  |
| Qualcomm Atheros                  | 6         | 5.61%   |
| Broadcom                          | 5         | 4.67%   |
| Ericsson Business Mobile Networks | 2         | 1.87%   |
| Broadcom Limited                  | 2         | 1.87%   |
| ASIX Electronics                  | 2         | 1.87%   |
| TP-Link                           | 1         | 0.93%   |
| Ralink                            | 1         | 0.93%   |
| Quectel Wireless Solutions        | 1         | 0.93%   |
| Qualcomm Atheros Communications   | 1         | 0.93%   |
| Nvidia                            | 1         | 0.93%   |
| Microchip Technology              | 1         | 0.93%   |
| Marvell Technology Group          | 1         | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 13.87%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 5.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 5.11%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 3.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.92%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 2.19%   |
| Realtek 802.11ac NIC                                              | 3         | 2.19%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.19%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.46%   |
| Intel Wireless 7260                                               | 2         | 1.46%   |
| Intel Wireless 3165                                               | 2         | 1.46%   |
| Intel Wireless 3160                                               | 2         | 1.46%   |
| Intel WiFi Link 5100                                              | 2         | 1.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.46%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 2         | 1.46%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.46%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.46%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 1.46%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.46%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.73%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.73%   |
| Quectel Wireless Solutions EM12G-ACER                             | 1         | 0.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 0.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 56.96%  |
| Realtek Semiconductor           | 19        | 24.05%  |
| Qualcomm Atheros                | 6         | 7.59%   |
| Broadcom                        | 3         | 3.8%    |
| Broadcom Limited                | 2         | 2.53%   |
| TP-Link                         | 1         | 1.27%   |
| Ralink                          | 1         | 1.27%   |
| Quectel Wireless Solutions      | 1         | 1.27%   |
| Qualcomm Atheros Communications | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 8.75%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 5%      |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 3.75%   |
| Realtek 802.11ac NIC                                                    | 3         | 3.75%   |
| Intel Wireless 8265 / 8275                                              | 3         | 3.75%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 3.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.5%    |
| Intel Wireless 7260                                                     | 2         | 2.5%    |
| Intel Wireless 3165                                                     | 2         | 2.5%    |
| Intel Wireless 3160                                                     | 2         | 2.5%    |
| Intel WiFi Link 5100                                                    | 2         | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.5%    |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 2.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.5%    |
| Intel Centrino Wireless-N 2230                                          | 2         | 2.5%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.5%    |
| TP-Link 802.11ac NIC                                                    | 1         | 1.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.25%   |
| Quectel Wireless Solutions EM12G-ACER                                   | 1         | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.25%   |
| Intel Wireless 8260                                                     | 1         | 1.25%   |
| Intel Wireless 7265                                                     | 1         | 1.25%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.25%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.25%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.25%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.25%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 53.7%   |
| Intel                    | 15        | 27.78%  |
| Broadcom                 | 4         | 7.41%   |
| ASIX Electronics         | 2         | 3.7%    |
| Qualcomm Atheros         | 1         | 1.85%   |
| Nvidia                   | 1         | 1.85%   |
| Microchip Technology     | 1         | 1.85%   |
| Marvell Technology Group | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 19        | 34.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 12.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 7.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 3.64%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 3.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 3.64%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 3.64%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.82%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.82%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 1.82%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.82%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 1.82%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.82%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.82%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.82%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.82%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.82%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.82%   |
| Intel 82566MC Gigabit Network Connection                                       | 1         | 1.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.82%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 56.92%  |
| Ethernet | 54        | 41.54%  |
| Modem    | 2         | 1.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 76.19%  |
| Ethernet | 20        | 23.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 50        | 67.57%  |
| 1     | 23        | 31.08%  |
| 0     | 1         | 1.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 62.16%  |
| Yes  | 28        | 37.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 47.76%  |
| Realtek Semiconductor           | 11        | 16.42%  |
| Broadcom                        | 7         | 10.45%  |
| IMC Networks                    | 5         | 7.46%   |
| Apple                           | 4         | 5.97%   |
| Cambridge Silicon Radio         | 3         | 4.48%   |
| Toshiba                         | 1         | 1.49%   |
| Ralink                          | 1         | 1.49%   |
| Qualcomm Atheros Communications | 1         | 1.49%   |
| Hewlett-Packard                 | 1         | 1.49%   |
| Foxconn / Hon Hai               | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                                                             | 11        | 16.42%  |
| Intel AX201 Bluetooth                                                               | 11        | 16.42%  |
| Intel Bluetooth wireless interface                                                  | 8         | 11.94%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 7.46%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 4.48%   |
| Intel AX200 Bluetooth                                                               | 3         | 4.48%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 4.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 4.48%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.99%   |
| IMC Networks Bluetooth Device                                                       | 2         | 2.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.99%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.99%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.99%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.49%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.49%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.49%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.49%   |
| Broadcom Bluetooth 3.0 Dongle                                                       | 1         | 1.49%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 1.49%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.49%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.49%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 57        | 61.96%  |
| AMD                    | 17        | 18.48%  |
| Nvidia                 | 13        | 14.13%  |
| C-Media Electronics    | 2         | 2.17%   |
| Meizu                  | 1         | 1.09%   |
| Generalplus Technology | 1         | 1.09%   |
| DSEA A/S               | 1         | 1.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 9.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 7.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 6.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 4.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.6%    |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.7%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 2.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.8%    |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.8%    |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 1.8%    |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.8%    |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.8%    |
| AMD High Definition Audio Controller                                       | 2         | 1.8%    |
| AMD FCH Azalia Controller                                                  | 2         | 1.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.8%    |
| Nvidia stereo controller                                                   | 1         | 0.9%    |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.9%    |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.9%    |
| Meizu HiFi DAC Headphone Amplifier                                         | 1         | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.9%    |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.9%    |
| Generalplus Technology USB Audio Device                                    | 1         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 26.23%  |
| SK hynix            | 15        | 24.59%  |
| Micron Technology   | 8         | 13.11%  |
| Unknown             | 6         | 9.84%   |
| Kingston            | 6         | 9.84%   |
| Unknown (ABCD)      | 4         | 6.56%   |
| Crucial             | 3         | 4.92%   |
| G.Skill             | 2         | 3.28%   |
| Nanya Technology    | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 5.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 4.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 2.94%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.94%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.47%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.47%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 1.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.47%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 1.47%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| Samsung RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 1.47%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.47%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.47%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 1         | 1.47%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 1         | 1.47%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 25        | 48.08%  |
| DDR3   | 17        | 32.69%  |
| LPDDR4 | 6         | 11.54%  |
| DDR2   | 3         | 5.77%   |
| SDRAM  | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 83.93%  |
| Row Of Chips | 8         | 14.29%  |
| Chip         | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 25        | 42.37%  |
| 4096  | 20        | 33.9%   |
| 16384 | 5         | 8.47%   |
| 2048  | 5         | 8.47%   |
| 32768 | 2         | 3.39%   |
| 1024  | 2         | 3.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 17        | 30.36%  |
| 1600    | 12        | 21.43%  |
| 2400    | 9         | 16.07%  |
| 2667    | 6         | 10.71%  |
| 1334    | 2         | 3.57%   |
| 667     | 2         | 3.57%   |
| Unknown | 2         | 3.57%   |
| 4267    | 1         | 1.79%   |
| 2133    | 1         | 1.79%   |
| 2048    | 1         | 1.79%   |
| 1867    | 1         | 1.79%   |
| 1067    | 1         | 1.79%   |
| 1066    | 1         | 1.79%   |

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


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M2070 Series | 1         | 100%    |

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
| Chicony Electronics                    | 21        | 30.88%  |
| Realtek Semiconductor                  | 8         | 11.76%  |
| Quanta                                 | 5         | 7.35%   |
| IMC Networks                           | 5         | 7.35%   |
| Syntek                                 | 4         | 5.88%   |
| Microdia                               | 3         | 4.41%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.41%   |
| Apple                                  | 3         | 4.41%   |
| Acer                                   | 3         | 4.41%   |
| Suyin                                  | 2         | 2.94%   |
| Sunplus Innovation Technology          | 2         | 2.94%   |
| Luxvisions Innotech Limited            | 2         | 2.94%   |
| U0AS01A-0                              | 1         | 1.47%   |
| Ricoh                                  | 1         | 1.47%   |
| Logitech                               | 1         | 1.47%   |
| Lite-On Technology                     | 1         | 1.47%   |
| Lenovo                                 | 1         | 1.47%   |
| ARC International                      | 1         | 1.47%   |
| Alcor Micro                            | 1         | 1.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Syntek Integrated Camera                      | 4         | 5.88%   |
| Chicony HP HD Camera                          | 4         | 5.88%   |
| Realtek USB Camera                            | 3         | 4.41%   |
| IMC Networks USB2.0 HD UVC WebCam             | 3         | 4.41%   |
| Realtek USB2.0 camera                         | 2         | 2.94%   |
| Quanta HD User Facing                         | 2         | 2.94%   |
| Microdia Webcam Vitade AF                     | 2         | 2.94%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.94%   |
| Chicony integrated camera                     | 2         | 2.94%   |
| Chicony HP Webcam                             | 2         | 2.94%   |
| Chicony HD User Facing                        | 2         | 2.94%   |
| Apple Built-in iSight                         | 2         | 2.94%   |
| Acer Integrated Camera                        | 2         | 2.94%   |
| U0AS01A-0 U0AS01A-0                           | 1         | 1.47%   |
| Suyin USB 2.0 Camera                          | 1         | 1.47%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 1         | 1.47%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 1.47%   |
| Sunplus HP Truevision HD                      | 1         | 1.47%   |
| Ricoh Dell Laptop Integrated Webcam           | 1         | 1.47%   |
| Realtek NexiGo N660P FHD Webcam               | 1         | 1.47%   |
| Realtek Laptop_Integrated_Webcam_HD           | 1         | 1.47%   |
| Realtek Integrated_Webcam_HD                  | 1         | 1.47%   |
| Quanta ov9734_techfront_camera                | 1         | 1.47%   |
| Quanta HP Webcam-101                          | 1         | 1.47%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.47%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.47%   |
| Logitech HD Webcam C615                       | 1         | 1.47%   |
| Lite-On HP HD Webcam                          | 1         | 1.47%   |
| Lenovo CNF7237&CNF7238                        | 1         | 1.47%   |
| IMC Networks TOSHIBA Web Camera - HD          | 1         | 1.47%   |
| IMC Networks Integrated Camera                | 1         | 1.47%   |
| Chicony USB2.0 VGA UVC WebCam                 | 1         | 1.47%   |
| Chicony USB2.0 Camera                         | 1         | 1.47%   |
| Chicony USB 2.0 Camera                        | 1         | 1.47%   |
| Chicony TOSHIBA Web Camera - HD               | 1         | 1.47%   |
| Chicony LG Camera                             | 1         | 1.47%   |
| Chicony Integrated HP HD Webcam               | 1         | 1.47%   |
| Chicony Integrated Camera [ThinkPad]          | 1         | 1.47%   |
| Chicony HP Truevision HD                      | 1         | 1.47%   |
| Chicony HD Webcam                             | 1         | 1.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 30.77%  |
| Shenzhen Goodix Technology | 4         | 30.77%  |
| Upek                       | 2         | 15.38%  |
| Synaptics                  | 1         | 7.69%   |
| Elan Microelectronics      | 1         | 7.69%   |
| AuthenTec                  | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 30.77%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 15.38%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 7.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 7.69%   |
| Elan ELAN:ARM-M4                                                           | 1         | 7.69%   |
| AuthenTec AES1600                                                          | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 36.36%  |
| Alcor Micro           | 3         | 27.27%  |
| Upek                  | 1         | 9.09%   |
| SCM Microsystems      | 1         | 9.09%   |
| O2 Micro              | 1         | 9.09%   |
| Advanced Card Systems | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 18.18%  |
| Broadcom 58200                                                               | 2         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 9.09%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 45        | 60%     |
| 1     | 22        | 29.33%  |
| 2     | 7         | 9.33%   |
| 3     | 1         | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 36.11%  |
| Chipcard              | 11        | 30.56%  |
| Net/wireless          | 3         | 8.33%   |
| Graphics card         | 3         | 8.33%   |
| Camera                | 2         | 5.56%   |
| Bluetooth             | 2         | 5.56%   |
| Multimedia controller | 1         | 2.78%   |
| Flash memory          | 1         | 2.78%   |


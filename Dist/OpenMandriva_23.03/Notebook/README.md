OpenMandriva 23.03 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 23.03.

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

Total: 737

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E1-572               | [532d86f9e6](https://linux-hardware.org/?probe=532d86f9e6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [03660fb140](https://linux-hardware.org/?probe=03660fb140) | Jun 10, 2023 |
| HP            | G42                         | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| HP            | Stream Notebook PC 11       | [fd037bb738](https://linux-hardware.org/?probe=fd037bb738) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| Razer         | Blade 15 Advanced Model ... | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4c3091f9ff](https://linux-hardware.org/?probe=4c3091f9ff) | Jun 06, 2023 |
| Lenovo        | Z50-70 20354                | [05a473a2be](https://linux-hardware.org/?probe=05a473a2be) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [681baff23c](https://linux-hardware.org/?probe=681baff23c) | Jun 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [5d6b08920f](https://linux-hardware.org/?probe=5d6b08920f) | Jun 03, 2023 |
| Compaq        | 420                         | [cf7a8f5641](https://linux-hardware.org/?probe=cf7a8f5641) | Jun 03, 2023 |
| Valve         | Jupiter                     | [3aa6cf6780](https://linux-hardware.org/?probe=3aa6cf6780) | Jun 03, 2023 |
| HP            | EliteBook 8440p             | [7f95f275b3](https://linux-hardware.org/?probe=7f95f275b3) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| Lenovo        | B51-80 80LM                 | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| HP            | Laptop 15-dw3xxx            | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| Apple         | MacBookAir9,1               | [b3e3a95a06](https://linux-hardware.org/?probe=b3e3a95a06) | Jun 01, 2023 |
| Dell          | System Vostro 3450          | [ae337aeb9c](https://linux-hardware.org/?probe=ae337aeb9c) | May 31, 2023 |
| Timi          | RedmiBook 14 II             | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| HP            | 255 G8 Notebook PC          | [ea55e0ac39](https://linux-hardware.org/?probe=ea55e0ac39) | May 30, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Samsung       | RV419/RV420                 | [ddab046bd5](https://linux-hardware.org/?probe=ddab046bd5) | May 30, 2023 |
| Acer          | Aspire ES1-512              | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| Google        | Auron_Paine                 | [66fd27934f](https://linux-hardware.org/?probe=66fd27934f) | May 29, 2023 |
| Acer          | Aspire E5-573               | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| Lenovo        | ThinkPad W541 20EF000MUS    | [44c1329399](https://linux-hardware.org/?probe=44c1329399) | May 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [42b817db26](https://linux-hardware.org/?probe=42b817db26) | May 29, 2023 |
| Acer          | Aspire VX5-591G             | [1db96272fe](https://linux-hardware.org/?probe=1db96272fe) | May 29, 2023 |
| Lenovo        | G400 20235                  | [193fbef9a1](https://linux-hardware.org/?probe=193fbef9a1) | May 28, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| Dell          | Inspiron 7559               | [af1bb009ca](https://linux-hardware.org/?probe=af1bb009ca) | May 28, 2023 |
| Lenovo        | ThinkPad T420 4236N79       | [9908724093](https://linux-hardware.org/?probe=9908724093) | May 28, 2023 |
| Toshiba       | Satellite L500              | [b1213efe40](https://linux-hardware.org/?probe=b1213efe40) | May 28, 2023 |
| Acer          | Aspire 7540                 | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| Toshiba       | Satellite C645D             | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Samsung       | 270E5J/2570EJ               | [f90f831805](https://linux-hardware.org/?probe=f90f831805) | May 28, 2023 |
| HP            | 15 Notebook PC              | [3904ffdddf](https://linux-hardware.org/?probe=3904ffdddf) | May 27, 2023 |
| Acer          | Aspire A517-51G             | [bfc89878ce](https://linux-hardware.org/?probe=bfc89878ce) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| Dell          | Inspiron 5567               | [9dc73257dc](https://linux-hardware.org/?probe=9dc73257dc) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| Dell          | Latitude 5290               | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| MSI           | GL75 Leopard 10SDK          | [41eac45c5e](https://linux-hardware.org/?probe=41eac45c5e) | May 25, 2023 |
| Dell          | Inspiron 15-3567            | [a8dd30a7bb](https://linux-hardware.org/?probe=a8dd30a7bb) | May 25, 2023 |
| Timi          | TM1701                      | [c883337466](https://linux-hardware.org/?probe=c883337466) | May 24, 2023 |
| Toshiba       | Satellite C660D             | [cd798092df](https://linux-hardware.org/?probe=cd798092df) | May 23, 2023 |
| Lenovo        | ThinkPad L520 5017A62       | [a8d01c9adb](https://linux-hardware.org/?probe=a8d01c9adb) | May 23, 2023 |
| Apple         | MacBookPro9,2               | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [76db4a03a1](https://linux-hardware.org/?probe=76db4a03a1) | May 22, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| Dell          | Latitude E6230              | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| ASUSTek       | K84L                        | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| HP            | Pavilion dv7                | [816fffab13](https://linux-hardware.org/?probe=816fffab13) | May 21, 2023 |
| Philco        | 14H                         | [5dbb0cb3b7](https://linux-hardware.org/?probe=5dbb0cb3b7) | May 21, 2023 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | [03afaf2468](https://linux-hardware.org/?probe=03afaf2468) | May 21, 2023 |
| Fujitsu       | LIFEBOOK S752               | [906ba8b65c](https://linux-hardware.org/?probe=906ba8b65c) | May 21, 2023 |
| ASUSTek       | N53TK                       | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Lenovo        | Y50-70 20378                | [2aff70d7c9](https://linux-hardware.org/?probe=2aff70d7c9) | May 21, 2023 |
| Acer          | Aspire 4750                 | [704221c10c](https://linux-hardware.org/?probe=704221c10c) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| HP            | 15 Notebook PC              | [e1939cff8f](https://linux-hardware.org/?probe=e1939cff8f) | May 21, 2023 |
| Toshiba       | Satellite P300              | [ed99950768](https://linux-hardware.org/?probe=ed99950768) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [59464cac80](https://linux-hardware.org/?probe=59464cac80) | May 20, 2023 |
| Dell          | Inspiron 1501               | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Dell          | Latitude 5285               | [0db3cfd34e](https://linux-hardware.org/?probe=0db3cfd34e) | May 20, 2023 |
| HP            | Laptop 15-ef2xxx            | [b563edd887](https://linux-hardware.org/?probe=b563edd887) | May 20, 2023 |
| HP            | 250 G2                      | [e3b94752ac](https://linux-hardware.org/?probe=e3b94752ac) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | [1094884573](https://linux-hardware.org/?probe=1094884573) | May 19, 2023 |
| Chuwi         | HeroBook Pro                | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| ASUSTek       | F7Se                        | [1cd79e84fd](https://linux-hardware.org/?probe=1cd79e84fd) | May 19, 2023 |
| Lenovo        | ThinkPad L560 20F2S1JP03    | [d0dd999b33](https://linux-hardware.org/?probe=d0dd999b33) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [82dca1cbb8](https://linux-hardware.org/?probe=82dca1cbb8) | May 18, 2023 |
| Toshiba       | Satellite L850-1HQ          | [d16c26b474](https://linux-hardware.org/?probe=d16c26b474) | May 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [df73f83c15](https://linux-hardware.org/?probe=df73f83c15) | May 18, 2023 |
| Google        | Auron_Paine                 | [a836fcd48f](https://linux-hardware.org/?probe=a836fcd48f) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| HP            | Pavilion g6                 | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| Lenovo        | V15-ADA 82C7                | [cfe4d9071b](https://linux-hardware.org/?probe=cfe4d9071b) | May 16, 2023 |
| Samsung       | R428/P428                   | [1d93335f58](https://linux-hardware.org/?probe=1d93335f58) | May 15, 2023 |
| HP            | Pavilion dv8                | [422d1fd213](https://linux-hardware.org/?probe=422d1fd213) | May 14, 2023 |
| Acer          | Aspire A114-32              | [6fdf42b8a9](https://linux-hardware.org/?probe=6fdf42b8a9) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| ASUSTek       | K53BR                       | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Dell          | Precision M4500             | [315cccc082](https://linux-hardware.org/?probe=315cccc082) | May 14, 2023 |
| Lenovo        | G50-30 80G0                 | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Vostro 3400                 | [37eeeb2f31](https://linux-hardware.org/?probe=37eeeb2f31) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Toshiba       | Satellite C75-A             | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| Acer          | Extensa 5220                | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| Chuwi         | GemiBook Pro                | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| HP            | Laptop 17-by0xxx            | [10b9d3a925](https://linux-hardware.org/?probe=10b9d3a925) | May 11, 2023 |
| Acer          | Aspire E1-521               | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| ASUSTek       | X555LAB                     | [2710a15a04](https://linux-hardware.org/?probe=2710a15a04) | May 10, 2023 |
| Samsung       | X420/X520                   | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Dell          | Precision M3800             | [e7b0097a72](https://linux-hardware.org/?probe=e7b0097a72) | May 09, 2023 |
| Dell          | Inspiron 5559               | [f7cb6c9251](https://linux-hardware.org/?probe=f7cb6c9251) | May 09, 2023 |
| Dell          | Latitude 5420               | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| Fujitsu       | FMVA0500TP                  | [61061bd78d](https://linux-hardware.org/?probe=61061bd78d) | May 09, 2023 |
| Acer          | Aspire VN7-592G             | [8ebde36ef2](https://linux-hardware.org/?probe=8ebde36ef2) | May 09, 2023 |
| Acer          | Aspire A515-56              | [57b843a3ca](https://linux-hardware.org/?probe=57b843a3ca) | May 09, 2023 |
| Apple         | MacBookPro11,4              | [83f86e5727](https://linux-hardware.org/?probe=83f86e5727) | May 09, 2023 |
| Dell          | Latitude E6440              | [6b8d3c96c5](https://linux-hardware.org/?probe=6b8d3c96c5) | May 09, 2023 |
| HP            | Pavilion dv7                | [1d9699c86f](https://linux-hardware.org/?probe=1d9699c86f) | May 09, 2023 |
| HP            | Pavilion dv6                | [531adb6cae](https://linux-hardware.org/?probe=531adb6cae) | May 09, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| HP            | 15                          | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| Acer          | Aspire ES1-132              | [10a13dcd68](https://linux-hardware.org/?probe=10a13dcd68) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [d615a9b90f](https://linux-hardware.org/?probe=d615a9b90f) | May 08, 2023 |
| ASUSTek       | X202E                       | [6039408aaf](https://linux-hardware.org/?probe=6039408aaf) | May 08, 2023 |
| HP            | 15                          | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Dell          | XPS 13 9310                 | [3530619c98](https://linux-hardware.org/?probe=3530619c98) | May 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b734a6d6f3](https://linux-hardware.org/?probe=b734a6d6f3) | May 07, 2023 |
| Toshiba       | Satellite L655              | [9eef570443](https://linux-hardware.org/?probe=9eef570443) | May 07, 2023 |
| Lenovo        | G50-70 20351                | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| HP            | Presario CQ57               | [370295ac6d](https://linux-hardware.org/?probe=370295ac6d) | May 07, 2023 |
| Dell          | System XPS L702X            | [210b876fe7](https://linux-hardware.org/?probe=210b876fe7) | May 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b3bf20b454](https://linux-hardware.org/?probe=b3bf20b454) | May 06, 2023 |
| Panasonic     | CF-54-1                     | [c964ce47c2](https://linux-hardware.org/?probe=c964ce47c2) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [094b22cf5a](https://linux-hardware.org/?probe=094b22cf5a) | May 06, 2023 |
| Toshiba       | Satellite L300D             | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| HP            | EliteBook 2530p             | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| ASUSTek       | K75DE                       | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| ASUSTek       | X401A1                      | [3fa1a1e9f0](https://linux-hardware.org/?probe=3fa1a1e9f0) | May 05, 2023 |
| Dell          | Inspiron 17-7779            | [f5717fc896](https://linux-hardware.org/?probe=f5717fc896) | May 04, 2023 |
| Medion        | E6232                       | [38b433b485](https://linux-hardware.org/?probe=38b433b485) | May 04, 2023 |
| Gateway       | NE46R                       | [05291d9029](https://linux-hardware.org/?probe=05291d9029) | May 04, 2023 |
| HP            | Laptop 17-ak0xx             | [579c16cd5c](https://linux-hardware.org/?probe=579c16cd5c) | May 04, 2023 |
| HP            | EliteBook 8540p             | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Fujitsu       | FMVA705ABS                  | [99cb877cba](https://linux-hardware.org/?probe=99cb877cba) | May 04, 2023 |
| Toshiba       | dynabook SS M42 210E/3W     | [ad7f7da4e4](https://linux-hardware.org/?probe=ad7f7da4e4) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [218ba5d6a5](https://linux-hardware.org/?probe=218ba5d6a5) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [d8ec895bea](https://linux-hardware.org/?probe=d8ec895bea) | May 03, 2023 |
| Dell          | Latitude E6410              | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| Dell          | Latitude E6540              | [e9f23b9574](https://linux-hardware.org/?probe=e9f23b9574) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [530aaeef9d](https://linux-hardware.org/?probe=530aaeef9d) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [cb2a0efe72](https://linux-hardware.org/?probe=cb2a0efe72) | May 02, 2023 |
| Toshiba       | Satellite L755              | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| Lenovo        | V15-IGL 82C3                | [583642a695](https://linux-hardware.org/?probe=583642a695) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| HP            | Compaq 8510w                | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [15c04364fa](https://linux-hardware.org/?probe=15c04364fa) | May 01, 2023 |
| lapbook       | S15 PRO                     | [d4b7c4a4db](https://linux-hardware.org/?probe=d4b7c4a4db) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| HP            | Notebook                    | [4cece109d5](https://linux-hardware.org/?probe=4cece109d5) | Apr 30, 2023 |
| ASUSTek       | X501A1                      | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| Acer          | Aspire A315-33              | [fdba59c054](https://linux-hardware.org/?probe=fdba59c054) | Apr 30, 2023 |
| Acer          | AO725                       | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| HP            | Compaq 6720s                | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | ProBook 650 G4              | [fd991056e0](https://linux-hardware.org/?probe=fd991056e0) | Apr 30, 2023 |
| Dell          | Inspiron 15 3525            | [41c212fa2c](https://linux-hardware.org/?probe=41c212fa2c) | Apr 30, 2023 |
| Acer          | TravelMate B311-31          | [de172b8988](https://linux-hardware.org/?probe=de172b8988) | Apr 30, 2023 |
| Dell          | Vostro 15 3515              | [8f07407e1a](https://linux-hardware.org/?probe=8f07407e1a) | Apr 29, 2023 |
| Lenovo        | G50-30 80G0                 | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| Toshiba       | PORTEGE R830                | [11dc4b3a3e](https://linux-hardware.org/?probe=11dc4b3a3e) | Apr 29, 2023 |
| Apple         | MacBookPro13,3              | [0f22698060](https://linux-hardware.org/?probe=0f22698060) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| HP            | Pavilion Notebook           | [168b3cf595](https://linux-hardware.org/?probe=168b3cf595) | Apr 29, 2023 |
| Dell          | Latitude 7390               | [c24cc9ab68](https://linux-hardware.org/?probe=c24cc9ab68) | Apr 29, 2023 |
| Medion        | X6816                       | [2c1807dad7](https://linux-hardware.org/?probe=2c1807dad7) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| ASUSTek       | X542URR                     | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| GPU Compan... | GWNR71517                   | [5fe84b74b0](https://linux-hardware.org/?probe=5fe84b74b0) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| Sony          | SVF15212CXW                 | [5d5367dc0e](https://linux-hardware.org/?probe=5d5367dc0e) | Apr 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| HP            | ProBook 4330s               | [955f91641b](https://linux-hardware.org/?probe=955f91641b) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| Lenovo        | ThinkPad R61 8943DJG        | [afc3fc578e](https://linux-hardware.org/?probe=afc3fc578e) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| NEC Comput... | PC-LE150C2                  | [a8e48f9686](https://linux-hardware.org/?probe=a8e48f9686) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [32960eca65](https://linux-hardware.org/?probe=32960eca65) | Apr 27, 2023 |
| Dell          | Latitude E6400              | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [21577119ad](https://linux-hardware.org/?probe=21577119ad) | Apr 27, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| Lenovo        | ThinkPad L512 4444PS9       | [78cf80b13b](https://linux-hardware.org/?probe=78cf80b13b) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [84bc235979](https://linux-hardware.org/?probe=84bc235979) | Apr 26, 2023 |
| ASUSTek       | X550CA                      | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| Unknown       | Unknown                     | [208f6823ed](https://linux-hardware.org/?probe=208f6823ed) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| GPU Compan... | GWNR71517                   | [b8b58af983](https://linux-hardware.org/?probe=b8b58af983) | Apr 26, 2023 |
| ASUSTek       | X550VQ                      | [3c7d8a0268](https://linux-hardware.org/?probe=3c7d8a0268) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [2e6de51ded](https://linux-hardware.org/?probe=2e6de51ded) | Apr 26, 2023 |
| Login Info... | LOG-S14BW01-CD              | [5f6e2a61f2](https://linux-hardware.org/?probe=5f6e2a61f2) | Apr 25, 2023 |
| Sony          | VPCS13V9E                   | [3c1551d7be](https://linux-hardware.org/?probe=3c1551d7be) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Lenovo        | ThinkPad SL500 2746CTO      | [7283a0f4d9](https://linux-hardware.org/?probe=7283a0f4d9) | Apr 25, 2023 |
| HP            | Compaq 15                   | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| Toshiba       | Satellite L305D             | [1bbf3a5e9c](https://linux-hardware.org/?probe=1bbf3a5e9c) | Apr 25, 2023 |
| ICL           | RAYbook Si1512              | [6aa907fd2e](https://linux-hardware.org/?probe=6aa907fd2e) | Apr 25, 2023 |
| Fujitsu       | LIFEBOOK S935               | [418c2c626e](https://linux-hardware.org/?probe=418c2c626e) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| Dell          | Latitude XT2                | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Chuwi         | GemiBook Pro                | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| Acer          | Aspire V5-552P              | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| ASUSTek       | S551LN                      | [9ba55985fd](https://linux-hardware.org/?probe=9ba55985fd) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Lenovo        | G550 2958                   | [7a1a8bb421](https://linux-hardware.org/?probe=7a1a8bb421) | Apr 23, 2023 |
| Toshiba       | dynabook BX/67TG            | [5349d462cd](https://linux-hardware.org/?probe=5349d462cd) | Apr 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6115e5ccd4](https://linux-hardware.org/?probe=6115e5ccd4) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 6930p             | [2ff545a3fc](https://linux-hardware.org/?probe=2ff545a3fc) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [63599179ae](https://linux-hardware.org/?probe=63599179ae) | Apr 22, 2023 |
| HP            | ProBook 4330s               | [f6608ffee2](https://linux-hardware.org/?probe=f6608ffee2) | Apr 22, 2023 |
| HP            | ProBook 450 G3              | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Acer          | Extensa 5635Z               | [015e857f63](https://linux-hardware.org/?probe=015e857f63) | Apr 22, 2023 |
| Notebook      | N13_N140ZU                  | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| ASUSTek       | S551LN                      | [c974888840](https://linux-hardware.org/?probe=c974888840) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [fc70e3e9e0](https://linux-hardware.org/?probe=fc70e3e9e0) | Apr 21, 2023 |
| HP            | Compaq 6720s                | [b980c3c57d](https://linux-hardware.org/?probe=b980c3c57d) | Apr 21, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [da51714544](https://linux-hardware.org/?probe=da51714544) | Apr 21, 2023 |
| Dell          | Inspiron 3520               | [11ea81f23c](https://linux-hardware.org/?probe=11ea81f23c) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| Acer          | Aspire 5745                 | [19e6d70ce0](https://linux-hardware.org/?probe=19e6d70ce0) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [44459cbe3a](https://linux-hardware.org/?probe=44459cbe3a) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| Dell          | Latitude 5400               | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| HP            | G62                         | [a0096bb254](https://linux-hardware.org/?probe=a0096bb254) | Apr 20, 2023 |
| MSI           | GE62 6QD                    | [785d4c1655](https://linux-hardware.org/?probe=785d4c1655) | Apr 20, 2023 |
| Toshiba       | dynabook T451/46EW          | [e45702b9aa](https://linux-hardware.org/?probe=e45702b9aa) | Apr 20, 2023 |
| HP            | ProBook 450 G2              | [14d03d2dd7](https://linux-hardware.org/?probe=14d03d2dd7) | Apr 19, 2023 |
| HP            | 255 G7 Notebook PC          | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| ASUSTek       | N501VW                      | [a31036cae1](https://linux-hardware.org/?probe=a31036cae1) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| ASUSTek       | UX305CA                     | [0ff08e0727](https://linux-hardware.org/?probe=0ff08e0727) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| Acer          | Aspire 5733Z                | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| Dell          | Vostro 5471                 | [5cbbc95995](https://linux-hardware.org/?probe=5cbbc95995) | Apr 19, 2023 |
| Dell          | Inspiron 15-3567            | [c5639cddcb](https://linux-hardware.org/?probe=c5639cddcb) | Apr 19, 2023 |
| Apple         | MacBookPro8,1               | [4e95dc284c](https://linux-hardware.org/?probe=4e95dc284c) | Apr 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6fae9a24fb](https://linux-hardware.org/?probe=6fae9a24fb) | Apr 19, 2023 |
| HP            | Unknown                     | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| HP            | Pavilion Laptop 17-ar0xx    | [76aabd80a0](https://linux-hardware.org/?probe=76aabd80a0) | Apr 18, 2023 |
| Acer          | AO722                       | [5fe24a9991](https://linux-hardware.org/?probe=5fe24a9991) | Apr 18, 2023 |
| Lenovo        | B50-30 20382                | [d8995dacdc](https://linux-hardware.org/?probe=d8995dacdc) | Apr 18, 2023 |
| Fujitsu       | FMVNA6HE                    | [609572e6f7](https://linux-hardware.org/?probe=609572e6f7) | Apr 18, 2023 |
| Lenovo        | ThinkPad P53 20QN001YUS     | [59549202bd](https://linux-hardware.org/?probe=59549202bd) | Apr 18, 2023 |
| Apple         | MacBookPro8,1               | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| HP            | ProBook 645 G1              | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| Medion        | E16401                      | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| HP            | Laptop 15-db1xxx            | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| Dell          | Latitude D830               | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a2b27dd2d6](https://linux-hardware.org/?probe=a2b27dd2d6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [14517ef743](https://linux-hardware.org/?probe=14517ef743) | Apr 17, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| Dell          | XPS 17 9700                 | [3ad1ee8197](https://linux-hardware.org/?probe=3ad1ee8197) | Apr 16, 2023 |
| Dell          | Precision 7510              | [abb2d93e32](https://linux-hardware.org/?probe=abb2d93e32) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Dell          | Latitude E6330              | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| ASUSTek       | K73E                        | [9ab8e37631](https://linux-hardware.org/?probe=9ab8e37631) | Apr 15, 2023 |
| Fujitsu Si... | ESPRIMO Mobile X9515        | [82ffd0e4bd](https://linux-hardware.org/?probe=82ffd0e4bd) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [6c711c5197](https://linux-hardware.org/?probe=6c711c5197) | Apr 15, 2023 |
| Dell          | Precision 7730              | [0e434903ec](https://linux-hardware.org/?probe=0e434903ec) | Apr 15, 2023 |
| MSI           | Modern 14 B10MW             | [c655afe860](https://linux-hardware.org/?probe=c655afe860) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [2e860ef402](https://linux-hardware.org/?probe=2e860ef402) | Apr 15, 2023 |
| GPD           | G1619-01                    | [2edac2c38e](https://linux-hardware.org/?probe=2edac2c38e) | Apr 15, 2023 |
| MSI           | Prestige 15 A12SC           | [51259c6f0a](https://linux-hardware.org/?probe=51259c6f0a) | Apr 15, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [dfed605628](https://linux-hardware.org/?probe=dfed605628) | Apr 15, 2023 |
| Acer          | Swift SF314-511             | [f960c27052](https://linux-hardware.org/?probe=f960c27052) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | [f3b7c9c255](https://linux-hardware.org/?probe=f3b7c9c255) | Apr 14, 2023 |
| MSI           | Delta 15 A5EFK              | [44cdfb0917](https://linux-hardware.org/?probe=44cdfb0917) | Apr 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | [a5cb4f9095](https://linux-hardware.org/?probe=a5cb4f9095) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Sony          | VGN-NR11Z_T                 | [d7d5674aa5](https://linux-hardware.org/?probe=d7d5674aa5) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [e3f3f9fd2b](https://linux-hardware.org/?probe=e3f3f9fd2b) | Apr 14, 2023 |
| HP            | Pavilion dv6                | [3f719938aa](https://linux-hardware.org/?probe=3f719938aa) | Apr 14, 2023 |
| Lenovo        | G505 20240                  | [62bdfa97bd](https://linux-hardware.org/?probe=62bdfa97bd) | Apr 14, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [8fb8771c70](https://linux-hardware.org/?probe=8fb8771c70) | Apr 14, 2023 |
| Dell          | Latitude E6540              | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| Dell          | Vostro 14-3468              | [947f70ebf7](https://linux-hardware.org/?probe=947f70ebf7) | Apr 13, 2023 |
| Toshiba       | Satellite L75D-A            | [210a475989](https://linux-hardware.org/?probe=210a475989) | Apr 13, 2023 |
| Acer          | Aspire A315-56              | [8c2cc310b2](https://linux-hardware.org/?probe=8c2cc310b2) | Apr 13, 2023 |
| System76      | Galago Pro                  | [9239e8d213](https://linux-hardware.org/?probe=9239e8d213) | Apr 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a841c5fce3](https://linux-hardware.org/?probe=a841c5fce3) | Apr 13, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f983dadfeb](https://linux-hardware.org/?probe=f983dadfeb) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [830a3e27dd](https://linux-hardware.org/?probe=830a3e27dd) | Apr 13, 2023 |
| Toshiba       | Satellite L300D             | [76595cf176](https://linux-hardware.org/?probe=76595cf176) | Apr 12, 2023 |
| Toshiba       | Satellite C660              | [551fabbc17](https://linux-hardware.org/?probe=551fabbc17) | Apr 12, 2023 |
| Dell          | Latitude E6230              | [a7cce7ebde](https://linux-hardware.org/?probe=a7cce7ebde) | Apr 12, 2023 |
| Acer          | Aspire 5733Z                | [b42b19277c](https://linux-hardware.org/?probe=b42b19277c) | Apr 12, 2023 |
| ASUSTek       | K53U                        | [19ec753136](https://linux-hardware.org/?probe=19ec753136) | Apr 12, 2023 |
| HUAWEI        | HLYL-WXX9                   | [db51c5a1f3](https://linux-hardware.org/?probe=db51c5a1f3) | Apr 12, 2023 |
| Toshiba       | Satellite L350D             | [df4e0aa857](https://linux-hardware.org/?probe=df4e0aa857) | Apr 12, 2023 |
| HP            | Presario CQ62               | [edee5d8480](https://linux-hardware.org/?probe=edee5d8480) | Apr 12, 2023 |
| Samsung       | R460                        | [9908964d4a](https://linux-hardware.org/?probe=9908964d4a) | Apr 11, 2023 |
| Lenovo        | IdeaPad Z470                | [2348aee3d4](https://linux-hardware.org/?probe=2348aee3d4) | Apr 11, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [238037e4b8](https://linux-hardware.org/?probe=238037e4b8) | Apr 11, 2023 |
| Dell          | Inspiron N4010              | [c52176294b](https://linux-hardware.org/?probe=c52176294b) | Apr 11, 2023 |
| Lenovo        | ThinkPad L580 20LW000VMX    | [7b2e3794c9](https://linux-hardware.org/?probe=7b2e3794c9) | Apr 11, 2023 |
| Lenovo        | B590 20206                  | [5aad144224](https://linux-hardware.org/?probe=5aad144224) | Apr 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fc305814c4](https://linux-hardware.org/?probe=fc305814c4) | Apr 11, 2023 |
| Acer          | TM6495T                     | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| Avell High... | A52 HYB                     | [0795bca947](https://linux-hardware.org/?probe=0795bca947) | Apr 11, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [eb294beef7](https://linux-hardware.org/?probe=eb294beef7) | Apr 11, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [52b464bfd3](https://linux-hardware.org/?probe=52b464bfd3) | Apr 10, 2023 |
| ASUSTek       | X541UV                      | [07b7bedac7](https://linux-hardware.org/?probe=07b7bedac7) | Apr 10, 2023 |
| Lenovo        | 3000 V200 07642XU           | [365e3a50d2](https://linux-hardware.org/?probe=365e3a50d2) | Apr 10, 2023 |
| ASUSTek       | N552VX                      | [a5bf121256](https://linux-hardware.org/?probe=a5bf121256) | Apr 10, 2023 |
| ASUSTek       | G751JY                      | [618a195c21](https://linux-hardware.org/?probe=618a195c21) | Apr 10, 2023 |
| Packard Be... | EasyNote LS11HR             | [56f4b51911](https://linux-hardware.org/?probe=56f4b51911) | Apr 10, 2023 |
| ASUSTek       | UX303UB                     | [f94b0ee950](https://linux-hardware.org/?probe=f94b0ee950) | Apr 10, 2023 |
| HP            | EliteBook 840 G5            | [da4c241466](https://linux-hardware.org/?probe=da4c241466) | Apr 10, 2023 |
| HP            | EliteBook 2170p             | [34f1e1686e](https://linux-hardware.org/?probe=34f1e1686e) | Apr 10, 2023 |
| Lenovo        | ThinkPad X201 3680WFQ       | [f90c2d47c7](https://linux-hardware.org/?probe=f90c2d47c7) | Apr 10, 2023 |
| Lenovo        | ThinkPad T420s 417152U      | [5964d01442](https://linux-hardware.org/?probe=5964d01442) | Apr 10, 2023 |
| Dell          | Inspiron 3583               | [502c993dfd](https://linux-hardware.org/?probe=502c993dfd) | Apr 10, 2023 |
| HP            | Notebook                    | [4a5d785f73](https://linux-hardware.org/?probe=4a5d785f73) | Apr 09, 2023 |
| Gigabyte      | MMLP3AP-00                  | [6fd82ceaec](https://linux-hardware.org/?probe=6fd82ceaec) | Apr 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [332f3ed32f](https://linux-hardware.org/?probe=332f3ed32f) | Apr 09, 2023 |
| Positivo      | A1000BW                     | [02295facdc](https://linux-hardware.org/?probe=02295facdc) | Apr 09, 2023 |
| Sony          | VPCEB1M1E                   | [c182925286](https://linux-hardware.org/?probe=c182925286) | Apr 09, 2023 |
| HP            | EliteBook 8570p             | [854ec28c71](https://linux-hardware.org/?probe=854ec28c71) | Apr 09, 2023 |
| lapbook       | S15 PRO                     | [5a039fc6fb](https://linux-hardware.org/?probe=5a039fc6fb) | Apr 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [d6cbe10f95](https://linux-hardware.org/?probe=d6cbe10f95) | Apr 09, 2023 |
| Lenovo        | B575 1450ABU                | [ef58d2e8e6](https://linux-hardware.org/?probe=ef58d2e8e6) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | [8def87668b](https://linux-hardware.org/?probe=8def87668b) | Apr 09, 2023 |
| SLIMBOOK      | EXECUTIVE-14                | [e66056ac2d](https://linux-hardware.org/?probe=e66056ac2d) | Apr 09, 2023 |
| Lenovo        | ThinkPad X131e 33722VU      | [5e2ba16114](https://linux-hardware.org/?probe=5e2ba16114) | Apr 09, 2023 |
| Samsung       | RV419                       | [88985a3d0d](https://linux-hardware.org/?probe=88985a3d0d) | Apr 09, 2023 |
| Sony          | SVE1713A1EW                 | [402fae93d5](https://linux-hardware.org/?probe=402fae93d5) | Apr 09, 2023 |
| Acer          | Aspire ES1-531              | [f36574c96a](https://linux-hardware.org/?probe=f36574c96a) | Apr 09, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | [779e8396d6](https://linux-hardware.org/?probe=779e8396d6) | Apr 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d261eb3697](https://linux-hardware.org/?probe=d261eb3697) | Apr 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | [eab5adc4e6](https://linux-hardware.org/?probe=eab5adc4e6) | Apr 09, 2023 |
| Google        | Lindar rev3                 | [e6dd3f6805](https://linux-hardware.org/?probe=e6dd3f6805) | Apr 09, 2023 |
| Dell          | Inspiron 7720               | [27df270817](https://linux-hardware.org/?probe=27df270817) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [fa54308baa](https://linux-hardware.org/?probe=fa54308baa) | Apr 09, 2023 |
| Apple         | MacBook5,2                  | [916db99ea5](https://linux-hardware.org/?probe=916db99ea5) | Apr 09, 2023 |
| Toshiba       | Satellite C660              | [bb9f88795d](https://linux-hardware.org/?probe=bb9f88795d) | Apr 09, 2023 |
| Acer          | Enduro EUN314-51WG          | [7f73117dba](https://linux-hardware.org/?probe=7f73117dba) | Apr 09, 2023 |
| Dell          | Latitude E6420              | [56f5370788](https://linux-hardware.org/?probe=56f5370788) | Apr 09, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [ea9bd3a740](https://linux-hardware.org/?probe=ea9bd3a740) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7659AB7        | [0b2f9a23ee](https://linux-hardware.org/?probe=0b2f9a23ee) | Apr 09, 2023 |
| Fujitsu       | LIFEBOOK E752               | [e60f7c9b72](https://linux-hardware.org/?probe=e60f7c9b72) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [c8173d40cd](https://linux-hardware.org/?probe=c8173d40cd) | Apr 09, 2023 |
| Dell          | Inspiron 7570               | [2bac711aba](https://linux-hardware.org/?probe=2bac711aba) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [2652354b7a](https://linux-hardware.org/?probe=2652354b7a) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | [93e9be5f34](https://linux-hardware.org/?probe=93e9be5f34) | Apr 09, 2023 |
| Lenovo        | G50-70 20351                | [7ab9939757](https://linux-hardware.org/?probe=7ab9939757) | Apr 09, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [675aea5637](https://linux-hardware.org/?probe=675aea5637) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | [a2e3b07f6b](https://linux-hardware.org/?probe=a2e3b07f6b) | Apr 09, 2023 |
| HP            | Laptop 17-by4xxx            | [03cfb9e574](https://linux-hardware.org/?probe=03cfb9e574) | Apr 09, 2023 |
| HP            | Compaq 6530b (KR978UT#AB... | [3d8060476b](https://linux-hardware.org/?probe=3d8060476b) | Apr 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [5d39494c01](https://linux-hardware.org/?probe=5d39494c01) | Apr 09, 2023 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1701c2baae](https://linux-hardware.org/?probe=1701c2baae) | Apr 08, 2023 |
| ASUSTek       | X540LA                      | [38299d8248](https://linux-hardware.org/?probe=38299d8248) | Apr 08, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [869d7607e9](https://linux-hardware.org/?probe=869d7607e9) | Apr 08, 2023 |
| HP            | EliteBook 2560p             | [a4b27a5659](https://linux-hardware.org/?probe=a4b27a5659) | Apr 08, 2023 |
| HP            | 250 G6 Notebook PC          | [22da370a63](https://linux-hardware.org/?probe=22da370a63) | Apr 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [12faf271f6](https://linux-hardware.org/?probe=12faf271f6) | Apr 08, 2023 |
| Sony          | VPCSE1V9E                   | [e6dd1647f3](https://linux-hardware.org/?probe=e6dd1647f3) | Apr 08, 2023 |
| ASUSTek       | X751LN                      | [8bf4f37814](https://linux-hardware.org/?probe=8bf4f37814) | Apr 08, 2023 |
| Acer          | Predator PH315-54           | [edbc0b98a4](https://linux-hardware.org/?probe=edbc0b98a4) | Apr 08, 2023 |
| Standard      | SF20BA2                     | [17763324b6](https://linux-hardware.org/?probe=17763324b6) | Apr 08, 2023 |
| HP            | Notebook                    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| Dell          | Latitude 3410               | [9fd7d9d439](https://linux-hardware.org/?probe=9fd7d9d439) | Apr 08, 2023 |
| Acer          | Aspire E5-575G              | [37194169cd](https://linux-hardware.org/?probe=37194169cd) | Apr 08, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [14a3d5f4be](https://linux-hardware.org/?probe=14a3d5f4be) | Apr 08, 2023 |
| Dell          | Inspiron 1520               | [b5b9ede1c6](https://linux-hardware.org/?probe=b5b9ede1c6) | Apr 08, 2023 |
| Toshiba       | dynabook R732/H             | [ff99abe105](https://linux-hardware.org/?probe=ff99abe105) | Apr 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1a6e63f6b2](https://linux-hardware.org/?probe=1a6e63f6b2) | Apr 08, 2023 |
| HP            | ProBook 6470b               | [9926dac4aa](https://linux-hardware.org/?probe=9926dac4aa) | Apr 08, 2023 |
| MSI           | Katana GF66 12UC            | [5d0c8cade6](https://linux-hardware.org/?probe=5d0c8cade6) | Apr 08, 2023 |
| Acer          | Aspire A515-56              | [7c8165c2ca](https://linux-hardware.org/?probe=7c8165c2ca) | Apr 08, 2023 |
| Acer          | Aspire A515-51G             | [34d03fbbcd](https://linux-hardware.org/?probe=34d03fbbcd) | Apr 08, 2023 |
| HP            | Laptop 15-dy2xxx            | [eadf220620](https://linux-hardware.org/?probe=eadf220620) | Apr 08, 2023 |
| Sony          | VJF155F11X-B0811B           | [89f9cc86a7](https://linux-hardware.org/?probe=89f9cc86a7) | Apr 08, 2023 |
| Acer          | Swift SF314-43              | [95cf4404c3](https://linux-hardware.org/?probe=95cf4404c3) | Apr 08, 2023 |
| Lenovo        | ThinkPad L430 24683NG       | [d5f226c56f](https://linux-hardware.org/?probe=d5f226c56f) | Apr 08, 2023 |
| Lenovo        | G50-70 20351                | [b8dd840f5d](https://linux-hardware.org/?probe=b8dd840f5d) | Apr 08, 2023 |
| VIT           | P2402                       | [1c25795c2f](https://linux-hardware.org/?probe=1c25795c2f) | Apr 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [99305e0876](https://linux-hardware.org/?probe=99305e0876) | Apr 07, 2023 |
| Acer          | Aspire 5517                 | [bbedb2d88e](https://linux-hardware.org/?probe=bbedb2d88e) | Apr 07, 2023 |
| Dell          | Inspiron 11-3162            | [accdfd2253](https://linux-hardware.org/?probe=accdfd2253) | Apr 07, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [e5393f2dd6](https://linux-hardware.org/?probe=e5393f2dd6) | Apr 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [76af734c86](https://linux-hardware.org/?probe=76af734c86) | Apr 07, 2023 |
| HP            | EliteBook 2530p             | [66ec38445f](https://linux-hardware.org/?probe=66ec38445f) | Apr 07, 2023 |
| Notebook      | NJ50_70CU                   | [0ad152ba3c](https://linux-hardware.org/?probe=0ad152ba3c) | Apr 07, 2023 |
| Dell          | Latitude 5400               | [f2d5671ba5](https://linux-hardware.org/?probe=f2d5671ba5) | Apr 07, 2023 |
| Lenovo        | ThinkPad T60 2008VW7        | [de0d5654c0](https://linux-hardware.org/?probe=de0d5654c0) | Apr 07, 2023 |
| ASUSTek       | A8Le                        | [c00ff94698](https://linux-hardware.org/?probe=c00ff94698) | Apr 07, 2023 |
| HP            | 250 G6 Notebook PC          | [859f83bbfc](https://linux-hardware.org/?probe=859f83bbfc) | Apr 07, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [aab830c5dd](https://linux-hardware.org/?probe=aab830c5dd) | Apr 07, 2023 |
| HP            | ProBook 650 G4              | [0e9b21ff7e](https://linux-hardware.org/?probe=0e9b21ff7e) | Apr 07, 2023 |
| HP            | Pavilion 17                 | [43d7593dd5](https://linux-hardware.org/?probe=43d7593dd5) | Apr 07, 2023 |
| ASUSTek       | S551LN                      | [2c731aefae](https://linux-hardware.org/?probe=2c731aefae) | Apr 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a3ae05a7cb](https://linux-hardware.org/?probe=a3ae05a7cb) | Apr 07, 2023 |
| Acer          | TravelMate 8572T            | [04f50662d8](https://linux-hardware.org/?probe=04f50662d8) | Apr 07, 2023 |
| ASUSTek       | X555QA                      | [6fb3c3952e](https://linux-hardware.org/?probe=6fb3c3952e) | Apr 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5a900adcdc](https://linux-hardware.org/?probe=5a900adcdc) | Apr 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d48cada4e3](https://linux-hardware.org/?probe=d48cada4e3) | Apr 07, 2023 |
| Dell          | XPS 17 9710                 | [b4c155dc99](https://linux-hardware.org/?probe=b4c155dc99) | Apr 07, 2023 |
| Dell          | Precision M3800             | [6fbee1d04d](https://linux-hardware.org/?probe=6fbee1d04d) | Apr 07, 2023 |
| Dell          | Latitude 5490               | [89f89d2a9e](https://linux-hardware.org/?probe=89f89d2a9e) | Apr 07, 2023 |
| HP            | 620                         | [2e14b2c046](https://linux-hardware.org/?probe=2e14b2c046) | Apr 07, 2023 |
| Lenovo        | ThinkPad T470s 20HF0001M... | [8c6105e5be](https://linux-hardware.org/?probe=8c6105e5be) | Apr 06, 2023 |
| eMachines     | E725                        | [758d0c86b2](https://linux-hardware.org/?probe=758d0c86b2) | Apr 06, 2023 |
| Dell          | Latitude E6440              | [d63602cd95](https://linux-hardware.org/?probe=d63602cd95) | Apr 06, 2023 |
| Acer          | Aspire E5-771               | [2ef87c5f77](https://linux-hardware.org/?probe=2ef87c5f77) | Apr 06, 2023 |
| HP            | ProBook 4740s               | [14fb51de44](https://linux-hardware.org/?probe=14fb51de44) | Apr 06, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2QF0... | [806fc59e4f](https://linux-hardware.org/?probe=806fc59e4f) | Apr 06, 2023 |
| HP            | Compaq Presario CQ70        | [11cd73fbce](https://linux-hardware.org/?probe=11cd73fbce) | Apr 06, 2023 |
| Samsung       | R540/R580/R780/SA41/E452... | [5c446bcf49](https://linux-hardware.org/?probe=5c446bcf49) | Apr 06, 2023 |
| Acer          | Aspire 5750G                | [3fa6f0de7a](https://linux-hardware.org/?probe=3fa6f0de7a) | Apr 06, 2023 |
| ASUSTek       | K46CM                       | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| ASUSTek       | X55U                        | [0abf7df439](https://linux-hardware.org/?probe=0abf7df439) | Apr 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3358152092](https://linux-hardware.org/?probe=3358152092) | Apr 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [0ca203f8b0](https://linux-hardware.org/?probe=0ca203f8b0) | Apr 06, 2023 |
| HP            | Laptop 15-bs0xx             | [c73108de7b](https://linux-hardware.org/?probe=c73108de7b) | Apr 06, 2023 |
| HP            | Compaq Presario CQ71        | [82c50e39ad](https://linux-hardware.org/?probe=82c50e39ad) | Apr 06, 2023 |
| Toshiba       | Satellite Pro L350          | [a75b4d94aa](https://linux-hardware.org/?probe=a75b4d94aa) | Apr 06, 2023 |
| MSI           | GL73 8RC                    | [c134ae92fc](https://linux-hardware.org/?probe=c134ae92fc) | Apr 06, 2023 |
| HP            | Laptop 15-db0xxx            | [e05bffcc8a](https://linux-hardware.org/?probe=e05bffcc8a) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| HUAWEI        | BOM-WXX9                    | [d4dd77439e](https://linux-hardware.org/?probe=d4dd77439e) | Apr 06, 2023 |
| Lenovo        | 3000 N200 0769DQJ           | [db1539e64a](https://linux-hardware.org/?probe=db1539e64a) | Apr 06, 2023 |
| Dell          | Inspiron 1720               | [0f0d515832](https://linux-hardware.org/?probe=0f0d515832) | Apr 06, 2023 |
| Dell          | Latitude E7440              | [3fc74781a7](https://linux-hardware.org/?probe=3fc74781a7) | Apr 06, 2023 |
| Positivo      | H14BT58                     | [135bb6e61a](https://linux-hardware.org/?probe=135bb6e61a) | Apr 06, 2023 |
| Apple         | MacBookPro5,5               | [4e0ff5c2f7](https://linux-hardware.org/?probe=4e0ff5c2f7) | Apr 06, 2023 |
| Lenovo        | ThinkPad X230 2324FU0       | [47be9d7510](https://linux-hardware.org/?probe=47be9d7510) | Apr 06, 2023 |
| ASUSTek       | S551LN                      | [bab2c0f0e4](https://linux-hardware.org/?probe=bab2c0f0e4) | Apr 06, 2023 |
| Dell          | Inspiron 3584               | [50f052ef1c](https://linux-hardware.org/?probe=50f052ef1c) | Apr 06, 2023 |
| HP            | 620                         | [ad46cdbb0d](https://linux-hardware.org/?probe=ad46cdbb0d) | Apr 06, 2023 |
| Dell          | Latitude E4200              | [6dae8e5ff4](https://linux-hardware.org/?probe=6dae8e5ff4) | Apr 05, 2023 |
| Dell          | Latitude E5550              | [5527315153](https://linux-hardware.org/?probe=5527315153) | Apr 05, 2023 |
| Lenovo        | ThinkPad X250 20CLS2X60S    | [b5b5fd68e9](https://linux-hardware.org/?probe=b5b5fd68e9) | Apr 05, 2023 |
| Lenovo        | ThinkPad X61s 7666WJ5       | [eb755a4a95](https://linux-hardware.org/?probe=eb755a4a95) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [0240b337ac](https://linux-hardware.org/?probe=0240b337ac) | Apr 05, 2023 |
| HP            | EliteBook 6930p             | [8e769590fb](https://linux-hardware.org/?probe=8e769590fb) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [5d0489d439](https://linux-hardware.org/?probe=5d0489d439) | Apr 05, 2023 |
| HP            | Notebook                    | [99a9d4cae5](https://linux-hardware.org/?probe=99a9d4cae5) | Apr 05, 2023 |
| ASUSTek       | X71Q                        | [9a7d0f4b2b](https://linux-hardware.org/?probe=9a7d0f4b2b) | Apr 05, 2023 |
| Toshiba       | Satellite L640              | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad E470 20H1006VRT    | [a9b909f3df](https://linux-hardware.org/?probe=a9b909f3df) | Apr 05, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [e27fc333c6](https://linux-hardware.org/?probe=e27fc333c6) | Apr 05, 2023 |
| Sony          | VGN-CS31MR_P                | [c97f0353d0](https://linux-hardware.org/?probe=c97f0353d0) | Apr 05, 2023 |
| HP            | Victus by Gaming Laptop ... | [6ad0f579b6](https://linux-hardware.org/?probe=6ad0f579b6) | Apr 05, 2023 |
| Fujitsu       | FMVA45MRP2                  | [80b1f5983b](https://linux-hardware.org/?probe=80b1f5983b) | Apr 05, 2023 |
| Acer          | Aspire ES1-572              | [bb95a52e54](https://linux-hardware.org/?probe=bb95a52e54) | Apr 05, 2023 |
| Dell          | Latitude E6440              | [eea06ab302](https://linux-hardware.org/?probe=eea06ab302) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Evolute       | B14HM21                     | [be41163512](https://linux-hardware.org/?probe=be41163512) | Apr 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [a2b079980a](https://linux-hardware.org/?probe=a2b079980a) | Apr 05, 2023 |
| ASUSTek       | UX305UA                     | [5c19e22fe1](https://linux-hardware.org/?probe=5c19e22fe1) | Apr 05, 2023 |
| Acer          | Aspire E5-575               | [ba6c827f8f](https://linux-hardware.org/?probe=ba6c827f8f) | Apr 05, 2023 |
| HP            | Notebook                    | [50c03e608d](https://linux-hardware.org/?probe=50c03e608d) | Apr 05, 2023 |
| Lenovo        | V15-ADA 82C7                | [62dd2f5f34](https://linux-hardware.org/?probe=62dd2f5f34) | Apr 05, 2023 |
| HP            | EliteBook 2530p             | [519d2a4d5a](https://linux-hardware.org/?probe=519d2a4d5a) | Apr 04, 2023 |
| Compumax C... | ONIX-CEL-0001               | [b3e9bc2fb0](https://linux-hardware.org/?probe=b3e9bc2fb0) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [f04b34af52](https://linux-hardware.org/?probe=f04b34af52) | Apr 04, 2023 |
| ASUSTek       | N501VW                      | [1db257af9f](https://linux-hardware.org/?probe=1db257af9f) | Apr 04, 2023 |
| HP            | EliteBook 8470w             | [47e8a4441b](https://linux-hardware.org/?probe=47e8a4441b) | Apr 04, 2023 |
| TPS           | C48P                        | [df8a2ac617](https://linux-hardware.org/?probe=df8a2ac617) | Apr 04, 2023 |
| Apple         | MacBookAir5,2               | [cb94d3ff68](https://linux-hardware.org/?probe=cb94d3ff68) | Apr 04, 2023 |
| eMachines     | D725                        | [f3cdf26e60](https://linux-hardware.org/?probe=f3cdf26e60) | Apr 04, 2023 |
| Dell          | Latitude 7280               | [e0fcb10ef5](https://linux-hardware.org/?probe=e0fcb10ef5) | Apr 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1af0b7675b](https://linux-hardware.org/?probe=1af0b7675b) | Apr 04, 2023 |
| HP            | ProBook 6570b               | [d42564b34f](https://linux-hardware.org/?probe=d42564b34f) | Apr 04, 2023 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [ceeafa59a2](https://linux-hardware.org/?probe=ceeafa59a2) | Apr 04, 2023 |
| Acer          | Aspire ES1-572              | [39e1087c79](https://linux-hardware.org/?probe=39e1087c79) | Apr 04, 2023 |
| Dell          | Studio 1558                 | [e9b75d657d](https://linux-hardware.org/?probe=e9b75d657d) | Apr 04, 2023 |
| Lenovo        | IdeaPad Z585 20152          | [efb4022e4c](https://linux-hardware.org/?probe=efb4022e4c) | Apr 04, 2023 |
| ASUSTek       | S551LB                      | [cd1746937a](https://linux-hardware.org/?probe=cd1746937a) | Apr 04, 2023 |
| Timi          | TM1703                      | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | [473898ff0e](https://linux-hardware.org/?probe=473898ff0e) | Apr 04, 2023 |
| Unknown       | Unknown                     | [7325272558](https://linux-hardware.org/?probe=7325272558) | Apr 04, 2023 |
| ASUSTek       | X200MA                      | [8cfe6c0f97](https://linux-hardware.org/?probe=8cfe6c0f97) | Apr 04, 2023 |
| Acer          | Aspire 4349                 | [43ae04b9c3](https://linux-hardware.org/?probe=43ae04b9c3) | Apr 04, 2023 |
| Lenovo        | B50-80 80LT                 | [163bfb5525](https://linux-hardware.org/?probe=163bfb5525) | Apr 03, 2023 |
| Toshiba       | Satellite L655              | [1381de4b71](https://linux-hardware.org/?probe=1381de4b71) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | [cd18ce0a96](https://linux-hardware.org/?probe=cd18ce0a96) | Apr 03, 2023 |
| Lenovo        | ThinkPad X200 7459J74       | [d7f98c1ddb](https://linux-hardware.org/?probe=d7f98c1ddb) | Apr 03, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [770caf96be](https://linux-hardware.org/?probe=770caf96be) | Apr 03, 2023 |
| Lenovo        | B50-30 80ES                 | [11da2097ba](https://linux-hardware.org/?probe=11da2097ba) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7f3280e60](https://linux-hardware.org/?probe=d7f3280e60) | Apr 03, 2023 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [49b1cef736](https://linux-hardware.org/?probe=49b1cef736) | Apr 03, 2023 |
| Acer          | Aspire A515-51              | [c9245a7032](https://linux-hardware.org/?probe=c9245a7032) | Apr 03, 2023 |
| Dell          | Inspiron 3542               | [bcf9cf6ba6](https://linux-hardware.org/?probe=bcf9cf6ba6) | Apr 03, 2023 |
| HP            | EliteBook Folio G1          | [ad873ac967](https://linux-hardware.org/?probe=ad873ac967) | Apr 03, 2023 |
| Dell          | Latitude 7480               | [f1ca485181](https://linux-hardware.org/?probe=f1ca485181) | Apr 02, 2023 |
| ASUSTek       | UX303UB                     | [9b46784fd5](https://linux-hardware.org/?probe=9b46784fd5) | Apr 02, 2023 |
| HP            | Laptop 17-ca0xxx            | [6399f19b22](https://linux-hardware.org/?probe=6399f19b22) | Apr 02, 2023 |
| HP            | OMEN by Laptop              | [647c427d7b](https://linux-hardware.org/?probe=647c427d7b) | Apr 02, 2023 |
| HP            | Laptop 14-cm0xxx            | [984d71ee3d](https://linux-hardware.org/?probe=984d71ee3d) | Apr 02, 2023 |
| ASUSTek       | G71V                        | [6594dac071](https://linux-hardware.org/?probe=6594dac071) | Apr 02, 2023 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [3ec9fed32b](https://linux-hardware.org/?probe=3ec9fed32b) | Apr 02, 2023 |
| ASUSTek       | N53SV                       | [5b2c0ea506](https://linux-hardware.org/?probe=5b2c0ea506) | Apr 02, 2023 |
| HP            | Laptop 15q-ds0xxx           | [42bd53a04e](https://linux-hardware.org/?probe=42bd53a04e) | Apr 02, 2023 |
| ASUSTek       | X555LAB                     | [95f5025351](https://linux-hardware.org/?probe=95f5025351) | Apr 02, 2023 |
| AZW           | Speed S                     | [52292a4968](https://linux-hardware.org/?probe=52292a4968) | Apr 02, 2023 |
| PCSMART S.... | PNTGOB11CPE                 | [874d355cc4](https://linux-hardware.org/?probe=874d355cc4) | Apr 02, 2023 |
| Dell          | Latitude E5400              | [4b69d7d67c](https://linux-hardware.org/?probe=4b69d7d67c) | Apr 02, 2023 |
| ASUSTek       | G750JW                      | [b7c8d9cc5f](https://linux-hardware.org/?probe=b7c8d9cc5f) | Apr 01, 2023 |
| Dell          | System XPS L502X            | [2ed08c70a9](https://linux-hardware.org/?probe=2ed08c70a9) | Apr 01, 2023 |
| HP            | ProBook 455 G1              | [869f36fc4c](https://linux-hardware.org/?probe=869f36fc4c) | Apr 01, 2023 |
| Dell          | Latitude 5511               | [86b4fcff61](https://linux-hardware.org/?probe=86b4fcff61) | Apr 01, 2023 |
| Dell          | Latitude E7470              | [3eb8069059](https://linux-hardware.org/?probe=3eb8069059) | Apr 01, 2023 |
| Acer          | Aspire A515-41G             | [f047e9361c](https://linux-hardware.org/?probe=f047e9361c) | Apr 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [eb7bbd9b91](https://linux-hardware.org/?probe=eb7bbd9b91) | Apr 01, 2023 |
| Notebook      | W54BL                       | [5e3ba9b128](https://linux-hardware.org/?probe=5e3ba9b128) | Apr 01, 2023 |
| Toshiba       | dynabook T653/46JR          | [7f0e2d07b5](https://linux-hardware.org/?probe=7f0e2d07b5) | Apr 01, 2023 |
| Acer          | Aspire A715-41G             | [cea0d2797d](https://linux-hardware.org/?probe=cea0d2797d) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [b0beffe006](https://linux-hardware.org/?probe=b0beffe006) | Apr 01, 2023 |
| Dell          | Inspiron 15 5510            | [e169cd0886](https://linux-hardware.org/?probe=e169cd0886) | Apr 01, 2023 |
| HP            | Pavilion g7                 | [7820d2ca67](https://linux-hardware.org/?probe=7820d2ca67) | Apr 01, 2023 |
| Acer          | Aspire V5-121               | [d6cc7a67ab](https://linux-hardware.org/?probe=d6cc7a67ab) | Apr 01, 2023 |
| Acer          | Aspire 5740                 | [eeba9d18fa](https://linux-hardware.org/?probe=eeba9d18fa) | Apr 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [96c53eccb0](https://linux-hardware.org/?probe=96c53eccb0) | Apr 01, 2023 |
| Acer          | Aspire A315-35              | [659a4cfd5a](https://linux-hardware.org/?probe=659a4cfd5a) | Apr 01, 2023 |
| ASUSTek       | N752VX                      | [d426499408](https://linux-hardware.org/?probe=d426499408) | Apr 01, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6ab0a0226d](https://linux-hardware.org/?probe=6ab0a0226d) | Apr 01, 2023 |
| Unknown       | X133                        | [950572f119](https://linux-hardware.org/?probe=950572f119) | Apr 01, 2023 |
| ASUSTek       | F3JP                        | [e561213582](https://linux-hardware.org/?probe=e561213582) | Apr 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [87bc2601f3](https://linux-hardware.org/?probe=87bc2601f3) | Apr 01, 2023 |
| ASUSTek       | S551LN                      | [916adbdf9f](https://linux-hardware.org/?probe=916adbdf9f) | Apr 01, 2023 |
| Sony          | VPCEH1S1R                   | [12100cdd4b](https://linux-hardware.org/?probe=12100cdd4b) | Apr 01, 2023 |
| Lenovo        | G505 20240                  | [d873632b2b](https://linux-hardware.org/?probe=d873632b2b) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [70fb59cd4f](https://linux-hardware.org/?probe=70fb59cd4f) | Apr 01, 2023 |
| HP            | EliteBook 8470p             | [178ccc8d4d](https://linux-hardware.org/?probe=178ccc8d4d) | Apr 01, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [9db0830268](https://linux-hardware.org/?probe=9db0830268) | Apr 01, 2023 |
| Lenovo        | G560 20042                  | [c5a4783dfb](https://linux-hardware.org/?probe=c5a4783dfb) | Apr 01, 2023 |
| Toshiba       | Satellite C55-B             | [250e5371c1](https://linux-hardware.org/?probe=250e5371c1) | Apr 01, 2023 |
| Lenovo        | ThinkPad X230 2325DV4       | [6cff5cd5d1](https://linux-hardware.org/?probe=6cff5cd5d1) | Apr 01, 2023 |
| Dell          | Latitude 5580               | [10cbd4c04d](https://linux-hardware.org/?probe=10cbd4c04d) | Apr 01, 2023 |
| Fujitsu       | LIFEBOOK S935               | [11b63a22b5](https://linux-hardware.org/?probe=11b63a22b5) | Apr 01, 2023 |
| Sony          | VPCEA3BFX                   | [6215c985dd](https://linux-hardware.org/?probe=6215c985dd) | Apr 01, 2023 |
| Lenovo        | V15-IGL 82C3                | [4773b9449c](https://linux-hardware.org/?probe=4773b9449c) | Apr 01, 2023 |
| Dell          | Vostro 15 3515              | [eea311b1bb](https://linux-hardware.org/?probe=eea311b1bb) | Apr 01, 2023 |
| HP            | Laptop 15s-eq3xxx           | [758bb2556e](https://linux-hardware.org/?probe=758bb2556e) | Apr 01, 2023 |
| Lenovo        | ThinkPad T530 23594LU       | [9de89fee19](https://linux-hardware.org/?probe=9de89fee19) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420s 4173R44      | [84e9a5f3d9](https://linux-hardware.org/?probe=84e9a5f3d9) | Apr 01, 2023 |
| UMAX          | VisionBook 14Wa Plus        | [ea8016c4a5](https://linux-hardware.org/?probe=ea8016c4a5) | Apr 01, 2023 |
| Dell          | Latitude E7450              | [8bf693a890](https://linux-hardware.org/?probe=8bf693a890) | Apr 01, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [93ef0bb287](https://linux-hardware.org/?probe=93ef0bb287) | Apr 01, 2023 |
| Samsung       | 270E5G/270E5U               | [67b91e463a](https://linux-hardware.org/?probe=67b91e463a) | Mar 31, 2023 |
| Acer          | Aspire A315-54K             | [d325177071](https://linux-hardware.org/?probe=d325177071) | Mar 31, 2023 |
| HP            | ProBook 440 G6              | [5198509903](https://linux-hardware.org/?probe=5198509903) | Mar 31, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [66a1075056](https://linux-hardware.org/?probe=66a1075056) | Mar 31, 2023 |
| Quanta        | QL3 TBD                     | [21673aecac](https://linux-hardware.org/?probe=21673aecac) | Mar 31, 2023 |
| HP            | Compaq Presario CQ60        | [e5a729243d](https://linux-hardware.org/?probe=e5a729243d) | Mar 31, 2023 |
| Microtech     | ebookPro                    | [ffe1da27cc](https://linux-hardware.org/?probe=ffe1da27cc) | Mar 31, 2023 |
| Intel         | Kabylake Platform           | [2b0fd79264](https://linux-hardware.org/?probe=2b0fd79264) | Mar 31, 2023 |
| Toshiba       | Satellite L655              | [d527726a1c](https://linux-hardware.org/?probe=d527726a1c) | Mar 31, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [59b2b4e152](https://linux-hardware.org/?probe=59b2b4e152) | Mar 31, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [ad92e27c90](https://linux-hardware.org/?probe=ad92e27c90) | Mar 31, 2023 |
| Acer          | Aspire 7720                 | [073d49ce6b](https://linux-hardware.org/?probe=073d49ce6b) | Mar 31, 2023 |
| Dell          | Precision 5570              | [a3d5f928ee](https://linux-hardware.org/?probe=a3d5f928ee) | Mar 31, 2023 |
| Dell          | Latitude E7440              | [fdd9fda693](https://linux-hardware.org/?probe=fdd9fda693) | Mar 31, 2023 |
| HP            | Compaq 6730b (GB987ET#UU... | [6c6ceb9bc3](https://linux-hardware.org/?probe=6c6ceb9bc3) | Mar 31, 2023 |
| HP            | 250 G5 Notebook PC          | [d271318192](https://linux-hardware.org/?probe=d271318192) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2347EP7       | [6fd7423cb6](https://linux-hardware.org/?probe=6fd7423cb6) | Mar 31, 2023 |
| HP            | Pavilion 15                 | [4dc2c9dfc1](https://linux-hardware.org/?probe=4dc2c9dfc1) | Mar 31, 2023 |
| HUAWEI        | KPL-W0X                     | [6e93ca4159](https://linux-hardware.org/?probe=6e93ca4159) | Mar 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [29c4ba04a1](https://linux-hardware.org/?probe=29c4ba04a1) | Mar 31, 2023 |
| Acer          | Aspire ES1-531              | [aedba72f70](https://linux-hardware.org/?probe=aedba72f70) | Mar 31, 2023 |
| Unknown       | Unknown                     | [c30740a3eb](https://linux-hardware.org/?probe=c30740a3eb) | Mar 31, 2023 |
| HP            | Laptop 17-cp2xxx            | [854de8a433](https://linux-hardware.org/?probe=854de8a433) | Mar 31, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [d6c537b33b](https://linux-hardware.org/?probe=d6c537b33b) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | [8c60cf0ec1](https://linux-hardware.org/?probe=8c60cf0ec1) | Mar 31, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [54f8c5082d](https://linux-hardware.org/?probe=54f8c5082d) | Mar 31, 2023 |
| Acer          | Aspire 1410                 | [58be80ea51](https://linux-hardware.org/?probe=58be80ea51) | Mar 31, 2023 |
| Acer          | Aspire 5720Z                | [ca2b750eeb](https://linux-hardware.org/?probe=ca2b750eeb) | Mar 31, 2023 |
| Acer          | TravelMate B311-31          | [3345b754b7](https://linux-hardware.org/?probe=3345b754b7) | Mar 31, 2023 |
| HP            | EliteBook 8540p             | [570836875c](https://linux-hardware.org/?probe=570836875c) | Mar 31, 2023 |
| Notebook      | NL40_50GU                   | [a46afd7246](https://linux-hardware.org/?probe=a46afd7246) | Mar 31, 2023 |
| Star Labs     | Lite                        | [e3689ef845](https://linux-hardware.org/?probe=e3689ef845) | Mar 31, 2023 |
| Acer          | Aspire 7741                 | [34bd6f42b1](https://linux-hardware.org/?probe=34bd6f42b1) | Mar 30, 2023 |
| HP            | Unknown                     | [fb784430a5](https://linux-hardware.org/?probe=fb784430a5) | Mar 30, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [225e13e1f0](https://linux-hardware.org/?probe=225e13e1f0) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8e927ead89](https://linux-hardware.org/?probe=8e927ead89) | Mar 30, 2023 |
| Toshiba       | Satellite P875              | [aba8c03541](https://linux-hardware.org/?probe=aba8c03541) | Mar 30, 2023 |
| ASUSTek       | K53SJ                       | [aa9a729217](https://linux-hardware.org/?probe=aa9a729217) | Mar 30, 2023 |
| Notebook      | N150CU                      | [5da0df2cf0](https://linux-hardware.org/?probe=5da0df2cf0) | Mar 30, 2023 |
| Acer          | Aspire ES1-523              | [a800dab0ab](https://linux-hardware.org/?probe=a800dab0ab) | Mar 30, 2023 |
| HP            | EliteBook 2540p             | [6aae8ca2a0](https://linux-hardware.org/?probe=6aae8ca2a0) | Mar 30, 2023 |
| Dell          | XPS 17 9710                 | [6b37881138](https://linux-hardware.org/?probe=6b37881138) | Mar 30, 2023 |
| HP            | ProBook 6360b               | [cf027e03de](https://linux-hardware.org/?probe=cf027e03de) | Mar 30, 2023 |
| Acer          | Prespa M                    | [a6541a27d9](https://linux-hardware.org/?probe=a6541a27d9) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [afd41155ee](https://linux-hardware.org/?probe=afd41155ee) | Mar 30, 2023 |
| Lenovo        | G550 2958                   | [41f23ded68](https://linux-hardware.org/?probe=41f23ded68) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a1fa08efc6](https://linux-hardware.org/?probe=a1fa08efc6) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [45f39402f0](https://linux-hardware.org/?probe=45f39402f0) | Mar 30, 2023 |
| Lenovo        | V15-ADA 82C7                | [552ad08e05](https://linux-hardware.org/?probe=552ad08e05) | Mar 30, 2023 |
| Dell          | Latitude E7450              | [63e8748d1f](https://linux-hardware.org/?probe=63e8748d1f) | Mar 30, 2023 |
| PC Special... | P65_67RSRP                  | [889f3e8521](https://linux-hardware.org/?probe=889f3e8521) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [d3eafe4568](https://linux-hardware.org/?probe=d3eafe4568) | Mar 30, 2023 |
| Toshiba       | Satellite L655              | [2e6ea8bf5c](https://linux-hardware.org/?probe=2e6ea8bf5c) | Mar 30, 2023 |
| Acer          | NC-M3-581T-33216G52MAKK     | [3f394d8b43](https://linux-hardware.org/?probe=3f394d8b43) | Mar 30, 2023 |
| Dell          | Latitude E6430              | [086b5d0f79](https://linux-hardware.org/?probe=086b5d0f79) | Mar 30, 2023 |
| Lenovo        | ThinkPad T400 6475J92       | [1d3c812668](https://linux-hardware.org/?probe=1d3c812668) | Mar 30, 2023 |
| Lenovo        | ThinkPad X395 20NLS0J400    | [e9d9710ef9](https://linux-hardware.org/?probe=e9d9710ef9) | Mar 30, 2023 |
| Dell          | Precision 5550              | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| HP            | Notebook                    | [e631e8e62a](https://linux-hardware.org/?probe=e631e8e62a) | Mar 29, 2023 |
| HP            | Laptop 14-bs0xx             | [53504486d2](https://linux-hardware.org/?probe=53504486d2) | Mar 29, 2023 |
| Lenovo        | U41-70 80JV                 | [975da67142](https://linux-hardware.org/?probe=975da67142) | Mar 29, 2023 |
| HP            | Laptop 15s-fq4xxx           | [029fa06a9a](https://linux-hardware.org/?probe=029fa06a9a) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK A555               | [6f28f9e6ec](https://linux-hardware.org/?probe=6f28f9e6ec) | Mar 29, 2023 |
| Acer          | Aspire A515-57              | [06a3c07a40](https://linux-hardware.org/?probe=06a3c07a40) | Mar 29, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [5be11a9a6e](https://linux-hardware.org/?probe=5be11a9a6e) | Mar 29, 2023 |
| Dell          | System Inspiron N7110       | [cc23cb7065](https://linux-hardware.org/?probe=cc23cb7065) | Mar 29, 2023 |
| Samsung       | 670Z5E                      | [2bf528dfb1](https://linux-hardware.org/?probe=2bf528dfb1) | Mar 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [695a074faf](https://linux-hardware.org/?probe=695a074faf) | Mar 29, 2023 |
| Lenovo        | G570 20079                  | [680c7a04ed](https://linux-hardware.org/?probe=680c7a04ed) | Mar 29, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [61ede0b764](https://linux-hardware.org/?probe=61ede0b764) | Mar 29, 2023 |
| Acer          | Aspire E1-571G              | [574f00dff5](https://linux-hardware.org/?probe=574f00dff5) | Mar 29, 2023 |
| Acer          | Aspire E5-576               | [37fc62a287](https://linux-hardware.org/?probe=37fc62a287) | Mar 29, 2023 |
| Acer          | Aspire E5-773G              | [3cb72ca21c](https://linux-hardware.org/?probe=3cb72ca21c) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fa1a582da6](https://linux-hardware.org/?probe=fa1a582da6) | Mar 29, 2023 |
| Notebook      | NL40_50CU                   | [fe471635fb](https://linux-hardware.org/?probe=fe471635fb) | Mar 29, 2023 |
| Dell          | Vostro 5568                 | [0004be15a4](https://linux-hardware.org/?probe=0004be15a4) | Mar 28, 2023 |
| HP            | ENVY Notebook               | [98cd32ea44](https://linux-hardware.org/?probe=98cd32ea44) | Mar 28, 2023 |
| HP            | 250 G6 Notebook PC          | [94cdfc44d1](https://linux-hardware.org/?probe=94cdfc44d1) | Mar 28, 2023 |
| Acer          | Aspire V3-571G              | [ecde786683](https://linux-hardware.org/?probe=ecde786683) | Mar 28, 2023 |
| HP            | Compaq 6510b (GR680ET)      | [716c4212c7](https://linux-hardware.org/?probe=716c4212c7) | Mar 28, 2023 |
| Lenovo        | V145-15AST 81MT             | [7fff3bb217](https://linux-hardware.org/?probe=7fff3bb217) | Mar 28, 2023 |
| Kiano         | Elegance 14.2               | [ea2013b347](https://linux-hardware.org/?probe=ea2013b347) | Mar 28, 2023 |
| Acer          | Aspire E1-570               | [71b25255fa](https://linux-hardware.org/?probe=71b25255fa) | Mar 28, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [f44d26ed76](https://linux-hardware.org/?probe=f44d26ed76) | Mar 28, 2023 |
| Acer          | Aspire E5-532G              | [35e076d9b5](https://linux-hardware.org/?probe=35e076d9b5) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK E556               | [bbd878e897](https://linux-hardware.org/?probe=bbd878e897) | Mar 28, 2023 |
| Dell          | Vostro 14-5480              | [b1ef6303a6](https://linux-hardware.org/?probe=b1ef6303a6) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK E556               | [3842c12714](https://linux-hardware.org/?probe=3842c12714) | Mar 28, 2023 |
| HP            | Pavilion Notebook           | [783330690d](https://linux-hardware.org/?probe=783330690d) | Mar 28, 2023 |
| Dell          | Latitude E5500              | [6fea10bf98](https://linux-hardware.org/?probe=6fea10bf98) | Mar 28, 2023 |
| TEKNOSERVI... | NJ5x_NJ7xLU                 | [2a0feae3f9](https://linux-hardware.org/?probe=2a0feae3f9) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Dell          | Latitude 7490               | [41d01ead49](https://linux-hardware.org/?probe=41d01ead49) | Mar 28, 2023 |
| Dell          | Latitude E5570              | [5b3d1ab8b9](https://linux-hardware.org/?probe=5b3d1ab8b9) | Mar 28, 2023 |
| Dell          | Inspiron 3558               | [c80d4c15ce](https://linux-hardware.org/?probe=c80d4c15ce) | Mar 28, 2023 |
| Dell          | Inspiron 5515               | [13a0d1426d](https://linux-hardware.org/?probe=13a0d1426d) | Mar 28, 2023 |
| Lenovo        | ThinkPad W520 4284E79       | [2d9875ca24](https://linux-hardware.org/?probe=2d9875ca24) | Mar 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [df27b06a95](https://linux-hardware.org/?probe=df27b06a95) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f511f8bcb1](https://linux-hardware.org/?probe=f511f8bcb1) | Mar 28, 2023 |
| ASUSTek       | X555DG                      | [6a464d8e68](https://linux-hardware.org/?probe=6a464d8e68) | Mar 27, 2023 |
| Acer          | Aspire E5-575               | [5964caaa02](https://linux-hardware.org/?probe=5964caaa02) | Mar 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS47P00    | [e287203572](https://linux-hardware.org/?probe=e287203572) | Mar 27, 2023 |
| Lenovo        | ThinkPad X220 42915P1       | [40d0cf6e14](https://linux-hardware.org/?probe=40d0cf6e14) | Mar 27, 2023 |
| Lenovo        | ThinkPad T420 4236W1K       | [e093aace6e](https://linux-hardware.org/?probe=e093aace6e) | Mar 27, 2023 |
| Dell          | Latitude E6430              | [61ec1b65ed](https://linux-hardware.org/?probe=61ec1b65ed) | Mar 27, 2023 |
| Sony          | VPCSA2C5E                   | [60e85a64b0](https://linux-hardware.org/?probe=60e85a64b0) | Mar 27, 2023 |
| ASUSTek       | K56CA                       | [43f064cb46](https://linux-hardware.org/?probe=43f064cb46) | Mar 27, 2023 |
| Acer          | Aspire A515-45              | [d480257689](https://linux-hardware.org/?probe=d480257689) | Mar 27, 2023 |
| Lenovo        | ThinkPad T580 20LAS4L216    | [9c3464baf9](https://linux-hardware.org/?probe=9c3464baf9) | Mar 27, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [580e3a1237](https://linux-hardware.org/?probe=580e3a1237) | Mar 27, 2023 |
| Acer          | Mammoth                     | [d43ab9891b](https://linux-hardware.org/?probe=d43ab9891b) | Mar 27, 2023 |
| Lenovo        | ThinkPad L450 20DS0001GE    | [17f869b10d](https://linux-hardware.org/?probe=17f869b10d) | Mar 27, 2023 |
| Sony          | VPCEH1S1E                   | [081294b14c](https://linux-hardware.org/?probe=081294b14c) | Mar 27, 2023 |
| Lenovo        | ThinkPad T450s 20BWS3WY0... | [d1e9fcddfc](https://linux-hardware.org/?probe=d1e9fcddfc) | Mar 27, 2023 |
| TUXEDO        | Pulse 14 Gen1               | [7facc52f0e](https://linux-hardware.org/?probe=7facc52f0e) | Mar 27, 2023 |
| HP            | 250 G6 Notebook PC          | [eb82e949b2](https://linux-hardware.org/?probe=eb82e949b2) | Mar 27, 2023 |
| ASUSTek       | K54HR                       | [ac6cf948d5](https://linux-hardware.org/?probe=ac6cf948d5) | Mar 27, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e4a88fa14e](https://linux-hardware.org/?probe=e4a88fa14e) | Mar 27, 2023 |
| Lenovo        | B460e                       | [1c79a13a61](https://linux-hardware.org/?probe=1c79a13a61) | Mar 27, 2023 |
| Acer          | Aspire A315-56              | [db607e02ea](https://linux-hardware.org/?probe=db607e02ea) | Mar 27, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [84d2bfb9cc](https://linux-hardware.org/?probe=84d2bfb9cc) | Mar 27, 2023 |
| Dell          | Inspiron 5448               | [b800b24cbd](https://linux-hardware.org/?probe=b800b24cbd) | Mar 27, 2023 |
| Acer          | Aspire V3-551               | [48409a7222](https://linux-hardware.org/?probe=48409a7222) | Mar 27, 2023 |
| Dell          | Latitude 7490               | [58ccd5d7e0](https://linux-hardware.org/?probe=58ccd5d7e0) | Mar 27, 2023 |
| HP            | Pavilion g6                 | [4b08001481](https://linux-hardware.org/?probe=4b08001481) | Mar 27, 2023 |
| Dell          | Inspiron 3537               | [5b1971e361](https://linux-hardware.org/?probe=5b1971e361) | Mar 27, 2023 |
| Acer          | Aspire A515-41G             | [33bccb2234](https://linux-hardware.org/?probe=33bccb2234) | Mar 27, 2023 |
| Sony          | VJFE52A0711H                | [f2186a4bc4](https://linux-hardware.org/?probe=f2186a4bc4) | Mar 27, 2023 |
| Lenovo        | ThinkPad L530 24812SG       | [163d4e376e](https://linux-hardware.org/?probe=163d4e376e) | Mar 26, 2023 |
| ASUSTek       | N552VW                      | [322426698a](https://linux-hardware.org/?probe=322426698a) | Mar 26, 2023 |
| Dell          | XPS 15 9520                 | [35718792af](https://linux-hardware.org/?probe=35718792af) | Mar 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [7dbe4350b5](https://linux-hardware.org/?probe=7dbe4350b5) | Mar 26, 2023 |
| Acer          | Aspire E1-431               | [f56a2c21cf](https://linux-hardware.org/?probe=f56a2c21cf) | Mar 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [84af25ca8c](https://linux-hardware.org/?probe=84af25ca8c) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E744               | [f32cce4c6f](https://linux-hardware.org/?probe=f32cce4c6f) | Mar 26, 2023 |
| Lenovo        | ThinkPad X220 4290LR3       | [dffa03da18](https://linux-hardware.org/?probe=dffa03da18) | Mar 26, 2023 |
| Gigabyte      | A7 K1                       | [0eca943d2e](https://linux-hardware.org/?probe=0eca943d2e) | Mar 26, 2023 |
| Acer          | Aspire 5820                 | [3e0e45bc17](https://linux-hardware.org/?probe=3e0e45bc17) | Mar 26, 2023 |
| Dell          | Inspiron 3576               | [18352c181a](https://linux-hardware.org/?probe=18352c181a) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [51d034c8d1](https://linux-hardware.org/?probe=51d034c8d1) | Mar 25, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [1c88428088](https://linux-hardware.org/?probe=1c88428088) | Mar 22, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [b6b5eb415f](https://linux-hardware.org/?probe=b6b5eb415f) | Mar 21, 2023 |
| Acer          | TravelMate 5760             | [712e36569d](https://linux-hardware.org/?probe=712e36569d) | Mar 20, 2023 |
| Acer          | Swift SF113-31              | [f1db5ada96](https://linux-hardware.org/?probe=f1db5ada96) | Mar 18, 2023 |
| Dell          | Latitude D530               | [c02081557b](https://linux-hardware.org/?probe=c02081557b) | Mar 18, 2023 |
| Dell          | Latitude E7470              | [f2dd0afe92](https://linux-hardware.org/?probe=f2dd0afe92) | Mar 17, 2023 |
| Toshiba       | Satellite C55-A-1T6         | [71751e4045](https://linux-hardware.org/?probe=71751e4045) | Mar 16, 2023 |
| HP            | ZBook 15 G5                 | [2af12bdf73](https://linux-hardware.org/?probe=2af12bdf73) | Mar 16, 2023 |
| Lenovo        | G400s 20244                 | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Inspiron 15-3567            | [97504eea44](https://linux-hardware.org/?probe=97504eea44) | Mar 13, 2023 |
| HONOR         | HYM-WXX                     | [366d00f0a7](https://linux-hardware.org/?probe=366d00f0a7) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0d7e6b4a80](https://linux-hardware.org/?probe=0d7e6b4a80) | Mar 12, 2023 |
| Unknown       | Unknown                     | [d1336c09a0](https://linux-hardware.org/?probe=d1336c09a0) | Mar 11, 2023 |
| ASUSTek       | X556UQK                     | [e5c898a856](https://linux-hardware.org/?probe=e5c898a856) | Mar 11, 2023 |
| Kiano         | Elegance 14.2               | [5714b30108](https://linux-hardware.org/?probe=5714b30108) | Mar 11, 2023 |
| Dell          | Latitude E5450              | [6a40dced5b](https://linux-hardware.org/?probe=6a40dced5b) | Mar 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6e7ffbd8ad](https://linux-hardware.org/?probe=6e7ffbd8ad) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d677609a51](https://linux-hardware.org/?probe=d677609a51) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [efe5bcec0b](https://linux-hardware.org/?probe=efe5bcec0b) | Mar 07, 2023 |
| GPU Compan... | GWTN156-11                  | [c451be28c3](https://linux-hardware.org/?probe=c451be28c3) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [67d9219fc2](https://linux-hardware.org/?probe=67d9219fc2) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [c517071efd](https://linux-hardware.org/?probe=c517071efd) | Mar 06, 2023 |
| HP            | Notebook                    | [06e805be3d](https://linux-hardware.org/?probe=06e805be3d) | Mar 06, 2023 |
| HP            | Compaq Presario CQ60        | [cbdc8bcd6a](https://linux-hardware.org/?probe=cbdc8bcd6a) | Mar 06, 2023 |
| Dell          | Inspiron 5567               | [780dc15bcc](https://linux-hardware.org/?probe=780dc15bcc) | Mar 06, 2023 |
| GPU Compan... | GWTN156-11                  | [fe4af91506](https://linux-hardware.org/?probe=fe4af91506) | Mar 06, 2023 |
| Lenovo        | ThinkPad T550 20CJS02E00    | [d8535715f8](https://linux-hardware.org/?probe=d8535715f8) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7e0a15042f](https://linux-hardware.org/?probe=7e0a15042f) | Mar 05, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9186971572](https://linux-hardware.org/?probe=9186971572) | Mar 03, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_23.03/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.2.6-desktop-1omv2390   | 701       | 95.63%  |
| 6.2.2-desktop-1omv2390   | 20        | 2.73%   |
| 6.1.1-desktop-1omv2290   | 4         | 0.55%   |
| 6.1.4-desktop-1omv2301   | 2         | 0.27%   |
| 5.16.13-desktop-1omv4003 | 2         | 0.27%   |
| 6.2.8-desktop-1omv2390   | 1         | 0.14%   |
| 6.2.7-desktop-1omv2390   | 1         | 0.14%   |
| 6.2.1-desktop-1omv2390   | 1         | 0.14%   |
| 6.1.22-xanmod1           | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.6   | 701       | 95.63%  |
| 6.2.2   | 20        | 2.73%   |
| 6.1.1   | 4         | 0.55%   |
| 6.1.4   | 2         | 0.27%   |
| 5.16.13 | 2         | 0.27%   |
| 6.2.8   | 1         | 0.14%   |
| 6.2.7   | 1         | 0.14%   |
| 6.2.1   | 1         | 0.14%   |
| 6.1.22  | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 724       | 98.77%  |
| 6.1     | 7         | 0.95%   |
| 5.16    | 2         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 733       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 627       | 85.54%  |
| GNOME    | 52        | 7.09%   |
| LXQt     | 46        | 6.28%   |
| Cinnamon | 3         | 0.41%   |
| XFCE     | 2         | 0.27%   |
| Unknown  | 2         | 0.27%   |
| Budgie   | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 684       | 93.32%  |
| Wayland | 49        | 6.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 679       | 92.63%  |
| GDM     | 52        | 7.09%   |
| LightDM | 2         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 338       | 46.11%  |
| de_DE | 61        | 8.32%   |
| fr_FR | 47        | 6.41%   |
| pl_PL | 34        | 4.64%   |
| en_GB | 34        | 4.64%   |
| ru_RU | 33        | 4.5%    |
| it_IT | 33        | 4.5%    |
| pt_BR | 19        | 2.59%   |
| es_MX | 18        | 2.46%   |
| es_ES | 14        | 1.91%   |
| en_AU | 10        | 1.36%   |
| en_CA | 9         | 1.23%   |
| cs_CZ | 8         | 1.09%   |
| hu_HU | 7         | 0.95%   |
| da_DK | 6         | 0.82%   |
| nl_NL | 5         | 0.68%   |
| en_IN | 5         | 0.68%   |
| tr_TR | 4         | 0.55%   |
| pt_PT | 4         | 0.55%   |
| es_PE | 4         | 0.55%   |
| es_AR | 4         | 0.55%   |
| fr_CH | 3         | 0.41%   |
| fr_BE | 3         | 0.41%   |
| en_NZ | 3         | 0.41%   |
| de_CH | 3         | 0.41%   |
| UTF-8 | 2         | 0.27%   |
| nl_BE | 2         | 0.27%   |
| ja_JP | 2         | 0.27%   |
| es_CL | 2         | 0.27%   |
| en_ZA | 2         | 0.27%   |
| en_AG | 2         | 0.27%   |
| C     | 2         | 0.27%   |
| id_ID | 1         | 0.14%   |
| fr_CA | 1         | 0.14%   |
| es_VE | 1         | 0.14%   |
| es_UY | 1         | 0.14%   |
| es_CO | 1         | 0.14%   |
| en_PH | 1         | 0.14%   |
| en_DK | 1         | 0.14%   |
| de_AT | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 462       | 63.03%  |
| BIOS | 271       | 36.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 370       | 50.48%  |
| Overlay | 296       | 40.38%  |
| Btrfs   | 52        | 7.09%   |
| Xfs     | 8         | 1.09%   |
| F2fs    | 7         | 0.95%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 589       | 80.35%  |
| MBR  | 144       | 19.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 421       | 57.44%  |
| Yes       | 312       | 42.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 474       | 64.67%  |
| Yes       | 259       | 35.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 163       | 22.24%  |
| Hewlett-Packard     | 128       | 17.46%  |
| Dell                | 99        | 13.51%  |
| ASUSTek Computer    | 80        | 10.91%  |
| Acer                | 76        | 10.37%  |
| Toshiba             | 35        | 4.77%   |
| Samsung Electronics | 18        | 2.46%   |
| Fujitsu             | 14        | 1.91%   |
| Sony                | 13        | 1.77%   |
| Apple               | 13        | 1.77%   |
| MSI                 | 9         | 1.23%   |
| Notebook            | 7         | 0.95%   |
| HUAWEI              | 5         | 0.68%   |
| Unknown             | 5         | 0.68%   |
| TUXEDO              | 4         | 0.55%   |
| GPU Company         | 4         | 0.55%   |
| Chuwi               | 4         | 0.55%   |
| Timi                | 3         | 0.41%   |
| Medion              | 3         | 0.41%   |
| Kiano               | 3         | 0.41%   |
| Google              | 3         | 0.41%   |
| Positivo            | 2         | 0.27%   |
| Packard Bell        | 2         | 0.27%   |
| lapbook             | 2         | 0.27%   |
| Gigabyte Technology | 2         | 0.27%   |
| Fujitsu Siemens     | 2         | 0.27%   |
| eMachines           | 2         | 0.27%   |
| Wortmann AG         | 1         | 0.14%   |
| VIT                 | 1         | 0.14%   |
| Valve               | 1         | 0.14%   |
| UMAX                | 1         | 0.14%   |
| TPS                 | 1         | 0.14%   |
| TEKNOSERVICE        | 1         | 0.14%   |
| System76            | 1         | 0.14%   |
| Star Labs           | 1         | 0.14%   |
| Standard            | 1         | 0.14%   |
| SLIMBOOK            | 1         | 0.14%   |
| Razer               | 1         | 0.14%   |
| Quanta              | 1         | 0.14%   |
| Philco              | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP Notebook                                 | 7         | 0.95%   |
| Unknown                                     | 7         | 0.95%   |
| ASUS S551LN                                 | 6         | 0.82%   |
| Lenovo IdeaPad 1 14ADA05 82GW               | 5         | 0.68%   |
| Toshiba Satellite L655                      | 4         | 0.55%   |
| Samsung 950XCJ/951XCJ/950XCR                | 4         | 0.55%   |
| Lenovo V15-ADA 82C7                         | 4         | 0.55%   |
| HP 250 G6 Notebook PC                       | 4         | 0.55%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)          | 3         | 0.41%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS | 3         | 0.41%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3001LUK        | 3         | 0.41%   |
| Lenovo IdeaPad S145-15AST 81N3              | 3         | 0.41%   |
| Lenovo IdeaPad 3 15ALC6 82KU                | 3         | 0.41%   |
| Lenovo G50-70 20351                         | 3         | 0.41%   |
| Kiano Elegance 14.2                         | 3         | 0.41%   |
| HP Pavilion Notebook                        | 3         | 0.41%   |
| HP Laptop 15s-eq2xxx                        | 3         | 0.41%   |
| HP EliteBook 2530p                          | 3         | 0.41%   |
| HP 255 G8 Notebook PC                       | 3         | 0.41%   |
| Fujitsu LIFEBOOK S935                       | 3         | 0.41%   |
| Dell Latitude E6440                         | 3         | 0.41%   |
| Dell Latitude 7490                          | 3         | 0.41%   |
| Dell Inspiron 1720                          | 3         | 0.41%   |
| Dell Inspiron 15-3567                       | 3         | 0.41%   |
| Apple MacBookPro9,2                         | 3         | 0.41%   |
| Apple MacBookPro8,1                         | 3         | 0.41%   |
| Toshiba Satellite L350D                     | 2         | 0.27%   |
| Toshiba Satellite L300D                     | 2         | 0.27%   |
| Toshiba Satellite C660                      | 2         | 0.27%   |
| MSI Modern 14 B10MW                         | 2         | 0.27%   |
| Lenovo V15-IGL 82C3                         | 2         | 0.27%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK       | 2         | 0.27%   |
| Lenovo IdeaPad 330S-15IKB 81F5              | 2         | 0.27%   |
| Lenovo IdeaPad 3 15ITL6 82H8                | 2         | 0.27%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 2         | 0.27%   |
| Lenovo G550 2958                            | 2         | 0.27%   |
| Lenovo G505 20240                           | 2         | 0.27%   |
| Lenovo G50-30 80G0                          | 2         | 0.27%   |
| lapbook S15 PRO                             | 2         | 0.27%   |
| HP ProBook 650 G4                           | 2         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 70        | 9.55%   |
| Acer Aspire         | 59        | 8.05%   |
| Lenovo IdeaPad      | 47        | 6.41%   |
| Dell Latitude       | 43        | 5.87%   |
| Dell Inspiron       | 31        | 4.23%   |
| Toshiba Satellite   | 29        | 3.96%   |
| HP Pavilion         | 26        | 3.55%   |
| HP Laptop           | 20        | 2.73%   |
| ASUS VivoBook       | 19        | 2.59%   |
| HP EliteBook        | 17        | 2.32%   |
| HP Compaq           | 14        | 1.91%   |
| HP ProBook          | 13        | 1.77%   |
| Fujitsu LIFEBOOK    | 10        | 1.36%   |
| Dell Vostro         | 8         | 1.09%   |
| HP Notebook         | 7         | 0.95%   |
| Dell Precision      | 7         | 0.95%   |
| Unknown             | 7         | 0.95%   |
| HP 250              | 6         | 0.82%   |
| ASUS S551LN         | 6         | 0.82%   |
| Toshiba dynabook    | 5         | 0.68%   |
| Lenovo Legion       | 5         | 0.68%   |
| Dell XPS            | 5         | 0.68%   |
| Acer Swift          | 5         | 0.68%   |
| Samsung 950XCJ      | 4         | 0.55%   |
| Lenovo V15-ADA      | 4         | 0.55%   |
| HP 255              | 4         | 0.55%   |
| HP 15               | 4         | 0.55%   |
| Dell System         | 4         | 0.55%   |
| ASUS ASUS           | 4         | 0.55%   |
| Acer TravelMate     | 4         | 0.55%   |
| TUXEDO InfinityBook | 3         | 0.41%   |
| Lenovo G50-70       | 3         | 0.41%   |
| Kiano Elegance      | 3         | 0.41%   |
| HP Victus           | 3         | 0.41%   |
| HP OMEN             | 3         | 0.41%   |
| ASUS TUF            | 3         | 0.41%   |
| ASUS ROG            | 3         | 0.41%   |
| Apple MacBookPro9   | 3         | 0.41%   |
| Apple MacBookPro8   | 3         | 0.41%   |
| Samsung RV419       | 2         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 78        | 10.64%  |
| 2020 | 74        | 10.1%   |
| 2012 | 63        | 8.59%   |
| 2011 | 60        | 8.19%   |
| 2015 | 52        | 7.09%   |
| 2018 | 48        | 6.55%   |
| 2013 | 46        | 6.28%   |
| 2019 | 44        | 6%      |
| 2014 | 42        | 5.73%   |
| 2010 | 42        | 5.73%   |
| 2017 | 37        | 5.05%   |
| 2016 | 34        | 4.64%   |
| 2008 | 34        | 4.64%   |
| 2022 | 26        | 3.55%   |
| 2007 | 24        | 3.27%   |
| 2009 | 22        | 3%      |
| 2023 | 3         | 0.41%   |
| 2006 | 3         | 0.41%   |
| 2004 | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 733       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 733       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 729       | 99.45%  |
| Yes  | 4         | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 274       | 37.38%  |
| 3.01-4.0    | 171       | 23.33%  |
| 16.01-24.0  | 100       | 13.64%  |
| 8.01-16.0   | 94        | 12.82%  |
| 32.01-64.0  | 31        | 4.23%   |
| 1.01-2.0    | 26        | 3.55%   |
| 2.01-3.0    | 17        | 2.32%   |
| 64.01-256.0 | 12        | 1.64%   |
| 24.01-32.0  | 8         | 1.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 456       | 62.21%  |
| 2.01-3.0 | 194       | 26.47%  |
| 0.51-1.0 | 42        | 5.73%   |
| 3.01-4.0 | 33        | 4.5%    |
| 4.01-8.0 | 7         | 0.95%   |
| 0.01-0.5 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 529       | 72.17%  |
| 2      | 169       | 23.06%  |
| 3      | 24        | 3.27%   |
| 0      | 9         | 1.23%   |
| 4      | 2         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 427       | 58.25%  |
| Yes       | 306       | 41.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 594       | 81.04%  |
| No        | 139       | 18.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 729       | 99.45%  |
| No        | 4         | 0.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 569       | 77.63%  |
| No        | 164       | 22.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 108       | 14.73%  |
| Germany     | 79        | 10.78%  |
| Italy       | 45        | 6.14%   |
| Russia      | 44        | 6%      |
| France      | 44        | 6%      |
| Poland      | 43        | 5.87%   |
| Brazil      | 35        | 4.77%   |
| UK          | 33        | 4.5%    |
| Japan       | 21        | 2.86%   |
| Spain       | 18        | 2.46%   |
| Canada      | 16        | 2.18%   |
| Netherlands | 13        | 1.77%   |
| Mexico      | 13        | 1.77%   |
| India       | 13        | 1.77%   |
| Finland     | 11        | 1.5%    |
| Czechia     | 11        | 1.5%    |
| Australia   | 11        | 1.5%    |
| Indonesia   | 9         | 1.23%   |
| Argentina   | 9         | 1.23%   |
| Hungary     | 8         | 1.09%   |
| Denmark     | 8         | 1.09%   |
| Romania     | 7         | 0.95%   |
| Belgium     | 7         | 0.95%   |
| Switzerland | 6         | 0.82%   |
| Portugal    | 6         | 0.82%   |
| Peru        | 6         | 0.82%   |
| Turkey      | 5         | 0.68%   |
| Colombia    | 5         | 0.68%   |
| Sweden      | 4         | 0.55%   |
| Slovakia    | 4         | 0.55%   |
| Saint Lucia | 4         | 0.55%   |
| Norway      | 4         | 0.55%   |
| Venezuela   | 3         | 0.41%   |
| Uruguay     | 3         | 0.41%   |
| Réunion    | 3         | 0.41%   |
| New Zealand | 3         | 0.41%   |
| Lithuania   | 3         | 0.41%   |
| Greece      | 3         | 0.41%   |
| Egypt       | 3         | 0.41%   |
| Chile       | 3         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Warsaw         | 10        | 1.36%   |
| Moscow         | 9         | 1.23%   |
| St Petersburg  | 7         | 0.95%   |
| Milan          | 6         | 0.82%   |
| Freeport       | 6         | 0.82%   |
| Cologne        | 6         | 0.82%   |
| Paris          | 5         | 0.68%   |
| Lima           | 5         | 0.68%   |
| Berlin         | 5         | 0.68%   |
| Wuppertal      | 4         | 0.55%   |
| Ufa            | 4         | 0.55%   |
| Rome           | 4         | 0.55%   |
| Rio de Janeiro | 4         | 0.55%   |
| Prague         | 4         | 0.55%   |
| Munich         | 4         | 0.55%   |
| Montpellier    | 4         | 0.55%   |
| Mexico City    | 4         | 0.55%   |
| Los Angeles    | 4         | 0.55%   |
| Krakow         | 4         | 0.55%   |
| Helsinki       | 4         | 0.55%   |
| Hamburg        | 4         | 0.55%   |
| Geneva         | 4         | 0.55%   |
| Cheltenham     | 4         | 0.55%   |
| Castries       | 4         | 0.55%   |
| Bucharest      | 4         | 0.55%   |
| Brisbane       | 4         | 0.55%   |
| Amadora        | 4         | 0.55%   |
| Victoria       | 3         | 0.41%   |
| Tokyo          | 3         | 0.41%   |
| Sydney         | 3         | 0.41%   |
| Skierniewice   | 3         | 0.41%   |
| Seattle        | 3         | 0.41%   |
| Saint-Denis    | 3         | 0.41%   |
| Poznan         | 3         | 0.41%   |
| Motherwell     | 3         | 0.41%   |
| Montevideo     | 3         | 0.41%   |
| Madrid         | 3         | 0.41%   |
| London         | 3         | 0.41%   |
| Krasnodar      | 3         | 0.41%   |
| Hexham         | 3         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 120       | 125    | 13.44%  |
| Seagate             | 111       | 114    | 12.43%  |
| WDC                 | 96        | 99     | 10.75%  |
| Toshiba             | 74        | 75     | 8.29%   |
| Crucial             | 46        | 48     | 5.15%   |
| Kingston            | 41        | 41     | 4.59%   |
| SanDisk             | 37        | 39     | 4.14%   |
| Hitachi             | 37        | 37     | 4.14%   |
| Unknown             | 32        | 32     | 3.58%   |
| HGST                | 27        | 29     | 3.02%   |
| SK hynix            | 19        | 19     | 2.13%   |
| Micron Technology   | 18        | 18     | 2.02%   |
| Intel               | 18        | 18     | 2.02%   |
| SPCC                | 14        | 14     | 1.57%   |
| JMicron Technology  | 13        | 13     | 1.46%   |
| Transcend           | 12        | 12     | 1.34%   |
| China               | 12        | 12     | 1.34%   |
| A-DATA Technology   | 10        | 10     | 1.12%   |
| KIOXIA              | 9         | 9      | 1.01%   |
| PNY                 | 8         | 8      | 0.9%    |
| Phison              | 8         | 8      | 0.9%    |
| Intenso             | 7         | 7      | 0.78%   |
| GOODRAM             | 7         | 7      | 0.78%   |
| Netac               | 6         | 6      | 0.67%   |
| Apple               | 6         | 6      | 0.67%   |
| KingSpec            | 5         | 5      | 0.56%   |
| Fujitsu             | 5         | 5      | 0.56%   |
| Verbatim            | 4         | 4      | 0.45%   |
| UMIS                | 4         | 4      | 0.45%   |
| SSSTC               | 4         | 4      | 0.45%   |
| Patriot             | 4         | 4      | 0.45%   |
| LITEON              | 4         | 4      | 0.45%   |
| Gigabyte Technology | 4         | 4      | 0.45%   |
| Apacer              | 4         | 4      | 0.45%   |
| Silicon Motion      | 3         | 3      | 0.34%   |
| Unknown             | 3         | 3      | 0.34%   |
| Wibtek              | 2         | 2      | 0.22%   |
| walram              | 2         | 2      | 0.22%   |
| SPCC Sol            | 2         | 2      | 0.22%   |
| ShiJi               | 2         | 2      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 15        | 1.65%   |
| Seagate ST1000LM035-1RK172 1TB       | 14        | 1.54%   |
| Seagate ST500LT012-1DG142 500GB      | 12        | 1.32%   |
| Toshiba MQ01ABF050 500GB             | 11        | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 0.99%   |
| Kingston SA400S37480G 480GB SSD      | 9         | 0.99%   |
| Toshiba MQ04ABF100 1TB               | 8         | 0.88%   |
| Seagate ST9500325AS 500GB            | 8         | 0.88%   |
| Seagate ST1000LM048-2E7172 1TB       | 8         | 0.88%   |
| SPCC Solid State Disk 512GB          | 7         | 0.77%   |
| SanDisk NVMe SSD Drive 1TB           | 7         | 0.77%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 0.77%   |
| Crucial CT500MX500SSD1 500GB         | 7         | 0.77%   |
| Crucial CT480BX500SSD1 480GB         | 7         | 0.77%   |
| Samsung SSD 860 EVO 500GB            | 6         | 0.66%   |
| JMicron Generic 320GB                | 6         | 0.66%   |
| Crucial CT240BX500SSD1 240GB         | 6         | 0.66%   |
| Unknown MMC64G  64GB                 | 5         | 0.55%   |
| Samsung SSD 980 PRO 1TB              | 5         | 0.55%   |
| Hitachi HTS545050B9A300 500GB        | 5         | 0.55%   |
| HGST HTS545050A7E680 500GB           | 5         | 0.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 0.44%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 4         | 0.44%   |
| Verbatim Vi550 S3 2TB                | 4         | 0.44%   |
| Toshiba MQ01ABD075 752GB             | 4         | 0.44%   |
| SSSTC CL1-4D256 256GB                | 4         | 0.44%   |
| SanDisk SSD PLUS 1000GB              | 4         | 0.44%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.44%   |
| Samsung MZVLB512HBJQ-000 512GB       | 4         | 0.44%   |
| Kingston SA400S37120G 120GB SSD      | 4         | 0.44%   |
| JMicron H/W JBOD 512GB SSD           | 4         | 0.44%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 0.44%   |
| Hitachi HTS723232A7A364 320GB        | 4         | 0.44%   |
| Hitachi HTS547575A9E384 752GB        | 4         | 0.44%   |
| HGST HTS721010A9E630 1TB             | 4         | 0.44%   |
| HGST HTS545050A7E380 500GB           | 4         | 0.44%   |
| HGST HTS541010A9E680 1TB             | 4         | 0.44%   |
| Crucial CT4000P3SSD8 4TB             | 4         | 0.44%   |
| Crucial CT1000MX500SSD1 1TB          | 4         | 0.44%   |
| Crucial CT1000BX500SSD1 1TB          | 4         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 108       | 110    | 35.29%  |
| Toshiba             | 65        | 65     | 21.24%  |
| WDC                 | 54        | 54     | 17.65%  |
| Hitachi             | 37        | 37     | 12.09%  |
| HGST                | 27        | 29     | 8.82%   |
| Fujitsu             | 5         | 5      | 1.63%   |
| Samsung Electronics | 3         | 3      | 0.98%   |
| ASMedia             | 2         | 2      | 0.65%   |
| Apple               | 2         | 2      | 0.65%   |
| USB3.0              | 1         | 1      | 0.33%   |
| Unknown             | 1         | 1      | 0.33%   |
| LaCie               | 1         | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 57        | 58     | 16.76%  |
| Crucial             | 37        | 38     | 10.88%  |
| Kingston            | 29        | 29     | 8.53%   |
| SanDisk             | 22        | 22     | 6.47%   |
| WDC                 | 15        | 15     | 4.41%   |
| SPCC                | 13        | 13     | 3.82%   |
| China               | 12        | 12     | 3.53%   |
| Micron Technology   | 11        | 11     | 3.24%   |
| Transcend           | 10        | 10     | 2.94%   |
| JMicron Technology  | 10        | 10     | 2.94%   |
| Toshiba             | 8         | 8      | 2.35%   |
| SK hynix            | 8         | 8      | 2.35%   |
| A-DATA Technology   | 7         | 7      | 2.06%   |
| PNY                 | 6         | 6      | 1.76%   |
| Netac               | 6         | 6      | 1.76%   |
| Intenso             | 6         | 6      | 1.76%   |
| Intel               | 6         | 6      | 1.76%   |
| GOODRAM             | 6         | 6      | 1.76%   |
| Verbatim            | 4         | 4      | 1.18%   |
| Patriot             | 4         | 4      | 1.18%   |
| LITEON              | 4         | 4      | 1.18%   |
| KingSpec            | 4         | 4      | 1.18%   |
| Seagate             | 3         | 3      | 0.88%   |
| Gigabyte Technology | 3         | 3      | 0.88%   |
| Apacer              | 3         | 3      | 0.88%   |
| Wibtek              | 2         | 2      | 0.59%   |
| SPCC Sol            | 2         | 2      | 0.59%   |
| ShiJi               | 2         | 2      | 0.59%   |
| SABRENT             | 2         | 2      | 0.59%   |
| KingFast            | 2         | 2      | 0.59%   |
| KingDian            | 2         | 2      | 0.59%   |
| Emtec               | 2         | 2      | 0.59%   |
| Apple               | 2         | 2      | 0.59%   |
| Wdstars             | 1         | 1      | 0.29%   |
| WDC WDS2            | 1         | 1      | 0.29%   |
| walram              | 1         | 1      | 0.29%   |
| V7                  | 1         | 1      | 0.29%   |
| TO Exter            | 1         | 1      | 0.29%   |
| Teclast             | 1         | 1      | 0.29%   |
| Star                | 1         | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 313       | 342    | 37.13%  |
| HDD     | 293       | 310    | 34.76%  |
| NVMe    | 191       | 212    | 22.66%  |
| MMC     | 37        | 38     | 4.39%   |
| Unknown | 9         | 9      | 1.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 544       | 615    | 66.42%  |
| NVMe | 191       | 211    | 23.32%  |
| SAS  | 47        | 47     | 5.74%   |
| MMC  | 37        | 38     | 4.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 406       | 450    | 67.89%  |
| 0.51-1.0   | 171       | 181    | 28.6%   |
| 1.01-2.0   | 16        | 16     | 2.68%   |
| 4.01-10.0  | 3         | 3      | 0.5%    |
| 10.01-20.0 | 2         | 2      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 227       | 30.97%  |
| 101-250        | 155       | 21.15%  |
| 251-500        | 147       | 20.05%  |
| 501-1000       | 63        | 8.59%   |
| 51-100         | 46        | 6.28%   |
| 21-50          | 42        | 5.73%   |
| Unknown        | 23        | 3.14%   |
| 1001-2000      | 19        | 2.59%   |
| 2001-3000      | 8         | 1.09%   |
| More than 3000 | 3         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 581       | 79.26%  |
| 21-50     | 54        | 7.37%   |
| 101-250   | 26        | 3.55%   |
| 51-100    | 25        | 3.41%   |
| Unknown   | 23        | 3.14%   |
| 251-500   | 13        | 1.77%   |
| 501-1000  | 8         | 1.09%   |
| 1001-2000 | 3         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 6         | 6      | 4%      |
| Seagate ST9500325AS 500GB          | 5         | 5      | 3.33%   |
| Toshiba MQ01ABD100 1TB             | 4         | 4      | 2.67%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 4      | 2.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 4      | 2.67%   |
| Hitachi HTS723232A7A364 320GB      | 4         | 4      | 2.67%   |
| HGST HTS721010A9E630 1TB           | 4         | 4      | 2.67%   |
| HGST HTS545050A7E680 500GB         | 4         | 4      | 2.67%   |
| HGST HTS545050A7E380 500GB         | 3         | 3      | 2%      |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 2%      |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 1.33%   |
| Toshiba MK5065GSX 500GB            | 2         | 2      | 1.33%   |
| Toshiba MK2529GSG 250GB            | 2         | 2      | 1.33%   |
| Seagate ST320LT012-1DG14C 320GB    | 2         | 2      | 1.33%   |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 2      | 1.33%   |
| LITEON CV8-8E128-HP 128GB SSD      | 2         | 2      | 1.33%   |
| Hitachi HTS547575A9E384 752GB      | 2         | 2      | 1.33%   |
| WDC WD7500BPVT-24HXZT1 752GB       | 1         | 1      | 0.67%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 0.67%   |
| WDC WD5000BEVT-26A0RT0 500GB       | 1         | 1      | 0.67%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 0.67%   |
| WDC WD3200LPVX-22V0TT0 320GB       | 1         | 1      | 0.67%   |
| WDC WD3200BUDT-63DPZY0 320GB       | 1         | 1      | 0.67%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 0.67%   |
| WDC WD3200BEVT-75ZCT0 320GB        | 1         | 1      | 0.67%   |
| WDC WD3200BEVT-26ZCT0 320GB        | 1         | 1      | 0.67%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 0.67%   |
| WDC WD3200BEKT-75PVMT0 320GB       | 1         | 1      | 0.67%   |
| WDC WD2500BEVS-22UST0 250GB        | 1         | 1      | 0.67%   |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 0.67%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 0.67%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 0.67%   |
| Toshiba MK5075GSX 500GB            | 1         | 1      | 0.67%   |
| Toshiba MK5065GSXN 500GB           | 1         | 1      | 0.67%   |
| Toshiba MK5061GSYN 500GB           | 1         | 1      | 0.67%   |
| Toshiba MK2555GSX 250GB            | 1         | 1      | 0.67%   |
| Toshiba MK2546GSX 250GB            | 1         | 1      | 0.67%   |
| Toshiba MK2035GSS 200GB            | 1         | 1      | 0.67%   |
| Toshiba MK1656GSY 160GB            | 1         | 1      | 0.67%   |
| Toshiba MK1652GSX 160GB            | 1         | 1      | 0.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 41     | 27.52%  |
| Toshiba             | 23        | 23     | 15.44%  |
| Hitachi             | 20        | 20     | 13.42%  |
| HGST                | 18        | 19     | 12.08%  |
| WDC                 | 12        | 12     | 8.05%   |
| SK hynix            | 4         | 4      | 2.68%   |
| Intel               | 4         | 4      | 2.68%   |
| Fujitsu             | 4         | 4      | 2.68%   |
| KingSpec            | 3         | 3      | 2.01%   |
| SPCC                | 2         | 2      | 1.34%   |
| Samsung Electronics | 2         | 2      | 1.34%   |
| LITEON              | 2         | 2      | 1.34%   |
| Intenso             | 2         | 2      | 1.34%   |
| China               | 2         | 2      | 1.34%   |
| A-DATA Technology   | 2         | 2      | 1.34%   |
| Teclast             | 1         | 1      | 0.67%   |
| SanDisk             | 1         | 1      | 0.67%   |
| Plextor             | 1         | 1      | 0.67%   |
| Netac               | 1         | 1      | 0.67%   |
| Micron Technology   | 1         | 1      | 0.67%   |
| Kingston            | 1         | 1      | 0.67%   |
| Crucial             | 1         | 1      | 0.67%   |
| Apple               | 1         | 1      | 0.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 41     | 34.45%  |
| Toshiba             | 22        | 22     | 18.49%  |
| Hitachi             | 20        | 20     | 16.81%  |
| HGST                | 18        | 19     | 15.13%  |
| WDC                 | 12        | 12     | 10.08%  |
| Fujitsu             | 4         | 4      | 3.36%   |
| Samsung Electronics | 1         | 1      | 0.84%   |
| Apple               | 1         | 1      | 0.84%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 118       | 120    | 79.73%  |
| SSD  | 27        | 27     | 18.24%  |
| NVMe | 3         | 3      | 2.03%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Toshiba MK3261GSYN 320GB   | 1         | 1      | 50%     |
| HGST HTS545050B7E660 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 581       | 671    | 71.64%  |
| Malfunc  | 145       | 150    | 17.88%  |
| Detected | 83        | 88     | 10.23%  |
| Failed   | 2         | 2      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 540       | 63.75%  |
| AMD                                     | 106       | 12.51%  |
| Samsung Electronics                     | 64        | 7.56%   |
| SanDisk                                 | 40        | 4.72%   |
| Phison Electronics                      | 13        | 1.53%   |
| Kingston Technology Company             | 13        | 1.53%   |
| SK hynix                                | 11        | 1.3%    |
| Micron/Crucial Technology               | 9         | 1.06%   |
| KIOXIA                                  | 9         | 1.06%   |
| Micron Technology                       | 7         | 0.83%   |
| Silicon Motion                          | 6         | 0.71%   |
| ADATA Technology                        | 5         | 0.59%   |
| Solid State Storage Technology          | 4         | 0.47%   |
| Nvidia                                  | 4         | 0.47%   |
| Union Memory (Shenzhen)                 | 3         | 0.35%   |
| Toshiba America Info Systems            | 2         | 0.24%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.24%   |
| Transcend                               | 1         | 0.12%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.12%   |
| Shenzhen Unionmemory Information System | 1         | 0.12%   |
| Shenzhen Longsys Electronics            | 1         | 0.12%   |
| Realtek Semiconductor                   | 1         | 0.12%   |
| Lenovo                                  | 1         | 0.12%   |
| JMicron Technology                      | 1         | 0.12%   |
| Biwin Storage Technology                | 1         | 0.12%   |
| Apple                                   | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 84        | 9.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 72        | 7.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 64        | 6.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 46        | 4.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 36        | 3.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 35        | 3.76%   |
| Intel Volume Management Device NVMe RAID Controller                              | 32        | 3.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 27        | 2.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 26        | 2.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 25        | 2.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 24        | 2.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22        | 2.37%   |
| Samsung NVMe SSD Controller 980                                                  | 21        | 2.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 21        | 2.26%   |
| Intel Tiger Lake-LP SATA Controller                                              | 19        | 2.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 19        | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 17        | 1.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 16        | 1.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 15        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 15        | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 1.4%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 12        | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 12        | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 11        | 1.18%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 0.97%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 9         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 0.97%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 8         | 0.86%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 8         | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.86%   |
| Phison PS5013 E13 NVMe Controller                                                | 7         | 0.75%   |
| Micron NVMe Storage Controller                                                   | 7         | 0.75%   |
| Intel Non-Volatile memory controller                                             | 7         | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 6         | 0.65%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 6         | 0.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 0.65%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 5         | 0.54%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 5         | 0.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 580       | 64.59%  |
| NVMe | 191       | 21.27%  |
| RAID | 69        | 7.68%   |
| IDE  | 58        | 6.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 591       | 80.63%  |
| AMD    | 142       | 19.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 1.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 11        | 1.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 11        | 1.5%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 11        | 1.5%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 10        | 1.36%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 1.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 1.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 9         | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 1.09%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 8         | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 1.09%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 8         | 1.09%   |
| AMD 3020e with Radeon Graphics                | 8         | 1.09%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.95%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.95%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 7         | 0.95%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 7         | 0.95%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 0.95%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 0.82%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 6         | 0.82%   |
| Intel 12th Gen Core i7-12700H                 | 6         | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 0.68%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 5         | 0.68%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.68%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 5         | 0.68%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 5         | 0.68%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.68%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 5         | 0.68%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 0.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.68%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 5         | 0.68%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 5         | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 165       | 22.51%  |
| Intel Core i7                  | 111       | 15.14%  |
| Intel Core i3                  | 82        | 11.19%  |
| Intel Celeron                  | 66        | 9%      |
| Other                          | 65        | 8.87%   |
| Intel Core 2 Duo               | 48        | 6.55%   |
| AMD Ryzen 5                    | 30        | 4.09%   |
| Intel Pentium                  | 29        | 3.96%   |
| AMD Ryzen 7                    | 19        | 2.59%   |
| AMD Ryzen 3                    | 16        | 2.18%   |
| Intel Pentium Dual-Core        | 8         | 1.09%   |
| AMD A6                         | 8         | 1.09%   |
| AMD A8                         | 7         | 0.95%   |
| Intel Pentium Dual             | 6         | 0.82%   |
| AMD A4                         | 6         | 0.82%   |
| AMD E                          | 5         | 0.68%   |
| AMD A10                        | 5         | 0.68%   |
| Intel Pentium Silver           | 4         | 0.55%   |
| Intel Core 2                   | 4         | 0.55%   |
| Intel Pentium Gold             | 3         | 0.41%   |
| Intel Core i9                  | 3         | 0.41%   |
| AMD Ryzen 9                    | 3         | 0.41%   |
| AMD E1                         | 3         | 0.41%   |
| AMD C-70                       | 3         | 0.41%   |
| AMD Athlon                     | 3         | 0.41%   |
| Intel Genuine                  | 2         | 0.27%   |
| Intel Celeron Dual-Core        | 2         | 0.27%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.27%   |
| AMD Ryzen 7 PRO                | 2         | 0.27%   |
| AMD Phenom II                  | 2         | 0.27%   |
| AMD E2                         | 2         | 0.27%   |
| AMD C-60                       | 2         | 0.27%   |
| AMD Athlon X2                  | 2         | 0.27%   |
| AMD Athlon 64 X2               | 2         | 0.27%   |
| AMD A12                        | 2         | 0.27%   |
| Intel Core m5                  | 1         | 0.14%   |
| Intel Core m3                  | 1         | 0.14%   |
| Intel Atom                     | 1         | 0.14%   |
| AMD V120                       | 1         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 475       | 64.8%   |
| 4      | 168       | 22.92%  |
| 6      | 31        | 4.23%   |
| 8      | 30        | 4.09%   |
| 1      | 18        | 2.46%   |
| 14     | 9         | 1.23%   |
| 12     | 1         | 0.14%   |
| 10     | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 733       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 491       | 66.98%  |
| 1      | 235       | 32.06%  |
| 4      | 5         | 0.68%   |
| 16     | 1         | 0.14%   |
| 8      | 1         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 733       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 593       | 80.9%   |
| 0x08108109 | 18        | 2.46%   |
| 0x0a50000c | 12        | 1.64%   |
| 0x08608103 | 12        | 1.64%   |
| 0x08200103 | 8         | 1.09%   |
| 0x06006705 | 8         | 1.09%   |
| 0x0500010d | 7         | 0.95%   |
| 0x08108102 | 6         | 0.82%   |
| 0x0a50000d | 5         | 0.68%   |
| 0x05000101 | 5         | 0.68%   |
| 0x08600106 | 4         | 0.55%   |
| 0x0600611a | 4         | 0.55%   |
| 0x06001119 | 4         | 0.55%   |
| 0x08608102 | 3         | 0.41%   |
| 0x0810100b | 3         | 0.41%   |
| 0x07030105 | 3         | 0.41%   |
| 0x0700010b | 3         | 0.41%   |
| 0x08600104 | 2         | 0.27%   |
| 0x0600111f | 2         | 0.27%   |
| 0x0600110f | 2         | 0.27%   |
| 0x03000027 | 2         | 0.27%   |
| 0x02000057 | 2         | 0.27%   |
| 0x02000032 | 2         | 0.27%   |
| 0x010000c8 | 2         | 0.27%   |
| 0x010000b6 | 2         | 0.27%   |
| 0x906a3    | 1         | 0.14%   |
| 0x806e9    | 1         | 0.14%   |
| 0x506c9    | 1         | 0.14%   |
| 0x406e3    | 1         | 0.14%   |
| 0x306a9    | 1         | 0.14%   |
| 0x206a7    | 1         | 0.14%   |
| 0x0a50000b | 1         | 0.14%   |
| 0x0a404102 | 1         | 0.14%   |
| 0x08a00006 | 1         | 0.14%   |
| 0x08900201 | 1         | 0.14%   |
| 0x08600103 | 1         | 0.14%   |
| 0x08600102 | 1         | 0.14%   |
| 0x08101007 | 1         | 0.14%   |
| 0x07030106 | 1         | 0.14%   |
| 0x07000110 | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 97        | 13.23%  |
| IvyBridge        | 65        | 8.87%   |
| SandyBridge      | 54        | 7.37%   |
| Skylake          | 45        | 6.14%   |
| Haswell          | 45        | 6.14%   |
| Penryn           | 42        | 5.73%   |
| TigerLake        | 37        | 5.05%   |
| Westmere         | 36        | 4.91%   |
| Silvermont       | 31        | 4.23%   |
| Core             | 31        | 4.23%   |
| Broadwell        | 31        | 4.23%   |
| Zen+             | 24        | 3.27%   |
| Goldmont plus    | 21        | 2.86%   |
| Zen 3            | 18        | 2.46%   |
| Unknown          | 18        | 2.46%   |
| IceLake          | 17        | 2.32%   |
| Excavator        | 14        | 1.91%   |
| Bobcat           | 13        | 1.77%   |
| Alderlake Hybrid | 13        | 1.77%   |
| Zen              | 12        | 1.64%   |
| CometLake        | 10        | 1.36%   |
| Zen 2            | 9         | 1.23%   |
| Piledriver       | 9         | 1.23%   |
| Goldmont         | 9         | 1.23%   |
| K8 Hammer        | 6         | 0.82%   |
| K10              | 5         | 0.68%   |
| Puma             | 4         | 0.55%   |
| K8 & K10 hybrid  | 4         | 0.55%   |
| Jaguar           | 4         | 0.55%   |
| Tremont          | 3         | 0.41%   |
| Nehalem          | 3         | 0.41%   |
| K10 Llano        | 2         | 0.27%   |
| Bonnell          | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 534       | 60.68%  |
| AMD                              | 188       | 21.36%  |
| Nvidia                           | 157       | 17.84%  |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 58        | 6.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 49        | 5.37%   |
| Intel HD Graphics 620                                                                    | 35        | 3.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 33        | 3.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 32        | 3.5%    |
| Intel HD Graphics 5500                                                                   | 27        | 2.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 27        | 2.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 2.74%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 2.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 2.3%    |
| Intel UHD Graphics 620                                                                   | 19        | 2.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 1.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 18        | 1.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 1.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.75%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 15        | 1.64%   |
| AMD Lucienne                                                                             | 15        | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 1.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.53%   |
| Intel HD Graphics 530                                                                    | 13        | 1.42%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 10        | 1.1%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 0.99%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.99%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 0.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 0.88%   |
| AMD Renoir                                                                               | 8         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.77%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.66%   |
| Intel HD Graphics 500                                                                    | 6         | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 349       | 47.61%  |
| 1 x AMD        | 133       | 18.14%  |
| Intel + Nvidia | 107       | 14.6%   |
| 2 x Intel      | 52        | 7.09%   |
| 1 x Nvidia     | 36        | 4.91%   |
| Intel + AMD    | 26        | 3.55%   |
| 2 x AMD        | 15        | 2.05%   |
| AMD + Nvidia   | 14        | 1.91%   |
| 1 x SiS        | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 708       | 96.59%  |
| Proprietary | 19        | 2.59%   |
| Unknown     | 6         | 0.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 417       | 56.89%  |
| 0.01-0.5   | 109       | 14.87%  |
| 1.01-2.0   | 91        | 12.41%  |
| 0.51-1.0   | 48        | 6.55%   |
| 3.01-4.0   | 47        | 6.41%   |
| 5.01-6.0   | 11        | 1.5%    |
| 7.01-8.0   | 6         | 0.82%   |
| 8.01-16.0  | 3         | 0.41%   |
| 2.01-3.0   | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 174       | 22.86%  |
| LG Display              | 122       | 16.03%  |
| BOE                     | 110       | 14.45%  |
| Chimei Innolux          | 109       | 14.32%  |
| Samsung Electronics     | 72        | 9.46%   |
| Lenovo                  | 22        | 2.89%   |
| Sharp                   | 19        | 2.5%    |
| LG Philips              | 16        | 2.1%    |
| Chi Mei Optoelectronics | 15        | 1.97%   |
| Apple                   | 12        | 1.58%   |
| PANDA                   | 11        | 1.45%   |
| HannStar                | 6         | 0.79%   |
| Dell                    | 6         | 0.79%   |
| Hewlett-Packard         | 5         | 0.66%   |
| AOC                     | 5         | 0.66%   |
| Sony                    | 4         | 0.53%   |
| HKC                     | 4         | 0.53%   |
| Goldstar                | 4         | 0.53%   |
| CSO                     | 4         | 0.53%   |
| Unknown                 | 3         | 0.39%   |
| Philips                 | 3         | 0.39%   |
| InfoVision              | 3         | 0.39%   |
| Hitachi                 | 3         | 0.39%   |
| Acer                    | 3         | 0.39%   |
| Toppoly                 | 2         | 0.26%   |
| Panasonic               | 2         | 0.26%   |
| InnoLux Display         | 2         | 0.26%   |
| Xiaomi                  | 1         | 0.13%   |
| Vizio                   | 1         | 0.13%   |
| ViewSonic               | 1         | 0.13%   |
| Vestel Elektronik       | 1         | 0.13%   |
| Valve                   | 1         | 0.13%   |
| TMX                     | 1         | 0.13%   |
| STA                     | 1         | 0.13%   |
| Sceptre Tech            | 1         | 0.13%   |
| QUS                     | 1         | 0.13%   |
| L                       | 1         | 0.13%   |
| Konka                   | 1         | 0.13%   |
| KDC                     | 1         | 0.13%   |
| JDZ                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 11        | 1.44%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 9         | 1.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 8         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 0.92%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.92%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 7         | 0.92%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 5         | 0.66%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 5         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 5         | 0.66%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 5         | 0.66%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 5         | 0.66%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 5         | 0.66%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 5         | 0.66%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 5         | 0.66%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 4         | 0.52%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 4         | 0.52%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 4         | 0.52%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 4         | 0.52%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 4         | 0.52%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 4         | 0.52%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch         | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch         | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 4         | 0.52%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3         | 0.39%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch               | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 3         | 0.39%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch               | 3         | 0.39%   |
| LG Philips LCD Monitor LPLA104 1440x900 367x230mm 17.1-inch           | 3         | 0.39%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch           | 3         | 0.39%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.39%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 0.39%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch               | 3         | 0.39%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 3         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 290       | 38.82%  |
| 1366x768 (WXGA)    | 281       | 37.62%  |
| 1600x900 (HD+)     | 42        | 5.62%   |
| 1280x800 (WXGA)    | 38        | 5.09%   |
| 1440x900 (WXGA+)   | 18        | 2.41%   |
| 3840x2160 (4K)     | 17        | 2.28%   |
| 2560x1600          | 13        | 1.74%   |
| 2560x1440 (QHD)    | 10        | 1.34%   |
| 1920x1200 (WUXGA)  | 9         | 1.2%    |
| 3840x2400          | 4         | 0.54%   |
| 1680x1050 (WSXGA+) | 4         | 0.54%   |
| 2288x1287          | 3         | 0.4%    |
| 3200x1800 (QHD+)   | 2         | 0.27%   |
| 2880x1800          | 2         | 0.27%   |
| 2160x1440          | 2         | 0.27%   |
| 800x1280           | 1         | 0.13%   |
| 3456x2160          | 1         | 0.13%   |
| 3440x1440          | 1         | 0.13%   |
| 2240x1400          | 1         | 0.13%   |
| 2160x1350          | 1         | 0.13%   |
| 1920x540           | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |
| 1600x2560          | 1         | 0.13%   |
| 1400x1050          | 1         | 0.13%   |
| 1360x768           | 1         | 0.13%   |
| 1024x768 (XGA)     | 1         | 0.13%   |
| 1024x600           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 367       | 48.1%   |
| 13      | 96        | 12.58%  |
| 14      | 95        | 12.45%  |
| 17      | 71        | 9.31%   |
| 12      | 26        | 3.41%   |
| 11      | 18        | 2.36%   |
| 16      | 15        | 1.97%   |
| 27      | 11        | 1.44%   |
| 23      | 11        | 1.44%   |
| 24      | 9         | 1.18%   |
| 21      | 7         | 0.92%   |
| 31      | 6         | 0.79%   |
| 18      | 5         | 0.66%   |
| 142     | 3         | 0.39%   |
| 84      | 3         | 0.39%   |
| 65      | 2         | 0.26%   |
| 52      | 2         | 0.26%   |
| 32      | 2         | 0.26%   |
| Unknown | 2         | 0.26%   |
| 72      | 1         | 0.13%   |
| 60      | 1         | 0.13%   |
| 54      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 36      | 1         | 0.13%   |
| 35      | 1         | 0.13%   |
| 29      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 22      | 1         | 0.13%   |
| 20      | 1         | 0.13%   |
| 8       | 1         | 0.13%   |
| 7       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 529       | 69.42%  |
| 351-400        | 81        | 10.63%  |
| 201-300        | 78        | 10.24%  |
| 501-600        | 30        | 3.94%   |
| 401-500        | 15        | 1.97%   |
| 601-700        | 7         | 0.92%   |
| 1001-1500      | 7         | 0.92%   |
| 1501-2000      | 4         | 0.52%   |
| More than 2000 | 3         | 0.39%   |
| 701-800        | 3         | 0.39%   |
| Unknown        | 2         | 0.26%   |
| 801-900        | 1         | 0.13%   |
| 101-200        | 1         | 0.13%   |
| 1-100          | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 611       | 85.34%  |
| 16/10   | 89        | 12.43%  |
| 3/2     | 7         | 0.98%   |
| 1.00    | 3         | 0.42%   |
| 4/3     | 2         | 0.28%   |
| 21/9    | 1         | 0.14%   |
| 0.67    | 1         | 0.14%   |
| 0.63    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 369       | 48.36%  |
| 81-90          | 160       | 20.97%  |
| 121-130        | 53        | 6.95%   |
| 71-80          | 31        | 4.06%   |
| 61-70          | 25        | 3.28%   |
| 201-250        | 24        | 3.15%   |
| 51-60          | 18        | 2.36%   |
| 131-140        | 18        | 2.36%   |
| More than 1000 | 13        | 1.7%    |
| 301-350        | 11        | 1.44%   |
| 111-120        | 11        | 1.44%   |
| 351-500        | 10        | 1.31%   |
| 141-150        | 5         | 0.66%   |
| 251-300        | 4         | 0.52%   |
| 91-100         | 3         | 0.39%   |
| 1-40           | 2         | 0.26%   |
| 151-200        | 2         | 0.26%   |
| 501-1000       | 2         | 0.26%   |
| Unknown        | 2         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 304       | 40.16%  |
| 101-120       | 293       | 38.71%  |
| 51-100        | 91        | 12.02%  |
| 161-240       | 42        | 5.55%   |
| More than 240 | 15        | 1.98%   |
| 1-50          | 10        | 1.32%   |
| Unknown       | 2         | 0.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 666       | 90.86%  |
| 2     | 62        | 8.46%   |
| 0     | 4         | 0.55%   |
| 3     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 401       | 35.02%  |
| Intel                             | 381       | 33.28%  |
| Qualcomm Atheros                  | 179       | 15.63%  |
| Broadcom                          | 63        | 5.5%    |
| Broadcom Limited                  | 16        | 1.4%    |
| MediaTek                          | 15        | 1.31%   |
| Ralink                            | 13        | 1.14%   |
| TP-Link                           | 11        | 0.96%   |
| Marvell Technology Group          | 10        | 0.87%   |
| Ralink Technology                 | 7         | 0.61%   |
| Dell                              | 6         | 0.52%   |
| Sierra Wireless                   | 4         | 0.35%   |
| Nvidia                            | 4         | 0.35%   |
| NetGear                           | 3         | 0.26%   |
| Ericsson Business Mobile Networks | 3         | 0.26%   |
| Xiaomi                            | 2         | 0.17%   |
| T & A Mobile Phones               | 2         | 0.17%   |
| Qualcomm Atheros Communications   | 2         | 0.17%   |
| Linksys                           | 2         | 0.17%   |
| JMicron Technology                | 2         | 0.17%   |
| ICS Advent                        | 2         | 0.17%   |
| ASIX Electronics                  | 2         | 0.17%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.09%   |
| Samsung Electronics               | 1         | 0.09%   |
| Qualcomm                          | 1         | 0.09%   |
| PLANEX                            | 1         | 0.09%   |
| Microsoft                         | 1         | 0.09%   |
| LG Electronics                    | 1         | 0.09%   |
| Lenovo                            | 1         | 0.09%   |
| Huawei Technologies               | 1         | 0.09%   |
| Holtek Semiconductor              | 1         | 0.09%   |
| D-Link System                     | 1         | 0.09%   |
| Attansic Technology               | 1         | 0.09%   |
| ASUSTek Computer                  | 1         | 0.09%   |
| Apple                             | 1         | 0.09%   |
| Android                           | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 233       | 16.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 79        | 5.7%    |
| Intel Wireless 7265                                                     | 39        | 2.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 32        | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 2.09%   |
| Intel Wi-Fi 6 AX201                                                     | 29        | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 26        | 1.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 26        | 1.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 1.51%   |
| Intel Wireless 8265 / 8275                                              | 21        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 21        | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.44%   |
| Intel Wireless 3165                                                     | 19        | 1.37%   |
| Intel Wireless 8260                                                     | 17        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 1.15%   |
| Intel Wireless 7260                                                     | 15        | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 14        | 1.01%   |
| Intel Wireless 3160                                                     | 14        | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 0.94%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                                   | 13        | 0.94%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                   | 11        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 10        | 0.72%   |
| Intel 82567LM Gigabit Network Connection                                | 10        | 0.72%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 9         | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 0.65%   |
| Intel Centrino Advanced-N 6200                                          | 9         | 0.65%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 8         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 369       | 48.49%  |
| Qualcomm Atheros                | 155       | 20.37%  |
| Realtek Semiconductor           | 133       | 17.48%  |
| Broadcom                        | 45        | 5.91%   |
| MediaTek                        | 14        | 1.84%   |
| Ralink                          | 13        | 1.71%   |
| Ralink Technology               | 7         | 0.92%   |
| Sierra Wireless                 | 4         | 0.53%   |
| Broadcom Limited                | 4         | 0.53%   |
| TP-Link                         | 3         | 0.39%   |
| Dell                            | 3         | 0.39%   |
| Qualcomm Atheros Communications | 2         | 0.26%   |
| NetGear                         | 2         | 0.26%   |
| Linksys                         | 2         | 0.26%   |
| Qualcomm                        | 1         | 0.13%   |
| PLANEX                          | 1         | 0.13%   |
| Microsoft                       | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |
| ASUSTek Computer                | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 39        | 5.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 3.79%   |
| Intel Wi-Fi 6 AX201                                                     | 29        | 3.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 3.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 26        | 3.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 2.75%   |
| Intel Wireless 8265 / 8275                                              | 21        | 2.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 21        | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 2.61%   |
| Intel Wireless 3165                                                     | 19        | 2.48%   |
| Intel Wireless 8260                                                     | 17        | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 2.09%   |
| Intel Wireless 7260                                                     | 15        | 1.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 14        | 1.83%   |
| Intel Wireless 3160                                                     | 14        | 1.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 1.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 1.7%    |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.7%    |
| Intel Centrino Ultimate-N 6300                                          | 13        | 1.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 1.31%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 1.31%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 1.31%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 10        | 1.31%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 9         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 1.18%   |
| Intel Centrino Advanced-N 6200                                          | 9         | 1.18%   |
| Intel WiFi Link 5100                                                    | 8         | 1.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 1.05%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 7         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 346       | 57.19%  |
| Intel                            | 130       | 21.49%  |
| Qualcomm Atheros                 | 48        | 7.93%   |
| Broadcom                         | 30        | 4.96%   |
| Broadcom Limited                 | 13        | 2.15%   |
| Marvell Technology Group         | 10        | 1.65%   |
| TP-Link                          | 8         | 1.32%   |
| Nvidia                           | 4         | 0.66%   |
| Xiaomi                           | 2         | 0.33%   |
| JMicron Technology               | 2         | 0.33%   |
| ICS Advent                       | 2         | 0.33%   |
| ASIX Electronics                 | 2         | 0.33%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| NetGear                          | 1         | 0.17%   |
| MediaTek                         | 1         | 0.17%   |
| LG Electronics                   | 1         | 0.17%   |
| Lenovo                           | 1         | 0.17%   |
| Attansic Technology              | 1         | 0.17%   |
| Apple                            | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 233       | 38.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 79        | 12.97%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 32        | 5.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 26        | 4.27%   |
| Intel Ethernet Connection (3) I218-LM                                          | 13        | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 1.81%   |
| Intel 82567LM Gigabit Network Connection                                       | 10        | 1.64%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 8         | 1.31%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 1.31%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 1.31%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 7         | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 1.15%   |
| Intel 82566MM Gigabit Network Connection                                       | 7         | 1.15%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 6         | 0.99%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 6         | 0.99%   |
| Intel 82579V Gigabit Network Connection                                        | 6         | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 0.99%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 5         | 0.82%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 0.66%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 0.66%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 4         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.49%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.49%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 0.49%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 0.49%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 0.49%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 3         | 0.49%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.33%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 729       | 54.57%  |
| Ethernet | 594       | 44.46%  |
| Modem    | 10        | 0.75%   |
| Unknown  | 3         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 544       | 75.66%  |
| Ethernet | 174       | 24.2%   |
| Modem    | 1         | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 543       | 74.08%  |
| 1     | 172       | 23.47%  |
| 0     | 16        | 2.18%   |
| 3     | 2         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 488       | 66.58%  |
| Yes  | 245       | 33.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 270       | 47.37%  |
| Realtek Semiconductor           | 62        | 10.88%  |
| Qualcomm Atheros Communications | 55        | 9.65%   |
| Broadcom                        | 34        | 5.96%   |
| Lite-On Technology              | 29        | 5.09%   |
| IMC Networks                    | 28        | 4.91%   |
| Foxconn / Hon Hai               | 17        | 2.98%   |
| Toshiba                         | 14        | 2.46%   |
| Hewlett-Packard                 | 13        | 2.28%   |
| Apple                           | 11        | 1.93%   |
| Dell                            | 10        | 1.75%   |
| Cambridge Silicon Radio         | 8         | 1.4%    |
| ASUSTek Computer                | 6         | 1.05%   |
| Ralink                          | 5         | 0.88%   |
| Realtek                         | 4         | 0.7%    |
| Qcom                            | 1         | 0.18%   |
| Fujitsu                         | 1         | 0.18%   |
| Foxconn International           | 1         | 0.18%   |
| Chicony Electronics             | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 128       | 22.46%  |
| Realtek Bluetooth Radio                             | 43        | 7.54%   |
| Intel AX201 Bluetooth                               | 43        | 7.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 42        | 7.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 25        | 4.39%   |
| Intel Wireless-AC 3168 Bluetooth                    | 16        | 2.81%   |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 2.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 2.28%   |
| Intel AX200 Bluetooth                               | 13        | 2.28%   |
| Intel Bluetooth Device                              | 12        | 2.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 1.93%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 1.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 1.4%    |
| IMC Networks Wireless_Device                        | 8         | 1.4%    |
| IMC Networks Bluetooth Radio                        | 8         | 1.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 1.4%    |
| Broadcom BCM2045B (BDC-2.1)                         | 8         | 1.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 1.23%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 1.23%   |
| Intel AX210 Bluetooth                               | 6         | 1.05%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.05%   |
| Apple Bluetooth Host Controller                     | 6         | 1.05%   |
| Toshiba Bluetooth Device                            | 5         | 0.88%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.88%   |
| IMC Networks Bluetooth Device                       | 5         | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.88%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.88%   |
| Realtek Bluetooth Radio                             | 4         | 0.7%    |
| Lite-On Wireless_Device                             | 4         | 0.7%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 4         | 0.7%    |
| Toshiba RT Bluetooth Radio                          | 3         | 0.53%   |
| Toshiba Askey Bluetooth Module                      | 3         | 0.53%   |
| Lite-On Bluetooth Device                            | 3         | 0.53%   |
| IMC Networks Bluetooth                              | 3         | 0.53%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 3         | 0.53%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.53%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.53%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 3         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 587       | 68.9%   |
| AMD                              | 158       | 18.54%  |
| Nvidia                           | 83        | 9.74%   |
| Generalplus Technology           | 6         | 0.7%    |
| C-Media Electronics              | 5         | 0.59%   |
| Texas Instruments                | 2         | 0.23%   |
| JMTek                            | 2         | 0.23%   |
| THX                              | 1         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| PreSonus Audio Electronics       | 1         | 0.12%   |
| No brand                         | 1         | 0.12%   |
| Lenovo                           | 1         | 0.12%   |
| Hewlett-Packard                  | 1         | 0.12%   |
| Creative Technology              | 1         | 0.12%   |
| Corsair                          | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 85        | 8.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 78        | 7.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 69        | 6.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 50        | 4.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 41        | 3.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 39        | 3.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 37        | 3.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 36        | 3.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 32        | 3.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 31        | 2.96%   |
| Intel Broadwell-U Audio Controller                                                                | 31        | 2.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 27        | 2.58%   |
| Intel 8 Series HD Audio Controller                                                                | 27        | 2.58%   |
| AMD FCH Azalia Controller                                                                         | 25        | 2.39%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 24        | 2.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 21        | 2.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 20        | 1.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 1.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 1.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 1.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 14        | 1.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 13        | 1.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 1.05%   |
| AMD Wrestler HDMI Audio                                                                           | 11        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 0.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 0.86%   |
| AMD Trinity HDMI Audio Controller                                                                 | 9         | 0.86%   |
| AMD High Definition Audio Controller                                                              | 9         | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.76%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.57%   |
| Generalplus Technology USB Audio Device                                                           | 6         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 236       | 25.62%  |
| SK hynix                                         | 200       | 21.72%  |
| Micron Technology                                | 115       | 12.49%  |
| Kingston                                         | 86        | 9.34%   |
| Unknown                                          | 58        | 6.3%    |
| Crucial                                          | 35        | 3.8%    |
| Nanya Technology                                 | 24        | 2.61%   |
| Ramaxel Technology                               | 22        | 2.39%   |
| Elpida                                           | 21        | 2.28%   |
| Unknown (ABCD)                                   | 17        | 1.85%   |
| A-DATA Technology                                | 15        | 1.63%   |
| Corsair                                          | 9         | 0.98%   |
| Transcend                                        | 8         | 0.87%   |
| Smart                                            | 7         | 0.76%   |
| Unknown                                          | 7         | 0.76%   |
| Team                                             | 5         | 0.54%   |
| G.Skill                                          | 5         | 0.54%   |
| Qimonda                                          | 4         | 0.43%   |
| Patriot                                          | 4         | 0.43%   |
| Teikon                                           | 3         | 0.33%   |
| Innodisk                                         | 3         | 0.33%   |
| GOODRAM                                          | 3         | 0.33%   |
| Unknown (0x48594D503132355336344350382D53362020) | 2         | 0.22%   |
| Timetec                                          | 2         | 0.22%   |
| Sesame                                           | 2         | 0.22%   |
| Neo Forza                                        | 2         | 0.22%   |
| Avant                                            | 2         | 0.22%   |
| Apacer                                           | 2         | 0.22%   |
| Wilk                                             | 1         | 0.11%   |
| Walton Chaintech                                 | 1         | 0.11%   |
| Unknown (0xAD0A)                                 | 1         | 0.11%   |
| Unknown (0x48594D503131325336344350362D53362020) | 1         | 0.11%   |
| Unknown (0x31364854463235363634485A2D3830304831) | 1         | 0.11%   |
| Unknown (0x202020202020202020202020202020202020) | 1         | 0.11%   |
| Unknown (081A)                                   | 1         | 0.11%   |
| Toshiba                                          | 1         | 0.11%   |
| SHARETRONIC                                      | 1         | 0.11%   |
| Qumo                                             | 1         | 0.11%   |
| PUSKILL                                          | 1         | 0.11%   |
| PNY                                              | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 16        | 1.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 16        | 1.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 1.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 1.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 1.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 1.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 1.13%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 11        | 1.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 1.03%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 9         | 0.92%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 8         | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.82%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 7         | 0.72%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.72%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 7         | 0.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.72%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.72%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 7         | 0.72%   |
| Unknown                                                          | 7         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 6         | 0.62%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 6         | 0.62%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 6         | 0.62%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 5         | 0.51%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 5         | 0.51%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.51%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 5         | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.51%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.51%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 318       | 42.29%  |
| DDR4    | 287       | 38.16%  |
| DDR2    | 58        | 7.71%   |
| LPDDR4  | 38        | 5.05%   |
| SDRAM   | 26        | 3.46%   |
| DDR     | 6         | 0.8%    |
| LPDDR3  | 5         | 0.66%   |
| DDR5    | 4         | 0.53%   |
| Unknown | 4         | 0.53%   |
| LPDDR5  | 3         | 0.4%    |
| DRAM    | 3         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 681       | 91.41%  |
| Row Of Chips | 49        | 6.58%   |
| Unknown      | 7         | 0.94%   |
| DIMM         | 6         | 0.81%   |
| Chip         | 2         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 320       | 37.69%  |
| 8192  | 269       | 31.68%  |
| 2048  | 143       | 16.84%  |
| 16384 | 62        | 7.3%    |
| 1024  | 32        | 3.77%   |
| 32768 | 22        | 2.59%   |
| 512   | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 219       | 26.32%  |
| 3200    | 143       | 17.19%  |
| 2667    | 115       | 13.82%  |
| 2400    | 69        | 8.29%   |
| 1334    | 65        | 7.81%   |
| 667     | 36        | 4.33%   |
| 1333    | 35        | 4.21%   |
| 2133    | 22        | 2.64%   |
| 800     | 21        | 2.52%   |
| 4199    | 15        | 1.8%    |
| Unknown | 15        | 1.8%    |
| 1067    | 12        | 1.44%   |
| 3266    | 10        | 1.2%    |
| 2048    | 10        | 1.2%    |
| 1867    | 8         | 0.96%   |
| 4267    | 7         | 0.84%   |
| 533     | 6         | 0.72%   |
| 1066    | 5         | 0.6%    |
| 4800    | 4         | 0.48%   |
| 975     | 4         | 0.48%   |
| 3733    | 3         | 0.36%   |
| 8400    | 2         | 0.24%   |
| 6400    | 2         | 0.24%   |
| 4266    | 2         | 0.24%   |
| 5500    | 1         | 0.12%   |
| 1866    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 36.36%  |
| Brother Industries  | 3         | 27.27%  |
| Xerox               | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |
| Prolific Technology | 1         | 9.09%   |
| Canon               | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox WorkCentre 6025               | 1         | 8.33%   |
| Samsung ML-2010P Mono Laser Printer | 1         | 8.33%   |
| Prolific PL2305 Parallel Port       | 1         | 8.33%   |
| HP OfficeJet 6950                   | 1         | 8.33%   |
| HP Deskjet F4500 series             | 1         | 8.33%   |
| HP DeskJet 6122                     | 1         | 8.33%   |
| HP Deskjet 2050 J510                | 1         | 8.33%   |
| Canon LBP6030w/6018w                | 1         | 8.33%   |
| Brother Printer                     | 1         | 8.33%   |
| Brother MFC-J6535DW                 | 1         | 8.33%   |
| Brother MFC-J480DW                  | 1         | 8.33%   |
| Brother DCP-7010                    | 1         | 8.33%   |

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
| Chicony Electronics                    | 186       | 29.38%  |
| Realtek Semiconductor                  | 57        | 9%      |
| IMC Networks                           | 57        | 9%      |
| Microdia                               | 46        | 7.27%   |
| Sunplus Innovation Technology          | 31        | 4.9%    |
| Suyin                                  | 28        | 4.42%   |
| Quanta                                 | 28        | 4.42%   |
| Syntek                                 | 25        | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 3.79%   |
| Bison Electronics                      | 24        | 3.79%   |
| Lite-On Technology                     | 14        | 2.21%   |
| Silicon Motion                         | 13        | 2.05%   |
| Apple                                  | 13        | 2.05%   |
| Acer                                   | 13        | 2.05%   |
| Alcor Micro                            | 9         | 1.42%   |
| Luxvisions Innotech Limited            | 8         | 1.26%   |
| Primax Electronics                     | 6         | 0.95%   |
| Ricoh                                  | 5         | 0.79%   |
| Importek                               | 5         | 0.79%   |
| Sonix Technology                       | 4         | 0.63%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.63%   |
| Lenovo                                 | 4         | 0.63%   |
| icSpring                               | 4         | 0.63%   |
| ALi                                    | 4         | 0.63%   |
| OmniVision Technologies                | 3         | 0.47%   |
| Z-Star Microelectronics                | 2         | 0.32%   |
| Y Media                                | 2         | 0.32%   |
| Sunplus Technology                     | 2         | 0.32%   |
| Samsung Electronics                    | 2         | 0.32%   |
| Logitech                               | 2         | 0.32%   |
| Intel                                  | 2         | 0.32%   |
| HRY                                    | 2         | 0.32%   |
| Huawei Technologies                    | 1         | 0.16%   |
| Genesys Logic                          | 1         | 0.16%   |
| Generalplus Technology                 | 1         | 0.16%   |
| DigiTech                               | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 27        | 4.27%   |
| Chicony HD WebCam                                | 20        | 3.16%   |
| Microdia Integrated_Webcam_HD                    | 18        | 2.84%   |
| Syntek Integrated Camera                         | 15        | 2.37%   |
| IMC Networks USB2.0 HD UVC WebCam                | 14        | 2.21%   |
| IMC Networks Integrated Camera                   | 14        | 2.21%   |
| Realtek USB Camera                               | 12        | 1.9%    |
| Realtek Integrated_Webcam_HD                     | 12        | 1.9%    |
| IMC Networks USB2.0 VGA UVC WebCam               | 11        | 1.74%   |
| Sunplus Integrated_Webcam_HD                     | 10        | 1.58%   |
| Microdia Integrated Webcam                       | 9         | 1.42%   |
| Chicony Lenovo EasyCamera                        | 9         | 1.42%   |
| Chicony USB2.0 Camera                            | 8         | 1.26%   |
| Chicony FJ Camera                                | 8         | 1.26%   |
| Bison Integrated Camera                          | 8         | 1.26%   |
| Chicony VGA Webcam                               | 7         | 1.11%   |
| Chicony HP TrueVision HD Camera                  | 7         | 1.11%   |
| Chicony HP Truevision HD                         | 7         | 1.11%   |
| Chicony HD User Facing                           | 7         | 1.11%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 7         | 1.11%   |
| Chicony TOSHIBA Web Camera - HD                  | 6         | 0.95%   |
| Chicony EasyCamera                               | 6         | 0.95%   |
| Apple FaceTime HD Camera                         | 6         | 0.95%   |
| Syntek Lenovo EasyCamera                         | 5         | 0.79%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 5         | 0.79%   |
| Suyin 1.3M HD WebCam                             | 5         | 0.79%   |
| Realtek Integrated Webcam                        | 5         | 0.79%   |
| Quanta HP TrueVision HD Camera                   | 5         | 0.79%   |
| Quanta HD User Facing                            | 5         | 0.79%   |
| Lite-On Integrated Camera                        | 5         | 0.79%   |
| Chicony Camera                                   | 5         | 0.79%   |
| Bison Lenovo EasyCamera                          | 5         | 0.79%   |
| Alcor Micro USB 2.0 Camera                       | 5         | 0.79%   |
| Acer Integrated Camera                           | 5         | 0.79%   |
| Acer HD Webcam                                   | 5         | 0.79%   |
| Sunplus HD WebCam                                | 4         | 0.63%   |
| Sonix USB2.0 HD UVC WebCam                       | 4         | 0.63%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera  | 4         | 0.63%   |
| Realtek EasyCamera                               | 4         | 0.63%   |
| Realtek Acer 640 x 480 laptop camera             | 4         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 34        | 30.09%  |
| AuthenTec                  | 19        | 16.81%  |
| Synaptics                  | 14        | 12.39%  |
| Shenzhen Goodix Technology | 11        | 9.73%   |
| Upek                       | 9         | 7.96%   |
| Elan Microelectronics      | 9         | 7.96%   |
| LighTuning Technology      | 6         | 5.31%   |
| STMicroelectronics         | 4         | 3.54%   |
| Samsung Electronics        | 4         | 3.54%   |
| Focal-systems.Corp         | 3         | 2.65%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 7.96%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 7.08%   |
| AuthenTec AES2810                                                          | 8         | 7.08%   |
| Validity Sensors VFS491                                                    | 6         | 5.31%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 5.31%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 5.31%   |
| Elan ELAN:ARM-M4                                                           | 5         | 4.42%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.54%   |
| Synaptics UWP WBDI Device                                                  | 4         | 3.54%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 3.54%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 3.54%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 3.54%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 3.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.65%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.65%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.65%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 2.65%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.77%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.77%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.77%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.77%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.77%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.77%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 1.77%   |
| AuthenTec AES1600                                                          | 2         | 1.77%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.88%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.88%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.88%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.88%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.88%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 20        | 42.55%  |
| O2 Micro              | 12        | 25.53%  |
| Alcor Micro           | 7         | 14.89%  |
| Upek                  | 3         | 6.38%   |
| Lenovo                | 3         | 6.38%   |
| Realtek Semiconductor | 1         | 2.13%   |
| Advanced Card Systems | 1         | 2.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 12        | 25.53%  |
| Broadcom 5880                                                                | 9         | 19.15%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 14.89%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 12.77%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 8.51%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 6.38%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.38%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.13%   |
| Broadcom 58200                                                               | 1         | 2.13%   |
| Advanced Card Systems ACR122U                                                | 1         | 2.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 535       | 72.99%  |
| 1     | 169       | 23.06%  |
| 2     | 27        | 3.68%   |
| 3     | 2         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 113       | 50.67%  |
| Chipcard                 | 46        | 20.63%  |
| Graphics card            | 43        | 19.28%  |
| Net/wireless             | 5         | 2.24%   |
| Bluetooth                | 5         | 2.24%   |
| Storage                  | 3         | 1.35%   |
| Camera                   | 3         | 1.35%   |
| Multimedia controller    | 2         | 0.9%    |
| Communication controller | 2         | 0.9%    |
| Flash memory             | 1         | 0.45%   |


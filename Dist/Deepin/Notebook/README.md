Deepin - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Deepin.

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

Total: 166

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | G15 5520                    | [0322e7d38c](https://linux-hardware.org/?probe=0322e7d38c) | Mar 06, 2023 |
| Lenovo    | ThinkPad T14 Gen 1 20UD0... | [42a0b7428f](https://linux-hardware.org/?probe=42a0b7428f) | Mar 05, 2023 |
| Dell      | G15 5520                    | [1e3dcc41d3](https://linux-hardware.org/?probe=1e3dcc41d3) | Mar 04, 2023 |
| Lenovo    | Legion Y530-15ICH 81FV      | [f492107b66](https://linux-hardware.org/?probe=f492107b66) | Feb 19, 2023 |
| HP        | Pavilion Laptop 15-eh1xx... | [1746b40d04](https://linux-hardware.org/?probe=1746b40d04) | Feb 09, 2023 |
| Acer      | Aspire A515-54G             | [a57a68e42f](https://linux-hardware.org/?probe=a57a68e42f) | Jan 31, 2023 |
| Infinix   | INBOOK X2 GEN11             | [a899026279](https://linux-hardware.org/?probe=a899026279) | Jan 08, 2023 |
| Lenovo    | ThinkBook 14 G4+ ARA 21D... | [c4170b9ea3](https://linux-hardware.org/?probe=c4170b9ea3) | Dec 20, 2022 |
| Dell      | Inspiron 5488               | [32b350c3f6](https://linux-hardware.org/?probe=32b350c3f6) | Nov 25, 2022 |
| Timi      | Redmi G 2022                | [86f8128511](https://linux-hardware.org/?probe=86f8128511) | Nov 12, 2022 |
| HP        | Laptop                      | [e1cd3de91a](https://linux-hardware.org/?probe=e1cd3de91a) | Nov 02, 2022 |
| HUAWEI    | MACHD-WXX9                  | [ba1f911067](https://linux-hardware.org/?probe=ba1f911067) | Sep 10, 2022 |
| HP        | 620                         | [4476f5f677](https://linux-hardware.org/?probe=4476f5f677) | Jun 23, 2022 |
| Lenovo    | ZHAOYANG K4e-ITL 82F8       | [6103e540b9](https://linux-hardware.org/?probe=6103e540b9) | May 04, 2022 |
| HP        | EliteBook 8570w             | [7795fe989b](https://linux-hardware.org/?probe=7795fe989b) | Apr 29, 2022 |
| HUAWEI    | BOM-WXX9                    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI    | BOM-WXX9                    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Lenovo    | Legion Y7000 81FW           | [c56c469d4f](https://linux-hardware.org/?probe=c56c469d4f) | Apr 21, 2022 |
| Acer      | Swift SF314-512             | [d7e77fd856](https://linux-hardware.org/?probe=d7e77fd856) | Apr 21, 2022 |
| HP        | Laptop 14s-fq0xxx           | [8794debb03](https://linux-hardware.org/?probe=8794debb03) | Apr 20, 2022 |
| ASUSTek   | P552LA                      | [94ef2678d5](https://linux-hardware.org/?probe=94ef2678d5) | Apr 03, 2022 |
| ASUSTek   | P552LA                      | [9166f15878](https://linux-hardware.org/?probe=9166f15878) | Apr 03, 2022 |
| HP        | EliteBook 8570w             | [131c9a7dc2](https://linux-hardware.org/?probe=131c9a7dc2) | Jan 27, 2022 |
| Lenovo    | Yoga 3 Pro-1370 80HE        | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| Google    | Akemi                       | [295fd594af](https://linux-hardware.org/?probe=295fd594af) | Dec 27, 2021 |
| Acer      | Aspire VN7-572G             | [895dca26b0](https://linux-hardware.org/?probe=895dca26b0) | Dec 21, 2021 |
| HUAWEI    | HN-WX9X                     | [f228b60d0c](https://linux-hardware.org/?probe=f228b60d0c) | Dec 07, 2021 |
| HP        | EliteBook 8570w             | [7752a79879](https://linux-hardware.org/?probe=7752a79879) | Dec 06, 2021 |
| HP        | Laptop 14-ck0xxx            | [4b03ed047c](https://linux-hardware.org/?probe=4b03ed047c) | Dec 06, 2021 |
| Samsung   | 550P5C/550P7C               | [31bc59dcb9](https://linux-hardware.org/?probe=31bc59dcb9) | Nov 12, 2021 |
| Lenovo    | ThinkBook 13s-IWL 20R9      | [88d791ff87](https://linux-hardware.org/?probe=88d791ff87) | Nov 09, 2021 |
| Dell      | Latitude 3400               | [7f519c2721](https://linux-hardware.org/?probe=7f519c2721) | Oct 23, 2021 |
| Samsung   | 550P5C/550P7C               | [2713972f14](https://linux-hardware.org/?probe=2713972f14) | Oct 22, 2021 |
| HP        | ZHAN 66 Pro G1              | [a1a1c41c6a](https://linux-hardware.org/?probe=a1a1c41c6a) | Oct 09, 2021 |
| HP        | ZHAN 66 Pro G1              | [fcc291e2f1](https://linux-hardware.org/?probe=fcc291e2f1) | Oct 08, 2021 |
| Lenovo    | Legion Y7000 2020 82AV      | [64d71e1177](https://linux-hardware.org/?probe=64d71e1177) | Sep 29, 2021 |
| HP        | Laptop 15-bs0xx             | [fc0f8f406b](https://linux-hardware.org/?probe=fc0f8f406b) | Aug 31, 2021 |
| Lenovo    | ThinkPad L412 0585AC3       | [f31b3187c3](https://linux-hardware.org/?probe=f31b3187c3) | Aug 23, 2021 |
| Lenovo    | Legion R9000K2021H 82N6     | [048b8332cc](https://linux-hardware.org/?probe=048b8332cc) | Aug 13, 2021 |
| ASUSTek   | ASUS TUF Gaming A15 FA50... | [5e1cc5b229](https://linux-hardware.org/?probe=5e1cc5b229) | Aug 11, 2021 |
| Lenovo    | XiaoXinAir-14ARE 2020 81... | [d563d62b5f](https://linux-hardware.org/?probe=d563d62b5f) | Jul 14, 2021 |
| Acer      | Aspire 5750G                | [61b9408d9e](https://linux-hardware.org/?probe=61b9408d9e) | Jul 11, 2021 |
| Acer      | Aspire 5750G                | [59728d9bef](https://linux-hardware.org/?probe=59728d9bef) | Jul 11, 2021 |
| HUAWEI    | HLYL-WXX9                   | [26b5b9e3d3](https://linux-hardware.org/?probe=26b5b9e3d3) | Jul 06, 2021 |
| Lenovo    | ZHAOYANG CF4620Z-A123 59... | [6f716961de](https://linux-hardware.org/?probe=6f716961de) | Jun 29, 2021 |
| Lenovo    | XiaoXin-15ARE 2020 81YR     | [279dea011e](https://linux-hardware.org/?probe=279dea011e) | Jun 28, 2021 |
| Lenovo    | ThinkBook 14 G2 ARE R7 8... | [b2c24061a6](https://linux-hardware.org/?probe=b2c24061a6) | Jun 13, 2021 |
| Lenovo    | IdeaPad 320-15IKB 80XL      | [0540d35606](https://linux-hardware.org/?probe=0540d35606) | May 31, 2021 |
| Samsung   | 300E4A/300E5A/300E7A/343... | [30ffaaaad4](https://linux-hardware.org/?probe=30ffaaaad4) | May 22, 2021 |
| Samsung   | 300E4A/300E5A/300E7A/343... | [91b9340ed6](https://linux-hardware.org/?probe=91b9340ed6) | May 20, 2021 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | [68740fff81](https://linux-hardware.org/?probe=68740fff81) | May 16, 2021 |
| Unknown   | Unknown                     | [4d3ffa307c](https://linux-hardware.org/?probe=4d3ffa307c) | Apr 26, 2021 |
| Unknown   | Unknown                     | [8d019adbf9](https://linux-hardware.org/?probe=8d019adbf9) | Apr 26, 2021 |
| Lenovo    | ThinkPad T420 4180M8P       | [1fe655cf93](https://linux-hardware.org/?probe=1fe655cf93) | Apr 25, 2021 |
| Toshiba   | Satellite E55t-A            | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Unknown   | Unknown                     | [94f00d3697](https://linux-hardware.org/?probe=94f00d3697) | Mar 27, 2021 |
| Sony      | VGN-AW11Z_B                 | [9ddedfd3c9](https://linux-hardware.org/?probe=9ddedfd3c9) | Feb 13, 2021 |
| HP        | Pavilion Laptop 14-bf0xx    | [309266e981](https://linux-hardware.org/?probe=309266e981) | Feb 13, 2021 |
| Dell      | Inspiron 7720               | [8c8689a8ba](https://linux-hardware.org/?probe=8c8689a8ba) | Feb 08, 2021 |
| Acer      | Aspire V5-571P              | [e03d4bc850](https://linux-hardware.org/?probe=e03d4bc850) | Feb 07, 2021 |
| Dell      | Inspiron 5547               | [e2cee5283f](https://linux-hardware.org/?probe=e2cee5283f) | Feb 04, 2021 |
| HUAWEI    | HN-WX9X                     | [b0ca634dee](https://linux-hardware.org/?probe=b0ca634dee) | Jan 28, 2021 |
| Lenovo    | ThinkPad E14 20RA0058VA     | [3c08ce49f5](https://linux-hardware.org/?probe=3c08ce49f5) | Jan 08, 2021 |
| Acer      | Aspire 4736Z                | [dd3b50729f](https://linux-hardware.org/?probe=dd3b50729f) | Jan 07, 2021 |
| ASUSTek   | X406UAR                     | [42e509209a](https://linux-hardware.org/?probe=42e509209a) | Dec 20, 2020 |
| ASUSTek   | X406UAR                     | [23b1fae05b](https://linux-hardware.org/?probe=23b1fae05b) | Dec 20, 2020 |
| Lenovo    | IdeaPad 3 14ARE05 81W3      | [667577cb5f](https://linux-hardware.org/?probe=667577cb5f) | Dec 15, 2020 |
| Lenovo    | G50-80 80L0                 | [951a5a280f](https://linux-hardware.org/?probe=951a5a280f) | Dec 11, 2020 |
| Acer      | Nitro AN515-54              | [d46eb4b9c9](https://linux-hardware.org/?probe=d46eb4b9c9) | Nov 19, 2020 |
| Acer      | Nitro AN515-54              | [877187c708](https://linux-hardware.org/?probe=877187c708) | Nov 19, 2020 |
| Lenovo    | ThinkPad E585 20KV0010US    | [033f6f0920](https://linux-hardware.org/?probe=033f6f0920) | Nov 18, 2020 |
| Lenovo    | ThinkPad E585 20KV0010US    | [d2bedcab13](https://linux-hardware.org/?probe=d2bedcab13) | Nov 18, 2020 |
| Lenovo    | IdeaPad S145-15API 81UT     | [b687de4d3c](https://linux-hardware.org/?probe=b687de4d3c) | Nov 05, 2020 |
| Toshiba   | Satellite C850D-11K         | [53f5d002c9](https://linux-hardware.org/?probe=53f5d002c9) | Oct 31, 2020 |
| HP        | ENVY 15                     | [c23287b06d](https://linux-hardware.org/?probe=c23287b06d) | Oct 31, 2020 |
| Acer      | Swift SF314-42              | [628265bca0](https://linux-hardware.org/?probe=628265bca0) | Oct 25, 2020 |
| Acer      | Swift SF314-42              | [01143e194b](https://linux-hardware.org/?probe=01143e194b) | Oct 20, 2020 |
| Lenovo    | IdeaPad 110-14IBR 80UJ      | [8d149c1a39](https://linux-hardware.org/?probe=8d149c1a39) | Oct 17, 2020 |
| Acer      | Nitro AN515-52              | [ca3d5b9444](https://linux-hardware.org/?probe=ca3d5b9444) | Oct 13, 2020 |
| Microtech | ebookPro                    | [2f1ff6265a](https://linux-hardware.org/?probe=2f1ff6265a) | Oct 10, 2020 |
| HUAWEI    | NBLK-WAX9X                  | [88e5775f0f](https://linux-hardware.org/?probe=88e5775f0f) | Oct 02, 2020 |
| HUAWEI    | NBLK-WAX9X                  | [2972557e3e](https://linux-hardware.org/?probe=2972557e3e) | Oct 02, 2020 |
| Lenovo    | G50-70 20351                | [c5ea28ed29](https://linux-hardware.org/?probe=c5ea28ed29) | Sep 28, 2020 |
| HP        | ENVY 15                     | [e7bfa62e4c](https://linux-hardware.org/?probe=e7bfa62e4c) | Sep 23, 2020 |
| Samsung   | 270E5J/2570EJ               | [d00667e263](https://linux-hardware.org/?probe=d00667e263) | Sep 21, 2020 |
| HP        | Pavilion 15                 | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| HP        | Pavilion 15                 | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| Dell      | Inspiron 3583               | [860b906339](https://linux-hardware.org/?probe=860b906339) | Sep 14, 2020 |
| Lenovo    | V310-15ISK 80SY             | [043d555fa5](https://linux-hardware.org/?probe=043d555fa5) | Sep 05, 2020 |
| Acer      | Aspire E5-571               | [84a6667f77](https://linux-hardware.org/?probe=84a6667f77) | Sep 05, 2020 |
| Acer      | Aspire 5735                 | [0e4c64618a](https://linux-hardware.org/?probe=0e4c64618a) | Sep 03, 2020 |
| Dell      | Inspiron 3583               | [885667a4cd](https://linux-hardware.org/?probe=885667a4cd) | Sep 02, 2020 |
| Samsung   | 340XAA/350XAA/550XAA        | [e4b74d9442](https://linux-hardware.org/?probe=e4b74d9442) | Sep 02, 2020 |
| Dell      | Inspiron 5447               | [bc69598c5f](https://linux-hardware.org/?probe=bc69598c5f) | Aug 28, 2020 |
| Dell      | Inspiron 5447               | [b9bf539788](https://linux-hardware.org/?probe=b9bf539788) | Jul 26, 2020 |
| Samsung   | 500R4K/500R5H/5400RK/501... | [b73122dcbf](https://linux-hardware.org/?probe=b73122dcbf) | Jul 24, 2020 |
| Dell      | Inspiron 7520               | [0e4bbcdaca](https://linux-hardware.org/?probe=0e4bbcdaca) | Jul 19, 2020 |
| Lenovo    | ThinkPad L512 44444NG       | [bfda7d01d5](https://linux-hardware.org/?probe=bfda7d01d5) | Jun 30, 2020 |
| HP        | EliteBook 820 G3            | [1ad623b060](https://linux-hardware.org/?probe=1ad623b060) | Jun 20, 2020 |
| HP        | EliteBook 820 G3            | [5517a703d4](https://linux-hardware.org/?probe=5517a703d4) | Jun 15, 2020 |
| Chuwi     | AeroBook                    | [12312a6c5b](https://linux-hardware.org/?probe=12312a6c5b) | Jun 03, 2020 |
| Chuwi     | AeroBook                    | [fdcf37b34d](https://linux-hardware.org/?probe=fdcf37b34d) | Jun 01, 2020 |
| Chuwi     | AeroBook                    | [6a57e4427b](https://linux-hardware.org/?probe=6a57e4427b) | Jun 01, 2020 |
| Google    | Edgar                       | [ed3bf69957](https://linux-hardware.org/?probe=ed3bf69957) | May 28, 2020 |
| ASUSTek   | T100TAF                     | [6d2999ebb1](https://linux-hardware.org/?probe=6d2999ebb1) | May 26, 2020 |
| HP        | Pavilion Notebook           | [825d07d907](https://linux-hardware.org/?probe=825d07d907) | May 14, 2020 |
| Lenovo    | IdeaPad 120S-11IAP 81A4     | [49661d90bd](https://linux-hardware.org/?probe=49661d90bd) | Apr 19, 2020 |
| HP        | EliteBook 8570p             | [6928abb72d](https://linux-hardware.org/?probe=6928abb72d) | Apr 07, 2020 |
| HP        | EliteBook 8570p             | [020c71d11e](https://linux-hardware.org/?probe=020c71d11e) | Apr 07, 2020 |
| HP        | EliteBook 8570p             | [163b885549](https://linux-hardware.org/?probe=163b885549) | Apr 07, 2020 |
| Sony      | VGN-NS140D                  | [dbae86d335](https://linux-hardware.org/?probe=dbae86d335) | Apr 06, 2020 |
| HP        | Pavilion Laptop 14-ce0xx... | [76c9608867](https://linux-hardware.org/?probe=76c9608867) | Mar 24, 2020 |
| HP        | Pavilion Laptop 14-ce0xx... | [81e20268cd](https://linux-hardware.org/?probe=81e20268cd) | Mar 24, 2020 |
| Fujitsu   | FARQ06012Z                  | [6d19311f7e](https://linux-hardware.org/?probe=6d19311f7e) | Mar 23, 2020 |
| HP        | EliteBook 820 G4            | [b525dfeb66](https://linux-hardware.org/?probe=b525dfeb66) | Mar 01, 2020 |
| HP        | EliteBook 820 G4            | [e28f1711fd](https://linux-hardware.org/?probe=e28f1711fd) | Mar 01, 2020 |
| CCE       | Capella & IbexPeak-M Chi... | [b6b6b3d6d5](https://linux-hardware.org/?probe=b6b6b3d6d5) | Mar 01, 2020 |
| HP        | ENVY 15                     | [a8fb8c36bf](https://linux-hardware.org/?probe=a8fb8c36bf) | Jan 22, 2020 |
| Acer      | P5WE0                       | [a3377994d6](https://linux-hardware.org/?probe=a3377994d6) | Jan 18, 2020 |
| HP        | 250 G5 Notebook PC          | [6882e04fe6](https://linux-hardware.org/?probe=6882e04fe6) | Jan 16, 2020 |
| Acer      | Nitro AN515-54              | [af36fc8a7c](https://linux-hardware.org/?probe=af36fc8a7c) | Jan 15, 2020 |
| Acer      | Nitro AN515-54              | [d96a34fd91](https://linux-hardware.org/?probe=d96a34fd91) | Jan 15, 2020 |
| Acer      | Nitro AN515-54              | [dbd7e76364](https://linux-hardware.org/?probe=dbd7e76364) | Jan 15, 2020 |
| HUAWEI    | HLY-WX9XX                   | [9f6e79326e](https://linux-hardware.org/?probe=9f6e79326e) | Jan 14, 2020 |
| Dell      | XPS 13 9360                 | [60888ae202](https://linux-hardware.org/?probe=60888ae202) | Jan 14, 2020 |
| Lenovo    | ThinkPad T420 4236CU8       | [0222255c98](https://linux-hardware.org/?probe=0222255c98) | Jan 12, 2020 |
| Toshiba   | Satellite L75-C             | [649fb9a60a](https://linux-hardware.org/?probe=649fb9a60a) | Jan 03, 2020 |
| Toshiba   | Satellite L75-C             | [2b66fb3c5e](https://linux-hardware.org/?probe=2b66fb3c5e) | Jan 03, 2020 |
| Toshiba   | Satellite C850-1H6          | [a0ffb29c6c](https://linux-hardware.org/?probe=a0ffb29c6c) | Dec 18, 2019 |
| Lenovo    | Unknown                     | [10ab399874](https://linux-hardware.org/?probe=10ab399874) | Dec 14, 2019 |
| Lenovo    | IdeaPad S145-15IWL 81S9     | [d1b18250b9](https://linux-hardware.org/?probe=d1b18250b9) | Dec 04, 2019 |
| BQ        | Tesla2 W10                  | [27f3692e24](https://linux-hardware.org/?probe=27f3692e24) | Dec 04, 2019 |
| BQ        | Tesla2 W10                  | [4c37070709](https://linux-hardware.org/?probe=4c37070709) | Dec 04, 2019 |
| HP        | Pavilion 15                 | [03188ddfb3](https://linux-hardware.org/?probe=03188ddfb3) | Dec 03, 2019 |
| HP        | Pavilion 15                 | [ae59f09d06](https://linux-hardware.org/?probe=ae59f09d06) | Nov 19, 2019 |
| Acer      | Aspire E5-571G              | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer      | Aspire E5-571G              | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| ASUSTek   | K501LX                      | [e90c15e3c9](https://linux-hardware.org/?probe=e90c15e3c9) | Nov 10, 2019 |
| Samsung   | 340XAA/350XAA/550XAA        | [997462e90b](https://linux-hardware.org/?probe=997462e90b) | Oct 19, 2019 |
| Sony      | SVF14A190X                  | [0b9bdec363](https://linux-hardware.org/?probe=0b9bdec363) | Oct 08, 2019 |
| Lenovo    | IdeaPad 120S-11IAP 81A4     | [c4f25ea846](https://linux-hardware.org/?probe=c4f25ea846) | Oct 07, 2019 |
| Gateway   | NE56R                       | [d0978555c2](https://linux-hardware.org/?probe=d0978555c2) | Sep 11, 2019 |
| Sony      | SVE14135CXP                 | [1b1819d6c0](https://linux-hardware.org/?probe=1b1819d6c0) | Aug 13, 2019 |
| Dell      | Inspiron 1428               | [d12daa7b97](https://linux-hardware.org/?probe=d12daa7b97) | Aug 01, 2019 |
| Dell      | Inspiron 1428               | [44b9085f50](https://linux-hardware.org/?probe=44b9085f50) | Aug 01, 2019 |
| Dell      | Inspiron 17 7000 Series ... | [37b056e670](https://linux-hardware.org/?probe=37b056e670) | Jul 23, 2019 |
| Timi      | TM1701                      | [cde89e0f6e](https://linux-hardware.org/?probe=cde89e0f6e) | Jun 13, 2019 |
| Dell      | Latitude E6420              | [c5063bb936](https://linux-hardware.org/?probe=c5063bb936) | May 12, 2019 |
| Dell      | Latitude E6420              | [9563d07d0a](https://linux-hardware.org/?probe=9563d07d0a) | May 12, 2019 |
| Acer      | Aspire 7741                 | [38acfde0bd](https://linux-hardware.org/?probe=38acfde0bd) | Apr 25, 2019 |
| ASUSTek   | N46VM                       | [c22250e143](https://linux-hardware.org/?probe=c22250e143) | Apr 25, 2019 |
| ASUSTek   | N46VM                       | [def5c1c07c](https://linux-hardware.org/?probe=def5c1c07c) | Apr 25, 2019 |
| Positivo  | C14CU51                     | [87fe4181bd](https://linux-hardware.org/?probe=87fe4181bd) | Apr 08, 2019 |
| HP        | Unknown                     | [53f0f72dd6](https://linux-hardware.org/?probe=53f0f72dd6) | Apr 02, 2019 |
| Sony      | VPCYB25AB                   | [035925b406](https://linux-hardware.org/?probe=035925b406) | Apr 01, 2019 |
| HP        | G42                         | [c0b7643d96](https://linux-hardware.org/?probe=c0b7643d96) | Mar 28, 2019 |
| HP        | Pavilion Notebook           | [53fb4de336](https://linux-hardware.org/?probe=53fb4de336) | Mar 27, 2019 |
| HP        | Pavilion Notebook           | [9a4cbb7444](https://linux-hardware.org/?probe=9a4cbb7444) | Mar 27, 2019 |
| Samsung   | 800G5M/800G5W               | [efdc2e3d09](https://linux-hardware.org/?probe=efdc2e3d09) | Mar 27, 2019 |
| HP        | EliteBook 840 G2            | [86742db945](https://linux-hardware.org/?probe=86742db945) | Mar 27, 2019 |
| Standard  | MB45II/MB45IN               | [5a6f9cc354](https://linux-hardware.org/?probe=5a6f9cc354) | Mar 27, 2019 |
| Lenovo    | IdeaPad 320-15IKB 80YH      | [619a0d9d90](https://linux-hardware.org/?probe=619a0d9d90) | Mar 27, 2019 |
| Lenovo    | G400s VILG1                 | [a18da046c8](https://linux-hardware.org/?probe=a18da046c8) | Mar 27, 2019 |
| Lenovo    | ThinkPad E450c 20EHA00NC... | [deac2364d1](https://linux-hardware.org/?probe=deac2364d1) | Jan 30, 2019 |
| Lenovo    | ThinkPad E450c 20EHA00NC... | [1629601591](https://linux-hardware.org/?probe=1629601591) | Jan 30, 2019 |
| Lenovo    | ThinkPad E450c 20EHA00NC... | [b314214e24](https://linux-hardware.org/?probe=b314214e24) | Dec 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Deepin         | 29        | 22.66%  |
| Deepin 15.11   | 23        | 17.97%  |
| Deepin 20      | 20        | 15.63%  |
| UOS 20         | 9         | 7.03%   |
| Deepin 15.9.2  | 8         | 6.25%   |
| Deepin 20.8    | 6         | 4.69%   |
| Deepin 20.3    | 5         | 3.91%   |
| Deepin 20.5    | 4         | 3.13%   |
| Deepin 20.1    | 4         | 3.13%   |
| Deepin 23      | 3         | 2.34%   |
| Deepin 20 beta | 3         | 2.34%   |
| Deepin 20.2.4  | 2         | 1.56%   |
| Deepin 15.9.3  | 2         | 1.56%   |
| Deepin 2014.3  | 1         | 0.78%   |
| Deepin 20.7.1  | 1         | 0.78%   |
| Deepin 20.7    | 1         | 0.78%   |
| Deepin 20.4    | 1         | 0.78%   |
| Deepin 20.2.3  | 1         | 0.78%   |
| Deepin 20.2.1  | 1         | 0.78%   |
| Deepin 15.9    | 1         | 0.78%   |
| Deepin 15.8    | 1         | 0.78%   |
| Deepin 15.10.1 | 1         | 0.78%   |
| Deepin 15.10   | 1         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Deepin | 123       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.15.0-30deepin-generic             | 32        | 25.2%   |
| 5.4.50-amd64-desktop                | 16        | 12.6%   |
| 4.15.0-29deepin-generic             | 12        | 9.45%   |
| 5.4.70-amd64-desktop                | 9         | 7.09%   |
| 5.10.60-amd64-desktop               | 9         | 7.09%   |
| 5.7.7-amd64-desktop                 | 4         | 3.15%   |
| 5.18.17-amd64-desktop-community-hwe | 4         | 3.15%   |
| 5.10.41-amd64-desktop               | 4         | 3.15%   |
| 5.10.29-amd64-desktop               | 4         | 3.15%   |
| 5.3.0-3-amd64                       | 3         | 2.36%   |
| 5.15.1-amd64-desktop                | 3         | 2.36%   |
| 5.18.17-amd64-desktop-hwe           | 2         | 1.57%   |
| 5.15.77-amd64-desktop               | 2         | 1.57%   |
| 5.15.24-amd64-desktop               | 2         | 1.57%   |
| 5.10.50-amd64-desktop               | 2         | 1.57%   |
| 5.10.5-amd64-desktop+               | 2         | 1.57%   |
| 5.10.18-amd64-desktop               | 2         | 1.57%   |
| 5.10.101-amd64-desktop              | 2         | 1.57%   |
| 5.10.0-amd64-desktop                | 2         | 1.57%   |
| 5.8.14-amd64-desktop                | 1         | 0.79%   |
| 5.6.14-050614-generic               | 1         | 0.79%   |
| 5.6.12-xanmod1                      | 1         | 0.79%   |
| 5.5.4-xanmod3                       | 1         | 0.79%   |
| 5.3.8-xanmod6                       | 1         | 0.79%   |
| 5.15.45-amd64-desktop               | 1         | 0.79%   |
| 5.10.83-amd64-desktop               | 1         | 0.79%   |
| 5.10.36-amd64-desktop               | 1         | 0.79%   |
| 5.1.0-050100rc2-generic             | 1         | 0.79%   |
| 4.19.0-amd64-desktop                | 1         | 0.79%   |
| 4.15.0-135-generic                  | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 45        | 35.43%  |
| 5.4.50   | 16        | 12.6%   |
| 5.4.70   | 9         | 7.09%   |
| 5.10.60  | 9         | 7.09%   |
| 5.18.17  | 6         | 4.72%   |
| 5.7.7    | 4         | 3.15%   |
| 5.10.41  | 4         | 3.15%   |
| 5.10.29  | 4         | 3.15%   |
| 5.3.0    | 3         | 2.36%   |
| 5.15.1   | 3         | 2.36%   |
| 5.15.77  | 2         | 1.57%   |
| 5.15.24  | 2         | 1.57%   |
| 5.10.50  | 2         | 1.57%   |
| 5.10.5   | 2         | 1.57%   |
| 5.10.18  | 2         | 1.57%   |
| 5.10.101 | 2         | 1.57%   |
| 5.10.0   | 2         | 1.57%   |
| 5.8.14   | 1         | 0.79%   |
| 5.6.14   | 1         | 0.79%   |
| 5.6.12   | 1         | 0.79%   |
| 5.5.4    | 1         | 0.79%   |
| 5.3.8    | 1         | 0.79%   |
| 5.15.45  | 1         | 0.79%   |
| 5.10.83  | 1         | 0.79%   |
| 5.10.36  | 1         | 0.79%   |
| 5.1.0    | 1         | 0.79%   |
| 4.19.0   | 1         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15    | 45        | 35.71%  |
| 5.10    | 29        | 23.02%  |
| 5.4     | 25        | 19.84%  |
| 5.15    | 7         | 5.56%   |
| 5.18    | 6         | 4.76%   |
| 5.7     | 4         | 3.17%   |
| 5.3     | 4         | 3.17%   |
| 5.6     | 2         | 1.59%   |
| 5.8     | 1         | 0.79%   |
| 5.5     | 1         | 0.79%   |
| 5.1     | 1         | 0.79%   |
| 4.19    | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 123       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Deepin  | 102       | 82.93%  |
| Unknown | 20        | 16.26%  |
| KDE     | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 123       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 54        | 43.2%   |
| TDM     | 39        | 31.2%   |
| LightDM | 32        | 25.6%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 30        | 24.39%  |
| en_US   | 24        | 19.51%  |
| zh_CN   | 16        | 13.01%  |
| pt_BR   | 15        | 12.2%   |
| es_ES   | 11        | 8.94%   |
| de_DE   | 9         | 7.32%   |
| ru_RU   | 7         | 5.69%   |
| it_IT   | 3         | 2.44%   |
| tr_TR   | 2         | 1.63%   |
| pl_PL   | 2         | 1.63%   |
| sv_SE   | 1         | 0.81%   |
| ja_JP   | 1         | 0.81%   |
| fr_FR   | 1         | 0.81%   |
| en_GB   | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 79        | 63.71%  |
| BIOS | 45        | 36.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 109       | 88.62%  |
| Unknown | 14        | 11.38%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 58        | 46.77%  |
| Unknown | 53        | 42.74%  |
| MBR     | 13        | 10.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 79.84%  |
| Yes       | 25        | 20.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 71.77%  |
| Yes       | 35        | 28.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 33        | 26.83%  |
| Hewlett-Packard     | 21        | 17.07%  |
| Acer                | 14        | 11.38%  |
| Dell                | 12        | 9.76%   |
| Samsung Electronics | 7         | 5.69%   |
| ASUSTek Computer    | 7         | 5.69%   |
| Sony                | 5         | 4.07%   |
| HUAWEI              | 5         | 4.07%   |
| Toshiba             | 4         | 3.25%   |
| Timi                | 2         | 1.63%   |
| Google              | 2         | 1.63%   |
| Unknown             | 2         | 1.63%   |
| Standard            | 1         | 0.81%   |
| Positivo            | 1         | 0.81%   |
| Microtech           | 1         | 0.81%   |
| Infinix             | 1         | 0.81%   |
| Gateway             | 1         | 0.81%   |
| Fujitsu             | 1         | 0.81%   |
| Chuwi               | 1         | 0.81%   |
| CCE                 | 1         | 0.81%   |
| BQ                  | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 4         | 3.25%   |
| Samsung 340XAA/350XAA/550XAA                      | 2         | 1.63%   |
| Lenovo IdeaPad 120S-11IAP 81A4                    | 2         | 1.63%   |
| HP Pavilion Notebook                              | 2         | 1.63%   |
| HP Pavilion 15                                    | 2         | 1.63%   |
| HP ENVY 15                                        | 2         | 1.63%   |
| Acer Nitro AN515-54                               | 2         | 1.63%   |
| Toshiba Satellite L75-C                           | 1         | 0.81%   |
| Toshiba Satellite E55t-A                          | 1         | 0.81%   |
| Toshiba Satellite C850D-11K                       | 1         | 0.81%   |
| Toshiba Satellite C850-1H6                        | 1         | 0.81%   |
| Timi TM1701                                       | 1         | 0.81%   |
| Timi Redmi G 2022                                 | 1         | 0.81%   |
| Standard MB45II/MB45IN                            | 1         | 0.81%   |
| Sony VPCYB25AB                                    | 1         | 0.81%   |
| Sony VGN-NS140D                                   | 1         | 0.81%   |
| Sony VGN-AW11Z_B                                  | 1         | 0.81%   |
| Sony SVF14A190X                                   | 1         | 0.81%   |
| Sony SVE14135CXP                                  | 1         | 0.81%   |
| Samsung 800G5M/800G5W                             | 1         | 0.81%   |
| Samsung 550P5C/550P7C                             | 1         | 0.81%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.81%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 1         | 0.81%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.81%   |
| Positivo C14CU51                                  | 1         | 0.81%   |
| Microtech ebookPro                                | 1         | 0.81%   |
| Lenovo ZHAOYANG K4e-ITL 82F8                      | 1         | 0.81%   |
| Lenovo ZHAOYANG CF4620Z-A123 59082537             | 1         | 0.81%   |
| Lenovo Yoga 3 Pro-1370 80HE                       | 1         | 0.81%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN                 | 1         | 0.81%   |
| Lenovo XiaoXin-15ARE 2020 81YR                    | 1         | 0.81%   |
| Lenovo V310-15ISK 80SY                            | 1         | 0.81%   |
| Lenovo ThinkPad T420 4236CU8                      | 1         | 0.81%   |
| Lenovo ThinkPad T420 4180M8P                      | 1         | 0.81%   |
| Lenovo ThinkPad T14 Gen 1 20UD003SRT              | 1         | 0.81%   |
| Lenovo ThinkPad L512 44444NG                      | 1         | 0.81%   |
| Lenovo ThinkPad L412 0585AC3                      | 1         | 0.81%   |
| Lenovo ThinkPad E585 20KV0010US                   | 1         | 0.81%   |
| Lenovo ThinkPad E450c 20EHA00NCD                  | 1         | 0.81%   |
| Lenovo ThinkPad E14 20RA0058VA                    | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 8         | 6.5%    |
| Lenovo IdeaPad          | 8         | 6.5%    |
| Dell Inspiron           | 8         | 6.5%    |
| Acer Aspire             | 8         | 6.5%    |
| HP Pavilion             | 5         | 4.07%   |
| HP EliteBook            | 5         | 4.07%   |
| Toshiba Satellite       | 4         | 3.25%   |
| Lenovo Legion           | 4         | 3.25%   |
| HP Laptop               | 4         | 3.25%   |
| Unknown                 | 4         | 3.25%   |
| Lenovo ThinkBook        | 3         | 2.44%   |
| Acer Nitro              | 3         | 2.44%   |
| Samsung 340XAA          | 2         | 1.63%   |
| Lenovo ZHAOYANG         | 2         | 1.63%   |
| HP ENVY                 | 2         | 1.63%   |
| Dell Latitude           | 2         | 1.63%   |
| Acer Swift              | 2         | 1.63%   |
| Timi TM1701             | 1         | 0.81%   |
| Timi Redmi              | 1         | 0.81%   |
| Standard MB45II         | 1         | 0.81%   |
| Sony VPCYB25AB          | 1         | 0.81%   |
| Sony VGN-NS140D         | 1         | 0.81%   |
| Sony VGN-AW11Z          | 1         | 0.81%   |
| Sony SVF14A190X         | 1         | 0.81%   |
| Sony SVE14135CXP        | 1         | 0.81%   |
| Samsung 800G5M          | 1         | 0.81%   |
| Samsung 550P5C          | 1         | 0.81%   |
| Samsung 500R4K          | 1         | 0.81%   |
| Samsung 300E4A          | 1         | 0.81%   |
| Samsung 270E5J          | 1         | 0.81%   |
| Positivo C14CU51        | 1         | 0.81%   |
| Microtech ebookPro      | 1         | 0.81%   |
| Lenovo Yoga             | 1         | 0.81%   |
| Lenovo XiaoXinAir-14ARE | 1         | 0.81%   |
| Lenovo XiaoXin-15ARE    | 1         | 0.81%   |
| Lenovo V310-15ISK       | 1         | 0.81%   |
| Lenovo G50-80           | 1         | 0.81%   |
| Lenovo G50-70           | 1         | 0.81%   |
| Lenovo G400s            | 1         | 0.81%   |
| Infinix INBOOK          | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 17        | 13.82%  |
| 2017    | 13        | 10.57%  |
| 2018    | 12        | 9.76%   |
| 2012    | 10        | 8.13%   |
| 2021    | 8         | 6.5%    |
| 2020    | 8         | 6.5%    |
| 2015    | 8         | 6.5%    |
| 2014    | 8         | 6.5%    |
| 2013    | 8         | 6.5%    |
| 2011    | 7         | 5.69%   |
| 2010    | 7         | 5.69%   |
| 2016    | 6         | 4.88%   |
| 2022    | 5         | 4.07%   |
| 2009    | 4         | 3.25%   |
| 2008    | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 123       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 114       | 92.68%  |
| Enabled  | 9         | 7.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 121       | 98.37%  |
| Yes  | 2         | 1.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 47        | 38.21%  |
| 8.01-16.0   | 28        | 22.76%  |
| 3.01-4.0    | 24        | 19.51%  |
| 16.01-24.0  | 14        | 11.38%  |
| 32.01-64.0  | 4         | 3.25%   |
| 1.01-2.0    | 4         | 3.25%   |
| 2.01-3.0    | 1         | 0.81%   |
| 64.01-256.0 | 1         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 42        | 33.07%  |
| 2.01-3.0  | 41        | 32.28%  |
| 3.01-4.0  | 17        | 13.39%  |
| 4.01-8.0  | 16        | 12.6%   |
| 0.51-1.0  | 8         | 6.3%    |
| 8.01-16.0 | 3         | 2.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 93        | 74.4%   |
| 2      | 31        | 24.8%   |
| 3      | 1         | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 63.41%  |
| Yes       | 45        | 36.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 76.42%  |
| No        | 29        | 23.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 98.37%  |
| No        | 2         | 1.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 82.11%  |
| No        | 22        | 17.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| Brazil                | 31        | 25%     |
| China                 | 19        | 15.32%  |
| Germany               | 9         | 7.26%   |
| USA                   | 5         | 4.03%   |
| Spain                 | 5         | 4.03%   |
| Turkey                | 4         | 3.23%   |
| Russia                | 4         | 3.23%   |
| Indonesia             | 4         | 3.23%   |
| Poland                | 3         | 2.42%   |
| Japan                 | 3         | 2.42%   |
| Italy                 | 3         | 2.42%   |
| Chile                 | 3         | 2.42%   |
| Panama                | 2         | 1.61%   |
| Canada                | 2         | 1.61%   |
| Bulgaria              | 2         | 1.61%   |
| Austria               | 2         | 1.61%   |
| Venezuela             | 1         | 0.81%   |
| Tunisia               | 1         | 0.81%   |
| Sweden                | 1         | 0.81%   |
| South Africa          | 1         | 0.81%   |
| Singapore             | 1         | 0.81%   |
| Serbia                | 1         | 0.81%   |
| Sao Tome and Principe | 1         | 0.81%   |
| Portugal              | 1         | 0.81%   |
| Pakistan              | 1         | 0.81%   |
| Mexico                | 1         | 0.81%   |
| Kenya                 | 1         | 0.81%   |
| Iran                  | 1         | 0.81%   |
| India                 | 1         | 0.81%   |
| Greece                | 1         | 0.81%   |
| France                | 1         | 0.81%   |
| Ecuador               | 1         | 0.81%   |
| Czechia               | 1         | 0.81%   |
| Cuba                  | 1         | 0.81%   |
| Colombia              | 1         | 0.81%   |
| Belarus               | 1         | 0.81%   |
| Bangladesh            | 1         | 0.81%   |
| Australia             | 1         | 0.81%   |
| Argentina             | 1         | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Guangzhou        | 3         | 2.42%   |
| Curitiba         | 3         | 2.42%   |
| Beijing          | 3         | 2.42%   |
| Wuhan            | 2         | 1.61%   |
| Uberlândia      | 2         | 1.61%   |
| Surabaya         | 2         | 1.61%   |
| Sao Paulo        | 2         | 1.61%   |
| Petrópolis      | 2         | 1.61%   |
| Londrina         | 2         | 1.61%   |
| Innsbruck        | 2         | 1.61%   |
| David            | 2         | 1.61%   |
| Atlanta          | 2         | 1.61%   |
| Yozgat           | 1         | 0.81%   |
| Yogyakarta       | 1         | 0.81%   |
| Xuhui            | 1         | 0.81%   |
| Voronezh         | 1         | 0.81%   |
| Villa Ballester  | 1         | 0.81%   |
| Vigo             | 1         | 0.81%   |
| Ufa              | 1         | 0.81%   |
| Tomsk            | 1         | 0.81%   |
| Tokyo            | 1         | 0.81%   |
| Tianjin          | 1         | 0.81%   |
| TehrДЃn        | 1         | 0.81%   |
| Taiyuan          | 1         | 0.81%   |
| Tai'an           | 1         | 0.81%   |
| SГЈo TomГ©   | 1         | 0.81%   |
| Suzano           | 1         | 0.81%   |
| Singapore        | 1         | 0.81%   |
| Shanghai         | 1         | 0.81%   |
| Sao Carlos       | 1         | 0.81%   |
| Sao Bento do Sul | 1         | 0.81%   |
| Santiago         | 1         | 0.81%   |
| Samara           | 1         | 0.81%   |
| Saitama          | 1         | 0.81%   |
| Rzeszów         | 1         | 0.81%   |
| Rotenburg        | 1         | 0.81%   |
| Poznan           | 1         | 0.81%   |
| Portoviejo       | 1         | 0.81%   |
| Porto Velho      | 1         | 0.81%   |
| Plovdiv          | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 22        | 25     | 14.19%  |
| WDC                            | 21        | 24     | 13.55%  |
| Samsung Electronics            | 16        | 18     | 10.32%  |
| Unknown                        | 12        | 12     | 7.74%   |
| Toshiba                        | 12        | 13     | 7.74%   |
| SanDisk                        | 9         | 9      | 5.81%   |
| SK hynix                       | 8         | 8      | 5.16%   |
| Kingston                       | 8         | 9      | 5.16%   |
| Micron Technology              | 6         | 8      | 3.87%   |
| Intel                          | 5         | 6      | 3.23%   |
| HGST                           | 5         | 5      | 3.23%   |
| Hitachi                        | 4         | 4      | 2.58%   |
| LITEON                         | 3         | 3      | 1.94%   |
| Crucial                        | 3         | 3      | 1.94%   |
| SPCC                           | 2         | 3      | 1.29%   |
| Silicon Motion                 | 2         | 2      | 1.29%   |
| China                          | 2         | 2      | 1.29%   |
| V-GeN                          | 1         | 1      | 0.65%   |
| Transcend                      | 1         | 1      | 0.65%   |
| Solid State Storage Technology | 1         | 1      | 0.65%   |
| Phison                         | 1         | 1      | 0.65%   |
| OEM                            | 1         | 1      | 0.65%   |
| OCZ                            | 1         | 1      | 0.65%   |
| Netac                          | 1         | 1      | 0.65%   |
| Microtech                      | 1         | 1      | 0.65%   |
| KingSpec                       | 1         | 1      | 0.65%   |
| JMicron Technology             | 1         | 1      | 0.65%   |
| Intenso                        | 1         | 1      | 0.65%   |
| Fujitsu                        | 1         | 2      | 0.65%   |
| FORESEE                        | 1         | 1      | 0.65%   |
| ADATA Technology               | 1         | 1      | 0.65%   |
| A-DATA Technology              | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 3.77%   |
| Toshiba MQ01ABF050 500GB             | 4         | 2.52%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 2.52%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.89%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 1.26%   |
| Unknown MMC Card                     | 2         | 1.26%   |
| Seagate ST9320325AS 320GB            | 2         | 1.26%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 1.26%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 1.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.26%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.26%   |
| HGST HTS545050A7E680 500GB           | 2         | 1.26%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 1.26%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.63%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.63%   |
| WDC WD7500BPVT-24HXZT3 752GB         | 1         | 0.63%   |
| WDC WD5000LPZX-75Z10T0 500GB         | 1         | 0.63%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.63%   |
| WDC WD5000LPVX-08V0TT6 500GB         | 1         | 0.63%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.63%   |
| WDC WD3200BEVT-60A23T0 320GB         | 1         | 0.63%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.63%   |
| WDC WD3200BEVT-08A23T1 320GB         | 1         | 0.63%   |
| WDC WD10SPZX-35Z10T0 1TB             | 1         | 0.63%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.63%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.63%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.63%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.63%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.63%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.63%   |
| WDC PC SN720 SDAPNTW-512G-1127 512GB | 1         | 0.63%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.63%   |
| WDC PC SN520 NVMe 256GB              | 1         | 0.63%   |
| V-GeN V-GEN10SM19AR120SDK 120GB SSD  | 1         | 0.63%   |
| Unknown SSO256GTLC9-SB3-4L 256GB SSD | 1         | 0.63%   |
| Unknown NVMe SSD Drive 512GB         | 1         | 0.63%   |
| Unknown MMC Card  64GB               | 1         | 0.63%   |
| Unknown MMC Card  32GB               | 1         | 0.63%   |
| Unknown MMC Card  16GB               | 1         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 25     | 35.48%  |
| WDC                 | 17        | 18     | 27.42%  |
| Toshiba             | 11        | 12     | 17.74%  |
| HGST                | 5         | 5      | 8.06%   |
| Hitachi             | 4         | 4      | 6.45%   |
| Samsung Electronics | 1         | 1      | 1.61%   |
| OEM                 | 1         | 1      | 1.61%   |
| Fujitsu             | 1         | 2      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 8      | 17.78%  |
| Kingston            | 7         | 8      | 15.56%  |
| Samsung Electronics | 6         | 7      | 13.33%  |
| WDC                 | 2         | 2      | 4.44%   |
| SPCC                | 2         | 3      | 4.44%   |
| SK hynix            | 2         | 2      | 4.44%   |
| Micron Technology   | 2         | 3      | 4.44%   |
| LITEON              | 2         | 2      | 4.44%   |
| Crucial             | 2         | 2      | 4.44%   |
| China               | 2         | 2      | 4.44%   |
| V-GeN               | 1         | 1      | 2.22%   |
| Unknown             | 1         | 1      | 2.22%   |
| Transcend           | 1         | 1      | 2.22%   |
| OCZ                 | 1         | 1      | 2.22%   |
| Netac               | 1         | 1      | 2.22%   |
| Microtech           | 1         | 1      | 2.22%   |
| KingSpec            | 1         | 1      | 2.22%   |
| JMicron Technology  | 1         | 1      | 2.22%   |
| Intenso             | 1         | 1      | 2.22%   |
| Intel               | 1         | 2      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 61        | 68     | 40.67%  |
| SSD  | 41        | 50     | 27.33%  |
| NVMe | 38        | 41     | 25.33%  |
| MMC  | 10        | 11     | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 113    | 62.59%  |
| NVMe | 38        | 41     | 27.34%  |
| MMC  | 10        | 11     | 7.19%   |
| SAS  | 4         | 5      | 2.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 60        | 76     | 62.5%   |
| 0.51-1.0   | 33        | 37     | 34.38%  |
| 1.01-2.0   | 2         | 4      | 2.08%   |
| 4.01-10.0  | 1         | 1      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 43        | 33.86%  |
| 101-250        | 35        | 27.56%  |
| 501-1000       | 25        | 19.69%  |
| 1001-2000      | 9         | 7.09%   |
| More than 3000 | 4         | 3.15%   |
| 21-50          | 4         | 3.15%   |
| 51-100         | 3         | 2.36%   |
| Unknown        | 3         | 2.36%   |
| 2001-3000      | 1         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 30        | 23.81%  |
| 1-20      | 29        | 23.02%  |
| 101-250   | 21        | 16.67%  |
| 51-100    | 18        | 14.29%  |
| 251-500   | 14        | 11.11%  |
| 501-1000  | 6         | 4.76%   |
| 1001-2000 | 3         | 2.38%   |
| Unknown   | 3         | 2.38%   |
| 2001-3000 | 2         | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                     | 2         | 2      | 16.67%  |
| WDC WD10JPVX-22JC3T0 1TB                      | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD032 320GB                      | 1         | 1      | 8.33%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB       | 1         | 1      | 8.33%   |
| Seagate ST1000LM049-2GH172 1TB                | 1         | 1      | 8.33%   |
| Samsung Electronics HM250HI 250GB             | 1         | 1      | 8.33%   |
| OCZ VERTEX4 256GB SSD                         | 1         | 1      | 8.33%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 2      | 8.33%   |
| Intenso lntenso SSD Sata III 128GB            | 1         | 1      | 8.33%   |
| Hitachi HTS543225L9A300 250GB                 | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 25%     |
| Toshiba             | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| SK hynix            | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| OCZ                 | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 2      | 8.33%   |
| Intenso             | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 37.5%   |
| Toshiba             | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 66.67%  |
| SSD  | 3         | 4      | 25%     |
| NVMe | 1         | 1      | 8.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba MK5065GSXN 500GB | 1         | 1      | 100%    |

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
| Detected | 65        | 90     | 49.24%  |
| Works    | 54        | 66     | 40.91%  |
| Malfunc  | 12        | 13     | 9.09%   |
| Failed   | 1         | 1      | 0.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 90        | 65.69%  |
| AMD                            | 10        | 7.3%    |
| Samsung Electronics            | 9         | 6.57%   |
| SK hynix                       | 6         | 4.38%   |
| SanDisk                        | 4         | 2.92%   |
| Micron Technology              | 4         | 2.92%   |
| Silicon Motion                 | 2         | 1.46%   |
| Zhaoxin                        | 1         | 0.73%   |
| Solid State Storage Technology | 1         | 0.73%   |
| Shenzhen Longsys Electronics   | 1         | 0.73%   |
| Realtek Semiconductor          | 1         | 0.73%   |
| Phison Electronics             | 1         | 0.73%   |
| Micron/Crucial Technology      | 1         | 0.73%   |
| Lite-On Technology             | 1         | 0.73%   |
| KIOXIA                         | 1         | 0.73%   |
| Kingston Technology Company    | 1         | 0.73%   |
| JMicron Technology             | 1         | 0.73%   |
| ADATA Technology               | 1         | 0.73%   |
| Unknown                        | 1         | 0.73%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 9.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 8.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 7.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 6.99%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 6.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 4.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 3.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 3.5%    |
| Micron NVMe Storage Controller                                                   | 4         | 2.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 2.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.8%    |
| SK hynix BC511                                                                   | 3         | 2.1%    |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.1%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 1.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 1.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.4%    |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G StorX AHCI Controller                     | 1         | 0.7%    |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.7%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.7%    |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 1         | 0.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.7%    |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.7%    |
| SanDisk NVMe Controller                                                          | 1         | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.7%    |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.7%    |
| Realtek NVMe Controller                                                          | 1         | 0.7%    |
| Phison Electronics Non-Volatile memory controller                                | 1         | 0.7%    |
| Micron/Crucial NVMe Storage Controller                                           | 1         | 0.7%    |
| Lite-On Non-Volatile memory controller                                           | 1         | 0.7%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.7%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.7%    |
| JMicron JMB368 IDE controller                                                    | 1         | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 93        | 66.43%  |
| NVMe | 37        | 26.43%  |
| RAID | 6         | 4.29%   |
| IDE  | 4         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 101       | 82.11%  |
| AMD          | 21        | 17.07%  |
| CentaurHauls | 1         | 0.81%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 4.07%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 3.25%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 3.25%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.44%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 2.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.44%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.63%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.63%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.63%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.63%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.63%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.63%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.63%   |
| AMD Ryzen 5 4600U with Radeon Graphics        | 2         | 1.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.63%   |
| AMD 3020e with Radeon Graphics                | 2         | 1.63%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.81%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.81%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.81%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.81%   |
| Intel Core M-5Y71 CPU @ 1.20GHz               | 1         | 0.81%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.81%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.81%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.81%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.81%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.81%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.81%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 28.46%  |
| Intel Core i7           | 27        | 21.95%  |
| Intel Core i3           | 10        | 8.13%   |
| Other                   | 9         | 7.32%   |
| Intel Celeron           | 7         | 5.69%   |
| AMD Ryzen 7             | 6         | 4.88%   |
| AMD Ryzen 5             | 6         | 4.88%   |
| Intel Pentium Dual-Core | 3         | 2.44%   |
| Intel Core 2 Duo        | 3         | 2.44%   |
| Intel Atom              | 3         | 2.44%   |
| Intel Pentium           | 2         | 1.63%   |
| AMD Ryzen 3             | 2         | 1.63%   |
| AMD A10                 | 2         | 1.63%   |
| Intel Pentium Silver    | 1         | 0.81%   |
| Intel Core m3           | 1         | 0.81%   |
| Intel Core M            | 1         | 0.81%   |
| Intel Core i9           | 1         | 0.81%   |
| Intel Celeron Dual-Core | 1         | 0.81%   |
| AMD Ryzen 5 PRO         | 1         | 0.81%   |
| AMD E1                  | 1         | 0.81%   |
| AMD E                   | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 69        | 56.1%   |
| 4      | 39        | 31.71%  |
| 6      | 6         | 4.88%   |
| 8      | 5         | 4.07%   |
| 12     | 2         | 1.63%   |
| 10     | 1         | 0.81%   |
| 1      | 1         | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 123       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 95        | 77.24%  |
| 1      | 28        | 22.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 112       | 91.06%  |
| Unknown        | 11        | 8.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 19.35%  |
| 0x306a9    | 10        | 8.06%   |
| 0x40651    | 9         | 7.26%   |
| 0x806ec    | 8         | 6.45%   |
| 0x806e9    | 7         | 5.65%   |
| 0x306d4    | 7         | 5.65%   |
| 0x206a7    | 6         | 4.84%   |
| 0x906ea    | 5         | 4.03%   |
| 0x406e3    | 5         | 4.03%   |
| 0x906a3    | 3         | 2.42%   |
| 0x806ea    | 3         | 2.42%   |
| 0x1067a    | 3         | 2.42%   |
| 0x08600106 | 3         | 2.42%   |
| 0x806c1    | 2         | 1.61%   |
| 0x406c4    | 2         | 1.61%   |
| 0x20655    | 2         | 1.61%   |
| 0x08600104 | 2         | 1.61%   |
| 0x08200103 | 2         | 1.61%   |
| 0x08108109 | 2         | 1.61%   |
| 0x08108102 | 2         | 1.61%   |
| 0xa0652    | 1         | 0.81%   |
| 0x906e9    | 1         | 0.81%   |
| 0x806c2    | 1         | 0.81%   |
| 0x706a1    | 1         | 0.81%   |
| 0x6fd      | 1         | 0.81%   |
| 0x406c3    | 1         | 0.81%   |
| 0x30678    | 1         | 0.81%   |
| 0x10676    | 1         | 0.81%   |
| 0x0a50000c | 1         | 0.81%   |
| 0x0a50000b | 1         | 0.81%   |
| 0x0a404101 | 1         | 0.81%   |
| 0x08600103 | 1         | 0.81%   |
| 0x08600102 | 1         | 0.81%   |
| 0x0810100b | 1         | 0.81%   |
| 0x06006115 | 1         | 0.81%   |
| 0x0500010d | 1         | 0.81%   |
| 0x05000029 | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 22.76%  |
| IvyBridge        | 13        | 10.57%  |
| Haswell          | 11        | 8.94%   |
| Broadwell        | 10        | 8.13%   |
| Zen 2            | 7         | 5.69%   |
| SandyBridge      | 7         | 5.69%   |
| Silvermont       | 6         | 4.88%   |
| Penryn           | 6         | 4.88%   |
| Skylake          | 5         | 4.07%   |
| Zen+             | 4         | 3.25%   |
| Zen              | 3         | 2.44%   |
| Westmere         | 3         | 2.44%   |
| TigerLake        | 3         | 2.44%   |
| Alderlake Hybrid | 3         | 2.44%   |
| Zen 3            | 2         | 1.63%   |
| Goldmont plus    | 2         | 1.63%   |
| Goldmont         | 2         | 1.63%   |
| Excavator        | 2         | 1.63%   |
| Bobcat           | 2         | 1.63%   |
| Unknown          | 2         | 1.63%   |
| Core             | 1         | 0.81%   |
| CometLake        | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 99        | 58.93%  |
| Nvidia  | 42        | 25%     |
| AMD     | 26        | 15.48%  |
| Zhaoxin | 1         | 0.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 7.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 6.47%   |
| Intel HD Graphics 5500                                                                   | 9         | 5.29%   |
| Intel HD Graphics 620                                                                    | 8         | 4.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.12%   |
| AMD Renoir                                                                               | 7         | 4.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 3.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.53%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 3.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 3.53%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.18%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.18%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 1.18%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.18%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.18%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1.18%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 1.18%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.18%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 1.18%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                                 | 2         | 1.18%   |
| Intel HD Graphics 500                                                                    | 2         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.18%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.18%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.18%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 0.59%   |
| Nvidia TU117M                                                                            | 1         | 0.59%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.59%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.59%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.59%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 45.53%  |
| Intel + Nvidia | 37        | 30.08%  |
| 1 x AMD        | 16        | 13.01%  |
| Intel + AMD    | 6         | 4.88%   |
| 1 x Nvidia     | 3         | 2.44%   |
| 2 x AMD        | 2         | 1.63%   |
| AMD + Nvidia   | 2         | 1.63%   |
| 1 x Zhaoxin    | 1         | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 100       | 81.3%   |
| Proprietary | 18        | 14.63%  |
| Unknown     | 5         | 4.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 53.6%   |
| 1.01-2.0   | 29        | 23.2%   |
| 3.01-4.0   | 15        | 12%     |
| 0.01-0.5   | 10        | 8%      |
| 0.51-1.0   | 3         | 2.4%    |
| 5.01-6.0   | 1         | 0.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 21.88%  |
| BOE                     | 26        | 20.31%  |
| Chimei Innolux          | 17        | 13.28%  |
| LG Display              | 16        | 12.5%   |
| Samsung Electronics     | 14        | 10.94%  |
| CSO                     | 4         | 3.13%   |
| Hewlett-Packard         | 3         | 2.34%   |
| Lenovo                  | 2         | 1.56%   |
| InfoVision              | 2         | 1.56%   |
| Goldstar                | 2         | 1.56%   |
| Chi Mei Optoelectronics | 2         | 1.56%   |
| AOC                     | 2         | 1.56%   |
| ViewSonic               | 1         | 0.78%   |
| TMX                     | 1         | 0.78%   |
| Sharp                   | 1         | 0.78%   |
| SAC                     | 1         | 0.78%   |
| PANDA                   | 1         | 0.78%   |
| Iiyama                  | 1         | 0.78%   |
| HB@                     | 1         | 0.78%   |
| HannStar                | 1         | 0.78%   |
| Dell                    | 1         | 0.78%   |
| BenQ                    | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 2.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 2.33%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 2         | 1.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.55%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.55%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.55%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 1.55%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 2         | 1.55%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch             | 1         | 0.78%   |
| TMX TL140VDXP03-2 TMX1398 1920x1080 309x174mm 14.0-inch               | 1         | 0.78%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0167 1280x1024 338x270mm 17.0-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC534B 1600x900 382x215mm 17.3-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4147 3840x2160 294x165mm 13.3-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                     | 1         | 0.78%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                 | 1         | 0.78%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.78%   |
| LG Display LP156WH1-TLA1 LGD6301 1366x768 344x194mm 15.5-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 51        | 42.15%  |
| 1920x1080 (FHD)  | 50        | 41.32%  |
| 1600x900 (HD+)   | 6         | 4.96%   |
| 3840x2160 (4K)   | 2         | 1.65%   |
| 2560x1600        | 2         | 1.65%   |
| 3440x1440        | 1         | 0.83%   |
| 3200x1800 (QHD+) | 1         | 0.83%   |
| 3000x2000        | 1         | 0.83%   |
| 2880x1800        | 1         | 0.83%   |
| 2560x1440 (QHD)  | 1         | 0.83%   |
| 2160x1440        | 1         | 0.83%   |
| 1920x540         | 1         | 0.83%   |
| 1680x945         | 1         | 0.83%   |
| 1280x800 (WXGA)  | 1         | 0.83%   |
| 1280x1024 (SXGA) | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 55        | 42.97%  |
| 13      | 25        | 19.53%  |
| 14      | 21        | 16.41%  |
| 17      | 4         | 3.13%   |
| 23      | 3         | 2.34%   |
| 18      | 3         | 2.34%   |
| 11      | 3         | 2.34%   |
| 32      | 2         | 1.56%   |
| 27      | 2         | 1.56%   |
| 21      | 2         | 1.56%   |
| 16      | 2         | 1.56%   |
| 12      | 2         | 1.56%   |
| 40      | 1         | 0.78%   |
| 25      | 1         | 0.78%   |
| 24      | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 93        | 74.4%   |
| 201-300     | 13        | 10.4%   |
| 501-600     | 6         | 4.8%    |
| 351-400     | 5         | 4%      |
| 401-500     | 4         | 3.2%    |
| 701-800     | 2         | 1.6%    |
| 801-900     | 1         | 0.8%    |
| Unknown     | 1         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 109       | 92.37%  |
| 16/10 | 5         | 4.24%   |
| 3/2   | 3         | 2.54%   |
| 5/4   | 1         | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 55        | 42.64%  |
| 81-90          | 39        | 30.23%  |
| 71-80          | 7         | 5.43%   |
| 201-250        | 6         | 4.65%   |
| 141-150        | 4         | 3.1%    |
| 51-60          | 3         | 2.33%   |
| 61-70          | 2         | 1.55%   |
| 351-500        | 2         | 1.55%   |
| 301-350        | 2         | 1.55%   |
| 251-300        | 2         | 1.55%   |
| 121-130        | 2         | 1.55%   |
| 111-120        | 2         | 1.55%   |
| 131-140        | 1         | 0.78%   |
| 501-1000       | 1         | 0.78%   |
| Unknown        | 1         | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 54        | 42.86%  |
| 121-160       | 46        | 36.51%  |
| 51-100        | 13        | 10.32%  |
| 161-240       | 9         | 7.14%   |
| More than 240 | 3         | 2.38%   |
| Unknown       | 1         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 103       | 83.74%  |
| 2     | 16        | 13.01%  |
| 0     | 3         | 2.44%   |
| 3     | 1         | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 86        | 45.03%  |
| Intel                           | 51        | 26.7%   |
| Qualcomm Atheros                | 34        | 17.8%   |
| Broadcom                        | 4         | 2.09%   |
| Marvell Technology Group        | 3         | 1.57%   |
| Broadcom Limited                | 3         | 1.57%   |
| Xiaomi                          | 2         | 1.05%   |
| MediaTek                        | 2         | 1.05%   |
| Ralink Technology               | 1         | 0.52%   |
| Ralink                          | 1         | 0.52%   |
| Qualcomm Atheros Communications | 1         | 0.52%   |
| OPPO Electronics                | 1         | 0.52%   |
| Huawei Technologies             | 1         | 0.52%   |
| Hewlett-Packard                 | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 24.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 8.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 5.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.23%   |
| Intel Wireless 3165                                               | 5         | 2.23%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.79%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.34%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.34%   |
| Intel Wireless 7260                                               | 3         | 1.34%   |
| Intel Wireless 3160                                               | 3         | 1.34%   |
| Intel WiFi Link 5100                                              | 3         | 1.34%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.89%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 2         | 0.89%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.89%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.89%   |
| Intel Wireless 7265                                               | 2         | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 40%     |
| Qualcomm Atheros                | 34        | 27.2%   |
| Realtek Semiconductor           | 31        | 24.8%   |
| Broadcom Limited                | 3         | 2.4%    |
| MediaTek                        | 2         | 1.6%    |
| Broadcom                        | 2         | 1.6%    |
| Ralink Technology               | 1         | 0.8%    |
| Ralink                          | 1         | 0.8%    |
| Qualcomm Atheros Communications | 1         | 0.8%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 9.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.97%   |
| Intel Wireless 3165                                            | 5         | 3.97%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 3.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 3.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.17%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 2.38%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.38%   |
| Intel Wireless 7260                                            | 3         | 2.38%   |
| Intel Wireless 3160                                            | 3         | 2.38%   |
| Intel WiFi Link 5100                                           | 3         | 2.38%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 2.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.59%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 2         | 1.59%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.59%   |
| Intel Wireless 7265                                            | 2         | 1.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.59%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.79%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.79%   |
| Realtek 802.11ac NIC                                           | 1         | 0.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 76        | 77.55%  |
| Intel                    | 9         | 9.18%   |
| Qualcomm Atheros         | 3         | 3.06%   |
| Marvell Technology Group | 3         | 3.06%   |
| Xiaomi                   | 2         | 2.04%   |
| Broadcom                 | 2         | 2.04%   |
| OPPO Electronics         | 1         | 1.02%   |
| Huawei Technologies      | 1         | 1.02%   |
| Hewlett-Packard          | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 56.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 18.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.06%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.04%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 2.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 2.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.02%   |
| OPPO RMX3263                                                      | 1         | 1.02%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.02%   |
| Huawei ANA-NX9                                                    | 1         | 1.02%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 56.02%  |
| Ethernet | 95        | 43.98%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 81.3%   |
| Ethernet | 23        | 18.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 89        | 72.36%  |
| 1     | 31        | 25.2%   |
| 0     | 2         | 1.63%   |
| 3     | 1         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 117       | 94.35%  |
| Yes  | 7         | 5.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 39.6%   |
| Qualcomm Atheros Communications | 20        | 19.8%   |
| Realtek Semiconductor           | 14        | 13.86%  |
| Foxconn / Hon Hai               | 7         | 6.93%   |
| Broadcom                        | 6         | 5.94%   |
| Realtek                         | 4         | 3.96%   |
| Lite-On Technology              | 3         | 2.97%   |
| IMC Networks                    | 3         | 2.97%   |
| Toshiba                         | 1         | 0.99%   |
| Ralink Technology               | 1         | 0.99%   |
| Dell                            | 1         | 0.99%   |
| Cambridge Silicon Radio         | 1         | 0.99%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 19        | 18.81%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 15        | 14.85%  |
| Intel AX201 Bluetooth                                                               | 7         | 6.93%   |
| Realtek Bluetooth Radio                                                             | 6         | 5.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 5.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 4.95%   |
| Intel AX200 Bluetooth                                                               | 5         | 4.95%   |
| Realtek Bluetooth Radio                                                             | 4         | 3.96%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.98%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.98%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.98%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.98%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.98%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.99%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.99%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.99%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.99%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.99%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.99%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.99%   |
| Intel Bluetooth Device                                                              | 1         | 0.99%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.99%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.99%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.99%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.99%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.99%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 0.99%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.99%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.99%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.99%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 98        | 72.59%  |
| AMD                 | 21        | 15.56%  |
| Nvidia              | 13        | 9.63%   |
| Zhaoxin             | 1         | 0.74%   |
| JMTek               | 1         | 0.74%   |
| Creative Technology | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 10.17%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 9.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 7.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 6.21%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 6.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 5.65%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 5.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 4.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 3.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.95%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.69%   |
| Nvidia Audio device                                                                               | 3         | 1.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.13%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.13%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.56%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller                          | 1         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.56%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.56%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.56%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.56%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                      | 1         | 0.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.56%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 0.56%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 28.4%   |
| SK hynix            | 20        | 24.69%  |
| Unknown             | 10        | 12.35%  |
| Micron Technology   | 7         | 8.64%   |
| Smart               | 4         | 4.94%   |
| Kingston            | 4         | 4.94%   |
| Ramaxel Technology  | 3         | 3.7%    |
| Nanya Technology    | 3         | 3.7%    |
| A-DATA Technology   | 2         | 2.47%   |
| Unknown (07FB)      | 1         | 1.23%   |
| Smart Brazil        | 1         | 1.23%   |
| MTASE               | 1         | 1.23%   |
| Crucial             | 1         | 1.23%   |
| ChangXin Memory     | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 2.33%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 2.33%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 2         | 2.33%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 2         | 2.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 2.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.33%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 2.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 2.33%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.16%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1.16%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 1.16%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 1.16%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.16%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 1.16%   |
| Unknown RAM Module 2048MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.16%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 1.16%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1.16%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s                 | 1         | 1.16%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.16%   |
| Unknown (07FB) RAM GST32G08SCL196P-26 32GB SODIMM DDR4 2667MT/s  | 1         | 1.16%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 1         | 1.16%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 1.16%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 1         | 1.16%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 1.16%   |
| SK hynix RAM MPPS4GBPC1600 1.35 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.16%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.16%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 1         | 1.16%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.16%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.16%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 1.16%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.16%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.16%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2048MB LPDDR3 1600MT/s           | 1         | 1.16%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 36        | 50.7%   |
| DDR3   | 20        | 28.17%  |
| LPDDR4 | 5         | 7.04%   |
| LPDDR3 | 5         | 7.04%   |
| DDR5   | 2         | 2.82%   |
| DDR2   | 2         | 2.82%   |
| LPDDR5 | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 83.33%  |
| Row Of Chips | 11        | 15.28%  |
| Unknown      | 1         | 1.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 28        | 36.84%  |
| 4096  | 27        | 35.53%  |
| 2048  | 13        | 17.11%  |
| 16384 | 5         | 6.58%   |
| 1024  | 2         | 2.63%   |
| 32768 | 1         | 1.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 18        | 24.32%  |
| 1600    | 17        | 22.97%  |
| 3200    | 10        | 13.51%  |
| 2400    | 4         | 5.41%   |
| 2133    | 4         | 5.41%   |
| 1334    | 3         | 4.05%   |
| 1333    | 3         | 4.05%   |
| 4800    | 2         | 2.7%    |
| 3266    | 2         | 2.7%    |
| Unknown | 2         | 2.7%    |
| 6400    | 1         | 1.35%   |
| 4267    | 1         | 1.35%   |
| 4266    | 1         | 1.35%   |
| 3733    | 1         | 1.35%   |
| 2933    | 1         | 1.35%   |
| 2666    | 1         | 1.35%   |
| 1867    | 1         | 1.35%   |
| 1066    | 1         | 1.35%   |
| 800     | 1         | 1.35%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 27.93%  |
| IMC Networks                           | 11        | 9.91%   |
| Microdia                               | 10        | 9.01%   |
| Realtek Semiconductor                  | 9         | 8.11%   |
| Syntek                                 | 6         | 5.41%   |
| Sunplus Innovation Technology          | 6         | 5.41%   |
| Silicon Motion                         | 6         | 5.41%   |
| Quanta                                 | 6         | 5.41%   |
| Suyin                                  | 5         | 4.5%    |
| Acer                                   | 5         | 4.5%    |
| Lite-On Technology                     | 4         | 3.6%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.7%    |
| Ricoh                                  | 2         | 1.8%    |
| Primax Electronics                     | 2         | 1.8%    |
| Alcor Micro                            | 2         | 1.8%    |
| LG Electronics                         | 1         | 0.9%    |
| Lenovo                                 | 1         | 0.9%    |
| Goodong Industry                       | 1         | 0.9%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 8         | 7.21%   |
| IMC Networks Integrated Camera           | 5         | 4.5%    |
| IMC Networks HD Camera                   | 4         | 3.6%    |
| Chicony EasyCamera                       | 4         | 3.6%    |
| Syntek EasyCamera                        | 3         | 2.7%    |
| Silicon Motion Web Camera                | 3         | 2.7%    |
| Quanta HD User Facing                    | 3         | 2.7%    |
| Chicony TOSHIBA Web Camera - HD          | 3         | 2.7%    |
| Syntek Integrated Camera                 | 2         | 1.8%    |
| Sunplus HD WebCam                        | 2         | 1.8%    |
| Realtek Integrated_Webcam_HD             | 2         | 1.8%    |
| Realtek HP "Truevision HD" laptop camera | 2         | 1.8%    |
| Quanta HP TrueVision HD Camera           | 2         | 1.8%    |
| Primax HP HD Webcam [Fixed]              | 2         | 1.8%    |
| Microdia USB 2.0 Camera                  | 2         | 1.8%    |
| Microdia Integrated_Webcam_HD            | 2         | 1.8%    |
| Chicony HP Webcam                        | 2         | 1.8%    |
| Chicony HP HD Webcam                     | 2         | 1.8%    |
| Chicony HD WebCam                        | 2         | 1.8%    |
| Acer Integrated Camera                   | 2         | 1.8%    |
| Syntek Lenovo EasyCamera                 | 1         | 0.9%    |
| Suyin Integrated_Webcam_HD               | 1         | 0.9%    |
| Suyin HP Truevision HD                   | 1         | 0.9%    |
| Suyin HD WebCam                          | 1         | 0.9%    |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.9%    |
| Suyin 1.3M HD WebCam                     | 1         | 0.9%    |
| Sunplus XiaoMi USB 2.0 Webcam            | 1         | 0.9%    |
| Sunplus Integrated_Webcam_HD             | 1         | 0.9%    |
| Sunplus HP Wide Vision HD                | 1         | 0.9%    |
| Sunplus Asus Webcam                      | 1         | 0.9%    |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.9%    |
| Silicon Motion WebCam SC-0311139N        | 1         | 0.9%    |
| Silicon Motion ATIV VGA Camera           | 1         | 0.9%    |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 0.9%    |
| Ricoh Laptop_Integrated_Webcam_FHD       | 1         | 0.9%    |
| Realtek USB Camera                       | 1         | 0.9%    |
| Realtek Laptop_Integrated_Webcam_HD      | 1         | 0.9%    |
| Realtek HP Wide Vision HD Camera         | 1         | 0.9%    |
| Realtek HP Truevision HD                 | 1         | 0.9%    |
| Realtek HD WebCam                        | 1         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 40%     |
| Shenzhen Goodix Technology | 8         | 32%     |
| Upek                       | 5         | 20%     |
| Synaptics                  | 1         | 4%      |
| Elan Microelectronics      | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 20%     |
| Shenzhen Goodix  Fingerprint Device                    | 5         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 12%     |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 12%     |
| Validity Sensors VFS491                                | 2         | 8%      |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 8%      |
| Upek TCS5B Fingerprint sensor                          | 2         | 8%      |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4%      |
| Elan ELAN:Fingerprint                                  | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Alcor Micro         | 3         | 50%     |
| Lenovo              | 1         | 16.67%  |
| Giesecke & Devrient | 1         | 16.67%  |
| Broadcom            | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 50%     |
| Lenovo Integrated Smart Card Reader            | 1         | 16.67%  |
| Giesecke & Devrient StarSign CUT               | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 80        | 64%     |
| 1     | 38        | 30.4%   |
| 2     | 7         | 5.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 25        | 48.08%  |
| Graphics card         | 15        | 28.85%  |
| Chipcard              | 5         | 9.62%   |
| Multimedia controller | 3         | 5.77%   |
| Sound                 | 2         | 3.85%   |
| Storage               | 1         | 1.92%   |
| Camera                | 1         | 1.92%   |


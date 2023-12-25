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

Total: 192

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T490s 20NX003AU... | [e0dc55809f](https://linux-hardware.org/?probe=e0dc55809f) | Dec 09, 2023 |
| Lenovo        | ThinkPad T490s 20NX003AU... | [649f5e559d](https://linux-hardware.org/?probe=649f5e559d) | Dec 02, 2023 |
| HUAWEI        | KLVC-WXX9                   | [dd49d338b4](https://linux-hardware.org/?probe=dd49d338b4) | Nov 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [4ce52b15f5](https://linux-hardware.org/?probe=4ce52b15f5) | Nov 24, 2023 |
| HP            | Compaq Presario CQ40        | [ede0c05f18](https://linux-hardware.org/?probe=ede0c05f18) | Nov 04, 2023 |
| Acer          | Nitro AN515-57              | [3b669afc38](https://linux-hardware.org/?probe=3b669afc38) | Oct 26, 2023 |
| UNOWHY        | Y13G012S4EI                 | [eb2ef3f8d5](https://linux-hardware.org/?probe=eb2ef3f8d5) | Oct 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [50698ed07c](https://linux-hardware.org/?probe=50698ed07c) | Oct 14, 2023 |
| Timi          | RedmiBook Air 13            | [63ea7be36f](https://linux-hardware.org/?probe=63ea7be36f) | Oct 07, 2023 |
| HP            | EliteBook 845 14 inch G1... | [b409947c26](https://linux-hardware.org/?probe=b409947c26) | Sep 11, 2023 |
| HP            | EliteBook 845 14 inch G1... | [f7f7964c03](https://linux-hardware.org/?probe=f7f7964c03) | Sep 09, 2023 |
| HP            | EliteBook 845 14 inch G1... | [6459a498c5](https://linux-hardware.org/?probe=6459a498c5) | Sep 07, 2023 |
| HP            | EliteBook 845 14 inch G1... | [c57f9232a2](https://linux-hardware.org/?probe=c57f9232a2) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G1... | [8b11ecfd36](https://linux-hardware.org/?probe=8b11ecfd36) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | [ac607e5597](https://linux-hardware.org/?probe=ac607e5597) | Aug 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4d875892d6](https://linux-hardware.org/?probe=4d875892d6) | Jul 30, 2023 |
| HONOR         | NBLK-WAX9X                  | [1081b2e480](https://linux-hardware.org/?probe=1081b2e480) | Jul 26, 2023 |
| HONOR         | NBLK-WAX9X                  | [9919413d6e](https://linux-hardware.org/?probe=9919413d6e) | Jul 25, 2023 |
| HUAWEI        | MACHC-WAX9                  | [bddace9995](https://linux-hardware.org/?probe=bddace9995) | Jul 25, 2023 |
| itel Mobil... | SPIRIT 1                    | [36c3d3f6a8](https://linux-hardware.org/?probe=36c3d3f6a8) | Jul 16, 2023 |
| MSI           | GL72M 7REX                  | [6d50ff945d](https://linux-hardware.org/?probe=6d50ff945d) | Jun 19, 2023 |
| MSI           | GL72M 7REX                  | [1f1699301f](https://linux-hardware.org/?probe=1f1699301f) | Jun 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [320e5bee32](https://linux-hardware.org/?probe=320e5bee32) | Jun 04, 2023 |
| Hometech      | Alfa 470C                   | [ee3bd9eb81](https://linux-hardware.org/?probe=ee3bd9eb81) | Jun 02, 2023 |
| Apple         | MacBookPro14,1              | [a5785cf3c3](https://linux-hardware.org/?probe=a5785cf3c3) | May 29, 2023 |
| Dell          | Inspiron 13-7359            | [35c9cf7244](https://linux-hardware.org/?probe=35c9cf7244) | May 12, 2023 |
| Dell          | G15 5520                    | [0322e7d38c](https://linux-hardware.org/?probe=0322e7d38c) | Mar 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [42a0b7428f](https://linux-hardware.org/?probe=42a0b7428f) | Mar 05, 2023 |
| Dell          | G15 5520                    | [1e3dcc41d3](https://linux-hardware.org/?probe=1e3dcc41d3) | Mar 04, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f492107b66](https://linux-hardware.org/?probe=f492107b66) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1746b40d04](https://linux-hardware.org/?probe=1746b40d04) | Feb 09, 2023 |
| Acer          | Aspire A515-54G             | [a57a68e42f](https://linux-hardware.org/?probe=a57a68e42f) | Jan 31, 2023 |
| Infinix       | INBOOK X2 GEN11             | [a899026279](https://linux-hardware.org/?probe=a899026279) | Jan 08, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [c4170b9ea3](https://linux-hardware.org/?probe=c4170b9ea3) | Dec 20, 2022 |
| Dell          | Inspiron 5488               | [32b350c3f6](https://linux-hardware.org/?probe=32b350c3f6) | Nov 25, 2022 |
| Timi          | Redmi G 2022                | [86f8128511](https://linux-hardware.org/?probe=86f8128511) | Nov 12, 2022 |
| HP            | Laptop                      | [e1cd3de91a](https://linux-hardware.org/?probe=e1cd3de91a) | Nov 02, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ba1f911067](https://linux-hardware.org/?probe=ba1f911067) | Sep 10, 2022 |
| HP            | 620                         | [4476f5f677](https://linux-hardware.org/?probe=4476f5f677) | Jun 23, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [6103e540b9](https://linux-hardware.org/?probe=6103e540b9) | May 04, 2022 |
| HP            | EliteBook 8570w             | [7795fe989b](https://linux-hardware.org/?probe=7795fe989b) | Apr 29, 2022 |
| HUAWEI        | BOM-WXX9                    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI        | BOM-WXX9                    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Lenovo        | Legion Y7000 81FW           | [c56c469d4f](https://linux-hardware.org/?probe=c56c469d4f) | Apr 21, 2022 |
| Acer          | Swift SF314-512             | [d7e77fd856](https://linux-hardware.org/?probe=d7e77fd856) | Apr 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | [8794debb03](https://linux-hardware.org/?probe=8794debb03) | Apr 20, 2022 |
| ASUSTek       | P552LA                      | [94ef2678d5](https://linux-hardware.org/?probe=94ef2678d5) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | [9166f15878](https://linux-hardware.org/?probe=9166f15878) | Apr 03, 2022 |
| HP            | EliteBook 8570w             | [131c9a7dc2](https://linux-hardware.org/?probe=131c9a7dc2) | Jan 27, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| Google        | Akemi                       | [295fd594af](https://linux-hardware.org/?probe=295fd594af) | Dec 27, 2021 |
| Acer          | Aspire VN7-572G             | [895dca26b0](https://linux-hardware.org/?probe=895dca26b0) | Dec 21, 2021 |
| HUAWEI        | HN-WX9X                     | [f228b60d0c](https://linux-hardware.org/?probe=f228b60d0c) | Dec 07, 2021 |
| HP            | EliteBook 8570w             | [7752a79879](https://linux-hardware.org/?probe=7752a79879) | Dec 06, 2021 |
| HP            | Laptop 14-ck0xxx            | [4b03ed047c](https://linux-hardware.org/?probe=4b03ed047c) | Dec 06, 2021 |
| Samsung       | 550P5C/550P7C               | [31bc59dcb9](https://linux-hardware.org/?probe=31bc59dcb9) | Nov 12, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [88d791ff87](https://linux-hardware.org/?probe=88d791ff87) | Nov 09, 2021 |
| Dell          | Latitude 3400               | [7f519c2721](https://linux-hardware.org/?probe=7f519c2721) | Oct 23, 2021 |
| Samsung       | 550P5C/550P7C               | [2713972f14](https://linux-hardware.org/?probe=2713972f14) | Oct 22, 2021 |
| HP            | ZHAN 66 Pro G1              | [a1a1c41c6a](https://linux-hardware.org/?probe=a1a1c41c6a) | Oct 09, 2021 |
| HP            | ZHAN 66 Pro G1              | [fcc291e2f1](https://linux-hardware.org/?probe=fcc291e2f1) | Oct 08, 2021 |
| Lenovo        | Legion Y7000 2020 82AV      | [64d71e1177](https://linux-hardware.org/?probe=64d71e1177) | Sep 29, 2021 |
| HP            | Laptop 15-bs0xx             | [fc0f8f406b](https://linux-hardware.org/?probe=fc0f8f406b) | Aug 31, 2021 |
| Lenovo        | ThinkPad L412 0585AC3       | [f31b3187c3](https://linux-hardware.org/?probe=f31b3187c3) | Aug 23, 2021 |
| Lenovo        | Legion R9000K2021H 82N6     | [048b8332cc](https://linux-hardware.org/?probe=048b8332cc) | Aug 13, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5e1cc5b229](https://linux-hardware.org/?probe=5e1cc5b229) | Aug 11, 2021 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | [d563d62b5f](https://linux-hardware.org/?probe=d563d62b5f) | Jul 14, 2021 |
| Acer          | Aspire 5750G                | [61b9408d9e](https://linux-hardware.org/?probe=61b9408d9e) | Jul 11, 2021 |
| Acer          | Aspire 5750G                | [59728d9bef](https://linux-hardware.org/?probe=59728d9bef) | Jul 11, 2021 |
| HUAWEI        | HLYL-WXX9                   | [26b5b9e3d3](https://linux-hardware.org/?probe=26b5b9e3d3) | Jul 06, 2021 |
| Lenovo        | ZHAOYANG CF4620Z-A123 59... | [6f716961de](https://linux-hardware.org/?probe=6f716961de) | Jun 29, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [279dea011e](https://linux-hardware.org/?probe=279dea011e) | Jun 28, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE R7 8... | [b2c24061a6](https://linux-hardware.org/?probe=b2c24061a6) | Jun 13, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [0540d35606](https://linux-hardware.org/?probe=0540d35606) | May 31, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [30ffaaaad4](https://linux-hardware.org/?probe=30ffaaaad4) | May 22, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [91b9340ed6](https://linux-hardware.org/?probe=91b9340ed6) | May 20, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [68740fff81](https://linux-hardware.org/?probe=68740fff81) | May 16, 2021 |
| Unknown       | Unknown                     | [4d3ffa307c](https://linux-hardware.org/?probe=4d3ffa307c) | Apr 26, 2021 |
| Unknown       | Unknown                     | [8d019adbf9](https://linux-hardware.org/?probe=8d019adbf9) | Apr 26, 2021 |
| Lenovo        | ThinkPad T420 4180M8P       | [1fe655cf93](https://linux-hardware.org/?probe=1fe655cf93) | Apr 25, 2021 |
| Toshiba       | Satellite E55t-A            | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Unknown       | Unknown                     | [94f00d3697](https://linux-hardware.org/?probe=94f00d3697) | Mar 27, 2021 |
| Sony          | VGN-AW11Z_B                 | [9ddedfd3c9](https://linux-hardware.org/?probe=9ddedfd3c9) | Feb 13, 2021 |
| HP            | Pavilion Laptop 14-bf0xx    | [309266e981](https://linux-hardware.org/?probe=309266e981) | Feb 13, 2021 |
| Dell          | Inspiron 7720               | [8c8689a8ba](https://linux-hardware.org/?probe=8c8689a8ba) | Feb 08, 2021 |
| Acer          | Aspire V5-571P              | [e03d4bc850](https://linux-hardware.org/?probe=e03d4bc850) | Feb 07, 2021 |
| Dell          | Inspiron 5547               | [e2cee5283f](https://linux-hardware.org/?probe=e2cee5283f) | Feb 04, 2021 |
| HUAWEI        | HN-WX9X                     | [b0ca634dee](https://linux-hardware.org/?probe=b0ca634dee) | Jan 28, 2021 |
| Lenovo        | ThinkPad E14 20RA0058VA     | [3c08ce49f5](https://linux-hardware.org/?probe=3c08ce49f5) | Jan 08, 2021 |
| Acer          | Aspire 4736Z                | [dd3b50729f](https://linux-hardware.org/?probe=dd3b50729f) | Jan 07, 2021 |
| ASUSTek       | X406UAR                     | [42e509209a](https://linux-hardware.org/?probe=42e509209a) | Dec 20, 2020 |
| ASUSTek       | X406UAR                     | [23b1fae05b](https://linux-hardware.org/?probe=23b1fae05b) | Dec 20, 2020 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [667577cb5f](https://linux-hardware.org/?probe=667577cb5f) | Dec 15, 2020 |
| Lenovo        | G50-80 80L0                 | [951a5a280f](https://linux-hardware.org/?probe=951a5a280f) | Dec 11, 2020 |
| Acer          | Nitro AN515-54              | [d46eb4b9c9](https://linux-hardware.org/?probe=d46eb4b9c9) | Nov 19, 2020 |
| Acer          | Nitro AN515-54              | [877187c708](https://linux-hardware.org/?probe=877187c708) | Nov 19, 2020 |
| Lenovo        | ThinkPad E585 20KV0010US    | [033f6f0920](https://linux-hardware.org/?probe=033f6f0920) | Nov 18, 2020 |
| Lenovo        | ThinkPad E585 20KV0010US    | [d2bedcab13](https://linux-hardware.org/?probe=d2bedcab13) | Nov 18, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [b687de4d3c](https://linux-hardware.org/?probe=b687de4d3c) | Nov 05, 2020 |
| Toshiba       | Satellite C850D-11K         | [53f5d002c9](https://linux-hardware.org/?probe=53f5d002c9) | Oct 31, 2020 |
| HP            | ENVY 15                     | [c23287b06d](https://linux-hardware.org/?probe=c23287b06d) | Oct 31, 2020 |
| Acer          | Swift SF314-42              | [628265bca0](https://linux-hardware.org/?probe=628265bca0) | Oct 25, 2020 |
| Acer          | Swift SF314-42              | [01143e194b](https://linux-hardware.org/?probe=01143e194b) | Oct 20, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [8d149c1a39](https://linux-hardware.org/?probe=8d149c1a39) | Oct 17, 2020 |
| Acer          | Nitro AN515-52              | [ca3d5b9444](https://linux-hardware.org/?probe=ca3d5b9444) | Oct 13, 2020 |
| Microtech     | ebookPro                    | [2f1ff6265a](https://linux-hardware.org/?probe=2f1ff6265a) | Oct 10, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [88e5775f0f](https://linux-hardware.org/?probe=88e5775f0f) | Oct 02, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [2972557e3e](https://linux-hardware.org/?probe=2972557e3e) | Oct 02, 2020 |
| Lenovo        | G50-70 20351                | [c5ea28ed29](https://linux-hardware.org/?probe=c5ea28ed29) | Sep 28, 2020 |
| HP            | ENVY 15                     | [e7bfa62e4c](https://linux-hardware.org/?probe=e7bfa62e4c) | Sep 23, 2020 |
| Samsung       | 270E5J/2570EJ               | [d00667e263](https://linux-hardware.org/?probe=d00667e263) | Sep 21, 2020 |
| HP            | Pavilion 15                 | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| HP            | Pavilion 15                 | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| Dell          | Inspiron 3583               | [860b906339](https://linux-hardware.org/?probe=860b906339) | Sep 14, 2020 |
| Lenovo        | V310-15ISK 80SY             | [043d555fa5](https://linux-hardware.org/?probe=043d555fa5) | Sep 05, 2020 |
| Acer          | Aspire E5-571               | [84a6667f77](https://linux-hardware.org/?probe=84a6667f77) | Sep 05, 2020 |
| Acer          | Aspire 5735                 | [0e4c64618a](https://linux-hardware.org/?probe=0e4c64618a) | Sep 03, 2020 |
| Dell          | Inspiron 3583               | [885667a4cd](https://linux-hardware.org/?probe=885667a4cd) | Sep 02, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [e4b74d9442](https://linux-hardware.org/?probe=e4b74d9442) | Sep 02, 2020 |
| Dell          | Inspiron 5447               | [bc69598c5f](https://linux-hardware.org/?probe=bc69598c5f) | Aug 28, 2020 |
| Dell          | Inspiron 5447               | [b9bf539788](https://linux-hardware.org/?probe=b9bf539788) | Jul 26, 2020 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [b73122dcbf](https://linux-hardware.org/?probe=b73122dcbf) | Jul 24, 2020 |
| Dell          | Inspiron 7520               | [0e4bbcdaca](https://linux-hardware.org/?probe=0e4bbcdaca) | Jul 19, 2020 |
| Lenovo        | ThinkPad L512 44444NG       | [bfda7d01d5](https://linux-hardware.org/?probe=bfda7d01d5) | Jun 30, 2020 |
| HP            | EliteBook 820 G3            | [1ad623b060](https://linux-hardware.org/?probe=1ad623b060) | Jun 20, 2020 |
| HP            | EliteBook 820 G3            | [5517a703d4](https://linux-hardware.org/?probe=5517a703d4) | Jun 15, 2020 |
| Chuwi         | AeroBook                    | [12312a6c5b](https://linux-hardware.org/?probe=12312a6c5b) | Jun 03, 2020 |
| Chuwi         | AeroBook                    | [fdcf37b34d](https://linux-hardware.org/?probe=fdcf37b34d) | Jun 01, 2020 |
| Chuwi         | AeroBook                    | [6a57e4427b](https://linux-hardware.org/?probe=6a57e4427b) | Jun 01, 2020 |
| Google        | Edgar                       | [ed3bf69957](https://linux-hardware.org/?probe=ed3bf69957) | May 28, 2020 |
| ASUSTek       | T100TAF                     | [6d2999ebb1](https://linux-hardware.org/?probe=6d2999ebb1) | May 26, 2020 |
| HP            | Pavilion Notebook           | [825d07d907](https://linux-hardware.org/?probe=825d07d907) | May 14, 2020 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [49661d90bd](https://linux-hardware.org/?probe=49661d90bd) | Apr 19, 2020 |
| HP            | EliteBook 8570p             | [6928abb72d](https://linux-hardware.org/?probe=6928abb72d) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [020c71d11e](https://linux-hardware.org/?probe=020c71d11e) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [163b885549](https://linux-hardware.org/?probe=163b885549) | Apr 07, 2020 |
| Sony          | VGN-NS140D                  | [dbae86d335](https://linux-hardware.org/?probe=dbae86d335) | Apr 06, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | [76c9608867](https://linux-hardware.org/?probe=76c9608867) | Mar 24, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | [81e20268cd](https://linux-hardware.org/?probe=81e20268cd) | Mar 24, 2020 |
| Fujitsu       | FARQ06012Z                  | [6d19311f7e](https://linux-hardware.org/?probe=6d19311f7e) | Mar 23, 2020 |
| HP            | EliteBook 820 G4            | [b525dfeb66](https://linux-hardware.org/?probe=b525dfeb66) | Mar 01, 2020 |
| HP            | EliteBook 820 G4            | [e28f1711fd](https://linux-hardware.org/?probe=e28f1711fd) | Mar 01, 2020 |
| CCE           | Capella & IbexPeak-M Chi... | [b6b6b3d6d5](https://linux-hardware.org/?probe=b6b6b3d6d5) | Mar 01, 2020 |
| HP            | ENVY 15                     | [a8fb8c36bf](https://linux-hardware.org/?probe=a8fb8c36bf) | Jan 22, 2020 |
| Acer          | P5WE0                       | [a3377994d6](https://linux-hardware.org/?probe=a3377994d6) | Jan 18, 2020 |
| HP            | 250 G5 Notebook PC          | [6882e04fe6](https://linux-hardware.org/?probe=6882e04fe6) | Jan 16, 2020 |
| Acer          | Nitro AN515-54              | [af36fc8a7c](https://linux-hardware.org/?probe=af36fc8a7c) | Jan 15, 2020 |
| Acer          | Nitro AN515-54              | [d96a34fd91](https://linux-hardware.org/?probe=d96a34fd91) | Jan 15, 2020 |
| Acer          | Nitro AN515-54              | [dbd7e76364](https://linux-hardware.org/?probe=dbd7e76364) | Jan 15, 2020 |
| HUAWEI        | HLY-WX9XX                   | [9f6e79326e](https://linux-hardware.org/?probe=9f6e79326e) | Jan 14, 2020 |
| Dell          | XPS 13 9360                 | [60888ae202](https://linux-hardware.org/?probe=60888ae202) | Jan 14, 2020 |
| Lenovo        | ThinkPad T420 4236CU8       | [0222255c98](https://linux-hardware.org/?probe=0222255c98) | Jan 12, 2020 |
| Toshiba       | Satellite L75-C             | [649fb9a60a](https://linux-hardware.org/?probe=649fb9a60a) | Jan 03, 2020 |
| Toshiba       | Satellite L75-C             | [2b66fb3c5e](https://linux-hardware.org/?probe=2b66fb3c5e) | Jan 03, 2020 |
| Toshiba       | Satellite C850-1H6          | [a0ffb29c6c](https://linux-hardware.org/?probe=a0ffb29c6c) | Dec 18, 2019 |
| Lenovo        | Unknown                     | [10ab399874](https://linux-hardware.org/?probe=10ab399874) | Dec 14, 2019 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d1b18250b9](https://linux-hardware.org/?probe=d1b18250b9) | Dec 04, 2019 |
| BQ            | Tesla2 W10                  | [27f3692e24](https://linux-hardware.org/?probe=27f3692e24) | Dec 04, 2019 |
| BQ            | Tesla2 W10                  | [4c37070709](https://linux-hardware.org/?probe=4c37070709) | Dec 04, 2019 |
| HP            | Pavilion 15                 | [03188ddfb3](https://linux-hardware.org/?probe=03188ddfb3) | Dec 03, 2019 |
| HP            | Pavilion 15                 | [ae59f09d06](https://linux-hardware.org/?probe=ae59f09d06) | Nov 19, 2019 |
| Acer          | Aspire E5-571G              | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer          | Aspire E5-571G              | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| ASUSTek       | K501LX                      | [e90c15e3c9](https://linux-hardware.org/?probe=e90c15e3c9) | Nov 10, 2019 |
| Samsung       | 340XAA/350XAA/550XAA        | [997462e90b](https://linux-hardware.org/?probe=997462e90b) | Oct 19, 2019 |
| Sony          | SVF14A190X                  | [0b9bdec363](https://linux-hardware.org/?probe=0b9bdec363) | Oct 08, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [c4f25ea846](https://linux-hardware.org/?probe=c4f25ea846) | Oct 07, 2019 |
| Gateway       | NE56R                       | [d0978555c2](https://linux-hardware.org/?probe=d0978555c2) | Sep 11, 2019 |
| Sony          | SVE14135CXP                 | [1b1819d6c0](https://linux-hardware.org/?probe=1b1819d6c0) | Aug 13, 2019 |
| Dell          | Inspiron 1428               | [d12daa7b97](https://linux-hardware.org/?probe=d12daa7b97) | Aug 01, 2019 |
| Dell          | Inspiron 1428               | [44b9085f50](https://linux-hardware.org/?probe=44b9085f50) | Aug 01, 2019 |
| Dell          | Inspiron 17 7000 Series ... | [37b056e670](https://linux-hardware.org/?probe=37b056e670) | Jul 23, 2019 |
| Timi          | TM1701                      | [cde89e0f6e](https://linux-hardware.org/?probe=cde89e0f6e) | Jun 13, 2019 |
| Dell          | Latitude E6420              | [c5063bb936](https://linux-hardware.org/?probe=c5063bb936) | May 12, 2019 |
| Dell          | Latitude E6420              | [9563d07d0a](https://linux-hardware.org/?probe=9563d07d0a) | May 12, 2019 |
| Acer          | Aspire 7741                 | [38acfde0bd](https://linux-hardware.org/?probe=38acfde0bd) | Apr 25, 2019 |
| ASUSTek       | N46VM                       | [c22250e143](https://linux-hardware.org/?probe=c22250e143) | Apr 25, 2019 |
| ASUSTek       | N46VM                       | [def5c1c07c](https://linux-hardware.org/?probe=def5c1c07c) | Apr 25, 2019 |
| Positivo      | C14CU51                     | [87fe4181bd](https://linux-hardware.org/?probe=87fe4181bd) | Apr 08, 2019 |
| HP            | Unknown                     | [53f0f72dd6](https://linux-hardware.org/?probe=53f0f72dd6) | Apr 02, 2019 |
| Sony          | VPCYB25AB                   | [035925b406](https://linux-hardware.org/?probe=035925b406) | Apr 01, 2019 |
| HP            | G42                         | [c0b7643d96](https://linux-hardware.org/?probe=c0b7643d96) | Mar 28, 2019 |
| HP            | Pavilion Notebook           | [53fb4de336](https://linux-hardware.org/?probe=53fb4de336) | Mar 27, 2019 |
| HP            | Pavilion Notebook           | [9a4cbb7444](https://linux-hardware.org/?probe=9a4cbb7444) | Mar 27, 2019 |
| Samsung       | 800G5M/800G5W               | [efdc2e3d09](https://linux-hardware.org/?probe=efdc2e3d09) | Mar 27, 2019 |
| HP            | EliteBook 840 G2            | [86742db945](https://linux-hardware.org/?probe=86742db945) | Mar 27, 2019 |
| Standard      | MB45II/MB45IN               | [5a6f9cc354](https://linux-hardware.org/?probe=5a6f9cc354) | Mar 27, 2019 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [619a0d9d90](https://linux-hardware.org/?probe=619a0d9d90) | Mar 27, 2019 |
| Lenovo        | G400s VILG1                 | [a18da046c8](https://linux-hardware.org/?probe=a18da046c8) | Mar 27, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | [deac2364d1](https://linux-hardware.org/?probe=deac2364d1) | Jan 30, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | [1629601591](https://linux-hardware.org/?probe=1629601591) | Jan 30, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | [b314214e24](https://linux-hardware.org/?probe=b314214e24) | Dec 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Deepin         | 29        | 20%     |
| Deepin 15.11   | 23        | 15.86%  |
| Deepin 20      | 20        | 13.79%  |
| UOS 20         | 13        | 8.97%   |
| Deepin 23      | 10        | 6.9%    |
| Deepin 15.9.2  | 8         | 5.52%   |
| Deepin 20.9    | 6         | 4.14%   |
| Deepin 20.8    | 6         | 4.14%   |
| Deepin 20.3    | 5         | 3.45%   |
| Deepin 20.5    | 4         | 2.76%   |
| Deepin 20.1    | 4         | 2.76%   |
| Deepin 20 beta | 3         | 2.07%   |
| Deepin 20.2.4  | 2         | 1.38%   |
| Deepin 15.9.3  | 2         | 1.38%   |
| Deepin 2014.3  | 1         | 0.69%   |
| Deepin 20.7.1  | 1         | 0.69%   |
| Deepin 20.7    | 1         | 0.69%   |
| Deepin 20.4    | 1         | 0.69%   |
| Deepin 20.2.3  | 1         | 0.69%   |
| Deepin 20.2.1  | 1         | 0.69%   |
| Deepin 15.9    | 1         | 0.69%   |
| Deepin 15.8    | 1         | 0.69%   |
| Deepin 15.10.1 | 1         | 0.69%   |
| Deepin 15.10   | 1         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Deepin | 140       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.15.0-30deepin-generic             | 32        | 22.07%  |
| 5.4.50-amd64-desktop                | 16        | 11.03%  |
| 4.15.0-29deepin-generic             | 12        | 8.28%   |
| 5.4.70-amd64-desktop                | 9         | 6.21%   |
| 5.10.60-amd64-desktop               | 9         | 6.21%   |
| 5.18.17-amd64-desktop-community-hwe | 6         | 4.14%   |
| 5.10.0-amd64-desktop                | 5         | 3.45%   |
| 6.1.32-amd64-desktop-hwe            | 4         | 2.76%   |
| 5.7.7-amd64-desktop                 | 4         | 2.76%   |
| 5.18.17-amd64-desktop-hwe           | 4         | 2.76%   |
| 5.10.41-amd64-desktop               | 4         | 2.76%   |
| 5.10.29-amd64-desktop               | 4         | 2.76%   |
| 5.3.0-3-amd64                       | 3         | 2.07%   |
| 5.15.77-amd64-desktop               | 3         | 2.07%   |
| 5.15.1-amd64-desktop                | 3         | 2.07%   |
| 6.1.11-amd64-desktop-hwe            | 2         | 1.38%   |
| 5.15.45-amd64-desktop               | 2         | 1.38%   |
| 5.15.24-amd64-desktop               | 2         | 1.38%   |
| 5.10.50-amd64-desktop               | 2         | 1.38%   |
| 5.10.5-amd64-desktop+               | 2         | 1.38%   |
| 5.10.18-amd64-desktop               | 2         | 1.38%   |
| 5.10.101-amd64-desktop              | 2         | 1.38%   |
| 4.19.0-amd64-desktop                | 2         | 1.38%   |
| 6.5.0                               | 1         | 0.69%   |
| 5.8.14-amd64-desktop                | 1         | 0.69%   |
| 5.6.14-050614-generic               | 1         | 0.69%   |
| 5.6.12-xanmod1                      | 1         | 0.69%   |
| 5.5.4-xanmod3                       | 1         | 0.69%   |
| 5.3.8-xanmod6                       | 1         | 0.69%   |
| 5.15.34-amd64-desktop               | 1         | 0.69%   |
| 5.10.83-amd64-desktop               | 1         | 0.69%   |
| 5.10.36-amd64-desktop               | 1         | 0.69%   |
| 5.1.0-050100rc2-generic             | 1         | 0.69%   |
| 4.15.0-135-generic                  | 1         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 45        | 31.03%  |
| 5.4.50   | 16        | 11.03%  |
| 5.18.17  | 10        | 6.9%    |
| 5.4.70   | 9         | 6.21%   |
| 5.10.60  | 9         | 6.21%   |
| 5.10.0   | 5         | 3.45%   |
| 6.1.32   | 4         | 2.76%   |
| 5.7.7    | 4         | 2.76%   |
| 5.10.41  | 4         | 2.76%   |
| 5.10.29  | 4         | 2.76%   |
| 5.3.0    | 3         | 2.07%   |
| 5.15.77  | 3         | 2.07%   |
| 5.15.1   | 3         | 2.07%   |
| 6.1.11   | 2         | 1.38%   |
| 5.15.45  | 2         | 1.38%   |
| 5.15.24  | 2         | 1.38%   |
| 5.10.50  | 2         | 1.38%   |
| 5.10.5   | 2         | 1.38%   |
| 5.10.18  | 2         | 1.38%   |
| 5.10.101 | 2         | 1.38%   |
| 4.19.0   | 2         | 1.38%   |
| 6.5.0    | 1         | 0.69%   |
| 5.8.14   | 1         | 0.69%   |
| 5.6.14   | 1         | 0.69%   |
| 5.6.12   | 1         | 0.69%   |
| 5.5.4    | 1         | 0.69%   |
| 5.3.8    | 1         | 0.69%   |
| 5.15.34  | 1         | 0.69%   |
| 5.10.83  | 1         | 0.69%   |
| 5.10.36  | 1         | 0.69%   |
| 5.1.0    | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15    | 45        | 31.25%  |
| 5.10    | 32        | 22.22%  |
| 5.4     | 25        | 17.36%  |
| 5.18    | 10        | 6.94%   |
| 5.15    | 10        | 6.94%   |
| 6.1     | 6         | 4.17%   |
| 5.7     | 4         | 2.78%   |
| 5.3     | 4         | 2.78%   |
| 5.6     | 2         | 1.39%   |
| 4.19    | 2         | 1.39%   |
| 6.5     | 1         | 0.69%   |
| 5.8     | 1         | 0.69%   |
| 5.5     | 1         | 0.69%   |
| 5.1     | 1         | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 140       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Deepin  | 114       | 81.43%  |
| Unknown | 20        | 14.29%  |
| DDE     | 5         | 3.57%   |
| KDE     | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 140       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 58        | 40.85%  |
| LightDM | 45        | 31.69%  |
| TDM     | 39        | 27.46%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 30        | 21.43%  |
| Unknown | 30        | 21.43%  |
| zh_CN   | 21        | 15%     |
| pt_BR   | 15        | 10.71%  |
| es_ES   | 11        | 7.86%   |
| de_DE   | 10        | 7.14%   |
| ru_RU   | 8         | 5.71%   |
| tr_TR   | 3         | 2.14%   |
| it_IT   | 3         | 2.14%   |
| sv_SE   | 2         | 1.43%   |
| pl_PL   | 2         | 1.43%   |
| fr_FR   | 2         | 1.43%   |
| nl_NL   | 1         | 0.71%   |
| ja_JP   | 1         | 0.71%   |
| en_GB   | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 94        | 66.67%  |
| BIOS | 47        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 125       | 89.29%  |
| Unknown | 14        | 10%     |
| Overlay | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 70        | 49.65%  |
| Unknown | 57        | 40.43%  |
| MBR     | 14        | 9.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 111       | 78.17%  |
| Yes       | 31        | 21.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 70.92%  |
| Yes       | 41        | 29.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 36        | 25.71%  |
| Hewlett-Packard     | 24        | 17.14%  |
| Acer                | 15        | 10.71%  |
| Dell                | 13        | 9.29%   |
| Samsung Electronics | 7         | 5%      |
| HUAWEI              | 7         | 5%      |
| ASUSTek Computer    | 7         | 5%      |
| Sony                | 5         | 3.57%   |
| Toshiba             | 4         | 2.86%   |
| Timi                | 3         | 2.14%   |
| Google              | 2         | 1.43%   |
| Unknown             | 2         | 1.43%   |
| UNOWHY              | 1         | 0.71%   |
| Standard            | 1         | 0.71%   |
| Positivo            | 1         | 0.71%   |
| MSI                 | 1         | 0.71%   |
| Microtech           | 1         | 0.71%   |
| itel Mobile Limited | 1         | 0.71%   |
| Infinix             | 1         | 0.71%   |
| HONOR               | 1         | 0.71%   |
| Hometech            | 1         | 0.71%   |
| Gateway             | 1         | 0.71%   |
| Fujitsu             | 1         | 0.71%   |
| Chuwi               | 1         | 0.71%   |
| CCE                 | 1         | 0.71%   |
| BQ                  | 1         | 0.71%   |
| Apple               | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 4         | 2.86%   |
| Samsung 340XAA/350XAA/550XAA                      | 2         | 1.43%   |
| Lenovo IdeaPad 120S-11IAP 81A4                    | 2         | 1.43%   |
| HP Pavilion Notebook                              | 2         | 1.43%   |
| HP Pavilion 15                                    | 2         | 1.43%   |
| HP ENVY 15                                        | 2         | 1.43%   |
| Acer Nitro AN515-54                               | 2         | 1.43%   |
| UNOWHY Y13G012S4EI                                | 1         | 0.71%   |
| Toshiba Satellite L75-C                           | 1         | 0.71%   |
| Toshiba Satellite E55t-A                          | 1         | 0.71%   |
| Toshiba Satellite C850D-11K                       | 1         | 0.71%   |
| Toshiba Satellite C850-1H6                        | 1         | 0.71%   |
| Timi TM1701                                       | 1         | 0.71%   |
| Timi RedmiBook Air 13                             | 1         | 0.71%   |
| Timi Redmi G 2022                                 | 1         | 0.71%   |
| Standard MB45II/MB45IN                            | 1         | 0.71%   |
| Sony VPCYB25AB                                    | 1         | 0.71%   |
| Sony VGN-NS140D                                   | 1         | 0.71%   |
| Sony VGN-AW11Z_B                                  | 1         | 0.71%   |
| Sony SVF14A190X                                   | 1         | 0.71%   |
| Sony SVE14135CXP                                  | 1         | 0.71%   |
| Samsung 800G5M/800G5W                             | 1         | 0.71%   |
| Samsung 550P5C/550P7C                             | 1         | 0.71%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.71%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 1         | 0.71%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.71%   |
| Positivo C14CU51                                  | 1         | 0.71%   |
| MSI GL72M 7REX                                    | 1         | 0.71%   |
| Microtech ebookPro                                | 1         | 0.71%   |
| Lenovo ZHAOYANG K4e-ITL 82F8                      | 1         | 0.71%   |
| Lenovo ZHAOYANG CF4620Z-A123 59082537             | 1         | 0.71%   |
| Lenovo Yoga 3 Pro-1370 80HE                       | 1         | 0.71%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN                 | 1         | 0.71%   |
| Lenovo XiaoXin-15ARE 2020 81YR                    | 1         | 0.71%   |
| Lenovo V310-15ISK 80SY                            | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW       | 1         | 0.71%   |
| Lenovo ThinkPad T490s 20NX003AUS                  | 1         | 0.71%   |
| Lenovo ThinkPad T420 4236CU8                      | 1         | 0.71%   |
| Lenovo ThinkPad T420 4180M8P                      | 1         | 0.71%   |
| Lenovo ThinkPad T14 Gen 1 20UD003SRT              | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 10        | 7.14%   |
| Dell Inspiron           | 9         | 6.43%   |
| Lenovo IdeaPad          | 8         | 5.71%   |
| Acer Aspire             | 8         | 5.71%   |
| HP EliteBook            | 6         | 4.29%   |
| HP Pavilion             | 5         | 3.57%   |
| HP Laptop               | 5         | 3.57%   |
| Toshiba Satellite       | 4         | 2.86%   |
| Lenovo ThinkBook        | 4         | 2.86%   |
| Lenovo Legion           | 4         | 2.86%   |
| Acer Nitro              | 4         | 2.86%   |
| Unknown                 | 4         | 2.86%   |
| Samsung 340XAA          | 2         | 1.43%   |
| Lenovo ZHAOYANG         | 2         | 1.43%   |
| HP ENVY                 | 2         | 1.43%   |
| Dell Latitude           | 2         | 1.43%   |
| Acer Swift              | 2         | 1.43%   |
| UNOWHY Y13G012S4EI      | 1         | 0.71%   |
| Timi TM1701             | 1         | 0.71%   |
| Timi RedmiBook          | 1         | 0.71%   |
| Timi Redmi              | 1         | 0.71%   |
| Standard MB45II         | 1         | 0.71%   |
| Sony VPCYB25AB          | 1         | 0.71%   |
| Sony VGN-NS140D         | 1         | 0.71%   |
| Sony VGN-AW11Z          | 1         | 0.71%   |
| Sony SVF14A190X         | 1         | 0.71%   |
| Sony SVE14135CXP        | 1         | 0.71%   |
| Samsung 800G5M          | 1         | 0.71%   |
| Samsung 550P5C          | 1         | 0.71%   |
| Samsung 500R4K          | 1         | 0.71%   |
| Samsung 300E4A          | 1         | 0.71%   |
| Samsung 270E5J          | 1         | 0.71%   |
| Positivo C14CU51        | 1         | 0.71%   |
| MSI GL72M               | 1         | 0.71%   |
| Microtech ebookPro      | 1         | 0.71%   |
| Lenovo Yoga             | 1         | 0.71%   |
| Lenovo XiaoXinAir-14ARE | 1         | 0.71%   |
| Lenovo XiaoXin-15ARE    | 1         | 0.71%   |
| Lenovo V310-15ISK       | 1         | 0.71%   |
| Lenovo G50-80           | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 17        | 12.14%  |
| 2021    | 14        | 10%     |
| 2017    | 14        | 10%     |
| 2018    | 13        | 9.29%   |
| 2020    | 10        | 7.14%   |
| 2015    | 10        | 7.14%   |
| 2012    | 10        | 7.14%   |
| 2014    | 8         | 5.71%   |
| 2013    | 8         | 5.71%   |
| 2011    | 7         | 5%      |
| 2010    | 7         | 5%      |
| 2022    | 6         | 4.29%   |
| 2016    | 6         | 4.29%   |
| 2009    | 4         | 2.86%   |
| 2023    | 3         | 2.14%   |
| 2008    | 2         | 1.43%   |
| Unknown | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 140       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 131       | 93.57%  |
| Enabled  | 9         | 6.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 138       | 98.57%  |
| Yes  | 2         | 1.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 50        | 35.71%  |
| 8.01-16.0   | 29        | 20.71%  |
| 3.01-4.0    | 27        | 19.29%  |
| 16.01-24.0  | 21        | 15%     |
| 32.01-64.0  | 7         | 5%      |
| 1.01-2.0    | 4         | 2.86%   |
| 2.01-3.0    | 1         | 0.71%   |
| 64.01-256.0 | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 45        | 31.03%  |
| 1.01-2.0  | 43        | 29.66%  |
| 3.01-4.0  | 24        | 16.55%  |
| 4.01-8.0  | 21        | 14.48%  |
| 0.51-1.0  | 8         | 5.52%   |
| 8.01-16.0 | 4         | 2.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 105       | 73.94%  |
| 2      | 36        | 25.35%  |
| 3      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 67.86%  |
| Yes       | 45        | 32.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 70%     |
| No        | 42        | 30%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 98.57%  |
| No        | 2         | 1.43%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 82.86%  |
| No        | 24        | 17.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| Brazil                | 31        | 21.99%  |
| China                 | 23        | 16.31%  |
| Germany               | 11        | 7.8%    |
| Russia                | 6         | 4.26%   |
| USA                   | 5         | 3.55%   |
| Turkey                | 5         | 3.55%   |
| Spain                 | 5         | 3.55%   |
| Indonesia             | 4         | 2.84%   |
| Poland                | 3         | 2.13%   |
| Japan                 | 3         | 2.13%   |
| Italy                 | 3         | 2.13%   |
| Chile                 | 3         | 2.13%   |
| Sweden                | 2         | 1.42%   |
| Panama                | 2         | 1.42%   |
| India                 | 2         | 1.42%   |
| Canada                | 2         | 1.42%   |
| Bulgaria              | 2         | 1.42%   |
| Austria               | 2         | 1.42%   |
| Vietnam               | 1         | 0.71%   |
| Venezuela             | 1         | 0.71%   |
| Tunisia               | 1         | 0.71%   |
| Sri Lanka             | 1         | 0.71%   |
| South Africa          | 1         | 0.71%   |
| Singapore             | 1         | 0.71%   |
| Serbia                | 1         | 0.71%   |
| Sao Tome and Principe | 1         | 0.71%   |
| Portugal              | 1         | 0.71%   |
| Pakistan              | 1         | 0.71%   |
| Netherlands           | 1         | 0.71%   |
| Mexico                | 1         | 0.71%   |
| Lebanon               | 1         | 0.71%   |
| Kenya                 | 1         | 0.71%   |
| Iran                  | 1         | 0.71%   |
| Hong Kong             | 1         | 0.71%   |
| Greece                | 1         | 0.71%   |
| France                | 1         | 0.71%   |
| Ecuador               | 1         | 0.71%   |
| Czechia               | 1         | 0.71%   |
| Cuba                  | 1         | 0.71%   |
| Colombia              | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Beijing          | 5         | 3.55%   |
| Wuhan            | 3         | 2.13%   |
| Guangzhou        | 3         | 2.13%   |
| Curitiba         | 3         | 2.13%   |
| Uberlândia      | 2         | 1.42%   |
| Taiyuan          | 2         | 1.42%   |
| Surabaya         | 2         | 1.42%   |
| Sao Paulo        | 2         | 1.42%   |
| Petrópolis      | 2         | 1.42%   |
| Londrina         | 2         | 1.42%   |
| Innsbruck        | 2         | 1.42%   |
| David            | 2         | 1.42%   |
| Atlanta          | 2         | 1.42%   |
| Yozgat           | 1         | 0.71%   |
| Yogyakarta       | 1         | 0.71%   |
| Yekaterinburg    | 1         | 0.71%   |
| Xuhui            | 1         | 0.71%   |
| Wanchai          | 1         | 0.71%   |
| Voronezh         | 1         | 0.71%   |
| Villa Ballester  | 1         | 0.71%   |
| Vigo             | 1         | 0.71%   |
| Ufa              | 1         | 0.71%   |
| Tomsk            | 1         | 0.71%   |
| Tokyo            | 1         | 0.71%   |
| Tianjin          | 1         | 0.71%   |
| TehrДЃn        | 1         | 0.71%   |
| Tai'an           | 1         | 0.71%   |
| SГЈo TomГ©   | 1         | 0.71%   |
| Suzano           | 1         | 0.71%   |
| Sofia            | 1         | 0.71%   |
| Singapore        | 1         | 0.71%   |
| Shanghai         | 1         | 0.71%   |
| Sao Carlos       | 1         | 0.71%   |
| Sao Bento do Sul | 1         | 0.71%   |
| Santiago         | 1         | 0.71%   |
| Samara           | 1         | 0.71%   |
| Saitama          | 1         | 0.71%   |
| Rzeszów         | 1         | 0.71%   |
| Rotenburg        | 1         | 0.71%   |
| Poznan           | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 23        | 26     | 13.07%  |
| Seagate                        | 23        | 26     | 13.07%  |
| Samsung Electronics            | 19        | 22     | 10.8%   |
| Unknown                        | 13        | 13     | 7.39%   |
| Toshiba                        | 13        | 14     | 7.39%   |
| Sandisk                        | 10        | 10     | 5.68%   |
| SK hynix                       | 9         | 10     | 5.11%   |
| Kingston                       | 9         | 10     | 5.11%   |
| Micron Technology              | 6         | 8      | 3.41%   |
| HGST                           | 6         | 6      | 3.41%   |
| Intel                          | 5         | 6      | 2.84%   |
| Hitachi                        | 4         | 4      | 2.27%   |
| Crucial                        | 4         | 4      | 2.27%   |
| LITEON                         | 3         | 3      | 1.7%    |
| China                          | 3         | 3      | 1.7%    |
| SPCC                           | 2         | 3      | 1.14%   |
| Silicon Motion                 | 2         | 2      | 1.14%   |
| KIOXIA                         | 2         | 2      | 1.14%   |
| V-GeN                          | 1         | 1      | 0.57%   |
| Transcend                      | 1         | 1      | 0.57%   |
| Solid State Storage Technology | 1         | 1      | 0.57%   |
| Phison                         | 1         | 1      | 0.57%   |
| Patriot                        | 1         | 1      | 0.57%   |
| OEM                            | 1         | 1      | 0.57%   |
| OCZ                            | 1         | 1      | 0.57%   |
| Netac                          | 1         | 1      | 0.57%   |
| Microtech                      | 1         | 1      | 0.57%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.57%   |
| Kingston Technology Company    | 1         | 1      | 0.57%   |
| KingSpec                       | 1         | 1      | 0.57%   |
| JMicron Technology             | 1         | 1      | 0.57%   |
| Intenso                        | 1         | 1      | 0.57%   |
| Fujitsu                        | 1         | 2      | 0.57%   |
| FORESEE                        | 1         | 1      | 0.57%   |
| Apple                          | 1         | 2      | 0.57%   |
| ADATA Technology               | 1         | 1      | 0.57%   |
| A-DATA Technology              | 1         | 1      | 0.57%   |
| Unknown                        | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 6         | 3.31%   |
| Toshiba MQ01ABF050 500GB                           | 4         | 2.21%   |
| Kingston SA400S37240G 240GB SSD                    | 4         | 2.21%   |
| Toshiba MQ01ABD100 1TB                             | 3         | 1.66%   |
| Crucial CT240BX500SSD1 240GB                       | 3         | 1.66%   |
| WDC WD5000LPCX-24VHAT0 500GB                       | 2         | 1.1%    |
| Unknown MMC Card                                   | 2         | 1.1%    |
| Seagate ST9320325AS 320GB                          | 2         | 1.1%    |
| Seagate ST500LM012 HN-M500MBB 500GB                | 2         | 1.1%    |
| Seagate ST2000LM007-1R8174 2TB                     | 2         | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 1.1%    |
| Samsung SSD 850 EVO 500GB                          | 2         | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 1.1%    |
| Samsung MZVLW256HEHP-000H1 256GB                   | 2         | 1.1%    |
| HGST HTS545050A7E680 500GB                         | 2         | 1.1%    |
| WDC WDS480G2G0B-00EPW0 480GB SSD                   | 1         | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 1         | 0.55%   |
| WDC WD7500BPVT-24HXZT3 752GB                       | 1         | 0.55%   |
| WDC WD5000LPZX-75Z10T0 500GB                       | 1         | 0.55%   |
| WDC WD5000LPVX-80V0TT0 500GB                       | 1         | 0.55%   |
| WDC WD5000LPVX-08V0TT6 500GB                       | 1         | 0.55%   |
| WDC WD5000LPCX-24C6HT0 500GB                       | 1         | 0.55%   |
| WDC WD3200BEVT-60A23T0 320GB                       | 1         | 0.55%   |
| WDC WD3200BEVT-22ZCT0 320GB                        | 1         | 0.55%   |
| WDC WD3200BEVT-08A23T1 320GB                       | 1         | 0.55%   |
| WDC WD10SPZX-35Z10T0 1TB                           | 1         | 0.55%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 0.55%   |
| WDC WD10SPZX-08Z10 1TB                             | 1         | 0.55%   |
| WDC WD10JPVX-60JC3T1 1TB                           | 1         | 0.55%   |
| WDC WD10JPVX-60JC3T0 1TB                           | 1         | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.55%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 0.55%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 0.55%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB               | 1         | 0.55%   |
| WDC PC SN720 SDAPNTW-512G-1127 512GB               | 1         | 0.55%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 0.55%   |
| WDC PC SN520 NVMe 256GB                            | 1         | 0.55%   |
| V-GeN V-GEN10SM19AR120SDK 120GB SSD                | 1         | 0.55%   |
| Unknown SSO256GTLC9-SB3-4L 256GB SSD               | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 26     | 35.94%  |
| WDC                 | 17        | 18     | 26.56%  |
| Toshiba             | 11        | 12     | 17.19%  |
| HGST                | 6         | 6      | 9.38%   |
| Hitachi             | 4         | 4      | 6.25%   |
| Samsung Electronics | 1         | 1      | 1.56%   |
| OEM                 | 1         | 1      | 1.56%   |
| Fujitsu             | 1         | 2      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 8      | 16.33%  |
| Samsung Electronics | 7         | 8      | 14.29%  |
| Kingston            | 7         | 8      | 14.29%  |
| WDC                 | 3         | 3      | 6.12%   |
| Crucial             | 3         | 3      | 6.12%   |
| China               | 3         | 3      | 6.12%   |
| SPCC                | 2         | 3      | 4.08%   |
| SK hynix            | 2         | 2      | 4.08%   |
| Micron Technology   | 2         | 3      | 4.08%   |
| LITEON              | 2         | 2      | 4.08%   |
| V-GeN               | 1         | 1      | 2.04%   |
| Unknown             | 1         | 1      | 2.04%   |
| Transcend           | 1         | 1      | 2.04%   |
| OCZ                 | 1         | 1      | 2.04%   |
| Netac               | 1         | 1      | 2.04%   |
| Microtech           | 1         | 1      | 2.04%   |
| KingSpec            | 1         | 1      | 2.04%   |
| JMicron Technology  | 1         | 1      | 2.04%   |
| Intenso             | 1         | 1      | 2.04%   |
| Intel               | 1         | 2      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 70     | 36.84%  |
| NVMe | 51        | 57     | 29.82%  |
| SSD  | 45        | 54     | 26.32%  |
| MMC  | 12        | 13     | 7.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 92        | 119    | 57.86%  |
| NVMe | 51        | 57     | 32.08%  |
| MMC  | 12        | 13     | 7.55%   |
| SAS  | 4         | 5      | 2.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 81     | 62.75%  |
| 0.51-1.0   | 35        | 40     | 34.31%  |
| 1.01-2.0   | 2         | 2      | 1.96%   |
| 4.01-10.0  | 1         | 1      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 50        | 34.72%  |
| 101-250        | 37        | 25.69%  |
| 501-1000       | 30        | 20.83%  |
| 1001-2000      | 10        | 6.94%   |
| More than 3000 | 4         | 2.78%   |
| 21-50          | 4         | 2.78%   |
| 51-100         | 4         | 2.78%   |
| Unknown        | 3         | 2.08%   |
| 2001-3000      | 1         | 0.69%   |
| 1-20           | 1         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 33        | 23.08%  |
| 21-50     | 32        | 22.38%  |
| 101-250   | 24        | 16.78%  |
| 51-100    | 21        | 14.69%  |
| 251-500   | 18        | 12.59%  |
| 501-1000  | 6         | 4.2%    |
| 1001-2000 | 4         | 2.8%    |
| Unknown   | 3         | 2.1%    |
| 2001-3000 | 2         | 1.4%    |

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
| Intenso lntenso SSD Sata III 480GB            | 1         | 1      | 8.33%   |
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
| Detected | 71        | 97     | 47.33%  |
| Works    | 66        | 83     | 44%     |
| Malfunc  | 12        | 13     | 8%      |
| Failed   | 1         | 1      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 98        | 62.03%  |
| Samsung Electronics            | 11        | 6.96%   |
| AMD                            | 10        | 6.33%   |
| SK hynix                       | 7         | 4.43%   |
| SanDisk                        | 6         | 3.8%    |
| Micron Technology              | 4         | 2.53%   |
| KIOXIA                         | 3         | 1.9%    |
| Kingston Technology Company    | 3         | 1.9%    |
| Silicon Motion                 | 2         | 1.27%   |
| MAXIO Technology (Hangzhou)    | 2         | 1.27%   |
| Zhaoxin                        | 1         | 0.63%   |
| Toshiba America Info Systems   | 1         | 0.63%   |
| Solid State Storage Technology | 1         | 0.63%   |
| Shenzhen Longsys Electronics   | 1         | 0.63%   |
| Realtek Semiconductor          | 1         | 0.63%   |
| Phison Electronics             | 1         | 0.63%   |
| Micron/Crucial Technology      | 1         | 0.63%   |
| Lite-On Technology             | 1         | 0.63%   |
| JMicron Technology             | 1         | 0.63%   |
| Apple                          | 1         | 0.63%   |
| ADATA Technology               | 1         | 0.63%   |
| Unknown                        | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 9.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 7.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 6.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 6.06%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 5.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 4.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 3.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 3.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 3.03%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 2.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 2.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.42%   |
| SK hynix BC511 NVMe SSD                                                          | 3         | 1.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 3         | 1.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.82%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 1.21%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.21%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 1.21%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 1.21%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.21%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.21%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G/KH-40000 StorX AHCI Controller            | 1         | 0.61%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.61%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 0.61%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 1         | 0.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.61%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                | 1         | 0.61%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.61%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                            | 1         | 0.61%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 0.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 0.61%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 1         | 0.61%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                              | 1         | 0.61%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                         | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 101       | 62.35%  |
| NVMe | 50        | 30.86%  |
| RAID | 7         | 4.32%   |
| IDE  | 4         | 2.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 115       | 82.14%  |
| AMD          | 24        | 17.14%  |
| CentaurHauls | 1         | 0.71%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 3.57%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 2.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 2.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.14%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 2.14%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 2.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.14%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.43%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.43%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.43%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.43%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.43%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.43%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.43%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.43%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.43%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.43%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.43%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.43%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.43%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.43%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.43%   |
| AMD Ryzen 5 4600U with Radeon Graphics        | 2         | 1.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.43%   |
| AMD 3020e with Radeon Graphics                | 2         | 1.43%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.71%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.71%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.71%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.71%   |
| Intel Core M-5Y71 CPU @ 1.20GHz               | 1         | 0.71%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.71%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.71%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 27.86%  |
| Intel Core i7           | 31        | 22.14%  |
| Other                   | 12        | 8.57%   |
| Intel Core i3           | 10        | 7.14%   |
| Intel Celeron           | 9         | 6.43%   |
| AMD Ryzen 7             | 7         | 5%      |
| AMD Ryzen 5             | 6         | 4.29%   |
| Intel Core 2 Duo        | 4         | 2.86%   |
| Intel Pentium Dual-Core | 3         | 2.14%   |
| Intel Atom              | 3         | 2.14%   |
| AMD Ryzen 3             | 3         | 2.14%   |
| Intel Pentium           | 2         | 1.43%   |
| AMD A10                 | 2         | 1.43%   |
| Intel Pentium Silver    | 1         | 0.71%   |
| Intel Core m3           | 1         | 0.71%   |
| Intel Core M            | 1         | 0.71%   |
| Intel Core i9           | 1         | 0.71%   |
| Intel Celeron Dual-Core | 1         | 0.71%   |
| AMD Ryzen 7 PRO         | 1         | 0.71%   |
| AMD Ryzen 5 PRO         | 1         | 0.71%   |
| AMD E1                  | 1         | 0.71%   |
| AMD E                   | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 73        | 52.14%  |
| 4      | 48        | 34.29%  |
| 6      | 7         | 5%      |
| 8      | 6         | 4.29%   |
| 12     | 2         | 1.43%   |
| 10     | 2         | 1.43%   |
| 14     | 1         | 0.71%   |
| 1      | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 109       | 77.86%  |
| 1      | 31        | 22.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 129       | 92.14%  |
| Unknown        | 11        | 7.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 18.31%  |
| 0x806ec    | 12        | 8.45%   |
| 0x306a9    | 10        | 7.04%   |
| 0x40651    | 9         | 6.34%   |
| 0x806e9    | 8         | 5.63%   |
| 0x306d4    | 7         | 4.93%   |
| 0x406e3    | 6         | 4.23%   |
| 0x206a7    | 6         | 4.23%   |
| 0x906ea    | 5         | 3.52%   |
| 0x1067a    | 4         | 2.82%   |
| 0x906a3    | 3         | 2.11%   |
| 0x806ea    | 3         | 2.11%   |
| 0x08600106 | 3         | 2.11%   |
| 0x08108109 | 3         | 2.11%   |
| 0x906e9    | 2         | 1.41%   |
| 0x806c1    | 2         | 1.41%   |
| 0x706a8    | 2         | 1.41%   |
| 0x406c4    | 2         | 1.41%   |
| 0x20655    | 2         | 1.41%   |
| 0x08600104 | 2         | 1.41%   |
| 0x08200103 | 2         | 1.41%   |
| 0x08108102 | 2         | 1.41%   |
| 0xb06a3    | 1         | 0.7%    |
| 0xb06a2    | 1         | 0.7%    |
| 0xa0652    | 1         | 0.7%    |
| 0x806d1    | 1         | 0.7%    |
| 0x806c2    | 1         | 0.7%    |
| 0x706a1    | 1         | 0.7%    |
| 0x6fd      | 1         | 0.7%    |
| 0x406c3    | 1         | 0.7%    |
| 0x30678    | 1         | 0.7%    |
| 0x10676    | 1         | 0.7%    |
| 0x0a704103 | 1         | 0.7%    |
| 0x0a50000c | 1         | 0.7%    |
| 0x0a50000b | 1         | 0.7%    |
| 0x0a404101 | 1         | 0.7%    |
| 0x08608102 | 1         | 0.7%    |
| 0x08600103 | 1         | 0.7%    |
| 0x08600102 | 1         | 0.7%    |
| 0x0810100b | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 25%     |
| IvyBridge        | 13        | 9.29%   |
| Haswell          | 11        | 7.86%   |
| Broadwell        | 10        | 7.14%   |
| Zen 2            | 7         | 5%      |
| SandyBridge      | 7         | 5%      |
| Penryn           | 7         | 5%      |
| Skylake          | 6         | 4.29%   |
| Silvermont       | 6         | 4.29%   |
| Zen+             | 5         | 3.57%   |
| Unknown          | 5         | 3.57%   |
| Goldmont plus    | 4         | 2.86%   |
| Alderlake Hybrid | 4         | 2.86%   |
| Zen              | 3         | 2.14%   |
| Westmere         | 3         | 2.14%   |
| TigerLake        | 3         | 2.14%   |
| Zen 3            | 2         | 1.43%   |
| Goldmont         | 2         | 1.43%   |
| Excavator        | 2         | 1.43%   |
| Bobcat           | 2         | 1.43%   |
| Icelake          | 1         | 0.71%   |
| Core             | 1         | 0.71%   |
| CometLake        | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 113       | 59.47%  |
| Nvidia  | 47        | 24.74%  |
| AMD     | 29        | 15.26%  |
| Zhaoxin | 1         | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 6.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.73%   |
| Intel HD Graphics 5500                                                                   | 9         | 4.69%   |
| Intel HD Graphics 620                                                                    | 8         | 4.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.65%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 3.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.13%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 3.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.6%    |
| Intel UHD Graphics 620                                                                   | 5         | 2.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.56%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.04%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.04%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 1.04%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.04%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.04%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1.04%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 1.04%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.04%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 1.04%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                                 | 2         | 1.04%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 1.04%   |
| Intel HD Graphics 630                                                                    | 2         | 1.04%   |
| Intel HD Graphics 500                                                                    | 2         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.04%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 1.04%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.04%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.52%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 46.43%  |
| Intel + Nvidia | 42        | 30%     |
| 1 x AMD        | 19        | 13.57%  |
| Intel + AMD    | 6         | 4.29%   |
| 1 x Nvidia     | 3         | 2.14%   |
| 2 x AMD        | 2         | 1.43%   |
| AMD + Nvidia   | 2         | 1.43%   |
| 1 x Zhaoxin    | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 112       | 79.43%  |
| Proprietary | 23        | 16.31%  |
| Unknown     | 6         | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 58.04%  |
| 1.01-2.0   | 29        | 20.28%  |
| 3.01-4.0   | 15        | 10.49%  |
| 0.01-0.5   | 12        | 8.39%   |
| 0.51-1.0   | 3         | 2.1%    |
| 5.01-6.0   | 1         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 19.59%  |
| BOE                     | 28        | 18.92%  |
| Chimei Innolux          | 21        | 14.19%  |
| Samsung Electronics     | 17        | 11.49%  |
| LG Display              | 17        | 11.49%  |
| CSO                     | 6         | 4.05%   |
| Hewlett-Packard         | 3         | 2.03%   |
| Goldstar                | 3         | 2.03%   |
| AOC                     | 3         | 2.03%   |
| Lenovo                  | 2         | 1.35%   |
| InfoVision              | 2         | 1.35%   |
| Chi Mei Optoelectronics | 2         | 1.35%   |
| ViewSonic               | 1         | 0.68%   |
| TMX                     | 1         | 0.68%   |
| Sharp                   | 1         | 0.68%   |
| SAC                     | 1         | 0.68%   |
| PANDA                   | 1         | 0.68%   |
| LG Philips              | 1         | 0.68%   |
| JDI                     | 1         | 0.68%   |
| Iiyama                  | 1         | 0.68%   |
| HKC                     | 1         | 0.68%   |
| HB@                     | 1         | 0.68%   |
| HannStar                | 1         | 0.68%   |
| Dell                    | 1         | 0.68%   |
| CS_                     | 1         | 0.68%   |
| BenQ                    | 1         | 0.68%   |
| Apple                   | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 2.01%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 2.01%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.34%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 1.34%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 2         | 1.34%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch             | 1         | 0.67%   |
| TMX TL140VDXP04-0 TMX1398 1920x1080 309x174mm 14.0-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0167 1280x1024 338x270mm 17.0-inch  | 1         | 0.67%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 700x400mm 31.7-inch     | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC864D 1920x1080 293x165mm 13.2-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC534B 1600x900 382x215mm 17.3-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                     | 1         | 0.67%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                 | 1         | 0.67%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.67%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.67%   |
| LG Display LP156WH1-TLA1 LGD6301 1366x768 344x194mm 15.5-inch         | 1         | 0.67%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x174mm 14.0-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 59        | 42.14%  |
| 1366x768 (WXGA)  | 51        | 36.43%  |
| 1600x900 (HD+)   | 6         | 4.29%   |
| 3840x2160 (4K)   | 4         | 2.86%   |
| 2560x1600        | 4         | 2.86%   |
| 2880x1800        | 3         | 2.14%   |
| 3000x2000        | 2         | 1.43%   |
| 2160x1440        | 2         | 1.43%   |
| 3440x1440        | 1         | 0.71%   |
| 3200x2000        | 1         | 0.71%   |
| 3200x1800 (QHD+) | 1         | 0.71%   |
| 2560x1440 (QHD)  | 1         | 0.71%   |
| 2288x1287        | 1         | 0.71%   |
| 1920x540         | 1         | 0.71%   |
| 1680x945         | 1         | 0.71%   |
| 1280x800 (WXGA)  | 1         | 0.71%   |
| 1280x1024 (SXGA) | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 59        | 39.86%  |
| 13      | 30        | 20.27%  |
| 14      | 25        | 16.89%  |
| 17      | 5         | 3.38%   |
| 23      | 4         | 2.7%    |
| 27      | 3         | 2.03%   |
| 21      | 3         | 2.03%   |
| 18      | 3         | 2.03%   |
| 16      | 3         | 2.03%   |
| 11      | 3         | 2.03%   |
| 32      | 2         | 1.35%   |
| 24      | 2         | 1.35%   |
| 12      | 2         | 1.35%   |
| 40      | 1         | 0.68%   |
| 31      | 1         | 0.68%   |
| 25      | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 102       | 70.34%  |
| 201-300     | 18        | 12.41%  |
| 501-600     | 9         | 6.21%   |
| 351-400     | 6         | 4.14%   |
| 401-500     | 5         | 3.45%   |
| 701-800     | 2         | 1.38%   |
| 801-900     | 1         | 0.69%   |
| 601-700     | 1         | 0.69%   |
| Unknown     | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 117       | 86.67%  |
| 16/10 | 12        | 8.89%   |
| 3/2   | 5         | 3.7%    |
| 5/4   | 1         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 59        | 39.6%   |
| 81-90          | 46        | 30.87%  |
| 71-80          | 9         | 6.04%   |
| 201-250        | 7         | 4.7%    |
| 141-150        | 4         | 2.68%   |
| 51-60          | 3         | 2.01%   |
| 351-500        | 3         | 2.01%   |
| 301-350        | 3         | 2.01%   |
| 251-300        | 3         | 2.01%   |
| 121-130        | 3         | 2.01%   |
| 111-120        | 3         | 2.01%   |
| 61-70          | 2         | 1.34%   |
| 151-200        | 1         | 0.67%   |
| 131-140        | 1         | 0.67%   |
| 501-1000       | 1         | 0.67%   |
| Unknown        | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 56        | 38.62%  |
| 121-160       | 52        | 35.86%  |
| 51-100        | 16        | 11.03%  |
| 161-240       | 14        | 9.66%   |
| More than 240 | 6         | 4.14%   |
| Unknown       | 1         | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 116       | 82.27%  |
| 2     | 20        | 14.18%  |
| 0     | 4         | 2.84%   |
| 3     | 1         | 0.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 91        | 43.13%  |
| Intel                           | 62        | 29.38%  |
| Qualcomm Atheros                | 35        | 16.59%  |
| Broadcom                        | 6         | 2.84%   |
| MediaTek                        | 3         | 1.42%   |
| Marvell Technology Group        | 3         | 1.42%   |
| Broadcom Limited                | 3         | 1.42%   |
| Xiaomi                          | 2         | 0.95%   |
| Ralink Technology               | 1         | 0.47%   |
| Ralink                          | 1         | 0.47%   |
| Qualcomm Atheros Communications | 1         | 0.47%   |
| OPPO Electronics                | 1         | 0.47%   |
| Huawei Technologies             | 1         | 0.47%   |
| Hewlett-Packard                 | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 22.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 7.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 4.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 3.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.86%   |
| Intel Wireless 3165                                               | 7         | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.63%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.22%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.22%   |
| Intel Wireless 7260                                               | 3         | 1.22%   |
| Intel Wireless 3160                                               | 3         | 1.22%   |
| Intel WiFi Link 5100                                              | 3         | 1.22%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.82%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 2         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.82%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.82%   |
| Intel Wireless 7265                                               | 2         | 0.82%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 2         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 42.96%  |
| Realtek Semiconductor           | 34        | 23.94%  |
| Qualcomm Atheros                | 34        | 23.94%  |
| Broadcom                        | 4         | 2.82%   |
| MediaTek                        | 3         | 2.11%   |
| Broadcom Limited                | 3         | 2.11%   |
| Ralink Technology               | 1         | 0.7%    |
| Ralink                          | 1         | 0.7%    |
| Qualcomm Atheros Communications | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 8.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 6.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 4.9%    |
| Intel Wireless 3165                                            | 7         | 4.9%    |
| Intel Wi-Fi 6 AX200                                            | 6         | 4.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.8%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 2.1%    |
| Intel Wireless 8265 / 8275                                     | 3         | 2.1%    |
| Intel Wireless 7260                                            | 3         | 2.1%    |
| Intel Wireless 3160                                            | 3         | 2.1%    |
| Intel WiFi Link 5100                                           | 3         | 2.1%    |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 2.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.4%    |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 2         | 1.4%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.4%    |
| Intel Wireless 7265                                            | 2         | 1.4%    |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 1.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.7%    |
| Realtek 802.11ac NIC                                           | 1         | 0.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.7%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.7%    |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 78        | 76.47%  |
| Intel                    | 10        | 9.8%    |
| Qualcomm Atheros         | 4         | 3.92%   |
| Marvell Technology Group | 3         | 2.94%   |
| Xiaomi                   | 2         | 1.96%   |
| Broadcom                 | 2         | 1.96%   |
| OPPO Electronics         | 1         | 0.98%   |
| Huawei Technologies      | 1         | 0.98%   |
| Hewlett-Packard          | 1         | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 53.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 18.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.96%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.98%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.98%   |
| OPPO RMX3623                                                      | 1         | 0.98%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.98%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.98%   |
| Huawei MAR-LX1M                                                   | 1         | 0.98%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 138       | 58.23%  |
| Ethernet | 99        | 41.77%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 83.57%  |
| Ethernet | 23        | 16.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 93        | 66.43%  |
| 1     | 43        | 30.71%  |
| 0     | 3         | 2.14%   |
| 3     | 1         | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 131       | 92.91%  |
| Yes  | 10        | 7.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 43.97%  |
| Qualcomm Atheros Communications | 20        | 17.24%  |
| Realtek Semiconductor           | 15        | 12.93%  |
| Foxconn / Hon Hai               | 8         | 6.9%    |
| Broadcom                        | 6         | 5.17%   |
| Realtek                         | 5         | 4.31%   |
| Lite-On Technology              | 3         | 2.59%   |
| IMC Networks                    | 3         | 2.59%   |
| Cambridge Silicon Radio         | 2         | 1.72%   |
| Toshiba                         | 1         | 0.86%   |
| Ralink Technology               | 1         | 0.86%   |
| Dell                            | 1         | 0.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 21        | 18.1%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 15        | 12.93%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 8.62%   |
| Intel AX201 Bluetooth                                                               | 9         | 7.76%   |
| Realtek Bluetooth Radio                                                             | 7         | 6.03%   |
| Intel AX200 Bluetooth                                                               | 6         | 5.17%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 4.31%   |
| Realtek 802.11ac WLAN Adapter                                                       | 5         | 4.31%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.72%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.72%   |
| Intel Bluetooth Device                                                              | 2         | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.72%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.72%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.86%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.86%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.86%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.86%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.86%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.86%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.86%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.86%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.86%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.86%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.86%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.86%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.86%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 0.86%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.86%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.86%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 112       | 72.73%  |
| AMD                 | 24        | 15.58%  |
| Nvidia              | 15        | 9.74%   |
| Zhaoxin             | 1         | 0.65%   |
| JMTek               | 1         | 0.65%   |
| Creative Technology | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 10.55%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 10.05%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 7.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 5.53%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 5.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 5.03%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 5.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 4.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 4.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 4.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 3.52%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.01%   |
| Nvidia Audio device                                                                               | 4         | 2.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.51%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.51%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 1.01%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.01%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.01%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.01%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.5%    |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000 High Definition Audio Controller                 | 1         | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.5%    |
| JMTek Speedlink PnP Sound Device                                                                  | 1         | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.5%    |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                      | 1         | 0.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 28.87%  |
| SK hynix            | 25        | 25.77%  |
| Unknown             | 10        | 10.31%  |
| Micron Technology   | 10        | 10.31%  |
| Smart               | 4         | 4.12%   |
| Kingston            | 4         | 4.12%   |
| Ramaxel Technology  | 3         | 3.09%   |
| Nanya Technology    | 3         | 3.09%   |
| Unknown (ABCD)      | 2         | 2.06%   |
| A-DATA Technology   | 2         | 2.06%   |
| Unknown (07FB)      | 1         | 1.03%   |
| Smart Brazil        | 1         | 1.03%   |
| MTASE               | 1         | 1.03%   |
| Kingmax             | 1         | 1.03%   |
| Crucial             | 1         | 1.03%   |
| ChangXin Memory     | 1         | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 3         | 2.94%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.96%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.96%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 2         | 1.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.96%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.96%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.96%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.98%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.98%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 0.98%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 0.98%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.98%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.98%   |
| Unknown RAM Module 2048MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.98%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.98%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.98%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s                 | 1         | 0.98%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.98%   |
| Unknown (07FB) RAM GST32G08SCL196P-26 32GB SODIMM DDR4 2667MT/s  | 1         | 0.98%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 1         | 0.98%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.98%   |
| SK hynix RAM MPPS4GBPC1600 1.35 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.98%   |
| SK hynix RAM Module 16384MB SODIMM DDR5 5600MT/s                 | 1         | 0.98%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 0.98%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.98%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.98%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 41        | 47.67%  |
| DDR3   | 21        | 24.42%  |
| LPDDR3 | 8         | 9.3%    |
| LPDDR4 | 7         | 8.14%   |
| DDR5   | 3         | 3.49%   |
| DDR2   | 3         | 3.49%   |
| LPDDR5 | 2         | 2.33%   |
| SDRAM  | 1         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 70        | 81.4%   |
| Row Of Chips | 15        | 17.44%  |
| Unknown      | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 37        | 40.66%  |
| 4096  | 31        | 34.07%  |
| 2048  | 13        | 14.29%  |
| 16384 | 7         | 7.69%   |
| 1024  | 2         | 2.2%    |
| 32768 | 1         | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 20        | 22.47%  |
| 1600    | 18        | 20.22%  |
| 3200    | 12        | 13.48%  |
| 2400    | 7         | 7.87%   |
| 2133    | 7         | 7.87%   |
| 1334    | 3         | 3.37%   |
| 1333    | 3         | 3.37%   |
| 4800    | 2         | 2.25%   |
| 3266    | 2         | 2.25%   |
| 800     | 2         | 2.25%   |
| Unknown | 2         | 2.25%   |
| 7467    | 1         | 1.12%   |
| 6400    | 1         | 1.12%   |
| 5600    | 1         | 1.12%   |
| 4267    | 1         | 1.12%   |
| 4266    | 1         | 1.12%   |
| 3733    | 1         | 1.12%   |
| 2933    | 1         | 1.12%   |
| 2666    | 1         | 1.12%   |
| 2048    | 1         | 1.12%   |
| 1867    | 1         | 1.12%   |
| 1066    | 1         | 1.12%   |

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
| Chicony Electronics                    | 32        | 25.81%  |
| IMC Networks                           | 12        | 9.68%   |
| Microdia                               | 11        | 8.87%   |
| Realtek Semiconductor                  | 10        | 8.06%   |
| Quanta                                 | 9         | 7.26%   |
| Sunplus Innovation Technology          | 7         | 5.65%   |
| Syntek                                 | 6         | 4.84%   |
| Suyin                                  | 6         | 4.84%   |
| Silicon Motion                         | 6         | 4.84%   |
| Lite-On Technology                     | 5         | 4.03%   |
| Bison Electronics                      | 5         | 4.03%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.42%   |
| Ricoh                                  | 2         | 1.61%   |
| Primax Electronics                     | 2         | 1.61%   |
| Alcor Micro                            | 2         | 1.61%   |
| Luxvisions Innotech Limited            | 1         | 0.81%   |
| LG Electronics                         | 1         | 0.81%   |
| Lenovo                                 | 1         | 0.81%   |
| kingcome                               | 1         | 0.81%   |
| icSpring                               | 1         | 0.81%   |
| Goodong Industry                       | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 8         | 6.45%   |
| IMC Networks Integrated Camera           | 5         | 4.03%   |
| Quanta HD User Facing                    | 4         | 3.23%   |
| Chicony EasyCamera                       | 4         | 3.23%   |
| Syntek EasyCamera                        | 3         | 2.42%   |
| Silicon Motion Web Camera                | 3         | 2.42%   |
| Quanta HP TrueVision HD Camera           | 3         | 2.42%   |
| IMC Networks ov9734_azurewave_camera     | 3         | 2.42%   |
| Chicony TOSHIBA Web Camera - HD          | 3         | 2.42%   |
| Syntek Integrated Camera                 | 2         | 1.61%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.61%   |
| Sunplus HD WebCam                        | 2         | 1.61%   |
| Realtek USB Camera                       | 2         | 1.61%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.61%   |
| Realtek HP "Truevision HD" laptop camera | 2         | 1.61%   |
| Primax HP HD Webcam [Fixed]              | 2         | 1.61%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.61%   |
| Lite-On Integrated Camera                | 2         | 1.61%   |
| IMC Networks HD Camera                   | 2         | 1.61%   |
| Chicony HP Webcam                        | 2         | 1.61%   |
| Chicony HP HD Webcam                     | 2         | 1.61%   |
| Bison Integrated Camera                  | 2         | 1.61%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.81%   |
| Suyin Integrated_Webcam_HD               | 1         | 0.81%   |
| Suyin HP Webcam 101                      | 1         | 0.81%   |
| Suyin HP Truevision HD                   | 1         | 0.81%   |
| Suyin HD WebCam                          | 1         | 0.81%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.81%   |
| Suyin 1.3M HD WebCam                     | 1         | 0.81%   |
| Sunplus XiaoMi USB 2.0 Webcam            | 1         | 0.81%   |
| Sunplus HP Wide Vision HD                | 1         | 0.81%   |
| Sunplus Asus Webcam                      | 1         | 0.81%   |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.81%   |
| Silicon Motion WebCam SC-0311139N        | 1         | 0.81%   |
| Silicon Motion ATIV VGA Camera           | 1         | 0.81%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 0.81%   |
| Ricoh Laptop_Integrated_Webcam_FHD       | 1         | 0.81%   |
| Realtek Laptop_Integrated_Webcam_HD      | 1         | 0.81%   |
| Realtek HP Wide Vision HD Camera         | 1         | 0.81%   |
| Realtek HP Truevision HD                 | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 37.04%  |
| Shenzhen Goodix Technology | 9         | 33.33%  |
| Upek                       | 5         | 18.52%  |
| Synaptics                  | 2         | 7.41%   |
| Elan Microelectronics      | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 6         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 18.52%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 11.11%  |
| Validity Sensors VFS491                                | 2         | 7.41%   |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 7.41%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 7.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 7.41%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.7%    |
| Elan ELAN:Fingerprint                                  | 1         | 3.7%    |

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
| 0     | 92        | 64.79%  |
| 1     | 42        | 29.58%  |
| 2     | 8         | 5.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 27        | 46.55%  |
| Graphics card         | 16        | 27.59%  |
| Multimedia controller | 6         | 10.34%  |
| Chipcard              | 5         | 8.62%   |
| Sound                 | 2         | 3.45%   |
| Storage               | 1         | 1.72%   |
| Camera                | 1         | 1.72%   |


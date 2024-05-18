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

Total: 202

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro11,1              | [0b8f54ed65](https://linux-hardware.org/?probe=0b8f54ed65) | Apr 08, 2024 |
| Insyde        | BayTrail                    | [89d859d241](https://linux-hardware.org/?probe=89d859d241) | Mar 14, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [5b2bd502f2](https://linux-hardware.org/?probe=5b2bd502f2) | Mar 05, 2024 |
| HP            | Pavilion g6                 | [b12a505c7c](https://linux-hardware.org/?probe=b12a505c7c) | Feb 25, 2024 |
| Lenovo        | ThinkPad E550 20DFA06NCD    | [7858b1e150](https://linux-hardware.org/?probe=7858b1e150) | Feb 12, 2024 |
| Unknown       | Unknown                     | [7f23752859](https://linux-hardware.org/?probe=7f23752859) | Feb 06, 2024 |
| KUU           | Andes II                    | [512394ef85](https://linux-hardware.org/?probe=512394ef85) | Jan 04, 2024 |
| Timi          | TM1709                      | [79d0628d57](https://linux-hardware.org/?probe=79d0628d57) | Jan 03, 2024 |
| Timi          | TM1709                      | [b934e033e4](https://linux-hardware.org/?probe=b934e033e4) | Jan 03, 2024 |
| KUU           | Andes II                    | [bda39c51cd](https://linux-hardware.org/?probe=bda39c51cd) | Jan 03, 2024 |
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
| Deepin         | 29        | 19.21%  |
| Deepin 15.11   | 23        | 15.23%  |
| Deepin 20      | 20        | 13.25%  |
| Deepin 23      | 15        | 9.93%   |
| UOS 20         | 14        | 9.27%   |
| Deepin 15.9.2  | 8         | 5.3%    |
| Deepin 20.9    | 6         | 3.97%   |
| Deepin 20.8    | 6         | 3.97%   |
| Deepin 20.3    | 5         | 3.31%   |
| Deepin 20.5    | 4         | 2.65%   |
| Deepin 20.1    | 4         | 2.65%   |
| Deepin 20 beta | 3         | 1.99%   |
| Deepin 20.2.4  | 2         | 1.32%   |
| Deepin 15.9.3  | 2         | 1.32%   |
| Deepin 2014.3  | 1         | 0.66%   |
| Deepin 20.7.1  | 1         | 0.66%   |
| Deepin 20.7    | 1         | 0.66%   |
| Deepin 20.4    | 1         | 0.66%   |
| Deepin 20.2.3  | 1         | 0.66%   |
| Deepin 20.2.1  | 1         | 0.66%   |
| Deepin 15.9    | 1         | 0.66%   |
| Deepin 15.8    | 1         | 0.66%   |
| Deepin 15.10.1 | 1         | 0.66%   |
| Deepin 15.10   | 1         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Deepin | 146       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.15.0-30deepin-generic             | 32        | 21.19%  |
| 5.4.50-amd64-desktop                | 16        | 10.6%   |
| 4.15.0-29deepin-generic             | 12        | 7.95%   |
| 5.4.70-amd64-desktop                | 9         | 5.96%   |
| 5.10.60-amd64-desktop               | 9         | 5.96%   |
| 6.1.32-amd64-desktop-hwe            | 8         | 5.3%    |
| 5.18.17-amd64-desktop-community-hwe | 6         | 3.97%   |
| 5.10.0-amd64-desktop                | 6         | 3.97%   |
| 5.7.7-amd64-desktop                 | 4         | 2.65%   |
| 5.18.17-amd64-desktop-hwe           | 4         | 2.65%   |
| 5.10.41-amd64-desktop               | 4         | 2.65%   |
| 5.10.29-amd64-desktop               | 4         | 2.65%   |
| 5.3.0-3-amd64                       | 3         | 1.99%   |
| 5.15.77-amd64-desktop               | 3         | 1.99%   |
| 5.15.1-amd64-desktop                | 3         | 1.99%   |
| 6.1.11-amd64-desktop-hwe            | 2         | 1.32%   |
| 5.15.45-amd64-desktop               | 2         | 1.32%   |
| 5.15.24-amd64-desktop               | 2         | 1.32%   |
| 5.10.50-amd64-desktop               | 2         | 1.32%   |
| 5.10.5-amd64-desktop+               | 2         | 1.32%   |
| 5.10.18-amd64-desktop               | 2         | 1.32%   |
| 5.10.101-amd64-desktop              | 2         | 1.32%   |
| 4.19.0-amd64-desktop                | 2         | 1.32%   |
| 6.5.0                               | 1         | 0.66%   |
| 5.8.14-amd64-desktop                | 1         | 0.66%   |
| 5.6.14-050614-generic               | 1         | 0.66%   |
| 5.6.12-xanmod1                      | 1         | 0.66%   |
| 5.5.4-xanmod3                       | 1         | 0.66%   |
| 5.3.8-xanmod6                       | 1         | 0.66%   |
| 5.18.4-amd64-desktop-hwe            | 1         | 0.66%   |
| 5.15.34-amd64-desktop               | 1         | 0.66%   |
| 5.10.83-amd64-desktop               | 1         | 0.66%   |
| 5.10.36-amd64-desktop               | 1         | 0.66%   |
| 5.1.0-050100rc2-generic             | 1         | 0.66%   |
| 4.15.0-135-generic                  | 1         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 45        | 29.8%   |
| 5.4.50   | 16        | 10.6%   |
| 5.18.17  | 10        | 6.62%   |
| 5.4.70   | 9         | 5.96%   |
| 5.10.60  | 9         | 5.96%   |
| 6.1.32   | 8         | 5.3%    |
| 5.10.0   | 6         | 3.97%   |
| 5.7.7    | 4         | 2.65%   |
| 5.10.41  | 4         | 2.65%   |
| 5.10.29  | 4         | 2.65%   |
| 5.3.0    | 3         | 1.99%   |
| 5.15.77  | 3         | 1.99%   |
| 5.15.1   | 3         | 1.99%   |
| 6.1.11   | 2         | 1.32%   |
| 5.15.45  | 2         | 1.32%   |
| 5.15.24  | 2         | 1.32%   |
| 5.10.50  | 2         | 1.32%   |
| 5.10.5   | 2         | 1.32%   |
| 5.10.18  | 2         | 1.32%   |
| 5.10.101 | 2         | 1.32%   |
| 4.19.0   | 2         | 1.32%   |
| 6.5.0    | 1         | 0.66%   |
| 5.8.14   | 1         | 0.66%   |
| 5.6.14   | 1         | 0.66%   |
| 5.6.12   | 1         | 0.66%   |
| 5.5.4    | 1         | 0.66%   |
| 5.3.8    | 1         | 0.66%   |
| 5.18.4   | 1         | 0.66%   |
| 5.15.34  | 1         | 0.66%   |
| 5.10.83  | 1         | 0.66%   |
| 5.10.36  | 1         | 0.66%   |
| 5.1.0    | 1         | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15    | 45        | 30%     |
| 5.10    | 33        | 22%     |
| 5.4     | 25        | 16.67%  |
| 5.18    | 11        | 7.33%   |
| 6.1     | 10        | 6.67%   |
| 5.15    | 10        | 6.67%   |
| 5.7     | 4         | 2.67%   |
| 5.3     | 4         | 2.67%   |
| 5.6     | 2         | 1.33%   |
| 4.19    | 2         | 1.33%   |
| 6.5     | 1         | 0.67%   |
| 5.8     | 1         | 0.67%   |
| 5.5     | 1         | 0.67%   |
| 5.1     | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 146       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Deepin  | 115       | 78.77%  |
| Unknown | 21        | 14.38%  |
| DDE     | 9         | 6.16%   |
| KDE     | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 146       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 59        | 39.86%  |
| LightDM | 50        | 33.78%  |
| TDM     | 39        | 26.35%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 31        | 21.23%  |
| Unknown | 30        | 20.55%  |
| zh_CN   | 26        | 17.81%  |
| pt_BR   | 15        | 10.27%  |
| es_ES   | 11        | 7.53%   |
| de_DE   | 10        | 6.85%   |
| ru_RU   | 8         | 5.48%   |
| tr_TR   | 3         | 2.05%   |
| it_IT   | 3         | 2.05%   |
| sv_SE   | 2         | 1.37%   |
| pl_PL   | 2         | 1.37%   |
| fr_FR   | 2         | 1.37%   |
| nl_NL   | 1         | 0.68%   |
| ja_JP   | 1         | 0.68%   |
| en_GB   | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 99        | 67.35%  |
| BIOS | 48        | 32.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 130       | 89.04%  |
| Unknown | 14        | 9.59%   |
| Tmpfs   | 1         | 0.68%   |
| Overlay | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 75        | 51.02%  |
| Unknown | 58        | 39.46%  |
| MBR     | 14        | 9.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 78.38%  |
| Yes       | 32        | 21.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 103       | 70.07%  |
| Yes       | 44        | 29.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 37        | 25.34%  |
| Hewlett-Packard     | 25        | 17.12%  |
| Acer                | 15        | 10.27%  |
| Dell                | 13        | 8.9%    |
| Samsung Electronics | 7         | 4.79%   |
| HUAWEI              | 7         | 4.79%   |
| ASUSTek Computer    | 7         | 4.79%   |
| Sony                | 5         | 3.42%   |
| Toshiba             | 4         | 2.74%   |
| Timi                | 4         | 2.74%   |
| Unknown             | 3         | 2.05%   |
| Google              | 2         | 1.37%   |
| UNOWHY              | 1         | 0.68%   |
| Standard            | 1         | 0.68%   |
| Positivo            | 1         | 0.68%   |
| MSI                 | 1         | 0.68%   |
| Microtech           | 1         | 0.68%   |
| KUU                 | 1         | 0.68%   |
| itel Mobile Limited | 1         | 0.68%   |
| Insyde              | 1         | 0.68%   |
| Infinix             | 1         | 0.68%   |
| HONOR               | 1         | 0.68%   |
| Hometech            | 1         | 0.68%   |
| Gateway             | 1         | 0.68%   |
| Fujitsu             | 1         | 0.68%   |
| Chuwi               | 1         | 0.68%   |
| CCE                 | 1         | 0.68%   |
| BQ                  | 1         | 0.68%   |
| Apple               | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 5         | 3.42%   |
| Samsung 340XAA/350XAA/550XAA                      | 2         | 1.37%   |
| Lenovo IdeaPad 120S-11IAP 81A4                    | 2         | 1.37%   |
| HP Pavilion Notebook                              | 2         | 1.37%   |
| HP Pavilion 15                                    | 2         | 1.37%   |
| HP ENVY 15                                        | 2         | 1.37%   |
| Acer Nitro AN515-54                               | 2         | 1.37%   |
| UNOWHY Y13G012S4EI                                | 1         | 0.68%   |
| Toshiba Satellite L75-C                           | 1         | 0.68%   |
| Toshiba Satellite E55t-A                          | 1         | 0.68%   |
| Toshiba Satellite C850D-11K                       | 1         | 0.68%   |
| Toshiba Satellite C850-1H6                        | 1         | 0.68%   |
| Timi TM1709                                       | 1         | 0.68%   |
| Timi TM1701                                       | 1         | 0.68%   |
| Timi RedmiBook Air 13                             | 1         | 0.68%   |
| Timi Redmi G 2022                                 | 1         | 0.68%   |
| Standard MB45II/MB45IN                            | 1         | 0.68%   |
| Sony VPCYB25AB                                    | 1         | 0.68%   |
| Sony VGN-NS140D                                   | 1         | 0.68%   |
| Sony VGN-AW11Z_B                                  | 1         | 0.68%   |
| Sony SVF14A190X                                   | 1         | 0.68%   |
| Sony SVE14135CXP                                  | 1         | 0.68%   |
| Samsung 800G5M/800G5W                             | 1         | 0.68%   |
| Samsung 550P5C/550P7C                             | 1         | 0.68%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.68%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 1         | 0.68%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.68%   |
| Positivo C14CU51                                  | 1         | 0.68%   |
| MSI GL72M 7REX                                    | 1         | 0.68%   |
| Microtech ebookPro                                | 1         | 0.68%   |
| Lenovo ZHAOYANG K4e-ITL 82F8                      | 1         | 0.68%   |
| Lenovo ZHAOYANG CF4620Z-A123 59082537             | 1         | 0.68%   |
| Lenovo Yoga 3 Pro-1370 80HE                       | 1         | 0.68%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN                 | 1         | 0.68%   |
| Lenovo XiaoXin-15ARE 2020 81YR                    | 1         | 0.68%   |
| Lenovo V310-15ISK 80SY                            | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW       | 1         | 0.68%   |
| Lenovo ThinkPad T490s 20NX003AUS                  | 1         | 0.68%   |
| Lenovo ThinkPad T420 4236CU8                      | 1         | 0.68%   |
| Lenovo ThinkPad T420 4180M8P                      | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 11        | 7.53%   |
| Dell Inspiron           | 9         | 6.16%   |
| Lenovo IdeaPad          | 8         | 5.48%   |
| Acer Aspire             | 8         | 5.48%   |
| HP Pavilion             | 6         | 4.11%   |
| HP EliteBook            | 6         | 4.11%   |
| HP Laptop               | 5         | 3.42%   |
| Unknown                 | 5         | 3.42%   |
| Toshiba Satellite       | 4         | 2.74%   |
| Lenovo ThinkBook        | 4         | 2.74%   |
| Lenovo Legion           | 4         | 2.74%   |
| Acer Nitro              | 4         | 2.74%   |
| Samsung 340XAA          | 2         | 1.37%   |
| Lenovo ZHAOYANG         | 2         | 1.37%   |
| HP ENVY                 | 2         | 1.37%   |
| Dell Latitude           | 2         | 1.37%   |
| Acer Swift              | 2         | 1.37%   |
| UNOWHY Y13G012S4EI      | 1         | 0.68%   |
| Timi TM1709             | 1         | 0.68%   |
| Timi TM1701             | 1         | 0.68%   |
| Timi RedmiBook          | 1         | 0.68%   |
| Timi Redmi              | 1         | 0.68%   |
| Standard MB45II         | 1         | 0.68%   |
| Sony VPCYB25AB          | 1         | 0.68%   |
| Sony VGN-NS140D         | 1         | 0.68%   |
| Sony VGN-AW11Z          | 1         | 0.68%   |
| Sony SVF14A190X         | 1         | 0.68%   |
| Sony SVE14135CXP        | 1         | 0.68%   |
| Samsung 800G5M          | 1         | 0.68%   |
| Samsung 550P5C          | 1         | 0.68%   |
| Samsung 500R4K          | 1         | 0.68%   |
| Samsung 300E4A          | 1         | 0.68%   |
| Samsung 270E5J          | 1         | 0.68%   |
| Positivo C14CU51        | 1         | 0.68%   |
| MSI GL72M               | 1         | 0.68%   |
| Microtech ebookPro      | 1         | 0.68%   |
| Lenovo Yoga             | 1         | 0.68%   |
| Lenovo XiaoXinAir-14ARE | 1         | 0.68%   |
| Lenovo XiaoXin-15ARE    | 1         | 0.68%   |
| Lenovo V310-15ISK       | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 17        | 11.64%  |
| 2021    | 14        | 9.59%   |
| 2018    | 14        | 9.59%   |
| 2017    | 14        | 9.59%   |
| 2020    | 10        | 6.85%   |
| 2015    | 10        | 6.85%   |
| 2014    | 10        | 6.85%   |
| 2012    | 10        | 6.85%   |
| 2013    | 8         | 5.48%   |
| 2011    | 8         | 5.48%   |
| 2010    | 7         | 4.79%   |
| 2022    | 6         | 4.11%   |
| 2016    | 6         | 4.11%   |
| 2023    | 5         | 3.42%   |
| 2009    | 4         | 2.74%   |
| 2008    | 2         | 1.37%   |
| Unknown | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 146       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 137       | 93.84%  |
| Enabled  | 9         | 6.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 144       | 98.63%  |
| Yes  | 2         | 1.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 52        | 35.62%  |
| 8.01-16.0   | 29        | 19.86%  |
| 3.01-4.0    | 28        | 19.18%  |
| 16.01-24.0  | 23        | 15.75%  |
| 32.01-64.0  | 7         | 4.79%   |
| 1.01-2.0    | 5         | 3.42%   |
| 2.01-3.0    | 1         | 0.68%   |
| 64.01-256.0 | 1         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 48        | 31.79%  |
| 1.01-2.0  | 45        | 29.8%   |
| 3.01-4.0  | 24        | 15.89%  |
| 4.01-8.0  | 22        | 14.57%  |
| 0.51-1.0  | 8         | 5.3%    |
| 8.01-16.0 | 4         | 2.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 73.65%  |
| 2      | 38        | 25.68%  |
| 3      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 68.49%  |
| Yes       | 46        | 31.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 70.55%  |
| No        | 43        | 29.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 97.95%  |
| No        | 3         | 2.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 82.88%  |
| No        | 25        | 17.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| Brazil                | 31        | 21.09%  |
| China                 | 27        | 18.37%  |
| Germany               | 11        | 7.48%   |
| Russia                | 6         | 4.08%   |
| USA                   | 5         | 3.4%    |
| Turkey                | 5         | 3.4%    |
| Spain                 | 5         | 3.4%    |
| Indonesia             | 4         | 2.72%   |
| Poland                | 3         | 2.04%   |
| Japan                 | 3         | 2.04%   |
| Italy                 | 3         | 2.04%   |
| Chile                 | 3         | 2.04%   |
| Canada                | 3         | 2.04%   |
| Sweden                | 2         | 1.36%   |
| Panama                | 2         | 1.36%   |
| India                 | 2         | 1.36%   |
| Hong Kong             | 2         | 1.36%   |
| Bulgaria              | 2         | 1.36%   |
| Austria               | 2         | 1.36%   |
| Vietnam               | 1         | 0.68%   |
| Venezuela             | 1         | 0.68%   |
| Tunisia               | 1         | 0.68%   |
| Sri Lanka             | 1         | 0.68%   |
| South Africa          | 1         | 0.68%   |
| Singapore             | 1         | 0.68%   |
| Serbia                | 1         | 0.68%   |
| Sao Tome and Principe | 1         | 0.68%   |
| Portugal              | 1         | 0.68%   |
| Pakistan              | 1         | 0.68%   |
| Netherlands           | 1         | 0.68%   |
| Mexico                | 1         | 0.68%   |
| Lebanon               | 1         | 0.68%   |
| Kenya                 | 1         | 0.68%   |
| Iran                  | 1         | 0.68%   |
| Greece                | 1         | 0.68%   |
| France                | 1         | 0.68%   |
| Ecuador               | 1         | 0.68%   |
| Czechia               | 1         | 0.68%   |
| Cuba                  | 1         | 0.68%   |
| Colombia              | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Beijing          | 5         | 3.4%    |
| Guangzhou        | 4         | 2.72%   |
| Wuhan            | 3         | 2.04%   |
| Curitiba         | 3         | 2.04%   |
| Uberlândia      | 2         | 1.36%   |
| Taiyuan          | 2         | 1.36%   |
| Surabaya         | 2         | 1.36%   |
| Sao Paulo        | 2         | 1.36%   |
| Petrópolis      | 2         | 1.36%   |
| Londrina         | 2         | 1.36%   |
| Innsbruck        | 2         | 1.36%   |
| David            | 2         | 1.36%   |
| Atlanta          | 2         | 1.36%   |
| Yozgat           | 1         | 0.68%   |
| Yogyakarta       | 1         | 0.68%   |
| Yekaterinburg    | 1         | 0.68%   |
| Xuhui            | 1         | 0.68%   |
| Xiamen           | 1         | 0.68%   |
| Wanchai          | 1         | 0.68%   |
| Voronezh         | 1         | 0.68%   |
| Villa Ballester  | 1         | 0.68%   |
| Vigo             | 1         | 0.68%   |
| Ufa              | 1         | 0.68%   |
| Tomsk            | 1         | 0.68%   |
| Tokyo            | 1         | 0.68%   |
| Tianjin          | 1         | 0.68%   |
| TehrДЃn        | 1         | 0.68%   |
| Tai'an           | 1         | 0.68%   |
| SГЈo TomГ©   | 1         | 0.68%   |
| Suzano           | 1         | 0.68%   |
| Sofia            | 1         | 0.68%   |
| Singapore        | 1         | 0.68%   |
| Shenzhen         | 1         | 0.68%   |
| Shanghai         | 1         | 0.68%   |
| Sao Carlos       | 1         | 0.68%   |
| Sao Bento do Sul | 1         | 0.68%   |
| Santiago         | 1         | 0.68%   |
| Samara           | 1         | 0.68%   |
| Saitama          | 1         | 0.68%   |
| Rzeszów         | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 24        | 27     | 13.04%  |
| Seagate                        | 23        | 26     | 12.5%   |
| Samsung Electronics            | 19        | 22     | 10.33%  |
| Unknown                        | 14        | 15     | 7.61%   |
| Toshiba                        | 14        | 15     | 7.61%   |
| SK hynix                       | 10        | 11     | 5.43%   |
| SanDisk                        | 10        | 10     | 5.43%   |
| Kingston                       | 9         | 10     | 4.89%   |
| Micron Technology              | 6         | 8      | 3.26%   |
| HGST                           | 6         | 6      | 3.26%   |
| Intel                          | 5         | 6      | 2.72%   |
| Hitachi                        | 5         | 5      | 2.72%   |
| Crucial                        | 4         | 4      | 2.17%   |
| LITEON                         | 3         | 3      | 1.63%   |
| China                          | 3         | 3      | 1.63%   |
| SPCC                           | 2         | 3      | 1.09%   |
| Silicon Motion                 | 2         | 2      | 1.09%   |
| KIOXIA                         | 2         | 2      | 1.09%   |
| A-DATA Technology              | 2         | 2      | 1.09%   |
| V-GeN                          | 1         | 1      | 0.54%   |
| Transcend                      | 1         | 1      | 0.54%   |
| Solid State Storage Technology | 1         | 1      | 0.54%   |
| Phison                         | 1         | 1      | 0.54%   |
| Patriot                        | 1         | 1      | 0.54%   |
| OEM                            | 1         | 1      | 0.54%   |
| OCZ                            | 1         | 1      | 0.54%   |
| Netac                          | 1         | 1      | 0.54%   |
| Microtech                      | 1         | 1      | 0.54%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.54%   |
| MaiChai                        | 1         | 1      | 0.54%   |
| Kingston Technology Company    | 1         | 1      | 0.54%   |
| KingSpec                       | 1         | 1      | 0.54%   |
| JMicron Technology             | 1         | 1      | 0.54%   |
| Intenso                        | 1         | 1      | 0.54%   |
| Fujitsu                        | 1         | 2      | 0.54%   |
| FORESEE                        | 1         | 1      | 0.54%   |
| Fanxiang                       | 1         | 1      | 0.54%   |
| Apple                          | 1         | 2      | 0.54%   |
| ADATA Technology               | 1         | 1      | 0.54%   |
| Unknown                        | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 6         | 3.17%   |
| Toshiba MQ01ABF050 500GB                           | 4         | 2.12%   |
| Kingston SA400S37240G 240GB SSD                    | 4         | 2.12%   |
| Toshiba MQ01ABD100 1TB                             | 3         | 1.59%   |
| Crucial CT240BX500SSD1 240GB                       | 3         | 1.59%   |
| WDC WD5000LPCX-24VHAT0 500GB                       | 2         | 1.06%   |
| Unknown MMC Card  32GB                             | 2         | 1.06%   |
| Unknown MMC Card                                   | 2         | 1.06%   |
| Seagate ST9320325AS 320GB                          | 2         | 1.06%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 2         | 1.06%   |
| Seagate ST2000LM007-1R8174 2TB                     | 2         | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 1.06%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 1.06%   |
| Samsung MZVLW256HEHP-000H1 256GB                   | 2         | 1.06%   |
| Hitachi HTS547575A9E384 752GB                      | 2         | 1.06%   |
| HGST HTS545050A7E680 500GB                         | 2         | 1.06%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                   | 1         | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 1         | 0.53%   |
| WDC WD7500BPVT-24HXZT3 752GB                       | 1         | 0.53%   |
| WDC WD5000LPZX-75Z10T0 500GB                       | 1         | 0.53%   |
| WDC WD5000LPVX-80V0TT0 500GB                       | 1         | 0.53%   |
| WDC WD5000LPVX-08V0TT6 500GB                       | 1         | 0.53%   |
| WDC WD5000LPCX-24C6HT0 500GB                       | 1         | 0.53%   |
| WDC WD3200BEVT-60A23T0 320GB                       | 1         | 0.53%   |
| WDC WD3200BEVT-22ZCT0 320GB                        | 1         | 0.53%   |
| WDC WD3200BEVT-08A23T1 320GB                       | 1         | 0.53%   |
| WDC WD10SPZX-35Z10T0 1TB                           | 1         | 0.53%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 0.53%   |
| WDC WD10SPZX-22Z10T1 1TB                           | 1         | 0.53%   |
| WDC WD10SPZX-08Z10 1TB                             | 1         | 0.53%   |
| WDC WD10JPVX-60JC3T1 1TB                           | 1         | 0.53%   |
| WDC WD10JPVX-60JC3T0 1TB                           | 1         | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.53%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 0.53%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 0.53%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB               | 1         | 0.53%   |
| WDC PC SN720 SDAPNTW-512G-1127 512GB               | 1         | 0.53%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 26     | 34.33%  |
| WDC                 | 18        | 19     | 26.87%  |
| Toshiba             | 11        | 12     | 16.42%  |
| HGST                | 6         | 6      | 8.96%   |
| Hitachi             | 5         | 5      | 7.46%   |
| Samsung Electronics | 1         | 1      | 1.49%   |
| OEM                 | 1         | 1      | 1.49%   |
| JMicron Technology  | 1         | 1      | 1.49%   |
| Fujitsu             | 1         | 2      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 8      | 15.69%  |
| Samsung Electronics | 7         | 8      | 13.73%  |
| Kingston            | 7         | 8      | 13.73%  |
| WDC                 | 3         | 3      | 5.88%   |
| SK hynix            | 3         | 3      | 5.88%   |
| Crucial             | 3         | 3      | 5.88%   |
| China               | 3         | 3      | 5.88%   |
| SPCC                | 2         | 3      | 3.92%   |
| Micron Technology   | 2         | 3      | 3.92%   |
| LITEON              | 2         | 2      | 3.92%   |
| V-GeN               | 1         | 1      | 1.96%   |
| Unknown             | 1         | 1      | 1.96%   |
| Transcend           | 1         | 1      | 1.96%   |
| Toshiba             | 1         | 1      | 1.96%   |
| OCZ                 | 1         | 1      | 1.96%   |
| Netac               | 1         | 1      | 1.96%   |
| Microtech           | 1         | 1      | 1.96%   |
| MaiChai             | 1         | 1      | 1.96%   |
| KingSpec            | 1         | 1      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |
| Intel               | 1         | 2      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 66        | 73     | 36.67%  |
| NVMe    | 52        | 58     | 28.89%  |
| SSD     | 48        | 56     | 26.67%  |
| MMC     | 13        | 15     | 7.22%   |
| Unknown | 1         | 1      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 124    | 57.83%  |
| NVMe | 52        | 58     | 31.33%  |
| MMC  | 13        | 15     | 7.83%   |
| SAS  | 5         | 6      | 3.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 84     | 63.21%  |
| 0.51-1.0   | 36        | 40     | 33.96%  |
| 1.01-2.0   | 2         | 4      | 1.89%   |
| 4.01-10.0  | 1         | 1      | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 51        | 34%     |
| 101-250        | 39        | 26%     |
| 501-1000       | 31        | 20.67%  |
| 1001-2000      | 11        | 7.33%   |
| 51-100         | 5         | 3.33%   |
| More than 3000 | 4         | 2.67%   |
| 21-50          | 4         | 2.67%   |
| Unknown        | 3         | 2%      |
| 2001-3000      | 1         | 0.67%   |
| 1-20           | 1         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 34        | 22.82%  |
| 1-20      | 34        | 22.82%  |
| 101-250   | 24        | 16.11%  |
| 51-100    | 23        | 15.44%  |
| 251-500   | 19        | 12.75%  |
| 501-1000  | 6         | 4.03%   |
| 1001-2000 | 4         | 2.68%   |
| Unknown   | 3         | 2.01%   |
| 2001-3000 | 2         | 1.34%   |

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
| Detected | 75        | 102    | 47.77%  |
| Works    | 69        | 87     | 43.95%  |
| Malfunc  | 12        | 13     | 7.64%   |
| Failed   | 1         | 1      | 0.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 101       | 61.96%  |
| Samsung Electronics            | 11        | 6.75%   |
| AMD                            | 11        | 6.75%   |
| SK hynix                       | 7         | 4.29%   |
| SanDisk                        | 6         | 3.68%   |
| Micron Technology              | 4         | 2.45%   |
| MAXIO Technology (Hangzhou)    | 3         | 1.84%   |
| KIOXIA                         | 3         | 1.84%   |
| Kingston Technology Company    | 3         | 1.84%   |
| Silicon Motion                 | 2         | 1.23%   |
| Zhaoxin                        | 1         | 0.61%   |
| Toshiba America Info Systems   | 1         | 0.61%   |
| Solid State Storage Technology | 1         | 0.61%   |
| Shenzhen Longsys Electronics   | 1         | 0.61%   |
| Realtek Semiconductor          | 1         | 0.61%   |
| Phison Electronics             | 1         | 0.61%   |
| Micron/Crucial Technology      | 1         | 0.61%   |
| Lite-On Technology             | 1         | 0.61%   |
| JMicron Technology             | 1         | 0.61%   |
| Apple                          | 1         | 0.61%   |
| ADATA Technology               | 1         | 0.61%   |
| Unknown                        | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 16        | 9.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 12        | 7.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 11        | 6.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 11        | 6.47%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 10        | 5.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 7         | 4.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 5         | 2.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 5         | 2.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                                                  | 5         | 2.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 5         | 2.94%   |
| Intel Comet Lake SATA AHCI Controller                                                                              | 4         | 2.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 4         | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 4         | 2.35%   |
| SK hynix BC511 NVMe SSD                                                                                            | 3         | 1.76%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 3         | 1.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 3         | 1.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 3         | 1.76%   |
| SK hynix BC501 NVMe Solid State Drive                                                                              | 2         | 1.18%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 2         | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 2         | 1.18%   |
| Micron 2200S NVMe SSD [Cassandra]                                                                                  | 2         | 1.18%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 2         | 1.18%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 2         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 2         | 1.18%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 2         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 2         | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                                           | 2         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller                                   | 2         | 1.18%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G/KH-40000/KX-7000 StorX AHCI Controller                                      | 1         | 0.59%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                                               | 1         | 0.59%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                                                     | 1         | 0.59%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                                                 | 1         | 0.59%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 1         | 0.59%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 0.59%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                                              | 1         | 0.59%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                                                              | 1         | 0.59%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                                                        | 1         | 0.59%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 1         | 0.59%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                                                  | 1         | 0.59%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                                                                | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 105       | 62.87%  |
| NVMe | 51        | 30.54%  |
| RAID | 7         | 4.19%   |
| IDE  | 4         | 2.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 120       | 82.19%  |
| AMD          | 25        | 17.12%  |
| CentaurHauls | 1         | 0.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 3.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 3.42%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 2.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 2.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 2.05%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 2.05%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.05%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.37%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.37%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.37%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.37%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.37%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.37%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.37%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.37%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.37%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.37%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.37%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.37%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.37%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.37%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.37%   |
| AMD Ryzen 5 4600U with Radeon Graphics        | 2         | 1.37%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.37%   |
| AMD 3020e with Radeon Graphics                | 2         | 1.37%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.68%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.68%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.68%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.68%   |
| Intel Core M-5Y71 CPU @ 1.20GHz               | 1         | 0.68%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.68%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.68%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 41        | 28.08%  |
| Intel Core i7           | 31        | 21.23%  |
| Other                   | 13        | 8.9%    |
| Intel Core i3           | 10        | 6.85%   |
| Intel Celeron           | 10        | 6.85%   |
| AMD Ryzen 7             | 7         | 4.79%   |
| AMD Ryzen 5             | 6         | 4.11%   |
| Intel Core 2 Duo        | 4         | 2.74%   |
| Intel Atom              | 4         | 2.74%   |
| Intel Pentium Dual-Core | 3         | 2.05%   |
| AMD Ryzen 3             | 3         | 2.05%   |
| Intel Pentium           | 2         | 1.37%   |
| AMD A10                 | 2         | 1.37%   |
| Intel Pentium Silver    | 1         | 0.68%   |
| Intel Core m3           | 1         | 0.68%   |
| Intel Core M            | 1         | 0.68%   |
| Intel Core i9           | 1         | 0.68%   |
| Intel Celeron Dual-Core | 1         | 0.68%   |
| AMD Ryzen 7 PRO         | 1         | 0.68%   |
| AMD Ryzen 5 PRO         | 1         | 0.68%   |
| AMD E1                  | 1         | 0.68%   |
| AMD E                   | 1         | 0.68%   |
| AMD A8                  | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 74        | 50.68%  |
| 4      | 53        | 36.3%   |
| 6      | 7         | 4.79%   |
| 8      | 6         | 4.11%   |
| 12     | 2         | 1.37%   |
| 10     | 2         | 1.37%   |
| 14     | 1         | 0.68%   |
| 1      | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 146       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 112       | 76.71%  |
| 1      | 34        | 23.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 135       | 92.47%  |
| Unknown        | 11        | 7.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 18.24%  |
| 0x806ec    | 12        | 8.11%   |
| 0x306a9    | 10        | 6.76%   |
| 0x40651    | 9         | 6.08%   |
| 0x806e9    | 8         | 5.41%   |
| 0x306d4    | 8         | 5.41%   |
| 0x406e3    | 6         | 4.05%   |
| 0x206a7    | 6         | 4.05%   |
| 0x906ea    | 5         | 3.38%   |
| 0x806ea    | 4         | 2.7%    |
| 0x1067a    | 4         | 2.7%    |
| 0x906a3    | 3         | 2.03%   |
| 0x08600106 | 3         | 2.03%   |
| 0x08108109 | 3         | 2.03%   |
| 0x906e9    | 2         | 1.35%   |
| 0x806c1    | 2         | 1.35%   |
| 0x706a8    | 2         | 1.35%   |
| 0x706a1    | 2         | 1.35%   |
| 0x406c4    | 2         | 1.35%   |
| 0x30678    | 2         | 1.35%   |
| 0x20655    | 2         | 1.35%   |
| 0x08600104 | 2         | 1.35%   |
| 0x08200103 | 2         | 1.35%   |
| 0x08108102 | 2         | 1.35%   |
| 0xb06a3    | 1         | 0.68%   |
| 0xb06a2    | 1         | 0.68%   |
| 0xa0652    | 1         | 0.68%   |
| 0x806d1    | 1         | 0.68%   |
| 0x806c2    | 1         | 0.68%   |
| 0x6fd      | 1         | 0.68%   |
| 0x406c3    | 1         | 0.68%   |
| 0x10676    | 1         | 0.68%   |
| 0x0a704103 | 1         | 0.68%   |
| 0x0a50000c | 1         | 0.68%   |
| 0x0a50000b | 1         | 0.68%   |
| 0x0a404101 | 1         | 0.68%   |
| 0x08608102 | 1         | 0.68%   |
| 0x08600103 | 1         | 0.68%   |
| 0x08600102 | 1         | 0.68%   |
| 0x0810100b | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 36        | 24.66%  |
| IvyBridge        | 13        | 8.9%    |
| Haswell          | 11        | 7.53%   |
| Broadwell        | 11        | 7.53%   |
| Zen 2            | 7         | 4.79%   |
| Silvermont       | 7         | 4.79%   |
| SandyBridge      | 7         | 4.79%   |
| Penryn           | 7         | 4.79%   |
| Skylake          | 6         | 4.11%   |
| Zen+             | 5         | 3.42%   |
| Goldmont plus    | 5         | 3.42%   |
| Unknown          | 5         | 3.42%   |
| TigerLake        | 4         | 2.74%   |
| Alderlake Hybrid | 4         | 2.74%   |
| Zen              | 3         | 2.05%   |
| Westmere         | 3         | 2.05%   |
| Zen 3            | 2         | 1.37%   |
| Goldmont         | 2         | 1.37%   |
| Excavator        | 2         | 1.37%   |
| Bobcat           | 2         | 1.37%   |
| K10 Llano        | 1         | 0.68%   |
| Icelake          | 1         | 0.68%   |
| Core             | 1         | 0.68%   |
| CometLake        | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 118       | 59.6%   |
| Nvidia  | 48        | 24.24%  |
| AMD     | 31        | 15.66%  |
| Zhaoxin | 1         | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 6%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.5%    |
| Intel HD Graphics 5500                                                                   | 10        | 5%      |
| Intel HD Graphics 620                                                                    | 8         | 4%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.5%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 3.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.5%    |
| Intel UHD Graphics 620                                                                   | 6         | 3%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 3%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 2%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.5%    |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 1.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.5%    |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1%      |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1%      |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1%      |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1%      |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1%      |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1%      |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 1%      |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                                 | 2         | 1%      |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 1%      |
| Intel HD Graphics 630                                                                    | 2         | 1%      |
| Intel HD Graphics 500                                                                    | 2         | 1%      |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 1%      |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1%      |
| Zhaoxin KX-6000 C-960 GPU                                                                | 1         | 0.5%    |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.5%    |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 46.58%  |
| Intel + Nvidia | 43        | 29.45%  |
| 1 x AMD        | 20        | 13.7%   |
| Intel + AMD    | 7         | 4.79%   |
| 1 x Nvidia     | 3         | 2.05%   |
| 2 x AMD        | 2         | 1.37%   |
| AMD + Nvidia   | 2         | 1.37%   |
| 1 x Zhaoxin    | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 117       | 79.59%  |
| Proprietary | 24        | 16.33%  |
| Unknown     | 6         | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 59.06%  |
| 1.01-2.0   | 30        | 20.13%  |
| 3.01-4.0   | 14        | 9.4%    |
| 0.01-0.5   | 13        | 8.72%   |
| 0.51-1.0   | 3         | 2.01%   |
| 5.01-6.0   | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 30        | 19.61%  |
| AU Optronics            | 29        | 18.95%  |
| Chimei Innolux          | 21        | 13.73%  |
| LG Display              | 19        | 12.42%  |
| Samsung Electronics     | 17        | 11.11%  |
| CSO                     | 6         | 3.92%   |
| Hewlett-Packard         | 3         | 1.96%   |
| Goldstar                | 3         | 1.96%   |
| AOC                     | 3         | 1.96%   |
| Lenovo                  | 2         | 1.31%   |
| InfoVision              | 2         | 1.31%   |
| HKC                     | 2         | 1.31%   |
| Chi Mei Optoelectronics | 2         | 1.31%   |
| ViewSonic               | 1         | 0.65%   |
| TMX                     | 1         | 0.65%   |
| Sharp                   | 1         | 0.65%   |
| SAC                     | 1         | 0.65%   |
| PANDA                   | 1         | 0.65%   |
| LG Philips              | 1         | 0.65%   |
| JDI                     | 1         | 0.65%   |
| Iiyama                  | 1         | 0.65%   |
| HB@                     | 1         | 0.65%   |
| HannStar                | 1         | 0.65%   |
| Dell                    | 1         | 0.65%   |
| CS_                     | 1         | 0.65%   |
| BenQ                    | 1         | 0.65%   |
| Apple                   | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 1.95%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.95%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 2         | 1.3%    |
| HKC LCD Monitor HKC3CFB 1920x1080 344x194mm 15.5-inch                 | 2         | 1.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.3%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.3%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 1.3%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 2         | 1.3%    |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch             | 1         | 0.65%   |
| TMX TL140VDXP04-0 TMX1398 1920x1080 309x174mm 14.0-inch               | 1         | 0.65%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM0167 1280x1024 338x270mm 17.0-inch  | 1         | 0.65%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 700x400mm 31.7-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC864D 1920x1080 293x165mm 13.2-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC534B 1600x900 382x215mm 17.3-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                     | 1         | 0.65%   |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch                 | 1         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.65%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.65%   |
| LG Display LP156WH1-TLA1 LGD6301 1366x768 344x194mm 15.5-inch         | 1         | 0.65%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 1         | 0.65%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.65%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.65%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.65%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x174mm 14.0-inch          | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 61        | 42.07%  |
| 1366x768 (WXGA)  | 53        | 36.55%  |
| 1600x900 (HD+)   | 6         | 4.14%   |
| 3840x2160 (4K)   | 4         | 2.76%   |
| 2560x1600        | 4         | 2.76%   |
| 2880x1800        | 3         | 2.07%   |
| 3000x2000        | 2         | 1.38%   |
| 2160x1440        | 2         | 1.38%   |
| 3440x1440        | 1         | 0.69%   |
| 3200x2000        | 1         | 0.69%   |
| 3200x1800 (QHD+) | 1         | 0.69%   |
| 2880x1920        | 1         | 0.69%   |
| 2560x1440 (QHD)  | 1         | 0.69%   |
| 2288x1287        | 1         | 0.69%   |
| 1920x540         | 1         | 0.69%   |
| 1680x945         | 1         | 0.69%   |
| 1280x800 (WXGA)  | 1         | 0.69%   |
| 1280x1024 (SXGA) | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 63        | 41.18%  |
| 13      | 31        | 20.26%  |
| 14      | 25        | 16.34%  |
| 17      | 5         | 3.27%   |
| 23      | 4         | 2.61%   |
| 27      | 3         | 1.96%   |
| 21      | 3         | 1.96%   |
| 18      | 3         | 1.96%   |
| 16      | 3         | 1.96%   |
| 11      | 3         | 1.96%   |
| 32      | 2         | 1.31%   |
| 24      | 2         | 1.31%   |
| 12      | 2         | 1.31%   |
| 40      | 1         | 0.65%   |
| 31      | 1         | 0.65%   |
| 25      | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 107       | 71.33%  |
| 201-300     | 18        | 12%     |
| 501-600     | 9         | 6%      |
| 351-400     | 6         | 4%      |
| 401-500     | 5         | 3.33%   |
| 701-800     | 2         | 1.33%   |
| 801-900     | 1         | 0.67%   |
| 601-700     | 1         | 0.67%   |
| Unknown     | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 122       | 87.14%  |
| 16/10 | 12        | 8.57%   |
| 3/2   | 5         | 3.57%   |
| 5/4   | 1         | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 40.91%  |
| 81-90          | 47        | 30.52%  |
| 71-80          | 9         | 5.84%   |
| 201-250        | 7         | 4.55%   |
| 141-150        | 4         | 2.6%    |
| 51-60          | 3         | 1.95%   |
| 351-500        | 3         | 1.95%   |
| 301-350        | 3         | 1.95%   |
| 251-300        | 3         | 1.95%   |
| 121-130        | 3         | 1.95%   |
| 111-120        | 3         | 1.95%   |
| 61-70          | 2         | 1.3%    |
| 151-200        | 1         | 0.65%   |
| 131-140        | 1         | 0.65%   |
| 501-1000       | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 58        | 38.67%  |
| 121-160       | 55        | 36.67%  |
| 51-100        | 16        | 10.67%  |
| 161-240       | 14        | 9.33%   |
| More than 240 | 6         | 4%      |
| Unknown       | 1         | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 122       | 82.99%  |
| 2     | 20        | 13.61%  |
| 0     | 4         | 2.72%   |
| 3     | 1         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 95        | 43.58%  |
| Intel                           | 63        | 28.9%   |
| Qualcomm Atheros                | 35        | 16.06%  |
| Broadcom                        | 7         | 3.21%   |
| MediaTek                        | 3         | 1.38%   |
| Marvell Technology Group        | 3         | 1.38%   |
| Broadcom Limited                | 3         | 1.38%   |
| Xiaomi                          | 2         | 0.92%   |
| Ralink Technology               | 1         | 0.46%   |
| Ralink                          | 1         | 0.46%   |
| Qualcomm Atheros Communications | 1         | 0.46%   |
| OPPO Electronics                | 1         | 0.46%   |
| Huawei Technologies             | 1         | 0.46%   |
| Hewlett-Packard                 | 1         | 0.46%   |
| ASIX Electronics                | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 56        | 22.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 20        | 7.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 4.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 9         | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 2.76%   |
| Intel Wireless 3165                                                    | 7         | 2.76%   |
| Intel Wi-Fi 6 AX200                                                    | 6         | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 1.57%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 3         | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.18%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.18%   |
| Intel Wireless 7265                                                    | 3         | 1.18%   |
| Intel Wireless 7260                                                    | 3         | 1.18%   |
| Intel Wireless 3160                                                    | 3         | 1.18%   |
| Intel WiFi Link 5100                                                   | 3         | 1.18%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 1.18%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.79%   |
| Realtek RTL8191SEvA Wireless LAN Controller                            | 2         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.79%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 2         | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 42.18%  |
| Realtek Semiconductor           | 37        | 25.17%  |
| Qualcomm Atheros                | 34        | 23.13%  |
| Broadcom                        | 5         | 3.4%    |
| MediaTek                        | 3         | 2.04%   |
| Broadcom Limited                | 3         | 2.04%   |
| Ralink Technology               | 1         | 0.68%   |
| Ralink                          | 1         | 0.68%   |
| Qualcomm Atheros Communications | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 8.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 6.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 4.73%   |
| Intel Wireless 3165                                            | 7         | 4.73%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 4.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.7%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 2.03%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.03%   |
| Intel Wireless 7265                                            | 3         | 2.03%   |
| Intel Wireless 7260                                            | 3         | 2.03%   |
| Intel Wireless 3160                                            | 3         | 2.03%   |
| Intel WiFi Link 5100                                           | 3         | 2.03%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 2.03%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.35%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 2         | 1.35%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.35%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 1.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.68%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.68%   |
| Realtek 802.11ac NIC                                           | 1         | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.68%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 80        | 75.47%  |
| Intel                    | 11        | 10.38%  |
| Qualcomm Atheros         | 4         | 3.77%   |
| Marvell Technology Group | 3         | 2.83%   |
| Xiaomi                   | 2         | 1.89%   |
| Broadcom                 | 2         | 1.89%   |
| OPPO Electronics         | 1         | 0.94%   |
| Huawei Technologies      | 1         | 0.94%   |
| Hewlett-Packard          | 1         | 0.94%   |
| ASIX Electronics         | 1         | 0.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 56        | 52.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 20        | 18.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 4.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 2.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 1.89%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 1.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.94%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.94%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 1         | 0.94%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 1         | 0.94%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.94%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.94%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.94%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.94%   |
| Huawei VTR-L09                                                         | 1         | 0.94%   |
| HP lt4120 Snapdragon X5 LTE                                            | 1         | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 143       | 58.13%  |
| Ethernet | 103       | 41.87%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 82.76%  |
| Ethernet | 25        | 17.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 96        | 65.75%  |
| 1     | 45        | 30.82%  |
| 0     | 4         | 2.74%   |
| 3     | 1         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 134       | 91.16%  |
| Yes  | 13        | 8.84%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 42.98%  |
| Qualcomm Atheros Communications | 20        | 16.53%  |
| Realtek Semiconductor           | 17        | 14.05%  |
| Foxconn / Hon Hai               | 8         | 6.61%   |
| Broadcom                        | 7         | 5.79%   |
| Realtek                         | 5         | 4.13%   |
| IMC Networks                    | 4         | 3.31%   |
| Lite-On Technology              | 3         | 2.48%   |
| Cambridge Silicon Radio         | 2         | 1.65%   |
| Toshiba                         | 1         | 0.83%   |
| Ralink Technology               | 1         | 0.83%   |
| Dell                            | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 14.88%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 15        | 12.4%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 8.26%   |
| Intel AX201 Bluetooth                                                               | 9         | 7.44%   |
| Realtek Bluetooth Radio                                                             | 8         | 6.61%   |
| Intel AX200 Bluetooth                                                               | 6         | 4.96%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 4.13%   |
| Realtek Bluetooth Radio                                                             | 5         | 4.13%   |
| Intel Bluetooth Device                                                              | 4         | 3.31%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.65%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.65%   |
| Intel AX211 Bluetooth                                                               | 2         | 1.65%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.65%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.65%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.83%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.83%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.83%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.83%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.83%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.83%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.83%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.83%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.83%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.83%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.83%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.83%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 0.83%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.83%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.83%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.83%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 116       | 72.96%  |
| AMD                 | 25        | 15.72%  |
| Nvidia              | 15        | 9.43%   |
| Zhaoxin             | 1         | 0.63%   |
| JMTek               | 1         | 0.63%   |
| Creative Technology | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 10.68%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 9.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 6.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 5.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 5.34%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 5.34%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 5.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 4.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 3.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 3.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 3.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 2.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.94%   |
| Nvidia Audio device                                                                               | 4         | 1.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.46%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.97%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.97%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.97%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.97%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.97%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.49%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller         | 1         | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.49%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.49%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.49%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.49%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.49%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.49%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.49%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                      | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 27.72%  |
| SK hynix            | 27        | 26.73%  |
| Unknown             | 11        | 10.89%  |
| Micron Technology   | 10        | 9.9%    |
| Smart               | 4         | 3.96%   |
| Kingston            | 4         | 3.96%   |
| Unknown (ABCD)      | 3         | 2.97%   |
| Ramaxel Technology  | 3         | 2.97%   |
| Nanya Technology    | 3         | 2.97%   |
| A-DATA Technology   | 2         | 1.98%   |
| Unknown (07FB)      | 1         | 0.99%   |
| Smart Brazil        | 1         | 0.99%   |
| MTASE               | 1         | 0.99%   |
| Kingmax             | 1         | 0.99%   |
| Crucial             | 1         | 0.99%   |
| ChangXin Memory     | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 2.83%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 3         | 2.83%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 1.89%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.89%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 2         | 1.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.89%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.89%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.89%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.89%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.94%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.94%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 0.94%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 0.94%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.94%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.94%   |
| Unknown RAM Module 2048MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.94%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.94%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.94%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s                 | 1         | 0.94%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.94%   |
| Unknown (07FB) RAM GST32G08SCL196P-26 32GB SODIMM DDR4 2667MT/s  | 1         | 0.94%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 1         | 0.94%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.94%   |
| SK hynix RAM MPPS4GBPC1600 1.35 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.94%   |
| SK hynix RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.94%   |
| SK hynix RAM Module 16384MB SODIMM DDR5 5600MT/s                 | 1         | 0.94%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.94%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.94%   |
| SK hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 0.94%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 1         | 0.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.94%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 46.67%  |
| DDR3   | 22        | 24.44%  |
| LPDDR4 | 9         | 10%     |
| LPDDR3 | 8         | 8.89%   |
| DDR5   | 3         | 3.33%   |
| DDR2   | 3         | 3.33%   |
| LPDDR5 | 2         | 2.22%   |
| SDRAM  | 1         | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 81.11%  |
| Row Of Chips | 16        | 17.78%  |
| Unknown      | 1         | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 39        | 41.05%  |
| 4096  | 31        | 32.63%  |
| 2048  | 15        | 15.79%  |
| 16384 | 7         | 7.37%   |
| 1024  | 2         | 2.11%   |
| 32768 | 1         | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 20        | 21.51%  |
| 1600    | 18        | 19.35%  |
| 3200    | 12        | 12.9%   |
| 2400    | 9         | 9.68%   |
| 2133    | 7         | 7.53%   |
| 1333    | 4         | 4.3%    |
| 1334    | 3         | 3.23%   |
| 4800    | 2         | 2.15%   |
| 4267    | 2         | 2.15%   |
| 3266    | 2         | 2.15%   |
| 800     | 2         | 2.15%   |
| Unknown | 2         | 2.15%   |
| 7467    | 1         | 1.08%   |
| 6400    | 1         | 1.08%   |
| 5600    | 1         | 1.08%   |
| 4266    | 1         | 1.08%   |
| 3733    | 1         | 1.08%   |
| 2933    | 1         | 1.08%   |
| 2666    | 1         | 1.08%   |
| 2048    | 1         | 1.08%   |
| 1867    | 1         | 1.08%   |
| 1066    | 1         | 1.08%   |

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
| Chicony Electronics                    | 32        | 24.81%  |
| Microdia                               | 12        | 9.3%    |
| IMC Networks                           | 12        | 9.3%    |
| Realtek Semiconductor                  | 11        | 8.53%   |
| Quanta                                 | 9         | 6.98%   |
| Sunplus Innovation Technology          | 8         | 6.2%    |
| Syntek                                 | 6         | 4.65%   |
| Suyin                                  | 6         | 4.65%   |
| Silicon Motion                         | 6         | 4.65%   |
| Lite-On Technology                     | 5         | 3.88%   |
| Bison Electronics                      | 5         | 3.88%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.1%    |
| Ricoh                                  | 2         | 1.55%   |
| Primax Electronics                     | 2         | 1.55%   |
| icSpring                               | 2         | 1.55%   |
| Alcor Micro                            | 2         | 1.55%   |
| Luxvisions Innotech Limited            | 1         | 0.78%   |
| LG Electronics                         | 1         | 0.78%   |
| Lenovo                                 | 1         | 0.78%   |
| kingcome                               | 1         | 0.78%   |
| Goodong Industry                       | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 8         | 6.15%   |
| IMC Networks Integrated Camera                               | 5         | 3.85%   |
| IMC Networks HD Camera                                       | 5         | 3.85%   |
| Quanta HD User Facing                                        | 4         | 3.08%   |
| Chicony EasyCamera                                           | 4         | 3.08%   |
| Syntek EasyCamera                                            | 3         | 2.31%   |
| Silicon Motion Web Camera                                    | 3         | 2.31%   |
| Quanta HP TrueVision HD Camera                               | 3         | 2.31%   |
| Chicony TOSHIBA Web Camera - HD                              | 3         | 2.31%   |
| Syntek Integrated Camera                                     | 2         | 1.54%   |
| Sunplus Integrated_Webcam_HD                                 | 2         | 1.54%   |
| Sunplus HD WebCam                                            | 2         | 1.54%   |
| Realtek USB Camera                                           | 2         | 1.54%   |
| Realtek Integrated_Webcam_HD                                 | 2         | 1.54%   |
| Realtek HP "Truevision HD" laptop camera                     | 2         | 1.54%   |
| Primax HP HD Webcam [Fixed]                                  | 2         | 1.54%   |
| Microdia USB 2.0 Camera                                      | 2         | 1.54%   |
| Microdia Integrated_Webcam_HD                                | 2         | 1.54%   |
| Microdia HP Integrated Webcam                                | 2         | 1.54%   |
| Lite-On Integrated Camera                                    | 2         | 1.54%   |
| icSpring camera                                              | 2         | 1.54%   |
| Chicony HP Webcam                                            | 2         | 1.54%   |
| Chicony HP HD Webcam                                         | 2         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 2         | 1.54%   |
| Bison Integrated Camera                                      | 2         | 1.54%   |
| Syntek Lenovo EasyCamera                                     | 1         | 0.77%   |
| Suyin Integrated_Webcam_HD                                   | 1         | 0.77%   |
| Suyin HP Webcam 101                                          | 1         | 0.77%   |
| Suyin HP Truevision HD                                       | 1         | 0.77%   |
| Suyin HD WebCam                                              | 1         | 0.77%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                     | 1         | 0.77%   |
| Suyin 1.3M HD WebCam                                         | 1         | 0.77%   |
| Sunplus XiaoMi USB 2.0 Webcam                                | 1         | 0.77%   |
| Sunplus Integrated Camera                                    | 1         | 0.77%   |
| Sunplus HP Wide Vision HD                                    | 1         | 0.77%   |
| Sunplus Asus Webcam                                          | 1         | 0.77%   |
| Silicon Motion WebCam SC-13HDL11939N                         | 1         | 0.77%   |
| Silicon Motion WebCam SC-0311139N                            | 1         | 0.77%   |
| Silicon Motion ATIV VGA Camera                               | 1         | 0.77%   |
| Ricoh Sony Vaio Integrated Webcam                            | 1         | 0.77%   |

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
| 0     | 99        | 66.89%  |
| 1     | 41        | 27.7%   |
| 2     | 8         | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 27        | 46.55%  |
| Graphics card         | 15        | 25.86%  |
| Multimedia controller | 7         | 12.07%  |
| Chipcard              | 5         | 8.62%   |
| Sound                 | 2         | 3.45%   |
| Storage               | 1         | 1.72%   |
| Camera                | 1         | 1.72%   |


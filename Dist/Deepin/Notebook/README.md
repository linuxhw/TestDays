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

Total: 188

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Deepin         | 29        | 20.42%  |
| Deepin 15.11   | 23        | 16.2%   |
| Deepin 20      | 20        | 14.08%  |
| UOS 20         | 13        | 9.15%   |
| Deepin 23      | 8         | 5.63%   |
| Deepin 15.9.2  | 8         | 5.63%   |
| Deepin 20.8    | 6         | 4.23%   |
| Deepin 20.9    | 5         | 3.52%   |
| Deepin 20.3    | 5         | 3.52%   |
| Deepin 20.5    | 4         | 2.82%   |
| Deepin 20.1    | 4         | 2.82%   |
| Deepin 20 beta | 3         | 2.11%   |
| Deepin 20.2.4  | 2         | 1.41%   |
| Deepin 15.9.3  | 2         | 1.41%   |
| Deepin 2014.3  | 1         | 0.7%    |
| Deepin 20.7.1  | 1         | 0.7%    |
| Deepin 20.7    | 1         | 0.7%    |
| Deepin 20.4    | 1         | 0.7%    |
| Deepin 20.2.3  | 1         | 0.7%    |
| Deepin 20.2.1  | 1         | 0.7%    |
| Deepin 15.9    | 1         | 0.7%    |
| Deepin 15.8    | 1         | 0.7%    |
| Deepin 15.10.1 | 1         | 0.7%    |
| Deepin 15.10   | 1         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Deepin | 137       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.15.0-30deepin-generic             | 32        | 22.54%  |
| 5.4.50-amd64-desktop                | 16        | 11.27%  |
| 4.15.0-29deepin-generic             | 12        | 8.45%   |
| 5.4.70-amd64-desktop                | 9         | 6.34%   |
| 5.10.60-amd64-desktop               | 9         | 6.34%   |
| 5.18.17-amd64-desktop-community-hwe | 5         | 3.52%   |
| 5.10.0-amd64-desktop                | 5         | 3.52%   |
| 5.7.7-amd64-desktop                 | 4         | 2.82%   |
| 5.18.17-amd64-desktop-hwe           | 4         | 2.82%   |
| 5.10.41-amd64-desktop               | 4         | 2.82%   |
| 5.10.29-amd64-desktop               | 4         | 2.82%   |
| 6.1.32-amd64-desktop-hwe            | 3         | 2.11%   |
| 5.3.0-3-amd64                       | 3         | 2.11%   |
| 5.15.77-amd64-desktop               | 3         | 2.11%   |
| 5.15.1-amd64-desktop                | 3         | 2.11%   |
| 6.1.11-amd64-desktop-hwe            | 2         | 1.41%   |
| 5.15.24-amd64-desktop               | 2         | 1.41%   |
| 5.10.50-amd64-desktop               | 2         | 1.41%   |
| 5.10.5-amd64-desktop+               | 2         | 1.41%   |
| 5.10.18-amd64-desktop               | 2         | 1.41%   |
| 5.10.101-amd64-desktop              | 2         | 1.41%   |
| 4.19.0-amd64-desktop                | 2         | 1.41%   |
| 6.5.0                               | 1         | 0.7%    |
| 5.8.14-amd64-desktop                | 1         | 0.7%    |
| 5.6.14-050614-generic               | 1         | 0.7%    |
| 5.6.12-xanmod1                      | 1         | 0.7%    |
| 5.5.4-xanmod3                       | 1         | 0.7%    |
| 5.3.8-xanmod6                       | 1         | 0.7%    |
| 5.15.45-amd64-desktop               | 1         | 0.7%    |
| 5.15.34-amd64-desktop               | 1         | 0.7%    |
| 5.10.83-amd64-desktop               | 1         | 0.7%    |
| 5.10.36-amd64-desktop               | 1         | 0.7%    |
| 5.1.0-050100rc2-generic             | 1         | 0.7%    |
| 4.15.0-135-generic                  | 1         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 45        | 31.69%  |
| 5.4.50   | 16        | 11.27%  |
| 5.4.70   | 9         | 6.34%   |
| 5.18.17  | 9         | 6.34%   |
| 5.10.60  | 9         | 6.34%   |
| 5.10.0   | 5         | 3.52%   |
| 5.7.7    | 4         | 2.82%   |
| 5.10.41  | 4         | 2.82%   |
| 5.10.29  | 4         | 2.82%   |
| 6.1.32   | 3         | 2.11%   |
| 5.3.0    | 3         | 2.11%   |
| 5.15.77  | 3         | 2.11%   |
| 5.15.1   | 3         | 2.11%   |
| 6.1.11   | 2         | 1.41%   |
| 5.15.24  | 2         | 1.41%   |
| 5.10.50  | 2         | 1.41%   |
| 5.10.5   | 2         | 1.41%   |
| 5.10.18  | 2         | 1.41%   |
| 5.10.101 | 2         | 1.41%   |
| 4.19.0   | 2         | 1.41%   |
| 6.5.0    | 1         | 0.7%    |
| 5.8.14   | 1         | 0.7%    |
| 5.6.14   | 1         | 0.7%    |
| 5.6.12   | 1         | 0.7%    |
| 5.5.4    | 1         | 0.7%    |
| 5.3.8    | 1         | 0.7%    |
| 5.15.45  | 1         | 0.7%    |
| 5.15.34  | 1         | 0.7%    |
| 5.10.83  | 1         | 0.7%    |
| 5.10.36  | 1         | 0.7%    |
| 5.1.0    | 1         | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15    | 45        | 31.91%  |
| 5.10    | 32        | 22.7%   |
| 5.4     | 25        | 17.73%  |
| 5.18    | 9         | 6.38%   |
| 5.15    | 9         | 6.38%   |
| 6.1     | 5         | 3.55%   |
| 5.7     | 4         | 2.84%   |
| 5.3     | 4         | 2.84%   |
| 5.6     | 2         | 1.42%   |
| 4.19    | 2         | 1.42%   |
| 6.5     | 1         | 0.71%   |
| 5.8     | 1         | 0.71%   |
| 5.5     | 1         | 0.71%   |
| 5.1     | 1         | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 137       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Deepin  | 113       | 82.48%  |
| Unknown | 20        | 14.6%   |
| DDE     | 3         | 2.19%   |
| KDE     | 1         | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 137       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 40.29%  |
| LightDM | 44        | 31.65%  |
| TDM     | 39        | 28.06%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 30        | 21.9%   |
| en_US   | 29        | 21.17%  |
| zh_CN   | 20        | 14.6%   |
| pt_BR   | 15        | 10.95%  |
| es_ES   | 11        | 8.03%   |
| de_DE   | 10        | 7.3%    |
| ru_RU   | 8         | 5.84%   |
| tr_TR   | 3         | 2.19%   |
| it_IT   | 3         | 2.19%   |
| pl_PL   | 2         | 1.46%   |
| fr_FR   | 2         | 1.46%   |
| sv_SE   | 1         | 0.73%   |
| nl_NL   | 1         | 0.73%   |
| ja_JP   | 1         | 0.73%   |
| en_GB   | 1         | 0.73%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 92        | 66.67%  |
| BIOS | 46        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 122       | 89.05%  |
| Unknown | 14        | 10.22%  |
| Overlay | 1         | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 69        | 50%     |
| Unknown | 55        | 39.86%  |
| MBR     | 14        | 10.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 109       | 78.42%  |
| Yes       | 30        | 21.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 70.29%  |
| Yes       | 41        | 29.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 34        | 24.82%  |
| Hewlett-Packard     | 24        | 17.52%  |
| Acer                | 15        | 10.95%  |
| Dell                | 13        | 9.49%   |
| Samsung Electronics | 7         | 5.11%   |
| ASUSTek Computer    | 7         | 5.11%   |
| HUAWEI              | 6         | 4.38%   |
| Sony                | 5         | 3.65%   |
| Toshiba             | 4         | 2.92%   |
| Timi                | 3         | 2.19%   |
| Google              | 2         | 1.46%   |
| Unknown             | 2         | 1.46%   |
| UNOWHY              | 1         | 0.73%   |
| Standard            | 1         | 0.73%   |
| Positivo            | 1         | 0.73%   |
| MSI                 | 1         | 0.73%   |
| Microtech           | 1         | 0.73%   |
| itel Mobile Limited | 1         | 0.73%   |
| Infinix             | 1         | 0.73%   |
| HONOR               | 1         | 0.73%   |
| Hometech            | 1         | 0.73%   |
| Gateway             | 1         | 0.73%   |
| Fujitsu             | 1         | 0.73%   |
| Chuwi               | 1         | 0.73%   |
| CCE                 | 1         | 0.73%   |
| BQ                  | 1         | 0.73%   |
| Apple               | 1         | 0.73%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 4         | 2.92%   |
| Samsung 340XAA/350XAA/550XAA                      | 2         | 1.46%   |
| Lenovo IdeaPad 120S-11IAP 81A4                    | 2         | 1.46%   |
| HP Pavilion Notebook                              | 2         | 1.46%   |
| HP Pavilion 15                                    | 2         | 1.46%   |
| HP ENVY 15                                        | 2         | 1.46%   |
| Acer Nitro AN515-54                               | 2         | 1.46%   |
| UNOWHY Y13G012S4EI                                | 1         | 0.73%   |
| Toshiba Satellite L75-C                           | 1         | 0.73%   |
| Toshiba Satellite E55t-A                          | 1         | 0.73%   |
| Toshiba Satellite C850D-11K                       | 1         | 0.73%   |
| Toshiba Satellite C850-1H6                        | 1         | 0.73%   |
| Timi TM1701                                       | 1         | 0.73%   |
| Timi RedmiBook Air 13                             | 1         | 0.73%   |
| Timi Redmi G 2022                                 | 1         | 0.73%   |
| Standard MB45II/MB45IN                            | 1         | 0.73%   |
| Sony VPCYB25AB                                    | 1         | 0.73%   |
| Sony VGN-NS140D                                   | 1         | 0.73%   |
| Sony VGN-AW11Z_B                                  | 1         | 0.73%   |
| Sony SVF14A190X                                   | 1         | 0.73%   |
| Sony SVE14135CXP                                  | 1         | 0.73%   |
| Samsung 800G5M/800G5W                             | 1         | 0.73%   |
| Samsung 550P5C/550P7C                             | 1         | 0.73%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.73%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 1         | 0.73%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.73%   |
| Positivo C14CU51                                  | 1         | 0.73%   |
| MSI GL72M 7REX                                    | 1         | 0.73%   |
| Microtech ebookPro                                | 1         | 0.73%   |
| Lenovo ZHAOYANG K4e-ITL 82F8                      | 1         | 0.73%   |
| Lenovo ZHAOYANG CF4620Z-A123 59082537             | 1         | 0.73%   |
| Lenovo Yoga 3 Pro-1370 80HE                       | 1         | 0.73%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN                 | 1         | 0.73%   |
| Lenovo XiaoXin-15ARE 2020 81YR                    | 1         | 0.73%   |
| Lenovo V310-15ISK 80SY                            | 1         | 0.73%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW       | 1         | 0.73%   |
| Lenovo ThinkPad T420 4236CU8                      | 1         | 0.73%   |
| Lenovo ThinkPad T420 4180M8P                      | 1         | 0.73%   |
| Lenovo ThinkPad T14 Gen 1 20UD003SRT              | 1         | 0.73%   |
| Lenovo ThinkPad L512 44444NG                      | 1         | 0.73%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 9         | 6.57%   |
| Dell Inspiron           | 9         | 6.57%   |
| Lenovo IdeaPad          | 8         | 5.84%   |
| Acer Aspire             | 8         | 5.84%   |
| HP EliteBook            | 6         | 4.38%   |
| HP Pavilion             | 5         | 3.65%   |
| HP Laptop               | 5         | 3.65%   |
| Toshiba Satellite       | 4         | 2.92%   |
| Lenovo Legion           | 4         | 2.92%   |
| Acer Nitro              | 4         | 2.92%   |
| Unknown                 | 4         | 2.92%   |
| Lenovo ThinkBook        | 3         | 2.19%   |
| Samsung 340XAA          | 2         | 1.46%   |
| Lenovo ZHAOYANG         | 2         | 1.46%   |
| HP ENVY                 | 2         | 1.46%   |
| Dell Latitude           | 2         | 1.46%   |
| Acer Swift              | 2         | 1.46%   |
| UNOWHY Y13G012S4EI      | 1         | 0.73%   |
| Timi TM1701             | 1         | 0.73%   |
| Timi RedmiBook          | 1         | 0.73%   |
| Timi Redmi              | 1         | 0.73%   |
| Standard MB45II         | 1         | 0.73%   |
| Sony VPCYB25AB          | 1         | 0.73%   |
| Sony VGN-NS140D         | 1         | 0.73%   |
| Sony VGN-AW11Z          | 1         | 0.73%   |
| Sony SVF14A190X         | 1         | 0.73%   |
| Sony SVE14135CXP        | 1         | 0.73%   |
| Samsung 800G5M          | 1         | 0.73%   |
| Samsung 550P5C          | 1         | 0.73%   |
| Samsung 500R4K          | 1         | 0.73%   |
| Samsung 300E4A          | 1         | 0.73%   |
| Samsung 270E5J          | 1         | 0.73%   |
| Positivo C14CU51        | 1         | 0.73%   |
| MSI GL72M               | 1         | 0.73%   |
| Microtech ebookPro      | 1         | 0.73%   |
| Lenovo Yoga             | 1         | 0.73%   |
| Lenovo XiaoXinAir-14ARE | 1         | 0.73%   |
| Lenovo XiaoXin-15ARE    | 1         | 0.73%   |
| Lenovo V310-15ISK       | 1         | 0.73%   |
| Lenovo G50-80           | 1         | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 16        | 11.68%  |
| 2021    | 14        | 10.22%  |
| 2017    | 14        | 10.22%  |
| 2018    | 13        | 9.49%   |
| 2015    | 10        | 7.3%    |
| 2012    | 10        | 7.3%    |
| 2020    | 9         | 6.57%   |
| 2014    | 8         | 5.84%   |
| 2013    | 8         | 5.84%   |
| 2011    | 7         | 5.11%   |
| 2010    | 7         | 5.11%   |
| 2022    | 6         | 4.38%   |
| 2016    | 6         | 4.38%   |
| 2009    | 4         | 2.92%   |
| 2023    | 2         | 1.46%   |
| 2008    | 2         | 1.46%   |
| Unknown | 1         | 0.73%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 137       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 128       | 93.43%  |
| Enabled  | 9         | 6.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 135       | 98.54%  |
| Yes  | 2         | 1.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 49        | 35.77%  |
| 8.01-16.0   | 29        | 21.17%  |
| 3.01-4.0    | 27        | 19.71%  |
| 16.01-24.0  | 20        | 14.6%   |
| 32.01-64.0  | 6         | 4.38%   |
| 1.01-2.0    | 4         | 2.92%   |
| 2.01-3.0    | 1         | 0.73%   |
| 64.01-256.0 | 1         | 0.73%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 44        | 30.99%  |
| 1.01-2.0  | 43        | 30.28%  |
| 3.01-4.0  | 23        | 16.2%   |
| 4.01-8.0  | 21        | 14.79%  |
| 0.51-1.0  | 8         | 5.63%   |
| 8.01-16.0 | 3         | 2.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 102       | 73.38%  |
| 2      | 36        | 25.9%   |
| 3      | 1         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 67.15%  |
| Yes       | 45        | 32.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 71.53%  |
| No        | 39        | 28.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 98.54%  |
| No        | 2         | 1.46%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 82.48%  |
| No        | 24        | 17.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| Brazil                | 31        | 22.46%  |
| China                 | 22        | 15.94%  |
| Germany               | 11        | 7.97%   |
| Russia                | 6         | 4.35%   |
| USA                   | 5         | 3.62%   |
| Turkey                | 5         | 3.62%   |
| Spain                 | 5         | 3.62%   |
| Indonesia             | 4         | 2.9%    |
| Poland                | 3         | 2.17%   |
| Japan                 | 3         | 2.17%   |
| Italy                 | 3         | 2.17%   |
| Chile                 | 3         | 2.17%   |
| Panama                | 2         | 1.45%   |
| India                 | 2         | 1.45%   |
| Canada                | 2         | 1.45%   |
| Bulgaria              | 2         | 1.45%   |
| Austria               | 2         | 1.45%   |
| Vietnam               | 1         | 0.72%   |
| Venezuela             | 1         | 0.72%   |
| Tunisia               | 1         | 0.72%   |
| Sweden                | 1         | 0.72%   |
| South Africa          | 1         | 0.72%   |
| Singapore             | 1         | 0.72%   |
| Serbia                | 1         | 0.72%   |
| Sao Tome and Principe | 1         | 0.72%   |
| Portugal              | 1         | 0.72%   |
| Pakistan              | 1         | 0.72%   |
| Netherlands           | 1         | 0.72%   |
| Mexico                | 1         | 0.72%   |
| Lebanon               | 1         | 0.72%   |
| Kenya                 | 1         | 0.72%   |
| Iran                  | 1         | 0.72%   |
| Hong Kong             | 1         | 0.72%   |
| Greece                | 1         | 0.72%   |
| France                | 1         | 0.72%   |
| Ecuador               | 1         | 0.72%   |
| Czechia               | 1         | 0.72%   |
| Cuba                  | 1         | 0.72%   |
| Colombia              | 1         | 0.72%   |
| Belarus               | 1         | 0.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Beijing          | 5         | 3.62%   |
| Wuhan            | 3         | 2.17%   |
| Guangzhou        | 3         | 2.17%   |
| Curitiba         | 3         | 2.17%   |
| Uberlândia      | 2         | 1.45%   |
| Surabaya         | 2         | 1.45%   |
| Sao Paulo        | 2         | 1.45%   |
| Petrópolis      | 2         | 1.45%   |
| Londrina         | 2         | 1.45%   |
| Innsbruck        | 2         | 1.45%   |
| David            | 2         | 1.45%   |
| Atlanta          | 2         | 1.45%   |
| Yozgat           | 1         | 0.72%   |
| Yogyakarta       | 1         | 0.72%   |
| Yekaterinburg    | 1         | 0.72%   |
| Xuhui            | 1         | 0.72%   |
| Wanchai          | 1         | 0.72%   |
| Voronezh         | 1         | 0.72%   |
| Villa Ballester  | 1         | 0.72%   |
| Vigo             | 1         | 0.72%   |
| Ufa              | 1         | 0.72%   |
| Tomsk            | 1         | 0.72%   |
| Tokyo            | 1         | 0.72%   |
| Tianjin          | 1         | 0.72%   |
| TehrДЃn        | 1         | 0.72%   |
| Taiyuan          | 1         | 0.72%   |
| Tai'an           | 1         | 0.72%   |
| SГЈo TomГ©   | 1         | 0.72%   |
| Suzano           | 1         | 0.72%   |
| Sofia            | 1         | 0.72%   |
| Singapore        | 1         | 0.72%   |
| Shanghai         | 1         | 0.72%   |
| Sao Carlos       | 1         | 0.72%   |
| Sao Bento do Sul | 1         | 0.72%   |
| Santiago         | 1         | 0.72%   |
| Samara           | 1         | 0.72%   |
| Saitama          | 1         | 0.72%   |
| Rzeszów         | 1         | 0.72%   |
| Rotenburg        | 1         | 0.72%   |
| Poznan           | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 23        | 26     | 13.29%  |
| Seagate                        | 23        | 26     | 13.29%  |
| Samsung Electronics            | 17        | 19     | 9.83%   |
| Unknown                        | 13        | 13     | 7.51%   |
| Toshiba                        | 13        | 14     | 7.51%   |
| SK hynix                       | 9         | 10     | 5.2%    |
| SanDisk                        | 9         | 9      | 5.2%    |
| Kingston                       | 9         | 10     | 5.2%    |
| Micron Technology              | 6         | 8      | 3.47%   |
| HGST                           | 6         | 6      | 3.47%   |
| Intel                          | 5         | 6      | 2.89%   |
| Hitachi                        | 4         | 4      | 2.31%   |
| Crucial                        | 4         | 4      | 2.31%   |
| LITEON                         | 3         | 3      | 1.73%   |
| China                          | 3         | 3      | 1.73%   |
| SPCC                           | 2         | 3      | 1.16%   |
| Silicon Motion                 | 2         | 2      | 1.16%   |
| KIOXIA                         | 2         | 2      | 1.16%   |
| V-GeN                          | 1         | 1      | 0.58%   |
| Transcend                      | 1         | 1      | 0.58%   |
| Solid State Storage Technology | 1         | 1      | 0.58%   |
| Phison                         | 1         | 1      | 0.58%   |
| Patriot                        | 1         | 1      | 0.58%   |
| OEM                            | 1         | 1      | 0.58%   |
| OCZ                            | 1         | 1      | 0.58%   |
| Netac                          | 1         | 1      | 0.58%   |
| Microtech                      | 1         | 1      | 0.58%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.58%   |
| Kingston Technology Company    | 1         | 1      | 0.58%   |
| KingSpec                       | 1         | 1      | 0.58%   |
| JMicron Technology             | 1         | 1      | 0.58%   |
| Intenso                        | 1         | 1      | 0.58%   |
| Fujitsu                        | 1         | 2      | 0.58%   |
| FORESEE                        | 1         | 1      | 0.58%   |
| Apple                          | 1         | 2      | 0.58%   |
| ADATA Technology               | 1         | 1      | 0.58%   |
| A-DATA Technology              | 1         | 1      | 0.58%   |
| Unknown                        | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 3.39%   |
| Toshiba MQ01ABF050 500GB             | 4         | 2.26%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 2.26%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.69%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.69%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 1.13%   |
| Unknown MMC Card                     | 2         | 1.13%   |
| Seagate ST9320325AS 320GB            | 2         | 1.13%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 1.13%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.13%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.13%   |
| HGST HTS545050A7E680 500GB           | 2         | 1.13%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.56%   |
| WDC WD7500BPVT-24HXZT3 752GB         | 1         | 0.56%   |
| WDC WD5000LPZX-75Z10T0 500GB         | 1         | 0.56%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.56%   |
| WDC WD5000LPVX-08V0TT6 500GB         | 1         | 0.56%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.56%   |
| WDC WD3200BEVT-60A23T0 320GB         | 1         | 0.56%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.56%   |
| WDC WD3200BEVT-08A23T1 320GB         | 1         | 0.56%   |
| WDC WD10SPZX-35Z10T0 1TB             | 1         | 0.56%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.56%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.56%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.56%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.56%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.56%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.56%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.56%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 1         | 0.56%   |
| WDC PC SN720 SDAPNTW-512G-1127 512GB | 1         | 0.56%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.56%   |
| WDC PC SN520 NVMe 256GB              | 1         | 0.56%   |
| V-GeN V-GEN10SM19AR120SDK 120GB SSD  | 1         | 0.56%   |
| Unknown SSO256GTLC9-SB3-4L 256GB SSD | 1         | 0.56%   |
| Unknown NVMe SSD Drive 512GB         | 1         | 0.56%   |
| Unknown MMC64G  64GB                 | 1         | 0.56%   |

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
| SanDisk             | 8         | 8      | 16.67%  |
| Samsung Electronics | 7         | 8      | 14.58%  |
| Kingston            | 7         | 8      | 14.58%  |
| WDC                 | 3         | 3      | 6.25%   |
| Crucial             | 3         | 3      | 6.25%   |
| China               | 3         | 3      | 6.25%   |
| SPCC                | 2         | 3      | 4.17%   |
| SK hynix            | 2         | 2      | 4.17%   |
| Micron Technology   | 2         | 3      | 4.17%   |
| LITEON              | 2         | 2      | 4.17%   |
| V-GeN               | 1         | 1      | 2.08%   |
| Unknown             | 1         | 1      | 2.08%   |
| Transcend           | 1         | 1      | 2.08%   |
| OCZ                 | 1         | 1      | 2.08%   |
| Netac               | 1         | 1      | 2.08%   |
| Microtech           | 1         | 1      | 2.08%   |
| KingSpec            | 1         | 1      | 2.08%   |
| Intenso             | 1         | 1      | 2.08%   |
| Intel               | 1         | 2      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 70     | 37.28%  |
| NVMe | 49        | 54     | 28.99%  |
| SSD  | 45        | 53     | 26.63%  |
| MMC  | 12        | 13     | 7.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 92        | 119    | 58.97%  |
| NVMe | 48        | 53     | 30.77%  |
| MMC  | 12        | 13     | 7.69%   |
| SAS  | 4         | 5      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 80     | 62.75%  |
| 0.51-1.0   | 35        | 40     | 34.31%  |
| 1.01-2.0   | 2         | 2      | 1.96%   |
| 4.01-10.0  | 1         | 1      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 49        | 34.75%  |
| 101-250        | 36        | 25.53%  |
| 501-1000       | 29        | 20.57%  |
| 1001-2000      | 10        | 7.09%   |
| More than 3000 | 4         | 2.84%   |
| 21-50          | 4         | 2.84%   |
| 51-100         | 4         | 2.84%   |
| Unknown        | 3         | 2.13%   |
| 2001-3000      | 1         | 0.71%   |
| 1-20           | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 32        | 22.86%  |
| 1-20      | 32        | 22.86%  |
| 101-250   | 24        | 17.14%  |
| 51-100    | 20        | 14.29%  |
| 251-500   | 17        | 12.14%  |
| 501-1000  | 6         | 4.29%   |
| 1001-2000 | 4         | 2.86%   |
| Unknown   | 3         | 2.14%   |
| 2001-3000 | 2         | 1.43%   |

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
| Detected | 69        | 95     | 46.94%  |
| Works    | 65        | 81     | 44.22%  |
| Malfunc  | 12        | 13     | 8.16%   |
| Failed   | 1         | 1      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 97        | 62.99%  |
| AMD                            | 10        | 6.49%   |
| Samsung Electronics            | 9         | 5.84%   |
| SK hynix                       | 7         | 4.55%   |
| SanDisk                        | 5         | 3.25%   |
| Micron Technology              | 4         | 2.6%    |
| KIOXIA                         | 3         | 1.95%   |
| Kingston Technology Company    | 3         | 1.95%   |
| Silicon Motion                 | 2         | 1.3%    |
| MAXIO Technology (Hangzhou)    | 2         | 1.3%    |
| Zhaoxin                        | 1         | 0.65%   |
| Toshiba America Info Systems   | 1         | 0.65%   |
| Solid State Storage Technology | 1         | 0.65%   |
| Shenzhen Longsys Electronics   | 1         | 0.65%   |
| Realtek Semiconductor          | 1         | 0.65%   |
| Phison Electronics             | 1         | 0.65%   |
| Micron/Crucial Technology      | 1         | 0.65%   |
| Lite-On Technology             | 1         | 0.65%   |
| JMicron Technology             | 1         | 0.65%   |
| Apple                          | 1         | 0.65%   |
| ADATA Technology               | 1         | 0.65%   |
| Unknown                        | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 9.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 7.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 6.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 6.21%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 5.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 3.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 3.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 3.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 2.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.48%   |
| SK hynix BC511 NVMe SSD                                                          | 3         | 1.86%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.86%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 1.24%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 1.24%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.24%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 1.24%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.24%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.24%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G/KH-40000 StorX AHCI Controller            | 1         | 0.62%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.62%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 0.62%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 1         | 0.62%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.62%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                | 1         | 0.62%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.62%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                            | 1         | 0.62%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 0.62%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 1         | 0.62%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                              | 1         | 0.62%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                         | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 101       | 63.92%  |
| NVMe | 47        | 29.75%  |
| RAID | 6         | 3.8%    |
| IDE  | 4         | 2.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 112       | 81.75%  |
| AMD          | 24        | 17.52%  |
| CentaurHauls | 1         | 0.73%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 3.65%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 2.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 2.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.19%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 2.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.19%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.19%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.46%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.46%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.46%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.46%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.46%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.46%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.46%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.46%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.46%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.46%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.46%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.46%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.46%   |
| AMD Ryzen 5 4600U with Radeon Graphics        | 2         | 1.46%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.46%   |
| AMD 3020e with Radeon Graphics                | 2         | 1.46%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.73%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.73%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.73%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.73%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.73%   |
| Intel Core M-5Y71 CPU @ 1.20GHz               | 1         | 0.73%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.73%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.73%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.73%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 38        | 27.74%  |
| Intel Core i7           | 30        | 21.9%   |
| Other                   | 11        | 8.03%   |
| Intel Core i3           | 10        | 7.3%    |
| Intel Celeron           | 9         | 6.57%   |
| AMD Ryzen 7             | 7         | 5.11%   |
| AMD Ryzen 5             | 6         | 4.38%   |
| Intel Core 2 Duo        | 4         | 2.92%   |
| Intel Pentium Dual-Core | 3         | 2.19%   |
| Intel Atom              | 3         | 2.19%   |
| AMD Ryzen 3             | 3         | 2.19%   |
| Intel Pentium           | 2         | 1.46%   |
| AMD A10                 | 2         | 1.46%   |
| Intel Pentium Silver    | 1         | 0.73%   |
| Intel Core m3           | 1         | 0.73%   |
| Intel Core M            | 1         | 0.73%   |
| Intel Core i9           | 1         | 0.73%   |
| Intel Celeron Dual-Core | 1         | 0.73%   |
| AMD Ryzen 7 PRO         | 1         | 0.73%   |
| AMD Ryzen 5 PRO         | 1         | 0.73%   |
| AMD E1                  | 1         | 0.73%   |
| AMD E                   | 1         | 0.73%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 73        | 53.28%  |
| 4      | 46        | 33.58%  |
| 6      | 7         | 5.11%   |
| 8      | 6         | 4.38%   |
| 12     | 2         | 1.46%   |
| 10     | 2         | 1.46%   |
| 1      | 1         | 0.73%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 137       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 77.37%  |
| 1      | 31        | 22.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 126       | 91.97%  |
| Unknown        | 11        | 8.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 18.71%  |
| 0x806ec    | 10        | 7.19%   |
| 0x306a9    | 10        | 7.19%   |
| 0x40651    | 9         | 6.47%   |
| 0x806e9    | 8         | 5.76%   |
| 0x306d4    | 7         | 5.04%   |
| 0x406e3    | 6         | 4.32%   |
| 0x206a7    | 6         | 4.32%   |
| 0x906ea    | 5         | 3.6%    |
| 0x1067a    | 4         | 2.88%   |
| 0x906a3    | 3         | 2.16%   |
| 0x806ea    | 3         | 2.16%   |
| 0x08600106 | 3         | 2.16%   |
| 0x08108109 | 3         | 2.16%   |
| 0x906e9    | 2         | 1.44%   |
| 0x806c1    | 2         | 1.44%   |
| 0x706a8    | 2         | 1.44%   |
| 0x406c4    | 2         | 1.44%   |
| 0x20655    | 2         | 1.44%   |
| 0x08600104 | 2         | 1.44%   |
| 0x08200103 | 2         | 1.44%   |
| 0x08108102 | 2         | 1.44%   |
| 0xb06a3    | 1         | 0.72%   |
| 0xa0652    | 1         | 0.72%   |
| 0x806d1    | 1         | 0.72%   |
| 0x806c2    | 1         | 0.72%   |
| 0x706a1    | 1         | 0.72%   |
| 0x6fd      | 1         | 0.72%   |
| 0x406c3    | 1         | 0.72%   |
| 0x30678    | 1         | 0.72%   |
| 0x10676    | 1         | 0.72%   |
| 0x0a704103 | 1         | 0.72%   |
| 0x0a50000c | 1         | 0.72%   |
| 0x0a50000b | 1         | 0.72%   |
| 0x0a404101 | 1         | 0.72%   |
| 0x08608102 | 1         | 0.72%   |
| 0x08600103 | 1         | 0.72%   |
| 0x08600102 | 1         | 0.72%   |
| 0x0810100b | 1         | 0.72%   |
| 0x06006115 | 1         | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 33        | 24.09%  |
| IvyBridge        | 13        | 9.49%   |
| Haswell          | 11        | 8.03%   |
| Broadwell        | 10        | 7.3%    |
| Zen 2            | 7         | 5.11%   |
| SandyBridge      | 7         | 5.11%   |
| Penryn           | 7         | 5.11%   |
| Skylake          | 6         | 4.38%   |
| Silvermont       | 6         | 4.38%   |
| Zen+             | 5         | 3.65%   |
| Goldmont plus    | 4         | 2.92%   |
| Alderlake Hybrid | 4         | 2.92%   |
| Unknown          | 4         | 2.92%   |
| Zen              | 3         | 2.19%   |
| Westmere         | 3         | 2.19%   |
| TigerLake        | 3         | 2.19%   |
| Zen 3            | 2         | 1.46%   |
| Goldmont         | 2         | 1.46%   |
| Excavator        | 2         | 1.46%   |
| Bobcat           | 2         | 1.46%   |
| Icelake          | 1         | 0.73%   |
| Core             | 1         | 0.73%   |
| CometLake        | 1         | 0.73%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 110       | 59.46%  |
| Nvidia  | 45        | 24.32%  |
| AMD     | 29        | 15.68%  |
| Zhaoxin | 1         | 0.54%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 6.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.88%   |
| Intel HD Graphics 5500                                                                   | 9         | 4.81%   |
| Intel HD Graphics 620                                                                    | 8         | 4.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.74%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 3.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.21%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 3.21%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 2.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.14%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.6%    |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.07%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.07%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 1.07%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.07%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.07%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1.07%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 1.07%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.07%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 1.07%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                                 | 2         | 1.07%   |
| Intel HD Graphics 630                                                                    | 2         | 1.07%   |
| Intel HD Graphics 500                                                                    | 2         | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.07%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 1.07%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.07%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 0.53%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.53%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 64        | 46.72%  |
| Intel + Nvidia | 40        | 29.2%   |
| 1 x AMD        | 19        | 13.87%  |
| Intel + AMD    | 6         | 4.38%   |
| 1 x Nvidia     | 3         | 2.19%   |
| 2 x AMD        | 2         | 1.46%   |
| AMD + Nvidia   | 2         | 1.46%   |
| 1 x Zhaoxin    | 1         | 0.73%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 111       | 80.43%  |
| Proprietary | 21        | 15.22%  |
| Unknown     | 6         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 57.14%  |
| 1.01-2.0   | 29        | 20.71%  |
| 3.01-4.0   | 15        | 10.71%  |
| 0.01-0.5   | 12        | 8.57%   |
| 0.51-1.0   | 3         | 2.14%   |
| 5.01-6.0   | 1         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 20%     |
| BOE                     | 28        | 19.31%  |
| Chimei Innolux          | 20        | 13.79%  |
| Samsung Electronics     | 17        | 11.72%  |
| LG Display              | 16        | 11.03%  |
| CSO                     | 5         | 3.45%   |
| Hewlett-Packard         | 3         | 2.07%   |
| Goldstar                | 3         | 2.07%   |
| AOC                     | 3         | 2.07%   |
| Lenovo                  | 2         | 1.38%   |
| InfoVision              | 2         | 1.38%   |
| Chi Mei Optoelectronics | 2         | 1.38%   |
| ViewSonic               | 1         | 0.69%   |
| TMX                     | 1         | 0.69%   |
| Sharp                   | 1         | 0.69%   |
| SAC                     | 1         | 0.69%   |
| PANDA                   | 1         | 0.69%   |
| LG Philips              | 1         | 0.69%   |
| JDI                     | 1         | 0.69%   |
| Iiyama                  | 1         | 0.69%   |
| HKC                     | 1         | 0.69%   |
| HB@                     | 1         | 0.69%   |
| HannStar                | 1         | 0.69%   |
| Dell                    | 1         | 0.69%   |
| CS_                     | 1         | 0.69%   |
| BenQ                    | 1         | 0.69%   |
| Apple                   | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 2.05%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 2.05%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 2         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.37%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 1.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.37%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 1.37%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 2         | 1.37%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch             | 1         | 0.68%   |
| TMX TL140VDXP04-0 TMX1398 1920x1080 309x174mm 14.0-inch               | 1         | 0.68%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0167 1280x1024 338x270mm 17.0-inch  | 1         | 0.68%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 698x393mm 31.5-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC864D 1920x1080 293x165mm 13.2-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC534B 1600x900 382x215mm 17.3-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                     | 1         | 0.68%   |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch                 | 1         | 0.68%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.68%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.68%   |
| LG Display LP156WH1-TLA1 LGD6301 1366x768 344x194mm 15.5-inch         | 1         | 0.68%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.68%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.68%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.68%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x174mm 14.0-inch          | 1         | 0.68%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 58        | 42.34%  |
| 1366x768 (WXGA)  | 51        | 37.23%  |
| 1600x900 (HD+)   | 6         | 4.38%   |
| 3840x2160 (4K)   | 4         | 2.92%   |
| 2560x1600        | 4         | 2.92%   |
| 2880x1800        | 3         | 2.19%   |
| 3000x2000        | 2         | 1.46%   |
| 3440x1440        | 1         | 0.73%   |
| 3200x1800 (QHD+) | 1         | 0.73%   |
| 2560x1440 (QHD)  | 1         | 0.73%   |
| 2288x1287        | 1         | 0.73%   |
| 2160x1440        | 1         | 0.73%   |
| 1920x540         | 1         | 0.73%   |
| 1680x945         | 1         | 0.73%   |
| 1280x800 (WXGA)  | 1         | 0.73%   |
| 1280x1024 (SXGA) | 1         | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 59        | 40.69%  |
| 13      | 30        | 20.69%  |
| 14      | 23        | 15.86%  |
| 17      | 5         | 3.45%   |
| 23      | 4         | 2.76%   |
| 27      | 3         | 2.07%   |
| 21      | 3         | 2.07%   |
| 18      | 3         | 2.07%   |
| 11      | 3         | 2.07%   |
| 32      | 2         | 1.38%   |
| 24      | 2         | 1.38%   |
| 16      | 2         | 1.38%   |
| 12      | 2         | 1.38%   |
| 40      | 1         | 0.69%   |
| 31      | 1         | 0.69%   |
| 25      | 1         | 0.69%   |
| Unknown | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 70.42%  |
| 201-300     | 17        | 11.97%  |
| 501-600     | 9         | 6.34%   |
| 351-400     | 6         | 4.23%   |
| 401-500     | 5         | 3.52%   |
| 701-800     | 2         | 1.41%   |
| 801-900     | 1         | 0.7%    |
| 601-700     | 1         | 0.7%    |
| Unknown     | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 116       | 87.88%  |
| 16/10 | 11        | 8.33%   |
| 3/2   | 4         | 3.03%   |
| 5/4   | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 59        | 40.41%  |
| 81-90          | 44        | 30.14%  |
| 71-80          | 9         | 6.16%   |
| 201-250        | 7         | 4.79%   |
| 141-150        | 4         | 2.74%   |
| 51-60          | 3         | 2.05%   |
| 351-500        | 3         | 2.05%   |
| 301-350        | 3         | 2.05%   |
| 251-300        | 3         | 2.05%   |
| 121-130        | 3         | 2.05%   |
| 61-70          | 2         | 1.37%   |
| 111-120        | 2         | 1.37%   |
| 151-200        | 1         | 0.68%   |
| 131-140        | 1         | 0.68%   |
| 501-1000       | 1         | 0.68%   |
| Unknown        | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 56        | 39.44%  |
| 121-160       | 51        | 35.92%  |
| 51-100        | 16        | 11.27%  |
| 161-240       | 12        | 8.45%   |
| More than 240 | 6         | 4.23%   |
| Unknown       | 1         | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 113       | 81.88%  |
| 2     | 20        | 14.49%  |
| 0     | 4         | 2.9%    |
| 3     | 1         | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 91        | 43.75%  |
| Intel                           | 59        | 28.37%  |
| Qualcomm Atheros                | 35        | 16.83%  |
| Broadcom                        | 6         | 2.88%   |
| MediaTek                        | 3         | 1.44%   |
| Marvell Technology Group        | 3         | 1.44%   |
| Broadcom Limited                | 3         | 1.44%   |
| Xiaomi                          | 2         | 0.96%   |
| Ralink Technology               | 1         | 0.48%   |
| Ralink                          | 1         | 0.48%   |
| Qualcomm Atheros Communications | 1         | 0.48%   |
| OPPO Electronics                | 1         | 0.48%   |
| Huawei Technologies             | 1         | 0.48%   |
| Hewlett-Packard                 | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 22.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 7.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 4.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 3.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.89%   |
| Intel Wireless 3165                                               | 7         | 2.89%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 2.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.65%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.24%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.24%   |
| Intel Wireless 7260                                               | 3         | 1.24%   |
| Intel Wireless 3160                                               | 3         | 1.24%   |
| Intel WiFi Link 5100                                              | 3         | 1.24%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.24%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.83%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 2         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.83%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.83%   |
| Intel Wireless 7265                                               | 2         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 41.73%  |
| Realtek Semiconductor           | 34        | 24.46%  |
| Qualcomm Atheros                | 34        | 24.46%  |
| Broadcom                        | 4         | 2.88%   |
| MediaTek                        | 3         | 2.16%   |
| Broadcom Limited                | 3         | 2.16%   |
| Ralink Technology               | 1         | 0.72%   |
| Ralink                          | 1         | 0.72%   |
| Qualcomm Atheros Communications | 1         | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 8.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 6.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 5%      |
| Intel Wireless 3165                                            | 7         | 5%      |
| Intel Wi-Fi 6 AX200                                            | 6         | 4.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.86%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 2.14%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.14%   |
| Intel Wireless 7260                                            | 3         | 2.14%   |
| Intel Wireless 3160                                            | 3         | 2.14%   |
| Intel WiFi Link 5100                                           | 3         | 2.14%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 2.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.43%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 2         | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.43%   |
| Intel Wireless 7265                                            | 2         | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.71%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.71%   |
| Realtek 802.11ac NIC                                           | 1         | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.71%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.71%   |

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
| OPPO RMX2027                                                      | 1         | 0.98%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.98%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.98%   |
| Huawei ALP-AL00                                                   | 1         | 0.98%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 57.69%  |
| Ethernet | 99        | 42.31%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 83.21%  |
| Ethernet | 23        | 16.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 93        | 67.88%  |
| 1     | 40        | 29.2%   |
| 0     | 3         | 2.19%   |
| 3     | 1         | 0.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 128       | 92.75%  |
| Yes  | 10        | 7.25%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 42.48%  |
| Qualcomm Atheros Communications | 20        | 17.7%   |
| Realtek Semiconductor           | 15        | 13.27%  |
| Foxconn / Hon Hai               | 8         | 7.08%   |
| Broadcom                        | 6         | 5.31%   |
| Realtek                         | 5         | 4.42%   |
| Lite-On Technology              | 3         | 2.65%   |
| IMC Networks                    | 3         | 2.65%   |
| Cambridge Silicon Radio         | 2         | 1.77%   |
| Toshiba                         | 1         | 0.88%   |
| Ralink Technology               | 1         | 0.88%   |
| Dell                            | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 21        | 18.58%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 15        | 13.27%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 7.08%   |
| Intel AX201 Bluetooth                                                               | 8         | 7.08%   |
| Realtek Bluetooth Radio                                                             | 7         | 6.19%   |
| Intel AX200 Bluetooth                                                               | 6         | 5.31%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 4.42%   |
| Realtek Bluetooth Radio                                                             | 5         | 4.42%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.77%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.77%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.77%   |
| Intel Bluetooth Device                                                              | 2         | 1.77%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.77%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.77%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.77%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.88%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.88%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.88%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.88%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.88%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.88%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.88%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.88%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.88%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.88%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.88%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 0.88%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.88%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.88%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 109       | 72.67%  |
| AMD                 | 24        | 16%     |
| Nvidia              | 14        | 9.33%   |
| Zhaoxin             | 1         | 0.67%   |
| JMTek               | 1         | 0.67%   |
| Creative Technology | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 10.77%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 10.26%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 7.18%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 5.64%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 5.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 5.13%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 5.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 4.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 4.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 4.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.54%   |
| Nvidia Audio device                                                                               | 3         | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.54%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.03%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.03%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.51%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000 High Definition Audio Controller                 | 1         | 0.51%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.51%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.51%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.51%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.51%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 0.51%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.51%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                      | 1         | 0.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 29.17%  |
| SK hynix            | 25        | 26.04%  |
| Unknown             | 10        | 10.42%  |
| Micron Technology   | 9         | 9.38%   |
| Smart               | 4         | 4.17%   |
| Kingston            | 4         | 4.17%   |
| Ramaxel Technology  | 3         | 3.13%   |
| Nanya Technology    | 3         | 3.13%   |
| Unknown (ABCD)      | 2         | 2.08%   |
| A-DATA Technology   | 2         | 2.08%   |
| Unknown (07FB)      | 1         | 1.04%   |
| Smart Brazil        | 1         | 1.04%   |
| MTASE               | 1         | 1.04%   |
| Kingmax             | 1         | 1.04%   |
| Crucial             | 1         | 1.04%   |
| ChangXin Memory     | 1         | 1.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 3         | 2.97%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 1.98%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.98%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.98%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 2         | 1.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.98%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.98%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.98%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.98%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.99%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.99%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 0.99%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 0.99%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.99%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.99%   |
| Unknown RAM Module 2048MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.99%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.99%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.99%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s                 | 1         | 0.99%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.99%   |
| Unknown (07FB) RAM GST32G08SCL196P-26 32GB SODIMM DDR4 2667MT/s  | 1         | 0.99%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 1         | 0.99%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.99%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 1         | 0.99%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.99%   |
| SK hynix RAM MPPS4GBPC1600 1.35 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.99%   |
| SK hynix RAM Module 16384MB SODIMM DDR5 5600MT/s                 | 1         | 0.99%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 0.99%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 1         | 0.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.99%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.99%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.99%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 40        | 47.06%  |
| DDR3   | 21        | 24.71%  |
| LPDDR3 | 8         | 9.41%   |
| LPDDR4 | 7         | 8.24%   |
| DDR5   | 3         | 3.53%   |
| DDR2   | 3         | 3.53%   |
| LPDDR5 | 2         | 2.35%   |
| SDRAM  | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 81.18%  |
| Row Of Chips | 15        | 17.65%  |
| Unknown      | 1         | 1.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 37        | 41.11%  |
| 4096  | 30        | 33.33%  |
| 2048  | 13        | 14.44%  |
| 16384 | 7         | 7.78%   |
| 1024  | 2         | 2.22%   |
| 32768 | 1         | 1.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 19        | 21.59%  |
| 1600    | 18        | 20.45%  |
| 3200    | 12        | 13.64%  |
| 2400    | 7         | 7.95%   |
| 2133    | 7         | 7.95%   |
| 1334    | 3         | 3.41%   |
| 1333    | 3         | 3.41%   |
| 4800    | 2         | 2.27%   |
| 3266    | 2         | 2.27%   |
| 800     | 2         | 2.27%   |
| Unknown | 2         | 2.27%   |
| 7467    | 1         | 1.14%   |
| 6400    | 1         | 1.14%   |
| 5600    | 1         | 1.14%   |
| 4267    | 1         | 1.14%   |
| 4266    | 1         | 1.14%   |
| 3733    | 1         | 1.14%   |
| 2933    | 1         | 1.14%   |
| 2666    | 1         | 1.14%   |
| 2048    | 1         | 1.14%   |
| 1867    | 1         | 1.14%   |
| 1066    | 1         | 1.14%   |

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
| Chicony Electronics                    | 32        | 26.45%  |
| Microdia                               | 11        | 9.09%   |
| IMC Networks                           | 11        | 9.09%   |
| Realtek Semiconductor                  | 10        | 8.26%   |
| Quanta                                 | 9         | 7.44%   |
| Sunplus Innovation Technology          | 7         | 5.79%   |
| Syntek                                 | 6         | 4.96%   |
| Suyin                                  | 6         | 4.96%   |
| Silicon Motion                         | 6         | 4.96%   |
| Lite-On Technology                     | 4         | 3.31%   |
| Bison Electronics                      | 4         | 3.31%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.48%   |
| Ricoh                                  | 2         | 1.65%   |
| Primax Electronics                     | 2         | 1.65%   |
| Alcor Micro                            | 2         | 1.65%   |
| LG Electronics                         | 1         | 0.83%   |
| Lenovo                                 | 1         | 0.83%   |
| kingcome                               | 1         | 0.83%   |
| icSpring                               | 1         | 0.83%   |
| Goodong Industry                       | 1         | 0.83%   |
| Acer                                   | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 8         | 6.61%   |
| IMC Networks Integrated Camera           | 5         | 4.13%   |
| Quanta HD User Facing                    | 4         | 3.31%   |
| Chicony EasyCamera                       | 4         | 3.31%   |
| Syntek EasyCamera                        | 3         | 2.48%   |
| Silicon Motion Web Camera                | 3         | 2.48%   |
| Quanta HP TrueVision HD Camera           | 3         | 2.48%   |
| IMC Networks ov9734_azurewave_camera     | 3         | 2.48%   |
| Chicony TOSHIBA Web Camera - HD          | 3         | 2.48%   |
| Syntek Integrated Camera                 | 2         | 1.65%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.65%   |
| Sunplus HD WebCam                        | 2         | 1.65%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.65%   |
| Realtek HP "Truevision HD" laptop camera | 2         | 1.65%   |
| Primax HP HD Webcam [Fixed]              | 2         | 1.65%   |
| Microdia USB 2.0 Camera                  | 2         | 1.65%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.65%   |
| Chicony HP Webcam                        | 2         | 1.65%   |
| Chicony HP HD Webcam                     | 2         | 1.65%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.83%   |
| Suyin Integrated_Webcam_HD               | 1         | 0.83%   |
| Suyin HP Webcam 101                      | 1         | 0.83%   |
| Suyin HP Truevision HD                   | 1         | 0.83%   |
| Suyin HD WebCam                          | 1         | 0.83%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.83%   |
| Suyin 1.3M HD WebCam                     | 1         | 0.83%   |
| Sunplus XiaoMi USB 2.0 Webcam            | 1         | 0.83%   |
| Sunplus HP Wide Vision HD                | 1         | 0.83%   |
| Sunplus Asus Webcam                      | 1         | 0.83%   |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.83%   |
| Silicon Motion WebCam SC-0311139N        | 1         | 0.83%   |
| Silicon Motion ATIV VGA Camera           | 1         | 0.83%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 0.83%   |
| Ricoh Laptop_Integrated_Webcam_FHD       | 1         | 0.83%   |
| Realtek USB2.0 camera                    | 1         | 0.83%   |
| Realtek USB Camera                       | 1         | 0.83%   |
| Realtek Laptop_Integrated_Webcam_HD      | 1         | 0.83%   |
| Realtek HP Wide Vision HD Camera         | 1         | 0.83%   |
| Realtek HP Truevision HD                 | 1         | 0.83%   |
| Realtek HD WebCam                        | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 38.46%  |
| Shenzhen Goodix Technology | 9         | 34.62%  |
| Upek                       | 5         | 19.23%  |
| Synaptics                  | 1         | 3.85%   |
| Elan Microelectronics      | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 6         | 23.08%  |
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 19.23%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 11.54%  |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 11.54%  |
| Validity Sensors VFS491                                | 2         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 7.69%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 3.85%   |
| Elan ELAN:Fingerprint                                  | 1         | 3.85%   |

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
| 0     | 91        | 65.47%  |
| 1     | 40        | 28.78%  |
| 2     | 8         | 5.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 26        | 46.43%  |
| Graphics card         | 15        | 26.79%  |
| Multimedia controller | 6         | 10.71%  |
| Chipcard              | 5         | 8.93%   |
| Sound                 | 2         | 3.57%   |
| Storage               | 1         | 1.79%   |
| Camera                | 1         | 1.79%   |


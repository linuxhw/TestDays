Deepin - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Deepin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Lenovo    | ZhaoYangCF4620Z-A123 590... | [6f716961de](https://linux-hardware.org/?probe=6f716961de) | Jun 29, 2021 |
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
| Unknown   | Unknown                     | [9ddedfd3c9](https://linux-hardware.org/?probe=9ddedfd3c9) | Feb 13, 2021 |
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
| Chuwi     | AeroBook                    | [5889780485](https://linux-hardware.org/?probe=5889780485) | Jun 01, 2020 |
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
| Toshiba   | Satellite L75-C             | [ac2b91127b](https://linux-hardware.org/?probe=ac2b91127b) | Jan 03, 2020 |
| Toshiba   | Satellite L75-C             | [2b66fb3c5e](https://linux-hardware.org/?probe=2b66fb3c5e) | Jan 03, 2020 |
| Toshiba   | Satellite C850-1H6          | [a0ffb29c6c](https://linux-hardware.org/?probe=a0ffb29c6c) | Dec 18, 2019 |
| Lenovo    | Unknown                     | [10ab399874](https://linux-hardware.org/?probe=10ab399874) | Dec 14, 2019 |
| Lenovo    | IdeaPad S145-15IWL 81S9     | [d1b18250b9](https://linux-hardware.org/?probe=d1b18250b9) | Dec 04, 2019 |
| bq        | Tesla2 W10                  | [27f3692e24](https://linux-hardware.org/?probe=27f3692e24) | Dec 04, 2019 |
| bq        | Tesla2 W10                  | [4c37070709](https://linux-hardware.org/?probe=4c37070709) | Dec 04, 2019 |
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

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 4.15.0-30deepin-generic | 32        | 29.63%  |
| 5.4.50-amd64-desktop    | 16        | 14.81%  |
| 4.15.0-29deepin-generic | 12        | 11.11%  |
| 5.4.70-amd64-desktop    | 9         | 8.33%   |
| 5.10.60-amd64-desktop   | 7         | 6.48%   |
| 5.7.7-amd64-desktop     | 4         | 3.7%    |
| 5.10.41-amd64-desktop   | 4         | 3.7%    |
| 5.10.29-amd64-desktop   | 4         | 3.7%    |
| 5.3.0-3-amd64           | 3         | 2.78%   |
| 5.15.1-amd64-desktop    | 3         | 2.78%   |
| 5.10.50-amd64-desktop   | 2         | 1.85%   |
| 5.10.5-amd64-desktop+   | 2         | 1.85%   |
| 5.10.18-amd64-desktop   | 2         | 1.85%   |
| 5.8.14-amd64-desktop    | 1         | 0.93%   |
| 5.6.14-050614-generic   | 1         | 0.93%   |
| 5.6.12-xanmod1          | 1         | 0.93%   |
| 5.5.4-xanmod3           | 1         | 0.93%   |
| 5.3.8-xanmod6           | 1         | 0.93%   |
| 5.10.36-amd64-desktop   | 1         | 0.93%   |
| 5.1.0-050100rc2-generic | 1         | 0.93%   |
| 4.15.0-135-generic      | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15.0  | 45        | 41.67%  |
| 5.4.50  | 16        | 14.81%  |
| 5.4.70  | 9         | 8.33%   |
| 5.10.60 | 7         | 6.48%   |
| 5.7.7   | 4         | 3.7%    |
| 5.10.41 | 4         | 3.7%    |
| 5.10.29 | 4         | 3.7%    |
| 5.3.0   | 3         | 2.78%   |
| 5.15.1  | 3         | 2.78%   |
| 5.10.50 | 2         | 1.85%   |
| 5.10.5  | 2         | 1.85%   |
| 5.10.18 | 2         | 1.85%   |
| 5.8.14  | 1         | 0.93%   |
| 5.6.14  | 1         | 0.93%   |
| 5.6.12  | 1         | 0.93%   |
| 5.5.4   | 1         | 0.93%   |
| 5.3.8   | 1         | 0.93%   |
| 5.10.36 | 1         | 0.93%   |
| 5.1.0   | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15    | 45        | 41.67%  |
| 5.4     | 25        | 23.15%  |
| 5.10    | 22        | 20.37%  |
| 5.7     | 4         | 3.7%    |
| 5.3     | 4         | 3.7%    |
| 5.15    | 3         | 2.78%   |
| 5.6     | 2         | 1.85%   |
| 5.8     | 1         | 0.93%   |
| 5.5     | 1         | 0.93%   |
| 5.1     | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 106       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Deepin  | 86        | 81.13%  |
| Unknown | 19        | 17.92%  |
| KDE     | 1         | 0.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 106       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 49.07%  |
| TDM     | 39        | 36.11%  |
| LightDM | 16        | 14.81%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 29        | 27.36%  |
| en_US   | 20        | 18.87%  |
| pt_BR   | 14        | 13.21%  |
| zh_CN   | 11        | 10.38%  |
| es_ES   | 11        | 10.38%  |
| de_DE   | 8         | 7.55%   |
| ru_RU   | 3         | 2.83%   |
| tr_TR   | 2         | 1.89%   |
| pl_PL   | 2         | 1.89%   |
| it_IT   | 2         | 1.89%   |
| sv_SE   | 1         | 0.94%   |
| ja_JP   | 1         | 0.94%   |
| fr_FR   | 1         | 0.94%   |
| en_GB   | 1         | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 63        | 58.88%  |
| BIOS | 44        | 41.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 92        | 86.79%  |
| Unknown | 14        | 13.21%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 52        | 48.6%   |
| GPT     | 42        | 39.25%  |
| MBR     | 13        | 12.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 94        | 88.68%  |
| Yes       | 12        | 11.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 69.81%  |
| Yes       | 32        | 30.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 25.47%  |
| Hewlett-Packard     | 18        | 16.98%  |
| Acer                | 12        | 11.32%  |
| Dell                | 10        | 9.43%   |
| Samsung Electronics | 7         | 6.6%    |
| ASUSTek Computer    | 6         | 5.66%   |
| Toshiba             | 4         | 3.77%   |
| Sony                | 4         | 3.77%   |
| HUAWEI              | 4         | 3.77%   |
| Unknown             | 3         | 2.83%   |
| Google              | 2         | 1.89%   |
| Timi                | 1         | 0.94%   |
| Standard            | 1         | 0.94%   |
| Positivo            | 1         | 0.94%   |
| Microtech           | 1         | 0.94%   |
| Gateway             | 1         | 0.94%   |
| Fujitsu             | 1         | 0.94%   |
| Chuwi               | 1         | 0.94%   |
| CCE                 | 1         | 0.94%   |
| bq                  | 1         | 0.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 5         | 4.72%   |
| Samsung 340XAA/350XAA/550XAA                      | 2         | 1.89%   |
| Lenovo IdeaPad 120S-11IAP 81A4                    | 2         | 1.89%   |
| HP Pavilion Notebook                              | 2         | 1.89%   |
| HP Pavilion 15                                    | 2         | 1.89%   |
| HP ENVY 15                                        | 2         | 1.89%   |
| Acer Nitro AN515-54                               | 2         | 1.89%   |
| Toshiba Satellite L75-C                           | 1         | 0.94%   |
| Toshiba Satellite E55t-A                          | 1         | 0.94%   |
| Toshiba Satellite C850D-11K                       | 1         | 0.94%   |
| Toshiba Satellite C850-1H6                        | 1         | 0.94%   |
| Timi TM1701                                       | 1         | 0.94%   |
| Standard MB45II/MB45IN                            | 1         | 0.94%   |
| Sony VPCYB25AB                                    | 1         | 0.94%   |
| Sony VGN-NS140D                                   | 1         | 0.94%   |
| Sony SVF14A190X                                   | 1         | 0.94%   |
| Sony SVE14135CXP                                  | 1         | 0.94%   |
| Samsung 800G5M/800G5W                             | 1         | 0.94%   |
| Samsung 550P5C/550P7C                             | 1         | 0.94%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.94%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 1         | 0.94%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.94%   |
| Positivo C14CU51                                  | 1         | 0.94%   |
| Microtech ebookPro                                | 1         | 0.94%   |
| Lenovo ZhaoYangCF4620Z-A123 59082537              | 1         | 0.94%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN                 | 1         | 0.94%   |
| Lenovo XiaoXin-15ARE 2020 81YR                    | 1         | 0.94%   |
| Lenovo V310-15ISK 80SY                            | 1         | 0.94%   |
| Lenovo ThinkPad T420 4236CU8                      | 1         | 0.94%   |
| Lenovo ThinkPad T420 4180M8P                      | 1         | 0.94%   |
| Lenovo ThinkPad L512 44444NG                      | 1         | 0.94%   |
| Lenovo ThinkPad L412 0585AC3                      | 1         | 0.94%   |
| Lenovo ThinkPad E585 20KV0010US                   | 1         | 0.94%   |
| Lenovo ThinkPad E450c 20EHA00NCD                  | 1         | 0.94%   |
| Lenovo ThinkPad E14 20RA0058VA                    | 1         | 0.94%   |
| Lenovo ThinkBook 14 G2 ARE R7 8 20VF              | 1         | 0.94%   |
| Lenovo ThinkBook 13s-IWL 20R9                     | 1         | 0.94%   |
| Lenovo Legion Y7000 2020 82AV                     | 1         | 0.94%   |
| Lenovo Legion R9000K2021H 82N6                    | 1         | 0.94%   |
| Lenovo IdeaPad S145-15IWL 81S9                    | 1         | 0.94%   |
| Lenovo IdeaPad S145-15API 81UT                    | 1         | 0.94%   |
| Lenovo IdeaPad 320-15IKB 80YH                     | 1         | 0.94%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 0.94%   |
| Lenovo IdeaPad 3 14ARE05 81W3                     | 1         | 0.94%   |
| Lenovo IdeaPad 110-14IBR 80UJ                     | 1         | 0.94%   |
| Lenovo G50-80 80L0                                | 1         | 0.94%   |
| Lenovo G50-70 20351                               | 1         | 0.94%   |
| Lenovo G400s VILG1                                | 1         | 0.94%   |
| HUAWEI NBLK-WAX9X                                 | 1         | 0.94%   |
| HUAWEI HN-WX9X                                    | 1         | 0.94%   |
| HUAWEI HLYL-WXX9                                  | 1         | 0.94%   |
| HUAWEI HLY-WX9XX                                  | 1         | 0.94%   |
| HP ZHAN 66 Pro G1                                 | 1         | 0.94%   |
| HP Pavilion Laptop 14-bf0xx                       | 1         | 0.94%   |
| HP Laptop 15-bs0xx                                | 1         | 0.94%   |
| HP Laptop 14-ck0xxx                               | 1         | 0.94%   |
| HP G42                                            | 1         | 0.94%   |
| HP EliteBook 8570w                                | 1         | 0.94%   |
| HP EliteBook 8570p                                | 1         | 0.94%   |
| HP EliteBook 840 G2                               | 1         | 0.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo IdeaPad              | 8         | 7.55%   |
| Lenovo ThinkPad             | 7         | 6.6%    |
| Dell Inspiron               | 7         | 6.6%    |
| Acer Aspire                 | 7         | 6.6%    |
| HP Pavilion                 | 5         | 4.72%   |
| HP EliteBook                | 5         | 4.72%   |
| Unknown                     | 5         | 4.72%   |
| Toshiba Satellite           | 4         | 3.77%   |
| Acer Nitro                  | 3         | 2.83%   |
| Samsung 340XAA              | 2         | 1.89%   |
| Lenovo ThinkBook            | 2         | 1.89%   |
| Lenovo Legion               | 2         | 1.89%   |
| HP Laptop                   | 2         | 1.89%   |
| HP ENVY                     | 2         | 1.89%   |
| Dell Latitude               | 2         | 1.89%   |
| Timi TM1701                 | 1         | 0.94%   |
| Standard MB45II             | 1         | 0.94%   |
| Sony VPCYB25AB              | 1         | 0.94%   |
| Sony VGN-NS140D             | 1         | 0.94%   |
| Sony SVF14A190X             | 1         | 0.94%   |
| Sony SVE14135CXP            | 1         | 0.94%   |
| Samsung 800G5M              | 1         | 0.94%   |
| Samsung 550P5C              | 1         | 0.94%   |
| Samsung 500R4K              | 1         | 0.94%   |
| Samsung 300E4A              | 1         | 0.94%   |
| Samsung 270E5J              | 1         | 0.94%   |
| Positivo C14CU51            | 1         | 0.94%   |
| Microtech ebookPro          | 1         | 0.94%   |
| Lenovo ZhaoYangCF4620Z-A123 | 1         | 0.94%   |
| Lenovo XiaoXinAir-14ARE     | 1         | 0.94%   |
| Lenovo XiaoXin-15ARE        | 1         | 0.94%   |
| Lenovo V310-15ISK           | 1         | 0.94%   |
| Lenovo G50-80               | 1         | 0.94%   |
| Lenovo G50-70               | 1         | 0.94%   |
| Lenovo G400s                | 1         | 0.94%   |
| HUAWEI NBLK-WAX9X           | 1         | 0.94%   |
| HUAWEI HN-WX9X              | 1         | 0.94%   |
| HUAWEI HLYL-WXX9            | 1         | 0.94%   |
| HUAWEI HLY-WX9XX            | 1         | 0.94%   |
| HP ZHAN                     | 1         | 0.94%   |
| HP G42                      | 1         | 0.94%   |
| HP 250                      | 1         | 0.94%   |
| Google Edgar                | 1         | 0.94%   |
| Google Akemi                | 1         | 0.94%   |
| Gateway NE56R               | 1         | 0.94%   |
| Fujitsu FARQ06012Z          | 1         | 0.94%   |
| Dell XPS                    | 1         | 0.94%   |
| Chuwi AeroBook              | 1         | 0.94%   |
| CCE Capella                 | 1         | 0.94%   |
| bq Tesla2                   | 1         | 0.94%   |
| ASUS X406UAR                | 1         | 0.94%   |
| ASUS VivoBook               | 1         | 0.94%   |
| ASUS T100TAF                | 1         | 0.94%   |
| ASUS N46VM                  | 1         | 0.94%   |
| ASUS K501LX                 | 1         | 0.94%   |
| ASUS ASUS                   | 1         | 0.94%   |
| Acer Swift                  | 1         | 0.94%   |
| Acer P5WE0                  | 1         | 0.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 20        | 18.87%  |
| 2020    | 14        | 13.21%  |
| 2018    | 11        | 10.38%  |
| 2015    | 10        | 9.43%   |
| 2017    | 9         | 8.49%   |
| 2013    | 9         | 8.49%   |
| 2012    | 7         | 6.6%    |
| 2021    | 6         | 5.66%   |
| 2016    | 6         | 5.66%   |
| 2011    | 4         | 3.77%   |
| 2010    | 3         | 2.83%   |
| 2009    | 3         | 2.83%   |
| 2014    | 2         | 1.89%   |
| 2008    | 1         | 0.94%   |
| Unknown | 1         | 0.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 106       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 103       | 97.17%  |
| Enabled  | 3         | 2.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 98.11%  |
| Yes  | 2         | 1.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 39        | 36.79%  |
| 8.01-16.0   | 26        | 24.53%  |
| 3.01-4.0    | 23        | 21.7%   |
| 16.01-24.0  | 9         | 8.49%   |
| 1.01-2.0    | 4         | 3.77%   |
| 32.01-64.0  | 3         | 2.83%   |
| 2.01-3.0    | 1         | 0.94%   |
| 64.01-256.0 | 1         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 37        | 33.94%  |
| 1.01-2.0  | 36        | 33.03%  |
| 3.01-4.0  | 16        | 14.68%  |
| 4.01-8.0  | 10        | 9.17%   |
| 0.51-1.0  | 8         | 7.34%   |
| 8.01-16.0 | 2         | 1.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 78        | 72.9%   |
| 2      | 28        | 26.17%  |
| 3      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 59.43%  |
| Yes       | 43        | 40.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 77.36%  |
| No        | 24        | 22.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 98.11%  |
| No        | 2         | 1.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 80.19%  |
| No        | 21        | 19.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| Brazil                | 30        | 28.04%  |
| China                 | 13        | 12.15%  |
| Germany               | 9         | 8.41%   |
| Spain                 | 5         | 4.67%   |
| USA                   | 4         | 3.74%   |
| Turkey                | 4         | 3.74%   |
| Indonesia             | 4         | 3.74%   |
| Poland                | 3         | 2.8%    |
| Chile                 | 3         | 2.8%    |
| Russia                | 2         | 1.87%   |
| Panama                | 2         | 1.87%   |
| Japan                 | 2         | 1.87%   |
| Italy                 | 2         | 1.87%   |
| Canada                | 2         | 1.87%   |
| Venezuela             | 1         | 0.93%   |
| Tunisia               | 1         | 0.93%   |
| Sweden                | 1         | 0.93%   |
| South Africa          | 1         | 0.93%   |
| Singapore             | 1         | 0.93%   |
| Serbia                | 1         | 0.93%   |
| Sao Tome and Principe | 1         | 0.93%   |
| Portugal              | 1         | 0.93%   |
| Pakistan              | 1         | 0.93%   |
| Mexico                | 1         | 0.93%   |
| Iran                  | 1         | 0.93%   |
| India                 | 1         | 0.93%   |
| Greece                | 1         | 0.93%   |
| France                | 1         | 0.93%   |
| Ecuador               | 1         | 0.93%   |
| Czechia               | 1         | 0.93%   |
| Cuba                  | 1         | 0.93%   |
| Colombia              | 1         | 0.93%   |
| Belarus               | 1         | 0.93%   |
| Bangladesh            | 1         | 0.93%   |
| Austria               | 1         | 0.93%   |
| Argentina             | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| São Paulo            | 2         | 1.85%   |
| Surabaya              | 2         | 1.85%   |
| Londrina              | 2         | 1.85%   |
| Istanbul              | 2         | 1.85%   |
| Hangzhou              | 2         | 1.85%   |
| David                 | 2         | 1.85%   |
| Curitiba              | 2         | 1.85%   |
| Zieleniewo            | 1         | 0.93%   |
| Villa Ballester       | 1         | 0.93%   |
| Vieiras               | 1         | 0.93%   |
| Valdenoches           | 1         | 0.93%   |
| Uberlândia           | 1         | 0.93%   |
| Uberl??ndia           | 1         | 0.93%   |
| Tunis                 | 1         | 0.93%   |
| Tres Rios             | 1         | 0.93%   |
| Tomsk                 | 1         | 0.93%   |
| Tianjin               | 1         | 0.93%   |
| Teknaf                | 1         | 0.93%   |
| Tehrān               | 1         | 0.93%   |
| Taiyuan               | 1         | 0.93%   |
| São Tomé            | 1         | 0.93%   |
| São Carlos           | 1         | 0.93%   |
| São Bento do Sul     | 1         | 0.93%   |
| Suzano                | 1         | 0.93%   |
| Sumaré               | 1         | 0.93%   |
| Srednyaya Akhtuba     | 1         | 0.93%   |
| Sobreda               | 1         | 0.93%   |
| Sleman                | 1         | 0.93%   |
| Singapore             | 1         | 0.93%   |
| Shanghai              | 1         | 0.93%   |
| Shahekou              | 1         | 0.93%   |
| Sehnde                | 1         | 0.93%   |
| Santiago              | 1         | 0.93%   |
| San Juan de Col??n    | 1         | 0.93%   |
| Saitama               | 1         | 0.93%   |
| Rzeszów              | 1         | 0.93%   |
| Rotenburg             | 1         | 0.93%   |
| Rio de Janeiro        | 1         | 0.93%   |
| Ravensburg            | 1         | 0.93%   |
| Portoviejo            | 1         | 0.93%   |
| Porto Velho           | 1         | 0.93%   |
| Pomigliano d'Arco     | 1         | 0.93%   |
| Pittsburgh            | 1         | 0.93%   |
| Pilsen                | 1         | 0.93%   |
| Petrópolis           | 1         | 0.93%   |
| Oxford                | 1         | 0.93%   |
| Osasco                | 1         | 0.93%   |
| Niagara Falls         | 1         | 0.93%   |
| Nanyang               | 1         | 0.93%   |
| Nanning               | 1         | 0.93%   |
| Málaga               | 1         | 0.93%   |
| Modena                | 1         | 0.93%   |
| Minsk                 | 1         | 0.93%   |
| Miesbach              | 1         | 0.93%   |
| Malmo                 | 1         | 0.93%   |
| Maipu                 | 1         | 0.93%   |
| Madrid                | 1         | 0.93%   |
| Ludwigshafen am Rhein | 1         | 0.93%   |
| Loudi                 | 1         | 0.93%   |
| Los Angeles           | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 20        | 23     | 15.15%  |
| WDC                            | 18        | 21     | 13.64%  |
| Samsung Electronics            | 14        | 16     | 10.61%  |
| Toshiba                        | 11        | 12     | 8.33%   |
| Unknown                        | 10        | 10     | 7.58%   |
| SanDisk                        | 9         | 9      | 6.82%   |
| Kingston                       | 7         | 8      | 5.3%    |
| SK Hynix                       | 6         | 6      | 4.55%   |
| HGST                           | 5         | 5      | 3.79%   |
| Micron Technology              | 4         | 5      | 3.03%   |
| Hitachi                        | 4         | 4      | 3.03%   |
| LITEON                         | 3         | 3      | 2.27%   |
| Intel                          | 3         | 4      | 2.27%   |
| Crucial                        | 3         | 3      | 2.27%   |
| V-GeN                          | 1         | 1      | 0.76%   |
| Transcend                      | 1         | 1      | 0.76%   |
| SPCC                           | 1         | 1      | 0.76%   |
| Solid State Storage Technology | 1         | 1      | 0.76%   |
| Silicon Motion                 | 1         | 1      | 0.76%   |
| OEM                            | 1         | 1      | 0.76%   |
| OCZ                            | 1         | 1      | 0.76%   |
| Netac                          | 1         | 1      | 0.76%   |
| Microtech                      | 1         | 1      | 0.76%   |
| KingSpec                       | 1         | 1      | 0.76%   |
| JMicron                        | 1         | 1      | 0.76%   |
| Intenso                        | 1         | 1      | 0.76%   |
| Fujitsu                        | 1         | 2      | 0.76%   |
| China                          | 1         | 1      | 0.76%   |
| A-DATA Technology              | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 6         | 4.41%   |
| Toshiba MQ01ABF050 500GB                  | 4         | 2.94%   |
| Kingston SA400S37240G 240GB SSD           | 4         | 2.94%   |
| Toshiba MQ01ABD100 1TB                    | 3         | 2.21%   |
| WDC WD5000LPCX-24VHAT0 500GB              | 2         | 1.47%   |
| Unknown MMC Card                          | 2         | 1.47%   |
| Seagate ST9320325AS 320GB                 | 2         | 1.47%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 2         | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 1.47%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 1.47%   |
| HGST HTS545050A7E680 500GB                | 2         | 1.47%   |
| Crucial CT240BX500SSD1 240GB              | 2         | 1.47%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD          | 1         | 0.74%   |
| WDC WDS120G2G0A-00JH30 120GB SSD          | 1         | 0.74%   |
| WDC WD7500BPVT-24HXZT3 752GB              | 1         | 0.74%   |
| WDC WD5000LPZX-75Z10T0 500GB              | 1         | 0.74%   |
| WDC WD5000LPVX-80V0TT0 500GB              | 1         | 0.74%   |
| WDC WD5000LPVX-08V0TT6 500GB              | 1         | 0.74%   |
| WDC WD5000LPCX-24C6HT0 500GB              | 1         | 0.74%   |
| WDC WD3200BEVT-22ZCT0 320GB               | 1         | 0.74%   |
| WDC WD3200BEVT-08A23T1 320GB              | 1         | 0.74%   |
| WDC WD10SPZX-35Z10T0 1TB                  | 1         | 0.74%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 0.74%   |
| WDC WD10SPZX-08Z10 1TB                    | 1         | 0.74%   |
| WDC WD10JPVX-60JC3T1 1TB                  | 1         | 0.74%   |
| WDC WD10JPVX-60JC3T0 1TB                  | 1         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.74%   |
| WDC WD10JPCX-24UE4T0 1TB                  | 1         | 0.74%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB      | 1         | 0.74%   |
| WDC PC SN720 SDAPNTW-512G-1127 512GB      | 1         | 0.74%   |
| V-GeN V-GEN10SM19AR120SDK 120GB SSD       | 1         | 0.74%   |
| Unknown SSO256GTLC9-SB3-4L 256GB SSD      | 1         | 0.74%   |
| Unknown MMC Card  32GB                    | 1         | 0.74%   |
| Unknown MMC Card  16GB                    | 1         | 0.74%   |
| Unknown MMC Card  128GB                   | 1         | 0.74%   |
| Unknown MBG4GC  32GB                      | 1         | 0.74%   |
| Unknown HBG4a2  32GB                      | 1         | 0.74%   |
| Unknown APPSD  272GB                      | 1         | 0.74%   |
| Unknown 032GE4  32GB                      | 1         | 0.74%   |
| Transcend TS120GSSD220S 120GB             | 1         | 0.74%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 0.74%   |
| Toshiba MK5065GSXN 500GB                  | 1         | 0.74%   |
| Toshiba MK5065GSX 500GB                   | 1         | 0.74%   |
| Toshiba KBG40ZMT128G MEMORY 128GB         | 1         | 0.74%   |
| SPCC M.2 SSD 256GB                        | 1         | 0.74%   |
| Solid State Storage NVMe SSD Drive 256GB  | 1         | 0.74%   |
| SK Hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.74%   |
| SK Hynix NVMe SSD Drive 512GB             | 1         | 0.74%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD     | 1         | 0.74%   |
| SK Hynix HFS128G39MNC-2300A 128GB SSD     | 1         | 0.74%   |
| SK Hynix HFM512GDJTNI-82A0A 512GB         | 1         | 0.74%   |
| SK Hynix HFM512GD3JX013N 512GB            | 1         | 0.74%   |
| Silicon Motion S2000 2TB                  | 1         | 0.74%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 0.74%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 0.74%   |
| Seagate ST500LM034-2GH17A 500GB           | 1         | 0.74%   |
| Seagate ST2000LM007-1R8174 2TB            | 1         | 0.74%   |
| Seagate ST1000LM014-SSHD-8GB              | 1         | 0.74%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB       | 1         | 0.74%   |
| Seagate ST1000LM014-1EJ164 1TB            | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 33.33%  |
| WDC                 | 16        | 17     | 28.07%  |
| Toshiba             | 10        | 11     | 17.54%  |
| HGST                | 5         | 5      | 8.77%   |
| Hitachi             | 4         | 4      | 7.02%   |
| Samsung Electronics | 1         | 1      | 1.75%   |
| OEM                 | 1         | 1      | 1.75%   |
| Fujitsu             | 1         | 2      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 8      | 19.51%  |
| Kingston            | 7         | 8      | 17.07%  |
| Samsung Electronics | 5         | 6      | 12.2%   |
| WDC                 | 2         | 2      | 4.88%   |
| SK Hynix            | 2         | 2      | 4.88%   |
| LITEON              | 2         | 2      | 4.88%   |
| Crucial             | 2         | 2      | 4.88%   |
| V-GeN               | 1         | 1      | 2.44%   |
| Unknown             | 1         | 1      | 2.44%   |
| Transcend           | 1         | 1      | 2.44%   |
| SPCC                | 1         | 1      | 2.44%   |
| OCZ                 | 1         | 1      | 2.44%   |
| Netac               | 1         | 1      | 2.44%   |
| Microtech           | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| KingSpec            | 1         | 1      | 2.44%   |
| JMicron             | 1         | 1      | 2.44%   |
| Intenso             | 1         | 1      | 2.44%   |
| Intel               | 1         | 2      | 2.44%   |
| China               | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 56        | 63     | 43.75%  |
| SSD     | 38        | 44     | 29.69%  |
| NVMe    | 24        | 27     | 18.75%  |
| MMC     | 9         | 10     | 7.03%   |
| Unknown | 1         | 1      | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 82        | 103    | 68.91%  |
| NVMe | 24        | 27     | 20.17%  |
| MMC  | 9         | 10     | 7.56%   |
| SAS  | 4         | 5      | 3.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 73     | 64.44%  |
| 0.51-1.0   | 31        | 33     | 34.44%  |
| 1.01-2.0   | 1         | 1      | 1.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 34        | 31.19%  |
| 101-250        | 31        | 28.44%  |
| 501-1000       | 24        | 22.02%  |
| 1001-2000      | 8         | 7.34%   |
| More than 3000 | 4         | 3.67%   |
| 21-50          | 4         | 3.67%   |
| 51-100         | 2         | 1.83%   |
| Unknown        | 2         | 1.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 27        | 25%     |
| 1-20      | 21        | 19.44%  |
| 51-100    | 18        | 16.67%  |
| 101-250   | 17        | 15.74%  |
| 251-500   | 13        | 12.04%  |
| 501-1000  | 6         | 5.56%   |
| 2001-3000 | 2         | 1.85%   |
| 1001-2000 | 2         | 1.85%   |
| Unknown   | 2         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB          | 2         | 2      | 22.22%  |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD032 320GB           | 1         | 1      | 11.11%  |
| Samsung Electronics HM250HI 250GB  | 1         | 1      | 11.11%  |
| OCZ VERTEX4 256GB SSD              | 1         | 1      | 11.11%  |
| Intenso lntenso SSD Sata III 240GB | 1         | 1      | 11.11%  |
| Hitachi HTS543225L9A300 250GB      | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| OCZ                 | 1         | 1      | 11.11%  |
| Intenso             | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 28.57%  |
| Seagate             | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 77.78%  |
| SSD  | 2         | 2      | 22.22%  |

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
| Detected | 62        | 86     | 55.36%  |
| Works    | 40        | 49     | 35.71%  |
| Malfunc  | 9         | 9      | 8.04%   |
| Failed   | 1         | 1      | 0.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 81        | 69.83%  |
| AMD                            | 10        | 8.62%   |
| Samsung Electronics            | 8         | 6.9%    |
| SK Hynix                       | 4         | 3.45%   |
| Micron Technology              | 3         | 2.59%   |
| Sandisk                        | 2         | 1.72%   |
| Zhaoxin                        | 1         | 0.86%   |
| Solid State Storage Technology | 1         | 0.86%   |
| Silicon Motion                 | 1         | 0.86%   |
| Realtek Semiconductor          | 1         | 0.86%   |
| Micron/Crucial Technology      | 1         | 0.86%   |
| Lite-On Technology             | 1         | 0.86%   |
| KIOXIA                         | 1         | 0.86%   |
| JMicron Technology             | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 14        | 11.67%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 12        | 10%     |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 9.17%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 7.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 8         | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 4.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 4.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 3.33%   |
| Micron Non-Volatile memory controller                                                  | 3         | 2.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.5%    |
| SK Hynix BC511                                                                         | 2         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 1.67%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 1.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 1.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 1.67%   |
| Zhaoxin ZX-100/ZX-200/ZX-E StorX AHCI Controller                                       | 1         | 0.83%   |
| Solid State Storage Non-Volatile memory controller                                     | 1         | 0.83%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 0.83%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.83%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.83%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.83%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.83%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 0.83%   |
| Micron/Crucial Non-Volatile memory controller                                          | 1         | 0.83%   |
| Lite-On Non-Volatile memory controller                                                 | 1         | 0.83%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 0.83%   |
| JMicron JMB368 IDE controller                                                          | 1         | 0.83%   |
| Intel SSD 600P Series                                                                  | 1         | 0.83%   |
| Intel NVMe Optane Memory Series                                                        | 1         | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 0.83%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.83%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 85        | 72.65%  |
| NVMe | 24        | 20.51%  |
| RAID | 4         | 3.42%   |
| IDE  | 4         | 3.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 88        | 83.02%  |
| AMD          | 17        | 16.04%  |
| CentaurHauls | 1         | 0.94%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 4.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 3.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 3.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.83%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.89%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.89%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.89%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 1.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.89%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.89%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.89%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.89%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.89%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.89%   |
| AMD Ryzen 5 4600U with Radeon Graphics        | 2         | 1.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.89%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.94%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.94%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.94%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.94%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.94%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.94%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.94%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.94%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.94%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.94%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.94%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.94%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.94%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 0.94%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.94%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.94%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 0.94%   |
| Intel Core i5-10200H CPU @ 2.40GHz            | 1         | 0.94%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 0.94%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 0.94%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 0.94%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 0.94%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 0.94%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 0.94%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 0.94%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 1         | 0.94%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 1         | 0.94%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 0.94%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 0.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 0.94%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 0.94%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 1         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34        | 32.08%  |
| Intel Core i7           | 24        | 22.64%  |
| Intel Core i3           | 9         | 8.49%   |
| Intel Celeron           | 7         | 6.6%    |
| AMD Ryzen 5             | 6         | 5.66%   |
| AMD Ryzen 7             | 5         | 4.72%   |
| Intel Pentium Dual-Core | 3         | 2.83%   |
| Intel Core 2 Duo        | 3         | 2.83%   |
| Intel Atom              | 3         | 2.83%   |
| Intel Pentium           | 2         | 1.89%   |
| AMD Ryzen 3             | 2         | 1.89%   |
| AMD A10                 | 2         | 1.89%   |
| Other                   | 1         | 0.94%   |
| Intel Pentium Silver    | 1         | 0.94%   |
| Intel Core m3           | 1         | 0.94%   |
| Intel Core i9           | 1         | 0.94%   |
| AMD E1                  | 1         | 0.94%   |
| AMD E                   | 1         | 0.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 64        | 60.38%  |
| 4      | 33        | 31.13%  |
| 8      | 4         | 3.77%   |
| 6      | 4         | 3.77%   |
| 1      | 1         | 0.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 106       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 82        | 77.36%  |
| 1      | 24        | 22.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 95        | 89.62%  |
| Unknown        | 11        | 10.38%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 21.5%   |
| 0x306a9    | 10        | 9.35%   |
| 0x40651    | 9         | 8.41%   |
| 0x806e9    | 7         | 6.54%   |
| 0x806ec    | 6         | 5.61%   |
| 0x206a7    | 6         | 5.61%   |
| 0x406e3    | 5         | 4.67%   |
| 0x306d4    | 5         | 4.67%   |
| 0x906ea    | 3         | 2.8%    |
| 0x806ea    | 3         | 2.8%    |
| 0x1067a    | 3         | 2.8%    |
| 0x406c4    | 2         | 1.87%   |
| 0x20655    | 2         | 1.87%   |
| 0x08600106 | 2         | 1.87%   |
| 0x08600104 | 2         | 1.87%   |
| 0x08108109 | 2         | 1.87%   |
| 0x08108102 | 2         | 1.87%   |
| 0xa0652    | 1         | 0.93%   |
| 0x906e9    | 1         | 0.93%   |
| 0x706a1    | 1         | 0.93%   |
| 0x6fd      | 1         | 0.93%   |
| 0x406c3    | 1         | 0.93%   |
| 0x30678    | 1         | 0.93%   |
| 0x10676    | 1         | 0.93%   |
| 0x0a50000c | 1         | 0.93%   |
| 0x0a50000b | 1         | 0.93%   |
| 0x08600103 | 1         | 0.93%   |
| 0x08600102 | 1         | 0.93%   |
| 0x0810100b | 1         | 0.93%   |
| 0x06006115 | 1         | 0.93%   |
| 0x0500010d | 1         | 0.93%   |
| 0x05000029 | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 22.64%  |
| IvyBridge     | 13        | 12.26%  |
| Haswell       | 11        | 10.38%  |
| Broadwell     | 8         | 7.55%   |
| SandyBridge   | 7         | 6.6%    |
| Zen 2         | 6         | 5.66%   |
| Silvermont    | 6         | 5.66%   |
| Skylake       | 5         | 4.72%   |
| Penryn        | 5         | 4.72%   |
| Zen+          | 4         | 3.77%   |
| Westmere      | 3         | 2.83%   |
| Zen 3         | 2         | 1.89%   |
| Goldmont plus | 2         | 1.89%   |
| Goldmont      | 2         | 1.89%   |
| Excavator     | 2         | 1.89%   |
| Bobcat        | 2         | 1.89%   |
| Zen           | 1         | 0.94%   |
| Core          | 1         | 0.94%   |
| CometLake     | 1         | 0.94%   |
| Unknown       | 1         | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 86        | 59.72%  |
| Nvidia  | 35        | 24.31%  |
| AMD     | 22        | 15.28%  |
| Zhaoxin | 1         | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 8.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 7.53%   |
| Intel HD Graphics 620                                                                    | 8         | 5.48%   |
| Intel HD Graphics 5500                                                                   | 8         | 5.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 4.11%   |
| AMD Renoir                                                                               | 6         | 4.11%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 3.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.37%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 1.37%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.37%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.37%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1.37%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 1.37%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.37%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 1.37%   |
| Intel HD Graphics 500                                                                    | 2         | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.37%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.37%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 0.68%   |
| Nvidia TU117M                                                                            | 1         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.68%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.68%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.68%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.68%   |
| Nvidia GM108M [GeForce 845M]                                                             | 1         | 0.68%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.68%   |
| Nvidia GK208M [GeForce GT 735M]                                                          | 1         | 0.68%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.68%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.68%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.68%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.68%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.68%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.68%   |
| Intel HD Graphics 630                                                                    | 1         | 0.68%   |
| Intel HD Graphics 515                                                                    | 1         | 0.68%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.68%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 0.68%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1         | 0.68%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 0.68%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.68%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.68%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 1         | 0.68%   |
| AMD Cezanne                                                                              | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 46.23%  |
| Intel + Nvidia | 31        | 29.25%  |
| 1 x AMD        | 13        | 12.26%  |
| Intel + AMD    | 6         | 5.66%   |
| 1 x Nvidia     | 3         | 2.83%   |
| 2 x AMD        | 2         | 1.89%   |
| 1 x Zhaoxin    | 1         | 0.94%   |
| AMD + Nvidia   | 1         | 0.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 91        | 85.85%  |
| Proprietary | 12        | 11.32%  |
| Unknown     | 3         | 2.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 52.78%  |
| 1.01-2.0   | 26        | 24.07%  |
| 3.01-4.0   | 12        | 11.11%  |
| 0.01-0.5   | 9         | 8.33%   |
| 0.51-1.0   | 3         | 2.78%   |
| 5.01-6.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 23.15%  |
| BOE                     | 24        | 22.22%  |
| LG Display              | 14        | 12.96%  |
| Chimei Innolux          | 13        | 12.04%  |
| Samsung Electronics     | 12        | 11.11%  |
| Hewlett-Packard         | 3         | 2.78%   |
| Lenovo                  | 2         | 1.85%   |
| InfoVision              | 2         | 1.85%   |
| Chi Mei Optoelectronics | 2         | 1.85%   |
| ViewSonic               | 1         | 0.93%   |
| Sharp                   | 1         | 0.93%   |
| SAC                     | 1         | 0.93%   |
| PANDA                   | 1         | 0.93%   |
| Iiyama                  | 1         | 0.93%   |
| HB@                     | 1         | 0.93%   |
| HannStar                | 1         | 0.93%   |
| Goldstar                | 1         | 0.93%   |
| Dell                    | 1         | 0.93%   |
| CSO                     | 1         | 0.93%   |
| AOC                     | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 2.75%   |
| LG Display LCD Monitor LGD0468 1366x768 340x190mm 15.3-inch           | 2         | 1.83%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.83%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.83%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.83%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 2         | 1.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.83%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch             | 1         | 0.92%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC534B 1600x900 380x220mm 17.3-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 340x190mm 15.3-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                     | 1         | 0.92%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                 | 1         | 0.92%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.92%   |
| LG Display LP156WH1-TLA1 LGD6301 1366x768 344x194mm 15.5-inch         | 1         | 0.92%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0503 1366x768 340x190mm 15.3-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0259 1920x1080 350x190mm 15.7-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 0.92%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch               | 1         | 0.92%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 1         | 0.92%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch           | 1         | 0.92%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch          | 1         | 0.92%   |
| Iiyama PLE2607WS IVM5608 1920x1200 550x344mm 25.5-inch                | 1         | 0.92%   |
| Iiyama PL2773HD IVM6606 1920x1080 598x336mm 27.0-inch                 | 1         | 0.92%   |
| Hewlett-Packard N240 HPN340A 1920x1080 527x296mm 23.8-inch            | 1         | 0.92%   |
| Hewlett-Packard 24mq HPN366F 2560x1440 527x296mm 23.8-inch            | 1         | 0.92%   |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch             | 1         | 0.92%   |
| HB@ HBTV-32D03HD HB@0B01 1920x540 708x398mm 32.0-inch                 | 1         | 0.92%   |
| HannStar HSD140PHW1 HSD0583 1366x768 309x174mm 14.0-inch              | 1         | 0.92%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                  | 1         | 0.92%   |
| Dell SE2216H DELF070 1920x1080 476x268mm 21.5-inch                    | 1         | 0.92%   |
| CSO LCD Monitor CSO1600 2560x1600 340x220mm 15.9-inch                 | 1         | 0.92%   |
| Chimei Innolux P130ZDZ-EF1 CMN8201 2160x1440 275x183mm 13.0-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15B9 1920x1080 340x190mm 15.3-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN151B 1920x1080 344x193mm 15.5-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 1         | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 47        | 46.08%  |
| 1920x1080 (FHD) | 42        | 41.18%  |
| 1600x900 (HD+)  | 6         | 5.88%   |
| 3840x2160 (4K)  | 1         | 0.98%   |
| 2560x1600       | 1         | 0.98%   |
| 2560x1440 (QHD) | 1         | 0.98%   |
| 2160x1440       | 1         | 0.98%   |
| 1920x540        | 1         | 0.98%   |
| 1680x945        | 1         | 0.98%   |
| 1280x800 (WXGA) | 1         | 0.98%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 49        | 44.95%  |
| 13      | 21        | 19.27%  |
| 14      | 16        | 14.68%  |
| 23      | 4         | 3.67%   |
| 18      | 3         | 2.75%   |
| 17      | 3         | 2.75%   |
| 11      | 3         | 2.75%   |
| 21      | 2         | 1.83%   |
| 12      | 2         | 1.83%   |
| 32      | 1         | 0.92%   |
| 27      | 1         | 0.92%   |
| 25      | 1         | 0.92%   |
| 24      | 1         | 0.92%   |
| 16      | 1         | 0.92%   |
| Unknown | 1         | 0.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 79        | 74.53%  |
| 201-300     | 11        | 10.38%  |
| 501-600     | 5         | 4.72%   |
| 351-400     | 5         | 4.72%   |
| 401-500     | 4         | 3.77%   |
| 701-800     | 1         | 0.94%   |
| Unknown     | 1         | 0.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 95        | 95%     |
| 16/10 | 3         | 3%      |
| 3/2   | 2         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 49        | 44.95%  |
| 81-90          | 31        | 28.44%  |
| 71-80          | 6         | 5.5%    |
| 201-250        | 6         | 5.5%    |
| 51-60          | 3         | 2.75%   |
| 141-150        | 3         | 2.75%   |
| 61-70          | 2         | 1.83%   |
| 251-300        | 2         | 1.83%   |
| 121-130        | 2         | 1.83%   |
| 351-500        | 1         | 0.92%   |
| 301-350        | 1         | 0.92%   |
| 131-140        | 1         | 0.92%   |
| 111-120        | 1         | 0.92%   |
| Unknown        | 1         | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 50        | 47.17%  |
| 121-160 | 38        | 35.85%  |
| 51-100  | 9         | 8.49%   |
| 161-240 | 8         | 7.55%   |
| Unknown | 1         | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 91        | 85.85%  |
| 2     | 12        | 11.32%  |
| 0     | 2         | 1.89%   |
| 3     | 1         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 73        | 44.24%  |
| Intel                           | 42        | 25.45%  |
| Qualcomm Atheros                | 34        | 20.61%  |
| Broadcom                        | 4         | 2.42%   |
| Marvell Technology Group        | 3         | 1.82%   |
| Broadcom Limited                | 2         | 1.21%   |
| Xiaomi                          | 1         | 0.61%   |
| Ralink Technology               | 1         | 0.61%   |
| Qualcomm Atheros Communications | 1         | 0.61%   |
| OPPO Electronics                | 1         | 0.61%   |
| MEDIATEK                        | 1         | 0.61%   |
| Huawei Technologies             | 1         | 0.61%   |
| Hewlett-Packard                 | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 23.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 8.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 6.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 3.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.58%   |
| Intel Wireless 3165                                               | 5         | 2.58%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 2.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.06%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.55%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.55%   |
| Intel Wireless 7260                                               | 3         | 1.55%   |
| Intel Wireless 3160                                               | 3         | 1.55%   |
| Intel WiFi Link 5100                                              | 3         | 1.55%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 2         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.03%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.03%   |
| Intel Wireless 7265                                               | 2         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.03%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.52%   |
| Realtek 802.11ac NIC                                              | 1         | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.52%   |
| OPPO RMX3151                                                      | 1         | 0.52%   |
| MEDIATEK Network controller                                       | 1         | 0.52%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Intel Wireless 8260                                               | 1         | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.52%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 0.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.52%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.52%   |
| Intel Centrino Wireless-N 100                                     | 1         | 0.52%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.52%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 0.52%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 0.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.52%   |
| Huawei MAR-LX1A                                                   | 1         | 0.52%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 37.96%  |
| Qualcomm Atheros                | 34        | 31.48%  |
| Realtek Semiconductor           | 26        | 24.07%  |
| Broadcom Limited                | 2         | 1.85%   |
| Broadcom                        | 2         | 1.85%   |
| Ralink Technology               | 1         | 0.93%   |
| Qualcomm Atheros Communications | 1         | 0.93%   |
| MEDIATEK                        | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 11.11%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 6.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 6.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 4.63%   |
| Intel Wireless 3165                                            | 5         | 4.63%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 4.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 3.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.7%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 2.78%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.78%   |
| Intel Wireless 7260                                            | 3         | 2.78%   |
| Intel Wireless 3160                                            | 3         | 2.78%   |
| Intel WiFi Link 5100                                           | 3         | 2.78%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 2         | 1.85%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.85%   |
| Intel Wireless 7265                                            | 2         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.93%   |
| Realtek 802.11ac NIC                                           | 1         | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| MEDIATEK Network controller                                    | 1         | 0.93%   |
| Intel Wireless 8260                                            | 1         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.93%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.93%   |
| Intel Centrino Wireless-N 100                                  | 1         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.93%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.93%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 0.93%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                        | 1         | 0.93%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 75.58%  |
| Intel                    | 9         | 10.47%  |
| Qualcomm Atheros         | 3         | 3.49%   |
| Marvell Technology Group | 3         | 3.49%   |
| Broadcom                 | 2         | 2.33%   |
| Xiaomi                   | 1         | 1.16%   |
| OPPO Electronics         | 1         | 1.16%   |
| Huawei Technologies      | 1         | 1.16%   |
| Hewlett-Packard          | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 53.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 18.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 2.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.16%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.16%   |
| OPPO RMX3151                                                      | 1         | 1.16%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.16%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.16%   |
| Huawei MAR-LX1A                                                   | 1         | 1.16%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 104       | 55.61%  |
| Ethernet | 83        | 44.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 65.49%  |
| Ethernet | 49        | 34.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 79        | 74.53%  |
| 1     | 25        | 23.58%  |
| 0     | 2         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 101       | 94.39%  |
| Yes  | 6         | 5.61%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 36.47%  |
| Qualcomm Atheros Communications | 20        | 23.53%  |
| Realtek Semiconductor           | 10        | 11.76%  |
| Broadcom                        | 6         | 7.06%   |
| Foxconn / Hon Hai               | 5         | 5.88%   |
| Realtek                         | 4         | 4.71%   |
| Lite-On Technology              | 3         | 3.53%   |
| IMC Networks                    | 3         | 3.53%   |
| Toshiba                         | 1         | 1.18%   |
| Dell                            | 1         | 1.18%   |
| Cambridge Silicon Radio         | 1         | 1.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 21.18%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 15        | 17.65%  |
| Realtek Bluetooth Radio                                                             | 5         | 5.88%   |
| Intel AX200 Bluetooth                                                               | 5         | 5.88%   |
| Realtek Bluetooth Radio                                                             | 4         | 4.71%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 4.71%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 3.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 3.53%   |
| Intel AX201 Bluetooth                                                               | 3         | 3.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 2.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.35%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.35%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 2.35%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 2.35%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 2.35%   |
| Toshiba Bluetooth Radio                                                             | 1         | 1.18%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 1.18%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.18%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.18%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.18%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.18%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.18%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.18%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.18%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.18%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.18%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 85        | 74.56%  |
| AMD                 | 17        | 14.91%  |
| Nvidia              | 9         | 7.89%   |
| Zhaoxin             | 1         | 0.88%   |
| JMTek               | 1         | 0.88%   |
| Creative Technology | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 12%     |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 9.33%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 13        | 8.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 7.33%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 7.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 5.33%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 5.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 4.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2%      |
| Nvidia Audio device                                                                               | 2         | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.33%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.33%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.67%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 1         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.67%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.67%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.67%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                      | 1         | 0.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.67%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 28.79%  |
| SK Hynix            | 15        | 22.73%  |
| Unknown             | 9         | 13.64%  |
| Smart               | 4         | 6.06%   |
| Micron Technology   | 4         | 6.06%   |
| Kingston            | 4         | 6.06%   |
| Nanya Technology    | 3         | 4.55%   |
| Ramaxel Technology  | 2         | 3.03%   |
| A-DATA Technology   | 2         | 3.03%   |
| Unknown (07FB)      | 1         | 1.52%   |
| SMART Brazil        | 1         | 1.52%   |
| MTASE               | 1         | 1.52%   |
| Crucial             | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 2.86%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s         | 2         | 2.86%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 2         | 2.86%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8192MB Row Of Chips DDR4 2667MT/s  | 2         | 2.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.86%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1.43%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 1.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 1.43%   |
| Unknown RAM Module 2048MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.43%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 1.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1.43%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s                 | 1         | 1.43%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.43%   |
| Unknown (07FB) RAM GST32G08SCL196P-26 32GB SODIMM DDR4 2667MT/s  | 1         | 1.43%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Smart RAM SG564568FG8NWKF-Z1 2048MB SODIMM DDR2 800MT/s          | 1         | 1.43%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 1.43%   |
| SK Hynix RAM MPPS4GBPC1600 1.35 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.43%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.43%   |
| SK Hynix RAM HMA82GS6MFR8N-TF 16384MB SODIMM DDR4 2133MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s        | 1         | 1.43%   |
| SK Hynix RAM H9CCNNNBJTMLAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.43%   |
| SK Hynix RAM H9CCNNN8JTBLAR-NUD 2048MB LPDDR3 1600MT/s           | 1         | 1.43%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.43%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.43%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2666MT/s                   | 1         | 1.43%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.43%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 1         | 1.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.43%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB SODIMM LPDDR4 4266MT/s           | 1         | 1.43%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 1         | 1.43%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.43%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 1.43%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 1.43%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.43%   |
| MTASE RAM Module 8192MB SODIMM DDR4 2933MT/s                     | 1         | 1.43%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s          | 1         | 1.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 1         | 1.43%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 1.43%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s            | 1         | 1.43%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 1         | 1.43%   |
| Kingston RAM 99U5469-015.A00LF 2048MB SODIMM DDR3 1066MT/s       | 1         | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 28        | 50%     |
| DDR3   | 20        | 35.71%  |
| LPDDR3 | 4         | 7.14%   |
| LPDDR4 | 2         | 3.57%   |
| DDR2   | 2         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 87.72%  |
| Row Of Chips | 6         | 10.53%  |
| Unknown      | 1         | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 40.98%  |
| 8192  | 19        | 31.15%  |
| 2048  | 11        | 18.03%  |
| 16384 | 3         | 4.92%   |
| 1024  | 2         | 3.28%   |
| 32768 | 1         | 1.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 27.12%  |
| 2667    | 14        | 23.73%  |
| 3200    | 6         | 10.17%  |
| 2133    | 4         | 6.78%   |
| 2400    | 3         | 5.08%   |
| 1334    | 3         | 5.08%   |
| 1333    | 3         | 5.08%   |
| 3266    | 2         | 3.39%   |
| Unknown | 2         | 3.39%   |
| 4266    | 1         | 1.69%   |
| 2933    | 1         | 1.69%   |
| 2666    | 1         | 1.69%   |
| 1867    | 1         | 1.69%   |
| 1066    | 1         | 1.69%   |
| 800     | 1         | 1.69%   |

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
| Chicony Electronics                    | 28        | 29.47%  |
| IMC Networks                           | 10        | 10.53%  |
| Microdia                               | 8         | 8.42%   |
| Realtek Semiconductor                  | 7         | 7.37%   |
| Syntek                                 | 6         | 6.32%   |
| Silicon Motion                         | 6         | 6.32%   |
| Suyin                                  | 5         | 5.26%   |
| Sunplus Innovation Technology          | 5         | 5.26%   |
| Quanta                                 | 3         | 3.16%   |
| Lite-On Technology                     | 3         | 3.16%   |
| Acer                                   | 3         | 3.16%   |
| Ricoh                                  | 2         | 2.11%   |
| Primax Electronics                     | 2         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.11%   |
| Alcor Micro                            | 2         | 2.11%   |
| LG Electronics                         | 1         | 1.05%   |
| Lenovo                                 | 1         | 1.05%   |
| Goodong Industry                       | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                             | 6         | 6.32%   |
| IMC Networks Integrated Camera                        | 4         | 4.21%   |
| IMC Networks HD Camera                                | 4         | 4.21%   |
| Chicony EasyCamera                                    | 4         | 4.21%   |
| Syntek EasyCamera                                     | 3         | 3.16%   |
| Silicon Motion Web Camera                             | 3         | 3.16%   |
| Chicony TOSHIBA Web Camera - HD                       | 3         | 3.16%   |
| Syntek Integrated Camera                              | 2         | 2.11%   |
| Sunplus HD WebCam                                     | 2         | 2.11%   |
| Realtek HP "Truevision HD" laptop camera              | 2         | 2.11%   |
| Quanta HD User Facing                                 | 2         | 2.11%   |
| Primax HP HD Webcam [Fixed]                           | 2         | 2.11%   |
| Chicony HP Webcam                                     | 2         | 2.11%   |
| Chicony HP HD Webcam                                  | 2         | 2.11%   |
| Chicony HD WebCam                                     | 2         | 2.11%   |
| Acer Integrated Camera                                | 2         | 2.11%   |
| Syntek Lenovo EasyCamera                              | 1         | 1.05%   |
| Suyin Integrated_Webcam_HD                            | 1         | 1.05%   |
| Suyin HP Truevision HD                                | 1         | 1.05%   |
| Suyin HD WebCam                                       | 1         | 1.05%   |
| Suyin Acer/HP Integrated Webcam [CN0314]              | 1         | 1.05%   |
| Suyin 1.3M HD WebCam                                  | 1         | 1.05%   |
| Sunplus Integrated_Webcam_HD                          | 1         | 1.05%   |
| Sunplus HP Wide Vision HD                             | 1         | 1.05%   |
| Sunplus Asus Webcam                                   | 1         | 1.05%   |
| Silicon Motion WebCam SC-13HDL11939N                  | 1         | 1.05%   |
| Silicon Motion WebCam SC-0311139N                     | 1         | 1.05%   |
| Silicon Motion ATIV VGA Camera                        | 1         | 1.05%   |
| Ricoh Sony Vaio Integrated Webcam                     | 1         | 1.05%   |
| Ricoh Laptop_Integrated_Webcam_FHD                    | 1         | 1.05%   |
| Realtek Laptop_Integrated_Webcam_HD                   | 1         | 1.05%   |
| Realtek Integrated_Webcam_HD                          | 1         | 1.05%   |
| Realtek HP Wide Vision HD Camera                      | 1         | 1.05%   |
| Realtek HP Truevision HD                              | 1         | 1.05%   |
| Realtek HD WebCam                                     | 1         | 1.05%   |
| Quanta HD Webcam                                      | 1         | 1.05%   |
| Microdia Webcam SC-10HDD12636P                        | 1         | 1.05%   |
| Microdia USB 2.0 Camera                               | 1         | 1.05%   |
| Microdia Sony Visual Communication Camera             | 1         | 1.05%   |
| Microdia Sonix USB 2.0 Camera                         | 1         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_HD                  | 1         | 1.05%   |
| Microdia Integrated_Webcam_HD                         | 1         | 1.05%   |
| Microdia Integrated Webcam HD                         | 1         | 1.05%   |
| Microdia Integrated HD Webcam                         | 1         | 1.05%   |
| Lite-On TOSHIBA Web Camera - HD                       | 1         | 1.05%   |
| Lite-On HP Webcam                                     | 1         | 1.05%   |
| Lite-On HP HD Camera                                  | 1         | 1.05%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 1.05%   |
| Lenovo Integrated Webcam [R5U877]                     | 1         | 1.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                    | 1         | 1.05%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 1         | 1.05%   |
| Goodong Industry USB2.0 HD UVC WebCam                 | 1         | 1.05%   |
| Chicony Webcam-101                                    | 1         | 1.05%   |
| Chicony USB2.0 VGA UVC WebCam                         | 1         | 1.05%   |
| Chicony USB2.0 Camera                                 | 1         | 1.05%   |
| Chicony HP Truevision HD camera                       | 1         | 1.05%   |
| Chicony HP HD Camera                                  | 1         | 1.05%   |
| Chicony HD User Facing                                | 1         | 1.05%   |
| Chicony Front Camera                                  | 1         | 1.05%   |
| Chicony Acer CrystalEye Webcam                        | 1         | 1.05%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 45.45%  |
| Shenzhen Goodix Technology | 6         | 27.27%  |
| Upek                       | 5         | 22.73%  |
| Elan Microelectronics      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 22.73%  |
| Shenzhen Goodix  FingerPrint Device                    | 4         | 18.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 13.64%  |
| Validity Sensors VFS491                                | 2         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 9.09%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 1         | 25%     |
| Giesecke & Devrient | 1         | 25%     |
| Broadcom            | 1         | 25%     |
| Alcor Micro         | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 25%     |
| Giesecke & Devrient StarSign CUT               | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 68        | 63.55%  |
| 1     | 34        | 31.78%  |
| 2     | 5         | 4.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 22        | 50%     |
| Graphics card         | 13        | 29.55%  |
| Chipcard              | 4         | 9.09%   |
| Multimedia controller | 2         | 4.55%   |
| Storage               | 1         | 2.27%   |
| Sound                 | 1         | 2.27%   |
| Camera                | 1         | 2.27%   |


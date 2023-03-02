Manjaro - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 5153

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 755 G5            | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude E7450              | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [3ab9ad10d8](https://linux-hardware.org/?probe=3ab9ad10d8) | Feb 28, 2023 |
| Dell          | XPS 13 9380                 | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| System76      | Serval WS                   | [1b136ec80d](https://linux-hardware.org/?probe=1b136ec80d) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| HP            | G60                         | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| HP            | ZBook 17 G2                 | [408bb96959](https://linux-hardware.org/?probe=408bb96959) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [93dfbdd8cd](https://linux-hardware.org/?probe=93dfbdd8cd) | Feb 24, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [aef7584b8c](https://linux-hardware.org/?probe=aef7584b8c) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | [b2ae4d0b42](https://linux-hardware.org/?probe=b2ae4d0b42) | Feb 23, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ead0af8ae4](https://linux-hardware.org/?probe=ead0af8ae4) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude E5470              | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| HP            | EliteBook 8470p             | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [55c6dbae70](https://linux-hardware.org/?probe=55c6dbae70) | Feb 23, 2023 |
| HP            | Pavilion Notebook           | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| Dell          | Latitude 7410               | [dfa449b870](https://linux-hardware.org/?probe=dfa449b870) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| MSI           | GF63 Thin 9RCX              | [87a9510543](https://linux-hardware.org/?probe=87a9510543) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f98cec9924](https://linux-hardware.org/?probe=f98cec9924) | Feb 22, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [8be573974d](https://linux-hardware.org/?probe=8be573974d) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Gigabyte      | AORUS 17 XE4                | [b674e3e1e0](https://linux-hardware.org/?probe=b674e3e1e0) | Feb 21, 2023 |
| Apple         | MacBookAir7,2               | [97b147476a](https://linux-hardware.org/?probe=97b147476a) | Feb 20, 2023 |
| Dell          | Latitude E6430              | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | [d8afec7717](https://linux-hardware.org/?probe=d8afec7717) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | [a3f369f79b](https://linux-hardware.org/?probe=a3f369f79b) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cc447f6c07](https://linux-hardware.org/?probe=cc447f6c07) | Feb 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [f8e02626c5](https://linux-hardware.org/?probe=f8e02626c5) | Feb 19, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [28e6263489](https://linux-hardware.org/?probe=28e6263489) | Feb 19, 2023 |
| HP            | Notebook                    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| Dell          | G3 3590                     | [a8a3df007f](https://linux-hardware.org/?probe=a8a3df007f) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| Acer          | Aspire A515-51              | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [5e35f0aecc](https://linux-hardware.org/?probe=5e35f0aecc) | Feb 17, 2023 |
| Jumper        | EZbook                      | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [03498d5815](https://linux-hardware.org/?probe=03498d5815) | Feb 16, 2023 |
| HONOR         | BMH-WCX9                    | [c113bd50f3](https://linux-hardware.org/?probe=c113bd50f3) | Feb 16, 2023 |
| Jumper        | EZbook                      | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e5e721aaf2](https://linux-hardware.org/?probe=e5e721aaf2) | Feb 16, 2023 |
| Google        | Robo360                     | [744490a82c](https://linux-hardware.org/?probe=744490a82c) | Feb 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Google        | Robo360                     | [573d036948](https://linux-hardware.org/?probe=573d036948) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [1ebc6ae882](https://linux-hardware.org/?probe=1ebc6ae882) | Feb 14, 2023 |
| Dell          | XPS 9320                    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| Acer          | TravelMate P215-52          | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Acer          | Aspire E5-771G              | [d1abb191dd](https://linux-hardware.org/?probe=d1abb191dd) | Feb 13, 2023 |
| Dell          | Latitude 7490               | [c3f07cbb13](https://linux-hardware.org/?probe=c3f07cbb13) | Feb 13, 2023 |
| Dell          | Precision 3571              | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7711c96063](https://linux-hardware.org/?probe=7711c96063) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| ASUSTek       | X550CC                      | [769e8c51f0](https://linux-hardware.org/?probe=769e8c51f0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | [fb8b46669e](https://linux-hardware.org/?probe=fb8b46669e) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [0a3aa89ac9](https://linux-hardware.org/?probe=0a3aa89ac9) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [69cd397ac6](https://linux-hardware.org/?probe=69cd397ac6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Dell          | Inspiron 13 5310            | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| MSI           | GE60 2QE                    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Dell          | Precision 3571              | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f5dbc828f3](https://linux-hardware.org/?probe=f5dbc828f3) | Feb 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [95f88cc4d8](https://linux-hardware.org/?probe=95f88cc4d8) | Feb 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [5c86b33fdd](https://linux-hardware.org/?probe=5c86b33fdd) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [7a2dd12cd8](https://linux-hardware.org/?probe=7a2dd12cd8) | Feb 08, 2023 |
| HP            | 15 Notebook PC              | [df487953da](https://linux-hardware.org/?probe=df487953da) | Feb 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [a8aa5d2d58](https://linux-hardware.org/?probe=a8aa5d2d58) | Feb 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [ad723064e1](https://linux-hardware.org/?probe=ad723064e1) | Feb 06, 2023 |
| ASUSTek       | X550VXK                     | [e7a0aa4ff9](https://linux-hardware.org/?probe=e7a0aa4ff9) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f3cc45d12e](https://linux-hardware.org/?probe=f3cc45d12e) | Feb 05, 2023 |
| Timi          | A34S                        | [97aed45fe2](https://linux-hardware.org/?probe=97aed45fe2) | Feb 04, 2023 |
| Timi          | A34S                        | [55208c4210](https://linux-hardware.org/?probe=55208c4210) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [139605fcc1](https://linux-hardware.org/?probe=139605fcc1) | Feb 03, 2023 |
| Dell          | XPS 15 7590                 | [81f824a063](https://linux-hardware.org/?probe=81f824a063) | Feb 03, 2023 |
| Unknown       | Unknown                     | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Acer          | Predator PH315-55           | [9f90c06d52](https://linux-hardware.org/?probe=9f90c06d52) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| GPD           | G1619-04                    | [958fa49a0e](https://linux-hardware.org/?probe=958fa49a0e) | Feb 02, 2023 |
| Acer          | TravelMate P633-M           | [b9bb5f3746](https://linux-hardware.org/?probe=b9bb5f3746) | Feb 02, 2023 |
| Dell          | Vostro 5481                 | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [3a2665872a](https://linux-hardware.org/?probe=3a2665872a) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| Dell          | Latitude 7430               | [44d6dd63ce](https://linux-hardware.org/?probe=44d6dd63ce) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| MSI           | GF63 Thin 11UC              | [4f06c55846](https://linux-hardware.org/?probe=4f06c55846) | Feb 01, 2023 |
| Acer          | Aspire A315-56              | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [3c0723977c](https://linux-hardware.org/?probe=3c0723977c) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8a324e4189](https://linux-hardware.org/?probe=8a324e4189) | Jan 30, 2023 |
| HP            | OMEN by Laptop 15z-en100    | [0c91238954](https://linux-hardware.org/?probe=0c91238954) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| MSI           | Modern 14 A10RB             | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| HP            | Compaq 6530b                | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | [1ae85a6add](https://linux-hardware.org/?probe=1ae85a6add) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | [7f9b52e91c](https://linux-hardware.org/?probe=7f9b52e91c) | Jan 27, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| Lenovo        | ThinkPad T490 20N20048GE    | [54915be6bc](https://linux-hardware.org/?probe=54915be6bc) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| realme        | CloudProXXXX                | [520d929687](https://linux-hardware.org/?probe=520d929687) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [bf22d53528](https://linux-hardware.org/?probe=bf22d53528) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| Dell          | XPS 9320                    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [e5cbb75254](https://linux-hardware.org/?probe=e5cbb75254) | Jan 23, 2023 |
| System76      | Darter UltraThin            | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| Medion        | E4251                       | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [348a78bb64](https://linux-hardware.org/?probe=348a78bb64) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c6a463e92f](https://linux-hardware.org/?probe=c6a463e92f) | Jan 22, 2023 |
| Toshiba       | Satellite C50-C             | [3512195f65](https://linux-hardware.org/?probe=3512195f65) | Jan 21, 2023 |
| Dell          | G7 7700                     | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| Acer          | Swift SF314-57              | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| Dell          | Latitude E5440              | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | EliteBook 840 G5            | [96e072d33f](https://linux-hardware.org/?probe=96e072d33f) | Jan 18, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Acer          | Predator PH315-52           | [4df4c5ecc8](https://linux-hardware.org/?probe=4df4c5ecc8) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| Dell          | Inspiron 5585               | [b92481ca4e](https://linux-hardware.org/?probe=b92481ca4e) | Jan 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [6c8a25d916](https://linux-hardware.org/?probe=6c8a25d916) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| MSI           | Prestige 15 A11SCX          | [9c5bf0d05c](https://linux-hardware.org/?probe=9c5bf0d05c) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| HP            | ProBook 655 G1              | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| LG Electro... | 17Z90N-R.AAS9U1             | [9d6736bccd](https://linux-hardware.org/?probe=9d6736bccd) | Jan 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [52b5182480](https://linux-hardware.org/?probe=52b5182480) | Jan 14, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [4a0fec8aef](https://linux-hardware.org/?probe=4a0fec8aef) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [73533cda86](https://linux-hardware.org/?probe=73533cda86) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [ff2c48315e](https://linux-hardware.org/?probe=ff2c48315e) | Jan 13, 2023 |
| realme        | CloudProXXXX                | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [fbb327effe](https://linux-hardware.org/?probe=fbb327effe) | Jan 12, 2023 |
| HP            | Pavilion 15                 | [1dc150e9db](https://linux-hardware.org/?probe=1dc150e9db) | Jan 12, 2023 |
| HP            | ProBook 6560b               | [9f06213ef6](https://linux-hardware.org/?probe=9f06213ef6) | Jan 12, 2023 |
| HP            | ProBook 6560b               | [5b71b83435](https://linux-hardware.org/?probe=5b71b83435) | Jan 12, 2023 |
| Notebook      | L14xMU                      | [48b282b529](https://linux-hardware.org/?probe=48b282b529) | Jan 12, 2023 |
| Apple         | MacBookPro11,3              | [ede9b6da76](https://linux-hardware.org/?probe=ede9b6da76) | Jan 12, 2023 |
| Lenovo        | Z50-75 80EC                 | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [5be6eaa40c](https://linux-hardware.org/?probe=5be6eaa40c) | Jan 11, 2023 |
| HONOR         | NMH-WCX9                    | [a67f1ee7b0](https://linux-hardware.org/?probe=a67f1ee7b0) | Jan 11, 2023 |
| Dell          | Precision 7710              | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| HP            | ProBook 655 G1              | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| ASUSTek       | UX31A                       | [c618ab31a8](https://linux-hardware.org/?probe=c618ab31a8) | Jan 10, 2023 |
| HP            | Pavilion dv6                | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [45e96fb346](https://linux-hardware.org/?probe=45e96fb346) | Jan 09, 2023 |
| Dell          | Precision 7710              | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| ASUSTek       | UX31A                       | [2eaea530ea](https://linux-hardware.org/?probe=2eaea530ea) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| MSI           | GS63 Stealth 8RE            | [8682a08d74](https://linux-hardware.org/?probe=8682a08d74) | Jan 09, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | [5feb203761](https://linux-hardware.org/?probe=5feb203761) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | [da175172b3](https://linux-hardware.org/?probe=da175172b3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dc2a0809aa](https://linux-hardware.org/?probe=dc2a0809aa) | Jan 07, 2023 |
| IPASON        | MaxBook P1X                 | [b7d1ce416f](https://linux-hardware.org/?probe=b7d1ce416f) | Jan 07, 2023 |
| Sony          | SVS1512U1RW                 | [c5de402a7c](https://linux-hardware.org/?probe=c5de402a7c) | Jan 06, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| Samsung       | R530/R730                   | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c298dd423d](https://linux-hardware.org/?probe=c298dd423d) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| ASUSTek       | X501A1                      | [f88e88d88d](https://linux-hardware.org/?probe=f88e88d88d) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| HP            | Laptop 14-dk0xxx            | [47654afbbc](https://linux-hardware.org/?probe=47654afbbc) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ac3df6f289](https://linux-hardware.org/?probe=ac3df6f289) | Jan 03, 2023 |
| HP            | EliteBook 840 G5            | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Dell          | Inspiron 7577               | [437194cbc0](https://linux-hardware.org/?probe=437194cbc0) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | [c8d9352d43](https://linux-hardware.org/?probe=c8d9352d43) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | [ddadb5f34d](https://linux-hardware.org/?probe=ddadb5f34d) | Jan 03, 2023 |
| Dell          | Latitude 7410               | [3dadd543f1](https://linux-hardware.org/?probe=3dadd543f1) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| Dell          | XPS 15 9570                 | [c5d2fc381a](https://linux-hardware.org/?probe=c5d2fc381a) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| HP            | ZBook 15 G5                 | [04364cac9a](https://linux-hardware.org/?probe=04364cac9a) | Jan 02, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [fbf89f7693](https://linux-hardware.org/?probe=fbf89f7693) | Jan 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [70d5242ad0](https://linux-hardware.org/?probe=70d5242ad0) | Jan 01, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | [a22f1e75b3](https://linux-hardware.org/?probe=a22f1e75b3) | Jan 01, 2023 |
| Unknown       | Unknown                     | [10496680a5](https://linux-hardware.org/?probe=10496680a5) | Dec 31, 2022 |
| Dell          | XPS 9320                    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| ASUSTek       | X550VXK                     | [b8cd38522a](https://linux-hardware.org/?probe=b8cd38522a) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| HP            | EliteBook 845 14 inch G9... | [5b5e58e433](https://linux-hardware.org/?probe=5b5e58e433) | Dec 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c2a949b725](https://linux-hardware.org/?probe=c2a949b725) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [11d4e1f9a1](https://linux-hardware.org/?probe=11d4e1f9a1) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [b60b954dc4](https://linux-hardware.org/?probe=b60b954dc4) | Dec 29, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| Apple         | MacBookAir6,2               | [af9ab4ba4d](https://linux-hardware.org/?probe=af9ab4ba4d) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f19e16b1ac](https://linux-hardware.org/?probe=f19e16b1ac) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [b62b4d2134](https://linux-hardware.org/?probe=b62b4d2134) | Dec 27, 2022 |
| Dell          | XPS 9320                    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [eb5e0b8201](https://linux-hardware.org/?probe=eb5e0b8201) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4ea69511df](https://linux-hardware.org/?probe=4ea69511df) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c8b85cb0cd](https://linux-hardware.org/?probe=c8b85cb0cd) | Dec 26, 2022 |
| Dell          | Inspiron N5010              | [69ac8a9522](https://linux-hardware.org/?probe=69ac8a9522) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [06027a53fb](https://linux-hardware.org/?probe=06027a53fb) | Dec 26, 2022 |
| Chuwi         | HeroBook Air                | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [649291f277](https://linux-hardware.org/?probe=649291f277) | Dec 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [8d2d8be057](https://linux-hardware.org/?probe=8d2d8be057) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Dell          | XPS 9320                    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [81fcc00d18](https://linux-hardware.org/?probe=81fcc00d18) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| HP            | Laptop 15-bs0xx             | [3d50b74a6b](https://linux-hardware.org/?probe=3d50b74a6b) | Dec 23, 2022 |
| HUAWEI        | KPR-WX9                     | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Dell          | Precision M6600             | [00840d085c](https://linux-hardware.org/?probe=00840d085c) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Dell          | XPS 9320                    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| MSI           | Katana GF66 11UE            | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0MQ0... | [94e5bdb2cb](https://linux-hardware.org/?probe=94e5bdb2cb) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [214d584e36](https://linux-hardware.org/?probe=214d584e36) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| HP            | ENVY Laptop 16-h0xxx        | [4e38f93dd3](https://linux-hardware.org/?probe=4e38f93dd3) | Dec 21, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [90d1d153a4](https://linux-hardware.org/?probe=90d1d153a4) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [93eff781da](https://linux-hardware.org/?probe=93eff781da) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [0b7352a343](https://linux-hardware.org/?probe=0b7352a343) | Dec 20, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [654a04cdc4](https://linux-hardware.org/?probe=654a04cdc4) | Dec 20, 2022 |
| Toshiba       | Satellite L10W-B-101        | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [ebf2594631](https://linux-hardware.org/?probe=ebf2594631) | Dec 19, 2022 |
| K.A.Techno... | TM1                         | [88e36a5d00](https://linux-hardware.org/?probe=88e36a5d00) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| Dell          | XPS 13 9350                 | [d414748117](https://linux-hardware.org/?probe=d414748117) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c45ca502c5](https://linux-hardware.org/?probe=c45ca502c5) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [2d6dff8209](https://linux-hardware.org/?probe=2d6dff8209) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0d67c53553](https://linux-hardware.org/?probe=0d67c53553) | Dec 18, 2022 |
| HP            | 2000                        | [6273a792ae](https://linux-hardware.org/?probe=6273a792ae) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [86fbbf1bc2](https://linux-hardware.org/?probe=86fbbf1bc2) | Dec 17, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| Alienware     | 15                          | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8f50c0d881](https://linux-hardware.org/?probe=8f50c0d881) | Dec 15, 2022 |
| Dell          | Vostro 7590                 | [c758af3223](https://linux-hardware.org/?probe=c758af3223) | Dec 15, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | [ca39e55353](https://linux-hardware.org/?probe=ca39e55353) | Dec 15, 2022 |
| Dell          | Latitude 5420               | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Dell          | Inspiron 5370               | [dd8f3feae5](https://linux-hardware.org/?probe=dd8f3feae5) | Dec 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [3878d884cb](https://linux-hardware.org/?probe=3878d884cb) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [98f6e27cac](https://linux-hardware.org/?probe=98f6e27cac) | Dec 14, 2022 |
| Toshiba       | Satellite Pro L300          | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| K.A.Techno... | TM1                         | [a27835f164](https://linux-hardware.org/?probe=a27835f164) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| Acer          | Aspire ES1-111M             | [0d527c1b1d](https://linux-hardware.org/?probe=0d527c1b1d) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Acer          | Nitro AN517-41              | [468d665801](https://linux-hardware.org/?probe=468d665801) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [559c3f32f8](https://linux-hardware.org/?probe=559c3f32f8) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [eb0d410f64](https://linux-hardware.org/?probe=eb0d410f64) | Dec 12, 2022 |
| Apple         | MacBookPro11,2              | [6048cffe66](https://linux-hardware.org/?probe=6048cffe66) | Dec 12, 2022 |
| Unknown       | X133                        | [694e264bcf](https://linux-hardware.org/?probe=694e264bcf) | Dec 12, 2022 |
| MSI           | Prestige 14 A11SC           | [7fa118f812](https://linux-hardware.org/?probe=7fa118f812) | Dec 11, 2022 |
| Medion        | E4251                       | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Apple         | MacBookPro11,1              | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| Acer          | Aspire E5-571G              | [5ddea1e0e0](https://linux-hardware.org/?probe=5ddea1e0e0) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| HUAWEI        | CREM-WXX9                   | [1b6dee1e4a](https://linux-hardware.org/?probe=1b6dee1e4a) | Dec 10, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [61b2bab886](https://linux-hardware.org/?probe=61b2bab886) | Dec 10, 2022 |
| Medion        | E4251                       | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [fdda7ba30e](https://linux-hardware.org/?probe=fdda7ba30e) | Dec 10, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [16232a46ed](https://linux-hardware.org/?probe=16232a46ed) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5S... | [7772d8b9f8](https://linux-hardware.org/?probe=7772d8b9f8) | Dec 10, 2022 |
| GPU Compan... | GWNR71517                   | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| IPASON        | MaxBook P1X                 | [c699081c87](https://linux-hardware.org/?probe=c699081c87) | Dec 08, 2022 |
| BESSTAR Te... | U820                        | [ea466e46b1](https://linux-hardware.org/?probe=ea466e46b1) | Dec 07, 2022 |
| HP            | 245 G8                      | [2fbc616550](https://linux-hardware.org/?probe=2fbc616550) | Dec 07, 2022 |
| Clevo         | P150HMx                     | [f1500b1665](https://linux-hardware.org/?probe=f1500b1665) | Dec 06, 2022 |
| Dell          | Inspiron N5110              | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Dell          | G15 5515                    | [63fed6d448](https://linux-hardware.org/?probe=63fed6d448) | Dec 06, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [3e1e88ac7a](https://linux-hardware.org/?probe=3e1e88ac7a) | Dec 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [792c537a38](https://linux-hardware.org/?probe=792c537a38) | Dec 06, 2022 |
| HP            | ProBook 440 G5              | [7f9c0a0974](https://linux-hardware.org/?probe=7f9c0a0974) | Dec 06, 2022 |
| Dell          | G5 5505                     | [c36399d764](https://linux-hardware.org/?probe=c36399d764) | Dec 06, 2022 |
| Medion        | E4251                       | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [504a0286fb](https://linux-hardware.org/?probe=504a0286fb) | Dec 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [8a91af8c9d](https://linux-hardware.org/?probe=8a91af8c9d) | Dec 05, 2022 |
| Toshiba       | Satellite C650D             | [694d2c9099](https://linux-hardware.org/?probe=694d2c9099) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [3ee55cc441](https://linux-hardware.org/?probe=3ee55cc441) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [4a2e796be8](https://linux-hardware.org/?probe=4a2e796be8) | Dec 04, 2022 |
| HP            | ProBook 440 G5              | [a8e17ad39c](https://linux-hardware.org/?probe=a8e17ad39c) | Dec 04, 2022 |
| MECHREVO      | X3 Series GK7CP6R           | [7990b26bbf](https://linux-hardware.org/?probe=7990b26bbf) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [05ae64c1b8](https://linux-hardware.org/?probe=05ae64c1b8) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [ae6745045a](https://linux-hardware.org/?probe=ae6745045a) | Dec 04, 2022 |
| HP            | ZBook 15 G4                 | [9950cb061d](https://linux-hardware.org/?probe=9950cb061d) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| HP            | Pavilion Laptop             | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Valve         | Jupiter                     | [1fdf6ffce7](https://linux-hardware.org/?probe=1fdf6ffce7) | Dec 01, 2022 |
| Dell          | Precision 5540              | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| Acer          | TravelMate P614-51T-G2      | [952e89e25d](https://linux-hardware.org/?probe=952e89e25d) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| Toshiba       | TECRA S11                   | [3d2414e47b](https://linux-hardware.org/?probe=3d2414e47b) | Nov 30, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [f5f86becf7](https://linux-hardware.org/?probe=f5f86becf7) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Dell          | Precision 7520              | [2c0cb92f23](https://linux-hardware.org/?probe=2c0cb92f23) | Nov 29, 2022 |
| HP            | ProBook 440 G5              | [45097ff070](https://linux-hardware.org/?probe=45097ff070) | Nov 29, 2022 |
| HP            | Notebook                    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460s 20FAS16J0... | [142a1e8a94](https://linux-hardware.org/?probe=142a1e8a94) | Nov 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e0bdd2fbd2](https://linux-hardware.org/?probe=e0bdd2fbd2) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [69a6535286](https://linux-hardware.org/?probe=69a6535286) | Nov 28, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| HP            | Laptop 15-dy2xxx            | [a1c088bc35](https://linux-hardware.org/?probe=a1c088bc35) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [0dcd2bdc50](https://linux-hardware.org/?probe=0dcd2bdc50) | Nov 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [620cab185f](https://linux-hardware.org/?probe=620cab185f) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| HUAWEI        | KLVL-WXXW                   | [7e65f428cc](https://linux-hardware.org/?probe=7e65f428cc) | Nov 27, 2022 |
| MSI           | GL62 7QF                    | [abd74be332](https://linux-hardware.org/?probe=abd74be332) | Nov 27, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| Dell          | Latitude E6420              | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| Alienware     | 15                          | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| MSI           | GP63 Leopard 8RE            | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| ASUSTek       | PRIME Z690-P                | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [60c1698203](https://linux-hardware.org/?probe=60c1698203) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6722142846](https://linux-hardware.org/?probe=6722142846) | Nov 20, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK E756               | [144470ec16](https://linux-hardware.org/?probe=144470ec16) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| Lenovo        | ThinkPad T430 2349KQ3       | [aacdefc31b](https://linux-hardware.org/?probe=aacdefc31b) | Nov 17, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| HP            | Compaq 15                   | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| Google        | Boten                       | [105e91dd04](https://linux-hardware.org/?probe=105e91dd04) | Nov 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [3e46bbaa1b](https://linux-hardware.org/?probe=3e46bbaa1b) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [cf97226a28](https://linux-hardware.org/?probe=cf97226a28) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| Dell          | Latitude E6220              | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [dcffe478fe](https://linux-hardware.org/?probe=dcffe478fe) | Nov 14, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e6ef3b56eb](https://linux-hardware.org/?probe=e6ef3b56eb) | Nov 14, 2022 |
| Lenovo        | ThinkPad T450s 20BW000DH... | [b9913c760a](https://linux-hardware.org/?probe=b9913c760a) | Nov 14, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [41dbab85c0](https://linux-hardware.org/?probe=41dbab85c0) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b3473a1862](https://linux-hardware.org/?probe=b3473a1862) | Nov 13, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ca85c59fad](https://linux-hardware.org/?probe=ca85c59fad) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| Dell          | G15 5510                    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| Lenovo        | G500 20236                  | [b156c32896](https://linux-hardware.org/?probe=b156c32896) | Nov 12, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [7827dd0f86](https://linux-hardware.org/?probe=7827dd0f86) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [64d896b971](https://linux-hardware.org/?probe=64d896b971) | Nov 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [c3612a66aa](https://linux-hardware.org/?probe=c3612a66aa) | Nov 10, 2022 |
| HP            | EliteBook 840 14 inch G9... | [950c263b8a](https://linux-hardware.org/?probe=950c263b8a) | Nov 10, 2022 |
| Dell          | Latitude E6330              | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Acer          | Aspire V5-123               | [7e9ca0bb77](https://linux-hardware.org/?probe=7e9ca0bb77) | Nov 09, 2022 |
| HP            | ENVY 15                     | [716fe10a4a](https://linux-hardware.org/?probe=716fe10a4a) | Nov 09, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| Lenovo        | V15-IIL 82C5                | [7f372be9dc](https://linux-hardware.org/?probe=7f372be9dc) | Nov 07, 2022 |
| Dell          | Inspiron 5379               | [f18d0b8b8a](https://linux-hardware.org/?probe=f18d0b8b8a) | Nov 06, 2022 |
| Dell          | Inspiron 5379               | [141de7e9a7](https://linux-hardware.org/?probe=141de7e9a7) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [e5abd4f928](https://linux-hardware.org/?probe=e5abd4f928) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Dell          | Inspiron 5502               | [204c296466](https://linux-hardware.org/?probe=204c296466) | Nov 04, 2022 |
| ASUSTek       | X553MA                      | [d70f962654](https://linux-hardware.org/?probe=d70f962654) | Nov 04, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [ca5335acd5](https://linux-hardware.org/?probe=ca5335acd5) | Nov 03, 2022 |
| Dell          | Latitude 7280               | [ec1ac4ec28](https://linux-hardware.org/?probe=ec1ac4ec28) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [2b5c165e30](https://linux-hardware.org/?probe=2b5c165e30) | Nov 02, 2022 |
| Dell          | XPS 13 9305                 | [4ffebc50a0](https://linux-hardware.org/?probe=4ffebc50a0) | Nov 02, 2022 |
| Dell          | Precision 7530              | [b1b5f7678c](https://linux-hardware.org/?probe=b1b5f7678c) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Acer          | Aspire A515-46              | [ef6bcab217](https://linux-hardware.org/?probe=ef6bcab217) | Nov 01, 2022 |
| Lenovo        | ThinkPad L460 20FVS1Y500    | [5fc669ddbe](https://linux-hardware.org/?probe=5fc669ddbe) | Nov 01, 2022 |
| SANTECH       | NL5xRU                      | [63e1b4298d](https://linux-hardware.org/?probe=63e1b4298d) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | [6a28e2929d](https://linux-hardware.org/?probe=6a28e2929d) | Oct 31, 2022 |
| Lenovo        | ThinkPad T440p 20AW005BG... | [b25134edde](https://linux-hardware.org/?probe=b25134edde) | Oct 31, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [5355a5547a](https://linux-hardware.org/?probe=5355a5547a) | Oct 31, 2022 |
| Alienware     | 15 R3                       | [4659975000](https://linux-hardware.org/?probe=4659975000) | Oct 31, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | [0e06dcc642](https://linux-hardware.org/?probe=0e06dcc642) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | [41a0a441d3](https://linux-hardware.org/?probe=41a0a441d3) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| ASUSTek       | X541UV                      | [cef88d9d62](https://linux-hardware.org/?probe=cef88d9d62) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| Chuwi         | LapBook Pro                 | [d362ed14bf](https://linux-hardware.org/?probe=d362ed14bf) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [806e4d754d](https://linux-hardware.org/?probe=806e4d754d) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d6ccf0a2d8](https://linux-hardware.org/?probe=d6ccf0a2d8) | Oct 28, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [d5c2f29c22](https://linux-hardware.org/?probe=d5c2f29c22) | Oct 28, 2022 |
| MSI           | GP66 Leopard 11UG           | [aec6edc8a0](https://linux-hardware.org/?probe=aec6edc8a0) | Oct 28, 2022 |
| Dell          | Inspiron 11 - 3147          | [58d46fb47f](https://linux-hardware.org/?probe=58d46fb47f) | Oct 28, 2022 |
| Acer          | Aspire E5-573G              | [f575803f23](https://linux-hardware.org/?probe=f575803f23) | Oct 28, 2022 |
| Lenovo        | G470 20078                  | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| HP            | ProBook 450 G5              | [664bf1184f](https://linux-hardware.org/?probe=664bf1184f) | Oct 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0e69671817](https://linux-hardware.org/?probe=0e69671817) | Oct 27, 2022 |
| HUAWEI        | BOM-WXX9                    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [b9c616b406](https://linux-hardware.org/?probe=b9c616b406) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [16b3338525](https://linux-hardware.org/?probe=16b3338525) | Oct 27, 2022 |
| HP            | ProBook 445 G7              | [d9f63cbff8](https://linux-hardware.org/?probe=d9f63cbff8) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ffa2d93859](https://linux-hardware.org/?probe=ffa2d93859) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [642cfbc2d7](https://linux-hardware.org/?probe=642cfbc2d7) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| HP            | Spectre Laptop 13-af0xx     | [1ded224c69](https://linux-hardware.org/?probe=1ded224c69) | Oct 26, 2022 |
| Acer          | Swift SFX14-41G             | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [bb90eb1ad1](https://linux-hardware.org/?probe=bb90eb1ad1) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b2bb88f27f](https://linux-hardware.org/?probe=b2bb88f27f) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [e5d5599bc7](https://linux-hardware.org/?probe=e5d5599bc7) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [9cc8a69671](https://linux-hardware.org/?probe=9cc8a69671) | Oct 25, 2022 |
| HP            | Spectre Laptop 13-af0xx     | [7e6d814d87](https://linux-hardware.org/?probe=7e6d814d87) | Oct 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [15ced71b20](https://linux-hardware.org/?probe=15ced71b20) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [8994af98ff](https://linux-hardware.org/?probe=8994af98ff) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fc7326f81b](https://linux-hardware.org/?probe=fc7326f81b) | Oct 24, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [37028111aa](https://linux-hardware.org/?probe=37028111aa) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | [bc30c6555a](https://linux-hardware.org/?probe=bc30c6555a) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | [667d235a8f](https://linux-hardware.org/?probe=667d235a8f) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| Tactus        | GeoBook_240                 | [5331bf15bd](https://linux-hardware.org/?probe=5331bf15bd) | Oct 23, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [efb2913d22](https://linux-hardware.org/?probe=efb2913d22) | Oct 23, 2022 |
| HP            | ZBook 17 G6                 | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7cafd024ea](https://linux-hardware.org/?probe=7cafd024ea) | Oct 22, 2022 |
| Global Dis... | W11651                      | [9cf1e2df07](https://linux-hardware.org/?probe=9cf1e2df07) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [9f16b5a7e2](https://linux-hardware.org/?probe=9f16b5a7e2) | Oct 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | Legion 5 82B5               | [3d67f01531](https://linux-hardware.org/?probe=3d67f01531) | Oct 22, 2022 |
| HP            | ProBook 6550b               | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| MSI           | Katana GF76 11UG            | [ab90111e61](https://linux-hardware.org/?probe=ab90111e61) | Oct 21, 2022 |
| Dell          | Latitude E6400              | [d899ab2ef4](https://linux-hardware.org/?probe=d899ab2ef4) | Oct 21, 2022 |
| Medion        | S15449                      | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| HP            | ProBook 6550b               | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| Acer          | Aspire E5-553G              | [8e75bbadf5](https://linux-hardware.org/?probe=8e75bbadf5) | Oct 20, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [30bf540299](https://linux-hardware.org/?probe=30bf540299) | Oct 19, 2022 |
| MSI           | Modern 15 A11MU             | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [56089b3625](https://linux-hardware.org/?probe=56089b3625) | Oct 19, 2022 |
| Acer          | Aspire 4750                 | [e07159c158](https://linux-hardware.org/?probe=e07159c158) | Oct 19, 2022 |
| Dell          | Latitude E6220              | [66badd4e9a](https://linux-hardware.org/?probe=66badd4e9a) | Oct 18, 2022 |
| Acer          | Aspire 4750                 | [0910d29ded](https://linux-hardware.org/?probe=0910d29ded) | Oct 18, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [8c97c331b9](https://linux-hardware.org/?probe=8c97c331b9) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [469118097a](https://linux-hardware.org/?probe=469118097a) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| Chuwi         | HeroBook Air                | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Acer          | Aspire V3-771               | [91e4682f34](https://linux-hardware.org/?probe=91e4682f34) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| HP            | ENVY 15                     | [17681478e1](https://linux-hardware.org/?probe=17681478e1) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| Lenovo        | Y50-70 20378                | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| MSI           | Katana GF76 11UG            | [460ceb1307](https://linux-hardware.org/?probe=460ceb1307) | Oct 16, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e515cd0e66](https://linux-hardware.org/?probe=e515cd0e66) | Oct 15, 2022 |
| HP            | ProBook 455 G7              | [bb58a322f3](https://linux-hardware.org/?probe=bb58a322f3) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Acer          | Aspire E5-553G              | [fcf93f53f4](https://linux-hardware.org/?probe=fcf93f53f4) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [705931711b](https://linux-hardware.org/?probe=705931711b) | Oct 13, 2022 |
| Dell          | Latitude E7250              | [f397f81353](https://linux-hardware.org/?probe=f397f81353) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [318b3ef82b](https://linux-hardware.org/?probe=318b3ef82b) | Oct 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [cbc3888844](https://linux-hardware.org/?probe=cbc3888844) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [17feafd680](https://linux-hardware.org/?probe=17feafd680) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e940ddf8a7](https://linux-hardware.org/?probe=e940ddf8a7) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [1bbc611d89](https://linux-hardware.org/?probe=1bbc611d89) | Oct 12, 2022 |
| AVITA         | NS14A6                      | [0ed9ac0a2b](https://linux-hardware.org/?probe=0ed9ac0a2b) | Oct 11, 2022 |
| AVITA         | NS14A6                      | [27412eff74](https://linux-hardware.org/?probe=27412eff74) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| HUAWEI        | HVY-WXX9                    | [10ab944320](https://linux-hardware.org/?probe=10ab944320) | Oct 11, 2022 |
| HP            | Pavilion g6                 | [943ee204e0](https://linux-hardware.org/?probe=943ee204e0) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [cc663da2bc](https://linux-hardware.org/?probe=cc663da2bc) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| Apple         | MacBookPro10,2              | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| Dell          | Precision 5560              | [001c5b0c94](https://linux-hardware.org/?probe=001c5b0c94) | Oct 09, 2022 |
| Dell          | Latitude 5310               | [f694e6b10e](https://linux-hardware.org/?probe=f694e6b10e) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Acer          | Extensa 215-32              | [3e6ce67bb5](https://linux-hardware.org/?probe=3e6ce67bb5) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [49802b54cd](https://linux-hardware.org/?probe=49802b54cd) | Oct 08, 2022 |
| Acer          | Extensa 215-32              | [366f0e7930](https://linux-hardware.org/?probe=366f0e7930) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | [4afa1df235](https://linux-hardware.org/?probe=4afa1df235) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | [d0584d3672](https://linux-hardware.org/?probe=d0584d3672) | Oct 08, 2022 |
| HP            | Pavilion dv6                | [0c2329c8d6](https://linux-hardware.org/?probe=0c2329c8d6) | Oct 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| Toshiba       | Satellite P755              | [9b8147c1f7](https://linux-hardware.org/?probe=9b8147c1f7) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| Toshiba       | Encore                      | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| CyberPower... | FANG Pro                    | [e8734135b0](https://linux-hardware.org/?probe=e8734135b0) | Oct 05, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [4ba2e11c73](https://linux-hardware.org/?probe=4ba2e11c73) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | ThinkPad T490 20RYS07R00    | [d6be1b9cf9](https://linux-hardware.org/?probe=d6be1b9cf9) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [ca89628082](https://linux-hardware.org/?probe=ca89628082) | Oct 03, 2022 |
| GPD           | G1621-02                    | [1f88eb2bec](https://linux-hardware.org/?probe=1f88eb2bec) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [9c3f9bb60e](https://linux-hardware.org/?probe=9c3f9bb60e) | Oct 03, 2022 |
| MSI           | Katana GF76 11UG            | [d433417836](https://linux-hardware.org/?probe=d433417836) | Oct 03, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [0d67980efe](https://linux-hardware.org/?probe=0d67980efe) | Oct 03, 2022 |
| Acer          | Aspire F5-573G              | [a9f0d894af](https://linux-hardware.org/?probe=a9f0d894af) | Oct 03, 2022 |
| Dell          | XPS 13 9310                 | [f58849d2c7](https://linux-hardware.org/?probe=f58849d2c7) | Oct 03, 2022 |
| HP            | Laptop 14-dk0xxx            | [4283f9a4bd](https://linux-hardware.org/?probe=4283f9a4bd) | Oct 02, 2022 |
| HP            | Laptop 15-da0xxx            | [831cd8e80f](https://linux-hardware.org/?probe=831cd8e80f) | Oct 02, 2022 |
| HP            | ProBook 6470b               | [10438199c4](https://linux-hardware.org/?probe=10438199c4) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | 250 G3                      | [753ef53a5a](https://linux-hardware.org/?probe=753ef53a5a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [e722d17a52](https://linux-hardware.org/?probe=e722d17a52) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [012add7349](https://linux-hardware.org/?probe=012add7349) | Oct 01, 2022 |
| Sony          | SVF15N17CXB                 | [5082dde27d](https://linux-hardware.org/?probe=5082dde27d) | Oct 01, 2022 |
| Irbis         | NB121                       | [a2eb8c8af1](https://linux-hardware.org/?probe=a2eb8c8af1) | Sep 30, 2022 |
| HP            | EliteBook 850 G1            | [9667dac801](https://linux-hardware.org/?probe=9667dac801) | Sep 30, 2022 |
| Irbis         | NB121                       | [90a0ae1cf9](https://linux-hardware.org/?probe=90a0ae1cf9) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [3ad60e2d21](https://linux-hardware.org/?probe=3ad60e2d21) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [5a8032ee05](https://linux-hardware.org/?probe=5a8032ee05) | Sep 30, 2022 |
| Intel Clie... | LAPQC71A                    | [6d7beecaf6](https://linux-hardware.org/?probe=6d7beecaf6) | Sep 30, 2022 |
| HP            | Notebook                    | [e172f83238](https://linux-hardware.org/?probe=e172f83238) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [4e9248b1eb](https://linux-hardware.org/?probe=4e9248b1eb) | Sep 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [353324cbfd](https://linux-hardware.org/?probe=353324cbfd) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a1bee52021](https://linux-hardware.org/?probe=a1bee52021) | Sep 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [25d3fc37f5](https://linux-hardware.org/?probe=25d3fc37f5) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [f5ddf4a2b4](https://linux-hardware.org/?probe=f5ddf4a2b4) | Sep 29, 2022 |
| HP            | ProBook 430 G6              | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | [72d80e02c9](https://linux-hardware.org/?probe=72d80e02c9) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | [47b22afda2](https://linux-hardware.org/?probe=47b22afda2) | Sep 29, 2022 |
| Toshiba       | Satellite C650D             | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| HP            | Laptop 14-dq1xxx            | [9b3a3858bc](https://linux-hardware.org/?probe=9b3a3858bc) | Sep 28, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [9a1e3a98ab](https://linux-hardware.org/?probe=9a1e3a98ab) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ebfbdd37b8](https://linux-hardware.org/?probe=ebfbdd37b8) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [09d154c2f2](https://linux-hardware.org/?probe=09d154c2f2) | Sep 27, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | [e27e7bfd76](https://linux-hardware.org/?probe=e27e7bfd76) | Sep 27, 2022 |
| Dell          | Latitude E7440              | [d211ff97c6](https://linux-hardware.org/?probe=d211ff97c6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Dell          | Latitude E6400              | [c1190109d0](https://linux-hardware.org/?probe=c1190109d0) | Sep 26, 2022 |
| Lenovo        | ThinkPad T460p 20FW000EG... | [60138ee2f9](https://linux-hardware.org/?probe=60138ee2f9) | Sep 26, 2022 |
| Timi          | RedmiBook Pro 15S           | [533cc3b3ae](https://linux-hardware.org/?probe=533cc3b3ae) | Sep 26, 2022 |
| ASUSTek       | N45SF                       | [7461bd2562](https://linux-hardware.org/?probe=7461bd2562) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | [0d1b8fe301](https://linux-hardware.org/?probe=0d1b8fe301) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [ccba8f6c1a](https://linux-hardware.org/?probe=ccba8f6c1a) | Sep 24, 2022 |
| ASUSTek       | X556UF                      | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| Acer          | Swift SF314-71              | [321edce78d](https://linux-hardware.org/?probe=321edce78d) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Unknown       | Unknown                     | [af65739ccc](https://linux-hardware.org/?probe=af65739ccc) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| HP            | Laptop                      | [0cbc7e4f5a](https://linux-hardware.org/?probe=0cbc7e4f5a) | Sep 21, 2022 |
| HP            | ENVY 15                     | [388547d18c](https://linux-hardware.org/?probe=388547d18c) | Sep 21, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [6ffce551a0](https://linux-hardware.org/?probe=6ffce551a0) | Sep 21, 2022 |
| HP            | ProBook 4520s               | [af4a575c52](https://linux-hardware.org/?probe=af4a575c52) | Sep 20, 2022 |
| Apple         | MacBookAir7,2               | [f9f1973349](https://linux-hardware.org/?probe=f9f1973349) | Sep 20, 2022 |
| Gateway       | NV57H                       | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [75cc4fa084](https://linux-hardware.org/?probe=75cc4fa084) | Sep 19, 2022 |
| Acer          | Nitro AN515-42              | [97e2956728](https://linux-hardware.org/?probe=97e2956728) | Sep 19, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [1cbec0f70e](https://linux-hardware.org/?probe=1cbec0f70e) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Apple         | MacBookPro15,1              | [b0e746792f](https://linux-hardware.org/?probe=b0e746792f) | Sep 19, 2022 |
| Sony          | VPCF236FM                   | [397f485cfc](https://linux-hardware.org/?probe=397f485cfc) | Sep 19, 2022 |
| Dell          | Precision M4800             | [73d00fe344](https://linux-hardware.org/?probe=73d00fe344) | Sep 19, 2022 |
| ASUSTek       | G752VT                      | [bbd1eb7810](https://linux-hardware.org/?probe=bbd1eb7810) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [13b23fabb7](https://linux-hardware.org/?probe=13b23fabb7) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [59369fa3fb](https://linux-hardware.org/?probe=59369fa3fb) | Sep 17, 2022 |
| Dell          | Inspiron MP061              | [f045e1f138](https://linux-hardware.org/?probe=f045e1f138) | Sep 17, 2022 |
| AXDIA Inte... | WINPAD V10                  | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [31c810e744](https://linux-hardware.org/?probe=31c810e744) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | [8e62e03e0b](https://linux-hardware.org/?probe=8e62e03e0b) | Sep 15, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [00bcfb51bd](https://linux-hardware.org/?probe=00bcfb51bd) | Sep 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [45309244c3](https://linux-hardware.org/?probe=45309244c3) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | V310-15ISK 80SY             | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| ASUSTek       | X550VXK                     | [df5d5b4f0d](https://linux-hardware.org/?probe=df5d5b4f0d) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [c9df1f2514](https://linux-hardware.org/?probe=c9df1f2514) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b62bd233c2](https://linux-hardware.org/?probe=b62bd233c2) | Sep 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [dee9d6b81f](https://linux-hardware.org/?probe=dee9d6b81f) | Sep 13, 2022 |
| ASUSTek       | X541UJ                      | [9745e99a08](https://linux-hardware.org/?probe=9745e99a08) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [82b9d1247e](https://linux-hardware.org/?probe=82b9d1247e) | Sep 13, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [b7eb07ec8d](https://linux-hardware.org/?probe=b7eb07ec8d) | Sep 12, 2022 |
| HP            | Pavilion dm1                | [eec30e7c48](https://linux-hardware.org/?probe=eec30e7c48) | Sep 12, 2022 |
| HP            | ENVY 15                     | [97caacee16](https://linux-hardware.org/?probe=97caacee16) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [3d1d8301c3](https://linux-hardware.org/?probe=3d1d8301c3) | Sep 12, 2022 |
| HP            | EliteBook 840 G5            | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| Timi          | RedmiBook Pro 15S           | [20b9167fee](https://linux-hardware.org/?probe=20b9167fee) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ecadc5740](https://linux-hardware.org/?probe=1ecadc5740) | Sep 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [8df1767beb](https://linux-hardware.org/?probe=8df1767beb) | Sep 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [f145a7915c](https://linux-hardware.org/?probe=f145a7915c) | Sep 10, 2022 |
| Dell          | Latitude E6430              | [323203ec1c](https://linux-hardware.org/?probe=323203ec1c) | Sep 09, 2022 |
| Lenovo        | ThinkPad T540p 20BFA05FU... | [e953e3c331](https://linux-hardware.org/?probe=e953e3c331) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [2f23958df0](https://linux-hardware.org/?probe=2f23958df0) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f752846656](https://linux-hardware.org/?probe=f752846656) | Sep 09, 2022 |
| CyberPower... | FANG Pro                    | [4bb2815c31](https://linux-hardware.org/?probe=4bb2815c31) | Sep 07, 2022 |
| ASUSTek       | X541UJ                      | [84b26ca406](https://linux-hardware.org/?probe=84b26ca406) | Sep 07, 2022 |
| HP            | EliteBook 840 G5            | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [58e55d314a](https://linux-hardware.org/?probe=58e55d314a) | Sep 06, 2022 |
| Lenovo        | G580 20150                  | [e0bb6ae251](https://linux-hardware.org/?probe=e0bb6ae251) | Sep 05, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [11bdade1e5](https://linux-hardware.org/?probe=11bdade1e5) | Sep 05, 2022 |
| Acer          | Nitro AN515-54              | [5b76bade7e](https://linux-hardware.org/?probe=5b76bade7e) | Sep 05, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [cc43cdda9a](https://linux-hardware.org/?probe=cc43cdda9a) | Sep 04, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [8d611bed12](https://linux-hardware.org/?probe=8d611bed12) | Sep 04, 2022 |
| HUAWEI        | VLT-WX0                     | [f9881e0b9b](https://linux-hardware.org/?probe=f9881e0b9b) | Sep 03, 2022 |
| Dell          | XPS 15 9510                 | [3e057c7bbb](https://linux-hardware.org/?probe=3e057c7bbb) | Sep 03, 2022 |
| Acer          | Nitro AN515-54              | [5b5cc6b013](https://linux-hardware.org/?probe=5b5cc6b013) | Sep 03, 2022 |
| ASUSTek       | X510UNR                     | [ca761f1ee7](https://linux-hardware.org/?probe=ca761f1ee7) | Sep 03, 2022 |
| Acer          | Nitro AN515-42              | [74cdbd53f7](https://linux-hardware.org/?probe=74cdbd53f7) | Sep 03, 2022 |
| Dell          | Inspiron 5566               | [3c2359f16d](https://linux-hardware.org/?probe=3c2359f16d) | Sep 03, 2022 |
| Intel Clie... | LAPQC71A                    | [9bc39724f8](https://linux-hardware.org/?probe=9bc39724f8) | Sep 02, 2022 |
| MSI           | Delta 15 A5EFK              | [b7de6bff83](https://linux-hardware.org/?probe=b7de6bff83) | Sep 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [9cabeefea8](https://linux-hardware.org/?probe=9cabeefea8) | Sep 01, 2022 |
| Unknown       | Unknown                     | [cba954794c](https://linux-hardware.org/?probe=cba954794c) | Aug 31, 2022 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | [df1e70349c](https://linux-hardware.org/?probe=df1e70349c) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6f169db96b](https://linux-hardware.org/?probe=6f169db96b) | Aug 29, 2022 |
| Lenovo        | V14-ADA 82C6                | [1d3dfbba56](https://linux-hardware.org/?probe=1d3dfbba56) | Aug 27, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [4384be22c4](https://linux-hardware.org/?probe=4384be22c4) | Aug 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [85e0bc5d57](https://linux-hardware.org/?probe=85e0bc5d57) | Aug 27, 2022 |
| Lenovo        | G580 20150                  | [1813b94682](https://linux-hardware.org/?probe=1813b94682) | Aug 27, 2022 |
| Dell          | Vostro 5625                 | [741abbfe3d](https://linux-hardware.org/?probe=741abbfe3d) | Aug 26, 2022 |
| Lenovo        | ThinkPad E580 20KS003GMH    | [5cadf3c5d2](https://linux-hardware.org/?probe=5cadf3c5d2) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [d988e1aeb9](https://linux-hardware.org/?probe=d988e1aeb9) | Aug 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9e3b6f2140](https://linux-hardware.org/?probe=9e3b6f2140) | Aug 24, 2022 |
| Dell          | Inspiron 5505               | [4ea2e79611](https://linux-hardware.org/?probe=4ea2e79611) | Aug 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [15960dc164](https://linux-hardware.org/?probe=15960dc164) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [eed44ba087](https://linux-hardware.org/?probe=eed44ba087) | Aug 24, 2022 |
| ASUSTek       | X202E                       | [b814b9f427](https://linux-hardware.org/?probe=b814b9f427) | Aug 24, 2022 |
| Dell          | XPS 15 9520                 | [e4f7ce1ec7](https://linux-hardware.org/?probe=e4f7ce1ec7) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [beb772b7f1](https://linux-hardware.org/?probe=beb772b7f1) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| HP            | Laptop 14-dq1xxx            | [975461703e](https://linux-hardware.org/?probe=975461703e) | Aug 23, 2022 |
| Acer          | Aspire A515-43              | [bc23fbec2a](https://linux-hardware.org/?probe=bc23fbec2a) | Aug 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [47cae9ef99](https://linux-hardware.org/?probe=47cae9ef99) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| HP            | ENVY m6 Notebook            | [c51af546e7](https://linux-hardware.org/?probe=c51af546e7) | Aug 22, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [64b9832653](https://linux-hardware.org/?probe=64b9832653) | Aug 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77a2156c5a](https://linux-hardware.org/?probe=77a2156c5a) | Aug 21, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [32e59cda1c](https://linux-hardware.org/?probe=32e59cda1c) | Aug 20, 2022 |
| Acer          | Aspire R3-131T              | [3f6370f978](https://linux-hardware.org/?probe=3f6370f978) | Aug 20, 2022 |
| Dell          | Latitude 5290 2-in-1        | [bafc4d3392](https://linux-hardware.org/?probe=bafc4d3392) | Aug 20, 2022 |
| HP            | ProBook 450 G7              | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [fdcb40d147](https://linux-hardware.org/?probe=fdcb40d147) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [cf5500d7b1](https://linux-hardware.org/?probe=cf5500d7b1) | Aug 18, 2022 |
| HUAWEI        | MACHC-WAX9                  | [95a5dd6af3](https://linux-hardware.org/?probe=95a5dd6af3) | Aug 18, 2022 |
| HUAWEI        | MACHC-WAX9                  | [0a9d130f45](https://linux-hardware.org/?probe=0a9d130f45) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| HP            | Dratini                     | [134a2600be](https://linux-hardware.org/?probe=134a2600be) | Aug 16, 2022 |
| HP            | EliteBook 755 G5            | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [c3fee5819a](https://linux-hardware.org/?probe=c3fee5819a) | Aug 14, 2022 |
| HP            | EliteBook 2760p             | [bb4c1e4c3a](https://linux-hardware.org/?probe=bb4c1e4c3a) | Aug 13, 2022 |
| Lenovo        | IdeaPad 3 15IML05 D1 81W... | [59b3324e73](https://linux-hardware.org/?probe=59b3324e73) | Aug 13, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [6b83355dfa](https://linux-hardware.org/?probe=6b83355dfa) | Aug 13, 2022 |
| MSI           | GE75 Raider 10SF            | [0fafeaaa76](https://linux-hardware.org/?probe=0fafeaaa76) | Aug 13, 2022 |
| HP            | EliteBook 8460p             | [b7418c601b](https://linux-hardware.org/?probe=b7418c601b) | Aug 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [601732f75e](https://linux-hardware.org/?probe=601732f75e) | Aug 13, 2022 |
| Dell          | Precision M6600             | [9c860085a8](https://linux-hardware.org/?probe=9c860085a8) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [59892dec35](https://linux-hardware.org/?probe=59892dec35) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [2f45536688](https://linux-hardware.org/?probe=2f45536688) | Aug 12, 2022 |
| Lenovo        | Z710 20250                  | [8c7b1d0773](https://linux-hardware.org/?probe=8c7b1d0773) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [6a07e79eb7](https://linux-hardware.org/?probe=6a07e79eb7) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [7e83b07cca](https://linux-hardware.org/?probe=7e83b07cca) | Aug 11, 2022 |
| HP            | 255 G4                      | [3ed3978b93](https://linux-hardware.org/?probe=3ed3978b93) | Aug 11, 2022 |
| Dell          | Latitude 5421               | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| ASUSTek       | ROG Strix G513QR            | [3b19026468](https://linux-hardware.org/?probe=3b19026468) | Aug 09, 2022 |
| Acer          | Aspire 5732Z                | [20746ad23d](https://linux-hardware.org/?probe=20746ad23d) | Aug 09, 2022 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [7dab66307c](https://linux-hardware.org/?probe=7dab66307c) | Aug 09, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [49f045d747](https://linux-hardware.org/?probe=49f045d747) | Aug 09, 2022 |
| ASUSTek       | ROG Strix G513QR            | [7aa074e467](https://linux-hardware.org/?probe=7aa074e467) | Aug 08, 2022 |
| HP            | Laptop 15-dw3xxx            | [e7a185eb28](https://linux-hardware.org/?probe=e7a185eb28) | Aug 08, 2022 |
| Razer         | Blade                       | [e2d9f80c98](https://linux-hardware.org/?probe=e2d9f80c98) | Aug 08, 2022 |
| HP            | Laptop 15-dw3xxx            | [7d20ee4549](https://linux-hardware.org/?probe=7d20ee4549) | Aug 08, 2022 |
| Framework     | Laptop                      | [da39a41b6b](https://linux-hardware.org/?probe=da39a41b6b) | Aug 08, 2022 |
| Framework     | Laptop                      | [f754ffd1d1](https://linux-hardware.org/?probe=f754ffd1d1) | Aug 08, 2022 |
| Dell          | XPS 15 9500                 | [d8486d3371](https://linux-hardware.org/?probe=d8486d3371) | Aug 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [c4a323d350](https://linux-hardware.org/?probe=c4a323d350) | Aug 06, 2022 |
| MSI           | GS66 Stealth 10SGS          | [24fbb2877c](https://linux-hardware.org/?probe=24fbb2877c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS3UW00    | [ddefadf8f1](https://linux-hardware.org/?probe=ddefadf8f1) | Aug 06, 2022 |
| Google        | Blorb                       | [b893b34702](https://linux-hardware.org/?probe=b893b34702) | Aug 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7151e1746a](https://linux-hardware.org/?probe=7151e1746a) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [66c9a8d0f6](https://linux-hardware.org/?probe=66c9a8d0f6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [417c72557c](https://linux-hardware.org/?probe=417c72557c) | Aug 05, 2022 |
| GPD           | G1621-02                    | [58586a10a3](https://linux-hardware.org/?probe=58586a10a3) | Aug 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0ef9fef16d](https://linux-hardware.org/?probe=0ef9fef16d) | Aug 04, 2022 |
| Dell          | XPS 15 9500                 | [840cb1763f](https://linux-hardware.org/?probe=840cb1763f) | Aug 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ed6b6ce93e](https://linux-hardware.org/?probe=ed6b6ce93e) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8f15b50066](https://linux-hardware.org/?probe=8f15b50066) | Aug 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Daten Tecn... | DT02-M4                     | [1dfd4fe5ba](https://linux-hardware.org/?probe=1dfd4fe5ba) | Aug 03, 2022 |
| Dell          | XPS 13 7390                 | [05e8b8d782](https://linux-hardware.org/?probe=05e8b8d782) | Aug 03, 2022 |
| Dell          | Latitude 7490               | [0df5a838bf](https://linux-hardware.org/?probe=0df5a838bf) | Aug 03, 2022 |
| Timi          | RedmiBook 14                | [10c33f11cf](https://linux-hardware.org/?probe=10c33f11cf) | Aug 02, 2022 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [c2520e642a](https://linux-hardware.org/?probe=c2520e642a) | Aug 02, 2022 |
| HP            | Unknown                     | [bd6c9221e7](https://linux-hardware.org/?probe=bd6c9221e7) | Aug 02, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [7b597ebcc8](https://linux-hardware.org/?probe=7b597ebcc8) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Dell          | G15 Special Edition 5521    | [c680e6f144](https://linux-hardware.org/?probe=c680e6f144) | Aug 01, 2022 |
| Dell          | Latitude 5290 2-in-1        | [838be3a87a](https://linux-hardware.org/?probe=838be3a87a) | Jul 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Dell          | Inspiron 5520               | [a4baade53f](https://linux-hardware.org/?probe=a4baade53f) | Jul 30, 2022 |
| Dell          | Inspiron 7577               | [a2909a87b1](https://linux-hardware.org/?probe=a2909a87b1) | Jul 30, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [aa446a0409](https://linux-hardware.org/?probe=aa446a0409) | Jul 29, 2022 |
| Dell          | Latitude 5290 2-in-1        | [8d93753bc7](https://linux-hardware.org/?probe=8d93753bc7) | Jul 29, 2022 |
| Dell          | Latitude 5290 2-in-1        | [910241c92e](https://linux-hardware.org/?probe=910241c92e) | Jul 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [fdb481a551](https://linux-hardware.org/?probe=fdb481a551) | Jul 28, 2022 |
| Acer          | Aspire A515-43              | [230cf1bf3d](https://linux-hardware.org/?probe=230cf1bf3d) | Jul 28, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | [d73469794d](https://linux-hardware.org/?probe=d73469794d) | Jul 28, 2022 |
| Alienware     | 17                          | [6a4212d19d](https://linux-hardware.org/?probe=6a4212d19d) | Jul 27, 2022 |
| Dell          | Inspiron 5502               | [f84c29c4b6](https://linux-hardware.org/?probe=f84c29c4b6) | Jul 27, 2022 |
| Lenovo        | ThinkPad T480s 20L8S31T0... | [60449c872b](https://linux-hardware.org/?probe=60449c872b) | Jul 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f4f4bdfefd](https://linux-hardware.org/?probe=f4f4bdfefd) | Jul 27, 2022 |
| MSI           | GF63 Thin 9SC               | [6d42baa166](https://linux-hardware.org/?probe=6d42baa166) | Jul 26, 2022 |
| Lenovo        | ThinkPad E585 20KV000YUS    | [0c8cde264e](https://linux-hardware.org/?probe=0c8cde264e) | Jul 26, 2022 |
| Acer          | Aspire A315-42              | [78415dc6be](https://linux-hardware.org/?probe=78415dc6be) | Jul 25, 2022 |
| Acer          | Predator PH315-52           | [a1346acc8a](https://linux-hardware.org/?probe=a1346acc8a) | Jul 25, 2022 |
| Dell          | Inspiron 15-5578            | [7621729bff](https://linux-hardware.org/?probe=7621729bff) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [123fc55893](https://linux-hardware.org/?probe=123fc55893) | Jul 24, 2022 |
| MSI           | GF63 Thin 9SC               | [1a2403b95a](https://linux-hardware.org/?probe=1a2403b95a) | Jul 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| ASUSTek       | Q504UA                      | [373dce5a6f](https://linux-hardware.org/?probe=373dce5a6f) | Jul 24, 2022 |
| System76      | Serval WS                   | [18259132ff](https://linux-hardware.org/?probe=18259132ff) | Jul 22, 2022 |
| MSI           | GS66 Stealth 10SGS          | [8d7172fe7e](https://linux-hardware.org/?probe=8d7172fe7e) | Jul 22, 2022 |
| ASUSTek       | X450LCP                     | [0617861116](https://linux-hardware.org/?probe=0617861116) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [4e47525879](https://linux-hardware.org/?probe=4e47525879) | Jul 22, 2022 |
| Lenovo        | IdeaPad U330p 20267         | [1775f75940](https://linux-hardware.org/?probe=1775f75940) | Jul 22, 2022 |
| HP            | ZBook 15 G5                 | [771428353e](https://linux-hardware.org/?probe=771428353e) | Jul 21, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [e632ef83da](https://linux-hardware.org/?probe=e632ef83da) | Jul 20, 2022 |
| HP            | EliteBook 840 G5            | [03afe0a303](https://linux-hardware.org/?probe=03afe0a303) | Jul 20, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [5859932a73](https://linux-hardware.org/?probe=5859932a73) | Jul 20, 2022 |
| Dell          | Vostro 15 3510              | [8327d57f7b](https://linux-hardware.org/?probe=8327d57f7b) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [29847a6864](https://linux-hardware.org/?probe=29847a6864) | Jul 20, 2022 |
| Lenovo        | ThinkPad E585 20KVCTO1WW    | [0602b2d850](https://linux-hardware.org/?probe=0602b2d850) | Jul 19, 2022 |
| Dell          | Latitude E5530 non-vPro     | [27a607d6ba](https://linux-hardware.org/?probe=27a607d6ba) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Apple         | MacBookPro14,2              | [4f1ce227b5](https://linux-hardware.org/?probe=4f1ce227b5) | Jul 18, 2022 |
| Dell          | Inspiron 3421               | [d4c15eb5fd](https://linux-hardware.org/?probe=d4c15eb5fd) | Jul 18, 2022 |
| Lenovo        | ThinkPad SL510 28479XU      | [092a752a62](https://linux-hardware.org/?probe=092a752a62) | Jul 18, 2022 |
| Lenovo        | ThinkPad SL510 28479XU      | [5eea2f8d37](https://linux-hardware.org/?probe=5eea2f8d37) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | [75cfb6ffa8](https://linux-hardware.org/?probe=75cfb6ffa8) | Jul 17, 2022 |
| Dell          | Latitude 7490               | [bed5644964](https://linux-hardware.org/?probe=bed5644964) | Jul 17, 2022 |
| HP            | Laptop 15-dy0xxx            | [cfd2b5a69c](https://linux-hardware.org/?probe=cfd2b5a69c) | Jul 17, 2022 |
| Schenker      | XMG PRO (Late 2021)         | [a59796b464](https://linux-hardware.org/?probe=a59796b464) | Jul 17, 2022 |
| Schenker      | XMG PRO (Late 2021)         | [d739731ef5](https://linux-hardware.org/?probe=d739731ef5) | Jul 17, 2022 |
| Google        | Coral                       | [ebf34e57e6](https://linux-hardware.org/?probe=ebf34e57e6) | Jul 17, 2022 |
| HP            | ProBook 4520s               | [580f66ae82](https://linux-hardware.org/?probe=580f66ae82) | Jul 16, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [1bb517b788](https://linux-hardware.org/?probe=1bb517b788) | Jul 16, 2022 |
| ASUSTek       | N552VW                      | [b29b2f27df](https://linux-hardware.org/?probe=b29b2f27df) | Jul 16, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [aa025d852d](https://linux-hardware.org/?probe=aa025d852d) | Jul 16, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [27f6399025](https://linux-hardware.org/?probe=27f6399025) | Jul 16, 2022 |
| ASUSTek       | X555LN                      | [0d6d6728ba](https://linux-hardware.org/?probe=0d6d6728ba) | Jul 15, 2022 |
| Chuwi         | HeroBook Air                | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| HP            | Laptop 17-cp0xxx            | [476ab880f4](https://linux-hardware.org/?probe=476ab880f4) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| Lenovo        | G580 20150                  | [d6b737940e](https://linux-hardware.org/?probe=d6b737940e) | Jul 15, 2022 |
| Apple         | MacBookAir6,2               | [fe231e27cf](https://linux-hardware.org/?probe=fe231e27cf) | Jul 14, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [367adf8f50](https://linux-hardware.org/?probe=367adf8f50) | Jul 14, 2022 |
| HP            | Laptop 15-dy0xxx            | [a7eb387b79](https://linux-hardware.org/?probe=a7eb387b79) | Jul 14, 2022 |
| Chuwi         | HeroBook Air                | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [f764827707](https://linux-hardware.org/?probe=f764827707) | Jul 13, 2022 |
| Dell          | Inspiron 7460               | [316285fb12](https://linux-hardware.org/?probe=316285fb12) | Jul 13, 2022 |
| Dell          | XPS 15 9510                 | [3207d8f9e9](https://linux-hardware.org/?probe=3207d8f9e9) | Jul 12, 2022 |
| Dell          | XPS 15 9510                 | [0f3d24f508](https://linux-hardware.org/?probe=0f3d24f508) | Jul 12, 2022 |
| HUAWEI        | KLVL-WXXW                   | [ded0cc5604](https://linux-hardware.org/?probe=ded0cc5604) | Jul 12, 2022 |
| Acer          | Aspire ES1-523              | [109bec9fa8](https://linux-hardware.org/?probe=109bec9fa8) | Jul 12, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Lenovo        | ThinkPad L470 20J5S01L00    | [401e13e2a6](https://linux-hardware.org/?probe=401e13e2a6) | Jul 12, 2022 |
| ASUSTek       | X202E                       | [102f50d1a3](https://linux-hardware.org/?probe=102f50d1a3) | Jul 12, 2022 |
| Apple         | MacBookPro14,1              | [32cbf49371](https://linux-hardware.org/?probe=32cbf49371) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [98d0043f0e](https://linux-hardware.org/?probe=98d0043f0e) | Jul 10, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [b0f6891a0b](https://linux-hardware.org/?probe=b0f6891a0b) | Jul 10, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [5d31b181fd](https://linux-hardware.org/?probe=5d31b181fd) | Jul 10, 2022 |
| Timi          | TM1701                      | [8786fe1e91](https://linux-hardware.org/?probe=8786fe1e91) | Jul 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ec2174a329](https://linux-hardware.org/?probe=ec2174a329) | Jul 10, 2022 |
| HP            | EliteBook 8540p             | [b161f9e458](https://linux-hardware.org/?probe=b161f9e458) | Jul 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [567077c28d](https://linux-hardware.org/?probe=567077c28d) | Jul 08, 2022 |
| Dell          | XPS 13 9333                 | [e464cd5823](https://linux-hardware.org/?probe=e464cd5823) | Jul 08, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [5fa7449343](https://linux-hardware.org/?probe=5fa7449343) | Jul 08, 2022 |
| HP            | ProBook 4540s               | [6b67ccac52](https://linux-hardware.org/?probe=6b67ccac52) | Jul 08, 2022 |
| Lenovo        | ThinkPad X230 2325TXB       | [1bf8e19c53](https://linux-hardware.org/?probe=1bf8e19c53) | Jul 08, 2022 |
| Dell          | Latitude E6430              | [9375063ae6](https://linux-hardware.org/?probe=9375063ae6) | Jul 08, 2022 |
| Acer          | Swift SF514-54GT            | [554171275d](https://linux-hardware.org/?probe=554171275d) | Jul 07, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [c9eb8f9a5f](https://linux-hardware.org/?probe=c9eb8f9a5f) | Jul 07, 2022 |
| Dell          | Inspiron 7572               | [e249d01b2b](https://linux-hardware.org/?probe=e249d01b2b) | Jul 06, 2022 |
| HUAWEI        | VLT-WX0                     | [9467db0d89](https://linux-hardware.org/?probe=9467db0d89) | Jul 06, 2022 |
| Toshiba       | Satellite A100              | [460363ac20](https://linux-hardware.org/?probe=460363ac20) | Jul 06, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d58dd09f25](https://linux-hardware.org/?probe=d58dd09f25) | Jul 06, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [53417c8761](https://linux-hardware.org/?probe=53417c8761) | Jul 06, 2022 |
| Toshiba       | Satellite A100              | [2b25713a3d](https://linux-hardware.org/?probe=2b25713a3d) | Jul 05, 2022 |
| HP            | ProBook 430 G6              | [4281fab7fd](https://linux-hardware.org/?probe=4281fab7fd) | Jul 05, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [61d8d4b071](https://linux-hardware.org/?probe=61d8d4b071) | Jul 05, 2022 |
| HP            | Pavilion g6                 | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Dell          | Latitude E6410              | [51fa58eb7d](https://linux-hardware.org/?probe=51fa58eb7d) | Jul 05, 2022 |
| Dell          | Inspiron 1764               | [3fa5f4d0a8](https://linux-hardware.org/?probe=3fa5f4d0a8) | Jul 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d285ee1f39](https://linux-hardware.org/?probe=d285ee1f39) | Jul 05, 2022 |
| Sony          | VJF153                      | [a1efa9107c](https://linux-hardware.org/?probe=a1efa9107c) | Jul 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7d1eafc534](https://linux-hardware.org/?probe=7d1eafc534) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [341512bec5](https://linux-hardware.org/?probe=341512bec5) | Jul 04, 2022 |
| LG Electro... | 17Z90N-V.AA55A1             | [272164819f](https://linux-hardware.org/?probe=272164819f) | Jul 04, 2022 |
| ASUSTek       | X55U                        | [ed55b4ef39](https://linux-hardware.org/?probe=ed55b4ef39) | Jul 03, 2022 |
| Dell          | XPS 15 9570                 | [f5b850a82c](https://linux-hardware.org/?probe=f5b850a82c) | Jul 03, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [9e7e4a5d8d](https://linux-hardware.org/?probe=9e7e4a5d8d) | Jul 03, 2022 |
| Timi          | Mi NoteBook Pro             | [046a18dc14](https://linux-hardware.org/?probe=046a18dc14) | Jul 03, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [c55ade019d](https://linux-hardware.org/?probe=c55ade019d) | Jul 02, 2022 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | [d90a910042](https://linux-hardware.org/?probe=d90a910042) | Jul 02, 2022 |
| Dell          | Latitude E6410              | [325a691029](https://linux-hardware.org/?probe=325a691029) | Jul 02, 2022 |
| TENKU         | SB14                        | [cbe2900f4f](https://linux-hardware.org/?probe=cbe2900f4f) | Jul 02, 2022 |
| HP            | ProBook 440 G4              | [ffaa37530b](https://linux-hardware.org/?probe=ffaa37530b) | Jul 02, 2022 |
| HP            | ProBook 4540s               | [c47e971697](https://linux-hardware.org/?probe=c47e971697) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [9034bf7260](https://linux-hardware.org/?probe=9034bf7260) | Jul 01, 2022 |
| Dell          | Inspiron 1764               | [dd5c77d711](https://linux-hardware.org/?probe=dd5c77d711) | Jul 01, 2022 |
| Chuwi         | HeroBook Air                | [217dcb770c](https://linux-hardware.org/?probe=217dcb770c) | Jul 01, 2022 |
| Dell          | Inspiron 5520               | [15b5edddd3](https://linux-hardware.org/?probe=15b5edddd3) | Jun 30, 2022 |
| Lenovo        | G580 20150                  | [dbe5fe496a](https://linux-hardware.org/?probe=dbe5fe496a) | Jun 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [53842b1b7d](https://linux-hardware.org/?probe=53842b1b7d) | Jun 29, 2022 |
| Dell          | Latitude 3590               | [b5d4509068](https://linux-hardware.org/?probe=b5d4509068) | Jun 29, 2022 |
| Dell          | Inspiron 3593               | [5b091180ec](https://linux-hardware.org/?probe=5b091180ec) | Jun 28, 2022 |
| SLIMBOOK      | PROX14-AMD                  | [1b58bbb69c](https://linux-hardware.org/?probe=1b58bbb69c) | Jun 28, 2022 |
| ASUSTek       | X507UB                      | [0ba0fc4089](https://linux-hardware.org/?probe=0ba0fc4089) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [ec155fca3f](https://linux-hardware.org/?probe=ec155fca3f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [016ee6ec73](https://linux-hardware.org/?probe=016ee6ec73) | Jun 28, 2022 |
| HP            | Laptop 14s-fq0xxx           | [c442dd3af1](https://linux-hardware.org/?probe=c442dd3af1) | Jun 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [95db2f9536](https://linux-hardware.org/?probe=95db2f9536) | Jun 27, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [78eaeff700](https://linux-hardware.org/?probe=78eaeff700) | Jun 27, 2022 |
| Fujitsu       | LIFEBOOK A512               | [8fb8607282](https://linux-hardware.org/?probe=8fb8607282) | Jun 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [2595b295a9](https://linux-hardware.org/?probe=2595b295a9) | Jun 27, 2022 |
| Intel Clie... | LAPKC71F                    | [1a50f7c080](https://linux-hardware.org/?probe=1a50f7c080) | Jun 27, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8a6b59bd5d](https://linux-hardware.org/?probe=8a6b59bd5d) | Jun 25, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9d53805c9a](https://linux-hardware.org/?probe=9d53805c9a) | Jun 25, 2022 |
| Sony          | VPCF236FM                   | [b2af243689](https://linux-hardware.org/?probe=b2af243689) | Jun 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [072acf05a0](https://linux-hardware.org/?probe=072acf05a0) | Jun 24, 2022 |
| Lenovo        | Legion 5 82B5               | [f0b00bb55e](https://linux-hardware.org/?probe=f0b00bb55e) | Jun 24, 2022 |
| Lenovo        | ThinkPad S2 20GJA00S00      | [44eb58334d](https://linux-hardware.org/?probe=44eb58334d) | Jun 24, 2022 |
| LG Electro... | 14Z90N-VA76K                | [9e606a176f](https://linux-hardware.org/?probe=9e606a176f) | Jun 24, 2022 |
| ASUSTek       | X751LK                      | [d7f4b1678b](https://linux-hardware.org/?probe=d7f4b1678b) | Jun 24, 2022 |
| ASUSTek       | X751LK                      | [09dfab066c](https://linux-hardware.org/?probe=09dfab066c) | Jun 24, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [97222f18a0](https://linux-hardware.org/?probe=97222f18a0) | Jun 23, 2022 |
| HP            | EliteBook 8470p             | [2ba22aa099](https://linux-hardware.org/?probe=2ba22aa099) | Jun 22, 2022 |
| HP            | EliteBook 8470p             | [eea8da46bd](https://linux-hardware.org/?probe=eea8da46bd) | Jun 22, 2022 |
| Dell          | Vostro 5470                 | [9a5e42fa6f](https://linux-hardware.org/?probe=9a5e42fa6f) | Jun 22, 2022 |
| Lenovo        | ThinkPad T420 4177Q5U       | [cf27027c76](https://linux-hardware.org/?probe=cf27027c76) | Jun 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [887fcf4e6d](https://linux-hardware.org/?probe=887fcf4e6d) | Jun 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [9715c826f4](https://linux-hardware.org/?probe=9715c826f4) | Jun 21, 2022 |
| HP            | Laptop 15-bs0xx             | [30befabf68](https://linux-hardware.org/?probe=30befabf68) | Jun 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f3ebefa03f](https://linux-hardware.org/?probe=f3ebefa03f) | Jun 21, 2022 |
| Dell          | Latitude 3590               | [fdfd4be1e2](https://linux-hardware.org/?probe=fdfd4be1e2) | Jun 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [fd65aaa4b3](https://linux-hardware.org/?probe=fd65aaa4b3) | Jun 21, 2022 |
| System76      | Lemur Pro                   | [81f0e790fd](https://linux-hardware.org/?probe=81f0e790fd) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [87abe6b88c](https://linux-hardware.org/?probe=87abe6b88c) | Jun 20, 2022 |
| Razer         | Blade 15 Advanced Model ... | [de5d975c12](https://linux-hardware.org/?probe=de5d975c12) | Jun 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [fd1361c7b9](https://linux-hardware.org/?probe=fd1361c7b9) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b3da04a3af](https://linux-hardware.org/?probe=b3da04a3af) | Jun 20, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [385b65c320](https://linux-hardware.org/?probe=385b65c320) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| MSI           | GE75 Raider 10SF            | [eee0889229](https://linux-hardware.org/?probe=eee0889229) | Jun 19, 2022 |
| Samsung       | 300E5M/300E5L               | [9191469ae0](https://linux-hardware.org/?probe=9191469ae0) | Jun 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [4e35a154b5](https://linux-hardware.org/?probe=4e35a154b5) | Jun 18, 2022 |
| Dell          | Inspiron 7437               | [2ac68c5d39](https://linux-hardware.org/?probe=2ac68c5d39) | Jun 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6dfa236f76](https://linux-hardware.org/?probe=6dfa236f76) | Jun 18, 2022 |
| HP            | 255 G8 Notebook PC          | [cae0332804](https://linux-hardware.org/?probe=cae0332804) | Jun 17, 2022 |
| HP            | 255 G8 Notebook PC          | [e65ead281f](https://linux-hardware.org/?probe=e65ead281f) | Jun 17, 2022 |
| Dell          | Latitude E7440              | [41acc5e2ba](https://linux-hardware.org/?probe=41acc5e2ba) | Jun 17, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [6941a8232a](https://linux-hardware.org/?probe=6941a8232a) | Jun 17, 2022 |
| HP            | EliteBook 8470p             | [f72ab26d6f](https://linux-hardware.org/?probe=f72ab26d6f) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| HP            | Pavilion Notebook           | [06c982ad14](https://linux-hardware.org/?probe=06c982ad14) | Jun 16, 2022 |
| HONOR         | BMH-WCX9                    | [0ddbf275c2](https://linux-hardware.org/?probe=0ddbf275c2) | Jun 16, 2022 |
| Dell          | Latitude E7440              | [612f30d834](https://linux-hardware.org/?probe=612f30d834) | Jun 16, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [8e0da08d4d](https://linux-hardware.org/?probe=8e0da08d4d) | Jun 15, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [cf4df37657](https://linux-hardware.org/?probe=cf4df37657) | Jun 15, 2022 |
| HP            | EliteBook 840 G5            | [33f68db1fa](https://linux-hardware.org/?probe=33f68db1fa) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [32adc7acf9](https://linux-hardware.org/?probe=32adc7acf9) | Jun 15, 2022 |
| MSI           | GP60 2OD                    | [6edff2c2ad](https://linux-hardware.org/?probe=6edff2c2ad) | Jun 14, 2022 |
| Lenovo        | ThinkPad T550 20CK003HMD    | [ea8155f580](https://linux-hardware.org/?probe=ea8155f580) | Jun 14, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [f4c7f13ff8](https://linux-hardware.org/?probe=f4c7f13ff8) | Jun 14, 2022 |
| HP            | Laptop 15-dy0xxx            | [d63a037918](https://linux-hardware.org/?probe=d63a037918) | Jun 14, 2022 |
| ASUSTek       | G751JT                      | [208fe1ea69](https://linux-hardware.org/?probe=208fe1ea69) | Jun 14, 2022 |
| HP            | EliteBook 850 G2            | [10b796ad9c](https://linux-hardware.org/?probe=10b796ad9c) | Jun 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [e26e612120](https://linux-hardware.org/?probe=e26e612120) | Jun 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [cbf5603095](https://linux-hardware.org/?probe=cbf5603095) | Jun 13, 2022 |
| Dell          | XPS 15 9500                 | [197482fd83](https://linux-hardware.org/?probe=197482fd83) | Jun 13, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5c07fd1664](https://linux-hardware.org/?probe=5c07fd1664) | Jun 12, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [44704fc87d](https://linux-hardware.org/?probe=44704fc87d) | Jun 12, 2022 |
| HP            | ProBook 455 G7              | [60bf6f8388](https://linux-hardware.org/?probe=60bf6f8388) | Jun 12, 2022 |
| Dell          | Latitude E7440              | [d2861687ff](https://linux-hardware.org/?probe=d2861687ff) | Jun 12, 2022 |
| Dell          | Latitude E6410              | [005799b9bf](https://linux-hardware.org/?probe=005799b9bf) | Jun 12, 2022 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | [9382b4e2c0](https://linux-hardware.org/?probe=9382b4e2c0) | Jun 12, 2022 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | [06526726ca](https://linux-hardware.org/?probe=06526726ca) | Jun 11, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [82258ff9e9](https://linux-hardware.org/?probe=82258ff9e9) | Jun 11, 2022 |
| HP            | Laptop 17-cn0xxx            | [f1791f8dd5](https://linux-hardware.org/?probe=f1791f8dd5) | Jun 11, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [29bf5546d5](https://linux-hardware.org/?probe=29bf5546d5) | Jun 10, 2022 |
| HP            | Laptop 15s-fq3xxx           | [d3a75d599a](https://linux-hardware.org/?probe=d3a75d599a) | Jun 10, 2022 |
| Dell          | Latitude E6420              | [a92cd16ef7](https://linux-hardware.org/?probe=a92cd16ef7) | Jun 10, 2022 |
| Lenovo        | ThinkPad X250 20CLS06L00    | [11202fb63f](https://linux-hardware.org/?probe=11202fb63f) | Jun 09, 2022 |
| ASUSTek       | X550VXK                     | [5820774a86](https://linux-hardware.org/?probe=5820774a86) | Jun 08, 2022 |
| Dell          | Vostro 3560                 | [4faa4230bd](https://linux-hardware.org/?probe=4faa4230bd) | Jun 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Manjaro        | 1385      | 36.88%  |
| Manjaro 22.0.0 | 188       | 5.01%   |
| Manjaro 20.2.1 | 163       | 4.34%   |
| Manjaro 20.1   | 142       | 3.78%   |
| Manjaro 20.2   | 140       | 3.73%   |
| Manjaro 20.0.3 | 125       | 3.33%   |
| Manjaro 21.2.6 | 113       | 3.01%   |
| Manjaro 21.1.0 | 89        | 2.37%   |
| Manjaro 18.1.5 | 83        | 2.21%   |
| Manjaro 21.2.0 | 72        | 1.92%   |
| Manjaro 21.0.7 | 70        | 1.86%   |
| Manjaro 21.2.5 | 65        | 1.73%   |
| Manjaro 21.1.6 | 63        | 1.68%   |
| Manjaro 19.0.2 | 55        | 1.46%   |
| Manjaro 20.0   | 52        | 1.38%   |
| Manjaro 21.2.1 | 48        | 1.28%   |
| Manjaro 18.0.4 | 47        | 1.25%   |
| Manjaro 21.0   | 46        | 1.23%   |
| Manjaro 21.0.5 | 44        | 1.17%   |
| Manjaro 20.1.1 | 41        | 1.09%   |
| Manjaro 20.1.2 | 40        | 1.07%   |
| Manjaro 21.2.3 | 37        | 0.99%   |
| Manjaro 20.0.1 | 36        | 0.96%   |
| Manjaro 21.3.7 | 34        | 0.91%   |
| Manjaro 21.2.2 | 31        | 0.83%   |
| Manjaro 21.0.4 | 31        | 0.83%   |
| Manjaro 21.3.6 | 29        | 0.77%   |
| Manjaro 21.2.4 | 29        | 0.77%   |
| Manjaro 21.1.2 | 25        | 0.67%   |
| Manjaro 21.1.4 | 24        | 0.64%   |
| Manjaro 21.0.1 | 20        | 0.53%   |
| Manjaro 18.1.4 | 20        | 0.53%   |
| Manjaro 21.3.1 | 19        | 0.51%   |
| Manjaro 21.3.0 | 19        | 0.51%   |
| Manjaro 21.1.3 | 19        | 0.51%   |
| Manjaro 21.1.1 | 19        | 0.51%   |
| Manjaro 21.0.2 | 17        | 0.45%   |
| Manjaro 22.0.1 | 16        | 0.43%   |
| Manjaro 21.0.3 | 16        | 0.43%   |
| Manjaro 21.3.2 | 15        | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Manjaro | 3451      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 161       | 3.99%   |
| 5.13.19-2-MANJARO | 95        | 2.36%   |
| 5.9.11-3-MANJARO  | 73        | 1.81%   |
| 5.8.11-1-MANJARO  | 69        | 1.71%   |
| 5.8.6-1-MANJARO   | 68        | 1.69%   |
| 5.15.32-1-MANJARO | 63        | 1.56%   |
| 5.15.28-1-MANJARO | 61        | 1.51%   |
| 5.10.42-1-MANJARO | 57        | 1.41%   |
| 5.8.18-1-MANJARO  | 55        | 1.36%   |
| 5.15.12-1-MANJARO | 52        | 1.29%   |
| 6.1.1-1-MANJARO   | 51        | 1.26%   |
| 5.8.16-2-MANJARO  | 41        | 1.02%   |
| 5.15.65-1-MANJARO | 40        | 0.99%   |
| 5.10.2-2-MANJARO  | 40        | 0.99%   |
| 5.6.16-1-MANJARO  | 39        | 0.97%   |
| 5.15.60-1-MANJARO | 39        | 0.97%   |
| 5.10.7-3-MANJARO  | 38        | 0.94%   |
| 5.12.9-1-MANJARO  | 36        | 0.89%   |
| 5.6.19-2-MANJARO  | 33        | 0.82%   |
| 5.15.74-3-MANJARO | 31        | 0.77%   |
| 5.15.7-1-MANJARO  | 31        | 0.77%   |
| 5.7.9-1-MANJARO   | 30        | 0.74%   |
| 5.6.15-1-MANJARO  | 30        | 0.74%   |
| 5.15.81-1-MANJARO | 30        | 0.74%   |
| 5.15.78-1-MANJARO | 30        | 0.74%   |
| 5.15.41-1-MANJARO | 30        | 0.74%   |
| 5.10.36-2-MANJARO | 30        | 0.74%   |
| 5.7.17-2-MANJARO  | 29        | 0.72%   |
| 5.7.0-3-MANJARO   | 29        | 0.72%   |
| 5.8.3-2-MANJARO   | 28        | 0.69%   |
| 5.15.25-1-MANJARO | 28        | 0.69%   |
| 5.14.10-1-MANJARO | 28        | 0.69%   |
| 5.10.34-1-MANJARO | 27        | 0.67%   |
| 5.16.14-1-MANJARO | 25        | 0.62%   |
| 5.15.85-1-MANJARO | 25        | 0.62%   |
| 5.10.70-1-MANJARO | 25        | 0.62%   |
| 5.10.53-1-MANJARO | 25        | 0.62%   |
| 5.9.3-1-MANJARO   | 23        | 0.57%   |
| 5.17.1-3-MANJARO  | 23        | 0.57%   |
| 5.15.38-1-MANJARO | 23        | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.16  | 161       | 4%      |
| 5.13.19 | 96        | 2.38%   |
| 5.9.11  | 77        | 1.91%   |
| 5.8.11  | 69        | 1.71%   |
| 5.8.6   | 68        | 1.69%   |
| 5.15.32 | 64        | 1.59%   |
| 5.15.28 | 61        | 1.51%   |
| 5.10.42 | 57        | 1.41%   |
| 5.8.18  | 55        | 1.36%   |
| 5.15.12 | 52        | 1.29%   |
| 6.1.1   | 51        | 1.27%   |
| 5.8.16  | 42        | 1.04%   |
| 5.15.65 | 40        | 0.99%   |
| 5.10.2  | 40        | 0.99%   |
| 5.6.16  | 39        | 0.97%   |
| 5.15.60 | 39        | 0.97%   |
| 5.10.7  | 39        | 0.97%   |
| 5.7.0   | 36        | 0.89%   |
| 5.12.9  | 36        | 0.89%   |
| 5.6.19  | 35        | 0.87%   |
| 5.9.1   | 33        | 0.82%   |
| 5.15.74 | 32        | 0.79%   |
| 5.15.7  | 32        | 0.79%   |
| 5.7.9   | 30        | 0.74%   |
| 5.6.15  | 30        | 0.74%   |
| 5.17.1  | 30        | 0.74%   |
| 5.15.81 | 30        | 0.74%   |
| 5.15.78 | 30        | 0.74%   |
| 5.15.41 | 30        | 0.74%   |
| 5.10.36 | 30        | 0.74%   |
| 5.7.17  | 29        | 0.72%   |
| 5.8.3   | 28        | 0.69%   |
| 5.15.25 | 28        | 0.69%   |
| 5.14.10 | 28        | 0.69%   |
| 5.10.34 | 27        | 0.67%   |
| 5.19.0  | 26        | 0.65%   |
| 5.16.14 | 25        | 0.62%   |
| 5.15.85 | 25        | 0.62%   |
| 5.10.70 | 25        | 0.62%   |
| 5.10.53 | 25        | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 685       | 17.96%  |
| 5.10    | 499       | 13.08%  |
| 5.4     | 356       | 9.33%   |
| 5.9     | 322       | 8.44%   |
| 5.8     | 291       | 7.63%   |
| 5.13    | 204       | 5.35%   |
| 5.6     | 199       | 5.22%   |
| 5.7     | 137       | 3.59%   |
| 6.1     | 135       | 3.54%   |
| 4.19    | 121       | 3.17%   |
| 5.16    | 99        | 2.6%    |
| 5.12    | 94        | 2.46%   |
| 5.11    | 81        | 2.12%   |
| 6.0     | 78        | 2.04%   |
| 5.14    | 76        | 1.99%   |
| 5.19    | 73        | 1.91%   |
| 5.17    | 70        | 1.83%   |
| 5.18    | 69        | 1.81%   |
| 5.3     | 64        | 1.68%   |
| 5.5     | 62        | 1.63%   |
| 4.14    | 25        | 0.66%   |
| 5.2     | 23        | 0.6%    |
| 5.0     | 17        | 0.45%   |
| 5.1     | 13        | 0.34%   |
| 4.20    | 9         | 0.24%   |
| 4.18    | 7         | 0.18%   |
| 6.2     | 3         | 0.08%   |
| 4.9     | 2         | 0.05%   |
| 4.16    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3449      | 99.94%  |
| i686   | 2         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| KDE5                 | 1213      | 34.17%  |
| XFCE                 | 791       | 22.28%  |
| GNOME                | 768       | 21.63%  |
| KDE                  | 274       | 7.72%   |
| Unknown              | 193       | 5.44%   |
| X-Cinnamon           | 79        | 2.23%   |
| i3                   | 78        | 2.2%    |
| MATE                 | 36        | 1.01%   |
| Cinnamon             | 30        | 0.85%   |
| Deepin               | 25        | 0.7%    |
| Budgie               | 14        | 0.39%   |
| awesome              | 11        | 0.31%   |
| LXQt                 | 7         | 0.2%    |
| sway                 | 6         | 0.17%   |
| LXDE                 | 6         | 0.17%   |
| i3-with-shmlog       | 3         | 0.08%   |
| leftwm               | 2         | 0.06%   |
| GNOME Flashback      | 2         | 0.06%   |
| DWM                  | 2         | 0.06%   |
| bspwm                | 2         | 0.06%   |
| Yaru:ubuntu:GNOME    | 1         | 0.03%   |
| xinitrc              | 1         | 0.03%   |
| Unity                | 1         | 0.03%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.03%   |
| qtile                | 1         | 0.03%   |
| herbstluftwm         | 1         | 0.03%   |
| GNOME Classic        | 1         | 0.03%   |
| Enlightenment        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2910      | 83.21%  |
| Wayland | 466       | 13.33%  |
| Unknown | 90        | 2.57%   |
| Tty     | 31        | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1373      | 38.88%  |
| SDDM    | 900       | 25.49%  |
| LightDM | 638       | 18.07%  |
| GDM     | 485       | 13.74%  |
| TDM     | 123       | 3.48%   |
| LXDM    | 5         | 0.14%   |
| Ly      | 2         | 0.06%   |
| GREETD  | 2         | 0.06%   |
| XDM     | 1         | 0.03%   |
| SLiM    | 1         | 0.03%   |
| CDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1501      | 43%     |
| de_DE   | 245       | 7.02%   |
| ru_RU   | 244       | 6.99%   |
| Unknown | 240       | 6.87%   |
| en_GB   | 225       | 6.45%   |
| pt_BR   | 138       | 3.95%   |
| fr_FR   | 92        | 2.64%   |
| it_IT   | 70        | 2.01%   |
| es_ES   | 66        | 1.89%   |
| pl_PL   | 63        | 1.8%    |
| en_CA   | 59        | 1.69%   |
| en_IN   | 51        | 1.46%   |
| es_MX   | 39        | 1.12%   |
| en_AU   | 36        | 1.03%   |
| zh_CN   | 30        | 0.86%   |
| ru_UA   | 20        | 0.57%   |
| de_AT   | 20        | 0.57%   |
| C       | 17        | 0.49%   |
| nl_NL   | 16        | 0.46%   |
| es_AR   | 15        | 0.43%   |
| pt_PT   | 14        | 0.4%    |
| en_IE   | 14        | 0.4%    |
| tr_TR   | 13        | 0.37%   |
| en_DK   | 13        | 0.37%   |
| cs_CZ   | 13        | 0.37%   |
| es_CL   | 12        | 0.34%   |
| uk_UA   | 10        | 0.29%   |
| sv_SE   | 10        | 0.29%   |
| es_CO   | 10        | 0.29%   |
| en_ZA   | 10        | 0.29%   |
| fi_FI   | 9         | 0.26%   |
| nl_BE   | 8         | 0.23%   |
| hu_HU   | 8         | 0.23%   |
| en_NZ   | 8         | 0.23%   |
| el_GR   | 8         | 0.23%   |
| de_CH   | 8         | 0.23%   |
| zh_TW   | 7         | 0.2%    |
| en_PH   | 7         | 0.2%    |
| en_DE   | 7         | 0.2%    |
| en_IL   | 6         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1790      | 51.08%  |
| EFI  | 1714      | 48.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 2933      | 84.38%  |
| Btrfs    | 310       | 8.92%   |
| Overlay  | 84        | 2.42%   |
| Unknown  | 82        | 2.36%   |
| Xfs      | 35        | 1.01%   |
| Tmpfs    | 13        | 0.37%   |
| F2fs     | 11        | 0.32%   |
| Reiserfs | 3         | 0.09%   |
| Ext3     | 3         | 0.09%   |
| Jfs      | 1         | 0.03%   |
| Ext2     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1707      | 48.66%  |
| Unknown | 1501      | 42.79%  |
| MBR     | 300       | 8.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3137      | 89.86%  |
| Yes       | 354       | 10.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2466      | 70.38%  |
| Yes       | 1038      | 29.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 880       | 25.5%   |
| Hewlett-Packard      | 587       | 17.01%  |
| Dell                 | 513       | 14.87%  |
| ASUSTek Computer     | 425       | 12.32%  |
| Acer                 | 277       | 8.03%   |
| MSI                  | 103       | 2.98%   |
| Apple                | 85        | 2.46%   |
| Toshiba              | 60        | 1.74%   |
| HUAWEI               | 58        | 1.68%   |
| Samsung Electronics  | 56        | 1.62%   |
| Timi                 | 38        | 1.1%    |
| Notebook             | 29        | 0.84%   |
| Sony                 | 28        | 0.81%   |
| Fujitsu              | 26        | 0.75%   |
| Google               | 23        | 0.67%   |
| Unknown              | 18        | 0.52%   |
| TUXEDO               | 16        | 0.46%   |
| Razer                | 14        | 0.41%   |
| Alienware            | 12        | 0.35%   |
| Schenker             | 11        | 0.32%   |
| Packard Bell         | 9         | 0.26%   |
| LG Electronics       | 9         | 0.26%   |
| System76             | 8         | 0.23%   |
| HONOR                | 8         | 0.23%   |
| Gigabyte Technology  | 8         | 0.23%   |
| Panasonic            | 7         | 0.2%    |
| Medion               | 7         | 0.2%    |
| Clevo                | 7         | 0.2%    |
| Chuwi                | 7         | 0.2%    |
| Monster              | 6         | 0.17%   |
| Positivo             | 5         | 0.14%   |
| Multilaser           | 5         | 0.14%   |
| GPD                  | 5         | 0.14%   |
| PC Specialist        | 4         | 0.12%   |
| Intel Client Systems | 4         | 0.12%   |
| TrekStor             | 3         | 0.09%   |
| Star Labs            | 3         | 0.09%   |
| MECHREVO             | 3         | 0.09%   |
| Gateway              | 3         | 0.09%   |
| Framework            | 3         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 28        | 0.81%   |
| HP Notebook                          | 21        | 0.61%   |
| Lenovo Legion 5 15ARH05 82B5         | 13        | 0.38%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 13        | 0.38%   |
| Dell XPS 13 9310                     | 13        | 0.38%   |
| Dell XPS 15 9500                     | 12        | 0.35%   |
| HP Pavilion Notebook                 | 11        | 0.32%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 11        | 0.32%   |
| HP Laptop 15-bs0xx                   | 10        | 0.29%   |
| HP Pavilion g6                       | 9         | 0.26%   |
| HP Pavilion dv7                      | 9         | 0.26%   |
| HP Pavilion 15                       | 9         | 0.26%   |
| Dell XPS 15 9570                     | 9         | 0.26%   |
| Dell XPS 15 9560                     | 9         | 0.26%   |
| Dell Inspiron 3542                   | 9         | 0.26%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 8         | 0.23%   |
| HP Pavilion dv6                      | 8         | 0.23%   |
| HP 15                                | 8         | 0.23%   |
| Dell XPS 15 7590                     | 8         | 0.23%   |
| Dell XPS 13 7390                     | 8         | 0.23%   |
| Dell Latitude E6430                  | 8         | 0.23%   |
| Dell Inspiron N5110                  | 8         | 0.23%   |
| Apple MacBookPro9,2                  | 8         | 0.23%   |
| Timi TM1701                          | 7         | 0.2%    |
| Lenovo Z50-70 20354                  | 7         | 0.2%    |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 7         | 0.2%    |
| Lenovo Y520-15IKBN 80WK              | 7         | 0.2%    |
| HP OMEN by Laptop                    | 7         | 0.2%    |
| HP Laptop 15s-eq2xxx                 | 7         | 0.2%    |
| Dell G3 3590                         | 7         | 0.2%    |
| Apple MacBookPro15,1                 | 7         | 0.2%    |
| Acer Swift SF314-42                  | 7         | 0.2%    |
| Lenovo ThinkBook 15-IIL 20SM         | 6         | 0.17%   |
| Lenovo Legion 5 15ARH05H 82B1        | 6         | 0.17%   |
| Lenovo Legion 5 15ACH6H 82JU         | 6         | 0.17%   |
| Lenovo IdeaPad S540-14API 81NH       | 6         | 0.17%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 6         | 0.17%   |
| Lenovo G580 20150                    | 6         | 0.17%   |
| HUAWEI KLVL-WXX9                     | 6         | 0.17%   |
| HUAWEI BOHK-WAX9X                    | 6         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 407       | 11.79%  |
| Lenovo IdeaPad        | 237       | 6.87%   |
| Acer Aspire           | 181       | 5.24%   |
| Dell Inspiron         | 169       | 4.9%    |
| HP Pavilion           | 138       | 4%      |
| Dell Latitude         | 134       | 3.88%   |
| Dell XPS              | 96        | 2.78%   |
| HP ProBook            | 90        | 2.61%   |
| HP Laptop             | 88        | 2.55%   |
| HP EliteBook          | 86        | 2.49%   |
| ASUS VivoBook         | 67        | 1.94%   |
| Lenovo Legion         | 65        | 1.88%   |
| Toshiba Satellite     | 54        | 1.56%   |
| ASUS ROG              | 48        | 1.39%   |
| Dell Precision        | 40        | 1.16%   |
| Dell Vostro           | 35        | 1.01%   |
| ASUS ZenBook          | 33        | 0.96%   |
| Acer Swift            | 33        | 0.96%   |
| ASUS TUF              | 30        | 0.87%   |
| Unknown               | 28        | 0.81%   |
| Lenovo ThinkBook      | 26        | 0.75%   |
| Acer Nitro            | 26        | 0.75%   |
| HP OMEN               | 25        | 0.72%   |
| HP ENVY               | 24        | 0.7%    |
| ASUS ASUS             | 23        | 0.67%   |
| Fujitsu LIFEBOOK      | 22        | 0.64%   |
| HP Notebook           | 21        | 0.61%   |
| Lenovo Yoga           | 20        | 0.58%   |
| HP ZBook              | 20        | 0.58%   |
| Timi RedmiBook        | 16        | 0.46%   |
| HP 250                | 16        | 0.46%   |
| Dell G3               | 15        | 0.43%   |
| HP Compaq             | 14        | 0.41%   |
| Razer Blade           | 13        | 0.38%   |
| HP 15                 | 13        | 0.38%   |
| Acer TravelMate       | 13        | 0.38%   |
| Apple MacBookPro11    | 12        | 0.35%   |
| HP 255                | 11        | 0.32%   |
| Acer Predator         | 11        | 0.32%   |
| Packard Bell EasyNote | 9         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 469       | 13.59%  |
| 2020    | 465       | 13.47%  |
| 2018    | 363       | 10.52%  |
| 2021    | 315       | 9.13%   |
| 2017    | 277       | 8.03%   |
| 2012    | 254       | 7.36%   |
| 2013    | 204       | 5.91%   |
| 2015    | 203       | 5.88%   |
| 2014    | 197       | 5.71%   |
| 2016    | 191       | 5.53%   |
| 2011    | 187       | 5.42%   |
| 2010    | 106       | 3.07%   |
| 2008    | 68        | 1.97%   |
| 2022    | 64        | 1.85%   |
| 2009    | 51        | 1.48%   |
| 2007    | 26        | 0.75%   |
| 2006    | 7         | 0.2%    |
| Unknown | 3         | 0.09%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3451      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3449      | 99.88%  |
| Enabled  | 4         | 0.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3411      | 98.84%  |
| Yes  | 40        | 1.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1059      | 30.34%  |
| 16.01-24.0  | 751       | 21.52%  |
| 8.01-16.0   | 726       | 20.8%   |
| 3.01-4.0    | 501       | 14.36%  |
| 32.01-64.0  | 258       | 7.39%   |
| 1.01-2.0    | 68        | 1.95%   |
| 24.01-32.0  | 60        | 1.72%   |
| 64.01-256.0 | 39        | 1.12%   |
| 2.01-3.0    | 27        | 0.77%   |
| 0.51-1.0    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1060      | 27.9%   |
| 1.01-2.0   | 980       | 25.8%   |
| 4.01-8.0   | 741       | 19.51%  |
| 3.01-4.0   | 656       | 17.27%  |
| 8.01-16.0  | 203       | 5.34%   |
| 0.51-1.0   | 132       | 3.47%   |
| 16.01-24.0 | 14        | 0.37%   |
| 24.01-32.0 | 6         | 0.16%   |
| 0.01-0.5   | 6         | 0.16%   |
| 32.01-64.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2387      | 67.91%  |
| 2      | 970       | 27.6%   |
| 3      | 127       | 3.61%   |
| 0      | 19        | 0.54%   |
| 4      | 10        | 0.28%   |
| 7      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2564      | 73.93%  |
| Yes       | 904       | 26.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2661      | 76.86%  |
| No        | 801       | 23.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3403      | 98.52%  |
| No        | 51        | 1.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2827      | 81.4%   |
| No        | 646       | 18.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 511       | 14.71%  |
| Germany     | 366       | 10.54%  |
| Russia      | 323       | 9.3%    |
| Brazil      | 205       | 5.9%    |
| France      | 133       | 3.83%   |
| UK          | 118       | 3.4%    |
| Italy       | 115       | 3.31%   |
| Poland      | 106       | 3.05%   |
| Canada      | 94        | 2.71%   |
| Spain       | 93        | 2.68%   |
| India       | 90        | 2.59%   |
| Ukraine     | 88        | 2.53%   |
| Netherlands | 83        | 2.39%   |
| Mexico      | 62        | 1.79%   |
| China       | 49        | 1.41%   |
| Austria     | 49        | 1.41%   |
| Turkey      | 44        | 1.27%   |
| Australia   | 42        | 1.21%   |
| Sweden      | 37        | 1.07%   |
| Indonesia   | 37        | 1.07%   |
| Romania     | 34        | 0.98%   |
| Switzerland | 32        | 0.92%   |
| Czechia     | 32        | 0.92%   |
| Belgium     | 32        | 0.92%   |
| Portugal    | 31        | 0.89%   |
| Belarus     | 28        | 0.81%   |
| Finland     | 26        | 0.75%   |
| Hungary     | 24        | 0.69%   |
| Norway      | 23        | 0.66%   |
| Greece      | 23        | 0.66%   |
| Bulgaria    | 23        | 0.66%   |
| Argentina   | 23        | 0.66%   |
| Colombia    | 21        | 0.6%    |
| Taiwan      | 20        | 0.58%   |
| Denmark     | 20        | 0.58%   |
| Iran        | 18        | 0.52%   |
| Bangladesh  | 17        | 0.49%   |
| Chile       | 16        | 0.46%   |
| Croatia     | 15        | 0.43%   |
| Japan       | 14        | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 72        | 1.97%   |
| St Petersburg     | 46        | 1.26%   |
| Vienna            | 34        | 0.93%   |
| Paris             | 32        | 0.88%   |
| Sao Paulo         | 26        | 0.71%   |
| Kyiv              | 25        | 0.68%   |
| Berlin            | 25        | 0.68%   |
| Amsterdam         | 23        | 0.63%   |
| Warsaw            | 20        | 0.55%   |
| Munich            | 18        | 0.49%   |
| Milan             | 18        | 0.49%   |
| Bengaluru         | 17        | 0.47%   |
| Toronto           | 16        | 0.44%   |
| Novosibirsk       | 16        | 0.44%   |
| Minsk             | 16        | 0.44%   |
| Istanbul          | 16        | 0.44%   |
| Prague            | 15        | 0.41%   |
| Helsinki          | 15        | 0.41%   |
| Madrid            | 14        | 0.38%   |
| Frankfurt am Main | 14        | 0.38%   |
| Rome              | 13        | 0.36%   |
| Mexico City       | 13        | 0.36%   |
| Hamburg           | 13        | 0.36%   |
| Budapest          | 13        | 0.36%   |
| Bucharest         | 13        | 0.36%   |
| Barcelona         | 13        | 0.36%   |
| London            | 12        | 0.33%   |
| Yekaterinburg     | 11        | 0.3%    |
| Sofia             | 11        | 0.3%    |
| Melbourne         | 11        | 0.3%    |
| Krasnodar         | 11        | 0.3%    |
| Dhaka             | 11        | 0.3%    |
| Cologne           | 11        | 0.3%    |
| Athens            | 11        | 0.3%    |
| Zagreb            | 10        | 0.27%   |
| The Hague         | 10        | 0.27%   |
| Stockholm         | 10        | 0.27%   |
| Seattle           | 10        | 0.27%   |
| Krakow            | 10        | 0.27%   |
| Bogotá           | 10        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 796       | 1051   | 17.56%  |
| WDC                            | 499       | 599    | 11.01%  |
| Seagate                        | 455       | 588    | 10.04%  |
| Toshiba                        | 346       | 400    | 7.63%   |
| SanDisk                        | 299       | 380    | 6.6%    |
| Kingston                       | 253       | 291    | 5.58%   |
| SK hynix                       | 229       | 277    | 5.05%   |
| Unknown                        | 226       | 271    | 4.99%   |
| Crucial                        | 158       | 195    | 3.49%   |
| Intel                          | 154       | 190    | 3.4%    |
| HGST                           | 136       | 163    | 3%      |
| Micron Technology              | 121       | 152    | 2.67%   |
| Hitachi                        | 87        | 102    | 1.92%   |
| KIOXIA                         | 58        | 65     | 1.28%   |
| A-DATA Technology              | 57        | 67     | 1.26%   |
| Apple                          | 53        | 61     | 1.17%   |
| Phison                         | 43        | 62     | 0.95%   |
| China                          | 35        | 38     | 0.77%   |
| Transcend                      | 30        | 36     | 0.66%   |
| LITEONIT                       | 26        | 32     | 0.57%   |
| GOODRAM                        | 25        | 43     | 0.55%   |
| LITEON                         | 23        | 26     | 0.51%   |
| Silicon Motion                 | 21        | 24     | 0.46%   |
| Micron/Crucial Technology      | 20        | 22     | 0.44%   |
| JMicron Technology             | 18        | 19     | 0.4%    |
| Phison Electronics             | 17        | 17     | 0.38%   |
| Plextor                        | 14        | 22     | 0.31%   |
| Union Memory (Shenzhen)        | 12        | 12     | 0.26%   |
| Patriot                        | 12        | 12     | 0.26%   |
| SPCC                           | 11        | 13     | 0.24%   |
| Intenso                        | 11        | 12     | 0.24%   |
| Solid State Storage Technology | 10        | 17     | 0.22%   |
| Fujitsu                        | 10        | 10     | 0.22%   |
| XPG                            | 9         | 15     | 0.2%    |
| Hewlett-Packard                | 9         | 13     | 0.2%    |
| Unknown                        | 9         | 10     | 0.2%    |
| PNY                            | 8         | 12     | 0.18%   |
| Netac                          | 8         | 14     | 0.18%   |
| Kingston Technology Company    | 8         | 8      | 0.18%   |
| Corsair                        | 8         | 8      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 88        | 1.86%   |
| Samsung NVMe SSD Drive 512GB                        | 65        | 1.38%   |
| Toshiba MQ01ABD100 1TB                              | 51        | 1.08%   |
| HGST HTS721010A9E630 1TB                            | 49        | 1.04%   |
| Toshiba MQ04ABF100 1TB                              | 47        | 1%      |
| SK hynix NVMe SSD Drive 512GB                       | 46        | 0.97%   |
| SanDisk NVMe SSD Drive 512GB                        | 43        | 0.91%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 43        | 0.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 43        | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 42        | 0.89%   |
| Kingston SA400S37240G 240GB SSD                     | 40        | 0.85%   |
| Toshiba MQ01ABF050 500GB                            | 37        | 0.78%   |
| Unknown MMC Card  32GB                              | 31        | 0.66%   |
| Intel NVMe SSD Drive 512GB                          | 30        | 0.64%   |
| Samsung NVMe SSD Drive 1TB                          | 29        | 0.61%   |
| Unknown SD/MMC/MS PRO 16GB                          | 28        | 0.59%   |
| Unknown MMC Card  64GB                              | 26        | 0.55%   |
| SanDisk NVMe SSD Drive 256GB                        | 26        | 0.55%   |
| Crucial CT500MX500SSD1 500GB                        | 26        | 0.55%   |
| Seagate ST500LT012-1DG142 500GB                     | 25        | 0.53%   |
| Seagate ST1000LM049-2GH172 1TB                      | 24        | 0.51%   |
| Samsung NVMe SSD Drive 1024GB                       | 23        | 0.49%   |
| Kingston SA400S37120G 120GB SSD                     | 23        | 0.49%   |
| SK hynix NVMe SSD Drive 256GB                       | 22        | 0.47%   |
| Samsung SSD 860 EVO 500GB                           | 22        | 0.47%   |
| Samsung SSD 850 EVO 500GB                           | 22        | 0.47%   |
| HGST HTS545050A7E680 500GB                          | 22        | 0.47%   |
| Seagate Expansion 1TB                               | 21        | 0.44%   |
| Kingston SA400S37480G 480GB SSD                     | 20        | 0.42%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 19        | 0.4%    |
| SanDisk NVMe SSD Drive 1TB                          | 19        | 0.4%    |
| Micron NVMe SSD Drive 512GB                         | 19        | 0.4%    |
| Kingston NVMe SSD Drive 512GB                       | 19        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB                         | 19        | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 18        | 0.38%   |
| Toshiba NVMe SSD Drive 512GB                        | 18        | 0.38%   |
| Seagate ST9500325AS 500GB                           | 18        | 0.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 18        | 0.38%   |
| Intel SSDPEKNW512G8 512GB                           | 18        | 0.38%   |
| WDC WD10SPZX-24Z10 1TB                              | 17        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 445       | 570    | 34.34%  |
| WDC                 | 321       | 375    | 24.77%  |
| Toshiba             | 222       | 256    | 17.13%  |
| HGST                | 136       | 163    | 10.49%  |
| Hitachi             | 87        | 102    | 6.71%   |
| Unknown             | 30        | 33     | 2.31%   |
| Samsung Electronics | 14        | 16     | 1.08%   |
| Fujitsu             | 10        | 10     | 0.77%   |
| JMicron Technology  | 8         | 8      | 0.62%   |
| Apple               | 5         | 6      | 0.39%   |
| SABRENT             | 4         | 4      | 0.31%   |
| USB3.0              | 2         | 2      | 0.15%   |
| Intenso             | 2         | 2      | 0.15%   |
| QNAP                | 1         | 1      | 0.08%   |
| Pioneer             | 1         | 3      | 0.08%   |
| PHD 3.0             | 1         | 1      | 0.08%   |
| KESU                | 1         | 1      | 0.08%   |
| Hewlett-Packard     | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |
| Apricorn            | 1         | 1      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 323       | 406    | 23.01%  |
| Kingston            | 182       | 207    | 12.96%  |
| Crucial             | 145       | 182    | 10.33%  |
| SanDisk             | 122       | 161    | 8.69%   |
| WDC                 | 84        | 102    | 5.98%   |
| Micron Technology   | 52        | 67     | 3.7%    |
| A-DATA Technology   | 42        | 47     | 2.99%   |
| SK hynix            | 37        | 46     | 2.64%   |
| Intel               | 37        | 43     | 2.64%   |
| China               | 35        | 38     | 2.49%   |
| Apple               | 35        | 39     | 2.49%   |
| Toshiba             | 30        | 31     | 2.14%   |
| Transcend           | 28        | 33     | 1.99%   |
| LITEONIT            | 26        | 32     | 1.85%   |
| GOODRAM             | 24        | 42     | 1.71%   |
| LITEON              | 20        | 23     | 1.42%   |
| Plextor             | 13        | 21     | 0.93%   |
| Patriot             | 11        | 11     | 0.78%   |
| Intenso             | 9         | 10     | 0.64%   |
| Netac               | 8         | 14     | 0.57%   |
| PNY                 | 7         | 11     | 0.5%    |
| OCZ                 | 7         | 8      | 0.5%    |
| KingSpec            | 7         | 7      | 0.5%    |
| SPCC                | 6         | 7      | 0.43%   |
| Seagate             | 6         | 10     | 0.43%   |
| Hewlett-Packard     | 5         | 8      | 0.36%   |
| Corsair             | 5         | 5      | 0.36%   |
| TO Exter            | 4         | 5      | 0.28%   |
| Lexar               | 4         | 4      | 0.28%   |
| FORESEE             | 4         | 4      | 0.28%   |
| Apacer              | 4         | 4      | 0.28%   |
| Unknown             | 4         | 5      | 0.28%   |
| TwinMOS             | 3         | 5      | 0.21%   |
| Team                | 3         | 4      | 0.21%   |
| Mushkin             | 3         | 4      | 0.21%   |
| Vaseky              | 2         | 2      | 0.14%   |
| Unknown             | 2         | 3      | 0.14%   |
| OWC                 | 2         | 4      | 0.14%   |
| NGFF                | 2         | 2      | 0.14%   |
| Londisk             | 2         | 2      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1492      | 2011   | 34.78%  |
| SSD     | 1312      | 1732   | 30.58%  |
| HDD     | 1242      | 1559   | 28.95%  |
| MMC     | 187       | 230    | 4.36%   |
| Unknown | 57        | 65     | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2188      | 3143   | 54.15%  |
| NVMe | 1492      | 2002   | 36.92%  |
| MMC  | 187       | 230    | 4.63%   |
| SAS  | 174       | 222    | 4.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1557      | 2083   | 61.96%  |
| 0.51-1.0   | 861       | 1071   | 34.26%  |
| 1.01-2.0   | 74        | 97     | 2.94%   |
| 4.01-10.0  | 14        | 20     | 0.56%   |
| 3.01-4.0   | 6         | 19     | 0.24%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 964       | 26.95%  |
| 251-500        | 925       | 25.86%  |
| 501-1000       | 566       | 15.82%  |
| 1001-2000      | 285       | 7.97%   |
| Unknown        | 254       | 7.1%    |
| 51-100         | 228       | 6.37%   |
| 1-20           | 130       | 3.63%   |
| 21-50          | 109       | 3.05%   |
| More than 3000 | 61        | 1.71%   |
| 2001-3000      | 55        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 873       | 23.4%   |
| 21-50          | 707       | 18.95%  |
| 101-250        | 633       | 16.97%  |
| 51-100         | 564       | 15.12%  |
| 251-500        | 388       | 10.4%   |
| Unknown        | 254       | 6.81%   |
| 501-1000       | 214       | 5.74%   |
| 1001-2000      | 67        | 1.8%    |
| More than 3000 | 15        | 0.4%    |
| 2001-3000      | 13        | 0.35%   |
| 0              | 3         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 11     | 4.9%    |
| HGST HTS721010A9E630 1TB                            | 8         | 8      | 3.92%   |
| HGST HTS545050A7E680 500GB                          | 8         | 8      | 3.92%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 2.94%   |
| HGST HTS545050A7E380 500GB                          | 6         | 6      | 2.94%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 22     | 2.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 5      | 2.45%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 1.96%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 1.47%   |
| Toshiba MQ01ABD050 500GB                            | 3         | 3      | 1.47%   |
| Seagate ST9500325AS 500GB                           | 3         | 4      | 1.47%   |
| Seagate ST9320325AS 320GB                           | 3         | 4      | 1.47%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 1.47%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 3         | 3      | 1.47%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 1.47%   |
| Hitachi HTS723232A7A364 320GB                       | 3         | 3      | 1.47%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 1.47%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 3      | 0.98%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 2         | 2      | 0.98%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.98%   |
| Seagate ST9750420AS 752GB                           | 2         | 2      | 0.98%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 2      | 0.98%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 5      | 0.98%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 2      | 0.98%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.98%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 0.98%   |
| Crucial CT525MX300SSD1 528GB                        | 2         | 2      | 0.98%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 0.49%   |
| WDC WD800BEVS-22RST0 80GB                           | 1         | 1      | 0.49%   |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 1      | 0.49%   |
| WDC WD5000LPVX-08V0TT5 500GB                        | 1         | 1      | 0.49%   |
| WDC WD5000LPLX-00ZNTT0 500GB                        | 1         | 1      | 0.49%   |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 1      | 0.49%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 1      | 0.49%   |
| WDC WD5000BPVT-60HXZT3 500GB                        | 1         | 1      | 0.49%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 1      | 0.49%   |
| WDC WD5000BEVT-75A0RT0 500GB                        | 1         | 1      | 0.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 1      | 0.49%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 1         | 1      | 0.49%   |
| WDC WD2500LPCX-24C6HT0 250GB                        | 1         | 1      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 81     | 26.11%  |
| HGST                | 30        | 30     | 14.78%  |
| WDC                 | 24        | 27     | 11.82%  |
| Toshiba             | 23        | 26     | 11.33%  |
| Hitachi             | 19        | 20     | 9.36%   |
| Samsung Electronics | 8         | 9      | 3.94%   |
| Crucial             | 8         | 11     | 3.94%   |
| SanDisk             | 6         | 6      | 2.96%   |
| SK hynix            | 5         | 9      | 2.46%   |
| Intel               | 5         | 6      | 2.46%   |
| Micron Technology   | 4         | 6      | 1.97%   |
| LITEON              | 3         | 3      | 1.48%   |
| Kingston            | 3         | 3      | 1.48%   |
| A-DATA Technology   | 3         | 4      | 1.48%   |
| TwinMOS             | 1         | 1      | 0.49%   |
| LITEONIT            | 1         | 1      | 0.49%   |
| KingSpec            | 1         | 1      | 0.49%   |
| IM3D                | 1         | 1      | 0.49%   |
| Faspeed             | 1         | 1      | 0.49%   |
| Corsair             | 1         | 1      | 0.49%   |
| ASMT                | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |
| Unknown             | 1         | 1      | 0.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 81     | 36.55%  |
| HGST                | 30        | 30     | 20.69%  |
| WDC                 | 23        | 26     | 15.86%  |
| Toshiba             | 19        | 22     | 13.1%   |
| Hitachi             | 19        | 20     | 13.1%   |
| Samsung Electronics | 1         | 1      | 0.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 144       | 180    | 71.64%  |
| SSD  | 50        | 62     | 24.88%  |
| NVMe | 7         | 8      | 3.48%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 33.33%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 33.33%  |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2148      | 3321   | 57.8%   |
| Works    | 1368      | 2023   | 36.81%  |
| Malfunc  | 197       | 250    | 5.3%    |
| Failed   | 3         | 3      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2261      | 52.56%  |
| Samsung Electronics              | 513       | 11.92%  |
| AMD                              | 505       | 11.74%  |
| SanDisk                          | 265       | 6.16%   |
| SK hynix                         | 190       | 4.42%   |
| Toshiba America Info Systems     | 89        | 2.07%   |
| Kingston Technology Company      | 78        | 1.81%   |
| Micron Technology                | 68        | 1.58%   |
| KIOXIA                           | 66        | 1.53%   |
| Phison Electronics               | 65        | 1.51%   |
| Micron/Crucial Technology        | 32        | 0.74%   |
| ADATA Technology                 | 26        | 0.6%    |
| Union Memory (Shenzhen)          | 25        | 0.58%   |
| Silicon Motion                   | 24        | 0.56%   |
| Nvidia                           | 18        | 0.42%   |
| Solid State Storage Technology   | 17        | 0.4%    |
| Apple                            | 12        | 0.28%   |
| Lite-On Technology               | 10        | 0.23%   |
| Shenzhen Longsys Electronics     | 7         | 0.16%   |
| Realtek Semiconductor            | 7         | 0.16%   |
| Marvell Technology Group         | 5         | 0.12%   |
| Lenovo                           | 4         | 0.09%   |
| Yangtze Memory Technologies      | 3         | 0.07%   |
| JMicron Technology               | 3         | 0.07%   |
| Biwin Storage Technology         | 3         | 0.07%   |
| Seagate Technology               | 2         | 0.05%   |
| Transcend                        | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| ASMedia Technology               | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 466       | 10.4%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 313       | 6.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 280       | 6.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 245       | 5.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 210       | 4.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 158       | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 153       | 3.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 141       | 3.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 127       | 2.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 117       | 2.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 107       | 2.39%   |
| Samsung NVMe SSD Controller 980                                                | 104       | 2.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 82        | 1.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 76        | 1.7%    |
| Micron Non-Volatile memory controller                                          | 68        | 1.52%   |
| Intel SSD 660P Series                                                          | 63        | 1.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 60        | 1.34%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 58        | 1.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 57        | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 55        | 1.23%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 54        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 50        | 1.12%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 46        | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 46        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 44        | 0.98%   |
| SK hynix BC511                                                                 | 43        | 0.96%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 40        | 0.89%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 39        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 38        | 0.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 36        | 0.8%    |
| SanDisk Non-Volatile memory controller                                         | 36        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 36        | 0.8%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 35        | 0.78%   |
| SK hynix Non-Volatile memory controller                                        | 33        | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 31        | 0.69%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 29        | 0.65%   |
| Phison E12 NVMe Controller                                                     | 29        | 0.65%   |
| Kingston Company Company Non-Volatile memory controller                        | 29        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 29        | 0.65%   |
| Intel Non-Volatile memory controller                                           | 28        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2436      | 56.39%  |
| NVMe | 1497      | 34.65%  |
| RAID | 289       | 6.69%   |
| IDE  | 98        | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2679      | 77.63%  |
| AMD    | 772       | 22.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 79        | 2.29%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 68        | 1.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 67        | 1.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 65        | 1.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 64        | 1.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 63        | 1.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 62        | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 62        | 1.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 58        | 1.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 1.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 49        | 1.42%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 46        | 1.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 46        | 1.33%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 43        | 1.24%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 42        | 1.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 42        | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 40        | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 40        | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 39        | 1.13%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 35        | 1.01%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.95%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 33        | 0.95%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 32        | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 31        | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 31        | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 30        | 0.87%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 28        | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 0.81%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 27        | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 27        | 0.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 27        | 0.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 0.78%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 26        | 0.75%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 26        | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.72%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.67%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 22        | 0.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 21        | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 20        | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 20        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 921       | 26.65%  |
| Intel Core i7                  | 919       | 26.59%  |
| AMD Ryzen 7                    | 234       | 6.77%   |
| AMD Ryzen 5                    | 231       | 6.68%   |
| Intel Core i3                  | 230       | 6.66%   |
| Other                          | 219       | 6.34%   |
| Intel Celeron                  | 132       | 3.82%   |
| Intel Core 2 Duo               | 86        | 2.49%   |
| Intel Pentium                  | 78        | 2.26%   |
| AMD Ryzen 3                    | 47        | 1.36%   |
| AMD Ryzen 7 PRO                | 32        | 0.93%   |
| AMD Ryzen 9                    | 30        | 0.87%   |
| AMD A6                         | 27        | 0.78%   |
| Intel Atom                     | 23        | 0.67%   |
| AMD A10                        | 23        | 0.67%   |
| Intel Core i9                  | 22        | 0.64%   |
| AMD A8                         | 22        | 0.64%   |
| Intel Pentium Dual-Core        | 19        | 0.55%   |
| AMD A4                         | 19        | 0.55%   |
| AMD E                          | 17        | 0.49%   |
| AMD E1                         | 16        | 0.46%   |
| Intel Pentium Silver           | 14        | 0.41%   |
| Intel Core 2                   | 10        | 0.29%   |
| AMD E2                         | 8         | 0.23%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.2%    |
| AMD Athlon                     | 7         | 0.2%    |
| Intel Core m3                  | 6         | 0.17%   |
| AMD Ryzen 5 PRO                | 6         | 0.17%   |
| AMD A12                        | 5         | 0.14%   |
| Intel Xeon                     | 4         | 0.12%   |
| Intel Genuine                  | 4         | 0.12%   |
| AMD FX                         | 4         | 0.12%   |
| Intel Core m5                  | 3         | 0.09%   |
| AMD Athlon X2                  | 3         | 0.09%   |
| Intel Core m7                  | 2         | 0.06%   |
| Intel Core M                   | 2         | 0.06%   |
| Intel Core 2 Quad              | 2         | 0.06%   |
| Intel Celeron Dual-Core        | 2         | 0.06%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.06%   |
| AMD Turion II                  | 2         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1474      | 42.7%   |
| 4       | 1290      | 37.37%  |
| 6       | 342       | 9.91%   |
| 8       | 300       | 8.69%   |
| 1       | 16        | 0.46%   |
| 14      | 13        | 0.38%   |
| 12      | 11        | 0.32%   |
| 16      | 2         | 0.06%   |
| 3       | 2         | 0.06%   |
| 10      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3451      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2841      | 82.28%  |
| 1       | 611       | 17.69%  |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3388      | 98.12%  |
| Unknown        | 65        | 1.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1697      | 47.6%   |
| 0x306a9    | 139       | 3.9%    |
| 0x906ea    | 116       | 3.25%   |
| 0x806ea    | 113       | 3.17%   |
| 0x806ec    | 102       | 2.86%   |
| 0x806c1    | 87        | 2.44%   |
| 0x806e9    | 76        | 2.13%   |
| 0x206a7    | 76        | 2.13%   |
| 0x40651    | 71        | 1.99%   |
| 0x406e3    | 68        | 1.91%   |
| 0x08108102 | 63        | 1.77%   |
| 0x306c3    | 58        | 1.63%   |
| 0x306d4    | 55        | 1.54%   |
| 0x906e9    | 53        | 1.49%   |
| 0x08600106 | 53        | 1.49%   |
| 0x0a50000c | 52        | 1.46%   |
| 0xa0652    | 45        | 1.26%   |
| 0x08600103 | 43        | 1.21%   |
| 0x806eb    | 41        | 1.15%   |
| 0x08108109 | 39        | 1.09%   |
| 0x706e5    | 38        | 1.07%   |
| 0x08600104 | 36        | 1.01%   |
| 0x1067a    | 29        | 0.81%   |
| 0x08608103 | 29        | 0.81%   |
| 0x506e3    | 28        | 0.79%   |
| 0x20655    | 28        | 0.79%   |
| 0x30678    | 17        | 0.48%   |
| 0x806d1    | 16        | 0.45%   |
| 0x0810100b | 16        | 0.45%   |
| 0x06006705 | 15        | 0.42%   |
| 0x906a3    | 14        | 0.39%   |
| 0x506c9    | 14        | 0.39%   |
| 0x406c4    | 14        | 0.39%   |
| 0x706a1    | 13        | 0.36%   |
| 0x906ed    | 11        | 0.31%   |
| 0x08600102 | 11        | 0.31%   |
| 0x0600611a | 11        | 0.31%   |
| 0x06001119 | 10        | 0.28%   |
| 0x0a50000b | 9         | 0.25%   |
| 0x20652    | 8         | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 866       | 25.08%  |
| Haswell          | 279       | 8.08%   |
| IvyBridge        | 256       | 7.41%   |
| Zen 2            | 207       | 5.99%   |
| Skylake          | 196       | 5.68%   |
| SandyBridge      | 194       | 5.62%   |
| Zen+             | 161       | 4.66%   |
| TigerLake        | 147       | 4.26%   |
| Broadwell        | 140       | 4.05%   |
| Zen 3            | 110       | 3.19%   |
| Unknown          | 108       | 3.13%   |
| Westmere         | 89        | 2.58%   |
| Penryn           | 89        | 2.58%   |
| CometLake        | 88        | 2.55%   |
| Silvermont       | 83        | 2.4%    |
| Icelake          | 79        | 2.29%   |
| Excavator        | 55        | 1.59%   |
| Goldmont plus    | 49        | 1.42%   |
| Zen              | 37        | 1.07%   |
| Core             | 35        | 1.01%   |
| Goldmont         | 29        | 0.84%   |
| Bobcat           | 27        | 0.78%   |
| Piledriver       | 24        | 0.7%    |
| Puma             | 22        | 0.64%   |
| Jaguar           | 19        | 0.55%   |
| Alderlake Hybrid | 13        | 0.38%   |
| Nehalem          | 10        | 0.29%   |
| K8 Hammer        | 9         | 0.26%   |
| K10 Llano        | 9         | 0.26%   |
| K10              | 7         | 0.2%    |
| Steamroller      | 5         | 0.14%   |
| K8 & K10 hybrid  | 5         | 0.14%   |
| Bonnell          | 5         | 0.14%   |
| Tremont          | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2492      | 53.79%  |
| Nvidia | 1220      | 26.33%  |
| AMD    | 921       | 19.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 244       | 5.16%   |
| AMD Renoir                                                                               | 197       | 4.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 194       | 4.1%    |
| Intel UHD Graphics 620                                                                   | 171       | 3.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 171       | 3.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 163       | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 154       | 3.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 146       | 3.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 130       | 2.75%   |
| Intel HD Graphics 620                                                                    | 120       | 2.54%   |
| Intel HD Graphics 5500                                                                   | 120       | 2.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 108       | 2.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 98        | 2.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 92        | 1.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 89        | 1.88%   |
| Intel HD Graphics 630                                                                    | 87        | 1.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 67        | 1.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 66        | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 64        | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 63        | 1.33%   |
| Intel HD Graphics 530                                                                    | 59        | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 58        | 1.23%   |
| AMD Lucienne                                                                             | 58        | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 50        | 1.06%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 45        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 45        | 0.95%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 42        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 42        | 0.89%   |
| Nvidia GP108M [GeForce MX150]                                                            | 40        | 0.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 40        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 38        | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 37        | 0.78%   |
| Nvidia TU117M                                                                            | 36        | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 36        | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 35        | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 34        | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 34        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 34        | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 32        | 0.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 32        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1453      | 42.02%  |
| Intel + Nvidia     | 921       | 26.63%  |
| 1 x AMD            | 602       | 17.41%  |
| 1 x Nvidia         | 156       | 4.51%   |
| AMD + Nvidia       | 138       | 3.99%   |
| Intel + AMD        | 114       | 3.3%    |
| 2 x AMD            | 68        | 1.97%   |
| 2 x Nvidia         | 3         | 0.09%   |
| Other              | 2         | 0.06%   |
| Intel + 2 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2784      | 79.84%  |
| Proprietary | 702       | 20.13%  |
| Unknown     | 1         | 0.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2660      | 75.93%  |
| 0.01-0.5   | 286       | 8.16%   |
| 1.01-2.0   | 230       | 6.57%   |
| 0.51-1.0   | 113       | 3.23%   |
| 3.01-4.0   | 111       | 3.17%   |
| 5.01-6.0   | 56        | 1.6%    |
| 7.01-8.0   | 28        | 0.8%    |
| 2.01-3.0   | 11        | 0.31%   |
| 8.01-16.0  | 7         | 0.2%    |
| 16.01-24.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 721       | 17.56%  |
| LG Display              | 634       | 15.44%  |
| Chimei Innolux          | 603       | 14.68%  |
| BOE                     | 595       | 14.49%  |
| Samsung Electronics     | 323       | 7.86%   |
| Sharp                   | 130       | 3.17%   |
| Dell                    | 114       | 2.78%   |
| Goldstar                | 106       | 2.58%   |
| PANDA                   | 90        | 2.19%   |
| Apple                   | 86        | 2.09%   |
| Chi Mei Optoelectronics | 77        | 1.87%   |
| Lenovo                  | 66        | 1.61%   |
| Hewlett-Packard         | 46        | 1.12%   |
| Philips                 | 38        | 0.93%   |
| Acer                    | 38        | 0.93%   |
| Ancor Communications    | 37        | 0.9%    |
| BenQ                    | 35        | 0.85%   |
| AOC                     | 34        | 0.83%   |
| InfoVision              | 27        | 0.66%   |
| CSO                     | 23        | 0.56%   |
| ViewSonic               | 22        | 0.54%   |
| LGD                     | 17        | 0.41%   |
| TMX                     | 16        | 0.39%   |
| Iiyama                  | 16        | 0.39%   |
| LG Philips              | 14        | 0.34%   |
| ASUSTek Computer        | 14        | 0.34%   |
| Sony                    | 13        | 0.32%   |
| Panasonic               | 11        | 0.27%   |
| CPT                     | 10        | 0.24%   |
| Toshiba                 | 8         | 0.19%   |
| NEC Computers           | 6         | 0.15%   |
| Insignia                | 6         | 0.15%   |
| Unknown                 | 6         | 0.15%   |
| Unknown                 | 5         | 0.12%   |
| JDI                     | 5         | 0.12%   |
| HannStar                | 5         | 0.12%   |
| Sceptre Tech            | 4         | 0.1%    |
| MSI                     | 4         | 0.1%    |
| LG Electronics          | 4         | 0.1%    |
| KDC                     | 4         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 42        | 1.01%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 38        | 0.91%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 36        | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 31        | 0.75%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 30        | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 21        | 0.5%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 20        | 0.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 20        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 19        | 0.46%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 17        | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 16        | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.38%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 14        | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 14        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 14        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.31%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 13        | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.29%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 11        | 0.26%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 11        | 0.26%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 11        | 0.26%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 11        | 0.26%   |
| AU Optronics LCD Monitor 1920x1080                                       | 11        | 0.26%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 10        | 0.24%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 10        | 0.24%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1920      | 50.12%  |
| 1366x768 (WXGA)    | 944       | 24.64%  |
| 3840x2160 (4K)     | 165       | 4.31%   |
| 1600x900 (HD+)     | 137       | 3.58%   |
| 2560x1440 (QHD)    | 106       | 2.77%   |
| 1280x800 (WXGA)    | 81        | 2.11%   |
| 1920x1200 (WUXGA)  | 62        | 1.62%   |
| 1440x900 (WXGA+)   | 55        | 1.44%   |
| 2560x1600          | 44        | 1.15%   |
| 2880x1800          | 34        | 0.89%   |
| 1680x1050 (WSXGA+) | 33        | 0.86%   |
| 2560x1080          | 27        | 0.7%    |
| Unknown            | 20        | 0.52%   |
| 3840x2400          | 19        | 0.5%    |
| 2160x1440          | 19        | 0.5%    |
| 1280x1024 (SXGA)   | 19        | 0.5%    |
| 1360x768           | 17        | 0.44%   |
| 3440x1440          | 15        | 0.39%   |
| 3840x1080          | 13        | 0.34%   |
| 3200x1800 (QHD+)   | 12        | 0.31%   |
| 3456x2160          | 9         | 0.23%   |
| 3200x2000          | 9         | 0.23%   |
| 3840x1600          | 6         | 0.16%   |
| 1920x540           | 6         | 0.16%   |
| 3000x2000          | 5         | 0.13%   |
| 2256x1504          | 5         | 0.13%   |
| 1920x1280          | 5         | 0.13%   |
| 3286x1080          | 4         | 0.1%    |
| 2240x1400          | 4         | 0.1%    |
| 2880x1920          | 3         | 0.08%   |
| 2520x1680          | 3         | 0.08%   |
| 1600x1200          | 3         | 0.08%   |
| 1024x600           | 3         | 0.08%   |
| 3840x1100          | 2         | 0.05%   |
| 3072x1920          | 2         | 0.05%   |
| 2560x1700          | 2         | 0.05%   |
| 800x1280           | 1         | 0.03%   |
| 7680x1080          | 1         | 0.03%   |
| 720x1280           | 1         | 0.03%   |
| 5760x2160          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1775      | 43.41%  |
| 13      | 592       | 14.48%  |
| 14      | 506       | 12.37%  |
| 17      | 248       | 6.07%   |
| 27      | 140       | 3.42%   |
| 24      | 130       | 3.18%   |
| 23      | 111       | 2.71%   |
| 12      | 87        | 2.13%   |
| 21      | 82        | 2.01%   |
| Unknown | 72        | 1.76%   |
| 11      | 50        | 1.22%   |
| 31      | 49        | 1.2%    |
| 16      | 41        | 1%      |
| 34      | 35        | 0.86%   |
| 18      | 23        | 0.56%   |
| 19      | 19        | 0.46%   |
| 22      | 17        | 0.42%   |
| 20      | 12        | 0.29%   |
| 84      | 10        | 0.24%   |
| 40      | 10        | 0.24%   |
| 32      | 9         | 0.22%   |
| 72      | 7         | 0.17%   |
| 37      | 7         | 0.17%   |
| 26      | 7         | 0.17%   |
| 54      | 5         | 0.12%   |
| 48      | 5         | 0.12%   |
| 25      | 5         | 0.12%   |
| 52      | 4         | 0.1%    |
| 49      | 4         | 0.1%    |
| 28      | 4         | 0.1%    |
| 10      | 4         | 0.1%    |
| 74      | 3         | 0.07%   |
| 42      | 2         | 0.05%   |
| 35      | 2         | 0.05%   |
| 33      | 2         | 0.05%   |
| 8       | 2         | 0.05%   |
| 86      | 1         | 0.02%   |
| 75      | 1         | 0.02%   |
| 60      | 1         | 0.02%   |
| 50      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2605      | 64.23%  |
| 201-300     | 400       | 9.86%   |
| 501-600     | 353       | 8.7%    |
| 351-400     | 295       | 7.27%   |
| 401-500     | 144       | 3.55%   |
| 601-700     | 73        | 1.8%    |
| Unknown     | 72        | 1.78%   |
| 701-800     | 46        | 1.13%   |
| 1501-2000   | 22        | 0.54%   |
| 801-900     | 20        | 0.49%   |
| 1001-1500   | 20        | 0.49%   |
| 901-1000    | 3         | 0.07%   |
| 101-200     | 2         | 0.05%   |
| 1-100       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3033      | 84.7%   |
| 16/10   | 352       | 9.83%   |
| Unknown | 59        | 1.65%   |
| 3/2     | 49        | 1.37%   |
| 21/9    | 45        | 1.26%   |
| 5/4     | 15        | 0.42%   |
| 4/3     | 11        | 0.31%   |
| 32/9    | 10        | 0.28%   |
| 3.40    | 2         | 0.06%   |
| 0.62    | 2         | 0.06%   |
| 6/5     | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1779      | 43.64%  |
| 81-90          | 891       | 21.85%  |
| 201-250        | 281       | 6.89%   |
| 121-130        | 211       | 5.18%   |
| 71-80          | 207       | 5.08%   |
| 301-350        | 144       | 3.53%   |
| 351-500        | 101       | 2.48%   |
| 61-70          | 82        | 2.01%   |
| Unknown        | 72        | 1.77%   |
| 51-60          | 52        | 1.28%   |
| 151-200        | 49        | 1.2%    |
| 251-300        | 41        | 1.01%   |
| More than 1000 | 36        | 0.88%   |
| 131-140        | 30        | 0.74%   |
| 141-150        | 28        | 0.69%   |
| 111-120        | 28        | 0.69%   |
| 501-1000       | 24        | 0.59%   |
| 91-100         | 14        | 0.34%   |
| 41-50          | 4         | 0.1%    |
| 1-40           | 3         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1837      | 45.84%  |
| 101-120       | 1029      | 25.68%  |
| 51-100        | 580       | 14.47%  |
| 161-240       | 303       | 7.56%   |
| More than 240 | 149       | 3.72%   |
| Unknown       | 72        | 1.8%    |
| 1-50          | 37        | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2810      | 79.94%  |
| 2     | 621       | 17.67%  |
| 3     | 61        | 1.74%   |
| 0     | 16        | 0.46%   |
| 4     | 7         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1920      | 35.47%  |
| Realtek Semiconductor             | 1911      | 35.3%   |
| Qualcomm Atheros                  | 740       | 13.67%  |
| Broadcom                          | 260       | 4.8%    |
| MediaTek                          | 71        | 1.31%   |
| Broadcom Limited                  | 70        | 1.29%   |
| Ralink                            | 43        | 0.79%   |
| TP-Link                           | 33        | 0.61%   |
| Ralink Technology                 | 31        | 0.57%   |
| ASIX Electronics                  | 28        | 0.52%   |
| Xiaomi                            | 24        | 0.44%   |
| Sierra Wireless                   | 24        | 0.44%   |
| Marvell Technology Group          | 24        | 0.44%   |
| Lenovo                            | 21        | 0.39%   |
| Dell                              | 21        | 0.39%   |
| DisplayLink                       | 18        | 0.33%   |
| Hewlett-Packard                   | 15        | 0.28%   |
| Qualcomm                          | 13        | 0.24%   |
| Huawei Technologies               | 13        | 0.24%   |
| JMicron Technology                | 12        | 0.22%   |
| Samsung Electronics               | 11        | 0.2%    |
| Ericsson Business Mobile Networks | 11        | 0.2%    |
| Nvidia                            | 9         | 0.17%   |
| ASUSTek Computer                  | 9         | 0.17%   |
| Linksys                           | 7         | 0.13%   |
| Fibocom                           | 7         | 0.13%   |
| Qualcomm Atheros Communications   | 6         | 0.11%   |
| NetGear                           | 6         | 0.11%   |
| D-Link                            | 6         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.07%   |
| Google                            | 4         | 0.07%   |
| Edimax Technology                 | 4         | 0.07%   |
| Apple                             | 4         | 0.07%   |
| Quectel Wireless Solutions        | 3         | 0.06%   |
| ZyXEL Communications              | 2         | 0.04%   |
| Spreadtrum Communications         | 2         | 0.04%   |
| Motorola PCS                      | 2         | 0.04%   |
| Microsoft                         | 2         | 0.04%   |
| ICS Advent                        | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1235      | 19.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 310       | 4.8%    |
| Intel Wi-Fi 6 AX200                                               | 271       | 4.2%    |
| Intel Wireless 8265 / 8275                                        | 173       | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 165       | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 137       | 2.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 136       | 2.11%   |
| Intel Wireless 7260                                               | 126       | 1.95%   |
| Intel Wireless 7265                                               | 123       | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 120       | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 117       | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 112       | 1.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 112       | 1.73%   |
| Intel Wi-Fi 6 AX201                                               | 108       | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 103       | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 92        | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 87        | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 82        | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 81        | 1.25%   |
| Intel Wireless 8260                                               | 79        | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 76        | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 72        | 1.12%   |
| Intel Wireless 3165                                               | 63        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 61        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 57        | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 41        | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 41        | 0.63%   |
| Intel Wireless 3160                                               | 40        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 40        | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 40        | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 39        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 39        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 39        | 0.6%    |
| Intel Wireless-AC 9260                                            | 38        | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 38        | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 36        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 36        | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 36        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 34        | 0.53%   |
| Intel Centrino Wireless-N 2230                                    | 34        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1868      | 52.06%  |
| Qualcomm Atheros                      | 622       | 17.34%  |
| Realtek Semiconductor                 | 577       | 16.08%  |
| Broadcom                              | 200       | 5.57%   |
| MediaTek                              | 55        | 1.53%   |
| Broadcom Limited                      | 54        | 1.51%   |
| Ralink                                | 43        | 1.2%    |
| Ralink Technology                     | 31        | 0.86%   |
| TP-Link                               | 28        | 0.78%   |
| Sierra Wireless                       | 24        | 0.67%   |
| Dell                                  | 15        | 0.42%   |
| Qualcomm                              | 7         | 0.2%    |
| Linksys                               | 7         | 0.2%    |
| ASUSTek Computer                      | 7         | 0.2%    |
| Qualcomm Atheros Communications       | 6         | 0.17%   |
| NetGear                               | 6         | 0.17%   |
| Fibocom                               | 6         | 0.17%   |
| D-Link                                | 6         | 0.17%   |
| Hewlett-Packard                       | 5         | 0.14%   |
| Ericsson Business Mobile Networks     | 4         | 0.11%   |
| Edimax Technology                     | 4         | 0.11%   |
| Quectel Wireless Solutions            | 3         | 0.08%   |
| ZyXEL Communications                  | 2         | 0.06%   |
| Microsoft                             | 2         | 0.06%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| D-Link System                         | 1         | 0.03%   |
| Belkin Components                     | 1         | 0.03%   |
| Apple                                 | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 271       | 7.5%    |
| Intel Wireless 8265 / 8275                                     | 173       | 4.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 165       | 4.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 136       | 3.76%   |
| Intel Wireless 7260                                            | 126       | 3.49%   |
| Intel Wireless 7265                                            | 123       | 3.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 117       | 3.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 112       | 3.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 112       | 3.1%    |
| Intel Wi-Fi 6 AX201                                            | 108       | 2.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 103       | 2.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 92        | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 87        | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 82        | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 81        | 2.24%   |
| Intel Wireless 8260                                            | 79        | 2.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 76        | 2.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 72        | 1.99%   |
| Intel Wireless 3165                                            | 63        | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 61        | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 57        | 1.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 41        | 1.13%   |
| Intel Wireless 3160                                            | 40        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 40        | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 40        | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 39        | 1.08%   |
| Intel Wireless-AC 9260                                         | 38        | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 38        | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 36        | 1%      |
| Broadcom BCM43142 802.11b/g/n                                  | 36        | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 34        | 0.94%   |
| Intel Centrino Wireless-N 2230                                 | 34        | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 32        | 0.89%   |
| Intel Centrino Advanced-N 6235                                 | 28        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                 | 26        | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 22        | 0.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 22        | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 21        | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 20        | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 20        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1705      | 61.53%  |
| Intel                                  | 557       | 20.1%   |
| Qualcomm Atheros                       | 185       | 6.68%   |
| Broadcom                               | 93        | 3.36%   |
| ASIX Electronics                       | 28        | 1.01%   |
| Marvell Technology Group               | 24        | 0.87%   |
| Xiaomi                                 | 23        | 0.83%   |
| Lenovo                                 | 21        | 0.76%   |
| Broadcom Limited                       | 19        | 0.69%   |
| DisplayLink                            | 18        | 0.65%   |
| MediaTek                               | 16        | 0.58%   |
| JMicron Technology                     | 12        | 0.43%   |
| Samsung Electronics                    | 10        | 0.36%   |
| Nvidia                                 | 9         | 0.32%   |
| Qualcomm                               | 6         | 0.22%   |
| Huawei Technologies                    | 6         | 0.22%   |
| TP-Link                                | 5         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.14%   |
| Google                                 | 4         | 0.14%   |
| Hewlett-Packard                        | 3         | 0.11%   |
| Apple                                  | 3         | 0.11%   |
| Spreadtrum Communications              | 2         | 0.07%   |
| Motorola PCS                           | 2         | 0.07%   |
| ICS Advent                             | 2         | 0.07%   |
| Attansic Technology                    | 2         | 0.07%   |
| ASUSTek Computer                       | 2         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| OPPO                                   | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1235      | 43.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 310       | 11.04%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 137       | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 120       | 4.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 39        | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 39        | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 36        | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 1.17%   |
| Intel Ethernet Connection I218-LM                                 | 33        | 1.17%   |
| Intel Ethernet Connection I217-LM                                 | 33        | 1.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 28        | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.82%   |
| Intel Ethernet Connection (6) I219-V                              | 23        | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 20        | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18        | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 18        | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17        | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 17        | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 16        | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.57%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                             | 16        | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 14        | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14        | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 12        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11        | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 10        | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.36%   |
| Intel Ethernet Connection I217-V                                  | 10        | 0.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.36%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3403      | 55.89%  |
| Ethernet | 2653      | 43.57%  |
| Modem    | 30        | 0.49%   |
| Unknown  | 3         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2947      | 81.16%  |
| Ethernet | 684       | 18.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2415      | 69.92%  |
| 1     | 977       | 28.29%  |
| 0     | 35        | 1.01%   |
| 3     | 27        | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2963      | 84.66%  |
| Yes  | 537       | 15.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1522      | 53.38%  |
| Realtek Semiconductor           | 335       | 11.75%  |
| Qualcomm Atheros Communications | 290       | 10.17%  |
| IMC Networks                    | 148       | 5.19%   |
| Lite-On Technology              | 129       | 4.52%   |
| Broadcom                        | 95        | 3.33%   |
| Apple                           | 70        | 2.46%   |
| Foxconn / Hon Hai               | 69        | 2.42%   |
| Realtek                         | 36        | 1.26%   |
| Cambridge Silicon Radio         | 31        | 1.09%   |
| Dell                            | 23        | 0.81%   |
| Ralink                          | 22        | 0.77%   |
| Hewlett-Packard                 | 17        | 0.6%    |
| Toshiba                         | 13        | 0.46%   |
| Foxconn International           | 9         | 0.32%   |
| Opticis                         | 7         | 0.25%   |
| ASUSTek Computer                | 7         | 0.25%   |
| Ralink Technology               | 6         | 0.21%   |
| Alps Electric                   | 5         | 0.18%   |
| Askey Computer                  | 4         | 0.14%   |
| MediaTek                        | 3         | 0.11%   |
| Fujitsu                         | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| USI                             | 1         | 0.04%   |
| TP-Link                         | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Dynex                           | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 560       | 19.63%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 266       | 9.32%   |
| Intel AX200 Bluetooth                               | 260       | 9.11%   |
| Intel AX201 Bluetooth                               | 243       | 8.52%   |
| Realtek Bluetooth Radio                             | 206       | 7.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 142       | 4.98%   |
| Realtek  Bluetooth 4.2 Adapter                      | 84        | 2.94%   |
| IMC Networks Bluetooth Radio                        | 60        | 2.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 55        | 1.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 47        | 1.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 42        | 1.47%   |
| Intel AX210 Bluetooth                               | 39        | 1.37%   |
| Lite-On Bluetooth Device                            | 37        | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 37        | 1.3%    |
| Apple Bluetooth Host Controller                     | 36        | 1.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 35        | 1.23%   |
| IMC Networks Bluetooth Device                       | 35        | 1.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 1.16%   |
| Realtek 802.11ac WLAN Adapter                       | 32        | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 32        | 1.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31        | 1.09%   |
| Foxconn / Hon Hai Bluetooth Device                  | 29        | 1.02%   |
| Apple Bluetooth USB Host Controller                 | 28        | 0.98%   |
| IMC Networks Wireless_Device                        | 25        | 0.88%   |
| Ralink RT3290 Bluetooth                             | 22        | 0.77%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 20        | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 19        | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 16        | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 15        | 0.53%   |
| Realtek RTL8821A Bluetooth                          | 15        | 0.53%   |
| Intel Bluetooth Device                              | 15        | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.46%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.42%   |
| Lite-On Wireless_Device                             | 10        | 0.35%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 0.35%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.35%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 9         | 0.32%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2636      | 62.21%  |
| AMD                                  | 831       | 19.61%  |
| Nvidia                               | 488       | 11.52%  |
| C-Media Electronics                  | 35        | 0.83%   |
| Realtek Semiconductor                | 23        | 0.54%   |
| Logitech                             | 23        | 0.54%   |
| Lenovo                               | 21        | 0.5%    |
| GN Netcom                            | 18        | 0.42%   |
| Kingston Technology                  | 13        | 0.31%   |
| JMTek                                | 12        | 0.28%   |
| Texas Instruments                    | 9         | 0.21%   |
| SteelSeries ApS                      | 9         | 0.21%   |
| Plantronics                          | 9         | 0.21%   |
| Generalplus Technology               | 8         | 0.19%   |
| Apple                                | 8         | 0.19%   |
| Focusrite-Novation                   | 6         | 0.14%   |
| Hewlett-Packard                      | 5         | 0.12%   |
| GYROCOM C&C                          | 5         | 0.12%   |
| Samson Technologies                  | 4         | 0.09%   |
| Razer USA                            | 4         | 0.09%   |
| Creative Technology                  | 4         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.07%   |
| RODE Microphones                     | 3         | 0.07%   |
| Huawei Technologies                  | 3         | 0.07%   |
| DSEA A/S                             | 3         | 0.07%   |
| Corsair                              | 3         | 0.07%   |
| Sony                                 | 2         | 0.05%   |
| Samsung Electronics                  | 2         | 0.05%   |
| DCMT Technology                      | 2         | 0.05%   |
| Cambridge Silicon Radio              | 2         | 0.05%   |
| Blue Microphones                     | 2         | 0.05%   |
| ASUSTek Computer                     | 2         | 0.05%   |
| Astro Gaming                         | 2         | 0.05%   |
| Alesis                               | 2         | 0.05%   |
| Yealink Network Technology           | 1         | 0.02%   |
| Yamaha                               | 1         | 0.02%   |
| VIA Technologies                     | 1         | 0.02%   |
| Trust                                | 1         | 0.02%   |
| TC Electronic                        | 1         | 0.02%   |
| Syntek                               | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 574       | 10.84%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 434       | 8.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 288       | 5.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 287       | 5.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 209       | 3.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 179       | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 163       | 3.08%   |
| Intel 8 Series HD Audio Controller                                                                | 156       | 2.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 155       | 2.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 150       | 2.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 147       | 2.78%   |
| Intel Broadwell-U Audio Controller                                                                | 140       | 2.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 139       | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 122       | 2.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 104       | 1.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 99        | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 95        | 1.79%   |
| Intel CM238 HD Audio Controller                                                                   | 95        | 1.79%   |
| AMD FCH Azalia Controller                                                                         | 89        | 1.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 76        | 1.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 70        | 1.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 69        | 1.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 64        | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                                          | 64        | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 63        | 1.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 54        | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 53        | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 49        | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 46        | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 41        | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 36        | 0.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 35        | 0.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 34        | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 33        | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 32        | 0.6%    |
| AMD High Definition Audio Controller                                                              | 32        | 0.6%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 30        | 0.57%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 29        | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 29        | 0.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 29        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 836       | 32.06%  |
| SK hynix            | 558       | 21.4%   |
| Micron Technology   | 355       | 13.61%  |
| Kingston            | 234       | 8.97%   |
| Crucial             | 120       | 4.6%    |
| Unknown             | 95        | 3.64%   |
| Ramaxel Technology  | 62        | 2.38%   |
| A-DATA Technology   | 61        | 2.34%   |
| Elpida              | 45        | 1.73%   |
| Corsair             | 35        | 1.34%   |
| Nanya Technology    | 30        | 1.15%   |
| G.Skill             | 23        | 0.88%   |
| Smart               | 17        | 0.65%   |
| GOODRAM             | 16        | 0.61%   |
| Unknown (ABCD)      | 15        | 0.58%   |
| Transcend           | 13        | 0.5%    |
| Patriot             | 12        | 0.46%   |
| Team                | 9         | 0.35%   |
| Apacer              | 7         | 0.27%   |
| Unknown             | 7         | 0.27%   |
| ASint Technology    | 6         | 0.23%   |
| AMD                 | 5         | 0.19%   |
| Teikon              | 4         | 0.15%   |
| Goldkey             | 4         | 0.15%   |
| Smart Brazil        | 3         | 0.12%   |
| Silicon Power       | 3         | 0.12%   |
| SHARETRONIC         | 3         | 0.12%   |
| Avant               | 3         | 0.12%   |
| Atermiter           | 3         | 0.12%   |
| Timetec             | 2         | 0.08%   |
| Qumo                | 2         | 0.08%   |
| Qimonda             | 2         | 0.08%   |
| Kllisre             | 2         | 0.08%   |
| V-Color             | 1         | 0.04%   |
| Unknown (768A)      | 1         | 0.04%   |
| Unknown (0x8AF1)    | 1         | 0.04%   |
| Unknown (0x0B6B)    | 1         | 0.04%   |
| Unknown (0x02BA)    | 1         | 0.04%   |
| Unknown (08B5)      | 1         | 0.04%   |
| Unknown (08AE)      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 56        | 2.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 51        | 1.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 44        | 1.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 1.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 35        | 1.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 34        | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 30        | 1.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 29        | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 28        | 1.02%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 26        | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 25        | 0.91%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 25        | 0.91%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.91%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.87%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.84%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 23        | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 19        | 0.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 18        | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 18        | 0.66%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 18        | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.62%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.62%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 15        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 13        | 0.47%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 13        | 0.47%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 13        | 0.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 12        | 0.44%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 12        | 0.44%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s         | 12        | 0.44%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.4%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1204      | 55.36%  |
| DDR3    | 666       | 30.62%  |
| LPDDR4  | 111       | 5.1%    |
| LPDDR3  | 99        | 4.55%   |
| SDRAM   | 33        | 1.52%   |
| DDR2    | 31        | 1.43%   |
| DDR5    | 15        | 0.69%   |
| LPDDR5  | 8         | 0.37%   |
| Unknown | 4         | 0.18%   |
| DRAM    | 2         | 0.09%   |
| DDR     | 2         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1888      | 86.49%  |
| Row Of Chips | 264       | 12.09%  |
| Chip         | 17        | 0.78%   |
| Unknown      | 8         | 0.37%   |
| DIMM         | 6         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1042      | 43.86%  |
| 4096  | 750       | 31.57%  |
| 16384 | 314       | 13.22%  |
| 2048  | 189       | 7.95%   |
| 32768 | 55        | 2.31%   |
| 1024  | 25        | 1.05%   |
| 512   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 603       | 25.33%  |
| 1600    | 514       | 21.59%  |
| 3200    | 436       | 18.31%  |
| 2400    | 206       | 8.65%   |
| 2133    | 151       | 6.34%   |
| 1334    | 91        | 3.82%   |
| 1333    | 56        | 2.35%   |
| 3266    | 51        | 2.14%   |
| 4267    | 48        | 2.02%   |
| 1867    | 31        | 1.3%    |
| 4199    | 25        | 1.05%   |
| 1067    | 25        | 1.05%   |
| 667     | 19        | 0.8%    |
| Unknown | 19        | 0.8%    |
| 4800    | 16        | 0.67%   |
| 4266    | 16        | 0.67%   |
| 800     | 12        | 0.5%    |
| 975     | 9         | 0.38%   |
| 6400    | 7         | 0.29%   |
| 1066    | 7         | 0.29%   |
| 8400    | 6         | 0.25%   |
| 3733    | 6         | 0.25%   |
| 2048    | 6         | 0.25%   |
| 2933    | 4         | 0.17%   |
| 1866    | 3         | 0.13%   |
| 3000    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 333     | 2         | 0.08%   |
| 65535   | 1         | 0.04%   |
| 3600    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |
| 888     | 1         | 0.04%   |
| 666     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 29.63%  |
| Seiko Epson         | 6         | 22.22%  |
| Brother Industries  | 4         | 14.81%  |
| Canon               | 3         | 11.11%  |
| Samsung Electronics | 2         | 7.41%   |
| Xiaomi              | 1         | 3.7%    |
| Sagem               | 1         | 3.7%    |
| Kyocera             | 1         | 3.7%    |
| Dymo-CoStar         | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| HP ENVY 4520 series                                    | 2         | 7.41%   |
| Brother HL-L2300D series                               | 2         | 7.41%   |
| Xiaomi MiMouse 2                                       | 1         | 3.7%    |
| Seiko Epson Printer                                    | 1         | 3.7%    |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 3.7%    |
| Seiko Epson L365 Series                                | 1         | 3.7%    |
| Seiko Epson L355 Series                                | 1         | 3.7%    |
| Seiko Epson ET-2850 Series                             | 1         | 3.7%    |
| Seiko Epson ET-2710 Series                             | 1         | 3.7%    |
| Samsung ML-1865                                        | 1         | 3.7%    |
| Samsung CLX-3180 Series                                | 1         | 3.7%    |
| Sagem Laser Pro LL                                     | 1         | 3.7%    |
| Kyocera FS-1030D printer                               | 1         | 3.7%    |
| HP Officejet 4500 G510g-m                              | 1         | 3.7%    |
| HP LaserJet P1102                                      | 1         | 3.7%    |
| HP Ink Tank Wireless 410 series                        | 1         | 3.7%    |
| HP Ink Tank 310 series                                 | 1         | 3.7%    |
| HP DeskJet 2700 series                                 | 1         | 3.7%    |
| HP DeskJet 1110 series                                 | 1         | 3.7%    |
| Dymo-CoStar DYMO LabelWriter 450 Twin Turbo            | 1         | 3.7%    |
| Canon TS300 series                                     | 1         | 3.7%    |
| Canon TR4500 series                                    | 1         | 3.7%    |
| Canon G4010 series                                     | 1         | 3.7%    |
| Brother QL-500 label printer                           | 1         | 3.7%    |
| Brother MFC-L2710DW series                             | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 7         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20     | 2         | 28.57%  |
| Canon CanoScan LiDE 220                | 2         | 28.57%  |
| Canon CanoScan LiDE 500F               | 1         | 14.29%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 14.29%  |
| Canon CanoScan LiDE 110                | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 753       | 23.85%  |
| IMC Networks                           | 445       | 14.1%   |
| Acer                                   | 280       | 8.87%   |
| Realtek Semiconductor                  | 269       | 8.52%   |
| Microdia                               | 241       | 7.63%   |
| Quanta                                 | 179       | 5.67%   |
| Sunplus Innovation Technology          | 164       | 5.19%   |
| Cheng Uei Precision Industry (Foxlink) | 123       | 3.9%    |
| Lite-On Technology                     | 101       | 3.2%    |
| Syntek                                 | 98        | 3.1%    |
| Suyin                                  | 84        | 2.66%   |
| Apple                                  | 59        | 1.87%   |
| Silicon Motion                         | 51        | 1.62%   |
| Logitech                               | 46        | 1.46%   |
| Alcor Micro                            | 37        | 1.17%   |
| Luxvisions Innotech Limited            | 30        | 0.95%   |
| Samsung Electronics                    | 19        | 0.6%    |
| Ricoh                                  | 18        | 0.57%   |
| Lenovo                                 | 14        | 0.44%   |
| DLEQNA19IFK6G2                         | 12        | 0.38%   |
| Microsoft                              | 11        | 0.35%   |
| Primax Electronics                     | 10        | 0.32%   |
| Importek                               | 10        | 0.32%   |
| Sonix Technology                       | 9         | 0.29%   |
| DigiTech                               | 7         | 0.22%   |
| ALi                                    | 6         | 0.19%   |
| Intel                                  | 5         | 0.16%   |
| Denron                                 | 5         | 0.16%   |
| Z-Star Microelectronics                | 4         | 0.13%   |
| SunplusIT                              | 4         | 0.13%   |
| OmniVision Technologies                | 4         | 0.13%   |
| icSpring                               | 4         | 0.13%   |
| Genesys Logic                          | 4         | 0.13%   |
| GEMBIRD                                | 4         | 0.13%   |
| Y Media                                | 3         | 0.1%    |
| Creative Technology                    | 3         | 0.1%    |
| ARC International                      | 3         | 0.1%    |
| USB Camera CS                          | 2         | 0.06%   |
| Unknown                                | 2         | 0.06%   |
| MacroSilicon                           | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 197       | 6.21%   |
| IMC Networks Integrated Camera          | 140       | 4.41%   |
| Microdia Integrated_Webcam_HD           | 127       | 4%      |
| IMC Networks USB2.0 HD UVC WebCam       | 110       | 3.47%   |
| Realtek Integrated_Webcam_HD            | 95        | 2.99%   |
| Acer Integrated Camera                  | 92        | 2.9%    |
| Chicony HD WebCam                       | 90        | 2.84%   |
| Syntek Integrated Camera                | 64        | 2.02%   |
| Sunplus Integrated_Webcam_HD            | 52        | 1.64%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 42        | 1.32%   |
| Lite-On Integrated Camera               | 37        | 1.17%   |
| Acer HD Webcam                          | 34        | 1.07%   |
| Acer Lenovo EasyCamera                  | 29        | 0.91%   |
| Quanta HP TrueVision HD Camera          | 28        | 0.88%   |
| Quanta HD User Facing                   | 28        | 0.88%   |
| Chicony HP HD Camera                    | 27        | 0.85%   |
| Lite-On HP HD Camera                    | 26        | 0.82%   |
| Chicony USB2.0 Camera                   | 26        | 0.82%   |
| Quanta HD Webcam                        | 24        | 0.76%   |
| Acer SunplusIT Integrated Camera        | 24        | 0.76%   |
| Microdia Integrated Webcam              | 23        | 0.72%   |
| Chicony USB2.0 HD UVC WebCam            | 23        | 0.72%   |
| Chicony HD User Facing                  | 23        | 0.72%   |
| IMC Networks HD Camera                  | 22        | 0.69%   |
| Chicony Lenovo EasyCamera               | 22        | 0.69%   |
| Acer BisonCam, NB Pro                   | 22        | 0.69%   |
| Realtek USB Camera                      | 21        | 0.66%   |
| Chicony EasyCamera                      | 21        | 0.66%   |
| Syntek Lenovo EasyCamera                | 20        | 0.63%   |
| Sunplus HD WebCam                       | 20        | 0.63%   |
| Samsung Galaxy A5 (MTP)                 | 19        | 0.6%    |
| Realtek USB2.0 HD UVC WebCam            | 19        | 0.6%    |
| Acer EasyCamera                         | 19        | 0.6%    |
| Quanta HP Wide Vision HD Camera         | 18        | 0.57%   |
| Microdia Laptop_Integrated_Webcam_HD    | 18        | 0.57%   |
| IMC Networks HP TrueVision HD Camera    | 18        | 0.57%   |
| Chicony USB2.0 VGA UVC WebCam           | 18        | 0.57%   |
| Chicony Integrated Camera (1280x720@30) | 18        | 0.57%   |
| Chicony HP Wide Vision HD Camera        | 18        | 0.57%   |
| Chicony HP TrueVision HD Camera         | 18        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 223       | 31.32%  |
| Synaptics                  | 191       | 26.83%  |
| Shenzhen Goodix Technology | 151       | 21.21%  |
| Elan Microelectronics      | 53        | 7.44%   |
| LighTuning Technology      | 31        | 4.35%   |
| Upek                       | 27        | 3.79%   |
| AuthenTec                  | 19        | 2.67%   |
| STMicroelectronics         | 7         | 0.98%   |
| Focal-systems.Corp         | 4         | 0.56%   |
| Samsung Electronics        | 3         | 0.42%   |
| DigitalPersona             | 2         | 0.28%   |
| HOLTEK                     | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 81        | 11.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 62        | 8.71%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 49        | 6.88%   |
| Unknown                                                                    | 47        | 6.6%    |
| Shenzhen Goodix Fingerprint Reader                                         | 42        | 5.9%    |
| Elan ELAN:Fingerprint                                                      | 35        | 4.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 34        | 4.78%   |
| Shenzhen Goodix FingerPrint                                                | 28        | 3.93%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 3.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 2.95%   |
| Validity Sensors Synaptics WBDI                                            | 20        | 2.81%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 19        | 2.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 2.39%   |
| Elan ELAN:ARM-M4                                                           | 17        | 2.39%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 16        | 2.25%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.97%   |
| Validity Sensors VFS491                                                    | 14        | 1.97%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 1.97%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.69%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.54%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.26%   |
| Synaptics  WBDI                                                            | 9         | 1.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.26%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.98%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.98%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.98%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.7%    |
| Synaptics WBDI Device                                                      | 5         | 0.7%    |
| AuthenTec AES2810                                                          | 5         | 0.7%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 0.56%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 0.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.42%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.42%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.42%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.28%   |
| Samsung Fingerprint Device                                                 | 2         | 0.28%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 85        | 36.8%   |
| Alcor Micro               | 80        | 34.63%  |
| Upek                      | 16        | 6.93%   |
| O2 Micro                  | 16        | 6.93%   |
| Lenovo                    | 16        | 6.93%   |
| Yubico.com                | 8         | 3.46%   |
| Gemalto (was Gemplus)     | 3         | 1.3%    |
| Reiner SCT Kartensysteme  | 1         | 0.43%   |
| OmniKey                   | 1         | 0.43%   |
| Hewlett-Packard           | 1         | 0.43%   |
| Clay Logic                | 1         | 0.43%   |
| C3PO                      | 1         | 0.43%   |
| Aladdin Knowledge Systems | 1         | 0.43%   |
| Advanced Card Systems     | 1         | 0.43%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 80        | 34.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 14.72%  |
| Broadcom 5880                                                                | 24        | 10.39%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 6.93%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.93%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 6.49%   |
| Broadcom 58200                                                               | 15        | 6.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 5.19%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 3.03%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.87%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 0.43%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.43%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.43%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.43%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.43%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.43%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.43%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.43%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.43%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.43%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2089      | 59.31%  |
| 1     | 1132      | 32.14%  |
| 2     | 276       | 7.84%   |
| 3     | 22        | 0.62%   |
| 4     | 3         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 697       | 40.86%  |
| Graphics card            | 342       | 20.05%  |
| Chipcard                 | 207       | 12.13%  |
| Multimedia controller    | 134       | 7.85%   |
| Net/wireless             | 129       | 7.56%   |
| Camera                   | 57        | 3.34%   |
| Net/ethernet             | 46        | 2.7%    |
| Bluetooth                | 34        | 1.99%   |
| Storage                  | 19        | 1.11%   |
| Card reader              | 15        | 0.88%   |
| Sound                    | 8         | 0.47%   |
| Communication controller | 7         | 0.41%   |
| Modem                    | 4         | 0.23%   |
| Network                  | 3         | 0.18%   |
| Storage/nvme             | 2         | 0.12%   |
| Dvb card                 | 2         | 0.12%   |


Linux in Switzerland - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

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

Total: 1319

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ZBook Studio G3             | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| Apple         | MacBookPro14,2              | [ff0dfe765e](https://linux-hardware.org/?probe=ff0dfe765e) | Jan 31, 2023 |
| Acer          | Aspire A715-75G             | [59a0c6f08f](https://linux-hardware.org/?probe=59a0c6f08f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [fddcdb0f47](https://linux-hardware.org/?probe=fddcdb0f47) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| Dell          | XPS 13 9360                 | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Laptop 15-dw3xxx            | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| Dell          | XPS 13 9380                 | [0192877edc](https://linux-hardware.org/?probe=0192877edc) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [873a521bf5](https://linux-hardware.org/?probe=873a521bf5) | Jan 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | [37fd07b937](https://linux-hardware.org/?probe=37fd07b937) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Lenovo        | B50-10 80QR                 | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| HP            | ProBook 650 G4              | [340bddf38d](https://linux-hardware.org/?probe=340bddf38d) | Jan 16, 2023 |
| HP            | EliteBook 2560p             | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | [1f30a57359](https://linux-hardware.org/?probe=1f30a57359) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [182eb9ffa1](https://linux-hardware.org/?probe=182eb9ffa1) | Jan 12, 2023 |
| Acer          | Aspire E5-511               | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Acer          | Aspire V3-772G              | [bd0adf87e3](https://linux-hardware.org/?probe=bd0adf87e3) | Jan 08, 2023 |
| ASUSTek       | K53U                        | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Alienware     | 17 R3                       | [f94b2fc95f](https://linux-hardware.org/?probe=f94b2fc95f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0016M... | [b48981da6d](https://linux-hardware.org/?probe=b48981da6d) | Jan 06, 2023 |
| Acer          | Predator G9-591             | [160b31ea8f](https://linux-hardware.org/?probe=160b31ea8f) | Jan 06, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| MSI           | Katana GF66 11SC            | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [8c9e803e01](https://linux-hardware.org/?probe=8c9e803e01) | Jan 01, 2023 |
| Valve         | Jupiter                     | [82b86d954a](https://linux-hardware.org/?probe=82b86d954a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | [bcb9b7a061](https://linux-hardware.org/?probe=bcb9b7a061) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| Dell          | XPS 13 9380                 | [a73fe5e678](https://linux-hardware.org/?probe=a73fe5e678) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| Acer          | Swift SF314-511             | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| ASUSTek       | X556UAK                     | [803a4e58e0](https://linux-hardware.org/?probe=803a4e58e0) | Dec 25, 2022 |
| HP            | ProBook 450 G7              | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [2d50f93c7f](https://linux-hardware.org/?probe=2d50f93c7f) | Dec 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [dac438be55](https://linux-hardware.org/?probe=dac438be55) | Dec 22, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [e160bf6ea0](https://linux-hardware.org/?probe=e160bf6ea0) | Dec 22, 2022 |
| Dell          | Inspiron 15 3511            | [e7bf0c0a09](https://linux-hardware.org/?probe=e7bf0c0a09) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | [9fca55febc](https://linux-hardware.org/?probe=9fca55febc) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | [57605a26eb](https://linux-hardware.org/?probe=57605a26eb) | Dec 19, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3a6e0b953f](https://linux-hardware.org/?probe=3a6e0b953f) | Dec 19, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | [7a528ca531](https://linux-hardware.org/?probe=7a528ca531) | Dec 17, 2022 |
| Acer          | Aspire E5-773               | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| HP            | Compaq 6830s                | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1129626fee](https://linux-hardware.org/?probe=1129626fee) | Dec 13, 2022 |
| Acer          | Aspire 7750                 | [9f0f4a8510](https://linux-hardware.org/?probe=9f0f4a8510) | Dec 12, 2022 |
| Acer          | Aspire 7750                 | [f7577f248a](https://linux-hardware.org/?probe=f7577f248a) | Dec 12, 2022 |
| ASUSTek       | X556UAK                     | [787ba0950d](https://linux-hardware.org/?probe=787ba0950d) | Dec 11, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Acer          | Swift SF314-511             | [c3c6c2f4fc](https://linux-hardware.org/?probe=c3c6c2f4fc) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| ASUSTek       | X556UAK                     | [637056cc12](https://linux-hardware.org/?probe=637056cc12) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | [15ca126de2](https://linux-hardware.org/?probe=15ca126de2) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | [eef6c9c624](https://linux-hardware.org/?probe=eef6c9c624) | Dec 08, 2022 |
| HP            | ENVY dv7                    | [8e8b9ecfb6](https://linux-hardware.org/?probe=8e8b9ecfb6) | Dec 04, 2022 |
| ASUSTek       | GL702ZC                     | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Dell          | XPS 15 9520                 | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Acer          | Predator PH317-56           | [ea1d794b18](https://linux-hardware.org/?probe=ea1d794b18) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | [19395b5e21](https://linux-hardware.org/?probe=19395b5e21) | Dec 02, 2022 |
| HP            | ProBook 6560b               | [c62ff16666](https://linux-hardware.org/?probe=c62ff16666) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8e0ea55ccc](https://linux-hardware.org/?probe=8e0ea55ccc) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | [7817399ec6](https://linux-hardware.org/?probe=7817399ec6) | Dec 02, 2022 |
| HP            | ENVY dv7                    | [60e3263ce2](https://linux-hardware.org/?probe=60e3263ce2) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| HP            | ENVY dv7                    | [1cef09f19a](https://linux-hardware.org/?probe=1cef09f19a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Notebook      | L140PU                      | [8893420e06](https://linux-hardware.org/?probe=8893420e06) | Nov 28, 2022 |
| Dell          | XPS 13 9370                 | [d353a1624b](https://linux-hardware.org/?probe=d353a1624b) | Nov 28, 2022 |
| Dell          | Latitude E6420              | [15ee6e2e20](https://linux-hardware.org/?probe=15ee6e2e20) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Apple         | MacBookAir6,2               | [8e266a1137](https://linux-hardware.org/?probe=8e266a1137) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | [080bbeb75a](https://linux-hardware.org/?probe=080bbeb75a) | Nov 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | [65c874adbd](https://linux-hardware.org/?probe=65c874adbd) | Nov 20, 2022 |
| Dell          | XPS 9320                    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| ASUSTek       | T100TA                      | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| HP            | Compaq 15                   | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| GPD           | G1619-04                    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [71a871168d](https://linux-hardware.org/?probe=71a871168d) | Nov 15, 2022 |
| Acer          | Aspire V3-771               | [5682e576ad](https://linux-hardware.org/?probe=5682e576ad) | Nov 14, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Apple         | MacBookPro4,1               | [69c1a004e6](https://linux-hardware.org/?probe=69c1a004e6) | Nov 03, 2022 |
| Dell          | XPS 13 9380                 | [9224a599b3](https://linux-hardware.org/?probe=9224a599b3) | Nov 03, 2022 |
| Dell          | Precision 5520              | [e1a819ec3e](https://linux-hardware.org/?probe=e1a819ec3e) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| GPD           | G1619-04                    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2W30... | [8e0c00531b](https://linux-hardware.org/?probe=8e0c00531b) | Oct 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6047d5d94a](https://linux-hardware.org/?probe=6047d5d94a) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
| HP            | ProBook 6570b               | [b5d48f6adb](https://linux-hardware.org/?probe=b5d48f6adb) | Oct 29, 2022 |
| Lenovo        | ThinkPad T420 4236NUG       | [d0e3fa9699](https://linux-hardware.org/?probe=d0e3fa9699) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c3bbb31b04](https://linux-hardware.org/?probe=c3bbb31b04) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | N750JK                      | [849800f3f3](https://linux-hardware.org/?probe=849800f3f3) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Medion        | S15449                      | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [f5073cd7a2](https://linux-hardware.org/?probe=f5073cd7a2) | Oct 20, 2022 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | [3e8ca06ac6](https://linux-hardware.org/?probe=3e8ca06ac6) | Oct 17, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Google        | Lars                        | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| HP            | ENVY 15                     | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | [67532c45cb](https://linux-hardware.org/?probe=67532c45cb) | Oct 12, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [5112d236ce](https://linux-hardware.org/?probe=5112d236ce) | Oct 12, 2022 |
| Samsung       | RC530/RC730                 | [ee62bfc634](https://linux-hardware.org/?probe=ee62bfc634) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Notebook      | W65_67SZ                    | [a3a056691b](https://linux-hardware.org/?probe=a3a056691b) | Oct 07, 2022 |
| Gigabyte      | RC14UD                      | [e48bdade3d](https://linux-hardware.org/?probe=e48bdade3d) | Oct 06, 2022 |
| Dell          | Latitude E6410              | [f7baa71813](https://linux-hardware.org/?probe=f7baa71813) | Oct 05, 2022 |
| HP            | ProBook 640 G2              | [e4cc03e802](https://linux-hardware.org/?probe=e4cc03e802) | Oct 03, 2022 |
| ASUSTek       | K55VJ                       | [e405dee0bd](https://linux-hardware.org/?probe=e405dee0bd) | Oct 02, 2022 |
| Gigabyte      | RC14UD                      | [744143bdd6](https://linux-hardware.org/?probe=744143bdd6) | Sep 30, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [9a1514cc61](https://linux-hardware.org/?probe=9a1514cc61) | Sep 26, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [fee2b2d57e](https://linux-hardware.org/?probe=fee2b2d57e) | Sep 24, 2022 |
| System76      | Darter Pro                  | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| System76      | Darter Pro                  | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Acer          | Aspire E5-571               | [dc6bf82565](https://linux-hardware.org/?probe=dc6bf82565) | Sep 22, 2022 |
| ASUSTek       | K56CB                       | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | [dddf15cbf5](https://linux-hardware.org/?probe=dddf15cbf5) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | [21404b14d1](https://linux-hardware.org/?probe=21404b14d1) | Sep 21, 2022 |
| HP            | EliteBook Folio 1040 G2     | [3aa36dda04](https://linux-hardware.org/?probe=3aa36dda04) | Sep 18, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [81d620ed2f](https://linux-hardware.org/?probe=81d620ed2f) | Sep 14, 2022 |
| HP            | Notebook                    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [4aa1954c0c](https://linux-hardware.org/?probe=4aa1954c0c) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | [e72b842ab6](https://linux-hardware.org/?probe=e72b842ab6) | Sep 10, 2022 |
| Acer          | Aspire S5-371               | [ed31a97b57](https://linux-hardware.org/?probe=ed31a97b57) | Sep 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| Acer          | Aspire 5942                 | [c2c893f2c2](https://linux-hardware.org/?probe=c2c893f2c2) | Sep 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [4808984401](https://linux-hardware.org/?probe=4808984401) | Aug 31, 2022 |
| Lenovo        | ThinkPad P43s 20RJS0D100    | [afbf0f6021](https://linux-hardware.org/?probe=afbf0f6021) | Aug 31, 2022 |
| Lenovo        | V330 81AX                   | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| Acer          | V3-771                      | [3efe8f2f41](https://linux-hardware.org/?probe=3efe8f2f41) | Aug 28, 2022 |
| Shuttle       | DS437                       | [9b866a79d6](https://linux-hardware.org/?probe=9b866a79d6) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| Acer          | Aspire 5942                 | [528e0a954b](https://linux-hardware.org/?probe=528e0a954b) | Aug 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [d0b18cffdb](https://linux-hardware.org/?probe=d0b18cffdb) | Aug 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [936ce5ca55](https://linux-hardware.org/?probe=936ce5ca55) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| Acer          | Predator G9-791             | [782f581f0b](https://linux-hardware.org/?probe=782f581f0b) | Aug 21, 2022 |
| Dell          | Inspiron 5570               | [a6de4113fa](https://linux-hardware.org/?probe=a6de4113fa) | Aug 17, 2022 |
| Apple         | MacBookPro13,3              | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| Panasonic     | CF-31JBGNNDM                | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [7817924a07](https://linux-hardware.org/?probe=7817924a07) | Aug 14, 2022 |
| HP            | Unknown                     | [7375604d06](https://linux-hardware.org/?probe=7375604d06) | Aug 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Acer          | Aspire V3-772G              | [283eb3c040](https://linux-hardware.org/?probe=283eb3c040) | Aug 06, 2022 |
| MSI           | GT72S 6QE                   | [9cb4896eba](https://linux-hardware.org/?probe=9cb4896eba) | Jul 28, 2022 |
| Lenovo        | ThinkPad T470s 20HGS36K0... | [caf10d48a0](https://linux-hardware.org/?probe=caf10d48a0) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| Lenovo        | ThinkPad P51 20HH001RMZ     | [3fee9267ba](https://linux-hardware.org/?probe=3fee9267ba) | Jul 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [44a5e2107e](https://linux-hardware.org/?probe=44a5e2107e) | Jul 27, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| Acer          | Aspire 5738                 | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Sony          | SVE1513R1EB                 | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Alienware     | 17 R5                       | [29b538f1c0](https://linux-hardware.org/?probe=29b538f1c0) | Jul 20, 2022 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | [51dd660f49](https://linux-hardware.org/?probe=51dd660f49) | Jul 20, 2022 |
| Acer          | V3-771                      | [809bd80b9a](https://linux-hardware.org/?probe=809bd80b9a) | Jul 17, 2022 |
| Lenovo        | ThinkPad T410 25379UG       | [00478c63ba](https://linux-hardware.org/?probe=00478c63ba) | Jul 16, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [41c6118825](https://linux-hardware.org/?probe=41c6118825) | Jul 15, 2022 |
| HP            | Pavilion dv7                | [4065c23b56](https://linux-hardware.org/?probe=4065c23b56) | Jul 15, 2022 |
| HP            | EliteBook 8540p             | [52a3abee65](https://linux-hardware.org/?probe=52a3abee65) | Jul 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [7a661a1449](https://linux-hardware.org/?probe=7a661a1449) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | [c8bf7e091c](https://linux-hardware.org/?probe=c8bf7e091c) | Jul 14, 2022 |
| HP            | EliteBook 8460p             | [c3f5c82808](https://linux-hardware.org/?probe=c3f5c82808) | Jul 14, 2022 |
| HP            | ProBook 440 G6              | [6a065093ba](https://linux-hardware.org/?probe=6a065093ba) | Jul 10, 2022 |
| HUAWEI        | KLVL-WXXW                   | [0e5d573899](https://linux-hardware.org/?probe=0e5d573899) | Jul 09, 2022 |
| HP            | EliteBook Folio 1040 G2     | [c58559e78c](https://linux-hardware.org/?probe=c58559e78c) | Jul 09, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d58dd09f25](https://linux-hardware.org/?probe=d58dd09f25) | Jul 06, 2022 |
| HP            | Pavilion dv7                | [ee1a040981](https://linux-hardware.org/?probe=ee1a040981) | Jul 06, 2022 |
| MSI           | GE62 2QF                    | [789826020e](https://linux-hardware.org/?probe=789826020e) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Dell          | Latitude 7530               | [0d40af60b2](https://linux-hardware.org/?probe=0d40af60b2) | Jul 01, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [9b8bb07ff0](https://linux-hardware.org/?probe=9b8bb07ff0) | Jul 01, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| Acer          | Aspire V3-772G              | [21cba60be3](https://linux-hardware.org/?probe=21cba60be3) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | [0dcbb35983](https://linux-hardware.org/?probe=0dcbb35983) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | [d8190f3da8](https://linux-hardware.org/?probe=d8190f3da8) | Jun 29, 2022 |
| HP            | ENVY dv7                    | [9f64d5f095](https://linux-hardware.org/?probe=9f64d5f095) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Dell          | Precision M6800             | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| HP            | ENVY dv7                    | [00ce30e950](https://linux-hardware.org/?probe=00ce30e950) | Jun 28, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [2103486702](https://linux-hardware.org/?probe=2103486702) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| HP            | EliteBook 8470p             | [2ba22aa099](https://linux-hardware.org/?probe=2ba22aa099) | Jun 22, 2022 |
| HP            | EliteBook 8470p             | [eea8da46bd](https://linux-hardware.org/?probe=eea8da46bd) | Jun 22, 2022 |
| HUAWEI        | MACH-WX9                    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| Acer          | Aspire V3-772G              | [21f78f9cf4](https://linux-hardware.org/?probe=21f78f9cf4) | Jun 19, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Lenovo        | G70-70 80HW                 | [de123e03c3](https://linux-hardware.org/?probe=de123e03c3) | Jun 16, 2022 |
| Lenovo        | G70-70 80HW                 | [31aa19ff98](https://linux-hardware.org/?probe=31aa19ff98) | Jun 16, 2022 |
| Clevo         | W150ER                      | [9121da24a8](https://linux-hardware.org/?probe=9121da24a8) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| HP            | 255 G8 Notebook PC          | [b31c452186](https://linux-hardware.org/?probe=b31c452186) | Jun 11, 2022 |
| Dell          | XPS 13 9380                 | [6a14acf011](https://linux-hardware.org/?probe=6a14acf011) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | [0fbc627b7e](https://linux-hardware.org/?probe=0fbc627b7e) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [13e2575e63](https://linux-hardware.org/?probe=13e2575e63) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | [878cae499d](https://linux-hardware.org/?probe=878cae499d) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | [0c53f7240c](https://linux-hardware.org/?probe=0c53f7240c) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| HUAWEI        | MACH-WX9                    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| Acer          | Swift SF515-51T             | [d4283c0b8b](https://linux-hardware.org/?probe=d4283c0b8b) | May 31, 2022 |
| Acer          | Swift SF515-51T             | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [e6145c7453](https://linux-hardware.org/?probe=e6145c7453) | May 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [03a4099a33](https://linux-hardware.org/?probe=03a4099a33) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Dell          | XPS 13 9380                 | [7220b6a007](https://linux-hardware.org/?probe=7220b6a007) | May 28, 2022 |
| Dell          | XPS 13 9380                 | [962defa2c3](https://linux-hardware.org/?probe=962defa2c3) | May 28, 2022 |
| HP            | ENVY TS 15                  | [cde5dba599](https://linux-hardware.org/?probe=cde5dba599) | May 27, 2022 |
| HP            | ENVY TS 15                  | [e6ee61fdd8](https://linux-hardware.org/?probe=e6ee61fdd8) | May 27, 2022 |
| Lenovo        | V320-17IKB 81AH             | [c5d9a03264](https://linux-hardware.org/?probe=c5d9a03264) | May 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [071bc80c0b](https://linux-hardware.org/?probe=071bc80c0b) | May 27, 2022 |
| Timi          | TM1613                      | [695d8d5ff0](https://linux-hardware.org/?probe=695d8d5ff0) | May 21, 2022 |
| Acer          | V3-771                      | [8bcab66496](https://linux-hardware.org/?probe=8bcab66496) | May 20, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [61c1716210](https://linux-hardware.org/?probe=61c1716210) | May 16, 2022 |
| Dell          | XPS 15 7590                 | [7f7463682a](https://linux-hardware.org/?probe=7f7463682a) | May 16, 2022 |
| HP            | Notebook                    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| TUXEDO        | N2x0WU                      | [b70a08c999](https://linux-hardware.org/?probe=b70a08c999) | May 12, 2022 |
| Lenovo        | ThinkPad W530 2463A64       | [f45c19aa6c](https://linux-hardware.org/?probe=f45c19aa6c) | May 11, 2022 |
| Sony          | VPCF23S1E                   | [5eb4b61ffb](https://linux-hardware.org/?probe=5eb4b61ffb) | May 10, 2022 |
| Toshiba       | TECRA R840                  | [38ff1a3344](https://linux-hardware.org/?probe=38ff1a3344) | May 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Apple         | MacBookPro9,2               | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| Dell          | Inspiron 1720               | [e95b0172b4](https://linux-hardware.org/?probe=e95b0172b4) | May 06, 2022 |
| Dell          | Inspiron 1720               | [a888a93774](https://linux-hardware.org/?probe=a888a93774) | May 06, 2022 |
| HP            | ProBook 450 G4              | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [94806fd9bf](https://linux-hardware.org/?probe=94806fd9bf) | May 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ebc49550d4](https://linux-hardware.org/?probe=ebc49550d4) | May 05, 2022 |
| Apple         | MacBookPro11,3              | [21f611f3c7](https://linux-hardware.org/?probe=21f611f3c7) | May 03, 2022 |
| Dell          | XPS 13 9380                 | [aa294d2650](https://linux-hardware.org/?probe=aa294d2650) | May 02, 2022 |
| Acer          | Aspire A515-56              | [a10b79694f](https://linux-hardware.org/?probe=a10b79694f) | Apr 29, 2022 |
| HP            | ENVY 17                     | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| Dell          | XPS 13 9380                 | [c052066ee4](https://linux-hardware.org/?probe=c052066ee4) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [85cc720515](https://linux-hardware.org/?probe=85cc720515) | Apr 24, 2022 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | [1cabdda156](https://linux-hardware.org/?probe=1cabdda156) | Apr 21, 2022 |
| Lenovo        | ThinkPad E580 20KS006EMZ    | [4d54c594ff](https://linux-hardware.org/?probe=4d54c594ff) | Apr 20, 2022 |
| System76      | Galago Pro                  | [32b09fd215](https://linux-hardware.org/?probe=32b09fd215) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | [451ce5305a](https://linux-hardware.org/?probe=451ce5305a) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | [fa843a199c](https://linux-hardware.org/?probe=fa843a199c) | Apr 19, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [6d63a9c8bc](https://linux-hardware.org/?probe=6d63a9c8bc) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Acer          | TMP455-M                    | [451dbf0a20](https://linux-hardware.org/?probe=451dbf0a20) | Apr 15, 2022 |
| Acer          | TMP455-M                    | [b7b9924190](https://linux-hardware.org/?probe=b7b9924190) | Apr 15, 2022 |
| Acer          | Swift SF514-51              | [147a0161aa](https://linux-hardware.org/?probe=147a0161aa) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NY000JM... | [e93e7d9ad1](https://linux-hardware.org/?probe=e93e7d9ad1) | Apr 13, 2022 |
| Dell          | Latitude E7240              | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Lenovo        | ThinkPad Helix 36986CG      | [f0aa04a603](https://linux-hardware.org/?probe=f0aa04a603) | Apr 12, 2022 |
| Dell          | Latitude D400               | [46981d939b](https://linux-hardware.org/?probe=46981d939b) | Apr 11, 2022 |
| Apple         | MacBookPro10,1              | [b53427c0f4](https://linux-hardware.org/?probe=b53427c0f4) | Apr 07, 2022 |
| HP            | ProBook 4530s               | [1b32584f41](https://linux-hardware.org/?probe=1b32584f41) | Apr 06, 2022 |
| HP            | ProBook 4530s               | [f4dfc894d9](https://linux-hardware.org/?probe=f4dfc894d9) | Apr 06, 2022 |
| HP            | ProBook 450 G5              | [3aa8c7cbc6](https://linux-hardware.org/?probe=3aa8c7cbc6) | Apr 04, 2022 |
| Acer          | Swift SF314-57              | [e43f33eef1](https://linux-hardware.org/?probe=e43f33eef1) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | [5090da9cbf](https://linux-hardware.org/?probe=5090da9cbf) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | [2388fe9587](https://linux-hardware.org/?probe=2388fe9587) | Apr 03, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Acer          | Aspire E5-773G              | [b43b436e59](https://linux-hardware.org/?probe=b43b436e59) | Mar 31, 2022 |
| HP            | Pavilion g7                 | [44a6ea06b0](https://linux-hardware.org/?probe=44a6ea06b0) | Mar 28, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [edbd5fd6aa](https://linux-hardware.org/?probe=edbd5fd6aa) | Mar 27, 2022 |
| Lenovo        | ThinkPad T430 2349U4B       | [95526f5b3e](https://linux-hardware.org/?probe=95526f5b3e) | Mar 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [ed949b0853](https://linux-hardware.org/?probe=ed949b0853) | Mar 24, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [684a4fd3c3](https://linux-hardware.org/?probe=684a4fd3c3) | Mar 24, 2022 |
| Dell          | XPS 15 7590                 | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Dell          | Inspiron 7400               | [a17dc3be48](https://linux-hardware.org/?probe=a17dc3be48) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| HP            | EliteBook 840 G5            | [dd13dcfd89](https://linux-hardware.org/?probe=dd13dcfd89) | Mar 22, 2022 |
| ASUSTek       | K73E                        | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [7664c536f4](https://linux-hardware.org/?probe=7664c536f4) | Mar 18, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [7649fad366](https://linux-hardware.org/?probe=7649fad366) | Mar 14, 2022 |
| Dell          | Latitude 5400               | [e23429d8ea](https://linux-hardware.org/?probe=e23429d8ea) | Mar 13, 2022 |
| Fujitsu       | LIFEBOOK E782               | [77b3a7f272](https://linux-hardware.org/?probe=77b3a7f272) | Mar 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f735730566](https://linux-hardware.org/?probe=f735730566) | Mar 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e8ffb57db8](https://linux-hardware.org/?probe=e8ffb57db8) | Mar 11, 2022 |
| Acer          | Aspire V3-772G              | [1526117b64](https://linux-hardware.org/?probe=1526117b64) | Mar 10, 2022 |
| HP            | ProBook 470 G5              | [c98fcbec3c](https://linux-hardware.org/?probe=c98fcbec3c) | Mar 10, 2022 |
| HUAWEI        | WRT-WX9                     | [2bd4f9201a](https://linux-hardware.org/?probe=2bd4f9201a) | Mar 09, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Dell          | XPS 13 9350                 | [ce5fd5227f](https://linux-hardware.org/?probe=ce5fd5227f) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| HP            | EliteBook 820 G3            | [fd01513251](https://linux-hardware.org/?probe=fd01513251) | Mar 04, 2022 |
| Acer          | Swift SF314-42              | [5c8b94d514](https://linux-hardware.org/?probe=5c8b94d514) | Mar 03, 2022 |
| Dell          | XPS 13 9370                 | [75b63c2d2c](https://linux-hardware.org/?probe=75b63c2d2c) | Mar 02, 2022 |
| Medion        | P6624                       | [0a502fd230](https://linux-hardware.org/?probe=0a502fd230) | Feb 28, 2022 |
| Dell          | XPS 15 9560                 | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| Notebook      | N13xWU                      | [50acf36954](https://linux-hardware.org/?probe=50acf36954) | Feb 25, 2022 |
| Acer          | TMP455-MG                   | [f1a500ae43](https://linux-hardware.org/?probe=f1a500ae43) | Feb 25, 2022 |
| Dell          | Precision 3551              | [9394fc8844](https://linux-hardware.org/?probe=9394fc8844) | Feb 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [923930ee4e](https://linux-hardware.org/?probe=923930ee4e) | Feb 22, 2022 |
| Dell          | XPS 15 9570                 | [226452fec0](https://linux-hardware.org/?probe=226452fec0) | Feb 21, 2022 |
| ASUSTek       | G551JK                      | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [b0e0d82d12](https://linux-hardware.org/?probe=b0e0d82d12) | Feb 20, 2022 |
| Dell          | Latitude 7490               | [2620ebab43](https://linux-hardware.org/?probe=2620ebab43) | Feb 15, 2022 |
| Acer          | Aspire 3820                 | [7364dc5d5e](https://linux-hardware.org/?probe=7364dc5d5e) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | [34bb725d27](https://linux-hardware.org/?probe=34bb725d27) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | [3dd59d8ebe](https://linux-hardware.org/?probe=3dd59d8ebe) | Feb 13, 2022 |
| HP            | Compaq 15                   | [fa22db8854](https://linux-hardware.org/?probe=fa22db8854) | Feb 12, 2022 |
| Acer          | Aspire V3-772G              | [6a16b1953c](https://linux-hardware.org/?probe=6a16b1953c) | Feb 11, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [8b31b460fc](https://linux-hardware.org/?probe=8b31b460fc) | Feb 11, 2022 |
| PC Special... | NH5x_7xRCx,RDx              | [3fad293703](https://linux-hardware.org/?probe=3fad293703) | Feb 10, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | [e06f742b06](https://linux-hardware.org/?probe=e06f742b06) | Feb 09, 2022 |
| whyopencom... | Unknown                     | [ed4f02d91d](https://linux-hardware.org/?probe=ed4f02d91d) | Feb 09, 2022 |
| HP            | Pavilion 11 x360 PC         | [f252168753](https://linux-hardware.org/?probe=f252168753) | Feb 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [73738d3f0c](https://linux-hardware.org/?probe=73738d3f0c) | Feb 08, 2022 |
| Quanta        | TW8/SW8/DW8                 | [a542c42556](https://linux-hardware.org/?probe=a542c42556) | Feb 08, 2022 |
| Dell          | Latitude E5410              | [fd73c50faa](https://linux-hardware.org/?probe=fd73c50faa) | Feb 07, 2022 |
| Acer          | Aspire A515-52G             | [cfc69482e3](https://linux-hardware.org/?probe=cfc69482e3) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [99770a5e77](https://linux-hardware.org/?probe=99770a5e77) | Feb 06, 2022 |
| Packard Be... | EasyNote TV44HC             | [60aaa89bfa](https://linux-hardware.org/?probe=60aaa89bfa) | Feb 03, 2022 |
| Acer          | Aspire V3-772G              | [1e4b8a880e](https://linux-hardware.org/?probe=1e4b8a880e) | Jan 29, 2022 |
| Clevo         | W76x/M77xCUH                | [48d0efb057](https://linux-hardware.org/?probe=48d0efb057) | Jan 26, 2022 |
| AMI           | Cherry Trail Tablet         | [0560bf99e5](https://linux-hardware.org/?probe=0560bf99e5) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [dbeeb0a6f3](https://linux-hardware.org/?probe=dbeeb0a6f3) | Jan 24, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [8ee01c475e](https://linux-hardware.org/?probe=8ee01c475e) | Jan 23, 2022 |
| Packard Be... | EasyNote TV44HC             | [38fb76e085](https://linux-hardware.org/?probe=38fb76e085) | Jan 23, 2022 |
| Apple         | MacBookPro5,3               | [e0b61bcde4](https://linux-hardware.org/?probe=e0b61bcde4) | Jan 22, 2022 |
| Packard Be... | EasyNote TV44HC             | [d2a1835844](https://linux-hardware.org/?probe=d2a1835844) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | [95b7ce0007](https://linux-hardware.org/?probe=95b7ce0007) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| HP            | Pavilion g7                 | [064474c7e0](https://linux-hardware.org/?probe=064474c7e0) | Jan 20, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | [e2161b5856](https://linux-hardware.org/?probe=e2161b5856) | Jan 20, 2022 |
| ASUSTek       | UX330UAK                    | [3749e7dc2e](https://linux-hardware.org/?probe=3749e7dc2e) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [1478a3da5a](https://linux-hardware.org/?probe=1478a3da5a) | Jan 17, 2022 |
| Notebook      | PCx0Dx                      | [1c35674fd1](https://linux-hardware.org/?probe=1c35674fd1) | Jan 17, 2022 |
| Acer          | Aspire E5-511               | [c2691bf00b](https://linux-hardware.org/?probe=c2691bf00b) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [80a80d7619](https://linux-hardware.org/?probe=80a80d7619) | Jan 16, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| Acer          | Aspire V3-772G              | [c6dc2d8971](https://linux-hardware.org/?probe=c6dc2d8971) | Jan 14, 2022 |
| Dell          | XPS 15 9510                 | [642e01d970](https://linux-hardware.org/?probe=642e01d970) | Jan 13, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [06f3fa0e22](https://linux-hardware.org/?probe=06f3fa0e22) | Jan 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [ec88cd8e93](https://linux-hardware.org/?probe=ec88cd8e93) | Jan 12, 2022 |
| Acer          | Aspire V3-772G              | [aaf1227ec4](https://linux-hardware.org/?probe=aaf1227ec4) | Jan 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [7ce7a30da1](https://linux-hardware.org/?probe=7ce7a30da1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [ac620bc1b6](https://linux-hardware.org/?probe=ac620bc1b6) | Jan 10, 2022 |
| Acer          | Aspire R7-572G              | [dc4a930b99](https://linux-hardware.org/?probe=dc4a930b99) | Jan 08, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [4d67659f6c](https://linux-hardware.org/?probe=4d67659f6c) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [b3428338c0](https://linux-hardware.org/?probe=b3428338c0) | Jan 07, 2022 |
| ASUSTek       | K53U                        | [62410e0adc](https://linux-hardware.org/?probe=62410e0adc) | Jan 07, 2022 |
| Apple         | MacBookPro14,3              | [96b76bc44b](https://linux-hardware.org/?probe=96b76bc44b) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [0551fb871e](https://linux-hardware.org/?probe=0551fb871e) | Dec 31, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [40eee8c893](https://linux-hardware.org/?probe=40eee8c893) | Dec 30, 2021 |
| Dell          | Latitude E5420              | [a2d1902586](https://linux-hardware.org/?probe=a2d1902586) | Dec 29, 2021 |
| HP            | EliteBook 840 G1            | [ca7f3a7275](https://linux-hardware.org/?probe=ca7f3a7275) | Dec 29, 2021 |
| Acer          | Aspire V3-572               | [57f2afd2a3](https://linux-hardware.org/?probe=57f2afd2a3) | Dec 28, 2021 |
| HP            | Pavilion dv7                | [79cc0303f4](https://linux-hardware.org/?probe=79cc0303f4) | Dec 27, 2021 |
| HP            | Pavilion dv7                | [3ab4ebdbfd](https://linux-hardware.org/?probe=3ab4ebdbfd) | Dec 27, 2021 |
| HP            | Pavilion dv7                | [d9456116de](https://linux-hardware.org/?probe=d9456116de) | Dec 27, 2021 |
| HP            | 300-250                     | [94f3405ce4](https://linux-hardware.org/?probe=94f3405ce4) | Dec 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [cb4cb1ea51](https://linux-hardware.org/?probe=cb4cb1ea51) | Dec 26, 2021 |
| Lenovo        | B50-10 80QR                 | [0195687c06](https://linux-hardware.org/?probe=0195687c06) | Dec 26, 2021 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [7ebdb585ab](https://linux-hardware.org/?probe=7ebdb585ab) | Dec 26, 2021 |
| Acer          | Aspire ES1-571              | [4973bd9cc7](https://linux-hardware.org/?probe=4973bd9cc7) | Dec 25, 2021 |
| Sony          | VPCEB1M1E                   | [1e9385a74f](https://linux-hardware.org/?probe=1e9385a74f) | Dec 25, 2021 |
| HP            | ProBook 4740s               | [149c7edca2](https://linux-hardware.org/?probe=149c7edca2) | Dec 23, 2021 |
| Acer          | Aspire A315-31              | [a55ed0d992](https://linux-hardware.org/?probe=a55ed0d992) | Dec 20, 2021 |
| HP            | Pavilion dv7                | [e1ac371752](https://linux-hardware.org/?probe=e1ac371752) | Dec 18, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [6e8ba23594](https://linux-hardware.org/?probe=6e8ba23594) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [70a9d341b1](https://linux-hardware.org/?probe=70a9d341b1) | Dec 16, 2021 |
| Dell          | Latitude E5410              | [433ad50dd3](https://linux-hardware.org/?probe=433ad50dd3) | Dec 16, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [d103baf427](https://linux-hardware.org/?probe=d103baf427) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX481FLY_UX481FL    | [d680085d25](https://linux-hardware.org/?probe=d680085d25) | Dec 15, 2021 |
| Dell          | Inspiron 16 7610            | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Apple         | MacBookAir3,1               | [edebb4d39b](https://linux-hardware.org/?probe=edebb4d39b) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| ASUSTek       | N551JW                      | [95f2828cd6](https://linux-hardware.org/?probe=95f2828cd6) | Dec 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1dba035790](https://linux-hardware.org/?probe=1dba035790) | Dec 07, 2021 |
| Acer          | Aspire E5-511               | [9e8fd519f0](https://linux-hardware.org/?probe=9e8fd519f0) | Dec 07, 2021 |
| HP            | ENVY dv7                    | [1ab140a424](https://linux-hardware.org/?probe=1ab140a424) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [d78c027940](https://linux-hardware.org/?probe=d78c027940) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [26964d4c51](https://linux-hardware.org/?probe=26964d4c51) | Dec 04, 2021 |
| Razer         | Blade Stealth               | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| HP            | ProBook 450 G4              | [0cc317d213](https://linux-hardware.org/?probe=0cc317d213) | Dec 04, 2021 |
| Lenovo        | G50-70 20351                | [6de772fed7](https://linux-hardware.org/?probe=6de772fed7) | Nov 27, 2021 |
| MSI           | MS-17G                      | [0fd0763f15](https://linux-hardware.org/?probe=0fd0763f15) | Nov 26, 2021 |
| MSI           | MS-17G                      | [00c3cd9a83](https://linux-hardware.org/?probe=00c3cd9a83) | Nov 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [fbec23b579](https://linux-hardware.org/?probe=fbec23b579) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| Toshiba       | Satellite C660              | [ab7e1ab2f6](https://linux-hardware.org/?probe=ab7e1ab2f6) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | [bf8a290d91](https://linux-hardware.org/?probe=bf8a290d91) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | [3b2959cf2d](https://linux-hardware.org/?probe=3b2959cf2d) | Nov 23, 2021 |
| HP            | Notebook                    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| Lenovo        | ThinkPad X250 20CM004UGE    | [26bd0cd883](https://linux-hardware.org/?probe=26bd0cd883) | Nov 22, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [80d0bc77b6](https://linux-hardware.org/?probe=80d0bc77b6) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| Google        | Lars                        | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [2067df0e1e](https://linux-hardware.org/?probe=2067df0e1e) | Nov 16, 2021 |
| Acer          | Aspire V3-772G              | [1e66881588](https://linux-hardware.org/?probe=1e66881588) | Nov 16, 2021 |
| HP            | ZBook 15 G2                 | [f40c4458aa](https://linux-hardware.org/?probe=f40c4458aa) | Nov 16, 2021 |
| Dell          | Latitude E7240              | [aaf6395a70](https://linux-hardware.org/?probe=aaf6395a70) | Nov 14, 2021 |
| Dell          | Latitude E7270              | [b462d15a6b](https://linux-hardware.org/?probe=b462d15a6b) | Nov 14, 2021 |
| HP            | EliteBook 735 G5            | [79600db29f](https://linux-hardware.org/?probe=79600db29f) | Nov 14, 2021 |
| HP            | Pavilion 15                 | [366558c9a6](https://linux-hardware.org/?probe=366558c9a6) | Nov 11, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [f9f140b132](https://linux-hardware.org/?probe=f9f140b132) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3876a60641](https://linux-hardware.org/?probe=3876a60641) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [92b50813ac](https://linux-hardware.org/?probe=92b50813ac) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [258574fc87](https://linux-hardware.org/?probe=258574fc87) | Nov 10, 2021 |
| ASUSTek       | UX430UNR                    | [292992ce5a](https://linux-hardware.org/?probe=292992ce5a) | Nov 07, 2021 |
| Dell          | XPS 15 9510                 | [6f9b7bffd1](https://linux-hardware.org/?probe=6f9b7bffd1) | Nov 06, 2021 |
| Acer          | V3-771                      | [bf99ad481c](https://linux-hardware.org/?probe=bf99ad481c) | Nov 04, 2021 |
| ASUSTek       | U36SD                       | [84e47bb477](https://linux-hardware.org/?probe=84e47bb477) | Nov 03, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | [8686d92d45](https://linux-hardware.org/?probe=8686d92d45) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [3f7a2585fe](https://linux-hardware.org/?probe=3f7a2585fe) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [e6958a71d6](https://linux-hardware.org/?probe=e6958a71d6) | Oct 31, 2021 |
| Acer          | TravelMate P459-G2-MG       | [05087f89c1](https://linux-hardware.org/?probe=05087f89c1) | Oct 30, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| Acer          | TravelMate P459-G2-MG       | [4a80b949aa](https://linux-hardware.org/?probe=4a80b949aa) | Oct 30, 2021 |
| HP            | EliteBook 840 G6            | [d0307fd66e](https://linux-hardware.org/?probe=d0307fd66e) | Oct 29, 2021 |
| HP            | EliteBook 840 G6            | [a5abf5d5ee](https://linux-hardware.org/?probe=a5abf5d5ee) | Oct 29, 2021 |
| Medion        | S3409 MD60234               | [4bb4415dae](https://linux-hardware.org/?probe=4bb4415dae) | Oct 27, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B80... | [a567978a3c](https://linux-hardware.org/?probe=a567978a3c) | Oct 26, 2021 |
| Acer          | V3-771                      | [b953b67d06](https://linux-hardware.org/?probe=b953b67d06) | Oct 25, 2021 |
| TUXEDO        | BC1510 1710                 | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| Packard Be... | EasyNote TV44HC             | [5ebedd4a1c](https://linux-hardware.org/?probe=5ebedd4a1c) | Oct 23, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [3517455df5](https://linux-hardware.org/?probe=3517455df5) | Oct 22, 2021 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b198944ad7](https://linux-hardware.org/?probe=b198944ad7) | Oct 22, 2021 |
| Acer          | Swift SF314-43              | [ef2da9ecca](https://linux-hardware.org/?probe=ef2da9ecca) | Oct 21, 2021 |
| Medion        | E6226                       | [ebc0f3d72b](https://linux-hardware.org/?probe=ebc0f3d72b) | Oct 20, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4f400bb9ab](https://linux-hardware.org/?probe=4f400bb9ab) | Oct 20, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4d7535970d](https://linux-hardware.org/?probe=4d7535970d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [d8302cc197](https://linux-hardware.org/?probe=d8302cc197) | Oct 19, 2021 |
| Acer          | Aspire 1410                 | [dc42de3c30](https://linux-hardware.org/?probe=dc42de3c30) | Oct 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [dda062734d](https://linux-hardware.org/?probe=dda062734d) | Oct 17, 2021 |
| Dell          | XPS 15 7590                 | [ff55772306](https://linux-hardware.org/?probe=ff55772306) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Dell          | Latitude 5410               | [bdd46a0cd7](https://linux-hardware.org/?probe=bdd46a0cd7) | Oct 14, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [62872f38de](https://linux-hardware.org/?probe=62872f38de) | Oct 14, 2021 |
| Acer          | Swift SF515-51T             | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [b72f6d9f64](https://linux-hardware.org/?probe=b72f6d9f64) | Oct 08, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [770a47642f](https://linux-hardware.org/?probe=770a47642f) | Oct 03, 2021 |
| Acer          | Aspire A515-52              | [1f5c815672](https://linux-hardware.org/?probe=1f5c815672) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [feed153041](https://linux-hardware.org/?probe=feed153041) | Sep 28, 2021 |
| Acer          | Aspire 1410                 | [8db88d13ec](https://linux-hardware.org/?probe=8db88d13ec) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Dell          | XPS 15 9560                 | [cc4ac84959](https://linux-hardware.org/?probe=cc4ac84959) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [2c7e4f944f](https://linux-hardware.org/?probe=2c7e4f944f) | Sep 18, 2021 |
| Acer          | Swift SF515-51T             | [a0a6460520](https://linux-hardware.org/?probe=a0a6460520) | Sep 17, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ab2e5dcff2](https://linux-hardware.org/?probe=ab2e5dcff2) | Sep 14, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f01a6435b7](https://linux-hardware.org/?probe=f01a6435b7) | Sep 14, 2021 |
| Lenovo        | ThinkPad T550 20CJS03300    | [2b53cd0d2d](https://linux-hardware.org/?probe=2b53cd0d2d) | Sep 11, 2021 |
| Lenovo        | ThinkPad W540 20BHS27X02    | [60ee8c9731](https://linux-hardware.org/?probe=60ee8c9731) | Sep 10, 2021 |
| Lenovo        | ThinkPad W540 20BHS27X02    | [c11d22f126](https://linux-hardware.org/?probe=c11d22f126) | Sep 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3333d2aabd](https://linux-hardware.org/?probe=3333d2aabd) | Sep 09, 2021 |
| Lenovo        | ThinkPad L460 20FVS01500    | [065324adcb](https://linux-hardware.org/?probe=065324adcb) | Sep 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Medion        | S3409 MD60234               | [30a93543cd](https://linux-hardware.org/?probe=30a93543cd) | Sep 07, 2021 |
| Medion        | S3409 MD60234               | [274fe63960](https://linux-hardware.org/?probe=274fe63960) | Sep 06, 2021 |
| Acer          | Swift SF114-32              | [41a2fef2aa](https://linux-hardware.org/?probe=41a2fef2aa) | Sep 05, 2021 |
| HP            | Laptop 15-bw0xx             | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| Packard Be... | EasyNote TV44HC             | [87353376d7](https://linux-hardware.org/?probe=87353376d7) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [4fc1ff5f76](https://linux-hardware.org/?probe=4fc1ff5f76) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [2087b72fe1](https://linux-hardware.org/?probe=2087b72fe1) | Aug 31, 2021 |
| Packard Be... | EasyNote TV44HC             | [4d4510dbfb](https://linux-hardware.org/?probe=4d4510dbfb) | Aug 30, 2021 |
| Lenovo        | ThinkPad T420 4236NGG       | [6f82a1cdeb](https://linux-hardware.org/?probe=6f82a1cdeb) | Aug 30, 2021 |
| Samsung       | 700G7C                      | [9bdbd478e5](https://linux-hardware.org/?probe=9bdbd478e5) | Aug 29, 2021 |
| TUXEDO        | BC1510 1710                 | [9061a72f3a](https://linux-hardware.org/?probe=9061a72f3a) | Aug 29, 2021 |
| Acer          | Aspire ES1-512              | [666660f555](https://linux-hardware.org/?probe=666660f555) | Aug 29, 2021 |
| Dell          | Precision M6700             | [c1e66e1633](https://linux-hardware.org/?probe=c1e66e1633) | Aug 28, 2021 |
| TrekStor      | Surfbook E11B               | [9014dfda1f](https://linux-hardware.org/?probe=9014dfda1f) | Aug 26, 2021 |
| Dell          | Precision 5520              | [12782a8da6](https://linux-hardware.org/?probe=12782a8da6) | Aug 24, 2021 |
| ASUSTek       | ZenBook UX431DA             | [76b34b8383](https://linux-hardware.org/?probe=76b34b8383) | Aug 24, 2021 |
| ASUSTek       | ZenBook UX431DA             | [35b4ea3ba9](https://linux-hardware.org/?probe=35b4ea3ba9) | Aug 24, 2021 |
| Dell          | Precision 5520              | [43f1c9c69c](https://linux-hardware.org/?probe=43f1c9c69c) | Aug 24, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3598b4e555](https://linux-hardware.org/?probe=3598b4e555) | Aug 23, 2021 |
| Dell          | Latitude E5550              | [186ab38330](https://linux-hardware.org/?probe=186ab38330) | Aug 23, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [e59555689c](https://linux-hardware.org/?probe=e59555689c) | Aug 23, 2021 |
| HP            | EliteBook Folio 9470m       | [ddd4cdd7ca](https://linux-hardware.org/?probe=ddd4cdd7ca) | Aug 22, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [47cea1b5c7](https://linux-hardware.org/?probe=47cea1b5c7) | Aug 20, 2021 |
| Dell          | Precision 5520              | [bb6728e105](https://linux-hardware.org/?probe=bb6728e105) | Aug 19, 2021 |
| Dell          | Precision 5520              | [87389dc90a](https://linux-hardware.org/?probe=87389dc90a) | Aug 19, 2021 |
| Acer          | V3-771                      | [5235c8cb39](https://linux-hardware.org/?probe=5235c8cb39) | Aug 18, 2021 |
| Acer          | Aspire 5253                 | [8d12d69ada](https://linux-hardware.org/?probe=8d12d69ada) | Aug 18, 2021 |
| Toshiba       | Satellite C660D             | [eb50acee36](https://linux-hardware.org/?probe=eb50acee36) | Aug 16, 2021 |
| Toshiba       | Satellite C660D             | [2afd21c6f7](https://linux-hardware.org/?probe=2afd21c6f7) | Aug 16, 2021 |
| Acer          | Aspire 5253                 | [06a6ece9cb](https://linux-hardware.org/?probe=06a6ece9cb) | Aug 16, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | [d628c6c320](https://linux-hardware.org/?probe=d628c6c320) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| HP            | ProBook 650 G2              | [8bd4184e25](https://linux-hardware.org/?probe=8bd4184e25) | Aug 15, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | [4b51090679](https://linux-hardware.org/?probe=4b51090679) | Aug 13, 2021 |
| Dell          | Latitude 7490               | [f78358fed7](https://linux-hardware.org/?probe=f78358fed7) | Aug 13, 2021 |
| Dell          | Latitude 7490               | [3c3c535058](https://linux-hardware.org/?probe=3c3c535058) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [4dc4a0efe0](https://linux-hardware.org/?probe=4dc4a0efe0) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6e44d2998d](https://linux-hardware.org/?probe=6e44d2998d) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | [9fef85ae5d](https://linux-hardware.org/?probe=9fef85ae5d) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| ASUSTek       | GL702ZC                     | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| Dell          | Latitude E7440              | [33a205253e](https://linux-hardware.org/?probe=33a205253e) | Aug 10, 2021 |
| HP            | ENVY dv7                    | [888257031e](https://linux-hardware.org/?probe=888257031e) | Aug 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [92fb2e26c0](https://linux-hardware.org/?probe=92fb2e26c0) | Aug 10, 2021 |
| Dell          | Latitude E7440              | [89a521499a](https://linux-hardware.org/?probe=89a521499a) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [05628cae80](https://linux-hardware.org/?probe=05628cae80) | Aug 09, 2021 |
| Lenovo        | ThinkPad W500 406152G       | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| GPD           | P2 MAX                      | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| TUXEDO        | Unknown                     | [15b26f4936](https://linux-hardware.org/?probe=15b26f4936) | Aug 07, 2021 |
| Acer          | Aspire E5-571G              | [ed862d4cb6](https://linux-hardware.org/?probe=ed862d4cb6) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Lenovo        | ThinkPad T510 43494JG       | [80fafef64f](https://linux-hardware.org/?probe=80fafef64f) | Aug 05, 2021 |
| Dell          | Inspiron 15-5578            | [1169a22f51](https://linux-hardware.org/?probe=1169a22f51) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [0724f0e60d](https://linux-hardware.org/?probe=0724f0e60d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T420 4236NGG       | [5b70933531](https://linux-hardware.org/?probe=5b70933531) | Aug 01, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [e2db581d0b](https://linux-hardware.org/?probe=e2db581d0b) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [b893ad294a](https://linux-hardware.org/?probe=b893ad294a) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [730d886e60](https://linux-hardware.org/?probe=730d886e60) | Jul 31, 2021 |
| HP            | Pavilion dv7                | [e9254ad52f](https://linux-hardware.org/?probe=e9254ad52f) | Jul 31, 2021 |
| Acer          | Aspire E1-572G              | [3963220295](https://linux-hardware.org/?probe=3963220295) | Jul 31, 2021 |
| Acer          | Aspire E1-572G              | [f8eb40a0a3](https://linux-hardware.org/?probe=f8eb40a0a3) | Jul 30, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | [9cf9065745](https://linux-hardware.org/?probe=9cf9065745) | Jul 30, 2021 |
| Dell          | Latitude E5550              | [84d60c9f30](https://linux-hardware.org/?probe=84d60c9f30) | Jul 30, 2021 |
| Dell          | XPS 13 9310                 | [4ad09b336f](https://linux-hardware.org/?probe=4ad09b336f) | Jul 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [423bc2b7a1](https://linux-hardware.org/?probe=423bc2b7a1) | Jul 28, 2021 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [cde8deea7e](https://linux-hardware.org/?probe=cde8deea7e) | Jul 26, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [7330b29e94](https://linux-hardware.org/?probe=7330b29e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [1a104c4440](https://linux-hardware.org/?probe=1a104c4440) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| GPD           | P2 MAX                      | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| Lenovo        | G580 20150                  | [a52bc56d5e](https://linux-hardware.org/?probe=a52bc56d5e) | Jul 23, 2021 |
| Medion        | E6226                       | [aee8a0be6f](https://linux-hardware.org/?probe=aee8a0be6f) | Jul 22, 2021 |
| HP            | Pavilion g7                 | [59f46869ee](https://linux-hardware.org/?probe=59f46869ee) | Jul 21, 2021 |
| HP            | Pavilion g7                 | [b71a21e87a](https://linux-hardware.org/?probe=b71a21e87a) | Jul 21, 2021 |
| HP            | ProBook 450 G3              | [8b355a2630](https://linux-hardware.org/?probe=8b355a2630) | Jul 20, 2021 |
| Medion        | P6618                       | [d8b3d2db11](https://linux-hardware.org/?probe=d8b3d2db11) | Jul 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [5c3f0aef89](https://linux-hardware.org/?probe=5c3f0aef89) | Jul 17, 2021 |
| Sony          | SVE14A2V1EW                 | [2b1ce53eca](https://linux-hardware.org/?probe=2b1ce53eca) | Jul 16, 2021 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [c61db52d00](https://linux-hardware.org/?probe=c61db52d00) | Jul 16, 2021 |
| Dell          | XPS 13 9360                 | [90fcb82f7e](https://linux-hardware.org/?probe=90fcb82f7e) | Jul 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [427828621f](https://linux-hardware.org/?probe=427828621f) | Jul 12, 2021 |
| Acer          | Swift SF114-33              | [7aa338a8dc](https://linux-hardware.org/?probe=7aa338a8dc) | Jul 12, 2021 |
| Toshiba       | NB550D                      | [6e4b998cc0](https://linux-hardware.org/?probe=6e4b998cc0) | Jul 12, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [04163e3fa8](https://linux-hardware.org/?probe=04163e3fa8) | Jul 12, 2021 |
| Notebook      | NS50MU                      | [6841e398e3](https://linux-hardware.org/?probe=6841e398e3) | Jul 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS3... | [6c9599ccf7](https://linux-hardware.org/?probe=6c9599ccf7) | Jul 07, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [8887f14351](https://linux-hardware.org/?probe=8887f14351) | Jul 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [70c0bc44a2](https://linux-hardware.org/?probe=70c0bc44a2) | Jul 05, 2021 |
| Lenovo        | ThinkPad E570 20H5006VMZ    | [7bbd48efde](https://linux-hardware.org/?probe=7bbd48efde) | Jul 03, 2021 |
| Lenovo        | ThinkPad T450s 20BX004KM... | [dbd8629d3c](https://linux-hardware.org/?probe=dbd8629d3c) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | [78ad5dbea0](https://linux-hardware.org/?probe=78ad5dbea0) | Jul 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [6fde0ddd03](https://linux-hardware.org/?probe=6fde0ddd03) | Jul 01, 2021 |
| HP            | Laptop 15-bs0xx             | [934190169c](https://linux-hardware.org/?probe=934190169c) | Jun 30, 2021 |
| Lenovo        | ThinkPad E570 20H5006VMZ    | [05a46ada33](https://linux-hardware.org/?probe=05a46ada33) | Jun 25, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [ea4ab7e535](https://linux-hardware.org/?probe=ea4ab7e535) | Jun 22, 2021 |
| HP            | ProBook 470 G5              | [94fbab0837](https://linux-hardware.org/?probe=94fbab0837) | Jun 19, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [822acd5e9b](https://linux-hardware.org/?probe=822acd5e9b) | Jun 19, 2021 |
| HUAWEI        | MACH-WX9                    | [4c0b858cde](https://linux-hardware.org/?probe=4c0b858cde) | Jun 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [32c83da9dd](https://linux-hardware.org/?probe=32c83da9dd) | Jun 19, 2021 |
| Apple         | MacBookPro14,1              | [a69ed7dfd9](https://linux-hardware.org/?probe=a69ed7dfd9) | Jun 18, 2021 |
| HP            | EliteBook Folio 9470m       | [33fce68a70](https://linux-hardware.org/?probe=33fce68a70) | Jun 18, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [790371eae7](https://linux-hardware.org/?probe=790371eae7) | Jun 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [96ee62e1dc](https://linux-hardware.org/?probe=96ee62e1dc) | Jun 15, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [f0a5e0cbb6](https://linux-hardware.org/?probe=f0a5e0cbb6) | Jun 13, 2021 |
| Dell          | Latitude E6510              | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| Acer          | Aspire E5-571G              | [455a20d0a7](https://linux-hardware.org/?probe=455a20d0a7) | Jun 10, 2021 |
| Acer          | Aspire E5-571G              | [467c46c227](https://linux-hardware.org/?probe=467c46c227) | Jun 08, 2021 |
| Dell          | XPS 13 9310                 | [5456739d8f](https://linux-hardware.org/?probe=5456739d8f) | Jun 08, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [0a5cb29f98](https://linux-hardware.org/?probe=0a5cb29f98) | Jun 07, 2021 |
| HP            | ProBook 4510s (NX684EA)     | [55591c1e24](https://linux-hardware.org/?probe=55591c1e24) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [29f66db2d1](https://linux-hardware.org/?probe=29f66db2d1) | Jun 07, 2021 |
| Dell          | Inspiron 5577               | [188fcc64df](https://linux-hardware.org/?probe=188fcc64df) | Jun 06, 2021 |
| Dell          | XPS 15 7590                 | [08b1e4c99f](https://linux-hardware.org/?probe=08b1e4c99f) | Jun 05, 2021 |
| Acer          | Aspire 1410                 | [c0022674fa](https://linux-hardware.org/?probe=c0022674fa) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| Dell          | Latitude E7440              | [32b9a694b3](https://linux-hardware.org/?probe=32b9a694b3) | Jun 04, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| HP            | ProBook 440 G8 Notebook ... | [c1ec69ad60](https://linux-hardware.org/?probe=c1ec69ad60) | Jun 02, 2021 |
| HP            | 355 G2                      | [c80a118e90](https://linux-hardware.org/?probe=c80a118e90) | May 29, 2021 |
| Acer          | Aspire 7736                 | [f8cf9b2aa2](https://linux-hardware.org/?probe=f8cf9b2aa2) | May 29, 2021 |
| HP            | ENVY 17                     | [bdaee2e27b](https://linux-hardware.org/?probe=bdaee2e27b) | May 28, 2021 |
| Acer          | Aspire F5-573G              | [d0c45f9b31](https://linux-hardware.org/?probe=d0c45f9b31) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [049671564e](https://linux-hardware.org/?probe=049671564e) | May 27, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [cb5051e015](https://linux-hardware.org/?probe=cb5051e015) | May 27, 2021 |
| HP            | Unknown                     | [42eeaf84d9](https://linux-hardware.org/?probe=42eeaf84d9) | May 24, 2021 |
| Acer          | TravelMate P215-53          | [dc89b4797f](https://linux-hardware.org/?probe=dc89b4797f) | May 24, 2021 |
| Acer          | TravelMate P215-53          | [18ea2a888a](https://linux-hardware.org/?probe=18ea2a888a) | May 23, 2021 |
| Notebook      | NH5x_7xDPx                  | [4a9dd7d6a1](https://linux-hardware.org/?probe=4a9dd7d6a1) | May 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [901f37d11b](https://linux-hardware.org/?probe=901f37d11b) | May 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [39f2002b6b](https://linux-hardware.org/?probe=39f2002b6b) | May 19, 2021 |
| Acer          | Aspire 1410                 | [877462fbca](https://linux-hardware.org/?probe=877462fbca) | May 18, 2021 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [abdc61ad94](https://linux-hardware.org/?probe=abdc61ad94) | May 18, 2021 |
| HP            | Compaq CQ58                 | [710fdca60a](https://linux-hardware.org/?probe=710fdca60a) | May 16, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| HP            | ProBook 455 G4              | [aca836bae8](https://linux-hardware.org/?probe=aca836bae8) | May 14, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [674a800477](https://linux-hardware.org/?probe=674a800477) | May 14, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [42a1bf7901](https://linux-hardware.org/?probe=42a1bf7901) | May 14, 2021 |
| HP            | Pavilion 15                 | [7e38915bdc](https://linux-hardware.org/?probe=7e38915bdc) | May 13, 2021 |
| HP            | OMEN by Laptop              | [43907153c2](https://linux-hardware.org/?probe=43907153c2) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [36ade7dd15](https://linux-hardware.org/?probe=36ade7dd15) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [06c1bbc65e](https://linux-hardware.org/?probe=06c1bbc65e) | May 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [b313183fd5](https://linux-hardware.org/?probe=b313183fd5) | May 11, 2021 |
| Acer          | Swift SF114-33              | [e2d8f58e1e](https://linux-hardware.org/?probe=e2d8f58e1e) | May 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [e126e1aa0c](https://linux-hardware.org/?probe=e126e1aa0c) | May 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [952093c613](https://linux-hardware.org/?probe=952093c613) | May 09, 2021 |
| Acer          | Swift SF114-33              | [a6ed80ed47](https://linux-hardware.org/?probe=a6ed80ed47) | May 08, 2021 |
| Google        | Lars                        | [2cba94fe45](https://linux-hardware.org/?probe=2cba94fe45) | May 08, 2021 |
| HP            | Compaq nc4400 (EN004AV)     | [eedf4bb0ca](https://linux-hardware.org/?probe=eedf4bb0ca) | May 08, 2021 |
| Acer          | Swift SF314-42              | [f28c9e243e](https://linux-hardware.org/?probe=f28c9e243e) | May 07, 2021 |
| HP            | Compaq nc4400 (EN004AV)     | [d6154d7955](https://linux-hardware.org/?probe=d6154d7955) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [06d44f569d](https://linux-hardware.org/?probe=06d44f569d) | May 06, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LM... | [0b155bcbcd](https://linux-hardware.org/?probe=0b155bcbcd) | May 04, 2021 |
| HP            | Notebook                    | [4e09e8ff3b](https://linux-hardware.org/?probe=4e09e8ff3b) | May 03, 2021 |
| HP            | 2133                        | [e81cac058d](https://linux-hardware.org/?probe=e81cac058d) | May 03, 2021 |
| Alienware     | m15 R2                      | [4884d06d2e](https://linux-hardware.org/?probe=4884d06d2e) | May 02, 2021 |
| HP            | EliteBook Folio 1040 G1     | [226f359e79](https://linux-hardware.org/?probe=226f359e79) | May 01, 2021 |
| HP            | 250 G7 Notebook PC          | [e69f0b2a6e](https://linux-hardware.org/?probe=e69f0b2a6e) | May 01, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ08    | [7efd61973c](https://linux-hardware.org/?probe=7efd61973c) | Apr 30, 2021 |
| Lenovo        | Z50-70 20354                | [93033f85c6](https://linux-hardware.org/?probe=93033f85c6) | Apr 29, 2021 |
| HP            | 2133                        | [fd8d7a6a94](https://linux-hardware.org/?probe=fd8d7a6a94) | Apr 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| Alienware     | m15 R2                      | [77d90d2a91](https://linux-hardware.org/?probe=77d90d2a91) | Apr 27, 2021 |
| Apple         | MacBookPro8,1               | [909c049308](https://linux-hardware.org/?probe=909c049308) | Apr 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6fd9f38406](https://linux-hardware.org/?probe=6fd9f38406) | Apr 26, 2021 |
| Dell          | Latitude E7440              | [b8c6136bd0](https://linux-hardware.org/?probe=b8c6136bd0) | Apr 26, 2021 |
| HP            | EliteBook 2170p             | [98a664ebcc](https://linux-hardware.org/?probe=98a664ebcc) | Apr 26, 2021 |
| ASUSTek       | K72Jr                       | [ff3ba69d3e](https://linux-hardware.org/?probe=ff3ba69d3e) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [e4b338aa1a](https://linux-hardware.org/?probe=e4b338aa1a) | Apr 25, 2021 |
| OriginPC      | ND-17                       | [8ff850fe97](https://linux-hardware.org/?probe=8ff850fe97) | Apr 25, 2021 |
| ASUSTek       | K72Jr                       | [bcc4e8b350](https://linux-hardware.org/?probe=bcc4e8b350) | Apr 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [b6b305b0bd](https://linux-hardware.org/?probe=b6b305b0bd) | Apr 24, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [101cc9e3ae](https://linux-hardware.org/?probe=101cc9e3ae) | Apr 23, 2021 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [41ade399b3](https://linux-hardware.org/?probe=41ade399b3) | Apr 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [926fa9f69a](https://linux-hardware.org/?probe=926fa9f69a) | Apr 21, 2021 |
| HP            | ENVY Laptop 17-cg1xxx       | [38221d2991](https://linux-hardware.org/?probe=38221d2991) | Apr 21, 2021 |
| Acer          | Aspire 1410                 | [7288f31e3c](https://linux-hardware.org/?probe=7288f31e3c) | Apr 20, 2021 |
| Lenovo        | Z50-70 20354                | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5b66c48c4a](https://linux-hardware.org/?probe=5b66c48c4a) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| Dell          | Latitude E7240              | [45870a7f89](https://linux-hardware.org/?probe=45870a7f89) | Apr 14, 2021 |
| whyopencom... | Unknown                     | [aad3ad526f](https://linux-hardware.org/?probe=aad3ad526f) | Apr 13, 2021 |
| HP            | 250 G6 Notebook PC          | [bc738ac65f](https://linux-hardware.org/?probe=bc738ac65f) | Apr 11, 2021 |
| Dell          | XPS 13 9343                 | [4d759a05db](https://linux-hardware.org/?probe=4d759a05db) | Apr 09, 2021 |
| Dell          | Latitude E6500              | [3bdee6855c](https://linux-hardware.org/?probe=3bdee6855c) | Apr 07, 2021 |
| Lenovo        | IdeaPad Yoga 13 2191        | [44aa3ba48f](https://linux-hardware.org/?probe=44aa3ba48f) | Apr 05, 2021 |
| Dell          | XPS 15 9570                 | [f74fdee693](https://linux-hardware.org/?probe=f74fdee693) | Apr 01, 2021 |
| TrekStor      | Surfbook E11B               | [464dce7796](https://linux-hardware.org/?probe=464dce7796) | Apr 01, 2021 |
| Dell          | Latitude E5450              | [5ce2bad1c1](https://linux-hardware.org/?probe=5ce2bad1c1) | Mar 29, 2021 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [449ee0c3ef](https://linux-hardware.org/?probe=449ee0c3ef) | Mar 28, 2021 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [44e41b06e8](https://linux-hardware.org/?probe=44e41b06e8) | Mar 28, 2021 |
| Medion        | S3409 MD60234               | [eee4e7256b](https://linux-hardware.org/?probe=eee4e7256b) | Mar 26, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [7e10f0b649](https://linux-hardware.org/?probe=7e10f0b649) | Mar 25, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [27a3733dc4](https://linux-hardware.org/?probe=27a3733dc4) | Mar 25, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [f00d8623c8](https://linux-hardware.org/?probe=f00d8623c8) | Mar 24, 2021 |
| Lenovo        | ThinkPad T460s 20F9005CS... | [c03bed695b](https://linux-hardware.org/?probe=c03bed695b) | Mar 24, 2021 |
| HP            | 250 G8 Notebook PC          | [8889dc5ad5](https://linux-hardware.org/?probe=8889dc5ad5) | Mar 22, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | [045f977209](https://linux-hardware.org/?probe=045f977209) | Mar 22, 2021 |
| Acer          | V3-771                      | [a602c93819](https://linux-hardware.org/?probe=a602c93819) | Mar 21, 2021 |
| Apple         | MacBookAir5,2               | [23d38894c7](https://linux-hardware.org/?probe=23d38894c7) | Mar 20, 2021 |
| Dell          | Inspiron 7577               | [25f556cacf](https://linux-hardware.org/?probe=25f556cacf) | Mar 18, 2021 |
| HP            | EliteBook 2760p             | [49ee1765af](https://linux-hardware.org/?probe=49ee1765af) | Mar 16, 2021 |
| HP            | EliteBook 2760p             | [20bf0cfe70](https://linux-hardware.org/?probe=20bf0cfe70) | Mar 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1deb9edb46](https://linux-hardware.org/?probe=1deb9edb46) | Mar 14, 2021 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [6c33ce2e79](https://linux-hardware.org/?probe=6c33ce2e79) | Mar 14, 2021 |
| ASUSTek       | GL702ZC                     | [1d220bf375](https://linux-hardware.org/?probe=1d220bf375) | Mar 14, 2021 |
| HP            | Laptop 15-bs1xx             | [bd1886f540](https://linux-hardware.org/?probe=bd1886f540) | Mar 14, 2021 |
| Acer          | Aspire E1-731               | [23ea26d43f](https://linux-hardware.org/?probe=23ea26d43f) | Mar 12, 2021 |
| Acer          | Aspire 7736                 | [f3777d97b2](https://linux-hardware.org/?probe=f3777d97b2) | Mar 11, 2021 |
| Medion        | E6226                       | [fd72b6bbc9](https://linux-hardware.org/?probe=fd72b6bbc9) | Mar 11, 2021 |
| Dell          | Latitude E7440              | [4521f4c1a3](https://linux-hardware.org/?probe=4521f4c1a3) | Mar 10, 2021 |
| HP            | ProBook 4720s               | [1dbaa2aa4b](https://linux-hardware.org/?probe=1dbaa2aa4b) | Mar 10, 2021 |
| GPD           | P2 MAX                      | [931b98f992](https://linux-hardware.org/?probe=931b98f992) | Mar 09, 2021 |
| Acer          | Nitro AN515-52              | [332460236a](https://linux-hardware.org/?probe=332460236a) | Mar 09, 2021 |
| Lenovo        | G50-80 80E5                 | [7d142fb2ab](https://linux-hardware.org/?probe=7d142fb2ab) | Mar 09, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [09ff2814ff](https://linux-hardware.org/?probe=09ff2814ff) | Mar 08, 2021 |
| Fujitsu       | LIFEBOOK E782               | [b926f7249f](https://linux-hardware.org/?probe=b926f7249f) | Mar 06, 2021 |
| Acer          | Aspire V3-771               | [6aea799f3a](https://linux-hardware.org/?probe=6aea799f3a) | Mar 06, 2021 |
| Acer          | Aspire V3-771               | [f87b2a351a](https://linux-hardware.org/?probe=f87b2a351a) | Mar 06, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [c1211fb175](https://linux-hardware.org/?probe=c1211fb175) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [025319ae47](https://linux-hardware.org/?probe=025319ae47) | Mar 03, 2021 |
| Lenovo        | ThinkPad W530 2441B32       | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| Acer          | Aspire A315-42              | [44974397a8](https://linux-hardware.org/?probe=44974397a8) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK E782               | [0c2c32289a](https://linux-hardware.org/?probe=0c2c32289a) | Feb 28, 2021 |
| HP            | Pavilion Notebook g6        | [e8fb0d80d6](https://linux-hardware.org/?probe=e8fb0d80d6) | Feb 27, 2021 |
| Medion        | P6624                       | [29fba6cccc](https://linux-hardware.org/?probe=29fba6cccc) | Feb 24, 2021 |
| HP            | Pavilion Notebook g6        | [786a3e39df](https://linux-hardware.org/?probe=786a3e39df) | Feb 21, 2021 |
| Toshiba       | QOSMIO X770                 | [1d2a7b2b7a](https://linux-hardware.org/?probe=1d2a7b2b7a) | Feb 20, 2021 |
| Acer          | V3-771                      | [b6e90947b8](https://linux-hardware.org/?probe=b6e90947b8) | Feb 20, 2021 |
| HP            | Pavilion g7                 | [35f315adb8](https://linux-hardware.org/?probe=35f315adb8) | Feb 19, 2021 |
| HP            | Pavilion g7                 | [93b1476aa8](https://linux-hardware.org/?probe=93b1476aa8) | Feb 19, 2021 |
| HP            | Laptop 15-bs0xx             | [f80d7003a7](https://linux-hardware.org/?probe=f80d7003a7) | Feb 18, 2021 |
| TUXEDO        | N13xWU                      | [905dae2b25](https://linux-hardware.org/?probe=905dae2b25) | Feb 18, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [fd4dd43574](https://linux-hardware.org/?probe=fd4dd43574) | Feb 16, 2021 |
| ASUSTek       | GL702ZC                     | [8730756c6f](https://linux-hardware.org/?probe=8730756c6f) | Feb 16, 2021 |
| Samsung       | 730U3E/740U3E               | [094783ff7a](https://linux-hardware.org/?probe=094783ff7a) | Feb 15, 2021 |
| ASUSTek       | X550ZE                      | [d8957c1789](https://linux-hardware.org/?probe=d8957c1789) | Feb 14, 2021 |
| Acer          | Aspire E5-774G              | [f002df90ed](https://linux-hardware.org/?probe=f002df90ed) | Feb 14, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [6e7025de29](https://linux-hardware.org/?probe=6e7025de29) | Feb 14, 2021 |
| Medion        | S621xT                      | [3b77cd1079](https://linux-hardware.org/?probe=3b77cd1079) | Feb 14, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [d955eb3433](https://linux-hardware.org/?probe=d955eb3433) | Feb 14, 2021 |
| HP            | ENVY 15                     | [ab6ef5e4cf](https://linux-hardware.org/?probe=ab6ef5e4cf) | Feb 12, 2021 |
| Samsung       | 730U3E/740U3E               | [df4eb897c9](https://linux-hardware.org/?probe=df4eb897c9) | Feb 12, 2021 |
| Apple         | MacBookPro10,1              | [0fdb263ea1](https://linux-hardware.org/?probe=0fdb263ea1) | Feb 11, 2021 |
| Acer          | V3-771                      | [525217a48b](https://linux-hardware.org/?probe=525217a48b) | Feb 07, 2021 |
| Dell          | Latitude E5440              | [421629b6e9](https://linux-hardware.org/?probe=421629b6e9) | Feb 07, 2021 |
| Medion        | X782X                       | [384e3543dd](https://linux-hardware.org/?probe=384e3543dd) | Feb 05, 2021 |
| Apple         | MacBookPro9,2               | [c3062ebba4](https://linux-hardware.org/?probe=c3062ebba4) | Feb 04, 2021 |
| Apple         | MacBookPro9,2               | [2203826b83](https://linux-hardware.org/?probe=2203826b83) | Feb 04, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| Sony          | SVE1511F4E                  | [6e713387ef](https://linux-hardware.org/?probe=6e713387ef) | Feb 01, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [669829c000](https://linux-hardware.org/?probe=669829c000) | Jan 31, 2021 |
| HP            | ZBook 17 G2                 | [ccf18d4e4e](https://linux-hardware.org/?probe=ccf18d4e4e) | Jan 31, 2021 |
| MSI           | Prestige 14 A10SC           | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| Hampoo        | Cherry Trail CR             | [ecaf6db2cc](https://linux-hardware.org/?probe=ecaf6db2cc) | Jan 31, 2021 |
| Schenker      | VIA 15 Pro                  | [4f091c50f8](https://linux-hardware.org/?probe=4f091c50f8) | Jan 30, 2021 |
| Acer          | V3-771                      | [84fb01f37b](https://linux-hardware.org/?probe=84fb01f37b) | Jan 30, 2021 |
| HP            | Pavilion zd8000 (PW934EA... | [640a4d1741](https://linux-hardware.org/?probe=640a4d1741) | Jan 29, 2021 |
| Acer          | Aspire 7736                 | [361d552fde](https://linux-hardware.org/?probe=361d552fde) | Jan 28, 2021 |
| Sony          | VGN-AR61ZU                  | [32858b781b](https://linux-hardware.org/?probe=32858b781b) | Jan 25, 2021 |
| Sony          | SVE1511N1ESI                | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Lenovo        | ThinkPad X260 20F6CT01WW    | [6f921d73e3](https://linux-hardware.org/?probe=6f921d73e3) | Jan 20, 2021 |
| Lenovo        | ThinkPad Edge E530 32597... | [bb6fc12e56](https://linux-hardware.org/?probe=bb6fc12e56) | Jan 20, 2021 |
| Dell          | XPS 17 9700                 | [d2bc47e82b](https://linux-hardware.org/?probe=d2bc47e82b) | Jan 20, 2021 |
| Sony          | SVE14A2V1EW                 | [baaf829145](https://linux-hardware.org/?probe=baaf829145) | Jan 20, 2021 |
| Lenovo        | ThinkPad T430 2349G5G       | [f552a37632](https://linux-hardware.org/?probe=f552a37632) | Jan 20, 2021 |
| Dell          | Latitude E5430 non-vPro     | [db6d4d3deb](https://linux-hardware.org/?probe=db6d4d3deb) | Jan 20, 2021 |
| ASUSTek       | K53SD                       | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| ASUSTek       | GL702ZC                     | [ba6a149cba](https://linux-hardware.org/?probe=ba6a149cba) | Jan 17, 2021 |
| Acer          | Nitro AN515-52              | [f5873c65c2](https://linux-hardware.org/?probe=f5873c65c2) | Jan 17, 2021 |
| GPD           | P2 MAX                      | [cdc2c0ab67](https://linux-hardware.org/?probe=cdc2c0ab67) | Jan 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [951df975ad](https://linux-hardware.org/?probe=951df975ad) | Jan 17, 2021 |
| whyopencom... | Unknown                     | [c120bc7ad7](https://linux-hardware.org/?probe=c120bc7ad7) | Jan 17, 2021 |
| ASUSTek       | F5RL                        | [79907a946b](https://linux-hardware.org/?probe=79907a946b) | Jan 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e07ae256e7](https://linux-hardware.org/?probe=e07ae256e7) | Jan 16, 2021 |
| Notebook      | W65_67SZ                    | [1992f23f11](https://linux-hardware.org/?probe=1992f23f11) | Jan 15, 2021 |
| whyopencom... | Unknown                     | [05e1dc54c4](https://linux-hardware.org/?probe=05e1dc54c4) | Jan 15, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [680db2a270](https://linux-hardware.org/?probe=680db2a270) | Jan 14, 2021 |
| HP            | Laptop 15s-eq1xxx           | [51f542581b](https://linux-hardware.org/?probe=51f542581b) | Jan 13, 2021 |
| Sony          | SVE1511F4E                  | [18f6b7a23f](https://linux-hardware.org/?probe=18f6b7a23f) | Jan 13, 2021 |
| HP            | EliteBook 840 G4            | [2e35accad4](https://linux-hardware.org/?probe=2e35accad4) | Jan 12, 2021 |
| Dell          | Latitude XT2                | [958e277130](https://linux-hardware.org/?probe=958e277130) | Jan 12, 2021 |
| Acer          | V3-771                      | [816da2c056](https://linux-hardware.org/?probe=816da2c056) | Jan 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1209b7ddaa](https://linux-hardware.org/?probe=1209b7ddaa) | Jan 10, 2021 |
| Dell          | XPS 13 7390                 | [ee990dcfb4](https://linux-hardware.org/?probe=ee990dcfb4) | Jan 10, 2021 |
| Lenovo        | ThinkPad T490 20N3S4AF00    | [88d0c92974](https://linux-hardware.org/?probe=88d0c92974) | Jan 05, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [6226d61b8d](https://linux-hardware.org/?probe=6226d61b8d) | Jan 05, 2021 |
| Lenovo        | ThinkPad X200 74591P0       | [0280683b9f](https://linux-hardware.org/?probe=0280683b9f) | Jan 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [0f6cbbdc40](https://linux-hardware.org/?probe=0f6cbbdc40) | Jan 03, 2021 |
| Dell          | XPS 13 7390                 | [7fcac0b28e](https://linux-hardware.org/?probe=7fcac0b28e) | Jan 01, 2021 |
| HP            | ProBook 650 G2              | [4e4dfa1185](https://linux-hardware.org/?probe=4e4dfa1185) | Jan 01, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [7c5bea876e](https://linux-hardware.org/?probe=7c5bea876e) | Dec 30, 2020 |
| Sony          | SVE1511F4E                  | [2482a9cf42](https://linux-hardware.org/?probe=2482a9cf42) | Dec 29, 2020 |
| Sony          | SVE1511F4E                  | [9ddcb0cab8](https://linux-hardware.org/?probe=9ddcb0cab8) | Dec 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9e768a771f](https://linux-hardware.org/?probe=9e768a771f) | Dec 29, 2020 |
| Dell          | Latitude E7470              | [5e06bae0e3](https://linux-hardware.org/?probe=5e06bae0e3) | Dec 28, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [0566fe029e](https://linux-hardware.org/?probe=0566fe029e) | Dec 28, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [ff668fef04](https://linux-hardware.org/?probe=ff668fef04) | Dec 28, 2020 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Acer          | Nitro AN515-44              | [017b4363ac](https://linux-hardware.org/?probe=017b4363ac) | Dec 26, 2020 |
| HP            | Pavilion 17                 | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [c5acd280dc](https://linux-hardware.org/?probe=c5acd280dc) | Dec 25, 2020 |
| Sony          | VPCEH2P1E                   | [f68b654e04](https://linux-hardware.org/?probe=f68b654e04) | Dec 24, 2020 |
| Acer          | Nitro AN515-44              | [28a3b8bc6f](https://linux-hardware.org/?probe=28a3b8bc6f) | Dec 24, 2020 |
| Lenovo        | ThinkPad T460 20FMS08Q1B    | [97f9380c82](https://linux-hardware.org/?probe=97f9380c82) | Dec 24, 2020 |
| Samsung       | 700T1C                      | [0f8a8671f2](https://linux-hardware.org/?probe=0f8a8671f2) | Dec 24, 2020 |
| Acer          | Aspire 7741                 | [bb04468cdd](https://linux-hardware.org/?probe=bb04468cdd) | Dec 22, 2020 |
| Apple         | MacBookPro11,1              | [7b60dbe66e](https://linux-hardware.org/?probe=7b60dbe66e) | Dec 22, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [9736b48f8d](https://linux-hardware.org/?probe=9736b48f8d) | Dec 22, 2020 |
| SLIMBOOK      | PROX15-AMD                  | [1746196bea](https://linux-hardware.org/?probe=1746196bea) | Dec 22, 2020 |
| ASUSTek       | UX331UA                     | [f570bd4fca](https://linux-hardware.org/?probe=f570bd4fca) | Dec 21, 2020 |
| Apple         | MacBookPro11,1              | [86f1e40ed8](https://linux-hardware.org/?probe=86f1e40ed8) | Dec 21, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [991d88e936](https://linux-hardware.org/?probe=991d88e936) | Dec 21, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [f5320272b1](https://linux-hardware.org/?probe=f5320272b1) | Dec 21, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | [1dddf64cc8](https://linux-hardware.org/?probe=1dddf64cc8) | Dec 20, 2020 |
| IGEL Techn... | M330C                       | [e2f47ddf56](https://linux-hardware.org/?probe=e2f47ddf56) | Dec 20, 2020 |
| IGEL Techn... | M330C                       | [e22d107c2b](https://linux-hardware.org/?probe=e22d107c2b) | Dec 20, 2020 |
| Dell          | Vostro 7590                 | [d71985d7a7](https://linux-hardware.org/?probe=d71985d7a7) | Dec 16, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [a1b69bb2a0](https://linux-hardware.org/?probe=a1b69bb2a0) | Dec 14, 2020 |
| Lenovo        | ThinkPad T440p 20AWS37D0... | [c35140641b](https://linux-hardware.org/?probe=c35140641b) | Dec 13, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [d89c8f909d](https://linux-hardware.org/?probe=d89c8f909d) | Dec 12, 2020 |
| HP            | ProBook 650 G2              | [88c6bb8d12](https://linux-hardware.org/?probe=88c6bb8d12) | Dec 11, 2020 |
| Packard Be... | EasyNote TE11HC             | [ecfcd2d772](https://linux-hardware.org/?probe=ecfcd2d772) | Dec 10, 2020 |
| Acer          | Aspire F5-771G              | [6d732fe2b5](https://linux-hardware.org/?probe=6d732fe2b5) | Dec 10, 2020 |
| ASUSTek       | G771JW                      | [0ebe86b001](https://linux-hardware.org/?probe=0ebe86b001) | Dec 08, 2020 |
| ASUSTek       | BU201LA                     | [4120fa5430](https://linux-hardware.org/?probe=4120fa5430) | Dec 07, 2020 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [307334cdad](https://linux-hardware.org/?probe=307334cdad) | Dec 07, 2020 |
| ASUSTek       | BU201LA                     | [f3fea11b14](https://linux-hardware.org/?probe=f3fea11b14) | Dec 07, 2020 |
| ASUSTek       | BU201LA                     | [efdfbd73d5](https://linux-hardware.org/?probe=efdfbd73d5) | Dec 06, 2020 |
| Acer          | Aspire V3-772G              | [5c75458a8d](https://linux-hardware.org/?probe=5c75458a8d) | Dec 05, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | [112d12030c](https://linux-hardware.org/?probe=112d12030c) | Dec 04, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0UD0... | [992060a459](https://linux-hardware.org/?probe=992060a459) | Dec 02, 2020 |
| Samsung       | 730U3E/740U3E               | [f392da9fc9](https://linux-hardware.org/?probe=f392da9fc9) | Dec 02, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0UD0... | [47e51b151b](https://linux-hardware.org/?probe=47e51b151b) | Dec 01, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [b80ed54426](https://linux-hardware.org/?probe=b80ed54426) | Dec 01, 2020 |
| Lenovo        | ThinkPad SL510 28479UU      | [f805d10499](https://linux-hardware.org/?probe=f805d10499) | Nov 28, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [afff87899c](https://linux-hardware.org/?probe=afff87899c) | Nov 28, 2020 |
| Toshiba       | TECRA R950                  | [e9755d13c3](https://linux-hardware.org/?probe=e9755d13c3) | Nov 28, 2020 |
| Samsung       | QX310/QX410/QX510/SF310/... | [dec24f879f](https://linux-hardware.org/?probe=dec24f879f) | Nov 26, 2020 |
| Dell          | XPS 15 9560                 | [7da87ec366](https://linux-hardware.org/?probe=7da87ec366) | Nov 26, 2020 |
| Dell          | XPS 15 9560                 | [30c4a823d8](https://linux-hardware.org/?probe=30c4a823d8) | Nov 26, 2020 |
| HP            | ProBook 440 G6              | [d4f0cf4cf6](https://linux-hardware.org/?probe=d4f0cf4cf6) | Nov 25, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [814797bb7b](https://linux-hardware.org/?probe=814797bb7b) | Nov 24, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [a45fc859a5](https://linux-hardware.org/?probe=a45fc859a5) | Nov 24, 2020 |
| ARIMA         | W622-DCX                    | [07cc1e0952](https://linux-hardware.org/?probe=07cc1e0952) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | [7388498d54](https://linux-hardware.org/?probe=7388498d54) | Nov 22, 2020 |
| Dell          | Latitude E6430              | [a1d7b0f9ab](https://linux-hardware.org/?probe=a1d7b0f9ab) | Nov 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [07b3330478](https://linux-hardware.org/?probe=07b3330478) | Nov 19, 2020 |
| HP            | ProBook 455 G7              | [86e6b8d3b3](https://linux-hardware.org/?probe=86e6b8d3b3) | Nov 18, 2020 |
| Lenovo        | ThinkPad T530 24296HG       | [04b88a5f7b](https://linux-hardware.org/?probe=04b88a5f7b) | Nov 16, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [eafab55a01](https://linux-hardware.org/?probe=eafab55a01) | Nov 15, 2020 |
| HP            | EliteBook Folio 1040 G1     | [572a7393df](https://linux-hardware.org/?probe=572a7393df) | Nov 14, 2020 |
| HP            | ENVY 15                     | [fb33289aed](https://linux-hardware.org/?probe=fb33289aed) | Nov 13, 2020 |
| Dell          | Precision 7530              | [2dca9dbf01](https://linux-hardware.org/?probe=2dca9dbf01) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | [7c89e8677b](https://linux-hardware.org/?probe=7c89e8677b) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | [e996126e7f](https://linux-hardware.org/?probe=e996126e7f) | Nov 12, 2020 |
| HP            | EliteBook x360 1040 G5      | [77d6b5680d](https://linux-hardware.org/?probe=77d6b5680d) | Nov 11, 2020 |
| HP            | Pavilion x2 Detachable P... | [f2fb66005f](https://linux-hardware.org/?probe=f2fb66005f) | Nov 11, 2020 |
| Lenovo        | ThinkPad E15 20RD003HMZ     | [3895f41e90](https://linux-hardware.org/?probe=3895f41e90) | Nov 10, 2020 |
| Acer          | Swift SF314-56              | [0a2c9a74a4](https://linux-hardware.org/?probe=0a2c9a74a4) | Nov 10, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [233b60886e](https://linux-hardware.org/?probe=233b60886e) | Nov 10, 2020 |
| Acer          | Aspire S7-391               | [b2b78adbd5](https://linux-hardware.org/?probe=b2b78adbd5) | Nov 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [04dd6da950](https://linux-hardware.org/?probe=04dd6da950) | Nov 09, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | EliteBook 8560w             | [8393d44a56](https://linux-hardware.org/?probe=8393d44a56) | Nov 06, 2020 |
| Acer          | Aspire V3-772G              | [ef2f846e22](https://linux-hardware.org/?probe=ef2f846e22) | Nov 04, 2020 |
| ASUSTek       | F3U                         | [a48a07cbcf](https://linux-hardware.org/?probe=a48a07cbcf) | Nov 03, 2020 |
| ASUSTek       | F3U                         | [828ad4fe18](https://linux-hardware.org/?probe=828ad4fe18) | Nov 03, 2020 |
| Acer          | Aspire V3-772G              | [754191159a](https://linux-hardware.org/?probe=754191159a) | Nov 03, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e68efeb7b8](https://linux-hardware.org/?probe=e68efeb7b8) | Nov 01, 2020 |
| Schenker      | SLIM15 SSL15L19             | [fa9a4ec7af](https://linux-hardware.org/?probe=fa9a4ec7af) | Oct 31, 2020 |
| Acer          | Aspire V3-772G              | [5eaea33f57](https://linux-hardware.org/?probe=5eaea33f57) | Oct 31, 2020 |
| HP            | EliteBook 850 G6            | [14f636e00d](https://linux-hardware.org/?probe=14f636e00d) | Oct 30, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [cd1259f1c9](https://linux-hardware.org/?probe=cd1259f1c9) | Oct 29, 2020 |
| Dell          | Latitude E7240              | [60701e4df3](https://linux-hardware.org/?probe=60701e4df3) | Oct 29, 2020 |
| HP            | OMEN by Laptop              | [5f09eb2168](https://linux-hardware.org/?probe=5f09eb2168) | Oct 26, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [3ed569dfa5](https://linux-hardware.org/?probe=3ed569dfa5) | Oct 25, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [72335ec621](https://linux-hardware.org/?probe=72335ec621) | Oct 25, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [5aa23a1d7e](https://linux-hardware.org/?probe=5aa23a1d7e) | Oct 23, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [94a8a3e5b3](https://linux-hardware.org/?probe=94a8a3e5b3) | Oct 22, 2020 |
| HP            | EliteBook x360 1040 G5      | [78cbc1663e](https://linux-hardware.org/?probe=78cbc1663e) | Oct 22, 2020 |
| Acer          | V3-771                      | [25aef0ed9b](https://linux-hardware.org/?probe=25aef0ed9b) | Oct 22, 2020 |
| Acer          | V3-771                      | [a360f75508](https://linux-hardware.org/?probe=a360f75508) | Oct 22, 2020 |
| HP            | EliteBook 840 G2            | [3b00a26eab](https://linux-hardware.org/?probe=3b00a26eab) | Oct 22, 2020 |
| HP            | ProBook 650 G2              | [0e8e3a9c90](https://linux-hardware.org/?probe=0e8e3a9c90) | Oct 21, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [4a883571a1](https://linux-hardware.org/?probe=4a883571a1) | Oct 21, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [c527497a87](https://linux-hardware.org/?probe=c527497a87) | Oct 20, 2020 |
| TUXEDO        | Book XC1711                 | [85474c7447](https://linux-hardware.org/?probe=85474c7447) | Oct 19, 2020 |
| Unknown       | Unknown                     | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| Lenovo        | ThinkPad W510 4389A16       | [4d825513e3](https://linux-hardware.org/?probe=4d825513e3) | Oct 18, 2020 |
| HP            | Pavilion dv6700             | [632f3c5363](https://linux-hardware.org/?probe=632f3c5363) | Oct 18, 2020 |
| HP            | Pavilion dv6700             | [7fee612d83](https://linux-hardware.org/?probe=7fee612d83) | Oct 18, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [25c98f28de](https://linux-hardware.org/?probe=25c98f28de) | Oct 15, 2020 |
| Lenovo        | ThinkPad R500 2732BHG       | [ce5551a52f](https://linux-hardware.org/?probe=ce5551a52f) | Oct 15, 2020 |
| Dell          | Latitude 7490               | [8b6e96473e](https://linux-hardware.org/?probe=8b6e96473e) | Oct 15, 2020 |
| Dell          | XPS 13 9350                 | [f99a03a6fa](https://linux-hardware.org/?probe=f99a03a6fa) | Oct 14, 2020 |
| Lenovo        | Z51-70 80K6                 | [1392da5d39](https://linux-hardware.org/?probe=1392da5d39) | Oct 14, 2020 |
| Lenovo        | ThinkPad T61 7661WBL        | [f19b646a14](https://linux-hardware.org/?probe=f19b646a14) | Oct 14, 2020 |
| Lenovo        | ThinkPad Edge E530 3259A... | [ee0934ca90](https://linux-hardware.org/?probe=ee0934ca90) | Oct 10, 2020 |
| ASUSTek       | K73SD                       | [776517f452](https://linux-hardware.org/?probe=776517f452) | Oct 10, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [83ae97a2cc](https://linux-hardware.org/?probe=83ae97a2cc) | Oct 08, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [fb75c1edd7](https://linux-hardware.org/?probe=fb75c1edd7) | Oct 05, 2020 |
| Lenovo        | B71-80 80RJ                 | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| Apple         | MacBookAir5,2               | [ae92ea7a52](https://linux-hardware.org/?probe=ae92ea7a52) | Oct 04, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [b02303b4f3](https://linux-hardware.org/?probe=b02303b4f3) | Oct 04, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [6b46fbb6cd](https://linux-hardware.org/?probe=6b46fbb6cd) | Oct 04, 2020 |
| Unknown       | Unknown                     | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| Sony          | VPCYB3V1E                   | [f116097e48](https://linux-hardware.org/?probe=f116097e48) | Oct 02, 2020 |
| Samsung       | NC10                        | [8ba791387e](https://linux-hardware.org/?probe=8ba791387e) | Oct 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a295a656f1](https://linux-hardware.org/?probe=a295a656f1) | Sep 30, 2020 |
| Sony          | VGN-AR61ZU                  | [b7d1817106](https://linux-hardware.org/?probe=b7d1817106) | Sep 29, 2020 |
| Dell          | Latitude 7490               | [13cb89196f](https://linux-hardware.org/?probe=13cb89196f) | Sep 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [5faa8e4ca3](https://linux-hardware.org/?probe=5faa8e4ca3) | Sep 28, 2020 |
| ASUSTek       | X510URR                     | [e0520a6f96](https://linux-hardware.org/?probe=e0520a6f96) | Sep 21, 2020 |
| Dell          | XPS 13 9300                 | [b66433f2e6](https://linux-hardware.org/?probe=b66433f2e6) | Sep 20, 2020 |
| ASUSTek       | X541UAK                     | [d0712e5a04](https://linux-hardware.org/?probe=d0712e5a04) | Sep 19, 2020 |
| HP            | Laptop 15-bs1xx             | [711a85f008](https://linux-hardware.org/?probe=711a85f008) | Sep 19, 2020 |
| Lenovo        | ThinkPad T470s 20HGS0B80... | [123de4a1c7](https://linux-hardware.org/?probe=123de4a1c7) | Sep 17, 2020 |
| Toshiba       | Satellite P50-C             | [6245fb1a20](https://linux-hardware.org/?probe=6245fb1a20) | Sep 17, 2020 |
| HP            | ZBook 15 G6                 | [4e73019ac5](https://linux-hardware.org/?probe=4e73019ac5) | Sep 16, 2020 |
| Sony          | SVE1511F4E                  | [891f09413c](https://linux-hardware.org/?probe=891f09413c) | Sep 16, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6130ae6b01](https://linux-hardware.org/?probe=6130ae6b01) | Sep 16, 2020 |
| ASUSTek       | K73SD                       | [67507a1125](https://linux-hardware.org/?probe=67507a1125) | Sep 16, 2020 |
| Lenovo        | ThinkPad P51 20HJS20100     | [0f91d1ee1f](https://linux-hardware.org/?probe=0f91d1ee1f) | Sep 16, 2020 |
| Lenovo        | ThinkPad P51 20HJS20100     | [1288fee0ed](https://linux-hardware.org/?probe=1288fee0ed) | Sep 16, 2020 |
| HP            | Laptop 15-dw0xxx            | [4c0cfd6509](https://linux-hardware.org/?probe=4c0cfd6509) | Sep 16, 2020 |
| HP            | EliteBook 840 G5            | [5511ff7784](https://linux-hardware.org/?probe=5511ff7784) | Sep 15, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [4c15a9819a](https://linux-hardware.org/?probe=4c15a9819a) | Sep 14, 2020 |
| HP            | OMEN by Laptop              | [1aca06c6ec](https://linux-hardware.org/?probe=1aca06c6ec) | Sep 14, 2020 |
| HP            | Compaq 15                   | [3c3d5c4299](https://linux-hardware.org/?probe=3c3d5c4299) | Sep 12, 2020 |
| HP            | Compaq 15                   | [8ae9fd7bff](https://linux-hardware.org/?probe=8ae9fd7bff) | Sep 12, 2020 |
| Razer         | Blade                       | [8a242cff29](https://linux-hardware.org/?probe=8a242cff29) | Sep 11, 2020 |
| Toshiba       | PORTEGE Z10T-A              | [0a43ad62d7](https://linux-hardware.org/?probe=0a43ad62d7) | Sep 08, 2020 |
| HP            | EliteBook 840 G5            | [a4465c328f](https://linux-hardware.org/?probe=a4465c328f) | Sep 08, 2020 |
| Lenovo        | ThinkPad Edge E530 3259A... | [deca89911a](https://linux-hardware.org/?probe=deca89911a) | Sep 07, 2020 |
| Dell          | Latitude E7470              | [42f49c6394](https://linux-hardware.org/?probe=42f49c6394) | Sep 07, 2020 |
| Apple         | MacBookPro9,2               | [96509c0af6](https://linux-hardware.org/?probe=96509c0af6) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [59ed33b893](https://linux-hardware.org/?probe=59ed33b893) | Sep 06, 2020 |
| Lenovo        | ThinkPad T590 20N4000BMZ    | [ff7f82b032](https://linux-hardware.org/?probe=ff7f82b032) | Sep 04, 2020 |
| Lenovo        | ThinkPad T590 20N4000BMZ    | [587d4d9277](https://linux-hardware.org/?probe=587d4d9277) | Sep 04, 2020 |
| HP            | Pavilion g6                 | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Apple         | MacBookPro9,2               | [6b4ddf377d](https://linux-hardware.org/?probe=6b4ddf377d) | Sep 03, 2020 |
| HP            | Pavilion g6                 | [ad8002e60e](https://linux-hardware.org/?probe=ad8002e60e) | Sep 01, 2020 |
| HP            | Laptop 15s-fq1xxx           | [5e853f5521](https://linux-hardware.org/?probe=5e853f5521) | Aug 31, 2020 |
| ASUSTek       | GL752VW                     | [d350d76726](https://linux-hardware.org/?probe=d350d76726) | Aug 29, 2020 |
| HP            | ProBook 650 G2              | [ad27d76a1a](https://linux-hardware.org/?probe=ad27d76a1a) | Aug 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | [f58e055469](https://linux-hardware.org/?probe=f58e055469) | Aug 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | [d19c11c74a](https://linux-hardware.org/?probe=d19c11c74a) | Aug 25, 2020 |
| Apple         | MacBookAir4,1               | [b6d976fc76](https://linux-hardware.org/?probe=b6d976fc76) | Aug 24, 2020 |
| Lenovo        | ThinkPad X230 23252S4       | [5fe0becd60](https://linux-hardware.org/?probe=5fe0becd60) | Aug 22, 2020 |
| Lenovo        | ThinkPad T580 20LAS1VW00    | [f75ec41143](https://linux-hardware.org/?probe=f75ec41143) | Aug 20, 2020 |
| Lenovo        | ThinkPad X280 20KES3DB00    | [c5e30308a8](https://linux-hardware.org/?probe=c5e30308a8) | Aug 19, 2020 |
| ASUSTek       | GL702ZC                     | [f685b1bfc0](https://linux-hardware.org/?probe=f685b1bfc0) | Aug 18, 2020 |
| HP            | Laptop 15s-fq1xxx           | [3f770a739d](https://linux-hardware.org/?probe=3f770a739d) | Aug 18, 2020 |
| HP            | ZBook 14u G6                | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| Acer          | TMP455-M                    | [8ebc259273](https://linux-hardware.org/?probe=8ebc259273) | Aug 17, 2020 |
| HP            | Laptop 15s-fq1xxx           | [19d3840414](https://linux-hardware.org/?probe=19d3840414) | Aug 17, 2020 |
| Fujitsu Si... | LIFEBOOK S6410              | [0aebb46ce0](https://linux-hardware.org/?probe=0aebb46ce0) | Aug 16, 2020 |
| Lenovo        | ThinkPad W530 24415QG       | [03d4068143](https://linux-hardware.org/?probe=03d4068143) | Aug 14, 2020 |
| Razer         | Blade Stealth 13 Late 20... | [32d0727725](https://linux-hardware.org/?probe=32d0727725) | Aug 13, 2020 |
| HP            | Pavilion dm1                | [60fa55c570](https://linux-hardware.org/?probe=60fa55c570) | Aug 12, 2020 |
| HP            | ZBook 14u G6                | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ac527dcde7](https://linux-hardware.org/?probe=ac527dcde7) | Aug 11, 2020 |
| Acer          | Aspire E1-572G              | [1a738a3991](https://linux-hardware.org/?probe=1a738a3991) | Aug 08, 2020 |
| PC Special... | X170SM                      | [0c9f2dc741](https://linux-hardware.org/?probe=0c9f2dc741) | Aug 07, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [1b44a0dac4](https://linux-hardware.org/?probe=1b44a0dac4) | Jul 31, 2020 |
| HP            | EliteBook Folio 1040 G1     | [379f2065ae](https://linux-hardware.org/?probe=379f2065ae) | Jul 31, 2020 |
| HP            | EliteBook Folio 1040 G1     | [50c100fc45](https://linux-hardware.org/?probe=50c100fc45) | Jul 31, 2020 |
| Dell          | Latitude E7470              | [b01705d65a](https://linux-hardware.org/?probe=b01705d65a) | Jul 31, 2020 |
| Dell          | System XPS L502X            | [2d4d18566a](https://linux-hardware.org/?probe=2d4d18566a) | Jul 28, 2020 |
| Dell          | System XPS L502X            | [8bb4b95768](https://linux-hardware.org/?probe=8bb4b95768) | Jul 28, 2020 |
| HP            | Pavilion dm1                | [db3461a440](https://linux-hardware.org/?probe=db3461a440) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| TUXEDO        | Unknown                     | [472fe9bea2](https://linux-hardware.org/?probe=472fe9bea2) | Jul 23, 2020 |
| HP            | EliteBook 840 G6            | [cdc922b41d](https://linux-hardware.org/?probe=cdc922b41d) | Jul 23, 2020 |
| Dell          | XPS 15 9500                 | [de8b60de3d](https://linux-hardware.org/?probe=de8b60de3d) | Jul 23, 2020 |
| Dell          | XPS 15 9560                 | [c90f589ae7](https://linux-hardware.org/?probe=c90f589ae7) | Jul 21, 2020 |
| HP            | OMEN by Laptop              | [a9202a9c5e](https://linux-hardware.org/?probe=a9202a9c5e) | Jul 20, 2020 |
| HP            | Pavilion dm1                | [84fc871f29](https://linux-hardware.org/?probe=84fc871f29) | Jul 18, 2020 |
| HP            | Pavilion dm1                | [ccc4a944e8](https://linux-hardware.org/?probe=ccc4a944e8) | Jul 18, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 131       | 14.13%  |
| Ubuntu 18.04                 | 90        | 9.71%   |
| Ubuntu 22.04                 | 35        | 3.78%   |
| Debian 11                    | 29        | 3.13%   |
| Linux Mint 20.3              | 27        | 2.91%   |
| Debian 10                    | 24        | 2.59%   |
| OpenMandriva 4.3             | 22        | 2.37%   |
| Linux Mint 20.1              | 20        | 2.16%   |
| Linux Mint 20.2              | 19        | 2.05%   |
| Ubuntu 21.10                 | 17        | 1.83%   |
| KDE neon 20.04               | 17        | 1.83%   |
| OpenMandriva 4.2             | 16        | 1.73%   |
| Ubuntu 20.10                 | 14        | 1.51%   |
| Ubuntu 19.10                 | 13        | 1.4%    |
| Manjaro                      | 13        | 1.4%    |
| Zorin 16                     | 12        | 1.29%   |
| Pop!_OS 22.04                | 12        | 1.29%   |
| Pop!_OS 21.04                | 12        | 1.29%   |
| Arch Rolling                 | 12        | 1.29%   |
| Arch                         | 12        | 1.29%   |
| Pop!_OS 20.10                | 11        | 1.19%   |
| Linux Mint 19.3              | 11        | 1.19%   |
| Fedora 34                    | 11        | 1.19%   |
| Fedora 32                    | 11        | 1.19%   |
| ArcoLinux Rolling            | 11        | 1.19%   |
| Pop!_OS 20.04                | 10        | 1.08%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 1.08%   |
| Kubuntu 20.04                | 10        | 1.08%   |
| Fedora 35                    | 10        | 1.08%   |
| Fedora 37                    | 9         | 0.97%   |
| Fedora 33                    | 9         | 0.97%   |
| Zorin 15                     | 8         | 0.86%   |
| Fedora 36                    | 8         | 0.86%   |
| Ubuntu MATE 20.04            | 7         | 0.76%   |
| LMDE 4                       | 7         | 0.76%   |
| Linux Mint 21                | 7         | 0.76%   |
| Fedora 31                    | 7         | 0.76%   |
| Ubuntu 21.04                 | 6         | 0.65%   |
| Ubuntu 19.04                 | 6         | 0.65%   |
| OpenMandriva 23.01           | 6         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 296       | 34.34%  |
| Linux Mint    | 87        | 10.09%  |
| Fedora        | 61        | 7.08%   |
| Debian        | 61        | 7.08%   |
| OpenMandriva  | 51        | 5.92%   |
| Pop!_OS       | 46        | 5.34%   |
| Manjaro       | 32        | 3.71%   |
| Kubuntu       | 23        | 2.67%   |
| Arch          | 23        | 2.67%   |
| Zorin         | 20        | 2.32%   |
| KDE neon      | 17        | 1.97%   |
| ROSA          | 14        | 1.62%   |
| ArcoLinux     | 14        | 1.62%   |
| openSUSE      | 13        | 1.51%   |
| Ubuntu MATE   | 10        | 1.16%   |
| Xubuntu       | 9         | 1.04%   |
| Kali          | 8         | 0.93%   |
| LMDE          | 7         | 0.81%   |
| Gentoo        | 7         | 0.81%   |
| Lubuntu       | 6         | 0.7%    |
| Endless       | 6         | 0.7%    |
| Elementary    | 6         | 0.7%    |
| BlackPanther  | 5         | 0.58%   |
| Ubuntu Budgie | 4         | 0.46%   |
| Feren OS      | 4         | 0.46%   |
| Void Linux    | 3         | 0.35%   |
| Ubuntu Unity  | 3         | 0.35%   |
| RHEL          | 3         | 0.35%   |
| Clear Linux   | 3         | 0.35%   |
| Parrot        | 2         | 0.23%   |
| Garuda Linux  | 2         | 0.23%   |
| EndeavourOS   | 2         | 0.23%   |
| CentOS        | 2         | 0.23%   |
| Artix         | 2         | 0.23%   |
| SteamOS       | 1         | 0.12%   |
| Solus         | 1         | 0.12%   |
| Redcore       | 1         | 0.12%   |
| Reborn OS     | 1         | 0.12%   |
| Peppermint    | 1         | 0.12%   |
| NixOS         | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 20        | 1.93%   |
| 5.15.0-56-generic        | 16        | 1.54%   |
| 5.10.14-desktop-1omv4002 | 16        | 1.54%   |
| 5.4.0-42-generic         | 14        | 1.35%   |
| 5.4.0-52-generic         | 12        | 1.16%   |
| 5.4.0-58-generic         | 10        | 0.97%   |
| 5.4.0-47-generic         | 10        | 0.97%   |
| 5.15.0-52-generic        | 9         | 0.87%   |
| 5.8.0-55-generic         | 8         | 0.77%   |
| 5.4.0-91-generic         | 8         | 0.77%   |
| 5.4.0-80-generic         | 8         | 0.77%   |
| 5.3.0-28-generic         | 8         | 0.77%   |
| 5.8.0-59-generic         | 7         | 0.68%   |
| 5.4.0-72-generic         | 7         | 0.68%   |
| 5.4.0-65-generic         | 7         | 0.68%   |
| 5.4.0-62-generic         | 7         | 0.68%   |
| 5.4.0-48-generic         | 7         | 0.68%   |
| 5.15.0-48-generic        | 7         | 0.68%   |
| 5.13.0-30-generic        | 7         | 0.68%   |
| 5.11.0-43-generic        | 7         | 0.68%   |
| 5.10.0-8-amd64           | 7         | 0.68%   |
| 5.0.0-37-generic         | 7         | 0.68%   |
| 6.1.1-desktop-1omv2290   | 6         | 0.58%   |
| 5.4.0-81-generic         | 6         | 0.58%   |
| 5.4.0-51-generic         | 6         | 0.58%   |
| 5.4.0-37-generic         | 6         | 0.58%   |
| 5.3.0-51-generic         | 6         | 0.58%   |
| 5.3.0-40-generic         | 6         | 0.58%   |
| 5.15.0-58-generic        | 6         | 0.58%   |
| 5.13.0-39-generic        | 6         | 0.58%   |
| 5.13.0-35-generic        | 6         | 0.58%   |
| 5.11.0-7620-generic      | 6         | 0.58%   |
| 5.11.0-40-generic        | 6         | 0.58%   |
| 5.11.0-38-generic        | 6         | 0.58%   |
| 4.15.0-96-generic        | 6         | 0.58%   |
| 5.8.0-53-generic         | 5         | 0.48%   |
| 5.4.0-73-generic         | 5         | 0.48%   |
| 5.4.0-66-generic         | 5         | 0.48%   |
| 5.4.0-45-generic         | 5         | 0.48%   |
| 5.4.0-33-generic         | 5         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 175       | 18.25%  |
| 5.15.0  | 69        | 7.19%   |
| 5.8.0   | 60        | 6.26%   |
| 4.15.0  | 57        | 5.94%   |
| 5.11.0  | 55        | 5.74%   |
| 5.13.0  | 51        | 5.32%   |
| 5.3.0   | 40        | 4.17%   |
| 5.10.0  | 33        | 3.44%   |
| 4.19.0  | 27        | 2.82%   |
| 5.0.0   | 26        | 2.71%   |
| 5.16.7  | 20        | 2.09%   |
| 4.18.0  | 18        | 1.88%   |
| 5.10.14 | 17        | 1.77%   |
| 5.14.0  | 11        | 1.15%   |
| 5.19.0  | 9         | 0.94%   |
| 6.1.1   | 8         | 0.83%   |
| 5.6.0   | 7         | 0.73%   |
| 5.17.5  | 7         | 0.73%   |
| 6.0.15  | 5         | 0.52%   |
| 6.0.0   | 5         | 0.52%   |
| 5.6.14  | 5         | 0.52%   |
| 5.9.16  | 4         | 0.42%   |
| 5.5.8   | 4         | 0.42%   |
| 5.18.0  | 4         | 0.42%   |
| 4.18.16 | 4         | 0.42%   |
| 6.0.8   | 3         | 0.31%   |
| 6.0.7   | 3         | 0.31%   |
| 6.0.12  | 3         | 0.31%   |
| 6.0.10  | 3         | 0.31%   |
| 5.9.8   | 3         | 0.31%   |
| 5.9.11  | 3         | 0.31%   |
| 5.7.0   | 3         | 0.31%   |
| 5.6.4   | 3         | 0.31%   |
| 5.17.6  | 3         | 0.31%   |
| 5.16.0  | 3         | 0.31%   |
| 5.13.8  | 3         | 0.31%   |
| 5.12.9  | 3         | 0.31%   |
| 5.11.4  | 3         | 0.31%   |
| 5.11.2  | 3         | 0.31%   |
| 5.10.7  | 3         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 183       | 19.3%   |
| 5.15    | 91        | 9.6%    |
| 5.8     | 71        | 7.49%   |
| 5.11    | 71        | 7.49%   |
| 5.10    | 63        | 6.65%   |
| 5.13    | 62        | 6.54%   |
| 4.15    | 57        | 6.01%   |
| 5.3     | 45        | 4.75%   |
| 5.16    | 35        | 3.69%   |
| 4.19    | 32        | 3.38%   |
| 5.0     | 28        | 2.95%   |
| 6.0     | 24        | 2.53%   |
| 4.18    | 24        | 2.53%   |
| 5.17    | 21        | 2.22%   |
| 5.6     | 18        | 1.9%    |
| 5.9     | 17        | 1.79%   |
| 5.14    | 17        | 1.79%   |
| 5.19    | 16        | 1.69%   |
| 5.18    | 14        | 1.48%   |
| 5.12    | 12        | 1.27%   |
| 5.7     | 11        | 1.16%   |
| 4.9     | 11        | 1.16%   |
| 6.1     | 9         | 0.95%   |
| 5.5     | 6         | 0.63%   |
| 5.2     | 2         | 0.21%   |
| 4.4     | 2         | 0.21%   |
| 4.14    | 2         | 0.21%   |
| 4.1     | 2         | 0.21%   |
| 4.20    | 1         | 0.11%   |
| 4.10    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 815       | 97.84%  |
| i686   | 18        | 2.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 378       | 43.05%  |
| KDE5            | 137       | 15.6%   |
| Unknown         | 115       | 13.1%   |
| X-Cinnamon      | 77        | 8.77%   |
| XFCE            | 46        | 5.24%   |
| MATE            | 25        | 2.85%   |
| KDE             | 16        | 1.82%   |
| Cinnamon        | 15        | 1.71%   |
| LXDE            | 12        | 1.37%   |
| LXQt            | 9         | 1.03%   |
| KDE4            | 8         | 0.91%   |
| i3              | 8         | 0.91%   |
| GNOME Flashback | 7         | 0.8%    |
| Pantheon        | 6         | 0.68%   |
| Budgie          | 6         | 0.68%   |
| bspwm           | 4         | 0.46%   |
| Unity           | 2         | 0.23%   |
| qtile           | 2         | 0.23%   |
| sway            | 1         | 0.11%   |
| openbox         | 1         | 0.11%   |
| herbstluftwm    | 1         | 0.11%   |
| GNUstep         | 1         | 0.11%   |
| GNOME Classic   | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 633       | 73.18%  |
| Wayland | 142       | 16.42%  |
| Unknown | 72        | 8.32%   |
| Tty     | 18        | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 410       | 47.24%  |
| GDM     | 122       | 14.06%  |
| SDDM    | 116       | 13.36%  |
| LightDM | 91        | 10.48%  |
| GDM3    | 77        | 8.87%   |
| TDM     | 40        | 4.61%   |
| KDM     | 8         | 0.92%   |
| XDM     | 2         | 0.23%   |
| LXDM    | 1         | 0.12%   |
| GREETD  | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 301       | 35.04%  |
| de_CH   | 201       | 23.4%   |
| Unknown | 121       | 14.09%  |
| fr_CH   | 60        | 6.98%   |
| de_DE   | 49        | 5.7%    |
| en_GB   | 40        | 4.66%   |
| C       | 18        | 2.1%    |
| fr_FR   | 17        | 1.98%   |
| pt_PT   | 10        | 1.16%   |
| it_IT   | 8         | 0.93%   |
| it_CH   | 7         | 0.81%   |
| pl_PL   | 3         | 0.35%   |
| es_ES   | 3         | 0.35%   |
| en_CH   | 3         | 0.35%   |
| de_AT   | 3         | 0.35%   |
| ru_RU   | 2         | 0.23%   |
| en_IE   | 2         | 0.23%   |
| en_CA   | 2         | 0.23%   |
| en_AU   | 2         | 0.23%   |
| tr_TR   | 1         | 0.12%   |
| ru_UA   | 1         | 0.12%   |
| POSIX   | 1         | 0.12%   |
| nl_BE   | 1         | 0.12%   |
| de_LI   | 1         | 0.12%   |
| de_IT   | 1         | 0.12%   |
| ca_ES   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 490       | 58.06%  |
| BIOS | 354       | 41.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 662       | 77.7%   |
| Btrfs   | 67        | 7.86%   |
| Overlay | 62        | 7.28%   |
| Unknown | 37        | 4.34%   |
| Xfs     | 10        | 1.17%   |
| Zfs     | 8         | 0.94%   |
| Ext2    | 4         | 0.47%   |
| F2fs    | 1         | 0.12%   |
| Ext3    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 427       | 50.12%  |
| GPT     | 339       | 39.79%  |
| MBR     | 86        | 10.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 750       | 88.55%  |
| Yes       | 97        | 11.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 652       | 77.07%  |
| Yes       | 194       | 22.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 220       | 26.44%  |
| Hewlett-Packard     | 195       | 23.44%  |
| Dell                | 96        | 11.54%  |
| Acer                | 84        | 10.1%   |
| ASUSTek Computer    | 66        | 7.93%   |
| Apple               | 32        | 3.85%   |
| Toshiba             | 16        | 1.92%   |
| Sony                | 12        | 1.44%   |
| TUXEDO              | 11        | 1.32%   |
| Notebook            | 11        | 1.32%   |
| Medion              | 9         | 1.08%   |
| HUAWEI              | 9         | 1.08%   |
| Samsung Electronics | 8         | 0.96%   |
| Razer               | 6         | 0.72%   |
| MSI                 | 5         | 0.6%    |
| Fujitsu             | 5         | 0.6%    |
| Schenker            | 4         | 0.48%   |
| Alienware           | 4         | 0.48%   |
| GPD                 | 3         | 0.36%   |
| Clevo               | 3         | 0.36%   |
| whyopencomputing    | 2         | 0.24%   |
| TrekStor            | 2         | 0.24%   |
| Timi                | 2         | 0.24%   |
| System76            | 2         | 0.24%   |
| PC Specialist       | 2         | 0.24%   |
| Packard Bell        | 2         | 0.24%   |
| MPMAN               | 2         | 0.24%   |
| Valve               | 1         | 0.12%   |
| SLIMBOOK            | 1         | 0.12%   |
| Shuttle             | 1         | 0.12%   |
| Quanta              | 1         | 0.12%   |
| Quanmax             | 1         | 0.12%   |
| Purism              | 1         | 0.12%   |
| Polaroid            | 1         | 0.12%   |
| Panasonic           | 1         | 0.12%   |
| OriginPC            | 1         | 0.12%   |
| LG Electronics      | 1         | 0.12%   |
| Intel               | 1         | 0.12%   |
| IGEL Technology     | 1         | 0.12%   |
| Hampoo              | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Pavilion dv7                            | 7         | 0.84%   |
| Unknown                                    | 7         | 0.84%   |
| HP Notebook                                | 5         | 0.6%    |
| HP ENVY 15                                 | 5         | 0.6%    |
| Dell XPS 15 9570                           | 5         | 0.6%    |
| Dell Latitude E7240                        | 5         | 0.6%    |
| Dell Latitude 7490                         | 5         | 0.6%    |
| HP ProBook 440 G8 Notebook PC              | 4         | 0.48%   |
| HP Pavilion g7                             | 4         | 0.48%   |
| HP Pavilion dv6                            | 4         | 0.48%   |
| HP Laptop 15-bs1xx                         | 4         | 0.48%   |
| HP EliteBook Folio 1040 G1                 | 4         | 0.48%   |
| Dell XPS 15 9560                           | 4         | 0.48%   |
| Dell XPS 15 7590                           | 4         | 0.48%   |
| Apple MacBookPro9,2                        | 4         | 0.48%   |
| TUXEDO Pulse 15 Gen1                       | 3         | 0.36%   |
| Razer Blade                                | 3         | 0.36%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 3         | 0.36%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 3         | 0.36%   |
| HUAWEI MACH-WX9                            | 3         | 0.36%   |
| HP ProBook 440 G6                          | 3         | 0.36%   |
| HP Pavilion g6                             | 3         | 0.36%   |
| HP Pavilion dv6700                         | 3         | 0.36%   |
| HP Pavilion 15                             | 3         | 0.36%   |
| HP ENVY dv7                                | 3         | 0.36%   |
| HP EliteBook 840 G6                        | 3         | 0.36%   |
| HP EliteBook 840 G5                        | 3         | 0.36%   |
| Dell XPS 13 9370                           | 3         | 0.36%   |
| Dell XPS 13 9360                           | 3         | 0.36%   |
| Dell XPS 13 7390                           | 3         | 0.36%   |
| Dell Latitude E7470                        | 3         | 0.36%   |
| Apple MacBookPro8,1                        | 3         | 0.36%   |
| Apple MacBookPro6,2                        | 3         | 0.36%   |
| Apple MacBookPro11,1                       | 3         | 0.36%   |
| Apple MacBookPro10,1                       | 3         | 0.36%   |
| Acer Aspire V3-772G                        | 3         | 0.36%   |
| Acer Aspire A515-51                        | 3         | 0.36%   |
| TUXEDO BC1510 1710                         | 2         | 0.24%   |
| Toshiba Satellite C660                     | 2         | 0.24%   |
| Samsung 700G7C                             | 2         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 164       | 19.71%  |
| Acer Aspire        | 55        | 6.61%   |
| HP EliteBook       | 51        | 6.13%   |
| Dell Latitude      | 40        | 4.81%   |
| HP Pavilion        | 39        | 4.69%   |
| Dell XPS           | 36        | 4.33%   |
| HP ProBook         | 31        | 3.73%   |
| Lenovo IdeaPad     | 17        | 2.04%   |
| HP Laptop          | 17        | 2.04%   |
| HP ENVY            | 16        | 1.92%   |
| Acer Swift         | 13        | 1.56%   |
| Lenovo Yoga        | 12        | 1.44%   |
| Dell Inspiron      | 12        | 1.44%   |
| Toshiba Satellite  | 11        | 1.32%   |
| HP ZBook           | 11        | 1.32%   |
| ASUS ZenBook       | 10        | 1.2%    |
| ASUS VivoBook      | 10        | 1.2%    |
| HP Compaq          | 8         | 0.96%   |
| Unknown            | 7         | 0.84%   |
| Razer Blade        | 6         | 0.72%   |
| Dell Precision     | 6         | 0.72%   |
| HP Notebook        | 5         | 0.6%    |
| Apple MacBookPro11 | 5         | 0.6%    |
| Lenovo ThinkBook   | 4         | 0.48%   |
| Fujitsu LIFEBOOK   | 4         | 0.48%   |
| ASUS ROG           | 4         | 0.48%   |
| Apple MacBookPro9  | 4         | 0.48%   |
| Acer TravelMate    | 4         | 0.48%   |
| TUXEDO Pulse       | 3         | 0.36%   |
| Lenovo Legion      | 3         | 0.36%   |
| HUAWEI MACH-WX9    | 3         | 0.36%   |
| HP OMEN            | 3         | 0.36%   |
| HP 250             | 3         | 0.36%   |
| Apple MacBookPro8  | 3         | 0.36%   |
| Apple MacBookPro6  | 3         | 0.36%   |
| Apple MacBookPro14 | 3         | 0.36%   |
| Apple MacBookPro10 | 3         | 0.36%   |
| Acer Predator      | 3         | 0.36%   |
| Acer Extensa       | 3         | 0.36%   |
| TUXEDO BC1510      | 2         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 90        | 10.82%  |
| 2019 | 83        | 9.98%   |
| 2020 | 82        | 9.86%   |
| 2012 | 71        | 8.53%   |
| 2017 | 61        | 7.33%   |
| 2011 | 59        | 7.09%   |
| 2013 | 54        | 6.49%   |
| 2021 | 52        | 6.25%   |
| 2015 | 49        | 5.89%   |
| 2014 | 49        | 5.89%   |
| 2010 | 46        | 5.53%   |
| 2016 | 42        | 5.05%   |
| 2008 | 26        | 3.13%   |
| 2022 | 20        | 2.4%    |
| 2007 | 20        | 2.4%    |
| 2009 | 18        | 2.16%   |
| 2005 | 5         | 0.6%    |
| 2006 | 4         | 0.48%   |
| 2004 | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 832       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 730       | 86.6%   |
| Enabled  | 113       | 13.4%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 826       | 99.28%  |
| Yes  | 6         | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 213       | 25.06%  |
| 4.01-8.0    | 192       | 22.59%  |
| 8.01-16.0   | 151       | 17.76%  |
| 3.01-4.0    | 131       | 15.41%  |
| 32.01-64.0  | 95        | 11.18%  |
| 1.01-2.0    | 23        | 2.71%   |
| 24.01-32.0  | 17        | 2%      |
| 64.01-256.0 | 11        | 1.29%   |
| 2.01-3.0    | 9         | 1.06%   |
| 0.51-1.0    | 8         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 312       | 33.55%  |
| 2.01-3.0   | 230       | 24.73%  |
| 4.01-8.0   | 160       | 17.2%   |
| 3.01-4.0   | 112       | 12.04%  |
| 0.51-1.0   | 58        | 6.24%   |
| 8.01-16.0  | 42        | 4.52%   |
| 16.01-24.0 | 8         | 0.86%   |
| 0.01-0.5   | 5         | 0.54%   |
| 24.01-32.0 | 3         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 646       | 75.64%  |
| 2      | 169       | 19.79%  |
| 3      | 26        | 3.04%   |
| 0      | 8         | 0.94%   |
| 5      | 3         | 0.35%   |
| 4      | 2         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 553       | 66.23%  |
| Yes       | 282       | 33.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 681       | 81.17%  |
| No        | 158       | 18.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 819       | 98.44%  |
| No        | 13        | 1.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 664       | 78.39%  |
| No        | 183       | 21.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Switzerland | 832       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Zurich        | 211       | 23.39%  |
| Bern          | 45        | 4.99%   |
| Geneva        | 37        | 4.1%    |
| Winterthur    | 20        | 2.22%   |
| Lucerne       | 16        | 1.77%   |
| Lausanne      | 16        | 1.77%   |
| Basel         | 16        | 1.77%   |
| Neuchatel     | 15        | 1.66%   |
| Lugano        | 10        | 1.11%   |
| Herrliberg    | 9         | 1%      |
| Thun          | 8         | 0.89%   |
| St. Gallen    | 8         | 0.89%   |
| Lyss          | 7         | 0.78%   |
| Wil           | 6         | 0.67%   |
| Wettingen     | 6         | 0.67%   |
| Munchenstein  | 6         | 0.67%   |
| Dietikon      | 6         | 0.67%   |
| Wohlen        | 5         | 0.55%   |
| Willisau      | 5         | 0.55%   |
| Sion          | 5         | 0.55%   |
| Grancy        | 5         | 0.55%   |
| Grabs         | 5         | 0.55%   |
| Gerlafingen   | 5         | 0.55%   |
| Chur          | 5         | 0.55%   |
| Bussigny      | 5         | 0.55%   |
| Biel/Bienne   | 5         | 0.55%   |
| Vernier       | 4         | 0.44%   |
| Onex          | 4         | 0.44%   |
| Munsingen     | 4         | 0.44%   |
| Morges        | 4         | 0.44%   |
| Gossau        | 4         | 0.44%   |
| Fribourg      | 4         | 0.44%   |
| Effretikon    | 4         | 0.44%   |
| Dubendorf     | 4         | 0.44%   |
| Baar          | 4         | 0.44%   |
| Zweidlen-Dorf | 3         | 0.33%   |
| Wettswil      | 3         | 0.33%   |
| Suhr          | 3         | 0.33%   |
| Solothurn     | 3         | 0.33%   |
| Schwarzenbach | 3         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 270       | 389    | 26.42%  |
| WDC                            | 104       | 138    | 10.18%  |
| Seagate                        | 95        | 115    | 9.3%    |
| Toshiba                        | 73        | 98     | 7.14%   |
| SanDisk                        | 65        | 78     | 6.36%   |
| Intel                          | 60        | 74     | 5.87%   |
| SK hynix                       | 49        | 61     | 4.79%   |
| Unknown                        | 47        | 65     | 4.6%    |
| Hitachi                        | 31        | 40     | 3.03%   |
| Crucial                        | 30        | 46     | 2.94%   |
| Micron Technology              | 24        | 30     | 2.35%   |
| Kingston                       | 20        | 34     | 1.96%   |
| HGST                           | 19        | 24     | 1.86%   |
| Apple                          | 18        | 21     | 1.76%   |
| LITEON                         | 15        | 20     | 1.47%   |
| LITEONIT                       | 8         | 9      | 0.78%   |
| OCZ                            | 7         | 7      | 0.68%   |
| Intenso                        | 7         | 7      | 0.68%   |
| Transcend                      | 6         | 9      | 0.59%   |
| KIOXIA                         | 6         | 7      | 0.59%   |
| Fujitsu                        | 6         | 9      | 0.59%   |
| A-DATA Technology              | 6         | 11     | 0.59%   |
| ASMT                           | 5         | 6      | 0.49%   |
| Phison Electronics             | 4         | 11     | 0.39%   |
| Corsair                        | 4         | 5      | 0.39%   |
| Silicon Motion                 | 3         | 4      | 0.29%   |
| Phison                         | 3         | 5      | 0.29%   |
| Lenovo                         | 3         | 3      | 0.29%   |
| JMicron Technology             | 3         | 3      | 0.29%   |
| SPCC                           | 2         | 2      | 0.2%    |
| Lite-On                        | 2         | 2      | 0.2%    |
| LaCie                          | 2         | 2      | 0.2%    |
| External                       | 2         | 2      | 0.2%    |
| USB3.0                         | 1         | 2      | 0.1%    |
| Unknown (CF)                   | 1         | 1      | 0.1%    |
| SSSTC                          | 1         | 1      | 0.1%    |
| Solid State Storage Technology | 1         | 2      | 0.1%    |
| SABRENT                        | 1         | 1      | 0.1%    |
| Realtek Semiconductor          | 1         | 1      | 0.1%    |
| PNY                            | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                            | 12        | 1.12%   |
| SK hynix NVMe SSD Drive 512GB                       | 11        | 1.03%   |
| Samsung SSD 850 EVO 500GB                           | 10        | 0.93%   |
| Unknown MMC Card  32GB                              | 9         | 0.84%   |
| Unknown MMC Card  128GB                             | 9         | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB                      | 9         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 9         | 0.84%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 9         | 0.84%   |
| Samsung NVMe SSD Drive 1024GB                       | 9         | 0.84%   |
| SanDisk NVMe SSD Drive 512GB                        | 8         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 7         | 0.65%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 0.65%   |
| Seagate ST1000LM048-2E7172 1TB                      | 7         | 0.65%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 0.65%   |
| Samsung SSD 860 EVO 250GB                           | 7         | 0.65%   |
| Samsung SSD 860 EVO 1TB                             | 7         | 0.65%   |
| Samsung NVMe SSD Drive 512GB                        | 7         | 0.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 7         | 0.65%   |
| Intel NVMe SSD Drive 512GB                          | 7         | 0.65%   |
| Crucial CT1000MX500SSD1 1TB                         | 7         | 0.65%   |
| Seagate ST2000LM015-2E8174 2TB                      | 6         | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB                      | 6         | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6         | 0.56%   |
| Samsung SSD 970 EVO 1TB                             | 6         | 0.56%   |
| Samsung SSD 850 EVO 250GB                           | 6         | 0.56%   |
| Samsung NVMe SSD Drive 2TB                          | 6         | 0.56%   |
| Unknown MMC Card  64GB                              | 5         | 0.47%   |
| Toshiba NVMe SSD Drive 512GB                        | 5         | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 0.47%   |
| Samsung NVMe SSD Drive 500GB                        | 5         | 0.47%   |
| Samsung NVMe SSD Drive 1TB                          | 5         | 0.47%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 5         | 0.47%   |
| Intel NVMe SSD Drive 1024GB                         | 5         | 0.47%   |
| Hitachi HTS547575A9E384 752GB                       | 5         | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 4         | 0.37%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 4         | 0.37%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 4         | 0.37%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 4         | 0.37%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                  | 4         | 0.37%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                | 4         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 92        | 112    | 36.95%  |
| WDC                 | 52        | 72     | 20.88%  |
| Toshiba             | 35        | 39     | 14.06%  |
| Hitachi             | 31        | 40     | 12.45%  |
| HGST                | 19        | 24     | 7.63%   |
| Fujitsu             | 6         | 9      | 2.41%   |
| Samsung Electronics | 3         | 3      | 1.2%    |
| ASMT                | 3         | 4      | 1.2%    |
| Unknown             | 2         | 2      | 0.8%    |
| USB3.0              | 1         | 2      | 0.4%    |
| Unknown (CF)        | 1         | 1      | 0.4%    |
| SABRENT             | 1         | 1      | 0.4%    |
| Intenso             | 1         | 1      | 0.4%    |
| HGST HTS            | 1         | 1      | 0.4%    |
| ASMedia             | 1         | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 133       | 169    | 34.82%  |
| SanDisk             | 41        | 50     | 10.73%  |
| Crucial             | 27        | 43     | 7.07%   |
| Intel               | 26        | 30     | 6.81%   |
| WDC                 | 21        | 26     | 5.5%    |
| LITEON              | 15        | 20     | 3.93%   |
| Micron Technology   | 14        | 19     | 3.66%   |
| Kingston            | 14        | 28     | 3.66%   |
| Apple               | 14        | 15     | 3.66%   |
| Toshiba             | 13        | 21     | 3.4%    |
| SK hynix            | 13        | 15     | 3.4%    |
| LITEONIT            | 8         | 9      | 2.09%   |
| OCZ                 | 7         | 7      | 1.83%   |
| Transcend           | 6         | 9      | 1.57%   |
| Intenso             | 6         | 6      | 1.57%   |
| Corsair             | 4         | 5      | 1.05%   |
| A-DATA Technology   | 4         | 7      | 1.05%   |
| JMicron Technology  | 2         | 2      | 0.52%   |
| SPCC                | 1         | 1      | 0.26%   |
| Seagate             | 1         | 1      | 0.26%   |
| PNY                 | 1         | 1      | 0.26%   |
| Plextor             | 1         | 1      | 0.26%   |
| Phison              | 1         | 3      | 0.26%   |
| ORICO               | 1         | 1      | 0.26%   |
| Mushkin             | 1         | 1      | 0.26%   |
| Kolink              | 1         | 1      | 0.26%   |
| KingSpec            | 1         | 1      | 0.26%   |
| KingDian            | 1         | 1      | 0.26%   |
| GOODRAM             | 1         | 2      | 0.26%   |
| China               | 1         | 1      | 0.26%   |
| BIWIN               | 1         | 1      | 0.26%   |
| ASMT                | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 353       | 498    | 35.95%  |
| NVMe    | 328       | 477    | 33.4%   |
| HDD     | 246       | 312    | 25.05%  |
| MMC     | 48        | 66     | 4.89%   |
| Unknown | 7         | 10     | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 517       | 776    | 55.59%  |
| NVMe | 327       | 476    | 35.16%  |
| MMC  | 48        | 66     | 5.16%   |
| SAS  | 38        | 45     | 4.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 387       | 541    | 65.37%  |
| 0.51-1.0   | 184       | 244    | 31.08%  |
| 1.01-2.0   | 16        | 20     | 2.7%    |
| 4.01-10.0  | 3         | 3      | 0.51%   |
| 3.01-4.0   | 2         | 2      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 224       | 25.31%  |
| 251-500        | 217       | 24.52%  |
| 501-1000       | 157       | 17.74%  |
| 1-20           | 70        | 7.91%   |
| 1001-2000      | 65        | 7.34%   |
| 51-100         | 53        | 5.99%   |
| Unknown        | 42        | 4.75%   |
| 21-50          | 33        | 3.73%   |
| 2001-3000      | 13        | 1.47%   |
| More than 3000 | 11        | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 366       | 39.74%  |
| 21-50     | 141       | 15.31%  |
| 101-250   | 128       | 13.9%   |
| 51-100    | 102       | 11.07%  |
| 251-500   | 78        | 8.47%   |
| 501-1000  | 44        | 4.78%   |
| Unknown   | 42        | 4.56%   |
| 1001-2000 | 17        | 1.85%   |
| 2001-3000 | 3         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                      | 2         | 2      | 4.76%   |
| Hitachi HTS545050B9A300 500GB                  | 2         | 2      | 4.76%   |
| WDC WD1600BEKT-60A25T1 160GB                   | 1         | 1      | 2.38%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 2.38%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 2.38%   |
| Toshiba MK1255GSX H 120GB                      | 1         | 1      | 2.38%   |
| SK hynix SC401 SATA 512GB SSD                  | 1         | 2      | 2.38%   |
| SK hynix SC210 mSATA 256GB SSD                 | 1         | 1      | 2.38%   |
| SK hynix HFS256GD9TNG-62A0A 256GB              | 1         | 1      | 2.38%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 1         | 1      | 2.38%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 2.38%   |
| Seagate ST9500420AS 500GB                      | 1         | 2      | 2.38%   |
| Seagate ST9250827AS 250GB                      | 1         | 1      | 2.38%   |
| Seagate ST9120822AS 120GB                      | 1         | 1      | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 2.38%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB            | 1         | 1      | 2.38%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD            | 1         | 1      | 2.38%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD            | 1         | 1      | 2.38%   |
| SanDisk SD7SB3Q256G1002 256GB SSD              | 1         | 2      | 2.38%   |
| Samsung Electronics SSD 870 EVO 500GB          | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 860 EVO M.2 1TB        | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 840 Series 120GB       | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 3      | 2.38%   |
| Samsung Electronics HM500JI 500GB              | 1         | 1      | 2.38%   |
| Micron Technology C300-MTFDDAC064MAG 64GB SSD  | 1         | 1      | 2.38%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.38%   |
| LITEONIT LAT-256M3S 256GB SSD                  | 1         | 1      | 2.38%   |
| Kingston SUV400S37240G 240GB SSD               | 1         | 1      | 2.38%   |
| Intenso SSD Sata III 256GB                     | 1         | 1      | 2.38%   |
| Intel SSDSCKKF256G8H 256GB                     | 1         | 1      | 2.38%   |
| Intel SSDSC2BF180A4L 180GB                     | 1         | 1      | 2.38%   |
| Intel SSDSC2BF180A4H 180GB                     | 1         | 1      | 2.38%   |
| Intel SSDPEKKW256G7 256GB                      | 1         | 1      | 2.38%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 2.38%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 2.38%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 2.38%   |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 2.38%   |
| Crucial CT512MX100SSD1 512GB                   | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 16.67%  |
| Toshiba             | 5         | 5      | 11.9%   |
| SK hynix            | 5         | 6      | 11.9%   |
| Samsung Electronics | 5         | 7      | 11.9%   |
| Intel               | 4         | 4      | 9.52%   |
| Hitachi             | 4         | 4      | 9.52%   |
| SanDisk             | 3         | 4      | 7.14%   |
| Micron Technology   | 2         | 2      | 4.76%   |
| HGST                | 2         | 2      | 4.76%   |
| WDC                 | 1         | 1      | 2.38%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| Kingston            | 1         | 1      | 2.38%   |
| Intenso             | 1         | 1      | 2.38%   |
| Crucial             | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 35%     |
| Toshiba             | 5         | 5      | 25%     |
| Hitachi             | 4         | 4      | 20%     |
| HGST                | 2         | 2      | 10%     |
| WDC                 | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 20        | 24     | 47.62%  |
| HDD  | 20        | 21     | 47.62%  |
| NVMe | 2         | 2      | 4.76%   |

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
| Detected | 487       | 790    | 54.6%   |
| Works    | 364       | 526    | 40.81%  |
| Malfunc  | 41        | 47     | 4.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 598       | 61.46%  |
| Samsung Electronics            | 147       | 15.11%  |
| AMD                            | 54        | 5.55%   |
| SanDisk                        | 53        | 5.45%   |
| SK hynix                       | 34        | 3.49%   |
| Toshiba America Info Systems   | 28        | 2.88%   |
| Micron Technology              | 11        | 1.13%   |
| Phison Electronics             | 7         | 0.72%   |
| Nvidia                         | 6         | 0.62%   |
| Kingston Technology Company    | 6         | 0.62%   |
| Marvell Technology Group       | 4         | 0.41%   |
| KIOXIA                         | 4         | 0.41%   |
| Silicon Motion                 | 3         | 0.31%   |
| Lite-On Technology             | 3         | 0.31%   |
| Lenovo                         | 3         | 0.31%   |
| Apple                          | 3         | 0.31%   |
| VIA Technologies               | 2         | 0.21%   |
| Solid State Storage Technology | 2         | 0.21%   |
| Micron/Crucial Technology      | 2         | 0.21%   |
| Realtek Semiconductor          | 1         | 0.1%    |
| Biwin Storage Technology       | 1         | 0.1%    |
| ADATA Technology               | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 84        | 8.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 77        | 7.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 74        | 7.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 49        | 4.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 47        | 4.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 42        | 4.03%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 40        | 3.84%   |
| Intel Volume Management Device NVMe RAID Controller                            | 37        | 3.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 28        | 2.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 26        | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 24        | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 20        | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 19        | 1.82%   |
| Samsung NVMe SSD Controller 980                                                | 19        | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 18        | 1.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 17        | 1.63%   |
| Intel SSD 660P Series                                                          | 17        | 1.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 15        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 15        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 15        | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 14        | 1.34%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 13        | 1.25%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 13        | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                          | 13        | 1.25%   |
| Intel Tiger Lake-LP SATA Controller                                            | 12        | 1.15%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 12        | 1.15%   |
| Micron Non-Volatile memory controller                                          | 11        | 1.06%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 11        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 1.06%   |
| SK hynix Non-Volatile memory controller                                        | 10        | 0.96%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 10        | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 10        | 0.96%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 8         | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 0.77%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 7         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 7         | 0.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 0.58%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 5         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 541       | 53.51%  |
| NVMe | 329       | 32.54%  |
| RAID | 89        | 8.8%    |
| IDE  | 52        | 5.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 742       | 89.18%  |
| AMD          | 88        | 10.58%  |
| CentaurHauls | 2         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 34        | 4.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 29        | 3.49%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 27        | 3.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 16        | 1.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 15        | 1.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz          | 14        | 1.68%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 14        | 1.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 14        | 1.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 1.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 11        | 1.32%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 10        | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz          | 10        | 1.2%    |
| Intel Core i5-5300U CPU @ 2.30GHz          | 10        | 1.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz          | 10        | 1.2%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 10        | 1.2%    |
| Intel Core i7-8650U CPU @ 1.90GHz          | 9         | 1.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 9         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 9         | 1.08%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 9         | 1.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 8         | 0.96%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 8         | 0.96%   |
| Intel Core i5-4200U CPU @ 1.60GHz          | 8         | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 8         | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 8         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 8         | 0.96%   |
| Intel Core i7-4510U CPU @ 2.00GHz          | 7         | 0.84%   |
| Intel Core i7-3610QM CPU @ 2.30GHz         | 7         | 0.84%   |
| Intel Core i7-2630QM CPU @ 2.00GHz         | 7         | 0.84%   |
| Intel Core i7 CPU M 620 @ 2.67GHz          | 7         | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 7         | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 7         | 0.84%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 7         | 0.84%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 6         | 0.72%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz         | 6         | 0.72%   |
| Intel Core i7-2620M CPU @ 2.70GHz          | 6         | 0.72%   |
| Intel Celeron N4000 CPU @ 1.10GHz          | 6         | 0.72%   |
| Intel 12th Gen Core i7-1260P               | 6         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 5         | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz          | 5         | 0.6%    |
| Intel Core i7-5600U CPU @ 2.60GHz          | 5         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 333       | 40.02%  |
| Intel Core i5           | 198       | 23.8%   |
| Other                   | 66        | 7.93%   |
| Intel Core 2 Duo        | 35        | 4.21%   |
| AMD Ryzen 7             | 26        | 3.13%   |
| Intel Celeron           | 24        | 2.88%   |
| Intel Core i3           | 20        | 2.4%    |
| Intel Pentium           | 19        | 2.28%   |
| AMD Ryzen 5             | 14        | 1.68%   |
| Intel Atom              | 13        | 1.56%   |
| AMD Ryzen 7 PRO         | 13        | 1.56%   |
| Intel Core 2            | 8         | 0.96%   |
| Intel Core i9           | 7         | 0.84%   |
| AMD E                   | 6         | 0.72%   |
| Intel Pentium Dual-Core | 5         | 0.6%    |
| Intel Xeon              | 3         | 0.36%   |
| Intel Pentium M         | 3         | 0.36%   |
| Intel Core M            | 3         | 0.36%   |
| AMD E1                  | 3         | 0.36%   |
| AMD A8                  | 3         | 0.36%   |
| Intel Pentium Silver    | 2         | 0.24%   |
| AMD Turion 64 X2 Mobile | 2         | 0.24%   |
| AMD Ryzen 9             | 2         | 0.24%   |
| AMD Ryzen 3             | 2         | 0.24%   |
| AMD Phenom II           | 2         | 0.24%   |
| AMD E2                  | 2         | 0.24%   |
| AMD C-50                | 2         | 0.24%   |
| AMD A4                  | 2         | 0.24%   |
| Intel Pentium Gold      | 1         | 0.12%   |
| Intel Pentium Dual      | 1         | 0.12%   |
| Intel Pentium 4         | 1         | 0.12%   |
| Intel Genuine           | 1         | 0.12%   |
| Intel Core m3           | 1         | 0.12%   |
| Intel Celeron Dual-Core | 1         | 0.12%   |
| CentaurHauls VIA Eden   | 1         | 0.12%   |
| CentaurHauls VIA C7     | 1         | 0.12%   |
| AMD Turion 64 Mobile    | 1         | 0.12%   |
| AMD Ryzen 5 PRO         | 1         | 0.12%   |
| AMD FX                  | 1         | 0.12%   |
| AMD C-60                | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 371       | 44.54%  |
| 4       | 324       | 38.9%   |
| 8       | 58        | 6.96%   |
| 6       | 53        | 6.36%   |
| 1       | 13        | 1.56%   |
| 12      | 6         | 0.72%   |
| 14      | 3         | 0.36%   |
| 10      | 3         | 0.36%   |
| 16      | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 832       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 680       | 81.53%  |
| 1       | 153       | 18.35%  |
| Unknown | 1         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 813       | 97.25%  |
| Unknown        | 17        | 2.03%   |
| 32-bit         | 6         | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 166       | 19.44%  |
| 0x306a9    | 66        | 7.73%   |
| 0x806ea    | 53        | 6.21%   |
| 0x206a7    | 51        | 5.97%   |
| 0x40651    | 47        | 5.5%    |
| 0x806ec    | 39        | 4.57%   |
| 0x806c1    | 36        | 4.22%   |
| 0x806e9    | 30        | 3.51%   |
| 0x906ea    | 29        | 3.4%    |
| 0x306d4    | 27        | 3.16%   |
| 0x1067a    | 23        | 2.69%   |
| 0x306c3    | 20        | 2.34%   |
| 0x20655    | 20        | 2.34%   |
| 0x406e3    | 16        | 1.87%   |
| 0x30678    | 14        | 1.64%   |
| 0xa0652    | 13        | 1.52%   |
| 0x806eb    | 13        | 1.52%   |
| 0x506e3    | 12        | 1.41%   |
| 0x0a50000c | 11        | 1.29%   |
| 0x906e9    | 9         | 1.05%   |
| 0x706e5    | 9         | 1.05%   |
| 0x20652    | 9         | 1.05%   |
| 0x10676    | 9         | 1.05%   |
| 0x08600103 | 9         | 1.05%   |
| 0x08600106 | 8         | 0.94%   |
| 0x906a3    | 7         | 0.82%   |
| 0x6fd      | 7         | 0.82%   |
| 0x706a1    | 6         | 0.7%    |
| 0x6f6      | 6         | 0.7%    |
| 0x406c4    | 6         | 0.7%    |
| 0x05000119 | 5         | 0.59%   |
| 0x806d1    | 4         | 0.47%   |
| 0x08108102 | 4         | 0.47%   |
| 0x05000029 | 4         | 0.47%   |
| 0xa0660    | 3         | 0.35%   |
| 0x906ed    | 3         | 0.35%   |
| 0x906a4    | 3         | 0.35%   |
| 0x106ca    | 3         | 0.35%   |
| 0x0a404102 | 3         | 0.35%   |
| 0x08608103 | 3         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 223       | 26.77%  |
| Haswell          | 82        | 9.84%   |
| IvyBridge        | 79        | 9.48%   |
| SandyBridge      | 60        | 7.2%    |
| TigerLake        | 44        | 5.28%   |
| Skylake          | 41        | 4.92%   |
| Penryn           | 36        | 4.32%   |
| Westmere         | 32        | 3.84%   |
| Broadwell        | 32        | 3.84%   |
| Silvermont       | 26        | 3.12%   |
| Zen 2            | 25        | 3%      |
| Unknown          | 20        | 2.4%    |
| CometLake        | 19        | 2.28%   |
| Core             | 17        | 2.04%   |
| IceLake          | 15        | 1.8%    |
| Zen 3            | 14        | 1.68%   |
| Bobcat           | 11        | 1.32%   |
| Alderlake Hybrid | 11        | 1.32%   |
| Goldmont plus    | 8         | 0.96%   |
| Zen+             | 6         | 0.72%   |
| K8 Hammer        | 4         | 0.48%   |
| Bonnell          | 4         | 0.48%   |
| P6               | 3         | 0.36%   |
| Jaguar           | 3         | 0.36%   |
| Excavator        | 3         | 0.36%   |
| Zen              | 2         | 0.24%   |
| Puma             | 2         | 0.24%   |
| Nehalem          | 2         | 0.24%   |
| K10 Llano        | 2         | 0.24%   |
| K10              | 2         | 0.24%   |
| Goldmont         | 2         | 0.24%   |
| Steamroller      | 1         | 0.12%   |
| Piledriver       | 1         | 0.12%   |
| NetBurst         | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 668       | 62.9%   |
| Nvidia           | 249       | 23.45%  |
| AMD              | 143       | 13.47%  |
| VIA Technologies | 2         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 6.68%   |
| Intel UHD Graphics 620                                                                   | 58        | 5.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 51        | 4.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 49        | 4.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 48        | 4.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 43        | 3.99%   |
| Intel HD Graphics 620                                                                    | 34        | 3.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 32        | 2.97%   |
| Intel HD Graphics 5500                                                                   | 28        | 2.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 2.32%   |
| AMD Renoir                                                                               | 25        | 2.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 2.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 1.48%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 1.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 1.11%   |
| Intel HD Graphics 630                                                                    | 11        | 1.02%   |
| Intel HD Graphics 530                                                                    | 11        | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 0.93%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 10        | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.83%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 9         | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 0.74%   |
| Intel Iris Plus Graphics G7                                                              | 8         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.65%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 7         | 0.65%   |
| AMD Lucienne                                                                             | 7         | 0.65%   |
| Nvidia GM108M [GeForce 840M]                                                             | 6         | 0.56%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 6         | 0.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 0.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 0.56%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 5         | 0.46%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 449       | 53.71%  |
| Intel + Nvidia | 192       | 22.97%  |
| 1 x AMD        | 102       | 12.2%   |
| 1 x Nvidia     | 49        | 5.86%   |
| Intel + AMD    | 28        | 3.35%   |
| AMD + Nvidia   | 8         | 0.96%   |
| 2 x AMD        | 4         | 0.48%   |
| 1 x VIA        | 2         | 0.24%   |
| Other          | 1         | 0.12%   |
| 2 x Nvidia     | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 702       | 83.87%  |
| Proprietary | 114       | 13.62%  |
| Unknown     | 21        | 2.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 528       | 62.04%  |
| 1.01-2.0   | 103       | 12.1%   |
| 0.01-0.5   | 85        | 9.99%   |
| 3.01-4.0   | 66        | 7.76%   |
| 0.51-1.0   | 43        | 5.05%   |
| 7.01-8.0   | 13        | 1.53%   |
| 5.01-6.0   | 8         | 0.94%   |
| 2.01-3.0   | 4         | 0.47%   |
| 8.01-16.0  | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 202       | 20.87%  |
| LG Display              | 167       | 17.25%  |
| Chimei Innolux          | 97        | 10.02%  |
| Samsung Electronics     | 85        | 8.78%   |
| BOE                     | 77        | 7.95%   |
| Sharp                   | 44        | 4.55%   |
| Lenovo                  | 34        | 3.51%   |
| Apple                   | 34        | 3.51%   |
| Dell                    | 30        | 3.1%    |
| Hewlett-Packard         | 22        | 2.27%   |
| Chi Mei Optoelectronics | 22        | 2.27%   |
| Acer                    | 19        | 1.96%   |
| Philips                 | 17        | 1.76%   |
| Goldstar                | 13        | 1.34%   |
| BenQ                    | 13        | 1.34%   |
| CSO                     | 12        | 1.24%   |
| InfoVision              | 10        | 1.03%   |
| PANDA                   | 6         | 0.62%   |
| Eizo                    | 6         | 0.62%   |
| Ancor Communications    | 6         | 0.62%   |
| Sony                    | 5         | 0.52%   |
| LG Philips              | 5         | 0.52%   |
| Toshiba                 | 4         | 0.41%   |
| JDI                     | 4         | 0.41%   |
| Iiyama                  | 4         | 0.41%   |
| Vestel Elektronik       | 3         | 0.31%   |
| HannStar                | 3         | 0.31%   |
| AOC                     | 3         | 0.31%   |
| Panasonic               | 2         | 0.21%   |
| LGD                     | 2         | 0.21%   |
| IBM                     | 2         | 0.21%   |
| ASUSTek Computer        | 2         | 0.21%   |
| ViewSonic               | 1         | 0.1%    |
| Valve                   | 1         | 0.1%    |
| Unknown                 | 1         | 0.1%    |
| Tianma XM               | 1         | 0.1%    |
| Nvidia                  | 1         | 0.1%    |
| MSI                     | 1         | 0.1%    |
| Matrox                  | 1         | 0.1%    |
| LPL                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 8         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 7         | 0.71%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 7         | 0.71%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 6         | 0.61%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 6         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 6         | 0.61%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO139E 1600x900 380x210mm 17.1-inch             | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 5         | 0.51%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 4         | 0.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 4         | 0.41%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 4         | 0.41%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 4         | 0.41%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch              | 4         | 0.41%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch              | 4         | 0.41%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 4         | 0.41%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 4         | 0.41%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                   | 4         | 0.41%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch              | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch           | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 4         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 4         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 4         | 0.41%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 4         | 0.41%   |
| BOE LCD Monitor BOE06EE 1920x1080 309x173mm 13.9-inch                     | 4         | 0.41%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO109B 3840x2160 382x214mm 17.2-inch            | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch            | 4         | 0.41%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch     | 3         | 0.3%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 3         | 0.3%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch     | 3         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 425       | 46.3%   |
| 1366x768 (WXGA)    | 135       | 14.71%  |
| 1600x900 (HD+)     | 75        | 8.17%   |
| 3840x2160 (4K)     | 62        | 6.75%   |
| 2560x1440 (QHD)    | 44        | 4.79%   |
| 1280x800 (WXGA)    | 34        | 3.7%    |
| 1920x1200 (WUXGA)  | 23        | 2.51%   |
| 1440x900 (WXGA+)   | 22        | 2.4%    |
| 1680x1050 (WSXGA+) | 14        | 1.53%   |
| 2880x1800          | 11        | 1.2%    |
| 2560x1600          | 11        | 1.2%    |
| 3440x1440          | 7         | 0.76%   |
| 3200x1800 (QHD+)   | 7         | 0.76%   |
| 1280x1024 (SXGA)   | 6         | 0.65%   |
| 3840x2400          | 5         | 0.54%   |
| 1024x600           | 5         | 0.54%   |
| 2560x1080          | 4         | 0.44%   |
| 3840x1600          | 3         | 0.33%   |
| 3000x2000          | 3         | 0.33%   |
| 2160x1440          | 3         | 0.33%   |
| 1600x1200          | 3         | 0.33%   |
| 3840x1100          | 2         | 0.22%   |
| 1360x768           | 2         | 0.22%   |
| 1024x768 (XGA)     | 2         | 0.22%   |
| 800x1280           | 1         | 0.11%   |
| 3840x1080          | 1         | 0.11%   |
| 3456x2160          | 1         | 0.11%   |
| 3286x1080          | 1         | 0.11%   |
| 3072x1920          | 1         | 0.11%   |
| 2560x1024          | 1         | 0.11%   |
| 2288x1287          | 1         | 0.11%   |
| 2048x1152          | 1         | 0.11%   |
| 1920x515           | 1         | 0.11%   |
| Unknown            | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 345       | 35.42%  |
| 13      | 135       | 13.86%  |
| 14      | 124       | 12.73%  |
| 17      | 101       | 10.37%  |
| 27      | 63        | 6.47%   |
| 12      | 43        | 4.41%   |
| 24      | 33        | 3.39%   |
| 23      | 16        | 1.64%   |
| 21      | 14        | 1.44%   |
| Unknown | 14        | 1.44%   |
| 34      | 11        | 1.13%   |
| 31      | 11        | 1.13%   |
| 11      | 10        | 1.03%   |
| 22      | 5         | 0.51%   |
| 84      | 4         | 0.41%   |
| 40      | 4         | 0.41%   |
| 32      | 4         | 0.41%   |
| 20      | 4         | 0.41%   |
| 16      | 4         | 0.41%   |
| 10      | 4         | 0.41%   |
| 37      | 3         | 0.31%   |
| 25      | 3         | 0.31%   |
| 19      | 3         | 0.31%   |
| 72      | 2         | 0.21%   |
| 54      | 2         | 0.21%   |
| 48      | 2         | 0.21%   |
| 46      | 2         | 0.21%   |
| 18      | 2         | 0.21%   |
| 142     | 1         | 0.1%    |
| 65      | 1         | 0.1%    |
| 55      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |
| 9       | 1         | 0.1%    |
| 7       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 521       | 53.99%  |
| 201-300        | 133       | 13.78%  |
| 351-400        | 111       | 11.5%   |
| 501-600        | 107       | 11.09%  |
| 401-500        | 25        | 2.59%   |
| 701-800        | 15        | 1.55%   |
| 601-700        | 15        | 1.55%   |
| Unknown        | 14        | 1.45%   |
| 1001-1500      | 8         | 0.83%   |
| 801-900        | 7         | 0.73%   |
| 1501-2000      | 6         | 0.62%   |
| More than 2000 | 1         | 0.1%    |
| 101-200        | 1         | 0.1%    |
| 1-100          | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 683       | 80.26%  |
| 16/10   | 116       | 13.63%  |
| 21/9    | 14        | 1.65%   |
| 3/2     | 10        | 1.18%   |
| Unknown | 10        | 1.18%   |
| 4/3     | 6         | 0.71%   |
| 5/4     | 5         | 0.59%   |
| 3.40    | 2         | 0.24%   |
| 32/9    | 1         | 0.12%   |
| 3.73    | 1         | 0.12%   |
| 2.50    | 1         | 0.12%   |
| 1.00    | 1         | 0.12%   |
| 0.67    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 342       | 35.15%  |
| 81-90          | 192       | 19.73%  |
| 121-130        | 88        | 9.04%   |
| 71-80          | 64        | 6.58%   |
| 301-350        | 64        | 6.58%   |
| 201-250        | 51        | 5.24%   |
| 61-70          | 43        | 4.42%   |
| 351-500        | 26        | 2.67%   |
| 251-300        | 19        | 1.95%   |
| Unknown        | 14        | 1.44%   |
| More than 1000 | 12        | 1.23%   |
| 51-60          | 12        | 1.23%   |
| 131-140        | 11        | 1.13%   |
| 501-1000       | 10        | 1.03%   |
| 151-200        | 8         | 0.82%   |
| 111-120        | 5         | 0.51%   |
| 41-50          | 4         | 0.41%   |
| 141-150        | 3         | 0.31%   |
| 91-100         | 3         | 0.31%   |
| 1-40           | 2         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 412       | 43.46%  |
| 101-120       | 217       | 22.89%  |
| 51-100        | 143       | 15.08%  |
| 161-240       | 95        | 10.02%  |
| More than 240 | 57        | 6.01%   |
| Unknown       | 14        | 1.48%   |
| 1-50          | 10        | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 662       | 77.25%  |
| 2     | 153       | 17.85%  |
| 0     | 22        | 2.57%   |
| 3     | 20        | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 541       | 41.02%  |
| Realtek Semiconductor             | 340       | 25.78%  |
| Qualcomm Atheros                  | 139       | 10.54%  |
| Broadcom                          | 84        | 6.37%   |
| Broadcom Limited                  | 24        | 1.82%   |
| Ralink                            | 21        | 1.59%   |
| Lenovo                            | 17        | 1.29%   |
| MediaTek                          | 14        | 1.06%   |
| Hewlett-Packard                   | 14        | 1.06%   |
| Sierra Wireless                   | 12        | 0.91%   |
| Marvell Technology Group          | 12        | 0.91%   |
| Dell                              | 12        | 0.91%   |
| ASIX Electronics                  | 11        | 0.83%   |
| Ericsson Business Mobile Networks | 10        | 0.76%   |
| Huawei Technologies               | 8         | 0.61%   |
| DisplayLink                       | 8         | 0.61%   |
| Samsung Electronics               | 5         | 0.38%   |
| Nvidia                            | 5         | 0.38%   |
| ASUSTek Computer                  | 5         | 0.38%   |
| Ralink Technology                 | 4         | 0.3%    |
| Qualcomm                          | 4         | 0.3%    |
| Fibocom                           | 4         | 0.3%    |
| Edimax Technology                 | 4         | 0.3%    |
| TP-Link                           | 3         | 0.23%   |
| NetGear                           | 2         | 0.15%   |
| Linksys                           | 2         | 0.15%   |
| D-Link                            | 2         | 0.15%   |
| Xiaomi                            | 1         | 0.08%   |
| Wilocity                          | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.08%   |
| Novatek Microelectronics          | 1         | 0.08%   |
| MosChip Semiconductor             | 1         | 0.08%   |
| JMicron Technology                | 1         | 0.08%   |
| Intersil                          | 1         | 0.08%   |
| HMD Global                        | 1         | 0.08%   |
| AVM                               | 1         | 0.08%   |
| Arduino SA                        | 1         | 0.08%   |
| Apple                             | 1         | 0.08%   |
| AMD                               | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 236       | 14.43%  |
| Intel Wireless 8265 / 8275                                        | 62        | 3.79%   |
| Intel Wi-Fi 6 AX200                                               | 62        | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 52        | 3.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 43        | 2.63%   |
| Intel Wireless 7260                                               | 41        | 2.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 35        | 2.14%   |
| Intel Wireless 7265                                               | 33        | 2.02%   |
| Intel Wi-Fi 6 AX201                                               | 33        | 2.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 26        | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 25        | 1.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 22        | 1.34%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 1.28%   |
| Intel Wireless 8260                                               | 20        | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19        | 1.16%   |
| Intel Centrino Ultimate-N 6300                                    | 18        | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 0.98%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 15        | 0.92%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.92%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 13        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 13        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 0.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 12        | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 11        | 0.67%   |
| Intel Wireless-AC 9260                                            | 11        | 0.67%   |
| Intel Centrino Advanced-N 6235                                    | 11        | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 11        | 0.67%   |
| Intel Wireless 3165                                               | 10        | 0.61%   |
| Intel Wireless 3160                                               | 10        | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 529       | 60.73%  |
| Qualcomm Atheros                  | 119       | 13.66%  |
| Broadcom                          | 62        | 7.12%   |
| Realtek Semiconductor             | 60        | 6.89%   |
| Ralink                            | 21        | 2.41%   |
| Broadcom Limited                  | 14        | 1.61%   |
| Sierra Wireless                   | 12        | 1.38%   |
| MediaTek                          | 12        | 1.38%   |
| Hewlett-Packard                   | 7         | 0.8%    |
| Dell                              | 6         | 0.69%   |
| ASUSTek Computer                  | 5         | 0.57%   |
| Ralink Technology                 | 4         | 0.46%   |
| Fibocom                           | 4         | 0.46%   |
| Edimax Technology                 | 4         | 0.46%   |
| Qualcomm                          | 3         | 0.34%   |
| TP-Link                           | 2         | 0.23%   |
| NetGear                           | 2         | 0.23%   |
| Wilocity                          | 1         | 0.11%   |
| Linksys                           | 1         | 0.11%   |
| Ericsson Business Mobile Networks | 1         | 0.11%   |
| D-Link                            | 1         | 0.11%   |
| AVM                               | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 62        | 7.07%   |
| Intel Wi-Fi 6 AX200                                                     | 62        | 7.07%   |
| Intel Wireless 7260                                                     | 41        | 4.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 35        | 3.99%   |
| Intel Wireless 7265                                                     | 33        | 3.76%   |
| Intel Wi-Fi 6 AX201                                                     | 33        | 3.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 2.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 25        | 2.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 22        | 2.51%   |
| Intel Wireless 8260                                                     | 20        | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 2.17%   |
| Intel Centrino Ultimate-N 6300                                          | 18        | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.48%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 1.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 12        | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 11        | 1.25%   |
| Intel Wireless-AC 9260                                                  | 11        | 1.25%   |
| Intel Centrino Advanced-N 6235                                          | 11        | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.25%   |
| Intel Wireless 3165                                                     | 10        | 1.14%   |
| Intel Wireless 3160                                                     | 10        | 1.14%   |
| Intel Centrino Advanced-N 6200                                          | 10        | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.8%    |
| HP lt4112 Gobi 4G Module Network Device                                 | 7         | 0.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 7         | 0.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 7         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 321       | 44.77%  |
| Intel                         | 231       | 32.22%  |
| Qualcomm Atheros              | 44        | 6.14%   |
| Broadcom                      | 37        | 5.16%   |
| Lenovo                        | 17        | 2.37%   |
| Marvell Technology Group      | 12        | 1.67%   |
| ASIX Electronics              | 11        | 1.53%   |
| Broadcom Limited              | 10        | 1.39%   |
| DisplayLink                   | 8         | 1.12%   |
| Samsung Electronics           | 5         | 0.7%    |
| Nvidia                        | 5         | 0.7%    |
| Huawei Technologies           | 3         | 0.42%   |
| MediaTek                      | 2         | 0.28%   |
| Xiaomi                        | 1         | 0.14%   |
| TP-Link                       | 1         | 0.14%   |
| Qualcomm                      | 1         | 0.14%   |
| OnePlus Technology (Shenzhen) | 1         | 0.14%   |
| MosChip Semiconductor         | 1         | 0.14%   |
| Linksys                       | 1         | 0.14%   |
| JMicron Technology            | 1         | 0.14%   |
| HMD Global                    | 1         | 0.14%   |
| Hewlett-Packard               | 1         | 0.14%   |
| D-Link                        | 1         | 0.14%   |
| Apple                         | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 236       | 32.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 52        | 7.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 43        | 5.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 5.52%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 2.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 2.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 2.35%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 2.21%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 2.07%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 2.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 1.93%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 1.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 1.38%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.97%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.97%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 7         | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.97%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 6         | 0.83%   |
| Lenovo ThinkPad Lan                                               | 6         | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.69%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.69%   |
| Intel Ethernet Connection (13) I219-V                             | 5         | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.69%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.55%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 4         | 0.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.41%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.41%   |
| Lenovo USB-C Dock Ethernet                                        | 3         | 0.41%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.41%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 3         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 819       | 53.46%  |
| Ethernet | 679       | 44.32%  |
| Modem    | 33        | 2.15%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 666       | 76.11%  |
| Ethernet | 209       | 23.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 601       | 72.24%  |
| 1     | 207       | 24.88%  |
| 3     | 14        | 1.68%   |
| 0     | 10        | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 685       | 80.49%  |
| Yes  | 166       | 19.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 385       | 57.63%  |
| Broadcom                        | 54        | 8.08%   |
| Qualcomm Atheros Communications | 36        | 5.39%   |
| Foxconn / Hon Hai               | 33        | 4.94%   |
| Realtek Semiconductor           | 31        | 4.64%   |
| Lite-On Technology              | 28        | 4.19%   |
| Apple                           | 26        | 3.89%   |
| IMC Networks                    | 15        | 2.25%   |
| Hewlett-Packard                 | 13        | 1.95%   |
| Dell                            | 11        | 1.65%   |
| Ralink                          | 9         | 1.35%   |
| Cambridge Silicon Radio         | 8         | 1.2%    |
| Toshiba                         | 3         | 0.45%   |
| Alps Electric                   | 3         | 0.45%   |
| Realtek                         | 2         | 0.3%    |
| Ralink Technology               | 2         | 0.3%    |
| Chicony Electronics             | 2         | 0.3%    |
| ASUSTek Computer                | 2         | 0.3%    |
| USI                             | 1         | 0.15%   |
| Taiyo Yuden                     | 1         | 0.15%   |
| Micro Star International        | 1         | 0.15%   |
| Fujitsu                         | 1         | 0.15%   |
| Foxconn International           | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 170       | 25.37%  |
| Intel Bluetooth Device                              | 78        | 11.64%  |
| Intel AX200 Bluetooth                               | 60        | 8.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 41        | 6.12%   |
| Realtek Bluetooth Radio                             | 20        | 2.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 2.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 2.54%   |
| Apple Bluetooth Host Controller                     | 17        | 2.54%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 2.09%   |
| Lite-On Bluetooth Device                            | 13        | 1.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 11        | 1.64%   |
| Foxconn / Hon Hai BCM20702A0                        | 11        | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 11        | 1.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 1.49%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 1.49%   |
| Ralink RT3290 Bluetooth                             | 9         | 1.34%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 1.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 1.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 0.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.9%    |
| IMC Networks Bluetooth Radio                        | 6         | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.9%    |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 0.75%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 5         | 0.75%   |
| Intel AX210 Bluetooth                               | 4         | 0.6%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.6%    |
| Lite-On Wireless_Device                             | 3         | 0.45%   |
| IMC Networks Wireless_Device                        | 3         | 0.45%   |
| IMC Networks Bluetooth Device                       | 3         | 0.45%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.45%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 0.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 3         | 0.45%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.45%   |
| Broadcom BCM2045 Bluetooth                          | 3         | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 728       | 70.27%  |
| Nvidia                   | 122       | 11.78%  |
| AMD                      | 110       | 10.62%  |
| Lenovo                   | 11        | 1.06%   |
| GN Netcom                | 10        | 0.97%   |
| Hewlett-Packard          | 8         | 0.77%   |
| Realtek Semiconductor    | 7         | 0.68%   |
| Plantronics              | 5         | 0.48%   |
| C-Media Electronics      | 5         | 0.48%   |
| Logitech                 | 4         | 0.39%   |
| VIA Technologies         | 2         | 0.19%   |
| SteelSeries ApS          | 2         | 0.19%   |
| RODE Microphones         | 2         | 0.19%   |
| Kingston Technology      | 2         | 0.19%   |
| Conexant Systems         | 2         | 0.19%   |
| BEHRINGER International  | 2         | 0.19%   |
| Tenx Technology          | 1         | 0.1%    |
| Other World Computing    | 1         | 0.1%    |
| Nordic Semiconductor ASA | 1         | 0.1%    |
| miniDSP                  | 1         | 0.1%    |
| Magic Control Technology | 1         | 0.1%    |
| JMTek                    | 1         | 0.1%    |
| Griffin Technology       | 1         | 0.1%    |
| freeVoice                | 1         | 0.1%    |
| Elite Silicon            | 1         | 0.1%    |
| Cambridge Silicon Radio  | 1         | 0.1%    |
| AudioQuest               | 1         | 0.1%    |
| Astro Gaming             | 1         | 0.1%    |
| Apple                    | 1         | 0.1%    |
| Afatech                  | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 124       | 10.16%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 86        | 7.04%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 56        | 4.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 53        | 4.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 52        | 4.26%   |
| Intel 8 Series HD Audio Controller                                                                | 52        | 4.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 49        | 4.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 44        | 3.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 41        | 3.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 38        | 3.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 2.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 32        | 2.62%   |
| Intel Broadwell-U Audio Controller                                                                | 32        | 2.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30        | 2.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 27        | 2.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 26        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24        | 1.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 1.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 1.23%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 13        | 1.06%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 1.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 0.9%    |
| AMD FCH Azalia Controller                                                                         | 11        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.66%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 0.66%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 0.57%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 7         | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 7         | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.57%   |
| Realtek Semiconductor USB Audio                                                                   | 6         | 0.49%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.49%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 6         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 188       | 33.81%  |
| SK hynix            | 141       | 25.36%  |
| Micron Technology   | 66        | 11.87%  |
| Kingston            | 54        | 9.71%   |
| Unknown             | 33        | 5.94%   |
| Crucial             | 18        | 3.24%   |
| Corsair             | 12        | 2.16%   |
| Elpida              | 11        | 1.98%   |
| A-DATA Technology   | 10        | 1.8%    |
| Ramaxel Technology  | 9         | 1.62%   |
| Unknown             | 5         | 0.9%    |
| Nanya Technology    | 4         | 0.72%   |
| G.Skill             | 2         | 0.36%   |
| Unknown (08AE)      | 1         | 0.18%   |
| OnBoard             | 1         | 0.18%   |
| ASint Technology    | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 2.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 1.84%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 1.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 10        | 1.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.17%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 1%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1%      |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1%      |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.83%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.83%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.83%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.83%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 5         | 0.83%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.83%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 5         | 0.83%   |
| Unknown                                                          | 5         | 0.83%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 4         | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.67%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.67%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.67%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 0.67%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.67%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.67%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 0.67%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 4         | 0.67%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 4         | 0.67%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 3         | 0.5%    |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.5%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.5%    |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s        | 3         | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.5%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.5%    |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 3         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 223       | 46.17%  |
| DDR3    | 171       | 35.4%   |
| LPDDR3  | 38        | 7.87%   |
| LPDDR4  | 21        | 4.35%   |
| DDR2    | 14        | 2.9%    |
| SDRAM   | 6         | 1.24%   |
| LPDDR5  | 3         | 0.62%   |
| DDR5    | 3         | 0.62%   |
| DDR     | 3         | 0.62%   |
| Unknown | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 415       | 86.28%  |
| Row Of Chips | 55        | 11.43%  |
| Chip         | 7         | 1.46%   |
| DIMM         | 2         | 0.42%   |
| Unknown      | 2         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 218       | 41.29%  |
| 4096  | 134       | 25.38%  |
| 16384 | 102       | 19.32%  |
| 2048  | 46        | 8.71%   |
| 32768 | 14        | 2.65%   |
| 1024  | 13        | 2.46%   |
| 512   | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 112       | 21.58%  |
| 2667    | 110       | 21.19%  |
| 3200    | 85        | 16.38%  |
| 2133    | 52        | 10.02%  |
| 1334    | 35        | 6.74%   |
| 2400    | 32        | 6.17%   |
| 1333    | 19        | 3.66%   |
| 1067    | 10        | 1.93%   |
| 4267    | 9         | 1.73%   |
| Unknown | 8         | 1.54%   |
| 667     | 7         | 1.35%   |
| 3266    | 6         | 1.16%   |
| 800     | 4         | 0.77%   |
| 8400    | 3         | 0.58%   |
| 6400    | 3         | 0.58%   |
| 4800    | 3         | 0.58%   |
| 4266    | 3         | 0.58%   |
| 2048    | 3         | 0.58%   |
| 1867    | 3         | 0.58%   |
| 4199    | 2         | 0.39%   |
| 3733    | 2         | 0.39%   |
| 1066    | 2         | 0.39%   |
| 975     | 2         | 0.39%   |
| 3000    | 1         | 0.19%   |
| 1639    | 1         | 0.19%   |
| 333     | 1         | 0.19%   |
| 266     | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 44.44%  |
| Samsung Electronics | 1         | 11.11%  |
| Prolific Technology | 1         | 11.11%  |
| Konica Minolta      | 1         | 11.11%  |
| Hewlett-Packard     | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series | 1         | 11.11%  |
| Prolific PL2305 Parallel Port  | 1         | 11.11%  |
| Konica Minolta Printer         | 1         | 11.11%  |
| HP Laserjet P1505              | 1         | 11.11%  |
| Canon PIXMA TS6250             | 1         | 11.11%  |
| Brother MFC Composite Device   | 1         | 11.11%  |
| Brother HL-3040CN series       | 1         | 11.11%  |
| Brother HL-2030 Laser Printer  | 1         | 11.11%  |
| Brother DCP-7055W              | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Seiko Epson       | 1         | 50%     |
| Canon Electronics | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 50%     |
| Canon P-150 Scanner                                     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 243       | 31.68%  |
| IMC Networks                           | 63        | 8.21%   |
| Acer                                   | 63        | 8.21%   |
| Microdia                               | 53        | 6.91%   |
| Realtek Semiconductor                  | 44        | 5.74%   |
| Sunplus Innovation Technology          | 37        | 4.82%   |
| Quanta                                 | 37        | 4.82%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 4.56%   |
| Lite-On Technology                     | 28        | 3.65%   |
| Apple                                  | 28        | 3.65%   |
| Suyin                                  | 27        | 3.52%   |
| Lenovo                                 | 16        | 2.09%   |
| Syntek                                 | 12        | 1.56%   |
| Ricoh                                  | 11        | 1.43%   |
| Logitech                               | 11        | 1.43%   |
| Luxvisions Innotech Limited            | 8         | 1.04%   |
| Alcor Micro                            | 8         | 1.04%   |
| Silicon Motion                         | 6         | 0.78%   |
| Samsung Electronics                    | 5         | 0.65%   |
| Primax Electronics                     | 5         | 0.65%   |
| Z-Star Microelectronics                | 3         | 0.39%   |
| ALi                                    | 3         | 0.39%   |
| Tripath Technology                     | 2         | 0.26%   |
| OmniVision Technologies                | 2         | 0.26%   |
| DigiTech                               | 2         | 0.26%   |
| Xiaomi                                 | 1         | 0.13%   |
| WCM_USB                                | 1         | 0.13%   |
| Tobii Technology AB                    | 1         | 0.13%   |
| Sonix Technology                       | 1         | 0.13%   |
| Pixart Imaging                         | 1         | 0.13%   |
| Novatek Microelectronics               | 1         | 0.13%   |
| Nikon                                  | 1         | 0.13%   |
| Mimaki Engineering                     | 1         | 0.13%   |
| Leap Motion                            | 1         | 0.13%   |
| Jieli Technology                       | 1         | 0.13%   |
| Importek                               | 1         | 0.13%   |
| Genesys Logic                          | 1         | 0.13%   |
| Generalplus Technology                 | 1         | 0.13%   |
| Foxconn / Hon Hai                      | 1         | 0.13%   |
| 8SSC20F27142V1SR22V24EV                | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 56        | 7.22%   |
| Microdia Integrated_Webcam_HD           | 31        | 3.99%   |
| Chicony HD WebCam                       | 30        | 3.87%   |
| IMC Networks Integrated Camera          | 24        | 3.09%   |
| Chicony HP HD Camera                    | 22        | 2.84%   |
| Realtek Integrated_Webcam_HD            | 17        | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam       | 15        | 1.93%   |
| Lite-On Integrated Camera               | 14        | 1.8%    |
| Acer Integrated Camera                  | 14        | 1.8%    |
| Chicony USB2.0 Camera                   | 13        | 1.68%   |
| Quanta HP HD Camera                     | 12        | 1.55%   |
| Sunplus HD WebCam                       | 11        | 1.42%   |
| Chicony HP Truevision HD                | 11        | 1.42%   |
| Acer Lenovo EasyCamera                  | 10        | 1.29%   |
| Sunplus Integrated_Webcam_HD            | 9         | 1.16%   |
| Microdia Integrated Webcam              | 8         | 1.03%   |
| Lite-On HP HD Camera                    | 8         | 1.03%   |
| Chicony Integrated Camera (1280x720@30) | 8         | 1.03%   |
| Suyin HP Truevision HD                  | 7         | 0.9%    |
| Lenovo Integrated Webcam                | 7         | 0.9%    |
| Chicony HD User Facing                  | 7         | 0.9%    |
| Apple FaceTime HD Camera                | 7         | 0.9%    |
| Apple Built-in iSight                   | 7         | 0.9%    |
| Syntek Lenovo EasyCamera                | 6         | 0.77%   |
| Quanta HD Webcam                        | 6         | 0.77%   |
| Lenovo Integrated Webcam [R5U877]       | 6         | 0.77%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 6         | 0.77%   |
| Chicony HP HD Webcam                    | 6         | 0.77%   |
| Chicony CNF9055 Toshiba Webcam          | 6         | 0.77%   |
| Apple iPhone 5/5C/5S/6/SE               | 6         | 0.77%   |
| Acer SunplusIT Integrated Camera        | 6         | 0.77%   |
| Acer BisonCam,NB Pro                    | 6         | 0.77%   |
| Samsung Galaxy A5 (MTP)                 | 5         | 0.64%   |
| Realtek USB2.0 HD UVC WebCam            | 5         | 0.64%   |
| Quanta HD User Facing                   | 5         | 0.64%   |
| Chicony TOSHIBA Web Camera - HD         | 5         | 0.64%   |
| Chicony HP Wide Vision HD Camera        | 5         | 0.64%   |
| Chicony HP TrueVision HD Camera         | 5         | 0.64%   |
| Chicony FJ Camera                       | 5         | 0.64%   |
| Acer ThinkPad Integrated Camera         | 5         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 102       | 39.38%  |
| Synaptics                  | 80        | 30.89%  |
| Shenzhen Goodix Technology | 21        | 8.11%   |
| Upek                       | 17        | 6.56%   |
| Elan Microelectronics      | 14        | 5.41%   |
| AuthenTec                  | 14        | 5.41%   |
| LighTuning Technology      | 9         | 3.47%   |
| STMicroelectronics         | 2         | 0.77%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 32        | 12.36%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 9.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 6.56%   |
| Unknown                                                                    | 14        | 5.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 5.02%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 4.63%   |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 4.25%   |
| Elan ELAN:ARM-M4                                                           | 10        | 3.86%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.47%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 3.47%   |
| Validity Sensors VFS491                                                    | 8         | 3.09%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 3.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 2.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 2.32%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.32%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 1.93%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 1.93%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.93%   |
| AuthenTec AES2810                                                          | 5         | 1.93%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.93%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.54%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.54%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.54%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 1.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.16%   |
| Synaptics  WBDI                                                            | 3         | 1.16%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 0.77%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.77%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.77%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.77%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.77%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.39%   |
| Synaptics WBDI Device                                                      | 1         | 0.39%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 36        | 39.56%  |
| Broadcom                  | 34        | 37.36%  |
| Upek                      | 9         | 9.89%   |
| O2 Micro                  | 3         | 3.3%    |
| Lenovo                    | 3         | 3.3%    |
| Yubico.com                | 2         | 2.2%    |
| OmniKey                   | 1         | 1.1%    |
| Gemalto (was Gemplus)     | 1         | 1.1%    |
| Clay Logic                | 1         | 1.1%    |
| Aladdin Knowledge Systems | 1         | 1.1%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 36        | 39.56%  |
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 13.19%  |
| Broadcom 5880                                                                | 10        | 10.99%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 9.89%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 7.69%   |
| Broadcom 58200                                                               | 5         | 5.49%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.3%    |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.3%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 2.2%    |
| OmniKey CardMan 4321                                                         | 1         | 1.1%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.1%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.1%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.1%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 430       | 50.23%  |
| 1     | 325       | 37.97%  |
| 2     | 84        | 9.81%   |
| 3     | 13        | 1.52%   |
| 7     | 2         | 0.23%   |
| 4     | 2         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 255       | 47.31%  |
| Chipcard                 | 79        | 14.66%  |
| Graphics card            | 74        | 13.73%  |
| Net/wireless             | 38        | 7.05%   |
| Multimedia controller    | 18        | 3.34%   |
| Bluetooth                | 15        | 2.78%   |
| Camera                   | 14        | 2.6%    |
| Communication controller | 11        | 2.04%   |
| Card reader              | 10        | 1.86%   |
| Storage                  | 6         | 1.11%   |
| Net/ethernet             | 6         | 1.11%   |
| Modem                    | 4         | 0.74%   |
| Sound                    | 3         | 0.56%   |
| Network                  | 2         | 0.37%   |
| Unassigned class         | 1         | 0.19%   |
| Storage/nvme             | 1         | 0.19%   |
| Flash memory             | 1         | 0.19%   |
| Dvb card                 | 1         | 0.19%   |


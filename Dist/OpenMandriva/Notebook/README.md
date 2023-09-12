OpenMandriva - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

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

Total: 7593

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | AO722                       | [ae49a1e9c0](https://linux-hardware.org/?probe=ae49a1e9c0) | Sep 07, 2023 |
| Lenovo        | V15-IGL 82C3                | [78ecb1b882](https://linux-hardware.org/?probe=78ecb1b882) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | [f3bdad3061](https://linux-hardware.org/?probe=f3bdad3061) | Sep 07, 2023 |
| Dell          | Latitude 5480               | [166d57f310](https://linux-hardware.org/?probe=166d57f310) | Sep 07, 2023 |
| Google        | Blooguard                   | [c9dec98f0f](https://linux-hardware.org/?probe=c9dec98f0f) | Sep 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [5254176a5a](https://linux-hardware.org/?probe=5254176a5a) | Sep 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7410c2416c](https://linux-hardware.org/?probe=7410c2416c) | Sep 07, 2023 |
| HP            | EliteBook 2740p             | [0bada236bc](https://linux-hardware.org/?probe=0bada236bc) | Sep 07, 2023 |
| Clevo         | M1100M                      | [399b796d9f](https://linux-hardware.org/?probe=399b796d9f) | Sep 06, 2023 |
| Acer          | Swift SF314-51              | [7e7c32364d](https://linux-hardware.org/?probe=7e7c32364d) | Sep 06, 2023 |
| MSI           | GE70 2PE                    | [19dddb0418](https://linux-hardware.org/?probe=19dddb0418) | Sep 06, 2023 |
| MSI           | Bravo 15 C7VF               | [72b288770a](https://linux-hardware.org/?probe=72b288770a) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| MSI           | GS60 2PC Ghost              | [0b971b067a](https://linux-hardware.org/?probe=0b971b067a) | Sep 06, 2023 |
| Lenovo        | IdeaPad Z360                | [1bb5ebf339](https://linux-hardware.org/?probe=1bb5ebf339) | Sep 06, 2023 |
| Google        | Pirika                      | [e05149e1de](https://linux-hardware.org/?probe=e05149e1de) | Sep 06, 2023 |
| Lenovo        | V110-15IAP 80TG             | [783815f79f](https://linux-hardware.org/?probe=783815f79f) | Sep 06, 2023 |
| HP            | Notebook                    | [ad9bafda30](https://linux-hardware.org/?probe=ad9bafda30) | Sep 06, 2023 |
| HP            | Pavilion dv4                | [0b01aaddd6](https://linux-hardware.org/?probe=0b01aaddd6) | Sep 06, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [dd18138503](https://linux-hardware.org/?probe=dd18138503) | Sep 06, 2023 |
| Purism        | Librem 15 v3                | [d3a66abc8b](https://linux-hardware.org/?probe=d3a66abc8b) | Sep 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | [cb8de94658](https://linux-hardware.org/?probe=cb8de94658) | Sep 05, 2023 |
| ASUSTek       | X751LD                      | [ed90b83cc0](https://linux-hardware.org/?probe=ed90b83cc0) | Sep 05, 2023 |
| HP            | Laptop 15s-eq2xxx           | [344c861540](https://linux-hardware.org/?probe=344c861540) | Sep 05, 2023 |
| ASUSTek       | UL80VT                      | [aec41416ac](https://linux-hardware.org/?probe=aec41416ac) | Sep 05, 2023 |
| Acer          | Aspire V3-572P              | [1b021435e8](https://linux-hardware.org/?probe=1b021435e8) | Sep 05, 2023 |
| Dell          | Inspiron 3482               | [078746577b](https://linux-hardware.org/?probe=078746577b) | Sep 05, 2023 |
| Toshiba       | Satellite C650              | [0b87bf5b4b](https://linux-hardware.org/?probe=0b87bf5b4b) | Sep 05, 2023 |
| Toshiba       | Satellite C850-1DZ          | [cf916c2f33](https://linux-hardware.org/?probe=cf916c2f33) | Sep 05, 2023 |
| HP            | mt40                        | [c3a4682e40](https://linux-hardware.org/?probe=c3a4682e40) | Sep 04, 2023 |
| HP            | Notebook                    | [3a7a5608af](https://linux-hardware.org/?probe=3a7a5608af) | Sep 04, 2023 |
| Dell          | Inspiron 5567               | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T470 20HD000RUS    | [f7250cb3ae](https://linux-hardware.org/?probe=f7250cb3ae) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [08e7b606c8](https://linux-hardware.org/?probe=08e7b606c8) | Sep 04, 2023 |
| ASUSTek       | N73SV                       | [1e0b979775](https://linux-hardware.org/?probe=1e0b979775) | Sep 04, 2023 |
| Lenovo        | ThinkPad SL510 28473QB      | [e1ff8baa87](https://linux-hardware.org/?probe=e1ff8baa87) | Sep 04, 2023 |
| Acer          | Aspire 4741                 | [2f2b673625](https://linux-hardware.org/?probe=2f2b673625) | Sep 04, 2023 |
| Dell          | Precision M4800             | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| Dell          | Vostro 5590                 | [24ee101fee](https://linux-hardware.org/?probe=24ee101fee) | Sep 04, 2023 |
| Acer          | Aspire A315-56              | [1f090fc4fd](https://linux-hardware.org/?probe=1f090fc4fd) | Sep 04, 2023 |
| ASUSTek       | K53TA                       | [b173b156f9](https://linux-hardware.org/?probe=b173b156f9) | Sep 04, 2023 |
| Apple         | MacBookPro11,1              | [d8efe50ca5](https://linux-hardware.org/?probe=d8efe50ca5) | Sep 04, 2023 |
| HP            | Laptop 17-by0xxx            | [7c149b5f95](https://linux-hardware.org/?probe=7c149b5f95) | Sep 04, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [b3e23f1718](https://linux-hardware.org/?probe=b3e23f1718) | Sep 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [02c4374b47](https://linux-hardware.org/?probe=02c4374b47) | Sep 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5f9e18ee26](https://linux-hardware.org/?probe=5f9e18ee26) | Sep 04, 2023 |
| HP            | ProBook 650 G2              | [64026d5e6d](https://linux-hardware.org/?probe=64026d5e6d) | Sep 04, 2023 |
| Lenovo        | V130-15IKB 81HN             | [760698ac8a](https://linux-hardware.org/?probe=760698ac8a) | Sep 04, 2023 |
| Dell          | Inspiron 3542               | [6046f9d74b](https://linux-hardware.org/?probe=6046f9d74b) | Sep 04, 2023 |
| Lenovo        | V15-ADA 82C7                | [85cc15f8ea](https://linux-hardware.org/?probe=85cc15f8ea) | Sep 04, 2023 |
| HP            | EliteBook 840 G1            | [318d03cfad](https://linux-hardware.org/?probe=318d03cfad) | Sep 04, 2023 |
| Gigabyte      | GB-BKi3A-7100               | [40c832efb9](https://linux-hardware.org/?probe=40c832efb9) | Sep 04, 2023 |
| ASUSTek       | X75A1                       | [d8be6d6952](https://linux-hardware.org/?probe=d8be6d6952) | Sep 04, 2023 |
| Compaq        | 430                         | [ac9fb09e14](https://linux-hardware.org/?probe=ac9fb09e14) | Sep 04, 2023 |
| AXIOO         | Mybook 14E                  | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| SLIMBOOK      | PROX14-AMD                  | [c2da44c04f](https://linux-hardware.org/?probe=c2da44c04f) | Sep 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [ee6914ebdf](https://linux-hardware.org/?probe=ee6914ebdf) | Sep 04, 2023 |
| ASUSTek       | N56JN                       | [eb9458de08](https://linux-hardware.org/?probe=eb9458de08) | Sep 04, 2023 |
| HP            | 1000                        | [59cd8d1250](https://linux-hardware.org/?probe=59cd8d1250) | Sep 04, 2023 |
| Sony          | VPCEB27FX                   | [268d3a14a7](https://linux-hardware.org/?probe=268d3a14a7) | Sep 04, 2023 |
| HP            | 247 G8 Notebook PC          | [74a7d9e304](https://linux-hardware.org/?probe=74a7d9e304) | Sep 04, 2023 |
| Chuwi         | GemiBook XPro               | [acf39c0e3f](https://linux-hardware.org/?probe=acf39c0e3f) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| Dell          | Latitude 5480               | [3a25585a10](https://linux-hardware.org/?probe=3a25585a10) | Sep 04, 2023 |
| HP            | EliteBook Revolve 810 G2    | [3f102b35e3](https://linux-hardware.org/?probe=3f102b35e3) | Sep 04, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [49d36f6acc](https://linux-hardware.org/?probe=49d36f6acc) | Sep 04, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8e29b0ae51](https://linux-hardware.org/?probe=8e29b0ae51) | Sep 04, 2023 |
| Lenovo        | ThinkPad T400 64758S4       | [efcb0a82e1](https://linux-hardware.org/?probe=efcb0a82e1) | Sep 04, 2023 |
| VIT           | P2400                       | [d8ea46cf44](https://linux-hardware.org/?probe=d8ea46cf44) | Sep 04, 2023 |
| Lenovo        | ThinkPad T430 2349MPS       | [183e5c528c](https://linux-hardware.org/?probe=183e5c528c) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK E734               | [1b89968327](https://linux-hardware.org/?probe=1b89968327) | Sep 03, 2023 |
| Acer          | Nitro AN515-57              | [95b036ac9a](https://linux-hardware.org/?probe=95b036ac9a) | Sep 03, 2023 |
| ALLDOCUBE     | i1402A                      | [d5d2c60681](https://linux-hardware.org/?probe=d5d2c60681) | Sep 03, 2023 |
| ASUSTek       | X555LJ                      | [c13b1a693d](https://linux-hardware.org/?probe=c13b1a693d) | Sep 03, 2023 |
| Acer          | Nitro AN515-41              | [8d55fa5be4](https://linux-hardware.org/?probe=8d55fa5be4) | Sep 03, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [f92734bf2b](https://linux-hardware.org/?probe=f92734bf2b) | Sep 03, 2023 |
| Toshiba       | Satellite C850              | [188a672b4d](https://linux-hardware.org/?probe=188a672b4d) | Sep 03, 2023 |
| Lenovo        | Z50-75 80EC                 | [12894bacfb](https://linux-hardware.org/?probe=12894bacfb) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [7b776b30bd](https://linux-hardware.org/?probe=7b776b30bd) | Sep 03, 2023 |
| Dell          | Latitude E6410              | [23f9814b2b](https://linux-hardware.org/?probe=23f9814b2b) | Sep 03, 2023 |
| Dell          | Studio 1735                 | [88cf1723e0](https://linux-hardware.org/?probe=88cf1723e0) | Sep 03, 2023 |
| Acer          | Aspire ES1-711              | [36b5fac615](https://linux-hardware.org/?probe=36b5fac615) | Sep 03, 2023 |
| MSI           | GF63 Thin 9SC               | [510641439b](https://linux-hardware.org/?probe=510641439b) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Acer          | Aspire 7745G                | [ce450a1a6e](https://linux-hardware.org/?probe=ce450a1a6e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T410 25188PG       | [603479bd64](https://linux-hardware.org/?probe=603479bd64) | Sep 03, 2023 |
| Lenovo        | G570 20079                  | [3e995d059e](https://linux-hardware.org/?probe=3e995d059e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T440 20B7S0RD00    | [af57fd1655](https://linux-hardware.org/?probe=af57fd1655) | Sep 03, 2023 |
| HP            | ENVY m6                     | [0a810c8663](https://linux-hardware.org/?probe=0a810c8663) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [d669a79662](https://linux-hardware.org/?probe=d669a79662) | Sep 03, 2023 |
| Acer          | Aspire A515-55              | [71305b0cca](https://linux-hardware.org/?probe=71305b0cca) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [2a900ea3bd](https://linux-hardware.org/?probe=2a900ea3bd) | Sep 03, 2023 |
| HP            | Laptop 15-bs0xx             | [9651a05c1d](https://linux-hardware.org/?probe=9651a05c1d) | Sep 03, 2023 |
| Acer          | Aspire 5741G                | [b49fa94760](https://linux-hardware.org/?probe=b49fa94760) | Sep 03, 2023 |
| Packard Be... | EasyNote TJ65               | [55bb236bde](https://linux-hardware.org/?probe=55bb236bde) | Sep 03, 2023 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [a785a4e9bb](https://linux-hardware.org/?probe=a785a4e9bb) | Sep 03, 2023 |
| Apple         | MacBookPro14,1              | [8e63bb873b](https://linux-hardware.org/?probe=8e63bb873b) | Sep 03, 2023 |
| Toshiba       | dynabook R73/J              | [c63c97e4a8](https://linux-hardware.org/?probe=c63c97e4a8) | Sep 03, 2023 |
| Google        | Lick                        | [11aec9d97c](https://linux-hardware.org/?probe=11aec9d97c) | Sep 03, 2023 |
| Acer          | Nitro AN515-52              | [45e892a632](https://linux-hardware.org/?probe=45e892a632) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| HP            | Laptop 14-fq0xxx            | [d68ec21cac](https://linux-hardware.org/?probe=d68ec21cac) | Sep 03, 2023 |
| Acer          | Aspire E5-471G              | [b1332205f3](https://linux-hardware.org/?probe=b1332205f3) | Sep 03, 2023 |
| HP            | ProBook 440 G7              | [2c90811519](https://linux-hardware.org/?probe=2c90811519) | Sep 03, 2023 |
| HP            | Laptop 15-rb0xx             | [0f08b5b0ad](https://linux-hardware.org/?probe=0f08b5b0ad) | Sep 03, 2023 |
| Acer          | Aspire A315-21              | [9c71da2165](https://linux-hardware.org/?probe=9c71da2165) | Sep 03, 2023 |
| Dell          | Inspiron 5559               | [b53be4cf36](https://linux-hardware.org/?probe=b53be4cf36) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1458b372fd](https://linux-hardware.org/?probe=1458b372fd) | Sep 03, 2023 |
| Dell          | Inspiron N4010              | [78f4fd9711](https://linux-hardware.org/?probe=78f4fd9711) | Sep 03, 2023 |
| Acer          | Aspire 5750                 | [2b257d37b3](https://linux-hardware.org/?probe=2b257d37b3) | Sep 03, 2023 |
| Chuwi         | GemiBook XPro               | [a76e69489c](https://linux-hardware.org/?probe=a76e69489c) | Sep 02, 2023 |
| Alienware     | m15 R3                      | [c2e00a5341](https://linux-hardware.org/?probe=c2e00a5341) | Sep 02, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Lenovo        | B590 20206                  | [3e11cfff1b](https://linux-hardware.org/?probe=3e11cfff1b) | Sep 02, 2023 |
| Lenovo        | ThinkPad A485 20MVS16C00    | [4d39e78f8f](https://linux-hardware.org/?probe=4d39e78f8f) | Sep 02, 2023 |
| HP            | EliteBook 850 G1            | [adacf1a54a](https://linux-hardware.org/?probe=adacf1a54a) | Sep 02, 2023 |
| Lenovo        | G565 20071                  | [289dd0308b](https://linux-hardware.org/?probe=289dd0308b) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [c5db2939ee](https://linux-hardware.org/?probe=c5db2939ee) | Sep 02, 2023 |
| Lenovo        | ThinkPad T460s 20F9003CU... | [8c94711a27](https://linux-hardware.org/?probe=8c94711a27) | Sep 02, 2023 |
| UMAX          | 13Wr                        | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| HP            | 250 G5 Notebook PC          | [66df65e0f0](https://linux-hardware.org/?probe=66df65e0f0) | Sep 02, 2023 |
| Acer          | TravelMate 8372             | [709e81e4a0](https://linux-hardware.org/?probe=709e81e4a0) | Sep 02, 2023 |
| Microtech     | ebookPro                    | [ce14e0ffeb](https://linux-hardware.org/?probe=ce14e0ffeb) | Sep 02, 2023 |
| Lenovo        | ThinkPad T540p 20BFCTO      | [6c4bd340bc](https://linux-hardware.org/?probe=6c4bd340bc) | Sep 02, 2023 |
| MSI           | MS-1688                     | [30cd2d6e9a](https://linux-hardware.org/?probe=30cd2d6e9a) | Sep 02, 2023 |
| HP            | Compaq Presario CQ61        | [0cd9e98276](https://linux-hardware.org/?probe=0cd9e98276) | Sep 02, 2023 |
| MSI           | GP70 2OD                    | [4bc109f9a0](https://linux-hardware.org/?probe=4bc109f9a0) | Sep 02, 2023 |
| HP            | 1000                        | [aedfad957a](https://linux-hardware.org/?probe=aedfad957a) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming FX505DU_TUF50... | [dd49edce58](https://linux-hardware.org/?probe=dd49edce58) | Sep 02, 2023 |
| Dell          | Inspiron 3585               | [a8bdd5bcca](https://linux-hardware.org/?probe=a8bdd5bcca) | Sep 02, 2023 |
| Samsung       | 500R5L/501R5L/500R5P        | [681c0ca0f9](https://linux-hardware.org/?probe=681c0ca0f9) | Sep 02, 2023 |
| Dell          | Latitude 2120               | [65eed61467](https://linux-hardware.org/?probe=65eed61467) | Sep 02, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [1c1b1adcc9](https://linux-hardware.org/?probe=1c1b1adcc9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Samsung       | 550XBE/350XBE               | [6953a7b5f2](https://linux-hardware.org/?probe=6953a7b5f2) | Sep 02, 2023 |
| Chuwi         | LapBook Pro                 | [4dd222efaa](https://linux-hardware.org/?probe=4dd222efaa) | Sep 01, 2023 |
| Lenovo        | G570 4334                   | [60c351e038](https://linux-hardware.org/?probe=60c351e038) | Sep 01, 2023 |
| Lenovo        | V145-15AST 81MT             | [741ffec692](https://linux-hardware.org/?probe=741ffec692) | Sep 01, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [f7e029febe](https://linux-hardware.org/?probe=f7e029febe) | Sep 01, 2023 |
| Lenovo        | G70-70 80HW                 | [f8ac18ebd1](https://linux-hardware.org/?probe=f8ac18ebd1) | Sep 01, 2023 |
| GPU Compan... | GWTC116-2                   | [455a21dde9](https://linux-hardware.org/?probe=455a21dde9) | Sep 01, 2023 |
| HP            | Laptop 17-bs0xx             | [c4727ff179](https://linux-hardware.org/?probe=c4727ff179) | Sep 01, 2023 |
| HP            | Pavilion g6                 | [0f0960322d](https://linux-hardware.org/?probe=0f0960322d) | Sep 01, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [28fc3470c8](https://linux-hardware.org/?probe=28fc3470c8) | Sep 01, 2023 |
| Medion        | A17                         | [31b4226638](https://linux-hardware.org/?probe=31b4226638) | Sep 01, 2023 |
| Dell          | Vostro 3590                 | [9a914c816e](https://linux-hardware.org/?probe=9a914c816e) | Sep 01, 2023 |
| Lenovo        | ThinkPad L450 20DSS1DT00    | [89ca82b3af](https://linux-hardware.org/?probe=89ca82b3af) | Sep 01, 2023 |
| Sony          | SVS1512DCXB                 | [b712723d6c](https://linux-hardware.org/?probe=b712723d6c) | Sep 01, 2023 |
| Lenovo        | ThinkPad X250 20CL001DGE    | [f6bc603569](https://linux-hardware.org/?probe=f6bc603569) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1f29e90c7f](https://linux-hardware.org/?probe=1f29e90c7f) | Sep 01, 2023 |
| ASUSTek       | K55VD                       | [3db7c113f4](https://linux-hardware.org/?probe=3db7c113f4) | Sep 01, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| Apple         | MacBookPro11,4              | [c833e40c97](https://linux-hardware.org/?probe=c833e40c97) | Sep 01, 2023 |
| HP            | Compaq 15                   | [2d0b51ccd5](https://linux-hardware.org/?probe=2d0b51ccd5) | Sep 01, 2023 |
| Packard Be... | EasyNote TE11HC             | [2a11f6be15](https://linux-hardware.org/?probe=2a11f6be15) | Sep 01, 2023 |
| HP            | EliteBook 8440p             | [2107ba0ad7](https://linux-hardware.org/?probe=2107ba0ad7) | Sep 01, 2023 |
| Acer          | Extensa 5635Z               | [da70c2acd8](https://linux-hardware.org/?probe=da70c2acd8) | Sep 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c37cbe9bd9](https://linux-hardware.org/?probe=c37cbe9bd9) | Sep 01, 2023 |
| Positivo      | Mobile                      | [3b32864073](https://linux-hardware.org/?probe=3b32864073) | Sep 01, 2023 |
| Acer          | TravelMate 5760G            | [1a0a1749fc](https://linux-hardware.org/?probe=1a0a1749fc) | Sep 01, 2023 |
| ASUSTek       | K53SD                       | [9a208331c5](https://linux-hardware.org/?probe=9a208331c5) | Sep 01, 2023 |
| ASUSTek       | UX305CA                     | [2220cac066](https://linux-hardware.org/?probe=2220cac066) | Sep 01, 2023 |
| Lenovo        | V15-IGL 82C3                | [4ab20a426a](https://linux-hardware.org/?probe=4ab20a426a) | Sep 01, 2023 |
| Lenovo        | IdeaPad Z370                | [5c21431c9d](https://linux-hardware.org/?probe=5c21431c9d) | Sep 01, 2023 |
| BGH           | C46G                        | [c56474510e](https://linux-hardware.org/?probe=c56474510e) | Sep 01, 2023 |
| Dell          | Inspiron 13-7353            | [021bbea0d4](https://linux-hardware.org/?probe=021bbea0d4) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| HP            | EliteBook 6930p             | [f40d8bbc73](https://linux-hardware.org/?probe=f40d8bbc73) | Sep 01, 2023 |
| Acer          | Aspire E5-571               | [04f5152e0c](https://linux-hardware.org/?probe=04f5152e0c) | Sep 01, 2023 |
| Lenovo        | ThinkPad X61 76753BJ        | [f90ed18892](https://linux-hardware.org/?probe=f90ed18892) | Sep 01, 2023 |
| Lenovo        | G550 2958                   | [033a5ccf76](https://linux-hardware.org/?probe=033a5ccf76) | Sep 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [499b5c3b2f](https://linux-hardware.org/?probe=499b5c3b2f) | Sep 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [0dbf80863b](https://linux-hardware.org/?probe=0dbf80863b) | Sep 01, 2023 |
| Apple         | MacBookPro11,4              | [406d9fd5fc](https://linux-hardware.org/?probe=406d9fd5fc) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [082d8a2ebf](https://linux-hardware.org/?probe=082d8a2ebf) | Sep 01, 2023 |
| Dell          | Latitude 3320               | [7c40b4eb0d](https://linux-hardware.org/?probe=7c40b4eb0d) | Sep 01, 2023 |
| ASUSTek       | K43SJ                       | [ab5c104bef](https://linux-hardware.org/?probe=ab5c104bef) | Aug 31, 2023 |
| ASUSTek       | S301LP                      | [d33b635602](https://linux-hardware.org/?probe=d33b635602) | Aug 31, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [a45654cfd8](https://linux-hardware.org/?probe=a45654cfd8) | Aug 31, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e5a1a106cb](https://linux-hardware.org/?probe=e5a1a106cb) | Aug 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5720a360fb](https://linux-hardware.org/?probe=5720a360fb) | Aug 31, 2023 |
| Acer          | Aspire A317-33              | [8e27446a62](https://linux-hardware.org/?probe=8e27446a62) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [064705b919](https://linux-hardware.org/?probe=064705b919) | Aug 31, 2023 |
| Lenovo        | Z50-70 20354                | [305133ce29](https://linux-hardware.org/?probe=305133ce29) | Aug 31, 2023 |
| Acer          | Extensa 5230                | [e4877c4cd7](https://linux-hardware.org/?probe=e4877c4cd7) | Aug 31, 2023 |
| Acer          | Aspire A315-58              | [ee8a1b4fb5](https://linux-hardware.org/?probe=ee8a1b4fb5) | Aug 31, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [a5847ee104](https://linux-hardware.org/?probe=a5847ee104) | Aug 31, 2023 |
| Medion        | Akoya E6239                 | [ec5460d846](https://linux-hardware.org/?probe=ec5460d846) | Aug 31, 2023 |
| Toshiba       | Satellite C50-B             | [9d05ea660f](https://linux-hardware.org/?probe=9d05ea660f) | Aug 31, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [76f095d7c2](https://linux-hardware.org/?probe=76f095d7c2) | Aug 31, 2023 |
| ASUSTek       | X75VC                       | [4a2115b7ae](https://linux-hardware.org/?probe=4a2115b7ae) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [6cd62bfac4](https://linux-hardware.org/?probe=6cd62bfac4) | Aug 31, 2023 |
| ASUSTek       | GL753VD                     | [649fb869a6](https://linux-hardware.org/?probe=649fb869a6) | Aug 31, 2023 |
| Dell          | Latitude 7390               | [3aaefe5b81](https://linux-hardware.org/?probe=3aaefe5b81) | Aug 31, 2023 |
| Dell          | System Inspiron N7110       | [c222da255e](https://linux-hardware.org/?probe=c222da255e) | Aug 31, 2023 |
| Acer          | Aspire 5755G                | [b938dc8500](https://linux-hardware.org/?probe=b938dc8500) | Aug 31, 2023 |
| Lenovo        | ThinkPad T480s 20L70025U... | [917664de79](https://linux-hardware.org/?probe=917664de79) | Aug 31, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [fab320d1d5](https://linux-hardware.org/?probe=fab320d1d5) | Aug 31, 2023 |
| HP            | Laptop 14-bs1xx             | [335b828114](https://linux-hardware.org/?probe=335b828114) | Aug 31, 2023 |
| HP            | EliteBook 2560p             | [1c5a7bba51](https://linux-hardware.org/?probe=1c5a7bba51) | Aug 31, 2023 |
| Dell          | Inspiron 15-3567            | [9e1df9ff88](https://linux-hardware.org/?probe=9e1df9ff88) | Aug 31, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [ba81140205](https://linux-hardware.org/?probe=ba81140205) | Aug 31, 2023 |
| Acer          | Aspire E1-571               | [62b0ee9c60](https://linux-hardware.org/?probe=62b0ee9c60) | Aug 31, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | [6af4b49ea2](https://linux-hardware.org/?probe=6af4b49ea2) | Aug 31, 2023 |
| HP            | EliteBook 8440p             | [48fe841736](https://linux-hardware.org/?probe=48fe841736) | Aug 30, 2023 |
| ASUSTek       | K53SV                       | [17802d53e7](https://linux-hardware.org/?probe=17802d53e7) | Aug 30, 2023 |
| Medion        | P7818                       | [b2e6745157](https://linux-hardware.org/?probe=b2e6745157) | Aug 30, 2023 |
| ASUSTek       | K501LX                      | [ca56f1b803](https://linux-hardware.org/?probe=ca56f1b803) | Aug 30, 2023 |
| HP            | EliteBook 8460p             | [3f2dec6262](https://linux-hardware.org/?probe=3f2dec6262) | Aug 30, 2023 |
| Lenovo        | G40-70 20369                | [f3cef329f6](https://linux-hardware.org/?probe=f3cef329f6) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470 20HES0ET0R    | [65d003a7a0](https://linux-hardware.org/?probe=65d003a7a0) | Aug 30, 2023 |
| Dell          | Latitude 3510               | [220b298103](https://linux-hardware.org/?probe=220b298103) | Aug 30, 2023 |
| HP            | ProBook 6360b               | [0dbff9ebb3](https://linux-hardware.org/?probe=0dbff9ebb3) | Aug 30, 2023 |
| Dell          | Inspiron 7520               | [f3e3f12f08](https://linux-hardware.org/?probe=f3e3f12f08) | Aug 30, 2023 |
| HUAWEI        | KLVF-XX                     | [747a685cc1](https://linux-hardware.org/?probe=747a685cc1) | Aug 30, 2023 |
| Acer          | Aspire E1-530               | [39c2df1a0b](https://linux-hardware.org/?probe=39c2df1a0b) | Aug 30, 2023 |
| Dell          | Inspiron 3585               | [02708536f4](https://linux-hardware.org/?probe=02708536f4) | Aug 30, 2023 |
| HP            | Laptop 15-db0xxx            | [76eb125a56](https://linux-hardware.org/?probe=76eb125a56) | Aug 30, 2023 |
| ASUSTek       | S500CA                      | [60d87bd79b](https://linux-hardware.org/?probe=60d87bd79b) | Aug 30, 2023 |
| Dell          | Inspiron 7548               | [6b6a2e7632](https://linux-hardware.org/?probe=6b6a2e7632) | Aug 30, 2023 |
| Dell          | Inspiron 16 7610            | [57c65a2bc8](https://linux-hardware.org/?probe=57c65a2bc8) | Aug 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a452d9eadf](https://linux-hardware.org/?probe=a452d9eadf) | Aug 30, 2023 |
| Lenovo        | V15-IGL 82C3                | [3a0999b4a7](https://linux-hardware.org/?probe=3a0999b4a7) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ef1b605965](https://linux-hardware.org/?probe=ef1b605965) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | [ac9c55fcb3](https://linux-hardware.org/?probe=ac9c55fcb3) | Aug 30, 2023 |
| Dell          | Inspiron 3576               | [f69425a68d](https://linux-hardware.org/?probe=f69425a68d) | Aug 30, 2023 |
| MSI           | GP72 7RDX                   | [071785ab97](https://linux-hardware.org/?probe=071785ab97) | Aug 30, 2023 |
| Lenovo        | ThinkPad X230 2325AJG       | [fa550a5ea1](https://linux-hardware.org/?probe=fa550a5ea1) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | [12b48399ac](https://linux-hardware.org/?probe=12b48399ac) | Aug 30, 2023 |
| Acer          | Nitro AN515-52              | [efee17a022](https://linux-hardware.org/?probe=efee17a022) | Aug 30, 2023 |
| Acer          | Swift SF314-52              | [4f6b648f42](https://linux-hardware.org/?probe=4f6b648f42) | Aug 30, 2023 |
| Dell          | Precision 7730              | [11c494a20e](https://linux-hardware.org/?probe=11c494a20e) | Aug 30, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [18f51f883e](https://linux-hardware.org/?probe=18f51f883e) | Aug 30, 2023 |
| Dell          | Latitude E6440              | [0b63ef8851](https://linux-hardware.org/?probe=0b63ef8851) | Aug 30, 2023 |
| Lenovo        | ThinkPad X200 7459BN8       | [38c0341384](https://linux-hardware.org/?probe=38c0341384) | Aug 30, 2023 |
| Alurin        | Go Notebook                 | [d07fd99df0](https://linux-hardware.org/?probe=d07fd99df0) | Aug 30, 2023 |
| MSI           | Katana GF76 11UC            | [dd25d90357](https://linux-hardware.org/?probe=dd25d90357) | Aug 30, 2023 |
| Chuwi         | CoreBook X                  | [c1a4e5d47f](https://linux-hardware.org/?probe=c1a4e5d47f) | Aug 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [44e7ba057b](https://linux-hardware.org/?probe=44e7ba057b) | Aug 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ded378b5da](https://linux-hardware.org/?probe=ded378b5da) | Aug 30, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [6f5bafed6c](https://linux-hardware.org/?probe=6f5bafed6c) | Aug 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | [dda651a1c4](https://linux-hardware.org/?probe=dda651a1c4) | Aug 30, 2023 |
| Acer          | TMP645-M                    | [17838ce9b0](https://linux-hardware.org/?probe=17838ce9b0) | Aug 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [958ecd81e5](https://linux-hardware.org/?probe=958ecd81e5) | Aug 30, 2023 |
| Apple         | MacBookPro11,1              | [b3caa97382](https://linux-hardware.org/?probe=b3caa97382) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [aa10544f35](https://linux-hardware.org/?probe=aa10544f35) | Aug 30, 2023 |
| Acer          | Aspire E1-572               | [77cdb6f4a4](https://linux-hardware.org/?probe=77cdb6f4a4) | Aug 30, 2023 |
| Dell          | Latitude 3350               | [4fa556a69f](https://linux-hardware.org/?probe=4fa556a69f) | Aug 30, 2023 |
| Dell          | Latitude 5290               | [0b4debc293](https://linux-hardware.org/?probe=0b4debc293) | Aug 30, 2023 |
| Apple         | MacBook4,1                  | [04424409ef](https://linux-hardware.org/?probe=04424409ef) | Aug 29, 2023 |
| Lenovo        | G500 20236                  | [93f309e8ad](https://linux-hardware.org/?probe=93f309e8ad) | Aug 29, 2023 |
| Acer          | Aspire 5720                 | [36403a156e](https://linux-hardware.org/?probe=36403a156e) | Aug 29, 2023 |
| Lenovo        | 3000 G410                   | [26c592ddd6](https://linux-hardware.org/?probe=26c592ddd6) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK S792               | [7547ab7e8e](https://linux-hardware.org/?probe=7547ab7e8e) | Aug 29, 2023 |
| HP            | Laptop 15s-eq1xxx           | [fe431ea565](https://linux-hardware.org/?probe=fe431ea565) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dc4910965c](https://linux-hardware.org/?probe=dc4910965c) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2a5afc6557](https://linux-hardware.org/?probe=2a5afc6557) | Aug 29, 2023 |
| Dell          | Latitude D630               | [d23ff7e118](https://linux-hardware.org/?probe=d23ff7e118) | Aug 29, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [9ed16c423b](https://linux-hardware.org/?probe=9ed16c423b) | Aug 29, 2023 |
| Dell          | Latitude 3190               | [7d8714663f](https://linux-hardware.org/?probe=7d8714663f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430 2349H86       | [6ed258911c](https://linux-hardware.org/?probe=6ed258911c) | Aug 29, 2023 |
| Toshiba       | PORTEGE Z930                | [b4acaedb21](https://linux-hardware.org/?probe=b4acaedb21) | Aug 29, 2023 |
| Dell          | Inspiron N4050              | [d354a59a67](https://linux-hardware.org/?probe=d354a59a67) | Aug 29, 2023 |
| System76      | Galago Pro                  | [31330746e6](https://linux-hardware.org/?probe=31330746e6) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z470                | [d3c372d869](https://linux-hardware.org/?probe=d3c372d869) | Aug 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [a5f9c0a211](https://linux-hardware.org/?probe=a5f9c0a211) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [338a8026f3](https://linux-hardware.org/?probe=338a8026f3) | Aug 29, 2023 |
| Lenovo        | B50-30 80ES                 | [96aa7b5683](https://linux-hardware.org/?probe=96aa7b5683) | Aug 29, 2023 |
| Panasonic     | CF-54-2                     | [7d2f4f34c9](https://linux-hardware.org/?probe=7d2f4f34c9) | Aug 28, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [fd0950b7c1](https://linux-hardware.org/?probe=fd0950b7c1) | Aug 28, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [9071631c6d](https://linux-hardware.org/?probe=9071631c6d) | Aug 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [54930549e6](https://linux-hardware.org/?probe=54930549e6) | Aug 28, 2023 |
| HP            | ProBook 430 G4 NOTEBOOK ... | [6ee102c046](https://linux-hardware.org/?probe=6ee102c046) | Aug 28, 2023 |
| ASUSTek       | K53E                        | [fa5eab9e81](https://linux-hardware.org/?probe=fa5eab9e81) | Aug 28, 2023 |
| Acer          | Aspire 7560                 | [4cb158cafc](https://linux-hardware.org/?probe=4cb158cafc) | Aug 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V805    | [ec4b2fa095](https://linux-hardware.org/?probe=ec4b2fa095) | Aug 28, 2023 |
| Lenovo        | ThinkPad X201 36809D4       | [1e4311af0b](https://linux-hardware.org/?probe=1e4311af0b) | Aug 28, 2023 |
| Lenovo        | ThinkPad L512 259766G       | [4b92af4aba](https://linux-hardware.org/?probe=4b92af4aba) | Aug 28, 2023 |
| Acer          | Aspire V5-573G              | [1afaed6ffa](https://linux-hardware.org/?probe=1afaed6ffa) | Aug 28, 2023 |
| Dell          | Latitude 7480               | [12f61ffe4a](https://linux-hardware.org/?probe=12f61ffe4a) | Aug 28, 2023 |
| Dell          | Latitude 5580               | [eb2a994e98](https://linux-hardware.org/?probe=eb2a994e98) | Aug 28, 2023 |
| HP            | ProBook 6550b               | [2906ded48c](https://linux-hardware.org/?probe=2906ded48c) | Aug 28, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [94f2581f9f](https://linux-hardware.org/?probe=94f2581f9f) | Aug 28, 2023 |
| Acer          | Aspire 5741Z                | [2127326562](https://linux-hardware.org/?probe=2127326562) | Aug 28, 2023 |
| Acer          | Aspire 4738                 | [6051c9190a](https://linux-hardware.org/?probe=6051c9190a) | Aug 28, 2023 |
| Sony          | VPCEB43FG                   | [99812c6c56](https://linux-hardware.org/?probe=99812c6c56) | Aug 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [e02ef868a3](https://linux-hardware.org/?probe=e02ef868a3) | Aug 28, 2023 |
| Positivo      | C14CU51                     | [7fa280c987](https://linux-hardware.org/?probe=7fa280c987) | Aug 28, 2023 |
| Dell          | Latitude 7480               | [95f7cd5046](https://linux-hardware.org/?probe=95f7cd5046) | Aug 27, 2023 |
| Fujitsu       | FMVU14003                   | [8da3625e06](https://linux-hardware.org/?probe=8da3625e06) | Aug 27, 2023 |
| HP            | ProBook 4540s               | [a477892896](https://linux-hardware.org/?probe=a477892896) | Aug 27, 2023 |
| HP            | Laptop 15-db0xxx            | [2c0f5739a3](https://linux-hardware.org/?probe=2c0f5739a3) | Aug 27, 2023 |
| System76      | Gazelle                     | [83bc87f8fc](https://linux-hardware.org/?probe=83bc87f8fc) | Aug 27, 2023 |
| Toshiba       | Satellite C55-A             | [20dc6d4044](https://linux-hardware.org/?probe=20dc6d4044) | Aug 27, 2023 |
| Acer          | Aspire E5-774G              | [6e40336ff6](https://linux-hardware.org/?probe=6e40336ff6) | Aug 27, 2023 |
| Dell          | Latitude E6410              | [451d5477e5](https://linux-hardware.org/?probe=451d5477e5) | Aug 27, 2023 |
| Dell          | Latitude E6420              | [1e2c15f171](https://linux-hardware.org/?probe=1e2c15f171) | Aug 27, 2023 |
| ASUSTek       | UX31E                       | [0557e95830](https://linux-hardware.org/?probe=0557e95830) | Aug 27, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [79c52635ec](https://linux-hardware.org/?probe=79c52635ec) | Aug 27, 2023 |
| LG Electro... | A530-T.BE76P1               | [6b9ae23c76](https://linux-hardware.org/?probe=6b9ae23c76) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ded7284a37](https://linux-hardware.org/?probe=ded7284a37) | Aug 27, 2023 |
| Dell          | Inspiron 5570               | [0baf10cd76](https://linux-hardware.org/?probe=0baf10cd76) | Aug 27, 2023 |
| HP            | EliteBook 835 G7 Noteboo... | [fec29a37b2](https://linux-hardware.org/?probe=fec29a37b2) | Aug 27, 2023 |
| Dell          | XPS M1330                   | [ce3d41b222](https://linux-hardware.org/?probe=ce3d41b222) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6c54b2881a](https://linux-hardware.org/?probe=6c54b2881a) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [a284c141d8](https://linux-hardware.org/?probe=a284c141d8) | Aug 27, 2023 |
| Acer          | Aspire 4810T                | [4e72e77dc6](https://linux-hardware.org/?probe=4e72e77dc6) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [97caef0e98](https://linux-hardware.org/?probe=97caef0e98) | Aug 27, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4112e03a31](https://linux-hardware.org/?probe=4112e03a31) | Aug 27, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [cfbb311c97](https://linux-hardware.org/?probe=cfbb311c97) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [7566a0ed19](https://linux-hardware.org/?probe=7566a0ed19) | Aug 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [cc91bf6584](https://linux-hardware.org/?probe=cc91bf6584) | Aug 27, 2023 |
| ZOOSTORM      | 7200-9062A                  | [5ee843d3d1](https://linux-hardware.org/?probe=5ee843d3d1) | Aug 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | [8586d608af](https://linux-hardware.org/?probe=8586d608af) | Aug 26, 2023 |
| HP            | EliteBook 840 G3            | [25b5ca25b8](https://linux-hardware.org/?probe=25b5ca25b8) | Aug 26, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | [46a647db9b](https://linux-hardware.org/?probe=46a647db9b) | Aug 26, 2023 |
| Dell          | Precision M4600             | [fcc3763c08](https://linux-hardware.org/?probe=fcc3763c08) | Aug 26, 2023 |
| Dell          | Precision 7720              | [2281163932](https://linux-hardware.org/?probe=2281163932) | Aug 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [35fede08aa](https://linux-hardware.org/?probe=35fede08aa) | Aug 26, 2023 |
| Acer          | Aspire A515-45G             | [c0480c060a](https://linux-hardware.org/?probe=c0480c060a) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 25222AU       | [fdc78cf5a0](https://linux-hardware.org/?probe=fdc78cf5a0) | Aug 26, 2023 |
| ASUSTek       | UL80VT                      | [858a6c3ea1](https://linux-hardware.org/?probe=858a6c3ea1) | Aug 26, 2023 |
| VALE          | Notebook Classic C140       | [c5cae456b6](https://linux-hardware.org/?probe=c5cae456b6) | Aug 26, 2023 |
| Lenovo        | ThinkPad T530 2394D27       | [3dac98b5a5](https://linux-hardware.org/?probe=3dac98b5a5) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [2ee2c8dd6c](https://linux-hardware.org/?probe=2ee2c8dd6c) | Aug 26, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [01750cc1d8](https://linux-hardware.org/?probe=01750cc1d8) | Aug 26, 2023 |
| HP            | ProBook 430 G1              | [aa3b7fe20f](https://linux-hardware.org/?probe=aa3b7fe20f) | Aug 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [3c528e98c6](https://linux-hardware.org/?probe=3c528e98c6) | Aug 26, 2023 |
| Dell          | Inspiron 7375               | [32e62fd188](https://linux-hardware.org/?probe=32e62fd188) | Aug 26, 2023 |
| Unknown       | Unknown                     | [dc1c907cda](https://linux-hardware.org/?probe=dc1c907cda) | Aug 26, 2023 |
| ASUSTek       | UX330CAK                    | [35aa466ca4](https://linux-hardware.org/?probe=35aa466ca4) | Aug 26, 2023 |
| Lenovo        | IdeaPad Z480                | [e0989b8f9e](https://linux-hardware.org/?probe=e0989b8f9e) | Aug 25, 2023 |
| HP            | ProBook 440 G3              | [0f16274ad6](https://linux-hardware.org/?probe=0f16274ad6) | Aug 25, 2023 |
| HP            | EliteBook 850 G5            | [2d3a15b432](https://linux-hardware.org/?probe=2d3a15b432) | Aug 25, 2023 |
| Dell          | Latitude E6440              | [759a858fa1](https://linux-hardware.org/?probe=759a858fa1) | Aug 25, 2023 |
| Dell          | Latitude E6400              | [4526151015](https://linux-hardware.org/?probe=4526151015) | Aug 25, 2023 |
| HUAWEI        | RLEF-XX                     | [b5c86f44b7](https://linux-hardware.org/?probe=b5c86f44b7) | Aug 25, 2023 |
| Packard Be... | EasyNote TJ66               | [010fe56f65](https://linux-hardware.org/?probe=010fe56f65) | Aug 25, 2023 |
| HP            | Laptop 15-dy1xxx            | [03fbbf3d84](https://linux-hardware.org/?probe=03fbbf3d84) | Aug 25, 2023 |
| Dell          | Studio 1747                 | [e1fe0ee217](https://linux-hardware.org/?probe=e1fe0ee217) | Aug 25, 2023 |
| Dell          | Studio 1735                 | [5932ab2004](https://linux-hardware.org/?probe=5932ab2004) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7355715562](https://linux-hardware.org/?probe=7355715562) | Aug 25, 2023 |
| HP            | Laptop 15-db1xxx            | [2a72d00223](https://linux-hardware.org/?probe=2a72d00223) | Aug 25, 2023 |
| HP            | EliteBook 840 G3            | [d3c6faac81](https://linux-hardware.org/?probe=d3c6faac81) | Aug 25, 2023 |
| HP            | Laptop 17-by3xxx            | [081372c3c4](https://linux-hardware.org/?probe=081372c3c4) | Aug 25, 2023 |
| HP            | Laptop                      | [94fd1a7af2](https://linux-hardware.org/?probe=94fd1a7af2) | Aug 25, 2023 |
| ASUSTek       | K73SV                       | [7aca2d97c0](https://linux-hardware.org/?probe=7aca2d97c0) | Aug 25, 2023 |
| ASUSTek       | K54HR                       | [5f24b13b35](https://linux-hardware.org/?probe=5f24b13b35) | Aug 25, 2023 |
| HP            | Compaq Presario CQ60        | [b407522eb0](https://linux-hardware.org/?probe=b407522eb0) | Aug 25, 2023 |
| Star Labs     | Lite                        | [0d0821a7dd](https://linux-hardware.org/?probe=0d0821a7dd) | Aug 25, 2023 |
| Dell          | G5 5590                     | [c13a60889c](https://linux-hardware.org/?probe=c13a60889c) | Aug 25, 2023 |
| HUAWEI        | KPL-W0X                     | [0cb8d58c01](https://linux-hardware.org/?probe=0cb8d58c01) | Aug 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3f37fa5636](https://linux-hardware.org/?probe=3f37fa5636) | Aug 25, 2023 |
| Acer          | Aspire A315-23              | [34e1a0c5c4](https://linux-hardware.org/?probe=34e1a0c5c4) | Aug 24, 2023 |
| Toshiba       | PORTEGE R705                | [cae49b36a8](https://linux-hardware.org/?probe=cae49b36a8) | Aug 24, 2023 |
| Lenovo        | ThinkPad T450s 20BWS2M30... | [052c7eaa90](https://linux-hardware.org/?probe=052c7eaa90) | Aug 24, 2023 |
| Samsung       | 300E5M/300E5L               | [4d99c3a598](https://linux-hardware.org/?probe=4d99c3a598) | Aug 24, 2023 |
| Dell          | Inspiron 5379               | [df7d53dd55](https://linux-hardware.org/?probe=df7d53dd55) | Aug 24, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [2431197665](https://linux-hardware.org/?probe=2431197665) | Aug 24, 2023 |
| Dell          | Inspiron N5050              | [4d282e98b2](https://linux-hardware.org/?probe=4d282e98b2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T410 2537UT5       | [8c0f550b61](https://linux-hardware.org/?probe=8c0f550b61) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [097bbaf86a](https://linux-hardware.org/?probe=097bbaf86a) | Aug 24, 2023 |
| HP            | ProBook 450 G1              | [1bb6f8d738](https://linux-hardware.org/?probe=1bb6f8d738) | Aug 24, 2023 |
| HP            | Laptop 17-cn0xxx            | [5b5a4fa5d9](https://linux-hardware.org/?probe=5b5a4fa5d9) | Aug 23, 2023 |
| Thomson       | GENEO14C-4WH128             | [b145cbea54](https://linux-hardware.org/?probe=b145cbea54) | Aug 23, 2023 |
| ASUSTek       | X541SA                      | [109de7a1ae](https://linux-hardware.org/?probe=109de7a1ae) | Aug 23, 2023 |
| HP            | Pavilion 15                 | [0228bd6d42](https://linux-hardware.org/?probe=0228bd6d42) | Aug 23, 2023 |
| ASUSTek       | Q550LF                      | [f6531bb92a](https://linux-hardware.org/?probe=f6531bb92a) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | [d0f87a58ec](https://linux-hardware.org/?probe=d0f87a58ec) | Aug 23, 2023 |
| Dell          | Latitude 7480               | [50bcada7d4](https://linux-hardware.org/?probe=50bcada7d4) | Aug 23, 2023 |
| Positivo      | M7X0S Bottom                | [f78713080f](https://linux-hardware.org/?probe=f78713080f) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| Positivo      | C14CU51                     | [b8c9fbc7b7](https://linux-hardware.org/?probe=b8c9fbc7b7) | Aug 23, 2023 |
| Dell          | Latitude E5420              | [102bee1da1](https://linux-hardware.org/?probe=102bee1da1) | Aug 23, 2023 |
| Unknown       | Unknown                     | [176f1e45e9](https://linux-hardware.org/?probe=176f1e45e9) | Aug 22, 2023 |
| HP            | Compaq nc8430 (EM741AV)     | [02d656a746](https://linux-hardware.org/?probe=02d656a746) | Aug 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [be00a84105](https://linux-hardware.org/?probe=be00a84105) | Aug 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [65747a7530](https://linux-hardware.org/?probe=65747a7530) | Aug 22, 2023 |
| Chuwi         | GemiBook Pro                | [62b31c86bb](https://linux-hardware.org/?probe=62b31c86bb) | Aug 22, 2023 |
| MSI           | CR610M                      | [e2432b72a5](https://linux-hardware.org/?probe=e2432b72a5) | Aug 22, 2023 |
| Dell          | Inspiron 1720               | [577e8e228f](https://linux-hardware.org/?probe=577e8e228f) | Aug 22, 2023 |
| Acer          | Aspire ES1-512              | [cb2839d263](https://linux-hardware.org/?probe=cb2839d263) | Aug 22, 2023 |
| HP            | Presario CQ57               | [bfc59ff9cd](https://linux-hardware.org/?probe=bfc59ff9cd) | Aug 22, 2023 |
| HP            | Pavilion dv6                | [10badbd20d](https://linux-hardware.org/?probe=10badbd20d) | Aug 22, 2023 |
| Acer          | Aspire E5-553G              | [d5350f0d1c](https://linux-hardware.org/?probe=d5350f0d1c) | Aug 22, 2023 |
| Acer          | Aspire A315-23              | [9b3a3cd47b](https://linux-hardware.org/?probe=9b3a3cd47b) | Aug 22, 2023 |
| ASUSTek       | Z450UAK                     | [68fb2ce5ec](https://linux-hardware.org/?probe=68fb2ce5ec) | Aug 22, 2023 |
| Samsung       | 270E5J/2570EJ               | [04a07b8fa6](https://linux-hardware.org/?probe=04a07b8fa6) | Aug 22, 2023 |
| Lenovo        | ThinkPad T530 23945ZS       | [07f7243392](https://linux-hardware.org/?probe=07f7243392) | Aug 21, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [62cddb0954](https://linux-hardware.org/?probe=62cddb0954) | Aug 21, 2023 |
| HP            | EliteBook 2170p             | [0bba785aee](https://linux-hardware.org/?probe=0bba785aee) | Aug 21, 2023 |
| Toshiba       | dynabook B350/22A           | [80ad4cd1ff](https://linux-hardware.org/?probe=80ad4cd1ff) | Aug 21, 2023 |
| Clevo         | W240HU/W250HUQ              | [4590ebf626](https://linux-hardware.org/?probe=4590ebf626) | Aug 21, 2023 |
| Sony          | VPCEG15FB                   | [e3b2126509](https://linux-hardware.org/?probe=e3b2126509) | Aug 20, 2023 |
| Dell          | Latitude 7490               | [e28046c842](https://linux-hardware.org/?probe=e28046c842) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [97ed27473e](https://linux-hardware.org/?probe=97ed27473e) | Aug 20, 2023 |
| Acer          | Aspire A315-42              | [e84eba7c7d](https://linux-hardware.org/?probe=e84eba7c7d) | Aug 20, 2023 |
| eMachines     | E520 V1.06                  | [bd63874856](https://linux-hardware.org/?probe=bd63874856) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d355f1941a](https://linux-hardware.org/?probe=d355f1941a) | Aug 20, 2023 |
| Lenovo        | G50-80 80E5                 | [6d8baa3226](https://linux-hardware.org/?probe=6d8baa3226) | Aug 20, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [e5512efda4](https://linux-hardware.org/?probe=e5512efda4) | Aug 20, 2023 |
| HP            | 15 TouchSmart               | [d756b77e06](https://linux-hardware.org/?probe=d756b77e06) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [398280327e](https://linux-hardware.org/?probe=398280327e) | Aug 19, 2023 |
| Chuwi         | GemiBook                    | [64a2767d60](https://linux-hardware.org/?probe=64a2767d60) | Aug 19, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [f75baa8a07](https://linux-hardware.org/?probe=f75baa8a07) | Aug 19, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [344dab6e5e](https://linux-hardware.org/?probe=344dab6e5e) | Aug 19, 2023 |
| Dell          | Latitude E5520              | [35f02a2ea2](https://linux-hardware.org/?probe=35f02a2ea2) | Aug 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c19ed9405c](https://linux-hardware.org/?probe=c19ed9405c) | Aug 19, 2023 |
| Danew         | Dbook 131                   | [35ea124809](https://linux-hardware.org/?probe=35ea124809) | Aug 19, 2023 |
| HP            | G62                         | [778c1c04b9](https://linux-hardware.org/?probe=778c1c04b9) | Aug 19, 2023 |
| Apple         | MacBookAir6,2               | [76dda9cde6](https://linux-hardware.org/?probe=76dda9cde6) | Aug 19, 2023 |
| HP            | Pavilion g6                 | [8e7844a79d](https://linux-hardware.org/?probe=8e7844a79d) | Aug 19, 2023 |
| Lenovo        | ThinkPad X230 23253B3       | [8da8bfe394](https://linux-hardware.org/?probe=8da8bfe394) | Aug 18, 2023 |
| Acer          | Aspire A315-59              | [8946b925ea](https://linux-hardware.org/?probe=8946b925ea) | Aug 18, 2023 |
| Toshiba       | IS 1422                     | [2ad1bbf471](https://linux-hardware.org/?probe=2ad1bbf471) | Aug 18, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [b5e6b20270](https://linux-hardware.org/?probe=b5e6b20270) | Aug 18, 2023 |
| Dell          | Latitude E6500              | [5d1f16198a](https://linux-hardware.org/?probe=5d1f16198a) | Aug 18, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7add4465a9](https://linux-hardware.org/?probe=7add4465a9) | Aug 18, 2023 |
| Acer          | Aspire E1-421               | [bab5968f80](https://linux-hardware.org/?probe=bab5968f80) | Aug 18, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [41b00dc8b3](https://linux-hardware.org/?probe=41b00dc8b3) | Aug 18, 2023 |
| Lenovo        | ThinkPad T420 418063G       | [f8e7a666cc](https://linux-hardware.org/?probe=f8e7a666cc) | Aug 18, 2023 |
| Toshiba       | Satellite Pro C850-10N      | [590ac28f26](https://linux-hardware.org/?probe=590ac28f26) | Aug 18, 2023 |
| HP            | ProBook 450 G3              | [c156f586f5](https://linux-hardware.org/?probe=c156f586f5) | Aug 18, 2023 |
| Chuwi         | GemiBook XPro               | [41b34e60fd](https://linux-hardware.org/?probe=41b34e60fd) | Aug 18, 2023 |
| Panasonic     | CF-31AQAAA1M                | [64416dbba5](https://linux-hardware.org/?probe=64416dbba5) | Aug 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [7da49ac1c3](https://linux-hardware.org/?probe=7da49ac1c3) | Aug 17, 2023 |
| Apple         | MacBookPro9,2               | [4ea732e404](https://linux-hardware.org/?probe=4ea732e404) | Aug 17, 2023 |
| Sony          | VGN-NW2SRF_S                | [93a310f950](https://linux-hardware.org/?probe=93a310f950) | Aug 17, 2023 |
| Dell          | Inspiron 1545               | [29c2bc1929](https://linux-hardware.org/?probe=29c2bc1929) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [1f416788fa](https://linux-hardware.org/?probe=1f416788fa) | Aug 17, 2023 |
| Acer          | Aspire ES1-311              | [3fa65d407a](https://linux-hardware.org/?probe=3fa65d407a) | Aug 17, 2023 |
| Toshiba       | Satellite L670              | [915e37b55d](https://linux-hardware.org/?probe=915e37b55d) | Aug 17, 2023 |
| Dell          | Latitude E6520              | [15420bd102](https://linux-hardware.org/?probe=15420bd102) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [dbdb6ca163](https://linux-hardware.org/?probe=dbdb6ca163) | Aug 17, 2023 |
| Dell          | XPS 9320                    | [cb112d9f03](https://linux-hardware.org/?probe=cb112d9f03) | Aug 17, 2023 |
| GPU Compan... | GWTN141-1                   | [97416e9fda](https://linux-hardware.org/?probe=97416e9fda) | Aug 16, 2023 |
| HP            | Laptop 15s-fq5xxx           | [d3926b324c](https://linux-hardware.org/?probe=d3926b324c) | Aug 16, 2023 |
| Packard Be... | EasyNote TS11HR             | [fb77a4db86](https://linux-hardware.org/?probe=fb77a4db86) | Aug 16, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [080867b516](https://linux-hardware.org/?probe=080867b516) | Aug 16, 2023 |
| Dell          | Latitude E6430              | [87849c0e6c](https://linux-hardware.org/?probe=87849c0e6c) | Aug 16, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [6026ba6c8a](https://linux-hardware.org/?probe=6026ba6c8a) | Aug 16, 2023 |
| Lenovo        | ThinkPad T470 20HES07J00    | [32ec341753](https://linux-hardware.org/?probe=32ec341753) | Aug 16, 2023 |
| Toshiba       | Satellite L510              | [f06d068ca0](https://linux-hardware.org/?probe=f06d068ca0) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| HP            | Laptop 15s-eq1xxx           | [140af1f27b](https://linux-hardware.org/?probe=140af1f27b) | Aug 15, 2023 |
| Acer          | Aspire A315-21G             | [b74079b9cd](https://linux-hardware.org/?probe=b74079b9cd) | Aug 15, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | [8b4200849d](https://linux-hardware.org/?probe=8b4200849d) | Aug 15, 2023 |
| Packard Be... | EasyNote TSX66HR            | [f1b16023fd](https://linux-hardware.org/?probe=f1b16023fd) | Aug 15, 2023 |
| Dell          | Latitude E5470              | [f09173281d](https://linux-hardware.org/?probe=f09173281d) | Aug 15, 2023 |
| MSI           | GP62 6QF                    | [d9455cbed8](https://linux-hardware.org/?probe=d9455cbed8) | Aug 15, 2023 |
| Acer          | Aspire V5-573G              | [f53da0a40d](https://linux-hardware.org/?probe=f53da0a40d) | Aug 15, 2023 |
| Samsung       | 755XDA                      | [3be32e2365](https://linux-hardware.org/?probe=3be32e2365) | Aug 15, 2023 |
| HP            | EliteBook Folio 9470m       | [d7f0d8e9cd](https://linux-hardware.org/?probe=d7f0d8e9cd) | Aug 15, 2023 |
| ASUSTek       | X553MA                      | [b2ee5cedbe](https://linux-hardware.org/?probe=b2ee5cedbe) | Aug 14, 2023 |
| Acer          | Aspire 5742                 | [ebc3e37c86](https://linux-hardware.org/?probe=ebc3e37c86) | Aug 13, 2023 |
| Lenovo        | ThinkPad E595 20NF0006GE    | [c9c068e82b](https://linux-hardware.org/?probe=c9c068e82b) | Aug 13, 2023 |
| Packard Be... | EasyNote LE69KB             | [42772eba76](https://linux-hardware.org/?probe=42772eba76) | Aug 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [e934dcd506](https://linux-hardware.org/?probe=e934dcd506) | Aug 13, 2023 |
| Sony          | SVE1112M1EW                 | [353fb8c6ff](https://linux-hardware.org/?probe=353fb8c6ff) | Aug 13, 2023 |
| Samsung       | 960XFH                      | [b7f35fe8b5](https://linux-hardware.org/?probe=b7f35fe8b5) | Aug 13, 2023 |
| Dell          | Inspiron 1720               | [1cb123d894](https://linux-hardware.org/?probe=1cb123d894) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [67f821bd4d](https://linux-hardware.org/?probe=67f821bd4d) | Aug 12, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | [1b7c441369](https://linux-hardware.org/?probe=1b7c441369) | Aug 12, 2023 |
| Lenovo        | V310-14ISK 80SX             | [edd47d65b6](https://linux-hardware.org/?probe=edd47d65b6) | Aug 12, 2023 |
| Lenovo        | V130-15IKB 81HN             | [88a9c5764d](https://linux-hardware.org/?probe=88a9c5764d) | Aug 11, 2023 |
| Acer          | Aspire A515-51              | [4856b9b32f](https://linux-hardware.org/?probe=4856b9b32f) | Aug 11, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | [fad80ecff3](https://linux-hardware.org/?probe=fad80ecff3) | Aug 11, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | [171fd219cc](https://linux-hardware.org/?probe=171fd219cc) | Aug 10, 2023 |
| Google        | Kip                         | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | [6802a19338](https://linux-hardware.org/?probe=6802a19338) | Aug 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [2f64f3ee9a](https://linux-hardware.org/?probe=2f64f3ee9a) | Aug 10, 2023 |
| Acer          | Extensa 5630                | [1cc3eaf69a](https://linux-hardware.org/?probe=1cc3eaf69a) | Aug 10, 2023 |
| Chuwi         | GemiBook Pro                | [b5685bdafc](https://linux-hardware.org/?probe=b5685bdafc) | Aug 10, 2023 |
| HP            | EliteBook 8570p             | [73c1dd0c14](https://linux-hardware.org/?probe=73c1dd0c14) | Aug 10, 2023 |
| ASUSTek       | F3L                         | [b97c082eff](https://linux-hardware.org/?probe=b97c082eff) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290W35       | [64db00247d](https://linux-hardware.org/?probe=64db00247d) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290C37       | [125ac0cbd3](https://linux-hardware.org/?probe=125ac0cbd3) | Aug 08, 2023 |
| ASUSTek       | G750JW                      | [fe527d6231](https://linux-hardware.org/?probe=fe527d6231) | Aug 08, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [187ac2792a](https://linux-hardware.org/?probe=187ac2792a) | Aug 08, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [b00519fee7](https://linux-hardware.org/?probe=b00519fee7) | Aug 08, 2023 |
| HP            | Laptop 17-cn1xxx            | [711a5fc7ce](https://linux-hardware.org/?probe=711a5fc7ce) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | [e8524b0045](https://linux-hardware.org/?probe=e8524b0045) | Aug 08, 2023 |
| HP            | Laptop 14-dq3xxx            | [c547f01fbb](https://linux-hardware.org/?probe=c547f01fbb) | Aug 08, 2023 |
| Acer          | AO756                       | [1ea1658ac0](https://linux-hardware.org/?probe=1ea1658ac0) | Aug 07, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [a1b9b9fc2c](https://linux-hardware.org/?probe=a1b9b9fc2c) | Aug 07, 2023 |
| MSI           | GL72 7QF                    | [73f4a3b852](https://linux-hardware.org/?probe=73f4a3b852) | Aug 07, 2023 |
| Dell          | Inspiron 5770               | [d6a978f124](https://linux-hardware.org/?probe=d6a978f124) | Aug 07, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| Unknown       | Unknown                     | [691c44286e](https://linux-hardware.org/?probe=691c44286e) | Aug 06, 2023 |
| GPD           | G1618-03                    | [070d548515](https://linux-hardware.org/?probe=070d548515) | Aug 06, 2023 |
| Dell          | Inspiron N4050              | [af35c9ce49](https://linux-hardware.org/?probe=af35c9ce49) | Aug 05, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [b69ff09aa4](https://linux-hardware.org/?probe=b69ff09aa4) | Aug 05, 2023 |
| Dell          | Precision M2800             | [7d1afe9d42](https://linux-hardware.org/?probe=7d1afe9d42) | Aug 05, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | [9db6bfdcfa](https://linux-hardware.org/?probe=9db6bfdcfa) | Aug 05, 2023 |
| HP            | Pavilion g4                 | [2094186715](https://linux-hardware.org/?probe=2094186715) | Aug 05, 2023 |
| MSI           | GE70 0NC                    | [c9fd935b80](https://linux-hardware.org/?probe=c9fd935b80) | Aug 05, 2023 |
| Fujitsu       | LIFEBOOK LH532              | [ba3a2e1773](https://linux-hardware.org/?probe=ba3a2e1773) | Aug 04, 2023 |
| Acer          | Aspire 5738                 | [f5df04e0e6](https://linux-hardware.org/?probe=f5df04e0e6) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S9R500    | [3624b5e366](https://linux-hardware.org/?probe=3624b5e366) | Aug 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [e7810a04a9](https://linux-hardware.org/?probe=e7810a04a9) | Aug 04, 2023 |
| Acer          | Aspire 8943G                | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| GFAST         | N150                        | [bccc2874df](https://linux-hardware.org/?probe=bccc2874df) | Aug 04, 2023 |
| Acer          | Nitro AN517-54              | [aee5a21c76](https://linux-hardware.org/?probe=aee5a21c76) | Aug 04, 2023 |
| MSI           | Titan GT77HX 13VH           | [3acda608a1](https://linux-hardware.org/?probe=3acda608a1) | Aug 03, 2023 |
| HP            | ProBook 6540b               | [6ae3405ec5](https://linux-hardware.org/?probe=6ae3405ec5) | Aug 03, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [a3401e5a4b](https://linux-hardware.org/?probe=a3401e5a4b) | Aug 03, 2023 |
| Toshiba       | Satellite C855D             | [4835e837bd](https://linux-hardware.org/?probe=4835e837bd) | Aug 03, 2023 |
| Dell          | Latitude E6330              | [75d54a8988](https://linux-hardware.org/?probe=75d54a8988) | Aug 03, 2023 |
| TUXEDO        | Book XA15 / XA17 Gen10      | [18e29b97ac](https://linux-hardware.org/?probe=18e29b97ac) | Aug 02, 2023 |
| Toshiba       | Satellite C850-B239         | [a075f60c70](https://linux-hardware.org/?probe=a075f60c70) | Aug 02, 2023 |
| Dell          | Precision M4500             | [b425204301](https://linux-hardware.org/?probe=b425204301) | Aug 02, 2023 |
| Dell          | Inspiron 1545               | [97d2508df2](https://linux-hardware.org/?probe=97d2508df2) | Aug 02, 2023 |
| MSI           | Modern 15 A10M              | [bab451a11e](https://linux-hardware.org/?probe=bab451a11e) | Aug 02, 2023 |
| Dell          | Inspiron 13-5368            | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| Dell          | Vostro 3700                 | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| Chuwi         | GemiBook Pro                | [be8a59432a](https://linux-hardware.org/?probe=be8a59432a) | Aug 01, 2023 |
| Apple         | MacBookAir9,1               | [2e59618067](https://linux-hardware.org/?probe=2e59618067) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [483fbca861](https://linux-hardware.org/?probe=483fbca861) | Jul 31, 2023 |
| Dell          | Latitude E6430              | [9dcf92cce9](https://linux-hardware.org/?probe=9dcf92cce9) | Jul 31, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [7cb3479a69](https://linux-hardware.org/?probe=7cb3479a69) | Jul 31, 2023 |
| Dell          | Inspiron 5558               | [de55f350ab](https://linux-hardware.org/?probe=de55f350ab) | Jul 30, 2023 |
| Toshiba       | Satellite A135              | [2eddaa2a26](https://linux-hardware.org/?probe=2eddaa2a26) | Jul 30, 2023 |
| Chuwi         | HeroBook Pro                | [eb332b024d](https://linux-hardware.org/?probe=eb332b024d) | Jul 30, 2023 |
| Acer          | Aspire 5742                 | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| ASUSTek       | E200HA                      | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| ASUSTek       | X540NA                      | [68b0d7d1fb](https://linux-hardware.org/?probe=68b0d7d1fb) | Jul 30, 2023 |
| Chuwi         | GemiBook                    | [f892a3970c](https://linux-hardware.org/?probe=f892a3970c) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [5da413f349](https://linux-hardware.org/?probe=5da413f349) | Jul 30, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [22f4bc0b5e](https://linux-hardware.org/?probe=22f4bc0b5e) | Jul 29, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Acer          | Aspire E5-511               | [aef96d4eb8](https://linux-hardware.org/?probe=aef96d4eb8) | Jul 29, 2023 |
| ASUSTek       | UX31E                       | [a7b390cdf4](https://linux-hardware.org/?probe=a7b390cdf4) | Jul 29, 2023 |
| Dell          | Latitude E6420              | [a70852def5](https://linux-hardware.org/?probe=a70852def5) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470 20HES2C000    | [6cb5b31808](https://linux-hardware.org/?probe=6cb5b31808) | Jul 29, 2023 |
| ASUSTek       | X102BA                      | [488aa4c5b4](https://linux-hardware.org/?probe=488aa4c5b4) | Jul 29, 2023 |
| Acer          | Aspire 4810T                | [4d3abb525e](https://linux-hardware.org/?probe=4d3abb525e) | Jul 28, 2023 |
| HP            | g14                         | [39d4ce09a1](https://linux-hardware.org/?probe=39d4ce09a1) | Jul 28, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [49b28d270b](https://linux-hardware.org/?probe=49b28d270b) | Jul 27, 2023 |
| ASUSTek       | X550CC                      | [792e9db762](https://linux-hardware.org/?probe=792e9db762) | Jul 27, 2023 |
| Toshiba       | Satellite C50D-A-11G        | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| A14CR         | Unknown                     | [4ceb4f6761](https://linux-hardware.org/?probe=4ceb4f6761) | Jul 27, 2023 |
| MSI           | Alpha 15 B5EEK              | [d6a4c29101](https://linux-hardware.org/?probe=d6a4c29101) | Jul 27, 2023 |
| GPU Compan... | GWNR71517                   | [ca3906a6c7](https://linux-hardware.org/?probe=ca3906a6c7) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [c7b69782db](https://linux-hardware.org/?probe=c7b69782db) | Jul 26, 2023 |
| Lenovo        | ThinkPad E555 20DH0027UK    | [b7bf821032](https://linux-hardware.org/?probe=b7bf821032) | Jul 26, 2023 |
| Positivo      | G800                        | [5dd0f188f8](https://linux-hardware.org/?probe=5dd0f188f8) | Jul 25, 2023 |
| ASUSTek       | P50IJ                       | [d8aff1255a](https://linux-hardware.org/?probe=d8aff1255a) | Jul 25, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | [47d5775197](https://linux-hardware.org/?probe=47d5775197) | Jul 25, 2023 |
| Acer          | Extensa 2530                | [6691e96edf](https://linux-hardware.org/?probe=6691e96edf) | Jul 25, 2023 |
| Dell          | Latitude 5530               | [cccd0bf0b8](https://linux-hardware.org/?probe=cccd0bf0b8) | Jul 25, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [6fc7661aae](https://linux-hardware.org/?probe=6fc7661aae) | Jul 25, 2023 |
| Acer          | Aspire E5-571G              | [3f39162908](https://linux-hardware.org/?probe=3f39162908) | Jul 25, 2023 |
| Lenovo        | ThinkPad E480 20KN001QMX    | [1ff9753d17](https://linux-hardware.org/?probe=1ff9753d17) | Jul 25, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [1cf27b8466](https://linux-hardware.org/?probe=1cf27b8466) | Jul 25, 2023 |
| HP            | 250 G5 Notebook PC          | [007f2e5957](https://linux-hardware.org/?probe=007f2e5957) | Jul 25, 2023 |
| HP            | Laptop 15s-du3xxx           | [e14cb2c24e](https://linux-hardware.org/?probe=e14cb2c24e) | Jul 25, 2023 |
| Toshiba       | IS 1442                     | [3a66df4c2d](https://linux-hardware.org/?probe=3a66df4c2d) | Jul 25, 2023 |
| Acer          | Aspire A114-33              | [a8c1a06e1a](https://linux-hardware.org/?probe=a8c1a06e1a) | Jul 25, 2023 |
| Lenovo        | ThinkPad L560 20F2S32Q00    | [0f437b5e3c](https://linux-hardware.org/?probe=0f437b5e3c) | Jul 25, 2023 |
| Dell          | Latitude 7490               | [066e3b9518](https://linux-hardware.org/?probe=066e3b9518) | Jul 25, 2023 |
| Chuwi         | CoreBook Pro                | [21ab3832ea](https://linux-hardware.org/?probe=21ab3832ea) | Jul 24, 2023 |
| Apple         | MacBookPro13,3              | [ae23c3b0d3](https://linux-hardware.org/?probe=ae23c3b0d3) | Jul 24, 2023 |
| Intel         | powered classmate PC        | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| ASUSTek       | F7E                         | [2aef1cc2c4](https://linux-hardware.org/?probe=2aef1cc2c4) | Jul 24, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [78560cbf59](https://linux-hardware.org/?probe=78560cbf59) | Jul 24, 2023 |
| ASUSTek       | X555LD                      | [732fe69d59](https://linux-hardware.org/?probe=732fe69d59) | Jul 23, 2023 |
| Dell          | Inspiron 13-5378            | [7f6b8fc2db](https://linux-hardware.org/?probe=7f6b8fc2db) | Jul 23, 2023 |
| HP            | Laptop 17-ak0xx             | [e9b5ae3c4d](https://linux-hardware.org/?probe=e9b5ae3c4d) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [92c6b0de0c](https://linux-hardware.org/?probe=92c6b0de0c) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| Lenovo        | ThinkPad L460 20FVS01J00    | [96fe0142cd](https://linux-hardware.org/?probe=96fe0142cd) | Jul 23, 2023 |
| Dell          | Inspiron N5110              | [8d94c58c16](https://linux-hardware.org/?probe=8d94c58c16) | Jul 23, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [4824895fac](https://linux-hardware.org/?probe=4824895fac) | Jul 23, 2023 |
| Dell          | Latitude E7270              | [9d14027d6c](https://linux-hardware.org/?probe=9d14027d6c) | Jul 23, 2023 |
| HP            | Compaq Presario C700        | [71ca83faee](https://linux-hardware.org/?probe=71ca83faee) | Jul 23, 2023 |
| HP            | Notebook                    | [1a4ba0be2f](https://linux-hardware.org/?probe=1a4ba0be2f) | Jul 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S6FY01    | [deaede763c](https://linux-hardware.org/?probe=deaede763c) | Jul 23, 2023 |
| HP            | Pavilion dv2500             | [6e86c0a75b](https://linux-hardware.org/?probe=6e86c0a75b) | Jul 23, 2023 |
| Lenovo        | V145-15AST 81MT             | [ecce500445](https://linux-hardware.org/?probe=ecce500445) | Jul 22, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [d387ed9d0c](https://linux-hardware.org/?probe=d387ed9d0c) | Jul 22, 2023 |
| HP            | Laptop 17-by3xxx            | [b5fe1f6fca](https://linux-hardware.org/?probe=b5fe1f6fca) | Jul 22, 2023 |
| Lenovo        | ThinkPad T420 4180EP2       | [4ec1a5c6fe](https://linux-hardware.org/?probe=4ec1a5c6fe) | Jul 22, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [33ee51ddc5](https://linux-hardware.org/?probe=33ee51ddc5) | Jul 22, 2023 |
| Gigabyte      | AERO 15-X9                  | [2849a149b9](https://linux-hardware.org/?probe=2849a149b9) | Jul 22, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [a9af1efc27](https://linux-hardware.org/?probe=a9af1efc27) | Jul 22, 2023 |
| HP            | Pavilion dv6700             | [aed45c2e40](https://linux-hardware.org/?probe=aed45c2e40) | Jul 21, 2023 |
| Packard Be... | EasyNote SL65               | [f66a4415f3](https://linux-hardware.org/?probe=f66a4415f3) | Jul 21, 2023 |
| Standard      | Unknown                     | [74acf0f707](https://linux-hardware.org/?probe=74acf0f707) | Jul 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe0c696d47](https://linux-hardware.org/?probe=fe0c696d47) | Jul 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1400CDA... | [61837fa4da](https://linux-hardware.org/?probe=61837fa4da) | Jul 21, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [2269e1f3d7](https://linux-hardware.org/?probe=2269e1f3d7) | Jul 21, 2023 |
| ASUSTek       | UX303LB                     | [901f80bb60](https://linux-hardware.org/?probe=901f80bb60) | Jul 20, 2023 |
| HP            | ProBook 6540b               | [ec232bc3fa](https://linux-hardware.org/?probe=ec232bc3fa) | Jul 20, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [61fa9a2c91](https://linux-hardware.org/?probe=61fa9a2c91) | Jul 20, 2023 |
| Acer          | Aspire A515-56              | [3e0e8609c8](https://linux-hardware.org/?probe=3e0e8609c8) | Jul 19, 2023 |
| Dell          | Latitude E6400              | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Apple         | MacBookPro10,1              | [c3ec46f79e](https://linux-hardware.org/?probe=c3ec46f79e) | Jul 19, 2023 |
| Dell          | Inspiron N5110              | [140474e198](https://linux-hardware.org/?probe=140474e198) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7843df6b43](https://linux-hardware.org/?probe=7843df6b43) | Jul 19, 2023 |
| Lenovo        | ThinkPad T410 2537AT1       | [7d94a6effc](https://linux-hardware.org/?probe=7d94a6effc) | Jul 19, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | [afc31702be](https://linux-hardware.org/?probe=afc31702be) | Jul 18, 2023 |
| Acer          | Predator PH317-56           | [248af0e35c](https://linux-hardware.org/?probe=248af0e35c) | Jul 18, 2023 |
| LG Electro... | P420-G.BE42P1               | [9dea573574](https://linux-hardware.org/?probe=9dea573574) | Jul 18, 2023 |
| Fujitsu       | LIFEBOOK A557               | [96f08b7598](https://linux-hardware.org/?probe=96f08b7598) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 20RDS1G700     | [6ad3194fd9](https://linux-hardware.org/?probe=6ad3194fd9) | Jul 18, 2023 |
| Acer          | Nitro AN515-57              | [9853a8cf46](https://linux-hardware.org/?probe=9853a8cf46) | Jul 18, 2023 |
| ASUSTek       | K46CB                       | [144d523bf1](https://linux-hardware.org/?probe=144d523bf1) | Jul 18, 2023 |
| HP            | Pavilion Notebook           | [babb224527](https://linux-hardware.org/?probe=babb224527) | Jul 18, 2023 |
| HP            | G42                         | [d42b44461e](https://linux-hardware.org/?probe=d42b44461e) | Jul 18, 2023 |
| HP            | Pavilion Laptop 17-ar0xx    | [574cd2e0f8](https://linux-hardware.org/?probe=574cd2e0f8) | Jul 17, 2023 |
| ASUSTek       | G551JM                      | [393e57db0c](https://linux-hardware.org/?probe=393e57db0c) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | [6d453b900a](https://linux-hardware.org/?probe=6d453b900a) | Jul 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [afb16ac821](https://linux-hardware.org/?probe=afb16ac821) | Jul 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [e2075c4a1e](https://linux-hardware.org/?probe=e2075c4a1e) | Jul 17, 2023 |
| HP            | Laptop 14s-dk0xxx           | [3cf00d1f89](https://linux-hardware.org/?probe=3cf00d1f89) | Jul 16, 2023 |
| Acer          | Aspire E5-573G              | [3cc36162b8](https://linux-hardware.org/?probe=3cc36162b8) | Jul 16, 2023 |
| Toshiba       | TECRA A10                   | [0740ca470e](https://linux-hardware.org/?probe=0740ca470e) | Jul 16, 2023 |
| HP            | Pavilion HDX9200            | [d893c8a2d1](https://linux-hardware.org/?probe=d893c8a2d1) | Jul 16, 2023 |
| ASUSTek       | K53SJ                       | [eb5e64c657](https://linux-hardware.org/?probe=eb5e64c657) | Jul 16, 2023 |
| Acer          | Swift SFE16-43              | [ebdd4b753c](https://linux-hardware.org/?probe=ebdd4b753c) | Jul 16, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46cfd28279](https://linux-hardware.org/?probe=46cfd28279) | Jul 16, 2023 |
| Lenovo        | ThinkPad T495 20NKS0T101    | [6154504eac](https://linux-hardware.org/?probe=6154504eac) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| MSI           | GE70 2QD                    | [f8ddf3a3a3](https://linux-hardware.org/?probe=f8ddf3a3a3) | Jul 15, 2023 |
| Lenovo        | ThinkPad T400 6474C53       | [e9db1ea8a6](https://linux-hardware.org/?probe=e9db1ea8a6) | Jul 15, 2023 |
| Acer          | Aspire E5-773G              | [a4a4102548](https://linux-hardware.org/?probe=a4a4102548) | Jul 15, 2023 |
| Positivo      | Mobile                      | [fdc2d91a25](https://linux-hardware.org/?probe=fdc2d91a25) | Jul 15, 2023 |
| Dell          | Inspiron MP061              | [0a26ffe33b](https://linux-hardware.org/?probe=0a26ffe33b) | Jul 15, 2023 |
| Toshiba       | Satellite C650              | [252f8adf16](https://linux-hardware.org/?probe=252f8adf16) | Jul 15, 2023 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [804b227bff](https://linux-hardware.org/?probe=804b227bff) | Jul 15, 2023 |
| Packard Be... | EasyNote LM85               | [3efd87a0d8](https://linux-hardware.org/?probe=3efd87a0d8) | Jul 14, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | [4df76c784c](https://linux-hardware.org/?probe=4df76c784c) | Jul 13, 2023 |
| Dell          | Inspiron 1545               | [0e9916f3e3](https://linux-hardware.org/?probe=0e9916f3e3) | Jul 13, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | [be2db3ecfa](https://linux-hardware.org/?probe=be2db3ecfa) | Jul 13, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [6130474cb1](https://linux-hardware.org/?probe=6130474cb1) | Jul 13, 2023 |
| Acer          | Nitro AN515-45              | [2e11b53615](https://linux-hardware.org/?probe=2e11b53615) | Jul 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d2dd2ac514](https://linux-hardware.org/?probe=d2dd2ac514) | Jul 13, 2023 |
| Acer          | Aspire E5-471G              | [c958efdb37](https://linux-hardware.org/?probe=c958efdb37) | Jul 12, 2023 |
| Apple         | MacBookPro12,1              | [dd19bc7fee](https://linux-hardware.org/?probe=dd19bc7fee) | Jul 12, 2023 |
| Dell          | Inspiron 5748               | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Dell          | Inspiron 5749               | [0421d22945](https://linux-hardware.org/?probe=0421d22945) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [97f39991c3](https://linux-hardware.org/?probe=97f39991c3) | Jul 11, 2023 |
| Lenovo        | ThinkPad T430 23501B3       | [8f1d64206e](https://linux-hardware.org/?probe=8f1d64206e) | Jul 11, 2023 |
| Apple         | MacBookAir9,1               | [c952cab7d7](https://linux-hardware.org/?probe=c952cab7d7) | Jul 11, 2023 |
| Dell          | Inspiron 1545               | [50ed801045](https://linux-hardware.org/?probe=50ed801045) | Jul 11, 2023 |
| HP            | Pavilion dv6500             | [a714d595da](https://linux-hardware.org/?probe=a714d595da) | Jul 10, 2023 |
| Apple         | MacBookAir9,1               | [703f4fd012](https://linux-hardware.org/?probe=703f4fd012) | Jul 10, 2023 |
| GPU Compan... | GWNR71517                   | [9a58539b66](https://linux-hardware.org/?probe=9a58539b66) | Jul 10, 2023 |
| ASUSTek       | X756UXK                     | [746e141543](https://linux-hardware.org/?probe=746e141543) | Jul 10, 2023 |
| Dell          | Latitude 3490               | [67de502259](https://linux-hardware.org/?probe=67de502259) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96ca518dc6](https://linux-hardware.org/?probe=96ca518dc6) | Jul 09, 2023 |
| HP            | ProBook 4420s               | [51e917f03e](https://linux-hardware.org/?probe=51e917f03e) | Jul 09, 2023 |
| HP            | Laptop 17-cp0xxx            | [f17dc1d3c6](https://linux-hardware.org/?probe=f17dc1d3c6) | Jul 09, 2023 |
| Alienware     | 17                          | [90e6911a60](https://linux-hardware.org/?probe=90e6911a60) | Jul 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [c6a3712ec9](https://linux-hardware.org/?probe=c6a3712ec9) | Jul 09, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [c1da8fb79e](https://linux-hardware.org/?probe=c1da8fb79e) | Jul 08, 2023 |
| Lenovo        | V145-15AST 81MT             | [a29509646a](https://linux-hardware.org/?probe=a29509646a) | Jul 08, 2023 |
| Acer          | Swift SF514-51              | [74c43ecd5c](https://linux-hardware.org/?probe=74c43ecd5c) | Jul 08, 2023 |
| Acer          | Aspire A315-21              | [d6a3964ff7](https://linux-hardware.org/?probe=d6a3964ff7) | Jul 08, 2023 |
| Toshiba       | Satellite L755              | [cb309977d0](https://linux-hardware.org/?probe=cb309977d0) | Jul 08, 2023 |
| Acer          | TravelMate 5335             | [7422cf6091](https://linux-hardware.org/?probe=7422cf6091) | Jul 08, 2023 |
| HP            | EliteBook 2560p             | [df243ca59d](https://linux-hardware.org/?probe=df243ca59d) | Jul 08, 2023 |
| Acer          | Chapala                     | [6ea600326f](https://linux-hardware.org/?probe=6ea600326f) | Jul 08, 2023 |
| Dell          | Vostro 1720                 | [0bd2fdf8a5](https://linux-hardware.org/?probe=0bd2fdf8a5) | Jul 08, 2023 |
| Toshiba       | dynabook R73/Y              | [37e3897f65](https://linux-hardware.org/?probe=37e3897f65) | Jul 08, 2023 |
| Dell          | Latitude E5470              | [ac0f0dd893](https://linux-hardware.org/?probe=ac0f0dd893) | Jul 08, 2023 |
| Lenovo        | G485 20136                  | [9ce1d97d02](https://linux-hardware.org/?probe=9ce1d97d02) | Jul 07, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [0b81f2e9b0](https://linux-hardware.org/?probe=0b81f2e9b0) | Jul 07, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [de87cf7e95](https://linux-hardware.org/?probe=de87cf7e95) | Jul 07, 2023 |
| Samsung       | 300E5M/300E5L               | [f60025eb2c](https://linux-hardware.org/?probe=f60025eb2c) | Jul 07, 2023 |
| HP            | ZBook 17 G3                 | [e328019dd8](https://linux-hardware.org/?probe=e328019dd8) | Jul 07, 2023 |
| Medion        | Unknown                     | [8fd3bc8734](https://linux-hardware.org/?probe=8fd3bc8734) | Jul 07, 2023 |
| Lenovo        | ThinkPad T510 4349RK6       | [e25d3f6783](https://linux-hardware.org/?probe=e25d3f6783) | Jul 07, 2023 |
| HP            | ProBook 450 G4              | [803b679fbd](https://linux-hardware.org/?probe=803b679fbd) | Jul 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [e484073491](https://linux-hardware.org/?probe=e484073491) | Jul 07, 2023 |
| Google        | Lick                        | [aa3d137fcf](https://linux-hardware.org/?probe=aa3d137fcf) | Jul 07, 2023 |
| Dell          | Latitude E5450              | [0a1677c02e](https://linux-hardware.org/?probe=0a1677c02e) | Jul 06, 2023 |
| Toshiba       | Satellite P200D             | [609a275664](https://linux-hardware.org/?probe=609a275664) | Jul 06, 2023 |
| Lenovo        | ThinkPad T400 6474W7T       | [56144d66ac](https://linux-hardware.org/?probe=56144d66ac) | Jul 05, 2023 |
| Toshiba       | Satellite L750              | [037db5066a](https://linux-hardware.org/?probe=037db5066a) | Jul 05, 2023 |
| Sony          | VPCCW2S8E                   | [4a3af37e51](https://linux-hardware.org/?probe=4a3af37e51) | Jul 05, 2023 |
| HP            | EliteBook Folio 9480m       | [d992b0a60f](https://linux-hardware.org/?probe=d992b0a60f) | Jul 05, 2023 |
| HP            | 550                         | [f788d05211](https://linux-hardware.org/?probe=f788d05211) | Jul 05, 2023 |
| HP            | EliteBook 840 G2            | [ec4a293de1](https://linux-hardware.org/?probe=ec4a293de1) | Jul 05, 2023 |
| ASUSTek       | TP501UA                     | [ee28aacdd1](https://linux-hardware.org/?probe=ee28aacdd1) | Jul 05, 2023 |
| Packard Be... | IPOWER                      | [3c116708b4](https://linux-hardware.org/?probe=3c116708b4) | Jul 05, 2023 |
| GPU Compan... | GWNR71517                   | [27e3b5a172](https://linux-hardware.org/?probe=27e3b5a172) | Jul 05, 2023 |
| Standard      | ECT                         | [42f38309b9](https://linux-hardware.org/?probe=42f38309b9) | Jul 04, 2023 |
| Lenovo        | ThinkPad L520 5015A12       | [0cb85712d9](https://linux-hardware.org/?probe=0cb85712d9) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | [71de589577](https://linux-hardware.org/?probe=71de589577) | Jul 04, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [9ec1de725f](https://linux-hardware.org/?probe=9ec1de725f) | Jul 04, 2023 |
| eMachines     | Padus                       | [008b3a48cd](https://linux-hardware.org/?probe=008b3a48cd) | Jul 04, 2023 |
| Google        | Gnawty                      | [05c8ee74db](https://linux-hardware.org/?probe=05c8ee74db) | Jul 03, 2023 |
| ASUSTek       | 1015PN                      | [7482ea5fc2](https://linux-hardware.org/?probe=7482ea5fc2) | Jul 03, 2023 |
| ASUSTek       | K55VD                       | [1a3814f9d9](https://linux-hardware.org/?probe=1a3814f9d9) | Jul 03, 2023 |
| ASUSTek       | X541UAK                     | [c4dcbea71d](https://linux-hardware.org/?probe=c4dcbea71d) | Jul 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8420              | [c997fd76cf](https://linux-hardware.org/?probe=c997fd76cf) | Jul 02, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [4a3acc3b0d](https://linux-hardware.org/?probe=4a3acc3b0d) | Jul 02, 2023 |
| Dell          | Inspiron 5559               | [06988fc303](https://linux-hardware.org/?probe=06988fc303) | Jul 02, 2023 |
| Alienware     | 18                          | [7898671060](https://linux-hardware.org/?probe=7898671060) | Jul 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f78c4a1930](https://linux-hardware.org/?probe=f78c4a1930) | Jul 01, 2023 |
| Acer          | Predator PT515-51           | [fc639c945e](https://linux-hardware.org/?probe=fc639c945e) | Jul 01, 2023 |
| HP            | 550                         | [7681694808](https://linux-hardware.org/?probe=7681694808) | Jul 01, 2023 |
| ASUSTek       | UX31E                       | [37a73c8939](https://linux-hardware.org/?probe=37a73c8939) | Jul 01, 2023 |
| Acer          | JM11-MS                     | [ad02c854e0](https://linux-hardware.org/?probe=ad02c854e0) | Jul 01, 2023 |
| lapbook       | S15 PRO                     | [06ae615fd1](https://linux-hardware.org/?probe=06ae615fd1) | Jul 01, 2023 |
| Acer          | Aspire E5-772               | [b33f11c7c9](https://linux-hardware.org/?probe=b33f11c7c9) | Jul 01, 2023 |
| ASUSTek       | N752VX                      | [d4fd40a9f3](https://linux-hardware.org/?probe=d4fd40a9f3) | Jul 01, 2023 |
| Packard Be... | EasyNote TSX66HR            | [96253a3da8](https://linux-hardware.org/?probe=96253a3da8) | Jul 01, 2023 |
| Dell          | Inspiron 1545               | [cfcc86ddd5](https://linux-hardware.org/?probe=cfcc86ddd5) | Jun 30, 2023 |
| Acer          | Aspire A314-22              | [ef54ec3027](https://linux-hardware.org/?probe=ef54ec3027) | Jun 30, 2023 |
| Lenovo        | ThinkPad L430 246634S       | [5368d4410f](https://linux-hardware.org/?probe=5368d4410f) | Jun 30, 2023 |
| HP            | Laptop 15-db1xxx            | [6d3d6e002f](https://linux-hardware.org/?probe=6d3d6e002f) | Jun 30, 2023 |
| ASUSTek       | X555LAB                     | [99e1623ea0](https://linux-hardware.org/?probe=99e1623ea0) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| HP            | Notebook                    | [a178cbf707](https://linux-hardware.org/?probe=a178cbf707) | Jun 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a77c825995](https://linux-hardware.org/?probe=a77c825995) | Jun 29, 2023 |
| Dell          | System XPS L321X            | [abf6b8b341](https://linux-hardware.org/?probe=abf6b8b341) | Jun 29, 2023 |
| Acer          | Aspire 5830TG               | [8c001b69bb](https://linux-hardware.org/?probe=8c001b69bb) | Jun 29, 2023 |
| HP            | Pavilion dv6500             | [0286d2f5e5](https://linux-hardware.org/?probe=0286d2f5e5) | Jun 29, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [1db11a4fa9](https://linux-hardware.org/?probe=1db11a4fa9) | Jun 29, 2023 |
| Lenovo        | ThinkPad L520 50153CJ       | [1793064ee5](https://linux-hardware.org/?probe=1793064ee5) | Jun 29, 2023 |
| Acer          | Aspire A315-42              | [d2a1351f86](https://linux-hardware.org/?probe=d2a1351f86) | Jun 28, 2023 |
| ASUSTek       | K54C                        | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| PCsmart       | PCSGOB14p-C                 | [a45977461f](https://linux-hardware.org/?probe=a45977461f) | Jun 27, 2023 |
| Clevo         | M540SS Bottom               | [4b613733a0](https://linux-hardware.org/?probe=4b613733a0) | Jun 27, 2023 |
| Dell          | Inspiron 7720               | [89858274fd](https://linux-hardware.org/?probe=89858274fd) | Jun 27, 2023 |
| Dell          | Inspiron 1545               | [d6b3d5cb90](https://linux-hardware.org/?probe=d6b3d5cb90) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [501d3b5530](https://linux-hardware.org/?probe=501d3b5530) | Jun 25, 2023 |
| HP            | Laptop 15-dw3xxx            | [a80704a116](https://linux-hardware.org/?probe=a80704a116) | Jun 25, 2023 |
| ASUSTek       | M51Vr                       | [16404e70f6](https://linux-hardware.org/?probe=16404e70f6) | Jun 25, 2023 |
| Toshiba       | Satellite A300              | [6f1d7a6089](https://linux-hardware.org/?probe=6f1d7a6089) | Jun 25, 2023 |
| Dell          | Precision M6400             | [b68c09e274](https://linux-hardware.org/?probe=b68c09e274) | Jun 25, 2023 |
| HP            | Pavilion dv6                | [d699670acc](https://linux-hardware.org/?probe=d699670acc) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c6edbe5681](https://linux-hardware.org/?probe=c6edbe5681) | Jun 25, 2023 |
| Toshiba       | Satellite Pro L500          | [44e57dc97b](https://linux-hardware.org/?probe=44e57dc97b) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S01G00    | [a66d6dba45](https://linux-hardware.org/?probe=a66d6dba45) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8862b2d8db](https://linux-hardware.org/?probe=8862b2d8db) | Jun 25, 2023 |
| Acer          | Aspire F5-571G              | [fb61026d60](https://linux-hardware.org/?probe=fb61026d60) | Jun 25, 2023 |
| Lenovo        | ThinkPad T450 20BUS0EW1K    | [43f405f4ce](https://linux-hardware.org/?probe=43f405f4ce) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | [bce89b670d](https://linux-hardware.org/?probe=bce89b670d) | Jun 25, 2023 |
| Lenovo        | V15 G2 ITL 82ME             | [3fde30195c](https://linux-hardware.org/?probe=3fde30195c) | Jun 25, 2023 |
| Dell          | Inspiron 1545               | [7f8217bce2](https://linux-hardware.org/?probe=7f8217bce2) | Jun 25, 2023 |
| eMachines     | eME732ZG                    | [4e1d6873ff](https://linux-hardware.org/?probe=4e1d6873ff) | Jun 24, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [23c2fe2245](https://linux-hardware.org/?probe=23c2fe2245) | Jun 24, 2023 |
| Packard Be... | EasyNote TK85               | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| HP            | G62                         | [e8187f4fb6](https://linux-hardware.org/?probe=e8187f4fb6) | Jun 24, 2023 |
| Packard Be... | EasyNote TJ65               | [cdc135487b](https://linux-hardware.org/?probe=cdc135487b) | Jun 24, 2023 |
| Dell          | Latitude 3180               | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| Toshiba       | Satellite C650              | [54ef5b6567](https://linux-hardware.org/?probe=54ef5b6567) | Jun 23, 2023 |
| HP            | 215 G1                      | [0b651dad7d](https://linux-hardware.org/?probe=0b651dad7d) | Jun 23, 2023 |
| HP            | Compaq 610                  | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| HP            | Presario CQ56               | [5a8991a97b](https://linux-hardware.org/?probe=5a8991a97b) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [4ab121533a](https://linux-hardware.org/?probe=4ab121533a) | Jun 23, 2023 |
| MSI           | S12T 3M/S12 3M              | [f135825cec](https://linux-hardware.org/?probe=f135825cec) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b47fa47ef7](https://linux-hardware.org/?probe=b47fa47ef7) | Jun 23, 2023 |
| HP            | Stream 11 Pro G4 EE         | [8add1110e7](https://linux-hardware.org/?probe=8add1110e7) | Jun 23, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [efad2eddea](https://linux-hardware.org/?probe=efad2eddea) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [9d234065ed](https://linux-hardware.org/?probe=9d234065ed) | Jun 22, 2023 |
| Acer          | Aspire ES1-571              | [db93ddfd03](https://linux-hardware.org/?probe=db93ddfd03) | Jun 22, 2023 |
| Acer          | Nitro AN515-57              | [fc54744449](https://linux-hardware.org/?probe=fc54744449) | Jun 22, 2023 |
| ASUSTek       | UX31E                       | [51b4c8d9ef](https://linux-hardware.org/?probe=51b4c8d9ef) | Jun 22, 2023 |
| Dell          | Inspiron 15 3525            | [09f4615df6](https://linux-hardware.org/?probe=09f4615df6) | Jun 22, 2023 |
| Dell          | Inspiron 5557               | [cc0794fa6e](https://linux-hardware.org/?probe=cc0794fa6e) | Jun 21, 2023 |
| Sony          | VGN-NS21M_W                 | [6813d6589e](https://linux-hardware.org/?probe=6813d6589e) | Jun 21, 2023 |
| Acer          | One S1002                   | [f7b8d25603](https://linux-hardware.org/?probe=f7b8d25603) | Jun 21, 2023 |
| Acer          | Aspire R3-131T              | [ab7c961e2b](https://linux-hardware.org/?probe=ab7c961e2b) | Jun 21, 2023 |
| ASUSTek       | K73SD                       | [2dcb7bb5c9](https://linux-hardware.org/?probe=2dcb7bb5c9) | Jun 21, 2023 |
| HP            | Notebook                    | [3460bcb864](https://linux-hardware.org/?probe=3460bcb864) | Jun 20, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [f84ddd7cac](https://linux-hardware.org/?probe=f84ddd7cac) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [c40e92156c](https://linux-hardware.org/?probe=c40e92156c) | Jun 20, 2023 |
| Acer          | Aspire F5-771G              | [034d235f5c](https://linux-hardware.org/?probe=034d235f5c) | Jun 19, 2023 |
| Dell          | System XPS L502X            | [463e017820](https://linux-hardware.org/?probe=463e017820) | Jun 19, 2023 |
| Dell          | Studio 1555                 | [d9337bf223](https://linux-hardware.org/?probe=d9337bf223) | Jun 19, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| HP            | Laptop 14s-dk1xxx           | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| HP            | Pavilion dv2                | [3f3b0104a4](https://linux-hardware.org/?probe=3f3b0104a4) | Jun 18, 2023 |
| HP            | Compaq Presario CQ71        | [d5025e2864](https://linux-hardware.org/?probe=d5025e2864) | Jun 18, 2023 |
| HP            | ZBook 15                    | [80caa07733](https://linux-hardware.org/?probe=80caa07733) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [46692b99cb](https://linux-hardware.org/?probe=46692b99cb) | Jun 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS4840B     | [a60f1ae93e](https://linux-hardware.org/?probe=a60f1ae93e) | Jun 17, 2023 |
| ASUSTek       | X551CAP                     | [9066d9bad2](https://linux-hardware.org/?probe=9066d9bad2) | Jun 17, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [d415965e91](https://linux-hardware.org/?probe=d415965e91) | Jun 17, 2023 |
| Monster       | HUMA H4 V5.2                | [491797a556](https://linux-hardware.org/?probe=491797a556) | Jun 17, 2023 |
| ASUSTek       | G50V                        | [32048be4b5](https://linux-hardware.org/?probe=32048be4b5) | Jun 16, 2023 |
| Dell          | XPS 15 9550                 | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| Acer          | Aspire V3-571               | [75c2da2c37](https://linux-hardware.org/?probe=75c2da2c37) | Jun 15, 2023 |
| HP            | EliteBook 2540p             | [20ddd7a28b](https://linux-hardware.org/?probe=20ddd7a28b) | Jun 15, 2023 |
| ASUSTek       | S400CA                      | [d512f1865e](https://linux-hardware.org/?probe=d512f1865e) | Jun 15, 2023 |
| ASUSTek       | X541UAK                     | [5540ea0d6f](https://linux-hardware.org/?probe=5540ea0d6f) | Jun 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b30634c1ba](https://linux-hardware.org/?probe=b30634c1ba) | Jun 14, 2023 |
| Dell          | Inspiron 1501               | [456a49b146](https://linux-hardware.org/?probe=456a49b146) | Jun 13, 2023 |
| LincPlus      | LINNCPLUS P1                | [878dc2b05f](https://linux-hardware.org/?probe=878dc2b05f) | Jun 13, 2023 |
| Chuwi         | GemiBook Pro                | [34cfc4a037](https://linux-hardware.org/?probe=34cfc4a037) | Jun 13, 2023 |
| Positivo      | C14CR01                     | [11d46971fa](https://linux-hardware.org/?probe=11d46971fa) | Jun 12, 2023 |
| Acer          | Aspire F5-571               | [e54e3157fc](https://linux-hardware.org/?probe=e54e3157fc) | Jun 11, 2023 |
| ASUSTek       | X540SAA                     | [ea61fdd09a](https://linux-hardware.org/?probe=ea61fdd09a) | Jun 11, 2023 |
| Acer          | Nitro AN515-44              | [c74a9048c0](https://linux-hardware.org/?probe=c74a9048c0) | Jun 10, 2023 |
| HP            | Compaq CQ58                 | [98a4edb43d](https://linux-hardware.org/?probe=98a4edb43d) | Jun 10, 2023 |
| Acer          | Aspire E1-572               | [532d86f9e6](https://linux-hardware.org/?probe=532d86f9e6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [03660fb140](https://linux-hardware.org/?probe=03660fb140) | Jun 10, 2023 |
| HP            | G42                         | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| Dell          | Latitude 3580               | [9c02d2c4c4](https://linux-hardware.org/?probe=9c02d2c4c4) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Lenovo        | V110-15IAP 80TG             | [68a77b486e](https://linux-hardware.org/?probe=68a77b486e) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| Toshiba       | Satellite L635              | [4f124d1525](https://linux-hardware.org/?probe=4f124d1525) | Jun 09, 2023 |
| Toshiba       | PORTEGE R705                | [c7a032c5cf](https://linux-hardware.org/?probe=c7a032c5cf) | Jun 09, 2023 |
| Dell          | Vostro 1015                 | [dcd4a1ad41](https://linux-hardware.org/?probe=dcd4a1ad41) | Jun 08, 2023 |
| Lenovo        | ThinkPad L430 24655Q7       | [7b45c0777e](https://linux-hardware.org/?probe=7b45c0777e) | Jun 08, 2023 |
| Lenovo        | ThinkPad L420 7829W1R       | [25d96d98f8](https://linux-hardware.org/?probe=25d96d98f8) | Jun 08, 2023 |
| HP            | Stream Notebook PC 11       | [fd037bb738](https://linux-hardware.org/?probe=fd037bb738) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| MSI           | GS63VR 6RF                  | [4bc33968d1](https://linux-hardware.org/?probe=4bc33968d1) | Jun 06, 2023 |
| Razer         | Blade 15 Advanced Model ... | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASUSTek       | UX31E                       | [92d0de412b](https://linux-hardware.org/?probe=92d0de412b) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4c3091f9ff](https://linux-hardware.org/?probe=4c3091f9ff) | Jun 06, 2023 |
| Lenovo        | Z50-70 20354                | [05a473a2be](https://linux-hardware.org/?probe=05a473a2be) | Jun 06, 2023 |
| MSI           | GF63 Thin 9RCX              | [85ec51dbf3](https://linux-hardware.org/?probe=85ec51dbf3) | Jun 05, 2023 |
| Toshiba       | Satellite L45-B             | [a1bcda2245](https://linux-hardware.org/?probe=a1bcda2245) | Jun 05, 2023 |
| Apple         | MacBookAir7,2               | [44cf28ec0e](https://linux-hardware.org/?probe=44cf28ec0e) | Jun 05, 2023 |
| HP            | Pavilion g4                 | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| HP            | Laptop 17-ak0xx             | [a0430d6f0c](https://linux-hardware.org/?probe=a0430d6f0c) | Jun 05, 2023 |
| Dell          | Latitude E4300              | [cfd95b7e5e](https://linux-hardware.org/?probe=cfd95b7e5e) | Jun 05, 2023 |
| ASUSTek       | VX7SX                       | [ddf3010e73](https://linux-hardware.org/?probe=ddf3010e73) | Jun 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [83982c1aa9](https://linux-hardware.org/?probe=83982c1aa9) | Jun 05, 2023 |
| ASUSTek       | K95VJ                       | [9bbcec82c6](https://linux-hardware.org/?probe=9bbcec82c6) | Jun 05, 2023 |
| Apple         | MacBookAir9,1               | [de1d4d9d23](https://linux-hardware.org/?probe=de1d4d9d23) | Jun 05, 2023 |
| Acer          | AO722                       | [b8f2636f02](https://linux-hardware.org/?probe=b8f2636f02) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| Dell          | Inspiron 5567               | [0564fd483d](https://linux-hardware.org/?probe=0564fd483d) | Jun 04, 2023 |
| HP            | 255 G7 Notebook PC          | [8b14da5cf8](https://linux-hardware.org/?probe=8b14da5cf8) | Jun 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [514b3788ed](https://linux-hardware.org/?probe=514b3788ed) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [681baff23c](https://linux-hardware.org/?probe=681baff23c) | Jun 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [5d6b08920f](https://linux-hardware.org/?probe=5d6b08920f) | Jun 03, 2023 |
| Compaq        | 420                         | [cf7a8f5641](https://linux-hardware.org/?probe=cf7a8f5641) | Jun 03, 2023 |
| Valve         | Jupiter                     | [3aa6cf6780](https://linux-hardware.org/?probe=3aa6cf6780) | Jun 03, 2023 |
| HP            | EliteBook 8440p             | [7f95f275b3](https://linux-hardware.org/?probe=7f95f275b3) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| Lenovo        | ThinkPad L490 20Q5002DMH    | [6d42b7647b](https://linux-hardware.org/?probe=6d42b7647b) | Jun 02, 2023 |
| Samsung       | 670Z5E                      | [647589cbbd](https://linux-hardware.org/?probe=647589cbbd) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1b82c0c3c8](https://linux-hardware.org/?probe=1b82c0c3c8) | Jun 02, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [7b5291c6f8](https://linux-hardware.org/?probe=7b5291c6f8) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | [589bd2e1f8](https://linux-hardware.org/?probe=589bd2e1f8) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| HP            | Laptop 15-dw3xxx            | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| ASUSTek       | X751MA                      | [1b1a5c05ac](https://linux-hardware.org/?probe=1b1a5c05ac) | Jun 01, 2023 |
| Dell          | Latitude 7490               | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| Apple         | MacBookAir9,1               | [b3e3a95a06](https://linux-hardware.org/?probe=b3e3a95a06) | Jun 01, 2023 |
| Samsung       | 300E5K/300E5Q               | [00d2d07850](https://linux-hardware.org/?probe=00d2d07850) | May 31, 2023 |
| Acer          | Aspire A315-58              | [f9995cb422](https://linux-hardware.org/?probe=f9995cb422) | May 31, 2023 |
| Dell          | System Vostro 3450          | [ae337aeb9c](https://linux-hardware.org/?probe=ae337aeb9c) | May 31, 2023 |
| Timi          | RedmiBook 14 II             | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| HP            | 255 G8 Notebook PC          | [ea55e0ac39](https://linux-hardware.org/?probe=ea55e0ac39) | May 30, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Samsung       | RV419/RV420                 | [ddab046bd5](https://linux-hardware.org/?probe=ddab046bd5) | May 30, 2023 |
| Samsung       | 600B4B/600B5B               | [feba5017b3](https://linux-hardware.org/?probe=feba5017b3) | May 29, 2023 |
| Acer          | Aspire ES1-512              | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | [e462733019](https://linux-hardware.org/?probe=e462733019) | May 29, 2023 |
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
| HP            | Pavilion dm4                | [51b921c72d](https://linux-hardware.org/?probe=51b921c72d) | May 28, 2023 |
| Samsung       | 270E5J/2570EJ               | [f90f831805](https://linux-hardware.org/?probe=f90f831805) | May 28, 2023 |
| HP            | 15 Notebook PC              | [3904ffdddf](https://linux-hardware.org/?probe=3904ffdddf) | May 27, 2023 |
| Acer          | Aspire A517-51G             | [bfc89878ce](https://linux-hardware.org/?probe=bfc89878ce) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| Dell          | Inspiron 5567               | [9dc73257dc](https://linux-hardware.org/?probe=9dc73257dc) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| Sony          | VGN-FZ31Z                   | [31c6913c14](https://linux-hardware.org/?probe=31c6913c14) | May 26, 2023 |
| Dell          | Latitude 5290               | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| Dell          | Latitude E5440              | [4a5501c365](https://linux-hardware.org/?probe=4a5501c365) | May 26, 2023 |
| MSI           | GL75 Leopard 10SDK          | [41eac45c5e](https://linux-hardware.org/?probe=41eac45c5e) | May 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffdb62c45](https://linux-hardware.org/?probe=0ffdb62c45) | May 25, 2023 |
| Acer          | TravelMate 5720             | [1066a7a5c5](https://linux-hardware.org/?probe=1066a7a5c5) | May 25, 2023 |
| Dell          | Inspiron 15-3567            | [a8dd30a7bb](https://linux-hardware.org/?probe=a8dd30a7bb) | May 25, 2023 |
| Timi          | TM1701                      | [c883337466](https://linux-hardware.org/?probe=c883337466) | May 24, 2023 |
| Toshiba       | Satellite C660D             | [cd798092df](https://linux-hardware.org/?probe=cd798092df) | May 23, 2023 |
| HP            | Laptop 15-bs1xx             | [f0b7bf3520](https://linux-hardware.org/?probe=f0b7bf3520) | May 23, 2023 |
| Lenovo        | ThinkPad L520 5017A62       | [a8d01c9adb](https://linux-hardware.org/?probe=a8d01c9adb) | May 23, 2023 |
| Apple         | MacBookPro9,2               | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [76db4a03a1](https://linux-hardware.org/?probe=76db4a03a1) | May 22, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | [5c190a4d57](https://linux-hardware.org/?probe=5c190a4d57) | May 22, 2023 |
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
| HP            | ProBook 645 G1              | [c1df991f26](https://linux-hardware.org/?probe=c1df991f26) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | [1094884573](https://linux-hardware.org/?probe=1094884573) | May 19, 2023 |
| Chuwi         | HeroBook Pro                | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| ASUSTek       | F7Se                        | [1cd79e84fd](https://linux-hardware.org/?probe=1cd79e84fd) | May 19, 2023 |
| Lenovo        | ThinkPad L560 20F2S1JP03    | [d0dd999b33](https://linux-hardware.org/?probe=d0dd999b33) | May 18, 2023 |
| Acer          | Aspire A114-32              | [d17a909427](https://linux-hardware.org/?probe=d17a909427) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [82dca1cbb8](https://linux-hardware.org/?probe=82dca1cbb8) | May 18, 2023 |
| Toshiba       | Satellite L850-1HQ          | [d16c26b474](https://linux-hardware.org/?probe=d16c26b474) | May 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [df73f83c15](https://linux-hardware.org/?probe=df73f83c15) | May 18, 2023 |
| Google        | Auron_Paine                 | [a836fcd48f](https://linux-hardware.org/?probe=a836fcd48f) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| HP            | Pavilion g6                 | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| Lenovo        | V15-ADA 82C7                | [cfe4d9071b](https://linux-hardware.org/?probe=cfe4d9071b) | May 16, 2023 |
| HP            | Laptop 17z-ca300            | [8daeb02e63](https://linux-hardware.org/?probe=8daeb02e63) | May 16, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [f199f11aa5](https://linux-hardware.org/?probe=f199f11aa5) | May 15, 2023 |
| Samsung       | R428/P428                   | [1d93335f58](https://linux-hardware.org/?probe=1d93335f58) | May 15, 2023 |
| Samsung       | R530/R730                   | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| Lenovo        | ThinkPad X100e 0022CTO      | [842b7a3ee2](https://linux-hardware.org/?probe=842b7a3ee2) | May 14, 2023 |
| HP            | Pavilion dv8                | [422d1fd213](https://linux-hardware.org/?probe=422d1fd213) | May 14, 2023 |
| Acer          | Aspire A114-32              | [6fdf42b8a9](https://linux-hardware.org/?probe=6fdf42b8a9) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| ASUSTek       | K53BR                       | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Dell          | Precision M4500             | [315cccc082](https://linux-hardware.org/?probe=315cccc082) | May 14, 2023 |
| Lenovo        | G50-30 80G0                 | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Vostro 3400                 | [37eeeb2f31](https://linux-hardware.org/?probe=37eeeb2f31) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| ASUSTek       | UX31E                       | [53f535546a](https://linux-hardware.org/?probe=53f535546a) | May 12, 2023 |
| HP            | EliteBook 720 G2            | [d6a156003b](https://linux-hardware.org/?probe=d6a156003b) | May 12, 2023 |
| Toshiba       | Satellite C75-A             | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| Acer          | Extensa 5220                | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| Chuwi         | GemiBook Pro                | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| Infinix       | INBook X1                   | [c005323a1a](https://linux-hardware.org/?probe=c005323a1a) | May 11, 2023 |
| HP            | Laptop 17-by0xxx            | [10b9d3a925](https://linux-hardware.org/?probe=10b9d3a925) | May 11, 2023 |
| Acer          | Aspire E1-521               | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| ASUSTek       | X555LAB                     | [2710a15a04](https://linux-hardware.org/?probe=2710a15a04) | May 10, 2023 |
| Samsung       | X420/X520                   | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Thomson       | N14C64WF                    | [4e5a5f6e51](https://linux-hardware.org/?probe=4e5a5f6e51) | May 10, 2023 |
| Dell          | Precision M3800             | [e7b0097a72](https://linux-hardware.org/?probe=e7b0097a72) | May 09, 2023 |
| Dell          | Inspiron 5559               | [f7cb6c9251](https://linux-hardware.org/?probe=f7cb6c9251) | May 09, 2023 |
| HP            | Compaq Mini CQ10-500        | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| Dell          | Latitude 5420               | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| Fujitsu       | FMVA0500TP                  | [61061bd78d](https://linux-hardware.org/?probe=61061bd78d) | May 09, 2023 |
| Sony          | VGN-FZ31Z                   | [6fe358200a](https://linux-hardware.org/?probe=6fe358200a) | May 09, 2023 |
| Acer          | Aspire VN7-592G             | [8ebde36ef2](https://linux-hardware.org/?probe=8ebde36ef2) | May 09, 2023 |
| Acer          | Aspire A515-56              | [57b843a3ca](https://linux-hardware.org/?probe=57b843a3ca) | May 09, 2023 |
| Apple         | MacBookPro11,4              | [83f86e5727](https://linux-hardware.org/?probe=83f86e5727) | May 09, 2023 |
| Dell          | Latitude E6440              | [6b8d3c96c5](https://linux-hardware.org/?probe=6b8d3c96c5) | May 09, 2023 |
| HP            | Pavilion dv7                | [1d9699c86f](https://linux-hardware.org/?probe=1d9699c86f) | May 09, 2023 |
| HP            | Pavilion dv6                | [531adb6cae](https://linux-hardware.org/?probe=531adb6cae) | May 09, 2023 |
| HP            | ProBook 440 G1              | [aea73943e8](https://linux-hardware.org/?probe=aea73943e8) | May 09, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| HP            | 15                          | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| Acer          | Aspire ES1-132              | [10a13dcd68](https://linux-hardware.org/?probe=10a13dcd68) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [d615a9b90f](https://linux-hardware.org/?probe=d615a9b90f) | May 08, 2023 |
| Apple         | MacBookAir9,1               | [a0073c6ff3](https://linux-hardware.org/?probe=a0073c6ff3) | May 08, 2023 |
| ASUSTek       | X202E                       | [6039408aaf](https://linux-hardware.org/?probe=6039408aaf) | May 08, 2023 |
| HP            | 15                          | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Dell          | XPS 13 9310                 | [3530619c98](https://linux-hardware.org/?probe=3530619c98) | May 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b734a6d6f3](https://linux-hardware.org/?probe=b734a6d6f3) | May 07, 2023 |
| Toshiba       | Satellite L655              | [9eef570443](https://linux-hardware.org/?probe=9eef570443) | May 07, 2023 |
| Lenovo        | G50-70 20351                | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| HP            | Presario CQ57               | [370295ac6d](https://linux-hardware.org/?probe=370295ac6d) | May 07, 2023 |
| Acer          | Aspire E5-523G              | [7a77c66c97](https://linux-hardware.org/?probe=7a77c66c97) | May 06, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [6c404ee491](https://linux-hardware.org/?probe=6c404ee491) | May 06, 2023 |
| Dell          | System XPS L702X            | [210b876fe7](https://linux-hardware.org/?probe=210b876fe7) | May 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b3bf20b454](https://linux-hardware.org/?probe=b3bf20b454) | May 06, 2023 |
| Panasonic     | CF-54-1                     | [c964ce47c2](https://linux-hardware.org/?probe=c964ce47c2) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [094b22cf5a](https://linux-hardware.org/?probe=094b22cf5a) | May 06, 2023 |
| Toshiba       | Satellite L300D             | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| HP            | EliteBook 2530p             | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| Quanta        | JW2                         | [eb9ff2a263](https://linux-hardware.org/?probe=eb9ff2a263) | May 06, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | [79c33e919f](https://linux-hardware.org/?probe=79c33e919f) | May 06, 2023 |
| ASUSTek       | K75DE                       | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| OpenMandriva 4.2    | 2202      | 29.76%  |
| OpenMandriva 4.3    | 2145      | 28.99%  |
| OpenMandriva 23.01  | 945       | 12.77%  |
| OpenMandriva 23.03  | 928       | 12.54%  |
| OpenMandriva 4.50   | 421       | 5.69%   |
| OpenMandriva 23.08  | 358       | 4.84%   |
| OpenMandriva 4.90   | 168       | 2.27%   |
| OpenMandriva 23.07  | 63        | 0.85%   |
| OpenMandriva 23.06  | 57        | 0.77%   |
| OpenMandriva 23.90  | 36        | 0.49%   |
| OpenMandriva 23.09  | 33        | 0.45%   |
| OpenMandriva 22.12  | 31        | 0.42%   |
| OpenMandriva 4.1    | 4         | 0.05%   |
| OpenMandriva 22.90  | 4         | 0.05%   |
| OpenMandriva 3.0    | 3         | 0.04%   |
| OpenMandriva 22.11  | 1         | 0.01%   |
| OpenMandriva 2014.0 | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| OpenMandriva | 6989      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002      | 2116      | 28.35%  |
| 5.16.7-desktop-1omv4003       | 2021      | 27.08%  |
| 6.2.6-desktop-1omv2390        | 895       | 11.99%  |
| 6.1.1-desktop-1omv2290        | 873       | 11.7%   |
| 6.4.11-desktop-1omv2390       | 250       | 3.35%   |
| 5.12.4-desktop-1omv4050       | 149       | 2%      |
| 5.16.13-desktop-1omv4003      | 138       | 1.85%   |
| 5.18.12-desktop-3omv4090      | 133       | 1.78%   |
| 6.3.5-desktop-3omv2390        | 114       | 1.53%   |
| 6.4.8-desktop-2omv2390        | 107       | 1.43%   |
| 5.11.12-desktop-1omv4002      | 102       | 1.37%   |
| 5.14.7-desktop-1omv4050       | 83        | 1.11%   |
| 5.19.5-desktop-1omv4090       | 77        | 1.03%   |
| 5.19.12-desktop-2omv4090      | 62        | 0.83%   |
| 6.1.4-desktop-1omv2301        | 61        | 0.82%   |
| 6.5.0-desktop-1omv2390        | 36        | 0.48%   |
| 6.0.10-desktop-2omv22090      | 33        | 0.44%   |
| 6.2.2-desktop-1omv2390        | 23        | 0.31%   |
| 5.14.14-desktop-1omv4050      | 18        | 0.24%   |
| 6.0.2-desktop-1omv4090        | 15        | 0.2%    |
| 5.17.1-desktop-2omv4050       | 13        | 0.17%   |
| 5.12.7-desktop-1omv4003       | 11        | 0.15%   |
| 6.2.1-desktop-1omv2390        | 9         | 0.12%   |
| 6.5.1-desktop-1omv2390        | 6         | 0.08%   |
| 6.0.2-desktop-1omv4050        | 6         | 0.08%   |
| 5.19.11-desktop-2omv4090      | 6         | 0.08%   |
| 5.19.1-desktop-1omv4090       | 5         | 0.07%   |
| 5.11.0-desktop-clang-1omv4002 | 5         | 0.07%   |
| 6.4.0-desktop-0.rc3.1omv2390  | 4         | 0.05%   |
| 6.1.2-desktop-1omv2301        | 4         | 0.05%   |
| 6.4.3-desktop-2omv2390        | 3         | 0.04%   |
| 6.2.8-desktop-1omv2390        | 3         | 0.04%   |
| 6.2.7-desktop-1omv2390        | 3         | 0.04%   |
| 5.5.12-desktop-1omv4001       | 3         | 0.04%   |
| 5.16.9-desktop-1omv4003       | 3         | 0.04%   |
| 5.16.5-desktop-2omv4003       | 3         | 0.04%   |
| 6.4.7-desktop-1omv2390        | 2         | 0.03%   |
| 6.3.1-desktop-1omv2390        | 2         | 0.03%   |
| 6.2.0-desktop-0.rc2.1omv2301  | 2         | 0.03%   |
| 6.1.11-desktop-1omv2390       | 2         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.14 | 2116      | 28.36%  |
| 5.16.7  | 2022      | 27.1%   |
| 6.2.6   | 895       | 11.99%  |
| 6.1.1   | 873       | 11.7%   |
| 6.4.11  | 250       | 3.35%   |
| 5.12.4  | 149       | 2%      |
| 5.16.13 | 139       | 1.86%   |
| 5.18.12 | 133       | 1.78%   |
| 6.3.5   | 114       | 1.53%   |
| 6.4.8   | 107       | 1.43%   |
| 5.11.12 | 102       | 1.37%   |
| 5.14.7  | 83        | 1.11%   |
| 5.19.5  | 77        | 1.03%   |
| 6.1.4   | 62        | 0.83%   |
| 5.19.12 | 62        | 0.83%   |
| 6.5.0   | 38        | 0.51%   |
| 6.0.10  | 33        | 0.44%   |
| 6.2.2   | 23        | 0.31%   |
| 6.0.2   | 21        | 0.28%   |
| 5.14.14 | 18        | 0.24%   |
| 5.17.1  | 15        | 0.2%    |
| 5.12.7  | 12        | 0.16%   |
| 6.2.1   | 9         | 0.12%   |
| 5.11.0  | 7         | 0.09%   |
| 6.5.1   | 6         | 0.08%   |
| 5.19.11 | 6         | 0.08%   |
| 5.19.1  | 5         | 0.07%   |
| 6.4.0   | 4         | 0.05%   |
| 6.1.2   | 4         | 0.05%   |
| 5.16.9  | 4         | 0.05%   |
| 6.4.3   | 3         | 0.04%   |
| 6.2.8   | 3         | 0.04%   |
| 6.2.7   | 3         | 0.04%   |
| 6.2.0   | 3         | 0.04%   |
| 5.5.12  | 3         | 0.04%   |
| 5.16.5  | 3         | 0.04%   |
| 6.4.7   | 2         | 0.03%   |
| 6.3.1   | 2         | 0.03%   |
| 6.1.11  | 2         | 0.03%   |
| 6.0.9   | 2         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 2140      | 28.8%   |
| 5.10    | 2118      | 28.51%  |
| 6.1     | 945       | 12.72%  |
| 6.2     | 937       | 12.61%  |
| 6.4     | 367       | 4.94%   |
| 5.12    | 161       | 2.17%   |
| 5.19    | 156       | 2.1%    |
| 5.18    | 139       | 1.87%   |
| 6.3     | 118       | 1.59%   |
| 5.11    | 113       | 1.52%   |
| 5.14    | 101       | 1.36%   |
| 6.0     | 61        | 0.82%   |
| 6.5     | 44        | 0.59%   |
| 5.17    | 15        | 0.2%    |
| 5.5     | 4         | 0.05%   |
| 5.9     | 2         | 0.03%   |
| 5.15    | 2         | 0.03%   |
| 4.19    | 2         | 0.03%   |
| 5.8     | 1         | 0.01%   |
| 5.13    | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |
| 4.1     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 6988      | 99.99%  |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 6667      | 94.51%  |
| GNOME    | 235       | 3.33%   |
| LXQt     | 106       | 1.5%    |
| Unknown  | 23        | 0.33%   |
| Cinnamon | 9         | 0.13%   |
| Budgie   | 7         | 0.1%    |
| XFCE     | 5         | 0.07%   |
| KDE4     | 1         | 0.01%   |
| DWM      | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 6511      | 91.77%  |
| Wayland | 583       | 8.22%   |
| Tty     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 6781      | 96.42%  |
| GDM     | 234       | 3.33%   |
| LightDM | 14        | 0.2%    |
| Unknown | 3         | 0.04%   |
| KDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3727      | 52.2%   |
| de_DE   | 531       | 7.44%   |
| fr_FR   | 433       | 6.06%   |
| pt_BR   | 307       | 4.3%    |
| pl_PL   | 306       | 4.29%   |
| ru_RU   | 299       | 4.19%   |
| it_IT   | 222       | 3.11%   |
| en_GB   | 220       | 3.08%   |
| cs_CZ   | 180       | 2.52%   |
| es_ES   | 157       | 2.2%    |
| es_MX   | 81        | 1.13%   |
| es_AR   | 45        | 0.63%   |
| en_CA   | 39        | 0.55%   |
| hu_HU   | 38        | 0.53%   |
| de_AT   | 37        | 0.52%   |
| nl_NL   | 34        | 0.48%   |
| en_IN   | 34        | 0.48%   |
| en_AU   | 30        | 0.42%   |
| pt_PT   | 29        | 0.41%   |
| es_CL   | 28        | 0.39%   |
| es_CO   | 26        | 0.36%   |
| fr_BE   | 25        | 0.35%   |
| tr_TR   | 23        | 0.32%   |
| de_CH   | 22        | 0.31%   |
| fr_CA   | 21        | 0.29%   |
| nl_BE   | 19        | 0.27%   |
| fr_CH   | 19        | 0.27%   |
| da_DK   | 18        | 0.25%   |
| es_PE   | 15        | 0.21%   |
| ro_RO   | 14        | 0.2%    |
| en_NZ   | 12        | 0.17%   |
| es_VE   | 11        | 0.15%   |
| Unknown | 11        | 0.15%   |
| ru_UA   | 10        | 0.14%   |
| nb_NO   | 9         | 0.13%   |
| es_UY   | 9         | 0.13%   |
| es_CR   | 7         | 0.1%    |
| en_AG   | 7         | 0.1%    |
| es_EC   | 6         | 0.08%   |
| en_IE   | 6         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3702      | 52.66%  |
| BIOS | 3328      | 47.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Overlay  | 4902      | 67.52%  |
| Ext4     | 2140      | 29.48%  |
| Btrfs    | 138       | 1.9%    |
| F2fs     | 35        | 0.48%   |
| Xfs      | 30        | 0.41%   |
| Ext2     | 7         | 0.1%    |
| Unknown  | 4         | 0.06%   |
| Ext3     | 2         | 0.03%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 4780      | 67.71%  |
| MBR     | 2271      | 32.17%  |
| Unknown | 9         | 0.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3655      | 51.12%  |
| Yes       | 3495      | 48.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4169      | 59.15%  |
| Yes       | 2879      | 40.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 1386      | 19.83%  |
| Hewlett-Packard       | 1203      | 17.21%  |
| Dell                  | 1019      | 14.58%  |
| ASUSTek Computer      | 861       | 12.32%  |
| Acer                  | 770       | 11.02%  |
| Toshiba               | 340       | 4.86%   |
| Sony                  | 155       | 2.22%   |
| Samsung Electronics   | 154       | 2.2%    |
| Apple                 | 124       | 1.77%   |
| MSI                   | 114       | 1.63%   |
| Fujitsu               | 90        | 1.29%   |
| Packard Bell          | 60        | 0.86%   |
| Positivo              | 57        | 0.82%   |
| Medion                | 52        | 0.74%   |
| HUAWEI                | 41        | 0.59%   |
| Unknown               | 34        | 0.49%   |
| Notebook              | 31        | 0.44%   |
| eMachines             | 30        | 0.43%   |
| Chuwi                 | 28        | 0.4%    |
| TUXEDO                | 27        | 0.39%   |
| Fujitsu Siemens       | 24        | 0.34%   |
| Philco                | 22        | 0.31%   |
| Google                | 21        | 0.3%    |
| LG Electronics        | 17        | 0.24%   |
| Gateway               | 13        | 0.19%   |
| Compaq                | 13        | 0.19%   |
| Clevo                 | 13        | 0.19%   |
| Alienware             | 12        | 0.17%   |
| System76              | 11        | 0.16%   |
| Panasonic             | 11        | 0.16%   |
| Intel                 | 11        | 0.16%   |
| Gigabyte Technology   | 11        | 0.16%   |
| Timi                  | 10        | 0.14%   |
| NEC Computers         | 10        | 0.14%   |
| GPU Company           | 10        | 0.14%   |
| Positivo Bahia - VAIO | 8         | 0.11%   |
| UMAX                  | 7         | 0.1%    |
| Wortmann AG           | 6         | 0.09%   |
| Teclast               | 6         | 0.09%   |
| Star Labs             | 5         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| ASUS UX31E                     | 125       | 1.79%   |
| Unknown                        | 71        | 1.02%   |
| HP Notebook                    | 69        | 0.99%   |
| HP Pavilion g6                 | 32        | 0.46%   |
| Dell Inspiron 3451             | 32        | 0.46%   |
| Dell Latitude 3310             | 29        | 0.41%   |
| HP Pavilion dv6                | 26        | 0.37%   |
| Toshiba dynabook T653/46JR     | 24        | 0.34%   |
| Dell Latitude E6430            | 23        | 0.33%   |
| Sony VGN-FZ31Z                 | 21        | 0.3%    |
| HP Pavilion 15                 | 20        | 0.29%   |
| Dell Latitude E6410            | 19        | 0.27%   |
| Dell Inspiron 15-3567          | 19        | 0.27%   |
| Lenovo IdeaPad 3 15ADA05 81W1  | 18        | 0.26%   |
| Dell Latitude E6400            | 18        | 0.26%   |
| Dell Inspiron 1545             | 18        | 0.26%   |
| HP 15                          | 17        | 0.24%   |
| Dell Latitude E6420            | 17        | 0.24%   |
| Dell Latitude D630             | 17        | 0.24%   |
| Positivo Mobile                | 16        | 0.23%   |
| Lenovo IdeaPad S145-15AST 81N3 | 16        | 0.23%   |
| Lenovo IdeaPad 1 14ADA05 82GW  | 16        | 0.23%   |
| HP Pavilion Notebook           | 16        | 0.23%   |
| Apple MacBookPro9,2            | 16        | 0.23%   |
| ASUS S551LN                    | 15        | 0.21%   |
| Apple MacBookPro8,1            | 15        | 0.21%   |
| HP Laptop 15-db0xxx            | 13        | 0.19%   |
| Dell Latitude E7450            | 13        | 0.19%   |
| Dell Latitude 7490             | 13        | 0.19%   |
| Lenovo IdeaPad 330-15IKB 81DE  | 12        | 0.17%   |
| HP EliteBook 8440p             | 12        | 0.17%   |
| HP Compaq Presario CQ60        | 12        | 0.17%   |
| Dell Latitude E6440            | 12        | 0.17%   |
| Lenovo IdeaPad 330S-15IKB 81F5 | 11        | 0.16%   |
| HP Pavilion dv7                | 11        | 0.16%   |
| HP 250 G6 Notebook PC          | 11        | 0.16%   |
| Dell Latitude E7440            | 11        | 0.16%   |
| Dell Latitude E6540            | 11        | 0.16%   |
| Dell Latitude E5470            | 11        | 0.16%   |
| Dell Inspiron N5110            | 11        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 587       | 8.4%    |
| Acer Aspire           | 563       | 8.06%   |
| Dell Latitude         | 489       | 7%      |
| Lenovo IdeaPad        | 425       | 6.08%   |
| Dell Inspiron         | 316       | 4.52%   |
| Toshiba Satellite     | 261       | 3.73%   |
| HP Pavilion           | 250       | 3.58%   |
| HP Laptop             | 190       | 2.72%   |
| HP EliteBook          | 151       | 2.16%   |
| ASUS VivoBook         | 144       | 2.06%   |
| HP ProBook            | 139       | 1.99%   |
| ASUS UX31E            | 125       | 1.79%   |
| HP Compaq             | 97        | 1.39%   |
| Unknown               | 71        | 1.02%   |
| HP Notebook           | 69        | 0.99%   |
| Fujitsu LIFEBOOK      | 69        | 0.99%   |
| Packard Bell EasyNote | 51        | 0.73%   |
| Dell Precision        | 51        | 0.73%   |
| Dell Vostro           | 50        | 0.72%   |
| Dell XPS              | 47        | 0.67%   |
| Toshiba dynabook      | 43        | 0.62%   |
| Acer TravelMate       | 42        | 0.6%    |
| Acer Nitro            | 42        | 0.6%    |
| Acer Extensa          | 39        | 0.56%   |
| HP 250                | 34        | 0.49%   |
| Acer Swift            | 31        | 0.44%   |
| Lenovo Legion         | 29        | 0.41%   |
| Lenovo Yoga           | 28        | 0.4%    |
| HP 255                | 27        | 0.39%   |
| Dell Studio           | 25        | 0.36%   |
| HP Stream             | 24        | 0.34%   |
| HP ENVY               | 23        | 0.33%   |
| HP 15                 | 23        | 0.33%   |
| ASUS ZenBook          | 22        | 0.31%   |
| Sony VGN-FZ31Z        | 21        | 0.3%    |
| ASUS ROG              | 21        | 0.3%    |
| Dell System           | 20        | 0.29%   |
| HP OMEN               | 19        | 0.27%   |
| Apple MacBookPro9     | 19        | 0.27%   |
| ASUS TUF              | 18        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 820       | 11.73%  |
| 2012    | 664       | 9.5%    |
| 2013    | 536       | 7.67%   |
| 2019    | 491       | 7.03%   |
| 2010    | 486       | 6.95%   |
| 2014    | 478       | 6.84%   |
| 2020    | 453       | 6.48%   |
| 2015    | 409       | 5.85%   |
| 2021    | 402       | 5.75%   |
| 2018    | 399       | 5.71%   |
| 2016    | 387       | 5.54%   |
| 2008    | 387       | 5.54%   |
| 2017    | 363       | 5.19%   |
| 2009    | 292       | 4.18%   |
| 2007    | 235       | 3.36%   |
| 2022    | 120       | 1.72%   |
| 2006    | 34        | 0.49%   |
| 2023    | 19        | 0.27%   |
| Unknown | 8         | 0.11%   |
| 2005    | 3         | 0.04%   |
| 2004    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 6989      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 6989      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6952      | 99.46%  |
| Yes  | 38        | 0.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 2402      | 34.12%  |
| 4.01-8.0    | 2266      | 32.19%  |
| 8.01-16.0   | 985       | 13.99%  |
| 16.01-24.0  | 687       | 9.76%   |
| 1.01-2.0    | 299       | 4.25%   |
| 32.01-64.0  | 176       | 2.5%    |
| 2.01-3.0    | 144       | 2.05%   |
| 24.01-32.0  | 36        | 0.51%   |
| 64.01-256.0 | 31        | 0.44%   |
| 0.51-1.0    | 13        | 0.18%   |
| Unknown     | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 5454      | 75.57%  |
| 2.01-3.0  | 901       | 12.48%  |
| 0.51-1.0  | 655       | 9.08%   |
| 3.01-4.0  | 117       | 1.62%   |
| 0.01-0.5  | 54        | 0.75%   |
| 4.01-8.0  | 32        | 0.44%   |
| 8.01-16.0 | 3         | 0.04%   |
| Unknown   | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5161      | 73.21%  |
| 2      | 1564      | 22.18%  |
| 3      | 199       | 2.82%   |
| 0      | 100       | 1.42%   |
| 4      | 23        | 0.33%   |
| 5      | 2         | 0.03%   |
| 7      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3625      | 51.68%  |
| Yes       | 3389      | 48.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6011      | 85.99%  |
| No        | 979       | 14.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6930      | 99.11%  |
| No        | 62        | 0.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5013      | 71.44%  |
| No        | 2004      | 28.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 776       | 11.08%  |
| Germany     | 752       | 10.74%  |
| France      | 510       | 7.28%   |
| Brazil      | 484       | 6.91%   |
| Poland      | 428       | 6.11%   |
| Russia      | 382       | 5.46%   |
| Italy       | 338       | 4.83%   |
| UK          | 258       | 3.68%   |
| Spain       | 222       | 3.17%   |
| Czechia     | 209       | 2.98%   |
| Canada      | 178       | 2.54%   |
| Netherlands | 151       | 2.16%   |
| Mexico      | 132       | 1.89%   |
| Japan       | 122       | 1.74%   |
| India       | 117       | 1.67%   |
| Australia   | 88        | 1.26%   |
| Indonesia   | 86        | 1.23%   |
| Portugal    | 84        | 1.2%    |
| Romania     | 78        | 1.11%   |
| Belgium     | 76        | 1.09%   |
| Finland     | 72        | 1.03%   |
| Switzerland | 69        | 0.99%   |
| Hungary     | 63        | 0.9%    |
| Sweden      | 62        | 0.89%   |
| Argentina   | 61        | 0.87%   |
| Turkey      | 58        | 0.83%   |
| Ukraine     | 55        | 0.79%   |
| Austria     | 54        | 0.77%   |
| Colombia    | 51        | 0.73%   |
| Greece      | 46        | 0.66%   |
| Slovakia    | 42        | 0.6%    |
| Chile       | 42        | 0.6%    |
| Bulgaria    | 41        | 0.59%   |
| China       | 36        | 0.51%   |
| Norway      | 32        | 0.46%   |
| New Zealand | 31        | 0.44%   |
| Denmark     | 30        | 0.43%   |
| Serbia      | 29        | 0.41%   |
| Peru        | 29        | 0.41%   |
| Belarus     | 25        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Prague         | 128       | 1.76%   |
| Warsaw         | 79        | 1.09%   |
| Moscow         | 76        | 1.05%   |
| Paris          | 70        | 0.96%   |
| Schagen        | 56        | 0.77%   |
| Berlin         | 55        | 0.76%   |
| Milan          | 53        | 0.73%   |
| Krakow         | 50        | 0.69%   |
| Sao Paulo      | 39        | 0.54%   |
| Munich         | 39        | 0.54%   |
| St Petersburg  | 36        | 0.5%    |
| Rome           | 33        | 0.45%   |
| Vienna         | 32        | 0.44%   |
| Mexico City    | 30        | 0.41%   |
| Rio de Janeiro | 28        | 0.39%   |
| Helsinki       | 27        | 0.37%   |
| Madrid         | 26        | 0.36%   |
| Hamburg        | 26        | 0.36%   |
| Cologne        | 23        | 0.32%   |
| Sydney         | 22        | 0.3%    |
| Athens         | 22        | 0.3%    |
| Funchal        | 21        | 0.29%   |
| Bucharest      | 21        | 0.29%   |
| Bengaluru      | 21        | 0.29%   |
| Poznan         | 20        | 0.28%   |
| Krasnodar      | 20        | 0.28%   |
| Jakarta        | 20        | 0.28%   |
| Budapest       | 20        | 0.28%   |
| Wroclaw        | 19        | 0.26%   |
| Barcelona      | 19        | 0.26%   |
| Stuttgart      | 18        | 0.25%   |
| Lima           | 18        | 0.25%   |
| Brisbane       | 18        | 0.25%   |
| Melbourne      | 17        | 0.23%   |
| London         | 17        | 0.23%   |
| Istanbul       | 17        | 0.23%   |
| Buenos Aires   | 17        | 0.23%   |
| Bogotá        | 17        | 0.23%   |
| Gdansk         | 16        | 0.22%   |
| Curitiba       | 15        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1192      | 1308   | 14.22%  |
| Seagate             | 984       | 1081   | 11.74%  |
| Samsung Electronics | 984       | 1127   | 11.74%  |
| Toshiba             | 769       | 837    | 9.18%   |
| Kingston            | 498       | 534    | 5.94%   |
| SanDisk             | 465       | 494    | 5.55%   |
| Hitachi             | 387       | 411    | 4.62%   |
| Unknown             | 335       | 360    | 4%      |
| Crucial             | 316       | 352    | 3.77%   |
| HGST                | 253       | 272    | 3.02%   |
| SK hynix            | 226       | 247    | 2.7%    |
| Intel               | 160       | 186    | 1.91%   |
| A-DATA Technology   | 143       | 153    | 1.71%   |
| Micron Technology   | 127       | 139    | 1.52%   |
| China               | 94        | 96     | 1.12%   |
| GOODRAM             | 65        | 70     | 0.78%   |
| Fujitsu             | 64        | 67     | 0.76%   |
| Apple               | 63        | 69     | 0.75%   |
| PNY                 | 62        | 70     | 0.74%   |
| KIOXIA              | 59        | 64     | 0.7%    |
| SPCC                | 58        | 61     | 0.69%   |
| Unknown             | 56        | 59     | 0.67%   |
| Intenso             | 55        | 57     | 0.66%   |
| JMicron Technology  | 54        | 56     | 0.64%   |
| LITEON              | 50        | 51     | 0.6%    |
| Transcend           | 45        | 46     | 0.54%   |
| Patriot             | 44        | 47     | 0.52%   |
| Phison              | 36        | 39     | 0.43%   |
| KingSpec            | 29        | 29     | 0.35%   |
| Netac               | 27        | 32     | 0.32%   |
| UMIS                | 25        | 25     | 0.3%    |
| SSSTC               | 25        | 29     | 0.3%    |
| Apacer              | 24        | 24     | 0.29%   |
| Silicon Motion      | 23        | 28     | 0.27%   |
| Gigabyte Technology | 23        | 23     | 0.27%   |
| OCZ                 | 22        | 22     | 0.26%   |
| LITEONIT            | 22        | 24     | 0.26%   |
| ASMT                | 22        | 23     | 0.26%   |
| SABRENT             | 18        | 22     | 0.21%   |
| Hewlett-Packard     | 17        | 19     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 134       | 1.57%   |
| SanDisk SSD U100 256GB              | 125       | 1.46%   |
| Toshiba MQ01ABF050 500GB            | 111       | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 107       | 1.25%   |
| Kingston SA400S37240G 240GB SSD     | 106       | 1.24%   |
| Toshiba MQ01ABD100 1TB              | 99        | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB      | 94        | 1.1%    |
| Toshiba MQ04ABF100 1TB              | 78        | 0.91%   |
| Kingston SA400S37480G 480GB SSD     | 67        | 0.78%   |
| Seagate ST9500325AS 500GB           | 66        | 0.77%   |
| Unknown                             | 56        | 0.65%   |
| HGST HTS545050A7E680 500GB          | 55        | 0.64%   |
| Crucial CT240BX500SSD1 240GB        | 52        | 0.61%   |
| Samsung SSD 860 EVO 500GB           | 51        | 0.6%    |
| Kingston SA400S37120G 120GB SSD     | 51        | 0.6%    |
| HGST HTS721010A9E630 1TB            | 50        | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB            | 48        | 0.56%   |
| HGST HTS541010A9E680 1TB            | 46        | 0.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 45        | 0.53%   |
| Toshiba MQ01ABD075 752GB            | 44        | 0.51%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 37        | 0.43%   |
| Crucial CT500MX500SSD1 500GB        | 37        | 0.43%   |
| Kingston SV300S37A120G 120GB SSD    | 36        | 0.42%   |
| Unknown SD/MMC/MS PRO 1GB           | 35        | 0.41%   |
| Seagate ST500LT012-9WS142 500GB     | 34        | 0.4%    |
| Samsung SSD 850 EVO 250GB           | 32        | 0.37%   |
| Samsung SSD 850 EVO 500GB           | 31        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 29        | 0.34%   |
| Seagate ST9320325AS 320GB           | 29        | 0.34%   |
| Hitachi HTS543232A7A384 320GB       | 29        | 0.34%   |
| HGST HTS545050A7E380 500GB          | 29        | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 28        | 0.33%   |
| Hitachi HTS547550A9E384 500GB       | 28        | 0.33%   |
| Crucial CT1000MX500SSD1 1TB         | 28        | 0.33%   |
| WDC WD10SPZX-21Z10T0 1TB            | 27        | 0.32%   |
| Toshiba MQ01ABD050 500GB            | 27        | 0.32%   |
| Seagate ST1000LM048-2E7172 1TB      | 27        | 0.32%   |
| Hitachi HTS547575A9E384 752GB       | 27        | 0.32%   |
| SanDisk DF4032  32GB                | 26        | 0.3%    |
| JMicron Generic 1TB                 | 26        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 965       | 1051   | 28.94%  |
| WDC                 | 833       | 901    | 24.99%  |
| Toshiba             | 660       | 713    | 19.8%   |
| Hitachi             | 387       | 411    | 11.61%  |
| HGST                | 253       | 272    | 7.59%   |
| Samsung Electronics | 69        | 72     | 2.07%   |
| Fujitsu             | 64        | 67     | 1.92%   |
| Unknown             | 35        | 35     | 1.05%   |
| Apple               | 15        | 15     | 0.45%   |
| SABRENT             | 13        | 16     | 0.39%   |
| External            | 7         | 7      | 0.21%   |
| USB                 | 5         | 5      | 0.15%   |
| SAGE                | 5         | 5      | 0.15%   |
| USB3.0              | 4         | 4      | 0.12%   |
| HGST HTS            | 3         | 3      | 0.09%   |
| ASMT                | 3         | 4      | 0.09%   |
| SSK                 | 2         | 3      | 0.06%   |
| Hewlett-Packard     | 2         | 2      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| WD MediaMax         | 1         | 1      | 0.03%   |
| QC-FT-D             | 1         | 1      | 0.03%   |
| Magnetic Data       | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 571       | 636    | 17.46%  |
| Kingston            | 409       | 438    | 12.5%   |
| SanDisk             | 395       | 415    | 12.08%  |
| Crucial             | 281       | 312    | 8.59%   |
| WDC                 | 167       | 174    | 5.11%   |
| A-DATA Technology   | 112       | 117    | 3.42%   |
| China               | 94        | 96     | 2.87%   |
| SK hynix            | 78        | 84     | 2.38%   |
| Toshiba             | 72        | 79     | 2.2%    |
| Micron Technology   | 71        | 78     | 2.17%   |
| GOODRAM             | 64        | 69     | 1.96%   |
| Intel               | 61        | 66     | 1.86%   |
| PNY                 | 53        | 58     | 1.62%   |
| SPCC                | 52        | 53     | 1.59%   |
| Intenso             | 49        | 51     | 1.5%    |
| LITEON              | 46        | 47     | 1.41%   |
| Patriot             | 43        | 46     | 1.31%   |
| Transcend           | 42        | 43     | 1.28%   |
| JMicron Technology  | 36        | 38     | 1.1%    |
| Apple               | 35        | 36     | 1.07%   |
| KingSpec            | 27        | 27     | 0.83%   |
| Netac               | 26        | 31     | 0.79%   |
| OCZ                 | 22        | 22     | 0.67%   |
| LITEONIT            | 22        | 24     | 0.67%   |
| Apacer              | 22        | 22     | 0.67%   |
| Unknown             | 20        | 20     | 0.61%   |
| ASMT                | 15        | 15     | 0.46%   |
| Gigabyte Technology | 14        | 14     | 0.43%   |
| Seagate             | 13        | 16     | 0.4%    |
| Lexar               | 13        | 14     | 0.4%    |
| Verbatim            | 12        | 14     | 0.37%   |
| Hewlett-Packard     | 12        | 13     | 0.37%   |
| Plextor             | 11        | 11     | 0.34%   |
| Unknown             | 10        | 10     | 0.31%   |
| KingDian            | 10        | 11     | 0.31%   |
| Team                | 9         | 9      | 0.28%   |
| KIOXIA-EXCERIA      | 9         | 9      | 0.28%   |
| Corsair             | 9         | 11     | 0.28%   |
| Acer                | 9         | 9      | 0.28%   |
| Teclast             | 8         | 8      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3215      | 3595   | 40.29%  |
| SSD     | 3026      | 3504   | 37.92%  |
| NVMe    | 1289      | 1542   | 16.15%  |
| MMC     | 367       | 406    | 4.6%    |
| Unknown | 83        | 86     | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5664      | 6781   | 73.77%  |
| NVMe | 1289      | 1530   | 16.79%  |
| MMC  | 367       | 406    | 4.78%   |
| SAS  | 358       | 416    | 4.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4514      | 5238   | 73.34%  |
| 0.51-1.0   | 1498      | 1698   | 24.34%  |
| 1.01-2.0   | 124       | 143    | 2.01%   |
| 4.01-10.0  | 12        | 13     | 0.19%   |
| 3.01-4.0   | 7         | 7      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3592      | 49.24%  |
| 101-250        | 1309      | 17.94%  |
| 251-500        | 861       | 11.8%   |
| 501-1000       | 432       | 5.92%   |
| 51-100         | 387       | 5.31%   |
| 21-50          | 310       | 4.25%   |
| Unknown        | 264       | 3.62%   |
| 1001-2000      | 100       | 1.37%   |
| 2001-3000      | 25        | 0.34%   |
| More than 3000 | 15        | 0.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 6117      | 85.19%  |
| 21-50          | 278       | 3.87%   |
| Unknown        | 264       | 3.68%   |
| 51-100         | 189       | 2.63%   |
| 101-250        | 175       | 2.44%   |
| 251-500        | 93        | 1.3%    |
| 501-1000       | 41        | 0.57%   |
| 1001-2000      | 18        | 0.25%   |
| More than 3000 | 2         | 0.03%   |
| 2001-3000      | 2         | 0.03%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 125       | 126    | 7.15%   |
| Seagate ST9500325AS 500GB           | 48        | 51     | 2.74%   |
| Seagate ST500LT012-1DG142 500GB     | 42        | 44     | 2.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 41        | 45     | 2.34%   |
| HGST HTS545050A7E680 500GB          | 38        | 38     | 2.17%   |
| Toshiba MQ01ABF050 500GB            | 32        | 33     | 1.83%   |
| Toshiba MQ01ABD075 752GB            | 32        | 33     | 1.83%   |
| Seagate ST500LT012-9WS142 500GB     | 32        | 33     | 1.83%   |
| HGST HTS541010A9E680 1TB            | 29        | 31     | 1.66%   |
| Seagate ST9320325AS 320GB           | 25        | 25     | 1.43%   |
| Toshiba MQ01ABD100 1TB              | 22        | 22     | 1.26%   |
| Seagate ST1000LM035-1RK172 1TB      | 21        | 22     | 1.2%    |
| Hitachi HTS543232A7A384 320GB       | 20        | 21     | 1.14%   |
| Toshiba MQ01ABD050 500GB            | 18        | 18     | 1.03%   |
| Hitachi HTS545050A7E380 500GB       | 18        | 20     | 1.03%   |
| HGST HTS545050A7E380 500GB          | 16        | 16     | 0.91%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 15        | 15     | 0.86%   |
| Crucial CT240M500SSD1 240GB         | 15        | 16     | 0.86%   |
| HGST HTS721010A9E630 1TB            | 14        | 15     | 0.8%    |
| Kingston SV300S37A120G 120GB SSD    | 13        | 13     | 0.74%   |
| Hitachi HTS547575A9E384 752GB       | 13        | 14     | 0.74%   |
| Hitachi HTS547550A9E384 500GB       | 13        | 14     | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB            | 12        | 12     | 0.69%   |
| Seagate ST500LM021-1KJ152 500GB     | 11        | 11     | 0.63%   |
| HGST HTS725050A7E630 500GB          | 11        | 11     | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 10        | 11     | 0.57%   |
| Toshiba MK3265GSX 320GB             | 10        | 11     | 0.57%   |
| Seagate ST9500420AS 500GB           | 10        | 10     | 0.57%   |
| Seagate ST9250827AS 250GB           | 10        | 13     | 0.57%   |
| Hitachi HTS545050B9A300 500GB       | 10        | 12     | 0.57%   |
| HGST HTS541075A9E680 752GB          | 10        | 12     | 0.57%   |
| Toshiba MK2555GSX 250GB             | 9         | 9      | 0.51%   |
| Seagate ST500LM000-1EJ162 500GB     | 9         | 10     | 0.51%   |
| Seagate ST320LT007-9ZV142 320GB     | 9         | 9      | 0.51%   |
| Hitachi HTS547564A9E384 640GB       | 9         | 10     | 0.51%   |
| Hitachi HTS542516K9SA00 160GB       | 9         | 9      | 0.51%   |
| Seagate ST9250410AS 250GB           | 8         | 9      | 0.46%   |
| Seagate ST9250315AS 250GB           | 8         | 9      | 0.46%   |
| Samsung Electronics HM641JI 640GB   | 8         | 10     | 0.46%   |
| Seagate ST9320423AS 320GB           | 7         | 9      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 404       | 429    | 23.17%  |
| Toshiba             | 277       | 286    | 15.88%  |
| WDC                 | 231       | 245    | 13.25%  |
| Hitachi             | 221       | 237    | 12.67%  |
| SanDisk             | 151       | 152    | 8.66%   |
| HGST                | 133       | 139    | 7.63%   |
| Samsung Electronics | 59        | 63     | 3.38%   |
| Kingston            | 37        | 37     | 2.12%   |
| Crucial             | 34        | 36     | 1.95%   |
| SK hynix            | 26        | 28     | 1.49%   |
| Fujitsu             | 25        | 27     | 1.43%   |
| Intel               | 23        | 25     | 1.32%   |
| A-DATA Technology   | 17        | 19     | 0.97%   |
| China               | 15        | 15     | 0.86%   |
| Micron Technology   | 13        | 14     | 0.75%   |
| LITEON              | 7         | 7      | 0.4%    |
| Apple               | 7         | 7      | 0.4%    |
| OCZ                 | 6         | 6      | 0.34%   |
| KingSpec            | 5         | 5      | 0.29%   |
| SPCC                | 4         | 4      | 0.23%   |
| Plextor             | 3         | 3      | 0.17%   |
| Netac               | 3         | 3      | 0.17%   |
| Intenso             | 3         | 3      | 0.17%   |
| Transcend           | 2         | 3      | 0.11%   |
| Teclast             | 2         | 2      | 0.11%   |
| PNY                 | 2         | 3      | 0.11%   |
| Dogfish             | 2         | 2      | 0.11%   |
| Corsair             | 2         | 3      | 0.11%   |
| ASMT                | 2         | 2      | 0.11%   |
| ASMedia             | 2         | 2      | 0.11%   |
| XrayDisk            | 1         | 1      | 0.06%   |
| Vaseky              | 1         | 1      | 0.06%   |
| USB                 | 1         | 1      | 0.06%   |
| Unknown             | 1         | 1      | 0.06%   |
| Union Memory        | 1         | 1      | 0.06%   |
| TakeMS              | 1         | 1      | 0.06%   |
| SSSTC               | 1         | 1      | 0.06%   |
| Smartbuy            | 1         | 1      | 0.06%   |
| RDM-II              | 1         | 1      | 0.06%   |
| Platinet            | 1         | 1      | 0.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 403       | 428    | 30.76%  |
| Toshiba             | 271       | 280    | 20.69%  |
| Hitachi             | 221       | 237    | 16.87%  |
| WDC                 | 212       | 225    | 16.18%  |
| HGST                | 133       | 139    | 10.15%  |
| Samsung Electronics | 37        | 39     | 2.82%   |
| Fujitsu             | 25        | 27     | 1.91%   |
| Apple               | 3         | 3      | 0.23%   |
| USB                 | 1         | 1      | 0.08%   |
| Magnetic Data       | 1         | 1      | 0.08%   |
| IBM/Hitachi         | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1294      | 1383   | 74.97%  |
| SSD     | 413       | 429    | 23.93%  |
| NVMe    | 18        | 21     | 1.04%   |
| Unknown | 1         | 1      | 0.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 4.88%   |
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 4.88%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 4.88%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 4.88%   |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 4.88%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 2.44%   |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 2.44%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 2.44%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 2.44%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 2.44%   |
| WDC WD3200BUCT-63TWBY0 320GB          | 1         | 1      | 2.44%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 1      | 2.44%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 2.44%   |
| WDC WD2500BEVT-35A23T0 250GB          | 1         | 1      | 2.44%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 2.44%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.44%   |
| Toshiba MK3265GSXN 320GB              | 1         | 1      | 2.44%   |
| Toshiba MK3261GSYN 320GB              | 1         | 1      | 2.44%   |
| Toshiba MK3259GSXP 320GB              | 1         | 2      | 2.44%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 2.44%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.44%   |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 2.44%   |
| Samsung Electronics HM500JI 500GB     | 1         | 1      | 2.44%   |
| Samsung Electronics HM321HI 320GB     | 1         | 1      | 2.44%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 2.44%   |
| Samsung Electronics HM250HI 250GB     | 1         | 1      | 2.44%   |
| Intel SSDSA2BW160G3 160GB             | 1         | 1      | 2.44%   |
| Hitachi HTS723232A7A364 320GB         | 1         | 1      | 2.44%   |
| Hitachi HTS545050B9SA00 500GB         | 1         | 1      | 2.44%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 2.44%   |
| Hitachi HTS545016B9A300 160GB         | 1         | 1      | 2.44%   |
| HGST HTS545050B7E660 500GB            | 1         | 1      | 2.44%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 2.44%   |
| Apple HDD HTS545050A7E362 500GB       | 1         | 1      | 2.44%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 15     | 36.59%  |
| Toshiba             | 6         | 7      | 14.63%  |
| Hitachi             | 6         | 6      | 14.63%  |
| Samsung Electronics | 5         | 5      | 12.2%   |
| Seagate             | 2         | 2      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| Crucial             | 2         | 2      | 4.88%   |
| SK hynix            | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 5199      | 6449   | 68.13%  |
| Malfunc  | 1708      | 1834   | 22.38%  |
| Detected | 683       | 808    | 8.95%   |
| Failed   | 41        | 42     | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 5327      | 69.27%  |
| AMD                                     | 989       | 12.86%  |
| Samsung Electronics                     | 389       | 5.06%   |
| SanDisk                                 | 237       | 3.08%   |
| SK hynix                                | 135       | 1.76%   |
| Kingston Technology Company             | 92        | 1.2%    |
| Phison Electronics                      | 69        | 0.9%    |
| Nvidia                                  | 62        | 0.81%   |
| KIOXIA                                  | 61        | 0.79%   |
| Micron Technology                       | 57        | 0.74%   |
| Toshiba America Info Systems            | 41        | 0.53%   |
| Silicon Motion                          | 38        | 0.49%   |
| Micron/Crucial Technology               | 35        | 0.46%   |
| Union Memory (Shenzhen)                 | 28        | 0.36%   |
| ADATA Technology                        | 26        | 0.34%   |
| Solid State Storage Technology          | 24        | 0.31%   |
| Realtek Semiconductor                   | 17        | 0.22%   |
| Apple                                   | 10        | 0.13%   |
| Silicon Integrated Systems [SiS]        | 9         | 0.12%   |
| JMicron Technology                      | 7         | 0.09%   |
| Lenovo                                  | 5         | 0.07%   |
| ASMedia Technology                      | 5         | 0.07%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.05%   |
| Lite-On Technology                      | 4         | 0.05%   |
| Biwin Storage Technology                | 4         | 0.05%   |
| Silicon Image                           | 3         | 0.04%   |
| Shenzhen Longsys Electronics            | 3         | 0.04%   |
| Seagate Technology                      | 3         | 0.04%   |
| Marvell Technology Group                | 3         | 0.04%   |
| Yangtze Memory Technologies             | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 766       | 9.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 698       | 8.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 610       | 7.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 567       | 6.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 421       | 5.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 380       | 4.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 275       | 3.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 271       | 3.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 259       | 3.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 224       | 2.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 224       | 2.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 176       | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 166       | 1.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 148       | 1.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 148       | 1.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 147       | 1.76%   |
| Samsung NVMe SSD Controller 980                                                  | 135       | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 129       | 1.54%   |
| Intel Volume Management Device NVMe RAID Controller                              | 120       | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 99        | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 96        | 1.15%   |
| Intel Tiger Lake-LP SATA Controller                                              | 84        | 1%      |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 81        | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 80        | 0.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 71        | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 59        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 55        | 0.66%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 54        | 0.65%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 52        | 0.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 49        | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 45        | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 44        | 0.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 42        | 0.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 42        | 0.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 41        | 0.49%   |
| Intel SSD 660P Series                                                            | 41        | 0.49%   |
| SK hynix BC511 NVMe SSD                                                          | 39        | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 37        | 0.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 35        | 0.42%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 34        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5671      | 70.1%   |
| NVMe | 1287      | 15.91%  |
| IDE  | 610       | 7.54%   |
| RAID | 522       | 6.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 5718      | 81.81%  |
| AMD    | 1271      | 18.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 125       | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 103       | 1.47%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 90        | 1.29%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 88        | 1.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 83        | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 83        | 1.19%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 81        | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 73        | 1.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 73        | 1.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 72        | 1.03%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 62        | 0.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 61        | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 60        | 0.86%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 58        | 0.83%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 57        | 0.81%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 57        | 0.81%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 57        | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 56        | 0.8%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 56        | 0.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 55        | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 55        | 0.79%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 52        | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 50        | 0.71%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 49        | 0.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 48        | 0.69%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 47        | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 46        | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 46        | 0.66%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 46        | 0.66%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 46        | 0.66%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 46        | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 45        | 0.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 43        | 0.61%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 43        | 0.61%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 41        | 0.59%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 40        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 39        | 0.56%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 37        | 0.53%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 36        | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 36        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1704      | 24.37%  |
| Intel Core i7           | 1034      | 14.79%  |
| Intel Core i3           | 833       | 11.91%  |
| Intel Celeron           | 660       | 9.44%   |
| Intel Core 2 Duo        | 545       | 7.79%   |
| Other                   | 304       | 4.35%   |
| Intel Pentium           | 291       | 4.16%   |
| AMD Ryzen 5             | 221       | 3.16%   |
| AMD Ryzen 7             | 168       | 2.4%    |
| Intel Pentium Dual-Core | 117       | 1.67%   |
| AMD A6                  | 94        | 1.34%   |
| AMD Ryzen 3             | 81        | 1.16%   |
| AMD E                   | 79        | 1.13%   |
| AMD E1                  | 74        | 1.06%   |
| Intel Pentium Dual      | 66        | 0.94%   |
| AMD A4                  | 64        | 0.92%   |
| Intel Atom              | 61        | 0.87%   |
| AMD A8                  | 60        | 0.86%   |
| AMD A10                 | 45        | 0.64%   |
| Intel Pentium Silver    | 42        | 0.6%    |
| AMD E2                  | 42        | 0.6%    |
| Intel Core 2            | 35        | 0.5%    |
| AMD Athlon              | 35        | 0.5%    |
| AMD C-60                | 30        | 0.43%   |
| Intel Genuine           | 27        | 0.39%   |
| Intel Celeron Dual-Core | 26        | 0.37%   |
| AMD Ryzen 9             | 24        | 0.34%   |
| AMD Turion 64 X2 Mobile | 16        | 0.23%   |
| AMD Athlon II           | 16        | 0.23%   |
| AMD Athlon X2           | 14        | 0.2%    |
| AMD Phenom II           | 13        | 0.19%   |
| AMD Ryzen 5 PRO         | 12        | 0.17%   |
| AMD C-70                | 11        | 0.16%   |
| AMD A12                 | 11        | 0.16%   |
| AMD Ryzen 7 PRO         | 9         | 0.13%   |
| AMD Athlon 64 X2        | 9         | 0.13%   |
| Intel Core m3           | 8         | 0.11%   |
| AMD Sempron             | 8         | 0.11%   |
| AMD FX                  | 8         | 0.11%   |
| Intel Pentium Gold      | 7         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4882      | 69.79%  |
| 4      | 1499      | 21.43%  |
| 6      | 211       | 3.02%   |
| 8      | 199       | 2.84%   |
| 1      | 157       | 2.24%   |
| 14     | 23        | 0.33%   |
| 10     | 9         | 0.13%   |
| 12     | 7         | 0.1%    |
| 3      | 4         | 0.06%   |
| 24     | 2         | 0.03%   |
| 16     | 1         | 0.01%   |
| 5      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6989      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4400      | 62.88%  |
| 1      | 2565      | 36.65%  |
| 4      | 17        | 0.24%   |
| 8      | 13        | 0.19%   |
| 12     | 2         | 0.03%   |
| 16     | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6986      | 99.96%  |
| Unknown        | 3         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1381      | 19.15%  |
| 0x206a7    | 713       | 9.88%   |
| 0x306a9    | 523       | 7.25%   |
| 0x1067a    | 345       | 4.78%   |
| 0x20655    | 275       | 3.81%   |
| 0x40651    | 249       | 3.45%   |
| 0x406e3    | 223       | 3.09%   |
| 0x306d4    | 213       | 2.95%   |
| 0x806e9    | 181       | 2.51%   |
| 0x6fd      | 170       | 2.36%   |
| 0x306c3    | 155       | 2.15%   |
| 0x806ea    | 144       | 2%      |
| 0x30678    | 142       | 1.97%   |
| 0x08108109 | 139       | 1.93%   |
| 0x806ec    | 127       | 1.76%   |
| 0x10676    | 125       | 1.73%   |
| 0x06006705 | 92        | 1.28%   |
| 0x806c1    | 91        | 1.26%   |
| 0x406c4    | 85        | 1.18%   |
| 0x20652    | 81        | 1.12%   |
| 0x706e5    | 76        | 1.05%   |
| 0x0500010d | 73        | 1.01%   |
| 0x906ea    | 71        | 0.98%   |
| 0x08608103 | 70        | 0.97%   |
| 0x07030105 | 69        | 0.96%   |
| 0x506e3    | 68        | 0.94%   |
| 0x506c9    | 68        | 0.94%   |
| 0x08108102 | 66        | 0.92%   |
| 0x706a1    | 63        | 0.87%   |
| 0x0a50000c | 56        | 0.78%   |
| 0x706a8    | 55        | 0.76%   |
| 0x08600106 | 44        | 0.61%   |
| 0x906e9    | 43        | 0.6%    |
| 0x406c3    | 39        | 0.54%   |
| 0x05000101 | 38        | 0.53%   |
| 0xa0652    | 37        | 0.51%   |
| 0x6fb      | 37        | 0.51%   |
| 0x08200103 | 32        | 0.44%   |
| 0x0700010b | 32        | 0.44%   |
| 0x0600611a | 31        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 824       | 11.78%  |
| KabyLake         | 770       | 11.01%  |
| IvyBridge        | 621       | 8.88%   |
| Penryn           | 550       | 7.87%   |
| Haswell          | 482       | 6.89%   |
| Westmere         | 425       | 6.08%   |
| Skylake          | 384       | 5.49%   |
| Silvermont       | 335       | 4.79%   |
| Core             | 321       | 4.59%   |
| Broadwell        | 267       | 3.82%   |
| Zen+             | 215       | 3.07%   |
| Bobcat           | 166       | 2.37%   |
| Goldmont plus    | 165       | 2.36%   |
| TigerLake        | 153       | 2.19%   |
| Excavator        | 151       | 2.16%   |
| Unknown          | 129       | 1.84%   |
| IceLake          | 114       | 1.63%   |
| Puma             | 103       | 1.47%   |
| Zen 2            | 98        | 1.4%    |
| Zen 3            | 90        | 1.29%   |
| Goldmont         | 82        | 1.17%   |
| Zen              | 74        | 1.06%   |
| CometLake        | 58        | 0.83%   |
| Jaguar           | 54        | 0.77%   |
| Piledriver       | 51        | 0.73%   |
| K10              | 50        | 0.72%   |
| Bonnell          | 45        | 0.64%   |
| K8 Hammer        | 43        | 0.61%   |
| Alderlake Hybrid | 43        | 0.61%   |
| K8 & K10 hybrid  | 31        | 0.44%   |
| K10 Llano        | 30        | 0.43%   |
| Nehalem          | 29        | 0.41%   |
| Tremont          | 23        | 0.33%   |
| Steamroller      | 14        | 0.2%    |
| Gracemont        | 3         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5116      | 61.83%  |
| AMD                              | 1699      | 20.53%  |
| Nvidia                           | 1451      | 17.54%  |
| Silicon Integrated Systems [SiS] | 8         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 765       | 8.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 581       | 6.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 380       | 4.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 306       | 3.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 292       | 3.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 253       | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 246       | 2.86%   |
| Intel HD Graphics 5500                                                                   | 232       | 2.7%    |
| Intel HD Graphics 620                                                                    | 230       | 2.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 188       | 2.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 173       | 2.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 173       | 2.01%   |
| Intel UHD Graphics 620                                                                   | 164       | 1.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 157       | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 147       | 1.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 136       | 1.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 109       | 1.27%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 109       | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 97        | 1.13%   |
| AMD Renoir                                                                               | 93        | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 88        | 1.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 82        | 0.95%   |
| AMD Lucienne                                                                             | 81        | 0.94%   |
| Intel HD Graphics 530                                                                    | 76        | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 72        | 0.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 71        | 0.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 70        | 0.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 68        | 0.79%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 68        | 0.79%   |
| Intel HD Graphics 500                                                                    | 60        | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 54        | 0.63%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 53        | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 48        | 0.56%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 48        | 0.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 48        | 0.56%   |
| Intel HD Graphics 630                                                                    | 47        | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 46        | 0.54%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 46        | 0.54%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 43        | 0.5%    |
| Nvidia GF108M [GeForce GT 540M]                                                          | 42        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 3739      | 53.29%  |
| 1 x AMD        | 1252      | 17.84%  |
| Intel + Nvidia | 968       | 13.8%   |
| 1 x Nvidia     | 392       | 5.59%   |
| Intel + AMD    | 230       | 3.28%   |
| 2 x Intel      | 202       | 2.88%   |
| 2 x AMD        | 132       | 1.88%   |
| AMD + Nvidia   | 86        | 1.23%   |
| 1 x SiS        | 8         | 0.11%   |
| 2 x Nvidia     | 7         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6904      | 98.56%  |
| Unknown     | 68        | 0.97%   |
| Proprietary | 33        | 0.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4101      | 58.48%  |
| 0.01-0.5   | 1128      | 16.08%  |
| 1.01-2.0   | 801       | 11.42%  |
| 0.51-1.0   | 563       | 8.03%   |
| 3.01-4.0   | 269       | 3.84%   |
| 5.01-6.0   | 77        | 1.1%    |
| 7.01-8.0   | 48        | 0.68%   |
| 2.01-3.0   | 19        | 0.27%   |
| 8.01-16.0  | 7         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1497      | 20.71%  |
| LG Display              | 1218      | 16.85%  |
| Chimei Innolux          | 1000      | 13.83%  |
| BOE                     | 965       | 13.35%  |
| Samsung Electronics     | 856       | 11.84%  |
| Chi Mei Optoelectronics | 257       | 3.55%   |
| Lenovo                  | 178       | 2.46%   |
| CPT                     | 147       | 2.03%   |
| Apple                   | 125       | 1.73%   |
| LG Philips              | 108       | 1.49%   |
| Sharp                   | 85        | 1.18%   |
| PANDA                   | 66        | 0.91%   |
| Dell                    | 66        | 0.91%   |
| InfoVision              | 65        | 0.9%    |
| Eizo                    | 61        | 0.84%   |
| Goldstar                | 60        | 0.83%   |
| Acer                    | 44        | 0.61%   |
| Hewlett-Packard         | 41        | 0.57%   |
| Sony                    | 31        | 0.43%   |
| AOC                     | 31        | 0.43%   |
| Philips                 | 28        | 0.39%   |
| BenQ                    | 20        | 0.28%   |
| Toshiba                 | 18        | 0.25%   |
| InnoLux Display         | 17        | 0.24%   |
| CSO                     | 17        | 0.24%   |
| Panasonic               | 15        | 0.21%   |
| HannStar                | 15        | 0.21%   |
| Ancor Communications    | 14        | 0.19%   |
| Iiyama                  | 13        | 0.18%   |
| ASUSTek Computer        | 13        | 0.18%   |
| ViewSonic               | 12        | 0.17%   |
| Unknown                 | 10        | 0.14%   |
| KDC                     | 8         | 0.11%   |
| HKC                     | 7         | 0.1%    |
| Vizio                   | 6         | 0.08%   |
| Quanta Display          | 6         | 0.08%   |
| Hitachi                 | 6         | 0.08%   |
| Vestel Elektronik       | 5         | 0.07%   |
| IBM                     | 5         | 0.07%   |
| Fujitsu Siemens         | 5         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 125       | 1.72%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 76        | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 73        | 1.01%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 69        | 0.95%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 61        | 0.84%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 59        | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 58        | 0.8%    |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 57        | 0.79%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 50        | 0.69%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 50        | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 39        | 0.54%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 38        | 0.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 37        | 0.51%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 37        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 32        | 0.44%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 32        | 0.44%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 31        | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 31        | 0.43%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 30        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 29        | 0.4%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 29        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 28        | 0.39%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 28        | 0.39%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 26        | 0.36%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 26        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 25        | 0.34%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 25        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 24        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 24        | 0.33%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 24        | 0.33%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 24        | 0.33%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 24        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 23        | 0.32%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 23        | 0.32%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 23        | 0.32%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 23        | 0.32%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 21        | 0.29%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 21        | 0.29%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 20        | 0.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 20        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 3128      | 44.03%  |
| 1920x1080 (FHD)    | 2134      | 30.04%  |
| 1600x900 (HD+)     | 608       | 8.56%   |
| 1280x800 (WXGA)    | 404       | 5.69%   |
| 3840x2160 (4K)     | 177       | 2.49%   |
| 1440x900 (WXGA+)   | 177       | 2.49%   |
| 1920x1200 (WUXGA)  | 75        | 1.06%   |
| 2560x1440 (QHD)    | 69        | 0.97%   |
| 2560x1600          | 57        | 0.8%    |
| 1680x1050 (WSXGA+) | 55        | 0.77%   |
| 2880x1800          | 23        | 0.32%   |
| 1024x600           | 22        | 0.31%   |
| 3200x1800 (QHD+)   | 20        | 0.28%   |
| 1280x1024 (SXGA)   | 18        | 0.25%   |
| 2160x1440          | 15        | 0.21%   |
| 1360x768           | 14        | 0.2%    |
| 1024x768 (XGA)     | 12        | 0.17%   |
| 1680x945           | 11        | 0.15%   |
| 1920x540           | 10        | 0.14%   |
| 2288x1287          | 9         | 0.13%   |
| 3840x2400          | 8         | 0.11%   |
| 2560x1080          | 8         | 0.11%   |
| 2256x1504          | 7         | 0.1%    |
| 3440x1440          | 6         | 0.08%   |
| 1920x1280          | 6         | 0.08%   |
| 1400x1050          | 4         | 0.06%   |
| 800x1280           | 3         | 0.04%   |
| 3456x2160          | 3         | 0.04%   |
| 2240x1400          | 3         | 0.04%   |
| 3200x2000          | 2         | 0.03%   |
| 1152x864           | 2         | 0.03%   |
| 3840x1100          | 1         | 0.01%   |
| 3840x1080          | 1         | 0.01%   |
| 3300x2200          | 1         | 0.01%   |
| 3072x1920          | 1         | 0.01%   |
| 3000x2000          | 1         | 0.01%   |
| 2880x1920          | 1         | 0.01%   |
| 2560x1700          | 1         | 0.01%   |
| 2304x1440          | 1         | 0.01%   |
| 2160x1350          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3371      | 46.57%  |
| 13      | 1119      | 15.46%  |
| 14      | 842       | 11.63%  |
| 17      | 693       | 9.57%   |
| 12      | 237       | 3.27%   |
| 11      | 171       | 2.36%   |
| 23      | 104       | 1.44%   |
| 31      | 93        | 1.28%   |
| 27      | 87        | 1.2%    |
| 24      | 67        | 0.93%   |
| 18      | 66        | 0.91%   |
| 21      | 63        | 0.87%   |
| 16      | 58        | 0.8%    |
| 10      | 34        | 0.47%   |
| 19      | 29        | 0.4%    |
| 20      | 26        | 0.36%   |
| 54      | 17        | 0.23%   |
| 22      | 16        | 0.22%   |
| 84      | 15        | 0.21%   |
| 26      | 15        | 0.21%   |
| Unknown | 14        | 0.19%   |
| 34      | 12        | 0.17%   |
| 72      | 11        | 0.15%   |
| 32      | 11        | 0.15%   |
| 40      | 8         | 0.11%   |
| 142     | 7         | 0.1%    |
| 65      | 6         | 0.08%   |
| 25      | 6         | 0.08%   |
| 39      | 5         | 0.07%   |
| 52      | 4         | 0.06%   |
| 48      | 4         | 0.06%   |
| 46      | 4         | 0.06%   |
| 37      | 3         | 0.04%   |
| 7       | 3         | 0.04%   |
| 74      | 2         | 0.03%   |
| 55      | 2         | 0.03%   |
| 42      | 2         | 0.03%   |
| 36      | 2         | 0.03%   |
| 85      | 1         | 0.01%   |
| 60      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 4697      | 65.06%  |
| 201-300        | 993       | 13.76%  |
| 351-400        | 842       | 11.66%  |
| 501-600        | 257       | 3.56%   |
| 401-500        | 188       | 2.6%    |
| 601-700        | 103       | 1.43%   |
| 1001-1500      | 40        | 0.55%   |
| 1501-2000      | 29        | 0.4%    |
| 701-800        | 26        | 0.36%   |
| 801-900        | 17        | 0.24%   |
| Unknown        | 14        | 0.19%   |
| More than 2000 | 7         | 0.1%    |
| 1-100          | 3         | 0.04%   |
| 901-1000       | 2         | 0.03%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 5869      | 86.33%  |
| 16/10   | 799       | 11.75%  |
| 3/2     | 54        | 0.79%   |
| 4/3     | 22        | 0.32%   |
| 5/4     | 21        | 0.31%   |
| 21/9    | 13        | 0.19%   |
| 1.00    | 7         | 0.1%    |
| 32/9    | 4         | 0.06%   |
| 0.67    | 3         | 0.04%   |
| Unknown | 2         | 0.03%   |
| 3.40    | 1         | 0.01%   |
| 2.65    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3370      | 46.56%  |
| 81-90          | 1487      | 20.54%  |
| 121-130        | 568       | 7.85%   |
| 71-80          | 472       | 6.52%   |
| 61-70          | 229       | 3.16%   |
| 201-250        | 218       | 3.01%   |
| 51-60          | 173       | 2.39%   |
| 351-500        | 120       | 1.66%   |
| 131-140        | 119       | 1.64%   |
| 301-350        | 94        | 1.3%    |
| 151-200        | 72        | 0.99%   |
| More than 1000 | 70        | 0.97%   |
| 141-150        | 69        | 0.95%   |
| 111-120        | 44        | 0.61%   |
| 41-50          | 34        | 0.47%   |
| 251-300        | 32        | 0.44%   |
| 501-1000       | 26        | 0.36%   |
| 91-100         | 23        | 0.32%   |
| Unknown        | 14        | 0.19%   |
| 1-40           | 4         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 3174      | 44.57%  |
| 121-160       | 2420      | 33.98%  |
| 51-100        | 1040      | 14.6%   |
| 161-240       | 330       | 4.63%   |
| More than 240 | 81        | 1.14%   |
| 1-50          | 62        | 0.87%   |
| Unknown       | 14        | 0.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6385      | 90.93%  |
| 2     | 590       | 8.4%    |
| 0     | 36        | 0.51%   |
| 3     | 9         | 0.13%   |
| 4     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3765      | 33.19%  |
| Intel                             | 3103      | 27.36%  |
| Qualcomm Atheros                  | 2260      | 19.92%  |
| Broadcom                          | 769       | 6.78%   |
| Broadcom Limited                  | 195       | 1.72%   |
| Marvell Technology Group          | 185       | 1.63%   |
| Samsung Electronics               | 149       | 1.31%   |
| Ralink                            | 140       | 1.23%   |
| MediaTek                          | 94        | 0.83%   |
| JMicron Technology                | 70        | 0.62%   |
| Dell                              | 65        | 0.57%   |
| TP-Link                           | 52        | 0.46%   |
| Huawei Technologies               | 52        | 0.46%   |
| Ericsson Business Mobile Networks | 49        | 0.43%   |
| Ralink Technology                 | 48        | 0.42%   |
| Nvidia                            | 41        | 0.36%   |
| ASIX Electronics                  | 37        | 0.33%   |
| Sierra Wireless                   | 32        | 0.28%   |
| Hewlett-Packard                   | 20        | 0.18%   |
| Xiaomi                            | 18        | 0.16%   |
| Qualcomm Atheros Communications   | 15        | 0.13%   |
| DisplayLink                       | 14        | 0.12%   |
| D-Link                            | 13        | 0.11%   |
| NetGear                           | 11        | 0.1%    |
| Motorola PCS                      | 10        | 0.09%   |
| Linksys                           | 10        | 0.09%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.08%   |
| Qualcomm                          | 9         | 0.08%   |
| ASUSTek Computer                  | 8         | 0.07%   |
| OPPO Electronics                  | 7         | 0.06%   |
| T & A Mobile Phones               | 6         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.05%   |
| ICS Advent                        | 6         | 0.05%   |
| D-Link System                     | 6         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.04%   |
| Lenovo                            | 5         | 0.04%   |
| Edimax Technology                 | 5         | 0.04%   |
| Belkin Components                 | 5         | 0.04%   |
| Apple                             | 5         | 0.04%   |
| Attansic Technology               | 4         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2113      | 15.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 932       | 6.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 415       | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 402       | 2.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 358       | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 340       | 2.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 312       | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 231       | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 224       | 1.66%   |
| Intel Wireless 7265                                                     | 222       | 1.64%   |
| Intel Wireless 8265 / 8275                                              | 178       | 1.32%   |
| Intel Wireless 7260                                                     | 176       | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 169       | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 157       | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 157       | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 153       | 1.13%   |
| Intel Wireless 8260                                                     | 150       | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 148       | 1.09%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 140       | 1.03%   |
| Intel Wi-Fi 6 AX200                                                     | 135       | 1%      |
| Intel Wireless 3165                                                     | 129       | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 123       | 0.91%   |
| Intel WiFi Link 5100                                                    | 115       | 0.85%   |
| Intel Wireless 3160                                                     | 112       | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 111       | 0.82%   |
| Intel 82577LM Gigabit Network Connection                                | 106       | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 105       | 0.78%   |
| Intel Wi-Fi 6 AX201                                                     | 102       | 0.75%   |
| Intel 82567LM Gigabit Network Connection                                | 97        | 0.72%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 95        | 0.7%    |
| Intel Centrino Advanced-N 6200                                          | 92        | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 88        | 0.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 83        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 82        | 0.61%   |
| Intel Centrino Ultimate-N 6300                                          | 82        | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 79        | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 76        | 0.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 76        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                   | 74        | 0.55%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 73        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2951      | 41.03%  |
| Qualcomm Atheros                      | 1977      | 27.49%  |
| Realtek Semiconductor                 | 1214      | 16.88%  |
| Broadcom                              | 510       | 7.09%   |
| Ralink                                | 140       | 1.95%   |
| Broadcom Limited                      | 92        | 1.28%   |
| MediaTek                              | 84        | 1.17%   |
| Ralink Technology                     | 48        | 0.67%   |
| Dell                                  | 34        | 0.47%   |
| Sierra Wireless                       | 32        | 0.44%   |
| TP-Link                               | 20        | 0.28%   |
| Qualcomm Atheros Communications       | 15        | 0.21%   |
| D-Link                                | 9         | 0.13%   |
| Linksys                               | 8         | 0.11%   |
| Ericsson Business Mobile Networks     | 8         | 0.11%   |
| NetGear                               | 6         | 0.08%   |
| Hewlett-Packard                       | 6         | 0.08%   |
| D-Link System                         | 6         | 0.08%   |
| ASUSTek Computer                      | 6         | 0.08%   |
| Edimax Technology                     | 5         | 0.07%   |
| Belkin Components                     | 4         | 0.06%   |
| Qcom                                  | 3         | 0.04%   |
| AVM                                   | 3         | 0.04%   |
| Qualcomm                              | 2         | 0.03%   |
| Fibocom                               | 2         | 0.03%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Senao                                 | 1         | 0.01%   |
| PLANEX                                | 1         | 0.01%   |
| Microsoft                             | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Elecom                                | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 415       | 5.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 402       | 5.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 358       | 4.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 340       | 4.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 231       | 3.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 224       | 3.11%   |
| Intel Wireless 7265                                                     | 222       | 3.08%   |
| Intel Wireless 8265 / 8275                                              | 178       | 2.47%   |
| Intel Wireless 7260                                                     | 176       | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 169       | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 157       | 2.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 153       | 2.12%   |
| Intel Wireless 8260                                                     | 150       | 2.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 148       | 2.05%   |
| Intel Wi-Fi 6 AX200                                                     | 135       | 1.87%   |
| Intel Wireless 3165                                                     | 129       | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 123       | 1.71%   |
| Intel WiFi Link 5100                                                    | 115       | 1.59%   |
| Intel Wireless 3160                                                     | 112       | 1.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 105       | 1.46%   |
| Intel Wi-Fi 6 AX201                                                     | 102       | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 95        | 1.32%   |
| Intel Centrino Advanced-N 6200                                          | 92        | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 88        | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 83        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 82        | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 82        | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 79        | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 76        | 1.05%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 76        | 1.05%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 73        | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 71        | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 67        | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 64        | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 64        | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 64        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 63        | 0.87%   |
| Intel Centrino Wireless-N 2230                                          | 62        | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 59        | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 54        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3278      | 53.19%  |
| Intel                            | 1142      | 18.53%  |
| Qualcomm Atheros                 | 570       | 9.25%   |
| Broadcom                         | 371       | 6.02%   |
| Marvell Technology Group         | 185       | 3%      |
| Samsung Electronics              | 149       | 2.42%   |
| Broadcom Limited                 | 107       | 1.74%   |
| JMicron Technology               | 70        | 1.14%   |
| Huawei Technologies              | 44        | 0.71%   |
| Nvidia                           | 40        | 0.65%   |
| ASIX Electronics                 | 37        | 0.6%    |
| TP-Link                          | 32        | 0.52%   |
| Xiaomi                           | 18        | 0.29%   |
| DisplayLink                      | 14        | 0.23%   |
| MediaTek                         | 10        | 0.16%   |
| Silicon Integrated Systems [SiS] | 9         | 0.15%   |
| Motorola PCS                     | 8         | 0.13%   |
| Qualcomm                         | 7         | 0.11%   |
| OPPO Electronics                 | 7         | 0.11%   |
| OnePlus Technology (Shenzhen)    | 6         | 0.1%    |
| ICS Advent                       | 6         | 0.1%    |
| ZTE WCDMA Technologies MSM       | 5         | 0.08%   |
| NetGear                          | 5         | 0.08%   |
| Lenovo                           | 5         | 0.08%   |
| Hewlett-Packard                  | 5         | 0.08%   |
| Apple                            | 5         | 0.08%   |
| D-Link                           | 4         | 0.06%   |
| Attansic Technology              | 4         | 0.06%   |
| Google                           | 3         | 0.05%   |
| vivo                             | 2         | 0.03%   |
| T & A Mobile Phones              | 2         | 0.03%   |
| Spreadtrum Communications        | 2         | 0.03%   |
| Linksys                          | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| Sitecom Europe                   | 1         | 0.02%   |
| LG Electronics                   | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| HMD Global                       | 1         | 0.02%   |
| Belkin Components                | 1         | 0.02%   |
| Archos                           | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2113      | 34.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 932       | 15.02%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 312       | 5.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 157       | 2.53%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 140       | 2.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 111       | 1.79%   |
| Intel 82577LM Gigabit Network Connection                                       | 106       | 1.71%   |
| Intel 82567LM Gigabit Network Connection                                       | 97        | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                                          | 74        | 1.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 70        | 1.13%   |
| Intel Ethernet Connection I218-LM                                              | 68        | 1.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 65        | 1.05%   |
| Intel Ethernet Connection I219-LM                                              | 64        | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                                          | 63        | 1.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 59        | 0.95%   |
| Intel Ethernet Connection I217-LM                                              | 57        | 0.92%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 56        | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 55        | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 52        | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 46        | 0.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 46        | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 41        | 0.66%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 41        | 0.66%   |
| Intel 82566MM Gigabit Network Connection                                       | 38        | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 37        | 0.6%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 37        | 0.6%    |
| Huawei E353/E3131                                                              | 36        | 0.58%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 34        | 0.55%   |
| Intel 82579V Gigabit Network Connection                                        | 33        | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 33        | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 31        | 0.5%    |
| Intel Ethernet Connection I219-V                                               | 30        | 0.48%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 29        | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 29        | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 29        | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 28        | 0.45%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 27        | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 26        | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 26        | 0.42%   |
| Intel Ethernet Connection (4) I219-V                                           | 26        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6931      | 53.1%   |
| Ethernet | 6007      | 46.02%  |
| Modem    | 100       | 0.77%   |
| Unknown  | 14        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4834      | 70.2%   |
| Ethernet | 2051      | 29.79%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5487      | 78.49%  |
| 1     | 1403      | 20.07%  |
| 0     | 80        | 1.14%   |
| 3     | 21        | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5017      | 70.83%  |
| Yes  | 2066      | 29.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1920      | 38.11%  |
| Qualcomm Atheros Communications | 603       | 11.97%  |
| Realtek Semiconductor           | 578       | 11.47%  |
| Broadcom                        | 372       | 7.38%   |
| Lite-On Technology              | 329       | 6.53%   |
| IMC Networks                    | 262       | 5.2%    |
| Foxconn / Hon Hai               | 221       | 4.39%   |
| Dell                            | 132       | 2.62%   |
| Apple                           | 111       | 2.2%    |
| Toshiba                         | 110       | 2.18%   |
| Hewlett-Packard                 | 102       | 2.02%   |
| Cambridge Silicon Radio         | 67        | 1.33%   |
| Ralink                          | 59        | 1.17%   |
| Realtek                         | 27        | 0.54%   |
| ASUSTek Computer                | 26        | 0.52%   |
| Alps Electric                   | 21        | 0.42%   |
| Foxconn International           | 20        | 0.4%    |
| Ralink Technology               | 14        | 0.28%   |
| Chicony Electronics             | 13        | 0.26%   |
| Askey Computer                  | 12        | 0.24%   |
| Fujitsu                         | 7         | 0.14%   |
| Taiyo Yuden                     | 6         | 0.12%   |
| MediaTek                        | 6         | 0.12%   |
| Micro Star International        | 4         | 0.08%   |
| USI                             | 3         | 0.06%   |
| TP-Link                         | 3         | 0.06%   |
| Smart Modular Technologies      | 2         | 0.04%   |
| Edimax Technology               | 2         | 0.04%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 996       | 19.77%  |
| Realtek Bluetooth Radio                                                             | 398       | 7.9%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 269       | 5.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 263       | 5.22%   |
| Intel AX201 Bluetooth                                                               | 201       | 3.99%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 137       | 2.72%   |
| Intel AX200 Bluetooth                                                               | 133       | 2.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 118       | 2.34%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 114       | 2.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 108       | 2.14%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 106       | 2.1%    |
| Intel Bluetooth Device                                                              | 106       | 2.1%    |
| IMC Networks Bluetooth Radio                                                        | 90        | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 88        | 1.75%   |
| IMC Networks Bluetooth Device                                                       | 80        | 1.59%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 79        | 1.57%   |
| Lite-On Bluetooth Device                                                            | 68        | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 68        | 1.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 67        | 1.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 65        | 1.29%   |
| Apple Bluetooth Host Controller                                                     | 60        | 1.19%   |
| Ralink RT3290 Bluetooth                                                             | 59        | 1.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 59        | 1.17%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 58        | 1.15%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 58        | 1.15%   |
| Dell DW375 Bluetooth Module                                                         | 58        | 1.15%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 45        | 0.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 42        | 0.83%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 41        | 0.81%   |
| Toshiba Bluetooth Device                                                            | 35        | 0.69%   |
| Apple Bluetooth USB Host Controller                                                 | 35        | 0.69%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 33        | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 32        | 0.64%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 32        | 0.64%   |
| Intel AX210 Bluetooth                                                               | 29        | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 28        | 0.56%   |
| Broadcom HP Portable SoftSailing                                                    | 26        | 0.52%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 25        | 0.5%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 25        | 0.5%    |
| Toshiba RT Bluetooth Radio                                                          | 24        | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5655      | 70.36%  |
| AMD                                          | 1449      | 18.03%  |
| Nvidia                                       | 777       | 9.67%   |
| C-Media Electronics                          | 20        | 0.25%   |
| Logitech                                     | 12        | 0.15%   |
| Generalplus Technology                       | 12        | 0.15%   |
| Realtek Semiconductor                        | 11        | 0.14%   |
| Silicon Integrated Systems [SiS]             | 9         | 0.11%   |
| JMTek                                        | 8         | 0.1%    |
| Creative Technology                          | 8         | 0.1%    |
| GN Netcom                                    | 7         | 0.09%   |
| Apple                                        | 7         | 0.09%   |
| Texas Instruments                            | 6         | 0.07%   |
| Lenovo                                       | 6         | 0.07%   |
| ASUSTek Computer                             | 4         | 0.05%   |
| Plantronics                                  | 3         | 0.04%   |
| Focusrite-Novation                           | 3         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.02%   |
| Razer USA                                    | 2         | 0.02%   |
| No brand                                     | 2         | 0.02%   |
| M-Audio                                      | 2         | 0.02%   |
| Corsair                                      | 2         | 0.02%   |
| Conexant Systems                             | 2         | 0.02%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.01%   |
| Yamaha                                       | 1         | 0.01%   |
| XMOS                                         | 1         | 0.01%   |
| VIA Technologies                             | 1         | 0.01%   |
| TTGK Technology                              | 1         | 0.01%   |
| THX                                          | 1         | 0.01%   |
| TerraTec Electronic                          | 1         | 0.01%   |
| Tenx Technology                              | 1         | 0.01%   |
| TEAC                                         | 1         | 0.01%   |
| Schiit Audio                                 | 1         | 0.01%   |
| SAVITECH                                     | 1         | 0.01%   |
| Samsung Electronics                          | 1         | 0.01%   |
| Samson Technologies                          | 1         | 0.01%   |
| RODE Microphones                             | 1         | 0.01%   |
| PreSonus Audio Electronics                   | 1         | 0.01%   |
| Phison Electronics                           | 1         | 0.01%   |
| Nordic Semiconductor ASA                     | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 782       | 7.9%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 712       | 7.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 663       | 6.7%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 567       | 5.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 504       | 5.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 454       | 4.59%   |
| AMD FCH Azalia Controller                                                                         | 313       | 3.16%   |
| Intel 8 Series HD Audio Controller                                                                | 296       | 2.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 293       | 2.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 279       | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 269       | 2.72%   |
| Intel Broadwell-U Audio Controller                                                                | 267       | 2.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 266       | 2.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 225       | 2.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 203       | 2.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 199       | 2.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 187       | 1.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 187       | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 164       | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 161       | 1.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 153       | 1.55%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 151       | 1.53%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 145       | 1.46%   |
| AMD Wrestler HDMI Audio                                                                           | 138       | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 137       | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 111       | 1.12%   |
| AMD High Definition Audio Controller                                                              | 109       | 1.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 97        | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 93        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 90        | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 88        | 0.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 82        | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 82        | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 71        | 0.72%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 61        | 0.62%   |
| Intel CM238 HD Audio Controller                                                                   | 59        | 0.6%    |
| Nvidia High Definition Audio Controller                                                           | 51        | 0.52%   |
| AMD Trinity HDMI Audio Controller                                                                 | 51        | 0.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 50        | 0.5%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 48        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2238      | 26.31%  |
| SK hynix            | 1784      | 20.97%  |
| Micron Technology   | 859       | 10.1%   |
| Kingston            | 755       | 8.88%   |
| Unknown             | 720       | 8.46%   |
| Elpida              | 354       | 4.16%   |
| Crucial             | 282       | 3.31%   |
| Ramaxel Technology  | 223       | 2.62%   |
| A-DATA Technology   | 198       | 2.33%   |
| Nanya Technology    | 176       | 2.07%   |
| Smart               | 134       | 1.58%   |
| Unknown (ABCD)      | 93        | 1.09%   |
| Corsair             | 81        | 0.95%   |
| Unknown             | 51        | 0.6%    |
| G.Skill             | 41        | 0.48%   |
| Teikon              | 36        | 0.42%   |
| Transcend           | 31        | 0.36%   |
| ASint Technology    | 30        | 0.35%   |
| Patriot             | 29        | 0.34%   |
| Team                | 28        | 0.33%   |
| High Bridge         | 24        | 0.28%   |
| Apacer              | 22        | 0.26%   |
| AMD                 | 20        | 0.24%   |
| Toshiba             | 19        | 0.22%   |
| Smart Brazil        | 19        | 0.22%   |
| GOODRAM             | 19        | 0.22%   |
| Qimonda             | 15        | 0.18%   |
| Avant               | 12        | 0.14%   |
| 48spaces            | 11        | 0.13%   |
| CSX                 | 10        | 0.12%   |
| PNY                 | 9         | 0.11%   |
| Timetec             | 8         | 0.09%   |
| SHARETRONIC         | 8         | 0.09%   |
| Multilaser          | 8         | 0.09%   |
| Silicon Power       | 7         | 0.08%   |
| Neo Forza           | 7         | 0.08%   |
| Kingmax             | 7         | 0.08%   |
| Goldkey             | 7         | 0.08%   |
| V-GeN               | 6         | 0.07%   |
| Sesame              | 5         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 157       | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 155       | 1.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 142       | 1.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 139       | 1.52%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 128       | 1.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 125       | 1.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 119       | 1.3%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 117       | 1.28%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 110       | 1.21%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 107       | 1.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 86        | 0.94%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 85        | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 82        | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 67        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 64        | 0.7%    |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 64        | 0.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 61        | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 57        | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 56        | 0.61%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 55        | 0.6%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 55        | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 55        | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 55        | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 54        | 0.59%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 53        | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 52        | 0.57%   |
| Unknown                                                          | 51        | 0.56%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 49        | 0.54%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 48        | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 47        | 0.52%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 47        | 0.52%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 46        | 0.5%    |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 41        | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 41        | 0.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 40        | 0.44%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 39        | 0.43%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 39        | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 38        | 0.42%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 36        | 0.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 35        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 3599      | 51.14%  |
| DDR4    | 2040      | 28.99%  |
| DDR2    | 653       | 9.28%   |
| LPDDR4  | 255       | 3.62%   |
| SDRAM   | 244       | 3.47%   |
| Unknown | 79        | 1.12%   |
| LPDDR3  | 70        | 0.99%   |
| DRAM    | 30        | 0.43%   |
| DDR5    | 26        | 0.37%   |
| DDR     | 24        | 0.34%   |
| LPDDR5  | 17        | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 6576      | 94.33%  |
| Row Of Chips | 312       | 4.48%   |
| DIMM         | 31        | 0.44%   |
| Chip         | 26        | 0.37%   |
| Unknown      | 26        | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 3194      | 40.19%  |
| 8192  | 2162      | 27.2%   |
| 2048  | 1752      | 22.04%  |
| 16384 | 403       | 5.07%   |
| 1024  | 304       | 3.82%   |
| 32768 | 119       | 1.5%    |
| 512   | 14        | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 2307      | 29.43%  |
| 2667    | 1008      | 12.86%  |
| 1334    | 722       | 9.21%   |
| 3200    | 721       | 9.2%    |
| 1333    | 545       | 6.95%   |
| 2400    | 491       | 6.26%   |
| 667     | 349       | 4.45%   |
| 1067    | 234       | 2.99%   |
| 2133    | 215       | 2.74%   |
| Unknown | 203       | 2.59%   |
| 800     | 191       | 2.44%   |
| 4199    | 140       | 1.79%   |
| 3266    | 119       | 1.52%   |
| 2048    | 91        | 1.16%   |
| 975     | 89        | 1.14%   |
| 1867    | 74        | 0.94%   |
| 1066    | 74        | 0.94%   |
| 533     | 56        | 0.71%   |
| 4267    | 47        | 0.6%    |
| 4800    | 26        | 0.33%   |
| 4266    | 26        | 0.33%   |
| 8400    | 18        | 0.23%   |
| 1866    | 18        | 0.23%   |
| 6400    | 16        | 0.2%    |
| 3733    | 14        | 0.18%   |
| 333     | 12        | 0.15%   |
| 1639    | 9         | 0.11%   |
| 2933    | 6         | 0.08%   |
| 400     | 3         | 0.04%   |
| 3000    | 2         | 0.03%   |
| 2267    | 2         | 0.03%   |
| 266     | 2         | 0.03%   |
| 5600    | 1         | 0.01%   |
| 5500    | 1         | 0.01%   |
| 1776    | 1         | 0.01%   |
| 1596    | 1         | 0.01%   |
| 1200    | 1         | 0.01%   |
| 933     | 1         | 0.01%   |
| 666     | 1         | 0.01%   |
| 200     | 1         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 29        | 38.67%  |
| Canon                 | 17        | 22.67%  |
| Brother Industries    | 11        | 14.67%  |
| Samsung Electronics   | 8         | 10.67%  |
| Seiko Epson           | 5         | 6.67%   |
| Xerox                 | 2         | 2.67%   |
| Prolific Technology   | 2         | 2.67%   |
| Lexmark International | 1         | 1.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Brother DCP-7055W                       | 4         | 5.26%   |
| Samsung ML-1640 Series Laser Printer    | 3         | 3.95%   |
| HP Deskjet 2050 J510                    | 3         | 3.95%   |
| Prolific PL2305 Parallel Port           | 2         | 2.63%   |
| HP LaserJet 1020                        | 2         | 2.63%   |
| HP ENVY Photo 6200 series               | 2         | 2.63%   |
| HP DeskJet 3630 series                  | 2         | 2.63%   |
| HP DeskJet 2600 series                  | 2         | 2.63%   |
| Canon TR8500 series                     | 2         | 2.63%   |
| Canon PIXMA MG3600 Series               | 2         | 2.63%   |
| Canon PIXMA MG2500 Series               | 2         | 2.63%   |
| Canon LBP2900                           | 2         | 2.63%   |
| Xerox WorkCentre 6025                   | 1         | 1.32%   |
| Xerox Phaser 6000B                      | 1         | 1.32%   |
| Seiko Epson L360 Series                 | 1         | 1.32%   |
| Seiko Epson L355 Series                 | 1         | 1.32%   |
| Seiko Epson L310 Series                 | 1         | 1.32%   |
| Seiko Epson L210 Series                 | 1         | 1.32%   |
| Seiko Epson ET-2710 Series              | 1         | 1.32%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 1.32%   |
| Samsung SCX-3400 Series                 | 1         | 1.32%   |
| Samsung ML-2010P Mono Laser Printer     | 1         | 1.32%   |
| Samsung M2070 Series                    | 1         | 1.32%   |
| Samsung CLP-325 Color Laser Printer     | 1         | 1.32%   |
| Lexmark International E360d             | 1         | 1.32%   |
| HP OfficeJet Pro 69                     | 1         | 1.32%   |
| HP OfficeJet 6950                       | 1         | 1.32%   |
| HP OfficeJet 4300                       | 1         | 1.32%   |
| HP LaserJet P1102                       | 1         | 1.32%   |
| HP LaserJet M14-M17                     | 1         | 1.32%   |
| HP LaserJet 3055                        | 1         | 1.32%   |
| HP LaserJet 200 colorMFP M275nw         | 1         | 1.32%   |
| HP LaserJet 1018                        | 1         | 1.32%   |
| HP ENVY 6000 series                     | 1         | 1.32%   |
| HP ENVY 4520 series                     | 1         | 1.32%   |
| HP Deskjet F4500 series                 | 1         | 1.32%   |
| HP DeskJet D1360                        | 1         | 1.32%   |
| HP DeskJet 6122                         | 1         | 1.32%   |
| HP DeskJet 5820 series                  | 1         | 1.32%   |
| HP DeskJet 3700 series                  | 1         | 1.32%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 44.44%  |
| Seiko Epson     | 3         | 33.33%  |
| Hewlett-Packard | 2         | 22.22%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| HP ScanJet 5590                                          | 2         | 22.22%  |
| Canon CanoScan LiDE 110                                  | 2         | 22.22%  |
| Seiko Epson Scanner                                      | 1         | 11.11%  |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 11.11%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 11.11%  |
| Canon CanoScan LiDE 600F                                 | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1610      | 27.36%  |
| Realtek Semiconductor                  | 502       | 8.53%   |
| IMC Networks                           | 497       | 8.45%   |
| Microdia                               | 477       | 8.11%   |
| Suyin                                  | 378       | 6.42%   |
| Bison Electronics                      | 348       | 5.91%   |
| Sunplus Innovation Technology          | 291       | 4.94%   |
| Quanta                                 | 258       | 4.38%   |
| Cheng Uei Precision Industry (Foxlink) | 242       | 4.11%   |
| Syntek                                 | 197       | 3.35%   |
| Silicon Motion                         | 124       | 2.11%   |
| Lite-On Technology                     | 115       | 1.95%   |
| Ricoh                                  | 106       | 1.8%    |
| Alcor Micro                            | 100       | 1.7%    |
| Acer                                   | 97        | 1.65%   |
| Apple                                  | 94        | 1.6%    |
| Lenovo                                 | 61        | 1.04%   |
| Luxvisions Innotech Limited            | 56        | 0.95%   |
| Importek                               | 50        | 0.85%   |
| ALi                                    | 42        | 0.71%   |
| Primax Electronics                     | 37        | 0.63%   |
| Z-Star Microelectronics                | 20        | 0.34%   |
| OmniVision Technologies                | 20        | 0.34%   |
| Sonix Technology                       | 19        | 0.32%   |
| DigiTech                               | 19        | 0.32%   |
| Logitech                               | 17        | 0.29%   |
| Samsung Electronics                    | 12        | 0.2%    |
| Sunplus Technology                     | 8         | 0.14%   |
| icSpring                               | 8         | 0.14%   |
| Intel                                  | 7         | 0.12%   |
| SunplusIT                              | 6         | 0.1%    |
| HRY                                    | 6         | 0.1%    |
| Genesys Logic                          | 6         | 0.1%    |
| Y Media                                | 4         | 0.07%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.07%   |
| Foxconn / Hon Hai                      | 4         | 0.07%   |
| Cubeternet                             | 4         | 0.07%   |
| Tripath Technology                     | 3         | 0.05%   |
| Nebraska Furniture Mart                | 3         | 0.05%   |
| GEMBIRD                                | 3         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 214       | 3.63%   |
| Chicony HD WebCam                                       | 151       | 2.56%   |
| Microdia Integrated_Webcam_HD                           | 135       | 2.29%   |
| Realtek Integrated_Webcam_HD                            | 112       | 1.9%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 107       | 1.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 92        | 1.56%   |
| Bison Integrated Camera                                 | 88        | 1.49%   |
| IMC Networks Integrated Camera                          | 87        | 1.48%   |
| Syntek Integrated Camera                                | 85        | 1.44%   |
| Sunplus Integrated_Webcam_HD                            | 81        | 1.37%   |
| Microdia Integrated Webcam                              | 80        | 1.36%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 72        | 1.22%   |
| Chicony VGA WebCam                                      | 67        | 1.14%   |
| Realtek USB Camera                                      | 65        | 1.1%    |
| Chicony USB 2.0 Camera                                  | 60        | 1.02%   |
| Sunplus HD WebCam                                       | 58        | 0.98%   |
| Chicony TOSHIBA Web Camera - HD                         | 56        | 0.95%   |
| Chicony Lenovo EasyCamera                               | 54        | 0.92%   |
| Chicony HP Truevision HD                                | 54        | 0.92%   |
| Chicony HP TrueVision HD Camera                         | 51        | 0.87%   |
| Syntek Lenovo EasyCamera                                | 50        | 0.85%   |
| Chicony USB2.0 HD UVC WebCam                            | 49        | 0.83%   |
| Chicony FJ Camera                                       | 45        | 0.76%   |
| Quanta HD User Facing                                   | 44        | 0.75%   |
| Lite-On Integrated Camera                               | 44        | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                           | 44        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 44        | 0.75%   |
| Chicony HD User Facing                                  | 42        | 0.71%   |
| Chicony EasyCamera                                      | 42        | 0.71%   |
| Suyin Integrated_Webcam_HD                              | 41        | 0.7%    |
| Bison Lenovo EasyCamera                                 | 40        | 0.68%   |
| Quanta VGA WebCam                                       | 38        | 0.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 38        | 0.64%   |
| IMC Networks UVC VGA Webcam                             | 38        | 0.64%   |
| Bison Lenovo Integrated Webcam                          | 38        | 0.64%   |
| Chicony HP Webcam                                       | 37        | 0.63%   |
| Apple FaceTime HD Camera                                | 37        | 0.63%   |
| Quanta HP Webcam                                        | 35        | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 35        | 0.59%   |
| Quanta HP TrueVision HD Camera                          | 34        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 314       | 38.62%  |
| AuthenTec                          | 130       | 15.99%  |
| Upek                               | 85        | 10.46%  |
| Synaptics                          | 77        | 9.47%   |
| Shenzhen Goodix Technology         | 63        | 7.75%   |
| Elan Microelectronics              | 61        | 7.5%    |
| LighTuning Technology              | 37        | 4.55%   |
| STMicroelectronics                 | 32        | 3.94%   |
| Focal-systems.Corp                 | 8         | 0.98%   |
| Samsung Electronics                | 4         | 0.49%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.12%   |
| HOLTEK                             | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 78        | 9.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 61        | 7.5%    |
| AuthenTec AES2810                                                          | 51        | 6.27%   |
| Shenzhen Goodix  Fingerprint Device                                        | 47        | 5.78%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 41        | 5.04%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 34        | 4.18%   |
| STMicroelectronics Fingerprint Reader                                      | 32        | 3.94%   |
| Validity Sensors VFS491                                                    | 31        | 3.81%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 30        | 3.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 30        | 3.69%   |
| Elan ELAN:Fingerprint                                                      | 26        | 3.2%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 25        | 3.08%   |
| Elan ELAN:ARM-M4                                                           | 25        | 3.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 2.46%   |
| Validity Sensors Synaptics WBDI                                            | 18        | 2.21%   |
| AuthenTec AES1600                                                          | 17        | 2.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 16        | 1.97%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 16        | 1.97%   |
| AuthenTec Fingerprint Sensor                                               | 15        | 1.85%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.72%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 1.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 1.48%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 1.48%   |
| Elan WBF Fingerprint Sensor                                                | 10        | 1.23%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.11%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 0.98%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.98%   |
| LighTuning Fingerprint Reader                                              | 8         | 0.98%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 8         | 0.98%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 0.86%   |
| Synaptics UWP WBDI Device                                                  | 7         | 0.86%   |
| Synaptics  WBDI                                                            | 7         | 0.86%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.86%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.74%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 6         | 0.74%   |
| Synaptics UWP WBDI                                                         | 5         | 0.62%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 4         | 0.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 0.49%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 245       | 52.35%  |
| Alcor Micro           | 76        | 16.24%  |
| O2 Micro              | 60        | 12.82%  |
| Upek                  | 38        | 8.12%   |
| Lenovo                | 37        | 7.91%   |
| SCM Microsystems      | 3         | 0.64%   |
| Gemalto (was Gemplus) | 3         | 0.64%   |
| Realtek Semiconductor | 1         | 0.21%   |
| OmniKey               | 1         | 0.21%   |
| Microchip Technology  | 1         | 0.21%   |
| Hewlett-Packard       | 1         | 0.21%   |
| Cherry                | 1         | 0.21%   |
| Advanced Card Systems | 1         | 0.21%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 122       | 26.07%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 75        | 16.03%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 59        | 12.61%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 58        | 12.39%  |
| Broadcom 5880                                                                | 52        | 11.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 38        | 8.12%   |
| Lenovo Integrated Smart Card Reader                                          | 37        | 7.91%   |
| Broadcom 58200                                                               | 12        | 2.56%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.64%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.64%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.21%   |
| OmniKey CardMan 4321                                                         | 1         | 0.21%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.21%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.21%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.21%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.21%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.21%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.21%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.21%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5205      | 74%     |
| 1     | 1530      | 21.75%  |
| 2     | 273       | 3.88%   |
| 3     | 24        | 0.34%   |
| 6     | 1         | 0.01%   |
| 4     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 813       | 38.51%  |
| Chipcard                 | 458       | 21.7%   |
| Graphics card            | 413       | 19.56%  |
| Net/wireless             | 114       | 5.4%    |
| Bluetooth                | 92        | 4.36%   |
| Storage                  | 83        | 3.93%   |
| Multimedia controller    | 54        | 2.56%   |
| Camera                   | 40        | 1.89%   |
| Communication controller | 18        | 0.85%   |
| Sound                    | 8         | 0.38%   |
| Flash memory             | 6         | 0.28%   |
| Network                  | 5         | 0.24%   |
| Card reader              | 3         | 0.14%   |
| Net/ethernet             | 2         | 0.09%   |
| Modem                    | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |


Linux in Portugal - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

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

Total: 1359

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 14-ec0xx... | [1da5570114](https://linux-hardware.org/?probe=1da5570114) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a1fa08efc6](https://linux-hardware.org/?probe=a1fa08efc6) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | [e9988edacd](https://linux-hardware.org/?probe=e9988edacd) | Mar 30, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Acer          | Nitro AN515-45              | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [b7a0579d38](https://linux-hardware.org/?probe=b7a0579d38) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [88d5c3bb9f](https://linux-hardware.org/?probe=88d5c3bb9f) | Mar 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d7b0ec58d5](https://linux-hardware.org/?probe=d7b0ec58d5) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f13da06079](https://linux-hardware.org/?probe=f13da06079) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [48370f2817](https://linux-hardware.org/?probe=48370f2817) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| ASUSTek       | X202EV                      | [db21e9ac28](https://linux-hardware.org/?probe=db21e9ac28) | Mar 13, 2023 |
| HP            | ENVY Notebook               | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| MSI           | GF65 Thin 9SD               | [ea69b96e55](https://linux-hardware.org/?probe=ea69b96e55) | Mar 09, 2023 |
| Dell          | Latitude E4310              | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude E5570              | [5a5d668611](https://linux-hardware.org/?probe=5a5d668611) | Mar 07, 2023 |
| MSI           | GF72 8RD                    | [54eb266d2a](https://linux-hardware.org/?probe=54eb266d2a) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [26b308e28a](https://linux-hardware.org/?probe=26b308e28a) | Mar 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [73c765dbe2](https://linux-hardware.org/?probe=73c765dbe2) | Mar 01, 2023 |
| Lenovo        | ThinkPad T480 20L6SEH700    | [4a187e016b](https://linux-hardware.org/?probe=4a187e016b) | Feb 27, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [7b59cbd067](https://linux-hardware.org/?probe=7b59cbd067) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d99e163be6](https://linux-hardware.org/?probe=d99e163be6) | Feb 24, 2023 |
| HP            | mt40                        | [16e5f8eb5d](https://linux-hardware.org/?probe=16e5f8eb5d) | Feb 23, 2023 |
| MSI           | GF72 8RD                    | [cf6dad63da](https://linux-hardware.org/?probe=cf6dad63da) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| HUAWEI        | BOHB-WAX9                   | [387aa81d4c](https://linux-hardware.org/?probe=387aa81d4c) | Feb 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | [ebaa8145e1](https://linux-hardware.org/?probe=ebaa8145e1) | Feb 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [bb1c4209c7](https://linux-hardware.org/?probe=bb1c4209c7) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [ef69c22820](https://linux-hardware.org/?probe=ef69c22820) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [4e6c625797](https://linux-hardware.org/?probe=4e6c625797) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Toshiba       | Satellite L500              | [da3617cc40](https://linux-hardware.org/?probe=da3617cc40) | Feb 14, 2023 |
| Gigabyte      | P65                         | [b3d7faba21](https://linux-hardware.org/?probe=b3d7faba21) | Feb 12, 2023 |
| Gigabyte      | P65                         | [25d871afca](https://linux-hardware.org/?probe=25d871afca) | Feb 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [b6b590fcdf](https://linux-hardware.org/?probe=b6b590fcdf) | Feb 11, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| HP            | ProBook 640 G1              | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| Acer          | Aspire S7-391               | [3777a7d1e9](https://linux-hardware.org/?probe=3777a7d1e9) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| Acer          | Aspire V3-572G              | [7b48d97053](https://linux-hardware.org/?probe=7b48d97053) | Feb 07, 2023 |
| Toshiba       | Satellite C660              | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Dell          | Precision 7550              | [9608ff008d](https://linux-hardware.org/?probe=9608ff008d) | Feb 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e3ab731c3c](https://linux-hardware.org/?probe=e3ab731c3c) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| ASUSTek       | X555LD                      | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| INSYS         | GW1-W149                    | [5a4337006d](https://linux-hardware.org/?probe=5a4337006d) | Jan 28, 2023 |
| Acer          | Aspire 7750G                | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| ASUSTek       | X541UJ                      | [d9ceb3c732](https://linux-hardware.org/?probe=d9ceb3c732) | Jan 27, 2023 |
| HP            | ProBook 640 G2              | [4e8cd1aa46](https://linux-hardware.org/?probe=4e8cd1aa46) | Jan 26, 2023 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [a9567dc72b](https://linux-hardware.org/?probe=a9567dc72b) | Jan 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| ASUSTek       | UX360CA                     | [98fa78d117](https://linux-hardware.org/?probe=98fa78d117) | Jan 22, 2023 |
| Acer          | Aspire E1-522               | [ad5202642a](https://linux-hardware.org/?probe=ad5202642a) | Jan 22, 2023 |
| Chuwi         | GemiBook Pro                | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| Apple         | MacBookPro6,2               | [95074766b9](https://linux-hardware.org/?probe=95074766b9) | Jan 18, 2023 |
| Acer          | Predator PH315-51           | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| ASUSTek       | X541UV                      | [d45c8ef0ac](https://linux-hardware.org/?probe=d45c8ef0ac) | Jan 13, 2023 |
| Acer          | Aspire V5-122               | [a25a7c3fb1](https://linux-hardware.org/?probe=a25a7c3fb1) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Aspire 5742G                | [07f15478a7](https://linux-hardware.org/?probe=07f15478a7) | Jan 11, 2023 |
| Unknown       | Unknown                     | [ce97b4a08f](https://linux-hardware.org/?probe=ce97b4a08f) | Jan 08, 2023 |
| ASUSTek       | GL753VE                     | [7e0d372f98](https://linux-hardware.org/?probe=7e0d372f98) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50d2637c41](https://linux-hardware.org/?probe=50d2637c41) | Jan 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| HP            | Pavilion dv6                | [9f0fb0adf5](https://linux-hardware.org/?probe=9f0fb0adf5) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Acer          | Aspire 4310                 | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [113a2a45b2](https://linux-hardware.org/?probe=113a2a45b2) | Jan 01, 2023 |
| Toshiba       | Satellite L775-12V          | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| Dell          | Latitude E4310              | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Dell          | XPS 13 9370                 | [982f470134](https://linux-hardware.org/?probe=982f470134) | Dec 21, 2022 |
| Dell          | Latitude E4310              | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Dell          | Inspiron N5050              | [41fb3c537a](https://linux-hardware.org/?probe=41fb3c537a) | Dec 19, 2022 |
| Thomson       | PT-NEO14A.2WH32             | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Sony          | VGN-FZ31Z                   | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [8008043900](https://linux-hardware.org/?probe=8008043900) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Acer          | Aspire A315-55G             | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| MSI           | GF72 8RD                    | [f943786d2c](https://linux-hardware.org/?probe=f943786d2c) | Dec 09, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| HP            | Pavilion dv6                | [8a940a493b](https://linux-hardware.org/?probe=8a940a493b) | Dec 03, 2022 |
| MSI           | GF72 8RD                    | [c03f783ea5](https://linux-hardware.org/?probe=c03f783ea5) | Dec 01, 2022 |
| Acer          | Nitro AN515-58              | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| MSI           | GF72 8RD                    | [fb92041c1b](https://linux-hardware.org/?probe=fb92041c1b) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| ASUSTek       | F7SR                        | [ecdba533ea](https://linux-hardware.org/?probe=ecdba533ea) | Nov 25, 2022 |
| ASUSTek       | F7SR                        | [8102d8b361](https://linux-hardware.org/?probe=8102d8b361) | Nov 25, 2022 |
| MSI           | Summit E16Flip A12UCT       | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [2de63dfd54](https://linux-hardware.org/?probe=2de63dfd54) | Nov 23, 2022 |
| HUAWEI        | BOD-WXX9                    | [814f45a510](https://linux-hardware.org/?probe=814f45a510) | Nov 23, 2022 |
| Apple         | MacBookAir5,1               | [2ded48104d](https://linux-hardware.org/?probe=2ded48104d) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| Acer          | Popcorn                     | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Dell          | XPS 13 9360                 | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [02c6e2e360](https://linux-hardware.org/?probe=02c6e2e360) | Nov 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [d4c27f1388](https://linux-hardware.org/?probe=d4c27f1388) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [0401b9e939](https://linux-hardware.org/?probe=0401b9e939) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| ASUSTek       | G752VS                      | [364d6d09ab](https://linux-hardware.org/?probe=364d6d09ab) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [c54708e797](https://linux-hardware.org/?probe=c54708e797) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [e54df5cb0d](https://linux-hardware.org/?probe=e54df5cb0d) | Nov 13, 2022 |
| ASUSTek       | A6JC                        | [dce6c2a8f4](https://linux-hardware.org/?probe=dce6c2a8f4) | Nov 13, 2022 |
| Packard Be... | EasyNote LV11HC             | [244d508935](https://linux-hardware.org/?probe=244d508935) | Nov 12, 2022 |
| HUAWEI        | HVY-WXX9                    | [c1f18206f4](https://linux-hardware.org/?probe=c1f18206f4) | Nov 11, 2022 |
| eMachines     | G525                        | [38b8684942](https://linux-hardware.org/?probe=38b8684942) | Nov 10, 2022 |
| ASUSTek       | N61Vg                       | [5205b24cb0](https://linux-hardware.org/?probe=5205b24cb0) | Nov 08, 2022 |
| Dell          | Latitude E6510              | [befb811cfe](https://linux-hardware.org/?probe=befb811cfe) | Nov 05, 2022 |
| Acer          | Nitro AN515-55              | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| ASUSTek       | N61Vg                       | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| Dell          | Latitude E6510              | [b346d71347](https://linux-hardware.org/?probe=b346d71347) | Oct 29, 2022 |
| Acer          | Aspire SW5-012              | [90dd31edc8](https://linux-hardware.org/?probe=90dd31edc8) | Oct 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Acer          | Aspire ES1-131              | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| Dell          | Latitude 7320               | [f249267def](https://linux-hardware.org/?probe=f249267def) | Oct 26, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [8ebb941ac6](https://linux-hardware.org/?probe=8ebb941ac6) | Oct 26, 2022 |
| ASUSTek       | X542URR                     | [fe6fb20830](https://linux-hardware.org/?probe=fe6fb20830) | Oct 25, 2022 |
| Toshiba       | NB300                       | [c5aa7d3c5f](https://linux-hardware.org/?probe=c5aa7d3c5f) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| Apple         | MacBookPro10,1              | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| HP            | G62                         | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [e5f7b07e9c](https://linux-hardware.org/?probe=e5f7b07e9c) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [25bb674789](https://linux-hardware.org/?probe=25bb674789) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| ASUSTek       | X541UV                      | [ba7c1c3d83](https://linux-hardware.org/?probe=ba7c1c3d83) | Oct 14, 2022 |
| Toshiba       | Satellite L650              | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| HP            | EliteBook 840 G2            | [d83c027361](https://linux-hardware.org/?probe=d83c027361) | Oct 12, 2022 |
| ASUSTek       | N53SV                       | [2460d79ba8](https://linux-hardware.org/?probe=2460d79ba8) | Oct 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [184ecb5e76](https://linux-hardware.org/?probe=184ecb5e76) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [a3d3100ffa](https://linux-hardware.org/?probe=a3d3100ffa) | Oct 05, 2022 |
| Acer          | Aspire ES1-520              | [b50cfdccab](https://linux-hardware.org/?probe=b50cfdccab) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| HP            | ENVY 15                     | [950623d8b2](https://linux-hardware.org/?probe=950623d8b2) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d9a196cd8e](https://linux-hardware.org/?probe=d9a196cd8e) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | [5c5666fa97](https://linux-hardware.org/?probe=5c5666fa97) | Sep 29, 2022 |
| GIADA         | ChiefRiver Platform         | [d0f71cdc7f](https://linux-hardware.org/?probe=d0f71cdc7f) | Sep 26, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [84d47822bf](https://linux-hardware.org/?probe=84d47822bf) | Sep 24, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [3afd2e892b](https://linux-hardware.org/?probe=3afd2e892b) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | [2f1fe986d8](https://linux-hardware.org/?probe=2f1fe986d8) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [910b604abc](https://linux-hardware.org/?probe=910b604abc) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Toshiba       | Satellite P845T             | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [dd6d053ae2](https://linux-hardware.org/?probe=dd6d053ae2) | Sep 17, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| ASUSTek       | X555LJ                      | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Lenovo        | ThinkPad W540 20BG0016US    | [9f0543edc4](https://linux-hardware.org/?probe=9f0543edc4) | Sep 11, 2022 |
| Chuwi         | CoreBook X                  | [4f29128588](https://linux-hardware.org/?probe=4f29128588) | Sep 11, 2022 |
| System76      | Oryx Pro                    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ab939db2c0](https://linux-hardware.org/?probe=ab939db2c0) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f9604390e8](https://linux-hardware.org/?probe=f9604390e8) | Sep 10, 2022 |
| HP            | EliteBook 840 G6            | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| HP            | Pavilion g6                 | [770b1a8154](https://linux-hardware.org/?probe=770b1a8154) | Sep 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| Sony          | VGN-FZ31Z                   | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [a74d79fc0b](https://linux-hardware.org/?probe=a74d79fc0b) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| ASUSTek       | X541UJ                      | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [11efd3dbe0](https://linux-hardware.org/?probe=11efd3dbe0) | Aug 30, 2022 |
| Toshiba       | Satellite A300              | [f90886ae85](https://linux-hardware.org/?probe=f90886ae85) | Aug 30, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [73db272ecb](https://linux-hardware.org/?probe=73db272ecb) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| HP            | Laptop 15s-fq2xxx           | [8ffebf0c43](https://linux-hardware.org/?probe=8ffebf0c43) | Aug 26, 2022 |
| ASUSTek       | N61Vg                       | [30be913709](https://linux-hardware.org/?probe=30be913709) | Aug 25, 2022 |
| HP            | ProBook 640 G2              | [fc50d4e200](https://linux-hardware.org/?probe=fc50d4e200) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [69c8e5eedc](https://linux-hardware.org/?probe=69c8e5eedc) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [2bf774fae7](https://linux-hardware.org/?probe=2bf774fae7) | Aug 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| ASUSTek       | N53SN                       | [6cb4ac4247](https://linux-hardware.org/?probe=6cb4ac4247) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [73a3d7c1cf](https://linux-hardware.org/?probe=73a3d7c1cf) | Aug 12, 2022 |
| MSI           | Modern 14 A10RB             | [9979c66e3e](https://linux-hardware.org/?probe=9979c66e3e) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| Apple         | MacBookAir6,1               | [154468415c](https://linux-hardware.org/?probe=154468415c) | Aug 05, 2022 |
| Apple         | MacBookAir6,1               | [6f355de994](https://linux-hardware.org/?probe=6f355de994) | Aug 04, 2022 |
| Toshiba       | Satellite U840              | [5ebf9417bf](https://linux-hardware.org/?probe=5ebf9417bf) | Aug 04, 2022 |
| MSI           | Modern 14 A10RB             | [abf1fcf08b](https://linux-hardware.org/?probe=abf1fcf08b) | Aug 02, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | [c6ce2d4317](https://linux-hardware.org/?probe=c6ce2d4317) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | [eca5fa0c39](https://linux-hardware.org/?probe=eca5fa0c39) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [bc5b132a8d](https://linux-hardware.org/?probe=bc5b132a8d) | Jul 29, 2022 |
| Toshiba       | Satellite U840              | [c3f00f5b90](https://linux-hardware.org/?probe=c3f00f5b90) | Jul 29, 2022 |
| ASUSTek       | N53SN                       | [2e35ef4a8a](https://linux-hardware.org/?probe=2e35ef4a8a) | Jul 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e95cafce19](https://linux-hardware.org/?probe=e95cafce19) | Jul 26, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [ae16c8863a](https://linux-hardware.org/?probe=ae16c8863a) | Jul 25, 2022 |
| ASUSTek       | X540LJ                      | [264bb2f2a1](https://linux-hardware.org/?probe=264bb2f2a1) | Jul 23, 2022 |
| ASUSTek       | X540LJ                      | [fc5c252e6e](https://linux-hardware.org/?probe=fc5c252e6e) | Jul 23, 2022 |
| Acer          | Aspire A515-45              | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| Dell          | XPS 15 7590                 | [528f562110](https://linux-hardware.org/?probe=528f562110) | Jul 18, 2022 |
| Packard Be... | EasyNote LV11HC             | [c0693d5f9a](https://linux-hardware.org/?probe=c0693d5f9a) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Sony          | VPCEB3L1E                   | [310a2ada05](https://linux-hardware.org/?probe=310a2ada05) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | [247411abde](https://linux-hardware.org/?probe=247411abde) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | [9af59fca26](https://linux-hardware.org/?probe=9af59fca26) | Jul 08, 2022 |
| ASUSTek       | X540LJ                      | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Sony          | VGN-FZ31Z                   | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Acer          | Aspire A515-54G             | [c0975c6877](https://linux-hardware.org/?probe=c0975c6877) | Jul 02, 2022 |
| ASUSTek       | N61Jq                       | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| Acer          | Aspire A515-54G             | [92d695d6be](https://linux-hardware.org/?probe=92d695d6be) | Jul 02, 2022 |
| HP            | EliteBook 840 G1            | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [91c5f849c5](https://linux-hardware.org/?probe=91c5f849c5) | Jun 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [17cb04c5f5](https://linux-hardware.org/?probe=17cb04c5f5) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Sony          | VPCEH2J1E                   | [7dde3ae196](https://linux-hardware.org/?probe=7dde3ae196) | Jun 23, 2022 |
| HP            | EliteBook 820 G1            | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [fd65aaa4b3](https://linux-hardware.org/?probe=fd65aaa4b3) | Jun 21, 2022 |
| Toshiba       | NB305                       | [1280ac15ba](https://linux-hardware.org/?probe=1280ac15ba) | Jun 17, 2022 |
| HP            | Pavilion Notebook           | [d9b85c0e15](https://linux-hardware.org/?probe=d9b85c0e15) | Jun 16, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [4b1946451e](https://linux-hardware.org/?probe=4b1946451e) | Jun 15, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [35dc89f7ff](https://linux-hardware.org/?probe=35dc89f7ff) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| Toshiba       | Satellite T130              | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| Sony          | VGN-FZ31Z                   | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Dell          | Latitude E6400              | [67a5bdc1aa](https://linux-hardware.org/?probe=67a5bdc1aa) | Jun 04, 2022 |
| HP            | Compaq nx7300 (RU464EA#A... | [a44ec57985](https://linux-hardware.org/?probe=a44ec57985) | Jun 02, 2022 |
| HP            | EliteBook 840 G2            | [8aff04335d](https://linux-hardware.org/?probe=8aff04335d) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [029a55ffb4](https://linux-hardware.org/?probe=029a55ffb4) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| Lenovo        | ThinkPad T530 2394C98       | [b5aebb2490](https://linux-hardware.org/?probe=b5aebb2490) | May 30, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [f47dbc0616](https://linux-hardware.org/?probe=f47dbc0616) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e72ac27af1](https://linux-hardware.org/?probe=e72ac27af1) | May 30, 2022 |
| Acer          | Swift SF314-54              | [eb522816a1](https://linux-hardware.org/?probe=eb522816a1) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [9e1d2f7e8a](https://linux-hardware.org/?probe=9e1d2f7e8a) | May 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [533beb13eb](https://linux-hardware.org/?probe=533beb13eb) | May 26, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| HP            | EliteBook 8540w             | [2f973c22ec](https://linux-hardware.org/?probe=2f973c22ec) | May 19, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1ef52e97fa](https://linux-hardware.org/?probe=1ef52e97fa) | May 18, 2022 |
| Apple         | MacBookAir7,2               | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| Notebook      | NB50TJ1_TK1                 | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [58f371c0d7](https://linux-hardware.org/?probe=58f371c0d7) | May 13, 2022 |
| Lenovo        | ThinkPad X61 7673AQ5        | [42a17c86f4](https://linux-hardware.org/?probe=42a17c86f4) | May 13, 2022 |
| MSI           | GT72VR 6RD                  | [c4cf6c9cd0](https://linux-hardware.org/?probe=c4cf6c9cd0) | May 12, 2022 |
| MSI           | Modern 15 A10RAS            | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion g6                 | [69406bff46](https://linux-hardware.org/?probe=69406bff46) | May 08, 2022 |
| HP            | Pavilion g6                 | [56ca785331](https://linux-hardware.org/?probe=56ca785331) | May 08, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [d24187e845](https://linux-hardware.org/?probe=d24187e845) | May 05, 2022 |
| HP            | ProBook 640 G2              | [50ccff3e1a](https://linux-hardware.org/?probe=50ccff3e1a) | May 04, 2022 |
| ASUSTek       | X540SAA                     | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| HP            | EliteBook 840 G5            | [47aaf6f556](https://linux-hardware.org/?probe=47aaf6f556) | May 04, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [0a6358dc13](https://linux-hardware.org/?probe=0a6358dc13) | May 03, 2022 |
| Sony          | VGN-FZ31Z                   | [ebe91972ba](https://linux-hardware.org/?probe=ebe91972ba) | May 01, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [96dbfb494e](https://linux-hardware.org/?probe=96dbfb494e) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| Lenovo        | G50-45 80E3                 | [910267bbd5](https://linux-hardware.org/?probe=910267bbd5) | Apr 28, 2022 |
| Lenovo        | G50-45 80E3                 | [22dd67107b](https://linux-hardware.org/?probe=22dd67107b) | Apr 28, 2022 |
| HP            | Laptop 15s-fq2xxx           | [91c7a6b5a0](https://linux-hardware.org/?probe=91c7a6b5a0) | Apr 27, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [9e591226b7](https://linux-hardware.org/?probe=9e591226b7) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [5c309ec35d](https://linux-hardware.org/?probe=5c309ec35d) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [710ddc650e](https://linux-hardware.org/?probe=710ddc650e) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Apple         | MacBookPro7,1               | [2641eee3f1](https://linux-hardware.org/?probe=2641eee3f1) | Apr 21, 2022 |
| ASUSTek       | X102BA                      | [00fbb5cbff](https://linux-hardware.org/?probe=00fbb5cbff) | Apr 20, 2022 |
| Lenovo        | ThinkPad L390 20NR001EPG    | [d83b89a414](https://linux-hardware.org/?probe=d83b89a414) | Apr 20, 2022 |
| HP            | Pavilion g6                 | [0c4c081e71](https://linux-hardware.org/?probe=0c4c081e71) | Apr 17, 2022 |
| Toshiba       | Satellite L775-151          | [957020b872](https://linux-hardware.org/?probe=957020b872) | Apr 16, 2022 |
| Toshiba       | Satellite L775-151          | [706f14a3e6](https://linux-hardware.org/?probe=706f14a3e6) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | [a9407bd227](https://linux-hardware.org/?probe=a9407bd227) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | [7403ce7189](https://linux-hardware.org/?probe=7403ce7189) | Apr 16, 2022 |
| Toshiba       | Satellite L300              | [242592fee5](https://linux-hardware.org/?probe=242592fee5) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Toshiba       | Satellite P70-B             | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [bc22c713a7](https://linux-hardware.org/?probe=bc22c713a7) | Apr 13, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [fba984b898](https://linux-hardware.org/?probe=fba984b898) | Apr 11, 2022 |
| Positivo      | H14BU08                     | [11014257c0](https://linux-hardware.org/?probe=11014257c0) | Apr 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4ca643452e](https://linux-hardware.org/?probe=4ca643452e) | Apr 10, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8adf631258](https://linux-hardware.org/?probe=8adf631258) | Apr 08, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [00c3a80eb1](https://linux-hardware.org/?probe=00c3a80eb1) | Apr 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ec5daa2c06](https://linux-hardware.org/?probe=ec5daa2c06) | Apr 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [191c569aa7](https://linux-hardware.org/?probe=191c569aa7) | Apr 05, 2022 |
| ASUSTek       | T100TA                      | [dbfc15621f](https://linux-hardware.org/?probe=dbfc15621f) | Apr 04, 2022 |
| ASUSTek       | X555LJ                      | [f9bbaea819](https://linux-hardware.org/?probe=f9bbaea819) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | [944f40aa28](https://linux-hardware.org/?probe=944f40aa28) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| HP            | Pavilion g6                 | [5dce001675](https://linux-hardware.org/?probe=5dce001675) | Mar 31, 2022 |
| MSI           | Modern 14 B11M              | [3cdc036c09](https://linux-hardware.org/?probe=3cdc036c09) | Mar 30, 2022 |
| Toshiba       | Satellite C660              | [60a6bafd86](https://linux-hardware.org/?probe=60a6bafd86) | Mar 30, 2022 |
| Fujitsu       | LIFEBOOK S752               | [73c18f75a9](https://linux-hardware.org/?probe=73c18f75a9) | Mar 29, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [41870b3fdb](https://linux-hardware.org/?probe=41870b3fdb) | Mar 28, 2022 |
| ASUSTek       | T100TA                      | [fa6858ef16](https://linux-hardware.org/?probe=fa6858ef16) | Mar 28, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [fc92c7a9d2](https://linux-hardware.org/?probe=fc92c7a9d2) | Mar 28, 2022 |
| ASUSTek       | GL552VW                     | [7e8bfac4b7](https://linux-hardware.org/?probe=7e8bfac4b7) | Mar 27, 2022 |
| MSI           | GL65 Leopard 10SFK          | [96afe8ccf1](https://linux-hardware.org/?probe=96afe8ccf1) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | [a2921a6b4c](https://linux-hardware.org/?probe=a2921a6b4c) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | [ca5720c46b](https://linux-hardware.org/?probe=ca5720c46b) | Mar 25, 2022 |
| Toshiba       | Satellite P50-B-10V         | [1f6acfd782](https://linux-hardware.org/?probe=1f6acfd782) | Mar 24, 2022 |
| ASUSTek       | X510UNR                     | [ab3b8653a6](https://linux-hardware.org/?probe=ab3b8653a6) | Mar 23, 2022 |
| Apple         | MacBookAir3,1               | [482fbd3456](https://linux-hardware.org/?probe=482fbd3456) | Mar 21, 2022 |
| HP            | ProBook 640 G2              | [17ceb0fd9f](https://linux-hardware.org/?probe=17ceb0fd9f) | Mar 19, 2022 |
| ASUSTek       | X541UV                      | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| MSI           | Stealth GS66 12UGS          | [882be4cd35](https://linux-hardware.org/?probe=882be4cd35) | Mar 19, 2022 |
| HP            | ProBook 640 G2              | [9024337e9f](https://linux-hardware.org/?probe=9024337e9f) | Mar 19, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [5b345c55f7](https://linux-hardware.org/?probe=5b345c55f7) | Mar 16, 2022 |
| HP            | 250 G8 Notebook PC          | [90bbda2f8c](https://linux-hardware.org/?probe=90bbda2f8c) | Mar 16, 2022 |
| Acer          | Nitro AN515-54              | [1fea8c1b2b](https://linux-hardware.org/?probe=1fea8c1b2b) | Mar 16, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [fabbaeb1bb](https://linux-hardware.org/?probe=fabbaeb1bb) | Mar 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [3aded823d8](https://linux-hardware.org/?probe=3aded823d8) | Mar 13, 2022 |
| ASUSTek       | ZenBook UX431FA             | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8469a31d58](https://linux-hardware.org/?probe=8469a31d58) | Mar 10, 2022 |
| Sony          | VGN-FZ31Z                   | [17e3cb9771](https://linux-hardware.org/?probe=17e3cb9771) | Mar 10, 2022 |
| ASUSTek       | X541UV                      | [aef8901d13](https://linux-hardware.org/?probe=aef8901d13) | Mar 08, 2022 |
| ASUSTek       | X541UV                      | [6bed69bcdb](https://linux-hardware.org/?probe=6bed69bcdb) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8a4f961472](https://linux-hardware.org/?probe=8a4f961472) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4d33fc28da](https://linux-hardware.org/?probe=4d33fc28da) | Mar 08, 2022 |
| Acer          | Aspire E5-551G              | [18bc15734f](https://linux-hardware.org/?probe=18bc15734f) | Mar 07, 2022 |
| ASUSTek       | X541UV                      | [a90d26bc2d](https://linux-hardware.org/?probe=a90d26bc2d) | Mar 06, 2022 |
| Lenovo        | ThinkPad W541 20EGS03100    | [f7b51cf262](https://linux-hardware.org/?probe=f7b51cf262) | Mar 05, 2022 |
| ASUSTek       | X541UV                      | [b5678eb9d3](https://linux-hardware.org/?probe=b5678eb9d3) | Mar 05, 2022 |
| Apple         | MacBookPro8,3               | [87a5df55b8](https://linux-hardware.org/?probe=87a5df55b8) | Mar 04, 2022 |
| ASUSTek       | T100TA                      | [485c2b3aa7](https://linux-hardware.org/?probe=485c2b3aa7) | Mar 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c1b8c2903d](https://linux-hardware.org/?probe=c1b8c2903d) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | [67241eca45](https://linux-hardware.org/?probe=67241eca45) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | [06455796f9](https://linux-hardware.org/?probe=06455796f9) | Mar 01, 2022 |
| Sony          | VGN-FZ31Z                   | [01b50ec980](https://linux-hardware.org/?probe=01b50ec980) | Mar 01, 2022 |
| Sony          | VGN-FZ31Z                   | [1d156021e3](https://linux-hardware.org/?probe=1d156021e3) | Feb 26, 2022 |
| Sony          | VGN-FZ31Z                   | [b223305dc1](https://linux-hardware.org/?probe=b223305dc1) | Feb 26, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Positivo      | H14BU08                     | [b3cb8e0d72](https://linux-hardware.org/?probe=b3cb8e0d72) | Feb 25, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e72b93aadf](https://linux-hardware.org/?probe=e72b93aadf) | Feb 24, 2022 |
| Apple         | MacBookPro12,1              | [e9d9cfb3e9](https://linux-hardware.org/?probe=e9d9cfb3e9) | Feb 24, 2022 |
| Samsung       | QX310/QX410/QX510/SF310/... | [20b0cf0db9](https://linux-hardware.org/?probe=20b0cf0db9) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [48d36e9bae](https://linux-hardware.org/?probe=48d36e9bae) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [60adc82fb8](https://linux-hardware.org/?probe=60adc82fb8) | Feb 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [cf3e28fb31](https://linux-hardware.org/?probe=cf3e28fb31) | Feb 23, 2022 |
| Apple         | MacBookPro12,1              | [677ffe54b5](https://linux-hardware.org/?probe=677ffe54b5) | Feb 23, 2022 |
| SLIMBOOK      | TITAN                       | [2a35f863c2](https://linux-hardware.org/?probe=2a35f863c2) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [c49acb0edf](https://linux-hardware.org/?probe=c49acb0edf) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [6f13abc9eb](https://linux-hardware.org/?probe=6f13abc9eb) | Feb 21, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [013349e12a](https://linux-hardware.org/?probe=013349e12a) | Feb 19, 2022 |
| HP            | EliteBook 840 G6            | [b6f947ed63](https://linux-hardware.org/?probe=b6f947ed63) | Feb 18, 2022 |
| Dell          | Latitude E6440              | [1d4bac917c](https://linux-hardware.org/?probe=1d4bac917c) | Feb 18, 2022 |
| ASUSTek       | T100TA                      | [9f0a454d8b](https://linux-hardware.org/?probe=9f0a454d8b) | Feb 18, 2022 |
| ASUSTek       | X555LJ                      | [c2f63ae6d7](https://linux-hardware.org/?probe=c2f63ae6d7) | Feb 14, 2022 |
| Acer          | Aspire 5715Z                | [cdd4414bbd](https://linux-hardware.org/?probe=cdd4414bbd) | Feb 13, 2022 |
| Apple         | MacBookPro12,1              | [aeec085062](https://linux-hardware.org/?probe=aeec085062) | Feb 13, 2022 |
| ASUSTek       | X541UV                      | [fb81da9fa5](https://linux-hardware.org/?probe=fb81da9fa5) | Feb 13, 2022 |
| Dell          | Precision 3561              | [23c3392c57](https://linux-hardware.org/?probe=23c3392c57) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6c64279dbc](https://linux-hardware.org/?probe=6c64279dbc) | Feb 12, 2022 |
| ASUSTek       | K50IJ                       | [0dd30d1e7e](https://linux-hardware.org/?probe=0dd30d1e7e) | Feb 11, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| HP            | Compaq Presario CQ60        | [f5d9f92aad](https://linux-hardware.org/?probe=f5d9f92aad) | Feb 09, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [0043180375](https://linux-hardware.org/?probe=0043180375) | Feb 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [70122a3cd0](https://linux-hardware.org/?probe=70122a3cd0) | Feb 07, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6bee100b0a](https://linux-hardware.org/?probe=6bee100b0a) | Feb 06, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [a554a842f7](https://linux-hardware.org/?probe=a554a842f7) | Feb 05, 2022 |
| Dell          | Latitude D630               | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [722271e199](https://linux-hardware.org/?probe=722271e199) | Feb 04, 2022 |
| HP            | Pavilion Notebook           | [62cf8cdd3c](https://linux-hardware.org/?probe=62cf8cdd3c) | Feb 02, 2022 |
| Dell          | Latitude D630               | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| Sony          | VGN-FZ31Z                   | [c3e03d2551](https://linux-hardware.org/?probe=c3e03d2551) | Feb 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [e0c36731ca](https://linux-hardware.org/?probe=e0c36731ca) | Jan 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [b4f3d4f1ee](https://linux-hardware.org/?probe=b4f3d4f1ee) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [77d230b476](https://linux-hardware.org/?probe=77d230b476) | Jan 29, 2022 |
| Acer          | Aspire E5-551G              | [435c894ed4](https://linux-hardware.org/?probe=435c894ed4) | Jan 29, 2022 |
| Toshiba       | Satellite C660              | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| ASUSTek       | N56VZ                       | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX431FA             | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| Apple         | MacBookPro9,2               | [90249388ff](https://linux-hardware.org/?probe=90249388ff) | Jan 22, 2022 |
| Toshiba       | Satellite A200              | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6fd36db1e0](https://linux-hardware.org/?probe=6fd36db1e0) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| Sony          | VGN-FZ31Z                   | [c7f9080e23](https://linux-hardware.org/?probe=c7f9080e23) | Jan 18, 2022 |
| Acer          | Aspire ES1-512              | [ca83027c67](https://linux-hardware.org/?probe=ca83027c67) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b27ed63a97](https://linux-hardware.org/?probe=b27ed63a97) | Jan 16, 2022 |
| Toshiba       | Satellite C660              | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a8ff8d111b](https://linux-hardware.org/?probe=a8ff8d111b) | Jan 11, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [5ba5bfc822](https://linux-hardware.org/?probe=5ba5bfc822) | Jan 11, 2022 |
| HP            | Laptop 15s-fq2xxx           | [468890e10d](https://linux-hardware.org/?probe=468890e10d) | Jan 08, 2022 |
| Sony          | VGN-FZ31Z                   | [7587e6c439](https://linux-hardware.org/?probe=7587e6c439) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [a3194a0ed3](https://linux-hardware.org/?probe=a3194a0ed3) | Jan 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a140e77bfe](https://linux-hardware.org/?probe=a140e77bfe) | Jan 05, 2022 |
| Toshiba       | Satellite L50D-B            | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| HP            | ProBook 4530s               | [c68e298c14](https://linux-hardware.org/?probe=c68e298c14) | Jan 04, 2022 |
| Lenovo        | ThinkPad L530 24791S8       | [030611ecba](https://linux-hardware.org/?probe=030611ecba) | Jan 04, 2022 |
| MSI           | Modern 14 A10RB             | [83285ade95](https://linux-hardware.org/?probe=83285ade95) | Jan 02, 2022 |
| MSI           | Modern 14 A10RB             | [602fe88681](https://linux-hardware.org/?probe=602fe88681) | Jan 02, 2022 |
| Timi          | TM1701                      | [594f40016d](https://linux-hardware.org/?probe=594f40016d) | Jan 02, 2022 |
| ASUSTek       | X542URR                     | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| Dell          | Latitude D420               | [3caac63d5f](https://linux-hardware.org/?probe=3caac63d5f) | Dec 31, 2021 |
| Sony          | VGN-FZ31Z                   | [38b3f4d971](https://linux-hardware.org/?probe=38b3f4d971) | Dec 30, 2021 |
| Sony          | VGN-FZ31Z                   | [d1a2146c05](https://linux-hardware.org/?probe=d1a2146c05) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | [6f891ac715](https://linux-hardware.org/?probe=6f891ac715) | Dec 29, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [d988f944f8](https://linux-hardware.org/?probe=d988f944f8) | Dec 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1daccedded](https://linux-hardware.org/?probe=1daccedded) | Dec 26, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [fe1f7f03e2](https://linux-hardware.org/?probe=fe1f7f03e2) | Dec 21, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [40282bb1fd](https://linux-hardware.org/?probe=40282bb1fd) | Dec 21, 2021 |
| Acer          | Aspire ES1-520              | [7a43d12de6](https://linux-hardware.org/?probe=7a43d12de6) | Dec 20, 2021 |
| ASUSTek       | T100HAN                     | [ad0dc6b737](https://linux-hardware.org/?probe=ad0dc6b737) | Dec 17, 2021 |
| ASUSTek       | T100HAN                     | [67b8998643](https://linux-hardware.org/?probe=67b8998643) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [f9a4ac885d](https://linux-hardware.org/?probe=f9a4ac885d) | Dec 17, 2021 |
| MSI           | Alpha 15 A4DEK              | [0ecac9e450](https://linux-hardware.org/?probe=0ecac9e450) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| MSI           | Alpha 15 A4DEK              | [4b7a0b485e](https://linux-hardware.org/?probe=4b7a0b485e) | Dec 15, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Sony          | VGN-SZ2HP_B                 | [a5d51adfab](https://linux-hardware.org/?probe=a5d51adfab) | Dec 13, 2021 |
| Lenovo        | Z51-70 80K6                 | [3faa0a2aad](https://linux-hardware.org/?probe=3faa0a2aad) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [11fb7ea1d7](https://linux-hardware.org/?probe=11fb7ea1d7) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [23579d8b3a](https://linux-hardware.org/?probe=23579d8b3a) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [66796a4303](https://linux-hardware.org/?probe=66796a4303) | Dec 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1d9d5bfe12](https://linux-hardware.org/?probe=1d9d5bfe12) | Dec 05, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [aa4d4e3b08](https://linux-hardware.org/?probe=aa4d4e3b08) | Dec 04, 2021 |
| Lenovo        | ThinkPad R61 89337HG        | [670c02b990](https://linux-hardware.org/?probe=670c02b990) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [c68a7d50dc](https://linux-hardware.org/?probe=c68a7d50dc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [49055ba417](https://linux-hardware.org/?probe=49055ba417) | Dec 01, 2021 |
| Sony          | VGN-FZ31Z                   | [8e4401834b](https://linux-hardware.org/?probe=8e4401834b) | Dec 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| Packard Be... | EasyNote_MX37-V-101PT       | [6f8e7042c4](https://linux-hardware.org/?probe=6f8e7042c4) | Nov 30, 2021 |
| Acer          | Aspire A315-57G             | [cfc036a421](https://linux-hardware.org/?probe=cfc036a421) | Nov 29, 2021 |
| HP            | OMEN by Laptop              | [4dec490a3f](https://linux-hardware.org/?probe=4dec490a3f) | Nov 29, 2021 |
| Acer          | Aspire E5-521               | [48d70742bb](https://linux-hardware.org/?probe=48d70742bb) | Nov 28, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [1a717e5780](https://linux-hardware.org/?probe=1a717e5780) | Nov 28, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| HP            | Pavilion 15                 | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| HP            | 15 TS                       | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| Clevo         | M7X0SU                      | [a9638079c6](https://linux-hardware.org/?probe=a9638079c6) | Nov 20, 2021 |
| ASUSTek       | UX303LAB                    | [21a3bdf255](https://linux-hardware.org/?probe=21a3bdf255) | Nov 19, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [8fc5db0cd9](https://linux-hardware.org/?probe=8fc5db0cd9) | Nov 17, 2021 |
| Sony          | VGN-FZ31Z                   | [2c4fd499c5](https://linux-hardware.org/?probe=2c4fd499c5) | Nov 17, 2021 |
| HP            | Pavilion dv6                | [3f54f48e23](https://linux-hardware.org/?probe=3f54f48e23) | Nov 17, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [5f28060674](https://linux-hardware.org/?probe=5f28060674) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [72e7bebf84](https://linux-hardware.org/?probe=72e7bebf84) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [39d8ea222a](https://linux-hardware.org/?probe=39d8ea222a) | Nov 16, 2021 |
| HUAWEI        | WRT-WX9                     | [6c0ee3ae74](https://linux-hardware.org/?probe=6c0ee3ae74) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [be61c60b41](https://linux-hardware.org/?probe=be61c60b41) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [9fa65491aa](https://linux-hardware.org/?probe=9fa65491aa) | Nov 12, 2021 |
| ASUSTek       | X202EV                      | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| Sony          | VGN-FZ31Z                   | [fe8ba3f801](https://linux-hardware.org/?probe=fe8ba3f801) | Nov 11, 2021 |
| ASUSTek       | T102HA                      | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| Lenovo        | ThinkPad T420 4177Q5U       | [02ce053478](https://linux-hardware.org/?probe=02ce053478) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [c13d42cb63](https://linux-hardware.org/?probe=c13d42cb63) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [8403f5c97f](https://linux-hardware.org/?probe=8403f5c97f) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| HP            | G62                         | [a4a0360f3a](https://linux-hardware.org/?probe=a4a0360f3a) | Nov 06, 2021 |
| HP            | G62                         | [cd87bfa19b](https://linux-hardware.org/?probe=cd87bfa19b) | Nov 06, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [87daccdc88](https://linux-hardware.org/?probe=87daccdc88) | Nov 05, 2021 |
| HP            | OMEN by Laptop              | [0b933dd493](https://linux-hardware.org/?probe=0b933dd493) | Nov 03, 2021 |
| Toshiba       | Satellite C660              | [c22b81abd4](https://linux-hardware.org/?probe=c22b81abd4) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | [bbe04676c1](https://linux-hardware.org/?probe=bbe04676c1) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | [09eba8bb5f](https://linux-hardware.org/?probe=09eba8bb5f) | Nov 02, 2021 |
| Standard      | Unknown                     | [3cccd4bf9f](https://linux-hardware.org/?probe=3cccd4bf9f) | Nov 02, 2021 |
| HP            | ProBook 445 G7              | [ca8418c85b](https://linux-hardware.org/?probe=ca8418c85b) | Nov 02, 2021 |
| Acer          | Aspire E1-570G              | [9c6c7691c9](https://linux-hardware.org/?probe=9c6c7691c9) | Nov 02, 2021 |
| Acer          | Aspire 4732Z                | [7095848f26](https://linux-hardware.org/?probe=7095848f26) | Oct 31, 2021 |
| Acer          | Aspire 4732Z                | [ce23f8d9f9](https://linux-hardware.org/?probe=ce23f8d9f9) | Oct 30, 2021 |
| Standard      | Unknown                     | [1bf7e2da2f](https://linux-hardware.org/?probe=1bf7e2da2f) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [9276790a36](https://linux-hardware.org/?probe=9276790a36) | Oct 28, 2021 |
| Acer          | Aspire 5732Z                | [9d4f7a1a4b](https://linux-hardware.org/?probe=9d4f7a1a4b) | Oct 27, 2021 |
| ASUSTek       | X453MA                      | [4a70424b2f](https://linux-hardware.org/?probe=4a70424b2f) | Oct 27, 2021 |
| ASUSTek       | X540YA                      | [9b382500c5](https://linux-hardware.org/?probe=9b382500c5) | Oct 27, 2021 |
| Dell          | Latitude E5400              | [7049bbe182](https://linux-hardware.org/?probe=7049bbe182) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [4826046b43](https://linux-hardware.org/?probe=4826046b43) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | [b3e2853259](https://linux-hardware.org/?probe=b3e2853259) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | [5af2c96114](https://linux-hardware.org/?probe=5af2c96114) | Oct 24, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [7aac95cd60](https://linux-hardware.org/?probe=7aac95cd60) | Oct 23, 2021 |
| HP            | Notebook                    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| ASUSTek       | X555LD                      | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Lenovo        | ThinkPad T480 20L6S7PE06    | [28857899a2](https://linux-hardware.org/?probe=28857899a2) | Oct 20, 2021 |
| HP            | Compaq Presario CQ60        | [0b02aa22d4](https://linux-hardware.org/?probe=0b02aa22d4) | Oct 17, 2021 |
| HP            | Pavilion x2 Detachable      | [c17c589af5](https://linux-hardware.org/?probe=c17c589af5) | Oct 17, 2021 |
| Toshiba       | Satellite C660              | [c70057c643](https://linux-hardware.org/?probe=c70057c643) | Oct 16, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [6360789a1c](https://linux-hardware.org/?probe=6360789a1c) | Oct 14, 2021 |
| eMachines     | E520 V1.06                  | [97c667e3c0](https://linux-hardware.org/?probe=97c667e3c0) | Oct 14, 2021 |
| HP            | EliteBook 840 G3            | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| HP            | Pavilion g6                 | [5eba384acd](https://linux-hardware.org/?probe=5eba384acd) | Oct 11, 2021 |
| HP            | Notebook                    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [77a6cb9eba](https://linux-hardware.org/?probe=77a6cb9eba) | Oct 07, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [99c08de77b](https://linux-hardware.org/?probe=99c08de77b) | Oct 07, 2021 |
| HP            | G62                         | [6cbed79ca9](https://linux-hardware.org/?probe=6cbed79ca9) | Oct 05, 2021 |
| Dell          | XPS 13 7390                 | [843d9a14d4](https://linux-hardware.org/?probe=843d9a14d4) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | [b1996e39c6](https://linux-hardware.org/?probe=b1996e39c6) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | [47def5d058](https://linux-hardware.org/?probe=47def5d058) | Oct 05, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96cf9ba56a](https://linux-hardware.org/?probe=96cf9ba56a) | Sep 30, 2021 |
| ASUSTek       | X453MA                      | [782dfc1a5f](https://linux-hardware.org/?probe=782dfc1a5f) | Sep 30, 2021 |
| Toshiba       | Satellite L500              | [07116867d0](https://linux-hardware.org/?probe=07116867d0) | Sep 30, 2021 |
| Unknown       | Unknown                     | [1466ee93ee](https://linux-hardware.org/?probe=1466ee93ee) | Sep 29, 2021 |
| SLIMBOOK      | TITAN                       | [985d394a66](https://linux-hardware.org/?probe=985d394a66) | Sep 29, 2021 |
| HP            | Pavilion dv6                | [0a3653d139](https://linux-hardware.org/?probe=0a3653d139) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| HP            | Pavilion dv6                | [a5de874a12](https://linux-hardware.org/?probe=a5de874a12) | Sep 26, 2021 |
| Dell          | Latitude 5400               | [c94a87ddcd](https://linux-hardware.org/?probe=c94a87ddcd) | Sep 26, 2021 |
| Fujitsu       | LIFEBOOK AH552/SL           | [adefc47ea8](https://linux-hardware.org/?probe=adefc47ea8) | Sep 22, 2021 |
| Toshiba       | PORTEGE Z30-A               | [13b9ce0773](https://linux-hardware.org/?probe=13b9ce0773) | Sep 22, 2021 |
| HP            | Laptop 15-bs0xx             | [6a1f29d17c](https://linux-hardware.org/?probe=6a1f29d17c) | Sep 22, 2021 |
| Dynabook      | PORTEGE X50-G               | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [8a14f4f8ce](https://linux-hardware.org/?probe=8a14f4f8ce) | Sep 20, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [61fd64b037](https://linux-hardware.org/?probe=61fd64b037) | Sep 19, 2021 |
| Sony          | VGN-FZ31Z                   | [134fab4631](https://linux-hardware.org/?probe=134fab4631) | Sep 17, 2021 |
| Sony          | VGN-FZ31Z                   | [78a5f6cc5b](https://linux-hardware.org/?probe=78a5f6cc5b) | Sep 16, 2021 |
| Sony          | VGN-FZ31Z                   | [fd9704ad22](https://linux-hardware.org/?probe=fd9704ad22) | Sep 16, 2021 |
| ASUSTek       | F5SL                        | [e6e93168a6](https://linux-hardware.org/?probe=e6e93168a6) | Sep 15, 2021 |
| Sony          | VGN-FZ21M                   | [f68a8cedaa](https://linux-hardware.org/?probe=f68a8cedaa) | Sep 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [232a307a5b](https://linux-hardware.org/?probe=232a307a5b) | Sep 14, 2021 |
| Acer          | Aspire ES1-520              | [4b4f263238](https://linux-hardware.org/?probe=4b4f263238) | Sep 14, 2021 |
| Intel         | powered classmate PC        | [15cb9c7764](https://linux-hardware.org/?probe=15cb9c7764) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [bfe6584c68](https://linux-hardware.org/?probe=bfe6584c68) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [e82ca3db5b](https://linux-hardware.org/?probe=e82ca3db5b) | Sep 12, 2021 |
| MSI           | GE75 Raider 8RF             | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [13d65a1a4e](https://linux-hardware.org/?probe=13d65a1a4e) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [c50b07bfbc](https://linux-hardware.org/?probe=c50b07bfbc) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [24053a2921](https://linux-hardware.org/?probe=24053a2921) | Sep 07, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [b34fb7492d](https://linux-hardware.org/?probe=b34fb7492d) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e65bcd50d4](https://linux-hardware.org/?probe=e65bcd50d4) | Sep 05, 2021 |
| ASUSTek       | K53SV                       | [f617f97f20](https://linux-hardware.org/?probe=f617f97f20) | Sep 03, 2021 |
| Dell          | XPS 13 7390                 | [be1de37337](https://linux-hardware.org/?probe=be1de37337) | Sep 03, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [62e286b6bc](https://linux-hardware.org/?probe=62e286b6bc) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [84ed2a684d](https://linux-hardware.org/?probe=84ed2a684d) | Aug 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6d630f76dc](https://linux-hardware.org/?probe=6d630f76dc) | Aug 30, 2021 |
| Apple         | MacBookAir3,1               | [c431035e14](https://linux-hardware.org/?probe=c431035e14) | Aug 28, 2021 |
| HP            | EliteBook 820 G1            | [fcfdefc5ce](https://linux-hardware.org/?probe=fcfdefc5ce) | Aug 24, 2021 |
| Acer          | Aspire one 1-431            | [1d73bf7163](https://linux-hardware.org/?probe=1d73bf7163) | Aug 23, 2021 |
| HP            | Compaq Presario CQ50        | [afde6653db](https://linux-hardware.org/?probe=afde6653db) | Aug 20, 2021 |
| ASUSTek       | K52Je                       | [d35de28c56](https://linux-hardware.org/?probe=d35de28c56) | Aug 17, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [c2dee4fe1c](https://linux-hardware.org/?probe=c2dee4fe1c) | Aug 14, 2021 |
| HP            | Compaq Presario CQ71        | [c1e4d1748b](https://linux-hardware.org/?probe=c1e4d1748b) | Aug 14, 2021 |
| ASUSTek       | K52Je                       | [ae9629c543](https://linux-hardware.org/?probe=ae9629c543) | Aug 13, 2021 |
| Teclast       | TbooK 11                    | [d045383640](https://linux-hardware.org/?probe=d045383640) | Aug 12, 2021 |
| Teclast       | TbooK 11                    | [f3e17cb791](https://linux-hardware.org/?probe=f3e17cb791) | Aug 12, 2021 |
| ASUSTek       | X541UV                      | [3f45acb762](https://linux-hardware.org/?probe=3f45acb762) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3fb07ec1ab](https://linux-hardware.org/?probe=3fb07ec1ab) | Aug 11, 2021 |
| MSI           | Alpha 15 A4DEK              | [f8bd1ccc54](https://linux-hardware.org/?probe=f8bd1ccc54) | Aug 09, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| MSI           | Alpha 15 A4DEK              | [77c994366c](https://linux-hardware.org/?probe=77c994366c) | Aug 04, 2021 |
| Apple         | MacBookPro8,1               | [ea96dd2fc0](https://linux-hardware.org/?probe=ea96dd2fc0) | Aug 03, 2021 |
| Acer          | Extensa 5635ZG              | [7b18fd92ec](https://linux-hardware.org/?probe=7b18fd92ec) | Aug 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [dde43dfc5f](https://linux-hardware.org/?probe=dde43dfc5f) | Jul 31, 2021 |
| Acer          | Extensa 5635ZG              | [920920b284](https://linux-hardware.org/?probe=920920b284) | Jul 30, 2021 |
| HP            | EliteBook 840 G1            | [a4d0bd11cf](https://linux-hardware.org/?probe=a4d0bd11cf) | Jul 30, 2021 |
| Packard Be... | EasyNote MB65               | [f659f0645c](https://linux-hardware.org/?probe=f659f0645c) | Jul 28, 2021 |
| Toshiba       | Satellite L50-B             | [0e3d86e5fc](https://linux-hardware.org/?probe=0e3d86e5fc) | Jul 28, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [e877303c3f](https://linux-hardware.org/?probe=e877303c3f) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| ASUSTek       | X550DP                      | [fab8695920](https://linux-hardware.org/?probe=fab8695920) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [a2ba4d937e](https://linux-hardware.org/?probe=a2ba4d937e) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N3S27C00    | [f4f26a9357](https://linux-hardware.org/?probe=f4f26a9357) | Jul 24, 2021 |
| Sony          | VGN-AW21Z_B                 | [16afdefee9](https://linux-hardware.org/?probe=16afdefee9) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [ad8fb39682](https://linux-hardware.org/?probe=ad8fb39682) | Jul 23, 2021 |
| Lenovo        | ThinkPad T480 20L5S03600    | [996bc7336f](https://linux-hardware.org/?probe=996bc7336f) | Jul 23, 2021 |
| Lenovo        | ThinkPad T480 20L5S03600    | [84d70d9bde](https://linux-hardware.org/?probe=84d70d9bde) | Jul 23, 2021 |
| Toshiba       | Satellite M70               | [ffe4b92da3](https://linux-hardware.org/?probe=ffe4b92da3) | Jul 21, 2021 |
| Toshiba       | Satellite C50-B             | [288b6b0769](https://linux-hardware.org/?probe=288b6b0769) | Jul 16, 2021 |
| Toshiba       | Satellite P50-C             | [3b8ead252b](https://linux-hardware.org/?probe=3b8ead252b) | Jul 15, 2021 |
| HP            | Compaq Presario CQ71        | [d26cb48393](https://linux-hardware.org/?probe=d26cb48393) | Jul 14, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [9d1dfce344](https://linux-hardware.org/?probe=9d1dfce344) | Jul 13, 2021 |
| ASUSTek       | T100HAN                     | [9d9f33c5e5](https://linux-hardware.org/?probe=9d9f33c5e5) | Jul 12, 2021 |
| Acer          | NC-V3-575G-58LU             | [da6da7fbd6](https://linux-hardware.org/?probe=da6da7fbd6) | Jul 11, 2021 |
| ASUSTek       | G50V                        | [ec1ddd4644](https://linux-hardware.org/?probe=ec1ddd4644) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| Dell          | Latitude D530               | [d48cd58890](https://linux-hardware.org/?probe=d48cd58890) | Jul 09, 2021 |
| Dell          | Precision M4600             | [388aad414f](https://linux-hardware.org/?probe=388aad414f) | Jul 08, 2021 |
| Dell          | Latitude D530               | [21ad721b61](https://linux-hardware.org/?probe=21ad721b61) | Jul 07, 2021 |
| SLIMBOOK      | TITAN                       | [59233d0bff](https://linux-hardware.org/?probe=59233d0bff) | Jul 07, 2021 |
| Acer          | Aspire 5738                 | [77c0819e0f](https://linux-hardware.org/?probe=77c0819e0f) | Jul 07, 2021 |
| Toshiba       | Satellite C50-B             | [0bdc8750c3](https://linux-hardware.org/?probe=0bdc8750c3) | Jul 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [0e79f21646](https://linux-hardware.org/?probe=0e79f21646) | Jul 05, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d6ef1b054b](https://linux-hardware.org/?probe=d6ef1b054b) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3430744d8](https://linux-hardware.org/?probe=f3430744d8) | Jun 24, 2021 |
| HP            | ENVY 17                     | [c6b33cf692](https://linux-hardware.org/?probe=c6b33cf692) | Jun 22, 2021 |
| HP            | EliteBook 820 G1            | [46e46cdce1](https://linux-hardware.org/?probe=46e46cdce1) | Jun 20, 2021 |
| Dell          | XPS 13 9305                 | [02ee8d11bc](https://linux-hardware.org/?probe=02ee8d11bc) | Jun 19, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Dell          | XPS 13 9305                 | [d1799a89c4](https://linux-hardware.org/?probe=d1799a89c4) | Jun 17, 2021 |
| Dell          | Latitude E6520              | [718e90b724](https://linux-hardware.org/?probe=718e90b724) | Jun 17, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [b796c5a183](https://linux-hardware.org/?probe=b796c5a183) | Jun 16, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| SLIMBOOK      | PROX15-INTEL                | [f471ae0176](https://linux-hardware.org/?probe=f471ae0176) | Jun 15, 2021 |
| ASUSTek       | K73SV                       | [228feaed8e](https://linux-hardware.org/?probe=228feaed8e) | Jun 12, 2021 |
| Google        | Coral                       | [f6cf3ed923](https://linux-hardware.org/?probe=f6cf3ed923) | Jun 11, 2021 |
| HP            | Slate 2                     | [0d820f363e](https://linux-hardware.org/?probe=0d820f363e) | Jun 10, 2021 |
| HP            | Slate 2                     | [ecb6d7d96f](https://linux-hardware.org/?probe=ecb6d7d96f) | Jun 10, 2021 |
| Acer          | Extensa 5635ZG              | [540d6fca8e](https://linux-hardware.org/?probe=540d6fca8e) | Jun 07, 2021 |
| Acer          | Aspire E5-523G              | [b092f36afc](https://linux-hardware.org/?probe=b092f36afc) | Jun 06, 2021 |
| HP            | ProBook 4520s               | [87f9426157](https://linux-hardware.org/?probe=87f9426157) | Jun 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [25a53bf5a0](https://linux-hardware.org/?probe=25a53bf5a0) | Jun 05, 2021 |
| Dell          | Precision M4600             | [b1bc313622](https://linux-hardware.org/?probe=b1bc313622) | Jun 04, 2021 |
| ASUSTek       | T100HAN                     | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| Toshiba       | Satellite C660D             | [39a33d288a](https://linux-hardware.org/?probe=39a33d288a) | Jun 03, 2021 |
| HP            | ProBook 450 G6              | [af16143ad8](https://linux-hardware.org/?probe=af16143ad8) | Jun 03, 2021 |
| Toshiba       | PORTEGE Z930                | [4a95259edd](https://linux-hardware.org/?probe=4a95259edd) | Jun 03, 2021 |
| Acer          | Aspire A315-41              | [15de6a42cc](https://linux-hardware.org/?probe=15de6a42cc) | Jun 01, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [0540d35606](https://linux-hardware.org/?probe=0540d35606) | May 31, 2021 |
| ASUSTek       | T100HAN                     | [ca42a42366](https://linux-hardware.org/?probe=ca42a42366) | May 30, 2021 |
| Acer          | Aspire ES1-572              | [c16c3f3c20](https://linux-hardware.org/?probe=c16c3f3c20) | May 29, 2021 |
| Samsung       | 700T                        | [374154a439](https://linux-hardware.org/?probe=374154a439) | May 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [430907546b](https://linux-hardware.org/?probe=430907546b) | May 29, 2021 |
| HP            | Pavilion g6                 | [03f3d2f19b](https://linux-hardware.org/?probe=03f3d2f19b) | May 27, 2021 |
| ASUSTek       | X555LD                      | [a0ab13de0b](https://linux-hardware.org/?probe=a0ab13de0b) | May 26, 2021 |
| ASUSTek       | T100HAN                     | [20badd4bf8](https://linux-hardware.org/?probe=20badd4bf8) | May 24, 2021 |
| HUAWEI        | WRT-WX9                     | [8865e5f33f](https://linux-hardware.org/?probe=8865e5f33f) | May 21, 2021 |
| ASUSTek       | X540YA                      | [c7d85ee10a](https://linux-hardware.org/?probe=c7d85ee10a) | May 21, 2021 |
| Toshiba       | PORTEGE Z930                | [e006b8bf83](https://linux-hardware.org/?probe=e006b8bf83) | May 18, 2021 |
| ASUSTek       | X541UJ                      | [0fc9152ae2](https://linux-hardware.org/?probe=0fc9152ae2) | May 16, 2021 |
| Acer          | Aspire E5-411               | [e9004a67e9](https://linux-hardware.org/?probe=e9004a67e9) | May 16, 2021 |
| HP            | EliteBook Folio 1040 G1     | [1e47d123cc](https://linux-hardware.org/?probe=1e47d123cc) | May 15, 2021 |
| ASUSTek       | T100HAN                     | [7195f02080](https://linux-hardware.org/?probe=7195f02080) | May 13, 2021 |
| ASUSTek       | 1215N                       | [2e4383bd79](https://linux-hardware.org/?probe=2e4383bd79) | May 13, 2021 |
| Acer          | Aspire 5750                 | [51386797f0](https://linux-hardware.org/?probe=51386797f0) | May 11, 2021 |
| HP            | Laptop 17-ak0xx             | [b2207b19c0](https://linux-hardware.org/?probe=b2207b19c0) | May 09, 2021 |
| INSYS         | CD9-G148                    | [162b7d2dd4](https://linux-hardware.org/?probe=162b7d2dd4) | May 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [34b008d2a3](https://linux-hardware.org/?probe=34b008d2a3) | May 06, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [8edf563281](https://linux-hardware.org/?probe=8edf563281) | May 03, 2021 |
| eMachines     | eME728                      | [9c098c150f](https://linux-hardware.org/?probe=9c098c150f) | May 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [8956498c75](https://linux-hardware.org/?probe=8956498c75) | Apr 29, 2021 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [b3a280cc6b](https://linux-hardware.org/?probe=b3a280cc6b) | Apr 29, 2021 |
| Positivo      | H14BU08                     | [0074b53665](https://linux-hardware.org/?probe=0074b53665) | Apr 28, 2021 |
| ASUSTek       | K73SV                       | [d810797575](https://linux-hardware.org/?probe=d810797575) | Apr 28, 2021 |
| ASUSTek       | K73SV                       | [b70e4fe78b](https://linux-hardware.org/?probe=b70e4fe78b) | Apr 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bf2ec3a69c](https://linux-hardware.org/?probe=bf2ec3a69c) | Apr 26, 2021 |
| ASUSTek       | X555LJ                      | [3febe6795e](https://linux-hardware.org/?probe=3febe6795e) | Apr 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [0bcc333251](https://linux-hardware.org/?probe=0bcc333251) | Apr 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [508213fd9c](https://linux-hardware.org/?probe=508213fd9c) | Apr 25, 2021 |
| JPSaCouto     | Intel powered classmate ... | [f82c8e8839](https://linux-hardware.org/?probe=f82c8e8839) | Apr 25, 2021 |
| JPSaCouto     | Intel powered classmate ... | [bcca68ee1a](https://linux-hardware.org/?probe=bcca68ee1a) | Apr 25, 2021 |
| HP            | Laptop 15-gw0xxx            | [bbb889a0ca](https://linux-hardware.org/?probe=bbb889a0ca) | Apr 25, 2021 |
| ASUSTek       | T100HAN                     | [a8ff3e1736](https://linux-hardware.org/?probe=a8ff3e1736) | Apr 22, 2021 |
| ASUSTek       | T100HAN                     | [2c4f2ffa49](https://linux-hardware.org/?probe=2c4f2ffa49) | Apr 20, 2021 |
| Dell          | XPS 13 7390                 | [b1801d62cb](https://linux-hardware.org/?probe=b1801d62cb) | Apr 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a008c4e692](https://linux-hardware.org/?probe=a008c4e692) | Apr 19, 2021 |
| ASUSTek       | T100HAN                     | [5ff0bb6a88](https://linux-hardware.org/?probe=5ff0bb6a88) | Apr 18, 2021 |
| Toshiba       | Satellite L50D-B            | [4b47248331](https://linux-hardware.org/?probe=4b47248331) | Apr 18, 2021 |
| Toshiba       | Satellite L50D-B            | [2df86fbb1c](https://linux-hardware.org/?probe=2df86fbb1c) | Apr 18, 2021 |
| Sony          | VGN-FZ140N                  | [b46e85cdb2](https://linux-hardware.org/?probe=b46e85cdb2) | Apr 17, 2021 |
| HP            | Pavilion dv6                | [cc367d13cf](https://linux-hardware.org/?probe=cc367d13cf) | Apr 16, 2021 |
| HP            | Pavilion dv6                | [d5b4576543](https://linux-hardware.org/?probe=d5b4576543) | Apr 16, 2021 |
| Lenovo        | B50-10 80QR                 | [a5d4730bbe](https://linux-hardware.org/?probe=a5d4730bbe) | Apr 16, 2021 |
| HP            | Pavilion dv6                | [10a2c15ac0](https://linux-hardware.org/?probe=10a2c15ac0) | Apr 12, 2021 |
| Dell          | XPS 13 7390                 | [2c074aa232](https://linux-hardware.org/?probe=2c074aa232) | Apr 12, 2021 |
| Toshiba       | Satellite L40               | [0f6ed90100](https://linux-hardware.org/?probe=0f6ed90100) | Apr 11, 2021 |
| HP            | Pavilion dv6                | [5c83ad0f56](https://linux-hardware.org/?probe=5c83ad0f56) | Apr 10, 2021 |
| Toshiba       | Satellite L650              | [5652130b72](https://linux-hardware.org/?probe=5652130b72) | Apr 09, 2021 |
| Acer          | Aspire A515-51G             | [0af274abed](https://linux-hardware.org/?probe=0af274abed) | Apr 03, 2021 |
| Acer          | Aspire A515-51G             | [21263e72df](https://linux-hardware.org/?probe=21263e72df) | Apr 03, 2021 |
| eMachines     | eME728                      | [1db163e222](https://linux-hardware.org/?probe=1db163e222) | Apr 02, 2021 |
| Dell          | Latitude E5410              | [5d8f94313f](https://linux-hardware.org/?probe=5d8f94313f) | Apr 02, 2021 |
| Acer          | Aspire A315-41              | [2ba4e8be53](https://linux-hardware.org/?probe=2ba4e8be53) | Apr 02, 2021 |
| Phoenix/Si... | M7X0SU                      | [44b42fe693](https://linux-hardware.org/?probe=44b42fe693) | Apr 02, 2021 |
| HP            | Pavilion dv6                | [9d7000a50b](https://linux-hardware.org/?probe=9d7000a50b) | Mar 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [859d3df16d](https://linux-hardware.org/?probe=859d3df16d) | Mar 30, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [8d09fd5fad](https://linux-hardware.org/?probe=8d09fd5fad) | Mar 29, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [417973ae47](https://linux-hardware.org/?probe=417973ae47) | Mar 27, 2021 |
| Lenovo        | ThinkPad X390 20Q1S17H02    | [8a1509f6f9](https://linux-hardware.org/?probe=8a1509f6f9) | Mar 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | [804865062f](https://linux-hardware.org/?probe=804865062f) | Mar 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [186f54f898](https://linux-hardware.org/?probe=186f54f898) | Mar 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [36ba280ff4](https://linux-hardware.org/?probe=36ba280ff4) | Mar 20, 2021 |
| HP            | Compaq Presario CQ60        | [29b5b3b3c4](https://linux-hardware.org/?probe=29b5b3b3c4) | Mar 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcb52364ec](https://linux-hardware.org/?probe=bcb52364ec) | Mar 18, 2021 |
| ASUSTek       | T100HAN                     | [4d004db7b4](https://linux-hardware.org/?probe=4d004db7b4) | Mar 17, 2021 |
| ASUSTek       | T100HAN                     | [375e68fd9f](https://linux-hardware.org/?probe=375e68fd9f) | Mar 17, 2021 |
| Toshiba       | Satellite T110              | [e974c29a53](https://linux-hardware.org/?probe=e974c29a53) | Mar 17, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1WS0... | [616d32ae4b](https://linux-hardware.org/?probe=616d32ae4b) | Mar 16, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1WS0... | [67f54ece11](https://linux-hardware.org/?probe=67f54ece11) | Mar 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [bcdd60dc85](https://linux-hardware.org/?probe=bcdd60dc85) | Mar 14, 2021 |
| Lenovo        | ThinkPad R400 7443E1G       | [10584ae27b](https://linux-hardware.org/?probe=10584ae27b) | Mar 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [14d6107700](https://linux-hardware.org/?probe=14d6107700) | Mar 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [3043c4c8ed](https://linux-hardware.org/?probe=3043c4c8ed) | Mar 13, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [edbe4b927f](https://linux-hardware.org/?probe=edbe4b927f) | Mar 12, 2021 |
| MSI           | Prestige 15 A10SC           | [6bcf98bb2b](https://linux-hardware.org/?probe=6bcf98bb2b) | Mar 10, 2021 |
| Alienware     | 17 R3                       | [8582334b5a](https://linux-hardware.org/?probe=8582334b5a) | Mar 10, 2021 |
| HP            | G62                         | [2be248991e](https://linux-hardware.org/?probe=2be248991e) | Mar 08, 2021 |
| Acer          | Aspire E5-521               | [d2ee782761](https://linux-hardware.org/?probe=d2ee782761) | Mar 07, 2021 |
| HP            | G62                         | [4d4a5d0369](https://linux-hardware.org/?probe=4d4a5d0369) | Mar 07, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [0f1bf2c9c8](https://linux-hardware.org/?probe=0f1bf2c9c8) | Mar 06, 2021 |
| Acer          | Aspire 5551G                | [eb7deed365](https://linux-hardware.org/?probe=eb7deed365) | Mar 05, 2021 |
| ASUSTek       | X102BA                      | [5b648fcc6b](https://linux-hardware.org/?probe=5b648fcc6b) | Mar 04, 2021 |
| Lenovo        | ThinkPad SL500 27466CS      | [f2d482cf8d](https://linux-hardware.org/?probe=f2d482cf8d) | Mar 02, 2021 |
| HP            | Pavilion x2 Detachable      | [9eb3ae4c15](https://linux-hardware.org/?probe=9eb3ae4c15) | Feb 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [83587f3565](https://linux-hardware.org/?probe=83587f3565) | Feb 25, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [c584e27b6c](https://linux-hardware.org/?probe=c584e27b6c) | Feb 25, 2021 |
| Apple         | MacBookPro9,2               | [7a2466e991](https://linux-hardware.org/?probe=7a2466e991) | Feb 25, 2021 |
| Acer          | Aspire E5-573G              | [55a00ca46d](https://linux-hardware.org/?probe=55a00ca46d) | Feb 24, 2021 |
| Sony          | 91                          | [adfdcf1669](https://linux-hardware.org/?probe=adfdcf1669) | Feb 24, 2021 |
| HP            | Laptop 15-da0xxx            | [86f60bbc44](https://linux-hardware.org/?probe=86f60bbc44) | Feb 23, 2021 |
| HP            | Laptop 15-da0xxx            | [6a9341e4ab](https://linux-hardware.org/?probe=6a9341e4ab) | Feb 22, 2021 |
| Acer          | Aspire ES1-512              | [cfc54d6468](https://linux-hardware.org/?probe=cfc54d6468) | Feb 21, 2021 |
| Acer          | Aspire E5-521G              | [7b0155df52](https://linux-hardware.org/?probe=7b0155df52) | Feb 20, 2021 |
| Apple         | MacBookPro9,2               | [022bccde17](https://linux-hardware.org/?probe=022bccde17) | Feb 19, 2021 |
| HP            | G62                         | [bf7d5b9736](https://linux-hardware.org/?probe=bf7d5b9736) | Feb 19, 2021 |
| Sony          | SVE1512C6EW                 | [477d0e5a6d](https://linux-hardware.org/?probe=477d0e5a6d) | Feb 17, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [2e3039e232](https://linux-hardware.org/?probe=2e3039e232) | Feb 15, 2021 |
| ASUSTek       | X555LD                      | [78355d7193](https://linux-hardware.org/?probe=78355d7193) | Feb 14, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [ba8153abd8](https://linux-hardware.org/?probe=ba8153abd8) | Feb 14, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [3cc715f92a](https://linux-hardware.org/?probe=3cc715f92a) | Feb 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [c097a16392](https://linux-hardware.org/?probe=c097a16392) | Feb 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [252b674af4](https://linux-hardware.org/?probe=252b674af4) | Feb 14, 2021 |
| Acer          | Aspire 5732Z                | [a72e26c3bd](https://linux-hardware.org/?probe=a72e26c3bd) | Feb 14, 2021 |
| HP            | G62                         | [3acbc7c7e3](https://linux-hardware.org/?probe=3acbc7c7e3) | Feb 13, 2021 |
| MSI           | GS65 Stealth Thin 8RE       | [d948546be2](https://linux-hardware.org/?probe=d948546be2) | Feb 13, 2021 |
| MSI           | GS65 Stealth Thin 8RE       | [63e4ddb6a6](https://linux-hardware.org/?probe=63e4ddb6a6) | Feb 13, 2021 |
| HP            | Pavilion Notebook           | [fcc62099b2](https://linux-hardware.org/?probe=fcc62099b2) | Feb 13, 2021 |
| Toshiba       | Satellite M50D-A            | [248337d69a](https://linux-hardware.org/?probe=248337d69a) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [922c8b7dfd](https://linux-hardware.org/?probe=922c8b7dfd) | Feb 11, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [e2f6310b33](https://linux-hardware.org/?probe=e2f6310b33) | Feb 11, 2021 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [57f509711d](https://linux-hardware.org/?probe=57f509711d) | Feb 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [1ddd62bb74](https://linux-hardware.org/?probe=1ddd62bb74) | Feb 10, 2021 |
| HP            | Compaq Presario CQ61        | [88bc30b5c4](https://linux-hardware.org/?probe=88bc30b5c4) | Feb 07, 2021 |
| HP            | Pavilion dv5                | [25a5b76a4b](https://linux-hardware.org/?probe=25a5b76a4b) | Feb 07, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b94aa04034](https://linux-hardware.org/?probe=b94aa04034) | Feb 06, 2021 |
| ASUSTek       | E203NAS                     | [a97e612dd4](https://linux-hardware.org/?probe=a97e612dd4) | Feb 05, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [33311133f5](https://linux-hardware.org/?probe=33311133f5) | Feb 03, 2021 |
| HP            | G62                         | [af6f8ed7d3](https://linux-hardware.org/?probe=af6f8ed7d3) | Feb 01, 2021 |
| Notebook      | N2x0WU                      | [fad3702ef5](https://linux-hardware.org/?probe=fad3702ef5) | Feb 01, 2021 |
| HP            | Compaq Presario CQ50        | [98a871c74d](https://linux-hardware.org/?probe=98a871c74d) | Feb 01, 2021 |
| HP            | ProBook 6550b               | [b41bf411ae](https://linux-hardware.org/?probe=b41bf411ae) | Jan 31, 2021 |
| Toshiba       | Satellite C50D-B            | [5b1624d2fa](https://linux-hardware.org/?probe=5b1624d2fa) | Jan 31, 2021 |
| ASUSTek       | S400CA                      | [9749eb6d22](https://linux-hardware.org/?probe=9749eb6d22) | Jan 31, 2021 |
| Acer          | Aspire E1-570G              | [19e6d6afd7](https://linux-hardware.org/?probe=19e6d6afd7) | Jan 28, 2021 |
| HP            | ProBook 6550b               | [90cc726402](https://linux-hardware.org/?probe=90cc726402) | Jan 27, 2021 |
| Acer          | Aspire E1-570G              | [f8f4880823](https://linux-hardware.org/?probe=f8f4880823) | Jan 26, 2021 |
| Clevo         | W760T/M740T/M760T           | [4b75664c6f](https://linux-hardware.org/?probe=4b75664c6f) | Jan 25, 2021 |
| MSI           | GF75 Thin 10SCSR            | [7a6ed88f27](https://linux-hardware.org/?probe=7a6ed88f27) | Jan 24, 2021 |
| MSI           | GF75 Thin 10SCSR            | [f04b769e0d](https://linux-hardware.org/?probe=f04b769e0d) | Jan 24, 2021 |
| ASUSTek       | X541UVK                     | [bb710f7faa](https://linux-hardware.org/?probe=bb710f7faa) | Jan 23, 2021 |
| ASUSTek       | X541UVK                     | [541bbe8e75](https://linux-hardware.org/?probe=541bbe8e75) | Jan 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [6eb0721a80](https://linux-hardware.org/?probe=6eb0721a80) | Jan 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF07    | [fab6e1d3ad](https://linux-hardware.org/?probe=fab6e1d3ad) | Jan 21, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF07    | [5311f338e0](https://linux-hardware.org/?probe=5311f338e0) | Jan 21, 2021 |
| Acer          | Aspire E5-521               | [50ee0ac068](https://linux-hardware.org/?probe=50ee0ac068) | Jan 20, 2021 |
| ASUSTek       | N56VZ                       | [039ce9b983](https://linux-hardware.org/?probe=039ce9b983) | Jan 19, 2021 |
| HP            | ProBook 6475b               | [82693f57b0](https://linux-hardware.org/?probe=82693f57b0) | Jan 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [313cc475fc](https://linux-hardware.org/?probe=313cc475fc) | Jan 11, 2021 |
| Notebook      | NV4XMZ                      | [130719e683](https://linux-hardware.org/?probe=130719e683) | Jan 09, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [ffeb181a7f](https://linux-hardware.org/?probe=ffeb181a7f) | Jan 08, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [5b2eb10b23](https://linux-hardware.org/?probe=5b2eb10b23) | Jan 08, 2021 |
| Lenovo        | ThinkPad T480 20L6SEH700    | [cce564cea6](https://linux-hardware.org/?probe=cce564cea6) | Jan 07, 2021 |
| HP            | Compaq Presario CQ61        | [87076627c9](https://linux-hardware.org/?probe=87076627c9) | Jan 04, 2021 |
| HP            | ProBook 6475b               | [31a4449ada](https://linux-hardware.org/?probe=31a4449ada) | Dec 30, 2020 |
| HP            | EliteBook 745 G6            | [abbb1bd093](https://linux-hardware.org/?probe=abbb1bd093) | Dec 28, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [a37f3f2e39](https://linux-hardware.org/?probe=a37f3f2e39) | Dec 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7deeb9d310](https://linux-hardware.org/?probe=7deeb9d310) | Dec 28, 2020 |
| Toshiba       | Satellite Pro L770-14H      | [82de56046c](https://linux-hardware.org/?probe=82de56046c) | Dec 27, 2020 |
| Acer          | Aspire 5715Z                | [8e6e0fd1c6](https://linux-hardware.org/?probe=8e6e0fd1c6) | Dec 24, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [0405731f25](https://linux-hardware.org/?probe=0405731f25) | Dec 23, 2020 |
| Toshiba       | Satellite P70-B             | [ec3a105576](https://linux-hardware.org/?probe=ec3a105576) | Dec 23, 2020 |
| Chuwi         | AeroBook                    | [94ca964c09](https://linux-hardware.org/?probe=94ca964c09) | Dec 21, 2020 |
| Chuwi         | AeroBook                    | [2639bb9e02](https://linux-hardware.org/?probe=2639bb9e02) | Dec 20, 2020 |
| Acer          | Aspire E1-570G              | [54c4be3905](https://linux-hardware.org/?probe=54c4be3905) | Dec 19, 2020 |
| HP            | HDX18                       | [933b4f749c](https://linux-hardware.org/?probe=933b4f749c) | Dec 18, 2020 |
| Lenovo        | ThinkPad X201 3680U18       | [ad31517eff](https://linux-hardware.org/?probe=ad31517eff) | Dec 18, 2020 |
| HP            | ProBook 6475b               | [c00a760aca](https://linux-hardware.org/?probe=c00a760aca) | Dec 18, 2020 |
| ASUSTek       | M51Vr                       | [a389e8ebce](https://linux-hardware.org/?probe=a389e8ebce) | Dec 18, 2020 |
| Toshiba       | TECRA R840                  | [731c5ca5c0](https://linux-hardware.org/?probe=731c5ca5c0) | Dec 16, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [ea3546c2f4](https://linux-hardware.org/?probe=ea3546c2f4) | Dec 16, 2020 |
| HP            | OMEN by Laptop 15-dc0xxx    | [3da605fec6](https://linux-hardware.org/?probe=3da605fec6) | Dec 14, 2020 |
| Samsung       | 530U4E/540U4E               | [415b67ede5](https://linux-hardware.org/?probe=415b67ede5) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| HP            | ProBook 6475b               | [e9ec659df5](https://linux-hardware.org/?probe=e9ec659df5) | Dec 07, 2020 |
| PC Special... | GK5NR0O                     | [1dfbed1284](https://linux-hardware.org/?probe=1dfbed1284) | Dec 05, 2020 |
| Acer          | Aspire ES1-512              | [575ce0ade3](https://linux-hardware.org/?probe=575ce0ade3) | Dec 04, 2020 |
| HP            | EliteBook 2560p             | [704777ce16](https://linux-hardware.org/?probe=704777ce16) | Dec 03, 2020 |
| Fujitsu       | STYLISTIC Q704              | [caa54ddfda](https://linux-hardware.org/?probe=caa54ddfda) | Dec 02, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [bb94d818b6](https://linux-hardware.org/?probe=bb94d818b6) | Nov 27, 2020 |
| HP            | OMEN by Laptop              | [0aa60b7f1f](https://linux-hardware.org/?probe=0aa60b7f1f) | Nov 27, 2020 |
| HP            | Laptop 15s-eq0xxx           | [4932c526f1](https://linux-hardware.org/?probe=4932c526f1) | Nov 26, 2020 |
| HUAWEI        | WRT-WX9                     | [a247637afb](https://linux-hardware.org/?probe=a247637afb) | Nov 23, 2020 |
| Toshiba       | Satellite L40               | [6dcbbd7118](https://linux-hardware.org/?probe=6dcbbd7118) | Nov 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [19118ea389](https://linux-hardware.org/?probe=19118ea389) | Nov 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [0429ace281](https://linux-hardware.org/?probe=0429ace281) | Nov 21, 2020 |
| ASUSTek       | X540LJ                      | [57ffeceb02](https://linux-hardware.org/?probe=57ffeceb02) | Nov 21, 2020 |
| Lenovo        | ThinkPad T430 2349V4B       | [989a5dd973](https://linux-hardware.org/?probe=989a5dd973) | Nov 20, 2020 |
| HP            | ProBook 6475b               | [973a088e4b](https://linux-hardware.org/?probe=973a088e4b) | Nov 18, 2020 |
| Acer          | Aspire A315-55G             | [2faf707e94](https://linux-hardware.org/?probe=2faf707e94) | Nov 18, 2020 |
| Acer          | Aspire ES1-512              | [53302b8e3b](https://linux-hardware.org/?probe=53302b8e3b) | Nov 18, 2020 |
| Acer          | Aspire ES1-512              | [af75ae9ad7](https://linux-hardware.org/?probe=af75ae9ad7) | Nov 18, 2020 |
| Acer          | Aspire E1-570G              | [3ac799a86e](https://linux-hardware.org/?probe=3ac799a86e) | Nov 17, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [5f82a45024](https://linux-hardware.org/?probe=5f82a45024) | Nov 17, 2020 |
| HP            | Pavilion dv6                | [15406baef7](https://linux-hardware.org/?probe=15406baef7) | Nov 16, 2020 |
| Toshiba       | Satellite C660              | [a5ce6d0206](https://linux-hardware.org/?probe=a5ce6d0206) | Nov 11, 2020 |
| HP            | EliteBook 8470p             | [4efe41437c](https://linux-hardware.org/?probe=4efe41437c) | Nov 10, 2020 |
| Toshiba       | Satellite A300              | [2caf4e2e66](https://linux-hardware.org/?probe=2caf4e2e66) | Nov 09, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ae8eac8bfa](https://linux-hardware.org/?probe=ae8eac8bfa) | Nov 09, 2020 |
| Lenovo        | ThinkPad T470 20HD005NPG    | [85783d0461](https://linux-hardware.org/?probe=85783d0461) | Nov 09, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [b5a263b4b2](https://linux-hardware.org/?probe=b5a263b4b2) | Nov 08, 2020 |
| Acer          | Aspire F5-573G              | [dec186ab5a](https://linux-hardware.org/?probe=dec186ab5a) | Nov 08, 2020 |
| Dell          | Inspiron N4050              | [25cad13082](https://linux-hardware.org/?probe=25cad13082) | Nov 08, 2020 |
| Lenovo        | ThinkPad E490 20N8000RPG    | [db604734d1](https://linux-hardware.org/?probe=db604734d1) | Nov 08, 2020 |
| Toshiba       | Satellite L755              | [596e65d9a3](https://linux-hardware.org/?probe=596e65d9a3) | Nov 08, 2020 |
| Toshiba       | Satellite C660              | [d5f99c156c](https://linux-hardware.org/?probe=d5f99c156c) | Nov 07, 2020 |
| Toshiba       | Satellite C660              | [45404bd97a](https://linux-hardware.org/?probe=45404bd97a) | Nov 07, 2020 |
| Toshiba       | Satellite L50-A-122         | [f8123b4683](https://linux-hardware.org/?probe=f8123b4683) | Nov 07, 2020 |
| HP            | ProBook 4520s               | [c55a9ad855](https://linux-hardware.org/?probe=c55a9ad855) | Nov 06, 2020 |
| ASUSTek       | 1001PXD                     | [d50b2e1307](https://linux-hardware.org/?probe=d50b2e1307) | Nov 05, 2020 |
| HP            | EliteBook 840 G7 Noteboo... | [220fe23808](https://linux-hardware.org/?probe=220fe23808) | Nov 03, 2020 |
| HP            | Laptop 15-da0xxx            | [4cfd6b02fc](https://linux-hardware.org/?probe=4cfd6b02fc) | Nov 02, 2020 |
| HP            | Laptop 15-da0xxx            | [d39b8abd00](https://linux-hardware.org/?probe=d39b8abd00) | Nov 02, 2020 |
| HP            | ProBook 4520s               | [963a5a268a](https://linux-hardware.org/?probe=963a5a268a) | Nov 02, 2020 |
| Lenovo        | ThinkPad X230 2325DN0       | [6e8fe08e17](https://linux-hardware.org/?probe=6e8fe08e17) | Nov 02, 2020 |
| HP            | EliteBook 840 G7 Noteboo... | [15cb102ee8](https://linux-hardware.org/?probe=15cb102ee8) | Nov 02, 2020 |
| Toshiba       | Satellite L50-A-122         | [8a8e86a89f](https://linux-hardware.org/?probe=8a8e86a89f) | Nov 02, 2020 |
| Toshiba       | Satellite L50-A-122         | [11edf88035](https://linux-hardware.org/?probe=11edf88035) | Nov 01, 2020 |
| Apple         | MacBook4,1                  | [0f9cbe4b62](https://linux-hardware.org/?probe=0f9cbe4b62) | Nov 01, 2020 |
| Acer          | TravelMate 6593             | [46917be341](https://linux-hardware.org/?probe=46917be341) | Oct 31, 2020 |
| HUAWEI        | MACHC-WAX9                  | [d1e313f801](https://linux-hardware.org/?probe=d1e313f801) | Oct 31, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [b047c6be9a](https://linux-hardware.org/?probe=b047c6be9a) | Oct 29, 2020 |
| Dell          | XPS 13 9380                 | [ed4cfd4a87](https://linux-hardware.org/?probe=ed4cfd4a87) | Oct 26, 2020 |
| Dell          | Inspiron 5458               | [1d90877f81](https://linux-hardware.org/?probe=1d90877f81) | Oct 26, 2020 |
| Dell          | Inspiron 5458               | [70e9c8c86d](https://linux-hardware.org/?probe=70e9c8c86d) | Oct 26, 2020 |
| Toshiba       | Satellite A200              | [cb8f91cd5d](https://linux-hardware.org/?probe=cb8f91cd5d) | Oct 24, 2020 |
| Lenovo        | G50-30 80G0                 | [b6cf7f3ac1](https://linux-hardware.org/?probe=b6cf7f3ac1) | Oct 24, 2020 |
| Sony          | VGN-FW180E                  | [7a48a240b3](https://linux-hardware.org/?probe=7a48a240b3) | Oct 22, 2020 |
| Apple         | MacBookAir9,1               | [cb7aac8083](https://linux-hardware.org/?probe=cb7aac8083) | Oct 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e070ae2fd4](https://linux-hardware.org/?probe=e070ae2fd4) | Oct 19, 2020 |
| Dell          | Inspiron 5570               | [225dbd1e07](https://linux-hardware.org/?probe=225dbd1e07) | Oct 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dffc9d85ac](https://linux-hardware.org/?probe=dffc9d85ac) | Oct 19, 2020 |
| ASUSTek       | M51Vr                       | [3d18405fd6](https://linux-hardware.org/?probe=3d18405fd6) | Oct 18, 2020 |
| Lenovo        | G50-70 20351                | [0f732b8d65](https://linux-hardware.org/?probe=0f732b8d65) | Oct 17, 2020 |
| HP            | Pavilion Notebook           | [9193175b26](https://linux-hardware.org/?probe=9193175b26) | Oct 14, 2020 |
| HP            | Compaq 6735s                | [6e8a85a125](https://linux-hardware.org/?probe=6e8a85a125) | Oct 14, 2020 |
| HP            | Pavilion 15                 | [cdeccc0d99](https://linux-hardware.org/?probe=cdeccc0d99) | Oct 13, 2020 |
| Dell          | XPS 13 7390                 | [cdb7cd1f54](https://linux-hardware.org/?probe=cdb7cd1f54) | Oct 13, 2020 |
| Toshiba       | Satellite P50-C             | [5a416fb424](https://linux-hardware.org/?probe=5a416fb424) | Oct 12, 2020 |
| Apple         | MacBookAir9,1               | [132912b6d5](https://linux-hardware.org/?probe=132912b6d5) | Oct 11, 2020 |
| Acer          | Aspire A315-55G             | [4a62c9205b](https://linux-hardware.org/?probe=4a62c9205b) | Oct 10, 2020 |
| Toshiba       | Satellite A660              | [b38d9e5755](https://linux-hardware.org/?probe=b38d9e5755) | Oct 10, 2020 |
| HP            | ProBook 440 G6              | [2f16a60e70](https://linux-hardware.org/?probe=2f16a60e70) | Oct 07, 2020 |
| HP            | OMEN by Laptop 15-dc1xxx    | [beb9e327ad](https://linux-hardware.org/?probe=beb9e327ad) | Oct 06, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4ec2f0a6cc](https://linux-hardware.org/?probe=4ec2f0a6cc) | Sep 29, 2020 |
| Dell          | Latitude 5480               | [9d564410ca](https://linux-hardware.org/?probe=9d564410ca) | Sep 28, 2020 |
| HP            | Stream Notebook PC 13       | [de7c2cac49](https://linux-hardware.org/?probe=de7c2cac49) | Sep 26, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [6e5da39670](https://linux-hardware.org/?probe=6e5da39670) | Sep 24, 2020 |
| Notebook      | W65_67SJ                    | [da03090968](https://linux-hardware.org/?probe=da03090968) | Sep 23, 2020 |
| ASUSTek       | F7F                         | [0ffb1837f3](https://linux-hardware.org/?probe=0ffb1837f3) | Sep 20, 2020 |
| Toshiba       | Satellite C660              | [ba30a12748](https://linux-hardware.org/?probe=ba30a12748) | Sep 19, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [7363b843fc](https://linux-hardware.org/?probe=7363b843fc) | Sep 19, 2020 |
| Phoenix/Si... | M720SR                      | [d6868a3eb3](https://linux-hardware.org/?probe=d6868a3eb3) | Sep 15, 2020 |
| Dell          | XPS 13 7390                 | [cddf6052a4](https://linux-hardware.org/?probe=cddf6052a4) | Sep 15, 2020 |
| Acer          | Aspire 7220                 | [4a9d4cd1c8](https://linux-hardware.org/?probe=4a9d4cd1c8) | Sep 15, 2020 |
| Acer          | Aspire 7220                 | [08231ea366](https://linux-hardware.org/?probe=08231ea366) | Sep 14, 2020 |
| Acer          | Aspire E5-571G              | [c10fa7f017](https://linux-hardware.org/?probe=c10fa7f017) | Sep 09, 2020 |
| Lenovo        | IdeaPad S340-14IML 81N9     | [e8d3301c2f](https://linux-hardware.org/?probe=e8d3301c2f) | Sep 09, 2020 |
| ASUSTek       | K52JU                       | [5a5da0bf01](https://linux-hardware.org/?probe=5a5da0bf01) | Sep 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f3296e1cd6](https://linux-hardware.org/?probe=f3296e1cd6) | Sep 05, 2020 |
| MSI           | GP62 2QE                    | [378c90c5a0](https://linux-hardware.org/?probe=378c90c5a0) | Sep 03, 2020 |
| HUAWEI        | WRT-WX9                     | [d957788781](https://linux-hardware.org/?probe=d957788781) | Sep 03, 2020 |
| Dell          | Latitude E6220              | [4dbb344e4e](https://linux-hardware.org/?probe=4dbb344e4e) | Sep 02, 2020 |
| Dell          | Latitude E6220              | [4a7fb29d5b](https://linux-hardware.org/?probe=4a7fb29d5b) | Sep 02, 2020 |
| Acer          | Aspire one V1.13            | [37b4d70de4](https://linux-hardware.org/?probe=37b4d70de4) | Sep 01, 2020 |
| HP            | Pavilion g6                 | [ffd9afb017](https://linux-hardware.org/?probe=ffd9afb017) | Sep 01, 2020 |
| Lenovo        | ThinkPad X220 42915D0       | [1ff043896e](https://linux-hardware.org/?probe=1ff043896e) | Aug 31, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [776a4390b7](https://linux-hardware.org/?probe=776a4390b7) | Aug 26, 2020 |
| TUXEDO        | Unknown                     | [8d654053ba](https://linux-hardware.org/?probe=8d654053ba) | Aug 25, 2020 |
| Lenovo        | ThinkPad X200 7458AK8       | [3e352fadf2](https://linux-hardware.org/?probe=3e352fadf2) | Aug 25, 2020 |
| Fujitsu       | STYLISTIC Q704              | [dbabe28124](https://linux-hardware.org/?probe=dbabe28124) | Aug 24, 2020 |
| Dell          | Inspiron 1545               | [0502d22a6e](https://linux-hardware.org/?probe=0502d22a6e) | Aug 22, 2020 |
| Dell          | Inspiron 1545               | [d4741fd8da](https://linux-hardware.org/?probe=d4741fd8da) | Aug 22, 2020 |
| Dell          | Latitude 7400               | [05a5042676](https://linux-hardware.org/?probe=05a5042676) | Aug 22, 2020 |
| HP            | Pavilion g6                 | [9bccb9af27](https://linux-hardware.org/?probe=9bccb9af27) | Aug 20, 2020 |
| MSI           | PE60 6QD                    | [3b353ca451](https://linux-hardware.org/?probe=3b353ca451) | Aug 20, 2020 |
| Dell          | Inspiron 1545               | [20a0eaa36a](https://linux-hardware.org/?probe=20a0eaa36a) | Aug 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [97b4a263d8](https://linux-hardware.org/?probe=97b4a263d8) | Aug 18, 2020 |
| ASUSTek       | K52JU                       | [e5da0afa90](https://linux-hardware.org/?probe=e5da0afa90) | Aug 18, 2020 |
| ASUSTek       | K52JU                       | [f8b66ba7f3](https://linux-hardware.org/?probe=f8b66ba7f3) | Aug 18, 2020 |
| ASUSTek       | K52JU                       | [7c0ca84517](https://linux-hardware.org/?probe=7c0ca84517) | Aug 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [29ca4e2b8c](https://linux-hardware.org/?probe=29ca4e2b8c) | Aug 17, 2020 |
| HP            | Pavilion g6                 | [8622ed021c](https://linux-hardware.org/?probe=8622ed021c) | Aug 17, 2020 |
| HP            | Pavilion g6                 | [926ccd304f](https://linux-hardware.org/?probe=926ccd304f) | Aug 15, 2020 |
| Acer          | Aspire one V1.13            | [c2802686dc](https://linux-hardware.org/?probe=c2802686dc) | Aug 15, 2020 |
| Dell          | Latitude 5400               | [c83cae8311](https://linux-hardware.org/?probe=c83cae8311) | Aug 13, 2020 |
| Acer          | Aspire 3820                 | [82be60b2ad](https://linux-hardware.org/?probe=82be60b2ad) | Aug 13, 2020 |
| Lenovo        | ThinkPad X230 2324M26       | [9e936d64dc](https://linux-hardware.org/?probe=9e936d64dc) | Aug 12, 2020 |
| Notebook      | N15_17RD                    | [7f22033e89](https://linux-hardware.org/?probe=7f22033e89) | Aug 11, 2020 |
| Apple         | MacBook6,1                  | [36dc269753](https://linux-hardware.org/?probe=36dc269753) | Aug 09, 2020 |
| Lenovo        | ThinkPad T60 2008U5A        | [dc6150daab](https://linux-hardware.org/?probe=dc6150daab) | Aug 08, 2020 |
| Lenovo        | ThinkPad E590 20NB0029PG    | [f93a4e17ee](https://linux-hardware.org/?probe=f93a4e17ee) | Aug 07, 2020 |
| ASUSTek       | G73Sw                       | [438644b7bc](https://linux-hardware.org/?probe=438644b7bc) | Aug 06, 2020 |
| ASUSTek       | G73Sw                       | [86a2fcb3ba](https://linux-hardware.org/?probe=86a2fcb3ba) | Aug 06, 2020 |
| HP            | Pavilion dv6                | [9c60c0d2ae](https://linux-hardware.org/?probe=9c60c0d2ae) | Aug 02, 2020 |
| Dell          | Latitude E5520              | [a3cb51ad9f](https://linux-hardware.org/?probe=a3cb51ad9f) | Aug 02, 2020 |
| Fujitsu       | STYLISTIC Q704              | [52a7e36042](https://linux-hardware.org/?probe=52a7e36042) | Aug 02, 2020 |
| HP            | Pavilion dv6                | [5c0e6e7ab8](https://linux-hardware.org/?probe=5c0e6e7ab8) | Aug 02, 2020 |
| Dell          | G3 3590                     | [8ef35f93a1](https://linux-hardware.org/?probe=8ef35f93a1) | Jul 30, 2020 |
| Lenovo        | ThinkPad T60 2008U5A        | [963da8c053](https://linux-hardware.org/?probe=963da8c053) | Jul 30, 2020 |
| HP            | 15                          | [337dcd22df](https://linux-hardware.org/?probe=337dcd22df) | Jul 30, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [66a6dcc790](https://linux-hardware.org/?probe=66a6dcc790) | Jul 30, 2020 |
| Acer          | Aspire ES1-520              | [55d2cc0731](https://linux-hardware.org/?probe=55d2cc0731) | Jul 29, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [358be6b820](https://linux-hardware.org/?probe=358be6b820) | Jul 28, 2020 |
| Acer          | Crane II                    | [10a0d7e3a2](https://linux-hardware.org/?probe=10a0d7e3a2) | Jul 28, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [80126ea21a](https://linux-hardware.org/?probe=80126ea21a) | Jul 26, 2020 |
| HP            | ProBook 640 G5              | [a427246eff](https://linux-hardware.org/?probe=a427246eff) | Jul 26, 2020 |
| ASUSTek       | K53U                        | [b79e3fda60](https://linux-hardware.org/?probe=b79e3fda60) | Jul 26, 2020 |
| Acer          | Aspire VN7-571G             | [f86039bb51](https://linux-hardware.org/?probe=f86039bb51) | Jul 26, 2020 |
| Dell          | G3 3590                     | [c0a8f31a29](https://linux-hardware.org/?probe=c0a8f31a29) | Jul 25, 2020 |
| ASUSTek       | X550LB                      | [21f4f262c0](https://linux-hardware.org/?probe=21f4f262c0) | Jul 25, 2020 |
| Dell          | G3 3590                     | [162780067f](https://linux-hardware.org/?probe=162780067f) | Jul 24, 2020 |
| Dell          | G3 3590                     | [81ec9d95ca](https://linux-hardware.org/?probe=81ec9d95ca) | Jul 24, 2020 |
| Acer          | Extensa 5620                | [9cd383a169](https://linux-hardware.org/?probe=9cd383a169) | Jul 24, 2020 |
| Lenovo        | ThinkPad T60 2008U5A        | [f9587afe50](https://linux-hardware.org/?probe=f9587afe50) | Jul 24, 2020 |
| Lenovo        | ThinkPad T60 2008U5A        | [3748a04de5](https://linux-hardware.org/?probe=3748a04de5) | Jul 24, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [53a67f2e4c](https://linux-hardware.org/?probe=53a67f2e4c) | Jul 24, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7f236555bc](https://linux-hardware.org/?probe=7f236555bc) | Jul 24, 2020 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [05dd571fe3](https://linux-hardware.org/?probe=05dd571fe3) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [50839500b3](https://linux-hardware.org/?probe=50839500b3) | Jul 24, 2020 |
| HP            | Laptop 15-bw0xx             | [a3434f6fd7](https://linux-hardware.org/?probe=a3434f6fd7) | Jul 24, 2020 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | [b9e28a3149](https://linux-hardware.org/?probe=b9e28a3149) | Jul 24, 2020 |
| Dell          | Latitude E5570              | [ad0b0af916](https://linux-hardware.org/?probe=ad0b0af916) | Jul 24, 2020 |
| Sony          | VPCSB1S1E                   | [38e79c26b0](https://linux-hardware.org/?probe=38e79c26b0) | Jul 24, 2020 |
| Notebook      | N2x0WU                      | [92dd0362a1](https://linux-hardware.org/?probe=92dd0362a1) | Jul 23, 2020 |
| HP            | Pavilion DV9000 (RY715EA... | [b3c779f8be](https://linux-hardware.org/?probe=b3c779f8be) | Jul 21, 2020 |
| Toshiba       | Satellite A200              | [28e350dd6b](https://linux-hardware.org/?probe=28e350dd6b) | Jul 17, 2020 |
| Acer          | Aspire 5715Z                | [929559cae0](https://linux-hardware.org/?probe=929559cae0) | Jul 17, 2020 |
| Lenovo        | ThinkPad T430 2349S31       | [e3c066c916](https://linux-hardware.org/?probe=e3c066c916) | Jul 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [a6c67b0097](https://linux-hardware.org/?probe=a6c67b0097) | Jul 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [0c9962d0a7](https://linux-hardware.org/?probe=0c9962d0a7) | Jul 15, 2020 |
| Dell          | Latitude E6410              | [35ad33c2ed](https://linux-hardware.org/?probe=35ad33c2ed) | Jul 14, 2020 |
| Lenovo        | ThinkPad T60 2008U5A        | [134823bc84](https://linux-hardware.org/?probe=134823bc84) | Jul 13, 2020 |
| HP            | Pavilion dv7                | [b35c308549](https://linux-hardware.org/?probe=b35c308549) | Jul 12, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [8164d6222a](https://linux-hardware.org/?probe=8164d6222a) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [478d2b6718](https://linux-hardware.org/?probe=478d2b6718) | Jul 11, 2020 |
| HP            | OMEN by Laptop 15-dc0xxx    | [5dea1bac37](https://linux-hardware.org/?probe=5dea1bac37) | Jul 09, 2020 |
| ASUSTek       | X75VD                       | [746c3fd55c](https://linux-hardware.org/?probe=746c3fd55c) | Jul 08, 2020 |
| ASUSTek       | M51Vr                       | [7353f36490](https://linux-hardware.org/?probe=7353f36490) | Jul 07, 2020 |
| Acer          | Extensa 5620                | [acea261722](https://linux-hardware.org/?probe=acea261722) | Jul 05, 2020 |
| ASUSTek       | N56VZ                       | [72895f1853](https://linux-hardware.org/?probe=72895f1853) | Jul 04, 2020 |
| Acer          | Extensa 5620                | [75671b7c65](https://linux-hardware.org/?probe=75671b7c65) | Jul 04, 2020 |
| HP            | Notebook                    | [1b077e7d7e](https://linux-hardware.org/?probe=1b077e7d7e) | Jun 30, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Portugal/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 135       | 13.61%  |
| Ubuntu 18.04                 | 87        | 8.77%   |
| Ubuntu 22.04                 | 43        | 4.33%   |
| OpenMandriva 4.3             | 30        | 3.02%   |
| Zorin 15                     | 24        | 2.42%   |
| Zorin 16                     | 22        | 2.22%   |
| OpenMandriva 4.2             | 21        | 2.12%   |
| KDE neon 20.04               | 19        | 1.92%   |
| Debian 11                    | 19        | 1.92%   |
| Pop!_OS 20.04                | 18        | 1.81%   |
| Linux Mint 20.3              | 18        | 1.81%   |
| Pop!_OS 22.04                | 17        | 1.71%   |
| Debian 10                    | 17        | 1.71%   |
| Fedora 34                    | 16        | 1.61%   |
| Ubuntu 19.10                 | 14        | 1.41%   |
| Linux Mint 20.1              | 14        | 1.41%   |
| Pop!_OS 21.04                | 13        | 1.31%   |
| Manjaro                      | 13        | 1.31%   |
| Arch                         | 13        | 1.31%   |
| Xubuntu 20.04                | 12        | 1.21%   |
| Ubuntu 21.10                 | 12        | 1.21%   |
| Ubuntu 19.04                 | 12        | 1.21%   |
| Pop!_OS 20.10                | 12        | 1.21%   |
| OpenMandriva 4.50            | 12        | 1.21%   |
| Linux Mint 19.3              | 12        | 1.21%   |
| Arch Rolling                 | 12        | 1.21%   |
| Fedora 36                    | 11        | 1.11%   |
| Fedora 33                    | 11        | 1.11%   |
| Xubuntu 18.04                | 10        | 1.01%   |
| OpenMandriva 23.01           | 10        | 1.01%   |
| Linux Mint 21                | 10        | 1.01%   |
| Linux Mint 20                | 10        | 1.01%   |
| Ubuntu 20.10                 | 9         | 0.91%   |
| Pop!_OS 21.10                | 9         | 0.91%   |
| Linux Mint 19.1              | 9         | 0.91%   |
| Fedora 35                    | 8         | 0.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 0.71%   |
| Linux Mint 19.2              | 7         | 0.71%   |
| Fedora 37                    | 7         | 0.71%   |
| Ubuntu 22.10                 | 6         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 314       | 33.12%  |
| Linux Mint       | 86        | 9.07%   |
| OpenMandriva     | 73        | 7.7%    |
| Pop!_OS          | 68        | 7.17%   |
| Fedora           | 57        | 6.01%   |
| Zorin            | 46        | 4.85%   |
| Debian           | 41        | 4.32%   |
| Manjaro          | 33        | 3.48%   |
| Endless          | 32        | 3.38%   |
| KDE neon         | 29        | 3.06%   |
| Arch             | 26        | 2.74%   |
| Xubuntu          | 24        | 2.53%   |
| Elementary       | 13        | 1.37%   |
| ROSA             | 11        | 1.16%   |
| Kubuntu          | 11        | 1.16%   |
| openSUSE         | 10        | 1.05%   |
| Ubuntu Unity     | 6         | 0.63%   |
| ArcoLinux        | 6         | 0.63%   |
| Slackware        | 5         | 0.53%   |
| LMDE             | 5         | 0.53%   |
| Ubuntu MATE      | 4         | 0.42%   |
| Nobara           | 4         | 0.42%   |
| Lubuntu          | 4         | 0.42%   |
| Gentoo           | 4         | 0.42%   |
| EndeavourOS      | 4         | 0.42%   |
| Clear Linux      | 4         | 0.42%   |
| Ubuntu Budgie    | 3         | 0.32%   |
| Peppermint       | 2         | 0.21%   |
| Parrot           | 2         | 0.21%   |
| MX               | 2         | 0.21%   |
| Devuan           | 2         | 0.21%   |
| UbuntuDDE        | 1         | 0.11%   |
| TUXEDO OS        | 1         | 0.11%   |
| RHEL             | 1         | 0.11%   |
| Reborn OS        | 1         | 0.11%   |
| PureOS           | 1         | 0.11%   |
| org.kde.Platform | 1         | 0.11%   |
| NixOS            | 1         | 0.11%   |
| LinuxFX          | 1         | 0.11%   |
| Linux Lite       | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 25        | 2.3%    |
| 5.4.0-42-generic         | 24        | 2.21%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.84%   |
| 5.15.0-56-generic        | 13        | 1.2%    |
| 5.3.0-46-generic         | 12        | 1.11%   |
| 5.4.0-29-generic         | 11        | 1.01%   |
| 5.15.0-52-generic        | 11        | 1.01%   |
| 5.14.14-desktop-1omv4050 | 11        | 1.01%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.92%   |
| 5.4.0-58-generic         | 10        | 0.92%   |
| 5.4.0-52-generic         | 10        | 0.92%   |
| 5.15.0-48-generic        | 10        | 0.92%   |
| 5.15.0-46-generic        | 10        | 0.92%   |
| 5.11.0-38-generic        | 10        | 0.92%   |
| 5.3.0-28-generic         | 9         | 0.83%   |
| 5.15.0-41-generic        | 9         | 0.83%   |
| 4.18.0-15-generic        | 9         | 0.83%   |
| 5.4.0-7634-generic       | 8         | 0.74%   |
| 5.0.0-25-generic         | 8         | 0.74%   |
| 5.4.0-31-generic         | 7         | 0.65%   |
| 5.4.0-26-generic         | 7         | 0.65%   |
| 5.19.0-76051900-generic  | 7         | 0.65%   |
| 5.15.0-58-generic        | 7         | 0.65%   |
| 5.13.0-39-generic        | 7         | 0.65%   |
| 5.11.0-43-generic        | 7         | 0.65%   |
| 5.0.0-37-generic         | 7         | 0.65%   |
| 4.18.0-25-generic        | 7         | 0.65%   |
| 4.15.0-46-generic        | 7         | 0.65%   |
| 5.8.0-63-generic         | 6         | 0.55%   |
| 5.4.0-91-generic         | 6         | 0.55%   |
| 5.4.0-65-generic         | 6         | 0.55%   |
| 5.3.0-40-generic         | 6         | 0.55%   |
| 5.11.0-7620-generic      | 6         | 0.55%   |
| 5.8.0-7642-generic       | 5         | 0.46%   |
| 5.8.0-55-generic         | 5         | 0.46%   |
| 5.8.0-48-generic         | 5         | 0.46%   |
| 5.8.0-43-generic         | 5         | 0.46%   |
| 5.4.0-54-generic         | 5         | 0.46%   |
| 5.4.0-48-generic         | 5         | 0.46%   |
| 5.4.0-37-generic         | 5         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 184       | 18.04%  |
| 5.15.0  | 77        | 7.55%   |
| 4.15.0  | 67        | 6.57%   |
| 5.8.0   | 63        | 6.18%   |
| 5.11.0  | 60        | 5.88%   |
| 5.3.0   | 55        | 5.39%   |
| 5.13.0  | 47        | 4.61%   |
| 5.0.0   | 38        | 3.73%   |
| 4.18.0  | 34        | 3.33%   |
| 5.16.7  | 25        | 2.45%   |
| 5.10.0  | 25        | 2.45%   |
| 5.19.0  | 21        | 2.06%   |
| 5.10.14 | 21        | 2.06%   |
| 4.19.0  | 17        | 1.67%   |
| 6.1.1   | 12        | 1.18%   |
| 5.14.14 | 11        | 1.08%   |
| 4.4.0   | 5         | 0.49%   |
| 6.0.12  | 4         | 0.39%   |
| 6.0.0   | 4         | 0.39%   |
| 5.6.0   | 4         | 0.39%   |
| 5.14.0  | 4         | 0.39%   |
| 5.11.12 | 4         | 0.39%   |
| 6.2.6   | 3         | 0.29%   |
| 6.1.12  | 3         | 0.29%   |
| 5.8.16  | 3         | 0.29%   |
| 5.7.9   | 3         | 0.29%   |
| 5.19.5  | 3         | 0.29%   |
| 5.16.15 | 3         | 0.29%   |
| 5.16.11 | 3         | 0.29%   |
| 5.16.0  | 3         | 0.29%   |
| 5.15.15 | 3         | 0.29%   |
| 5.15.11 | 3         | 0.29%   |
| 5.14.16 | 3         | 0.29%   |
| 5.12.7  | 3         | 0.29%   |
| 5.12.4  | 3         | 0.29%   |
| 4.9.60  | 3         | 0.29%   |
| 4.9.0   | 3         | 0.29%   |
| 6.1.9   | 2         | 0.2%    |
| 6.1.8   | 2         | 0.2%    |
| 6.1.11  | 2         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 194       | 19.15%  |
| 5.15    | 103       | 10.17%  |
| 5.8     | 77        | 7.6%    |
| 5.11    | 68        | 6.71%   |
| 4.15    | 67        | 6.61%   |
| 5.10    | 60        | 5.92%   |
| 5.3     | 58        | 5.73%   |
| 5.13    | 52        | 5.13%   |
| 5.16    | 43        | 4.24%   |
| 5.0     | 39        | 3.85%   |
| 4.18    | 35        | 3.46%   |
| 5.19    | 33        | 3.26%   |
| 6.1     | 26        | 2.57%   |
| 5.14    | 24        | 2.37%   |
| 4.19    | 20        | 1.97%   |
| 6.0     | 19        | 1.88%   |
| 5.12    | 16        | 1.58%   |
| 4.9     | 12        | 1.18%   |
| 5.7     | 10        | 0.99%   |
| 5.6     | 10        | 0.99%   |
| 5.17    | 10        | 0.99%   |
| 5.9     | 9         | 0.89%   |
| 5.5     | 6         | 0.59%   |
| 5.18    | 6         | 0.59%   |
| 6.2     | 5         | 0.49%   |
| 4.4     | 5         | 0.49%   |
| 5.2     | 2         | 0.2%    |
| 4.12    | 1         | 0.1%    |
| 4.1     | 1         | 0.1%    |
| 3.10    | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 871       | 94.88%  |
| i686   | 47        | 5.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 439       | 45.73%  |
| KDE5            | 147       | 15.31%  |
| Unknown         | 135       | 14.06%  |
| XFCE            | 72        | 7.5%    |
| X-Cinnamon      | 66        | 6.88%   |
| KDE             | 18        | 1.88%   |
| MATE            | 17        | 1.77%   |
| Pantheon        | 11        | 1.15%   |
| KDE4            | 9         | 0.94%   |
| i3              | 9         | 0.94%   |
| Cinnamon        | 8         | 0.83%   |
| Unity           | 7         | 0.73%   |
| Budgie          | 6         | 0.63%   |
| LXQt            | 4         | 0.42%   |
| LXDE            | 4         | 0.42%   |
| GNOME Flashback | 2         | 0.21%   |
| Deepin          | 2         | 0.21%   |
| awesome         | 2         | 0.21%   |
| Openbox         | 1         | 0.1%    |
| fluxbox         | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 741       | 79%     |
| Wayland | 130       | 13.86%  |
| Unknown | 65        | 6.93%   |
| Tty     | 2         | 0.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 537       | 56.41%  |
| SDDM    | 125       | 13.13%  |
| GDM     | 97        | 10.19%  |
| GDM3    | 91        | 9.56%   |
| LightDM | 61        | 6.41%   |
| TDM     | 28        | 2.94%   |
| KDM     | 9         | 0.95%   |
| XDM     | 3         | 0.32%   |
| SLiM    | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pt_PT   | 366       | 38.81%  |
| en_US   | 343       | 36.37%  |
| Unknown | 129       | 13.68%  |
| en_GB   | 51        | 5.41%   |
| pt_BR   | 18        | 1.91%   |
| C       | 16        | 1.7%    |
| en_IE   | 4         | 0.42%   |
| fr_FR   | 3         | 0.32%   |
| de_DE   | 3         | 0.32%   |
| ru_RU   | 2         | 0.21%   |
| POSIX   | 2         | 0.21%   |
| es_ES   | 2         | 0.21%   |
| sk_SK   | 1         | 0.11%   |
| it_IT   | 1         | 0.11%   |
| en_IN   | 1         | 0.11%   |
| Default | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 487       | 51.7%   |
| EFI  | 455       | 48.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 743       | 79.98%  |
| Btrfs    | 64        | 6.89%   |
| Overlay  | 61        | 6.57%   |
| Unknown  | 44        | 4.74%   |
| Zfs      | 5         | 0.54%   |
| Xfs      | 5         | 0.54%   |
| Ext2     | 4         | 0.43%   |
| Ext3     | 2         | 0.22%   |
| Reiserfs | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 572       | 61.05%  |
| GPT     | 289       | 30.84%  |
| MBR     | 76        | 8.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 828       | 89.42%  |
| Yes       | 98        | 10.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 665       | 71.35%  |
| Yes       | 267       | 28.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 169       | 18.43%  |
| Hewlett-Packard     | 165       | 17.99%  |
| ASUSTek Computer    | 164       | 17.88%  |
| Acer                | 95        | 10.36%  |
| Toshiba             | 77        | 8.4%    |
| Dell                | 47        | 5.13%   |
| Sony                | 41        | 4.47%   |
| MSI                 | 24        | 2.62%   |
| Apple               | 24        | 2.62%   |
| HUAWEI              | 19        | 2.07%   |
| Samsung Electronics | 14        | 1.53%   |
| Notebook            | 9         | 0.98%   |
| TUXEDO              | 6         | 0.65%   |
| Packard Bell        | 6         | 0.65%   |
| Fujitsu             | 4         | 0.44%   |
| Phoenix/SiS         | 3         | 0.33%   |
| LG Electronics      | 3         | 0.33%   |
| Intel               | 3         | 0.33%   |
| eMachines           | 3         | 0.33%   |
| Clevo               | 3         | 0.33%   |
| Chuwi               | 3         | 0.33%   |
| Unknown             | 3         | 0.33%   |
| Teclast             | 2         | 0.22%   |
| SLIMBOOK            | 2         | 0.22%   |
| Positivo            | 2         | 0.22%   |
| OBSIDIAN-PC         | 2         | 0.22%   |
| INSYS               | 2         | 0.22%   |
| Gigabyte Technology | 2         | 0.22%   |
| Fujitsu Siemens     | 2         | 0.22%   |
| Alienware           | 2         | 0.22%   |
| Timi                | 1         | 0.11%   |
| Thomson             | 1         | 0.11%   |
| System76            | 1         | 0.11%   |
| Standard            | 1         | 0.11%   |
| Schenker            | 1         | 0.11%   |
| Qilive              | 1         | 0.11%   |
| Purism              | 1         | 0.11%   |
| PC Specialist       | 1         | 0.11%   |
| LIVEFAN             | 1         | 0.11%   |
| Linx                | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Sony VGN-FZ31Z                         | 20        | 2.18%   |
| Lenovo IdeaPad 1 14ADA05 82GW          | 11        | 1.2%    |
| Toshiba Satellite C660                 | 8         | 0.87%   |
| HP Pavilion g6                         | 8         | 0.87%   |
| HP Pavilion dv6                        | 8         | 0.87%   |
| HP G62                                 | 7         | 0.76%   |
| HP Notebook                            | 6         | 0.65%   |
| Toshiba Satellite L650                 | 5         | 0.55%   |
| Lenovo Legion 5 15ACH6H 82JU           | 5         | 0.55%   |
| ASUS X555LJ                            | 5         | 0.55%   |
| ASUS X555LD                            | 5         | 0.55%   |
| ASUS X541UV                            | 5         | 0.55%   |
| Acer Extensa 5620                      | 5         | 0.55%   |
| Unknown                                | 5         | 0.55%   |
| Toshiba Satellite L500                 | 4         | 0.44%   |
| Toshiba Satellite L40                  | 4         | 0.44%   |
| Toshiba Satellite A200                 | 4         | 0.44%   |
| Lenovo Y520-15IKBN 80WK                | 4         | 0.44%   |
| HUAWEI NBLK-WAX9X                      | 4         | 0.44%   |
| HP Pavilion Notebook                   | 4         | 0.44%   |
| HP OMEN by Laptop 15-dc0xxx            | 4         | 0.44%   |
| HP Compaq Presario CQ60                | 4         | 0.44%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 4         | 0.44%   |
| ASUS VivoBook 15_ASUS Laptop X507LA    | 4         | 0.44%   |
| Acer Aspire E5-551G                    | 4         | 0.44%   |
| Toshiba Satellite L50D-B               | 3         | 0.33%   |
| MSI Modern 14 A10RB                    | 3         | 0.33%   |
| Lenovo Legion 5 15ARH05 82B5           | 3         | 0.33%   |
| Lenovo IdeaPad 320-15AST 80XV          | 3         | 0.33%   |
| Lenovo G50-45 80E3                     | 3         | 0.33%   |
| Intel powered classmate PC             | 3         | 0.33%   |
| HUAWEI WRT-WX9                         | 3         | 0.33%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 3         | 0.33%   |
| HP Pavilion 15                         | 3         | 0.33%   |
| HP OMEN by Laptop                      | 3         | 0.33%   |
| HP Compaq Presario CQ61                | 3         | 0.33%   |
| Dell XPS 13 7390                       | 3         | 0.33%   |
| ASUS ZenBook UX425EA_UX425EA           | 3         | 0.33%   |
| ASUS X542URR                           | 3         | 0.33%   |
| ASUS X541UJ                            | 3         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 84        | 9.16%   |
| Acer Aspire           | 77        | 8.4%    |
| Toshiba Satellite     | 67        | 7.31%   |
| HP Pavilion           | 53        | 5.78%   |
| Lenovo IdeaPad        | 49        | 5.34%   |
| ASUS VivoBook         | 33        | 3.6%    |
| HP EliteBook          | 22        | 2.4%    |
| Dell Latitude         | 22        | 2.4%    |
| Sony VGN-FZ31Z        | 20        | 2.18%   |
| HP Compaq             | 17        | 1.85%   |
| HP ProBook            | 15        | 1.64%   |
| Lenovo Legion         | 13        | 1.42%   |
| HP Laptop             | 12        | 1.31%   |
| Dell XPS              | 11        | 1.2%    |
| HP OMEN               | 10        | 1.09%   |
| ASUS ZenBook          | 10        | 1.09%   |
| Dell Inspiron         | 9         | 0.98%   |
| Acer Extensa          | 8         | 0.87%   |
| HP G62                | 7         | 0.76%   |
| ASUS ROG              | 7         | 0.76%   |
| Packard Bell EasyNote | 6         | 0.65%   |
| MSI Modern            | 6         | 0.65%   |
| HP Notebook           | 6         | 0.65%   |
| HP ENVY               | 6         | 0.65%   |
| ASUS X555LJ           | 5         | 0.55%   |
| ASUS X555LD           | 5         | 0.55%   |
| ASUS X541UV           | 5         | 0.55%   |
| Unknown               | 5         | 0.55%   |
| Lenovo Yoga           | 4         | 0.44%   |
| Lenovo Y520-15IKBN    | 4         | 0.44%   |
| HUAWEI NBLK-WAX9X     | 4         | 0.44%   |
| Dell Precision        | 4         | 0.44%   |
| Apple MacBookPro8     | 4         | 0.44%   |
| Acer Nitro            | 4         | 0.44%   |
| TUXEDO InfinityBook   | 3         | 0.33%   |
| Toshiba QOSMIO        | 3         | 0.33%   |
| Toshiba PORTEGE       | 3         | 0.33%   |
| Lenovo G50-45         | 3         | 0.33%   |
| Intel powered         | 3         | 0.33%   |
| HUAWEI WRT-WX9        | 3         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 86        | 9.38%   |
| 2019    | 84        | 9.16%   |
| 2010    | 76        | 8.29%   |
| 2018    | 73        | 7.96%   |
| 2015    | 61        | 6.65%   |
| 2014    | 58        | 6.32%   |
| 2013    | 58        | 6.32%   |
| 2007    | 56        | 6.11%   |
| 2008    | 52        | 5.67%   |
| 2021    | 50        | 5.45%   |
| 2017    | 48        | 5.23%   |
| 2016    | 48        | 5.23%   |
| 2011    | 48        | 5.23%   |
| 2012    | 41        | 4.47%   |
| 2009    | 40        | 4.36%   |
| 2022    | 19        | 2.07%   |
| 2006    | 10        | 1.09%   |
| 2005    | 7         | 0.76%   |
| Unknown | 2         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 917       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 839       | 89.83%  |
| Enabled  | 95        | 10.17%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 915       | 99.78%  |
| Yes  | 2         | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 259       | 28%     |
| 4.01-8.0    | 237       | 25.62%  |
| 8.01-16.0   | 138       | 14.92%  |
| 16.01-24.0  | 123       | 13.3%   |
| 1.01-2.0    | 66        | 7.14%   |
| 32.01-64.0  | 63        | 6.81%   |
| 2.01-3.0    | 17        | 1.84%   |
| 0.51-1.0    | 11        | 1.19%   |
| 24.01-32.0  | 6         | 0.65%   |
| 64.01-256.0 | 5         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 389       | 38.67%  |
| 2.01-3.0   | 218       | 21.67%  |
| 4.01-8.0   | 146       | 14.51%  |
| 3.01-4.0   | 119       | 11.83%  |
| 0.51-1.0   | 81        | 8.05%   |
| 8.01-16.0  | 39        | 3.88%   |
| 16.01-24.0 | 7         | 0.7%    |
| 0.01-0.5   | 6         | 0.6%    |
| 24.01-32.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 694       | 74.22%  |
| 2      | 201       | 21.5%   |
| 3      | 26        | 2.78%   |
| 0      | 10        | 1.07%   |
| 4      | 3         | 0.32%   |
| 5      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 581       | 63.29%  |
| Yes       | 337       | 36.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 761       | 82.54%  |
| No        | 161       | 17.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 895       | 97.6%   |
| No        | 22        | 2.4%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 660       | 71.2%   |
| No        | 267       | 28.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Portugal | 917       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lisbon                  | 218       | 22.27%  |
| Porto                   | 87        | 8.89%   |
| Funchal                 | 30        | 3.06%   |
| Vila Nova de Gaia       | 26        | 2.66%   |
| Amadora                 | 22        | 2.25%   |
| Braga                   | 17        | 1.74%   |
| Coimbra                 | 15        | 1.53%   |
| Cascais                 | 15        | 1.53%   |
| Aveiro                  | 15        | 1.53%   |
| Setúbal                | 13        | 1.33%   |
| Loures                  | 13        | 1.33%   |
| Faro                    | 11        | 1.12%   |
| Bragança               | 11        | 1.12%   |
| Leiria                  | 10        | 1.02%   |
| Sintra                  | 9         | 0.92%   |
| Mem Martins             | 9         | 0.92%   |
| Almada                  | 9         | 0.92%   |
| Santarém               | 8         | 0.82%   |
| Póvoa de Varzim        | 8         | 0.82%   |
| Feira                   | 8         | 0.82%   |
| Alverca do Ribatejo     | 8         | 0.82%   |
| Santo Tirso             | 7         | 0.72%   |
| Odivelas                | 7         | 0.72%   |
| Guimaraes               | 7         | 0.72%   |
| Carnaxide               | 7         | 0.72%   |
| Cacem                   | 7         | 0.72%   |
| Viseu                   | 6         | 0.61%   |
| Viana do Castelo        | 6         | 0.61%   |
| Matosinhos Municipality | 6         | 0.61%   |
| Maia                    | 6         | 0.61%   |
| Evora                   | 6         | 0.61%   |
| Águeda Municipality    | 6         | 0.61%   |
| Vila Nova de Famalicao  | 5         | 0.51%   |
| Lagos                   | 5         | 0.51%   |
| Estoril                 | 5         | 0.51%   |
| Barcelos                | 5         | 0.51%   |
| Albufeira               | 5         | 0.51%   |
| Vila do Conde           | 4         | 0.41%   |
| Valongo                 | 4         | 0.41%   |
| Trofa                   | 4         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 170       | 219    | 15.33%  |
| Toshiba                     | 122       | 142    | 11%     |
| WDC                         | 118       | 157    | 10.64%  |
| Seagate                     | 113       | 137    | 10.19%  |
| Kingston                    | 89        | 102    | 8.03%   |
| SanDisk                     | 63        | 76     | 5.68%   |
| Unknown                     | 62        | 92     | 5.59%   |
| Crucial                     | 44        | 55     | 3.97%   |
| Hitachi                     | 39        | 42     | 3.52%   |
| HGST                        | 38        | 48     | 3.43%   |
| Intel                       | 29        | 47     | 2.61%   |
| SK hynix                    | 27        | 32     | 2.43%   |
| Micron Technology           | 22        | 26     | 1.98%   |
| Fujitsu                     | 17        | 18     | 1.53%   |
| KIOXIA                      | 14        | 23     | 1.26%   |
| Apple                       | 11        | 11     | 0.99%   |
| GOODRAM                     | 9         | 9      | 0.81%   |
| JMicron Technology          | 7         | 7      | 0.63%   |
| A-DATA Technology           | 7         | 7      | 0.63%   |
| S3+                         | 6         | 15     | 0.54%   |
| LITEON                      | 6         | 7      | 0.54%   |
| Transcend                   | 4         | 5      | 0.36%   |
| Silicon Motion              | 4         | 4      | 0.36%   |
| PNY                         | 4         | 5      | 0.36%   |
| Emtec                       | 4         | 5      | 0.36%   |
| China                       | 4         | 5      | 0.36%   |
| BlueRay                     | 4         | 5      | 0.36%   |
| Team                        | 3         | 4      | 0.27%   |
| Phison                      | 3         | 3      | 0.27%   |
| OCZ                         | 3         | 3      | 0.27%   |
| Netac                       | 3         | 3      | 0.27%   |
| Micron/Crucial Technology   | 3         | 6      | 0.27%   |
| Maxtor                      | 3         | 10     | 0.27%   |
| KIOXIA-EXCERIA              | 3         | 3      | 0.27%   |
| Kingston Technology Company | 3         | 3      | 0.27%   |
| Unknown                     | 3         | 3      | 0.27%   |
| USB                         | 2         | 2      | 0.18%   |
| Union Memory (Shenzhen)     | 2         | 5      | 0.18%   |
| UMIS                        | 2         | 2      | 0.18%   |
| TCSUNBOW                    | 2         | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB     | 18        | 1.57%   |
| HGST HTS721010A9E630 1TB               | 18        | 1.57%   |
| Toshiba MQ01ABD100 1TB                 | 17        | 1.48%   |
| Unknown MMC Card  32GB                 | 15        | 1.31%   |
| Kingston SA400S37120G 120GB SSD        | 15        | 1.31%   |
| Toshiba MQ01ABF050 500GB               | 13        | 1.13%   |
| Seagate ST1000LM035-1RK172 1TB         | 13        | 1.13%   |
| Crucial CT240M500SSD1 240GB            | 13        | 1.13%   |
| Seagate ST500LT012-1DG142 500GB        | 12        | 1.05%   |
| Kingston SV300S37A120G 120GB SSD       | 12        | 1.05%   |
| Unknown MMC64G  64GB                   | 11        | 0.96%   |
| Unknown MMC Card  64GB                 | 10        | 0.87%   |
| SanDisk NVMe SSD Drive 512GB           | 10        | 0.87%   |
| Seagate ST9500325AS 500GB              | 9         | 0.78%   |
| Samsung SSD 850 EVO 500GB              | 9         | 0.78%   |
| Kingston SA400S37240G 240GB SSD        | 9         | 0.78%   |
| Samsung NVMe SSD Drive 512GB           | 8         | 0.7%    |
| Toshiba TR200 240GB SSD                | 7         | 0.61%   |
| Toshiba MQ04ABF100 1TB                 | 7         | 0.61%   |
| SanDisk NVMe SSD Drive 256GB           | 7         | 0.61%   |
| Samsung SSD 860 EVO 500GB              | 7         | 0.61%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 7         | 0.61%   |
| Kingston SA400S37480G 480GB SSD        | 7         | 0.61%   |
| Kingston NVMe SSD Drive 512GB          | 7         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 6         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 6         | 0.52%   |
| WDC WD3200BEVT-22ZCT0 320GB            | 6         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB               | 6         | 0.52%   |
| SK hynix NVMe SSD Drive 512GB          | 6         | 0.52%   |
| SK hynix NVMe SSD Drive 256GB          | 6         | 0.52%   |
| SanDisk NVMe SSD Drive 1024GB          | 6         | 0.52%   |
| Samsung NVMe SSD Drive 1024GB          | 6         | 0.52%   |
| Micron NVMe SSD Drive 512GB            | 6         | 0.52%   |
| HGST HTS541010A9E680 1TB               | 6         | 0.52%   |
| Crucial CT240BX500SSD1 240GB           | 6         | 0.52%   |
| Seagate ST9320325AS 320GB              | 5         | 0.44%   |
| Seagate Expansion+ 2TB                 | 5         | 0.44%   |
| Samsung SSD 860 QVO 1TB                | 5         | 0.44%   |
| Samsung SSD 860 EVO 1TB                | 5         | 0.44%   |
| Samsung SSD 850 EVO 250GB              | 5         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 112       | 132    | 29.24%  |
| Toshiba             | 84        | 102    | 21.93%  |
| WDC                 | 77        | 93     | 20.1%   |
| Hitachi             | 39        | 42     | 10.18%  |
| HGST                | 38        | 48     | 9.92%   |
| Fujitsu             | 17        | 18     | 4.44%   |
| Samsung Electronics | 12        | 12     | 3.13%   |
| USB                 | 2         | 2      | 0.52%   |
| USB3.0              | 1         | 1      | 0.26%   |
| ASMedia             | 1         | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 74        | 91     | 20.27%  |
| Kingston            | 72        | 83     | 19.73%  |
| Crucial             | 43        | 53     | 11.78%  |
| SanDisk             | 28        | 34     | 7.67%   |
| Toshiba             | 18        | 20     | 4.93%   |
| WDC                 | 16        | 17     | 4.38%   |
| Apple               | 10        | 10     | 2.74%   |
| GOODRAM             | 9         | 9      | 2.47%   |
| Intel               | 7         | 9      | 1.92%   |
| A-DATA Technology   | 7         | 7      | 1.92%   |
| S3+                 | 6         | 15     | 1.64%   |
| SK hynix            | 5         | 5      | 1.37%   |
| Micron Technology   | 5         | 8      | 1.37%   |
| Transcend           | 4         | 5      | 1.1%    |
| LITEON              | 4         | 5      | 1.1%    |
| JMicron Technology  | 4         | 4      | 1.1%    |
| Emtec               | 4         | 5      | 1.1%    |
| China               | 4         | 5      | 1.1%    |
| BlueRay             | 4         | 5      | 1.1%    |
| Team                | 3         | 4      | 0.82%   |
| PNY                 | 3         | 4      | 0.82%   |
| OCZ                 | 3         | 3      | 0.82%   |
| Netac               | 3         | 3      | 0.82%   |
| Maxtor              | 3         | 10     | 0.82%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.82%   |
| TCSUNBOW            | 2         | 2      | 0.55%   |
| Seagate             | 2         | 4      | 0.55%   |
| KingDian            | 2         | 2      | 0.55%   |
| Hewlett-Packard     | 2         | 2      | 0.55%   |
| Unknown             | 2         | 2      | 0.55%   |
| Verbatim            | 1         | 1      | 0.27%   |
| Vaseky              | 1         | 1      | 0.27%   |
| Teclast             | 1         | 1      | 0.27%   |
| TEAM T25            | 1         | 1      | 0.27%   |
| Plextor             | 1         | 1      | 0.27%   |
| OSC                 | 1         | 1      | 0.27%   |
| LITEONIT            | 1         | 1      | 0.27%   |
| Lexar               | 1         | 1      | 0.27%   |
| KingSpec            | 1         | 1      | 0.27%   |
| Gigabyte Technology | 1         | 1      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 376       | 451    | 35.4%   |
| SSD     | 338       | 442    | 31.83%  |
| NVMe    | 276       | 392    | 25.99%  |
| MMC     | 61        | 93     | 5.74%   |
| Unknown | 11        | 11     | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 642       | 869    | 63.63%  |
| NVMe | 276       | 391    | 27.35%  |
| MMC  | 61        | 93     | 6.05%   |
| SAS  | 30        | 36     | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 510       | 671    | 73.49%  |
| 0.51-1.0   | 169       | 202    | 24.35%  |
| 1.01-2.0   | 14        | 19     | 2.02%   |
| 3.01-4.0   | 1         | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 286       | 29.95%  |
| 251-500        | 244       | 25.55%  |
| 501-1000       | 128       | 13.4%   |
| 51-100         | 82        | 8.59%   |
| 1-20           | 72        | 7.54%   |
| 1001-2000      | 49        | 5.13%   |
| 21-50          | 45        | 4.71%   |
| Unknown        | 21        | 2.2%    |
| More than 3000 | 14        | 1.47%   |
| 2001-3000      | 14        | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 412       | 41.7%   |
| 21-50          | 208       | 21.05%  |
| 101-250        | 122       | 12.35%  |
| 51-100         | 107       | 10.83%  |
| 251-500        | 66        | 6.68%   |
| 501-1000       | 27        | 2.73%   |
| Unknown        | 21        | 2.13%   |
| 1001-2000      | 19        | 1.92%   |
| More than 3000 | 5         | 0.51%   |
| 2001-3000      | 1         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Crucial CT240M500SSD1 240GB         | 13        | 13     | 21.67%  |
| Kingston SV300S37A120G 120GB SSD    | 6         | 6      | 10%     |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 2      | 3.33%   |
| Kingston SV300S37A240G 240GB SSD    | 2         | 2      | 3.33%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 2      | 3.33%   |
| HGST HTS721010A9E630 1TB            | 2         | 2      | 3.33%   |
| WDC WD5000BPVT-80HXZT1 500GB        | 1         | 1      | 1.67%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 1      | 1.67%   |
| WDC WD10JPVT-22A1YT0 1TB            | 1         | 1      | 1.67%   |
| USB 3.1 120GB                       | 1         | 1      | 1.67%   |
| Toshiba Q300. 240GB SSD             | 1         | 1      | 1.67%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.67%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.67%   |
| Toshiba MK7575GSX 752GB             | 1         | 1      | 1.67%   |
| Toshiba MK5065GSX 500GB             | 1         | 1      | 1.67%   |
| Toshiba MK3276GSX 320GB             | 1         | 1      | 1.67%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 1.67%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 1.67%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 1.67%   |
| Seagate ST9160310AS 160GB           | 1         | 2      | 1.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.67%   |
| Seagate ST1000LM049-2GH172 1TB      | 1         | 1      | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 1.67%   |
| SanDisk SSD U100 24GB               | 1         | 1      | 1.67%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 1.67%   |
| Samsung Electronics HM320JI 320GB   | 1         | 1      | 1.67%   |
| Samsung Electronics HM251HI 250GB   | 1         | 1      | 1.67%   |
| Kingston SUV400S37240G 240GB SSD    | 1         | 1      | 1.67%   |
| Hitachi HTS727575A9E364 752GB       | 1         | 1      | 1.67%   |
| Hitachi HTS725050A9A364 500GB       | 1         | 1      | 1.67%   |
| Hitachi HTS545025B9A300 250GB       | 1         | 1      | 1.67%   |
| Hitachi HTS543232A7A384 320GB       | 1         | 1      | 1.67%   |
| Hitachi HTS543225L9A300 250GB       | 1         | 1      | 1.67%   |
| Hitachi HTS543216L9A300 160GB       | 1         | 1      | 1.67%   |
| Hitachi HTS541010G9SA00 100GB       | 1         | 1      | 1.67%   |
| Fujitsu MHW2080BH PL 80GB           | 1         | 1      | 1.67%   |
| A-DATA Technology SP920SS 128GB SSD | 1         | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 13        | 13     | 21.67%  |
| Seagate             | 11        | 12     | 18.33%  |
| Kingston            | 9         | 9      | 15%     |
| Hitachi             | 9         | 9      | 15%     |
| Toshiba             | 6         | 6      | 10%     |
| WDC                 | 3         | 3      | 5%      |
| Samsung Electronics | 3         | 3      | 5%      |
| HGST                | 2         | 2      | 3.33%   |
| USB                 | 1         | 1      | 1.67%   |
| SanDisk             | 1         | 1      | 1.67%   |
| Fujitsu             | 1         | 1      | 1.67%   |
| A-DATA Technology   | 1         | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 32.35%  |
| Hitachi             | 9         | 9      | 26.47%  |
| Toshiba             | 5         | 5      | 14.71%  |
| WDC                 | 3         | 3      | 8.82%   |
| Samsung Electronics | 2         | 2      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |
| USB                 | 1         | 1      | 2.94%   |
| Fujitsu             | 1         | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 35     | 56.67%  |
| SSD  | 26        | 26     | 43.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010B7E610 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 614       | 928    | 64.23%  |
| Works    | 281       | 399    | 29.39%  |
| Malfunc  | 60        | 61     | 6.28%   |
| Failed   | 1         | 1      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 624       | 60.35%  |
| AMD                              | 110       | 10.64%  |
| Samsung Electronics              | 93        | 8.99%   |
| SanDisk                          | 55        | 5.32%   |
| Toshiba America Info Systems     | 22        | 2.13%   |
| SK hynix                         | 20        | 1.93%   |
| Kingston Technology Company      | 19        | 1.84%   |
| Micron Technology                | 17        | 1.64%   |
| Silicon Integrated Systems [SiS] | 12        | 1.16%   |
| KIOXIA                           | 12        | 1.16%   |
| Nvidia                           | 11        | 1.06%   |
| Union Memory (Shenzhen)          | 6         | 0.58%   |
| Phison Electronics               | 6         | 0.58%   |
| Micron/Crucial Technology        | 5         | 0.48%   |
| Lite-On Technology               | 5         | 0.48%   |
| Silicon Motion                   | 4         | 0.39%   |
| JMicron Technology               | 4         | 0.39%   |
| Solid State Storage Technology   | 2         | 0.19%   |
| Lenovo                           | 2         | 0.19%   |
| Silicon Image                    | 1         | 0.1%    |
| Realtek Semiconductor            | 1         | 0.1%    |
| Marvell Technology Group         | 1         | 0.1%    |
| Enmotus                          | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 102       | 8.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 64        | 5.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 58        | 5.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 53        | 4.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 52        | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 50        | 4.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 47        | 4.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 46        | 4%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 42        | 3.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 41        | 3.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 33        | 2.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 24        | 2.09%   |
| Samsung NVMe SSD Controller 980                                                | 21        | 1.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 1.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 20        | 1.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 19        | 1.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 18        | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 1.56%   |
| Micron NVMe Storage Controller                                                 | 17        | 1.48%   |
| Intel SSD 660P Series                                                          | 14        | 1.22%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 13        | 1.13%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 12        | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 12        | 1.04%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 11        | 0.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 11        | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 10        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 10        | 0.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 10        | 0.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.78%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 9         | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 9         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 0.78%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 8         | 0.7%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 8         | 0.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 8         | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 7         | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 0.61%   |
| Kingston Company Company Non-Volatile memory controller                        | 7         | 0.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 7         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 644       | 58.65%  |
| NVMe | 277       | 25.23%  |
| IDE  | 117       | 10.66%  |
| RAID | 60        | 5.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 754       | 82.22%  |
| AMD    | 163       | 17.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 24        | 2.62%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 19        | 2.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 1.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 17        | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 1.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 1.31%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 1.31%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 1.31%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 11        | 1.2%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 1.2%    |
| AMD 3020e with Radeon Graphics                | 11        | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 1.09%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 1.09%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 9         | 0.98%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 9         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 0.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 0.98%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 9         | 0.98%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 0.98%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 0.98%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.87%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 8         | 0.87%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 7         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 0.76%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.76%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.76%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 7         | 0.76%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 6         | 0.65%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 6         | 0.65%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 6         | 0.65%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 6         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 223       | 24.32%  |
| Intel Core i5           | 181       | 19.74%  |
| Intel Core 2 Duo        | 74        | 8.07%   |
| Other                   | 64        | 6.98%   |
| Intel Core i3           | 61        | 6.65%   |
| Intel Celeron           | 39        | 4.25%   |
| AMD Ryzen 7             | 39        | 4.25%   |
| AMD Ryzen 5             | 35        | 3.82%   |
| Intel Atom              | 32        | 3.49%   |
| Intel Pentium Dual-Core | 24        | 2.62%   |
| Intel Pentium Dual      | 23        | 2.51%   |
| Intel Pentium           | 15        | 1.64%   |
| Intel Genuine           | 13        | 1.42%   |
| AMD A4                  | 12        | 1.31%   |
| AMD A6                  | 10        | 1.09%   |
| Intel Core 2            | 9         | 0.98%   |
| AMD A8                  | 9         | 0.98%   |
| AMD E2                  | 7         | 0.76%   |
| AMD Ryzen 9             | 6         | 0.65%   |
| AMD Ryzen 3             | 6         | 0.65%   |
| Intel Pentium M         | 5         | 0.55%   |
| AMD A10                 | 4         | 0.44%   |
| AMD E                   | 3         | 0.33%   |
| AMD Athlon              | 3         | 0.33%   |
| Intel Core m3           | 2         | 0.22%   |
| Intel Celeron M         | 2         | 0.22%   |
| AMD Ryzen 7 PRO         | 2         | 0.22%   |
| AMD Mobile Sempron      | 2         | 0.22%   |
| AMD E1                  | 2         | 0.22%   |
| Intel Core m7           | 1         | 0.11%   |
| Intel Core i9           | 1         | 0.11%   |
| Intel Celeron Dual-Core | 1         | 0.11%   |
| AMD Turion 64 X2 Mobile | 1         | 0.11%   |
| AMD Turion              | 1         | 0.11%   |
| AMD Ryzen 5 PRO         | 1         | 0.11%   |
| AMD Quad-Core           | 1         | 0.11%   |
| AMD Phenom II           | 1         | 0.11%   |
| AMD FX                  | 1         | 0.11%   |
| AMD Athlon 64 X2        | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 483       | 52.67%  |
| 4      | 294       | 32.06%  |
| 6      | 56        | 6.11%   |
| 8      | 43        | 4.69%   |
| 1      | 28        | 3.05%   |
| 14     | 4         | 0.44%   |
| 12     | 4         | 0.44%   |
| 10     | 4         | 0.44%   |
| 3      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 917       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 616       | 67.18%  |
| 1      | 301       | 32.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 869       | 94.46%  |
| Unknown        | 29        | 3.15%   |
| 32-bit         | 19        | 2.07%   |
| 64-bit         | 3         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 208       | 22.01%  |
| 0x306a9    | 49        | 5.19%   |
| 0x206a7    | 48        | 5.08%   |
| 0x1067a    | 41        | 4.34%   |
| 0x806ec    | 36        | 3.81%   |
| 0x10676    | 34        | 3.6%    |
| 0x806ea    | 31        | 3.28%   |
| 0x6fd      | 30        | 3.17%   |
| 0x906ea    | 28        | 2.96%   |
| 0x806c1    | 26        | 2.75%   |
| 0x40651    | 24        | 2.54%   |
| 0x306d4    | 21        | 2.22%   |
| 0x20655    | 21        | 2.22%   |
| 0x406e3    | 18        | 1.9%    |
| 0x806eb    | 16        | 1.69%   |
| 0x20652    | 16        | 1.69%   |
| 0x806e9    | 15        | 1.59%   |
| 0x306c3    | 14        | 1.48%   |
| 0x506e3    | 13        | 1.38%   |
| 0x30678    | 13        | 1.38%   |
| 0x08108109 | 13        | 1.38%   |
| 0x08200103 | 11        | 1.16%   |
| 0xa0652    | 10        | 1.06%   |
| 0x406c3    | 10        | 1.06%   |
| 0x0a50000c | 10        | 1.06%   |
| 0x406c4    | 8         | 0.85%   |
| 0x106ca    | 8         | 0.85%   |
| 0x08108102 | 8         | 0.85%   |
| 0x07030105 | 8         | 0.85%   |
| 0x906e9    | 7         | 0.74%   |
| 0x6f6      | 7         | 0.74%   |
| 0x906a3    | 6         | 0.63%   |
| 0x6d8      | 6         | 0.63%   |
| 0x106e5    | 6         | 0.63%   |
| 0x08600104 | 6         | 0.63%   |
| 0x08600103 | 6         | 0.63%   |
| 0x06006704 | 6         | 0.63%   |
| 0x706e5    | 5         | 0.53%   |
| 0x08608103 | 5         | 0.53%   |
| 0x08600106 | 5         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 158       | 17.23%  |
| Penryn           | 87        | 9.49%   |
| IvyBridge        | 62        | 6.76%   |
| SandyBridge      | 59        | 6.43%   |
| Haswell          | 56        | 6.11%   |
| Core             | 54        | 5.89%   |
| Westmere         | 48        | 5.23%   |
| Skylake          | 46        | 5.02%   |
| Silvermont       | 42        | 4.58%   |
| TigerLake        | 35        | 3.82%   |
| Broadwell        | 29        | 3.16%   |
| Zen+             | 24        | 2.62%   |
| Zen 3            | 23        | 2.51%   |
| Zen 2            | 23        | 2.51%   |
| Zen              | 19        | 2.07%   |
| Puma             | 16        | 1.74%   |
| Bonnell          | 15        | 1.64%   |
| Unknown          | 15        | 1.64%   |
| CometLake        | 14        | 1.53%   |
| P6               | 13        | 1.42%   |
| Excavator        | 13        | 1.42%   |
| Jaguar           | 10        | 1.09%   |
| Alderlake Hybrid | 8         | 0.87%   |
| Nehalem          | 7         | 0.76%   |
| IceLake          | 7         | 0.76%   |
| Goldmont plus    | 6         | 0.65%   |
| Steamroller      | 5         | 0.55%   |
| Bobcat           | 5         | 0.55%   |
| K8 Hammer        | 4         | 0.44%   |
| K8 & K10 hybrid  | 4         | 0.44%   |
| Piledriver       | 3         | 0.33%   |
| Goldmont         | 3         | 0.33%   |
| K10 Llano        | 2         | 0.22%   |
| Tremont          | 1         | 0.11%   |
| K10              | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 606       | 50.08%  |
| Nvidia                           | 346       | 28.6%   |
| AMD                              | 249       | 20.58%  |
| Silicon Integrated Systems [SiS] | 9         | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 62        | 4.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 3.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 35        | 2.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 2.77%   |
| Intel UHD Graphics 620                                                                   | 34        | 2.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 33        | 2.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 2.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 2.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 26        | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 1.98%   |
| Intel HD Graphics 5500                                                                   | 24        | 1.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 23        | 1.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 23        | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 1.82%   |
| AMD Renoir                                                                               | 21        | 1.66%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 20        | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.5%    |
| Intel HD Graphics 620                                                                    | 18        | 1.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 1.43%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 17        | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 1.11%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 1.11%   |
| Intel HD Graphics 530                                                                    | 14        | 1.11%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.87%   |
| Nvidia GP108M [GeForce MX250]                                                            | 11        | 0.87%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 11        | 0.87%   |
| Intel HD Graphics 630                                                                    | 11        | 0.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 0.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.87%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 11        | 0.87%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 10        | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.79%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 9         | 0.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 0.71%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 9         | 0.71%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 8         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 342       | 37.25%  |
| Intel + Nvidia | 219       | 23.86%  |
| 1 x AMD        | 157       | 17.1%   |
| 1 x Nvidia     | 98        | 10.68%  |
| Intel + AMD    | 45        | 4.9%    |
| AMD + Nvidia   | 29        | 3.16%   |
| 2 x AMD        | 19        | 2.07%   |
| 1 x SiS        | 9         | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 750       | 80.56%  |
| Proprietary | 148       | 15.9%   |
| Unknown     | 33        | 3.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 510       | 54.31%  |
| 0.01-0.5   | 163       | 17.36%  |
| 1.01-2.0   | 129       | 13.74%  |
| 0.51-1.0   | 68        | 7.24%   |
| 3.01-4.0   | 43        | 4.58%   |
| 5.01-6.0   | 17        | 1.81%   |
| 7.01-8.0   | 7         | 0.75%   |
| 2.01-3.0   | 2         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 197       | 20.1%   |
| Chimei Innolux          | 142       | 14.49%  |
| LG Display              | 121       | 12.35%  |
| BOE                     | 109       | 11.12%  |
| Samsung Electronics     | 93        | 9.49%   |
| Goldstar                | 32        | 3.27%   |
| Chi Mei Optoelectronics | 30        | 3.06%   |
| Apple                   | 24        | 2.45%   |
| LG Philips              | 21        | 2.14%   |
| Dell                    | 19        | 1.94%   |
| PANDA                   | 18        | 1.84%   |
| Lenovo                  | 18        | 1.84%   |
| Hewlett-Packard         | 17        | 1.73%   |
| Ancor Communications    | 16        | 1.63%   |
| Sharp                   | 13        | 1.33%   |
| AOC                     | 12        | 1.22%   |
| Philips                 | 9         | 0.92%   |
| BenQ                    | 8         | 0.82%   |
| CPT                     | 7         | 0.71%   |
| Sony                    | 6         | 0.61%   |
| Seiko/Epson             | 6         | 0.61%   |
| MSI                     | 5         | 0.51%   |
| InfoVision              | 5         | 0.51%   |
| Acer                    | 5         | 0.51%   |
| HannStar                | 4         | 0.41%   |
| ASUSTek Computer        | 4         | 0.41%   |
| Toshiba                 | 3         | 0.31%   |
| LGD                     | 3         | 0.31%   |
| LG Electronics          | 3         | 0.31%   |
| CSO                     | 3         | 0.31%   |
| ViewSonic               | 2         | 0.2%    |
| Unknown                 | 2         | 0.2%    |
| Panasonic               | 2         | 0.2%    |
| HUAWEI                  | 2         | 0.2%    |
| CVT                     | 2         | 0.2%    |
| ZTR                     | 1         | 0.1%    |
| RTK                     | 1         | 0.1%    |
| Plain Tree Systems      | 1         | 0.1%    |
| Nvidia                  | 1         | 0.1%    |
| Mi                      | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 11        | 1.11%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 11        | 1.11%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.91%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 8         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 6         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 6         | 0.6%    |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                     | 6         | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 6         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.5%    |
| LG Philips LCD Monitor LPLDD00 1280x800 331x207mm 15.4-inch              | 5         | 0.5%    |
| LG Display LCD Monitor LGD045D 1366x768 345x194mm 15.6-inch              | 5         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 5         | 0.5%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 5         | 0.5%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.5%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 4         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 4         | 0.4%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.4%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.4%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 4         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 4         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 4         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 4         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.4%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 4         | 0.4%    |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 4         | 0.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 4         | 0.4%    |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 333       | 36.67%  |
| 1366x768 (WXGA)    | 331       | 36.45%  |
| 1280x800 (WXGA)    | 58        | 6.39%   |
| 1600x900 (HD+)     | 30        | 3.3%    |
| 3840x2160 (4K)     | 27        | 2.97%   |
| 1440x900 (WXGA+)   | 19        | 2.09%   |
| 2560x1440 (QHD)    | 13        | 1.43%   |
| 1680x1050 (WSXGA+) | 12        | 1.32%   |
| 1280x1024 (SXGA)   | 12        | 1.32%   |
| 1920x1200 (WUXGA)  | 8         | 0.88%   |
| 2560x1080          | 7         | 0.77%   |
| 1024x600           | 6         | 0.66%   |
| 3440x1440          | 5         | 0.55%   |
| 2560x1600          | 5         | 0.55%   |
| 2160x1440          | 5         | 0.55%   |
| 1360x768           | 5         | 0.55%   |
| 1024x768 (XGA)     | 5         | 0.55%   |
| 2880x1800          | 4         | 0.44%   |
| Unknown            | 4         | 0.44%   |
| 3840x2400          | 3         | 0.33%   |
| 3200x1800 (QHD+)   | 3         | 0.33%   |
| 2288x1287          | 2         | 0.22%   |
| 1400x1050          | 2         | 0.22%   |
| 640x480            | 1         | 0.11%   |
| 3840x1080          | 1         | 0.11%   |
| 3520x1080          | 1         | 0.11%   |
| 3280x1080          | 1         | 0.11%   |
| 3000x2000          | 1         | 0.11%   |
| 2880x1620          | 1         | 0.11%   |
| 2726x768           | 1         | 0.11%   |
| 2240x1400          | 1         | 0.11%   |
| 1600x1200          | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 464       | 47.44%  |
| 14      | 116       | 11.86%  |
| 13      | 114       | 11.66%  |
| 17      | 50        | 5.11%   |
| 24      | 34        | 3.48%   |
| 21      | 28        | 2.86%   |
| 27      | 23        | 2.35%   |
| Unknown | 23        | 2.35%   |
| 23      | 21        | 2.15%   |
| 12      | 18        | 1.84%   |
| 11      | 16        | 1.64%   |
| 34      | 13        | 1.33%   |
| 16      | 9         | 0.92%   |
| 10      | 9         | 0.92%   |
| 22      | 8         | 0.82%   |
| 19      | 6         | 0.61%   |
| 31      | 5         | 0.51%   |
| 40      | 4         | 0.41%   |
| 18      | 4         | 0.41%   |
| 20      | 3         | 0.31%   |
| 84      | 2         | 0.2%    |
| 72      | 2         | 0.2%    |
| 26      | 2         | 0.2%    |
| 25      | 2         | 0.2%    |
| 54      | 1         | 0.1%    |
| 8       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 637       | 66.15%  |
| 201-300     | 97        | 10.07%  |
| 501-600     | 73        | 7.58%   |
| 351-400     | 55        | 5.71%   |
| 401-500     | 47        | 4.88%   |
| Unknown     | 23        | 2.39%   |
| 701-800     | 13        | 1.35%   |
| 601-700     | 8         | 0.83%   |
| 801-900     | 4         | 0.42%   |
| 1501-2000   | 4         | 0.42%   |
| 101-200     | 1         | 0.1%    |
| 1001-1500   | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 695       | 79.98%  |
| 16/10   | 113       | 13%     |
| Unknown | 21        | 2.42%   |
| 21/9    | 12        | 1.38%   |
| 5/4     | 11        | 1.27%   |
| 4/3     | 9         | 1.04%   |
| 3/2     | 8         | 0.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 464       | 47.49%  |
| 81-90          | 186       | 19.04%  |
| 201-250        | 76        | 7.78%   |
| 71-80          | 43        | 4.4%    |
| 121-130        | 32        | 3.28%   |
| 301-350        | 24        | 2.46%   |
| Unknown        | 23        | 2.35%   |
| 61-70          | 18        | 1.84%   |
| 351-500        | 17        | 1.74%   |
| 151-200        | 17        | 1.74%   |
| 51-60          | 16        | 1.64%   |
| 141-150        | 12        | 1.23%   |
| 251-300        | 11        | 1.13%   |
| 41-50          | 9         | 0.92%   |
| 131-140        | 8         | 0.82%   |
| 111-120        | 6         | 0.61%   |
| More than 1000 | 5         | 0.51%   |
| 501-1000       | 5         | 0.51%   |
| 91-100         | 4         | 0.41%   |
| 1-40           | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 342       | 35.89%  |
| 121-160       | 329       | 34.52%  |
| 51-100        | 192       | 20.15%  |
| 161-240       | 46        | 4.83%   |
| Unknown       | 23        | 2.41%   |
| More than 240 | 18        | 1.89%   |
| 1-50          | 3         | 0.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 737       | 78.57%  |
| 2     | 139       | 14.82%  |
| 0     | 42        | 4.48%   |
| 3     | 17        | 1.81%   |
| 4     | 3         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 477       | 32.52%  |
| Intel                             | 416       | 28.36%  |
| Qualcomm Atheros                  | 260       | 17.72%  |
| Broadcom                          | 110       | 7.5%    |
| Marvell Technology Group          | 43        | 2.93%   |
| TP-Link                           | 24        | 1.64%   |
| Broadcom Limited                  | 18        | 1.23%   |
| MediaTek                          | 17        | 1.16%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.82%   |
| Ralink                            | 12        | 0.82%   |
| Nvidia                            | 8         | 0.55%   |
| Ralink Technology                 | 5         | 0.34%   |
| ASIX Electronics                  | 5         | 0.34%   |
| Sierra Wireless                   | 4         | 0.27%   |
| JMicron Technology                | 4         | 0.27%   |
| Ericsson Business Mobile Networks | 4         | 0.27%   |
| D-Link                            | 4         | 0.27%   |
| Attansic Technology               | 4         | 0.27%   |
| Qualcomm Atheros Communications   | 3         | 0.2%    |
| Lenovo                            | 3         | 0.2%    |
| ICS Advent                        | 3         | 0.2%    |
| Hewlett-Packard                   | 3         | 0.2%    |
| DisplayLink                       | 3         | 0.2%    |
| ASUSTek Computer                  | 3         | 0.2%    |
| Samsung Electronics               | 2         | 0.14%   |
| Huawei Technologies               | 2         | 0.14%   |
| Fibocom                           | 2         | 0.14%   |
| Dell                              | 2         | 0.14%   |
| Xiaomi                            | 1         | 0.07%   |
| TRENDnet                          | 1         | 0.07%   |
| Toshiba                           | 1         | 0.07%   |
| T & A Mobile Phones               | 1         | 0.07%   |
| SparkFun                          | 1         | 0.07%   |
| Qualcomm                          | 1         | 0.07%   |
| Micro Star International          | 1         | 0.07%   |
| LSI                               | 1         | 0.07%   |
| GrupoPIE PORTUGAL                 | 1         | 0.07%   |
| D-Link System                     | 1         | 0.07%   |
| Belkin Components                 | 1         | 0.07%   |
| Archos                            | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 290       | 16.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 108       | 6.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 3.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 45        | 2.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 37        | 2.14%   |
| Intel Wi-Fi 6 AX200                                                     | 35        | 2.03%   |
| Intel Wireless 8265 / 8275                                              | 30        | 1.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 29        | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 1.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 1.62%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                    | 25        | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                           | 25        | 1.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 24        | 1.39%   |
| Intel Wi-Fi 6 AX201                                                     | 24        | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 22        | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 1.22%   |
| Intel Wireless 7260                                                     | 21        | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 21        | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 20        | 1.16%   |
| Intel Wireless 7265                                                     | 19        | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 1.1%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 17        | 0.98%   |
| Intel Wireless 8260                                                     | 17        | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 17        | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 15        | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 14        | 0.81%   |
| Intel Wireless 3165                                                     | 12        | 0.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 11        | 0.64%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 11        | 0.64%   |
| Intel Wireless 3160                                                     | 11        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 0.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 0.64%   |
| Intel WiFi Link 5100                                                    | 10        | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 404       | 43.39%  |
| Qualcomm Atheros                | 229       | 24.6%   |
| Realtek Semiconductor           | 135       | 14.5%   |
| Broadcom                        | 88        | 9.45%   |
| MediaTek                        | 16        | 1.72%   |
| Ralink                          | 12        | 1.29%   |
| Broadcom Limited                | 12        | 1.29%   |
| TP-Link                         | 8         | 0.86%   |
| Ralink Technology               | 5         | 0.54%   |
| Sierra Wireless                 | 4         | 0.43%   |
| D-Link                          | 4         | 0.43%   |
| Qualcomm Atheros Communications | 3         | 0.32%   |
| ASUSTek Computer                | 3         | 0.32%   |
| Fibocom                         | 2         | 0.21%   |
| Dell                            | 2         | 0.21%   |
| TRENDnet                        | 1         | 0.11%   |
| Micro Star International        | 1         | 0.11%   |
| D-Link System                   | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 5.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 45        | 4.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 37        | 3.97%   |
| Intel Wi-Fi 6 AX200                                                     | 35        | 3.76%   |
| Intel Wireless 8265 / 8275                                              | 30        | 3.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 3.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 3.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 25        | 2.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 24        | 2.58%   |
| Intel Wi-Fi 6 AX201                                                     | 24        | 2.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 2.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 22        | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 2.26%   |
| Intel Wireless 7260                                                     | 21        | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 21        | 2.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 2.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 20        | 2.15%   |
| Intel Wireless 7265                                                     | 19        | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 2.04%   |
| Intel Wireless 8260                                                     | 17        | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 1.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 15        | 1.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 14        | 1.5%    |
| Intel Wireless 3165                                                     | 12        | 1.29%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 11        | 1.18%   |
| Intel Wireless 3160                                                     | 11        | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 1.18%   |
| Intel WiFi Link 5100                                                    | 10        | 1.07%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 0.97%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.97%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 0.86%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 8         | 0.86%   |
| Intel Wireless-AC 9260                                                  | 7         | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                          | 7         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 438       | 56.23%  |
| Intel                            | 121       | 15.53%  |
| Qualcomm Atheros                 | 62        | 7.96%   |
| Marvell Technology Group         | 43        | 5.52%   |
| Broadcom                         | 38        | 4.88%   |
| TP-Link                          | 17        | 2.18%   |
| Silicon Integrated Systems [SiS] | 12        | 1.54%   |
| Nvidia                           | 8         | 1.03%   |
| Broadcom Limited                 | 6         | 0.77%   |
| ASIX Electronics                 | 5         | 0.64%   |
| JMicron Technology               | 4         | 0.51%   |
| Attansic Technology              | 4         | 0.51%   |
| Lenovo                           | 3         | 0.39%   |
| ICS Advent                       | 3         | 0.39%   |
| DisplayLink                      | 3         | 0.39%   |
| Samsung Electronics              | 2         | 0.26%   |
| Hewlett-Packard                  | 2         | 0.26%   |
| Xiaomi                           | 1         | 0.13%   |
| T & A Mobile Phones              | 1         | 0.13%   |
| Qualcomm                         | 1         | 0.13%   |
| MediaTek                         | 1         | 0.13%   |
| LSI                              | 1         | 0.13%   |
| Huawei Technologies              | 1         | 0.13%   |
| Archos                           | 1         | 0.13%   |
| Allwinner Technology             | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 290       | 37.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 108       | 13.83%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 29        | 3.71%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 25        | 3.2%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 17        | 2.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17        | 2.18%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 11        | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 9         | 1.15%   |
| Intel Ethernet Connection I218-LM                                              | 9         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 1.15%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 8         | 1.02%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 8         | 1.02%   |
| Intel 82579V Gigabit Network Connection                                        | 8         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                                          | 7         | 0.9%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 7         | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 6         | 0.77%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.64%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 5         | 0.64%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 0.64%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 0.64%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 4         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                                          | 4         | 0.51%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 0.51%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 0.51%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 0.51%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 4         | 0.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 4         | 0.51%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 4         | 0.51%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.38%   |
| Nvidia MCP77 Ethernet                                                          | 3         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 895       | 53.56%  |
| Ethernet | 760       | 45.48%  |
| Modem    | 14        | 0.84%   |
| Unknown  | 2         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 715       | 73.86%  |
| Ethernet | 253       | 26.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 681       | 74.18%  |
| 1     | 218       | 23.75%  |
| 0     | 17        | 1.85%   |
| 3     | 2         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 703       | 75.03%  |
| Yes  | 234       | 24.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 277       | 41.78%  |
| Realtek Semiconductor           | 70        | 10.56%  |
| Qualcomm Atheros Communications | 54        | 8.14%   |
| IMC Networks                    | 51        | 7.69%   |
| Lite-On Technology              | 41        | 6.18%   |
| Foxconn / Hon Hai               | 37        | 5.58%   |
| Broadcom                        | 32        | 4.83%   |
| Apple                           | 23        | 3.47%   |
| Toshiba                         | 17        | 2.56%   |
| Hewlett-Packard                 | 14        | 2.11%   |
| ASUSTek Computer                | 12        | 1.81%   |
| Realtek                         | 9         | 1.36%   |
| Dell                            | 9         | 1.36%   |
| Ralink                          | 5         | 0.75%   |
| Cambridge Silicon Radio         | 4         | 0.6%    |
| Alps Electric                   | 4         | 0.6%    |
| Ralink Technology               | 2         | 0.3%    |
| Foxconn International           | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 110       | 16.59%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 50        | 7.54%   |
| Realtek Bluetooth Radio                                                             | 49        | 7.39%   |
| Intel AX201 Bluetooth                                                               | 49        | 7.39%   |
| Intel AX200 Bluetooth                                                               | 35        | 5.28%   |
| IMC Networks Bluetooth Device                                                       | 28        | 4.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 17        | 2.56%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 16        | 2.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 1.96%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.96%   |
| Apple Bluetooth Host Controller                                                     | 12        | 1.81%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 1.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.66%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 1.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 11        | 1.66%   |
| Lite-On Bluetooth Device                                                            | 10        | 1.51%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1.51%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.51%   |
| Realtek Bluetooth Radio                                                             | 9         | 1.36%   |
| Apple Bluetooth USB Host Controller                                                 | 9         | 1.36%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 8         | 1.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 7         | 1.06%   |
| Intel Bluetooth Device                                                              | 6         | 0.9%    |
| IMC Networks Wireless_Device                                                        | 6         | 0.9%    |
| Realtek RTL8821A Bluetooth                                                          | 5         | 0.75%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 0.75%   |
| Lite-On BCM43142A0                                                                  | 5         | 0.75%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.75%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 0.75%   |
| Toshiba Integrated Bluetooth HCI                                                    | 4         | 0.6%    |
| Toshiba Askey Bluetooth Module                                                      | 4         | 0.6%    |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 4         | 0.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 0.6%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 0.6%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 4         | 0.6%    |
| Toshiba Bluetooth Device                                                            | 3         | 0.45%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 3         | 0.45%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 719       | 63.8%   |
| AMD                              | 202       | 17.92%  |
| Nvidia                           | 136       | 12.07%  |
| Silicon Integrated Systems [SiS] | 12        | 1.06%   |
| C-Media Electronics              | 7         | 0.62%   |
| Realtek Semiconductor            | 6         | 0.53%   |
| GN Netcom                        | 5         | 0.44%   |
| Creative Technology              | 4         | 0.35%   |
| Texas Instruments                | 2         | 0.18%   |
| Razer USA                        | 2         | 0.18%   |
| Plantronics                      | 2         | 0.18%   |
| Lenovo                           | 2         | 0.18%   |
| Kingston Technology              | 2         | 0.18%   |
| JMTek                            | 2         | 0.18%   |
| Hewlett-Packard                  | 2         | 0.18%   |
| Generalplus Technology           | 2         | 0.18%   |
| DSEA A/S                         | 2         | 0.18%   |
| XMOS                             | 1         | 0.09%   |
| Trust                            | 1         | 0.09%   |
| Sony                             | 1         | 0.09%   |
| Micro Star International         | 1         | 0.09%   |
| Logitech                         | 1         | 0.09%   |
| JBL                              | 1         | 0.09%   |
| Huawei Technologies              | 1         | 0.09%   |
| GYROCOM C&C                      | 1         | 0.09%   |
| ESS Technology                   | 1         | 0.09%   |
| EGO SYStems                      | 1         | 0.09%   |
| Dell                             | 1         | 0.09%   |
| Corsair                          | 1         | 0.09%   |
| Conexant Systems                 | 1         | 0.09%   |
| Conexant                         | 1         | 0.09%   |
| CMX Systems                      | 1         | 0.09%   |
| BEHRINGER International          | 1         | 0.09%   |
| ASUSTek Computer                 | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 95        | 7.08%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 80        | 5.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 68        | 5.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 61        | 4.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 55        | 4.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 53        | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 53        | 3.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 42        | 3.13%   |
| AMD FCH Azalia Controller                                                                         | 38        | 2.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 35        | 2.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 35        | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 34        | 2.54%   |
| Intel 8 Series HD Audio Controller                                                                | 34        | 2.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 34        | 2.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 33        | 2.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 31        | 2.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 30        | 2.24%   |
| Intel Broadwell-U Audio Controller                                                                | 29        | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 28        | 2.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 28        | 2.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 1.27%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 15        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 0.89%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 11        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 11        | 0.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 0.82%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 0.82%   |
| AMD High Definition Audio Controller                                                              | 11        | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 0.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 10        | 0.75%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 10        | 0.75%   |
| Nvidia High Definition Audio Controller                                                           | 9         | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 156       | 31.08%  |
| SK hynix            | 115       | 22.91%  |
| Unknown             | 64        | 12.75%  |
| Micron Technology   | 51        | 10.16%  |
| Kingston            | 43        | 8.57%   |
| Ramaxel Technology  | 13        | 2.59%   |
| G.Skill             | 9         | 1.79%   |
| Crucial             | 9         | 1.79%   |
| Elpida              | 7         | 1.39%   |
| Corsair             | 7         | 1.39%   |
| A-DATA Technology   | 7         | 1.39%   |
| Transcend           | 3         | 0.6%    |
| Team                | 3         | 0.6%    |
| Nanya Technology    | 3         | 0.6%    |
| Unknown (ABCD)      | 1         | 0.2%    |
| Unigen              | 1         | 0.2%    |
| Toshiba             | 1         | 0.2%    |
| Teikon              | 1         | 0.2%    |
| PUSKILL             | 1         | 0.2%    |
| Netlist             | 1         | 0.2%    |
| GOODRAM             | 1         | 0.2%    |
| Goldkey             | 1         | 0.2%    |
| Essencore Limited   | 1         | 0.2%    |
| Apacer              | 1         | 0.2%    |
| 48spaces            | 1         | 0.2%    |
| Unknown             | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 23        | 4.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 2.66%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 13        | 2.47%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 9         | 1.71%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 1.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.14%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 1.14%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.95%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 5         | 0.95%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.95%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.76%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.76%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.76%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.76%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.76%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.76%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 4         | 0.76%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.76%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.57%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 3         | 0.57%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.57%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.57%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.57%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.57%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.57%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.57%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.57%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s             | 3         | 0.57%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s                   | 2         | 0.38%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 207       | 48.25%  |
| DDR3    | 124       | 28.9%   |
| DDR2    | 46        | 10.72%  |
| LPDDR3  | 16        | 3.73%   |
| LPDDR4  | 15        | 3.5%    |
| SDRAM   | 10        | 2.33%   |
| LPDDR5  | 3         | 0.7%    |
| DDR5    | 3         | 0.7%    |
| DDR     | 3         | 0.7%    |
| Unknown | 2         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 371       | 86.68%  |
| Row Of Chips | 53        | 12.38%  |
| DIMM         | 2         | 0.47%   |
| Chip         | 2         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 150       | 32.05%  |
| 4096    | 136       | 29.06%  |
| 2048    | 74        | 15.81%  |
| 16384   | 73        | 15.6%   |
| 1024    | 19        | 4.06%   |
| 32768   | 11        | 2.35%   |
| 512     | 4         | 0.85%   |
| Unknown | 1         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 99        | 21.71%  |
| 1600    | 81        | 17.76%  |
| 3200    | 70        | 15.35%  |
| Unknown | 41        | 8.99%   |
| 2400    | 29        | 6.36%   |
| 2133    | 26        | 5.7%    |
| 1334    | 20        | 4.39%   |
| 1333    | 12        | 2.63%   |
| 667     | 12        | 2.63%   |
| 8400    | 10        | 2.19%   |
| 4267    | 8         | 1.75%   |
| 4199    | 6         | 1.32%   |
| 3266    | 6         | 1.32%   |
| 1067    | 6         | 1.32%   |
| 1867    | 5         | 1.1%    |
| 800     | 5         | 1.1%    |
| 6400    | 3         | 0.66%   |
| 4800    | 3         | 0.66%   |
| 1066    | 3         | 0.66%   |
| 533     | 3         | 0.66%   |
| 2933    | 2         | 0.44%   |
| 4266    | 1         | 0.22%   |
| 3733    | 1         | 0.22%   |
| 3000    | 1         | 0.22%   |
| 2048    | 1         | 0.22%   |
| 1866    | 1         | 0.22%   |
| 1200    | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 4         | 57.14%  |
| Seiko Epson            | 1         | 14.29%  |
| Samsung Electronics    | 1         | 14.29%  |
| Panasonic (Matsushita) | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson AcuLaser C1700           | 1         | 14.29%  |
| Samsung ML-1640 Series Laser Printer | 1         | 14.29%  |
| Panasonic (Matsushita) KX-FLB851SP   | 1         | 14.29%  |
| HP OfficeJet 3830 series             | 1         | 14.29%  |
| HP DeskJet F4100 Printer series      | 1         | 14.29%  |
| HP Deskjet 3050A                     | 1         | 14.29%  |
| HP DeskJet 2130 series               | 1         | 14.29%  |

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
| Chicony Electronics                    | 225       | 27.57%  |
| IMC Networks                           | 111       | 13.6%   |
| Realtek Semiconductor                  | 66        | 8.09%   |
| Acer                                   | 55        | 6.74%   |
| Suyin                                  | 46        | 5.64%   |
| Quanta                                 | 39        | 4.78%   |
| Microdia                               | 36        | 4.41%   |
| Ricoh                                  | 31        | 3.8%    |
| Cheng Uei Precision Industry (Foxlink) | 25        | 3.06%   |
| Syntek                                 | 24        | 2.94%   |
| Sunplus Innovation Technology          | 24        | 2.94%   |
| Lite-On Technology                     | 23        | 2.82%   |
| Apple                                  | 18        | 2.21%   |
| Luxvisions Innotech Limited            | 12        | 1.47%   |
| Silicon Motion                         | 10        | 1.23%   |
| Alcor Micro                            | 8         | 0.98%   |
| Lenovo                                 | 7         | 0.86%   |
| Importek                               | 7         | 0.86%   |
| Z-Star Microelectronics                | 6         | 0.74%   |
| Bison Electronics                      | 6         | 0.74%   |
| Logitech                               | 4         | 0.49%   |
| Generalplus Technology                 | 4         | 0.49%   |
| Samsung Electronics                    | 3         | 0.37%   |
| ALi                                    | 3         | 0.37%   |
| WaveRider Communications               | 2         | 0.25%   |
| Sonix Technology                       | 2         | 0.25%   |
| Primax Electronics                     | 2         | 0.25%   |
| Microsoft                              | 2         | 0.25%   |
| DigiTech                               | 2         | 0.25%   |
| Creative Technology                    | 2         | 0.25%   |
| Y Media                                | 1         | 0.12%   |
| Trust                                  | 1         | 0.12%   |
| OmniVision Technologies                | 1         | 0.12%   |
| Mustek Systems                         | 1         | 0.12%   |
| MacroSilicon                           | 1         | 0.12%   |
| lihappe8                               | 1         | 0.12%   |
| kingcome                               | 1         | 0.12%   |
| Intel                                  | 1         | 0.12%   |
| Genesys Logic                          | 1         | 0.12%   |
| Gearway Electronics (Dong Guan)        | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 32        | 3.91%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 31        | 3.79%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 21        | 2.56%   |
| IMC Networks Integrated Camera                      | 21        | 2.56%   |
| Chicony HD Webcam                                   | 21        | 2.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 18        | 2.2%    |
| Chicony USB2.0 VGA UVC WebCam                       | 15        | 1.83%   |
| Chicony USB 2.0 Camera                              | 13        | 1.59%   |
| Chicony CNF9055 Toshiba Webcam                      | 13        | 1.59%   |
| Realtek USB Camera                                  | 12        | 1.47%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 11        | 1.34%   |
| Realtek EasyCamera                                  | 11        | 1.34%   |
| Microdia Integrated_Webcam_HD                       | 11        | 1.34%   |
| Chicony TOSHIBA Web Camera - HD                     | 11        | 1.34%   |
| Acer Integrated Camera                              | 11        | 1.34%   |
| IMC Networks HD Camera                              | 9         | 1.1%    |
| Syntek Integrated Camera                            | 8         | 0.98%   |
| Realtek Integrated_Webcam_HD                        | 8         | 0.98%   |
| Quanta HP Wide Vision HD Camera                     | 8         | 0.98%   |
| Suyin USB 2.0 Camera                                | 7         | 0.85%   |
| Realtek HD WebCam                                   | 7         | 0.85%   |
| Quanta HP TrueVision HD Camera                      | 7         | 0.85%   |
| Lite-On Integrated Camera                           | 7         | 0.85%   |
| IMC Networks ov9734_azurewave_camera                | 7         | 0.85%   |
| Chicony HP Truevision HD                            | 7         | 0.85%   |
| Chicony HP HD Camera                                | 7         | 0.85%   |
| Acer HD Webcam                                      | 7         | 0.85%   |
| Syntek EasyCamera                                   | 6         | 0.73%   |
| Sunplus HD WebCam                                   | 6         | 0.73%   |
| Realtek USB2.0-Camera                               | 6         | 0.73%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 0.73%   |
| Chicony VGA Webcam                                  | 6         | 0.73%   |
| Chicony USB2.0 HD UVC WebCam                        | 6         | 0.73%   |
| Chicony USB2.0 Camera                               | 6         | 0.73%   |
| Quanta VGA WebCam                                   | 5         | 0.61%   |
| Microdia USB 2.0 Camera                             | 5         | 0.61%   |
| Microdia Sonix USB 2.0 Camera                       | 5         | 0.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.61%   |
| Lite-On TOSHIBA Web Camera - HD                     | 5         | 0.61%   |
| Chicony Webcam                                      | 5         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 43        | 33.33%  |
| Validity Sensors                   | 39        | 30.23%  |
| Shenzhen Goodix Technology         | 19        | 14.73%  |
| AuthenTec                          | 9         | 6.98%   |
| Upek                               | 6         | 4.65%   |
| Elan Microelectronics              | 6         | 4.65%   |
| LighTuning Technology              | 4         | 3.1%    |
| STMicroelectronics                 | 2         | 1.55%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 15        | 11.63%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 7.75%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 6.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 3.88%   |
| Synaptics UWP WBDI Device                                                  | 5         | 3.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.1%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 3.1%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 3.1%    |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.1%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 3.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 3.1%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.33%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.33%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.33%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.33%   |
| AuthenTec AES2810                                                          | 3         | 2.33%   |
| AuthenTec AES1600                                                          | 3         | 2.33%   |
| Validity Sensors VFS491                                                    | 2         | 1.55%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.55%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.55%   |
| Synaptics WBDI                                                             | 2         | 1.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.55%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.55%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.55%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.78%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.78%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.78%   |
| Synaptics WBDI Device                                                      | 1         | 0.78%   |
| Synaptics UWP WBDI                                                         | 1         | 0.78%   |
| Synaptics  WBDI                                                            | 1         | 0.78%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.78%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.78%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 22        | 38.6%   |
| Broadcom              | 17        | 29.82%  |
| O2 Micro              | 5         | 8.77%   |
| Gemalto (was Gemplus) | 4         | 7.02%   |
| Lenovo                | 3         | 5.26%   |
| SCM Microsystems      | 2         | 3.51%   |
| Yubico.com            | 1         | 1.75%   |
| Upek                  | 1         | 1.75%   |
| Cherry                | 1         | 1.75%   |
| Advanced Card Systems | 1         | 1.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 22        | 38.6%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 12.28%  |
| Broadcom 58200                                                               | 6         | 10.53%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 7.02%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.26%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 5.26%   |
| Broadcom 5880                                                                | 3         | 5.26%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 3.51%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.75%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.75%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.75%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.75%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.75%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.75%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.75%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 596       | 63%     |
| 1     | 266       | 28.12%  |
| 2     | 65        | 6.87%   |
| 3     | 14        | 1.48%   |
| 4     | 4         | 0.42%   |
| 5     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 128       | 29.63%  |
| Graphics card            | 116       | 26.85%  |
| Net/wireless             | 54        | 12.5%   |
| Chipcard                 | 44        | 10.19%  |
| Multimedia controller    | 34        | 7.87%   |
| Camera                   | 14        | 3.24%   |
| Card reader              | 9         | 2.08%   |
| Bluetooth                | 9         | 2.08%   |
| Storage                  | 7         | 1.62%   |
| Communication controller | 5         | 1.16%   |
| Modem                    | 4         | 0.93%   |
| Flash memory             | 4         | 0.93%   |
| Net/ethernet             | 2         | 0.46%   |
| Sound                    | 1         | 0.23%   |
| Network                  | 1         | 0.23%   |


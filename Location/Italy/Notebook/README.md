Linux in Italy - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 6354

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | OMEN by Laptop 15-dc1xxx    | [fb024a9374](https://linux-hardware.org/?probe=fb024a9374) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [398f85e94a](https://linux-hardware.org/?probe=398f85e94a) | Aug 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [b21e9793a5](https://linux-hardware.org/?probe=b21e9793a5) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| Dell          | Latitude 5300               | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [9627b6d632](https://linux-hardware.org/?probe=9627b6d632) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [099d1ac0de](https://linux-hardware.org/?probe=099d1ac0de) | Aug 10, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | [abf7479cb8](https://linux-hardware.org/?probe=abf7479cb8) | Aug 09, 2023 |
| Acer          | Aspire V3-112P              | [e6305472c5](https://linux-hardware.org/?probe=e6305472c5) | Aug 09, 2023 |
| Lenovo        | ThinkPad X240 20AL00C6UK    | [d33c586eab](https://linux-hardware.org/?probe=d33c586eab) | Aug 09, 2023 |
| Unknown       | Unknown                     | [5f186cbc4d](https://linux-hardware.org/?probe=5f186cbc4d) | Aug 09, 2023 |
| HP            | EliteBook 8470p             | [16acf13ed8](https://linux-hardware.org/?probe=16acf13ed8) | Aug 09, 2023 |
| HP            | 255 G5                      | [d4adfe0ead](https://linux-hardware.org/?probe=d4adfe0ead) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | [f3ee04187f](https://linux-hardware.org/?probe=f3ee04187f) | Aug 09, 2023 |
| Dell          | Inspiron 5584               | [33e964d1d6](https://linux-hardware.org/?probe=33e964d1d6) | Aug 09, 2023 |
| Dell          | XPS L521X                   | [5aec7ef034](https://linux-hardware.org/?probe=5aec7ef034) | Aug 08, 2023 |
| Dell          | Latitude 7440               | [0cfa45fbd8](https://linux-hardware.org/?probe=0cfa45fbd8) | Aug 08, 2023 |
| Dell          | Latitude 7440               | [e476a3e532](https://linux-hardware.org/?probe=e476a3e532) | Aug 08, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [3cd08fb125](https://linux-hardware.org/?probe=3cd08fb125) | Aug 08, 2023 |
| Timi          | A7S                         | [34a354df5a](https://linux-hardware.org/?probe=34a354df5a) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [ce02da2586](https://linux-hardware.org/?probe=ce02da2586) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [aabc0a8aee](https://linux-hardware.org/?probe=aabc0a8aee) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [4dec7b692a](https://linux-hardware.org/?probe=4dec7b692a) | Aug 07, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Dell          | Latitude E5540              | [928c427cbc](https://linux-hardware.org/?probe=928c427cbc) | Aug 06, 2023 |
| Dell          | Precision 7730              | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| Dell          | Inspiron 15 5510            | [88f7813621](https://linux-hardware.org/?probe=88f7813621) | Aug 06, 2023 |
| HP            | 255 G8 Notebook PC          | [5b67a1f9cf](https://linux-hardware.org/?probe=5b67a1f9cf) | Aug 06, 2023 |
| Dell          | Inspiron 5584               | [7a4e005f77](https://linux-hardware.org/?probe=7a4e005f77) | Aug 06, 2023 |
| Dell          | Latitude E6230              | [cc78868322](https://linux-hardware.org/?probe=cc78868322) | Aug 05, 2023 |
| Dell          | Inspiron 15 5510            | [6d78d72399](https://linux-hardware.org/?probe=6d78d72399) | Aug 05, 2023 |
| Mediacom      | SmartBook 130 FullHD - M... | [3aa51361ae](https://linux-hardware.org/?probe=3aa51361ae) | Aug 05, 2023 |
| Apple         | MacBookAir7,2               | [e21469f818](https://linux-hardware.org/?probe=e21469f818) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6fd7ffb05b](https://linux-hardware.org/?probe=6fd7ffb05b) | Aug 04, 2023 |
| SANTECH       | NL5xNU                      | [68d1f62251](https://linux-hardware.org/?probe=68d1f62251) | Aug 04, 2023 |
| HP            | Notebook                    | [9b9a2bd44a](https://linux-hardware.org/?probe=9b9a2bd44a) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Dell          | Latitude 5530               | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| PC Special... | Lafite Pro III 17           | [702cdf4138](https://linux-hardware.org/?probe=702cdf4138) | Aug 03, 2023 |
| Apple         | MacBookAir7,2               | [89c0c5c135](https://linux-hardware.org/?probe=89c0c5c135) | Aug 03, 2023 |
| Timi          | A7S                         | [7de693ff63](https://linux-hardware.org/?probe=7de693ff63) | Aug 03, 2023 |
| HP            | ENVY 17                     | [ef244ad969](https://linux-hardware.org/?probe=ef244ad969) | Aug 02, 2023 |
| HP            | 255 G8 Notebook PC          | [d0e963d600](https://linux-hardware.org/?probe=d0e963d600) | Aug 02, 2023 |
| Dell          | Precision 3571              | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [6cfc0b2281](https://linux-hardware.org/?probe=6cfc0b2281) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| MSI           | Alpha 15 B5EEK              | [18924cfab7](https://linux-hardware.org/?probe=18924cfab7) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [00c9fab30f](https://linux-hardware.org/?probe=00c9fab30f) | Jul 31, 2023 |
| ASUSTek       | P552LA                      | [d84e6d9683](https://linux-hardware.org/?probe=d84e6d9683) | Jul 30, 2023 |
| SiComputer    | NL40_50CU                   | [95afbe5674](https://linux-hardware.org/?probe=95afbe5674) | Jul 30, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| Beelink       | Gemini X                    | [2846d152be](https://linux-hardware.org/?probe=2846d152be) | Jul 29, 2023 |
| Dell          | System XPS L702X            | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Lenovo        | V15-IGL 82C3                | [613164e308](https://linux-hardware.org/?probe=613164e308) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6546d49225](https://linux-hardware.org/?probe=6546d49225) | Jul 27, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [87d69792fb](https://linux-hardware.org/?probe=87d69792fb) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [83097985a2](https://linux-hardware.org/?probe=83097985a2) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| ASUSTek       | P50IJ                       | [d8aff1255a](https://linux-hardware.org/?probe=d8aff1255a) | Jul 25, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | [47d5775197](https://linux-hardware.org/?probe=47d5775197) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| SANTECH       | NHx0DB,DE                   | [80aa11a7e8](https://linux-hardware.org/?probe=80aa11a7e8) | Jul 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [f347019f85](https://linux-hardware.org/?probe=f347019f85) | Jul 24, 2023 |
| Dell          | Latitude 5420               | [c286ff883f](https://linux-hardware.org/?probe=c286ff883f) | Jul 24, 2023 |
| HP            | 250 G3                      | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | [2def302827](https://linux-hardware.org/?probe=2def302827) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | [2f0b072622](https://linux-hardware.org/?probe=2f0b072622) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | [84c7ea08c6](https://linux-hardware.org/?probe=84c7ea08c6) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| Timi          | A7S                         | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| HP            | ProBook 635 Aero G8 Note... | [ff5392a180](https://linux-hardware.org/?probe=ff5392a180) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| HP            | 250 G1                      | [deab96c404](https://linux-hardware.org/?probe=deab96c404) | Jul 23, 2023 |
| Sony          | SVE1713X1EB                 | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [ea078c7fb9](https://linux-hardware.org/?probe=ea078c7fb9) | Jul 22, 2023 |
| MSI           | GL63 8SD                    | [7705e15f5e](https://linux-hardware.org/?probe=7705e15f5e) | Jul 21, 2023 |
| Dell          | XPS 9315                    | [f97422b64b](https://linux-hardware.org/?probe=f97422b64b) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [32ec9929c9](https://linux-hardware.org/?probe=32ec9929c9) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [a1f316c8c9](https://linux-hardware.org/?probe=a1f316c8c9) | Jul 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [e99bf7a4be](https://linux-hardware.org/?probe=e99bf7a4be) | Jul 20, 2023 |
| Sony          | SVE1713X1EB                 | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [56e1ff54a3](https://linux-hardware.org/?probe=56e1ff54a3) | Jul 19, 2023 |
| Lenovo        | ThinkPad E15 20RDS1G700     | [6ad3194fd9](https://linux-hardware.org/?probe=6ad3194fd9) | Jul 18, 2023 |
| Acer          | Aspire 7750G                | [c7d69d227a](https://linux-hardware.org/?probe=c7d69d227a) | Jul 17, 2023 |
| MSI           | Creator 17 A10SE            | [775c65db16](https://linux-hardware.org/?probe=775c65db16) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [7f25599ad8](https://linux-hardware.org/?probe=7f25599ad8) | Jul 17, 2023 |
| Unknown       | Unknown                     | [2bda9f913a](https://linux-hardware.org/?probe=2bda9f913a) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [8c94595be0](https://linux-hardware.org/?probe=8c94595be0) | Jul 17, 2023 |
| Olivetti      | Olipad Graphos W811         | [d303fe2826](https://linux-hardware.org/?probe=d303fe2826) | Jul 17, 2023 |
| Toshiba       | TECRA A10                   | [0740ca470e](https://linux-hardware.org/?probe=0740ca470e) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | [91f38d0ab5](https://linux-hardware.org/?probe=91f38d0ab5) | Jul 16, 2023 |
| ASUSTek       | K53SJ                       | [eb5e64c657](https://linux-hardware.org/?probe=eb5e64c657) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| HP            | 250 G8 Notebook PC          | [60809c13e6](https://linux-hardware.org/?probe=60809c13e6) | Jul 15, 2023 |
| Lenovo        | ThinkPad T450 20BUS0S902    | [34329ab49c](https://linux-hardware.org/?probe=34329ab49c) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | [97e2731292](https://linux-hardware.org/?probe=97e2731292) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | [fab0c2fb26](https://linux-hardware.org/?probe=fab0c2fb26) | Jul 15, 2023 |
| Notebook      | PCX0DX                      | [4b7f45adc4](https://linux-hardware.org/?probe=4b7f45adc4) | Jul 15, 2023 |
| HUAWEI        | BOM-WXX9                    | [31ae047fcf](https://linux-hardware.org/?probe=31ae047fcf) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [25bd8ff761](https://linux-hardware.org/?probe=25bd8ff761) | Jul 14, 2023 |
| HUAWEI        | HN-WX9X                     | [9868eab45f](https://linux-hardware.org/?probe=9868eab45f) | Jul 14, 2023 |
| HP            | ENVY 15                     | [d69bc2702c](https://linux-hardware.org/?probe=d69bc2702c) | Jul 14, 2023 |
| HP            | Compaq CQ58                 | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Dell          | Latitude 5501               | [b10b0e72f0](https://linux-hardware.org/?probe=b10b0e72f0) | Jul 13, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | [be2db3ecfa](https://linux-hardware.org/?probe=be2db3ecfa) | Jul 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d2dd2ac514](https://linux-hardware.org/?probe=d2dd2ac514) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| Toshiba       | Satellite Pro S500          | [b9b5f89f0c](https://linux-hardware.org/?probe=b9b5f89f0c) | Jul 12, 2023 |
| Acer          | Aspire A515-47              | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | [bc78a01502](https://linux-hardware.org/?probe=bc78a01502) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | [c01febb128](https://linux-hardware.org/?probe=c01febb128) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | [a4f7584ee4](https://linux-hardware.org/?probe=a4f7584ee4) | Jul 12, 2023 |
| MSI           | Katana GF66 12UC            | [aac3e629d3](https://linux-hardware.org/?probe=aac3e629d3) | Jul 11, 2023 |
| Acer          | Aspire A715-71G             | [cd76343b6e](https://linux-hardware.org/?probe=cd76343b6e) | Jul 11, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [59b334f01a](https://linux-hardware.org/?probe=59b334f01a) | Jul 10, 2023 |
| Panasonic     | CF-C1BD06EFG                | [3b5ab4416a](https://linux-hardware.org/?probe=3b5ab4416a) | Jul 10, 2023 |
| HUAWEI        | HLYL-WXX9                   | [480ee8d732](https://linux-hardware.org/?probe=480ee8d732) | Jul 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [71329b9909](https://linux-hardware.org/?probe=71329b9909) | Jul 10, 2023 |
| Lenovo        | V15-IGL 82C3                | [9f920e8a7e](https://linux-hardware.org/?probe=9f920e8a7e) | Jul 10, 2023 |
| Dell          | Latitude E6440              | [6265e6109a](https://linux-hardware.org/?probe=6265e6109a) | Jul 09, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [acdb08441f](https://linux-hardware.org/?probe=acdb08441f) | Jul 09, 2023 |
| HUAWEI        | HN-WX9X                     | [c01a765f59](https://linux-hardware.org/?probe=c01a765f59) | Jul 09, 2023 |
| Acer          | Aspire F5-573G              | [10cf2c3aa5](https://linux-hardware.org/?probe=10cf2c3aa5) | Jul 09, 2023 |
| HP            | Notebook                    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| Acer          | Aspire V3-371               | [b4f20e8bc3](https://linux-hardware.org/?probe=b4f20e8bc3) | Jul 08, 2023 |
| Acer          | TravelMate 5335             | [7422cf6091](https://linux-hardware.org/?probe=7422cf6091) | Jul 08, 2023 |
| Acer          | Chapala                     | [6ea600326f](https://linux-hardware.org/?probe=6ea600326f) | Jul 08, 2023 |
| MSI           | Alpha 15 B5EEK              | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | Inspiron 7720               | [dde4874147](https://linux-hardware.org/?probe=dde4874147) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [6a739102d0](https://linux-hardware.org/?probe=6a739102d0) | Jul 08, 2023 |
| Acer          | Aspire E1-570G              | [f1d3e3070e](https://linux-hardware.org/?probe=f1d3e3070e) | Jul 07, 2023 |
| Olidata       | Stainer 8050                | [beb3c029a6](https://linux-hardware.org/?probe=beb3c029a6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| Timi          | RedmiBook 16                | [dbb5eb75b8](https://linux-hardware.org/?probe=dbb5eb75b8) | Jul 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [e484073491](https://linux-hardware.org/?probe=e484073491) | Jul 07, 2023 |
| Acer          | Aspire E1-570G              | [276cdeb14d](https://linux-hardware.org/?probe=276cdeb14d) | Jul 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [e134f78b10](https://linux-hardware.org/?probe=e134f78b10) | Jul 07, 2023 |
| Dell          | Precision M6800             | [4b8d02d04a](https://linux-hardware.org/?probe=4b8d02d04a) | Jul 06, 2023 |
| Dell          | Precision M6800             | [239c3ea2b9](https://linux-hardware.org/?probe=239c3ea2b9) | Jul 06, 2023 |
| Apple         | MacBookPro14,3              | [d6153317bf](https://linux-hardware.org/?probe=d6153317bf) | Jul 05, 2023 |
| Toshiba       | Satellite L750              | [037db5066a](https://linux-hardware.org/?probe=037db5066a) | Jul 05, 2023 |
| Dell          | Latitude 7440               | [2efee1eb6c](https://linux-hardware.org/?probe=2efee1eb6c) | Jul 05, 2023 |
| Sony          | VGN-NS21M_W                 | [36b9bc971f](https://linux-hardware.org/?probe=36b9bc971f) | Jul 05, 2023 |
| MSI           | Creator 15M A9SD            | [84c85a8969](https://linux-hardware.org/?probe=84c85a8969) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | [71de589577](https://linux-hardware.org/?probe=71de589577) | Jul 04, 2023 |
| Packard Be... | EasyNote MH36               | [87873c1e0e](https://linux-hardware.org/?probe=87873c1e0e) | Jul 03, 2023 |
| ASUSTek       | K55VD                       | [1a3814f9d9](https://linux-hardware.org/?probe=1a3814f9d9) | Jul 03, 2023 |
| Toshiba       | Satellite C660              | [3e88dd8cd6](https://linux-hardware.org/?probe=3e88dd8cd6) | Jul 03, 2023 |
| Dell          | XPS 15 7590                 | [de620c05a9](https://linux-hardware.org/?probe=de620c05a9) | Jul 03, 2023 |
| MSI           | Katana GF66 12UC            | [b241427d10](https://linux-hardware.org/?probe=b241427d10) | Jul 03, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9ebec4e811](https://linux-hardware.org/?probe=9ebec4e811) | Jul 03, 2023 |
| Jumper        | EZbook                      | [735e20e770](https://linux-hardware.org/?probe=735e20e770) | Jul 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f341618e19](https://linux-hardware.org/?probe=f341618e19) | Jul 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [2ac145f096](https://linux-hardware.org/?probe=2ac145f096) | Jul 02, 2023 |
| HP            | Pavilion dv6                | [0840377177](https://linux-hardware.org/?probe=0840377177) | Jul 02, 2023 |
| Dell          | Latitude E6420              | [aae88e9000](https://linux-hardware.org/?probe=aae88e9000) | Jul 01, 2023 |
| Acer          | Aspire A315-55G             | [caddb7bcf7](https://linux-hardware.org/?probe=caddb7bcf7) | Jul 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Acer          | Aspire 7750G                | [ec3012e08e](https://linux-hardware.org/?probe=ec3012e08e) | Jul 01, 2023 |
| Apple         | MacBookPro14,3              | [4a51b35cb8](https://linux-hardware.org/?probe=4a51b35cb8) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| Dell          | Vostro 2520                 | [48d04d8282](https://linux-hardware.org/?probe=48d04d8282) | Jun 30, 2023 |
| Dell          | Latitude 5521               | [3a8f3794aa](https://linux-hardware.org/?probe=3a8f3794aa) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [1db11a4fa9](https://linux-hardware.org/?probe=1db11a4fa9) | Jun 29, 2023 |
| Acer          | Aspire 5750G                | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| Dell          | Latitude 7440               | [24f85667ac](https://linux-hardware.org/?probe=24f85667ac) | Jun 28, 2023 |
| Acer          | Aspire A315-21              | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | [7f0ae1c657](https://linux-hardware.org/?probe=7f0ae1c657) | Jun 27, 2023 |
| Dell          | XPS 15 9500                 | [8ea6d92813](https://linux-hardware.org/?probe=8ea6d92813) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [24d66c058b](https://linux-hardware.org/?probe=24d66c058b) | Jun 27, 2023 |
| HP            | ENVY 15                     | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| HP            | Pavilion dv6                | [fe7974bbc9](https://linux-hardware.org/?probe=fe7974bbc9) | Jun 26, 2023 |
| HP            | Pavilion dv6                | [3051c4ac4e](https://linux-hardware.org/?probe=3051c4ac4e) | Jun 26, 2023 |
| Acer          | Aspire V3-772               | [12cc9ac9dc](https://linux-hardware.org/?probe=12cc9ac9dc) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Google        | Sasuke                      | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| Toshiba       | Satellite A300              | [6f1d7a6089](https://linux-hardware.org/?probe=6f1d7a6089) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Microtech     | CoreBook Lite               | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| Packard Be... | EasyNote TJ65               | [cdc135487b](https://linux-hardware.org/?probe=cdc135487b) | Jun 24, 2023 |
| HP            | Presario CQ56               | [5a8991a97b](https://linux-hardware.org/?probe=5a8991a97b) | Jun 23, 2023 |
| HP            | Laptop 15-da0xxx            | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| HP            | ENVY 15                     | [3918cca1e5](https://linux-hardware.org/?probe=3918cca1e5) | Jun 23, 2023 |
| HP            | Pavilion g6                 | [fa58c1a1fd](https://linux-hardware.org/?probe=fa58c1a1fd) | Jun 22, 2023 |
| Acer          | Aspire 7720G                | [a8e44a5ab1](https://linux-hardware.org/?probe=a8e44a5ab1) | Jun 22, 2023 |
| HP            | Pavilion g6                 | [a58868d782](https://linux-hardware.org/?probe=a58868d782) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Dell          | Vostro 3700                 | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| ASUSTek       | K55VD                       | [223967ea1d](https://linux-hardware.org/?probe=223967ea1d) | Jun 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [44050251e9](https://linux-hardware.org/?probe=44050251e9) | Jun 22, 2023 |
| Sony          | VGN-NS21M_W                 | [6813d6589e](https://linux-hardware.org/?probe=6813d6589e) | Jun 21, 2023 |
| HP            | EliteBook 820 G2            | [d4f506e331](https://linux-hardware.org/?probe=d4f506e331) | Jun 21, 2023 |
| ASUSTek       | K55VD                       | [49f6cc6986](https://linux-hardware.org/?probe=49f6cc6986) | Jun 20, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | [42ba3d75e5](https://linux-hardware.org/?probe=42ba3d75e5) | Jun 20, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | [6e2f7d8295](https://linux-hardware.org/?probe=6e2f7d8295) | Jun 20, 2023 |
| Samsung       | RC420/RC520/RC720           | [406b650f19](https://linux-hardware.org/?probe=406b650f19) | Jun 19, 2023 |
| MSI           | PS63 Modern 8RC             | [f540e88555](https://linux-hardware.org/?probe=f540e88555) | Jun 18, 2023 |
| Dell          | Latitude 5520               | [09da4ee3c4](https://linux-hardware.org/?probe=09da4ee3c4) | Jun 18, 2023 |
| Dell          | Latitude 5520               | [5e70c1929c](https://linux-hardware.org/?probe=5e70c1929c) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [46692b99cb](https://linux-hardware.org/?probe=46692b99cb) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| Sony          | SVE1713X1EB                 | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| HUAWEI        | MACH-WX9                    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| HP            | ENVY 15                     | [10a4cb8865](https://linux-hardware.org/?probe=10a4cb8865) | Jun 17, 2023 |
| Dell          | Vostro 3700                 | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | [bbc15bef9c](https://linux-hardware.org/?probe=bbc15bef9c) | Jun 15, 2023 |
| Acer          | Aspire 1810T                | [1b1d11f461](https://linux-hardware.org/?probe=1b1d11f461) | Jun 14, 2023 |
| Samsung       | N130                        | [3efb763643](https://linux-hardware.org/?probe=3efb763643) | Jun 14, 2023 |
| MSI           | GL73 8RE                    | [e37b06f2b0](https://linux-hardware.org/?probe=e37b06f2b0) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| Dell          | XPS 15 9560                 | [f3b25c0959](https://linux-hardware.org/?probe=f3b25c0959) | Jun 14, 2023 |
| HP            | Pavilion dv7                | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Dell          | Latitude E5540              | [029d51e57f](https://linux-hardware.org/?probe=029d51e57f) | Jun 13, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [d910ebe7bb](https://linux-hardware.org/?probe=d910ebe7bb) | Jun 13, 2023 |
| Dell          | Latitude E7250              | [cc9fc2bace](https://linux-hardware.org/?probe=cc9fc2bace) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| HP            | ZBook 15 G6                 | [180abd0b90](https://linux-hardware.org/?probe=180abd0b90) | Jun 11, 2023 |
| Valve         | Jupiter                     | [d276b58f38](https://linux-hardware.org/?probe=d276b58f38) | Jun 10, 2023 |
| HP            | Compaq CQ58                 | [98a4edb43d](https://linux-hardware.org/?probe=98a4edb43d) | Jun 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bdca36306b](https://linux-hardware.org/?probe=bdca36306b) | Jun 10, 2023 |
| HUAWEI        | BOD-WXX9                    | [c4063bcf07](https://linux-hardware.org/?probe=c4063bcf07) | Jun 09, 2023 |
| HUAWEI        | BOD-WXX9                    | [9016ad81ae](https://linux-hardware.org/?probe=9016ad81ae) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | [5648ca2620](https://linux-hardware.org/?probe=5648ca2620) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | [30dbebd931](https://linux-hardware.org/?probe=30dbebd931) | Jun 09, 2023 |
| Onda TLC      | ONDA Oliver                 | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | [b88712538e](https://linux-hardware.org/?probe=b88712538e) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | [51bfdec531](https://linux-hardware.org/?probe=51bfdec531) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| HP            | G42                         | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | [d6a8e02362](https://linux-hardware.org/?probe=d6a8e02362) | Jun 08, 2023 |
| ASUSTek       | X580VN                      | [8c1cf3f164](https://linux-hardware.org/?probe=8c1cf3f164) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | [fdb80f6e89](https://linux-hardware.org/?probe=fdb80f6e89) | Jun 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [82d0019a0b](https://linux-hardware.org/?probe=82d0019a0b) | Jun 08, 2023 |
| Acer          | AO722                       | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [75a37cd4c8](https://linux-hardware.org/?probe=75a37cd4c8) | Jun 07, 2023 |
| Onda TLC      | ONDA Oliver                 | [bbfcf4a3be](https://linux-hardware.org/?probe=bbfcf4a3be) | Jun 07, 2023 |
| Dell          | Latitude 5300               | [1eea10cfa3](https://linux-hardware.org/?probe=1eea10cfa3) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Acer          | AO722                       | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Acer          | Aspire E1-571               | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | GF63 Thin 9RCX              | [85ec51dbf3](https://linux-hardware.org/?probe=85ec51dbf3) | Jun 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [c20dd8572a](https://linux-hardware.org/?probe=c20dd8572a) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | [450d20f29d](https://linux-hardware.org/?probe=450d20f29d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | [b4f165f28d](https://linux-hardware.org/?probe=b4f165f28d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | [e0ce9df73c](https://linux-hardware.org/?probe=e0ce9df73c) | Jun 05, 2023 |
| MSI           | GL75 Leopard 10SER          | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Acer          | Aspire E5-573G              | [3ef3c9ec82](https://linux-hardware.org/?probe=3ef3c9ec82) | Jun 04, 2023 |
| Sony          | SVE1713X1EB                 | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| HP            | 255 G7 Notebook PC          | [8b14da5cf8](https://linux-hardware.org/?probe=8b14da5cf8) | Jun 04, 2023 |
| HP            | ZBook 15 G2                 | [19ed8e22e6](https://linux-hardware.org/?probe=19ed8e22e6) | Jun 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ba2dfac7ae](https://linux-hardware.org/?probe=ba2dfac7ae) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| HONOR         | BBR-WAX9                    | [fe03659a55](https://linux-hardware.org/?probe=fe03659a55) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [959b76650d](https://linux-hardware.org/?probe=959b76650d) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| HONOR         | BBR-WAX9                    | [0a536c1198](https://linux-hardware.org/?probe=0a536c1198) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [fcc2d0ed39](https://linux-hardware.org/?probe=fcc2d0ed39) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | [9324563727](https://linux-hardware.org/?probe=9324563727) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | [778e78d2a5](https://linux-hardware.org/?probe=778e78d2a5) | Jun 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [0b0c375bb8](https://linux-hardware.org/?probe=0b0c375bb8) | May 31, 2023 |
| Olidata       | Tehom cw4900                | [f5b147962f](https://linux-hardware.org/?probe=f5b147962f) | May 31, 2023 |
| HONOR         | BBR-WAX9                    | [8630cfad52](https://linux-hardware.org/?probe=8630cfad52) | May 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [bfcb7f950d](https://linux-hardware.org/?probe=bfcb7f950d) | May 31, 2023 |
| Dell          | Inspiron 15 5510            | [bd2319fd67](https://linux-hardware.org/?probe=bd2319fd67) | May 31, 2023 |
| Jumper        | EZbook                      | [3ccf2e1365](https://linux-hardware.org/?probe=3ccf2e1365) | May 31, 2023 |
| HP            | ENVY 15                     | [ad3cf182fe](https://linux-hardware.org/?probe=ad3cf182fe) | May 30, 2023 |
| HP            | ENVY 15                     | [5acbfb03f4](https://linux-hardware.org/?probe=5acbfb03f4) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bb50e13268](https://linux-hardware.org/?probe=bb50e13268) | May 30, 2023 |
| HP            | Pavilion 15                 | [ca18fafda8](https://linux-hardware.org/?probe=ca18fafda8) | May 29, 2023 |
| Lenovo        | G50-45 80E3                 | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Dell          | Latitude E5470              | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Unknown       | Unknown                     | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Acer          | Aspire A515-41G             | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Apple         | MacBookAir7,2               | [2f44574d7c](https://linux-hardware.org/?probe=2f44574d7c) | May 29, 2023 |
| Apple         | MacBookPro7,1               | [81a267d02b](https://linux-hardware.org/?probe=81a267d02b) | May 28, 2023 |
| Apple         | MacBookAir7,2               | [5e146ef326](https://linux-hardware.org/?probe=5e146ef326) | May 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [c7afdbbd76](https://linux-hardware.org/?probe=c7afdbbd76) | May 28, 2023 |
| Apple         | MacBookPro6,2               | [db9c87ce89](https://linux-hardware.org/?probe=db9c87ce89) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [1eecbd5808](https://linux-hardware.org/?probe=1eecbd5808) | May 27, 2023 |
| HP            | G42                         | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| Dell          | XPS 15 9570                 | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| Dell          | XPS 15 9570                 | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | Pavilion x2 Detachable      | [e21476b6d2](https://linux-hardware.org/?probe=e21476b6d2) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [433b367e58](https://linux-hardware.org/?probe=433b367e58) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [ac85063e46](https://linux-hardware.org/?probe=ac85063e46) | May 26, 2023 |
| Acer          | Aspire 7750G                | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| Lenovo        | IdeaPad Z580                | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| ASUSTek       | S551LB                      | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| Mediacom      | SMARTBOOK ONE               | [ad010a6b3e](https://linux-hardware.org/?probe=ad010a6b3e) | May 25, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | [978ae98d6e](https://linux-hardware.org/?probe=978ae98d6e) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Sony          | SVE1513Q1ESI                | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [e484eaf025](https://linux-hardware.org/?probe=e484eaf025) | May 24, 2023 |
| Dell          | Precision 3571              | [3806fcdb9c](https://linux-hardware.org/?probe=3806fcdb9c) | May 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1280876877](https://linux-hardware.org/?probe=1280876877) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | [01e2285654](https://linux-hardware.org/?probe=01e2285654) | May 24, 2023 |
| Acer          | Aspire 7750G                | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [0dfd1ede62](https://linux-hardware.org/?probe=0dfd1ede62) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| Valve         | Jupiter                     | [223ab4f15c](https://linux-hardware.org/?probe=223ab4f15c) | May 23, 2023 |
| HP            | ENVY 15                     | [85a97390d5](https://linux-hardware.org/?probe=85a97390d5) | May 23, 2023 |
| Sony          | SVE1513Q1ESI                | [eef57d6c26](https://linux-hardware.org/?probe=eef57d6c26) | May 23, 2023 |
| HP            | Pavilion x2 Detachable      | [f9f3305d0b](https://linux-hardware.org/?probe=f9f3305d0b) | May 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [14b20068ca](https://linux-hardware.org/?probe=14b20068ca) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Dell          | Latitude E6230              | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| HUAWEI        | KLVL-WXX9                   | [5cb11eee20](https://linux-hardware.org/?probe=5cb11eee20) | May 22, 2023 |
| HP            | ENVY 15                     | [21a38278ca](https://linux-hardware.org/?probe=21a38278ca) | May 21, 2023 |
| MSI           | Modern 14 B11MOL            | [7bc8f5e875](https://linux-hardware.org/?probe=7bc8f5e875) | May 21, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [55a289b426](https://linux-hardware.org/?probe=55a289b426) | May 21, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [916d381f2f](https://linux-hardware.org/?probe=916d381f2f) | May 21, 2023 |
| ASUSTek       | N53TK                       | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Acer          | Aspire 7750G                | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [8ec7bb4682](https://linux-hardware.org/?probe=8ec7bb4682) | May 21, 2023 |
| Acer          | Aspire V3-572G              | [8f1be2d961](https://linux-hardware.org/?probe=8f1be2d961) | May 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| Toshiba       | Satellite Pro S500          | [b08ca84ea8](https://linux-hardware.org/?probe=b08ca84ea8) | May 20, 2023 |
| HP            | Pavilion dv6                | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Valve         | Jupiter                     | [6b5b728c7e](https://linux-hardware.org/?probe=6b5b728c7e) | May 20, 2023 |
| Unknown       | Unknown                     | [c7157cc723](https://linux-hardware.org/?probe=c7157cc723) | May 20, 2023 |
| HP            | Pavilion dv3                | [34c6a2c14a](https://linux-hardware.org/?probe=34c6a2c14a) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1f6220f21a](https://linux-hardware.org/?probe=1f6220f21a) | May 19, 2023 |
| MSI           | Alpha 15 B5EEK              | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Unknown       | Unknown                     | [49c702a8c9](https://linux-hardware.org/?probe=49c702a8c9) | May 18, 2023 |
| ASUSTek       | X555LPB                     | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| Acer          | Aspire 5920G                | [65638219a5](https://linux-hardware.org/?probe=65638219a5) | May 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [62e064b7d0](https://linux-hardware.org/?probe=62e064b7d0) | May 18, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | [b5aef01bc9](https://linux-hardware.org/?probe=b5aef01bc9) | May 17, 2023 |
| HP            | ENVY 15                     | [4576cea8b0](https://linux-hardware.org/?probe=4576cea8b0) | May 17, 2023 |
| ASUSTek       | UX305FA                     | [36cb231f34](https://linux-hardware.org/?probe=36cb231f34) | May 16, 2023 |
| HP            | Pavilion dv6                | [bc505434f7](https://linux-hardware.org/?probe=bc505434f7) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Acer          | Nitro AN515-45              | [62e3c494bd](https://linux-hardware.org/?probe=62e3c494bd) | May 16, 2023 |
| Valve         | Jupiter                     | [6c64da33ef](https://linux-hardware.org/?probe=6c64da33ef) | May 16, 2023 |
| Apple         | MacBook4,1                  | [755f1920f2](https://linux-hardware.org/?probe=755f1920f2) | May 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ba609eb1e6](https://linux-hardware.org/?probe=ba609eb1e6) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| HP            | Pavilion dv6                | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| Dell          | Precision 7520              | [cbfb960bae](https://linux-hardware.org/?probe=cbfb960bae) | May 15, 2023 |
| Dell          | Precision 7520              | [a42d1a8bf5](https://linux-hardware.org/?probe=a42d1a8bf5) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | [e9e5b21145](https://linux-hardware.org/?probe=e9e5b21145) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | [34c6621991](https://linux-hardware.org/?probe=34c6621991) | May 15, 2023 |
| Lenovo        | ThinkPad X100e 0022CTO      | [842b7a3ee2](https://linux-hardware.org/?probe=842b7a3ee2) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [bb119829d0](https://linux-hardware.org/?probe=bb119829d0) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [020d4612bd](https://linux-hardware.org/?probe=020d4612bd) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [ca65ed1052](https://linux-hardware.org/?probe=ca65ed1052) | May 14, 2023 |
| HP            | Compaq CQ58                 | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Valve         | Jupiter                     | [af70e39629](https://linux-hardware.org/?probe=af70e39629) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1bb0ed422e](https://linux-hardware.org/?probe=1bb0ed422e) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [24aaf9e627](https://linux-hardware.org/?probe=24aaf9e627) | May 13, 2023 |
| HP            | Pavilion dv6                | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| HP            | ENVY 15                     | [e188fe21b7](https://linux-hardware.org/?probe=e188fe21b7) | May 12, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| Unknown       | Unknown                     | [8375f52559](https://linux-hardware.org/?probe=8375f52559) | May 12, 2023 |
| HP            | OMEN by Laptop              | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| Unknown       | Unknown                     | [00f98129ce](https://linux-hardware.org/?probe=00f98129ce) | May 11, 2023 |
| Valve         | Jupiter                     | [ec8ac0aafd](https://linux-hardware.org/?probe=ec8ac0aafd) | May 11, 2023 |
| Dell          | XPS 9315                    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [e03da60adf](https://linux-hardware.org/?probe=e03da60adf) | May 11, 2023 |
| Acer          | Aspire 5715Z                | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| Acer          | Aspire E5-553G              | [922a392eee](https://linux-hardware.org/?probe=922a392eee) | May 09, 2023 |
| Dell          | Latitude 7420               | [4b8927333b](https://linux-hardware.org/?probe=4b8927333b) | May 09, 2023 |
| Dell          | Latitude E6520              | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | 255 G5                      | [4ed50eeba3](https://linux-hardware.org/?probe=4ed50eeba3) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [4e95a5b88e](https://linux-hardware.org/?probe=4e95a5b88e) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5cbf24306a](https://linux-hardware.org/?probe=5cbf24306a) | May 08, 2023 |
| Acer          | Aspire 5750G                | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a4f5dce6d6](https://linux-hardware.org/?probe=a4f5dce6d6) | May 08, 2023 |
| Dell          | XPS 15 9570                 | [100534a570](https://linux-hardware.org/?probe=100534a570) | May 08, 2023 |
| Notebook      | P750ZM                      | [2cbd56abdc](https://linux-hardware.org/?probe=2cbd56abdc) | May 08, 2023 |
| Apple         | MacBookPro3,1               | [561202c004](https://linux-hardware.org/?probe=561202c004) | May 07, 2023 |
| HP            | 255 G3                      | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| HP            | Pavilion dv6                | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Acer          | Aspire E5-551G              | [ab9ff23d88](https://linux-hardware.org/?probe=ab9ff23d88) | May 07, 2023 |
| Acer          | Aspire E5-551G              | [a21a8395d8](https://linux-hardware.org/?probe=a21a8395d8) | May 07, 2023 |
| Lenovo        | G50-70 20351                | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| Dell          | XPS 13 9343                 | [5e91733408](https://linux-hardware.org/?probe=5e91733408) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| HP            | Notebook                    | [cb89261339](https://linux-hardware.org/?probe=cb89261339) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| HP            | EliteBook 2530p             | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| Lenovo        | IdeaPad U510 20191          | [23414f0626](https://linux-hardware.org/?probe=23414f0626) | May 06, 2023 |
| HP            | Notebook                    | [74f9f1122e](https://linux-hardware.org/?probe=74f9f1122e) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [bd885c202d](https://linux-hardware.org/?probe=bd885c202d) | May 05, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [a27c899176](https://linux-hardware.org/?probe=a27c899176) | May 04, 2023 |
| HP            | 255 G8 Notebook PC          | [af9621c92b](https://linux-hardware.org/?probe=af9621c92b) | May 04, 2023 |
| HP            | Elite x2 1012 G1            | [20dcc3e6b3](https://linux-hardware.org/?probe=20dcc3e6b3) | May 04, 2023 |
| KUU           | Andes II                    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| HP            | Compaq Presario C700        | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Sony          | SVF1521G1EW                 | [b84b2ed08a](https://linux-hardware.org/?probe=b84b2ed08a) | May 03, 2023 |
| Acer          | Swift SF515-51T             | [80d7446f47](https://linux-hardware.org/?probe=80d7446f47) | May 03, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | [bb924b0c19](https://linux-hardware.org/?probe=bb924b0c19) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [4280750d03](https://linux-hardware.org/?probe=4280750d03) | May 03, 2023 |
| Samsung       | 750XDA                      | [2e99c882ff](https://linux-hardware.org/?probe=2e99c882ff) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [fd0dee0606](https://linux-hardware.org/?probe=fd0dee0606) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | [d8256a8177](https://linux-hardware.org/?probe=d8256a8177) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | [d4019e13f1](https://linux-hardware.org/?probe=d4019e13f1) | May 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [910824ac40](https://linux-hardware.org/?probe=910824ac40) | May 03, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [56d274f769](https://linux-hardware.org/?probe=56d274f769) | May 03, 2023 |
| Lenovo        | V130-15IKB 81HN             | [8c3e5e8d50](https://linux-hardware.org/?probe=8c3e5e8d50) | May 03, 2023 |
| Dell          | Latitude E7270              | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| Sony          | VPCF11C5E                   | [77f08d3d00](https://linux-hardware.org/?probe=77f08d3d00) | May 02, 2023 |
| Dell          | Latitude E7270              | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | [5375a4f57c](https://linux-hardware.org/?probe=5375a4f57c) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| HP            | 255 G4                      | [b06ddec94b](https://linux-hardware.org/?probe=b06ddec94b) | May 01, 2023 |
| Timi          | RedmiBook 16                | [01706331eb](https://linux-hardware.org/?probe=01706331eb) | May 01, 2023 |
| HP            | Compaq 8510w                | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| HP            | ENVY 15                     | [935dc183e1](https://linux-hardware.org/?probe=935dc183e1) | May 01, 2023 |
| HP            | OMEN by Laptop              | [bfbda66d8b](https://linux-hardware.org/?probe=bfbda66d8b) | May 01, 2023 |
| ASUSTek       | K52Jc                       | [ae414cf185](https://linux-hardware.org/?probe=ae414cf185) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| HP            | Compaq 6720s                | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [94118ab632](https://linux-hardware.org/?probe=94118ab632) | Apr 30, 2023 |
| MSI           | Modern 14 B11MOU            | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| Acer          | Aspire A515-51G             | [bd4c84da60](https://linux-hardware.org/?probe=bd4c84da60) | Apr 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [25d0c90e31](https://linux-hardware.org/?probe=25d0c90e31) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b6bd42eb71](https://linux-hardware.org/?probe=b6bd42eb71) | Apr 27, 2023 |
| TUXEDO        | Unknown                     | [5108a05d49](https://linux-hardware.org/?probe=5108a05d49) | Apr 27, 2023 |
| Dell          | Latitude E6400              | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| Toshiba       | Satellite Pro S500          | [7a2503959a](https://linux-hardware.org/?probe=7a2503959a) | Apr 26, 2023 |
| Acer          | TravelMate 6593             | [58dce8147e](https://linux-hardware.org/?probe=58dce8147e) | Apr 26, 2023 |
| HP            | ENVY 15                     | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [82bd4b0d20](https://linux-hardware.org/?probe=82bd4b0d20) | Apr 26, 2023 |
| Acer          | Aspire A515-45              | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Acer          | Aspire 5920G                | [c6387003fc](https://linux-hardware.org/?probe=c6387003fc) | Apr 25, 2023 |
| HP            | Laptop 17-cp0xxx            | [288f3f709c](https://linux-hardware.org/?probe=288f3f709c) | Apr 24, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Onda TLC      | ONDA Oliver                 | [c59dbdea18](https://linux-hardware.org/?probe=c59dbdea18) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| Toshiba       | Satellite Pro S500          | [fcf8a7bdb4](https://linux-hardware.org/?probe=fcf8a7bdb4) | Apr 23, 2023 |
| Dell          | Inspiron MP061              | [2b25a48030](https://linux-hardware.org/?probe=2b25a48030) | Apr 23, 2023 |
| Sony          | SVE1713X1EB                 | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [5cceab0ac3](https://linux-hardware.org/?probe=5cceab0ac3) | Apr 22, 2023 |
| Apple         | MacBook6,1                  | [47ea666f74](https://linux-hardware.org/?probe=47ea666f74) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [9a23d08368](https://linux-hardware.org/?probe=9a23d08368) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [6b255d5f07](https://linux-hardware.org/?probe=6b255d5f07) | Apr 21, 2023 |
| HP            | Pavilion Sleekbook 15       | [644ea805a9](https://linux-hardware.org/?probe=644ea805a9) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [aace924665](https://linux-hardware.org/?probe=aace924665) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| Lenovo        | G50-45 80E3                 | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| ASUSTek       | 1011PX                      | [6aa9d32dda](https://linux-hardware.org/?probe=6aa9d32dda) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9df9b0d25d](https://linux-hardware.org/?probe=9df9b0d25d) | Apr 19, 2023 |
| HP            | Pavilion x2 Detachable      | [1c7cd2fe1d](https://linux-hardware.org/?probe=1c7cd2fe1d) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9db7166b25](https://linux-hardware.org/?probe=9db7166b25) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| PC Special... | PCx0Dx                      | [0f82987a84](https://linux-hardware.org/?probe=0f82987a84) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Toshiba       | Kronos 10CUG                | [228e28e6a8](https://linux-hardware.org/?probe=228e28e6a8) | Apr 18, 2023 |
| HP            | Laptop 15s-fq1xxx           | [9437766194](https://linux-hardware.org/?probe=9437766194) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| HP            | Pavilion x2 Detachable      | [5d56d95ea5](https://linux-hardware.org/?probe=5d56d95ea5) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| Apple         | MacBookPro8,1               | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| HP            | EliteBook 8570w             | [317efe55c2](https://linux-hardware.org/?probe=317efe55c2) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [877464f534](https://linux-hardware.org/?probe=877464f534) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [650deb855e](https://linux-hardware.org/?probe=650deb855e) | Apr 17, 2023 |
| Medion        | E16401                      | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| Acer          | TravelMate 5730             | [8e99149abe](https://linux-hardware.org/?probe=8e99149abe) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Acer          | Swift SF314-41              | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| Google        | Dragonair                   | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Google        | Dragonair                   | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| HP            | Pavilion 15                 | [a51b096e12](https://linux-hardware.org/?probe=a51b096e12) | Apr 15, 2023 |
| HP            | Pavilion 15                 | [1f524a54fc](https://linux-hardware.org/?probe=1f524a54fc) | Apr 15, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| Dell          | Latitude 9420               | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | [6522f4e2dc](https://linux-hardware.org/?probe=6522f4e2dc) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| MAXDATA       | o.max_5xs                   | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| Lenovo        | V15-IGL 82C3                | [3b24daf87d](https://linux-hardware.org/?probe=3b24daf87d) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| Toshiba       | Satellite Pro S500          | [44dca3cd92](https://linux-hardware.org/?probe=44dca3cd92) | Apr 13, 2023 |
| Dell          | XPS 9315                    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| Acer          | Aspire A715-42G             | [54a72d7d55](https://linux-hardware.org/?probe=54a72d7d55) | Apr 12, 2023 |
| Packard Be... | EasyNote_MX45               | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| Lenovo        | ThinkPad L530 24783B3       | [9cb172cc6b](https://linux-hardware.org/?probe=9cb172cc6b) | Apr 11, 2023 |
| HP            | ProBook 650 G1              | [1a09ecfcd1](https://linux-hardware.org/?probe=1a09ecfcd1) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [dae979ddc0](https://linux-hardware.org/?probe=dae979ddc0) | Apr 11, 2023 |
| BESSTAR Te... | X400                        | [6b1587e21d](https://linux-hardware.org/?probe=6b1587e21d) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [e6e26b16f3](https://linux-hardware.org/?probe=e6e26b16f3) | Apr 11, 2023 |
| ASUSTek       | X541UV                      | [07b7bedac7](https://linux-hardware.org/?probe=07b7bedac7) | Apr 10, 2023 |
| ASUSTek       | N552VX                      | [a5bf121256](https://linux-hardware.org/?probe=a5bf121256) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Apple         | MacBookPro11,5              | [2e428c73dc](https://linux-hardware.org/?probe=2e428c73dc) | Apr 10, 2023 |
| ASUSTek       | K52Jc                       | [0e6d01e44d](https://linux-hardware.org/?probe=0e6d01e44d) | Apr 09, 2023 |
| Lenovo        | V14-ADA 82C6                | [23a244aaf4](https://linux-hardware.org/?probe=23a244aaf4) | Apr 09, 2023 |
| AMI           | Intel                       | [f35d255c12](https://linux-hardware.org/?probe=f35d255c12) | Apr 09, 2023 |
| ASUSTek       | K52Jc                       | [594a8d9a89](https://linux-hardware.org/?probe=594a8d9a89) | Apr 08, 2023 |
| HP            | EliteBook 2560p             | [a4b27a5659](https://linux-hardware.org/?probe=a4b27a5659) | Apr 08, 2023 |
| Sony          | VPCSE1V9E                   | [e6dd1647f3](https://linux-hardware.org/?probe=e6dd1647f3) | Apr 08, 2023 |
| Lenovo        | Z50-75 80EC                 | [1502ff1933](https://linux-hardware.org/?probe=1502ff1933) | Apr 08, 2023 |
| MSI           | Katana GF66 12UC            | [5d0c8cade6](https://linux-hardware.org/?probe=5d0c8cade6) | Apr 08, 2023 |
| Lenovo        | ThinkPad L430 24683NG       | [d5f226c56f](https://linux-hardware.org/?probe=d5f226c56f) | Apr 08, 2023 |
| HP            | Pavilion dv7                | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| HP            | Pavilion dv7                | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [1e9120783f](https://linux-hardware.org/?probe=1e9120783f) | Apr 07, 2023 |
| HP            | 250 G6 Notebook PC          | [859f83bbfc](https://linux-hardware.org/?probe=859f83bbfc) | Apr 07, 2023 |
| HP            | G61                         | [8eec217a3a](https://linux-hardware.org/?probe=8eec217a3a) | Apr 07, 2023 |
| HP            | G61                         | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Lenovo        | B51-80 80LM                 | [78e2e080ea](https://linux-hardware.org/?probe=78e2e080ea) | Apr 07, 2023 |
| System76      | Oryx Pro                    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | 250 G4                      | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | [bf0fc7e5d1](https://linux-hardware.org/?probe=bf0fc7e5d1) | Apr 06, 2023 |
| Dell          | XPS 9320                    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| Dell          | XPS 13 9380                 | [58e0aa6707](https://linux-hardware.org/?probe=58e0aa6707) | Apr 06, 2023 |
| Acer          | Aspire 5750G                | [3fa6f0de7a](https://linux-hardware.org/?probe=3fa6f0de7a) | Apr 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2X60S    | [b5b5fd68e9](https://linux-hardware.org/?probe=b5b5fd68e9) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| Lenovo        | ThinkPad X61s 7666WJ5       | [eb755a4a95](https://linux-hardware.org/?probe=eb755a4a95) | Apr 05, 2023 |
| Fujitsu       | LIFEBOOK U759               | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| Dell          | Latitude 5591               | [aa2f4e4208](https://linux-hardware.org/?probe=aa2f4e4208) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| ASUSTek       | S551LB                      | [cd1746937a](https://linux-hardware.org/?probe=cd1746937a) | Apr 04, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [93fa18f474](https://linux-hardware.org/?probe=93fa18f474) | Apr 03, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [915c34d052](https://linux-hardware.org/?probe=915c34d052) | Apr 03, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [cef60ea315](https://linux-hardware.org/?probe=cef60ea315) | Apr 03, 2023 |
| Lenovo        | ThinkPad X200 7459J74       | [d7f98c1ddb](https://linux-hardware.org/?probe=d7f98c1ddb) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Lenovo        | B50-30 80ES                 | [11da2097ba](https://linux-hardware.org/?probe=11da2097ba) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [f995b3a81f](https://linux-hardware.org/?probe=f995b3a81f) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| Packard Be... | EasyNote TJ65               | [cd6a05149d](https://linux-hardware.org/?probe=cd6a05149d) | Apr 02, 2023 |
| ASUSTek       | X555LAB                     | [95f5025351](https://linux-hardware.org/?probe=95f5025351) | Apr 02, 2023 |
| Lenovo        | B50-30 80ES                 | [a971008720](https://linux-hardware.org/?probe=a971008720) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Acer          | Aspire A515-41G             | [f047e9361c](https://linux-hardware.org/?probe=f047e9361c) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [db058df07b](https://linux-hardware.org/?probe=db058df07b) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [3691be13e8](https://linux-hardware.org/?probe=3691be13e8) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [70fb59cd4f](https://linux-hardware.org/?probe=70fb59cd4f) | Apr 01, 2023 |
| Unknown       | Unknown                     | [702a241ca6](https://linux-hardware.org/?probe=702a241ca6) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| HP            | Notebook                    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | [363d925d25](https://linux-hardware.org/?probe=363d925d25) | Apr 01, 2023 |
| ASUSTek       | X556UAK                     | [24f79c68f6](https://linux-hardware.org/?probe=24f79c68f6) | Mar 31, 2023 |
| Notebook      | W54_55SU1,SUW               | [74313ae73b](https://linux-hardware.org/?probe=74313ae73b) | Mar 31, 2023 |
| Microtech     | ebookPro                    | [ffe1da27cc](https://linux-hardware.org/?probe=ffe1da27cc) | Mar 31, 2023 |
| Acer          | Extensa 215-31              | [b1601e6747](https://linux-hardware.org/?probe=b1601e6747) | Mar 31, 2023 |
| Dell          | Latitude E7440              | [fdd9fda693](https://linux-hardware.org/?probe=fdd9fda693) | Mar 31, 2023 |
| HP            | Pavilion 15                 | [4dc2c9dfc1](https://linux-hardware.org/?probe=4dc2c9dfc1) | Mar 31, 2023 |
| Lenovo        | ThinkPad E14 20RA0016IX     | [685f18f5b3](https://linux-hardware.org/?probe=685f18f5b3) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| Valve         | Jupiter                     | [34766581f3](https://linux-hardware.org/?probe=34766581f3) | Mar 31, 2023 |
| Toshiba       | Satellite Pro S500          | [b2e60d9170](https://linux-hardware.org/?probe=b2e60d9170) | Mar 31, 2023 |
| ASUSTek       | N552VX                      | [cacf95c277](https://linux-hardware.org/?probe=cacf95c277) | Mar 30, 2023 |
| Acer          | Aspire ES1-523              | [a800dab0ab](https://linux-hardware.org/?probe=a800dab0ab) | Mar 30, 2023 |
| Sony          | SVE1713X1EB                 | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [45f39402f0](https://linux-hardware.org/?probe=45f39402f0) | Mar 30, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| Dell          | Precision 3560              | [f6ef5c1a2c](https://linux-hardware.org/?probe=f6ef5c1a2c) | Mar 30, 2023 |
| Lenovo        | G505 20240                  | [25c5c7ee2e](https://linux-hardware.org/?probe=25c5c7ee2e) | Mar 30, 2023 |
| Toshiba       | Satellite L655              | [2e6ea8bf5c](https://linux-hardware.org/?probe=2e6ea8bf5c) | Mar 30, 2023 |
| Dell          | Latitude 5580               | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK A555               | [6f28f9e6ec](https://linux-hardware.org/?probe=6f28f9e6ec) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| Lenovo        | G50-45 80E3                 | [7bfed0aedd](https://linux-hardware.org/?probe=7bfed0aedd) | Mar 29, 2023 |
| HP            | Laptop 15-dw0xxx            | [53bc341050](https://linux-hardware.org/?probe=53bc341050) | Mar 29, 2023 |
| Valve         | Jupiter                     | [889e4e5eef](https://linux-hardware.org/?probe=889e4e5eef) | Mar 29, 2023 |
| HP            | ProBook 640 G1              | [c9ac2eb353](https://linux-hardware.org/?probe=c9ac2eb353) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [f44d26ed76](https://linux-hardware.org/?probe=f44d26ed76) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| HP            | ProBook 450 G7              | [8b27d78a17](https://linux-hardware.org/?probe=8b27d78a17) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | N53SV                       | [77aa77b2a3](https://linux-hardware.org/?probe=77aa77b2a3) | Mar 28, 2023 |
| Unknown       | Unknown                     | [26d819f9fc](https://linux-hardware.org/?probe=26d819f9fc) | Mar 27, 2023 |
| HP            | 250 G1                      | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| Sony          | SVE1713X1EB                 | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [2f96abf16a](https://linux-hardware.org/?probe=2f96abf16a) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [07caea9176](https://linux-hardware.org/?probe=07caea9176) | Mar 27, 2023 |
| Acer          | Mammoth                     | [d43ab9891b](https://linux-hardware.org/?probe=d43ab9891b) | Mar 27, 2023 |
| Sony          | VPCEH1S1E                   | [081294b14c](https://linux-hardware.org/?probe=081294b14c) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| ASUSTek       | X550LD                      | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| ASUSTek       | N552VW                      | [322426698a](https://linux-hardware.org/?probe=322426698a) | Mar 26, 2023 |
| Apple         | MacBookPro11,5              | [0c2be4a34c](https://linux-hardware.org/?probe=0c2be4a34c) | Mar 26, 2023 |
| Dell          | XPS 13 9305                 | [5b29fbd6ac](https://linux-hardware.org/?probe=5b29fbd6ac) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| HP            | Laptop 15-dw3xxx            | [3b8cd70b69](https://linux-hardware.org/?probe=3b8cd70b69) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | [0bfaf1252f](https://linux-hardware.org/?probe=0bfaf1252f) | Mar 25, 2023 |
| Dell          | Latitude E6230              | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Acer          | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | XPS 13 9305                 | [c7e354ffe3](https://linux-hardware.org/?probe=c7e354ffe3) | Mar 24, 2023 |
| Apple         | MacBookPro11,5              | [9fd6508caf](https://linux-hardware.org/?probe=9fd6508caf) | Mar 24, 2023 |
| Dell          | Latitude 5580               | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| ASUSTek       | K53SJ                       | [175f99ccdd](https://linux-hardware.org/?probe=175f99ccdd) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| HUAWEI        | BOD-WXX9                    | [088494906d](https://linux-hardware.org/?probe=088494906d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Dell          | Inspiron 1750               | [007a0b3bb7](https://linux-hardware.org/?probe=007a0b3bb7) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Toshiba       | Satellite Pro S500          | [2bb2519c2c](https://linux-hardware.org/?probe=2bb2519c2c) | Mar 21, 2023 |
| Toshiba       | Satellite Pro S500          | [a45c7086e5](https://linux-hardware.org/?probe=a45c7086e5) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| Acer          | Extensa 5235                | [270cd6ed83](https://linux-hardware.org/?probe=270cd6ed83) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| Notebook      | P15SM                       | [00d7786f9f](https://linux-hardware.org/?probe=00d7786f9f) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | G62                         | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| HP            | Laptop 15-dw1xxx            | [63ecda6230](https://linux-hardware.org/?probe=63ecda6230) | Mar 18, 2023 |
| HP            | ProBook 6570b               | [f5c9cd8419](https://linux-hardware.org/?probe=f5c9cd8419) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | K61IC                       | [045474725b](https://linux-hardware.org/?probe=045474725b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S88M0... | [2ad89b7995](https://linux-hardware.org/?probe=2ad89b7995) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [6a1e908693](https://linux-hardware.org/?probe=6a1e908693) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Dell          | Latitude E5470              | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| MSI           | Modern 14 B11MOL            | [33bbc272c0](https://linux-hardware.org/?probe=33bbc272c0) | Mar 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c454542aaa](https://linux-hardware.org/?probe=c454542aaa) | Mar 15, 2023 |
| Valve         | Jupiter                     | [fc387a787e](https://linux-hardware.org/?probe=fc387a787e) | Mar 15, 2023 |
| Toshiba       | Satellite Pro S500          | [0065669867](https://linux-hardware.org/?probe=0065669867) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b0b311216d](https://linux-hardware.org/?probe=b0b311216d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [0f6370d7f7](https://linux-hardware.org/?probe=0f6370d7f7) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [d9f9e09a41](https://linux-hardware.org/?probe=d9f9e09a41) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [be16fd4aab](https://linux-hardware.org/?probe=be16fd4aab) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| HP            | Pavilion dv6500             | [03097b6049](https://linux-hardware.org/?probe=03097b6049) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [ee01825196](https://linux-hardware.org/?probe=ee01825196) | Mar 13, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Acer          | aspire5740                  | [d5e64f31d4](https://linux-hardware.org/?probe=d5e64f31d4) | Mar 12, 2023 |
| HP            | Laptop 15s-fq5xxx           | [5bf763c288](https://linux-hardware.org/?probe=5bf763c288) | Mar 11, 2023 |
| Dell          | Latitude E6440              | [e5ba284442](https://linux-hardware.org/?probe=e5ba284442) | Mar 11, 2023 |
| HP            | G61                         | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| ASUSTek       | X556UQK                     | [e5c898a856](https://linux-hardware.org/?probe=e5c898a856) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| HP            | EliteBook 840 G1            | [1315898b67](https://linux-hardware.org/?probe=1315898b67) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ffcc55bb14](https://linux-hardware.org/?probe=ffcc55bb14) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [420b463f4d](https://linux-hardware.org/?probe=420b463f4d) | Mar 10, 2023 |
| ASUSTek       | X540LA                      | [de3c24e686](https://linux-hardware.org/?probe=de3c24e686) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [041ebfc8c6](https://linux-hardware.org/?probe=041ebfc8c6) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [8faa1d14ca](https://linux-hardware.org/?probe=8faa1d14ca) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| Timi          | TM1701                      | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| HP            | Pavilion dv6                | [a1631eb10b](https://linux-hardware.org/?probe=a1631eb10b) | Mar 07, 2023 |
| Unknown       | Unknown                     | [fdc4f4d3c6](https://linux-hardware.org/?probe=fdc4f4d3c6) | Mar 07, 2023 |
| Dell          | Latitude 5330               | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [f56dc75b4e](https://linux-hardware.org/?probe=f56dc75b4e) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| Acer          | Aspire E5-575G              | [fd8c378fda](https://linux-hardware.org/?probe=fd8c378fda) | Mar 07, 2023 |
| ASUSTek       | X556UAK                     | [51f2084195](https://linux-hardware.org/?probe=51f2084195) | Mar 06, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [745898b5de](https://linux-hardware.org/?probe=745898b5de) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [20fbc926fd](https://linux-hardware.org/?probe=20fbc926fd) | Mar 06, 2023 |
| Lenovo        | G50-45 80E3                 | [02dfdb807e](https://linux-hardware.org/?probe=02dfdb807e) | Mar 06, 2023 |
| HP            | G72                         | [64009d0874](https://linux-hardware.org/?probe=64009d0874) | Mar 06, 2023 |
| HP            | ProBook 430 G5              | [aaebada0ca](https://linux-hardware.org/?probe=aaebada0ca) | Mar 06, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Microtech     | ebookPro                    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| Dell          | Inspiron 17-7779            | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| Apple         | MacBookPro10,1              | [7b7aa513b8](https://linux-hardware.org/?probe=7b7aa513b8) | Mar 04, 2023 |
| Toshiba       | NB550D                      | [8ba5171640](https://linux-hardware.org/?probe=8ba5171640) | Mar 04, 2023 |
| HP            | G72                         | [a094ef43f1](https://linux-hardware.org/?probe=a094ef43f1) | Mar 04, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4816618219](https://linux-hardware.org/?probe=4816618219) | Mar 04, 2023 |
| Dell          | Inspiron 16 7610            | [1121d93a65](https://linux-hardware.org/?probe=1121d93a65) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| HP            | ENVY 15                     | [9ceefd9a22](https://linux-hardware.org/?probe=9ceefd9a22) | Mar 03, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [17f1328add](https://linux-hardware.org/?probe=17f1328add) | Mar 03, 2023 |
| HP            | ENVY dv6                    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [f791caa732](https://linux-hardware.org/?probe=f791caa732) | Mar 03, 2023 |
| Acer          | Aspire 5732Z                | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Toshiba       | Satellite L50-B             | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [0b39498d52](https://linux-hardware.org/?probe=0b39498d52) | Mar 03, 2023 |
| GMK           | NucBox2                     | [84af5a7d53](https://linux-hardware.org/?probe=84af5a7d53) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [c34c6d8786](https://linux-hardware.org/?probe=c34c6d8786) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2a1515aaa3](https://linux-hardware.org/?probe=2a1515aaa3) | Mar 02, 2023 |
| Acer          | TravelMate P253             | [aa56b7749c](https://linux-hardware.org/?probe=aa56b7749c) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Acer          | Aspire 5755G                | [c1594b1f9d](https://linux-hardware.org/?probe=c1594b1f9d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [98e86d41d1](https://linux-hardware.org/?probe=98e86d41d1) | Mar 01, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [61fe88e268](https://linux-hardware.org/?probe=61fe88e268) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | Pavilion 15                 | [78f570552a](https://linux-hardware.org/?probe=78f570552a) | Mar 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [b518eb9925](https://linux-hardware.org/?probe=b518eb9925) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| Acer          | Aspire 5750G                | [34b5806bcf](https://linux-hardware.org/?probe=34b5806bcf) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| Acer          | Aspire E1-531               | [a52b94c2d5](https://linux-hardware.org/?probe=a52b94c2d5) | Feb 27, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [2cea6ee649](https://linux-hardware.org/?probe=2cea6ee649) | Feb 26, 2023 |
| ASUSTek       | X540NA                      | [8bca0d4eb5](https://linux-hardware.org/?probe=8bca0d4eb5) | Feb 26, 2023 |
| Timi          | TM1612                      | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| ASUSTek       | T100HAN                     | [bde9736ffd](https://linux-hardware.org/?probe=bde9736ffd) | Feb 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [84750f9d96](https://linux-hardware.org/?probe=84750f9d96) | Feb 25, 2023 |
| Acer          | Aspire A515-51G             | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Acer          | Aspire ES1-521              | [e5f0a23afd](https://linux-hardware.org/?probe=e5f0a23afd) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| HP            | 250 G3                      | [6a3d2238ba](https://linux-hardware.org/?probe=6a3d2238ba) | Feb 25, 2023 |
| ASUSTek       | T100HAN                     | [fd75fdb59f](https://linux-hardware.org/?probe=fd75fdb59f) | Feb 25, 2023 |
| ASUSTek       | X556URK                     | [fc80e01794](https://linux-hardware.org/?probe=fc80e01794) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| BESSTAR Te... | X400                        | [e1c05e0782](https://linux-hardware.org/?probe=e1c05e0782) | Feb 25, 2023 |
| HP            | ENVY 17                     | [08db7a8be2](https://linux-hardware.org/?probe=08db7a8be2) | Feb 25, 2023 |
| HP            | ENVY 17                     | [0ad15a7e01](https://linux-hardware.org/?probe=0ad15a7e01) | Feb 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| HONOR         | HYM-WXX                     | [c6f84d1224](https://linux-hardware.org/?probe=c6f84d1224) | Feb 24, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [f24e6a55c4](https://linux-hardware.org/?probe=f24e6a55c4) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK U749               | [ba7cdc6018](https://linux-hardware.org/?probe=ba7cdc6018) | Feb 24, 2023 |
| ASUSTek       | X555LA                      | [502020fe52](https://linux-hardware.org/?probe=502020fe52) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| ASUSTek       | X510UQR                     | [075081e4ad](https://linux-hardware.org/?probe=075081e4ad) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Acer          | Aspire E1-531               | [4526585d29](https://linux-hardware.org/?probe=4526585d29) | Feb 24, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [a8fbcbec0e](https://linux-hardware.org/?probe=a8fbcbec0e) | Feb 23, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [cddc383ff9](https://linux-hardware.org/?probe=cddc383ff9) | Feb 23, 2023 |
| Acer          | Aspire SW3-013              | [771b90caaa](https://linux-hardware.org/?probe=771b90caaa) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [dbbcb7502c](https://linux-hardware.org/?probe=dbbcb7502c) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [d620cdcce0](https://linux-hardware.org/?probe=d620cdcce0) | Feb 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [0f5352f94f](https://linux-hardware.org/?probe=0f5352f94f) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| Dell          | Latitude 7300               | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| Acer          | TravelMate P253             | [b99414b6de](https://linux-hardware.org/?probe=b99414b6de) | Feb 23, 2023 |
| HP            | Pavilion g6                 | [c76844f9a1](https://linux-hardware.org/?probe=c76844f9a1) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| ASUSTek       | X555DG                      | [5e7abe271f](https://linux-hardware.org/?probe=5e7abe271f) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [99d4f0df73](https://linux-hardware.org/?probe=99d4f0df73) | Feb 22, 2023 |
| ASUSTek       | X555LA                      | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [71928c5a75](https://linux-hardware.org/?probe=71928c5a75) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [57e007d035](https://linux-hardware.org/?probe=57e007d035) | Feb 22, 2023 |
| HP            | ENVY 17                     | [f705060f1e](https://linux-hardware.org/?probe=f705060f1e) | Feb 22, 2023 |
| HP            | ENVY 17                     | [bf86e7904b](https://linux-hardware.org/?probe=bf86e7904b) | Feb 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [05f20bac2d](https://linux-hardware.org/?probe=05f20bac2d) | Feb 21, 2023 |
| HP            | Pavilion dv6                | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| BESSTAR Te... | X400                        | [f7f9004058](https://linux-hardware.org/?probe=f7f9004058) | Feb 21, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| Unknown       | Unknown                     | [46d473b3e5](https://linux-hardware.org/?probe=46d473b3e5) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [3a525ce932](https://linux-hardware.org/?probe=3a525ce932) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [f845d181ec](https://linux-hardware.org/?probe=f845d181ec) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [ec529ac1bd](https://linux-hardware.org/?probe=ec529ac1bd) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0BY0... | [56c81f1044](https://linux-hardware.org/?probe=56c81f1044) | Feb 20, 2023 |
| HP            | EliteBook 8570w             | [a6fd2ffc5b](https://linux-hardware.org/?probe=a6fd2ffc5b) | Feb 20, 2023 |
| HP            | ProBook 650 G1              | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [51d702d217](https://linux-hardware.org/?probe=51d702d217) | Feb 19, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Dell          | Inspiron 7520               | [1489b9779a](https://linux-hardware.org/?probe=1489b9779a) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [84e519800c](https://linux-hardware.org/?probe=84e519800c) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [2ffc7c4a96](https://linux-hardware.org/?probe=2ffc7c4a96) | Feb 19, 2023 |
| Packard Be... | EasyNote TJ65               | [2c98b99901](https://linux-hardware.org/?probe=2c98b99901) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1104c148d1](https://linux-hardware.org/?probe=1104c148d1) | Feb 19, 2023 |
| Dell          | Latitude 5480               | [e288a18f9d](https://linux-hardware.org/?probe=e288a18f9d) | Feb 18, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [eb9f3822a0](https://linux-hardware.org/?probe=eb9f3822a0) | Feb 18, 2023 |
| HP            | 255 G8 Notebook PC          | [ecf73f400b](https://linux-hardware.org/?probe=ecf73f400b) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | [cadd20aaff](https://linux-hardware.org/?probe=cadd20aaff) | Feb 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [355838f8b2](https://linux-hardware.org/?probe=355838f8b2) | Feb 18, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | [01a17523fa](https://linux-hardware.org/?probe=01a17523fa) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | [6b59c75dec](https://linux-hardware.org/?probe=6b59c75dec) | Feb 18, 2023 |
| Jumper        | EZbook                      | [35f7c6a28a](https://linux-hardware.org/?probe=35f7c6a28a) | Feb 18, 2023 |
| HP            | ENVY 15                     | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [7360e6e667](https://linux-hardware.org/?probe=7360e6e667) | Feb 17, 2023 |
| Dell          | Latitude E6440              | [96e9e43a2e](https://linux-hardware.org/?probe=96e9e43a2e) | Feb 17, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [b29933336d](https://linux-hardware.org/?probe=b29933336d) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [d97ee3d7d1](https://linux-hardware.org/?probe=d97ee3d7d1) | Feb 17, 2023 |
| Acer          | Aspire E5-571G              | [7a47fab9f3](https://linux-hardware.org/?probe=7a47fab9f3) | Feb 17, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e84edd71e7](https://linux-hardware.org/?probe=e84edd71e7) | Feb 17, 2023 |
| HP            | Pavilion 15                 | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| HP            | EliteBook 840 G3            | [f8b182d99b](https://linux-hardware.org/?probe=f8b182d99b) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [85fd62f731](https://linux-hardware.org/?probe=85fd62f731) | Feb 17, 2023 |
| Jumper        | EZbook                      | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [7d6dcd9cd1](https://linux-hardware.org/?probe=7d6dcd9cd1) | Feb 16, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [4b6268364f](https://linux-hardware.org/?probe=4b6268364f) | Feb 16, 2023 |
| Jumper        | EZbook                      | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Acer          | Swift SF314-59              | [fcf01071e5](https://linux-hardware.org/?probe=fcf01071e5) | Feb 15, 2023 |
| HP            | Notebook                    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | [56ee76d678](https://linux-hardware.org/?probe=56ee76d678) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | [1f8387dde4](https://linux-hardware.org/?probe=1f8387dde4) | Feb 15, 2023 |
| ASUSTek       | F6A                         | [3660446fe5](https://linux-hardware.org/?probe=3660446fe5) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [28ac8fee12](https://linux-hardware.org/?probe=28ac8fee12) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| Acer          | Aspire 7250G                | [5f5cec8261](https://linux-hardware.org/?probe=5f5cec8261) | Feb 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a3eb6fde29](https://linux-hardware.org/?probe=a3eb6fde29) | Feb 14, 2023 |
| HP            | ENVY 17                     | [d07a7a99de](https://linux-hardware.org/?probe=d07a7a99de) | Feb 14, 2023 |
| Dell          | XPS 9320                    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| HP            | Laptop 15s-fq4xxx           | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| Acer          | Swift SF114-33              | [14cd72be0e](https://linux-hardware.org/?probe=14cd72be0e) | Feb 13, 2023 |
| MSI           | Prestige 14Evo A11M         | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Unknown       | Unknown                     | [23a611650b](https://linux-hardware.org/?probe=23a611650b) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| HP            | ENVY 15                     | [efc0c8427a](https://linux-hardware.org/?probe=efc0c8427a) | Feb 12, 2023 |
| Lenovo        | ThinkPad L460 20FVS25H01    | [37383d8798](https://linux-hardware.org/?probe=37383d8798) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [c798855263](https://linux-hardware.org/?probe=c798855263) | Feb 12, 2023 |
| HP            | Compaq 6720s                | [4b8e0e10e0](https://linux-hardware.org/?probe=4b8e0e10e0) | Feb 12, 2023 |
| HP            | Compaq 6720s                | [a23186bb63](https://linux-hardware.org/?probe=a23186bb63) | Feb 11, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [404cac8b60](https://linux-hardware.org/?probe=404cac8b60) | Feb 11, 2023 |
| Dell          | Vostro 15 3510              | [8291db193a](https://linux-hardware.org/?probe=8291db193a) | Feb 11, 2023 |
| HP            | Notebook                    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| HP            | ZBook 17 G3                 | [f0dff8ed53](https://linux-hardware.org/?probe=f0dff8ed53) | Feb 11, 2023 |
| HP            | Notebook                    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Dell          | XPS 15 9500                 | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| MSI           | Prestige 15 A11SCX          | [a82372e461](https://linux-hardware.org/?probe=a82372e461) | Feb 10, 2023 |
| HP            | Notebook                    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| HP            | ZBook 17 G3                 | [bd09c6036f](https://linux-hardware.org/?probe=bd09c6036f) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fd8d478a5b](https://linux-hardware.org/?probe=fd8d478a5b) | Feb 10, 2023 |
| Lenovo        | Yoga Slim 7 13ITL5 82CU     | [7f4c6d1757](https://linux-hardware.org/?probe=7f4c6d1757) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| HP            | 255 G4                      | [00870a3da9](https://linux-hardware.org/?probe=00870a3da9) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08f3d3b7d8](https://linux-hardware.org/?probe=08f3d3b7d8) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0cb6963914](https://linux-hardware.org/?probe=0cb6963914) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ce86509b6](https://linux-hardware.org/?probe=5ce86509b6) | Feb 08, 2023 |
| Dell          | XPS 17 9720                 | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Google        | Grunt                       | [84ecb8aaf1](https://linux-hardware.org/?probe=84ecb8aaf1) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| HP            | ENVY 15                     | [641ce1347d](https://linux-hardware.org/?probe=641ce1347d) | Feb 08, 2023 |
| Acer          | Aspire E5-553               | [5e951ad06d](https://linux-hardware.org/?probe=5e951ad06d) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [0713732442](https://linux-hardware.org/?probe=0713732442) | Feb 07, 2023 |
| Google        | Grunt                       | [1bbc4ae776](https://linux-hardware.org/?probe=1bbc4ae776) | Feb 07, 2023 |
| Lenovo        | ThinkPad T430 2347G7G       | [925017105d](https://linux-hardware.org/?probe=925017105d) | Feb 07, 2023 |
| HUAWEI        | MACH-WX9                    | [263101d492](https://linux-hardware.org/?probe=263101d492) | Feb 07, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [b7ab00ddb1](https://linux-hardware.org/?probe=b7ab00ddb1) | Feb 07, 2023 |
| MSI           | U90/U100                    | [f7dc915782](https://linux-hardware.org/?probe=f7dc915782) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | X550JF                      | [c8f1b71cfd](https://linux-hardware.org/?probe=c8f1b71cfd) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0edeee4ba6](https://linux-hardware.org/?probe=0edeee4ba6) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| Acer          | Extensa 5635                | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [762c097b3e](https://linux-hardware.org/?probe=762c097b3e) | Feb 06, 2023 |
| Intel         | Unknown                     | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Lenovo        | Flex 2-14D 20376            | [16f0d33c85](https://linux-hardware.org/?probe=16f0d33c85) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Valve         | Jupiter                     | [8a1998f130](https://linux-hardware.org/?probe=8a1998f130) | Feb 05, 2023 |
| Dell          | Latitude 7380               | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| ASUSTek       | N55SF                       | [5b81cbed5f](https://linux-hardware.org/?probe=5b81cbed5f) | Feb 05, 2023 |
| Acer          | One S1002                   | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [30676c5e14](https://linux-hardware.org/?probe=30676c5e14) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08bf9ddbcf](https://linux-hardware.org/?probe=08bf9ddbcf) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| HP            | 255 G3                      | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| Acer          | Aspire E5-573G              | [b7760210a8](https://linux-hardware.org/?probe=b7760210a8) | Feb 05, 2023 |
| Notebook      | W25CSW                      | [b63184cd07](https://linux-hardware.org/?probe=b63184cd07) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| Acer          | TravelMate P253             | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| SiComputer    | Nauta 01C                   | [1579a837f7](https://linux-hardware.org/?probe=1579a837f7) | Feb 04, 2023 |
| Microtech     | CoreBook                    | [2ee0649a6e](https://linux-hardware.org/?probe=2ee0649a6e) | Feb 03, 2023 |
| Toshiba       | Satellite Pro S500          | [9274080d89](https://linux-hardware.org/?probe=9274080d89) | Feb 03, 2023 |
| HP            | ProBook 440 G7              | [f9a4f80656](https://linux-hardware.org/?probe=f9a4f80656) | Feb 03, 2023 |
| Intel         | Unknown                     | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Acer          | Aspire F5-573G              | [ba43497e32](https://linux-hardware.org/?probe=ba43497e32) | Feb 02, 2023 |
| HP            | 250 G6 Notebook PC          | [a0b5d1c73c](https://linux-hardware.org/?probe=a0b5d1c73c) | Feb 02, 2023 |
| ASUSTek       | K54L                        | [8568b17267](https://linux-hardware.org/?probe=8568b17267) | Feb 02, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 474       | 10.35%  |
| Ubuntu 18.04        | 294       | 6.42%   |
| Ubuntu 22.04        | 279       | 6.09%   |
| Arch Rolling        | 146       | 3.19%   |
| Debian 11           | 109       | 2.38%   |
| OpenMandriva 4.2    | 108       | 2.36%   |
| OpenMandriva 4.3    | 101       | 2.21%   |
| Fedora 36           | 93        | 2.03%   |
| Linux Mint 21.1     | 82        | 1.79%   |
| Pop!_OS 22.04       | 75        | 1.64%   |
| Arch                | 75        | 1.64%   |
| Fedora 37           | 73        | 1.59%   |
| Ubuntu 22.10        | 70        | 1.53%   |
| Xubuntu 18.04       | 69        | 1.51%   |
| Ubuntu 19.10        | 68        | 1.48%   |
| Zorin 16            | 67        | 1.46%   |
| Xubuntu 20.04       | 62        | 1.35%   |
| Ubuntu 20.10        | 61        | 1.33%   |
| Linux Mint 20.3     | 60        | 1.31%   |
| Ubuntu 21.10        | 58        | 1.27%   |
| EndeavourOS Rolling | 57        | 1.24%   |
| Ubuntu 19.04        | 56        | 1.22%   |
| OpenMandriva 23.03  | 56        | 1.22%   |
| KDE neon 20.04      | 54        | 1.18%   |
| Linux Mint 21       | 53        | 1.16%   |
| Zorin 15            | 49        | 1.07%   |
| Debian 10           | 46        | 1%      |
| Fedora 35           | 42        | 0.92%   |
| Ubuntu 18.10        | 40        | 0.87%   |
| Kubuntu 22.04       | 40        | 0.87%   |
| Ubuntu 21.04        | 39        | 0.85%   |
| OpenMandriva 23.01  | 39        | 0.85%   |
| Fedora 38           | 38        | 0.83%   |
| Linux Mint 20.1     | 36        | 0.79%   |
| Pop!_OS 20.10       | 35        | 0.76%   |
| Linux Mint 20.2     | 35        | 0.76%   |
| Linux Mint 20       | 35        | 0.76%   |
| Linux Mint 19.3     | 35        | 0.76%   |
| Kubuntu 20.04       | 35        | 0.76%   |
| Fedora 33           | 35        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1410      | 32.65%  |
| Linux Mint    | 336       | 7.78%   |
| Fedora        | 328       | 7.59%   |
| OpenMandriva  | 319       | 7.39%   |
| Arch          | 215       | 4.98%   |
| Debian        | 198       | 4.58%   |
| Xubuntu       | 187       | 4.33%   |
| Pop!_OS       | 166       | 3.84%   |
| Manjaro       | 128       | 2.96%   |
| Zorin         | 122       | 2.82%   |
| Kubuntu       | 120       | 2.78%   |
| ROSA          | 88        | 2.04%   |
| KDE neon      | 76        | 1.76%   |
| Lubuntu       | 63        | 1.46%   |
| EndeavourOS   | 59        | 1.37%   |
| openSUSE      | 53        | 1.23%   |
| Elementary    | 41        | 0.95%   |
| Ubuntu MATE   | 39        | 0.9%    |
| Endless       | 38        | 0.88%   |
| ArcoLinux     | 27        | 0.63%   |
| LMDE          | 23        | 0.53%   |
| Gentoo        | 22        | 0.51%   |
| Ubuntu Unity  | 21        | 0.49%   |
| MX            | 21        | 0.49%   |
| BlackPanther  | 20        | 0.46%   |
| Kali          | 18        | 0.42%   |
| Ubuntu Budgie | 16        | 0.37%   |
| Clear Linux   | 16        | 0.37%   |
| SteamOS       | 14        | 0.32%   |
| Garuda Linux  | 14        | 0.32%   |
| Peppermint    | 11        | 0.25%   |
| Parrot        | 10        | 0.23%   |
| Nobara        | 7         | 0.16%   |
| LinuxFX       | 7         | 0.16%   |
| NixOS         | 5         | 0.12%   |
| Chrome OS     | 5         | 0.12%   |
| Xero          | 4         | 0.09%   |
| Slackware     | 4         | 0.09%   |
| Linux Lite    | 4         | 0.09%   |
| CentOS        | 4         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 103       | 2.04%   |
| 5.15.0-52-generic        | 98        | 1.94%   |
| 5.16.7-desktop-1omv4003  | 96        | 1.9%    |
| 5.4.0-42-generic         | 68        | 1.35%   |
| 5.15.0-56-generic        | 63        | 1.25%   |
| 6.2.6-desktop-1omv2390   | 55        | 1.09%   |
| 5.15.0-58-generic        | 43        | 0.85%   |
| 5.4.0-26-generic         | 41        | 0.81%   |
| 5.15.0-46-generic        | 41        | 0.81%   |
| 5.3.0-46-generic         | 40        | 0.79%   |
| 5.4.0-52-generic         | 36        | 0.71%   |
| 5.4.0-29-generic         | 36        | 0.71%   |
| 5.15.0-47-generic        | 35        | 0.69%   |
| 6.1.1-desktop-1omv2290   | 33        | 0.65%   |
| 5.4.0-58-generic         | 33        | 0.65%   |
| 5.15.0-43-generic        | 33        | 0.65%   |
| 5.3.0-40-generic         | 32        | 0.63%   |
| 5.3.0-42-generic         | 31        | 0.61%   |
| 5.4.0-48-generic         | 30        | 0.59%   |
| 5.15.0-41-generic        | 30        | 0.59%   |
| 6.0.2-arch1-1            | 28        | 0.55%   |
| 5.15.0-53-generic        | 27        | 0.53%   |
| 5.13.0-28-generic        | 27        | 0.53%   |
| 5.0.0-37-generic         | 27        | 0.53%   |
| 5.19.0-32-generic        | 26        | 0.51%   |
| 5.15.0-48-generic        | 25        | 0.49%   |
| 5.10.0-19-amd64          | 24        | 0.47%   |
| 5.3.0-51-generic         | 23        | 0.46%   |
| 5.19.0-23-generic        | 23        | 0.46%   |
| 5.19.0-21-generic        | 23        | 0.46%   |
| 5.15.0-60-generic        | 23        | 0.46%   |
| 5.10.0-21-amd64          | 23        | 0.46%   |
| 5.4.0-54-generic         | 22        | 0.44%   |
| 5.4.0-47-generic         | 22        | 0.44%   |
| 5.4.0-28-generic         | 22        | 0.44%   |
| 6.2.0-20-generic         | 21        | 0.42%   |
| 5.15.0-50-generic        | 21        | 0.42%   |
| 4.18.0-15-generic        | 21        | 0.42%   |
| 5.4.0-33-generic         | 20        | 0.4%    |
| 5.19.0-76051900-generic  | 20        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 691       | 14.62%  |
| 5.15.0  | 516       | 10.92%  |
| 4.15.0  | 243       | 5.14%   |
| 5.19.0  | 228       | 4.82%   |
| 5.3.0   | 224       | 4.74%   |
| 5.8.0   | 201       | 4.25%   |
| 5.13.0  | 199       | 4.21%   |
| 5.11.0  | 168       | 3.55%   |
| 5.10.0  | 146       | 3.09%   |
| 5.0.0   | 113       | 2.39%   |
| 5.10.14 | 103       | 2.18%   |
| 5.16.7  | 98        | 2.07%   |
| 4.18.0  | 87        | 1.84%   |
| 6.2.6   | 72        | 1.52%   |
| 6.0.2   | 53        | 1.12%   |
| 4.19.0  | 45        | 0.95%   |
| 6.2.0   | 44        | 0.93%   |
| 6.1.1   | 40        | 0.85%   |
| 6.1.0   | 29        | 0.61%   |
| 5.19.16 | 29        | 0.61%   |
| 6.0.0   | 27        | 0.57%   |
| 6.0.12  | 22        | 0.47%   |
| 5.17.5  | 20        | 0.42%   |
| 4.18.16 | 19        | 0.4%    |
| 6.0.7   | 18        | 0.38%   |
| 6.0.6   | 18        | 0.38%   |
| 4.9.60  | 18        | 0.38%   |
| 4.9.20  | 17        | 0.36%   |
| 4.4.0   | 17        | 0.36%   |
| 5.17.1  | 14        | 0.3%    |
| 6.0.5   | 13        | 0.28%   |
| 6.2.9   | 12        | 0.25%   |
| 6.1.8   | 12        | 0.25%   |
| 6.0.9   | 12        | 0.25%   |
| 5.18.0  | 12        | 0.25%   |
| 6.0.10  | 11        | 0.23%   |
| 5.19.12 | 11        | 0.23%   |
| 5.14.0  | 11        | 0.23%   |
| 6.3.5   | 10        | 0.21%   |
| 6.2.15  | 10        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 737       | 15.78%  |
| 5.15    | 605       | 12.96%  |
| 5.19    | 333       | 7.13%   |
| 5.10    | 306       | 6.55%   |
| 5.3     | 249       | 5.33%   |
| 4.15    | 244       | 5.22%   |
| 5.8     | 241       | 5.16%   |
| 5.13    | 220       | 4.71%   |
| 6.0     | 206       | 4.41%   |
| 5.11    | 205       | 4.39%   |
| 6.2     | 184       | 3.94%   |
| 6.1     | 157       | 3.36%   |
| 5.16    | 150       | 3.21%   |
| 5.0     | 116       | 2.48%   |
| 4.18    | 109       | 2.33%   |
| 5.17    | 65        | 1.39%   |
| 4.9     | 62        | 1.33%   |
| 4.19    | 58        | 1.24%   |
| 5.14    | 57        | 1.22%   |
| 5.18    | 54        | 1.16%   |
| 6.3     | 53        | 1.13%   |
| 5.9     | 46        | 0.99%   |
| 5.12    | 37        | 0.79%   |
| 5.6     | 34        | 0.73%   |
| 5.5     | 34        | 0.73%   |
| 6.4     | 26        | 0.56%   |
| 5.7     | 23        | 0.49%   |
| 4.4     | 18        | 0.39%   |
| 5.2     | 9         | 0.19%   |
| 4.13    | 6         | 0.13%   |
| 4.1     | 6         | 0.13%   |
| 5.1     | 4         | 0.09%   |
| 4.12    | 4         | 0.09%   |
| 4.20    | 3         | 0.06%   |
| 4.17    | 3         | 0.06%   |
| 4.16    | 2         | 0.04%   |
| 3.10    | 2         | 0.04%   |
| 4.14    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3931      | 94.84%  |
| i686   | 213       | 5.14%   |
| armv7l | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1903      | 43.85%  |
| KDE5              | 825       | 19.01%  |
| Unknown           | 408       | 9.4%    |
| XFCE              | 400       | 9.22%   |
| X-Cinnamon        | 270       | 6.22%   |
| MATE              | 115       | 2.65%   |
| LXQt              | 72        | 1.66%   |
| KDE               | 69        | 1.59%   |
| KDE4              | 50        | 1.15%   |
| Pantheon          | 41        | 0.94%   |
| Cinnamon          | 30        | 0.69%   |
| LXDE              | 27        | 0.62%   |
| Unity             | 23        | 0.53%   |
| Budgie            | 23        | 0.53%   |
| i3                | 16        | 0.37%   |
| GNOME Flashback   | 15        | 0.35%   |
| GNOME Classic     | 8         | 0.18%   |
| sway              | 6         | 0.14%   |
| Deepin            | 6         | 0.14%   |
| bspwm             | 5         | 0.12%   |
| Hyprland          | 4         | 0.09%   |
| DWM               | 4         | 0.09%   |
| xubuntu           | 2         | 0.05%   |
| qtile             | 2         | 0.05%   |
| openbox           | 2         | 0.05%   |
| Enlightenment     | 2         | 0.05%   |
| awesome           | 2         | 0.05%   |
| ubuntu:pika:GNOME | 1         | 0.02%   |
| ubuntu            | 1         | 0.02%   |
| Trinity           | 1         | 0.02%   |
| pika:GNOME        | 1         | 0.02%   |
| none+i3           | 1         | 0.02%   |
| none+bspwm        | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| icewm             | 1         | 0.02%   |
| gamescope         | 1         | 0.02%   |
| Cutefish          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3211      | 74.85%  |
| Wayland | 827       | 19.28%  |
| Unknown | 210       | 4.9%    |
| Tty     | 42        | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1850      | 42.72%  |
| SDDM    | 773       | 17.85%  |
| GDM3    | 560       | 12.93%  |
| GDM     | 520       | 12.01%  |
| LightDM | 462       | 10.67%  |
| TDM     | 95        | 2.19%   |
| KDM     | 51        | 1.18%   |
| XDM     | 6         | 0.14%   |
| SLiM    | 6         | 0.14%   |
| LXDM    | 3         | 0.07%   |
| WDM     | 1         | 0.02%   |
| SLIMSKI | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| Ly      | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| it_IT        | 2642      | 61.86%  |
| en_US        | 932       | 21.82%  |
| Unknown      | 434       | 10.16%  |
| en_GB        | 103       | 2.41%   |
| C            | 81        | 1.9%    |
| de_DE        | 14        | 0.33%   |
| fr_FR        | 9         | 0.21%   |
| es_ES        | 8         | 0.19%   |
| de_IT        | 8         | 0.19%   |
| ru_RU        | 5         | 0.12%   |
| POSIX        | 5         | 0.12%   |
| en_AG        | 4         | 0.09%   |
| it_IT@euro   | 3         | 0.07%   |
| en_AU        | 3         | 0.07%   |
| en_US.UTF8   | 2         | 0.05%   |
| en_IE        | 2         | 0.05%   |
| ro_RO        | 1         | 0.02%   |
| pt_BR        | 1         | 0.02%   |
| pl_PL        | 1         | 0.02%   |
| it_IT.UTF -8 | 1         | 0.02%   |
| it_CH        | 1         | 0.02%   |
| fur_IT       | 1         | 0.02%   |
| fr_BE        | 1         | 0.02%   |
| es_US        | 1         | 0.02%   |
| en_US@euro   | 1         | 0.02%   |
| en_US.utf-8  | 1         | 0.02%   |
| en_IN        | 1         | 0.02%   |
| en_DK        | 1         | 0.02%   |
| de_CH        | 1         | 0.02%   |
| de_AT        | 1         | 0.02%   |
| C.UTF8       | 1         | 0.02%   |
| bg_BG        | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2250      | 53.19%  |
| BIOS | 1980      | 46.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3208      | 75.23%  |
| Overlay  | 409       | 9.59%   |
| Btrfs    | 387       | 9.08%   |
| Unknown  | 103       | 2.42%   |
| Tmpfs    | 69        | 1.62%   |
| Xfs      | 33        | 0.77%   |
| Zfs      | 26        | 0.61%   |
| Ext2     | 12        | 0.28%   |
| F2fs     | 8         | 0.19%   |
| Ext3     | 5         | 0.12%   |
| XXX4     | 2         | 0.05%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2016      | 47.37%  |
| GPT     | 1786      | 41.96%  |
| MBR     | 454       | 10.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3694      | 87.58%  |
| Yes       | 524       | 12.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2811      | 66.47%  |
| Yes       | 1418      | 33.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 943       | 22.77%  |
| Lenovo              | 674       | 16.28%  |
| ASUSTek Computer    | 626       | 15.12%  |
| Acer                | 468       | 11.3%   |
| Dell                | 433       | 10.46%  |
| Toshiba             | 105       | 2.54%   |
| HUAWEI              | 105       | 2.54%   |
| Apple               | 102       | 2.46%   |
| Sony                | 91        | 2.2%    |
| MSI                 | 87        | 2.1%    |
| Samsung Electronics | 73        | 1.76%   |
| Fujitsu             | 40        | 0.97%   |
| Unknown             | 35        | 0.85%   |
| Mediacom            | 33        | 0.8%    |
| Packard Bell        | 31        | 0.75%   |
| Notebook            | 22        | 0.53%   |
| Chuwi               | 22        | 0.53%   |
| Teclast             | 21        | 0.51%   |
| Fujitsu Siemens     | 19        | 0.46%   |
| Timi                | 18        | 0.43%   |
| Microtech           | 17        | 0.41%   |
| TUXEDO              | 14        | 0.34%   |
| PC Specialist       | 13        | 0.31%   |
| Valve               | 12        | 0.29%   |
| SANTECH             | 9         | 0.22%   |
| Jumper              | 9         | 0.22%   |
| Google              | 8         | 0.19%   |
| TrekStor            | 7         | 0.17%   |
| Olivetti            | 7         | 0.17%   |
| eMachines           | 7         | 0.17%   |
| LG Electronics      | 5         | 0.12%   |
| Alienware           | 5         | 0.12%   |
| SiComputer          | 4         | 0.1%    |
| YASHI               | 3         | 0.07%   |
| TELECOMITALIA       | 3         | 0.07%   |
| System76            | 3         | 0.07%   |
| Razer               | 3         | 0.07%   |
| Onda TLC            | 3         | 0.07%   |
| Olidata             | 3         | 0.07%   |
| Intel               | 3         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Pavilion dv6                       | 55        | 1.33%   |
| Unknown                               | 50        | 1.21%   |
| HP Notebook                           | 41        | 0.99%   |
| HP Pavilion 15                        | 28        | 0.68%   |
| HP Pavilion g6                        | 23        | 0.56%   |
| HP 255 G8 Notebook PC                 | 22        | 0.53%   |
| HUAWEI NBLK-WAX9X                     | 19        | 0.46%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 17        | 0.41%   |
| HP 15                                 | 15        | 0.36%   |
| Dell XPS 15 7590                      | 14        | 0.34%   |
| HP ENVY 15                            | 13        | 0.31%   |
| HP 255 G7 Notebook PC                 | 13        | 0.31%   |
| Valve Jupiter                         | 12        | 0.29%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 12        | 0.29%   |
| HUAWEI KLVL-WXX9                      | 12        | 0.29%   |
| HP G62                                | 12        | 0.29%   |
| HP 250 G6 Notebook PC                 | 12        | 0.29%   |
| Apple MacBook4,1                      | 12        | 0.29%   |
| Lenovo IdeaPad 330S-15IKB 81F5        | 11        | 0.27%   |
| HP Pavilion x2 Detachable             | 11        | 0.27%   |
| HP 255 G6 Notebook PC                 | 11        | 0.27%   |
| Dell XPS 15 9570                      | 11        | 0.27%   |
| Acer Aspire 5750G                     | 11        | 0.27%   |
| HP Pavilion dv7                       | 10        | 0.24%   |
| Dell XPS 15 9560                      | 10        | 0.24%   |
| Acer Aspire 5920G                     | 10        | 0.24%   |
| Jumper EZbook                         | 9         | 0.22%   |
| HUAWEI BOD-WXX9                       | 9         | 0.22%   |
| HP Laptop 15s-eq2xxx                  | 9         | 0.22%   |
| HP EliteBook 8440p                    | 9         | 0.22%   |
| HP Compaq 6730s                       | 9         | 0.22%   |
| HP 250 G3                             | 9         | 0.22%   |
| Dell Inspiron 5570                    | 9         | 0.22%   |
| Acer Aspire A515-51G                  | 9         | 0.22%   |
| Acer Aspire A515-45                   | 9         | 0.22%   |
| Microtech ebookPro                    | 8         | 0.19%   |
| Lenovo V145-15AST 81MT                | 8         | 0.19%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 8         | 0.19%   |
| HUAWEI BOHB-WAX9                      | 8         | 0.19%   |
| HP ProBook 450 G5                     | 8         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 321       | 7.75%   |
| Acer Aspire           | 313       | 7.56%   |
| HP Pavilion           | 251       | 6.06%   |
| Lenovo IdeaPad        | 175       | 4.23%   |
| Dell Latitude         | 165       | 3.98%   |
| HP EliteBook          | 109       | 2.63%   |
| Dell XPS              | 101       | 2.44%   |
| ASUS VivoBook         | 95        | 2.29%   |
| Toshiba Satellite     | 90        | 2.17%   |
| HP Laptop             | 90        | 2.17%   |
| HP ProBook            | 87        | 2.1%    |
| Dell Inspiron         | 79        | 1.91%   |
| HP Compaq             | 69        | 1.67%   |
| HP 255                | 64        | 1.55%   |
| HP 250                | 56        | 1.35%   |
| Unknown               | 50        | 1.21%   |
| HP Notebook           | 41        | 0.99%   |
| Fujitsu LIFEBOOK      | 38        | 0.92%   |
| Acer Swift            | 37        | 0.89%   |
| Acer TravelMate       | 36        | 0.87%   |
| Dell Precision        | 35        | 0.85%   |
| Acer Extensa          | 33        | 0.8%    |
| Dell Vostro           | 32        | 0.77%   |
| Lenovo ThinkBook      | 29        | 0.7%    |
| Packard Bell EasyNote | 24        | 0.58%   |
| HP ENVY               | 24        | 0.58%   |
| Mediacom SmartBook    | 21        | 0.51%   |
| ASUS ROG              | 20        | 0.48%   |
| HUAWEI NBLK-WAX9X     | 19        | 0.46%   |
| Apple MacBookPro11    | 18        | 0.43%   |
| MSI Modern            | 16        | 0.39%   |
| HP ZBook              | 15        | 0.36%   |
| HP Presario           | 15        | 0.36%   |
| HP OMEN               | 15        | 0.36%   |
| HP 15                 | 15        | 0.36%   |
| ASUS Zenbook          | 14        | 0.34%   |
| Lenovo Legion         | 13        | 0.31%   |
| Acer Nitro            | 13        | 0.31%   |
| Valve Jupiter         | 12        | 0.29%   |
| MSI Prestige          | 12        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 361       | 8.72%   |
| 2019    | 355       | 8.57%   |
| 2021    | 339       | 8.19%   |
| 2018    | 324       | 7.82%   |
| 2013    | 281       | 6.79%   |
| 2017    | 275       | 6.64%   |
| 2016    | 246       | 5.94%   |
| 2011    | 245       | 5.92%   |
| 2012    | 243       | 5.87%   |
| 2008    | 243       | 5.87%   |
| 2010    | 236       | 5.7%    |
| 2015    | 235       | 5.67%   |
| 2014    | 227       | 5.48%   |
| 2009    | 188       | 4.54%   |
| 2007    | 124       | 2.99%   |
| 2022    | 113       | 2.73%   |
| 2006    | 64        | 1.55%   |
| 2005    | 23        | 0.56%   |
| 2023    | 9         | 0.22%   |
| Unknown | 6         | 0.14%   |
| 2004    | 3         | 0.07%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4141      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3769      | 89.93%  |
| Enabled  | 422       | 10.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4125      | 99.61%  |
| Yes  | 16        | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1180      | 28.13%  |
| 3.01-4.0    | 1033      | 24.62%  |
| 16.01-24.0  | 673       | 16.04%  |
| 8.01-16.0   | 656       | 15.64%  |
| 1.01-2.0    | 267       | 6.36%   |
| 32.01-64.0  | 197       | 4.7%    |
| 2.01-3.0    | 90        | 2.15%   |
| 0.51-1.0    | 45        | 1.07%   |
| 24.01-32.0  | 29        | 0.69%   |
| 64.01-256.0 | 22        | 0.52%   |
| 0.01-0.5    | 3         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1751      | 37.97%  |
| 2.01-3.0   | 1130      | 24.5%   |
| 4.01-8.0   | 590       | 12.79%  |
| 3.01-4.0   | 562       | 12.19%  |
| 0.51-1.0   | 372       | 8.07%   |
| 8.01-16.0  | 146       | 3.17%   |
| 0.01-0.5   | 47        | 1.02%   |
| 16.01-24.0 | 10        | 0.22%   |
| 24.01-32.0 | 2         | 0.04%   |
| 32.01-64.0 | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3161      | 74.92%  |
| 2      | 914       | 21.66%  |
| 3      | 95        | 2.25%   |
| 0      | 34        | 0.81%   |
| 4      | 11        | 0.26%   |
| 6      | 2         | 0.05%   |
| 5      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2406      | 57.85%  |
| Yes       | 1753      | 42.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3296      | 79.25%  |
| No        | 863       | 20.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4055      | 97.83%  |
| No        | 90        | 2.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3058      | 72.84%  |
| No        | 1140      | 27.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 4141      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Milan               | 637       | 13.48%  |
| Rome                | 478       | 10.11%  |
| Turin               | 158       | 3.34%   |
| Florence            | 87        | 1.84%   |
| Naples              | 83        | 1.76%   |
| Bologna             | 80        | 1.69%   |
| Rho                 | 75        | 1.59%   |
| Genoa               | 64        | 1.35%   |
| Padova              | 58        | 1.23%   |
| Milano              | 54        | 1.14%   |
| Palermo             | 52        | 1.1%    |
| Verona              | 48        | 1.02%   |
| Bari                | 46        | 0.97%   |
| Catania             | 42        | 0.89%   |
| Brescia             | 35        | 0.74%   |
| Trieste             | 32        | 0.68%   |
| Parma               | 32        | 0.68%   |
| Venice              | 28        | 0.59%   |
| Pisa                | 28        | 0.59%   |
| Bergamo             | 28        | 0.59%   |
| Modena              | 22        | 0.47%   |
| Bolzano             | 22        | 0.47%   |
| Casalecchio di Reno | 21        | 0.44%   |
| Trento              | 20        | 0.42%   |
| Monza               | 20        | 0.42%   |
| Reggio Emilia       | 19        | 0.4%    |
| Perugia             | 19        | 0.4%    |
| Cagliari            | 19        | 0.4%    |
| Seregno             | 18        | 0.38%   |
| Sesto San Giovanni  | 17        | 0.36%   |
| Salerno             | 17        | 0.36%   |
| Udine               | 16        | 0.34%   |
| Vicenza             | 15        | 0.32%   |
| Taranto             | 15        | 0.32%   |
| Reggio Calabria     | 15        | 0.32%   |
| Pescara             | 15        | 0.32%   |
| Mestre              | 13        | 0.28%   |
| Legnano             | 13        | 0.28%   |
| Forlì              | 13        | 0.28%   |
| Rimini              | 12        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 912       | 1222   | 17.93%  |
| WDC                         | 492       | 616    | 9.67%   |
| Seagate                     | 468       | 568    | 9.2%    |
| Toshiba                     | 338       | 437    | 6.65%   |
| SanDisk                     | 316       | 424    | 6.21%   |
| Unknown                     | 314       | 425    | 6.17%   |
| Kingston                    | 297       | 350    | 5.84%   |
| Crucial                     | 290       | 342    | 5.7%    |
| Hitachi                     | 230       | 280    | 4.52%   |
| SK hynix                    | 194       | 240    | 3.81%   |
| HGST                        | 181       | 237    | 3.56%   |
| Micron Technology           | 134       | 167    | 2.63%   |
| Intel                       | 122       | 156    | 2.4%    |
| KIOXIA                      | 62        | 75     | 1.22%   |
| Fujitsu                     | 46        | 54     | 0.9%    |
| China                       | 42        | 48     | 0.83%   |
| Phison                      | 41        | 49     | 0.81%   |
| Apple                       | 35        | 38     | 0.69%   |
| SPCC                        | 30        | 37     | 0.59%   |
| LITEON                      | 28        | 36     | 0.55%   |
| Intenso                     | 25        | 26     | 0.49%   |
| Transcend                   | 24        | 31     | 0.47%   |
| JMicron Technology          | 22        | 25     | 0.43%   |
| Phison Electronics          | 20        | 25     | 0.39%   |
| A-DATA Technology           | 19        | 23     | 0.37%   |
| Netac                       | 18        | 19     | 0.35%   |
| Teclast                     | 17        | 22     | 0.33%   |
| Kingston Technology Company | 17        | 19     | 0.33%   |
| Unknown                     | 17        | 23     | 0.33%   |
| KingDian                    | 15        | 20     | 0.29%   |
| PNY                         | 13        | 15     | 0.26%   |
| Micron/Crucial Technology   | 13        | 18     | 0.26%   |
| SABRENT                     | 12        | 12     | 0.24%   |
| Silicon Motion              | 11        | 15     | 0.22%   |
| Drevo                       | 11        | 12     | 0.22%   |
| SSSTC                       | 9         | 9      | 0.18%   |
| Patriot                     | 9         | 13     | 0.18%   |
| LITEONIT                    | 9         | 20     | 0.18%   |
| Microtech                   | 8         | 18     | 0.16%   |
| Lenovo                      | 8         | 8      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 80        | 1.52%   |
| Crucial CT500MX500SSD1 500GB                        | 72        | 1.36%   |
| Unknown MMC Card  32GB                              | 67        | 1.27%   |
| Samsung SSD 860 EVO 500GB                           | 64        | 1.21%   |
| Toshiba MQ01ABF050 500GB                            | 61        | 1.16%   |
| HGST HTS545050A7E680 500GB                          | 51        | 0.97%   |
| Seagate ST500LT012-1DG142 500GB                     | 50        | 0.95%   |
| Samsung SSD 850 EVO 250GB                           | 50        | 0.95%   |
| Seagate ST1000LM035-1RK172 1TB                      | 47        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 47        | 0.89%   |
| HGST HTS721010A9E630 1TB                            | 46        | 0.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 42        | 0.8%    |
| Samsung SSD 850 EVO 500GB                           | 41        | 0.78%   |
| Unknown MMC Card  64GB                              | 38        | 0.72%   |
| Crucial CT240BX500SSD1 240GB                        | 37        | 0.7%    |
| Kingston SA400S37480G 480GB SSD                     | 34        | 0.64%   |
| Samsung NVMe SSD Drive 512GB                        | 32        | 0.61%   |
| Toshiba MQ01ABD100 1TB                              | 30        | 0.57%   |
| Toshiba MQ04ABF100 1TB                              | 28        | 0.53%   |
| Seagate ST9500325AS 500GB                           | 28        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB                        | 28        | 0.53%   |
| Crucial CT480BX500SSD1 480GB                        | 28        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                         | 26        | 0.49%   |
| SanDisk SSD PLUS 240GB                              | 25        | 0.47%   |
| Samsung SSD 860 EVO 250GB                           | 25        | 0.47%   |
| Samsung SSD 860 EVO 1TB                             | 24        | 0.45%   |
| Samsung NVMe SSD Drive 256GB                        | 22        | 0.42%   |
| Unknown MMC Card  128GB                             | 21        | 0.4%    |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.4%    |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.4%    |
| Hitachi HTS545050A7E380 500GB                       | 21        | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB                        | 20        | 0.38%   |
| Unknown NCard  32GB                                 | 20        | 0.38%   |
| HGST HTS541010A9E680 1TB                            | 20        | 0.38%   |
| SK hynix NVMe SSD Drive 512GB                       | 19        | 0.36%   |
| Seagate M3 Portable 1TB                             | 19        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD                    | 19        | 0.36%   |
| Hitachi HTS545050B9A300 500GB                       | 19        | 0.36%   |
| Samsung SSD 840 EVO 250GB                           | 18        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 18        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 446       | 536    | 28.3%   |
| WDC                 | 342       | 431    | 21.7%   |
| Toshiba             | 235       | 283    | 14.91%  |
| Hitachi             | 230       | 280    | 14.59%  |
| HGST                | 181       | 237    | 11.48%  |
| Fujitsu             | 46        | 54     | 2.92%   |
| Samsung Electronics | 42        | 53     | 2.66%   |
| Unknown             | 19        | 20     | 1.21%   |
| JMicron Technology  | 11        | 12     | 0.7%    |
| External            | 5         | 6      | 0.32%   |
| ASMT                | 5         | 6      | 0.32%   |
| SSK                 | 2         | 2      | 0.13%   |
| IBM/Hitachi         | 2         | 3      | 0.13%   |
| HGST HTS            | 2         | 2      | 0.13%   |
| USB3.0              | 1         | 1      | 0.06%   |
| StoreJet            | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| Generic-            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |
| Apple               | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 460       | 600    | 26.45%  |
| Crucial             | 271       | 322    | 15.58%  |
| Kingston            | 225       | 263    | 12.94%  |
| SanDisk             | 174       | 223    | 10.01%  |
| Micron Technology   | 56        | 72     | 3.22%   |
| WDC                 | 48        | 62     | 2.76%   |
| SK hynix            | 47        | 52     | 2.7%    |
| China               | 41        | 47     | 2.36%   |
| Toshiba             | 27        | 42     | 1.55%   |
| Apple               | 27        | 29     | 1.55%   |
| SPCC                | 26        | 32     | 1.5%    |
| Transcend           | 24        | 31     | 1.38%   |
| LITEON              | 24        | 27     | 1.38%   |
| Intel               | 24        | 29     | 1.38%   |
| Intenso             | 21        | 21     | 1.21%   |
| Teclast             | 17        | 22     | 0.98%   |
| Netac               | 17        | 18     | 0.98%   |
| KingDian            | 15        | 20     | 0.86%   |
| A-DATA Technology   | 14        | 16     | 0.81%   |
| PNY                 | 12        | 13     | 0.69%   |
| Drevo               | 11        | 12     | 0.63%   |
| Patriot             | 9         | 13     | 0.52%   |
| LITEONIT            | 9         | 20     | 0.52%   |
| Unknown             | 9         | 15     | 0.52%   |
| Microtech           | 8         | 18     | 0.46%   |
| Corsair             | 8         | 9      | 0.46%   |
| GOODRAM             | 7         | 8      | 0.4%    |
| Dogfish             | 7         | 8      | 0.4%    |
| Verbatim            | 5         | 10     | 0.29%   |
| TCSUNBOW            | 5         | 5      | 0.29%   |
| KingSpec            | 5         | 6      | 0.29%   |
| FORESEE             | 5         | 5      | 0.29%   |
| Emtec               | 5         | 5      | 0.29%   |
| BAITITON            | 5         | 8      | 0.29%   |
| Team                | 4         | 4      | 0.23%   |
| OCZ                 | 4         | 4      | 0.23%   |
| Leven               | 4         | 4      | 0.23%   |
| Hewlett-Packard     | 4         | 5      | 0.23%   |
| BHT                 | 4         | 4      | 0.23%   |
| TO Exter            | 3         | 3      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1644      | 2158   | 33.92%  |
| HDD     | 1523      | 1936   | 31.43%  |
| NVMe    | 1291      | 1805   | 26.64%  |
| MMC     | 310       | 434    | 6.4%    |
| Unknown | 78        | 93     | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2862      | 3983   | 61.72%  |
| NVMe | 1283      | 1790   | 27.67%  |
| MMC  | 310       | 434    | 6.69%   |
| SAS  | 182       | 219    | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2337      | 3103   | 75.27%  |
| 0.51-1.0   | 710       | 920    | 22.87%  |
| 1.01-2.0   | 49        | 62     | 1.58%   |
| 3.01-4.0   | 5         | 5      | 0.16%   |
| 4.01-10.0  | 4         | 4      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1301      | 29.65%  |
| 251-500        | 1128      | 25.71%  |
| 501-1000       | 491       | 11.19%  |
| 1-20           | 456       | 10.39%  |
| 51-100         | 352       | 8.02%   |
| 21-50          | 224       | 5.1%    |
| 1001-2000      | 209       | 4.76%   |
| Unknown        | 100       | 2.28%   |
| 2001-3000      | 64        | 1.46%   |
| More than 3000 | 63        | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1978      | 43.36%  |
| 21-50          | 733       | 16.07%  |
| 101-250        | 621       | 13.61%  |
| 51-100         | 549       | 12.03%  |
| 251-500        | 328       | 7.19%   |
| 501-1000       | 161       | 3.53%   |
| Unknown        | 100       | 2.19%   |
| 1001-2000      | 55        | 1.21%   |
| More than 3000 | 19        | 0.42%   |
| 2001-3000      | 18        | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                     | 15        | 18     | 5.47%   |
| Seagate ST9500325AS 500GB                      | 7         | 7      | 2.55%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 9      | 2.55%   |
| Seagate ST500LT012-1DG142 500GB                | 6         | 6      | 2.19%   |
| Hitachi HTS725050A9A364 500GB                  | 6         | 6      | 2.19%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 5         | 5      | 1.82%   |
| Toshiba MQ01ABF050 500GB                       | 5         | 5      | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 5         | 5      | 1.82%   |
| Hitachi HTS545050A7E380 500GB                  | 5         | 5      | 1.82%   |
| HGST HTS721010A9E630 1TB                       | 5         | 5      | 1.82%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 4         | 4      | 1.46%   |
| Hitachi HTS547550A9E384 500GB                  | 4         | 4      | 1.46%   |
| HGST HTS725050A7E630 500GB                     | 4         | 5      | 1.46%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 1.09%   |
| Toshiba MK5065GSX 500GB                        | 3         | 3      | 1.09%   |
| SK hynix HFS512G39TND-N210A 512GB SSD          | 3         | 3      | 1.09%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.09%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 1.09%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 3         | 3      | 1.09%   |
| Hitachi HTS543232A7A384 320GB                  | 3         | 4      | 1.09%   |
| HGST HTS541075A9E680 752GB                     | 3         | 6      | 1.09%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 2         | 2      | 0.73%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 2         | 2      | 0.73%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 3      | 0.73%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 2         | 2      | 0.73%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.73%   |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 0.73%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.73%   |
| Seagate ST9160310AS 160GB                      | 2         | 3      | 0.73%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 0.73%   |
| Seagate ST320LT020-9YG142 320GB                | 2         | 2      | 0.73%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.73%   |
| Samsung Electronics HM160HC 160GB              | 2         | 2      | 0.73%   |
| Kingston SA400S37240G 240GB SSD                | 2         | 2      | 0.73%   |
| Hitachi HTS547575A9E384 752GB                  | 2         | 2      | 0.73%   |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 0.73%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 0.73%   |
| Hitachi HTS543225L9A300 250GB                  | 2         | 2      | 0.73%   |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.73%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 0.73%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 59        | 62     | 21.53%  |
| Hitachi                     | 47        | 48     | 17.15%  |
| WDC                         | 32        | 37     | 11.68%  |
| HGST                        | 32        | 39     | 11.68%  |
| Toshiba                     | 31        | 32     | 11.31%  |
| SK hynix                    | 11        | 13     | 4.01%   |
| Samsung Electronics         | 11        | 11     | 4.01%   |
| Crucial                     | 9         | 9      | 3.28%   |
| Micron Technology           | 7         | 7      | 2.55%   |
| Intel                       | 6         | 8      | 2.19%   |
| Kingston                    | 5         | 5      | 1.82%   |
| Fujitsu                     | 5         | 5      | 1.82%   |
| SanDisk                     | 3         | 3      | 1.09%   |
| Drevo                       | 2         | 2      | 0.73%   |
| Yangtze Memory Technologies | 1         | 1      | 0.36%   |
| WINTEC                      | 1         | 1      | 0.36%   |
| WDC WDS2                    | 1         | 1      | 0.36%   |
| Unknown                     | 1         | 1      | 0.36%   |
| Transcend                   | 1         | 2      | 0.36%   |
| Teclast                     | 1         | 1      | 0.36%   |
| TCSUNBOW                    | 1         | 1      | 0.36%   |
| SSSTC                       | 1         | 1      | 0.36%   |
| NGFF                        | 1         | 1      | 0.36%   |
| LITEON                      | 1         | 1      | 0.36%   |
| KingSpec                    | 1         | 1      | 0.36%   |
| KingDian                    | 1         | 1      | 0.36%   |
| BAITITON                    | 1         | 3      | 0.36%   |
| A-DATA Technology           | 1         | 1      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 62     | 28.37%  |
| Hitachi             | 47        | 48     | 22.6%   |
| HGST                | 32        | 39     | 15.38%  |
| WDC                 | 31        | 36     | 14.9%   |
| Toshiba             | 29        | 30     | 13.94%  |
| Fujitsu             | 5         | 5      | 2.4%    |
| Samsung Electronics | 4         | 4      | 1.92%   |
| Unknown             | 1         | 1      | 0.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 207       | 225    | 75.82%  |
| SSD  | 57        | 60     | 20.88%  |
| NVMe | 9         | 13     | 3.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 11.11%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 11.11%  |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 11.11%  |
| Seagate ST9500420AS 500GB                        | 1         | 3      | 11.11%  |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 11.11%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 44.44%  |
| Seagate             | 2         | 4      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2421      | 3747   | 54.96%  |
| Works    | 1703      | 2370   | 38.66%  |
| Malfunc  | 272       | 298    | 6.17%   |
| Failed   | 9         | 11     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2911      | 60.93%  |
| AMD                              | 479       | 10.03%  |
| Samsung Electronics              | 454       | 9.5%    |
| SanDisk                          | 216       | 4.52%   |
| SK hynix                         | 138       | 2.89%   |
| Kingston Technology Company      | 88        | 1.84%   |
| Micron Technology                | 80        | 1.67%   |
| Toshiba America Info Systems     | 75        | 1.57%   |
| KIOXIA                           | 68        | 1.42%   |
| Phison Electronics               | 60        | 1.26%   |
| Nvidia                           | 49        | 1.03%   |
| Micron/Crucial Technology        | 31        | 0.65%   |
| Silicon Integrated Systems [SiS] | 25        | 0.52%   |
| Union Memory (Shenzhen)          | 13        | 0.27%   |
| Solid State Storage Technology   | 13        | 0.27%   |
| Silicon Motion                   | 13        | 0.27%   |
| ADATA Technology                 | 8         | 0.17%   |
| VIA Technologies                 | 7         | 0.15%   |
| Lite-On Technology               | 7         | 0.15%   |
| Lenovo                           | 7         | 0.15%   |
| Apple                            | 7         | 0.15%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.13%   |
| Yangtze Memory Technologies      | 4         | 0.08%   |
| Silicon Image                    | 3         | 0.06%   |
| Shenzhen Longsys Electronics     | 3         | 0.06%   |
| Seagate Technology               | 3         | 0.06%   |
| ASMedia Technology               | 3         | 0.06%   |
| Realtek Semiconductor            | 2         | 0.04%   |
| JMicron Technology               | 2         | 0.04%   |
| O2 Micro                         | 1         | 0.02%   |
| Marvell Technology Group         | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 393       | 7.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 342       | 6.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 268       | 5.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 239       | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 218       | 4.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 217       | 4.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 203       | 3.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 164       | 3.18%   |
| Samsung NVMe SSD Controller 980                                                  | 132       | 2.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 128       | 2.48%   |
| Intel Volume Management Device NVMe RAID Controller                              | 119       | 2.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 112       | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 110       | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 109       | 2.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 102       | 1.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 98        | 1.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 84        | 1.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 78        | 1.51%   |
| Intel Comet Lake SATA AHCI Controller                                            | 66        | 1.28%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 61        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 55        | 1.06%   |
| Intel SSD 660P Series                                                            | 54        | 1.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 53        | 1.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 51        | 0.99%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 48        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 48        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 46        | 0.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 46        | 0.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 44        | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 42        | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 42        | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 41        | 0.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 40        | 0.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 39        | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                              | 36        | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 36        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 36        | 0.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 33        | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 32        | 0.62%   |
| Phison E12 NVMe Controller                                                       | 31        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2916      | 58.64%  |
| NVMe | 1291      | 25.96%  |
| IDE  | 400       | 8.04%   |
| RAID | 366       | 7.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3409      | 82.32%  |
| AMD          | 728       | 17.58%  |
| CentaurHauls | 2         | 0.05%   |
| ARM          | 1         | 0.02%   |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 87        | 2.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 68        | 1.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 68        | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 60        | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 56        | 1.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 54        | 1.3%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 51        | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 48        | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 48        | 1.16%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 48        | 1.16%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 46        | 1.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 46        | 1.11%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 43        | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 0.99%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 41        | 0.99%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 39        | 0.94%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 37        | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 36        | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 35        | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 35        | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 32        | 0.77%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 32        | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 29        | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 28        | 0.68%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 0.68%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 27        | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 27        | 0.65%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 26        | 0.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 26        | 0.63%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 26        | 0.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 25        | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 25        | 0.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 25        | 0.6%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 24        | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 24        | 0.58%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 24        | 0.58%   |
| Intel 12th Gen Core i7-12700H                 | 24        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 24        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1010      | 24.38%  |
| Intel Core i5           | 802       | 19.36%  |
| Other                   | 316       | 7.63%   |
| Intel Core 2 Duo        | 295       | 7.12%   |
| Intel Core i3           | 287       | 6.93%   |
| Intel Celeron           | 256       | 6.18%   |
| Intel Atom              | 171       | 4.13%   |
| AMD Ryzen 7             | 155       | 3.74%   |
| AMD Ryzen 5             | 151       | 3.65%   |
| Intel Pentium           | 51        | 1.23%   |
| AMD E1                  | 48        | 1.16%   |
| Intel Pentium Dual-Core | 44        | 1.06%   |
| Intel Pentium Dual      | 37        | 0.89%   |
| Intel Genuine           | 35        | 0.85%   |
| Intel Core 2            | 33        | 0.8%    |
| AMD A4                  | 33        | 0.8%    |
| AMD A10                 | 31        | 0.75%   |
| AMD A8                  | 30        | 0.72%   |
| AMD A6                  | 30        | 0.72%   |
| AMD Ryzen 3             | 26        | 0.63%   |
| AMD E2                  | 23        | 0.56%   |
| Intel Core i9           | 22        | 0.53%   |
| AMD Ryzen 9             | 22        | 0.53%   |
| Intel Pentium Silver    | 16        | 0.39%   |
| Intel Pentium M         | 16        | 0.39%   |
| AMD Ryzen 7 PRO         | 16        | 0.39%   |
| AMD Turion 64 X2 Mobile | 15        | 0.36%   |
| Intel Celeron M         | 13        | 0.31%   |
| AMD Sempron             | 13        | 0.31%   |
| Intel Celeron Dual-Core | 11        | 0.27%   |
| AMD Ryzen 5 PRO         | 11        | 0.27%   |
| AMD E                   | 10        | 0.24%   |
| AMD Mobile Sempron      | 9         | 0.22%   |
| AMD A12                 | 9         | 0.22%   |
| Intel Core m3           | 8         | 0.19%   |
| AMD Athlon II           | 7         | 0.17%   |
| Intel Core M            | 6         | 0.14%   |
| AMD Athlon              | 6         | 0.14%   |
| Intel Core Duo          | 5         | 0.12%   |
| AMD C-60                | 5         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2103      | 50.74%  |
| 4       | 1359      | 32.79%  |
| 6       | 225       | 5.43%   |
| 8       | 212       | 5.11%   |
| 1       | 171       | 4.13%   |
| 14      | 33        | 0.8%    |
| 10      | 26        | 0.63%   |
| 12      | 13        | 0.31%   |
| 16      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4141      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2890      | 69.64%  |
| 1       | 1257      | 30.29%  |
| 4       | 2         | 0.05%   |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4016      | 96.86%  |
| 32-bit         | 101       | 2.44%   |
| Unknown        | 29        | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1000      | 23.17%  |
| 0x306a9    | 214       | 4.96%   |
| 0x206a7    | 210       | 4.87%   |
| 0x1067a    | 146       | 3.38%   |
| 0x40651    | 144       | 3.34%   |
| 0x806ea    | 140       | 3.24%   |
| 0x806ec    | 133       | 3.08%   |
| 0x806c1    | 128       | 2.97%   |
| 0x406e3    | 128       | 2.97%   |
| 0x806e9    | 104       | 2.41%   |
| 0x6fd      | 96        | 2.22%   |
| 0x20655    | 92        | 2.13%   |
| 0x906ea    | 90        | 2.09%   |
| 0x306c3    | 88        | 2.04%   |
| 0x306d4    | 83        | 1.92%   |
| 0x10676    | 72        | 1.67%   |
| 0x08108109 | 71        | 1.65%   |
| 0x706e5    | 57        | 1.32%   |
| 0x406c3    | 57        | 1.32%   |
| 0x806eb    | 50        | 1.16%   |
| 0x906e9    | 48        | 1.11%   |
| 0x30678    | 47        | 1.09%   |
| 0x20652    | 47        | 1.09%   |
| 0x0a50000c | 47        | 1.09%   |
| 0x08608103 | 47        | 1.09%   |
| 0xa0652    | 44        | 1.02%   |
| 0x06006705 | 44        | 1.02%   |
| 0x706a8    | 40        | 0.93%   |
| 0x406c4    | 40        | 0.93%   |
| 0x106ca    | 40        | 0.93%   |
| 0x706a1    | 37        | 0.86%   |
| 0x506e3    | 32        | 0.74%   |
| 0x506c9    | 32        | 0.74%   |
| 0x07030105 | 31        | 0.72%   |
| 0x08600106 | 29        | 0.67%   |
| 0x08600104 | 29        | 0.67%   |
| 0x906a3    | 28        | 0.65%   |
| 0x106c2    | 27        | 0.63%   |
| 0x08108102 | 27        | 0.63%   |
| 0x0700010f | 25        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 721       | 17.4%   |
| Haswell          | 310       | 7.48%   |
| IvyBridge        | 272       | 6.56%   |
| Penryn           | 269       | 6.49%   |
| SandyBridge      | 257       | 6.2%    |
| Skylake          | 208       | 5.02%   |
| Core             | 194       | 4.68%   |
| TigerLake        | 180       | 4.34%   |
| Silvermont       | 177       | 4.27%   |
| Westmere         | 164       | 3.96%   |
| Unknown          | 143       | 3.45%   |
| Zen+             | 115       | 2.78%   |
| Broadwell        | 114       | 2.75%   |
| Goldmont plus    | 102       | 2.46%   |
| Excavator        | 97        | 2.34%   |
| IceLake          | 85        | 2.05%   |
| Bonnell          | 82        | 1.98%   |
| Zen 2            | 80        | 1.93%   |
| Zen 3            | 74        | 1.79%   |
| CometLake        | 65        | 1.57%   |
| P6               | 59        | 1.42%   |
| Alderlake Hybrid | 49        | 1.18%   |
| Puma             | 43        | 1.04%   |
| Jaguar           | 42        | 1.01%   |
| Goldmont         | 42        | 1.01%   |
| K8 Hammer        | 38        | 0.92%   |
| Bobcat           | 32        | 0.77%   |
| Zen              | 26        | 0.63%   |
| K10              | 21        | 0.51%   |
| Nehalem          | 20        | 0.48%   |
| K8 & K10 hybrid  | 18        | 0.43%   |
| K10 Llano        | 15        | 0.36%   |
| Steamroller      | 13        | 0.31%   |
| Piledriver       | 9         | 0.22%   |
| Tremont          | 5         | 0.12%   |
| NetBurst         | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2998      | 56.77%  |
| Nvidia                           | 1210      | 22.91%  |
| AMD                              | 1052      | 19.92%  |
| Silicon Integrated Systems [SiS] | 15        | 0.28%   |
| VIA Technologies                 | 5         | 0.09%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 255       | 4.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 226       | 4.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 181       | 3.27%   |
| Intel UHD Graphics 620                                                                   | 174       | 3.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 166       | 3%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 151       | 2.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 146       | 2.64%   |
| Intel HD Graphics 620                                                                    | 120       | 2.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 119       | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 118       | 2.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 115       | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 114       | 2.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 109       | 1.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 107       | 1.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 96        | 1.74%   |
| Intel HD Graphics 5500                                                                   | 95        | 1.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 86        | 1.56%   |
| AMD Renoir                                                                               | 78        | 1.41%   |
| AMD Lucienne                                                                             | 78        | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 76        | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 76        | 1.37%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 69        | 1.25%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 66        | 1.19%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 64        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 63        | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 58        | 1.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 58        | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 56        | 1.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 55        | 0.99%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 49        | 0.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 46        | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 45        | 0.81%   |
| Intel HD Graphics 630                                                                    | 45        | 0.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 45        | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                                            | 43        | 0.78%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 41        | 0.74%   |
| Intel HD Graphics 530                                                                    | 40        | 0.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 40        | 0.72%   |
| Nvidia GM108M [GeForce MX130]                                                            | 37        | 0.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 37        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1899      | 45.75%  |
| Intel + Nvidia  | 897       | 21.61%  |
| 1 x AMD         | 716       | 17.25%  |
| 1 x Nvidia      | 251       | 6.05%   |
| Intel + AMD     | 182       | 4.38%   |
| 2 x AMD         | 99        | 2.38%   |
| AMD + Nvidia    | 59        | 1.42%   |
| 2 x Intel       | 18        | 0.43%   |
| 1 x SiS         | 15        | 0.36%   |
| Other           | 5         | 0.12%   |
| 1 x VIA         | 5         | 0.12%   |
| 2 x Nvidia      | 4         | 0.1%    |
| 1 x S3 Graphics | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3553      | 84.6%   |
| Proprietary | 539       | 12.83%  |
| Unknown     | 108       | 2.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2584      | 60.61%  |
| 0.01-0.5   | 594       | 13.93%  |
| 1.01-2.0   | 552       | 12.95%  |
| 0.51-1.0   | 284       | 6.66%   |
| 3.01-4.0   | 172       | 4.03%   |
| 5.01-6.0   | 44        | 1.03%   |
| 7.01-8.0   | 23        | 0.54%   |
| 2.01-3.0   | 9         | 0.21%   |
| 8.01-16.0  | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 859       | 19.09%  |
| Chimei Innolux          | 666       | 14.8%   |
| BOE                     | 596       | 13.24%  |
| LG Display              | 593       | 13.18%  |
| Samsung Electronics     | 510       | 11.33%  |
| Chi Mei Optoelectronics | 136       | 3.02%   |
| Sharp                   | 114       | 2.53%   |
| Apple                   | 99        | 2.2%    |
| Goldstar                | 79        | 1.76%   |
| Hewlett-Packard         | 74        | 1.64%   |
| Philips                 | 69        | 1.53%   |
| LG Philips              | 65        | 1.44%   |
| PANDA                   | 57        | 1.27%   |
| Lenovo                  | 56        | 1.24%   |
| Dell                    | 55        | 1.22%   |
| Ancor Communications    | 49        | 1.09%   |
| Acer                    | 38        | 0.84%   |
| HannStar                | 34        | 0.76%   |
| InfoVision              | 32        | 0.71%   |
| BenQ                    | 32        | 0.71%   |
| Sony                    | 26        | 0.58%   |
| CSO                     | 23        | 0.51%   |
| CPT                     | 23        | 0.51%   |
| AOC                     | 23        | 0.51%   |
| Toshiba                 | 14        | 0.31%   |
| Quanta Display          | 13        | 0.29%   |
| LGD                     | 13        | 0.29%   |
| ASUSTek Computer        | 10        | 0.22%   |
| Valve                   | 9         | 0.2%    |
| MSI                     | 9         | 0.2%    |
| TMX                     | 8         | 0.18%   |
| Seiko/Epson             | 8         | 0.18%   |
| InnoLux Display         | 6         | 0.13%   |
| Vestel Elektronik       | 5         | 0.11%   |
| Panasonic               | 5         | 0.11%   |
| Iiyama                  | 5         | 0.11%   |
| Eizo                    | 5         | 0.11%   |
| Tianma XM               | 4         | 0.09%   |
| Nvidia                  | 4         | 0.09%   |
| Unknown                 | 3         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 68        | 1.5%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 35        | 0.77%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 34        | 0.75%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 33        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 32        | 0.7%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 32        | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 31        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 30        | 0.66%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 29        | 0.64%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 28        | 0.62%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 26        | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 25        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 24        | 0.53%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 23        | 0.51%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 22        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 22        | 0.48%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 22        | 0.48%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 22        | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 21        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 20        | 0.44%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 18        | 0.4%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 18        | 0.4%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 18        | 0.4%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 17        | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 17        | 0.37%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 15        | 0.33%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 15        | 0.33%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 14        | 0.31%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 14        | 0.31%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 14        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 14        | 0.31%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 14        | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 13        | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 13        | 0.29%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1694      | 39.67%  |
| 1366x768 (WXGA)    | 1422      | 33.3%   |
| 1280x800 (WXGA)    | 294       | 6.89%   |
| 1600x900 (HD+)     | 147       | 3.44%   |
| 3840x2160 (4K)     | 139       | 3.26%   |
| 1440x900 (WXGA+)   | 71        | 1.66%   |
| 2560x1440 (QHD)    | 69        | 1.62%   |
| 1920x1200 (WUXGA)  | 68        | 1.59%   |
| 1024x600           | 60        | 1.41%   |
| 1680x1050 (WSXGA+) | 36        | 0.84%   |
| 2560x1600          | 35        | 0.82%   |
| 2160x1440          | 35        | 0.82%   |
| 2880x1800          | 25        | 0.59%   |
| 1280x1024 (SXGA)   | 24        | 0.56%   |
| 3840x2400          | 16        | 0.37%   |
| 2560x1080          | 14        | 0.33%   |
| 1360x768           | 14        | 0.33%   |
| 3440x1440          | 11        | 0.26%   |
| 800x1280           | 10        | 0.23%   |
| 3200x1800 (QHD+)   | 8         | 0.19%   |
| 3000x2000          | 8         | 0.19%   |
| 1024x768 (XGA)     | 7         | 0.16%   |
| 3072x1920          | 6         | 0.14%   |
| 2520x1680          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 2240x1400          | 4         | 0.09%   |
| 1920x540           | 4         | 0.09%   |
| Unknown            | 4         | 0.09%   |
| 3840x1600          | 3         | 0.07%   |
| 3840x1080          | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 3456x2160          | 2         | 0.05%   |
| 2880x1920          | 2         | 0.05%   |
| 2880x1620          | 2         | 0.05%   |
| 2288x1287          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1600x1200          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 1280x720 (HD)      | 2         | 0.05%   |
| 3840x1200          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2288      | 50.88%  |
| 13      | 546       | 12.14%  |
| 14      | 394       | 8.76%   |
| 17      | 213       | 4.74%   |
| 24      | 139       | 3.09%   |
| 27      | 126       | 2.8%    |
| 12      | 124       | 2.76%   |
| 23      | 99        | 2.2%    |
| 21      | 80        | 1.78%   |
| 11      | 69        | 1.53%   |
| 10      | 66        | 1.47%   |
| Unknown | 61        | 1.36%   |
| 16      | 54        | 1.2%    |
| 19      | 30        | 0.67%   |
| 18      | 26        | 0.58%   |
| 34      | 18        | 0.4%    |
| 22      | 18        | 0.4%    |
| 31      | 17        | 0.38%   |
| 40      | 15        | 0.33%   |
| 20      | 14        | 0.31%   |
| 84      | 11        | 0.24%   |
| 54      | 11        | 0.24%   |
| 7       | 9         | 0.2%    |
| 32      | 7         | 0.16%   |
| 25      | 7         | 0.16%   |
| 26      | 6         | 0.13%   |
| 8       | 6         | 0.13%   |
| 72      | 5         | 0.11%   |
| 65      | 5         | 0.11%   |
| 47      | 4         | 0.09%   |
| 35      | 4         | 0.09%   |
| 58      | 3         | 0.07%   |
| 52      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 37      | 3         | 0.07%   |
| 142     | 2         | 0.04%   |
| 46      | 2         | 0.04%   |
| 28      | 2         | 0.04%   |
| 49      | 1         | 0.02%   |
| 42      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2927      | 65.51%  |
| 201-300        | 557       | 12.47%  |
| 501-600        | 345       | 7.72%   |
| 351-400        | 277       | 6.2%    |
| 401-500        | 152       | 3.4%    |
| Unknown        | 61        | 1.37%   |
| 601-700        | 34        | 0.76%   |
| 1001-1500      | 30        | 0.67%   |
| 701-800        | 26        | 0.58%   |
| 801-900        | 23        | 0.51%   |
| 1501-2000      | 16        | 0.36%   |
| 1-100          | 10        | 0.22%   |
| 101-200        | 7         | 0.16%   |
| More than 2000 | 2         | 0.04%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3323      | 81.77%  |
| 16/10   | 543       | 13.36%  |
| 3/2     | 64        | 1.57%   |
| Unknown | 46        | 1.13%   |
| 21/9    | 27        | 0.66%   |
| 5/4     | 25        | 0.62%   |
| 4/3     | 17        | 0.42%   |
| 0.67    | 9         | 0.22%   |
| 32/9    | 4         | 0.1%    |
| 6/5     | 3         | 0.07%   |
| 1.00    | 2         | 0.05%   |
| 2.21    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2288      | 50.98%  |
| 81-90          | 718       | 16%     |
| 201-250        | 280       | 6.24%   |
| 71-80          | 219       | 4.88%   |
| 121-130        | 171       | 3.81%   |
| 301-350        | 132       | 2.94%   |
| 61-70          | 119       | 2.65%   |
| 51-60          | 69        | 1.54%   |
| 41-50          | 67        | 1.49%   |
| Unknown        | 61        | 1.36%   |
| 151-200        | 57        | 1.27%   |
| 351-500        | 47        | 1.05%   |
| 251-300        | 46        | 1.02%   |
| 111-120        | 44        | 0.98%   |
| More than 1000 | 40        | 0.89%   |
| 141-150        | 37        | 0.82%   |
| 131-140        | 30        | 0.67%   |
| 501-1000       | 30        | 0.67%   |
| 91-100         | 17        | 0.38%   |
| 1-40           | 16        | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1653      | 37.4%   |
| 101-120       | 1424      | 32.22%  |
| 51-100        | 855       | 19.34%  |
| 161-240       | 288       | 6.52%   |
| More than 240 | 107       | 2.42%   |
| Unknown       | 61        | 1.38%   |
| 1-50          | 32        | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3502      | 82.48%  |
| 2     | 575       | 13.54%  |
| 0     | 118       | 2.78%   |
| 3     | 47        | 1.11%   |
| 4     | 4         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2236      | 33.74%  |
| Intel                             | 1949      | 29.41%  |
| Qualcomm Atheros                  | 1022      | 15.42%  |
| Broadcom                          | 496       | 7.48%   |
| Marvell Technology Group          | 125       | 1.89%   |
| Broadcom Limited                  | 111       | 1.67%   |
| MediaTek                          | 81        | 1.22%   |
| Ralink                            | 73        | 1.1%    |
| TP-Link                           | 55        | 0.83%   |
| Ralink Technology                 | 46        | 0.69%   |
| Nvidia                            | 33        | 0.5%    |
| ASIX Electronics                  | 32        | 0.48%   |
| Dell                              | 27        | 0.41%   |
| Huawei Technologies               | 26        | 0.39%   |
| Ericsson Business Mobile Networks | 21        | 0.32%   |
| Samsung Electronics               | 20        | 0.3%    |
| Xiaomi                            | 19        | 0.29%   |
| Silicon Integrated Systems [SiS]  | 18        | 0.27%   |
| Sierra Wireless                   | 17        | 0.26%   |
| JMicron Technology                | 17        | 0.26%   |
| Attansic Technology               | 17        | 0.26%   |
| Qualcomm                          | 14        | 0.21%   |
| Qualcomm Atheros Communications   | 13        | 0.2%    |
| Hewlett-Packard                   | 12        | 0.18%   |
| DisplayLink                       | 10        | 0.15%   |
| OPPO Electronics                  | 9         | 0.14%   |
| Lenovo                            | 9         | 0.14%   |
| Sitecom Europe                    | 8         | 0.12%   |
| Apple                             | 7         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.09%   |
| T & A Mobile Phones               | 6         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.09%   |
| NetGear                           | 6         | 0.09%   |
| D-Link System                     | 6         | 0.09%   |
| AMD                               | 6         | 0.09%   |
| ICS Advent                        | 5         | 0.08%   |
| Fibocom                           | 5         | 0.08%   |
| Belkin Components                 | 5         | 0.08%   |
| D-Link                            | 4         | 0.06%   |
| ZyDAS                             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1337      | 17.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 411       | 5.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 184       | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 182       | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 174       | 2.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 163       | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 158       | 2.02%   |
| Intel Wireless 8265 / 8275                                              | 155       | 1.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 148       | 1.9%    |
| Intel Wi-Fi 6 AX200                                                     | 141       | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 131       | 1.68%   |
| Intel Wi-Fi 6 AX201                                                     | 125       | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 121       | 1.55%   |
| Intel Wireless 7265                                                     | 117       | 1.5%    |
| Intel Wireless 3165                                                     | 113       | 1.45%   |
| Intel Wireless 7260                                                     | 96        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 91        | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 83        | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 77        | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 70        | 0.9%    |
| Intel Wireless 8260                                                     | 70        | 0.9%    |
| Intel WiFi Link 5100                                                    | 70        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 68        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 65        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 59        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 53        | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 50        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 44        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 0.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 44        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                   | 41        | 0.53%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 40        | 0.51%   |
| Intel Ethernet Connection I218-LM                                       | 39        | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 39        | 0.5%    |
| Intel Centrino Advanced-N 6200                                          | 37        | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 36        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1869      | 43.79%  |
| Qualcomm Atheros                      | 932       | 21.84%  |
| Realtek Semiconductor                 | 679       | 15.91%  |
| Broadcom                              | 359       | 8.41%   |
| MediaTek                              | 79        | 1.85%   |
| Broadcom Limited                      | 77        | 1.8%    |
| Ralink                                | 73        | 1.71%   |
| Ralink Technology                     | 46        | 1.08%   |
| TP-Link                               | 43        | 1.01%   |
| Sierra Wireless                       | 17        | 0.4%    |
| Dell                                  | 16        | 0.37%   |
| Qualcomm Atheros Communications       | 13        | 0.3%    |
| Sitecom Europe                        | 7         | 0.16%   |
| Ericsson Business Mobile Networks     | 7         | 0.16%   |
| Qualcomm                              | 6         | 0.14%   |
| NetGear                               | 6         | 0.14%   |
| D-Link System                         | 6         | 0.14%   |
| Fibocom                               | 5         | 0.12%   |
| Belkin Components                     | 5         | 0.12%   |
| ZyDAS                                 | 3         | 0.07%   |
| Microsoft                             | 3         | 0.07%   |
| D-Link                                | 3         | 0.07%   |
| ASUSTek Computer                      | 3         | 0.07%   |
| U.S. Robotics                         | 2         | 0.05%   |
| Qcom                                  | 2         | 0.05%   |
| Hewlett-Packard                       | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Edimax Technology                     | 1         | 0.02%   |
| AVM                                   | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 184       | 4.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 182       | 4.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 174       | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 163       | 3.8%    |
| Intel Wireless 8265 / 8275                                              | 155       | 3.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 148       | 3.45%   |
| Intel Wi-Fi 6 AX200                                                     | 141       | 3.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 131       | 3.06%   |
| Intel Wi-Fi 6 AX201                                                     | 125       | 2.92%   |
| Intel Wireless 7265                                                     | 117       | 2.73%   |
| Intel Wireless 3165                                                     | 113       | 2.64%   |
| Intel Wireless 7260                                                     | 96        | 2.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 91        | 2.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 83        | 1.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 1.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 77        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 1.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 70        | 1.63%   |
| Intel Wireless 8260                                                     | 70        | 1.63%   |
| Intel WiFi Link 5100                                                    | 70        | 1.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 68        | 1.59%   |
| Broadcom BCM43142 802.11b/g/n                                           | 65        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 59        | 1.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 53        | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 50        | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 1.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 44        | 1.03%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 40        | 0.93%   |
| Intel Centrino Advanced-N 6200                                          | 37        | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 36        | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 35        | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 34        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 34        | 0.79%   |
| Intel Wireless-AC 9260                                                  | 33        | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 33        | 0.77%   |
| Intel Centrino Wireless-N 2230                                          | 32        | 0.75%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 31        | 0.72%   |
| Intel Wireless 3160                                                     | 30        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1977      | 58.06%  |
| Intel                                  | 597       | 17.53%  |
| Qualcomm Atheros                       | 206       | 6.05%   |
| Broadcom                               | 196       | 5.76%   |
| Marvell Technology Group               | 125       | 3.67%   |
| Broadcom Limited                       | 35        | 1.03%   |
| Nvidia                                 | 32        | 0.94%   |
| ASIX Electronics                       | 32        | 0.94%   |
| Huawei Technologies                    | 20        | 0.59%   |
| Xiaomi                                 | 19        | 0.56%   |
| JMicron Technology                     | 17        | 0.5%    |
| Attansic Technology                    | 17        | 0.5%    |
| Silicon Integrated Systems [SiS]       | 16        | 0.47%   |
| Samsung Electronics                    | 13        | 0.38%   |
| TP-Link                                | 12        | 0.35%   |
| DisplayLink                            | 10        | 0.29%   |
| OPPO Electronics                       | 9         | 0.26%   |
| Lenovo                                 | 9         | 0.26%   |
| Qualcomm                               | 8         | 0.23%   |
| Apple                                  | 7         | 0.21%   |
| ZTE WCDMA Technologies MSM             | 6         | 0.18%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.18%   |
| ICS Advent                             | 5         | 0.15%   |
| T & A Mobile Phones                    | 4         | 0.12%   |
| VIA Technologies                       | 3         | 0.09%   |
| Motorola PCS                           | 3         | 0.09%   |
| HMD Global                             | 3         | 0.09%   |
| Hewlett-Packard                        | 3         | 0.09%   |
| Spreadtrum Communications              | 2         | 0.06%   |
| MediaTek                               | 2         | 0.06%   |
| LG Electronics                         | 2         | 0.06%   |
| Google                                 | 2         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Sitecom Europe                         | 1         | 0.03%   |
| MosChip Semiconductor                  | 1         | 0.03%   |
| Microchip Technology                   | 1         | 0.03%   |
| D-Link                                 | 1         | 0.03%   |
| ADMtek                                 | 1         | 0.03%   |
| Accton Technology                      | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1337      | 38.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 411       | 11.97%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 158       | 4.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 121       | 3.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 44        | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                                          | 41        | 1.19%   |
| Intel Ethernet Connection I218-LM                                              | 39        | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 39        | 1.14%   |
| Intel 82567LM Gigabit Network Connection                                       | 36        | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 35        | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                       | 35        | 1.02%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 33        | 0.96%   |
| Intel Ethernet Connection I219-LM                                              | 30        | 0.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 29        | 0.84%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 28        | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 28        | 0.82%   |
| Intel Ethernet Connection I217-LM                                              | 26        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 25        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                                          | 25        | 0.73%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 23        | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 22        | 0.64%   |
| Intel Ethernet Connection I219-V                                               | 22        | 0.64%   |
| Intel Ethernet Connection (4) I219-V                                           | 20        | 0.58%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 20        | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 19        | 0.55%   |
| Nvidia MCP79 Ethernet                                                          | 18        | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 18        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 17        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 17        | 0.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 17        | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 17        | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 17        | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 17        | 0.5%    |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 17        | 0.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 15        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                                           | 15        | 0.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 15        | 0.44%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 15        | 0.44%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 14        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                          | 14        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4055      | 54.64%  |
| Ethernet | 3285      | 44.27%  |
| Modem    | 74        | 1%      |
| Unknown  | 7         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3406      | 79.39%  |
| Ethernet | 881       | 20.54%  |
| Unknown  | 2         | 0.05%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2992      | 72.15%  |
| 1     | 1032      | 24.89%  |
| 0     | 98        | 2.36%   |
| 3     | 25        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3897      | 93.03%  |
| Yes  | 292       | 6.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1374      | 44.52%  |
| Realtek Semiconductor           | 393       | 12.73%  |
| Qualcomm Atheros Communications | 220       | 7.13%   |
| IMC Networks                    | 177       | 5.74%   |
| Lite-On Technology              | 176       | 5.7%    |
| Broadcom                        | 169       | 5.48%   |
| Foxconn / Hon Hai               | 138       | 4.47%   |
| Apple                           | 90        | 2.92%   |
| Hewlett-Packard                 | 67        | 2.17%   |
| Realtek                         | 57        | 1.85%   |
| Dell                            | 44        | 1.43%   |
| Cambridge Silicon Radio         | 40        | 1.3%    |
| Toshiba                         | 35        | 1.13%   |
| Ralink                          | 35        | 1.13%   |
| ASUSTek Computer                | 18        | 0.58%   |
| Alps Electric                   | 15        | 0.49%   |
| Ralink Technology               | 7         | 0.23%   |
| MediaTek                        | 6         | 0.19%   |
| Foxconn International           | 5         | 0.16%   |
| Chicony Electronics             | 4         | 0.13%   |
| Askey Computer                  | 4         | 0.13%   |
| Taiyo Yuden                     | 3         | 0.1%    |
| Integrated System Solution      | 2         | 0.06%   |
| USI                             | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| ISSC                            | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Conwise Technology              | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 582       | 18.86%  |
| Realtek Bluetooth Radio                                                             | 267       | 8.65%   |
| Intel AX201 Bluetooth                                                               | 246       | 7.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 209       | 6.77%   |
| Intel AX200 Bluetooth                                                               | 136       | 4.41%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 96        | 3.11%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 87        | 2.82%   |
| IMC Networks Bluetooth Device                                                       | 73        | 2.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 61        | 1.98%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 51        | 1.65%   |
| IMC Networks Bluetooth Radio                                                        | 48        | 1.56%   |
| Apple Bluetooth Host Controller                                                     | 48        | 1.56%   |
| Realtek 802.11ac WLAN Adapter                                                       | 46        | 1.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 45        | 1.46%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 45        | 1.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 43        | 1.39%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 43        | 1.39%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 41        | 1.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 40        | 1.3%    |
| Lite-On Bluetooth Device                                                            | 39        | 1.26%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 37        | 1.2%    |
| Ralink RT3290 Bluetooth                                                             | 35        | 1.13%   |
| Intel Bluetooth Device                                                              | 34        | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 32        | 1.04%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 32        | 1.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 31        | 1%      |
| Broadcom BCM2045 Bluetooth                                                          | 25        | 0.81%   |
| IMC Networks Wireless_Device                                                        | 24        | 0.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 22        | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 21        | 0.68%   |
| Intel AX210 Bluetooth                                                               | 21        | 0.68%   |
| Apple Bluetooth HCI                                                                 | 20        | 0.65%   |
| Apple Bluetooth USB Host Controller                                                 | 18        | 0.58%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 17        | 0.55%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 17        | 0.55%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 17        | 0.55%   |
| Realtek RTL8723B Bluetooth                                                          | 16        | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 16        | 0.52%   |
| Lite-On Wireless_Device                                                             | 15        | 0.49%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 15        | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3260      | 67.23%  |
| AMD                                          | 857       | 17.67%  |
| Nvidia                                       | 473       | 9.75%   |
| C-Media Electronics                          | 28        | 0.58%   |
| Silicon Integrated Systems [SiS]             | 25        | 0.52%   |
| Logitech                                     | 20        | 0.41%   |
| GN Netcom                                    | 20        | 0.41%   |
| JMTek                                        | 15        | 0.31%   |
| Realtek Semiconductor                        | 14        | 0.29%   |
| Generalplus Technology                       | 12        | 0.25%   |
| CMX Systems                                  | 8         | 0.16%   |
| VIA Technologies                             | 7         | 0.14%   |
| Lenovo                                       | 7         | 0.14%   |
| Texas Instruments                            | 6         | 0.12%   |
| Plantronics                                  | 5         | 0.1%    |
| Hewlett-Packard                              | 5         | 0.1%    |
| Apple                                        | 5         | 0.1%    |
| M-Audio                                      | 4         | 0.08%   |
| Huawei Technologies                          | 4         | 0.08%   |
| Fujitsu                                      | 4         | 0.08%   |
| Creative Technology                          | 4         | 0.08%   |
| BEHRINGER International                      | 4         | 0.08%   |
| Sony                                         | 3         | 0.06%   |
| Samson Technologies                          | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| Syntek                                       | 2         | 0.04%   |
| SteelSeries ApS                              | 2         | 0.04%   |
| Medeli Electronics                           | 2         | 0.04%   |
| Focusrite-Novation                           | 2         | 0.04%   |
| DSEA A/S                                     | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |
| Corsair                                      | 2         | 0.04%   |
| Cambridge Silicon Radio                      | 2         | 0.04%   |
| ASUSTek Computer                             | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| Textech International                        | 1         | 0.02%   |
| TEAC                                         | 1         | 0.02%   |
| SmartlinkTechnology                          | 1         | 0.02%   |
| Schiit Audio                                 | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 465       | 7.89%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 377       | 6.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 304       | 5.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 240       | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 225       | 3.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 206       | 3.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 184       | 3.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 183       | 3.1%    |
| Intel 8 Series HD Audio Controller                                                                | 183       | 3.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 180       | 3.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 143       | 2.43%   |
| AMD FCH Azalia Controller                                                                         | 137       | 2.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 133       | 2.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 131       | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 128       | 2.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 121       | 2.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 121       | 2.05%   |
| Intel Cannon Lake PCH cAVS                                                                        | 121       | 2.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 116       | 1.97%   |
| Intel Broadwell-U Audio Controller                                                                | 114       | 1.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 110       | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 107       | 1.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 101       | 1.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 96        | 1.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 66        | 1.12%   |
| AMD High Definition Audio Controller                                                              | 66        | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 62        | 1.05%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 62        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 61        | 1.03%   |
| Intel Comet Lake PCH cAVS                                                                         | 59        | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 57        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 48        | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 46        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 45        | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 42        | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 39        | 0.66%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 35        | 0.59%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 34        | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 33        | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 32        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 808       | 29.6%   |
| SK hynix                     | 597       | 21.87%  |
| Micron Technology            | 349       | 12.78%  |
| Unknown                      | 243       | 8.9%    |
| Kingston                     | 226       | 8.28%   |
| Crucial                      | 122       | 4.47%   |
| Ramaxel Technology           | 69        | 2.53%   |
| Elpida                       | 63        | 2.31%   |
| Unknown (ABCD)               | 57        | 2.09%   |
| A-DATA Technology            | 41        | 1.5%    |
| Corsair                      | 36        | 1.32%   |
| Nanya Technology             | 34        | 1.25%   |
| Unknown                      | 15        | 0.55%   |
| Team                         | 11        | 0.4%    |
| Transcend                    | 9         | 0.33%   |
| ASint Technology             | 6         | 0.22%   |
| Toshiba                      | 5         | 0.18%   |
| G.Skill                      | 5         | 0.18%   |
| Timetec                      | 4         | 0.15%   |
| Qimonda                      | 4         | 0.15%   |
| 48spaces                     | 4         | 0.15%   |
| Patriot                      | 2         | 0.07%   |
| ChangXin Memory              | 2         | 0.07%   |
| Unknown (8A5D)               | 1         | 0.04%   |
| Unknown (8A02)               | 1         | 0.04%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.04%   |
| Unknown (0x5846)             | 1         | 0.04%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.04%   |
| Unigen                       | 1         | 0.04%   |
| Unifosa                      | 1         | 0.04%   |
| Smart Brazil                 | 1         | 0.04%   |
| SHARETRONIC                  | 1         | 0.04%   |
| Sesame                       | 1         | 0.04%   |
| Neo Forza                    | 1         | 0.04%   |
| Lexar                        | 1         | 0.04%   |
| Infineon                     | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| Essencore Limited            | 1         | 0.04%   |
| Avant                        | 1         | 0.04%   |
| Apacer                       | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 53        | 1.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 43        | 1.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 38        | 1.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 1.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 32        | 1.1%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 31        | 1.07%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 29        | 1%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 28        | 0.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 25        | 0.86%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 25        | 0.86%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 22        | 0.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 21        | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 20        | 0.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.69%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 20        | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.65%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 19        | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 0.62%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.59%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 17        | 0.59%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 17        | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 16        | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 16        | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 16        | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.52%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 15        | 0.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.52%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 15        | 0.52%   |
| Unknown                                                          | 15        | 0.52%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 14        | 0.48%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.48%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 14        | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1097      | 46.5%   |
| DDR3    | 795       | 33.7%   |
| LPDDR4  | 146       | 6.19%   |
| DDR2    | 139       | 5.89%   |
| LPDDR3  | 64        | 2.71%   |
| SDRAM   | 50        | 2.12%   |
| DDR5    | 20        | 0.85%   |
| Unknown | 17        | 0.72%   |
| LPDDR5  | 13        | 0.55%   |
| DRAM    | 10        | 0.42%   |
| DDR     | 8         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2112      | 88.74%  |
| Row Of Chips | 245       | 10.29%  |
| DIMM         | 10        | 0.42%   |
| Chip         | 10        | 0.42%   |
| Unknown      | 3         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 980       | 38.07%  |
| 4096  | 799       | 31.04%  |
| 2048  | 347       | 13.48%  |
| 16384 | 323       | 12.55%  |
| 1024  | 74        | 2.87%   |
| 32768 | 35        | 1.36%   |
| 512   | 15        | 0.58%   |
| 256   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 517       | 20.37%  |
| 1600    | 505       | 19.9%   |
| 3200    | 424       | 16.71%  |
| 2400    | 214       | 8.43%   |
| 1334    | 142       | 5.59%   |
| 2133    | 121       | 4.77%   |
| 1333    | 85        | 3.35%   |
| Unknown | 82        | 3.23%   |
| 667     | 78        | 3.07%   |
| 4267    | 51        | 2.01%   |
| 3266    | 43        | 1.69%   |
| 1066    | 41        | 1.62%   |
| 800     | 36        | 1.42%   |
| 1867    | 25        | 0.99%   |
| 1067    | 25        | 0.99%   |
| 4800    | 21        | 0.83%   |
| 4199    | 20        | 0.79%   |
| 8400    | 17        | 0.67%   |
| 2048    | 15        | 0.59%   |
| 533     | 15        | 0.59%   |
| 6400    | 13        | 0.51%   |
| 975     | 9         | 0.35%   |
| 4266    | 8         | 0.32%   |
| 2933    | 7         | 0.28%   |
| 3733    | 4         | 0.16%   |
| 333     | 3         | 0.12%   |
| 3400    | 2         | 0.08%   |
| 1866    | 2         | 0.08%   |
| 1639    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 400     | 2         | 0.08%   |
| 3000    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 2000    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 32.31%  |
| Samsung Electronics | 17        | 26.15%  |
| Canon               | 11        | 16.92%  |
| Brother Industries  | 6         | 9.23%   |
| Seiko Epson         | 4         | 6.15%   |
| Pantum              | 2         | 3.08%   |
| Xerox               | 1         | 1.54%   |
| Sagem               | 1         | 1.54%   |
| ICS Advent          | 1         | 1.54%   |
| Apple               | 1         | 1.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 3         | 4.55%   |
| Samsung M2070 Series                 | 3         | 4.55%   |
| Samsung M267x 287x Series            | 2         | 3.03%   |
| HP OfficeJet 3830 series             | 2         | 3.03%   |
| HP Officejet 2620 series             | 2         | 3.03%   |
| Xerox B215                           | 1         | 1.52%   |
| Seiko Epson WF-2510 Series           | 1         | 1.52%   |
| Seiko Epson Printer                  | 1         | 1.52%   |
| Seiko Epson L355 Series              | 1         | 1.52%   |
| Seiko Epson L3250 Series             | 1         | 1.52%   |
| Samsung SCX-483x 5x3x Series         | 1         | 1.52%   |
| Samsung SCX-4623 Series              | 1         | 1.52%   |
| Samsung SCX-4300 Series              | 1         | 1.52%   |
| Samsung ML-331x Series Laser Printer | 1         | 1.52%   |
| Samsung ML-2010P Mono Laser Printer  | 1         | 1.52%   |
| Samsung ML-1865W Series              | 1         | 1.52%   |
| Samsung ML-1640 Series Laser Printer | 1         | 1.52%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 1.52%   |
| Samsung C3060 Series                 | 1         | 1.52%   |
| Sagem Laser Pro LL                   | 1         | 1.52%   |
| Pantum P2500W series                 | 1         | 1.52%   |
| Pantum M6500W series                 | 1         | 1.52%   |
| ICS Advent Parallel Adapter          | 1         | 1.52%   |
| HP Officejet Pro 6230                | 1         | 1.52%   |
| HP OfficeJet 6950                    | 1         | 1.52%   |
| HP OfficeJet 5600 (USBHUB)           | 1         | 1.52%   |
| HP LaserJet P3005                    | 1         | 1.52%   |
| HP LaserJet P2055 series             | 1         | 1.52%   |
| HP LaserJet P1102                    | 1         | 1.52%   |
| HP LaserJet 1200                     | 1         | 1.52%   |
| HP LaserJet 1020                     | 1         | 1.52%   |
| HP LaserJet 1015                     | 1         | 1.52%   |
| HP LaserJet 1010                     | 1         | 1.52%   |
| HP ENVY 5000 series                  | 1         | 1.52%   |
| HP ENVY 4520 series                  | 1         | 1.52%   |
| HP DeskJet 940c                      | 1         | 1.52%   |
| HP DeskJet 840c                      | 1         | 1.52%   |
| HP Deskjet 3520 series               | 1         | 1.52%   |
| HP DeskJet 2700 series               | 1         | 1.52%   |
| HP Deskjet 2050 J510                 | 1         | 1.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 46.15%  |
| Seiko Epson     | 5         | 38.46%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 2         | 14.29%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 7.14%   |
| Seiko Epson ES-D400 [GT-S80]                             | 1         | 7.14%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]               | 1         | 7.14%   |
| HP Scanjet G2710                                         | 1         | 7.14%   |
| HP ScanJet 3570c                                         | 1         | 7.14%   |
| Canon CanoScan LIDE 25                                   | 1         | 7.14%   |
| Canon CanoScan LiDE 220                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 120                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 110                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 100                                  | 1         | 7.14%   |
| Canon CanoScan 4400F                                     | 1         | 7.14%   |
| Canon CanoScan 1220U                                     | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 972       | 26.23%  |
| IMC Networks                           | 453       | 12.22%  |
| Realtek Semiconductor                  | 275       | 7.42%   |
| Microdia                               | 261       | 7.04%   |
| Bison Electronics                      | 200       | 5.4%    |
| Quanta                                 | 197       | 5.32%   |
| Suyin                                  | 182       | 4.91%   |
| Cheng Uei Precision Industry (Foxlink) | 159       | 4.29%   |
| Sunplus Innovation Technology          | 158       | 4.26%   |
| Acer                                   | 106       | 2.86%   |
| Alcor Micro                            | 102       | 2.75%   |
| Syntek                                 | 94        | 2.54%   |
| Lite-On Technology                     | 86        | 2.32%   |
| Apple                                  | 81        | 2.19%   |
| Luxvisions Innotech Limited            | 72        | 1.94%   |
| Silicon Motion                         | 46        | 1.24%   |
| Ricoh                                  | 46        | 1.24%   |
| Logitech                               | 30        | 0.81%   |
| Z-Star Microelectronics                | 20        | 0.54%   |
| ALi                                    | 17        | 0.46%   |
| Samsung Electronics                    | 15        | 0.4%    |
| Primax Electronics                     | 15        | 0.4%    |
| icSpring                               | 13        | 0.35%   |
| Lenovo                                 | 10        | 0.27%   |
| Sunplus Technology                     | 8         | 0.22%   |
| Sonix Technology                       | 7         | 0.19%   |
| Importek                               | 7         | 0.19%   |
| DigiTech                               | 7         | 0.19%   |
| ARC International                      | 6         | 0.16%   |
| Genesys Logic                          | 5         | 0.13%   |
| GEMBIRD                                | 5         | 0.13%   |
| SunplusIT                              | 4         | 0.11%   |
| Microsoft                              | 4         | 0.11%   |
| Generalplus Technology                 | 3         | 0.08%   |
| WaveRider Communications               | 2         | 0.05%   |
| USB Camera CS                          | 2         | 0.05%   |
| Unknown (3730304231385031345945)       | 2         | 0.05%   |
| Pixart Imaging                         | 2         | 0.05%   |
| OmniVision Technologies                | 2         | 0.05%   |
| Nebraska Furniture Mart                | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 150       | 4.03%   |
| Microdia Integrated_Webcam_HD                           | 110       | 2.96%   |
| Chicony HD WebCam                                       | 93        | 2.5%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 83        | 2.23%   |
| IMC Networks Integrated Camera                          | 73        | 1.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 71        | 1.91%   |
| Realtek Integrated_Webcam_HD                            | 59        | 1.59%   |
| Realtek USB Camera                                      | 53        | 1.42%   |
| Alcor Micro USB 2.0 Camera                              | 53        | 1.42%   |
| Syntek Integrated Camera                                | 51        | 1.37%   |
| Chicony USB2.0 VGA UVC WebCam                           | 44        | 1.18%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 43        | 1.16%   |
| Chicony USB2.0 HD UVC WebCam                            | 43        | 1.16%   |
| Chicony HP Truevision HD                                | 43        | 1.16%   |
| Sunplus Integrated_Webcam_HD                            | 41        | 1.1%    |
| Bison Integrated Camera                                 | 41        | 1.1%    |
| Quanta HP TrueVision HD Camera                          | 37        | 0.99%   |
| IMC Networks HD Camera                                  | 37        | 0.99%   |
| Chicony HP TrueVision HD Camera                         | 35        | 0.94%   |
| Sunplus HD WebCam                                       | 30        | 0.81%   |
| Chicony HP Webcam                                       | 30        | 0.81%   |
| Chicony HP HD Camera                                    | 30        | 0.81%   |
| Chicony FJ Camera                                       | 30        | 0.81%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 29        | 0.78%   |
| Quanta HP Webcam                                        | 28        | 0.75%   |
| Acer Integrated Camera                                  | 27        | 0.73%   |
| Suyin HP TrueVision HD                                  | 25        | 0.67%   |
| Realtek USB2.0 VGA UVC WebCam                           | 25        | 0.67%   |
| Chicony USB2.0 Camera                                   | 25        | 0.67%   |
| Microdia Integrated Webcam                              | 24        | 0.64%   |
| Chicony HP Wide Vision HD Camera                        | 24        | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 24        | 0.64%   |
| Apple Built-in iSight                                   | 24        | 0.64%   |
| Alcor Micro Asus Integrated Webcam                      | 24        | 0.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 23        | 0.62%   |
| IMC Networks ov9734_azurewave_camera                    | 23        | 0.62%   |
| Bison SunplusIT Integrated Camera                       | 23        | 0.62%   |
| Suyin Acer CrystalEye Webcam                            | 22        | 0.59%   |
| Lite-On HP HD Camera                                    | 22        | 0.59%   |
| IMC Networks UVC VGA Webcam                             | 22        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 207       | 29.15%  |
| Synaptics                          | 151       | 21.27%  |
| Shenzhen Goodix Technology         | 128       | 18.03%  |
| Elan Microelectronics              | 86        | 12.11%  |
| Upek                               | 43        | 6.06%   |
| AuthenTec                          | 41        | 5.77%   |
| LighTuning Technology              | 39        | 5.49%   |
| STMicroelectronics                 | 6         | 0.85%   |
| Focal-systems.Corp                 | 5         | 0.7%    |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.28%   |
| Microsoft                          | 1         | 0.14%   |
| HOLTEK                             | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 98        | 13.8%   |
| Elan ELAN:ARM-M4                                                           | 59        | 8.31%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 43        | 6.06%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 5.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 5.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 27        | 3.8%    |
| Elan ELAN:Fingerprint                                                      | 27        | 3.8%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 25        | 3.52%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 21        | 2.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 2.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 2.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 2.82%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 2.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 16        | 2.25%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 1.97%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.97%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 1.69%   |
| Validity Sensors VFS491                                                    | 11        | 1.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 1.55%   |
| Unknown                                                                    | 10        | 1.41%   |
| Synaptics  WBDI                                                            | 9         | 1.27%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.13%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 1.13%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.13%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.99%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.99%   |
| AuthenTec AES1600                                                          | 7         | 0.99%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 0.85%   |
| Synaptics UWP WBDI                                                         | 6         | 0.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.85%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.85%   |
| AuthenTec AES2810                                                          | 6         | 0.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.7%    |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.7%    |
| Synaptics UWP WBDI Device                                                  | 5         | 0.7%    |
| LighTuning Fingerprint Reader                                              | 5         | 0.7%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 0.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 117       | 41.79%  |
| Alcor Micro              | 89        | 31.79%  |
| O2 Micro                 | 28        | 10%     |
| Lenovo                   | 16        | 5.71%   |
| Upek                     | 11        | 3.93%   |
| Advanced Card Systems    | 5         | 1.79%   |
| Gemalto (was Gemplus)    | 4         | 1.43%   |
| BIT4ID                   | 4         | 1.43%   |
| Realtek Semiconductor    | 2         | 0.71%   |
| SCM Microsystems         | 1         | 0.36%   |
| Reiner SCT Kartensysteme | 1         | 0.36%   |
| OmniKey                  | 1         | 0.36%   |
| In Focus Systems         | 1         | 0.36%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 86        | 30.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 12.5%   |
| Broadcom 58200                                                               | 35        | 12.5%   |
| Broadcom 5880                                                                | 25        | 8.93%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 8.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 7.14%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.71%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 3.93%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.43%   |
| BIT4ID miniLector EVO                                                        | 4         | 1.43%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.07%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.07%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 1.07%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.71%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.71%   |
| Advanced Card Systems ACR122U                                                | 2         | 0.71%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.36%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.36%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.36%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.36%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.36%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2613      | 61.21%  |
| 1     | 1294      | 30.31%  |
| 2     | 319       | 7.47%   |
| 3     | 30        | 0.7%    |
| 4     | 9         | 0.21%   |
| 5     | 3         | 0.07%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 702       | 35.06%  |
| Graphics card            | 476       | 23.78%  |
| Chipcard                 | 243       | 12.14%  |
| Net/wireless             | 182       | 9.09%   |
| Multimedia controller    | 100       | 5%      |
| Camera                   | 75        | 3.75%   |
| Bluetooth                | 60        | 3%      |
| Storage                  | 34        | 1.7%    |
| Communication controller | 31        | 1.55%   |
| Sound                    | 19        | 0.95%   |
| Modem                    | 19        | 0.95%   |
| Flash memory             | 18        | 0.9%    |
| Net/ethernet             | 15        | 0.75%   |
| Card reader              | 13        | 0.65%   |
| Network                  | 7         | 0.35%   |
| Dvb card                 | 3         | 0.15%   |
| Storage/ide              | 2         | 0.1%    |
| Wireless                 | 1         | 0.05%   |
| Storage/raid             | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |


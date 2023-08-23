Linux in Italy - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 11265

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [fb024a9374](https://linux-hardware.org/?probe=fb024a9374) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [398f85e94a](https://linux-hardware.org/?probe=398f85e94a) | Aug 12, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [92f4e14369](https://linux-hardware.org/?probe=92f4e14369) | Aug 11, 2023 |
| MSI           | Boston                      | Desktop     | [62ad275a7d](https://linux-hardware.org/?probe=62ad275a7d) | Aug 11, 2023 |
| MSI           | Boston                      | Desktop     | [a34a89c083](https://linux-hardware.org/?probe=a34a89c083) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [d4b93affe2](https://linux-hardware.org/?probe=d4b93affe2) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [7a8e32eb89](https://linux-hardware.org/?probe=7a8e32eb89) | Aug 11, 2023 |
| Gigabyte      | B250-HD3P-CF                | Desktop     | [b347883be2](https://linux-hardware.org/?probe=b347883be2) | Aug 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [b21e9793a5](https://linux-hardware.org/?probe=b21e9793a5) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| Fujitsu Si... | G31T-M2 V3.02               | Desktop     | [1c32da7aed](https://linux-hardware.org/?probe=1c32da7aed) | Aug 10, 2023 |
| Dell          | XPS 15 9575                 | Convertible | [48f1354795](https://linux-hardware.org/?probe=48f1354795) | Aug 10, 2023 |
| Dell          | Latitude 5300               | Notebook    | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [9627b6d632](https://linux-hardware.org/?probe=9627b6d632) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [099d1ac0de](https://linux-hardware.org/?probe=099d1ac0de) | Aug 10, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [a9c4812d66](https://linux-hardware.org/?probe=a9c4812d66) | Aug 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [abf7479cb8](https://linux-hardware.org/?probe=abf7479cb8) | Aug 09, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [e6305472c5](https://linux-hardware.org/?probe=e6305472c5) | Aug 09, 2023 |
| Lenovo        | ThinkPad X240 20AL00C6UK    | Notebook    | [d33c586eab](https://linux-hardware.org/?probe=d33c586eab) | Aug 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [5f186cbc4d](https://linux-hardware.org/?probe=5f186cbc4d) | Aug 09, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [0c755e3349](https://linux-hardware.org/?probe=0c755e3349) | Aug 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [16acf13ed8](https://linux-hardware.org/?probe=16acf13ed8) | Aug 09, 2023 |
| HP            | 255 G5                      | Notebook    | [d4adfe0ead](https://linux-hardware.org/?probe=d4adfe0ead) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [f3ee04187f](https://linux-hardware.org/?probe=f3ee04187f) | Aug 09, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [33e964d1d6](https://linux-hardware.org/?probe=33e964d1d6) | Aug 09, 2023 |
| ASUSTek       | ET2011A 0405                | All in one  | [a236196a29](https://linux-hardware.org/?probe=a236196a29) | Aug 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6abad99081](https://linux-hardware.org/?probe=6abad99081) | Aug 08, 2023 |
| Dell          | XPS L521X                   | Notebook    | [5aec7ef034](https://linux-hardware.org/?probe=5aec7ef034) | Aug 08, 2023 |
| Intel         | X79M-S                      | Desktop     | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [ed5ccc8efb](https://linux-hardware.org/?probe=ed5ccc8efb) | Aug 08, 2023 |
| Dell          | Latitude 7440               | Notebook    | [0cfa45fbd8](https://linux-hardware.org/?probe=0cfa45fbd8) | Aug 08, 2023 |
| Dell          | Latitude 7440               | Notebook    | [e476a3e532](https://linux-hardware.org/?probe=e476a3e532) | Aug 08, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [3cd08fb125](https://linux-hardware.org/?probe=3cd08fb125) | Aug 08, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [8839aa58c4](https://linux-hardware.org/?probe=8839aa58c4) | Aug 08, 2023 |
| AZW           | U59                         | Desktop     | [d7b7b7641b](https://linux-hardware.org/?probe=d7b7b7641b) | Aug 07, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [c7a3dd2647](https://linux-hardware.org/?probe=c7a3dd2647) | Aug 07, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [ed6fdbd235](https://linux-hardware.org/?probe=ed6fdbd235) | Aug 07, 2023 |
| Timi          | A7S                         | Notebook    | [34a354df5a](https://linux-hardware.org/?probe=34a354df5a) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [ce02da2586](https://linux-hardware.org/?probe=ce02da2586) | Aug 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [31c3da5150](https://linux-hardware.org/?probe=31c3da5150) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [aabc0a8aee](https://linux-hardware.org/?probe=aabc0a8aee) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [4dec7b692a](https://linux-hardware.org/?probe=4dec7b692a) | Aug 07, 2023 |
| ASUSTek       | P5GDC                       | Desktop     | [82fefe395d](https://linux-hardware.org/?probe=82fefe395d) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Dell          | Latitude E5540              | Notebook    | [928c427cbc](https://linux-hardware.org/?probe=928c427cbc) | Aug 06, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1b3c788790](https://linux-hardware.org/?probe=1b3c788790) | Aug 06, 2023 |
| Dell          | Precision 7730              | Notebook    | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| Pegatron      | IPMMB-MQ1                   | Desktop     | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [88f7813621](https://linux-hardware.org/?probe=88f7813621) | Aug 06, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5b67a1f9cf](https://linux-hardware.org/?probe=5b67a1f9cf) | Aug 06, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [7a4e005f77](https://linux-hardware.org/?probe=7a4e005f77) | Aug 06, 2023 |
| Dell          | Latitude E6230              | Notebook    | [cc78868322](https://linux-hardware.org/?probe=cc78868322) | Aug 05, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [6d78d72399](https://linux-hardware.org/?probe=6d78d72399) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [5ca4ca286b](https://linux-hardware.org/?probe=5ca4ca286b) | Aug 05, 2023 |
| Mediacom      | SmartBook 130 FullHD - M... | Notebook    | [3aa51361ae](https://linux-hardware.org/?probe=3aa51361ae) | Aug 05, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [1a1d48f2a6](https://linux-hardware.org/?probe=1a1d48f2a6) | Aug 05, 2023 |
| Acer          | Veriton M2632G V:1.0        | Desktop     | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [9d5490fb82](https://linux-hardware.org/?probe=9d5490fb82) | Aug 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [e21469f818](https://linux-hardware.org/?probe=e21469f818) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [6fd7ffb05b](https://linux-hardware.org/?probe=6fd7ffb05b) | Aug 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [d946977ec8](https://linux-hardware.org/?probe=d946977ec8) | Aug 04, 2023 |
| SANTECH       | NL5xNU                      | Notebook    | [68d1f62251](https://linux-hardware.org/?probe=68d1f62251) | Aug 04, 2023 |
| HP            | Notebook                    | Notebook    | [9b9a2bd44a](https://linux-hardware.org/?probe=9b9a2bd44a) | Aug 04, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e0b5eb8809](https://linux-hardware.org/?probe=e0b5eb8809) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | Notebook    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| PC Special... | Lafite Pro III 17           | Notebook    | [702cdf4138](https://linux-hardware.org/?probe=702cdf4138) | Aug 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [89c0c5c135](https://linux-hardware.org/?probe=89c0c5c135) | Aug 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [020699b05e](https://linux-hardware.org/?probe=020699b05e) | Aug 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ccc5e0b3ab](https://linux-hardware.org/?probe=ccc5e0b3ab) | Aug 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [34a566342b](https://linux-hardware.org/?probe=34a566342b) | Aug 03, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [8f3eaca764](https://linux-hardware.org/?probe=8f3eaca764) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [986cf08dc9](https://linux-hardware.org/?probe=986cf08dc9) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [da8d764a97](https://linux-hardware.org/?probe=da8d764a97) | Aug 03, 2023 |
| Timi          | A7S                         | Notebook    | [7de693ff63](https://linux-hardware.org/?probe=7de693ff63) | Aug 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| HP            | ENVY 17                     | Notebook    | [ef244ad969](https://linux-hardware.org/?probe=ef244ad969) | Aug 02, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [2c10cb0378](https://linux-hardware.org/?probe=2c10cb0378) | Aug 02, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [7241233996](https://linux-hardware.org/?probe=7241233996) | Aug 02, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d0e963d600](https://linux-hardware.org/?probe=d0e963d600) | Aug 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [6cfc0b2281](https://linux-hardware.org/?probe=6cfc0b2281) | Aug 01, 2023 |
| ASRock        | B365M-HDV                   | Desktop     | [994853ef26](https://linux-hardware.org/?probe=994853ef26) | Aug 01, 2023 |
| Intel         | X79                         | Desktop     | [051316466a](https://linux-hardware.org/?probe=051316466a) | Aug 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [603bee8812](https://linux-hardware.org/?probe=603bee8812) | Aug 01, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [64bc1caf41](https://linux-hardware.org/?probe=64bc1caf41) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [18924cfab7](https://linux-hardware.org/?probe=18924cfab7) | Jul 31, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9ddb5c2ea3](https://linux-hardware.org/?probe=9ddb5c2ea3) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [00c9fab30f](https://linux-hardware.org/?probe=00c9fab30f) | Jul 31, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [be9923f6d2](https://linux-hardware.org/?probe=be9923f6d2) | Jul 30, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [d84e6d9683](https://linux-hardware.org/?probe=d84e6d9683) | Jul 30, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [2672322c34](https://linux-hardware.org/?probe=2672322c34) | Jul 30, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [ac4682042f](https://linux-hardware.org/?probe=ac4682042f) | Jul 30, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [9a5567fb0b](https://linux-hardware.org/?probe=9a5567fb0b) | Jul 30, 2023 |
| SiComputer    | NL40_50CU                   | Notebook    | [95afbe5674](https://linux-hardware.org/?probe=95afbe5674) | Jul 30, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [37e282ff80](https://linux-hardware.org/?probe=37e282ff80) | Jul 30, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| Beelink       | Gemini X                    | Notebook    | [2846d152be](https://linux-hardware.org/?probe=2846d152be) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [cd83e4a73a](https://linux-hardware.org/?probe=cd83e4a73a) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [56918c8bad](https://linux-hardware.org/?probe=56918c8bad) | Jul 29, 2023 |
| ASRock        | A620M-HDV/M.2+              | Desktop     | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| Dell          | System XPS L702X            | Notebook    | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [83a69f246c](https://linux-hardware.org/?probe=83a69f246c) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [7e89496549](https://linux-hardware.org/?probe=7e89496549) | Jul 27, 2023 |
| MSI           | MS-B1831                    | Desktop     | [35f0e625f1](https://linux-hardware.org/?probe=35f0e625f1) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [d32fa8840b](https://linux-hardware.org/?probe=d32fa8840b) | Jul 27, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [613164e308](https://linux-hardware.org/?probe=613164e308) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6546d49225](https://linux-hardware.org/?probe=6546d49225) | Jul 27, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [bb2046286f](https://linux-hardware.org/?probe=bb2046286f) | Jul 26, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [6ced09890f](https://linux-hardware.org/?probe=6ced09890f) | Jul 26, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [0a84eeb8e2](https://linux-hardware.org/?probe=0a84eeb8e2) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [87d69792fb](https://linux-hardware.org/?probe=87d69792fb) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [83097985a2](https://linux-hardware.org/?probe=83097985a2) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| ASUSTek       | P50IJ                       | Notebook    | [d8aff1255a](https://linux-hardware.org/?probe=d8aff1255a) | Jul 25, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [47d5775197](https://linux-hardware.org/?probe=47d5775197) | Jul 25, 2023 |
| HP            | 871C                        | All in one  | [4ebf5aee4d](https://linux-hardware.org/?probe=4ebf5aee4d) | Jul 25, 2023 |
| Acer          | TravelMate B113             | Notebook    | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [676bfc8484](https://linux-hardware.org/?probe=676bfc8484) | Jul 25, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [22c5b2df49](https://linux-hardware.org/?probe=22c5b2df49) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [80aa11a7e8](https://linux-hardware.org/?probe=80aa11a7e8) | Jul 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f347019f85](https://linux-hardware.org/?probe=f347019f85) | Jul 24, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [48ac49a195](https://linux-hardware.org/?probe=48ac49a195) | Jul 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [c286ff883f](https://linux-hardware.org/?probe=c286ff883f) | Jul 24, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| HP            | 250 G3                      | Notebook    | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | Notebook    | [2def302827](https://linux-hardware.org/?probe=2def302827) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | Notebook    | [2f0b072622](https://linux-hardware.org/?probe=2f0b072622) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [84c7ea08c6](https://linux-hardware.org/?probe=84c7ea08c6) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| Intel         | X79                         | Desktop     | [8037a9fc0e](https://linux-hardware.org/?probe=8037a9fc0e) | Jul 24, 2023 |
| Timi          | A7S                         | Notebook    | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [5d16b13584](https://linux-hardware.org/?probe=5d16b13584) | Jul 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ae4343c245](https://linux-hardware.org/?probe=ae4343c245) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [04982390e0](https://linux-hardware.org/?probe=04982390e0) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b13bb2310f](https://linux-hardware.org/?probe=b13bb2310f) | Jul 23, 2023 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [ff5392a180](https://linux-hardware.org/?probe=ff5392a180) | Jul 23, 2023 |
| Microtech     | ebookPro                    | Notebook    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| HP            | 250 G1                      | Notebook    | [deab96c404](https://linux-hardware.org/?probe=deab96c404) | Jul 23, 2023 |
| ASUSTek       | CG8480                      | Desktop     | [2b839ca54f](https://linux-hardware.org/?probe=2b839ca54f) | Jul 23, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [9ce9a989dd](https://linux-hardware.org/?probe=9ce9a989dd) | Jul 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0e830a2330](https://linux-hardware.org/?probe=0e830a2330) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [23d73ededd](https://linux-hardware.org/?probe=23d73ededd) | Jul 23, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [bda4392623](https://linux-hardware.org/?probe=bda4392623) | Jul 22, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [3ed87bb81b](https://linux-hardware.org/?probe=3ed87bb81b) | Jul 22, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [ea078c7fb9](https://linux-hardware.org/?probe=ea078c7fb9) | Jul 22, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [723915cfda](https://linux-hardware.org/?probe=723915cfda) | Jul 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [931df813b1](https://linux-hardware.org/?probe=931df813b1) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [625e829a7e](https://linux-hardware.org/?probe=625e829a7e) | Jul 22, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [02903e0210](https://linux-hardware.org/?probe=02903e0210) | Jul 22, 2023 |
| MSI           | GL63 8SD                    | Notebook    | [7705e15f5e](https://linux-hardware.org/?probe=7705e15f5e) | Jul 21, 2023 |
| Dell          | XPS 9315                    | Notebook    | [f97422b64b](https://linux-hardware.org/?probe=f97422b64b) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [187cbf1010](https://linux-hardware.org/?probe=187cbf1010) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [32ec9929c9](https://linux-hardware.org/?probe=32ec9929c9) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [a1f316c8c9](https://linux-hardware.org/?probe=a1f316c8c9) | Jul 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [e99bf7a4be](https://linux-hardware.org/?probe=e99bf7a4be) | Jul 20, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [56e1ff54a3](https://linux-hardware.org/?probe=56e1ff54a3) | Jul 19, 2023 |
| Acer          | MCP7A                       | Desktop     | [06afe36113](https://linux-hardware.org/?probe=06afe36113) | Jul 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [032a11c2a5](https://linux-hardware.org/?probe=032a11c2a5) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 20RDS1G700     | Notebook    | [6ad3194fd9](https://linux-hardware.org/?probe=6ad3194fd9) | Jul 18, 2023 |
| HP            | 18E7                        | Desktop     | [bddd22fb18](https://linux-hardware.org/?probe=bddd22fb18) | Jul 18, 2023 |
| AMI           | Intel                       | Desktop     | [fb562a8b94](https://linux-hardware.org/?probe=fb562a8b94) | Jul 18, 2023 |
| AMI           | Intel                       | Desktop     | [52cb51f3c6](https://linux-hardware.org/?probe=52cb51f3c6) | Jul 18, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4c8b8b5a8a](https://linux-hardware.org/?probe=4c8b8b5a8a) | Jul 18, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [c75f0b8a63](https://linux-hardware.org/?probe=c75f0b8a63) | Jul 17, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [c7d69d227a](https://linux-hardware.org/?probe=c7d69d227a) | Jul 17, 2023 |
| MSI           | Creator 17 A10SE            | Notebook    | [775c65db16](https://linux-hardware.org/?probe=775c65db16) | Jul 17, 2023 |
| HP            | 3048h                       | Desktop     | [ad7b0d8c8d](https://linux-hardware.org/?probe=ad7b0d8c8d) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [7f25599ad8](https://linux-hardware.org/?probe=7f25599ad8) | Jul 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [2bda9f913a](https://linux-hardware.org/?probe=2bda9f913a) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [8c94595be0](https://linux-hardware.org/?probe=8c94595be0) | Jul 17, 2023 |
| Olivetti      | Olipad Graphos W811         | Notebook    | [d303fe2826](https://linux-hardware.org/?probe=d303fe2826) | Jul 17, 2023 |
| Toshiba       | TECRA A10                   | Notebook    | [0740ca470e](https://linux-hardware.org/?probe=0740ca470e) | Jul 16, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [65afe9f74b](https://linux-hardware.org/?probe=65afe9f74b) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [91f38d0ab5](https://linux-hardware.org/?probe=91f38d0ab5) | Jul 16, 2023 |
| Unknown       | Unknown                     | Soc         | [99bfa94ff7](https://linux-hardware.org/?probe=99bfa94ff7) | Jul 16, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [eb5e64c657](https://linux-hardware.org/?probe=eb5e64c657) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [60809c13e6](https://linux-hardware.org/?probe=60809c13e6) | Jul 15, 2023 |
| Lenovo        | ThinkPad T450 20BUS0S902    | Notebook    | [34329ab49c](https://linux-hardware.org/?probe=34329ab49c) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [6087b16809](https://linux-hardware.org/?probe=6087b16809) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [97e2731292](https://linux-hardware.org/?probe=97e2731292) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [dd63c138ad](https://linux-hardware.org/?probe=dd63c138ad) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [fab0c2fb26](https://linux-hardware.org/?probe=fab0c2fb26) | Jul 15, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [4b7f45adc4](https://linux-hardware.org/?probe=4b7f45adc4) | Jul 15, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [31ae047fcf](https://linux-hardware.org/?probe=31ae047fcf) | Jul 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8df4f1a098](https://linux-hardware.org/?probe=8df4f1a098) | Jul 14, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [9ec51bc7eb](https://linux-hardware.org/?probe=9ec51bc7eb) | Jul 14, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [a945d4d417](https://linux-hardware.org/?probe=a945d4d417) | Jul 14, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [1c568b626c](https://linux-hardware.org/?probe=1c568b626c) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [25bd8ff761](https://linux-hardware.org/?probe=25bd8ff761) | Jul 14, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [9868eab45f](https://linux-hardware.org/?probe=9868eab45f) | Jul 14, 2023 |
| Acer          | Aspire TC-380               | Desktop     | [94f5f10ff2](https://linux-hardware.org/?probe=94f5f10ff2) | Jul 14, 2023 |
| HP            | ENVY 15                     | Notebook    | [d69bc2702c](https://linux-hardware.org/?probe=d69bc2702c) | Jul 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [23fef6418b](https://linux-hardware.org/?probe=23fef6418b) | Jul 13, 2023 |
| Dell          | Latitude 5501               | Notebook    | [b10b0e72f0](https://linux-hardware.org/?probe=b10b0e72f0) | Jul 13, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [6c08fefa24](https://linux-hardware.org/?probe=6c08fefa24) | Jul 13, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [be2db3ecfa](https://linux-hardware.org/?probe=be2db3ecfa) | Jul 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d2dd2ac514](https://linux-hardware.org/?probe=d2dd2ac514) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| ASUSTek       | K8V-X                       | Desktop     | [7562568efe](https://linux-hardware.org/?probe=7562568efe) | Jul 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cd3de89b97](https://linux-hardware.org/?probe=cd3de89b97) | Jul 12, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [b9b5f89f0c](https://linux-hardware.org/?probe=b9b5f89f0c) | Jul 12, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [bc78a01502](https://linux-hardware.org/?probe=bc78a01502) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [c01febb128](https://linux-hardware.org/?probe=c01febb128) | Jul 12, 2023 |
| HP            | ProLiant DL580 G7           | Server      | [cf5953ed12](https://linux-hardware.org/?probe=cf5953ed12) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [a4f7584ee4](https://linux-hardware.org/?probe=a4f7584ee4) | Jul 12, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [40281279ab](https://linux-hardware.org/?probe=40281279ab) | Jul 12, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [f7e7c29964](https://linux-hardware.org/?probe=f7e7c29964) | Jul 12, 2023 |
| Acer          | EG31M R01-B1                | Desktop     | [dbc5e1d5db](https://linux-hardware.org/?probe=dbc5e1d5db) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | Desktop     | [12f533494b](https://linux-hardware.org/?probe=12f533494b) | Jul 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4347661295](https://linux-hardware.org/?probe=4347661295) | Jul 11, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [aac3e629d3](https://linux-hardware.org/?probe=aac3e629d3) | Jul 11, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e9a45b4e27](https://linux-hardware.org/?probe=e9a45b4e27) | Jul 11, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [68ee3dff51](https://linux-hardware.org/?probe=68ee3dff51) | Jul 11, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [cd76343b6e](https://linux-hardware.org/?probe=cd76343b6e) | Jul 11, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [1a540134de](https://linux-hardware.org/?probe=1a540134de) | Jul 11, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [59b334f01a](https://linux-hardware.org/?probe=59b334f01a) | Jul 10, 2023 |
| Panasonic     | CF-C1BD06EFG                | Notebook    | [3b5ab4416a](https://linux-hardware.org/?probe=3b5ab4416a) | Jul 10, 2023 |
| ASRock        | A75 Extreme6                | Desktop     | [1c0eb1b3ea](https://linux-hardware.org/?probe=1c0eb1b3ea) | Jul 10, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [480ee8d732](https://linux-hardware.org/?probe=480ee8d732) | Jul 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [71329b9909](https://linux-hardware.org/?probe=71329b9909) | Jul 10, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [b7d5b7b224](https://linux-hardware.org/?probe=b7d5b7b224) | Jul 10, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [29c15fc4d2](https://linux-hardware.org/?probe=29c15fc4d2) | Jul 10, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [9f920e8a7e](https://linux-hardware.org/?probe=9f920e8a7e) | Jul 10, 2023 |
| Dell          | Latitude E6440              | Notebook    | [6265e6109a](https://linux-hardware.org/?probe=6265e6109a) | Jul 09, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [483109bdd9](https://linux-hardware.org/?probe=483109bdd9) | Jul 09, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [acdb08441f](https://linux-hardware.org/?probe=acdb08441f) | Jul 09, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [c01a765f59](https://linux-hardware.org/?probe=c01a765f59) | Jul 09, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [7d98a62bcc](https://linux-hardware.org/?probe=7d98a62bcc) | Jul 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [10cf2c3aa5](https://linux-hardware.org/?probe=10cf2c3aa5) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [a1b896bd04](https://linux-hardware.org/?probe=a1b896bd04) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | Notebook    | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [b4f20e8bc3](https://linux-hardware.org/?probe=b4f20e8bc3) | Jul 08, 2023 |
| HP            | 82A1                        | Desktop     | [2db1718d8f](https://linux-hardware.org/?probe=2db1718d8f) | Jul 08, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [018447554a](https://linux-hardware.org/?probe=018447554a) | Jul 08, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [aa3a981cb3](https://linux-hardware.org/?probe=aa3a981cb3) | Jul 08, 2023 |
| Acer          | TravelMate 5335             | Notebook    | [7422cf6091](https://linux-hardware.org/?probe=7422cf6091) | Jul 08, 2023 |
| Acer          | Chapala                     | Notebook    | [6ea600326f](https://linux-hardware.org/?probe=6ea600326f) | Jul 08, 2023 |
| HP            | 82A1                        | Desktop     | [1bab189e8d](https://linux-hardware.org/?probe=1bab189e8d) | Jul 08, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [dde4874147](https://linux-hardware.org/?probe=dde4874147) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [6a739102d0](https://linux-hardware.org/?probe=6a739102d0) | Jul 08, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [f1d3e3070e](https://linux-hardware.org/?probe=f1d3e3070e) | Jul 07, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [9c6ce21357](https://linux-hardware.org/?probe=9c6ce21357) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [f2203ae88e](https://linux-hardware.org/?probe=f2203ae88e) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [e2adf09ecf](https://linux-hardware.org/?probe=e2adf09ecf) | Jul 07, 2023 |
| Olidata       | Stainer 8050                | Notebook    | [beb3c029a6](https://linux-hardware.org/?probe=beb3c029a6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [dbb5eb75b8](https://linux-hardware.org/?probe=dbb5eb75b8) | Jul 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [e484073491](https://linux-hardware.org/?probe=e484073491) | Jul 07, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [276cdeb14d](https://linux-hardware.org/?probe=276cdeb14d) | Jul 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [e134f78b10](https://linux-hardware.org/?probe=e134f78b10) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| HP            | 82FE 11                     | Desktop     | [fcac934bde](https://linux-hardware.org/?probe=fcac934bde) | Jul 06, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [2cb98a7961](https://linux-hardware.org/?probe=2cb98a7961) | Jul 06, 2023 |
| Dell          | Precision M6800             | Notebook    | [4b8d02d04a](https://linux-hardware.org/?probe=4b8d02d04a) | Jul 06, 2023 |
| Dell          | Precision M6800             | Notebook    | [239c3ea2b9](https://linux-hardware.org/?probe=239c3ea2b9) | Jul 06, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [79bd04036c](https://linux-hardware.org/?probe=79bd04036c) | Jul 05, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [d6153317bf](https://linux-hardware.org/?probe=d6153317bf) | Jul 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [037db5066a](https://linux-hardware.org/?probe=037db5066a) | Jul 05, 2023 |
| Dell          | Latitude 7440               | Notebook    | [2efee1eb6c](https://linux-hardware.org/?probe=2efee1eb6c) | Jul 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [44140c28bb](https://linux-hardware.org/?probe=44140c28bb) | Jul 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a4b93f17c2](https://linux-hardware.org/?probe=a4b93f17c2) | Jul 05, 2023 |
| Sony          | VGN-NS21M_W                 | Notebook    | [36b9bc971f](https://linux-hardware.org/?probe=36b9bc971f) | Jul 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5699e37170](https://linux-hardware.org/?probe=5699e37170) | Jul 04, 2023 |
| MSI           | Creator 15M A9SD            | Notebook    | [84c85a8969](https://linux-hardware.org/?probe=84c85a8969) | Jul 04, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | Desktop     | [db376a9857](https://linux-hardware.org/?probe=db376a9857) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [71de589577](https://linux-hardware.org/?probe=71de589577) | Jul 04, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [87873c1e0e](https://linux-hardware.org/?probe=87873c1e0e) | Jul 03, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [1a3814f9d9](https://linux-hardware.org/?probe=1a3814f9d9) | Jul 03, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [78bdc20fe8](https://linux-hardware.org/?probe=78bdc20fe8) | Jul 03, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | Desktop     | [46dbe425b5](https://linux-hardware.org/?probe=46dbe425b5) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [3e88dd8cd6](https://linux-hardware.org/?probe=3e88dd8cd6) | Jul 03, 2023 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [4bede9ff31](https://linux-hardware.org/?probe=4bede9ff31) | Jul 03, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [de620c05a9](https://linux-hardware.org/?probe=de620c05a9) | Jul 03, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [b241427d10](https://linux-hardware.org/?probe=b241427d10) | Jul 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [08fb6b76ce](https://linux-hardware.org/?probe=08fb6b76ce) | Jul 03, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9ebec4e811](https://linux-hardware.org/?probe=9ebec4e811) | Jul 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [349ff94e9f](https://linux-hardware.org/?probe=349ff94e9f) | Jul 02, 2023 |
| Jumper        | EZbook                      | Notebook    | [735e20e770](https://linux-hardware.org/?probe=735e20e770) | Jul 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f341618e19](https://linux-hardware.org/?probe=f341618e19) | Jul 02, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [304cab93f1](https://linux-hardware.org/?probe=304cab93f1) | Jul 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [2ac145f096](https://linux-hardware.org/?probe=2ac145f096) | Jul 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0840377177](https://linux-hardware.org/?probe=0840377177) | Jul 02, 2023 |
| Cincoze       | DX-1000.01.001              | Desktop     | [696453bbab](https://linux-hardware.org/?probe=696453bbab) | Jul 02, 2023 |
| Dell          | Latitude E6420              | Notebook    | [aae88e9000](https://linux-hardware.org/?probe=aae88e9000) | Jul 01, 2023 |
| MSI           | Boston                      | Desktop     | [39a458d562](https://linux-hardware.org/?probe=39a458d562) | Jul 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1b8105097a](https://linux-hardware.org/?probe=1b8105097a) | Jul 01, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [caddb7bcf7](https://linux-hardware.org/?probe=caddb7bcf7) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [fb7e164f62](https://linux-hardware.org/?probe=fb7e164f62) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [2774be84e6](https://linux-hardware.org/?probe=2774be84e6) | Jul 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [97ebc05877](https://linux-hardware.org/?probe=97ebc05877) | Jul 01, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [ec3012e08e](https://linux-hardware.org/?probe=ec3012e08e) | Jul 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [53eedfaac9](https://linux-hardware.org/?probe=53eedfaac9) | Jul 01, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [06d9033522](https://linux-hardware.org/?probe=06d9033522) | Jul 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [4a51b35cb8](https://linux-hardware.org/?probe=4a51b35cb8) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | Notebook    | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [d42cdc8551](https://linux-hardware.org/?probe=d42cdc8551) | Jun 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [7ddc95bb2f](https://linux-hardware.org/?probe=7ddc95bb2f) | Jun 30, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [48d04d8282](https://linux-hardware.org/?probe=48d04d8282) | Jun 30, 2023 |
| Dell          | Latitude 5521               | Notebook    | [3a8f3794aa](https://linux-hardware.org/?probe=3a8f3794aa) | Jun 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [1db11a4fa9](https://linux-hardware.org/?probe=1db11a4fa9) | Jun 29, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [4ad54ee28d](https://linux-hardware.org/?probe=4ad54ee28d) | Jun 29, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [a7617c12c5](https://linux-hardware.org/?probe=a7617c12c5) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| Dell          | Latitude 7440               | Notebook    | [24f85667ac](https://linux-hardware.org/?probe=24f85667ac) | Jun 28, 2023 |
| Dell          | 0XJ5V0 A03                  | Desktop     | [a1595a590c](https://linux-hardware.org/?probe=a1595a590c) | Jun 28, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | Desktop     | [1114cf7328](https://linux-hardware.org/?probe=1114cf7328) | Jun 28, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [0251f7e1ab](https://linux-hardware.org/?probe=0251f7e1ab) | Jun 27, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [cb47380993](https://linux-hardware.org/?probe=cb47380993) | Jun 27, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | Notebook    | [7f0ae1c657](https://linux-hardware.org/?probe=7f0ae1c657) | Jun 27, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [8ea6d92813](https://linux-hardware.org/?probe=8ea6d92813) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [24d66c058b](https://linux-hardware.org/?probe=24d66c058b) | Jun 27, 2023 |
| HP            | ENVY 15                     | Notebook    | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | Notebook    | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | Notebook    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [f664b455eb](https://linux-hardware.org/?probe=f664b455eb) | Jun 26, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [09acdc7c4a](https://linux-hardware.org/?probe=09acdc7c4a) | Jun 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [5a9f85740e](https://linux-hardware.org/?probe=5a9f85740e) | Jun 26, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fe7974bbc9](https://linux-hardware.org/?probe=fe7974bbc9) | Jun 26, 2023 |
| HP            | Pavilion dv6                | Notebook    | [3051c4ac4e](https://linux-hardware.org/?probe=3051c4ac4e) | Jun 26, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [8a0a603eef](https://linux-hardware.org/?probe=8a0a603eef) | Jun 26, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [12cc9ac9dc](https://linux-hardware.org/?probe=12cc9ac9dc) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Google        | Sasuke                      | Notebook    | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [6f1d7a6089](https://linux-hardware.org/?probe=6f1d7a6089) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | Notebook    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| HP            | 8437                        | Desktop     | [477b6d5623](https://linux-hardware.org/?probe=477b6d5623) | Jun 24, 2023 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [d91441b98b](https://linux-hardware.org/?probe=d91441b98b) | Jun 24, 2023 |
| Microtech     | CoreBook Lite               | Notebook    | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [cdc135487b](https://linux-hardware.org/?probe=cdc135487b) | Jun 24, 2023 |
| MSI           | MS-7360                     | Desktop     | [9a0d46b069](https://linux-hardware.org/?probe=9a0d46b069) | Jun 23, 2023 |
| HP            | Presario CQ56               | Notebook    | [5a8991a97b](https://linux-hardware.org/?probe=5a8991a97b) | Jun 23, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2fb45a65c8](https://linux-hardware.org/?probe=2fb45a65c8) | Jun 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ae8e0ef85b](https://linux-hardware.org/?probe=ae8e0ef85b) | Jun 23, 2023 |
| HP            | ENVY 15                     | Notebook    | [3918cca1e5](https://linux-hardware.org/?probe=3918cca1e5) | Jun 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fa58c1a1fd](https://linux-hardware.org/?probe=fa58c1a1fd) | Jun 22, 2023 |
| Acer          | Aspire 7720G                | Notebook    | [a8e44a5ab1](https://linux-hardware.org/?probe=a8e44a5ab1) | Jun 22, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a58868d782](https://linux-hardware.org/?probe=a58868d782) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| IP3 Techno... | ACB19                       | Mini pc     | [db5c45e4f7](https://linux-hardware.org/?probe=db5c45e4f7) | Jun 22, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [223967ea1d](https://linux-hardware.org/?probe=223967ea1d) | Jun 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [44050251e9](https://linux-hardware.org/?probe=44050251e9) | Jun 22, 2023 |
| Sony          | VGN-NS21M_W                 | Notebook    | [6813d6589e](https://linux-hardware.org/?probe=6813d6589e) | Jun 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d4f506e331](https://linux-hardware.org/?probe=d4f506e331) | Jun 21, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [197d2f4c7c](https://linux-hardware.org/?probe=197d2f4c7c) | Jun 21, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [49f6cc6986](https://linux-hardware.org/?probe=49f6cc6986) | Jun 20, 2023 |
| Intel         | X79                         | Desktop     | [8c50d3b5e8](https://linux-hardware.org/?probe=8c50d3b5e8) | Jun 20, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | Notebook    | [42ba3d75e5](https://linux-hardware.org/?probe=42ba3d75e5) | Jun 20, 2023 |
| AMI           | Intel                       | Desktop     | [94c1b63cc6](https://linux-hardware.org/?probe=94c1b63cc6) | Jun 20, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [6e2f7d8295](https://linux-hardware.org/?probe=6e2f7d8295) | Jun 20, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [35de204113](https://linux-hardware.org/?probe=35de204113) | Jun 19, 2023 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [406b650f19](https://linux-hardware.org/?probe=406b650f19) | Jun 19, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [0f15219a46](https://linux-hardware.org/?probe=0f15219a46) | Jun 19, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [7412881615](https://linux-hardware.org/?probe=7412881615) | Jun 18, 2023 |
| MSI           | PS63 Modern 8RC             | Notebook    | [f540e88555](https://linux-hardware.org/?probe=f540e88555) | Jun 18, 2023 |
| Dell          | Latitude 5520               | Notebook    | [09da4ee3c4](https://linux-hardware.org/?probe=09da4ee3c4) | Jun 18, 2023 |
| Dell          | Latitude 5520               | Notebook    | [5e70c1929c](https://linux-hardware.org/?probe=5e70c1929c) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [46692b99cb](https://linux-hardware.org/?probe=46692b99cb) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| MSI           | Boston                      | Desktop     | [8bc41737a5](https://linux-hardware.org/?probe=8bc41737a5) | Jun 17, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [834705c660](https://linux-hardware.org/?probe=834705c660) | Jun 17, 2023 |
| HP            | ENVY 15                     | Notebook    | [10a4cb8865](https://linux-hardware.org/?probe=10a4cb8865) | Jun 17, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [23b64edd39](https://linux-hardware.org/?probe=23b64edd39) | Jun 17, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [4dae4ff7c6](https://linux-hardware.org/?probe=4dae4ff7c6) | Jun 16, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [bbc15bef9c](https://linux-hardware.org/?probe=bbc15bef9c) | Jun 15, 2023 |
| Supermicro    | C7X99-OCE                   | Server      | [3d606bb171](https://linux-hardware.org/?probe=3d606bb171) | Jun 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [f3d2cd0976](https://linux-hardware.org/?probe=f3d2cd0976) | Jun 15, 2023 |
| Acer          | Aspire 1810T                | Notebook    | [1b1d11f461](https://linux-hardware.org/?probe=1b1d11f461) | Jun 14, 2023 |
| Samsung       | N130                        | Notebook    | [3efb763643](https://linux-hardware.org/?probe=3efb763643) | Jun 14, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [e37b06f2b0](https://linux-hardware.org/?probe=e37b06f2b0) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [e6ac28ac73](https://linux-hardware.org/?probe=e6ac28ac73) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [ca27fe4c19](https://linux-hardware.org/?probe=ca27fe4c19) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [511317bdbc](https://linux-hardware.org/?probe=511317bdbc) | Jun 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [f3b25c0959](https://linux-hardware.org/?probe=f3b25c0959) | Jun 14, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [11bb40ef32](https://linux-hardware.org/?probe=11bb40ef32) | Jun 13, 2023 |
| HP            | 18E7                        | Desktop     | [1be1b42bb4](https://linux-hardware.org/?probe=1be1b42bb4) | Jun 13, 2023 |
| HP            | 18E7                        | Desktop     | [cbf4019da2](https://linux-hardware.org/?probe=cbf4019da2) | Jun 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Dell          | Latitude E5540              | Notebook    | [029d51e57f](https://linux-hardware.org/?probe=029d51e57f) | Jun 13, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [d910ebe7bb](https://linux-hardware.org/?probe=d910ebe7bb) | Jun 13, 2023 |
| Dell          | Latitude E7250              | Notebook    | [cc9fc2bace](https://linux-hardware.org/?probe=cc9fc2bace) | Jun 13, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [d9cd48b67d](https://linux-hardware.org/?probe=d9cd48b67d) | Jun 12, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | Desktop     | [5c2eef3678](https://linux-hardware.org/?probe=5c2eef3678) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [017c7fd564](https://linux-hardware.org/?probe=017c7fd564) | Jun 11, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [e31b33ae5e](https://linux-hardware.org/?probe=e31b33ae5e) | Jun 11, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [180abd0b90](https://linux-hardware.org/?probe=180abd0b90) | Jun 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [d276b58f38](https://linux-hardware.org/?probe=d276b58f38) | Jun 10, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [98a4edb43d](https://linux-hardware.org/?probe=98a4edb43d) | Jun 10, 2023 |
| Intel         | NUC11ATBC2 M53055-202       | Mini pc     | [81aee70d12](https://linux-hardware.org/?probe=81aee70d12) | Jun 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bdca36306b](https://linux-hardware.org/?probe=bdca36306b) | Jun 10, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c4063bcf07](https://linux-hardware.org/?probe=c4063bcf07) | Jun 09, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9016ad81ae](https://linux-hardware.org/?probe=9016ad81ae) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [5648ca2620](https://linux-hardware.org/?probe=5648ca2620) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [30dbebd931](https://linux-hardware.org/?probe=30dbebd931) | Jun 09, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [5ad9f9e0bf](https://linux-hardware.org/?probe=5ad9f9e0bf) | Jun 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [797dea9c96](https://linux-hardware.org/?probe=797dea9c96) | Jun 09, 2023 |
| MSI           | H81I                        | Desktop     | [c7c19346a2](https://linux-hardware.org/?probe=c7c19346a2) | Jun 09, 2023 |
| HP            | 09E0h                       | Desktop     | [b6bb01441c](https://linux-hardware.org/?probe=b6bb01441c) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [b88712538e](https://linux-hardware.org/?probe=b88712538e) | Jun 09, 2023 |
| HP            | 2B35                        | Desktop     | [5921b94b60](https://linux-hardware.org/?probe=5921b94b60) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [51bfdec531](https://linux-hardware.org/?probe=51bfdec531) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [eea4cea0e0](https://linux-hardware.org/?probe=eea4cea0e0) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [d6a8e02362](https://linux-hardware.org/?probe=d6a8e02362) | Jun 08, 2023 |
| HP            | 87A4 10100                  | All in one  | [3c67e34a5e](https://linux-hardware.org/?probe=3c67e34a5e) | Jun 08, 2023 |
| ASUSTek       | X580VN                      | Notebook    | [8c1cf3f164](https://linux-hardware.org/?probe=8c1cf3f164) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [fdb80f6e89](https://linux-hardware.org/?probe=fdb80f6e89) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f4e1a7a712](https://linux-hardware.org/?probe=f4e1a7a712) | Jun 08, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [d5d7ffe9df](https://linux-hardware.org/?probe=d5d7ffe9df) | Jun 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [82d0019a0b](https://linux-hardware.org/?probe=82d0019a0b) | Jun 08, 2023 |
| Acer          | AO722                       | Notebook    | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [75a37cd4c8](https://linux-hardware.org/?probe=75a37cd4c8) | Jun 07, 2023 |
| HP            | 1905                        | Desktop     | [0617f4e698](https://linux-hardware.org/?probe=0617f4e698) | Jun 07, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [2ad409f60a](https://linux-hardware.org/?probe=2ad409f60a) | Jun 07, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [bbfcf4a3be](https://linux-hardware.org/?probe=bbfcf4a3be) | Jun 07, 2023 |
| Dell          | Latitude 5300               | Notebook    | [1eea10cfa3](https://linux-hardware.org/?probe=1eea10cfa3) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [23b41d16db](https://linux-hardware.org/?probe=23b41d16db) | Jun 06, 2023 |
| Acer          | AO722                       | Notebook    | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [f395c0f429](https://linux-hardware.org/?probe=f395c0f429) | Jun 06, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [85ec51dbf3](https://linux-hardware.org/?probe=85ec51dbf3) | Jun 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [c20dd8572a](https://linux-hardware.org/?probe=c20dd8572a) | Jun 05, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [8d150fb2b0](https://linux-hardware.org/?probe=8d150fb2b0) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [450d20f29d](https://linux-hardware.org/?probe=450d20f29d) | Jun 05, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [e3738c1f5a](https://linux-hardware.org/?probe=e3738c1f5a) | Jun 05, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [cc575f0073](https://linux-hardware.org/?probe=cc575f0073) | Jun 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [292269611c](https://linux-hardware.org/?probe=292269611c) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [b4f165f28d](https://linux-hardware.org/?probe=b4f165f28d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e0ce9df73c](https://linux-hardware.org/?probe=e0ce9df73c) | Jun 05, 2023 |
| MSI           | Boston                      | Desktop     | [9f5efc29ad](https://linux-hardware.org/?probe=9f5efc29ad) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3af6e03b1c](https://linux-hardware.org/?probe=3af6e03b1c) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | Notebook    | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4b162cac99](https://linux-hardware.org/?probe=4b162cac99) | Jun 04, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [3ef3c9ec82](https://linux-hardware.org/?probe=3ef3c9ec82) | Jun 04, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8b14da5cf8](https://linux-hardware.org/?probe=8b14da5cf8) | Jun 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [70e5950511](https://linux-hardware.org/?probe=70e5950511) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [19ed8e22e6](https://linux-hardware.org/?probe=19ed8e22e6) | Jun 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ba2dfac7ae](https://linux-hardware.org/?probe=ba2dfac7ae) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3d911ac9c9](https://linux-hardware.org/?probe=3d911ac9c9) | Jun 03, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [fe03659a55](https://linux-hardware.org/?probe=fe03659a55) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [959b76650d](https://linux-hardware.org/?probe=959b76650d) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [35fff15a30](https://linux-hardware.org/?probe=35fff15a30) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [54fcb811b8](https://linux-hardware.org/?probe=54fcb811b8) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [0a536c1198](https://linux-hardware.org/?probe=0a536c1198) | Jun 01, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5430a83fca](https://linux-hardware.org/?probe=5430a83fca) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [fcc2d0ed39](https://linux-hardware.org/?probe=fcc2d0ed39) | Jun 01, 2023 |
| HP            | 18E7                        | Desktop     | [a3f557389e](https://linux-hardware.org/?probe=a3f557389e) | Jun 01, 2023 |
| ASRock        | H310M-HDV                   | Desktop     | [3dc5138ecd](https://linux-hardware.org/?probe=3dc5138ecd) | Jun 01, 2023 |
| Fujitsu Si... | D2740-A2 S26361-D2740-A2    | Desktop     | [165491db1f](https://linux-hardware.org/?probe=165491db1f) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [9324563727](https://linux-hardware.org/?probe=9324563727) | Jun 01, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [778e78d2a5](https://linux-hardware.org/?probe=778e78d2a5) | Jun 01, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [aaeac4c226](https://linux-hardware.org/?probe=aaeac4c226) | Jun 01, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [cfabc605f7](https://linux-hardware.org/?probe=cfabc605f7) | Jun 01, 2023 |
| Acer          | WG43M                       | Desktop     | [cdd78e1cac](https://linux-hardware.org/?probe=cdd78e1cac) | May 31, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [0b0c375bb8](https://linux-hardware.org/?probe=0b0c375bb8) | May 31, 2023 |
| Olidata       | Tehom cw4900                | Notebook    | [f5b147962f](https://linux-hardware.org/?probe=f5b147962f) | May 31, 2023 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [810f6b35ea](https://linux-hardware.org/?probe=810f6b35ea) | May 31, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [8630cfad52](https://linux-hardware.org/?probe=8630cfad52) | May 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [bfcb7f950d](https://linux-hardware.org/?probe=bfcb7f950d) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [bd2319fd67](https://linux-hardware.org/?probe=bd2319fd67) | May 31, 2023 |
| Jumper        | EZbook                      | Notebook    | [3ccf2e1365](https://linux-hardware.org/?probe=3ccf2e1365) | May 31, 2023 |
| HP            | ENVY 15                     | Notebook    | [ad3cf182fe](https://linux-hardware.org/?probe=ad3cf182fe) | May 30, 2023 |
| HP            | ENVY 15                     | Notebook    | [5acbfb03f4](https://linux-hardware.org/?probe=5acbfb03f4) | May 30, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [de30e713bf](https://linux-hardware.org/?probe=de30e713bf) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [bb50e13268](https://linux-hardware.org/?probe=bb50e13268) | May 30, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [48359795cc](https://linux-hardware.org/?probe=48359795cc) | May 30, 2023 |
| HP            | Pavilion 15                 | Notebook    | [ca18fafda8](https://linux-hardware.org/?probe=ca18fafda8) | May 29, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4679a6e565](https://linux-hardware.org/?probe=4679a6e565) | May 29, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [ec89dcb694](https://linux-hardware.org/?probe=ec89dcb694) | May 29, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Dell          | Latitude E5470              | Notebook    | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2f44574d7c](https://linux-hardware.org/?probe=2f44574d7c) | May 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [81a267d02b](https://linux-hardware.org/?probe=81a267d02b) | May 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [5e146ef326](https://linux-hardware.org/?probe=5e146ef326) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [6ce88925e9](https://linux-hardware.org/?probe=6ce88925e9) | May 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c7afdbbd76](https://linux-hardware.org/?probe=c7afdbbd76) | May 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [db9c87ce89](https://linux-hardware.org/?probe=db9c87ce89) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [1eecbd5808](https://linux-hardware.org/?probe=1eecbd5808) | May 27, 2023 |
| HP            | G42                         | Notebook    | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e21476b6d2](https://linux-hardware.org/?probe=e21476b6d2) | May 26, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [433b367e58](https://linux-hardware.org/?probe=433b367e58) | May 26, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [ac85063e46](https://linux-hardware.org/?probe=ac85063e46) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| Mediacom      | SMARTBOOK ONE               | Notebook    | [ad010a6b3e](https://linux-hardware.org/?probe=ad010a6b3e) | May 25, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [530b841978](https://linux-hardware.org/?probe=530b841978) | May 25, 2023 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [4c9595e6ea](https://linux-hardware.org/?probe=4c9595e6ea) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [978ae98d6e](https://linux-hardware.org/?probe=978ae98d6e) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [e484eaf025](https://linux-hardware.org/?probe=e484eaf025) | May 24, 2023 |
| Dell          | Precision 3571              | Notebook    | [3806fcdb9c](https://linux-hardware.org/?probe=3806fcdb9c) | May 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1280876877](https://linux-hardware.org/?probe=1280876877) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [01e2285654](https://linux-hardware.org/?probe=01e2285654) | May 24, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [0dfd1ede62](https://linux-hardware.org/?probe=0dfd1ede62) | May 23, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [9f7d80df58](https://linux-hardware.org/?probe=9f7d80df58) | May 23, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [e177bb8db5](https://linux-hardware.org/?probe=e177bb8db5) | May 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [223ab4f15c](https://linux-hardware.org/?probe=223ab4f15c) | May 23, 2023 |
| HP            | ENVY 15                     | Notebook    | [85a97390d5](https://linux-hardware.org/?probe=85a97390d5) | May 23, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [eef57d6c26](https://linux-hardware.org/?probe=eef57d6c26) | May 23, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [1ec3710265](https://linux-hardware.org/?probe=1ec3710265) | May 23, 2023 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [d0312b1a56](https://linux-hardware.org/?probe=d0312b1a56) | May 23, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f9f3305d0b](https://linux-hardware.org/?probe=f9f3305d0b) | May 23, 2023 |
| HP            | 2AF3                        | Desktop     | [e70a1c12fb](https://linux-hardware.org/?probe=e70a1c12fb) | May 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [14b20068ca](https://linux-hardware.org/?probe=14b20068ca) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cc7b8d0a8](https://linux-hardware.org/?probe=9cc7b8d0a8) | May 22, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a8e6f277e2](https://linux-hardware.org/?probe=a8e6f277e2) | May 22, 2023 |
| Dell          | Latitude E6230              | Notebook    | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5cb11eee20](https://linux-hardware.org/?probe=5cb11eee20) | May 22, 2023 |
| HP            | ENVY 15                     | Notebook    | [21a38278ca](https://linux-hardware.org/?probe=21a38278ca) | May 21, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [7bc8f5e875](https://linux-hardware.org/?probe=7bc8f5e875) | May 21, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [55a289b426](https://linux-hardware.org/?probe=55a289b426) | May 21, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [916d381f2f](https://linux-hardware.org/?probe=916d381f2f) | May 21, 2023 |
| Intel         | NUC11ATBC2 M53055-202       | Mini pc     | [6f50de46aa](https://linux-hardware.org/?probe=6f50de46aa) | May 21, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [2eb8cdff34](https://linux-hardware.org/?probe=2eb8cdff34) | May 21, 2023 |
| ASUSTek       | N53TK                       | Notebook    | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [c8c091e2d8](https://linux-hardware.org/?probe=c8c091e2d8) | May 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [8ec7bb4682](https://linux-hardware.org/?probe=8ec7bb4682) | May 21, 2023 |
| Acer          | Aspire V3-572G              | Notebook    | [8f1be2d961](https://linux-hardware.org/?probe=8f1be2d961) | May 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| Dell          | 0FGCC7 A01                  | Server      | [3900d6a330](https://linux-hardware.org/?probe=3900d6a330) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [b08ca84ea8](https://linux-hardware.org/?probe=b08ca84ea8) | May 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [6b5b728c7e](https://linux-hardware.org/?probe=6b5b728c7e) | May 20, 2023 |
| HP            | 8437                        | Desktop     | [d41a0c8439](https://linux-hardware.org/?probe=d41a0c8439) | May 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [c7157cc723](https://linux-hardware.org/?probe=c7157cc723) | May 20, 2023 |
| HP            | Pavilion dv3                | Notebook    | [34c6a2c14a](https://linux-hardware.org/?probe=34c6a2c14a) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1f6220f21a](https://linux-hardware.org/?probe=1f6220f21a) | May 19, 2023 |
| HP            | 8437                        | Desktop     | [ceacc79bf6](https://linux-hardware.org/?probe=ceacc79bf6) | May 19, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [76a17acffb](https://linux-hardware.org/?probe=76a17acffb) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [2d5184956b](https://linux-hardware.org/?probe=2d5184956b) | May 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [49c702a8c9](https://linux-hardware.org/?probe=49c702a8c9) | May 18, 2023 |
| ASUSTek       | P5B                         | Desktop     | [9d815bcd44](https://linux-hardware.org/?probe=9d815bcd44) | May 18, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [95fcf79dd4](https://linux-hardware.org/?probe=95fcf79dd4) | May 18, 2023 |
| ASUSTek       | P5B                         | Desktop     | [70be41e795](https://linux-hardware.org/?probe=70be41e795) | May 18, 2023 |
| ASUSTek       | X555LPB                     | Notebook    | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [65638219a5](https://linux-hardware.org/?probe=65638219a5) | May 18, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [c9d1849e5e](https://linux-hardware.org/?probe=c9d1849e5e) | May 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [62e064b7d0](https://linux-hardware.org/?probe=62e064b7d0) | May 18, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [790c5137ba](https://linux-hardware.org/?probe=790c5137ba) | May 18, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [bb4c9d6b4c](https://linux-hardware.org/?probe=bb4c9d6b4c) | May 17, 2023 |
| HP            | 3048h                       | Desktop     | [9e65995057](https://linux-hardware.org/?probe=9e65995057) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [b5aef01bc9](https://linux-hardware.org/?probe=b5aef01bc9) | May 17, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [7f3487434e](https://linux-hardware.org/?probe=7f3487434e) | May 17, 2023 |
| HP            | 09F8h                       | Desktop     | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | Desktop     | [281042ebf0](https://linux-hardware.org/?probe=281042ebf0) | May 17, 2023 |
| HP            | ENVY 15                     | Notebook    | [4576cea8b0](https://linux-hardware.org/?probe=4576cea8b0) | May 17, 2023 |
| HP            | 18E5                        | Desktop     | [5e25e2156a](https://linux-hardware.org/?probe=5e25e2156a) | May 16, 2023 |
| ASUSTek       | UX305FA                     | Notebook    | [36cb231f34](https://linux-hardware.org/?probe=36cb231f34) | May 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [bc505434f7](https://linux-hardware.org/?probe=bc505434f7) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [62e3c494bd](https://linux-hardware.org/?probe=62e3c494bd) | May 16, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [212936564d](https://linux-hardware.org/?probe=212936564d) | May 16, 2023 |
| MSI           | MS-7369                     | Desktop     | [4a083f89af](https://linux-hardware.org/?probe=4a083f89af) | May 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [6c64da33ef](https://linux-hardware.org/?probe=6c64da33ef) | May 16, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [755f1920f2](https://linux-hardware.org/?probe=755f1920f2) | May 15, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [16308738b3](https://linux-hardware.org/?probe=16308738b3) | May 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ba609eb1e6](https://linux-hardware.org/?probe=ba609eb1e6) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| Dell          | Precision 7520              | Notebook    | [cbfb960bae](https://linux-hardware.org/?probe=cbfb960bae) | May 15, 2023 |
| Dell          | Precision 7520              | Notebook    | [a42d1a8bf5](https://linux-hardware.org/?probe=a42d1a8bf5) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e9e5b21145](https://linux-hardware.org/?probe=e9e5b21145) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [34c6621991](https://linux-hardware.org/?probe=34c6621991) | May 15, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [fafdf532fb](https://linux-hardware.org/?probe=fafdf532fb) | May 15, 2023 |
| TEXA          | NEMO MINI                   | Tablet      | [81fc17efec](https://linux-hardware.org/?probe=81fc17efec) | May 14, 2023 |
| Lenovo        | ThinkPad X100e 0022CTO      | Notebook    | [842b7a3ee2](https://linux-hardware.org/?probe=842b7a3ee2) | May 14, 2023 |
| TEXA          | NEMO MINI                   | Tablet      | [4b0f306d78](https://linux-hardware.org/?probe=4b0f306d78) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [bb119829d0](https://linux-hardware.org/?probe=bb119829d0) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [020d4612bd](https://linux-hardware.org/?probe=020d4612bd) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [ca65ed1052](https://linux-hardware.org/?probe=ca65ed1052) | May 14, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [0495c4f485](https://linux-hardware.org/?probe=0495c4f485) | May 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [af70e39629](https://linux-hardware.org/?probe=af70e39629) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [1bb0ed422e](https://linux-hardware.org/?probe=1bb0ed422e) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ab7d27081e](https://linux-hardware.org/?probe=ab7d27081e) | May 13, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [24aaf9e627](https://linux-hardware.org/?probe=24aaf9e627) | May 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| HP            | ENVY 15                     | Notebook    | [e188fe21b7](https://linux-hardware.org/?probe=e188fe21b7) | May 12, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | Notebook    | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [4e603c1756](https://linux-hardware.org/?probe=4e603c1756) | May 12, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [5379481e09](https://linux-hardware.org/?probe=5379481e09) | May 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [8375f52559](https://linux-hardware.org/?probe=8375f52559) | May 12, 2023 |
| HP            | 1998                        | Desktop     | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [068ef24174](https://linux-hardware.org/?probe=068ef24174) | May 12, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [00f98129ce](https://linux-hardware.org/?probe=00f98129ce) | May 11, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [80892a273c](https://linux-hardware.org/?probe=80892a273c) | May 11, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [59efd46e1c](https://linux-hardware.org/?probe=59efd46e1c) | May 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [ec8ac0aafd](https://linux-hardware.org/?probe=ec8ac0aafd) | May 11, 2023 |
| Dell          | XPS 9315                    | Notebook    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| ASRock        | Z370 Extreme4               | Desktop     | [bdd9bcedf5](https://linux-hardware.org/?probe=bdd9bcedf5) | May 11, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4d4946eec9](https://linux-hardware.org/?probe=4d4946eec9) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [e03da60adf](https://linux-hardware.org/?probe=e03da60adf) | May 11, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0a3aa24894](https://linux-hardware.org/?probe=0a3aa24894) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| HP            | 2ADE                        | Desktop     | [ef4aa64bd5](https://linux-hardware.org/?probe=ef4aa64bd5) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [922a392eee](https://linux-hardware.org/?probe=922a392eee) | May 09, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4b8927333b](https://linux-hardware.org/?probe=4b8927333b) | May 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [666c071a8b](https://linux-hardware.org/?probe=666c071a8b) | May 09, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | M32CD4-K                    | Desktop     | [0bca52bcc5](https://linux-hardware.org/?probe=0bca52bcc5) | May 09, 2023 |
| Dell          | Latitude E6520              | Notebook    | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | 255 G5                      | Notebook    | [4ed50eeba3](https://linux-hardware.org/?probe=4ed50eeba3) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [4e95a5b88e](https://linux-hardware.org/?probe=4e95a5b88e) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5cbf24306a](https://linux-hardware.org/?probe=5cbf24306a) | May 08, 2023 |
| HP            | 2ADE                        | Desktop     | [bb8ee11580](https://linux-hardware.org/?probe=bb8ee11580) | May 08, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3b4eb54186](https://linux-hardware.org/?probe=3b4eb54186) | May 08, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a4f5dce6d6](https://linux-hardware.org/?probe=a4f5dce6d6) | May 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [100534a570](https://linux-hardware.org/?probe=100534a570) | May 08, 2023 |
| Notebook      | P750ZM                      | Notebook    | [2cbd56abdc](https://linux-hardware.org/?probe=2cbd56abdc) | May 08, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [561202c004](https://linux-hardware.org/?probe=561202c004) | May 07, 2023 |
| HP            | 255 G3                      | Notebook    | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [ecfcb0cab6](https://linux-hardware.org/?probe=ecfcb0cab6) | May 07, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [d6085d9a0b](https://linux-hardware.org/?probe=d6085d9a0b) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [ab9ff23d88](https://linux-hardware.org/?probe=ab9ff23d88) | May 07, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [a21a8395d8](https://linux-hardware.org/?probe=a21a8395d8) | May 07, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [5e91733408](https://linux-hardware.org/?probe=5e91733408) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| HP            | Notebook                    | Notebook    | [cb89261339](https://linux-hardware.org/?probe=cb89261339) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| Lenovo        | IdeaPad U510 20191          | Notebook    | [23414f0626](https://linux-hardware.org/?probe=23414f0626) | May 06, 2023 |
| HP            | Notebook                    | Notebook    | [74f9f1122e](https://linux-hardware.org/?probe=74f9f1122e) | May 06, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [2d5ecba977](https://linux-hardware.org/?probe=2d5ecba977) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [91c6b0d769](https://linux-hardware.org/?probe=91c6b0d769) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [bd885c202d](https://linux-hardware.org/?probe=bd885c202d) | May 05, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [a27c899176](https://linux-hardware.org/?probe=a27c899176) | May 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [af9621c92b](https://linux-hardware.org/?probe=af9621c92b) | May 04, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [20dcc3e6b3](https://linux-hardware.org/?probe=20dcc3e6b3) | May 04, 2023 |
| KUU           | Andes II                    | Notebook    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Sony          | SVF1521G1EW                 | Notebook    | [b84b2ed08a](https://linux-hardware.org/?probe=b84b2ed08a) | May 03, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [80d7446f47](https://linux-hardware.org/?probe=80d7446f47) | May 03, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | Notebook    | [bb924b0c19](https://linux-hardware.org/?probe=bb924b0c19) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [4280750d03](https://linux-hardware.org/?probe=4280750d03) | May 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [f8d80b7cf0](https://linux-hardware.org/?probe=f8d80b7cf0) | May 03, 2023 |
| Samsung       | 750XDA                      | Notebook    | [2e99c882ff](https://linux-hardware.org/?probe=2e99c882ff) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [fd0dee0606](https://linux-hardware.org/?probe=fd0dee0606) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | Notebook    | [d8256a8177](https://linux-hardware.org/?probe=d8256a8177) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | Notebook    | [d4019e13f1](https://linux-hardware.org/?probe=d4019e13f1) | May 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [910824ac40](https://linux-hardware.org/?probe=910824ac40) | May 03, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [50f922927f](https://linux-hardware.org/?probe=50f922927f) | May 03, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [56d274f769](https://linux-hardware.org/?probe=56d274f769) | May 03, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [8c3e5e8d50](https://linux-hardware.org/?probe=8c3e5e8d50) | May 03, 2023 |
| Unknown       | 1.0                         | Desktop     | [5f99ebeed7](https://linux-hardware.org/?probe=5f99ebeed7) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [553a101cf8](https://linux-hardware.org/?probe=553a101cf8) | May 02, 2023 |
| Sony          | VPCF11C5E                   | Notebook    | [77f08d3d00](https://linux-hardware.org/?probe=77f08d3d00) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [5375a4f57c](https://linux-hardware.org/?probe=5375a4f57c) | May 02, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [12d9338aba](https://linux-hardware.org/?probe=12d9338aba) | May 02, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [eaa909b055](https://linux-hardware.org/?probe=eaa909b055) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| HP            | 255 G4                      | Notebook    | [b06ddec94b](https://linux-hardware.org/?probe=b06ddec94b) | May 01, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [01706331eb](https://linux-hardware.org/?probe=01706331eb) | May 01, 2023 |
| HP            | Compaq 8510w                | Notebook    | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| ASRock        | G41M-GS                     | Desktop     | [0824a9c571](https://linux-hardware.org/?probe=0824a9c571) | May 01, 2023 |
| HP            | ENVY 15                     | Notebook    | [935dc183e1](https://linux-hardware.org/?probe=935dc183e1) | May 01, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [bfbda66d8b](https://linux-hardware.org/?probe=bfbda66d8b) | May 01, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [dfe07c7749](https://linux-hardware.org/?probe=dfe07c7749) | May 01, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [ae414cf185](https://linux-hardware.org/?probe=ae414cf185) | May 01, 2023 |
| ASUSTek       | T103HAF                     | Tablet      | [961e13c584](https://linux-hardware.org/?probe=961e13c584) | May 01, 2023 |
| Pegatron      | 2A94                        | Desktop     | [7dcdfa9b9f](https://linux-hardware.org/?probe=7dcdfa9b9f) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [d02d21f47a](https://linux-hardware.org/?probe=d02d21f47a) | May 01, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [26681d2879](https://linux-hardware.org/?probe=26681d2879) | May 01, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [577b5e8f51](https://linux-hardware.org/?probe=577b5e8f51) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b2adc0ae5](https://linux-hardware.org/?probe=1b2adc0ae5) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [4ac55a6bbe](https://linux-hardware.org/?probe=4ac55a6bbe) | Apr 30, 2023 |
| HP            | Compaq 6720s                | Notebook    | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [94118ab632](https://linux-hardware.org/?probe=94118ab632) | Apr 30, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [7dcb847a6c](https://linux-hardware.org/?probe=7dcb847a6c) | Apr 30, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [77f87da085](https://linux-hardware.org/?probe=77f87da085) | Apr 29, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [e585f66f17](https://linux-hardware.org/?probe=e585f66f17) | Apr 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [4801547d54](https://linux-hardware.org/?probe=4801547d54) | Apr 29, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8ea78b28f1](https://linux-hardware.org/?probe=8ea78b28f1) | Apr 29, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [bd4c84da60](https://linux-hardware.org/?probe=bd4c84da60) | Apr 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [19bb30e27a](https://linux-hardware.org/?probe=19bb30e27a) | Apr 29, 2023 |
| HP            | 1998                        | Desktop     | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| HP            | 339A                        | Desktop     | [4f9a0b2661](https://linux-hardware.org/?probe=4f9a0b2661) | Apr 28, 2023 |
| Rockchip      | Unknown                     | Soc         | [5236b9452c](https://linux-hardware.org/?probe=5236b9452c) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | Desktop     | [94f2408a63](https://linux-hardware.org/?probe=94f2408a63) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | Desktop     | [76c36882d9](https://linux-hardware.org/?probe=76c36882d9) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [25d0c90e31](https://linux-hardware.org/?probe=25d0c90e31) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b6bd42eb71](https://linux-hardware.org/?probe=b6bd42eb71) | Apr 27, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5108a05d49](https://linux-hardware.org/?probe=5108a05d49) | Apr 27, 2023 |
| Dell          | Latitude E6400              | Notebook    | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [a5d42a7b78](https://linux-hardware.org/?probe=a5d42a7b78) | Apr 26, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [7a2503959a](https://linux-hardware.org/?probe=7a2503959a) | Apr 26, 2023 |
| Acer          | TravelMate 6593             | Notebook    | [58dce8147e](https://linux-hardware.org/?probe=58dce8147e) | Apr 26, 2023 |
| HP            | ENVY 15                     | Notebook    | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [82bd4b0d20](https://linux-hardware.org/?probe=82bd4b0d20) | Apr 26, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [98ed5e9a2e](https://linux-hardware.org/?probe=98ed5e9a2e) | Apr 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [c6387003fc](https://linux-hardware.org/?probe=c6387003fc) | Apr 25, 2023 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [405bcbb43c](https://linux-hardware.org/?probe=405bcbb43c) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [b144f1aa54](https://linux-hardware.org/?probe=b144f1aa54) | Apr 24, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [7ca2bb8871](https://linux-hardware.org/?probe=7ca2bb8871) | Apr 24, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [34278ef67e](https://linux-hardware.org/?probe=34278ef67e) | Apr 24, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [288f3f709c](https://linux-hardware.org/?probe=288f3f709c) | Apr 24, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [2ea3950e19](https://linux-hardware.org/?probe=2ea3950e19) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| MSI           | B460M PRO-VDH               | Desktop     | [f7709c23a1](https://linux-hardware.org/?probe=f7709c23a1) | Apr 24, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [c59dbdea18](https://linux-hardware.org/?probe=c59dbdea18) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| AMI           | Intel                       | Desktop     | [62d06b215e](https://linux-hardware.org/?probe=62d06b215e) | Apr 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [fcf8a7bdb4](https://linux-hardware.org/?probe=fcf8a7bdb4) | Apr 23, 2023 |
| Dell          | Inspiron MP061              | Notebook    | [2b25a48030](https://linux-hardware.org/?probe=2b25a48030) | Apr 23, 2023 |
| ASRock        | Z77 Pro3                    | Desktop     | [2f4b412834](https://linux-hardware.org/?probe=2f4b412834) | Apr 22, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5cceab0ac3](https://linux-hardware.org/?probe=5cceab0ac3) | Apr 22, 2023 |
| ASUSTek       | ET1602                      | Desktop     | [637fb8c9ce](https://linux-hardware.org/?probe=637fb8c9ce) | Apr 22, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [46516c6f3a](https://linux-hardware.org/?probe=46516c6f3a) | Apr 22, 2023 |
| ASRock        | H61M/U3S3                   | Desktop     | [8fd7aea5ea](https://linux-hardware.org/?probe=8fd7aea5ea) | Apr 22, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3165ab3194](https://linux-hardware.org/?probe=3165ab3194) | Apr 22, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [47ea666f74](https://linux-hardware.org/?probe=47ea666f74) | Apr 21, 2023 |
| HP            | Compaq 6735s                | Notebook    | [9a23d08368](https://linux-hardware.org/?probe=9a23d08368) | Apr 21, 2023 |
| HP            | Compaq 6735s                | Notebook    | [6b255d5f07](https://linux-hardware.org/?probe=6b255d5f07) | Apr 21, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [644ea805a9](https://linux-hardware.org/?probe=644ea805a9) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| ELSKY         | M219F-6C                    | Desktop     | [5f41223856](https://linux-hardware.org/?probe=5f41223856) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [aace924665](https://linux-hardware.org/?probe=aace924665) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f7ca0a552d](https://linux-hardware.org/?probe=f7ca0a552d) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [3f390ff38e](https://linux-hardware.org/?probe=3f390ff38e) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [a4f54ca55b](https://linux-hardware.org/?probe=a4f54ca55b) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [b830d8001e](https://linux-hardware.org/?probe=b830d8001e) | Apr 19, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [6aa9d32dda](https://linux-hardware.org/?probe=6aa9d32dda) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9df9b0d25d](https://linux-hardware.org/?probe=9df9b0d25d) | Apr 19, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [1c7cd2fe1d](https://linux-hardware.org/?probe=1c7cd2fe1d) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9db7166b25](https://linux-hardware.org/?probe=9db7166b25) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | Notebook    | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| PC Special... | PCx0Dx                      | Notebook    | [0f82987a84](https://linux-hardware.org/?probe=0f82987a84) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Toshiba       | Kronos 10CUG                | Notebook    | [228e28e6a8](https://linux-hardware.org/?probe=228e28e6a8) | Apr 18, 2023 |
| Otazak        | iPC45                       | Convertible | [1775e826d8](https://linux-hardware.org/?probe=1775e826d8) | Apr 18, 2023 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [175cfb374b](https://linux-hardware.org/?probe=175cfb374b) | Apr 18, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [9437766194](https://linux-hardware.org/?probe=9437766194) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | Notebook    | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [5d56d95ea5](https://linux-hardware.org/?probe=5d56d95ea5) | Apr 18, 2023 |
| HP            | 18E9                        | Desktop     | [8c36235f13](https://linux-hardware.org/?probe=8c36235f13) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [9552ef2174](https://linux-hardware.org/?probe=9552ef2174) | Apr 17, 2023 |
| MSI           | PRO B660-A DDR4             | Desktop     | [b274726abd](https://linux-hardware.org/?probe=b274726abd) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | Desktop     | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9df377aaf2](https://linux-hardware.org/?probe=9df377aaf2) | Apr 17, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [317efe55c2](https://linux-hardware.org/?probe=317efe55c2) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [877464f534](https://linux-hardware.org/?probe=877464f534) | Apr 17, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [0a544df503](https://linux-hardware.org/?probe=0a544df503) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [650deb855e](https://linux-hardware.org/?probe=650deb855e) | Apr 17, 2023 |
| Medion        | E16401                      | Notebook    | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5109f5c8d9](https://linux-hardware.org/?probe=5109f5c8d9) | Apr 17, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [8e99149abe](https://linux-hardware.org/?probe=8e99149abe) | Apr 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [67ce5b3ab1](https://linux-hardware.org/?probe=67ce5b3ab1) | Apr 16, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [bff38bc725](https://linux-hardware.org/?probe=bff38bc725) | Apr 16, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [19a6cddfe0](https://linux-hardware.org/?probe=19a6cddfe0) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4375bd0fb6](https://linux-hardware.org/?probe=4375bd0fb6) | Apr 16, 2023 |
| ASUSTek       | P5E Deluxe                  | Desktop     | [ce0a1adc22](https://linux-hardware.org/?probe=ce0a1adc22) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | Notebook    | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| Google        | Dragonair                   | Notebook    | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Google        | Dragonair                   | Notebook    | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | Notebook    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [e17175b9ac](https://linux-hardware.org/?probe=e17175b9ac) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a51b096e12](https://linux-hardware.org/?probe=a51b096e12) | Apr 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1f524a54fc](https://linux-hardware.org/?probe=1f524a54fc) | Apr 15, 2023 |
| MSI           | 970A-G45                    | Desktop     | [8f62fd1fb1](https://linux-hardware.org/?probe=8f62fd1fb1) | Apr 15, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [91696fe0f2](https://linux-hardware.org/?probe=91696fe0f2) | Apr 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [9f6209111c](https://linux-hardware.org/?probe=9f6209111c) | Apr 14, 2023 |
| Dell          | Latitude 9420               | Notebook    | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [540a259700](https://linux-hardware.org/?probe=540a259700) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [6522f4e2dc](https://linux-hardware.org/?probe=6522f4e2dc) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | Notebook    | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| Cincoze       | DX-1000.01.001              | Desktop     | [fa2c48478a](https://linux-hardware.org/?probe=fa2c48478a) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| MAXDATA       | o.max_5xs                   | Notebook    | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [9ab3fc183a](https://linux-hardware.org/?probe=9ab3fc183a) | Apr 13, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [3b24daf87d](https://linux-hardware.org/?probe=3b24daf87d) | Apr 13, 2023 |
| Chuwi         | UBook X                     | Tablet      | [2e70372d4b](https://linux-hardware.org/?probe=2e70372d4b) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [ea50bc5d28](https://linux-hardware.org/?probe=ea50bc5d28) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [44dca3cd92](https://linux-hardware.org/?probe=44dca3cd92) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [23371691ec](https://linux-hardware.org/?probe=23371691ec) | Apr 12, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [214038993e](https://linux-hardware.org/?probe=214038993e) | Apr 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [9408f6348b](https://linux-hardware.org/?probe=9408f6348b) | Apr 12, 2023 |
| Dell          | XPS 9315                    | Notebook    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [695de52123](https://linux-hardware.org/?probe=695de52123) | Apr 12, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [54a72d7d55](https://linux-hardware.org/?probe=54a72d7d55) | Apr 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [46eba03bed](https://linux-hardware.org/?probe=46eba03bed) | Apr 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [07353da9f6](https://linux-hardware.org/?probe=07353da9f6) | Apr 11, 2023 |
| Packard Be... | EasyNote_MX45               | Notebook    | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| Acer          | H57M01                      | Desktop     | [c62231ca98](https://linux-hardware.org/?probe=c62231ca98) | Apr 11, 2023 |
| Lenovo        | ThinkPad L530 24783B3       | Notebook    | [9cb172cc6b](https://linux-hardware.org/?probe=9cb172cc6b) | Apr 11, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [1a09ecfcd1](https://linux-hardware.org/?probe=1a09ecfcd1) | Apr 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [02d670e0db](https://linux-hardware.org/?probe=02d670e0db) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [dae979ddc0](https://linux-hardware.org/?probe=dae979ddc0) | Apr 11, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [6b1587e21d](https://linux-hardware.org/?probe=6b1587e21d) | Apr 11, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [ce8b386e5b](https://linux-hardware.org/?probe=ce8b386e5b) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [e6e26b16f3](https://linux-hardware.org/?probe=e6e26b16f3) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [07b7bedac7](https://linux-hardware.org/?probe=07b7bedac7) | Apr 10, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [a5bf121256](https://linux-hardware.org/?probe=a5bf121256) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [2e428c73dc](https://linux-hardware.org/?probe=2e428c73dc) | Apr 10, 2023 |
| ASUSTek       | ZN240IC                     | All in one  | [557e50987c](https://linux-hardware.org/?probe=557e50987c) | Apr 09, 2023 |
| ASRock        | Q1900M                      | Desktop     | [6ff7177033](https://linux-hardware.org/?probe=6ff7177033) | Apr 09, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [1f8dc6aa3d](https://linux-hardware.org/?probe=1f8dc6aa3d) | Apr 09, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [ff595db737](https://linux-hardware.org/?probe=ff595db737) | Apr 09, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [0e6d01e44d](https://linux-hardware.org/?probe=0e6d01e44d) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [621eb9522f](https://linux-hardware.org/?probe=621eb9522f) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [23a244aaf4](https://linux-hardware.org/?probe=23a244aaf4) | Apr 09, 2023 |
| AMI           | Intel                       | Notebook    | [f35d255c12](https://linux-hardware.org/?probe=f35d255c12) | Apr 09, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [594a8d9a89](https://linux-hardware.org/?probe=594a8d9a89) | Apr 08, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [cb57237789](https://linux-hardware.org/?probe=cb57237789) | Apr 08, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [a4b27a5659](https://linux-hardware.org/?probe=a4b27a5659) | Apr 08, 2023 |
| Sony          | VPCSE1V9E                   | Notebook    | [e6dd1647f3](https://linux-hardware.org/?probe=e6dd1647f3) | Apr 08, 2023 |
| Lenovo        | ThinkPad 10 20C1002PUK      | Tablet      | [1133b0413b](https://linux-hardware.org/?probe=1133b0413b) | Apr 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e657bedde3](https://linux-hardware.org/?probe=e657bedde3) | Apr 08, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [1502ff1933](https://linux-hardware.org/?probe=1502ff1933) | Apr 08, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [5d0c8cade6](https://linux-hardware.org/?probe=5d0c8cade6) | Apr 08, 2023 |
| Lenovo        | ThinkPad L430 24683NG       | Notebook    | [d5f226c56f](https://linux-hardware.org/?probe=d5f226c56f) | Apr 08, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bd1dc31213](https://linux-hardware.org/?probe=bd1dc31213) | Apr 07, 2023 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fccb05fbef](https://linux-hardware.org/?probe=fccb05fbef) | Apr 07, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [1e9120783f](https://linux-hardware.org/?probe=1e9120783f) | Apr 07, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [859f83bbfc](https://linux-hardware.org/?probe=859f83bbfc) | Apr 07, 2023 |
| HP            | G61                         | Notebook    | [8eec217a3a](https://linux-hardware.org/?probe=8eec217a3a) | Apr 07, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [bf0c0bb982](https://linux-hardware.org/?probe=bf0c0bb982) | Apr 07, 2023 |
| HP            | G61                         | Notebook    | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [9f5a3611b8](https://linux-hardware.org/?probe=9f5a3611b8) | Apr 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [241572fcea](https://linux-hardware.org/?probe=241572fcea) | Apr 07, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [78e2e080ea](https://linux-hardware.org/?probe=78e2e080ea) | Apr 07, 2023 |
| Samsung       | 950QED                      | Convertible | [c691077d2f](https://linux-hardware.org/?probe=c691077d2f) | Apr 06, 2023 |
| System76      | Oryx Pro                    | Notebook    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | 250 G4                      | Notebook    | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [bf0fc7e5d1](https://linux-hardware.org/?probe=bf0fc7e5d1) | Apr 06, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [58e0aa6707](https://linux-hardware.org/?probe=58e0aa6707) | Apr 06, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [3fa6f0de7a](https://linux-hardware.org/?probe=3fa6f0de7a) | Apr 06, 2023 |
| Quanta        | XV1                         | All in one  | [7cce1c6f6f](https://linux-hardware.org/?probe=7cce1c6f6f) | Apr 06, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [51d2c2c17d](https://linux-hardware.org/?probe=51d2c2c17d) | Apr 06, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [3fae5e4d5c](https://linux-hardware.org/?probe=3fae5e4d5c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X250 20CLS2X60S    | Notebook    | [b5b5fd68e9](https://linux-hardware.org/?probe=b5b5fd68e9) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| Lenovo        | ThinkPad X61s 7666WJ5       | Notebook    | [eb755a4a95](https://linux-hardware.org/?probe=eb755a4a95) | Apr 05, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [caf5563d44](https://linux-hardware.org/?probe=caf5563d44) | Apr 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [0e7d453676](https://linux-hardware.org/?probe=0e7d453676) | Apr 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 905       | 11.18%  |
| Ubuntu 18.04                 | 563       | 6.95%   |
| Ubuntu 22.04                 | 462       | 5.71%   |
| Arch Rolling                 | 234       | 2.89%   |
| OpenMandriva 4.2             | 221       | 2.73%   |
| Debian 11                    | 202       | 2.5%    |
| OpenMandriva 4.3             | 192       | 2.37%   |
| Fedora 36                    | 151       | 1.87%   |
| Linux Mint 21.1              | 144       | 1.78%   |
| Ubuntu 20.10                 | 130       | 1.61%   |
| Ubuntu 22.10                 | 126       | 1.56%   |
| Arch                         | 123       | 1.52%   |
| Ubuntu 19.10                 | 120       | 1.48%   |
| Zorin 16                     | 118       | 1.46%   |
| Pop!_OS 22.04                | 115       | 1.42%   |
| Ubuntu 19.04                 | 108       | 1.33%   |
| Xubuntu 18.04                | 107       | 1.32%   |
| Xubuntu 20.04                | 104       | 1.28%   |
| Linux Mint 20.3              | 103       | 1.27%   |
| KDE neon 20.04               | 102       | 1.26%   |
| Fedora 37                    | 102       | 1.26%   |
| OpenMandriva 23.03           | 97        | 1.2%    |
| Ubuntu 21.10                 | 96        | 1.19%   |
| Linux Mint 21                | 93        | 1.15%   |
| OpenMandriva 23.01           | 91        | 1.12%   |
| EndeavourOS Rolling          | 85        | 1.05%   |
| Ubuntu 21.04                 | 83        | 1.03%   |
| Debian 10                    | 81        | 1%      |
| Manjaro                      | 74        | 0.91%   |
| Zorin 15                     | 71        | 0.88%   |
| Ubuntu 18.10                 | 68        | 0.84%   |
| Fedora 35                    | 68        | 0.84%   |
| Linux Mint 19.3              | 66        | 0.82%   |
| Kubuntu 22.04                | 66        | 0.82%   |
| Kubuntu 20.04                | 66        | 0.82%   |
| openSUSE Tumbleweed-XXXXXXXX | 63        | 0.78%   |
| ROSA R10                     | 62        | 0.77%   |
| Fedora 38                    | 61        | 0.75%   |
| Linux Mint 20.2              | 60        | 0.74%   |
| Linux Mint 20.1              | 60        | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2602      | 34.11%  |
| OpenMandriva  | 638       | 8.36%   |
| Linux Mint    | 590       | 7.73%   |
| Fedora        | 512       | 6.71%   |
| Debian        | 364       | 4.77%   |
| Arch          | 348       | 4.56%   |
| Xubuntu       | 306       | 4.01%   |
| Pop!_OS       | 264       | 3.46%   |
| Manjaro       | 226       | 2.96%   |
| Kubuntu       | 208       | 2.73%   |
| Zorin         | 199       | 2.61%   |
| ROSA          | 184       | 2.41%   |
| KDE neon      | 148       | 1.94%   |
| Lubuntu       | 96        | 1.26%   |
| EndeavourOS   | 91        | 1.19%   |
| openSUSE      | 88        | 1.15%   |
| Ubuntu MATE   | 77        | 1.01%   |
| Elementary    | 61        | 0.8%    |
| Endless       | 48        | 0.63%   |
| Ubuntu Unity  | 43        | 0.56%   |
| ArcoLinux     | 41        | 0.54%   |
| Clear Linux   | 38        | 0.5%    |
| LMDE          | 37        | 0.48%   |
| MX            | 35        | 0.46%   |
| BlackPanther  | 35        | 0.46%   |
| Gentoo        | 33        | 0.43%   |
| Kali          | 27        | 0.35%   |
| Garuda Linux  | 25        | 0.33%   |
| Ubuntu Budgie | 23        | 0.3%    |
| Peppermint    | 20        | 0.26%   |
| SteamOS       | 15        | 0.2%    |
| Parrot        | 15        | 0.2%    |
| Nobara        | 13        | 0.17%   |
| LinuxFX       | 12        | 0.16%   |
| NixOS         | 11        | 0.14%   |
| Ubuntu Studio | 10        | 0.13%   |
| Slackware     | 9         | 0.12%   |
| Raspbian      | 9         | 0.12%   |
| Q4OS          | 8         | 0.1%    |
| CentOS        | 8         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 214       | 2.38%   |
| 5.16.7-desktop-1omv4003  | 183       | 2.03%   |
| 5.15.0-52-generic        | 168       | 1.87%   |
| 5.4.0-42-generic         | 125       | 1.39%   |
| 5.15.0-56-generic        | 122       | 1.36%   |
| 6.2.6-desktop-1omv2390   | 96        | 1.07%   |
| 5.4.0-52-generic         | 81        | 0.9%    |
| 6.1.1-desktop-1omv2290   | 76        | 0.85%   |
| 5.15.0-58-generic        | 73        | 0.81%   |
| 5.15.0-47-generic        | 71        | 0.79%   |
| 5.4.0-26-generic         | 66        | 0.73%   |
| 5.3.0-46-generic         | 66        | 0.73%   |
| 5.15.0-46-generic        | 65        | 0.72%   |
| 5.4.0-58-generic         | 60        | 0.67%   |
| 5.4.0-29-generic         | 59        | 0.66%   |
| 5.3.0-40-generic         | 58        | 0.64%   |
| 5.4.0-48-generic         | 56        | 0.62%   |
| 5.15.0-43-generic        | 54        | 0.6%    |
| 5.3.0-42-generic         | 48        | 0.53%   |
| 5.4.0-54-generic         | 46        | 0.51%   |
| 5.10.0-19-amd64          | 42        | 0.47%   |
| 5.19.0-23-generic        | 41        | 0.46%   |
| 5.15.0-53-generic        | 41        | 0.46%   |
| 5.15.0-41-generic        | 41        | 0.46%   |
| 6.0.2-arch1-1            | 40        | 0.44%   |
| 5.4.0-28-generic         | 40        | 0.44%   |
| 5.19.0-35-generic        | 40        | 0.44%   |
| 5.15.0-60-generic        | 40        | 0.44%   |
| 5.0.0-37-generic         | 39        | 0.43%   |
| 5.4.0-56-generic         | 38        | 0.42%   |
| 5.4.0-37-generic         | 38        | 0.42%   |
| 5.4.0-33-generic         | 38        | 0.42%   |
| 5.15.0-48-generic        | 38        | 0.42%   |
| 5.4.0-47-generic         | 37        | 0.41%   |
| 5.19.0-32-generic        | 37        | 0.41%   |
| 5.11.0-38-generic        | 37        | 0.41%   |
| 5.4.0-40-generic         | 35        | 0.39%   |
| 5.13.0-28-generic        | 35        | 0.39%   |
| 5.15.0-50-generic        | 34        | 0.38%   |
| 5.10.0-21-amd64          | 34        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1262      | 15.06%  |
| 5.15.0  | 890       | 10.62%  |
| 4.15.0  | 471       | 5.62%   |
| 5.8.0   | 395       | 4.71%   |
| 5.3.0   | 385       | 4.59%   |
| 5.19.0  | 374       | 4.46%   |
| 5.11.0  | 309       | 3.69%   |
| 5.13.0  | 303       | 3.62%   |
| 5.10.0  | 239       | 2.85%   |
| 5.0.0   | 224       | 2.67%   |
| 5.10.14 | 215       | 2.57%   |
| 5.16.7  | 186       | 2.22%   |
| 4.18.0  | 158       | 1.89%   |
| 6.2.6   | 123       | 1.47%   |
| 6.1.1   | 89        | 1.06%   |
| 6.0.2   | 83        | 0.99%   |
| 4.19.0  | 79        | 0.94%   |
| 6.2.0   | 71        | 0.85%   |
| 6.1.0   | 48        | 0.57%   |
| 5.19.16 | 47        | 0.56%   |
| 6.0.0   | 37        | 0.44%   |
| 4.9.60  | 36        | 0.43%   |
| 4.9.20  | 36        | 0.43%   |
| 6.0.6   | 35        | 0.42%   |
| 6.0.12  | 34        | 0.41%   |
| 4.18.16 | 34        | 0.41%   |
| 5.17.5  | 32        | 0.38%   |
| 4.4.0   | 29        | 0.35%   |
| 5.19.6  | 28        | 0.33%   |
| 6.0.7   | 26        | 0.31%   |
| 6.0.10  | 24        | 0.29%   |
| 6.2.9   | 21        | 0.25%   |
| 6.0.5   | 21        | 0.25%   |
| 5.16.11 | 20        | 0.24%   |
| 6.1.8   | 19        | 0.23%   |
| 6.0.9   | 19        | 0.23%   |
| 5.17.1  | 19        | 0.23%   |
| 5.12.4  | 18        | 0.21%   |
| 5.18.0  | 17        | 0.2%    |
| 6.1.4   | 16        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1342      | 16.23%  |
| 5.15    | 1059      | 12.81%  |
| 5.19    | 561       | 6.78%   |
| 5.10    | 549       | 6.64%   |
| 4.15    | 473       | 5.72%   |
| 5.8     | 465       | 5.62%   |
| 5.3     | 415       | 5.02%   |
| 5.11    | 371       | 4.49%   |
| 5.13    | 336       | 4.06%   |
| 6.0     | 327       | 3.95%   |
| 6.2     | 307       | 3.71%   |
| 6.1     | 286       | 3.46%   |
| 5.16    | 280       | 3.39%   |
| 5.0     | 232       | 2.81%   |
| 4.18    | 199       | 2.41%   |
| 4.9     | 124       | 1.5%    |
| 5.17    | 106       | 1.28%   |
| 4.19    | 104       | 1.26%   |
| 5.18    | 99        | 1.2%    |
| 6.3     | 89        | 1.08%   |
| 5.9     | 82        | 0.99%   |
| 5.14    | 81        | 0.98%   |
| 5.6     | 64        | 0.77%   |
| 5.12    | 62        | 0.75%   |
| 5.7     | 50        | 0.6%    |
| 6.4     | 49        | 0.59%   |
| 5.5     | 47        | 0.57%   |
| 4.4     | 31        | 0.37%   |
| 4.1     | 16        | 0.19%   |
| 5.2     | 13        | 0.16%   |
| 4.13    | 12        | 0.15%   |
| 5.1     | 7         | 0.08%   |
| 4.20    | 5         | 0.06%   |
| 4.17    | 5         | 0.06%   |
| 4.12    | 5         | 0.06%   |
| 4.14    | 4         | 0.05%   |
| 3.10    | 3         | 0.04%   |
| 4.16    | 2         | 0.02%   |
| 4.10    | 2         | 0.02%   |
| 4.8     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6962      | 94.9%   |
| i686    | 323       | 4.4%    |
| aarch64 | 36        | 0.49%   |
| armv7l  | 14        | 0.19%   |
| ppc64le | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 3256      | 42.43%  |
| KDE5              | 1475      | 19.22%  |
| Unknown           | 841       | 10.96%  |
| XFCE              | 644       | 8.39%   |
| X-Cinnamon        | 486       | 6.33%   |
| MATE              | 214       | 2.79%   |
| KDE               | 140       | 1.82%   |
| LXQt              | 119       | 1.55%   |
| KDE4              | 108       | 1.41%   |
| Pantheon          | 60        | 0.78%   |
| Cinnamon          | 55        | 0.72%   |
| LXDE              | 51        | 0.66%   |
| Unity             | 45        | 0.59%   |
| Budgie            | 34        | 0.44%   |
| GNOME Flashback   | 28        | 0.36%   |
| i3                | 22        | 0.29%   |
| GNOME Classic     | 15        | 0.2%    |
| Deepin            | 11        | 0.14%   |
| Sway              | 10        | 0.13%   |
| Hyprland          | 10        | 0.13%   |
| Openbox           | 9         | 0.12%   |
| bspwm             | 6         | 0.08%   |
| Trinity           | 5         | 0.07%   |
| lightdm-xsession  | 5         | 0.07%   |
| dwm               | 4         | 0.05%   |
| xubuntu           | 2         | 0.03%   |
| qtile             | 2         | 0.03%   |
| icewm             | 2         | 0.03%   |
| Enlightenment     | 2         | 0.03%   |
| awesome           | 2         | 0.03%   |
| ubuntu:pika:GNOME | 1         | 0.01%   |
| ubuntu            | 1         | 0.01%   |
| pika:GNOME        | 1         | 0.01%   |
| none+i3           | 1         | 0.01%   |
| none+bspwm        | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| herbstluftwm      | 1         | 0.01%   |
| gamescope         | 1         | 0.01%   |
| FVWM              | 1         | 0.01%   |
| Cutefish          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5745      | 75.72%  |
| Wayland | 1301      | 17.15%  |
| Unknown | 429       | 5.65%   |
| Tty     | 112       | 1.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3436      | 44.76%  |
| SDDM    | 1388      | 18.08%  |
| GDM3    | 929       | 12.1%   |
| GDM     | 826       | 10.76%  |
| LightDM | 783       | 10.2%   |
| TDM     | 169       | 2.2%    |
| KDM     | 111       | 1.45%   |
| XDM     | 15        | 0.2%    |
| SLiM    | 6         | 0.08%   |
| LXDM    | 5         | 0.07%   |
| GREETD  | 3         | 0.04%   |
| Ly      | 2         | 0.03%   |
| WDM     | 1         | 0.01%   |
| SLIMSKI | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| it_IT        | 4690      | 62.13%  |
| en_US        | 1550      | 20.53%  |
| Unknown      | 864       | 11.45%  |
| en_GB        | 168       | 2.23%   |
| C            | 144       | 1.91%   |
| de_DE        | 24        | 0.32%   |
| fr_FR        | 15        | 0.2%    |
| es_ES        | 12        | 0.16%   |
| de_IT        | 11        | 0.15%   |
| POSIX        | 9         | 0.12%   |
| ru_RU        | 8         | 0.11%   |
| it_CH        | 8         | 0.11%   |
| en_IE        | 6         | 0.08%   |
| en_AG        | 5         | 0.07%   |
| it_IT@euro   | 4         | 0.05%   |
| de_AT        | 4         | 0.05%   |
| en_AU        | 3         | 0.04%   |
| en_US.UTF8   | 2         | 0.03%   |
| sc_IT        | 1         | 0.01%   |
| ro_RO        | 1         | 0.01%   |
| pt_BR        | 1         | 0.01%   |
| pl_PL        | 1         | 0.01%   |
| it_ITutf8    | 1         | 0.01%   |
| it_IT.UTF -8 | 1         | 0.01%   |
| it           | 1         | 0.01%   |
| hu_HU        | 1         | 0.01%   |
| fur_IT       | 1         | 0.01%   |
| fr_CH        | 1         | 0.01%   |
| fr_BE        | 1         | 0.01%   |
| es_US        | 1         | 0.01%   |
| es_MX        | 1         | 0.01%   |
| en_US@euro   | 1         | 0.01%   |
| en_US.utf-8  | 1         | 0.01%   |
| en_US.ASCII  | 1         | 0.01%   |
| en_IN        | 1         | 0.01%   |
| en_DK        | 1         | 0.01%   |
| de_CH        | 1         | 0.01%   |
| Default      | 1         | 0.01%   |
| C.UTF8       | 1         | 0.01%   |
| bg_BG        | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3849      | 51.31%  |
| EFI  | 3653      | 48.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5658      | 74.89%  |
| Overlay  | 764       | 10.11%  |
| Btrfs    | 618       | 8.18%   |
| Unknown  | 230       | 3.04%   |
| Tmpfs    | 115       | 1.52%   |
| Xfs      | 75        | 0.99%   |
| Zfs      | 38        | 0.5%    |
| Ext2     | 19        | 0.25%   |
| Ext3     | 17        | 0.23%   |
| F2fs     | 13        | 0.17%   |
| Aufs     | 3         | 0.04%   |
| XXX4     | 2         | 0.03%   |
| XXXX     | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3677      | 48.67%  |
| GPT     | 2980      | 39.44%  |
| MBR     | 898       | 11.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6309      | 84.15%  |
| Yes       | 1188      | 15.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4768      | 63.52%  |
| Yes       | 2738      | 36.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1509      | 20.59%  |
| Hewlett-Packard         | 1236      | 16.86%  |
| Lenovo                  | 839       | 11.45%  |
| Dell                    | 597       | 8.15%   |
| Acer                    | 592       | 8.08%   |
| MSI                     | 425       | 5.8%    |
| ASRock                  | 331       | 4.52%   |
| Gigabyte Technology     | 257       | 3.51%   |
| Apple                   | 161       | 2.2%    |
| Intel                   | 108       | 1.47%   |
| HUAWEI                  | 106       | 1.45%   |
| Toshiba                 | 105       | 1.43%   |
| Sony                    | 95        | 1.3%    |
| Fujitsu                 | 80        | 1.09%   |
| Unknown                 | 79        | 1.08%   |
| Samsung Electronics     | 77        | 1.05%   |
| Packard Bell            | 57        | 0.78%   |
| Pegatron                | 44        | 0.6%    |
| Raspberry Pi Foundation | 36        | 0.49%   |
| Mediacom                | 34        | 0.46%   |
| Fujitsu Siemens         | 33        | 0.45%   |
| Chuwi                   | 32        | 0.44%   |
| Teclast                 | 27        | 0.37%   |
| AMI                     | 25        | 0.34%   |
| Microsoft               | 24        | 0.33%   |
| Notebook                | 22        | 0.3%    |
| Foxconn                 | 22        | 0.3%    |
| BESSTAR Tech            | 20        | 0.27%   |
| Microtech               | 19        | 0.26%   |
| Timi                    | 18        | 0.25%   |
| TUXEDO                  | 14        | 0.19%   |
| AZW                     | 14        | 0.19%   |
| Supermicro              | 13        | 0.18%   |
| PC Specialist           | 13        | 0.18%   |
| Valve                   | 12        | 0.16%   |
| TrekStor                | 9         | 0.12%   |
| SANTECH                 | 9         | 0.12%   |
| Jumper                  | 9         | 0.12%   |
| Google                  | 9         | 0.12%   |
| eMachines               | 9         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 96        | 1.31%   |
| ASUS All Series                       | 77        | 1.05%   |
| HP Pavilion dv6                       | 55        | 0.75%   |
| HP Notebook                           | 41        | 0.56%   |
| HP Pavilion 15                        | 28        | 0.38%   |
| HP Pavilion g6                        | 23        | 0.31%   |
| HP 255 G8 Notebook PC                 | 22        | 0.3%    |
| HUAWEI NBLK-WAX9X                     | 19        | 0.26%   |
| MSI MS-7C37                           | 17        | 0.23%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 17        | 0.23%   |
| ASUS PRIME A320M-K                    | 17        | 0.23%   |
| HP 15                                 | 15        | 0.2%    |
| Dell OptiPlex 7010                    | 15        | 0.2%    |
| MSI MS-7C56                           | 14        | 0.19%   |
| Dell XPS 15 7590                      | 14        | 0.19%   |
| MSI MS-7B86                           | 13        | 0.18%   |
| HP Pavilion x2 Detachable             | 13        | 0.18%   |
| HP ENVY 15                            | 13        | 0.18%   |
| HP 255 G7 Notebook PC                 | 13        | 0.18%   |
| Valve Jupiter                         | 12        | 0.16%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 12        | 0.16%   |
| HUAWEI KLVL-WXX9                      | 12        | 0.16%   |
| HP G62                                | 12        | 0.16%   |
| HP 250 G6 Notebook PC                 | 12        | 0.16%   |
| ASUS T101HA                           | 12        | 0.16%   |
| Apple MacBook4,1                      | 12        | 0.16%   |
| Lenovo IdeaPad 330S-15IKB 81F5        | 11        | 0.15%   |
| HP 255 G6 Notebook PC                 | 11        | 0.15%   |
| Dell XPS 15 9570                      | 11        | 0.15%   |
| AMI Intel                             | 11        | 0.15%   |
| Acer Aspire 5750G                     | 11        | 0.15%   |
| RPi Raspberry Pi                      | 10        | 0.14%   |
| MSI MS-7B79                           | 10        | 0.14%   |
| HP Pavilion dv7                       | 10        | 0.14%   |
| HP Compaq Elite 8300 SFF              | 10        | 0.14%   |
| Gigabyte B450M DS3H                   | 10        | 0.14%   |
| Dell XPS 15 9560                      | 10        | 0.14%   |
| Acer Aspire 5920G                     | 10        | 0.14%   |
| Jumper EZbook                         | 9         | 0.12%   |
| HUAWEI BOD-WXX9                       | 9         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 379       | 5.17%   |
| Lenovo ThinkPad       | 337       | 4.6%    |
| HP Pavilion           | 284       | 3.88%   |
| Lenovo IdeaPad        | 176       | 2.4%    |
| Dell Latitude         | 175       | 2.39%   |
| HP Compaq             | 157       | 2.14%   |
| ASUS PRIME            | 126       | 1.72%   |
| HP EliteBook          | 117       | 1.6%    |
| Dell XPS              | 111       | 1.51%   |
| ASUS VivoBook         | 100       | 1.36%   |
| Dell Inspiron         | 96        | 1.31%   |
| Unknown               | 96        | 1.31%   |
| Toshiba Satellite     | 90        | 1.23%   |
| HP Laptop             | 90        | 1.23%   |
| HP ProBook            | 89        | 1.21%   |
| Dell OptiPlex         | 81        | 1.11%   |
| ASUS ROG              | 78        | 1.06%   |
| ASUS All              | 77        | 1.05%   |
| HP 255                | 64        | 0.87%   |
| ASUS TUF              | 59        | 0.81%   |
| Dell Precision        | 57        | 0.78%   |
| HP 250                | 56        | 0.76%   |
| Lenovo ThinkCentre    | 53        | 0.72%   |
| HP Notebook           | 41        | 0.56%   |
| Dell Vostro           | 40        | 0.55%   |
| Fujitsu LIFEBOOK      | 38        | 0.52%   |
| HP ENVY               | 37        | 0.5%    |
| Acer TravelMate       | 37        | 0.5%    |
| Acer Swift            | 37        | 0.5%    |
| RPi Raspberry         | 36        | 0.49%   |
| Fujitsu ESPRIMO       | 36        | 0.49%   |
| Acer Veriton          | 36        | 0.49%   |
| Acer Extensa          | 36        | 0.49%   |
| Lenovo Yoga           | 33        | 0.45%   |
| Lenovo ThinkBook      | 30        | 0.41%   |
| Packard Bell EasyNote | 24        | 0.33%   |
| Microsoft Surface     | 24        | 0.33%   |
| HP ProDesk            | 23        | 0.31%   |
| ASUS P8H61-M          | 22        | 0.3%    |
| Mediacom SMARTBOOK    | 21        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 630       | 8.6%    |
| 2020    | 597       | 8.15%   |
| 2019    | 596       | 8.13%   |
| 2013    | 500       | 6.82%   |
| 2021    | 483       | 6.59%   |
| 2017    | 471       | 6.43%   |
| 2012    | 469       | 6.4%    |
| 2011    | 441       | 6.02%   |
| 2008    | 427       | 5.83%   |
| 2014    | 411       | 5.61%   |
| 2009    | 404       | 5.51%   |
| 2016    | 402       | 5.49%   |
| 2010    | 393       | 5.36%   |
| 2015    | 387       | 5.28%   |
| 2007    | 253       | 3.45%   |
| 2022    | 174       | 2.37%   |
| 2006    | 139       | 1.9%    |
| 2005    | 67        | 0.91%   |
| Unknown | 47        | 0.64%   |
| 2023    | 16        | 0.22%   |
| 2004    | 14        | 0.19%   |
| 2003    | 5         | 0.07%   |
| 2001    | 2         | 0.03%   |
| 2002    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4141      | 56.5%   |
| Desktop        | 2667      | 36.39%  |
| Convertible    | 155       | 2.11%   |
| Mini pc        | 106       | 1.45%   |
| All in one     | 100       | 1.36%   |
| Tablet         | 90        | 1.23%   |
| System on chip | 48        | 0.65%   |
| Server         | 21        | 0.29%   |
| Phone          | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6849      | 92.62%  |
| Enabled  | 546       | 7.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7312      | 99.77%  |
| Yes  | 17        | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1778      | 23.9%   |
| 3.01-4.0        | 1671      | 22.47%  |
| 16.01-24.0      | 1351      | 18.16%  |
| 8.01-16.0       | 1292      | 17.37%  |
| 32.01-64.0      | 501       | 6.74%   |
| 1.01-2.0        | 432       | 5.81%   |
| 2.01-3.0        | 135       | 1.82%   |
| 64.01-256.0     | 98        | 1.32%   |
| 24.01-32.0      | 85        | 1.14%   |
| 0.51-1.0        | 82        | 1.1%    |
| 0.01-0.5        | 7         | 0.09%   |
| More than 256.0 | 6         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3159      | 38.7%   |
| 2.01-3.0   | 1991      | 24.39%  |
| 4.01-8.0   | 996       | 12.2%   |
| 3.01-4.0   | 961       | 11.77%  |
| 0.51-1.0   | 673       | 8.25%   |
| 8.01-16.0  | 240       | 2.94%   |
| 0.01-0.5   | 104       | 1.27%   |
| 16.01-24.0 | 25        | 0.31%   |
| 24.01-32.0 | 8         | 0.1%    |
| Unknown    | 3         | 0.04%   |
| 32.01-64.0 | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4587      | 60.82%  |
| 2       | 1868      | 24.77%  |
| 3       | 574       | 7.61%   |
| 4       | 238       | 3.16%   |
| 5       | 108       | 1.43%   |
| 0       | 70        | 0.93%   |
| 6       | 52        | 0.69%   |
| 7       | 19        | 0.25%   |
| 8       | 13        | 0.17%   |
| 10      | 4         | 0.05%   |
| 12      | 3         | 0.04%   |
| 9       | 3         | 0.04%   |
| Unknown | 2         | 0.03%   |
| 13      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3944      | 53.43%  |
| Yes       | 3437      | 46.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6239      | 84.84%  |
| No        | 1115      | 15.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5642      | 76.55%  |
| No        | 1728      | 23.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4191      | 56.3%   |
| No        | 3253      | 43.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 7329      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Milan               | 1026      | 12.26%  |
| Rome                | 851       | 10.16%  |
| Turin               | 268       | 3.2%    |
| Bologna             | 173       | 2.07%   |
| Florence            | 156       | 1.86%   |
| Naples              | 152       | 1.82%   |
| Genoa               | 120       | 1.43%   |
| Rho                 | 114       | 1.36%   |
| Padova              | 101       | 1.21%   |
| Palermo             | 91        | 1.09%   |
| Milano              | 86        | 1.03%   |
| Verona              | 79        | 0.94%   |
| Catania             | 68        | 0.81%   |
| Bari                | 67        | 0.8%    |
| Brescia             | 61        | 0.73%   |
| Trieste             | 56        | 0.67%   |
| Venice              | 52        | 0.62%   |
| Parma               | 50        | 0.6%    |
| Bergamo             | 45        | 0.54%   |
| Pisa                | 44        | 0.53%   |
| Reggio Emilia       | 40        | 0.48%   |
| Modena              | 40        | 0.48%   |
| Pescara             | 39        | 0.47%   |
| Cagliari            | 39        | 0.47%   |
| Monza               | 36        | 0.43%   |
| Casalecchio di Reno | 35        | 0.42%   |
| Trento              | 34        | 0.41%   |
| Sesto San Giovanni  | 33        | 0.39%   |
| Perugia             | 33        | 0.39%   |
| Bolzano             | 30        | 0.36%   |
| Vicenza             | 28        | 0.33%   |
| Taranto             | 28        | 0.33%   |
| Udine               | 26        | 0.31%   |
| Seregno             | 25        | 0.3%    |
| Mestre              | 24        | 0.29%   |
| Como                | 24        | 0.29%   |
| Salerno             | 23        | 0.27%   |
| Reggio Calabria     | 23        | 0.27%   |
| Forlì              | 21        | 0.25%   |
| Treviso             | 20        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1724      | 2500   | 16.26%  |
| Seagate                     | 1487      | 2269   | 14.02%  |
| WDC                         | 1424      | 2175   | 13.43%  |
| Kingston                    | 688       | 906    | 6.49%   |
| Toshiba                     | 620       | 868    | 5.85%   |
| Crucial                     | 618       | 783    | 5.83%   |
| SanDisk                     | 535       | 729    | 5.05%   |
| Unknown                     | 510       | 691    | 4.81%   |
| Hitachi                     | 404       | 516    | 3.81%   |
| SK hynix                    | 237       | 290    | 2.24%   |
| HGST                        | 219       | 296    | 2.07%   |
| Maxtor                      | 188       | 255    | 1.77%   |
| Micron Technology           | 167       | 211    | 1.57%   |
| Intel                       | 163       | 217    | 1.54%   |
| Phison                      | 107       | 149    | 1.01%   |
| China                       | 90        | 102    | 0.85%   |
| KIOXIA                      | 77        | 103    | 0.73%   |
| SPCC                        | 71        | 87     | 0.67%   |
| Apple                       | 56        | 71     | 0.53%   |
| Intenso                     | 55        | 69     | 0.52%   |
| Fujitsu                     | 55        | 64     | 0.52%   |
| Micron/Crucial Technology   | 50        | 67     | 0.47%   |
| Transcend                   | 48        | 62     | 0.45%   |
| A-DATA Technology           | 44        | 59     | 0.41%   |
| Phison Electronics          | 42        | 52     | 0.4%    |
| PNY                         | 38        | 46     | 0.36%   |
| Corsair                     | 37        | 54     | 0.35%   |
| LITEON                      | 33        | 42     | 0.31%   |
| KingDian                    | 33        | 39     | 0.31%   |
| JMicron Technology          | 33        | 37     | 0.31%   |
| Kingston Technology Company | 32        | 38     | 0.3%    |
| Unknown                     | 31        | 39     | 0.29%   |
| Silicon Motion              | 28        | 41     | 0.26%   |
| OCZ                         | 27        | 32     | 0.25%   |
| Netac                       | 25        | 27     | 0.24%   |
| Patriot                     | 24        | 34     | 0.23%   |
| Teclast                     | 23        | 29     | 0.22%   |
| SABRENT                     | 23        | 24     | 0.22%   |
| Drevo                       | 23        | 25     | 0.22%   |
| ASMT                        | 19        | 22     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 188       | 1.62%   |
| Samsung SSD 860 EVO 500GB                           | 150       | 1.29%   |
| Crucial CT500MX500SSD1 500GB                        | 145       | 1.25%   |
| Samsung SSD 850 EVO 250GB                           | 130       | 1.12%   |
| Seagate ST500DM002-1BD142 500GB                     | 110       | 0.95%   |
| Unknown MMC Card  32GB                              | 92        | 0.79%   |
| Samsung SSD 850 EVO 500GB                           | 91        | 0.78%   |
| Kingston SA400S37480G 480GB SSD                     | 90        | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB                      | 75        | 0.65%   |
| Crucial CT240BX500SSD1 240GB                        | 75        | 0.65%   |
| Unknown MMC Card  64GB                              | 73        | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 72        | 0.62%   |
| Toshiba MQ01ABF050 500GB                            | 71        | 0.61%   |
| Samsung SSD 860 EVO 250GB                           | 71        | 0.61%   |
| Crucial CT1000MX500SSD1 1TB                         | 65        | 0.56%   |
| Toshiba DT01ACA100 1TB                              | 63        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 62        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                     | 61        | 0.53%   |
| Crucial CT480BX500SSD1 480GB                        | 59        | 0.51%   |
| HGST HTS545050A7E680 500GB                          | 56        | 0.48%   |
| Seagate ST500LT012-1DG142 500GB                     | 54        | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB                      | 54        | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB                      | 53        | 0.46%   |
| HGST HTS721010A9E630 1TB                            | 52        | 0.45%   |
| Seagate ST3500418AS 500GB                           | 50        | 0.43%   |
| Kingston SV300S37A120G 120GB SSD                    | 49        | 0.42%   |
| Seagate M3 Portable 1TB                             | 48        | 0.41%   |
| Unknown SD/MMC/MS PRO 128GB                         | 47        | 0.4%    |
| SanDisk SSD PLUS 240GB                              | 45        | 0.39%   |
| Samsung SSD 860 EVO 1TB                             | 43        | 0.37%   |
| Samsung SSD 840 EVO 250GB                           | 43        | 0.37%   |
| Samsung NVMe SSD Drive 512GB                        | 43        | 0.37%   |
| Seagate ST9500325AS 500GB                           | 42        | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 41        | 0.35%   |
| Unknown MMC Card  128GB                             | 41        | 0.35%   |
| Phison Sabrent 1TB                                  | 41        | 0.35%   |
| Seagate Expansion 1TB                               | 40        | 0.34%   |
| Toshiba MQ01ABD100 1TB                              | 39        | 0.34%   |
| Seagate ST31000528AS 1TB                            | 39        | 0.34%   |
| Seagate ST1000DM003-1CH162 1TB                      | 39        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1439      | 2183   | 33.8%   |
| WDC                 | 1188      | 1828   | 27.91%  |
| Toshiba             | 457       | 632    | 10.74%  |
| Hitachi             | 404       | 516    | 9.49%   |
| HGST                | 218       | 295    | 5.12%   |
| Maxtor              | 186       | 253    | 4.37%   |
| Samsung Electronics | 142       | 178    | 3.34%   |
| Unknown             | 60        | 70     | 1.41%   |
| Fujitsu             | 55        | 64     | 1.29%   |
| Apple               | 18        | 21     | 0.42%   |
| ASMT                | 16        | 19     | 0.38%   |
| JMicron Technology  | 15        | 17     | 0.35%   |
| External            | 11        | 12     | 0.26%   |
| USB3.0              | 5         | 6      | 0.12%   |
| HGST HTS            | 5         | 5      | 0.12%   |
| IBM/Hitachi         | 4         | 5      | 0.09%   |
| SSK                 | 3         | 3      | 0.07%   |
| Inateck             | 3         | 3      | 0.07%   |
| Hewlett-Packard     | 3         | 4      | 0.07%   |
| WD MediaMax         | 2         | 2      | 0.05%   |
| LaCie               | 2         | 3      | 0.05%   |
| Intenso             | 2         | 4      | 0.05%   |
| ASMT109x            | 2         | 2      | 0.05%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| USB                 | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| QUANTUM             | 1         | 1      | 0.02%   |
| Promise             | 1         | 1      | 0.02%   |
| PI-041              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| Initio              | 1         | 1      | 0.02%   |
| IBM-ESXS            | 1         | 2      | 0.02%   |
| IBM-207x            | 1         | 4      | 0.02%   |
| HPE                 | 1         | 1      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| FC-1307             | 1         | 2      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| Config              | 1         | 1      | 0.02%   |
| China               | 1         | 1      | 0.02%   |
| ASMedia             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 960       | 1346   | 26.7%   |
| Kingston            | 580       | 769    | 16.13%  |
| Crucial             | 555       | 704    | 15.43%  |
| SanDisk             | 320       | 441    | 8.9%    |
| WDC                 | 119       | 163    | 3.31%   |
| China               | 88        | 100    | 2.45%   |
| Micron Technology   | 72        | 89     | 2%      |
| SPCC                | 60        | 73     | 1.67%   |
| Toshiba             | 56        | 78     | 1.56%   |
| SK hynix            | 52        | 60     | 1.45%   |
| Intenso             | 48        | 58     | 1.33%   |
| Transcend           | 45        | 59     | 1.25%   |
| Intel               | 39        | 52     | 1.08%   |
| PNY                 | 35        | 42     | 0.97%   |
| A-DATA Technology   | 35        | 48     | 0.97%   |
| Apple               | 33        | 36     | 0.92%   |
| KingDian            | 32        | 38     | 0.89%   |
| Corsair             | 31        | 46     | 0.86%   |
| LITEON              | 29        | 33     | 0.81%   |
| OCZ                 | 26        | 31     | 0.72%   |
| Patriot             | 24        | 34     | 0.67%   |
| Teclast             | 23        | 29     | 0.64%   |
| Netac               | 21        | 22     | 0.58%   |
| Drevo               | 21        | 22     | 0.58%   |
| LITEONIT            | 16        | 27     | 0.44%   |
| GOODRAM             | 16        | 24     | 0.44%   |
| Dogfish             | 16        | 20     | 0.44%   |
| Unknown             | 14        | 20     | 0.39%   |
| TCSUNBOW            | 13        | 14     | 0.36%   |
| Team                | 12        | 23     | 0.33%   |
| Verbatim            | 11        | 16     | 0.31%   |
| FORESEE             | 11        | 13     | 0.31%   |
| Unknown             | 10        | 11     | 0.28%   |
| BAITITON            | 10        | 13     | 0.28%   |
| Lexar               | 9         | 12     | 0.25%   |
| KingSpec            | 9         | 11     | 0.25%   |
| TO Exter            | 8         | 8      | 0.22%   |
| Microtech           | 8         | 18     | 0.22%   |
| Emtec               | 8         | 8      | 0.22%   |
| Fanxiang            | 6         | 7      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3585      | 6152   | 37.82%  |
| SSD     | 3214      | 4764   | 33.91%  |
| NVMe    | 2033      | 2949   | 21.45%  |
| MMC     | 466       | 652    | 4.92%   |
| Unknown | 181       | 230    | 1.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5556      | 10632  | 65.75%  |
| NVMe | 2019      | 2914   | 23.89%  |
| MMC  | 466       | 652    | 5.51%   |
| SAS  | 409       | 549    | 4.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 4549      | 7204   | 65.77%  |
| 0.51-1.0        | 1718      | 2578   | 24.84%  |
| 1.01-2.0        | 375       | 634    | 5.42%   |
| 3.01-4.0        | 108       | 193    | 1.56%   |
| 2.01-3.0        | 102       | 174    | 1.47%   |
| 4.01-10.0       | 57        | 117    | 0.82%   |
| 10.01-20.0      | 7         | 15     | 0.1%    |
| More than 100.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2123      | 27.1%   |
| 251-500        | 1709      | 21.82%  |
| 501-1000       | 934       | 11.92%  |
| 1-20           | 778       | 9.93%   |
| 51-100         | 619       | 7.9%    |
| 1001-2000      | 558       | 7.12%   |
| 21-50          | 375       | 4.79%   |
| More than 3000 | 295       | 3.77%   |
| 2001-3000      | 228       | 2.91%   |
| Unknown        | 214       | 2.73%   |
| 0              | 1         | 0.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3334      | 41.08%  |
| 21-50          | 1238      | 15.26%  |
| 101-250        | 988       | 12.17%  |
| 51-100         | 902       | 11.12%  |
| 251-500        | 602       | 7.42%   |
| 501-1000       | 421       | 5.19%   |
| 1001-2000      | 220       | 2.71%   |
| Unknown        | 214       | 2.64%   |
| More than 3000 | 112       | 1.38%   |
| 2001-3000      | 83        | 1.02%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 19        | 22     | 2.77%   |
| HGST HTS545050A7E680 500GB            | 17        | 20     | 2.48%   |
| Seagate ST3500418AS 500GB             | 11        | 15     | 1.61%   |
| Seagate ST9500325AS 500GB             | 10        | 10     | 1.46%   |
| Seagate ST1000LM035-1RK172 1TB        | 8         | 10     | 1.17%   |
| Maxtor STM3250310AS 250GB             | 8         | 9      | 1.17%   |
| Hitachi HTS725050A9A364 500GB         | 8         | 8      | 1.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 9      | 1.02%   |
| Toshiba MQ01ABF050 500GB              | 6         | 6      | 0.88%   |
| Seagate ST500LT012-1DG142 500GB       | 6         | 6      | 0.88%   |
| WDC WD40EFRX-68N32N0 4TB              | 5         | 6      | 0.73%   |
| WDC WD3200BEVT-60A23T0 320GB          | 5         | 5      | 0.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 5         | 7      | 0.73%   |
| SanDisk SSD PLUS 480GB                | 5         | 6      | 0.73%   |
| Maxtor STM3320820AS 320GB             | 5         | 5      | 0.73%   |
| Kingston SA400S37240G 240GB SSD       | 5         | 5      | 0.73%   |
| Hitachi HTS545050A7E380 500GB         | 5         | 5      | 0.73%   |
| HGST HTS725050A7E630 500GB            | 5         | 6      | 0.73%   |
| HGST HTS721010A9E630 1TB              | 5         | 5      | 0.73%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 4         | 4      | 0.58%   |
| Unknown MM0500EANCR 500GB             | 4         | 9      | 0.58%   |
| Toshiba MK5065GSX 500GB               | 4         | 4      | 0.58%   |
| Seagate ST9320325AS 320GB             | 4         | 4      | 0.58%   |
| Seagate ST31500341AS 1TB              | 4         | 4      | 0.58%   |
| Seagate ST31000528AS 1TB              | 4         | 7      | 0.58%   |
| Samsung Electronics HD103UJ 1TB       | 4         | 4      | 0.58%   |
| Hitachi HTS547550A9E384 500GB         | 4         | 4      | 0.58%   |
| Hitachi HTS543232A7A384 320GB         | 4         | 5      | 0.58%   |
| WDC WD20EFRX-68EUZN0 2TB              | 3         | 4      | 0.44%   |
| WDC WD10EZEX-60WN4A0 1TB              | 3         | 4      | 0.44%   |
| Toshiba MQ01ABD100 1TB                | 3         | 4      | 0.44%   |
| Toshiba DT01ACA100 1TB                | 3         | 3      | 0.44%   |
| Toshiba DT01ACA050 500GB              | 3         | 3      | 0.44%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 3         | 3      | 0.44%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.44%   |
| Seagate ST3500413AS 500GB             | 3         | 5      | 0.44%   |
| Seagate ST3500320AS 500GB             | 3         | 3      | 0.44%   |
| Seagate ST3250310AS 250GB             | 3         | 3      | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB        | 3         | 7      | 0.44%   |
| Seagate ST1000LM014-1EJ164 1TB        | 3         | 3      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 176       | 227    | 26.43%  |
| WDC                         | 129       | 159    | 19.37%  |
| Hitachi                     | 77        | 81     | 11.56%  |
| Toshiba                     | 46        | 47     | 6.91%   |
| Samsung Electronics         | 41        | 45     | 6.16%   |
| Maxtor                      | 38        | 44     | 5.71%   |
| HGST                        | 36        | 44     | 5.41%   |
| Crucial                     | 20        | 20     | 3%      |
| Kingston                    | 17        | 17     | 2.55%   |
| SK hynix                    | 12        | 14     | 1.8%    |
| SanDisk                     | 10        | 11     | 1.5%    |
| Micron Technology           | 9         | 9      | 1.35%   |
| Intel                       | 7         | 10     | 1.05%   |
| Fujitsu                     | 6         | 6      | 0.9%    |
| Unknown                     | 5         | 10     | 0.75%   |
| OCZ                         | 3         | 3      | 0.45%   |
| Drevo                       | 3         | 3      | 0.45%   |
| ASMT                        | 3         | 3      | 0.45%   |
| TCSUNBOW                    | 2         | 2      | 0.3%    |
| Intenso                     | 2         | 3      | 0.3%    |
| Corsair                     | 2         | 3      | 0.3%    |
| BAITITON                    | 2         | 4      | 0.3%    |
| Yangtze Memory Technologies | 1         | 1      | 0.15%   |
| WINTEC                      | 1         | 1      | 0.15%   |
| WDC WDS2                    | 1         | 1      | 0.15%   |
| WD MediaMax                 | 1         | 1      | 0.15%   |
| USB3.0                      | 1         | 1      | 0.15%   |
| Transcend                   | 1         | 2      | 0.15%   |
| Teclast                     | 1         | 1      | 0.15%   |
| SSSTC                       | 1         | 1      | 0.15%   |
| QUANTUM                     | 1         | 1      | 0.15%   |
| NGFF                        | 1         | 1      | 0.15%   |
| LITEONIT                    | 1         | 1      | 0.15%   |
| LITEON                      | 1         | 1      | 0.15%   |
| KingSpec                    | 1         | 1      | 0.15%   |
| KingDian                    | 1         | 1      | 0.15%   |
| GSemi                       | 1         | 1      | 0.15%   |
| Emtec                       | 1         | 1      | 0.15%   |
| CT1000P1                    | 1         | 2      | 0.15%   |
| Apple                       | 1         | 1      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 176       | 227    | 32.77%  |
| WDC                 | 125       | 152    | 23.28%  |
| Hitachi             | 77        | 81     | 14.34%  |
| Toshiba             | 44        | 45     | 8.19%   |
| Maxtor              | 38        | 44     | 7.08%   |
| HGST                | 36        | 44     | 6.7%    |
| Samsung Electronics | 23        | 25     | 4.28%   |
| Fujitsu             | 6         | 6      | 1.12%   |
| Unknown             | 5         | 10     | 0.93%   |
| ASMT                | 3         | 3      | 0.56%   |
| WD MediaMax         | 1         | 1      | 0.19%   |
| USB3.0              | 1         | 1      | 0.19%   |
| QUANTUM             | 1         | 1      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 506       | 641    | 79.56%  |
| SSD  | 113       | 124    | 17.77%  |
| NVMe | 17        | 22     | 2.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                        | 2         | 4      | 13.33%  |
| Seagate ST500DM002-1BD142 500GB                  | 2         | 3      | 13.33%  |
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 6.67%   |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 6.67%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 6.67%   |
| Seagate STM3250318AS 250GB                       | 1         | 1      | 6.67%   |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 6.67%   |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 6.67%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 6.67%   |
| Hitachi HTS543216L9A300 160GB                    | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 9      | 40%     |
| WDC                 | 4         | 4      | 26.67%  |
| Hitachi             | 3         | 3      | 20%     |
| Toshiba             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4371      | 8602   | 54.69%  |
| Works    | 2989      | 5340   | 37.4%   |
| Malfunc  | 618       | 787    | 7.73%   |
| Failed   | 15        | 18     | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4918      | 54.63%  |
| AMD                              | 1232      | 13.68%  |
| Samsung Electronics              | 749       | 8.32%   |
| SanDisk                          | 307       | 3.41%   |
| Nvidia                           | 184       | 2.04%   |
| SK hynix                         | 174       | 1.93%   |
| Phison Electronics               | 158       | 1.75%   |
| ASMedia Technology               | 144       | 1.6%    |
| Kingston Technology Company      | 142       | 1.58%   |
| JMicron Technology               | 136       | 1.51%   |
| Marvell Technology Group         | 129       | 1.43%   |
| Toshiba America Info Systems     | 112       | 1.24%   |
| Micron/Crucial Technology        | 112       | 1.24%   |
| Micron Technology                | 100       | 1.11%   |
| KIOXIA                           | 86        | 0.96%   |
| VIA Technologies                 | 58        | 0.64%   |
| Silicon Motion                   | 39        | 0.43%   |
| Silicon Integrated Systems [SiS] | 34        | 0.38%   |
| ADATA Technology                 | 20        | 0.22%   |
| Union Memory (Shenzhen)          | 16        | 0.18%   |
| Adaptec                          | 16        | 0.18%   |
| Solid State Storage Technology   | 15        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 15        | 0.17%   |
| Silicon Image                    | 12        | 0.13%   |
| LSI Logic / Symbios Logic        | 11        | 0.12%   |
| Broadcom / LSI                   | 10        | 0.11%   |
| Apple                            | 9         | 0.1%    |
| Realtek Semiconductor            | 8         | 0.09%   |
| Shenzhen Longsys Electronics     | 7         | 0.08%   |
| Lite-On Technology               | 7         | 0.08%   |
| Lenovo                           | 7         | 0.08%   |
| Seagate Technology               | 6         | 0.07%   |
| Yangtze Memory Technologies      | 4         | 0.04%   |
| Hewlett-Packard                  | 4         | 0.04%   |
| Promise Technology               | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| Broadcom                         | 3         | 0.03%   |
| ULi Electronics                  | 2         | 0.02%   |
| INNOGRIT                         | 2         | 0.02%   |
| HighPoint Technologies           | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 819       | 7.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 386       | 3.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 368       | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 301       | 2.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 277       | 2.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 251       | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 221       | 2.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 205       | 1.95%   |
| Samsung NVMe SSD Controller 980                                                | 186       | 1.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 175       | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 171       | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 160       | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 157       | 1.49%   |
| AMD 400 Series Chipset SATA Controller                                         | 157       | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 150       | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 148       | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 144       | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 143       | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 134       | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 134       | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 133       | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 115       | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 115       | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 113       | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 112       | 1.07%   |
| Intel SATA Controller [RAID mode]                                              | 112       | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 112       | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                          | 106       | 1.01%   |
| Phison E12 NVMe Controller                                                     | 99        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 94        | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 91        | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 86        | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 85        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 81        | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 79        | 0.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 76        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 75        | 0.71%   |
| JMicron JMB363 SATA/IDE Controller                                             | 73        | 0.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 73        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 69        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5086      | 55.93%  |
| NVMe | 2033      | 22.36%  |
| IDE  | 1330      | 14.63%  |
| RAID | 624       | 6.86%   |
| SCSI | 11        | 0.12%   |
| SAS  | 10        | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 5660      | 77.23%  |
| AMD                      | 1613      | 22.01%  |
| ARM                      | 50        | 0.68%   |
| CentaurHauls             | 4         | 0.05%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.01%   |
| Unknown                  | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 97        | 1.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 80        | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 76        | 1.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 75        | 1.02%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 73        | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 57        | 0.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 57        | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 55        | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 53        | 0.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 52        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 51        | 0.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 51        | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 49        | 0.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 49        | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 47        | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 46        | 0.63%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 44        | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 42        | 0.57%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 41        | 0.56%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 41        | 0.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 0.53%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 37        | 0.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 37        | 0.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 36        | 0.49%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 36        | 0.49%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 36        | 0.49%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 35        | 0.48%   |
| ARM Processor                                 | 34        | 0.46%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 32        | 0.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 32        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 31        | 0.42%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 30        | 0.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 0.41%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 30        | 0.41%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 29        | 0.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 0.38%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 28        | 0.38%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 28        | 0.38%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 28        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1437      | 19.57%  |
| Intel Core i5           | 1395      | 19%     |
| Intel Core i3           | 499       | 6.8%    |
| Other                   | 434       | 5.91%   |
| Intel Core 2 Duo        | 420       | 5.72%   |
| Intel Celeron           | 398       | 5.42%   |
| AMD Ryzen 5             | 364       | 4.96%   |
| AMD Ryzen 7             | 294       | 4%      |
| Intel Atom              | 262       | 3.57%   |
| Intel Pentium           | 140       | 1.91%   |
| Intel Pentium Dual-Core | 123       | 1.68%   |
| Intel Xeon              | 107       | 1.46%   |
| Intel Core 2 Quad       | 105       | 1.43%   |
| AMD Ryzen 9             | 80        | 1.09%   |
| Intel Core 2            | 75        | 1.02%   |
| AMD FX                  | 75        | 1.02%   |
| AMD Ryzen 3             | 74        | 1.01%   |
| Intel Pentium Dual      | 72        | 0.98%   |
| Intel Pentium 4         | 65        | 0.89%   |
| AMD A8                  | 57        | 0.78%   |
| AMD E1                  | 53        | 0.72%   |
| AMD A10                 | 50        | 0.68%   |
| Intel Core i9           | 49        | 0.67%   |
| AMD Athlon 64 X2        | 49        | 0.67%   |
| AMD A4                  | 47        | 0.64%   |
| AMD A6                  | 45        | 0.61%   |
| Intel Genuine           | 40        | 0.54%   |
| AMD Sempron             | 33        | 0.45%   |
| AMD Phenom II X4        | 31        | 0.42%   |
| AMD E2                  | 26        | 0.35%   |
| Intel Pentium D         | 24        | 0.33%   |
| Intel Pentium Silver    | 22        | 0.3%    |
| AMD Phenom II X6        | 20        | 0.27%   |
| AMD Athlon II X2        | 19        | 0.26%   |
| AMD Ryzen 7 PRO         | 18        | 0.25%   |
| AMD Ryzen 5 PRO         | 18        | 0.25%   |
| AMD Athlon              | 18        | 0.25%   |
| Intel Pentium M         | 16        | 0.22%   |
| AMD Phenom              | 16        | 0.22%   |
| AMD Athlon II X4        | 16        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3001      | 40.86%  |
| 4       | 2755      | 37.51%  |
| 6       | 590       | 8.03%   |
| 8       | 447       | 6.09%   |
| 1       | 307       | 4.18%   |
| 12      | 80        | 1.09%   |
| 10      | 45        | 0.61%   |
| 3       | 36        | 0.49%   |
| 14      | 35        | 0.48%   |
| 16      | 27        | 0.37%   |
| Unknown | 7         | 0.1%    |
| 24      | 5         | 0.07%   |
| 40      | 2         | 0.03%   |
| 28      | 2         | 0.03%   |
| 20      | 2         | 0.03%   |
| 5       | 2         | 0.03%   |
| 64      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7270      | 99.19%  |
| 2       | 50        | 0.68%   |
| Unknown | 5         | 0.07%   |
| 4       | 3         | 0.04%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4413      | 60.09%  |
| 1       | 2918      | 39.73%  |
| Unknown | 7         | 0.1%    |
| 4       | 5         | 0.07%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7124      | 97.04%  |
| 32-bit         | 124       | 1.69%   |
| Unknown        | 91        | 1.24%   |
| 64-bit         | 2         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1806      | 23.59%  |
| 0x206a7    | 371       | 4.85%   |
| 0x306a9    | 359       | 4.69%   |
| 0x1067a    | 300       | 3.92%   |
| 0x306c3    | 294       | 3.84%   |
| 0x806ea    | 176       | 2.3%    |
| 0x906ea    | 152       | 1.99%   |
| 0x806ec    | 151       | 1.97%   |
| 0x806c1    | 151       | 1.97%   |
| 0x40651    | 150       | 1.96%   |
| 0x806e9    | 147       | 1.92%   |
| 0x506e3    | 139       | 1.82%   |
| 0x406e3    | 139       | 1.82%   |
| 0x6fd      | 134       | 1.75%   |
| 0x906e9    | 129       | 1.68%   |
| 0x20655    | 114       | 1.49%   |
| 0x08108109 | 106       | 1.38%   |
| 0x10676    | 104       | 1.36%   |
| 0x08701021 | 93        | 1.21%   |
| 0x306d4    | 91        | 1.19%   |
| 0x406c4    | 85        | 1.11%   |
| 0x6fb      | 77        | 1.01%   |
| 0x406c3    | 74        | 0.97%   |
| 0x30678    | 72        | 0.94%   |
| 0x0a50000c | 70        | 0.91%   |
| 0x20652    | 66        | 0.86%   |
| 0x706e5    | 64        | 0.84%   |
| 0x706a1    | 63        | 0.82%   |
| 0x706a8    | 55        | 0.72%   |
| 0x806eb    | 54        | 0.71%   |
| 0x08608103 | 54        | 0.71%   |
| 0x6f6      | 52        | 0.68%   |
| 0x010000c8 | 52        | 0.68%   |
| 0x06006705 | 50        | 0.65%   |
| 0x506c9    | 49        | 0.64%   |
| 0x106e5    | 48        | 0.63%   |
| 0x906ed    | 45        | 0.59%   |
| 0xa0652    | 44        | 0.57%   |
| 0x106ca    | 44        | 0.57%   |
| 0x08600106 | 43        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1095      | 14.91%  |
| Haswell          | 590       | 8.03%   |
| Penryn           | 513       | 6.98%   |
| SandyBridge      | 474       | 6.45%   |
| IvyBridge        | 459       | 6.25%   |
| Skylake          | 367       | 5%      |
| Core             | 356       | 4.85%   |
| Silvermont       | 292       | 3.97%   |
| Zen 2            | 250       | 3.4%    |
| Westmere         | 230       | 3.13%   |
| Unknown          | 230       | 3.13%   |
| Zen+             | 209       | 2.85%   |
| TigerLake        | 208       | 2.83%   |
| Zen 3            | 181       | 2.46%   |
| K10              | 168       | 2.29%   |
| Goldmont plus    | 154       | 2.1%    |
| CometLake        | 143       | 1.95%   |
| Broadwell        | 127       | 1.73%   |
| Zen              | 118       | 1.61%   |
| Excavator        | 118       | 1.61%   |
| K8 Hammer        | 112       | 1.52%   |
| IceLake          | 109       | 1.48%   |
| Piledriver       | 99        | 1.35%   |
| Bonnell          | 98        | 1.33%   |
| NetBurst         | 97        | 1.32%   |
| Nehalem          | 95        | 1.29%   |
| Alderlake Hybrid | 71        | 0.97%   |
| Goldmont         | 70        | 0.95%   |
| P6               | 60        | 0.82%   |
| Jaguar           | 53        | 0.72%   |
| Puma             | 50        | 0.68%   |
| Bobcat           | 39        | 0.53%   |
| K10 Llano        | 35        | 0.48%   |
| Steamroller      | 32        | 0.44%   |
| K8 & K10 hybrid  | 18        | 0.25%   |
| Tremont          | 12        | 0.16%   |
| Bulldozer        | 12        | 0.16%   |
| K6               | 1         | 0.01%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4114      | 47.89%  |
| Nvidia                                       | 2424      | 28.22%  |
| AMD                                          | 1983      | 23.08%  |
| Silicon Integrated Systems [SiS]             | 21        | 0.24%   |
| Matrox Electronics Systems                   | 17        | 0.2%    |
| VIA Technologies                             | 16        | 0.19%   |
| ASPEED Technology                            | 8         | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.03%   |
| S3 Graphics                                  | 2         | 0.02%   |
| ATI Technologies                             | 2         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 327       | 3.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 264       | 2.95%   |
| Intel UHD Graphics 620                                                                   | 204       | 2.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 192       | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 190       | 2.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 188       | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 160       | 1.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 154       | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 154       | 1.72%   |
| Intel HD Graphics 620                                                                    | 149       | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 132       | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 132       | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 131       | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 116       | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 113       | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 108       | 1.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 107       | 1.2%    |
| AMD Renoir                                                                               | 103       | 1.15%   |
| Intel HD Graphics 5500                                                                   | 100       | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 98        | 1.1%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 97        | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 94        | 1.05%   |
| Intel HD Graphics 630                                                                    | 88        | 0.98%   |
| Intel HD Graphics 530                                                                    | 85        | 0.95%   |
| AMD Lucienne                                                                             | 85        | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 77        | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 76        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 76        | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 74        | 0.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 72        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 70        | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 66        | 0.74%   |
| Nvidia GT218 [GeForce 210]                                                               | 61        | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 60        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 59        | 0.66%   |
| Intel HD Graphics 500                                                                    | 59        | 0.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 59        | 0.66%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 59        | 0.66%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 56        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 56        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2903      | 39.44%  |
| 1 x AMD                 | 1543      | 20.96%  |
| 1 x Nvidia              | 1375      | 18.68%  |
| Intel + Nvidia          | 943       | 12.81%  |
| Intel + AMD             | 196       | 2.66%   |
| 2 x AMD                 | 156       | 2.12%   |
| AMD + Nvidia            | 86        | 1.17%   |
| Other                   | 57        | 0.77%   |
| 1 x SiS                 | 21        | 0.29%   |
| 2 x Intel               | 20        | 0.27%   |
| 1 x VIA                 | 16        | 0.22%   |
| 2 x Nvidia              | 11        | 0.15%   |
| 1 x Matrox              | 9         | 0.12%   |
| Nvidia + Matrox         | 4         | 0.05%   |
| 1 x ASPEED              | 4         | 0.05%   |
| 1 x XGI                 | 3         | 0.04%   |
| Nvidia + ASPEED         | 3         | 0.04%   |
| AMD + Matrox            | 3         | 0.04%   |
| 1 x S3 Graphics         | 2         | 0.03%   |
| 3 x AMD                 | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + ASPEED            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6024      | 80.76%  |
| Proprietary | 1169      | 15.67%  |
| Unknown     | 266       | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4042      | 53.35%  |
| 0.01-0.5   | 1037      | 13.69%  |
| 1.01-2.0   | 1003      | 13.24%  |
| 0.51-1.0   | 660       | 8.71%   |
| 3.01-4.0   | 395       | 5.21%   |
| 7.01-8.0   | 192       | 2.53%   |
| 5.01-6.0   | 152       | 2.01%   |
| 2.01-3.0   | 47        | 0.62%   |
| 8.01-16.0  | 46        | 0.61%   |
| 4.01-5.0   | 1         | 0.01%   |
| 16.01-24.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1127      | 14.66%  |
| AU Optronics            | 903       | 11.75%  |
| Chimei Innolux          | 699       | 9.09%   |
| BOE                     | 631       | 8.21%   |
| LG Display              | 623       | 8.1%    |
| Hewlett-Packard         | 385       | 5.01%   |
| Goldstar                | 347       | 4.51%   |
| Philips                 | 344       | 4.47%   |
| Ancor Communications    | 287       | 3.73%   |
| Acer                    | 252       | 3.28%   |
| Dell                    | 194       | 2.52%   |
| BenQ                    | 173       | 2.25%   |
| Sharp                   | 143       | 1.86%   |
| Chi Mei Optoelectronics | 141       | 1.83%   |
| Apple                   | 139       | 1.81%   |
| AOC                     | 132       | 1.72%   |
| Lenovo                  | 107       | 1.39%   |
| Sony                    | 74        | 0.96%   |
| HannStar                | 74        | 0.96%   |
| LG Philips              | 65        | 0.85%   |
| PANDA                   | 62        | 0.81%   |
| ASUSTek Computer        | 46        | 0.6%    |
| InfoVision              | 44        | 0.57%   |
| Unknown                 | 42        | 0.55%   |
| LG Electronics          | 39        | 0.51%   |
| MSI                     | 28        | 0.36%   |
| CPT                     | 25        | 0.33%   |
| CSO                     | 23        | 0.3%    |
| Eizo                    | 22        | 0.29%   |
| Fujitsu Siemens         | 21        | 0.27%   |
| Toshiba                 | 17        | 0.22%   |
| Panasonic               | 16        | 0.21%   |
| Iiyama                  | 15        | 0.2%    |
| Vestel Elektronik       | 14        | 0.18%   |
| Packard Bell            | 14        | 0.18%   |
| Quanta Display          | 13        | 0.17%   |
| LGD                     | 13        | 0.17%   |
| NEC Computers           | 12        | 0.16%   |
| Mi                      | 12        | 0.16%   |
| RTK                     | 11        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 69        | 0.87%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 43        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 39        | 0.49%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 35        | 0.44%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 35        | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 34        | 0.43%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 33        | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 33        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 32        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 30        | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 29        | 0.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 28        | 0.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 27        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 26        | 0.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 25        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 24        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 24        | 0.3%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 24        | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 23        | 0.29%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 23        | 0.29%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 22        | 0.28%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 22        | 0.28%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 22        | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 21        | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 21        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 20        | 0.25%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 18        | 0.23%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 18        | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 18        | 0.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 18        | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 17        | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 17        | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 17        | 0.22%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                      | 16        | 0.2%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 15        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 15        | 0.19%   |
| AU Optronics LCD Monitor AUO18D4 1280x800 216x135mm 10.0-inch            | 15        | 0.19%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 14        | 0.18%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 14        | 0.18%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 14        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3214      | 43.45%  |
| 1366x768 (WXGA)    | 1505      | 20.35%  |
| 3840x2160 (4K)     | 376       | 5.08%   |
| 1280x1024 (SXGA)   | 322       | 4.35%   |
| 1280x800 (WXGA)    | 302       | 4.08%   |
| 1440x900 (WXGA+)   | 236       | 3.19%   |
| 2560x1440 (QHD)    | 234       | 3.16%   |
| 1680x1050 (WSXGA+) | 220       | 2.97%   |
| 1600x900 (HD+)     | 198       | 2.68%   |
| 1920x1200 (WUXGA)  | 121       | 1.64%   |
| 1360x768           | 72        | 0.97%   |
| Unknown            | 61        | 0.82%   |
| 1024x600           | 60        | 0.81%   |
| 2560x1080          | 50        | 0.68%   |
| 2560x1600          | 41        | 0.55%   |
| 3440x1440          | 39        | 0.53%   |
| 1024x768 (XGA)     | 38        | 0.51%   |
| 2160x1440          | 36        | 0.49%   |
| 3840x1080          | 31        | 0.42%   |
| 2880x1800          | 25        | 0.34%   |
| 3840x2400          | 18        | 0.24%   |
| 1920x540           | 15        | 0.2%    |
| 1600x1200          | 15        | 0.2%    |
| 1280x720 (HD)      | 12        | 0.16%   |
| 1920x1280          | 11        | 0.15%   |
| 800x1280           | 10        | 0.14%   |
| 3000x2000          | 10        | 0.14%   |
| 3200x1800 (QHD+)   | 9         | 0.12%   |
| 2736x1824          | 9         | 0.12%   |
| 3840x1600          | 6         | 0.08%   |
| 3072x1920          | 6         | 0.08%   |
| 2880x1920          | 6         | 0.08%   |
| 2520x1680          | 5         | 0.07%   |
| 2288x1287          | 5         | 0.07%   |
| 1800x1200          | 5         | 0.07%   |
| 1280x768           | 5         | 0.07%   |
| 4480x1440          | 4         | 0.05%   |
| 2256x1504          | 4         | 0.05%   |
| 2240x1400          | 4         | 0.05%   |
| 1400x1050          | 4         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2354      | 30.56%  |
| 13      | 644       | 8.36%   |
| 24      | 525       | 6.81%   |
| 27      | 510       | 6.62%   |
| 21      | 483       | 6.27%   |
| 14      | 429       | 5.57%   |
| 23      | 410       | 5.32%   |
| Unknown | 393       | 5.1%    |
| 17      | 358       | 4.65%   |
| 19      | 286       | 3.71%   |
| 18      | 154       | 2%      |
| 12      | 146       | 1.9%    |
| 20      | 124       | 1.61%   |
| 22      | 114       | 1.48%   |
| 31      | 91        | 1.18%   |
| 10      | 81        | 1.05%   |
| 34      | 80        | 1.04%   |
| 11      | 75        | 0.97%   |
| 16      | 56        | 0.73%   |
| 40      | 54        | 0.7%    |
| 84      | 40        | 0.52%   |
| 72      | 34        | 0.44%   |
| 54      | 33        | 0.43%   |
| 25      | 24        | 0.31%   |
| 32      | 23        | 0.3%    |
| 26      | 14        | 0.18%   |
| 28      | 13        | 0.17%   |
| 52      | 12        | 0.16%   |
| 47      | 12        | 0.16%   |
| 46      | 12        | 0.16%   |
| 48      | 11        | 0.14%   |
| 65      | 10        | 0.13%   |
| 42      | 9         | 0.12%   |
| 37      | 9         | 0.12%   |
| 7       | 9         | 0.12%   |
| 39      | 7         | 0.09%   |
| 36      | 7         | 0.09%   |
| 29      | 6         | 0.08%   |
| 8       | 6         | 0.08%   |
| 142     | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3185      | 41.84%  |
| 501-600        | 1362      | 17.89%  |
| 401-500        | 987       | 12.97%  |
| 201-300        | 675       | 8.87%   |
| 351-400        | 440       | 5.78%   |
| Unknown        | 393       | 5.16%   |
| 601-700        | 160       | 2.1%    |
| 701-800        | 113       | 1.48%   |
| 1001-1500      | 105       | 1.38%   |
| 1501-2000      | 79        | 1.04%   |
| 801-900        | 76        | 1%      |
| 901-1000       | 14        | 0.18%   |
| 1-100          | 10        | 0.13%   |
| 101-200        | 8         | 0.11%   |
| More than 2000 | 5         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5200      | 73.32%  |
| 16/10   | 947       | 13.35%  |
| Unknown | 326       | 4.6%    |
| 5/4     | 307       | 4.33%   |
| 3/2     | 102       | 1.44%   |
| 21/9    | 90        | 1.27%   |
| 4/3     | 81        | 1.14%   |
| 6/5     | 13        | 0.18%   |
| 32/9    | 10        | 0.14%   |
| 0.67    | 9         | 0.13%   |
| 1.00    | 5         | 0.07%   |
| 2.65    | 1         | 0.01%   |
| 2.21    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2349      | 30.75%  |
| 201-250        | 1247      | 16.32%  |
| 81-90          | 780       | 10.21%  |
| 151-200        | 568       | 7.44%   |
| 301-350        | 525       | 6.87%   |
| Unknown        | 393       | 5.14%   |
| 71-80          | 297       | 3.89%   |
| 141-150        | 248       | 3.25%   |
| 351-500        | 206       | 2.7%    |
| 121-130        | 177       | 2.32%   |
| 251-300        | 159       | 2.08%   |
| More than 1000 | 158       | 2.07%   |
| 61-70          | 131       | 1.71%   |
| 501-1000       | 128       | 1.68%   |
| 41-50          | 80        | 1.05%   |
| 51-60          | 77        | 1.01%   |
| 111-120        | 45        | 0.59%   |
| 131-140        | 33        | 0.43%   |
| 91-100         | 21        | 0.27%   |
| 1-40           | 17        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2624      | 35.05%  |
| 101-120       | 1967      | 26.28%  |
| 121-160       | 1808      | 24.15%  |
| 161-240       | 417       | 5.57%   |
| Unknown       | 393       | 5.25%   |
| 1-50          | 147       | 1.96%   |
| More than 240 | 130       | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6183      | 82.58%  |
| 2     | 933       | 12.46%  |
| 0     | 283       | 3.78%   |
| 3     | 84        | 1.12%   |
| 4     | 4         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4015      | 36.22%  |
| Intel                             | 3166      | 28.56%  |
| Qualcomm Atheros                  | 1341      | 12.1%   |
| Broadcom                          | 657       | 5.93%   |
| Marvell Technology Group          | 213       | 1.92%   |
| TP-Link                           | 157       | 1.42%   |
| Broadcom Limited                  | 156       | 1.41%   |
| Nvidia                            | 141       | 1.27%   |
| Ralink Technology                 | 135       | 1.22%   |
| Ralink                            | 118       | 1.06%   |
| MediaTek                          | 112       | 1.01%   |
| Huawei Technologies               | 55        | 0.5%    |
| Qualcomm Atheros Communications   | 54        | 0.49%   |
| ASIX Electronics                  | 52        | 0.47%   |
| Xiaomi                            | 44        | 0.4%    |
| D-Link System                     | 42        | 0.38%   |
| Samsung Electronics               | 41        | 0.37%   |
| D-Link                            | 38        | 0.34%   |
| VIA Technologies                  | 32        | 0.29%   |
| Sitecom Europe                    | 31        | 0.28%   |
| Dell                              | 30        | 0.27%   |
| NetGear                           | 28        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 25        | 0.23%   |
| ASUSTek Computer                  | 22        | 0.2%    |
| Sierra Wireless                   | 21        | 0.19%   |
| Microsoft                         | 21        | 0.19%   |
| Ericsson Business Mobile Networks | 21        | 0.19%   |
| OPPO Electronics                  | 20        | 0.18%   |
| JMicron Technology                | 19        | 0.17%   |
| Qualcomm                          | 17        | 0.15%   |
| Attansic Technology               | 17        | 0.15%   |
| DisplayLink                       | 15        | 0.14%   |
| Microchip Technology              | 14        | 0.13%   |
| Hewlett-Packard                   | 13        | 0.12%   |
| Belkin Components                 | 13        | 0.12%   |
| ZTE WCDMA Technologies MSM        | 11        | 0.1%    |
| OnePlus Technology (Shenzhen)     | 9         | 0.08%   |
| Lenovo                            | 9         | 0.08%   |
| Gemtek                            | 9         | 0.08%   |
| T & A Mobile Phones               | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2719      | 21.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 466       | 3.63%   |
| Intel Wi-Fi 6 AX200                                                     | 249       | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 237       | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 220       | 1.72%   |
| Intel Wireless 8265 / 8275                                              | 200       | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 199       | 1.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 195       | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 191       | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 178       | 1.39%   |
| Intel Wireless 7265                                                     | 171       | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 169       | 1.32%   |
| Intel Wireless 3165                                                     | 159       | 1.24%   |
| Intel Wi-Fi 6 AX201                                                     | 148       | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 147       | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                    | 119       | 0.93%   |
| Intel I211 Gigabit Network Connection                                   | 112       | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 111       | 0.87%   |
| Intel Wireless 7260                                                     | 109       | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 96        | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                       | 92        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 89        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 89        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 88        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 84        | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 0.65%   |
| Intel Wireless 8260                                                     | 82        | 0.64%   |
| Intel 82579V Gigabit Network Connection                                 | 80        | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 79        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 77        | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 75        | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 73        | 0.57%   |
| Intel WiFi Link 5100                                                    | 70        | 0.55%   |
| Intel Ethernet Connection I217-LM                                       | 69        | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 66        | 0.51%   |
| Broadcom BCM43142 802.11b/g/n                                           | 66        | 0.51%   |
| Intel Wireless-AC 9260                                                  | 59        | 0.46%   |
| Intel Ethernet Controller I225-V                                        | 57        | 0.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 57        | 0.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 56        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2385      | 40%     |
| Qualcomm Atheros                      | 1130      | 18.95%  |
| Realtek Semiconductor                 | 1074      | 18.01%  |
| Broadcom                              | 433       | 7.26%   |
| TP-Link                               | 140       | 2.35%   |
| Ralink Technology                     | 135       | 2.26%   |
| Ralink                                | 118       | 1.98%   |
| MediaTek                              | 103       | 1.73%   |
| Broadcom Limited                      | 91        | 1.53%   |
| Qualcomm Atheros Communications       | 54        | 0.91%   |
| D-Link                                | 37        | 0.62%   |
| D-Link System                         | 34        | 0.57%   |
| Sitecom Europe                        | 30        | 0.5%    |
| NetGear                               | 27        | 0.45%   |
| Sierra Wireless                       | 21        | 0.35%   |
| ASUSTek Computer                      | 21        | 0.35%   |
| Microsoft                             | 18        | 0.3%    |
| Dell                                  | 18        | 0.3%    |
| Marvell Technology Group              | 14        | 0.23%   |
| Belkin Components                     | 13        | 0.22%   |
| Gemtek                                | 9         | 0.15%   |
| Ericsson Business Mobile Networks     | 7         | 0.12%   |
| Qualcomm                              | 6         | 0.1%    |
| Linksys                               | 6         | 0.1%    |
| Fibocom                               | 6         | 0.1%    |
| AVM                                   | 6         | 0.1%    |
| ZyDAS                                 | 5         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.07%   |
| Edimax Technology                     | 3         | 0.05%   |
| ZyXEL Communications                  | 2         | 0.03%   |
| U.S. Robotics                         | 2         | 0.03%   |
| Qcom                                  | 2         | 0.03%   |
| Hewlett-Packard                       | 2         | 0.03%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Fiberline                             | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |
| AboCom Systems                        | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 249       | 4.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 237       | 3.95%   |
| Intel Wireless 8265 / 8275                                              | 200       | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 199       | 3.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 195       | 3.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 178       | 2.97%   |
| Intel Wireless 7265                                                     | 171       | 2.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 169       | 2.82%   |
| Intel Wireless 3165                                                     | 159       | 2.65%   |
| Intel Wi-Fi 6 AX201                                                     | 148       | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 147       | 2.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 111       | 1.85%   |
| Intel Wireless 7260                                                     | 109       | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 96        | 1.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 89        | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 88        | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 84        | 1.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 1.38%   |
| Intel Wireless 8260                                                     | 82        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 79        | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 77        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 75        | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 73        | 1.22%   |
| Intel WiFi Link 5100                                                    | 70        | 1.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 66        | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                           | 66        | 1.1%    |
| Intel Wireless-AC 9260                                                  | 59        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 57        | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 56        | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 51        | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 51        | 0.85%   |
| Realtek 802.11ac NIC                                                    | 51        | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 50        | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                         | 49        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 48        | 0.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 45        | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 44        | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 44        | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 41        | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 40        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3600      | 54.54%  |
| Intel                            | 1490      | 22.57%  |
| Qualcomm Atheros                 | 348       | 5.27%   |
| Broadcom                         | 305       | 4.62%   |
| Marvell Technology Group         | 199       | 3.01%   |
| Nvidia                           | 140       | 2.12%   |
| Broadcom Limited                 | 66        | 1%      |
| ASIX Electronics                 | 52        | 0.79%   |
| Huawei Technologies              | 45        | 0.68%   |
| Xiaomi                           | 44        | 0.67%   |
| VIA Technologies                 | 30        | 0.45%   |
| Samsung Electronics              | 30        | 0.45%   |
| Silicon Integrated Systems [SiS] | 23        | 0.35%   |
| OPPO Electronics                 | 20        | 0.3%    |
| JMicron Technology               | 19        | 0.29%   |
| TP-Link                          | 17        | 0.26%   |
| Attansic Technology              | 17        | 0.26%   |
| DisplayLink                      | 15        | 0.23%   |
| Qualcomm                         | 11        | 0.17%   |
| ZTE WCDMA Technologies MSM       | 10        | 0.15%   |
| Microchip Technology             | 10        | 0.15%   |
| MediaTek                         | 9         | 0.14%   |
| Lenovo                           | 9         | 0.14%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.12%   |
| D-Link System                    | 8         | 0.12%   |
| Aquantia                         | 8         | 0.12%   |
| Apple                            | 7         | 0.11%   |
| HMD Global                       | 6         | 0.09%   |
| 3Com                             | 6         | 0.09%   |
| Motorola PCS                     | 5         | 0.08%   |
| ICS Advent                       | 5         | 0.08%   |
| Google                           | 5         | 0.08%   |
| T & A Mobile Phones              | 4         | 0.06%   |
| Hewlett-Packard                  | 4         | 0.06%   |
| LG Electronics                   | 3         | 0.05%   |
| Spreadtrum Communications        | 2         | 0.03%   |
| NetXen Incorporated              | 2         | 0.03%   |
| Foxconn / Hon Hai                | 2         | 0.03%   |
| ULi Electronics                  | 1         | 0.02%   |
| SysKonnect                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2719      | 40.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 466       | 6.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 220       | 3.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 191       | 2.85%   |
| Intel Ethernet Connection (2) I219-V                              | 119       | 1.78%   |
| Intel I211 Gigabit Network Connection                             | 112       | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 92        | 1.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 89        | 1.33%   |
| Intel 82579V Gigabit Network Connection                           | 80        | 1.19%   |
| Intel Ethernet Connection I217-LM                                 | 69        | 1.03%   |
| Intel Ethernet Controller I225-V                                  | 57        | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 55        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 48        | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 46        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 44        | 0.66%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 42        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 41        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 40        | 0.6%    |
| Nvidia MCP61 Ethernet                                             | 39        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 39        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 37        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 36        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 36        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 36        | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 33        | 0.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 33        | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 32        | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 31        | 0.46%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 31        | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 31        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 30        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 30        | 0.45%   |
| Intel Ethernet Connection (6) I219-V                              | 29        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 28        | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 28        | 0.42%   |
| Huawei WLZ-AN00                                                   | 28        | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 25        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6224      | 51.93%  |
| WiFi     | 5638      | 47.04%  |
| Modem    | 111       | 0.93%   |
| Unknown  | 13        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4385      | 58.64%  |
| Ethernet | 3089      | 41.31%  |
| Unknown  | 3         | 0.04%   |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3949      | 53.7%   |
| 1     | 3078      | 41.85%  |
| 0     | 186       | 2.53%   |
| 3     | 119       | 1.62%   |
| 4     | 15        | 0.2%    |
| 5     | 3         | 0.04%   |
| 6     | 2         | 0.03%   |
| 12    | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6921      | 93.48%  |
| Yes  | 483       | 6.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1853      | 43.74%  |
| Realtek Semiconductor           | 522       | 12.32%  |
| Qualcomm Atheros Communications | 260       | 6.14%   |
| Cambridge Silicon Radio         | 250       | 5.9%    |
| IMC Networks                    | 221       | 5.22%   |
| Broadcom                        | 220       | 5.19%   |
| Lite-On Technology              | 186       | 4.39%   |
| Apple                           | 153       | 3.61%   |
| Foxconn / Hon Hai               | 144       | 3.4%    |
| Hewlett-Packard                 | 68        | 1.61%   |
| ASUSTek Computer                | 63        | 1.49%   |
| Realtek                         | 59        | 1.39%   |
| Dell                            | 45        | 1.06%   |
| Toshiba                         | 35        | 0.83%   |
| Ralink                          | 35        | 0.83%   |
| MediaTek                        | 19        | 0.45%   |
| Alps Electric                   | 16        | 0.38%   |
| Marvell Semiconductor           | 13        | 0.31%   |
| TP-Link                         | 10        | 0.24%   |
| Integrated System Solution      | 10        | 0.24%   |
| Ralink Technology               | 7         | 0.17%   |
| Foxconn International           | 5         | 0.12%   |
| Belkin Components               | 5         | 0.12%   |
| Sitecom Europe                  | 4         | 0.09%   |
| Chicony Electronics             | 4         | 0.09%   |
| Askey Computer                  | 4         | 0.09%   |
| Taiyo Yuden                     | 3         | 0.07%   |
| Conwise Technology              | 3         | 0.07%   |
| SINO WEALTH                     | 2         | 0.05%   |
| ISSC                            | 2         | 0.05%   |
| D-Link System                   | 2         | 0.05%   |
| Accel Semiconductor             | 2         | 0.05%   |
| USI                             | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| HTC (High Tech Computer)        | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 748       | 17.65%  |
| Realtek Bluetooth Radio                                                             | 355       | 8.38%   |
| Intel AX201 Bluetooth                                                               | 315       | 7.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 270       | 6.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 250       | 5.9%    |
| Intel AX200 Bluetooth                                                               | 231       | 5.45%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 129       | 3.04%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 102       | 2.41%   |
| IMC Networks Bluetooth Device                                                       | 102       | 2.41%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 77        | 1.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 64        | 1.51%   |
| IMC Networks Bluetooth Radio                                                        | 57        | 1.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 56        | 1.32%   |
| Apple Bluetooth Host Controller                                                     | 56        | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 55        | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 53        | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 48        | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 48        | 1.13%   |
| Realtek 802.11ac WLAN Adapter                                                       | 46        | 1.09%   |
| Lite-On Bluetooth Device                                                            | 46        | 1.09%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 46        | 1.09%   |
| Apple Bluetooth USB Host Controller                                                 | 44        | 1.04%   |
| Intel Bluetooth Device                                                              | 42        | 0.99%   |
| Intel AX210 Bluetooth                                                               | 41        | 0.97%   |
| Broadcom BCM2045 Bluetooth                                                          | 40        | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 37        | 0.87%   |
| Ralink RT3290 Bluetooth                                                             | 35        | 0.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 33        | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 32        | 0.76%   |
| IMC Networks Wireless_Device                                                        | 29        | 0.68%   |
| Apple Bluetooth HCI                                                                 | 29        | 0.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 25        | 0.59%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 23        | 0.54%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 22        | 0.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 21        | 0.5%    |
| Realtek RTL8723B Bluetooth                                                          | 18        | 0.42%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 18        | 0.42%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 17        | 0.4%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 17        | 0.4%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 16        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 5295      | 54.55%  |
| AMD                                  | 1966      | 20.26%  |
| Nvidia                               | 1554      | 16.01%  |
| C-Media Electronics                  | 171       | 1.76%   |
| Logitech                             | 59        | 0.61%   |
| Creative Labs                        | 55        | 0.57%   |
| VIA Technologies                     | 43        | 0.44%   |
| Silicon Integrated Systems [SiS]     | 34        | 0.35%   |
| JMTek                                | 31        | 0.32%   |
| GN Netcom                            | 30        | 0.31%   |
| Razer USA                            | 23        | 0.24%   |
| Generalplus Technology               | 23        | 0.24%   |
| Texas Instruments                    | 22        | 0.23%   |
| Realtek Semiconductor                | 22        | 0.23%   |
| Creative Technology                  | 22        | 0.23%   |
| M-Audio                              | 17        | 0.18%   |
| Focusrite-Novation                   | 16        | 0.16%   |
| ASUSTek Computer                     | 14        | 0.14%   |
| Micro Star International             | 13        | 0.13%   |
| BEHRINGER International              | 13        | 0.13%   |
| Kingston Technology                  | 12        | 0.12%   |
| Samson Technologies                  | 11        | 0.11%   |
| Tenx Technology                      | 10        | 0.1%    |
| Plantronics                          | 10        | 0.1%    |
| Dell                                 | 10        | 0.1%    |
| Hewlett-Packard                      | 9         | 0.09%   |
| Corsair                              | 9         | 0.09%   |
| Lenovo                               | 8         | 0.08%   |
| CMX Systems                          | 8         | 0.08%   |
| Trust                                | 7         | 0.07%   |
| Microsoft                            | 7         | 0.07%   |
| Ensoniq                              | 7         | 0.07%   |
| Sony                                 | 6         | 0.06%   |
| Apple                                | 6         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.05%   |
| SteelSeries ApS                      | 5         | 0.05%   |
| SAVITECH                             | 5         | 0.05%   |
| Cambridge Silicon Radio              | 5         | 0.05%   |
| Yamaha                               | 4         | 0.04%   |
| XMOS                                 | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 562       | 4.92%   |
| AMD Family 17h/19h HD Audio Controller                                     | 541       | 4.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 452       | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 436       | 3.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 330       | 2.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 328       | 2.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 310       | 2.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 281       | 2.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 273       | 2.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 238       | 2.09%   |
| AMD FCH Azalia Controller                                                  | 223       | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 219       | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 216       | 1.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 208       | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 204       | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 203       | 1.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 203       | 1.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 190       | 1.66%   |
| Intel 8 Series HD Audio Controller                                         | 190       | 1.66%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 159       | 1.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 153       | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 146       | 1.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 143       | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 143       | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 133       | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 125       | 1.1%    |
| Intel 200 Series PCH HD Audio                                              | 125       | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 124       | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 122       | 1.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 119       | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 115       | 1.01%   |
| Nvidia High Definition Audio Controller                                    | 113       | 0.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 106       | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 101       | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 101       | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 92        | 0.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 86        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 80        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 76        | 0.67%   |
| AMD High Definition Audio Controller                                       | 74        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1028      | 22.16%  |
| SK hynix                     | 778       | 16.77%  |
| Kingston                     | 549       | 11.83%  |
| Unknown                      | 532       | 11.47%  |
| Micron Technology            | 465       | 10.02%  |
| Crucial                      | 321       | 6.92%   |
| Corsair                      | 283       | 6.1%    |
| G.Skill                      | 93        | 2%      |
| Unknown (ABCD)               | 89        | 1.92%   |
| Ramaxel Technology           | 86        | 1.85%   |
| Elpida                       | 78        | 1.68%   |
| A-DATA Technology            | 64        | 1.38%   |
| Nanya Technology             | 49        | 1.06%   |
| Team                         | 40        | 0.86%   |
| Unknown                      | 32        | 0.69%   |
| Patriot                      | 28        | 0.6%    |
| Transcend                    | 19        | 0.41%   |
| ASint Technology             | 10        | 0.22%   |
| Unifosa                      | 8         | 0.17%   |
| Toshiba                      | 6         | 0.13%   |
| Qimonda                      | 6         | 0.13%   |
| Timetec                      | 5         | 0.11%   |
| 48spaces                     | 5         | 0.11%   |
| Patriot Memory (PDP Systems) | 4         | 0.09%   |
| Hewlett-Packard              | 4         | 0.09%   |
| GOODRAM                      | 4         | 0.09%   |
| Unknown (AB)                 | 3         | 0.06%   |
| Silicon Power                | 3         | 0.06%   |
| GeIL                         | 3         | 0.06%   |
| A Force                      | 3         | 0.06%   |
| PLEXHD                       | 2         | 0.04%   |
| Netac                        | 2         | 0.04%   |
| Lexar                        | 2         | 0.04%   |
| Goldkey                      | 2         | 0.04%   |
| CSX                          | 2         | 0.04%   |
| ChangXin Memory              | 2         | 0.04%   |
| V-Color                      | 1         | 0.02%   |
| Unknown (D386)               | 1         | 0.02%   |
| Unknown (8A5D)               | 1         | 0.02%   |
| Unknown (8A02)               | 1         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 62        | 1.24%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 48        | 0.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 39        | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 38        | 0.76%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 35        | 0.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 34        | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 33        | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 32        | 0.64%   |
| Unknown                                                           | 32        | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 30        | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s          | 29        | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 28        | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 27        | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 27        | 0.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 27        | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 25        | 0.5%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 24        | 0.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 23        | 0.46%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 23        | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s          | 22        | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 21        | 0.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s             | 21        | 0.42%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 21        | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 20        | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 20        | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s         | 20        | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 20        | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 19        | 0.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 19        | 0.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 19        | 0.38%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s             | 19        | 0.38%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s             | 19        | 0.38%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 18        | 0.36%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s            | 18        | 0.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 18        | 0.36%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 17        | 0.34%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 16        | 0.32%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s       | 16        | 0.32%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s             | 16        | 0.32%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 16        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1847      | 45.28%  |
| DDR3    | 1326      | 32.51%  |
| DDR2    | 278       | 6.82%   |
| LPDDR4  | 197       | 4.83%   |
| SDRAM   | 143       | 3.51%   |
| LPDDR3  | 108       | 2.65%   |
| Unknown | 86        | 2.11%   |
| DDR5    | 35        | 0.86%   |
| DDR     | 32        | 0.78%   |
| LPDDR5  | 17        | 0.42%   |
| DRAM    | 10        | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2370      | 58.49%  |
| DIMM         | 1346      | 33.22%  |
| Row Of Chips | 317       | 7.82%   |
| Chip         | 12        | 0.3%    |
| FB-DIMM      | 4         | 0.1%    |
| Unknown      | 3         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1654      | 37.32%  |
| 4096  | 1275      | 28.77%  |
| 2048  | 659       | 14.87%  |
| 16384 | 558       | 12.59%  |
| 1024  | 165       | 3.72%   |
| 32768 | 78        | 1.76%   |
| 512   | 35        | 0.79%   |
| 256   | 5         | 0.11%   |
| 3072  | 2         | 0.05%   |
| 32    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 806       | 18.31%  |
| 2667    | 626       | 14.22%  |
| 3200    | 592       | 13.45%  |
| 2400    | 355       | 8.07%   |
| 1333    | 270       | 6.13%   |
| 2133    | 187       | 4.25%   |
| 1334    | 155       | 3.52%   |
| Unknown | 133       | 3.02%   |
| 667     | 124       | 2.82%   |
| 3600    | 122       | 2.77%   |
| 800     | 116       | 2.64%   |
| 1867    | 104       | 2.36%   |
| 4267    | 63        | 1.43%   |
| 1066    | 61        | 1.39%   |
| 3266    | 59        | 1.34%   |
| 2933    | 38        | 0.86%   |
| 3400    | 37        | 0.84%   |
| 1067    | 36        | 0.82%   |
| 3000    | 35        | 0.8%    |
| 1800    | 31        | 0.7%    |
| 4800    | 29        | 0.66%   |
| 3733    | 29        | 0.66%   |
| 533     | 26        | 0.59%   |
| 1866    | 23        | 0.52%   |
| 3533    | 22        | 0.5%    |
| 2048    | 21        | 0.48%   |
| 4199    | 20        | 0.45%   |
| 3666    | 20        | 0.45%   |
| 8400    | 18        | 0.41%   |
| 6400    | 17        | 0.39%   |
| 400     | 16        | 0.36%   |
| 3800    | 15        | 0.34%   |
| 266     | 15        | 0.34%   |
| 2666    | 14        | 0.32%   |
| 4266    | 10        | 0.23%   |
| 2800    | 10        | 0.23%   |
| 333     | 10        | 0.23%   |
| 975     | 9         | 0.2%    |
| 2000    | 7         | 0.16%   |
| 1639    | 7         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 109       | 35.97%  |
| Samsung Electronics   | 54        | 17.82%  |
| Canon                 | 43        | 14.19%  |
| Brother Industries    | 34        | 11.22%  |
| Seiko Epson           | 33        | 10.89%  |
| Xerox                 | 4         | 1.32%   |
| Lexmark International | 4         | 1.32%   |
| Dymo-CoStar           | 4         | 1.32%   |
| Pantum                | 3         | 0.99%   |
| Prolific Technology   | 2         | 0.66%   |
| Oki Data              | 2         | 0.66%   |
| Kyocera               | 2         | 0.66%   |
| Apple                 | 2         | 0.66%   |
| Toshiba TEC           | 1         | 0.33%   |
| STMicroelectronics    | 1         | 0.33%   |
| Sato                  | 1         | 0.33%   |
| Sagem                 | 1         | 0.33%   |
| Ricoh                 | 1         | 0.33%   |
| QinHeng Electronics   | 1         | 0.33%   |
| ICS Advent            | 1         | 0.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung M2020 Series                                                  | 9         | 2.96%   |
| Seiko Epson WF-2510 Series                                            | 8         | 2.63%   |
| HP OfficeJet 6950                                                     | 8         | 2.63%   |
| Samsung ML-216x Series Laser Printer                                  | 7         | 2.3%    |
| Samsung M267x 287x Series                                             | 7         | 2.3%    |
| HP Deskjet 2050 J510                                                  | 7         | 2.3%    |
| Samsung M2070 Series                                                  | 6         | 1.97%   |
| Seiko Epson Printer                                                   | 5         | 1.64%   |
| HP ENVY 4520 series                                                   | 5         | 1.64%   |
| Canon LiDE 400                                                        | 5         | 1.64%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 4         | 1.32%   |
| HP Officejet 2620 series                                              | 4         | 1.32%   |
| HP LaserJet P1102                                                     | 4         | 1.32%   |
| HP LaserJet 1018                                                      | 4         | 1.32%   |
| Canon PIXMA MG3600 Series                                             | 4         | 1.32%   |
| Samsung ML-1660 Series                                                | 3         | 0.99%   |
| Samsung ML-1640 Series Laser Printer                                  | 3         | 0.99%   |
| Samsung Composite Device                                              | 3         | 0.99%   |
| HP LaserJet Professional P 1102w                                      | 3         | 0.99%   |
| HP LaserJet P1005                                                     | 3         | 0.99%   |
| HP LaserJet 1200                                                      | 3         | 0.99%   |
| HP ENVY 5000 series                                                   | 3         | 0.99%   |
| HP Deskjet F4500 series                                               | 3         | 0.99%   |
| HP Deskjet 3520 series                                                | 3         | 0.99%   |
| HP Deskjet 3050A                                                      | 3         | 0.99%   |
| Dymo-CoStar LabelWriter 450                                           | 3         | 0.99%   |
| Canon PIXMA MG2500 Series                                             | 3         | 0.99%   |
| Brother MFC-L2700DW                                                   | 3         | 0.99%   |
| Brother HL-3140CW series                                              | 3         | 0.99%   |
| Brother DCP-1610W                                                     | 3         | 0.99%   |
| Seiko Epson ET-2820 Series                                            | 2         | 0.66%   |
| Samsung SCX-4623 Series                                               | 2         | 0.66%   |
| Samsung SCX-4300 Series                                               | 2         | 0.66%   |
| Prolific PL2305 Parallel Port                                         | 2         | 0.66%   |
| Oki Data USB Device                                                   | 2         | 0.66%   |
| Lexmark International InkJet Color Printer                            | 2         | 0.66%   |
| HP Officejet Pro 6230                                                 | 2         | 0.66%   |
| HP OfficeJet 5200 series                                              | 2         | 0.66%   |
| HP OfficeJet 4650 series                                              | 2         | 0.66%   |
| HP Officejet 4630 series                                              | 2         | 0.66%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 42        | 53.85%  |
| Seiko Epson        | 21        | 26.92%  |
| Hewlett-Packard    | 9         | 11.54%  |
| Mustek Systems     | 4         | 5.13%   |
| Ultima Electronics | 1         | 1.28%   |
| Plustek            | 1         | 1.28%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 10        | 12.66%  |
| Canon CanoScan LiDE 210                                                               | 6         | 7.59%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 4         | 5.06%   |
| Canon CanoScan LiDE 120                                                               | 4         | 5.06%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 3         | 3.8%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 3.8%    |
| Canon CanoScan LiDE 220                                                               | 3         | 3.8%    |
| Canon CanoScan LiDE 100                                                               | 3         | 3.8%    |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2         | 2.53%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 2.53%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2         | 2.53%   |
| HP Scanjet 200                                                                        | 2         | 2.53%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 2.53%   |
| Canon CanoScan LiDE 60                                                                | 2         | 2.53%   |
| Canon CanoScan LIDE 25                                                                | 2         | 2.53%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 1.27%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 1.27%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 1.27%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 1.27%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1         | 1.27%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.27%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.27%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 1.27%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                                  | 1         | 1.27%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1         | 1.27%   |
| Seiko Epson ES-D400 [GT-S80]                                                          | 1         | 1.27%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                                            | 1         | 1.27%   |
| Plustek 600DPI USB Scanner                                                            | 1         | 1.27%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.27%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 1.27%   |
| HP Scanjet G2710                                                                      | 1         | 1.27%   |
| HP ScanJet 3800c                                                                      | 1         | 1.27%   |
| HP ScanJet 3570c                                                                      | 1         | 1.27%   |
| HP ScanJet 3400cse                                                                    | 1         | 1.27%   |
| HP ScanJet 2400c                                                                      | 1         | 1.27%   |
| HP PSC 1200                                                                           | 1         | 1.27%   |
| HP HP4470C                                                                            | 1         | 1.27%   |
| Canon CanoScan LiDE 90                                                                | 1         | 1.27%   |
| Canon CanoScan LiDE 700F                                                              | 1         | 1.27%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 1.27%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1039      | 22.95%  |
| IMC Networks                           | 477       | 10.54%  |
| Microdia                               | 334       | 7.38%   |
| Realtek Semiconductor                  | 317       | 7%      |
| Logitech                               | 221       | 4.88%   |
| Quanta                                 | 207       | 4.57%   |
| Bison Electronics                      | 204       | 4.51%   |
| Sunplus Innovation Technology          | 192       | 4.24%   |
| Suyin                                  | 190       | 4.2%    |
| Cheng Uei Precision Industry (Foxlink) | 175       | 3.87%   |
| Apple                                  | 130       | 2.87%   |
| Acer                                   | 124       | 2.74%   |
| Alcor Micro                            | 108       | 2.39%   |
| Syntek                                 | 106       | 2.34%   |
| Lite-On Technology                     | 91        | 2.01%   |
| Luxvisions Innotech Limited            | 76        | 1.68%   |
| Microsoft                              | 68        | 1.5%    |
| Silicon Motion                         | 51        | 1.13%   |
| Ricoh                                  | 50        | 1.1%    |
| Z-Star Microelectronics                | 28        | 0.62%   |
| Samsung Electronics                    | 27        | 0.6%    |
| ARC International                      | 26        | 0.57%   |
| Trust                                  | 17        | 0.38%   |
| ALi                                    | 17        | 0.38%   |
| Primax Electronics                     | 15        | 0.33%   |
| Generalplus Technology                 | 15        | 0.33%   |
| KYE Systems (Mouse Systems)            | 13        | 0.29%   |
| icSpring                               | 13        | 0.29%   |
| GEMBIRD                                | 11        | 0.24%   |
| Sunplus Technology                     | 10        | 0.22%   |
| Sonix Technology                       | 10        | 0.22%   |
| Lenovo                                 | 10        | 0.22%   |
| SunplusIT                              | 9         | 0.2%    |
| Cubeternet                             | 9         | 0.2%    |
| WaveRider Communications               | 8         | 0.18%   |
| Sunplus IT                             | 8         | 0.18%   |
| Genesys Logic                          | 8         | 0.18%   |
| Importek                               | 7         | 0.15%   |
| DigiTech                               | 7         | 0.15%   |
| Huawei Technologies                    | 6         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 163       | 3.57%   |
| Microdia Integrated_Webcam_HD                           | 115       | 2.52%   |
| Chicony HD WebCam                                       | 97        | 2.13%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 93        | 2.04%   |
| IMC Networks Integrated Camera                          | 79        | 1.73%   |
| Realtek Integrated_Webcam_HD                            | 76        | 1.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 72        | 1.58%   |
| Logitech Webcam C270                                    | 63        | 1.38%   |
| Syntek Integrated Camera                                | 59        | 1.29%   |
| Realtek USB Camera                                      | 58        | 1.27%   |
| Alcor Micro USB 2.0 Camera                              | 56        | 1.23%   |
| Chicony USB2.0 HD UVC WebCam                            | 46        | 1.01%   |
| Chicony HP Truevision HD                                | 46        | 1.01%   |
| Chicony USB2.0 VGA UVC WebCam                           | 45        | 0.99%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 43        | 0.94%   |
| Acer Integrated Camera                                  | 43        | 0.94%   |
| Bison Integrated Camera                                 | 42        | 0.92%   |
| Apple Built-in iSight                                   | 42        | 0.92%   |
| Sunplus Integrated_Webcam_HD                            | 41        | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 38        | 0.83%   |
| Quanta HP TrueVision HD Camera                          | 37        | 0.81%   |
| IMC Networks HD Camera                                  | 37        | 0.81%   |
| Chicony HP TrueVision HD Camera                         | 35        | 0.77%   |
| Chicony HP HD Camera                                    | 35        | 0.77%   |
| Microdia Webcam Vitade AF                               | 33        | 0.72%   |
| Chicony HP Wide Vision HD Camera                        | 32        | 0.7%    |
| Sunplus HD WebCam                                       | 30        | 0.66%   |
| Chicony HP Webcam                                       | 30        | 0.66%   |
| Chicony FJ Camera                                       | 30        | 0.66%   |
| Microsoft LifeCam HD-3000                               | 29        | 0.64%   |
| Quanta HP Webcam                                        | 28        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 28        | 0.61%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 27        | 0.59%   |
| Suyin HP TrueVision HD                                  | 26        | 0.57%   |
| Logitech HD Pro Webcam C920                             | 26        | 0.57%   |
| ARC International Camera                                | 26        | 0.57%   |
| Realtek USB2.0 VGA UVC WebCam                           | 25        | 0.55%   |
| Chicony USB2.0 Camera                                   | 25        | 0.55%   |
| Apple FaceTime HD Camera (Built-in)                     | 25        | 0.55%   |
| Microdia Integrated Webcam                              | 24        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 224       | 28.32%  |
| Synaptics                          | 194       | 24.53%  |
| Shenzhen Goodix Technology         | 140       | 17.7%   |
| Elan Microelectronics              | 94        | 11.88%  |
| Upek                               | 43        | 5.44%   |
| AuthenTec                          | 41        | 5.18%   |
| LighTuning Technology              | 39        | 4.93%   |
| STMicroelectronics                 | 6         | 0.76%   |
| Focal-systems.Corp                 | 5         | 0.63%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.25%   |
| Microsoft                          | 1         | 0.13%   |
| HOLTEK                             | 1         | 0.13%   |
| Dell                               | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 98        | 12.39%  |
| Elan ELAN:ARM-M4                                                           | 63        | 7.96%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 45        | 5.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 5.31%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 4.8%    |
| Elan ELAN:Fingerprint                                                      | 31        | 3.92%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 3.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 27        | 3.41%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 25        | 3.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 2.78%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 2.65%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 21        | 2.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 2.53%   |
| Synaptics  WBDI                                                            | 18        | 2.28%   |
| Synaptics UWP WBDI                                                         | 17        | 2.15%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 16        | 2.02%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 1.77%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 1.52%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 1.52%   |
| Validity Sensors VFS491                                                    | 11        | 1.39%   |
| Synaptics WBDI                                                             | 11        | 1.39%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 1.26%   |
| Unknown                                                                    | 10        | 1.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.14%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 1.14%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.14%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.01%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 1.01%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.88%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.88%   |
| AuthenTec AES1600                                                          | 7         | 0.88%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.76%   |
| AuthenTec AES2810                                                          | 6         | 0.76%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.63%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.63%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 122       | 36.09%  |
| Alcor Micro               | 95        | 28.11%  |
| O2 Micro                  | 28        | 8.28%   |
| Advanced Card Systems     | 23        | 6.8%    |
| Lenovo                    | 16        | 4.73%   |
| BIT4ID                    | 12        | 3.55%   |
| Upek                      | 11        | 3.25%   |
| Gemalto (was Gemplus)     | 8         | 2.37%   |
| Realtek Semiconductor     | 7         | 2.07%   |
| SCM Microsystems          | 5         | 1.48%   |
| OmniKey                   | 3         | 0.89%   |
| Clay Logic                | 3         | 0.89%   |
| Reiner SCT Kartensysteme  | 2         | 0.59%   |
| Microchip Technology      | 1         | 0.3%    |
| In Focus Systems          | 1         | 0.3%    |
| Fujitsu Siemens Computers | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 90        | 26.55%  |
| Broadcom 58200                                                               | 39        | 11.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 10.32%  |
| Broadcom 5880                                                                | 26        | 7.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 7.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 5.9%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 17        | 5.01%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 4.72%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 3.24%   |
| BIT4ID miniLector EVO                                                        | 11        | 3.24%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 7         | 2.06%   |
| Advanced Card Systems ACR122U                                                | 6         | 1.77%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.47%   |
| Alcor Micro Watchdata W 1981                                                 | 5         | 1.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.18%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.88%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.88%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 2         | 0.59%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.59%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.29%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.29%   |
| SCM Microsystems Identiv SmartOS Reader                                      | 1         | 0.29%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.29%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.29%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.29%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.29%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.29%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.29%   |
| BIT4ID miniLector AIR NFC v3                                                 | 1         | 0.29%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.29%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5324      | 70.74%  |
| 1     | 1766      | 23.47%  |
| 2     | 377       | 5.01%   |
| 3     | 40        | 0.53%   |
| 4     | 11        | 0.15%   |
| 5     | 6         | 0.08%   |
| 6     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 782       | 29.96%  |
| Graphics card            | 634       | 24.29%  |
| Net/wireless             | 315       | 12.07%  |
| Chipcard                 | 281       | 10.77%  |
| Multimedia controller    | 128       | 4.9%    |
| Camera                   | 92        | 3.52%   |
| Communication controller | 84        | 3.22%   |
| Bluetooth                | 64        | 2.45%   |
| Sound                    | 35        | 1.34%   |
| Storage                  | 34        | 1.3%    |
| Unassigned class         | 33        | 1.26%   |
| Modem                    | 25        | 0.96%   |
| Card reader              | 24        | 0.92%   |
| Net/ethernet             | 20        | 0.77%   |
| Flash memory             | 18        | 0.69%   |
| Network                  | 12        | 0.46%   |
| Dvb card                 | 7         | 0.27%   |
| Storage/raid             | 6         | 0.23%   |
| Firewire controller      | 5         | 0.19%   |
| Storage/ide              | 4         | 0.15%   |
| Wireless                 | 2         | 0.08%   |
| Video                    | 2         | 0.08%   |
| Tv card                  | 2         | 0.08%   |
| Storage/nvme             | 1         | 0.04%   |


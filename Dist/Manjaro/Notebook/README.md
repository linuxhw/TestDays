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

Total: 4573

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| ASUSTek       | ROG Strix G713RW_G713RW     | [a783a36e7e](https://linux-hardware.org/?probe=a783a36e7e) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [f5ddf4a2b4](https://linux-hardware.org/?probe=f5ddf4a2b4) | Sep 29, 2022 |
| HP            | ProBook 430 G6              | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | [72d80e02c9](https://linux-hardware.org/?probe=72d80e02c9) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | [47b22afda2](https://linux-hardware.org/?probe=47b22afda2) | Sep 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [50bf4e6b4e](https://linux-hardware.org/?probe=50bf4e6b4e) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [224549bcb6](https://linux-hardware.org/?probe=224549bcb6) | Sep 28, 2022 |
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
| HP            | ENVY 15                     | [b662f9b708](https://linux-hardware.org/?probe=b662f9b708) | Sep 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [75cc4fa084](https://linux-hardware.org/?probe=75cc4fa084) | Sep 19, 2022 |
| Acer          | Nitro AN515-42              | [97e2956728](https://linux-hardware.org/?probe=97e2956728) | Sep 19, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [1cbec0f70e](https://linux-hardware.org/?probe=1cbec0f70e) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Apple         | MacBookPro15,1              | [b0e746792f](https://linux-hardware.org/?probe=b0e746792f) | Sep 19, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [515032e1c3](https://linux-hardware.org/?probe=515032e1c3) | Sep 19, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [c98bc3dacb](https://linux-hardware.org/?probe=c98bc3dacb) | Sep 19, 2022 |
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
| HP            | ENVY 15                     | [e3a2a0d5d7](https://linux-hardware.org/?probe=e3a2a0d5d7) | Sep 13, 2022 |
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
| ASUSTek       | X541UJ                      | [471a57d688](https://linux-hardware.org/?probe=471a57d688) | Sep 07, 2022 |
| ASUSTek       | X541UJ                      | [84b26ca406](https://linux-hardware.org/?probe=84b26ca406) | Sep 07, 2022 |
| HP            | EliteBook 840 G5            | [a870f2cf25](https://linux-hardware.org/?probe=a870f2cf25) | Sep 07, 2022 |
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
| Lenovo        | IdeaPad S145-15API 81V7     | [1be0869985](https://linux-hardware.org/?probe=1be0869985) | Aug 04, 2022 |
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
| HP            | ProBook 4540s               | [e209d1f716](https://linux-hardware.org/?probe=e209d1f716) | Jul 08, 2022 |
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
| HP            | Laptop 15-dy0xxx            | [b124bc6727](https://linux-hardware.org/?probe=b124bc6727) | Jun 22, 2022 |
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
| HP            | Laptop 15-dy0xxx            | [35b5b0d570](https://linux-hardware.org/?probe=35b5b0d570) | Jun 15, 2022 |
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
| Dell          | Vostro 3560                 | [9eb42db4b8](https://linux-hardware.org/?probe=9eb42db4b8) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| HP            | Laptop 15s-fq3xxx           | [2646216b05](https://linux-hardware.org/?probe=2646216b05) | Jun 07, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [fdda1deb12](https://linux-hardware.org/?probe=fdda1deb12) | Jun 07, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [24da0cf09c](https://linux-hardware.org/?probe=24da0cf09c) | Jun 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [3281dce7d5](https://linux-hardware.org/?probe=3281dce7d5) | Jun 06, 2022 |
| HP            | Laptop 15s-fq3xxx           | [fca50a2737](https://linux-hardware.org/?probe=fca50a2737) | Jun 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [f1bad1050e](https://linux-hardware.org/?probe=f1bad1050e) | Jun 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2KW1... | [686fcbebd3](https://linux-hardware.org/?probe=686fcbebd3) | Jun 06, 2022 |
| HP            | Laptop 15-dy2xxx            | [ecc580e75f](https://linux-hardware.org/?probe=ecc580e75f) | Jun 06, 2022 |
| HP            | Laptop 15-dy2xxx            | [e737d522f2](https://linux-hardware.org/?probe=e737d522f2) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [d2efe762b7](https://linux-hardware.org/?probe=d2efe762b7) | Jun 06, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f5ca696120](https://linux-hardware.org/?probe=f5ca696120) | Jun 04, 2022 |
| Purism        | Librem 14                   | [6dad17c85e](https://linux-hardware.org/?probe=6dad17c85e) | Jun 04, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [d16eb6886f](https://linux-hardware.org/?probe=d16eb6886f) | Jun 04, 2022 |
| Dell          | Latitude E6400              | [67a5bdc1aa](https://linux-hardware.org/?probe=67a5bdc1aa) | Jun 04, 2022 |
| HP            | ProBook 6550b               | [005fa13ca2](https://linux-hardware.org/?probe=005fa13ca2) | Jun 04, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [7583c09b9d](https://linux-hardware.org/?probe=7583c09b9d) | Jun 04, 2022 |
| HP            | Laptop 15s-fq2xxx           | [5bcb742cbe](https://linux-hardware.org/?probe=5bcb742cbe) | Jun 04, 2022 |
| HP            | ProBook 455 G7              | [0f2ae8ff19](https://linux-hardware.org/?probe=0f2ae8ff19) | Jun 03, 2022 |
| Lenovo        | ThinkPad T450 20BV0005US    | [a795ed872f](https://linux-hardware.org/?probe=a795ed872f) | Jun 03, 2022 |
| Acer          | Nitro AN517-52              | [fff36b3fae](https://linux-hardware.org/?probe=fff36b3fae) | Jun 03, 2022 |
| Lenovo        | G580 20150                  | [ca44145e04](https://linux-hardware.org/?probe=ca44145e04) | Jun 03, 2022 |
| Dell          | Latitude 5480               | [e78587e156](https://linux-hardware.org/?probe=e78587e156) | Jun 03, 2022 |
| HP            | Pavilion Laptop 15-cs1xx... | [09ccc0899e](https://linux-hardware.org/?probe=09ccc0899e) | Jun 03, 2022 |
| Dell          | XPS 15 9500                 | [00e3c7f3c6](https://linux-hardware.org/?probe=00e3c7f3c6) | Jun 03, 2022 |
| HP            | ProBook 430 G2              | [97edec8a04](https://linux-hardware.org/?probe=97edec8a04) | Jun 02, 2022 |
| HP            | ProBook 455 G7              | [658e8ce62f](https://linux-hardware.org/?probe=658e8ce62f) | Jun 02, 2022 |
| Acer          | Aspire E5-475G              | [4692c93a71](https://linux-hardware.org/?probe=4692c93a71) | Jun 02, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [185587d5e1](https://linux-hardware.org/?probe=185587d5e1) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| HP            | Laptop 15s-fq3xxx           | [b089cb1095](https://linux-hardware.org/?probe=b089cb1095) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [164d02e437](https://linux-hardware.org/?probe=164d02e437) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a3e63f04e7](https://linux-hardware.org/?probe=a3e63f04e7) | May 31, 2022 |
| HP            | ProBook 455 G7              | [d95897f938](https://linux-hardware.org/?probe=d95897f938) | May 31, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [a08d3e5d4b](https://linux-hardware.org/?probe=a08d3e5d4b) | May 31, 2022 |
| Notebook      | Multicom Xishan NL50        | [9ffa89c7a9](https://linux-hardware.org/?probe=9ffa89c7a9) | May 31, 2022 |
| Razer         | Blade                       | [d7271bb7c4](https://linux-hardware.org/?probe=d7271bb7c4) | May 30, 2022 |
| Acer          | Aspire E5-573               | [467494fb1a](https://linux-hardware.org/?probe=467494fb1a) | May 30, 2022 |
| Notebook      | Multicom Xishan NL50        | [0c45263f11](https://linux-hardware.org/?probe=0c45263f11) | May 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [4fadee73e4](https://linux-hardware.org/?probe=4fadee73e4) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5e77f9d2f9](https://linux-hardware.org/?probe=5e77f9d2f9) | May 29, 2022 |
| ASUSTek       | N53SM                       | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Dell          | XPS 15 9500                 | [ec336b7bfb](https://linux-hardware.org/?probe=ec336b7bfb) | May 28, 2022 |
| Acer          | Aspire A715-75G             | [30fc2ddbf0](https://linux-hardware.org/?probe=30fc2ddbf0) | May 28, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | [475315dc10](https://linux-hardware.org/?probe=475315dc10) | May 28, 2022 |
| Toshiba       | Satellite L10W-B-101        | [774d5a9eae](https://linux-hardware.org/?probe=774d5a9eae) | May 28, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [a53ea69c8e](https://linux-hardware.org/?probe=a53ea69c8e) | May 27, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | [018e2a8bff](https://linux-hardware.org/?probe=018e2a8bff) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | [6d4ab67cb8](https://linux-hardware.org/?probe=6d4ab67cb8) | May 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [3a8329a411](https://linux-hardware.org/?probe=3a8329a411) | May 26, 2022 |
| Acer          | Aspire A517-51G             | [ad47cf8631](https://linux-hardware.org/?probe=ad47cf8631) | May 26, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [110903519d](https://linux-hardware.org/?probe=110903519d) | May 26, 2022 |
| ASUSTek       | N552VW                      | [1bc0990250](https://linux-hardware.org/?probe=1bc0990250) | May 25, 2022 |
| HONOR         | NMH-WCX9                    | [afdda4edc0](https://linux-hardware.org/?probe=afdda4edc0) | May 25, 2022 |
| HONOR         | NMH-WCX9                    | [222e1d3dd4](https://linux-hardware.org/?probe=222e1d3dd4) | May 25, 2022 |
| Packard Be... | EasyNote LM98               | [0024e410e9](https://linux-hardware.org/?probe=0024e410e9) | May 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [0a468b99d2](https://linux-hardware.org/?probe=0a468b99d2) | May 25, 2022 |
| HP            | EliteBook 2560p             | [00b2e6d758](https://linux-hardware.org/?probe=00b2e6d758) | May 24, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [a6626edfaa](https://linux-hardware.org/?probe=a6626edfaa) | May 24, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [fca93c5473](https://linux-hardware.org/?probe=fca93c5473) | May 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8b214b9114](https://linux-hardware.org/?probe=8b214b9114) | May 24, 2022 |
| ASUSTek       | N53SM                       | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Acer          | Aspire A715-42G             | [2979dfecb7](https://linux-hardware.org/?probe=2979dfecb7) | May 24, 2022 |
| Toshiba       | Satellite L10W-B-101        | [bb4ce9afdd](https://linux-hardware.org/?probe=bb4ce9afdd) | May 24, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [eb3ad5999e](https://linux-hardware.org/?probe=eb3ad5999e) | May 24, 2022 |
| Dell          | XPS 15 9500                 | [4f2f7e71db](https://linux-hardware.org/?probe=4f2f7e71db) | May 24, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | [9eef1e277c](https://linux-hardware.org/?probe=9eef1e277c) | May 23, 2022 |
| Packard Be... | EasyNote LM98               | [5730a17a5e](https://linux-hardware.org/?probe=5730a17a5e) | May 23, 2022 |
| Fujitsu       | CELSIUS H7510               | [5380d9bfca](https://linux-hardware.org/?probe=5380d9bfca) | May 23, 2022 |
| Dell          | XPS 13 9310                 | [c7cf536a61](https://linux-hardware.org/?probe=c7cf536a61) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [50a0ed5e81](https://linux-hardware.org/?probe=50a0ed5e81) | May 22, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [952fd6afe9](https://linux-hardware.org/?probe=952fd6afe9) | May 22, 2022 |
| ASUSTek       | G752VL                      | [6cb02316f1](https://linux-hardware.org/?probe=6cb02316f1) | May 22, 2022 |
| Apple         | MacBookPro8,1               | [1af89e5ffb](https://linux-hardware.org/?probe=1af89e5ffb) | May 22, 2022 |
| Standard      | B14HM21                     | [cc85dd7b32](https://linux-hardware.org/?probe=cc85dd7b32) | May 21, 2022 |
| Dell          | Inspiron 3542               | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| HP            | ProBook 470 G2              | [9d14cc23ca](https://linux-hardware.org/?probe=9d14cc23ca) | May 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d226cdf436](https://linux-hardware.org/?probe=d226cdf436) | May 20, 2022 |
| Lenovo        | B590 20208                  | [04c26fdb1b](https://linux-hardware.org/?probe=04c26fdb1b) | May 19, 2022 |
| Lenovo        | V145-15AST 81MT             | [ab767eaa59](https://linux-hardware.org/?probe=ab767eaa59) | May 19, 2022 |
| Dell          | XPS 17 9720                 | [4481be171e](https://linux-hardware.org/?probe=4481be171e) | May 19, 2022 |
| Apple         | MacBookPro16,1              | [a60048a58a](https://linux-hardware.org/?probe=a60048a58a) | May 19, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b85af00b16](https://linux-hardware.org/?probe=b85af00b16) | May 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1e61b49f67](https://linux-hardware.org/?probe=1e61b49f67) | May 18, 2022 |
| Acer          | Aspire A315-42              | [cd2a742b8c](https://linux-hardware.org/?probe=cd2a742b8c) | May 18, 2022 |
| Dell          | XPS 15 9500                 | [671279f960](https://linux-hardware.org/?probe=671279f960) | May 18, 2022 |
| Apple         | MacBookPro16,1              | [e5c6c46d14](https://linux-hardware.org/?probe=e5c6c46d14) | May 18, 2022 |
| Sony          | SVS1512U1RW                 | [491818d2e0](https://linux-hardware.org/?probe=491818d2e0) | May 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [716443586f](https://linux-hardware.org/?probe=716443586f) | May 18, 2022 |
| Lenovo        | Legion 5 82B5               | [40b039a144](https://linux-hardware.org/?probe=40b039a144) | May 17, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [5e0b60c547](https://linux-hardware.org/?probe=5e0b60c547) | May 17, 2022 |
| Chuwi         | HeroBook Air                | [7d96e10672](https://linux-hardware.org/?probe=7d96e10672) | May 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [1ccddf153e](https://linux-hardware.org/?probe=1ccddf153e) | May 17, 2022 |
| Razer         | Blade 15 Advanced Model ... | [9ee25daa97](https://linux-hardware.org/?probe=9ee25daa97) | May 17, 2022 |
| HP            | ProBook 455 G7              | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [39581d3868](https://linux-hardware.org/?probe=39581d3868) | May 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [dd2fb5f70b](https://linux-hardware.org/?probe=dd2fb5f70b) | May 17, 2022 |
| ASUSTek       | G752VL                      | [8295577f79](https://linux-hardware.org/?probe=8295577f79) | May 17, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [cee7de1ac8](https://linux-hardware.org/?probe=cee7de1ac8) | May 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [09c8ff393f](https://linux-hardware.org/?probe=09c8ff393f) | May 16, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [a32c82c654](https://linux-hardware.org/?probe=a32c82c654) | May 16, 2022 |
| Apple         | MacBookAir7,1               | [fb9fa22053](https://linux-hardware.org/?probe=fb9fa22053) | May 16, 2022 |
| Samsung       | 530XBB                      | [97c9209a74](https://linux-hardware.org/?probe=97c9209a74) | May 16, 2022 |
| Dell          | Inspiron 7559               | [90bfbc9f6b](https://linux-hardware.org/?probe=90bfbc9f6b) | May 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [71e5fcaa52](https://linux-hardware.org/?probe=71e5fcaa52) | May 15, 2022 |
| ASUSTek       | X555LB                      | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| Dell          | Inspiron 5505               | [c1353ba170](https://linux-hardware.org/?probe=c1353ba170) | May 15, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [286db103cd](https://linux-hardware.org/?probe=286db103cd) | May 15, 2022 |
| Dell          | Inspiron 5557               | [b0f50a8bcb](https://linux-hardware.org/?probe=b0f50a8bcb) | May 15, 2022 |
| ASUSTek       | N53SM                       | [7781811703](https://linux-hardware.org/?probe=7781811703) | May 14, 2022 |
| ASUSTek       | N53SM                       | [6846e2d548](https://linux-hardware.org/?probe=6846e2d548) | May 14, 2022 |
| Notebook      | NLx0MU                      | [b46632bd9a](https://linux-hardware.org/?probe=b46632bd9a) | May 14, 2022 |
| Acer          | Aspire E5-575G              | [55a5fb9d6e](https://linux-hardware.org/?probe=55a5fb9d6e) | May 14, 2022 |
| Toshiba       | Satellite C850-D1W          | [7d7d976bad](https://linux-hardware.org/?probe=7d7d976bad) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [b6cb96e1d0](https://linux-hardware.org/?probe=b6cb96e1d0) | May 13, 2022 |
| HP            | Pavilion dm1                | [7acb944db2](https://linux-hardware.org/?probe=7acb944db2) | May 13, 2022 |
| Pegatron      | H36ST                       | [7795d9059b](https://linux-hardware.org/?probe=7795d9059b) | May 13, 2022 |
| Star Labs     | Lite                        | [dbe031aada](https://linux-hardware.org/?probe=dbe031aada) | May 13, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [7e1a423d8b](https://linux-hardware.org/?probe=7e1a423d8b) | May 13, 2022 |
| Dell          | Inspiron 3542               | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| Packard Be... | EasyNote TE69CXP            | [de4486e0e1](https://linux-hardware.org/?probe=de4486e0e1) | May 12, 2022 |
| HP            | EliteBook 840 G1            | [a57e3f28c2](https://linux-hardware.org/?probe=a57e3f28c2) | May 12, 2022 |
| Fujitsu       | LIFEBOOK E756               | [5cda1364ad](https://linux-hardware.org/?probe=5cda1364ad) | May 12, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [d3d6871bf7](https://linux-hardware.org/?probe=d3d6871bf7) | May 12, 2022 |
| ICL           | Unknown                     | [858558d9fe](https://linux-hardware.org/?probe=858558d9fe) | May 12, 2022 |
| HP            | Pavilion g6                 | [5662b515c3](https://linux-hardware.org/?probe=5662b515c3) | May 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | [d01456558c](https://linux-hardware.org/?probe=d01456558c) | May 12, 2022 |
| HP            | ENVY dv6                    | [81f03e297f](https://linux-hardware.org/?probe=81f03e297f) | May 10, 2022 |
| Sony          | SVS13137PGB                 | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| MSI           | Modern 14 B11MO             | [75bc7c18db](https://linux-hardware.org/?probe=75bc7c18db) | May 10, 2022 |
| Positivo B... | VJFE43F11X-XXXXXX           | [6b22a6e3db](https://linux-hardware.org/?probe=6b22a6e3db) | May 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [25787f8eb3](https://linux-hardware.org/?probe=25787f8eb3) | May 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [7d146e5dec](https://linux-hardware.org/?probe=7d146e5dec) | May 10, 2022 |
| HP            | 255 G8 Notebook PC          | [d45bb1569a](https://linux-hardware.org/?probe=d45bb1569a) | May 10, 2022 |
| HP            | Laptop 15s-fq3xxx           | [b016f7ad1e](https://linux-hardware.org/?probe=b016f7ad1e) | May 10, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [48678afa40](https://linux-hardware.org/?probe=48678afa40) | May 09, 2022 |
| HP            | Laptop 15s-eq2xxx           | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| Dell          | XPS 15 9570                 | [43760b2df8](https://linux-hardware.org/?probe=43760b2df8) | May 09, 2022 |
| Dell          | Inspiron 3542               | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| Lenovo        | ThinkPad X230 2325SU3       | [b6d1786548](https://linux-hardware.org/?probe=b6d1786548) | May 08, 2022 |
| Dell          | XPS 15 9570                 | [8e6eed83cb](https://linux-hardware.org/?probe=8e6eed83cb) | May 08, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [36ac7ebe13](https://linux-hardware.org/?probe=36ac7ebe13) | May 08, 2022 |
| Lenovo        | Y40-70 20347                | [3c9abd80e9](https://linux-hardware.org/?probe=3c9abd80e9) | May 08, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [89ecde894a](https://linux-hardware.org/?probe=89ecde894a) | May 07, 2022 |
| ASUSTek       | N552VW                      | [ee99a66c19](https://linux-hardware.org/?probe=ee99a66c19) | May 07, 2022 |
| Samsung       | 550XDA                      | [271c745a5a](https://linux-hardware.org/?probe=271c745a5a) | May 07, 2022 |
| Chuwi         | HeroBook Air                | [255ff705ac](https://linux-hardware.org/?probe=255ff705ac) | May 07, 2022 |
| MSI           | Modern 14 B10MW             | [0f0a3c0728](https://linux-hardware.org/?probe=0f0a3c0728) | May 07, 2022 |
| Samsung       | 750XDA                      | [466689475e](https://linux-hardware.org/?probe=466689475e) | May 07, 2022 |
| HP            | ProBook 645 G1              | [c8bd8caf2f](https://linux-hardware.org/?probe=c8bd8caf2f) | May 07, 2022 |
| Acer          | Nitro AN515-45              | [6ae88a39dd](https://linux-hardware.org/?probe=6ae88a39dd) | May 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0F40... | [9d6a8926ec](https://linux-hardware.org/?probe=9d6a8926ec) | May 06, 2022 |
| Avell High... | G1713/C55 Fox               | [3967b8c677](https://linux-hardware.org/?probe=3967b8c677) | May 06, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [ca9c5a57a8](https://linux-hardware.org/?probe=ca9c5a57a8) | May 06, 2022 |
| ASUSTek       | GL552VW                     | [e1ece84cc1](https://linux-hardware.org/?probe=e1ece84cc1) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [b6dc8a3fc8](https://linux-hardware.org/?probe=b6dc8a3fc8) | May 05, 2022 |
| HP            | Notebook                    | [e72ad22650](https://linux-hardware.org/?probe=e72ad22650) | May 05, 2022 |
| Dell          | Inspiron 3580               | [51d4e9a2e2](https://linux-hardware.org/?probe=51d4e9a2e2) | May 05, 2022 |
| HP            | Notebook                    | [db14ab3fc7](https://linux-hardware.org/?probe=db14ab3fc7) | May 05, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7c8dbdcffc](https://linux-hardware.org/?probe=7c8dbdcffc) | May 05, 2022 |
| Panasonic     | CF-19THRAXF9                | [3e2d64f517](https://linux-hardware.org/?probe=3e2d64f517) | May 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ccb21427bf](https://linux-hardware.org/?probe=ccb21427bf) | May 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb2ffeb78a](https://linux-hardware.org/?probe=bb2ffeb78a) | May 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb73f6aa37](https://linux-hardware.org/?probe=bb73f6aa37) | May 04, 2022 |
| Apple         | MacBookPro11,3              | [21f611f3c7](https://linux-hardware.org/?probe=21f611f3c7) | May 03, 2022 |
| Dell          | Vostro 3500                 | [00add28269](https://linux-hardware.org/?probe=00add28269) | May 03, 2022 |
| HP            | Laptop 15-bs1xx             | [aa3fb50ed5](https://linux-hardware.org/?probe=aa3fb50ed5) | May 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [26cfc77ab9](https://linux-hardware.org/?probe=26cfc77ab9) | May 02, 2022 |
| MSI           | MS-16Y1                     | [7a8ff17e6c](https://linux-hardware.org/?probe=7a8ff17e6c) | May 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ec5dbcb034](https://linux-hardware.org/?probe=ec5dbcb034) | May 02, 2022 |
| Sony          | VPCF236FM                   | [ec0af02205](https://linux-hardware.org/?probe=ec0af02205) | May 02, 2022 |
| Acer          | Aspire A315-41              | [1bd7f7cd93](https://linux-hardware.org/?probe=1bd7f7cd93) | May 02, 2022 |
| Apple         | MacBookAir5,2               | [7bee091d47](https://linux-hardware.org/?probe=7bee091d47) | May 02, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [6a9dfa32d3](https://linux-hardware.org/?probe=6a9dfa32d3) | May 02, 2022 |
| Acer          | Aspire V5-561               | [e9dfda82d4](https://linux-hardware.org/?probe=e9dfda82d4) | May 02, 2022 |
| ASUSTek       | UX310UA                     | [80fce5caed](https://linux-hardware.org/?probe=80fce5caed) | May 01, 2022 |
| Dell          | Latitude E6540              | [ad5bf6fab1](https://linux-hardware.org/?probe=ad5bf6fab1) | May 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b152a1215a](https://linux-hardware.org/?probe=b152a1215a) | Apr 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6710b89c52](https://linux-hardware.org/?probe=6710b89c52) | Apr 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| HP            | ZBook 15 G5                 | [133b6e19a9](https://linux-hardware.org/?probe=133b6e19a9) | Apr 30, 2022 |
| HP            | ZBook 15 G5                 | [ce42a9f877](https://linux-hardware.org/?probe=ce42a9f877) | Apr 30, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4af637024a](https://linux-hardware.org/?probe=4af637024a) | Apr 29, 2022 |
| Acer          | Nitro AN515-45              | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| Dell          | Inspiron 3580               | [794ab7ba41](https://linux-hardware.org/?probe=794ab7ba41) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Inspiron 3543               | [6165b0554d](https://linux-hardware.org/?probe=6165b0554d) | Apr 28, 2022 |
| Sony          | VPCF120FL                   | [1636c68c92](https://linux-hardware.org/?probe=1636c68c92) | Apr 27, 2022 |
| Timi          | A35S                        | [8a3195e10c](https://linux-hardware.org/?probe=8a3195e10c) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | [b72fe24642](https://linux-hardware.org/?probe=b72fe24642) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | [4dc675b81c](https://linux-hardware.org/?probe=4dc675b81c) | Apr 27, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [1a773927c4](https://linux-hardware.org/?probe=1a773927c4) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [d23e7110f6](https://linux-hardware.org/?probe=d23e7110f6) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [3390e01a9c](https://linux-hardware.org/?probe=3390e01a9c) | Apr 27, 2022 |
| Timi          | RedmiBook Pro 15S           | [d060ed71c3](https://linux-hardware.org/?probe=d060ed71c3) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Acer          | Aspire E1-571               | [009a9c8ce0](https://linux-hardware.org/?probe=009a9c8ce0) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8104edaf22](https://linux-hardware.org/?probe=8104edaf22) | Apr 24, 2022 |
| ASUSTek       | X550VX                      | [2e5a3b2158](https://linux-hardware.org/?probe=2e5a3b2158) | Apr 24, 2022 |
| Dell          | XPS 12-9Q33                 | [5cbe457f54](https://linux-hardware.org/?probe=5cbe457f54) | Apr 24, 2022 |
| Dell          | Vostro 3500                 | [33a9b533e8](https://linux-hardware.org/?probe=33a9b533e8) | Apr 23, 2022 |
| Dell          | Vostro 3500                 | [ffb0508bd2](https://linux-hardware.org/?probe=ffb0508bd2) | Apr 23, 2022 |
| Acer          | Aspire E1-571               | [4a76d57188](https://linux-hardware.org/?probe=4a76d57188) | Apr 23, 2022 |
| Acer          | Aspire E1-571               | [ee546b53aa](https://linux-hardware.org/?probe=ee546b53aa) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [0ca0b999d6](https://linux-hardware.org/?probe=0ca0b999d6) | Apr 23, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [998ea03b05](https://linux-hardware.org/?probe=998ea03b05) | Apr 22, 2022 |
| Apple         | MacBookPro9,2               | [2ceab75e03](https://linux-hardware.org/?probe=2ceab75e03) | Apr 22, 2022 |
| HP            | Notebook                    | [e6099e9fd5](https://linux-hardware.org/?probe=e6099e9fd5) | Apr 22, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [a1e3d6d19a](https://linux-hardware.org/?probe=a1e3d6d19a) | Apr 22, 2022 |
| HP            | Laptop 15-bs0xx             | [a1636896d9](https://linux-hardware.org/?probe=a1636896d9) | Apr 22, 2022 |
| HP            | Laptop 15-bs0xx             | [03481a94b3](https://linux-hardware.org/?probe=03481a94b3) | Apr 22, 2022 |
| Dell          | Inspiron 1764               | [4c6e3f36dd](https://linux-hardware.org/?probe=4c6e3f36dd) | Apr 21, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [aa08ee444f](https://linux-hardware.org/?probe=aa08ee444f) | Apr 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e0d5f104b9](https://linux-hardware.org/?probe=e0d5f104b9) | Apr 21, 2022 |
| HP            | Laptop 15-bw0xx             | [bf030ccfa0](https://linux-hardware.org/?probe=bf030ccfa0) | Apr 21, 2022 |
| MSI           | Modern 15 A11MU             | [9fc8be1cac](https://linux-hardware.org/?probe=9fc8be1cac) | Apr 21, 2022 |
| HP            | ZBook 15 G3                 | [3b23a0c003](https://linux-hardware.org/?probe=3b23a0c003) | Apr 20, 2022 |
| Dell          | XPS 13 9333                 | [e3fcba68df](https://linux-hardware.org/?probe=e3fcba68df) | Apr 20, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [0ebad8c6f7](https://linux-hardware.org/?probe=0ebad8c6f7) | Apr 20, 2022 |
| Dell          | Latitude 5480               | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| HP            | Laptop 15-bw0xx             | [790b162fa0](https://linux-hardware.org/?probe=790b162fa0) | Apr 20, 2022 |
| Toshiba       | Satellite L50-C             | [9e2b287533](https://linux-hardware.org/?probe=9e2b287533) | Apr 20, 2022 |
| HP            | Laptop 17-cn0xxx            | [2851261ddb](https://linux-hardware.org/?probe=2851261ddb) | Apr 20, 2022 |
| MSI           | GS60 2PE                    | [89a2ef83fd](https://linux-hardware.org/?probe=89a2ef83fd) | Apr 20, 2022 |
| Lenovo        | ThinkPad T400 6474WBN       | [8bac0a70d6](https://linux-hardware.org/?probe=8bac0a70d6) | Apr 20, 2022 |
| Lenovo        | ThinkPad T400 6474WBN       | [b7f4f882f3](https://linux-hardware.org/?probe=b7f4f882f3) | Apr 19, 2022 |
| Lenovo        | 3000 N100 076835U           | [31a5dc6cf6](https://linux-hardware.org/?probe=31a5dc6cf6) | Apr 19, 2022 |
| Lenovo        | ThinkPad T440p 20AWS03H0... | [0458ae6c71](https://linux-hardware.org/?probe=0458ae6c71) | Apr 19, 2022 |
| Timi          | A35S                        | [e7d8adf61f](https://linux-hardware.org/?probe=e7d8adf61f) | Apr 19, 2022 |
| Apple         | MacBookPro11,1              | [a010271a3d](https://linux-hardware.org/?probe=a010271a3d) | Apr 19, 2022 |
| Dell          | Inspiron 5558               | [51a3d5d920](https://linux-hardware.org/?probe=51a3d5d920) | Apr 19, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [a33d067e62](https://linux-hardware.org/?probe=a33d067e62) | Apr 18, 2022 |
| Dell          | Latitude E7440              | [8609968661](https://linux-hardware.org/?probe=8609968661) | Apr 18, 2022 |
| MSI           | Modern 14 B10MW             | [3ad8717f9a](https://linux-hardware.org/?probe=3ad8717f9a) | Apr 18, 2022 |
| Apple         | MacBookAir5,2               | [2cca37f312](https://linux-hardware.org/?probe=2cca37f312) | Apr 18, 2022 |
| Dell          | Inspiron 5567               | [e9f6594677](https://linux-hardware.org/?probe=e9f6594677) | Apr 18, 2022 |
| Dell          | Inspiron 5567               | [d6b72a0160](https://linux-hardware.org/?probe=d6b72a0160) | Apr 18, 2022 |
| HP            | ProBook 4535s               | [23ab986b5e](https://linux-hardware.org/?probe=23ab986b5e) | Apr 18, 2022 |
| Apple         | MacBookPro11,1              | [c9e6f401ab](https://linux-hardware.org/?probe=c9e6f401ab) | Apr 18, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [c7f2c2e71c](https://linux-hardware.org/?probe=c7f2c2e71c) | Apr 18, 2022 |
| Acer          | Aspire A515-43              | [c661d7a105](https://linux-hardware.org/?probe=c661d7a105) | Apr 18, 2022 |
| Acer          | Aspire V3-571               | [b1ea72b76e](https://linux-hardware.org/?probe=b1ea72b76e) | Apr 18, 2022 |
| Dell          | Latitude E7440              | [bd010335eb](https://linux-hardware.org/?probe=bd010335eb) | Apr 17, 2022 |
| HP            | Laptop 17-cn0xxx            | [abdd8db787](https://linux-hardware.org/?probe=abdd8db787) | Apr 17, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [49f90b075b](https://linux-hardware.org/?probe=49f90b075b) | Apr 17, 2022 |
| HP            | Laptop 15s-fq3xxx           | [1fef674c68](https://linux-hardware.org/?probe=1fef674c68) | Apr 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a37c8a7b48](https://linux-hardware.org/?probe=a37c8a7b48) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [0d918922ac](https://linux-hardware.org/?probe=0d918922ac) | Apr 16, 2022 |
| Toshiba       | Satellite L775-151          | [957020b872](https://linux-hardware.org/?probe=957020b872) | Apr 16, 2022 |
| Toshiba       | Satellite L775-151          | [706f14a3e6](https://linux-hardware.org/?probe=706f14a3e6) | Apr 16, 2022 |
| Lenovo        | ThinkPad X230 2325YGM       | [3606442649](https://linux-hardware.org/?probe=3606442649) | Apr 16, 2022 |
| ASUSTek       | X510UAR                     | [b39b237ff0](https://linux-hardware.org/?probe=b39b237ff0) | Apr 16, 2022 |
| Lenovo        | ThinkPad L440 20ASA02800    | [697a90ffa2](https://linux-hardware.org/?probe=697a90ffa2) | Apr 16, 2022 |
| Apple         | MacBookPro9,2               | [144971e364](https://linux-hardware.org/?probe=144971e364) | Apr 16, 2022 |
| Timi          | RedmiBook Pro 15S           | [e29970db9c](https://linux-hardware.org/?probe=e29970db9c) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS03H0... | [64fb4146d0](https://linux-hardware.org/?probe=64fb4146d0) | Apr 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c6f1d1b99b](https://linux-hardware.org/?probe=c6f1d1b99b) | Apr 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [6d63a9c8bc](https://linux-hardware.org/?probe=6d63a9c8bc) | Apr 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [48e04dd798](https://linux-hardware.org/?probe=48e04dd798) | Apr 15, 2022 |
| HP            | Laptop 15s-fq3xxx           | [1488e2a91f](https://linux-hardware.org/?probe=1488e2a91f) | Apr 15, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [1877553731](https://linux-hardware.org/?probe=1877553731) | Apr 15, 2022 |
| Dell          | XPS 13 9333                 | [0d1712dd76](https://linux-hardware.org/?probe=0d1712dd76) | Apr 14, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [13bfd82a49](https://linux-hardware.org/?probe=13bfd82a49) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [8b693a6221](https://linux-hardware.org/?probe=8b693a6221) | Apr 14, 2022 |
| TUXEDO        | PA70ES                      | [aa3ae14c59](https://linux-hardware.org/?probe=aa3ae14c59) | Apr 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [154eb4b040](https://linux-hardware.org/?probe=154eb4b040) | Apr 14, 2022 |
| Framework     | Laptop                      | [2550bb5cd7](https://linux-hardware.org/?probe=2550bb5cd7) | Apr 14, 2022 |
| Dell          | Latitude 5480               | [41b0487e91](https://linux-hardware.org/?probe=41b0487e91) | Apr 14, 2022 |
| Dell          | XPS 15 9510                 | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| Lenovo        | ThinkPad T495s 20QKS01E0... | [4035ec75ce](https://linux-hardware.org/?probe=4035ec75ce) | Apr 14, 2022 |
| Acer          | Aspire F5-573G              | [26ac9971a3](https://linux-hardware.org/?probe=26ac9971a3) | Apr 13, 2022 |
| Toshiba       | Satellite C855D             | [aada4d4d5e](https://linux-hardware.org/?probe=aada4d4d5e) | Apr 13, 2022 |
| Lenovo        | ThinkPad T460s 20F90044M... | [47498ed4aa](https://linux-hardware.org/?probe=47498ed4aa) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Avell High... | B.ON                        | [0e81f76e2b](https://linux-hardware.org/?probe=0e81f76e2b) | Apr 13, 2022 |
| HP            | ProBook 4535s               | [1aa29ed37f](https://linux-hardware.org/?probe=1aa29ed37f) | Apr 13, 2022 |
| ASUSTek       | X550VX                      | [be27a452e2](https://linux-hardware.org/?probe=be27a452e2) | Apr 13, 2022 |
| ASUSTek       | X550VX                      | [19bfd91984](https://linux-hardware.org/?probe=19bfd91984) | Apr 13, 2022 |
| ASUSTek       | G752VL                      | [910e126de2](https://linux-hardware.org/?probe=910e126de2) | Apr 13, 2022 |
| Dell          | Inspiron 17 7000 Series ... | [c8abf66820](https://linux-hardware.org/?probe=c8abf66820) | Apr 12, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | [64e00f7a40](https://linux-hardware.org/?probe=64e00f7a40) | Apr 12, 2022 |
| HP            | ZBook 15                    | [c8c2248854](https://linux-hardware.org/?probe=c8c2248854) | Apr 11, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [17f7c92cc6](https://linux-hardware.org/?probe=17f7c92cc6) | Apr 11, 2022 |
| ASUSTek       | G752VL                      | [ee065014a8](https://linux-hardware.org/?probe=ee065014a8) | Apr 11, 2022 |
| HONOR         | BMH-WCX9                    | [7bc4dfd917](https://linux-hardware.org/?probe=7bc4dfd917) | Apr 10, 2022 |
| HP            | Notebook                    | [24faf4835d](https://linux-hardware.org/?probe=24faf4835d) | Apr 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2fa2ca8320](https://linux-hardware.org/?probe=2fa2ca8320) | Apr 10, 2022 |
| Monster       | ABRA A5 V12.1               | [4b45daf3b2](https://linux-hardware.org/?probe=4b45daf3b2) | Apr 10, 2022 |
| Lenovo        | B560                        | [276b375e4a](https://linux-hardware.org/?probe=276b375e4a) | Apr 09, 2022 |
| ASUSTek       | UX310UA                     | [732364c253](https://linux-hardware.org/?probe=732364c253) | Apr 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [6099079c27](https://linux-hardware.org/?probe=6099079c27) | Apr 09, 2022 |
| Timi          | A35                         | [d7e8ca818b](https://linux-hardware.org/?probe=d7e8ca818b) | Apr 09, 2022 |
| HP            | 250 G4 Notebook PC          | [7f35e9e656](https://linux-hardware.org/?probe=7f35e9e656) | Apr 09, 2022 |
| HP            | ZBook 15                    | [ee70932ef2](https://linux-hardware.org/?probe=ee70932ef2) | Apr 09, 2022 |
| Acer          | Aspire A315-21              | [163d8c26a5](https://linux-hardware.org/?probe=163d8c26a5) | Apr 09, 2022 |
| MSI           | GS70 6QE                    | [8e387655c0](https://linux-hardware.org/?probe=8e387655c0) | Apr 08, 2022 |
| Lenovo        | Z51-70 80K6                 | [dc1db2125f](https://linux-hardware.org/?probe=dc1db2125f) | Apr 08, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [414464db43](https://linux-hardware.org/?probe=414464db43) | Apr 08, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | [ca8d7c1137](https://linux-hardware.org/?probe=ca8d7c1137) | Apr 08, 2022 |
| Dell          | Inspiron N5110              | [993ad2218a](https://linux-hardware.org/?probe=993ad2218a) | Apr 07, 2022 |
| Dell          | Latitude 5480               | [82b5d0a46e](https://linux-hardware.org/?probe=82b5d0a46e) | Apr 07, 2022 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [8dae5ce312](https://linux-hardware.org/?probe=8dae5ce312) | Apr 07, 2022 |
| HP            | ProBook 445 G7              | [ce5b95cf78](https://linux-hardware.org/?probe=ce5b95cf78) | Apr 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [2f09a13f44](https://linux-hardware.org/?probe=2f09a13f44) | Apr 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [bb750c0f56](https://linux-hardware.org/?probe=bb750c0f56) | Apr 06, 2022 |
| Dell          | Latitude E7250              | [a39d4e32a0](https://linux-hardware.org/?probe=a39d4e32a0) | Apr 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [73a02fadb2](https://linux-hardware.org/?probe=73a02fadb2) | Apr 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [9b7950cd38](https://linux-hardware.org/?probe=9b7950cd38) | Apr 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [943191da55](https://linux-hardware.org/?probe=943191da55) | Apr 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [9a0f2c7fe7](https://linux-hardware.org/?probe=9a0f2c7fe7) | Apr 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [81165aa277](https://linux-hardware.org/?probe=81165aa277) | Apr 05, 2022 |
| HP            | Pavilion g6                 | [a2d8dcb1bf](https://linux-hardware.org/?probe=a2d8dcb1bf) | Apr 05, 2022 |
| Gigabyte      | AERO 15 YD                  | [bac9bb4c7e](https://linux-hardware.org/?probe=bac9bb4c7e) | Apr 05, 2022 |
| Gigabyte      | AERO 15 YD                  | [55de739c49](https://linux-hardware.org/?probe=55de739c49) | Apr 05, 2022 |
| HP            | Victus by Laptop 16         | [62650f5d20](https://linux-hardware.org/?probe=62650f5d20) | Apr 04, 2022 |
| Timi          | RedmiBook Pro 15S           | [9c1fd6c304](https://linux-hardware.org/?probe=9c1fd6c304) | Apr 04, 2022 |
| Apple         | MacBookPro12,1              | [44a524bb2f](https://linux-hardware.org/?probe=44a524bb2f) | Apr 03, 2022 |
| HP            | Unknown                     | [e33741c278](https://linux-hardware.org/?probe=e33741c278) | Apr 03, 2022 |
| Dell          | Inspiron 5559               | [ba24b37041](https://linux-hardware.org/?probe=ba24b37041) | Apr 03, 2022 |
| Dell          | Inspiron 5559               | [57a0d73ab9](https://linux-hardware.org/?probe=57a0d73ab9) | Apr 02, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [736e44b59d](https://linux-hardware.org/?probe=736e44b59d) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| HP            | Unknown                     | [761f0c08b2](https://linux-hardware.org/?probe=761f0c08b2) | Apr 02, 2022 |
| HP            | Pavilion dv6                | [bacb1d04de](https://linux-hardware.org/?probe=bacb1d04de) | Apr 02, 2022 |
| MSI           | MS-7816                     | [5641d3418b](https://linux-hardware.org/?probe=5641d3418b) | Apr 01, 2022 |
| HP            | Laptop 14-dk1xxx            | [4fb10b4b1b](https://linux-hardware.org/?probe=4fb10b4b1b) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | [00630dc1b2](https://linux-hardware.org/?probe=00630dc1b2) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | [373ac41605](https://linux-hardware.org/?probe=373ac41605) | Apr 01, 2022 |
| Dell          | Inspiron 5515               | [224f954e8f](https://linux-hardware.org/?probe=224f954e8f) | Apr 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [39b70e2f99](https://linux-hardware.org/?probe=39b70e2f99) | Apr 01, 2022 |
| Lenovo        | ThinkPad L512 2598AM7       | [92d91f4fb8](https://linux-hardware.org/?probe=92d91f4fb8) | Mar 31, 2022 |
| Gateway       | NV57H                       | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| HP            | ZBook 17 G6                 | [a18aa9fa7e](https://linux-hardware.org/?probe=a18aa9fa7e) | Mar 31, 2022 |
| HP            | Pavilion g6                 | [a9a0826520](https://linux-hardware.org/?probe=a9a0826520) | Mar 31, 2022 |
| Lenovo        | ThinkPad L512 2598AM7       | [661c16a667](https://linux-hardware.org/?probe=661c16a667) | Mar 31, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [eeb03a5d88](https://linux-hardware.org/?probe=eeb03a5d88) | Mar 31, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [10fe068865](https://linux-hardware.org/?probe=10fe068865) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | [85f1411d0e](https://linux-hardware.org/?probe=85f1411d0e) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | [f8edce28d5](https://linux-hardware.org/?probe=f8edce28d5) | Mar 30, 2022 |
| Samsung       | 530XBB                      | [cf7f06b3fe](https://linux-hardware.org/?probe=cf7f06b3fe) | Mar 30, 2022 |
| HP            | ProBook 430 G3              | [8623b2ac51](https://linux-hardware.org/?probe=8623b2ac51) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| HP            | ProBook 455 G7              | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Dell          | Vostro 5402                 | [9fde02b49a](https://linux-hardware.org/?probe=9fde02b49a) | Mar 30, 2022 |
| ASUSTek       | G751JT                      | [c247b0bad3](https://linux-hardware.org/?probe=c247b0bad3) | Mar 30, 2022 |
| Dell          | XPS 15 9500                 | [8cf6c58236](https://linux-hardware.org/?probe=8cf6c58236) | Mar 29, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ab2bed88a7](https://linux-hardware.org/?probe=ab2bed88a7) | Mar 29, 2022 |
| ASUSTek       | X580VD                      | [192125a71f](https://linux-hardware.org/?probe=192125a71f) | Mar 29, 2022 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | [8199781e64](https://linux-hardware.org/?probe=8199781e64) | Mar 28, 2022 |
| HONOR         | HGE-WX6                     | [d59a8be353](https://linux-hardware.org/?probe=d59a8be353) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [b431dc3d73](https://linux-hardware.org/?probe=b431dc3d73) | Mar 28, 2022 |
| Acer          | Aspire 5560                 | [6c3b8c6e6c](https://linux-hardware.org/?probe=6c3b8c6e6c) | Mar 28, 2022 |
| HP            | ProBook 4340s               | [787443949a](https://linux-hardware.org/?probe=787443949a) | Mar 27, 2022 |
| Dell          | XPS 15 9500                 | [26c61ab42f](https://linux-hardware.org/?probe=26c61ab42f) | Mar 27, 2022 |
| ASUSTek       | GL502VT                     | [6e19fc670b](https://linux-hardware.org/?probe=6e19fc670b) | Mar 27, 2022 |
| ASUSTek       | GL502VT                     | [c4ce562b21](https://linux-hardware.org/?probe=c4ce562b21) | Mar 27, 2022 |
| HP            | Laptop 15-bs0xx             | [bd875807ce](https://linux-hardware.org/?probe=bd875807ce) | Mar 26, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | [277143e66b](https://linux-hardware.org/?probe=277143e66b) | Mar 26, 2022 |
| Dell          | Vostro 7590                 | [1a15d49b97](https://linux-hardware.org/?probe=1a15d49b97) | Mar 25, 2022 |
| Dell          | Latitude E7240              | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | [d5b5eeffc8](https://linux-hardware.org/?probe=d5b5eeffc8) | Mar 25, 2022 |
| HP            | Laptop 15-bs0xx             | [96f9ba743f](https://linux-hardware.org/?probe=96f9ba743f) | Mar 25, 2022 |
| Apple         | MacBookPro14,1              | [f453ee2c77](https://linux-hardware.org/?probe=f453ee2c77) | Mar 25, 2022 |
| Dell          | XPS 17 9710                 | [4f862c8b5e](https://linux-hardware.org/?probe=4f862c8b5e) | Mar 25, 2022 |
| MSI           | GS60 2PE                    | [7700fa2b69](https://linux-hardware.org/?probe=7700fa2b69) | Mar 24, 2022 |
| Dell          | Vostro 5515                 | [b3f93f17bb](https://linux-hardware.org/?probe=b3f93f17bb) | Mar 24, 2022 |
| Dell          | Latitude E5530 non-vPro     | [80a259fdac](https://linux-hardware.org/?probe=80a259fdac) | Mar 24, 2022 |
| ASUSTek       | N56VZ                       | [7ad46659a5](https://linux-hardware.org/?probe=7ad46659a5) | Mar 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8533e3cf0d](https://linux-hardware.org/?probe=8533e3cf0d) | Mar 23, 2022 |
| HP            | Laptop 15s-fq1xxx           | [d081c85de2](https://linux-hardware.org/?probe=d081c85de2) | Mar 23, 2022 |
| Acer          | Nitro AN515-54              | [4bb7650e38](https://linux-hardware.org/?probe=4bb7650e38) | Mar 23, 2022 |
| Dell          | Vostro 5481                 | [82934a5fbf](https://linux-hardware.org/?probe=82934a5fbf) | Mar 23, 2022 |
| HP            | Pavilion Notebook           | [e02916c256](https://linux-hardware.org/?probe=e02916c256) | Mar 22, 2022 |
| MSI           | GE62 6QF                    | [4596b4e280](https://linux-hardware.org/?probe=4596b4e280) | Mar 22, 2022 |
| HP            | Pavilion g7                 | [9d4d9b0c34](https://linux-hardware.org/?probe=9d4d9b0c34) | Mar 22, 2022 |
| Dell          | Latitude 7420               | [d9f1365e01](https://linux-hardware.org/?probe=d9f1365e01) | Mar 22, 2022 |
| Apple         | MacBookAir3,1               | [482fbd3456](https://linux-hardware.org/?probe=482fbd3456) | Mar 21, 2022 |
| HP            | 255 G7 Notebook PC          | [ce0d6584b2](https://linux-hardware.org/?probe=ce0d6584b2) | Mar 21, 2022 |
| Timi          | RedmiBook 16                | [0d8a2d4ea4](https://linux-hardware.org/?probe=0d8a2d4ea4) | Mar 21, 2022 |
| Casper        | EXCALIBUR G900              | [d4902562f0](https://linux-hardware.org/?probe=d4902562f0) | Mar 21, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [490b0d88b3](https://linux-hardware.org/?probe=490b0d88b3) | Mar 20, 2022 |
| Acer          | Aspire A515-43              | [48816e7394](https://linux-hardware.org/?probe=48816e7394) | Mar 20, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [8e148f567b](https://linux-hardware.org/?probe=8e148f567b) | Mar 19, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [52558a7cc2](https://linux-hardware.org/?probe=52558a7cc2) | Mar 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [ee813d0051](https://linux-hardware.org/?probe=ee813d0051) | Mar 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [6adea9d280](https://linux-hardware.org/?probe=6adea9d280) | Mar 19, 2022 |
| Dell          | Latitude 5285               | [662d409a76](https://linux-hardware.org/?probe=662d409a76) | Mar 18, 2022 |
| Dell          | Latitude 5285               | [fb9225d49b](https://linux-hardware.org/?probe=fb9225d49b) | Mar 18, 2022 |
| Dell          | XPS 13 9360                 | [962a1f764e](https://linux-hardware.org/?probe=962a1f764e) | Mar 18, 2022 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [0cd9c29dd0](https://linux-hardware.org/?probe=0cd9c29dd0) | Mar 18, 2022 |
| HP            | Victus by Laptop 16         | [cbf47a2c89](https://linux-hardware.org/?probe=cbf47a2c89) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK U748               | [7451bcb3ef](https://linux-hardware.org/?probe=7451bcb3ef) | Mar 17, 2022 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [b8fa124867](https://linux-hardware.org/?probe=b8fa124867) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [75909ee2fc](https://linux-hardware.org/?probe=75909ee2fc) | Mar 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [b289d3d5b9](https://linux-hardware.org/?probe=b289d3d5b9) | Mar 17, 2022 |
| Google        | Nightfury                   | [33c6929b2c](https://linux-hardware.org/?probe=33c6929b2c) | Mar 16, 2022 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [d49f3c26e1](https://linux-hardware.org/?probe=d49f3c26e1) | Mar 16, 2022 |
| HP            | 250 G8 Notebook PC          | [90bbda2f8c](https://linux-hardware.org/?probe=90bbda2f8c) | Mar 16, 2022 |
| MSI           | Alpha 15 B5EEK              | [f4c72eaa35](https://linux-hardware.org/?probe=f4c72eaa35) | Mar 15, 2022 |
| Dell          | XPS 15 9560                 | [25c3d1bf8e](https://linux-hardware.org/?probe=25c3d1bf8e) | Mar 15, 2022 |
| HP            | Laptop 14-fq1xxx            | [de6a7f79dc](https://linux-hardware.org/?probe=de6a7f79dc) | Mar 15, 2022 |
| Fujitsu       | LIFEBOOK T901               | [fcb0dd110e](https://linux-hardware.org/?probe=fcb0dd110e) | Mar 15, 2022 |
| HP            | Laptop 14-fq1xxx            | [8116dd6dc0](https://linux-hardware.org/?probe=8116dd6dc0) | Mar 14, 2022 |
| Acer          | Aspire E5-553G              | [ebeea29eda](https://linux-hardware.org/?probe=ebeea29eda) | Mar 14, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| Dell          | Inspiron 1545               | [461f90d3a5](https://linux-hardware.org/?probe=461f90d3a5) | Mar 14, 2022 |
| Dell          | XPS 15 7590                 | [527b0d7066](https://linux-hardware.org/?probe=527b0d7066) | Mar 14, 2022 |
| Dell          | Latitude 5400               | [e23429d8ea](https://linux-hardware.org/?probe=e23429d8ea) | Mar 13, 2022 |
| Acer          | Swift SF514-54GT            | [a170593a67](https://linux-hardware.org/?probe=a170593a67) | Mar 13, 2022 |
| HP            | ProBook 4340s               | [01af2dee98](https://linux-hardware.org/?probe=01af2dee98) | Mar 13, 2022 |
| MSI           | Alpha 15 B5EEK              | [8859888f0c](https://linux-hardware.org/?probe=8859888f0c) | Mar 12, 2022 |
| Lenovo        | G580 20150                  | [1eeedb6d3e](https://linux-hardware.org/?probe=1eeedb6d3e) | Mar 12, 2022 |
| HP            | Pavilion dm1                | [d65e1a184d](https://linux-hardware.org/?probe=d65e1a184d) | Mar 12, 2022 |
| Intel Clie... | LAPQC71A                    | [14108beccf](https://linux-hardware.org/?probe=14108beccf) | Mar 12, 2022 |
| Intel Clie... | LAPQC71A                    | [ee7f4f0b82](https://linux-hardware.org/?probe=ee7f4f0b82) | Mar 12, 2022 |
| Apple         | MacBookPro14,1              | [cef0b5d08f](https://linux-hardware.org/?probe=cef0b5d08f) | Mar 12, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4Q20... | [4d9c3fdcc5](https://linux-hardware.org/?probe=4d9c3fdcc5) | Mar 12, 2022 |
| ASUSTek       | GL553VD                     | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| Dell          | Vostro 5471                 | [8248b17f01](https://linux-hardware.org/?probe=8248b17f01) | Mar 11, 2022 |
| Apple         | MacBookPro14,1              | [5be1842448](https://linux-hardware.org/?probe=5be1842448) | Mar 11, 2022 |
| ASUSTek       | G73Jh                       | [4f1cae64b4](https://linux-hardware.org/?probe=4f1cae64b4) | Mar 11, 2022 |
| MSI           | GF65 Thin 9SEXR             | [14747d7263](https://linux-hardware.org/?probe=14747d7263) | Mar 11, 2022 |
| Dell          | Latitude 5480               | [817e973e9d](https://linux-hardware.org/?probe=817e973e9d) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8469a31d58](https://linux-hardware.org/?probe=8469a31d58) | Mar 10, 2022 |
| Apple         | MacBookAir6,2               | [92f34786b4](https://linux-hardware.org/?probe=92f34786b4) | Mar 10, 2022 |
| Acer          | Swift SF314-42              | [160a8dd021](https://linux-hardware.org/?probe=160a8dd021) | Mar 10, 2022 |
| HP            | ProBook 455 G1              | [c6ad6edf70](https://linux-hardware.org/?probe=c6ad6edf70) | Mar 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4b0c952d9b](https://linux-hardware.org/?probe=4b0c952d9b) | Mar 09, 2022 |
| Acer          | Swift SF314-42              | [e323bc4a41](https://linux-hardware.org/?probe=e323bc4a41) | Mar 09, 2022 |
| HONOR         | NMH-WCX9                    | [fab21c122b](https://linux-hardware.org/?probe=fab21c122b) | Mar 09, 2022 |
| Dell          | Vostro 5471                 | [6e46455791](https://linux-hardware.org/?probe=6e46455791) | Mar 09, 2022 |
| Dell          | G7 7588                     | [6a2247e8e1](https://linux-hardware.org/?probe=6a2247e8e1) | Mar 09, 2022 |
| Toshiba       | Satellite L10W-B-101        | [4425801f5c](https://linux-hardware.org/?probe=4425801f5c) | Mar 09, 2022 |
| HONOR         | NMH-WCX9                    | [9bd4914d8e](https://linux-hardware.org/?probe=9bd4914d8e) | Mar 08, 2022 |
| Acer          | Swift SF314-42              | [321af0eb17](https://linux-hardware.org/?probe=321af0eb17) | Mar 08, 2022 |
| HP            | EliteBook 850 G1            | [b2aeea55e5](https://linux-hardware.org/?probe=b2aeea55e5) | Mar 07, 2022 |
| HP            | Laptop 14 14s-dq1008ni      | [8184627283](https://linux-hardware.org/?probe=8184627283) | Mar 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [ea52efd6b6](https://linux-hardware.org/?probe=ea52efd6b6) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CLS06L00    | [e6d00b85ed](https://linux-hardware.org/?probe=e6d00b85ed) | Mar 06, 2022 |
| Lenovo        | G580 20150                  | [a75c798641](https://linux-hardware.org/?probe=a75c798641) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | [31f37e7748](https://linux-hardware.org/?probe=31f37e7748) | Mar 05, 2022 |
| Chuwi         | HeroBook Air                | [77ffb9a5a6](https://linux-hardware.org/?probe=77ffb9a5a6) | Mar 05, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [7e97d74a65](https://linux-hardware.org/?probe=7e97d74a65) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Chuwi         | HeroBook Air                | [167b8de1e1](https://linux-hardware.org/?probe=167b8de1e1) | Mar 05, 2022 |
| Dell          | Inspiron 5735               | [cc6ad48a04](https://linux-hardware.org/?probe=cc6ad48a04) | Mar 05, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [61191e0c42](https://linux-hardware.org/?probe=61191e0c42) | Mar 04, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [3a12accc7d](https://linux-hardware.org/?probe=3a12accc7d) | Mar 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [89e8399104](https://linux-hardware.org/?probe=89e8399104) | Mar 03, 2022 |
| Apple         | MacBookPro12,1              | [29053388a7](https://linux-hardware.org/?probe=29053388a7) | Mar 03, 2022 |
| Clevo         | E512xQ/E4129                | [7aff97f14f](https://linux-hardware.org/?probe=7aff97f14f) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| UNOWHY        | Y14G101S2E                  | [1c7bb4416a](https://linux-hardware.org/?probe=1c7bb4416a) | Mar 02, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [c697a91a8e](https://linux-hardware.org/?probe=c697a91a8e) | Mar 02, 2022 |
| UNOWHY        | Y14G101S2E                  | [1b4f96aec6](https://linux-hardware.org/?probe=1b4f96aec6) | Mar 02, 2022 |
| Dell          | XPS 13 9333                 | [93ec468fa7](https://linux-hardware.org/?probe=93ec468fa7) | Mar 02, 2022 |
| ASUSTek       | X555LAB                     | [0a0e3feff6](https://linux-hardware.org/?probe=0a0e3feff6) | Mar 01, 2022 |
| ASUSTek       | X555LAB                     | [2b791434ce](https://linux-hardware.org/?probe=2b791434ce) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [60d1c44981](https://linux-hardware.org/?probe=60d1c44981) | Feb 28, 2022 |
| Toshiba       | Satellite C655D             | [10f38d005e](https://linux-hardware.org/?probe=10f38d005e) | Feb 28, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [58d47eab9c](https://linux-hardware.org/?probe=58d47eab9c) | Feb 28, 2022 |
| HP            | Pavilion g7                 | [c9fa0137bd](https://linux-hardware.org/?probe=c9fa0137bd) | Feb 27, 2022 |
| Dell          | Latitude 5420               | [8f9eabc64b](https://linux-hardware.org/?probe=8f9eabc64b) | Feb 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [c1bee41eec](https://linux-hardware.org/?probe=c1bee41eec) | Feb 27, 2022 |
| Packard Be... | EasyNote TK85               | [97ab51b64a](https://linux-hardware.org/?probe=97ab51b64a) | Feb 26, 2022 |
| HP            | Notebook                    | [51dbbe9d8d](https://linux-hardware.org/?probe=51dbbe9d8d) | Feb 26, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [42cbfe4ee6](https://linux-hardware.org/?probe=42cbfe4ee6) | Feb 26, 2022 |
| Dell          | Latitude E6420              | [97ebb25b17](https://linux-hardware.org/?probe=97ebb25b17) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [16281a52e8](https://linux-hardware.org/?probe=16281a52e8) | Feb 26, 2022 |
| HP            | Pavilion g7                 | [66d6050018](https://linux-hardware.org/?probe=66d6050018) | Feb 25, 2022 |
| Timi          | RedmiBook 13 R              | [a74bea030c](https://linux-hardware.org/?probe=a74bea030c) | Feb 25, 2022 |
| Timi          | RedmiBook 13 R              | [318a4d1d35](https://linux-hardware.org/?probe=318a4d1d35) | Feb 25, 2022 |
| Dell          | Inspiron 5505               | [42117b7c9e](https://linux-hardware.org/?probe=42117b7c9e) | Feb 25, 2022 |
| MSI           | P65 Creator 9SD             | [093c9b9f41](https://linux-hardware.org/?probe=093c9b9f41) | Feb 24, 2022 |
| MSI           | GS60 2PE                    | [2a0cbe38d7](https://linux-hardware.org/?probe=2a0cbe38d7) | Feb 24, 2022 |
| Toshiba       | Satellite L300              | [9f42d69f9f](https://linux-hardware.org/?probe=9f42d69f9f) | Feb 24, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [9a94ad6810](https://linux-hardware.org/?probe=9a94ad6810) | Feb 23, 2022 |
| MSI           | GT72 6QD                    | [7f4b5361a7](https://linux-hardware.org/?probe=7f4b5361a7) | Feb 23, 2022 |
| MSI           | P65 Creator 9SD             | [2782f833c9](https://linux-hardware.org/?probe=2782f833c9) | Feb 23, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [742af9249b](https://linux-hardware.org/?probe=742af9249b) | Feb 23, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [0a9140ff8f](https://linux-hardware.org/?probe=0a9140ff8f) | Feb 22, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [63fe1b47e9](https://linux-hardware.org/?probe=63fe1b47e9) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [3886078240](https://linux-hardware.org/?probe=3886078240) | Feb 22, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [78e355e895](https://linux-hardware.org/?probe=78e355e895) | Feb 21, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [1adb30dfb2](https://linux-hardware.org/?probe=1adb30dfb2) | Feb 21, 2022 |
| Dell          | Latitude 7490               | [003b6b4a95](https://linux-hardware.org/?probe=003b6b4a95) | Feb 21, 2022 |
| HP            | Notebook                    | [d734cd43d3](https://linux-hardware.org/?probe=d734cd43d3) | Feb 21, 2022 |
| Dell          | Inspiron 5558               | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b4979c164c](https://linux-hardware.org/?probe=b4979c164c) | Feb 20, 2022 |
| Lenovo        | ThinkPad ThinkPad L14 20... | [369c625e43](https://linux-hardware.org/?probe=369c625e43) | Feb 20, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [215889b22b](https://linux-hardware.org/?probe=215889b22b) | Feb 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [b91f497b74](https://linux-hardware.org/?probe=b91f497b74) | Feb 19, 2022 |
| Lenovo        | V330-15IKB 81AX             | [3bc582ad91](https://linux-hardware.org/?probe=3bc582ad91) | Feb 19, 2022 |
| HP            | Notebook                    | [1e57c317b4](https://linux-hardware.org/?probe=1e57c317b4) | Feb 19, 2022 |
| HP            | Notebook                    | [583b61ead6](https://linux-hardware.org/?probe=583b61ead6) | Feb 19, 2022 |
| HP            | 250 G8 Notebook PC          | [f7adb86dce](https://linux-hardware.org/?probe=f7adb86dce) | Feb 18, 2022 |
| Dell          | Inspiron 5548               | [862a31fa80](https://linux-hardware.org/?probe=862a31fa80) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [3c30a8c6a1](https://linux-hardware.org/?probe=3c30a8c6a1) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4fba279b51](https://linux-hardware.org/?probe=4fba279b51) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [42cf76ea1b](https://linux-hardware.org/?probe=42cf76ea1b) | Feb 18, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [91540e8aa6](https://linux-hardware.org/?probe=91540e8aa6) | Feb 18, 2022 |
| Acer          | Aspire 5750G                | [3bb86aa608](https://linux-hardware.org/?probe=3bb86aa608) | Feb 17, 2022 |
| Dell          | Inspiron 5505               | [ac3f9fa03e](https://linux-hardware.org/?probe=ac3f9fa03e) | Feb 17, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [1e700d65ea](https://linux-hardware.org/?probe=1e700d65ea) | Feb 17, 2022 |
| Apple         | MacBookAir3,2               | [2e812a8de9](https://linux-hardware.org/?probe=2e812a8de9) | Feb 17, 2022 |
| Dell          | Inspiron 5567               | [00fa8d31f3](https://linux-hardware.org/?probe=00fa8d31f3) | Feb 17, 2022 |
| Acer          | TravelMate P214-53          | [4d1c34fef7](https://linux-hardware.org/?probe=4d1c34fef7) | Feb 17, 2022 |
| ASUSTek       | X55A                        | [1ed422d0e2](https://linux-hardware.org/?probe=1ed422d0e2) | Feb 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| Google        | Chell                       | [a7795e2fb9](https://linux-hardware.org/?probe=a7795e2fb9) | Feb 15, 2022 |
| Google        | Chell                       | [9ec35bc2d1](https://linux-hardware.org/?probe=9ec35bc2d1) | Feb 15, 2022 |
| ASUSTek       | UX303UB                     | [ef498b262a](https://linux-hardware.org/?probe=ef498b262a) | Feb 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS06K0... | [60cf03acd8](https://linux-hardware.org/?probe=60cf03acd8) | Feb 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS06K0... | [8305aa0d2e](https://linux-hardware.org/?probe=8305aa0d2e) | Feb 15, 2022 |
| Toshiba       | Satellite C870D-11F         | [eaac3ab809](https://linux-hardware.org/?probe=eaac3ab809) | Feb 14, 2022 |
| Acer          | Swift SF114-32              | [92d9e3e1eb](https://linux-hardware.org/?probe=92d9e3e1eb) | Feb 14, 2022 |
| Acer          | Swift SF114-32              | [031e61417a](https://linux-hardware.org/?probe=031e61417a) | Feb 14, 2022 |
| Google        | Celes                       | [93a2853671](https://linux-hardware.org/?probe=93a2853671) | Feb 13, 2022 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [98d7355c52](https://linux-hardware.org/?probe=98d7355c52) | Feb 13, 2022 |
| Acer          | Swift SF315-51G             | [5e25ecab1f](https://linux-hardware.org/?probe=5e25ecab1f) | Feb 13, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [25027ae3f1](https://linux-hardware.org/?probe=25027ae3f1) | Feb 13, 2022 |
| Acer          | Aspire A315-23              | [2e9d58f492](https://linux-hardware.org/?probe=2e9d58f492) | Feb 13, 2022 |
| ASUSTek       | G74Sx                       | [a3709f6df1](https://linux-hardware.org/?probe=a3709f6df1) | Feb 12, 2022 |
| HP            | EliteBook 745 G3            | [a84f254fbc](https://linux-hardware.org/?probe=a84f254fbc) | Feb 12, 2022 |
| HP            | EliteBook 745 G3            | [26ed6eddae](https://linux-hardware.org/?probe=26ed6eddae) | Feb 12, 2022 |
| HP            | Pavilion g6                 | [da04806287](https://linux-hardware.org/?probe=da04806287) | Feb 11, 2022 |
| HP            | Laptop 15s-dr1xxx           | [8abd201999](https://linux-hardware.org/?probe=8abd201999) | Feb 11, 2022 |
| Dell          | Inspiron 5548               | [112bf24036](https://linux-hardware.org/?probe=112bf24036) | Feb 11, 2022 |
| HP            | Laptop 15s-dr1xxx           | [a84b20f4fd](https://linux-hardware.org/?probe=a84b20f4fd) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6df20f0f72](https://linux-hardware.org/?probe=6df20f0f72) | Feb 11, 2022 |
| MSI           | GP66 Leopard 11UG           | [3ac8f883ab](https://linux-hardware.org/?probe=3ac8f883ab) | Feb 11, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [0f65488b54](https://linux-hardware.org/?probe=0f65488b54) | Feb 11, 2022 |
| HP            | EliteBook 745 G3            | [21d3c81852](https://linux-hardware.org/?probe=21d3c81852) | Feb 10, 2022 |
| PC Special... | NH5x_7xRCx,RDx              | [3fad293703](https://linux-hardware.org/?probe=3fad293703) | Feb 10, 2022 |
| Gateway       | NV57H                       | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| HONOR         | BMH-WCX9                    | [ee510b7924](https://linux-hardware.org/?probe=ee510b7924) | Feb 09, 2022 |
| HP            | Notebook                    | [7900320935](https://linux-hardware.org/?probe=7900320935) | Feb 09, 2022 |
| Acer          | Nitro AN515-51              | [1308425490](https://linux-hardware.org/?probe=1308425490) | Feb 08, 2022 |
| Toshiba       | Satellite U900              | [de937d0299](https://linux-hardware.org/?probe=de937d0299) | Feb 07, 2022 |
| Toshiba       | Satellite U900              | [2c06fc7359](https://linux-hardware.org/?probe=2c06fc7359) | Feb 07, 2022 |
| Lenovo        | ThinkPad E495 20NES01600    | [c40a0c5222](https://linux-hardware.org/?probe=c40a0c5222) | Feb 07, 2022 |
| MSI           | GE76 Raider 11UH            | [092c3d1877](https://linux-hardware.org/?probe=092c3d1877) | Feb 07, 2022 |
| Samsung       | 550XDA                      | [9c9b8d6672](https://linux-hardware.org/?probe=9c9b8d6672) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c1fe9c81a0](https://linux-hardware.org/?probe=c1fe9c81a0) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f92b5e4b44](https://linux-hardware.org/?probe=f92b5e4b44) | Feb 06, 2022 |
| Lenovo        | ThinkPad E490 20N80029GE    | [463f54f91a](https://linux-hardware.org/?probe=463f54f91a) | Feb 05, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [dc86c1f5d5](https://linux-hardware.org/?probe=dc86c1f5d5) | Feb 05, 2022 |
| Toshiba       | Satellite L300              | [24713a7953](https://linux-hardware.org/?probe=24713a7953) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| Acer          | Aspire SW7-272              | [920f676336](https://linux-hardware.org/?probe=920f676336) | Feb 04, 2022 |
| Dell          | Latitude 9420               | [987feed95d](https://linux-hardware.org/?probe=987feed95d) | Feb 04, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [5828b467b9](https://linux-hardware.org/?probe=5828b467b9) | Feb 04, 2022 |
| Dell          | XPS 15 9500                 | [748e3fae6c](https://linux-hardware.org/?probe=748e3fae6c) | Feb 04, 2022 |
| Dell          | Latitude 9420               | [8ba5ead5e5](https://linux-hardware.org/?probe=8ba5ead5e5) | Feb 03, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| Intel Clie... | LAPBC710                    | [76dff27038](https://linux-hardware.org/?probe=76dff27038) | Feb 02, 2022 |
| Intel Clie... | LAPBC710                    | [a4c71279a4](https://linux-hardware.org/?probe=a4c71279a4) | Feb 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [a6bc5bb673](https://linux-hardware.org/?probe=a6bc5bb673) | Feb 01, 2022 |
| HP            | OMEN by Laptop              | [196508f0aa](https://linux-hardware.org/?probe=196508f0aa) | Feb 01, 2022 |
| Lenovo        | ThinkPad W520 427637U       | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | [8583114e36](https://linux-hardware.org/?probe=8583114e36) | Feb 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | [8d0b4e7b64](https://linux-hardware.org/?probe=8d0b4e7b64) | Feb 01, 2022 |
| HP            | Grunt                       | [315d957271](https://linux-hardware.org/?probe=315d957271) | Feb 01, 2022 |
| HP            | Grunt                       | [e95882e549](https://linux-hardware.org/?probe=e95882e549) | Jan 31, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [dccef6f0ca](https://linux-hardware.org/?probe=dccef6f0ca) | Jan 30, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e41e701a15](https://linux-hardware.org/?probe=e41e701a15) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [2248ba47d2](https://linux-hardware.org/?probe=2248ba47d2) | Jan 30, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [74eb47cb2f](https://linux-hardware.org/?probe=74eb47cb2f) | Jan 30, 2022 |
| HP            | OMEN by Laptop              | [67f194f1e2](https://linux-hardware.org/?probe=67f194f1e2) | Jan 29, 2022 |
| Apple         | MacBook3,1                  | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [7697915441](https://linux-hardware.org/?probe=7697915441) | Jan 29, 2022 |
| HP            | ProBook 4720s               | [c17f5dcf26](https://linux-hardware.org/?probe=c17f5dcf26) | Jan 29, 2022 |
| GPD           | G1621-02                    | [7bc0adb6d3](https://linux-hardware.org/?probe=7bc0adb6d3) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f653016830](https://linux-hardware.org/?probe=f653016830) | Jan 28, 2022 |
| TUXEDO        | Book XP1511                 | [12a1ab9ddb](https://linux-hardware.org/?probe=12a1ab9ddb) | Jan 27, 2022 |
| Fujitsu       | LIFEBOOK A530               | [bda3f36826](https://linux-hardware.org/?probe=bda3f36826) | Jan 27, 2022 |
| HP            | Pavilion dv5                | [1fbb598e3a](https://linux-hardware.org/?probe=1fbb598e3a) | Jan 27, 2022 |
| Positivo B... | VJFE43F11X-XXXXXX           | [ef86245dd3](https://linux-hardware.org/?probe=ef86245dd3) | Jan 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [56ce398ad8](https://linux-hardware.org/?probe=56ce398ad8) | Jan 25, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [1816cd81d3](https://linux-hardware.org/?probe=1816cd81d3) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [510e973c9d](https://linux-hardware.org/?probe=510e973c9d) | Jan 25, 2022 |

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
| Manjaro        | 1207      | 36.01%  |
| Manjaro 20.2.1 | 163       | 4.86%   |
| Manjaro 20.1   | 142       | 4.24%   |
| Manjaro 20.2   | 140       | 4.18%   |
| Manjaro 20.0.3 | 125       | 3.73%   |
| Manjaro 21.2.6 | 113       | 3.37%   |
| Manjaro 21.1.0 | 89        | 2.66%   |
| Manjaro 18.1.5 | 83        | 2.48%   |
| Manjaro 21.2.0 | 72        | 2.15%   |
| Manjaro 21.0.7 | 69        | 2.06%   |
| Manjaro 21.2.5 | 65        | 1.94%   |
| Manjaro 21.1.6 | 63        | 1.88%   |
| Manjaro 19.0.2 | 55        | 1.64%   |
| Manjaro 20.0   | 52        | 1.55%   |
| Manjaro 21.2.1 | 48        | 1.43%   |
| Manjaro 18.0.4 | 47        | 1.4%    |
| Manjaro 21.0   | 46        | 1.37%   |
| Manjaro 21.0.5 | 44        | 1.31%   |
| Manjaro 20.1.1 | 41        | 1.22%   |
| Manjaro 20.1.2 | 40        | 1.19%   |
| Manjaro 21.2.3 | 37        | 1.1%    |
| Manjaro 22.0.0 | 36        | 1.07%   |
| Manjaro 20.0.1 | 36        | 1.07%   |
| Manjaro 21.2.2 | 31        | 0.92%   |
| Manjaro 21.0.4 | 31        | 0.92%   |
| Manjaro 21.3.7 | 30        | 0.89%   |
| Manjaro 21.3.6 | 29        | 0.87%   |
| Manjaro 21.2.4 | 29        | 0.87%   |
| Manjaro 21.1.2 | 25        | 0.75%   |
| Manjaro 21.1.4 | 24        | 0.72%   |
| Manjaro 21.0.1 | 20        | 0.6%    |
| Manjaro 18.1.4 | 20        | 0.6%    |
| Manjaro 21.3.1 | 19        | 0.57%   |
| Manjaro 21.3.0 | 19        | 0.57%   |
| Manjaro 21.1.3 | 19        | 0.57%   |
| Manjaro 21.1.1 | 19        | 0.57%   |
| Manjaro 21.0.2 | 17        | 0.51%   |
| Manjaro 21.0.3 | 16        | 0.48%   |
| Manjaro 21.3.2 | 15        | 0.45%   |
| Manjaro 18.1.0 | 15        | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Manjaro | 3087      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 161       | 4.48%   |
| 5.13.19-2-MANJARO | 95        | 2.65%   |
| 5.9.11-3-MANJARO  | 74        | 2.06%   |
| 5.8.11-1-MANJARO  | 69        | 1.92%   |
| 5.8.6-1-MANJARO   | 68        | 1.89%   |
| 5.15.32-1-MANJARO | 63        | 1.75%   |
| 5.15.28-1-MANJARO | 61        | 1.7%    |
| 5.10.42-1-MANJARO | 56        | 1.56%   |
| 5.8.18-1-MANJARO  | 55        | 1.53%   |
| 5.15.12-1-MANJARO | 52        | 1.45%   |
| 5.8.16-2-MANJARO  | 41        | 1.14%   |
| 5.10.2-2-MANJARO  | 40        | 1.11%   |
| 5.6.16-1-MANJARO  | 39        | 1.09%   |
| 5.10.7-3-MANJARO  | 38        | 1.06%   |
| 5.12.9-1-MANJARO  | 36        | 1%      |
| 5.6.19-2-MANJARO  | 33        | 0.92%   |
| 5.15.60-1-MANJARO | 32        | 0.89%   |
| 5.15.7-1-MANJARO  | 31        | 0.86%   |
| 5.7.9-1-MANJARO   | 30        | 0.84%   |
| 5.6.15-1-MANJARO  | 30        | 0.84%   |
| 5.15.41-1-MANJARO | 30        | 0.84%   |
| 5.10.36-2-MANJARO | 30        | 0.84%   |
| 5.7.17-2-MANJARO  | 29        | 0.81%   |
| 5.7.0-3-MANJARO   | 29        | 0.81%   |
| 5.8.3-2-MANJARO   | 28        | 0.78%   |
| 5.15.25-1-MANJARO | 28        | 0.78%   |
| 5.14.10-1-MANJARO | 28        | 0.78%   |
| 5.15.65-1-MANJARO | 27        | 0.75%   |
| 5.10.34-1-MANJARO | 27        | 0.75%   |
| 5.16.14-1-MANJARO | 25        | 0.7%    |
| 5.10.70-1-MANJARO | 25        | 0.7%    |
| 5.10.53-1-MANJARO | 25        | 0.7%    |
| 5.9.3-1-MANJARO   | 23        | 0.64%   |
| 5.17.1-3-MANJARO  | 23        | 0.64%   |
| 5.15.38-1-MANJARO | 23        | 0.64%   |
| 5.4.6-2-MANJARO   | 22        | 0.61%   |
| 5.15.21-1-MANJARO | 22        | 0.61%   |
| 5.11.6-1-MANJARO  | 22        | 0.61%   |
| 5.10.23-1-MANJARO | 22        | 0.61%   |
| 5.9.1-1-MANJARO   | 21        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.16  | 161       | 4.49%   |
| 5.13.19 | 96        | 2.68%   |
| 5.9.11  | 78        | 2.17%   |
| 5.8.11  | 69        | 1.92%   |
| 5.8.6   | 68        | 1.9%    |
| 5.15.32 | 64        | 1.78%   |
| 5.15.28 | 61        | 1.7%    |
| 5.10.42 | 56        | 1.56%   |
| 5.8.18  | 55        | 1.53%   |
| 5.15.12 | 52        | 1.45%   |
| 5.8.16  | 42        | 1.17%   |
| 5.10.2  | 40        | 1.11%   |
| 5.6.16  | 39        | 1.09%   |
| 5.10.7  | 39        | 1.09%   |
| 5.7.0   | 36        | 1%      |
| 5.12.9  | 36        | 1%      |
| 5.6.19  | 35        | 0.98%   |
| 5.9.1   | 33        | 0.92%   |
| 5.15.7  | 32        | 0.89%   |
| 5.15.60 | 32        | 0.89%   |
| 5.7.9   | 30        | 0.84%   |
| 5.6.15  | 30        | 0.84%   |
| 5.17.1  | 30        | 0.84%   |
| 5.15.41 | 30        | 0.84%   |
| 5.10.36 | 30        | 0.84%   |
| 5.7.17  | 29        | 0.81%   |
| 5.8.3   | 28        | 0.78%   |
| 5.15.25 | 28        | 0.78%   |
| 5.14.10 | 28        | 0.78%   |
| 5.15.65 | 27        | 0.75%   |
| 5.10.34 | 27        | 0.75%   |
| 5.16.14 | 25        | 0.7%    |
| 5.10.70 | 25        | 0.7%    |
| 5.10.53 | 25        | 0.7%    |
| 5.9.3   | 24        | 0.67%   |
| 5.15.38 | 23        | 0.64%   |
| 5.15.21 | 23        | 0.64%   |
| 5.11.6  | 23        | 0.64%   |
| 5.4.6   | 22        | 0.61%   |
| 5.19.0  | 22        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 517       | 15.18%  |
| 5.10    | 494       | 14.51%  |
| 5.4     | 353       | 10.37%  |
| 5.9     | 323       | 9.49%   |
| 5.8     | 291       | 8.55%   |
| 5.13    | 204       | 5.99%   |
| 5.6     | 199       | 5.84%   |
| 5.7     | 137       | 4.02%   |
| 4.19    | 120       | 3.52%   |
| 5.16    | 99        | 2.91%   |
| 5.12    | 94        | 2.76%   |
| 5.11    | 80        | 2.35%   |
| 5.14    | 73        | 2.14%   |
| 5.17    | 70        | 2.06%   |
| 5.18    | 68        | 2%      |
| 5.3     | 64        | 1.88%   |
| 5.5     | 62        | 1.82%   |
| 5.19    | 54        | 1.59%   |
| 4.14    | 25        | 0.73%   |
| 5.2     | 23        | 0.68%   |
| 5.0     | 17        | 0.5%    |
| 5.1     | 13        | 0.38%   |
| 4.20    | 9         | 0.26%   |
| 4.18    | 7         | 0.21%   |
| 6.0     | 6         | 0.18%   |
| 4.9     | 2         | 0.06%   |
| 4.16    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3085      | 99.94%  |
| i686   | 2         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| KDE5                 | 1010      | 31.81%  |
| XFCE                 | 746       | 23.5%   |
| GNOME                | 680       | 21.42%  |
| KDE                  | 268       | 8.44%   |
| Unknown              | 184       | 5.8%    |
| i3                   | 71        | 2.24%   |
| X-Cinnamon           | 69        | 2.17%   |
| MATE                 | 33        | 1.04%   |
| Cinnamon             | 30        | 0.94%   |
| Deepin               | 23        | 0.72%   |
| Budgie               | 13        | 0.41%   |
| awesome              | 11        | 0.35%   |
| LXQt                 | 7         | 0.22%   |
| sway                 | 6         | 0.19%   |
| LXDE                 | 6         | 0.19%   |
| leftwm               | 2         | 0.06%   |
| i3-with-shmlog       | 2         | 0.06%   |
| GNOME Flashback      | 2         | 0.06%   |
| DWM                  | 2         | 0.06%   |
| Bspwm                | 2         | 0.06%   |
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
| X11     | 2637      | 84.3%   |
| Wayland | 389       | 12.44%  |
| Unknown | 79        | 2.53%   |
| Tty     | 23        | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1196      | 37.85%  |
| SDDM    | 800       | 25.32%  |
| LightDM | 589       | 18.64%  |
| GDM     | 440       | 13.92%  |
| TDM     | 123       | 3.89%   |
| LXDM    | 5         | 0.16%   |
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
| en_US   | 1335      | 42.73%  |
| Unknown | 234       | 7.49%   |
| de_DE   | 226       | 7.23%   |
| ru_RU   | 222       | 7.11%   |
| en_GB   | 198       | 6.34%   |
| pt_BR   | 124       | 3.97%   |
| fr_FR   | 81        | 2.59%   |
| es_ES   | 58        | 1.86%   |
| en_CA   | 57        | 1.82%   |
| it_IT   | 56        | 1.79%   |
| pl_PL   | 54        | 1.73%   |
| en_IN   | 47        | 1.5%    |
| en_AU   | 33        | 1.06%   |
| es_MX   | 31        | 0.99%   |
| zh_CN   | 24        | 0.77%   |
| ru_UA   | 20        | 0.64%   |
| de_AT   | 17        | 0.54%   |
| en_IE   | 14        | 0.45%   |
| C       | 13        | 0.42%   |
| pt_PT   | 12        | 0.38%   |
| es_AR   | 12        | 0.38%   |
| tr_TR   | 11        | 0.35%   |
| nl_NL   | 11        | 0.35%   |
| en_DK   | 11        | 0.35%   |
| uk_UA   | 10        | 0.32%   |
| en_ZA   | 10        | 0.32%   |
| cs_CZ   | 10        | 0.32%   |
| sv_SE   | 9         | 0.29%   |
| es_CO   | 9         | 0.29%   |
| nl_BE   | 8         | 0.26%   |
| hu_HU   | 8         | 0.26%   |
| es_CL   | 8         | 0.26%   |
| en_NZ   | 8         | 0.26%   |
| fi_FI   | 7         | 0.22%   |
| en_PH   | 7         | 0.22%   |
| el_GR   | 7         | 0.22%   |
| de_CH   | 7         | 0.22%   |
| zh_TW   | 6         | 0.19%   |
| en_IL   | 6         | 0.19%   |
| en_DE   | 6         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1584      | 50.53%  |
| EFI  | 1551      | 49.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 2638      | 84.85%  |
| Btrfs    | 252       | 8.11%   |
| Unknown  | 82        | 2.64%   |
| Overlay  | 79        | 2.54%   |
| Xfs      | 31        | 1%      |
| F2fs     | 10        | 0.32%   |
| Tmpfs    | 9         | 0.29%   |
| Reiserfs | 3         | 0.1%    |
| Ext3     | 3         | 0.1%    |
| Jfs      | 1         | 0.03%   |
| Ext2     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1505      | 48.05%  |
| Unknown | 1345      | 42.94%  |
| MBR     | 282       | 9%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2795      | 89.53%  |
| Yes       | 327       | 10.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2189      | 69.87%  |
| Yes       | 944       | 30.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 786       | 25.46%  |
| Hewlett-Packard      | 526       | 17.04%  |
| Dell                 | 466       | 15.1%   |
| ASUSTek Computer     | 391       | 12.67%  |
| Acer                 | 242       | 7.84%   |
| MSI                  | 86        | 2.79%   |
| Apple                | 76        | 2.46%   |
| Toshiba              | 54        | 1.75%   |
| Samsung Electronics  | 54        | 1.75%   |
| HUAWEI               | 48        | 1.55%   |
| Timi                 | 35        | 1.13%   |
| Notebook             | 28        | 0.91%   |
| Sony                 | 27        | 0.87%   |
| Fujitsu              | 24        | 0.78%   |
| Google               | 21        | 0.68%   |
| Unknown              | 14        | 0.45%   |
| TUXEDO               | 12        | 0.39%   |
| Razer                | 12        | 0.39%   |
| Alienware            | 11        | 0.36%   |
| Schenker             | 10        | 0.32%   |
| Packard Bell         | 9         | 0.29%   |
| LG Electronics       | 8         | 0.26%   |
| Panasonic            | 7         | 0.23%   |
| Gigabyte Technology  | 7         | 0.23%   |
| System76             | 6         | 0.19%   |
| Monster              | 6         | 0.19%   |
| HONOR                | 6         | 0.19%   |
| Clevo                | 6         | 0.19%   |
| Positivo             | 5         | 0.16%   |
| Multilaser           | 5         | 0.16%   |
| Chuwi                | 5         | 0.16%   |
| PC Specialist        | 4         | 0.13%   |
| Medion               | 4         | 0.13%   |
| Intel Client Systems | 4         | 0.13%   |
| TrekStor             | 3         | 0.1%    |
| Star Labs            | 3         | 0.1%    |
| GPD                  | 3         | 0.1%    |
| Gateway              | 3         | 0.1%    |
| Wortmann AG          | 2         | 0.06%   |
| UNOWHY               | 2         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 24        | 0.78%   |
| HP Notebook                          | 20        | 0.65%   |
| Lenovo Legion 5 15ARH05 82B5         | 13        | 0.42%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 12        | 0.39%   |
| Dell XPS 13 9310                     | 12        | 0.39%   |
| Dell XPS 15 9500                     | 11        | 0.36%   |
| HP Pavilion Notebook                 | 10        | 0.32%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 10        | 0.32%   |
| HP Laptop 15-bs0xx                   | 10        | 0.32%   |
| HP Pavilion dv7                      | 9         | 0.29%   |
| Dell XPS 15 9560                     | 9         | 0.29%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 8         | 0.26%   |
| HP Pavilion 15                       | 8         | 0.26%   |
| HP 15                                | 8         | 0.26%   |
| Dell XPS 15 9570                     | 8         | 0.26%   |
| Dell XPS 13 7390                     | 8         | 0.26%   |
| Dell Inspiron 3542                   | 8         | 0.26%   |
| Timi TM1701                          | 7         | 0.23%   |
| Lenovo Z50-70 20354                  | 7         | 0.23%   |
| Lenovo Y520-15IKBN 80WK              | 7         | 0.23%   |
| HP Pavilion g6                       | 7         | 0.23%   |
| HP Pavilion dv6                      | 7         | 0.23%   |
| HP OMEN by Laptop                    | 7         | 0.23%   |
| Dell XPS 15 7590                     | 7         | 0.23%   |
| Dell Latitude E6430                  | 7         | 0.23%   |
| Apple MacBookPro9,2                  | 7         | 0.23%   |
| Apple MacBookPro15,1                 | 7         | 0.23%   |
| Acer Swift SF314-42                  | 7         | 0.23%   |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 6         | 0.19%   |
| Lenovo ThinkBook 15-IIL 20SM         | 6         | 0.19%   |
| Lenovo IdeaPad S540-14API 81NH       | 6         | 0.19%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 6         | 0.19%   |
| Lenovo G580 20150                    | 6         | 0.19%   |
| HUAWEI BOHK-WAX9X                    | 6         | 0.19%   |
| HP Laptop 15-bw0xx                   | 6         | 0.19%   |
| HP 250 G7 Notebook PC                | 6         | 0.19%   |
| Dell Latitude E7240                  | 6         | 0.19%   |
| Dell Latitude E5530 non-vPro         | 6         | 0.19%   |
| Dell Latitude 5480                   | 6         | 0.19%   |
| Dell Inspiron N5110                  | 6         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 355       | 11.5%   |
| Lenovo IdeaPad        | 219       | 7.09%   |
| Dell Inspiron         | 158       | 5.12%   |
| Acer Aspire           | 157       | 5.09%   |
| HP Pavilion           | 123       | 3.98%   |
| Dell Latitude         | 122       | 3.95%   |
| Dell XPS              | 86        | 2.79%   |
| HP ProBook            | 81        | 2.62%   |
| HP Laptop             | 79        | 2.56%   |
| HP EliteBook          | 76        | 2.46%   |
| ASUS VivoBook         | 57        | 1.85%   |
| Lenovo Legion         | 56        | 1.81%   |
| Toshiba Satellite     | 50        | 1.62%   |
| ASUS ROG              | 44        | 1.43%   |
| Dell Precision        | 33        | 1.07%   |
| Dell Vostro           | 32        | 1.04%   |
| ASUS TUF              | 31        | 1%      |
| Acer Swift            | 31        | 1%      |
| ASUS ZenBook          | 29        | 0.94%   |
| Unknown               | 24        | 0.78%   |
| Lenovo ThinkBook      | 23        | 0.75%   |
| HP ENVY               | 23        | 0.75%   |
| Acer Nitro            | 23        | 0.75%   |
| HP OMEN               | 20        | 0.65%   |
| HP Notebook           | 20        | 0.65%   |
| Fujitsu LIFEBOOK      | 20        | 0.65%   |
| ASUS ASUS             | 19        | 0.62%   |
| HP ZBook              | 18        | 0.58%   |
| Timi RedmiBook        | 16        | 0.52%   |
| Lenovo Yoga           | 16        | 0.52%   |
| HP 250                | 16        | 0.52%   |
| Dell G3               | 14        | 0.45%   |
| HP Compaq             | 12        | 0.39%   |
| HP 15                 | 12        | 0.39%   |
| Razer Blade           | 11        | 0.36%   |
| HP 255                | 11        | 0.36%   |
| Acer TravelMate       | 11        | 0.36%   |
| Apple MacBookPro11    | 10        | 0.32%   |
| Packard Bell EasyNote | 9         | 0.29%   |
| Apple MacBookPro9     | 8         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 428       | 13.86%  |
| 2020    | 416       | 13.48%  |
| 2018    | 347       | 11.24%  |
| 2017    | 255       | 8.26%   |
| 2021    | 237       | 7.68%   |
| 2012    | 233       | 7.55%   |
| 2015    | 193       | 6.25%   |
| 2013    | 186       | 6.03%   |
| 2014    | 177       | 5.73%   |
| 2016    | 172       | 5.57%   |
| 2011    | 172       | 5.57%   |
| 2010    | 100       | 3.24%   |
| 2008    | 63        | 2.04%   |
| 2009    | 47        | 1.52%   |
| 2007    | 26        | 0.84%   |
| 2022    | 24        | 0.78%   |
| 2006    | 7         | 0.23%   |
| Unknown | 3         | 0.1%    |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3087      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3085      | 99.87%  |
| Enabled  | 4         | 0.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3049      | 98.77%  |
| Yes  | 38        | 1.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 960       | 30.73%  |
| 16.01-24.0  | 671       | 21.48%  |
| 8.01-16.0   | 649       | 20.77%  |
| 3.01-4.0    | 460       | 14.72%  |
| 32.01-64.0  | 213       | 6.82%   |
| 1.01-2.0    | 66        | 2.11%   |
| 24.01-32.0  | 47        | 1.5%    |
| 64.01-256.0 | 31        | 0.99%   |
| 2.01-3.0    | 26        | 0.83%   |
| 0.51-1.0    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 944       | 27.88%  |
| 1.01-2.0   | 931       | 27.5%   |
| 4.01-8.0   | 620       | 18.31%  |
| 3.01-4.0   | 578       | 17.07%  |
| 8.01-16.0  | 163       | 4.81%   |
| 0.51-1.0   | 127       | 3.75%   |
| 16.01-24.0 | 12        | 0.35%   |
| 0.01-0.5   | 6         | 0.18%   |
| 24.01-32.0 | 4         | 0.12%   |
| 32.01-64.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2106      | 67.01%  |
| 2      | 895       | 28.48%  |
| 3      | 112       | 3.56%   |
| 0      | 18        | 0.57%   |
| 4      | 10        | 0.32%   |
| 7      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2261      | 72.86%  |
| Yes       | 842       | 27.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2395      | 77.33%  |
| No        | 702       | 22.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3051      | 98.74%  |
| No        | 39        | 1.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2513      | 80.91%  |
| No        | 593       | 19.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 455       | 14.66%  |
| Germany      | 331       | 10.66%  |
| Russia       | 292       | 9.41%   |
| Brazil       | 188       | 6.06%   |
| France       | 114       | 3.67%   |
| UK           | 110       | 3.54%   |
| Poland       | 96        | 3.09%   |
| Italy        | 93        | 3%      |
| Canada       | 88        | 2.84%   |
| Ukraine      | 87        | 2.8%    |
| Spain        | 82        | 2.64%   |
| India        | 80        | 2.58%   |
| Netherlands  | 69        | 2.22%   |
| Mexico       | 54        | 1.74%   |
| Austria      | 44        | 1.42%   |
| China        | 42        | 1.35%   |
| Turkey       | 39        | 1.26%   |
| Australia    | 39        | 1.26%   |
| Sweden       | 34        | 1.1%    |
| Indonesia    | 32        | 1.03%   |
| Romania      | 31        | 1%      |
| Portugal     | 29        | 0.93%   |
| Belgium      | 29        | 0.93%   |
| Switzerland  | 27        | 0.87%   |
| Czechia      | 27        | 0.87%   |
| Belarus      | 25        | 0.81%   |
| Norway       | 23        | 0.74%   |
| Hungary      | 21        | 0.68%   |
| Finland      | 21        | 0.68%   |
| Greece       | 20        | 0.64%   |
| Colombia     | 20        | 0.64%   |
| Taiwan       | 19        | 0.61%   |
| Bulgaria     | 18        | 0.58%   |
| Iran         | 17        | 0.55%   |
| Denmark      | 17        | 0.55%   |
| Bangladesh   | 17        | 0.55%   |
| Argentina    | 16        | 0.52%   |
| South Africa | 13        | 0.42%   |
| Croatia      | 13        | 0.42%   |
| Vietnam      | 12        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 64        | 1.97%   |
| St Petersburg     | 41        | 1.26%   |
| Vienna            | 31        | 0.95%   |
| Paris             | 27        | 0.83%   |
| Kyiv              | 24        | 0.74%   |
| Berlin            | 24        | 0.74%   |
| Sao Paulo         | 23        | 0.71%   |
| Warsaw            | 17        | 0.52%   |
| Munich            | 17        | 0.52%   |
| Amsterdam         | 17        | 0.52%   |
| Novosibirsk       | 15        | 0.46%   |
| Minsk             | 15        | 0.46%   |
| Milan             | 14        | 0.43%   |
| Bengaluru         | 14        | 0.43%   |
| Toronto           | 13        | 0.4%    |
| Istanbul          | 13        | 0.4%    |
| Frankfurt am Main | 13        | 0.4%    |
| Barcelona         | 13        | 0.4%    |
| Rome              | 12        | 0.37%   |
| Prague            | 12        | 0.37%   |
| Helsinki          | 12        | 0.37%   |
| Hamburg           | 12        | 0.37%   |
| Yekaterinburg     | 11        | 0.34%   |
| Madrid            | 11        | 0.34%   |
| London            | 11        | 0.34%   |
| Dhaka             | 11        | 0.34%   |
| Bucharest         | 11        | 0.34%   |
| Stockholm         | 10        | 0.31%   |
| Sofia             | 10        | 0.31%   |
| Mexico City       | 10        | 0.31%   |
| Melbourne         | 10        | 0.31%   |
| Krakow            | 10        | 0.31%   |
| Cologne           | 10        | 0.31%   |
| Budapest          | 10        | 0.31%   |
| Belo Horizonte    | 10        | 0.31%   |
| Zagreb            | 9         | 0.28%   |
| The Hague         | 9         | 0.28%   |
| Sydney            | 9         | 0.28%   |
| Seattle           | 9         | 0.28%   |
| Denver            | 9         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 698       | 920    | 17.17%  |
| WDC                            | 471       | 562    | 11.59%  |
| Seagate                        | 426       | 550    | 10.48%  |
| Toshiba                        | 322       | 373    | 7.92%   |
| SanDisk                        | 247       | 315    | 6.08%   |
| Kingston                       | 232       | 264    | 5.71%   |
| Unknown                        | 208       | 248    | 5.12%   |
| SK hynix                       | 201       | 239    | 4.94%   |
| Intel                          | 141       | 175    | 3.47%   |
| Crucial                        | 140       | 172    | 3.44%   |
| HGST                           | 130       | 155    | 3.2%    |
| Micron Technology              | 102       | 127    | 2.51%   |
| Hitachi                        | 84        | 98     | 2.07%   |
| A-DATA Technology              | 52        | 61     | 1.28%   |
| Apple                          | 47        | 54     | 1.16%   |
| KIOXIA                         | 46        | 51     | 1.13%   |
| Phison                         | 42        | 60     | 1.03%   |
| China                          | 31        | 34     | 0.76%   |
| Transcend                      | 28        | 33     | 0.69%   |
| LITEONIT                       | 25        | 28     | 0.62%   |
| GOODRAM                        | 23        | 39     | 0.57%   |
| LITEON                         | 22        | 25     | 0.54%   |
| JMicron Technology             | 18        | 18     | 0.44%   |
| Silicon Motion                 | 16        | 19     | 0.39%   |
| Plextor                        | 13        | 21     | 0.32%   |
| Micron/Crucial Technology      | 13        | 15     | 0.32%   |
| Patriot                        | 11        | 11     | 0.27%   |
| Union Memory (Shenzhen)        | 10        | 10     | 0.25%   |
| SPCC                           | 10        | 12     | 0.25%   |
| Intenso                        | 10        | 10     | 0.25%   |
| Fujitsu                        | 10        | 10     | 0.25%   |
| XPG                            | 9         | 15     | 0.22%   |
| Solid State Storage Technology | 8         | 15     | 0.2%    |
| PNY                            | 8         | 11     | 0.2%    |
| Hewlett-Packard                | 8         | 11     | 0.2%    |
| Corsair                        | 8         | 8      | 0.2%    |
| OCZ                            | 7         | 8      | 0.17%   |
| KingSpec                       | 7         | 7      | 0.17%   |
| Lite-On                        | 6         | 6      | 0.15%   |
| ADATA Technology               | 6         | 7      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 85        | 2.01%   |
| Samsung NVMe SSD Drive 512GB        | 64        | 1.51%   |
| Toshiba MQ01ABD100 1TB              | 46        | 1.09%   |
| SK hynix NVMe SSD Drive 512GB       | 46        | 1.09%   |
| Toshiba MQ04ABF100 1TB              | 44        | 1.04%   |
| HGST HTS721010A9E630 1TB            | 44        | 1.04%   |
| SanDisk NVMe SSD Drive 512GB        | 43        | 1.02%   |
| Samsung NVMe SSD Drive 256GB        | 43        | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 39        | 0.92%   |
| Kingston SA400S37240G 240GB SSD     | 37        | 0.88%   |
| Toshiba MQ01ABF050 500GB            | 35        | 0.83%   |
| Intel NVMe SSD Drive 512GB          | 30        | 0.71%   |
| Samsung NVMe SSD Drive 1TB          | 29        | 0.69%   |
| Unknown SD/MMC/MS PRO 2GB           | 27        | 0.64%   |
| Unknown MMC Card  32GB              | 26        | 0.61%   |
| SanDisk NVMe SSD Drive 256GB        | 26        | 0.61%   |
| Unknown MMC Card  64GB              | 24        | 0.57%   |
| Seagate ST500LT012-1DG142 500GB     | 23        | 0.54%   |
| Samsung NVMe SSD Drive 1024GB       | 23        | 0.54%   |
| Kingston SA400S37120G 120GB SSD     | 23        | 0.54%   |
| Crucial CT500MX500SSD1 500GB        | 23        | 0.54%   |
| SK hynix NVMe SSD Drive 256GB       | 22        | 0.52%   |
| Seagate ST1000LM049-2GH172 1TB      | 22        | 0.52%   |
| Samsung SSD 860 EVO 500GB           | 22        | 0.52%   |
| HGST HTS545050A7E680 500GB          | 22        | 0.52%   |
| Samsung SSD 850 EVO 500GB           | 21        | 0.5%    |
| Seagate Expansion 1TB               | 20        | 0.47%   |
| SanDisk NVMe SSD Drive 1TB          | 19        | 0.45%   |
| Micron NVMe SSD Drive 512GB         | 19        | 0.45%   |
| Kingston NVMe SSD Drive 512GB       | 19        | 0.45%   |
| WDC WD10SPZX-21Z10T0 1TB            | 18        | 0.43%   |
| Toshiba NVMe SSD Drive 512GB        | 18        | 0.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 18        | 0.43%   |
| Kingston SA400S37480G 480GB SSD     | 18        | 0.43%   |
| Intel SSDPEKNW512G8 512GB           | 18        | 0.43%   |
| WDC WD10SPZX-24Z10 1TB              | 17        | 0.4%    |
| Samsung SSD 860 EVO 250GB           | 17        | 0.4%    |
| Samsung NVMe SSD Drive 500GB        | 17        | 0.4%    |
| Toshiba NVMe SSD Drive 256GB        | 16        | 0.38%   |
| Crucial CT240BX500SSD1 240GB        | 16        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 417       | 533    | 34.66%  |
| WDC                 | 295       | 344    | 24.52%  |
| Toshiba             | 209       | 239    | 17.37%  |
| HGST                | 130       | 155    | 10.81%  |
| Hitachi             | 84        | 98     | 6.98%   |
| Unknown             | 28        | 31     | 2.33%   |
| Samsung Electronics | 13        | 15     | 1.08%   |
| Fujitsu             | 10        | 10     | 0.83%   |
| Apple               | 5         | 6      | 0.42%   |
| Intenso             | 2         | 2      | 0.17%   |
| USB3.0              | 1         | 1      | 0.08%   |
| QNAP                | 1         | 1      | 0.08%   |
| PHD 3.0             | 1         | 1      | 0.08%   |
| KESU                | 1         | 1      | 0.08%   |
| Inateck             | 1         | 1      | 0.08%   |
| Hewlett-Packard     | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |
| Apricorn            | 1         | 1      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 302       | 381    | 23.47%  |
| Kingston            | 171       | 192    | 13.29%  |
| Crucial             | 127       | 159    | 9.87%   |
| SanDisk             | 109       | 143    | 8.47%   |
| WDC                 | 80        | 96     | 6.22%   |
| Micron Technology   | 48        | 60     | 3.73%   |
| A-DATA Technology   | 37        | 41     | 2.87%   |
| Intel               | 36        | 42     | 2.8%    |
| SK hynix            | 34        | 42     | 2.64%   |
| China               | 31        | 34     | 2.41%   |
| Apple               | 30        | 34     | 2.33%   |
| Toshiba             | 28        | 28     | 2.18%   |
| Transcend           | 27        | 31     | 2.1%    |
| LITEONIT            | 25        | 28     | 1.94%   |
| GOODRAM             | 22        | 38     | 1.71%   |
| LITEON              | 19        | 22     | 1.48%   |
| Plextor             | 12        | 20     | 0.93%   |
| Patriot             | 10        | 10     | 0.78%   |
| Intenso             | 8         | 8      | 0.62%   |
| PNY                 | 7         | 10     | 0.54%   |
| OCZ                 | 7         | 8      | 0.54%   |
| KingSpec            | 7         | 7      | 0.54%   |
| Seagate             | 6         | 10     | 0.47%   |
| SPCC                | 5         | 6      | 0.39%   |
| Hewlett-Packard     | 5         | 7      | 0.39%   |
| Corsair             | 5         | 5      | 0.39%   |
| TO Exter            | 4         | 5      | 0.31%   |
| Apacer              | 4         | 4      | 0.31%   |
| Team                | 3         | 4      | 0.23%   |
| Netac               | 3         | 8      | 0.23%   |
| Lexar               | 3         | 3      | 0.23%   |
| FORESEE             | 3         | 3      | 0.23%   |
| Vaseky              | 2         | 2      | 0.16%   |
| Unknown             | 2         | 3      | 0.16%   |
| TwinMOS             | 2         | 2      | 0.16%   |
| OWC                 | 2         | 4      | 0.16%   |
| NGFF                | 2         | 2      | 0.16%   |
| Mushkin             | 2         | 3      | 0.16%   |
| Londisk             | 2         | 2      | 0.16%   |
| Leven               | 2         | 3      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1276      | 1714   | 33.02%  |
| SSD     | 1212      | 1577   | 31.37%  |
| HDD     | 1154      | 1443   | 29.87%  |
| MMC     | 171       | 212    | 4.43%   |
| Unknown | 51        | 55     | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2027      | 2890   | 55.82%  |
| NVMe | 1273      | 1698   | 35.06%  |
| MMC  | 171       | 212    | 4.71%   |
| SAS  | 160       | 201    | 4.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1438      | 1912   | 62.04%  |
| 0.51-1.0   | 792       | 982    | 34.17%  |
| 1.01-2.0   | 77        | 102    | 3.32%   |
| 4.01-10.0  | 6         | 7      | 0.26%   |
| 3.01-4.0   | 5         | 17     | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 887       | 27.74%  |
| 251-500        | 811       | 25.37%  |
| 501-1000       | 505       | 15.8%   |
| 1001-2000      | 249       | 7.79%   |
| 51-100         | 213       | 6.66%   |
| Unknown        | 212       | 6.63%   |
| 1-20           | 118       | 3.69%   |
| 21-50          | 103       | 3.22%   |
| 2001-3000      | 50        | 1.56%   |
| More than 3000 | 49        | 1.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 808       | 24.29%  |
| 21-50          | 628       | 18.88%  |
| 101-250        | 565       | 16.99%  |
| 51-100         | 505       | 15.18%  |
| 251-500        | 342       | 10.28%  |
| Unknown        | 212       | 6.37%   |
| 501-1000       | 181       | 5.44%   |
| 1001-2000      | 58        | 1.74%   |
| More than 3000 | 14        | 0.42%   |
| 2001-3000      | 11        | 0.33%   |
| 0              | 2         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 11     | 5.13%   |
| HGST HTS545050A7E680 500GB                          | 8         | 8      | 4.1%    |
| HGST HTS721010A9E630 1TB                            | 7         | 7      | 3.59%   |
| HGST HTS545050A7E380 500GB                          | 6         | 6      | 3.08%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 7      | 2.56%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 20     | 2.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 5      | 2.56%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 2.05%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 1.54%   |
| Toshiba MQ01ABD050 500GB                            | 3         | 3      | 1.54%   |
| Seagate ST9320325AS 320GB                           | 3         | 4      | 1.54%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 1.54%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 1.54%   |
| Hitachi HTS723232A7A364 320GB                       | 3         | 3      | 1.54%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 1.54%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 3      | 1.03%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 2         | 2      | 1.03%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 1.03%   |
| Seagate ST9750420AS 752GB                           | 2         | 2      | 1.03%   |
| Seagate ST9500325AS 500GB                           | 2         | 3      | 1.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 2      | 1.03%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 5      | 1.03%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 2      | 1.03%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 2      | 1.03%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 1.03%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 1.03%   |
| Crucial CT525MX300SSD1 528GB                        | 2         | 2      | 1.03%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 0.51%   |
| WDC WD800BEVS-22RST0 80GB                           | 1         | 1      | 0.51%   |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 1      | 0.51%   |
| WDC WD5000LPVX-08V0TT5 500GB                        | 1         | 1      | 0.51%   |
| WDC WD5000LPLX-00ZNTT0 500GB                        | 1         | 1      | 0.51%   |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 1      | 0.51%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 1      | 0.51%   |
| WDC WD5000BPVT-60HXZT3 500GB                        | 1         | 1      | 0.51%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 1      | 0.51%   |
| WDC WD5000BEVT-75A0RT0 500GB                        | 1         | 1      | 0.51%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 1      | 0.51%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 1         | 1      | 0.51%   |
| WDC WD2500LPCX-24C6HT0 250GB                        | 1         | 1      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 78     | 26.67%  |
| HGST                | 29        | 29     | 14.87%  |
| WDC                 | 24        | 26     | 12.31%  |
| Toshiba             | 22        | 25     | 11.28%  |
| Hitachi             | 19        | 20     | 9.74%   |
| Crucial             | 8         | 11     | 4.1%    |
| Samsung Electronics | 6         | 6      | 3.08%   |
| SK hynix            | 5         | 9      | 2.56%   |
| SanDisk             | 5         | 5      | 2.56%   |
| Micron Technology   | 4         | 6      | 2.05%   |
| Intel               | 4         | 5      | 2.05%   |
| LITEON              | 3         | 3      | 1.54%   |
| Kingston            | 3         | 3      | 1.54%   |
| A-DATA Technology   | 3         | 4      | 1.54%   |
| LITEONIT            | 1         | 1      | 0.51%   |
| KingSpec            | 1         | 1      | 0.51%   |
| IM3D                | 1         | 1      | 0.51%   |
| Faspeed             | 1         | 1      | 0.51%   |
| Corsair             | 1         | 1      | 0.51%   |
| ASMT                | 1         | 1      | 0.51%   |
| Apple               | 1         | 1      | 0.51%   |
| Unknown             | 1         | 1      | 0.51%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 78     | 36.62%  |
| HGST                | 29        | 29     | 20.42%  |
| WDC                 | 23        | 25     | 16.2%   |
| Hitachi             | 19        | 20     | 13.38%  |
| Toshiba             | 18        | 21     | 12.68%  |
| Samsung Electronics | 1         | 1      | 0.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 141       | 174    | 73.06%  |
| SSD  | 46        | 57     | 23.83%  |
| NVMe | 6         | 7      | 3.11%   |

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
| Detected | 1908      | 2945   | 57.25%  |
| Works    | 1233      | 1815   | 36.99%  |
| Malfunc  | 189       | 238    | 5.67%   |
| Failed   | 3         | 3      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2072      | 54.24%  |
| AMD                              | 447       | 11.7%   |
| Samsung Electronics              | 434       | 11.36%  |
| SanDisk                          | 227       | 5.94%   |
| SK hynix                         | 165       | 4.32%   |
| Toshiba America Info Systems     | 80        | 2.09%   |
| Kingston Technology Company      | 61        | 1.6%    |
| KIOXIA                           | 54        | 1.41%   |
| Phison Electronics               | 53        | 1.39%   |
| Micron Technology                | 53        | 1.39%   |
| Micron/Crucial Technology        | 25        | 0.65%   |
| ADATA Technology                 | 25        | 0.65%   |
| Union Memory (Shenzhen)          | 23        | 0.6%    |
| Silicon Motion                   | 18        | 0.47%   |
| Nvidia                           | 17        | 0.45%   |
| Solid State Storage Technology   | 14        | 0.37%   |
| Apple                            | 11        | 0.29%   |
| Lite-On Technology               | 10        | 0.26%   |
| Realtek Semiconductor            | 7         | 0.18%   |
| Shenzhen Longsys Electronics     | 6         | 0.16%   |
| Lenovo                           | 4         | 0.1%    |
| Marvell Technology Group         | 3         | 0.08%   |
| JMicron Technology               | 3         | 0.08%   |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| Seagate Technology               | 2         | 0.05%   |
| Biwin Storage Technology         | 2         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Silicon Image                    | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 409       | 10.28%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 296       | 7.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 246       | 6.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 227       | 5.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 187       | 4.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 144       | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 144       | 3.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 136       | 3.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 122       | 3.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 109       | 2.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 97        | 2.44%   |
| Samsung NVMe SSD Controller 980                                                | 79        | 1.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 72        | 1.81%   |
| Intel SSD 660P Series                                                          | 60        | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                            | 59        | 1.48%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 57        | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 54        | 1.36%   |
| Micron Non-Volatile memory controller                                          | 53        | 1.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 49        | 1.23%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 48        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 48        | 1.21%   |
| SK hynix Gold P31 SSD                                                          | 45        | 1.13%   |
| SK hynix BC511                                                                 | 41        | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 39        | 0.98%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 38        | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                          | 38        | 0.95%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 37        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 35        | 0.88%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 33        | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 32        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 32        | 0.8%    |
| SanDisk Non-Volatile memory controller                                         | 30        | 0.75%   |
| Phison E12 NVMe Controller                                                     | 27        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 27        | 0.68%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 26        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 26        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 26        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 25        | 0.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 25        | 0.63%   |
| SK hynix Non-Volatile memory controller                                        | 24        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2225      | 57.81%  |
| NVMe | 1280      | 33.26%  |
| RAID | 248       | 6.44%   |
| IDE  | 96        | 2.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2422      | 78.46%  |
| AMD    | 665       | 21.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 74        | 2.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 64        | 2.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 61        | 1.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 60        | 1.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 59        | 1.91%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 59        | 1.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 58        | 1.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 58        | 1.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 54        | 1.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 45        | 1.46%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 42        | 1.36%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 42        | 1.36%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 41        | 1.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 40        | 1.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 40        | 1.29%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 37        | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 37        | 1.2%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 34        | 1.1%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 1.07%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 32        | 1.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 31        | 1%      |
| AMD Ryzen 5 4600H with Radeon Graphics        | 31        | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz             | 30        | 0.97%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 28        | 0.91%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 27        | 0.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 27        | 0.87%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 27        | 0.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 26        | 0.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 26        | 0.84%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 24        | 0.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 24        | 0.78%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 23        | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 0.71%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 21        | 0.68%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 21        | 0.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 19        | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 18        | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 18        | 0.58%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 18        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 847       | 27.39%  |
| Intel Core i5                  | 845       | 27.33%  |
| Intel Core i3                  | 215       | 6.95%   |
| AMD Ryzen 5                    | 204       | 6.6%    |
| AMD Ryzen 7                    | 192       | 6.21%   |
| Other                          | 160       | 5.17%   |
| Intel Celeron                  | 116       | 3.75%   |
| Intel Core 2 Duo               | 81        | 2.62%   |
| Intel Pentium                  | 74        | 2.39%   |
| AMD Ryzen 3                    | 42        | 1.36%   |
| AMD Ryzen 9                    | 27        | 0.87%   |
| AMD A6                         | 27        | 0.87%   |
| AMD Ryzen 7 PRO                | 26        | 0.84%   |
| Intel Atom                     | 21        | 0.68%   |
| Intel Pentium Dual-Core        | 18        | 0.58%   |
| Intel Core i9                  | 18        | 0.58%   |
| AMD A8                         | 18        | 0.58%   |
| AMD A10                        | 18        | 0.58%   |
| AMD A4                         | 17        | 0.55%   |
| AMD E                          | 15        | 0.49%   |
| AMD E1                         | 14        | 0.45%   |
| Intel Pentium Silver           | 11        | 0.36%   |
| Intel Core 2                   | 10        | 0.32%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.23%   |
| AMD E2                         | 7         | 0.23%   |
| AMD Athlon                     | 7         | 0.23%   |
| Intel Core m3                  | 6         | 0.19%   |
| AMD A12                        | 5         | 0.16%   |
| Intel Genuine                  | 4         | 0.13%   |
| Intel Xeon                     | 3         | 0.1%    |
| Intel Core m5                  | 3         | 0.1%    |
| AMD Ryzen 5 PRO                | 3         | 0.1%    |
| AMD Athlon X2                  | 3         | 0.1%    |
| Intel Core m7                  | 2         | 0.06%   |
| Intel Core M                   | 2         | 0.06%   |
| Intel Core 2 Quad              | 2         | 0.06%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.06%   |
| AMD Turion II                  | 2         | 0.06%   |
| AMD Phenom II                  | 2         | 0.06%   |
| AMD FX                         | 2         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1359      | 44.01%  |
| 4       | 1164      | 37.69%  |
| 6       | 294       | 9.52%   |
| 8       | 244       | 7.9%    |
| 1       | 15        | 0.49%   |
| 14      | 5         | 0.16%   |
| 12      | 3         | 0.1%    |
| 3       | 2         | 0.06%   |
| 16      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3087      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2534      | 82.03%  |
| 1       | 554       | 17.93%  |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3024      | 97.9%   |
| Unknown        | 65        | 2.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1493      | 46.85%  |
| 0x306a9    | 130       | 4.08%   |
| 0x906ea    | 108       | 3.39%   |
| 0x806ea    | 107       | 3.36%   |
| 0x806ec    | 92        | 2.89%   |
| 0x806e9    | 73        | 2.29%   |
| 0x206a7    | 73        | 2.29%   |
| 0x806c1    | 72        | 2.26%   |
| 0x40651    | 68        | 2.13%   |
| 0x406e3    | 64        | 2.01%   |
| 0x08108102 | 60        | 1.88%   |
| 0x306d4    | 55        | 1.73%   |
| 0x306c3    | 54        | 1.69%   |
| 0x906e9    | 51        | 1.6%    |
| 0x08600106 | 44        | 1.38%   |
| 0xa0652    | 41        | 1.29%   |
| 0x08600103 | 41        | 1.29%   |
| 0x806eb    | 39        | 1.22%   |
| 0x706e5    | 36        | 1.13%   |
| 0x0a50000c | 36        | 1.13%   |
| 0x08108109 | 36        | 1.13%   |
| 0x08600104 | 33        | 1.04%   |
| 0x506e3    | 27        | 0.85%   |
| 0x1067a    | 26        | 0.82%   |
| 0x20655    | 25        | 0.78%   |
| 0x08608103 | 21        | 0.66%   |
| 0x30678    | 16        | 0.5%    |
| 0x0810100b | 16        | 0.5%    |
| 0x506c9    | 14        | 0.44%   |
| 0x406c4    | 14        | 0.44%   |
| 0x06006705 | 14        | 0.44%   |
| 0x706a1    | 12        | 0.38%   |
| 0x806d1    | 11        | 0.35%   |
| 0x08600102 | 11        | 0.35%   |
| 0x06001119 | 10        | 0.31%   |
| 0x906ed    | 9         | 0.28%   |
| 0x0a50000b | 9         | 0.28%   |
| 0x0600611a | 9         | 0.28%   |
| 0x10676    | 8         | 0.25%   |
| 0xa0660    | 7         | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 793       | 25.69%  |
| Haswell          | 259       | 8.39%   |
| IvyBridge        | 235       | 7.61%   |
| Zen 2            | 186       | 6.03%   |
| Skylake          | 182       | 5.9%    |
| SandyBridge      | 182       | 5.9%    |
| Zen+             | 150       | 4.86%   |
| Broadwell        | 129       | 4.18%   |
| TigerLake        | 118       | 3.82%   |
| Zen 3            | 83        | 2.69%   |
| Westmere         | 83        | 2.69%   |
| Penryn           | 82        | 2.66%   |
| CometLake        | 79        | 2.56%   |
| Silvermont       | 77        | 2.49%   |
| IceLake          | 70        | 2.27%   |
| Unknown          | 63        | 2.04%   |
| Excavator        | 49        | 1.59%   |
| Goldmont plus    | 38        | 1.23%   |
| Zen              | 37        | 1.2%    |
| Core             | 34        | 1.1%    |
| Goldmont         | 27        | 0.87%   |
| Bobcat           | 25        | 0.81%   |
| Piledriver       | 23        | 0.75%   |
| Puma             | 18        | 0.58%   |
| Jaguar           | 16        | 0.52%   |
| Nehalem          | 10        | 0.32%   |
| K8 Hammer        | 9         | 0.29%   |
| K10 Llano        | 8         | 0.26%   |
| K10              | 7         | 0.23%   |
| K8 & K10 hybrid  | 5         | 0.16%   |
| Bonnell          | 5         | 0.16%   |
| Alderlake Hybrid | 3         | 0.1%    |
| Steamroller      | 2         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2247      | 54.12%  |
| Nvidia | 1095      | 26.37%  |
| AMD    | 810       | 19.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 223       | 5.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 177       | 4.18%   |
| AMD Renoir                                                                               | 176       | 4.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 161       | 3.8%    |
| Intel UHD Graphics 620                                                                   | 158       | 3.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 152       | 3.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 147       | 3.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 135       | 3.19%   |
| Intel HD Graphics 620                                                                    | 111       | 2.62%   |
| Intel HD Graphics 5500                                                                   | 110       | 2.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 104       | 2.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 99        | 2.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 87        | 2.05%   |
| Intel HD Graphics 630                                                                    | 81        | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 76        | 1.79%   |
| AMD Cezanne                                                                              | 71        | 1.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 62        | 1.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 62        | 1.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 59        | 1.39%   |
| Intel HD Graphics 530                                                                    | 56        | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 55        | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 55        | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 44        | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 43        | 1.02%   |
| Nvidia GP108M [GeForce MX150]                                                            | 40        | 0.94%   |
| AMD Lucienne                                                                             | 40        | 0.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 38        | 0.9%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 38        | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 38        | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 34        | 0.8%    |
| Nvidia TU117M                                                                            | 33        | 0.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 33        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 33        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 32        | 0.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 31        | 0.73%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 31        | 0.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 30        | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 30        | 0.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 29        | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1308      | 42.29%  |
| Intel + Nvidia     | 827       | 26.74%  |
| 1 x AMD            | 525       | 16.97%  |
| 1 x Nvidia         | 143       | 4.62%   |
| AMD + Nvidia       | 120       | 3.88%   |
| Intel + AMD        | 110       | 3.56%   |
| 2 x AMD            | 55        | 1.78%   |
| 2 x Nvidia         | 3         | 0.1%    |
| Other              | 1         | 0.03%   |
| Intel + 2 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2497      | 80.03%  |
| Proprietary | 622       | 19.94%  |
| Unknown     | 1         | 0.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2382      | 76.08%  |
| 0.01-0.5   | 248       | 7.92%   |
| 1.01-2.0   | 212       | 6.77%   |
| 0.51-1.0   | 99        | 3.16%   |
| 3.01-4.0   | 98        | 3.13%   |
| 5.01-6.0   | 49        | 1.56%   |
| 7.01-8.0   | 26        | 0.83%   |
| 2.01-3.0   | 11        | 0.35%   |
| 8.01-16.0  | 6         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 648       | 17.77%  |
| LG Display              | 571       | 15.66%  |
| Chimei Innolux          | 535       | 14.67%  |
| BOE                     | 519       | 14.23%  |
| Samsung Electronics     | 291       | 7.98%   |
| Sharp                   | 119       | 3.26%   |
| Dell                    | 99        | 2.72%   |
| Goldstar                | 88        | 2.41%   |
| PANDA                   | 81        | 2.22%   |
| Apple                   | 77        | 2.11%   |
| Chi Mei Optoelectronics | 72        | 1.97%   |
| Lenovo                  | 60        | 1.65%   |
| Hewlett-Packard         | 38        | 1.04%   |
| Philips                 | 37        | 1.01%   |
| Ancor Communications    | 33        | 0.91%   |
| Acer                    | 31        | 0.85%   |
| BenQ                    | 29        | 0.8%    |
| AOC                     | 29        | 0.8%    |
| InfoVision              | 23        | 0.63%   |
| CSO                     | 19        | 0.52%   |
| LGD                     | 17        | 0.47%   |
| ViewSonic               | 15        | 0.41%   |
| Iiyama                  | 15        | 0.41%   |
| TMX                     | 14        | 0.38%   |
| LG Philips              | 13        | 0.36%   |
| Sony                    | 12        | 0.33%   |
| ASUSTek Computer        | 11        | 0.3%    |
| Panasonic               | 10        | 0.27%   |
| CPT                     | 10        | 0.27%   |
| Toshiba                 | 6         | 0.16%   |
| Insignia                | 6         | 0.16%   |
| Unknown                 | 5         | 0.14%   |
| NEC Computers           | 5         | 0.14%   |
| HannStar                | 5         | 0.14%   |
| KDC                     | 4         | 0.11%   |
| JDI                     | 4         | 0.11%   |
| InnoLux Display         | 4         | 0.11%   |
| Fujitsu Siemens         | 4         | 0.11%   |
| CMN                     | 4         | 0.11%   |
| Vizio                   | 3         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 39        | 1.06%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 35        | 0.95%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 32        | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 28        | 0.76%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 27        | 0.73%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 20        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 19        | 0.52%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 19        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 16        | 0.43%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 16        | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 14        | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.38%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 13        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 13        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 12        | 0.33%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 12        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 12        | 0.33%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 12        | 0.33%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 11        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.3%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 11        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 10        | 0.27%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 10        | 0.27%   |
| AU Optronics LCD Monitor 1920x1080                                       | 10        | 0.27%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                  | 9         | 0.24%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 9         | 0.24%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 9         | 0.24%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 9         | 0.24%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 9         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 9         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 9         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1695      | 49.75%  |
| 1366x768 (WXGA)    | 864       | 25.36%  |
| 3840x2160 (4K)     | 143       | 4.2%    |
| 1600x900 (HD+)     | 132       | 3.87%   |
| 2560x1440 (QHD)    | 94        | 2.76%   |
| 1280x800 (WXGA)    | 75        | 2.2%    |
| 1440x900 (WXGA+)   | 51        | 1.5%    |
| 1920x1200 (WUXGA)  | 48        | 1.41%   |
| 1680x1050 (WSXGA+) | 31        | 0.91%   |
| 2880x1800          | 29        | 0.85%   |
| 2560x1600          | 29        | 0.85%   |
| 2560x1080          | 23        | 0.68%   |
| Unknown            | 18        | 0.53%   |
| 3840x2400          | 17        | 0.5%    |
| 1280x1024 (SXGA)   | 17        | 0.5%    |
| 2160x1440          | 15        | 0.44%   |
| 1360x768           | 15        | 0.44%   |
| 3840x1080          | 12        | 0.35%   |
| 3200x1800 (QHD+)   | 11        | 0.32%   |
| 3456x2160          | 9         | 0.26%   |
| 3440x1440          | 9         | 0.26%   |
| 3200x2000          | 9         | 0.26%   |
| 1920x540           | 6         | 0.18%   |
| 3000x2000          | 5         | 0.15%   |
| 1920x1280          | 5         | 0.15%   |
| 3286x1080          | 4         | 0.12%   |
| 2256x1504          | 4         | 0.12%   |
| 3840x1600          | 3         | 0.09%   |
| 2880x1920          | 3         | 0.09%   |
| 2240x1400          | 3         | 0.09%   |
| 1600x1200          | 3         | 0.09%   |
| 1024x600           | 3         | 0.09%   |
| 3840x1100          | 2         | 0.06%   |
| 2560x1700          | 2         | 0.06%   |
| 2520x1680          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 7680x1080          | 1         | 0.03%   |
| 720x1280           | 1         | 0.03%   |
| 5760x2160          | 1         | 0.03%   |
| 4480x1600          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1599      | 44.1%   |
| 13      | 523       | 14.42%  |
| 14      | 446       | 12.3%   |
| 17      | 231       | 6.37%   |
| 27      | 121       | 3.34%   |
| 24      | 114       | 3.14%   |
| 23      | 92        | 2.54%   |
| 12      | 82        | 2.26%   |
| 21      | 73        | 2.01%   |
| Unknown | 64        | 1.77%   |
| 11      | 46        | 1.27%   |
| 31      | 40        | 1.1%    |
| 34      | 29        | 0.8%    |
| 16      | 26        | 0.72%   |
| 18      | 20        | 0.55%   |
| 19      | 16        | 0.44%   |
| 22      | 15        | 0.41%   |
| 20      | 12        | 0.33%   |
| 84      | 9         | 0.25%   |
| 32      | 8         | 0.22%   |
| 72      | 6         | 0.17%   |
| 26      | 5         | 0.14%   |
| 54      | 4         | 0.11%   |
| 49      | 4         | 0.11%   |
| 48      | 4         | 0.11%   |
| 37      | 4         | 0.11%   |
| 25      | 4         | 0.11%   |
| 10      | 4         | 0.11%   |
| 74      | 3         | 0.08%   |
| 52      | 3         | 0.08%   |
| 28      | 3         | 0.08%   |
| 42      | 2         | 0.06%   |
| 40      | 2         | 0.06%   |
| 33      | 2         | 0.06%   |
| 8       | 2         | 0.06%   |
| 86      | 1         | 0.03%   |
| 75      | 1         | 0.03%   |
| 60      | 1         | 0.03%   |
| 50      | 1         | 0.03%   |
| 43      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2325      | 64.64%  |
| 201-300     | 360       | 10.01%  |
| 501-600     | 301       | 8.37%   |
| 351-400     | 268       | 7.45%   |
| 401-500     | 130       | 3.61%   |
| Unknown     | 64        | 1.78%   |
| 601-700     | 60        | 1.67%   |
| 701-800     | 39        | 1.08%   |
| 1501-2000   | 20        | 0.56%   |
| 1001-1500   | 17        | 0.47%   |
| 801-900     | 8         | 0.22%   |
| 901-1000    | 3         | 0.08%   |
| 101-200     | 2         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2719      | 85.26%  |
| 16/10   | 303       | 9.5%    |
| Unknown | 52        | 1.63%   |
| 3/2     | 43        | 1.35%   |
| 21/9    | 34        | 1.07%   |
| 5/4     | 13        | 0.41%   |
| 4/3     | 10        | 0.31%   |
| 32/9    | 9         | 0.28%   |
| 3.40    | 2         | 0.06%   |
| 0.62    | 2         | 0.06%   |
| 6/5     | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1600      | 44.24%  |
| 81-90          | 781       | 21.59%  |
| 201-250        | 243       | 6.72%   |
| 121-130        | 194       | 5.36%   |
| 71-80          | 189       | 5.23%   |
| 301-350        | 124       | 3.43%   |
| 351-500        | 83        | 2.29%   |
| 61-70          | 77        | 2.13%   |
| Unknown        | 64        | 1.77%   |
| 51-60          | 48        | 1.33%   |
| 151-200        | 43        | 1.19%   |
| 251-300        | 35        | 0.97%   |
| More than 1000 | 32        | 0.88%   |
| 131-140        | 30        | 0.83%   |
| 141-150        | 25        | 0.69%   |
| 111-120        | 17        | 0.47%   |
| 501-1000       | 14        | 0.39%   |
| 91-100         | 12        | 0.33%   |
| 41-50          | 4         | 0.11%   |
| 1-40           | 2         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1624      | 45.66%  |
| 101-120       | 941       | 26.45%  |
| 51-100        | 504       | 14.17%  |
| 161-240       | 252       | 7.08%   |
| More than 240 | 140       | 3.94%   |
| Unknown       | 64        | 1.8%    |
| 1-50          | 32        | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2525      | 80.41%  |
| 2     | 544       | 17.32%  |
| 3     | 51        | 1.62%   |
| 0     | 16        | 0.51%   |
| 4     | 4         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1722      | 35.51%  |
| Realtek Semiconductor             | 1707      | 35.2%   |
| Qualcomm Atheros                  | 674       | 13.9%   |
| Broadcom                          | 243       | 5.01%   |
| Broadcom Limited                  | 65        | 1.34%   |
| MediaTek                          | 47        | 0.97%   |
| Ralink                            | 41        | 0.85%   |
| TP-Link                           | 32        | 0.66%   |
| Ralink Technology                 | 30        | 0.62%   |
| Marvell Technology Group          | 23        | 0.47%   |
| Xiaomi                            | 22        | 0.45%   |
| Sierra Wireless                   | 21        | 0.43%   |
| Dell                              | 19        | 0.39%   |
| ASIX Electronics                  | 19        | 0.39%   |
| Lenovo                            | 16        | 0.33%   |
| Hewlett-Packard                   | 14        | 0.29%   |
| DisplayLink                       | 14        | 0.29%   |
| Huawei Technologies               | 12        | 0.25%   |
| JMicron Technology                | 11        | 0.23%   |
| Samsung Electronics               | 10        | 0.21%   |
| Ericsson Business Mobile Networks | 10        | 0.21%   |
| Nvidia                            | 9         | 0.19%   |
| Qualcomm                          | 8         | 0.16%   |
| ASUSTek Computer                  | 8         | 0.16%   |
| Linksys                           | 7         | 0.14%   |
| NetGear                           | 6         | 0.12%   |
| D-Link                            | 6         | 0.12%   |
| Qualcomm Atheros Communications   | 5         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 5         | 0.1%    |
| FIBOCOM                           | 5         | 0.1%    |
| Edimax Technology                 | 4         | 0.08%   |
| Apple                             | 4         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.06%   |
| Google                            | 3         | 0.06%   |
| ZyXEL Communications              | 2         | 0.04%   |
| Spreadtrum Communications         | 2         | 0.04%   |
| Quectel Wireless Solutions        | 2         | 0.04%   |
| Motorola PCS                      | 2         | 0.04%   |
| ICS Advent                        | 2         | 0.04%   |
| Attansic Technology               | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1122      | 19.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 286       | 4.94%   |
| Intel Wi-Fi 6 AX200                                               | 239       | 4.13%   |
| Intel Wireless 8265 / 8275                                        | 158       | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 151       | 2.61%   |
| Intel Wireless 7265                                               | 117       | 2.02%   |
| Intel Wireless 7260                                               | 117       | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 116       | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 115       | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 111       | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 109       | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 100       | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 98        | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 94        | 1.62%   |
| Intel Wi-Fi 6 AX201                                               | 90        | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 85        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 78        | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 77        | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 75        | 1.3%    |
| Intel Wireless 8260                                               | 70        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 63        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 62        | 1.07%   |
| Intel Wireless 3165                                               | 62        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 54        | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 53        | 0.92%   |
| Intel Wireless 3160                                               | 39        | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 39        | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 39        | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 37        | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 36        | 0.62%   |
| Intel Wireless-AC 9260                                            | 35        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 35        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 0.59%   |
| Intel Centrino Wireless-N 2230                                    | 34        | 0.59%   |
| Broadcom BCM43142 802.11b/g/n                                     | 34        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 33        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 32        | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 31        | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 29        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1676      | 52%     |
| Qualcomm Atheros                      | 566       | 17.56%  |
| Realtek Semiconductor                 | 508       | 15.76%  |
| Broadcom                              | 187       | 5.8%    |
| Broadcom Limited                      | 50        | 1.55%   |
| MediaTek                              | 43        | 1.33%   |
| Ralink                                | 41        | 1.27%   |
| Ralink Technology                     | 30        | 0.93%   |
| TP-Link                               | 27        | 0.84%   |
| Sierra Wireless                       | 21        | 0.65%   |
| Dell                                  | 14        | 0.43%   |
| Linksys                               | 7         | 0.22%   |
| NetGear                               | 6         | 0.19%   |
| D-Link                                | 6         | 0.19%   |
| ASUSTek Computer                      | 6         | 0.19%   |
| Qualcomm Atheros Communications       | 5         | 0.16%   |
| Hewlett-Packard                       | 4         | 0.12%   |
| FIBOCOM                               | 4         | 0.12%   |
| Ericsson Business Mobile Networks     | 4         | 0.12%   |
| Edimax Technology                     | 4         | 0.12%   |
| Qualcomm                              | 3         | 0.09%   |
| ZyXEL Communications                  | 2         | 0.06%   |
| Quectel Wireless Solutions            | 2         | 0.06%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Microsoft                             | 1         | 0.03%   |
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
| Intel Wi-Fi 6 AX200                                            | 239       | 7.35%   |
| Intel Wireless 8265 / 8275                                     | 158       | 4.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 151       | 4.65%   |
| Intel Wireless 7265                                            | 117       | 3.6%    |
| Intel Wireless 7260                                            | 117       | 3.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 116       | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 109       | 3.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 100       | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 98        | 3.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 94        | 2.89%   |
| Intel Wi-Fi 6 AX201                                            | 90        | 2.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 85        | 2.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 78        | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 77        | 2.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 75        | 2.31%   |
| Intel Wireless 8260                                            | 70        | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 63        | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 62        | 1.91%   |
| Intel Wireless 3165                                            | 62        | 1.91%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 54        | 1.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 53        | 1.63%   |
| Intel Wireless 3160                                            | 39        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 39        | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 39        | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 37        | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 36        | 1.11%   |
| Intel Wireless-AC 9260                                         | 35        | 1.08%   |
| Intel Centrino Wireless-N 2230                                 | 34        | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                  | 34        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 31        | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 29        | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 28        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 27        | 0.83%   |
| Intel Centrino Advanced-N 6235                                 | 25        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                 | 23        | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 21        | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 20        | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 19        | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 19        | 0.58%   |
| Realtek 802.11ac NIC                                           | 19        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1534      | 61.98%  |
| Intel                                  | 497       | 20.08%  |
| Qualcomm Atheros                       | 168       | 6.79%   |
| Broadcom                               | 86        | 3.47%   |
| Marvell Technology Group               | 23        | 0.93%   |
| Xiaomi                                 | 21        | 0.85%   |
| ASIX Electronics                       | 19        | 0.77%   |
| Broadcom Limited                       | 18        | 0.73%   |
| Lenovo                                 | 16        | 0.65%   |
| DisplayLink                            | 14        | 0.57%   |
| JMicron Technology                     | 11        | 0.44%   |
| Samsung Electronics                    | 9         | 0.36%   |
| Nvidia                                 | 9         | 0.36%   |
| TP-Link                                | 5         | 0.2%    |
| Qualcomm                               | 5         | 0.2%    |
| Huawei Technologies                    | 5         | 0.2%    |
| OnePlus Technology (Shenzhen)          | 4         | 0.16%   |
| MediaTek                               | 4         | 0.16%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.12%   |
| Hewlett-Packard                        | 3         | 0.12%   |
| Google                                 | 3         | 0.12%   |
| Apple                                  | 3         | 0.12%   |
| Spreadtrum Communications              | 2         | 0.08%   |
| Motorola PCS                           | 2         | 0.08%   |
| ICS Advent                             | 2         | 0.08%   |
| Attansic Technology                    | 2         | 0.08%   |
| ASUSTek Computer                       | 2         | 0.08%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1122      | 44.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 286       | 11.41%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 115       | 4.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 111       | 4.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 35        | 1.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 33        | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32        | 1.28%   |
| Intel Ethernet Connection (4) I219-V                              | 32        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 25        | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 24        | 0.96%   |
| Intel Ethernet Connection (6) I219-V                              | 21        | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.84%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                             | 18        | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 16        | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15        | 0.6%    |
| Intel Ethernet Connection I219-V                                  | 15        | 0.6%    |
| Intel 82567LM Gigabit Network Connection                          | 15        | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 14        | 0.56%   |
| Intel Ethernet Connection (10) I219-V                             | 14        | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 13        | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 12        | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 11        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 9         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.32%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.32%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 0.32%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.32%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 8         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3052      | 55.81%  |
| Ethernet | 2386      | 43.63%  |
| Modem    | 28        | 0.51%   |
| Unknown  | 3         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2647      | 81.42%  |
| Ethernet | 604       | 18.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2186      | 70.74%  |
| 1     | 853       | 27.61%  |
| 0     | 28        | 0.91%   |
| 3     | 23        | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2703      | 86.52%  |
| Yes  | 421       | 13.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1357      | 53.62%  |
| Realtek Semiconductor           | 286       | 11.3%   |
| Qualcomm Atheros Communications | 268       | 10.59%  |
| IMC Networks                    | 132       | 5.22%   |
| Lite-On Technology              | 112       | 4.43%   |
| Broadcom                        | 87        | 3.44%   |
| Apple                           | 62        | 2.45%   |
| Foxconn / Hon Hai               | 53        | 2.09%   |
| Realtek                         | 31        | 1.22%   |
| Cambridge Silicon Radio         | 26        | 1.03%   |
| Dell                            | 22        | 0.87%   |
| Ralink                          | 21        | 0.83%   |
| Hewlett-Packard                 | 16        | 0.63%   |
| Toshiba                         | 11        | 0.43%   |
| Foxconn International           | 9         | 0.36%   |
| Ralink Technology               | 6         | 0.24%   |
| ASUSTek Computer                | 6         | 0.24%   |
| Opticis                         | 5         | 0.2%    |
| Alps Electric                   | 5         | 0.2%    |
| Askey Computer                  | 4         | 0.16%   |
| MediaTek                        | 3         | 0.12%   |
| Fujitsu                         | 2         | 0.08%   |
| Belkin Components               | 2         | 0.08%   |
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
| Intel Bluetooth wireless interface                  | 522       | 20.61%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 245       | 9.67%   |
| Intel AX200 Bluetooth                               | 230       | 9.08%   |
| Intel AX201 Bluetooth                               | 198       | 7.82%   |
| Realtek Bluetooth Radio                             | 183       | 7.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 133       | 5.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 76        | 3%      |
| IMC Networks Bluetooth Radio                        | 57        | 2.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 51        | 2.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 41        | 1.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 39        | 1.54%   |
| Lite-On Bluetooth Device                            | 36        | 1.42%   |
| Intel Wireless-AC 3168 Bluetooth                    | 36        | 1.42%   |
| Apple Bluetooth Host Controller                     | 32        | 1.26%   |
| Realtek Bluetooth Radio                             | 31        | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 31        | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 31        | 1.22%   |
| IMC Networks Bluetooth Device                       | 30        | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 1.14%   |
| Intel AX210 Bluetooth                               | 26        | 1.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device                  | 24        | 0.95%   |
| Apple Bluetooth USB Host Controller                 | 24        | 0.95%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.83%   |
| IMC Networks Wireless_Device                        | 20        | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 18        | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 16        | 0.63%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 15        | 0.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 15        | 0.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.51%   |
| Broadcom HP Portable SoftSailing                    | 11        | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 10        | 0.39%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.36%   |
| Foxconn International BCM43142A0 Bluetooth module   | 9         | 0.36%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 8         | 0.32%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 8         | 0.32%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 0.32%   |
| Dell BCM20702A0 Bluetooth Module                    | 8         | 0.32%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 7         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2382      | 63.22%  |
| AMD                                  | 722       | 19.16%  |
| Nvidia                               | 417       | 11.07%  |
| C-Media Electronics                  | 29        | 0.77%   |
| Realtek Semiconductor                | 22        | 0.58%   |
| Logitech                             | 22        | 0.58%   |
| Lenovo                               | 17        | 0.45%   |
| GN Netcom                            | 17        | 0.45%   |
| Kingston Technology                  | 12        | 0.32%   |
| JMTek                                | 10        | 0.27%   |
| SteelSeries ApS                      | 9         | 0.24%   |
| Texas Instruments                    | 8         | 0.21%   |
| Plantronics                          | 8         | 0.21%   |
| Generalplus Technology               | 8         | 0.21%   |
| Apple                                | 8         | 0.21%   |
| Focusrite-Novation                   | 5         | 0.13%   |
| Samson Technologies                  | 4         | 0.11%   |
| GYROCOM C&C                          | 4         | 0.11%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.08%   |
| Razer USA                            | 3         | 0.08%   |
| Huawei Technologies                  | 3         | 0.08%   |
| Hewlett-Packard                      | 3         | 0.08%   |
| Corsair                              | 3         | 0.08%   |
| RODE Microphones                     | 2         | 0.05%   |
| DSEA A/S                             | 2         | 0.05%   |
| DCMT Technology                      | 2         | 0.05%   |
| Creative Technology                  | 2         | 0.05%   |
| Cambridge Silicon Radio              | 2         | 0.05%   |
| Blue Microphones                     | 2         | 0.05%   |
| Astro Gaming                         | 2         | 0.05%   |
| Alesis                               | 2         | 0.05%   |
| Yealink Network Technology           | 1         | 0.03%   |
| Yamaha                               | 1         | 0.03%   |
| VIA Technologies                     | 1         | 0.03%   |
| Trust                                | 1         | 0.03%   |
| TC Electronic                        | 1         | 0.03%   |
| Syntek                               | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| SlrTek                               | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 494       | 10.51%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 402       | 8.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 265       | 5.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 232       | 4.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 191       | 4.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 168       | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 152       | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 149       | 3.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 148       | 3.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 138       | 2.93%   |
| Intel Broadwell-U Audio Controller                                                                | 129       | 2.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 128       | 2.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 118       | 2.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 109       | 2.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 93        | 1.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 91        | 1.94%   |
| Intel CM238 HD Audio Controller                                                                   | 87        | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 85        | 1.81%   |
| AMD FCH Azalia Controller                                                                         | 76        | 1.62%   |
| Intel Comet Lake PCH cAVS                                                                         | 67        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 67        | 1.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 62        | 1.32%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 59        | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 58        | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 53        | 1.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 48        | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 46        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 39        | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 38        | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 36        | 0.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 34        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 33        | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 30        | 0.64%   |
| AMD High Definition Audio Controller                                                              | 30        | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 29        | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 27        | 0.57%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 26        | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 25        | 0.53%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 25        | 0.53%   |
| AMD Trinity HDMI Audio Controller                                                                 | 23        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 764       | 32.28%  |
| SK hynix            | 509       | 21.5%   |
| Micron Technology   | 312       | 13.18%  |
| Kingston            | 216       | 9.13%   |
| Crucial             | 103       | 4.35%   |
| Unknown             | 89        | 3.76%   |
| Ramaxel Technology  | 59        | 2.49%   |
| A-DATA Technology   | 57        | 2.41%   |
| Elpida              | 41        | 1.73%   |
| Corsair             | 30        | 1.27%   |
| Nanya Technology    | 29        | 1.23%   |
| G.Skill             | 21        | 0.89%   |
| Smart               | 17        | 0.72%   |
| GOODRAM             | 14        | 0.59%   |
| Unknown (ABCD)      | 12        | 0.51%   |
| Transcend           | 12        | 0.51%   |
| Patriot             | 11        | 0.46%   |
| Team                | 9         | 0.38%   |
| ASint Technology    | 6         | 0.25%   |
| Apacer              | 6         | 0.25%   |
| AMD                 | 5         | 0.21%   |
| Teikon              | 4         | 0.17%   |
| Unknown             | 4         | 0.17%   |
| Smart Brazil        | 3         | 0.13%   |
| SHARETRONIC         | 3         | 0.13%   |
| Goldkey             | 3         | 0.13%   |
| Avant               | 3         | 0.13%   |
| Atermiter           | 3         | 0.13%   |
| Silicon Power       | 2         | 0.08%   |
| Qumo                | 2         | 0.08%   |
| Qimonda             | 2         | 0.08%   |
| Kllisre             | 2         | 0.08%   |
| V-Color             | 1         | 0.04%   |
| Unknown (768A)      | 1         | 0.04%   |
| Unknown (0x02BA)    | 1         | 0.04%   |
| Unknown (08B5)      | 1         | 0.04%   |
| Unknown (08AE)      | 1         | 0.04%   |
| Unifosa             | 1         | 0.04%   |
| TwinMOS             | 1         | 0.04%   |
| Timetec             | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 55        | 2.21%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 49        | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 42        | 1.68%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 38        | 1.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 33        | 1.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 33        | 1.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 29        | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 1.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 26        | 1.04%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 1%      |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 24        | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.88%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 22        | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.8%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 19        | 0.76%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 19        | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 16        | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 15        | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.6%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.52%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 13        | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 13        | 0.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.48%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 12        | 0.48%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 12        | 0.48%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.44%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.44%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 11        | 0.44%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 11        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 10        | 0.4%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 10        | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 0.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 10        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1077      | 54.64%  |
| DDR3    | 627       | 31.81%  |
| LPDDR4  | 95        | 4.82%   |
| LPDDR3  | 91        | 4.62%   |
| SDRAM   | 31        | 1.57%   |
| DDR2    | 31        | 1.57%   |
| DDR5    | 6         | 0.3%    |
| LPDDR5  | 5         | 0.25%   |
| Unknown | 4         | 0.2%    |
| DRAM    | 2         | 0.1%    |
| DDR     | 2         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1718      | 87.08%  |
| Row Of Chips | 228       | 11.56%  |
| Chip         | 14        | 0.71%   |
| Unknown      | 7         | 0.35%   |
| DIMM         | 6         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 917       | 42.45%  |
| 4096  | 726       | 33.61%  |
| 16384 | 268       | 12.41%  |
| 2048  | 178       | 8.24%   |
| 32768 | 46        | 2.13%   |
| 1024  | 24        | 1.11%   |
| 512   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 566       | 26.18%  |
| 1600    | 478       | 22.11%  |
| 3200    | 358       | 16.56%  |
| 2400    | 192       | 8.88%   |
| 2133    | 143       | 6.61%   |
| 1334    | 87        | 4.02%   |
| 1333    | 54        | 2.5%    |
| 3266    | 49        | 2.27%   |
| 4267    | 42        | 1.94%   |
| 1867    | 29        | 1.34%   |
| 4199    | 23        | 1.06%   |
| 1067    | 23        | 1.06%   |
| 667     | 19        | 0.88%   |
| Unknown | 18        | 0.83%   |
| 800     | 12        | 0.56%   |
| 4266    | 11        | 0.51%   |
| 975     | 9         | 0.42%   |
| 4800    | 7         | 0.32%   |
| 8400    | 6         | 0.28%   |
| 3733    | 6         | 0.28%   |
| 2048    | 6         | 0.28%   |
| 1066    | 6         | 0.28%   |
| 6400    | 5         | 0.23%   |
| 1866    | 3         | 0.14%   |
| 333     | 2         | 0.09%   |
| 65535   | 1         | 0.05%   |
| 3600    | 1         | 0.05%   |
| 2134    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |
| 933     | 1         | 0.05%   |
| 888     | 1         | 0.05%   |
| 666     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 32%     |
| Seiko Epson         | 5         | 20%     |
| Brother Industries  | 4         | 16%     |
| Samsung Electronics | 2         | 8%      |
| Canon               | 2         | 8%      |
| Xiaomi              | 1         | 4%      |
| Sagem               | 1         | 4%      |
| Kyocera             | 1         | 4%      |
| Dymo-CoStar         | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| HP ENVY 4520 series                                    | 2         | 8%      |
| Brother HL-L2300D series                               | 2         | 8%      |
| Xiaomi MiMouse 2                                       | 1         | 4%      |
| Seiko Epson Printer                                    | 1         | 4%      |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 4%      |
| Seiko Epson L365 Series                                | 1         | 4%      |
| Seiko Epson L355 Series                                | 1         | 4%      |
| Seiko Epson ET-2710 Series                             | 1         | 4%      |
| Samsung ML-1865                                        | 1         | 4%      |
| Samsung CLX-3180 Series                                | 1         | 4%      |
| Sagem Laser Pro LL                                     | 1         | 4%      |
| Kyocera FS-1030D printer                               | 1         | 4%      |
| HP Officejet 4500 G510g-m                              | 1         | 4%      |
| HP LaserJet P1102                                      | 1         | 4%      |
| HP Ink Tank Wireless 410 series                        | 1         | 4%      |
| HP Ink Tank 310 series                                 | 1         | 4%      |
| HP DeskJet 2700 series                                 | 1         | 4%      |
| HP DeskJet 1110 series                                 | 1         | 4%      |
| Dymo-CoStar DYMO LabelWriter 450 Twin Turbo            | 1         | 4%      |
| Canon TS300 series                                     | 1         | 4%      |
| Canon TR4500 series                                    | 1         | 4%      |
| Brother QL-500 label printer                           | 1         | 4%      |
| Brother MFC-L2710DW series                             | 1         | 4%      |

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
| Chicony Electronics                    | 675       | 23.95%  |
| IMC Networks                           | 400       | 14.19%  |
| Realtek Semiconductor                  | 245       | 8.69%   |
| Acer                                   | 245       | 8.69%   |
| Microdia                               | 216       | 7.67%   |
| Sunplus Innovation Technology          | 151       | 5.36%   |
| Quanta                                 | 149       | 5.29%   |
| Cheng Uei Precision Industry (Foxlink) | 115       | 4.08%   |
| Syntek                                 | 91        | 3.23%   |
| Lite-On Technology                     | 90        | 3.19%   |
| Suyin                                  | 79        | 2.8%    |
| Apple                                  | 55        | 1.95%   |
| Silicon Motion                         | 50        | 1.77%   |
| Logitech                               | 38        | 1.35%   |
| Alcor Micro                            | 30        | 1.06%   |
| Luxvisions Innotech Limited            | 28        | 0.99%   |
| Samsung Electronics                    | 18        | 0.64%   |
| Ricoh                                  | 18        | 0.64%   |
| Lenovo                                 | 13        | 0.46%   |
| Microsoft                              | 10        | 0.35%   |
| Importek                               | 10        | 0.35%   |
| Primax Electronics                     | 9         | 0.32%   |
| Sonix Technology                       | 7         | 0.25%   |
| DigiTech                               | 6         | 0.21%   |
| Denron                                 | 5         | 0.18%   |
| ALi                                    | 5         | 0.18%   |
| Z-Star Microelectronics                | 4         | 0.14%   |
| OmniVision Technologies                | 4         | 0.14%   |
| Intel                                  | 4         | 0.14%   |
| Genesys Logic                          | 4         | 0.14%   |
| GEMBIRD                                | 3         | 0.11%   |
| Creative Technology                    | 3         | 0.11%   |
| ARC International                      | 3         | 0.11%   |
| USB Camera CS                          | 2         | 0.07%   |
| Unknown                                | 2         | 0.07%   |
| SunplusIT                              | 2         | 0.07%   |
| MacroSilicon                           | 2         | 0.07%   |
| LG Electronics                         | 2         | 0.07%   |
| KYE Systems (Mouse Systems)            | 2         | 0.07%   |
| icSpring                               | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 173       | 6.11%   |
| IMC Networks Integrated Camera                          | 126       | 4.45%   |
| Microdia Integrated_Webcam_HD                           | 110       | 3.88%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 100       | 3.53%   |
| Realtek Integrated_Webcam_HD                            | 85        | 3%      |
| Chicony HD Webcam                                       | 78        | 2.75%   |
| Acer Integrated Camera                                  | 76        | 2.68%   |
| Syntek Integrated Camera                                | 60        | 2.12%   |
| Sunplus Integrated_Webcam_HD                            | 48        | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 39        | 1.38%   |
| Lite-On Integrated Camera                               | 33        | 1.16%   |
| Acer HD Webcam                                          | 30        | 1.06%   |
| Quanta HP TrueVision HD Camera                          | 26        | 0.92%   |
| Chicony USB2.0 Camera                                   | 26        | 0.92%   |
| Chicony HP HD Camera                                    | 26        | 0.92%   |
| Acer Lenovo EasyCamera                                  | 26        | 0.92%   |
| Lite-On HP HD Camera                                    | 24        | 0.85%   |
| Quanta HD User Facing                                   | 23        | 0.81%   |
| Quanta HD Webcam                                        | 22        | 0.78%   |
| Microdia Integrated Webcam                              | 22        | 0.78%   |
| Acer SunplusIT Integrated Camera                        | 22        | 0.78%   |
| Chicony USB2.0 HD UVC WebCam                            | 21        | 0.74%   |
| Chicony Lenovo EasyCamera                               | 21        | 0.74%   |
| Chicony EasyCamera                                      | 20        | 0.71%   |
| Sunplus HD WebCam                                       | 19        | 0.67%   |
| Realtek USB2.0 HD UVC WebCam                            | 19        | 0.67%   |
| Syntek Lenovo EasyCamera                                | 18        | 0.64%   |
| Samsung Galaxy A5 (MTP)                                 | 18        | 0.64%   |
| Realtek USB Camera                                      | 18        | 0.64%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 18        | 0.64%   |
| Chicony HD User Facing                                  | 18        | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 18        | 0.64%   |
| Acer BisonCam, NB Pro                                   | 18        | 0.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 17        | 0.6%    |
| Chicony Integrated Camera (1280x720@30)                 | 17        | 0.6%    |
| Chicony HP Truevision HD                                | 17        | 0.6%    |
| Apple iPhone5/5C/5S/6                                   | 17        | 0.6%    |
| Acer EasyCamera                                         | 17        | 0.6%    |
| Realtek Integrated Webcam                               | 16        | 0.56%   |
| Realtek HD WebCam                                       | 16        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 204       | 32.38%  |
| Synaptics                  | 162       | 25.71%  |
| Shenzhen Goodix Technology | 128       | 20.32%  |
| Elan Microelectronics      | 49        | 7.78%   |
| LighTuning Technology      | 29        | 4.6%    |
| Upek                       | 26        | 4.13%   |
| AuthenTec                  | 17        | 2.7%    |
| STMicroelectronics         | 7         | 1.11%   |
| Samsung Electronics        | 3         | 0.48%   |
| Focal-systems.Corp         | 2         | 0.32%   |
| DigitalPersona             | 2         | 0.32%   |
| HOLTEK                     | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 65        | 10.32%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 51        | 8.1%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                                         | 38        | 6.03%   |
| Unknown                                                                    | 38        | 6.03%   |
| Elan ELAN:Fingerprint                                                      | 34        | 5.4%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 4.76%   |
| Shenzhen Goodix FingerPrint                                                | 25        | 3.97%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.81%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 19        | 3.02%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 3.02%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 19        | 3.02%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 2.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 15        | 2.38%   |
| Elan ELAN:ARM-M4                                                           | 14        | 2.22%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 13        | 2.06%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 2.06%   |
| Validity Sensors VFS491                                                    | 12        | 1.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.9%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.75%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 1.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.27%   |
| Synaptics  WBDI                                                            | 8         | 1.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 1.27%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.11%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.95%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.79%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 0.63%   |
| Synaptics WBDI Device                                                      | 4         | 0.63%   |
| AuthenTec AES2810                                                          | 4         | 0.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 0.63%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.48%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.48%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.32%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.32%   |
| Samsung Fingerprint Device                                                 | 2         | 0.32%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.32%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 72        | 36%     |
| Alcor Micro              | 68        | 34%     |
| O2 Micro                 | 15        | 7.5%    |
| Lenovo                   | 15        | 7.5%    |
| Upek                     | 14        | 7%      |
| Yubico.com               | 8         | 4%      |
| Gemalto (was Gemplus)    | 3         | 1.5%    |
| Reiner SCT Kartensysteme | 1         | 0.5%    |
| OmniKey                  | 1         | 0.5%    |
| Hewlett-Packard          | 1         | 0.5%    |
| Clay Logic               | 1         | 0.5%    |
| C3PO                     | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 68        | 34%     |
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 15%     |
| Broadcom 5880                                                                | 20        | 10%     |
| Lenovo Integrated Smart Card Reader                                          | 15        | 7.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 7%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 14        | 7%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 6%      |
| Broadcom 58200                                                               | 10        | 5%      |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 3.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.5%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.5%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.5%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.5%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.5%    |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.5%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.5%    |
| C3PO USB SMART CARD READER                                                   | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1878      | 59.64%  |
| 1     | 1011      | 32.11%  |
| 2     | 238       | 7.56%   |
| 3     | 20        | 0.64%   |
| 4     | 2         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 617       | 41.05%  |
| Graphics card            | 299       | 19.89%  |
| Chipcard                 | 177       | 11.78%  |
| Net/wireless             | 121       | 8.05%   |
| Multimedia controller    | 114       | 7.58%   |
| Camera                   | 51        | 3.39%   |
| Net/ethernet             | 42        | 2.79%   |
| Bluetooth                | 32        | 2.13%   |
| Storage                  | 16        | 1.06%   |
| Card reader              | 10        | 0.67%   |
| Sound                    | 8         | 0.53%   |
| Communication controller | 6         | 0.4%    |
| Modem                    | 4         | 0.27%   |
| Network                  | 3         | 0.2%    |
| Dvb card                 | 2         | 0.13%   |
| Storage/nvme             | 1         | 0.07%   |


Elementary 7 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Elementary 7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_7/Desktop/README.md) and [notebooks](/Dist/Elementary_7/Notebook/README.md).

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

Total: 305

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro6,2               | Notebook    | [7c62a05800](https://linux-hardware.org/?probe=7c62a05800) | Aug 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [80f2f711d8](https://linux-hardware.org/?probe=80f2f711d8) | Aug 10, 2023 |
| HP            | ProBook 4310s               | Notebook    | [ac0c1be078](https://linux-hardware.org/?probe=ac0c1be078) | Aug 09, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [04a319c904](https://linux-hardware.org/?probe=04a319c904) | Aug 09, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6165a2d50e](https://linux-hardware.org/?probe=6165a2d50e) | Aug 08, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [663f9e62db](https://linux-hardware.org/?probe=663f9e62db) | Aug 08, 2023 |
| Acer          | Aspire TC-710 V:1.1         | Desktop     | [f6af1382fd](https://linux-hardware.org/?probe=f6af1382fd) | Aug 08, 2023 |
| HP            | G60                         | Notebook    | [7f3b9aec85](https://linux-hardware.org/?probe=7f3b9aec85) | Aug 07, 2023 |
| Lenovo        | ThinkPad X201 Tablet 298... | Notebook    | [7132bbeb85](https://linux-hardware.org/?probe=7132bbeb85) | Aug 06, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [09ae57bb9a](https://linux-hardware.org/?probe=09ae57bb9a) | Aug 05, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [21460cac53](https://linux-hardware.org/?probe=21460cac53) | Aug 05, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [9d5490fb82](https://linux-hardware.org/?probe=9d5490fb82) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2b8f90f79d](https://linux-hardware.org/?probe=2b8f90f79d) | Aug 03, 2023 |
| Acer          | Predator G3-571             | Notebook    | [fc950e8651](https://linux-hardware.org/?probe=fc950e8651) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2f4ed3cb1f](https://linux-hardware.org/?probe=2f4ed3cb1f) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| SHENZHEN Y... | A8S PRO                     | Notebook    | [829a4178a5](https://linux-hardware.org/?probe=829a4178a5) | Jul 30, 2023 |
| Acer          | Spin SP314-53GN             | Convertible | [92acef890a](https://linux-hardware.org/?probe=92acef890a) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c7572ce663](https://linux-hardware.org/?probe=c7572ce663) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8ac9af1db8](https://linux-hardware.org/?probe=8ac9af1db8) | Jul 29, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [36dda4bbfa](https://linux-hardware.org/?probe=36dda4bbfa) | Jul 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [10fa87c167](https://linux-hardware.org/?probe=10fa87c167) | Jul 28, 2023 |
| SHENZHEN Y... | A8S PRO                     | Notebook    | [08a6feda0e](https://linux-hardware.org/?probe=08a6feda0e) | Jul 28, 2023 |
| ASRock        | X570 Extreme4               | Desktop     | [5b1a74fc68](https://linux-hardware.org/?probe=5b1a74fc68) | Jul 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c2e02d1490](https://linux-hardware.org/?probe=c2e02d1490) | Jul 24, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [20ec4f50dc](https://linux-hardware.org/?probe=20ec4f50dc) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a5359c62e0](https://linux-hardware.org/?probe=a5359c62e0) | Jul 20, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [6c258335bb](https://linux-hardware.org/?probe=6c258335bb) | Jul 20, 2023 |
| Alienware     | m15 R6                      | Notebook    | [93d5e98358](https://linux-hardware.org/?probe=93d5e98358) | Jul 20, 2023 |
| HP            | Notebook                    | Notebook    | [2ccf016245](https://linux-hardware.org/?probe=2ccf016245) | Jul 19, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [a7dc2996b6](https://linux-hardware.org/?probe=a7dc2996b6) | Jul 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [7dd13cea49](https://linux-hardware.org/?probe=7dd13cea49) | Jul 17, 2023 |
| Google        | Phaser360                   | Notebook    | [1e66458514](https://linux-hardware.org/?probe=1e66458514) | Jul 17, 2023 |
| HP            | ENVY 15                     | Notebook    | [a173db4ea1](https://linux-hardware.org/?probe=a173db4ea1) | Jul 17, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | Notebook    | [2c05f1a964](https://linux-hardware.org/?probe=2c05f1a964) | Jul 16, 2023 |
| Acer          | Aspire TC-380               | Desktop     | [94f5f10ff2](https://linux-hardware.org/?probe=94f5f10ff2) | Jul 14, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [f0736c39fe](https://linux-hardware.org/?probe=f0736c39fe) | Jul 13, 2023 |
| Wortmann      | TERRA_PC                    | Desktop     | [60ece53188](https://linux-hardware.org/?probe=60ece53188) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [74420b09b7](https://linux-hardware.org/?probe=74420b09b7) | Jul 12, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3532802c06](https://linux-hardware.org/?probe=3532802c06) | Jul 12, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [4e8926a95b](https://linux-hardware.org/?probe=4e8926a95b) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1a0add8887](https://linux-hardware.org/?probe=1a0add8887) | Jul 11, 2023 |
| HP            | ENVY 15                     | Notebook    | [3ccdaf4d4e](https://linux-hardware.org/?probe=3ccdaf4d4e) | Jul 10, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [784f886357](https://linux-hardware.org/?probe=784f886357) | Jul 10, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [881754a433](https://linux-hardware.org/?probe=881754a433) | Jul 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [8877b51b89](https://linux-hardware.org/?probe=8877b51b89) | Jul 08, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [bb065938a5](https://linux-hardware.org/?probe=bb065938a5) | Jul 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ee299280f8](https://linux-hardware.org/?probe=ee299280f8) | Jul 07, 2023 |
| Dell          | Latitude E7270              | Notebook    | [406e4a918b](https://linux-hardware.org/?probe=406e4a918b) | Jul 06, 2023 |
| Intel Clie... | LAPBC710                    | Notebook    | [fd97a27365](https://linux-hardware.org/?probe=fd97a27365) | Jul 06, 2023 |
| Alienware     | 07HV66 A00                  | Desktop     | [41d4d9ae84](https://linux-hardware.org/?probe=41d4d9ae84) | Jul 05, 2023 |
| Alienware     | 07HV66 A00                  | Desktop     | [2712110727](https://linux-hardware.org/?probe=2712110727) | Jul 05, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [9c0f0d40b9](https://linux-hardware.org/?probe=9c0f0d40b9) | Jul 05, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e4a653435](https://linux-hardware.org/?probe=2e4a653435) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| GPD           | MicroPC                     | Notebook    | [f666f4c574](https://linux-hardware.org/?probe=f666f4c574) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 23254W5       | Notebook    | [5842896b76](https://linux-hardware.org/?probe=5842896b76) | Jul 03, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [6e52890194](https://linux-hardware.org/?probe=6e52890194) | Jul 02, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [8bfe14749f](https://linux-hardware.org/?probe=8bfe14749f) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2349OB6       | Notebook    | [f2f66bb9d0](https://linux-hardware.org/?probe=f2f66bb9d0) | Jun 29, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [d73388baab](https://linux-hardware.org/?probe=d73388baab) | Jun 28, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [afc9f56d8d](https://linux-hardware.org/?probe=afc9f56d8d) | Jun 28, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [38ae545c1c](https://linux-hardware.org/?probe=38ae545c1c) | Jun 23, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [a75e6d35da](https://linux-hardware.org/?probe=a75e6d35da) | Jun 21, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [4f5e2f9201](https://linux-hardware.org/?probe=4f5e2f9201) | Jun 21, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [293b8783a3](https://linux-hardware.org/?probe=293b8783a3) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [2f452cfce0](https://linux-hardware.org/?probe=2f452cfce0) | Jun 20, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [f49534dfa4](https://linux-hardware.org/?probe=f49534dfa4) | Jun 19, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [a57885e16c](https://linux-hardware.org/?probe=a57885e16c) | Jun 18, 2023 |
| Pegatron      | IPMIP-GS                    | Desktop     | [fb51893272](https://linux-hardware.org/?probe=fb51893272) | Jun 15, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [782fa74afe](https://linux-hardware.org/?probe=782fa74afe) | Jun 14, 2023 |
| Razer         | Blade Stealth               | Notebook    | [f218e04a1c](https://linux-hardware.org/?probe=f218e04a1c) | Jun 14, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d675395634](https://linux-hardware.org/?probe=d675395634) | Jun 11, 2023 |
| ECS           | G41T-M                      | Desktop     | [2c148573fc](https://linux-hardware.org/?probe=2c148573fc) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [08114e8a97](https://linux-hardware.org/?probe=08114e8a97) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [93555cfd25](https://linux-hardware.org/?probe=93555cfd25) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2e6d82c14f](https://linux-hardware.org/?probe=2e6d82c14f) | Jun 10, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [604f40e700](https://linux-hardware.org/?probe=604f40e700) | Jun 09, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d001c4cf1c](https://linux-hardware.org/?probe=d001c4cf1c) | Jun 09, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d487214e2a](https://linux-hardware.org/?probe=d487214e2a) | Jun 08, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [ddefeff960](https://linux-hardware.org/?probe=ddefeff960) | Jun 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [6c62565787](https://linux-hardware.org/?probe=6c62565787) | Jun 07, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [b2281ad2cb](https://linux-hardware.org/?probe=b2281ad2cb) | Jun 06, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [77fe6db865](https://linux-hardware.org/?probe=77fe6db865) | Jun 06, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [1ebf23281e](https://linux-hardware.org/?probe=1ebf23281e) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [532dea434a](https://linux-hardware.org/?probe=532dea434a) | Jun 02, 2023 |
| HP            | G62                         | Notebook    | [f2600c2f4b](https://linux-hardware.org/?probe=f2600c2f4b) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [71208c2344](https://linux-hardware.org/?probe=71208c2344) | Jun 01, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [827e0203ac](https://linux-hardware.org/?probe=827e0203ac) | May 31, 2023 |
| Gigabyte      | GA-E6010N                   | Desktop     | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
| ASUSTek       | X550WA                      | Notebook    | [864236b0c9](https://linux-hardware.org/?probe=864236b0c9) | May 29, 2023 |
| PCBOX         | Kant                        | Notebook    | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [16b9dfbbe0](https://linux-hardware.org/?probe=16b9dfbbe0) | May 29, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [35d14ed328](https://linux-hardware.org/?probe=35d14ed328) | May 29, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [36a3563566](https://linux-hardware.org/?probe=36a3563566) | May 29, 2023 |
| Chuwi         | UBook Pro                   | Tablet      | [190fe84e14](https://linux-hardware.org/?probe=190fe84e14) | May 27, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e29fb14e81](https://linux-hardware.org/?probe=e29fb14e81) | May 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [84d0d9807f](https://linux-hardware.org/?probe=84d0d9807f) | May 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [124c8183a8](https://linux-hardware.org/?probe=124c8183a8) | May 26, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| Dell          | Precision 5530              | Notebook    | [702b4d7914](https://linux-hardware.org/?probe=702b4d7914) | May 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Unknown       | Unknown                     | Tablet      | [8a83b799d5](https://linux-hardware.org/?probe=8a83b799d5) | May 24, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| HP            | ProBook 4310s               | Notebook    | [1a32d434c0](https://linux-hardware.org/?probe=1a32d434c0) | May 21, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [7f15c1b9e3](https://linux-hardware.org/?probe=7f15c1b9e3) | May 21, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [ff730fcbf6](https://linux-hardware.org/?probe=ff730fcbf6) | May 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [73d62695e4](https://linux-hardware.org/?probe=73d62695e4) | May 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [56aa17165e](https://linux-hardware.org/?probe=56aa17165e) | May 18, 2023 |
| HP            | ProBook 4310s               | Notebook    | [dfcb51e697](https://linux-hardware.org/?probe=dfcb51e697) | May 17, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3776285fc1](https://linux-hardware.org/?probe=3776285fc1) | May 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [155b921e10](https://linux-hardware.org/?probe=155b921e10) | May 13, 2023 |
| HP            | 1998                        | Desktop     | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [81e3161a34](https://linux-hardware.org/?probe=81e3161a34) | May 11, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [ea0b55ed61](https://linux-hardware.org/?probe=ea0b55ed61) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [df06b3c5b3](https://linux-hardware.org/?probe=df06b3c5b3) | May 07, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [bac71eb24d](https://linux-hardware.org/?probe=bac71eb24d) | May 06, 2023 |
| Lenovo        | ThinkPad P51s 20HB001TUS    | Notebook    | [eac4ebdef0](https://linux-hardware.org/?probe=eac4ebdef0) | May 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [834d2304aa](https://linux-hardware.org/?probe=834d2304aa) | May 06, 2023 |
| Intel         | JSL MRD                     | Desktop     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [6a80029392](https://linux-hardware.org/?probe=6a80029392) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [fe61386871](https://linux-hardware.org/?probe=fe61386871) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [764f38bb65](https://linux-hardware.org/?probe=764f38bb65) | May 05, 2023 |
| Dell          | 02N3WF A02                  | Desktop     | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c5927045a3](https://linux-hardware.org/?probe=c5927045a3) | May 04, 2023 |
| HP            | 1998                        | Desktop     | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [97acececd3](https://linux-hardware.org/?probe=97acececd3) | Apr 28, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [c188ae4d7d](https://linux-hardware.org/?probe=c188ae4d7d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [2a9fcae8c3](https://linux-hardware.org/?probe=2a9fcae8c3) | Apr 28, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [87c8761eff](https://linux-hardware.org/?probe=87c8761eff) | Apr 27, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [53dd8334ac](https://linux-hardware.org/?probe=53dd8334ac) | Apr 26, 2023 |
| HP            | 8055                        | Desktop     | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| ASRock        | B660M-C                     | Desktop     | [849fc5d462](https://linux-hardware.org/?probe=849fc5d462) | Apr 25, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [8fd18554d1](https://linux-hardware.org/?probe=8fd18554d1) | Apr 24, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | Desktop     | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| Dell          | Latitude E4300              | Notebook    | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [763953fb60](https://linux-hardware.org/?probe=763953fb60) | Apr 22, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [50a18b5e94](https://linux-hardware.org/?probe=50a18b5e94) | Apr 19, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d60e2b7da](https://linux-hardware.org/?probe=4d60e2b7da) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [94bf014457](https://linux-hardware.org/?probe=94bf014457) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [2ebc6a2f61](https://linux-hardware.org/?probe=2ebc6a2f61) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ff6dbdcc10](https://linux-hardware.org/?probe=ff6dbdcc10) | Apr 15, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845e7bfdd1](https://linux-hardware.org/?probe=845e7bfdd1) | Apr 15, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [936a7d1fe3](https://linux-hardware.org/?probe=936a7d1fe3) | Apr 15, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4c6427b3fc](https://linux-hardware.org/?probe=4c6427b3fc) | Apr 14, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e311d21def](https://linux-hardware.org/?probe=e311d21def) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [c750ece414](https://linux-hardware.org/?probe=c750ece414) | Apr 12, 2023 |
| Dell          | Latitude E5570              | Notebook    | [81eaf54f19](https://linux-hardware.org/?probe=81eaf54f19) | Apr 07, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [5c12ed53b7](https://linux-hardware.org/?probe=5c12ed53b7) | Apr 05, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [6896e5d9e2](https://linux-hardware.org/?probe=6896e5d9e2) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [d3bd81c4fd](https://linux-hardware.org/?probe=d3bd81c4fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [f7f207f61c](https://linux-hardware.org/?probe=f7f207f61c) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e06d57c27a](https://linux-hardware.org/?probe=e06d57c27a) | Apr 01, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d4c718bdab](https://linux-hardware.org/?probe=d4c718bdab) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [448d1a491c](https://linux-hardware.org/?probe=448d1a491c) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| Dell          | Latitude E7440              | Notebook    | [1159c854cd](https://linux-hardware.org/?probe=1159c854cd) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a9a8004509](https://linux-hardware.org/?probe=a9a8004509) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1dccfbe9f4](https://linux-hardware.org/?probe=1dccfbe9f4) | Mar 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d714c46c4f](https://linux-hardware.org/?probe=d714c46c4f) | Mar 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [5590ec1365](https://linux-hardware.org/?probe=5590ec1365) | Mar 28, 2023 |
| AZW           | U59                         | Desktop     | [7674bb8dc9](https://linux-hardware.org/?probe=7674bb8dc9) | Mar 27, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [39995c1c00](https://linux-hardware.org/?probe=39995c1c00) | Mar 24, 2023 |
| Dell          | Latitude E7440              | Notebook    | [1a986dbeb8](https://linux-hardware.org/?probe=1a986dbeb8) | Mar 24, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [df318ed208](https://linux-hardware.org/?probe=df318ed208) | Mar 21, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Latitude E5570              | Notebook    | [a15d1b43ca](https://linux-hardware.org/?probe=a15d1b43ca) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dd07b0c3b3](https://linux-hardware.org/?probe=dd07b0c3b3) | Mar 17, 2023 |
| Dell          | G3 3590                     | Notebook    | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [03e5d43f27](https://linux-hardware.org/?probe=03e5d43f27) | Mar 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [4c49d73583](https://linux-hardware.org/?probe=4c49d73583) | Mar 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [c6ff6d14a0](https://linux-hardware.org/?probe=c6ff6d14a0) | Mar 15, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [28f8273eb5](https://linux-hardware.org/?probe=28f8273eb5) | Mar 15, 2023 |
| HP            | 805A                        | Desktop     | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | Notebook    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [023f42d6d1](https://linux-hardware.org/?probe=023f42d6d1) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK A359               | Notebook    | [0fa1ebbc11](https://linux-hardware.org/?probe=0fa1ebbc11) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK A359               | Notebook    | [f977012127](https://linux-hardware.org/?probe=f977012127) | Mar 11, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [fce6120754](https://linux-hardware.org/?probe=fce6120754) | Mar 11, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [a4ba2ff90e](https://linux-hardware.org/?probe=a4ba2ff90e) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | Notebook    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Sony          | VPCEH2C5E                   | Notebook    | [adf4a69310](https://linux-hardware.org/?probe=adf4a69310) | Mar 07, 2023 |
| Sony          | VPCEH2C5E                   | Notebook    | [9e5b625dda](https://linux-hardware.org/?probe=9e5b625dda) | Mar 07, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [3547dd712b](https://linux-hardware.org/?probe=3547dd712b) | Mar 07, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [4ecfeecd31](https://linux-hardware.org/?probe=4ecfeecd31) | Mar 06, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| Microsoft     | Surface Book                | Tablet      | [cc3ad3e0d2](https://linux-hardware.org/?probe=cc3ad3e0d2) | Mar 02, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d58385d1e6](https://linux-hardware.org/?probe=d58385d1e6) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [e189c60b09](https://linux-hardware.org/?probe=e189c60b09) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3883ba28c7](https://linux-hardware.org/?probe=3883ba28c7) | Mar 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1c5f8fef49](https://linux-hardware.org/?probe=1c5f8fef49) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [216ad20179](https://linux-hardware.org/?probe=216ad20179) | Feb 28, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [371a95fb3d](https://linux-hardware.org/?probe=371a95fb3d) | Feb 28, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [e331c5e257](https://linux-hardware.org/?probe=e331c5e257) | Feb 27, 2023 |
| Acer          | Predator G3620              | Desktop     | [72f3382b60](https://linux-hardware.org/?probe=72f3382b60) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [73c974942f](https://linux-hardware.org/?probe=73c974942f) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a66f75c107](https://linux-hardware.org/?probe=a66f75c107) | Feb 26, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [ce9dda227f](https://linux-hardware.org/?probe=ce9dda227f) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [b815c24c07](https://linux-hardware.org/?probe=b815c24c07) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [e578b951f9](https://linux-hardware.org/?probe=e578b951f9) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [0dc5add67b](https://linux-hardware.org/?probe=0dc5add67b) | Feb 24, 2023 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [b101883e65](https://linux-hardware.org/?probe=b101883e65) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [6db3a90234](https://linux-hardware.org/?probe=6db3a90234) | Feb 24, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [0a3d750f36](https://linux-hardware.org/?probe=0a3d750f36) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [7ee9e59831](https://linux-hardware.org/?probe=7ee9e59831) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [2751aac3e0](https://linux-hardware.org/?probe=2751aac3e0) | Feb 16, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [76ab936a75](https://linux-hardware.org/?probe=76ab936a75) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [e0f89bbca1](https://linux-hardware.org/?probe=e0f89bbca1) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| HP            | 550                         | Notebook    | [81b67f211d](https://linux-hardware.org/?probe=81b67f211d) | Feb 15, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [150c1de326](https://linux-hardware.org/?probe=150c1de326) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e8a460c42c](https://linux-hardware.org/?probe=e8a460c42c) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [a92df0196e](https://linux-hardware.org/?probe=a92df0196e) | Feb 15, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| HP            | 805D                        | Desktop     | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [f22c83d683](https://linux-hardware.org/?probe=f22c83d683) | Feb 14, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [12431d8083](https://linux-hardware.org/?probe=12431d8083) | Feb 14, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f0899499e5](https://linux-hardware.org/?probe=f0899499e5) | Feb 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [537d29b0d5](https://linux-hardware.org/?probe=537d29b0d5) | Feb 12, 2023 |
| Acer          | Extensa 5230                | Notebook    | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [b906f960a0](https://linux-hardware.org/?probe=b906f960a0) | Feb 08, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [1e6a345b00](https://linux-hardware.org/?probe=1e6a345b00) | Feb 07, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [c3607bb4c2](https://linux-hardware.org/?probe=c3607bb4c2) | Feb 07, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [07ea9d3c2f](https://linux-hardware.org/?probe=07ea9d3c2f) | Feb 06, 2023 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [30e2a88930](https://linux-hardware.org/?probe=30e2a88930) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | Notebook    | [10f8560601](https://linux-hardware.org/?probe=10f8560601) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | Notebook    | [be37cc70f5](https://linux-hardware.org/?probe=be37cc70f5) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [8d67e1438d](https://linux-hardware.org/?probe=8d67e1438d) | Feb 05, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8bdb86b164](https://linux-hardware.org/?probe=8bdb86b164) | Feb 04, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [3786e7a211](https://linux-hardware.org/?probe=3786e7a211) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [8aa57f1d6d](https://linux-hardware.org/?probe=8aa57f1d6d) | Feb 03, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [78919f6127](https://linux-hardware.org/?probe=78919f6127) | Feb 03, 2023 |
| Alienware     | x17 R2                      | Notebook    | [474a70c148](https://linux-hardware.org/?probe=474a70c148) | Feb 03, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [42c3899a37](https://linux-hardware.org/?probe=42c3899a37) | Feb 02, 2023 |
| Sony          | SVF1521O4E                  | Notebook    | [e2d47879d4](https://linux-hardware.org/?probe=e2d47879d4) | Feb 02, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [fdf7b5e80e](https://linux-hardware.org/?probe=fdf7b5e80e) | Feb 02, 2023 |
| Lenovo        | ThinkPad X230 23259S9       | Notebook    | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [1ce7db78c1](https://linux-hardware.org/?probe=1ce7db78c1) | Feb 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c2a4529e33](https://linux-hardware.org/?probe=c2a4529e33) | Jan 30, 2023 |
| Star Labs     | StarBook                    | Notebook    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Unknown       | HX90                        | Desktop     | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-58-generic      | 56        | 25.45%  |
| 5.19.0-41-generic      | 23        | 10.45%  |
| 5.19.0-35-generic      | 23        | 10.45%  |
| 5.19.0-32-generic      | 22        | 10%     |
| 5.19.0-46-generic      | 21        | 9.55%   |
| 5.19.0-38-generic      | 16        | 7.27%   |
| 5.19.0-43-generic      | 13        | 5.91%   |
| 5.15.0-60-generic      | 9         | 4.09%   |
| 6.2.0-26-generic       | 8         | 3.64%   |
| 5.19.0-40-generic      | 6         | 2.73%   |
| 5.19.0-50-generic      | 5         | 2.27%   |
| 5.19.0-42-generic      | 5         | 2.27%   |
| 5.19.0-45-generic      | 3         | 1.36%   |
| 5.15.0-56-generic      | 2         | 0.91%   |
| 6.4.5-x64v3-xanmod1    | 1         | 0.45%   |
| 6.2.8-3-liquorix-amd64 | 1         | 0.45%   |
| 6.2.7-060207-generic   | 1         | 0.45%   |
| 6.2.2-surface          | 1         | 0.45%   |
| 6.2.14-surface         | 1         | 0.45%   |
| 6.1.9-060109-generic   | 1         | 0.45%   |
| 6.1.6-060106-generic   | 1         | 0.45%   |
| 6.1.0-1013-oem         | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 130       | 61.03%  |
| 5.15.0  | 67        | 31.46%  |
| 6.2.0   | 8         | 3.76%   |
| 6.4.5   | 1         | 0.47%   |
| 6.2.8   | 1         | 0.47%   |
| 6.2.7   | 1         | 0.47%   |
| 6.2.2   | 1         | 0.47%   |
| 6.2.14  | 1         | 0.47%   |
| 6.1.9   | 1         | 0.47%   |
| 6.1.6   | 1         | 0.47%   |
| 6.1.0   | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 130       | 61.32%  |
| 5.15    | 67        | 31.6%   |
| 6.2     | 11        | 5.19%   |
| 6.1     | 3         | 1.42%   |
| 6.4     | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 209       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 209       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 209       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 173       | 82.78%  |
| LightDM | 36        | 17.22%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 89        | 42.38%  |
| de_DE | 32        | 15.24%  |
| es_ES | 19        | 9.05%   |
| ru_RU | 18        | 8.57%   |
| fr_FR | 7         | 3.33%   |
| pl_PL | 5         | 2.38%   |
| it_IT | 5         | 2.38%   |
| en_GB | 5         | 2.38%   |
| sv_SE | 4         | 1.9%    |
| pt_BR | 4         | 1.9%    |
| en_AU | 4         | 1.9%    |
| tr_TR | 2         | 0.95%   |
| pt_PT | 2         | 0.95%   |
| nl_NL | 2         | 0.95%   |
| nb_NO | 2         | 0.95%   |
| el_GR | 2         | 0.95%   |
| uk_UA | 1         | 0.48%   |
| sk_SK | 1         | 0.48%   |
| ja_JP | 1         | 0.48%   |
| hu_HU | 1         | 0.48%   |
| fi_FI | 1         | 0.48%   |
| en_CA | 1         | 0.48%   |
| da_DK | 1         | 0.48%   |
| cs_CZ | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 185       | 88.52%  |
| EFI  | 24        | 11.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 198       | 94.29%  |
| Tmpfs   | 6         | 2.86%   |
| Btrfs   | 3         | 1.43%   |
| Xfs     | 2         | 0.95%   |
| Overlay | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 173       | 82.78%  |
| GPT     | 29        | 13.88%  |
| MBR     | 7         | 3.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 207       | 99.04%  |
| Yes       | 2         | 0.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 197       | 94.26%  |
| Yes       | 12        | 5.74%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 32        | 15.31%  |
| Apple                       | 31        | 14.83%  |
| Lenovo                      | 27        | 12.92%  |
| ASUSTek Computer            | 27        | 12.92%  |
| Dell                        | 16        | 7.66%   |
| Acer                        | 13        | 6.22%   |
| MSI                         | 10        | 4.78%   |
| Gigabyte Technology         | 8         | 3.83%   |
| HUAWEI                      | 5         | 2.39%   |
| Toshiba                     | 3         | 1.44%   |
| Fujitsu                     | 3         | 1.44%   |
| ASRock                      | 3         | 1.44%   |
| Alienware                   | 3         | 1.44%   |
| Unknown                     | 3         | 1.44%   |
| Sony                        | 2         | 0.96%   |
| Pegatron                    | 2         | 0.96%   |
| HONOR                       | 2         | 0.96%   |
| Foxconn                     | 2         | 0.96%   |
| Wortmann AG                 | 1         | 0.48%   |
| Star Labs                   | 1         | 0.48%   |
| SHENZHEN YOUDISI E-COMMERCE | 1         | 0.48%   |
| Samsung Electronics         | 1         | 0.48%   |
| Razer                       | 1         | 0.48%   |
| PCBOX                       | 1         | 0.48%   |
| Microsoft                   | 1         | 0.48%   |
| MACHINIST                   | 1         | 0.48%   |
| Inventec                    | 1         | 0.48%   |
| Intel                       | 1         | 0.48%   |
| GPU Company                 | 1         | 0.48%   |
| GPD                         | 1         | 0.48%   |
| Google                      | 1         | 0.48%   |
| ECS                         | 1         | 0.48%   |
| Clevo                       | 1         | 0.48%   |
| Chuwi                       | 1         | 0.48%   |
| AZW                         | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                        | 3         | 1.44%   |
| Unknown                                    | 3         | 1.44%   |
| HUAWEI BOD-WXX9                            | 2         | 0.96%   |
| HP 255 G7 Notebook PC                      | 2         | 0.96%   |
| ASUS H110M-A/M.2                           | 2         | 0.96%   |
| Apple MacBookPro9,2                        | 2         | 0.96%   |
| Apple MacBookPro11,3                       | 2         | 0.96%   |
| Apple iMac7,1                              | 2         | 0.96%   |
| Apple iMac12,1                             | 2         | 0.96%   |
| Apple iMac11,2                             | 2         | 0.96%   |
| Wortmann AG TERRA_PC                       | 1         | 0.48%   |
| Toshiba TECRA Z40-C                        | 1         | 0.48%   |
| Toshiba TECRA R850                         | 1         | 0.48%   |
| Toshiba Satellite C660                     | 1         | 0.48%   |
| Star Labs StarBook                         | 1         | 0.48%   |
| Sony VPCEH2C5E                             | 1         | 0.48%   |
| Sony SVF1521O4E                            | 1         | 0.48%   |
| SHENZHEN YOUDISI E-COMMERCE A8S PRO        | 1         | 0.48%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.48%   |
| Razer Blade Stealth                        | 1         | 0.48%   |
| Pegatron Pro 3010 Microtower PC            | 1         | 0.48%   |
| Pegatron IPMIP-GS                          | 1         | 0.48%   |
| PCBOX Kant                                 | 1         | 0.48%   |
| MSI PE70 6QE                               | 1         | 0.48%   |
| MSI MS-7C52                                | 1         | 0.48%   |
| MSI MS-7C31                                | 1         | 0.48%   |
| MSI MS-7C02                                | 1         | 0.48%   |
| MSI MS-7B84                                | 1         | 0.48%   |
| MSI MS-7B17                                | 1         | 0.48%   |
| MSI MS-7816                                | 1         | 0.48%   |
| MSI GT72 2QE                               | 1         | 0.48%   |
| MSI GE62VR 6RF                             | 1         | 0.48%   |
| MSI CX61 2PC                               | 1         | 0.48%   |
| Microsoft Surface Pro 7                    | 1         | 0.48%   |
| MACHINIST E5-MR9A PRO V1.1                 | 1         | 0.48%   |
| Lenovo Yoga 6 13ALC7 82UD                  | 1         | 0.48%   |
| Lenovo Yoga 530-14ARR 81H9                 | 1         | 0.48%   |
| Lenovo V14 G2 ITL 82KA                     | 1         | 0.48%   |
| Lenovo ThinkPad X240 20AMS0XP0S            | 1         | 0.48%   |
| Lenovo ThinkPad X230 23259S9               | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 15        | 7.18%   |
| Acer Aspire                     | 9         | 4.31%   |
| Dell Latitude                   | 6         | 2.87%   |
| ASUS ZenBook                    | 6         | 2.87%   |
| HP ProBook                      | 5         | 2.39%   |
| HP Pavilion                     | 5         | 2.39%   |
| ASUS VivoBook                   | 5         | 2.39%   |
| Lenovo IdeaPad                  | 4         | 1.91%   |
| HP Laptop                       | 4         | 1.91%   |
| Apple MacBookPro8               | 4         | 1.91%   |
| Apple MacBookPro11              | 4         | 1.91%   |
| HP 255                          | 3         | 1.44%   |
| Fujitsu LIFEBOOK                | 3         | 1.44%   |
| Dell XPS                        | 3         | 1.44%   |
| Unknown                         | 3         | 1.44%   |
| Toshiba TECRA                   | 2         | 0.96%   |
| Lenovo Yoga                     | 2         | 0.96%   |
| HUAWEI BOD-WXX9                 | 2         | 0.96%   |
| HP ENVY                         | 2         | 0.96%   |
| HP EliteDesk                    | 2         | 0.96%   |
| HP EliteBook                    | 2         | 0.96%   |
| Dell OptiPlex                   | 2         | 0.96%   |
| Dell Inspiron                   | 2         | 0.96%   |
| ASUS ROG                        | 2         | 0.96%   |
| ASUS PRIME                      | 2         | 0.96%   |
| ASUS H110M-A                    | 2         | 0.96%   |
| Apple Macmini6                  | 2         | 0.96%   |
| Apple MacBookPro9               | 2         | 0.96%   |
| Apple MacBookPro5               | 2         | 0.96%   |
| Apple MacBookAir3               | 2         | 0.96%   |
| Apple iMac7                     | 2         | 0.96%   |
| Apple iMac12                    | 2         | 0.96%   |
| Apple iMac11                    | 2         | 0.96%   |
| Acer Predator                   | 2         | 0.96%   |
| Wortmann AG TERRA               | 1         | 0.48%   |
| Toshiba Satellite               | 1         | 0.48%   |
| Star Labs StarBook              | 1         | 0.48%   |
| Sony VPCEH2C5E                  | 1         | 0.48%   |
| Sony SVF1521O4E                 | 1         | 0.48%   |
| SHENZHEN YOUDISI E-COMMERCE A8S | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 21        | 10.05%  |
| 2012 | 21        | 10.05%  |
| 2021 | 20        | 9.57%   |
| 2020 | 17        | 8.13%   |
| 2018 | 14        | 6.7%    |
| 2016 | 14        | 6.7%    |
| 2015 | 14        | 6.7%    |
| 2022 | 13        | 6.22%   |
| 2013 | 12        | 5.74%   |
| 2010 | 12        | 5.74%   |
| 2014 | 11        | 5.26%   |
| 2009 | 11        | 5.26%   |
| 2011 | 9         | 4.31%   |
| 2017 | 8         | 3.83%   |
| 2008 | 8         | 3.83%   |
| 2023 | 3         | 1.44%   |
| 2007 | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 132       | 63.16%  |
| Desktop     | 55        | 26.32%  |
| All in one  | 9         | 4.31%   |
| Convertible | 7         | 3.35%   |
| Tablet      | 3         | 1.44%   |
| Mini pc     | 3         | 1.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 203       | 97.13%  |
| Enabled  | 6         | 2.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 207       | 99.04%  |
| Yes  | 2         | 0.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 66        | 31.43%  |
| 8.01-16.0   | 43        | 20.48%  |
| 16.01-24.0  | 41        | 19.52%  |
| 3.01-4.0    | 34        | 16.19%  |
| 32.01-64.0  | 17        | 8.1%    |
| 64.01-256.0 | 4         | 1.9%    |
| 1.01-2.0    | 3         | 1.43%   |
| 24.01-32.0  | 1         | 0.48%   |
| 2.01-3.0    | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 95        | 43.18%  |
| 1.01-2.0  | 44        | 20%     |
| 3.01-4.0  | 41        | 18.64%  |
| 4.01-8.0  | 32        | 14.55%  |
| 8.01-16.0 | 5         | 2.27%   |
| 0.51-1.0  | 3         | 1.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 146       | 69.52%  |
| 2      | 49        | 23.33%  |
| 3      | 8         | 3.81%   |
| 4      | 4         | 1.9%    |
| 5      | 3         | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 137       | 65.24%  |
| Yes       | 73        | 34.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 81.34%  |
| No        | 39        | 18.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 85.65%  |
| No        | 30        | 14.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 77.03%  |
| No        | 48        | 22.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 40        | 19.05%  |
| Germany      | 37        | 17.62%  |
| Russia       | 16        | 7.62%   |
| Spain        | 8         | 3.81%   |
| Netherlands  | 7         | 3.33%   |
| France       | 7         | 3.33%   |
| Brazil       | 7         | 3.33%   |
| UK           | 6         | 2.86%   |
| Poland       | 6         | 2.86%   |
| Italy        | 6         | 2.86%   |
| India        | 6         | 2.86%   |
| Australia    | 5         | 2.38%   |
| Sweden       | 3         | 1.43%   |
| Portugal     | 3         | 1.43%   |
| Norway       | 3         | 1.43%   |
| Mexico       | 3         | 1.43%   |
| Indonesia    | 3         | 1.43%   |
| Greece       | 3         | 1.43%   |
| Canada       | 3         | 1.43%   |
| Argentina    | 3         | 1.43%   |
| Turkey       | 2         | 0.95%   |
| Thailand     | 2         | 0.95%   |
| Israel       | 2         | 0.95%   |
| Ireland      | 2         | 0.95%   |
| Czechia      | 2         | 0.95%   |
| China        | 2         | 0.95%   |
| Chile        | 2         | 0.95%   |
| Venezuela    | 1         | 0.48%   |
| Ukraine      | 1         | 0.48%   |
| Tunisia      | 1         | 0.48%   |
| South Africa | 1         | 0.48%   |
| Slovakia     | 1         | 0.48%   |
| Saudi Arabia | 1         | 0.48%   |
| Puerto Rico  | 1         | 0.48%   |
| Panama       | 1         | 0.48%   |
| Kazakhstan   | 1         | 0.48%   |
| Japan        | 1         | 0.48%   |
| Hungary      | 1         | 0.48%   |
| Hong Kong    | 1         | 0.48%   |
| Georgia      | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 6         | 2.78%   |
| Stuttgart               | 3         | 1.39%   |
| Madrid                  | 3         | 1.39%   |
| Delhi                   | 3         | 1.39%   |
| Berlin                  | 3         | 1.39%   |
| Warsaw                  | 2         | 0.93%   |
| Stockholm               | 2         | 0.93%   |
| St Petersburg           | 2         | 0.93%   |
| Perth                   | 2         | 0.93%   |
| Novosibirsk             | 2         | 0.93%   |
| Munich                  | 2         | 0.93%   |
| Melbourne               | 2         | 0.93%   |
| Los Angeles             | 2         | 0.93%   |
| Las Vegas               | 2         | 0.93%   |
| Jakarta                 | 2         | 0.93%   |
| Hamm                    | 2         | 0.93%   |
| Faridabad               | 2         | 0.93%   |
| Cologne                 | 2         | 0.93%   |
| Brampton                | 2         | 0.93%   |
| Bangkok                 | 2         | 0.93%   |
| Aubagne                 | 2         | 0.93%   |
| Athens                  | 2         | 0.93%   |
| Amsterdam               | 2         | 0.93%   |
| Znojmo                  | 1         | 0.46%   |
| Zhuantang               | 1         | 0.46%   |
| Yorktown                | 1         | 0.46%   |
| Yekaterinburg           | 1         | 0.46%   |
| Wouldham                | 1         | 0.46%   |
| Worcestershire          | 1         | 0.46%   |
| Wilster                 | 1         | 0.46%   |
| Wilsdruff               | 1         | 0.46%   |
| Wiesbaden               | 1         | 0.46%   |
| West Jordan             | 1         | 0.46%   |
| Villingen-Schwenningen  | 1         | 0.46%   |
| Villefranche-sur-Saône | 1         | 0.46%   |
| Vigo                    | 1         | 0.46%   |
| Vienna                  | 1         | 0.46%   |
| Viareggio               | 1         | 0.46%   |
| Valencia                | 1         | 0.46%   |
| Twickenham              | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 36        | 40     | 12.54%  |
| Samsung Electronics            | 35        | 40     | 12.2%   |
| Seagate                        | 21        | 27     | 7.32%   |
| Sandisk                        | 21        | 23     | 7.32%   |
| Toshiba                        | 20        | 25     | 6.97%   |
| Crucial                        | 18        | 20     | 6.27%   |
| Kingston                       | 13        | 15     | 4.53%   |
| Apple                          | 10        | 10     | 3.48%   |
| Unknown                        | 9         | 10     | 3.14%   |
| Hitachi                        | 8         | 9      | 2.79%   |
| China                          | 7         | 7      | 2.44%   |
| Intel                          | 6         | 7      | 2.09%   |
| PNY                            | 5         | 5      | 1.74%   |
| SK hynix                       | 4         | 5      | 1.39%   |
| Micron Technology              | 4         | 4      | 1.39%   |
| KIOXIA                         | 4         | 7      | 1.39%   |
| Phison Electronics             | 3         | 3      | 1.05%   |
| Netac                          | 3         | 4      | 1.05%   |
| Micron/Crucial Technology      | 3         | 3      | 1.05%   |
| Intenso                        | 3         | 5      | 1.05%   |
| HGST                           | 3         | 4      | 1.05%   |
| Unknown                        | 3         | 3      | 1.05%   |
| Team                           | 2         | 3      | 0.7%    |
| Silicon Motion                 | 2         | 2      | 0.7%    |
| Realtek Semiconductor          | 2         | 3      | 0.7%    |
| JMicron Technology             | 2         | 2      | 0.7%    |
| Fujitsu                        | 2         | 2      | 0.7%    |
| BIWIN                          | 2         | 2      | 0.7%    |
| A-DATA Technology              | 2         | 2      | 0.7%    |
| Yeestor                        | 1         | 1      | 0.35%   |
| XrayDisk                       | 1         | 1      | 0.35%   |
| VISIPRO                        | 1         | 1      | 0.35%   |
| USB 3.0                        | 1         | 1      | 0.35%   |
| Union Memory                   | 1         | 2      | 0.35%   |
| T-FORCE                        | 1         | 1      | 0.35%   |
| Star Drive                     | 1         | 1      | 0.35%   |
| SPCC                           | 1         | 1      | 0.35%   |
| Solid State Storage Technology | 1         | 1      | 0.35%   |
| Solid State Storage            | 1         | 1      | 0.35%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 6         | 2.01%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 2.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 5         | 1.68%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 4         | 1.34%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 4         | 1.34%   |
| Crucial CT500MX500SSD1 500GB                        | 4         | 1.34%   |
| Crucial CT240BX500SSD1 240GB                        | 4         | 1.34%   |
| Unknown MMC Card  7GB                               | 3         | 1.01%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 1.01%   |
| Toshiba DT01ACA200 2TB                              | 3         | 1.01%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 1.01%   |
| Phison E12 NVMe Controller 2TB                      | 3         | 1.01%   |
| Unknown                                             | 3         | 1.01%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2         | 0.67%   |
| Unknown MMC Card  32GB                              | 2         | 0.67%   |
| Toshiba MK5065GSXF 500GB                            | 2         | 0.67%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.67%   |
| Seagate Expansion 1TB                               | 2         | 0.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 2         | 0.67%   |
| SanDisk SDSSDA240G 240GB                            | 2         | 0.67%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.67%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD                | 2         | 0.67%   |
| PNY CS900 480GB SSD                                 | 2         | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2         | 0.67%   |
| Intenso SSD SATAIII 128GB                           | 2         | 0.67%   |
| Intel SSDPEKNU512GZ 512GB                           | 2         | 0.67%   |
| HGST HTS721010A9E630 1TB                            | 2         | 0.67%   |
| Crucial CT275MX300SSD1 275GB                        | 2         | 0.67%   |
| Crucial CT250MX500SSD1 250GB                        | 2         | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.67%   |
| Apple SSD SM0512F 500GB                             | 2         | 0.67%   |
| Yeestor 512GB                                       | 1         | 0.34%   |
| XrayDisk 512GB SSD                                  | 1         | 0.34%   |
| WDC WDS480G2G0C-00AJM0 480GB                        | 1         | 0.34%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.34%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 0.34%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 24        | 27     | 31.58%  |
| Seagate             | 19        | 23     | 25%     |
| Toshiba             | 15        | 17     | 19.74%  |
| Hitachi             | 8         | 9      | 10.53%  |
| HGST                | 3         | 4      | 3.95%   |
| Fujitsu             | 2         | 2      | 2.63%   |
| Unknown             | 1         | 1      | 1.32%   |
| Samsung Electronics | 1         | 1      | 1.32%   |
| JMicron Technology  | 1         | 1      | 1.32%   |
| ASMT                | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 18        | 20     | 15%     |
| Samsung Electronics | 15        | 18     | 12.5%   |
| Kingston            | 12        | 14     | 10%     |
| SanDisk             | 11        | 12     | 9.17%   |
| WDC                 | 8         | 9      | 6.67%   |
| Apple               | 8         | 8      | 6.67%   |
| China               | 7         | 7      | 5.83%   |
| PNY                 | 5         | 5      | 4.17%   |
| Toshiba             | 4         | 6      | 3.33%   |
| Team                | 2         | 3      | 1.67%   |
| Seagate             | 2         | 2      | 1.67%   |
| Netac               | 2         | 2      | 1.67%   |
| Micron Technology   | 2         | 2      | 1.67%   |
| Intenso             | 2         | 4      | 1.67%   |
| A-DATA Technology   | 2         | 2      | 1.67%   |
| XrayDisk            | 1         | 1      | 0.83%   |
| VISIPRO             | 1         | 1      | 0.83%   |
| SPCC                | 1         | 1      | 0.83%   |
| SD                  | 1         | 1      | 0.83%   |
| OWC                 | 1         | 1      | 0.83%   |
| OCZ-VERTEX2         | 1         | 1      | 0.83%   |
| NGFF                | 1         | 1      | 0.83%   |
| MaiChai             | 1         | 1      | 0.83%   |
| LITEONIT            | 1         | 1      | 0.83%   |
| LITEON              | 1         | 1      | 0.83%   |
| KUU                 | 1         | 1      | 0.83%   |
| KingDian            | 1         | 2      | 0.83%   |
| Intel               | 1         | 1      | 0.83%   |
| Inland              | 1         | 1      | 0.83%   |
| HS-SSD-E100         | 1         | 1      | 0.83%   |
| Hewlett-Packard     | 1         | 1      | 0.83%   |
| Corsair             | 1         | 1      | 0.83%   |
| BIWIN               | 1         | 1      | 0.83%   |
| Apacer              | 1         | 1      | 0.83%   |
| Unknown             | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 111       | 135    | 41.57%  |
| NVMe    | 69        | 82     | 25.84%  |
| HDD     | 64        | 87     | 23.97%  |
| Unknown | 15        | 16     | 5.62%   |
| MMC     | 8         | 9      | 3%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 154       | 223    | 62.86%  |
| NVMe | 69        | 82     | 28.16%  |
| SAS  | 14        | 15     | 5.71%   |
| MMC  | 8         | 9      | 3.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 117       | 147    | 66.48%  |
| 0.51-1.0   | 43        | 58     | 24.43%  |
| 1.01-2.0   | 14        | 15     | 7.95%   |
| 3.01-4.0   | 2         | 2      | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 92        | 43.6%   |
| 251-500        | 57        | 27.01%  |
| 501-1000       | 35        | 16.59%  |
| 51-100         | 14        | 6.64%   |
| 2001-3000      | 4         | 1.9%    |
| 1001-2000      | 4         | 1.9%    |
| 21-50          | 2         | 0.95%   |
| 1-20           | 2         | 0.95%   |
| More than 3000 | 1         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 103       | 47.91%  |
| 21-50          | 53        | 24.65%  |
| 51-100         | 25        | 11.63%  |
| 101-250        | 24        | 11.16%  |
| 251-500        | 5         | 2.33%   |
| 1001-2000      | 3         | 1.4%    |
| More than 3000 | 1         | 0.47%   |
| 501-1000       | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 187       | 296    | 86.57%  |
| Works    | 28        | 32     | 12.96%  |
| Malfunc  | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 146       | 56.81%  |
| AMD                            | 30        | 11.67%  |
| Samsung Electronics            | 25        | 9.73%   |
| SanDisk                        | 13        | 5.06%   |
| Nvidia                         | 5         | 1.95%   |
| SK hynix                       | 4         | 1.56%   |
| Phison Electronics             | 4         | 1.56%   |
| KIOXIA                         | 4         | 1.56%   |
| Micron/Crucial Technology      | 3         | 1.17%   |
| Marvell Technology Group       | 3         | 1.17%   |
| ASMedia Technology             | 3         | 1.17%   |
| Toshiba America Info Systems   | 2         | 0.78%   |
| Solid State Storage Technology | 2         | 0.78%   |
| Silicon Motion                 | 2         | 0.78%   |
| Realtek Semiconductor          | 2         | 0.78%   |
| Micron Technology              | 2         | 0.78%   |
| Kingston Technology Company    | 2         | 0.78%   |
| Union Memory (Shenzhen)        | 1         | 0.39%   |
| Shenzhen Longsys Electronics   | 1         | 0.39%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.39%   |
| INNOGRIT                       | 1         | 0.39%   |
| Biwin Storage Technology       | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 8.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 5.96%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 3.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 3.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 3.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 2.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 2.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 2.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2.11%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.4%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.05%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 3         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.05%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.05%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.05%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.05%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.7%    |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 2         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 166       | 63.12%  |
| NVMe | 68        | 25.86%  |
| RAID | 17        | 6.46%   |
| IDE  | 12        | 4.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 169       | 80.86%  |
| AMD    | 40        | 19.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz               | 4         | 1.91%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 4         | 1.91%   |
| Intel Core i9-9900K CPU @ 3.60GHz               | 3         | 1.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 3         | 1.44%   |
| Intel Core i5-2435M CPU @ 2.40GHz               | 3         | 1.44%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 3         | 1.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 1.44%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 2         | 0.96%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 2         | 0.96%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 0.96%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 0.96%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz              | 2         | 0.96%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 2         | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 0.96%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 0.96%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 0.96%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 0.96%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 2         | 0.96%   |
| Intel Celeron N5105 @ 2.00GHz                   | 2         | 0.96%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 0.96%   |
| Intel 12th Gen Core i7-1260P                    | 2         | 0.96%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 0.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 0.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 2         | 0.96%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 0.96%   |
| Intel Xeon CPU W3520 @ 2.67GHz                  | 1         | 0.48%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz             | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz     | 1         | 0.48%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 0.48%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.48%   |
| Intel Pentium CPU J2900 @ 2.41GHz               | 1         | 0.48%   |
| Intel Pentium CPU G2020 @ 2.90GHz               | 1         | 0.48%   |
| Intel Pentium CPU 6805 @ 1.10GHz                | 1         | 0.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.48%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 0.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 51        | 24.4%   |
| Intel Core i7           | 38        | 18.18%  |
| Other                   | 22        | 10.53%  |
| Intel Core i3           | 16        | 7.66%   |
| Intel Core 2 Duo        | 15        | 7.18%   |
| Intel Celeron           | 14        | 6.7%    |
| AMD Ryzen 7             | 9         | 4.31%   |
| AMD Ryzen 5             | 9         | 4.31%   |
| Intel Pentium           | 5         | 2.39%   |
| Intel Core i9           | 3         | 1.44%   |
| AMD Athlon              | 3         | 1.44%   |
| AMD A8                  | 3         | 1.44%   |
| Intel Xeon              | 2         | 0.96%   |
| Intel Pentium Silver    | 2         | 0.96%   |
| Intel Pentium Dual-Core | 2         | 0.96%   |
| AMD Ryzen 9             | 2         | 0.96%   |
| AMD Ryzen 5 PRO         | 2         | 0.96%   |
| AMD Ryzen 3             | 2         | 0.96%   |
| AMD A4                  | 2         | 0.96%   |
| AMD A12                 | 2         | 0.96%   |
| AMD Sempron             | 1         | 0.48%   |
| AMD Phenom II X6        | 1         | 0.48%   |
| AMD G                   | 1         | 0.48%   |
| AMD E1                  | 1         | 0.48%   |
| AMD A6                  | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 94        | 44.76%  |
| 4      | 72        | 34.29%  |
| 8      | 16        | 7.62%   |
| 6      | 12        | 5.71%   |
| 12     | 6         | 2.86%   |
| 1      | 5         | 2.38%   |
| 10     | 2         | 0.95%   |
| 5      | 2         | 0.95%   |
| 14     | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 209       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 151       | 72.25%  |
| 1      | 58        | 27.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 209       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 173       | 81.99%  |
| 0x806ec    | 3         | 1.42%   |
| 0x806c1    | 3         | 1.42%   |
| 0x706e5    | 3         | 1.42%   |
| 0x906e9    | 2         | 0.95%   |
| 0x906a4    | 2         | 0.95%   |
| 0x806d1    | 2         | 0.95%   |
| 0x306a9    | 2         | 0.95%   |
| 0x206a7    | 2         | 0.95%   |
| 0x0a50000c | 2         | 0.95%   |
| 0x906ec    | 1         | 0.47%   |
| 0x906c0    | 1         | 0.47%   |
| 0x906a3    | 1         | 0.47%   |
| 0x806eb    | 1         | 0.47%   |
| 0x806ea    | 1         | 0.47%   |
| 0x706a8    | 1         | 0.47%   |
| 0x706a1    | 1         | 0.47%   |
| 0x40661    | 1         | 0.47%   |
| 0x40651    | 1         | 0.47%   |
| 0x1067a    | 1         | 0.47%   |
| 0x10676    | 1         | 0.47%   |
| 0x0a50000d | 1         | 0.47%   |
| 0x08600106 | 1         | 0.47%   |
| 0x08108109 | 1         | 0.47%   |
| 0x07030106 | 1         | 0.47%   |
| 0x0600611a | 1         | 0.47%   |
| 0x010000c8 | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 27        | 12.92%  |
| IvyBridge        | 21        | 10.05%  |
| Haswell          | 19        | 9.09%   |
| Penryn           | 15        | 7.18%   |
| Skylake          | 14        | 6.7%    |
| SandyBridge      | 12        | 5.74%   |
| Unknown          | 11        | 5.26%   |
| TigerLake        | 10        | 4.78%   |
| Goldmont plus    | 10        | 4.78%   |
| Westmere         | 8         | 3.83%   |
| Zen+             | 7         | 3.35%   |
| Zen 3            | 7         | 3.35%   |
| Zen 2            | 6         | 2.87%   |
| IceLake          | 6         | 2.87%   |
| Broadwell        | 5         | 2.39%   |
| Zen              | 4         | 1.91%   |
| Silvermont       | 4         | 1.91%   |
| Excavator        | 4         | 1.91%   |
| Puma             | 3         | 1.44%   |
| Core             | 3         | 1.44%   |
| Alderlake Hybrid | 3         | 1.44%   |
| Steamroller      | 2         | 0.96%   |
| Nehalem          | 2         | 0.96%   |
| K10              | 2         | 0.96%   |
| Tremont          | 1         | 0.48%   |
| Piledriver       | 1         | 0.48%   |
| CometLake        | 1         | 0.48%   |
| Bobcat           | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 135       | 55.33%  |
| AMD    | 57        | 23.36%  |
| Nvidia | 52        | 21.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 16        | 6.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 10        | 4%      |
| Intel GeminiLake [UHD Graphics 600]                                       | 8         | 3.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 2.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 2.4%    |
| Intel HD Graphics 530                                                     | 6         | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 2.4%    |
| Intel Core Processor Integrated Graphics Controller                       | 6         | 2.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 6         | 2.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 6         | 2.4%    |
| Intel HD Graphics 630                                                     | 5         | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 1.6%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 4         | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 1.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 3         | 1.2%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 1.2%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.2%    |
| Intel HD Graphics 620                                                     | 3         | 1.2%    |
| Intel HD Graphics 5500                                                    | 3         | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 1.2%    |
| Intel Alder Lake-P Integrated Graphics Controller                         | 3         | 1.2%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 3         | 1.2%    |
| AMD Renoir                                                                | 3         | 1.2%    |
| AMD Lucienne                                                              | 3         | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3         | 1.2%    |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 0.8%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 2         | 0.8%    |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                               | 2         | 0.8%    |
| Nvidia GK107 [GeForce GT 640]                                             | 2         | 0.8%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 2         | 0.8%    |
| Nvidia C79 [GeForce 9400M]                                                | 2         | 0.8%    |
| Intel UHD Graphics 620                                                    | 2         | 0.8%    |
| Intel JasperLake [UHD Graphics]                                           | 2         | 0.8%    |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 0.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 2         | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 0.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 2         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 101       | 48.33%  |
| 1 x AMD         | 47        | 22.49%  |
| Intel + Nvidia  | 25        | 11.96%  |
| 1 x Nvidia      | 24        | 11.48%  |
| Intel + AMD     | 4         | 1.91%   |
| 2 x AMD         | 3         | 1.44%   |
| AMD + Nvidia    | 2         | 0.96%   |
| Other           | 1         | 0.48%   |
| 2 x Nvidia      | 1         | 0.48%   |
| Intel + 2 x AMD | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 195       | 93.3%   |
| Proprietary | 11        | 5.26%   |
| Unknown     | 3         | 1.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 195       | 93.3%   |
| 0.01-0.5   | 4         | 1.91%   |
| 7.01-8.0   | 3         | 1.44%   |
| 1.01-2.0   | 3         | 1.44%   |
| 0.51-1.0   | 3         | 1.44%   |
| 3.01-4.0   | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 12.73%  |
| Apple                   | 28        | 12.73%  |
| LG Display              | 23        | 10.45%  |
| BOE                     | 22        | 10%     |
| Samsung Electronics     | 19        | 8.64%   |
| Chimei Innolux          | 16        | 7.27%   |
| Goldstar                | 11        | 5%      |
| Dell                    | 11        | 5%      |
| Sharp                   | 7         | 3.18%   |
| Lenovo                  | 4         | 1.82%   |
| Hewlett-Packard         | 4         | 1.82%   |
| Acer                    | 4         | 1.82%   |
| Philips                 | 3         | 1.36%   |
| PANDA                   | 3         | 1.36%   |
| BenQ                    | 3         | 1.36%   |
| Vizio                   | 2         | 0.91%   |
| Sceptre Tech            | 2         | 0.91%   |
| Chi Mei Optoelectronics | 2         | 0.91%   |
| ASUSTek Computer        | 2         | 0.91%   |
| AOC                     | 2         | 0.91%   |
| ___                     | 1         | 0.45%   |
| ViewSonic               | 1         | 0.45%   |
| Unknown                 | 1         | 0.45%   |
| Toshiba                 | 1         | 0.45%   |
| Sony                    | 1         | 0.45%   |
| Positivo                | 1         | 0.45%   |
| Panasonic               | 1         | 0.45%   |
| NSL                     | 1         | 0.45%   |
| NEC Computers           | 1         | 0.45%   |
| MYS                     | 1         | 0.45%   |
| MSI                     | 1         | 0.45%   |
| Mi                      | 1         | 0.45%   |
| LG Philips              | 1         | 0.45%   |
| Kogan                   | 1         | 0.45%   |
| InfoVision              | 1         | 0.45%   |
| Idek Iiyama             | 1         | 0.45%   |
| Hitachi                 | 1         | 0.45%   |
| HannStar                | 1         | 0.45%   |
| Fujitsu Siemens         | 1         | 0.45%   |
| Eizo                    | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.88%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 0.88%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 2         | 0.88%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 2         | 0.88%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 2         | 0.88%   |
| Apple LCD Monitor Color LCD 2880x1800                                | 2         | 0.88%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch               | 2         | 0.88%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 2         | 0.88%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                     | 2         | 0.88%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                | 2         | 0.88%   |
| Apple Color LCD APP9C6C 1920x1200 520x320mm 24.0-inch                | 2         | 0.88%   |
| ___ LCDTV16 ___3393 1366x768                                         | 1         | 0.44%   |
| Vizio SV470M VIZ0057 1920x1080 1039x584mm 46.9-inch                  | 1         | 0.44%   |
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                   | 1         | 0.44%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch        | 1         | 0.44%   |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                  | 1         | 0.44%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                | 1         | 0.44%   |
| Sony TV SNY7A02 1360x768 708x398mm 32.0-inch                         | 1         | 0.44%   |
| Sharp LCD Monitor SHP151C 1920x1080 344x194mm 15.5-inch              | 1         | 0.44%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 1         | 0.44%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch              | 1         | 0.44%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch              | 1         | 0.44%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.44%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch              | 1         | 0.44%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 1         | 0.44%   |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch       | 1         | 0.44%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch        | 1         | 0.44%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch    | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch | 1         | 0.44%   |
| Samsung Electronics SMB2030HD SAM0709 1600x900 443x249mm 20.0-inch   | 1         | 0.44%   |
| Samsung Electronics S27A950D SAM079F 1920x1080 598x336mm 27.0-inch   | 1         | 0.44%   |
| Samsung Electronics S24E450 SAM0C7F 1920x1080 521x293mm 23.5-inch    | 1         | 0.44%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 1         | 0.44%   |
| Samsung Electronics LS27AG55x SAM71E0 2560x1440 597x336mm 27.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 100       | 46.51%  |
| 1366x768 (WXGA)    | 41        | 19.07%  |
| 1920x1200 (WUXGA)  | 10        | 4.65%   |
| 1280x800 (WXGA)    | 10        | 4.65%   |
| 3840x2160 (4K)     | 7         | 3.26%   |
| 2560x1440 (QHD)    | 7         | 3.26%   |
| 2880x1800          | 6         | 2.79%   |
| 1600x900 (HD+)     | 5         | 2.33%   |
| 1440x900 (WXGA+)   | 5         | 2.33%   |
| 1280x1024 (SXGA)   | 4         | 1.86%   |
| 3440x1440          | 3         | 1.4%    |
| 2560x1600          | 3         | 1.4%    |
| 1680x1050 (WSXGA+) | 3         | 1.4%    |
| 2560x1080          | 2         | 0.93%   |
| 1360x768           | 2         | 0.93%   |
| 3840x2400          | 1         | 0.47%   |
| 3840x1080          | 1         | 0.47%   |
| 3360x1080          | 1         | 0.47%   |
| 2880x1920          | 1         | 0.47%   |
| 2736x1824          | 1         | 0.47%   |
| 1920x1280          | 1         | 0.47%   |
| Unknown            | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 63        | 28.13%  |
| 13      | 29        | 12.95%  |
| 14      | 20        | 8.93%   |
| 24      | 16        | 7.14%   |
| 21      | 15        | 6.7%    |
| 27      | 14        | 6.25%   |
| 17      | 12        | 5.36%   |
| 23      | 6         | 2.68%   |
| 12      | 6         | 2.68%   |
| 18      | 5         | 2.23%   |
| Unknown | 5         | 2.23%   |
| 34      | 4         | 1.79%   |
| 31      | 4         | 1.79%   |
| 11      | 4         | 1.79%   |
| 20      | 3         | 1.34%   |
| 19      | 3         | 1.34%   |
| 84      | 2         | 0.89%   |
| 26      | 2         | 0.89%   |
| 72      | 1         | 0.45%   |
| 65      | 1         | 0.45%   |
| 60      | 1         | 0.45%   |
| 54      | 1         | 0.45%   |
| 49      | 1         | 0.45%   |
| 42      | 1         | 0.45%   |
| 35      | 1         | 0.45%   |
| 32      | 1         | 0.45%   |
| 29      | 1         | 0.45%   |
| 22      | 1         | 0.45%   |
| 16      | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 88        | 39.64%  |
| 501-600     | 36        | 16.22%  |
| 201-300     | 33        | 14.86%  |
| 401-500     | 25        | 11.26%  |
| 351-400     | 16        | 7.21%   |
| 701-800     | 5         | 2.25%   |
| 601-700     | 5         | 2.25%   |
| Unknown     | 5         | 2.25%   |
| 1001-1500   | 4         | 1.8%    |
| 1501-2000   | 3         | 1.35%   |
| 801-900     | 1         | 0.45%   |
| 901-1000    | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 154       | 73.33%  |
| 16/10   | 37        | 17.62%  |
| 3/2     | 5         | 2.38%   |
| 21/9    | 5         | 2.38%   |
| Unknown | 4         | 1.9%    |
| 4/3     | 2         | 0.95%   |
| 6/5     | 1         | 0.48%   |
| 5/4     | 1         | 0.48%   |
| 32/9    | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 65        | 29.28%  |
| 81-90          | 32        | 14.41%  |
| 201-250        | 25        | 11.26%  |
| 71-80          | 17        | 7.66%   |
| 301-350        | 15        | 6.76%   |
| 351-500        | 11        | 4.95%   |
| 151-200        | 11        | 4.95%   |
| 121-130        | 8         | 3.6%    |
| 251-300        | 7         | 3.15%   |
| More than 1000 | 6         | 2.7%    |
| 61-70          | 5         | 2.25%   |
| 141-150        | 5         | 2.25%   |
| Unknown        | 5         | 2.25%   |
| 51-60          | 4         | 1.8%    |
| 131-140        | 4         | 1.8%    |
| 501-1000       | 2         | 0.9%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 32.09%  |
| 101-120       | 62        | 28.84%  |
| 51-100        | 53        | 24.65%  |
| 161-240       | 17        | 7.91%   |
| 1-50          | 5         | 2.33%   |
| Unknown       | 5         | 2.33%   |
| More than 240 | 4         | 1.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 181       | 86.19%  |
| 2     | 25        | 11.9%   |
| 0     | 3         | 1.43%   |
| 3     | 1         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 93        | 29.43%  |
| Intel                             | 92        | 29.11%  |
| Broadcom                          | 41        | 12.97%  |
| Qualcomm Atheros                  | 36        | 11.39%  |
| Marvell Technology Group          | 7         | 2.22%   |
| TP-Link                           | 5         | 1.58%   |
| Ralink Technology                 | 5         | 1.58%   |
| Samsung Electronics               | 4         | 1.27%   |
| Broadcom Limited                  | 4         | 1.27%   |
| Xiaomi                            | 3         | 0.95%   |
| Qualcomm                          | 3         | 0.95%   |
| Nvidia                            | 3         | 0.95%   |
| Huawei Technologies               | 3         | 0.95%   |
| NetGear                           | 2         | 0.63%   |
| MediaTek                          | 2         | 0.63%   |
| Ericsson Business Mobile Networks | 2         | 0.63%   |
| Dell                              | 2         | 0.63%   |
| ASIX Electronics                  | 2         | 0.63%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.32%   |
| Sierra Wireless                   | 1         | 0.32%   |
| Ralink                            | 1         | 0.32%   |
| OPPO Electronics                  | 1         | 0.32%   |
| Motorola PCS                      | 1         | 0.32%   |
| Linksys                           | 1         | 0.32%   |
| ASUSTek Computer                  | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 16.45%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 3.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 2.35%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 2.35%   |
| Intel Wireless 8260                                               | 8         | 2.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 2.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 8         | 2.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.83%   |
| Intel Wireless 3165                                               | 6         | 1.57%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.31%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 1.04%   |
| Intel Wireless 7265                                               | 4         | 1.04%   |
| Intel Wireless 7260                                               | 4         | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.04%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 1.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 4         | 1.04%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 4         | 1.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                    | 3         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.78%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.78%   |
| Intel Wireless-AC 9260                                            | 3         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 75        | 38.66%  |
| Broadcom                          | 34        | 17.53%  |
| Realtek Semiconductor             | 33        | 17.01%  |
| Qualcomm Atheros                  | 27        | 13.92%  |
| Ralink Technology                 | 5         | 2.58%   |
| TP-Link                           | 4         | 2.06%   |
| Broadcom Limited                  | 3         | 1.55%   |
| Qualcomm                          | 2         | 1.03%   |
| MediaTek                          | 2         | 1.03%   |
| Marvell Technology Group          | 2         | 1.03%   |
| Sierra Wireless                   | 1         | 0.52%   |
| Ralink                            | 1         | 0.52%   |
| NetGear                           | 1         | 0.52%   |
| Linksys                           | 1         | 0.52%   |
| Ericsson Business Mobile Networks | 1         | 0.52%   |
| Dell                              | 1         | 0.52%   |
| ASUSTek Computer                  | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 6.12%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 4.59%   |
| Intel Wireless 8260                                            | 8         | 4.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 8         | 4.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 3.57%   |
| Intel Wireless 3165                                            | 6         | 3.06%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 3.06%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 2.04%   |
| Intel Wireless 7265                                            | 4         | 2.04%   |
| Intel Wireless 7260                                            | 4         | 2.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 2.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 2.04%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 4         | 2.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 1.53%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.53%   |
| Ralink RT5370 Wireless Adapter                                 | 3         | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.53%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 1.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.53%   |
| Intel Wireless-AC 9260                                         | 3         | 1.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.53%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 1.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.02%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 2         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.02%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.02%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 1.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 80        | 43.72%  |
| Intel                      | 45        | 24.59%  |
| Broadcom                   | 19        | 10.38%  |
| Qualcomm Atheros           | 14        | 7.65%   |
| Marvell Technology Group   | 5         | 2.73%   |
| Xiaomi                     | 3         | 1.64%   |
| Samsung Electronics        | 3         | 1.64%   |
| Nvidia                     | 3         | 1.64%   |
| Huawei Technologies        | 3         | 1.64%   |
| ASIX Electronics           | 2         | 1.09%   |
| ZTE WCDMA Technologies MSM | 1         | 0.55%   |
| TP-Link                    | 1         | 0.55%   |
| Qualcomm                   | 1         | 0.55%   |
| OPPO Electronics           | 1         | 0.55%   |
| NetGear                    | 1         | 0.55%   |
| Broadcom Limited           | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 34.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 4.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.19%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 2.19%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.19%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.64%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.64%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.64%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 1.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.09%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.09%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.09%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.09%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.09%   |
| Huawei WLZ-AN00                                                   | 2         | 1.09%   |
| ZTE WCDMA MSM Android                                             | 1         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.55%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.55%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.55%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.55%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.55%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 179       | 50.71%  |
| Ethernet | 170       | 48.16%  |
| Modem    | 3         | 0.85%   |
| Unknown  | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 133       | 62.74%  |
| Ethernet | 79        | 37.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 123       | 58.85%  |
| 1     | 79        | 37.8%   |
| 3     | 5         | 2.39%   |
| 0     | 2         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 144       | 68.57%  |
| Yes  | 66        | 31.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 41.61%  |
| Apple                           | 29        | 18.01%  |
| Realtek Semiconductor           | 22        | 13.66%  |
| Qualcomm Atheros Communications | 9         | 5.59%   |
| Broadcom                        | 7         | 4.35%   |
| Lite-On Technology              | 6         | 3.73%   |
| IMC Networks                    | 5         | 3.11%   |
| Foxconn / Hon Hai               | 5         | 3.11%   |
| Cambridge Silicon Radio         | 5         | 3.11%   |
| ASUSTek Computer                | 2         | 1.24%   |
| Toshiba                         | 1         | 0.62%   |
| MediaTek                        | 1         | 0.62%   |
| Hewlett-Packard                 | 1         | 0.62%   |
| Askey Computer                  | 1         | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 23        | 14.29%  |
| Intel AX201 Bluetooth                               | 15        | 9.32%   |
| Apple Bluetooth Host Controller                     | 12        | 7.45%   |
| Realtek Bluetooth Radio                             | 11        | 6.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 6.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 6.21%   |
| Apple Bluetooth USB Host Controller                 | 7         | 4.35%   |
| Intel AX200 Bluetooth                               | 6         | 3.73%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 3.73%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 3.11%   |
| Lite-On Bluetooth Device                            | 4         | 2.48%   |
| Intel AX210 Bluetooth                               | 4         | 2.48%   |
| Apple Bluetooth HCI                                 | 4         | 2.48%   |
| Intel Bluetooth Device                              | 3         | 1.86%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.86%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.24%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.24%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.24%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.24%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 1.24%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.24%   |
| Toshiba Bluetooth Device                            | 1         | 0.62%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.62%   |
| MediaTek Wireless_Device                            | 1         | 0.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.62%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.62%   |
| IMC Networks Bluetooth                              | 1         | 0.62%   |
| IMC Networks BCM20702A0                             | 1         | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.62%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.62%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.62%   |
| Broadcom Bluetooth 3.0 USB Dongle                   | 1         | 0.62%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.62%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.62%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 164       | 58.99%  |
| AMD                      | 54        | 19.42%  |
| Nvidia                   | 35        | 12.59%  |
| C-Media Electronics      | 8         | 2.88%   |
| Logitech                 | 5         | 1.8%    |
| Realtek Semiconductor    | 1         | 0.36%   |
| Razer USA                | 1         | 0.36%   |
| Nordic Semiconductor ASA | 1         | 0.36%   |
| Microsoft                | 1         | 0.36%   |
| KTMicro                  | 1         | 0.36%   |
| Hewlett-Packard          | 1         | 0.36%   |
| Goldvish                 | 1         | 0.36%   |
| GN Netcom                | 1         | 0.36%   |
| Generalplus Technology   | 1         | 0.36%   |
| Dell                     | 1         | 0.36%   |
| Creative Labs            | 1         | 0.36%   |
| ASUSTek Computer         | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 6.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 19        | 5.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 4.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 3.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 3.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 3.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 3.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 3.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 2.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.11%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 1.81%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.81%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.51%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.51%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.51%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.2%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.2%    |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.2%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.2%    |
| Nvidia MCP79 High Definition Audio                                         | 3         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.9%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 0.9%    |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 0.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.9%    |
| AMD Navi 10 HDMI Audio                                                     | 3         | 0.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.6%    |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 32.61%  |
| Micron Technology   | 10        | 21.74%  |
| SK hynix            | 6         | 13.04%  |
| Kingston            | 3         | 6.52%   |
| Unknown             | 2         | 4.35%   |
| Unknown (ABCD)      | 1         | 2.17%   |
| Unknown (0x5846)    | 1         | 2.17%   |
| Ramaxel Technology  | 1         | 2.17%   |
| pqi                 | 1         | 2.17%   |
| GSkill              | 1         | 2.17%   |
| CSX                 | 1         | 2.17%   |
| Crucial             | 1         | 2.17%   |
| Corsair             | 1         | 2.17%   |
| Apacer              | 1         | 2.17%   |
| A-DATA Technology   | 1         | 2.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 4.35%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 4.35%   |
| Unknown                                                          | 2         | 4.35%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.17%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s    | 1         | 2.17%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.17%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.17%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 2.17%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 2.17%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 1         | 2.17%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 2.17%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 2.17%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.17%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 2.17%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.17%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2.17%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s              | 1         | 2.17%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s              | 1         | 2.17%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.17%   |
| Ramaxel RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.17%   |
| pqi RAM Module 2GB SODIMM DDR2 667MT/s                           | 1         | 2.17%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 2.17%   |
| Micron RAM MT53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 2.17%   |
| Micron RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 2.17%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2.17%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.17%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.17%   |
| Micron RAM 16ATF4G64HZ-3G2E2 32GB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| Micron RAM 16ATF2G64HZ-2G6E3 16GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| Kingston RAM HX426C16FB/4 4GB DIMM DDR4 2800MT/s                 | 1         | 2.17%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1600MT/s                  | 1         | 2.17%   |
| Kingston RAM ASU16D3LU1KBG/4G 4GB DIMM DDR3 3200MT/s             | 1         | 2.17%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 1         | 2.17%   |
| CSX RAM V01D3L82GB26826813 2GB DIMM 1066MT/s                     | 1         | 2.17%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 1         | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 20        | 50%     |
| DDR3    | 9         | 22.5%   |
| LPDDR4  | 6         | 15%     |
| SDRAM   | 1         | 2.5%    |
| LPDDR3  | 1         | 2.5%    |
| DDR5    | 1         | 2.5%    |
| DDR2    | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 60%     |
| Row Of Chips | 9         | 22.5%   |
| DIMM         | 7         | 17.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 23        | 56.1%   |
| 4096  | 10        | 24.39%  |
| 16384 | 4         | 9.76%   |
| 2048  | 3         | 7.32%   |
| 32768 | 1         | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 11        | 25.58%  |
| 2667  | 8         | 18.6%   |
| 1600  | 6         | 13.95%  |
| 4267  | 5         | 11.63%  |
| 2400  | 3         | 6.98%   |
| 2800  | 2         | 4.65%   |
| 4800  | 1         | 2.33%   |
| 2133  | 1         | 2.33%   |
| 2000  | 1         | 2.33%   |
| 1333  | 1         | 2.33%   |
| 1066  | 1         | 2.33%   |
| 800   | 1         | 2.33%   |
| 667   | 1         | 2.33%   |
| 533   | 1         | 2.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung M2020 Series               | 1         | 33.33%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 33.33%  |
| Canon MF4320-4350                  | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson ES-H300 [GT-2500] | 1         | 50%     |
| Canon CanoScan LiDE 100       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Apple                                  | 26        | 18.31%  |
| Chicony Electronics                    | 25        | 17.61%  |
| Quanta                                 | 14        | 9.86%   |
| IMC Networks                           | 13        | 9.15%   |
| Realtek Semiconductor                  | 10        | 7.04%   |
| Microdia                               | 10        | 7.04%   |
| Bison Electronics                      | 7         | 4.93%   |
| Sunplus Innovation Technology          | 6         | 4.23%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.52%   |
| Syntek                                 | 2         | 1.41%   |
| SunplusIT                              | 2         | 1.41%   |
| Samsung Electronics                    | 2         | 1.41%   |
| Luxvisions Innotech Limited            | 2         | 1.41%   |
| Lenovo                                 | 2         | 1.41%   |
| Generalplus Technology                 | 2         | 1.41%   |
| Alcor Micro                            | 2         | 1.41%   |
| Acer                                   | 2         | 1.41%   |
| Suyin                                  | 1         | 0.7%    |
| Sunplus Technology                     | 1         | 0.7%    |
| Sonix Technology                       | 1         | 0.7%    |
| Silicon Motion                         | 1         | 0.7%    |
| Shine-optics                           | 1         | 0.7%    |
| Logitech                               | 1         | 0.7%    |
| Lite-On Technology                     | 1         | 0.7%    |
| Intel                                  | 1         | 0.7%    |
| Cubeternet                             | 1         | 0.7%    |
| Cisco Systems                          | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Apple Built-in iSight                            | 9         | 6.25%   |
| Chicony Integrated Camera                        | 7         | 4.86%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 6         | 4.17%   |
| Apple FaceTime HD Camera                         | 6         | 4.17%   |
| Microdia Integrated_Webcam_HD                    | 4         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam                | 4         | 2.78%   |
| Apple FaceTime HD Camera (Built-in)              | 4         | 2.78%   |
| Realtek Integrated_Webcam_HD                     | 3         | 2.08%   |
| IMC Networks Integrated Camera                   | 3         | 2.08%   |
| Chicony HD WebCam                                | 3         | 2.08%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 1.39%   |
| Samsung Galaxy series, misc. (MTP mode)          | 2         | 1.39%   |
| Quanta USB2.0 HD UVC WebCam                      | 2         | 1.39%   |
| Quanta HP TrueVision HD Camera                   | 2         | 1.39%   |
| Quanta HP HD Camera                              | 2         | 1.39%   |
| Quanta HD Webcam                                 | 2         | 1.39%   |
| Quanta HD Camera                                 | 2         | 1.39%   |
| Microdia Webcam Vitade AF                        | 2         | 1.39%   |
| Microdia Integrated Webcam                       | 2         | 1.39%   |
| IMC Networks HD Camera                           | 2         | 1.39%   |
| Chicony HP Webcam                                | 2         | 1.39%   |
| Chicony HP TrueVision HD Camera                  | 2         | 1.39%   |
| Chicony HP Truevision HD                         | 2         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.39%   |
| Bison Lenovo Integrated Webcam                   | 2         | 1.39%   |
| Apple FaceTime Camera                            | 2         | 1.39%   |
| Syntek Lenovo EasyCamera                         | 1         | 0.69%   |
| Syntek EasyCamera                                | 1         | 0.69%   |
| Suyin Acer HD Crystal Eye webcam                 | 1         | 0.69%   |
| SunplusIT HD Camera                              | 1         | 0.69%   |
| SunplusIT HBT Camera                             | 1         | 0.69%   |
| Sunplus 1.3M HD WebCam                           | 1         | 0.69%   |
| Sunplus HD WebCam                                | 1         | 0.69%   |
| Sunplus Dell E5570 integrated webcam             | 1         | 0.69%   |
| Sunplus Camera                                   | 1         | 0.69%   |
| Sunplus 1080P Webcam                             | 1         | 0.69%   |
| Sonix HP Webcam-101                              | 1         | 0.69%   |
| Silicon Motion WebCam SC-03FFL11939N             | 1         | 0.69%   |
| Shine-optics USB2.0 HD UVC WebCam                | 1         | 0.69%   |
| Realtek USB Camera                               | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 35.71%  |
| Shenzhen Goodix Technology | 8         | 28.57%  |
| Synaptics                  | 4         | 14.29%  |
| Elan Microelectronics      | 3         | 10.71%  |
| Upek                       | 1         | 3.57%   |
| LighTuning Technology      | 1         | 3.57%   |
| AuthenTec                  | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 21.43%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 10.71%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 7.14%   |
| Elan ELAN:Fingerprint                                                      | 2         | 7.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.57%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.57%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 3.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 3.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.57%   |
| LighTuning Fingerprint Reader                                              | 1         | 3.57%   |
| Elan ELAN:ARM-M4                                                           | 1         | 3.57%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 37.5%   |
| Upek        | 2         | 25%     |
| Alcor Micro | 2         | 25%     |
| O2 Micro    | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 139       | 66.51%  |
| 1     | 56        | 26.79%  |
| 2     | 13        | 6.22%   |
| 3     | 1         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 32.14%  |
| Net/wireless             | 19        | 22.62%  |
| Multimedia controller    | 14        | 16.67%  |
| Graphics card            | 10        | 11.9%   |
| Chipcard                 | 8         | 9.52%   |
| Net/ethernet             | 2         | 2.38%   |
| Storage                  | 1         | 1.19%   |
| Network                  | 1         | 1.19%   |
| Communication controller | 1         | 1.19%   |
| Card reader              | 1         | 1.19%   |


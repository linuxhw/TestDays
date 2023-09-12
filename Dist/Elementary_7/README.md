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

Total: 340

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro11,2              | Notebook    | [d3996a81e2](https://linux-hardware.org/?probe=d3996a81e2) | Sep 07, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [2ce7b78a76](https://linux-hardware.org/?probe=2ce7b78a76) | Sep 06, 2023 |
| Dell          | Latitude E5570              | Notebook    | [10d8ad7a3d](https://linux-hardware.org/?probe=10d8ad7a3d) | Sep 05, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [7a27c6dd8d](https://linux-hardware.org/?probe=7a27c6dd8d) | Sep 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [783d0f51f5](https://linux-hardware.org/?probe=783d0f51f5) | Aug 31, 2023 |
| Medion        | E15301                      | Notebook    | [7f6c4eb814](https://linux-hardware.org/?probe=7f6c4eb814) | Aug 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24ad5e2b06](https://linux-hardware.org/?probe=24ad5e2b06) | Aug 31, 2023 |
| HP            | 350 G1                      | Notebook    | [1e317e5a51](https://linux-hardware.org/?probe=1e317e5a51) | Aug 30, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [9374424bbd](https://linux-hardware.org/?probe=9374424bbd) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | Notebook    | [22e88dc9a5](https://linux-hardware.org/?probe=22e88dc9a5) | Aug 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [8741a9bb96](https://linux-hardware.org/?probe=8741a9bb96) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [7efcdba9ef](https://linux-hardware.org/?probe=7efcdba9ef) | Aug 29, 2023 |
| HP            | 350 G1                      | Notebook    | [d800790bce](https://linux-hardware.org/?probe=d800790bce) | Aug 28, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [627068909d](https://linux-hardware.org/?probe=627068909d) | Aug 25, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [ac61c512ef](https://linux-hardware.org/?probe=ac61c512ef) | Aug 25, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [5c956051fb](https://linux-hardware.org/?probe=5c956051fb) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [744be89da4](https://linux-hardware.org/?probe=744be89da4) | Aug 24, 2023 |
| Google        | Eldrid                      | Notebook    | [e451d840cf](https://linux-hardware.org/?probe=e451d840cf) | Aug 24, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [190a0f1eee](https://linux-hardware.org/?probe=190a0f1eee) | Aug 23, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [0112053569](https://linux-hardware.org/?probe=0112053569) | Aug 23, 2023 |
| HP            | 18E7                        | Desktop     | [0bd07157fb](https://linux-hardware.org/?probe=0bd07157fb) | Aug 20, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [01a44fbb3b](https://linux-hardware.org/?probe=01a44fbb3b) | Aug 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [054a5a44ad](https://linux-hardware.org/?probe=054a5a44ad) | Aug 18, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [d05585906d](https://linux-hardware.org/?probe=d05585906d) | Aug 18, 2023 |
| Gateway       | ZX4931                      | All in one  | [953740388e](https://linux-hardware.org/?probe=953740388e) | Aug 17, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8298417da7](https://linux-hardware.org/?probe=8298417da7) | Aug 16, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [fafbb2dbc0](https://linux-hardware.org/?probe=fafbb2dbc0) | Aug 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [ce1ba9dce0](https://linux-hardware.org/?probe=ce1ba9dce0) | Aug 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [9271029425](https://linux-hardware.org/?probe=9271029425) | Aug 13, 2023 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-58-generic      | 62        | 25%     |
| 6.2.0-26-generic       | 23        | 9.27%   |
| 5.19.0-41-generic      | 23        | 9.27%   |
| 5.19.0-35-generic      | 23        | 9.27%   |
| 5.19.0-46-generic      | 22        | 8.87%   |
| 5.19.0-32-generic      | 22        | 8.87%   |
| 5.19.0-38-generic      | 16        | 6.45%   |
| 5.19.0-43-generic      | 13        | 5.24%   |
| 5.15.0-60-generic      | 9         | 3.63%   |
| 5.19.0-40-generic      | 6         | 2.42%   |
| 6.2.0-31-generic       | 5         | 2.02%   |
| 5.19.0-50-generic      | 5         | 2.02%   |
| 5.19.0-42-generic      | 5         | 2.02%   |
| 5.19.0-45-generic      | 3         | 1.21%   |
| 5.15.0-56-generic      | 2         | 0.81%   |
| 6.4.5-x64v3-xanmod1    | 1         | 0.4%    |
| 6.2.8-3-liquorix-amd64 | 1         | 0.4%    |
| 6.2.7-060207-generic   | 1         | 0.4%    |
| 6.2.2-surface          | 1         | 0.4%    |
| 6.2.14-surface         | 1         | 0.4%    |
| 6.1.9-060109-generic   | 1         | 0.4%    |
| 6.1.6-060106-generic   | 1         | 0.4%    |
| 6.1.0-1013-oem         | 1         | 0.4%    |
| 5.15.0-79-generic      | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 131       | 54.36%  |
| 5.15.0  | 74        | 30.71%  |
| 6.2.0   | 28        | 11.62%  |
| 6.4.5   | 1         | 0.41%   |
| 6.2.8   | 1         | 0.41%   |
| 6.2.7   | 1         | 0.41%   |
| 6.2.2   | 1         | 0.41%   |
| 6.2.14  | 1         | 0.41%   |
| 6.1.9   | 1         | 0.41%   |
| 6.1.6   | 1         | 0.41%   |
| 6.1.0   | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 131       | 54.58%  |
| 5.15    | 74        | 30.83%  |
| 6.2     | 31        | 12.92%  |
| 6.1     | 3         | 1.25%   |
| 6.4     | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 235       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 235       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 235       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 192       | 81.7%   |
| LightDM | 43        | 18.3%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 104       | 44.07%  |
| de_DE | 35        | 14.83%  |
| ru_RU | 19        | 8.05%   |
| es_ES | 19        | 8.05%   |
| pl_PL | 7         | 2.97%   |
| fr_FR | 7         | 2.97%   |
| it_IT | 6         | 2.54%   |
| pt_BR | 5         | 2.12%   |
| en_GB | 5         | 2.12%   |
| sv_SE | 4         | 1.69%   |
| en_AU | 4         | 1.69%   |
| nl_NL | 3         | 1.27%   |
| tr_TR | 2         | 0.85%   |
| pt_PT | 2         | 0.85%   |
| nb_NO | 2         | 0.85%   |
| en_CA | 2         | 0.85%   |
| el_GR | 2         | 0.85%   |
| uk_UA | 1         | 0.42%   |
| sk_SK | 1         | 0.42%   |
| ja_JP | 1         | 0.42%   |
| hu_HU | 1         | 0.42%   |
| fi_FI | 1         | 0.42%   |
| da_DK | 1         | 0.42%   |
| cs_CZ | 1         | 0.42%   |
| bg_BG | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 206       | 87.66%  |
| EFI  | 29        | 12.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 222       | 94.07%  |
| Tmpfs   | 8         | 3.39%   |
| Btrfs   | 3         | 1.27%   |
| Xfs     | 2         | 0.85%   |
| Overlay | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 192       | 81.7%   |
| GPT     | 35        | 14.89%  |
| MBR     | 8         | 3.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 232       | 98.72%  |
| Yes       | 3         | 1.28%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 220       | 93.62%  |
| Yes       | 15        | 6.38%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Apple                       | 40        | 17.02%  |
| Hewlett-Packard             | 35        | 14.89%  |
| Lenovo                      | 32        | 13.62%  |
| ASUSTek Computer            | 27        | 11.49%  |
| Dell                        | 19        | 8.09%   |
| Acer                        | 14        | 5.96%   |
| MSI                         | 10        | 4.26%   |
| Gigabyte Technology         | 9         | 3.83%   |
| HUAWEI                      | 5         | 2.13%   |
| Toshiba                     | 3         | 1.28%   |
| Fujitsu                     | 3         | 1.28%   |
| ASRock                      | 3         | 1.28%   |
| Alienware                   | 3         | 1.28%   |
| Unknown                     | 3         | 1.28%   |
| Sony                        | 2         | 0.85%   |
| Pegatron                    | 2         | 0.85%   |
| HONOR                       | 2         | 0.85%   |
| Google                      | 2         | 0.85%   |
| Foxconn                     | 2         | 0.85%   |
| Wortmann AG                 | 1         | 0.43%   |
| Star Labs                   | 1         | 0.43%   |
| SHENZHEN YOUDISI E-COMMERCE | 1         | 0.43%   |
| Samsung Electronics         | 1         | 0.43%   |
| Razer                       | 1         | 0.43%   |
| PCBOX                       | 1         | 0.43%   |
| Microsoft                   | 1         | 0.43%   |
| Medion                      | 1         | 0.43%   |
| MACHINIST                   | 1         | 0.43%   |
| Inventec                    | 1         | 0.43%   |
| Intel                       | 1         | 0.43%   |
| GPU Company                 | 1         | 0.43%   |
| GPD                         | 1         | 0.43%   |
| Gateway                     | 1         | 0.43%   |
| ECS                         | 1         | 0.43%   |
| Digma                       | 1         | 0.43%   |
| Clevo                       | 1         | 0.43%   |
| Chuwi                       | 1         | 0.43%   |
| AZW                         | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Apple MacBookPro9,2                        | 3         | 1.28%   |
| Apple MacBookPro8,1                        | 3         | 1.28%   |
| Apple iMac7,1                              | 3         | 1.28%   |
| Apple iMac12,1                             | 3         | 1.28%   |
| Unknown                                    | 3         | 1.28%   |
| HUAWEI BOD-WXX9                            | 2         | 0.85%   |
| HP 255 G7 Notebook PC                      | 2         | 0.85%   |
| Dell OptiPlex 790                          | 2         | 0.85%   |
| Dell Latitude E5570                        | 2         | 0.85%   |
| ASUS H110M-A/M.2                           | 2         | 0.85%   |
| Apple MacBookPro5,5                        | 2         | 0.85%   |
| Apple MacBookPro11,3                       | 2         | 0.85%   |
| Apple MacBookPro11,2                       | 2         | 0.85%   |
| Apple MacBookAir6,2                        | 2         | 0.85%   |
| Apple iMac11,2                             | 2         | 0.85%   |
| Wortmann AG TERRA_PC                       | 1         | 0.43%   |
| Toshiba TECRA Z40-C                        | 1         | 0.43%   |
| Toshiba TECRA R850                         | 1         | 0.43%   |
| Toshiba Satellite C660                     | 1         | 0.43%   |
| Star Labs StarBook                         | 1         | 0.43%   |
| Sony VPCEH2C5E                             | 1         | 0.43%   |
| Sony SVF1521O4E                            | 1         | 0.43%   |
| SHENZHEN YOUDISI E-COMMERCE A8S PRO        | 1         | 0.43%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.43%   |
| Razer Blade Stealth                        | 1         | 0.43%   |
| Pegatron Pro 3010 Microtower PC            | 1         | 0.43%   |
| Pegatron IPMIP-GS                          | 1         | 0.43%   |
| PCBOX Kant                                 | 1         | 0.43%   |
| MSI PE70 6QE                               | 1         | 0.43%   |
| MSI MS-7C52                                | 1         | 0.43%   |
| MSI MS-7C31                                | 1         | 0.43%   |
| MSI MS-7C02                                | 1         | 0.43%   |
| MSI MS-7B84                                | 1         | 0.43%   |
| MSI MS-7B17                                | 1         | 0.43%   |
| MSI MS-7816                                | 1         | 0.43%   |
| MSI GT72 2QE                               | 1         | 0.43%   |
| MSI GE62VR 6RF                             | 1         | 0.43%   |
| MSI CX61 2PC                               | 1         | 0.43%   |
| Microsoft Surface Pro 7                    | 1         | 0.43%   |
| Medion E15301                              | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 16        | 6.81%   |
| Acer Aspire        | 9         | 3.83%   |
| Dell Latitude      | 7         | 2.98%   |
| Lenovo IdeaPad     | 6         | 2.55%   |
| HP Pavilion        | 6         | 2.55%   |
| ASUS ZenBook       | 6         | 2.55%   |
| HP ProBook         | 5         | 2.13%   |
| ASUS VivoBook      | 5         | 2.13%   |
| Apple MacBookPro11 | 5         | 2.13%   |
| HP Laptop          | 4         | 1.7%    |
| Apple MacBookPro8  | 4         | 1.7%    |
| HP 255             | 3         | 1.28%   |
| Fujitsu LIFEBOOK   | 3         | 1.28%   |
| Dell XPS           | 3         | 1.28%   |
| Dell OptiPlex      | 3         | 1.28%   |
| Dell Inspiron      | 3         | 1.28%   |
| Apple MacBookPro9  | 3         | 1.28%   |
| Apple MacBookPro5  | 3         | 1.28%   |
| Apple iMac7        | 3         | 1.28%   |
| Apple iMac12       | 3         | 1.28%   |
| Unknown            | 3         | 1.28%   |
| Toshiba TECRA      | 2         | 0.85%   |
| Lenovo Yoga        | 2         | 0.85%   |
| Lenovo Legion      | 2         | 0.85%   |
| HUAWEI BOD-WXX9    | 2         | 0.85%   |
| HP ProDesk         | 2         | 0.85%   |
| HP ENVY            | 2         | 0.85%   |
| HP EliteDesk       | 2         | 0.85%   |
| HP EliteBook       | 2         | 0.85%   |
| ASUS ROG           | 2         | 0.85%   |
| ASUS PRIME         | 2         | 0.85%   |
| ASUS H110M-A       | 2         | 0.85%   |
| Apple Macmini6     | 2         | 0.85%   |
| Apple MacBookAir6  | 2         | 0.85%   |
| Apple MacBookAir3  | 2         | 0.85%   |
| Apple iMac11       | 2         | 0.85%   |
| Acer Predator      | 2         | 0.85%   |
| Wortmann AG TERRA  | 1         | 0.43%   |
| Toshiba Satellite  | 1         | 0.43%   |
| Star Labs StarBook | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 23        | 9.79%   |
| 2012 | 23        | 9.79%   |
| 2019 | 22        | 9.36%   |
| 2020 | 18        | 7.66%   |
| 2018 | 16        | 6.81%   |
| 2016 | 16        | 6.81%   |
| 2013 | 16        | 6.81%   |
| 2015 | 14        | 5.96%   |
| 2022 | 13        | 5.53%   |
| 2010 | 13        | 5.53%   |
| 2009 | 13        | 5.53%   |
| 2014 | 12        | 5.11%   |
| 2011 | 12        | 5.11%   |
| 2017 | 9         | 3.83%   |
| 2008 | 8         | 3.4%    |
| 2023 | 5         | 2.13%   |
| 2007 | 2         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 150       | 63.83%  |
| Desktop     | 58        | 24.68%  |
| All in one  | 13        | 5.53%   |
| Convertible | 7         | 2.98%   |
| Mini pc     | 4         | 1.7%    |
| Tablet      | 3         | 1.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 229       | 97.45%  |
| Enabled  | 6         | 2.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 232       | 98.72%  |
| Yes  | 3         | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 73        | 30.93%  |
| 16.01-24.0  | 48        | 20.34%  |
| 8.01-16.0   | 46        | 19.49%  |
| 3.01-4.0    | 42        | 17.8%   |
| 32.01-64.0  | 17        | 7.2%    |
| 64.01-256.0 | 4         | 1.69%   |
| 1.01-2.0    | 3         | 1.27%   |
| 2.01-3.0    | 2         | 0.85%   |
| 24.01-32.0  | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 107       | 43.32%  |
| 1.01-2.0  | 51        | 20.65%  |
| 3.01-4.0  | 48        | 19.43%  |
| 4.01-8.0  | 32        | 12.96%  |
| 8.01-16.0 | 6         | 2.43%   |
| 0.51-1.0  | 3         | 1.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 165       | 69.92%  |
| 2      | 55        | 23.31%  |
| 3      | 9         | 3.81%   |
| 4      | 4         | 1.69%   |
| 5      | 3         | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 154       | 65.25%  |
| Yes       | 82        | 34.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 79.57%  |
| No        | 48        | 20.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 202       | 85.96%  |
| No        | 33        | 14.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 77.45%  |
| No        | 53        | 22.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 46        | 19.49%  |
| Germany      | 39        | 16.53%  |
| Russia       | 17        | 7.2%    |
| Spain        | 9         | 3.81%   |
| France       | 8         | 3.39%   |
| Brazil       | 8         | 3.39%   |
| UK           | 7         | 2.97%   |
| Poland       | 7         | 2.97%   |
| Netherlands  | 7         | 2.97%   |
| Italy        | 7         | 2.97%   |
| India        | 7         | 2.97%   |
| Australia    | 6         | 2.54%   |
| Sweden       | 4         | 1.69%   |
| Portugal     | 4         | 1.69%   |
| Canada       | 4         | 1.69%   |
| Norway       | 3         | 1.27%   |
| Mexico       | 3         | 1.27%   |
| Indonesia    | 3         | 1.27%   |
| Greece       | 3         | 1.27%   |
| Argentina    | 3         | 1.27%   |
| Turkey       | 2         | 0.85%   |
| Thailand     | 2         | 0.85%   |
| Israel       | 2         | 0.85%   |
| Ireland      | 2         | 0.85%   |
| Czechia      | 2         | 0.85%   |
| Colombia     | 2         | 0.85%   |
| China        | 2         | 0.85%   |
| Chile        | 2         | 0.85%   |
| Belgium      | 2         | 0.85%   |
| Austria      | 2         | 0.85%   |
| Venezuela    | 1         | 0.42%   |
| Ukraine      | 1         | 0.42%   |
| Tunisia      | 1         | 0.42%   |
| Switzerland  | 1         | 0.42%   |
| South Africa | 1         | 0.42%   |
| Slovakia     | 1         | 0.42%   |
| Saudi Arabia | 1         | 0.42%   |
| Puerto Rico  | 1         | 0.42%   |
| Panama       | 1         | 0.42%   |
| Kazakhstan   | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 6         | 2.47%   |
| Warsaw                  | 3         | 1.23%   |
| Stuttgart               | 3         | 1.23%   |
| Munich                  | 3         | 1.23%   |
| Melbourne               | 3         | 1.23%   |
| Madrid                  | 3         | 1.23%   |
| Delhi                   | 3         | 1.23%   |
| Berlin                  | 3         | 1.23%   |
| Vienna                  | 2         | 0.82%   |
| Stockholm               | 2         | 0.82%   |
| St Petersburg           | 2         | 0.82%   |
| Perth                   | 2         | 0.82%   |
| Novosibirsk             | 2         | 0.82%   |
| Monza                   | 2         | 0.82%   |
| Los Angeles             | 2         | 0.82%   |
| Las Vegas               | 2         | 0.82%   |
| Jakarta                 | 2         | 0.82%   |
| Hamm                    | 2         | 0.82%   |
| Hamburg                 | 2         | 0.82%   |
| Faridabad               | 2         | 0.82%   |
| Córdoba                | 2         | 0.82%   |
| Cologne                 | 2         | 0.82%   |
| Brampton                | 2         | 0.82%   |
| Bangkok                 | 2         | 0.82%   |
| Aubagne                 | 2         | 0.82%   |
| Athens                  | 2         | 0.82%   |
| Amsterdam               | 2         | 0.82%   |
| Znojmo                  | 1         | 0.41%   |
| Zhuantang               | 1         | 0.41%   |
| Yorktown                | 1         | 0.41%   |
| Yekaterinburg           | 1         | 0.41%   |
| Wouldham                | 1         | 0.41%   |
| Worcestershire          | 1         | 0.41%   |
| Wilster                 | 1         | 0.41%   |
| Wilsdruff               | 1         | 0.41%   |
| Wiesbaden               | 1         | 0.41%   |
| West Jordan             | 1         | 0.41%   |
| Villingen-Schwenningen  | 1         | 0.41%   |
| Villefranche-sur-Saône | 1         | 0.41%   |
| Vigo                    | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 38        | 43     | 11.88%  |
| Samsung Electronics         | 37        | 43     | 11.56%  |
| Seagate                     | 26        | 33     | 8.13%   |
| Sandisk                     | 24        | 26     | 7.5%    |
| Toshiba                     | 20        | 25     | 6.25%   |
| Crucial                     | 19        | 21     | 5.94%   |
| Kingston                    | 13        | 15     | 4.06%   |
| Apple                       | 12        | 12     | 3.75%   |
| Unknown                     | 10        | 11     | 3.13%   |
| Hitachi                     | 9         | 10     | 2.81%   |
| Intel                       | 7         | 8      | 2.19%   |
| China                       | 7         | 7      | 2.19%   |
| SK hynix                    | 6         | 8      | 1.88%   |
| PNY                         | 5         | 5      | 1.56%   |
| Micron Technology           | 5         | 5      | 1.56%   |
| KIOXIA                      | 5         | 8      | 1.56%   |
| HGST                        | 4         | 5      | 1.25%   |
| Unknown                     | 4         | 4      | 1.25%   |
| Phison Electronics          | 3         | 3      | 0.94%   |
| Netac                       | 3         | 4      | 0.94%   |
| Micron/Crucial Technology   | 3         | 3      | 0.94%   |
| Kingston Technology Company | 3         | 3      | 0.94%   |
| Intenso                     | 3         | 5      | 0.94%   |
| A-DATA Technology           | 3         | 3      | 0.94%   |
| Team                        | 2         | 3      | 0.63%   |
| Silicon Motion              | 2         | 2      | 0.63%   |
| Realtek Semiconductor       | 2         | 4      | 0.63%   |
| KingDian                    | 2         | 3      | 0.63%   |
| JMicron Technology          | 2         | 2      | 0.63%   |
| Fujitsu                     | 2         | 2      | 0.63%   |
| BIWIN                       | 2         | 2      | 0.63%   |
| Apacer                      | 2         | 2      | 0.63%   |
| Yeestor                     | 1         | 1      | 0.31%   |
| XrayDisk                    | 1         | 1      | 0.31%   |
| VISIPRO                     | 1         | 1      | 0.31%   |
| USB30                       | 1         | 1      | 0.31%   |
| USB 3.0                     | 1         | 1      | 0.31%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.31%   |
| Union Memory                | 1         | 2      | 0.31%   |
| Transcend                   | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 6         | 1.81%   |
| Kingston SA400S37240G 240GB SSD                       | 6         | 1.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 5         | 1.51%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 4         | 1.2%    |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 4         | 1.2%    |
| Crucial CT500MX500SSD1 500GB                          | 4         | 1.2%    |
| Crucial CT240BX500SSD1 240GB                          | 4         | 1.2%    |
| Unknown                                               | 4         | 1.2%    |
| Unknown MMC Card  7GB                                 | 3         | 0.9%    |
| Toshiba MQ01ABD100 1TB                                | 3         | 0.9%    |
| Toshiba DT01ACA200 2TB                                | 3         | 0.9%    |
| Samsung SSD 850 EVO 250GB                             | 3         | 0.9%    |
| Phison E12 NVMe Controller 256GB                      | 3         | 0.9%    |
| Apple SSD SD0128F 121GB                               | 3         | 0.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 2         | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 2         | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 2         | 0.6%    |
| Unknown MMC Card  32GB                                | 2         | 0.6%    |
| Toshiba MK5065GSXF 500GB                              | 2         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive 512GB           | 2         | 0.6%    |
| Seagate ST9500325AS 500GB                             | 2         | 0.6%    |
| Seagate ST4000DM004-2CV104 4TB                        | 2         | 0.6%    |
| Seagate ST3500418AS 500GB                             | 2         | 0.6%    |
| Seagate Expansion 2TB                                 | 2         | 0.6%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 2         | 0.6%    |
| SanDisk SDSSDA240G 240GB                              | 2         | 0.6%    |
| Samsung SSD 860 EVO 1TB                               | 2         | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 2         | 0.6%    |
| Samsung MZNLH128HBHQ-000H1 128GB SSD                  | 2         | 0.6%    |
| PNY CS900 480GB SSD                                   | 2         | 0.6%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 2         | 0.6%    |
| Kingston Company SNV2S1000G 1TB                       | 2         | 0.6%    |
| KingDian S280 240GB                                   | 2         | 0.6%    |
| Intenso SSD SATAIII 240GB                             | 2         | 0.6%    |
| Intel SSDPEKNU512GZ 512GB                             | 2         | 0.6%    |
| HGST HTS721010A9E630 1TB                              | 2         | 0.6%    |
| Crucial CT275MX300SSD1 275GB                          | 2         | 0.6%    |
| Crucial CT250MX500SSD1 250GB                          | 2         | 0.6%    |
| Crucial CT1000MX500SSD1 1TB                           | 2         | 0.6%    |
| Apple SSD SM0512F 500GB                               | 2         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 29     | 30.59%  |
| Seagate             | 24        | 29     | 28.24%  |
| Toshiba             | 15        | 17     | 17.65%  |
| Hitachi             | 9         | 10     | 10.59%  |
| HGST                | 4         | 5      | 4.71%   |
| Samsung Electronics | 2         | 2      | 2.35%   |
| Fujitsu             | 2         | 2      | 2.35%   |
| Unknown             | 1         | 1      | 1.18%   |
| ASMT                | 1         | 1      | 1.18%   |
| Apple               | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 19        | 21     | 14.18%  |
| Samsung Electronics | 16        | 19     | 11.94%  |
| SanDisk             | 13        | 14     | 9.7%    |
| Kingston            | 12        | 14     | 8.96%   |
| Apple               | 10        | 10     | 7.46%   |
| WDC                 | 8         | 10     | 5.97%   |
| China               | 7         | 7      | 5.22%   |
| PNY                 | 5         | 5      | 3.73%   |
| Toshiba             | 4         | 6      | 2.99%   |
| A-DATA Technology   | 3         | 3      | 2.24%   |
| Team                | 2         | 3      | 1.49%   |
| Seagate             | 2         | 2      | 1.49%   |
| Netac               | 2         | 2      | 1.49%   |
| Micron Technology   | 2         | 2      | 1.49%   |
| KingDian            | 2         | 3      | 1.49%   |
| Intenso             | 2         | 4      | 1.49%   |
| Apacer              | 2         | 2      | 1.49%   |
| XrayDisk            | 1         | 1      | 0.75%   |
| VISIPRO             | 1         | 1      | 0.75%   |
| USB30               | 1         | 1      | 0.75%   |
| Transcend           | 1         | 1      | 0.75%   |
| SPCC                | 1         | 1      | 0.75%   |
| SK hynix            | 1         | 1      | 0.75%   |
| SD                  | 1         | 1      | 0.75%   |
| Phison              | 1         | 1      | 0.75%   |
| OWC                 | 1         | 1      | 0.75%   |
| OCZ-VERTEX2         | 1         | 1      | 0.75%   |
| NGFF                | 1         | 1      | 0.75%   |
| MaiChai             | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| LITEON              | 1         | 1      | 0.75%   |
| KUU                 | 1         | 1      | 0.75%   |
| JMicron Technology  | 1         | 1      | 0.75%   |
| Intel               | 1         | 1      | 0.75%   |
| Inland              | 1         | 1      | 0.75%   |
| HS-SSD-E100         | 1         | 1      | 0.75%   |
| Hewlett-Packard     | 1         | 1      | 0.75%   |
| Corsair             | 1         | 1      | 0.75%   |
| BIWIN               | 1         | 1      | 0.75%   |
| Unknown             | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 125       | 150    | 41.53%  |
| NVMe    | 78        | 93     | 25.91%  |
| HDD     | 73        | 97     | 24.25%  |
| Unknown | 15        | 16     | 4.98%   |
| MMC     | 10        | 11     | 3.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 173       | 246    | 62.45%  |
| NVMe | 78        | 93     | 28.16%  |
| SAS  | 16        | 17     | 5.78%   |
| MMC  | 10        | 11     | 3.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 132       | 164    | 66.67%  |
| 0.51-1.0   | 48        | 63     | 24.24%  |
| 1.01-2.0   | 15        | 17     | 7.58%   |
| 3.01-4.0   | 3         | 3      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 104       | 43.88%  |
| 251-500        | 64        | 27%     |
| 501-1000       | 38        | 16.03%  |
| 51-100         | 16        | 6.75%   |
| 2001-3000      | 5         | 2.11%   |
| 1001-2000      | 4         | 1.69%   |
| 21-50          | 3         | 1.27%   |
| 1-20           | 2         | 0.84%   |
| More than 3000 | 1         | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 117       | 48.35%  |
| 21-50          | 63        | 26.03%  |
| 101-250        | 25        | 10.33%  |
| 51-100         | 25        | 10.33%  |
| 251-500        | 7         | 2.89%   |
| 1001-2000      | 3         | 1.24%   |
| More than 3000 | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 210       | 329    | 86.07%  |
| Works    | 33        | 37     | 13.52%  |
| Malfunc  | 1         | 1      | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 162       | 56.25%  |
| AMD                            | 33        | 11.46%  |
| Samsung Electronics            | 26        | 9.03%   |
| SanDisk                        | 14        | 4.86%   |
| Nvidia                         | 7         | 2.43%   |
| SK hynix                       | 5         | 1.74%   |
| Marvell Technology Group       | 5         | 1.74%   |
| KIOXIA                         | 5         | 1.74%   |
| Phison Electronics             | 4         | 1.39%   |
| Kingston Technology Company    | 4         | 1.39%   |
| Micron/Crucial Technology      | 3         | 1.04%   |
| Micron Technology              | 3         | 1.04%   |
| ASMedia Technology             | 3         | 1.04%   |
| Union Memory (Shenzhen)        | 2         | 0.69%   |
| Toshiba America Info Systems   | 2         | 0.69%   |
| Solid State Storage Technology | 2         | 0.69%   |
| Silicon Motion                 | 2         | 0.69%   |
| Realtek Semiconductor          | 2         | 0.69%   |
| Shenzhen Longsys Electronics   | 1         | 0.35%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.35%   |
| INNOGRIT                       | 1         | 0.35%   |
| Biwin Storage Technology       | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 27        | 8.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 5.64%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 3.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 3.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 3.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 2.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 2.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.88%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 1.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.88%   |
| Nvidia MCP79 AHCI Controller                                                   | 5         | 1.57%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 1.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.25%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.25%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.25%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.94%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 3         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.94%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.94%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 3         | 0.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.94%   |
| Intel SSD 660P Series                                                          | 3         | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3         | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.94%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 187       | 62.96%  |
| NVMe | 77        | 25.93%  |
| RAID | 19        | 6.4%    |
| IDE  | 14        | 4.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 191       | 81.28%  |
| AMD    | 44        | 18.72%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 6         | 2.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 5         | 2.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 4         | 1.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz               | 4         | 1.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 4         | 1.7%    |
| Intel Core i9-9900K CPU @ 3.60GHz               | 3         | 1.28%   |
| Intel Core i5-2435M CPU @ 2.40GHz               | 3         | 1.28%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 3         | 1.28%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 3         | 1.28%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 2         | 0.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 2         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 0.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 0.85%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz              | 2         | 0.85%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 2         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 0.85%   |
| Intel Core i5-2400S CPU @ 2.50GHz               | 2         | 0.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 0.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 2         | 0.85%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 0.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 0.85%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 2         | 0.85%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 2         | 0.85%   |
| Intel Celeron N5105 @ 2.00GHz                   | 2         | 0.85%   |
| Intel 12th Gen Core i7-1260P                    | 2         | 0.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 0.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 0.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 2         | 0.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 0.85%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 0.85%   |
| Intel Xeon CPU W3520 @ 2.67GHz                  | 1         | 0.43%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz             | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz     | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 0.43%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 0.43%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.43%   |
| Intel Pentium CPU J2900 @ 2.41GHz               | 1         | 0.43%   |
| Intel Pentium CPU G2020 @ 2.90GHz               | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 61        | 25.96%  |
| Intel Core i7           | 40        | 17.02%  |
| Other                   | 25        | 10.64%  |
| Intel Core 2 Duo        | 18        | 7.66%   |
| Intel Core i3           | 17        | 7.23%   |
| Intel Celeron           | 16        | 6.81%   |
| AMD Ryzen 7             | 10        | 4.26%   |
| AMD Ryzen 5             | 10        | 4.26%   |
| Intel Pentium           | 5         | 2.13%   |
| Intel Pentium Dual-Core | 3         | 1.28%   |
| Intel Core i9           | 3         | 1.28%   |
| AMD Ryzen 3             | 3         | 1.28%   |
| AMD Athlon              | 3         | 1.28%   |
| AMD A8                  | 3         | 1.28%   |
| Intel Xeon              | 2         | 0.85%   |
| Intel Pentium Silver    | 2         | 0.85%   |
| AMD Ryzen 9             | 2         | 0.85%   |
| AMD Ryzen 5 PRO         | 2         | 0.85%   |
| AMD A4                  | 2         | 0.85%   |
| AMD A12                 | 2         | 0.85%   |
| AMD Sempron             | 1         | 0.43%   |
| AMD Phenom II X6        | 1         | 0.43%   |
| AMD G                   | 1         | 0.43%   |
| AMD FX                  | 1         | 0.43%   |
| AMD E1                  | 1         | 0.43%   |
| AMD A6                  | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 108       | 45.76%  |
| 4      | 82        | 34.75%  |
| 8      | 17        | 7.2%    |
| 6      | 13        | 5.51%   |
| 12     | 6         | 2.54%   |
| 1      | 5         | 2.12%   |
| 10     | 2         | 0.85%   |
| 5      | 2         | 0.85%   |
| 14     | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 235       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 169       | 71.91%  |
| 1      | 66        | 28.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 235       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 198       | 83.54%  |
| 0x806ec    | 3         | 1.27%   |
| 0x806c1    | 3         | 1.27%   |
| 0x706e5    | 3         | 1.27%   |
| 0x906e9    | 2         | 0.84%   |
| 0x906a4    | 2         | 0.84%   |
| 0x806d1    | 2         | 0.84%   |
| 0x706a8    | 2         | 0.84%   |
| 0x306a9    | 2         | 0.84%   |
| 0x206a7    | 2         | 0.84%   |
| 0x0a50000c | 2         | 0.84%   |
| 0x906ec    | 1         | 0.42%   |
| 0x906c0    | 1         | 0.42%   |
| 0x906a3    | 1         | 0.42%   |
| 0x806eb    | 1         | 0.42%   |
| 0x806ea    | 1         | 0.42%   |
| 0x706a1    | 1         | 0.42%   |
| 0x40661    | 1         | 0.42%   |
| 0x40651    | 1         | 0.42%   |
| 0x1067a    | 1         | 0.42%   |
| 0x10676    | 1         | 0.42%   |
| 0x0a50000d | 1         | 0.42%   |
| 0x08600106 | 1         | 0.42%   |
| 0x08108109 | 1         | 0.42%   |
| 0x07030106 | 1         | 0.42%   |
| 0x0600611a | 1         | 0.42%   |
| 0x010000c8 | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 12.34%  |
| Haswell          | 24        | 10.21%  |
| IvyBridge        | 22        | 9.36%   |
| Penryn           | 18        | 7.66%   |
| Skylake          | 16        | 6.81%   |
| SandyBridge      | 16        | 6.81%   |
| TigerLake        | 13        | 5.53%   |
| Unknown          | 13        | 5.53%   |
| Goldmont plus    | 11        | 4.68%   |
| Zen+             | 8         | 3.4%    |
| Westmere         | 8         | 3.4%    |
| Zen 3            | 7         | 2.98%   |
| Zen 2            | 6         | 2.55%   |
| IceLake          | 6         | 2.55%   |
| Broadwell        | 5         | 2.13%   |
| Zen              | 4         | 1.7%    |
| Silvermont       | 4         | 1.7%    |
| Excavator        | 4         | 1.7%    |
| Core             | 4         | 1.7%    |
| Puma             | 3         | 1.28%   |
| Alderlake Hybrid | 3         | 1.28%   |
| Steamroller      | 2         | 0.85%   |
| Piledriver       | 2         | 0.85%   |
| Nehalem          | 2         | 0.85%   |
| K10              | 2         | 0.85%   |
| Tremont          | 1         | 0.43%   |
| CometLake        | 1         | 0.43%   |
| Bobcat           | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 153       | 55.43%  |
| AMD    | 63        | 22.83%  |
| Nvidia | 60        | 21.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 17        | 6.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 13        | 4.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 9         | 3.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 9         | 3.19%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 9         | 3.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 8         | 2.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7         | 2.48%   |
| Intel HD Graphics 530                                                     | 6         | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                       | 6         | 2.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 6         | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 1.77%   |
| Intel HD Graphics 630                                                     | 5         | 1.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 1.77%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 4         | 1.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 1.42%   |
| AMD Lucienne                                                              | 4         | 1.42%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.06%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 3         | 1.06%   |
| Nvidia C79 [GeForce 9400M]                                                | 3         | 1.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 1.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.06%   |
| Intel HD Graphics 620                                                     | 3         | 1.06%   |
| Intel HD Graphics 5500                                                    | 3         | 1.06%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 3         | 1.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 3         | 1.06%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 3         | 1.06%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 3         | 1.06%   |
| AMD Renoir                                                                | 3         | 1.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3         | 1.06%   |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 2         | 0.71%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 2         | 0.71%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                               | 2         | 0.71%   |
| Nvidia GK107 [GeForce GTX 650]                                            | 2         | 0.71%   |
| Nvidia GK107 [GeForce GT 640]                                             | 2         | 0.71%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 2         | 0.71%   |
| Intel UHD Graphics 620                                                    | 2         | 0.71%   |
| Intel JasperLake [UHD Graphics]                                           | 2         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 114       | 48.51%  |
| 1 x AMD         | 52        | 22.13%  |
| 1 x Nvidia      | 29        | 12.34%  |
| Intel + Nvidia  | 27        | 11.49%  |
| Intel + AMD     | 5         | 2.13%   |
| 2 x AMD         | 3         | 1.28%   |
| AMD + Nvidia    | 2         | 0.85%   |
| Other           | 1         | 0.43%   |
| 2 x Nvidia      | 1         | 0.43%   |
| Intel + 2 x AMD | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 220       | 93.62%  |
| Proprietary | 12        | 5.11%   |
| Unknown     | 3         | 1.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 220       | 93.62%  |
| 0.01-0.5   | 4         | 1.7%    |
| 7.01-8.0   | 3         | 1.28%   |
| 1.01-2.0   | 3         | 1.28%   |
| 0.51-1.0   | 3         | 1.28%   |
| 3.01-4.0   | 2         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 36        | 14.46%  |
| AU Optronics            | 30        | 12.05%  |
| LG Display              | 27        | 10.84%  |
| BOE                     | 24        | 9.64%   |
| Samsung Electronics     | 20        | 8.03%   |
| Chimei Innolux          | 18        | 7.23%   |
| Goldstar                | 12        | 4.82%   |
| Dell                    | 11        | 4.42%   |
| Sharp                   | 8         | 3.21%   |
| Acer                    | 5         | 2.01%   |
| Lenovo                  | 4         | 1.61%   |
| Hewlett-Packard         | 4         | 1.61%   |
| ViewSonic               | 3         | 1.2%    |
| Philips                 | 3         | 1.2%    |
| PANDA                   | 3         | 1.2%    |
| BenQ                    | 3         | 1.2%    |
| Vizio                   | 2         | 0.8%    |
| Sceptre Tech            | 2         | 0.8%    |
| NEC Computers           | 2         | 0.8%    |
| Chi Mei Optoelectronics | 2         | 0.8%    |
| ASUSTek Computer        | 2         | 0.8%    |
| AOC                     | 2         | 0.8%    |
| ___                     | 1         | 0.4%    |
| XCX                     | 1         | 0.4%    |
| Unknown                 | 1         | 0.4%    |
| Toshiba                 | 1         | 0.4%    |
| Sony                    | 1         | 0.4%    |
| RGT                     | 1         | 0.4%    |
| RCA                     | 1         | 0.4%    |
| Positivo                | 1         | 0.4%    |
| Panasonic               | 1         | 0.4%    |
| NSL                     | 1         | 0.4%    |
| MYS                     | 1         | 0.4%    |
| MSI                     | 1         | 0.4%    |
| Mi                      | 1         | 0.4%    |
| LG Philips              | 1         | 0.4%    |
| Kogan                   | 1         | 0.4%    |
| InfoVision              | 1         | 0.4%    |
| Idek Iiyama             | 1         | 0.4%    |
| Hitachi                 | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 1.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 1.17%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                     | 3         | 1.17%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 3         | 1.17%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch        | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.78%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 0.78%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 2         | 0.78%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 2         | 0.78%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 2         | 0.78%   |
| Apple LCD Monitor Color LCD 2880x1800                                | 2         | 0.78%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch               | 2         | 0.78%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 2         | 0.78%   |
| Apple Color LCD APPA019 2880x1800 331x207mm 15.4-inch                | 2         | 0.78%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                | 2         | 0.78%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 2         | 0.78%   |
| Apple Color LCD APP9C6C 1920x1200 520x320mm 24.0-inch                | 2         | 0.78%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                | 2         | 0.78%   |
| ___ LCDTV16 ___3393 1920x1080                                        | 1         | 0.39%   |
| XCX LCD Monitor XCX0844 1366x768 256x144mm 11.6-inch                 | 1         | 0.39%   |
| Vizio SV470M VIZ0057 1920x1080 1039x584mm 46.9-inch                  | 1         | 0.39%   |
| Vizio E420VO VIZ0070 1920x1080 930x523mm 42.0-inch                   | 1         | 0.39%   |
| ViewSonic VP201b VSC6911 1600x1200 408x306mm 20.1-inch               | 1         | 0.39%   |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                  | 1         | 0.39%   |
| Toshiba PI-KVM Video TSB8888 1920x1080                               | 1         | 0.39%   |
| Sony TV SNY7A02 1360x768 576x324mm 26.0-inch                         | 1         | 0.39%   |
| Sharp LCD Monitor SHP151C 1920x1080 344x194mm 15.5-inch              | 1         | 0.39%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 1         | 0.39%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch              | 1         | 0.39%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch              | 1         | 0.39%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.39%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch              | 1         | 0.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 1         | 0.39%   |
| Sharp HDMI SHP1048 1920x1080 820x460mm 37.0-inch                     | 1         | 0.39%   |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch       | 1         | 0.39%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch               | 1         | 0.39%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch    | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 114       | 47.11%  |
| 1366x768 (WXGA)    | 44        | 18.18%  |
| 1280x800 (WXGA)    | 12        | 4.96%   |
| 1920x1200 (WUXGA)  | 10        | 4.13%   |
| 3840x2160 (4K)     | 8         | 3.31%   |
| 2880x1800          | 8         | 3.31%   |
| 2560x1440 (QHD)    | 7         | 2.89%   |
| 1440x900 (WXGA+)   | 7         | 2.89%   |
| 1680x1050 (WSXGA+) | 5         | 2.07%   |
| 1600x900 (HD+)     | 5         | 2.07%   |
| 3440x1440          | 3         | 1.24%   |
| 2560x1600          | 3         | 1.24%   |
| 2560x1080          | 3         | 1.24%   |
| 1280x1024 (SXGA)   | 3         | 1.24%   |
| 1360x768           | 2         | 0.83%   |
| 3840x2400          | 1         | 0.41%   |
| 3840x1080          | 1         | 0.41%   |
| 3360x1080          | 1         | 0.41%   |
| 2880x1920          | 1         | 0.41%   |
| 2736x1824          | 1         | 0.41%   |
| 1920x1280          | 1         | 0.41%   |
| 1600x1200          | 1         | 0.41%   |
| Unknown            | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 72        | 28.46%  |
| 13      | 34        | 13.44%  |
| 14      | 23        | 9.09%   |
| 21      | 19        | 7.51%   |
| 24      | 16        | 6.32%   |
| 27      | 15        | 5.93%   |
| 17      | 12        | 4.74%   |
| 23      | 6         | 2.37%   |
| 12      | 6         | 2.37%   |
| 20      | 5         | 1.98%   |
| 18      | 5         | 1.98%   |
| 11      | 5         | 1.98%   |
| Unknown | 5         | 1.98%   |
| 34      | 4         | 1.58%   |
| 31      | 4         | 1.58%   |
| 19      | 3         | 1.19%   |
| 84      | 2         | 0.79%   |
| 60      | 2         | 0.79%   |
| 26      | 2         | 0.79%   |
| 22      | 2         | 0.79%   |
| 72      | 1         | 0.4%    |
| 65      | 1         | 0.4%    |
| 54      | 1         | 0.4%    |
| 49      | 1         | 0.4%    |
| 42      | 1         | 0.4%    |
| 36      | 1         | 0.4%    |
| 35      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 29      | 1         | 0.4%    |
| 28      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 40.24%  |
| 201-300     | 38        | 15.14%  |
| 501-600     | 37        | 14.74%  |
| 401-500     | 32        | 12.75%  |
| 351-400     | 16        | 6.37%   |
| 701-800     | 6         | 2.39%   |
| 601-700     | 6         | 2.39%   |
| 1001-1500   | 5         | 1.99%   |
| Unknown     | 5         | 1.99%   |
| 1501-2000   | 3         | 1.2%    |
| 801-900     | 1         | 0.4%    |
| 901-1000    | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 172       | 72.27%  |
| 16/10   | 45        | 18.91%  |
| 21/9    | 6         | 2.52%   |
| 3/2     | 5         | 2.1%    |
| Unknown | 4         | 1.68%   |
| 4/3     | 3         | 1.26%   |
| 6/5     | 1         | 0.42%   |
| 5/4     | 1         | 0.42%   |
| 32/9    | 1         | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 74        | 29.48%  |
| 81-90          | 40        | 15.94%  |
| 201-250        | 29        | 11.55%  |
| 71-80          | 17        | 6.77%   |
| 301-350        | 16        | 6.37%   |
| 151-200        | 14        | 5.58%   |
| 351-500        | 11        | 4.38%   |
| 251-300        | 8         | 3.19%   |
| 121-130        | 8         | 3.19%   |
| More than 1000 | 7         | 2.79%   |
| 61-70          | 5         | 1.99%   |
| 51-60          | 5         | 1.99%   |
| 141-150        | 5         | 1.99%   |
| Unknown        | 5         | 1.99%   |
| 131-140        | 4         | 1.59%   |
| 501-1000       | 3         | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 82        | 33.61%  |
| 101-120       | 70        | 28.69%  |
| 51-100        | 58        | 23.77%  |
| 161-240       | 18        | 7.38%   |
| 1-50          | 6         | 2.46%   |
| More than 240 | 5         | 2.05%   |
| Unknown       | 5         | 2.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 204       | 86.44%  |
| 2     | 28        | 11.86%  |
| 0     | 3         | 1.27%   |
| 3     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 102       | 28.98%  |
| Intel                             | 102       | 28.98%  |
| Broadcom                          | 47        | 13.35%  |
| Qualcomm Atheros                  | 39        | 11.08%  |
| Marvell Technology Group          | 8         | 2.27%   |
| Broadcom Limited                  | 6         | 1.7%    |
| TP-Link                           | 5         | 1.42%   |
| Samsung Electronics               | 5         | 1.42%   |
| Ralink Technology                 | 5         | 1.42%   |
| Nvidia                            | 5         | 1.42%   |
| Xiaomi                            | 3         | 0.85%   |
| Qualcomm                          | 3         | 0.85%   |
| MediaTek                          | 3         | 0.85%   |
| Huawei Technologies               | 3         | 0.85%   |
| Ralink                            | 2         | 0.57%   |
| NetGear                           | 2         | 0.57%   |
| Ericsson Business Mobile Networks | 2         | 0.57%   |
| Dell                              | 2         | 0.57%   |
| ASIX Electronics                  | 2         | 0.57%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.28%   |
| Sierra Wireless                   | 1         | 0.28%   |
| OPPO Electronics                  | 1         | 0.28%   |
| Motorola PCS                      | 1         | 0.28%   |
| Linksys                           | 1         | 0.28%   |
| ASUSTek Computer                  | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 15.49%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 2.82%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 2.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 11        | 2.58%   |
| Intel Wireless 8260                                               | 10        | 2.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 10        | 2.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.64%   |
| Intel Wireless 3165                                               | 7         | 1.64%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.41%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.17%   |
| Nvidia MCP79 Ethernet                                             | 5         | 1.17%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 5         | 1.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5         | 1.17%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 1.17%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 5         | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 0.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.94%   |
| Intel Wireless 7265                                               | 4         | 0.94%   |
| Intel Wireless 7260                                               | 4         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.7%    |
| Ralink RT5370 Wireless Adapter                                    | 3         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.7%    |
| Intel Wireless-AC 9260                                            | 3         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 3         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 82        | 37.79%  |
| Broadcom                          | 39        | 17.97%  |
| Realtek Semiconductor             | 37        | 17.05%  |
| Qualcomm Atheros                  | 30        | 13.82%  |
| Ralink Technology                 | 5         | 2.3%    |
| Broadcom Limited                  | 5         | 2.3%    |
| TP-Link                           | 4         | 1.84%   |
| MediaTek                          | 3         | 1.38%   |
| Ralink                            | 2         | 0.92%   |
| Qualcomm                          | 2         | 0.92%   |
| Marvell Technology Group          | 2         | 0.92%   |
| Sierra Wireless                   | 1         | 0.46%   |
| NetGear                           | 1         | 0.46%   |
| Linksys                           | 1         | 0.46%   |
| Ericsson Business Mobile Networks | 1         | 0.46%   |
| Dell                              | 1         | 0.46%   |
| ASUSTek Computer                  | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 5.43%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 5.43%   |
| Intel Wireless 8260                                            | 10        | 4.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 10        | 4.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 3.17%   |
| Intel Wireless 3165                                            | 7         | 3.17%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 2.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 5         | 2.26%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 5         | 2.26%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 5         | 2.26%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 1.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 4         | 1.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.81%   |
| Intel Wireless 7265                                            | 4         | 1.81%   |
| Intel Wireless 7260                                            | 4         | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 1.81%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 1.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 1.36%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.36%   |
| Ralink RT5370 Wireless Adapter                                 | 3         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.36%   |
| Intel Wireless-AC 9260                                         | 3         | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.36%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 1.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.9%    |
| Realtek 802.11n WLAN Adapter                                   | 2         | 0.9%    |
| Realtek 802.11ac NIC                                           | 2         | 0.9%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 2         | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 85        | 42.08%  |
| Intel                      | 50        | 24.75%  |
| Broadcom                   | 22        | 10.89%  |
| Qualcomm Atheros           | 15        | 7.43%   |
| Marvell Technology Group   | 6         | 2.97%   |
| Samsung Electronics        | 5         | 2.48%   |
| Nvidia                     | 5         | 2.48%   |
| Xiaomi                     | 3         | 1.49%   |
| Huawei Technologies        | 3         | 1.49%   |
| ASIX Electronics           | 2         | 0.99%   |
| ZTE WCDMA Technologies MSM | 1         | 0.5%    |
| TP-Link                    | 1         | 0.5%    |
| Qualcomm                   | 1         | 0.5%    |
| OPPO Electronics           | 1         | 0.5%    |
| NetGear                    | 1         | 0.5%    |
| Broadcom Limited           | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 32.67%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 11        | 5.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.46%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 2.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.48%   |
| Nvidia MCP79 Ethernet                                             | 5         | 2.48%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 5         | 2.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.49%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 1.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 1.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.99%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.99%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.99%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.99%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.99%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.99%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.99%   |
| Huawei MLA-L11                                                    | 2         | 0.99%   |
| ZTE WCDMA MSM Unisoc Phone                                        | 1         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.5%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.5%    |
| Qualcomm Redmi Note 8                                             | 1         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 202       | 51.53%  |
| Ethernet | 187       | 47.7%   |
| Modem    | 2         | 0.51%   |
| Unknown  | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 61.76%  |
| Ethernet | 91        | 38.24%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 133       | 56.6%   |
| 1     | 94        | 40%     |
| 3     | 5         | 2.13%   |
| 0     | 3         | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 165       | 69.92%  |
| Yes  | 71        | 30.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 40.66%  |
| Apple                           | 38        | 20.88%  |
| Realtek Semiconductor           | 23        | 12.64%  |
| Qualcomm Atheros Communications | 10        | 5.49%   |
| Broadcom                        | 7         | 3.85%   |
| Lite-On Technology              | 6         | 3.3%    |
| Foxconn / Hon Hai               | 6         | 3.3%    |
| IMC Networks                    | 5         | 2.75%   |
| Cambridge Silicon Radio         | 5         | 2.75%   |
| ASUSTek Computer                | 2         | 1.1%    |
| Toshiba                         | 1         | 0.55%   |
| Ralink                          | 1         | 0.55%   |
| MediaTek                        | 1         | 0.55%   |
| Hewlett-Packard                 | 1         | 0.55%   |
| Askey Computer                  | 1         | 0.55%   |
| Unknown                         | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 26        | 14.29%  |
| Intel AX201 Bluetooth                               | 17        | 9.34%   |
| Apple Bluetooth Host Controller                     | 15        | 8.24%   |
| Realtek Bluetooth Radio                             | 12        | 6.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 6.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 5.49%   |
| Apple Bluetooth USB Host Controller                 | 10        | 5.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 4.4%    |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 3.3%    |
| Intel AX200 Bluetooth                               | 6         | 3.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 2.75%   |
| Apple Bluetooth HCI                                 | 5         | 2.75%   |
| Lite-On Bluetooth Device                            | 4         | 2.2%    |
| Intel AX210 Bluetooth                               | 4         | 2.2%    |
| Intel Bluetooth Device                              | 3         | 1.65%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.65%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.1%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 1.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.1%    |
| Toshiba Bluetooth Device                            | 1         | 0.55%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.55%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.55%   |
| MediaTek Wireless_Device                            | 1         | 0.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.55%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.55%   |
| IMC Networks Bluetooth                              | 1         | 0.55%   |
| IMC Networks BCM20702A0                             | 1         | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.55%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.55%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.55%   |
| Broadcom Bluetooth 3.0 USB Dongle                   | 1         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 184       | 59.35%  |
| AMD                      | 59        | 19.03%  |
| Nvidia                   | 41        | 13.23%  |
| C-Media Electronics      | 8         | 2.58%   |
| Logitech                 | 5         | 1.61%   |
| Sony                     | 1         | 0.32%   |
| Realtek Semiconductor    | 1         | 0.32%   |
| Razer USA                | 1         | 0.32%   |
| Nordic Semiconductor ASA | 1         | 0.32%   |
| Microsoft                | 1         | 0.32%   |
| KTMicro                  | 1         | 0.32%   |
| Hewlett-Packard          | 1         | 0.32%   |
| Goldvish                 | 1         | 0.32%   |
| GN Netcom                | 1         | 0.32%   |
| Generalplus Technology   | 1         | 0.32%   |
| Dell                     | 1         | 0.32%   |
| Creative Labs            | 1         | 0.32%   |
| ASUSTek Computer         | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 18        | 4.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 4.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 3.49%   |
| Intel Sunrise Point-LP HD Audio                                            | 13        | 3.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 3.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11        | 2.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 2.42%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 2.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 2.15%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7         | 1.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.61%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.61%   |
| Nvidia MCP79 High Definition Audio                                         | 5         | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.34%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.34%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.34%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.08%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.08%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4         | 1.08%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 1.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 0.81%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 0.81%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 0.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 30.77%  |
| Micron Technology   | 11        | 21.15%  |
| SK hynix            | 6         | 11.54%  |
| Kingston            | 4         | 7.69%   |
| Unknown (ABCD)      | 2         | 3.85%   |
| Unknown             | 2         | 3.85%   |
| Unknown (0x5846)    | 1         | 1.92%   |
| Unknown             | 1         | 1.92%   |
| Ramaxel Technology  | 1         | 1.92%   |
| pqi                 | 1         | 1.92%   |
| GSkill              | 1         | 1.92%   |
| Elpida              | 1         | 1.92%   |
| CSX                 | 1         | 1.92%   |
| Crucial             | 1         | 1.92%   |
| Corsair             | 1         | 1.92%   |
| Apacer              | 1         | 1.92%   |
| A-DATA Technology   | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 3.85%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 3.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 3.85%   |
| Unknown                                                          | 2         | 3.85%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.92%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.92%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.92%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.92%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.92%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.92%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.92%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.92%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 1.92%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 1.92%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.92%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.92%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s              | 1         | 1.92%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.92%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.92%   |
| Ramaxel RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.92%   |
| pqi RAM Module 2GB SODIMM DDR2 667MT/s                           | 1         | 1.92%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.92%   |
| Micron RAM MT53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.92%   |
| Micron RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 1.92%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.92%   |
| Micron RAM 16ATF4G64HZ-3G2E2 32GB SODIMM DDR4 3200MT/s           | 1         | 1.92%   |
| Micron RAM 16ATF2G64HZ-2G6E3 16GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 1.92%   |
| Kingston RAM HX426C16FB/4 4GB DIMM DDR4 2800MT/s                 | 1         | 1.92%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1600MT/s                  | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 22        | 47.83%  |
| DDR3    | 12        | 26.09%  |
| LPDDR4  | 7         | 15.22%  |
| SDRAM   | 1         | 2.17%   |
| LPDDR3  | 1         | 2.17%   |
| DDR5    | 1         | 2.17%   |
| DDR2    | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 63.04%  |
| Row Of Chips | 9         | 19.57%  |
| DIMM         | 8         | 17.39%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 27        | 57.45%  |
| 4096  | 10        | 21.28%  |
| 2048  | 5         | 10.64%  |
| 16384 | 4         | 8.51%   |
| 32768 | 1         | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 12        | 24.49%  |
| 2667  | 9         | 18.37%  |
| 1600  | 8         | 16.33%  |
| 4267  | 5         | 10.2%   |
| 2400  | 4         | 8.16%   |
| 2800  | 2         | 4.08%   |
| 1333  | 2         | 4.08%   |
| 4800  | 1         | 2.04%   |
| 2133  | 1         | 2.04%   |
| 2000  | 1         | 2.04%   |
| 1066  | 1         | 2.04%   |
| 800   | 1         | 2.04%   |
| 667   | 1         | 2.04%   |
| 533   | 1         | 2.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung M2020 Series   | 1         | 33.33%  |
| HP DeskJet 2600 series | 1         | 33.33%  |
| Canon MF4320-4350      | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson ES-H300 [GT-2500] | 1         | 50%     |
| Canon CanoScan LiDE 100       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Apple                                  | 31        | 19.25%  |
| Chicony Electronics                    | 27        | 16.77%  |
| Quanta                                 | 15        | 9.32%   |
| IMC Networks                           | 14        | 8.7%    |
| Microdia                               | 11        | 6.83%   |
| Realtek Semiconductor                  | 10        | 6.21%   |
| Bison Electronics                      | 9         | 5.59%   |
| Sunplus Innovation Technology          | 7         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.35%   |
| Samsung Electronics                    | 3         | 1.86%   |
| Luxvisions Innotech Limited            | 3         | 1.86%   |
| Syntek                                 | 2         | 1.24%   |
| SunplusIT                              | 2         | 1.24%   |
| Sonix Technology                       | 2         | 1.24%   |
| Lite-On Technology                     | 2         | 1.24%   |
| Lenovo                                 | 2         | 1.24%   |
| Generalplus Technology                 | 2         | 1.24%   |
| Alcor Micro                            | 2         | 1.24%   |
| Y Media                                | 1         | 0.62%   |
| Suyin                                  | 1         | 0.62%   |
| Sunplus Technology                     | 1         | 0.62%   |
| Silicon Motion                         | 1         | 0.62%   |
| Shine-optics                           | 1         | 0.62%   |
| Logitech                               | 1         | 0.62%   |
| Intel                                  | 1         | 0.62%   |
| Cubeternet                             | 1         | 0.62%   |
| Cisco Systems                          | 1         | 0.62%   |
| Acer                                   | 1         | 0.62%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Apple Built-in iSight                            | 12        | 7.36%   |
| Chicony Integrated Camera                        | 8         | 4.91%   |
| Apple FaceTime HD Camera                         | 7         | 4.29%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 6         | 3.68%   |
| Microdia Integrated_Webcam_HD                    | 5         | 3.07%   |
| Apple FaceTime HD Camera (Built-in)              | 5         | 3.07%   |
| IMC Networks USB2.0 HD UVC WebCam                | 4         | 2.45%   |
| IMC Networks Integrated Camera                   | 4         | 2.45%   |
| Samsung Galaxy series, misc. (MTP mode)          | 3         | 1.84%   |
| Realtek Integrated_Webcam_HD                     | 3         | 1.84%   |
| Bison Lenovo Integrated Webcam                   | 3         | 1.84%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 1.23%   |
| Sunplus Dell E5570 integrated webcam             | 2         | 1.23%   |
| Quanta USB2.0 HD UVC WebCam                      | 2         | 1.23%   |
| Quanta HP Wide Vision HD Camera                  | 2         | 1.23%   |
| Quanta HP TrueVision HD Camera                   | 2         | 1.23%   |
| Quanta HP HD Camera                              | 2         | 1.23%   |
| Quanta HD Webcam                                 | 2         | 1.23%   |
| Quanta HD Camera                                 | 2         | 1.23%   |
| Microdia Webcam Vitade AF                        | 2         | 1.23%   |
| Microdia Integrated Webcam                       | 2         | 1.23%   |
| Lite-On Integrated Camera                        | 2         | 1.23%   |
| IMC Networks HD Camera                           | 2         | 1.23%   |
| Chicony Integrated HD WebCam                     | 2         | 1.23%   |
| Chicony HP Webcam                                | 2         | 1.23%   |
| Chicony HP TrueVision HD Camera                  | 2         | 1.23%   |
| Chicony HP Truevision HD                         | 2         | 1.23%   |
| Chicony HD WebCam                                | 2         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.23%   |
| Bison Integrated Camera                          | 2         | 1.23%   |
| Apple FaceTime Camera                            | 2         | 1.23%   |
| Y Media USB Camera                               | 1         | 0.61%   |
| Syntek Lenovo EasyCamera                         | 1         | 0.61%   |
| Syntek EasyCamera                                | 1         | 0.61%   |
| Suyin Acer HD Crystal Eye webcam                 | 1         | 0.61%   |
| SunplusIT USB camera                             | 1         | 0.61%   |
| SunplusIT HD Camera                              | 1         | 0.61%   |
| Sunplus 1.3M HD WebCam                           | 1         | 0.61%   |
| Sunplus HD WebCam                                | 1         | 0.61%   |
| Sunplus FHD Camera Microphone                    | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 35.48%  |
| Shenzhen Goodix Technology | 8         | 25.81%  |
| Synaptics                  | 4         | 12.9%   |
| Elan Microelectronics      | 4         | 12.9%   |
| LighTuning Technology      | 2         | 6.45%   |
| Upek                       | 1         | 3.23%   |
| AuthenTec                  | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 19.35%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 9.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 6.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 6.45%   |
| Elan ELAN:ARM-M4                                                           | 2         | 6.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.23%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 3.23%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.23%   |
| LighTuning Fingerprint Reader                                              | 1         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.23%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 3.23%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.23%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 40%     |
| Upek        | 2         | 20%     |
| Alcor Micro | 2         | 20%     |
| OmniKey     | 1         | 10%     |
| O2 Micro    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 153       | 65.11%  |
| 1     | 64        | 27.23%  |
| 2     | 17        | 7.23%   |
| 3     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 30%     |
| Net/wireless             | 22        | 22%     |
| Multimedia controller    | 19        | 19%     |
| Graphics card            | 12        | 12%     |
| Chipcard                 | 10        | 10%     |
| Net/ethernet             | 2         | 2%      |
| Storage                  | 1         | 1%      |
| Network                  | 1         | 1%      |
| Communication controller | 1         | 1%      |
| Card reader              | 1         | 1%      |
| Bluetooth                | 1         | 1%      |


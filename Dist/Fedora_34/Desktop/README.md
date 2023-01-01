Fedora 34 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 34.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 761

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | A88X-PRO                    | [b88a699d58](https://linux-hardware.org/?probe=b88a699d58) | Sep 19, 2022 |
| ASUSTek       | P8H77-V LE                  | [7f6138d8ce](https://linux-hardware.org/?probe=7f6138d8ce) | Aug 17, 2022 |
| Foxconn       | 2ABF                        | [cc835ea750](https://linux-hardware.org/?probe=cc835ea750) | Aug 13, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a6fb0fd95c](https://linux-hardware.org/?probe=a6fb0fd95c) | Jul 03, 2022 |
| MSI           | Z97 GAMING 5                | [6a1978f197](https://linux-hardware.org/?probe=6a1978f197) | Jul 02, 2022 |
| Dell          | 0VRWRC A00                  | [373df03a96](https://linux-hardware.org/?probe=373df03a96) | Jun 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [17e9f5a71f](https://linux-hardware.org/?probe=17e9f5a71f) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e474768a25](https://linux-hardware.org/?probe=e474768a25) | May 30, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [b810bd52cc](https://linux-hardware.org/?probe=b810bd52cc) | May 28, 2022 |
| ASUSTek       | H170M-E D3                  | [279a2c9102](https://linux-hardware.org/?probe=279a2c9102) | May 22, 2022 |
| MSI           | Creator TRX40               | [9ba6032977](https://linux-hardware.org/?probe=9ba6032977) | May 14, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [6693954f79](https://linux-hardware.org/?probe=6693954f79) | May 07, 2022 |
| ASRock        | AD2700-ITX                  | [c44c5e8931](https://linux-hardware.org/?probe=c44c5e8931) | May 06, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [46adc67882](https://linux-hardware.org/?probe=46adc67882) | May 05, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [30f8dbd98c](https://linux-hardware.org/?probe=30f8dbd98c) | Apr 22, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [179d1e1a0f](https://linux-hardware.org/?probe=179d1e1a0f) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d2ba372696](https://linux-hardware.org/?probe=d2ba372696) | Apr 21, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [753f5d4e22](https://linux-hardware.org/?probe=753f5d4e22) | Apr 21, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [1c54ba7a0c](https://linux-hardware.org/?probe=1c54ba7a0c) | Apr 21, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [7c4882a4ef](https://linux-hardware.org/?probe=7c4882a4ef) | Apr 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [69b4016133](https://linux-hardware.org/?probe=69b4016133) | Apr 15, 2022 |
| Gigabyte      | Z590 VISION D               | [4bde7cc5cd](https://linux-hardware.org/?probe=4bde7cc5cd) | Apr 13, 2022 |
| Intel         | D945GCL AAD82064-200        | [c6d6c5a3df](https://linux-hardware.org/?probe=c6d6c5a3df) | Apr 13, 2022 |
| Dell          | 0RY007                      | [f4384d4c1e](https://linux-hardware.org/?probe=f4384d4c1e) | Apr 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [71d793e054](https://linux-hardware.org/?probe=71d793e054) | Apr 13, 2022 |
| Lenovo        | MAHOBAY                     | [ad714d63bc](https://linux-hardware.org/?probe=ad714d63bc) | Apr 05, 2022 |
| ASUSTek       | P7P55D-E PRO                | [3e01b6fb25](https://linux-hardware.org/?probe=3e01b6fb25) | Apr 03, 2022 |
| Colorful T... | C.H110M-K D3 PLUS V20       | [191dfebc88](https://linux-hardware.org/?probe=191dfebc88) | Mar 23, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [44ff6c5827](https://linux-hardware.org/?probe=44ff6c5827) | Mar 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | [30bcf38da7](https://linux-hardware.org/?probe=30bcf38da7) | Mar 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d09e650768](https://linux-hardware.org/?probe=d09e650768) | Feb 28, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [9670ab829e](https://linux-hardware.org/?probe=9670ab829e) | Feb 26, 2022 |
| ASUSTek       | M4N68T-M-LE-V2              | [e639fc94c0](https://linux-hardware.org/?probe=e639fc94c0) | Feb 23, 2022 |
| Lenovo        | ThinkCentre M58p 6234A1G    | [1cbf260df6](https://linux-hardware.org/?probe=1cbf260df6) | Feb 18, 2022 |
| Dell          | 0X501H A02                  | [3c59b77cb3](https://linux-hardware.org/?probe=3c59b77cb3) | Feb 15, 2022 |
| Dell          | 04Y8V0 A02                  | [96679aaa7e](https://linux-hardware.org/?probe=96679aaa7e) | Feb 09, 2022 |
| Supermicro    | X9DAi                       | [ea3cbb18b7](https://linux-hardware.org/?probe=ea3cbb18b7) | Feb 08, 2022 |
| Supermicro    | X9DAi                       | [f4ce79a016](https://linux-hardware.org/?probe=f4ce79a016) | Feb 08, 2022 |
| Gigabyte      | D525TUD                     | [b3622bb011](https://linux-hardware.org/?probe=b3622bb011) | Jan 21, 2022 |
| Gigabyte      | H77N-WIFI                   | [c4760a5fc7](https://linux-hardware.org/?probe=c4760a5fc7) | Jan 21, 2022 |
| Gigabyte      | Z370P D3-CF                 | [5dc59f682d](https://linux-hardware.org/?probe=5dc59f682d) | Jan 20, 2022 |
| ASRock        | AD2700-ITX                  | [5c082420d7](https://linux-hardware.org/?probe=5c082420d7) | Jan 11, 2022 |
| ASUSTek       | PRIME B350M-A               | [b51f64610b](https://linux-hardware.org/?probe=b51f64610b) | Jan 09, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [8875c8251a](https://linux-hardware.org/?probe=8875c8251a) | Jan 08, 2022 |
| Gigabyte      | TRX40 AORUS XTREME          | [fa9ae6e044](https://linux-hardware.org/?probe=fa9ae6e044) | Jan 08, 2022 |
| MSI           | B350 PC MATE                | [c5c108c138](https://linux-hardware.org/?probe=c5c108c138) | Jan 03, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [93f4a40b03](https://linux-hardware.org/?probe=93f4a40b03) | Jan 01, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [ea153b6c44](https://linux-hardware.org/?probe=ea153b6c44) | Dec 25, 2021 |
| ASUSTek       | P8Z68-V LX                  | [7ac56b955a](https://linux-hardware.org/?probe=7ac56b955a) | Dec 23, 2021 |
| Gigabyte      | G41MT-D3                    | [703f2f070d](https://linux-hardware.org/?probe=703f2f070d) | Dec 23, 2021 |
| Dell          | 0GC080                      | [7ab7f1da0e](https://linux-hardware.org/?probe=7ab7f1da0e) | Dec 23, 2021 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [151434ab61](https://linux-hardware.org/?probe=151434ab61) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS M                | [abc283a58a](https://linux-hardware.org/?probe=abc283a58a) | Dec 20, 2021 |
| HP            | 8056                        | [68992da248](https://linux-hardware.org/?probe=68992da248) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [8f47435f8d](https://linux-hardware.org/?probe=8f47435f8d) | Dec 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [dc5f8e3963](https://linux-hardware.org/?probe=dc5f8e3963) | Dec 17, 2021 |
| ASUSTek       | P8Z68-V LX                  | [5991c3dff6](https://linux-hardware.org/?probe=5991c3dff6) | Dec 03, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [74dcac77ec](https://linux-hardware.org/?probe=74dcac77ec) | Dec 01, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b586fa0595](https://linux-hardware.org/?probe=b586fa0595) | Nov 29, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [b84bde4b26](https://linux-hardware.org/?probe=b84bde4b26) | Nov 28, 2021 |
| ASUSTek       | B150M-A D3                  | [9f95a1d036](https://linux-hardware.org/?probe=9f95a1d036) | Nov 26, 2021 |
| Gigabyte      | 990FXA-UD3                  | [06acab97b2](https://linux-hardware.org/?probe=06acab97b2) | Nov 25, 2021 |
| ASUSTek       | Z97-PRO                     | [8cd0ce3c4a](https://linux-hardware.org/?probe=8cd0ce3c4a) | Nov 17, 2021 |
| ASUSTek       | Z97-PRO                     | [a2ae0961aa](https://linux-hardware.org/?probe=a2ae0961aa) | Nov 17, 2021 |
| ASUSTek       | B150M-A D3                  | [fe4ea79cb7](https://linux-hardware.org/?probe=fe4ea79cb7) | Nov 17, 2021 |
| Lenovo        | SHARKBAY NOK                | [2e7ed34d33](https://linux-hardware.org/?probe=2e7ed34d33) | Nov 16, 2021 |
| ASUSTek       | P6T                         | [bc74d32e1c](https://linux-hardware.org/?probe=bc74d32e1c) | Nov 14, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [43cad93f6f](https://linux-hardware.org/?probe=43cad93f6f) | Nov 13, 2021 |
| ASRock        | A520M Pro4                  | [d39fac3260](https://linux-hardware.org/?probe=d39fac3260) | Nov 12, 2021 |
| ASRock        | 970 Extreme4                | [a39bc6cd00](https://linux-hardware.org/?probe=a39bc6cd00) | Nov 11, 2021 |
| ASRock        | X570 Taichi Razer Editio... | [982fbc9995](https://linux-hardware.org/?probe=982fbc9995) | Nov 10, 2021 |
| Dell          | 0DF42J A00                  | [bea323f69b](https://linux-hardware.org/?probe=bea323f69b) | Nov 09, 2021 |
| Unknown       | NF-MCP78                    | [54e66411a9](https://linux-hardware.org/?probe=54e66411a9) | Nov 08, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [cc9d9dad12](https://linux-hardware.org/?probe=cc9d9dad12) | Nov 04, 2021 |
| ASRock        | Z87 Extreme6                | [32b0b7b787](https://linux-hardware.org/?probe=32b0b7b787) | Nov 04, 2021 |
| ASRock        | Z390 Extreme4               | [2997c8b2a9](https://linux-hardware.org/?probe=2997c8b2a9) | Nov 03, 2021 |
| Pegatron      | EVE                         | [b3e2638017](https://linux-hardware.org/?probe=b3e2638017) | Nov 03, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [bc49b41641](https://linux-hardware.org/?probe=bc49b41641) | Nov 03, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [b20a9e2eb0](https://linux-hardware.org/?probe=b20a9e2eb0) | Nov 03, 2021 |
| ASRock        | AD2700-ITX                  | [c963a16f9b](https://linux-hardware.org/?probe=c963a16f9b) | Nov 02, 2021 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [14e8c3fcb9](https://linux-hardware.org/?probe=14e8c3fcb9) | Nov 01, 2021 |
| HP            | 21D0                        | [040c7efa45](https://linux-hardware.org/?probe=040c7efa45) | Nov 01, 2021 |
| ASRock        | X399 Taichi                 | [a26b02e6b0](https://linux-hardware.org/?probe=a26b02e6b0) | Nov 01, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [f5b93984c3](https://linux-hardware.org/?probe=f5b93984c3) | Nov 01, 2021 |
| Intel         | H61                         | [6978cd209f](https://linux-hardware.org/?probe=6978cd209f) | Oct 31, 2021 |
| Gigabyte      | EP45-DS3L                   | [0233ae7054](https://linux-hardware.org/?probe=0233ae7054) | Oct 31, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [ff0bc6375e](https://linux-hardware.org/?probe=ff0bc6375e) | Oct 30, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [1739e3b05d](https://linux-hardware.org/?probe=1739e3b05d) | Oct 30, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [3e8d9f5687](https://linux-hardware.org/?probe=3e8d9f5687) | Oct 30, 2021 |
| HP            | 339A                        | [28da82ff00](https://linux-hardware.org/?probe=28da82ff00) | Oct 27, 2021 |
| MSI           | A320M GAMING PRO            | [599dfb26a8](https://linux-hardware.org/?probe=599dfb26a8) | Oct 26, 2021 |
| Unknown       | NF-MCP78                    | [50a93243d2](https://linux-hardware.org/?probe=50a93243d2) | Oct 26, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [87abf841b5](https://linux-hardware.org/?probe=87abf841b5) | Oct 26, 2021 |
| Dell          | 0GC080                      | [cb7602a2bd](https://linux-hardware.org/?probe=cb7602a2bd) | Oct 26, 2021 |
| LattePanda    | Alpha                       | [93cea579ca](https://linux-hardware.org/?probe=93cea579ca) | Oct 25, 2021 |
| LattePanda    | Alpha                       | [3f81c1a08a](https://linux-hardware.org/?probe=3f81c1a08a) | Oct 25, 2021 |
| Gigabyte      | B450 AORUS M                | [93ec7f3964](https://linux-hardware.org/?probe=93ec7f3964) | Oct 24, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [3d4bec1c75](https://linux-hardware.org/?probe=3d4bec1c75) | Oct 23, 2021 |
| ASRock        | X570 Taichi                 | [4200d04ab2](https://linux-hardware.org/?probe=4200d04ab2) | Oct 23, 2021 |
| ASRock        | B450M-HDV R4.0              | [fb31c8d088](https://linux-hardware.org/?probe=fb31c8d088) | Oct 23, 2021 |
| Gigabyte      | Z77-D3H                     | [0205ab4321](https://linux-hardware.org/?probe=0205ab4321) | Oct 21, 2021 |
| ASRock        | G41M-VS3                    | [267bee9221](https://linux-hardware.org/?probe=267bee9221) | Oct 21, 2021 |
| Gigabyte      | Z77-D3H                     | [c2d1fcd5bc](https://linux-hardware.org/?probe=c2d1fcd5bc) | Oct 21, 2021 |
| HP            | 2B36                        | [a2743184d7](https://linux-hardware.org/?probe=a2743184d7) | Oct 21, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [484ff1a750](https://linux-hardware.org/?probe=484ff1a750) | Oct 21, 2021 |
| Gigabyte      | H310M H x.x                 | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | P8Z68-V PRO GEN3            | [f11c125224](https://linux-hardware.org/?probe=f11c125224) | Oct 20, 2021 |
| Gigabyte      | H370M DS3H-CF               | [1c2a383c4f](https://linux-hardware.org/?probe=1c2a383c4f) | Oct 20, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [2c6cfc5b5a](https://linux-hardware.org/?probe=2c6cfc5b5a) | Oct 20, 2021 |
| Dell          | 03KWTV A00                  | [d4f071950b](https://linux-hardware.org/?probe=d4f071950b) | Oct 19, 2021 |
| Gigabyte      | H310M H                     | [c8106b6a92](https://linux-hardware.org/?probe=c8106b6a92) | Oct 18, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [1a170cd208](https://linux-hardware.org/?probe=1a170cd208) | Oct 18, 2021 |
| ASRock        | AB350M-HDV                  | [eff4abf74e](https://linux-hardware.org/?probe=eff4abf74e) | Oct 18, 2021 |
| ASUSTek       | TUF Z270 MARK 2             | [37523e831d](https://linux-hardware.org/?probe=37523e831d) | Oct 17, 2021 |
| ASRock        | B550M Pro4                  | [ae854c2ff2](https://linux-hardware.org/?probe=ae854c2ff2) | Oct 16, 2021 |
| Gigabyte      | B365M HD3                   | [26e0d9a3d9](https://linux-hardware.org/?probe=26e0d9a3d9) | Oct 16, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [a034c42ddd](https://linux-hardware.org/?probe=a034c42ddd) | Oct 15, 2021 |
| MSI           | B560M PRO-VDH               | [2a4135bc50](https://linux-hardware.org/?probe=2a4135bc50) | Oct 14, 2021 |
| Gigabyte      | H310M H x.x                 | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [1d5dc0eb72](https://linux-hardware.org/?probe=1d5dc0eb72) | Oct 14, 2021 |
| ASRock        | 970A-G                      | [be8559f8a6](https://linux-hardware.org/?probe=be8559f8a6) | Oct 14, 2021 |
| MSI           | A320M BAZOOKA               | [acfde1543b](https://linux-hardware.org/?probe=acfde1543b) | Oct 13, 2021 |
| ASRock        | FM2A88X Extreme6+           | [11aa15d19c](https://linux-hardware.org/?probe=11aa15d19c) | Oct 13, 2021 |
| Gigabyte      | G41MT-D3                    | [42387af777](https://linux-hardware.org/?probe=42387af777) | Oct 12, 2021 |
| ASUSTek       | M5A97 R2.0                  | [4342f43c87](https://linux-hardware.org/?probe=4342f43c87) | Oct 12, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [e3683dfc6a](https://linux-hardware.org/?probe=e3683dfc6a) | Oct 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [fe78f0e87c](https://linux-hardware.org/?probe=fe78f0e87c) | Oct 12, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [4054b4ec35](https://linux-hardware.org/?probe=4054b4ec35) | Oct 11, 2021 |
| Unknown       | Phitronics G41-M3           | [2b94f6fcca](https://linux-hardware.org/?probe=2b94f6fcca) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [d01c751c63](https://linux-hardware.org/?probe=d01c751c63) | Oct 11, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [e2dff5f003](https://linux-hardware.org/?probe=e2dff5f003) | Oct 10, 2021 |
| ASRock        | FM2A88X Extreme6+           | [185b72ac58](https://linux-hardware.org/?probe=185b72ac58) | Oct 10, 2021 |
| ASRock        | FM2A88X Extreme6+           | [55df2f0eaf](https://linux-hardware.org/?probe=55df2f0eaf) | Oct 10, 2021 |
| ASUSTek       | B85M-G                      | [f15bc46048](https://linux-hardware.org/?probe=f15bc46048) | Oct 09, 2021 |
| ASUSTek       | B85M-G                      | [230c5862d7](https://linux-hardware.org/?probe=230c5862d7) | Oct 09, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | [719e7db7f5](https://linux-hardware.org/?probe=719e7db7f5) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [a96f6b582d](https://linux-hardware.org/?probe=a96f6b582d) | Oct 09, 2021 |
| Huanan        | X99-TF V2.0                 | [21ead32720](https://linux-hardware.org/?probe=21ead32720) | Oct 08, 2021 |
| HP            | 8061                        | [404d0b4b19](https://linux-hardware.org/?probe=404d0b4b19) | Oct 08, 2021 |
| Unknown       | Unknown                     | [54642e6ee3](https://linux-hardware.org/?probe=54642e6ee3) | Oct 07, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [37b9009c4f](https://linux-hardware.org/?probe=37b9009c4f) | Oct 07, 2021 |
| Unknown       | Unknown                     | [3910c19edf](https://linux-hardware.org/?probe=3910c19edf) | Oct 07, 2021 |
| MSI           | Z270M MORTAR                | [65ae5e6153](https://linux-hardware.org/?probe=65ae5e6153) | Oct 06, 2021 |
| MSI           | MS-9A45 0A                  | [04afb3d9fe](https://linux-hardware.org/?probe=04afb3d9fe) | Oct 06, 2021 |
| Acer          | Aspire XC-886 V:2.0         | [e9ee820848](https://linux-hardware.org/?probe=e9ee820848) | Oct 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [46552d08f3](https://linux-hardware.org/?probe=46552d08f3) | Oct 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [1f29f9efba](https://linux-hardware.org/?probe=1f29f9efba) | Oct 06, 2021 |
| HP            | 21D0                        | [ba6cce80cb](https://linux-hardware.org/?probe=ba6cce80cb) | Oct 05, 2021 |
| MSI           | MS-9A45 0A                  | [658cbe1d32](https://linux-hardware.org/?probe=658cbe1d32) | Oct 05, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [46a61c0976](https://linux-hardware.org/?probe=46a61c0976) | Oct 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d720268b28](https://linux-hardware.org/?probe=d720268b28) | Oct 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [3be1453b82](https://linux-hardware.org/?probe=3be1453b82) | Oct 05, 2021 |
| MSI           | B450I GAMING PLUS AC        | [1ca6c5085e](https://linux-hardware.org/?probe=1ca6c5085e) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | [9c4f3417d4](https://linux-hardware.org/?probe=9c4f3417d4) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | [3e695d6744](https://linux-hardware.org/?probe=3e695d6744) | Oct 04, 2021 |
| ASUSTek       | PRIME B250M-PLUS            | [f9ad2204b1](https://linux-hardware.org/?probe=f9ad2204b1) | Oct 03, 2021 |
| ASUSTek       | B85M-G                      | [cbd6e4f12a](https://linux-hardware.org/?probe=cbd6e4f12a) | Oct 03, 2021 |
| Gigabyte      | G41MT-D3                    | [5add233ca1](https://linux-hardware.org/?probe=5add233ca1) | Oct 03, 2021 |
| ASRock        | H97M Pro4                   | [4a45a79a05](https://linux-hardware.org/?probe=4a45a79a05) | Oct 03, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [58205ac600](https://linux-hardware.org/?probe=58205ac600) | Oct 03, 2021 |
| MSI           | Z270M MORTAR                | [8498a78a16](https://linux-hardware.org/?probe=8498a78a16) | Oct 03, 2021 |
| ASUSTek       | A68HM-PLUS                  | [00c624b592](https://linux-hardware.org/?probe=00c624b592) | Oct 03, 2021 |
| ASUSTek       | A68HM-PLUS                  | [09b4e39973](https://linux-hardware.org/?probe=09b4e39973) | Oct 03, 2021 |
| Gigabyte      | H510M H                     | [991a31ce5a](https://linux-hardware.org/?probe=991a31ce5a) | Oct 02, 2021 |
| MSI           | X570-A PRO                  | [96868e511e](https://linux-hardware.org/?probe=96868e511e) | Oct 02, 2021 |
| ASRock        | H97M Pro4                   | [55a744f106](https://linux-hardware.org/?probe=55a744f106) | Oct 02, 2021 |
| Gigabyte      | X79-UP4                     | [349f8dbe53](https://linux-hardware.org/?probe=349f8dbe53) | Oct 01, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [f76f23b18b](https://linux-hardware.org/?probe=f76f23b18b) | Oct 01, 2021 |
| Gigabyte      | B85M-D3H                    | [c264fff200](https://linux-hardware.org/?probe=c264fff200) | Oct 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [819ee8affd](https://linux-hardware.org/?probe=819ee8affd) | Sep 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | [4328d7510a](https://linux-hardware.org/?probe=4328d7510a) | Sep 30, 2021 |
| MSI           | MEG X570 UNIFY              | [98852179e1](https://linux-hardware.org/?probe=98852179e1) | Sep 30, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [1e96ea621f](https://linux-hardware.org/?probe=1e96ea621f) | Sep 29, 2021 |
| ASUSTek       | P7H55-M LX                  | [a47ae6e7b0](https://linux-hardware.org/?probe=a47ae6e7b0) | Sep 29, 2021 |
| Gigabyte      | GA-MA69GM-S2H               | [b1f14324be](https://linux-hardware.org/?probe=b1f14324be) | Sep 29, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [40295a8f09](https://linux-hardware.org/?probe=40295a8f09) | Sep 29, 2021 |
| HP            | 1998                        | [bb31e60922](https://linux-hardware.org/?probe=bb31e60922) | Sep 28, 2021 |
| ASRock        | H170M Pro4                  | [062fe3bada](https://linux-hardware.org/?probe=062fe3bada) | Sep 28, 2021 |
| Foxconn       | 2ABF                        | [2acf5e4c6d](https://linux-hardware.org/?probe=2acf5e4c6d) | Sep 28, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [9cd559605c](https://linux-hardware.org/?probe=9cd559605c) | Sep 27, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [68f4ff7431](https://linux-hardware.org/?probe=68f4ff7431) | Sep 27, 2021 |
| HP            | 8053                        | [e74bf378e7](https://linux-hardware.org/?probe=e74bf378e7) | Sep 27, 2021 |
| ECS           | H61H2-CM                    | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| Gigabyte      | EP45-DS3L                   | [e8c44e9282](https://linux-hardware.org/?probe=e8c44e9282) | Sep 26, 2021 |
| ASUSTek       | H110M-CS/BR                 | [1c65589814](https://linux-hardware.org/?probe=1c65589814) | Sep 26, 2021 |
| Gigabyte      | H81M-S2H                    | [4199c35f38](https://linux-hardware.org/?probe=4199c35f38) | Sep 25, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [08d8affc67](https://linux-hardware.org/?probe=08d8affc67) | Sep 25, 2021 |
| MSI           | MAG B550M BAZOOKA           | [d06dd7e0ec](https://linux-hardware.org/?probe=d06dd7e0ec) | Sep 25, 2021 |
| ASUSTek       | GD30CI                      | [9782c6bff5](https://linux-hardware.org/?probe=9782c6bff5) | Sep 25, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [aa7607a2b7](https://linux-hardware.org/?probe=aa7607a2b7) | Sep 24, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [6dad1e6449](https://linux-hardware.org/?probe=6dad1e6449) | Sep 24, 2021 |
| ASUSTek       | H81M-E R2.0                 | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| HP            | 0B4Ch D                     | [f56bf148bf](https://linux-hardware.org/?probe=f56bf148bf) | Sep 24, 2021 |
| ASRock        | Z390 Pro4                   | [7ab201b716](https://linux-hardware.org/?probe=7ab201b716) | Sep 24, 2021 |
| MSI           | X570-A PRO                  | [9813ead17b](https://linux-hardware.org/?probe=9813ead17b) | Sep 23, 2021 |
| MSI           | Z370-A PRO                  | [694fab3776](https://linux-hardware.org/?probe=694fab3776) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-A               | [c4a94c7628](https://linux-hardware.org/?probe=c4a94c7628) | Sep 23, 2021 |
| ASUSTek       | P8H61-M LX                  | [7360f8d859](https://linux-hardware.org/?probe=7360f8d859) | Sep 23, 2021 |
| System76      | Thelio Mira thelio-mira-... | [f6580e7358](https://linux-hardware.org/?probe=f6580e7358) | Sep 22, 2021 |
| ASUSTek       | X99-S                       | [454c9e999e](https://linux-hardware.org/?probe=454c9e999e) | Sep 22, 2021 |
| Dell          | 05XGC8 A01                  | [ea9f525cf5](https://linux-hardware.org/?probe=ea9f525cf5) | Sep 22, 2021 |
| Dell          | 0GC080                      | [0297b84b90](https://linux-hardware.org/?probe=0297b84b90) | Sep 22, 2021 |
| Dell          | 0GC080                      | [d66102b7f1](https://linux-hardware.org/?probe=d66102b7f1) | Sep 22, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [50bccc87d3](https://linux-hardware.org/?probe=50bccc87d3) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9f131c2aec](https://linux-hardware.org/?probe=9f131c2aec) | Sep 21, 2021 |
| MSI           | E3M WORKSTATION V5          | [6924705831](https://linux-hardware.org/?probe=6924705831) | Sep 20, 2021 |
| ASUSTek       | PRIME X399-A                | [edd8b3c5b2](https://linux-hardware.org/?probe=edd8b3c5b2) | Sep 20, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [a460a3a6fb](https://linux-hardware.org/?probe=a460a3a6fb) | Sep 19, 2021 |
| HP            | 8055                        | [12a1144916](https://linux-hardware.org/?probe=12a1144916) | Sep 18, 2021 |
| HP            | 8055                        | [0404bcffca](https://linux-hardware.org/?probe=0404bcffca) | Sep 18, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ceba17a8cc](https://linux-hardware.org/?probe=ceba17a8cc) | Sep 16, 2021 |
| ASUSTek       | P8Z77-V LK                  | [203e58b1d1](https://linux-hardware.org/?probe=203e58b1d1) | Sep 16, 2021 |
| MSI           | B85-G43 GAMING              | [da6e58ed2a](https://linux-hardware.org/?probe=da6e58ed2a) | Sep 16, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [ad193a0b9c](https://linux-hardware.org/?probe=ad193a0b9c) | Sep 16, 2021 |
| ECS           | G41T-M7                     | [42e72694fc](https://linux-hardware.org/?probe=42e72694fc) | Sep 15, 2021 |
| Dell          | 0GC080                      | [e7be152af1](https://linux-hardware.org/?probe=e7be152af1) | Sep 15, 2021 |
| EVGA          | 111-SS-E172                 | [b9c8f1f9e8](https://linux-hardware.org/?probe=b9c8f1f9e8) | Sep 15, 2021 |
| ASRock        | X570M Pro4                  | [297bbaf6a4](https://linux-hardware.org/?probe=297bbaf6a4) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [e0948f8a85](https://linux-hardware.org/?probe=e0948f8a85) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [981d2b7173](https://linux-hardware.org/?probe=981d2b7173) | Sep 14, 2021 |
| ASRock        | H170M Pro4                  | [59ab06bdda](https://linux-hardware.org/?probe=59ab06bdda) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [1fa62f847b](https://linux-hardware.org/?probe=1fa62f847b) | Sep 14, 2021 |
| ASUSTek       | SABERTOOTH X79              | [79242cc1bb](https://linux-hardware.org/?probe=79242cc1bb) | Sep 13, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [66154dd009](https://linux-hardware.org/?probe=66154dd009) | Sep 13, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [0b058e8bd8](https://linux-hardware.org/?probe=0b058e8bd8) | Sep 13, 2021 |
| Acer          | Aspire X3470                | [1a3f77423d](https://linux-hardware.org/?probe=1a3f77423d) | Sep 13, 2021 |
| Acer          | Aspire X3470                | [f53f569155](https://linux-hardware.org/?probe=f53f569155) | Sep 13, 2021 |
| HP            | 1587h                       | [5447d2e6c3](https://linux-hardware.org/?probe=5447d2e6c3) | Sep 12, 2021 |
| Gigabyte      | B150M-D3H-CF                | [d13739db96](https://linux-hardware.org/?probe=d13739db96) | Sep 11, 2021 |
| Intel         | DG41RQ AAE54511-201         | [14957a27ad](https://linux-hardware.org/?probe=14957a27ad) | Sep 11, 2021 |
| Intel         | DG41RQ AAE54511-201         | [f525bfb156](https://linux-hardware.org/?probe=f525bfb156) | Sep 11, 2021 |
| Gigabyte      | B85M-D3V-A                  | [04e9d9ef11](https://linux-hardware.org/?probe=04e9d9ef11) | Sep 10, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [bbfc6ac323](https://linux-hardware.org/?probe=bbfc6ac323) | Sep 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [74d478552c](https://linux-hardware.org/?probe=74d478552c) | Sep 10, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | [afb539ff26](https://linux-hardware.org/?probe=afb539ff26) | Sep 10, 2021 |
| ASUSTek       | AM1M-A                      | [ab6a989deb](https://linux-hardware.org/?probe=ab6a989deb) | Sep 09, 2021 |
| Gigabyte      | X99-Gaming 5                | [0a8ee7324e](https://linux-hardware.org/?probe=0a8ee7324e) | Sep 09, 2021 |
| ASUSTek       | SABERTOOTH X79              | [7f60ba417d](https://linux-hardware.org/?probe=7f60ba417d) | Sep 09, 2021 |
| Acer          | WG43M                       | [35c29a05ff](https://linux-hardware.org/?probe=35c29a05ff) | Sep 09, 2021 |
| ASRock        | Z390 Taichi                 | [8052fb9273](https://linux-hardware.org/?probe=8052fb9273) | Sep 09, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [bd88876ddf](https://linux-hardware.org/?probe=bd88876ddf) | Sep 08, 2021 |
| Intel         | DG33BU AAD79951-407         | [69bbaa38d9](https://linux-hardware.org/?probe=69bbaa38d9) | Sep 08, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [b6b99a61a3](https://linux-hardware.org/?probe=b6b99a61a3) | Sep 07, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [e6b54f6ad3](https://linux-hardware.org/?probe=e6b54f6ad3) | Sep 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | [feff42e39c](https://linux-hardware.org/?probe=feff42e39c) | Sep 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | [dcd49ffb0e](https://linux-hardware.org/?probe=dcd49ffb0e) | Sep 06, 2021 |
| ASUSTek       | PRIME X470-PRO              | [8275c1d1e8](https://linux-hardware.org/?probe=8275c1d1e8) | Sep 06, 2021 |
| ASRock        | H170M Pro4                  | [a1ef6a3a8b](https://linux-hardware.org/?probe=a1ef6a3a8b) | Sep 06, 2021 |
| HP            | 2AF7                        | [ea75e63661](https://linux-hardware.org/?probe=ea75e63661) | Sep 06, 2021 |
| ASUSTek       | G11CD-K                     | [c4364afff6](https://linux-hardware.org/?probe=c4364afff6) | Sep 05, 2021 |
| Gigabyte      | Z370N WIFI-CF               | [cc4ad372df](https://linux-hardware.org/?probe=cc4ad372df) | Sep 05, 2021 |
| HP            | 2B5E                        | [51682d8e81](https://linux-hardware.org/?probe=51682d8e81) | Sep 03, 2021 |
| HP            | 2B5E                        | [9fd111c3eb](https://linux-hardware.org/?probe=9fd111c3eb) | Sep 03, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [c55d1ba8bf](https://linux-hardware.org/?probe=c55d1ba8bf) | Sep 03, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [43894b89a7](https://linux-hardware.org/?probe=43894b89a7) | Sep 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [167e800e3a](https://linux-hardware.org/?probe=167e800e3a) | Sep 02, 2021 |
| ASRock        | P55M Pro                    | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [724ad5d6a2](https://linux-hardware.org/?probe=724ad5d6a2) | Sep 02, 2021 |
| ASRock        | X300M-STX                   | [79afad37d2](https://linux-hardware.org/?probe=79afad37d2) | Sep 01, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [d2f0fba8f9](https://linux-hardware.org/?probe=d2f0fba8f9) | Sep 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [7bb30a79c1](https://linux-hardware.org/?probe=7bb30a79c1) | Sep 01, 2021 |
| Gigabyte      | B550M DS3H                  | [20389db1bd](https://linux-hardware.org/?probe=20389db1bd) | Aug 31, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [3ccd4032a1](https://linux-hardware.org/?probe=3ccd4032a1) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [e014d83782](https://linux-hardware.org/?probe=e014d83782) | Aug 31, 2021 |
| ASUSTek       | P5Q-E                       | [997ce785b2](https://linux-hardware.org/?probe=997ce785b2) | Aug 31, 2021 |
| Gigabyte      | B150M-D3H-CF                | [6f0e81a6d9](https://linux-hardware.org/?probe=6f0e81a6d9) | Aug 31, 2021 |
| Gigabyte      | F2A68HM-S1                  | [dcc0bda879](https://linux-hardware.org/?probe=dcc0bda879) | Aug 30, 2021 |
| Gigabyte      | 970A-DS3P                   | [9a3be042e0](https://linux-hardware.org/?probe=9a3be042e0) | Aug 30, 2021 |
| HP            | 198E                        | [82d1a8a5a7](https://linux-hardware.org/?probe=82d1a8a5a7) | Aug 29, 2021 |
| Gigabyte      | 970A-DS3P                   | [e539faacf5](https://linux-hardware.org/?probe=e539faacf5) | Aug 29, 2021 |
| MSI           | MEG X570 UNIFY              | [cf5f33a843](https://linux-hardware.org/?probe=cf5f33a843) | Aug 28, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [5fd92a80fa](https://linux-hardware.org/?probe=5fd92a80fa) | Aug 28, 2021 |
| Lenovo        | ThinkStation D20 415579G    | [ec9c58b54e](https://linux-hardware.org/?probe=ec9c58b54e) | Aug 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4331eedde2](https://linux-hardware.org/?probe=4331eedde2) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [614ac09d36](https://linux-hardware.org/?probe=614ac09d36) | Aug 28, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [3c31559d95](https://linux-hardware.org/?probe=3c31559d95) | Aug 28, 2021 |
| MSI           | X570-A PRO                  | [830bfb129f](https://linux-hardware.org/?probe=830bfb129f) | Aug 27, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| MSI           | X570-A PRO                  | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| MSI           | A320M-A PRO M2              | [fda90307d4](https://linux-hardware.org/?probe=fda90307d4) | Aug 27, 2021 |
| ASUSTek       | P6T                         | [ad049817af](https://linux-hardware.org/?probe=ad049817af) | Aug 27, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [a0ed3c6558](https://linux-hardware.org/?probe=a0ed3c6558) | Aug 27, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [63104dc43a](https://linux-hardware.org/?probe=63104dc43a) | Aug 26, 2021 |
| ASUSTek       | PRIME Z390-A                | [6e2699cc9e](https://linux-hardware.org/?probe=6e2699cc9e) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [3e39cc51a8](https://linux-hardware.org/?probe=3e39cc51a8) | Aug 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [74a9538d04](https://linux-hardware.org/?probe=74a9538d04) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [11d9254c35](https://linux-hardware.org/?probe=11d9254c35) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [778e5aa3ae](https://linux-hardware.org/?probe=778e5aa3ae) | Aug 25, 2021 |
| ASRock        | FM2A55M-VG3+                | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| Dell          | 0HH807                      | [fe3659d065](https://linux-hardware.org/?probe=fe3659d065) | Aug 24, 2021 |
| ASRock        | 980DE3/U3S3                 | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| Biostar       | A68I-450 DELUXE             | [3e0a375af7](https://linux-hardware.org/?probe=3e0a375af7) | Aug 23, 2021 |
| ASUSTek       | PRIME A320M-K               | [847e7f4c1a](https://linux-hardware.org/?probe=847e7f4c1a) | Aug 23, 2021 |
| MSI           | E3M WORKSTATION V5          | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [014af10464](https://linux-hardware.org/?probe=014af10464) | Aug 23, 2021 |
| Dell          | 0F3KHR A01                  | [b5bc473971](https://linux-hardware.org/?probe=b5bc473971) | Aug 23, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [07d9074437](https://linux-hardware.org/?probe=07d9074437) | Aug 23, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| ASRock        | H170M Pro4                  | [0cd9bde7b4](https://linux-hardware.org/?probe=0cd9bde7b4) | Aug 23, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f983e2baca](https://linux-hardware.org/?probe=f983e2baca) | Aug 22, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [b2190e55e8](https://linux-hardware.org/?probe=b2190e55e8) | Aug 22, 2021 |
| ASUSTek       | Z77-A                       | [971dc3b5c7](https://linux-hardware.org/?probe=971dc3b5c7) | Aug 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [edc2f605d1](https://linux-hardware.org/?probe=edc2f605d1) | Aug 21, 2021 |
| MSI           | X370 SLI PLUS               | [4a611b712a](https://linux-hardware.org/?probe=4a611b712a) | Aug 21, 2021 |
| ASUSTek       | AM1M-A                      | [433d420dd4](https://linux-hardware.org/?probe=433d420dd4) | Aug 20, 2021 |
| ASUSTek       | P6T                         | [d0495a4765](https://linux-hardware.org/?probe=d0495a4765) | Aug 20, 2021 |
| ASRock        | B450 Steel Legend           | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| Gigabyte      | G41MT-D3                    | [e49dbd40b5](https://linux-hardware.org/?probe=e49dbd40b5) | Aug 20, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [41874518ea](https://linux-hardware.org/?probe=41874518ea) | Aug 20, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [78feb5ae08](https://linux-hardware.org/?probe=78feb5ae08) | Aug 20, 2021 |
| BESSTAR Te... | HM80                        | [60fdee03d6](https://linux-hardware.org/?probe=60fdee03d6) | Aug 19, 2021 |
| HP            | 83E9                        | [21b492b0bf](https://linux-hardware.org/?probe=21b492b0bf) | Aug 19, 2021 |
| HP            | 83E9                        | [7cb2c3256a](https://linux-hardware.org/?probe=7cb2c3256a) | Aug 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3eb5c512ad](https://linux-hardware.org/?probe=3eb5c512ad) | Aug 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [84153c2a8d](https://linux-hardware.org/?probe=84153c2a8d) | Aug 19, 2021 |
| Gigabyte      | B150M-D3H-CF                | [2aed19ac0a](https://linux-hardware.org/?probe=2aed19ac0a) | Aug 19, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [5c3e90c735](https://linux-hardware.org/?probe=5c3e90c735) | Aug 19, 2021 |
| Gigabyte      | P55-USB3                    | [5e6a1d1926](https://linux-hardware.org/?probe=5e6a1d1926) | Aug 19, 2021 |
| ASUSTek       | AM1M-A                      | [c0653de55c](https://linux-hardware.org/?probe=c0653de55c) | Aug 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6eaf105bca](https://linux-hardware.org/?probe=6eaf105bca) | Aug 18, 2021 |
| ASRock        | X399 Taichi                 | [efead486a3](https://linux-hardware.org/?probe=efead486a3) | Aug 18, 2021 |
| HP            | 82F2 A01                    | [b6847d9605](https://linux-hardware.org/?probe=b6847d9605) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| ASRock        | B460M-ITX/ac                | [2eb3e6f3f6](https://linux-hardware.org/?probe=2eb3e6f3f6) | Aug 17, 2021 |
| Gigabyte      | G41MT-S2P                   | [63a8a28fd9](https://linux-hardware.org/?probe=63a8a28fd9) | Aug 17, 2021 |
| Dell          | 0Y2YM6 A00                  | [4d3d87b641](https://linux-hardware.org/?probe=4d3d87b641) | Aug 17, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [78a3158393](https://linux-hardware.org/?probe=78a3158393) | Aug 16, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [419995b0da](https://linux-hardware.org/?probe=419995b0da) | Aug 15, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f931b86af5](https://linux-hardware.org/?probe=f931b86af5) | Aug 15, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [cd8825c8d0](https://linux-hardware.org/?probe=cd8825c8d0) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [5f49d58f42](https://linux-hardware.org/?probe=5f49d58f42) | Aug 14, 2021 |
| Dell          | 0NKW6Y A00                  | [7d0c7834be](https://linux-hardware.org/?probe=7d0c7834be) | Aug 14, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [32bc94c4e2](https://linux-hardware.org/?probe=32bc94c4e2) | Aug 13, 2021 |
| Intel         | B75                         | [2bac7a8140](https://linux-hardware.org/?probe=2bac7a8140) | Aug 13, 2021 |
| Gigabyte      | Z390 D                      | [8bfd432fba](https://linux-hardware.org/?probe=8bfd432fba) | Aug 13, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5e9853124d](https://linux-hardware.org/?probe=5e9853124d) | Aug 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [0b46a87be6](https://linux-hardware.org/?probe=0b46a87be6) | Aug 13, 2021 |
| Dell          | 03NVJ6 A01                  | [ef0028e285](https://linux-hardware.org/?probe=ef0028e285) | Aug 12, 2021 |
| MSI           | X570-A PRO                  | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3ed6340d82](https://linux-hardware.org/?probe=3ed6340d82) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | [5f70360eea](https://linux-hardware.org/?probe=5f70360eea) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | [aeec0ec477](https://linux-hardware.org/?probe=aeec0ec477) | Aug 12, 2021 |
| Acer          | Aspire TC-705               | [bbf5c161d3](https://linux-hardware.org/?probe=bbf5c161d3) | Aug 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [3fd838012c](https://linux-hardware.org/?probe=3fd838012c) | Aug 12, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6808748401](https://linux-hardware.org/?probe=6808748401) | Aug 10, 2021 |
| Dell          | 0KWVT8 A02                  | [d8e685c049](https://linux-hardware.org/?probe=d8e685c049) | Aug 10, 2021 |
| MSI           | B75MA-E33                   | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [8ad0df4157](https://linux-hardware.org/?probe=8ad0df4157) | Aug 09, 2021 |
| Biostar       | X370GTN                     | [eeff407867](https://linux-hardware.org/?probe=eeff407867) | Aug 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [ec3a3d05e5](https://linux-hardware.org/?probe=ec3a3d05e5) | Aug 08, 2021 |
| Gigabyte      | G41MT-D3                    | [feacdb6873](https://linux-hardware.org/?probe=feacdb6873) | Aug 08, 2021 |
| HP            | 1998                        | [38acf34efb](https://linux-hardware.org/?probe=38acf34efb) | Aug 08, 2021 |
| MSI           | MAG B560 TORPEDO            | [8e1e7782d9](https://linux-hardware.org/?probe=8e1e7782d9) | Aug 08, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | [f51ff5d22f](https://linux-hardware.org/?probe=f51ff5d22f) | Aug 07, 2021 |
| MSI           | MAG B560 TORPEDO            | [4d2a5f5d27](https://linux-hardware.org/?probe=4d2a5f5d27) | Aug 07, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [4c87b2ff27](https://linux-hardware.org/?probe=4c87b2ff27) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f74df24802](https://linux-hardware.org/?probe=f74df24802) | Aug 05, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [2fbf46c559](https://linux-hardware.org/?probe=2fbf46c559) | Aug 05, 2021 |
| MSI           | B450-A PRO MAX              | [a096b9bb71](https://linux-hardware.org/?probe=a096b9bb71) | Aug 05, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [2c843a3d35](https://linux-hardware.org/?probe=2c843a3d35) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | [b3ae79f78f](https://linux-hardware.org/?probe=b3ae79f78f) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | [a124194272](https://linux-hardware.org/?probe=a124194272) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | [dce96ae07e](https://linux-hardware.org/?probe=dce96ae07e) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | [345ce8fb64](https://linux-hardware.org/?probe=345ce8fb64) | Aug 04, 2021 |
| HP            | 82F2 A01                    | [b6b124c434](https://linux-hardware.org/?probe=b6b124c434) | Aug 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [f776a4eb93](https://linux-hardware.org/?probe=f776a4eb93) | Aug 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [39919aab55](https://linux-hardware.org/?probe=39919aab55) | Aug 02, 2021 |
| ASRock        | B450 Pro4                   | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [454fecb7fb](https://linux-hardware.org/?probe=454fecb7fb) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [c18e0a53fc](https://linux-hardware.org/?probe=c18e0a53fc) | Aug 01, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [052a6762c4](https://linux-hardware.org/?probe=052a6762c4) | Jul 31, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [2b00e34271](https://linux-hardware.org/?probe=2b00e34271) | Jul 31, 2021 |
| Lenovo        | MAHOBAY NOK                 | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [b5a0d25d72](https://linux-hardware.org/?probe=b5a0d25d72) | Jul 30, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [e842eefc11](https://linux-hardware.org/?probe=e842eefc11) | Jul 29, 2021 |
| Gigabyte      | F2A78M-HD2                  | [ae31c59ee8](https://linux-hardware.org/?probe=ae31c59ee8) | Jul 29, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [20e3d5c8af](https://linux-hardware.org/?probe=20e3d5c8af) | Jul 29, 2021 |
| ASUSTek       | PRIME Z390-A                | [c6239b2672](https://linux-hardware.org/?probe=c6239b2672) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [88d668c3ab](https://linux-hardware.org/?probe=88d668c3ab) | Jul 27, 2021 |
| ASUSTek       | M5A97 R2.0                  | [fe0953d7db](https://linux-hardware.org/?probe=fe0953d7db) | Jul 27, 2021 |
| ASRock        | X399 Professional Gaming    | [5e769c8137](https://linux-hardware.org/?probe=5e769c8137) | Jul 26, 2021 |
| Gigabyte      | H61N-USB3                   | [25961dfa1f](https://linux-hardware.org/?probe=25961dfa1f) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Gigabyte      | H97M-DS3P                   | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| HP            | 2AF7                        | [a24b46f292](https://linux-hardware.org/?probe=a24b46f292) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [f2c2beb7da](https://linux-hardware.org/?probe=f2c2beb7da) | Jul 24, 2021 |
| Lenovo        | MAHOBAY NOK                 | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Acer          | WG43M                       | [9efd66b779](https://linux-hardware.org/?probe=9efd66b779) | Jul 22, 2021 |
| Dell          | 0W0CHX A01                  | [d4f3e21abc](https://linux-hardware.org/?probe=d4f3e21abc) | Jul 22, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [0b87f80aa9](https://linux-hardware.org/?probe=0b87f80aa9) | Jul 22, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [831024faec](https://linux-hardware.org/?probe=831024faec) | Jul 22, 2021 |
| Intel         | H81                         | [166b35fa7f](https://linux-hardware.org/?probe=166b35fa7f) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Gigabyte      | G41M-Combo                  | [785c30284d](https://linux-hardware.org/?probe=785c30284d) | Jul 21, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [4dd5b903b6](https://linux-hardware.org/?probe=4dd5b903b6) | Jul 21, 2021 |
| HP            | 83E1                        | [977631dbb5](https://linux-hardware.org/?probe=977631dbb5) | Jul 20, 2021 |
| ASUSTek       | B85M-G                      | [bddfad8365](https://linux-hardware.org/?probe=bddfad8365) | Jul 20, 2021 |
| ASUSTek       | B85M-G                      | [2dcaee58ab](https://linux-hardware.org/?probe=2dcaee58ab) | Jul 20, 2021 |
| Gigabyte      | B450 AORUS M                | [ebed27d481](https://linux-hardware.org/?probe=ebed27d481) | Jul 20, 2021 |
| ASUSTek       | P8B75-M                     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| ASUSTek       | P5LD2                       | [9e97498649](https://linux-hardware.org/?probe=9e97498649) | Jul 19, 2021 |
| MSI           | Z390-A PRO                  | [811ff5b5d4](https://linux-hardware.org/?probe=811ff5b5d4) | Jul 19, 2021 |
| Gigabyte      | G41M-Combo                  | [5f182f7f80](https://linux-hardware.org/?probe=5f182f7f80) | Jul 18, 2021 |
| HP            | 3646h                       | [b4dd06e5ce](https://linux-hardware.org/?probe=b4dd06e5ce) | Jul 18, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [d51165f3df](https://linux-hardware.org/?probe=d51165f3df) | Jul 17, 2021 |
| Gigabyte      | M61PME-S2P                  | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [6f6f7c6f5b](https://linux-hardware.org/?probe=6f6f7c6f5b) | Jul 16, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [02c451c80b](https://linux-hardware.org/?probe=02c451c80b) | Jul 16, 2021 |
| Biostar       | X370GTN                     | [22114c765e](https://linux-hardware.org/?probe=22114c765e) | Jul 16, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | [38067d7d6d](https://linux-hardware.org/?probe=38067d7d6d) | Jul 15, 2021 |
| ASRock        | 990FX Extreme3              | [0621ec449f](https://linux-hardware.org/?probe=0621ec449f) | Jul 15, 2021 |
| ASRock        | A320M-HDV R4.0              | [663c98e1f6](https://linux-hardware.org/?probe=663c98e1f6) | Jul 13, 2021 |
| HP            | 872B                        | [319ce0e306](https://linux-hardware.org/?probe=319ce0e306) | Jul 13, 2021 |
| ASRock        | A320M-HD                    | [d3700506ef](https://linux-hardware.org/?probe=d3700506ef) | Jul 13, 2021 |
| SYWZ          | S200 Series                 | [842ae5d4a3](https://linux-hardware.org/?probe=842ae5d4a3) | Jul 12, 2021 |
| Dell          | 0C2KJT A00                  | [891d514a94](https://linux-hardware.org/?probe=891d514a94) | Jul 12, 2021 |
| EVGA          | 111-KS-E272                 | [a97173038d](https://linux-hardware.org/?probe=a97173038d) | Jul 12, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [16799202de](https://linux-hardware.org/?probe=16799202de) | Jul 11, 2021 |
| Dell          | 0DF42J A00                  | [8a76db0ada](https://linux-hardware.org/?probe=8a76db0ada) | Jul 11, 2021 |
| ASUSTek       | EX-B250-V7                  | [32e09fdf66](https://linux-hardware.org/?probe=32e09fdf66) | Jul 11, 2021 |
| Gigabyte      | Z270-Gaming K3              | [731361283a](https://linux-hardware.org/?probe=731361283a) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [89ed1de959](https://linux-hardware.org/?probe=89ed1de959) | Jul 10, 2021 |
| Dell          | 0VRWRC A00                  | [3ec458e478](https://linux-hardware.org/?probe=3ec458e478) | Jul 10, 2021 |
| Gigabyte      | P31-ES3G                    | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f008db5308](https://linux-hardware.org/?probe=f008db5308) | Jul 10, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [e1049532a5](https://linux-hardware.org/?probe=e1049532a5) | Jul 09, 2021 |
| MSI           | MS-B1711                    | [ad46286aa7](https://linux-hardware.org/?probe=ad46286aa7) | Jul 09, 2021 |
| HP            | 1497                        | [eecafd7c6c](https://linux-hardware.org/?probe=eecafd7c6c) | Jul 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [07e45f519d](https://linux-hardware.org/?probe=07e45f519d) | Jul 09, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [413c28caa0](https://linux-hardware.org/?probe=413c28caa0) | Jul 08, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [785027f8f6](https://linux-hardware.org/?probe=785027f8f6) | Jul 08, 2021 |
| ASRock        | X399 Phantom Gaming 6       | [d93e096489](https://linux-hardware.org/?probe=d93e096489) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | [9314761de4](https://linux-hardware.org/?probe=9314761de4) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | [c658575abc](https://linux-hardware.org/?probe=c658575abc) | Jul 08, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f0474e6193](https://linux-hardware.org/?probe=f0474e6193) | Jul 08, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [25fdba4c4f](https://linux-hardware.org/?probe=25fdba4c4f) | Jul 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [47e2b55bb5](https://linux-hardware.org/?probe=47e2b55bb5) | Jul 07, 2021 |
| ASUSTek       | X99-A II                    | [d84c3b80a1](https://linux-hardware.org/?probe=d84c3b80a1) | Jul 07, 2021 |
| Gigabyte      | H61N-USB3                   | [4533c4325a](https://linux-hardware.org/?probe=4533c4325a) | Jul 07, 2021 |
| Dell          | 0PC5F7 A02                  | [ea43204b3b](https://linux-hardware.org/?probe=ea43204b3b) | Jul 06, 2021 |
| ASUSTek       | Z170-A                      | [04b8667d2e](https://linux-hardware.org/?probe=04b8667d2e) | Jul 06, 2021 |
| ASRock        | AD2700-ITX                  | [9b868b0c9b](https://linux-hardware.org/?probe=9b868b0c9b) | Jul 06, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [5758df25ec](https://linux-hardware.org/?probe=5758df25ec) | Jul 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [a44525ea2d](https://linux-hardware.org/?probe=a44525ea2d) | Jul 05, 2021 |
| ASUSTek       | Z87-DELUXE                  | [3aa1e79866](https://linux-hardware.org/?probe=3aa1e79866) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | [6fdc284c1a](https://linux-hardware.org/?probe=6fdc284c1a) | Jul 05, 2021 |
| MSI           | B450M BAZOOKA V2            | [efe8014efa](https://linux-hardware.org/?probe=efe8014efa) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | [13f5ecaf06](https://linux-hardware.org/?probe=13f5ecaf06) | Jul 04, 2021 |
| Alienware     | 0N4R4N A00                  | [9219336156](https://linux-hardware.org/?probe=9219336156) | Jul 04, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [de1eb87e32](https://linux-hardware.org/?probe=de1eb87e32) | Jul 04, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| MSI           | MS-B9321                    | [93243d00da](https://linux-hardware.org/?probe=93243d00da) | Jul 03, 2021 |
| Google        | Panther                     | [043feff8fe](https://linux-hardware.org/?probe=043feff8fe) | Jul 03, 2021 |
| ASRock        | J3160DC-ITX                 | [cfd320c331](https://linux-hardware.org/?probe=cfd320c331) | Jul 03, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0e5e9b16b8](https://linux-hardware.org/?probe=0e5e9b16b8) | Jul 03, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [f61ba12c20](https://linux-hardware.org/?probe=f61ba12c20) | Jul 03, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [36c64a337b](https://linux-hardware.org/?probe=36c64a337b) | Jul 03, 2021 |
| MSI           | H110M PRO-VD                | [55cdedffc2](https://linux-hardware.org/?probe=55cdedffc2) | Jul 03, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f3ef9d51b3](https://linux-hardware.org/?probe=f3ef9d51b3) | Jul 02, 2021 |
| MSI           | MS-B1711                    | [21ec3e7523](https://linux-hardware.org/?probe=21ec3e7523) | Jul 02, 2021 |
| AMD           | A320IPC VER:1.00            | [f165ce8a70](https://linux-hardware.org/?probe=f165ce8a70) | Jul 01, 2021 |
| HP            | 8056                        | [d10cd539f1](https://linux-hardware.org/?probe=d10cd539f1) | Jul 01, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [48bef18c1a](https://linux-hardware.org/?probe=48bef18c1a) | Jul 01, 2021 |
| Gigabyte      | G41MT-D3                    | [ed64b27c12](https://linux-hardware.org/?probe=ed64b27c12) | Jul 01, 2021 |
| Gigabyte      | H61N-USB3                   | [d6bf3eece4](https://linux-hardware.org/?probe=d6bf3eece4) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [a37dd487ac](https://linux-hardware.org/?probe=a37dd487ac) | Jun 30, 2021 |
| Dell          | 08NPPY A00                  | [28dd0487c3](https://linux-hardware.org/?probe=28dd0487c3) | Jun 30, 2021 |
| ASRock        | A320M-HD                    | [ce332204a6](https://linux-hardware.org/?probe=ce332204a6) | Jun 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [a8268a0c9d](https://linux-hardware.org/?probe=a8268a0c9d) | Jun 29, 2021 |
| Lenovo        | ThinkCentre M58p 6234GY2    | [1e1ba598d3](https://linux-hardware.org/?probe=1e1ba598d3) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | [1185271556](https://linux-hardware.org/?probe=1185271556) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | [0369ff2b06](https://linux-hardware.org/?probe=0369ff2b06) | Jun 29, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [353a5052a1](https://linux-hardware.org/?probe=353a5052a1) | Jun 29, 2021 |
| Dell          | 06D7TR A00                  | [52e029b58e](https://linux-hardware.org/?probe=52e029b58e) | Jun 28, 2021 |
| SYWZ          | S200 Series                 | [a848b9e433](https://linux-hardware.org/?probe=a848b9e433) | Jun 28, 2021 |
| Positivo      | POS-MI945AA                 | [fd4be0982e](https://linux-hardware.org/?probe=fd4be0982e) | Jun 27, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [a6b799f108](https://linux-hardware.org/?probe=a6b799f108) | Jun 27, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [62c1b02c31](https://linux-hardware.org/?probe=62c1b02c31) | Jun 27, 2021 |
| HP            | 8436                        | [617d5e50fd](https://linux-hardware.org/?probe=617d5e50fd) | Jun 27, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [f479cb95d4](https://linux-hardware.org/?probe=f479cb95d4) | Jun 26, 2021 |
| Dell          | 08NPPY A00                  | [3c33ace801](https://linux-hardware.org/?probe=3c33ace801) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [c1e9364997](https://linux-hardware.org/?probe=c1e9364997) | Jun 26, 2021 |
| Unknown       | NF-MCP78                    | [39a0c32be8](https://linux-hardware.org/?probe=39a0c32be8) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [68cd01f446](https://linux-hardware.org/?probe=68cd01f446) | Jun 25, 2021 |
| ASUSTek       | PRIME B460M-A               | [95a80b91fd](https://linux-hardware.org/?probe=95a80b91fd) | Jun 25, 2021 |
| Gigabyte      | B150M-D3H-CF                | [02924c7c01](https://linux-hardware.org/?probe=02924c7c01) | Jun 25, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [7f19e67108](https://linux-hardware.org/?probe=7f19e67108) | Jun 24, 2021 |
| Gigabyte      | H110M-H-CF                  | [f8a74fc57a](https://linux-hardware.org/?probe=f8a74fc57a) | Jun 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b5d17f5b99](https://linux-hardware.org/?probe=b5d17f5b99) | Jun 24, 2021 |
| ASRock        | A320M-HD                    | [121770a05e](https://linux-hardware.org/?probe=121770a05e) | Jun 23, 2021 |
| MSI           | Z97 GAMING 5                | [8edc5f4d03](https://linux-hardware.org/?probe=8edc5f4d03) | Jun 23, 2021 |
| ASRock        | B550M Steel Legend          | [e1346ace5c](https://linux-hardware.org/?probe=e1346ace5c) | Jun 23, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7a6f9e9890](https://linux-hardware.org/?probe=7a6f9e9890) | Jun 22, 2021 |
| ASRock        | H77 Pro4-M                  | [643c704c39](https://linux-hardware.org/?probe=643c704c39) | Jun 22, 2021 |
| Lenovo        | 3714 SDK0R32862 WIN 3258... | [b20ad5477a](https://linux-hardware.org/?probe=b20ad5477a) | Jun 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ca17e02509](https://linux-hardware.org/?probe=ca17e02509) | Jun 22, 2021 |
| ASRock        | H97M Pro4                   | [b57edde05d](https://linux-hardware.org/?probe=b57edde05d) | Jun 22, 2021 |
| HP            | ProLiant ML150 G5           | [dd931cb4e6](https://linux-hardware.org/?probe=dd931cb4e6) | Jun 21, 2021 |
| ASRock        | Z97 Extreme4                | [9974950d4a](https://linux-hardware.org/?probe=9974950d4a) | Jun 21, 2021 |
| MSI           | B450 TOMAHAWK               | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| Gigabyte      | H77N-WIFI                   | [0c1eb0be4f](https://linux-hardware.org/?probe=0c1eb0be4f) | Jun 21, 2021 |
| ASUSTek       | PRIME B460M-A               | [5050b7baad](https://linux-hardware.org/?probe=5050b7baad) | Jun 21, 2021 |
| ASUSTek       | PRIME A320M-E               | [edb0b62fe0](https://linux-hardware.org/?probe=edb0b62fe0) | Jun 19, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [ed109bbeda](https://linux-hardware.org/?probe=ed109bbeda) | Jun 19, 2021 |
| Dell          | 0F8101                      | [a33d01212c](https://linux-hardware.org/?probe=a33d01212c) | Jun 19, 2021 |
| ASRock        | H97 Killer                  | [acc4773b1b](https://linux-hardware.org/?probe=acc4773b1b) | Jun 18, 2021 |
| HP            | 81C5 MVB                    | [eb5550cdef](https://linux-hardware.org/?probe=eb5550cdef) | Jun 17, 2021 |
| Gigabyte      | H77N-WIFI                   | [c9cf129666](https://linux-hardware.org/?probe=c9cf129666) | Jun 17, 2021 |
| Intel         | MIR1 RVP7                   | [b0a36a3845](https://linux-hardware.org/?probe=b0a36a3845) | Jun 17, 2021 |
| ASUSTek       | P5N73-CM                    | [5320c39497](https://linux-hardware.org/?probe=5320c39497) | Jun 16, 2021 |
| ASUSTek       | P5N73-CM                    | [096e520c57](https://linux-hardware.org/?probe=096e520c57) | Jun 16, 2021 |
| ASRock        | Z170 Extreme7+              | [180e2dcad0](https://linux-hardware.org/?probe=180e2dcad0) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [caee94b554](https://linux-hardware.org/?probe=caee94b554) | Jun 16, 2021 |
| Gigabyte      | EP45-DS3L                   | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [692dcceeee](https://linux-hardware.org/?probe=692dcceeee) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3b280580e0](https://linux-hardware.org/?probe=3b280580e0) | Jun 14, 2021 |
| ASRock        | B450M-HDV R4.0              | [b5b8d7a195](https://linux-hardware.org/?probe=b5b8d7a195) | Jun 13, 2021 |
| Intel         | SHARKBAY                    | [2b38485e94](https://linux-hardware.org/?probe=2b38485e94) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| ASUSTek       | M2N-E SLI                   | [c1805791ab](https://linux-hardware.org/?probe=c1805791ab) | Jun 13, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [2dcbc551cd](https://linux-hardware.org/?probe=2dcbc551cd) | Jun 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [0a78275a12](https://linux-hardware.org/?probe=0a78275a12) | Jun 12, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [8081e6a752](https://linux-hardware.org/?probe=8081e6a752) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [92f48178fc](https://linux-hardware.org/?probe=92f48178fc) | Jun 12, 2021 |
| HP            | 3397                        | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| Gigabyte      | EP41-UD3L                   | [aa273ff14d](https://linux-hardware.org/?probe=aa273ff14d) | Jun 10, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | [405b055ebd](https://linux-hardware.org/?probe=405b055ebd) | Jun 10, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [ebca8fe85a](https://linux-hardware.org/?probe=ebca8fe85a) | Jun 09, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [0023c36bb4](https://linux-hardware.org/?probe=0023c36bb4) | Jun 09, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [85ad270405](https://linux-hardware.org/?probe=85ad270405) | Jun 09, 2021 |
| ASRock        | A300M-STX                   | [d5fbd4c05d](https://linux-hardware.org/?probe=d5fbd4c05d) | Jun 08, 2021 |
| MSI           | Z390-A PRO                  | [8d4983662d](https://linux-hardware.org/?probe=8d4983662d) | Jun 08, 2021 |
| HP            | 843C                        | [391865c5a2](https://linux-hardware.org/?probe=391865c5a2) | Jun 08, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [c493d4cdf9](https://linux-hardware.org/?probe=c493d4cdf9) | Jun 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2c66c12e1b](https://linux-hardware.org/?probe=2c66c12e1b) | Jun 07, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [13eaba8cd2](https://linux-hardware.org/?probe=13eaba8cd2) | Jun 07, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [872d0ecc32](https://linux-hardware.org/?probe=872d0ecc32) | Jun 07, 2021 |
| Gateway       | DX4860                      | [bd9a842eec](https://linux-hardware.org/?probe=bd9a842eec) | Jun 07, 2021 |
| Gateway       | DX4860                      | [a26d972766](https://linux-hardware.org/?probe=a26d972766) | Jun 07, 2021 |
| ASRock        | B560M Steel Legend          | [c87d28e8c0](https://linux-hardware.org/?probe=c87d28e8c0) | Jun 07, 2021 |
| ASRock        | H97M Pro4                   | [8ba65755ff](https://linux-hardware.org/?probe=8ba65755ff) | Jun 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7e68daad35](https://linux-hardware.org/?probe=7e68daad35) | Jun 06, 2021 |
| ASUSTek       | Z170-A                      | [ba3e1c4e32](https://linux-hardware.org/?probe=ba3e1c4e32) | Jun 05, 2021 |
| Intel         | H61                         | [607d6e5e33](https://linux-hardware.org/?probe=607d6e5e33) | Jun 05, 2021 |
| Intel         | H61                         | [8ed3e75d2d](https://linux-hardware.org/?probe=8ed3e75d2d) | Jun 05, 2021 |
| HP            | 8768 A                      | [f239501901](https://linux-hardware.org/?probe=f239501901) | Jun 05, 2021 |
| MSI           | A78M-E35                    | [4d4959df32](https://linux-hardware.org/?probe=4d4959df32) | Jun 04, 2021 |
| MSI           | A78M-E35                    | [7dc4db6092](https://linux-hardware.org/?probe=7dc4db6092) | Jun 04, 2021 |
| ASRock        | AB350 Pro4                  | [557557b4eb](https://linux-hardware.org/?probe=557557b4eb) | Jun 04, 2021 |
| HP            | 0AECh D                     | [0a0a487efe](https://linux-hardware.org/?probe=0a0a487efe) | Jun 04, 2021 |
| ASUSTek       | Z170-A                      | [221e440b21](https://linux-hardware.org/?probe=221e440b21) | Jun 03, 2021 |
| ASUSTek       | PRIME H310M-D               | [5f98fdcb02](https://linux-hardware.org/?probe=5f98fdcb02) | Jun 03, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1c0016dc30](https://linux-hardware.org/?probe=1c0016dc30) | Jun 03, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [0e54cb2214](https://linux-hardware.org/?probe=0e54cb2214) | Jun 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [290d70d292](https://linux-hardware.org/?probe=290d70d292) | Jun 03, 2021 |
| Gigabyte      | H77N-WIFI                   | [ceb72d0ae7](https://linux-hardware.org/?probe=ceb72d0ae7) | Jun 03, 2021 |
| Gigabyte      | G41MT-D3                    | [9bae888d70](https://linux-hardware.org/?probe=9bae888d70) | Jun 03, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [4c17a95dc1](https://linux-hardware.org/?probe=4c17a95dc1) | Jun 03, 2021 |
| Dell          | 0427JK A00                  | [0cde3de43d](https://linux-hardware.org/?probe=0cde3de43d) | Jun 03, 2021 |
| ASUSTek       | Maximus VII HERO            | [dbfeab0bb4](https://linux-hardware.org/?probe=dbfeab0bb4) | Jun 02, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [1a7c5aee0e](https://linux-hardware.org/?probe=1a7c5aee0e) | Jun 02, 2021 |
| ASUSTek       | M2N-E SLI                   | [203b62c458](https://linux-hardware.org/?probe=203b62c458) | Jun 02, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ad37db1da8](https://linux-hardware.org/?probe=ad37db1da8) | Jun 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [f5dafbe2de](https://linux-hardware.org/?probe=f5dafbe2de) | Jun 01, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [f7ca87e974](https://linux-hardware.org/?probe=f7ca87e974) | Jun 01, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [b8d0e81636](https://linux-hardware.org/?probe=b8d0e81636) | Jun 01, 2021 |
| Gigabyte      | 990XA-UD3                   | [77fcb9cf4a](https://linux-hardware.org/?probe=77fcb9cf4a) | Jun 01, 2021 |
| Gigabyte      | Z97-HD3                     | [e0277e3530](https://linux-hardware.org/?probe=e0277e3530) | May 31, 2021 |
| Dell          | 0R849J A00                  | [7a75936b55](https://linux-hardware.org/?probe=7a75936b55) | May 31, 2021 |
| Dell          | 0GXM1W A01                  | [4daf9fdc0d](https://linux-hardware.org/?probe=4daf9fdc0d) | May 31, 2021 |
| ASUSTek       | PRIME B460M-A               | [5125306d59](https://linux-hardware.org/?probe=5125306d59) | May 31, 2021 |
| MSI           | X570-A PRO                  | [9b20a88d5e](https://linux-hardware.org/?probe=9b20a88d5e) | May 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [65310866eb](https://linux-hardware.org/?probe=65310866eb) | May 31, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ff3d2367ee](https://linux-hardware.org/?probe=ff3d2367ee) | May 30, 2021 |
| HP            | 8056                        | [fc6d4c2e7d](https://linux-hardware.org/?probe=fc6d4c2e7d) | May 30, 2021 |
| Huanan        | X79 VAA1                    | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| ASRock        | FM2A55M-VG3+                | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| Dell          | 00V62H A01                  | [73da9f35d4](https://linux-hardware.org/?probe=73da9f35d4) | May 29, 2021 |
| ASUSTek       | A88X-PRO                    | [bdb612797a](https://linux-hardware.org/?probe=bdb612797a) | May 29, 2021 |
| Gigabyte      | H370N WIFI-CF               | [197e319075](https://linux-hardware.org/?probe=197e319075) | May 29, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [06bb083e38](https://linux-hardware.org/?probe=06bb083e38) | May 29, 2021 |
| Gigabyte      | B360M D3H-CF                | [f23de0d726](https://linux-hardware.org/?probe=f23de0d726) | May 28, 2021 |
| Gigabyte      | H61M-S2PH                   | [e88de55691](https://linux-hardware.org/?probe=e88de55691) | May 28, 2021 |
| Dell          | 00V62H A01                  | [927f339e68](https://linux-hardware.org/?probe=927f339e68) | May 28, 2021 |
| ASRock        | B450M Pro4                  | [ccd56acb24](https://linux-hardware.org/?probe=ccd56acb24) | May 27, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [5474165f7b](https://linux-hardware.org/?probe=5474165f7b) | May 27, 2021 |
| Unknown       | X79                         | [c6dcb137fb](https://linux-hardware.org/?probe=c6dcb137fb) | May 27, 2021 |
| ASRock        | X99 Extreme4                | [6feb0aec47](https://linux-hardware.org/?probe=6feb0aec47) | May 26, 2021 |
| HP            | 21D0                        | [d6d7cbe7c5](https://linux-hardware.org/?probe=d6d7cbe7c5) | May 26, 2021 |
| HP            | 21D0                        | [68f25edcdd](https://linux-hardware.org/?probe=68f25edcdd) | May 26, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [a6751fcc02](https://linux-hardware.org/?probe=a6751fcc02) | May 26, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [b07793f86c](https://linux-hardware.org/?probe=b07793f86c) | May 25, 2021 |
| Gigabyte      | Z97N-Gaming 5               | [b1b61b4aa6](https://linux-hardware.org/?probe=b1b61b4aa6) | May 25, 2021 |
| Intel         | H61                         | [5b5682ab2e](https://linux-hardware.org/?probe=5b5682ab2e) | May 25, 2021 |
| ASRock        | A300M-STX                   | [cecc5ad69e](https://linux-hardware.org/?probe=cecc5ad69e) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | [cf4e1cb0d6](https://linux-hardware.org/?probe=cf4e1cb0d6) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | [e65ad78e90](https://linux-hardware.org/?probe=e65ad78e90) | May 24, 2021 |
| HP            | 198E                        | [45fbf9c1d7](https://linux-hardware.org/?probe=45fbf9c1d7) | May 23, 2021 |
| Unknown       | Unknown                     | [ad90a50d8d](https://linux-hardware.org/?probe=ad90a50d8d) | May 22, 2021 |
| Unknown       | Unknown                     | [acaa4c3731](https://linux-hardware.org/?probe=acaa4c3731) | May 22, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d3762e2020](https://linux-hardware.org/?probe=d3762e2020) | May 21, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [662203ff7f](https://linux-hardware.org/?probe=662203ff7f) | May 21, 2021 |
| ASRock        | E3C226D2I                   | [195f9748ad](https://linux-hardware.org/?probe=195f9748ad) | May 20, 2021 |
| ASUSTek       | ROG STRIX B460-H GAMING     | [7911704f32](https://linux-hardware.org/?probe=7911704f32) | May 19, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| ASUSTek       | Z97-A                       | [0767c99abb](https://linux-hardware.org/?probe=0767c99abb) | May 19, 2021 |
| Unknown       | X79                         | [718089029d](https://linux-hardware.org/?probe=718089029d) | May 18, 2021 |
| Acer          | Veriton X2640G V:1.0        | [6e95528aca](https://linux-hardware.org/?probe=6e95528aca) | May 18, 2021 |
| ASUSTek       | PRIME Z370-A II             | [5a5c05e953](https://linux-hardware.org/?probe=5a5c05e953) | May 18, 2021 |
| ASUSTek       | Z77-A                       | [5569c32840](https://linux-hardware.org/?probe=5569c32840) | May 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [64c121a751](https://linux-hardware.org/?probe=64c121a751) | May 18, 2021 |
| ASRock        | Z370 Professional Gaming... | [2c915c81d9](https://linux-hardware.org/?probe=2c915c81d9) | May 18, 2021 |
| Dell          | 077RRV A00                  | [c9ed9d5dfa](https://linux-hardware.org/?probe=c9ed9d5dfa) | May 17, 2021 |
| ASRock        | Z270 Pro4                   | [ba92e877c3](https://linux-hardware.org/?probe=ba92e877c3) | May 17, 2021 |
| MSI           | H110I PRO AC                | [17722fe0bf](https://linux-hardware.org/?probe=17722fe0bf) | May 17, 2021 |
| Gigabyte      | Z370N WIFI-CF               | [ca8565e246](https://linux-hardware.org/?probe=ca8565e246) | May 17, 2021 |
| MSI           | X570-A PRO                  | [16c877dbfe](https://linux-hardware.org/?probe=16c877dbfe) | May 16, 2021 |
| ASUSTek       | P7P55 LX                    | [35257f4cf0](https://linux-hardware.org/?probe=35257f4cf0) | May 16, 2021 |
| ASRock        | FM2A55M-VG3+                | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [be75687645](https://linux-hardware.org/?probe=be75687645) | May 15, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [344858ad94](https://linux-hardware.org/?probe=344858ad94) | May 15, 2021 |
| Alienware     | 07HV66 A01                  | [016da6343d](https://linux-hardware.org/?probe=016da6343d) | May 15, 2021 |
| MSI           | B560M PRO-VDH WIFI          | [529fdcaf2a](https://linux-hardware.org/?probe=529fdcaf2a) | May 14, 2021 |
| Unknown       | NF-MCP78                    | [a419bff4a3](https://linux-hardware.org/?probe=a419bff4a3) | May 14, 2021 |
| ASRock        | X570 Creator                | [6ac8300ce8](https://linux-hardware.org/?probe=6ac8300ce8) | May 14, 2021 |
| ASUSTek       | M5A97                       | [3853338a60](https://linux-hardware.org/?probe=3853338a60) | May 14, 2021 |
| Acer          | Veriton X2640G V:1.0        | [924b420c67](https://linux-hardware.org/?probe=924b420c67) | May 13, 2021 |
| Dell          | 0HD5W2 A01                  | [3d9373090c](https://linux-hardware.org/?probe=3d9373090c) | May 13, 2021 |
| ASUSTek       | Benicia                     | [d8f52bab1c](https://linux-hardware.org/?probe=d8f52bab1c) | May 12, 2021 |
| ASUSTek       | Benicia                     | [a36fa0a3b4](https://linux-hardware.org/?probe=a36fa0a3b4) | May 12, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [22e9d3f5fd](https://linux-hardware.org/?probe=22e9d3f5fd) | May 12, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [fab7d18783](https://linux-hardware.org/?probe=fab7d18783) | May 12, 2021 |
| ASRock        | FM2A55M-VG3+                | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| MSI           | B350M GAMING PRO            | [565e8ea07c](https://linux-hardware.org/?probe=565e8ea07c) | May 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | [cff0fbf297](https://linux-hardware.org/?probe=cff0fbf297) | May 11, 2021 |
| MSI           | H170A GAMING PRO            | [a7c97c0108](https://linux-hardware.org/?probe=a7c97c0108) | May 10, 2021 |
| HP            | 1494                        | [26a35b5f46](https://linux-hardware.org/?probe=26a35b5f46) | May 10, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [a3a6a201cf](https://linux-hardware.org/?probe=a3a6a201cf) | May 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [816b6507ca](https://linux-hardware.org/?probe=816b6507ca) | May 09, 2021 |
| ASUSTek       | ProArt B550-CREATOR         | [6969c309d4](https://linux-hardware.org/?probe=6969c309d4) | May 09, 2021 |
| Gigabyte      | H310M H                     | [993800d632](https://linux-hardware.org/?probe=993800d632) | May 08, 2021 |
| Gigabyte      | H87-HD3                     | [ef87a640ab](https://linux-hardware.org/?probe=ef87a640ab) | May 08, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [312ad18259](https://linux-hardware.org/?probe=312ad18259) | May 08, 2021 |
| Biostar       | H81MLC                      | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [d20858b78f](https://linux-hardware.org/?probe=d20858b78f) | May 08, 2021 |
| ASUSTek       | M5A78L-M LX3                | [d6af9c1156](https://linux-hardware.org/?probe=d6af9c1156) | May 07, 2021 |
| ASRock        | X570 Taichi                 | [a0c245e667](https://linux-hardware.org/?probe=a0c245e667) | May 07, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [73fd34e4a9](https://linux-hardware.org/?probe=73fd34e4a9) | May 07, 2021 |
| Acer          | Veriton S2660G              | [31f3a2c202](https://linux-hardware.org/?probe=31f3a2c202) | May 07, 2021 |
| HP            | 1497                        | [bd5ee666bd](https://linux-hardware.org/?probe=bd5ee666bd) | May 07, 2021 |
| HP            | 1497                        | [e52c3c2489](https://linux-hardware.org/?probe=e52c3c2489) | May 06, 2021 |
| HP            | 1791                        | [ad7ad34a9d](https://linux-hardware.org/?probe=ad7ad34a9d) | May 06, 2021 |
| ASUSTek       | PRIME X570-P                | [a34826ba77](https://linux-hardware.org/?probe=a34826ba77) | May 06, 2021 |
| Lenovo        | ThinkCentre M58 8820AJG     | [239c4bf44d](https://linux-hardware.org/?probe=239c4bf44d) | May 06, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [b411cc602f](https://linux-hardware.org/?probe=b411cc602f) | May 06, 2021 |
| Gigabyte      | B75M-D3P                    | [ab4f7cc66d](https://linux-hardware.org/?probe=ab4f7cc66d) | May 06, 2021 |
| ASUSTek       | P5QL-E                      | [1aee0fab6e](https://linux-hardware.org/?probe=1aee0fab6e) | May 05, 2021 |
| MSI           | P55-GD80                    | [e9002ad1ad](https://linux-hardware.org/?probe=e9002ad1ad) | May 04, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [2f8ba8af70](https://linux-hardware.org/?probe=2f8ba8af70) | May 04, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [523fba1dd3](https://linux-hardware.org/?probe=523fba1dd3) | May 04, 2021 |
| ASRock        | H310CM-HDV/M.2              | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| MSI           | B350I PRO AC                | [db10576980](https://linux-hardware.org/?probe=db10576980) | May 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [3ab07ff020](https://linux-hardware.org/?probe=3ab07ff020) | May 03, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [fec58faf85](https://linux-hardware.org/?probe=fec58faf85) | May 03, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [74bff35fdd](https://linux-hardware.org/?probe=74bff35fdd) | May 02, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [3551a877a0](https://linux-hardware.org/?probe=3551a877a0) | May 02, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [d0660819a7](https://linux-hardware.org/?probe=d0660819a7) | May 02, 2021 |
| HP            | 3029h                       | [f0912110eb](https://linux-hardware.org/?probe=f0912110eb) | May 02, 2021 |
| Gigabyte      | B450 AORUS M                | [fe7a0a48f9](https://linux-hardware.org/?probe=fe7a0a48f9) | May 02, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [1c48dea9a3](https://linux-hardware.org/?probe=1c48dea9a3) | May 02, 2021 |
| MSI           | P55-GD80                    | [a950a914fc](https://linux-hardware.org/?probe=a950a914fc) | May 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e019fb0b7a](https://linux-hardware.org/?probe=e019fb0b7a) | May 01, 2021 |
| Biostar       | TB350-BTC                   | [905cd6f7b5](https://linux-hardware.org/?probe=905cd6f7b5) | May 01, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [ef811a6184](https://linux-hardware.org/?probe=ef811a6184) | May 01, 2021 |
| MSI           | B365M PRO-VDH               | [e0ff71901e](https://linux-hardware.org/?probe=e0ff71901e) | Apr 30, 2021 |
| ASRock        | H81M-HG4 R4.0               | [3fb3ca76ae](https://linux-hardware.org/?probe=3fb3ca76ae) | Apr 30, 2021 |
| Lenovo        | SDK0J40700 WIN              | [000925bf4b](https://linux-hardware.org/?probe=000925bf4b) | Apr 30, 2021 |
| ASUSTek       | PRIME A520M-K               | [9f2a73a4d2](https://linux-hardware.org/?probe=9f2a73a4d2) | Apr 30, 2021 |
| Gigabyte      | B450 AORUS M                | [179e39ba13](https://linux-hardware.org/?probe=179e39ba13) | Apr 30, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [916b016881](https://linux-hardware.org/?probe=916b016881) | Apr 30, 2021 |
| ASRock        | B450 Pro4                   | [e66999f076](https://linux-hardware.org/?probe=e66999f076) | Apr 30, 2021 |
| ASRock        | A320M-HDV R4.0              | [3bb19f53e9](https://linux-hardware.org/?probe=3bb19f53e9) | Apr 30, 2021 |
| HP            | 82F2 A01                    | [abecc29894](https://linux-hardware.org/?probe=abecc29894) | Apr 30, 2021 |
| HP            | 82F2 A01                    | [6c0f1f15f5](https://linux-hardware.org/?probe=6c0f1f15f5) | Apr 30, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [fcfd291a4f](https://linux-hardware.org/?probe=fcfd291a4f) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fb11e4cdcc](https://linux-hardware.org/?probe=fb11e4cdcc) | Apr 29, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [a93721363c](https://linux-hardware.org/?probe=a93721363c) | Apr 29, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [a09dab9f9b](https://linux-hardware.org/?probe=a09dab9f9b) | Apr 29, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [492d410d60](https://linux-hardware.org/?probe=492d410d60) | Apr 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ac1ae66d11](https://linux-hardware.org/?probe=ac1ae66d11) | Apr 29, 2021 |
| MSI           | GF615M-P33                  | [4219571ca8](https://linux-hardware.org/?probe=4219571ca8) | Apr 29, 2021 |
| ASUSTek       | H110M-K                     | [f323b316a2](https://linux-hardware.org/?probe=f323b316a2) | Apr 29, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [2ff23ca44c](https://linux-hardware.org/?probe=2ff23ca44c) | Apr 28, 2021 |
| MSI           | B250 PC MATE                | [4feda9bc8e](https://linux-hardware.org/?probe=4feda9bc8e) | Apr 28, 2021 |
| Medion        | Cattle24 1M                 | [2273e237c4](https://linux-hardware.org/?probe=2273e237c4) | Apr 28, 2021 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [69827caaf1](https://linux-hardware.org/?probe=69827caaf1) | Apr 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [97016e3ff3](https://linux-hardware.org/?probe=97016e3ff3) | Apr 27, 2021 |
| ASRock        | H81M-HG4 R4.0               | [4a7617821f](https://linux-hardware.org/?probe=4a7617821f) | Apr 25, 2021 |
| ASRock        | K10N78D                     | [9b0a7f242b](https://linux-hardware.org/?probe=9b0a7f242b) | Apr 24, 2021 |
| Gigabyte      | B150M-D3H-CF                | [573385087f](https://linux-hardware.org/?probe=573385087f) | Apr 24, 2021 |
| MSI           | Z370-A PRO                  | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| Gigabyte      | B150M-D3H-CF                | [4ea82584ae](https://linux-hardware.org/?probe=4ea82584ae) | Apr 23, 2021 |
| eMachines     | EMCP73VT-PM                 | [4e2eabe9ea](https://linux-hardware.org/?probe=4e2eabe9ea) | Apr 21, 2021 |
| MSI           | MEG Z390 GODLIKE            | [320bab5ee4](https://linux-hardware.org/?probe=320bab5ee4) | Apr 21, 2021 |
| Gigabyte      | B450M DS3H V2               | [7b5da54a3b](https://linux-hardware.org/?probe=7b5da54a3b) | Apr 20, 2021 |
| MSI           | B350M PRO-VDH               | [50704a4b1b](https://linux-hardware.org/?probe=50704a4b1b) | Apr 20, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [3aa509bfc6](https://linux-hardware.org/?probe=3aa509bfc6) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [4046940d3e](https://linux-hardware.org/?probe=4046940d3e) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [41035d03ea](https://linux-hardware.org/?probe=41035d03ea) | Apr 19, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [2fe3493737](https://linux-hardware.org/?probe=2fe3493737) | Apr 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [414dee060e](https://linux-hardware.org/?probe=414dee060e) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| ASRock        | AB350 Pro4                  | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a4b4d5abd6](https://linux-hardware.org/?probe=a4b4d5abd6) | Apr 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [0b127087c5](https://linux-hardware.org/?probe=0b127087c5) | Apr 09, 2021 |
| ASUSTek       | H110M-K                     | [b2c194ec6f](https://linux-hardware.org/?probe=b2c194ec6f) | Apr 09, 2021 |
| Lenovo        | ThinkCentre M91 2491A3G     | [d27988d8dd](https://linux-hardware.org/?probe=d27988d8dd) | Apr 09, 2021 |
| Gigabyte      | Z97N-WIFI                   | [6e9360be26](https://linux-hardware.org/?probe=6e9360be26) | Apr 09, 2021 |
| ASUSTek       | Maximus VII HERO            | [f1bdcd63e8](https://linux-hardware.org/?probe=f1bdcd63e8) | Apr 09, 2021 |
| Dell          | 0GWHMW A03                  | [a0ff0f4cf3](https://linux-hardware.org/?probe=a0ff0f4cf3) | Apr 08, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [b3b901029c](https://linux-hardware.org/?probe=b3b901029c) | Apr 07, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [2824275b63](https://linux-hardware.org/?probe=2824275b63) | Apr 07, 2021 |
| MSI           | B350M GAMING PRO            | [de5a14a4f3](https://linux-hardware.org/?probe=de5a14a4f3) | Apr 06, 2021 |
| ASUSTek       | Z87-DELUXE                  | [e4f7f8688b](https://linux-hardware.org/?probe=e4f7f8688b) | Apr 05, 2021 |
| Gigabyte      | H310M H x.x                 | [ec750c2771](https://linux-hardware.org/?probe=ec750c2771) | Apr 05, 2021 |
| Unknown       | Unknown                     | [d38419f785](https://linux-hardware.org/?probe=d38419f785) | Apr 04, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [42b83bbd08](https://linux-hardware.org/?probe=42b83bbd08) | Apr 03, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [9e4b82fb49](https://linux-hardware.org/?probe=9e4b82fb49) | Apr 02, 2021 |
| Gigabyte      | A520M DS3H                  | [6977cb0073](https://linux-hardware.org/?probe=6977cb0073) | Mar 31, 2021 |
| ASUSTek       | H61M-E                      | [fcc9dabb3d](https://linux-hardware.org/?probe=fcc9dabb3d) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | [ed7f2979b9](https://linux-hardware.org/?probe=ed7f2979b9) | Mar 30, 2021 |
| Alienware     | 0FRTKJ A00                  | [e31c5f36aa](https://linux-hardware.org/?probe=e31c5f36aa) | Mar 28, 2021 |
| MSI           | Z490-A PRO                  | [cf1b5653e8](https://linux-hardware.org/?probe=cf1b5653e8) | Mar 28, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [b41b0c2610](https://linux-hardware.org/?probe=b41b0c2610) | Mar 28, 2021 |
| Gigabyte      | H87-HD3                     | [87cb9f98e5](https://linux-hardware.org/?probe=87cb9f98e5) | Mar 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0e12cc8e95](https://linux-hardware.org/?probe=0e12cc8e95) | Mar 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [a0f771669c](https://linux-hardware.org/?probe=a0f771669c) | Mar 24, 2021 |
| Gigabyte      | A320M-H-CF                  | [01c43fc8b4](https://linux-hardware.org/?probe=01c43fc8b4) | Mar 23, 2021 |
| MSI           | 760GM-P21                   | [91a13be8c4](https://linux-hardware.org/?probe=91a13be8c4) | Mar 17, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6124e0aa83](https://linux-hardware.org/?probe=6124e0aa83) | Mar 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [07cd9eac56](https://linux-hardware.org/?probe=07cd9eac56) | Mar 17, 2021 |
| Gigabyte      | Z490 VISION D               | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | [6b611bf344](https://linux-hardware.org/?probe=6b611bf344) | Feb 26, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [fdc4baf022](https://linux-hardware.org/?probe=fdc4baf022) | Feb 23, 2021 |
| ECS           | MCP61M-M3                   | [445f06dbde](https://linux-hardware.org/?probe=445f06dbde) | Jan 29, 2021 |
| ASUSTek       | PRIME X570-PRO              | [e3a5631517](https://linux-hardware.org/?probe=e3a5631517) | Nov 15, 2020 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [f695c35adf](https://linux-hardware.org/?probe=f695c35adf) | Oct 12, 2020 |
| Positivo      | POS-PARS760GCD              | [482e549764](https://linux-hardware.org/?probe=482e549764) | Sep 05, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_34/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.13.12-200.fc34.x86_64 | 39       | 6.34%   |
| 5.11.12-300.fc34.x86_64 | 34       | 5.53%   |
| 5.12.13-300.fc34.x86_64 | 30       | 4.88%   |
| 5.11.16-300.fc34.x86_64 | 24       | 3.9%    |
| 5.14.9-200.fc34.x86_64  | 23       | 3.74%   |
| 5.12.8-300.fc34.x86_64  | 23       | 3.74%   |
| 5.13.4-200.fc34.x86_64  | 19       | 3.09%   |
| 5.13.19-200.fc34.x86_64 | 17       | 2.76%   |
| 5.13.16-200.fc34.x86_64 | 17       | 2.76%   |
| 5.12.12-300.fc34.x86_64 | 17       | 2.76%   |
| 5.11.17-300.fc34.x86_64 | 17       | 2.76%   |
| 5.12.9-300.fc34.x86_64  | 16       | 2.6%    |
| 5.13.9-200.fc34.x86_64  | 15       | 2.44%   |
| 5.12.7-300.fc34.x86_64  | 15       | 2.44%   |
| 5.13.6-200.fc34.x86_64  | 14       | 2.28%   |
| 5.12.15-300.fc34.x86_64 | 14       | 2.28%   |
| 5.11.20-300.fc34.x86_64 | 14       | 2.28%   |
| 5.11.19-300.fc34.x86_64 | 13       | 2.11%   |
| 5.12.14-300.fc34.x86_64 | 12       | 1.95%   |
| 5.14.14-200.fc34.x86_64 | 11       | 1.79%   |
| 5.13.10-200.fc34.x86_64 | 11       | 1.79%   |
| 5.11.18-300.fc34.x86_64 | 11       | 1.79%   |
| 5.13.8-200.fc34.x86_64  | 10       | 1.63%   |
| 5.13.14-200.fc34.x86_64 | 10       | 1.63%   |
| 5.12.11-300.fc34.x86_64 | 10       | 1.63%   |
| 5.11.11-300.fc34.x86_64 | 10       | 1.63%   |
| 5.13.13-200.fc34.x86_64 | 9        | 1.46%   |
| 5.12.6-300.fc34.x86_64  | 9        | 1.46%   |
| 5.14.13-200.fc34.x86_64 | 8        | 1.3%    |
| 5.14.11-200.fc34.x86_64 | 8        | 1.3%    |
| 5.14.16-201.fc34.x86_64 | 7        | 1.14%   |
| 5.13.15-200.fc34.x86_64 | 7        | 1.14%   |
| 5.12.10-300.fc34.x86_64 | 7        | 1.14%   |
| 5.16.18-100.fc34.x86_64 | 6        | 0.98%   |
| 5.13.7-200.fc34.x86_64  | 6        | 0.98%   |
| 5.15.12-100.fc34.x86_64 | 5        | 0.81%   |
| 5.11.3-300.fc34.x86_64  | 5        | 0.81%   |
| 5.17.12-100.fc34.x86_64 | 4        | 0.65%   |
| 5.15.8-100.fc34.x86_64  | 4        | 0.65%   |
| 5.15.10-100.fc34.x86_64 | 4        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.12 | 39       | 6.34%   |
| 5.11.12 | 34       | 5.53%   |
| 5.12.13 | 30       | 4.88%   |
| 5.11.16 | 24       | 3.9%    |
| 5.14.9  | 23       | 3.74%   |
| 5.12.8  | 23       | 3.74%   |
| 5.13.4  | 20       | 3.25%   |
| 5.13.19 | 19       | 3.09%   |
| 5.13.16 | 17       | 2.76%   |
| 5.12.12 | 17       | 2.76%   |
| 5.11.17 | 17       | 2.76%   |
| 5.12.9  | 16       | 2.6%    |
| 5.12.7  | 16       | 2.6%    |
| 5.13.9  | 15       | 2.44%   |
| 5.13.6  | 14       | 2.28%   |
| 5.12.15 | 14       | 2.28%   |
| 5.11.20 | 14       | 2.28%   |
| 5.11.19 | 13       | 2.11%   |
| 5.12.14 | 12       | 1.95%   |
| 5.14.14 | 11       | 1.79%   |
| 5.13.8  | 11       | 1.79%   |
| 5.13.14 | 11       | 1.79%   |
| 5.13.10 | 11       | 1.79%   |
| 5.12.11 | 11       | 1.79%   |
| 5.11.18 | 11       | 1.79%   |
| 5.11.11 | 10       | 1.63%   |
| 5.13.13 | 9        | 1.46%   |
| 5.12.6  | 9        | 1.46%   |
| 5.14.13 | 8        | 1.3%    |
| 5.14.11 | 8        | 1.3%    |
| 5.14.16 | 7        | 1.14%   |
| 5.13.15 | 7        | 1.14%   |
| 5.12.10 | 7        | 1.14%   |
| 5.16.18 | 6        | 0.98%   |
| 5.13.7  | 6        | 0.98%   |
| 5.15.12 | 5        | 0.81%   |
| 5.11.3  | 5        | 0.81%   |
| 5.17.12 | 4        | 0.65%   |
| 5.15.8  | 4        | 0.65%   |
| 5.15.10 | 4        | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 172      | 29.4%   |
| 5.12    | 155      | 26.5%   |
| 5.11    | 149      | 25.47%  |
| 5.14    | 62       | 10.6%   |
| 5.15    | 21       | 3.59%   |
| 5.16    | 13       | 2.22%   |
| 5.17    | 9        | 1.54%   |
| 5.10    | 2        | 0.34%   |
| 5.9     | 1        | 0.17%   |
| 5.4     | 1        | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 518      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 366      | 69.32%  |
| KDE5          | 50       | 9.47%   |
| KDE           | 27       | 5.11%   |
| Unknown       | 21       | 3.98%   |
| Cinnamon      | 18       | 3.41%   |
| X-Cinnamon    | 13       | 2.46%   |
| XFCE          | 12       | 2.27%   |
| MATE          | 10       | 1.89%   |
| GNOME Classic | 3        | 0.57%   |
| qtile         | 1        | 0.19%   |
| openbox       | 1        | 0.19%   |
| NsCDE         | 1        | 0.19%   |
| LXDE          | 1        | 0.19%   |
| KDE4          | 1        | 0.19%   |
| i3            | 1        | 0.19%   |
| Deepin        | 1        | 0.19%   |
| awesome       | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 271      | 50%     |
| X11     | 232      | 42.8%   |
| Tty     | 27       | 4.98%   |
| Unknown | 12       | 2.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 293      | 55.08%  |
| GDM     | 155      | 29.14%  |
| SDDM    | 35       | 6.58%   |
| LightDM | 35       | 6.58%   |
| TDM     | 13       | 2.44%   |
| KDM     | 1        | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 242      | 46.36%  |
| en_GB   | 42       | 8.05%   |
| pt_BR   | 32       | 6.13%   |
| ru_RU   | 25       | 4.79%   |
| en_AU   | 23       | 4.41%   |
| fr_FR   | 20       | 3.83%   |
| en_CA   | 20       | 3.83%   |
| de_DE   | 20       | 3.83%   |
| pl_PL   | 9        | 1.72%   |
| it_IT   | 8        | 1.53%   |
| ja_JP   | 6        | 1.15%   |
| es_ES   | 6        | 1.15%   |
| Unknown | 5        | 0.96%   |
| ru_UA   | 4        | 0.77%   |
| en_NZ   | 4        | 0.77%   |
| en_IN   | 4        | 0.77%   |
| cs_CZ   | 4        | 0.77%   |
| nl_BE   | 3        | 0.57%   |
| fr_CH   | 3        | 0.57%   |
| es_AR   | 3        | 0.57%   |
| C       | 3        | 0.57%   |
| sk_SK   | 2        | 0.38%   |
| nl_NL   | 2        | 0.38%   |
| fi_FI   | 2        | 0.38%   |
| es_MX   | 2        | 0.38%   |
| es_EC   | 2        | 0.38%   |
| es_CL   | 2        | 0.38%   |
| en_SG   | 2        | 0.38%   |
| zh_TW   | 1        | 0.19%   |
| uk_UA   | 1        | 0.19%   |
| sv_SE   | 1        | 0.19%   |
| sr_RS   | 1        | 0.19%   |
| ko_KR   | 1        | 0.19%   |
| id_ID   | 1        | 0.19%   |
| hu_HU   | 1        | 0.19%   |
| es_UY   | 1        | 0.19%   |
| es_PA   | 1        | 0.19%   |
| es_GT   | 1        | 0.19%   |
| es_DO   | 1        | 0.19%   |
| es_CO   | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 329      | 63.03%  |
| BIOS | 193      | 36.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 325      | 62.5%   |
| Ext4                | 157      | 30.19%  |
| Xfs                 | 33       | 6.35%   |
| Zfs                 | 3        | 0.58%   |
| Fuse.fuse-overlayfs | 1        | 0.19%   |
| Ext3                | 1        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 285      | 53.98%  |
| GPT     | 188      | 35.61%  |
| MBR     | 55       | 10.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 433      | 82.48%  |
| Yes       | 92       | 17.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 393      | 75.29%  |
| Yes       | 129      | 24.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 137      | 26.45%  |
| Gigabyte Technology | 113      | 21.81%  |
| MSI                 | 70       | 13.51%  |
| ASRock              | 60       | 11.58%  |
| Hewlett-Packard     | 31       | 5.98%   |
| Dell                | 28       | 5.41%   |
| Lenovo              | 16       | 3.09%   |
| Intel               | 10       | 1.93%   |
| Unknown             | 8        | 1.54%   |
| Acer                | 6        | 1.16%   |
| Biostar             | 5        | 0.97%   |
| Fujitsu             | 4        | 0.77%   |
| Huanan              | 3        | 0.58%   |
| ECS                 | 3        | 0.58%   |
| Alienware           | 3        | 0.58%   |
| Foxconn             | 2        | 0.39%   |
| EVGA                | 2        | 0.39%   |
| Apple               | 2        | 0.39%   |
| SYWZ                | 1        | 0.19%   |
| System76            | 1        | 0.19%   |
| Supermicro          | 1        | 0.19%   |
| Samsung Electronics | 1        | 0.19%   |
| Positivo            | 1        | 0.19%   |
| Pegatron            | 1        | 0.19%   |
| Medion              | 1        | 0.19%   |
| Itautec             | 1        | 0.19%   |
| Google              | 1        | 0.19%   |
| Gateway             | 1        | 0.19%   |
| eMachines           | 1        | 0.19%   |
| Colorful Technology | 1        | 0.19%   |
| BESSTAR Tech        | 1        | 0.19%   |
| ASRockRack          | 1        | 0.19%   |
| AMD                 | 1        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 13       | 2.51%   |
| MSI MS-7C37                      | 9        | 1.74%   |
| Unknown                          | 8        | 1.54%   |
| MSI MS-7C02                      | 5        | 0.97%   |
| Gigabyte B450 I AORUS PRO WIFI   | 4        | 0.77%   |
| ASUS TUF Gaming X570-PLUS        | 4        | 0.77%   |
| ASUS ROG CROSSHAIR VII HERO      | 4        | 0.77%   |
| MSI MS-7C84                      | 3        | 0.58%   |
| MSI MS-7A38                      | 3        | 0.58%   |
| Intel H61                        | 3        | 0.58%   |
| Gigabyte B450M DS3H              | 3        | 0.58%   |
| Gigabyte B450 AORUS M            | 3        | 0.58%   |
| Gigabyte A320M-S2H               | 3        | 0.58%   |
| ASUS TUF Gaming B550M-PLUS       | 3        | 0.58%   |
| ASUS ROG STRIX X570-E GAMING     | 3        | 0.58%   |
| ASUS ROG STRIX B450-F GAMING     | 3        | 0.58%   |
| ASUS PRIME X470-PRO              | 3        | 0.58%   |
| MSI MS-7C91                      | 2        | 0.39%   |
| MSI MS-7C35                      | 2        | 0.39%   |
| MSI MS-7B98                      | 2        | 0.39%   |
| MSI MS-7B85                      | 2        | 0.39%   |
| MSI MS-7B48                      | 2        | 0.39%   |
| MSI MS-7A40                      | 2        | 0.39%   |
| MSI MS-7A39                      | 2        | 0.39%   |
| HP ProDesk 600 G1 DM             | 2        | 0.39%   |
| HP EliteDesk 800 G1 SFF          | 2        | 0.39%   |
| HP Compaq 6200 Pro SFF PC        | 2        | 0.39%   |
| Gigabyte Z370N WIFI              | 2        | 0.39%   |
| Gigabyte Z170-D3H                | 2        | 0.39%   |
| Gigabyte X570 AORUS PRO WIFI     | 2        | 0.39%   |
| Gigabyte X570 AORUS MASTER       | 2        | 0.39%   |
| Gigabyte X570 AORUS ELITE WIFI   | 2        | 0.39%   |
| Gigabyte X470 AORUS ULTRA GAMING | 2        | 0.39%   |
| Gigabyte H310M H 2.0             | 2        | 0.39%   |
| Gigabyte H310M H                 | 2        | 0.39%   |
| Gigabyte B550I AORUS PRO AX      | 2        | 0.39%   |
| Gigabyte B450 AORUS PRO WIFI     | 2        | 0.39%   |
| Gigabyte B450 AORUS ELITE V2     | 2        | 0.39%   |
| Gigabyte B450 AORUS ELITE        | 2        | 0.39%   |
| Gigabyte B250M-DS3H              | 2        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS ROG            | 38       | 7.34%   |
| ASUS PRIME          | 24       | 4.63%   |
| Dell OptiPlex       | 17       | 3.28%   |
| Gigabyte B450       | 14       | 2.7%    |
| ASUS All            | 13       | 2.51%   |
| ASUS TUF            | 12       | 2.32%   |
| Lenovo ThinkCentre  | 10       | 1.93%   |
| MSI MS-7C37         | 9        | 1.74%   |
| HP EliteDesk        | 8        | 1.54%   |
| Unknown             | 8        | 1.54%   |
| HP Compaq           | 7        | 1.35%   |
| Gigabyte X570       | 7        | 1.35%   |
| MSI MS-7C02         | 5        | 0.97%   |
| Gigabyte B450M      | 5        | 0.97%   |
| ASUS P8H61-M        | 5        | 0.97%   |
| ASRock X570         | 5        | 0.97%   |
| HP ProDesk          | 4        | 0.77%   |
| Gigabyte H310M      | 4        | 0.77%   |
| Fujitsu ESPRIMO     | 4        | 0.77%   |
| Dell XPS            | 4        | 0.77%   |
| ASRock X399         | 4        | 0.77%   |
| ASRock B450         | 4        | 0.77%   |
| Acer Aspire         | 4        | 0.77%   |
| MSI MS-7C84         | 3        | 0.58%   |
| MSI MS-7A38         | 3        | 0.58%   |
| Lenovo ThinkStation | 3        | 0.58%   |
| Intel H61           | 3        | 0.58%   |
| Gigabyte Z390       | 3        | 0.58%   |
| Gigabyte X470       | 3        | 0.58%   |
| Gigabyte A320M-S2H  | 3        | 0.58%   |
| ASRock Z390         | 3        | 0.58%   |
| ASRock B550         | 3        | 0.58%   |
| MSI MS-7C91         | 2        | 0.39%   |
| MSI MS-7C35         | 2        | 0.39%   |
| MSI MS-7B98         | 2        | 0.39%   |
| MSI MS-7B85         | 2        | 0.39%   |
| MSI MS-7B48         | 2        | 0.39%   |
| MSI MS-7A40         | 2        | 0.39%   |
| MSI MS-7A39         | 2        | 0.39%   |
| Huanan X79          | 2        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 91       | 17.57%  |
| 2019    | 62       | 11.97%  |
| 2020    | 61       | 11.78%  |
| 2017    | 49       | 9.46%   |
| 2014    | 30       | 5.79%   |
| 2013    | 30       | 5.79%   |
| 2021    | 28       | 5.41%   |
| 2016    | 28       | 5.41%   |
| 2012    | 27       | 5.21%   |
| 2015    | 24       | 4.63%   |
| 2011    | 23       | 4.44%   |
| 2010    | 19       | 3.67%   |
| 2009    | 16       | 3.09%   |
| 2008    | 16       | 3.09%   |
| 2007    | 5        | 0.97%   |
| 2006    | 5        | 0.97%   |
| 2005    | 2        | 0.39%   |
| Unknown | 2        | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 518      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 499      | 95.59%  |
| Enabled  | 23       | 4.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 517      | 99.81%  |
| Yes  | 1        | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 151      | 28.65%  |
| 32.01-64.0  | 121      | 22.96%  |
| 8.01-16.0   | 90       | 17.08%  |
| 4.01-8.0    | 65       | 12.33%  |
| 3.01-4.0    | 39       | 7.4%    |
| 64.01-256.0 | 38       | 7.21%   |
| 24.01-32.0  | 17       | 3.23%   |
| 2.01-3.0    | 3        | 0.57%   |
| 1.01-2.0    | 3        | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 156      | 27.23%  |
| 2.01-3.0   | 141      | 24.61%  |
| 3.01-4.0   | 110      | 19.2%   |
| 1.01-2.0   | 93       | 16.23%  |
| 8.01-16.0  | 39       | 6.81%   |
| 0.51-1.0   | 15       | 2.62%   |
| 16.01-24.0 | 9        | 1.57%   |
| 24.01-32.0 | 4        | 0.7%    |
| 32.01-64.0 | 3        | 0.52%   |
| 0.01-0.5   | 3        | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 156      | 29.38%  |
| 1      | 133      | 25.05%  |
| 3      | 123      | 23.16%  |
| 4      | 57       | 10.73%  |
| 5      | 26       | 4.9%    |
| 6      | 14       | 2.64%   |
| 8      | 9        | 1.69%   |
| 7      | 5        | 0.94%   |
| 0      | 3        | 0.56%   |
| 12     | 2        | 0.38%   |
| 9      | 2        | 0.38%   |
| 15     | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 325      | 62.14%  |
| Yes       | 198      | 37.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 513      | 99.03%  |
| No        | 5        | 0.97%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 264      | 50.48%  |
| Yes       | 259      | 49.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 289      | 55.47%  |
| Yes       | 232      | 44.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 115      | 22.16%  |
| Brazil             | 43       | 8.29%   |
| Germany            | 36       | 6.94%   |
| Russia             | 28       | 5.39%   |
| Australia          | 26       | 5.01%   |
| Canada             | 25       | 4.82%   |
| France             | 23       | 4.43%   |
| UK                 | 22       | 4.24%   |
| Poland             | 17       | 3.28%   |
| Spain              | 14       | 2.7%    |
| Italy              | 12       | 2.31%   |
| Sweden             | 11       | 2.12%   |
| India              | 10       | 1.93%   |
| Switzerland        | 9        | 1.73%   |
| Ukraine            | 8        | 1.54%   |
| Czechia            | 8        | 1.54%   |
| Belgium            | 8        | 1.54%   |
| Japan              | 6        | 1.16%   |
| New Zealand        | 5        | 0.96%   |
| Romania            | 4        | 0.77%   |
| Norway             | 4        | 0.77%   |
| Netherlands        | 4        | 0.77%   |
| Finland            | 4        | 0.77%   |
| Chile              | 4        | 0.77%   |
| Belarus            | 4        | 0.77%   |
| Austria            | 4        | 0.77%   |
| Argentina          | 4        | 0.77%   |
| Turkey             | 3        | 0.58%   |
| Slovakia           | 3        | 0.58%   |
| Mexico             | 3        | 0.58%   |
| Hungary            | 3        | 0.58%   |
| Estonia            | 3        | 0.58%   |
| South Korea        | 2        | 0.39%   |
| Portugal           | 2        | 0.39%   |
| Pakistan           | 2        | 0.39%   |
| Malaysia           | 2        | 0.39%   |
| Indonesia          | 2        | 0.39%   |
| Greece             | 2        | 0.39%   |
| Ecuador            | 2        | 0.39%   |
| Dominican Republic | 2        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 18       | 3.35%   |
| Moscow         | 7        | 1.3%    |
| St Petersburg  | 6        | 1.12%   |
| Madrid         | 6        | 1.12%   |
| Toronto        | 5        | 0.93%   |
| Rio de Janeiro | 4        | 0.74%   |
| Minsk          | 4        | 0.74%   |
| Cologne        | 4        | 0.74%   |
| Berlin         | 4        | 0.74%   |
| Belo Horizonte | 4        | 0.74%   |
| Yekaterinburg  | 3        | 0.56%   |
| Warsaw         | 3        | 0.56%   |
| Vienna         | 3        | 0.56%   |
| Ufa            | 3        | 0.56%   |
| Tallinn        | 3        | 0.56%   |
| Saitama        | 3        | 0.56%   |
| Prague         | 3        | 0.56%   |
| Pilsen         | 3        | 0.56%   |
| Paris          | 3        | 0.56%   |
| Kansas City    | 3        | 0.56%   |
| Brussels       | 3        | 0.56%   |
| Auckland       | 3        | 0.56%   |
| Wroclaw        | 2        | 0.37%   |
| Vijayawada     | 2        | 0.37%   |
| Ulm            | 2        | 0.37%   |
| Tawau          | 2        | 0.37%   |
| Tallahassee    | 2        | 0.37%   |
| Sorocaba       | 2        | 0.37%   |
| Serra          | 2        | 0.37%   |
| Sao Paulo      | 2        | 0.37%   |
| Riverside      | 2        | 0.37%   |
| Pflugerville   | 2        | 0.37%   |
| Novopskov      | 2        | 0.37%   |
| Morges         | 2        | 0.37%   |
| Montreal       | 2        | 0.37%   |
| Minneapolis    | 2        | 0.37%   |
| Miami          | 2        | 0.37%   |
| Melbourne      | 2        | 0.37%   |
| Lyon           | 2        | 0.37%   |
| Lucerne        | 2        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 193      | 397    | 18.16%  |
| WDC                       | 180      | 297    | 16.93%  |
| Seagate                   | 179      | 301    | 16.84%  |
| Kingston                  | 77       | 98     | 7.24%   |
| Crucial                   | 60       | 87     | 5.64%   |
| Toshiba                   | 51       | 77     | 4.8%    |
| SanDisk                   | 43       | 50     | 4.05%   |
| Hitachi                   | 38       | 52     | 3.57%   |
| Intel                     | 26       | 44     | 2.45%   |
| Phison                    | 17       | 22     | 1.6%    |
| A-DATA Technology         | 16       | 18     | 1.51%   |
| Corsair                   | 14       | 19     | 1.32%   |
| Micron Technology         | 11       | 15     | 1.03%   |
| SK hynix                  | 9        | 12     | 0.85%   |
| HGST                      | 9        | 19     | 0.85%   |
| SPCC                      | 8        | 9      | 0.75%   |
| Unknown                   | 7        | 9      | 0.66%   |
| Patriot                   | 7        | 7      | 0.66%   |
| OCZ                       | 7        | 12     | 0.66%   |
| Micron/Crucial Technology | 7        | 8      | 0.66%   |
| XPG                       | 6        | 7      | 0.56%   |
| PNY                       | 6        | 9      | 0.56%   |
| Gigabyte Technology       | 6        | 7      | 0.56%   |
| China                     | 6        | 6      | 0.56%   |
| Silicon Motion            | 5        | 5      | 0.47%   |
| Team                      | 4        | 5      | 0.38%   |
| Maxtor                    | 4        | 5      | 0.38%   |
| Transcend                 | 3        | 3      | 0.28%   |
| SABRENT                   | 3        | 3      | 0.28%   |
| Phison Electronics        | 3        | 10     | 0.28%   |
| LITEONIT                  | 3        | 3      | 0.28%   |
| LITEON                    | 3        | 3      | 0.28%   |
| KingSpec                  | 3        | 6      | 0.28%   |
| Hewlett-Packard           | 3        | 3      | 0.28%   |
| GOODRAM                   | 3        | 3      | 0.28%   |
| ASMT                      | 3        | 4      | 0.28%   |
| Apple                     | 3        | 3      | 0.28%   |
| Mushkin                   | 2        | 4      | 0.19%   |
| MaxDigital                | 2        | 2      | 0.19%   |
| Apacer                    | 2        | 3      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB       | 23       | 1.76%   |
| Samsung SSD 860 EVO 1TB            | 21       | 1.61%   |
| Seagate ST2000DM008-2FR102 2TB     | 18       | 1.38%   |
| Samsung SSD 860 EVO 500GB          | 18       | 1.38%   |
| Kingston SA400S37240G 240GB SSD    | 17       | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB     | 14       | 1.07%   |
| Seagate ST500DM002-1BD142 500GB    | 13       | 0.99%   |
| Samsung SSD 850 EVO 250GB          | 13       | 0.99%   |
| Samsung NVMe SSD Drive 1TB         | 13       | 0.99%   |
| Samsung SSD 850 EVO 500GB          | 12       | 0.92%   |
| Toshiba DT01ACA100 1TB             | 11       | 0.84%   |
| Samsung NVMe SSD Drive 250GB       | 11       | 0.84%   |
| Crucial CT500MX500SSD1 500GB       | 11       | 0.84%   |
| SanDisk NVMe SSD Drive 500GB       | 10       | 0.77%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 9        | 0.69%   |
| Toshiba DT01ACA200 2TB             | 9        | 0.69%   |
| Samsung SSD 970 EVO Plus 500GB     | 9        | 0.69%   |
| Kingston SA400S37480G 480GB SSD    | 9        | 0.69%   |
| Kingston SA400S37120G 120GB SSD    | 9        | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB     | 8        | 0.61%   |
| Samsung SSD 970 EVO Plus 1TB       | 8        | 0.61%   |
| Samsung SSD 860 QVO 1TB            | 8        | 0.61%   |
| Seagate ST1000DM003-1ER162 1TB     | 7        | 0.54%   |
| Samsung SSD 980 PRO 1TB            | 7        | 0.54%   |
| Kingston SV300S37A120G 120GB SSD   | 7        | 0.54%   |
| Crucial CT1000MX500SSD1 1TB        | 7        | 0.54%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 6        | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB           | 6        | 0.46%   |
| Seagate ST3500418AS 500GB          | 6        | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB     | 6        | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6        | 0.46%   |
| SanDisk NVMe SSD Drive 1TB         | 6        | 0.46%   |
| Samsung SSD 970 EVO 500GB          | 6        | 0.46%   |
| Samsung SSD 840 EVO 250GB          | 6        | 0.46%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 5        | 0.38%   |
| WDC WD40EFRX-68N32N0 4TB           | 5        | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB           | 5        | 0.38%   |
| Toshiba HDWD110 1TB                | 5        | 0.38%   |
| Seagate ST8000DM004-2CX188 8TB     | 5        | 0.38%   |
| Seagate ST31000524AS 1TB           | 5        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 175      | 291    | 38.46%  |
| WDC                 | 150      | 242    | 32.97%  |
| Toshiba             | 40       | 59     | 8.79%   |
| Hitachi             | 38       | 52     | 8.35%   |
| Samsung Electronics | 24       | 42     | 5.27%   |
| HGST                | 9        | 19     | 1.98%   |
| Unknown             | 4        | 5      | 0.88%   |
| Maxtor              | 3        | 3      | 0.66%   |
| MaxDigital          | 2        | 2      | 0.44%   |
| Hewlett-Packard     | 2        | 2      | 0.44%   |
| USB 3.0             | 1        | 1      | 0.22%   |
| Synology            | 1        | 1      | 0.22%   |
| PHD 3.0             | 1        | 1      | 0.22%   |
| Magnetic Data       | 1        | 1      | 0.22%   |
| Inateck             | 1        | 1      | 0.22%   |
| ASMT106x            | 1        | 1      | 0.22%   |
| ASMT                | 1        | 1      | 0.22%   |
| Apple               | 1        | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 115      | 204    | 27.78%  |
| Kingston            | 61       | 79     | 14.73%  |
| Crucial             | 52       | 78     | 12.56%  |
| WDC                 | 26       | 32     | 6.28%   |
| SanDisk             | 25       | 27     | 6.04%   |
| A-DATA Technology   | 14       | 16     | 3.38%   |
| Intel               | 10       | 20     | 2.42%   |
| Micron Technology   | 9        | 12     | 2.17%   |
| Toshiba             | 8        | 9      | 1.93%   |
| Patriot             | 7        | 7      | 1.69%   |
| OCZ                 | 7        | 12     | 1.69%   |
| PNY                 | 6        | 8      | 1.45%   |
| China               | 6        | 6      | 1.45%   |
| SPCC                | 5        | 6      | 1.21%   |
| SK hynix            | 5        | 5      | 1.21%   |
| Team                | 4        | 5      | 0.97%   |
| Gigabyte Technology | 4        | 5      | 0.97%   |
| Transcend           | 3        | 3      | 0.72%   |
| LITEONIT            | 3        | 3      | 0.72%   |
| LITEON              | 3        | 3      | 0.72%   |
| KingSpec            | 3        | 6      | 0.72%   |
| GOODRAM             | 3        | 3      | 0.72%   |
| Corsair             | 3        | 4      | 0.72%   |
| Unknown             | 2        | 2      | 0.48%   |
| Mushkin             | 2        | 4      | 0.48%   |
| ASMT                | 2        | 3      | 0.48%   |
| Apple               | 2        | 2      | 0.48%   |
| Apacer              | 2        | 3      | 0.48%   |
| TEXTORM             | 1        | 1      | 0.24%   |
| SPCC M.2            | 1        | 1      | 0.24%   |
| Smartbuy            | 1        | 1      | 0.24%   |
| Smart               | 1        | 1      | 0.24%   |
| Seagate             | 1        | 1      | 0.24%   |
| Radeon              | 1        | 1      | 0.24%   |
| Plextor             | 1        | 2      | 0.24%   |
| OWC                 | 1        | 1      | 0.24%   |
| ORICO               | 1        | 1      | 0.24%   |
| MG                  | 1        | 1      | 0.24%   |
| Maxtor              | 1        | 2      | 0.24%   |
| Lexar               | 1        | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 341      | 725    | 38.49%  |
| SSD     | 331      | 592    | 37.36%  |
| NVMe    | 205      | 353    | 23.14%  |
| Unknown | 9        | 12     | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 473      | 1277   | 65.79%  |
| NVMe | 202      | 348    | 28.09%  |
| SAS  | 44       | 57     | 6.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 343      | 647    | 45.07%  |
| 0.51-1.0   | 225      | 364    | 29.57%  |
| 1.01-2.0   | 94       | 137    | 12.35%  |
| 3.01-4.0   | 41       | 66     | 5.39%   |
| 4.01-10.0  | 30       | 61     | 3.94%   |
| 2.01-3.0   | 22       | 29     | 2.89%   |
| 10.01-20.0 | 6        | 13     | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 98       | 18.18%  |
| 1001-2000      | 87       | 16.14%  |
| 251-500        | 82       | 15.21%  |
| More than 3000 | 79       | 14.66%  |
| 101-250        | 73       | 13.54%  |
| 2001-3000      | 47       | 8.72%   |
| 1-20           | 34       | 6.31%   |
| Unknown        | 23       | 4.27%   |
| 51-100         | 9        | 1.67%   |
| 21-50          | 7        | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 103      | 18.43%  |
| 501-1000       | 82       | 14.67%  |
| 101-250        | 76       | 13.6%   |
| 21-50          | 72       | 12.88%  |
| 251-500        | 61       | 10.91%  |
| 51-100         | 57       | 10.2%   |
| 1001-2000      | 47       | 8.41%   |
| More than 3000 | 25       | 4.47%   |
| Unknown        | 23       | 4.11%   |
| 2001-3000      | 13       | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 4        | 9      | 5.63%   |
| Intel SSDSC2CT120A3 120GB           | 3        | 8      | 4.23%   |
| WDC WD1003FBYX-01Y7B1 1TB           | 2        | 2      | 2.82%   |
| Toshiba DT01ACA200 2TB              | 2        | 3      | 2.82%   |
| Seagate ST31000524AS 1TB            | 2        | 2      | 2.82%   |
| Kingston SA400S37240G 240GB SSD     | 2        | 2      | 2.82%   |
| Crucial CT275MX300SSD1 275GB        | 2        | 2      | 2.82%   |
| WDC WD60EFAX-68SHWN0 6TB            | 1        | 1      | 1.41%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1        | 1      | 1.41%   |
| WDC WD40PURZ-85AKKY0 4TB            | 1        | 1      | 1.41%   |
| WDC WD30EZRX-00AZ6B0 3TB            | 1        | 1      | 1.41%   |
| WDC WD20EFRX-68AX9N0 2TB            | 1        | 1      | 1.41%   |
| WDC WD1600AVVS-63L2B0 160GB         | 1        | 1      | 1.41%   |
| WDC WD15EARS-00Z5B1 1TB             | 1        | 1      | 1.41%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1        | 1      | 1.41%   |
| WDC WD10EZEX-60WN4A1 1TB            | 1        | 1      | 1.41%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 1      | 1.41%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 1      | 1.41%   |
| Seagate ST9250315AS 250GB           | 1        | 1      | 1.41%   |
| Seagate ST500DM002-1SB10A 500GB     | 1        | 1      | 1.41%   |
| Seagate ST4000DM000-1F2168 4TB      | 1        | 1      | 1.41%   |
| Seagate ST3500630AS 500GB           | 1        | 1      | 1.41%   |
| Seagate ST3500620AS 500GB           | 1        | 1      | 1.41%   |
| Seagate ST3500418AS 500GB           | 1        | 2      | 1.41%   |
| Seagate ST3250410AS 250GB           | 1        | 1      | 1.41%   |
| Seagate ST31000528AS 1TB            | 1        | 1      | 1.41%   |
| Seagate ST31000340NS 1TB            | 1        | 1      | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 1      | 1.41%   |
| Seagate ST1000DX001-1CM162 1TB      | 1        | 1      | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1      | 1.41%   |
| SanDisk SSD U100 64GB               | 1        | 1      | 1.41%   |
| SanDisk SSD PLUS 480GB              | 1        | 1      | 1.41%   |
| SanDisk SDSSDX240GG25 240GB         | 1        | 1      | 1.41%   |
| Samsung Electronics SSD 970 PRO 1TB | 1        | 1      | 1.41%   |
| Samsung Electronics SSD 870 EVO 2TB | 1        | 1      | 1.41%   |
| Samsung Electronics SP2514N 250GB   | 1        | 1      | 1.41%   |
| Samsung Electronics SP2004C 200GB   | 1        | 1      | 1.41%   |
| Samsung Electronics SP1614C 160GB   | 1        | 1      | 1.41%   |
| Samsung Electronics HM160HI 160GB   | 1        | 4      | 1.41%   |
| Samsung Electronics HD501LJ 500GB   | 1        | 10     | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 24     | 25.71%  |
| WDC                 | 13       | 13     | 18.57%  |
| Samsung Electronics | 8        | 20     | 11.43%  |
| Hitachi             | 6        | 7      | 8.57%   |
| Intel               | 5        | 10     | 7.14%   |
| Crucial             | 5        | 5      | 7.14%   |
| SanDisk             | 3        | 3      | 4.29%   |
| Kingston            | 3        | 3      | 4.29%   |
| Toshiba             | 2        | 3      | 2.86%   |
| HGST                | 2        | 3      | 2.86%   |
| A-DATA Technology   | 2        | 2      | 2.86%   |
| ORICO               | 1        | 1      | 1.43%   |
| LITEON              | 1        | 1      | 1.43%   |
| Hewlett-Packard     | 1        | 1      | 1.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 24     | 37.5%   |
| WDC                 | 13       | 13     | 27.08%  |
| Samsung Electronics | 6        | 18     | 12.5%   |
| Hitachi             | 6        | 7      | 12.5%   |
| Toshiba             | 2        | 3      | 4.17%   |
| HGST                | 2        | 3      | 4.17%   |
| Hewlett-Packard     | 1        | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 45       | 69     | 67.16%  |
| SSD  | 20       | 25     | 29.85%  |
| NVMe | 2        | 2      | 2.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Hitachi HDS721010DLE630 1TB | 1        | 4      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 301      | 899    | 49.92%  |
| Works    | 235      | 683    | 38.97%  |
| Malfunc  | 66       | 96     | 10.95%  |
| Failed   | 1        | 4      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 289      | 34.95%  |
| AMD                          | 222      | 26.84%  |
| Samsung Electronics          | 97       | 11.73%  |
| ASMedia Technology           | 39       | 4.72%   |
| Phison Electronics           | 33       | 3.99%   |
| SanDisk                      | 31       | 3.75%   |
| Kingston Technology Company  | 18       | 2.18%   |
| Micron/Crucial Technology    | 15       | 1.81%   |
| Marvell Technology Group     | 13       | 1.57%   |
| JMicron Technology           | 12       | 1.45%   |
| Nvidia                       | 9        | 1.09%   |
| Toshiba America Info Systems | 7        | 0.85%   |
| ADATA Technology             | 7        | 0.85%   |
| Silicon Motion               | 5        | 0.6%    |
| SK hynix                     | 4        | 0.48%   |
| Broadcom / LSI               | 4        | 0.48%   |
| Realtek Semiconductor        | 3        | 0.36%   |
| LSI Logic / Symbios Logic    | 3        | 0.36%   |
| VIA Technologies             | 2        | 0.24%   |
| ULi Electronics              | 2        | 0.24%   |
| Silicon Image                | 2        | 0.24%   |
| Seagate Technology           | 2        | 0.24%   |
| Micron Technology            | 2        | 0.24%   |
| Adaptec                      | 2        | 0.24%   |
| Union Memory (Shenzhen)      | 1        | 0.12%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.12%   |
| HighPoint Technologies       | 1        | 0.12%   |
| Hewlett-Packard              | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 158      | 15.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 66       | 6.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 57       | 5.67%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 38       | 3.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 36       | 3.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 34       | 3.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 31       | 3.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 30       | 2.98%   |
| Intel SATA Controller [RAID mode]                                                       | 23       | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 22       | 2.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 19       | 1.89%   |
| Phison E12 NVMe Controller                                                              | 18       | 1.79%   |
| AMD 300 Series Chipset SATA Controller                                                  | 17       | 1.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 16       | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16       | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 15       | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 15       | 1.49%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 14       | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 1.39%   |
| AMD FCH SATA Controller D                                                               | 14       | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 13       | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 12       | 1.19%   |
| Kingston Company A2000 NVMe SSD                                                         | 10       | 0.99%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 9        | 0.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9        | 0.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 0.89%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 8        | 0.8%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 0.8%    |
| Intel SSD 660P Series                                                                   | 8        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7        | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.7%    |
| AMD X399 Series Chipset SATA Controller                                                 | 7        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 0.6%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 5        | 0.5%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 448      | 58.26%  |
| NVMe | 201      | 26.14%  |
| IDE  | 79       | 10.27%  |
| RAID | 35       | 4.55%   |
| SAS  | 3        | 0.39%   |
| SCSI | 3        | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 286      | 55.21%  |
| AMD    | 232      | 44.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 21       | 4.05%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 12       | 2.31%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 12       | 2.31%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 11       | 2.12%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 10       | 1.93%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 9        | 1.73%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 8        | 1.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 8        | 1.54%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 8        | 1.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 8        | 1.54%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 8        | 1.54%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 8        | 1.54%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 7        | 1.35%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 7        | 1.35%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 7        | 1.35%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 6        | 1.16%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 6        | 1.16%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 6        | 1.16%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 6        | 1.16%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 5        | 0.96%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 5        | 0.96%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 5        | 0.96%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 5        | 0.96%   |
| Intel Core i9-9900K CPU @ 3.60GHz               | 4        | 0.77%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 4        | 0.77%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 4        | 0.77%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 4        | 0.77%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 4        | 0.77%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 4        | 0.77%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 4        | 0.77%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 4        | 0.77%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 4        | 0.77%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 4        | 0.77%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 4        | 0.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 4        | 0.77%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 4        | 0.77%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 4        | 0.77%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz             | 3        | 0.58%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 3        | 0.58%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 3        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 86       | 16.6%   |
| Intel Core i7           | 82       | 15.83%  |
| AMD Ryzen 5             | 79       | 15.25%  |
| AMD Ryzen 7             | 38       | 7.34%   |
| AMD Ryzen 9             | 34       | 6.56%   |
| Intel Core i3           | 30       | 5.79%   |
| Intel Xeon              | 28       | 5.41%   |
| AMD Ryzen 3             | 15       | 2.9%    |
| AMD FX                  | 13       | 2.51%   |
| AMD Ryzen Threadripper  | 11       | 2.12%   |
| Intel Core 2 Duo        | 10       | 1.93%   |
| Intel Pentium           | 9        | 1.74%   |
| Intel Core i9           | 8        | 1.54%   |
| Intel Core 2 Quad       | 8        | 1.54%   |
| AMD A10                 | 8        | 1.54%   |
| Intel Pentium Dual-Core | 6        | 1.16%   |
| Intel Celeron           | 6        | 1.16%   |
| Other                   | 5        | 0.97%   |
| AMD Phenom II X2        | 4        | 0.77%   |
| AMD Athlon 64 X2        | 4        | 0.77%   |
| AMD Ryzen 7 PRO         | 3        | 0.58%   |
| AMD Athlon Dual Core    | 3        | 0.58%   |
| AMD A6                  | 3        | 0.58%   |
| Intel Pentium D         | 2        | 0.39%   |
| Intel Core 2            | 2        | 0.39%   |
| Intel Atom              | 2        | 0.39%   |
| AMD Ryzen 5 PRO         | 2        | 0.39%   |
| AMD Phenom II X6        | 2        | 0.39%   |
| AMD Phenom II X4        | 2        | 0.39%   |
| AMD Athlon II X2        | 2        | 0.39%   |
| AMD Athlon              | 2        | 0.39%   |
| AMD A8                  | 2        | 0.39%   |
| Intel Pentium Dual      | 1        | 0.19%   |
| Intel Pentium 4         | 1        | 0.19%   |
| AMD E2                  | 1        | 0.19%   |
| AMD E                   | 1        | 0.19%   |
| AMD Athlon X2           | 1        | 0.19%   |
| AMD Athlon II X4        | 1        | 0.19%   |
| AMD A4                  | 1        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 190      | 36.61%  |
| 6      | 115      | 22.16%  |
| 2      | 89       | 17.15%  |
| 8      | 67       | 12.91%  |
| 12     | 24       | 4.62%   |
| 16     | 19       | 3.66%   |
| 1      | 5        | 0.96%   |
| 32     | 4        | 0.77%   |
| 3      | 3        | 0.58%   |
| 10     | 2        | 0.39%   |
| 24     | 1        | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 511      | 98.65%  |
| 2      | 7        | 1.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 342      | 65.77%  |
| 1      | 178      | 34.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 518      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 47       | 9%      |
| 0x306c3    | 45       | 8.62%   |
| 0x506e3    | 30       | 5.75%   |
| Unknown    | 29       | 5.56%   |
| 0x306a9    | 24       | 4.6%    |
| 0x906ea    | 23       | 4.41%   |
| 0x0800820d | 22       | 4.21%   |
| 0x906e9    | 21       | 4.02%   |
| 0x206a7    | 21       | 4.02%   |
| 0x0a201009 | 21       | 4.02%   |
| 0x1067a    | 20       | 3.83%   |
| 0x08701013 | 15       | 2.87%   |
| 0x906ed    | 12       | 2.3%    |
| 0xa0655    | 10       | 1.92%   |
| 0x0a201016 | 10       | 1.92%   |
| 0x08108109 | 10       | 1.92%   |
| 0x08001138 | 8        | 1.53%   |
| 0x106e5    | 7        | 1.34%   |
| 0x08001137 | 7        | 1.34%   |
| 0x06003106 | 7        | 1.34%   |
| 0x08101016 | 6        | 1.15%   |
| 0xa0671    | 5        | 0.96%   |
| 0x906ec    | 5        | 0.96%   |
| 0x306f2    | 5        | 0.96%   |
| 0x106a5    | 5        | 0.96%   |
| 0x0810100b | 5        | 0.96%   |
| 0xa0653    | 4        | 0.77%   |
| 0x906eb    | 4        | 0.77%   |
| 0x0a50000c | 4        | 0.77%   |
| 0x06000822 | 4        | 0.77%   |
| 0x6f6      | 3        | 0.57%   |
| 0x306e4    | 3        | 0.57%   |
| 0x206d7    | 3        | 0.57%   |
| 0x10676    | 3        | 0.57%   |
| 0x08600103 | 3        | 0.57%   |
| 0x08301039 | 3        | 0.57%   |
| 0x0800820b | 3        | 0.57%   |
| 0x06001119 | 3        | 0.57%   |
| 0x06000817 | 3        | 0.57%   |
| 0x010000c8 | 3        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 73       | 14.09%  |
| KabyLake      | 71       | 13.71%  |
| Haswell       | 54       | 10.42%  |
| Zen+          | 42       | 8.11%   |
| Zen 3         | 35       | 6.76%   |
| Zen           | 33       | 6.37%   |
| Skylake       | 33       | 6.37%   |
| IvyBridge     | 28       | 5.41%   |
| Penryn        | 25       | 4.83%   |
| SandyBridge   | 24       | 4.63%   |
| CometLake     | 15       | 2.9%    |
| Piledriver    | 14       | 2.7%    |
| Nehalem       | 13       | 2.51%   |
| K10           | 12       | 2.32%   |
| Steamroller   | 7        | 1.35%   |
| K8 Hammer     | 7        | 1.35%   |
| Core          | 6        | 1.16%   |
| Icelake       | 5        | 0.97%   |
| NetBurst      | 4        | 0.77%   |
| Excavator     | 3        | 0.58%   |
| Westmere      | 2        | 0.39%   |
| Bulldozer     | 2        | 0.39%   |
| Broadwell     | 2        | 0.39%   |
| Bonnell       | 2        | 0.39%   |
| Silvermont    | 1        | 0.19%   |
| Puma          | 1        | 0.19%   |
| K10 Llano     | 1        | 0.19%   |
| Jaguar        | 1        | 0.19%   |
| Goldmont plus | 1        | 0.19%   |
| Bobcat        | 1        | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 236      | 41.55%  |
| AMD                        | 202      | 35.56%  |
| Intel                      | 128      | 22.54%  |
| Matrox Electronics Systems | 1        | 0.18%   |
| ASPEED Technology          | 1        | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 45       | 7.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 23       | 3.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21       | 3.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 21       | 3.63%   |
| Intel HD Graphics 530                                                       | 16       | 2.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13       | 2.25%   |
| Nvidia GK208B [GeForce GT 710]                                              | 13       | 2.25%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 12       | 2.07%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12       | 2.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12       | 2.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11       | 1.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 1.73%   |
| Intel HD Graphics 630                                                       | 10       | 1.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10       | 1.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 9        | 1.55%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 8        | 1.38%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 1.21%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.21%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 7        | 1.21%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 7        | 1.21%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 7        | 1.21%   |
| AMD Renoir                                                                  | 7        | 1.21%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 7        | 1.21%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 1.04%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.04%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 1.04%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 5        | 0.86%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 5        | 0.86%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 5        | 0.86%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 5        | 0.86%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 0.86%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 5        | 0.86%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5        | 0.86%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 0.86%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.69%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 4        | 0.69%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.69%   |
| Nvidia GF108 [GeForce GT 730]                                               | 4        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 210      | 40%     |
| 1 x AMD        | 186      | 35.43%  |
| 1 x Intel      | 90       | 17.14%  |
| Intel + Nvidia | 17       | 3.24%   |
| 2 x Nvidia     | 6        | 1.14%   |
| 2 x AMD        | 6        | 1.14%   |
| AMD + Nvidia   | 5        | 0.95%   |
| Intel + AMD    | 2        | 0.38%   |
| Other          | 1        | 0.19%   |
| 1 x Matrox     | 1        | 0.19%   |
| 1 x ASPEED     | 1        | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 381      | 72.43%  |
| Proprietary | 131      | 24.9%   |
| Unknown     | 14       | 2.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 173      | 32.52%  |
| 7.01-8.0   | 79       | 14.85%  |
| 1.01-2.0   | 75       | 14.1%   |
| 3.01-4.0   | 60       | 11.28%  |
| 0.51-1.0   | 57       | 10.71%  |
| 0.01-0.5   | 33       | 6.2%    |
| 5.01-6.0   | 26       | 4.89%   |
| 8.01-16.0  | 22       | 4.14%   |
| 2.01-3.0   | 6        | 1.13%   |
| 16.01-24.0 | 1        | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 92       | 15.11%  |
| Samsung Electronics  | 88       | 14.45%  |
| Dell                 | 74       | 12.15%  |
| Acer                 | 42       | 6.9%    |
| BenQ                 | 38       | 6.24%   |
| Hewlett-Packard      | 33       | 5.42%   |
| AOC                  | 32       | 5.25%   |
| Philips              | 25       | 4.11%   |
| Iiyama               | 25       | 4.11%   |
| Ancor Communications | 24       | 3.94%   |
| ViewSonic            | 12       | 1.97%   |
| Lenovo               | 12       | 1.97%   |
| ASUSTek Computer     | 10       | 1.64%   |
| Sony                 | 7        | 1.15%   |
| Sceptre Tech         | 7        | 1.15%   |
| ___                  | 6        | 0.99%   |
| Unknown              | 6        | 0.99%   |
| NEC Computers        | 5        | 0.82%   |
| MSI                  | 5        | 0.82%   |
| Eizo                 | 5        | 0.82%   |
| Vizio                | 4        | 0.66%   |
| Vestel Elektronik    | 3        | 0.49%   |
| Insignia             | 3        | 0.49%   |
| Unknown (XXX)        | 2        | 0.33%   |
| Toshiba              | 2        | 0.33%   |
| NEW                  | 2        | 0.33%   |
| Mitsubishi           | 2        | 0.33%   |
| Mi                   | 2        | 0.33%   |
| HannStar             | 2        | 0.33%   |
| Gigabyte Technology  | 2        | 0.33%   |
| eMachines            | 2        | 0.33%   |
| Element              | 2        | 0.33%   |
| Zoran                | 1        | 0.16%   |
| Wacom                | 1        | 0.16%   |
| SHX                  | 1        | 0.16%   |
| SAC                  | 1        | 0.16%   |
| RIS                  | 1        | 0.16%   |
| RGT                  | 1        | 0.16%   |
| Razer                | 1        | 0.16%   |
| Positivo             | 1        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 8        | 1.21%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 6        | 0.9%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 5        | 0.75%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                 | 5        | 0.75%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                   | 4        | 0.6%    |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch            | 4        | 0.6%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 4        | 0.6%    |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 4        | 0.6%    |
| ___ LCDTV16 ___9000 1360x768                                           | 3        | 0.45%   |
| ___ LCDTV16 ___0101 1920x1080                                          | 3        | 0.45%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch   | 3        | 0.45%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                    | 3        | 0.45%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch         | 3        | 0.45%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 3        | 0.45%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch      | 3        | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 3        | 0.45%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 3        | 0.45%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 0.45%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 3        | 0.45%   |
| Goldstar W2442 GSM56D9 1920x1080 531x299mm 24.0-inch                   | 3        | 0.45%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                     | 3        | 0.45%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 3        | 0.45%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                      | 3        | 0.45%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                       | 3        | 0.45%   |
| AOC 2757 AOC2757 1920x1080 598x336mm 27.0-inch                         | 3        | 0.45%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 2        | 0.3%    |
| Sony TV SNYE903 1920x1080                                              | 2        | 0.3%    |
| Sceptre Tech E27 SPT0ABF 1920x1080 521x293mm 23.5-inch                 | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM043F 1920x1200 518x324mm 24.1-inch   | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch    | 2        | 0.3%    |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 0.3%    |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 2        | 0.3%    |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch     | 2        | 0.3%    |
| Samsung Electronics C27HG7x SAM0E16 2560x1440 600x340mm 27.2-inch      | 2        | 0.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 2        | 0.3%    |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 2        | 0.3%    |
| Mitsubishi RDT234WLM MEL4887 1920x1080 509x286mm 23.0-inch             | 2        | 0.3%    |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch              | 2        | 0.3%    |
| Lenovo LEN L1711pC LEN13B7 1280x1024 360x300mm 18.4-inch               | 2        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 276      | 47.34%  |
| 3840x2160 (4K)     | 67       | 11.49%  |
| 2560x1440 (QHD)    | 67       | 11.49%  |
| 1920x1200 (WUXGA)  | 22       | 3.77%   |
| 1280x1024 (SXGA)   | 22       | 3.77%   |
| 1366x768 (WXGA)    | 21       | 3.6%    |
| 2560x1080          | 19       | 3.26%   |
| 1440x900 (WXGA+)   | 17       | 2.92%   |
| 1680x1050 (WSXGA+) | 14       | 2.4%    |
| 1360x768           | 10       | 1.72%   |
| 3840x1080          | 9        | 1.54%   |
| 3440x1440          | 9        | 1.54%   |
| 1600x900 (HD+)     | 9        | 1.54%   |
| Unknown            | 5        | 0.86%   |
| 1024x768 (XGA)     | 4        | 0.69%   |
| 2048x1152          | 3        | 0.51%   |
| 1600x1200          | 2        | 0.34%   |
| 7680x1440          | 1        | 0.17%   |
| 7120x1080          | 1        | 0.17%   |
| 2560x1600          | 1        | 0.17%   |
| 2288x1287          | 1        | 0.17%   |
| 1920x540           | 1        | 0.17%   |
| 1280x960           | 1        | 0.17%   |
| 1280x720 (HD)      | 1        | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 123      | 20.2%   |
| 24      | 113      | 18.56%  |
| 21      | 78       | 12.81%  |
| 23      | 67       | 11%     |
| 19      | 31       | 5.09%   |
| 34      | 27       | 4.43%   |
| 31      | 23       | 3.78%   |
| 18      | 23       | 3.78%   |
| Unknown | 16       | 2.63%   |
| 72      | 15       | 2.46%   |
| 22      | 11       | 1.81%   |
| 20      | 10       | 1.64%   |
| 15      | 9        | 1.48%   |
| 48      | 8        | 1.31%   |
| 32      | 8        | 1.31%   |
| 84      | 6        | 0.99%   |
| 17      | 6        | 0.99%   |
| 28      | 5        | 0.82%   |
| 25      | 5        | 0.82%   |
| 54      | 3        | 0.49%   |
| 49      | 2        | 0.33%   |
| 42      | 2        | 0.33%   |
| 40      | 2        | 0.33%   |
| 26      | 2        | 0.33%   |
| 16      | 2        | 0.33%   |
| 13      | 2        | 0.33%   |
| 69      | 1        | 0.16%   |
| 64      | 1        | 0.16%   |
| 50      | 1        | 0.16%   |
| 46      | 1        | 0.16%   |
| 43      | 1        | 0.16%   |
| 38      | 1        | 0.16%   |
| 36      | 1        | 0.16%   |
| 33      | 1        | 0.16%   |
| 30      | 1        | 0.16%   |
| 14      | 1        | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 270      | 46.71%  |
| 401-500     | 127      | 21.97%  |
| 601-700     | 42       | 7.27%   |
| 701-800     | 37       | 6.4%    |
| 351-400     | 25       | 4.33%   |
| 1501-2000   | 22       | 3.81%   |
| 1001-1500   | 16       | 2.77%   |
| Unknown     | 16       | 2.77%   |
| 301-350     | 15       | 2.6%    |
| 801-900     | 3        | 0.52%   |
| 901-1000    | 3        | 0.52%   |
| 201-300     | 2        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 400      | 74.49%  |
| 16/10   | 54       | 10.06%  |
| 21/9    | 28       | 5.21%   |
| 5/4     | 22       | 4.1%    |
| Unknown | 10       | 1.86%   |
| 4/3     | 9        | 1.68%   |
| 32/9    | 7        | 1.3%    |
| 6/5     | 3        | 0.56%   |
| 3/2     | 3        | 0.56%   |
| 1.96    | 1        | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 202      | 33.84%  |
| 301-350        | 124      | 20.77%  |
| 151-200        | 67       | 11.22%  |
| 351-500        | 64       | 10.72%  |
| 251-300        | 42       | 7.04%   |
| More than 1000 | 28       | 4.69%   |
| 141-150        | 20       | 3.35%   |
| 501-1000       | 16       | 2.68%   |
| Unknown        | 16       | 2.68%   |
| 101-110        | 7        | 1.17%   |
| 131-140        | 4        | 0.67%   |
| 91-100         | 3        | 0.5%    |
| 81-90          | 2        | 0.34%   |
| 121-130        | 1        | 0.17%   |
| 111-120        | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 330      | 57.89%  |
| 101-120 | 148      | 25.96%  |
| 121-160 | 36       | 6.32%   |
| 1-50    | 25       | 4.39%   |
| Unknown | 16       | 2.81%   |
| 161-240 | 15       | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 361      | 68.37%  |
| 2     | 130      | 24.62%  |
| 0     | 19       | 3.6%    |
| 3     | 18       | 3.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 303      | 40.13%  |
| Intel                           | 279      | 36.95%  |
| Qualcomm Atheros                | 42       | 5.56%   |
| Broadcom                        | 19       | 2.52%   |
| Ralink Technology               | 16       | 2.12%   |
| TP-Link                         | 12       | 1.59%   |
| Aquantia                        | 12       | 1.59%   |
| Nvidia                          | 6        | 0.79%   |
| Ralink                          | 5        | 0.66%   |
| Xiaomi                          | 4        | 0.53%   |
| Qualcomm Atheros Communications | 4        | 0.53%   |
| NetGear                         | 4        | 0.53%   |
| Marvell Technology Group        | 4        | 0.53%   |
| D-Link System                   | 4        | 0.53%   |
| Broadcom Limited                | 4        | 0.53%   |
| Microsoft                       | 3        | 0.4%    |
| Huawei Technologies             | 3        | 0.4%    |
| ASUSTek Computer                | 3        | 0.4%    |
| Motorola PCS                    | 2        | 0.26%   |
| Linksys                         | 2        | 0.26%   |
| ICS Advent                      | 2        | 0.26%   |
| Arduino SA                      | 2        | 0.26%   |
| Apple                           | 2        | 0.26%   |
| ADMtek                          | 2        | 0.26%   |
| Wilocity                        | 1        | 0.13%   |
| Qualcomm                        | 1        | 0.13%   |
| OPPO Electronics                | 1        | 0.13%   |
| Oculus VR                       | 1        | 0.13%   |
| Microchip Technology            | 1        | 0.13%   |
| Mellanox Technologies           | 1        | 0.13%   |
| MediaTek                        | 1        | 0.13%   |
| InterBiometrics                 | 1        | 0.13%   |
| INGENICO                        | 1        | 0.13%   |
| IMC Networks                    | 1        | 0.13%   |
| Google                          | 1        | 0.13%   |
| DisplayLink                     | 1        | 0.13%   |
| D-Link                          | 1        | 0.13%   |
| ASIX Electronics                | 1        | 0.13%   |
| Adafruit                        | 1        | 0.13%   |
| Accton Technology               | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 231      | 25.38%  |
| Intel Wi-Fi 6 AX200                                                           | 77       | 8.46%   |
| Intel I211 Gigabit Network Connection                                         | 69       | 7.58%   |
| Realtek RTL8125 2.5GbE Controller                                             | 38       | 4.18%   |
| Intel Ethernet Connection (2) I219-V                                          | 34       | 3.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 22       | 2.42%   |
| Intel Wireless-AC 9260                                                        | 16       | 1.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 15       | 1.65%   |
| Intel Ethernet Connection (7) I219-V                                          | 14       | 1.54%   |
| Intel Ethernet Controller I225-V                                              | 13       | 1.43%   |
| Intel Ethernet Connection (2) I218-V                                          | 12       | 1.32%   |
| Intel Ethernet Connection I217-LM                                             | 11       | 1.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 1.1%    |
| Intel Wireless 8260                                                           | 10       | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 9        | 0.99%   |
| Intel Wireless 7260                                                           | 8        | 0.88%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 8        | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 7        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7        | 0.77%   |
| Intel 82574L Gigabit Network Connection                                       | 7        | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 6        | 0.66%   |
| Intel Ethernet Connection I217-V                                              | 6        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 6        | 0.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 6        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 5        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 5        | 0.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 5        | 0.55%   |
| Ralink MT7601U Wireless Adapter                                               | 5        | 0.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 5        | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.44%   |
| Ralink RT5370 Wireless Adapter                                                | 4        | 0.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 4        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 4        | 0.44%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 0.44%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 0.44%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.44%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 4        | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 3        | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 151      | 53.17%  |
| Realtek Semiconductor           | 45       | 15.85%  |
| Qualcomm Atheros                | 23       | 8.1%    |
| Ralink Technology               | 16       | 5.63%   |
| TP-Link                         | 12       | 4.23%   |
| Broadcom                        | 10       | 3.52%   |
| Ralink                          | 5        | 1.76%   |
| Qualcomm Atheros Communications | 4        | 1.41%   |
| NetGear                         | 4        | 1.41%   |
| Microsoft                       | 3        | 1.06%   |
| ASUSTek Computer                | 3        | 1.06%   |
| Linksys                         | 2        | 0.7%    |
| Xiaomi                          | 1        | 0.35%   |
| Wilocity                        | 1        | 0.35%   |
| MediaTek                        | 1        | 0.35%   |
| IMC Networks                    | 1        | 0.35%   |
| D-Link System                   | 1        | 0.35%   |
| Broadcom Limited                | 1        | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 77       | 27.02%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 22       | 7.72%   |
| Intel Wireless-AC 9260                                                 | 16       | 5.61%   |
| Intel Wireless 8260                                                    | 10       | 3.51%   |
| Intel Wireless 7260                                                    | 8        | 2.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7        | 2.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6        | 2.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 6        | 2.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5        | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 5        | 1.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 5        | 1.75%   |
| Ralink MT7601U Wireless Adapter                                        | 5        | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5        | 1.75%   |
| Ralink RT5370 Wireless Adapter                                         | 4        | 1.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 4        | 1.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 3        | 1.05%   |
| TP-Link Archer T4U ver.3                                               | 3        | 1.05%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 3        | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3        | 1.05%   |
| Realtek 802.11ac NIC                                                   | 3        | 1.05%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                      | 3        | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3        | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 3        | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3        | 1.05%   |
| NetGear A6210                                                          | 3        | 1.05%   |
| Intel Wireless 8265 / 8275                                             | 3        | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 3        | 1.05%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 3        | 1.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 2        | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.7%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 2        | 0.7%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                        | 2        | 0.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 2        | 0.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2        | 0.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2        | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 0.7%    |
| Microsoft XBOX ACC                                                     | 2        | 0.7%    |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 2        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 2        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 285      | 49.05%  |
| Intel                    | 213      | 36.66%  |
| Qualcomm Atheros         | 24       | 4.13%   |
| Aquantia                 | 12       | 2.07%   |
| Broadcom                 | 10       | 1.72%   |
| Nvidia                   | 6        | 1.03%   |
| Marvell Technology Group | 4        | 0.69%   |
| Xiaomi                   | 3        | 0.52%   |
| D-Link System            | 3        | 0.52%   |
| Broadcom Limited         | 3        | 0.52%   |
| Motorola PCS             | 2        | 0.34%   |
| ICS Advent               | 2        | 0.34%   |
| Huawei Technologies      | 2        | 0.34%   |
| Apple                    | 2        | 0.34%   |
| ADMtek                   | 2        | 0.34%   |
| Qualcomm                 | 1        | 0.17%   |
| OPPO Electronics         | 1        | 0.17%   |
| Mellanox Technologies    | 1        | 0.17%   |
| Google                   | 1        | 0.17%   |
| DisplayLink              | 1        | 0.17%   |
| D-Link                   | 1        | 0.17%   |
| ASIX Electronics         | 1        | 0.17%   |
| Accton Technology        | 1        | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 231      | 37.44%  |
| Intel I211 Gigabit Network Connection                                         | 69       | 11.18%  |
| Realtek RTL8125 2.5GbE Controller                                             | 38       | 6.16%   |
| Intel Ethernet Connection (2) I219-V                                          | 34       | 5.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 15       | 2.43%   |
| Intel Ethernet Connection (7) I219-V                                          | 14       | 2.27%   |
| Intel Ethernet Controller I225-V                                              | 13       | 2.11%   |
| Intel Ethernet Connection (2) I218-V                                          | 12       | 1.94%   |
| Intel Ethernet Connection I217-LM                                             | 11       | 1.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 9        | 1.46%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 8        | 1.3%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7        | 1.13%   |
| Intel 82574L Gigabit Network Connection                                       | 7        | 1.13%   |
| Intel Ethernet Connection I217-V                                              | 6        | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 0.97%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 6        | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 4        | 0.65%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 0.65%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.65%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 4        | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 3        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 3        | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 0.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.49%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 3        | 0.49%   |
| Intel Ethernet Connection (12) I219-V                                         | 3        | 0.49%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.32%   |
| Nvidia MCP77 Ethernet                                                         | 2        | 0.32%   |
| Nvidia MCP61 Ethernet                                                         | 2        | 0.32%   |
| Motorola PCS moto g(9) play                                                   | 2        | 0.32%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.32%   |
| Huawei STK-L21                                                                | 2        | 0.32%   |
| D-Link System RTL8139 Ethernet                                                | 2        | 0.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.32%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                       | 2        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 513      | 65.85%  |
| WiFi     | 258      | 33.12%  |
| Modem    | 8        | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 411      | 75.14%  |
| WiFi     | 136      | 24.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 264      | 50.57%  |
| 2     | 198      | 37.93%  |
| 3     | 47       | 9%      |
| 4     | 6        | 1.15%   |
| 5     | 4        | 0.77%   |
| 0     | 2        | 0.38%   |
| 9     | 1        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 399      | 76%     |
| Yes  | 126      | 24%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 142      | 59.66%  |
| Cambridge Silicon Radio         | 43       | 18.07%  |
| Broadcom                        | 15       | 6.3%    |
| ASUSTek Computer                | 13       | 5.46%   |
| Realtek Semiconductor           | 7        | 2.94%   |
| Qualcomm Atheros Communications | 5        | 2.1%    |
| IMC Networks                    | 5        | 2.1%    |
| Apple                           | 3        | 1.26%   |
| Lite-On Technology              | 1        | 0.42%   |
| Hewlett-Packard                 | 1        | 0.42%   |
| Edimax Technology               | 1        | 0.42%   |
| Dynex                           | 1        | 0.42%   |
| D-Link System                   | 1        | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                    | 71       | 29.83%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 43       | 18.07%  |
| Intel Wireless-AC 3168 Bluetooth                         | 22       | 9.24%   |
| Intel Bluetooth wireless interface                       | 20       | 8.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 17       | 7.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 12       | 5.04%   |
| Realtek Bluetooth Radio                                  | 5        | 2.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 5        | 2.1%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 4        | 1.68%   |
| ASUS Bluetooth Radio                                     | 4        | 1.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 3        | 1.26%   |
| Intel AX210 Bluetooth                                    | 3        | 1.26%   |
| Intel AX201 Bluetooth                                    | 3        | 1.26%   |
| IMC Networks Bluetooth Device                            | 3        | 1.26%   |
| Apple Bluetooth USB Host Controller                      | 3        | 1.26%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 0.84%   |
| Broadcom BCM2045 Bluetooth                               | 2        | 0.84%   |
| ASUS Bluetooth Device                                    | 2        | 0.84%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 0.42%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.42%   |
| Lite-On Bluetooth Device                                 | 1        | 0.42%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.42%   |
| IMC Networks Bluetooth Radio                             | 1        | 0.42%   |
| IMC Networks Bluetooth Module                            | 1        | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 1        | 0.42%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter  | 1        | 0.42%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.42%   |
| D-Link System DBT-122 Bluetooth                          | 1        | 0.42%   |
| Broadcom HP Portable Bumble Bee                          | 1        | 0.42%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 0.42%   |
| ASUS Bluetooth Adapter                                   | 1        | 0.42%   |
| ASUS BCM20702A0                                          | 1        | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 279      | 29.15%  |
| Intel                      | 276      | 28.84%  |
| Nvidia                     | 229      | 23.93%  |
| C-Media Electronics        | 29       | 3.03%   |
| Logitech                   | 17       | 1.78%   |
| Creative Technology        | 11       | 1.15%   |
| Focusrite-Novation         | 8        | 0.84%   |
| Creative Labs              | 8        | 0.84%   |
| Kingston Technology        | 7        | 0.73%   |
| Blue Microphones           | 7        | 0.73%   |
| Generalplus Technology     | 6        | 0.63%   |
| Corsair                    | 6        | 0.63%   |
| SteelSeries ApS            | 5        | 0.52%   |
| Razer USA                  | 4        | 0.42%   |
| Plantronics                | 4        | 0.42%   |
| GYROCOM C&C                | 4        | 0.42%   |
| Samson Technologies        | 3        | 0.31%   |
| RODE Microphones           | 3        | 0.31%   |
| GN Netcom                  | 3        | 0.31%   |
| ASUSTek Computer           | 3        | 0.31%   |
| ULi Electronics            | 2        | 0.21%   |
| Texas Instruments          | 2        | 0.21%   |
| Tenx Technology            | 2        | 0.21%   |
| Schiit Audio               | 2        | 0.21%   |
| JMTek                      | 2        | 0.21%   |
| JBL                        | 2        | 0.21%   |
| Giga-Byte Technology       | 2        | 0.21%   |
| EGO SYStems                | 2        | 0.21%   |
| Cambridge Silicon Radio    | 2        | 0.21%   |
| Yamaha                     | 1        | 0.1%    |
| Xilinx                     | 1        | 0.1%    |
| VIA Technologies           | 1        | 0.1%    |
| Unknown (ABC)              | 1        | 0.1%    |
| Unknown                    | 1        | 0.1%    |
| Thermaltake                | 1        | 0.1%    |
| Sony                       | 1        | 0.1%    |
| Shenzhen Riitek Technology | 1        | 0.1%    |
| SAVITECH                   | 1        | 0.1%    |
| Realtek Semiconductor      | 1        | 0.1%    |
| PreSonus Audio Electronics | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 95       | 8.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 48       | 4.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 46       | 4.1%    |
| Intel 200 Series PCH HD Audio                                              | 42       | 3.74%   |
| AMD Family 17h/19h HD Audio Controller                                     | 36       | 3.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 35       | 3.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 29       | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 29       | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 24       | 2.14%   |
| AMD Navi 10 HDMI Audio                                                     | 24       | 2.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 23       | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23       | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 22       | 1.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 22       | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 21       | 1.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 20       | 1.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 20       | 1.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 19       | 1.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18       | 1.6%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 17       | 1.51%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 16       | 1.42%   |
| Nvidia TU116 High Definition Audio Controller                              | 15       | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                              | 13       | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                              | 13       | 1.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13       | 1.16%   |
| AMD FCH Azalia Controller                                                  | 13       | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11       | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10       | 0.89%   |
| Nvidia TU104 HD Audio Controller                                           | 9        | 0.8%    |
| Nvidia High Definition Audio Controller                                    | 9        | 0.8%    |
| Nvidia GM204 High Definition Audio Controller                              | 9        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 0.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9        | 0.8%    |
| Intel Comet Lake PCH-V cAVS                                                | 8        | 0.71%   |
| C-Media Electronics USB Audio Device                                       | 8        | 0.71%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8        | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                              | 7        | 0.62%   |
| Nvidia GM206 High Definition Audio Controller                              | 7        | 0.62%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 0.62%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 7        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 56       | 18.92%  |
| Corsair                      | 50       | 16.89%  |
| G.Skill                      | 46       | 15.54%  |
| Unknown                      | 31       | 10.47%  |
| Samsung Electronics          | 28       | 9.46%   |
| Crucial                      | 24       | 8.11%   |
| SK hynix                     | 21       | 7.09%   |
| Micron Technology            | 12       | 4.05%   |
| Patriot                      | 3        | 1.01%   |
| GOODRAM                      | 3        | 1.01%   |
| Elpida                       | 3        | 1.01%   |
| A-DATA Technology            | 3        | 1.01%   |
| Team                         | 2        | 0.68%   |
| Ramaxel Technology           | 2        | 0.68%   |
| GeIL                         | 2        | 0.68%   |
| V-Color                      | 1        | 0.34%   |
| Unknown (0xF7F7F7F7F7F7E300) | 1        | 0.34%   |
| Transcend                    | 1        | 0.34%   |
| Teikon                       | 1        | 0.34%   |
| Smart                        | 1        | 0.34%   |
| Silicon Power                | 1        | 0.34%   |
| Rahonix                      | 1        | 0.34%   |
| pqi                          | 1        | 0.34%   |
| Nanya Technology             | 1        | 0.34%   |
| Apacer                       | 1        | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 4        | 1.23%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 4        | 1.23%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s    | 4        | 1.23%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 3        | 0.92%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 3        | 0.92%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s        | 3        | 0.92%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 3        | 0.92%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s   | 3        | 0.92%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 3        | 0.92%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 3        | 0.92%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 3        | 0.92%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s    | 3        | 0.92%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 3        | 0.92%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 3        | 0.92%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3200MT/s   | 3        | 0.92%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 2        | 0.62%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 2        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                | 2        | 0.62%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                  | 2        | 0.62%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.62%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.62%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s      | 2        | 0.62%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 2        | 0.62%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s               | 2        | 0.62%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s     | 2        | 0.62%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 0.62%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s     | 2        | 0.62%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s      | 2        | 0.62%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s        | 2        | 0.62%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3600MT/s    | 2        | 0.62%   |
| G.Skill RAM F4-3600C19-16GVRB 16GB DIMM DDR4 3600MT/s    | 2        | 0.62%   |
| G.Skill RAM F4-3600C18-16GVK 16GB DIMM DDR4 3733MT/s     | 2        | 0.62%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 2        | 0.62%   |
| G.Skill RAM F4-3200C16-8GTZB 8GB DIMM DDR4 3200MT/s      | 2        | 0.62%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s   | 2        | 0.62%   |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4 3733MT/s | 2        | 0.62%   |
| Corsair RAM CMT64GX4M4E3200C16 16GB DIMM DDR4 3200MT/s   | 2        | 0.62%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 2        | 0.62%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 2        | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 161      | 61.92%  |
| DDR3    | 69       | 26.54%  |
| DDR2    | 11       | 4.23%   |
| Unknown | 10       | 3.85%   |
| SDRAM   | 4        | 1.54%   |
| DDR     | 4        | 1.54%   |
| LPDDR3  | 1        | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 243      | 93.82%  |
| SODIMM       | 14       | 5.41%   |
| Row Of Chips | 1        | 0.39%   |
| RIMM         | 1        | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 109      | 38.52%  |
| 16384 | 63       | 22.26%  |
| 4096  | 58       | 20.49%  |
| 2048  | 34       | 12.01%  |
| 32768 | 12       | 4.24%   |
| 1024  | 6        | 2.12%   |
| 512   | 1        | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 44       | 15.02%  |
| 3200    | 43       | 14.68%  |
| 3600    | 23       | 7.85%   |
| 1333    | 20       | 6.83%   |
| 2400    | 19       | 6.48%   |
| 2133    | 15       | 5.12%   |
| 2667    | 12       | 4.1%    |
| 3733    | 11       | 3.75%   |
| 3400    | 11       | 3.75%   |
| 3000    | 8        | 2.73%   |
| 3466    | 7        | 2.39%   |
| 667     | 7        | 2.39%   |
| 3800    | 6        | 2.05%   |
| 2800    | 6        | 2.05%   |
| 1867    | 6        | 2.05%   |
| 3866    | 5        | 1.71%   |
| 1866    | 5        | 1.71%   |
| 1067    | 5        | 1.71%   |
| Unknown | 5        | 1.71%   |
| 800     | 4        | 1.37%   |
| 2666    | 3        | 1.02%   |
| 1800    | 3        | 1.02%   |
| 333     | 3        | 1.02%   |
| 2933    | 2        | 0.68%   |
| 1334    | 2        | 0.68%   |
| 1066    | 2        | 0.68%   |
| 49926   | 1        | 0.34%   |
| 4000    | 1        | 0.34%   |
| 3666    | 1        | 0.34%   |
| 3533    | 1        | 0.34%   |
| 3467    | 1        | 0.34%   |
| 3334    | 1        | 0.34%   |
| 3100    | 1        | 0.34%   |
| 3066    | 1        | 0.34%   |
| 2934    | 1        | 0.34%   |
| 2866    | 1        | 0.34%   |
| 2134    | 1        | 0.34%   |
| 2132    | 1        | 0.34%   |
| 2000    | 1        | 0.34%   |
| 975     | 1        | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 13       | 41.94%  |
| Brother Industries  | 7        | 22.58%  |
| Seiko Epson         | 2        | 6.45%   |
| Canon               | 2        | 6.45%   |
| Xerox               | 1        | 3.23%   |
| Star Micronics      | 1        | 3.23%   |
| Samsung Electronics | 1        | 3.23%   |
| Prolific Technology | 1        | 3.23%   |
| Dymo-CoStar         | 1        | 3.23%   |
| Dell                | 1        | 3.23%   |
| Boca Systems        | 1        | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| HP OfficeJet 6950                            | 2        | 6.45%   |
| HP DeskJet 2620 All-in-One Printer           | 2        | 6.45%   |
| Xerox Phaser 3010                            | 1        | 3.23%   |
| Star Micronics TUP592 (STR_T-001)            | 1        | 3.23%   |
| Seiko Epson PX-045A Series                   | 1        | 3.23%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 3.23%   |
| Samsung M2070 Series                         | 1        | 3.23%   |
| Prolific PL2305 Parallel Port                | 1        | 3.23%   |
| HP Neverstop Laser 100x                      | 1        | 3.23%   |
| HP LaserJet Professional P 1102w             | 1        | 3.23%   |
| HP LaserJet P1006                            | 1        | 3.23%   |
| HP Ink Tank 310 series                       | 1        | 3.23%   |
| HP EWS UPD                                   | 1        | 3.23%   |
| HP ENVY 5000 series                          | 1        | 3.23%   |
| HP DeskJet F4100 Printer series              | 1        | 3.23%   |
| HP Deskjet D2500 series                      | 1        | 3.23%   |
| HP DeskJet 4530 series                       | 1        | 3.23%   |
| Dymo-CoStar DYMO LabelWriter 4XL             | 1        | 3.23%   |
| Dell B1160w Mono Laser Printer               | 1        | 3.23%   |
| Canon PIXMA MP270 All-In-One Printer         | 1        | 3.23%   |
| Canon CanoScan LiDE 300                      | 1        | 3.23%   |
| Brother Printer                              | 1        | 3.23%   |
| Brother MFC-9330CDW                          | 1        | 3.23%   |
| Brother MFC-9325CW                           | 1        | 3.23%   |
| Brother HL-L2340D series                     | 1        | 3.23%   |
| Brother HL-1430 Laser Printer                | 1        | 3.23%   |
| Brother DCP-7040                             | 1        | 3.23%   |
| Brother DCP-7030                             | 1        | 3.23%   |
| Boca Systems FGL46 Thermal Printer           | 1        | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 6        | 54.55%  |
| Seiko Epson     | 4        | 36.36%  |
| Hewlett-Packard | 1        | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1        | 9.09%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 9.09%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 9.09%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]             | 1        | 9.09%   |
| HP ScanJet G4050                                        | 1        | 9.09%   |
| Canon CanoScan N1240U/LiDE 30                           | 1        | 9.09%   |
| Canon CanoScan LiDE 70                                  | 1        | 9.09%   |
| Canon CanoScan LIDE 25                                  | 1        | 9.09%   |
| Canon CanoScan LiDE 220                                 | 1        | 9.09%   |
| Canon CanoScan LiDE 210                                 | 1        | 9.09%   |
| Canon CanoScan 4400F                                    | 1        | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 66       | 45.83%  |
| Microsoft                     | 10       | 6.94%   |
| Sunplus Innovation Technology | 6        | 4.17%   |
| Realtek Semiconductor         | 6        | 4.17%   |
| Microdia                      | 6        | 4.17%   |
| Samsung Electronics           | 4        | 2.78%   |
| HD 2MP WEBCAM                 | 4        | 2.78%   |
| Jieli Technology              | 3        | 2.08%   |
| AVerMedia Technologies        | 3        | 2.08%   |
| ARC International             | 3        | 2.08%   |
| Z-Star Microelectronics       | 2        | 1.39%   |
| YGTek                         | 2        | 1.39%   |
| Unknown                       | 2        | 1.39%   |
| Trust                         | 2        | 1.39%   |
| Razer USA                     | 2        | 1.39%   |
| Generalplus Technology        | 2        | 1.39%   |
| Creative Technology           | 2        | 1.39%   |
| Apple                         | 2        | 1.39%   |
| Alcor Micro                   | 2        | 1.39%   |
| WN-5693-210616                | 1        | 0.69%   |
| SunplusIT                     | 1        | 0.69%   |
| Sony                          | 1        | 0.69%   |
| Owl Labs                      | 1        | 0.69%   |
| OmniVision Technologies       | 1        | 0.69%   |
| MacroSilicon                  | 1        | 0.69%   |
| LG Electronics                | 1        | 0.69%   |
| Lenovo                        | 1        | 0.69%   |
| KYE Systems (Mouse Systems)   | 1        | 0.69%   |
| INOGENI                       | 1        | 0.69%   |
| Huawei Technologies           | 1        | 0.69%   |
| Hewlett-Packard               | 1        | 0.69%   |
| Chicony Electronics           | 1        | 0.69%   |
| BUFFALO                       | 1        | 0.69%   |
| Alcorlink                     | 1        | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 22       | 14.86%  |
| Logitech HD Pro Webcam C920              | 11       | 7.43%   |
| Logitech HD Webcam C525                  | 6        | 4.05%   |
| Samsung Galaxy A5 (MTP)                  | 4        | 2.7%    |
| Microsoft LifeCam Cinema                 | 4        | 2.7%    |
| Logitech Webcam C925e                    | 4        | 2.7%    |
| HD 2MP WEBCAM HD 2MP WEBCAM              | 4        | 2.7%    |
| Microdia Webcam Vitade AF                | 3        | 2.03%   |
| Logitech StreamCam                       | 3        | 2.03%   |
| Logitech HD Webcam C615                  | 3        | 2.03%   |
| Logitech C922 Pro Stream Webcam          | 3        | 2.03%   |
| Logitech BRIO Ultra HD Webcam            | 3        | 2.03%   |
| Jieli USB PHY 2.0                        | 3        | 2.03%   |
| ARC International Camera                 | 3        | 2.03%   |
| YGTek Webcam                             | 2        | 1.35%   |
| Sunplus HD 720P webcam                   | 2        | 1.35%   |
| Realtek USB Camera                       | 2        | 1.35%   |
| Realtek Full HD webcam                   | 2        | 1.35%   |
| Razer USA Gaming Webcam [Kiyo]           | 2        | 1.35%   |
| Microsoft LifeCam HD-3000                | 2        | 1.35%   |
| Microdia USB 2.0 Camera                  | 2        | 1.35%   |
| Logitech Webcam C930e                    | 2        | 1.35%   |
| Logitech Webcam C170                     | 2        | 1.35%   |
| Logitech QuickCam Pro for Notebooks      | 2        | 1.35%   |
| Logitech QuickCam E 3500                 | 2        | 1.35%   |
| Generalplus 808 Camera #9 (web-cam mode) | 2        | 1.35%   |
| Creative Live! Cam Sync 1080p            | 2        | 1.35%   |
| Apple iPhone5/5C/5S/6                    | 2        | 1.35%   |
| Alcor Micro USB 2.0 PC Camera            | 2        | 1.35%   |
| Z-Star Venus USB2.0 Camera               | 1        | 0.68%   |
| Z-Star A4 TECH USB2.0 PC Camera J        | 1        | 0.68%   |
| WN-5693-210616 BBA USB CAMERA            | 1        | 0.68%   |
| Unknown HD Camera                        | 1        | 0.68%   |
| Unknown HD 720P                          | 1        | 0.68%   |
| Trust Widescreen 3MP Webcam              | 1        | 0.68%   |
| Trust USB Camera                         | 1        | 0.68%   |
| SunplusIT MTD camera                     | 1        | 0.68%   |
| Sunplus NexiGo N930AF FHD Webcam         | 1        | 0.68%   |
| Sunplus MYPIN HD Capture                 | 1        | 0.68%   |
| Sunplus ezcap U3 capture-04              | 1        | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 50%     |
| OmniKey               | 1        | 25%     |
| Cherry                | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 50%     |
| OmniKey CardMan 3021 / 3121                       | 1        | 25%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC       | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 462      | 87.83%  |
| 1     | 58       | 11.03%  |
| 2     | 6        | 1.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 20       | 30.77%  |
| Graphics card            | 17       | 26.15%  |
| Unassigned class         | 9        | 13.85%  |
| Sound                    | 3        | 4.62%   |
| Multimedia controller    | 3        | 4.62%   |
| Communication controller | 3        | 4.62%   |
| Camera                   | 3        | 4.62%   |
| Bluetooth                | 2        | 3.08%   |
| Network                  | 1        | 1.54%   |
| Net/ethernet             | 1        | 1.54%   |
| Fingerprint reader       | 1        | 1.54%   |
| Dvb card                 | 1        | 1.54%   |
| Card reader              | 1        | 1.54%   |


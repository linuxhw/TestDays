Linux in Austria - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Austria.

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

Total: 1038

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Clevo         | Modified by dsanke          | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | [e18983e0d8](https://linux-hardware.org/?probe=e18983e0d8) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | [d59ef2842d](https://linux-hardware.org/?probe=d59ef2842d) | Jun 21, 2022 |
| Razer         | Blade 15 Advanced Model ... | [de5d975c12](https://linux-hardware.org/?probe=de5d975c12) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [bfc7b65dee](https://linux-hardware.org/?probe=bfc7b65dee) | Jun 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eb60cda77f](https://linux-hardware.org/?probe=eb60cda77f) | Jun 18, 2022 |
| HP            | EliteBook 8460p             | [e19c095325](https://linux-hardware.org/?probe=e19c095325) | Jun 18, 2022 |
| Acer          | Aspire A515-44G             | [f07dc47259](https://linux-hardware.org/?probe=f07dc47259) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6db07f5434](https://linux-hardware.org/?probe=6db07f5434) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c637722355](https://linux-hardware.org/?probe=c637722355) | Jun 11, 2022 |
| Valve         | Jupiter                     | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Lenovo        | ThinkPad X220 4291IR6       | [958f8bb25b](https://linux-hardware.org/?probe=958f8bb25b) | Jun 09, 2022 |
| HP            | ProBook 450 G6              | [898eff4fae](https://linux-hardware.org/?probe=898eff4fae) | Jun 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b2f7663fc9](https://linux-hardware.org/?probe=b2f7663fc9) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [39bb0fa0c5](https://linux-hardware.org/?probe=39bb0fa0c5) | Jun 07, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [5ad950659b](https://linux-hardware.org/?probe=5ad950659b) | Jun 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [24da0cf09c](https://linux-hardware.org/?probe=24da0cf09c) | Jun 06, 2022 |
| Acer          | Swift SFX14-41G             | [38fb3963cd](https://linux-hardware.org/?probe=38fb3963cd) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | [6f5f1c9373](https://linux-hardware.org/?probe=6f5f1c9373) | Jun 01, 2022 |
| Dell          | Latitude 5520               | [03622600a8](https://linux-hardware.org/?probe=03622600a8) | May 30, 2022 |
| Dell          | Latitude E6410              | [72345f9352](https://linux-hardware.org/?probe=72345f9352) | May 28, 2022 |
| HP            | ProBook 470 G4              | [6049c10c3c](https://linux-hardware.org/?probe=6049c10c3c) | May 28, 2022 |
| System76      | Lemur Pro                   | [dcfd3abdd6](https://linux-hardware.org/?probe=dcfd3abdd6) | May 26, 2022 |
| Valve         | Jupiter                     | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1RS0... | [174f6e2270](https://linux-hardware.org/?probe=174f6e2270) | May 23, 2022 |
| Dell          | Latitude E6410              | [39be06dd23](https://linux-hardware.org/?probe=39be06dd23) | May 19, 2022 |
| Acer          | Extensa 2509                | [46df59d8b3](https://linux-hardware.org/?probe=46df59d8b3) | May 19, 2022 |
| Acer          | Aspire A515-51G             | [9a945a6cf5](https://linux-hardware.org/?probe=9a945a6cf5) | May 17, 2022 |
| Apple         | MacBookPro5,4               | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [b28d047360](https://linux-hardware.org/?probe=b28d047360) | May 14, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [36ccfac84d](https://linux-hardware.org/?probe=36ccfac84d) | May 14, 2022 |
| Valve         | Jupiter                     | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [d3d6871bf7](https://linux-hardware.org/?probe=d3d6871bf7) | May 12, 2022 |
| Dell          | Latitude 5520               | [927a4b0ed0](https://linux-hardware.org/?probe=927a4b0ed0) | May 12, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [17dda821a0](https://linux-hardware.org/?probe=17dda821a0) | May 11, 2022 |
| Apple         | MacBook1,1                  | [399e291a66](https://linux-hardware.org/?probe=399e291a66) | May 09, 2022 |
| Dell          | XPS 13 9310                 | [d95a50c16a](https://linux-hardware.org/?probe=d95a50c16a) | May 09, 2022 |
| Dell          | Latitude E6430              | [a6b570e125](https://linux-hardware.org/?probe=a6b570e125) | May 08, 2022 |
| HP            | 255 G8 Notebook PC          | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [8fda480b12](https://linux-hardware.org/?probe=8fda480b12) | May 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1U60... | [ffafca2b97](https://linux-hardware.org/?probe=ffafca2b97) | May 06, 2022 |
| HP            | ZBook 17 G5                 | [5190bc7cf3](https://linux-hardware.org/?probe=5190bc7cf3) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | [0bc5a5fb9f](https://linux-hardware.org/?probe=0bc5a5fb9f) | May 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| Sony          | VPCEH2J1E                   | [86f6b8c750](https://linux-hardware.org/?probe=86f6b8c750) | Apr 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9f5c24d3e8](https://linux-hardware.org/?probe=9f5c24d3e8) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [da73d0b77d](https://linux-hardware.org/?probe=da73d0b77d) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [2b7f66b701](https://linux-hardware.org/?probe=2b7f66b701) | Apr 26, 2022 |
| Fujitsu       | LIFEBOOK E751               | [ace84bb1e5](https://linux-hardware.org/?probe=ace84bb1e5) | Apr 25, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [a8038d3972](https://linux-hardware.org/?probe=a8038d3972) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bbc4928d39](https://linux-hardware.org/?probe=bbc4928d39) | Apr 19, 2022 |
| Apple         | MacBookPro9,2               | [812afb255a](https://linux-hardware.org/?probe=812afb255a) | Apr 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [b228a9bf01](https://linux-hardware.org/?probe=b228a9bf01) | Apr 15, 2022 |
| Notebook      | NJ50_70CU                   | [1ec86958b8](https://linux-hardware.org/?probe=1ec86958b8) | Apr 15, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c68c62f98c](https://linux-hardware.org/?probe=c68c62f98c) | Apr 14, 2022 |
| Medion        | X6816                       | [41350ad402](https://linux-hardware.org/?probe=41350ad402) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | [ac82d62350](https://linux-hardware.org/?probe=ac82d62350) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | [60a1fc5c39](https://linux-hardware.org/?probe=60a1fc5c39) | Apr 12, 2022 |
| TUXEDO        | P65xHP                      | [a29da5ce79](https://linux-hardware.org/?probe=a29da5ce79) | Apr 11, 2022 |
| Acer          | Aspire A114-31              | [8779ba2891](https://linux-hardware.org/?probe=8779ba2891) | Apr 09, 2022 |
| Acer          | Aspire A114-31              | [298acab48c](https://linux-hardware.org/?probe=298acab48c) | Apr 08, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [0b5e11625d](https://linux-hardware.org/?probe=0b5e11625d) | Apr 08, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fed3e90b10](https://linux-hardware.org/?probe=fed3e90b10) | Apr 08, 2022 |
| HP            | Pavilion dv6                | [b69de03677](https://linux-hardware.org/?probe=b69de03677) | Apr 06, 2022 |
| HP            | Pavilion dv6                | [9e8312e9c1](https://linux-hardware.org/?probe=9e8312e9c1) | Apr 06, 2022 |
| Dell          | XPS 13 9305                 | [0e254bc578](https://linux-hardware.org/?probe=0e254bc578) | Apr 05, 2022 |
| Medion        | E7216                       | [58f12f9e91](https://linux-hardware.org/?probe=58f12f9e91) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [edf4c472c3](https://linux-hardware.org/?probe=edf4c472c3) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [35e0c67fed](https://linux-hardware.org/?probe=35e0c67fed) | Apr 03, 2022 |
| Acer          | TravelMate 7730             | [c0c1bedcec](https://linux-hardware.org/?probe=c0c1bedcec) | Apr 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [869407eb01](https://linux-hardware.org/?probe=869407eb01) | Apr 03, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [26082e6921](https://linux-hardware.org/?probe=26082e6921) | Apr 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [0f191252cb](https://linux-hardware.org/?probe=0f191252cb) | Apr 02, 2022 |
| MSI           | Bravo 17 A4DDR              | [590d188f5d](https://linux-hardware.org/?probe=590d188f5d) | Apr 01, 2022 |
| VALE          | Notebook Slim S132          | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Acer          | TravelMate 7730             | [6cabffccbe](https://linux-hardware.org/?probe=6cabffccbe) | Mar 30, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Notebook      | NJ50_70CU                   | [ba5b62756b](https://linux-hardware.org/?probe=ba5b62756b) | Mar 29, 2022 |
| Sony          | VPCEH2J1E                   | [23d5b99aca](https://linux-hardware.org/?probe=23d5b99aca) | Mar 27, 2022 |
| Acer          | Nitro AN515-45              | [c6fa89e81f](https://linux-hardware.org/?probe=c6fa89e81f) | Mar 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [76b97dcfe7](https://linux-hardware.org/?probe=76b97dcfe7) | Mar 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [ec3089df82](https://linux-hardware.org/?probe=ec3089df82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| ASUSTek       | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| HP            | Pavilion dv7                | [64d5f14244](https://linux-hardware.org/?probe=64d5f14244) | Mar 22, 2022 |
| HP            | Pavilion dv7                | [e2bfdae482](https://linux-hardware.org/?probe=e2bfdae482) | Mar 22, 2022 |
| MSI           | Modern 14 B10MW             | [e8bbca6adf](https://linux-hardware.org/?probe=e8bbca6adf) | Mar 21, 2022 |
| Fujitsu Si... | AMILO Pro Edition V3545     | [be2c23f4a5](https://linux-hardware.org/?probe=be2c23f4a5) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Medion        | E14410                      | [800f98d1ef](https://linux-hardware.org/?probe=800f98d1ef) | Mar 21, 2022 |
| Sony          | VPCEH2J1E                   | [ae54fc4033](https://linux-hardware.org/?probe=ae54fc4033) | Mar 19, 2022 |
| ASUSTek       | X201EP                      | [864fc80ac3](https://linux-hardware.org/?probe=864fc80ac3) | Mar 17, 2022 |
| MSI           | Alpha 15 B5EEK              | [f4c72eaa35](https://linux-hardware.org/?probe=f4c72eaa35) | Mar 15, 2022 |
| MSI           | Alpha 15 B5EEK              | [8859888f0c](https://linux-hardware.org/?probe=8859888f0c) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | [1aa06e7b53](https://linux-hardware.org/?probe=1aa06e7b53) | Mar 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e2eacd6969](https://linux-hardware.org/?probe=e2eacd6969) | Mar 12, 2022 |
| Lenovo        | ThinkPad E15 20RES12P00     | [200b3a0b69](https://linux-hardware.org/?probe=200b3a0b69) | Mar 12, 2022 |
| ASUSTek       | UX303LAB                    | [f3d0e8fbea](https://linux-hardware.org/?probe=f3d0e8fbea) | Mar 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [adf7b6c95e](https://linux-hardware.org/?probe=adf7b6c95e) | Mar 10, 2022 |
| ASUSTek       | UX305FA                     | [f1641a436c](https://linux-hardware.org/?probe=f1641a436c) | Mar 09, 2022 |
| Dell          | Vostro 5471                 | [6e46455791](https://linux-hardware.org/?probe=6e46455791) | Mar 09, 2022 |
| Sony          | VPCEH2J1E                   | [713f08757a](https://linux-hardware.org/?probe=713f08757a) | Mar 09, 2022 |
| HP            | EliteBook 850 G1            | [b2aeea55e5](https://linux-hardware.org/?probe=b2aeea55e5) | Mar 07, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| HP            | Pavilion g6                 | [e9b1f4c1ec](https://linux-hardware.org/?probe=e9b1f4c1ec) | Mar 03, 2022 |
| HP            | Pavilion g6                 | [f378d8a1df](https://linux-hardware.org/?probe=f378d8a1df) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [359368d345](https://linux-hardware.org/?probe=359368d345) | Feb 26, 2022 |
| Toshiba       | Satellite L775-166          | [f0ad0a4da5](https://linux-hardware.org/?probe=f0ad0a4da5) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [16281a52e8](https://linux-hardware.org/?probe=16281a52e8) | Feb 26, 2022 |
| Toshiba       | Satellite P500              | [980cb1d4af](https://linux-hardware.org/?probe=980cb1d4af) | Feb 25, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [6bf461797c](https://linux-hardware.org/?probe=6bf461797c) | Feb 25, 2022 |
| HP            | ZBook 15 G3                 | [7b9e3082bf](https://linux-hardware.org/?probe=7b9e3082bf) | Feb 25, 2022 |
| HP            | EliteBook 820 G1            | [916b00f114](https://linux-hardware.org/?probe=916b00f114) | Feb 24, 2022 |
| Lenovo        | IdeaPad S206 2638           | [84772cc34d](https://linux-hardware.org/?probe=84772cc34d) | Feb 23, 2022 |
| HP            | EliteBook 6930p             | [82000c3346](https://linux-hardware.org/?probe=82000c3346) | Feb 22, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| Acer          | Aspire A517-51              | [997108b078](https://linux-hardware.org/?probe=997108b078) | Feb 19, 2022 |
| Acer          | Aspire E1-572G              | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| HP            | EliteBook 840 G1            | [3047069a4f](https://linux-hardware.org/?probe=3047069a4f) | Feb 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [934591472d](https://linux-hardware.org/?probe=934591472d) | Feb 16, 2022 |
| Dell          | XPS 15 9550                 | [701eeea0ed](https://linux-hardware.org/?probe=701eeea0ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [32022a8232](https://linux-hardware.org/?probe=32022a8232) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [372c231b58](https://linux-hardware.org/?probe=372c231b58) | Feb 14, 2022 |
| Acer          | Swift SF114-34              | [31d020671e](https://linux-hardware.org/?probe=31d020671e) | Feb 13, 2022 |
| Lenovo        | ThinkPad X230T 34382AG      | [bec561800f](https://linux-hardware.org/?probe=bec561800f) | Feb 13, 2022 |
| HP            | ProBook 4730s               | [2a3ff15659](https://linux-hardware.org/?probe=2a3ff15659) | Feb 12, 2022 |
| HP            | Compaq 15                   | [78b2f3bfa6](https://linux-hardware.org/?probe=78b2f3bfa6) | Feb 11, 2022 |
| Acer          | Aspire A315-54              | [d4e5b617c7](https://linux-hardware.org/?probe=d4e5b617c7) | Feb 10, 2022 |
| Fujitsu       | LIFEBOOK E559               | [66696218c1](https://linux-hardware.org/?probe=66696218c1) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK S751               | [42d5c28f38](https://linux-hardware.org/?probe=42d5c28f38) | Feb 09, 2022 |
| Medion        | P6402 MD60800               | [a749ba246d](https://linux-hardware.org/?probe=a749ba246d) | Feb 08, 2022 |
| HP            | ProBook 450 G2              | [57c513ecbc](https://linux-hardware.org/?probe=57c513ecbc) | Feb 08, 2022 |
| Acer          | Predator G9-792             | [8404f2e6d1](https://linux-hardware.org/?probe=8404f2e6d1) | Feb 08, 2022 |
| HP            | EliteBook 840 G3            | [82d892f3e5](https://linux-hardware.org/?probe=82d892f3e5) | Feb 07, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | [8337edfc91](https://linux-hardware.org/?probe=8337edfc91) | Feb 07, 2022 |
| Acer          | TravelMate 5720             | [9db7cd9351](https://linux-hardware.org/?probe=9db7cd9351) | Feb 06, 2022 |
| Chuwi         | HeroBook Pro                | [9f5da53181](https://linux-hardware.org/?probe=9f5da53181) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Acer          | Swift SF314-54              | [d11fb8c7b6](https://linux-hardware.org/?probe=d11fb8c7b6) | Feb 04, 2022 |
| Acer          | Aspire A114-31              | [caa9365785](https://linux-hardware.org/?probe=caa9365785) | Feb 04, 2022 |
| Sony          | VPCEH2J1E                   | [f5ed0cbaa4](https://linux-hardware.org/?probe=f5ed0cbaa4) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5a1723f28e](https://linux-hardware.org/?probe=5a1723f28e) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [7db46606ab](https://linux-hardware.org/?probe=7db46606ab) | Feb 04, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [376503f06d](https://linux-hardware.org/?probe=376503f06d) | Feb 03, 2022 |
| HP            | ProBook 4310s               | [6d2a66aa1e](https://linux-hardware.org/?probe=6d2a66aa1e) | Feb 02, 2022 |
| Lenovo        | ThinkPad X280 20KF001GGE    | [f076061f22](https://linux-hardware.org/?probe=f076061f22) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| Acer          | Aspire E1-571G              | [440bc30637](https://linux-hardware.org/?probe=440bc30637) | Jan 31, 2022 |
| Acer          | Aspire E1-571G              | [dd2d541140](https://linux-hardware.org/?probe=dd2d541140) | Jan 31, 2022 |
| Dell          | XPS M1530                   | [4b402569cc](https://linux-hardware.org/?probe=4b402569cc) | Jan 29, 2022 |
| Acer          | Predator G9-792             | [863bce4abe](https://linux-hardware.org/?probe=863bce4abe) | Jan 28, 2022 |
| Apple         | MacBookPro9,2               | [d112bf0361](https://linux-hardware.org/?probe=d112bf0361) | Jan 27, 2022 |
| Dell          | Precision 5510              | [511eeac9a0](https://linux-hardware.org/?probe=511eeac9a0) | Jan 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5edb2eb3](https://linux-hardware.org/?probe=4d5edb2eb3) | Jan 25, 2022 |
| Lenovo        | ThinkPad T495 20NJS0KB00    | [e92c44b58a](https://linux-hardware.org/?probe=e92c44b58a) | Jan 24, 2022 |
| Dell          | Inspiron 1720               | [0b6d89660a](https://linux-hardware.org/?probe=0b6d89660a) | Jan 24, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | [46a5cef815](https://linux-hardware.org/?probe=46a5cef815) | Jan 23, 2022 |
| Lenovo        | ThinkPad T560 20FJS2PN00    | [e9f3d5c785](https://linux-hardware.org/?probe=e9f3d5c785) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| Razer         | Blade Stealth 13 Late 20... | [e19ee364b0](https://linux-hardware.org/?probe=e19ee364b0) | Jan 21, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [a0399b1c6b](https://linux-hardware.org/?probe=a0399b1c6b) | Jan 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0410ba28b0](https://linux-hardware.org/?probe=0410ba28b0) | Jan 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [24c10d9f2d](https://linux-hardware.org/?probe=24c10d9f2d) | Jan 20, 2022 |
| Acer          | Nitro AN515-44              | [f45a7eb0bb](https://linux-hardware.org/?probe=f45a7eb0bb) | Jan 20, 2022 |
| Acer          | Swift SF114-34              | [7ea8fc4686](https://linux-hardware.org/?probe=7ea8fc4686) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [5ba89b6e26](https://linux-hardware.org/?probe=5ba89b6e26) | Jan 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fca800793f](https://linux-hardware.org/?probe=fca800793f) | Jan 18, 2022 |
| Lenovo        | ThinkPad T560 20FJS2PN00    | [11340212f2](https://linux-hardware.org/?probe=11340212f2) | Jan 18, 2022 |
| Acer          | Aspire ES1-531              | [d089029f6c](https://linux-hardware.org/?probe=d089029f6c) | Jan 18, 2022 |
| Dell          | XPS 15 9570                 | [b8d4a9ee87](https://linux-hardware.org/?probe=b8d4a9ee87) | Jan 17, 2022 |
| Lenovo        | ThinkPad X230 2325WR3       | [decbecce89](https://linux-hardware.org/?probe=decbecce89) | Jan 16, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [dd69f44bab](https://linux-hardware.org/?probe=dd69f44bab) | Jan 15, 2022 |
| ASUSTek       | K52JT                       | [8545fedf93](https://linux-hardware.org/?probe=8545fedf93) | Jan 14, 2022 |
| Medion        | CRAWLER E10                 | [d658e7cd88](https://linux-hardware.org/?probe=d658e7cd88) | Jan 13, 2022 |
| HP            | EliteBook 1030 G1           | [73839f5dd5](https://linux-hardware.org/?probe=73839f5dd5) | Jan 09, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [f212038b15](https://linux-hardware.org/?probe=f212038b15) | Jan 09, 2022 |
| HP            | Compaq 8510p                | [94c5350957](https://linux-hardware.org/?probe=94c5350957) | Jan 09, 2022 |
| ASUSTek       | K52JT                       | [c5d880e138](https://linux-hardware.org/?probe=c5d880e138) | Jan 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [dc436bb38c](https://linux-hardware.org/?probe=dc436bb38c) | Jan 08, 2022 |
| HP            | Laptop 15-db1xxx            | [28db094e56](https://linux-hardware.org/?probe=28db094e56) | Jan 08, 2022 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [2dbdfe4883](https://linux-hardware.org/?probe=2dbdfe4883) | Jan 08, 2022 |
| Dell          | Vostro 5370                 | [0d027d4b84](https://linux-hardware.org/?probe=0d027d4b84) | Jan 07, 2022 |
| Dell          | Precision 5510              | [7a763a42bb](https://linux-hardware.org/?probe=7a763a42bb) | Jan 07, 2022 |
| HP            | Laptop 17-ak0xx             | [fee6068743](https://linux-hardware.org/?probe=fee6068743) | Jan 05, 2022 |
| Dell          | Latitude E6520              | [f9c32b0bee](https://linux-hardware.org/?probe=f9c32b0bee) | Jan 05, 2022 |
| Dell          | Latitude E7440              | [c8811522dd](https://linux-hardware.org/?probe=c8811522dd) | Jan 05, 2022 |
| Dell          | Latitude E5550              | [8956b15ec8](https://linux-hardware.org/?probe=8956b15ec8) | Jan 04, 2022 |
| HP            | EliteBook 8540p             | [a321b2cfd9](https://linux-hardware.org/?probe=a321b2cfd9) | Jan 03, 2022 |
| HP            | EliteBook 8540p             | [6130b11204](https://linux-hardware.org/?probe=6130b11204) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| TUXEDO        | P65_67HSHP                  | [4d448637c0](https://linux-hardware.org/?probe=4d448637c0) | Jan 02, 2022 |
| ASUSTek       | N50Vn                       | [8fadb8c7af](https://linux-hardware.org/?probe=8fadb8c7af) | Jan 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS05V0... | [7c496e685d](https://linux-hardware.org/?probe=7c496e685d) | Dec 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [5095c47f07](https://linux-hardware.org/?probe=5095c47f07) | Dec 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [1724d0d357](https://linux-hardware.org/?probe=1724d0d357) | Dec 26, 2021 |
| HP            | ProBook 470 G1              | [0e99096fe2](https://linux-hardware.org/?probe=0e99096fe2) | Dec 26, 2021 |
| Dell          | Inspiron 3505               | [fe87929ac5](https://linux-hardware.org/?probe=fe87929ac5) | Dec 26, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [cb2ae92d82](https://linux-hardware.org/?probe=cb2ae92d82) | Dec 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [492fc37142](https://linux-hardware.org/?probe=492fc37142) | Dec 22, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [d7f3d69923](https://linux-hardware.org/?probe=d7f3d69923) | Dec 21, 2021 |
| HP            | EliteBook 8460p             | [59ec7afd71](https://linux-hardware.org/?probe=59ec7afd71) | Dec 20, 2021 |
| ASUSTek       | GL702ZC                     | [ff27d21705](https://linux-hardware.org/?probe=ff27d21705) | Dec 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [a8713c0bd9](https://linux-hardware.org/?probe=a8713c0bd9) | Dec 18, 2021 |
| MSI           | Modern 14 B10MW             | [1771ceeb4e](https://linux-hardware.org/?probe=1771ceeb4e) | Dec 14, 2021 |
| Dell          | XPS 17 9700                 | [eef9ef9d60](https://linux-hardware.org/?probe=eef9ef9d60) | Dec 12, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [c33bc12a7a](https://linux-hardware.org/?probe=c33bc12a7a) | Dec 11, 2021 |
| Dell          | XPS 17 9700                 | [d5ec843ea7](https://linux-hardware.org/?probe=d5ec843ea7) | Dec 11, 2021 |
| Toshiba       | Satellite L500              | [aaab078915](https://linux-hardware.org/?probe=aaab078915) | Dec 11, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [ec9930ae99](https://linux-hardware.org/?probe=ec9930ae99) | Dec 11, 2021 |
| HP            | ZBook Firefly 15 inch G8... | [f2bfaaf185](https://linux-hardware.org/?probe=f2bfaaf185) | Dec 11, 2021 |
| Dell          | XPS M1530                   | [ad4bfb0cbd](https://linux-hardware.org/?probe=ad4bfb0cbd) | Dec 08, 2021 |
| HP            | Pavilion dv6                | [9dd21ffaf4](https://linux-hardware.org/?probe=9dd21ffaf4) | Dec 08, 2021 |
| Medion        | P7624                       | [05d0f23734](https://linux-hardware.org/?probe=05d0f23734) | Dec 08, 2021 |
| Unknown       | Unknown                     | [9e9e0598b6](https://linux-hardware.org/?probe=9e9e0598b6) | Dec 07, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [600faccbe5](https://linux-hardware.org/?probe=600faccbe5) | Dec 07, 2021 |
| ASUSTek       | T100HAN                     | [9ad6409a34](https://linux-hardware.org/?probe=9ad6409a34) | Dec 06, 2021 |
| Dell          | Vostro 5471                 | [0d989a4f1f](https://linux-hardware.org/?probe=0d989a4f1f) | Dec 05, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Sony          | SVF1532Z1EB                 | [d65626b69d](https://linux-hardware.org/?probe=d65626b69d) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | [cd254ead05](https://linux-hardware.org/?probe=cd254ead05) | Dec 04, 2021 |
| HP            | ProBook 470 G1              | [4359617795](https://linux-hardware.org/?probe=4359617795) | Dec 03, 2021 |
| Lenovo        | ThinkPad Edge E330 33549... | [d8c1e34c94](https://linux-hardware.org/?probe=d8c1e34c94) | Dec 02, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [6204315459](https://linux-hardware.org/?probe=6204315459) | Dec 02, 2021 |
| HP            | Pavilion dv6                | [640e1f0491](https://linux-hardware.org/?probe=640e1f0491) | Dec 01, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [d77b252a78](https://linux-hardware.org/?probe=d77b252a78) | Dec 01, 2021 |
| Acer          | Swift SF314-42              | [c77012b538](https://linux-hardware.org/?probe=c77012b538) | Nov 30, 2021 |
| HP            | 625                         | [75b1dd3ee1](https://linux-hardware.org/?probe=75b1dd3ee1) | Nov 29, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Medion        | P15648                      | [1328e63002](https://linux-hardware.org/?probe=1328e63002) | Nov 25, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [5632c40eac](https://linux-hardware.org/?probe=5632c40eac) | Nov 24, 2021 |
| HP            | Pavilion g7                 | [c8b8a8bed7](https://linux-hardware.org/?probe=c8b8a8bed7) | Nov 24, 2021 |
| HP            | Pavilion g7                 | [fab49120f0](https://linux-hardware.org/?probe=fab49120f0) | Nov 23, 2021 |
| HP            | ProBook 455 G8 Notebook ... | [56cd58b089](https://linux-hardware.org/?probe=56cd58b089) | Nov 23, 2021 |
| ASUSTek       | X751SA                      | [d19fd8c59f](https://linux-hardware.org/?probe=d19fd8c59f) | Nov 22, 2021 |
| MSI           | GF72 7RE                    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| HP            | ENVY 15                     | [f4752615c9](https://linux-hardware.org/?probe=f4752615c9) | Nov 19, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | [73b9b15b14](https://linux-hardware.org/?probe=73b9b15b14) | Nov 19, 2021 |
| Lenovo        | ThinkPad P50 20EQS15P00     | [4c9b03387c](https://linux-hardware.org/?probe=4c9b03387c) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [915853adf6](https://linux-hardware.org/?probe=915853adf6) | Nov 18, 2021 |
| HP            | Laptop 15-db1xxx            | [cd32f937e9](https://linux-hardware.org/?probe=cd32f937e9) | Nov 17, 2021 |
| Acer          | Aspire 7750G                | [79eb5a8344](https://linux-hardware.org/?probe=79eb5a8344) | Nov 16, 2021 |
| Dell          | Vostro 5471                 | [348b6bc909](https://linux-hardware.org/?probe=348b6bc909) | Nov 16, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [1976dd6a72](https://linux-hardware.org/?probe=1976dd6a72) | Nov 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [039fb54354](https://linux-hardware.org/?probe=039fb54354) | Nov 12, 2021 |
| HP            | Laptop 15-db1xxx            | [c34d10b1c8](https://linux-hardware.org/?probe=c34d10b1c8) | Nov 12, 2021 |
| Sony          | VPCEH2J1E                   | [02a4a3ea01](https://linux-hardware.org/?probe=02a4a3ea01) | Nov 06, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f0d8cb68f0](https://linux-hardware.org/?probe=f0d8cb68f0) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [f4273d4dc1](https://linux-hardware.org/?probe=f4273d4dc1) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [86f7bd9873](https://linux-hardware.org/?probe=86f7bd9873) | Nov 06, 2021 |
| Lenovo        | G500s 20245                 | [e16940fe24](https://linux-hardware.org/?probe=e16940fe24) | Nov 05, 2021 |
| Medion        | E6220                       | [45d5f5ec30](https://linux-hardware.org/?probe=45d5f5ec30) | Nov 04, 2021 |
| ASUSTek       | X580VD                      | [2970522382](https://linux-hardware.org/?probe=2970522382) | Nov 01, 2021 |
| Panasonic     | FZG1-3                      | [8a52b831d7](https://linux-hardware.org/?probe=8a52b831d7) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ba228b1ed7](https://linux-hardware.org/?probe=ba228b1ed7) | Oct 31, 2021 |
| Medion        | Akoya S4220 MD99660         | [fd406382b2](https://linux-hardware.org/?probe=fd406382b2) | Oct 30, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0c865ddf24](https://linux-hardware.org/?probe=0c865ddf24) | Oct 30, 2021 |
| Dell          | Latitude 5490               | [4efdbaeea5](https://linux-hardware.org/?probe=4efdbaeea5) | Oct 30, 2021 |
| Acer          | Aspire A317-33              | [ad0f3b8799](https://linux-hardware.org/?probe=ad0f3b8799) | Oct 24, 2021 |
| Acer          | TravelMate P253             | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Medion        | E7216                       | [f4c7def4b7](https://linux-hardware.org/?probe=f4c7def4b7) | Oct 24, 2021 |
| Medion        | P7624                       | [efc2ccc6a2](https://linux-hardware.org/?probe=efc2ccc6a2) | Oct 24, 2021 |
| HP            | ProBook 430 G5              | [6954277377](https://linux-hardware.org/?probe=6954277377) | Oct 23, 2021 |
| MSI           | Modern 14 B10MW             | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| Lenovo        | ThinkPad T440s 20AQS0090... | [415cc7fe56](https://linux-hardware.org/?probe=415cc7fe56) | Oct 18, 2021 |
| HP            | Pavilion dv6                | [0392f507d0](https://linux-hardware.org/?probe=0392f507d0) | Oct 18, 2021 |
| HP            | Laptop 14s-fq1xxx           | [61d5829888](https://linux-hardware.org/?probe=61d5829888) | Oct 14, 2021 |
| HP            | Laptop 14s-fq1xxx           | [c42ff576c7](https://linux-hardware.org/?probe=c42ff576c7) | Oct 14, 2021 |
| Acer          | Aspire A515-51G             | [7555392d34](https://linux-hardware.org/?probe=7555392d34) | Oct 14, 2021 |
| Medion        | P15648                      | [5ea319450e](https://linux-hardware.org/?probe=5ea319450e) | Oct 13, 2021 |
| HP            | Laptop 14s-fq1xxx           | [1e047e7a9a](https://linux-hardware.org/?probe=1e047e7a9a) | Oct 12, 2021 |
| ASUSTek       | N61Jv                       | [0e300bafe8](https://linux-hardware.org/?probe=0e300bafe8) | Oct 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [037a558c7d](https://linux-hardware.org/?probe=037a558c7d) | Oct 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [1984f59bbe](https://linux-hardware.org/?probe=1984f59bbe) | Oct 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [a631c78255](https://linux-hardware.org/?probe=a631c78255) | Oct 09, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [b6715f92f7](https://linux-hardware.org/?probe=b6715f92f7) | Oct 08, 2021 |
| Dell          | Latitude E5550              | [a4f8896675](https://linux-hardware.org/?probe=a4f8896675) | Oct 07, 2021 |
| Medion        | E6415 MD99904               | [4b24e7fb1a](https://linux-hardware.org/?probe=4b24e7fb1a) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [572e073021](https://linux-hardware.org/?probe=572e073021) | Oct 04, 2021 |
| ASUSTek       | X556UQK                     | [363c1a3642](https://linux-hardware.org/?probe=363c1a3642) | Oct 03, 2021 |
| Apple         | MacBookPro12,1              | [2a4757a98f](https://linux-hardware.org/?probe=2a4757a98f) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | [a7e79f067e](https://linux-hardware.org/?probe=a7e79f067e) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | [0b2f645654](https://linux-hardware.org/?probe=0b2f645654) | Sep 30, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [c63b30f0df](https://linux-hardware.org/?probe=c63b30f0df) | Sep 29, 2021 |
| Lenovo        | Z50-70 20354                | [0aef47a401](https://linux-hardware.org/?probe=0aef47a401) | Sep 29, 2021 |
| TUXEDO        | Book BA1510                 | [e408c8fb46](https://linux-hardware.org/?probe=e408c8fb46) | Sep 28, 2021 |
| Acer          | Aspire ES1-332              | [ae6c812e4c](https://linux-hardware.org/?probe=ae6c812e4c) | Sep 28, 2021 |
| Acer          | Aspire ES1-332              | [6bbaec4cfc](https://linux-hardware.org/?probe=6bbaec4cfc) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [4850590ac5](https://linux-hardware.org/?probe=4850590ac5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e7f361c688](https://linux-hardware.org/?probe=e7f361c688) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [61fb50bdf0](https://linux-hardware.org/?probe=61fb50bdf0) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [17bef7f4cf](https://linux-hardware.org/?probe=17bef7f4cf) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3b68a00361](https://linux-hardware.org/?probe=3b68a00361) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| Dell          | Latitude E7450              | [f600127ab1](https://linux-hardware.org/?probe=f600127ab1) | Sep 24, 2021 |
| Lenovo        | B575e 368523G               | [f795bbcedc](https://linux-hardware.org/?probe=f795bbcedc) | Sep 22, 2021 |
| HP            | Compaq nc6400 (EH522AV)     | [8e613adf36](https://linux-hardware.org/?probe=8e613adf36) | Sep 22, 2021 |
| Apple         | MacBookPro15,1              | [3a3ccf8143](https://linux-hardware.org/?probe=3a3ccf8143) | Sep 21, 2021 |
| TUXEDO        | N130BU                      | [12a72404ea](https://linux-hardware.org/?probe=12a72404ea) | Sep 18, 2021 |
| Dell          | XPS 13 9305                 | [369e99699a](https://linux-hardware.org/?probe=369e99699a) | Sep 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [318f8d1653](https://linux-hardware.org/?probe=318f8d1653) | Sep 18, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [385fd35a7e](https://linux-hardware.org/?probe=385fd35a7e) | Sep 16, 2021 |
| TUXEDO        | Book BA1510                 | [2397ee987d](https://linux-hardware.org/?probe=2397ee987d) | Sep 15, 2021 |
| Apple         | MacBookPro15,1              | [73bab0d19c](https://linux-hardware.org/?probe=73bab0d19c) | Sep 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [5fb084ffa4](https://linux-hardware.org/?probe=5fb084ffa4) | Sep 15, 2021 |
| Lenovo        | ThinkPad E580 20KS0039GE    | [d85ddde9ba](https://linux-hardware.org/?probe=d85ddde9ba) | Sep 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [216f21f8d5](https://linux-hardware.org/?probe=216f21f8d5) | Sep 13, 2021 |
| Dell          | Precision 5540              | [2888ae8d0a](https://linux-hardware.org/?probe=2888ae8d0a) | Sep 13, 2021 |
| ASUSTek       | G750JX                      | [185445c775](https://linux-hardware.org/?probe=185445c775) | Sep 12, 2021 |
| Dell          | Latitude E4300              | [4c52be511c](https://linux-hardware.org/?probe=4c52be511c) | Sep 11, 2021 |
| TUXEDO        | N130BU                      | [e81e4cc415](https://linux-hardware.org/?probe=e81e4cc415) | Sep 08, 2021 |
| Medion        | P6618                       | [3fabc658b8](https://linux-hardware.org/?probe=3fabc658b8) | Sep 07, 2021 |
| Unknown       | T3 MRD                      | [e4aff60504](https://linux-hardware.org/?probe=e4aff60504) | Sep 05, 2021 |
| Lenovo        | ThinkPad X130e 06222EU      | [a5822f49a3](https://linux-hardware.org/?probe=a5822f49a3) | Sep 05, 2021 |
| Lenovo        | ThinkPad X270 20HN0016GE    | [cecb5eb453](https://linux-hardware.org/?probe=cecb5eb453) | Sep 05, 2021 |
| Unknown       | T3 MRD                      | [686ecdcfdb](https://linux-hardware.org/?probe=686ecdcfdb) | Sep 04, 2021 |
| Acer          | Aspire A517-52G             | [2d3edcffdd](https://linux-hardware.org/?probe=2d3edcffdd) | Sep 04, 2021 |
| Acer          | Nitro AN517-41              | [5e1633d787](https://linux-hardware.org/?probe=5e1633d787) | Sep 04, 2021 |
| Acer          | Nitro AN517-41              | [37968ff92c](https://linux-hardware.org/?probe=37968ff92c) | Sep 04, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [8c8a4d9cdf](https://linux-hardware.org/?probe=8c8a4d9cdf) | Aug 31, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [bb2bba4301](https://linux-hardware.org/?probe=bb2bba4301) | Aug 31, 2021 |
| Apple         | MacBookPro8,1               | [cf9595f120](https://linux-hardware.org/?probe=cf9595f120) | Aug 31, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [2db9a5db96](https://linux-hardware.org/?probe=2db9a5db96) | Aug 29, 2021 |
| ASUSTek       | X556UQK                     | [e0132c63a3](https://linux-hardware.org/?probe=e0132c63a3) | Aug 29, 2021 |
| Medion        | P6618                       | [39c6d2480b](https://linux-hardware.org/?probe=39c6d2480b) | Aug 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [39ae07c4d8](https://linux-hardware.org/?probe=39ae07c4d8) | Aug 27, 2021 |
| Apple         | MacBookPro8,1               | [c7926f6e27](https://linux-hardware.org/?probe=c7926f6e27) | Aug 27, 2021 |
| HP            | 655                         | [31397c6fa8](https://linux-hardware.org/?probe=31397c6fa8) | Aug 27, 2021 |
| Lenovo        | ThinkPad E570 20H500B4GE    | [be964b556b](https://linux-hardware.org/?probe=be964b556b) | Aug 21, 2021 |
| ASUSTek       | UX305CA                     | [6ab6beca67](https://linux-hardware.org/?probe=6ab6beca67) | Aug 18, 2021 |
| Apple         | MacBookPro15,1              | [c797030409](https://linux-hardware.org/?probe=c797030409) | Aug 17, 2021 |
| MSI           | GE63VR 7RF                  | [d7bffa1592](https://linux-hardware.org/?probe=d7bffa1592) | Aug 15, 2021 |
| Acer          | Aspire 7750G                | [33750f4d18](https://linux-hardware.org/?probe=33750f4d18) | Aug 14, 2021 |
| Acer          | Aspire 7750G                | [0a59ad8e86](https://linux-hardware.org/?probe=0a59ad8e86) | Aug 14, 2021 |
| MSI           | GE63VR 7RF                  | [15a5918df5](https://linux-hardware.org/?probe=15a5918df5) | Aug 12, 2021 |
| Dell          | Precision 7550              | [4fc8f5c8e5](https://linux-hardware.org/?probe=4fc8f5c8e5) | Aug 12, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | [2bc14051d8](https://linux-hardware.org/?probe=2bc14051d8) | Aug 12, 2021 |
| Apple         | MacBookAir7,2               | [54ca114d0c](https://linux-hardware.org/?probe=54ca114d0c) | Aug 10, 2021 |
| Acer          | AO531h                      | [f677e6e910](https://linux-hardware.org/?probe=f677e6e910) | Aug 09, 2021 |
| Acer          | AO531h                      | [42bc030846](https://linux-hardware.org/?probe=42bc030846) | Aug 09, 2021 |
| Acer          | AO531h                      | [3475d2f343](https://linux-hardware.org/?probe=3475d2f343) | Aug 09, 2021 |
| Acer          | Aspire E1-531               | [b26c826616](https://linux-hardware.org/?probe=b26c826616) | Aug 08, 2021 |
| Acer          | Aspire E1-531               | [e3f2ac2973](https://linux-hardware.org/?probe=e3f2ac2973) | Aug 08, 2021 |
| Apple         | MacBookAir6,1               | [5bf397d9fa](https://linux-hardware.org/?probe=5bf397d9fa) | Aug 08, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [dff1b9d6eb](https://linux-hardware.org/?probe=dff1b9d6eb) | Aug 07, 2021 |
| Acer          | Aspire ES1-511              | [d8963041b5](https://linux-hardware.org/?probe=d8963041b5) | Aug 06, 2021 |
| Dell          | Latitude E4300              | [2e5aebdfe9](https://linux-hardware.org/?probe=2e5aebdfe9) | Aug 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | [b83cac3113](https://linux-hardware.org/?probe=b83cac3113) | Aug 03, 2021 |
| Teclast       | F15S                        | [68bbf00d14](https://linux-hardware.org/?probe=68bbf00d14) | Jul 31, 2021 |
| HP            | ProBook 4740s               | [ac069e99cf](https://linux-hardware.org/?probe=ac069e99cf) | Jul 30, 2021 |
| HP            | ProBook 4740s               | [a5251f5930](https://linux-hardware.org/?probe=a5251f5930) | Jul 30, 2021 |
| TENKU         | SB14                        | [b59b680689](https://linux-hardware.org/?probe=b59b680689) | Jul 30, 2021 |
| Lenovo        | ThinkPad P51 20HJS0D107     | [7100544202](https://linux-hardware.org/?probe=7100544202) | Jul 29, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [3927a38ae3](https://linux-hardware.org/?probe=3927a38ae3) | Jul 28, 2021 |
| Dell          | XPS M1530                   | [30b7f582ce](https://linux-hardware.org/?probe=30b7f582ce) | Jul 27, 2021 |
| TUXEDO        | P95_HR                      | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | [d1e3a988b1](https://linux-hardware.org/?probe=d1e3a988b1) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [5ca74a5c0a](https://linux-hardware.org/?probe=5ca74a5c0a) | Jul 22, 2021 |
| Dell          | Latitude E6320              | [f4460165a4](https://linux-hardware.org/?probe=f4460165a4) | Jul 22, 2021 |
| Timi          | A35S                        | [203b3229da](https://linux-hardware.org/?probe=203b3229da) | Jul 20, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| Dell          | Latitude E7470              | [d4985046b7](https://linux-hardware.org/?probe=d4985046b7) | Jul 15, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [36f192a564](https://linux-hardware.org/?probe=36f192a564) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | [5292f36e16](https://linux-hardware.org/?probe=5292f36e16) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | [3367527048](https://linux-hardware.org/?probe=3367527048) | Jul 15, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [5676714ec9](https://linux-hardware.org/?probe=5676714ec9) | Jul 14, 2021 |
| HP            | EliteBook 1030 G1           | [6c60248fbc](https://linux-hardware.org/?probe=6c60248fbc) | Jul 11, 2021 |
| ASUSTek       | K95VB                       | [ee4aa23d71](https://linux-hardware.org/?probe=ee4aa23d71) | Jul 11, 2021 |
| HP            | EliteBook 8570p             | [f4d41192b1](https://linux-hardware.org/?probe=f4d41192b1) | Jul 10, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b411603809](https://linux-hardware.org/?probe=b411603809) | Jul 10, 2021 |
| Lenovo        | ThinkPad T470s 20HGS45C0... | [afc9280a07](https://linux-hardware.org/?probe=afc9280a07) | Jul 09, 2021 |
| Dell          | Precision 5530              | [a2698d4e69](https://linux-hardware.org/?probe=a2698d4e69) | Jul 07, 2021 |
| Sony          | VPCEH2J1E                   | [dcad426e53](https://linux-hardware.org/?probe=dcad426e53) | Jul 06, 2021 |
| Sony          | VPCEH2J1E                   | [d9c094da9f](https://linux-hardware.org/?probe=d9c094da9f) | Jul 05, 2021 |
| HP            | ProBook 430 G2              | [82608fa1f4](https://linux-hardware.org/?probe=82608fa1f4) | Jul 04, 2021 |
| HP            | ProBook 430 G2              | [73af72bee1](https://linux-hardware.org/?probe=73af72bee1) | Jul 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [048d10c013](https://linux-hardware.org/?probe=048d10c013) | Jul 04, 2021 |
| Acer          | Aspire V5-573G              | [eef9527dd8](https://linux-hardware.org/?probe=eef9527dd8) | Jul 04, 2021 |
| Toshiba       | QOSMIO X70-B                | [dcec6c2c5f](https://linux-hardware.org/?probe=dcec6c2c5f) | Jul 02, 2021 |
| Acer          | Aspire V5-573G              | [243f7cf95e](https://linux-hardware.org/?probe=243f7cf95e) | Jul 01, 2021 |
| Acer          | Aspire E5-575G              | [698f108789](https://linux-hardware.org/?probe=698f108789) | Jun 29, 2021 |
| Acer          | Aspire V5-573G              | [5b40b1a1a3](https://linux-hardware.org/?probe=5b40b1a1a3) | Jun 27, 2021 |
| Sony          | VGN-CR42S_W                 | [26b02ccda4](https://linux-hardware.org/?probe=26b02ccda4) | Jun 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [71134cd640](https://linux-hardware.org/?probe=71134cd640) | Jun 25, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [7c679b05c3](https://linux-hardware.org/?probe=7c679b05c3) | Jun 25, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | [2bf10c3d80](https://linux-hardware.org/?probe=2bf10c3d80) | Jun 19, 2021 |
| HP            | EliteBook 8570p             | [f872ec3b49](https://linux-hardware.org/?probe=f872ec3b49) | Jun 18, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [9f796182e7](https://linux-hardware.org/?probe=9f796182e7) | Jun 16, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE R7 8... | [b2c24061a6](https://linux-hardware.org/?probe=b2c24061a6) | Jun 13, 2021 |
| Sony          | VGN-NW21MF_P                | [60fc563598](https://linux-hardware.org/?probe=60fc563598) | Jun 12, 2021 |
| Dell          | Precision 5540              | [b21ffd09ff](https://linux-hardware.org/?probe=b21ffd09ff) | Jun 11, 2021 |
| Medion        | P6669 MD60147               | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Dell          | Latitude E6400              | [6e177b21bc](https://linux-hardware.org/?probe=6e177b21bc) | Jun 08, 2021 |
| Dell          | Latitude E7450              | [2a06a286c3](https://linux-hardware.org/?probe=2a06a286c3) | Jun 07, 2021 |
| Dell          | Latitude E6540              | [92f0506c6a](https://linux-hardware.org/?probe=92f0506c6a) | Jun 07, 2021 |
| HP            | Unknown                     | [c3e3f15a63](https://linux-hardware.org/?probe=c3e3f15a63) | Jun 05, 2021 |
| LG Electro... | 16Z90P-G.AA76G              | [7a64de799d](https://linux-hardware.org/?probe=7a64de799d) | Jun 03, 2021 |
| Dell          | Latitude E6520              | [4a0a20fd2b](https://linux-hardware.org/?probe=4a0a20fd2b) | Jun 03, 2021 |
| Dell          | Latitude E5550              | [4a4f7af190](https://linux-hardware.org/?probe=4a4f7af190) | Jun 03, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [6c7ee340df](https://linux-hardware.org/?probe=6c7ee340df) | Jun 03, 2021 |
| Acer          | Aspire S7-191               | [0b0c0919e0](https://linux-hardware.org/?probe=0b0c0919e0) | Jun 02, 2021 |
| Apple         | MacBookPro9,2               | [08232b5b75](https://linux-hardware.org/?probe=08232b5b75) | Jun 02, 2021 |
| HP            | EliteBook 2540p             | [d62314d0c2](https://linux-hardware.org/?probe=d62314d0c2) | Jun 01, 2021 |
| Acer          | Aspire E5-575G              | [d8f16e67c0](https://linux-hardware.org/?probe=d8f16e67c0) | Jun 01, 2021 |
| HP            | EliteBook 2560p             | [e96260cfb9](https://linux-hardware.org/?probe=e96260cfb9) | May 31, 2021 |
| TUXEDO        | InfinityBook_S_14_v5        | [36d147c67f](https://linux-hardware.org/?probe=36d147c67f) | May 31, 2021 |
| Acer          | Aspire ES1-511              | [a7aea0a2dd](https://linux-hardware.org/?probe=a7aea0a2dd) | May 30, 2021 |
| Acer          | Aspire ES1-511              | [ac5911f3a7](https://linux-hardware.org/?probe=ac5911f3a7) | May 30, 2021 |
| Medion        | Erazer X7841 MD99556        | [3e6f8e05b4](https://linux-hardware.org/?probe=3e6f8e05b4) | May 27, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [2ffefbd96c](https://linux-hardware.org/?probe=2ffefbd96c) | May 25, 2021 |
| HP            | EliteBook 1030 G1           | [34cf12674c](https://linux-hardware.org/?probe=34cf12674c) | May 24, 2021 |
| Acer          | Swift SF114-34              | [7747754c25](https://linux-hardware.org/?probe=7747754c25) | May 23, 2021 |
| Acer          | Swift SF114-34              | [b8c61540de](https://linux-hardware.org/?probe=b8c61540de) | May 23, 2021 |
| Toshiba       | Satellite C50D-B            | [7ae2644ef1](https://linux-hardware.org/?probe=7ae2644ef1) | May 20, 2021 |
| Toshiba       | Satellite C50D-B            | [599106595e](https://linux-hardware.org/?probe=599106595e) | May 20, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [12ffaaefb1](https://linux-hardware.org/?probe=12ffaaefb1) | May 18, 2021 |
| Dell          | XPS 13 7390                 | [e69f835f2b](https://linux-hardware.org/?probe=e69f835f2b) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| HP            | EliteBook 8570p             | [2c31a6309e](https://linux-hardware.org/?probe=2c31a6309e) | May 12, 2021 |
| HP            | EliteBook 8570p             | [6d330f71d0](https://linux-hardware.org/?probe=6d330f71d0) | May 12, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [28f6f5a90b](https://linux-hardware.org/?probe=28f6f5a90b) | May 12, 2021 |
| ASUSTek       | K50IJ                       | [9932cbdd1a](https://linux-hardware.org/?probe=9932cbdd1a) | May 12, 2021 |
| Sony          | VPCEH2D0E                   | [3c201a9337](https://linux-hardware.org/?probe=3c201a9337) | May 11, 2021 |
| Dell          | Venue 11 Pro 7130 MS        | [478ca880ab](https://linux-hardware.org/?probe=478ca880ab) | May 10, 2021 |
| ASUSTek       | K52F                        | [0ff0faf2a5](https://linux-hardware.org/?probe=0ff0faf2a5) | May 07, 2021 |
| Acer          | Swift SF314-42              | [ecb10aec9a](https://linux-hardware.org/?probe=ecb10aec9a) | May 03, 2021 |
| HP            | Pavilion x2 Detachable      | [71120b9356](https://linux-hardware.org/?probe=71120b9356) | May 03, 2021 |
| Lenovo        | G570 4334                   | [e7e1be6de9](https://linux-hardware.org/?probe=e7e1be6de9) | May 01, 2021 |
| Lenovo        | G570 4334                   | [c9ba5be735](https://linux-hardware.org/?probe=c9ba5be735) | May 01, 2021 |
| Lenovo        | ThinkPad E470 20H2S00700    | [cc35722c1f](https://linux-hardware.org/?probe=cc35722c1f) | May 01, 2021 |
| Lenovo        | G505 20240                  | [3b93e825de](https://linux-hardware.org/?probe=3b93e825de) | Apr 29, 2021 |
| Dell          | Latitude E6540              | [b704f13c9d](https://linux-hardware.org/?probe=b704f13c9d) | Apr 29, 2021 |
| Lenovo        | G505 20240                  | [af3eb72485](https://linux-hardware.org/?probe=af3eb72485) | Apr 28, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [190564ec8e](https://linux-hardware.org/?probe=190564ec8e) | Apr 28, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4e842c54ad](https://linux-hardware.org/?probe=4e842c54ad) | Apr 23, 2021 |
| Lenovo        | ThinkPad T430 23511Z0       | [7bea11a2e4](https://linux-hardware.org/?probe=7bea11a2e4) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [7074c51162](https://linux-hardware.org/?probe=7074c51162) | Apr 21, 2021 |
| Toshiba       | Satellite A200              | [3f0ebd44ad](https://linux-hardware.org/?probe=3f0ebd44ad) | Apr 19, 2021 |
| Lenovo        | ThinkPad T430s 2356GW2      | [1a6dcc75f5](https://linux-hardware.org/?probe=1a6dcc75f5) | Apr 19, 2021 |
| Lenovo        | ThinkPad E495 20NEA001GE    | [d7fed90840](https://linux-hardware.org/?probe=d7fed90840) | Apr 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [0fafab787e](https://linux-hardware.org/?probe=0fafab787e) | Apr 19, 2021 |
| Shuttle       | DS67U                       | [f1dff13da7](https://linux-hardware.org/?probe=f1dff13da7) | Apr 18, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [b753c3d9a0](https://linux-hardware.org/?probe=b753c3d9a0) | Apr 16, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [dd3ff8b26e](https://linux-hardware.org/?probe=dd3ff8b26e) | Apr 16, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [763d56e304](https://linux-hardware.org/?probe=763d56e304) | Apr 15, 2021 |
| HP            | EliteBook Folio 9470m       | [9801f1066c](https://linux-hardware.org/?probe=9801f1066c) | Apr 14, 2021 |
| HP            | EliteBook Folio 9470m       | [267c47f371](https://linux-hardware.org/?probe=267c47f371) | Apr 14, 2021 |
| Jumper        | EZpad6                      | [4cd7cb7569](https://linux-hardware.org/?probe=4cd7cb7569) | Apr 13, 2021 |
| Jumper        | EZpad6                      | [5c8abe710b](https://linux-hardware.org/?probe=5c8abe710b) | Apr 13, 2021 |
| Lenovo        | IdeaPad U510 4941           | [96b93bc0f4](https://linux-hardware.org/?probe=96b93bc0f4) | Apr 12, 2021 |
| HP            | Laptop 15-bs1xx             | [44520abad1](https://linux-hardware.org/?probe=44520abad1) | Apr 11, 2021 |
| Acer          | Nitro AN515-44              | [19f0a0eeed](https://linux-hardware.org/?probe=19f0a0eeed) | Apr 10, 2021 |
| Medion        | E7426 MD62150               | [e5a42ec693](https://linux-hardware.org/?probe=e5a42ec693) | Apr 10, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [54d7d9c149](https://linux-hardware.org/?probe=54d7d9c149) | Apr 10, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [3db45eec95](https://linux-hardware.org/?probe=3db45eec95) | Apr 10, 2021 |
| Notebook      | N8xEJEK                     | [4794a1ad98](https://linux-hardware.org/?probe=4794a1ad98) | Apr 09, 2021 |
| Acer          | Nitro AN515-44              | [c9dcfde4e1](https://linux-hardware.org/?probe=c9dcfde4e1) | Apr 09, 2021 |
| Dell          | Latitude 7280               | [1c4da429ac](https://linux-hardware.org/?probe=1c4da429ac) | Apr 09, 2021 |
| HP            | EliteBook 8760w             | [9067d9bf55](https://linux-hardware.org/?probe=9067d9bf55) | Apr 08, 2021 |
| HP            | EliteBook 8760w             | [59247a25b1](https://linux-hardware.org/?probe=59247a25b1) | Apr 07, 2021 |
| Dell          | Precision M6700             | [8a5e6b4598](https://linux-hardware.org/?probe=8a5e6b4598) | Apr 06, 2021 |
| HP            | EliteBook Folio 9480m       | [c878c10e7b](https://linux-hardware.org/?probe=c878c10e7b) | Apr 03, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Medion        | P7402 MD60850               | [0e482f31af](https://linux-hardware.org/?probe=0e482f31af) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | [430aae4994](https://linux-hardware.org/?probe=430aae4994) | Mar 27, 2021 |
| ASUSTek       | GL702ZC                     | [b79e897508](https://linux-hardware.org/?probe=b79e897508) | Mar 27, 2021 |
| Lenovo        | Yoga S940-14IIL 81Q8        | [53acf73fdc](https://linux-hardware.org/?probe=53acf73fdc) | Mar 25, 2021 |
| Schenker      | VIA 15 Pro                  | [2773f5141e](https://linux-hardware.org/?probe=2773f5141e) | Mar 24, 2021 |
| ASUSTek       | ZenBook UX392FA_UX392FA     | [bc779456b0](https://linux-hardware.org/?probe=bc779456b0) | Mar 20, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [e143b5b907](https://linux-hardware.org/?probe=e143b5b907) | Mar 17, 2021 |
| Dell          | Latitude E6540              | [1d979a7265](https://linux-hardware.org/?probe=1d979a7265) | Mar 17, 2021 |
| Medion        | Akoya E4214 MD99570         | [45e8b2ad25](https://linux-hardware.org/?probe=45e8b2ad25) | Mar 17, 2021 |
| ASUSTek       | X541NA                      | [c18feddb7b](https://linux-hardware.org/?probe=c18feddb7b) | Mar 15, 2021 |
| Acer          | Aspire 5733Z                | [beb1b7f09e](https://linux-hardware.org/?probe=beb1b7f09e) | Mar 15, 2021 |
| Sony          | VGN-CR42S_W                 | [b45fd47859](https://linux-hardware.org/?probe=b45fd47859) | Mar 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | [199c5a397a](https://linux-hardware.org/?probe=199c5a397a) | Mar 14, 2021 |
| Lenovo        | ThinkPad T470s 20HGS45C0... | [8739fea3ef](https://linux-hardware.org/?probe=8739fea3ef) | Mar 14, 2021 |
| Lenovo        | ThinkPad T470s 20HGS45C0... | [b6d9e2c549](https://linux-hardware.org/?probe=b6d9e2c549) | Mar 14, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ae0a17e8ab](https://linux-hardware.org/?probe=ae0a17e8ab) | Mar 13, 2021 |
| Lenovo        | Yoga S940-14IIL 81Q8        | [4816527f0e](https://linux-hardware.org/?probe=4816527f0e) | Mar 12, 2021 |
| Dell          | Latitude E5470              | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| HP            | EliteBook 1030 G1           | [3b865be010](https://linux-hardware.org/?probe=3b865be010) | Mar 09, 2021 |
| Medion        | P6618                       | [70a3be7f75](https://linux-hardware.org/?probe=70a3be7f75) | Mar 06, 2021 |
| Lenovo        | G500 20236                  | [d3f859d949](https://linux-hardware.org/?probe=d3f859d949) | Mar 06, 2021 |
| HP            | EliteBook 840 G1            | [078c01d2d4](https://linux-hardware.org/?probe=078c01d2d4) | Mar 04, 2021 |
| HP            | EliteBook 840 G1            | [4209d1408d](https://linux-hardware.org/?probe=4209d1408d) | Mar 04, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [3621039fbb](https://linux-hardware.org/?probe=3621039fbb) | Mar 04, 2021 |
| Acer          | Aspire 2930 V1.04           | [8ec4fa1849](https://linux-hardware.org/?probe=8ec4fa1849) | Feb 26, 2021 |
| Acer          | Aspire 2930 V1.04           | [4730e616bb](https://linux-hardware.org/?probe=4730e616bb) | Feb 26, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [4b4b633bd6](https://linux-hardware.org/?probe=4b4b633bd6) | Feb 22, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [4376a22c0a](https://linux-hardware.org/?probe=4376a22c0a) | Feb 22, 2021 |
| Apple         | MacBookPro15,1              | [566cc27d41](https://linux-hardware.org/?probe=566cc27d41) | Feb 22, 2021 |
| Apple         | MacBookPro15,1              | [18cb9d83ae](https://linux-hardware.org/?probe=18cb9d83ae) | Feb 22, 2021 |
| Acer          | Aspire 7750G                | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| HP            | Compaq 6820s                | [26295aee0f](https://linux-hardware.org/?probe=26295aee0f) | Feb 18, 2021 |
| HP            | Compaq 6820s                | [b8c238fd7a](https://linux-hardware.org/?probe=b8c238fd7a) | Feb 18, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [42cd2866c5](https://linux-hardware.org/?probe=42cd2866c5) | Feb 17, 2021 |
| Toshiba       | Satellite C50D-B            | [4114652578](https://linux-hardware.org/?probe=4114652578) | Feb 16, 2021 |
| Toshiba       | Satellite C50D-B            | [63a04a0d52](https://linux-hardware.org/?probe=63a04a0d52) | Feb 16, 2021 |
| HP            | ProBook 450 G3              | [8b14f78b72](https://linux-hardware.org/?probe=8b14f78b72) | Feb 16, 2021 |
| Toshiba       | Satellite L70-B             | [6ac7d50ce6](https://linux-hardware.org/?probe=6ac7d50ce6) | Feb 15, 2021 |
| Acer          | Chapala                     | [317beca6a3](https://linux-hardware.org/?probe=317beca6a3) | Feb 14, 2021 |
| Acer          | Chapala                     | [42de79c5ac](https://linux-hardware.org/?probe=42de79c5ac) | Feb 14, 2021 |
| Medion        | E7426 MD62150               | [12c4a589c1](https://linux-hardware.org/?probe=12c4a589c1) | Feb 14, 2021 |
| ASUSTek       | F5N                         | [40ca2e2a26](https://linux-hardware.org/?probe=40ca2e2a26) | Feb 14, 2021 |
| Toshiba       | Satellite P300              | [a00049839a](https://linux-hardware.org/?probe=a00049839a) | Feb 13, 2021 |
| Toshiba       | Satellite C855D-12N         | [4c6329a7a2](https://linux-hardware.org/?probe=4c6329a7a2) | Feb 13, 2021 |
| Toshiba       | Satellite C855D-12N         | [8ec19f60ae](https://linux-hardware.org/?probe=8ec19f60ae) | Feb 13, 2021 |
| Lenovo        | V15-ADA 82C7                | [b736631193](https://linux-hardware.org/?probe=b736631193) | Feb 11, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [43d2f5786d](https://linux-hardware.org/?probe=43d2f5786d) | Feb 08, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [38992d7b6b](https://linux-hardware.org/?probe=38992d7b6b) | Feb 08, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [fc50e7350b](https://linux-hardware.org/?probe=fc50e7350b) | Feb 07, 2021 |
| Lenovo        | ThinkPad W510 4389W1B       | [ec27151293](https://linux-hardware.org/?probe=ec27151293) | Feb 06, 2021 |
| Acer          | TravelMate P253             | [678af5f2af](https://linux-hardware.org/?probe=678af5f2af) | Feb 06, 2021 |
| HP            | Pavilion x2 Detachable      | [8d05902c8c](https://linux-hardware.org/?probe=8d05902c8c) | Feb 06, 2021 |
| Lenovo        | ThinkPad W530 2447H21       | [9a62d43629](https://linux-hardware.org/?probe=9a62d43629) | Feb 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [109924ff6a](https://linux-hardware.org/?probe=109924ff6a) | Feb 02, 2021 |
| Lenovo        | ThinkPad T460s 20FAS1TH0... | [2d4882b3f4](https://linux-hardware.org/?probe=2d4882b3f4) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460s 20FAS1TH0... | [bd4071fabf](https://linux-hardware.org/?probe=bd4071fabf) | Feb 01, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [529126337c](https://linux-hardware.org/?probe=529126337c) | Jan 31, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| Dell          | Latitude 5490               | [7747e6a7ea](https://linux-hardware.org/?probe=7747e6a7ea) | Jan 28, 2021 |
| Lenovo        | ThinkPad T410 25376R9       | [2ca383227c](https://linux-hardware.org/?probe=2ca383227c) | Jan 27, 2021 |
| HP            | EliteBook Folio 1040 G3     | [78ae5415c8](https://linux-hardware.org/?probe=78ae5415c8) | Jan 22, 2021 |
| Dell          | XPS 13 9300                 | [c014c04288](https://linux-hardware.org/?probe=c014c04288) | Jan 21, 2021 |
| HP            | Pavilion dv6                | [ab2744120a](https://linux-hardware.org/?probe=ab2744120a) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [8ac8b21edc](https://linux-hardware.org/?probe=8ac8b21edc) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [1fd8dfebee](https://linux-hardware.org/?probe=1fd8dfebee) | Jan 20, 2021 |
| HP            | Pavilion dv6                | [facfb18441](https://linux-hardware.org/?probe=facfb18441) | Jan 20, 2021 |
| Lenovo        | Flex 2-14D 20376            | [a93ecc2faa](https://linux-hardware.org/?probe=a93ecc2faa) | Jan 19, 2021 |
| Apple         | MacBookPro9,2               | [25244fe913](https://linux-hardware.org/?probe=25244fe913) | Jan 19, 2021 |
| Toshiba       | Satellite Pro C660          | [ba0d7bcaf8](https://linux-hardware.org/?probe=ba0d7bcaf8) | Jan 19, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [4cae7dc78d](https://linux-hardware.org/?probe=4cae7dc78d) | Jan 18, 2021 |
| HP            | Pavilion dv6                | [650296bdfb](https://linux-hardware.org/?probe=650296bdfb) | Jan 16, 2021 |
| Dell          | XPS L322X                   | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [6a0bdefe43](https://linux-hardware.org/?probe=6a0bdefe43) | Jan 13, 2021 |
| HP            | ProBook 650 G5              | [d81e73dec0](https://linux-hardware.org/?probe=d81e73dec0) | Jan 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [a716890bba](https://linux-hardware.org/?probe=a716890bba) | Jan 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [cc4b76d3f9](https://linux-hardware.org/?probe=cc4b76d3f9) | Jan 12, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [d292578866](https://linux-hardware.org/?probe=d292578866) | Jan 11, 2021 |
| Dell          | XPS 13 9310                 | [ac8d0ac299](https://linux-hardware.org/?probe=ac8d0ac299) | Jan 11, 2021 |
| TUXEDO        | P65_67HSHP                  | [ac1abdaf6f](https://linux-hardware.org/?probe=ac1abdaf6f) | Jan 10, 2021 |
| ASUSTek       | K53SC                       | [5bdf46531d](https://linux-hardware.org/?probe=5bdf46531d) | Jan 09, 2021 |
| ASUSTek       | K53SC                       | [14e9aa89c7](https://linux-hardware.org/?probe=14e9aa89c7) | Jan 09, 2021 |
| HP            | EliteBook 840 G3            | [37610922c3](https://linux-hardware.org/?probe=37610922c3) | Jan 06, 2021 |
| Lenovo        | ThinkPad X250 20CLS78300    | [fd874fe822](https://linux-hardware.org/?probe=fd874fe822) | Jan 06, 2021 |
| Sony          | VPCEH2J1E                   | [6ef61078ae](https://linux-hardware.org/?probe=6ef61078ae) | Jan 05, 2021 |
| Sony          | VPCEH2J1E                   | [a063086db9](https://linux-hardware.org/?probe=a063086db9) | Jan 05, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [892e0a235f](https://linux-hardware.org/?probe=892e0a235f) | Jan 05, 2021 |
| HP            | EliteBook 840 G3            | [e6886a3a33](https://linux-hardware.org/?probe=e6886a3a33) | Jan 04, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [0f2ae77a6d](https://linux-hardware.org/?probe=0f2ae77a6d) | Jan 04, 2021 |
| Medion        | Erazer X7841 MD99556        | [13c1c5ae54](https://linux-hardware.org/?probe=13c1c5ae54) | Jan 04, 2021 |
| Unknown       | Unknown                     | [e702e7abac](https://linux-hardware.org/?probe=e702e7abac) | Jan 04, 2021 |
| HP            | Pavilion dv6                | [6f5046b1ce](https://linux-hardware.org/?probe=6f5046b1ce) | Jan 04, 2021 |
| HP            | EliteBook 8570p             | [387e3e274b](https://linux-hardware.org/?probe=387e3e274b) | Jan 03, 2021 |
| HP            | EliteBook 850 G1            | [60b89588c9](https://linux-hardware.org/?probe=60b89588c9) | Jan 03, 2021 |
| HP            | EliteBook 850 G1            | [eafc5693d2](https://linux-hardware.org/?probe=eafc5693d2) | Jan 03, 2021 |
| ASUSTek       | N501VW                      | [76cb94dddc](https://linux-hardware.org/?probe=76cb94dddc) | Dec 31, 2020 |
| HP            | Presario CQ57               | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| Lenovo        | Flex 2-14D 20376            | [c834f7e438](https://linux-hardware.org/?probe=c834f7e438) | Dec 31, 2020 |
| HP            | Presario CQ57               | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | TravelMate 5735Z            | [caca9a9ee2](https://linux-hardware.org/?probe=caca9a9ee2) | Dec 30, 2020 |
| HP            | ZBook 17 G5                 | [f314302d88](https://linux-hardware.org/?probe=f314302d88) | Dec 30, 2020 |
| Wortmann      | Mobile 1745                 | [72f9ad676b](https://linux-hardware.org/?probe=72f9ad676b) | Dec 30, 2020 |
| Wortmann      | Mobile 1745                 | [17db63ebf8](https://linux-hardware.org/?probe=17db63ebf8) | Dec 30, 2020 |
| Dell          | Latitude E6320              | [c4cccf3f47](https://linux-hardware.org/?probe=c4cccf3f47) | Dec 30, 2020 |
| HP            | EliteBook 745 G3            | [ec6c4665e1](https://linux-hardware.org/?probe=ec6c4665e1) | Dec 29, 2020 |
| HP            | EliteBook 745 G3            | [50225c105a](https://linux-hardware.org/?probe=50225c105a) | Dec 29, 2020 |
| TUXEDO        | Pulse 15 Gen1               | [84c045204c](https://linux-hardware.org/?probe=84c045204c) | Dec 28, 2020 |
| Dell          | Inspiron 5570               | [a8dfd61976](https://linux-hardware.org/?probe=a8dfd61976) | Dec 28, 2020 |
| Wortmann      | Mobile 1745                 | [579e27e69b](https://linux-hardware.org/?probe=579e27e69b) | Dec 27, 2020 |
| Dell          | Latitude E7440              | [0f52253e24](https://linux-hardware.org/?probe=0f52253e24) | Dec 25, 2020 |
| Dell          | Inspiron 5570               | [d3732710f8](https://linux-hardware.org/?probe=d3732710f8) | Dec 25, 2020 |
| HP            | Notebook                    | [4264579980](https://linux-hardware.org/?probe=4264579980) | Dec 25, 2020 |
| HP            | Notebook                    | [23299a3071](https://linux-hardware.org/?probe=23299a3071) | Dec 25, 2020 |
| HP            | EliteBook 8570p             | [a85684b0e3](https://linux-hardware.org/?probe=a85684b0e3) | Dec 23, 2020 |
| HP            | EliteBook 8570p             | [625c0af78f](https://linux-hardware.org/?probe=625c0af78f) | Dec 23, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8b65be60d7](https://linux-hardware.org/?probe=8b65be60d7) | Dec 22, 2020 |
| Fujitsu       | LIFEBOOK E756               | [9072367bc6](https://linux-hardware.org/?probe=9072367bc6) | Dec 22, 2020 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [c1f5cdeba9](https://linux-hardware.org/?probe=c1f5cdeba9) | Dec 22, 2020 |
| Apple         | MacBook4,1                  | [0ff1a21e49](https://linux-hardware.org/?probe=0ff1a21e49) | Dec 21, 2020 |
| Dell          | XPS 15 9570                 | [169f75ba5c](https://linux-hardware.org/?probe=169f75ba5c) | Dec 21, 2020 |
| Lenovo        | ThinkPad P70 20ER000EGE     | [6413990c99](https://linux-hardware.org/?probe=6413990c99) | Dec 16, 2020 |
| HP            | EliteBook 840 G3            | [708eaf5602](https://linux-hardware.org/?probe=708eaf5602) | Dec 14, 2020 |
| Dell          | XPS 15 9570                 | [7d337ec9b3](https://linux-hardware.org/?probe=7d337ec9b3) | Dec 13, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | [2494a33ba4](https://linux-hardware.org/?probe=2494a33ba4) | Dec 13, 2020 |
| Apple         | MacBookPro15,1              | [6b39cb0ac1](https://linux-hardware.org/?probe=6b39cb0ac1) | Dec 11, 2020 |
| Apple         | MacBookPro15,1              | [4a2bda5c7e](https://linux-hardware.org/?probe=4a2bda5c7e) | Dec 11, 2020 |
| Medion        | Akoya S4220 MD99660         | [b07a7e906e](https://linux-hardware.org/?probe=b07a7e906e) | Dec 07, 2020 |
| Acer          | TravelMate P253             | [a9e4db8396](https://linux-hardware.org/?probe=a9e4db8396) | Dec 06, 2020 |
| Unknown       | Unknown                     | [b6af52b707](https://linux-hardware.org/?probe=b6af52b707) | Dec 04, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [d8fff30988](https://linux-hardware.org/?probe=d8fff30988) | Dec 04, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [548218334c](https://linux-hardware.org/?probe=548218334c) | Dec 03, 2020 |
| Acer          | Aspire 5733Z                | [cee0103079](https://linux-hardware.org/?probe=cee0103079) | Dec 02, 2020 |
| Unknown       | Unknown                     | [4102aed9b6](https://linux-hardware.org/?probe=4102aed9b6) | Dec 02, 2020 |
| Dell          | Precision 5530              | [7067683c8a](https://linux-hardware.org/?probe=7067683c8a) | Dec 01, 2020 |
| Clevo         | W150ER                      | [43d4833cd9](https://linux-hardware.org/?probe=43d4833cd9) | Dec 01, 2020 |
| Sony          | SVE1513S1EW                 | [cabda1d2bb](https://linux-hardware.org/?probe=cabda1d2bb) | Nov 30, 2020 |
| Lenovo        | Z710 20250                  | [700c65c16f](https://linux-hardware.org/?probe=700c65c16f) | Nov 29, 2020 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [e3c0f67fb8](https://linux-hardware.org/?probe=e3c0f67fb8) | Nov 29, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [14558cdb25](https://linux-hardware.org/?probe=14558cdb25) | Nov 29, 2020 |
| Lenovo        | ThinkPad T420 4236B87       | [c4208169ee](https://linux-hardware.org/?probe=c4208169ee) | Nov 29, 2020 |
| ASUSTek       | X541UAK                     | [b527cf9243](https://linux-hardware.org/?probe=b527cf9243) | Nov 29, 2020 |
| Apple         | MacBookPro15,1              | [9cedfc4727](https://linux-hardware.org/?probe=9cedfc4727) | Nov 25, 2020 |
| Lenovo        | ThinkPad T61 7659AB7        | [87d6a75f6f](https://linux-hardware.org/?probe=87d6a75f6f) | Nov 23, 2020 |
| MSI           | CX700                       | [78401c7758](https://linux-hardware.org/?probe=78401c7758) | Nov 22, 2020 |
| ASUSTek       | X200CA                      | [73a317dd32](https://linux-hardware.org/?probe=73a317dd32) | Nov 21, 2020 |
| ASUSTek       | X200CA                      | [2a86994bf7](https://linux-hardware.org/?probe=2a86994bf7) | Nov 21, 2020 |
| ASUSTek       | P553UA                      | [08a45ba314](https://linux-hardware.org/?probe=08a45ba314) | Nov 16, 2020 |
| HP            | OMEN by Laptop 17-cb0xxx    | [43f7b0ed5e](https://linux-hardware.org/?probe=43f7b0ed5e) | Nov 16, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4fccf7c912](https://linux-hardware.org/?probe=4fccf7c912) | Nov 15, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [00d5983461](https://linux-hardware.org/?probe=00d5983461) | Nov 15, 2020 |
| Apple         | MacBookPro15,1              | [1ebfd7c5b6](https://linux-hardware.org/?probe=1ebfd7c5b6) | Nov 14, 2020 |
| Apple         | MacBookPro15,1              | [8bc8600e93](https://linux-hardware.org/?probe=8bc8600e93) | Nov 14, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU0S    | [f70cdb0ad4](https://linux-hardware.org/?probe=f70cdb0ad4) | Nov 12, 2020 |
| Alienware     | 18                          | [57676ac43d](https://linux-hardware.org/?probe=57676ac43d) | Nov 10, 2020 |
| TUXEDO        | P65_67HSHP                  | [66d5b793fb](https://linux-hardware.org/?probe=66d5b793fb) | Nov 08, 2020 |
| HP            | 250 G3                      | [8b5f98ec2a](https://linux-hardware.org/?probe=8b5f98ec2a) | Nov 07, 2020 |
| Medion        | Akoya S4220 MD99660         | [7f1c16bcda](https://linux-hardware.org/?probe=7f1c16bcda) | Nov 06, 2020 |
| Lenovo        | E51-80 80QB                 | [ca5466d80a](https://linux-hardware.org/?probe=ca5466d80a) | Nov 05, 2020 |
| HP            | ProBook 455 G7              | [98b7cd43d4](https://linux-hardware.org/?probe=98b7cd43d4) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [aa9c0e0e54](https://linux-hardware.org/?probe=aa9c0e0e54) | Nov 04, 2020 |
| Dell          | Latitude E6530              | [37fe920988](https://linux-hardware.org/?probe=37fe920988) | Oct 31, 2020 |
| Medion        | Akoya S4220 MD99660         | [bb717a9e21](https://linux-hardware.org/?probe=bb717a9e21) | Oct 31, 2020 |
| Gigabyte      | M1M3XBP-00                  | [b6c122e3a8](https://linux-hardware.org/?probe=b6c122e3a8) | Oct 30, 2020 |
| Dell          | Inspiron N5110              | [cf33d9bfbd](https://linux-hardware.org/?probe=cf33d9bfbd) | Oct 30, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [560dfacda1](https://linux-hardware.org/?probe=560dfacda1) | Oct 30, 2020 |
| Acer          | Aspire VN7-571G             | [cb343ac230](https://linux-hardware.org/?probe=cb343ac230) | Oct 29, 2020 |
| HP            | Notebook                    | [e9cffa5296](https://linux-hardware.org/?probe=e9cffa5296) | Oct 27, 2020 |
| Sony          | VPCEH2J1E                   | [63d6cbf81b](https://linux-hardware.org/?probe=63d6cbf81b) | Oct 26, 2020 |
| Apple         | MacBookPro5,1               | [9a77d8bcee](https://linux-hardware.org/?probe=9a77d8bcee) | Oct 25, 2020 |
| HP            | ProBook 455 G7              | [2567e8cd8d](https://linux-hardware.org/?probe=2567e8cd8d) | Oct 22, 2020 |
| ASUSTek       | K70IC                       | [bd81130974](https://linux-hardware.org/?probe=bd81130974) | Oct 21, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [0795bcf48b](https://linux-hardware.org/?probe=0795bcf48b) | Oct 20, 2020 |
| Dell          | XPS M1530                   | [fe7376d804](https://linux-hardware.org/?probe=fe7376d804) | Oct 20, 2020 |
| HP            | ZBook 15u G6                | [d7fdb50013](https://linux-hardware.org/?probe=d7fdb50013) | Oct 20, 2020 |
| Sony          | VPCEH2J1E                   | [1eaddc7d21](https://linux-hardware.org/?probe=1eaddc7d21) | Oct 19, 2020 |
| Lenovo        | ThinkPad E470 20H2S00700    | [425f8279f4](https://linux-hardware.org/?probe=425f8279f4) | Oct 18, 2020 |
| HP            | Pavilion dv6000 (RM474EA... | [45c9c4c500](https://linux-hardware.org/?probe=45c9c4c500) | Oct 16, 2020 |
| Lenovo        | ThinkPad E470 20H2S00700    | [6c91e0804a](https://linux-hardware.org/?probe=6c91e0804a) | Oct 16, 2020 |
| Lenovo        | ThinkPad P51 20HJS0Q900     | [afbd1d03a4](https://linux-hardware.org/?probe=afbd1d03a4) | Oct 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [8f7686c8ae](https://linux-hardware.org/?probe=8f7686c8ae) | Oct 15, 2020 |
| HP            | 250 G3                      | [66a0f6f80d](https://linux-hardware.org/?probe=66a0f6f80d) | Oct 15, 2020 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [89d37bfc4f](https://linux-hardware.org/?probe=89d37bfc4f) | Oct 15, 2020 |
| HP            | EliteBook 8460p             | [081e9ba453](https://linux-hardware.org/?probe=081e9ba453) | Oct 13, 2020 |
| HP            | ProBook 445 G7              | [d915bbd395](https://linux-hardware.org/?probe=d915bbd395) | Oct 12, 2020 |
| Lenovo        | ThinkPad T480 20L50063GE    | [8e233f307a](https://linux-hardware.org/?probe=8e233f307a) | Oct 12, 2020 |
| HP            | EliteBook 8460p             | [efecdb4bd2](https://linux-hardware.org/?probe=efecdb4bd2) | Oct 11, 2020 |
| HP            | 250 G3                      | [4bd94aaef2](https://linux-hardware.org/?probe=4bd94aaef2) | Oct 07, 2020 |
| Apple         | MacBookPro15,1              | [d1bf2547ae](https://linux-hardware.org/?probe=d1bf2547ae) | Oct 07, 2020 |
| Apple         | MacBookPro15,1              | [9782f126d8](https://linux-hardware.org/?probe=9782f126d8) | Oct 07, 2020 |
| HP            | 250 G3                      | [c4e7564fc7](https://linux-hardware.org/?probe=c4e7564fc7) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| System76      | Lemur Pro                   | [5f01c32134](https://linux-hardware.org/?probe=5f01c32134) | Oct 05, 2020 |
| Dell          | Latitude 5411               | [84fa41043c](https://linux-hardware.org/?probe=84fa41043c) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ec7ec04666](https://linux-hardware.org/?probe=ec7ec04666) | Oct 01, 2020 |
| Acer          | TravelMate B117-M           | [0d658847c1](https://linux-hardware.org/?probe=0d658847c1) | Sep 30, 2020 |
| Dell          | Latitude 3330               | [e9df98027f](https://linux-hardware.org/?probe=e9df98027f) | Sep 29, 2020 |
| System76      | Lemur Pro                   | [a364cc95e8](https://linux-hardware.org/?probe=a364cc95e8) | Sep 26, 2020 |
| HP            | Notebook                    | [07eb4784fa](https://linux-hardware.org/?probe=07eb4784fa) | Sep 20, 2020 |
| ASUSTek       | G750JZA                     | [0f045b46bd](https://linux-hardware.org/?probe=0f045b46bd) | Sep 20, 2020 |
| Medion        | P15648                      | [c135c2beeb](https://linux-hardware.org/?probe=c135c2beeb) | Sep 20, 2020 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [fe11f72b06](https://linux-hardware.org/?probe=fe11f72b06) | Sep 19, 2020 |
| HP            | 255 G7 Notebook PC          | [eee18a3d6f](https://linux-hardware.org/?probe=eee18a3d6f) | Sep 15, 2020 |
| HP            | EliteBook Folio G1          | [406bd04dda](https://linux-hardware.org/?probe=406bd04dda) | Sep 13, 2020 |
| HP            | EliteBook Folio G1          | [cfaad6c829](https://linux-hardware.org/?probe=cfaad6c829) | Sep 13, 2020 |
| Lenovo        | ThinkPad T460s 20FAS54D0... | [1906a25c9b](https://linux-hardware.org/?probe=1906a25c9b) | Sep 13, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [451f9dcbaa](https://linux-hardware.org/?probe=451f9dcbaa) | Sep 13, 2020 |
| Lenovo        | V145-15AST 81MT             | [401a915579](https://linux-hardware.org/?probe=401a915579) | Sep 10, 2020 |
| Lenovo        | ThinkPad T490 20N20048GE    | [3d81acb7a7](https://linux-hardware.org/?probe=3d81acb7a7) | Sep 08, 2020 |
| Apple         | MacBookPro15,1              | [14f7792e0d](https://linux-hardware.org/?probe=14f7792e0d) | Sep 07, 2020 |
| Lenovo        | Flex 2-14D 20376            | [42f622f899](https://linux-hardware.org/?probe=42f622f899) | Sep 06, 2020 |
| Lenovo        | Flex 2-14D 20376            | [976ebfa4ea](https://linux-hardware.org/?probe=976ebfa4ea) | Sep 06, 2020 |
| Apple         | MacBookPro9,2               | [97a1b28c1a](https://linux-hardware.org/?probe=97a1b28c1a) | Sep 06, 2020 |
| HP            | ZBook 15 G2                 | [4517259103](https://linux-hardware.org/?probe=4517259103) | Sep 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ee329db2e4](https://linux-hardware.org/?probe=ee329db2e4) | Sep 05, 2020 |
| Apple         | MacBookPro8,1               | [1a243ff587](https://linux-hardware.org/?probe=1a243ff587) | Sep 04, 2020 |
| Lenovo        | ThinkPad L470 20J4000NIX    | [a9bf3bb043](https://linux-hardware.org/?probe=a9bf3bb043) | Sep 04, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [2de7a19bf0](https://linux-hardware.org/?probe=2de7a19bf0) | Sep 02, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [9c0614c658](https://linux-hardware.org/?probe=9c0614c658) | Sep 02, 2020 |
| Medion        | E6415 MD99904               | [736d4513c4](https://linux-hardware.org/?probe=736d4513c4) | Sep 01, 2020 |
| Sony          | VPCSB4M9E                   | [7dcc858a48](https://linux-hardware.org/?probe=7dcc858a48) | Aug 31, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [540e8eb564](https://linux-hardware.org/?probe=540e8eb564) | Aug 31, 2020 |
| HP            | ProBook 445 G7              | [b8baf427ab](https://linux-hardware.org/?probe=b8baf427ab) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f462ed28f8](https://linux-hardware.org/?probe=f462ed28f8) | Aug 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8f4232f9f1](https://linux-hardware.org/?probe=8f4232f9f1) | Aug 27, 2020 |
| Apple         | MacBookPro15,1              | [7453da059c](https://linux-hardware.org/?probe=7453da059c) | Aug 25, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [b2afc4638f](https://linux-hardware.org/?probe=b2afc4638f) | Aug 24, 2020 |
| Dell          | XPS 13 9343                 | [65cff6afdc](https://linux-hardware.org/?probe=65cff6afdc) | Aug 24, 2020 |
| Apple         | MacBookPro15,1              | [be21c397d9](https://linux-hardware.org/?probe=be21c397d9) | Aug 23, 2020 |
| Apple         | MacBookPro3,1               | [dfbcd5465f](https://linux-hardware.org/?probe=dfbcd5465f) | Aug 22, 2020 |
| HP            | Pavilion g7                 | [2af3b3e46e](https://linux-hardware.org/?probe=2af3b3e46e) | Aug 21, 2020 |
| Apple         | MacBookPro15,1              | [9bfbed1a2a](https://linux-hardware.org/?probe=9bfbed1a2a) | Aug 21, 2020 |
| Apple         | MacBookPro8,1               | [de109678e9](https://linux-hardware.org/?probe=de109678e9) | Aug 19, 2020 |
| Sony          | VPCSB4M9E                   | [023b8f969c](https://linux-hardware.org/?probe=023b8f969c) | Aug 17, 2020 |
| Lenovo        | ThinkPad T61 7659AB7        | [fd1b79a95a](https://linux-hardware.org/?probe=fd1b79a95a) | Aug 15, 2020 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [b88b8f8632](https://linux-hardware.org/?probe=b88b8f8632) | Aug 13, 2020 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [d4b87a0017](https://linux-hardware.org/?probe=d4b87a0017) | Aug 13, 2020 |
| HP            | EliteBook 840 G6            | [48e5c468eb](https://linux-hardware.org/?probe=48e5c468eb) | Aug 11, 2020 |
| TUXEDO        | Book BA1510                 | [cb33d0e196](https://linux-hardware.org/?probe=cb33d0e196) | Aug 11, 2020 |
| ASUSTek       | X555LAB                     | [53f9b8a1a8](https://linux-hardware.org/?probe=53f9b8a1a8) | Aug 10, 2020 |
| Apple         | MacBookPro15,1              | [f9412036c4](https://linux-hardware.org/?probe=f9412036c4) | Aug 10, 2020 |
| HP            | 255 G3                      | [4d659eb265](https://linux-hardware.org/?probe=4d659eb265) | Aug 10, 2020 |
| Dell          | Inspiron 1012               | [f6bcf43f2d](https://linux-hardware.org/?probe=f6bcf43f2d) | Aug 10, 2020 |
| Acer          | TravelMate P256-MG          | [b87afa646c](https://linux-hardware.org/?probe=b87afa646c) | Aug 08, 2020 |
| Apple         | MacBookPro15,1              | [5cef1b9672](https://linux-hardware.org/?probe=5cef1b9672) | Aug 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3b0831d8cd](https://linux-hardware.org/?probe=3b0831d8cd) | Aug 07, 2020 |
| Lenovo        | ThinkPad W541 20EF000UGE    | [5069a399ae](https://linux-hardware.org/?probe=5069a399ae) | Aug 04, 2020 |
| Apple         | MacBookPro10,1              | [9c24d40f13](https://linux-hardware.org/?probe=9c24d40f13) | Aug 03, 2020 |
| Apple         | MacBookPro15,1              | [6cdc75b450](https://linux-hardware.org/?probe=6cdc75b450) | Jul 30, 2020 |
| Apple         | MacBookPro15,1              | [eeba18a905](https://linux-hardware.org/?probe=eeba18a905) | Jul 30, 2020 |
| Lenovo        | ThinkPad L470 20J4003WGE    | [48cd289259](https://linux-hardware.org/?probe=48cd289259) | Jul 29, 2020 |
| MSI           | P65 Creator 9SE             | [cba3c22a57](https://linux-hardware.org/?probe=cba3c22a57) | Jul 28, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c53ab8278b](https://linux-hardware.org/?probe=c53ab8278b) | Jul 27, 2020 |
| HP            | ProBook 440 G4              | [d5dd831e60](https://linux-hardware.org/?probe=d5dd831e60) | Jul 25, 2020 |
| Lenovo        | V110-15AST 80TD             | [f7ebec8b02](https://linux-hardware.org/?probe=f7ebec8b02) | Jul 25, 2020 |
| Apple         | MacBookPro15,1              | [7f8b2568b4](https://linux-hardware.org/?probe=7f8b2568b4) | Jul 18, 2020 |
| Sony          | VPCEJ2L1E                   | [2497ad55e0](https://linux-hardware.org/?probe=2497ad55e0) | Jul 17, 2020 |
| Dell          | Latitude E7450              | [81d0042be7](https://linux-hardware.org/?probe=81d0042be7) | Jul 17, 2020 |
| Apple         | MacBookPro15,1              | [f128e49c63](https://linux-hardware.org/?probe=f128e49c63) | Jul 16, 2020 |
| Apple         | MacBookPro15,1              | [8cdd0c7080](https://linux-hardware.org/?probe=8cdd0c7080) | Jul 16, 2020 |
| ASUSTek       | ZenBook UX392FA_UX392FA     | [56c9214691](https://linux-hardware.org/?probe=56c9214691) | Jul 14, 2020 |
| Lenovo        | V15-IIL 82C5                | [0b79ef9ef1](https://linux-hardware.org/?probe=0b79ef9ef1) | Jul 12, 2020 |
| HP            | 530 Notebook PC(GH634AA#... | [271e393696](https://linux-hardware.org/?probe=271e393696) | Jul 12, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [1cb4a44270](https://linux-hardware.org/?probe=1cb4a44270) | Jul 11, 2020 |
| HP            | ProBook 440 G4              | [6a65b389b0](https://linux-hardware.org/?probe=6a65b389b0) | Jul 10, 2020 |
| HP            | EliteBook 840 G2            | [c560a5a1db](https://linux-hardware.org/?probe=c560a5a1db) | Jul 10, 2020 |
| HP            | Pavilion Notebook           | [72710ffdc6](https://linux-hardware.org/?probe=72710ffdc6) | Jul 10, 2020 |
| HP            | EliteBook 840 G6            | [2aa344c383](https://linux-hardware.org/?probe=2aa344c383) | Jul 09, 2020 |
| Toshiba       | Satellite Pro A30t-C        | [02a72184b0](https://linux-hardware.org/?probe=02a72184b0) | Jul 09, 2020 |
| Notebook      | W65_W67RN,RC1,RCY           | [57db8f98a9](https://linux-hardware.org/?probe=57db8f98a9) | Jul 07, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a253e286bf](https://linux-hardware.org/?probe=a253e286bf) | Jul 06, 2020 |
| HP            | Notebook                    | [c71e280237](https://linux-hardware.org/?probe=c71e280237) | Jul 06, 2020 |
| Sony          | VPCW22M1E                   | [d2527d279c](https://linux-hardware.org/?probe=d2527d279c) | Jul 06, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| HP            | ProBook 430 G5              | [ea27ca7285](https://linux-hardware.org/?probe=ea27ca7285) | Jul 01, 2020 |
| HP            | ProBook 440 G4              | [0957532611](https://linux-hardware.org/?probe=0957532611) | Jul 01, 2020 |
| Apple         | MacBookPro15,1              | [e4d129c0d2](https://linux-hardware.org/?probe=e4d129c0d2) | Jul 01, 2020 |
| Apple         | MacBookPro15,1              | [e686fdbfb1](https://linux-hardware.org/?probe=e686fdbfb1) | Jul 01, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c2c3727c6a](https://linux-hardware.org/?probe=c2c3727c6a) | Jun 30, 2020 |
| ASUSTek       | X540LA                      | [df995fd6b3](https://linux-hardware.org/?probe=df995fd6b3) | Jun 27, 2020 |
| HP            | ProBook 440 G4              | [c60568237f](https://linux-hardware.org/?probe=c60568237f) | Jun 27, 2020 |
| Sony          | VGN-AW41MF_H                | [222b0cb3b0](https://linux-hardware.org/?probe=222b0cb3b0) | Jun 27, 2020 |
| HP            | Pavilion Notebook           | [f4b2e3494d](https://linux-hardware.org/?probe=f4b2e3494d) | Jun 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [73c01bef24](https://linux-hardware.org/?probe=73c01bef24) | Jun 23, 2020 |
| Lenovo        | ThinkPad P53 20QN000DGE     | [1ee633aa8c](https://linux-hardware.org/?probe=1ee633aa8c) | Jun 22, 2020 |
| HP            | 250 G7 Notebook PC          | [3fa7c66cb7](https://linux-hardware.org/?probe=3fa7c66cb7) | Jun 19, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a6d2c4f2e2](https://linux-hardware.org/?probe=a6d2c4f2e2) | Jun 17, 2020 |
| Acer          | Aspire E5-774G              | [f76380f497](https://linux-hardware.org/?probe=f76380f497) | Jun 17, 2020 |
| ASUSTek       | X55U                        | [139c699a3b](https://linux-hardware.org/?probe=139c699a3b) | Jun 17, 2020 |
| ASUSTek       | X55U                        | [acecf7cf92](https://linux-hardware.org/?probe=acecf7cf92) | Jun 17, 2020 |
| HP            | Notebook                    | [acd1e9f946](https://linux-hardware.org/?probe=acd1e9f946) | Jun 16, 2020 |
| Toshiba       | Satellite U920T             | [3bcf98d2cf](https://linux-hardware.org/?probe=3bcf98d2cf) | Jun 15, 2020 |
| TUXEDO        | Unknown                     | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| HP            | 250 G3                      | [f6cf1f21df](https://linux-hardware.org/?probe=f6cf1f21df) | Jun 12, 2020 |
| ASUSTek       | X550CC                      | [19c1cd0275](https://linux-hardware.org/?probe=19c1cd0275) | Jun 11, 2020 |
| Apple         | MacBookPro15,1              | [953fe94792](https://linux-hardware.org/?probe=953fe94792) | Jun 06, 2020 |
| HP            | EliteBook 2560p             | [a04fddd992](https://linux-hardware.org/?probe=a04fddd992) | Jun 05, 2020 |
| Acer          | Swift SF314-42              | [5fbd0c2b78](https://linux-hardware.org/?probe=5fbd0c2b78) | Jun 05, 2020 |
| Acer          | Swift SF314-42              | [7270fcf010](https://linux-hardware.org/?probe=7270fcf010) | Jun 05, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [bbf7b189e8](https://linux-hardware.org/?probe=bbf7b189e8) | Jun 04, 2020 |
| Lenovo        | ThinkPad T590 20N40009GE    | [c757daf95b](https://linux-hardware.org/?probe=c757daf95b) | Jun 04, 2020 |
| Lenovo        | ThinkPad T590 20N40009GE    | [55592316df](https://linux-hardware.org/?probe=55592316df) | Jun 04, 2020 |
| Medion        | E6234                       | [156d0fad52](https://linux-hardware.org/?probe=156d0fad52) | Jun 04, 2020 |
| HP            | EliteBook 2560p             | [63e8663282](https://linux-hardware.org/?probe=63e8663282) | Jun 03, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [6341aa627a](https://linux-hardware.org/?probe=6341aa627a) | Jun 01, 2020 |
| Acer          | Aspire E5-774G              | [3ace5aa3a2](https://linux-hardware.org/?probe=3ace5aa3a2) | May 31, 2020 |
| Apple         | MacBookPro15,1              | [91f82cb3f9](https://linux-hardware.org/?probe=91f82cb3f9) | May 31, 2020 |
| Apple         | MacBookPro15,1              | [8f3ca25a03](https://linux-hardware.org/?probe=8f3ca25a03) | May 31, 2020 |
| Apple         | MacBookPro15,1              | [4b8f308a9a](https://linux-hardware.org/?probe=4b8f308a9a) | May 30, 2020 |
| Lenovo        | ThinkPad T470s 20JTS0K80... | [c8512a9720](https://linux-hardware.org/?probe=c8512a9720) | May 30, 2020 |
| Lenovo        | ThinkPad T470s 20JTS0K80... | [3c1a33f98c](https://linux-hardware.org/?probe=3c1a33f98c) | May 30, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [6c69546de7](https://linux-hardware.org/?probe=6c69546de7) | May 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4aff0b33d1](https://linux-hardware.org/?probe=4aff0b33d1) | May 29, 2020 |
| Apple         | MacBookPro15,1              | [c856b73498](https://linux-hardware.org/?probe=c856b73498) | May 28, 2020 |
| HP            | OMEN by Laptop 15-dc0xxx    | [e7f2c6aaee](https://linux-hardware.org/?probe=e7f2c6aaee) | May 25, 2020 |
| ASUSTek       | K52F                        | [ce6b7f3bfb](https://linux-hardware.org/?probe=ce6b7f3bfb) | May 23, 2020 |
| HP            | ZBook 17 G5                 | [93f2b3d9a8](https://linux-hardware.org/?probe=93f2b3d9a8) | May 22, 2020 |
| HP            | 250 G7 Notebook PC          | [9db7fe5c54](https://linux-hardware.org/?probe=9db7fe5c54) | May 19, 2020 |
| HP            | 250 G7 Notebook PC          | [3f7cabee9f](https://linux-hardware.org/?probe=3f7cabee9f) | May 16, 2020 |
| Acer          | Aspire 5551G                | [013faec925](https://linux-hardware.org/?probe=013faec925) | May 16, 2020 |
| Lenovo        | IdeaPad Z360                | [fd6f7cb118](https://linux-hardware.org/?probe=fd6f7cb118) | May 15, 2020 |
| Sony          | VPCSB4M9E                   | [ee9d1561e1](https://linux-hardware.org/?probe=ee9d1561e1) | May 15, 2020 |
| Sony          | VPCSB4M9E                   | [3e4e276564](https://linux-hardware.org/?probe=3e4e276564) | May 15, 2020 |
| HP            | EliteBook 8460p             | [68f49e181f](https://linux-hardware.org/?probe=68f49e181f) | May 14, 2020 |
| HP            | Compaq 15                   | [8362ccc50e](https://linux-hardware.org/?probe=8362ccc50e) | May 14, 2020 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [b60c49bd7d](https://linux-hardware.org/?probe=b60c49bd7d) | May 13, 2020 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [2a491de495](https://linux-hardware.org/?probe=2a491de495) | May 13, 2020 |
| HP            | ProBook 450 G2              | [4851e2f3ff](https://linux-hardware.org/?probe=4851e2f3ff) | May 11, 2020 |
| Dell          | XPS 15 7590                 | [3526843e9f](https://linux-hardware.org/?probe=3526843e9f) | May 10, 2020 |
| HP            | EliteBook 2560p             | [d738b6165b](https://linux-hardware.org/?probe=d738b6165b) | May 09, 2020 |
| Lenovo        | Z710 20250                  | [40527a10da](https://linux-hardware.org/?probe=40527a10da) | May 09, 2020 |
| Lenovo        | IdeaPad Z360                | [68d24fa190](https://linux-hardware.org/?probe=68d24fa190) | May 07, 2020 |
| Lenovo        | ThinkPad X201 Tablet 309... | [49c9895e09](https://linux-hardware.org/?probe=49c9895e09) | May 07, 2020 |
| Lenovo        | ThinkPad X201 Tablet 309... | [e3bbc139a1](https://linux-hardware.org/?probe=e3bbc139a1) | May 06, 2020 |
| HP            | Pavilion dv6                | [a797799780](https://linux-hardware.org/?probe=a797799780) | May 06, 2020 |
| Lenovo        | ThinkPad T400 6475V8J       | [891f806dbf](https://linux-hardware.org/?probe=891f806dbf) | May 05, 2020 |
| Lenovo        | U310                        | [173c832aac](https://linux-hardware.org/?probe=173c832aac) | May 05, 2020 |
| Lenovo        | Z710 20250                  | [90f5ccee90](https://linux-hardware.org/?probe=90f5ccee90) | May 04, 2020 |
| HP            | EliteBook 830 G5            | [1c5b9e257f](https://linux-hardware.org/?probe=1c5b9e257f) | May 04, 2020 |
| HP            | EliteBook 2530p             | [11361df5c1](https://linux-hardware.org/?probe=11361df5c1) | May 04, 2020 |
| Timi          | TM1701                      | [dce301507a](https://linux-hardware.org/?probe=dce301507a) | May 03, 2020 |
| Dell          | XPS 13 9343                 | [0c0460401a](https://linux-hardware.org/?probe=0c0460401a) | May 02, 2020 |
| Lenovo        | V155-15API 81V5             | [07ecad57e1](https://linux-hardware.org/?probe=07ecad57e1) | May 02, 2020 |
| Acer          | Predator PH317-52           | [d5d4771606](https://linux-hardware.org/?probe=d5d4771606) | May 02, 2020 |
| Timi          | TM1701                      | [2c0cd9b7cf](https://linux-hardware.org/?probe=2c0cd9b7cf) | May 02, 2020 |
| Lenovo        | ThinkPad E470 20H2S00700    | [5509ae8eb8](https://linux-hardware.org/?probe=5509ae8eb8) | Apr 30, 2020 |
| HP            | ZBook 17 G5                 | [222fb4f26b](https://linux-hardware.org/?probe=222fb4f26b) | Apr 29, 2020 |
| HP            | EliteBook 6930p             | [72e7230b26](https://linux-hardware.org/?probe=72e7230b26) | Apr 28, 2020 |
| HP            | ProBook 430 G5              | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| Lenovo        | V155-15API 81V5             | [eaa6cfe3a1](https://linux-hardware.org/?probe=eaa6cfe3a1) | Apr 27, 2020 |
| HP            | 250 G3                      | [77a826318e](https://linux-hardware.org/?probe=77a826318e) | Apr 27, 2020 |
| HP            | EliteBook 840 G5            | [25a57d9328](https://linux-hardware.org/?probe=25a57d9328) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| ASUSTek       | K52F                        | [4592f833fa](https://linux-hardware.org/?probe=4592f833fa) | Apr 26, 2020 |
| HP            | ProBook 470 G5              | [14762c7fc9](https://linux-hardware.org/?probe=14762c7fc9) | Apr 26, 2020 |
| Lenovo        | ThinkPad T400 6475V8J       | [ac93664dd5](https://linux-hardware.org/?probe=ac93664dd5) | Apr 25, 2020 |
| HP            | EliteBook 8560p             | [7fe6ce5446](https://linux-hardware.org/?probe=7fe6ce5446) | Apr 24, 2020 |
| Dell          | XPS 15 9570                 | [d2d9a88841](https://linux-hardware.org/?probe=d2d9a88841) | Apr 23, 2020 |
| HP            | 250 G3                      | [e58e824d1e](https://linux-hardware.org/?probe=e58e824d1e) | Apr 23, 2020 |
| HP            | Presario CQ62               | [89ec142930](https://linux-hardware.org/?probe=89ec142930) | Apr 22, 2020 |
| Dell          | Inspiron 1720               | [5bbab2bc27](https://linux-hardware.org/?probe=5bbab2bc27) | Apr 21, 2020 |
| HP            | Pavilion dv6                | [c87812f0b6](https://linux-hardware.org/?probe=c87812f0b6) | Apr 19, 2020 |
| Lenovo        | ThinkPad X230 2325E58       | [115a7cb6e8](https://linux-hardware.org/?probe=115a7cb6e8) | Apr 19, 2020 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [15a9d81427](https://linux-hardware.org/?probe=15a9d81427) | Apr 18, 2020 |
| HP            | Pavilion g6                 | [75a149c376](https://linux-hardware.org/?probe=75a149c376) | Apr 18, 2020 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [0f324eff93](https://linux-hardware.org/?probe=0f324eff93) | Apr 15, 2020 |
| HP            | ZBook 17 G5                 | [19a267ec38](https://linux-hardware.org/?probe=19a267ec38) | Apr 15, 2020 |
| Dell          | Inspiron 1370               | [c7ec016f28](https://linux-hardware.org/?probe=c7ec016f28) | Apr 13, 2020 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [dab9ed3a88](https://linux-hardware.org/?probe=dab9ed3a88) | Apr 12, 2020 |
| Samsung       | 900X3C/900X4C/900X4D        | [c3727b56fe](https://linux-hardware.org/?probe=c3727b56fe) | Apr 11, 2020 |
| Dell          | Latitude 5591               | [0a0cc321d5](https://linux-hardware.org/?probe=0a0cc321d5) | Apr 10, 2020 |
| Fujitsu Si... | LIFEBOOK S7210              | [83ef7b016e](https://linux-hardware.org/?probe=83ef7b016e) | Apr 08, 2020 |
| Acer          | Aspire 7720Z                | [53bced64ee](https://linux-hardware.org/?probe=53bced64ee) | Apr 08, 2020 |
| Samsung       | 275E4E/275E5E               | [42334085a3](https://linux-hardware.org/?probe=42334085a3) | Apr 07, 2020 |
| Sony          | VPCEJ2Z1E                   | [8644050307](https://linux-hardware.org/?probe=8644050307) | Apr 07, 2020 |
| Sony          | VPCEJ2Z1E                   | [d2f25d33cd](https://linux-hardware.org/?probe=d2f25d33cd) | Apr 07, 2020 |
| TWJ           | Unknown                     | [46d5d76af1](https://linux-hardware.org/?probe=46d5d76af1) | Apr 05, 2020 |
| TWJ           | Unknown                     | [ff50430fcf](https://linux-hardware.org/?probe=ff50430fcf) | Apr 05, 2020 |
| Acer          | Aspire A315-41              | [ec505d4ab7](https://linux-hardware.org/?probe=ec505d4ab7) | Apr 02, 2020 |
| HP            | EliteBook 8540p             | [8a7018aba0](https://linux-hardware.org/?probe=8a7018aba0) | Apr 01, 2020 |
| Dell          | Inspiron MM061              | [81c8f6a88f](https://linux-hardware.org/?probe=81c8f6a88f) | Mar 31, 2020 |
| Dell          | Inspiron MM061              | [ec58223171](https://linux-hardware.org/?probe=ec58223171) | Mar 31, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [cea75ac44a](https://linux-hardware.org/?probe=cea75ac44a) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | [59c568e03a](https://linux-hardware.org/?probe=59c568e03a) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | [592d008d70](https://linux-hardware.org/?probe=592d008d70) | Mar 30, 2020 |
| MAXDATA       | obook3-2                    | [1fcc44c107](https://linux-hardware.org/?probe=1fcc44c107) | Mar 29, 2020 |
| MAXDATA       | obook3-2                    | [96f3fa6a9a](https://linux-hardware.org/?probe=96f3fa6a9a) | Mar 29, 2020 |
| HP            | Laptop 15-bw0xx             | [711444c9be](https://linux-hardware.org/?probe=711444c9be) | Mar 28, 2020 |
| Lenovo        | ThinkPad T480 20L50063GE    | [02a6eb697c](https://linux-hardware.org/?probe=02a6eb697c) | Mar 25, 2020 |
| HP            | ProBook 470 G5              | [e9c424a2bc](https://linux-hardware.org/?probe=e9c424a2bc) | Mar 22, 2020 |
| Sony          | VGN-FE21M                   | [b117ba3f2f](https://linux-hardware.org/?probe=b117ba3f2f) | Mar 22, 2020 |
| Acer          | Aspire A315-53              | [41cb001222](https://linux-hardware.org/?probe=41cb001222) | Mar 22, 2020 |
| ASUSTek       | X75A1                       | [6b38c604cc](https://linux-hardware.org/?probe=6b38c604cc) | Mar 21, 2020 |
| Dell          | Latitude 5401               | [224f10a741](https://linux-hardware.org/?probe=224f10a741) | Mar 21, 2020 |
| ASUSTek       | R11CX                       | [680a4502f2](https://linux-hardware.org/?probe=680a4502f2) | Mar 19, 2020 |
| ASUSTek       | R11CX                       | [36a803af0b](https://linux-hardware.org/?probe=36a803af0b) | Mar 19, 2020 |
| Lenovo        | B50-70 80EU                 | [32162d2fcb](https://linux-hardware.org/?probe=32162d2fcb) | Mar 19, 2020 |
| HP            | OMEN by Laptop 17-cb0xxx    | [a42a77029d](https://linux-hardware.org/?probe=a42a77029d) | Mar 18, 2020 |
| Toshiba       | Satellite C50D-B            | [7ff86aad0f](https://linux-hardware.org/?probe=7ff86aad0f) | Mar 12, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [7089e13229](https://linux-hardware.org/?probe=7089e13229) | Mar 11, 2020 |
| ASUSTek       | X55VD                       | [bde6829542](https://linux-hardware.org/?probe=bde6829542) | Mar 10, 2020 |
| Lenovo        | ThinkPad T490s 20NX000AG... | [0ea72326af](https://linux-hardware.org/?probe=0ea72326af) | Mar 01, 2020 |
| Lenovo        | ThinkPad T490s 20NX000AG... | [73cbe94499](https://linux-hardware.org/?probe=73cbe94499) | Feb 29, 2020 |
| HP            | ProBook 450 G6              | [646e94e305](https://linux-hardware.org/?probe=646e94e305) | Feb 28, 2020 |
| HP            | EliteBook 2760p             | [4d734200ca](https://linux-hardware.org/?probe=4d734200ca) | Feb 28, 2020 |
| ASUSTek       | GL702ZC                     | [817c286851](https://linux-hardware.org/?probe=817c286851) | Feb 28, 2020 |
| Wortmann      | TERRA_MOBILE_1160           | [bff33cd85b](https://linux-hardware.org/?probe=bff33cd85b) | Feb 26, 2020 |
| Dell          | Precision 5510              | [97fdd683cd](https://linux-hardware.org/?probe=97fdd683cd) | Feb 23, 2020 |
| HP            | ProBook 430 G3              | [5b2b1ad074](https://linux-hardware.org/?probe=5b2b1ad074) | Feb 09, 2020 |
| HP            | ProBook 430 G3              | [81716ad04d](https://linux-hardware.org/?probe=81716ad04d) | Feb 09, 2020 |
| Medion        | E7424 MD60150               | [36d0eb9930](https://linux-hardware.org/?probe=36d0eb9930) | Feb 08, 2020 |
| Acer          | Aspire ES1-533              | [66f8cf847e](https://linux-hardware.org/?probe=66f8cf847e) | Feb 08, 2020 |
| HP            | Pavilion g7                 | [06c947fb4e](https://linux-hardware.org/?probe=06c947fb4e) | Feb 02, 2020 |
| HP            | G62                         | [b0bf4c0a3a](https://linux-hardware.org/?probe=b0bf4c0a3a) | Feb 02, 2020 |
| ASUSTek       | GL702ZC                     | [97b6716f79](https://linux-hardware.org/?probe=97b6716f79) | Feb 02, 2020 |
| TrekStor      | Notebook Slim S130          | [e0e1b59385](https://linux-hardware.org/?probe=e0e1b59385) | Feb 01, 2020 |
| Acer          | Aspire A515-51G             | [82087e8762](https://linux-hardware.org/?probe=82087e8762) | Jan 31, 2020 |
| HP            | Pavilion dv7                | [43cbdc89e1](https://linux-hardware.org/?probe=43cbdc89e1) | Jan 30, 2020 |
| Acer          | Aspire VN7-571G             | [9e5a133e04](https://linux-hardware.org/?probe=9e5a133e04) | Jan 29, 2020 |
| HP            | Pavilion dv6                | [b8f388d4f8](https://linux-hardware.org/?probe=b8f388d4f8) | Jan 29, 2020 |
| HP            | EliteBook 840 G6            | [648a5ff1d0](https://linux-hardware.org/?probe=648a5ff1d0) | Jan 28, 2020 |
| Clevo         | P15xEMx                     | [93f424b7a8](https://linux-hardware.org/?probe=93f424b7a8) | Jan 27, 2020 |
| Toshiba       | Satellite C70D-B            | [d2f8e9ac26](https://linux-hardware.org/?probe=d2f8e9ac26) | Jan 26, 2020 |
| Toshiba       | Satellite C70D-B            | [8f8cdb2cb8](https://linux-hardware.org/?probe=8f8cdb2cb8) | Jan 26, 2020 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [799f73dcd0](https://linux-hardware.org/?probe=799f73dcd0) | Jan 26, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [4e73bb136f](https://linux-hardware.org/?probe=4e73bb136f) | Jan 25, 2020 |
| TUXEDO        | P65_67HSHP                  | [5b33c37e09](https://linux-hardware.org/?probe=5b33c37e09) | Jan 24, 2020 |
| Fujitsu       | LIFEBOOK S761               | [102025c163](https://linux-hardware.org/?probe=102025c163) | Jan 24, 2020 |
| HP            | EliteBook 830 G5            | [810e2a2abb](https://linux-hardware.org/?probe=810e2a2abb) | Jan 23, 2020 |
| Toshiba       | NB550D                      | [ad15454dbc](https://linux-hardware.org/?probe=ad15454dbc) | Jan 22, 2020 |
| Dell          | Latitude E7450              | [be13083547](https://linux-hardware.org/?probe=be13083547) | Jan 19, 2020 |
| HP            | EliteBook 840 G6            | [92c6683381](https://linux-hardware.org/?probe=92c6683381) | Jan 18, 2020 |
| Dell          | XPS 13 9360                 | [f7d14c4931](https://linux-hardware.org/?probe=f7d14c4931) | Jan 18, 2020 |
| Lenovo        | IdeaPad U160 08946JG        | [2e1af2c46b](https://linux-hardware.org/?probe=2e1af2c46b) | Jan 16, 2020 |
| Acer          | Aspire A515-51G             | [3ee2771816](https://linux-hardware.org/?probe=3ee2771816) | Jan 16, 2020 |
| Dell          | XPS 13 9360                 | [afdd4a5e1b](https://linux-hardware.org/?probe=afdd4a5e1b) | Jan 15, 2020 |
| Acer          | Aspire A515-51G             | [e127d6cf0c](https://linux-hardware.org/?probe=e127d6cf0c) | Jan 14, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| Acer          | Aspire A515-51G             | [1af5b38f97](https://linux-hardware.org/?probe=1af5b38f97) | Jan 11, 2020 |
| TUXEDO        | P64_HJ,HK1                  | [62ed55a7e5](https://linux-hardware.org/?probe=62ed55a7e5) | Jan 10, 2020 |
| Medion        | P6669 MD60147               | [b857f2b82d](https://linux-hardware.org/?probe=b857f2b82d) | Jan 07, 2020 |
| TUXEDO        | P64_HJ,HK1                  | [125e1bc57d](https://linux-hardware.org/?probe=125e1bc57d) | Jan 07, 2020 |
| HP            | EliteBook 8570p             | [a5fbe34a20](https://linux-hardware.org/?probe=a5fbe34a20) | Jan 05, 2020 |
| HP            | EliteBook 8570p             | [136c747313](https://linux-hardware.org/?probe=136c747313) | Jan 05, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [fc9febf992](https://linux-hardware.org/?probe=fc9febf992) | Jan 05, 2020 |
| HP            | ProBook 4530s               | [40d2daa855](https://linux-hardware.org/?probe=40d2daa855) | Jan 04, 2020 |
| Lenovo        | ThinkPad X130e 0627RZ4      | [5a21476ee9](https://linux-hardware.org/?probe=5a21476ee9) | Jan 02, 2020 |
| Acer          | Aspire 5630                 | [aa7a1a4557](https://linux-hardware.org/?probe=aa7a1a4557) | Jan 02, 2020 |
| HP            | EliteBook 8570p             | [2d62efe070](https://linux-hardware.org/?probe=2d62efe070) | Jan 02, 2020 |
| Acer          | Aspire E5-771G              | [b2b052a122](https://linux-hardware.org/?probe=b2b052a122) | Jan 01, 2020 |
| Lenovo        | ThinkPad T530 2429MA6       | [058b964895](https://linux-hardware.org/?probe=058b964895) | Jan 01, 2020 |
| Acer          | Aspire E5-771G              | [530ec1c7c2](https://linux-hardware.org/?probe=530ec1c7c2) | Dec 28, 2019 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [c7b4c5a204](https://linux-hardware.org/?probe=c7b4c5a204) | Dec 27, 2019 |
| ASUSTek       | K73SV                       | [af47b62f54](https://linux-hardware.org/?probe=af47b62f54) | Dec 26, 2019 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [105fe15441](https://linux-hardware.org/?probe=105fe15441) | Dec 25, 2019 |
| Acer          | TravelMate B117-M           | [283c5fd2d1](https://linux-hardware.org/?probe=283c5fd2d1) | Dec 23, 2019 |
| ASUSTek       | ZenBook UX392FA_UX392FA     | [906bcfc089](https://linux-hardware.org/?probe=906bcfc089) | Dec 17, 2019 |
| Lenovo        | ThinkPad T530 2429MA6       | [d0b40a5be3](https://linux-hardware.org/?probe=d0b40a5be3) | Dec 15, 2019 |
| Lenovo        | ThinkPad T530 2429MA6       | [378d4fca97](https://linux-hardware.org/?probe=378d4fca97) | Dec 15, 2019 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [388abffcbb](https://linux-hardware.org/?probe=388abffcbb) | Dec 11, 2019 |
| Dell          | XPS 13 9360                 | [a767963691](https://linux-hardware.org/?probe=a767963691) | Dec 09, 2019 |
| ASUSTek       | 1001PX                      | [e368a28816](https://linux-hardware.org/?probe=e368a28816) | Dec 04, 2019 |
| Dell          | Latitude E6230              | [ffcb01d534](https://linux-hardware.org/?probe=ffcb01d534) | Dec 03, 2019 |
| Dell          | Latitude E6230              | [8a56a952ee](https://linux-hardware.org/?probe=8a56a952ee) | Dec 03, 2019 |
| Toshiba       | Satellite C70D-B            | [4b9e002f83](https://linux-hardware.org/?probe=4b9e002f83) | Dec 01, 2019 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [d30516dd82](https://linux-hardware.org/?probe=d30516dd82) | Nov 28, 2019 |
| Lenovo        | ThinkPad P43s 20RHS03V00    | [e80ae71bd7](https://linux-hardware.org/?probe=e80ae71bd7) | Nov 27, 2019 |
| HP            | TouchSmart tm2              | [7476027d6d](https://linux-hardware.org/?probe=7476027d6d) | Nov 24, 2019 |
| HP            | Laptop 17-bs0xx             | [989461cca6](https://linux-hardware.org/?probe=989461cca6) | Nov 20, 2019 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [2d27b12d67](https://linux-hardware.org/?probe=2d27b12d67) | Nov 17, 2019 |
| Lenovo        | ACLU12                      | [6e6e5e6fba](https://linux-hardware.org/?probe=6e6e5e6fba) | Nov 16, 2019 |
| Lenovo        | V145-15AST 81MT             | [665488fd10](https://linux-hardware.org/?probe=665488fd10) | Nov 16, 2019 |
| Acer          | Chapala                     | [6194d1a664](https://linux-hardware.org/?probe=6194d1a664) | Nov 10, 2019 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [1c5178fffa](https://linux-hardware.org/?probe=1c5178fffa) | Nov 03, 2019 |
| Toshiba       | Satellite L50-B             | [8f2d33cb2f](https://linux-hardware.org/?probe=8f2d33cb2f) | Nov 02, 2019 |
| Medion        | E7424 MD60150               | [34b9d4fd1d](https://linux-hardware.org/?probe=34b9d4fd1d) | Nov 01, 2019 |
| Medion        | E7424 MD60150               | [9328927899](https://linux-hardware.org/?probe=9328927899) | Nov 01, 2019 |
| Lenovo        | ThinkPad T430 2349QM6       | [70493b615b](https://linux-hardware.org/?probe=70493b615b) | Oct 30, 2019 |
| Lenovo        | ThinkPad L440 20AT002YGE    | [2967de1dd6](https://linux-hardware.org/?probe=2967de1dd6) | Oct 25, 2019 |
| Dell          | Vostro 5471                 | [87df9cdfd4](https://linux-hardware.org/?probe=87df9cdfd4) | Oct 20, 2019 |
| Sony          | VPCEC1M1E                   | [b5e705dc9c](https://linux-hardware.org/?probe=b5e705dc9c) | Oct 19, 2019 |
| Acer          | Aspire ES1-732              | [5d07941304](https://linux-hardware.org/?probe=5d07941304) | Oct 18, 2019 |
| Acer          | Aspire A517-51G             | [2beeb73a87](https://linux-hardware.org/?probe=2beeb73a87) | Oct 18, 2019 |
| HP            | EliteBook 830 G6            | [29db415451](https://linux-hardware.org/?probe=29db415451) | Oct 08, 2019 |
| Lenovo        | ThinkPad X220 Tablet 429... | [4aae34be82](https://linux-hardware.org/?probe=4aae34be82) | Oct 04, 2019 |
| ASUSTek       | X540LA                      | [297d35f1b7](https://linux-hardware.org/?probe=297d35f1b7) | Sep 29, 2019 |
| Lenovo        | ThinkPad X220 Tablet 429... | [df153af585](https://linux-hardware.org/?probe=df153af585) | Sep 21, 2019 |
| Fujitsu       | LIFEBOOK T935               | [499fa73439](https://linux-hardware.org/?probe=499fa73439) | Sep 17, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [23cd76118d](https://linux-hardware.org/?probe=23cd76118d) | Sep 13, 2019 |
| Lenovo        | Yoga 300-11IBY 80M0         | [eef734b471](https://linux-hardware.org/?probe=eef734b471) | Sep 10, 2019 |
| ASUSTek       | 1001PG                      | [2d7b5f4727](https://linux-hardware.org/?probe=2d7b5f4727) | Sep 05, 2019 |
| Lenovo        | G500s 20245                 | [0cb00a3267](https://linux-hardware.org/?probe=0cb00a3267) | Sep 04, 2019 |
| Lenovo        | G500s 20245                 | [240ff6331a](https://linux-hardware.org/?probe=240ff6331a) | Sep 04, 2019 |
| HP            | EliteBook 830 G5            | [2da46102bd](https://linux-hardware.org/?probe=2da46102bd) | Sep 01, 2019 |
| HUAWEI        | KPL-W0X                     | [1aa481c976](https://linux-hardware.org/?probe=1aa481c976) | Sep 01, 2019 |
| Lenovo        | ThinkPad T400 6475L16       | [69f007d21a](https://linux-hardware.org/?probe=69f007d21a) | Aug 30, 2019 |
| Sony          | SVE1713F1EW                 | [4a962f6e93](https://linux-hardware.org/?probe=4a962f6e93) | Aug 25, 2019 |
| Dell          | Inspiron 5570               | [793a2320a1](https://linux-hardware.org/?probe=793a2320a1) | Aug 14, 2019 |
| Lenovo        | ThinkPad T420 4236Z9L       | [61770bf8d4](https://linux-hardware.org/?probe=61770bf8d4) | Aug 11, 2019 |
| Sony          | VPCEH2Q1E                   | [0602df6740](https://linux-hardware.org/?probe=0602df6740) | Aug 10, 2019 |
| GPD           | MicroPC                     | [19516bca1b](https://linux-hardware.org/?probe=19516bca1b) | Aug 07, 2019 |
| HP            | EliteBook 820 G2            | [33413be6e3](https://linux-hardware.org/?probe=33413be6e3) | Aug 04, 2019 |
| HP            | EliteBook 820 G2            | [bd821c28ea](https://linux-hardware.org/?probe=bd821c28ea) | Aug 04, 2019 |
| Unknown       | S16                         | [5ea1f0f406](https://linux-hardware.org/?probe=5ea1f0f406) | Aug 02, 2019 |
| Fujitsu       | LIFEBOOK S761               | [8f2e060d39](https://linux-hardware.org/?probe=8f2e060d39) | Jul 27, 2019 |
| Apple         | MacBookPro7,1               | [80ecbde76e](https://linux-hardware.org/?probe=80ecbde76e) | Jul 24, 2019 |
| Apple         | MacBookPro7,1               | [370f74d97a](https://linux-hardware.org/?probe=370f74d97a) | Jul 19, 2019 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [93d5c57ffc](https://linux-hardware.org/?probe=93d5c57ffc) | Jul 18, 2019 |
| Dell          | Precision 7510              | [5e0dc6dfa3](https://linux-hardware.org/?probe=5e0dc6dfa3) | Jul 14, 2019 |
| Dell          | Inspiron 1720               | [aef28a0d3b](https://linux-hardware.org/?probe=aef28a0d3b) | Jun 18, 2019 |
| HP            | EliteBook 840 G1            | [947db57348](https://linux-hardware.org/?probe=947db57348) | Jun 15, 2019 |
| Acer          | Aspire ES1-732              | [468c52188e](https://linux-hardware.org/?probe=468c52188e) | Jun 12, 2019 |
| Lenovo        | ThinkPad T450s 20BWS1UT0... | [d2d5d46b97](https://linux-hardware.org/?probe=d2d5d46b97) | May 20, 2019 |
| Lenovo        | ThinkPad X270 20HN0016GE    | [5e61c7e6ce](https://linux-hardware.org/?probe=5e61c7e6ce) | May 16, 2019 |
| HP            | Pavilion 15                 | [d63356c82a](https://linux-hardware.org/?probe=d63356c82a) | May 13, 2019 |
| Lenovo        | ThinkPad X230 23258R6       | [db80cd572d](https://linux-hardware.org/?probe=db80cd572d) | May 10, 2019 |
| Lenovo        | ThinkPad X230 23258R6       | [edeacb2c5c](https://linux-hardware.org/?probe=edeacb2c5c) | May 10, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [be51dd82dd](https://linux-hardware.org/?probe=be51dd82dd) | May 05, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6061d04eb0](https://linux-hardware.org/?probe=6061d04eb0) | May 03, 2019 |
| Acer          | TravelMate P253             | [9b10195ee4](https://linux-hardware.org/?probe=9b10195ee4) | May 02, 2019 |
| Acer          | Aspire V3-772G              | [5e6c7af841](https://linux-hardware.org/?probe=5e6c7af841) | Apr 16, 2019 |
| HP            | 15                          | [e67aff9f7d](https://linux-hardware.org/?probe=e67aff9f7d) | Apr 12, 2019 |
| HP            | Laptop 15-db0xxx            | [84a78d0a9a](https://linux-hardware.org/?probe=84a78d0a9a) | Mar 31, 2019 |
| HP            | 250 G6 Notebook PC          | [611f91e78e](https://linux-hardware.org/?probe=611f91e78e) | Mar 30, 2019 |
| Acer          | Aspire ES1-531              | [385b05150a](https://linux-hardware.org/?probe=385b05150a) | Mar 27, 2019 |
| ASUSTek       | X555UF                      | [f0b293c2ec](https://linux-hardware.org/?probe=f0b293c2ec) | Mar 27, 2019 |
| Lenovo        | ThinkPad T430 2349I62       | [fec4621cc7](https://linux-hardware.org/?probe=fec4621cc7) | Mar 26, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [01f45660b6](https://linux-hardware.org/?probe=01f45660b6) | Mar 13, 2019 |
| HP            | EliteBook 830 G5            | [ece59b9429](https://linux-hardware.org/?probe=ece59b9429) | Mar 01, 2019 |
| HP            | EliteBook 830 G5            | [26bd1d2a99](https://linux-hardware.org/?probe=26bd1d2a99) | Feb 25, 2019 |
| Lenovo        | ThinkPad W530 24475HG       | [d1f8ec4125](https://linux-hardware.org/?probe=d1f8ec4125) | Feb 11, 2019 |
| Acer          | Aspire ES1-732              | [866131a1c5](https://linux-hardware.org/?probe=866131a1c5) | Feb 04, 2019 |
| Lenovo        | ThinkPad W530 244723G       | [2081f42b97](https://linux-hardware.org/?probe=2081f42b97) | Jan 22, 2019 |
| Dell          | Latitude E4300              | [8b31b50bca](https://linux-hardware.org/?probe=8b31b50bca) | Dec 11, 2018 |
| Fujitsu       | LIFEBOOK T935               | [5c425e246f](https://linux-hardware.org/?probe=5c425e246f) | Dec 07, 2018 |
| Fujitsu       | LIFEBOOK T935               | [f95e23374a](https://linux-hardware.org/?probe=f95e23374a) | Dec 07, 2018 |
| Lenovo        | ThinkPad X220 4287CTO       | [49b0278321](https://linux-hardware.org/?probe=49b0278321) | Dec 06, 2018 |
| ASUSTek       | N55SL                       | [4bc4cee1b4](https://linux-hardware.org/?probe=4bc4cee1b4) | Nov 29, 2018 |
| ASUSTek       | N55SL                       | [13d9ae4033](https://linux-hardware.org/?probe=13d9ae4033) | Nov 29, 2018 |
| Dell          | Latitude E4300              | [e4c63a4b0f](https://linux-hardware.org/?probe=e4c63a4b0f) | Nov 28, 2018 |
| Dell          | Latitude E4300              | [5f76e9a3c9](https://linux-hardware.org/?probe=5f76e9a3c9) | Nov 28, 2018 |
| Dell          | Latitude E4300              | [c1256d74fd](https://linux-hardware.org/?probe=c1256d74fd) | Nov 27, 2018 |
| Dell          | Latitude E4300              | [d36ec8c712](https://linux-hardware.org/?probe=d36ec8c712) | Nov 27, 2018 |
| HP            | EliteBook 6930p             | [b5b4de22fd](https://linux-hardware.org/?probe=b5b4de22fd) | Nov 21, 2018 |
| Acer          | AOD257                      | [75e7a270d1](https://linux-hardware.org/?probe=75e7a270d1) | Nov 14, 2018 |
| eMachines     | G725                        | [a0ee7316ab](https://linux-hardware.org/?probe=a0ee7316ab) | Nov 09, 2018 |
| Dell          | Inspiron 3537               | [73aeec9a31](https://linux-hardware.org/?probe=73aeec9a31) | Nov 09, 2018 |
| HP            | EliteBook 6930p             | [b84097fdeb](https://linux-hardware.org/?probe=b84097fdeb) | Nov 06, 2018 |
| Lenovo        | ThinkPad X1 Carbon 3460B... | [b7014678b5](https://linux-hardware.org/?probe=b7014678b5) | Oct 30, 2018 |
| Lenovo        | ThinkPad T470 20HD002HGE    | [ea8f4068e3](https://linux-hardware.org/?probe=ea8f4068e3) | Oct 17, 2018 |
| Dell          | Latitude E7440              | [01acdf416a](https://linux-hardware.org/?probe=01acdf416a) | Sep 10, 2018 |
| Lenovo        | ThinkPad 13 20GJ0048GE      | [346bcc6617](https://linux-hardware.org/?probe=346bcc6617) | Aug 25, 2018 |
| Dell          | Latitude E7440              | [68b06fc22d](https://linux-hardware.org/?probe=68b06fc22d) | Aug 19, 2018 |
| Dell          | Latitude E7440              | [31a3d95275](https://linux-hardware.org/?probe=31a3d95275) | Aug 17, 2018 |
| HP            | EliteBook 840 G3            | [7ad7251488](https://linux-hardware.org/?probe=7ad7251488) | Jul 08, 2018 |
| HP            | EliteBook 840 G3            | [d170dcb3a8](https://linux-hardware.org/?probe=d170dcb3a8) | Jul 08, 2018 |
| ASUSTek       | N752VX                      | [2e12c0bdb2](https://linux-hardware.org/?probe=2e12c0bdb2) | Jun 22, 2018 |
| Lenovo        | ThinkPad X270 20HN0014HV    | [bc47c0b75b](https://linux-hardware.org/?probe=bc47c0b75b) | Jun 21, 2018 |
| Samsung       | RC530/RC730                 | [c33c8ba4e4](https://linux-hardware.org/?probe=c33c8ba4e4) | Apr 09, 2018 |
| HP            | EliteBook 8570w             | [1a2050b00f](https://linux-hardware.org/?probe=1a2050b00f) | Mar 24, 2018 |
| HP            | EliteBook 8570w             | [2baf3cf792](https://linux-hardware.org/?probe=2baf3cf792) | Mar 21, 2018 |
| HP            | EliteBook 8570w             | [3acf80fd4a](https://linux-hardware.org/?probe=3acf80fd4a) | Mar 13, 2018 |
| ASUSTek       | BU201LA                     | [740c1d3cbf](https://linux-hardware.org/?probe=740c1d3cbf) | Dec 29, 2017 |
| ASUSTek       | G752VSK                     | [c6173b38b7](https://linux-hardware.org/?probe=c6173b38b7) | Aug 24, 2017 |
| ASUSTek       | X202EP                      | [4d608145e3](https://linux-hardware.org/?probe=4d608145e3) | May 24, 2017 |
| Toshiba       | Satellite Pro L770-116      | [a41af6606a](https://linux-hardware.org/?probe=a41af6606a) | Apr 09, 2017 |
| Lenovo        | ThinkPad X230 23252CG       | [c684f1cb0e](https://linux-hardware.org/?probe=c684f1cb0e) | Nov 30, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 136       | 18.16%  |
| Ubuntu 18.04                 | 60        | 8.01%   |
| Linux Mint 20.2              | 27        | 3.6%    |
| Arch                         | 21        | 2.8%    |
| BlackPanther 18.1            | 19        | 2.54%   |
| Linux Mint 20.1              | 17        | 2.27%   |
| Fedora 35                    | 17        | 2.27%   |
| Ubuntu 21.04                 | 16        | 2.14%   |
| OpenMandriva 4.3             | 16        | 2.14%   |
| Arch Rolling                 | 15        | 2%      |
| Zorin 16                     | 14        | 1.87%   |
| Manjaro                      | 14        | 1.87%   |
| Linux Mint 19.3              | 14        | 1.87%   |
| Fedora 33                    | 14        | 1.87%   |
| Ubuntu 19.10                 | 13        | 1.74%   |
| Debian 11                    | 13        | 1.74%   |
| Ubuntu 21.10                 | 12        | 1.6%    |
| KDE neon 20.04               | 12        | 1.6%    |
| OpenMandriva 4.2             | 11        | 1.47%   |
| Fedora 32                    | 11        | 1.47%   |
| Fedora 34                    | 10        | 1.34%   |
| Pop!_OS 21.04                | 9         | 1.2%    |
| Zorin 15                     | 8         | 1.07%   |
| Ubuntu 20.10                 | 8         | 1.07%   |
| Pop!_OS 20.04                | 8         | 1.07%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 1.07%   |
| Ubuntu 19.04                 | 7         | 0.93%   |
| Linux Mint 20                | 7         | 0.93%   |
| Xubuntu 20.04                | 6         | 0.8%    |
| Ubuntu 16.04                 | 6         | 0.8%    |
| Pop!_OS 20.10                | 6         | 0.8%    |
| Ubuntu 22.04                 | 5         | 0.67%   |
| ROSA R10                     | 5         | 0.67%   |
| Linux Mint 20.3              | 5         | 0.67%   |
| MX 19                        | 4         | 0.53%   |
| Manjaro 20.0.3               | 4         | 0.53%   |
| Linux Mint 19                | 4         | 0.53%   |
| Fedora 36                    | 4         | 0.53%   |
| Fedora 31                    | 4         | 0.53%   |
| Elementary 6.1               | 4         | 0.53%   |
| Debian Testing               | 4         | 0.53%   |
| Ubuntu 18.10                 | 3         | 0.4%    |
| OpenMandriva 4.50            | 3         | 0.4%    |
| Manjaro 20.2                 | 3         | 0.4%    |
| Manjaro 20.1                 | 3         | 0.4%    |
| LMDE 4                       | 3         | 0.4%    |
| Kubuntu 21.10                | 3         | 0.4%    |
| Kubuntu 20.04                | 3         | 0.4%    |
| KDE neon 18.04               | 3         | 0.4%    |
| Gentoo 2.6                   | 3         | 0.4%    |
| Elementary 5.1.6             | 3         | 0.4%    |
| Debian 10                    | 3         | 0.4%    |
| Xubuntu 18.04                | 2         | 0.27%   |
| Ubuntu Budgie 20.04          | 2         | 0.27%   |
| ROSA R9                      | 2         | 0.27%   |
| ROSA R11                     | 2         | 0.27%   |
| Pop!_OS 21.10                | 2         | 0.27%   |
| openSUSE Leap-15.2           | 2         | 0.27%   |
| openSUSE Leap-15.1           | 2         | 0.27%   |
| MX 21                        | 2         | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 261       | 36.86%  |
| Linux Mint    | 69        | 9.75%   |
| Fedora        | 55        | 7.77%   |
| Manjaro       | 42        | 5.93%   |
| Arch          | 33        | 4.66%   |
| OpenMandriva  | 30        | 4.24%   |
| Pop!_OS       | 25        | 3.53%   |
| Debian        | 24        | 3.39%   |
| Zorin         | 22        | 3.11%   |
| BlackPanther  | 19        | 2.68%   |
| openSUSE      | 15        | 2.12%   |
| KDE neon      | 15        | 2.12%   |
| ROSA          | 11        | 1.55%   |
| Xubuntu       | 10        | 1.41%   |
| Kubuntu       | 10        | 1.41%   |
| Endless       | 9         | 1.27%   |
| Elementary    | 9         | 1.27%   |
| MX            | 6         | 0.85%   |
| Ubuntu Budgie | 5         | 0.71%   |
| LMDE          | 4         | 0.56%   |
| Gentoo        | 4         | 0.56%   |
| Ubuntu MATE   | 3         | 0.42%   |
| Kali          | 3         | 0.42%   |
| Lubuntu       | 2         | 0.28%   |
| EndeavourOS   | 2         | 0.28%   |
| Clear Linux   | 2         | 0.28%   |
| CentOS        | 2         | 0.28%   |
| CachyOS       | 2         | 0.28%   |
| UbuntuDDE     | 1         | 0.14%   |
| Ubuntu Studio | 1         | 0.14%   |
| SteamOS       | 1         | 0.14%   |
| Solus         | 1         | 0.14%   |
| Sn3rpOs       | 1         | 0.14%   |
| Parrot        | 1         | 0.14%   |
| NixOS         | 1         | 0.14%   |
| Garuda Linux  | 1         | 0.14%   |
| Funtoo        | 1         | 0.14%   |
| Devuan        | 1         | 0.14%   |
| Deepin        | 1         | 0.14%   |
| Chrome OS     | 1         | 0.14%   |
| ArcoLinux     | 1         | 0.14%   |
| antergos      | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 16        | 1.94%   |
| 5.16.7-desktop-1omv4003  | 16        | 1.94%   |
| 4.18.16-desktop-1bP      | 13        | 1.58%   |
| 5.4.0-58-generic         | 12        | 1.46%   |
| 5.3.0-46-generic         | 12        | 1.46%   |
| 5.10.14-desktop-1omv4002 | 11        | 1.34%   |
| 5.4.0-52-generic         | 10        | 1.22%   |
| 5.3.0-26-generic         | 10        | 1.22%   |
| 5.4.0-29-generic         | 9         | 1.09%   |
| 5.4.0-26-generic         | 9         | 1.09%   |
| 5.13.0-28-generic        | 9         | 1.09%   |
| 5.4.0-91-generic         | 8         | 0.97%   |
| 5.13.0-39-generic        | 8         | 0.97%   |
| 5.13.0-27-generic        | 8         | 0.97%   |
| 5.11.0-37-generic        | 8         | 0.97%   |
| 5.6.14-desktop-2bP       | 7         | 0.85%   |
| 5.4.0-48-generic         | 7         | 0.85%   |
| 5.11.0-27-generic        | 7         | 0.85%   |
| 5.11.0-25-generic        | 7         | 0.85%   |
| 5.4.0-74-generic         | 6         | 0.73%   |
| 5.4.0-33-generic         | 6         | 0.73%   |
| 5.3.0-42-generic         | 6         | 0.73%   |
| 5.10.0-8-amd64           | 6         | 0.73%   |
| 5.8.0-43-generic         | 5         | 0.61%   |
| 5.4.0-28-generic         | 5         | 0.61%   |
| 5.15.12-200.fc35.x86_64  | 5         | 0.61%   |
| 5.13.0-40-generic        | 5         | 0.61%   |
| 5.11.0-43-generic        | 5         | 0.61%   |
| 5.11.0-40-generic        | 5         | 0.61%   |
| 5.11.0-38-generic        | 5         | 0.61%   |
| 5.11.0-34-generic        | 5         | 0.61%   |
| 5.0.0-32-generic         | 5         | 0.61%   |
| 5.0.0-25-generic         | 5         | 0.61%   |
| 5.8.0-7630-generic       | 4         | 0.49%   |
| 5.8.0-53-generic         | 4         | 0.49%   |
| 5.8.0-50-generic         | 4         | 0.49%   |
| 5.8.0-41-generic         | 4         | 0.49%   |
| 5.8.0-33-generic         | 4         | 0.49%   |
| 5.8.0-14-generic         | 4         | 0.49%   |
| 5.4.0-80-generic         | 4         | 0.49%   |
| 5.4.0-47-generic         | 4         | 0.49%   |
| 5.4.0-37-generic         | 4         | 0.49%   |
| 5.3.0-28-generic         | 4         | 0.49%   |
| 5.3.0-24-generic         | 4         | 0.49%   |
| 5.13.0-7614-generic      | 4         | 0.49%   |
| 5.13.0-35-generic        | 4         | 0.49%   |
| 5.11.0-22-generic        | 4         | 0.49%   |
| 5.0.0-23-generic         | 4         | 0.49%   |
| 5.8.0-48-generic         | 3         | 0.36%   |
| 5.8.0-25-generic         | 3         | 0.36%   |
| 5.7.9-1-MANJARO          | 3         | 0.36%   |
| 5.4.0-94-generic         | 3         | 0.36%   |
| 5.4.0-90-generic         | 3         | 0.36%   |
| 5.4.0-89-generic         | 3         | 0.36%   |
| 5.4.0-84-generic         | 3         | 0.36%   |
| 5.4.0-77-generic         | 3         | 0.36%   |
| 5.4.0-72-generic         | 3         | 0.36%   |
| 5.4.0-70-generic         | 3         | 0.36%   |
| 5.4.0-65-generic         | 3         | 0.36%   |
| 5.4.0-62-generic         | 3         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 154       | 19.85%  |
| 5.11.0  | 63        | 8.12%   |
| 5.13.0  | 59        | 7.6%    |
| 5.8.0   | 49        | 6.31%   |
| 5.3.0   | 47        | 6.06%   |
| 4.15.0  | 45        | 5.8%    |
| 5.0.0   | 22        | 2.84%   |
| 5.10.0  | 20        | 2.58%   |
| 5.16.7  | 17        | 2.19%   |
| 4.18.0  | 14        | 1.8%    |
| 4.18.16 | 13        | 1.68%   |
| 5.10.14 | 11        | 1.42%   |
| 4.19.0  | 11        | 1.42%   |
| 5.6.14  | 7         | 0.9%    |
| 5.15.12 | 5         | 0.64%   |
| 5.15.0  | 5         | 0.64%   |
| 5.9.11  | 4         | 0.52%   |
| 5.7.9   | 4         | 0.52%   |
| 5.7.0   | 4         | 0.52%   |
| 5.3.18  | 4         | 0.52%   |
| 5.17.5  | 4         | 0.52%   |
| 5.17.1  | 4         | 0.52%   |
| 5.9.10  | 3         | 0.39%   |
| 5.8.14  | 3         | 0.39%   |
| 5.6.19  | 3         | 0.39%   |
| 5.17.4  | 3         | 0.39%   |
| 5.16.18 | 3         | 0.39%   |
| 5.13.19 | 3         | 0.39%   |
| 5.12.4  | 3         | 0.39%   |
| 5.11.12 | 3         | 0.39%   |
| 5.10.2  | 3         | 0.39%   |
| 4.4.0   | 3         | 0.39%   |
| 4.12.14 | 3         | 0.39%   |
| 5.9.16  | 2         | 0.26%   |
| 5.8.6   | 2         | 0.26%   |
| 5.8.5   | 2         | 0.26%   |
| 5.8.4   | 2         | 0.26%   |
| 5.8.18  | 2         | 0.26%   |
| 5.8.16  | 2         | 0.26%   |
| 5.8.15  | 2         | 0.26%   |
| 5.7.15  | 2         | 0.26%   |
| 5.7.12  | 2         | 0.26%   |
| 5.6.7   | 2         | 0.26%   |
| 5.6.16  | 2         | 0.26%   |
| 5.6.10  | 2         | 0.26%   |
| 5.4.14  | 2         | 0.26%   |
| 5.2.0   | 2         | 0.26%   |
| 5.18.0  | 2         | 0.26%   |
| 5.17.15 | 2         | 0.26%   |
| 5.17.11 | 2         | 0.26%   |
| 5.16.11 | 2         | 0.26%   |
| 5.16.0  | 2         | 0.26%   |
| 5.15.32 | 2         | 0.26%   |
| 5.15.10 | 2         | 0.26%   |
| 5.14.9  | 2         | 0.26%   |
| 5.13.13 | 2         | 0.26%   |
| 5.13.1  | 2         | 0.26%   |
| 5.12.8  | 2         | 0.26%   |
| 5.12.14 | 2         | 0.26%   |
| 5.10.7  | 2         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 168       | 21.96%  |
| 5.11    | 72        | 9.41%   |
| 5.13    | 70        | 9.15%   |
| 5.8     | 64        | 8.37%   |
| 5.3     | 55        | 7.19%   |
| 5.10    | 50        | 6.54%   |
| 4.15    | 45        | 5.88%   |
| 5.16    | 31        | 4.05%   |
| 4.18    | 27        | 3.53%   |
| 5.0     | 23        | 3.01%   |
| 5.6     | 22        | 2.88%   |
| 5.15    | 19        | 2.48%   |
| 5.7     | 18        | 2.35%   |
| 5.17    | 17        | 2.22%   |
| 5.9     | 15        | 1.96%   |
| 4.19    | 13        | 1.7%    |
| 5.12    | 11        | 1.44%   |
| 5.14    | 7         | 0.92%   |
| 4.9     | 7         | 0.92%   |
| 5.5     | 6         | 0.78%   |
| 5.18    | 4         | 0.52%   |
| 4.4     | 4         | 0.52%   |
| 4.17    | 4         | 0.52%   |
| 5.2     | 3         | 0.39%   |
| 4.12    | 3         | 0.39%   |
| 5.1     | 2         | 0.26%   |
| 4.13    | 2         | 0.26%   |
| 4.8     | 1         | 0.13%   |
| 4.14    | 1         | 0.13%   |
| 4.10    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 683       | 98.27%  |
| i686   | 12        | 1.73%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 336       | 46.93%  |
| KDE5            | 110       | 15.36%  |
| Unknown         | 81        | 11.31%  |
| X-Cinnamon      | 49        | 6.84%   |
| XFCE            | 48        | 6.7%    |
| MATE            | 18        | 2.51%   |
| KDE             | 17        | 2.37%   |
| Cinnamon        | 14        | 1.96%   |
| Pantheon        | 9         | 1.26%   |
| Budgie          | 6         | 0.84%   |
| KDE4            | 5         | 0.7%    |
| i3              | 5         | 0.7%    |
| Unity           | 4         | 0.56%   |
| LXDE            | 4         | 0.56%   |
| Deepin          | 3         | 0.42%   |
| LXQt            | 2         | 0.28%   |
| awesome         | 2         | 0.28%   |
| sway            | 1         | 0.14%   |
| GNOME Flashback | 1         | 0.14%   |
| Bspwm           | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 574       | 80.73%  |
| Wayland | 91        | 12.8%   |
| Unknown | 43        | 6.05%   |
| Tty     | 3         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 370       | 51.46%  |
| SDDM    | 103       | 14.33%  |
| GDM     | 101       | 14.05%  |
| LightDM | 59        | 8.21%   |
| GDM3    | 55        | 7.65%   |
| TDM     | 25        | 3.48%   |
| KDM     | 5         | 0.7%    |
| SLiM    | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| de_AT   | 240       | 33.76%  |
| en_US   | 209       | 29.4%   |
| Unknown | 102       | 14.35%  |
| de_DE   | 99        | 13.92%  |
| en_GB   | 27        | 3.8%    |
| C       | 7         | 0.98%   |
| pl_PL   | 5         | 0.7%    |
| POSIX   | 3         | 0.42%   |
| de_CH   | 3         | 0.42%   |
| tr_TR   | 2         | 0.28%   |
| es_ES   | 2         | 0.28%   |
| en_AT   | 2         | 0.28%   |
| ru_RU   | 1         | 0.14%   |
| ro_RO   | 1         | 0.14%   |
| pt_BR   | 1         | 0.14%   |
| it_IT   | 1         | 0.14%   |
| hr_HR   | 1         | 0.14%   |
| en_IE   | 1         | 0.14%   |
| en      | 1         | 0.14%   |
| de_LI   | 1         | 0.14%   |
| C.UTF8  | 1         | 0.14%   |
| bg_BG   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 384       | 53.93%  |
| BIOS | 328       | 46.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 553       | 78.89%  |
| Overlay | 57        | 8.13%   |
| Btrfs   | 46        | 6.56%   |
| Unknown | 30        | 4.28%   |
| Xfs     | 6         | 0.86%   |
| Zfs     | 2         | 0.29%   |
| Ext3    | 2         | 0.29%   |
| XXXXXXX | 1         | 0.14%   |
| Tmpfs   | 1         | 0.14%   |
| Nfs     | 1         | 0.14%   |
| Ext2    | 1         | 0.14%   |
| Aufs    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 409       | 58.01%  |
| GPT     | 218       | 30.92%  |
| MBR     | 78        | 11.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 621       | 88.59%  |
| Yes       | 80        | 11.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 530       | 75.28%  |
| Yes       | 174       | 24.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 190       | 27.38%  |
| Hewlett-Packard     | 142       | 20.46%  |
| Dell                | 71        | 10.23%  |
| Acer                | 67        | 9.65%   |
| ASUSTek Computer    | 63        | 9.08%   |
| Medion              | 24        | 3.46%   |
| Apple               | 23        | 3.31%   |
| Toshiba             | 19        | 2.74%   |
| Sony                | 15        | 2.16%   |
| TUXEDO              | 14        | 2.02%   |
| Fujitsu             | 8         | 1.15%   |
| MSI                 | 7         | 1.01%   |
| Samsung Electronics | 5         | 0.72%   |
| Unknown             | 5         | 0.72%   |
| HUAWEI              | 4         | 0.58%   |
| Fujitsu Siemens     | 4         | 0.58%   |
| Razer               | 3         | 0.43%   |
| Notebook            | 3         | 0.43%   |
| Clevo               | 3         | 0.43%   |
| Wortmann AG         | 2         | 0.29%   |
| TrekStor            | 2         | 0.29%   |
| Timi                | 2         | 0.29%   |
| System76            | 2         | 0.29%   |
| Valve               | 1         | 0.14%   |
| VALE                | 1         | 0.14%   |
| TWJ                 | 1         | 0.14%   |
| TENKU               | 1         | 0.14%   |
| Teclast             | 1         | 0.14%   |
| Shuttle             | 1         | 0.14%   |
| Schenker            | 1         | 0.14%   |
| Panasonic           | 1         | 0.14%   |
| MAXDATA             | 1         | 0.14%   |
| LG Electronics      | 1         | 0.14%   |
| Jumper              | 1         | 0.14%   |
| GPD                 | 1         | 0.14%   |
| Gigabyte Technology | 1         | 0.14%   |
| eMachines           | 1         | 0.14%   |
| Chuwi               | 1         | 0.14%   |
| Alienware           | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Apple MacBookPro15,1                              | 8         | 1.15%   |
| Unknown                                           | 8         | 1.15%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                     | 5         | 0.72%   |
| HP Pavilion dv6                                   | 5         | 0.72%   |
| HP EliteBook 8570p                                | 5         | 0.72%   |
| HP EliteBook 840 G3                               | 5         | 0.72%   |
| HP EliteBook 8460p                                | 4         | 0.58%   |
| HP EliteBook 840 G6                               | 4         | 0.58%   |
| Dell XPS 15 9570                                  | 4         | 0.58%   |
| Toshiba Satellite C70D-B                          | 3         | 0.43%   |
| Medion P15648                                     | 3         | 0.43%   |
| Lenovo Yoga Slim 7 14ARE05 82A2                   | 3         | 0.43%   |
| Lenovo ThinkPad E470 20H2S00700                   | 3         | 0.43%   |
| HP Pavilion g7                                    | 3         | 0.43%   |
| HP Notebook                                       | 3         | 0.43%   |
| HP EliteBook 840 G1                               | 3         | 0.43%   |
| HP EliteBook 6930p                                | 3         | 0.43%   |
| HP EliteBook 2560p                                | 3         | 0.43%   |
| Dell Latitude E7450                               | 3         | 0.43%   |
| Dell Latitude E7440                               | 3         | 0.43%   |
| Dell Inspiron 1720                                | 3         | 0.43%   |
| Apple MacBookPro8,1                               | 3         | 0.43%   |
| Acer TravelMate P253                              | 3         | 0.43%   |
| Acer Swift SF314-42                               | 3         | 0.43%   |
| Acer Swift SF114-34                               | 3         | 0.43%   |
| Acer Aspire 7750G                                 | 3         | 0.43%   |
| TUXEDO Pulse 15 Gen1                              | 2         | 0.29%   |
| Toshiba Satellite C50D-B                          | 2         | 0.29%   |
| System76 Lemur Pro                                | 2         | 0.29%   |
| Medion P7624                                      | 2         | 0.29%   |
| Medion P6669 MD60147                              | 2         | 0.29%   |
| Medion P6618                                      | 2         | 0.29%   |
| Medion E6220                                      | 2         | 0.29%   |
| Lenovo V145-15AST 81MT                            | 2         | 0.29%   |
| Lenovo ThinkPad X270 20HN0016GE                   | 2         | 0.29%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW         | 2         | 0.29%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES01L00          | 2         | 0.29%   |
| Lenovo ThinkPad T14 Gen 2i 20W000AUGE             | 2         | 0.29%   |
| Lenovo ThinkPad L14 Gen 1 20U50001GE              | 2         | 0.29%   |
| Lenovo ThinkPad E580 20KS001RGE                   | 2         | 0.29%   |
| Lenovo ThinkBook 16p Gen 2 20YM                   | 2         | 0.29%   |
| Lenovo IdeaPad 700-15ISK 80RU                     | 2         | 0.29%   |
| Lenovo G500s 20245                                | 2         | 0.29%   |
| HUAWEI KPL-W0X                                    | 2         | 0.29%   |
| HP ZBook Firefly 15 inch G8 Mobile Workstation PC | 2         | 0.29%   |
| HP ZBook 17 G5                                    | 2         | 0.29%   |
| HP ProBook 450 G6                                 | 2         | 0.29%   |
| HP ProBook 450 G2                                 | 2         | 0.29%   |
| HP ProBook 430 G5                                 | 2         | 0.29%   |
| HP Pavilion x2 Detachable                         | 2         | 0.29%   |
| HP Pavilion g6                                    | 2         | 0.29%   |
| HP Pavilion dv7                                   | 2         | 0.29%   |
| HP Laptop 15-db1xxx                               | 2         | 0.29%   |
| HP EliteBook 8540p                                | 2         | 0.29%   |
| HP EliteBook 850 G7 Notebook PC                   | 2         | 0.29%   |
| HP EliteBook 845 G7 Notebook PC                   | 2         | 0.29%   |
| HP 250 G7 Notebook PC                             | 2         | 0.29%   |
| HP 250 G3                                         | 2         | 0.29%   |
| Fujitsu LIFEBOOK S761                             | 2         | 0.29%   |
| Dell XPS 17 9700                                  | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 129       | 18.59%  |
| HP EliteBook          | 54        | 7.78%   |
| Acer Aspire           | 40        | 5.76%   |
| Dell Latitude         | 29        | 4.18%   |
| Lenovo IdeaPad        | 24        | 3.46%   |
| HP ProBook            | 24        | 3.46%   |
| HP Pavilion           | 20        | 2.88%   |
| Dell XPS              | 20        | 2.88%   |
| Toshiba Satellite     | 17        | 2.45%   |
| Dell Inspiron         | 12        | 1.73%   |
| HP Laptop             | 9         | 1.3%    |
| Acer TravelMate       | 9         | 1.3%    |
| Lenovo Yoga           | 8         | 1.15%   |
| Fujitsu LIFEBOOK      | 8         | 1.15%   |
| Apple MacBookPro15    | 8         | 1.15%   |
| Acer Swift            | 8         | 1.15%   |
| Unknown               | 8         | 1.15%   |
| HP ZBook              | 7         | 1.01%   |
| Dell Precision        | 7         | 1.01%   |
| ASUS VivoBook         | 6         | 0.86%   |
| Lenovo ThinkBook      | 5         | 0.72%   |
| HP 250                | 5         | 0.72%   |
| ASUS ZenBook          | 5         | 0.72%   |
| Acer Nitro            | 5         | 0.72%   |
| HP Compaq             | 4         | 0.58%   |
| ASUS ROG              | 4         | 0.58%   |
| Razer Blade           | 3         | 0.43%   |
| Medion P15648         | 3         | 0.43%   |
| Lenovo Legion         | 3         | 0.43%   |
| HP OMEN               | 3         | 0.43%   |
| HP Notebook           | 3         | 0.43%   |
| HP 255                | 3         | 0.43%   |
| Apple MacBookPro8     | 3         | 0.43%   |
| TUXEDO Pulse          | 2         | 0.29%   |
| System76 Lemur        | 2         | 0.29%   |
| Samsung 900X3C        | 2         | 0.29%   |
| Medion P7624          | 2         | 0.29%   |
| Medion P6669          | 2         | 0.29%   |
| Medion P6618          | 2         | 0.29%   |
| Medion E6220          | 2         | 0.29%   |
| Medion Akoya          | 2         | 0.29%   |
| Lenovo V145-15AST     | 2         | 0.29%   |
| Lenovo G500s          | 2         | 0.29%   |
| HUAWEI KPL-W0X        | 2         | 0.29%   |
| HP ENVY               | 2         | 0.29%   |
| Fujitsu Siemens AMILO | 2         | 0.29%   |
| Dell Vostro           | 2         | 0.29%   |
| ASUS TUF              | 2         | 0.29%   |
| ASUS K52F             | 2         | 0.29%   |
| Apple MacBookPro9     | 2         | 0.29%   |
| Apple MacBookPro5     | 2         | 0.29%   |
| Acer Predator         | 2         | 0.29%   |
| Wortmann AG TERRA     | 1         | 0.14%   |
| Wortmann AG Mobile    | 1         | 0.14%   |
| Valve Jupiter         | 1         | 0.14%   |
| VALE Notebook         | 1         | 0.14%   |
| TUXEDO Stellaris      | 1         | 0.14%   |
| TUXEDO Polaris        | 1         | 0.14%   |
| TUXEDO P95            | 1         | 0.14%   |
| TUXEDO P7xxTM1        | 1         | 0.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 90        | 12.97%  |
| 2012 | 67        | 9.65%   |
| 2019 | 62        | 8.93%   |
| 2011 | 61        | 8.79%   |
| 2017 | 54        | 7.78%   |
| 2018 | 52        | 7.49%   |
| 2015 | 48        | 6.92%   |
| 2016 | 46        | 6.63%   |
| 2014 | 46        | 6.63%   |
| 2021 | 45        | 6.48%   |
| 2013 | 29        | 4.18%   |
| 2008 | 28        | 4.03%   |
| 2010 | 24        | 3.46%   |
| 2009 | 19        | 2.74%   |
| 2007 | 16        | 2.31%   |
| 2006 | 5         | 0.72%   |
| 2022 | 2         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 694       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 614       | 87.09%  |
| Enabled  | 91        | 12.91%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 692       | 99.71%  |
| Yes  | 2         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 175       | 24.93%  |
| 16.01-24.0  | 141       | 20.09%  |
| 8.01-16.0   | 139       | 19.8%   |
| 3.01-4.0    | 127       | 18.09%  |
| 32.01-64.0  | 58        | 8.26%   |
| 1.01-2.0    | 32        | 4.56%   |
| 24.01-32.0  | 10        | 1.42%   |
| 2.01-3.0    | 9         | 1.28%   |
| 0.51-1.0    | 7         | 1%      |
| 64.01-256.0 | 4         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 306       | 39.9%   |
| 2.01-3.0   | 184       | 23.99%  |
| 4.01-8.0   | 98        | 12.78%  |
| 3.01-4.0   | 86        | 11.21%  |
| 0.51-1.0   | 53        | 6.91%   |
| 8.01-16.0  | 28        | 3.65%   |
| 16.01-24.0 | 6         | 0.78%   |
| 0.01-0.5   | 3         | 0.39%   |
| 24.01-32.0 | 2         | 0.26%   |
| 32.01-64.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 527       | 74.86%  |
| 2      | 145       | 20.6%   |
| 3      | 23        | 3.27%   |
| 0      | 6         | 0.85%   |
| 4      | 2         | 0.28%   |
| 5      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 447       | 64.13%  |
| Yes       | 250       | 35.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 584       | 83.91%  |
| No        | 112       | 16.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 688       | 99.14%  |
| No        | 6         | 0.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 530       | 76.04%  |
| No        | 167       | 23.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Austria | 694       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Vienna                          | 425       | 58.54%  |
| Graz                            | 41        | 5.65%   |
| Salzburg                        | 18        | 2.48%   |
| Bad Hall                        | 18        | 2.48%   |
| Linz                            | 16        | 2.2%    |
| Innsbruck                       | 14        | 1.93%   |
| Klagenfurt                      | 7         | 0.96%   |
| Perg                            | 6         | 0.83%   |
| Leonding                        | 6         | 0.83%   |
| Wiener Neustadt                 | 5         | 0.69%   |
| Wels                            | 5         | 0.69%   |
| Sankt Pölten                   | 5         | 0.69%   |
| Wörgl                          | 4         | 0.55%   |
| Villach                         | 4         | 0.55%   |
| Dornbirn                        | 4         | 0.55%   |
| Bregenz                         | 4         | 0.55%   |
| Baden bei Wien                  | 4         | 0.55%   |
| Traun                           | 3         | 0.41%   |
| Korneuburg                      | 3         | 0.41%   |
| Hard                            | 3         | 0.41%   |
| Gaenserndorf                    | 3         | 0.41%   |
| Woerdern                        | 2         | 0.28%   |
| Umhausen                        | 2         | 0.28%   |
| Traunkirchen                    | 2         | 0.28%   |
| Traiskirchen                    | 2         | 0.28%   |
| Neusiedl am See                 | 2         | 0.28%   |
| Mauthausen                      | 2         | 0.28%   |
| Mautern                         | 2         | 0.28%   |
| Lech                            | 2         | 0.28%   |
| Hartberg                        | 2         | 0.28%   |
| Hallwang                        | 2         | 0.28%   |
| Gross-Enzersdorf                | 2         | 0.28%   |
| Feldkirch                       | 2         | 0.28%   |
| Deutsch Griffen                 | 2         | 0.28%   |
| Zell am See                     | 1         | 0.14%   |
| Wolfern                         | 1         | 0.14%   |
| Wildon                          | 1         | 0.14%   |
| Waxenberg                       | 1         | 0.14%   |
| Vorchdorf                       | 1         | 0.14%   |
| Voitsberg                       | 1         | 0.14%   |
| Voecklabruck                    | 1         | 0.14%   |
| Thalgau                         | 1         | 0.14%   |
| Stronsdorf                      | 1         | 0.14%   |
| Strasshof an der Nordbahn       | 1         | 0.14%   |
| Steinabrueckl                   | 1         | 0.14%   |
| Stallhofen                      | 1         | 0.14%   |
| Spillern                        | 1         | 0.14%   |
| Spielberg bei Knittelfeld       | 1         | 0.14%   |
| Sommerein                       | 1         | 0.14%   |
| Sollenau                        | 1         | 0.14%   |
| Sistrans                        | 1         | 0.14%   |
| Seewalchen                      | 1         | 0.14%   |
| Schwechat                       | 1         | 0.14%   |
| Schnaidt                        | 1         | 0.14%   |
| Schleinbach                     | 1         | 0.14%   |
| Scheffau am Wilden Kaiser       | 1         | 0.14%   |
| Schaeffern                      | 1         | 0.14%   |
| Sankt Peter im Sulmtal          | 1         | 0.14%   |
| Sankt Oswald bei Freistadt      | 1         | 0.14%   |
| Sankt Margarethen im Burgenland | 1         | 0.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 197       | 272    | 23.2%   |
| SanDisk                        | 83        | 112    | 9.78%   |
| Seagate                        | 80        | 102    | 9.42%   |
| WDC                            | 74        | 94     | 8.72%   |
| Toshiba                        | 74        | 88     | 8.72%   |
| Unknown                        | 44        | 57     | 5.18%   |
| SK hynix                       | 35        | 45     | 4.12%   |
| Kingston                       | 33        | 42     | 3.89%   |
| Intel                          | 26        | 28     | 3.06%   |
| Hitachi                        | 25        | 27     | 2.94%   |
| HGST                           | 24        | 29     | 2.83%   |
| Crucial                        | 22        | 30     | 2.59%   |
| Micron Technology              | 17        | 21     | 2%      |
| Apple                          | 13        | 23     | 1.53%   |
| Transcend                      | 10        | 11     | 1.18%   |
| Intenso                        | 10        | 12     | 1.18%   |
| KIOXIA                         | 8         | 11     | 0.94%   |
| LITEONIT                       | 6         | 8      | 0.71%   |
| LITEON                         | 5         | 6      | 0.59%   |
| A-DATA Technology              | 5         | 7      | 0.59%   |
| Phison                         | 4         | 4      | 0.47%   |
| China                          | 4         | 4      | 0.47%   |
| SABRENT                        | 3         | 3      | 0.35%   |
| OCZ                            | 3         | 4      | 0.35%   |
| Lenovo                         | 3         | 4      | 0.35%   |
| INNOVATION IT                  | 3         | 3      | 0.35%   |
| ASMT                           | 3         | 5      | 0.35%   |
| Unknown                        | 3         | 4      | 0.35%   |
| Solid State Storage Technology | 2         | 2      | 0.24%   |
| Micron/Crucial Technology      | 2         | 2      | 0.24%   |
| ICY BOX                        | 2         | 2      | 0.24%   |
| Hewlett-Packard                | 2         | 1      | 0.24%   |
| Goodram                        | 2         | 2      | 0.24%   |
| Fujitsu                        | 2         | 2      | 0.24%   |
| Vaseky                         | 1         | 1      | 0.12%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.12%   |
| Union Memory                   | 1         | 1      | 0.12%   |
| Teclast                        | 1         | 1      | 0.12%   |
| TCSUNBOW                       | 1         | 1      | 0.12%   |
| SPCC                           | 1         | 1      | 0.12%   |
| ShanDianZhe                    | 1         | 1      | 0.12%   |
| Netac                          | 1         | 1      | 0.12%   |
| Mushkin                        | 1         | 1      | 0.12%   |
| MTFDDAK1                       | 1         | 1      | 0.12%   |
| Leven                          | 1         | 1      | 0.12%   |
| KIOXIA-EXCERIA                 | 1         | 1      | 0.12%   |
| KingDian                       | 1         | 1      | 0.12%   |
| JMicron Technology             | 1         | 1      | 0.12%   |
| JetFlash                       | 1         | 1      | 0.12%   |
| Inateck                        | 1         | 1      | 0.12%   |
| EMTEC                          | 1         | 1      | 0.12%   |
| Corsair                        | 1         | 1      | 0.12%   |
| BIWIN                          | 1         | 1      | 0.12%   |
| Apacer                         | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB           | 22        | 2.49%   |
| Toshiba MQ01ABD100 1TB                 | 11        | 1.24%   |
| Samsung SSD 850 EVO 250GB              | 11        | 1.24%   |
| Samsung NVMe SSD Drive 1TB             | 11        | 1.24%   |
| SanDisk NVMe SSD Drive 512GB           | 10        | 1.13%   |
| Samsung NVMe SSD Drive 1024GB          | 9         | 1.02%   |
| SK hynix NVMe SSD Drive 512GB          | 8         | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 8         | 0.9%    |
| Apple SSD AP0512M 500GB                | 7         | 0.79%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 6         | 0.68%   |
| Toshiba MQ04ABF100 1TB                 | 6         | 0.68%   |
| Seagate ST9500325AS 500GB              | 6         | 0.68%   |
| Seagate ST500LT012-1DG142 500GB        | 6         | 0.68%   |
| SanDisk SSD PLUS 240GB                 | 6         | 0.68%   |
| Samsung SSD 860 EVO 500GB              | 6         | 0.68%   |
| Samsung SSD 850 PRO 256GB              | 6         | 0.68%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 6         | 0.68%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 5         | 0.56%   |
| Transcend TS240GMTS420S 240GB SSD      | 5         | 0.56%   |
| Toshiba NVMe SSD Drive 512GB           | 5         | 0.56%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 5         | 0.56%   |
| SK hynix HFS256G39TND-N210A 256GB SSD  | 5         | 0.56%   |
| Seagate ST2000LM015-2E8174 2TB         | 5         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 0.56%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD    | 5         | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB           | 5         | 0.56%   |
| Samsung MZVLB1T0HBLR-000L7 1TB         | 5         | 0.56%   |
| Kingston SV300S37A120G 120GB SSD       | 5         | 0.56%   |
| Kingston SA400S37480G 480GB SSD        | 5         | 0.56%   |
| Intel NVMe SSD Drive 512GB             | 5         | 0.56%   |
| HGST HTS721010A9E630 1TB               | 5         | 0.56%   |
| HGST HTS541010A9E680 1TB               | 5         | 0.56%   |
| Unknown MMC Card  64GB                 | 4         | 0.45%   |
| Unknown MMC Card  32GB                 | 4         | 0.45%   |
| Toshiba MQ01ABF050 500GB               | 4         | 0.45%   |
| Samsung SSD 970 EVO 1TB                | 4         | 0.45%   |
| Samsung SSD 850 EVO 500GB              | 4         | 0.45%   |
| Samsung NVMe SSD Drive 256GB           | 4         | 0.45%   |
| Kingston NVMe SSD Drive 512GB          | 4         | 0.45%   |
| HGST HTS545050A7E680 500GB             | 4         | 0.45%   |
| Crucial CT250MX500SSD1 250GB           | 4         | 0.45%   |
| Crucial CT240BX500SSD1 240GB           | 4         | 0.45%   |
| WDC WD1600BEVS-22RST0 160GB            | 3         | 0.34%   |
| WDC WD10SPZX-60Z10T0 1TB               | 3         | 0.34%   |
| Unknown SL16G  16GB                    | 3         | 0.34%   |
| Transcend TS512GMTS430S 512GB SSD      | 3         | 0.34%   |
| Toshiba MQ01ABD050 500GB               | 3         | 0.34%   |
| Toshiba KXG6AZNV1T02 1TB               | 3         | 0.34%   |
| Toshiba KBG40ZNT512G MEMORY 512GB      | 3         | 0.34%   |
| SK hynix NVMe SSD Drive 1024GB         | 3         | 0.34%   |
| Seagate ST500LM021-1KJ152 500GB        | 3         | 0.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 3         | 0.34%   |
| Seagate Expansion 1TB                  | 3         | 0.34%   |
| SanDisk SD9SB8W256G1002 256GB SSD      | 3         | 0.34%   |
| SanDisk NVMe SSD Drive 256GB           | 3         | 0.34%   |
| SanDisk NVMe SSD Drive 1TB             | 3         | 0.34%   |
| SanDisk NVMe SSD Drive 1024GB          | 3         | 0.34%   |
| Samsung SSD 860 EVO M.2 1TB            | 3         | 0.34%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.34%   |
| Samsung SSD 860 EVO 1TB                | 3         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 100    | 34.21%  |
| WDC                 | 45        | 57     | 19.74%  |
| Toshiba             | 45        | 57     | 19.74%  |
| Hitachi             | 25        | 27     | 10.96%  |
| HGST                | 24        | 29     | 10.53%  |
| Samsung Electronics | 5         | 6      | 2.19%   |
| Fujitsu             | 2         | 2      | 0.88%   |
| JMicron Technology  | 1         | 1      | 0.44%   |
| Inateck             | 1         | 1      | 0.44%   |
| ASMT                | 1         | 1      | 0.44%   |
| Apple               | 1         | 1      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 94        | 118    | 30.52%  |
| SanDisk             | 60        | 83     | 19.48%  |
| Kingston            | 25        | 30     | 8.12%   |
| Crucial             | 22        | 30     | 7.14%   |
| Transcend           | 10        | 11     | 3.25%   |
| SK hynix            | 10        | 13     | 3.25%   |
| Micron Technology   | 9         | 10     | 2.92%   |
| Intenso             | 9         | 11     | 2.92%   |
| Intel               | 8         | 8      | 2.6%    |
| Toshiba             | 7         | 8      | 2.27%   |
| LITEONIT            | 6         | 8      | 1.95%   |
| WDC                 | 5         | 5      | 1.62%   |
| LITEON              | 5         | 6      | 1.62%   |
| A-DATA Technology   | 5         | 7      | 1.62%   |
| China               | 4         | 4      | 1.3%    |
| Apple               | 4         | 4      | 1.3%    |
| OCZ                 | 3         | 4      | 0.97%   |
| INNOVATION IT       | 3         | 3      | 0.97%   |
| Phison              | 2         | 2      | 0.65%   |
| Goodram             | 2         | 2      | 0.65%   |
| Vaseky              | 1         | 1      | 0.32%   |
| Unknown             | 1         | 2      | 0.32%   |
| Teclast             | 1         | 1      | 0.32%   |
| TCSUNBOW            | 1         | 1      | 0.32%   |
| SPCC                | 1         | 1      | 0.32%   |
| Seagate             | 1         | 1      | 0.32%   |
| Netac               | 1         | 1      | 0.32%   |
| Mushkin             | 1         | 1      | 0.32%   |
| Leven               | 1         | 1      | 0.32%   |
| KingDian            | 1         | 1      | 0.32%   |
| Hewlett-Packard     | 1         | 1      | 0.32%   |
| EMTEC               | 1         | 1      | 0.32%   |
| Corsair             | 1         | 1      | 0.32%   |
| BIWIN               | 1         | 1      | 0.32%   |
| Apacer              | 1         | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 293       | 383    | 35.69%  |
| NVMe    | 257       | 349    | 31.3%   |
| HDD     | 216       | 282    | 26.31%  |
| MMC     | 44        | 61     | 5.36%   |
| Unknown | 11        | 12     | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 455       | 646    | 58.33%  |
| NVMe | 254       | 346    | 32.56%  |
| MMC  | 44        | 61     | 5.64%   |
| SAS  | 27        | 34     | 3.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 349       | 469    | 69.66%  |
| 0.51-1.0   | 136       | 173    | 27.15%  |
| 1.01-2.0   | 11        | 17     | 2.2%    |
| 4.01-10.0  | 3         | 4      | 0.6%    |
| 3.01-4.0   | 1         | 1      | 0.2%    |
| 2.01-3.0   | 1         | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 225       | 31.21%  |
| 251-500        | 166       | 23.02%  |
| 501-1000       | 99        | 13.73%  |
| 1-20           | 55        | 7.63%   |
| 51-100         | 45        | 6.24%   |
| Unknown        | 36        | 4.99%   |
| 1001-2000      | 35        | 4.85%   |
| 21-50          | 33        | 4.58%   |
| More than 3000 | 16        | 2.22%   |
| 2001-3000      | 11        | 1.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 309       | 41.26%  |
| 21-50          | 134       | 17.89%  |
| 101-250        | 107       | 14.29%  |
| 51-100         | 76        | 10.15%  |
| 251-500        | 37        | 4.94%   |
| Unknown        | 36        | 4.81%   |
| 501-1000       | 30        | 4.01%   |
| 1001-2000      | 14        | 1.87%   |
| More than 3000 | 3         | 0.4%    |
| 2001-3000      | 3         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB               | 4         | 4      | 9.76%   |
| Toshiba MQ01ABF050 500GB                         | 2         | 3      | 4.88%   |
| HGST HTS721010A9E630 1TB                         | 2         | 3      | 4.88%   |
| WDC WD5000LPLX-00ZNTT0 500GB                     | 1         | 1      | 2.44%   |
| WDC WD3200BEVT-08A23T1 320GB                     | 1         | 1      | 2.44%   |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD100M 1TB                          | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 2.44%   |
| Toshiba MK7559GSXP 752GB                         | 1         | 1      | 2.44%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 2.44%   |
| Toshiba MK3276GSX 320GB                          | 1         | 1      | 2.44%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 2.44%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 2.44%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 2      | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 2.44%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB              | 1         | 7      | 2.44%   |
| Samsung Electronics SSD 850 EVO 1TB              | 1         | 1      | 2.44%   |
| Samsung Electronics MZ7PA128HMCD-010H1 128GB SSD | 1         | 1      | 2.44%   |
| Samsung Electronics HN-M101MBB 1TB               | 1         | 1      | 2.44%   |
| Samsung Electronics HM500JI 500GB                | 1         | 1      | 2.44%   |
| LITEONIT LCS-128L9S-11 2.5 7mm 128GB SSD         | 1         | 1      | 2.44%   |
| LITEONIT CMT-64L3M 64GB SSD                      | 1         | 2      | 2.44%   |
| LITEON CV8-8E128-HP 128GB SSD                    | 1         | 1      | 2.44%   |
| Intel SSDPEKNW512G8H 512GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS725050A9A364 500GB                    | 1         | 2      | 2.44%   |
| Hitachi HTS725032A9A364 320GB                    | 1         | 1      | 2.44%   |
| Hitachi HTS547575A9E384 752GB                    | 1         | 1      | 2.44%   |
| Hitachi HTS543232A7A384 320GB                    | 1         | 1      | 2.44%   |
| Hitachi HTS543216A7A384 160GB                    | 1         | 1      | 2.44%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 2.44%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 2.44%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 2.44%   |
| Goodram C40 120GB SSD                            | 1         | 1      | 2.44%   |
| Fujitsu MHY2200BH 200GB                          | 1         | 1      | 2.44%   |
| Crucial CT512M550SSD3 512GB                      | 1         | 1      | 2.44%   |
| A-DATA Technology SSD DP900 128GB-DL3            | 1         | 3      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 9      | 20%     |
| Seagate             | 8         | 16     | 20%     |
| Hitachi             | 5         | 6      | 12.5%   |
| HGST                | 5         | 6      | 12.5%   |
| Samsung Electronics | 4         | 4      | 10%     |
| WDC                 | 2         | 2      | 5%      |
| LITEONIT            | 2         | 3      | 5%      |
| LITEON              | 1         | 1      | 2.5%    |
| Intel               | 1         | 1      | 2.5%    |
| Goodram             | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |
| Crucial             | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 3      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 9      | 25.81%  |
| Seagate             | 8         | 16     | 25.81%  |
| Hitachi             | 5         | 6      | 16.13%  |
| HGST                | 5         | 6      | 16.13%  |
| WDC                 | 2         | 2      | 6.45%   |
| Samsung Electronics | 2         | 2      | 6.45%   |
| Fujitsu             | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 42     | 76.92%  |
| SSD  | 8         | 11     | 20.51%  |
| NVMe | 1         | 1      | 2.56%   |

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
| Detected | 452       | 690    | 60.75%  |
| Works    | 253       | 343    | 34.01%  |
| Malfunc  | 39        | 54     | 5.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 467       | 58.16%  |
| Samsung Electronics            | 106       | 13.2%   |
| AMD                            | 84        | 10.46%  |
| SanDisk                        | 43        | 5.35%   |
| SK hynix                       | 26        | 3.24%   |
| Toshiba America Info Systems   | 24        | 2.99%   |
| KIOXIA                         | 9         | 1.12%   |
| Micron Technology              | 8         | 1%      |
| Kingston Technology Company    | 8         | 1%      |
| Apple                          | 8         | 1%      |
| Nvidia                         | 6         | 0.75%   |
| Union Memory (Shenzhen)        | 3         | 0.37%   |
| Lenovo                         | 3         | 0.37%   |
| Solid State Storage Technology | 2         | 0.25%   |
| Phison Electronics             | 2         | 0.25%   |
| Micron/Crucial Technology      | 2         | 0.25%   |
| VIA Technologies               | 1         | 0.12%   |
| Seagate Technology             | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 74        | 8.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 67        | 7.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 65        | 7.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 55        | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 55        | 6.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 35        | 4.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 29        | 3.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 23        | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 21        | 2.44%   |
| Samsung NVMe SSD Controller 980                                                  | 18        | 2.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 18        | 2.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 17        | 1.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 16        | 1.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 14        | 1.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 1.62%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 13        | 1.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 12        | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 12        | 1.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 11        | 1.28%   |
| Intel SSD 660P Series                                                            | 11        | 1.28%   |
| SK hynix Non-Volatile memory controller                                          | 10        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 1.16%   |
| KIOXIA Non-Volatile memory controller                                            | 9         | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 1.04%   |
| Micron Non-Volatile memory controller                                            | 8         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 0.93%   |
| Apple ANS2 NVMe Controller                                                       | 8         | 0.93%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 7         | 0.81%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 7         | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 0.7%    |
| SK hynix BC511                                                                   | 5         | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 0.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 0.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 5         | 0.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 0.58%   |
| SanDisk Non-Volatile memory controller                                           | 4         | 0.46%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.46%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 4         | 0.46%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 0.46%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 4         | 0.46%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 4         | 0.46%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.35%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.35%   |
| SK hynix Gold P31 SSD                                                            | 3         | 0.35%   |
| SanDisk PC SN520 NVMe SSD                                                        | 3         | 0.35%   |
| Samsung Electronics SATA controller                                              | 3         | 0.35%   |
| Lenovo Non-Volatile memory controller                                            | 3         | 0.35%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.35%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.35%   |
| AMD FCH IDE Controller                                                           | 3         | 0.35%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 488       | 57.82%  |
| NVMe | 255       | 30.21%  |
| RAID | 51        | 6.04%   |
| IDE  | 50        | 5.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 562       | 80.98%  |
| AMD    | 132       | 19.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 20        | 2.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 2.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 1.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 11        | 1.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 1.44%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 10        | 1.44%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 9         | 1.3%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 9         | 1.3%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 9         | 1.3%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 1.15%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 8         | 1.15%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 1.15%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 1.01%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 7         | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 1.01%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 1.01%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 0.86%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 6         | 0.86%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.86%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.72%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 5         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.72%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.72%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 0.72%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 5         | 0.72%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.72%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.72%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 5         | 0.72%   |
| AMD Ryzen 7 4800U with Radeon Graphics        | 5         | 0.72%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 4         | 0.58%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 4         | 0.58%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 0.58%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.58%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 4         | 0.58%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.58%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 4         | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.58%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 4         | 0.58%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 4         | 0.58%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 4         | 0.58%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 4         | 0.58%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.58%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.58%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics   | 4         | 0.58%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 197       | 28.39%  |
| Intel Core i5           | 178       | 25.65%  |
| Intel Core 2 Duo        | 39        | 5.62%   |
| AMD Ryzen 7             | 36        | 5.19%   |
| Intel Core i3           | 31        | 4.47%   |
| AMD Ryzen 5             | 27        | 3.89%   |
| Intel Celeron           | 24        | 3.46%   |
| Other                   | 23        | 3.31%   |
| Intel Pentium           | 22        | 3.17%   |
| AMD Ryzen 7 PRO         | 16        | 2.31%   |
| Intel Atom              | 15        | 2.16%   |
| AMD A4                  | 9         | 1.3%    |
| Intel Pentium Dual-Core | 8         | 1.15%   |
| AMD Ryzen 9             | 6         | 0.86%   |
| Intel Core i9           | 5         | 0.72%   |
| Intel Core 2            | 5         | 0.72%   |
| AMD E2                  | 5         | 0.72%   |
| AMD A6                  | 5         | 0.72%   |
| Intel Pentium Silver    | 4         | 0.58%   |
| Intel Genuine           | 4         | 0.58%   |
| AMD A8                  | 4         | 0.58%   |
| AMD Ryzen 5 PRO         | 3         | 0.43%   |
| AMD E1                  | 3         | 0.43%   |
| AMD E                   | 3         | 0.43%   |
| AMD Athlon II           | 3         | 0.43%   |
| Intel Xeon              | 2         | 0.29%   |
| Intel Pentium Dual      | 2         | 0.29%   |
| Intel Core m5           | 2         | 0.29%   |
| AMD Turion 64 X2 Mobile | 2         | 0.29%   |
| AMD Athlon              | 2         | 0.29%   |
| AMD A10                 | 2         | 0.29%   |
| Intel Core m7           | 1         | 0.14%   |
| Intel Core M            | 1         | 0.14%   |
| Intel Celeron M         | 1         | 0.14%   |
| AMD Ryzen 3             | 1         | 0.14%   |
| AMD PRO A8              | 1         | 0.14%   |
| AMD Phenom II           | 1         | 0.14%   |
| AMD C-50                | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 334       | 48.13%  |
| 4       | 242       | 34.87%  |
| 8       | 58        | 8.36%   |
| 6       | 48        | 6.92%   |
| 1       | 10        | 1.44%   |
| 14      | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 694       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 521       | 74.96%  |
| 1       | 173       | 24.89%  |
| Unknown | 1         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 676       | 97.27%  |
| Unknown        | 13        | 1.87%   |
| 32-bit         | 6         | 0.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 16.08%  |
| 0x206a7    | 56        | 7.83%   |
| 0x306a9    | 46        | 6.43%   |
| 0x806ec    | 36        | 5.03%   |
| 0x806ea    | 31        | 4.34%   |
| 0x406e3    | 28        | 3.92%   |
| 0x40651    | 25        | 3.5%    |
| 0x306d4    | 24        | 3.36%   |
| 0x906ea    | 22        | 3.08%   |
| 0x1067a    | 22        | 3.08%   |
| 0x806e9    | 19        | 2.66%   |
| 0x806c1    | 18        | 2.52%   |
| 0x08600106 | 15        | 2.1%    |
| 0x506e3    | 14        | 1.96%   |
| 0x306c3    | 13        | 1.82%   |
| 0x706e5    | 11        | 1.54%   |
| 0x10676    | 11        | 1.54%   |
| 0x08600103 | 11        | 1.54%   |
| 0x08108102 | 11        | 1.54%   |
| 0x906e9    | 10        | 1.4%    |
| 0x0a50000c | 10        | 1.4%    |
| 0x506c9    | 9         | 1.26%   |
| 0x406c3    | 9         | 1.26%   |
| 0x806eb    | 8         | 1.12%   |
| 0x30678    | 8         | 1.12%   |
| 0x20655    | 8         | 1.12%   |
| 0xa0652    | 7         | 0.98%   |
| 0x08600104 | 7         | 0.98%   |
| 0x20652    | 6         | 0.84%   |
| 0x07030105 | 6         | 0.84%   |
| 0x05000119 | 6         | 0.84%   |
| 0x6fd      | 5         | 0.7%    |
| 0x406c4    | 5         | 0.7%    |
| 0x106ca    | 5         | 0.7%    |
| 0x08608103 | 5         | 0.7%    |
| 0x06006705 | 5         | 0.7%    |
| 0x906ed    | 4         | 0.56%   |
| 0x906c0    | 4         | 0.56%   |
| 0x6f6      | 4         | 0.56%   |
| 0x010000c8 | 4         | 0.56%   |
| 0x706a8    | 3         | 0.42%   |
| 0x6fb      | 3         | 0.42%   |
| 0x6fa      | 3         | 0.42%   |
| 0x6e8      | 3         | 0.42%   |
| 0x08600102 | 3         | 0.42%   |
| 0x0700010f | 3         | 0.42%   |
| 0x106e5    | 2         | 0.28%   |
| 0x106c2    | 2         | 0.28%   |
| 0x08108109 | 2         | 0.28%   |
| 0x0810100b | 2         | 0.28%   |
| 0x08101007 | 2         | 0.28%   |
| 0x06001119 | 2         | 0.28%   |
| 0x05000101 | 2         | 0.28%   |
| 0x03000027 | 2         | 0.28%   |
| 0x906a3    | 1         | 0.14%   |
| 0x806d1    | 1         | 0.14%   |
| 0x806c2    | 1         | 0.14%   |
| 0x706a1    | 1         | 0.14%   |
| 0x6f2      | 1         | 0.14%   |
| 0x30661    | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 157       | 22.62%  |
| SandyBridge      | 62        | 8.93%   |
| IvyBridge        | 58        | 8.36%   |
| Haswell          | 47        | 6.77%   |
| Skylake          | 45        | 6.48%   |
| Zen 2            | 43        | 6.2%    |
| Penryn           | 40        | 5.76%   |
| Broadwell        | 25        | 3.6%    |
| Silvermont       | 23        | 3.31%   |
| TigerLake        | 19        | 2.74%   |
| Zen+             | 17        | 2.45%   |
| Zen 3            | 17        | 2.45%   |
| Westmere         | 16        | 2.31%   |
| Core             | 16        | 2.31%   |
| IceLake          | 14        | 2.02%   |
| Unknown          | 10        | 1.44%   |
| Goldmont         | 9         | 1.3%    |
| Excavator        | 9         | 1.3%    |
| Bobcat           | 9         | 1.3%    |
| Puma             | 8         | 1.15%   |
| CometLake        | 8         | 1.15%   |
| Bonnell          | 8         | 1.15%   |
| Zen              | 6         | 0.86%   |
| Goldmont plus    | 5         | 0.72%   |
| K10              | 4         | 0.58%   |
| Jaguar           | 4         | 0.58%   |
| P6               | 3         | 0.43%   |
| K8 Hammer        | 3         | 0.43%   |
| Tremont          | 2         | 0.29%   |
| Piledriver       | 2         | 0.29%   |
| Nehalem          | 2         | 0.29%   |
| K10 Llano        | 2         | 0.29%   |
| Alderlake Hybrid | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 479       | 54.87%  |
| AMD    | 200       | 22.91%  |
| Nvidia | 194       | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 6.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 46        | 5.12%   |
| AMD Renoir                                                                               | 42        | 4.68%   |
| Intel UHD Graphics 620                                                                   | 35        | 3.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 3.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 3.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 2.9%    |
| Intel HD Graphics 620                                                                    | 25        | 2.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 2.56%   |
| Intel HD Graphics 5500                                                                   | 21        | 2.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 2.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 1.89%   |
| AMD Cezanne                                                                              | 17        | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 1.45%   |
| Intel HD Graphics 530                                                                    | 12        | 1.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.34%   |
| Nvidia GP108M [GeForce MX250]                                                            | 11        | 1.22%   |
| Intel Iris Plus Graphics G7                                                              | 9         | 1%      |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 9         | 1%      |
| Intel HD Graphics 630                                                                    | 8         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 0.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 8         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 0.78%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 7         | 0.78%   |
| Intel HD Graphics 500                                                                    | 7         | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 0.78%   |
| AMD Lucienne                                                                             | 7         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.67%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.56%   |
| Nvidia GP107M [GeForce MX350]                                                            | 5         | 0.56%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.56%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 0.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 0.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5         | 0.56%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.45%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.45%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 4         | 0.45%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 4         | 0.45%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 4         | 0.45%   |
| Nvidia GF119M [GeForce 410M]                                                             | 4         | 0.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.45%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 0.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.45%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 4         | 0.45%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 4         | 0.45%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.45%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 4         | 0.45%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 316       | 45.4%   |
| 1 x AMD        | 135       | 19.4%   |
| Intel + Nvidia | 128       | 18.39%  |
| 1 x Nvidia     | 52        | 7.47%   |
| Intel + AMD    | 36        | 5.17%   |
| AMD + Nvidia   | 15        | 2.16%   |
| 2 x AMD        | 14        | 2.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 605       | 86.06%  |
| Proprietary | 87        | 12.38%  |
| Unknown     | 11        | 1.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 395       | 55.71%  |
| 1.01-2.0   | 98        | 13.82%  |
| 0.01-0.5   | 97        | 13.68%  |
| 3.01-4.0   | 50        | 7.05%   |
| 0.51-1.0   | 50        | 7.05%   |
| 7.01-8.0   | 10        | 1.41%   |
| 5.01-6.0   | 6         | 0.85%   |
| 2.01-3.0   | 2         | 0.28%   |
| 8.01-16.0  | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 170       | 21.44%  |
| LG Display              | 122       | 15.38%  |
| Chimei Innolux          | 89        | 11.22%  |
| Samsung Electronics     | 88        | 11.1%   |
| BOE                     | 78        | 9.84%   |
| Sharp                   | 27        | 3.4%    |
| Apple                   | 24        | 3.03%   |
| Dell                    | 21        | 2.65%   |
| Lenovo                  | 20        | 2.52%   |
| Hewlett-Packard         | 14        | 1.77%   |
| Chi Mei Optoelectronics | 14        | 1.77%   |
| InfoVision              | 10        | 1.26%   |
| PANDA                   | 9         | 1.13%   |
| Goldstar                | 9         | 1.13%   |
| AOC                     | 8         | 1.01%   |
| Acer                    | 7         | 0.88%   |
| LG Philips              | 6         | 0.76%   |
| Iiyama                  | 5         | 0.63%   |
| Eizo                    | 5         | 0.63%   |
| CSO                     | 5         | 0.63%   |
| BenQ                    | 5         | 0.63%   |
| Ancor Communications    | 5         | 0.63%   |
| HannStar                | 4         | 0.5%    |
| Gericom                 | 4         | 0.5%    |
| CPT                     | 4         | 0.5%    |
| Toshiba                 | 3         | 0.38%   |
| Philips                 | 3         | 0.38%   |
| Panasonic               | 3         | 0.38%   |
| LGD                     | 3         | 0.38%   |
| TMX                     | 2         | 0.25%   |
| Sony                    | 2         | 0.25%   |
| CMN                     | 2         | 0.25%   |
| ASUSTek Computer        | 2         | 0.25%   |
| Vestel Elektronik       | 1         | 0.13%   |
| Unknown                 | 1         | 0.13%   |
| TM@                     | 1         | 0.13%   |
| Tianma XM               | 1         | 0.13%   |
| TCL                     | 1         | 0.13%   |
| SDC                     | 1         | 0.13%   |
| Onkyo                   | 1         | 0.13%   |
| Medion Akoya            | 1         | 0.13%   |
| Medion                  | 1         | 0.13%   |
| LPL                     | 1         | 0.13%   |
| LOE                     | 1         | 0.13%   |
| Lenovo Group Limited    | 1         | 0.13%   |
| KDB                     | 1         | 0.13%   |
| GRM                     | 1         | 0.13%   |
| Fujitsu Siemens         | 1         | 0.13%   |
| EXP                     | 1         | 0.13%   |
| Compal                  | 1         | 0.13%   |
| CHI                     | 1         | 0.13%   |
| CHD                     | 1         | 0.13%   |
| ANX                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.99%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch                 | 8         | 0.99%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.86%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.74%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.62%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 5         | 0.62%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 4         | 0.49%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch      | 4         | 0.49%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 309x174mm 14.0-inch        | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO1136 2560x1440 309x174mm 14.0-inch        | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.49%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.37%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.37%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch  | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 3         | 0.37%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.37%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch              | 3         | 0.37%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.37%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 3         | 0.37%   |
| InfoVision LCD Monitor IVO8C69 1920x1080 309x174mm 14.0-inch          | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch       | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch       | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.37%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                 | 3         | 0.37%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 3         | 0.37%   |
| BOE LCD Monitor BOE0694 1920x1080 380x210mm 17.1-inch                 | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 3         | 0.37%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 3         | 0.37%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch               | 2         | 0.25%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 0.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 2         | 0.25%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.25%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 2         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 351       | 46.99%  |
| 1366x768 (WXGA)    | 147       | 19.68%  |
| 1600x900 (HD+)     | 58        | 7.76%   |
| 1280x800 (WXGA)    | 36        | 4.82%   |
| 3840x2160 (4K)     | 33        | 4.42%   |
| 2560x1440 (QHD)    | 32        | 4.28%   |
| 1440x900 (WXGA+)   | 17        | 2.28%   |
| 1680x1050 (WSXGA+) | 10        | 1.34%   |
| 2880x1800          | 9         | 1.2%    |
| 1920x1200 (WUXGA)  | 7         | 0.94%   |
| 1024x600           | 6         | 0.8%    |
| 3840x2400          | 5         | 0.67%   |
| 1280x1024 (SXGA)   | 5         | 0.67%   |
| 3440x1440          | 4         | 0.54%   |
| 3200x1800 (QHD+)   | 4         | 0.54%   |
| 2560x1600          | 4         | 0.54%   |
| 3840x1080          | 3         | 0.4%    |
| 2560x1080          | 3         | 0.4%    |
| 1920x540           | 3         | 0.4%    |
| Unknown            | 3         | 0.4%    |
| 800x1280           | 1         | 0.13%   |
| 3456x2160          | 1         | 0.13%   |
| 2288x1287          | 1         | 0.13%   |
| 1680x945           | 1         | 0.13%   |
| 1600x1200          | 1         | 0.13%   |
| 1360x768           | 1         | 0.13%   |
| 1280x720 (HD)      | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 282       | 35.47%  |
| 13      | 111       | 13.96%  |
| 14      | 102       | 12.83%  |
| 17      | 84        | 10.57%  |
| 27      | 36        | 4.53%   |
| 12      | 29        | 3.65%   |
| 23      | 22        | 2.77%   |
| 24      | 20        | 2.52%   |
| Unknown | 16        | 2.01%   |
| 21      | 14        | 1.76%   |
| 11      | 12        | 1.51%   |
| 10      | 10        | 1.26%   |
| 34      | 7         | 0.88%   |
| 31      | 6         | 0.75%   |
| 25      | 6         | 0.75%   |
| 22      | 6         | 0.75%   |
| 19      | 6         | 0.75%   |
| 18      | 6         | 0.75%   |
| 16      | 5         | 0.63%   |
| 54      | 3         | 0.38%   |
| 84      | 2         | 0.25%   |
| 32      | 2         | 0.25%   |
| 142     | 1         | 0.13%   |
| 65      | 1         | 0.13%   |
| 52      | 1         | 0.13%   |
| 49      | 1         | 0.13%   |
| 47      | 1         | 0.13%   |
| 39      | 1         | 0.13%   |
| 28      | 1         | 0.13%   |
| 20      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 438       | 55.44%  |
| 201-300        | 104       | 13.16%  |
| 351-400        | 96        | 12.15%  |
| 501-600        | 72        | 9.11%   |
| 401-500        | 28        | 3.54%   |
| 601-700        | 16        | 2.03%   |
| Unknown        | 16        | 2.03%   |
| 701-800        | 9         | 1.14%   |
| 1001-1500      | 7         | 0.89%   |
| 1501-2000      | 2         | 0.25%   |
| More than 2000 | 1         | 0.13%   |
| 801-900        | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 582       | 82.79%  |
| 16/10   | 90        | 12.8%   |
| Unknown | 12        | 1.71%   |
| 21/9    | 7         | 1%      |
| 5/4     | 5         | 0.71%   |
| 32/9    | 2         | 0.28%   |
| 3/2     | 2         | 0.28%   |
| 4/3     | 1         | 0.14%   |
| 1.00    | 1         | 0.14%   |
| 0.62    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 282       | 35.61%  |
| 81-90          | 168       | 21.21%  |
| 121-130        | 75        | 9.47%   |
| 71-80          | 45        | 5.68%   |
| 201-250        | 45        | 5.68%   |
| 301-350        | 36        | 4.55%   |
| 61-70          | 29        | 3.66%   |
| 351-500        | 16        | 2.02%   |
| Unknown        | 16        | 2.02%   |
| 251-300        | 15        | 1.89%   |
| 151-200        | 13        | 1.64%   |
| 51-60          | 12        | 1.52%   |
| 41-50          | 10        | 1.26%   |
| 131-140        | 9         | 1.14%   |
| More than 1000 | 8         | 1.01%   |
| 141-150        | 5         | 0.63%   |
| 111-120        | 3         | 0.38%   |
| 501-1000       | 3         | 0.38%   |
| 91-100         | 2         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 350       | 44.81%  |
| 101-120       | 198       | 25.35%  |
| 51-100        | 125       | 16.01%  |
| 161-240       | 62        | 7.94%   |
| More than 240 | 24        | 3.07%   |
| Unknown       | 16        | 2.05%   |
| 1-50          | 6         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 571       | 79.75%  |
| 2     | 108       | 15.08%  |
| 3     | 17        | 2.37%   |
| 0     | 17        | 2.37%   |
| 4     | 3         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 425       | 37.64%  |
| Realtek Semiconductor             | 326       | 28.88%  |
| Qualcomm Atheros                  | 136       | 12.05%  |
| Broadcom                          | 64        | 5.67%   |
| Ralink                            | 13        | 1.15%   |
| Broadcom Limited                  | 13        | 1.15%   |
| Sierra Wireless                   | 12        | 1.06%   |
| Marvell Technology Group          | 12        | 1.06%   |
| Ericsson Business Mobile Networks | 12        | 1.06%   |
| MediaTek                          | 10        | 0.89%   |
| Hewlett-Packard                   | 9         | 0.8%    |
| Lenovo                            | 8         | 0.71%   |
| Huawei Technologies               | 8         | 0.71%   |
| Fibocom                           | 7         | 0.62%   |
| Dell                              | 7         | 0.62%   |
| DisplayLink                       | 6         | 0.53%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.35%   |
| Nvidia                            | 4         | 0.35%   |
| NetGear                           | 4         | 0.35%   |
| JMicron Technology                | 4         | 0.35%   |
| Edimax Technology                 | 4         | 0.35%   |
| ASIX Electronics                  | 4         | 0.35%   |
| ZyXEL Communications              | 3         | 0.27%   |
| TP-Link                           | 3         | 0.27%   |
| Samsung Electronics               | 3         | 0.27%   |
| Ralink Technology                 | 3         | 0.27%   |
| Qualcomm                          | 3         | 0.27%   |
| Google                            | 3         | 0.27%   |
| Xiaomi                            | 2         | 0.18%   |
| Qualcomm Atheros Communications   | 2         | 0.18%   |
| Linksys                           | 2         | 0.18%   |
| D-Link System                     | 2         | 0.18%   |
| ASUSTek Computer                  | 2         | 0.18%   |
| Apple                             | 2         | 0.18%   |
| Sitecom Europe                    | 1         | 0.09%   |
| Research In Motion                | 1         | 0.09%   |
| Motorola PCS                      | 1         | 0.09%   |
| Manta                             | 1         | 0.09%   |
| Cypress Semiconductor             | 1         | 0.09%   |
| Conexant Systems                  | 1         | 0.09%   |
| Attansic Technology               | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 217       | 15.53%  |
| Intel Wi-Fi 6 AX200                                                     | 61        | 4.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 47        | 3.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 45        | 3.22%   |
| Intel Wireless 8265 / 8275                                              | 40        | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 33        | 2.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 29        | 2.08%   |
| Intel Wireless 7265                                                     | 28        | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 27        | 1.93%   |
| Intel Wireless 8260                                                     | 26        | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 1.65%   |
| Intel Wireless 7260                                                     | 19        | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 1.15%   |
| Intel Wireless 3165                                                     | 16        | 1.15%   |
| Intel Ethernet Connection (6) I219-V                                    | 16        | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 1.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 1.07%   |
| Intel Centrino Ultimate-N 6300                                          | 15        | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 1%      |
| Intel Wi-Fi 6 AX201                                                     | 13        | 0.93%   |
| Intel Ethernet Connection (4) I219-V                                    | 13        | 0.93%   |
| Intel Ethernet Connection I219-LM                                       | 12        | 0.86%   |
| Intel Ethernet Connection I218-LM                                       | 12        | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                                   | 11        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 0.72%   |
| Intel Wireless-AC 9260                                                  | 10        | 0.72%   |
| Intel WiFi Link 5100                                                    | 10        | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 9         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                                | 9         | 0.64%   |
| Intel Wireless 3160                                                     | 8         | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 0.57%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 8         | 0.57%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 7         | 0.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                                   | 7         | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 0.5%    |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.43%   |
| Intel Ethernet Connection I219-V                                        | 6         | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                   | 6         | 0.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.43%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 6         | 0.43%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.43%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 6         | 0.43%   |
| Sierra Wireless EM7455                                                  | 5         | 0.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.36%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 5         | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 414       | 56.02%  |
| Qualcomm Atheros                | 113       | 15.29%  |
| Realtek Semiconductor           | 81        | 10.96%  |
| Broadcom                        | 51        | 6.9%    |
| Ralink                          | 13        | 1.76%   |
| Sierra Wireless                 | 12        | 1.62%   |
| MediaTek                        | 10        | 1.35%   |
| Broadcom Limited                | 7         | 0.95%   |
| Fibocom                         | 6         | 0.81%   |
| NetGear                         | 4         | 0.54%   |
| Edimax Technology               | 4         | 0.54%   |
| Dell                            | 4         | 0.54%   |
| ZyXEL Communications            | 3         | 0.41%   |
| TP-Link                         | 3         | 0.41%   |
| Ralink Technology               | 3         | 0.41%   |
| Qualcomm Atheros Communications | 2         | 0.27%   |
| Qualcomm                        | 2         | 0.27%   |
| D-Link System                   | 2         | 0.27%   |
| ASUSTek Computer                | 2         | 0.27%   |
| Sitecom Europe                  | 1         | 0.14%   |
| Linksys                         | 1         | 0.14%   |
| Hewlett-Packard                 | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 61        | 8.24%   |
| Intel Wireless 8265 / 8275                                              | 40        | 5.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 33        | 4.46%   |
| Intel Wireless 7265                                                     | 28        | 3.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 27        | 3.65%   |
| Intel Wireless 8260                                                     | 26        | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 3.11%   |
| Intel Wireless 7260                                                     | 19        | 2.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 2.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 2.16%   |
| Intel Wireless 3165                                                     | 16        | 2.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 2.03%   |
| Intel Centrino Ultimate-N 6300                                          | 15        | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 1.35%   |
| Intel Wireless-AC 9260                                                  | 10        | 1.35%   |
| Intel WiFi Link 5100                                                    | 10        | 1.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.35%   |
| Intel Wireless 3160                                                     | 8         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.08%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 8         | 1.08%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.95%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 7         | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 0.95%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.81%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 6         | 0.81%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.81%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 6         | 0.81%   |
| Sierra Wireless EM7455                                                  | 5         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 5         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.68%   |
| Sierra Wireless MC8305 Modem                                            | 4         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.54%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 4         | 0.54%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 4         | 0.54%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.41%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.41%   |
| Dell Wireless 5809e Gobiâ¢ 4G LTE Mobile Broadband Card             | 3         | 0.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.41%   |
| ZyXEL ZyXEL Dual-Band Wireless AC USB Adapter                           | 2         | 0.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 295       | 47.73%  |
| Intel                         | 190       | 30.74%  |
| Qualcomm Atheros              | 43        | 6.96%   |
| Broadcom                      | 24        | 3.88%   |
| Marvell Technology Group      | 12        | 1.94%   |
| Lenovo                        | 8         | 1.29%   |
| DisplayLink                   | 6         | 0.97%   |
| Broadcom Limited              | 6         | 0.97%   |
| OnePlus Technology (Shenzhen) | 4         | 0.65%   |
| Nvidia                        | 4         | 0.65%   |
| JMicron Technology            | 4         | 0.65%   |
| ASIX Electronics              | 4         | 0.65%   |
| Samsung Electronics           | 3         | 0.49%   |
| Huawei Technologies           | 3         | 0.49%   |
| Xiaomi                        | 2         | 0.32%   |
| Apple                         | 2         | 0.32%   |
| Research In Motion            | 1         | 0.16%   |
| Qualcomm                      | 1         | 0.16%   |
| Motorola PCS                  | 1         | 0.16%   |
| Linksys                       | 1         | 0.16%   |
| Hewlett-Packard               | 1         | 0.16%   |
| Fibocom                       | 1         | 0.16%   |
| Cypress Semiconductor         | 1         | 0.16%   |
| Attansic Technology           | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 217       | 34.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 47        | 7.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 7.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 29        | 4.64%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 2.56%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 2.08%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 1.92%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 1.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 1.44%   |
| Intel 82567LM Gigabit Network Connection                          | 9         | 1.44%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 1.12%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.8%    |
| Lenovo USB-C Dock Ethernet                                        | 5         | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.8%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.64%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:63F1CF71                        | 4         | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.64%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.64%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.64%   |
| DisplayLink Dell Universal Dock D6000                             | 4         | 0.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 4         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3         | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.48%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 0.48%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.48%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.48%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 3         | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.32%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.32%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.32%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.32%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.32%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.32%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.32%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.32%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.32%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.32%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.32%   |
| Intel Ethernet Connection (10) I219-LM                            | 2         | 0.32%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.32%   |
| Huawei E353/E3131                                                 | 2         | 0.32%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 688       | 52.8%   |
| Ethernet | 583       | 44.74%  |
| Modem    | 31        | 2.38%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 573       | 77.96%  |
| Ethernet | 162       | 22.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 531       | 76.51%  |
| 1     | 145       | 20.89%  |
| 3     | 12        | 1.73%   |
| 0     | 6         | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 628       | 89.2%   |
| Yes  | 76        | 10.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 289       | 53.72%  |
| Realtek Semiconductor           | 49        | 9.11%   |
| Qualcomm Atheros Communications | 46        | 8.55%   |
| Broadcom                        | 31        | 5.76%   |
| Lite-On Technology              | 22        | 4.09%   |
| IMC Networks                    | 17        | 3.16%   |
| Foxconn / Hon Hai               | 15        | 2.79%   |
| Apple                           | 15        | 2.79%   |
| Hewlett-Packard                 | 13        | 2.42%   |
| Dell                            | 9         | 1.67%   |
| Cambridge Silicon Radio         | 9         | 1.67%   |
| Toshiba                         | 7         | 1.3%    |
| Foxconn International           | 4         | 0.74%   |
| Ralink                          | 3         | 0.56%   |
| MediaTek                        | 2         | 0.37%   |
| Alps Electric                   | 2         | 0.37%   |
| Realtek                         | 1         | 0.19%   |
| i.Tech Dynamic Limited          | 1         | 0.19%   |
| Edimax Technology               | 1         | 0.19%   |
| Belkin Components               | 1         | 0.19%   |
| ASUSTek Computer                | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 124       | 23.05%  |
| Intel AX200 Bluetooth                                                               | 58        | 10.78%  |
| Intel Bluetooth Device                                                              | 38        | 7.06%   |
| Realtek Bluetooth Radio                                                             | 35        | 6.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 31        | 5.76%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 15        | 2.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 13        | 2.42%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 12        | 2.23%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 2.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 2.04%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 1.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 10        | 1.86%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 1.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 1.49%   |
| Apple Bluetooth Host Controller                                                     | 8         | 1.49%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 1.3%    |
| IMC Networks Bluetooth Radio                                                        | 7         | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.12%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.93%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 4         | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 0.74%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 0.74%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 0.74%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 0.74%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.56%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.56%   |
| Lite-On Wireless_Device                                                             | 3         | 0.56%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.56%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.56%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.56%   |
| Broadcom BCM2045 Bluetooth                                                          | 3         | 0.56%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.56%   |
| Toshiba BCM43142A0                                                                  | 2         | 0.37%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.37%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.37%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.37%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.37%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.37%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 2         | 0.37%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.19%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.19%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.19%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.19%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.19%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.19%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.19%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.19%   |
| MediaTek Wireless_Device                                                            | 1         | 0.19%   |
| MediaTek MT7630e Bluetooth Adapter                                                  | 1         | 0.19%   |
| IMC Networks Bluetooth                                                              | 1         | 0.19%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.19%   |
| i.Tech Dynamic Limited BlueCON U2                                                   | 1         | 0.19%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.19%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 543       | 62.63%  |
| AMD                         | 160       | 18.45%  |
| Nvidia                      | 87        | 10.03%  |
| Lenovo                      | 8         | 0.92%   |
| Apple                       | 8         | 0.92%   |
| C-Media Electronics         | 7         | 0.81%   |
| Texas Instruments           | 6         | 0.69%   |
| Logitech                    | 5         | 0.58%   |
| GN Netcom                   | 5         | 0.58%   |
| Realtek Semiconductor       | 4         | 0.46%   |
| Plantronics                 | 4         | 0.46%   |
| Sennheiser Communications   | 3         | 0.35%   |
| Yamaha                      | 2         | 0.23%   |
| SteelSeries ApS             | 2         | 0.23%   |
| Sony                        | 2         | 0.23%   |
| Hewlett-Packard             | 2         | 0.23%   |
| Focusrite-Novation          | 2         | 0.23%   |
| Creative Technology         | 2         | 0.23%   |
| ZOOM                        | 1         | 0.12%   |
| XMOS                        | 1         | 0.12%   |
| Tenx Technology             | 1         | 0.12%   |
| Samsung Electronics         | 1         | 0.12%   |
| Roland                      | 1         | 0.12%   |
| No brand                    | 1         | 0.12%   |
| Microsoft                   | 1         | 0.12%   |
| Mackie Designs              | 1         | 0.12%   |
| M-Audio                     | 1         | 0.12%   |
| Kingston Technology         | 1         | 0.12%   |
| GYROCOM C&C                 | 1         | 0.12%   |
| Generalplus Technology      | 1         | 0.12%   |
| FiiO Electronics Technology | 1         | 0.12%   |
| Blue Microphones            | 1         | 0.12%   |
| AudioQuest                  | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 95        | 9.02%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 89        | 8.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 64        | 6.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 56        | 5.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 54        | 5.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 2.94%   |
| Intel 8 Series HD Audio Controller                                                                | 31        | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 28        | 2.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 26        | 2.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 25        | 2.37%   |
| Intel Broadwell-U Audio Controller                                                                | 25        | 2.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 23        | 2.18%   |
| Intel Cannon Lake PCH cAVS                                                                        | 23        | 2.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 1.99%   |
| AMD FCH Azalia Controller                                                                         | 20        | 1.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 1.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 19        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 1.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 15        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 1.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 1.14%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 10        | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.76%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 0.76%   |
| Apple Audio Device                                                                                | 8         | 0.76%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 0.66%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.57%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6         | 0.57%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 6         | 0.57%   |
| AMD High Definition Audio Controller                                                              | 6         | 0.57%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.47%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 5         | 0.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 0.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 5         | 0.47%   |
| Realtek Semiconductor USB Audio                                                                   | 4         | 0.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.38%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.38%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.38%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.38%   |
| Nvidia Audio device                                                                               | 4         | 0.38%   |
| Intel Jasper Lake HD Audio                                                                        | 4         | 0.38%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.28%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.28%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.28%   |
| Logitech USB Headset                                                                              | 3         | 0.28%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.28%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.28%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 137       | 31.57%  |
| SK hynix              | 99        | 22.81%  |
| Micron Technology     | 62        | 14.29%  |
| Kingston              | 34        | 7.83%   |
| Unknown               | 27        | 6.22%   |
| Crucial               | 24        | 5.53%   |
| Ramaxel Technology    | 10        | 2.3%    |
| Corsair               | 10        | 2.3%    |
| Elpida                | 9         | 2.07%   |
| Unknown (ABCD)        | 5         | 1.15%   |
| A-DATA Technology     | 3         | 0.69%   |
| Silicon Power         | 2         | 0.46%   |
| Nanya Technology      | 2         | 0.46%   |
| Goodram               | 2         | 0.46%   |
| G.Skill               | 2         | 0.46%   |
| Vaseky                | 1         | 0.23%   |
| Transcend             | 1         | 0.23%   |
| Smart                 | 1         | 0.23%   |
| Kingmax Semiconductor | 1         | 0.23%   |
| CSX                   | 1         | 0.23%   |
| Avant                 | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 13        | 2.8%    |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s               | 8         | 1.72%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 7         | 1.51%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 6         | 1.29%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s           | 6         | 1.29%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 5         | 1.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 5         | 1.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 1.08%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 1.08%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 1.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 1.08%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 1.08%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.08%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 5         | 1.08%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 4         | 0.86%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 4         | 0.86%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 4         | 0.86%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 4         | 0.86%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s               | 4         | 0.86%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s                | 4         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 3         | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.65%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 3         | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 3         | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.65%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 3         | 0.65%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s    | 3         | 0.65%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 3         | 0.65%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 3         | 0.65%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s               | 3         | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.65%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 3         | 0.65%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.65%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 3         | 0.65%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 3         | 0.65%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s             | 3         | 0.65%   |
| Corsair RAM CMSX8GX3M1A1600C10 8192MB SODIMM DDR3 1600MT/s          | 3         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 2         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 2         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 2         | 0.43%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 2         | 0.43%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 2         | 0.43%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                    | 2         | 0.43%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                    | 2         | 0.43%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 2         | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.43%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                         | 2         | 0.43%   |
| Samsung RAM Module 8GB SODIMM DDR3 1600MT/s                         | 2         | 0.43%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 2         | 0.43%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 186       | 50.54%  |
| DDR3    | 121       | 32.88%  |
| LPDDR4  | 22        | 5.98%   |
| DDR2    | 17        | 4.62%   |
| SDRAM   | 10        | 2.72%   |
| LPDDR3  | 10        | 2.72%   |
| Unknown | 2         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 331       | 89.7%   |
| Row Of Chips | 34        | 9.21%   |
| Chip         | 3         | 0.81%   |
| DIMM         | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 166       | 41.6%   |
| 4096  | 100       | 25.06%  |
| 16384 | 73        | 18.3%   |
| 2048  | 44        | 11.03%  |
| 1024  | 11        | 2.76%   |
| 32768 | 5         | 1.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 87        | 22.19%  |
| 1600    | 80        | 20.41%  |
| 3200    | 71        | 18.11%  |
| 2400    | 35        | 8.93%   |
| 1333    | 22        | 5.61%   |
| 2133    | 19        | 4.85%   |
| 1334    | 16        | 4.08%   |
| 667     | 10        | 2.55%   |
| 4267    | 7         | 1.79%   |
| Unknown | 7         | 1.79%   |
| 4199    | 5         | 1.28%   |
| 3266    | 5         | 1.28%   |
| 2048    | 5         | 1.28%   |
| 1867    | 5         | 1.28%   |
| 1067    | 5         | 1.28%   |
| 4266    | 4         | 1.02%   |
| 4800    | 3         | 0.77%   |
| 533     | 2         | 0.51%   |
| 6400    | 1         | 0.26%   |
| 3733    | 1         | 0.26%   |
| 800     | 1         | 0.26%   |
| 333     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 42.86%  |
| Samsung Electronics | 2         | 28.57%  |
| Canon               | 2         | 28.57%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung SCX-4300 Series                               | 1         | 14.29%  |
| Samsung C48x Series Color Laser Multifunction Printer | 1         | 14.29%  |
| HP LaserJet 1200                                      | 1         | 14.29%  |
| HP ENVY Pro 6400 series                               | 1         | 14.29%  |
| HP Deskjet 3520 series                                | 1         | 14.29%  |
| Canon PIXMA iX6850 Printer                            | 1         | 14.29%  |
| Canon MG2100 series                                   | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |
| Canon CanoScan                | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 193       | 31.74%  |
| IMC Networks                           | 66        | 10.86%  |
| Acer                                   | 64        | 10.53%  |
| Microdia                               | 40        | 6.58%   |
| Realtek Semiconductor                  | 34        | 5.59%   |
| Sunplus Innovation Technology          | 33        | 5.43%   |
| Quanta                                 | 29        | 4.77%   |
| Lite-On Technology                     | 22        | 3.62%   |
| Suyin                                  | 21        | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 21        | 3.45%   |
| Apple                                  | 16        | 2.63%   |
| Syntek                                 | 13        | 2.14%   |
| Luxvisions Innotech Limited            | 6         | 0.99%   |
| Alcor Micro                            | 6         | 0.99%   |
| Primax Electronics                     | 5         | 0.82%   |
| Ricoh                                  | 4         | 0.66%   |
| OmniVision Technologies                | 4         | 0.66%   |
| Logitech                               | 4         | 0.66%   |
| Silicon Motion                         | 3         | 0.49%   |
| Samsung Electronics                    | 3         | 0.49%   |
| Lenovo                                 | 3         | 0.49%   |
| Z-Star Microelectronics                | 2         | 0.33%   |
| Sony                                   | 2         | 0.33%   |
| Microsoft                              | 2         | 0.33%   |
| icSpring                               | 2         | 0.33%   |
| SunplusIT                              | 1         | 0.16%   |
| Sunplus Technology                     | 1         | 0.16%   |
| Nebraska Furniture Mart                | 1         | 0.16%   |
| Jieli Technology                       | 1         | 0.16%   |
| Goertek Electronics                    | 1         | 0.16%   |
| Genesys Logic                          | 1         | 0.16%   |
| Generalplus Technology                 | 1         | 0.16%   |
| GEMBIRD                                | 1         | 0.16%   |
| DigiTech                               | 1         | 0.16%   |
| Alpha Imaging Technology               | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 45        | 7.38%   |
| IMC Networks Integrated Camera                      | 34        | 5.57%   |
| Acer Integrated Camera                              | 22        | 3.61%   |
| Microdia Integrated_Webcam_HD                       | 20        | 3.28%   |
| Chicony HD WebCam                                   | 17        | 2.79%   |
| Chicony HP HD Camera                                | 15        | 2.46%   |
| Quanta HD User Facing                               | 10        | 1.64%   |
| Lite-On HP HD Camera                                | 10        | 1.64%   |
| Sunplus Integrated_Webcam_HD                        | 9         | 1.48%   |
| Realtek USB2.0 HD UVC WebCam                        | 9         | 1.48%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 9         | 1.48%   |
| Chicony TOSHIBA Web Camera - HD                     | 9         | 1.48%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 8         | 1.31%   |
| Chicony VGA WebCam                                  | 8         | 1.31%   |
| Realtek Integrated_Webcam_HD                        | 7         | 1.15%   |
| Lite-On Integrated Camera                           | 7         | 1.15%   |
| Chicony USB2.0 HD UVC WebCam                        | 7         | 1.15%   |
| Chicony Integrated HP HD Webcam                     | 7         | 1.15%   |
| Chicony HP HD Webcam                                | 7         | 1.15%   |
| Acer Lenovo EasyCamera                              | 7         | 1.15%   |
| Quanta HP HD Camera                                 | 6         | 0.98%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 6         | 0.98%   |
| Acer SunplusIT Integrated Camera                    | 6         | 0.98%   |
| Acer BisonCam, NB Pro                               | 6         | 0.98%   |
| Syntek Integrated Camera                            | 5         | 0.82%   |
| Realtek HD WebCam                                   | 5         | 0.82%   |
| Chicony USB 2.0 Camera                              | 5         | 0.82%   |
| Chicony Integrated Camera (1280x720@30)             | 5         | 0.82%   |
| Chicony HP TrueVision HD Camera                     | 5         | 0.82%   |
| Chicony HD User Facing                              | 5         | 0.82%   |
| Chicony FJ Camera                                   | 5         | 0.82%   |
| Apple FaceTime HD Camera                            | 5         | 0.82%   |
| Acer Lenovo Integrated Webcam                       | 5         | 0.82%   |
| Syntek Lenovo EasyCamera                            | 4         | 0.66%   |
| Sunplus HD WebCam                                   | 4         | 0.66%   |
| OmniVision OV2640 Webcam                            | 4         | 0.66%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 4         | 0.66%   |
| Chicony Lenovo EasyCamera                           | 4         | 0.66%   |
| Chicony EasyCamera                                  | 4         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 4         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 4         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 0.66%   |
| Apple iPhone 5/5C/5S/6/SE                           | 4         | 0.66%   |
| Apple Built-in iSight                               | 4         | 0.66%   |
| Acer ThinkPad Integrated Camera                     | 4         | 0.66%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 0.49%   |
| Suyin Acer CrystalEye Webcam                        | 3         | 0.49%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 3         | 0.49%   |
| Sunplus Laptop Integrated WebCam HD                 | 3         | 0.49%   |
| Sunplus HP HD Webcam [Fixed]                        | 3         | 0.49%   |
| Sunplus FHD Camera Microphone                       | 3         | 0.49%   |
| Sunplus Asus Webcam                                 | 3         | 0.49%   |
| Samsung Galaxy series, misc. (MTP mode)             | 3         | 0.49%   |
| Realtek Lenovo EasyCamera                           | 3         | 0.49%   |
| Quanta VGA WebCam                                   | 3         | 0.49%   |
| Microdia USB 2.0 Camera                             | 3         | 0.49%   |
| Microdia Integrated Webcam                          | 3         | 0.49%   |
| Microdia Dell Integrated HD Webcam                  | 3         | 0.49%   |
| Luxvisions Innotech Limited HP HD Camera            | 3         | 0.49%   |
| Chicony USB2.0 Camera                               | 3         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 81        | 40.1%   |
| Synaptics                  | 69        | 34.16%  |
| Shenzhen Goodix Technology | 19        | 9.41%   |
| AuthenTec                  | 13        | 6.44%   |
| Upek                       | 10        | 4.95%   |
| LighTuning Technology      | 6         | 2.97%   |
| Elan Microelectronics      | 2         | 0.99%   |
| STMicroelectronics         | 1         | 0.5%    |
| Focal-systems.Corp         | 1         | 0.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 36        | 17.73%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 10.84%  |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 6.4%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 4.93%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 4.93%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 4.43%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 4.43%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 4.43%   |
| Validity Sensors VFS491                                                    | 6         | 2.96%   |
| Unknown                                                                    | 6         | 2.96%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.46%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.46%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.46%   |
| AuthenTec AES2810                                                          | 5         | 2.46%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.97%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.97%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 1.97%   |
| Synaptics WBDI Device                                                      | 3         | 1.48%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.48%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.48%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.99%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.99%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.99%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.99%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 0.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.99%   |
| Elan ELAN:Fingerprint                                                      | 2         | 0.99%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.49%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.49%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.49%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.49%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.49%   |
| AuthenTec AES1600                                                          | 1         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 47        | 53.41%  |
| Broadcom              | 23        | 26.14%  |
| Upek                  | 7         | 7.95%   |
| Lenovo                | 7         | 7.95%   |
| O2 Micro              | 2         | 2.27%   |
| SCM Microsystems      | 1         | 1.14%   |
| Advanced Card Systems | 1         | 1.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 47        | 53.41%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 10.23%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 7.95%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 7.95%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 6.82%   |
| Broadcom 58200                                                               | 5         | 5.68%   |
| Broadcom 5880                                                                | 3         | 3.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.27%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.14%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 382       | 53.28%  |
| 1     | 255       | 35.56%  |
| 2     | 54        | 7.53%   |
| 3     | 19        | 2.65%   |
| 4     | 4         | 0.56%   |
| 8     | 1         | 0.14%   |
| 6     | 1         | 0.14%   |
| 5     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 199       | 45.64%  |
| Chipcard                 | 69        | 15.83%  |
| Graphics card            | 54        | 12.39%  |
| Net/wireless             | 41        | 9.4%    |
| Multimedia controller    | 17        | 3.9%    |
| Sound                    | 10        | 2.29%   |
| Bluetooth                | 9         | 2.06%   |
| Communication controller | 8         | 1.83%   |
| Camera                   | 8         | 1.83%   |
| Card reader              | 5         | 1.15%   |
| Storage                  | 4         | 0.92%   |
| Net/ethernet             | 4         | 0.92%   |
| Unassigned class         | 3         | 0.69%   |
| Modem                    | 2         | 0.46%   |
| Flash memory             | 2         | 0.46%   |
| Firewire controller      | 1         | 0.23%   |


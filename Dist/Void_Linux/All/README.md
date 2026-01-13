Void Linux - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Void Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Void_Linux/Desktop/README.md) and [notebooks](/Dist/Void_Linux/Notebook/README.md).

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

Total: 452

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| VX            | B75                         | Desktop     | [48ca782567](https://linux-hardware.org/?probe=48ca782567) | Dec 24, 2025 |
| Lenovo        | T480                        | Notebook    | [c03d9a28e8](https://linux-hardware.org/?probe=c03d9a28e8) | Dec 22, 2025 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [34148ae1ec](https://linux-hardware.org/?probe=34148ae1ec) | Dec 21, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [8a1ff23d12](https://linux-hardware.org/?probe=8a1ff23d12) | Dec 18, 2025 |
| Gigabyte      | X870E AORUS PRO ICE         | Desktop     | [44aaa1503a](https://linux-hardware.org/?probe=44aaa1503a) | Dec 18, 2025 |
| Lenovo        | ThinkPad T480 20L6S0AQ00    | Notebook    | [d22725c8f4](https://linux-hardware.org/?probe=d22725c8f4) | Dec 15, 2025 |
| HP            | ProBook 455 G2              | Notebook    | [b6742cb85a](https://linux-hardware.org/?probe=b6742cb85a) | Dec 12, 2025 |
| HP            | ProBook 455 G2              | Notebook    | [9563214ac8](https://linux-hardware.org/?probe=9563214ac8) | Dec 11, 2025 |
| ASUSTek       | K61IC                       | Notebook    | [65e78812d6](https://linux-hardware.org/?probe=65e78812d6) | Dec 09, 2025 |
| Gigabyte      | X870E AORUS PRO ICE         | Desktop     | [619993e266](https://linux-hardware.org/?probe=619993e266) | Dec 08, 2025 |
| ASUSTek       | ASUS Vivobook S 16 S3607... | Notebook    | [56541110d2](https://linux-hardware.org/?probe=56541110d2) | Dec 08, 2025 |
| Dell          | XPS 15 9500                 | Notebook    | [e5f120ef83](https://linux-hardware.org/?probe=e5f120ef83) | Dec 06, 2025 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [db3c9a81a4](https://linux-hardware.org/?probe=db3c9a81a4) | Dec 04, 2025 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [413375cd44](https://linux-hardware.org/?probe=413375cd44) | Nov 26, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5d2bc435b0](https://linux-hardware.org/?probe=5d2bc435b0) | Nov 24, 2025 |
| Lenovo        | ThinkPad E425 1198CTO       | Notebook    | [c0ec7bd6ac](https://linux-hardware.org/?probe=c0ec7bd6ac) | Nov 21, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [b32334a28b](https://linux-hardware.org/?probe=b32334a28b) | Oct 31, 2025 |
| Lenovo        | IdeaPad Slim 3 15AHP10 8... | Notebook    | [0b81457d0d](https://linux-hardware.org/?probe=0b81457d0d) | Oct 23, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [4aa6152849](https://linux-hardware.org/?probe=4aa6152849) | Oct 22, 2025 |
| Positivo      | R732512BI-15                | Notebook    | [a3d131c053](https://linux-hardware.org/?probe=a3d131c053) | Oct 14, 2025 |
| Positivo      | R732512BI-15                | Notebook    | [70571558f3](https://linux-hardware.org/?probe=70571558f3) | Oct 14, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [093709474e](https://linux-hardware.org/?probe=093709474e) | Oct 07, 2025 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [6440972eb4](https://linux-hardware.org/?probe=6440972eb4) | Oct 01, 2025 |
| ASUSTek       | PRIME X370-A                | Desktop     | [cb5d936b99](https://linux-hardware.org/?probe=cb5d936b99) | Sep 29, 2025 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [84cf546e2e](https://linux-hardware.org/?probe=84cf546e2e) | Sep 29, 2025 |
| HP            | ProLiant DL360 G5           | Server      | [fbb7d7e4c2](https://linux-hardware.org/?probe=fbb7d7e4c2) | Sep 29, 2025 |
| ASUSTek       | X555QG                      | Notebook    | [97e3449156](https://linux-hardware.org/?probe=97e3449156) | Sep 27, 2025 |
| ASUSTek       | X555QG                      | Notebook    | [1c2f1da003](https://linux-hardware.org/?probe=1c2f1da003) | Sep 27, 2025 |
| Lenovo        | IdeaPad 1 15IAU7 82VY       | Notebook    | [a4df077d5f](https://linux-hardware.org/?probe=a4df077d5f) | Sep 26, 2025 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [6d7ef4bf2d](https://linux-hardware.org/?probe=6d7ef4bf2d) | Sep 24, 2025 |
| Lenovo        | ThinkPad E590 20NB000JAD    | Notebook    | [9556c5e3c2](https://linux-hardware.org/?probe=9556c5e3c2) | Sep 21, 2025 |
| Lenovo        | IdeaPad Slim 3 14AHP10 8... | Notebook    | [7adb7226b1](https://linux-hardware.org/?probe=7adb7226b1) | Sep 18, 2025 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [9f64589fd7](https://linux-hardware.org/?probe=9f64589fd7) | Sep 11, 2025 |
| Lenovo        | ThinkPad T520 4242X04       | Notebook    | [7695a117dd](https://linux-hardware.org/?probe=7695a117dd) | Sep 09, 2025 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [c9c9e27029](https://linux-hardware.org/?probe=c9c9e27029) | Sep 06, 2025 |
| Lenovo        | LOQ 15ARP9 83JC             | Notebook    | [b5f8fdb526](https://linux-hardware.org/?probe=b5f8fdb526) | Sep 02, 2025 |
| HP            | 250 G1                      | Notebook    | [1565b9f846](https://linux-hardware.org/?probe=1565b9f846) | Aug 23, 2025 |
| Lenovo        | LOQ 15ARP9 83JC             | Notebook    | [276975cfc2](https://linux-hardware.org/?probe=276975cfc2) | Aug 09, 2025 |
| Lenovo        | LOQ 15ARP9 83JC             | Notebook    | [05fc4aac11](https://linux-hardware.org/?probe=05fc4aac11) | Aug 09, 2025 |
| Vestel        | Calistoga & ICH7M Chipse... | Notebook    | [68cd55edcc](https://linux-hardware.org/?probe=68cd55edcc) | Aug 09, 2025 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [26cc0238cf](https://linux-hardware.org/?probe=26cc0238cf) | Aug 08, 2025 |
| Lenovo        | LOQ 15ARP9 83JC             | Notebook    | [ac9ae75a82](https://linux-hardware.org/?probe=ac9ae75a82) | Aug 07, 2025 |
| Lenovo        | ThinkPad E16 Gen 1 21JTS... | Notebook    | [354d9569e1](https://linux-hardware.org/?probe=354d9569e1) | Aug 06, 2025 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [10179fed97](https://linux-hardware.org/?probe=10179fed97) | Aug 05, 2025 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [40127c6c1e](https://linux-hardware.org/?probe=40127c6c1e) | Aug 04, 2025 |
| ASRock        | B550M-ITX/ac                | Desktop     | [04b9df9f7c](https://linux-hardware.org/?probe=04b9df9f7c) | Jul 21, 2025 |
| Intel         | H55                         | Desktop     | [45f3e53ac8](https://linux-hardware.org/?probe=45f3e53ac8) | Jul 21, 2025 |
| HP            | EliteBook 840 G6            | Notebook    | [7f0dd34eed](https://linux-hardware.org/?probe=7f0dd34eed) | Jul 14, 2025 |
| ASRock        | X870E Taichi Lite           | Desktop     | [8ef3d20c4d](https://linux-hardware.org/?probe=8ef3d20c4d) | Jul 14, 2025 |
| ASRock        | X870E Taichi Lite           | Desktop     | [6ee32c026c](https://linux-hardware.org/?probe=6ee32c026c) | Jul 14, 2025 |
| Lenovo        | 333E                        | Mini pc     | [a22cbd9d23](https://linux-hardware.org/?probe=a22cbd9d23) | Jul 13, 2025 |
| Lenovo        | LOQ 15IRX9 83DV             | Notebook    | [4506dbcf26](https://linux-hardware.org/?probe=4506dbcf26) | Jul 11, 2025 |
| AOpen         | i915GMt-FSA 918ET10I9C0     | Desktop     | [980bb040dd](https://linux-hardware.org/?probe=980bb040dd) | Jul 09, 2025 |
| ASUSTek       | PRIME H510M-E R2.0          | Desktop     | [16a46f3236](https://linux-hardware.org/?probe=16a46f3236) | Jun 30, 2025 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2d6034b14e](https://linux-hardware.org/?probe=2d6034b14e) | Jun 22, 2025 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [a5def4ec2c](https://linux-hardware.org/?probe=a5def4ec2c) | Jun 22, 2025 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [0c1b5ac601](https://linux-hardware.org/?probe=0c1b5ac601) | Jun 22, 2025 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [94dda7255d](https://linux-hardware.org/?probe=94dda7255d) | Jun 16, 2025 |
| Acer          | Nitro AN16-41               | Notebook    | [7ee815feb4](https://linux-hardware.org/?probe=7ee815feb4) | Jun 16, 2025 |
| HP            | Pavilion dv2700             | Notebook    | [ff815a1556](https://linux-hardware.org/?probe=ff815a1556) | Jun 15, 2025 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [bab46c9af6](https://linux-hardware.org/?probe=bab46c9af6) | Jun 15, 2025 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [61098dfeae](https://linux-hardware.org/?probe=61098dfeae) | Jun 13, 2025 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2d806f5a4a](https://linux-hardware.org/?probe=2d806f5a4a) | May 29, 2025 |
| Gigabyte      | X570 UD                     | Desktop     | [516d4e0985](https://linux-hardware.org/?probe=516d4e0985) | May 19, 2025 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f466402c6a](https://linux-hardware.org/?probe=f466402c6a) | May 19, 2025 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [0d1e1a57cb](https://linux-hardware.org/?probe=0d1e1a57cb) | May 17, 2025 |
| Raspberry ... | Raspberry Pi                | Soc         | [38651d332a](https://linux-hardware.org/?probe=38651d332a) | May 09, 2025 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [a43ff37272](https://linux-hardware.org/?probe=a43ff37272) | May 04, 2025 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [b6f235142e](https://linux-hardware.org/?probe=b6f235142e) | May 02, 2025 |
| Dell          | Latitude 5420               | Notebook    | [f2cc25c331](https://linux-hardware.org/?probe=f2cc25c331) | May 01, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [04bc01fc05](https://linux-hardware.org/?probe=04bc01fc05) | Apr 27, 2025 |
| Gigabyte      | Z97X-UD7 TH-CF              | Desktop     | [a8b707ff9c](https://linux-hardware.org/?probe=a8b707ff9c) | Apr 27, 2025 |
| ASUSTek       | X555LAB                     | Notebook    | [400dd86f3a](https://linux-hardware.org/?probe=400dd86f3a) | Apr 26, 2025 |
| HP            | Pavilion dm1                | Notebook    | [9cabc1f3cd](https://linux-hardware.org/?probe=9cabc1f3cd) | Apr 23, 2025 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8078f62d5c](https://linux-hardware.org/?probe=8078f62d5c) | Apr 20, 2025 |
| Acer          | V5-131                      | Notebook    | [c0b1b12d37](https://linux-hardware.org/?probe=c0b1b12d37) | Apr 20, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [c7395705d9](https://linux-hardware.org/?probe=c7395705d9) | Apr 20, 2025 |
| TUXEDO        | Sirius 16 Gen2              | Notebook    | [3b4ba24108](https://linux-hardware.org/?probe=3b4ba24108) | Apr 14, 2025 |
| Dell          | G5 5505                     | Notebook    | [915d9e665b](https://linux-hardware.org/?probe=915d9e665b) | Apr 14, 2025 |
| ASUSTek       | M11AD                       | Desktop     | [19ecbf4c82](https://linux-hardware.org/?probe=19ecbf4c82) | Apr 04, 2025 |
| Lenovo        | IdeaPad Slim 5 15ARP10 8... | Notebook    | [145ce92f10](https://linux-hardware.org/?probe=145ce92f10) | Mar 30, 2025 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [6f54ed80bc](https://linux-hardware.org/?probe=6f54ed80bc) | Mar 22, 2025 |
| Lenovo        | Yoga Slim 7 14IMH9 83GM     | Notebook    | [2eaed49e4c](https://linux-hardware.org/?probe=2eaed49e4c) | Mar 16, 2025 |
| Lenovo        | Yoga Slim 7 14IMH9 83GM     | Notebook    | [818b8f2041](https://linux-hardware.org/?probe=818b8f2041) | Mar 16, 2025 |
| Dell          | 0T2HR0 A02                  | Desktop     | [5e36bd6457](https://linux-hardware.org/?probe=5e36bd6457) | Mar 11, 2025 |
| Dell          | 0T2HR0 A02                  | Desktop     | [3c5d7514b2](https://linux-hardware.org/?probe=3c5d7514b2) | Mar 10, 2025 |
| Apple         | Mac-F221BEC8                | Desktop     | [6d46b86163](https://linux-hardware.org/?probe=6d46b86163) | Mar 06, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [ce294e49a4](https://linux-hardware.org/?probe=ce294e49a4) | Mar 05, 2025 |
| EVOO          | EV-C-116-5                  | Notebook    | [e1ac760dbb](https://linux-hardware.org/?probe=e1ac760dbb) | Mar 04, 2025 |
| MSI           | A68HM-E33 V2                | Desktop     | [c42d3ef6d1](https://linux-hardware.org/?probe=c42d3ef6d1) | Mar 02, 2025 |
| Fujitsu       | FMVNP8AE                    | Notebook    | [81f4d935ff](https://linux-hardware.org/?probe=81f4d935ff) | Mar 01, 2025 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [51c28dacd1](https://linux-hardware.org/?probe=51c28dacd1) | Feb 27, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d539afeb54](https://linux-hardware.org/?probe=d539afeb54) | Feb 27, 2025 |
| ASRock        | H61M-DGS                    | Desktop     | [6ecd09fd4b](https://linux-hardware.org/?probe=6ecd09fd4b) | Feb 12, 2025 |
| ASUSTek       | TUF Gaming B650-E WIFI      | Desktop     | [75d237ff8b](https://linux-hardware.org/?probe=75d237ff8b) | Feb 12, 2025 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [1abd024ed0](https://linux-hardware.org/?probe=1abd024ed0) | Feb 12, 2025 |
| HP            | 246 G7 Notebook PC          | Notebook    | [8b60115d4d](https://linux-hardware.org/?probe=8b60115d4d) | Feb 09, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [902eebca03](https://linux-hardware.org/?probe=902eebca03) | Feb 05, 2025 |
| PELADN        | WI-6                        | Desktop     | [a813b4eb74](https://linux-hardware.org/?probe=a813b4eb74) | Feb 04, 2025 |
| HP            | 245 G8                      | Notebook    | [d8a3698e6e](https://linux-hardware.org/?probe=d8a3698e6e) | Feb 03, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d3bcfe59e7](https://linux-hardware.org/?probe=d3bcfe59e7) | Feb 02, 2025 |
| Acer          | AOD255                      | Notebook    | [d7275909a0](https://linux-hardware.org/?probe=d7275909a0) | Jan 29, 2025 |
| Lenovo        | ThinkPad T420 4180AF8       | Notebook    | [63df1b7f49](https://linux-hardware.org/?probe=63df1b7f49) | Jan 20, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [cca046633b](https://linux-hardware.org/?probe=cca046633b) | Jan 19, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [c7127ed8a1](https://linux-hardware.org/?probe=c7127ed8a1) | Jan 19, 2025 |
| MSI           | B450-A PRO MAX              | Desktop     | [b94f3bdf70](https://linux-hardware.org/?probe=b94f3bdf70) | Jan 14, 2025 |
| Dell          | 0HN7XN A01                  | Desktop     | [920737f97c](https://linux-hardware.org/?probe=920737f97c) | Jan 13, 2025 |
| Lenovo        | ThinkPad T14s Gen 4 21F7... | Notebook    | [a16459ab58](https://linux-hardware.org/?probe=a16459ab58) | Jan 13, 2025 |
| Lenovo        | ThinkPad E570 20H5009LUS    | Notebook    | [fac2ee5166](https://linux-hardware.org/?probe=fac2ee5166) | Jan 13, 2025 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [9e4d6b7864](https://linux-hardware.org/?probe=9e4d6b7864) | Jan 10, 2025 |
| MSI           | Unknown                     | Notebook    | [680e38dd59](https://linux-hardware.org/?probe=680e38dd59) | Jan 09, 2025 |
| MSI           | P41T-C31                    | Desktop     | [c6bfdbb4ac](https://linux-hardware.org/?probe=c6bfdbb4ac) | Jan 03, 2025 |
| MSI           | Modern 14 C5M               | Notebook    | [e986a9bd5b](https://linux-hardware.org/?probe=e986a9bd5b) | Dec 20, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [34f734e369](https://linux-hardware.org/?probe=34f734e369) | Dec 08, 2024 |
| Acer          | Aspire 7530                 | Notebook    | [d3ba125ebf](https://linux-hardware.org/?probe=d3ba125ebf) | Dec 07, 2024 |
| TUXEDO        | Sirius 16 Gen2              | Notebook    | [354db7d135](https://linux-hardware.org/?probe=354db7d135) | Dec 03, 2024 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [f153085b7c](https://linux-hardware.org/?probe=f153085b7c) | Nov 21, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [cb494ef824](https://linux-hardware.org/?probe=cb494ef824) | Nov 13, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 MFG_... | Notebook    | [9776c3f272](https://linux-hardware.org/?probe=9776c3f272) | Nov 11, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1ff85be360](https://linux-hardware.org/?probe=1ff85be360) | Oct 30, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1c9f70e101](https://linux-hardware.org/?probe=1c9f70e101) | Oct 30, 2024 |
| TECNO Mobi... | MEGABOOK K16SDA             | Notebook    | [70986a82fc](https://linux-hardware.org/?probe=70986a82fc) | Oct 29, 2024 |
| SHENZHEN Y... | LAITNIN G5                  | Notebook    | [48ddc95621](https://linux-hardware.org/?probe=48ddc95621) | Oct 27, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTS... | Notebook    | [a65fd5c1bd](https://linux-hardware.org/?probe=a65fd5c1bd) | Oct 25, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTS... | Notebook    | [18e9247d81](https://linux-hardware.org/?probe=18e9247d81) | Oct 25, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTS... | Notebook    | [64bcd6a568](https://linux-hardware.org/?probe=64bcd6a568) | Oct 25, 2024 |
| ASRock        | B450M/ac                    | Desktop     | [7d8108e45d](https://linux-hardware.org/?probe=7d8108e45d) | Oct 16, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [de44b9af7c](https://linux-hardware.org/?probe=de44b9af7c) | Oct 15, 2024 |
| Dell          | 0RY007 A01                  | Desktop     | [5d0dff2bab](https://linux-hardware.org/?probe=5d0dff2bab) | Oct 13, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [b1e957c653](https://linux-hardware.org/?probe=b1e957c653) | Oct 07, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [e388b60674](https://linux-hardware.org/?probe=e388b60674) | Oct 05, 2024 |
| Acer          | IAXBT-BL                    | All in one  | [59fb4c7892](https://linux-hardware.org/?probe=59fb4c7892) | Oct 04, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTS... | Notebook    | [1681159aa6](https://linux-hardware.org/?probe=1681159aa6) | Oct 03, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [8b4bc215f3](https://linux-hardware.org/?probe=8b4bc215f3) | Oct 02, 2024 |
| Positivo      | Mobile                      | Notebook    | [aeb1cab172](https://linux-hardware.org/?probe=aeb1cab172) | Sep 27, 2024 |
| Casper        | NIRVANA                     | Notebook    | [7fec4c1d6a](https://linux-hardware.org/?probe=7fec4c1d6a) | Sep 26, 2024 |
| Lenovo        | ThinkPad T450 20BUS0QB01    | Notebook    | [d690a02173](https://linux-hardware.org/?probe=d690a02173) | Sep 08, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [fb2050ff91](https://linux-hardware.org/?probe=fb2050ff91) | Aug 29, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [caf63dfcd4](https://linux-hardware.org/?probe=caf63dfcd4) | Aug 27, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [d011f81b2c](https://linux-hardware.org/?probe=d011f81b2c) | Aug 21, 2024 |
| Dell          | G15 Special Edition 5521    | Notebook    | [f63c3accfa](https://linux-hardware.org/?probe=f63c3accfa) | Aug 10, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f5055fea58](https://linux-hardware.org/?probe=f5055fea58) | Aug 04, 2024 |
| HP            | Pavilion 15                 | Notebook    | [57e8c42dac](https://linux-hardware.org/?probe=57e8c42dac) | Aug 04, 2024 |
| HP            | Pavilion 15                 | Notebook    | [9a6044e07e](https://linux-hardware.org/?probe=9a6044e07e) | Aug 04, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [7aafcbd9f1](https://linux-hardware.org/?probe=7aafcbd9f1) | Jul 20, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [524616cba4](https://linux-hardware.org/?probe=524616cba4) | Jul 16, 2024 |
| HP            | 15                          | Notebook    | [23f73adbdd](https://linux-hardware.org/?probe=23f73adbdd) | Jul 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d7c2d0c8e1](https://linux-hardware.org/?probe=d7c2d0c8e1) | Jul 08, 2024 |
| Gigabyte      | H310M S2H                   | Desktop     | [a61d3c9e57](https://linux-hardware.org/?probe=a61d3c9e57) | Jul 05, 2024 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [d1bb865d34](https://linux-hardware.org/?probe=d1bb865d34) | Jul 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | Notebook    | [640bc2625d](https://linux-hardware.org/?probe=640bc2625d) | Jun 20, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [0bd7cbd871](https://linux-hardware.org/?probe=0bd7cbd871) | Jun 19, 2024 |
| HP            | 0AE4h                       | Desktop     | [3eedb438d5](https://linux-hardware.org/?probe=3eedb438d5) | Jun 19, 2024 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | Notebook    | [dda20727cf](https://linux-hardware.org/?probe=dda20727cf) | Jun 17, 2024 |
| AMI           | Unknown                     | Desktop     | [287abc46ae](https://linux-hardware.org/?probe=287abc46ae) | Jun 11, 2024 |
| HP            | 8594                        | Desktop     | [f06ecd2e7b](https://linux-hardware.org/?probe=f06ecd2e7b) | Jun 08, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7bc9c456ff](https://linux-hardware.org/?probe=7bc9c456ff) | Jun 05, 2024 |
| TUXEDO        | Pulse 14 Gen3               | Notebook    | [0543a1b5a2](https://linux-hardware.org/?probe=0543a1b5a2) | Jun 04, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [606e2f7d8a](https://linux-hardware.org/?probe=606e2f7d8a) | Jun 04, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [c06c68d9b3](https://linux-hardware.org/?probe=c06c68d9b3) | May 29, 2024 |
| Shuttle       | FH170                       | Desktop     | [7d64c3247b](https://linux-hardware.org/?probe=7d64c3247b) | May 29, 2024 |
| Matsushita... | CF-74GCDADBM                | Notebook    | [95822893cd](https://linux-hardware.org/?probe=95822893cd) | May 23, 2024 |
| HP            | 8594                        | Desktop     | [441198408b](https://linux-hardware.org/?probe=441198408b) | May 22, 2024 |
| Matsushita... | CF-74GCDADBM                | Notebook    | [062929e9d9](https://linux-hardware.org/?probe=062929e9d9) | May 14, 2024 |
| Lenovo        | ThinkPad T420 4180D81       | Notebook    | [586b69e749](https://linux-hardware.org/?probe=586b69e749) | Apr 23, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4113f409f3](https://linux-hardware.org/?probe=4113f409f3) | Apr 22, 2024 |
| Lenovo        | ThinkPad T520 42433ZG       | Notebook    | [d2899d8de6](https://linux-hardware.org/?probe=d2899d8de6) | Apr 19, 2024 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [02724e5adf](https://linux-hardware.org/?probe=02724e5adf) | Apr 15, 2024 |
| ASUSTek       | E402MA                      | Notebook    | [58a1e32393](https://linux-hardware.org/?probe=58a1e32393) | Apr 14, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [d6d03b4ad2](https://linux-hardware.org/?probe=d6d03b4ad2) | Apr 14, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [4e18f485f3](https://linux-hardware.org/?probe=4e18f485f3) | Apr 11, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [27c9e47ccc](https://linux-hardware.org/?probe=27c9e47ccc) | Apr 11, 2024 |
| Acer          | E1-510                      | Notebook    | [c53095abd3](https://linux-hardware.org/?probe=c53095abd3) | Apr 10, 2024 |
| Dell          | Latitude 5400               | Notebook    | [20fa0e002d](https://linux-hardware.org/?probe=20fa0e002d) | Mar 23, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [09665b9825](https://linux-hardware.org/?probe=09665b9825) | Mar 21, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [d5c50b0264](https://linux-hardware.org/?probe=d5c50b0264) | Mar 20, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [14b3cedbef](https://linux-hardware.org/?probe=14b3cedbef) | Mar 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [d2152999e9](https://linux-hardware.org/?probe=d2152999e9) | Mar 13, 2024 |
| Gigabyte      | Z97X-UD7 TH-CF              | Desktop     | [3f20fe5386](https://linux-hardware.org/?probe=3f20fe5386) | Mar 13, 2024 |
| ASUSTek       | ROG Maximus Z790 APEX EN... | Desktop     | [b0c33ebfd2](https://linux-hardware.org/?probe=b0c33ebfd2) | Mar 07, 2024 |
| OrangePi      | Zero3                       | Soc         | [a92d36b760](https://linux-hardware.org/?probe=a92d36b760) | Mar 06, 2024 |
| ASUSTek       | ROG Maximus Z790 APEX EN... | Desktop     | [15c45d681f](https://linux-hardware.org/?probe=15c45d681f) | Mar 06, 2024 |
| Lenovo        | ThinkPad T480 20L6S37W04    | Notebook    | [1278612ad9](https://linux-hardware.org/?probe=1278612ad9) | Mar 05, 2024 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [bf1cfeb779](https://linux-hardware.org/?probe=bf1cfeb779) | Mar 05, 2024 |
| Lenovo        | ThinkPad E590 20NB001AUK    | Notebook    | [45eadbd174](https://linux-hardware.org/?probe=45eadbd174) | Mar 03, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [b68f17fbdf](https://linux-hardware.org/?probe=b68f17fbdf) | Mar 02, 2024 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [4dd27fbd4e](https://linux-hardware.org/?probe=4dd27fbd4e) | Feb 23, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7fe3789b7f](https://linux-hardware.org/?probe=7fe3789b7f) | Feb 23, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [99f1228781](https://linux-hardware.org/?probe=99f1228781) | Feb 20, 2024 |
| Dell          | Latitude 7420               | Notebook    | [29ce5896a7](https://linux-hardware.org/?probe=29ce5896a7) | Feb 05, 2024 |
| Dell          | Latitude 7420               | Notebook    | [cdd5031988](https://linux-hardware.org/?probe=cdd5031988) | Feb 04, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bda104dc07](https://linux-hardware.org/?probe=bda104dc07) | Feb 04, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [c35fdb0865](https://linux-hardware.org/?probe=c35fdb0865) | Feb 04, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [3cec123511](https://linux-hardware.org/?probe=3cec123511) | Feb 04, 2024 |
| HP            | 2ADE                        | Desktop     | [c98c83ddde](https://linux-hardware.org/?probe=c98c83ddde) | Jan 29, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [971c919cef](https://linux-hardware.org/?probe=971c919cef) | Jan 20, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [89387d46ef](https://linux-hardware.org/?probe=89387d46ef) | Jan 18, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [c1e2f276ba](https://linux-hardware.org/?probe=c1e2f276ba) | Jan 18, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [78a77e24d1](https://linux-hardware.org/?probe=78a77e24d1) | Jan 14, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [4b6c5e1edb](https://linux-hardware.org/?probe=4b6c5e1edb) | Jan 08, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [cc169dad66](https://linux-hardware.org/?probe=cc169dad66) | Jan 08, 2024 |
| Dell          | 0G919G A00                  | Desktop     | [265aa7e914](https://linux-hardware.org/?probe=265aa7e914) | Jan 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [9eb47b934a](https://linux-hardware.org/?probe=9eb47b934a) | Jan 02, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [7caa5da564](https://linux-hardware.org/?probe=7caa5da564) | Dec 31, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [b063fdc8bf](https://linux-hardware.org/?probe=b063fdc8bf) | Dec 29, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [9662ee22d6](https://linux-hardware.org/?probe=9662ee22d6) | Dec 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [4f6ecdc95a](https://linux-hardware.org/?probe=4f6ecdc95a) | Dec 19, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [cd261e1bc3](https://linux-hardware.org/?probe=cd261e1bc3) | Dec 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [5f97c0d536](https://linux-hardware.org/?probe=5f97c0d536) | Dec 13, 2023 |
| Apple         | Mac-F42787C8 PVT            | All in one  | [e553ac24bf](https://linux-hardware.org/?probe=e553ac24bf) | Dec 10, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [acb5d61dd5](https://linux-hardware.org/?probe=acb5d61dd5) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [980caec27f](https://linux-hardware.org/?probe=980caec27f) | Dec 03, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [c6f9c552b6](https://linux-hardware.org/?probe=c6f9c552b6) | Nov 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f6d20427d3](https://linux-hardware.org/?probe=f6d20427d3) | Nov 26, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [04fce2b1b1](https://linux-hardware.org/?probe=04fce2b1b1) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [70a8dad823](https://linux-hardware.org/?probe=70a8dad823) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7ed36f1817](https://linux-hardware.org/?probe=7ed36f1817) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f2070cd827](https://linux-hardware.org/?probe=f2070cd827) | Nov 18, 2023 |
| Unknown       | T100                        | Desktop     | [298b8f8764](https://linux-hardware.org/?probe=298b8f8764) | Nov 16, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [426fd54105](https://linux-hardware.org/?probe=426fd54105) | Nov 15, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [a9ff569501](https://linux-hardware.org/?probe=a9ff569501) | Nov 14, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5e3d94c299](https://linux-hardware.org/?probe=5e3d94c299) | Nov 07, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [6a8536f5df](https://linux-hardware.org/?probe=6a8536f5df) | Nov 04, 2023 |
| Supermicro    | X11SCA-F                    | Server      | [e63931ed4f](https://linux-hardware.org/?probe=e63931ed4f) | Nov 04, 2023 |
| Google        | Phaser360                   | Notebook    | [9915a1a3be](https://linux-hardware.org/?probe=9915a1a3be) | Nov 03, 2023 |
| Dell          | 0C27VV A03                  | Desktop     | [3e65f94217](https://linux-hardware.org/?probe=3e65f94217) | Oct 28, 2023 |
| Dell          | Latitude D610               | Notebook    | [270c26c018](https://linux-hardware.org/?probe=270c26c018) | Oct 27, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [9faa5f07eb](https://linux-hardware.org/?probe=9faa5f07eb) | Oct 20, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [4bec650d3e](https://linux-hardware.org/?probe=4bec650d3e) | Oct 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [93113727fa](https://linux-hardware.org/?probe=93113727fa) | Oct 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b000ad74e9](https://linux-hardware.org/?probe=b000ad74e9) | Oct 14, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [d96bdeca74](https://linux-hardware.org/?probe=d96bdeca74) | Oct 10, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c63ad78eb4](https://linux-hardware.org/?probe=c63ad78eb4) | Oct 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c074bb832e](https://linux-hardware.org/?probe=c074bb832e) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| Acer          | One S1003                   | Tablet      | [dd8e16ad67](https://linux-hardware.org/?probe=dd8e16ad67) | Sep 25, 2023 |
| Acer          | One S1003                   | Tablet      | [02c8574cb0](https://linux-hardware.org/?probe=02c8574cb0) | Sep 25, 2023 |
| HP            | 15                          | Notebook    | [d0ddd6fbc9](https://linux-hardware.org/?probe=d0ddd6fbc9) | Sep 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [1e60d905c5](https://linux-hardware.org/?probe=1e60d905c5) | Sep 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [2322edb05f](https://linux-hardware.org/?probe=2322edb05f) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [179381f376](https://linux-hardware.org/?probe=179381f376) | Aug 12, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [4f4304a557](https://linux-hardware.org/?probe=4f4304a557) | Aug 06, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [f86b014869](https://linux-hardware.org/?probe=f86b014869) | Aug 06, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [dd0cfabd4b](https://linux-hardware.org/?probe=dd0cfabd4b) | Jul 29, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [14dbf1a55b](https://linux-hardware.org/?probe=14dbf1a55b) | Jul 26, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [de2e3a3ebb](https://linux-hardware.org/?probe=de2e3a3ebb) | Jul 23, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | Desktop     | [08d9fe81da](https://linux-hardware.org/?probe=08d9fe81da) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [00a862ae7c](https://linux-hardware.org/?probe=00a862ae7c) | Jun 14, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [42eab3e3af](https://linux-hardware.org/?probe=42eab3e3af) | Jun 08, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [827f6ecac2](https://linux-hardware.org/?probe=827f6ecac2) | Jun 07, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [45c21cb512](https://linux-hardware.org/?probe=45c21cb512) | May 24, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [f06fd87a32](https://linux-hardware.org/?probe=f06fd87a32) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [cba22e109f](https://linux-hardware.org/?probe=cba22e109f) | Mar 23, 2023 |
| Acer          | E1-510                      | Notebook    | [86abc88022](https://linux-hardware.org/?probe=86abc88022) | Mar 06, 2023 |
| HP            | ENVY m7 Notebook            | Notebook    | [88d1b48b0c](https://linux-hardware.org/?probe=88d1b48b0c) | Feb 26, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d94b8cf0e0](https://linux-hardware.org/?probe=d94b8cf0e0) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d77029e5a0](https://linux-hardware.org/?probe=d77029e5a0) | Feb 13, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| ASUSTek       | Q325UAR                     | Convertible | [b95d2d4e30](https://linux-hardware.org/?probe=b95d2d4e30) | Feb 02, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [43ba50f36c](https://linux-hardware.org/?probe=43ba50f36c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [35024faf2b](https://linux-hardware.org/?probe=35024faf2b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [3c9f8b612c](https://linux-hardware.org/?probe=3c9f8b612c) | Jan 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a551d228f4](https://linux-hardware.org/?probe=a551d228f4) | Jan 14, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [b9ca7fb340](https://linux-hardware.org/?probe=b9ca7fb340) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| MSI           | B550M PRO                   | Desktop     | [61b36bfa2e](https://linux-hardware.org/?probe=61b36bfa2e) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [b30f8a638b](https://linux-hardware.org/?probe=b30f8a638b) | Dec 26, 2022 |
| MSI           | B550M PRO                   | Desktop     | [57f4a4985a](https://linux-hardware.org/?probe=57f4a4985a) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [34882fc8cb](https://linux-hardware.org/?probe=34882fc8cb) | Nov 16, 2022 |
| Toshiba       | Satellite A300D             | Notebook    | [21952b8d66](https://linux-hardware.org/?probe=21952b8d66) | Nov 15, 2022 |
| Lenovo        | Y520-15IKB 80YY             | Notebook    | [626a442179](https://linux-hardware.org/?probe=626a442179) | Nov 06, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [b487c53dfd](https://linux-hardware.org/?probe=b487c53dfd) | Nov 04, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | Notebook    | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | Notebook    | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [001bcba320](https://linux-hardware.org/?probe=001bcba320) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a3485b332a](https://linux-hardware.org/?probe=a3485b332a) | Sep 27, 2022 |
| Unknown       | 1.0                         | Notebook    | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [2f9e03051e](https://linux-hardware.org/?probe=2f9e03051e) | Aug 13, 2022 |
| Exo           | Exomate X352                | Notebook    | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| ASUSTek       | X455LF                      | Notebook    | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [7e7f71a3c0](https://linux-hardware.org/?probe=7e7f71a3c0) | Jul 23, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [761dd08497](https://linux-hardware.org/?probe=761dd08497) | Jul 23, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [53fd2c87d2](https://linux-hardware.org/?probe=53fd2c87d2) | Jul 16, 2022 |
| HP            | 3397                        | Desktop     | [7d3b738672](https://linux-hardware.org/?probe=7d3b738672) | Jul 14, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [fa17eccd81](https://linux-hardware.org/?probe=fa17eccd81) | Jul 04, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6302e38583](https://linux-hardware.org/?probe=6302e38583) | Jun 22, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [ce610351c3](https://linux-hardware.org/?probe=ce610351c3) | Jun 03, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [1e0c1bed2a](https://linux-hardware.org/?probe=1e0c1bed2a) | Jun 02, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [607d5b3c79](https://linux-hardware.org/?probe=607d5b3c79) | May 14, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| MSI           | Z87-G43                     | Desktop     | [d5612db7ca](https://linux-hardware.org/?probe=d5612db7ca) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | Notebook    | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [abc0c5402d](https://linux-hardware.org/?probe=abc0c5402d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [9389a4bd1e](https://linux-hardware.org/?probe=9389a4bd1e) | Apr 29, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6be9414efd](https://linux-hardware.org/?probe=6be9414efd) | Apr 22, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [59b9a2cbcb](https://linux-hardware.org/?probe=59b9a2cbcb) | Apr 11, 2022 |
| MSI           | B550M PRO                   | Desktop     | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| HP            | ENVY 6                      | Notebook    | [988417aaa7](https://linux-hardware.org/?probe=988417aaa7) | Feb 25, 2022 |
| ASUSTek       | Q325UAR                     | Convertible | [fc83e5d0b3](https://linux-hardware.org/?probe=fc83e5d0b3) | Feb 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [28be6b9f17](https://linux-hardware.org/?probe=28be6b9f17) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [5819fc1b20](https://linux-hardware.org/?probe=5819fc1b20) | Feb 14, 2022 |
| Framework     | Laptop                      | Notebook    | [24c119ef46](https://linux-hardware.org/?probe=24c119ef46) | Feb 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [61374a4048](https://linux-hardware.org/?probe=61374a4048) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [24fedcca0a](https://linux-hardware.org/?probe=24fedcca0a) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA34HMN    | Notebook    | [a4dfbb6e38](https://linux-hardware.org/?probe=a4dfbb6e38) | Jan 10, 2022 |
| HP            | Notebook                    | Notebook    | [3b26596e87](https://linux-hardware.org/?probe=3b26596e87) | Jan 10, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [8ff352de01](https://linux-hardware.org/?probe=8ff352de01) | Dec 31, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [ce95acc16d](https://linux-hardware.org/?probe=ce95acc16d) | Nov 24, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [ae9fd68c7d](https://linux-hardware.org/?probe=ae9fd68c7d) | Nov 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1dec2f3df](https://linux-hardware.org/?probe=b1dec2f3df) | Oct 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [093a7d451a](https://linux-hardware.org/?probe=093a7d451a) | Oct 16, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7917f7d57f](https://linux-hardware.org/?probe=7917f7d57f) | Oct 12, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [30d85d7ea1](https://linux-hardware.org/?probe=30d85d7ea1) | Oct 03, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [6ad302377d](https://linux-hardware.org/?probe=6ad302377d) | Sep 30, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9c0d90d6ab](https://linux-hardware.org/?probe=9c0d90d6ab) | Sep 24, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [4cff8ab563](https://linux-hardware.org/?probe=4cff8ab563) | Sep 24, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [efc517d282](https://linux-hardware.org/?probe=efc517d282) | Sep 22, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b4749d300a](https://linux-hardware.org/?probe=b4749d300a) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b9d873983c](https://linux-hardware.org/?probe=b9d873983c) | Sep 17, 2021 |
| Dell          | G3 3579                     | Notebook    | [95182b0267](https://linux-hardware.org/?probe=95182b0267) | Sep 16, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a0d3015e21](https://linux-hardware.org/?probe=a0d3015e21) | Sep 15, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d3c1b5c10c](https://linux-hardware.org/?probe=d3c1b5c10c) | Sep 11, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [feddf87464](https://linux-hardware.org/?probe=feddf87464) | Sep 01, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [bc2b986f06](https://linux-hardware.org/?probe=bc2b986f06) | Aug 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [85d1c86c68](https://linux-hardware.org/?probe=85d1c86c68) | Aug 19, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | Notebook    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [5dec53ee3f](https://linux-hardware.org/?probe=5dec53ee3f) | Jul 26, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [17aab9510b](https://linux-hardware.org/?probe=17aab9510b) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [e1f4843546](https://linux-hardware.org/?probe=e1f4843546) | Jun 16, 2021 |
| ASRock        | J4005B-ITX                  | Desktop     | [053a28a1b7](https://linux-hardware.org/?probe=053a28a1b7) | Jun 13, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e075758bf](https://linux-hardware.org/?probe=8e075758bf) | May 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [59e32967c4](https://linux-hardware.org/?probe=59e32967c4) | May 26, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [32c0e61ea7](https://linux-hardware.org/?probe=32c0e61ea7) | May 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [bf2d71e7f2](https://linux-hardware.org/?probe=bf2d71e7f2) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c96223f666](https://linux-hardware.org/?probe=c96223f666) | Apr 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [42d648695d](https://linux-hardware.org/?probe=42d648695d) | Mar 26, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [b0e56964ae](https://linux-hardware.org/?probe=b0e56964ae) | Mar 15, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [adf7976842](https://linux-hardware.org/?probe=adf7976842) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bdedf5a7c7](https://linux-hardware.org/?probe=bdedf5a7c7) | Feb 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [35af7cfd3d](https://linux-hardware.org/?probe=35af7cfd3d) | Feb 22, 2021 |
| ASUSTek       | X510UAR                     | Notebook    | [1888d46194](https://linux-hardware.org/?probe=1888d46194) | Feb 21, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [09b0e87eec](https://linux-hardware.org/?probe=09b0e87eec) | Feb 12, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [5d02f20d1d](https://linux-hardware.org/?probe=5d02f20d1d) | Feb 10, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | Notebook    | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [66e8ed8402](https://linux-hardware.org/?probe=66e8ed8402) | Jan 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4fcffbd93](https://linux-hardware.org/?probe=d4fcffbd93) | Jan 22, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [624f71f228](https://linux-hardware.org/?probe=624f71f228) | Jan 21, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [73c3fdc605](https://linux-hardware.org/?probe=73c3fdc605) | Jan 16, 2021 |
| ASUSTek       | PRIME Z270-AR               | Desktop     | [35d08fe710](https://linux-hardware.org/?probe=35d08fe710) | Dec 30, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1f66d0eb72](https://linux-hardware.org/?probe=1f66d0eb72) | Dec 22, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [61887011a6](https://linux-hardware.org/?probe=61887011a6) | Dec 22, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [e84677b145](https://linux-hardware.org/?probe=e84677b145) | Dec 20, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| Dell          | Inspiron 11 - 3148          | Notebook    | [f9ec6964bb](https://linux-hardware.org/?probe=f9ec6964bb) | Nov 29, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [d8adc8e3f8](https://linux-hardware.org/?probe=d8adc8e3f8) | Nov 20, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| Acer          | AO722                       | Notebook    | [cee0cf9a99](https://linux-hardware.org/?probe=cee0cf9a99) | Nov 17, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [438477ec85](https://linux-hardware.org/?probe=438477ec85) | Nov 14, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [ac5adde915](https://linux-hardware.org/?probe=ac5adde915) | Nov 13, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d889341667](https://linux-hardware.org/?probe=d889341667) | Oct 28, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e769e1f93a](https://linux-hardware.org/?probe=e769e1f93a) | Oct 24, 2020 |
| HP            | 82C0                        | Mini pc     | [44430304d3](https://linux-hardware.org/?probe=44430304d3) | Oct 19, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b50f7a3624](https://linux-hardware.org/?probe=b50f7a3624) | Oct 07, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Acer          | Aspire A315-55G             | Notebook    | [d24561be9e](https://linux-hardware.org/?probe=d24561be9e) | Oct 01, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [90d57d39e2](https://linux-hardware.org/?probe=90d57d39e2) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [66f15fef73](https://linux-hardware.org/?probe=66f15fef73) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [ee56035e75](https://linux-hardware.org/?probe=ee56035e75) | Sep 24, 2020 |
| Acer          | Nitro AN715-51              | Notebook    | [d375c469b7](https://linux-hardware.org/?probe=d375c469b7) | Sep 16, 2020 |
| Getac         | V110                        | Notebook    | [f0d3292b48](https://linux-hardware.org/?probe=f0d3292b48) | Sep 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | AOA150                      | Notebook    | [f88d38a138](https://linux-hardware.org/?probe=f88d38a138) | Sep 04, 2020 |
| ASUSTek       | P8H67-V                     | Desktop     | [9bc61b31d4](https://linux-hardware.org/?probe=9bc61b31d4) | Sep 02, 2020 |
| Acer          | AO722                       | Notebook    | [816e97376d](https://linux-hardware.org/?probe=816e97376d) | Aug 21, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [efac4b3e2b](https://linux-hardware.org/?probe=efac4b3e2b) | May 25, 2020 |
| Lenovo        | IdeaPad Z570 10246ZG        | Notebook    | [0a0f078e76](https://linux-hardware.org/?probe=0a0f078e76) | Apr 25, 2020 |
| HP            | 15                          | Notebook    | [66422a127b](https://linux-hardware.org/?probe=66422a127b) | Mar 14, 2020 |
| Dell          | Precision 3530              | Notebook    | [dd006a4ce0](https://linux-hardware.org/?probe=dd006a4ce0) | Mar 07, 2020 |
| Dell          | Latitude E4300              | Notebook    | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| Dell          | 0H8052                      | Desktop     | [18169ce984](https://linux-hardware.org/?probe=18169ce984) | Jan 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [b9eb4a5652](https://linux-hardware.org/?probe=b9eb4a5652) | Jan 24, 2020 |
| Unknown       | Unknown                     | Desktop     | [ac87dc43f3](https://linux-hardware.org/?probe=ac87dc43f3) | Jan 24, 2020 |
| ASUSTek       | X555UJ                      | Notebook    | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [faeec47313](https://linux-hardware.org/?probe=faeec47313) | Jan 21, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [ec79f8e0c6](https://linux-hardware.org/?probe=ec79f8e0c6) | Jan 21, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| Dell          | Inspiron 1501               | Notebook    | [17f0e8e41b](https://linux-hardware.org/?probe=17f0e8e41b) | Dec 03, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3bae5ecb46](https://linux-hardware.org/?probe=3bae5ecb46) | Oct 10, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [230c0c9bc6](https://linux-hardware.org/?probe=230c0c9bc6) | Oct 01, 2019 |
| Dell          | Latitude 3379               | Notebook    | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
| ASRock        | AB350M                      | Desktop     | [1ec4015426](https://linux-hardware.org/?probe=1ec4015426) | Sep 01, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [69e86c050b](https://linux-hardware.org/?probe=69e86c050b) | Aug 18, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [ef4f02af88](https://linux-hardware.org/?probe=ef4f02af88) | Aug 16, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [c2458d18f6](https://linux-hardware.org/?probe=c2458d18f6) | Aug 03, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [51273f53df](https://linux-hardware.org/?probe=51273f53df) | Jul 15, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [5ac8c5ff7b](https://linux-hardware.org/?probe=5ac8c5ff7b) | Jun 25, 2019 |
| MSI           | B350M GAMING PRO            | Desktop     | [20e1f5d7a1](https://linux-hardware.org/?probe=20e1f5d7a1) | Apr 17, 2019 |
| Positivo      | Mobile                      | Notebook    | [0267cf3435](https://linux-hardware.org/?probe=0267cf3435) | Mar 27, 2019 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [1b0a4407c7](https://linux-hardware.org/?probe=1b0a4407c7) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 297       | 85.1%   |
| Void Linux         | 52        | 14.9%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 346       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 6.3.13_1  | 11        | 2.92%   |
| 6.3.12_1  | 9         | 2.39%   |
| 5.13.19_1 | 7         | 1.86%   |
| 6.6.52_1  | 5         | 1.33%   |
| 6.6.21_1  | 5         | 1.33%   |
| 6.6.11_1  | 5         | 1.33%   |
| 6.12.11_1 | 5         | 1.33%   |
| 5.8.18_1  | 5         | 1.33%   |
| 6.6.22_1  | 4         | 1.06%   |
| 6.12.9_1  | 4         | 1.06%   |
| 6.12.37_1 | 4         | 1.06%   |
| 6.12.23_1 | 4         | 1.06%   |
| 6.12.16_1 | 4         | 1.06%   |
| 6.1.4_1   | 4         | 1.06%   |
| 6.1.31_1  | 4         | 1.06%   |
| 5.3.9_1   | 4         | 1.06%   |
| 5.18.19_1 | 4         | 1.06%   |
| 5.16.20_1 | 4         | 1.06%   |
| 5.10.17_1 | 4         | 1.06%   |
| 6.9.12_1  | 3         | 0.8%    |
| 6.6.8_1   | 3         | 0.8%    |
| 6.6.63_1  | 3         | 0.8%    |
| 6.6.35_1  | 3         | 0.8%    |
| 6.6.31_1  | 3         | 0.8%    |
| 6.5.13_1  | 3         | 0.8%    |
| 6.5.11_1  | 3         | 0.8%    |
| 6.16.0_1  | 3         | 0.8%    |
| 6.12.49_1 | 3         | 0.8%    |
| 6.12.25_1 | 3         | 0.8%    |
| 6.12.17_1 | 3         | 0.8%    |
| 6.12.13_1 | 3         | 0.8%    |
| 5.8.12_1  | 3         | 0.8%    |
| 5.19.17_1 | 3         | 0.8%    |
| 5.18.14_1 | 3         | 0.8%    |
| 5.15.32_1 | 3         | 0.8%    |
| 5.13.13_1 | 3         | 0.8%    |
| 5.12.10_1 | 3         | 0.8%    |
| 6.7.6_1   | 2         | 0.53%   |
| 6.6.9_1   | 2         | 0.53%   |
| 6.6.54_1  | 2         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.13  | 11        | 2.92%   |
| 6.3.12  | 9         | 2.39%   |
| 5.13.19 | 7         | 1.86%   |
| 6.6.52  | 5         | 1.33%   |
| 6.6.21  | 5         | 1.33%   |
| 6.6.11  | 5         | 1.33%   |
| 6.12.11 | 5         | 1.33%   |
| 5.8.18  | 5         | 1.33%   |
| 6.6.22  | 4         | 1.06%   |
| 6.12.9  | 4         | 1.06%   |
| 6.12.37 | 4         | 1.06%   |
| 6.12.23 | 4         | 1.06%   |
| 6.12.16 | 4         | 1.06%   |
| 6.1.4   | 4         | 1.06%   |
| 6.1.31  | 4         | 1.06%   |
| 5.8.12  | 4         | 1.06%   |
| 5.3.9   | 4         | 1.06%   |
| 5.18.19 | 4         | 1.06%   |
| 5.16.20 | 4         | 1.06%   |
| 5.10.17 | 4         | 1.06%   |
| 6.9.12  | 3         | 0.8%    |
| 6.6.8   | 3         | 0.8%    |
| 6.6.63  | 3         | 0.8%    |
| 6.6.35  | 3         | 0.8%    |
| 6.6.31  | 3         | 0.8%    |
| 6.5.13  | 3         | 0.8%    |
| 6.5.11  | 3         | 0.8%    |
| 6.16.0  | 3         | 0.8%    |
| 6.12.60 | 3         | 0.8%    |
| 6.12.49 | 3         | 0.8%    |
| 6.12.25 | 3         | 0.8%    |
| 6.12.17 | 3         | 0.8%    |
| 6.12.13 | 3         | 0.8%    |
| 5.19.17 | 3         | 0.8%    |
| 5.18.14 | 3         | 0.8%    |
| 5.15.32 | 3         | 0.8%    |
| 5.13.13 | 3         | 0.8%    |
| 5.12.10 | 3         | 0.8%    |
| 6.8.0   | 2         | 0.53%   |
| 6.7.6   | 2         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.12    | 69        | 18.65%  |
| 6.6     | 54        | 14.59%  |
| 6.1     | 24        | 6.49%   |
| 5.15    | 24        | 6.49%   |
| 6.3     | 20        | 5.41%   |
| 5.8     | 18        | 4.86%   |
| 5.13    | 16        | 4.32%   |
| 6.5     | 15        | 4.05%   |
| 5.10    | 15        | 4.05%   |
| 5.18    | 12        | 3.24%   |
| 5.12    | 9         | 2.43%   |
| 6.16    | 7         | 1.89%   |
| 5.4     | 7         | 1.89%   |
| 6.9     | 6         | 1.62%   |
| 6.8     | 6         | 1.62%   |
| 6.0     | 6         | 1.62%   |
| 6.11    | 5         | 1.35%   |
| 5.3     | 5         | 1.35%   |
| 5.19    | 5         | 1.35%   |
| 5.11    | 5         | 1.35%   |
| 6.7     | 4         | 1.08%   |
| 6.17    | 4         | 1.08%   |
| 6.14    | 4         | 1.08%   |
| 5.9     | 4         | 1.08%   |
| 5.16    | 4         | 1.08%   |
| 4.19    | 4         | 1.08%   |
| 6.2     | 2         | 0.54%   |
| 6.18    | 2         | 0.54%   |
| 6.13    | 2         | 0.54%   |
| 6.10    | 2         | 0.54%   |
| 6.4     | 1         | 0.27%   |
| 6.15    | 1         | 0.27%   |
| 5.7     | 1         | 0.27%   |
| 5.6     | 1         | 0.27%   |
| 5.2     | 1         | 0.27%   |
| 5.17    | 1         | 0.27%   |
| 5.14    | 1         | 0.27%   |
| 5.1     | 1         | 0.27%   |
| 4.4     | 1         | 0.27%   |
| 4.14    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 329       | 95.09%  |
| i686    | 8         | 2.31%   |
| aarch64 | 6         | 1.73%   |
| ppc64le | 1         | 0.29%   |
| ppc64   | 1         | 0.29%   |
| armv7l  | 1         | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 128       | 35.65%  |
| XFCE                | 67        | 18.66%  |
| GNOME               | 25        | 6.96%   |
| KDE5                | 20        | 5.57%   |
| KDE6                | 19        | 5.29%   |
| KDE                 | 17        | 4.74%   |
| sway                | 16        | 4.46%   |
| MATE                | 10        | 2.79%   |
| X-Cinnamon          | 9         | 2.51%   |
| i3                  | 9         | 2.51%   |
| bspwm               | 5         | 1.39%   |
| dwm                 | 4         | 1.11%   |
| awesome             | 4         | 1.11%   |
| river               | 3         | 0.84%   |
| openbox             | 3         | 0.84%   |
| Hyprland            | 3         | 0.84%   |
| X-Generic           | 2         | 0.56%   |
| sway:wlroots        | 2         | 0.56%   |
| niri                | 2         | 0.56%   |
| LXQt                | 2         | 0.56%   |
| Lumina              | 2         | 0.56%   |
| sway:wlroots:swayfx | 1         | 0.28%   |
| LXDE                | 1         | 0.28%   |
| labwc:wlroots       | 1         | 0.28%   |
| i3-with-dbus        | 1         | 0.28%   |
| Enlightenment       | 1         | 0.28%   |
| dot-xsession        | 1         | 0.28%   |
| awesome-with-dbus   | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 212       | 59.55%  |
| Wayland | 83        | 23.31%  |
| Tty     | 31        | 8.71%   |
| Unknown | 30        | 8.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 248       | 69.86%  |
| LightDM | 52        | 14.65%  |
| SDDM    | 33        | 9.3%    |
| GDM     | 10        | 2.82%   |
| LXDM    | 9         | 2.54%   |
| XDM     | 1         | 0.28%   |
| SLiM    | 1         | 0.28%   |
| LDM     | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 190       | 53.52%  |
| Unknown     | 30        | 8.45%   |
| en_GB       | 22        | 6.2%    |
| de_DE       | 11        | 3.1%    |
| C           | 11        | 3.1%    |
| ru_RU       | 9         | 2.54%   |
| en_DK       | 9         | 2.54%   |
| pt_BR       | 8         | 2.25%   |
| en_CA       | 8         | 2.25%   |
| it_IT       | 7         | 1.97%   |
| fr_FR       | 7         | 1.97%   |
| en_AU       | 7         | 1.97%   |
| es_ES       | 6         | 1.69%   |
| pl_PL       | 4         | 1.13%   |
| cs_CZ       | 3         | 0.85%   |
| tr_TR       | 2         | 0.56%   |
| es_CL       | 2         | 0.56%   |
| en_NZ       | 2         | 0.56%   |
| el_GR       | 2         | 0.56%   |
| ru_UA       | 1         | 0.28%   |
| pt_PT       | 1         | 0.28%   |
| nb_NO       | 1         | 0.28%   |
| hu_HU       | 1         | 0.28%   |
| es_VE       | 1         | 0.28%   |
| es_UY       | 1         | 0.28%   |
| es_HN       | 1         | 0.28%   |
| es_EC       | 1         | 0.28%   |
| es_DO       | 1         | 0.28%   |
| es_AR       | 1         | 0.28%   |
| en_US.utf-8 | 1         | 0.28%   |
| en_PH       | 1         | 0.28%   |
| en_IE       | 1         | 0.28%   |
| ca_ES       | 1         | 0.28%   |
| bg_BG       | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 195       | 55.08%  |
| BIOS | 159       | 44.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 208       | 59.09%  |
| Btrfs   | 88        | 25%     |
| Xfs     | 22        | 6.25%   |
| Zfs     | 14        | 3.98%   |
| Overlay | 7         | 1.99%   |
| Unknown | 7         | 1.99%   |
| F2fs    | 4         | 1.14%   |
| XXX4    | 1         | 0.28%   |
| Ext3    | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 213       | 60.17%  |
| Unknown | 103       | 29.1%   |
| MBR     | 38        | 10.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 305       | 87.39%  |
| Yes       | 44        | 12.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 276       | 78.86%  |
| Yes       | 74        | 21.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 76        | 21.97%  |
| ASUSTek Computer               | 63        | 18.21%  |
| Hewlett-Packard                | 39        | 11.27%  |
| Dell                           | 25        | 7.23%   |
| MSI                            | 24        | 6.94%   |
| Acer                           | 24        | 6.94%   |
| Gigabyte Technology            | 18        | 5.2%    |
| ASRock                         | 15        | 4.34%   |
| Apple                          | 7         | 2.02%   |
| Unknown                        | 7         | 2.02%   |
| TUXEDO                         | 4         | 1.16%   |
| HUAWEI                         | 4         | 1.16%   |
| Raspberry Pi Foundation        | 3         | 0.87%   |
| Positivo                       | 3         | 0.87%   |
| Notebook                       | 2         | 0.58%   |
| Microsoft                      | 2         | 0.58%   |
| Fujitsu                        | 2         | 0.58%   |
| Framework                      | 2         | 0.58%   |
| VX                             | 1         | 0.29%   |
| Toshiba                        | 1         | 0.29%   |
| Timi                           | 1         | 0.29%   |
| TECNO Mobile Limited           | 1         | 0.29%   |
| Supermicro                     | 1         | 0.29%   |
| Shuttle                        | 1         | 0.29%   |
| SHENZHEN YOUDISI E-COMMERCE    | 1         | 0.29%   |
| Samsung Electronics            | 1         | 0.29%   |
| Razer                          | 1         | 0.29%   |
| Pine Microsystems              | 1         | 0.29%   |
| PELADN                         | 1         | 0.29%   |
| OrangePi                       | 1         | 0.29%   |
| Nokia                          | 1         | 0.29%   |
| Matsushita Electric Industrial | 1         | 0.29%   |
| Intel                          | 1         | 0.29%   |
| Google                         | 1         | 0.29%   |
| Getac                          | 1         | 0.29%   |
| Exo                            | 1         | 0.29%   |
| EVOO                           | 1         | 0.29%   |
| EVGA                           | 1         | 0.29%   |
| Digibras                       | 1         | 0.29%   |
| Cisco Systems                  | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 9         | 2.6%    |
| TUXEDO Sirius 16 Gen2                  | 2         | 0.58%   |
| RPi Raspberry Pi                       | 2         | 0.58%   |
| Positivo Mobile                        | 2         | 0.58%   |
| MSI MS-7C02                            | 2         | 0.58%   |
| MSI MS-7B86                            | 2         | 0.58%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW  | 2         | 0.58%   |
| HP Pavilion Notebook                   | 2         | 0.58%   |
| HP Pavilion 15                         | 2         | 0.58%   |
| HP Laptop 15-bw0xx                     | 2         | 0.58%   |
| HP 15                                  | 2         | 0.58%   |
| Dell XPS 15 9500                       | 2         | 0.58%   |
| Dell OptiPlex 780                      | 2         | 0.58%   |
| Dell OptiPlex 7010                     | 2         | 0.58%   |
| ASUS X751LD                            | 2         | 0.58%   |
| ASUS PRIME Z390-P                      | 2         | 0.58%   |
| ASUS PRIME X470-PRO                    | 2         | 0.58%   |
| ASRock B450 Pro4                       | 2         | 0.58%   |
| Apple MacBookPro11,1                   | 2         | 0.58%   |
| Acer Swift SF314-42                    | 2         | 0.58%   |
| VX B75                                 | 1         | 0.29%   |
| TUXEDO Pulse 14 Gen3                   | 1         | 0.29%   |
| TUXEDO Aura 15 Gen1                    | 1         | 0.29%   |
| Toshiba Satellite A200                 | 1         | 0.29%   |
| Timi Redmi Book Pro 15 2022            | 1         | 0.29%   |
| TECNO Mobile Limited MEGABOOK K16SDA   | 1         | 0.29%   |
| Supermicro Super Server                | 1         | 0.29%   |
| Shuttle DH170                          | 1         | 0.29%   |
| SHENZHEN YOUDISI E-COMMERCE LAITNIN G5 | 1         | 0.29%   |
| Samsung 275E4E/275E5E                  | 1         | 0.29%   |
| Razer Blade 14 (2022) - RZ09-0427      | 1         | 0.29%   |
| RPi Raspberry Pi Zero 2 W Rev 1.0      | 1         | 0.29%   |
| Positivo R732512BI-15                  | 1         | 0.29%   |
| Pine Microsystems Pine64 Pinebook Pro  | 1         | 0.29%   |
| PELADN WI-6                            | 1         | 0.29%   |
| OrangePi Zero3                         | 1         | 0.29%   |
| Notebook NV4XMB,ME,MZ                  | 1         | 0.29%   |
| Notebook NH50_70RA                     | 1         | 0.29%   |
| Nokia Booklet 3G                       | 1         | 0.29%   |
| MSI Summit E13FlipEvo A12MT            | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 42        | 12.14%  |
| Lenovo IdeaPad     | 15        | 4.34%   |
| ASUS PRIME         | 15        | 4.34%   |
| Acer Aspire        | 14        | 4.05%   |
| ASUS VivoBook      | 10        | 2.89%   |
| Unknown            | 9         | 2.6%    |
| HP Pavilion        | 8         | 2.31%   |
| Dell Latitude      | 7         | 2.02%   |
| HP Laptop          | 6         | 1.73%   |
| Dell OptiPlex      | 6         | 1.73%   |
| Dell Inspiron      | 5         | 1.45%   |
| ASUS TUF           | 5         | 1.45%   |
| ASUS ROG           | 5         | 1.45%   |
| Lenovo ThinkBook   | 4         | 1.16%   |
| ASUS ASUS          | 4         | 1.16%   |
| RPi Raspberry      | 3         | 0.87%   |
| HP Stream          | 3         | 0.87%   |
| Dell XPS           | 3         | 0.87%   |
| TUXEDO Sirius      | 2         | 0.58%   |
| Positivo Mobile    | 2         | 0.58%   |
| MSI MS-7C02        | 2         | 0.58%   |
| MSI MS-7B86        | 2         | 0.58%   |
| Microsoft Surface  | 2         | 0.58%   |
| Lenovo Yoga        | 2         | 0.58%   |
| Lenovo ThinkCentre | 2         | 0.58%   |
| Lenovo LOQ         | 2         | 0.58%   |
| Lenovo Legion      | 2         | 0.58%   |
| HP Spectre         | 2         | 0.58%   |
| HP ENVY            | 2         | 0.58%   |
| HP EliteDesk       | 2         | 0.58%   |
| HP EliteBook       | 2         | 0.58%   |
| HP Compaq          | 2         | 0.58%   |
| HP 255             | 2         | 0.58%   |
| HP 15              | 2         | 0.58%   |
| Gigabyte X570      | 2         | 0.58%   |
| Gigabyte H310M     | 2         | 0.58%   |
| Gigabyte B550M     | 2         | 0.58%   |
| Gigabyte B550      | 2         | 0.58%   |
| Framework Laptop   | 2         | 0.58%   |
| ASUS X751LD        | 2         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 44        | 12.72%  |
| 2020    | 39        | 11.27%  |
| 2018    | 32        | 9.25%   |
| 2021    | 27        | 7.8%    |
| 2023    | 20        | 5.78%   |
| 2014    | 20        | 5.78%   |
| 2013    | 20        | 5.78%   |
| 2022    | 19        | 5.49%   |
| 2017    | 18        | 5.2%    |
| 2012    | 15        | 4.34%   |
| 2024    | 14        | 4.05%   |
| 2016    | 13        | 3.76%   |
| 2015    | 12        | 3.47%   |
| 2011    | 12        | 3.47%   |
| 2010    | 9         | 2.6%    |
| Unknown | 8         | 2.31%   |
| 2009    | 6         | 1.73%   |
| 2008    | 5         | 1.45%   |
| 2007    | 4         | 1.16%   |
| 2006    | 4         | 1.16%   |
| 2025    | 3         | 0.87%   |
| 2005    | 2         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 211       | 60.98%  |
| Desktop        | 111       | 32.08%  |
| Convertible    | 7         | 2.02%   |
| System on chip | 4         | 1.16%   |
| Tablet         | 4         | 1.16%   |
| Mini pc        | 3         | 0.87%   |
| All in one     | 3         | 0.87%   |
| Server         | 3         | 0.87%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 345       | 99.71%  |
| Enabled  | 1         | 0.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 345       | 99.71%  |
| Yes  | 1         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 75        | 21.43%  |
| 4.01-8.0        | 65        | 18.57%  |
| 8.01-16.0       | 64        | 18.29%  |
| 32.01-64.0      | 50        | 14.29%  |
| 3.01-4.0        | 44        | 12.57%  |
| 1.01-2.0        | 17        | 4.86%   |
| 24.01-32.0      | 14        | 4%      |
| 64.01-256.0     | 12        | 3.43%   |
| 0.51-1.0        | 4         | 1.14%   |
| 2.01-3.0        | 2         | 0.57%   |
| 0.01-0.5        | 2         | 0.57%   |
| More than 256.0 | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 107       | 28.92%  |
| 2.01-3.0    | 83        | 22.43%  |
| 4.01-8.0    | 58        | 15.68%  |
| 3.01-4.0    | 50        | 13.51%  |
| 0.51-1.0    | 31        | 8.38%   |
| 8.01-16.0   | 21        | 5.68%   |
| 0.01-0.5    | 14        | 3.78%   |
| 16.01-24.0  | 4         | 1.08%   |
| 64.01-256.0 | 2         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 221       | 63.14%  |
| 2      | 79        | 22.57%  |
| 3      | 34        | 9.71%   |
| 4      | 8         | 2.29%   |
| 5      | 5         | 1.43%   |
| 9      | 1         | 0.29%   |
| 7      | 1         | 0.29%   |
| 0      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 280       | 80.92%  |
| Yes       | 66        | 19.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 277       | 79.83%  |
| No        | 70        | 20.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 271       | 78.1%   |
| No        | 76        | 21.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 238       | 68.39%  |
| No        | 110       | 31.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 70        | 20.17%  |
| Germany     | 31        | 8.93%   |
| Russia      | 28        | 8.07%   |
| Brazil      | 20        | 5.76%   |
| UK          | 18        | 5.19%   |
| India       | 15        | 4.32%   |
| Italy       | 12        | 3.46%   |
| Canada      | 12        | 3.46%   |
| Poland      | 10        | 2.88%   |
| Czechia     | 10        | 2.88%   |
| France      | 9         | 2.59%   |
| Turkey      | 8         | 2.31%   |
| Denmark     | 7         | 2.02%   |
| Netherlands | 6         | 1.73%   |
| Greece      | 6         | 1.73%   |
| Switzerland | 5         | 1.44%   |
| Spain       | 5         | 1.44%   |
| Romania     | 5         | 1.44%   |
| Australia   | 5         | 1.44%   |
| Vietnam     | 4         | 1.15%   |
| Ukraine     | 4         | 1.15%   |
| Argentina   | 4         | 1.15%   |
| Thailand    | 3         | 0.86%   |
| Norway      | 3         | 0.86%   |
| Bulgaria    | 3         | 0.86%   |
| Belarus     | 3         | 0.86%   |
| Uruguay     | 2         | 0.58%   |
| Serbia      | 2         | 0.58%   |
| Portugal    | 2         | 0.58%   |
| Philippines | 2         | 0.58%   |
| New Zealand | 2         | 0.58%   |
| Morocco     | 2         | 0.58%   |
| Mexico      | 2         | 0.58%   |
| Latvia      | 2         | 0.58%   |
| Indonesia   | 2         | 0.58%   |
| Finland     | 2         | 0.58%   |
| Ecuador     | 2         | 0.58%   |
| Chile       | 2         | 0.58%   |
| Venezuela   | 1         | 0.29%   |
| Sweden      | 1         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 9         | 2.51%   |
| Prague           | 7         | 1.96%   |
| Sao Paulo        | 5         | 1.4%    |
| Milton           | 5         | 1.4%    |
| Munich           | 4         | 1.12%   |
| Izmir            | 4         | 1.12%   |
| Vancouver        | 3         | 0.84%   |
| St Petersburg    | 3         | 0.84%   |
| Orlando          | 3         | 0.84%   |
| Lublin           | 3         | 0.84%   |
| Harrisonburg     | 3         | 0.84%   |
| Denver           | 3         | 0.84%   |
| Bengaluru        | 3         | 0.84%   |
| Bangkok          | 3         | 0.84%   |
| Amsterdam        | 3         | 0.84%   |
| Warsaw           | 2         | 0.56%   |
| Toulouse         | 2         | 0.56%   |
| Sydney           | 2         | 0.56%   |
| Spring Hill      | 2         | 0.56%   |
| Sofia            | 2         | 0.56%   |
| San Antonio      | 2         | 0.56%   |
| Rosario          | 2         | 0.56%   |
| Rome             | 2         | 0.56%   |
| Riga             | 2         | 0.56%   |
| Pyatigorsk       | 2         | 0.56%   |
| Piteşti         | 2         | 0.56%   |
| Milan            | 2         | 0.56%   |
| Mieres           | 2         | 0.56%   |
| Meknes           | 2         | 0.56%   |
| London           | 2         | 0.56%   |
| Kenmore          | 2         | 0.56%   |
| Istanbul         | 2         | 0.56%   |
| Ioannina         | 2         | 0.56%   |
| Hyderabad        | 2         | 0.56%   |
| Ho Chi Minh City | 2         | 0.56%   |
| Hanover          | 2         | 0.56%   |
| Geneva           | 2         | 0.56%   |
| Codlea           | 2         | 0.56%   |
| Aarhus           | 2         | 0.56%   |
| Aalborg          | 2         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 93        | 130    | 18.9%   |
| WDC                          | 59        | 74     | 11.99%  |
| Seagate                      | 51        | 69     | 10.37%  |
| Sandisk                      | 39        | 45     | 7.93%   |
| Kingston                     | 32        | 33     | 6.5%    |
| Unknown                      | 23        | 31     | 4.67%   |
| Toshiba                      | 19        | 20     | 3.86%   |
| SK hynix                     | 18        | 23     | 3.66%   |
| Intel                        | 15        | 19     | 3.05%   |
| Crucial                      | 13        | 15     | 2.64%   |
| Hitachi                      | 12        | 12     | 2.44%   |
| HGST                         | 12        | 15     | 2.44%   |
| Micron Technology            | 9         | 13     | 1.83%   |
| KIOXIA                       | 7         | 8      | 1.42%   |
| Phison Electronics           | 6         | 6      | 1.22%   |
| Kingston Technology Company  | 6         | 7      | 1.22%   |
| PNY                          | 5         | 6      | 1.02%   |
| Lenovo                       | 5         | 5      | 1.02%   |
| A-DATA Technology            | 5         | 7      | 1.02%   |
| Realtek Semiconductor        | 4         | 4      | 0.81%   |
| Micron/Crucial Technology    | 4         | 4      | 0.81%   |
| Apple                        | 4         | 4      | 0.81%   |
| Phison                       | 3         | 3      | 0.61%   |
| Patriot                      | 3         | 3      | 0.61%   |
| MAXIO Technology (Hangzhou)  | 3         | 4      | 0.61%   |
| Corsair                      | 3         | 3      | 0.61%   |
| China                        | 3         | 3      | 0.61%   |
| ADATA Technology             | 3         | 4      | 0.61%   |
| SPCC                         | 2         | 2      | 0.41%   |
| Lexar                        | 2         | 3      | 0.41%   |
| XrayDisk                     | 1         | 1      | 0.2%    |
| XPG                          | 1         | 4      | 0.2%    |
| Union Memory (Shenzhen)      | 1         | 1      | 0.2%    |
| Union Memory                 | 1         | 1      | 0.2%    |
| Transcend                    | 1         | 1      | 0.2%    |
| T-FORCE                      | 1         | 1      | 0.2%    |
| SuperSSpeed                  | 1         | 1      | 0.2%    |
| Shenzhen Longsys Electronics | 1         | 1      | 0.2%    |
| Realtek                      | 1         | 1      | 0.2%    |
| PELADN                       | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 12        | 2.23%   |
| Unknown MMC Card  32GB                               | 9         | 1.67%   |
| Kingston SA400S37240G 240GB SSD                      | 9         | 1.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 7         | 1.3%    |
| Unknown MMC Card  64GB                               | 6         | 1.11%   |
| Seagate ST1000LM035-1RK172 1TB                       | 6         | 1.11%   |
| Seagate ST2000DM008-2FR102 2TB                       | 5         | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB                       | 5         | 0.93%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                | 5         | 0.93%   |
| Samsung SSD 980 1TB                                  | 5         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 5         | 0.93%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 4         | 0.74%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 4         | 0.74%   |
| Samsung SSD 870 EVO 500GB                            | 4         | 0.74%   |
| Kingston SA400S37120G 120GB SSD                      | 4         | 0.74%   |
| HGST HTS545050A7E680 500GB                           | 4         | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 3         | 0.56%   |
| Unknown MMC Card  128GB                              | 3         | 0.56%   |
| Toshiba MQ01ABF050 500GB                             | 3         | 0.56%   |
| Toshiba DT01ACA050 500GB                             | 3         | 0.56%   |
| Samsung SSD 870 QVO 1TB                              | 3         | 0.56%   |
| Samsung SSD 850 EVO 500GB                            | 3         | 0.56%   |
| Samsung NVMe SSD Drive 1TB                           | 3         | 0.56%   |
| PNY SSD2SC120G1SA754D117-820 120GB                   | 3         | 0.56%   |
| Phison E12 NVMe Controller 1TB                       | 3         | 0.56%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                  | 3         | 0.56%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB     | 3         | 0.56%   |
| Lenovo LENSE30256GMSP34MEAT3TA 256GB                 | 3         | 0.56%   |
| Kingston SNVS500G 500GB                              | 3         | 0.56%   |
| Kingston SHFS37A120G 120GB SSD                       | 3         | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                            | 3         | 0.56%   |
| Crucial CT500MX500SSD1 500GB                         | 3         | 0.56%   |
| Crucial CT240BX500SSD1 240GB                         | 3         | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB                         | 2         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 2         | 0.37%   |
| WDC WD5000LPVX-22V0TT0 500GB                         | 2         | 0.37%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 2         | 0.37%   |
| Unknown MMC Card  8GB                                | 2         | 0.37%   |
| Toshiba MQ04ABF100 1TB                               | 2         | 0.37%   |
| Toshiba MQ01ABD100 1TB                               | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 69     | 32.48%  |
| WDC                 | 50        | 61     | 31.85%  |
| Toshiba             | 16        | 17     | 10.19%  |
| Hitachi             | 12        | 12     | 7.64%   |
| HGST                | 12        | 15     | 7.64%   |
| Samsung Electronics | 8         | 10     | 5.1%    |
| XrayDisk            | 1         | 1      | 0.64%   |
| Unknown             | 1         | 1      | 0.64%   |
| Maxtor              | 1         | 1      | 0.64%   |
| JMicron Technology  | 1         | 1      | 0.64%   |
| IBM/Hitachi         | 1         | 1      | 0.64%   |
| Hewlett-Packard     | 1         | 1      | 0.64%   |
| Fujitsu             | 1         | 1      | 0.64%   |
| Apple               | 1         | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 36     | 22.79%  |
| Kingston            | 26        | 27     | 19.12%  |
| SanDisk             | 12        | 15     | 8.82%   |
| Crucial             | 11        | 13     | 8.09%   |
| WDC                 | 8         | 9      | 5.88%   |
| PNY                 | 5         | 6      | 3.68%   |
| Intel               | 4         | 5      | 2.94%   |
| A-DATA Technology   | 4         | 6      | 2.94%   |
| Patriot             | 3         | 3      | 2.21%   |
| China               | 3         | 3      | 2.21%   |
| Apple               | 3         | 3      | 2.21%   |
| SPCC                | 2         | 2      | 1.47%   |
| Lexar               | 2         | 3      | 1.47%   |
| Transcend           | 1         | 1      | 0.74%   |
| Toshiba             | 1         | 1      | 0.74%   |
| T-FORCE             | 1         | 1      | 0.74%   |
| SuperSSpeed         | 1         | 1      | 0.74%   |
| SK hynix            | 1         | 1      | 0.74%   |
| PELADN              | 1         | 1      | 0.74%   |
| ORIGIN              | 1         | 1      | 0.74%   |
| OCZ                 | 1         | 1      | 0.74%   |
| NGFF                | 1         | 1      | 0.74%   |
| Netac               | 1         | 1      | 0.74%   |
| LITEONIT            | 1         | 1      | 0.74%   |
| Lenovo              | 1         | 1      | 0.74%   |
| Intenso             | 1         | 1      | 0.74%   |
| INNOVATION IT       | 1         | 1      | 0.74%   |
| HS-SSD-E100         | 1         | 1      | 0.74%   |
| Gigabyte Technology | 1         | 2      | 0.74%   |
| Corsair             | 1         | 1      | 0.74%   |
| BIWIN               | 1         | 1      | 0.74%   |
| BHT                 | 1         | 1      | 0.74%   |
| AMD                 | 1         | 1      | 0.74%   |
| AGI                 | 1         | 1      | 0.74%   |
| Unknown             | 1         | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 171       | 233    | 38.08%  |
| HDD     | 137       | 192    | 30.51%  |
| SSD     | 118       | 154    | 26.28%  |
| MMC     | 22        | 28     | 4.9%    |
| Unknown | 1         | 1      | 0.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 204       | 335    | 49.76%  |
| NVMe | 171       | 230    | 41.71%  |
| MMC  | 22        | 28     | 5.37%   |
| SAS  | 13        | 15     | 3.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 142       | 189    | 54.2%   |
| 0.51-1.0   | 84        | 103    | 32.06%  |
| 1.01-2.0   | 21        | 28     | 8.02%   |
| 3.01-4.0   | 8         | 17     | 3.05%   |
| 4.01-10.0  | 6         | 8      | 2.29%   |
| 10.01-20.0 | 1         | 1      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 77        | 21.63%  |
| 101-250        | 75        | 21.07%  |
| 501-1000       | 72        | 20.22%  |
| 1001-2000      | 35        | 9.83%   |
| 1-20           | 20        | 5.62%   |
| 51-100         | 20        | 5.62%   |
| Unknown        | 20        | 5.62%   |
| More than 3000 | 19        | 5.34%   |
| 2001-3000      | 10        | 2.81%   |
| 21-50          | 8         | 2.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 106       | 28.88%  |
| 101-250        | 68        | 18.53%  |
| 21-50          | 56        | 15.26%  |
| 251-500        | 34        | 9.26%   |
| 51-100         | 32        | 8.72%   |
| 501-1000       | 25        | 6.81%   |
| Unknown        | 20        | 5.45%   |
| 1001-2000      | 17        | 4.63%   |
| More than 3000 | 7         | 1.91%   |
| 2001-3000      | 2         | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Computers | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB                       | 2         | 2      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB                           | 2         | 2      | 4.35%   |
| HGST HTS545050A7E680 500GB                                | 2         | 2      | 4.35%   |
| HGST HTS541010A9E680 1TB                                  | 2         | 2      | 4.35%   |
| WDC WD5000AADS-00S9B0 500GB                               | 1         | 2      | 2.17%   |
| WDC WD3200BPVT-75JJ5T0 320GB                              | 1         | 1      | 2.17%   |
| WDC WD2003FZEX-00Z4SA0 2TB                                | 1         | 1      | 2.17%   |
| WDC WD1600BEVS-60VAT0 160GB                               | 1         | 1      | 2.17%   |
| WDC WD10EZEX-08WN4A0 1TB                                  | 1         | 1      | 2.17%   |
| Toshiba MQ04ABF100 1TB                                    | 1         | 2      | 2.17%   |
| Toshiba MQ01ABF050 500GB                                  | 1         | 1      | 2.17%   |
| Seagate ST980811AS 80GB                                   | 1         | 1      | 2.17%   |
| Seagate ST9750420AS 752GB                                 | 1         | 1      | 2.17%   |
| Seagate ST9500325AS 500GB                                 | 1         | 1      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB                           | 1         | 1      | 2.17%   |
| Seagate ST4000VN008-2DR166 4TB                            | 1         | 2      | 2.17%   |
| Seagate ST4000VN000-1H4168 4TB                            | 1         | 4      | 2.17%   |
| Seagate ST3750330AS 752GB                                 | 1         | 1      | 2.17%   |
| Seagate ST3250410AS 250GB                                 | 1         | 1      | 2.17%   |
| Seagate ST3160318AS 160GB                                 | 1         | 1      | 2.17%   |
| Seagate ST2000VX000-1CU164 2TB                            | 1         | 2      | 2.17%   |
| Seagate ST2000DM001-1CH164 2TB                            | 1         | 1      | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB                            | 1         | 1      | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                        | 1         | 1      | 2.17%   |
| SanDisk SSD U100 256GB                                    | 1         | 2      | 2.17%   |
| SanDisk SSD PLUS 240GB                                    | 1         | 1      | 2.17%   |
| Samsung Electronics SSD 870 EVO 500GB                     | 1         | 1      | 2.17%   |
| Samsung Electronics HM160HI 160GB                         | 1         | 1      | 2.17%   |
| Samsung Electronics HD502HJ 500GB                         | 1         | 1      | 2.17%   |
| Samsung Electronics HD322HJ 320GB                         | 1         | 1      | 2.17%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 512GB | 1         | 1      | 2.17%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB                         | 1         | 1      | 2.17%   |
| Hitachi HUA722010CLA330 1TB                               | 1         | 1      | 2.17%   |
| Hitachi HTS727575A9E364 752GB                             | 1         | 1      | 2.17%   |
| Hitachi HTS545050B9A300 500GB                             | 1         | 1      | 2.17%   |
| Hitachi HTS545050A7E380 500GB                             | 1         | 1      | 2.17%   |
| Hitachi HTS543216L9A300 160GB                             | 1         | 1      | 2.17%   |
| Hitachi HTS541680J9SA00 80GB                              | 1         | 1      | 2.17%   |
| HGST HTS545050A7E380 500GB                                | 1         | 1      | 2.17%   |
| Crucial CT525MX300SSD1 528GB                              | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 15        | 22     | 34.09%  |
| Hitachi               | 6         | 6      | 13.64%  |
| WDC                   | 5         | 6      | 11.36%  |
| HGST                  | 5         | 5      | 11.36%  |
| Samsung Electronics   | 4         | 4      | 9.09%   |
| Toshiba               | 2         | 3      | 4.55%   |
| SanDisk               | 2         | 3      | 4.55%   |
| Crucial               | 2         | 2      | 4.55%   |
| Realtek Semiconductor | 1         | 1      | 2.27%   |
| IBM/Hitachi           | 1         | 1      | 2.27%   |
| A-DATA Technology     | 1         | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 22     | 40.54%  |
| Hitachi             | 6         | 6      | 16.22%  |
| WDC                 | 5         | 6      | 13.51%  |
| HGST                | 5         | 5      | 13.51%  |
| Samsung Electronics | 3         | 3      | 8.11%   |
| Toshiba             | 2         | 3      | 5.41%   |
| IBM/Hitachi         | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 46     | 83.72%  |
| SSD  | 6         | 7      | 13.95%  |
| NVMe | 1         | 1      | 2.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC WD2000JS-60NCB1 200GB | 1         | 1      | 50%     |
| Intel SSDSC2BW240H6 240GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| Intel  | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 201       | 304    | 51.67%  |
| Detected | 146       | 248    | 37.53%  |
| Malfunc  | 40        | 54     | 10.28%  |
| Failed   | 2         | 2      | 0.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 166       | 37.22%  |
| AMD                                     | 85        | 19.06%  |
| Samsung Electronics                     | 64        | 14.35%  |
| Sandisk                                 | 29        | 6.5%    |
| SK hynix                                | 17        | 3.81%   |
| Kingston Technology Company             | 12        | 2.69%   |
| Phison Electronics                      | 11        | 2.47%   |
| Micron Technology                       | 9         | 2.02%   |
| KIOXIA                                  | 7         | 1.57%   |
| ASMedia Technology                      | 6         | 1.35%   |
| Micron/Crucial Technology               | 5         | 1.12%   |
| ADATA Technology                        | 5         | 1.12%   |
| Realtek Semiconductor                   | 4         | 0.9%    |
| Marvell Technology Group                | 4         | 0.9%    |
| Lenovo                                  | 4         | 0.9%    |
| Nvidia                                  | 3         | 0.67%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.67%   |
| Toshiba America Info Systems            | 2         | 0.45%   |
| LSI Logic / Symbios Logic               | 2         | 0.45%   |
| Union Memory (Shenzhen)                 | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.22%   |
| Shenzhen Unionmemory Information System | 1         | 0.22%   |
| Shenzhen Longsys Electronics            | 1         | 0.22%   |
| JMicron Technology                      | 1         | 0.22%   |
| Hewlett-Packard                         | 1         | 0.22%   |
| Chelsio Communications                  | 1         | 0.22%   |
| Broadcom                                | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 55        | 11.09%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 25        | 5.04%   |
| AMD 400 Series Chipset SATA Controller                                         | 16        | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 3.02%   |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 2.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 11        | 2.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 2.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 2.02%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 8         | 1.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 1.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 8         | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.41%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 1.41%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 6         | 1.21%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 6         | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 1.21%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6         | 1.21%   |
| Phison E12 NVMe Controller                                                     | 5         | 1.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 0.81%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 4         | 0.81%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 4         | 0.81%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 0.81%   |
| Intel SATA Controller [RAID Mode]                                              | 4         | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 0.81%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 0.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 0.81%   |
| Sandisk WD PC SN5000S M.2 2242 NVMe SSD (DRAM-less)                            | 3         | 0.6%    |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3         | 0.6%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 0.6%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 3         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 221       | 49.55%  |
| NVMe | 172       | 38.57%  |
| IDE  | 27        | 6.05%   |
| RAID | 24        | 5.38%   |
| SCSI | 2         | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 207       | 59.83%  |
| AMD                      | 130       | 37.57%  |
| ARM                      | 7         | 2.02%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.29%   |
| PowerMac11,2             | 1         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 1.73%   |
| ARM Processor                                 | 6         | 1.73%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 6         | 1.73%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.16%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 4         | 1.16%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 1.16%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 4         | 1.16%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4         | 1.16%   |
| Intel Core i9-14900K                          | 3         | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.87%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.87%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 0.87%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 0.87%   |
| AMD Ryzen 7 5700X 8-Core Processor            | 3         | 0.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.87%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.87%   |
| Intel Pentium M processor 2.13GHz             | 2         | 0.58%   |
| Intel Core Ultra 7 155H                       | 2         | 0.58%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.58%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.58%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.58%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.58%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.58%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 2         | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.58%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 2         | 0.58%   |
| Intel Core i3-5010U CPU @ 2.10GHz             | 2         | 0.58%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.58%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 55        | 15.9%   |
| AMD Ryzen 7             | 47        | 13.58%  |
| Other                   | 42        | 12.14%  |
| Intel Core i7           | 40        | 11.56%  |
| AMD Ryzen 5             | 34        | 9.83%   |
| Intel Core i3           | 23        | 6.65%   |
| Intel Celeron           | 14        | 4.05%   |
| Intel Atom              | 10        | 2.89%   |
| Intel Xeon              | 8         | 2.31%   |
| AMD Ryzen 9             | 8         | 2.31%   |
| AMD Ryzen 7 PRO         | 8         | 2.31%   |
| Intel Core 2 Duo        | 6         | 1.73%   |
| Intel Pentium           | 5         | 1.45%   |
| AMD Ryzen 3             | 5         | 1.45%   |
| Intel Core i9           | 4         | 1.16%   |
| AMD FX                  | 4         | 1.16%   |
| Intel Genuine           | 3         | 0.87%   |
| Intel Core              | 3         | 0.87%   |
| AMD A8                  | 3         | 0.87%   |
| AMD A4                  | 3         | 0.87%   |
| Intel Pentium M         | 2         | 0.58%   |
| Intel Core 2 Quad       | 2         | 0.58%   |
| Intel Pentium Gold      | 1         | 0.29%   |
| Intel Pentium Dual-Core | 1         | 0.29%   |
| Intel Pentium 4         | 1         | 0.29%   |
| AMD Turion 64 X2 Mobile | 1         | 0.29%   |
| AMD Ryzen Threadripper  | 1         | 0.29%   |
| AMD Ryzen 5 PRO         | 1         | 0.29%   |
| AMD Phenom II X4        | 1         | 0.29%   |
| AMD E2                  | 1         | 0.29%   |
| AMD E1                  | 1         | 0.29%   |
| AMD E                   | 1         | 0.29%   |
| AMD C-60                | 1         | 0.29%   |
| AMD Athlon X4           | 1         | 0.29%   |
| AMD Athlon X2           | 1         | 0.29%   |
| AMD Athlon II X3        | 1         | 0.29%   |
| AMD Athlon II X2        | 1         | 0.29%   |
| AMD A6                  | 1         | 0.29%   |
| AMD A10                 | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 107       | 30.92%  |
| 2       | 87        | 25.14%  |
| 8       | 61        | 17.63%  |
| 6       | 48        | 13.87%  |
| 1       | 11        | 3.18%   |
| 12      | 8         | 2.31%   |
| 16      | 7         | 2.02%   |
| 10      | 4         | 1.16%   |
| Unknown | 4         | 1.16%   |
| 24      | 3         | 0.87%   |
| 14      | 3         | 0.87%   |
| 64      | 1         | 0.29%   |
| 18      | 1         | 0.29%   |
| 3       | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 338       | 97.69%  |
| 2       | 4         | 1.16%   |
| Unknown | 4         | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 246       | 71.1%   |
| 1       | 95        | 27.46%  |
| Unknown | 4         | 1.16%   |
| 4       | 1         | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 328       | 94.8%   |
| Unknown        | 8         | 2.31%   |
| 32-bit         | 6         | 1.73%   |
| 64-bit         | 4         | 1.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 225       | 63.2%   |
| 0x40651    | 8         | 2.25%   |
| 0x306a9    | 7         | 1.97%   |
| 0x906e9    | 5         | 1.4%    |
| 0x0a404102 | 5         | 1.4%    |
| 0x906ea    | 4         | 1.12%   |
| 0x806ec    | 4         | 1.12%   |
| 0x806e9    | 4         | 1.12%   |
| 0x406e3    | 4         | 1.12%   |
| 0x08108102 | 4         | 1.12%   |
| 0x806ea    | 3         | 0.84%   |
| 0x30678    | 3         | 0.84%   |
| 0x206a7    | 3         | 0.84%   |
| 0x0a50000c | 3         | 0.84%   |
| 0x08600104 | 3         | 0.84%   |
| 0x0800820d | 3         | 0.84%   |
| 0x06006705 | 3         | 0.84%   |
| 0x906a3    | 2         | 0.56%   |
| 0x506e3    | 2         | 0.56%   |
| 0x106c2    | 2         | 0.56%   |
| 0x0a50000f | 2         | 0.56%   |
| 0x0a50000d | 2         | 0.56%   |
| 0x0a201009 | 2         | 0.56%   |
| 0x08701030 | 2         | 0.56%   |
| 0x08701021 | 2         | 0.56%   |
| 0x08608103 | 2         | 0.56%   |
| 0x08608102 | 2         | 0.56%   |
| 0x08600106 | 2         | 0.56%   |
| 0x07030105 | 2         | 0.56%   |
| 0x06000852 | 2         | 0.56%   |
| 0x05000119 | 2         | 0.56%   |
| 0x010000c8 | 2         | 0.56%   |
| 0xa0671    | 1         | 0.28%   |
| 0xa0652    | 1         | 0.28%   |
| 0x906ed    | 1         | 0.28%   |
| 0x90675    | 1         | 0.28%   |
| 0x90672    | 1         | 0.28%   |
| 0x806eb    | 1         | 0.28%   |
| 0x806c1    | 1         | 0.28%   |
| 0x706e5    | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 53        | 15.27%  |
| Unknown           | 48        | 13.83%  |
| Zen 3             | 32        | 9.22%   |
| Zen 2             | 21        | 6.05%   |
| Haswell           | 19        | 5.48%   |
| IvyBridge         | 16        | 4.61%   |
| Zen+              | 14        | 4.03%   |
| Alderlake Hybrid  | 14        | 4.03%   |
| Skylake           | 11        | 3.17%   |
| Silvermont        | 11        | 3.17%   |
| SandyBridge       | 10        | 2.88%   |
| Broadwell         | 9         | 2.59%   |
| TigerLake         | 8         | 2.31%   |
| IceLake           | 8         | 2.31%   |
| Excavator         | 8         | 2.31%   |
| Core              | 7         | 2.02%   |
| Zen               | 6         | 1.73%   |
| Penryn            | 6         | 1.73%   |
| CometLake         | 5         | 1.44%   |
| Bonnell           | 5         | 1.44%   |
| Piledriver        | 4         | 1.15%   |
| Goldmont plus     | 4         | 1.15%   |
| Westmere          | 3         | 0.86%   |
| Puma              | 3         | 0.86%   |
| P6                | 3         | 0.86%   |
| K10               | 3         | 0.86%   |
| Bobcat            | 3         | 0.86%   |
| Nehalem           | 2         | 0.58%   |
| Meteorlake Hybrid | 2         | 0.58%   |
| Gracemont         | 2         | 0.58%   |
| Steamroller       | 1         | 0.29%   |
| NetBurst          | 1         | 0.29%   |
| K8 Hammer         | 1         | 0.29%   |
| K8 & K10 hybrid   | 1         | 0.29%   |
| K10 Llano         | 1         | 0.29%   |
| Jaguar            | 1         | 0.29%   |
| Goldmont          | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 167       | 42.17%  |
| AMD                              | 131       | 33.08%  |
| Nvidia                           | 94        | 23.74%  |
| ASPEED Technology                | 2         | 0.51%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Matrox Electronics Systems       | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 13        | 3.11%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 11        | 2.63%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 11        | 2.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 11        | 2.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 10        | 2.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 10        | 2.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 9         | 2.15%   |
| AMD Rembrandt [Radeon 680M]                                               | 9         | 2.15%   |
| AMD Lucienne                                                              | 9         | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 8         | 1.91%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 8         | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 8         | 1.91%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 8         | 1.91%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 7         | 1.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 6         | 1.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 6         | 1.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 1.44%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 6         | 1.44%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 6         | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 6         | 1.44%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 5         | 1.2%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 5         | 1.2%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 5         | 1.2%    |
| AMD HawkPoint1                                                            | 5         | 1.2%    |
| AMD Barcelo                                                               | 5         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 4         | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 4         | 0.96%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 4         | 0.96%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                        | 4         | 0.96%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 3         | 0.72%   |
| Nvidia GP108M [GeForce MX250]                                             | 3         | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 3         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 3         | 0.72%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 3         | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                            | 3         | 0.72%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                           | 3         | 0.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 3         | 0.72%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 3         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 120       | 34.29%  |
| 1 x AMD              | 105       | 30%     |
| 1 x Nvidia           | 48        | 13.71%  |
| Intel + Nvidia       | 37        | 10.57%  |
| 2 x AMD              | 11        | 3.14%   |
| Other                | 9         | 2.57%   |
| AMD + Nvidia         | 7         | 2%      |
| Intel + AMD          | 4         | 1.14%   |
| 2 x Nvidia           | 2         | 0.57%   |
| AMD + ASPEED         | 2         | 0.57%   |
| 3 x AMD + 1 x Nvidia | 1         | 0.29%   |
| 3 x AMD              | 1         | 0.29%   |
| 2 x Intel            | 1         | 0.29%   |
| 1 x SiS              | 1         | 0.29%   |
| 1 x Matrox           | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 262       | 74.64%  |
| Proprietary | 70        | 19.94%  |
| Unknown     | 19        | 5.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 207       | 57.98%  |
| 0.01-0.5   | 34        | 9.52%   |
| 1.01-2.0   | 30        | 8.4%    |
| 3.01-4.0   | 24        | 6.72%   |
| 7.01-8.0   | 23        | 6.44%   |
| 0.51-1.0   | 15        | 4.2%    |
| 8.01-16.0  | 11        | 3.08%   |
| 5.01-6.0   | 7         | 1.96%   |
| 16.01-24.0 | 4         | 1.12%   |
| 2.01-3.0   | 2         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 49        | 13.03%  |
| Chimei Innolux       | 46        | 12.23%  |
| BOE                  | 39        | 10.37%  |
| Samsung Electronics  | 38        | 10.11%  |
| LG Display           | 26        | 6.91%   |
| Hewlett-Packard      | 15        | 3.99%   |
| Goldstar             | 15        | 3.99%   |
| Dell                 | 15        | 3.99%   |
| Philips              | 9         | 2.39%   |
| Acer                 | 9         | 2.39%   |
| Lenovo               | 8         | 2.13%   |
| Apple                | 7         | 1.86%   |
| AOC                  | 7         | 1.86%   |
| MSI                  | 6         | 1.6%    |
| Iiyama               | 5         | 1.33%   |
| BenQ                 | 5         | 1.33%   |
| ViewSonic            | 4         | 1.06%   |
| Sharp                | 4         | 1.06%   |
| PANDA                | 4         | 1.06%   |
| LG Philips           | 4         | 1.06%   |
| Ancor Communications | 4         | 1.06%   |
| Unknown              | 4         | 1.06%   |
| CSO                  | 3         | 0.8%    |
| ASUSTek Computer     | 3         | 0.8%    |
| Unknown (XXX)        | 2         | 0.53%   |
| Unknown              | 2         | 0.53%   |
| TMX                  | 2         | 0.53%   |
| Sceptre Tech         | 2         | 0.53%   |
| Fujitsu Siemens      | 2         | 0.53%   |
| Eizo                 | 2         | 0.53%   |
| CTO                  | 2         | 0.53%   |
| BOE Technology Group | 2         | 0.53%   |
| ___                  | 1         | 0.27%   |
| YMK                  | 1         | 0.27%   |
| Vizio                | 1         | 0.27%   |
| Toshiba              | 1         | 0.27%   |
| TMA                  | 1         | 0.27%   |
| STD                  | 1         | 0.27%   |
| Sceptre              | 1         | 0.27%   |
| Quanta Display       | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch    | 4         | 1.03%   |
| Unknown                                                           | 4         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch  | 3         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch  | 3         | 0.77%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch              | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch    | 3         | 0.77%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch            | 2         | 0.51%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch           | 2         | 0.51%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch | 2         | 0.51%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch | 2         | 0.51%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch | 2         | 0.51%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch           | 2         | 0.51%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch           | 2         | 0.51%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch       | 2         | 0.51%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch             | 2         | 0.51%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch             | 2         | 0.51%   |
| Hewlett-Packard Z24n G3 HPN36C8 1920x1200 518x324mm 24.1-inch     | 2         | 0.51%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch      | 2         | 0.51%   |
| Hewlett-Packard 22w HPN342E 1920x1080 476x268mm 21.5-inch         | 2         | 0.51%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 2         | 0.51%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch            | 2         | 0.51%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch  | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch   | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1614 1920x1200 344x215mm 16.0-inch  | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch   | 2         | 0.51%   |
| BOE Technology Group LCD Monitor 1920x1080                        | 2         | 0.51%   |
| BOE LCD Monitor BOE09E5 2560x1440 355x200mm 16.0-inch             | 2         | 0.51%   |
| BenQ V2400Eco BNQ7D02 1920x1080 531x299mm 24.0-inch               | 2         | 0.51%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch    | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch    | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch    | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch    | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch     | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch     | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch     | 2         | 0.51%   |
| Apple Color LCD APPA020 2560x1600 286x179mm 13.3-inch             | 2         | 0.51%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                      | 2         | 0.51%   |
| ___ LCDTV ___0309 1920x1080 700x390mm 31.5-inch                   | 1         | 0.26%   |
| YMK EM160TP-A YMK447A 2880x1800 340x220mm 15.9-inch               | 1         | 0.26%   |
| Vizio D24h-C1 VIZ0095 1360x768 521x293mm 23.5-inch                | 1         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 151       | 41.71%  |
| 1366x768 (WXGA)    | 56        | 15.47%  |
| 2560x1440 (QHD)    | 27        | 7.46%   |
| 1920x1200 (WUXGA)  | 26        | 7.18%   |
| 3840x2160 (4K)     | 20        | 5.52%   |
| 1600x900 (HD+)     | 12        | 3.31%   |
| 2880x1800          | 7         | 1.93%   |
| 3440x1440          | 6         | 1.66%   |
| 2560x1600          | 6         | 1.66%   |
| 1440x900 (WXGA+)   | 6         | 1.66%   |
| 1280x800 (WXGA)    | 5         | 1.38%   |
| Unknown            | 5         | 1.38%   |
| 2560x1080          | 4         | 1.1%    |
| 2160x1440          | 4         | 1.1%    |
| 1680x1050 (WSXGA+) | 4         | 1.1%    |
| 3840x1080          | 3         | 0.83%   |
| 1280x1024 (SXGA)   | 3         | 0.83%   |
| 1024x600           | 3         | 0.83%   |
| 2256x1504          | 2         | 0.55%   |
| 1920x1280          | 2         | 0.55%   |
| 1024x768 (XGA)     | 2         | 0.55%   |
| 7680x1080          | 1         | 0.28%   |
| 7040x1440          | 1         | 0.28%   |
| 3840x1600          | 1         | 0.28%   |
| 3200x2000          | 1         | 0.28%   |
| 2288x1287          | 1         | 0.28%   |
| 1600x1200          | 1         | 0.28%   |
| 1360x768           | 1         | 0.28%   |
| 1280x720 (HD)      | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 90        | 24.06%  |
| 14      | 45        | 12.03%  |
| 13      | 37        | 9.89%   |
| 24      | 35        | 9.36%   |
| 27      | 23        | 6.15%   |
| Unknown | 21        | 5.61%   |
| 23      | 17        | 4.55%   |
| 21      | 14        | 3.74%   |
| 16      | 13        | 3.48%   |
| 31      | 10        | 2.67%   |
| 17      | 8         | 2.14%   |
| 11      | 8         | 2.14%   |
| 34      | 7         | 1.87%   |
| 22      | 6         | 1.6%    |
| 19      | 6         | 1.6%    |
| 12      | 4         | 1.07%   |
| 10      | 4         | 1.07%   |
| 84      | 3         | 0.8%    |
| 28      | 3         | 0.8%    |
| 20      | 3         | 0.8%    |
| 48      | 2         | 0.53%   |
| 32      | 2         | 0.53%   |
| 25      | 2         | 0.53%   |
| 18      | 2         | 0.53%   |
| 63      | 1         | 0.27%   |
| 54      | 1         | 0.27%   |
| 49      | 1         | 0.27%   |
| 40      | 1         | 0.27%   |
| 39      | 1         | 0.27%   |
| 37      | 1         | 0.27%   |
| 33      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 8       | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 161       | 43.75%  |
| 501-600     | 71        | 19.29%  |
| 201-300     | 39        | 10.6%   |
| 401-500     | 28        | 7.61%   |
| Unknown     | 21        | 5.71%   |
| 601-700     | 16        | 4.35%   |
| 701-800     | 10        | 2.72%   |
| 351-400     | 10        | 2.72%   |
| 1001-1500   | 5         | 1.36%   |
| 801-900     | 3         | 0.82%   |
| 1501-2000   | 3         | 0.82%   |
| 101-200     | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 240       | 69.57%  |
| 16/10   | 56        | 16.23%  |
| Unknown | 20        | 5.8%    |
| 3/2     | 11        | 3.19%   |
| 21/9    | 10        | 2.9%    |
| 5/4     | 3         | 0.87%   |
| 32/9    | 3         | 0.87%   |
| 4/3     | 2         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 89        | 23.86%  |
| 81-90          | 66        | 17.69%  |
| 201-250        | 54        | 14.48%  |
| 301-350        | 24        | 6.43%   |
| 351-500        | 22        | 5.9%    |
| Unknown        | 21        | 5.63%   |
| 251-300        | 19        | 5.09%   |
| 71-80          | 14        | 3.75%   |
| 111-120        | 14        | 3.75%   |
| 151-200        | 10        | 2.68%   |
| 51-60          | 9         | 2.41%   |
| 501-1000       | 6         | 1.61%   |
| More than 1000 | 5         | 1.34%   |
| 61-70          | 4         | 1.07%   |
| 141-150        | 4         | 1.07%   |
| 41-50          | 3         | 0.8%    |
| 131-140        | 3         | 0.8%    |
| 121-130        | 3         | 0.8%    |
| 91-100         | 2         | 0.54%   |
| 1-40           | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 111       | 30.41%  |
| 51-100        | 102       | 27.95%  |
| 101-120       | 80        | 21.92%  |
| 161-240       | 42        | 11.51%  |
| Unknown       | 21        | 5.75%   |
| More than 240 | 7         | 1.92%   |
| 1-50          | 2         | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 281       | 80.06%  |
| 2     | 57        | 16.24%  |
| 0     | 8         | 2.28%   |
| 3     | 5         | 1.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 198       | 39.29%  |
| Intel                            | 149       | 29.56%  |
| Qualcomm Atheros                 | 35        | 6.94%   |
| Broadcom                         | 26        | 5.16%   |
| MediaTek                         | 21        | 4.17%   |
| TP-Link                          | 8         | 1.59%   |
| Broadcom Limited                 | 8         | 1.59%   |
| Ralink Technology                | 5         | 0.99%   |
| Qualcomm                         | 5         | 0.99%   |
| Ralink                           | 4         | 0.79%   |
| Marvell Technology Group         | 4         | 0.79%   |
| ASIX Electronics                 | 4         | 0.79%   |
| Xiaomi                           | 3         | 0.6%    |
| Sierra Wireless                  | 3         | 0.6%    |
| Qualcomm Atheros Communications  | 3         | 0.6%    |
| Aquantia                         | 3         | 0.6%    |
| Qualcomm Technologies            | 2         | 0.4%    |
| Huawei Technologies              | 2         | 0.4%    |
| Cypress Semiconductor            | 2         | 0.4%    |
| Tenda                            | 1         | 0.2%    |
| STMicroelectronics               | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Raspberry Pi                     | 1         | 0.2%    |
| Pulse-Eight                      | 1         | 0.2%    |
| OPPO Electronics                 | 1         | 0.2%    |
| OnePlus Technology (Shenzhen)    | 1         | 0.2%    |
| OCZ Technology                   | 1         | 0.2%    |
| Nvidia                           | 1         | 0.2%    |
| Microsoft                        | 1         | 0.2%    |
| Microchip Technology             | 1         | 0.2%    |
| Mellanox Technologies            | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| JMicron Technology               | 1         | 0.2%    |
| DisplayLink                      | 1         | 0.2%    |
| Chelsio Communications           | 1         | 0.2%    |
| ASUSTek Computer                 | 1         | 0.2%    |
| Arduino SA                       | 1         | 0.2%    |
| Apple                            | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 126       | 21.36%  |
| Intel Wi-Fi 6 AX200                                                    | 21        | 3.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 19        | 3.22%   |
| Realtek RTL8125 2.5GbE Controller                                      | 16        | 2.71%   |
| Intel Wireless 8265 / 8275                                             | 15        | 2.54%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 12        | 2.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 11        | 1.86%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 1.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 9         | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 1.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 9         | 1.53%   |
| Broadcom BCM43142 802.11b/g/n                                          | 7         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 1.02%   |
| Intel Wireless 7265                                                    | 6         | 1.02%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.85%   |
| Intel Wireless 8260                                                    | 5         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5         | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 4         | 0.68%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 4         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 0.68%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.68%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 4         | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 0.51%   |
| Ralink MT7601U Wireless Adapter                                        | 3         | 0.51%   |
| Intel Wireless 7260                                                    | 3         | 0.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 0.51%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 43.77%  |
| Realtek Semiconductor           | 58        | 20.64%  |
| Qualcomm Atheros                | 29        | 10.32%  |
| MediaTek                        | 20        | 7.12%   |
| Broadcom                        | 16        | 5.69%   |
| TP-Link                         | 6         | 2.14%   |
| Ralink Technology               | 5         | 1.78%   |
| Broadcom Limited                | 5         | 1.78%   |
| Ralink                          | 4         | 1.42%   |
| Qualcomm                        | 4         | 1.42%   |
| Sierra Wireless                 | 3         | 1.07%   |
| Qualcomm Atheros Communications | 3         | 1.07%   |
| Qualcomm Technologies           | 2         | 0.71%   |
| Tenda                           | 1         | 0.36%   |
| Microsoft                       | 1         | 0.36%   |
| ASUSTek Computer                | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 21        | 7.42%   |
| Intel Wireless 8265 / 8275                                           | 15        | 5.3%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 12        | 4.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 11        | 3.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 10        | 3.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 9         | 3.18%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 9         | 3.18%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 8         | 2.83%   |
| Broadcom BCM43142 802.11b/g/n                                        | 7         | 2.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 2.12%   |
| Intel Wireless 7265                                                  | 6         | 2.12%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 2.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 1.77%   |
| Intel Wireless 8260                                                  | 5         | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5         | 1.77%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 4         | 1.41%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 4         | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 1.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 4         | 1.41%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4         | 1.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 4         | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 4         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 4         | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 3         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                      | 3         | 1.06%   |
| Intel Wireless 7260                                                  | 3         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 3         | 1.06%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 3         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 3         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 1.06%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 1.06%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 1.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2         | 0.71%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 2         | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 173       | 58.25%  |
| Intel                            | 69        | 23.23%  |
| Broadcom                         | 12        | 4.04%   |
| Qualcomm Atheros                 | 8         | 2.69%   |
| Marvell Technology Group         | 4         | 1.35%   |
| ASIX Electronics                 | 4         | 1.35%   |
| Xiaomi                           | 3         | 1.01%   |
| Broadcom Limited                 | 3         | 1.01%   |
| Aquantia                         | 3         | 1.01%   |
| TP-Link                          | 2         | 0.67%   |
| Cypress Semiconductor            | 2         | 0.67%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| Raspberry Pi                     | 1         | 0.34%   |
| Qualcomm                         | 1         | 0.34%   |
| OPPO Electronics                 | 1         | 0.34%   |
| Nvidia                           | 1         | 0.34%   |
| Microchip Technology             | 1         | 0.34%   |
| Mellanox Technologies            | 1         | 0.34%   |
| MediaTek                         | 1         | 0.34%   |
| Lenovo                           | 1         | 0.34%   |
| JMicron Technology               | 1         | 0.34%   |
| Huawei Technologies              | 1         | 0.34%   |
| DisplayLink                      | 1         | 0.34%   |
| Chelsio Communications           | 1         | 0.34%   |
| Apple                            | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 126       | 42%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 19        | 6.33%   |
| Realtek RTL8125 2.5GbE Controller                                      | 16        | 5.33%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 3.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.67%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.33%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.67%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.67%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 2         | 0.67%   |
| Intel Ethernet Controller I226-V                                       | 2         | 0.67%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.67%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.67%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.67%   |
| Cypress USB Type-C Dock                                                | 2         | 0.67%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 0.33%   |
| Realtek RTL8126 5GbE Controller                                        | 1         | 0.33%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.33%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.33%   |
| Raspberry Pi RP1 PCIe 2.0 South Bridge                                 | 1         | 0.33%   |
| Qualcomm YUPIK-QRD _SN:AC1D5909                                        | 1         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 275       | 49.73%  |
| WiFi     | 271       | 49.01%  |
| Modem    | 6         | 1.08%   |
| Unknown  | 1         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 214       | 61.32%  |
| Ethernet | 135       | 38.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 175       | 50.58%  |
| 1     | 142       | 41.04%  |
| 3     | 13        | 3.76%   |
| 0     | 13        | 3.76%   |
| 4     | 2         | 0.58%   |
| 8     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 262       | 75.07%  |
| Yes  | 87        | 24.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 105       | 43.39%  |
| Realtek Semiconductor           | 33        | 13.64%  |
| Foxconn / Hon Hai               | 16        | 6.61%   |
| Lite-On Technology              | 14        | 5.79%   |
| IMC Networks                    | 14        | 5.79%   |
| Broadcom                        | 12        | 4.96%   |
| Cambridge Silicon Radio         | 10        | 4.13%   |
| Apple                           | 7         | 2.89%   |
| Qualcomm Atheros Communications | 6         | 2.48%   |
| USI                             | 4         | 1.65%   |
| Realtek                         | 4         | 1.65%   |
| MediaTek                        | 3         | 1.24%   |
| Ralink                          | 2         | 0.83%   |
| ASUSTek Computer                | 2         | 0.83%   |
| TP-Link                         | 1         | 0.41%   |
| Toshiba                         | 1         | 0.41%   |
| Taiyo Yuden                     | 1         | 0.41%   |
| SINO WEALTH                     | 1         | 0.41%   |
| Ralink Technology               | 1         | 0.41%   |
| Opticis                         | 1         | 0.41%   |
| Foxconn International           | 1         | 0.41%   |
| Edimax Technology               | 1         | 0.41%   |
| Dell                            | 1         | 0.41%   |
| Actions                         | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 28        | 11.52%  |
| Realtek Bluetooth Radio                             | 24        | 9.88%   |
| Intel AX200 Bluetooth                               | 21        | 8.64%   |
| Intel AX201 Bluetooth                               | 19        | 7.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 4.53%   |
| Intel Bluetooth Device                              | 10        | 4.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 4.12%   |
| Intel AX210 Bluetooth                               | 9         | 3.7%    |
| IMC Networks Bluetooth Radio                        | 8         | 3.29%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 3.29%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2.47%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 2.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 2.06%   |
| USI Bluetooth Device                                | 4         | 1.65%   |
| Realtek Bluetooth Radio                             | 4         | 1.65%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 1.23%   |
| MediaTek Wireless_Device                            | 3         | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.23%   |
| Lite-On Bluetooth Device                            | 3         | 1.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.23%   |
| IMC Networks Wireless_Device                        | 3         | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.23%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 1.23%   |
| Apple Bluetooth Host Controller                     | 3         | 1.23%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.82%   |
| IMC Networks Bluetooth Device                       | 2         | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.82%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.82%   |
| TP-Link TP-T@- UB500 Adapter                        | 1         | 0.41%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.41%   |
| Taiyo Yuden Bluetooth Device(BC04-External)         | 1         | 0.41%   |
| SINO WEALTH Bluetooth Keyboard                      | 1         | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.41%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.41%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.41%   |
| Ralink CSR BS8510                                   | 1         | 0.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.41%   |
| Opticis Bluetooth Radio                             | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 195       | 40.97%  |
| AMD                                          | 145       | 30.46%  |
| Nvidia                                       | 68        | 14.29%  |
| Logitech                                     | 7         | 1.47%   |
| C-Media Electronics                          | 7         | 1.47%   |
| JMTek                                        | 5         | 1.05%   |
| Focusrite-Novation                           | 3         | 0.63%   |
| Creative Technology                          | 3         | 0.63%   |
| Corsair                                      | 3         | 0.63%   |
| Texas Instruments                            | 2         | 0.42%   |
| SteelSeries ApS                              | 2         | 0.42%   |
| Sony                                         | 2         | 0.42%   |
| Lenovo                                       | 2         | 0.42%   |
| Astro Gaming                                 | 2         | 0.42%   |
| ASRock                                       | 2         | 0.42%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.21%   |
| VIA Technologies                             | 1         | 0.21%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.21%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.21%   |
| SAVITECH                                     | 1         | 0.21%   |
| Samson Technologies                          | 1         | 0.21%   |
| Razer USA                                    | 1         | 0.21%   |
| Mark of the Unicorn                          | 1         | 0.21%   |
| M-Audio                                      | 1         | 0.21%   |
| Logic3                                       | 1         | 0.21%   |
| liyuany                                      | 1         | 0.21%   |
| KTMicro                                      | 1         | 0.21%   |
| Kingston Technology                          | 1         | 0.21%   |
| GN Netcom                                    | 1         | 0.21%   |
| Giga-Byte Technology                         | 1         | 0.21%   |
| Fujitsu                                      | 1         | 0.21%   |
| Fry's Electronics                            | 1         | 0.21%   |
| FiiO Electronics Technology                  | 1         | 0.21%   |
| ESS Technology                               | 1         | 0.21%   |
| Elgato Systems                               | 1         | 0.21%   |
| EDFIER                                       | 1         | 0.21%   |
| Creative Labs                                | 1         | 0.21%   |
| Cambridge Silicon Radio                      | 1         | 0.21%   |
| Cambridge Audio                              | 1         | 0.21%   |
| Blue Microphones                             | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 65        | 10.47%  |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 36        | 5.8%    |
| AMD Starship/Matisse HD Audio Controller                                   | 25        | 4.03%   |
| Intel Sunrise Point-LP HD Audio                                            | 23        | 3.7%    |
| AMD Radeon High Definition Audio Controller                                | 21        | 3.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 2.09%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 2.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 1.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 12        | 1.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12        | 1.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 1.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.45%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 1.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 1.29%   |
| Intel 200 Series PCH HD Audio                                              | 8         | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 1.29%   |
| AMD FCH Azalia Controller                                                  | 8         | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 1.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 7         | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6         | 0.97%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 6         | 0.97%   |
| AMD Navi 10 HDMI Audio                                                     | 6         | 0.97%   |
| AMD High Definition Audio Controller                                       | 6         | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 0.81%   |
| JMTek USB PnP Audio Device                                                 | 5         | 0.81%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 5         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 22.58%  |
| SK hynix            | 56        | 20.07%  |
| Micron Technology   | 34        | 12.19%  |
| Kingston            | 26        | 9.32%   |
| Unknown             | 18        | 6.45%   |
| Corsair             | 18        | 6.45%   |
| G.Skill             | 15        | 5.38%   |
| Crucial             | 12        | 4.3%    |
| A-DATA Technology   | 8         | 2.87%   |
| Ramaxel Technology  | 4         | 1.43%   |
| Team                | 3         | 1.08%   |
| Nanya Technology    | 3         | 1.08%   |
| Transcend           | 2         | 0.72%   |
| Unknown             | 2         | 0.72%   |
| Wodposit            | 1         | 0.36%   |
| Unknown (ABCD)      | 1         | 0.36%   |
| Unknown (0x0CC7)    | 1         | 0.36%   |
| Timetec             | 1         | 0.36%   |
| Smart               | 1         | 0.36%   |
| Patriot Memory      | 1         | 0.36%   |
| Patriot             | 1         | 0.36%   |
| Neo Forza           | 1         | 0.36%   |
| Kingmax             | 1         | 0.36%   |
| HT Micron           | 1         | 0.36%   |
| Elpida              | 1         | 0.36%   |
| Avant               | 1         | 0.36%   |
| 4ea5                | 1         | 0.36%   |
| 48spaces            | 1         | 0.36%   |
| 3034CB0010CA        | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.99%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.66%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.32%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.99%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.99%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 3         | 0.99%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3600MT/s           | 3         | 0.99%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.66%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 2         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 2         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.66%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 0.66%   |
| Micron RAM MTC4C10163S1SC56BD1 8GB SODIMM DDR5 5600MT/s          | 2         | 0.66%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s       | 2         | 0.66%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.66%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 2         | 0.66%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s          | 2         | 0.66%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.66%   |
| Unknown                                                          | 2         | 0.66%   |
| Wodposit RAM WPBH32D408SWD-8G 8GB SODIMM DDR4 3200MT/s           | 1         | 0.33%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.33%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.33%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 117       | 48.35%  |
| DDR3    | 66        | 27.27%  |
| DDR5    | 16        | 6.61%   |
| LPDDR5  | 12        | 4.96%   |
| DDR2    | 9         | 3.72%   |
| LPDDR3  | 7         | 2.89%   |
| LPDDR4  | 6         | 2.48%   |
| SDRAM   | 5         | 2.07%   |
| Unknown | 3         | 1.24%   |
| DDR     | 1         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 145       | 59.18%  |
| DIMM         | 70        | 28.57%  |
| Row Of Chips | 29        | 11.84%  |
| Unknown      | 1         | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 116       | 43.28%  |
| 4096  | 64        | 23.88%  |
| 16384 | 45        | 16.79%  |
| 2048  | 20        | 7.46%   |
| 32768 | 8         | 2.99%   |
| 1024  | 8         | 2.99%   |
| 512   | 4         | 1.49%   |
| 65536 | 1         | 0.37%   |
| 24576 | 1         | 0.37%   |
| 12288 | 1         | 0.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 49        | 18.56%  |
| 1600    | 45        | 17.05%  |
| 2667    | 33        | 12.5%   |
| 3600    | 16        | 6.06%   |
| 2400    | 14        | 5.3%    |
| 1333    | 14        | 5.3%    |
| 2133    | 9         | 3.41%   |
| 5600    | 8         | 3.03%   |
| 6400    | 7         | 2.65%   |
| 1334    | 7         | 2.65%   |
| 667     | 7         | 2.65%   |
| 4800    | 6         | 2.27%   |
| 8400    | 5         | 1.89%   |
| Unknown | 5         | 1.89%   |
| 7500    | 4         | 1.52%   |
| 1867    | 4         | 1.52%   |
| 3733    | 3         | 1.14%   |
| 533     | 3         | 1.14%   |
| 3866    | 2         | 0.76%   |
| 1866    | 2         | 0.76%   |
| 8600    | 1         | 0.38%   |
| 8200    | 1         | 0.38%   |
| 6000    | 1         | 0.38%   |
| 5000    | 1         | 0.38%   |
| 4267    | 1         | 0.38%   |
| 4266    | 1         | 0.38%   |
| 4199    | 1         | 0.38%   |
| 4000    | 1         | 0.38%   |
| 3800    | 1         | 0.38%   |
| 3466    | 1         | 0.38%   |
| 3333    | 1         | 0.38%   |
| 3266    | 1         | 0.38%   |
| 3100    | 1         | 0.38%   |
| 3000    | 1         | 0.38%   |
| 2800    | 1         | 0.38%   |
| 2666    | 1         | 0.38%   |
| 1800    | 1         | 0.38%   |
| 1648    | 1         | 0.38%   |
| 1067    | 1         | 0.38%   |
| 1066    | 1         | 0.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 61        | 27.6%   |
| Bison Electronics                      | 25        | 11.31%  |
| Microdia                               | 21        | 9.5%    |
| IMC Networks                           | 20        | 9.05%   |
| Quanta                                 | 12        | 5.43%   |
| Realtek Semiconductor                  | 11        | 4.98%   |
| Logitech                               | 11        | 4.98%   |
| Luxvisions Innotech Limited            | 8         | 3.62%   |
| Syntek                                 | 7         | 3.17%   |
| Sunplus Innovation Technology          | 7         | 3.17%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.17%   |
| Sonix Technology                       | 4         | 1.81%   |
| Suyin                                  | 3         | 1.36%   |
| Apple                                  | 3         | 1.36%   |
| Alcor Micro                            | 3         | 1.36%   |
| MacroSilicon                           | 2         | 0.9%    |
| Unknown                                | 2         | 0.9%    |
| WaveRider Communications               | 1         | 0.45%   |
| SunplusIT                              | 1         | 0.45%   |
| Silicon Motion                         | 1         | 0.45%   |
| Shinetech                              | 1         | 0.45%   |
| Shine-optics                           | 1         | 0.45%   |
| Samsung Electronics                    | 1         | 0.45%   |
| Microsoft                              | 1         | 0.45%   |
| Lite-On Technology                     | 1         | 0.45%   |
| Intel                                  | 1         | 0.45%   |
| Hewlett-Packard                        | 1         | 0.45%   |
| GEMBIRD                                | 1         | 0.45%   |
| Asuscom Network                        | 1         | 0.45%   |
| ALi                                    | 1         | 0.45%   |
| Alcorlink                              | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 21        | 9.33%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 8         | 3.56%   |
| Microdia Integrated_Webcam_HD                     | 6         | 2.67%   |
| Bison Integrated Camera                           | 6         | 2.67%   |
| Syntek Integrated Camera                          | 5         | 2.22%   |
| Realtek USB Camera                                | 5         | 2.22%   |
| Bison Integrated RGB Camera                       | 5         | 2.22%   |
| Quanta HD User Facing                             | 4         | 1.78%   |
| Logitech Webcam C270                              | 4         | 1.78%   |
| Chicony HP TrueVision HD Camera                   | 4         | 1.78%   |
| Chicony HD WebCam                                 | 4         | 1.78%   |
| Suyin HP Truevision HD                            | 3         | 1.33%   |
| Microdia USB 2.0 Camera                           | 3         | 1.33%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 3         | 1.33%   |
| Luxvisions Innotech Limited Integrated Camera     | 3         | 1.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 3         | 1.33%   |
| IMC Networks Integrated Camera                    | 3         | 1.33%   |
| Chicony USB2.0 VGA UVC WebCam                     | 3         | 1.33%   |
| Chicony USB 2.0 Camera                            | 3         | 1.33%   |
| Chicony Integrated Camera (1280x720@30)           | 3         | 1.33%   |
| Chicony HD WebCam (Acer)                          | 3         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam     | 3         | 1.33%   |
| Bison SunplusIT Integrated Camera                 | 3         | 1.33%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 0.89%   |
| Sonix USB2.0 HD UVC WebCam                        | 2         | 0.89%   |
| Quanta HP Webcam                                  | 2         | 0.89%   |
| Microdia Webcam Vitade AF                         | 2         | 0.89%   |
| Microdia HP Integrated Webcam                     | 2         | 0.89%   |
| Microdia HDE Webcam USB                           | 2         | 0.89%   |
| Microdia Camera                                   | 2         | 0.89%   |
| Logitech HD Webcam C615                           | 2         | 0.89%   |
| IMC Networks HD Camera                            | 2         | 0.89%   |
| Chicony USB2.0 Camera                             | 2         | 0.89%   |
| Chicony ThinkPad T490 Webcam                      | 2         | 0.89%   |
| Chicony Lenovo EasyCamera                         | 2         | 0.89%   |
| Chicony HP Wide Vision HD Camera                  | 2         | 0.89%   |
| Chicony HP 720p HD Monitor Webcam                 | 2         | 0.89%   |
| Chicony HD User Facing                            | 2         | 0.89%   |
| Chicony EasyCamera                                | 2         | 0.89%   |
| Bison Lenovo EasyCamera                           | 2         | 0.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 22        | 51.16%  |
| Validity Sensors           | 6         | 13.95%  |
| Shenzhen Goodix Technology | 6         | 13.95%  |
| Upek                       | 4         | 9.3%    |
| Elan Microelectronics      | 3         | 6.98%   |
| HOLTEK                     | 1         | 2.33%   |
| Focal-systems.Corp         | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 8         | 18.6%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 5         | 11.63%  |
| Shenzhen Goodix  FingerPrint Device                    | 5         | 11.63%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 9.3%    |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 6.98%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 4.65%   |
| Synaptics UWP WBDI Device                              | 2         | 4.65%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 4.65%   |
| Elan ELAN:Fingerprint                                  | 2         | 4.65%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 2.33%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 2.33%   |
| Synaptics WBDI                                         | 1         | 2.33%   |
| Synaptics  WBDI                                        | 1         | 2.33%   |
| Synaptics Prometheus Fingerprint Reader                | 1         | 2.33%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 2.33%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 2.33%   |
| HOLTEK FocalTech Fingerprint Device                    | 1         | 2.33%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 2.33%   |
| Elan ELAN:ARM-M4                                       | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 9         | 56.25%  |
| Lenovo      | 4         | 25%     |
| Broadcom    | 3         | 18.75%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                         | 9         | 56.25%  |
| Lenovo Integrated Smart Card Reader                                         | 4         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                              | 1         | 6.25%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 1         | 6.25%   |
| Broadcom 58200                                                              | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 255       | 73.49%  |
| 1     | 70        | 20.17%  |
| 2     | 18        | 5.19%   |
| 3     | 4         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 37.39%  |
| Graphics card            | 17        | 14.78%  |
| Chipcard                 | 15        | 13.04%  |
| Net/wireless             | 10        | 8.7%    |
| Multimedia controller    | 9         | 7.83%   |
| Camera                   | 5         | 4.35%   |
| Sound                    | 4         | 3.48%   |
| Communication controller | 4         | 3.48%   |
| Card reader              | 3         | 2.61%   |
| Bluetooth                | 2         | 1.74%   |
| Unassigned class         | 1         | 0.87%   |
| Storage/raid             | 1         | 0.87%   |
| Net/ethernet             | 1         | 0.87%   |


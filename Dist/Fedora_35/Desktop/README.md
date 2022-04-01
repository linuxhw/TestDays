Fedora 35 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 575

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B460M D3H                   | [7c159eefd8](https://linux-hardware.org/?probe=7c159eefd8) | Apr 01, 2022 |
| ASUSTek       | B85M-E                      | [b81a77ca49](https://linux-hardware.org/?probe=b81a77ca49) | Apr 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d0f35d0a4](https://linux-hardware.org/?probe=8d0f35d0a4) | Apr 01, 2022 |
| MSI           | B85-G43 GAMING              | [70574c396b](https://linux-hardware.org/?probe=70574c396b) | Mar 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b08e7d8589](https://linux-hardware.org/?probe=b08e7d8589) | Mar 31, 2022 |
| ASRock        | H510M-HVS R2.0              | [a4ad860e3d](https://linux-hardware.org/?probe=a4ad860e3d) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| ASUSTek       | M5A97 EVO                   | [96cd3f3a03](https://linux-hardware.org/?probe=96cd3f3a03) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [a9cf0523c2](https://linux-hardware.org/?probe=a9cf0523c2) | Mar 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4146e027d3](https://linux-hardware.org/?probe=4146e027d3) | Mar 31, 2022 |
| Gigabyte      | H77N-WIFI                   | [cc57bcd7a9](https://linux-hardware.org/?probe=cc57bcd7a9) | Mar 31, 2022 |
| Gigabyte      | M68MT-S2P                   | [c2daebfd60](https://linux-hardware.org/?probe=c2daebfd60) | Mar 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [3cd8bdb60c](https://linux-hardware.org/?probe=3cd8bdb60c) | Mar 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [e205dc3177](https://linux-hardware.org/?probe=e205dc3177) | Mar 30, 2022 |
| Gigabyte      | X99-UD4-CF                  | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d8c91051f3](https://linux-hardware.org/?probe=d8c91051f3) | Mar 30, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [2491111c9d](https://linux-hardware.org/?probe=2491111c9d) | Mar 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cfaa52d13e](https://linux-hardware.org/?probe=cfaa52d13e) | Mar 29, 2022 |
| Gateway       | SX2185                      | [3d1d72a3c1](https://linux-hardware.org/?probe=3d1d72a3c1) | Mar 28, 2022 |
| HP            | 82A2                        | [5736762c06](https://linux-hardware.org/?probe=5736762c06) | Mar 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9464f8c81e](https://linux-hardware.org/?probe=9464f8c81e) | Mar 28, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e4c1632bc2](https://linux-hardware.org/?probe=e4c1632bc2) | Mar 28, 2022 |
| ASUSTek       | P5Q-PRO                     | [c5d26f3dc7](https://linux-hardware.org/?probe=c5d26f3dc7) | Mar 27, 2022 |
| ASUSTek       | P5Q-PRO                     | [53da8c0cdf](https://linux-hardware.org/?probe=53da8c0cdf) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | [51c0f63296](https://linux-hardware.org/?probe=51c0f63296) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | [9c0577803f](https://linux-hardware.org/?probe=9c0577803f) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | [a296d4597c](https://linux-hardware.org/?probe=a296d4597c) | Mar 27, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [e04592bee1](https://linux-hardware.org/?probe=e04592bee1) | Mar 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | [26a2540713](https://linux-hardware.org/?probe=26a2540713) | Mar 27, 2022 |
| Dell          | 0M6C7G A00                  | [d214df0c57](https://linux-hardware.org/?probe=d214df0c57) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [8252c302e2](https://linux-hardware.org/?probe=8252c302e2) | Mar 27, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [ce82ab584b](https://linux-hardware.org/?probe=ce82ab584b) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | [91b7f328b1](https://linux-hardware.org/?probe=91b7f328b1) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | [48ce1c3bd8](https://linux-hardware.org/?probe=48ce1c3bd8) | Mar 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [029e0a790e](https://linux-hardware.org/?probe=029e0a790e) | Mar 26, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [d1b78f5eb8](https://linux-hardware.org/?probe=d1b78f5eb8) | Mar 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [e1ce096233](https://linux-hardware.org/?probe=e1ce096233) | Mar 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b2d35dc269](https://linux-hardware.org/?probe=b2d35dc269) | Mar 26, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [c8acfed97a](https://linux-hardware.org/?probe=c8acfed97a) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [a68ce8edaf](https://linux-hardware.org/?probe=a68ce8edaf) | Mar 26, 2022 |
| ASUSTek       | P8H61-MX USB3               | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [90299bc344](https://linux-hardware.org/?probe=90299bc344) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [50335ac3a2](https://linux-hardware.org/?probe=50335ac3a2) | Mar 25, 2022 |
| ASRock        | G41M-VS3                    | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2424807acb](https://linux-hardware.org/?probe=2424807acb) | Mar 24, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [d6d6620190](https://linux-hardware.org/?probe=d6d6620190) | Mar 24, 2022 |
| BESSTAR Te... | UM700                       | [b1ff998755](https://linux-hardware.org/?probe=b1ff998755) | Mar 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25d5cba9dc](https://linux-hardware.org/?probe=25d5cba9dc) | Mar 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c10b664e4e](https://linux-hardware.org/?probe=c10b664e4e) | Mar 24, 2022 |
| Intel         | DH61BE AAG14062-206         | [08a352b1d2](https://linux-hardware.org/?probe=08a352b1d2) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6136cfa920](https://linux-hardware.org/?probe=6136cfa920) | Mar 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d74979a970](https://linux-hardware.org/?probe=d74979a970) | Mar 24, 2022 |
| Dell          | 08HPGT A01                  | [440e4d8b48](https://linux-hardware.org/?probe=440e4d8b48) | Mar 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e75d387eea](https://linux-hardware.org/?probe=e75d387eea) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [86c831ce79](https://linux-hardware.org/?probe=86c831ce79) | Mar 23, 2022 |
| Gigabyte      | G1.Sniper Z97               | [3024cce066](https://linux-hardware.org/?probe=3024cce066) | Mar 23, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [ddf8fb6916](https://linux-hardware.org/?probe=ddf8fb6916) | Mar 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [6239582d24](https://linux-hardware.org/?probe=6239582d24) | Mar 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bea334f9c7](https://linux-hardware.org/?probe=bea334f9c7) | Mar 22, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [188fb139c3](https://linux-hardware.org/?probe=188fb139c3) | Mar 21, 2022 |
| ABIT          | IP35-E                      | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| ABIT          | IP35-E                      | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| MSI           | A320M BAZOOKA               | [0c12287476](https://linux-hardware.org/?probe=0c12287476) | Mar 21, 2022 |
| MACHINIST     | X99-G7 V1.0                 | [70a784f09c](https://linux-hardware.org/?probe=70a784f09c) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | [c294e20164](https://linux-hardware.org/?probe=c294e20164) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | [5b9b7903ad](https://linux-hardware.org/?probe=5b9b7903ad) | Mar 21, 2022 |
| ASRock        | Z270 Extreme4               | [0f3a8eb166](https://linux-hardware.org/?probe=0f3a8eb166) | Mar 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [621ad4beae](https://linux-hardware.org/?probe=621ad4beae) | Mar 21, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [279bb03666](https://linux-hardware.org/?probe=279bb03666) | Mar 21, 2022 |
| ASUSTek       | PRIME Z370-P                | [a5937e694a](https://linux-hardware.org/?probe=a5937e694a) | Mar 20, 2022 |
| Gigabyte      | H77N-WIFI                   | [536bac0d6a](https://linux-hardware.org/?probe=536bac0d6a) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| MSI           | B550-A PRO                  | [2f713e8db8](https://linux-hardware.org/?probe=2f713e8db8) | Mar 19, 2022 |
| MACHINIST     | X99-G7 V1.0                 | [ebc42c3206](https://linux-hardware.org/?probe=ebc42c3206) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | [b4a188ad90](https://linux-hardware.org/?probe=b4a188ad90) | Mar 19, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [5415b5f876](https://linux-hardware.org/?probe=5415b5f876) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [dc3b3ab391](https://linux-hardware.org/?probe=dc3b3ab391) | Mar 18, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [6f4835e78d](https://linux-hardware.org/?probe=6f4835e78d) | Mar 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [b928348a02](https://linux-hardware.org/?probe=b928348a02) | Mar 17, 2022 |
| ASRock        | B550 Steel Legend           | [c6b6cc1f1d](https://linux-hardware.org/?probe=c6b6cc1f1d) | Mar 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a3444ce232](https://linux-hardware.org/?probe=a3444ce232) | Mar 16, 2022 |
| Gigabyte      | H61M-USB3V                  | [d5afbde22c](https://linux-hardware.org/?probe=d5afbde22c) | Mar 16, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [b0d9828f83](https://linux-hardware.org/?probe=b0d9828f83) | Mar 16, 2022 |
| ASUSTek       | PRIME B450M-A               | [75a7099e71](https://linux-hardware.org/?probe=75a7099e71) | Mar 15, 2022 |
| ASRock        | H470M-HDV                   | [72a6f7ef1b](https://linux-hardware.org/?probe=72a6f7ef1b) | Mar 13, 2022 |
| Dell          | 08HPGT A02                  | [79211f85fd](https://linux-hardware.org/?probe=79211f85fd) | Mar 13, 2022 |
| MSI           | B85M-E45 2015-08-19         | [90f5d4247e](https://linux-hardware.org/?probe=90f5d4247e) | Mar 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [d5d90a423a](https://linux-hardware.org/?probe=d5d90a423a) | Mar 13, 2022 |
| MSI           | 2A9C                        | [99c139f47b](https://linux-hardware.org/?probe=99c139f47b) | Mar 12, 2022 |
| MSI           | X570-A PRO                  | [2bb86501da](https://linux-hardware.org/?probe=2bb86501da) | Mar 12, 2022 |
| ASUSTek       | P8Z77-V LK                  | [21c958ad5f](https://linux-hardware.org/?probe=21c958ad5f) | Mar 12, 2022 |
| HP            | 8767 A                      | [6eca88e86f](https://linux-hardware.org/?probe=6eca88e86f) | Mar 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8a8cc84461](https://linux-hardware.org/?probe=8a8cc84461) | Mar 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4c71606b0a](https://linux-hardware.org/?probe=4c71606b0a) | Mar 11, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [889e5fe7a3](https://linux-hardware.org/?probe=889e5fe7a3) | Mar 11, 2022 |
| ASUSTek       | PRIME Z390-A                | [dc38e0d85a](https://linux-hardware.org/?probe=dc38e0d85a) | Mar 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c4d9b11074](https://linux-hardware.org/?probe=c4d9b11074) | Mar 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e4596496cf](https://linux-hardware.org/?probe=e4596496cf) | Mar 10, 2022 |
| MSI           | 2A9C                        | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| MSI           | 2A9C                        | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5aef9f7ccf](https://linux-hardware.org/?probe=5aef9f7ccf) | Mar 09, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [9be6d8c4aa](https://linux-hardware.org/?probe=9be6d8c4aa) | Mar 08, 2022 |
| Gigabyte      | H410M H                     | [13a9aa4fb3](https://linux-hardware.org/?probe=13a9aa4fb3) | Mar 08, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c935c59d99](https://linux-hardware.org/?probe=c935c59d99) | Mar 08, 2022 |
| Gigabyte      | Z68XP-UD3                   | [5fb0149650](https://linux-hardware.org/?probe=5fb0149650) | Mar 08, 2022 |
| ASUSTek       | PRIME X370-A                | [cec3d7b058](https://linux-hardware.org/?probe=cec3d7b058) | Mar 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd9567c6ce](https://linux-hardware.org/?probe=bd9567c6ce) | Mar 08, 2022 |
| Gigabyte      | H77N-WIFI                   | [3b750cbc3f](https://linux-hardware.org/?probe=3b750cbc3f) | Mar 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [ec3824b685](https://linux-hardware.org/?probe=ec3824b685) | Mar 07, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ae9c8e47e2](https://linux-hardware.org/?probe=ae9c8e47e2) | Mar 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [49d6176e9e](https://linux-hardware.org/?probe=49d6176e9e) | Mar 07, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f0a65362c5](https://linux-hardware.org/?probe=f0a65362c5) | Mar 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [a544689bd5](https://linux-hardware.org/?probe=a544689bd5) | Mar 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [94584a9a48](https://linux-hardware.org/?probe=94584a9a48) | Mar 06, 2022 |
| Dell          | 0KWVT8 A03                  | [e29f709958](https://linux-hardware.org/?probe=e29f709958) | Mar 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [91bb2e28fe](https://linux-hardware.org/?probe=91bb2e28fe) | Mar 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [7cea2ed288](https://linux-hardware.org/?probe=7cea2ed288) | Mar 05, 2022 |
| Dell          | 0WR7PY A00                  | [19895058a5](https://linux-hardware.org/?probe=19895058a5) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [55d8863b7b](https://linux-hardware.org/?probe=55d8863b7b) | Mar 05, 2022 |
| Dell          | 01TN68 A01                  | [f57cafd9b1](https://linux-hardware.org/?probe=f57cafd9b1) | Mar 03, 2022 |
| Dell          | 01TN68 A01                  | [a93c073676](https://linux-hardware.org/?probe=a93c073676) | Mar 03, 2022 |
| ASRock        | FM2A88X Extreme6+           | [81e8102a40](https://linux-hardware.org/?probe=81e8102a40) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d2e96e523e](https://linux-hardware.org/?probe=d2e96e523e) | Mar 03, 2022 |
| Acer          | Veriton X6620G v1.0         | [01922bdee0](https://linux-hardware.org/?probe=01922bdee0) | Mar 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [eb61ea7985](https://linux-hardware.org/?probe=eb61ea7985) | Mar 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d40f3513ef](https://linux-hardware.org/?probe=d40f3513ef) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7af526bbb7](https://linux-hardware.org/?probe=7af526bbb7) | Mar 01, 2022 |
| HP            | 212B                        | [c183489268](https://linux-hardware.org/?probe=c183489268) | Mar 01, 2022 |
| Dell          | 0M5DCD A00                  | [884adfefd3](https://linux-hardware.org/?probe=884adfefd3) | Mar 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9d178352ca](https://linux-hardware.org/?probe=9d178352ca) | Mar 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [8a51a8730b](https://linux-hardware.org/?probe=8a51a8730b) | Feb 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ffbae7cdf3](https://linux-hardware.org/?probe=ffbae7cdf3) | Feb 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78cc2173d9](https://linux-hardware.org/?probe=78cc2173d9) | Feb 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | [930b650263](https://linux-hardware.org/?probe=930b650263) | Feb 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9cdd0eea43](https://linux-hardware.org/?probe=9cdd0eea43) | Feb 26, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [03f2fa46f2](https://linux-hardware.org/?probe=03f2fa46f2) | Feb 26, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f0692aebbe](https://linux-hardware.org/?probe=f0692aebbe) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | [d8dec986e8](https://linux-hardware.org/?probe=d8dec986e8) | Feb 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [eaa8067586](https://linux-hardware.org/?probe=eaa8067586) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | [7b58208c52](https://linux-hardware.org/?probe=7b58208c52) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | [03a5ed6072](https://linux-hardware.org/?probe=03a5ed6072) | Feb 24, 2022 |
| MSI           | B350 TOMAHAWK               | [e1ddcb9f9a](https://linux-hardware.org/?probe=e1ddcb9f9a) | Feb 24, 2022 |
| Gigabyte      | B450 AORUS M                | [b94d0c6e20](https://linux-hardware.org/?probe=b94d0c6e20) | Feb 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [eb017e14fa](https://linux-hardware.org/?probe=eb017e14fa) | Feb 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88734fe9a0](https://linux-hardware.org/?probe=88734fe9a0) | Feb 23, 2022 |
| MSI           | B550-A PRO                  | [9d3f01a706](https://linux-hardware.org/?probe=9d3f01a706) | Feb 23, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [228e9e9d0c](https://linux-hardware.org/?probe=228e9e9d0c) | Feb 23, 2022 |
| Lenovo        | 30D2 NOK                    | [108296cf9b](https://linux-hardware.org/?probe=108296cf9b) | Feb 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d32c812d2b](https://linux-hardware.org/?probe=d32c812d2b) | Feb 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0d69aa634e](https://linux-hardware.org/?probe=0d69aa634e) | Feb 22, 2022 |
| ASRock        | B450M Pro4                  | [5825d4fcaf](https://linux-hardware.org/?probe=5825d4fcaf) | Feb 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [67deab7343](https://linux-hardware.org/?probe=67deab7343) | Feb 22, 2022 |
| ASUSTek       | P5QL                        | [2714d59901](https://linux-hardware.org/?probe=2714d59901) | Feb 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | [6c4ff21b02](https://linux-hardware.org/?probe=6c4ff21b02) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8223731dc](https://linux-hardware.org/?probe=c8223731dc) | Feb 21, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [ebca133032](https://linux-hardware.org/?probe=ebca133032) | Feb 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | [558ef9e9d4](https://linux-hardware.org/?probe=558ef9e9d4) | Feb 20, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [eccaa1c72e](https://linux-hardware.org/?probe=eccaa1c72e) | Feb 19, 2022 |
| Gateway       | DX4860                      | [d28784e189](https://linux-hardware.org/?probe=d28784e189) | Feb 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [3d816cc71a](https://linux-hardware.org/?probe=3d816cc71a) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b2c662bad6](https://linux-hardware.org/?probe=b2c662bad6) | Feb 18, 2022 |
| Gigabyte      | F2A68HM-S1                  | [83e6228c44](https://linux-hardware.org/?probe=83e6228c44) | Feb 17, 2022 |
| MSI           | A520M-A PRO                 | [dbe8ddd097](https://linux-hardware.org/?probe=dbe8ddd097) | Feb 17, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [f2d47f2d8b](https://linux-hardware.org/?probe=f2d47f2d8b) | Feb 17, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [a74d65bfe6](https://linux-hardware.org/?probe=a74d65bfe6) | Feb 16, 2022 |
| HP            | 82A2                        | [5efad9b732](https://linux-hardware.org/?probe=5efad9b732) | Feb 16, 2022 |
| MSI           | B450-A PRO MAX              | [538072f18d](https://linux-hardware.org/?probe=538072f18d) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e3eee22fef](https://linux-hardware.org/?probe=e3eee22fef) | Feb 16, 2022 |
| Dell          | 08HPGT A02                  | [a6c76eb5f6](https://linux-hardware.org/?probe=a6c76eb5f6) | Feb 15, 2022 |
| Dell          | 08HPGT A02                  | [6d024608a5](https://linux-hardware.org/?probe=6d024608a5) | Feb 15, 2022 |
| MSI           | B450M MORTAR MAX            | [68f6b7dd88](https://linux-hardware.org/?probe=68f6b7dd88) | Feb 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [890fea8813](https://linux-hardware.org/?probe=890fea8813) | Feb 15, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [a82c9b223f](https://linux-hardware.org/?probe=a82c9b223f) | Feb 14, 2022 |
| MSI           | B450-A PRO MAX              | [4c61db4a18](https://linux-hardware.org/?probe=4c61db4a18) | Feb 13, 2022 |
| ECS           | A58F2P-M4                   | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [84005ca8f9](https://linux-hardware.org/?probe=84005ca8f9) | Feb 12, 2022 |
| Biostar       | AM1ML                       | [54e50bd790](https://linux-hardware.org/?probe=54e50bd790) | Feb 12, 2022 |
| Biostar       | AM1ML                       | [e933dbc718](https://linux-hardware.org/?probe=e933dbc718) | Feb 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [359fac7afc](https://linux-hardware.org/?probe=359fac7afc) | Feb 12, 2022 |
| Gigabyte      | B550 GAMING X V2            | [60ee5faa6c](https://linux-hardware.org/?probe=60ee5faa6c) | Feb 10, 2022 |
| Gigabyte      | G41MT-D3                    | [ac4b2855c6](https://linux-hardware.org/?probe=ac4b2855c6) | Feb 10, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [1b903af2df](https://linux-hardware.org/?probe=1b903af2df) | Feb 10, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [87d3fd2916](https://linux-hardware.org/?probe=87d3fd2916) | Feb 09, 2022 |
| ASRock        | Z87 Pro3                    | [dea0b07f08](https://linux-hardware.org/?probe=dea0b07f08) | Feb 08, 2022 |
| ASUSTek       | TUF GAMING Z690-PLUS WIF... | [ab81e91207](https://linux-hardware.org/?probe=ab81e91207) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [29ca9095c4](https://linux-hardware.org/?probe=29ca9095c4) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-K               | [24a7621237](https://linux-hardware.org/?probe=24a7621237) | Feb 08, 2022 |
| Gigabyte      | EP45-DS3L                   | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| ASRock        | X570 Taichi                 | [e7b3bb2161](https://linux-hardware.org/?probe=e7b3bb2161) | Feb 07, 2022 |
| ASRock        | X570 Taichi                 | [97a6c42f5f](https://linux-hardware.org/?probe=97a6c42f5f) | Feb 07, 2022 |
| Gigabyte      | H310M M.2 x.x               | [824af874a4](https://linux-hardware.org/?probe=824af874a4) | Feb 06, 2022 |
| ASRock        | B560M Steel Legend          | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| MSI           | B450-A PRO MAX              | [830c0232b6](https://linux-hardware.org/?probe=830c0232b6) | Feb 06, 2022 |
| MSI           | Z77A-GD65 GAMING            | [8d2cf11a20](https://linux-hardware.org/?probe=8d2cf11a20) | Feb 06, 2022 |
| Dell          | 0200DY A00                  | [5714dfdd29](https://linux-hardware.org/?probe=5714dfdd29) | Feb 06, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Supermicro    | X9DRW                       | [432d4db3ea](https://linux-hardware.org/?probe=432d4db3ea) | Feb 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [63a70836f3](https://linux-hardware.org/?probe=63a70836f3) | Feb 05, 2022 |
| Gigabyte      | D525TUD                     | [08962dc9f9](https://linux-hardware.org/?probe=08962dc9f9) | Feb 05, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [cd81e5ce82](https://linux-hardware.org/?probe=cd81e5ce82) | Feb 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [cab5335d99](https://linux-hardware.org/?probe=cab5335d99) | Feb 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [548f756c0e](https://linux-hardware.org/?probe=548f756c0e) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [e799f33b3f](https://linux-hardware.org/?probe=e799f33b3f) | Feb 04, 2022 |
| ASUSTek       | H97M-E                      | [f10bee8b8f](https://linux-hardware.org/?probe=f10bee8b8f) | Feb 04, 2022 |
| ASUSTek       | PRIME B250M-A               | [9a45aba28e](https://linux-hardware.org/?probe=9a45aba28e) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [4df88dcf23](https://linux-hardware.org/?probe=4df88dcf23) | Feb 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [9da6b947f5](https://linux-hardware.org/?probe=9da6b947f5) | Feb 03, 2022 |
| Gigabyte      | D525TUD                     | [83678f76fc](https://linux-hardware.org/?probe=83678f76fc) | Feb 03, 2022 |
| ASUSTek       | H97M-E                      | [f37fe196d0](https://linux-hardware.org/?probe=f37fe196d0) | Feb 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [104c871438](https://linux-hardware.org/?probe=104c871438) | Feb 03, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [dca1097e4a](https://linux-hardware.org/?probe=dca1097e4a) | Feb 02, 2022 |
| Dell          | 0X4H68 A00                  | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [813bec5fe7](https://linux-hardware.org/?probe=813bec5fe7) | Feb 02, 2022 |
| ASUSTek       | PRIME Z270-P                | [26a4917db5](https://linux-hardware.org/?probe=26a4917db5) | Feb 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7ea870fff3](https://linux-hardware.org/?probe=7ea870fff3) | Feb 02, 2022 |
| ASRock        | A320M-HD R4.0               | [f2dfa50076](https://linux-hardware.org/?probe=f2dfa50076) | Feb 02, 2022 |
| ASUSTek       | P8Z77-V LK                  | [a6321e237c](https://linux-hardware.org/?probe=a6321e237c) | Feb 01, 2022 |
| ASUSTek       | PRIME B360M-A               | [c60e8a85c4](https://linux-hardware.org/?probe=c60e8a85c4) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [fb9c5fac50](https://linux-hardware.org/?probe=fb9c5fac50) | Feb 01, 2022 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [9ba4b1306f](https://linux-hardware.org/?probe=9ba4b1306f) | Jan 31, 2022 |
| ASUSTek       | H97M-E                      | [d8cbfade46](https://linux-hardware.org/?probe=d8cbfade46) | Jan 31, 2022 |
| MSI           | X99A GAMING PRO CARBON      | [49bd28cbf5](https://linux-hardware.org/?probe=49bd28cbf5) | Jan 31, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS_BR     | [dc652a6ac4](https://linux-hardware.org/?probe=dc652a6ac4) | Jan 30, 2022 |
| Dell          | 0X4H68 A00                  | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [83cdfa61a4](https://linux-hardware.org/?probe=83cdfa61a4) | Jan 28, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [ed43351639](https://linux-hardware.org/?probe=ed43351639) | Jan 27, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e422d19fb3](https://linux-hardware.org/?probe=e422d19fb3) | Jan 27, 2022 |
| Gigabyte      | B85M-D3V-A                  | [2d778a328d](https://linux-hardware.org/?probe=2d778a328d) | Jan 27, 2022 |
| PCWare        | IPMH110G                    | [82ee6777f1](https://linux-hardware.org/?probe=82ee6777f1) | Jan 26, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [267ee0e693](https://linux-hardware.org/?probe=267ee0e693) | Jan 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [a72f036b05](https://linux-hardware.org/?probe=a72f036b05) | Jan 26, 2022 |
| Gigabyte      | P55A-UD7                    | [084f158a19](https://linux-hardware.org/?probe=084f158a19) | Jan 26, 2022 |
| MSI           | Z270M MORTAR                | [2493fd0195](https://linux-hardware.org/?probe=2493fd0195) | Jan 26, 2022 |
| ASUSTek       | PRIME B250M-A               | [875671a912](https://linux-hardware.org/?probe=875671a912) | Jan 25, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [ec67e898bd](https://linux-hardware.org/?probe=ec67e898bd) | Jan 24, 2022 |
| Gigabyte      | B85M-D3V-A                  | [b812fc3ed2](https://linux-hardware.org/?probe=b812fc3ed2) | Jan 24, 2022 |
| HP            | 1497                        | [7761e5755c](https://linux-hardware.org/?probe=7761e5755c) | Jan 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | [dd33a742c9](https://linux-hardware.org/?probe=dd33a742c9) | Jan 24, 2022 |
| Gigabyte      | H110M-H-CF                  | [f8afc9746e](https://linux-hardware.org/?probe=f8afc9746e) | Jan 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3ceffb0902](https://linux-hardware.org/?probe=3ceffb0902) | Jan 24, 2022 |
| MSI           | B450M MORTAR MAX            | [619b081f40](https://linux-hardware.org/?probe=619b081f40) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [79e2d3dc48](https://linux-hardware.org/?probe=79e2d3dc48) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [937ad3940c](https://linux-hardware.org/?probe=937ad3940c) | Jan 23, 2022 |
| Gigabyte      | EP45-DS3L                   | [10b9d78b55](https://linux-hardware.org/?probe=10b9d78b55) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [1bea66eb77](https://linux-hardware.org/?probe=1bea66eb77) | Jan 23, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [38c5a8b4f6](https://linux-hardware.org/?probe=38c5a8b4f6) | Jan 23, 2022 |
| Gigabyte      | H77N-WIFI                   | [b006be0c8b](https://linux-hardware.org/?probe=b006be0c8b) | Jan 22, 2022 |
| Gigabyte      | D525TUD                     | [db0a0adc46](https://linux-hardware.org/?probe=db0a0adc46) | Jan 22, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [992e0c224c](https://linux-hardware.org/?probe=992e0c224c) | Jan 22, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [ada27693c4](https://linux-hardware.org/?probe=ada27693c4) | Jan 21, 2022 |
| MSI           | H310M PRO-VH                | [68c71dac17](https://linux-hardware.org/?probe=68c71dac17) | Jan 21, 2022 |
| Gigabyte      | H97-D3H-CF                  | [8e39cc0d01](https://linux-hardware.org/?probe=8e39cc0d01) | Jan 21, 2022 |
| BESSTAR Te... | HM50                        | [ddc2e44fcc](https://linux-hardware.org/?probe=ddc2e44fcc) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [1b1004081a](https://linux-hardware.org/?probe=1b1004081a) | Jan 21, 2022 |
| Gigabyte      | H81M-S2H                    | [5a010a60d7](https://linux-hardware.org/?probe=5a010a60d7) | Jan 20, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [04926d5643](https://linux-hardware.org/?probe=04926d5643) | Jan 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | [af3563e3e7](https://linux-hardware.org/?probe=af3563e3e7) | Jan 20, 2022 |
| Gigabyte      | B450 AORUS M                | [a846ee2ac3](https://linux-hardware.org/?probe=a846ee2ac3) | Jan 19, 2022 |
| MSI           | B450-A PRO MAX              | [72415f94c8](https://linux-hardware.org/?probe=72415f94c8) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [87c1802929](https://linux-hardware.org/?probe=87c1802929) | Jan 19, 2022 |
| MSI           | B450-A PRO MAX              | [ab286ab82d](https://linux-hardware.org/?probe=ab286ab82d) | Jan 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [ca82eeb3d3](https://linux-hardware.org/?probe=ca82eeb3d3) | Jan 19, 2022 |
| MSI           | H310M PRO-VH                | [844791ed3e](https://linux-hardware.org/?probe=844791ed3e) | Jan 19, 2022 |
| Dell          | 0PP150 A00                  | [851a920599](https://linux-hardware.org/?probe=851a920599) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c4103d5c5a](https://linux-hardware.org/?probe=c4103d5c5a) | Jan 19, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [3dd363739d](https://linux-hardware.org/?probe=3dd363739d) | Jan 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [01e009ebd0](https://linux-hardware.org/?probe=01e009ebd0) | Jan 18, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| Gigabyte      | Z590 AORUS MASTER           | [db8f93ad4a](https://linux-hardware.org/?probe=db8f93ad4a) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [7451fd2f02](https://linux-hardware.org/?probe=7451fd2f02) | Jan 17, 2022 |
| HP            | 1494                        | [c03b887753](https://linux-hardware.org/?probe=c03b887753) | Jan 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [6a024b63f0](https://linux-hardware.org/?probe=6a024b63f0) | Jan 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [01f17fdaa9](https://linux-hardware.org/?probe=01f17fdaa9) | Jan 16, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [ef86d029ff](https://linux-hardware.org/?probe=ef86d029ff) | Jan 16, 2022 |
| Acer          | Veriton X6620G v1.0         | [8ef5b3632a](https://linux-hardware.org/?probe=8ef5b3632a) | Jan 16, 2022 |
| Dell          | 09M8Y8 A01                  | [d5bd08abac](https://linux-hardware.org/?probe=d5bd08abac) | Jan 16, 2022 |
| Gigabyte      | B250M-D3H-CF                | [339d7aa470](https://linux-hardware.org/?probe=339d7aa470) | Jan 15, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [6903f0230f](https://linux-hardware.org/?probe=6903f0230f) | Jan 15, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [c458fb3c47](https://linux-hardware.org/?probe=c458fb3c47) | Jan 15, 2022 |
| ASUSTek       | Q87M-E                      | [30309c0416](https://linux-hardware.org/?probe=30309c0416) | Jan 15, 2022 |
| Dell          | 0NDYHG A01                  | [cc3a8808e7](https://linux-hardware.org/?probe=cc3a8808e7) | Jan 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| MSI           | B450-A PRO MAX              | [7bf06ab6f0](https://linux-hardware.org/?probe=7bf06ab6f0) | Jan 14, 2022 |
| Gigabyte      | Z490 AORUS MASTER           | [7de1f8971f](https://linux-hardware.org/?probe=7de1f8971f) | Jan 14, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | [e1d5a4a319](https://linux-hardware.org/?probe=e1d5a4a319) | Jan 14, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [bef980429e](https://linux-hardware.org/?probe=bef980429e) | Jan 14, 2022 |
| Gigabyte      | F2A68HM-H                   | [f8b504601e](https://linux-hardware.org/?probe=f8b504601e) | Jan 13, 2022 |
| MSI           | MAG B550M MORTAR            | [c7567b5c29](https://linux-hardware.org/?probe=c7567b5c29) | Jan 13, 2022 |
| Gigabyte      | EP45-DS3L                   | [538e62155e](https://linux-hardware.org/?probe=538e62155e) | Jan 11, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [f05cc95e99](https://linux-hardware.org/?probe=f05cc95e99) | Jan 11, 2022 |
| ASRock        | B360M IB-R1                 | [afb5a134ce](https://linux-hardware.org/?probe=afb5a134ce) | Jan 11, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [63db2e4ecc](https://linux-hardware.org/?probe=63db2e4ecc) | Jan 10, 2022 |
| ASRock        | B450 Pro4                   | [3b3b0c2855](https://linux-hardware.org/?probe=3b3b0c2855) | Jan 10, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [132d4e0b47](https://linux-hardware.org/?probe=132d4e0b47) | Jan 10, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [5d7aaea168](https://linux-hardware.org/?probe=5d7aaea168) | Jan 10, 2022 |
| ASUSTek       | H81-GAMER                   | [e123597c40](https://linux-hardware.org/?probe=e123597c40) | Jan 09, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [02fe041d02](https://linux-hardware.org/?probe=02fe041d02) | Jan 09, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [8d51630dcf](https://linux-hardware.org/?probe=8d51630dcf) | Jan 09, 2022 |
| Lenovo        | 369A SDK0F82993 WIN         | [e1141045bf](https://linux-hardware.org/?probe=e1141045bf) | Jan 08, 2022 |
| Gigabyte      | X570S AERO G                | [fc3f2a485a](https://linux-hardware.org/?probe=fc3f2a485a) | Jan 08, 2022 |
| Dell          | 04Y8V0 A02                  | [fa29ca9b4b](https://linux-hardware.org/?probe=fa29ca9b4b) | Jan 08, 2022 |
| Dell          | 04Y8V0 A02                  | [2564a1e4de](https://linux-hardware.org/?probe=2564a1e4de) | Jan 08, 2022 |
| ASUSTek       | Maximus IX CODE             | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| Gigabyte      | B75M-D3V                    | [faa71fac97](https://linux-hardware.org/?probe=faa71fac97) | Jan 06, 2022 |
| ASUSTek       | PRIME B360M-A               | [3b6e3858d5](https://linux-hardware.org/?probe=3b6e3858d5) | Jan 06, 2022 |
| ASUSTek       | Z77-A                       | [627b0162be](https://linux-hardware.org/?probe=627b0162be) | Jan 06, 2022 |
| Gigabyte      | B450 AORUS M                | [9ebb75d7a4](https://linux-hardware.org/?probe=9ebb75d7a4) | Jan 06, 2022 |
| Gigabyte      | EP45-DS3L                   | [9a5e27cab0](https://linux-hardware.org/?probe=9a5e27cab0) | Jan 05, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | [b56f576ff8](https://linux-hardware.org/?probe=b56f576ff8) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [75db843d7d](https://linux-hardware.org/?probe=75db843d7d) | Jan 04, 2022 |
| ASRock        | H110M-HDV R3.0              | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| HP            | 1495                        | [6298747a55](https://linux-hardware.org/?probe=6298747a55) | Jan 03, 2022 |
| ASRock        | H81M-HG4 R4.0               | [282277fa58](https://linux-hardware.org/?probe=282277fa58) | Jan 02, 2022 |
| MSI           | Z97S SLI Krait Edition      | [abff969a99](https://linux-hardware.org/?probe=abff969a99) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [b4049969e7](https://linux-hardware.org/?probe=b4049969e7) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [c5e569b5c7](https://linux-hardware.org/?probe=c5e569b5c7) | Jan 02, 2022 |
| ASRock        | B360M IB-R1                 | [f300f71e62](https://linux-hardware.org/?probe=f300f71e62) | Jan 02, 2022 |
| Gigabyte      | EP45-DS3L                   | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| Gigabyte      | G41MT-D3                    | [9c2f65c964](https://linux-hardware.org/?probe=9c2f65c964) | Jan 01, 2022 |
| Dell          | 0T7D40 A01                  | [4fce685dae](https://linux-hardware.org/?probe=4fce685dae) | Jan 01, 2022 |
| Dell          | 0T7D40 A01                  | [4ce7ea3bb0](https://linux-hardware.org/?probe=4ce7ea3bb0) | Dec 31, 2021 |
| Intel         | SKYBAY                      | [043f80cded](https://linux-hardware.org/?probe=043f80cded) | Dec 31, 2021 |
| ASUSTek       | PRIME B450M-A               | [58cb628601](https://linux-hardware.org/?probe=58cb628601) | Dec 31, 2021 |
| Gigabyte      | F2A88XM-DS2P                | [75eea6ae2f](https://linux-hardware.org/?probe=75eea6ae2f) | Dec 30, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [00f3b181b3](https://linux-hardware.org/?probe=00f3b181b3) | Dec 30, 2021 |
| MSI           | X370 GAMING PLUS            | [49f7093e8c](https://linux-hardware.org/?probe=49f7093e8c) | Dec 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [47edce55a4](https://linux-hardware.org/?probe=47edce55a4) | Dec 29, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [e3297eb51f](https://linux-hardware.org/?probe=e3297eb51f) | Dec 29, 2021 |
| Gigabyte      | TRX40 AORUS XTREME          | [cbf9ee4a86](https://linux-hardware.org/?probe=cbf9ee4a86) | Dec 28, 2021 |
| MSI           | H81M-E33                    | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| XFX           | nForce 780i 3-Way SLI 1     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| ASUSTek       | M2N-E                       | [3a08145f4b](https://linux-hardware.org/?probe=3a08145f4b) | Dec 24, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [ca0f62a716](https://linux-hardware.org/?probe=ca0f62a716) | Dec 24, 2021 |
| MSI           | MEG Z390 GODLIKE            | [f1e535b5ba](https://linux-hardware.org/?probe=f1e535b5ba) | Dec 24, 2021 |
| Gigabyte      | Z390 M-CF                   | [6efc5bede0](https://linux-hardware.org/?probe=6efc5bede0) | Dec 23, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [4cd052492e](https://linux-hardware.org/?probe=4cd052492e) | Dec 23, 2021 |
| MSI           | A320M PRO-VH PLUS           | [27379a7599](https://linux-hardware.org/?probe=27379a7599) | Dec 22, 2021 |
| MSI           | PRO Z690-A WIFI DDR4        | [51a7e08e9a](https://linux-hardware.org/?probe=51a7e08e9a) | Dec 22, 2021 |
| MSI           | X470 GAMING M7 AC           | [9b2acc6ea1](https://linux-hardware.org/?probe=9b2acc6ea1) | Dec 22, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [dd197ecb62](https://linux-hardware.org/?probe=dd197ecb62) | Dec 21, 2021 |
| ASUSTek       | P5G41-M                     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [03abaff4ae](https://linux-hardware.org/?probe=03abaff4ae) | Dec 21, 2021 |
| Gigabyte      | EP45-DS3L                   | [e0f736fe3b](https://linux-hardware.org/?probe=e0f736fe3b) | Dec 20, 2021 |
| Dell          | 0YJPT1 A00                  | [a92e152a7c](https://linux-hardware.org/?probe=a92e152a7c) | Dec 20, 2021 |
| ASRock        | X399 Taichi                 | [16e27617b9](https://linux-hardware.org/?probe=16e27617b9) | Dec 20, 2021 |
| Gigabyte      | H61M-USB3V                  | [d05d2fe462](https://linux-hardware.org/?probe=d05d2fe462) | Dec 20, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [9c1cf57d74](https://linux-hardware.org/?probe=9c1cf57d74) | Dec 20, 2021 |
| Dell          | 0C522T A03                  | [58f36b9637](https://linux-hardware.org/?probe=58f36b9637) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI           | X370 SLI PLUS               | [adb27f9347](https://linux-hardware.org/?probe=adb27f9347) | Dec 19, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [e2ce1d7284](https://linux-hardware.org/?probe=e2ce1d7284) | Dec 19, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6653477f61](https://linux-hardware.org/?probe=6653477f61) | Dec 18, 2021 |
| JINGSHA       | Unknown                     | [13da82798c](https://linux-hardware.org/?probe=13da82798c) | Dec 18, 2021 |
| Gigabyte      | H370 HD3-CF                 | [2497b24eda](https://linux-hardware.org/?probe=2497b24eda) | Dec 18, 2021 |
| Gigabyte      | F2A88XM-DS2P                | [c18ddabc8d](https://linux-hardware.org/?probe=c18ddabc8d) | Dec 18, 2021 |
| ASUSTek       | P5G41-M                     | [c073d4a4e9](https://linux-hardware.org/?probe=c073d4a4e9) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| HP            | 805D                        | [dfdc70512c](https://linux-hardware.org/?probe=dfdc70512c) | Dec 16, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [45a411c9fe](https://linux-hardware.org/?probe=45a411c9fe) | Dec 15, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [60a7206b05](https://linux-hardware.org/?probe=60a7206b05) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [660ce7fc74](https://linux-hardware.org/?probe=660ce7fc74) | Dec 15, 2021 |
| Dell          | 0RY007                      | [f3cb490147](https://linux-hardware.org/?probe=f3cb490147) | Dec 14, 2021 |
| Gigabyte      | Z270P-D3-CF                 | [b2dc7c9e05](https://linux-hardware.org/?probe=b2dc7c9e05) | Dec 14, 2021 |
| HP            | 2B2B                        | [bf929a4359](https://linux-hardware.org/?probe=bf929a4359) | Dec 14, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [53523a4ea7](https://linux-hardware.org/?probe=53523a4ea7) | Dec 14, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [3030fcf474](https://linux-hardware.org/?probe=3030fcf474) | Dec 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Gigabyte      | B560M DS3H V2               | [169e6793c2](https://linux-hardware.org/?probe=169e6793c2) | Dec 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [021525201e](https://linux-hardware.org/?probe=021525201e) | Dec 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [bd4a0c5d2f](https://linux-hardware.org/?probe=bd4a0c5d2f) | Dec 12, 2021 |
| ASUSTek       | P6T                         | [b789a1151e](https://linux-hardware.org/?probe=b789a1151e) | Dec 11, 2021 |
| Gigabyte      | X570 AORUS PRO              | [8ae1043ce6](https://linux-hardware.org/?probe=8ae1043ce6) | Dec 10, 2021 |
| Gigabyte      | 990FXA-UD3                  | [b76ef07c59](https://linux-hardware.org/?probe=b76ef07c59) | Dec 10, 2021 |
| ASUSTek       | P6T                         | [71ce922273](https://linux-hardware.org/?probe=71ce922273) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [bf533d0378](https://linux-hardware.org/?probe=bf533d0378) | Dec 09, 2021 |
| Gigabyte      | Z690 UD DDR4                | [d0070c39c4](https://linux-hardware.org/?probe=d0070c39c4) | Dec 09, 2021 |
| Gigabyte      | Z77-D3H                     | [c486c9645b](https://linux-hardware.org/?probe=c486c9645b) | Dec 09, 2021 |
| Dell          | 040DDP A01                  | [b8e92a4957](https://linux-hardware.org/?probe=b8e92a4957) | Dec 09, 2021 |
| ASUSTek       | P6T                         | [d04f9d16a8](https://linux-hardware.org/?probe=d04f9d16a8) | Dec 08, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [82926e68a4](https://linux-hardware.org/?probe=82926e68a4) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| Apple         | Mac-F221BEC8                | [809152313d](https://linux-hardware.org/?probe=809152313d) | Dec 07, 2021 |
| ASUSTek       | SABERTOOTH X79              | [58c6a86730](https://linux-hardware.org/?probe=58c6a86730) | Dec 07, 2021 |
| Gigabyte      | Z97P-D3                     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | [5393b5ad7a](https://linux-hardware.org/?probe=5393b5ad7a) | Dec 06, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [9e878d83a3](https://linux-hardware.org/?probe=9e878d83a3) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [0a06cba7c5](https://linux-hardware.org/?probe=0a06cba7c5) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [82cd98ea5a](https://linux-hardware.org/?probe=82cd98ea5a) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [07f484651e](https://linux-hardware.org/?probe=07f484651e) | Dec 06, 2021 |
| Gigabyte      | B450 AORUS M                | [18ae64d44d](https://linux-hardware.org/?probe=18ae64d44d) | Dec 05, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [b296e2a320](https://linux-hardware.org/?probe=b296e2a320) | Dec 05, 2021 |
| Dell          | 0M859N A00                  | [f254ee88c6](https://linux-hardware.org/?probe=f254ee88c6) | Dec 05, 2021 |
| MSI           | Z87M GAMING                 | [4ef67e0560](https://linux-hardware.org/?probe=4ef67e0560) | Dec 04, 2021 |
| ASUSTek       | Z87-A                       | [e7d4963834](https://linux-hardware.org/?probe=e7d4963834) | Dec 04, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | [ce556a2535](https://linux-hardware.org/?probe=ce556a2535) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [511a349d7f](https://linux-hardware.org/?probe=511a349d7f) | Dec 03, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [fd20b7fc56](https://linux-hardware.org/?probe=fd20b7fc56) | Dec 03, 2021 |
| Dell          | 06D7TR A00                  | [8c6244cb77](https://linux-hardware.org/?probe=8c6244cb77) | Dec 03, 2021 |
| MSI           | MEG Z390 GODLIKE            | [ca1727f54a](https://linux-hardware.org/?probe=ca1727f54a) | Dec 02, 2021 |
| Gateway       | SX2185                      | [70e907b207](https://linux-hardware.org/?probe=70e907b207) | Dec 02, 2021 |
| Dell          | 040DDP A01                  | [b108ae97c2](https://linux-hardware.org/?probe=b108ae97c2) | Dec 02, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| ASUSTek       | H81M-C                      | [ffecd77f3a](https://linux-hardware.org/?probe=ffecd77f3a) | Dec 02, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [508352ad4a](https://linux-hardware.org/?probe=508352ad4a) | Dec 02, 2021 |
| Gigabyte      | B85M-D3V-A                  | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| Huanan        | X99-F8 V2.0                 | [1b4de261b3](https://linux-hardware.org/?probe=1b4de261b3) | Nov 30, 2021 |
| Gigabyte      | Z690 UD DDR4                | [7ad53e55ba](https://linux-hardware.org/?probe=7ad53e55ba) | Nov 30, 2021 |
| Apple         | Mac-F221BEC8                | [2ceb61c052](https://linux-hardware.org/?probe=2ceb61c052) | Nov 30, 2021 |
| Gigabyte      | EX58-UD3R                   | [8ece12c9e6](https://linux-hardware.org/?probe=8ece12c9e6) | Nov 28, 2021 |
| ECS           | H61H2-CM                    | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Gigabyte      | H170-Gaming 3               | [e83680db56](https://linux-hardware.org/?probe=e83680db56) | Nov 28, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [d813ffb878](https://linux-hardware.org/?probe=d813ffb878) | Nov 28, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [5d5d624d8c](https://linux-hardware.org/?probe=5d5d624d8c) | Nov 27, 2021 |
| MSI           | B450-A PRO MAX              | [d949cb9963](https://linux-hardware.org/?probe=d949cb9963) | Nov 27, 2021 |
| Dell          | 06D7TR A00                  | [d980b32136](https://linux-hardware.org/?probe=d980b32136) | Nov 27, 2021 |
| ASRock        | H81M-HG4 R4.0               | [c23e7e890b](https://linux-hardware.org/?probe=c23e7e890b) | Nov 27, 2021 |
| ASUSTek       | M4A77T/USB3                 | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [1e4799819e](https://linux-hardware.org/?probe=1e4799819e) | Nov 26, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| Apple         | Mac-F221BEC8                | [f4f5c37779](https://linux-hardware.org/?probe=f4f5c37779) | Nov 25, 2021 |
| Gigabyte      | Z690 UD DDR4                | [b6ffc90d4e](https://linux-hardware.org/?probe=b6ffc90d4e) | Nov 25, 2021 |
| MSI           | B550-A PRO                  | [b90083da69](https://linux-hardware.org/?probe=b90083da69) | Nov 24, 2021 |
| Apple         | Mac-F221BEC8                | [e606757d4a](https://linux-hardware.org/?probe=e606757d4a) | Nov 24, 2021 |
| Dell          | 0C522T A03                  | [96fec5d214](https://linux-hardware.org/?probe=96fec5d214) | Nov 24, 2021 |
| Gigabyte      | B550 AORUS PRO              | [35801f40df](https://linux-hardware.org/?probe=35801f40df) | Nov 24, 2021 |
| Dell          | 0C522T A03                  | [79ee4911cb](https://linux-hardware.org/?probe=79ee4911cb) | Nov 24, 2021 |
| MSI           | A55M-E33                    | [e6616870b6](https://linux-hardware.org/?probe=e6616870b6) | Nov 24, 2021 |
| HP            | 1906                        | [8ec5c16fc7](https://linux-hardware.org/?probe=8ec5c16fc7) | Nov 24, 2021 |
| HP            | 83E1                        | [7598ac7e6c](https://linux-hardware.org/?probe=7598ac7e6c) | Nov 23, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | [c50601fb76](https://linux-hardware.org/?probe=c50601fb76) | Nov 23, 2021 |
| HP            | 0B4Ch D                     | [0c3c7c6bb3](https://linux-hardware.org/?probe=0c3c7c6bb3) | Nov 23, 2021 |
| HP            | 1906                        | [90499fe34d](https://linux-hardware.org/?probe=90499fe34d) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| Gigabyte      | GA-MA790X-UD4               | [0a19a35ac4](https://linux-hardware.org/?probe=0a19a35ac4) | Nov 22, 2021 |
| ASRock        | G41M-VS3                    | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| Pegatron      | 2AD5                        | [8fc4f44be5](https://linux-hardware.org/?probe=8fc4f44be5) | Nov 22, 2021 |
| Gigabyte      | F2A85XM-D3H                 | [1c41d8c34c](https://linux-hardware.org/?probe=1c41d8c34c) | Nov 22, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [683697e6ee](https://linux-hardware.org/?probe=683697e6ee) | Nov 21, 2021 |
| MSI           | B450M-A PRO MAX             | [92375d0ecc](https://linux-hardware.org/?probe=92375d0ecc) | Nov 21, 2021 |
| Dell          | 0M859N A00                  | [2fa52f3236](https://linux-hardware.org/?probe=2fa52f3236) | Nov 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | [faec9a8f8b](https://linux-hardware.org/?probe=faec9a8f8b) | Nov 21, 2021 |
| HP            | 3048h                       | [e38eb769b5](https://linux-hardware.org/?probe=e38eb769b5) | Nov 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [44d1a95b0b](https://linux-hardware.org/?probe=44d1a95b0b) | Nov 20, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [3b34362c42](https://linux-hardware.org/?probe=3b34362c42) | Nov 19, 2021 |
| ASUSTek       | A68HM-K                     | [8bf7660808](https://linux-hardware.org/?probe=8bf7660808) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | [02b2e4cb00](https://linux-hardware.org/?probe=02b2e4cb00) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | [181c56512d](https://linux-hardware.org/?probe=181c56512d) | Nov 19, 2021 |
| Dell          | 0YNVJG A01                  | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Dell          | 0YNVJG A01                  | [fbedd3af33](https://linux-hardware.org/?probe=fbedd3af33) | Nov 19, 2021 |
| Pegatron      | 2AD5                        | [839b5c24aa](https://linux-hardware.org/?probe=839b5c24aa) | Nov 19, 2021 |
| MSI           | B450 TOMAHAWK               | [6a1607ab9d](https://linux-hardware.org/?probe=6a1607ab9d) | Nov 18, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [c8a6893780](https://linux-hardware.org/?probe=c8a6893780) | Nov 18, 2021 |
| MSI           | A320M-A PRO MAX             | [d9f71fda8f](https://linux-hardware.org/?probe=d9f71fda8f) | Nov 18, 2021 |
| Dell          | 0C27VV A01                  | [34aff3ab72](https://linux-hardware.org/?probe=34aff3ab72) | Nov 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f35f04cabd](https://linux-hardware.org/?probe=f35f04cabd) | Nov 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [50535d277c](https://linux-hardware.org/?probe=50535d277c) | Nov 18, 2021 |
| ASUSTek       | PRIME B360M-K               | [3b2165faa8](https://linux-hardware.org/?probe=3b2165faa8) | Nov 18, 2021 |
| Gigabyte      | B550M DS3H                  | [93c3ab9ed1](https://linux-hardware.org/?probe=93c3ab9ed1) | Nov 18, 2021 |
| Gigabyte      | H97M-D3H                    | [f6dc8337e7](https://linux-hardware.org/?probe=f6dc8337e7) | Nov 18, 2021 |
| MSI           | Z77A-G43                    | [04db0a2350](https://linux-hardware.org/?probe=04db0a2350) | Nov 17, 2021 |
| ASRock        | X470 Master SLI             | [c48f95d233](https://linux-hardware.org/?probe=c48f95d233) | Nov 17, 2021 |
| Gigabyte      | H370M DS3H-CF               | [c69f79e654](https://linux-hardware.org/?probe=c69f79e654) | Nov 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [ddfb1c2b1a](https://linux-hardware.org/?probe=ddfb1c2b1a) | Nov 17, 2021 |
| Dell          | 0GY6Y8 A02                  | [61734716ea](https://linux-hardware.org/?probe=61734716ea) | Nov 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9404dfb1fe](https://linux-hardware.org/?probe=9404dfb1fe) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3412d5cf0b](https://linux-hardware.org/?probe=3412d5cf0b) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [bdd9599f2f](https://linux-hardware.org/?probe=bdd9599f2f) | Nov 16, 2021 |
| ASUSTek       | M2N-E                       | [8da42387a5](https://linux-hardware.org/?probe=8da42387a5) | Nov 15, 2021 |
| Gigabyte      | B560M DS3H                  | [97ed26b846](https://linux-hardware.org/?probe=97ed26b846) | Nov 15, 2021 |
| ASRock        | B450 Pro4                   | [098387cb9c](https://linux-hardware.org/?probe=098387cb9c) | Nov 15, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [bc6a3771aa](https://linux-hardware.org/?probe=bc6a3771aa) | Nov 13, 2021 |
| ASUSTek       | M3A78-EM                    | [e1cc8b1ee3](https://linux-hardware.org/?probe=e1cc8b1ee3) | Nov 13, 2021 |
| ASUSTek       | H61M-CS                     | [22858e9ab9](https://linux-hardware.org/?probe=22858e9ab9) | Nov 13, 2021 |
| Apple         | Mac-F221BEC8                | [5991ba5f44](https://linux-hardware.org/?probe=5991ba5f44) | Nov 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [e85856bbef](https://linux-hardware.org/?probe=e85856bbef) | Nov 12, 2021 |
| Dell          | 0DXJD9 A00                  | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| Intel         | D33217GKE G69901-205        | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| MSI           | Z390-A PRO                  | [ca1489298b](https://linux-hardware.org/?probe=ca1489298b) | Nov 10, 2021 |
| Gigabyte      | X570 UD                     | [c5ae0c1fca](https://linux-hardware.org/?probe=c5ae0c1fca) | Nov 09, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Dell          | 040DDP A01                  | [3587a95d63](https://linux-hardware.org/?probe=3587a95d63) | Nov 09, 2021 |
| Intel         | D33217GKE G69901-205        | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | [09cae8a245](https://linux-hardware.org/?probe=09cae8a245) | Nov 09, 2021 |
| HP            | 2215                        | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| Gigabyte      | EP45-DS3L                   | [fdbec54288](https://linux-hardware.org/?probe=fdbec54288) | Nov 08, 2021 |
| Gigabyte      | H97M-D3H                    | [74b5acd6cd](https://linux-hardware.org/?probe=74b5acd6cd) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | [a7510caa6d](https://linux-hardware.org/?probe=a7510caa6d) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | [2eebb6842a](https://linux-hardware.org/?probe=2eebb6842a) | Nov 08, 2021 |
| Seco          | C40 C                       | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI           | X570-A PRO                  | [0e47ec7819](https://linux-hardware.org/?probe=0e47ec7819) | Nov 08, 2021 |
| ASUSTek       | PRIME B550M-A               | [ef16e3ad0f](https://linux-hardware.org/?probe=ef16e3ad0f) | Nov 07, 2021 |
| Gigabyte      | EP45-DS3L                   | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| Dell          | 0C522T A03                  | [43d8e3d9d8](https://linux-hardware.org/?probe=43d8e3d9d8) | Nov 07, 2021 |
| ABIT          | AX78                        | [3d56ae3738](https://linux-hardware.org/?probe=3d56ae3738) | Nov 06, 2021 |
| MSI           | MEG X570 UNIFY              | [37685b5198](https://linux-hardware.org/?probe=37685b5198) | Nov 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6cce11439f](https://linux-hardware.org/?probe=6cce11439f) | Nov 06, 2021 |
| ASUSTek       | M5A97                       | [f8ce8bca36](https://linux-hardware.org/?probe=f8ce8bca36) | Nov 05, 2021 |
| MSI           | Z97M-G43                    | [7b0e15a051](https://linux-hardware.org/?probe=7b0e15a051) | Nov 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [ad6e327cf5](https://linux-hardware.org/?probe=ad6e327cf5) | Nov 05, 2021 |
| ASRock        | G41M-VS3                    | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | [fa84d0d544](https://linux-hardware.org/?probe=fa84d0d544) | Nov 04, 2021 |
| ASUSTek       | PRIME Z370-P                | [50301dd3e3](https://linux-hardware.org/?probe=50301dd3e3) | Nov 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [f5ef935897](https://linux-hardware.org/?probe=f5ef935897) | Nov 04, 2021 |
| Gigabyte      | H61M-S2V-B3                 | [5baf0ce3af](https://linux-hardware.org/?probe=5baf0ce3af) | Nov 04, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [14c9dda4cd](https://linux-hardware.org/?probe=14c9dda4cd) | Nov 04, 2021 |
| MSI           | B450M MORTAR                | [00a97d0eba](https://linux-hardware.org/?probe=00a97d0eba) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V                     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| ASUSTek       | Z87M-PLUS                   | [c26ea680eb](https://linux-hardware.org/?probe=c26ea680eb) | Nov 03, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [3acf5c243f](https://linux-hardware.org/?probe=3acf5c243f) | Nov 03, 2021 |
| MSI           | MAG B550M MORTAR            | [10a45363fe](https://linux-hardware.org/?probe=10a45363fe) | Nov 03, 2021 |
| ASRock        | G41M-VS3                    | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| MSI           | B365M PRO-VH                | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [c8716ec9a6](https://linux-hardware.org/?probe=c8716ec9a6) | Nov 03, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [93de1508cb](https://linux-hardware.org/?probe=93de1508cb) | Oct 31, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [136c409f1a](https://linux-hardware.org/?probe=136c409f1a) | Oct 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [ae8daa788a](https://linux-hardware.org/?probe=ae8daa788a) | Oct 27, 2021 |
| MSI           | B550-A PRO                  | [91c5853577](https://linux-hardware.org/?probe=91c5853577) | Oct 25, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [fac95138dc](https://linux-hardware.org/?probe=fac95138dc) | Oct 23, 2021 |
| Foxconn       | H81MXV FAB A                | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [746401b748](https://linux-hardware.org/?probe=746401b748) | Oct 18, 2021 |
| MSI           | B350 PC MATE                | [bc716e921b](https://linux-hardware.org/?probe=bc716e921b) | Oct 15, 2021 |
| Dell          | 0WMJ54 A01                  | [01ce3b252c](https://linux-hardware.org/?probe=01ce3b252c) | Oct 14, 2021 |
| ASUSTek       | PRIME B550M-A               | [2ff2eb607a](https://linux-hardware.org/?probe=2ff2eb607a) | Oct 14, 2021 |
| ASUSTek       | PRIME A320I-K               | [eee2a960f5](https://linux-hardware.org/?probe=eee2a960f5) | Oct 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [7b26df9bc4](https://linux-hardware.org/?probe=7b26df9bc4) | Oct 10, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [cfbe862160](https://linux-hardware.org/?probe=cfbe862160) | Oct 10, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [a9ceb4591e](https://linux-hardware.org/?probe=a9ceb4591e) | Oct 09, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [7c210a60ab](https://linux-hardware.org/?probe=7c210a60ab) | Oct 09, 2021 |
| Gigabyte      | H61N-USB3                   | [43ded3a853](https://linux-hardware.org/?probe=43ded3a853) | Oct 09, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b3d0295208](https://linux-hardware.org/?probe=b3d0295208) | Oct 08, 2021 |
| Gigabyte      | H61N-USB3                   | [75d34f09c4](https://linux-hardware.org/?probe=75d34f09c4) | Oct 06, 2021 |
| MSI           | B550-A PRO                  | [17a03c217e](https://linux-hardware.org/?probe=17a03c217e) | Oct 04, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [103d2198a4](https://linux-hardware.org/?probe=103d2198a4) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| Gigabyte      | H81M-S2H                    | [b8c27bd56c](https://linux-hardware.org/?probe=b8c27bd56c) | Sep 28, 2021 |
| ASRock        | B450M-HDV R4.0              | [2f771e8271](https://linux-hardware.org/?probe=2f771e8271) | Sep 24, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [e75373a634](https://linux-hardware.org/?probe=e75373a634) | Sep 23, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [3875512e39](https://linux-hardware.org/?probe=3875512e39) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [4fb9ed180b](https://linux-hardware.org/?probe=4fb9ed180b) | Sep 14, 2021 |
| Dell          | 0WMJ54 A01                  | [3231b34d4d](https://linux-hardware.org/?probe=3231b34d4d) | Aug 24, 2021 |
| Dell          | 0WMJ54 A01                  | [a94ad8a323](https://linux-hardware.org/?probe=a94ad8a323) | Aug 22, 2021 |
| HP            | 8055                        | [29f5b9a7ab](https://linux-hardware.org/?probe=29f5b9a7ab) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | [f48bc9ac9d](https://linux-hardware.org/?probe=f48bc9ac9d) | Aug 07, 2021 |
| ASUSTek       | Maximus V FORMULA           | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell          | 0KC9NP A01                  | [7dcd16d3fd](https://linux-hardware.org/?probe=7dcd16d3fd) | Jul 14, 2021 |
| Dell          | 0KC9NP A01                  | [eedd464065](https://linux-hardware.org/?probe=eedd464065) | Jul 14, 2021 |
| Dell          | 0KC9NP A01                  | [8d1e68aad0](https://linux-hardware.org/?probe=8d1e68aad0) | Jul 07, 2021 |
| Dell          | 0KC9NP A01                  | [852a8a103d](https://linux-hardware.org/?probe=852a8a103d) | Jul 04, 2021 |
| Dell          | 0KC9NP A01                  | [3a0ca9b90c](https://linux-hardware.org/?probe=3a0ca9b90c) | Jul 01, 2021 |
| Dell          | 0KC9NP A01                  | [3ed1ee1f81](https://linux-hardware.org/?probe=3ed1ee1f81) | Jun 25, 2021 |
| Dell          | 0KC9NP A01                  | [f611d9ec88](https://linux-hardware.org/?probe=f611d9ec88) | Jun 23, 2021 |
| ASUSTek       | Maximus V FORMULA           | [95ba18d5da](https://linux-hardware.org/?probe=95ba18d5da) | Jun 23, 2021 |
| Dell          | 0KC9NP A01                  | [511e8019e0](https://linux-hardware.org/?probe=511e8019e0) | Jun 19, 2021 |
| Dell          | 0KC9NP A01                  | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek       | Maximus V FORMULA           | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| ECS           | MCP61M-M3                   | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek       | PRIME X570-PRO              | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| 5.15.6-200.fc35.x86_64                                        | 29       | 6.65%   |
| 5.14.10-300.fc35.x86_64                                       | 27       | 6.19%   |
| 5.16.16-200.fc35.x86_64                                       | 24       | 5.5%    |
| 5.16.12-200.fc35.x86_64                                       | 22       | 5.05%   |
| 5.16.9-200.fc35.x86_64                                        | 21       | 4.82%   |
| 5.15.12-200.fc35.x86_64                                       | 21       | 4.82%   |
| 5.14.18-300.fc35.x86_64                                       | 20       | 4.59%   |
| 5.15.16-200.fc35.x86_64                                       | 17       | 3.9%    |
| 5.14.17-301.fc35.x86_64                                       | 17       | 3.9%    |
| 5.14.16-301.fc35.x86_64                                       | 17       | 3.9%    |
| 5.15.18-200.fc35.x86_64                                       | 15       | 3.44%   |
| 5.14.14-300.fc35.x86_64                                       | 14       | 3.21%   |
| 5.16.5-200.fc35.x86_64                                        | 13       | 2.98%   |
| 5.15.14-200.fc35.x86_64                                       | 13       | 2.98%   |
| 5.16.11-200.fc35.x86_64                                       | 12       | 2.75%   |
| 5.15.8-200.fc35.x86_64                                        | 12       | 2.75%   |
| 5.14.15-300.fc35.x86_64                                       | 11       | 2.52%   |
| 5.16.15-201.fc35.x86_64                                       | 10       | 2.29%   |
| 5.15.13-200.fc35.x86_64                                       | 10       | 2.29%   |
| 5.15.11-200.fc35.x86_64                                       | 9        | 2.06%   |
| 5.15.15-200.fc35.x86_64                                       | 7        | 1.61%   |
| 5.15.10-200.fc35.x86_64                                       | 7        | 1.61%   |
| 5.16.8-200.fc35.x86_64                                        | 6        | 1.38%   |
| 5.16.7-200.fc35.x86_64                                        | 6        | 1.38%   |
| 5.16.18-200.fc35.x86_64                                       | 6        | 1.38%   |
| 5.15.17-200.fc35.x86_64                                       | 6        | 1.38%   |
| 5.15.5-200.fc35.x86_64                                        | 5        | 1.15%   |
| 5.15.4-201.fc35.x86_64                                        | 5        | 1.15%   |
| 5.14.9-300.fc35.x86_64                                        | 5        | 1.15%   |
| 5.16.14-200.fc35.x86_64                                       | 4        | 0.92%   |
| 5.16.13-200.fc35.x86_64                                       | 4        | 0.92%   |
| 5.15.7-200.fc35.x86_64                                        | 4        | 0.92%   |
| 5.14.0-60.fc35.x86_64                                         | 3        | 0.69%   |
| 5.14.20-300.fc35.x86_64                                       | 2        | 0.46%   |
| 5.12.0-0.rc7.189.fc35.x86_64                                  | 2        | 0.46%   |
| 5.8.15-301.fc33.x86_64                                        | 1        | 0.23%   |
| 5.16.4-200.fc35.x86_64                                        | 1        | 0.23%   |
| 5.16.2-225.vanilla.1.fc35.x86_64                              | 1        | 0.23%   |
| 5.16.2-200.fc35.x86_64                                        | 1        | 0.23%   |
| 5.16.17-200.fc35.x86_64                                       | 1        | 0.23%   |
| 5.16.11-xm1.0.fc35.x86_64                                     | 1        | 0.23%   |
| 5.16.0-0.rc6.41.vanilla.1.fc35.x86_64                         | 1        | 0.23%   |
| 5.16.0-0.rc2.18.vanilla.1.fc35.x86_64                         | 1        | 0.23%   |
| 5.16.0-0.rc1.20211115git8ab774587903.14.vanilla.1.fc35.x86_64 | 1        | 0.23%   |
| 5.15.5-xm1tt.0.fc35.x86_64                                    | 1        | 0.23%   |
| 5.15.4-xm1.0.fc35.x86_64                                      | 1        | 0.23%   |
| 5.15.2_tkg_bmq                                                | 1        | 0.23%   |
| 5.15.0-500.chinfo.fc35.x86_64                                 | 1        | 0.23%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.vanilla.1.fc35.x86_64 | 1        | 0.23%   |
| 5.14.8-lqx1.0.fc35.x86_64                                     | 1        | 0.23%   |
| 5.14.7-300.fc35.x86_64                                        | 1        | 0.23%   |
| 5.14.6-300.fc35.x86_64                                        | 1        | 0.23%   |
| 5.14.18-301.fsync.fc35.x86_64                                 | 1        | 0.23%   |
| 5.14.13_MY                                                    | 1        | 0.23%   |
| 5.14.1-300.fc35.x86_64                                        | 1        | 0.23%   |
| 5.14.0-0.rc6.46.fc35.x86_64                                   | 1        | 0.23%   |
| 5.13.7-200.fc34.x86_64                                        | 1        | 0.23%   |
| 5.13.0-58.fc35.x86_64                                         | 1        | 0.23%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64           | 1        | 0.23%   |
| 5.13.0-0.rc6.45.fc35.x86_64                                   | 1        | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.6  | 29       | 6.71%   |
| 5.14.10 | 27       | 6.25%   |
| 5.16.16 | 24       | 5.56%   |
| 5.16.12 | 22       | 5.09%   |
| 5.16.9  | 21       | 4.86%   |
| 5.15.12 | 21       | 4.86%   |
| 5.14.18 | 21       | 4.86%   |
| 5.15.16 | 17       | 3.94%   |
| 5.14.17 | 17       | 3.94%   |
| 5.14.16 | 17       | 3.94%   |
| 5.15.18 | 15       | 3.47%   |
| 5.14.14 | 14       | 3.24%   |
| 5.16.5  | 13       | 3.01%   |
| 5.16.11 | 13       | 3.01%   |
| 5.15.14 | 13       | 3.01%   |
| 5.15.8  | 12       | 2.78%   |
| 5.14.15 | 11       | 2.55%   |
| 5.16.15 | 10       | 2.31%   |
| 5.15.13 | 10       | 2.31%   |
| 5.15.11 | 9        | 2.08%   |
| 5.15.15 | 7        | 1.62%   |
| 5.15.10 | 7        | 1.62%   |
| 5.16.8  | 6        | 1.39%   |
| 5.16.7  | 6        | 1.39%   |
| 5.16.18 | 6        | 1.39%   |
| 5.15.5  | 6        | 1.39%   |
| 5.15.4  | 6        | 1.39%   |
| 5.15.17 | 6        | 1.39%   |
| 5.14.9  | 5        | 1.16%   |
| 5.16.14 | 4        | 0.93%   |
| 5.16.13 | 4        | 0.93%   |
| 5.15.7  | 4        | 0.93%   |
| 5.14.0  | 4        | 0.93%   |
| 5.13.0  | 3        | 0.69%   |
| 5.16.2  | 2        | 0.46%   |
| 5.16.0  | 2        | 0.46%   |
| 5.15.0  | 2        | 0.46%   |
| 5.14.20 | 2        | 0.46%   |
| 5.12.0  | 2        | 0.46%   |
| 5.8.15  | 1        | 0.23%   |
| 5.16.4  | 1        | 0.23%   |
| 5.16.17 | 1        | 0.23%   |
| 5.15.2  | 1        | 0.23%   |
| 5.14.8  | 1        | 0.23%   |
| 5.14.7  | 1        | 0.23%   |
| 5.14.6  | 1        | 0.23%   |
| 5.14.13 | 1        | 0.23%   |
| 5.14.1  | 1        | 0.23%   |
| 5.13.7  | 1        | 0.23%   |
| 5.11.13 | 1        | 0.23%   |
| 5.10.15 | 1        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 150      | 37.22%  |
| 5.16    | 123      | 30.52%  |
| 5.14    | 121      | 30.02%  |
| 5.13    | 4        | 0.99%   |
| 5.12    | 2        | 0.5%    |
| 5.8     | 1        | 0.25%   |
| 5.11    | 1        | 0.25%   |
| 5.10    | 1        | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 377      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 286      | 75.26%  |
| KDE5          | 42       | 11.05%  |
| Unknown       | 17       | 4.47%   |
| X-Cinnamon    | 8        | 2.11%   |
| Cinnamon      | 8        | 2.11%   |
| XFCE          | 5        | 1.32%   |
| MATE          | 5        | 1.32%   |
| KDE           | 4        | 1.05%   |
| GNOME Classic | 3        | 0.79%   |
| openbox       | 1        | 0.26%   |
| LXDE          | 1        | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 203      | 52.32%  |
| X11     | 160      | 41.24%  |
| Tty     | 15       | 3.87%   |
| Unknown | 9        | 2.32%   |
| Web     | 1        | 0.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 214      | 56.46%  |
| GDM     | 112      | 29.55%  |
| LightDM | 28       | 7.39%   |
| SDDM    | 25       | 6.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 169      | 44.59%  |
| en_GB      | 26       | 6.86%   |
| ru_RU      | 24       | 6.33%   |
| pt_BR      | 20       | 5.28%   |
| fr_FR      | 17       | 4.49%   |
| de_DE      | 17       | 4.49%   |
| en_AU      | 12       | 3.17%   |
| es_ES      | 10       | 2.64%   |
| en_CA      | 8        | 2.11%   |
| pl_PL      | 7        | 1.85%   |
| it_IT      | 6        | 1.58%   |
| es_MX      | 5        | 1.32%   |
| es_CO      | 5        | 1.32%   |
| cs_CZ      | 5        | 1.32%   |
| nl_BE      | 4        | 1.06%   |
| fr_CH      | 3        | 0.79%   |
| en_IE      | 3        | 0.79%   |
| tr_TR      | 2        | 0.53%   |
| ru_UA      | 2        | 0.53%   |
| nl_NL      | 2        | 0.53%   |
| hu_HU      | 2        | 0.53%   |
| es_CL      | 2        | 0.53%   |
| en_NZ      | 2        | 0.53%   |
| de_AT      | 2        | 0.53%   |
| C          | 2        | 0.53%   |
| ar_SA      | 2        | 0.53%   |
| Unknown    | 2        | 0.53%   |
| zh_CN      | 1        | 0.26%   |
| sv_SE      | 1        | 0.26%   |
| sr_RS      | 1        | 0.26%   |
| ro_RO      | 1        | 0.26%   |
| pt_PT      | 1        | 0.26%   |
| pa_IN      | 1        | 0.26%   |
| nb_NO      | 1        | 0.26%   |
| ja_JP      | 1        | 0.26%   |
| fr_BE      | 1        | 0.26%   |
| fi_FI      | 1        | 0.26%   |
| es_VE      | 1        | 0.26%   |
| en_US.UTF8 | 1        | 0.26%   |
| en_IN      | 1        | 0.26%   |
| en_IL      | 1        | 0.26%   |
| el_GR      | 1        | 0.26%   |
| de_CH      | 1        | 0.26%   |
| ca_ES      | 1        | 0.26%   |
| bs_BA      | 1        | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 256      | 67.19%  |
| BIOS | 125      | 32.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 262      | 68.77%  |
| Ext4    | 99       | 25.98%  |
| Xfs     | 17       | 4.46%   |
| Overlay | 2        | 0.52%   |
| Ext3    | 1        | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 212      | 55.5%   |
| GPT     | 141      | 36.91%  |
| MBR     | 29       | 7.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 328      | 86.32%  |
| Yes       | 52       | 13.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 299      | 77.66%  |
| Yes       | 86       | 22.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 106      | 28.12%  |
| Gigabyte Technology | 93       | 24.67%  |
| MSI                 | 68       | 18.04%  |
| Dell                | 29       | 7.69%   |
| ASRock              | 23       | 6.1%    |
| Hewlett-Packard     | 14       | 3.71%   |
| Lenovo              | 12       | 3.18%   |
| Fujitsu             | 4        | 1.06%   |
| Intel               | 3        | 0.8%    |
| ECS                 | 3        | 0.8%    |
| XFX                 | 2        | 0.53%   |
| Supermicro          | 2        | 0.53%   |
| Gateway             | 2        | 0.53%   |
| BESSTAR Tech        | 2        | 0.53%   |
| Apple               | 2        | 0.53%   |
| ABIT                | 2        | 0.53%   |
| Seco                | 1        | 0.27%   |
| Pegatron            | 1        | 0.27%   |
| PCWare              | 1        | 0.27%   |
| MACHINIST           | 1        | 0.27%   |
| JINGSHA             | 1        | 0.27%   |
| Huanan              | 1        | 0.27%   |
| Foxconn             | 1        | 0.27%   |
| Biostar             | 1        | 0.27%   |
| Acer                | 1        | 0.27%   |
| AAEON               | 1        | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 8        | 2.12%   |
| MSI MS-7C56                      | 5        | 1.33%   |
| Gigabyte B450M DS3H              | 4        | 1.06%   |
| ASUS ROG CROSSHAIR VII HERO      | 4        | 1.06%   |
| MSI MS-7D25                      | 3        | 0.8%    |
| MSI MS-7C84                      | 3        | 0.8%    |
| MSI MS-7C37                      | 3        | 0.8%    |
| MSI MS-7B93                      | 3        | 0.8%    |
| MSI MS-7B89                      | 3        | 0.8%    |
| MSI MS-7B86                      | 3        | 0.8%    |
| MSI MS-7B79                      | 3        | 0.8%    |
| Gigabyte X570 AORUS MASTER       | 3        | 0.8%    |
| Gigabyte B450 AORUS M            | 3        | 0.8%    |
| Dell Precision T3600             | 3        | 0.8%    |
| Dell OptiPlex 7010               | 3        | 0.8%    |
| ASUS ROG STRIX B550-I GAMING     | 3        | 0.8%    |
| ASUS ROG STRIX B550-F GAMING     | 3        | 0.8%    |
| ASUS ROG STRIX B450-F GAMING     | 3        | 0.8%    |
| MSI MS-7C95                      | 2        | 0.53%   |
| MSI MS-7C94                      | 2        | 0.53%   |
| MSI MS-7C91                      | 2        | 0.53%   |
| MSI MS-7C52                      | 2        | 0.53%   |
| MSI MS-7B85                      | 2        | 0.53%   |
| MSI MS-7B10                      | 2        | 0.53%   |
| MSI MS-7A34                      | 2        | 0.53%   |
| MSI MS-7A33                      | 2        | 0.53%   |
| Gigabyte Z690 UD DDR4            | 2        | 0.53%   |
| Gigabyte Z390 I AORUS PRO WIFI   | 2        | 0.53%   |
| Gigabyte Z390 AORUS MASTER       | 2        | 0.53%   |
| Gigabyte H97M-D3H                | 2        | 0.53%   |
| Gigabyte GB-BRR7H-4800           | 2        | 0.53%   |
| Gigabyte B450 AORUS ELITE        | 2        | 0.53%   |
| Gigabyte AB350-Gaming 3          | 2        | 0.53%   |
| Dell OptiPlex 3020               | 2        | 0.53%   |
| ASUS Z170 PRO GAMING             | 2        | 0.53%   |
| ASUS TUF GAMING B550M-PLUS       | 2        | 0.53%   |
| ASUS TUF GAMING B550-PLUS        | 2        | 0.53%   |
| ASUS ROG Maximus XI HERO         | 2        | 0.53%   |
| ASUS ROG Maximus XI FORMULA      | 2        | 0.53%   |
| ASUS ROG CROSSHAIR VIII HERO     | 2        | 0.53%   |
| ASUS PRIME Z370-P                | 2        | 0.53%   |
| ASUS PRIME B450M-A               | 2        | 0.53%   |
| ASRock G41M-VS3                  | 2        | 0.53%   |
| ASRock B450 Pro4                 | 2        | 0.53%   |
| Apple MacPro5,1                  | 2        | 0.53%   |
| XFX nForce 780i 3-Way SLI        | 1        | 0.27%   |
| XFX MI-A78S-8209 Ver1.1          | 1        | 0.27%   |
| Supermicro X9DRW                 | 1        | 0.27%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 0.27%   |
| Seco C40                         | 1        | 0.27%   |
| Pegatron h9-1350                 | 1        | 0.27%   |
| PCWare IPMH110G                  | 1        | 0.27%   |
| MSI PPPPP-CCC#MMMMMMMM           | 1        | 0.27%   |
| MSI MS-7C96                      | 1        | 0.27%   |
| MSI MS-7C92                      | 1        | 0.27%   |
| MSI MS-7C35                      | 1        | 0.27%   |
| MSI MS-7C31                      | 1        | 0.27%   |
| MSI MS-7C02                      | 1        | 0.27%   |
| MSI MS-7B98                      | 1        | 0.27%   |
| MSI MS-7B77                      | 1        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS ROG                         | 33       | 8.75%   |
| ASUS PRIME                       | 23       | 6.1%    |
| Dell OptiPlex                    | 17       | 4.51%   |
| ASUS TUF                         | 11       | 2.92%   |
| Lenovo ThinkCentre               | 8        | 2.12%   |
| Gigabyte X570                    | 8        | 2.12%   |
| ASUS All                         | 8        | 2.12%   |
| Dell Precision                   | 6        | 1.59%   |
| MSI MS-7C56                      | 5        | 1.33%   |
| Gigabyte Z390                    | 5        | 1.33%   |
| Gigabyte B450                    | 5        | 1.33%   |
| Gigabyte B550                    | 4        | 1.06%   |
| Gigabyte B450M                   | 4        | 1.06%   |
| ASUS Maximus                     | 4        | 1.06%   |
| MSI MS-7D25                      | 3        | 0.8%    |
| MSI MS-7C84                      | 3        | 0.8%    |
| MSI MS-7C37                      | 3        | 0.8%    |
| MSI MS-7B93                      | 3        | 0.8%    |
| MSI MS-7B89                      | 3        | 0.8%    |
| MSI MS-7B86                      | 3        | 0.8%    |
| MSI MS-7B79                      | 3        | 0.8%    |
| HP EliteDesk                     | 3        | 0.8%    |
| HP Compaq                        | 3        | 0.8%    |
| Fujitsu ESPRIMO                  | 3        | 0.8%    |
| Dell XPS                         | 3        | 0.8%    |
| ASUS M5A97                       | 3        | 0.8%    |
| MSI MS-7C95                      | 2        | 0.53%   |
| MSI MS-7C94                      | 2        | 0.53%   |
| MSI MS-7C91                      | 2        | 0.53%   |
| MSI MS-7C52                      | 2        | 0.53%   |
| MSI MS-7B85                      | 2        | 0.53%   |
| MSI MS-7B10                      | 2        | 0.53%   |
| MSI MS-7A34                      | 2        | 0.53%   |
| MSI MS-7A33                      | 2        | 0.53%   |
| HP ProDesk                       | 2        | 0.53%   |
| Gigabyte Z690                    | 2        | 0.53%   |
| Gigabyte TRX40                   | 2        | 0.53%   |
| Gigabyte H97M-D3H                | 2        | 0.53%   |
| Gigabyte GB-BRR7H-4800           | 2        | 0.53%   |
| Gigabyte G1.Sniper               | 2        | 0.53%   |
| Gigabyte AB350-Gaming            | 2        | 0.53%   |
| Dell G5                          | 2        | 0.53%   |
| ASUS Z170                        | 2        | 0.53%   |
| ASUS P8Z77-V                     | 2        | 0.53%   |
| ASUS M5A78L-M                    | 2        | 0.53%   |
| ASRock X570                      | 2        | 0.53%   |
| ASRock G41M-VS3                  | 2        | 0.53%   |
| ASRock B550                      | 2        | 0.53%   |
| ASRock B450                      | 2        | 0.53%   |
| Apple MacPro5                    | 2        | 0.53%   |
| XFX nForce                       | 1        | 0.27%   |
| XFX MI-A78S-8209                 | 1        | 0.27%   |
| Supermicro X9DRW                 | 1        | 0.27%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 0.27%   |
| Seco C40                         | 1        | 0.27%   |
| Pegatron h9-1350                 | 1        | 0.27%   |
| PCWare IPMH110G                  | 1        | 0.27%   |
| MSI PPPPP-CCC#MMMMMMMM           | 1        | 0.27%   |
| MSI MS-7C96                      | 1        | 0.27%   |
| MSI MS-7C92                      | 1        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 55       | 14.59%  |
| 2018 | 51       | 13.53%  |
| 2019 | 47       | 12.47%  |
| 2021 | 35       | 9.28%   |
| 2014 | 31       | 8.22%   |
| 2017 | 29       | 7.69%   |
| 2013 | 28       | 7.43%   |
| 2012 | 19       | 5.04%   |
| 2011 | 16       | 4.24%   |
| 2010 | 16       | 4.24%   |
| 2016 | 15       | 3.98%   |
| 2015 | 14       | 3.71%   |
| 2009 | 8        | 2.12%   |
| 2008 | 8        | 2.12%   |
| 2007 | 2        | 0.53%   |
| 2006 | 2        | 0.53%   |
| 2022 | 1        | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 377      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 357      | 94.44%  |
| Enabled  | 21       | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 377      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 118      | 31.13%  |
| 32.01-64.0  | 90       | 23.75%  |
| 8.01-16.0   | 60       | 15.83%  |
| 4.01-8.0    | 40       | 10.55%  |
| 64.01-256.0 | 35       | 9.23%   |
| 3.01-4.0    | 24       | 6.33%   |
| 24.01-32.0  | 9        | 2.37%   |
| 2.01-3.0    | 2        | 0.53%   |
| 1.01-2.0    | 1        | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 119      | 28.47%  |
| 4.01-8.0   | 109      | 26.08%  |
| 3.01-4.0   | 77       | 18.42%  |
| 1.01-2.0   | 51       | 12.2%   |
| 8.01-16.0  | 37       | 8.85%   |
| 0.51-1.0   | 9        | 2.15%   |
| 16.01-24.0 | 8        | 1.91%   |
| 24.01-32.0 | 6        | 1.44%   |
| 32.01-64.0 | 1        | 0.24%   |
| 0.01-0.5   | 1        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 121      | 31.51%  |
| 1      | 97       | 25.26%  |
| 3      | 84       | 21.88%  |
| 4      | 34       | 8.85%   |
| 5      | 23       | 5.99%   |
| 6      | 13       | 3.39%   |
| 7      | 8        | 2.08%   |
| 8      | 2        | 0.52%   |
| 14     | 1        | 0.26%   |
| 9      | 1        | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 258      | 68.07%  |
| Yes       | 121      | 31.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 376      | 99.47%  |
| No        | 2        | 0.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 51.72%  |
| Yes       | 182      | 48.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 209      | 55%     |
| Yes       | 171      | 45%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 77       | 20.37%  |
| Russia       | 26       | 6.88%   |
| Germany      | 25       | 6.61%   |
| Brazil       | 24       | 6.35%   |
| France       | 21       | 5.56%   |
| UK           | 17       | 4.5%    |
| Spain        | 15       | 3.97%   |
| Canada       | 14       | 3.7%    |
| Australia    | 14       | 3.7%    |
| Poland       | 12       | 3.17%   |
| Czechia      | 9        | 2.38%   |
| Netherlands  | 8        | 2.12%   |
| Belgium      | 8        | 2.12%   |
| Ukraine      | 7        | 1.85%   |
| Switzerland  | 7        | 1.85%   |
| Italy        | 7        | 1.85%   |
| Mexico       | 6        | 1.59%   |
| India        | 6        | 1.59%   |
| Turkey       | 5        | 1.32%   |
| Sweden       | 5        | 1.32%   |
| Romania      | 5        | 1.32%   |
| Colombia     | 5        | 1.32%   |
| Austria      | 5        | 1.32%   |
| Norway       | 4        | 1.06%   |
| Hong Kong    | 4        | 1.06%   |
| Belarus      | 4        | 1.06%   |
| Ireland      | 3        | 0.79%   |
| Indonesia    | 3        | 0.79%   |
| Hungary      | 3        | 0.79%   |
| Greece       | 3        | 0.79%   |
| Chile        | 3        | 0.79%   |
| Saudi Arabia | 2        | 0.53%   |
| Kyrgyzstan   | 2        | 0.53%   |
| Israel       | 2        | 0.53%   |
| Yemen        | 1        | 0.26%   |
| Venezuela    | 1        | 0.26%   |
| Thailand     | 1        | 0.26%   |
| Slovenia     | 1        | 0.26%   |
| Slovakia     | 1        | 0.26%   |
| New Zealand  | 1        | 0.26%   |
| Moldova      | 1        | 0.26%   |
| Latvia       | 1        | 0.26%   |
| Kuwait       | 1        | 0.26%   |
| Kazakhstan   | 1        | 0.26%   |
| Japan        | 1        | 0.26%   |
| Estonia      | 1        | 0.26%   |
| Egypt        | 1        | 0.26%   |
| Cyprus       | 1        | 0.26%   |
| Bulgaria     | 1        | 0.26%   |
| Bolivia      | 1        | 0.26%   |
| Argentina    | 1        | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Sydney            | 8        | 2.04%   |
| Moscow            | 8        | 2.04%   |
| Berlin            | 6        | 1.53%   |
| Vienna            | 5        | 1.27%   |
| Madrid            | 4        | 1.02%   |
| Warsaw            | 3        | 0.76%   |
| Minsk             | 3        | 0.76%   |
| Kyiv              | 3        | 0.76%   |
| Istanbul          | 3        | 0.76%   |
| Amsterdam         | 3        | 0.76%   |
| Zurich            | 2        | 0.51%   |
| Yekaterinburg     | 2        | 0.51%   |
| Weinsberg         | 2        | 0.51%   |
| Villavicencio     | 2        | 0.51%   |
| Ufa               | 2        | 0.51%   |
| TimiÈ™oara     | 2        | 0.51%   |
| St Petersburg     | 2        | 0.51%   |
| Sautron           | 2        | 0.51%   |
| Sao Paulo         | 2        | 0.51%   |
| Rome              | 2        | 0.51%   |
| Rio de Janeiro    | 2        | 0.51%   |
| Raleigh           | 2        | 0.51%   |
| Pompano Beach     | 2        | 0.51%   |
| Pennsville        | 2        | 0.51%   |
| Paris             | 2        | 0.51%   |
| Louisville        | 2        | 0.51%   |
| Los Angeles       | 2        | 0.51%   |
| London            | 2        | 0.51%   |
| Krakow            | 2        | 0.51%   |
| Jakarta           | 2        | 0.51%   |
| Houston           | 2        | 0.51%   |
| Hamburg           | 2        | 0.51%   |
| Dublin            | 2        | 0.51%   |
| Dallas            | 2        | 0.51%   |
| Brussels          | 2        | 0.51%   |
| Brno              | 2        | 0.51%   |
| Brisbane          | 2        | 0.51%   |
| BrasÃ­lia       | 2        | 0.51%   |
| Bishkek           | 2        | 0.51%   |
| Bainbridge Island | 2        | 0.51%   |
| Athens            | 2        | 0.51%   |
| Ankara            | 2        | 0.51%   |
| Aix-en-Provence   | 2        | 0.51%   |
| ZlÃ­n           | 1        | 0.25%   |
| Zheleznogorsk     | 1        | 0.25%   |
| Zgorzelec         | 1        | 0.25%   |
| Zeven             | 1        | 0.25%   |
| Zaratamo          | 1        | 0.25%   |
| Zaporizhzhya      | 1        | 0.25%   |
| Zapopan           | 1        | 0.25%   |
| Yverdon-les-Bains | 1        | 0.25%   |
| Winterthur        | 1        | 0.25%   |
| Windsor           | 1        | 0.25%   |
| Winchester        | 1        | 0.25%   |
| Wilmington        | 1        | 0.25%   |
| Willowbrook       | 1        | 0.25%   |
| Wigan             | 1        | 0.25%   |
| Westerronfeld     | 1        | 0.25%   |
| Waynesville       | 1        | 0.25%   |
| Wateringen        | 1        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 146      | 271    | 19.01%  |
| Seagate                     | 129      | 219    | 16.8%   |
| WDC                         | 128      | 215    | 16.67%  |
| Kingston                    | 52       | 64     | 6.77%   |
| Crucial                     | 49       | 58     | 6.38%   |
| SanDisk                     | 40       | 48     | 5.21%   |
| Toshiba                     | 34       | 47     | 4.43%   |
| A-DATA Technology           | 19       | 25     | 2.47%   |
| Phison                      | 18       | 27     | 2.34%   |
| Hitachi                     | 17       | 20     | 2.21%   |
| Intel                       | 16       | 21     | 2.08%   |
| SPCC                        | 11       | 14     | 1.43%   |
| Patriot                     | 8        | 10     | 1.04%   |
| Silicon Motion              | 7        | 7      | 0.91%   |
| Corsair                     | 7        | 8      | 0.91%   |
| XPG                         | 6        | 8      | 0.78%   |
| Unknown                     | 6        | 8      | 0.78%   |
| HGST                        | 5        | 10     | 0.65%   |
| SABRENT                     | 4        | 4      | 0.52%   |
| Micron/Crucial Technology   | 4        | 5      | 0.52%   |
| GOODRAM                     | 4        | 4      | 0.52%   |
| China                       | 4        | 5      | 0.52%   |
| SK Hynix                    | 3        | 3      | 0.39%   |
| Realtek Semiconductor       | 3        | 3      | 0.39%   |
| Lexar                       | 3        | 4      | 0.39%   |
| KingSpec                    | 3        | 3      | 0.39%   |
| Hewlett-Packard             | 3        | 3      | 0.39%   |
| Verbatim                    | 2        | 2      | 0.26%   |
| SSK                         | 2        | 2      | 0.26%   |
| PNY                         | 2        | 3      | 0.26%   |
| OCZ                         | 2        | 2      | 0.26%   |
| Micron Technology           | 2        | 3      | 0.26%   |
| MAXTOR                      | 2        | 2      | 0.26%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.26%   |
| Intenso                     | 2        | 5      | 0.26%   |
| Apacer                      | 2        | 3      | 0.26%   |
| USB 3.0                     | 1        | 2      | 0.13%   |
| Transcend                   | 1        | 1      | 0.13%   |
| Team                        | 1        | 2      | 0.13%   |
| T-FORCE                     | 1        | 1      | 0.13%   |
| SUNEAST                     | 1        | 1      | 0.13%   |
| sobetter                    | 1        | 1      | 0.13%   |
| PLEXTOR                     | 1        | 1      | 0.13%   |
| OWC                         | 1        | 1      | 0.13%   |
| Mushkin                     | 1        | 1      | 0.13%   |
| MaxDigital                  | 1        | 1      | 0.13%   |
| LS600                       | 1        | 1      | 0.13%   |
| LITEON                      | 1        | 2      | 0.13%   |
| LDLC                        | 1        | 2      | 0.13%   |
| KIOXIA                      | 1        | 2      | 0.13%   |
| HS-SSD-C100                 | 1        | 1      | 0.13%   |
| Gigabyte Technology         | 1        | 2      | 0.13%   |
| Dahua                       | 1        | 1      | 0.13%   |
| BIWIN                       | 1        | 1      | 0.13%   |
| ASMT                        | 1        | 1      | 0.13%   |
| AMD                         | 1        | 2      | 0.13%   |
| Unknown                     | 1        | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB     | 24       | 2.56%   |
| Samsung SSD 860 EVO 500GB        | 17       | 1.82%   |
| Seagate ST2000DM008-2FR102 2TB   | 13       | 1.39%   |
| Seagate ST1000DM010-2EP102 1TB   | 11       | 1.18%   |
| Samsung SSD 860 EVO 1TB          | 9        | 0.96%   |
| Samsung SSD 850 EVO 500GB        | 9        | 0.96%   |
| Samsung NVMe SSD Drive 1TB       | 9        | 0.96%   |
| Kingston SA400S37480G 480GB SSD  | 9        | 0.96%   |
| Kingston SA400S37240G 240GB SSD  | 9        | 0.96%   |
| Crucial CT1000MX500SSD1 1TB      | 9        | 0.96%   |
| Seagate ST500DM002-1BD142 500GB  | 8        | 0.85%   |
| Seagate ST4000DM004-2CV104 4TB   | 8        | 0.85%   |
| Seagate ST3500418AS 500GB        | 8        | 0.85%   |
| Samsung SSD 850 EVO 250GB        | 8        | 0.85%   |
| Seagate ST1000DM003-1ER162 1TB   | 7        | 0.75%   |
| Sandisk NVMe SSD Drive 1TB       | 7        | 0.75%   |
| Samsung SSD 970 EVO Plus 500GB   | 7        | 0.75%   |
| Samsung SSD 970 EVO Plus 1TB     | 7        | 0.75%   |
| Kingston SV300S37A120G 120GB SSD | 7        | 0.75%   |
| Crucial CT500MX500SSD1 500GB     | 7        | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 6        | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB   | 6        | 0.64%   |
| Sandisk NVMe SSD Drive 500GB     | 6        | 0.64%   |
| Samsung NVMe SSD Drive 250GB     | 6        | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 5        | 0.53%   |
| WDC WD30EFRX-68EUZN0 3TB         | 5        | 0.53%   |
| WDC WD10EZEX-00WN4A0 1TB         | 5        | 0.53%   |
| Toshiba HDWD110 1TB              | 5        | 0.53%   |
| Samsung SSD 970 EVO 250GB        | 5        | 0.53%   |
| Samsung SSD 870 EVO 500GB        | 5        | 0.53%   |
| Samsung SSD 870 EVO 1TB          | 5        | 0.53%   |
| Samsung SSD 860 EVO 250GB        | 5        | 0.53%   |
| Samsung NVMe SSD Drive 2TB       | 5        | 0.53%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 4        | 0.43%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 4        | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 0.43%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 4        | 0.43%   |
| Toshiba HDWD120 2TB              | 4        | 0.43%   |
| Toshiba DT01ACA050 500GB         | 4        | 0.43%   |
| Seagate ST8000DM004-2CX188 8TB   | 4        | 0.43%   |
| Samsung SSD 970 EVO Plus 2TB     | 4        | 0.43%   |
| Phison Sabrent 1TB               | 4        | 0.43%   |
| Phison NVMe SSD Drive 2TB        | 4        | 0.43%   |
| Kingston SUV400S37240G 240GB SSD | 4        | 0.43%   |
| Kingston SA2000M81000G 1TB       | 4        | 0.43%   |
| Crucial CT480BX500SSD1 480GB     | 4        | 0.43%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 3        | 0.32%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 3        | 0.32%   |
| WDC WD5000AADS-00S9B0 500GB      | 3        | 0.32%   |
| WDC WD20EZRX-00D8PB0 2TB         | 3        | 0.32%   |
| WDC WD10EZRX-00L4HB0 1TB         | 3        | 0.32%   |
| WDC WD10EZEX-22MFCA0 1TB         | 3        | 0.32%   |
| Toshiba TR200 240GB SSD          | 3        | 0.32%   |
| SPCC Solid State Disk 256GB      | 3        | 0.32%   |
| Seagate ST4000DM005-2DP166 4TB   | 3        | 0.32%   |
| Seagate ST31000528AS 1TB         | 3        | 0.32%   |
| Seagate ST3000DM008-2DM166 3TB   | 3        | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB   | 3        | 0.32%   |
| SanDisk SSD PLUS 240GB           | 3        | 0.32%   |
| Samsung SSD 980 PRO 1TB          | 3        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 124      | 209    | 42.61%  |
| WDC                 | 99       | 168    | 34.02%  |
| Toshiba             | 28       | 37     | 9.62%   |
| Hitachi             | 17       | 20     | 5.84%   |
| Samsung Electronics | 9        | 13     | 3.09%   |
| HGST                | 5        | 10     | 1.72%   |
| SABRENT             | 3        | 3      | 1.03%   |
| MAXTOR              | 2        | 2      | 0.69%   |
| USB 3.0             | 1        | 2      | 0.34%   |
| MaxDigital          | 1        | 1      | 0.34%   |
| Hewlett-Packard     | 1        | 1      | 0.34%   |
| ASMT                | 1        | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 82       | 142    | 27.06%  |
| Kingston            | 41       | 50     | 13.53%  |
| Crucial             | 41       | 48     | 13.53%  |
| WDC                 | 27       | 35     | 8.91%   |
| SanDisk             | 24       | 26     | 7.92%   |
| A-DATA Technology   | 15       | 20     | 4.95%   |
| SPCC                | 8        | 10     | 2.64%   |
| Intel               | 8        | 9      | 2.64%   |
| Patriot             | 7        | 9      | 2.31%   |
| Toshiba             | 5        | 6      | 1.65%   |
| GOODRAM             | 4        | 4      | 1.32%   |
| China               | 4        | 5      | 1.32%   |
| KingSpec            | 3        | 3      | 0.99%   |
| Corsair             | 3        | 4      | 0.99%   |
| Verbatim            | 2        | 2      | 0.66%   |
| PNY                 | 2        | 3      | 0.66%   |
| OCZ                 | 2        | 2      | 0.66%   |
| Lexar               | 2        | 2      | 0.66%   |
| Intenso             | 2        | 5      | 0.66%   |
| Apacer              | 2        | 3      | 0.66%   |
| XPG                 | 1        | 2      | 0.33%   |
| Unknown             | 1        | 1      | 0.33%   |
| Transcend           | 1        | 1      | 0.33%   |
| Team                | 1        | 2      | 0.33%   |
| T-FORCE             | 1        | 1      | 0.33%   |
| SUNEAST             | 1        | 1      | 0.33%   |
| Seagate             | 1        | 2      | 0.33%   |
| SABRENT             | 1        | 1      | 0.33%   |
| PLEXTOR             | 1        | 1      | 0.33%   |
| OWC                 | 1        | 1      | 0.33%   |
| Mushkin             | 1        | 1      | 0.33%   |
| Micron Technology   | 1        | 1      | 0.33%   |
| LS600               | 1        | 1      | 0.33%   |
| LITEON              | 1        | 2      | 0.33%   |
| HS-SSD-C100         | 1        | 1      | 0.33%   |
| Hewlett-Packard     | 1        | 1      | 0.33%   |
| Dahua               | 1        | 1      | 0.33%   |
| BIWIN               | 1        | 1      | 0.33%   |
| AMD                 | 1        | 2      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 243      | 412    | 37.04%  |
| HDD     | 237      | 467    | 36.13%  |
| NVMe    | 158      | 263    | 24.09%  |
| Unknown | 15       | 21     | 2.29%   |
| MMC     | 3        | 3      | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 327      | 867    | 63.62%  |
| NVMe | 158      | 263    | 30.74%  |
| SAS  | 26       | 33     | 5.06%   |
| MMC  | 3        | 3      | 0.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 243      | 417    | 45%     |
| 0.51-1.0   | 158      | 248    | 29.26%  |
| 1.01-2.0   | 64       | 84     | 11.85%  |
| 3.01-4.0   | 34       | 50     | 6.3%    |
| 4.01-10.0  | 19       | 32     | 3.52%   |
| 2.01-3.0   | 17       | 40     | 3.15%   |
| 10.01-20.0 | 5        | 8      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 80       | 20.62%  |
| 501-1000       | 76       | 19.59%  |
| 251-500        | 60       | 15.46%  |
| More than 3000 | 58       | 14.95%  |
| 101-250        | 41       | 10.57%  |
| 2001-3000      | 30       | 7.73%   |
| 1-20           | 21       | 5.41%   |
| Unknown        | 12       | 3.09%   |
| 51-100         | 8        | 2.06%   |
| 21-50          | 2        | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 74       | 18.36%  |
| 251-500        | 54       | 13.4%   |
| 501-1000       | 53       | 13.15%  |
| 101-250        | 50       | 12.41%  |
| 21-50          | 48       | 11.91%  |
| 51-100         | 41       | 10.17%  |
| 1001-2000      | 35       | 8.68%   |
| More than 3000 | 20       | 4.96%   |
| 2001-3000      | 16       | 3.97%   |
| Unknown        | 12       | 2.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Desktops | Drives | Percent |
|-----------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 5        | 10     | 9.43%   |
| Seagate ST3500418AS 500GB                           | 3        | 4      | 5.66%   |
| Samsung Electronics SSD 870 EVO 500GB               | 2        | 2      | 3.77%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1        | 1      | 1.89%   |
| WDC WD5000AAKS-00UU3A0 500GB                        | 1        | 1      | 1.89%   |
| WDC WD3200BEVT-24A23T0 320GB                        | 1        | 1      | 1.89%   |
| WDC WD30EZRX-00MMMB0 3TB                            | 1        | 1      | 1.89%   |
| WDC WD2500AAKX-753CA1 250GB                         | 1        | 1      | 1.89%   |
| WDC WD15EARS-00S0XB0 1TB                            | 1        | 1      | 1.89%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1        | 1      | 1.89%   |
| WDC WD10EFRX-68JCSN0 1TB                            | 1        | 1      | 1.89%   |
| WDC WD10EALX-009BA0 1TB                             | 1        | 1      | 1.89%   |
| WDC WD1003FBYX-01Y7B1 1TB                           | 1        | 1      | 1.89%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 1        | 1      | 1.89%   |
| Toshiba MK6476GSX 640GB                             | 1        | 1      | 1.89%   |
| Team T2535T480G 480GB SSD                           | 1        | 2      | 1.89%   |
| Seagate ST9750420AS 752GB                           | 1        | 1      | 1.89%   |
| Seagate ST9500325AS 500GB                           | 1        | 1      | 1.89%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1        | 1      | 1.89%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB                | 1        | 1      | 1.89%   |
| Seagate ST500DM009-2F110A 500GB                     | 1        | 1      | 1.89%   |
| Seagate ST3500630AS 500GB                           | 1        | 1      | 1.89%   |
| Seagate ST3200822A 200GB                            | 1        | 1      | 1.89%   |
| Seagate ST31000528AS 1TB                            | 1        | 1      | 1.89%   |
| Seagate ST31000524AS 1TB                            | 1        | 1      | 1.89%   |
| Seagate ST3000DM001-1ER166 3TB                      | 1        | 1      | 1.89%   |
| Seagate ST3000DM001-1CH166 3TB                      | 1        | 3      | 1.89%   |
| Seagate ST2000DM001-1CH164 2TB                      | 1        | 1      | 1.89%   |
| Seagate ST2000DL003-9VT166 2TB                      | 1        | 1      | 1.89%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 1      | 1.89%   |
| Seagate ST1000DM003-1ER162 1TB                      | 1        | 1      | 1.89%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                 | 1        | 1      | 1.89%   |
| Samsung Electronics SSD 970 EVO 250GB               | 1        | 1      | 1.89%   |
| Samsung Electronics HD501LJ 500GB                   | 1        | 4      | 1.89%   |
| Samsung Electronics HD103UJ 1TB                     | 1        | 1      | 1.89%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1        | 1      | 1.89%   |
| MAXTOR 6Y080M0 81GB                                 | 1        | 1      | 1.89%   |
| Kingston SV300S37A240G 240GB SSD                    | 1        | 1      | 1.89%   |
| Kingston SV300S37A120G 120GB SSD                    | 1        | 1      | 1.89%   |
| Intel SSDSC2CT120A3 120GB                           | 1        | 2      | 1.89%   |
| Intel SSDPEKKW256G7 256GB                           | 1        | 1      | 1.89%   |
| Hitachi HDS5C3020ALA632 2TB                         | 1        | 1      | 1.89%   |
| Crucial CT240M500SSD1 240GB                         | 1        | 1      | 1.89%   |
| Crucial CT128MX100SSD1 128GB                        | 1        | 1      | 1.89%   |
| Corsair Force LS SSD 480GB                          | 1        | 1      | 1.89%   |
| A-DATA Technology SX8100NP 1TB                      | 1        | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 31     | 42.31%  |
| WDC                 | 11       | 11     | 21.15%  |
| Samsung Electronics | 5        | 8      | 9.62%   |
| Kingston            | 2        | 2      | 3.85%   |
| Intel               | 2        | 3      | 3.85%   |
| Crucial             | 2        | 2      | 3.85%   |
| Toshiba             | 1        | 1      | 1.92%   |
| Team                | 1        | 2      | 1.92%   |
| SanDisk             | 1        | 1      | 1.92%   |
| Micron Technology   | 1        | 1      | 1.92%   |
| MAXTOR              | 1        | 1      | 1.92%   |
| Hitachi             | 1        | 1      | 1.92%   |
| Corsair             | 1        | 1      | 1.92%   |
| A-DATA Technology   | 1        | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 31     | 59.46%  |
| WDC                 | 10       | 10     | 27.03%  |
| Samsung Electronics | 2        | 5      | 5.41%   |
| Toshiba             | 1        | 1      | 2.7%    |
| MAXTOR              | 1        | 1      | 2.7%    |
| Hitachi             | 1        | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 34       | 49     | 69.39%  |
| SSD  | 12       | 14     | 24.49%  |
| NVMe | 3        | 3      | 6.12%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 219      | 646    | 50.11%  |
| Works    | 170      | 454    | 38.9%   |
| Malfunc  | 48       | 66     | 10.98%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 204      | 33.72%  |
| AMD                          | 166      | 27.44%  |
| Samsung Electronics          | 76       | 12.56%  |
| Sandisk                      | 25       | 4.13%   |
| Phison Electronics           | 23       | 3.8%    |
| ASMedia Technology           | 19       | 3.14%   |
| Marvell Technology Group     | 13       | 2.15%   |
| Kingston Technology Company  | 13       | 2.15%   |
| Micron/Crucial Technology    | 12       | 1.98%   |
| JMicron Technology           | 9        | 1.49%   |
| Silicon Motion               | 8        | 1.32%   |
| ADATA Technology             | 8        | 1.32%   |
| Nvidia                       | 6        | 0.99%   |
| Realtek Semiconductor        | 4        | 0.66%   |
| SK Hynix                     | 3        | 0.5%    |
| Toshiba America Info Systems | 2        | 0.33%   |
| Silicon Image                | 2        | 0.33%   |
| Micron Technology            | 2        | 0.33%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.33%   |
| LSI Logic / Symbios Logic    | 2        | 0.33%   |
| KIOXIA                       | 2        | 0.33%   |
| VIA Technologies             | 1        | 0.17%   |
| ULi Electronics              | 1        | 0.17%   |
| Seagate Technology           | 1        | 0.17%   |
| Adaptec                      | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 107      | 14.72%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 53       | 7.29%   |
| AMD 400 Series Chipset SATA Controller                                                  | 43       | 5.91%   |
| AMD 500 Series Chipset SATA Controller                                                  | 31       | 4.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 28       | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 3.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 20       | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17       | 2.34%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 17       | 2.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15       | 2.06%   |
| Phison E12 NVMe Controller                                                              | 14       | 1.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11       | 1.51%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 1.38%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9        | 1.24%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 9        | 1.24%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 1.24%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8        | 1.1%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 8        | 1.1%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8        | 1.1%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 7        | 0.96%   |
| Samsung NVMe SSD Controller 980                                                         | 7        | 0.96%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 7        | 0.96%   |
| Kingston Company A2000 NVMe SSD                                                         | 7        | 0.96%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 0.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 0.96%   |
| AMD FCH IDE Controller                                                                  | 7        | 0.96%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 6        | 0.83%   |
| AMD FCH SATA Controller D                                                               | 6        | 0.83%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 5        | 0.69%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 5        | 0.69%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 5        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 0.69%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 5        | 0.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.69%   |
| AMD X370 Series Chipset SATA Controller                                                 | 5        | 0.69%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 0.55%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 0.55%   |
| Intel SSD 660P Series                                                                   | 4        | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.55%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 4        | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 0.41%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 3        | 0.41%   |
| Kingston Company KC2000 NVMe SSD                                                        | 3        | 0.41%   |
| JMicron JMB362 SATA Controller                                                          | 3        | 0.41%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.41%   |
| Intel SSD 600P Series                                                                   | 3        | 0.41%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 0.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.41%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.41%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.41%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2        | 0.28%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 2        | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 344      | 59.62%  |
| NVMe | 158      | 27.38%  |
| IDE  | 48       | 8.32%   |
| RAID | 20       | 3.47%   |
| SAS  | 7        | 1.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 204      | 54.11%  |
| AMD    | 173      | 45.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 12       | 3.18%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 9        | 2.39%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 9        | 2.39%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 9        | 2.39%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 8        | 2.12%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 8        | 2.12%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 8        | 2.12%   |
| AMD Ryzen 5 3600 6-Core Processor           | 8        | 2.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 1.86%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 6        | 1.59%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 6        | 1.59%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 1.33%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 5        | 1.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.06%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.06%   |
| Intel 12th Gen Core i5-12600K               | 4        | 1.06%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 1.06%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 4        | 1.06%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 4        | 1.06%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 1.06%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 1.06%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.8%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.8%    |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.8%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3        | 0.8%    |
| Intel Core i5-7600K CPU @ 3.80GHz           | 3        | 0.8%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.8%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.8%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.8%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.8%    |
| Intel 12th Gen Core i9-12900K               | 3        | 0.8%    |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 3        | 0.8%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 0.8%    |
| AMD Ryzen 3 1200 Quad-Core Processor        | 3        | 0.8%    |
| Intel Xeon CPU X5680 @ 3.33GHz              | 2        | 0.53%   |
| Intel Xeon CPU E5-2673 v3 @ 2.40GHz         | 2        | 0.53%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 2        | 0.53%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 2        | 0.53%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.53%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.53%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.53%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 0.53%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.53%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.53%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.53%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.53%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2        | 0.53%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.53%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.53%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 0.53%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2        | 0.53%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.53%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 0.53%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 2        | 0.53%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 0.53%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 2        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 67       | 17.77%  |
| Intel Core i7           | 54       | 14.32%  |
| AMD Ryzen 5             | 49       | 13%     |
| AMD Ryzen 7             | 44       | 11.67%  |
| AMD Ryzen 9             | 25       | 6.63%   |
| Intel Xeon              | 19       | 5.04%   |
| Intel Core i3           | 17       | 4.51%   |
| Other                   | 14       | 3.71%   |
| Intel Core i9           | 12       | 3.18%   |
| Intel Core 2 Duo        | 8        | 2.12%   |
| AMD Ryzen 3             | 8        | 2.12%   |
| AMD FX                  | 8        | 2.12%   |
| AMD Ryzen Threadripper  | 5        | 1.33%   |
| Intel Pentium           | 4        | 1.06%   |
| AMD A4                  | 4        | 1.06%   |
| AMD A10                 | 4        | 1.06%   |
| Intel Core 2 Quad       | 3        | 0.8%    |
| AMD Phenom              | 3        | 0.8%    |
| AMD Athlon              | 3        | 0.8%    |
| AMD A6                  | 3        | 0.8%    |
| Intel Pentium Dual-Core | 2        | 0.53%   |
| AMD Phenom II X4        | 2        | 0.53%   |
| AMD Phenom II X2        | 2        | 0.53%   |
| AMD Athlon X4           | 2        | 0.53%   |
| AMD Athlon II X2        | 2        | 0.53%   |
| AMD Athlon 64 X2        | 2        | 0.53%   |
| AMD A8                  | 2        | 0.53%   |
| Intel Pentium Gold      | 1        | 0.27%   |
| Intel Core 2 Extreme    | 1        | 0.27%   |
| Intel Celeron           | 1        | 0.27%   |
| Intel Atom              | 1        | 0.27%   |
| AMD Ryzen Embedded      | 1        | 0.27%   |
| AMD Ryzen 7 PRO         | 1        | 0.27%   |
| AMD Ryzen 3 PRO         | 1        | 0.27%   |
| AMD Phenom II X6        | 1        | 0.27%   |
| AMD Athlon X2           | 1        | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 128      | 33.95%  |
| 6      | 82       | 21.75%  |
| 8      | 62       | 16.45%  |
| 2      | 51       | 13.53%  |
| 12     | 19       | 5.04%   |
| 16     | 16       | 4.24%   |
| 10     | 7        | 1.86%   |
| 1      | 5        | 1.33%   |
| 24     | 3        | 0.8%    |
| 3      | 3        | 0.8%    |
| 32     | 1        | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 374      | 99.2%   |
| 2      | 3        | 0.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 261      | 69.05%  |
| 1      | 117      | 30.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 377      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 34       | 8.95%   |
| 0x08701021 | 31       | 8.16%   |
| Unknown    | 27       | 7.11%   |
| 0x906ea    | 18       | 4.74%   |
| 0x306a9    | 17       | 4.47%   |
| 0x206a7    | 15       | 3.95%   |
| 0x0a201016 | 15       | 3.95%   |
| 0x506e3    | 13       | 3.42%   |
| 0x0a201009 | 12       | 3.16%   |
| 0x0800820d | 12       | 3.16%   |
| 0x906ed    | 11       | 2.89%   |
| 0x906e9    | 10       | 2.63%   |
| 0x08001138 | 10       | 2.63%   |
| 0x90672    | 8        | 2.11%   |
| 0x1067a    | 8        | 2.11%   |
| 0xa0653    | 6        | 1.58%   |
| 0x906ec    | 6        | 1.58%   |
| 0x306f2    | 6        | 1.58%   |
| 0x0a50000c | 6        | 1.58%   |
| 0x08701013 | 6        | 1.58%   |
| 0x0800820b | 6        | 1.58%   |
| 0x06001119 | 6        | 1.58%   |
| 0xa0655    | 5        | 1.32%   |
| 0x10676    | 5        | 1.32%   |
| 0x08108109 | 5        | 1.32%   |
| 0x08008206 | 5        | 1.32%   |
| 0x08001137 | 5        | 1.32%   |
| 0x06003106 | 5        | 1.32%   |
| 0xa0671    | 4        | 1.05%   |
| 0x206d7    | 4        | 1.05%   |
| 0x08101016 | 4        | 1.05%   |
| 0x106a5    | 3        | 0.79%   |
| 0x0810100b | 3        | 0.79%   |
| 0x010000b6 | 3        | 0.79%   |
| 0x00000000 | 3        | 0.79%   |
| 0x306e4    | 2        | 0.53%   |
| 0x206c2    | 2        | 0.53%   |
| 0x20655    | 2        | 0.53%   |
| 0x08600103 | 2        | 0.53%   |
| 0x06000822 | 2        | 0.53%   |
| 0x906eb    | 1        | 0.26%   |
| 0x806e9    | 1        | 0.26%   |
| 0x6fb      | 1        | 0.26%   |
| 0x40671    | 1        | 0.26%   |
| 0x20652    | 1        | 0.26%   |
| 0x106e5    | 1        | 0.26%   |
| 0x106ca    | 1        | 0.26%   |
| 0x10677    | 1        | 0.26%   |
| 0x0a50000b | 1        | 0.26%   |
| 0x0a201204 | 1        | 0.26%   |
| 0x0a201006 | 1        | 0.26%   |
| 0x08600106 | 1        | 0.26%   |
| 0x08600104 | 1        | 0.26%   |
| 0x0830104d | 1        | 0.26%   |
| 0x08301025 | 1        | 0.26%   |
| 0x08101013 | 1        | 0.26%   |
| 0x0800820c | 1        | 0.26%   |
| 0x07030105 | 1        | 0.26%   |
| 0x0700010b | 1        | 0.26%   |
| 0x07000106 | 1        | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 52       | 13.79%  |
| Zen 2            | 44       | 11.67%  |
| Haswell          | 41       | 10.88%  |
| Zen 3            | 40       | 10.61%  |
| Zen+             | 29       | 7.69%   |
| Zen              | 23       | 6.1%    |
| SandyBridge      | 22       | 5.84%   |
| IvyBridge        | 22       | 5.84%   |
| Skylake          | 16       | 4.24%   |
| Penryn           | 14       | 3.71%   |
| Piledriver       | 12       | 3.18%   |
| CometLake        | 11       | 2.92%   |
| K10              | 10       | 2.65%   |
| Alderlake Hybrid | 8        | 2.12%   |
| Steamroller      | 6        | 1.59%   |
| Westmere         | 5        | 1.33%   |
| Nehalem          | 4        | 1.06%   |
| Icelake          | 4        | 1.06%   |
| K8 Hammer        | 2        | 0.53%   |
| Jaguar           | 2        | 0.53%   |
| Bulldozer        | 2        | 0.53%   |
| Unknown          | 2        | 0.53%   |
| Puma             | 1        | 0.27%   |
| K10 Llano        | 1        | 0.27%   |
| Excavator        | 1        | 0.27%   |
| Core             | 1        | 0.27%   |
| Broadwell        | 1        | 0.27%   |
| Bonnell          | 1        | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 161      | 39.56%  |
| AMD                        | 144      | 35.38%  |
| Intel                      | 100      | 24.57%  |
| Matrox Electronics Systems | 1        | 0.25%   |
| ASPEED Technology          | 1        | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 36       | 8.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 17       | 4.1%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 16       | 3.86%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 15       | 3.61%   |
| Nvidia GK208B [GeForce GT 710]                                              | 12       | 2.89%   |
| Intel HD Graphics 530                                                       | 12       | 2.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 2.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 10       | 2.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 2.17%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9        | 2.17%   |
| AMD Cezanne                                                                 | 8        | 1.93%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 7        | 1.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 7        | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 1.69%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 7        | 1.69%   |
| Intel AlderLake-S GT1                                                       | 6        | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.2%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 1.2%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 1.2%    |
| Intel HD Graphics 630                                                       | 5        | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 1.2%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 1.2%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 4        | 0.96%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 4        | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 0.96%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 0.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 0.96%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 4        | 0.96%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 4        | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.72%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.72%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 3        | 0.72%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 3        | 0.72%   |
| AMD Renoir                                                                  | 3        | 0.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 0.72%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 0.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.48%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.48%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.48%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.48%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 0.48%   |
| Nvidia GP107GL [Quadro P400]                                                | 2        | 0.48%   |
| Nvidia GP107GL [Quadro P1000]                                               | 2        | 0.48%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.48%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 0.48%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 0.48%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 2        | 0.48%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 0.48%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 0.48%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.48%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 0.48%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.48%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 0.48%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 0.48%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 2        | 0.48%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 149      | 39.42%  |
| 1 x AMD            | 137      | 36.24%  |
| 1 x Intel          | 72       | 19.05%  |
| Intel + Nvidia     | 8        | 2.12%   |
| 2 x AMD            | 5        | 1.32%   |
| Other              | 1        | 0.26%   |
| 2 x Nvidia         | 1        | 0.26%   |
| Nvidia + Matrox    | 1        | 0.26%   |
| Intel + 2 x Nvidia | 1        | 0.26%   |
| Intel + 2 x AMD    | 1        | 0.26%   |
| 1 x ASPEED         | 1        | 0.26%   |
| AMD + Nvidia       | 1        | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 275      | 72.37%  |
| Proprietary | 98       | 25.79%  |
| Unknown     | 7        | 1.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 149      | 38.9%   |
| 7.01-8.0   | 55       | 14.36%  |
| 1.01-2.0   | 48       | 12.53%  |
| 3.01-4.0   | 38       | 9.92%   |
| 0.51-1.0   | 29       | 7.57%   |
| 0.01-0.5   | 25       | 6.53%   |
| 8.01-16.0  | 20       | 5.22%   |
| 5.01-6.0   | 15       | 3.92%   |
| 2.01-3.0   | 4        | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 75       | 17.12%  |
| Goldstar             | 53       | 12.1%   |
| Dell                 | 45       | 10.27%  |
| Acer                 | 34       | 7.76%   |
| AOC                  | 31       | 7.08%   |
| Hewlett-Packard      | 24       | 5.48%   |
| Ancor Communications | 21       | 4.79%   |
| BenQ                 | 20       | 4.57%   |
| Philips              | 19       | 4.34%   |
| ViewSonic            | 16       | 3.65%   |
| Lenovo               | 13       | 2.97%   |
| Iiyama               | 11       | 2.51%   |
| ASUSTek Computer     | 10       | 2.28%   |
| Eizo                 | 7        | 1.6%    |
| HannStar             | 6        | 1.37%   |
| Unknown              | 4        | 0.91%   |
| Vizio                | 3        | 0.68%   |
| Sony                 | 3        | 0.68%   |
| Panasonic            | 3        | 0.68%   |
| MSI                  | 3        | 0.68%   |
| Fujitsu Siemens      | 3        | 0.68%   |
| ___                  | 2        | 0.46%   |
| Mi                   | 2        | 0.46%   |
| Gigabyte Technology  | 2        | 0.46%   |
| Arnos Instruments    | 2        | 0.46%   |
| YUK                  | 1        | 0.23%   |
| Westinghouse         | 1        | 0.23%   |
| Valve                | 1        | 0.23%   |
| Unknown (XXX)        | 1        | 0.23%   |
| Toshiba              | 1        | 0.23%   |
| TCT                  | 1        | 0.23%   |
| TCL                  | 1        | 0.23%   |
| SHX                  | 1        | 0.23%   |
| Sharp                | 1        | 0.23%   |
| Sceptre Tech         | 1        | 0.23%   |
| PRISM+               | 1        | 0.23%   |
| Plain Tree Systems   | 1        | 0.23%   |
| Pixio                | 1        | 0.23%   |
| Packard Bell         | 1        | 0.23%   |
| ONN                  | 1        | 0.23%   |
| NEC Computers        | 1        | 0.23%   |
| LG Electronics       | 1        | 0.23%   |
| Insignia             | 1        | 0.23%   |
| Haier                | 1        | 0.23%   |
| Denver               | 1        | 0.23%   |
| Daewoo               | 1        | 0.23%   |
| CHE                  | 1        | 0.23%   |
| Belinea              | 1        | 0.23%   |
| Apple                | 1        | 0.23%   |
| AMT International    | 1        | 0.23%   |
| AGO                  | 1        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch               | 6        | 1.29%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5        | 1.07%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 4        | 0.86%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 4        | 0.86%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 3        | 0.64%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 3        | 0.64%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 3        | 0.64%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 3        | 0.64%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                       | 3        | 0.64%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 3        | 0.64%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 2        | 0.43%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 2        | 0.43%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.43%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 530x300mm 24.0-inch      | 2        | 0.43%   |
| Samsung Electronics S22C350 SAM0A32 1920x1080 477x268mm 21.5-inch      | 2        | 0.43%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 2        | 0.43%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch  | 2        | 0.43%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch     | 2        | 0.43%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch      | 2        | 0.43%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 2        | 0.43%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                  | 2        | 0.43%   |
| Iiyama PL2282H IVM5632 1920x1080 476x268mm 21.5-inch                   | 2        | 0.43%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.43%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 2        | 0.43%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch               | 2        | 0.43%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                  | 2        | 0.43%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                      | 2        | 0.43%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                      | 2        | 0.43%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                    | 2        | 0.43%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                      | 2        | 0.43%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                      | 2        | 0.43%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 2        | 0.43%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch           | 2        | 0.43%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch           | 2        | 0.43%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                    | 2        | 0.43%   |
| AOC 22B2WG5 AOC2202 1920x1080 477x268mm 21.5-inch                      | 2        | 0.43%   |
| AOC 22B1W AOC2201 1920x1080 476x268mm 21.5-inch                        | 2        | 0.43%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 2        | 0.43%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.43%   |
| Acer VG240Y ACR0673 1920x1080 527x296mm 23.8-inch                      | 2        | 0.43%   |
| ___ LCDTV16 ___0101 1360x768                                           | 1        | 0.21%   |
| ___ LCD TV ___9000 1360x768                                            | 1        | 0.21%   |
| YUK NexDock YUKBC34 1920x1080 293x165mm 13.2-inch                      | 1        | 0.21%   |
| Westinghouse EU24H1G1 WDT1D42 1366x768 1150x650mm 52.0-inch            | 1        | 0.21%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1        | 0.21%   |
| Vizio E60-E3 VIZ1018 3840x2160 1330x748mm 60.1-inch                    | 1        | 0.21%   |
| Vizio E390-A1 VIZ0098 1920x1080 853x480mm 38.5-inch                    | 1        | 0.21%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch          | 1        | 0.21%   |
| ViewSonic VX3258 SERIES VSCDE35 2560x1440 697x392mm 31.5-inch          | 1        | 0.21%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch              | 1        | 0.21%   |
| ViewSonic VX2739wm VSC3F24 1920x1080 598x336mm 27.0-inch               | 1        | 0.21%   |
| ViewSonic VX2336 SERIES VSC402A 1920x1080 510x290mm 23.1-inch          | 1        | 0.21%   |
| ViewSonic VX2276 Series VSC2F32 1920x1080 476x268mm 21.5-inch          | 1        | 0.21%   |
| ViewSonic VX2268wm VSC0E23 1680x1050 474x296mm 22.0-inch               | 1        | 0.21%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch               | 1        | 0.21%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch          | 1        | 0.21%   |
| ViewSonic VX2025wm VSCE51D 1680x1050 433x271mm 20.1-inch               | 1        | 0.21%   |
| ViewSonic VP2250wb VSC5320 1920x1080 465x291mm 21.6-inch               | 1        | 0.21%   |
| ViewSonic VA2419 Series VSC7B32 1920x1080 527x296mm 23.8-inch          | 1        | 0.21%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch              | 1        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 194      | 45.54%  |
| 2560x1440 (QHD)    | 59       | 13.85%  |
| 3840x2160 (4K)     | 55       | 12.91%  |
| 1280x1024 (SXGA)   | 18       | 4.23%   |
| 1680x1050 (WSXGA+) | 17       | 3.99%   |
| 1366x768 (WXGA)    | 14       | 3.29%   |
| 1920x1200 (WUXGA)  | 13       | 3.05%   |
| 1440x900 (WXGA+)   | 12       | 2.82%   |
| 3440x1440          | 11       | 2.58%   |
| 1600x900 (HD+)     | 8        | 1.88%   |
| 2560x1080          | 5        | 1.17%   |
| 3840x1080          | 3        | 0.7%    |
| 1360x768           | 3        | 0.7%    |
| Unknown            | 3        | 0.7%    |
| 2560x1600          | 2        | 0.47%   |
| 1600x1200          | 2        | 0.47%   |
| 6784x2160          | 1        | 0.23%   |
| 4480x1080          | 1        | 0.23%   |
| 3840x1600          | 1        | 0.23%   |
| 1920x540           | 1        | 0.23%   |
| 1280x960           | 1        | 0.23%   |
| 1280x720 (HD)      | 1        | 0.23%   |
| 1024x768 (XGA)     | 1        | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 97       | 21.8%   |
| 24      | 75       | 16.85%  |
| 21      | 61       | 13.71%  |
| 23      | 48       | 10.79%  |
| 31      | 26       | 5.84%   |
| 19      | 18       | 4.04%   |
| 34      | 16       | 3.6%    |
| 22      | 15       | 3.37%   |
| 18      | 15       | 3.37%   |
| 20      | 10       | 2.25%   |
| 17      | 9        | 2.02%   |
| Unknown | 6        | 1.35%   |
| 72      | 5        | 1.12%   |
| 25      | 5        | 1.12%   |
| 84      | 4        | 0.9%    |
| 42      | 4        | 0.9%    |
| 54      | 3        | 0.67%   |
| 48      | 3        | 0.67%   |
| 32      | 3        | 0.67%   |
| 15      | 3        | 0.67%   |
| 65      | 2        | 0.45%   |
| 49      | 2        | 0.45%   |
| 47      | 2        | 0.45%   |
| 37      | 2        | 0.45%   |
| 28      | 2        | 0.45%   |
| 74      | 1        | 0.22%   |
| 52      | 1        | 0.22%   |
| 35      | 1        | 0.22%   |
| 30      | 1        | 0.22%   |
| 29      | 1        | 0.22%   |
| 26      | 1        | 0.22%   |
| 16      | 1        | 0.22%   |
| 13      | 1        | 0.22%   |
| 12      | 1        | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 199      | 46.39%  |
| 401-500     | 106      | 24.71%  |
| 601-700     | 41       | 9.56%   |
| 701-800     | 19       | 4.43%   |
| 351-400     | 15       | 3.5%    |
| 1001-1500   | 13       | 3.03%   |
| 301-350     | 11       | 2.56%   |
| 1501-2000   | 10       | 2.33%   |
| Unknown     | 6        | 1.4%    |
| 901-1000    | 4        | 0.93%   |
| 801-900     | 3        | 0.7%    |
| 201-300     | 2        | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 294      | 74.43%  |
| 16/10   | 49       | 12.41%  |
| 5/4     | 19       | 4.81%   |
| 21/9    | 17       | 4.3%    |
| 4/3     | 5        | 1.27%   |
| Unknown | 5        | 1.27%   |
| 32/9    | 3        | 0.76%   |
| 6/5     | 2        | 0.51%   |
| 3/2     | 1        | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 146      | 33.49%  |
| 301-350        | 97       | 22.25%  |
| 151-200        | 52       | 11.93%  |
| 351-500        | 49       | 11.24%  |
| 251-300        | 29       | 6.65%   |
| 141-150        | 21       | 4.82%   |
| More than 1000 | 17       | 3.9%    |
| 501-1000       | 12       | 2.75%   |
| Unknown        | 6        | 1.38%   |
| 101-110        | 3        | 0.69%   |
| 71-80          | 2        | 0.46%   |
| 131-140        | 1        | 0.23%   |
| 121-130        | 1        | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 237      | 57.8%   |
| 101-120 | 114      | 27.8%   |
| 121-160 | 25       | 6.1%    |
| 161-240 | 17       | 4.15%   |
| 1-50    | 11       | 2.68%   |
| Unknown | 6        | 1.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 268      | 70.34%  |
| 2     | 91       | 23.88%  |
| 0     | 15       | 3.94%   |
| 3     | 6        | 1.57%   |
| 4     | 1        | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 219      | 40.78%  |
| Intel                           | 195      | 36.31%  |
| Qualcomm Atheros                | 29       | 5.4%    |
| TP-Link                         | 18       | 3.35%   |
| Ralink Technology               | 13       | 2.42%   |
| Broadcom                        | 12       | 2.23%   |
| Aquantia                        | 6        | 1.12%   |
| Nvidia                          | 5        | 0.93%   |
| NetGear                         | 3        | 0.56%   |
| Marvell Technology Group        | 3        | 0.56%   |
| Google                          | 3        | 0.56%   |
| Belkin Components               | 3        | 0.56%   |
| Xiaomi                          | 2        | 0.37%   |
| Wilocity                        | 2        | 0.37%   |
| Samsung Electronics             | 2        | 0.37%   |
| Ralink                          | 2        | 0.37%   |
| Microsoft                       | 2        | 0.37%   |
| ICS Advent                      | 2        | 0.37%   |
| Edimax Technology               | 2        | 0.37%   |
| ASUSTek Computer                | 2        | 0.37%   |
| Xilinx                          | 1        | 0.19%   |
| Winbond Electronics             | 1        | 0.19%   |
| Unknown                         | 1        | 0.19%   |
| Qualcomm Atheros Communications | 1        | 0.19%   |
| Mellanox Technologies           | 1        | 0.19%   |
| Linksys                         | 1        | 0.19%   |
| Huawei Technologies             | 1        | 0.19%   |
| HMD Global                      | 1        | 0.19%   |
| D-Link                          | 1        | 0.19%   |
| AVM                             | 1        | 0.19%   |
| ASIX Electronics                | 1        | 0.19%   |
| Apple                           | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 172      | 27.34%  |
| Intel Wi-Fi 6 AX200                                               | 48       | 7.63%   |
| Intel I211 Gigabit Network Connection                             | 39       | 6.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 29       | 4.61%   |
| Intel Ethernet Connection (7) I219-V                              | 20       | 3.18%   |
| Intel Ethernet Controller I225-V                                  | 18       | 2.86%   |
| Intel Ethernet Connection (2) I219-V                              | 17       | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10       | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9        | 1.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 7        | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 1.11%   |
| Intel Wireless-AC 9260                                            | 7        | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7        | 1.11%   |
| Intel 82579V Gigabit Network Connection                           | 7        | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 0.95%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 0.95%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 0.79%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 5        | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4        | 0.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4        | 0.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.64%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4        | 0.64%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 4        | 0.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 0.48%   |
| TP-Link 802.11ac NIC                                              | 3        | 0.48%   |
| Realtek 802.11ac NIC                                              | 3        | 0.48%   |
| Ralink RT5372 Wireless Adapter                                    | 3        | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3        | 0.48%   |
| Intel Wireless 8260                                               | 3        | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.48%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.32%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 2        | 0.32%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.32%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.32%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2        | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.32%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.32%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.32%   |
| Microsoft XBOX ACC                                                | 2        | 0.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2        | 0.32%   |
| Intel I350 Gigabit Network Connection                             | 2        | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 101      | 50.25%  |
| Realtek Semiconductor           | 25       | 12.44%  |
| TP-Link                         | 18       | 8.96%   |
| Qualcomm Atheros                | 15       | 7.46%   |
| Ralink Technology               | 13       | 6.47%   |
| Broadcom                        | 10       | 4.98%   |
| NetGear                         | 3        | 1.49%   |
| Belkin Components               | 3        | 1.49%   |
| Wilocity                        | 2        | 1%      |
| Ralink                          | 2        | 1%      |
| Microsoft                       | 2        | 1%      |
| Edimax Technology               | 2        | 1%      |
| Qualcomm Atheros Communications | 1        | 0.5%    |
| Linksys                         | 1        | 0.5%    |
| D-Link                          | 1        | 0.5%    |
| AVM                             | 1        | 0.5%    |
| ASUSTek Computer                | 1        | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 48       | 23.41%  |
| Intel Cannon Lake PCH CNVi WiFi                                           | 10       | 4.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 9        | 4.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 7        | 3.41%   |
| Intel Wireless-AC 9260                                                    | 7        | 3.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 7        | 3.41%   |
| Ralink RT5370 Wireless Adapter                                            | 5        | 2.44%   |
| Intel Alder Lake-S PCH CNVi WiFi                                          | 5        | 2.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 4        | 1.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 4        | 1.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 4        | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 4        | 1.95%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 4        | 1.95%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                        | 4        | 1.95%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                        | 4        | 1.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3        | 1.46%   |
| TP-Link 802.11ac NIC                                                      | 3        | 1.46%   |
| Realtek 802.11ac NIC                                                      | 3        | 1.46%   |
| Ralink RT5372 Wireless Adapter                                            | 3        | 1.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 3        | 1.46%   |
| Intel Wireless 8260                                                       | 3        | 1.46%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                        | 2        | 0.98%   |
| TP-Link 802.11ac WLAN Adapter                                             | 2        | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2        | 0.98%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                | 2        | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 2        | 0.98%   |
| Ralink MT7601U Wireless Adapter                                           | 2        | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2        | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 2        | 0.98%   |
| Microsoft XBOX ACC                                                        | 2        | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 2        | 0.98%   |
| Intel Centrino Wireless-N 2230                                            | 2        | 0.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 2        | 0.98%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                       | 1        | 0.49%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1        | 0.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                | 1        | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 0.49%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                  | 1        | 0.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 1        | 0.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                           | 1        | 0.49%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                           | 1        | 0.49%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1        | 0.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1        | 0.49%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1        | 0.49%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                         | 1        | 0.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                 | 1        | 0.49%   |
| Ralink RT2500 Wireless 802.11bg                                           | 1        | 0.49%   |
| Qualcomm Atheros AR5523                                                   | 1        | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 1        | 0.49%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1        | 0.49%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]          | 1        | 0.49%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 0.49%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]    | 1        | 0.49%   |
| Intel Wireless 8265 / 8275                                                | 1        | 0.49%   |
| Intel Wireless 7265                                                       | 1        | 0.49%   |
| Intel Wireless 7260                                                       | 1        | 0.49%   |
| Intel Wireless 3165                                                       | 1        | 0.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1        | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1        | 0.49%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                             | 1        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 207      | 51.24%  |
| Intel                    | 151      | 37.38%  |
| Qualcomm Atheros         | 15       | 3.71%   |
| Aquantia                 | 6        | 1.49%   |
| Nvidia                   | 5        | 1.24%   |
| Marvell Technology Group | 3        | 0.74%   |
| Xiaomi                   | 2        | 0.5%    |
| Samsung Electronics      | 2        | 0.5%    |
| ICS Advent               | 2        | 0.5%    |
| Broadcom                 | 2        | 0.5%    |
| Xilinx                   | 1        | 0.25%   |
| Unknown                  | 1        | 0.25%   |
| Mellanox Technologies    | 1        | 0.25%   |
| Huawei Technologies      | 1        | 0.25%   |
| HMD Global               | 1        | 0.25%   |
| Google                   | 1        | 0.25%   |
| ASUSTek Computer         | 1        | 0.25%   |
| ASIX Electronics         | 1        | 0.25%   |
| Apple                    | 1        | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 172      | 40.95%  |
| Intel I211 Gigabit Network Connection                                         | 39       | 9.29%   |
| Realtek RTL8125 2.5GbE Controller                                             | 29       | 6.9%    |
| Intel Ethernet Connection (7) I219-V                                          | 20       | 4.76%   |
| Intel Ethernet Controller I225-V                                              | 18       | 4.29%   |
| Intel Ethernet Connection (2) I219-V                                          | 17       | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13       | 3.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 7        | 1.67%   |
| Intel 82579V Gigabit Network Connection                                       | 7        | 1.67%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 1.43%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 1.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 5        | 1.19%   |
| Intel Ethernet Connection (2) I218-V                                          | 4        | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 0.71%   |
| Intel Ethernet Connection I217-V                                              | 3        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 0.71%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 2        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2        | 0.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2        | 0.48%   |
| Nvidia MCP61 Ethernet                                                         | 2        | 0.48%   |
| Nvidia MCP55 Ethernet                                                         | 2        | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 0.48%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 0.48%   |
| Intel Ethernet Connection (14) I219-LM                                        | 2        | 0.48%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.48%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 2        | 0.48%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 0.48%   |
| Xilinx Smart JTAG Cable                                                       | 1        | 0.24%   |
| Unknown Ceton InfiniTV Network                                                | 1        | 0.24%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 0.24%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.24%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.24%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.24%   |
| Nvidia MCP51 Ethernet Controller                                              | 1        | 0.24%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.24%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1        | 0.24%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 0.24%   |
| Intel I210 Gigabit Network Connection                                         | 1        | 0.24%   |
| Intel Ethernet Controller 10G X550T                                           | 1        | 0.24%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 0.24%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.24%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.24%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.24%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.24%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.24%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 1        | 0.24%   |
| Huawei E353/E3131                                                             | 1        | 0.24%   |
| HMD Global Nokia 2.4                                                          | 1        | 0.24%   |
| Google Nexus/Pixel Device (tether)                                            | 1        | 0.24%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.24%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 1        | 0.24%   |
| ASUS USB 10/100/1G/2.5G LAN                                                   | 1        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 375      | 66.84%  |
| WiFi     | 182      | 32.44%  |
| Modem    | 3        | 0.53%   |
| Unknown  | 1        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 339      | 71.97%  |
| WiFi     | 132      | 28.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 215      | 56.73%  |
| 2     | 130      | 34.3%   |
| 3     | 25       | 6.6%    |
| 0     | 4        | 1.06%   |
| 4     | 3        | 0.79%   |
| 6     | 1        | 0.26%   |
| 5     | 1        | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 274      | 72.49%  |
| Yes  | 104      | 27.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 96       | 54.24%  |
| Cambridge Silicon Radio         | 36       | 20.34%  |
| ASUSTek Computer                | 17       | 9.6%    |
| Broadcom                        | 9        | 5.08%   |
| Realtek Semiconductor           | 5        | 2.82%   |
| Qualcomm Atheros Communications | 5        | 2.82%   |
| Apple                           | 4        | 2.26%   |
| TP-Link                         | 2        | 1.13%   |
| Belkin Components               | 2        | 1.13%   |
| Lite-On Technology              | 1        | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 46       | 25.99%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 36       | 20.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 10       | 5.65%   |
| Intel Wireless-AC 3168 Bluetooth                      | 9        | 5.08%   |
| Intel Bluetooth Device                                | 8        | 4.52%   |
| Intel Bluetooth wireless interface                    | 7        | 3.95%   |
| Intel AX210 Bluetooth                                 | 7        | 3.95%   |
| Intel AX201 Bluetooth                                 | 6        | 3.39%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 6        | 3.39%   |
| Realtek Bluetooth Radio                               | 5        | 2.82%   |
| ASUS Bluetooth Radio                                  | 5        | 2.82%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 1.69%   |
| ASUS ASUS USB-BT500                                   | 3        | 1.69%   |
| TP-Link UB500 Adapter                                 | 2        | 1.13%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 2        | 1.13%   |
| ASUS Bluetooth Device                                 | 2        | 1.13%   |
| ASUS Bluetooth Adapter                                | 2        | 1.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2        | 1.13%   |
| Apple Bluetooth USB Host Controller                   | 2        | 1.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 0.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 0.56%   |
| Lite-On Bluetooth Device                              | 1        | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 1        | 0.56%   |
| Broadcom HP Portable Bumble Bee                       | 1        | 0.56%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle    | 1        | 0.56%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 0.56%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 0.56%   |
| Belkin Components F8T012 Bluetooth Adapter            | 1        | 0.56%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.56%   |
| ASUS BCM20702A0                                       | 1        | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 203      | 28.31%  |
| Intel                                | 196      | 27.34%  |
| Nvidia                               | 154      | 21.48%  |
| C-Media Electronics                  | 16       | 2.23%   |
| Creative Labs                        | 10       | 1.39%   |
| JMTek                                | 8        | 1.12%   |
| Logitech                             | 7        | 0.98%   |
| Texas Instruments                    | 6        | 0.84%   |
| SteelSeries ApS                      | 6        | 0.84%   |
| Razer USA                            | 6        | 0.84%   |
| Plantronics                          | 6        | 0.84%   |
| Kingston Technology                  | 6        | 0.84%   |
| Focusrite-Novation                   | 6        | 0.84%   |
| GN Netcom                            | 5        | 0.7%    |
| Corsair                              | 5        | 0.7%    |
| Sony                                 | 4        | 0.56%   |
| Blue Microphones                     | 4        | 0.56%   |
| Tenx Technology                      | 3        | 0.42%   |
| Sennheiser Communications            | 3        | 0.42%   |
| Realtek Semiconductor                | 3        | 0.42%   |
| Generalplus Technology               | 3        | 0.42%   |
| Creative Technology                  | 3        | 0.42%   |
| Apogee Electronics                   | 3        | 0.42%   |
| Unknown                              | 2        | 0.28%   |
| SAVITECH                             | 2        | 0.28%   |
| Samson Technologies                  | 2        | 0.28%   |
| RODE Microphones                     | 2        | 0.28%   |
| GYROCOM C&C                          | 2        | 0.28%   |
| Giga-Byte Technology                 | 2        | 0.28%   |
| Audio-Technica                       | 2        | 0.28%   |
| ASUSTek Computer                     | 2        | 0.28%   |
| Apple                                | 2        | 0.28%   |
| Unknown                              | 2        | 0.28%   |
| Yamaha                               | 1        | 0.14%   |
| Valve Software                       | 1        | 0.14%   |
| ULi Electronics                      | 1        | 0.14%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.14%   |
| Thermaltake                          | 1        | 0.14%   |
| ShareWave                            | 1        | 0.14%   |
| Schiit Audio                         | 1        | 0.14%   |
| Roland                               | 1        | 0.14%   |
| RME                                  | 1        | 0.14%   |
| Quanta                               | 1        | 0.14%   |
| OLKB                                 | 1        | 0.14%   |
| Native Instruments                   | 1        | 0.14%   |
| Microsoft                            | 1        | 0.14%   |
| Microdia                             | 1        | 0.14%   |
| Meizu                                | 1        | 0.14%   |
| Mark of the Unicorn                  | 1        | 0.14%   |
| Lenovo                               | 1        | 0.14%   |
| Huawei Technologies                  | 1        | 0.14%   |
| HiFimeDIY Audio                      | 1        | 0.14%   |
| Goldvish                             | 1        | 0.14%   |
| FiiO Electronics Technology          | 1        | 0.14%   |
| Elite Silicon                        | 1        | 0.14%   |
| DigiTech                             | 1        | 0.14%   |
| Digidesign                           | 1        | 0.14%   |
| Dell                                 | 1        | 0.14%   |
| Cooler Master                        | 1        | 0.14%   |
| Cambridge Silicon Radio              | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 70       | 8.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 38       | 4.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 36       | 4.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 30       | 3.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 3.19%   |
| AMD Family 17h/19h HD Audio Controller                                     | 24       | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21       | 2.48%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 20       | 2.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 19       | 2.25%   |
| Intel 200 Series PCH HD Audio                                              | 19       | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18       | 2.13%   |
| AMD Navi 10 HDMI Audio                                                     | 17       | 2.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16       | 1.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 15       | 1.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15       | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15       | 1.77%   |
| AMD FCH Azalia Controller                                                  | 15       | 1.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 13       | 1.54%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 12       | 1.42%   |
| Nvidia TU106 High Definition Audio Controller                              | 11       | 1.3%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 11       | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 11       | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11       | 1.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 9        | 1.06%   |
| Nvidia TU104 HD Audio Controller                                           | 8        | 0.95%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8        | 0.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8        | 0.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 0.71%   |
| Nvidia GM206 High Definition Audio Controller                              | 6        | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                              | 5        | 0.59%   |
| Nvidia GP102 HDMI Audio Controller                                         | 5        | 0.59%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5        | 0.59%   |
| Nvidia GA102 High Definition Audio Controller                              | 5        | 0.59%   |
| JMTek USB PnP Audio Device                                                 | 5        | 0.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 0.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 0.59%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.59%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 0.59%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 0.59%   |
| Texas Instruments PCM2902 Audio Codec                                      | 4        | 0.47%   |
| Nvidia TU102 High Definition Audio Controller                              | 4        | 0.47%   |
| Nvidia High Definition Audio Controller                                    | 4        | 0.47%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.47%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 0.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.47%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 4        | 0.47%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 4        | 0.47%   |
| AMD Trinity HDMI Audio Controller                                          | 4        | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 0.35%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 0.35%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 0.35%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.35%   |
| Intel USB PnP Sound Device                                                 | 3        | 0.35%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.35%   |
| Intel Audio device                                                         | 3        | 0.35%   |
| Generalplus Technology USB Audio Device                                    | 3        | 0.35%   |
| C-Media Electronics KLIM Mantis Audio 7.1                                  | 3        | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 44       | 21.57%  |
| Corsair             | 42       | 20.59%  |
| Crucial             | 25       | 12.25%  |
| Unknown             | 22       | 10.78%  |
| G.Skill             | 22       | 10.78%  |
| SK Hynix            | 14       | 6.86%   |
| Samsung Electronics | 11       | 5.39%   |
| Micron Technology   | 6        | 2.94%   |
| Team                | 4        | 1.96%   |
| A-DATA Technology   | 3        | 1.47%   |
| Patriot             | 2        | 0.98%   |
| GOODRAM             | 2        | 0.98%   |
| V-GeN               | 1        | 0.49%   |
| TIMETEC             | 1        | 0.49%   |
| Ramaxel Technology  | 1        | 0.49%   |
| PLEXHD              | 1        | 0.49%   |
| OCZ                 | 1        | 0.49%   |
| Apacer              | 1        | 0.49%   |
| Unknown             | 1        | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s         | 4        | 1.83%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s       | 4        | 1.83%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s        | 3        | 1.38%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s        | 3        | 1.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s           | 3        | 1.38%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s      | 3        | 1.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s   | 3        | 1.38%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s    | 3        | 1.38%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                        | 2        | 0.92%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 2        | 0.92%   |
| Unknown RAM Module 4GB DIMM 800MT/s                         | 2        | 0.92%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 2        | 0.92%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                  | 2        | 0.92%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 2667MT/s     | 2        | 0.92%   |
| Kingston RAM Module 4GB DIMM DDR3 1066MT/s                  | 2        | 0.92%   |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s   | 2        | 0.92%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s         | 2        | 0.92%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s         | 2        | 0.92%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 2        | 0.92%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s       | 2        | 0.92%   |
| G.Skill RAM F4-3200C14-16GVK 16GB DIMM DDR4 3200MT/s        | 2        | 0.92%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16384MB DIMM DDR4 3400MT/s | 2        | 0.92%   |
| Corsair RAM CMX4GX3M2A1600C9 2GB DIMM DDR3 1600MT/s         | 2        | 0.92%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s       | 2        | 0.92%   |
| Corsair RAM CMW16GX4M2C3000C15 8GB DIMM DDR4 3200MT/s       | 2        | 0.92%   |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 2133MT/s        | 2        | 0.92%   |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s               | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                   | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                   | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM 400MT/s                         | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                   | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 667MT/s                         | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 400MT/s                         | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                        | 1        | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                    | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                     | 1        | 0.46%   |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s                | 1        | 0.46%   |
| Unknown RAM CL19-19-19 D4-2666 8192MB DIMM DDR4 2400MT/s    | 1        | 0.46%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s         | 1        | 0.46%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s          | 1        | 0.46%   |
| TIMETEC RAM UD4-3600 32GB DIMM DDR4 3600MT/s                | 1        | 0.46%   |
| Timetec RAM 36NU1R8-8G 8GB DIMM DDR4 3600MT/s               | 1        | 0.46%   |
| Team RAM TEAMGROUP-UD4-4000 8GB DIMM DDR4 3200MT/s          | 1        | 0.46%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s          | 1        | 0.46%   |
| Team RAM TEAMGROUP-UD4-3200 16384MB DIMM DDR4 3733MT/s      | 1        | 0.46%   |
| Team RAM TEAMGROUP-UD4-2400 8192MB DIMM DDR4 2400MT/s       | 1        | 0.46%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s        | 1        | 0.46%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s        | 1        | 0.46%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1        | 0.46%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1067MT/s        | 1        | 0.46%   |
| SK Hynix RAM HMT125U6BFR8C-H9 2GB DIMM DDR3 1067MT/s        | 1        | 0.46%   |
| SK Hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s         | 1        | 0.46%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s        | 1        | 0.46%   |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s        | 1        | 0.46%   |
| SK Hynix RAM HMA451U6AFR8N-TF 4096MB DIMM DDR4 2133MT/s     | 1        | 0.46%   |
| SK Hynix RAM HMA41GR7MFR4N-TF 8GB DIMM DDR4 2667MT/s        | 1        | 0.46%   |
| SK Hynix RAM HMA41GR7AFR4N-TF 8192MB DIMM DDR4 2133MT/s     | 1        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 114      | 62.3%   |
| DDR3    | 51       | 27.87%  |
| Unknown | 13       | 7.1%    |
| DDR2    | 4        | 2.19%   |
| DDR     | 1        | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 175      | 96.15%  |
| SODIMM | 7        | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 77       | 40.31%  |
| 16384 | 48       | 25.13%  |
| 4096  | 34       | 17.8%   |
| 2048  | 20       | 10.47%  |
| 32768 | 10       | 5.24%   |
| 1024  | 2        | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 36       | 18%     |
| 3200  | 35       | 17.5%   |
| 3600  | 22       | 11%     |
| 1333  | 15       | 7.5%    |
| 2667  | 13       | 6.5%    |
| 2400  | 12       | 6%      |
| 2133  | 8        | 4%      |
| 800   | 6        | 3%      |
| 3466  | 5        | 2.5%    |
| 3400  | 5        | 2.5%    |
| 2933  | 5        | 2.5%    |
| 2666  | 5        | 2.5%    |
| 1867  | 4        | 2%      |
| 3533  | 3        | 1.5%    |
| 3000  | 3        | 1.5%    |
| 1067  | 3        | 1.5%    |
| 4800  | 2        | 1%      |
| 3733  | 2        | 1%      |
| 3266  | 2        | 1%      |
| 2800  | 2        | 1%      |
| 1066  | 2        | 1%      |
| 400   | 2        | 1%      |
| 4000  | 1        | 0.5%    |
| 3066  | 1        | 0.5%    |
| 2802  | 1        | 0.5%    |
| 2134  | 1        | 0.5%    |
| 1866  | 1        | 0.5%    |
| 1024  | 1        | 0.5%    |
| 667   | 1        | 0.5%    |
| 333   | 1        | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 6        | 40%     |
| Hewlett-Packard     | 3        | 20%     |
| Canon               | 2        | 13.33%  |
| Seiko Epson         | 1        | 6.67%   |
| Samsung Electronics | 1        | 6.67%   |
| QinHeng Electronics | 1        | 6.67%   |
| Kyocera             | 1        | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother HL-L2340D series      | 2        | 13.33%  |
| Seiko Epson WF-2510 Series    | 1        | 6.67%   |
| Samsung M2070 Series          | 1        | 6.67%   |
| QinHeng CH340S                | 1        | 6.67%   |
| Kyocera ECOSYS M5521cdw       | 1        | 6.67%   |
| HP LaserJet CM1415fnw         | 1        | 6.67%   |
| HP DeskJet F300 series        | 1        | 6.67%   |
| HP DeskJet F2492 All-in-One   | 1        | 6.67%   |
| Canon TR4500 series           | 1        | 6.67%   |
| Canon MF4010 series           | 1        | 6.67%   |
| Brother Printer               | 1        | 6.67%   |
| Brother MFC-J485DW            | 1        | 6.67%   |
| Brother HL-L2360D series      | 1        | 6.67%   |
| Brother HL-1440 Laser Printer | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 3        | 50%     |
| Canon       | 3        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]       | 2        | 33.33%  |
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 1        | 16.67%  |
| Canon CanoScan LiDE 220                     | 1        | 16.67%  |
| Canon CanoScan LiDE 210                     | 1        | 16.67%  |
| Canon CanoScan LiDE 120                     | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 47       | 54.65%  |
| Microdia                               | 4        | 4.65%   |
| Apple                                  | 4        | 4.65%   |
| Microsoft                              | 3        | 3.49%   |
| Generalplus Technology                 | 3        | 3.49%   |
| Z-Star Microelectronics                | 2        | 2.33%   |
| Trust                                  | 2        | 2.33%   |
| Sunplus Innovation Technology          | 2        | 2.33%   |
| Lenovo                                 | 2        | 2.33%   |
| KYE Systems (Mouse Systems)            | 2        | 2.33%   |
| Jieli Technology                       | 2        | 2.33%   |
| Genesys Logic                          | 2        | 2.33%   |
| Creative Technology                    | 2        | 2.33%   |
| Sonix Technology                       | 1        | 1.16%   |
| Samsung Electronics                    | 1        | 1.16%   |
| Quanta                                 | 1        | 1.16%   |
| Micro Star International               | 1        | 1.16%   |
| LG Electronics                         | 1        | 1.16%   |
| Hewlett-Packard                        | 1        | 1.16%   |
| Guillemot                              | 1        | 1.16%   |
| Cubeternet                             | 1        | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 1.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                          | 14       | 16.28%  |
| Logitech Webcam C270                                                 | 11       | 12.79%  |
| Logitech StreamCam                                                   | 4        | 4.65%   |
| Microdia Webcam Vitade AF                                            | 3        | 3.49%   |
| Logitech HD Webcam C615                                              | 3        | 3.49%   |
| Generalplus GENERAL WEBCAM                                           | 3        | 3.49%   |
| Apple iPhone 5/5C/5S/6/SE                                            | 3        | 3.49%   |
| Logitech Webcam C170                                                 | 2        | 2.33%   |
| Logitech QuickCam Pro 9000                                           | 2        | 2.33%   |
| Logitech HD Webcam C525                                              | 2        | 2.33%   |
| Logitech C922 Pro Stream Webcam                                      | 2        | 2.33%   |
| Jieli USB PHY 2.0                                                    | 2        | 2.33%   |
| Genesys Logic Camera                                                 | 2        | 2.33%   |
| Creative Live! Cam Sync HD [VF0770]                                  | 2        | 2.33%   |
| Z-Star Venus USB2.0 Camera                                           | 1        | 1.16%   |
| Z-Star Sirius USB 2.0 Camera                                         | 1        | 1.16%   |
| Trust USB Camera                                                     | 1        | 1.16%   |
| Trust Full HD Webcam                                                 | 1        | 1.16%   |
| Sunplus HD 720P webcam                                               | 1        | 1.16%   |
| Sunplus ezcap U3 capture-04                                          | 1        | 1.16%   |
| Sonix USB Camera                                                     | 1        | 1.16%   |
| Samsung Galaxy series, misc. (MTP mode)                              | 1        | 1.16%   |
| Quanta HD Camera                                                     | 1        | 1.16%   |
| Microsoft Xbox NUI Camera                                            | 1        | 1.16%   |
| Microsoft LifeCam HD-3000                                            | 1        | 1.16%   |
| Microsoft LifeCam Cinema                                             | 1        | 1.16%   |
| Microdia CyberTrack H6                                               | 1        | 1.16%   |
| Micro Star International MSI USB Device                              | 1        | 1.16%   |
| Logitech Webcam Pro 9000                                             | 1        | 1.16%   |
| Logitech Webcam C930e                                                | 1        | 1.16%   |
| Logitech Webcam C310                                                 | 1        | 1.16%   |
| Logitech QuickCam Ultra Vision                                       | 1        | 1.16%   |
| Logitech QuickCam Communicate Deluxe                                 | 1        | 1.16%   |
| Logitech HD Webcam C510                                              | 1        | 1.16%   |
| Logitech BRIO                                                        | 1        | 1.16%   |
| LG AN-VC500 Camera                                                   | 1        | 1.16%   |
| Lenovo FULL HD 1080P Webcam                                          | 1        | 1.16%   |
| Lenovo 500 RGB Camera                                                | 1        | 1.16%   |
| KYE Systems (Mouse Systems) Genius iSlim 330                         | 1        | 1.16%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                            | 1        | 1.16%   |
| HP Webcam 1300                                                       | 1        | 1.16%   |
| Guillemot Hercules Dualpix Exchange                                  | 1        | 1.16%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101]  | 1        | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 1.16%   |
| Apple iSight in LED Cinema Display                                   | 1        | 1.16%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Yubico.com | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Yubico.com Yubikey 4/5 CCID | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 346      | 89.87%  |
| 1     | 35       | 9.09%   |
| 2     | 2        | 0.52%   |
| 5     | 1        | 0.26%   |
| 3     | 1        | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 30.95%  |
| Graphics card            | 12       | 28.57%  |
| Unassigned class         | 5        | 11.9%   |
| Communication controller | 5        | 11.9%   |
| Camera                   | 3        | 7.14%   |
| Sound                    | 2        | 4.76%   |
| Firewire controller      | 1        | 2.38%   |
| Bluetooth                | 1        | 2.38%   |


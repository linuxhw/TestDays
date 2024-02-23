Linux in Poland - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 9002

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Medion        | Z170H4-EA                   | Desktop     | [17c714c6b5](https://linux-hardware.org/?probe=17c714c6b5) | Feb 02, 2024 |
| Dell          | Latitude 7390               | Notebook    | [2386e8641f](https://linux-hardware.org/?probe=2386e8641f) | Feb 02, 2024 |
| Dell          | Latitude 7400               | Notebook    | [ad51cec5ea](https://linux-hardware.org/?probe=ad51cec5ea) | Feb 02, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [075ee0ca67](https://linux-hardware.org/?probe=075ee0ca67) | Feb 02, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [47431ad7d9](https://linux-hardware.org/?probe=47431ad7d9) | Feb 02, 2024 |
| Valve         | Galileo                     | Notebook    | [aebc4c73ad](https://linux-hardware.org/?probe=aebc4c73ad) | Feb 01, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fc6230e374](https://linux-hardware.org/?probe=fc6230e374) | Feb 01, 2024 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [5bf97512a7](https://linux-hardware.org/?probe=5bf97512a7) | Feb 01, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [c211b49a95](https://linux-hardware.org/?probe=c211b49a95) | Feb 01, 2024 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [ae13945074](https://linux-hardware.org/?probe=ae13945074) | Feb 01, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [c83dcb11ca](https://linux-hardware.org/?probe=c83dcb11ca) | Jan 31, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bf9814808f](https://linux-hardware.org/?probe=bf9814808f) | Jan 31, 2024 |
| HP            | Elite x360 830 13 inch G... | Convertible | [d8081ec509](https://linux-hardware.org/?probe=d8081ec509) | Jan 31, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [85c2cd9371](https://linux-hardware.org/?probe=85c2cd9371) | Jan 31, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [54beeb17dc](https://linux-hardware.org/?probe=54beeb17dc) | Jan 31, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [65272ffc77](https://linux-hardware.org/?probe=65272ffc77) | Jan 31, 2024 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [45a5318a64](https://linux-hardware.org/?probe=45a5318a64) | Jan 31, 2024 |
| HP            | ProBook 450 G8              | Notebook    | [f8d060061c](https://linux-hardware.org/?probe=f8d060061c) | Jan 30, 2024 |
| HP            | ProBook 450 G8              | Notebook    | [4ca13b7d13](https://linux-hardware.org/?probe=4ca13b7d13) | Jan 30, 2024 |
| Dell          | Latitude 3190               | Notebook    | [16f86af47d](https://linux-hardware.org/?probe=16f86af47d) | Jan 30, 2024 |
| ASUSTek       | P5QLD PRO                   | Desktop     | [2558422111](https://linux-hardware.org/?probe=2558422111) | Jan 30, 2024 |
| Lenovo        | ThinkPad T570 20HAS0NU00    | Notebook    | [39f3b9fb56](https://linux-hardware.org/?probe=39f3b9fb56) | Jan 30, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [c0f87d75df](https://linux-hardware.org/?probe=c0f87d75df) | Jan 29, 2024 |
| Dell          | Latitude E5420              | Notebook    | [fe49c198a3](https://linux-hardware.org/?probe=fe49c198a3) | Jan 29, 2024 |
| Dell          | Latitude E5420              | Notebook    | [d76191acac](https://linux-hardware.org/?probe=d76191acac) | Jan 29, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [9cbabba588](https://linux-hardware.org/?probe=9cbabba588) | Jan 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [913338a499](https://linux-hardware.org/?probe=913338a499) | Jan 29, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [12cf7dfeeb](https://linux-hardware.org/?probe=12cf7dfeeb) | Jan 29, 2024 |
| HP            | 805D                        | Desktop     | [81113f9b0d](https://linux-hardware.org/?probe=81113f9b0d) | Jan 29, 2024 |
| Dell          | Latitude 5511               | Notebook    | [40fad497db](https://linux-hardware.org/?probe=40fad497db) | Jan 29, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [66d4abe24d](https://linux-hardware.org/?probe=66d4abe24d) | Jan 29, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8949a81c2e](https://linux-hardware.org/?probe=8949a81c2e) | Jan 29, 2024 |
| MSI           | MS-B0961                    | All in one  | [5c66f68a0e](https://linux-hardware.org/?probe=5c66f68a0e) | Jan 29, 2024 |
| MSI           | MS-B0961                    | All in one  | [231209ac00](https://linux-hardware.org/?probe=231209ac00) | Jan 29, 2024 |
| HP            | ProLiant DL385p Gen8        | Server      | [c6ad62b067](https://linux-hardware.org/?probe=c6ad62b067) | Jan 28, 2024 |
| HP            | ProLiant DL380 G6           | Server      | [05b7c13538](https://linux-hardware.org/?probe=05b7c13538) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f20816d81d](https://linux-hardware.org/?probe=f20816d81d) | Jan 28, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [d508f78053](https://linux-hardware.org/?probe=d508f78053) | Jan 28, 2024 |
| eMachines     | eME732ZG                    | Notebook    | [50446e8377](https://linux-hardware.org/?probe=50446e8377) | Jan 28, 2024 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [5c4d08e0c4](https://linux-hardware.org/?probe=5c4d08e0c4) | Jan 28, 2024 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [d3d40bf0b4](https://linux-hardware.org/?probe=d3d40bf0b4) | Jan 28, 2024 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [d3bd3f1abf](https://linux-hardware.org/?probe=d3bd3f1abf) | Jan 28, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e17793cd71](https://linux-hardware.org/?probe=e17793cd71) | Jan 28, 2024 |
| Acer          | Aspire A715-42G             | Notebook    | [6e3e887615](https://linux-hardware.org/?probe=6e3e887615) | Jan 27, 2024 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [23059625c1](https://linux-hardware.org/?probe=23059625c1) | Jan 27, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [31fa6a22ea](https://linux-hardware.org/?probe=31fa6a22ea) | Jan 27, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a6b046b2b7](https://linux-hardware.org/?probe=a6b046b2b7) | Jan 27, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9eeddc4566](https://linux-hardware.org/?probe=9eeddc4566) | Jan 27, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [95541e0847](https://linux-hardware.org/?probe=95541e0847) | Jan 27, 2024 |
| HP            | ZBook 15 G5                 | Notebook    | [73e974c084](https://linux-hardware.org/?probe=73e974c084) | Jan 27, 2024 |
| Dell          | Latitude 5520               | Notebook    | [acedcebd94](https://linux-hardware.org/?probe=acedcebd94) | Jan 26, 2024 |
| mPTech        | Techbite ZIN 3              | Notebook    | [57234bbbc3](https://linux-hardware.org/?probe=57234bbbc3) | Jan 26, 2024 |
| MSI           | B250M BAZOOKA               | Desktop     | [0bd7085870](https://linux-hardware.org/?probe=0bd7085870) | Jan 26, 2024 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [01dd8556d5](https://linux-hardware.org/?probe=01dd8556d5) | Jan 26, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9b7cbb57c7](https://linux-hardware.org/?probe=9b7cbb57c7) | Jan 26, 2024 |
| HP            | 1589                        | Desktop     | [d731924276](https://linux-hardware.org/?probe=d731924276) | Jan 25, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [3ed9ff642f](https://linux-hardware.org/?probe=3ed9ff642f) | Jan 25, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [813ed73797](https://linux-hardware.org/?probe=813ed73797) | Jan 25, 2024 |
| Dell          | Latitude D620               | Notebook    | [d46bb1fc6b](https://linux-hardware.org/?probe=d46bb1fc6b) | Jan 25, 2024 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [d530eec023](https://linux-hardware.org/?probe=d530eec023) | Jan 25, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [347b980bdf](https://linux-hardware.org/?probe=347b980bdf) | Jan 25, 2024 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [f05b3ce6a1](https://linux-hardware.org/?probe=f05b3ce6a1) | Jan 25, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [869af9b5c0](https://linux-hardware.org/?probe=869af9b5c0) | Jan 25, 2024 |
| HP            | Pavilion dv6                | Notebook    | [073fe44f35](https://linux-hardware.org/?probe=073fe44f35) | Jan 24, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [ea518cb09d](https://linux-hardware.org/?probe=ea518cb09d) | Jan 24, 2024 |
| Samsung       | 450R4E/450R5E/450R4V/450... | Notebook    | [0f69d36c02](https://linux-hardware.org/?probe=0f69d36c02) | Jan 24, 2024 |
| Toshiba       | Satellite C650              | Notebook    | [2fa418e377](https://linux-hardware.org/?probe=2fa418e377) | Jan 24, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [b687521689](https://linux-hardware.org/?probe=b687521689) | Jan 24, 2024 |
| Dell          | Inspiron 7559               | Notebook    | [b82f00532c](https://linux-hardware.org/?probe=b82f00532c) | Jan 24, 2024 |
| Toshiba       | Satellite L40               | Notebook    | [0f0ab308a5](https://linux-hardware.org/?probe=0f0ab308a5) | Jan 23, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [b0c74cf9c0](https://linux-hardware.org/?probe=b0c74cf9c0) | Jan 23, 2024 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | Notebook    | [27804a7892](https://linux-hardware.org/?probe=27804a7892) | Jan 23, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7039b3ef95](https://linux-hardware.org/?probe=7039b3ef95) | Jan 23, 2024 |
| Google        | Kefka                       | Notebook    | [6cb0b95d02](https://linux-hardware.org/?probe=6cb0b95d02) | Jan 22, 2024 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [03a6ed21ba](https://linux-hardware.org/?probe=03a6ed21ba) | Jan 22, 2024 |
| ASUSTek       | X550VC                      | Notebook    | [90ebdf4197](https://linux-hardware.org/?probe=90ebdf4197) | Jan 22, 2024 |
| Acer          | Swift SFX14-51G             | Notebook    | [ac8dbddf38](https://linux-hardware.org/?probe=ac8dbddf38) | Jan 22, 2024 |
| MSI           | Z87-G43 GAMING              | Desktop     | [09efa6e85b](https://linux-hardware.org/?probe=09efa6e85b) | Jan 22, 2024 |
| MSI           | Z87-G43 GAMING              | Desktop     | [4966a58d3c](https://linux-hardware.org/?probe=4966a58d3c) | Jan 22, 2024 |
| HP            | ProBook 6560b               | Notebook    | [6d2bbcc556](https://linux-hardware.org/?probe=6d2bbcc556) | Jan 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [9a1d16aad2](https://linux-hardware.org/?probe=9a1d16aad2) | Jan 21, 2024 |
| Samsung       | X420/X520                   | Notebook    | [9dae8bd2c2](https://linux-hardware.org/?probe=9dae8bd2c2) | Jan 21, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [73c6b8874b](https://linux-hardware.org/?probe=73c6b8874b) | Jan 21, 2024 |
| HP            | 213D A01                    | Desktop     | [37b7fb4c4e](https://linux-hardware.org/?probe=37b7fb4c4e) | Jan 20, 2024 |
| Gigabyte      | H310M S2V                   | Desktop     | [7be62ed879](https://linux-hardware.org/?probe=7be62ed879) | Jan 20, 2024 |
| HP            | 8055                        | Desktop     | [5e6a445b12](https://linux-hardware.org/?probe=5e6a445b12) | Jan 19, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5174a4a05a](https://linux-hardware.org/?probe=5174a4a05a) | Jan 19, 2024 |
| HP            | Pavilion dv7                | Notebook    | [da67ecc7a4](https://linux-hardware.org/?probe=da67ecc7a4) | Jan 18, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [66b278bb03](https://linux-hardware.org/?probe=66b278bb03) | Jan 18, 2024 |
| Dream Mach... | NS5x_NS7xPU                 | Notebook    | [d4604f53fc](https://linux-hardware.org/?probe=d4604f53fc) | Jan 17, 2024 |
| HP            | 1998                        | Desktop     | [b193235ba4](https://linux-hardware.org/?probe=b193235ba4) | Jan 17, 2024 |
| Acer          | Aspire E1-531G              | Notebook    | [2c64046f89](https://linux-hardware.org/?probe=2c64046f89) | Jan 17, 2024 |
| MSI           | A68HM-E33 V2                | Desktop     | [da97b5c9f5](https://linux-hardware.org/?probe=da97b5c9f5) | Jan 17, 2024 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d8e4449d99](https://linux-hardware.org/?probe=d8e4449d99) | Jan 16, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [48399b3fc4](https://linux-hardware.org/?probe=48399b3fc4) | Jan 16, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [dc21da33ed](https://linux-hardware.org/?probe=dc21da33ed) | Jan 16, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [cb1fa259a7](https://linux-hardware.org/?probe=cb1fa259a7) | Jan 16, 2024 |
| Toshiba       | Satellite L40               | Notebook    | [f5e9dbe1c8](https://linux-hardware.org/?probe=f5e9dbe1c8) | Jan 16, 2024 |
| HP            | 8617                        | Desktop     | [4ea51313bd](https://linux-hardware.org/?probe=4ea51313bd) | Jan 15, 2024 |
| HP            | EliteBook 830 13 inch G1... | Notebook    | [d462837d11](https://linux-hardware.org/?probe=d462837d11) | Jan 15, 2024 |
| Dell          | 09CGW2 A08                  | Server      | [017c48fd55](https://linux-hardware.org/?probe=017c48fd55) | Jan 14, 2024 |
| Dell          | 09CGW2 A08                  | Server      | [39383a063d](https://linux-hardware.org/?probe=39383a063d) | Jan 14, 2024 |
| Dell          | Latitude E4310              | Notebook    | [a11f178faf](https://linux-hardware.org/?probe=a11f178faf) | Jan 14, 2024 |
| Toshiba       | Satellite C55-A-1H9         | Notebook    | [7fa6a6c318](https://linux-hardware.org/?probe=7fa6a6c318) | Jan 14, 2024 |
| Dell          | Inspiron 5515               | Notebook    | [6523b11a61](https://linux-hardware.org/?probe=6523b11a61) | Jan 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [51d79bc7e2](https://linux-hardware.org/?probe=51d79bc7e2) | Jan 14, 2024 |
| ASRock        | 970 Extreme4                | Desktop     | [7c02fff797](https://linux-hardware.org/?probe=7c02fff797) | Jan 13, 2024 |
| ASRock        | 970 Extreme4                | Desktop     | [9956a82d50](https://linux-hardware.org/?probe=9956a82d50) | Jan 13, 2024 |
| HP            | Compaq 6720s                | Notebook    | [4b6c283ab3](https://linux-hardware.org/?probe=4b6c283ab3) | Jan 13, 2024 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [cd57f74a31](https://linux-hardware.org/?probe=cd57f74a31) | Jan 13, 2024 |
| HP            | 1589                        | Desktop     | [194b5a119c](https://linux-hardware.org/?probe=194b5a119c) | Jan 13, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [9fbe7a7217](https://linux-hardware.org/?probe=9fbe7a7217) | Jan 13, 2024 |
| ASUSTek       | Z87-C                       | Desktop     | [acc914cabd](https://linux-hardware.org/?probe=acc914cabd) | Jan 12, 2024 |
| ASRock        | B360M Pro4                  | Desktop     | [054186ab28](https://linux-hardware.org/?probe=054186ab28) | Jan 12, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [132b261039](https://linux-hardware.org/?probe=132b261039) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [a7a2eedaec](https://linux-hardware.org/?probe=a7a2eedaec) | Jan 12, 2024 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [f67cc2282f](https://linux-hardware.org/?probe=f67cc2282f) | Jan 12, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [655eb2734a](https://linux-hardware.org/?probe=655eb2734a) | Jan 11, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [2e0a03aba1](https://linux-hardware.org/?probe=2e0a03aba1) | Jan 11, 2024 |
| HP            | 530 Notebook PC(GH634AA#... | Notebook    | [a17c4145f4](https://linux-hardware.org/?probe=a17c4145f4) | Jan 11, 2024 |
| MSI           | B450M MORTAR                | Desktop     | [1d1f76da3c](https://linux-hardware.org/?probe=1d1f76da3c) | Jan 11, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [7b242e0b03](https://linux-hardware.org/?probe=7b242e0b03) | Jan 11, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [a4cfa8b935](https://linux-hardware.org/?probe=a4cfa8b935) | Jan 11, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | Notebook    | [9066b38bfc](https://linux-hardware.org/?probe=9066b38bfc) | Jan 11, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [bdddc03230](https://linux-hardware.org/?probe=bdddc03230) | Jan 11, 2024 |
| Dell          | 0D24M8 A00                  | Desktop     | [a482ed79df](https://linux-hardware.org/?probe=a482ed79df) | Jan 11, 2024 |
| Dell          | 0773VG A02                  | Desktop     | [f06d515c8d](https://linux-hardware.org/?probe=f06d515c8d) | Jan 11, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [0c54141bbd](https://linux-hardware.org/?probe=0c54141bbd) | Jan 11, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [3117cde827](https://linux-hardware.org/?probe=3117cde827) | Jan 11, 2024 |
| Google        | Phaser360                   | Notebook    | [7402fc6e46](https://linux-hardware.org/?probe=7402fc6e46) | Jan 11, 2024 |
| Dell          | 0T1D10 A01                  | Desktop     | [0c1256487e](https://linux-hardware.org/?probe=0c1256487e) | Jan 11, 2024 |
| Dell          | Latitude E7440              | Notebook    | [08decb079c](https://linux-hardware.org/?probe=08decb079c) | Jan 11, 2024 |
| Dell          | Latitude E7240              | Notebook    | [5661525290](https://linux-hardware.org/?probe=5661525290) | Jan 11, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a14291c1d2](https://linux-hardware.org/?probe=a14291c1d2) | Jan 11, 2024 |
| Dell          | 0JRTXX A00                  | Mini pc     | [3d30ab92ce](https://linux-hardware.org/?probe=3d30ab92ce) | Jan 10, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [fb2aecbc70](https://linux-hardware.org/?probe=fb2aecbc70) | Jan 10, 2024 |
| MSI           | Z87I                        | Desktop     | [35114b37dd](https://linux-hardware.org/?probe=35114b37dd) | Jan 10, 2024 |
| Dell          | Inspiron 7737               | Notebook    | [ae41cf1d2f](https://linux-hardware.org/?probe=ae41cf1d2f) | Jan 10, 2024 |
| Acer          | Aspire A715-74G             | Notebook    | [4d6e4c3464](https://linux-hardware.org/?probe=4d6e4c3464) | Jan 10, 2024 |
| Acer          | TravelMate 8572G            | Notebook    | [4322118152](https://linux-hardware.org/?probe=4322118152) | Jan 10, 2024 |
| Dell          | Latitude 5521               | Notebook    | [8058baf2cb](https://linux-hardware.org/?probe=8058baf2cb) | Jan 10, 2024 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [302723b72f](https://linux-hardware.org/?probe=302723b72f) | Jan 10, 2024 |
| ASUSTek       | P5K-E                       | Desktop     | [1cacfbcadd](https://linux-hardware.org/?probe=1cacfbcadd) | Jan 09, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [34eaf45d7f](https://linux-hardware.org/?probe=34eaf45d7f) | Jan 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [62bf989a58](https://linux-hardware.org/?probe=62bf989a58) | Jan 09, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [62b2915f0f](https://linux-hardware.org/?probe=62b2915f0f) | Jan 09, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [9446a22c53](https://linux-hardware.org/?probe=9446a22c53) | Jan 09, 2024 |
| Dell          | Latitude 3190               | Notebook    | [afdd5a1dbe](https://linux-hardware.org/?probe=afdd5a1dbe) | Jan 09, 2024 |
| Lenovo        | IdeaPad Y530                | Notebook    | [344509ac97](https://linux-hardware.org/?probe=344509ac97) | Jan 08, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [4001af92e2](https://linux-hardware.org/?probe=4001af92e2) | Jan 08, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [4b6c5e1edb](https://linux-hardware.org/?probe=4b6c5e1edb) | Jan 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [bddd9671c1](https://linux-hardware.org/?probe=bddd9671c1) | Jan 08, 2024 |
| Lenovo        | ThinkPad L540 20AUA1E600    | Notebook    | [9d0e13031a](https://linux-hardware.org/?probe=9d0e13031a) | Jan 08, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ded26713a9](https://linux-hardware.org/?probe=ded26713a9) | Jan 08, 2024 |
| Samsung       | Galaxy Tab 4 10.1 WiFi (... | Soc         | [9097684f8c](https://linux-hardware.org/?probe=9097684f8c) | Jan 08, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [363ad22f1d](https://linux-hardware.org/?probe=363ad22f1d) | Jan 08, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [a9f2ff1fc3](https://linux-hardware.org/?probe=a9f2ff1fc3) | Jan 07, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [dac2172dc5](https://linux-hardware.org/?probe=dac2172dc5) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [770f12c749](https://linux-hardware.org/?probe=770f12c749) | Jan 07, 2024 |
| Lenovo        | B50-70 20384                | Notebook    | [87e302df7b](https://linux-hardware.org/?probe=87e302df7b) | Jan 07, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [db24e06c04](https://linux-hardware.org/?probe=db24e06c04) | Jan 07, 2024 |
| Dell          | G3 3579                     | Notebook    | [5c48d53216](https://linux-hardware.org/?probe=5c48d53216) | Jan 07, 2024 |
| Dell          | G3 3579                     | Notebook    | [6ee6a6d56a](https://linux-hardware.org/?probe=6ee6a6d56a) | Jan 07, 2024 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b543dba019](https://linux-hardware.org/?probe=b543dba019) | Jan 07, 2024 |
| Toshiba       | Satellite C55-A-1H9         | Notebook    | [ab8c5bc566](https://linux-hardware.org/?probe=ab8c5bc566) | Jan 07, 2024 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [a642b9a382](https://linux-hardware.org/?probe=a642b9a382) | Jan 07, 2024 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [ea07a49b87](https://linux-hardware.org/?probe=ea07a49b87) | Jan 07, 2024 |
| HP            | ZBook 17 G6                 | Notebook    | [89cde2f9d4](https://linux-hardware.org/?probe=89cde2f9d4) | Jan 06, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [41582699c7](https://linux-hardware.org/?probe=41582699c7) | Jan 06, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0f5ae64d19](https://linux-hardware.org/?probe=0f5ae64d19) | Jan 06, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [0a9a88c59f](https://linux-hardware.org/?probe=0a9a88c59f) | Jan 06, 2024 |
| Dell          | Latitude 7420               | Notebook    | [7b6c854eaf](https://linux-hardware.org/?probe=7b6c854eaf) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3be696b6a2](https://linux-hardware.org/?probe=3be696b6a2) | Jan 06, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [a7c6792366](https://linux-hardware.org/?probe=a7c6792366) | Jan 05, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [bb1b5c33d2](https://linux-hardware.org/?probe=bb1b5c33d2) | Jan 05, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [0f56b6d674](https://linux-hardware.org/?probe=0f56b6d674) | Jan 05, 2024 |
| Dell          | 0T1D10 A01                  | Desktop     | [36fd42ae37](https://linux-hardware.org/?probe=36fd42ae37) | Jan 05, 2024 |
| HP            | Compaq 6730s                | Notebook    | [1ad2b54c9d](https://linux-hardware.org/?probe=1ad2b54c9d) | Jan 05, 2024 |
| ASRock        | X670E Pro RS                | Desktop     | [d7b3301bdb](https://linux-hardware.org/?probe=d7b3301bdb) | Jan 05, 2024 |
| Lenovo        | V15 G3 IAP CTO 83C4         | Notebook    | [050c0c3ac6](https://linux-hardware.org/?probe=050c0c3ac6) | Jan 04, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7bf93755f2](https://linux-hardware.org/?probe=7bf93755f2) | Jan 04, 2024 |
| Samsung       | DP700A3D-X01PL SEC_SW_RE... | All in one  | [d46262e2ef](https://linux-hardware.org/?probe=d46262e2ef) | Jan 04, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [da0c7ff210](https://linux-hardware.org/?probe=da0c7ff210) | Jan 04, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [436f8ebcc9](https://linux-hardware.org/?probe=436f8ebcc9) | Jan 04, 2024 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [5ca009faf3](https://linux-hardware.org/?probe=5ca009faf3) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [c085db23b6](https://linux-hardware.org/?probe=c085db23b6) | Jan 04, 2024 |
| HP            | Stream Notebook PC 13       | Notebook    | [35597f6ed8](https://linux-hardware.org/?probe=35597f6ed8) | Jan 03, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e98a083e68](https://linux-hardware.org/?probe=e98a083e68) | Jan 03, 2024 |
| Dell          | Inspiron 5502               | Notebook    | [3486d53d60](https://linux-hardware.org/?probe=3486d53d60) | Jan 03, 2024 |
| AMI           | Cherry Trail CR             | Notebook    | [35f5071102](https://linux-hardware.org/?probe=35f5071102) | Jan 03, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [ee8caab1b7](https://linux-hardware.org/?probe=ee8caab1b7) | Jan 03, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [457ba2586a](https://linux-hardware.org/?probe=457ba2586a) | Jan 03, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [063cb7f7f8](https://linux-hardware.org/?probe=063cb7f7f8) | Jan 02, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a0e025d32d](https://linux-hardware.org/?probe=a0e025d32d) | Jan 02, 2024 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [2db319c529](https://linux-hardware.org/?probe=2db319c529) | Jan 02, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [01650ef12d](https://linux-hardware.org/?probe=01650ef12d) | Jan 02, 2024 |
| Dell          | Inspiron 13-5368            | Notebook    | [811a112c63](https://linux-hardware.org/?probe=811a112c63) | Jan 02, 2024 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4389374c55](https://linux-hardware.org/?probe=4389374c55) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [de7126bf06](https://linux-hardware.org/?probe=de7126bf06) | Jan 01, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2f74327d87](https://linux-hardware.org/?probe=2f74327d87) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | Notebook    | [34dd6e3ec3](https://linux-hardware.org/?probe=34dd6e3ec3) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | Notebook    | [4b00ffd071](https://linux-hardware.org/?probe=4b00ffd071) | Jan 01, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [3b6183bbb5](https://linux-hardware.org/?probe=3b6183bbb5) | Dec 31, 2023 |
| Dell          | Latitude 7420               | Notebook    | [a32d08979b](https://linux-hardware.org/?probe=a32d08979b) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [cd2840bccc](https://linux-hardware.org/?probe=cd2840bccc) | Dec 31, 2023 |
| Lenovo        | ThinkCentre M91p 7005A21    | Desktop     | [043bcfc503](https://linux-hardware.org/?probe=043bcfc503) | Dec 31, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [f5f0fa82e5](https://linux-hardware.org/?probe=f5f0fa82e5) | Dec 31, 2023 |
| Dell          | Latitude 7420               | Notebook    | [9bee55a186](https://linux-hardware.org/?probe=9bee55a186) | Dec 31, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [1a25482d3d](https://linux-hardware.org/?probe=1a25482d3d) | Dec 31, 2023 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | Notebook    | [1fedc1bf30](https://linux-hardware.org/?probe=1fedc1bf30) | Dec 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [bbae93d767](https://linux-hardware.org/?probe=bbae93d767) | Dec 31, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e51fc438b3](https://linux-hardware.org/?probe=e51fc438b3) | Dec 31, 2023 |
| Lenovo        | ThinkCentre M91p 7005A21    | Desktop     | [e783d0ce11](https://linux-hardware.org/?probe=e783d0ce11) | Dec 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [49a4d9cad0](https://linux-hardware.org/?probe=49a4d9cad0) | Dec 31, 2023 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [451e3803a0](https://linux-hardware.org/?probe=451e3803a0) | Dec 31, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [1a5d669774](https://linux-hardware.org/?probe=1a5d669774) | Dec 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [4f95b9d510](https://linux-hardware.org/?probe=4f95b9d510) | Dec 30, 2023 |
| HP            | 1494                        | Desktop     | [a7618ec01a](https://linux-hardware.org/?probe=a7618ec01a) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f391231013](https://linux-hardware.org/?probe=f391231013) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | Notebook    | [8cb3a2ee0a](https://linux-hardware.org/?probe=8cb3a2ee0a) | Dec 30, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [c914756956](https://linux-hardware.org/?probe=c914756956) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4YE0... | Notebook    | [74d75dc18d](https://linux-hardware.org/?probe=74d75dc18d) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4UD0... | Notebook    | [0305a2f3cf](https://linux-hardware.org/?probe=0305a2f3cf) | Dec 30, 2023 |
| Dell          | Latitude E7440              | Notebook    | [d9fb6a9ead](https://linux-hardware.org/?probe=d9fb6a9ead) | Dec 30, 2023 |
| HP            | Notebook                    | Notebook    | [c5f68d3103](https://linux-hardware.org/?probe=c5f68d3103) | Dec 30, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [4744ad0a98](https://linux-hardware.org/?probe=4744ad0a98) | Dec 30, 2023 |
| Lenovo        | ThinkPad T430 2349FC4       | Notebook    | [689d3295aa](https://linux-hardware.org/?probe=689d3295aa) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | Notebook    | [274f6e86fc](https://linux-hardware.org/?probe=274f6e86fc) | Dec 29, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0e612ffdf7](https://linux-hardware.org/?probe=0e612ffdf7) | Dec 29, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [99561c9ed3](https://linux-hardware.org/?probe=99561c9ed3) | Dec 29, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [13e6674db0](https://linux-hardware.org/?probe=13e6674db0) | Dec 29, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [cf4b641dde](https://linux-hardware.org/?probe=cf4b641dde) | Dec 29, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [aa3f2ed203](https://linux-hardware.org/?probe=aa3f2ed203) | Dec 29, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [09f37233e4](https://linux-hardware.org/?probe=09f37233e4) | Dec 29, 2023 |
| MSI           | B250 PC MATE                | Desktop     | [5429df4a6b](https://linux-hardware.org/?probe=5429df4a6b) | Dec 29, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [0a6df1d55f](https://linux-hardware.org/?probe=0a6df1d55f) | Dec 28, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [fa779d28cc](https://linux-hardware.org/?probe=fa779d28cc) | Dec 28, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [66f68b08bd](https://linux-hardware.org/?probe=66f68b08bd) | Dec 28, 2023 |
| MSI           | GS70 2OD                    | Notebook    | [13dab050a1](https://linux-hardware.org/?probe=13dab050a1) | Dec 28, 2023 |
| MSI           | GS70 2OD                    | Notebook    | [7092678d3b](https://linux-hardware.org/?probe=7092678d3b) | Dec 28, 2023 |
| Intel         | NUC6CAYB J23203-407         | Mini pc     | [11883e6f6c](https://linux-hardware.org/?probe=11883e6f6c) | Dec 28, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [c9ac7b8022](https://linux-hardware.org/?probe=c9ac7b8022) | Dec 28, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [755facbd26](https://linux-hardware.org/?probe=755facbd26) | Dec 28, 2023 |
| TrekStor      | Notebook Slim S130          | Notebook    | [9fbe38b102](https://linux-hardware.org/?probe=9fbe38b102) | Dec 28, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [f1144c99b2](https://linux-hardware.org/?probe=f1144c99b2) | Dec 27, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [fe315c0cf8](https://linux-hardware.org/?probe=fe315c0cf8) | Dec 27, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [619ddf5210](https://linux-hardware.org/?probe=619ddf5210) | Dec 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [e0b1c57cc6](https://linux-hardware.org/?probe=e0b1c57cc6) | Dec 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [983d2046a3](https://linux-hardware.org/?probe=983d2046a3) | Dec 27, 2023 |
| Dell          | Latitude 5400               | Notebook    | [4c2ddb74c4](https://linux-hardware.org/?probe=4c2ddb74c4) | Dec 27, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [a8871fb21b](https://linux-hardware.org/?probe=a8871fb21b) | Dec 27, 2023 |
| Hampoo        | L1W6_I1101_C Reserved       | Notebook    | [ad4de7dcab](https://linux-hardware.org/?probe=ad4de7dcab) | Dec 26, 2023 |
| Dell          | Latitude E7450              | Notebook    | [84dc5f09e7](https://linux-hardware.org/?probe=84dc5f09e7) | Dec 26, 2023 |
| Dell          | Latitude 5400               | Notebook    | [35adbae547](https://linux-hardware.org/?probe=35adbae547) | Dec 26, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [8b68f422dd](https://linux-hardware.org/?probe=8b68f422dd) | Dec 26, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [9c32017999](https://linux-hardware.org/?probe=9c32017999) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f58bf5fe4c](https://linux-hardware.org/?probe=f58bf5fe4c) | Dec 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [e0da711bcb](https://linux-hardware.org/?probe=e0da711bcb) | Dec 26, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [ed9f6e6354](https://linux-hardware.org/?probe=ed9f6e6354) | Dec 26, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b35c9836e7](https://linux-hardware.org/?probe=b35c9836e7) | Dec 26, 2023 |
| Lenovo        | ThinkPad E470 20H1004UIG    | Notebook    | [69efda7672](https://linux-hardware.org/?probe=69efda7672) | Dec 26, 2023 |
| Lenovo        | ThinkPad T500 20828WG       | Notebook    | [a3edf5e69b](https://linux-hardware.org/?probe=a3edf5e69b) | Dec 26, 2023 |
| Acer          | Nitro AN16-41               | Notebook    | [ae0d837def](https://linux-hardware.org/?probe=ae0d837def) | Dec 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a35ed82108](https://linux-hardware.org/?probe=a35ed82108) | Dec 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [d9ec9cb0f7](https://linux-hardware.org/?probe=d9ec9cb0f7) | Dec 26, 2023 |
| Dell          | Precision M4500             | Notebook    | [a98dcc4861](https://linux-hardware.org/?probe=a98dcc4861) | Dec 26, 2023 |
| MSI           | B85-G43                     | Desktop     | [fd632d7a1f](https://linux-hardware.org/?probe=fd632d7a1f) | Dec 25, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [4c20fee408](https://linux-hardware.org/?probe=4c20fee408) | Dec 25, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [54ca5c9e74](https://linux-hardware.org/?probe=54ca5c9e74) | Dec 25, 2023 |
| Dell          | Latitude 5400               | Notebook    | [7ddd773af2](https://linux-hardware.org/?probe=7ddd773af2) | Dec 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [47255f4ba3](https://linux-hardware.org/?probe=47255f4ba3) | Dec 25, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [cba7a81460](https://linux-hardware.org/?probe=cba7a81460) | Dec 25, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [5820853b65](https://linux-hardware.org/?probe=5820853b65) | Dec 24, 2023 |
| Lenovo        | ThinkCentre M81 5049RK4     | Desktop     | [9ea1bc22a1](https://linux-hardware.org/?probe=9ea1bc22a1) | Dec 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [4c98f6b6f3](https://linux-hardware.org/?probe=4c98f6b6f3) | Dec 24, 2023 |
| ASRock        | Z790 PG Lightning           | Desktop     | [0b5268372a](https://linux-hardware.org/?probe=0b5268372a) | Dec 24, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [c9bcc97e5b](https://linux-hardware.org/?probe=c9bcc97e5b) | Dec 24, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [4452cd4a25](https://linux-hardware.org/?probe=4452cd4a25) | Dec 24, 2023 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [ef61ad2663](https://linux-hardware.org/?probe=ef61ad2663) | Dec 24, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0600... | Notebook    | [07efd36bbe](https://linux-hardware.org/?probe=07efd36bbe) | Dec 24, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [a90623afe1](https://linux-hardware.org/?probe=a90623afe1) | Dec 23, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [996611fcab](https://linux-hardware.org/?probe=996611fcab) | Dec 23, 2023 |
| Dell          | Latitude E6530              | Notebook    | [2a62f5f318](https://linux-hardware.org/?probe=2a62f5f318) | Dec 23, 2023 |
| Dell          | Latitude E6530              | Notebook    | [2d9ff2bdb9](https://linux-hardware.org/?probe=2d9ff2bdb9) | Dec 23, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [45b0f5ae9a](https://linux-hardware.org/?probe=45b0f5ae9a) | Dec 23, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [dc2914021f](https://linux-hardware.org/?probe=dc2914021f) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | Desktop     | [739d4b0840](https://linux-hardware.org/?probe=739d4b0840) | Dec 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [da051b693c](https://linux-hardware.org/?probe=da051b693c) | Dec 23, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [9bf64ae4b7](https://linux-hardware.org/?probe=9bf64ae4b7) | Dec 23, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [8f1a82681b](https://linux-hardware.org/?probe=8f1a82681b) | Dec 22, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [44b0b8bd05](https://linux-hardware.org/?probe=44b0b8bd05) | Dec 22, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [33d1b64e50](https://linux-hardware.org/?probe=33d1b64e50) | Dec 22, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [58a2ef76f9](https://linux-hardware.org/?probe=58a2ef76f9) | Dec 22, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [8191965e71](https://linux-hardware.org/?probe=8191965e71) | Dec 22, 2023 |
| Dell          | Latitude 5440               | Notebook    | [d7462b97ac](https://linux-hardware.org/?probe=d7462b97ac) | Dec 22, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [c6cefd749d](https://linux-hardware.org/?probe=c6cefd749d) | Dec 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [6e6d4fec11](https://linux-hardware.org/?probe=6e6d4fec11) | Dec 21, 2023 |
| Dell          | Precision M6600             | Notebook    | [5e387ee3ac](https://linux-hardware.org/?probe=5e387ee3ac) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ec0a846182](https://linux-hardware.org/?probe=ec0a846182) | Dec 21, 2023 |
| Lenovo        | ThinkPad SL 2746E9G         | Notebook    | [594a56a070](https://linux-hardware.org/?probe=594a56a070) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [5632b47c38](https://linux-hardware.org/?probe=5632b47c38) | Dec 21, 2023 |
| Dell          | Latitude E6320              | Notebook    | [a1e4b48d85](https://linux-hardware.org/?probe=a1e4b48d85) | Dec 20, 2023 |
| Hampoo        | Cherry Trail CR             | Desktop     | [2c180fa555](https://linux-hardware.org/?probe=2c180fa555) | Dec 20, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [a2f7b09b87](https://linux-hardware.org/?probe=a2f7b09b87) | Dec 20, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [f46e034f2c](https://linux-hardware.org/?probe=f46e034f2c) | Dec 20, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [c931f0f65a](https://linux-hardware.org/?probe=c931f0f65a) | Dec 20, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [5615091c1d](https://linux-hardware.org/?probe=5615091c1d) | Dec 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [6f1ca9e563](https://linux-hardware.org/?probe=6f1ca9e563) | Dec 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [13072c9ecc](https://linux-hardware.org/?probe=13072c9ecc) | Dec 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a7e488632e](https://linux-hardware.org/?probe=a7e488632e) | Dec 19, 2023 |
| Google        | Phaser360                   | Notebook    | [c739678794](https://linux-hardware.org/?probe=c739678794) | Dec 18, 2023 |
| Dell          | Latitude E6440              | Notebook    | [8d1b130773](https://linux-hardware.org/?probe=8d1b130773) | Dec 18, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [ffff088d9c](https://linux-hardware.org/?probe=ffff088d9c) | Dec 18, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [89fd7ee431](https://linux-hardware.org/?probe=89fd7ee431) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [1a1a04845b](https://linux-hardware.org/?probe=1a1a04845b) | Dec 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [3504b628f1](https://linux-hardware.org/?probe=3504b628f1) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [fcc1139818](https://linux-hardware.org/?probe=fcc1139818) | Dec 18, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e0b7c61c9f](https://linux-hardware.org/?probe=e0b7c61c9f) | Dec 18, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [2860ba102d](https://linux-hardware.org/?probe=2860ba102d) | Dec 18, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [24edc4b12c](https://linux-hardware.org/?probe=24edc4b12c) | Dec 17, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [8d45a13b61](https://linux-hardware.org/?probe=8d45a13b61) | Dec 17, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [9d204d6a41](https://linux-hardware.org/?probe=9d204d6a41) | Dec 17, 2023 |
| ASUSTek       | K84L                        | Notebook    | [3e0ea1ca0a](https://linux-hardware.org/?probe=3e0ea1ca0a) | Dec 17, 2023 |
| MSI           | MS-7255                     | Desktop     | [efdf3ede47](https://linux-hardware.org/?probe=efdf3ede47) | Dec 17, 2023 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [d0b623f72b](https://linux-hardware.org/?probe=d0b623f72b) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [7ebbee0896](https://linux-hardware.org/?probe=7ebbee0896) | Dec 17, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [73df6dfb3b](https://linux-hardware.org/?probe=73df6dfb3b) | Dec 16, 2023 |
| Google        | Phaser360                   | Notebook    | [784ed40440](https://linux-hardware.org/?probe=784ed40440) | Dec 16, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [f7ffef008a](https://linux-hardware.org/?probe=f7ffef008a) | Dec 16, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [fc9b36317a](https://linux-hardware.org/?probe=fc9b36317a) | Dec 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [3907c9bfa3](https://linux-hardware.org/?probe=3907c9bfa3) | Dec 16, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [b6afc3e929](https://linux-hardware.org/?probe=b6afc3e929) | Dec 16, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [7928703207](https://linux-hardware.org/?probe=7928703207) | Dec 16, 2023 |
| HP            | 8265                        | Desktop     | [58cc9fa090](https://linux-hardware.org/?probe=58cc9fa090) | Dec 16, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [091abf1a59](https://linux-hardware.org/?probe=091abf1a59) | Dec 16, 2023 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [125cbeedba](https://linux-hardware.org/?probe=125cbeedba) | Dec 15, 2023 |
| Dell          | Latitude E5410              | Notebook    | [ee4251c01c](https://linux-hardware.org/?probe=ee4251c01c) | Dec 15, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [7f5a3db82c](https://linux-hardware.org/?probe=7f5a3db82c) | Dec 15, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | Notebook    | [c2186c6471](https://linux-hardware.org/?probe=c2186c6471) | Dec 14, 2023 |
| MSI           | GT70 2OC/2OD                | Notebook    | [22910f80b0](https://linux-hardware.org/?probe=22910f80b0) | Dec 14, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [326d6a97b8](https://linux-hardware.org/?probe=326d6a97b8) | Dec 14, 2023 |
| HP            | 1495                        | Desktop     | [bd97989dd8](https://linux-hardware.org/?probe=bd97989dd8) | Dec 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c8d2a05aea](https://linux-hardware.org/?probe=c8d2a05aea) | Dec 14, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [a51734cec9](https://linux-hardware.org/?probe=a51734cec9) | Dec 13, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [6f5272ea27](https://linux-hardware.org/?probe=6f5272ea27) | Dec 13, 2023 |
| Dell          | Latitude E6440              | Notebook    | [cf0bb02399](https://linux-hardware.org/?probe=cf0bb02399) | Dec 13, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [0e87f04695](https://linux-hardware.org/?probe=0e87f04695) | Dec 12, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [82f5fec0c4](https://linux-hardware.org/?probe=82f5fec0c4) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [2f96568c78](https://linux-hardware.org/?probe=2f96568c78) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [68fe94d3be](https://linux-hardware.org/?probe=68fe94d3be) | Dec 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [9b92833e92](https://linux-hardware.org/?probe=9b92833e92) | Dec 12, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [56e614b2fe](https://linux-hardware.org/?probe=56e614b2fe) | Dec 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [faf8105e3c](https://linux-hardware.org/?probe=faf8105e3c) | Dec 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1c38d5c24a](https://linux-hardware.org/?probe=1c38d5c24a) | Dec 12, 2023 |
| MSI           | H61M-E33                    | Desktop     | [6123a79100](https://linux-hardware.org/?probe=6123a79100) | Dec 12, 2023 |
| HP            | Laptop                      | Notebook    | [8bdb6d048e](https://linux-hardware.org/?probe=8bdb6d048e) | Dec 11, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [a46aa4d97c](https://linux-hardware.org/?probe=a46aa4d97c) | Dec 11, 2023 |
| Dell          | Precision 7520              | Notebook    | [d0f203dcb1](https://linux-hardware.org/?probe=d0f203dcb1) | Dec 11, 2023 |
| Dell          | Precision 7520              | Notebook    | [2e02455101](https://linux-hardware.org/?probe=2e02455101) | Dec 11, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [baec95bb2f](https://linux-hardware.org/?probe=baec95bb2f) | Dec 11, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9e23503add](https://linux-hardware.org/?probe=9e23503add) | Dec 11, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [e07d68d658](https://linux-hardware.org/?probe=e07d68d658) | Dec 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8bf4107eed](https://linux-hardware.org/?probe=8bf4107eed) | Dec 11, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [9d882fc801](https://linux-hardware.org/?probe=9d882fc801) | Dec 11, 2023 |
| HP            | Laptop                      | Notebook    | [b5d2cf7074](https://linux-hardware.org/?probe=b5d2cf7074) | Dec 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [71de71e3f4](https://linux-hardware.org/?probe=71de71e3f4) | Dec 10, 2023 |
| Gigabyte      | P67A-UD3P-B3                | Desktop     | [e96b9306cb](https://linux-hardware.org/?probe=e96b9306cb) | Dec 10, 2023 |
| Lenovo        | ThinkPad T410 2522V3S       | Notebook    | [7a6c259421](https://linux-hardware.org/?probe=7a6c259421) | Dec 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [64b0038221](https://linux-hardware.org/?probe=64b0038221) | Dec 10, 2023 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [dd4ad4373b](https://linux-hardware.org/?probe=dd4ad4373b) | Dec 10, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [a29797fb65](https://linux-hardware.org/?probe=a29797fb65) | Dec 10, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [a960a2a5b7](https://linux-hardware.org/?probe=a960a2a5b7) | Dec 10, 2023 |
| Toshiba       | Satellite A660              | Notebook    | [441f997be2](https://linux-hardware.org/?probe=441f997be2) | Dec 10, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [25d8aaca3c](https://linux-hardware.org/?probe=25d8aaca3c) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [63b05d421b](https://linux-hardware.org/?probe=63b05d421b) | Dec 10, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [581807905e](https://linux-hardware.org/?probe=581807905e) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ecb7258d5](https://linux-hardware.org/?probe=1ecb7258d5) | Dec 10, 2023 |
| Dell          | Latitude 7440               | Notebook    | [2aef8e5157](https://linux-hardware.org/?probe=2aef8e5157) | Dec 09, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [87be870a89](https://linux-hardware.org/?probe=87be870a89) | Dec 09, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [459870519f](https://linux-hardware.org/?probe=459870519f) | Dec 09, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [514239398e](https://linux-hardware.org/?probe=514239398e) | Dec 09, 2023 |
| Gigabyte      | AORUS 15 9KF                | Notebook    | [d6386ee775](https://linux-hardware.org/?probe=d6386ee775) | Dec 09, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [f7f70db230](https://linux-hardware.org/?probe=f7f70db230) | Dec 08, 2023 |
| Dell          | Latitude 7490               | Notebook    | [13759c617a](https://linux-hardware.org/?probe=13759c617a) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [cc6cd166f2](https://linux-hardware.org/?probe=cc6cd166f2) | Dec 08, 2023 |
| Dell          | Latitude E5550              | Notebook    | [740c338fbe](https://linux-hardware.org/?probe=740c338fbe) | Dec 08, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9f006edcd8](https://linux-hardware.org/?probe=9f006edcd8) | Dec 08, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [da95a095fa](https://linux-hardware.org/?probe=da95a095fa) | Dec 08, 2023 |
| Dell          | Latitude E6430              | Notebook    | [dee39185ec](https://linux-hardware.org/?probe=dee39185ec) | Dec 08, 2023 |
| MSI           | G31TM-P35                   | Desktop     | [e241cfaeca](https://linux-hardware.org/?probe=e241cfaeca) | Dec 08, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [2ab879045f](https://linux-hardware.org/?probe=2ab879045f) | Dec 08, 2023 |
| Dell          | Latitude E5550              | Notebook    | [52866a9d1a](https://linux-hardware.org/?probe=52866a9d1a) | Dec 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS8C000    | Notebook    | [bff5eac6db](https://linux-hardware.org/?probe=bff5eac6db) | Dec 08, 2023 |
| Dell          | 0KP561                      | Desktop     | [bd0971e9cc](https://linux-hardware.org/?probe=bd0971e9cc) | Dec 08, 2023 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [b2fcb75892](https://linux-hardware.org/?probe=b2fcb75892) | Dec 07, 2023 |
| HP            | 1495                        | Desktop     | [361c8f4360](https://linux-hardware.org/?probe=361c8f4360) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [87aa35c45c](https://linux-hardware.org/?probe=87aa35c45c) | Dec 07, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [3c37d1bb9f](https://linux-hardware.org/?probe=3c37d1bb9f) | Dec 07, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [256fbd42a6](https://linux-hardware.org/?probe=256fbd42a6) | Dec 06, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [2a4412d268](https://linux-hardware.org/?probe=2a4412d268) | Dec 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [3fce748548](https://linux-hardware.org/?probe=3fce748548) | Dec 06, 2023 |
| Packard Be... | EasyNote TSX66HR            | Notebook    | [8ca6149044](https://linux-hardware.org/?probe=8ca6149044) | Dec 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9b6cdd96f4](https://linux-hardware.org/?probe=9b6cdd96f4) | Dec 06, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [7d11b1aed9](https://linux-hardware.org/?probe=7d11b1aed9) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [fae6162d7b](https://linux-hardware.org/?probe=fae6162d7b) | Dec 06, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e6657bb173](https://linux-hardware.org/?probe=e6657bb173) | Dec 06, 2023 |
| Valve         | Galileo                     | Notebook    | [4704035dff](https://linux-hardware.org/?probe=4704035dff) | Dec 06, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [519c5e78fc](https://linux-hardware.org/?probe=519c5e78fc) | Dec 06, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [3d8844bc98](https://linux-hardware.org/?probe=3d8844bc98) | Dec 05, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [5fa41b15bb](https://linux-hardware.org/?probe=5fa41b15bb) | Dec 05, 2023 |
| Lenovo        | ThinkPad E15 20RD003KMH     | Notebook    | [d54efc5833](https://linux-hardware.org/?probe=d54efc5833) | Dec 05, 2023 |
| ASUSTek       | K53U                        | Notebook    | [b76cef4836](https://linux-hardware.org/?probe=b76cef4836) | Dec 05, 2023 |
| MSI           | 2A9C                        | Desktop     | [2ae992c0d5](https://linux-hardware.org/?probe=2ae992c0d5) | Dec 05, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [15d4dc2fe9](https://linux-hardware.org/?probe=15d4dc2fe9) | Dec 05, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [65d5ddf61f](https://linux-hardware.org/?probe=65d5ddf61f) | Dec 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [6d790b9d8c](https://linux-hardware.org/?probe=6d790b9d8c) | Dec 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [667c6d4e98](https://linux-hardware.org/?probe=667c6d4e98) | Dec 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [63e8b02453](https://linux-hardware.org/?probe=63e8b02453) | Dec 05, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [bd98f1df4c](https://linux-hardware.org/?probe=bd98f1df4c) | Dec 04, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b4b71ada44](https://linux-hardware.org/?probe=b4b71ada44) | Dec 04, 2023 |
| Dell          | 0FG011                      | Desktop     | [4a5701f000](https://linux-hardware.org/?probe=4a5701f000) | Dec 04, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [87616f0d71](https://linux-hardware.org/?probe=87616f0d71) | Dec 04, 2023 |
| Acer          | Veriton S6620G v1.0         | Desktop     | [34095bbfed](https://linux-hardware.org/?probe=34095bbfed) | Dec 04, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [0f629c5ee8](https://linux-hardware.org/?probe=0f629c5ee8) | Dec 04, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [7b1c8f906b](https://linux-hardware.org/?probe=7b1c8f906b) | Dec 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1fe1dc7462](https://linux-hardware.org/?probe=1fe1dc7462) | Dec 04, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [4fd5ba2289](https://linux-hardware.org/?probe=4fd5ba2289) | Dec 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [961b00cfbe](https://linux-hardware.org/?probe=961b00cfbe) | Dec 04, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [7c16c8b9ac](https://linux-hardware.org/?probe=7c16c8b9ac) | Dec 03, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [49eeb946c5](https://linux-hardware.org/?probe=49eeb946c5) | Dec 03, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [50979ecbd2](https://linux-hardware.org/?probe=50979ecbd2) | Dec 03, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [848e0dbd37](https://linux-hardware.org/?probe=848e0dbd37) | Dec 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [bae67b7a50](https://linux-hardware.org/?probe=bae67b7a50) | Dec 03, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [f0df20f63f](https://linux-hardware.org/?probe=f0df20f63f) | Dec 03, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4c97431f16](https://linux-hardware.org/?probe=4c97431f16) | Dec 03, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9abcd3c636](https://linux-hardware.org/?probe=9abcd3c636) | Dec 03, 2023 |
| Medion        | E6214                       | Notebook    | [f5e38ac376](https://linux-hardware.org/?probe=f5e38ac376) | Dec 03, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [45cf863e9b](https://linux-hardware.org/?probe=45cf863e9b) | Dec 03, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [bc4c5638a3](https://linux-hardware.org/?probe=bc4c5638a3) | Dec 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a18c178195](https://linux-hardware.org/?probe=a18c178195) | Dec 02, 2023 |
| ASUSTek       | F3E                         | Notebook    | [26a960dd12](https://linux-hardware.org/?probe=26a960dd12) | Dec 02, 2023 |
| Dell          | Precision 5520              | Notebook    | [aa1a1feefc](https://linux-hardware.org/?probe=aa1a1feefc) | Dec 02, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [983698f613](https://linux-hardware.org/?probe=983698f613) | Dec 02, 2023 |
| MSI           | B85M-E43 DASH               | Desktop     | [b9caa2d56f](https://linux-hardware.org/?probe=b9caa2d56f) | Dec 02, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [561cad738d](https://linux-hardware.org/?probe=561cad738d) | Dec 02, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [186eb0ce63](https://linux-hardware.org/?probe=186eb0ce63) | Dec 02, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [6f6f496558](https://linux-hardware.org/?probe=6f6f496558) | Dec 01, 2023 |
| Lenovo        | G585                        | Notebook    | [a62a35b461](https://linux-hardware.org/?probe=a62a35b461) | Dec 01, 2023 |
| Dell          | Latitude 7440               | Notebook    | [b4179d70c3](https://linux-hardware.org/?probe=b4179d70c3) | Dec 01, 2023 |
| Google        | Fleex                       | Notebook    | [4baac33893](https://linux-hardware.org/?probe=4baac33893) | Dec 01, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [436f0406e4](https://linux-hardware.org/?probe=436f0406e4) | Dec 01, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [52a7a60343](https://linux-hardware.org/?probe=52a7a60343) | Dec 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [ab8935b499](https://linux-hardware.org/?probe=ab8935b499) | Dec 01, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [327582fb65](https://linux-hardware.org/?probe=327582fb65) | Dec 01, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [f3f624e1cf](https://linux-hardware.org/?probe=f3f624e1cf) | Nov 30, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [d536392d03](https://linux-hardware.org/?probe=d536392d03) | Nov 30, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [bfe263dfe0](https://linux-hardware.org/?probe=bfe263dfe0) | Nov 30, 2023 |
| MSI           | A78M-E45                    | Desktop     | [fd9a5e65e4](https://linux-hardware.org/?probe=fd9a5e65e4) | Nov 30, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [c7a78a1510](https://linux-hardware.org/?probe=c7a78a1510) | Nov 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [cc54ea37ef](https://linux-hardware.org/?probe=cc54ea37ef) | Nov 30, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [03de11e5b3](https://linux-hardware.org/?probe=03de11e5b3) | Nov 30, 2023 |
| Dell          | G15 5515                    | Notebook    | [25c732d6aa](https://linux-hardware.org/?probe=25c732d6aa) | Nov 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e39e2b268d](https://linux-hardware.org/?probe=e39e2b268d) | Nov 30, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [5dd27edbe4](https://linux-hardware.org/?probe=5dd27edbe4) | Nov 29, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6a3776da6b](https://linux-hardware.org/?probe=6a3776da6b) | Nov 29, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [d416d62cf1](https://linux-hardware.org/?probe=d416d62cf1) | Nov 29, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [d0eb22aa03](https://linux-hardware.org/?probe=d0eb22aa03) | Nov 29, 2023 |
| ASRock        | J3355M                      | Desktop     | [a767ff37ed](https://linux-hardware.org/?probe=a767ff37ed) | Nov 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2d1452d207](https://linux-hardware.org/?probe=2d1452d207) | Nov 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [655dc71f64](https://linux-hardware.org/?probe=655dc71f64) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK E5512              | Notebook    | [9df65d1a3d](https://linux-hardware.org/?probe=9df65d1a3d) | Nov 29, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [c6673a5a66](https://linux-hardware.org/?probe=c6673a5a66) | Nov 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [c5dd65037d](https://linux-hardware.org/?probe=c5dd65037d) | Nov 29, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [2a9b640b54](https://linux-hardware.org/?probe=2a9b640b54) | Nov 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [34f3153910](https://linux-hardware.org/?probe=34f3153910) | Nov 28, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [52a0c464fe](https://linux-hardware.org/?probe=52a0c464fe) | Nov 28, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [b8337b50d8](https://linux-hardware.org/?probe=b8337b50d8) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [2df2a6f5d8](https://linux-hardware.org/?probe=2df2a6f5d8) | Nov 28, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0a4f97781c](https://linux-hardware.org/?probe=0a4f97781c) | Nov 27, 2023 |
| Lenovo        | ThinkPad T520 4243PH3       | Notebook    | [63ba3b10d4](https://linux-hardware.org/?probe=63ba3b10d4) | Nov 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [1a855ee74d](https://linux-hardware.org/?probe=1a855ee74d) | Nov 27, 2023 |
| Clevo         | M720R                       | Notebook    | [cf202bc2be](https://linux-hardware.org/?probe=cf202bc2be) | Nov 27, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [d36366cac6](https://linux-hardware.org/?probe=d36366cac6) | Nov 27, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [0c272521ab](https://linux-hardware.org/?probe=0c272521ab) | Nov 27, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [e4cbe05d6d](https://linux-hardware.org/?probe=e4cbe05d6d) | Nov 27, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [142a3240d4](https://linux-hardware.org/?probe=142a3240d4) | Nov 27, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [1d71979dbb](https://linux-hardware.org/?probe=1d71979dbb) | Nov 27, 2023 |
| Dell          | G15 5515                    | Notebook    | [b33a8c3a2e](https://linux-hardware.org/?probe=b33a8c3a2e) | Nov 27, 2023 |
| Dell          | 0DR845                      | Desktop     | [e09cfb8e7a](https://linux-hardware.org/?probe=e09cfb8e7a) | Nov 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2a04ec7adc](https://linux-hardware.org/?probe=2a04ec7adc) | Nov 27, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [da3ac19523](https://linux-hardware.org/?probe=da3ac19523) | Nov 26, 2023 |
| Dell          | Latitude D630               | Notebook    | [51af6a8f00](https://linux-hardware.org/?probe=51af6a8f00) | Nov 26, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [8a894da286](https://linux-hardware.org/?probe=8a894da286) | Nov 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [95bd4c2832](https://linux-hardware.org/?probe=95bd4c2832) | Nov 26, 2023 |
| Fujitsu       | LIFEBOOK E4511              | Notebook    | [a849237ab7](https://linux-hardware.org/?probe=a849237ab7) | Nov 26, 2023 |
| Chuwi         | GemiBook Plus               | Notebook    | [6316398e5b](https://linux-hardware.org/?probe=6316398e5b) | Nov 26, 2023 |
| HP            | ProBook 5330m               | Notebook    | [74e3bacd14](https://linux-hardware.org/?probe=74e3bacd14) | Nov 25, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [17cd5f34c3](https://linux-hardware.org/?probe=17cd5f34c3) | Nov 25, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [462b5c65a7](https://linux-hardware.org/?probe=462b5c65a7) | Nov 25, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [a642075264](https://linux-hardware.org/?probe=a642075264) | Nov 25, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [a0480513dd](https://linux-hardware.org/?probe=a0480513dd) | Nov 25, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [e01ac99a92](https://linux-hardware.org/?probe=e01ac99a92) | Nov 25, 2023 |
| ASRock        | H110M-HDS                   | Desktop     | [8e326dd485](https://linux-hardware.org/?probe=8e326dd485) | Nov 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [eb4379efae](https://linux-hardware.org/?probe=eb4379efae) | Nov 24, 2023 |
| Dell          | Inspiron N5040              | Notebook    | [3b51468cdf](https://linux-hardware.org/?probe=3b51468cdf) | Nov 24, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2b2ac91a50](https://linux-hardware.org/?probe=2b2ac91a50) | Nov 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [fb9766adc5](https://linux-hardware.org/?probe=fb9766adc5) | Nov 24, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [50a53cf2b0](https://linux-hardware.org/?probe=50a53cf2b0) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [2852a62f61](https://linux-hardware.org/?probe=2852a62f61) | Nov 24, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [4b725b7022](https://linux-hardware.org/?probe=4b725b7022) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2c505c0b1e](https://linux-hardware.org/?probe=2c505c0b1e) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [48112cbfe0](https://linux-hardware.org/?probe=48112cbfe0) | Nov 24, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [387b322a8e](https://linux-hardware.org/?probe=387b322a8e) | Nov 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5417165a43](https://linux-hardware.org/?probe=5417165a43) | Nov 24, 2023 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [080042a410](https://linux-hardware.org/?probe=080042a410) | Nov 23, 2023 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [f82ecf4011](https://linux-hardware.org/?probe=f82ecf4011) | Nov 23, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ee82d7417c](https://linux-hardware.org/?probe=ee82d7417c) | Nov 23, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [ac0bed612a](https://linux-hardware.org/?probe=ac0bed612a) | Nov 22, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [e0781004e0](https://linux-hardware.org/?probe=e0781004e0) | Nov 22, 2023 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [1370f43083](https://linux-hardware.org/?probe=1370f43083) | Nov 22, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4eae08c59f](https://linux-hardware.org/?probe=4eae08c59f) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [195e3a2ce6](https://linux-hardware.org/?probe=195e3a2ce6) | Nov 22, 2023 |
| HP            | 8158 A01                    | Mini pc     | [5132b64a8a](https://linux-hardware.org/?probe=5132b64a8a) | Nov 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [b73a5b800d](https://linux-hardware.org/?probe=b73a5b800d) | Nov 22, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [56319a6e9d](https://linux-hardware.org/?probe=56319a6e9d) | Nov 21, 2023 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [5a2df7d067](https://linux-hardware.org/?probe=5a2df7d067) | Nov 21, 2023 |
| Dell          | Latitude 3190               | Notebook    | [3c5b8541c7](https://linux-hardware.org/?probe=3c5b8541c7) | Nov 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [442654cab6](https://linux-hardware.org/?probe=442654cab6) | Nov 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [aeb55b832b](https://linux-hardware.org/?probe=aeb55b832b) | Nov 21, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [f9da55efe2](https://linux-hardware.org/?probe=f9da55efe2) | Nov 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [56c19073cb](https://linux-hardware.org/?probe=56c19073cb) | Nov 20, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [b2b85808ca](https://linux-hardware.org/?probe=b2b85808ca) | Nov 20, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b11ea54568](https://linux-hardware.org/?probe=b11ea54568) | Nov 20, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [4ceda102e6](https://linux-hardware.org/?probe=4ceda102e6) | Nov 20, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9d71a8e453](https://linux-hardware.org/?probe=9d71a8e453) | Nov 20, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [8d33a8020d](https://linux-hardware.org/?probe=8d33a8020d) | Nov 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ac6d14ae8d](https://linux-hardware.org/?probe=ac6d14ae8d) | Nov 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [a090e73dbf](https://linux-hardware.org/?probe=a090e73dbf) | Nov 20, 2023 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7a812fcce7](https://linux-hardware.org/?probe=7a812fcce7) | Nov 20, 2023 |
| HP            | 8054                        | Desktop     | [2ccc2c67f2](https://linux-hardware.org/?probe=2ccc2c67f2) | Nov 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [08b0fccf59](https://linux-hardware.org/?probe=08b0fccf59) | Nov 20, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e89473830f](https://linux-hardware.org/?probe=e89473830f) | Nov 19, 2023 |
| Dell          | Latitude E6330              | Notebook    | [3c6e547f2a](https://linux-hardware.org/?probe=3c6e547f2a) | Nov 19, 2023 |
| Lenovo        | ThinkPad X60 1707Y91        | Notebook    | [ac0e28ee75](https://linux-hardware.org/?probe=ac0e28ee75) | Nov 19, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e8ca29066e](https://linux-hardware.org/?probe=e8ca29066e) | Nov 19, 2023 |
| Dell          | Latitude E6330              | Notebook    | [078f4227bd](https://linux-hardware.org/?probe=078f4227bd) | Nov 19, 2023 |
| eMachines     | ET1850                      | Desktop     | [0bcca3431b](https://linux-hardware.org/?probe=0bcca3431b) | Nov 18, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [7d8d716f9d](https://linux-hardware.org/?probe=7d8d716f9d) | Nov 18, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [87222a31f3](https://linux-hardware.org/?probe=87222a31f3) | Nov 18, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [088efe59ae](https://linux-hardware.org/?probe=088efe59ae) | Nov 18, 2023 |
| Dell          | Latitude D630               | Notebook    | [54e404f085](https://linux-hardware.org/?probe=54e404f085) | Nov 18, 2023 |
| Dell          | Latitude E6400              | Notebook    | [737ee5a8d3](https://linux-hardware.org/?probe=737ee5a8d3) | Nov 18, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b3da1a92d0](https://linux-hardware.org/?probe=b3da1a92d0) | Nov 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [5383dca9b2](https://linux-hardware.org/?probe=5383dca9b2) | Nov 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [66c6f85ec1](https://linux-hardware.org/?probe=66c6f85ec1) | Nov 17, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [fa0b8c4a6a](https://linux-hardware.org/?probe=fa0b8c4a6a) | Nov 17, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [da6ffb4c35](https://linux-hardware.org/?probe=da6ffb4c35) | Nov 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [6518d0d83e](https://linux-hardware.org/?probe=6518d0d83e) | Nov 17, 2023 |
| Dell          | Inspiron 7566               | Notebook    | [5709fca952](https://linux-hardware.org/?probe=5709fca952) | Nov 17, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [648f624587](https://linux-hardware.org/?probe=648f624587) | Nov 16, 2023 |
| Intel         | NUC7i5DNB J57626-507        | Mini pc     | [110973f4a4](https://linux-hardware.org/?probe=110973f4a4) | Nov 16, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [5c4603de9d](https://linux-hardware.org/?probe=5c4603de9d) | Nov 16, 2023 |
| MSI           | H61M-P20                    | Desktop     | [237c033c24](https://linux-hardware.org/?probe=237c033c24) | Nov 15, 2023 |
| Medion        | DN2820FYB-IS BTNUCW08.11... | Desktop     | [def1bf43ff](https://linux-hardware.org/?probe=def1bf43ff) | Nov 15, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d2cafb1814](https://linux-hardware.org/?probe=d2cafb1814) | Nov 15, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6ea69f0699](https://linux-hardware.org/?probe=6ea69f0699) | Nov 15, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [f27cfbe5ca](https://linux-hardware.org/?probe=f27cfbe5ca) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [df8a98ef2c](https://linux-hardware.org/?probe=df8a98ef2c) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [513485cc8f](https://linux-hardware.org/?probe=513485cc8f) | Nov 14, 2023 |
| MSI           | Z97-G43                     | Desktop     | [ea16582cb2](https://linux-hardware.org/?probe=ea16582cb2) | Nov 14, 2023 |
| MSI           | Modern 14 B11MO             | Notebook    | [2095892205](https://linux-hardware.org/?probe=2095892205) | Nov 14, 2023 |
| Dell          | 0PGKWF A02                  | Desktop     | [3025cd2250](https://linux-hardware.org/?probe=3025cd2250) | Nov 14, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [200a783f1a](https://linux-hardware.org/?probe=200a783f1a) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [3c336ad6e1](https://linux-hardware.org/?probe=3c336ad6e1) | Nov 14, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [2ed7720fa6](https://linux-hardware.org/?probe=2ed7720fa6) | Nov 13, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [b7d9898316](https://linux-hardware.org/?probe=b7d9898316) | Nov 13, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [113193bb57](https://linux-hardware.org/?probe=113193bb57) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6f0d8ee5da](https://linux-hardware.org/?probe=6f0d8ee5da) | Nov 13, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [73a53ca5a4](https://linux-hardware.org/?probe=73a53ca5a4) | Nov 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8080101e6f](https://linux-hardware.org/?probe=8080101e6f) | Nov 13, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [72639a4231](https://linux-hardware.org/?probe=72639a4231) | Nov 13, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8b8d073259](https://linux-hardware.org/?probe=8b8d073259) | Nov 13, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [de369665dc](https://linux-hardware.org/?probe=de369665dc) | Nov 13, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [0d2accfed1](https://linux-hardware.org/?probe=0d2accfed1) | Nov 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [9d2aeb3f90](https://linux-hardware.org/?probe=9d2aeb3f90) | Nov 13, 2023 |
| Timi          | A35S                        | Notebook    | [f225083df7](https://linux-hardware.org/?probe=f225083df7) | Nov 12, 2023 |
| Dell          | Latitude E7440              | Notebook    | [407afcc9d2](https://linux-hardware.org/?probe=407afcc9d2) | Nov 12, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [a49a531710](https://linux-hardware.org/?probe=a49a531710) | Nov 12, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [edf208cfd3](https://linux-hardware.org/?probe=edf208cfd3) | Nov 12, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [572825e302](https://linux-hardware.org/?probe=572825e302) | Nov 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [bedc6fd7f0](https://linux-hardware.org/?probe=bedc6fd7f0) | Nov 11, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [a749127ad5](https://linux-hardware.org/?probe=a749127ad5) | Nov 11, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [ed70ccc9b1](https://linux-hardware.org/?probe=ed70ccc9b1) | Nov 11, 2023 |
| HP            | 1850                        | Desktop     | [117ab7ea0d](https://linux-hardware.org/?probe=117ab7ea0d) | Nov 11, 2023 |
| MSI           | MS-B0A21                    | Desktop     | [c9d19c0810](https://linux-hardware.org/?probe=c9d19c0810) | Nov 11, 2023 |
| MSI           | P55-GD65                    | Desktop     | [5a95aca3cc](https://linux-hardware.org/?probe=5a95aca3cc) | Nov 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5fcb6b8815](https://linux-hardware.org/?probe=5fcb6b8815) | Nov 11, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [951f01b614](https://linux-hardware.org/?probe=951f01b614) | Nov 11, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [99fa1e8cbd](https://linux-hardware.org/?probe=99fa1e8cbd) | Nov 11, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [c9f63fc134](https://linux-hardware.org/?probe=c9f63fc134) | Nov 11, 2023 |
| HP            | 8158 A01                    | Mini pc     | [3dcdff02d7](https://linux-hardware.org/?probe=3dcdff02d7) | Nov 10, 2023 |
| HP            | 8158 A01                    | Mini pc     | [8a512faa94](https://linux-hardware.org/?probe=8a512faa94) | Nov 10, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [4e81c16b62](https://linux-hardware.org/?probe=4e81c16b62) | Nov 10, 2023 |
| HP            | 1850                        | Desktop     | [10595f0ac3](https://linux-hardware.org/?probe=10595f0ac3) | Nov 10, 2023 |
| Dell          | Latitude D630               | Notebook    | [8af88f25f0](https://linux-hardware.org/?probe=8af88f25f0) | Nov 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [b299fd1fe9](https://linux-hardware.org/?probe=b299fd1fe9) | Nov 09, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [6f20a56938](https://linux-hardware.org/?probe=6f20a56938) | Nov 09, 2023 |
| Medion        | Akoya E1318T                | Notebook    | [4e3e62ee88](https://linux-hardware.org/?probe=4e3e62ee88) | Nov 09, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [665ed1538e](https://linux-hardware.org/?probe=665ed1538e) | Nov 09, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [2e06b9e7ff](https://linux-hardware.org/?probe=2e06b9e7ff) | Nov 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [58c681b475](https://linux-hardware.org/?probe=58c681b475) | Nov 09, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [bb13a5b1c7](https://linux-hardware.org/?probe=bb13a5b1c7) | Nov 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [80431017dc](https://linux-hardware.org/?probe=80431017dc) | Nov 09, 2023 |
| Intel         | NUC7i5DNB J57626-507        | Mini pc     | [42845cfd6f](https://linux-hardware.org/?probe=42845cfd6f) | Nov 09, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [656bd0c4c2](https://linux-hardware.org/?probe=656bd0c4c2) | Nov 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [9ae1f9c05f](https://linux-hardware.org/?probe=9ae1f9c05f) | Nov 08, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [02154de863](https://linux-hardware.org/?probe=02154de863) | Nov 08, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [16cf6c0ede](https://linux-hardware.org/?probe=16cf6c0ede) | Nov 08, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c4f7fd2835](https://linux-hardware.org/?probe=c4f7fd2835) | Nov 08, 2023 |
| HP            | 339A                        | Desktop     | [cdcbe8d47d](https://linux-hardware.org/?probe=cdcbe8d47d) | Nov 07, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [665120f441](https://linux-hardware.org/?probe=665120f441) | Nov 07, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [1f3f493cb1](https://linux-hardware.org/?probe=1f3f493cb1) | Nov 07, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [6ac34aa88a](https://linux-hardware.org/?probe=6ac34aa88a) | Nov 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [436bd1729a](https://linux-hardware.org/?probe=436bd1729a) | Nov 06, 2023 |
| MSI           | B85M-E45                    | Desktop     | [a2b6c4ab44](https://linux-hardware.org/?probe=a2b6c4ab44) | Nov 06, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [5b992d974a](https://linux-hardware.org/?probe=5b992d974a) | Nov 06, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [4d3a7373ae](https://linux-hardware.org/?probe=4d3a7373ae) | Nov 06, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [1da691596b](https://linux-hardware.org/?probe=1da691596b) | Nov 06, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d385d4714c](https://linux-hardware.org/?probe=d385d4714c) | Nov 06, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [89a24ae9fa](https://linux-hardware.org/?probe=89a24ae9fa) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ff44a3299b](https://linux-hardware.org/?probe=ff44a3299b) | Nov 06, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [d40cc6e0a4](https://linux-hardware.org/?probe=d40cc6e0a4) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [39e8a692ae](https://linux-hardware.org/?probe=39e8a692ae) | Nov 05, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [b3669f73a8](https://linux-hardware.org/?probe=b3669f73a8) | Nov 05, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [f0399efc08](https://linux-hardware.org/?probe=f0399efc08) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [fd9594de89](https://linux-hardware.org/?probe=fd9594de89) | Nov 05, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b5b47ea33a](https://linux-hardware.org/?probe=b5b47ea33a) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [a5a8cf5c09](https://linux-hardware.org/?probe=a5a8cf5c09) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [74099b3a6e](https://linux-hardware.org/?probe=74099b3a6e) | Nov 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [2cbd472a6e](https://linux-hardware.org/?probe=2cbd472a6e) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [bdad71bf99](https://linux-hardware.org/?probe=bdad71bf99) | Nov 05, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [1488a8a70f](https://linux-hardware.org/?probe=1488a8a70f) | Nov 05, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bdd24f60d2](https://linux-hardware.org/?probe=bdd24f60d2) | Nov 05, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [534fcded19](https://linux-hardware.org/?probe=534fcded19) | Nov 05, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [29fc753f1e](https://linux-hardware.org/?probe=29fc753f1e) | Nov 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS3YT01    | Notebook    | [89b8df73c1](https://linux-hardware.org/?probe=89b8df73c1) | Nov 04, 2023 |
| HP            | 21D0                        | Desktop     | [160964fbab](https://linux-hardware.org/?probe=160964fbab) | Nov 04, 2023 |
| HP            | 89B5 A                      | Desktop     | [e31ecc3904](https://linux-hardware.org/?probe=e31ecc3904) | Nov 04, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [04d425d450](https://linux-hardware.org/?probe=04d425d450) | Nov 04, 2023 |
| Lenovo        | 80SY                        | Notebook    | [7c7a6ba82f](https://linux-hardware.org/?probe=7c7a6ba82f) | Nov 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [9999b9fa3d](https://linux-hardware.org/?probe=9999b9fa3d) | Nov 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [a6ce21c9de](https://linux-hardware.org/?probe=a6ce21c9de) | Nov 04, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d4845b6b9](https://linux-hardware.org/?probe=2d4845b6b9) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [db71fb65bf](https://linux-hardware.org/?probe=db71fb65bf) | Nov 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [43ccf36bf0](https://linux-hardware.org/?probe=43ccf36bf0) | Nov 03, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [4ccd2ef567](https://linux-hardware.org/?probe=4ccd2ef567) | Nov 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0e493c7b85](https://linux-hardware.org/?probe=0e493c7b85) | Nov 03, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [3a0023b4ba](https://linux-hardware.org/?probe=3a0023b4ba) | Nov 03, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [3ddccb994b](https://linux-hardware.org/?probe=3ddccb994b) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [d48f7514df](https://linux-hardware.org/?probe=d48f7514df) | Nov 02, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [027a0a96da](https://linux-hardware.org/?probe=027a0a96da) | Nov 02, 2023 |
| Dell          | Latitude E6420              | Notebook    | [cdef3b5f1c](https://linux-hardware.org/?probe=cdef3b5f1c) | Nov 02, 2023 |
| Dell          | 0CNCJW A08                  | Server      | [c166457131](https://linux-hardware.org/?probe=c166457131) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [0c8b2cd660](https://linux-hardware.org/?probe=0c8b2cd660) | Nov 01, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [45d3b00840](https://linux-hardware.org/?probe=45d3b00840) | Nov 01, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [a9ed160c1c](https://linux-hardware.org/?probe=a9ed160c1c) | Nov 01, 2023 |
| ASUSTek       | Z97-AR                      | Desktop     | [39741158bc](https://linux-hardware.org/?probe=39741158bc) | Nov 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [7dd972fb0d](https://linux-hardware.org/?probe=7dd972fb0d) | Nov 01, 2023 |
| HP            | Pavilion g7                 | Notebook    | [157c592b3a](https://linux-hardware.org/?probe=157c592b3a) | Nov 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [6d00cda16c](https://linux-hardware.org/?probe=6d00cda16c) | Nov 01, 2023 |
| ZOTAC         | ZBOX-MI623/MI643 Rev.00     | Mini pc     | [4b769dbcca](https://linux-hardware.org/?probe=4b769dbcca) | Oct 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [dc68dc55c9](https://linux-hardware.org/?probe=dc68dc55c9) | Oct 31, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [1323e3ad04](https://linux-hardware.org/?probe=1323e3ad04) | Oct 31, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [00ffbda72d](https://linux-hardware.org/?probe=00ffbda72d) | Oct 31, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ff0dfe1642](https://linux-hardware.org/?probe=ff0dfe1642) | Oct 30, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [fca3ef2e73](https://linux-hardware.org/?probe=fca3ef2e73) | Oct 30, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [12e8c83970](https://linux-hardware.org/?probe=12e8c83970) | Oct 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fe7dbb2385](https://linux-hardware.org/?probe=fe7dbb2385) | Oct 29, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [eeddd1e3e1](https://linux-hardware.org/?probe=eeddd1e3e1) | Oct 29, 2023 |
| Dell          | Precision M6600             | Notebook    | [30e8d1522d](https://linux-hardware.org/?probe=30e8d1522d) | Oct 29, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [09d76f025a](https://linux-hardware.org/?probe=09d76f025a) | Oct 29, 2023 |
| OrangePi      | Zero3                       | Soc         | [6d3ecf003f](https://linux-hardware.org/?probe=6d3ecf003f) | Oct 29, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [101c8c676c](https://linux-hardware.org/?probe=101c8c676c) | Oct 29, 2023 |
| Shenzhen M... | TH80                        | Desktop     | [22dea9593a](https://linux-hardware.org/?probe=22dea9593a) | Oct 28, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [f78fcbc612](https://linux-hardware.org/?probe=f78fcbc612) | Oct 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bbba3e21c7](https://linux-hardware.org/?probe=bbba3e21c7) | Oct 27, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [3cc39678ff](https://linux-hardware.org/?probe=3cc39678ff) | Oct 27, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [e76ead66bc](https://linux-hardware.org/?probe=e76ead66bc) | Oct 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [15488b723a](https://linux-hardware.org/?probe=15488b723a) | Oct 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [54aa16ef1e](https://linux-hardware.org/?probe=54aa16ef1e) | Oct 27, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [0a0a08dd5f](https://linux-hardware.org/?probe=0a0a08dd5f) | Oct 26, 2023 |
| MSI           | MS-1688                     | Notebook    | [c3689c0452](https://linux-hardware.org/?probe=c3689c0452) | Oct 26, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [7f10f1b379](https://linux-hardware.org/?probe=7f10f1b379) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [700ceddf43](https://linux-hardware.org/?probe=700ceddf43) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f43adee740](https://linux-hardware.org/?probe=f43adee740) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [e3c1de1472](https://linux-hardware.org/?probe=e3c1de1472) | Oct 26, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [f1bcad7519](https://linux-hardware.org/?probe=f1bcad7519) | Oct 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [38a8824fe8](https://linux-hardware.org/?probe=38a8824fe8) | Oct 25, 2023 |
| HP            | Compaq 610                  | Notebook    | [f449560c8a](https://linux-hardware.org/?probe=f449560c8a) | Oct 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [dab53e45c9](https://linux-hardware.org/?probe=dab53e45c9) | Oct 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [6c88fcef70](https://linux-hardware.org/?probe=6c88fcef70) | Oct 25, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [b01d80e583](https://linux-hardware.org/?probe=b01d80e583) | Oct 24, 2023 |
| Gigabyte      | 965P-DS3                    | Desktop     | [b33d6b8a3c](https://linux-hardware.org/?probe=b33d6b8a3c) | Oct 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3eee01cd16](https://linux-hardware.org/?probe=3eee01cd16) | Oct 24, 2023 |
| Notebook      | P7xxDM(-G)                  | Notebook    | [bb211b2fb4](https://linux-hardware.org/?probe=bb211b2fb4) | Oct 24, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | Desktop     | [67564f88a0](https://linux-hardware.org/?probe=67564f88a0) | Oct 24, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [06247cab2e](https://linux-hardware.org/?probe=06247cab2e) | Oct 24, 2023 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [7be979fc66](https://linux-hardware.org/?probe=7be979fc66) | Oct 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [6f72e3839d](https://linux-hardware.org/?probe=6f72e3839d) | Oct 23, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [def0406ec0](https://linux-hardware.org/?probe=def0406ec0) | Oct 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8da5e9e836](https://linux-hardware.org/?probe=8da5e9e836) | Oct 23, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [047f359430](https://linux-hardware.org/?probe=047f359430) | Oct 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6ef12aa776](https://linux-hardware.org/?probe=6ef12aa776) | Oct 23, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | Notebook    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [9538ff99bf](https://linux-hardware.org/?probe=9538ff99bf) | Oct 22, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9fcaeda183](https://linux-hardware.org/?probe=9fcaeda183) | Oct 22, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [66d1164d86](https://linux-hardware.org/?probe=66d1164d86) | Oct 21, 2023 |
| Dell          | Precision 5520              | Notebook    | [79b5c73851](https://linux-hardware.org/?probe=79b5c73851) | Oct 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dca6ad28b3](https://linux-hardware.org/?probe=dca6ad28b3) | Oct 21, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [d6bd0eda6d](https://linux-hardware.org/?probe=d6bd0eda6d) | Oct 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [83811b2a84](https://linux-hardware.org/?probe=83811b2a84) | Oct 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [1ff62f5fd7](https://linux-hardware.org/?probe=1ff62f5fd7) | Oct 21, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e8d5f9186c](https://linux-hardware.org/?probe=e8d5f9186c) | Oct 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [2ca3451a04](https://linux-hardware.org/?probe=2ca3451a04) | Oct 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [7deca235e3](https://linux-hardware.org/?probe=7deca235e3) | Oct 20, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [65f3d76afa](https://linux-hardware.org/?probe=65f3d76afa) | Oct 19, 2023 |
| Dell          | Latitude 5440               | Notebook    | [e3760f51a8](https://linux-hardware.org/?probe=e3760f51a8) | Oct 19, 2023 |
| ASRock        | A88M-G                      | Desktop     | [05d17c88b7](https://linux-hardware.org/?probe=05d17c88b7) | Oct 18, 2023 |
| Dell          | Latitude 5440               | Notebook    | [257850f5d8](https://linux-hardware.org/?probe=257850f5d8) | Oct 18, 2023 |
| Dell          | Latitude 5440               | Notebook    | [2097e4ed5e](https://linux-hardware.org/?probe=2097e4ed5e) | Oct 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [e1751f1726](https://linux-hardware.org/?probe=e1751f1726) | Oct 17, 2023 |
| Dell          | Latitude E6420              | Notebook    | [f703c6bd74](https://linux-hardware.org/?probe=f703c6bd74) | Oct 17, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [a4661384e1](https://linux-hardware.org/?probe=a4661384e1) | Oct 17, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [9eb823dcdd](https://linux-hardware.org/?probe=9eb823dcdd) | Oct 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7b5cf8abfc](https://linux-hardware.org/?probe=7b5cf8abfc) | Oct 17, 2023 |
| Dell          | Latitude 3190               | Notebook    | [6524dff50f](https://linux-hardware.org/?probe=6524dff50f) | Oct 17, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [cc5a77d2c3](https://linux-hardware.org/?probe=cc5a77d2c3) | Oct 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [e8dd286f6d](https://linux-hardware.org/?probe=e8dd286f6d) | Oct 16, 2023 |
| HP            | ProBook 6560b               | Notebook    | [3567f55849](https://linux-hardware.org/?probe=3567f55849) | Oct 15, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [04afaee575](https://linux-hardware.org/?probe=04afaee575) | Oct 15, 2023 |
| HP            | 1589                        | Desktop     | [88e5bbcc5a](https://linux-hardware.org/?probe=88e5bbcc5a) | Oct 15, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7d2501217c](https://linux-hardware.org/?probe=7d2501217c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [dfee331121](https://linux-hardware.org/?probe=dfee331121) | Oct 15, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [b09d2e33fd](https://linux-hardware.org/?probe=b09d2e33fd) | Oct 15, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [af4857609e](https://linux-hardware.org/?probe=af4857609e) | Oct 15, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [38155dfb23](https://linux-hardware.org/?probe=38155dfb23) | Oct 15, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [475107b82f](https://linux-hardware.org/?probe=475107b82f) | Oct 15, 2023 |
| ACTION        | M5A78L-M lX V2              | Desktop     | [fe141a8a31](https://linux-hardware.org/?probe=fe141a8a31) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [fd52faa27e](https://linux-hardware.org/?probe=fd52faa27e) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [39d3b3133e](https://linux-hardware.org/?probe=39d3b3133e) | Oct 14, 2023 |
| HP            | ProBook 6560b               | Notebook    | [49ffe8b6c5](https://linux-hardware.org/?probe=49ffe8b6c5) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d68359ee50](https://linux-hardware.org/?probe=d68359ee50) | Oct 14, 2023 |
| HP            | EliteBook 830 13 inch G1... | Notebook    | [e9ced529e2](https://linux-hardware.org/?probe=e9ced529e2) | Oct 14, 2023 |
| Lenovo        | ThinkPad T430u 3352A83      | Notebook    | [c5a829d842](https://linux-hardware.org/?probe=c5a829d842) | Oct 14, 2023 |
| Lenovo        | ThinkPad T400 64757D7       | Notebook    | [b374e214af](https://linux-hardware.org/?probe=b374e214af) | Oct 13, 2023 |
| HPE           | ProLiant MicroServer Gen... | Server      | [62f56cc610](https://linux-hardware.org/?probe=62f56cc610) | Oct 13, 2023 |
| MSI           | GE72 6QF                    | Notebook    | [94f1c85d10](https://linux-hardware.org/?probe=94f1c85d10) | Oct 13, 2023 |
| HP            | Grunt                       | Notebook    | [af80cd9bd6](https://linux-hardware.org/?probe=af80cd9bd6) | Oct 13, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [0400bae582](https://linux-hardware.org/?probe=0400bae582) | Oct 12, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [32ffcc827b](https://linux-hardware.org/?probe=32ffcc827b) | Oct 12, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [c3992a85f0](https://linux-hardware.org/?probe=c3992a85f0) | Oct 12, 2023 |
| ASUSTek       | X510UQ                      | Notebook    | [0494369566](https://linux-hardware.org/?probe=0494369566) | Oct 12, 2023 |
| Lenovo        | IdeaPad P500 20210          | Notebook    | [ba316cb723](https://linux-hardware.org/?probe=ba316cb723) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [c83831e304](https://linux-hardware.org/?probe=c83831e304) | Oct 11, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [bffc7bdfe6](https://linux-hardware.org/?probe=bffc7bdfe6) | Oct 11, 2023 |
| Dell          | Latitude 5511               | Notebook    | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [04fbcfc11b](https://linux-hardware.org/?probe=04fbcfc11b) | Oct 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [078d4619a6](https://linux-hardware.org/?probe=078d4619a6) | Oct 09, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [df4f5f4e21](https://linux-hardware.org/?probe=df4f5f4e21) | Oct 09, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [d4efaf21cb](https://linux-hardware.org/?probe=d4efaf21cb) | Oct 08, 2023 |
| Google        | Sasuke                      | Notebook    | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [8a9290f8a1](https://linux-hardware.org/?probe=8a9290f8a1) | Oct 08, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [889b36122b](https://linux-hardware.org/?probe=889b36122b) | Oct 08, 2023 |
| Google        | Lindar                      | Notebook    | [75852e1ad7](https://linux-hardware.org/?probe=75852e1ad7) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3cfe6c7d0c](https://linux-hardware.org/?probe=3cfe6c7d0c) | Oct 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [a95183052c](https://linux-hardware.org/?probe=a95183052c) | Oct 08, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [3854022982](https://linux-hardware.org/?probe=3854022982) | Oct 08, 2023 |
| HP            | 83E8                        | Desktop     | [c1028de72b](https://linux-hardware.org/?probe=c1028de72b) | Oct 07, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [9d6684c4a9](https://linux-hardware.org/?probe=9d6684c4a9) | Oct 07, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [372a2d0189](https://linux-hardware.org/?probe=372a2d0189) | Oct 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [0bf2deeb16](https://linux-hardware.org/?probe=0bf2deeb16) | Oct 07, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [61fef3256c](https://linux-hardware.org/?probe=61fef3256c) | Oct 07, 2023 |
| MSI           | MS-7235                     | Desktop     | [afb00bf553](https://linux-hardware.org/?probe=afb00bf553) | Oct 07, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [665a7ff2eb](https://linux-hardware.org/?probe=665a7ff2eb) | Oct 06, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [3ce37336af](https://linux-hardware.org/?probe=3ce37336af) | Oct 06, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [355bc3fdfc](https://linux-hardware.org/?probe=355bc3fdfc) | Oct 06, 2023 |
| Dell          | Latitude 5310 2-in-1        | Convertible | [a88c9fdbb6](https://linux-hardware.org/?probe=a88c9fdbb6) | Oct 06, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [c07c01c9e6](https://linux-hardware.org/?probe=c07c01c9e6) | Oct 06, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [fbd07d95c2](https://linux-hardware.org/?probe=fbd07d95c2) | Oct 06, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [21ec0f4129](https://linux-hardware.org/?probe=21ec0f4129) | Oct 06, 2023 |
| Intel         | X99                         | Desktop     | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6c5a7d30f3](https://linux-hardware.org/?probe=6c5a7d30f3) | Oct 06, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f496e4dfff](https://linux-hardware.org/?probe=f496e4dfff) | Oct 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3b01422b2a](https://linux-hardware.org/?probe=3b01422b2a) | Oct 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6e8b2e49f0](https://linux-hardware.org/?probe=6e8b2e49f0) | Oct 05, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [7ad16296eb](https://linux-hardware.org/?probe=7ad16296eb) | Oct 05, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [5529ffcf1b](https://linux-hardware.org/?probe=5529ffcf1b) | Oct 05, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [94ac6e4439](https://linux-hardware.org/?probe=94ac6e4439) | Oct 04, 2023 |
| ASRock        | P4i945GC                    | Desktop     | [9e7c1b2d58](https://linux-hardware.org/?probe=9e7c1b2d58) | Oct 04, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [18675da607](https://linux-hardware.org/?probe=18675da607) | Oct 04, 2023 |
| HP            | 1589                        | Desktop     | [75f8ba109d](https://linux-hardware.org/?probe=75f8ba109d) | Oct 04, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [8a684c7512](https://linux-hardware.org/?probe=8a684c7512) | Oct 04, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [e7b2bada83](https://linux-hardware.org/?probe=e7b2bada83) | Oct 04, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [57b66fc6eb](https://linux-hardware.org/?probe=57b66fc6eb) | Oct 04, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [e31f443ff9](https://linux-hardware.org/?probe=e31f443ff9) | Oct 04, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4161bb4b7f](https://linux-hardware.org/?probe=4161bb4b7f) | Oct 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [27d781a357](https://linux-hardware.org/?probe=27d781a357) | Oct 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c40f80d33a](https://linux-hardware.org/?probe=c40f80d33a) | Oct 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [21aac15234](https://linux-hardware.org/?probe=21aac15234) | Oct 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [001368f3a9](https://linux-hardware.org/?probe=001368f3a9) | Oct 03, 2023 |
| Dell          | 0NGT4D A01                  | Mini pc     | [457dfea13d](https://linux-hardware.org/?probe=457dfea13d) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [880b4780ee](https://linux-hardware.org/?probe=880b4780ee) | Oct 03, 2023 |
| Lenovo        | ThinkPad X390 20Q1S5K400    | Notebook    | [4d9d1bf62a](https://linux-hardware.org/?probe=4d9d1bf62a) | Oct 02, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [09b97f9681](https://linux-hardware.org/?probe=09b97f9681) | Oct 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [ea10bf8eab](https://linux-hardware.org/?probe=ea10bf8eab) | Oct 02, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [43062f3c9a](https://linux-hardware.org/?probe=43062f3c9a) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b8068a8e68](https://linux-hardware.org/?probe=b8068a8e68) | Oct 02, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [c095e62997](https://linux-hardware.org/?probe=c095e62997) | Oct 02, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [b7463e19f8](https://linux-hardware.org/?probe=b7463e19f8) | Oct 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cbd8df2f8a](https://linux-hardware.org/?probe=cbd8df2f8a) | Oct 02, 2023 |
| Intel         | NUC10i5FNB K61361-306       | Mini pc     | [f612ea4b42](https://linux-hardware.org/?probe=f612ea4b42) | Oct 02, 2023 |
| HP            | ProBook 6560b               | Notebook    | [ea59e8557f](https://linux-hardware.org/?probe=ea59e8557f) | Oct 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f52bb9587d](https://linux-hardware.org/?probe=f52bb9587d) | Oct 01, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [06371cc0f7](https://linux-hardware.org/?probe=06371cc0f7) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [f9be6afb3a](https://linux-hardware.org/?probe=f9be6afb3a) | Oct 01, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [6faa4fd636](https://linux-hardware.org/?probe=6faa4fd636) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [61a08e5e89](https://linux-hardware.org/?probe=61a08e5e89) | Oct 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0a11dba9ac](https://linux-hardware.org/?probe=0a11dba9ac) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [d180995f93](https://linux-hardware.org/?probe=d180995f93) | Sep 30, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [63c99972d1](https://linux-hardware.org/?probe=63c99972d1) | Sep 30, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [b223d9b4f5](https://linux-hardware.org/?probe=b223d9b4f5) | Sep 30, 2023 |
| Dell          | Latitude 5430               | Notebook    | [eee2a34ff5](https://linux-hardware.org/?probe=eee2a34ff5) | Sep 30, 2023 |
| HP            | ProBook 6560b               | Notebook    | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a0e4942d9f](https://linux-hardware.org/?probe=a0e4942d9f) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| HP            | Notebook                    | Notebook    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [6e7e482b2d](https://linux-hardware.org/?probe=6e7e482b2d) | Sep 29, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [e1f22fdce4](https://linux-hardware.org/?probe=e1f22fdce4) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [4befa6db63](https://linux-hardware.org/?probe=4befa6db63) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0e4e90fac1](https://linux-hardware.org/?probe=0e4e90fac1) | Sep 29, 2023 |
| Lenovo        | IdeaPad Y530                | Notebook    | [83a6d1b19b](https://linux-hardware.org/?probe=83a6d1b19b) | Sep 28, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| HP            | 620                         | Notebook    | [1bdfd56638](https://linux-hardware.org/?probe=1bdfd56638) | Sep 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4ef9eaaaba](https://linux-hardware.org/?probe=4ef9eaaaba) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5646b6da22](https://linux-hardware.org/?probe=5646b6da22) | Sep 27, 2023 |
| HP            | 1589                        | Desktop     | [1063a6e665](https://linux-hardware.org/?probe=1063a6e665) | Sep 27, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [8e70938939](https://linux-hardware.org/?probe=8e70938939) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [4f1f07158b](https://linux-hardware.org/?probe=4f1f07158b) | Sep 26, 2023 |
| Google        | Blorb                       | Notebook    | [efa4ad9e2c](https://linux-hardware.org/?probe=efa4ad9e2c) | Sep 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | Notebook    | [d4137582b5](https://linux-hardware.org/?probe=d4137582b5) | Sep 26, 2023 |
| Google        | Phaser360                   | Notebook    | [95686db08c](https://linux-hardware.org/?probe=95686db08c) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | Notebook    | [aa988ac4df](https://linux-hardware.org/?probe=aa988ac4df) | Sep 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8S77U1... | Notebook    | [4a3185fd78](https://linux-hardware.org/?probe=4a3185fd78) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5ab77e3f48](https://linux-hardware.org/?probe=5ab77e3f48) | Sep 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [8ebd8669f2](https://linux-hardware.org/?probe=8ebd8669f2) | Sep 26, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [32a39c6a01](https://linux-hardware.org/?probe=32a39c6a01) | Sep 25, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [2881d9e4ec](https://linux-hardware.org/?probe=2881d9e4ec) | Sep 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [4c68092d28](https://linux-hardware.org/?probe=4c68092d28) | Sep 25, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [3afc2a0804](https://linux-hardware.org/?probe=3afc2a0804) | Sep 24, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [694b4ab1f2](https://linux-hardware.org/?probe=694b4ab1f2) | Sep 24, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| HP            | 3397                        | Desktop     | [cc6f1cc8ba](https://linux-hardware.org/?probe=cc6f1cc8ba) | Sep 24, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [3b050c2582](https://linux-hardware.org/?probe=3b050c2582) | Sep 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [ff891ca545](https://linux-hardware.org/?probe=ff891ca545) | Sep 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [da4274c691](https://linux-hardware.org/?probe=da4274c691) | Sep 24, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b3a0648c6e](https://linux-hardware.org/?probe=b3a0648c6e) | Sep 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6b3c3ce703](https://linux-hardware.org/?probe=6b3c3ce703) | Sep 23, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [5735f79e4f](https://linux-hardware.org/?probe=5735f79e4f) | Sep 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [46a99bb50a](https://linux-hardware.org/?probe=46a99bb50a) | Sep 23, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e2dd7767f0](https://linux-hardware.org/?probe=e2dd7767f0) | Sep 23, 2023 |
| Dell          | Precision M6600             | Notebook    | [1cef385aec](https://linux-hardware.org/?probe=1cef385aec) | Sep 23, 2023 |
| ASUSTek       | P5K                         | Desktop     | [4d67ad50cf](https://linux-hardware.org/?probe=4d67ad50cf) | Sep 22, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [4bf358cd4f](https://linux-hardware.org/?probe=4bf358cd4f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Dell          | Latitude 5421               | Notebook    | [fd5892945d](https://linux-hardware.org/?probe=fd5892945d) | Sep 21, 2023 |
| Dell          | Latitude 5421               | Notebook    | [50a3d79521](https://linux-hardware.org/?probe=50a3d79521) | Sep 21, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [37990955f8](https://linux-hardware.org/?probe=37990955f8) | Sep 21, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [8e60d0df9c](https://linux-hardware.org/?probe=8e60d0df9c) | Sep 21, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [ff9bab7040](https://linux-hardware.org/?probe=ff9bab7040) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [459e666cd3](https://linux-hardware.org/?probe=459e666cd3) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [dfb78764ea](https://linux-hardware.org/?probe=dfb78764ea) | Sep 20, 2023 |
| Lenovo        | ThinkPad X270 20HMS0DF00    | Notebook    | [276048d4f4](https://linux-hardware.org/?probe=276048d4f4) | Sep 20, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a7eae64ec7](https://linux-hardware.org/?probe=a7eae64ec7) | Sep 20, 2023 |
| Lenovo        | ThinkPad E580 20KS001RUK    | Notebook    | [9882734ee2](https://linux-hardware.org/?probe=9882734ee2) | Sep 20, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [b66d6be0cf](https://linux-hardware.org/?probe=b66d6be0cf) | Sep 19, 2023 |
| HP            | 3047h                       | Desktop     | [f684816e88](https://linux-hardware.org/?probe=f684816e88) | Sep 19, 2023 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [e76f3de142](https://linux-hardware.org/?probe=e76f3de142) | Sep 19, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [0ad032f320](https://linux-hardware.org/?probe=0ad032f320) | Sep 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0748266b0a](https://linux-hardware.org/?probe=0748266b0a) | Sep 19, 2023 |
| Medion        | MS-7848                     | Desktop     | [acbe0e1821](https://linux-hardware.org/?probe=acbe0e1821) | Sep 19, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [8d1653a141](https://linux-hardware.org/?probe=8d1653a141) | Sep 19, 2023 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [1ac41cc2e4](https://linux-hardware.org/?probe=1ac41cc2e4) | Sep 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [0a698044d8](https://linux-hardware.org/?probe=0a698044d8) | Sep 19, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [5680b32e39](https://linux-hardware.org/?probe=5680b32e39) | Sep 18, 2023 |
| Dell          | 0DY2X0 A01                  | Server      | [2384b2e12c](https://linux-hardware.org/?probe=2384b2e12c) | Sep 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7b51f6f455](https://linux-hardware.org/?probe=7b51f6f455) | Sep 18, 2023 |
| HP            | Notebook                    | Notebook    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| Dell          | Latitude 5490               | Notebook    | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMS    | Notebook    | [13de66f73a](https://linux-hardware.org/?probe=13de66f73a) | Sep 17, 2023 |
| Dell          | Latitude E5420              | Notebook    | [56c6b73d62](https://linux-hardware.org/?probe=56c6b73d62) | Sep 17, 2023 |
| Dell          | Latitude E5420              | Notebook    | [5931b51b00](https://linux-hardware.org/?probe=5931b51b00) | Sep 17, 2023 |
| HP            | G72                         | Notebook    | [b77f2ba361](https://linux-hardware.org/?probe=b77f2ba361) | Sep 17, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [8368825071](https://linux-hardware.org/?probe=8368825071) | Sep 17, 2023 |
| Dell          | Latitude 5421               | Notebook    | [a42c87b953](https://linux-hardware.org/?probe=a42c87b953) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | Notebook    | [ba678c25e1](https://linux-hardware.org/?probe=ba678c25e1) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | Notebook    | [b056244ce9](https://linux-hardware.org/?probe=b056244ce9) | Sep 17, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [8af23c2e56](https://linux-hardware.org/?probe=8af23c2e56) | Sep 17, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [35d0dc4629](https://linux-hardware.org/?probe=35d0dc4629) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [50bfb485e5](https://linux-hardware.org/?probe=50bfb485e5) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d795a474b2](https://linux-hardware.org/?probe=d795a474b2) | Sep 16, 2023 |
| ASUSTek       | PRIME H770-PLUS             | Desktop     | [c58fea9225](https://linux-hardware.org/?probe=c58fea9225) | Sep 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9915642af4](https://linux-hardware.org/?probe=9915642af4) | Sep 16, 2023 |
| Acer          | Predator G3-710             | Desktop     | [aa2ac7f07c](https://linux-hardware.org/?probe=aa2ac7f07c) | Sep 16, 2023 |
| Dell          | Latitude 9420               | Notebook    | [35feb16995](https://linux-hardware.org/?probe=35feb16995) | Sep 15, 2023 |
| HP            | 339A                        | Desktop     | [5808e19d94](https://linux-hardware.org/?probe=5808e19d94) | Sep 15, 2023 |
| Dell          | Latitude 9420               | Notebook    | [da407d0553](https://linux-hardware.org/?probe=da407d0553) | Sep 15, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [7cf209e4c1](https://linux-hardware.org/?probe=7cf209e4c1) | Sep 15, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [a3d82edc9c](https://linux-hardware.org/?probe=a3d82edc9c) | Sep 15, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [8f1762e098](https://linux-hardware.org/?probe=8f1762e098) | Sep 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [d321e5cfc8](https://linux-hardware.org/?probe=d321e5cfc8) | Sep 14, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [96f4c972a0](https://linux-hardware.org/?probe=96f4c972a0) | Sep 14, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [c3d0531198](https://linux-hardware.org/?probe=c3d0531198) | Sep 14, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [a5acc6026f](https://linux-hardware.org/?probe=a5acc6026f) | Sep 14, 2023 |
| Toshiba       | Intel H81/Q87 PCH 32        | All in one  | [43275b430f](https://linux-hardware.org/?probe=43275b430f) | Sep 14, 2023 |
| ASUSTek       | P553UJ                      | Notebook    | [3463413300](https://linux-hardware.org/?probe=3463413300) | Sep 14, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [df814b2a84](https://linux-hardware.org/?probe=df814b2a84) | Sep 13, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a09109e90c](https://linux-hardware.org/?probe=a09109e90c) | Sep 13, 2023 |
| Dell          | 07T4MC A06                  | Desktop     | [393a33da8c](https://linux-hardware.org/?probe=393a33da8c) | Sep 12, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d4e392a0ad](https://linux-hardware.org/?probe=d4e392a0ad) | Sep 12, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [49cc8ea6d2](https://linux-hardware.org/?probe=49cc8ea6d2) | Sep 12, 2023 |
| Dell          | Latitude E4200              | Notebook    | [ab13ebe930](https://linux-hardware.org/?probe=ab13ebe930) | Sep 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a03ec42023](https://linux-hardware.org/?probe=a03ec42023) | Sep 12, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [34149789e7](https://linux-hardware.org/?probe=34149789e7) | Sep 12, 2023 |
| HP            | 620                         | Notebook    | [59577ac122](https://linux-hardware.org/?probe=59577ac122) | Sep 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [27b430aa3f](https://linux-hardware.org/?probe=27b430aa3f) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7c32a84014](https://linux-hardware.org/?probe=7c32a84014) | Sep 11, 2023 |
| Dell          | 0HJK12 A03                  | Server      | [b4ec3650ef](https://linux-hardware.org/?probe=b4ec3650ef) | Sep 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [3716cce5f9](https://linux-hardware.org/?probe=3716cce5f9) | Sep 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [77105eb7da](https://linux-hardware.org/?probe=77105eb7da) | Sep 11, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [de229ab61f](https://linux-hardware.org/?probe=de229ab61f) | Sep 11, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a25f4b1c5c](https://linux-hardware.org/?probe=a25f4b1c5c) | Sep 11, 2023 |
| Dell          | Precision 5530              | Notebook    | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| Dell          | 07T4MC A06                  | Desktop     | [ec26895704](https://linux-hardware.org/?probe=ec26895704) | Sep 10, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9b4b4d897f](https://linux-hardware.org/?probe=9b4b4d897f) | Sep 10, 2023 |
| LG Electro... | 15Z990-U.AAS5U1             | Notebook    | [61eed61cd5](https://linux-hardware.org/?probe=61eed61cd5) | Sep 10, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f01636c129](https://linux-hardware.org/?probe=f01636c129) | Sep 09, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | Notebook    | [e35abd1445](https://linux-hardware.org/?probe=e35abd1445) | Sep 09, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [dffd28975a](https://linux-hardware.org/?probe=dffd28975a) | Sep 09, 2023 |
| HP            | ProBook 6470b               | Notebook    | [1c8817d025](https://linux-hardware.org/?probe=1c8817d025) | Sep 09, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [23e3266b07](https://linux-hardware.org/?probe=23e3266b07) | Sep 08, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [032db27cfa](https://linux-hardware.org/?probe=032db27cfa) | Sep 08, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [786aafb0e9](https://linux-hardware.org/?probe=786aafb0e9) | Sep 07, 2023 |
| HP            | 1589                        | Desktop     | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [1aa546be8c](https://linux-hardware.org/?probe=1aa546be8c) | Sep 05, 2023 |
| MSI           | P55-GD65                    | Desktop     | [2b514a72b1](https://linux-hardware.org/?probe=2b514a72b1) | Sep 05, 2023 |
| Dell          | Precision M4800             | Notebook    | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| Prestigio     | Smartbook PSB116A           | Notebook    | [d70df77a35](https://linux-hardware.org/?probe=d70df77a35) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f51b98f4cd](https://linux-hardware.org/?probe=f51b98f4cd) | Sep 04, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [8585671bfb](https://linux-hardware.org/?probe=8585671bfb) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [a9fdf4f92b](https://linux-hardware.org/?probe=a9fdf4f92b) | Sep 03, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [dcb8595c51](https://linux-hardware.org/?probe=dcb8595c51) | Sep 03, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [5f73c55303](https://linux-hardware.org/?probe=5f73c55303) | Sep 03, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | Notebook    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [8533d021f8](https://linux-hardware.org/?probe=8533d021f8) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9f3df2894e](https://linux-hardware.org/?probe=9f3df2894e) | Sep 02, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f6a5d73879](https://linux-hardware.org/?probe=f6a5d73879) | Sep 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [fd0297e4e0](https://linux-hardware.org/?probe=fd0297e4e0) | Sep 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [d5d9154715](https://linux-hardware.org/?probe=d5d9154715) | Sep 01, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | Notebook    | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| HP            | 1589                        | Desktop     | [447cae1b4c](https://linux-hardware.org/?probe=447cae1b4c) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | Notebook    | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [0ac2938640](https://linux-hardware.org/?probe=0ac2938640) | Aug 31, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 600       | 9.57%   |
| Ubuntu 22.04       | 323       | 5.15%   |
| OpenMandriva 4.2   | 318       | 5.07%   |
| Ubuntu 18.04       | 281       | 4.48%   |
| OpenMandriva 4.3   | 236       | 3.77%   |
| Arch Rolling       | 179       | 2.86%   |
| Debian 11          | 167       | 2.66%   |
| OpenMandriva 23.03 | 106       | 1.69%   |
| ROSA R10           | 98        | 1.56%   |
| Zorin 16           | 93        | 1.48%   |
| OpenMandriva 23.01 | 93        | 1.48%   |
| OpenMandriva 23.08 | 81        | 1.29%   |
| Linux Mint 21.1    | 81        | 1.29%   |
| Fedora 38          | 77        | 1.23%   |
| Manjaro            | 76        | 1.21%   |
| Linux Mint 20.3    | 73        | 1.16%   |
| ROSA R9            | 70        | 1.12%   |
| ROSA R11.1         | 69        | 1.1%    |
| ROSA R11           | 69        | 1.1%    |
| Debian 12          | 69        | 1.1%    |
| Pop!_OS 22.04      | 68        | 1.09%   |
| Arch               | 68        | 1.09%   |
| Fedora 37          | 67        | 1.07%   |
| Linux Mint 20.1    | 66        | 1.05%   |
| KDE neon 20.04     | 64        | 1.02%   |
| Fedora 36          | 60        | 0.96%   |
| Ubuntu 20.10       | 57        | 0.91%   |
| Linux Mint 20.2    | 55        | 0.88%   |
| Ubuntu 21.04       | 50        | 0.8%    |
| Linux Mint 21.2    | 50        | 0.8%    |
| Linux Mint 20      | 49        | 0.78%   |
| Linux Mint 19.3    | 49        | 0.78%   |
| Ubuntu 19.10       | 48        | 0.77%   |
| Fedora 39          | 48        | 0.77%   |
| Ubuntu 22.10       | 46        | 0.73%   |
| Ubuntu 21.10       | 44        | 0.7%    |
| OpenMandriva 5.0   | 43        | 0.69%   |
| Fedora 35          | 43        | 0.69%   |
| ROSA R8            | 42        | 0.67%   |
| Linux Mint 21      | 42        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1473      | 25.52%  |
| OpenMandriva  | 884       | 15.32%  |
| Linux Mint    | 467       | 8.09%   |
| Fedora        | 411       | 7.12%   |
| ROSA          | 345       | 5.98%   |
| Debian        | 305       | 5.28%   |
| Arch          | 239       | 4.14%   |
| Manjaro       | 214       | 3.71%   |
| Pop!_OS       | 165       | 2.86%   |
| Zorin         | 137       | 2.37%   |
| Kubuntu       | 115       | 1.99%   |
| KDE neon      | 98        | 1.7%    |
| Xubuntu       | 86        | 1.49%   |
| openSUSE      | 56        | 0.97%   |
| Kali          | 56        | 0.97%   |
| Gentoo        | 52        | 0.9%    |
| ArcoLinux     | 45        | 0.78%   |
| SteamOS       | 40        | 0.69%   |
| Lubuntu       | 40        | 0.69%   |
| LMDE          | 38        | 0.66%   |
| EndeavourOS   | 38        | 0.66%   |
| Elementary    | 38        | 0.66%   |
| Endless       | 37        | 0.64%   |
| Ubuntu Unity  | 22        | 0.38%   |
| Ubuntu MATE   | 22        | 0.38%   |
| MX            | 22        | 0.38%   |
| Nobara        | 21        | 0.36%   |
| Clear Linux   | 21        | 0.36%   |
| Xero          | 20        | 0.35%   |
| BlackPanther  | 18        | 0.31%   |
| Garuda Linux  | 17        | 0.29%   |
| CentOS        | 15        | 0.26%   |
| Ubuntu Budgie | 14        | 0.24%   |
| Peppermint    | 12        | 0.21%   |
| Raspbian      | 10        | 0.17%   |
| NixOS         | 10        | 0.17%   |
| LinuxFX       | 10        | 0.17%   |
| EuroLinux     | 10        | 0.17%   |
| Linux Lite    | 8         | 0.14%   |
| Artix         | 8         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 304       | 4.35%   |
| 5.16.7-desktop-1omv4003         | 215       | 3.07%   |
| 6.2.6-desktop-1omv2390          | 101       | 1.44%   |
| 6.1.1-desktop-1omv2290          | 83        | 1.19%   |
| 5.4.0-42-generic                | 78        | 1.12%   |
| 6.4.11-desktop-1omv2390         | 72        | 1.03%   |
| 5.15.0-56-generic               | 60        | 0.86%   |
| 6.6.2-desktop-1omv2390          | 55        | 0.79%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 54        | 0.77%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 53        | 0.76%   |
| 5.15.0-43-generic               | 42        | 0.6%    |
| 5.4.0-26-generic                | 40        | 0.57%   |
| 5.15.0-58-generic               | 39        | 0.56%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 39        | 0.56%   |
| 5.4.0-52-generic                | 38        | 0.54%   |
| 5.4.0-48-generic                | 36        | 0.51%   |
| 5.15.0-52-generic               | 36        | 0.51%   |
| 5.19.0-35-generic               | 35        | 0.5%    |
| 5.4.0-58-generic                | 33        | 0.47%   |
| 5.4.0-29-generic                | 30        | 0.43%   |
| 5.3.0-46-generic                | 30        | 0.43%   |
| 5.4.0-54-generic                | 29        | 0.41%   |
| 5.19.0-32-generic               | 29        | 0.41%   |
| 5.8.0-43-generic                | 27        | 0.39%   |
| 5.13.0-39-generic               | 27        | 0.39%   |
| 5.11.0-37-generic               | 27        | 0.39%   |
| 5.4.0-40-generic                | 26        | 0.37%   |
| 5.16.13-desktop-1omv4003        | 26        | 0.37%   |
| 5.4.0-37-generic                | 25        | 0.36%   |
| 5.15.0-48-generic               | 25        | 0.36%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 24        | 0.34%   |
| 5.4.0-66-generic                | 23        | 0.33%   |
| 5.4.0-33-generic                | 23        | 0.33%   |
| 5.13.0-27-generic               | 23        | 0.33%   |
| 5.3.0-42-generic                | 22        | 0.31%   |
| 5.15.0-60-generic               | 22        | 0.31%   |
| 5.11.0-27-generic               | 22        | 0.31%   |
| 5.0.0-37-generic                | 22        | 0.31%   |
| 6.2.0-39-generic                | 21        | 0.3%    |
| 6.2.0-33-generic                | 21        | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 773       | 11.71%  |
| 5.15.0  | 494       | 7.49%   |
| 5.10.14 | 306       | 4.64%   |
| 4.15.0  | 289       | 4.38%   |
| 5.11.0  | 224       | 3.39%   |
| 5.8.0   | 222       | 3.36%   |
| 5.16.7  | 218       | 3.3%    |
| 5.13.0  | 204       | 3.09%   |
| 5.10.0  | 175       | 2.65%   |
| 5.19.0  | 169       | 2.56%   |
| 5.3.0   | 166       | 2.52%   |
| 6.2.0   | 142       | 2.15%   |
| 6.2.6   | 123       | 1.86%   |
| 5.0.0   | 101       | 1.53%   |
| 6.1.0   | 96        | 1.45%   |
| 4.18.0  | 91        | 1.38%   |
| 6.1.1   | 85        | 1.29%   |
| 6.4.11  | 76        | 1.15%   |
| 4.9.60  | 66        | 1%      |
| 6.6.2   | 62        | 0.94%   |
| 4.9.20  | 62        | 0.94%   |
| 6.5.0   | 59        | 0.89%   |
| 4.19.0  | 55        | 0.83%   |
| 5.14.0  | 40        | 0.61%   |
| 4.1.34  | 32        | 0.48%   |
| 5.16.13 | 28        | 0.42%   |
| 4.1.38  | 28        | 0.42%   |
| 6.0.0   | 26        | 0.39%   |
| 5.17.5  | 20        | 0.3%    |
| 5.4.32  | 19        | 0.29%   |
| 5.11.12 | 19        | 0.29%   |
| 6.5.5   | 18        | 0.27%   |
| 5.9.0   | 18        | 0.27%   |
| 6.0.12  | 17        | 0.26%   |
| 4.9.155 | 17        | 0.26%   |
| 4.9.76  | 16        | 0.24%   |
| 4.9.124 | 16        | 0.24%   |
| 6.6.8   | 15        | 0.23%   |
| 6.0.7   | 15        | 0.23%   |
| 5.17.0  | 15        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 877       | 13.72%  |
| 5.15    | 641       | 10.03%  |
| 5.10    | 597       | 9.34%   |
| 6.2     | 353       | 5.52%   |
| 6.1     | 324       | 5.07%   |
| 5.16    | 314       | 4.91%   |
| 5.11    | 290       | 4.54%   |
| 4.15    | 289       | 4.52%   |
| 5.8     | 280       | 4.38%   |
| 5.13    | 235       | 3.68%   |
| 5.19    | 227       | 3.55%   |
| 5.3     | 186       | 2.91%   |
| 4.9     | 185       | 2.9%    |
| 6.6     | 148       | 2.32%   |
| 6.5     | 147       | 2.3%    |
| 6.4     | 145       | 2.27%   |
| 6.0     | 131       | 2.05%   |
| 5.0     | 111       | 1.74%   |
| 4.18    | 103       | 1.61%   |
| 5.14    | 101       | 1.58%   |
| 5.17    | 81        | 1.27%   |
| 5.9     | 74        | 1.16%   |
| 6.3     | 73        | 1.14%   |
| 5.6     | 70        | 1.1%    |
| 5.18    | 70        | 1.1%    |
| 4.19    | 68        | 1.06%   |
| 4.1     | 63        | 0.99%   |
| 5.12    | 60        | 0.94%   |
| 5.5     | 39        | 0.61%   |
| 5.7     | 35        | 0.55%   |
| 4.4     | 17        | 0.27%   |
| 6.7     | 8         | 0.13%   |
| 5.1     | 8         | 0.13%   |
| 3.10    | 7         | 0.11%   |
| 5.2     | 5         | 0.08%   |
| 4.20    | 4         | 0.06%   |
| 4.16    | 3         | 0.05%   |
| 4.13    | 3         | 0.05%   |
| 4.8     | 2         | 0.03%   |
| 4.7     | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5328      | 96.17%  |
| i686    | 157       | 2.83%   |
| aarch64 | 29        | 0.52%   |
| armv7l  | 19        | 0.34%   |
| armv8l  | 3         | 0.05%   |
| armv6l  | 2         | 0.04%   |
| ppc64   | 1         | 0.02%   |
| ppc     | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2097      | 35.91%  |
| KDE5             | 1596      | 27.33%  |
| Unknown          | 516       | 8.84%   |
| XFCE             | 404       | 6.92%   |
| X-Cinnamon       | 341       | 5.84%   |
| KDE4             | 179       | 3.07%   |
| MATE             | 143       | 2.45%   |
| KDE              | 127       | 2.18%   |
| LXQt             | 89        | 1.52%   |
| Cinnamon         | 71        | 1.22%   |
| LXDE             | 51        | 0.87%   |
| i3               | 40        | 0.69%   |
| Pantheon         | 37        | 0.63%   |
| Unity            | 25        | 0.43%   |
| Budgie           | 24        | 0.41%   |
| Deepin           | 16        | 0.27%   |
| GNOME Flashback  | 13        | 0.22%   |
| Hyprland         | 11        | 0.19%   |
| GNOME Classic    | 7         | 0.12%   |
| sway             | 6         | 0.1%    |
| openbox          | 6         | 0.1%    |
| awesome          | 6         | 0.1%    |
| qtile            | 5         | 0.09%   |
| icewm            | 5         | 0.09%   |
| DWM              | 4         | 0.07%   |
| lightdm-xsession | 3         | 0.05%   |
| Fluxbox          | 3         | 0.05%   |
| trinity          | 2         | 0.03%   |
| GNUstep          | 2         | 0.03%   |
| xmonad           | 1         | 0.02%   |
| stumpwm          | 1         | 0.02%   |
| ratflow          | 1         | 0.02%   |
| qt5ct            | 1         | 0.02%   |
| MakuluGameR      | 1         | 0.02%   |
| jwm              | 1         | 0.02%   |
| gnome-xorg       | 1         | 0.02%   |
| gamescope        | 1         | 0.02%   |
| Endless:GNOME    | 1         | 0.02%   |
| BunsenLabs       | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 4304      | 74.85%  |
| Wayland     | 1074      | 18.68%  |
| Unknown     | 254       | 4.42%   |
| Tty         | 117       | 2.03%   |
| Unspecified | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2261      | 38.93%  |
| SDDM    | 1465      | 25.22%  |
| GDM     | 595       | 10.24%  |
| GDM3    | 570       | 9.81%   |
| LightDM | 543       | 9.35%   |
| KDM     | 189       | 3.25%   |
| TDM     | 152       | 2.62%   |
| XDM     | 12        | 0.21%   |
| Ly      | 4         | 0.07%   |
| LXDM    | 4         | 0.07%   |
| SLIMSKI | 3         | 0.05%   |
| SLiM    | 3         | 0.05%   |
| NODM    | 2         | 0.03%   |
| MDM     | 2         | 0.03%   |
| LY-DM   | 2         | 0.03%   |
| SU      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pl_PL       | 3117      | 54.22%  |
| en_US       | 1550      | 26.96%  |
| Unknown     | 655       | 11.39%  |
| en_GB       | 160       | 2.78%   |
| C           | 114       | 1.98%   |
| ru_RU       | 39        | 0.68%   |
| uk_UA       | 12        | 0.21%   |
| szl_PL      | 12        | 0.21%   |
| ru_UA       | 12        | 0.21%   |
| de_DE       | 11        | 0.19%   |
| en_CA       | 8         | 0.14%   |
| fr_FR       | 6         | 0.1%    |
| en_IE       | 6         | 0.1%    |
| POSIX       | 5         | 0.09%   |
| en_DK       | 5         | 0.09%   |
| en_AG       | 4         | 0.07%   |
| C.UTF8      | 4         | 0.07%   |
| it_IT       | 3         | 0.05%   |
| nl_NL       | 2         | 0.03%   |
| hu_HU       | 2         | 0.03%   |
| es_ES       | 2         | 0.03%   |
| en_US.utf-8 | 2         | 0.03%   |
| en_IN       | 2         | 0.03%   |
| sv_SE       | 1         | 0.02%   |
| sk_SK       | 1         | 0.02%   |
| pl_PL.UTF8  | 1         | 0.02%   |
| es_BO       | 1         | 0.02%   |
| es_AR       | 1         | 0.02%   |
| en_US.UTF8  | 1         | 0.02%   |
| en_US.UTF.8 | 1         | 0.02%   |
| en_SE       | 1         | 0.02%   |
| en_AU       | 1         | 0.02%   |
| el_GR       | 1         | 0.02%   |
| de_CH       | 1         | 0.02%   |
| Default     | 1         | 0.02%   |
| cs_CZ       | 1         | 0.02%   |
| be_BY       | 1         | 0.02%   |
| af_ZA       | 1         | 0.02%   |
| aa_DJ       | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3025      | 53.31%  |
| EFI  | 2649      | 46.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3819      | 66.08%  |
| Overlay  | 797       | 13.79%  |
| Btrfs    | 579       | 10.02%  |
| Unknown  | 299       | 5.17%   |
| Tmpfs    | 122       | 2.11%   |
| Xfs      | 82        | 1.42%   |
| Zfs      | 36        | 0.62%   |
| F2fs     | 20        | 0.35%   |
| Ext2     | 7         | 0.12%   |
| Ext3     | 6         | 0.1%    |
| Rootfs   | 3         | 0.05%   |
| Jfs      | 3         | 0.05%   |
| Bcachefs | 2         | 0.03%   |
| XXXXXXX  | 1         | 0.02%   |
| XXXXX    | 1         | 0.02%   |
| SquXshfs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2449      | 42.63%  |
| GPT     | 2319      | 40.37%  |
| MBR     | 977       | 17.01%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4632      | 81.36%  |
| Yes       | 1061      | 18.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3727      | 65.84%  |
| Yes       | 1934      | 34.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 976       | 17.65%  |
| Dell                    | 882       | 15.95%  |
| ASUSTek Computer        | 824       | 14.9%   |
| Hewlett-Packard         | 686       | 12.41%  |
| Gigabyte Technology     | 469       | 8.48%   |
| MSI                     | 413       | 7.47%   |
| Acer                    | 230       | 4.16%   |
| ASRock                  | 195       | 3.53%   |
| Samsung Electronics     | 93        | 1.68%   |
| Toshiba                 | 91        | 1.65%   |
| Fujitsu                 | 63        | 1.14%   |
| Apple                   | 52        | 0.94%   |
| HUAWEI                  | 40        | 0.72%   |
| Sony                    | 37        | 0.67%   |
| Intel                   | 37        | 0.67%   |
| Fujitsu Siemens         | 34        | 0.61%   |
| Valve                   | 32        | 0.58%   |
| Google                  | 29        | 0.52%   |
| Unknown                 | 27        | 0.49%   |
| Raspberry Pi Foundation | 26        | 0.47%   |
| Medion                  | 20        | 0.36%   |
| Packard Bell            | 16        | 0.29%   |
| Notebook                | 16        | 0.29%   |
| Foxconn                 | 15        | 0.27%   |
| Kiano                   | 13        | 0.24%   |
| eMachines               | 12        | 0.22%   |
| Timi                    | 10        | 0.18%   |
| Inventec                | 10        | 0.18%   |
| AMI                     | 8         | 0.14%   |
| mPTech                  | 7         | 0.13%   |
| Microsoft               | 6         | 0.11%   |
| Huanan                  | 6         | 0.11%   |
| ZOTAC                   | 5         | 0.09%   |
| Supermicro              | 5         | 0.09%   |
| Kruger&Matz             | 4         | 0.07%   |
| GPU Company             | 4         | 0.07%   |
| Gateway                 | 4         | 0.07%   |
| ECS                     | 4         | 0.07%   |
| Clevo                   | 4         | 0.07%   |
| Chuwi                   | 4         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 52        | 0.94%   |
| ASUS All Series                     | 36        | 0.65%   |
| Dell Inspiron 3451                  | 31        | 0.56%   |
| Valve Jupiter                       | 30        | 0.54%   |
| Gigabyte B450M DS3H                 | 20        | 0.36%   |
| MSI MS-7B86                         | 19        | 0.34%   |
| Dell Latitude E6400                 | 19        | 0.34%   |
| ASUS SABERTOOTH Z77                 | 18        | 0.33%   |
| MSI MS-7817                         | 17        | 0.31%   |
| Dell OptiPlex 780                   | 15        | 0.27%   |
| Dell Latitude E6540                 | 15        | 0.27%   |
| MSI MS-7C37                         | 14        | 0.25%   |
| MSI MS-7C02                         | 14        | 0.25%   |
| Lenovo G50-30 80G0                  | 14        | 0.25%   |
| HP Pavilion dv7                     | 13        | 0.24%   |
| Dell Latitude E6430                 | 13        | 0.24%   |
| ASUS X555LJ                         | 13        | 0.24%   |
| Dell OptiPlex 7010                  | 12        | 0.22%   |
| Dell Latitude E7440                 | 12        | 0.22%   |
| Dell Latitude D630                  | 12        | 0.22%   |
| Dell Latitude 5490                  | 12        | 0.22%   |
| Dell Latitude 5480                  | 12        | 0.22%   |
| MSI MS-7816                         | 11        | 0.2%    |
| MSI MS-7721                         | 11        | 0.2%    |
| Lenovo G580 20150                   | 11        | 0.2%    |
| Gigabyte B550 AORUS ELITE V2        | 11        | 0.2%    |
| MSI MS-7B79                         | 10        | 0.18%   |
| Lenovo Legion Y530-15ICH 81FV       | 10        | 0.18%   |
| Lenovo G510 20238                   | 10        | 0.18%   |
| HP Notebook                         | 10        | 0.18%   |
| Gigabyte B450 AORUS ELITE           | 10        | 0.18%   |
| Dell OptiPlex 755                   | 10        | 0.18%   |
| Dell Latitude E6420                 | 10        | 0.18%   |
| Dell Latitude E6330                 | 10        | 0.18%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 9         | 0.16%   |
| HP Pavilion dv6                     | 9         | 0.16%   |
| HP 15                               | 9         | 0.16%   |
| Gigabyte B85M-D3H                   | 9         | 0.16%   |
| Dell Latitude E6440                 | 9         | 0.16%   |
| Dell Latitude E5430 non-vPro        | 9         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 406       | 7.34%   |
| Dell Latitude      | 367       | 6.64%   |
| Dell Inspiron      | 177       | 3.2%    |
| Lenovo IdeaPad     | 174       | 3.15%   |
| Acer Aspire        | 135       | 2.44%   |
| HP EliteBook       | 121       | 2.19%   |
| Dell OptiPlex      | 119       | 2.15%   |
| HP Pavilion        | 111       | 2.01%   |
| ASUS PRIME         | 84        | 1.52%   |
| HP Compaq          | 81        | 1.46%   |
| HP ProBook         | 76        | 1.37%   |
| Dell Precision     | 76        | 1.37%   |
| Toshiba Satellite  | 74        | 1.34%   |
| Lenovo Legion      | 68        | 1.23%   |
| ASUS TUF           | 63        | 1.14%   |
| ASUS ROG           | 55        | 0.99%   |
| Unknown            | 52        | 0.94%   |
| Dell Vostro        | 48        | 0.87%   |
| Lenovo ThinkCentre | 47        | 0.85%   |
| ASUS VivoBook      | 47        | 0.85%   |
| HP Laptop          | 42        | 0.76%   |
| ASUS All           | 36        | 0.65%   |
| Dell XPS           | 35        | 0.63%   |
| ASUS ASUS          | 31        | 0.56%   |
| Valve Jupiter      | 30        | 0.54%   |
| Gigabyte B450M     | 29        | 0.52%   |
| RPi Raspberry      | 26        | 0.47%   |
| HP EliteDesk       | 26        | 0.47%   |
| Fujitsu LIFEBOOK   | 24        | 0.43%   |
| HP 250             | 23        | 0.42%   |
| Fujitsu ESPRIMO    | 22        | 0.4%    |
| Lenovo Yoga        | 21        | 0.38%   |
| ASUS SABERTOOTH    | 20        | 0.36%   |
| MSI MS-7B86        | 19        | 0.34%   |
| Lenovo ThinkBook   | 19        | 0.34%   |
| HP ZBook           | 19        | 0.34%   |
| Acer Nitro         | 19        | 0.34%   |
| Gigabyte B550      | 18        | 0.33%   |
| MSI MS-7817        | 17        | 0.31%   |
| ASUS ZenBook       | 17        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 478       | 8.64%   |
| 2018    | 475       | 8.59%   |
| 2013    | 448       | 8.1%    |
| 2019    | 427       | 7.72%   |
| 2020    | 421       | 7.61%   |
| 2011    | 389       | 7.03%   |
| 2014    | 347       | 6.27%   |
| 2017    | 319       | 5.77%   |
| 2015    | 297       | 5.37%   |
| 2021    | 290       | 5.24%   |
| 2008    | 289       | 5.23%   |
| 2010    | 281       | 5.08%   |
| 2016    | 245       | 4.43%   |
| 2009    | 229       | 4.14%   |
| 2007    | 208       | 3.76%   |
| 2022    | 174       | 3.15%   |
| 2006    | 81        | 1.46%   |
| 2023    | 68        | 1.23%   |
| Unknown | 45        | 0.81%   |
| 2005    | 11        | 0.2%    |
| 2004    | 7         | 0.13%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3295      | 59.58%  |
| Desktop        | 1983      | 35.86%  |
| Convertible    | 68        | 1.23%   |
| Mini pc        | 51        | 0.92%   |
| System on chip | 44        | 0.8%    |
| Server         | 33        | 0.6%    |
| All in one     | 25        | 0.45%   |
| Tablet         | 24        | 0.43%   |
| Phone          | 7         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5234      | 93.98%  |
| Enabled  | 335       | 6.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5497      | 99.4%   |
| Yes  | 33        | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1180      | 20.86%  |
| 3.01-4.0        | 1140      | 20.15%  |
| 16.01-24.0      | 1054      | 18.63%  |
| 8.01-16.0       | 1032      | 18.24%  |
| 32.01-64.0      | 616       | 10.89%  |
| 1.01-2.0        | 215       | 3.8%    |
| 64.01-256.0     | 135       | 2.39%   |
| 2.01-3.0        | 132       | 2.33%   |
| 24.01-32.0      | 102       | 1.8%    |
| 0.51-1.0        | 44        | 0.78%   |
| More than 256.0 | 4         | 0.07%   |
| 0.01-0.5        | 4         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2217      | 35.21%  |
| 2.01-3.0        | 1384      | 21.98%  |
| 4.01-8.0        | 936       | 14.86%  |
| 3.01-4.0        | 757       | 12.02%  |
| 0.51-1.0        | 535       | 8.5%    |
| 8.01-16.0       | 283       | 4.49%   |
| 0.01-0.5        | 101       | 1.6%    |
| 16.01-24.0      | 54        | 0.86%   |
| 24.01-32.0      | 17        | 0.27%   |
| Unknown         | 5         | 0.08%   |
| 32.01-64.0      | 4         | 0.06%   |
| 64.01-256.0     | 3         | 0.05%   |
| More than 256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3386      | 58.71%  |
| 2       | 1440      | 24.97%  |
| 3       | 498       | 8.64%   |
| 4       | 192       | 3.33%   |
| 5       | 90        | 1.56%   |
| 0       | 87        | 1.51%   |
| 6       | 34        | 0.59%   |
| 7       | 19        | 0.33%   |
| 8       | 8         | 0.14%   |
| 9       | 4         | 0.07%   |
| 11      | 3         | 0.05%   |
| 10      | 2         | 0.03%   |
| 16      | 1         | 0.02%   |
| 13      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3282      | 58.57%  |
| Yes       | 2322      | 41.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4929      | 88.86%  |
| No        | 618       | 11.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4201      | 75.23%  |
| No        | 1383      | 24.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3229      | 57.37%  |
| No        | 2399      | 42.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 5530      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 1270      | 20.94%  |
| Krakow                 | 447       | 7.37%   |
| Wroclaw                | 359       | 5.92%   |
| Poznan                 | 311       | 5.13%   |
| Gdansk                 | 204       | 3.36%   |
| Lodz                   | 189       | 3.12%   |
| Katowice               | 155       | 2.56%   |
| Lublin                 | 86        | 1.42%   |
| Gdynia                 | 79        | 1.3%    |
| Szczecin               | 73        | 1.2%    |
| Bialystok              | 56        | 0.92%   |
| Gliwice                | 51        | 0.84%   |
| Bydgoszcz              | 47        | 0.77%   |
| Częstochowa           | 46        | 0.76%   |
| Torun                  | 42        | 0.69%   |
| Rzeszów               | 42        | 0.69%   |
| Bytom                  | 39        | 0.64%   |
| Ruda Śląska          | 38        | 0.63%   |
| Kielce                 | 32        | 0.53%   |
| Zabrze                 | 31        | 0.51%   |
| Płock                 | 31        | 0.51%   |
| Sosnowiec              | 29        | 0.48%   |
| Elblag                 | 28        | 0.46%   |
| Bielsko-Biala          | 27        | 0.45%   |
| Rybnik                 | 25        | 0.41%   |
| Olsztyn                | 25        | 0.41%   |
| Radom                  | 22        | 0.36%   |
| Opole                  | 22        | 0.36%   |
| Chorzów               | 22        | 0.36%   |
| Strzyzow               | 21        | 0.35%   |
| Tarnów                | 20        | 0.33%   |
| Tychy                  | 19        | 0.31%   |
| Słupsk                | 19        | 0.31%   |
| Siemianowice Śląskie | 19        | 0.31%   |
| Zielona Góra          | 17        | 0.28%   |
| Cieszyn                | 17        | 0.28%   |
| Kalisz                 | 16        | 0.26%   |
| Debica                 | 16        | 0.26%   |
| Tarnowskie Gory        | 15        | 0.25%   |
| Piaseczno              | 15        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1146      | 1745   | 13.87%  |
| Seagate                     | 1114      | 1744   | 13.48%  |
| WDC                         | 1064      | 1647   | 12.88%  |
| GOODRAM                     | 565       | 869    | 6.84%   |
| Toshiba                     | 491       | 733    | 5.94%   |
| Kingston                    | 316       | 448    | 3.82%   |
| Unknown                     | 313       | 480    | 3.79%   |
| Crucial                     | 311       | 517    | 3.76%   |
| A-DATA Technology           | 311       | 420    | 3.76%   |
| SanDisk                     | 308       | 425    | 3.73%   |
| Hitachi                     | 266       | 398    | 3.22%   |
| Intel                       | 199       | 274    | 2.41%   |
| SK hynix                    | 190       | 243    | 2.3%    |
| Micron Technology           | 139       | 179    | 1.68%   |
| HGST                        | 117       | 150    | 1.42%   |
| Patriot                     | 106       | 138    | 1.28%   |
| SPCC                        | 90        | 148    | 1.09%   |
| KIOXIA                      | 64        | 70     | 0.77%   |
| PNY                         | 63        | 70     | 0.76%   |
| Plextor                     | 63        | 84     | 0.76%   |
| Phison Electronics          | 48        | 62     | 0.58%   |
| Phison                      | 46        | 61     | 0.56%   |
| XPG                         | 44        | 63     | 0.53%   |
| China                       | 42        | 63     | 0.51%   |
| Fujitsu                     | 41        | 49     | 0.5%    |
| Apacer                      | 41        | 68     | 0.5%    |
| ADATA Technology            | 35        | 42     | 0.42%   |
| Silicon Motion              | 32        | 40     | 0.39%   |
| Transcend                   | 30        | 34     | 0.36%   |
| OCZ                         | 30        | 33     | 0.36%   |
| LITEON                      | 29        | 38     | 0.35%   |
| Corsair                     | 27        | 37     | 0.33%   |
| Kingston Technology Company | 25        | 26     | 0.3%    |
| Unknown                     | 25        | 29     | 0.3%    |
| Realtek Semiconductor       | 24        | 36     | 0.29%   |
| Lexar                       | 24        | 26     | 0.29%   |
| Maxtor                      | 23        | 24     | 0.28%   |
| Apple                       | 23        | 29     | 0.28%   |
| Micron/Crucial Technology   | 22        | 24     | 0.27%   |
| KIOXIA-EXCERIA              | 22        | 31     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB                       | 73        | 0.81%   |
| Seagate ST500LT012-1DG142 500GB                    | 69        | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 65        | 0.72%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                   | 64        | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 63        | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB                     | 61        | 0.67%   |
| Toshiba HDWD110 1TB                                | 59        | 0.65%   |
| Samsung SSD 850 EVO 250GB                          | 59        | 0.65%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                   | 52        | 0.57%   |
| GOODRAM SSD 120GB                                  | 52        | 0.57%   |
| Unknown MMC Card  32GB                             | 49        | 0.54%   |
| Crucial CT1000MX500SSD1 1TB                        | 49        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB                    | 45        | 0.5%    |
| Samsung SSD 860 EVO 500GB                          | 43        | 0.48%   |
| GOODRAM SSD 240GB                                  | 43        | 0.48%   |
| Kingston SA400S37240G 240GB SSD                    | 41        | 0.45%   |
| Crucial CT240BX500SSD1 240GB                       | 41        | 0.45%   |
| Unknown MMC Card  64GB                             | 40        | 0.44%   |
| Samsung SSD 980 1TB                                | 38        | 0.42%   |
| GOODRAM SSDPR-CX400-512 512GB                      | 38        | 0.42%   |
| A-DATA SU800 256GB SSD                             | 38        | 0.42%   |
| Seagate ST1000DM010-2EP102 1TB                     | 36        | 0.4%    |
| Kingston SV300S37A120G 120GB SSD                   | 36        | 0.4%    |
| Toshiba MQ01ABD100 1TB                             | 35        | 0.39%   |
| Seagate ST9500325AS 500GB                          | 35        | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB                     | 35        | 0.39%   |
| Samsung SSD 860 EVO 250GB                          | 34        | 0.38%   |
| Seagate ST3500418AS 500GB                          | 33        | 0.36%   |
| Samsung SSD 980 500GB                              | 33        | 0.36%   |
| Samsung NVMe SSD Drive 500GB                       | 32        | 0.35%   |
| Patriot Burst 120GB SSD                            | 32        | 0.35%   |
| GOODRAM SSDPR-CX400-256 256GB                      | 31        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 30        | 0.33%   |
| HGST HTS721010A9E630 1TB                           | 30        | 0.33%   |
| Seagate Expansion 1TB                              | 29        | 0.32%   |
| Toshiba MQ01ABF050 500GB                           | 28        | 0.31%   |
| Samsung NVMe SSD Drive 512GB                       | 28        | 0.31%   |
| Kingston SA400S37480G 480GB SSD                    | 28        | 0.31%   |
| Toshiba DT01ACA100 1TB                             | 27        | 0.3%    |
| Samsung SSD 970 EVO Plus 500GB                     | 27        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1106      | 1730   | 36.13%  |
| WDC                 | 885       | 1395   | 28.91%  |
| Toshiba             | 374       | 589    | 12.22%  |
| Hitachi             | 266       | 398    | 8.69%   |
| Samsung Electronics | 188       | 263    | 6.14%   |
| HGST                | 117       | 150    | 3.82%   |
| Fujitsu             | 41        | 49     | 1.34%   |
| Maxtor              | 21        | 22     | 0.69%   |
| JMicron Technology  | 15        | 19     | 0.49%   |
| Unknown             | 10        | 11     | 0.33%   |
| Apple               | 7         | 7      | 0.23%   |
| ASMT                | 5         | 6      | 0.16%   |
| WD MediaMax         | 3         | 5      | 0.1%    |
| SAGE                | 3         | 3      | 0.1%    |
| StoreJet            | 2         | 2      | 0.07%   |
| IBM/Hitachi         | 2         | 2      | 0.07%   |
| Hewlett-Packard     | 2         | 5      | 0.07%   |
| ASMedia             | 2         | 2      | 0.07%   |
| Unknown             | 2         | 2      | 0.07%   |
| Synology            | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LaCie               | 1         | 2      | 0.03%   |
| Initio              | 1         | 1      | 0.03%   |
| IB-377U3            | 1         | 6      | 0.03%   |
| HPE                 | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| GOODRAM             | 547       | 833    | 18.18%  |
| Samsung Electronics | 487       | 685    | 16.19%  |
| Crucial             | 301       | 505    | 10.01%  |
| A-DATA Technology   | 261       | 350    | 8.68%   |
| Kingston            | 212       | 295    | 7.05%   |
| SanDisk             | 190       | 267    | 6.32%   |
| WDC                 | 97        | 117    | 3.22%   |
| Patriot             | 95        | 127    | 3.16%   |
| SPCC                | 82        | 138    | 2.73%   |
| Micron Technology   | 62        | 78     | 2.06%   |
| Intel               | 62        | 77     | 2.06%   |
| Plextor             | 54        | 75     | 1.8%    |
| Toshiba             | 51        | 56     | 1.7%    |
| PNY                 | 50        | 56     | 1.66%   |
| SK hynix            | 49        | 59     | 1.63%   |
| China               | 41        | 62     | 1.36%   |
| Apacer              | 37        | 62     | 1.23%   |
| OCZ                 | 30        | 33     | 1%      |
| Transcend           | 29        | 33     | 0.96%   |
| LITEON              | 29        | 38     | 0.96%   |
| LITEONIT            | 19        | 21     | 0.63%   |
| KIOXIA-EXCERIA      | 18        | 25     | 0.6%    |
| ASMT                | 15        | 15     | 0.5%    |
| Apple               | 13        | 14     | 0.43%   |
| Team                | 12        | 13     | 0.4%    |
| Corsair             | 11        | 12     | 0.37%   |
| KingSpec            | 10        | 11     | 0.33%   |
| Intenso             | 8         | 13     | 0.27%   |
| Lexar               | 7         | 8      | 0.23%   |
| Gigabyte Technology | 7         | 8      | 0.23%   |
| USB3.0              | 5         | 5      | 0.17%   |
| POLION              | 5         | 5      | 0.17%   |
| BIWIN               | 5         | 5      | 0.17%   |
| Unknown             | 5         | 5      | 0.17%   |
| Hewlett-Packard     | 4         | 4      | 0.13%   |
| Biostar             | 4         | 4      | 0.13%   |
| Argon               | 4         | 6      | 0.13%   |
| WDC WDS2            | 3         | 3      | 0.1%    |
| sobetter            | 3         | 3      | 0.1%    |
| Phison              | 3         | 3      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 2607      | 4226   | 35.64%  |
| HDD     | 2596      | 4676   | 35.49%  |
| NVMe    | 1725      | 2608   | 23.58%  |
| MMC     | 294       | 422    | 4.02%   |
| Unknown | 93        | 157    | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4175      | 8656   | 64.45%  |
| NVMe | 1724      | 2596   | 26.61%  |
| MMC  | 294       | 422    | 4.54%   |
| SAS  | 285       | 415    | 4.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3384      | 5632   | 64.15%  |
| 0.51-1.0   | 1403      | 2292   | 26.6%   |
| 1.01-2.0   | 275       | 451    | 5.21%   |
| 3.01-4.0   | 80        | 175    | 1.52%   |
| 2.01-3.0   | 71        | 203    | 1.35%   |
| 4.01-10.0  | 52        | 116    | 0.99%   |
| 10.01-20.0 | 10        | 33     | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1621      | 26.89%  |
| 251-500        | 1152      | 19.11%  |
| 1-20           | 740       | 12.28%  |
| 501-1000       | 718       | 11.91%  |
| 51-100         | 489       | 8.11%   |
| 1001-2000      | 425       | 7.05%   |
| 21-50          | 294       | 4.88%   |
| Unknown        | 257       | 4.26%   |
| More than 3000 | 189       | 3.14%   |
| 2001-3000      | 143       | 2.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2558      | 41.24%  |
| 21-50          | 906       | 14.61%  |
| 101-250        | 764       | 12.32%  |
| 51-100         | 675       | 10.88%  |
| 251-500        | 405       | 6.53%   |
| 501-1000       | 331       | 5.34%   |
| Unknown        | 257       | 4.14%   |
| 1001-2000      | 177       | 2.85%   |
| More than 3000 | 64        | 1.03%   |
| 2001-3000      | 63        | 1.02%   |
| 0              | 3         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 16        | 19     | 2.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 11        | 13     | 1.38%   |
| Seagate ST500LT012-9WS142 500GB      | 10        | 30     | 1.26%   |
| Seagate ST3500418AS 500GB            | 10        | 13     | 1.26%   |
| Seagate ST500LT012-1DG142 500GB      | 9         | 12     | 1.13%   |
| Seagate ST500DM002-1BD142 500GB      | 8         | 9      | 1.01%   |
| Seagate ST1000DM003-9YN162 1TB       | 7         | 8      | 0.88%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 0.75%   |
| HGST HTS545050A7E680 500GB           | 6         | 6      | 0.75%   |
| Toshiba MQ01ABD100 1TB               | 5         | 6      | 0.63%   |
| Seagate ST1000LM014-1EJ164 1TB       | 5         | 6      | 0.63%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 0.63%   |
| GOODRAM SSD 120GB                    | 5         | 5      | 0.63%   |
| ASMT 2135 240GB                      | 5         | 5      | 0.63%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 4      | 0.5%    |
| Seagate ST980811AS 80GB              | 4         | 4      | 0.5%    |
| Seagate ST9500420AS 500GB            | 4         | 4      | 0.5%    |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.5%    |
| Seagate ST92505610AS 250GB           | 4         | 4      | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 5      | 0.5%    |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.5%    |
| Seagate ST1000LM014-SSHD-8GB         | 4         | 4      | 0.5%    |
| Seagate ST1000DX001-1CM162 1TB       | 4         | 7      | 0.5%    |
| Kingston SA400S37480G 480GB SSD      | 4         | 4      | 0.5%    |
| Hitachi HTS543225L9SA00 250GB        | 4         | 4      | 0.5%    |
| Hitachi HTS542516K9SA00 160GB        | 4         | 6      | 0.5%    |
| Hitachi HTS541612J9SA00 120GB        | 4         | 5      | 0.5%    |
| A-DATA Technology SU800 512GB SSD    | 4         | 4      | 0.5%    |
| A-DATA Technology SU650 240GB SSD    | 4         | 4      | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 4      | 0.38%   |
| WDC WD5000AVDS-63U7B1 500GB          | 3         | 4      | 0.38%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.38%   |
| WDC WD1600BEVT-75A23T0 160GB         | 3         | 3      | 0.38%   |
| WDC WD15EARS-00Z5B1 1TB              | 3         | 3      | 0.38%   |
| WDC WD10JFCX-68N6GN0 1TB             | 3         | 4      | 0.38%   |
| Toshiba MK3265GSX 320GB              | 3         | 3      | 0.38%   |
| Toshiba MK1637GSX 160GB              | 3         | 3      | 0.38%   |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.38%   |
| Seagate ST9250827AS 250GB            | 3         | 4      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 223       | 299    | 29.15%  |
| WDC                   | 143       | 204    | 18.69%  |
| Hitachi               | 72        | 88     | 9.41%   |
| Samsung Electronics   | 57        | 67     | 7.45%   |
| Toshiba               | 52        | 64     | 6.8%    |
| A-DATA Technology     | 34        | 37     | 4.44%   |
| HGST                  | 20        | 21     | 2.61%   |
| SanDisk               | 18        | 21     | 2.35%   |
| SK hynix              | 16        | 17     | 2.09%   |
| Kingston              | 16        | 17     | 2.09%   |
| Fujitsu               | 10        | 13     | 1.31%   |
| Intel                 | 9         | 9      | 1.18%   |
| Micron Technology     | 8         | 8      | 1.05%   |
| GOODRAM               | 8         | 8      | 1.05%   |
| Crucial               | 7         | 18     | 0.92%   |
| Maxtor                | 6         | 7      | 0.78%   |
| LITEON                | 6         | 6      | 0.78%   |
| ASMT                  | 6         | 7      | 0.78%   |
| China                 | 5         | 6      | 0.65%   |
| SPCC                  | 4         | 4      | 0.52%   |
| LITEONIT              | 4         | 4      | 0.52%   |
| Hewlett-Packard       | 4         | 5      | 0.52%   |
| Apacer                | 4         | 7      | 0.52%   |
| WD MediaMax           | 3         | 4      | 0.39%   |
| Patriot               | 3         | 5      | 0.39%   |
| OCZ                   | 3         | 3      | 0.39%   |
| ASMedia               | 3         | 3      | 0.39%   |
| SSSTC                 | 2         | 2      | 0.26%   |
| Apple                 | 2         | 2      | 0.26%   |
| XPG                   | 1         | 1      | 0.13%   |
| WDC WDS2              | 1         | 1      | 0.13%   |
| SAGE                  | 1         | 1      | 0.13%   |
| RENICE                | 1         | 1      | 0.13%   |
| Realtek Semiconductor | 1         | 1      | 0.13%   |
| POLION                | 1         | 1      | 0.13%   |
| Plextor               | 1         | 1      | 0.13%   |
| Platinet              | 1         | 1      | 0.13%   |
| OWC                   | 1         | 1      | 0.13%   |
| Lexar                 | 1         | 1      | 0.13%   |
| Lenovo                | 1         | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 223       | 299    | 38.92%  |
| WDC                 | 139       | 199    | 24.26%  |
| Hitachi             | 72        | 88     | 12.57%  |
| Toshiba             | 49        | 61     | 8.55%   |
| Samsung Electronics | 43        | 50     | 7.5%    |
| HGST                | 20        | 21     | 3.49%   |
| Fujitsu             | 10        | 13     | 1.75%   |
| Maxtor              | 6         | 7      | 1.05%   |
| WD MediaMax         | 3         | 4      | 0.52%   |
| Hewlett-Packard     | 2         | 3      | 0.35%   |
| SAGE                | 1         | 1      | 0.17%   |
| JMicron Technology  | 1         | 2      | 0.17%   |
| ASMT                | 1         | 2      | 0.17%   |
| ASMedia             | 1         | 1      | 0.17%   |
| Apple               | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 531       | 753    | 73.96%  |
| SSD  | 160       | 192    | 22.28%  |
| NVMe | 27        | 30     | 3.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB         | 1         | 1      | 7.69%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 7.69%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 7.69%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 7.69%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 7.69%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 7.69%   |
| Toshiba DT01ACA100 1TB            | 1         | 2      | 7.69%   |
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 7.69%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.69%   |
| Samsung Electronics HD250HJ 250GB | 1         | 1      | 7.69%   |
| OCZ-AGIL ITY3 64GB SSD            | 1         | 1      | 7.69%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 38.46%  |
| Seagate             | 3         | 3      | 23.08%  |
| Toshiba             | 2         | 3      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| OCZ-AGIL            | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2770      | 5878   | 45.31%  |
| Works    | 2628      | 5222   | 42.98%  |
| Malfunc  | 703       | 975    | 11.5%   |
| Failed   | 13        | 14     | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3754      | 53.43%  |
| AMD                              | 1023      | 14.56%  |
| Samsung Electronics              | 561       | 7.98%   |
| SanDisk                          | 205       | 2.92%   |
| Phison Electronics               | 148       | 2.11%   |
| SK hynix                         | 137       | 1.95%   |
| Kingston Technology Company      | 131       | 1.86%   |
| ADATA Technology                 | 122       | 1.74%   |
| ASMedia Technology               | 115       | 1.64%   |
| JMicron Technology               | 110       | 1.57%   |
| Nvidia                           | 93        | 1.32%   |
| Micron Technology                | 78        | 1.11%   |
| Toshiba America Info Systems     | 71        | 1.01%   |
| KIOXIA                           | 69        | 0.98%   |
| Silicon Motion                   | 59        | 0.84%   |
| Marvell Technology Group         | 55        | 0.78%   |
| Realtek Semiconductor            | 38        | 0.54%   |
| Micron/Crucial Technology        | 31        | 0.44%   |
| Lite-On Technology               | 29        | 0.41%   |
| Shenzhen Longsys Electronics     | 28        | 0.4%    |
| VIA Technologies                 | 24        | 0.34%   |
| LSI Logic / Symbios Logic        | 22        | 0.31%   |
| Union Memory (Shenzhen)          | 18        | 0.26%   |
| MAXIO Technology (Hangzhou)      | 15        | 0.21%   |
| Silicon Integrated Systems [SiS] | 11        | 0.16%   |
| Hewlett-Packard                  | 11        | 0.16%   |
| Solid State Storage Technology   | 10        | 0.14%   |
| Lenovo                           | 10        | 0.14%   |
| Silicon Image                    | 8         | 0.11%   |
| Broadcom / LSI                   | 8         | 0.11%   |
| Apple                            | 5         | 0.07%   |
| O2 Micro                         | 4         | 0.06%   |
| INNOGRIT                         | 4         | 0.06%   |
| Integrated Technology Express    | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| ULi Electronics                  | 2         | 0.03%   |
| Seagate Technology               | 2         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.03%   |
| Adaptec                          | 2         | 0.03%   |
| Tekram Technology                | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 648       | 7.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 272       | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 268       | 3.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 266       | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 234       | 2.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 196       | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 196       | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 187       | 2.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 164       | 1.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 147       | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 137       | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 135       | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 122       | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 120       | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 117       | 1.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 115       | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 113       | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller                            | 111       | 1.35%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 110       | 1.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 106       | 1.29%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 102       | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 100       | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 95        | 1.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 92        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 88        | 1.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 86        | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 86        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 81        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 81        | 0.98%   |
| Intel SSD 660P Series                                                          | 80        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 76        | 0.92%   |
| JMicron JMB363 SATA/IDE Controller                                             | 75        | 0.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 74        | 0.9%    |
| Intel SATA Controller [RAID mode]                                              | 72        | 0.88%   |
| AMD 500 Series Chipset SATA Controller                                         | 71        | 0.86%   |
| Phison E12 NVMe Controller                                                     | 69        | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 68        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 65        | 0.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 57        | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 52        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3963      | 55.82%  |
| NVMe | 1741      | 24.52%  |
| IDE  | 926       | 13.04%  |
| RAID | 436       | 6.14%   |
| SAS  | 19        | 0.27%   |
| SCSI | 14        | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 4140      | 74.86%  |
| AMD          | 1333      | 24.1%   |
| ARM          | 49        | 0.89%   |
| Qualcomm     | 3         | 0.05%   |
| CentaurHauls | 2         | 0.04%   |
| PowerMac11,2 | 1         | 0.02%   |
| PowerBook6,7 | 1         | 0.02%   |
| AppliedMicro | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 54        | 0.97%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 53        | 0.95%   |
| AMD Ryzen 5 3600 6-Core Processor             | 50        | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 49        | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 49        | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 48        | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 44        | 0.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 42        | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 42        | 0.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 40        | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 0.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 37        | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 34        | 0.61%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 34        | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 33        | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 33        | 0.59%   |
| AMD Custom APU 0405                           | 32        | 0.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 31        | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 30        | 0.54%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 30        | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.54%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 30        | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 28        | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 28        | 0.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 28        | 0.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 27        | 0.49%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 27        | 0.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 26        | 0.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 26        | 0.47%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 26        | 0.47%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 25        | 0.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 24        | 0.43%   |
| ARM Processor                                 | 24        | 0.43%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 24        | 0.43%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 24        | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 23        | 0.41%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 23        | 0.41%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 23        | 0.41%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1344      | 24.22%  |
| Intel Core i7           | 820       | 14.78%  |
| Intel Core i3           | 385       | 6.94%   |
| AMD Ryzen 5             | 379       | 6.83%   |
| Other                   | 351       | 6.33%   |
| Intel Core 2 Duo        | 332       | 5.98%   |
| Intel Celeron           | 246       | 4.43%   |
| AMD Ryzen 7             | 240       | 4.33%   |
| Intel Pentium           | 153       | 2.76%   |
| Intel Xeon              | 140       | 2.52%   |
| Intel Atom              | 89        | 1.6%    |
| Intel Pentium Dual-Core | 77        | 1.39%   |
| Intel Core 2 Quad       | 74        | 1.33%   |
| AMD Ryzen 9             | 72        | 1.3%    |
| AMD FX                  | 57        | 1.03%   |
| Intel Core 2            | 44        | 0.79%   |
| AMD A8                  | 42        | 0.76%   |
| AMD A6                  | 42        | 0.76%   |
| AMD Ryzen 3             | 41        | 0.74%   |
| AMD Phenom II X4        | 40        | 0.72%   |
| Intel Pentium Dual      | 39        | 0.7%    |
| AMD Athlon 64 X2        | 35        | 0.63%   |
| AMD A10                 | 34        | 0.61%   |
| AMD Athlon II X2        | 30        | 0.54%   |
| AMD A4                  | 23        | 0.41%   |
| AMD Ryzen 7 PRO         | 22        | 0.4%    |
| AMD Athlon II X4        | 20        | 0.36%   |
| Intel Genuine           | 19        | 0.34%   |
| Intel Core i9           | 19        | 0.34%   |
| AMD Ryzen 5 PRO         | 18        | 0.32%   |
| AMD E                   | 17        | 0.31%   |
| AMD GX                  | 16        | 0.29%   |
| ARM BCM                 | 14        | 0.25%   |
| AMD E1                  | 14        | 0.25%   |
| Intel Celeron M         | 12        | 0.22%   |
| Intel Pentium Silver    | 11        | 0.2%    |
| AMD Ryzen Threadripper  | 11        | 0.2%    |
| AMD Athlon              | 11        | 0.2%    |
| AMD Athlon X2           | 9         | 0.16%   |
| Intel Pentium M         | 8         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2327      | 41.84%  |
| 4       | 1906      | 34.27%  |
| 6       | 550       | 9.89%   |
| 8       | 347       | 6.24%   |
| 1       | 118       | 2.12%   |
| 12      | 100       | 1.8%    |
| Unknown | 73        | 1.31%   |
| 10      | 38        | 0.68%   |
| 16      | 32        | 0.58%   |
| 14      | 27        | 0.49%   |
| 3       | 25        | 0.45%   |
| 20      | 4         | 0.07%   |
| 32      | 3         | 0.05%   |
| 24      | 3         | 0.05%   |
| 192     | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5471      | 98.88%  |
| 2       | 52        | 0.94%   |
| Unknown | 9         | 0.16%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3469      | 62.35%  |
| 1       | 2020      | 36.3%   |
| Unknown | 73        | 1.31%   |
| 8       | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5394      | 97.36%  |
| Unknown        | 87        | 1.57%   |
| 32-bit         | 56        | 1.01%   |
| 64-bit         | 3         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1625      | 28%     |
| 0x306a9    | 304       | 5.24%   |
| 0x206a7    | 294       | 5.07%   |
| 0x306c3    | 258       | 4.45%   |
| 0x1067a    | 230       | 3.96%   |
| 0x906ea    | 138       | 2.38%   |
| 0x506e3    | 122       | 2.1%    |
| 0x40651    | 111       | 1.91%   |
| 0x20655    | 98        | 1.69%   |
| 0x806ec    | 95        | 1.64%   |
| 0x6fd      | 94        | 1.62%   |
| 0x906e9    | 92        | 1.59%   |
| 0x30678    | 92        | 1.59%   |
| 0x306d4    | 91        | 1.57%   |
| 0x806c1    | 87        | 1.5%    |
| 0x806ea    | 84        | 1.45%   |
| 0x406e3    | 82        | 1.41%   |
| 0x10676    | 78        | 1.34%   |
| 0x806e9    | 71        | 1.22%   |
| 0x0800820d | 71        | 1.22%   |
| 0x08701021 | 69        | 1.19%   |
| 0x010000c8 | 66        | 1.14%   |
| 0x0a50000c | 65        | 1.12%   |
| 0x6fb      | 48        | 0.83%   |
| 0x08108109 | 47        | 0.81%   |
| 0x06001119 | 47        | 0.81%   |
| 0x08600106 | 45        | 0.78%   |
| 0x20652    | 34        | 0.59%   |
| 0xa0652    | 33        | 0.57%   |
| 0x6f6      | 33        | 0.57%   |
| 0x08108102 | 30        | 0.52%   |
| 0x806eb    | 29        | 0.5%    |
| 0x406c4    | 29        | 0.5%    |
| 0x08701013 | 28        | 0.48%   |
| 0xa0653    | 27        | 0.47%   |
| 0x906ed    | 27        | 0.47%   |
| 0x06000852 | 27        | 0.47%   |
| 0x706e5    | 25        | 0.43%   |
| 0x0a50000d | 25        | 0.43%   |
| 0x08001138 | 23        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 757       | 13.65%  |
| Haswell          | 511       | 9.21%   |
| IvyBridge        | 412       | 7.43%   |
| SandyBridge      | 394       | 7.1%    |
| Penryn           | 376       | 6.78%   |
| Skylake          | 298       | 5.37%   |
| Zen 2            | 254       | 4.58%   |
| Core             | 248       | 4.47%   |
| Unknown          | 220       | 3.97%   |
| Zen+             | 196       | 3.53%   |
| Westmere         | 190       | 3.43%   |
| Silvermont       | 183       | 3.3%    |
| Zen 3            | 165       | 2.97%   |
| Broadwell        | 138       | 2.49%   |
| K10              | 131       | 2.36%   |
| TigerLake        | 127       | 2.29%   |
| Piledriver       | 104       | 1.87%   |
| Zen              | 98        | 1.77%   |
| CometLake        | 96        | 1.73%   |
| Alderlake Hybrid | 91        | 1.64%   |
| K8 Hammer        | 67        | 1.21%   |
| IceLake          | 64        | 1.15%   |
| Bobcat           | 47        | 0.85%   |
| Goldmont plus    | 46        | 0.83%   |
| Nehalem          | 45        | 0.81%   |
| Bonnell          | 38        | 0.69%   |
| P6               | 34        | 0.61%   |
| Excavator        | 34        | 0.61%   |
| Jaguar           | 32        | 0.58%   |
| Goldmont         | 31        | 0.56%   |
| Steamroller      | 25        | 0.45%   |
| Puma             | 21        | 0.38%   |
| NetBurst         | 20        | 0.36%   |
| K10 Llano        | 19        | 0.34%   |
| K8 & K10 hybrid  | 16        | 0.29%   |
| Bulldozer        | 13        | 0.23%   |
| Tremont          | 4         | 0.07%   |
| Gracemont        | 2         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3129      | 47.37%  |
| Nvidia                           | 1942      | 29.4%   |
| AMD                              | 1493      | 22.6%   |
| Matrox Electronics Systems       | 19        | 0.29%   |
| ASPEED Technology                | 8         | 0.12%   |
| VIA Technologies                 | 7         | 0.11%   |
| Silicon Integrated Systems [SiS] | 6         | 0.09%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 313       | 4.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 259       | 3.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 146       | 2.13%   |
| Intel UHD Graphics 620                                                                   | 124       | 1.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 120       | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 120       | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 116       | 1.69%   |
| Intel HD Graphics 530                                                                    | 115       | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 115       | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 114       | 1.66%   |
| Intel HD Graphics 5500                                                                   | 113       | 1.65%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 112       | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 111       | 1.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 111       | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 108       | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 108       | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 101       | 1.47%   |
| Intel HD Graphics 620                                                                    | 96        | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 92        | 1.34%   |
| Intel HD Graphics 630                                                                    | 81        | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 79        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 68        | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 62        | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 59        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 58        | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 52        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 51        | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 49        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 48        | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 45        | 0.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 45        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 44        | 0.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 41        | 0.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 40        | 0.58%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 37        | 0.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 36        | 0.52%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 33        | 0.48%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 33        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2142      | 38.28%  |
| 1 x AMD                  | 1094      | 19.55%  |
| 1 x Nvidia               | 1083      | 19.36%  |
| Intel + Nvidia           | 722       | 12.9%   |
| Intel + AMD              | 197       | 3.52%   |
| AMD + Nvidia             | 123       | 2.2%    |
| 2 x AMD                  | 83        | 1.48%   |
| Other                    | 61        | 1.09%   |
| 2 x Intel                | 36        | 0.64%   |
| 1 x Matrox               | 19        | 0.34%   |
| 2 x Nvidia               | 8         | 0.14%   |
| 1 x VIA                  | 7         | 0.13%   |
| 1 x SiS                  | 6         | 0.11%   |
| 1 x ASPEED               | 5         | 0.09%   |
| Nvidia + ASPEED          | 3         | 0.05%   |
| 3 x AMD                  | 2         | 0.04%   |
| 2 x Intel + 1 x Nvidia   | 2         | 0.04%   |
| 1 x S3 Graphics          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4456      | 78.87%  |
| Proprietary | 959       | 16.97%  |
| Unknown     | 235       | 4.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3008      | 52.37%  |
| 1.01-2.0   | 726       | 12.64%  |
| 0.01-0.5   | 701       | 12.2%   |
| 0.51-1.0   | 482       | 8.39%   |
| 3.01-4.0   | 376       | 6.55%   |
| 7.01-8.0   | 215       | 3.74%   |
| 5.01-6.0   | 139       | 2.42%   |
| 8.01-16.0  | 61        | 1.06%   |
| 2.01-3.0   | 26        | 0.45%   |
| 16.01-24.0 | 9         | 0.16%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 844       | 13.71%  |
| AU Optronics            | 701       | 11.39%  |
| LG Display              | 586       | 9.52%   |
| BOE                     | 481       | 7.82%   |
| Chimei Innolux          | 428       | 6.95%   |
| Dell                    | 372       | 6.04%   |
| Goldstar                | 343       | 5.57%   |
| Iiyama                  | 214       | 3.48%   |
| Philips                 | 200       | 3.25%   |
| Lenovo                  | 152       | 2.47%   |
| Hewlett-Packard         | 152       | 2.47%   |
| BenQ                    | 150       | 2.44%   |
| Acer                    | 148       | 2.4%    |
| Chi Mei Optoelectronics | 125       | 2.03%   |
| AOC                     | 124       | 2.01%   |
| NEC Computers           | 91        | 1.48%   |
| Eizo                    | 91        | 1.48%   |
| Ancor Communications    | 74        | 1.2%    |
| Sharp                   | 68        | 1.1%    |
| PANDA                   | 55        | 0.89%   |
| LG Philips              | 49        | 0.8%    |
| Sony                    | 45        | 0.73%   |
| InfoVision              | 43        | 0.7%    |
| Fujitsu Siemens         | 41        | 0.67%   |
| Apple                   | 40        | 0.65%   |
| LG Electronics          | 36        | 0.58%   |
| ASUSTek Computer        | 35        | 0.57%   |
| Valve                   | 26        | 0.42%   |
| Unknown                 | 25        | 0.41%   |
| HannStar                | 20        | 0.32%   |
| Toshiba                 | 19        | 0.31%   |
| MSI                     | 18        | 0.29%   |
| Idek Iiyama             | 18        | 0.29%   |
| CSO                     | 17        | 0.28%   |
| CPT                     | 16        | 0.26%   |
| Panasonic               | 15        | 0.24%   |
| ViewSonic               | 14        | 0.23%   |
| Gateway                 | 14        | 0.23%   |
| Gigabyte Technology     | 13        | 0.21%   |
| Belinea                 | 13        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 34        | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 33        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 31        | 0.48%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 29        | 0.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.45%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 27        | 0.42%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 22        | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 22        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 22        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 21        | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 21        | 0.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 20        | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 19        | 0.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 18        | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 18        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 18        | 0.28%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 17        | 0.27%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 17        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 17        | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 16        | 0.25%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 16        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 15        | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 15        | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 14        | 0.22%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.22%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 14        | 0.22%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 14        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 14        | 0.22%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                     | 13        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 13        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 13        | 0.2%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.2%    |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 13        | 0.2%    |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 12        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 12        | 0.19%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 12        | 0.19%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 12        | 0.19%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 12        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2504      | 42.98%  |
| 1366x768 (WXGA)    | 982       | 16.86%  |
| 2560x1440 (QHD)    | 284       | 4.87%   |
| 3840x2160 (4K)     | 269       | 4.62%   |
| 1280x1024 (SXGA)   | 247       | 4.24%   |
| 1600x900 (HD+)     | 239       | 4.1%    |
| 1920x1200 (WUXGA)  | 211       | 3.62%   |
| 1280x800 (WXGA)    | 208       | 3.57%   |
| 1680x1050 (WSXGA+) | 204       | 3.5%    |
| 1440x900 (WXGA+)   | 158       | 2.71%   |
| 3440x1440          | 63        | 1.08%   |
| Unknown            | 57        | 0.98%   |
| 2560x1080          | 43        | 0.74%   |
| 2560x1600          | 38        | 0.65%   |
| 800x1280           | 27        | 0.46%   |
| 1024x600           | 27        | 0.46%   |
| 1360x768           | 26        | 0.45%   |
| 1600x1200          | 23        | 0.39%   |
| 1024x768 (XGA)     | 23        | 0.39%   |
| 3840x1080          | 19        | 0.33%   |
| 2880x1800          | 15        | 0.26%   |
| 2160x1440          | 14        | 0.24%   |
| 1920x540           | 13        | 0.22%   |
| 3840x2400          | 11        | 0.19%   |
| 2288x1287          | 11        | 0.19%   |
| 1280x720 (HD)      | 8         | 0.14%   |
| 3200x1800 (QHD+)   | 7         | 0.12%   |
| 2048x1152          | 5         | 0.09%   |
| 1400x1050          | 5         | 0.09%   |
| 1280x768           | 5         | 0.09%   |
| 5120x1440          | 4         | 0.07%   |
| 3840x1600          | 4         | 0.07%   |
| 3840x1200          | 4         | 0.07%   |
| 3200x2000          | 4         | 0.07%   |
| 2736x1824          | 4         | 0.07%   |
| 1680x945           | 4         | 0.07%   |
| 1280x960           | 4         | 0.07%   |
| 4480x1440          | 3         | 0.05%   |
| 3456x2160          | 3         | 0.05%   |
| 3286x1080          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1651      | 26.88%  |
| 24      | 500       | 8.14%   |
| 13      | 478       | 7.78%   |
| 14      | 447       | 7.28%   |
| 23      | 398       | 6.48%   |
| 27      | 384       | 6.25%   |
| 17      | 372       | 6.06%   |
| 21      | 356       | 5.8%    |
| Unknown | 279       | 4.54%   |
| 19      | 214       | 3.48%   |
| 12      | 128       | 2.08%   |
| 22      | 123       | 2%      |
| 34      | 100       | 1.63%   |
| 31      | 90        | 1.47%   |
| 18      | 86        | 1.4%    |
| 11      | 60        | 0.98%   |
| 20      | 54        | 0.88%   |
| 16      | 47        | 0.77%   |
| 25      | 35        | 0.57%   |
| 10      | 33        | 0.54%   |
| 84      | 31        | 0.5%    |
| 72      | 31        | 0.5%    |
| 32      | 27        | 0.44%   |
| 40      | 26        | 0.42%   |
| 7       | 24        | 0.39%   |
| 54      | 22        | 0.36%   |
| 65      | 15        | 0.24%   |
| 48      | 15        | 0.24%   |
| 46      | 11        | 0.18%   |
| 28      | 11        | 0.18%   |
| 142     | 10        | 0.16%   |
| 43      | 10        | 0.16%   |
| 33      | 10        | 0.16%   |
| 42      | 9         | 0.15%   |
| 26      | 9         | 0.15%   |
| 37      | 7         | 0.11%   |
| 29      | 5         | 0.08%   |
| 3       | 5         | 0.08%   |
| 49      | 4         | 0.07%   |
| 39      | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2426      | 40.21%  |
| 501-600        | 1219      | 20.2%   |
| 401-500        | 684       | 11.34%  |
| 351-400        | 474       | 7.86%   |
| 201-300        | 437       | 7.24%   |
| Unknown        | 279       | 4.62%   |
| 701-800        | 137       | 2.27%   |
| 601-700        | 135       | 2.24%   |
| 1001-1500      | 82        | 1.36%   |
| 1501-2000      | 63        | 1.04%   |
| 801-900        | 42        | 0.7%    |
| 1-100          | 28        | 0.46%   |
| 901-1000       | 17        | 0.28%   |
| More than 2000 | 10        | 0.17%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3945      | 71.36%  |
| 16/10   | 817       | 14.78%  |
| Unknown | 242       | 4.38%   |
| 5/4     | 236       | 4.27%   |
| 21/9    | 108       | 1.95%   |
| 3/2     | 64        | 1.16%   |
| 4/3     | 58        | 1.05%   |
| 0.67    | 22        | 0.4%    |
| 32/9    | 11        | 0.2%    |
| 1.00    | 10        | 0.18%   |
| 6/5     | 9         | 0.16%   |
| 0.62    | 3         | 0.05%   |
| 0.56    | 2         | 0.04%   |
| 3.20    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1643      | 26.98%  |
| 201-250        | 1070      | 17.57%  |
| 81-90          | 737       | 12.1%   |
| 301-350        | 391       | 6.42%   |
| 151-200        | 348       | 5.71%   |
| Unknown        | 279       | 4.58%   |
| 251-300        | 244       | 4.01%   |
| 351-500        | 238       | 3.91%   |
| 121-130        | 221       | 3.63%   |
| 71-80          | 184       | 3.02%   |
| 141-150        | 167       | 2.74%   |
| More than 1000 | 136       | 2.23%   |
| 61-70          | 119       | 1.95%   |
| 501-1000       | 76        | 1.25%   |
| 51-60          | 60        | 0.99%   |
| 131-140        | 50        | 0.82%   |
| 111-120        | 41        | 0.67%   |
| 41-50          | 33        | 0.54%   |
| 1-40           | 29        | 0.48%   |
| 91-100         | 24        | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2020      | 34.13%  |
| 121-160       | 1640      | 27.71%  |
| 101-120       | 1486      | 25.11%  |
| 161-240       | 284       | 4.8%    |
| Unknown       | 279       | 4.71%   |
| 1-50          | 125       | 2.11%   |
| More than 240 | 84        | 1.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4477      | 78.53%  |
| 2     | 851       | 14.93%  |
| 0     | 228       | 4%      |
| 3     | 126       | 2.21%   |
| 4     | 16        | 0.28%   |
| 6     | 2         | 0.04%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2838      | 33.29%  |
| Intel                                  | 2713      | 31.82%  |
| Qualcomm Atheros                       | 985       | 11.55%  |
| Broadcom                               | 483       | 5.67%   |
| Broadcom Limited                       | 137       | 1.61%   |
| TP-Link                                | 133       | 1.56%   |
| MediaTek                               | 115       | 1.35%   |
| Marvell Technology Group               | 104       | 1.22%   |
| Huawei Technologies                    | 90        | 1.06%   |
| Dell                                   | 89        | 1.04%   |
| Ralink                                 | 77        | 0.9%    |
| Ralink Technology                      | 74        | 0.87%   |
| Nvidia                                 | 65        | 0.76%   |
| Qualcomm Atheros Communications        | 61        | 0.72%   |
| Samsung Electronics                    | 46        | 0.54%   |
| Xiaomi                                 | 44        | 0.52%   |
| Microsoft                              | 40        | 0.47%   |
| Ericsson Business Mobile Networks      | 34        | 0.4%    |
| ASUSTek Computer                       | 30        | 0.35%   |
| Hewlett-Packard                        | 28        | 0.33%   |
| ASIX Electronics                       | 26        | 0.3%    |
| Sierra Wireless                        | 21        | 0.25%   |
| Lenovo                                 | 18        | 0.21%   |
| Qualcomm                               | 17        | 0.2%    |
| JMicron Technology                     | 17        | 0.2%    |
| Edimax Technology                      | 15        | 0.18%   |
| DisplayLink                            | 14        | 0.16%   |
| VIA Technologies                       | 12        | 0.14%   |
| NetGear                                | 12        | 0.14%   |
| Motorola PCS                           | 12        | 0.14%   |
| Aquantia                               | 12        | 0.14%   |
| Fibocom                                | 11        | 0.13%   |
| ZTE WCDMA Technologies MSM             | 9         | 0.11%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.11%   |
| D-Link                                 | 9         | 0.11%   |
| OPPO Electronics                       | 7         | 0.08%   |
| Microchip Technology                   | 7         | 0.08%   |
| HTC (High Tech Computer)               | 6         | 0.07%   |
| Texas Instruments                      | 5         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2021      | 20.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 288       | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 271       | 2.71%   |
| Intel Wi-Fi 6 AX200                                                    | 189       | 1.89%   |
| Intel Wireless 8265 / 8275                                             | 163       | 1.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 147       | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 133       | 1.33%   |
| Intel Wireless 7260                                                    | 129       | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 125       | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 119       | 1.19%   |
| Intel Wireless 8260                                                    | 112       | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 111       | 1.11%   |
| Realtek RTL8125 2.5GbE Controller                                      | 111       | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 107       | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 101       | 1.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 99        | 0.99%   |
| Intel Wi-Fi 6 AX201                                                    | 99        | 0.99%   |
| Intel Ethernet Connection I217-LM                                      | 94        | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 93        | 0.93%   |
| Intel Wireless 7265                                                    | 92        | 0.92%   |
| Intel I211 Gigabit Network Connection                                  | 89        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 77        | 0.77%   |
| Intel Wireless 3165                                                    | 76        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 72        | 0.72%   |
| Intel Wireless 3160                                                    | 72        | 0.72%   |
| Intel Ethernet Connection (2) I219-V                                   | 70        | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 66        | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 64        | 0.64%   |
| Intel 82567LM Gigabit Network Connection                               | 59        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                  | 58        | 0.58%   |
| Intel 82579V Gigabit Network Connection                                | 58        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 57        | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 57        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                          | 57        | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 55        | 0.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 55        | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 54        | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 53        | 0.53%   |
| Intel Centrino Ultimate-N 6300                                         | 53        | 0.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 51        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2091      | 46.57%  |
| Qualcomm Atheros                  | 750       | 16.7%   |
| Realtek Semiconductor             | 595       | 13.25%  |
| Broadcom                          | 295       | 6.57%   |
| TP-Link                           | 128       | 2.85%   |
| MediaTek                          | 109       | 2.43%   |
| Ralink                            | 77        | 1.71%   |
| Ralink Technology                 | 74        | 1.65%   |
| Broadcom Limited                  | 65        | 1.45%   |
| Qualcomm Atheros Communications   | 61        | 1.36%   |
| Dell                              | 53        | 1.18%   |
| Microsoft                         | 38        | 0.85%   |
| ASUSTek Computer                  | 30        | 0.67%   |
| Sierra Wireless                   | 21        | 0.47%   |
| Edimax Technology                 | 15        | 0.33%   |
| Fibocom                           | 11        | 0.24%   |
| Ericsson Business Mobile Networks | 11        | 0.24%   |
| Qualcomm                          | 9         | 0.2%    |
| D-Link                            | 9         | 0.2%    |
| NetGear                           | 8         | 0.18%   |
| Hewlett-Packard                   | 8         | 0.18%   |
| Sagem                             | 4         | 0.09%   |
| Marvell Technology Group          | 4         | 0.09%   |
| ZyXEL Communications              | 3         | 0.07%   |
| D-Link System                     | 3         | 0.07%   |
| Belkin Components                 | 3         | 0.07%   |
| ZyDAS                             | 2         | 0.04%   |
| Linksys                           | 2         | 0.04%   |
| Unknown                           | 2         | 0.04%   |
| Z-Com                             | 1         | 0.02%   |
| Wacom                             | 1         | 0.02%   |
| Tenda                             | 1         | 0.02%   |
| Sweex                             | 1         | 0.02%   |
| Ovislink                          | 1         | 0.02%   |
| Mercucys                          | 1         | 0.02%   |
| IMC Networks                      | 1         | 0.02%   |
| AVM                               | 1         | 0.02%   |
| Accton Technology                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 189       | 4.2%    |
| Intel Wireless 8265 / 8275                                              | 163       | 3.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 147       | 3.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 133       | 2.95%   |
| Intel Wireless 7260                                                     | 129       | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 125       | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 119       | 2.64%   |
| Intel Wireless 8260                                                     | 112       | 2.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 107       | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 101       | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 99        | 2.2%    |
| Intel Wi-Fi 6 AX201                                                     | 99        | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 93        | 2.06%   |
| Intel Wireless 7265                                                     | 92        | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 77        | 1.71%   |
| Intel Wireless 3165                                                     | 76        | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 1.6%    |
| Intel Wireless 3160                                                     | 72        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 66        | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 64        | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 57        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 57        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 55        | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 55        | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 54        | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 53        | 1.18%   |
| Intel Centrino Ultimate-N 6300                                          | 53        | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 51        | 1.13%   |
| Qualcomm Atheros AR9271 802.11n                                         | 47        | 1.04%   |
| Intel WiFi Link 5100                                                    | 47        | 1.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 46        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 46        | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 41        | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 40        | 0.89%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 38        | 0.84%   |
| Intel Centrino Advanced-N 6200                                          | 37        | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                         | 34        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2591      | 49.35%  |
| Intel                                  | 1477      | 28.13%  |
| Qualcomm Atheros                       | 346       | 6.59%   |
| Broadcom                               | 236       | 4.5%    |
| Marvell Technology Group               | 101       | 1.92%   |
| Broadcom Limited                       | 73        | 1.39%   |
| Nvidia                                 | 65        | 1.24%   |
| Huawei Technologies                    | 60        | 1.14%   |
| Samsung Electronics                    | 44        | 0.84%   |
| Xiaomi                                 | 43        | 0.82%   |
| ASIX Electronics                       | 26        | 0.5%    |
| Lenovo                                 | 18        | 0.34%   |
| JMicron Technology                     | 17        | 0.32%   |
| DisplayLink                            | 14        | 0.27%   |
| VIA Technologies                       | 12        | 0.23%   |
| Aquantia                               | 12        | 0.23%   |
| Motorola PCS                           | 11        | 0.21%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.17%   |
| ZTE WCDMA Technologies MSM             | 8         | 0.15%   |
| Qualcomm                               | 8         | 0.15%   |
| OPPO Electronics                       | 7         | 0.13%   |
| Microchip Technology                   | 7         | 0.13%   |
| TP-Link                                | 6         | 0.11%   |
| HTC (High Tech Computer)               | 6         | 0.11%   |
| Attansic Technology                    | 5         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 4         | 0.08%   |
| NetGear                                | 4         | 0.08%   |
| MediaTek                               | 4         | 0.08%   |
| ICS Advent                             | 4         | 0.08%   |
| Hewlett-Packard                        | 4         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.06%   |
| NetXen Incorporated                    | 3         | 0.06%   |
| Google                                 | 3         | 0.06%   |
| Apple                                  | 3         | 0.06%   |
| Research In Motion                     | 2         | 0.04%   |
| QLogic                                 | 2         | 0.04%   |
| 3Com                                   | 2         | 0.04%   |
| QinHeng Electronics                    | 1         | 0.02%   |
| Mellanox Technologies                  | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2021      | 37.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 288       | 5.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 271       | 5.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 111       | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                      | 111       | 2.08%   |
| Intel Ethernet Connection I217-LM                                      | 94        | 1.76%   |
| Intel I211 Gigabit Network Connection                                  | 89        | 1.67%   |
| Intel Ethernet Connection (2) I219-V                                   | 70        | 1.31%   |
| Intel 82567LM Gigabit Network Connection                               | 59        | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                  | 58        | 1.09%   |
| Intel 82579V Gigabit Network Connection                                | 58        | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 50        | 0.94%   |
| Intel Ethernet Connection I218-LM                                      | 50        | 0.94%   |
| Huawei E353/E3131                                                      | 48        | 0.9%    |
| Intel 82577LM Gigabit Network Connection                               | 46        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                                   | 43        | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 41        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 41        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                  | 40        | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 40        | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 37        | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 37        | 0.69%   |
| Intel Ethernet Controller I225-V                                       | 35        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                  | 35        | 0.66%   |
| Intel Ethernet Connection (6) I219-V                                   | 35        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                  | 35        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 32        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 30        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 30        | 0.56%   |
| Nvidia MCP61 Ethernet                                                  | 30        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 29        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 28        | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                   | 28        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 27        | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 24        | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 23        | 0.43%   |
| Intel Ethernet Connection I217-V                                       | 23        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                                   | 23        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 22        | 0.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 22        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4919      | 53.04%  |
| WiFi     | 4200      | 45.29%  |
| Modem    | 138       | 1.49%   |
| Unknown  | 17        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3226      | 57.26%  |
| Ethernet | 2406      | 42.71%  |
| Modem    | 1         | 0.02%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3211      | 57.77%  |
| 1     | 2124      | 38.22%  |
| 0     | 119       | 2.14%   |
| 3     | 70        | 1.26%   |
| 4     | 17        | 0.31%   |
| 5     | 6         | 0.11%   |
| 6     | 5         | 0.09%   |
| 8     | 2         | 0.04%   |
| 17    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5143      | 92.09%  |
| Yes  | 442       | 7.91%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1503      | 45.96%  |
| Qualcomm Atheros Communications | 283       | 8.65%   |
| Realtek Semiconductor           | 231       | 7.06%   |
| Cambridge Silicon Radio         | 205       | 6.27%   |
| Broadcom                        | 199       | 6.09%   |
| IMC Networks                    | 159       | 4.86%   |
| Foxconn / Hon Hai               | 104       | 3.18%   |
| ASUSTek Computer                | 102       | 3.12%   |
| Dell                            | 100       | 3.06%   |
| Lite-On Technology              | 81        | 2.48%   |
| Hewlett-Packard                 | 67        | 2.05%   |
| Apple                           | 47        | 1.44%   |
| Toshiba                         | 33        | 1.01%   |
| Ralink                          | 21        | 0.64%   |
| Realtek                         | 19        | 0.58%   |
| Foxconn International           | 19        | 0.58%   |
| MediaTek                        | 18        | 0.55%   |
| TP-Link                         | 17        | 0.52%   |
| Alps Electric                   | 8         | 0.24%   |
| Integrated System Solution      | 7         | 0.21%   |
| Edimax Technology               | 7         | 0.21%   |
| Chicony Electronics             | 7         | 0.21%   |
| Taiyo Yuden                     | 5         | 0.15%   |
| USI                             | 3         | 0.09%   |
| Ralink Technology               | 3         | 0.09%   |
| Conwise Technology              | 3         | 0.09%   |
| Unknown                         | 3         | 0.09%   |
| Opticis                         | 2         | 0.06%   |
| Micro Star International        | 2         | 0.06%   |
| Marvell Semiconductor           | 2         | 0.06%   |
| Logitech                        | 2         | 0.06%   |
| Belkin Components               | 2         | 0.06%   |
| Askey Computer                  | 2         | 0.06%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| AboCom Systems                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 634       | 19.37%  |
| Intel AX201 Bluetooth                               | 220       | 6.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 205       | 6.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 189       | 5.77%   |
| Intel AX200 Bluetooth                               | 182       | 5.56%   |
| Realtek Bluetooth Radio                             | 159       | 4.86%   |
| Qualcomm Atheros  Bluetooth Device                  | 120       | 3.67%   |
| Intel Bluetooth Device                              | 84        | 2.57%   |
| IMC Networks Bluetooth Radio                        | 70        | 2.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 66        | 2.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 64        | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 56        | 1.71%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 55        | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 51        | 1.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 45        | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 41        | 1.25%   |
| Broadcom BCM2045B (BDC-2.1)                         | 41        | 1.25%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 37        | 1.13%   |
| IMC Networks Wireless_Device                        | 36        | 1.1%    |
| Foxconn / Hon Hai Wireless_Device                   | 34        | 1.04%   |
| Dell BCM20702A0 Bluetooth Module                    | 34        | 1.04%   |
| Intel AX210 Bluetooth                               | 32        | 0.98%   |
| Dell DW375 Bluetooth Module                         | 30        | 0.92%   |
| HP Broadcom 2070 Bluetooth Combo                    | 29        | 0.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 25        | 0.76%   |
| Lite-On Bluetooth Device                            | 24        | 0.73%   |
| IMC Networks Bluetooth Device                       | 24        | 0.73%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.64%   |
| Apple Bluetooth Host Controller                     | 21        | 0.64%   |
| Realtek RTL8723B Bluetooth                          | 20        | 0.61%   |
| Broadcom BCM2070 Bluetooth Device                   | 20        | 0.61%   |
| Realtek Bluetooth Radio                             | 19        | 0.58%   |
| Foxconn International BCM43142A0 Bluetooth module   | 19        | 0.58%   |
| TP-Link UB500 Adapter                               | 17        | 0.52%   |
| MediaTek Wireless_Device                            | 17        | 0.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.52%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 17        | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 15        | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3978      | 52.01%  |
| AMD                                  | 1540      | 20.14%  |
| Nvidia                               | 1351      | 17.66%  |
| C-Media Electronics                  | 111       | 1.45%   |
| Creative Labs                        | 95        | 1.24%   |
| Creative Technology                  | 55        | 0.72%   |
| Logitech                             | 37        | 0.48%   |
| Realtek Semiconductor                | 28        | 0.37%   |
| JMTek                                | 26        | 0.34%   |
| VIA Technologies                     | 24        | 0.31%   |
| Texas Instruments                    | 22        | 0.29%   |
| SteelSeries ApS                      | 22        | 0.29%   |
| Lenovo                               | 21        | 0.27%   |
| GN Netcom                            | 21        | 0.27%   |
| Plantronics                          | 19        | 0.25%   |
| Kingston Technology                  | 17        | 0.22%   |
| Generalplus Technology               | 15        | 0.2%    |
| ASUSTek Computer                     | 14        | 0.18%   |
| GYROCOM C&C                          | 13        | 0.17%   |
| Dell                                 | 13        | 0.17%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.14%   |
| Hewlett-Packard                      | 11        | 0.14%   |
| SAVITECH                             | 10        | 0.13%   |
| Sony                                 | 8         | 0.1%    |
| BEHRINGER International              | 8         | 0.1%    |
| Razer USA                            | 7         | 0.09%   |
| M-Audio                              | 7         | 0.09%   |
| Focusrite-Novation                   | 7         | 0.09%   |
| Samson Technologies                  | 6         | 0.08%   |
| AOKEO                                | 6         | 0.08%   |
| Valve Software                       | 5         | 0.07%   |
| Trust                                | 5         | 0.07%   |
| RODE Microphones                     | 5         | 0.07%   |
| Micro Star International             | 5         | 0.07%   |
| Corsair                              | 5         | 0.07%   |
| AudioQuest                           | 5         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.05%   |
| Stadium USB microphone               | 4         | 0.05%   |
| KTMicro                              | 4         | 0.05%   |
| SM900 Microphon                      | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 441       | 4.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 430       | 4.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 350       | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 347       | 3.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 288       | 3.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 237       | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 233       | 2.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 212       | 2.34%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 210       | 2.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 192       | 2.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 190       | 2.1%    |
| AMD Starship/Matisse HD Audio Controller                                   | 188       | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 183       | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 181       | 2%      |
| AMD FCH Azalia Controller                                                  | 171       | 1.89%   |
| Intel 8 Series HD Audio Controller                                         | 152       | 1.68%   |
| Intel Haswell-ULT HD Audio Controller                                      | 150       | 1.66%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 148       | 1.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 132       | 1.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 132       | 1.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 132       | 1.46%   |
| Intel Broadwell-U Audio Controller                                         | 129       | 1.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 127       | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 126       | 1.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 112       | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                              | 106       | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 97        | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 93        | 1.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 85        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 81        | 0.89%   |
| Intel 200 Series PCH HD Audio                                              | 79        | 0.87%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 78        | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 76        | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 76        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 71        | 0.78%   |
| Intel CM238 HD Audio Controller                                            | 67        | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                   | 66        | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 64        | 0.71%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 64        | 0.71%   |
| Nvidia High Definition Audio Controller                                    | 61        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 888       | 21.16%  |
| SK hynix                     | 697       | 16.61%  |
| Kingston                     | 549       | 13.08%  |
| Unknown                      | 460       | 10.96%  |
| Micron Technology            | 358       | 8.53%   |
| GOODRAM                      | 259       | 6.17%   |
| Crucial                      | 181       | 4.31%   |
| G.Skill                      | 125       | 2.98%   |
| Corsair                      | 100       | 2.38%   |
| A-DATA Technology            | 86        | 2.05%   |
| Ramaxel Technology           | 80        | 1.91%   |
| Nanya Technology             | 68        | 1.62%   |
| Patriot                      | 60        | 1.43%   |
| Elpida                       | 60        | 1.43%   |
| Unknown                      | 33        | 0.79%   |
| Unknown (ABCD)               | 22        | 0.52%   |
| Wilk                         | 20        | 0.48%   |
| Qimonda                      | 13        | 0.31%   |
| Apacer                       | 13        | 0.31%   |
| Wilk Elektronik              | 10        | 0.24%   |
| GeIL                         | 10        | 0.24%   |
| ASint Technology             | 9         | 0.21%   |
| Silicon Power                | 7         | 0.17%   |
| Patriot Memory (PDP Systems) | 6         | 0.14%   |
| 48spaces                     | 6         | 0.14%   |
| Transcend                    | 5         | 0.12%   |
| Unifosa                      | 4         | 0.1%    |
| Team                         | 4         | 0.1%    |
| Lexar                        | 4         | 0.1%    |
| ff                           | 4         | 0.1%    |
| fef5                         | 4         | 0.1%    |
| 4ea5                         | 4         | 0.1%    |
| Toshiba                      | 3         | 0.07%   |
| OCZ                          | 3         | 0.07%   |
| Unknown (0x0E9D)             | 2         | 0.05%   |
| SHARETRONIC                  | 2         | 0.05%   |
| PUSKILL                      | 2         | 0.05%   |
| PNY                          | 2         | 0.05%   |
| KingFast                     | 2         | 0.05%   |
| ChangXin Memory              | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 44        | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 41        | 0.89%   |
| Samsung RAM M471B5173BH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 37        | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 34        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 33        | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 33        | 0.72%   |
| Unknown                                                             | 33        | 0.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 32        | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 30        | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 30        | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 30        | 0.65%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 29        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 28        | 0.61%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s             | 28        | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 27        | 0.59%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s             | 25        | 0.55%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 22        | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 20        | 0.44%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 19        | 0.41%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s               | 19        | 0.41%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                              | 18        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 18        | 0.39%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 18        | 0.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 18        | 0.39%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 17        | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 17        | 0.37%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s                 | 17        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 17        | 0.37%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 16        | 0.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 16        | 0.35%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 16        | 0.35%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s               | 16        | 0.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 15        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 15        | 0.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 15        | 0.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 15        | 0.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 15        | 0.33%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s              | 15        | 0.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 14        | 0.31%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 14        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1427      | 40.2%   |
| DDR3    | 1292      | 36.39%  |
| DDR2    | 257       | 7.24%   |
| Unknown | 160       | 4.51%   |
| SDRAM   | 154       | 4.34%   |
| LPDDR4  | 89        | 2.51%   |
| DDR5    | 56        | 1.58%   |
| LPDDR3  | 47        | 1.32%   |
| DDR     | 35        | 0.99%   |
| LPDDR5  | 25        | 0.7%    |
| DRAM    | 8         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 2092      | 60.03%  |
| DIMM            | 1227      | 35.21%  |
| Row Of Chips    | 134       | 3.85%   |
| Unknown         | 15        | 0.43%   |
| Chip            | 13        | 0.37%   |
| RIMM            | 2         | 0.06%   |
| Proprietary Car | 1         | 0.03%   |
| FB-DIMM         | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1262      | 32.23%  |
| 4096    | 1052      | 26.87%  |
| 2048    | 641       | 16.37%  |
| 16384   | 566       | 14.46%  |
| 1024    | 223       | 5.7%    |
| 32768   | 130       | 3.32%   |
| 512     | 29        | 0.74%   |
| Unknown | 4         | 0.1%    |
| 256     | 3         | 0.08%   |
| 131072  | 2         | 0.05%   |
| 1536    | 2         | 0.05%   |
| 64      | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 875       | 22.47%  |
| 3200    | 491       | 12.61%  |
| 2667    | 472       | 12.12%  |
| 1333    | 252       | 6.47%   |
| 2400    | 231       | 5.93%   |
| 1334    | 162       | 4.16%   |
| 2133    | 153       | 3.93%   |
| 667     | 148       | 3.8%    |
| 800     | 135       | 3.47%   |
| 3600    | 98        | 2.52%   |
| Unknown | 83        | 2.13%   |
| 1067    | 64        | 1.64%   |
| 1867    | 54        | 1.39%   |
| 4199    | 50        | 1.28%   |
| 4800    | 33        | 0.85%   |
| 533     | 33        | 0.85%   |
| 3000    | 32        | 0.82%   |
| 2048    | 31        | 0.8%    |
| 975     | 30        | 0.77%   |
| 3733    | 29        | 0.74%   |
| 1066    | 28        | 0.72%   |
| 6400    | 27        | 0.69%   |
| 4267    | 25        | 0.64%   |
| 3400    | 25        | 0.64%   |
| 3266    | 24        | 0.62%   |
| 1800    | 23        | 0.59%   |
| 400     | 23        | 0.59%   |
| 2933    | 21        | 0.54%   |
| 1866    | 21        | 0.54%   |
| 2666    | 20        | 0.51%   |
| 3866    | 18        | 0.46%   |
| 3800    | 16        | 0.41%   |
| 8400    | 11        | 0.28%   |
| 3533    | 11        | 0.28%   |
| 333     | 11        | 0.28%   |
| 6000    | 10        | 0.26%   |
| 3333    | 10        | 0.26%   |
| 5600    | 8         | 0.21%   |
| 4266    | 8         | 0.21%   |
| 2866    | 8         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 54        | 45%     |
| Samsung Electronics   | 15        | 12.5%   |
| Brother Industries    | 14        | 11.67%  |
| Canon                 | 11        | 9.17%   |
| Seiko Epson           | 9         | 7.5%    |
| Prolific Technology   | 5         | 4.17%   |
| Lexmark International | 4         | 3.33%   |
| Zebra                 | 3         | 2.5%    |
| Xerox                 | 2         | 1.67%   |
| Minolta               | 1         | 0.83%   |
| MIIIW                 | 1         | 0.83%   |
| Datamax-O'Neil        | 1         | 0.83%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port           | 5         | 4.1%    |
| HP LaserJet 1020                        | 5         | 4.1%    |
| Samsung M2020 Series                    | 3         | 2.46%   |
| HP LaserJet P2015 series                | 3         | 2.46%   |
| HP HP LaserJet M14-M17                  | 3         | 2.46%   |
| Canon iP7200 series                     | 3         | 2.46%   |
| Seiko Epson L6270 Series                | 2         | 1.64%   |
| Seiko Epson AL-M310DN                   | 2         | 1.64%   |
| Samsung SCX-3400 Series                 | 2         | 1.64%   |
| Samsung ML-216x Series Laser Printer    | 2         | 1.64%   |
| Samsung ML-2010P Mono Laser Printer     | 2         | 1.64%   |
| HP LaserJet P1102                       | 2         | 1.64%   |
| HP LaserJet 1018                        | 2         | 1.64%   |
| HP Deskjet F4500 series                 | 2         | 1.64%   |
| HP DeskJet F4100 Printer series         | 2         | 1.64%   |
| HP Deskjet F2280 series                 | 2         | 1.64%   |
| HP DeskJet 845c                         | 2         | 1.64%   |
| HP DeskJet 840c                         | 2         | 1.64%   |
| HP DeskJet 4530 series                  | 2         | 1.64%   |
| HP DeskJet 3700 series                  | 2         | 1.64%   |
| HP DeskJet 2600 series                  | 2         | 1.64%   |
| HP Deskjet 2540 series                  | 2         | 1.64%   |
| HP Deskjet 1050 J410                    | 2         | 1.64%   |
| Canon PIXMA MG5600 Series               | 2         | 1.64%   |
| Canon LiDE 400                          | 2         | 1.64%   |
| Brother DCP-J105                        | 2         | 1.64%   |
| Brother DCP-1610W                       | 2         | 1.64%   |
| Zebra ZTC GX420t                        | 1         | 0.82%   |
| Zebra LP2844 Printer                    | 1         | 0.82%   |
| Zebra LP2824                            | 1         | 0.82%   |
| Xerox WorkCentre PE16                   | 1         | 0.82%   |
| Xerox Phaser 6000B                      | 1         | 0.82%   |
| Seiko Epson Stylus NX230/SX235W Series  | 1         | 0.82%   |
| Seiko Epson L405 Series                 | 1         | 0.82%   |
| Seiko Epson L3150 Series                | 1         | 0.82%   |
| Seiko Epson L1110 Series                | 1         | 0.82%   |
| Seiko Epson ET-2600 Series              | 1         | 0.82%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 0.82%   |
| Samsung SCX-6545 Series                 | 1         | 0.82%   |
| Samsung SCX-4300 Series                 | 1         | 0.82%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 13        | 61.9%   |
| Seiko Epson                 | 2         | 9.52%   |
| Plustek                     | 2         | 9.52%   |
| Ultima Electronics          | 1         | 4.76%   |
| Mustek Systems              | 1         | 4.76%   |
| Microtek International      | 1         | 4.76%   |
| Acer Peripherals (now BenQ) | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 5         | 23.81%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 9.52%   |
| Canon CanoScan LiDE 120                                  | 2         | 9.52%   |
| Canon CanoScan LiDE 110                                  | 2         | 9.52%   |
| Ultima Artec E+ 48U                                      | 1         | 4.76%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 4.76%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 4.76%   |
| Plustek OpticSlim 1200 Scanner                           | 1         | 4.76%   |
| Plustek OpticPro 1248U Scanner #2                        | 1         | 4.76%   |
| Mustek Systems BearPaw 2448 TA Pro                       | 1         | 4.76%   |
| Microtek International USB1200 Scanner                   | 1         | 4.76%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 4.76%   |
| Canon CanoScan LIDE 25                                   | 1         | 4.76%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 719       | 22.24%  |
| Microdia                               | 323       | 9.99%   |
| IMC Networks                           | 296       | 9.16%   |
| Realtek Semiconductor                  | 271       | 8.38%   |
| Sunplus Innovation Technology          | 167       | 5.17%   |
| Bison Electronics                      | 160       | 4.95%   |
| Quanta                                 | 144       | 4.45%   |
| Logitech                               | 127       | 3.93%   |
| Suyin                                  | 119       | 3.68%   |
| Cheng Uei Precision Industry (Foxlink) | 102       | 3.15%   |
| Syntek                                 | 93        | 2.88%   |
| Acer                                   | 91        | 2.81%   |
| Lite-On Technology                     | 75        | 2.32%   |
| Silicon Motion                         | 64        | 1.98%   |
| Apple                                  | 47        | 1.45%   |
| Luxvisions Innotech Limited            | 39        | 1.21%   |
| Creative Technology                    | 38        | 1.18%   |
| Ricoh                                  | 35        | 1.08%   |
| Alcor Micro                            | 34        | 1.05%   |
| Lenovo                                 | 30        | 0.93%   |
| Samsung Electronics                    | 27        | 0.84%   |
| Z-Star Microelectronics                | 25        | 0.77%   |
| Microsoft                              | 23        | 0.71%   |
| Sonix Technology                       | 18        | 0.56%   |
| DigiTech                               | 13        | 0.4%    |
| Intel                                  | 11        | 0.34%   |
| Primax Electronics                     | 10        | 0.31%   |
| Generalplus Technology                 | 10        | 0.31%   |
| ALi                                    | 10        | 0.31%   |
| Cubeternet                             | 9         | 0.28%   |
| Jieli Technology                       | 8         | 0.25%   |
| Hewlett-Packard                        | 7         | 0.22%   |
| Importek                               | 6         | 0.19%   |
| Trust                                  | 5         | 0.15%   |
| SunplusIT                              | 5         | 0.15%   |
| GEMBIRD                                | 5         | 0.15%   |
| Sunplus Technology                     | 4         | 0.12%   |
| Razer USA                              | 4         | 0.12%   |
| MacroSilicon                           | 4         | 0.12%   |
| LG Electronics                         | 4         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 144       | 4.43%   |
| Microdia Integrated_Webcam_HD            | 104       | 3.2%    |
| Realtek Integrated_Webcam_HD             | 94        | 2.89%   |
| IMC Networks Integrated Camera           | 81        | 2.49%   |
| IMC Networks USB2.0 HD UVC WebCam        | 73        | 2.25%   |
| Sunplus Integrated_Webcam_HD             | 59        | 1.82%   |
| Chicony Lenovo EasyCamera                | 50        | 1.54%   |
| Microdia Integrated Webcam               | 48        | 1.48%   |
| Chicony HD WebCam                        | 47        | 1.45%   |
| Bison Lenovo EasyCamera                  | 42        | 1.29%   |
| Syntek Integrated Camera                 | 40        | 1.23%   |
| Suyin Integrated_Webcam_HD               | 36        | 1.11%   |
| Bison Integrated Camera                  | 36        | 1.11%   |
| Syntek Lenovo EasyCamera                 | 33        | 1.02%   |
| Realtek USB Camera                       | 33        | 1.02%   |
| Lite-On Integrated Camera                | 33        | 1.02%   |
| Chicony HP HD Camera                     | 33        | 1.02%   |
| Realtek Lenovo EasyCamera                | 31        | 0.95%   |
| Logitech Webcam C270                     | 30        | 0.92%   |
| Quanta HP TrueVision HD Camera           | 29        | 0.89%   |
| Microdia USB 2.0 Camera                  | 28        | 0.86%   |
| Samsung Galaxy series, misc. (MTP mode)  | 25        | 0.77%   |
| Chicony USB2.0 HD UVC WebCam             | 24        | 0.74%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 23        | 0.71%   |
| Acer Integrated Camera                   | 23        | 0.71%   |
| Bison Lenovo Integrated Webcam           | 22        | 0.68%   |
| Quanta HD User Facing                    | 21        | 0.65%   |
| Microdia Laptop_Integrated_Webcam_HD     | 21        | 0.65%   |
| Acer SunplusIT Integrated Camera         | 21        | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 20        | 0.62%   |
| Realtek Integrated Webcam                | 20        | 0.62%   |
| Chicony Integrated Camera (1280x720@30)  | 19        | 0.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR       | 19        | 0.58%   |
| Creative Live! Cam Sync HD [VF0770]      | 18        | 0.55%   |
| Chicony USB2.0 VGA UVC WebCam            | 18        | 0.55%   |
| Chicony USB 2.0 Camera                   | 18        | 0.55%   |
| IMC Networks Integrated Webcam           | 17        | 0.52%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 17        | 0.52%   |
| Alcor Micro USB 2.0 Camera               | 17        | 0.52%   |
| Sonix USB2.0 HD UVC WebCam               | 16        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 229       | 36.7%   |
| Synaptics                          | 156       | 25%     |
| Shenzhen Goodix Technology         | 76        | 12.18%  |
| AuthenTec                          | 65        | 10.42%  |
| Upek                               | 38        | 6.09%   |
| Elan Microelectronics              | 26        | 4.17%   |
| LighTuning Technology              | 18        | 2.88%   |
| STMicroelectronics                 | 14        | 2.24%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 47        | 7.53%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 7.21%   |
| Shenzhen Goodix  FingerPrint Device                                        | 43        | 6.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 5.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 34        | 5.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 4.49%   |
| AuthenTec AES2810                                                          | 27        | 4.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 26        | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 25        | 4.01%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 18        | 2.88%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 17        | 2.72%   |
| Synaptics Fingerprint reader [HP G6]                                       | 17        | 2.72%   |
| Elan ELAN:Fingerprint                                                      | 17        | 2.72%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 2.24%   |
| Validity Sensors VFS491                                                    | 14        | 2.24%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.24%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.24%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 13        | 2.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 1.76%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 1.76%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.44%   |
| Synaptics  WBDI                                                            | 9         | 1.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.28%   |
| Elan ELAN:ARM-M4                                                           | 8         | 1.28%   |
| AuthenTec AES1600                                                          | 8         | 1.28%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.12%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.12%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.96%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.8%    |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.8%    |
| Synaptics WBDI                                                             | 5         | 0.8%    |
| Synaptics UWP WBDI                                                         | 5         | 0.8%    |
| LighTuning Fingerprint Reader                                              | 5         | 0.8%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.8%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.64%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.64%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.64%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 261       | 56.13%  |
| Alcor Micro               | 96        | 20.65%  |
| O2 Micro                  | 46        | 9.89%   |
| Upek                      | 22        | 4.73%   |
| Lenovo                    | 21        | 4.52%   |
| Gemalto (was Gemplus)     | 5         | 1.08%   |
| OmniKey                   | 3         | 0.65%   |
| Advanced Card Systems     | 3         | 0.65%   |
| SCM Microsystems          | 2         | 0.43%   |
| Clay Logic                | 2         | 0.43%   |
| Cherry                    | 2         | 0.43%   |
| Reiner SCT Kartensysteme  | 1         | 0.22%   |
| Aladdin Knowledge Systems | 1         | 0.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 93        | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 82        | 17.63%  |
| Broadcom 58200                                                               | 72        | 15.48%  |
| Broadcom 5880                                                                | 59        | 12.69%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 47        | 10.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 39        | 8.39%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 4.73%   |
| Lenovo Integrated Smart Card Reader                                          | 21        | 4.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.51%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.65%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.43%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.43%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.43%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.43%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.43%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.22%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.22%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.22%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.22%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.22%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.22%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.22%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.22%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.22%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3861      | 67.82%  |
| 1     | 1451      | 25.49%  |
| 2     | 311       | 5.46%   |
| 3     | 52        | 0.91%   |
| 4     | 8         | 0.14%   |
| 5     | 4         | 0.07%   |
| 7     | 3         | 0.05%   |
| 6     | 3         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 617       | 28.08%  |
| Graphics card            | 503       | 22.89%  |
| Chipcard                 | 414       | 18.84%  |
| Net/wireless             | 203       | 9.24%   |
| Multimedia controller    | 81        | 3.69%   |
| Communication controller | 61        | 2.78%   |
| Bluetooth                | 61        | 2.78%   |
| Storage                  | 55        | 2.5%    |
| Camera                   | 48        | 2.18%   |
| Unassigned class         | 37        | 1.68%   |
| Sound                    | 29        | 1.32%   |
| Card reader              | 20        | 0.91%   |
| Net/ethernet             | 12        | 0.55%   |
| Modem                    | 11        | 0.5%    |
| Firewire controller      | 11        | 0.5%    |
| Network                  | 9         | 0.41%   |
| Storage/ide              | 6         | 0.27%   |
| Dvb card                 | 6         | 0.27%   |
| Flash memory             | 5         | 0.23%   |
| Storage/raid             | 4         | 0.18%   |
| Wireless                 | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |
| Tv card                  | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |


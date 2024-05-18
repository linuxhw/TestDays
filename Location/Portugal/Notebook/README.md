Linux in Portugal - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

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

Total: 1803

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Cyborg 15 A12VF             | [1168634a54](https://linux-hardware.org/?probe=1168634a54) | May 06, 2024 |
| ASUSTek       | F5SL                        | [da423af0cb](https://linux-hardware.org/?probe=da423af0cb) | May 05, 2024 |
| ASUSTek       | ROG Strix G733QM_G733QM     | [c7e3ed99cc](https://linux-hardware.org/?probe=c7e3ed99cc) | May 04, 2024 |
| INSYS         | GW1-W149                    | [1219dfdc44](https://linux-hardware.org/?probe=1219dfdc44) | May 02, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [f899f3dccf](https://linux-hardware.org/?probe=f899f3dccf) | May 01, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [56c9f37671](https://linux-hardware.org/?probe=56c9f37671) | Apr 29, 2024 |
| Acer          | Nitro AN515-58              | [5192e9d32b](https://linux-hardware.org/?probe=5192e9d32b) | Apr 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4f05e448a7](https://linux-hardware.org/?probe=4f05e448a7) | Apr 26, 2024 |
| HUAWEI        | BOM-WXX9                    | [5fe5c7ed8d](https://linux-hardware.org/?probe=5fe5c7ed8d) | Apr 26, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [70560c5a36](https://linux-hardware.org/?probe=70560c5a36) | Apr 25, 2024 |
| Acer          | Nitro AN515-58              | [4512bf861b](https://linux-hardware.org/?probe=4512bf861b) | Apr 24, 2024 |
| Dell          | Latitude 5290 2-in-1        | [de4f7d0a06](https://linux-hardware.org/?probe=de4f7d0a06) | Apr 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [62d4436d4e](https://linux-hardware.org/?probe=62d4436d4e) | Apr 21, 2024 |
| Medion        | M14L-256                    | [21ced95f8d](https://linux-hardware.org/?probe=21ced95f8d) | Apr 21, 2024 |
| LNV           | M14LC2-256                  | [582ccc43d4](https://linux-hardware.org/?probe=582ccc43d4) | Apr 21, 2024 |
| Dell          | Latitude 13                 | [88b6f3f2c8](https://linux-hardware.org/?probe=88b6f3f2c8) | Apr 20, 2024 |
| HP            | Pavilion Notebook           | [8b925ca8f0](https://linux-hardware.org/?probe=8b925ca8f0) | Apr 19, 2024 |
| INSYS         | GW1-W149                    | [2f53f6286d](https://linux-hardware.org/?probe=2f53f6286d) | Apr 15, 2024 |
| Apple         | MacBookAir2,1               | [9145361a08](https://linux-hardware.org/?probe=9145361a08) | Apr 15, 2024 |
| Apple         | MacBookAir2,1               | [94a43b871f](https://linux-hardware.org/?probe=94a43b871f) | Apr 14, 2024 |
| Apple         | MacBookPro11,3              | [159bfe4be5](https://linux-hardware.org/?probe=159bfe4be5) | Apr 13, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [22b0bf7e14](https://linux-hardware.org/?probe=22b0bf7e14) | Apr 13, 2024 |
| Apple         | MacBookPro9,1               | [421b7a0e3a](https://linux-hardware.org/?probe=421b7a0e3a) | Apr 12, 2024 |
| Toshiba       | Satellite Pro C50-A-1C8     | [64265aeb0e](https://linux-hardware.org/?probe=64265aeb0e) | Apr 12, 2024 |
| ASUSTek       | X542URR                     | [e3a4e15a6e](https://linux-hardware.org/?probe=e3a4e15a6e) | Apr 12, 2024 |
| Dell          | Precision 3571              | [6bef26b856](https://linux-hardware.org/?probe=6bef26b856) | Apr 10, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [67c665fbe5](https://linux-hardware.org/?probe=67c665fbe5) | Apr 09, 2024 |
| ASUSTek       | K55VM                       | [081e45fb7f](https://linux-hardware.org/?probe=081e45fb7f) | Apr 08, 2024 |
| Dell          | Precision 3571              | [fdab7d40f5](https://linux-hardware.org/?probe=fdab7d40f5) | Apr 07, 2024 |
| HP            | EliteBook 840 14 inch G9... | [3eb7bba175](https://linux-hardware.org/?probe=3eb7bba175) | Apr 04, 2024 |
| ASUSTek       | ROG Strix G733QM_G733QM     | [556039fa6c](https://linux-hardware.org/?probe=556039fa6c) | Apr 04, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9bc584b914](https://linux-hardware.org/?probe=9bc584b914) | Apr 03, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [7a09978e27](https://linux-hardware.org/?probe=7a09978e27) | Apr 03, 2024 |
| Lenovo        | ThinkPad L380 20M50011PG    | [663de4db43](https://linux-hardware.org/?probe=663de4db43) | Apr 03, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [955dc4530f](https://linux-hardware.org/?probe=955dc4530f) | Apr 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [083640b754](https://linux-hardware.org/?probe=083640b754) | Mar 31, 2024 |
| Medion        | M14L-256                    | [28c0f833c0](https://linux-hardware.org/?probe=28c0f833c0) | Mar 31, 2024 |
| Dell          | Vostro 1015                 | [f9ca91d526](https://linux-hardware.org/?probe=f9ca91d526) | Mar 29, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [5b4456a2d6](https://linux-hardware.org/?probe=5b4456a2d6) | Mar 29, 2024 |
| Sony          | VPCY11S1E                   | [905655032f](https://linux-hardware.org/?probe=905655032f) | Mar 29, 2024 |
| INET          | Z156                        | [fd38934a49](https://linux-hardware.org/?probe=fd38934a49) | Mar 27, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c2dedfbe62](https://linux-hardware.org/?probe=c2dedfbe62) | Mar 25, 2024 |
| ASUSTek       | F5RL                        | [6d1c82c10a](https://linux-hardware.org/?probe=6d1c82c10a) | Mar 24, 2024 |
| Medion        | M14L-256                    | [d2fb66e78e](https://linux-hardware.org/?probe=d2fb66e78e) | Mar 22, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [99ff7d5b73](https://linux-hardware.org/?probe=99ff7d5b73) | Mar 21, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8041a52ffe](https://linux-hardware.org/?probe=8041a52ffe) | Mar 21, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | [3bc7983914](https://linux-hardware.org/?probe=3bc7983914) | Mar 20, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [f7da71747e](https://linux-hardware.org/?probe=f7da71747e) | Mar 18, 2024 |
| Dell          | Inspiron 15-3567            | [4c1a37011d](https://linux-hardware.org/?probe=4c1a37011d) | Mar 18, 2024 |
| Dell          | Inspiron 15-3567            | [b322a7f7ff](https://linux-hardware.org/?probe=b322a7f7ff) | Mar 18, 2024 |
| Toshiba       | Satellite C660D             | [63b9e3f1b8](https://linux-hardware.org/?probe=63b9e3f1b8) | Mar 18, 2024 |
| Medion        | E15301                      | [a3f6fc8c36](https://linux-hardware.org/?probe=a3f6fc8c36) | Mar 17, 2024 |
| HP            | Pavilion dv6000 (GF677EA... | [ecbe5ffb1f](https://linux-hardware.org/?probe=ecbe5ffb1f) | Mar 16, 2024 |
| HP            | Pavilion Power Laptop 15... | [8529154b4a](https://linux-hardware.org/?probe=8529154b4a) | Mar 15, 2024 |
| Acer          | Aspire 5742                 | [280af1d066](https://linux-hardware.org/?probe=280af1d066) | Mar 12, 2024 |
| HP            | OMEN by Laptop              | [754b3828fc](https://linux-hardware.org/?probe=754b3828fc) | Mar 12, 2024 |
| HP            | EliteBook Folio 9470m       | [ddf5a549da](https://linux-hardware.org/?probe=ddf5a549da) | Mar 11, 2024 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [695773aa7b](https://linux-hardware.org/?probe=695773aa7b) | Mar 10, 2024 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [fd7305258c](https://linux-hardware.org/?probe=fd7305258c) | Mar 10, 2024 |
| ASUSTek       | X555LJ                      | [72da032893](https://linux-hardware.org/?probe=72da032893) | Mar 09, 2024 |
| HP            | Laptop 15s-eq0xxx           | [e4a401d044](https://linux-hardware.org/?probe=e4a401d044) | Mar 08, 2024 |
| Lenovo        | ThinkPad T440p              | [fb060608ab](https://linux-hardware.org/?probe=fb060608ab) | Mar 08, 2024 |
| Dell          | Latitude 7280               | [b40f34a4ed](https://linux-hardware.org/?probe=b40f34a4ed) | Mar 02, 2024 |
| AMI           | Intel                       | [e9dc6ddc46](https://linux-hardware.org/?probe=e9dc6ddc46) | Mar 01, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | [39d528dadf](https://linux-hardware.org/?probe=39d528dadf) | Mar 01, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | [5fc24348a8](https://linux-hardware.org/?probe=5fc24348a8) | Mar 01, 2024 |
| HP            | Pavilion Laptop 15-eh2xx... | [0510a78cfe](https://linux-hardware.org/?probe=0510a78cfe) | Feb 29, 2024 |
| Dell          | Latitude 7400               | [97c11ef92d](https://linux-hardware.org/?probe=97c11ef92d) | Feb 28, 2024 |
| HP            | EliteBook 840 14 inch G9... | [fd37aa8001](https://linux-hardware.org/?probe=fd37aa8001) | Feb 27, 2024 |
| Acer          | NC-E1-530-21174G            | [56d0444e6b](https://linux-hardware.org/?probe=56d0444e6b) | Feb 27, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [0812dc5f8e](https://linux-hardware.org/?probe=0812dc5f8e) | Feb 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [527feb458b](https://linux-hardware.org/?probe=527feb458b) | Feb 26, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3b3a145c76](https://linux-hardware.org/?probe=3b3a145c76) | Feb 23, 2024 |
| Lenovo        | ThinkPad T440p              | [da00bee2f4](https://linux-hardware.org/?probe=da00bee2f4) | Feb 23, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [500e3a58df](https://linux-hardware.org/?probe=500e3a58df) | Feb 20, 2024 |
| Medion        | M14L-256                    | [b8b493a84b](https://linux-hardware.org/?probe=b8b493a84b) | Feb 18, 2024 |
| HP            | Pavilion dv6                | [27bd273fa1](https://linux-hardware.org/?probe=27bd273fa1) | Feb 16, 2024 |
| HP            | ENVY Sleekbook 6 PC         | [1fa513616f](https://linux-hardware.org/?probe=1fa513616f) | Feb 16, 2024 |
| HP            | ENVY Sleekbook 6 PC         | [697d384203](https://linux-hardware.org/?probe=697d384203) | Feb 16, 2024 |
| HP            | Pavilion dv6                | [fd84d867f4](https://linux-hardware.org/?probe=fd84d867f4) | Feb 15, 2024 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [e6ae670af4](https://linux-hardware.org/?probe=e6ae670af4) | Feb 15, 2024 |
| Dell          | Latitude 7490               | [2401d4da6d](https://linux-hardware.org/?probe=2401d4da6d) | Feb 15, 2024 |
| HP            | G62                         | [b6daa4e6b1](https://linux-hardware.org/?probe=b6daa4e6b1) | Feb 12, 2024 |
| HP            | ProBook 6475b               | [e8a155c0d9](https://linux-hardware.org/?probe=e8a155c0d9) | Feb 09, 2024 |
| ASUSTek       | K54LY                       | [44e7b53945](https://linux-hardware.org/?probe=44e7b53945) | Feb 08, 2024 |
| Medion        | M14L-256                    | [f36647da46](https://linux-hardware.org/?probe=f36647da46) | Feb 07, 2024 |
| Apple         | MacBookPro5,1               | [965e14a38d](https://linux-hardware.org/?probe=965e14a38d) | Feb 06, 2024 |
| Apple         | MacBookPro5,1               | [0f0883d52e](https://linux-hardware.org/?probe=0f0883d52e) | Feb 06, 2024 |
| Dell          | Latitude E5450              | [03b9a11c55](https://linux-hardware.org/?probe=03b9a11c55) | Feb 06, 2024 |
| Dell          | XPS 9320                    | [74d4b364f8](https://linux-hardware.org/?probe=74d4b364f8) | Feb 03, 2024 |
| Dell          | Latitude 7280               | [0a79c87afb](https://linux-hardware.org/?probe=0a79c87afb) | Jan 31, 2024 |
| ASUSTek       | GL552JX                     | [4aebfef2d8](https://linux-hardware.org/?probe=4aebfef2d8) | Jan 31, 2024 |
| Minix         | NEO Z83-4A                  | [a563c8089f](https://linux-hardware.org/?probe=a563c8089f) | Jan 31, 2024 |
| Valve         | Jupiter                     | [282271ee83](https://linux-hardware.org/?probe=282271ee83) | Jan 31, 2024 |
| Valve         | Jupiter                     | [1cdbb473c3](https://linux-hardware.org/?probe=1cdbb473c3) | Jan 30, 2024 |
| HP            | Pavilion Power Laptop 15... | [8098729533](https://linux-hardware.org/?probe=8098729533) | Jan 30, 2024 |
| ASUSTek       | GL552JX                     | [4acec8f3e2](https://linux-hardware.org/?probe=4acec8f3e2) | Jan 30, 2024 |
| Medion        | M14L-256                    | [6bff8bee51](https://linux-hardware.org/?probe=6bff8bee51) | Jan 28, 2024 |
| Toshiba       | Satellite P50-B-10Z         | [574103da6a](https://linux-hardware.org/?probe=574103da6a) | Jan 28, 2024 |
| Dell          | Latitude 7490               | [8687d67e07](https://linux-hardware.org/?probe=8687d67e07) | Jan 27, 2024 |
| HP            | EliteBook 2560p             | [ed987e9ac7](https://linux-hardware.org/?probe=ed987e9ac7) | Jan 27, 2024 |
| HP            | Laptop 15-db0xxx            | [077619fc48](https://linux-hardware.org/?probe=077619fc48) | Jan 27, 2024 |
| Sony          | SVF1521J7EW                 | [ad472454ae](https://linux-hardware.org/?probe=ad472454ae) | Jan 27, 2024 |
| INSYS         | GW1-W149                    | [a37edb118a](https://linux-hardware.org/?probe=a37edb118a) | Jan 26, 2024 |
| Sony          | VGN-CS11S_Q                 | [df687ca726](https://linux-hardware.org/?probe=df687ca726) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [660c45b7e5](https://linux-hardware.org/?probe=660c45b7e5) | Jan 26, 2024 |
| Sony          | VGN-CS11S_Q                 | [4c9e427a30](https://linux-hardware.org/?probe=4c9e427a30) | Jan 25, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [4a41cdcc67](https://linux-hardware.org/?probe=4a41cdcc67) | Jan 25, 2024 |
| Hampoo        | I2W6_AP135 Reserved         | [fe5025efdd](https://linux-hardware.org/?probe=fe5025efdd) | Jan 21, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [d10912daa4](https://linux-hardware.org/?probe=d10912daa4) | Jan 21, 2024 |
| Lenovo        | ThinkPad T460 20FMS0CR00    | [1bfe0bce6d](https://linux-hardware.org/?probe=1bfe0bce6d) | Jan 21, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [53887e0fb9](https://linux-hardware.org/?probe=53887e0fb9) | Jan 21, 2024 |
| Dell          | Latitude 7280               | [2b43daee98](https://linux-hardware.org/?probe=2b43daee98) | Jan 20, 2024 |
| Medion        | M14L-256                    | [095760429f](https://linux-hardware.org/?probe=095760429f) | Jan 18, 2024 |
| Unknown       | Unknown                     | [6e08825a5c](https://linux-hardware.org/?probe=6e08825a5c) | Jan 17, 2024 |
| HP            | Laptop 14s-dq0xxx           | [d8a2561e72](https://linux-hardware.org/?probe=d8a2561e72) | Jan 12, 2024 |
| ASUSTek       | ZenBook S UX391UA           | [bc0571ca78](https://linux-hardware.org/?probe=bc0571ca78) | Jan 11, 2024 |
| ASUSTek       | ZenBook S UX391UA           | [21d336676f](https://linux-hardware.org/?probe=21d336676f) | Jan 11, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [8d8f216f10](https://linux-hardware.org/?probe=8d8f216f10) | Jan 10, 2024 |
| Sony          | VGN-FZ31Z                   | [3df7d503da](https://linux-hardware.org/?probe=3df7d503da) | Jan 09, 2024 |
| Dell          | XPS 15 9530                 | [26570f8a8b](https://linux-hardware.org/?probe=26570f8a8b) | Jan 08, 2024 |
| ASUSTek       | X550CC                      | [b4987d6897](https://linux-hardware.org/?probe=b4987d6897) | Jan 08, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f101013f61](https://linux-hardware.org/?probe=f101013f61) | Jan 07, 2024 |
| ASUSTek       | N550JK                      | [5fe8e3ca15](https://linux-hardware.org/?probe=5fe8e3ca15) | Jan 07, 2024 |
| Acer          | Aspire ES1-572              | [6de42f8573](https://linux-hardware.org/?probe=6de42f8573) | Jan 06, 2024 |
| HP            | Pavilion 10 TS              | [cd7638b3d6](https://linux-hardware.org/?probe=cd7638b3d6) | Jan 05, 2024 |
| ASUSTek       | P50IJ                       | [5a72912f2f](https://linux-hardware.org/?probe=5a72912f2f) | Jan 03, 2024 |
| Acer          | Aspire ES1-520              | [a869979bc4](https://linux-hardware.org/?probe=a869979bc4) | Jan 02, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [8701a130d2](https://linux-hardware.org/?probe=8701a130d2) | Jan 02, 2024 |
| ASUSTek       | K53SC                       | [1f2ddea9fa](https://linux-hardware.org/?probe=1f2ddea9fa) | Dec 31, 2023 |
| Medion        | M14L-256                    | [0dbbd4db74](https://linux-hardware.org/?probe=0dbbd4db74) | Dec 31, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [8b28cb5a8f](https://linux-hardware.org/?probe=8b28cb5a8f) | Dec 30, 2023 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [11892aa026](https://linux-hardware.org/?probe=11892aa026) | Dec 30, 2023 |
| HP            | OMEN by Laptop              | [71d20fd45b](https://linux-hardware.org/?probe=71d20fd45b) | Dec 28, 2023 |
| Acer          | Aspire E5-571G              | [a143ecb3c3](https://linux-hardware.org/?probe=a143ecb3c3) | Dec 27, 2023 |
| Dell          | Latitude 7490               | [3c17f0bdce](https://linux-hardware.org/?probe=3c17f0bdce) | Dec 25, 2023 |
| Dell          | Latitude 7490               | [69205c648f](https://linux-hardware.org/?probe=69205c648f) | Dec 24, 2023 |
| Unknown       | Unknown                     | [006211d916](https://linux-hardware.org/?probe=006211d916) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [bfc1ebaf00](https://linux-hardware.org/?probe=bfc1ebaf00) | Dec 22, 2023 |
| HP            | 350 G1                      | [c219133bce](https://linux-hardware.org/?probe=c219133bce) | Dec 20, 2023 |
| Dell          | Latitude E6510              | [e9aceddae8](https://linux-hardware.org/?probe=e9aceddae8) | Dec 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7b5e55e475](https://linux-hardware.org/?probe=7b5e55e475) | Dec 18, 2023 |
| ASUSTek       | ROG Zephyrus S15 GX502LX... | [357f74bcc2](https://linux-hardware.org/?probe=357f74bcc2) | Dec 17, 2023 |
| Medion        | M14L-256                    | [6cd85934b3](https://linux-hardware.org/?probe=6cd85934b3) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7a1a444ed0](https://linux-hardware.org/?probe=7a1a444ed0) | Dec 15, 2023 |
| HP            | Laptop 15s-eq0xxx           | [cee2ad1e7c](https://linux-hardware.org/?probe=cee2ad1e7c) | Dec 15, 2023 |
| HP            | EliteBook 8530w             | [6ce01d863a](https://linux-hardware.org/?probe=6ce01d863a) | Dec 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [a56ec48040](https://linux-hardware.org/?probe=a56ec48040) | Dec 13, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [490ceeb636](https://linux-hardware.org/?probe=490ceeb636) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | [cdcd6ddfc6](https://linux-hardware.org/?probe=cdcd6ddfc6) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | [e6f39159ad](https://linux-hardware.org/?probe=e6f39159ad) | Dec 13, 2023 |
| Medion        | M14L-256                    | [b5e0624a7f](https://linux-hardware.org/?probe=b5e0624a7f) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7be431fb](https://linux-hardware.org/?probe=af7be431fb) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d27df22c9a](https://linux-hardware.org/?probe=d27df22c9a) | Dec 11, 2023 |
| HP            | EliteBook 840 14 inch G1... | [17dd4245b8](https://linux-hardware.org/?probe=17dd4245b8) | Dec 11, 2023 |
| Lenovo        | ThinkPad T530 242922G       | [2b8062d3cc](https://linux-hardware.org/?probe=2b8062d3cc) | Dec 09, 2023 |
| Acer          | Aspire A515-45              | [ccc3f6589d](https://linux-hardware.org/?probe=ccc3f6589d) | Dec 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e7fabdedad](https://linux-hardware.org/?probe=e7fabdedad) | Dec 07, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [3ffedf98eb](https://linux-hardware.org/?probe=3ffedf98eb) | Dec 07, 2023 |
| Dell          | Latitude E5440              | [56987fc258](https://linux-hardware.org/?probe=56987fc258) | Dec 06, 2023 |
| Dell          | Latitude E5440              | [6cdafbd9d1](https://linux-hardware.org/?probe=6cdafbd9d1) | Dec 06, 2023 |
| ASUSTek       | 1015PEM                     | [cbaedb564f](https://linux-hardware.org/?probe=cbaedb564f) | Dec 06, 2023 |
| Dell          | Inspiron 1545               | [d54ba07f49](https://linux-hardware.org/?probe=d54ba07f49) | Dec 06, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [2ffb70a1ca](https://linux-hardware.org/?probe=2ffb70a1ca) | Dec 03, 2023 |
| Gigabyte      | AERO 15 KD                  | [58b6cdf11c](https://linux-hardware.org/?probe=58b6cdf11c) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d4a1f56f8d](https://linux-hardware.org/?probe=d4a1f56f8d) | Dec 01, 2023 |
| HP            | Pavilion Notebook           | [06fdc9d8e6](https://linux-hardware.org/?probe=06fdc9d8e6) | Dec 01, 2023 |
| Dell          | Inspiron 5570               | [6642e4462f](https://linux-hardware.org/?probe=6642e4462f) | Nov 30, 2023 |
| TUXEDO        | Book BA1510                 | [0c59322d62](https://linux-hardware.org/?probe=0c59322d62) | Nov 29, 2023 |
| Gigabyte      | AERO 15 KD                  | [772e5ce3f6](https://linux-hardware.org/?probe=772e5ce3f6) | Nov 29, 2023 |
| Dell          | Latitude 7490               | [70a7c438a1](https://linux-hardware.org/?probe=70a7c438a1) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [2ca445207e](https://linux-hardware.org/?probe=2ca445207e) | Nov 26, 2023 |
| HP            | Laptop 15s-fq2xxx           | [aa4097f060](https://linux-hardware.org/?probe=aa4097f060) | Nov 24, 2023 |
| Valve         | Jupiter                     | [399542e5be](https://linux-hardware.org/?probe=399542e5be) | Nov 24, 2023 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [db22f8c316](https://linux-hardware.org/?probe=db22f8c316) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | [ca5e9fbf52](https://linux-hardware.org/?probe=ca5e9fbf52) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | [ab672024d6](https://linux-hardware.org/?probe=ab672024d6) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bf30102553](https://linux-hardware.org/?probe=bf30102553) | Nov 23, 2023 |
| ASUSTek       | X542URR                     | [7fb275b8f2](https://linux-hardware.org/?probe=7fb275b8f2) | Nov 22, 2023 |
| Samsung       | RC530/RC730                 | [8d328f4394](https://linux-hardware.org/?probe=8d328f4394) | Nov 21, 2023 |
| Toshiba       | Satellite P50-B-11V         | [448150c108](https://linux-hardware.org/?probe=448150c108) | Nov 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [ebfe063207](https://linux-hardware.org/?probe=ebfe063207) | Nov 19, 2023 |
| Timi          | TM1701                      | [f14bab873b](https://linux-hardware.org/?probe=f14bab873b) | Nov 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [f5414a4ffe](https://linux-hardware.org/?probe=f5414a4ffe) | Nov 18, 2023 |
| MSI           | Prestige 14Evo A12M         | [39c61d33cc](https://linux-hardware.org/?probe=39c61d33cc) | Nov 18, 2023 |
| Jumper        | EZbook                      | [5623f4ec87](https://linux-hardware.org/?probe=5623f4ec87) | Nov 15, 2023 |
| HP            | EliteBook 840 14 inch G1... | [f4d839670e](https://linux-hardware.org/?probe=f4d839670e) | Nov 13, 2023 |
| Dell          | Latitude 13                 | [4999e3eba9](https://linux-hardware.org/?probe=4999e3eba9) | Nov 09, 2023 |
| Dell          | Latitude 13                 | [acb0bd4f9d](https://linux-hardware.org/?probe=acb0bd4f9d) | Nov 09, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [4f037eafa8](https://linux-hardware.org/?probe=4f037eafa8) | Nov 08, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [216e0bed29](https://linux-hardware.org/?probe=216e0bed29) | Nov 07, 2023 |
| Apple         | MacBookPro11,4              | [45dfbee68a](https://linux-hardware.org/?probe=45dfbee68a) | Nov 05, 2023 |
| Notebook      | N141CU                      | [8f817eeabf](https://linux-hardware.org/?probe=8f817eeabf) | Nov 04, 2023 |
| POV           | I102A                       | [955f97d47e](https://linux-hardware.org/?probe=955f97d47e) | Nov 04, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [abe3da8a30](https://linux-hardware.org/?probe=abe3da8a30) | Nov 03, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7ccaf83d7](https://linux-hardware.org/?probe=e7ccaf83d7) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S937               | [e4e8acb8db](https://linux-hardware.org/?probe=e4e8acb8db) | Nov 03, 2023 |
| Sony          | VGN-CS21S_R                 | [a7eb8de9f5](https://linux-hardware.org/?probe=a7eb8de9f5) | Nov 01, 2023 |
| Apple         | MacBookPro8,1               | [f1387b3bd9](https://linux-hardware.org/?probe=f1387b3bd9) | Nov 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [639a14d08d](https://linux-hardware.org/?probe=639a14d08d) | Nov 01, 2023 |
| ASUSTek       | X555LD                      | [2c79650ee2](https://linux-hardware.org/?probe=2c79650ee2) | Oct 29, 2023 |
| Dell          | Latitude E5400              | [169d73bee0](https://linux-hardware.org/?probe=169d73bee0) | Oct 28, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [cb44c39574](https://linux-hardware.org/?probe=cb44c39574) | Oct 27, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [3cf7c10977](https://linux-hardware.org/?probe=3cf7c10977) | Oct 25, 2023 |
| HP            | EliteBook 820 G2            | [d6d5273a5a](https://linux-hardware.org/?probe=d6d5273a5a) | Oct 25, 2023 |
| Dell          | Inspiron 11-3168            | [07fd1e8be9](https://linux-hardware.org/?probe=07fd1e8be9) | Oct 25, 2023 |
| Gigabyte      | G5 KC                       | [32743a624c](https://linux-hardware.org/?probe=32743a624c) | Oct 24, 2023 |
| Gigabyte      | G5 KC                       | [23d64978d9](https://linux-hardware.org/?probe=23d64978d9) | Oct 24, 2023 |
| Sony          | VGN-FZ21M                   | [ba7c93bcd4](https://linux-hardware.org/?probe=ba7c93bcd4) | Oct 21, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [801d54f088](https://linux-hardware.org/?probe=801d54f088) | Oct 21, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [69d0758d3d](https://linux-hardware.org/?probe=69d0758d3d) | Oct 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [2408be3605](https://linux-hardware.org/?probe=2408be3605) | Oct 16, 2023 |
| Gigabyte      | G7 GD                       | [667243780c](https://linux-hardware.org/?probe=667243780c) | Oct 15, 2023 |
| HP            | EliteBook 840 G2            | [3055b32637](https://linux-hardware.org/?probe=3055b32637) | Oct 15, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [bd6f7ac948](https://linux-hardware.org/?probe=bd6f7ac948) | Oct 13, 2023 |
| Samsung       | 550XCJ/550XCR               | [3b06edb6bf](https://linux-hardware.org/?probe=3b06edb6bf) | Oct 13, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [adad0100ea](https://linux-hardware.org/?probe=adad0100ea) | Oct 13, 2023 |
| Lenovo        | ThinkPad X250 20CM0048US    | [cf66338531](https://linux-hardware.org/?probe=cf66338531) | Oct 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [20b1614237](https://linux-hardware.org/?probe=20b1614237) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [d5040f4ca4](https://linux-hardware.org/?probe=d5040f4ca4) | Oct 12, 2023 |
| MSI           | Prestige 16Studio A13VE     | [0209063983](https://linux-hardware.org/?probe=0209063983) | Oct 12, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c715105687](https://linux-hardware.org/?probe=c715105687) | Oct 10, 2023 |
| ASUSTek       | K52JB                       | [a2a5c14c8a](https://linux-hardware.org/?probe=a2a5c14c8a) | Oct 09, 2023 |
| MSI           | Summit E16Flip A12UCT       | [882d0daf54](https://linux-hardware.org/?probe=882d0daf54) | Oct 09, 2023 |
| ASUSTek       | K52JB                       | [b3fd22ad8e](https://linux-hardware.org/?probe=b3fd22ad8e) | Oct 08, 2023 |
| HP            | Pavilion 15                 | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| Dell          | XPS 15 9500                 | [ee251b10d4](https://linux-hardware.org/?probe=ee251b10d4) | Oct 07, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [08aa11c398](https://linux-hardware.org/?probe=08aa11c398) | Oct 05, 2023 |
| HP            | Laptop 15-db0xxx            | [9b841951f2](https://linux-hardware.org/?probe=9b841951f2) | Oct 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8ba8fa3184](https://linux-hardware.org/?probe=8ba8fa3184) | Oct 05, 2023 |
| HP            | EliteBook 840 G2            | [a90e584705](https://linux-hardware.org/?probe=a90e584705) | Oct 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [bf9ddbe725](https://linux-hardware.org/?probe=bf9ddbe725) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [3a8b2b229a](https://linux-hardware.org/?probe=3a8b2b229a) | Oct 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [b0b5262c87](https://linux-hardware.org/?probe=b0b5262c87) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [d929b857db](https://linux-hardware.org/?probe=d929b857db) | Oct 01, 2023 |
| ASUSTek       | F7SR                        | [b895fd8bb2](https://linux-hardware.org/?probe=b895fd8bb2) | Sep 30, 2023 |
| ASUSTek       | F7SR                        | [1b7493ae6e](https://linux-hardware.org/?probe=1b7493ae6e) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| ASUSTek       | K52JB                       | [7524eea19f](https://linux-hardware.org/?probe=7524eea19f) | Sep 26, 2023 |
| HP            | G62                         | [50fef7b3fa](https://linux-hardware.org/?probe=50fef7b3fa) | Sep 26, 2023 |
| Samsung       | 300E5M/300E5L               | [1df46b6215](https://linux-hardware.org/?probe=1df46b6215) | Sep 25, 2023 |
| Samsung       | 300E5M/300E5L               | [1d90b7b714](https://linux-hardware.org/?probe=1d90b7b714) | Sep 25, 2023 |
| ASUSTek       | K55VM                       | [3dd45a6297](https://linux-hardware.org/?probe=3dd45a6297) | Sep 24, 2023 |
| Notebook      | P7xxTM                      | [e14cfa2f1f](https://linux-hardware.org/?probe=e14cfa2f1f) | Sep 22, 2023 |
| Notebook      | P7xxTM                      | [41b1348520](https://linux-hardware.org/?probe=41b1348520) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [98ab1e6859](https://linux-hardware.org/?probe=98ab1e6859) | Sep 21, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [7377101d6d](https://linux-hardware.org/?probe=7377101d6d) | Sep 20, 2023 |
| HP            | Laptop 15-bs0xx             | [963330511d](https://linux-hardware.org/?probe=963330511d) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | [5f8df7dfcb](https://linux-hardware.org/?probe=5f8df7dfcb) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [50c2f9349d](https://linux-hardware.org/?probe=50c2f9349d) | Sep 18, 2023 |
| MSI           | PS42 8RB                    | [2fa07ede2a](https://linux-hardware.org/?probe=2fa07ede2a) | Sep 16, 2023 |
| PC Special... | P7xxTM1                     | [2bdbc2f2e7](https://linux-hardware.org/?probe=2bdbc2f2e7) | Sep 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| ASUSTek       | GL553VW                     | [3859055e8d](https://linux-hardware.org/?probe=3859055e8d) | Sep 11, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6RF0... | [6c62d111db](https://linux-hardware.org/?probe=6c62d111db) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [8dc4477486](https://linux-hardware.org/?probe=8dc4477486) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [e737851117](https://linux-hardware.org/?probe=e737851117) | Sep 10, 2023 |
| Dell          | Inspiron 11-3168            | [57ef365bf9](https://linux-hardware.org/?probe=57ef365bf9) | Sep 10, 2023 |
| Dell          | Latitude E7240              | [79a666783a](https://linux-hardware.org/?probe=79a666783a) | Sep 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c9a07c44d5](https://linux-hardware.org/?probe=c9a07c44d5) | Sep 06, 2023 |
| HP            | mt40                        | [c3a4682e40](https://linux-hardware.org/?probe=c3a4682e40) | Sep 04, 2023 |
| Lenovo        | ThinkPad SL510 28473QB      | [e1ff8baa87](https://linux-hardware.org/?probe=e1ff8baa87) | Sep 04, 2023 |
| ASUSTek       | X555LJ                      | [c13b1a693d](https://linux-hardware.org/?probe=c13b1a693d) | Sep 03, 2023 |
| Acer          | Aspire A515-57              | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1BL0... | [f1e1512fc9](https://linux-hardware.org/?probe=f1e1512fc9) | Sep 01, 2023 |
| Apple         | MacBookPro11,1              | [b3caa97382](https://linux-hardware.org/?probe=b3caa97382) | Aug 30, 2023 |
| Lenovo        | 3000 G410                   | [26c592ddd6](https://linux-hardware.org/?probe=26c592ddd6) | Aug 29, 2023 |
| HP            | Laptop 15s-eq1xxx           | [fe431ea565](https://linux-hardware.org/?probe=fe431ea565) | Aug 29, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5e7257145a](https://linux-hardware.org/?probe=5e7257145a) | Aug 26, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [627068909d](https://linux-hardware.org/?probe=627068909d) | Aug 25, 2023 |
| HP            | 15                          | [76decc7899](https://linux-hardware.org/?probe=76decc7899) | Aug 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [7e6a7de337](https://linux-hardware.org/?probe=7e6a7de337) | Aug 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e0a5f63a8b](https://linux-hardware.org/?probe=e0a5f63a8b) | Aug 22, 2023 |
| Acer          | Aspire ES1-520              | [99cdeba16c](https://linux-hardware.org/?probe=99cdeba16c) | Aug 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a665e45380](https://linux-hardware.org/?probe=a665e45380) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [b5e6b20270](https://linux-hardware.org/?probe=b5e6b20270) | Aug 18, 2023 |
| Chuwi         | GemiBook XPro               | [41b34e60fd](https://linux-hardware.org/?probe=41b34e60fd) | Aug 18, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [82c579f8a7](https://linux-hardware.org/?probe=82c579f8a7) | Aug 16, 2023 |
| HP            | Pavilion dv6                | [ee8c1f96e8](https://linux-hardware.org/?probe=ee8c1f96e8) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7050972395](https://linux-hardware.org/?probe=7050972395) | Aug 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [67a1535765](https://linux-hardware.org/?probe=67a1535765) | Aug 15, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| LNV           | L40-70                      | [66fe107447](https://linux-hardware.org/?probe=66fe107447) | Aug 11, 2023 |
| HP            | 250 G3                      | [512fd5d81f](https://linux-hardware.org/?probe=512fd5d81f) | Aug 10, 2023 |
| HP            | Notebook                    | [02ceb78a4f](https://linux-hardware.org/?probe=02ceb78a4f) | Aug 07, 2023 |
| Medion        | M14L-256                    | [7d0a8921dc](https://linux-hardware.org/?probe=7d0a8921dc) | Aug 07, 2023 |
| Apple         | MacBook7,1                  | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Teclast       | F7S                         | [a844443394](https://linux-hardware.org/?probe=a844443394) | Aug 06, 2023 |
| Unknown       | Unknown                     | [9431f6f4e8](https://linux-hardware.org/?probe=9431f6f4e8) | Aug 06, 2023 |
| Teclast       | F7S                         | [71ab18cda5](https://linux-hardware.org/?probe=71ab18cda5) | Aug 05, 2023 |
| HUAWEI        | RLEF-XX                     | [5b0c2b27e7](https://linux-hardware.org/?probe=5b0c2b27e7) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [2825bbd67b](https://linux-hardware.org/?probe=2825bbd67b) | Aug 04, 2023 |
| ASUSTek       | UX430UNR                    | [89c8324528](https://linux-hardware.org/?probe=89c8324528) | Aug 01, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| Lenovo        | G50-45 80E3                 | [002504b8be](https://linux-hardware.org/?probe=002504b8be) | Jul 29, 2023 |
| HP            | Laptop 15-fc0xxx            | [30dabbbc28](https://linux-hardware.org/?probe=30dabbbc28) | Jul 28, 2023 |
| HP            | EliteBook 840 G3            | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| MSI           | Summit E16Flip A12UCT       | [daf09efe6e](https://linux-hardware.org/?probe=daf09efe6e) | Jul 24, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c1e386e9cc](https://linux-hardware.org/?probe=c1e386e9cc) | Jul 22, 2023 |
| Acer          | Extensa 5635ZG              | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [069bfd995c](https://linux-hardware.org/?probe=069bfd995c) | Jul 15, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [7d2f78f0d3](https://linux-hardware.org/?probe=7d2f78f0d3) | Jul 15, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [20e49aa241](https://linux-hardware.org/?probe=20e49aa241) | Jul 14, 2023 |
| HP            | Pavilion dv3                | [94eeea2364](https://linux-hardware.org/?probe=94eeea2364) | Jul 12, 2023 |
| HP            | EliteBook 645 14 inch G9... | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Dell          | Latitude E5500              | [03798c7840](https://linux-hardware.org/?probe=03798c7840) | Jul 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [50f23f3476](https://linux-hardware.org/?probe=50f23f3476) | Jul 09, 2023 |
| Dell          | XPS 13 9350                 | [9fc07d1102](https://linux-hardware.org/?probe=9fc07d1102) | Jul 08, 2023 |
| HP            | 350 G1                      | [d965c2785d](https://linux-hardware.org/?probe=d965c2785d) | Jul 04, 2023 |
| HP            | 350 G1                      | [bb742c9ffb](https://linux-hardware.org/?probe=bb742c9ffb) | Jul 04, 2023 |
| Acer          | Aspire 5737Z                | [842aa57faf](https://linux-hardware.org/?probe=842aa57faf) | Jun 30, 2023 |
| ASUSTek       | K56CB                       | [952909bc80](https://linux-hardware.org/?probe=952909bc80) | Jun 29, 2023 |
| MSI           | PS63 Modern 8SC             | [dcbb8108cf](https://linux-hardware.org/?probe=dcbb8108cf) | Jun 29, 2023 |
| Lenovo        | ThinkPad T430 2349OB6       | [f2f66bb9d0](https://linux-hardware.org/?probe=f2f66bb9d0) | Jun 29, 2023 |
| Toshiba       | Satellite X200              | [4a3e7008cf](https://linux-hardware.org/?probe=4a3e7008cf) | Jun 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c05a780b64](https://linux-hardware.org/?probe=c05a780b64) | Jun 27, 2023 |
| Gigabyte      | AERO 15 KD                  | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | XPS 9315                    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| HP            | EliteBook 840 G5            | [4ad837baa7](https://linux-hardware.org/?probe=4ad837baa7) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4b866ca19f](https://linux-hardware.org/?probe=4b866ca19f) | Jun 22, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [22c2768f76](https://linux-hardware.org/?probe=22c2768f76) | Jun 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2f19a23a54](https://linux-hardware.org/?probe=2f19a23a54) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | [3d8b5e9564](https://linux-hardware.org/?probe=3d8b5e9564) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | [fb8da18b42](https://linux-hardware.org/?probe=fb8da18b42) | Jun 17, 2023 |
| Dell          | Latitude E5400              | [f5d066d8fc](https://linux-hardware.org/?probe=f5d066d8fc) | Jun 16, 2023 |
| Toshiba       | Satellite X200              | [d57a63387d](https://linux-hardware.org/?probe=d57a63387d) | Jun 15, 2023 |
| Toshiba       | Satellite L650              | [d92c0dea02](https://linux-hardware.org/?probe=d92c0dea02) | Jun 14, 2023 |
| Sony          | SVF1521J7EW                 | [2d04d992c2](https://linux-hardware.org/?probe=2d04d992c2) | Jun 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| Chuwi         | GemiBook Pro                | [83adb0e53a](https://linux-hardware.org/?probe=83adb0e53a) | Jun 07, 2023 |
| Lenovo        | ThinkPad T440p              | [d46387134e](https://linux-hardware.org/?probe=d46387134e) | Jun 07, 2023 |
| Chuwi         | GemiBook Pro                | [1378fdec29](https://linux-hardware.org/?probe=1378fdec29) | Jun 07, 2023 |
| Lenovo        | ThinkPad T440p              | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| ASUSTek       | N56VB                       | [f47c68a2a7](https://linux-hardware.org/?probe=f47c68a2a7) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | [6964a1da79](https://linux-hardware.org/?probe=6964a1da79) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Dell          | Latitude 5491               | [6a8a7e6188](https://linux-hardware.org/?probe=6a8a7e6188) | Jun 03, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [3de77b392a](https://linux-hardware.org/?probe=3de77b392a) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [109dbbfff0](https://linux-hardware.org/?probe=109dbbfff0) | Jun 02, 2023 |
| HP            | Unknown                     | [626075d6f2](https://linux-hardware.org/?probe=626075d6f2) | Jun 02, 2023 |
| HP            | Unknown                     | [2289bb8d24](https://linux-hardware.org/?probe=2289bb8d24) | Jun 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [302ae0e2dc](https://linux-hardware.org/?probe=302ae0e2dc) | Jun 02, 2023 |
| Chuwi         | GemiBook Pro                | [f17ebfac4b](https://linux-hardware.org/?probe=f17ebfac4b) | May 31, 2023 |
| HP            | Unknown                     | [3eb658702b](https://linux-hardware.org/?probe=3eb658702b) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [93ac1fb021](https://linux-hardware.org/?probe=93ac1fb021) | May 31, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [5881fb6ae2](https://linux-hardware.org/?probe=5881fb6ae2) | May 30, 2023 |
| HP            | Unknown                     | [2007104aeb](https://linux-hardware.org/?probe=2007104aeb) | May 30, 2023 |
| Lenovo        | ThinkPad E490 20N8000RPG    | [73b8bfb3a5](https://linux-hardware.org/?probe=73b8bfb3a5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [84781c068a](https://linux-hardware.org/?probe=84781c068a) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [97f0880258](https://linux-hardware.org/?probe=97f0880258) | May 29, 2023 |
| Chuwi         | GemiBook Pro                | [5684d2005d](https://linux-hardware.org/?probe=5684d2005d) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [462ae1c4f5](https://linux-hardware.org/?probe=462ae1c4f5) | May 28, 2023 |
| HP            | 15                          | [f5373f2397](https://linux-hardware.org/?probe=f5373f2397) | May 27, 2023 |
| HP            | 15                          | [f30c3b3a95](https://linux-hardware.org/?probe=f30c3b3a95) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [0f3f548ff0](https://linux-hardware.org/?probe=0f3f548ff0) | May 27, 2023 |
| Sony          | VGN-FZ31Z                   | [31c6913c14](https://linux-hardware.org/?probe=31c6913c14) | May 26, 2023 |
| ASUSTek       | K55VJ                       | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Chuwi         | GemiBook Pro                | [ac87b1945b](https://linux-hardware.org/?probe=ac87b1945b) | May 26, 2023 |
| ASUSTek       | GL702ZC                     | [c60d7fabbb](https://linux-hardware.org/?probe=c60d7fabbb) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [b5a283de1d](https://linux-hardware.org/?probe=b5a283de1d) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [0a65452634](https://linux-hardware.org/?probe=0a65452634) | May 24, 2023 |
| ASUSTek       | GL702ZC                     | [9764417bf8](https://linux-hardware.org/?probe=9764417bf8) | May 24, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [d03d942df4](https://linux-hardware.org/?probe=d03d942df4) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [4c512786cc](https://linux-hardware.org/?probe=4c512786cc) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [da0b980bc3](https://linux-hardware.org/?probe=da0b980bc3) | May 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0aba7a98b9](https://linux-hardware.org/?probe=0aba7a98b9) | May 24, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [a11fdd0361](https://linux-hardware.org/?probe=a11fdd0361) | May 23, 2023 |
| ASUSTek       | N56VB                       | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d1c4b3ee44](https://linux-hardware.org/?probe=d1c4b3ee44) | May 22, 2023 |
| Acer          | Nitro AN515-52              | [f250413f11](https://linux-hardware.org/?probe=f250413f11) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| HP            | Unknown                     | [8ae91264ca](https://linux-hardware.org/?probe=8ae91264ca) | May 19, 2023 |
| HP            | Pavilion Notebook           | [73d62695e4](https://linux-hardware.org/?probe=73d62695e4) | May 18, 2023 |
| Acer          | Aspire E5-521               | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| HP            | Pavilion Notebook           | [56aa17165e](https://linux-hardware.org/?probe=56aa17165e) | May 18, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [7df5747f30](https://linux-hardware.org/?probe=7df5747f30) | May 18, 2023 |
| HUAWEI        | KLVL-WXXW                   | [72b5dfc390](https://linux-hardware.org/?probe=72b5dfc390) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | [d7e4640b82](https://linux-hardware.org/?probe=d7e4640b82) | May 15, 2023 |
| ASUSTek       | X541UJ                      | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| ASUSTek       | N56VB                       | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Valve         | Jupiter                     | [9a9b88a86c](https://linux-hardware.org/?probe=9a9b88a86c) | May 14, 2023 |
| Apple         | MacBookPro11,2              | [a2199ee2c6](https://linux-hardware.org/?probe=a2199ee2c6) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [38acb76489](https://linux-hardware.org/?probe=38acb76489) | May 11, 2023 |
| HP            | G62                         | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Dell          | Latitude 5420               | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| Sony          | VGN-FZ31Z                   | [6fe358200a](https://linux-hardware.org/?probe=6fe358200a) | May 09, 2023 |
| Lenovo        | G50-70 20351                | [70c3231200](https://linux-hardware.org/?probe=70c3231200) | May 07, 2023 |
| Notebook      | N141CU                      | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| Acer          | Aspire E5-523G              | [7a77c66c97](https://linux-hardware.org/?probe=7a77c66c97) | May 06, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [678b4ca4ed](https://linux-hardware.org/?probe=678b4ca4ed) | May 06, 2023 |
| Valve         | Jupiter                     | [04f1f6146c](https://linux-hardware.org/?probe=04f1f6146c) | May 04, 2023 |
| Dell          | Precision 5540              | [3139d97ce0](https://linux-hardware.org/?probe=3139d97ce0) | May 04, 2023 |
| Toshiba       | PORTEGE Z830                | [a8cc4a63c2](https://linux-hardware.org/?probe=a8cc4a63c2) | May 03, 2023 |
| HP            | Unknown                     | [4d0dc62d87](https://linux-hardware.org/?probe=4d0dc62d87) | May 03, 2023 |
| HP            | Unknown                     | [95bbd82535](https://linux-hardware.org/?probe=95bbd82535) | May 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3e8baa565](https://linux-hardware.org/?probe=f3e8baa565) | May 01, 2023 |
| HUAWEI        | RLEF-XX                     | [168396ff77](https://linux-hardware.org/?probe=168396ff77) | May 01, 2023 |
| HUAWEI        | RLEF-XX                     | [b7ca4beb49](https://linux-hardware.org/?probe=b7ca4beb49) | Apr 30, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d4cfc1e964](https://linux-hardware.org/?probe=d4cfc1e964) | Apr 30, 2023 |
| ASUSTek       | X542URR                     | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| Dell          | Inspiron 5521               | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 850 G5            | [ba9bbe1e70](https://linux-hardware.org/?probe=ba9bbe1e70) | Apr 21, 2023 |
| Dell          | Precision 5540              | [66b58fad6c](https://linux-hardware.org/?probe=66b58fad6c) | Apr 19, 2023 |
| Dell          | Precision 5540              | [e114fb911c](https://linux-hardware.org/?probe=e114fb911c) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [b4c6c1198f](https://linux-hardware.org/?probe=b4c6c1198f) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a2b27dd2d6](https://linux-hardware.org/?probe=a2b27dd2d6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [14517ef743](https://linux-hardware.org/?probe=14517ef743) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [b054f2bcd1](https://linux-hardware.org/?probe=b054f2bcd1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [238037e4b8](https://linux-hardware.org/?probe=238037e4b8) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [69f8d7dfdf](https://linux-hardware.org/?probe=69f8d7dfdf) | Apr 11, 2023 |
| Chuwi         | GemiBook Pro                | [e0f6223c25](https://linux-hardware.org/?probe=e0f6223c25) | Apr 10, 2023 |
| Chuwi         | GemiBook Pro                | [cb009d5401](https://linux-hardware.org/?probe=cb009d5401) | Apr 10, 2023 |
| Chuwi         | GemiBook Pro                | [617f2a18bb](https://linux-hardware.org/?probe=617f2a18bb) | Apr 09, 2023 |
| Chuwi         | GemiBook Pro                | [5ff7c0183d](https://linux-hardware.org/?probe=5ff7c0183d) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK E751               | [0bdc444de8](https://linux-hardware.org/?probe=0bdc444de8) | Apr 05, 2023 |
| Dell          | Latitude 5430               | [6494113c9b](https://linux-hardware.org/?probe=6494113c9b) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [1da5570114](https://linux-hardware.org/?probe=1da5570114) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a1fa08efc6](https://linux-hardware.org/?probe=a1fa08efc6) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | [e9988edacd](https://linux-hardware.org/?probe=e9988edacd) | Mar 30, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Acer          | Nitro AN515-45              | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [b7a0579d38](https://linux-hardware.org/?probe=b7a0579d38) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [88d5c3bb9f](https://linux-hardware.org/?probe=88d5c3bb9f) | Mar 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d7b0ec58d5](https://linux-hardware.org/?probe=d7b0ec58d5) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f13da06079](https://linux-hardware.org/?probe=f13da06079) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [48370f2817](https://linux-hardware.org/?probe=48370f2817) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| ASUSTek       | X202EV                      | [db21e9ac28](https://linux-hardware.org/?probe=db21e9ac28) | Mar 13, 2023 |
| HP            | ENVY Notebook               | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| MSI           | GF65 Thin 9SD               | [ea69b96e55](https://linux-hardware.org/?probe=ea69b96e55) | Mar 09, 2023 |
| Dell          | Latitude E4310              | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude E5570              | [5a5d668611](https://linux-hardware.org/?probe=5a5d668611) | Mar 07, 2023 |
| MSI           | GF72 8RD                    | [54eb266d2a](https://linux-hardware.org/?probe=54eb266d2a) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [26b308e28a](https://linux-hardware.org/?probe=26b308e28a) | Mar 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [73c765dbe2](https://linux-hardware.org/?probe=73c765dbe2) | Mar 01, 2023 |
| Lenovo        | ThinkPad T480 20L6SEH700    | [4a187e016b](https://linux-hardware.org/?probe=4a187e016b) | Feb 27, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [7b59cbd067](https://linux-hardware.org/?probe=7b59cbd067) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d99e163be6](https://linux-hardware.org/?probe=d99e163be6) | Feb 24, 2023 |
| HP            | mt40                        | [16e5f8eb5d](https://linux-hardware.org/?probe=16e5f8eb5d) | Feb 23, 2023 |
| MSI           | GF72 8RD                    | [cf6dad63da](https://linux-hardware.org/?probe=cf6dad63da) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| HUAWEI        | BOHB-WAX9                   | [387aa81d4c](https://linux-hardware.org/?probe=387aa81d4c) | Feb 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | [ebaa8145e1](https://linux-hardware.org/?probe=ebaa8145e1) | Feb 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [bb1c4209c7](https://linux-hardware.org/?probe=bb1c4209c7) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [ef69c22820](https://linux-hardware.org/?probe=ef69c22820) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [4e6c625797](https://linux-hardware.org/?probe=4e6c625797) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Toshiba       | Satellite L500              | [da3617cc40](https://linux-hardware.org/?probe=da3617cc40) | Feb 14, 2023 |
| Gigabyte      | P65                         | [b3d7faba21](https://linux-hardware.org/?probe=b3d7faba21) | Feb 12, 2023 |
| Gigabyte      | P65                         | [25d871afca](https://linux-hardware.org/?probe=25d871afca) | Feb 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [b6b590fcdf](https://linux-hardware.org/?probe=b6b590fcdf) | Feb 11, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| HP            | ProBook 640 G1              | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| Acer          | Aspire S7-391               | [3777a7d1e9](https://linux-hardware.org/?probe=3777a7d1e9) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| Acer          | Aspire V3-572G              | [7b48d97053](https://linux-hardware.org/?probe=7b48d97053) | Feb 07, 2023 |
| Toshiba       | Satellite C660              | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Dell          | Precision 7550              | [9608ff008d](https://linux-hardware.org/?probe=9608ff008d) | Feb 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e3ab731c3c](https://linux-hardware.org/?probe=e3ab731c3c) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| ASUSTek       | X555LD                      | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| INSYS         | GW1-W149                    | [5a4337006d](https://linux-hardware.org/?probe=5a4337006d) | Jan 28, 2023 |
| Acer          | Aspire 7750G                | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| ASUSTek       | X541UJ                      | [d9ceb3c732](https://linux-hardware.org/?probe=d9ceb3c732) | Jan 27, 2023 |
| HP            | ProBook 640 G2              | [4e8cd1aa46](https://linux-hardware.org/?probe=4e8cd1aa46) | Jan 26, 2023 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [a9567dc72b](https://linux-hardware.org/?probe=a9567dc72b) | Jan 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| ASUSTek       | UX360CA                     | [98fa78d117](https://linux-hardware.org/?probe=98fa78d117) | Jan 22, 2023 |
| Acer          | Aspire E1-522               | [ad5202642a](https://linux-hardware.org/?probe=ad5202642a) | Jan 22, 2023 |
| Chuwi         | GemiBook Pro                | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| Apple         | MacBookPro6,2               | [95074766b9](https://linux-hardware.org/?probe=95074766b9) | Jan 18, 2023 |
| Acer          | Predator PH315-51           | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| ASUSTek       | X541UV                      | [d45c8ef0ac](https://linux-hardware.org/?probe=d45c8ef0ac) | Jan 13, 2023 |
| Acer          | Aspire V5-122               | [a25a7c3fb1](https://linux-hardware.org/?probe=a25a7c3fb1) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Aspire 5742G                | [07f15478a7](https://linux-hardware.org/?probe=07f15478a7) | Jan 11, 2023 |
| Unknown       | Unknown                     | [ce97b4a08f](https://linux-hardware.org/?probe=ce97b4a08f) | Jan 08, 2023 |
| ASUSTek       | GL753VE                     | [7e0d372f98](https://linux-hardware.org/?probe=7e0d372f98) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50d2637c41](https://linux-hardware.org/?probe=50d2637c41) | Jan 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| HP            | Pavilion dv6                | [9f0fb0adf5](https://linux-hardware.org/?probe=9f0fb0adf5) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Acer          | Aspire 4310                 | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [113a2a45b2](https://linux-hardware.org/?probe=113a2a45b2) | Jan 01, 2023 |
| Toshiba       | Satellite L775-12V          | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| Dell          | Latitude E4310              | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Dell          | XPS 13 9370                 | [982f470134](https://linux-hardware.org/?probe=982f470134) | Dec 21, 2022 |
| Dell          | Latitude E4310              | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Dell          | Inspiron N5050              | [41fb3c537a](https://linux-hardware.org/?probe=41fb3c537a) | Dec 19, 2022 |
| Thomson       | PT-NEO14A.2WH32             | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Sony          | VGN-FZ31Z                   | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [8008043900](https://linux-hardware.org/?probe=8008043900) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Acer          | Aspire A315-55G             | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| MSI           | GF72 8RD                    | [f943786d2c](https://linux-hardware.org/?probe=f943786d2c) | Dec 09, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| HP            | Pavilion dv6                | [8a940a493b](https://linux-hardware.org/?probe=8a940a493b) | Dec 03, 2022 |
| MSI           | GF72 8RD                    | [c03f783ea5](https://linux-hardware.org/?probe=c03f783ea5) | Dec 01, 2022 |
| Acer          | Nitro AN515-58              | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| MSI           | GF72 8RD                    | [fb92041c1b](https://linux-hardware.org/?probe=fb92041c1b) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| ASUSTek       | F7SR                        | [ecdba533ea](https://linux-hardware.org/?probe=ecdba533ea) | Nov 25, 2022 |
| ASUSTek       | F7SR                        | [8102d8b361](https://linux-hardware.org/?probe=8102d8b361) | Nov 25, 2022 |
| MSI           | Summit E16Flip A12UCT       | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [2de63dfd54](https://linux-hardware.org/?probe=2de63dfd54) | Nov 23, 2022 |
| HUAWEI        | BOD-WXX9                    | [814f45a510](https://linux-hardware.org/?probe=814f45a510) | Nov 23, 2022 |
| Apple         | MacBookAir5,1               | [2ded48104d](https://linux-hardware.org/?probe=2ded48104d) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| Acer          | Popcorn                     | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Dell          | XPS 13 9360                 | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [02c6e2e360](https://linux-hardware.org/?probe=02c6e2e360) | Nov 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [d4c27f1388](https://linux-hardware.org/?probe=d4c27f1388) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [0401b9e939](https://linux-hardware.org/?probe=0401b9e939) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| ASUSTek       | G752VS                      | [364d6d09ab](https://linux-hardware.org/?probe=364d6d09ab) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [c54708e797](https://linux-hardware.org/?probe=c54708e797) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [e54df5cb0d](https://linux-hardware.org/?probe=e54df5cb0d) | Nov 13, 2022 |
| ASUSTek       | A6JC                        | [dce6c2a8f4](https://linux-hardware.org/?probe=dce6c2a8f4) | Nov 13, 2022 |
| Packard Be... | EasyNote LV11HC             | [244d508935](https://linux-hardware.org/?probe=244d508935) | Nov 12, 2022 |
| HUAWEI        | HVY-WXX9                    | [c1f18206f4](https://linux-hardware.org/?probe=c1f18206f4) | Nov 11, 2022 |
| eMachines     | G525                        | [38b8684942](https://linux-hardware.org/?probe=38b8684942) | Nov 10, 2022 |
| ASUSTek       | N61Vg                       | [5205b24cb0](https://linux-hardware.org/?probe=5205b24cb0) | Nov 08, 2022 |
| Dell          | Latitude E6510              | [befb811cfe](https://linux-hardware.org/?probe=befb811cfe) | Nov 05, 2022 |
| Acer          | Nitro AN515-55              | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| ASUSTek       | N61Vg                       | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| Dell          | Latitude E6510              | [b346d71347](https://linux-hardware.org/?probe=b346d71347) | Oct 29, 2022 |
| Acer          | Aspire SW5-012              | [90dd31edc8](https://linux-hardware.org/?probe=90dd31edc8) | Oct 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Acer          | Aspire ES1-131              | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| Dell          | Latitude 7320               | [f249267def](https://linux-hardware.org/?probe=f249267def) | Oct 26, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [8ebb941ac6](https://linux-hardware.org/?probe=8ebb941ac6) | Oct 26, 2022 |
| ASUSTek       | X542URR                     | [fe6fb20830](https://linux-hardware.org/?probe=fe6fb20830) | Oct 25, 2022 |
| Toshiba       | NB300                       | [c5aa7d3c5f](https://linux-hardware.org/?probe=c5aa7d3c5f) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| Apple         | MacBookPro10,1              | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| HP            | G62                         | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [e5f7b07e9c](https://linux-hardware.org/?probe=e5f7b07e9c) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [25bb674789](https://linux-hardware.org/?probe=25bb674789) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| ASUSTek       | X541UV                      | [ba7c1c3d83](https://linux-hardware.org/?probe=ba7c1c3d83) | Oct 14, 2022 |
| Toshiba       | Satellite L650              | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| HP            | EliteBook 840 G2            | [d83c027361](https://linux-hardware.org/?probe=d83c027361) | Oct 12, 2022 |
| ASUSTek       | N53SV                       | [2460d79ba8](https://linux-hardware.org/?probe=2460d79ba8) | Oct 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [184ecb5e76](https://linux-hardware.org/?probe=184ecb5e76) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [a3d3100ffa](https://linux-hardware.org/?probe=a3d3100ffa) | Oct 05, 2022 |
| Acer          | Aspire ES1-520              | [b50cfdccab](https://linux-hardware.org/?probe=b50cfdccab) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| HP            | ENVY 15                     | [950623d8b2](https://linux-hardware.org/?probe=950623d8b2) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d9a196cd8e](https://linux-hardware.org/?probe=d9a196cd8e) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | [5c5666fa97](https://linux-hardware.org/?probe=5c5666fa97) | Sep 29, 2022 |
| GIADA         | ChiefRiver Platform         | [d0f71cdc7f](https://linux-hardware.org/?probe=d0f71cdc7f) | Sep 26, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [84d47822bf](https://linux-hardware.org/?probe=84d47822bf) | Sep 24, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [3afd2e892b](https://linux-hardware.org/?probe=3afd2e892b) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | [2f1fe986d8](https://linux-hardware.org/?probe=2f1fe986d8) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [910b604abc](https://linux-hardware.org/?probe=910b604abc) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Toshiba       | Satellite P845T             | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [dd6d053ae2](https://linux-hardware.org/?probe=dd6d053ae2) | Sep 17, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| ASUSTek       | X555LJ                      | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Lenovo        | ThinkPad W540 20BG0016US    | [9f0543edc4](https://linux-hardware.org/?probe=9f0543edc4) | Sep 11, 2022 |
| Chuwi         | CoreBook X                  | [4f29128588](https://linux-hardware.org/?probe=4f29128588) | Sep 11, 2022 |
| System76      | Oryx Pro                    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ab939db2c0](https://linux-hardware.org/?probe=ab939db2c0) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f9604390e8](https://linux-hardware.org/?probe=f9604390e8) | Sep 10, 2022 |
| HP            | EliteBook 840 G6            | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| HP            | Pavilion g6                 | [770b1a8154](https://linux-hardware.org/?probe=770b1a8154) | Sep 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| Sony          | VGN-FZ31Z                   | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [a74d79fc0b](https://linux-hardware.org/?probe=a74d79fc0b) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| ASUSTek       | X541UJ                      | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [11efd3dbe0](https://linux-hardware.org/?probe=11efd3dbe0) | Aug 30, 2022 |
| Toshiba       | Satellite A300              | [f90886ae85](https://linux-hardware.org/?probe=f90886ae85) | Aug 30, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [73db272ecb](https://linux-hardware.org/?probe=73db272ecb) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| HP            | Laptop 15s-fq2xxx           | [8ffebf0c43](https://linux-hardware.org/?probe=8ffebf0c43) | Aug 26, 2022 |
| ASUSTek       | N61Vg                       | [30be913709](https://linux-hardware.org/?probe=30be913709) | Aug 25, 2022 |
| HP            | ProBook 640 G2              | [fc50d4e200](https://linux-hardware.org/?probe=fc50d4e200) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [69c8e5eedc](https://linux-hardware.org/?probe=69c8e5eedc) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [2bf774fae7](https://linux-hardware.org/?probe=2bf774fae7) | Aug 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| ASUSTek       | N53SN                       | [6cb4ac4247](https://linux-hardware.org/?probe=6cb4ac4247) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [73a3d7c1cf](https://linux-hardware.org/?probe=73a3d7c1cf) | Aug 12, 2022 |
| MSI           | Modern 14 A10RB             | [9979c66e3e](https://linux-hardware.org/?probe=9979c66e3e) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| Apple         | MacBookAir6,1               | [154468415c](https://linux-hardware.org/?probe=154468415c) | Aug 05, 2022 |
| Apple         | MacBookAir6,1               | [6f355de994](https://linux-hardware.org/?probe=6f355de994) | Aug 04, 2022 |
| Toshiba       | Satellite U840              | [5ebf9417bf](https://linux-hardware.org/?probe=5ebf9417bf) | Aug 04, 2022 |
| MSI           | Modern 14 A10RB             | [abf1fcf08b](https://linux-hardware.org/?probe=abf1fcf08b) | Aug 02, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | [c6ce2d4317](https://linux-hardware.org/?probe=c6ce2d4317) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | [eca5fa0c39](https://linux-hardware.org/?probe=eca5fa0c39) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [bc5b132a8d](https://linux-hardware.org/?probe=bc5b132a8d) | Jul 29, 2022 |
| Toshiba       | Satellite U840              | [c3f00f5b90](https://linux-hardware.org/?probe=c3f00f5b90) | Jul 29, 2022 |
| ASUSTek       | N53SN                       | [2e35ef4a8a](https://linux-hardware.org/?probe=2e35ef4a8a) | Jul 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e95cafce19](https://linux-hardware.org/?probe=e95cafce19) | Jul 26, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [ae16c8863a](https://linux-hardware.org/?probe=ae16c8863a) | Jul 25, 2022 |
| ASUSTek       | X540LJ                      | [264bb2f2a1](https://linux-hardware.org/?probe=264bb2f2a1) | Jul 23, 2022 |
| ASUSTek       | X540LJ                      | [fc5c252e6e](https://linux-hardware.org/?probe=fc5c252e6e) | Jul 23, 2022 |
| Acer          | Aspire A515-45              | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| Dell          | XPS 15 7590                 | [528f562110](https://linux-hardware.org/?probe=528f562110) | Jul 18, 2022 |
| Packard Be... | EasyNote LV11HC             | [c0693d5f9a](https://linux-hardware.org/?probe=c0693d5f9a) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Sony          | VPCEB3L1E                   | [310a2ada05](https://linux-hardware.org/?probe=310a2ada05) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | [247411abde](https://linux-hardware.org/?probe=247411abde) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | [9af59fca26](https://linux-hardware.org/?probe=9af59fca26) | Jul 08, 2022 |
| ASUSTek       | X540LJ                      | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Sony          | VGN-FZ31Z                   | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Acer          | Aspire A515-54G             | [c0975c6877](https://linux-hardware.org/?probe=c0975c6877) | Jul 02, 2022 |
| ASUSTek       | N61Jq                       | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| Acer          | Aspire A515-54G             | [92d695d6be](https://linux-hardware.org/?probe=92d695d6be) | Jul 02, 2022 |
| HP            | EliteBook 840 G1            | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [91c5f849c5](https://linux-hardware.org/?probe=91c5f849c5) | Jun 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [17cb04c5f5](https://linux-hardware.org/?probe=17cb04c5f5) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Sony          | VPCEH2J1E                   | [7dde3ae196](https://linux-hardware.org/?probe=7dde3ae196) | Jun 23, 2022 |
| HP            | EliteBook 820 G1            | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [fd65aaa4b3](https://linux-hardware.org/?probe=fd65aaa4b3) | Jun 21, 2022 |
| Toshiba       | NB305                       | [1280ac15ba](https://linux-hardware.org/?probe=1280ac15ba) | Jun 17, 2022 |
| HP            | Pavilion Notebook           | [d9b85c0e15](https://linux-hardware.org/?probe=d9b85c0e15) | Jun 16, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [4b1946451e](https://linux-hardware.org/?probe=4b1946451e) | Jun 15, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [35dc89f7ff](https://linux-hardware.org/?probe=35dc89f7ff) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| Toshiba       | Satellite T130              | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| Sony          | VGN-FZ31Z                   | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Dell          | Latitude E6400              | [67a5bdc1aa](https://linux-hardware.org/?probe=67a5bdc1aa) | Jun 04, 2022 |
| HP            | Compaq nx7300 (RU464EA#A... | [a44ec57985](https://linux-hardware.org/?probe=a44ec57985) | Jun 02, 2022 |
| HP            | EliteBook 840 G2            | [8aff04335d](https://linux-hardware.org/?probe=8aff04335d) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [029a55ffb4](https://linux-hardware.org/?probe=029a55ffb4) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| Lenovo        | ThinkPad T530 2394C98       | [b5aebb2490](https://linux-hardware.org/?probe=b5aebb2490) | May 30, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [f47dbc0616](https://linux-hardware.org/?probe=f47dbc0616) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e72ac27af1](https://linux-hardware.org/?probe=e72ac27af1) | May 30, 2022 |
| Acer          | Swift SF314-54              | [eb522816a1](https://linux-hardware.org/?probe=eb522816a1) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [9e1d2f7e8a](https://linux-hardware.org/?probe=9e1d2f7e8a) | May 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [533beb13eb](https://linux-hardware.org/?probe=533beb13eb) | May 26, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| HP            | EliteBook 8540w             | [2f973c22ec](https://linux-hardware.org/?probe=2f973c22ec) | May 19, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1ef52e97fa](https://linux-hardware.org/?probe=1ef52e97fa) | May 18, 2022 |
| Apple         | MacBookAir7,2               | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| Notebook      | NB50TJ1_TK1                 | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [58f371c0d7](https://linux-hardware.org/?probe=58f371c0d7) | May 13, 2022 |
| Lenovo        | ThinkPad X61 7673AQ5        | [42a17c86f4](https://linux-hardware.org/?probe=42a17c86f4) | May 13, 2022 |
| MSI           | GT72VR 6RD                  | [c4cf6c9cd0](https://linux-hardware.org/?probe=c4cf6c9cd0) | May 12, 2022 |
| MSI           | Modern 15 A10RAS            | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion g6                 | [69406bff46](https://linux-hardware.org/?probe=69406bff46) | May 08, 2022 |
| HP            | Pavilion g6                 | [56ca785331](https://linux-hardware.org/?probe=56ca785331) | May 08, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [d24187e845](https://linux-hardware.org/?probe=d24187e845) | May 05, 2022 |
| HP            | ProBook 640 G2              | [50ccff3e1a](https://linux-hardware.org/?probe=50ccff3e1a) | May 04, 2022 |
| ASUSTek       | X540SAA                     | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| HP            | EliteBook 840 G5            | [47aaf6f556](https://linux-hardware.org/?probe=47aaf6f556) | May 04, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [0a6358dc13](https://linux-hardware.org/?probe=0a6358dc13) | May 03, 2022 |
| Sony          | VGN-FZ31Z                   | [ebe91972ba](https://linux-hardware.org/?probe=ebe91972ba) | May 01, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [96dbfb494e](https://linux-hardware.org/?probe=96dbfb494e) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| Lenovo        | G50-45 80E3                 | [910267bbd5](https://linux-hardware.org/?probe=910267bbd5) | Apr 28, 2022 |
| Lenovo        | G50-45 80E3                 | [22dd67107b](https://linux-hardware.org/?probe=22dd67107b) | Apr 28, 2022 |
| HP            | Laptop 15s-fq2xxx           | [91c7a6b5a0](https://linux-hardware.org/?probe=91c7a6b5a0) | Apr 27, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [9e591226b7](https://linux-hardware.org/?probe=9e591226b7) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [5c309ec35d](https://linux-hardware.org/?probe=5c309ec35d) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [710ddc650e](https://linux-hardware.org/?probe=710ddc650e) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Apple         | MacBookPro7,1               | [2641eee3f1](https://linux-hardware.org/?probe=2641eee3f1) | Apr 21, 2022 |
| ASUSTek       | X102BA                      | [00fbb5cbff](https://linux-hardware.org/?probe=00fbb5cbff) | Apr 20, 2022 |
| Lenovo        | ThinkPad L390 20NR001EPG    | [d83b89a414](https://linux-hardware.org/?probe=d83b89a414) | Apr 20, 2022 |
| HP            | Pavilion g6                 | [0c4c081e71](https://linux-hardware.org/?probe=0c4c081e71) | Apr 17, 2022 |
| Toshiba       | Satellite L775-151          | [957020b872](https://linux-hardware.org/?probe=957020b872) | Apr 16, 2022 |
| Toshiba       | Satellite L775-151          | [706f14a3e6](https://linux-hardware.org/?probe=706f14a3e6) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | [a9407bd227](https://linux-hardware.org/?probe=a9407bd227) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | [7403ce7189](https://linux-hardware.org/?probe=7403ce7189) | Apr 16, 2022 |
| Toshiba       | Satellite L300              | [242592fee5](https://linux-hardware.org/?probe=242592fee5) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Toshiba       | Satellite P70-B             | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [bc22c713a7](https://linux-hardware.org/?probe=bc22c713a7) | Apr 13, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [fba984b898](https://linux-hardware.org/?probe=fba984b898) | Apr 11, 2022 |
| Positivo      | H14BU08                     | [11014257c0](https://linux-hardware.org/?probe=11014257c0) | Apr 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4ca643452e](https://linux-hardware.org/?probe=4ca643452e) | Apr 10, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8adf631258](https://linux-hardware.org/?probe=8adf631258) | Apr 08, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [00c3a80eb1](https://linux-hardware.org/?probe=00c3a80eb1) | Apr 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ec5daa2c06](https://linux-hardware.org/?probe=ec5daa2c06) | Apr 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [191c569aa7](https://linux-hardware.org/?probe=191c569aa7) | Apr 05, 2022 |
| ASUSTek       | T100TA                      | [dbfc15621f](https://linux-hardware.org/?probe=dbfc15621f) | Apr 04, 2022 |
| ASUSTek       | X555LJ                      | [f9bbaea819](https://linux-hardware.org/?probe=f9bbaea819) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | [944f40aa28](https://linux-hardware.org/?probe=944f40aa28) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| HP            | Pavilion g6                 | [5dce001675](https://linux-hardware.org/?probe=5dce001675) | Mar 31, 2022 |
| MSI           | Modern 14 B11M              | [3cdc036c09](https://linux-hardware.org/?probe=3cdc036c09) | Mar 30, 2022 |
| Toshiba       | Satellite C660              | [60a6bafd86](https://linux-hardware.org/?probe=60a6bafd86) | Mar 30, 2022 |
| Fujitsu       | LIFEBOOK S752               | [73c18f75a9](https://linux-hardware.org/?probe=73c18f75a9) | Mar 29, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [41870b3fdb](https://linux-hardware.org/?probe=41870b3fdb) | Mar 28, 2022 |
| ASUSTek       | T100TA                      | [fa6858ef16](https://linux-hardware.org/?probe=fa6858ef16) | Mar 28, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [fc92c7a9d2](https://linux-hardware.org/?probe=fc92c7a9d2) | Mar 28, 2022 |
| ASUSTek       | GL552VW                     | [7e8bfac4b7](https://linux-hardware.org/?probe=7e8bfac4b7) | Mar 27, 2022 |
| MSI           | GL65 Leopard 10SFK          | [96afe8ccf1](https://linux-hardware.org/?probe=96afe8ccf1) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | [a2921a6b4c](https://linux-hardware.org/?probe=a2921a6b4c) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | [ca5720c46b](https://linux-hardware.org/?probe=ca5720c46b) | Mar 25, 2022 |
| Toshiba       | Satellite P50-B-10V         | [1f6acfd782](https://linux-hardware.org/?probe=1f6acfd782) | Mar 24, 2022 |
| ASUSTek       | X510UNR                     | [ab3b8653a6](https://linux-hardware.org/?probe=ab3b8653a6) | Mar 23, 2022 |
| Apple         | MacBookAir3,1               | [482fbd3456](https://linux-hardware.org/?probe=482fbd3456) | Mar 21, 2022 |
| HP            | ProBook 640 G2              | [17ceb0fd9f](https://linux-hardware.org/?probe=17ceb0fd9f) | Mar 19, 2022 |
| ASUSTek       | X541UV                      | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| MSI           | Stealth GS66 12UGS          | [882be4cd35](https://linux-hardware.org/?probe=882be4cd35) | Mar 19, 2022 |
| HP            | ProBook 640 G2              | [9024337e9f](https://linux-hardware.org/?probe=9024337e9f) | Mar 19, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [5b345c55f7](https://linux-hardware.org/?probe=5b345c55f7) | Mar 16, 2022 |
| HP            | 250 G8 Notebook PC          | [90bbda2f8c](https://linux-hardware.org/?probe=90bbda2f8c) | Mar 16, 2022 |
| Acer          | Nitro AN515-54              | [1fea8c1b2b](https://linux-hardware.org/?probe=1fea8c1b2b) | Mar 16, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [fabbaeb1bb](https://linux-hardware.org/?probe=fabbaeb1bb) | Mar 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [3aded823d8](https://linux-hardware.org/?probe=3aded823d8) | Mar 13, 2022 |
| ASUSTek       | ZenBook UX431FA             | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8469a31d58](https://linux-hardware.org/?probe=8469a31d58) | Mar 10, 2022 |
| Sony          | VGN-FZ31Z                   | [17e3cb9771](https://linux-hardware.org/?probe=17e3cb9771) | Mar 10, 2022 |
| ASUSTek       | X541UV                      | [aef8901d13](https://linux-hardware.org/?probe=aef8901d13) | Mar 08, 2022 |
| ASUSTek       | X541UV                      | [6bed69bcdb](https://linux-hardware.org/?probe=6bed69bcdb) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8a4f961472](https://linux-hardware.org/?probe=8a4f961472) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4d33fc28da](https://linux-hardware.org/?probe=4d33fc28da) | Mar 08, 2022 |
| Acer          | Aspire E5-551G              | [18bc15734f](https://linux-hardware.org/?probe=18bc15734f) | Mar 07, 2022 |
| ASUSTek       | X541UV                      | [a90d26bc2d](https://linux-hardware.org/?probe=a90d26bc2d) | Mar 06, 2022 |
| Lenovo        | ThinkPad W541 20EGS03100    | [f7b51cf262](https://linux-hardware.org/?probe=f7b51cf262) | Mar 05, 2022 |
| ASUSTek       | X541UV                      | [b5678eb9d3](https://linux-hardware.org/?probe=b5678eb9d3) | Mar 05, 2022 |
| Apple         | MacBookPro8,3               | [87a5df55b8](https://linux-hardware.org/?probe=87a5df55b8) | Mar 04, 2022 |
| ASUSTek       | T100TA                      | [485c2b3aa7](https://linux-hardware.org/?probe=485c2b3aa7) | Mar 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c1b8c2903d](https://linux-hardware.org/?probe=c1b8c2903d) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | [67241eca45](https://linux-hardware.org/?probe=67241eca45) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | [06455796f9](https://linux-hardware.org/?probe=06455796f9) | Mar 01, 2022 |
| Sony          | VGN-FZ31Z                   | [01b50ec980](https://linux-hardware.org/?probe=01b50ec980) | Mar 01, 2022 |
| Sony          | VGN-FZ31Z                   | [1d156021e3](https://linux-hardware.org/?probe=1d156021e3) | Feb 26, 2022 |
| Sony          | VGN-FZ31Z                   | [b223305dc1](https://linux-hardware.org/?probe=b223305dc1) | Feb 26, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Positivo      | H14BU08                     | [b3cb8e0d72](https://linux-hardware.org/?probe=b3cb8e0d72) | Feb 25, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e72b93aadf](https://linux-hardware.org/?probe=e72b93aadf) | Feb 24, 2022 |
| Apple         | MacBookPro12,1              | [e9d9cfb3e9](https://linux-hardware.org/?probe=e9d9cfb3e9) | Feb 24, 2022 |
| Samsung       | QX310/QX410/QX510/SF310/... | [20b0cf0db9](https://linux-hardware.org/?probe=20b0cf0db9) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [48d36e9bae](https://linux-hardware.org/?probe=48d36e9bae) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [60adc82fb8](https://linux-hardware.org/?probe=60adc82fb8) | Feb 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [cf3e28fb31](https://linux-hardware.org/?probe=cf3e28fb31) | Feb 23, 2022 |
| Apple         | MacBookPro12,1              | [677ffe54b5](https://linux-hardware.org/?probe=677ffe54b5) | Feb 23, 2022 |
| SLIMBOOK      | TITAN                       | [2a35f863c2](https://linux-hardware.org/?probe=2a35f863c2) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [c49acb0edf](https://linux-hardware.org/?probe=c49acb0edf) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [6f13abc9eb](https://linux-hardware.org/?probe=6f13abc9eb) | Feb 21, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [013349e12a](https://linux-hardware.org/?probe=013349e12a) | Feb 19, 2022 |
| HP            | EliteBook 840 G6            | [b6f947ed63](https://linux-hardware.org/?probe=b6f947ed63) | Feb 18, 2022 |
| Dell          | Latitude E6440              | [1d4bac917c](https://linux-hardware.org/?probe=1d4bac917c) | Feb 18, 2022 |
| ASUSTek       | T100TA                      | [9f0a454d8b](https://linux-hardware.org/?probe=9f0a454d8b) | Feb 18, 2022 |
| ASUSTek       | X555LJ                      | [c2f63ae6d7](https://linux-hardware.org/?probe=c2f63ae6d7) | Feb 14, 2022 |
| Acer          | Aspire 5715Z                | [cdd4414bbd](https://linux-hardware.org/?probe=cdd4414bbd) | Feb 13, 2022 |
| Apple         | MacBookPro12,1              | [aeec085062](https://linux-hardware.org/?probe=aeec085062) | Feb 13, 2022 |
| ASUSTek       | X541UV                      | [fb81da9fa5](https://linux-hardware.org/?probe=fb81da9fa5) | Feb 13, 2022 |
| Dell          | Precision 3561              | [23c3392c57](https://linux-hardware.org/?probe=23c3392c57) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6c64279dbc](https://linux-hardware.org/?probe=6c64279dbc) | Feb 12, 2022 |
| ASUSTek       | K50IJ                       | [0dd30d1e7e](https://linux-hardware.org/?probe=0dd30d1e7e) | Feb 11, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| HP            | Compaq Presario CQ60        | [f5d9f92aad](https://linux-hardware.org/?probe=f5d9f92aad) | Feb 09, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [0043180375](https://linux-hardware.org/?probe=0043180375) | Feb 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [70122a3cd0](https://linux-hardware.org/?probe=70122a3cd0) | Feb 07, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6bee100b0a](https://linux-hardware.org/?probe=6bee100b0a) | Feb 06, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [a554a842f7](https://linux-hardware.org/?probe=a554a842f7) | Feb 05, 2022 |
| Dell          | Latitude D630               | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [722271e199](https://linux-hardware.org/?probe=722271e199) | Feb 04, 2022 |
| HP            | Pavilion Notebook           | [62cf8cdd3c](https://linux-hardware.org/?probe=62cf8cdd3c) | Feb 02, 2022 |
| Dell          | Latitude D630               | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| Sony          | VGN-FZ31Z                   | [c3e03d2551](https://linux-hardware.org/?probe=c3e03d2551) | Feb 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [e0c36731ca](https://linux-hardware.org/?probe=e0c36731ca) | Jan 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [b4f3d4f1ee](https://linux-hardware.org/?probe=b4f3d4f1ee) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [77d230b476](https://linux-hardware.org/?probe=77d230b476) | Jan 29, 2022 |
| Acer          | Aspire E5-551G              | [435c894ed4](https://linux-hardware.org/?probe=435c894ed4) | Jan 29, 2022 |
| Toshiba       | Satellite C660              | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| ASUSTek       | N56VZ                       | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX431FA             | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| Apple         | MacBookPro9,2               | [90249388ff](https://linux-hardware.org/?probe=90249388ff) | Jan 22, 2022 |
| Toshiba       | Satellite A200              | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6fd36db1e0](https://linux-hardware.org/?probe=6fd36db1e0) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| Sony          | VGN-FZ31Z                   | [c7f9080e23](https://linux-hardware.org/?probe=c7f9080e23) | Jan 18, 2022 |
| Acer          | Aspire ES1-512              | [ca83027c67](https://linux-hardware.org/?probe=ca83027c67) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b27ed63a97](https://linux-hardware.org/?probe=b27ed63a97) | Jan 16, 2022 |
| Toshiba       | Satellite C660              | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a8ff8d111b](https://linux-hardware.org/?probe=a8ff8d111b) | Jan 11, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [5ba5bfc822](https://linux-hardware.org/?probe=5ba5bfc822) | Jan 11, 2022 |
| HP            | Laptop 15s-fq2xxx           | [468890e10d](https://linux-hardware.org/?probe=468890e10d) | Jan 08, 2022 |
| Sony          | VGN-FZ31Z                   | [7587e6c439](https://linux-hardware.org/?probe=7587e6c439) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [a3194a0ed3](https://linux-hardware.org/?probe=a3194a0ed3) | Jan 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a140e77bfe](https://linux-hardware.org/?probe=a140e77bfe) | Jan 05, 2022 |
| Toshiba       | Satellite L50D-B            | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| HP            | ProBook 4530s               | [c68e298c14](https://linux-hardware.org/?probe=c68e298c14) | Jan 04, 2022 |
| Lenovo        | ThinkPad L530 24791S8       | [030611ecba](https://linux-hardware.org/?probe=030611ecba) | Jan 04, 2022 |
| MSI           | Modern 14 A10RB             | [83285ade95](https://linux-hardware.org/?probe=83285ade95) | Jan 02, 2022 |
| MSI           | Modern 14 A10RB             | [602fe88681](https://linux-hardware.org/?probe=602fe88681) | Jan 02, 2022 |
| Timi          | TM1701                      | [594f40016d](https://linux-hardware.org/?probe=594f40016d) | Jan 02, 2022 |
| ASUSTek       | X542URR                     | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| Dell          | Latitude D420               | [3caac63d5f](https://linux-hardware.org/?probe=3caac63d5f) | Dec 31, 2021 |
| Sony          | VGN-FZ31Z                   | [38b3f4d971](https://linux-hardware.org/?probe=38b3f4d971) | Dec 30, 2021 |
| Sony          | VGN-FZ31Z                   | [d1a2146c05](https://linux-hardware.org/?probe=d1a2146c05) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | [6f891ac715](https://linux-hardware.org/?probe=6f891ac715) | Dec 29, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [d988f944f8](https://linux-hardware.org/?probe=d988f944f8) | Dec 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1daccedded](https://linux-hardware.org/?probe=1daccedded) | Dec 26, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [fe1f7f03e2](https://linux-hardware.org/?probe=fe1f7f03e2) | Dec 21, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [40282bb1fd](https://linux-hardware.org/?probe=40282bb1fd) | Dec 21, 2021 |
| Acer          | Aspire ES1-520              | [7a43d12de6](https://linux-hardware.org/?probe=7a43d12de6) | Dec 20, 2021 |
| ASUSTek       | T100HAN                     | [ad0dc6b737](https://linux-hardware.org/?probe=ad0dc6b737) | Dec 17, 2021 |
| ASUSTek       | T100HAN                     | [67b8998643](https://linux-hardware.org/?probe=67b8998643) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [f9a4ac885d](https://linux-hardware.org/?probe=f9a4ac885d) | Dec 17, 2021 |
| MSI           | Alpha 15 A4DEK              | [0ecac9e450](https://linux-hardware.org/?probe=0ecac9e450) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| MSI           | Alpha 15 A4DEK              | [4b7a0b485e](https://linux-hardware.org/?probe=4b7a0b485e) | Dec 15, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Sony          | VGN-SZ2HP_B                 | [a5d51adfab](https://linux-hardware.org/?probe=a5d51adfab) | Dec 13, 2021 |
| Lenovo        | Z51-70 80K6                 | [3faa0a2aad](https://linux-hardware.org/?probe=3faa0a2aad) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [11fb7ea1d7](https://linux-hardware.org/?probe=11fb7ea1d7) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [23579d8b3a](https://linux-hardware.org/?probe=23579d8b3a) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [66796a4303](https://linux-hardware.org/?probe=66796a4303) | Dec 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1d9d5bfe12](https://linux-hardware.org/?probe=1d9d5bfe12) | Dec 05, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [aa4d4e3b08](https://linux-hardware.org/?probe=aa4d4e3b08) | Dec 04, 2021 |
| Lenovo        | ThinkPad R61 89337HG        | [670c02b990](https://linux-hardware.org/?probe=670c02b990) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [c68a7d50dc](https://linux-hardware.org/?probe=c68a7d50dc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [49055ba417](https://linux-hardware.org/?probe=49055ba417) | Dec 01, 2021 |
| Sony          | VGN-FZ31Z                   | [8e4401834b](https://linux-hardware.org/?probe=8e4401834b) | Dec 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| Packard Be... | EasyNote_MX37-V-101PT       | [6f8e7042c4](https://linux-hardware.org/?probe=6f8e7042c4) | Nov 30, 2021 |
| Acer          | Aspire A315-57G             | [cfc036a421](https://linux-hardware.org/?probe=cfc036a421) | Nov 29, 2021 |
| HP            | OMEN by Laptop              | [4dec490a3f](https://linux-hardware.org/?probe=4dec490a3f) | Nov 29, 2021 |
| Acer          | Aspire E5-521               | [48d70742bb](https://linux-hardware.org/?probe=48d70742bb) | Nov 28, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [1a717e5780](https://linux-hardware.org/?probe=1a717e5780) | Nov 28, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| HP            | Pavilion 15                 | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| HP            | 15 TS                       | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| Clevo         | M7X0SU                      | [a9638079c6](https://linux-hardware.org/?probe=a9638079c6) | Nov 20, 2021 |
| ASUSTek       | UX303LAB                    | [21a3bdf255](https://linux-hardware.org/?probe=21a3bdf255) | Nov 19, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [8fc5db0cd9](https://linux-hardware.org/?probe=8fc5db0cd9) | Nov 17, 2021 |
| Sony          | VGN-FZ31Z                   | [2c4fd499c5](https://linux-hardware.org/?probe=2c4fd499c5) | Nov 17, 2021 |
| HP            | Pavilion dv6                | [3f54f48e23](https://linux-hardware.org/?probe=3f54f48e23) | Nov 17, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [5f28060674](https://linux-hardware.org/?probe=5f28060674) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [72e7bebf84](https://linux-hardware.org/?probe=72e7bebf84) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [39d8ea222a](https://linux-hardware.org/?probe=39d8ea222a) | Nov 16, 2021 |
| HUAWEI        | WRT-WX9                     | [6c0ee3ae74](https://linux-hardware.org/?probe=6c0ee3ae74) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [be61c60b41](https://linux-hardware.org/?probe=be61c60b41) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [9fa65491aa](https://linux-hardware.org/?probe=9fa65491aa) | Nov 12, 2021 |
| ASUSTek       | X202EV                      | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| Sony          | VGN-FZ31Z                   | [fe8ba3f801](https://linux-hardware.org/?probe=fe8ba3f801) | Nov 11, 2021 |
| ASUSTek       | T102HA                      | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| Lenovo        | ThinkPad T420 4177Q5U       | [02ce053478](https://linux-hardware.org/?probe=02ce053478) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [c13d42cb63](https://linux-hardware.org/?probe=c13d42cb63) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [8403f5c97f](https://linux-hardware.org/?probe=8403f5c97f) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| HP            | G62                         | [a4a0360f3a](https://linux-hardware.org/?probe=a4a0360f3a) | Nov 06, 2021 |
| HP            | G62                         | [cd87bfa19b](https://linux-hardware.org/?probe=cd87bfa19b) | Nov 06, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [87daccdc88](https://linux-hardware.org/?probe=87daccdc88) | Nov 05, 2021 |
| HP            | OMEN by Laptop              | [0b933dd493](https://linux-hardware.org/?probe=0b933dd493) | Nov 03, 2021 |
| Toshiba       | Satellite C660              | [c22b81abd4](https://linux-hardware.org/?probe=c22b81abd4) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | [bbe04676c1](https://linux-hardware.org/?probe=bbe04676c1) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | [09eba8bb5f](https://linux-hardware.org/?probe=09eba8bb5f) | Nov 02, 2021 |
| Standard      | Unknown                     | [3cccd4bf9f](https://linux-hardware.org/?probe=3cccd4bf9f) | Nov 02, 2021 |
| HP            | ProBook 445 G7              | [ca8418c85b](https://linux-hardware.org/?probe=ca8418c85b) | Nov 02, 2021 |
| Acer          | Aspire E1-570G              | [9c6c7691c9](https://linux-hardware.org/?probe=9c6c7691c9) | Nov 02, 2021 |
| Acer          | Aspire 4732Z                | [7095848f26](https://linux-hardware.org/?probe=7095848f26) | Oct 31, 2021 |
| Acer          | Aspire 4732Z                | [ce23f8d9f9](https://linux-hardware.org/?probe=ce23f8d9f9) | Oct 30, 2021 |
| Standard      | Unknown                     | [1bf7e2da2f](https://linux-hardware.org/?probe=1bf7e2da2f) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [9276790a36](https://linux-hardware.org/?probe=9276790a36) | Oct 28, 2021 |
| Acer          | Aspire 5732Z                | [9d4f7a1a4b](https://linux-hardware.org/?probe=9d4f7a1a4b) | Oct 27, 2021 |
| ASUSTek       | X453MA                      | [4a70424b2f](https://linux-hardware.org/?probe=4a70424b2f) | Oct 27, 2021 |
| ASUSTek       | X540YA                      | [9b382500c5](https://linux-hardware.org/?probe=9b382500c5) | Oct 27, 2021 |
| Dell          | Latitude E5400              | [7049bbe182](https://linux-hardware.org/?probe=7049bbe182) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [4826046b43](https://linux-hardware.org/?probe=4826046b43) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | [b3e2853259](https://linux-hardware.org/?probe=b3e2853259) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | [5af2c96114](https://linux-hardware.org/?probe=5af2c96114) | Oct 24, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [7aac95cd60](https://linux-hardware.org/?probe=7aac95cd60) | Oct 23, 2021 |
| HP            | Notebook                    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| ASUSTek       | X555LD                      | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Lenovo        | ThinkPad T480 20L6S7PE06    | [28857899a2](https://linux-hardware.org/?probe=28857899a2) | Oct 20, 2021 |
| HP            | Compaq Presario CQ60        | [0b02aa22d4](https://linux-hardware.org/?probe=0b02aa22d4) | Oct 17, 2021 |
| HP            | Pavilion x2 Detachable      | [c17c589af5](https://linux-hardware.org/?probe=c17c589af5) | Oct 17, 2021 |
| Toshiba       | Satellite C660              | [c70057c643](https://linux-hardware.org/?probe=c70057c643) | Oct 16, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [6360789a1c](https://linux-hardware.org/?probe=6360789a1c) | Oct 14, 2021 |
| eMachines     | E520 V1.06                  | [97c667e3c0](https://linux-hardware.org/?probe=97c667e3c0) | Oct 14, 2021 |
| HP            | EliteBook 840 G3            | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| HP            | Pavilion g6                 | [5eba384acd](https://linux-hardware.org/?probe=5eba384acd) | Oct 11, 2021 |
| HP            | Notebook                    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [77a6cb9eba](https://linux-hardware.org/?probe=77a6cb9eba) | Oct 07, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [99c08de77b](https://linux-hardware.org/?probe=99c08de77b) | Oct 07, 2021 |
| HP            | G62                         | [6cbed79ca9](https://linux-hardware.org/?probe=6cbed79ca9) | Oct 05, 2021 |
| Dell          | XPS 13 7390                 | [843d9a14d4](https://linux-hardware.org/?probe=843d9a14d4) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | [b1996e39c6](https://linux-hardware.org/?probe=b1996e39c6) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | [47def5d058](https://linux-hardware.org/?probe=47def5d058) | Oct 05, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96cf9ba56a](https://linux-hardware.org/?probe=96cf9ba56a) | Sep 30, 2021 |
| ASUSTek       | X453MA                      | [782dfc1a5f](https://linux-hardware.org/?probe=782dfc1a5f) | Sep 30, 2021 |
| Toshiba       | Satellite L500              | [07116867d0](https://linux-hardware.org/?probe=07116867d0) | Sep 30, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Portugal/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 140       | 10.7%   |
| Ubuntu 22.04                 | 89        | 6.8%    |
| Ubuntu 18.04                 | 87        | 6.65%   |
| Pop!_OS 22.04                | 36        | 2.75%   |
| OpenMandriva 4.3             | 33        | 2.52%   |
| Zorin 16                     | 27        | 2.06%   |
| Arch Rolling                 | 27        | 2.06%   |
| Zorin 15                     | 24        | 1.83%   |
| OpenMandriva 4.2             | 21        | 1.61%   |
| Fedora 38                    | 21        | 1.61%   |
| Debian 11                    | 21        | 1.61%   |
| KDE neon 20.04               | 19        | 1.45%   |
| Pop!_OS 20.04                | 18        | 1.38%   |
| Linux Mint 20.3              | 18        | 1.38%   |
| Debian 10                    | 17        | 1.3%    |
| Fedora 34                    | 16        | 1.22%   |
| Linux Mint 21.2              | 15        | 1.15%   |
| Fedora 39                    | 15        | 1.15%   |
| Ubuntu 19.10                 | 14        | 1.07%   |
| Manjaro                      | 14        | 1.07%   |
| Linux Mint 20.1              | 14        | 1.07%   |
| Debian 12                    | 14        | 1.07%   |
| Pop!_OS 21.04                | 13        | 0.99%   |
| Linux Mint 19.3              | 13        | 0.99%   |
| Arch                         | 13        | 0.99%   |
| Xubuntu 20.04                | 12        | 0.92%   |
| Ubuntu 21.10                 | 12        | 0.92%   |
| Ubuntu 19.04                 | 12        | 0.92%   |
| Pop!_OS 20.10                | 12        | 0.92%   |
| OpenMandriva 4.50            | 12        | 0.92%   |
| Fedora 36                    | 12        | 0.92%   |
| Linux Mint 21.1              | 11        | 0.84%   |
| Linux Mint 21                | 11        | 0.84%   |
| Linux Mint 20                | 11        | 0.84%   |
| Fedora 33                    | 11        | 0.84%   |
| Zorin 17                     | 10        | 0.76%   |
| Xubuntu 18.04                | 10        | 0.76%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.76%   |
| OpenMandriva 23.08           | 10        | 0.76%   |
| OpenMandriva 23.01           | 10        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 377       | 30.55%  |
| Linux Mint       | 109       | 8.83%   |
| OpenMandriva     | 95        | 7.7%    |
| Fedora           | 95        | 7.7%    |
| Pop!_OS          | 87        | 7.05%   |
| Zorin            | 61        | 4.94%   |
| Debian           | 60        | 4.86%   |
| Arch             | 40        | 3.24%   |
| Manjaro          | 37        | 3%      |
| KDE neon         | 33        | 2.67%   |
| Endless          | 32        | 2.59%   |
| Xubuntu          | 24        | 1.94%   |
| Kubuntu          | 16        | 1.3%    |
| Elementary       | 16        | 1.3%    |
| openSUSE         | 14        | 1.13%   |
| ROSA             | 12        | 0.97%   |
| ArcoLinux        | 10        | 0.81%   |
| Kali             | 8         | 0.65%   |
| Ubuntu Unity     | 6         | 0.49%   |
| Ubuntu MATE      | 6         | 0.49%   |
| Slackware        | 6         | 0.49%   |
| NixOS            | 6         | 0.49%   |
| Nobara           | 5         | 0.41%   |
| Lubuntu          | 5         | 0.41%   |
| LMDE             | 5         | 0.41%   |
| Gentoo           | 5         | 0.41%   |
| EndeavourOS      | 5         | 0.41%   |
| Clear Linux      | 5         | 0.41%   |
| Ubuntu Budgie    | 4         | 0.32%   |
| TUXEDO OS        | 4         | 0.32%   |
| SteamOS          | 4         | 0.32%   |
| MX               | 4         | 0.32%   |
| Devuan           | 4         | 0.32%   |
| Parrot           | 3         | 0.24%   |
| Xero             | 2         | 0.16%   |
| Peppermint       | 2         | 0.16%   |
| org.kde.Platform | 2         | 0.16%   |
| Linux Lite       | 2         | 0.16%   |
| Artix            | 2         | 0.16%   |
| Alpine           | 2         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 25        | 1.75%   |
| 5.4.0-42-generic         | 24        | 1.68%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.4%    |
| 5.15.0-56-generic        | 13        | 0.91%   |
| 5.14.14-desktop-1omv4050 | 13        | 0.91%   |
| 5.3.0-46-generic         | 12        | 0.84%   |
| 6.2.6-76060206-generic   | 11        | 0.77%   |
| 5.4.0-29-generic         | 11        | 0.77%   |
| 5.15.0-52-generic        | 11        | 0.77%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.7%    |
| 5.4.0-58-generic         | 10        | 0.7%    |
| 5.4.0-52-generic         | 10        | 0.7%    |
| 5.15.0-48-generic        | 10        | 0.7%    |
| 5.15.0-46-generic        | 10        | 0.7%    |
| 5.11.0-38-generic        | 10        | 0.7%    |
| 5.3.0-28-generic         | 9         | 0.63%   |
| 5.15.0-41-generic        | 9         | 0.63%   |
| 4.18.0-15-generic        | 9         | 0.63%   |
| 6.4.11-desktop-1omv2390  | 8         | 0.56%   |
| 5.4.0-7634-generic       | 8         | 0.56%   |
| 5.4.0-26-generic         | 8         | 0.56%   |
| 5.11.0-43-generic        | 8         | 0.56%   |
| 5.0.0-25-generic         | 8         | 0.56%   |
| 4.18.0-25-generic        | 8         | 0.56%   |
| 6.2.6-desktop-1omv2390   | 7         | 0.49%   |
| 6.2.0-36-generic         | 7         | 0.49%   |
| 6.2.0-26-generic         | 7         | 0.49%   |
| 5.4.0-31-generic         | 7         | 0.49%   |
| 5.19.0-76051900-generic  | 7         | 0.49%   |
| 5.15.0-58-generic        | 7         | 0.49%   |
| 5.13.0-39-generic        | 7         | 0.49%   |
| 5.0.0-37-generic         | 7         | 0.49%   |
| 4.15.0-46-generic        | 7         | 0.49%   |
| 6.5.0-14-generic         | 6         | 0.42%   |
| 6.2.0-39-generic         | 6         | 0.42%   |
| 6.2.0-37-generic         | 6         | 0.42%   |
| 6.2.0-20-generic         | 6         | 0.42%   |
| 6.1.0-13-amd64           | 6         | 0.42%   |
| 5.8.0-63-generic         | 6         | 0.42%   |
| 5.4.0-91-generic         | 6         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 186       | 13.78%  |
| 5.15.0  | 107       | 7.93%   |
| 4.15.0  | 66        | 4.89%   |
| 5.8.0   | 63        | 4.67%   |
| 5.11.0  | 60        | 4.44%   |
| 5.3.0   | 55        | 4.07%   |
| 5.13.0  | 49        | 3.63%   |
| 6.2.0   | 47        | 3.48%   |
| 5.19.0  | 45        | 3.33%   |
| 5.0.0   | 38        | 2.81%   |
| 6.5.0   | 37        | 2.74%   |
| 4.18.0  | 35        | 2.59%   |
| 5.10.0  | 28        | 2.07%   |
| 5.16.7  | 25        | 1.85%   |
| 6.1.0   | 22        | 1.63%   |
| 5.10.14 | 21        | 1.56%   |
| 6.2.6   | 18        | 1.33%   |
| 4.19.0  | 17        | 1.26%   |
| 5.14.14 | 13        | 0.96%   |
| 6.1.1   | 12        | 0.89%   |
| 6.4.11  | 8         | 0.59%   |
| 6.6.2   | 6         | 0.44%   |
| 6.6.10  | 6         | 0.44%   |
| 6.6.15  | 5         | 0.37%   |
| 6.5.6   | 5         | 0.37%   |
| 6.0.12  | 5         | 0.37%   |
| 5.14.0  | 5         | 0.37%   |
| 4.4.0   | 5         | 0.37%   |
| 6.8.7   | 4         | 0.3%    |
| 6.7.9   | 4         | 0.3%    |
| 6.6.3   | 4         | 0.3%    |
| 6.5.5   | 4         | 0.3%    |
| 6.3.8   | 4         | 0.3%    |
| 6.2.15  | 4         | 0.3%    |
| 6.2.14  | 4         | 0.3%    |
| 6.0.0   | 4         | 0.3%    |
| 5.6.0   | 4         | 0.3%    |
| 5.11.12 | 4         | 0.3%    |
| 6.6.13  | 3         | 0.22%   |
| 6.4.8   | 3         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 196       | 14.63%  |
| 5.15    | 134       | 10%     |
| 6.2     | 80        | 5.97%   |
| 5.8     | 77        | 5.75%   |
| 5.11    | 68        | 5.07%   |
| 4.15    | 66        | 4.93%   |
| 5.10    | 64        | 4.78%   |
| 6.5     | 58        | 4.33%   |
| 5.3     | 58        | 4.33%   |
| 5.19    | 58        | 4.33%   |
| 6.1     | 57        | 4.25%   |
| 5.13    | 54        | 4.03%   |
| 5.16    | 44        | 3.28%   |
| 5.0     | 39        | 2.91%   |
| 4.18    | 36        | 2.69%   |
| 6.6     | 35        | 2.61%   |
| 5.14    | 27        | 2.01%   |
| 6.4     | 23        | 1.72%   |
| 6.3     | 21        | 1.57%   |
| 6.0     | 20        | 1.49%   |
| 4.19    | 20        | 1.49%   |
| 5.12    | 16        | 1.19%   |
| 4.9     | 12        | 0.9%    |
| 5.9     | 10        | 0.75%   |
| 5.7     | 10        | 0.75%   |
| 5.6     | 10        | 0.75%   |
| 5.17    | 10        | 0.75%   |
| 6.7     | 7         | 0.52%   |
| 5.18    | 7         | 0.52%   |
| 6.8     | 6         | 0.45%   |
| 5.5     | 6         | 0.45%   |
| 4.4     | 5         | 0.37%   |
| 5.2     | 2         | 0.15%   |
| 4.12    | 1         | 0.07%   |
| 4.1     | 1         | 0.07%   |
| 3.10    | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1143      | 95.97%  |
| i686    | 47        | 3.95%   |
| aarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 579       | 46.39%  |
| KDE5             | 218       | 17.47%  |
| Unknown          | 142       | 11.38%  |
| XFCE             | 89        | 7.13%   |
| X-Cinnamon       | 86        | 6.89%   |
| MATE             | 24        | 1.92%   |
| KDE              | 22        | 1.76%   |
| Pantheon         | 14        | 1.12%   |
| i3               | 12        | 0.96%   |
| Cinnamon         | 10        | 0.8%    |
| KDE4             | 9         | 0.72%   |
| Budgie           | 8         | 0.64%   |
| Unity            | 7         | 0.56%   |
| LXQt             | 7         | 0.56%   |
| LXDE             | 4         | 0.32%   |
| GNOME Flashback  | 3         | 0.24%   |
| Deepin           | 3         | 0.24%   |
| DWM              | 2         | 0.16%   |
| awesome          | 2         | 0.16%   |
| xmonad           | 1         | 0.08%   |
| Openbox          | 1         | 0.08%   |
| lightdm-xsession | 1         | 0.08%   |
| KDE6             | 1         | 0.08%   |
| fluxbox          | 1         | 0.08%   |
| Cutefish         | 1         | 0.08%   |
| bspwm            | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 897       | 73.34%  |
| Wayland | 252       | 20.61%  |
| Unknown | 71        | 5.81%   |
| Tty     | 3         | 0.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 637       | 51.41%  |
| SDDM    | 175       | 14.12%  |
| GDM3    | 162       | 13.08%  |
| GDM     | 120       | 9.69%   |
| LightDM | 102       | 8.23%   |
| TDM     | 28        | 2.26%   |
| KDM     | 9         | 0.73%   |
| XDM     | 3         | 0.24%   |
| SLiM    | 2         | 0.16%   |
| GREETD  | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pt_PT   | 491       | 40.11%  |
| en_US   | 441       | 36.03%  |
| Unknown | 137       | 11.19%  |
| en_GB   | 80        | 6.54%   |
| pt_BR   | 24        | 1.96%   |
| C       | 24        | 1.96%   |
| de_DE   | 6         | 0.49%   |
| fr_FR   | 4         | 0.33%   |
| en_IE   | 4         | 0.33%   |
| POSIX   | 3         | 0.25%   |
| ru_RU   | 2         | 0.16%   |
| it_IT   | 2         | 0.16%   |
| es_ES   | 2         | 0.16%   |
| sk_SK   | 1         | 0.08%   |
| en_IN   | 1         | 0.08%   |
| en_DK   | 1         | 0.08%   |
| Default | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 612       | 50%     |
| EFI  | 612       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 911       | 74.43%  |
| Btrfs    | 124       | 10.13%  |
| Overlay  | 70        | 5.72%   |
| Tmpfs    | 50        | 4.08%   |
| Unknown  | 44        | 3.59%   |
| Xfs      | 10        | 0.82%   |
| Zfs      | 8         | 0.65%   |
| Ext2     | 4         | 0.33%   |
| Ext3     | 2         | 0.16%   |
| Reiserfs | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 666       | 54.5%   |
| GPT     | 451       | 36.91%  |
| MBR     | 105       | 8.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1084      | 89.81%  |
| Yes       | 123       | 10.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 874       | 72.05%  |
| Yes       | 339       | 27.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 226       | 18.99%  |
| Hewlett-Packard     | 226       | 18.99%  |
| ASUSTek Computer    | 203       | 17.06%  |
| Acer                | 111       | 9.33%   |
| Toshiba             | 84        | 7.06%   |
| Dell                | 74        | 6.22%   |
| Sony                | 48        | 4.03%   |
| Apple               | 33        | 2.77%   |
| MSI                 | 30        | 2.52%   |
| HUAWEI              | 25        | 2.1%    |
| Samsung Electronics | 18        | 1.51%   |
| Notebook            | 10        | 0.84%   |
| TUXEDO              | 7         | 0.59%   |
| Fujitsu             | 7         | 0.59%   |
| Packard Bell        | 6         | 0.5%    |
| Chuwi               | 6         | 0.5%    |
| Unknown             | 6         | 0.5%    |
| Gigabyte Technology | 5         | 0.42%   |
| Valve               | 4         | 0.34%   |
| Clevo               | 4         | 0.34%   |
| Teclast             | 3         | 0.25%   |
| SLIMBOOK            | 3         | 0.25%   |
| Phoenix/SiS         | 3         | 0.25%   |
| Medion              | 3         | 0.25%   |
| LG Electronics      | 3         | 0.25%   |
| Intel               | 3         | 0.25%   |
| INSYS               | 3         | 0.25%   |
| eMachines           | 3         | 0.25%   |
| Positivo            | 2         | 0.17%   |
| PC Specialist       | 2         | 0.17%   |
| OBSIDIAN-PC         | 2         | 0.17%   |
| LNV                 | 2         | 0.17%   |
| Jumper              | 2         | 0.17%   |
| Fujitsu Siemens     | 2         | 0.17%   |
| Alienware           | 2         | 0.17%   |
| Timi                | 1         | 0.08%   |
| Thomson             | 1         | 0.08%   |
| System76            | 1         | 0.08%   |
| Standard            | 1         | 0.08%   |
| Schenker            | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Sony VGN-FZ31Z                         | 22        | 1.85%   |
| Lenovo IdeaPad 1 14ADA05 82GW          | 14        | 1.18%   |
| HP Pavilion dv6                        | 10        | 0.84%   |
| Unknown                                | 10        | 0.84%   |
| Lenovo Legion 5 15ACH6H 82JU           | 9         | 0.76%   |
| HP G62                                 | 9         | 0.76%   |
| Toshiba Satellite C660                 | 8         | 0.67%   |
| HP Pavilion g6                         | 8         | 0.67%   |
| HP Notebook                            | 7         | 0.59%   |
| Toshiba Satellite L650                 | 6         | 0.5%    |
| HP Pavilion Notebook                   | 6         | 0.5%    |
| ASUS X555LJ                            | 6         | 0.5%    |
| Lenovo Y520-15IKBN 80WK                | 5         | 0.42%   |
| HP OMEN by Laptop                      | 5         | 0.42%   |
| ASUS X555LD                            | 5         | 0.42%   |
| ASUS X541UV                            | 5         | 0.42%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 5         | 0.42%   |
| ASUS VivoBook 15_ASUS Laptop X507LA    | 5         | 0.42%   |
| Acer Extensa 5620                      | 5         | 0.42%   |
| Acer Aspire ES1-520                    | 5         | 0.42%   |
| Valve Jupiter                          | 4         | 0.34%   |
| Toshiba Satellite L500                 | 4         | 0.34%   |
| Toshiba Satellite L40                  | 4         | 0.34%   |
| Toshiba Satellite A200                 | 4         | 0.34%   |
| Lenovo Legion Y530-15ICH 81FV          | 4         | 0.34%   |
| Lenovo Legion 5 15ARH05H 82B1          | 4         | 0.34%   |
| Lenovo IdeaPad 320-15AST 80XV          | 4         | 0.34%   |
| Lenovo G50-45 80E3                     | 4         | 0.34%   |
| HUAWEI NBLK-WAX9X                      | 4         | 0.34%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 4         | 0.34%   |
| HP Pavilion 15                         | 4         | 0.34%   |
| HP OMEN by Laptop 15-dc0xxx            | 4         | 0.34%   |
| HP Compaq Presario CQ60                | 4         | 0.34%   |
| HP 15                                  | 4         | 0.34%   |
| ASUS X541UJ                            | 4         | 0.34%   |
| Apple MacBookPro8,1                    | 4         | 0.34%   |
| Acer Extensa 5635ZG                    | 4         | 0.34%   |
| Acer Aspire E5-571G                    | 4         | 0.34%   |
| Acer Aspire E5-551G                    | 4         | 0.34%   |
| Toshiba Satellite L50D-B               | 3         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 105       | 8.82%   |
| Acer Aspire           | 87        | 7.31%   |
| Toshiba Satellite     | 73        | 6.13%   |
| HP Pavilion           | 66        | 5.55%   |
| Lenovo IdeaPad        | 64        | 5.38%   |
| ASUS VivoBook         | 44        | 3.7%    |
| Dell Latitude         | 36        | 3.03%   |
| HP EliteBook          | 35        | 2.94%   |
| HP Laptop             | 26        | 2.18%   |
| Lenovo Legion         | 24        | 2.02%   |
| Sony VGN-FZ31Z        | 22        | 1.85%   |
| HP ProBook            | 17        | 1.43%   |
| HP Compaq             | 17        | 1.43%   |
| Dell XPS              | 17        | 1.43%   |
| HP OMEN               | 13        | 1.09%   |
| Dell Inspiron         | 13        | 1.09%   |
| ASUS ZenBook          | 12        | 1.01%   |
| ASUS ROG              | 12        | 1.01%   |
| Unknown               | 10        | 0.84%   |
| HP G62                | 9         | 0.76%   |
| Acer Extensa          | 9         | 0.76%   |
| Lenovo Yoga           | 8         | 0.67%   |
| HP ENVY               | 8         | 0.67%   |
| Acer Nitro            | 8         | 0.67%   |
| HP Notebook           | 7         | 0.59%   |
| Packard Bell EasyNote | 6         | 0.5%    |
| MSI Modern            | 6         | 0.5%    |
| Fujitsu LIFEBOOK      | 6         | 0.5%    |
| Dell Precision        | 6         | 0.5%    |
| ASUS X555LJ           | 6         | 0.5%    |
| ASUS TUF              | 6         | 0.5%    |
| Lenovo Y520-15IKBN    | 5         | 0.42%   |
| Lenovo ThinkBook      | 5         | 0.42%   |
| HP 15                 | 5         | 0.42%   |
| ASUS X555LD           | 5         | 0.42%   |
| ASUS X541UV           | 5         | 0.42%   |
| Apple MacBookPro8     | 5         | 0.42%   |
| Apple MacBookPro11    | 5         | 0.42%   |
| Valve Jupiter         | 4         | 0.34%   |
| Toshiba PORTEGE       | 4         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 110       | 9.24%   |
| 2019    | 97        | 8.15%   |
| 2018    | 97        | 8.15%   |
| 2010    | 88        | 7.39%   |
| 2021    | 85        | 7.14%   |
| 2013    | 76        | 6.39%   |
| 2014    | 71        | 5.97%   |
| 2015    | 69        | 5.8%    |
| 2007    | 67        | 5.63%   |
| 2008    | 66        | 5.55%   |
| 2012    | 60        | 5.04%   |
| 2017    | 59        | 4.96%   |
| 2016    | 57        | 4.79%   |
| 2011    | 54        | 4.54%   |
| 2009    | 48        | 4.03%   |
| 2022    | 46        | 3.87%   |
| 2023    | 20        | 1.68%   |
| 2006    | 10        | 0.84%   |
| 2005    | 7         | 0.59%   |
| Unknown | 3         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1190      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1085      | 89.37%  |
| Enabled  | 129       | 10.63%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1184      | 99.5%   |
| Yes  | 6         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 309       | 25.66%  |
| 3.01-4.0    | 306       | 25.42%  |
| 8.01-16.0   | 207       | 17.19%  |
| 16.01-24.0  | 170       | 14.12%  |
| 32.01-64.0  | 86        | 7.14%   |
| 1.01-2.0    | 72        | 5.98%   |
| 2.01-3.0    | 20        | 1.66%   |
| 64.01-256.0 | 14        | 1.16%   |
| 0.51-1.0    | 11        | 0.91%   |
| 24.01-32.0  | 9         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 459       | 34.69%  |
| 2.01-3.0   | 325       | 24.57%  |
| 4.01-8.0   | 207       | 15.65%  |
| 3.01-4.0   | 167       | 12.62%  |
| 0.51-1.0   | 93        | 7.03%   |
| 8.01-16.0  | 48        | 3.63%   |
| 16.01-24.0 | 10        | 0.76%   |
| 0.01-0.5   | 9         | 0.68%   |
| 24.01-32.0 | 4         | 0.3%    |
| 32.01-64.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 900       | 74.07%  |
| 2      | 259       | 21.32%  |
| 3      | 38        | 3.13%   |
| 0      | 10        | 0.82%   |
| 4      | 6         | 0.49%   |
| 5      | 2         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 794       | 66.55%  |
| Yes       | 399       | 33.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 967       | 80.65%  |
| No        | 232       | 19.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1163      | 97.73%  |
| No        | 27        | 2.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 893       | 74.23%  |
| No        | 310       | 25.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Portugal | 1190      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lisbon                  | 293       | 22.87%  |
| Porto                   | 133       | 10.38%  |
| Funchal                 | 35        | 2.73%   |
| Vila Nova de Gaia       | 32        | 2.5%    |
| Amadora                 | 27        | 2.11%   |
| Coimbra                 | 25        | 1.95%   |
| Aveiro                  | 24        | 1.87%   |
| Braga                   | 21        | 1.64%   |
| Setúbal                | 20        | 1.56%   |
| Cascais                 | 18        | 1.41%   |
| Guimaraes               | 16        | 1.25%   |
| Loures                  | 15        | 1.17%   |
| Almada                  | 14        | 1.09%   |
| Barreiro                | 13        | 1.01%   |
| Leiria                  | 12        | 0.94%   |
| Faro                    | 12        | 0.94%   |
| Bragança               | 11        | 0.86%   |
| Mem Martins             | 10        | 0.78%   |
| Maia                    | 10        | 0.78%   |
| Sintra                  | 9         | 0.7%    |
| Portimao                | 9         | 0.7%    |
| Barcelos                | 9         | 0.7%    |
| Alverca do Ribatejo     | 9         | 0.7%    |
| Viseu                   | 8         | 0.62%   |
| Santo Tirso             | 8         | 0.62%   |
| Santarém               | 8         | 0.62%   |
| Póvoa de Varzim        | 8         | 0.62%   |
| Odivelas                | 8         | 0.62%   |
| Matosinhos Municipality | 8         | 0.62%   |
| Feira                   | 8         | 0.62%   |
| Carnaxide               | 8         | 0.62%   |
| Viana do Castelo        | 7         | 0.55%   |
| Vila do Conde           | 6         | 0.47%   |
| Sao Joao da Madeira     | 6         | 0.47%   |
| Queluz                  | 6         | 0.47%   |
| Palmela                 | 6         | 0.47%   |
| Lagos                   | 6         | 0.47%   |
| Evora                   | 6         | 0.47%   |
| Cacem                   | 6         | 0.47%   |
| Águeda Municipality    | 6         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 225       | 296    | 15.33%  |
| WDC                         | 142       | 187    | 9.67%   |
| Toshiba                     | 142       | 169    | 9.67%   |
| Seagate                     | 136       | 171    | 9.26%   |
| Kingston                    | 106       | 124    | 7.22%   |
| Sandisk                     | 89        | 107    | 6.06%   |
| Unknown                     | 85        | 121    | 5.79%   |
| Crucial                     | 61        | 74     | 4.16%   |
| Hitachi                     | 46        | 49     | 3.13%   |
| HGST                        | 46        | 59     | 3.13%   |
| Intel                       | 45        | 73     | 3.07%   |
| SK hynix                    | 43        | 55     | 2.93%   |
| Micron Technology           | 43        | 49     | 2.93%   |
| Fujitsu                     | 18        | 19     | 1.23%   |
| KIOXIA                      | 16        | 26     | 1.09%   |
| Apple                       | 15        | 17     | 1.02%   |
| S3+                         | 11        | 22     | 0.75%   |
| Phison Electronics          | 11        | 14     | 0.75%   |
| JMicron Technology          | 11        | 12     | 0.75%   |
| China                       | 11        | 13     | 0.75%   |
| GOODRAM                     | 10        | 10     | 0.68%   |
| A-DATA Technology           | 9         | 9      | 0.61%   |
| LITEON                      | 8         | 9      | 0.54%   |
| Kingston Technology Company | 8         | 8      | 0.54%   |
| KIOXIA-EXCERIA              | 7         | 7      | 0.48%   |
| Emtec                       | 7         | 8      | 0.48%   |
| BlueRay                     | 7         | 9      | 0.48%   |
| Unknown                     | 7         | 12     | 0.48%   |
| Transcend                   | 6         | 7      | 0.41%   |
| Phison                      | 6         | 6      | 0.41%   |
| Silicon Motion              | 5         | 7      | 0.34%   |
| USB                         | 4         | 4      | 0.27%   |
| PNY                         | 4         | 5      | 0.27%   |
| Netac                       | 4         | 6      | 0.27%   |
| Micron/Crucial Technology   | 4         | 7      | 0.27%   |
| Union Memory (Shenzhen)     | 3         | 6      | 0.2%    |
| Team                        | 3         | 4      | 0.2%    |
| OCZ                         | 3         | 3      | 0.2%    |
| Maxtor                      | 3         | 10     | 0.2%    |
| Lenovo                      | 3         | 3      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                             | 20        | 1.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 20        | 1.31%   |
| HGST HTS721010A9E630 1TB                           | 20        | 1.31%   |
| Unknown MMC Card  64GB                             | 18        | 1.18%   |
| Toshiba MQ01ABF050 500GB                           | 18        | 1.18%   |
| Unknown MMC Card  32GB                             | 17        | 1.11%   |
| Seagate ST500LT012-1DG142 500GB                    | 16        | 1.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 16        | 1.05%   |
| Seagate ST1000LM035-1RK172 1TB                     | 15        | 0.98%   |
| Kingston SA400S37120G 120GB SSD                    | 15        | 0.98%   |
| Crucial CT240M500SSD1 240GB                        | 15        | 0.98%   |
| Unknown MMC64G  64GB                               | 14        | 0.92%   |
| Kingston SV300S37A120G 120GB SSD                   | 13        | 0.85%   |
| Kingston SA400S37240G 240GB SSD                    | 13        | 0.85%   |
| SanDisk NVMe SSD Drive 512GB                       | 12        | 0.79%   |
| Seagate ST9500325AS 500GB                          | 9         | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 9         | 0.59%   |
| Samsung SSD 850 EVO 500GB                          | 9         | 0.59%   |
| Crucial CT500MX500SSD1 500GB                       | 9         | 0.59%   |
| Unknown MMC Card  16GB                             | 8         | 0.52%   |
| Toshiba TR200 240GB SSD                            | 8         | 0.52%   |
| Toshiba MQ04ABF100 1TB                             | 8         | 0.52%   |
| Samsung NVMe SSD Drive 512GB                       | 8         | 0.52%   |
| Kingston SA400S37480G 480GB SSD                    | 8         | 0.52%   |
| JMicron Generic 320GB                              | 8         | 0.52%   |
| Crucial CT240BX500SSD1 240GB                       | 8         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 7         | 0.46%   |
| WDC WD3200BEVT-22ZCT0 320GB                        | 7         | 0.46%   |
| Seagate ST9320325AS 320GB                          | 7         | 0.46%   |
| SanDisk NVMe SSD Drive 256GB                       | 7         | 0.46%   |
| Samsung SSD 860 QVO 1TB                            | 7         | 0.46%   |
| Samsung SSD 860 EVO 500GB                          | 7         | 0.46%   |
| Samsung SSD 860 EVO 1TB                            | 7         | 0.46%   |
| Samsung SSD 850 EVO 250GB                          | 7         | 0.46%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 7         | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 7         | 0.46%   |
| Phison PS5013 E13 NVMe Controller 512GB            | 7         | 0.46%   |
| Kingston SV300S37A240G 240GB SSD                   | 7         | 0.46%   |
| Kingston NVMe SSD Drive 512GB                      | 7         | 0.46%   |
| Intel SSDPEKNU512GZ 512GB                          | 7         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 134       | 165    | 29.07%  |
| Toshiba             | 98        | 122    | 21.26%  |
| WDC                 | 94        | 112    | 20.39%  |
| Hitachi             | 46        | 49     | 9.98%   |
| HGST                | 46        | 59     | 9.98%   |
| Fujitsu             | 18        | 19     | 3.9%    |
| Samsung Electronics | 15        | 16     | 3.25%   |
| JMicron Technology  | 8         | 9      | 1.74%   |
| Intenso             | 1         | 1      | 0.22%   |
| ASMedia             | 1         | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 90        | 112    | 18.87%  |
| Kingston            | 83        | 97     | 17.4%   |
| Crucial             | 58        | 70     | 12.16%  |
| SanDisk             | 30        | 36     | 6.29%   |
| WDC                 | 22        | 25     | 4.61%   |
| Toshiba             | 22        | 24     | 4.61%   |
| Apple               | 13        | 13     | 2.73%   |
| Intel               | 12        | 17     | 2.52%   |
| S3+                 | 11        | 22     | 2.31%   |
| China               | 11        | 13     | 2.31%   |
| Micron Technology   | 10        | 14     | 2.1%    |
| GOODRAM             | 10        | 10     | 2.1%    |
| A-DATA Technology   | 9         | 9      | 1.89%   |
| SK hynix            | 7         | 7      | 1.47%   |
| Emtec               | 7         | 8      | 1.47%   |
| Transcend           | 6         | 7      | 1.26%   |
| KIOXIA-EXCERIA      | 6         | 6      | 1.26%   |
| BlueRay             | 6         | 8      | 1.26%   |
| LITEON              | 5         | 6      | 1.05%   |
| Unknown             | 5         | 10     | 1.05%   |
| USB                 | 4         | 4      | 0.84%   |
| Netac               | 4         | 6      | 0.84%   |
| Team                | 3         | 4      | 0.63%   |
| PNY                 | 3         | 4      | 0.63%   |
| OCZ                 | 3         | 3      | 0.63%   |
| Maxtor              | 3         | 10     | 0.63%   |
| TCSUNBOW            | 2         | 2      | 0.42%   |
| Seagate             | 2         | 4      | 0.42%   |
| Plextor             | 2         | 2      | 0.42%   |
| LITEONIT            | 2         | 2      | 0.42%   |
| KingDian            | 2         | 2      | 0.42%   |
| Hewlett-Packard     | 2         | 2      | 0.42%   |
| Dogfish             | 2         | 2      | 0.42%   |
| Corsair             | 2         | 2      | 0.42%   |
| Wibtek              | 1         | 1      | 0.21%   |
| VNYEZ               | 1         | 1      | 0.21%   |
| Verbatim            | 1         | 1      | 0.21%   |
| Vaseky              | 1         | 1      | 0.21%   |
| USB30               | 1         | 1      | 0.21%   |
| USB3.0              | 1         | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 448       | 553    | 32.09%  |
| SSD     | 440       | 582    | 31.52%  |
| NVMe    | 408       | 584    | 29.23%  |
| MMC     | 84        | 123    | 6.02%   |
| Unknown | 16        | 18     | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 797       | 1102   | 59.83%  |
| NVMe | 408       | 582    | 30.63%  |
| MMC  | 84        | 123    | 6.31%   |
| SAS  | 43        | 53     | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 639       | 847    | 73.45%  |
| 0.51-1.0   | 208       | 256    | 23.91%  |
| 1.01-2.0   | 18        | 27     | 2.07%   |
| 3.01-4.0   | 4         | 4      | 0.46%   |
| 2.01-3.0   | 1         | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 382       | 30.51%  |
| 251-500        | 324       | 25.88%  |
| 501-1000       | 165       | 13.18%  |
| 51-100         | 102       | 8.15%   |
| 1-20           | 85        | 6.79%   |
| 1001-2000      | 66        | 5.27%   |
| 21-50          | 50        | 3.99%   |
| Unknown        | 33        | 2.64%   |
| More than 3000 | 27        | 2.16%   |
| 2001-3000      | 18        | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 528       | 40.58%  |
| 21-50          | 271       | 20.83%  |
| 101-250        | 165       | 12.68%  |
| 51-100         | 139       | 10.68%  |
| 251-500        | 89        | 6.84%   |
| 501-1000       | 39        | 3%      |
| Unknown        | 33        | 2.54%   |
| 1001-2000      | 22        | 1.69%   |
| More than 3000 | 11        | 0.85%   |
| 2001-3000      | 3         | 0.23%   |
| 0              | 1         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Crucial CT240M500SSD1 240GB           | 15        | 16     | 17.24%  |
| Kingston SV300S37A120G 120GB SSD      | 6         | 6      | 6.9%    |
| Seagate ST9320325AS 320GB             | 3         | 4      | 3.45%   |
| Kingston SV300S37A240G 240GB SSD      | 3         | 3      | 3.45%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 3      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 2.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 2.3%    |
| Hitachi HTS543216L9A300 160GB         | 2         | 2      | 2.3%    |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 2.3%    |
| China G521N256GB SSD                  | 2         | 3      | 2.3%    |
| WDC WD7500BPVX-60JC3T0 752GB          | 1         | 2      | 1.15%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 1      | 1.15%   |
| WDC WD5000BPVT-80HXZT1 500GB          | 1         | 1      | 1.15%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 1.15%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 1.15%   |
| WDC WD10JPVT-22A1YT0 1TB              | 1         | 1      | 1.15%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 1.15%   |
| VNYEZ SSD MSATA 128GB                 | 1         | 1      | 1.15%   |
| USB 3.1 512GB                         | 1         | 1      | 1.15%   |
| Toshiba Q300. 240GB SSD               | 1         | 1      | 1.15%   |
| Toshiba MQ01ACF050 500GB              | 1         | 1      | 1.15%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.15%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.15%   |
| Toshiba MK7575GSX 752GB               | 1         | 1      | 1.15%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 1.15%   |
| Toshiba MK3276GSX 320GB               | 1         | 1      | 1.15%   |
| Toshiba MK2561GSYN 250GB              | 1         | 1      | 1.15%   |
| Toshiba HDWL120 2TB                   | 1         | 1      | 1.15%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 1         | 1      | 1.15%   |
| SK hynix HFS256G32MND-2900A 256GB SSD | 1         | 1      | 1.15%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 1.15%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.15%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.15%   |
| Seagate ST9160310AS 160GB             | 1         | 2      | 1.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.15%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.15%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 1.15%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.15%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 1.15%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 18.6%   |
| Crucial             | 15        | 16     | 17.44%  |
| Hitachi             | 12        | 12     | 13.95%  |
| Toshiba             | 9         | 9      | 10.47%  |
| Kingston            | 9         | 10     | 10.47%  |
| WDC                 | 7         | 8      | 8.14%   |
| HGST                | 4         | 4      | 4.65%   |
| Samsung Electronics | 3         | 3      | 3.49%   |
| SK hynix            | 2         | 2      | 2.33%   |
| China               | 2         | 3      | 2.33%   |
| VNYEZ               | 1         | 1      | 1.16%   |
| USB                 | 1         | 1      | 1.16%   |
| SanDisk             | 1         | 1      | 1.16%   |
| LITEON              | 1         | 1      | 1.16%   |
| Intel               | 1         | 1      | 1.16%   |
| Fujitsu             | 1         | 1      | 1.16%   |
| A-DATA Technology   | 1         | 1      | 1.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 32%     |
| Hitachi             | 12        | 12     | 24%     |
| Toshiba             | 8         | 8      | 16%     |
| WDC                 | 7         | 8      | 14%     |
| HGST                | 4         | 4      | 8%      |
| Samsung Electronics | 2         | 2      | 4%      |
| Fujitsu             | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 53     | 57.65%  |
| SSD  | 35        | 38     | 41.18%  |
| NVMe | 1         | 1      | 1.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010B7E610 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 771       | 1191   | 61.73%  |
| Works    | 393       | 576    | 31.47%  |
| Malfunc  | 84        | 92     | 6.73%   |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 789       | 57.55%  |
| AMD                              | 143       | 10.43%  |
| Samsung Electronics              | 135       | 9.85%   |
| SanDisk                          | 78        | 5.69%   |
| SK hynix                         | 34        | 2.48%   |
| Micron Technology                | 33        | 2.41%   |
| Kingston Technology Company      | 30        | 2.19%   |
| Toshiba America Info Systems     | 25        | 1.82%   |
| Phison Electronics               | 17        | 1.24%   |
| Nvidia                           | 15        | 1.09%   |
| KIOXIA                           | 15        | 1.09%   |
| Silicon Integrated Systems [SiS] | 13        | 0.95%   |
| Micron/Crucial Technology        | 8         | 0.58%   |
| Union Memory (Shenzhen)          | 7         | 0.51%   |
| Silicon Motion                   | 6         | 0.44%   |
| Lite-On Technology               | 6         | 0.44%   |
| JMicron Technology               | 4         | 0.29%   |
| Lenovo                           | 3         | 0.22%   |
| Solid State Storage Technology   | 2         | 0.15%   |
| Silicon Image                    | 1         | 0.07%   |
| Realtek Semiconductor            | 1         | 0.07%   |
| O2 Micro                         | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.07%   |
| Marvell Technology Group         | 1         | 0.07%   |
| Enmotus                          | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |
| ADATA Technology                 | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 132       | 8.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 80        | 5.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 71        | 4.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 68        | 4.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 65        | 4.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 57        | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 57        | 3.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 50        | 3.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 50        | 3.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 49        | 3.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 41        | 2.71%   |
| Intel Volume Management Device NVMe RAID Controller                            | 34        | 2.25%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 31        | 2.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 31        | 2.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 27        | 1.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 27        | 1.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 25        | 1.65%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 21        | 1.39%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 19        | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 15        | 0.99%   |
| Intel SSD 660P Series                                                          | 15        | 0.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 14        | 0.93%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 13        | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 13        | 0.86%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 12        | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 12        | 0.79%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 12        | 0.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 12        | 0.79%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 11        | 0.73%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 11        | 0.73%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 11        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 11        | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 11        | 0.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 10        | 0.66%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 10        | 0.66%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 10        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 0.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.6%    |
| Micron 2200S NVMe SSD [Cassandra]                                              | 9         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 817       | 56.62%  |
| NVMe | 408       | 28.27%  |
| IDE  | 128       | 8.87%   |
| RAID | 90        | 6.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 959       | 80.59%  |
| AMD     | 230       | 19.33%  |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 26        | 2.18%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 24        | 2.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 19        | 1.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 1.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 17        | 1.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 1.34%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 16        | 1.34%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.34%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 14        | 1.18%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 14        | 1.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 1.18%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.18%   |
| AMD 3020e with Radeon Graphics                | 14        | 1.18%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 1.09%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 12        | 1.01%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 12        | 1.01%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 11        | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 11        | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.92%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 0.92%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 10        | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 10        | 0.84%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 10        | 0.84%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 10        | 0.84%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 9         | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.76%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 9         | 0.76%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.76%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 8         | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.67%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 8         | 0.67%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 8         | 0.67%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 8         | 0.67%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 8         | 0.67%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 7         | 0.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 283       | 23.78%  |
| Intel Core i5           | 222       | 18.66%  |
| Other                   | 111       | 9.33%   |
| Intel Core 2 Duo        | 93        | 7.82%   |
| Intel Core i3           | 78        | 6.55%   |
| AMD Ryzen 7             | 68        | 5.71%   |
| Intel Celeron           | 53        | 4.45%   |
| AMD Ryzen 5             | 49        | 4.12%   |
| Intel Atom              | 37        | 3.11%   |
| Intel Pentium Dual-Core | 27        | 2.27%   |
| Intel Pentium Dual      | 24        | 2.02%   |
| Intel Pentium           | 17        | 1.43%   |
| AMD A4                  | 16        | 1.34%   |
| Intel Genuine           | 15        | 1.26%   |
| AMD A6                  | 13        | 1.09%   |
| AMD A8                  | 11        | 0.92%   |
| Intel Core 2            | 10        | 0.84%   |
| AMD Ryzen 3             | 9         | 0.76%   |
| AMD Ryzen 9             | 8         | 0.67%   |
| AMD E2                  | 8         | 0.67%   |
| Intel Pentium M         | 5         | 0.42%   |
| AMD E                   | 4         | 0.34%   |
| AMD A10                 | 4         | 0.34%   |
| AMD Ryzen 7 PRO         | 3         | 0.25%   |
| AMD Athlon              | 3         | 0.25%   |
| Intel Core m3           | 2         | 0.17%   |
| Intel Core i9           | 2         | 0.17%   |
| Intel Celeron M         | 2         | 0.17%   |
| AMD Mobile Sempron      | 2         | 0.17%   |
| AMD E1                  | 2         | 0.17%   |
| Intel Core m7           | 1         | 0.08%   |
| Intel Celeron Dual-Core | 1         | 0.08%   |
| AMD Turion 64 X2 Mobile | 1         | 0.08%   |
| AMD Turion              | 1         | 0.08%   |
| AMD Ryzen 5 PRO         | 1         | 0.08%   |
| AMD Quad-Core           | 1         | 0.08%   |
| AMD Phenom II           | 1         | 0.08%   |
| AMD FX                  | 1         | 0.08%   |
| AMD Athlon 64 X2        | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 589       | 49.5%   |
| 4      | 380       | 31.93%  |
| 6      | 78        | 6.55%   |
| 8      | 77        | 6.47%   |
| 1      | 31        | 2.61%   |
| 10     | 13        | 1.09%   |
| 14     | 10        | 0.84%   |
| 12     | 9         | 0.76%   |
| 24     | 1         | 0.08%   |
| 16     | 1         | 0.08%   |
| 3      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1190      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 821       | 68.88%  |
| 1      | 371       | 31.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1143      | 95.65%  |
| Unknown        | 29        | 2.43%   |
| 32-bit         | 19        | 1.59%   |
| 64-bit         | 4         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 406       | 32.79%  |
| 0x306a9    | 53        | 4.28%   |
| 0x206a7    | 48        | 3.88%   |
| 0x1067a    | 46        | 3.72%   |
| 0x806ec    | 39        | 3.15%   |
| 0x10676    | 37        | 2.99%   |
| 0x806ea    | 35        | 2.83%   |
| 0x906ea    | 32        | 2.58%   |
| 0x6fd      | 30        | 2.42%   |
| 0x806c1    | 28        | 2.26%   |
| 0x40651    | 27        | 2.18%   |
| 0x306d4    | 21        | 1.7%    |
| 0x20655    | 21        | 1.7%    |
| 0x406e3    | 19        | 1.53%   |
| 0x806e9    | 18        | 1.45%   |
| 0x806eb    | 16        | 1.29%   |
| 0x20652    | 16        | 1.29%   |
| 0x08108109 | 16        | 1.29%   |
| 0x306c3    | 14        | 1.13%   |
| 0x08200103 | 14        | 1.13%   |
| 0xa0652    | 13        | 1.05%   |
| 0x506e3    | 13        | 1.05%   |
| 0x30678    | 13        | 1.05%   |
| 0x0a50000c | 13        | 1.05%   |
| 0x406c4    | 10        | 0.81%   |
| 0x406c3    | 10        | 0.81%   |
| 0x0a50000d | 10        | 0.81%   |
| 0x07030105 | 10        | 0.81%   |
| 0x08108102 | 9         | 0.73%   |
| 0x906e9    | 8         | 0.65%   |
| 0x106ca    | 8         | 0.65%   |
| 0x906a3    | 7         | 0.57%   |
| 0x706e5    | 7         | 0.57%   |
| 0x6f6      | 7         | 0.57%   |
| 0x106e5    | 7         | 0.57%   |
| 0x08600106 | 7         | 0.57%   |
| 0x08600104 | 7         | 0.57%   |
| 0x08600103 | 7         | 0.57%   |
| 0x6d8      | 6         | 0.48%   |
| 0x08608103 | 6         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 203       | 17.03%  |
| Penryn           | 108       | 9.06%   |
| IvyBridge        | 80        | 6.71%   |
| Haswell          | 75        | 6.29%   |
| SandyBridge      | 68        | 5.7%    |
| Core             | 60        | 5.03%   |
| Westmere         | 54        | 4.53%   |
| Skylake          | 54        | 4.53%   |
| Silvermont       | 49        | 4.11%   |
| TigerLake        | 48        | 4.03%   |
| Unknown          | 47        | 3.94%   |
| Zen 3            | 38        | 3.19%   |
| Broadwell        | 36        | 3.02%   |
| Zen+             | 32        | 2.68%   |
| Zen 2            | 30        | 2.52%   |
| Zen              | 24        | 2.01%   |
| Alderlake Hybrid | 24        | 2.01%   |
| CometLake        | 21        | 1.76%   |
| Puma             | 20        | 1.68%   |
| Bonnell          | 16        | 1.34%   |
| Excavator        | 15        | 1.26%   |
| P6               | 13        | 1.09%   |
| Jaguar           | 13        | 1.09%   |
| IceLake          | 11        | 0.92%   |
| Nehalem          | 9         | 0.76%   |
| Goldmont plus    | 7         | 0.59%   |
| Goldmont         | 7         | 0.59%   |
| Bobcat           | 6         | 0.5%    |
| Steamroller      | 5         | 0.42%   |
| Piledriver       | 4         | 0.34%   |
| K8 Hammer        | 4         | 0.34%   |
| K8 & K10 hybrid  | 4         | 0.34%   |
| Tremont          | 3         | 0.25%   |
| K10 Llano        | 2         | 0.17%   |
| K10              | 1         | 0.08%   |
| Gracemont        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 785       | 50.16%  |
| Nvidia                           | 441       | 28.18%  |
| AMD                              | 330       | 21.09%  |
| Silicon Integrated Systems [SiS] | 9         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 80        | 4.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 52        | 3.2%    |
| Intel UHD Graphics 620                                                                   | 46        | 2.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 46        | 2.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 45        | 2.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 44        | 2.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 37        | 2.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 36        | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 2.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 34        | 2.09%   |
| Intel HD Graphics 5500                                                                   | 31        | 1.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 31        | 1.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 28        | 1.72%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 27        | 1.66%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 27        | 1.66%   |
| Intel HD Graphics 620                                                                    | 26        | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 1.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 25        | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 25        | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 22        | 1.35%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 22        | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 21        | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 1.29%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 19        | 1.17%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 17        | 1.05%   |
| Intel HD Graphics 530                                                                    | 17        | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 1.05%   |
| AMD Lucienne                                                                             | 17        | 1.05%   |
| Nvidia GP108M [GeForce MX150]                                                            | 15        | 0.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 15        | 0.92%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 14        | 0.86%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 13        | 0.8%    |
| Intel HD Graphics 630                                                                    | 13        | 0.8%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 0.8%    |
| Nvidia GP108M [GeForce MX250]                                                            | 11        | 0.68%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 11        | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 11        | 0.68%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 11        | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 450       | 37.63%  |
| Intel + Nvidia | 279       | 23.33%  |
| 1 x AMD        | 213       | 17.81%  |
| 1 x Nvidia     | 118       | 9.87%   |
| Intel + AMD    | 52        | 4.35%   |
| AMD + Nvidia   | 45        | 3.76%   |
| 2 x AMD        | 22        | 1.84%   |
| 1 x SiS        | 9         | 0.75%   |
| 2 x Intel      | 6         | 0.5%    |
| Other          | 1         | 0.08%   |
| 2 x Nvidia     | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 963       | 79.39%  |
| Proprietary | 203       | 16.74%  |
| Unknown     | 47        | 3.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 708       | 57.8%   |
| 0.01-0.5   | 203       | 16.57%  |
| 1.01-2.0   | 150       | 12.24%  |
| 0.51-1.0   | 76        | 6.2%    |
| 3.01-4.0   | 53        | 4.33%   |
| 5.01-6.0   | 23        | 1.88%   |
| 7.01-8.0   | 9         | 0.73%   |
| 2.01-3.0   | 2         | 0.16%   |
| 8.01-16.0  | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 241       | 18.75%  |
| Chimei Innolux          | 186       | 14.47%  |
| LG Display              | 167       | 13%     |
| BOE                     | 153       | 11.91%  |
| Samsung Electronics     | 124       | 9.65%   |
| Goldstar                | 43        | 3.35%   |
| Chi Mei Optoelectronics | 32        | 2.49%   |
| Apple                   | 30        | 2.33%   |
| LG Philips              | 27        | 2.1%    |
| Lenovo                  | 25        | 1.95%   |
| PANDA                   | 22        | 1.71%   |
| Hewlett-Packard         | 22        | 1.71%   |
| Dell                    | 22        | 1.71%   |
| Sharp                   | 21        | 1.63%   |
| Ancor Communications    | 20        | 1.56%   |
| AOC                     | 17        | 1.32%   |
| Philips                 | 10        | 0.78%   |
| BenQ                    | 9         | 0.7%    |
| Sony                    | 8         | 0.62%   |
| InfoVision              | 7         | 0.54%   |
| CPT                     | 7         | 0.54%   |
| ASUSTek Computer        | 7         | 0.54%   |
| Acer                    | 7         | 0.54%   |
| Seiko/Epson             | 6         | 0.47%   |
| MSI                     | 5         | 0.39%   |
| HannStar                | 5         | 0.39%   |
| ViewSonic               | 4         | 0.31%   |
| Valve                   | 4         | 0.31%   |
| CSO                     | 4         | 0.31%   |
| Toshiba                 | 3         | 0.23%   |
| Panasonic               | 3         | 0.23%   |
| LGD                     | 3         | 0.23%   |
| LG Electronics          | 3         | 0.23%   |
| ZTR                     | 2         | 0.16%   |
| Unknown                 | 2         | 0.16%   |
| Mi                      | 2         | 0.16%   |
| Lenovo Group Limited    | 2         | 0.16%   |
| HUAWEI                  | 2         | 0.16%   |
| HKC                     | 2         | 0.16%   |
| CVT                     | 2         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 14        | 1.07%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 13        | 1%      |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.92%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 12        | 0.92%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.77%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 10        | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 9         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 7         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.54%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                     | 7         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.46%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 6         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 6         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 6         | 0.46%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 6         | 0.46%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.46%   |
| LG Philips LCD Monitor LPLDD00 1280x800 331x207mm 15.4-inch              | 5         | 0.38%   |
| LG Display LCD Monitor LGD045D 1366x768 345x194mm 15.6-inch              | 5         | 0.38%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.38%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 5         | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 5         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.38%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 5         | 0.38%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.38%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 4         | 0.31%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 4         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 4         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 463       | 38.81%  |
| 1366x768 (WXGA)    | 402       | 33.7%   |
| 1280x800 (WXGA)    | 65        | 5.45%   |
| 3840x2160 (4K)     | 36        | 3.02%   |
| 1600x900 (HD+)     | 33        | 2.77%   |
| 2560x1440 (QHD)    | 25        | 2.1%    |
| 1440x900 (WXGA+)   | 19        | 1.59%   |
| 1920x1200 (WUXGA)  | 17        | 1.42%   |
| 1680x1050 (WSXGA+) | 15        | 1.26%   |
| 1280x1024 (SXGA)   | 12        | 1.01%   |
| 2560x1600          | 11        | 0.92%   |
| 2560x1080          | 11        | 0.92%   |
| 2880x1800          | 9         | 0.75%   |
| 2160x1440          | 9         | 0.75%   |
| 1024x600           | 7         | 0.59%   |
| 3840x2400          | 6         | 0.5%    |
| 3440x1440          | 6         | 0.5%    |
| 1360x768           | 6         | 0.5%    |
| 1024x768 (XGA)     | 5         | 0.42%   |
| Unknown            | 5         | 0.42%   |
| 800x1280           | 4         | 0.34%   |
| 3200x1800 (QHD+)   | 3         | 0.25%   |
| 2288x1287          | 3         | 0.25%   |
| 3072x1920          | 2         | 0.17%   |
| 2880x1620          | 2         | 0.17%   |
| 2240x1400          | 2         | 0.17%   |
| 1920x1280          | 2         | 0.17%   |
| 1400x1050          | 2         | 0.17%   |
| 640x480            | 1         | 0.08%   |
| 5760x1080          | 1         | 0.08%   |
| 3840x1600          | 1         | 0.08%   |
| 3840x1100          | 1         | 0.08%   |
| 3840x1080          | 1         | 0.08%   |
| 3520x1080          | 1         | 0.08%   |
| 3280x1080          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2726x768           | 1         | 0.08%   |
| 1920x540           | 1         | 0.08%   |
| 1600x1200          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 595       | 46.38%  |
| 14      | 159       | 12.39%  |
| 13      | 153       | 11.93%  |
| 17      | 57        | 4.44%   |
| 24      | 50        | 3.9%    |
| 21      | 40        | 3.12%   |
| 27      | 29        | 2.26%   |
| Unknown | 27        | 2.1%    |
| 23      | 25        | 1.95%   |
| 12      | 23        | 1.79%   |
| 16      | 18        | 1.4%    |
| 11      | 17        | 1.33%   |
| 34      | 16        | 1.25%   |
| 31      | 13        | 1.01%   |
| 10      | 11        | 0.86%   |
| 22      | 9         | 0.7%    |
| 19      | 7         | 0.55%   |
| 40      | 5         | 0.39%   |
| 7       | 4         | 0.31%   |
| 84      | 3         | 0.23%   |
| 28      | 3         | 0.23%   |
| 25      | 3         | 0.23%   |
| 20      | 3         | 0.23%   |
| 18      | 3         | 0.23%   |
| 72      | 2         | 0.16%   |
| 26      | 2         | 0.16%   |
| 60      | 1         | 0.08%   |
| 54      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |
| 32      | 1         | 0.08%   |
| 8       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 835       | 66.01%  |
| 201-300     | 124       | 9.8%    |
| 501-600     | 99        | 7.83%   |
| 351-400     | 67        | 5.3%    |
| 401-500     | 59        | 4.66%   |
| Unknown     | 27        | 2.13%   |
| 601-700     | 18        | 1.42%   |
| 701-800     | 17        | 1.34%   |
| 801-900     | 6         | 0.47%   |
| 1501-2000   | 5         | 0.4%    |
| 1-100       | 4         | 0.32%   |
| 1001-1500   | 3         | 0.24%   |
| 101-200     | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 902       | 79.4%   |
| 16/10   | 152       | 13.38%  |
| Unknown | 24        | 2.11%   |
| 21/9    | 18        | 1.58%   |
| 3/2     | 14        | 1.23%   |
| 5/4     | 11        | 0.97%   |
| 4/3     | 9         | 0.79%   |
| 0.67    | 4         | 0.35%   |
| 6/5     | 1         | 0.09%   |
| 3.40    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 594       | 46.33%  |
| 81-90          | 249       | 19.42%  |
| 201-250        | 101       | 7.88%   |
| 71-80          | 58        | 4.52%   |
| 121-130        | 40        | 3.12%   |
| 301-350        | 31        | 2.42%   |
| 351-500        | 30        | 2.34%   |
| Unknown        | 27        | 2.11%   |
| 61-70          | 22        | 1.72%   |
| 151-200        | 19        | 1.48%   |
| 51-60          | 18        | 1.4%    |
| 251-300        | 18        | 1.4%    |
| 111-120        | 14        | 1.09%   |
| 141-150        | 12        | 0.94%   |
| 41-50          | 11        | 0.86%   |
| 131-140        | 9         | 0.7%    |
| 91-100         | 9         | 0.7%    |
| 501-1000       | 8         | 0.62%   |
| More than 1000 | 7         | 0.55%   |
| 1-40           | 5         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 450       | 35.97%  |
| 101-120       | 418       | 33.41%  |
| 51-100        | 240       | 19.18%  |
| 161-240       | 81        | 6.47%   |
| More than 240 | 29        | 2.32%   |
| Unknown       | 27        | 2.16%   |
| 1-50          | 6         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 945       | 77.21%  |
| 2     | 190       | 15.52%  |
| 0     | 62        | 5.07%   |
| 3     | 24        | 1.96%   |
| 4     | 3         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 630       | 33.28%  |
| Intel                             | 552       | 29.16%  |
| Qualcomm Atheros                  | 299       | 15.8%   |
| Broadcom                          | 137       | 7.24%   |
| Marvell Technology Group          | 49        | 2.59%   |
| TP-Link                           | 34        | 1.8%    |
| MediaTek                          | 29        | 1.53%   |
| Broadcom Limited                  | 25        | 1.32%   |
| Ralink                            | 20        | 1.06%   |
| Silicon Integrated Systems [SiS]  | 13        | 0.69%   |
| Nvidia                            | 10        | 0.53%   |
| ASIX Electronics                  | 10        | 0.53%   |
| Ralink Technology                 | 6         | 0.32%   |
| Sierra Wireless                   | 5         | 0.26%   |
| Lenovo                            | 5         | 0.26%   |
| JMicron Technology                | 5         | 0.26%   |
| Ericsson Business Mobile Networks | 5         | 0.26%   |
| DisplayLink                       | 5         | 0.26%   |
| ICS Advent                        | 4         | 0.21%   |
| Hewlett-Packard                   | 4         | 0.21%   |
| Dell                              | 4         | 0.21%   |
| D-Link                            | 4         | 0.21%   |
| Attansic Technology               | 4         | 0.21%   |
| ASUSTek Computer                  | 4         | 0.21%   |
| Samsung Electronics               | 3         | 0.16%   |
| Qualcomm Atheros Communications   | 3         | 0.16%   |
| Huawei Technologies               | 3         | 0.16%   |
| Mercucys                          | 2         | 0.11%   |
| FIBOCOM                           | 2         | 0.11%   |
| ASR Microelectronics              | 2         | 0.11%   |
| Xiaomi                            | 1         | 0.05%   |
| TRENDnet                          | 1         | 0.05%   |
| Toshiba                           | 1         | 0.05%   |
| T & A Mobile Phones               | 1         | 0.05%   |
| SparkFun                          | 1         | 0.05%   |
| Qualcomm                          | 1         | 0.05%   |
| Microsoft                         | 1         | 0.05%   |
| Micro Star International          | 1         | 0.05%   |
| LSI                               | 1         | 0.05%   |
| GrupoPIE PORTUGAL                 | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 376       | 16.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 126       | 5.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 58        | 2.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 53        | 2.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 48        | 2.15%   |
| Intel Wi-Fi 6 AX200                                                     | 47        | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 1.83%   |
| Intel Wireless 8265 / 8275                                              | 41        | 1.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 34        | 1.52%   |
| Intel Wi-Fi 6 AX201                                                     | 34        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 1.43%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 1.34%   |
| Intel Wireless 7265                                                     | 28        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 1.25%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                    | 27        | 1.21%   |
| Intel Wireless 7260                                                     | 27        | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 1.16%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 25        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 25        | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 25        | 1.12%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 24        | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 24        | 1.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 24        | 1.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 23        | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 21        | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 20        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 20        | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 0.89%   |
| Intel Wireless 8260                                                     | 19        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 0.72%   |
| Intel Wireless 3165                                                     | 14        | 0.63%   |
| Intel Wireless 3160                                                     | 14        | 0.63%   |
| Intel WiFi Link 5100                                                    | 14        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                   | 13        | 0.58%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 12        | 0.54%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 12        | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 537       | 44.16%  |
| Qualcomm Atheros                | 262       | 21.55%  |
| Realtek Semiconductor           | 198       | 16.28%  |
| Broadcom                        | 110       | 9.05%   |
| MediaTek                        | 28        | 2.3%    |
| Ralink                          | 20        | 1.64%   |
| Broadcom Limited                | 16        | 1.32%   |
| TP-Link                         | 11        | 0.9%    |
| Ralink Technology               | 6         | 0.49%   |
| Sierra Wireless                 | 5         | 0.41%   |
| Dell                            | 4         | 0.33%   |
| D-Link                          | 4         | 0.33%   |
| ASUSTek Computer                | 4         | 0.33%   |
| Qualcomm Atheros Communications | 3         | 0.25%   |
| Mercucys                        | 2         | 0.16%   |
| FIBOCOM                         | 2         | 0.16%   |
| TRENDnet                        | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| D-Link System                   | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 58        | 4.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 53        | 4.35%   |
| Intel Wi-Fi 6 AX200                                                     | 47        | 3.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 3.37%   |
| Intel Wireless 8265 / 8275                                              | 41        | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 34        | 2.79%   |
| Intel Wi-Fi 6 AX201                                                     | 34        | 2.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 2.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 2.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 2.47%   |
| Intel Wireless 7265                                                     | 28        | 2.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 2.3%    |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 2.3%    |
| Intel Wireless 7260                                                     | 27        | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 2.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 2.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 25        | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 25        | 2.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 25        | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 24        | 1.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 23        | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 21        | 1.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 20        | 1.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 20        | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 1.64%   |
| Intel Wireless 8260                                                     | 19        | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.31%   |
| Intel Wireless 3165                                                     | 14        | 1.15%   |
| Intel Wireless 3160                                                     | 14        | 1.15%   |
| Intel WiFi Link 5100                                                    | 14        | 1.15%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 12        | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 0.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.9%    |
| Intel Centrino Advanced-N 6235                                          | 11        | 0.9%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 10        | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 9         | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 9         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 563       | 56.64%  |
| Intel                            | 158       | 15.9%   |
| Qualcomm Atheros                 | 73        | 7.34%   |
| Marvell Technology Group         | 49        | 4.93%   |
| Broadcom                         | 45        | 4.53%   |
| TP-Link                          | 24        | 2.41%   |
| Silicon Integrated Systems [SiS] | 13        | 1.31%   |
| Nvidia                           | 10        | 1.01%   |
| ASIX Electronics                 | 10        | 1.01%   |
| Broadcom Limited                 | 9         | 0.91%   |
| Lenovo                           | 5         | 0.5%    |
| JMicron Technology               | 5         | 0.5%    |
| DisplayLink                      | 5         | 0.5%    |
| ICS Advent                       | 4         | 0.4%    |
| Attansic Technology              | 4         | 0.4%    |
| Samsung Electronics              | 3         | 0.3%    |
| Hewlett-Packard                  | 3         | 0.3%    |
| Huawei Technologies              | 2         | 0.2%    |
| Xiaomi                           | 1         | 0.1%    |
| T & A Mobile Phones              | 1         | 0.1%    |
| Qualcomm                         | 1         | 0.1%    |
| Microsoft                        | 1         | 0.1%    |
| MediaTek                         | 1         | 0.1%    |
| LSI                              | 1         | 0.1%    |
| Archos                           | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |
| Allwinner Technology             | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 376       | 37.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 126       | 12.59%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 48        | 4.8%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 27        | 2.7%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 24        | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 24        | 2.4%    |
| Intel Ethernet Connection (4) I219-LM                                          | 13        | 1.3%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 12        | 1.2%    |
| Intel Ethernet Connection I218-LM                                              | 11        | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 10        | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 10        | 1%      |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 9         | 0.9%    |
| Intel 82579V Gigabit Network Connection                                        | 9         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 0.9%    |
| Intel Ethernet Connection I217-LM                                              | 8         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                                           | 8         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.7%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 7         | 0.7%    |
| Intel Ethernet Connection I219-LM                                              | 7         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                                       | 7         | 0.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 7         | 0.7%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 7         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 6         | 0.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 6         | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 6         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 6         | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 0.5%    |
| Realtek Killer E2600 GbE Controller                                            | 5         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 5         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 0.5%    |
| Intel 82573L Gigabit Ethernet Controller                                       | 5         | 0.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 5         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.4%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1163      | 54.14%  |
| Ethernet | 966       | 44.97%  |
| Modem    | 15        | 0.7%    |
| Unknown  | 4         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 942       | 74.76%  |
| Ethernet | 318       | 25.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 854       | 71.64%  |
| 1     | 314       | 26.34%  |
| 0     | 21        | 1.76%   |
| 3     | 3         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 847       | 69.43%  |
| Yes  | 373       | 30.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 392       | 43.6%   |
| Realtek Semiconductor           | 107       | 11.9%   |
| Qualcomm Atheros Communications | 66        | 7.34%   |
| IMC Networks                    | 66        | 7.34%   |
| Foxconn / Hon Hai               | 49        | 5.45%   |
| Lite-On Technology              | 45        | 5.01%   |
| Broadcom                        | 38        | 4.23%   |
| Apple                           | 32        | 3.56%   |
| Toshiba                         | 20        | 2.22%   |
| Hewlett-Packard                 | 17        | 1.89%   |
| ASUSTek Computer                | 14        | 1.56%   |
| Realtek                         | 12        | 1.33%   |
| Ralink                          | 12        | 1.33%   |
| Dell                            | 12        | 1.33%   |
| Alps Electric                   | 6         | 0.67%   |
| Cambridge Silicon Radio         | 4         | 0.44%   |
| Ralink Technology               | 2         | 0.22%   |
| Chicony Electronics             | 2         | 0.22%   |
| MediaTek                        | 1         | 0.11%   |
| Foxconn International           | 1         | 0.11%   |
| Conwise Technology              | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 87        | 9.68%   |
| Realtek Bluetooth Radio                                                             | 73        | 8.12%   |
| Intel AX201 Bluetooth                                                               | 73        | 8.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 65        | 7.23%   |
| Intel Bluetooth Device                                                              | 58        | 6.45%   |
| Intel AX200 Bluetooth                                                               | 47        | 5.23%   |
| IMC Networks Bluetooth Device                                                       | 31        | 3.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 21        | 2.34%   |
| Intel AX211 Bluetooth                                                               | 20        | 2.22%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 19        | 2.11%   |
| IMC Networks Bluetooth Radio                                                        | 19        | 2.11%   |
| Apple Bluetooth Host Controller                                                     | 19        | 2.11%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 18        | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 17        | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 15        | 1.67%   |
| Realtek Bluetooth Radio                                                             | 12        | 1.33%   |
| Ralink RT3290 Bluetooth                                                             | 12        | 1.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 12        | 1.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.22%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 11        | 1.22%   |
| Apple Bluetooth USB Host Controller                                                 | 11        | 1.22%   |
| Lite-On Bluetooth Device                                                            | 10        | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 10        | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.11%   |
| IMC Networks Wireless_Device                                                        | 9         | 1%      |
| Realtek 802.11ac WLAN Adapter                                                       | 8         | 0.89%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 8         | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 7         | 0.78%   |
| Realtek RTL8821A Bluetooth                                                          | 6         | 0.67%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 6         | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 0.67%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.56%   |
| Toshiba Askey Bluetooth Module                                                      | 5         | 0.56%   |
| Lite-On BCM43142A0                                                                  | 5         | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 0.56%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 5         | 0.56%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 915       | 61.37%  |
| AMD                                          | 277       | 18.58%  |
| Nvidia                                       | 193       | 12.94%  |
| Silicon Integrated Systems [SiS]             | 13        | 0.87%   |
| GN Netcom                                    | 10        | 0.67%   |
| C-Media Electronics                          | 10        | 0.67%   |
| Realtek Semiconductor                        | 8         | 0.54%   |
| Plantronics                                  | 6         | 0.4%    |
| Hewlett-Packard                              | 6         | 0.4%    |
| Lenovo                                       | 5         | 0.34%   |
| Texas Instruments                            | 4         | 0.27%   |
| Razer USA                                    | 4         | 0.27%   |
| Logitech                                     | 4         | 0.27%   |
| JMTek                                        | 4         | 0.27%   |
| Creative Technology                          | 4         | 0.27%   |
| Sony                                         | 2         | 0.13%   |
| Kingston Technology                          | 2         | 0.13%   |
| Generalplus Technology                       | 2         | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.07%   |
| XMOS                                         | 1         | 0.07%   |
| Trust                                        | 1         | 0.07%   |
| Sennheiser Communications                    | 1         | 0.07%   |
| Micro Star International                     | 1         | 0.07%   |
| M2Tech                                       | 1         | 0.07%   |
| JBL                                          | 1         | 0.07%   |
| Huawei Technologies                          | 1         | 0.07%   |
| GYROCOM C&C                                  | 1         | 0.07%   |
| Guillemot                                    | 1         | 0.07%   |
| Focusrite-Novation                           | 1         | 0.07%   |
| ESS Technology                               | 1         | 0.07%   |
| EGO SYStems                                  | 1         | 0.07%   |
| DSEA A/S                                     | 1         | 0.07%   |
| Dell                                         | 1         | 0.07%   |
| Corsair                                      | 1         | 0.07%   |
| Conexant Systems                             | 1         | 0.07%   |
| Conexant                                     | 1         | 0.07%   |
| CMX Systems                                  | 1         | 0.07%   |
| BEHRINGER International                      | 1         | 0.07%   |
| ASUSTek Computer                             | 1         | 0.07%   |
| Apple                                        | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 143       | 8.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 105       | 5.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 88        | 4.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 76        | 4.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 63        | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 60        | 3.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 58        | 3.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 56        | 3.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 53        | 2.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 48        | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 46        | 2.58%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 44        | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 44        | 2.47%   |
| Intel 8 Series HD Audio Controller                                                                | 43        | 2.41%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 39        | 2.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 37        | 2.08%   |
| Intel Broadwell-U Audio Controller                                                                | 36        | 2.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 35        | 1.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 35        | 1.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 32        | 1.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 32        | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 26        | 1.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 25        | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 22        | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 17        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 0.95%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 17        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 15        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 14        | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 14        | 0.79%   |
| Nvidia Audio device                                                                               | 14        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 14        | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 13        | 0.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 13        | 0.73%   |
| AMD High Definition Audio Controller                                                              | 13        | 0.73%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 12        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 205       | 30.15%  |
| SK hynix            | 155       | 22.79%  |
| Unknown             | 80        | 11.76%  |
| Micron Technology   | 74        | 10.88%  |
| Kingston            | 58        | 8.53%   |
| Crucial             | 18        | 2.65%   |
| Ramaxel Technology  | 15        | 2.21%   |
| Elpida              | 11        | 1.62%   |
| G.Skill             | 10        | 1.47%   |
| Corsair             | 9         | 1.32%   |
| A-DATA Technology   | 9         | 1.32%   |
| Unknown             | 7         | 1.03%   |
| Team                | 4         | 0.59%   |
| Unknown (ABCD)      | 3         | 0.44%   |
| Transcend           | 3         | 0.44%   |
| Nanya Technology    | 3         | 0.44%   |
| Lexar               | 2         | 0.29%   |
| Unigen              | 1         | 0.15%   |
| Toshiba             | 1         | 0.15%   |
| Teikon              | 1         | 0.15%   |
| Smart               | 1         | 0.15%   |
| Silicon Power       | 1         | 0.15%   |
| PUSKILL             | 1         | 0.15%   |
| Netlist             | 1         | 0.15%   |
| Kllisre             | 1         | 0.15%   |
| GOODRAM             | 1         | 0.15%   |
| Goldkey             | 1         | 0.15%   |
| Essencore Limited   | 1         | 0.15%   |
| ASint Technology    | 1         | 0.15%   |
| Apacer              | 1         | 0.15%   |
| 48spaces            | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                           | 25        | 3.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 17        | 2.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s  | 16        | 2.25%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 11        | 1.55%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 9         | 1.27%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 8         | 1.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 8         | 1.13%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 7         | 0.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 7         | 0.99%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 7         | 0.99%   |
| Unknown                                                      | 7         | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 5         | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 5         | 0.7%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 5         | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 5         | 0.7%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 5         | 0.7%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 5         | 0.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 5         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 5         | 0.7%    |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 0.56%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s     | 4         | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 0.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 4         | 0.56%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 4         | 0.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 4         | 0.56%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 4         | 0.56%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 4         | 0.56%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 4         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 4         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 4         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 3         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 3         | 0.42%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 3         | 0.42%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s        | 3         | 0.42%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 0.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 3         | 0.42%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 3         | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s       | 3         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 281       | 48.2%   |
| DDR3    | 164       | 28.13%  |
| DDR2    | 57        | 9.78%   |
| LPDDR4  | 22        | 3.77%   |
| LPDDR3  | 19        | 3.26%   |
| LPDDR5  | 14        | 2.4%    |
| SDRAM   | 12        | 2.06%   |
| DDR5    | 8         | 1.37%   |
| DDR     | 4         | 0.69%   |
| Unknown | 2         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 499       | 85.45%  |
| Row Of Chips | 76        | 13.01%  |
| DIMM         | 4         | 0.68%   |
| Chip         | 3         | 0.51%   |
| Unknown      | 2         | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 222       | 35.13%  |
| 4096    | 168       | 26.58%  |
| 16384   | 100       | 15.82%  |
| 2048    | 95        | 15.03%  |
| 1024    | 23        | 3.64%   |
| 32768   | 19        | 3.01%   |
| 512     | 4         | 0.63%   |
| Unknown | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 131       | 21.16%  |
| 3200    | 120       | 19.39%  |
| 1600    | 105       | 16.96%  |
| Unknown | 47        | 7.59%   |
| 2400    | 31        | 5.01%   |
| 2133    | 31        | 5.01%   |
| 1334    | 23        | 3.72%   |
| 1333    | 17        | 2.75%   |
| 667     | 16        | 2.58%   |
| 6400    | 13        | 2.1%    |
| 8400    | 12        | 1.94%   |
| 4267    | 10        | 1.62%   |
| 1067    | 10        | 1.62%   |
| 4800    | 7         | 1.13%   |
| 3266    | 7         | 1.13%   |
| 4199    | 6         | 0.97%   |
| 1867    | 5         | 0.81%   |
| 800     | 5         | 0.81%   |
| 533     | 4         | 0.65%   |
| 1066    | 3         | 0.48%   |
| 975     | 3         | 0.48%   |
| 4266    | 2         | 0.32%   |
| 2933    | 2         | 0.32%   |
| 2048    | 2         | 0.32%   |
| 1866    | 2         | 0.32%   |
| 5600    | 1         | 0.16%   |
| 3733    | 1         | 0.16%   |
| 3000    | 1         | 0.16%   |
| 1200    | 1         | 0.16%   |
| 666     | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 4         | 44.44%  |
| Seiko Epson            | 2         | 22.22%  |
| STMicroelectronics     | 1         | 11.11%  |
| Samsung Electronics    | 1         | 11.11%  |
| Panasonic (Matsushita) | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 11.11%  |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 11.11%  |
| Seiko Epson AcuLaser C1700                                            | 1         | 11.11%  |
| Samsung ML-1640 Series Laser Printer                                  | 1         | 11.11%  |
| Panasonic (Matsushita) KX-FLB851SP                                    | 1         | 11.11%  |
| HP OfficeJet 3830 series                                              | 1         | 11.11%  |
| HP DeskJet F4100 Printer series                                       | 1         | 11.11%  |
| HP Deskjet 3050A                                                      | 1         | 11.11%  |
| HP DeskJet 2130 series                                                | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems BearPaw 2448 CU Pro | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 273       | 25.54%  |
| IMC Networks                           | 140       | 13.1%   |
| Realtek Semiconductor                  | 78        | 7.3%    |
| Suyin                                  | 55        | 5.14%   |
| Quanta                                 | 54        | 5.05%   |
| Bison Electronics                      | 50        | 4.68%   |
| Microdia                               | 47        | 4.4%    |
| Sunplus Innovation Technology          | 41        | 3.84%   |
| Cheng Uei Precision Industry (Foxlink) | 38        | 3.55%   |
| Ricoh                                  | 36        | 3.37%   |
| Syntek                                 | 34        | 3.18%   |
| Lite-On Technology                     | 33        | 3.09%   |
| Acer                                   | 31        | 2.9%    |
| Apple                                  | 25        | 2.34%   |
| Luxvisions Innotech Limited            | 22        | 2.06%   |
| Silicon Motion                         | 16        | 1.5%    |
| Logitech                               | 9         | 0.84%   |
| Alcor Micro                            | 9         | 0.84%   |
| Lenovo                                 | 8         | 0.75%   |
| Importek                               | 8         | 0.75%   |
| Z-Star Microelectronics                | 7         | 0.65%   |
| Sonix Technology                       | 7         | 0.65%   |
| Generalplus Technology                 | 5         | 0.47%   |
| SunplusIT                              | 4         | 0.37%   |
| Samsung Electronics                    | 4         | 0.37%   |
| WaveRider Communications               | 3         | 0.28%   |
| Creative Technology                    | 3         | 0.28%   |
| ALi                                    | 3         | 0.28%   |
| Y Media                                | 2         | 0.19%   |
| Primax Electronics                     | 2         | 0.19%   |
| Microsoft                              | 2         | 0.19%   |
| MacroSilicon                           | 2         | 0.19%   |
| icSpring                               | 2         | 0.19%   |
| DigiTech                               | 2         | 0.19%   |
| Trust                                  | 1         | 0.09%   |
| Tripath Technology                     | 1         | 0.09%   |
| ShineTech                              | 1         | 0.09%   |
| OmniVision Technologies                | 1         | 0.09%   |
| Mustek Systems                         | 1         | 0.09%   |
| lihappe8                               | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 40        | 3.73%   |
| Chicony Integrated Camera                           | 39        | 3.63%   |
| IMC Networks Integrated Camera                      | 28        | 2.61%   |
| Chicony HD WebCam                                   | 24        | 2.24%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 23        | 2.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 20        | 1.86%   |
| Realtek USB Camera                                  | 19        | 1.77%   |
| Chicony USB2.0 VGA UVC WebCam                       | 18        | 1.68%   |
| Microdia Integrated_Webcam_HD                       | 17        | 1.58%   |
| Realtek EasyCamera                                  | 14        | 1.3%    |
| Syntek Integrated Camera                            | 13        | 1.21%   |
| Chicony CNF9055 Toshiba Webcam                      | 13        | 1.21%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 12        | 1.12%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 1.12%   |
| Lite-On Integrated Camera                           | 12        | 1.12%   |
| Chicony TOSHIBA Web Camera - HD                     | 12        | 1.12%   |
| Acer Integrated Camera                              | 12        | 1.12%   |
| Realtek Integrated_Webcam_HD                        | 11        | 1.03%   |
| Chicony USB 2.0 Camera                              | 11        | 1.03%   |
| Bison Integrated Camera                             | 11        | 1.03%   |
| Quanta HP Wide Vision HD Camera                     | 10        | 0.93%   |
| IMC Networks HD Camera                              | 10        | 0.93%   |
| Chicony HP Truevision HD                            | 10        | 0.93%   |
| Bison HD Webcam                                     | 10        | 0.93%   |
| Quanta HP TrueVision HD Camera                      | 9         | 0.84%   |
| Suyin USB 2.0 Camera                                | 8         | 0.75%   |
| Chicony VGA Webcam                                  | 8         | 0.75%   |
| Chicony HP HD Camera                                | 8         | 0.75%   |
| Sunplus HD WebCam                                   | 7         | 0.65%   |
| Realtek HD WebCam                                   | 7         | 0.65%   |
| IMC Networks ov9734_azurewave_camera                | 7         | 0.65%   |
| Chicony USB2.0 HD UVC WebCam                        | 7         | 0.65%   |
| Chicony Integrated Camera (1280x720@30)             | 7         | 0.65%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 7         | 0.65%   |
| Apple FaceTime HD Camera                            | 7         | 0.65%   |
| Apple Built-in iSight                               | 7         | 0.65%   |
| Syntek Lenovo EasyCamera                            | 6         | 0.56%   |
| Syntek EasyCamera                                   | 6         | 0.56%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 0.56%   |
| Realtek USB2.0 HD UVC WebCam                        | 6         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 57        | 33.73%  |
| Validity Sensors                   | 52        | 30.77%  |
| Shenzhen Goodix Technology         | 26        | 15.38%  |
| AuthenTec                          | 10        | 5.92%   |
| Elan Microelectronics              | 8         | 4.73%   |
| Upek                               | 6         | 3.55%   |
| LighTuning Technology              | 5         | 2.96%   |
| STMicroelectronics                 | 3         | 1.78%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 19        | 11.24%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 7.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 4.73%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 4.73%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 3.55%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 3.55%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 2.96%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 2.96%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 2.96%   |
| Synaptics UWP WBDI Device                                                  | 5         | 2.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 2.96%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 2.96%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 2.37%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.37%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.37%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 2.37%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.37%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.37%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.37%   |
| AuthenTec AES2810                                                          | 4         | 2.37%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.78%   |
| Validity Sensors VFS491                                                    | 3         | 1.78%   |
| Synaptics WBDI Device                                                      | 3         | 1.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.78%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.78%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.78%   |
| AuthenTec AES1600                                                          | 3         | 1.78%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.18%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.18%   |
| Synaptics WBDI                                                             | 2         | 1.18%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.18%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.18%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.18%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.18%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.59%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.59%   |
| Synaptics UWP WBDI                                                         | 1         | 0.59%   |
| Synaptics TouchPad                                                         | 1         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 27        | 34.62%  |
| Broadcom              | 25        | 32.05%  |
| O2 Micro              | 6         | 7.69%   |
| Gemalto (was Gemplus) | 6         | 7.69%   |
| Upek                  | 3         | 3.85%   |
| Lenovo                | 3         | 3.85%   |
| SCM Microsystems      | 2         | 2.56%   |
| Realtek Semiconductor | 2         | 2.56%   |
| Yubico.com            | 1         | 1.28%   |
| CHERRY                | 1         | 1.28%   |
| Bit4id                | 1         | 1.28%   |
| Advanced Card Systems | 1         | 1.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 34.62%  |
| Broadcom 58200                                                               | 8         | 10.26%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 8.97%   |
| Broadcom 5880                                                                | 7         | 8.97%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 6.41%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 5.13%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 3.85%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.85%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.56%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 2.56%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 2.56%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.28%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.28%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.28%   |
| Bit4id miniLector EVO                                                        | 1         | 1.28%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 771       | 62.73%  |
| 1     | 353       | 28.72%  |
| 2     | 81        | 6.59%   |
| 3     | 18        | 1.46%   |
| 4     | 4         | 0.33%   |
| 5     | 2         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 167       | 29.72%  |
| Graphics card            | 145       | 25.8%   |
| Chipcard                 | 62        | 11.03%  |
| Net/wireless             | 61        | 10.85%  |
| Multimedia controller    | 48        | 8.54%   |
| Camera                   | 20        | 3.56%   |
| Bluetooth                | 18        | 3.2%    |
| Card reader              | 12        | 2.14%   |
| Communication controller | 8         | 1.42%   |
| Storage                  | 7         | 1.25%   |
| Modem                    | 4         | 0.71%   |
| Flash memory             | 4         | 0.71%   |
| Network                  | 2         | 0.36%   |
| Net/ethernet             | 2         | 0.36%   |
| Storage/ata              | 1         | 0.18%   |
| Sound                    | 1         | 0.18%   |


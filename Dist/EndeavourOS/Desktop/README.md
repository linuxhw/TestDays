EndeavourOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

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

Total: 405

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 18E4                        | [cab6d807e9](https://linux-hardware.org/?probe=cab6d807e9) | Feb 27, 2023 |
| HP            | 18E4                        | [5c7c3413c9](https://linux-hardware.org/?probe=5c7c3413c9) | Feb 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [ccff1403b0](https://linux-hardware.org/?probe=ccff1403b0) | Feb 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [576a0fc8f5](https://linux-hardware.org/?probe=576a0fc8f5) | Feb 23, 2023 |
| ASRock        | B460 Steel Legend           | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [d5f5531b82](https://linux-hardware.org/?probe=d5f5531b82) | Feb 20, 2023 |
| ASUSTek       | PRIME Z390-P                | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| ASUSTek       | BT6130                      | [b0693958a6](https://linux-hardware.org/?probe=b0693958a6) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | [c84212b39c](https://linux-hardware.org/?probe=c84212b39c) | Feb 15, 2023 |
| MSI           | 760GMA-P34                  | [6c540405e8](https://linux-hardware.org/?probe=6c540405e8) | Feb 15, 2023 |
| Alienware     | 0VDT73 A00                  | [d8ed5d5e88](https://linux-hardware.org/?probe=d8ed5d5e88) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [820aa2bf49](https://linux-hardware.org/?probe=820aa2bf49) | Feb 13, 2023 |
| MSI           | X470 GAMING PLUS            | [debdb17904](https://linux-hardware.org/?probe=debdb17904) | Feb 12, 2023 |
| MSI           | 760GMA-P34                  | [05d11c4fe3](https://linux-hardware.org/?probe=05d11c4fe3) | Feb 12, 2023 |
| Dell          | 0Y5FXV A00                  | [692b7eab6b](https://linux-hardware.org/?probe=692b7eab6b) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [43c3e4d160](https://linux-hardware.org/?probe=43c3e4d160) | Feb 06, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [96847498e3](https://linux-hardware.org/?probe=96847498e3) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [de7f0840d1](https://linux-hardware.org/?probe=de7f0840d1) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [4251ab2f9a](https://linux-hardware.org/?probe=4251ab2f9a) | Feb 01, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [55b2bf8aea](https://linux-hardware.org/?probe=55b2bf8aea) | Jan 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | [f1d22db1d7](https://linux-hardware.org/?probe=f1d22db1d7) | Jan 21, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [2c44f8275e](https://linux-hardware.org/?probe=2c44f8275e) | Jan 17, 2023 |
| ASUSTek       | PRIME B460M-A               | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| Unknown       | Unknown                     | [2e40c15660](https://linux-hardware.org/?probe=2e40c15660) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [154dafff1e](https://linux-hardware.org/?probe=154dafff1e) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [ce588e0413](https://linux-hardware.org/?probe=ce588e0413) | Jan 14, 2023 |
| ASUSTek       | PRIME Z390-P                | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [4fc1f3aff0](https://linux-hardware.org/?probe=4fc1f3aff0) | Jan 11, 2023 |
| MSI           | B450 TOMAHAWK               | [878c92decc](https://linux-hardware.org/?probe=878c92decc) | Jan 11, 2023 |
| HP            | 18E4                        | [600d82b264](https://linux-hardware.org/?probe=600d82b264) | Jan 11, 2023 |
| HP            | 18E4                        | [3386d53667](https://linux-hardware.org/?probe=3386d53667) | Jan 10, 2023 |
| HP            | 2179                        | [ad75cc2104](https://linux-hardware.org/?probe=ad75cc2104) | Jan 10, 2023 |
| Dell          | 0NRKPK A01                  | [f5bdf45b4a](https://linux-hardware.org/?probe=f5bdf45b4a) | Jan 08, 2023 |
| Dell          | 0J584C A00                  | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| Intel         | DH61DL AAG14066-205         | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c84118baf](https://linux-hardware.org/?probe=0c84118baf) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | [2d0530b779](https://linux-hardware.org/?probe=2d0530b779) | Jan 03, 2023 |
| MSI           | B250M PRO-VD                | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [b613cd1179](https://linux-hardware.org/?probe=b613cd1179) | Jan 02, 2023 |
| Intel         | DH61DL AAG14066-205         | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| Gigabyte      | P55A-UD3                    | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| HP            | 18E4                        | [c83c8341e3](https://linux-hardware.org/?probe=c83c8341e3) | Jan 01, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [20eb2d93e2](https://linux-hardware.org/?probe=20eb2d93e2) | Jan 01, 2023 |
| HP            | 18E4                        | [1b1eccbbe1](https://linux-hardware.org/?probe=1b1eccbbe1) | Dec 31, 2022 |
| Gigabyte      | H310M S2 x.x                | [9aba0ac647](https://linux-hardware.org/?probe=9aba0ac647) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [b38e3cc51e](https://linux-hardware.org/?probe=b38e3cc51e) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [adb13e2649](https://linux-hardware.org/?probe=adb13e2649) | Dec 29, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | [cd90f1782c](https://linux-hardware.org/?probe=cd90f1782c) | Dec 26, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | [78418bfaa6](https://linux-hardware.org/?probe=78418bfaa6) | Dec 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [348c431775](https://linux-hardware.org/?probe=348c431775) | Dec 23, 2022 |
| Gigabyte      | X570S AERO G                | [262a879a99](https://linux-hardware.org/?probe=262a879a99) | Dec 19, 2022 |
| HP            | 18E4                        | [26757adc9d](https://linux-hardware.org/?probe=26757adc9d) | Dec 15, 2022 |
| HP            | 18E4                        | [ba6bef79d5](https://linux-hardware.org/?probe=ba6bef79d5) | Dec 15, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [de70f43070](https://linux-hardware.org/?probe=de70f43070) | Dec 14, 2022 |
| HP            | 18E4                        | [00f1e4a14a](https://linux-hardware.org/?probe=00f1e4a14a) | Dec 14, 2022 |
| MSI           | B75MA-E33                   | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| ASRock        | X300M-STX                   | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| HP            | 18E4                        | [418a689ae5](https://linux-hardware.org/?probe=418a689ae5) | Dec 10, 2022 |
| MSI           | B450M-A PRO MAX             | [46a6e9e722](https://linux-hardware.org/?probe=46a6e9e722) | Dec 07, 2022 |
| HP            | 18E4                        | [e897549786](https://linux-hardware.org/?probe=e897549786) | Dec 06, 2022 |
| HP            | 18E4                        | [b12969b62f](https://linux-hardware.org/?probe=b12969b62f) | Dec 06, 2022 |
| MSI           | MEG Z490 UNIFY              | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1deadcff69](https://linux-hardware.org/?probe=1deadcff69) | Nov 27, 2022 |
| HP            | 18E4                        | [d72a174606](https://linux-hardware.org/?probe=d72a174606) | Nov 26, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [63521d3e8d](https://linux-hardware.org/?probe=63521d3e8d) | Nov 26, 2022 |
| HP            | 18E4                        | [4a4ac150b6](https://linux-hardware.org/?probe=4a4ac150b6) | Nov 24, 2022 |
| ASRock        | X570M Pro4                  | [2b2778b81a](https://linux-hardware.org/?probe=2b2778b81a) | Nov 24, 2022 |
| ASUSTek       | PRIME B460M-A               | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| HP            | 18E4                        | [ff954b29c9](https://linux-hardware.org/?probe=ff954b29c9) | Nov 21, 2022 |
| MSI           | B360 GAMING PLUS            | [6552f5cfc9](https://linux-hardware.org/?probe=6552f5cfc9) | Nov 18, 2022 |
| HP            | 18E4                        | [37dd18c268](https://linux-hardware.org/?probe=37dd18c268) | Nov 17, 2022 |
| HP            | 3397                        | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| HP            | 18E4                        | [be545cc91f](https://linux-hardware.org/?probe=be545cc91f) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [31cae1e989](https://linux-hardware.org/?probe=31cae1e989) | Nov 04, 2022 |
| HP            | 18E4                        | [66463ac87d](https://linux-hardware.org/?probe=66463ac87d) | Nov 04, 2022 |
| HP            | 18E4                        | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| Gigabyte      | P55A-UD3                    | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| ASRock        | B450M Pro4                  | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| HP            | 18E7                        | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| Acer          | Predator PO3-620            | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| HP            | 18E4                        | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| ASRock        | Z270 Killer SLI/ac          | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| Dell          | 040DDP A01                  | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3ab5922ddf](https://linux-hardware.org/?probe=3ab5922ddf) | Oct 25, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| ASRock        | A320M-HDV R4.0              | [17a0e006d0](https://linux-hardware.org/?probe=17a0e006d0) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | [c6966a0df9](https://linux-hardware.org/?probe=c6966a0df9) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | [5b4ecfb7e9](https://linux-hardware.org/?probe=5b4ecfb7e9) | Oct 25, 2022 |
| Dell          | 042P49 A02                  | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| HP            | 18E4                        | [dfbdab6987](https://linux-hardware.org/?probe=dfbdab6987) | Oct 21, 2022 |
| Gigabyte      | H87M-D3H                    | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [c8997eb831](https://linux-hardware.org/?probe=c8997eb831) | Oct 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [01338c4f3c](https://linux-hardware.org/?probe=01338c4f3c) | Oct 19, 2022 |
| ASRock        | B450 Pro4                   | [d7784759fb](https://linux-hardware.org/?probe=d7784759fb) | Oct 19, 2022 |
| MSI           | Z390-A PRO                  | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| MSI           | B250M PRO-VD                | [28d9942c9f](https://linux-hardware.org/?probe=28d9942c9f) | Oct 17, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [bf1677e47c](https://linux-hardware.org/?probe=bf1677e47c) | Oct 14, 2022 |
| ASUSTek       | PRIME B560M-A               | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| Gigabyte      | H81M-S2PV                   | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| HP            | 18E4                        | [6603067eba](https://linux-hardware.org/?probe=6603067eba) | Oct 10, 2022 |
| HP            | 18E4                        | [53c6bf7af4](https://linux-hardware.org/?probe=53c6bf7af4) | Oct 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [75e1aeaff5](https://linux-hardware.org/?probe=75e1aeaff5) | Oct 02, 2022 |
| ASUSTek       | PRIME Z390-P                | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| ASRock        | B450M-HDV R4.0              | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | [6e96f4620a](https://linux-hardware.org/?probe=6e96f4620a) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | [acb677ddeb](https://linux-hardware.org/?probe=acb677ddeb) | Sep 25, 2022 |
| ASRock        | B450 Pro4                   | [fe99b8a461](https://linux-hardware.org/?probe=fe99b8a461) | Sep 25, 2022 |
| ASUSTek       | SABERTOOTH P67              | [164ad85233](https://linux-hardware.org/?probe=164ad85233) | Sep 23, 2022 |
| AZW           | SEi                         | [579b2be420](https://linux-hardware.org/?probe=579b2be420) | Sep 23, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [d0f94bde46](https://linux-hardware.org/?probe=d0f94bde46) | Sep 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f4f33e2362](https://linux-hardware.org/?probe=f4f33e2362) | Sep 20, 2022 |
| ASUSTek       | SABERTOOTH P67              | [579f73fc88](https://linux-hardware.org/?probe=579f73fc88) | Sep 19, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [543fad9f1c](https://linux-hardware.org/?probe=543fad9f1c) | Sep 18, 2022 |
| HP            | 1998                        | [f3ef7a85fe](https://linux-hardware.org/?probe=f3ef7a85fe) | Sep 16, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| ASUSTek       | H170M-PLUS                  | [df80ca89ee](https://linux-hardware.org/?probe=df80ca89ee) | Sep 08, 2022 |
| Dell          | 0HMF7C A01                  | [292123f83b](https://linux-hardware.org/?probe=292123f83b) | Sep 03, 2022 |
| ASUSTek       | PRIME H310M-K               | [2fb52eb1a8](https://linux-hardware.org/?probe=2fb52eb1a8) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte      | P55A-UD3                    | [297cab0eb2](https://linux-hardware.org/?probe=297cab0eb2) | Sep 01, 2022 |
| HP            | 18E7                        | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| ASUSTek       | Maximus IX HERO             | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| ASRock        | B550M Pro4                  | [9b5ba9f755](https://linux-hardware.org/?probe=9b5ba9f755) | Aug 18, 2022 |
| MSI           | A320M PRO-E                 | [2aa966d8af](https://linux-hardware.org/?probe=2aa966d8af) | Aug 14, 2022 |
| ASUSTek       | PRIME X570-P                | [94579c3a70](https://linux-hardware.org/?probe=94579c3a70) | Aug 13, 2022 |
| AZW           | U59                         | [33aea75ff4](https://linux-hardware.org/?probe=33aea75ff4) | Aug 07, 2022 |
| Gigabyte      | B550M AORUS PRO             | [7a5337e18d](https://linux-hardware.org/?probe=7a5337e18d) | Jul 28, 2022 |
| ASRock        | A320M-HDV R4.0              | [06dd902359](https://linux-hardware.org/?probe=06dd902359) | Jul 23, 2022 |
| MSI           | PRO Z690-A WIFI             | [00f490c5d0](https://linux-hardware.org/?probe=00f490c5d0) | Jul 22, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b3f65d7c35](https://linux-hardware.org/?probe=b3f65d7c35) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | [d7e2758b93](https://linux-hardware.org/?probe=d7e2758b93) | Jul 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| Samsung       | DeskTop System              | [d0d33ec330](https://linux-hardware.org/?probe=d0d33ec330) | Jul 19, 2022 |
| Samsung       | DeskTop System              | [3af9bcc9cb](https://linux-hardware.org/?probe=3af9bcc9cb) | Jul 19, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [85a02f5d41](https://linux-hardware.org/?probe=85a02f5d41) | Jul 15, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HP            | 158B                        | [1f3ebf7ecf](https://linux-hardware.org/?probe=1f3ebf7ecf) | Jul 07, 2022 |
| Gigabyte      | N3160TN                     | [b92830b100](https://linux-hardware.org/?probe=b92830b100) | Jul 03, 2022 |
| Gigabyte      | P55A-UD3                    | [36dcdacdb1](https://linux-hardware.org/?probe=36dcdacdb1) | Jul 01, 2022 |
| ASRock        | B450M Pro4                  | [5dd727cd5e](https://linux-hardware.org/?probe=5dd727cd5e) | Jul 01, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| MSI           | B450 TOMAHAWK               | [b9a8ce148e](https://linux-hardware.org/?probe=b9a8ce148e) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | [16d7a07f8f](https://linux-hardware.org/?probe=16d7a07f8f) | Jun 20, 2022 |
| Dell          | 040DDP A01                  | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [b0cc04798d](https://linux-hardware.org/?probe=b0cc04798d) | Jun 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| MSI           | B450 TOMAHAWK               | [ed5235f3f4](https://linux-hardware.org/?probe=ed5235f3f4) | Jun 09, 2022 |
| ASUSTek       | SABERTOOTH X99              | [5c7a9690cf](https://linux-hardware.org/?probe=5c7a9690cf) | Jun 05, 2022 |
| ASUSTek       | H110M-E/M.2                 | [cb5ea65a1d](https://linux-hardware.org/?probe=cb5ea65a1d) | Jun 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| ASRock        | B450 Pro4                   | [394d112de5](https://linux-hardware.org/?probe=394d112de5) | May 31, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| Gigabyte      | B550M AORUS PRO             | [0075e2d9df](https://linux-hardware.org/?probe=0075e2d9df) | May 28, 2022 |
| Dell          | 0K240Y A01                  | [4ef7645f2d](https://linux-hardware.org/?probe=4ef7645f2d) | May 28, 2022 |
| HP            | 0A08h                       | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP            | 0A08h                       | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| ASRock        | A320M/ac                    | [78ee9c8853](https://linux-hardware.org/?probe=78ee9c8853) | May 20, 2022 |
| HP            | 3647h                       | [eccb82bec8](https://linux-hardware.org/?probe=eccb82bec8) | May 20, 2022 |
| HP            | 8906 SMVB                   | [0bc568827c](https://linux-hardware.org/?probe=0bc568827c) | May 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| MSI           | B75MA-E33                   | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| ASUSTek       | P8H77-M                     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [7354dedb38](https://linux-hardware.org/?probe=7354dedb38) | May 03, 2022 |
| ASRock        | B450 Pro4                   | [bcc65ca336](https://linux-hardware.org/?probe=bcc65ca336) | May 03, 2022 |
| ASRock        | B450 Pro4                   | [e40e784775](https://linux-hardware.org/?probe=e40e784775) | May 03, 2022 |
| ASRock        | AB350M Pro4                 | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| Gigabyte      | P55A-UD3                    | [b212517217](https://linux-hardware.org/?probe=b212517217) | May 01, 2022 |
| ASRock        | B450M Pro4                  | [79a3d8d3f6](https://linux-hardware.org/?probe=79a3d8d3f6) | May 01, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e45e120b35](https://linux-hardware.org/?probe=e45e120b35) | Apr 29, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a7eeea4f7c](https://linux-hardware.org/?probe=a7eeea4f7c) | Apr 27, 2022 |
| ASRock        | B560 Pro4                   | [5fdc5a8e7b](https://linux-hardware.org/?probe=5fdc5a8e7b) | Apr 21, 2022 |
| ASUSTek       | PRIME H410M-E               | [583693a1a9](https://linux-hardware.org/?probe=583693a1a9) | Apr 17, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1a48a9a11d](https://linux-hardware.org/?probe=1a48a9a11d) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [1ff04268cf](https://linux-hardware.org/?probe=1ff04268cf) | Apr 13, 2022 |
| ASRock        | B560 Pro4                   | [bbaa6e145b](https://linux-hardware.org/?probe=bbaa6e145b) | Apr 12, 2022 |
| Dell          | 0WMJ54 A01                  | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [0127833323](https://linux-hardware.org/?probe=0127833323) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| ASRock        | B450 Pro4                   | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| Gigabyte      | B450 GAMING X               | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Lenovo        | ThinkStation C20 426593U    | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [a0a0ba299e](https://linux-hardware.org/?probe=a0a0ba299e) | Mar 15, 2022 |
| Dell          | 0JP3NX A01                  | [e8f9fb7d24](https://linux-hardware.org/?probe=e8f9fb7d24) | Mar 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | P55A-UD3                    | [677fa0d0a3](https://linux-hardware.org/?probe=677fa0d0a3) | Mar 01, 2022 |
| ASRock        | B450M Pro4                  | [e81420b85c](https://linux-hardware.org/?probe=e81420b85c) | Mar 01, 2022 |
| MSI           | B75MA-P45                   | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell          | 0KWVT8 A03                  | [f4bc34ce43](https://linux-hardware.org/?probe=f4bc34ce43) | Feb 23, 2022 |
| ASRock        | B450M Pro4                  | [4f87ec9849](https://linux-hardware.org/?probe=4f87ec9849) | Feb 19, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [7ad21cbc90](https://linux-hardware.org/?probe=7ad21cbc90) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | [2bfd36f050](https://linux-hardware.org/?probe=2bfd36f050) | Feb 18, 2022 |
| MSI           | B450 TOMAHAWK               | [63d492d4bb](https://linux-hardware.org/?probe=63d492d4bb) | Feb 16, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a8c18662ff](https://linux-hardware.org/?probe=a8c18662ff) | Feb 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [64e32a1354](https://linux-hardware.org/?probe=64e32a1354) | Feb 02, 2022 |
| HP            | 1905                        | [8014fae46e](https://linux-hardware.org/?probe=8014fae46e) | Feb 02, 2022 |
| ASUSTek       | P8H77-V                     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| MSI           | B75MA-P45                   | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [5c5ac9fe1d](https://linux-hardware.org/?probe=5c5ac9fe1d) | Jan 26, 2022 |
| ASRock        | A320M-HD                    | [215b5c3802](https://linux-hardware.org/?probe=215b5c3802) | Jan 23, 2022 |
| MSI           | B150M ECO                   | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | [56e21b8bd6](https://linux-hardware.org/?probe=56e21b8bd6) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | [6586f2d78f](https://linux-hardware.org/?probe=6586f2d78f) | Jan 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| ASRock        | B550M Steel Legend          | [b09195fb3c](https://linux-hardware.org/?probe=b09195fb3c) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [211aac7b59](https://linux-hardware.org/?probe=211aac7b59) | Jan 18, 2022 |
| MSI           | Z170A GAMING M3             | [57e7500f2a](https://linux-hardware.org/?probe=57e7500f2a) | Jan 17, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [e1f153a5e6](https://linux-hardware.org/?probe=e1f153a5e6) | Jan 14, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [5ca44fe54c](https://linux-hardware.org/?probe=5ca44fe54c) | Jan 10, 2022 |
| ASUSTek       | Maximus VII GENE            | [0462560ab2](https://linux-hardware.org/?probe=0462560ab2) | Jan 10, 2022 |
| ASRock        | FM2A88X Pro3+               | [1cc054ed3f](https://linux-hardware.org/?probe=1cc054ed3f) | Jan 09, 2022 |
| Dell          | 0K240Y A01                  | [2542ffac8a](https://linux-hardware.org/?probe=2542ffac8a) | Jan 06, 2022 |
| MSI           | Z97 PC Mate                 | [2e5c796311](https://linux-hardware.org/?probe=2e5c796311) | Jan 06, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [aa4f09754b](https://linux-hardware.org/?probe=aa4f09754b) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [411cf580b4](https://linux-hardware.org/?probe=411cf580b4) | Jan 04, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| MSI           | Z490-A PRO                  | [ab40f6782f](https://linux-hardware.org/?probe=ab40f6782f) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Positivo      | POS-PIH81DI                 | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| ASUSTek       | Z97-A                       | [1ebd581629](https://linux-hardware.org/?probe=1ebd581629) | Jan 01, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| ASRock        | B450 Steel Legend           | [9a67c15230](https://linux-hardware.org/?probe=9a67c15230) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| MSI           | B450 TOMAHAWK               | [c85d7c78e7](https://linux-hardware.org/?probe=c85d7c78e7) | Dec 28, 2021 |
| LattePanda    | Alpha                       | [497e370fc3](https://linux-hardware.org/?probe=497e370fc3) | Dec 26, 2021 |
| Biostar       | G31-M7 TE                   | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| LattePanda    | Alpha                       | [442f08d351](https://linux-hardware.org/?probe=442f08d351) | Dec 24, 2021 |
| Gigabyte      | M68M-S2P                    | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Acer          | Aspire XC-1660G V:1.1       | [c460e492aa](https://linux-hardware.org/?probe=c460e492aa) | Dec 23, 2021 |
| Gigabyte      | H110N-CF                    | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| MSI           | Z87-G41 PC Mate             | [aa7388fdd1](https://linux-hardware.org/?probe=aa7388fdd1) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| Unknown       | Intel X79                   | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| Dell          | 0HD5W2 A01                  | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [8c9d779e45](https://linux-hardware.org/?probe=8c9d779e45) | Dec 14, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [641af2bfa6](https://linux-hardware.org/?probe=641af2bfa6) | Dec 13, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| MSI           | B350 PC MATE                | [7fbe80215d](https://linux-hardware.org/?probe=7fbe80215d) | Nov 24, 2021 |
| Gigabyte      | B560M DS3H                  | [89ea080ce0](https://linux-hardware.org/?probe=89ea080ce0) | Nov 20, 2021 |
| ASUSTek       | Z87-DELUXE                  | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte      | B560M DS3H                  | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| Gigabyte      | Z77X-D3H                    | [be03431631](https://linux-hardware.org/?probe=be03431631) | Nov 15, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [7ebeace900](https://linux-hardware.org/?probe=7ebeace900) | Nov 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [1cfd4ee9f9](https://linux-hardware.org/?probe=1cfd4ee9f9) | Nov 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [c9e5138184](https://linux-hardware.org/?probe=c9e5138184) | Nov 07, 2021 |
| ASUSTek       | Maximus VIII HERO           | [22ce2703b9](https://linux-hardware.org/?probe=22ce2703b9) | Nov 07, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [5d0bad7c15](https://linux-hardware.org/?probe=5d0bad7c15) | Nov 06, 2021 |
| ASRock        | H310CM-DVS                  | [79e6ef3655](https://linux-hardware.org/?probe=79e6ef3655) | Oct 29, 2021 |
| ASRock        | H310CM-DVS                  | [6db3b9d661](https://linux-hardware.org/?probe=6db3b9d661) | Oct 29, 2021 |
| Gigabyte      | B450 GAMING X               | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| ASRock        | B550M Pro4                  | [87ab64b604](https://linux-hardware.org/?probe=87ab64b604) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| UMAX          | J42 Nano                    | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| Gigabyte      | B85M-HD3                    | [cc7d0245a7](https://linux-hardware.org/?probe=cc7d0245a7) | Oct 09, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [849ca2da3d](https://linux-hardware.org/?probe=849ca2da3d) | Oct 06, 2021 |
| Gigabyte      | B550 VISION D               | [e8a2ba9952](https://linux-hardware.org/?probe=e8a2ba9952) | Oct 03, 2021 |
| MSI           | G41M-P33 Combo              | [ec8e63e96e](https://linux-hardware.org/?probe=ec8e63e96e) | Oct 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Gigabyte      | H110M-S2-CF                 | [a20f426eed](https://linux-hardware.org/?probe=a20f426eed) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [35cbc8e5b5](https://linux-hardware.org/?probe=35cbc8e5b5) | Sep 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [860fb3dc8c](https://linux-hardware.org/?probe=860fb3dc8c) | Sep 19, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [8ffa4dd273](https://linux-hardware.org/?probe=8ffa4dd273) | Sep 18, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [60555ce93d](https://linux-hardware.org/?probe=60555ce93d) | Sep 16, 2021 |
| MSI           | B450M PRO-VDH MAX           | [33cee010e8](https://linux-hardware.org/?probe=33cee010e8) | Sep 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [c06b4b30a0](https://linux-hardware.org/?probe=c06b4b30a0) | Sep 10, 2021 |
| MSI           | B450-A PRO MAX              | [12cf057e04](https://linux-hardware.org/?probe=12cf057e04) | Sep 02, 2021 |
| Intel         | DH55HC AAE70933-504         | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [1c75e967eb](https://linux-hardware.org/?probe=1c75e967eb) | Aug 24, 2021 |
| HP            | 8906 SMVB                   | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| Gigabyte      | P35-DS3R                    | [421cd7ce36](https://linux-hardware.org/?probe=421cd7ce36) | Aug 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [8e9d51a941](https://linux-hardware.org/?probe=8e9d51a941) | Aug 07, 2021 |
| Dell          | 0K240Y A01                  | [5cc92cb5ac](https://linux-hardware.org/?probe=5cc92cb5ac) | Aug 04, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [404eae69f4](https://linux-hardware.org/?probe=404eae69f4) | Jul 14, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [f36328f6b3](https://linux-hardware.org/?probe=f36328f6b3) | Jul 12, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [14b3d46ef8](https://linux-hardware.org/?probe=14b3d46ef8) | Jul 03, 2021 |
| ASUSTek       | P7H55D-M EVO                | [62f256e36e](https://linux-hardware.org/?probe=62f256e36e) | Jul 03, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| Gigabyte      | Z97X-Gaming 5               | [625c876e08](https://linux-hardware.org/?probe=625c876e08) | Jun 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [10c5bbf0f8](https://linux-hardware.org/?probe=10c5bbf0f8) | Jun 18, 2021 |
| ASUSTek       | F1A55-M LX                  | [9e7c39435d](https://linux-hardware.org/?probe=9e7c39435d) | Jun 13, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [ed31182c51](https://linux-hardware.org/?probe=ed31182c51) | Jun 07, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [585db3001d](https://linux-hardware.org/?probe=585db3001d) | May 19, 2021 |
| HP            | 2B36                        | [62135f1e45](https://linux-hardware.org/?probe=62135f1e45) | May 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fec75a202e](https://linux-hardware.org/?probe=fec75a202e) | May 19, 2021 |
| ASRock        | A300M-STX                   | [fc96347868](https://linux-hardware.org/?probe=fc96347868) | May 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [dd68978e2b](https://linux-hardware.org/?probe=dd68978e2b) | Apr 28, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [7ee064e334](https://linux-hardware.org/?probe=7ee064e334) | Apr 27, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [8276e1fb2f](https://linux-hardware.org/?probe=8276e1fb2f) | Apr 20, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [cf4d5786e5](https://linux-hardware.org/?probe=cf4d5786e5) | Apr 19, 2021 |
| Lenovo        | SHARKBAY NOK                | [0685ce717e](https://linux-hardware.org/?probe=0685ce717e) | Apr 16, 2021 |
| Gigabyte      | B550M AORUS PRO             | [a635a3acb3](https://linux-hardware.org/?probe=a635a3acb3) | Apr 13, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [e08e82478f](https://linux-hardware.org/?probe=e08e82478f) | Apr 12, 2021 |
| Gigabyte      | B450 AORUS M                | [d53c2a8b0e](https://linux-hardware.org/?probe=d53c2a8b0e) | Apr 11, 2021 |
| Dell          | 0080PM A00                  | [efc9497e6d](https://linux-hardware.org/?probe=efc9497e6d) | Apr 08, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [63e7ed5aa3](https://linux-hardware.org/?probe=63e7ed5aa3) | Apr 07, 2021 |
| Lenovo        | 36EB NOK                    | [2c6f4de8b9](https://linux-hardware.org/?probe=2c6f4de8b9) | Apr 06, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [08f8da317e](https://linux-hardware.org/?probe=08f8da317e) | Apr 03, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [90f906f5f9](https://linux-hardware.org/?probe=90f906f5f9) | Mar 31, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [b2fa0502d0](https://linux-hardware.org/?probe=b2fa0502d0) | Mar 31, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [31baa57d40](https://linux-hardware.org/?probe=31baa57d40) | Mar 17, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [7c5776953c](https://linux-hardware.org/?probe=7c5776953c) | Mar 15, 2021 |
| Gigabyte      | B550M AORUS PRO             | [41de0a7ee7](https://linux-hardware.org/?probe=41de0a7ee7) | Mar 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f9b4d57c67](https://linux-hardware.org/?probe=f9b4d57c67) | Feb 18, 2021 |
| MSI           | Z87-G45 GAMING              | [67ca38a642](https://linux-hardware.org/?probe=67ca38a642) | Feb 12, 2021 |
| MSI           | Z87-G45 GAMING              | [e6937666ae](https://linux-hardware.org/?probe=e6937666ae) | Feb 11, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [e11200bd19](https://linux-hardware.org/?probe=e11200bd19) | Feb 10, 2021 |
| ASUSTek       | H81-PLUS                    | [75fc956099](https://linux-hardware.org/?probe=75fc956099) | Feb 10, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [cef326fa21](https://linux-hardware.org/?probe=cef326fa21) | Feb 08, 2021 |
| ASRock        | B550M Steel Legend          | [335242ec06](https://linux-hardware.org/?probe=335242ec06) | Jan 20, 2021 |
| ASUSTek       | PRIME X470-PRO              | [396227c9b5](https://linux-hardware.org/?probe=396227c9b5) | Jan 14, 2021 |
| Gigabyte      | X58A-UD3R                   | [3d8c62e8fe](https://linux-hardware.org/?probe=3d8c62e8fe) | Jan 04, 2021 |
| ASUSTek       | Z87-PRO                     | [2ab19967fa](https://linux-hardware.org/?probe=2ab19967fa) | Dec 30, 2020 |
| ASUSTek       | Maximus VIII HERO           | [4d27980548](https://linux-hardware.org/?probe=4d27980548) | Dec 27, 2020 |
| ASUSTek       | Maximus VIII HERO           | [08895b552f](https://linux-hardware.org/?probe=08895b552f) | Dec 27, 2020 |
| HP            | 1905                        | [63771015f5](https://linux-hardware.org/?probe=63771015f5) | Dec 22, 2020 |
| Gigabyte      | H110M-S2-CF                 | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| Gigabyte      | X58A-UD3R                   | [a138dbf3ac](https://linux-hardware.org/?probe=a138dbf3ac) | Dec 08, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [00dc0236a1](https://linux-hardware.org/?probe=00dc0236a1) | Dec 07, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [0ffe9c1f28](https://linux-hardware.org/?probe=0ffe9c1f28) | Nov 27, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| Dell          | 0KRC95 A02                  | [af91587001](https://linux-hardware.org/?probe=af91587001) | Nov 19, 2020 |
| ASRock        | Z77 Extreme4                | [3de701fc00](https://linux-hardware.org/?probe=3de701fc00) | Nov 12, 2020 |
| ASRock        | Z77 Extreme4                | [64d986c0ec](https://linux-hardware.org/?probe=64d986c0ec) | Nov 12, 2020 |
| Dell          | 0KRC95 A02                  | [6471eccd57](https://linux-hardware.org/?probe=6471eccd57) | Nov 11, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7a14486580](https://linux-hardware.org/?probe=7a14486580) | Nov 04, 2020 |
| Gigabyte      | H270-HD3-CF                 | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| HP            | 8455                        | [0671b6f4da](https://linux-hardware.org/?probe=0671b6f4da) | Oct 27, 2020 |
| HP            | 8455                        | [e37d606b6b](https://linux-hardware.org/?probe=e37d606b6b) | Oct 26, 2020 |
| Dell          | 0G214D A00                  | [21319d118b](https://linux-hardware.org/?probe=21319d118b) | Oct 25, 2020 |
| MSI           | MS-7366                     | [ada828f120](https://linux-hardware.org/?probe=ada828f120) | Sep 29, 2020 |
| Dell          | 096JG8 A01                  | [a031f4a8a2](https://linux-hardware.org/?probe=a031f4a8a2) | Sep 29, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [ee969068e8](https://linux-hardware.org/?probe=ee969068e8) | Sep 28, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a4e794299b](https://linux-hardware.org/?probe=a4e794299b) | Sep 28, 2020 |
| ASUSTek       | P8P67 DELUXE                | [ba15c37977](https://linux-hardware.org/?probe=ba15c37977) | Sep 28, 2020 |
| MSI           | MS-7366                     | [9938e6501b](https://linux-hardware.org/?probe=9938e6501b) | Sep 24, 2020 |
| Gigabyte      | B450 AORUS M                | [34f1896f7e](https://linux-hardware.org/?probe=34f1896f7e) | Sep 23, 2020 |
| Gigabyte      | B550M AORUS PRO             | [17e933a69c](https://linux-hardware.org/?probe=17e933a69c) | Sep 21, 2020 |
| HP            | 1497                        | [7cb2cee563](https://linux-hardware.org/?probe=7cb2cee563) | Sep 19, 2020 |
| Gigabyte      | B550M AORUS PRO             | [50a3035c47](https://linux-hardware.org/?probe=50a3035c47) | Sep 12, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3919584d23](https://linux-hardware.org/?probe=3919584d23) | Sep 06, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [028f3ba060](https://linux-hardware.org/?probe=028f3ba060) | Sep 03, 2020 |
| ASUSTek       | M5A97 R2.0                  | [662f61d283](https://linux-hardware.org/?probe=662f61d283) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [143c679f1a](https://linux-hardware.org/?probe=143c679f1a) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2ab9b15cb6](https://linux-hardware.org/?probe=2ab9b15cb6) | Sep 03, 2020 |
| Gigabyte      | Z170-Gaming K3-CF           | [f70636a60c](https://linux-hardware.org/?probe=f70636a60c) | Sep 02, 2020 |
| ASUSTek       | Z87M-PLUS                   | [844cca1bee](https://linux-hardware.org/?probe=844cca1bee) | Aug 09, 2020 |
| ASUSTek       | PRIME X570-P                | [cb7a700ec4](https://linux-hardware.org/?probe=cb7a700ec4) | Aug 07, 2020 |
| Gigabyte      | B365M DS3H                  | [79c5cea1c1](https://linux-hardware.org/?probe=79c5cea1c1) | Jul 14, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [54774ae912](https://linux-hardware.org/?probe=54774ae912) | Jul 14, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [85295c522b](https://linux-hardware.org/?probe=85295c522b) | Jul 14, 2020 |
| Lenovo        | MAHOBAY NOK                 | [6e3c82fbca](https://linux-hardware.org/?probe=6e3c82fbca) | Jul 13, 2020 |
| ASUSTek       | Z87M-PLUS                   | [d0c246206e](https://linux-hardware.org/?probe=d0c246206e) | Jul 13, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [5ed412893a](https://linux-hardware.org/?probe=5ed412893a) | Jul 12, 2020 |
| Gigabyte      | B365M DS3H                  | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [b81603bb8b](https://linux-hardware.org/?probe=b81603bb8b) | Jul 12, 2020 |
| MSI           | B450-A PRO MAX              | [22ee76b578](https://linux-hardware.org/?probe=22ee76b578) | Jun 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eb81165361](https://linux-hardware.org/?probe=eb81165361) | May 31, 2020 |
| Biostar       | G31-M7 TE                   | [0ae18cfc51](https://linux-hardware.org/?probe=0ae18cfc51) | May 05, 2020 |
| Gigabyte      | B85M-D3H                    | [adba7e2f11](https://linux-hardware.org/?probe=adba7e2f11) | Apr 24, 2020 |
| ASUSTek       | PRIME A320M-K               | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Gigabyte      | B450M S2H                   | [5a1d01743b](https://linux-hardware.org/?probe=5a1d01743b) | Feb 12, 2020 |
| ASUSTek       | PRIME A320M-K               | [32f5e3b842](https://linux-hardware.org/?probe=32f5e3b842) | Nov 21, 2019 |
| ASUSTek       | PRIME A320M-K               | [4d0de4b06b](https://linux-hardware.org/?probe=4d0de4b06b) | Nov 19, 2019 |
| ASUSTek       | PRIME A320M-K               | [791bd283a6](https://linux-hardware.org/?probe=791bd283a6) | Nov 18, 2019 |
| ASUSTek       | PRIME A320M-K               | [50ea35444e](https://linux-hardware.org/?probe=50ea35444e) | Nov 17, 2019 |
| ASUSTek       | PRIME A320M-K               | [42a25ee1f6](https://linux-hardware.org/?probe=42a25ee1f6) | Nov 08, 2019 |
| ASUSTek       | PRIME A320M-K               | [587cf1258f](https://linux-hardware.org/?probe=587cf1258f) | Nov 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| EndeavourOS Rolling | 221      | 78.65%  |
| EndeavourOS         | 60       | 21.35%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| EndeavourOS | 278      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.15.12-arch1-1    | 10       | 3.03%   |
| 6.1.1-arch1-1      | 8        | 2.42%   |
| 5.7.7-arch1-1      | 6        | 1.82%   |
| 6.0.2-zen1-1-zen   | 5        | 1.52%   |
| 6.0.2-arch1-1      | 5        | 1.52%   |
| 5.17.5-arch1-1     | 5        | 1.52%   |
| 5.17.1-arch1-1     | 5        | 1.52%   |
| 5.16.2-arch1-1     | 5        | 1.52%   |
| 6.1.12-arch1-1     | 4        | 1.21%   |
| 6.0.9-arch1-1      | 4        | 1.21%   |
| 5.18.12-arch1-1    | 4        | 1.21%   |
| 5.15.74-1-lts      | 4        | 1.21%   |
| 5.15.7-arch1-1     | 4        | 1.21%   |
| 5.11.11-arch1-1    | 4        | 1.21%   |
| 6.1.11-arch1-1     | 3        | 0.91%   |
| 6.1.1-zen1-1-zen   | 3        | 0.91%   |
| 6.0.6-arch1-1      | 3        | 0.91%   |
| 5.19.10-arch1-1    | 3        | 0.91%   |
| 5.18.7-arch1-1     | 3        | 0.91%   |
| 5.18.5-arch1-1     | 3        | 0.91%   |
| 5.18.14-arch1-1    | 3        | 0.91%   |
| 5.17.9-arch1-1     | 3        | 0.91%   |
| 5.16.16-arch1-1    | 3        | 0.91%   |
| 5.16.10-arch1-1    | 3        | 0.91%   |
| 5.15.8-arch1-1     | 3        | 0.91%   |
| 5.15.12-zen1-1-zen | 3        | 0.91%   |
| 5.15.10-arch1-1    | 3        | 0.91%   |
| 5.14.9-arch2-1     | 3        | 0.91%   |
| 5.14.8-arch1-1     | 3        | 0.91%   |
| 5.10.88-2-lts      | 3        | 0.91%   |
| 6.1.9-arch1-2      | 2        | 0.61%   |
| 6.1.8-arch1-1      | 2        | 0.61%   |
| 6.1.4-zen2-1-zen   | 2        | 0.61%   |
| 6.1.4-arch1-1      | 2        | 0.61%   |
| 6.1.3-arch1-1      | 2        | 0.61%   |
| 6.0.8-arch1-1      | 2        | 0.61%   |
| 6.0.6-zen1-1-zen   | 2        | 0.61%   |
| 6.0.12-arch1-1     | 2        | 0.61%   |
| 6.0.11-zen1-1-zen  | 2        | 0.61%   |
| 5.9.14-arch1-1     | 2        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.12 | 14       | 4.24%   |
| 6.1.1   | 11       | 3.33%   |
| 6.0.2   | 10       | 3.03%   |
| 5.17.5  | 7        | 2.12%   |
| 5.7.7   | 6        | 1.82%   |
| 6.0.9   | 5        | 1.52%   |
| 6.0.6   | 5        | 1.52%   |
| 5.19.9  | 5        | 1.52%   |
| 5.18.12 | 5        | 1.52%   |
| 5.17.1  | 5        | 1.52%   |
| 5.16.2  | 5        | 1.52%   |
| 5.16.16 | 5        | 1.52%   |
| 5.15.7  | 5        | 1.52%   |
| 6.1.4   | 4        | 1.21%   |
| 6.1.12  | 4        | 1.21%   |
| 6.0.11  | 4        | 1.21%   |
| 5.8.5   | 4        | 1.21%   |
| 5.18.5  | 4        | 1.21%   |
| 5.17.9  | 4        | 1.21%   |
| 5.15.74 | 4        | 1.21%   |
| 5.11.11 | 4        | 1.21%   |
| 5.10.88 | 4        | 1.21%   |
| 6.1.8   | 3        | 0.91%   |
| 6.1.11  | 3        | 0.91%   |
| 6.0.12  | 3        | 0.91%   |
| 5.9.1   | 3        | 0.91%   |
| 5.19.5  | 3        | 0.91%   |
| 5.19.10 | 3        | 0.91%   |
| 5.18.7  | 3        | 0.91%   |
| 5.18.14 | 3        | 0.91%   |
| 5.16.11 | 3        | 0.91%   |
| 5.16.10 | 3        | 0.91%   |
| 5.15.8  | 3        | 0.91%   |
| 5.15.13 | 3        | 0.91%   |
| 5.15.11 | 3        | 0.91%   |
| 5.15.10 | 3        | 0.91%   |
| 5.14.9  | 3        | 0.91%   |
| 5.14.8  | 3        | 0.91%   |
| 5.12.15 | 3        | 0.91%   |
| 6.1.9   | 2        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 53       | 16.51%  |
| 6.1     | 33       | 10.28%  |
| 6.0     | 31       | 9.66%   |
| 5.18    | 28       | 8.72%   |
| 5.16    | 25       | 7.79%   |
| 5.19    | 22       | 6.85%   |
| 5.17    | 22       | 6.85%   |
| 5.14    | 17       | 5.3%    |
| 5.10    | 15       | 4.67%   |
| 5.11    | 14       | 4.36%   |
| 5.9     | 13       | 4.05%   |
| 5.12    | 13       | 4.05%   |
| 5.8     | 10       | 3.12%   |
| 5.7     | 9        | 2.8%    |
| 5.13    | 7        | 2.18%   |
| 5.6     | 3        | 0.93%   |
| 6.2     | 2        | 0.62%   |
| 5.5     | 2        | 0.62%   |
| 5.4     | 1        | 0.31%   |
| Unknown | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 278      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 117      | 40.07%  |
| XFCE            | 58       | 19.86%  |
| GNOME           | 51       | 17.47%  |
| i3              | 16       | 5.48%   |
| X-Cinnamon      | 13       | 4.45%   |
| KDE             | 11       | 3.77%   |
| Budgie          | 7        | 2.4%    |
| Cinnamon        | 4        | 1.37%   |
| sway            | 3        | 1.03%   |
| LXQt            | 3        | 1.03%   |
| Unknown         | 3        | 1.03%   |
| MATE            | 2        | 0.68%   |
| jwm             | 1        | 0.34%   |
| herbstluftwm    | 1        | 0.34%   |
| GNOME Flashback | 1        | 0.34%   |
| awesome         | 1        | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 241      | 83.97%  |
| Wayland | 33       | 11.5%   |
| Tty     | 9        | 3.14%   |
| Unknown | 3        | 1.05%   |
| Web     | 1        | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 88       | 30.88%  |
| Unknown | 78       | 27.37%  |
| SDDM    | 72       | 25.26%  |
| GDM     | 27       | 9.47%   |
| TDM     | 20       | 7.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 134      | 48.03%  |
| de_DE   | 23       | 8.24%   |
| en_GB   | 22       | 7.89%   |
| it_IT   | 17       | 6.09%   |
| en_CA   | 11       | 3.94%   |
| ru_RU   | 8        | 2.87%   |
| pl_PL   | 6        | 2.15%   |
| en_IN   | 4        | 1.43%   |
| en_DK   | 4        | 1.43%   |
| en_AG   | 4        | 1.43%   |
| pt_BR   | 3        | 1.08%   |
| nl_NL   | 3        | 1.08%   |
| nl_BE   | 3        | 1.08%   |
| fr_FR   | 3        | 1.08%   |
| es_AR   | 3        | 1.08%   |
| en_AU   | 3        | 1.08%   |
| Unknown | 3        | 1.08%   |
| tr_TR   | 2        | 0.72%   |
| es_MX   | 2        | 0.72%   |
| es_ES   | 2        | 0.72%   |
| en_HK   | 2        | 0.72%   |
| de_AT   | 2        | 0.72%   |
| sv_SE   | 1        | 0.36%   |
| sl_SI   | 1        | 0.36%   |
| pt_PT   | 1        | 0.36%   |
| hu_HU   | 1        | 0.36%   |
| fr_CA   | 1        | 0.36%   |
| fr_BE   | 1        | 0.36%   |
| fi_FI   | 1        | 0.36%   |
| es_GT   | 1        | 0.36%   |
| es_CR   | 1        | 0.36%   |
| eo      | 1        | 0.36%   |
| en_ZA   | 1        | 0.36%   |
| en_SG   | 1        | 0.36%   |
| en_FI   | 1        | 0.36%   |
| de_CH   | 1        | 0.36%   |
| cs_CZ   | 1        | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 162      | 57.65%  |
| BIOS | 119      | 42.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 193      | 69.18%  |
| Btrfs   | 78       | 27.96%  |
| Overlay | 4        | 1.43%   |
| Xfs     | 2        | 0.72%   |
| XXX4    | 1        | 0.36%   |
| F2fs    | 1        | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 175      | 62.28%  |
| Unknown | 83       | 29.54%  |
| MBR     | 23       | 8.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 223      | 79.36%  |
| Yes       | 58       | 20.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 169      | 59.3%   |
| Yes       | 116      | 40.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 76       | 27.34%  |
| MSI                                  | 57       | 20.5%   |
| Gigabyte Technology                  | 57       | 20.5%   |
| ASRock                               | 29       | 10.43%  |
| Hewlett-Packard                      | 16       | 5.76%   |
| Dell                                 | 14       | 5.04%   |
| Lenovo                               | 8        | 2.88%   |
| Samsung Electronics                  | 2        | 0.72%   |
| Intel                                | 2        | 0.72%   |
| Fujitsu                              | 2        | 0.72%   |
| Biostar                              | 2        | 0.72%   |
| AZW                                  | 2        | 0.72%   |
| Acer                                 | 2        | 0.72%   |
| Unknown                              | 2        | 0.72%   |
| UMAX                                 | 1        | 0.36%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.36%   |
| Positivo                             | 1        | 0.36%   |
| Medion                               | 1        | 0.36%   |
| LattePanda                           | 1        | 0.36%   |
| Huanan                               | 1        | 0.36%   |
| Alienware                            | 1        | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| MSI MS-7C37                                | 10       | 3.6%    |
| ASUS All Series                            | 8        | 2.88%   |
| ASUS ROG STRIX X570-E GAMING               | 5        | 1.8%    |
| MSI MS-7C02                                | 4        | 1.44%   |
| ASUS TUF Gaming X570-PLUS                  | 4        | 1.44%   |
| ASRock B450M Pro4                          | 4        | 1.44%   |
| ASRock B450 Pro4                           | 4        | 1.44%   |
| MSI MS-7C91                                | 3        | 1.08%   |
| MSI MS-7A38                                | 3        | 1.08%   |
| Gigabyte B550M AORUS PRO                   | 3        | 1.08%   |
| Gigabyte B450M DS3H                        | 3        | 1.08%   |
| MSI MS-7C84                                | 2        | 0.72%   |
| MSI MS-7B86                                | 2        | 0.72%   |
| MSI MS-7B85                                | 2        | 0.72%   |
| MSI MS-7A74                                | 2        | 0.72%   |
| MSI MS-7850                                | 2        | 0.72%   |
| MSI MS-7798                                | 2        | 0.72%   |
| HP Z230 Tower Workstation                  | 2        | 0.72%   |
| HP ProDesk 600 G1 SFF                      | 2        | 0.72%   |
| Gigabyte H110M-S2                          | 2        | 0.72%   |
| Gigabyte B550 AORUS ELITE V2               | 2        | 0.72%   |
| Gigabyte B450M S2H                         | 2        | 0.72%   |
| Gigabyte B450 AORUS ELITE                  | 2        | 0.72%   |
| Dell OptiPlex 3020                         | 2        | 0.72%   |
| Biostar G31-M7 TE                          | 2        | 0.72%   |
| ASUS ROG CROSSHAIR VIII DARK HERO          | 2        | 0.72%   |
| ASUS PRIME X570-P                          | 2        | 0.72%   |
| ASUS K30AD_M31AD_M51AD                     | 2        | 0.72%   |
| ASRock B550M Steel Legend                  | 2        | 0.72%   |
| ASRock B550M Pro4                          | 2        | 0.72%   |
| Unknown                                    | 2        | 0.72%   |
| UMAX J42 Nano                              | 1        | 0.36%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.36%   |
| Samsung DeskTop System                     | 1        | 0.36%   |
| Samsung 500T8A/500S8A/500T9A/500S9A        | 1        | 0.36%   |
| Positivo POS-PIH81DI                       | 1        | 0.36%   |
| MSI MS-7D52                                | 1        | 0.36%   |
| MSI MS-7D43                                | 1        | 0.36%   |
| MSI MS-7D25                                | 1        | 0.36%   |
| MSI MS-7D19                                | 1        | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 16       | 5.76%   |
| ASUS PRIME           | 15       | 5.4%    |
| ASUS TUF             | 14       | 5.04%   |
| MSI MS-7C37          | 10       | 3.6%    |
| Dell OptiPlex        | 9        | 3.24%   |
| ASUS All             | 8        | 2.88%   |
| ASRock B450          | 6        | 2.16%   |
| Gigabyte B550        | 5        | 1.8%    |
| Gigabyte B450M       | 5        | 1.8%    |
| Gigabyte B450        | 5        | 1.8%    |
| MSI MS-7C02          | 4        | 1.44%   |
| Lenovo ThinkCentre   | 4        | 1.44%   |
| Gigabyte X570        | 4        | 1.44%   |
| Gigabyte B550M       | 4        | 1.44%   |
| ASRock B550M         | 4        | 1.44%   |
| ASRock B450M         | 4        | 1.44%   |
| MSI MS-7C91          | 3        | 1.08%   |
| MSI MS-7A38          | 3        | 1.08%   |
| Gigabyte Z390        | 3        | 1.08%   |
| MSI MS-7C84          | 2        | 0.72%   |
| MSI MS-7B86          | 2        | 0.72%   |
| MSI MS-7B85          | 2        | 0.72%   |
| MSI MS-7A74          | 2        | 0.72%   |
| MSI MS-7850          | 2        | 0.72%   |
| MSI MS-7798          | 2        | 0.72%   |
| Lenovo IdeaCentre    | 2        | 0.72%   |
| HP Z230              | 2        | 0.72%   |
| HP ProDesk           | 2        | 0.72%   |
| HP Pavilion          | 2        | 0.72%   |
| HP EliteDesk         | 2        | 0.72%   |
| HP Compaq            | 2        | 0.72%   |
| Gigabyte Z97X-Gaming | 2        | 0.72%   |
| Gigabyte H110M-S2    | 2        | 0.72%   |
| Fujitsu CELSIUS      | 2        | 0.72%   |
| Dell Vostro          | 2        | 0.72%   |
| Biostar G31-M7       | 2        | 0.72%   |
| ASUS STRIX           | 2        | 0.72%   |
| ASUS P8Z77-V         | 2        | 0.72%   |
| ASUS Maximus         | 2        | 0.72%   |
| ASUS K30AD           | 2        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 53       | 19.06%  |
| 2019 | 48       | 17.27%  |
| 2020 | 37       | 13.31%  |
| 2021 | 24       | 8.63%   |
| 2013 | 21       | 7.55%   |
| 2012 | 17       | 6.12%   |
| 2014 | 14       | 5.04%   |
| 2017 | 13       | 4.68%   |
| 2016 | 13       | 4.68%   |
| 2011 | 8        | 2.88%   |
| 2022 | 7        | 2.52%   |
| 2015 | 7        | 2.52%   |
| 2009 | 6        | 2.16%   |
| 2008 | 4        | 1.44%   |
| 2007 | 4        | 1.44%   |
| 2010 | 2        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 278      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 277      | 99.64%  |
| Enabled  | 1        | 0.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 278      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 109      | 38.79%  |
| 32.01-64.0  | 74       | 26.33%  |
| 8.01-16.0   | 41       | 14.59%  |
| 4.01-8.0    | 18       | 6.41%   |
| 24.01-32.0  | 14       | 4.98%   |
| 64.01-256.0 | 13       | 4.63%   |
| 3.01-4.0    | 11       | 3.91%   |
| 1.01-2.0    | 1        | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 82       | 27.15%  |
| 2.01-3.0   | 63       | 20.86%  |
| 1.01-2.0   | 61       | 20.2%   |
| 3.01-4.0   | 53       | 17.55%  |
| 8.01-16.0  | 33       | 10.93%  |
| 0.51-1.0   | 5        | 1.66%   |
| 16.01-24.0 | 3        | 0.99%   |
| 24.01-32.0 | 2        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 85       | 29.51%  |
| 3      | 63       | 21.88%  |
| 1      | 55       | 19.1%   |
| 4      | 48       | 16.67%  |
| 5      | 25       | 8.68%   |
| 6      | 5        | 1.74%   |
| 7      | 4        | 1.39%   |
| 9      | 1        | 0.35%   |
| 8      | 1        | 0.35%   |
| 0      | 1        | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 215      | 76.51%  |
| Yes       | 66       | 23.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 277      | 99.64%  |
| No        | 1        | 0.36%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 149      | 53.21%  |
| No        | 131      | 46.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 143      | 50.71%  |
| No        | 139      | 49.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 68       | 24.46%  |
| Germany             | 32       | 11.51%  |
| Italy               | 24       | 8.63%   |
| Canada              | 14       | 5.04%   |
| France              | 11       | 3.96%   |
| Poland              | 9        | 3.24%   |
| Netherlands         | 9        | 3.24%   |
| Belgium             | 9        | 3.24%   |
| UK                  | 7        | 2.52%   |
| Austria             | 7        | 2.52%   |
| Russia              | 6        | 2.16%   |
| Brazil              | 6        | 2.16%   |
| Sweden              | 5        | 1.8%    |
| Spain               | 5        | 1.8%    |
| India               | 5        | 1.8%    |
| Australia           | 5        | 1.8%    |
| Turkey              | 3        | 1.08%   |
| Switzerland         | 3        | 1.08%   |
| Slovenia            | 3        | 1.08%   |
| Mexico              | 3        | 1.08%   |
| Hungary             | 3        | 1.08%   |
| Finland             | 3        | 1.08%   |
| Denmark             | 3        | 1.08%   |
| Argentina           | 3        | 1.08%   |
| Romania             | 2        | 0.72%   |
| Portugal            | 2        | 0.72%   |
| Norway              | 2        | 0.72%   |
| Hong Kong           | 2        | 0.72%   |
| Czechia             | 2        | 0.72%   |
| Vietnam             | 1        | 0.36%   |
| Trinidad and Tobago | 1        | 0.36%   |
| Sri Lanka           | 1        | 0.36%   |
| South Korea         | 1        | 0.36%   |
| South Africa        | 1        | 0.36%   |
| Singapore           | 1        | 0.36%   |
| Serbia              | 1        | 0.36%   |
| Saudi Arabia        | 1        | 0.36%   |
| North Macedonia     | 1        | 0.36%   |
| Maldives            | 1        | 0.36%   |
| Malaysia            | 1        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 5        | 1.68%   |
| Leipzig           | 4        | 1.35%   |
| Warsaw            | 3        | 1.01%   |
| Turin             | 3        | 1.01%   |
| St Petersburg     | 3        | 1.01%   |
| Ottawa            | 3        | 1.01%   |
| Montreal          | 3        | 1.01%   |
| Houston           | 3        | 1.01%   |
| Amsterdam         | 3        | 1.01%   |
| Zurich            | 2        | 0.67%   |
| Wroclaw           | 2        | 0.67%   |
| Westminster       | 2        | 0.67%   |
| Tuen Mun          | 2        | 0.67%   |
| Toronto           | 2        | 0.67%   |
| Sydney            | 2        | 0.67%   |
| Snohomish         | 2        | 0.67%   |
| Schiedam          | 2        | 0.67%   |
| Renton            | 2        | 0.67%   |
| Porth             | 2        | 0.67%   |
| North Little Rock | 2        | 0.67%   |
| Milan             | 2        | 0.67%   |
| Madrid            | 2        | 0.67%   |
| Ljubljana         | 2        | 0.67%   |
| Koblach           | 2        | 0.67%   |
| Istanbul          | 2        | 0.67%   |
| Hamburg           | 2        | 0.67%   |
| Geesteren         | 2        | 0.67%   |
| Barbentane        | 2        | 0.67%   |
| Antwerp           | 2        | 0.67%   |
| Zuidlaren         | 1        | 0.34%   |
| Zapopan           | 1        | 0.34%   |
| Wimauma           | 1        | 0.34%   |
| Whiteville        | 1        | 0.34%   |
| Weybridge         | 1        | 0.34%   |
| Wevelgem          | 1        | 0.34%   |
| West Haddon       | 1        | 0.34%   |
| Waxahachie        | 1        | 0.34%   |
| Wasmes            | 1        | 0.34%   |
| Voluntari         | 1        | 0.34%   |
| Virar             | 1        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 115      | 197    | 18.52%  |
| WDC                         | 107      | 183    | 17.23%  |
| Seagate                     | 105      | 156    | 16.91%  |
| Kingston                    | 50       | 79     | 8.05%   |
| Crucial                     | 41       | 63     | 6.6%    |
| SanDisk                     | 28       | 36     | 4.51%   |
| Toshiba                     | 25       | 33     | 4.03%   |
| Hitachi                     | 13       | 14     | 2.09%   |
| Phison                      | 11       | 12     | 1.77%   |
| Intel                       | 9        | 15     | 1.45%   |
| Corsair                     | 7        | 7      | 1.13%   |
| Micron Technology           | 6        | 8      | 0.97%   |
| China                       | 6        | 6      | 0.97%   |
| A-DATA Technology           | 6        | 12     | 0.97%   |
| Unknown                     | 5        | 6      | 0.81%   |
| SPCC                        | 5        | 5      | 0.81%   |
| Phison Electronics          | 5        | 5      | 0.81%   |
| Intenso                     | 5        | 7      | 0.81%   |
| XPG                         | 4        | 4      | 0.64%   |
| PNY                         | 4        | 4      | 0.64%   |
| HGST                        | 4        | 4      | 0.64%   |
| Patriot                     | 3        | 4      | 0.48%   |
| OCZ                         | 3        | 3      | 0.48%   |
| Micron/Crucial Technology   | 3        | 7      | 0.48%   |
| Kingston Technology Company | 3        | 3      | 0.48%   |
| Gigabyte Technology         | 3        | 4      | 0.48%   |
| Transcend                   | 2        | 3      | 0.32%   |
| SK hynix                    | 2        | 2      | 0.32%   |
| Silicon Motion              | 2        | 2      | 0.32%   |
| SABRENT                     | 2        | 4      | 0.32%   |
| Plextor                     | 2        | 3      | 0.32%   |
| Lexar                       | 2        | 2      | 0.32%   |
| Leven                       | 2        | 3      | 0.32%   |
| JMicron Technology          | 2        | 2      | 0.32%   |
| ASMT                        | 2        | 4      | 0.32%   |
| USB3.1                      | 1        | 1      | 0.16%   |
| UMAX                        | 1        | 1      | 0.16%   |
| Timetec                     | 1        | 5      | 0.16%   |
| T-FORCE                     | 1        | 1      | 0.16%   |
| Realtek Semiconductor       | 1        | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                      | 22       | 2.94%   |
| Crucial CT500MX500SSD1 500GB                        | 13       | 1.74%   |
| Samsung SSD 860 EVO 1TB                             | 11       | 1.47%   |
| Kingston SA400S37120G 120GB SSD                     | 11       | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB                      | 10       | 1.34%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 9        | 1.2%    |
| Seagate ST4000DM004-2CV104 4TB                      | 9        | 1.2%    |
| Samsung SSD 860 EVO 500GB                           | 9        | 1.2%    |
| Samsung SSD 850 EVO 250GB                           | 9        | 1.2%    |
| Samsung SSD 850 EVO 500GB                           | 8        | 1.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 8        | 1.07%   |
| Kingston SA400S37240G 240GB SSD                     | 7        | 0.94%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 6        | 0.8%    |
| Seagate ST2000DM006-2DM164 2TB                      | 6        | 0.8%    |
| Samsung SSD 870 QVO 1TB                             | 6        | 0.8%    |
| Crucial CT240BX500SSD1 240GB                        | 6        | 0.8%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 5        | 0.67%   |
| Seagate Expansion Desk 5TB                          | 5        | 0.67%   |
| Samsung SSD 860 EVO 250GB                           | 5        | 0.67%   |
| Kingston SA400S37480G 480GB SSD                     | 5        | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                         | 5        | 0.67%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 4        | 0.53%   |
| Toshiba HDWD110 1TB                                 | 4        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                      | 4        | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB                      | 4        | 0.53%   |
| Samsung SSD 980 500GB                               | 4        | 0.53%   |
| Samsung SSD 970 EVO Plus 500GB                      | 4        | 0.53%   |
| Samsung SSD 970 EVO 500GB                           | 4        | 0.53%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 4        | 0.53%   |
| Samsung NVMe SSD Drive 1TB                          | 4        | 0.53%   |
| Kingston NVMe SSD Drive 1TB                         | 4        | 0.53%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 3        | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 3        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 3        | 0.4%    |
| WDC WDS100T3X0C-00SJG0 1TB                          | 3        | 0.4%    |
| WDC WDS100T2B0C-00PXH0 1TB                          | 3        | 0.4%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 3        | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB                            | 3        | 0.4%    |
| WDC WD20EARS-42S0XB0 2TB                            | 3        | 0.4%    |
| WDC WD10EZEX-22MFCA0 1TB                            | 3        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 104      | 155    | 42.11%  |
| WDC                 | 82       | 127    | 33.2%   |
| Toshiba             | 20       | 24     | 8.1%    |
| Hitachi             | 13       | 14     | 5.26%   |
| Samsung Electronics | 9        | 19     | 3.64%   |
| HGST                | 4        | 4      | 1.62%   |
| Unknown             | 3        | 3      | 1.21%   |
| SABRENT             | 2        | 4      | 0.81%   |
| JMicron Technology  | 2        | 2      | 0.81%   |
| ASMT                | 2        | 4      | 0.81%   |
| PI-041              | 1        | 1      | 0.4%    |
| Maxtor              | 1        | 1      | 0.4%    |
| Maxone              | 1        | 1      | 0.4%    |
| HPE                 | 1        | 1      | 0.4%    |
| ASMedia             | 1        | 1      | 0.4%    |
| Unknown             | 1        | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 78       | 113    | 30.23%  |
| Kingston            | 38       | 61     | 14.73%  |
| Crucial             | 37       | 51     | 14.34%  |
| WDC                 | 25       | 32     | 9.69%   |
| SanDisk             | 16       | 21     | 6.2%    |
| China               | 6        | 6      | 2.33%   |
| Micron Technology   | 5        | 7      | 1.94%   |
| Intenso             | 5        | 7      | 1.94%   |
| Intel               | 5        | 8      | 1.94%   |
| Toshiba             | 4        | 6      | 1.55%   |
| SPCC                | 3        | 3      | 1.16%   |
| PNY                 | 3        | 3      | 1.16%   |
| Patriot             | 3        | 4      | 1.16%   |
| OCZ                 | 3        | 3      | 1.16%   |
| Corsair             | 3        | 3      | 1.16%   |
| Phison              | 2        | 2      | 0.78%   |
| Leven               | 2        | 3      | 0.78%   |
| Gigabyte Technology | 2        | 2      | 0.78%   |
| A-DATA Technology   | 2        | 2      | 0.78%   |
| UMAX                | 1        | 1      | 0.39%   |
| Transcend           | 1        | 1      | 0.39%   |
| Timetec             | 1        | 5      | 0.39%   |
| Plextor             | 1        | 2      | 0.39%   |
| Pioneer             | 1        | 3      | 0.39%   |
| NGFF                | 1        | 1      | 0.39%   |
| Mushkin             | 1        | 1      | 0.39%   |
| LITEONIT            | 1        | 1      | 0.39%   |
| Lexar               | 1        | 1      | 0.39%   |
| LDLC                | 1        | 1      | 0.39%   |
| Kingmax             | 1        | 2      | 0.39%   |
| Imation             | 1        | 1      | 0.39%   |
| Hewlett-Packard     | 1        | 1      | 0.39%   |
| GOODRAM             | 1        | 1      | 0.39%   |
| Emtec               | 1        | 1      | 0.39%   |
| Drevo               | 1        | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 188      | 361    | 37.01%  |
| HDD     | 186      | 362    | 36.61%  |
| NVMe    | 130      | 208    | 25.59%  |
| Unknown | 4        | 5      | 0.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 247      | 686    | 60.54%  |
| NVMe | 130      | 207    | 31.86%  |
| SAS  | 31       | 43     | 7.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 173      | 352    | 39.77%  |
| 0.51-1.0   | 132      | 192    | 30.34%  |
| 1.01-2.0   | 69       | 100    | 15.86%  |
| 3.01-4.0   | 23       | 36     | 5.29%   |
| 2.01-3.0   | 19       | 22     | 4.37%   |
| 4.01-10.0  | 17       | 19     | 3.91%   |
| 10.01-20.0 | 2        | 2      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 64       | 22.22%  |
| More than 3000 | 54       | 18.75%  |
| 501-1000       | 41       | 14.24%  |
| 101-250        | 35       | 12.15%  |
| 2001-3000      | 33       | 11.46%  |
| 251-500        | 30       | 10.42%  |
| Unknown        | 16       | 5.56%   |
| 1-20           | 6        | 2.08%   |
| 51-100         | 6        | 2.08%   |
| 21-50          | 3        | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 47       | 15.36%  |
| 501-1000       | 47       | 15.36%  |
| 1-20           | 44       | 14.38%  |
| 101-250        | 37       | 12.09%  |
| 251-500        | 34       | 11.11%  |
| 51-100         | 28       | 9.15%   |
| 21-50          | 26       | 8.5%    |
| More than 3000 | 16       | 5.23%   |
| Unknown        | 16       | 5.23%   |
| 2001-3000      | 11       | 3.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Desktops | Drives | Percent |
|-----------------------------------------------------------------|----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB                                        | 2        | 2      | 4.88%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 2        | 4      | 4.88%   |
| XPG GAMMIX S11 480GB                                            | 1        | 1      | 2.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1        | 1      | 2.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                                | 1        | 1      | 2.44%   |
| WDC WD5000AZRX-00A8LB0 500GB                                    | 1        | 1      | 2.44%   |
| WDC WD5000AVDS-63U7B1 500GB                                     | 1        | 1      | 2.44%   |
| WDC WD40EFRX-68WT0N0 4TB                                        | 1        | 2      | 2.44%   |
| WDC WD2003FZEX-00Z4SA0 2TB                                      | 1        | 1      | 2.44%   |
| WDC WD2002FYPS-01U1B0 2TB                                       | 1        | 1      | 2.44%   |
| WDC WD10EACS-00D6B1 1TB                                         | 1        | 1      | 2.44%   |
| WDC WD Blue SA510 2.5 1TB SSD                                   | 1        | 1      | 2.44%   |
| Toshiba DT01ACA100 1TB                                          | 1        | 1      | 2.44%   |
| Seagate ST9320325AS 320GB                                       | 1        | 4      | 2.44%   |
| Seagate ST6000VX0023-2EF110 6TB                                 | 1        | 1      | 2.44%   |
| Seagate ST4000DM004-2CV104 4TB                                  | 1        | 1      | 2.44%   |
| Seagate ST3320620AS 320GB                                       | 1        | 1      | 2.44%   |
| Seagate ST2000DX002-2DV164 2TB                                  | 1        | 1      | 2.44%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 1        | 1      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 1        | 2      | 2.44%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 1        | 1      | 2.44%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 1        | 2      | 2.44%   |
| Samsung Electronics SSD 960 EVO 500GB                           | 1        | 1      | 2.44%   |
| Samsung Electronics SSD 840 Series 120GB                        | 1        | 1      | 2.44%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 1        | 1      | 2.44%   |
| Samsung Electronics HD103SI 1TB                                 | 1        | 1      | 2.44%   |
| Patriot Burst 480GB SSD                                         | 1        | 1      | 2.44%   |
| OCZ VERTEX3 240GB SSD                                           | 1        | 1      | 2.44%   |
| Kingston SV300S37A120G 120GB SSD                                | 1        | 1      | 2.44%   |
| Hitachi HTS547575A9E384 752GB                                   | 1        | 1      | 2.44%   |
| Hitachi HTS545050A7E380 500GB                                   | 1        | 1      | 2.44%   |
| Hitachi HDT725025VLA380 250GB                                   | 1        | 1      | 2.44%   |
| HGST HTS545050A7E680 500GB                                      | 1        | 1      | 2.44%   |
| Drevo X1 SSD 240GB                                              | 1        | 1      | 2.44%   |
| Crucial CT500MX500SSD1 500GB                                    | 1        | 6      | 2.44%   |
| Crucial CT256MX100SSD1 256GB                                    | 1        | 1      | 2.44%   |
| Crucial CT1050MX300SSD1 1050GB                                  | 1        | 1      | 2.44%   |
| Corsair Force LS SSD 120GB                                      | 1        | 1      | 2.44%   |
| ASMT ASM1156-PM 3TB                                             | 1        | 2      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 12     | 25.64%  |
| Seagate             | 10       | 18     | 25.64%  |
| Samsung Electronics | 4        | 4      | 10.26%  |
| Hitachi             | 3        | 3      | 7.69%   |
| Crucial             | 3        | 8      | 7.69%   |
| XPG                 | 1        | 1      | 2.56%   |
| Toshiba             | 1        | 1      | 2.56%   |
| Patriot             | 1        | 1      | 2.56%   |
| OCZ                 | 1        | 1      | 2.56%   |
| Kingston            | 1        | 1      | 2.56%   |
| HGST                | 1        | 1      | 2.56%   |
| Drevo               | 1        | 1      | 2.56%   |
| Corsair             | 1        | 1      | 2.56%   |
| ASMT                | 1        | 2      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 18     | 40%     |
| WDC                 | 8        | 9      | 32%     |
| Hitachi             | 3        | 3      | 12%     |
| Toshiba             | 1        | 1      | 4%      |
| Samsung Electronics | 1        | 1      | 4%      |
| HGST                | 1        | 1      | 4%      |
| ASMT                | 1        | 2      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 35     | 65.79%  |
| SSD  | 10       | 17     | 26.32%  |
| NVMe | 3        | 3      | 7.89%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB   | 1        | 1      | 50%     |
| Samsung Electronics HD252HJ 250GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 191      | 570    | 57.53%  |
| Detected | 103      | 309    | 31.02%  |
| Malfunc  | 36       | 55     | 10.84%  |
| Failed   | 2        | 2      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 144      | 30.7%   |
| AMD                            | 129      | 27.51%  |
| Samsung Electronics            | 51       | 10.87%  |
| SanDisk                        | 30       | 6.4%    |
| ASMedia Technology             | 28       | 5.97%   |
| Phison Electronics             | 21       | 4.48%   |
| Kingston Technology Company    | 16       | 3.41%   |
| Micron/Crucial Technology      | 7        | 1.49%   |
| Marvell Technology Group       | 6        | 1.28%   |
| Silicon Motion                 | 5        | 1.07%   |
| Realtek Semiconductor          | 5        | 1.07%   |
| JMicron Technology             | 5        | 1.07%   |
| ADATA Technology               | 5        | 1.07%   |
| Toshiba America Info Systems   | 3        | 0.64%   |
| Nvidia                         | 3        | 0.64%   |
| Transcend                      | 2        | 0.43%   |
| SK hynix                       | 2        | 0.43%   |
| Micron Technology              | 2        | 0.43%   |
| Solid State Storage Technology | 1        | 0.21%   |
| Seagate Technology             | 1        | 0.21%   |
| LSI Logic / Symbios Logic      | 1        | 0.21%   |
| KIOXIA                         | 1        | 0.21%   |
| Broadcom / LSI                 | 1        | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 78       | 14.42%  |
| AMD 400 Series Chipset SATA Controller                                         | 45       | 8.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29       | 5.36%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 27       | 4.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 25       | 4.62%   |
| AMD 500 Series Chipset SATA Controller                                         | 22       | 4.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 14       | 2.59%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 14       | 2.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 12       | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 12       | 2.22%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 11       | 2.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9        | 1.66%   |
| Phison E16 PCIe4 NVMe Controller                                               | 9        | 1.66%   |
| Samsung NVMe SSD Controller 980                                                | 8        | 1.48%   |
| Phison E12 NVMe Controller                                                     | 8        | 1.48%   |
| Kingston Company A2000 NVMe SSD                                                | 8        | 1.48%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 8        | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7        | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7        | 1.29%   |
| Intel SATA Controller [RAID mode]                                              | 7        | 1.29%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 6        | 1.11%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 6        | 1.11%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5        | 0.92%   |
| Kingston Company Company Non-Volatile memory controller                        | 5        | 0.92%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5        | 0.92%   |
| AMD FCH SATA Controller D                                                      | 5        | 0.92%   |
| Realtek Realtek Non-Volatile memory controller                                 | 4        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 0.74%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4        | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3        | 0.55%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 3        | 0.55%   |
| Kingston Company KC2000 NVMe SSD                                               | 3        | 0.55%   |
| JMicron JMB363 SATA/IDE Controller                                             | 3        | 0.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3        | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 0.55%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3        | 0.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 253      | 60.1%   |
| NVMe | 130      | 30.88%  |
| IDE  | 23       | 5.46%   |
| RAID | 13       | 3.09%   |
| SAS  | 2        | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 146      | 52.52%  |
| AMD    | 132      | 47.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 15       | 5.4%    |
| AMD Ryzen 5 3600 6-Core Processor           | 14       | 5.04%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 13       | 4.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 3.24%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 2.88%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 6        | 2.16%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 5        | 1.8%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 1.8%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.8%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 1.44%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 1.44%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 4        | 1.44%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 1.44%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 1.44%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 1.44%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 1.44%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.08%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.08%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 1.08%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.08%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 1.08%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 0.72%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.72%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.72%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.72%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.72%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.72%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 2        | 0.72%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.72%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.72%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.72%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 2        | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.72%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2        | 0.72%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 0.72%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.72%   |
| Intel 12th Gen Core i5-12600K               | 2        | 0.72%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 2        | 0.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 55       | 19.78%  |
| Intel Core i5           | 51       | 18.35%  |
| Intel Core i7           | 43       | 15.47%  |
| AMD Ryzen 7             | 40       | 14.39%  |
| AMD Ryzen 9             | 19       | 6.83%   |
| Intel Xeon              | 11       | 3.96%   |
| Other                   | 10       | 3.6%    |
| Intel Core i3           | 10       | 3.6%    |
| AMD FX                  | 6        | 2.16%   |
| AMD Ryzen 3             | 5        | 1.8%    |
| Intel Core 2 Duo        | 4        | 1.44%   |
| Intel Celeron           | 4        | 1.44%   |
| Intel Core i9           | 3        | 1.08%   |
| Intel Core 2 Quad       | 3        | 1.08%   |
| AMD Ryzen Threadripper  | 3        | 1.08%   |
| Intel Pentium           | 2        | 0.72%   |
| Intel Pentium Gold      | 1        | 0.36%   |
| Intel Pentium Dual-Core | 1        | 0.36%   |
| Intel Pentium Dual      | 1        | 0.36%   |
| Intel Core m3           | 1        | 0.36%   |
| Intel Core 2            | 1        | 0.36%   |
| AMD Phenom II X4        | 1        | 0.36%   |
| AMD Athlon X4           | 1        | 0.36%   |
| AMD Athlon II X4        | 1        | 0.36%   |
| AMD A8                  | 1        | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 96       | 34.41%  |
| 6      | 74       | 26.52%  |
| 8      | 53       | 19%     |
| 2      | 23       | 8.24%   |
| 12     | 19       | 6.81%   |
| 16     | 6        | 2.15%   |
| 10     | 4        | 1.43%   |
| 3      | 3        | 1.08%   |
| 32     | 1        | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 275      | 98.57%  |
| 2      | 4        | 1.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 202      | 72.66%  |
| 1      | 76       | 27.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 278      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 108      | 38.03%  |
| 0x08701021 | 27       | 9.51%   |
| 0x306c3    | 19       | 6.69%   |
| 0x0a201009 | 11       | 3.87%   |
| 0x08701013 | 10       | 3.52%   |
| 0x506e3    | 8        | 2.82%   |
| 0x306a9    | 8        | 2.82%   |
| 0x906ea    | 7        | 2.46%   |
| 0x0a50000c | 7        | 2.46%   |
| 0x906e9    | 6        | 2.11%   |
| 0x0a201016 | 6        | 2.11%   |
| 0xa0655    | 5        | 1.76%   |
| 0x0a20120a | 5        | 1.76%   |
| 0x0800820d | 5        | 1.76%   |
| 0x08001138 | 4        | 1.41%   |
| 0xa0653    | 3        | 1.06%   |
| 0x106a5    | 3        | 1.06%   |
| 0x08108109 | 3        | 1.06%   |
| 0x08001137 | 3        | 1.06%   |
| 0xa0671    | 2        | 0.7%    |
| 0x906ec    | 2        | 0.7%    |
| 0x906eb    | 2        | 0.7%    |
| 0x90672    | 2        | 0.7%    |
| 0x6fd      | 2        | 0.7%    |
| 0x306f2    | 2        | 0.7%    |
| 0x106e5    | 2        | 0.7%    |
| 0x08101016 | 2        | 0.7%    |
| 0x06000852 | 2        | 0.7%    |
| 0x906ed    | 1        | 0.35%   |
| 0x706a8    | 1        | 0.35%   |
| 0x6fb      | 1        | 0.35%   |
| 0x6f6      | 1        | 0.35%   |
| 0x6f2      | 1        | 0.35%   |
| 0x406c4    | 1        | 0.35%   |
| 0x206c2    | 1        | 0.35%   |
| 0x206a7    | 1        | 0.35%   |
| 0x20652    | 1        | 0.35%   |
| 0x1067a    | 1        | 0.35%   |
| 0x10676    | 1        | 0.35%   |
| 0x0a601201 | 1        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 52       | 18.64%  |
| Zen 3            | 41       | 14.7%   |
| Haswell          | 35       | 12.54%  |
| KabyLake         | 32       | 11.47%  |
| Skylake          | 15       | 5.38%   |
| Zen+             | 14       | 5.02%   |
| CometLake        | 14       | 5.02%   |
| Zen              | 13       | 4.66%   |
| IvyBridge        | 13       | 4.66%   |
| Unknown          | 9        | 3.23%   |
| Core             | 7        | 2.51%   |
| SandyBridge      | 6        | 2.15%   |
| Nehalem          | 5        | 1.79%   |
| Piledriver       | 4        | 1.43%   |
| Penryn           | 4        | 1.43%   |
| Alderlake Hybrid | 3        | 1.08%   |
| Westmere         | 2        | 0.72%   |
| Icelake          | 2        | 0.72%   |
| Bulldozer        | 2        | 0.72%   |
| Steamroller      | 1        | 0.36%   |
| Silvermont       | 1        | 0.36%   |
| K10 Llano        | 1        | 0.36%   |
| K10              | 1        | 0.36%   |
| Goldmont plus    | 1        | 0.36%   |
| Excavator        | 1        | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 149      | 48.69%  |
| AMD    | 105      | 34.31%  |
| Intel  | 52       | 16.99%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 27       | 8.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 17       | 5.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 15       | 4.78%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 11       | 3.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 2.87%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 9        | 2.87%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 2.87%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 9        | 2.87%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9        | 2.87%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 7        | 2.23%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 7        | 2.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7        | 2.23%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 5        | 1.59%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 5        | 1.59%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 5        | 1.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 1.59%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.59%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 1.27%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 1.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 1.27%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.96%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 3        | 0.96%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.96%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 0.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.96%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 0.96%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 3        | 0.96%   |
| Intel HD Graphics 630                                                       | 3        | 0.96%   |
| Intel HD Graphics 530                                                       | 3        | 0.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 0.96%   |
| Intel AlderLake-S GT1                                                       | 3        | 0.96%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 0.96%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.64%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.64%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.64%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 132      | 46.64%  |
| 1 x AMD        | 91       | 32.16%  |
| 1 x Intel      | 33       | 11.66%  |
| Intel + Nvidia | 8        | 2.83%   |
| AMD + Nvidia   | 6        | 2.12%   |
| 2 x AMD        | 5        | 1.77%   |
| Intel + AMD    | 5        | 1.77%   |
| 2 x Nvidia     | 3        | 1.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 157      | 56.27%  |
| Proprietary | 122      | 43.73%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 87       | 30.53%  |
| 7.01-8.0   | 57       | 20%     |
| 3.01-4.0   | 37       | 12.98%  |
| 1.01-2.0   | 31       | 10.88%  |
| 8.01-16.0  | 26       | 9.12%   |
| 5.01-6.0   | 23       | 8.07%   |
| 0.01-0.5   | 11       | 3.86%   |
| 0.51-1.0   | 10       | 3.51%   |
| 16.01-24.0 | 2        | 0.7%    |
| 2.01-3.0   | 1        | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 61       | 16.9%   |
| Dell                 | 34       | 9.42%   |
| Goldstar             | 33       | 9.14%   |
| Acer                 | 30       | 8.31%   |
| AOC                  | 26       | 7.2%    |
| Ancor Communications | 26       | 7.2%    |
| BenQ                 | 21       | 5.82%   |
| Hewlett-Packard      | 15       | 4.16%   |
| ASUSTek Computer     | 15       | 4.16%   |
| ViewSonic            | 8        | 2.22%   |
| Lenovo               | 8        | 2.22%   |
| Iiyama               | 7        | 1.94%   |
| Vizio                | 6        | 1.66%   |
| Philips              | 6        | 1.66%   |
| LG Electronics       | 6        | 1.66%   |
| Gigabyte Technology  | 6        | 1.66%   |
| Fujitsu Siemens      | 3        | 0.83%   |
| Eizo                 | 3        | 0.83%   |
| Valve                | 2        | 0.55%   |
| Sony                 | 2        | 0.55%   |
| Sceptre Tech         | 2        | 0.55%   |
| MSI                  | 2        | 0.55%   |
| Lenovo Group Limited | 2        | 0.55%   |
| AOpen                | 2        | 0.55%   |
| Xiaomi               | 1        | 0.28%   |
| VOXICON              | 1        | 0.28%   |
| Unknown (XXX)        | 1        | 0.28%   |
| Unknown              | 1        | 0.28%   |
| UGD                  | 1        | 0.28%   |
| Toshiba              | 1        | 0.28%   |
| SAC                  | 1        | 0.28%   |
| RTK                  | 1        | 0.28%   |
| RS                   | 1        | 0.28%   |
| Planar               | 1        | 0.28%   |
| Pixio                | 1        | 0.28%   |
| Panasonic            | 1        | 0.28%   |
| Orion                | 1        | 0.28%   |
| OLT                  | 1        | 0.28%   |
| NEC Computers        | 1        | 0.28%   |
| Microstep            | 1        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 5        | 1.3%    |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5        | 1.3%    |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 4        | 1.04%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3        | 0.78%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.78%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.78%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch        | 3        | 0.78%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                     | 3        | 0.78%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 3        | 0.78%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 2        | 0.52%   |
| ViewSonic VX2758-Series VSCA738 2560x1440 598x336mm 27.0-inch         | 2        | 0.52%   |
| Valve LCD Monitor VLV91A8                                             | 2        | 0.52%   |
| Sceptre Tech Sceptre M24 SPT098C 1920x1080 544x303mm 24.5-inch        | 2        | 0.52%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 2        | 0.52%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch     | 2        | 0.52%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 2        | 0.52%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.52%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2        | 0.52%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                  | 2        | 0.52%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.52%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 2        | 0.52%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 2        | 0.52%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 2        | 0.52%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 2        | 0.52%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 2        | 0.52%   |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                     | 2        | 0.52%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 2        | 0.52%   |
| BenQ G2450H BNQ78AB 1920x1080 531x298mm 24.0-inch                     | 2        | 0.52%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 2        | 0.52%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2        | 0.52%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch          | 2        | 0.52%   |
| ASUSTek Computer VG248 AUS24AC 1920x1080 531x299mm 24.0-inch          | 2        | 0.52%   |
| AOpen 24CH2Y AOP077C 1920x1080 527x296mm 23.8-inch                    | 2        | 0.52%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 2        | 0.52%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                     | 2        | 0.52%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch      | 2        | 0.52%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 2        | 0.52%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 2        | 0.52%   |
| Acer XB270HU ACR0408 2560x1440 598x336mm 27.0-inch                    | 2        | 0.52%   |
| Acer VG240Y ACR0673 1920x1080 527x296mm 23.8-inch                     | 2        | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 158      | 46.06%  |
| 2560x1440 (QHD)    | 49       | 14.29%  |
| 3840x2160 (4K)     | 43       | 12.54%  |
| 1280x1024 (SXGA)   | 13       | 3.79%   |
| 1920x1200 (WUXGA)  | 10       | 2.92%   |
| 1680x1050 (WSXGA+) | 10       | 2.92%   |
| Unknown            | 9        | 2.62%   |
| 1600x900 (HD+)     | 8        | 2.33%   |
| 1440x900 (WXGA+)   | 6        | 1.75%   |
| 1366x768 (WXGA)    | 6        | 1.75%   |
| 3440x1440          | 5        | 1.46%   |
| 2560x1080          | 5        | 1.46%   |
| 3840x1080          | 4        | 1.17%   |
| 1360x768           | 3        | 0.87%   |
| 3840x1600          | 2        | 0.58%   |
| 1920x540           | 2        | 0.58%   |
| 9840x3840          | 1        | 0.29%   |
| 5760x1080          | 1        | 0.29%   |
| 4480x1440          | 1        | 0.29%   |
| 3840x1200          | 1        | 0.29%   |
| 3520x1080          | 1        | 0.29%   |
| 3200x1080          | 1        | 0.29%   |
| 2880x1700          | 1        | 0.29%   |
| 2560x1600          | 1        | 0.29%   |
| 1600x1200          | 1        | 0.29%   |
| 1024x768 (XGA)     | 1        | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 81       | 22.75%  |
| 27      | 69       | 19.38%  |
| 23      | 36       | 10.11%  |
| 21      | 30       | 8.43%   |
| Unknown | 27       | 7.58%   |
| 31      | 17       | 4.78%   |
| 34      | 14       | 3.93%   |
| 19      | 13       | 3.65%   |
| 22      | 11       | 3.09%   |
| 18      | 7        | 1.97%   |
| 20      | 6        | 1.69%   |
| 17      | 6        | 1.69%   |
| 54      | 5        | 1.4%    |
| 84      | 4        | 1.12%   |
| 32      | 4        | 1.12%   |
| 49      | 3        | 0.84%   |
| 40      | 3        | 0.84%   |
| 72      | 2        | 0.56%   |
| 42      | 2        | 0.56%   |
| 37      | 2        | 0.56%   |
| 74      | 1        | 0.28%   |
| 69      | 1        | 0.28%   |
| 65      | 1        | 0.28%   |
| 60      | 1        | 0.28%   |
| 52      | 1        | 0.28%   |
| 50      | 1        | 0.28%   |
| 48      | 1        | 0.28%   |
| 46      | 1        | 0.28%   |
| 33      | 1        | 0.28%   |
| 28      | 1        | 0.28%   |
| 16      | 1        | 0.28%   |
| 15      | 1        | 0.28%   |
| 13      | 1        | 0.28%   |
| 10      | 1        | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 158      | 47.73%  |
| 401-500     | 58       | 17.52%  |
| Unknown     | 27       | 8.16%   |
| 601-700     | 25       | 7.55%   |
| 701-800     | 19       | 5.74%   |
| 1001-1500   | 14       | 4.23%   |
| 301-350     | 8        | 2.42%   |
| 1501-2000   | 8        | 2.42%   |
| 801-900     | 5        | 1.51%   |
| 351-400     | 5        | 1.51%   |
| 201-300     | 2        | 0.6%    |
| 901-1000    | 2        | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 216      | 71.05%  |
| 16/10   | 33       | 10.86%  |
| Unknown | 24       | 7.89%   |
| 21/9    | 13       | 4.28%   |
| 5/4     | 10       | 3.29%   |
| 32/9    | 4        | 1.32%   |
| 6/5     | 2        | 0.66%   |
| 4/3     | 2        | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 118      | 34.6%   |
| 301-350        | 69       | 20.23%  |
| 351-500        | 33       | 9.68%   |
| Unknown        | 27       | 7.92%   |
| 251-300        | 26       | 7.62%   |
| 151-200        | 21       | 6.16%   |
| More than 1000 | 18       | 5.28%   |
| 501-1000       | 13       | 3.81%   |
| 141-150        | 12       | 3.52%   |
| 71-80          | 1        | 0.29%   |
| 41-50          | 1        | 0.29%   |
| 131-140        | 1        | 0.29%   |
| 111-120        | 1        | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 186      | 59.62%  |
| 101-120       | 65       | 20.83%  |
| Unknown       | 27       | 8.65%   |
| 1-50          | 15       | 4.81%   |
| 121-160       | 10       | 3.21%   |
| 161-240       | 8        | 2.56%   |
| More than 240 | 1        | 0.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 193      | 68.2%   |
| 2     | 72       | 25.44%  |
| 3     | 15       | 5.3%    |
| 4     | 2        | 0.71%   |
| 0     | 1        | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 190      | 46%     |
| Intel                                 | 136      | 32.93%  |
| Qualcomm Atheros                      | 17       | 4.12%   |
| Broadcom                              | 11       | 2.66%   |
| Microsoft                             | 9        | 2.18%   |
| TP-Link                               | 7        | 1.69%   |
| Ralink Technology                     | 5        | 1.21%   |
| ASIX Electronics                      | 5        | 1.21%   |
| MediaTek                              | 4        | 0.97%   |
| Ralink                                | 3        | 0.73%   |
| Aquantia                              | 3        | 0.73%   |
| Xiaomi                                | 2        | 0.48%   |
| Nvidia                                | 2        | 0.48%   |
| Microchip Technology                  | 2        | 0.48%   |
| Google                                | 2        | 0.48%   |
| Wilocity                              | 1        | 0.24%   |
| Samsung Electronics                   | 1        | 0.24%   |
| Qualcomm Atheros Communications       | 1        | 0.24%   |
| OPPO                                  | 1        | 0.24%   |
| NetGear                               | 1        | 0.24%   |
| Motorola PCS                          | 1        | 0.24%   |
| InterBiometrics                       | 1        | 0.24%   |
| Huawei Technologies                   | 1        | 0.24%   |
| Exar                                  | 1        | 0.24%   |
| Edimax Technology                     | 1        | 0.24%   |
| DisplayLink                           | 1        | 0.24%   |
| D-Link                                | 1        | 0.24%   |
| Broadcom Limited                      | 1        | 0.24%   |
| AVM                                   | 1        | 0.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 139      | 28.48%  |
| Realtek RTL8125 2.5GbE Controller                                                             | 36       | 7.38%   |
| Intel Wi-Fi 6 AX200                                                                           | 32       | 6.56%   |
| Intel I211 Gigabit Network Connection                                                         | 30       | 6.15%   |
| Intel Ethernet Connection (2) I219-V                                                          | 12       | 2.46%   |
| Intel Ethernet Controller I225-V                                                              | 10       | 2.05%   |
| Intel Ethernet Connection (7) I219-V                                                          | 10       | 2.05%   |
| Intel Wireless-AC 9260                                                                        | 9        | 1.84%   |
| Intel Ethernet Connection I217-LM                                                             | 9        | 1.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 8        | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 6        | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 5        | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 4        | 0.82%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 4        | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 4        | 0.82%   |
| Realtek 802.11ac NIC                                                                          | 4        | 0.82%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 4        | 0.82%   |
| Intel Ethernet Connection I217-V                                                              | 4        | 0.82%   |
| Intel Ethernet Connection (2) I218-V                                                          | 4        | 0.82%   |
| Intel 82579V Gigabit Network Connection                                                       | 4        | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                                                 | 4        | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 0.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 3        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 3        | 0.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3        | 0.61%   |
| Microsoft XBOX ACC                                                                            | 3        | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 3        | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 3        | 0.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 3        | 0.61%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 3        | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2        | 0.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2        | 0.41%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.41%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 2        | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 2        | 0.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 75       | 46.88%  |
| Realtek Semiconductor                 | 32       | 20%     |
| Qualcomm Atheros                      | 10       | 6.25%   |
| Microsoft                             | 9        | 5.63%   |
| Broadcom                              | 9        | 5.63%   |
| TP-Link                               | 6        | 3.75%   |
| Ralink Technology                     | 5        | 3.13%   |
| MediaTek                              | 4        | 2.5%    |
| Ralink                                | 3        | 1.88%   |
| Wilocity                              | 1        | 0.63%   |
| Qualcomm Atheros Communications       | 1        | 0.63%   |
| NetGear                               | 1        | 0.63%   |
| Edimax Technology                     | 1        | 0.63%   |
| D-Link                                | 1        | 0.63%   |
| AVM                                   | 1        | 0.63%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 32       | 19.51%  |
| Intel Wireless-AC 9260                                                                        | 9        | 5.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 8        | 4.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 6        | 3.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 3.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 3.05%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 4        | 2.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 4        | 2.44%   |
| Realtek 802.11ac NIC                                                                          | 4        | 2.44%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 4        | 2.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3        | 1.83%   |
| Microsoft XBOX ACC                                                                            | 3        | 1.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 3        | 1.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 3        | 1.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 3        | 1.83%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 3        | 1.83%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 1.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2        | 1.22%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 1.22%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 2        | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 1.22%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 1.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 2        | 1.22%   |
| Intel Wireless 8260                                                                           | 2        | 1.22%   |
| Intel Wireless 7265                                                                           | 2        | 1.22%   |
| Intel Wireless 3165                                                                           | 2        | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 2        | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2        | 1.22%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                            | 1        | 0.61%   |
| TP-Link Archer T4UH v2 [Realtek RTL8812AU]                                                    | 1        | 0.61%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.61%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 0.61%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                                     | 1        | 0.61%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                      | 1        | 0.61%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 180      | 57.69%  |
| Intel                 | 101      | 32.37%  |
| Qualcomm Atheros      | 9        | 2.88%   |
| ASIX Electronics      | 5        | 1.6%    |
| Aquantia              | 3        | 0.96%   |
| Xiaomi                | 2        | 0.64%   |
| Nvidia                | 2        | 0.64%   |
| Google                | 2        | 0.64%   |
| Broadcom              | 2        | 0.64%   |
| TP-Link               | 1        | 0.32%   |
| Samsung Electronics   | 1        | 0.32%   |
| OPPO                  | 1        | 0.32%   |
| Motorola PCS          | 1        | 0.32%   |
| DisplayLink           | 1        | 0.32%   |
| Broadcom Limited      | 1        | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 139      | 43.57%  |
| Realtek RTL8125 2.5GbE Controller                                 | 36       | 11.29%  |
| Intel I211 Gigabit Network Connection                             | 30       | 9.4%    |
| Intel Ethernet Connection (2) I219-V                              | 12       | 3.76%   |
| Intel Ethernet Controller I225-V                                  | 10       | 3.13%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 3.13%   |
| Intel Ethernet Connection I217-LM                                 | 9        | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 1.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.25%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4        | 1.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 0.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.63%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.63%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.63%   |
| Google Pixel 6a                                                   | 2        | 0.63%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.31%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.31%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.31%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.31%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.31%   |
| OPPO CPH1923                                                      | 1        | 0.31%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.31%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.31%   |
| Motorola PCS moto g(8) plus                                       | 1        | 0.31%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.31%   |
| Intel Ethernet Controller I226-V                                  | 1        | 0.31%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.31%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.31%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 277      | 64.57%  |
| WiFi     | 147      | 34.27%  |
| Modem    | 5        | 1.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 225      | 76.27%  |
| WiFi     | 70       | 23.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 158      | 56.23%  |
| 2     | 100      | 35.59%  |
| 3     | 18       | 6.41%   |
| 4     | 4        | 1.42%   |
| 0     | 1        | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 215      | 75.7%   |
| Yes  | 69       | 24.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 69       | 46%     |
| Cambridge Silicon Radio         | 26       | 17.33%  |
| Realtek Semiconductor           | 18       | 12%     |
| ASUSTek Computer                | 12       | 8%      |
| Broadcom                        | 10       | 6.67%   |
| TP-Link                         | 3        | 2%      |
| MediaTek                        | 3        | 2%      |
| Qualcomm Atheros Communications | 2        | 1.33%   |
| IMC Networks                    | 2        | 1.33%   |
| HTC (High Tech Computer)        | 2        | 1.33%   |
| Toshiba                         | 1        | 0.67%   |
| Realtek                         | 1        | 0.67%   |
| Dynex                           | 1        | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 29       | 19.21%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 26       | 17.22%  |
| Realtek Bluetooth Radio                                              | 17       | 11.26%  |
| Intel Bluetooth wireless interface                                   | 10       | 6.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 8        | 5.3%    |
| Intel AX210 Bluetooth                                                | 8        | 5.3%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 7        | 4.64%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 6        | 3.97%   |
| Intel AX201 Bluetooth                                                | 6        | 3.97%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 6        | 3.97%   |
| TP-Link TPuLink UB500 Adapter                                        | 3        | 1.99%   |
| MediaTek Wireless_Device                                             | 3        | 1.99%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 1.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 1.32%   |
| IMC Networks Bluetooth Radio                                         | 2        | 1.32%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 1.32%   |
| ASUS Bluetooth Device                                                | 2        | 1.32%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 1        | 0.66%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.66%   |
| Realtek Bluetooth Radio                                              | 1        | 0.66%   |
| Intel Bluetooth Device                                               | 1        | 0.66%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.66%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 0.66%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 0.66%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 0.66%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.66%   |
| ASUS BCM20702A0                                                      | 1        | 0.66%   |
| ASUS ASUS USB-BT500                                                  | 1        | 0.66%   |
| ASUS 2045 Bluetooth 2.0 Device with trace filter                     | 1        | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 159      | 26.24%  |
| Nvidia                               | 145      | 23.93%  |
| Intel                                | 140      | 23.1%   |
| C-Media Electronics                  | 20       | 3.3%    |
| Logitech                             | 15       | 2.48%   |
| SteelSeries ApS                      | 14       | 2.31%   |
| Kingston Technology                  | 10       | 1.65%   |
| Creative Labs                        | 8        | 1.32%   |
| Texas Instruments                    | 7        | 1.16%   |
| JMTek                                | 7        | 1.16%   |
| Razer USA                            | 6        | 0.99%   |
| Sony                                 | 5        | 0.83%   |
| RODE Microphones                     | 5        | 0.83%   |
| Focusrite-Novation                   | 5        | 0.83%   |
| Blue Microphones                     | 5        | 0.83%   |
| Valve Software                       | 3        | 0.5%    |
| Creative Technology                  | 3        | 0.5%    |
| XMOS                                 | 2        | 0.33%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.33%   |
| Samson Technologies                  | 2        | 0.33%   |
| KTMicro                              | 2        | 0.33%   |
| Hewlett-Packard                      | 2        | 0.33%   |
| Giga-Byte Technology                 | 2        | 0.33%   |
| Generalplus Technology               | 2        | 0.33%   |
| Corsair                              | 2        | 0.33%   |
| Yamaha                               | 1        | 0.17%   |
| Xilinx                               | 1        | 0.17%   |
| VIA Technologies                     | 1        | 0.17%   |
| Trust                                | 1        | 0.17%   |
| TC Electronic                        | 1        | 0.17%   |
| Solid State System                   | 1        | 0.17%   |
| Sennheiser Communications            | 1        | 0.17%   |
| Realtek Semiconductor                | 1        | 0.17%   |
| Pro-Ject                             | 1        | 0.17%   |
| PreSonus Audio Electronics           | 1        | 0.17%   |
| Plantronics                          | 1        | 0.17%   |
| No brand                             | 1        | 0.17%   |
| Native Instruments                   | 1        | 0.17%   |
| NAD Electronics                      | 1        | 0.17%   |
| Micro Star International             | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 77       | 10.97%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 28       | 3.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 27       | 3.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 27       | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 20       | 2.85%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 19       | 2.71%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 19       | 2.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 19       | 2.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 19       | 2.71%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 15       | 2.14%   |
| Intel 200 Series PCH HD Audio                                                                   | 15       | 2.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 15       | 2.14%   |
| Intel Cannon Lake PCH cAVS                                                                      | 14       | 1.99%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 12       | 1.71%   |
| AMD Navi 10 HDMI Audio                                                                          | 12       | 1.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 11       | 1.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 10       | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 10       | 1.42%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 9        | 1.28%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 9        | 1.28%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 8        | 1.14%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 7        | 1%      |
| Nvidia GK104 HDMI Audio Controller                                                              | 7        | 1%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 6        | 0.85%   |
| Kingston Technology HyperX 7.1 Audio                                                            | 6        | 0.85%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 6        | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 6        | 0.85%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 6        | 0.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 6        | 0.85%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 5        | 0.71%   |
| SteelSeries ApS Arctis Pro Wireless                                                             | 5        | 0.71%   |
| Nvidia TU104 HD Audio Controller                                                                | 5        | 0.71%   |
| JMTek USB PnP Audio Device                                                                      | 5        | 0.71%   |
| Intel Audio device                                                                              | 5        | 0.71%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 5        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 5        | 0.71%   |
| C-Media Electronics USB Audio Device                                                            | 5        | 0.71%   |
| Blue Microphones Yeti Stereo Microphone                                                         | 5        | 0.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 5        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 4        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 46       | 20.26%  |
| G.Skill             | 42       | 18.5%   |
| Kingston            | 29       | 12.78%  |
| Crucial             | 24       | 10.57%  |
| Samsung Electronics | 17       | 7.49%   |
| Unknown             | 13       | 5.73%   |
| SK hynix            | 11       | 4.85%   |
| Team                | 8        | 3.52%   |
| Patriot             | 8        | 3.52%   |
| Micron Technology   | 6        | 2.64%   |
| A-DATA Technology   | 4        | 1.76%   |
| Unknown             | 3        | 1.32%   |
| Ramaxel Technology  | 2        | 0.88%   |
| GOODRAM             | 2        | 0.88%   |
| Golden Empire       | 2        | 0.88%   |
| Wilk                | 1        | 0.44%   |
| Unknown (ABCD)      | 1        | 0.44%   |
| Unknown (0x5846)    | 1        | 0.44%   |
| Strontium           | 1        | 0.44%   |
| PNY                 | 1        | 0.44%   |
| Neo Forza           | 1        | 0.44%   |
| Kingmax             | 1        | 0.44%   |
| GeIL                | 1        | 0.44%   |
| Avant               | 1        | 0.44%   |
| AMD                 | 1        | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 11       | 4.33%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 6        | 2.36%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 4        | 1.57%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s      | 3        | 1.18%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 3        | 1.18%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 3        | 1.18%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s              | 3        | 1.18%   |
| Unknown                                                  | 3        | 1.18%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 0.79%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s       | 2        | 0.79%   |
| Team RAM TEAMGROUP-UD4-3200 16384MB DIMM DDR4 3733MT/s   | 2        | 0.79%   |
| SK hynix RAM HMT41GU6AFR8C-PB 8GB DIMM DDR3 1600MT/s     | 2        | 0.79%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 0.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 2        | 0.79%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.79%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s      | 2        | 0.79%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s      | 2        | 0.79%   |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s      | 2        | 0.79%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 2        | 0.79%   |
| Patriot RAM PSD34G16002 4GB DIMM DDR3 1648MT/s           | 2        | 0.79%   |
| G.Skill RAM F4-3600C18-16GTZR 16GB DIMM DDR4 3600MT/s    | 2        | 0.79%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s   | 2        | 0.79%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 2        | 0.79%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 2        | 0.79%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s      | 2        | 0.79%   |
| G.Skill RAM F4-3200C16-8GTZRX 8GB DIMM DDR4 3200MT/s     | 2        | 0.79%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 2        | 0.79%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 2        | 0.79%   |
| G.Skill RAM F4-3200C16-16GIS 16384MB DIMM DDR4 3600MT/s  | 2        | 0.79%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 2        | 0.79%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2733MT/s   | 2        | 0.79%   |
| Crucial RAM BL8G32C16U4BL.M8FE 8GB DIMM DDR4 3600MT/s    | 2        | 0.79%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s | 2        | 0.79%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s    | 2        | 0.79%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 2        | 0.79%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 2        | 0.79%   |
| Wilk RAM IRX3200D464L16SA/8G 8GB DIMM DDR4 3200MT/s      | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 140      | 68.97%  |
| DDR3    | 40       | 19.7%   |
| Unknown | 7        | 3.45%   |
| SDRAM   | 5        | 2.46%   |
| DDR2    | 5        | 2.46%   |
| LPDDR4  | 3        | 1.48%   |
| DDR5    | 2        | 0.99%   |
| DDR     | 1        | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 186      | 94.42%  |
| SODIMM  | 9        | 4.57%   |
| RIMM    | 1        | 0.51%   |
| FB-DIMM | 1        | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 112      | 51.85%  |
| 16384 | 37       | 17.13%  |
| 4096  | 36       | 16.67%  |
| 32768 | 15       | 6.94%   |
| 2048  | 14       | 6.48%   |
| 1024  | 2        | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 41       | 17.9%   |
| 3600    | 36       | 15.72%  |
| 1600    | 26       | 11.35%  |
| 1333    | 16       | 6.99%   |
| 2667    | 12       | 5.24%   |
| 2400    | 9        | 3.93%   |
| 2133    | 9        | 3.93%   |
| 3466    | 7        | 3.06%   |
| 3400    | 7        | 3.06%   |
| 3733    | 5        | 2.18%   |
| 3266    | 5        | 2.18%   |
| 3866    | 4        | 1.75%   |
| 3800    | 4        | 1.75%   |
| 3000    | 4        | 1.75%   |
| 800     | 4        | 1.75%   |
| 2666    | 3        | 1.31%   |
| 1867    | 3        | 1.31%   |
| 1800    | 3        | 1.31%   |
| 3500    | 2        | 0.87%   |
| 3333    | 2        | 0.87%   |
| 2733    | 2        | 0.87%   |
| 1648    | 2        | 0.87%   |
| 667     | 2        | 0.87%   |
| Unknown | 2        | 0.87%   |
| 65535   | 1        | 0.44%   |
| 49926   | 1        | 0.44%   |
| 5800    | 1        | 0.44%   |
| 4800    | 1        | 0.44%   |
| 4333    | 1        | 0.44%   |
| 4000    | 1        | 0.44%   |
| 3534    | 1        | 0.44%   |
| 3533    | 1        | 0.44%   |
| 3151    | 1        | 0.44%   |
| 3134    | 1        | 0.44%   |
| 3066    | 1        | 0.44%   |
| 2933    | 1        | 0.44%   |
| 2800    | 1        | 0.44%   |
| 2465    | 1        | 0.44%   |
| 2267    | 1        | 0.44%   |
| 2048    | 1        | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 4        | 50%     |
| Prolific Technology | 1        | 12.5%   |
| Pantum              | 1        | 12.5%   |
| Hewlett-Packard     | 1        | 12.5%   |
| Canon               | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Prolific PL2305 Parallel Port | 1        | 12.5%   |
| Pantum P2500W series          | 1        | 12.5%   |
| HP ColorLaserJet M253-M254    | 1        | 12.5%   |
| Canon PIXMA MG2500 Series     | 1        | 12.5%   |
| Brother Printer               | 1        | 12.5%   |
| Brother MFC-J4535DW           | 1        | 12.5%   |
| Brother HL-2130 series        | 1        | 12.5%   |
| Brother DCP-9015CDW           | 1        | 12.5%   |

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


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 41       | 44.57%  |
| Microdia                               | 8        | 8.7%    |
| Microsoft                              | 6        | 6.52%   |
| Valve Software                         | 3        | 3.26%   |
| Sunplus Innovation Technology          | 3        | 3.26%   |
| Hewlett-Packard                        | 3        | 3.26%   |
| MacroSilicon                           | 2        | 2.17%   |
| Huawei Technologies                    | 2        | 2.17%   |
| Xiaomi                                 | 1        | 1.09%   |
| WCM_USB                                | 1        | 1.09%   |
| Trust                                  | 1        | 1.09%   |
| Tobii AB                               | 1        | 1.09%   |
| Sunplus IT                             | 1        | 1.09%   |
| Sony                                   | 1        | 1.09%   |
| SN0002                                 | 1        | 1.09%   |
| SJ-180517-N                            | 1        | 1.09%   |
| Samsung Electronics                    | 1        | 1.09%   |
| Realtek Semiconductor                  | 1        | 1.09%   |
| Razer USA                              | 1        | 1.09%   |
| Nikon                                  | 1        | 1.09%   |
| LG Electronics                         | 1        | 1.09%   |
| Lenovo                                 | 1        | 1.09%   |
| Leap Motion                            | 1        | 1.09%   |
| KYE Systems (Mouse Systems)            | 1        | 1.09%   |
| HTC (High Tech Computer)               | 1        | 1.09%   |
| Google                                 | 1        | 1.09%   |
| GEMBIRD                                | 1        | 1.09%   |
| EVGA                                   | 1        | 1.09%   |
| Creative Technology                    | 1        | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 1.09%   |
| Apple                                  | 1        | 1.09%   |
| Unknown                                | 1        | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920        | 10       | 10.75%  |
| Logitech Webcam C270               | 9        | 9.68%   |
| Logitech C922 Pro Stream Webcam    | 4        | 4.3%    |
| Valve Software 3D Camera           | 3        | 3.23%   |
| Microdia Webcam Vitade AF          | 3        | 3.23%   |
| Logitech Webcam C310               | 3        | 3.23%   |
| Logitech HD Webcam C615            | 3        | 3.23%   |
| Microsoft LifeCam HD-3000          | 2        | 2.15%   |
| Microdia USB 2.0 Camera            | 2        | 2.15%   |
| MacroSilicon USB Video             | 2        | 2.15%   |
| Logitech StreamCam                 | 2        | 2.15%   |
| Logitech BRIO Ultra HD Webcam      | 2        | 2.15%   |
| Huawei HD Webcam                   | 2        | 2.15%   |
| HP Webcam HD 2300                  | 2        | 2.15%   |
| Xiaomi Mi/Redmi series (PTP + ADB) | 1        | 1.08%   |
| WCM_USB WEB CAM                    | 1        | 1.08%   |
| Trust FHD Webcam                   | 1        | 1.08%   |
| Tobii AB EyeChip                   | 1        | 1.08%   |
| Sunplus IT AUKEY PC-LM1 USB Camera | 1        | 1.08%   |
| Sunplus FHD Camera Microphone      | 1        | 1.08%   |
| Sunplus Canyon CNS CWC5 Webcam     | 1        | 1.08%   |
| Sunplus AAPDQT-0622-W              | 1        | 1.08%   |
| Sony CEVCECM                       | 1        | 1.08%   |
| SN0002 1080P Web Camera            | 1        | 1.08%   |
| SJ-180517-N 1080P Webcam           | 1        | 1.08%   |
| Samsung Galaxy A5 (MTP)            | 1        | 1.08%   |
| Realtek Webcam                     | 1        | 1.08%   |
| Razer USA Razer Kiyo               | 1        | 1.08%   |
| Nikon D50 (ptp)                    | 1        | 1.08%   |
| Microsoft LifeCam VX-800           | 1        | 1.08%   |
| Microsoft LifeCam VX-5000          | 1        | 1.08%   |
| Microsoft LifeCam VX-2000          | 1        | 1.08%   |
| Microsoft LifeCam Cinema           | 1        | 1.08%   |
| Microdia USB Live camera           | 1        | 1.08%   |
| Microdia Integrated Camera         | 1        | 1.08%   |
| Microdia CameraA                   | 1        | 1.08%   |
| Logitech Webcam C600               | 1        | 1.08%   |
| Logitech Webcam C170               | 1        | 1.08%   |
| Logitech Webcam C110               | 1        | 1.08%   |
| Logitech Webcam B500               | 1        | 1.08%   |

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


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| HID Global  | 1        | 50%     |
| Alcor Micro | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| HID Global USB Reader V3            | 1        | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 245      | 86.88%  |
| 1     | 33       | 11.7%   |
| 2     | 3        | 1.06%   |
| 3     | 1        | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 9        | 23.68%  |
| Network               | 6        | 15.79%  |
| Net/ethernet          | 5        | 13.16%  |
| Graphics card         | 5        | 13.16%  |
| Camera                | 3        | 7.89%   |
| Sound                 | 2        | 5.26%   |
| Multimedia controller | 2        | 5.26%   |
| Chipcard              | 2        | 5.26%   |
| Bluetooth             | 2        | 5.26%   |
| Unassigned class      | 1        | 2.63%   |
| Dvb card              | 1        | 2.63%   |


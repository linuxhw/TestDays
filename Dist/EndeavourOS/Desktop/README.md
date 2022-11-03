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

Total: 319

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| HP         | 18E4                        | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| Gigabyte   | P55A-UD3                    | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| ASUSTek    | PRIME B560M-A               | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| ASRock     | B450M Pro4                  | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| HP         | 18E7                        | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| Acer       | Predator PO3-620            | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| HP         | 18E4                        | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| ASRock     | Z270 Killer SLI/ac          | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| Dell       | 040DDP A01                  | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| ASUSTek    | PRIME X570-PRO              | [3ab5922ddf](https://linux-hardware.org/?probe=3ab5922ddf) | Oct 25, 2022 |
| MSI        | MAG Z490 TOMAHAWK           | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| ASRock     | A320M-HDV R4.0              | [17a0e006d0](https://linux-hardware.org/?probe=17a0e006d0) | Oct 25, 2022 |
| Gigabyte   | P35C-DS3R                   | [c6966a0df9](https://linux-hardware.org/?probe=c6966a0df9) | Oct 25, 2022 |
| Gigabyte   | P35C-DS3R                   | [5b4ecfb7e9](https://linux-hardware.org/?probe=5b4ecfb7e9) | Oct 25, 2022 |
| Dell       | 042P49 A02                  | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| Medion     | B460H6-EM                   | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| HP         | 18E4                        | [dfbdab6987](https://linux-hardware.org/?probe=dfbdab6987) | Oct 21, 2022 |
| Gigabyte   | H87M-D3H                    | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| Lenovo     | 3111 SDK0J40697 WIN 3305... | [c8997eb831](https://linux-hardware.org/?probe=c8997eb831) | Oct 20, 2022 |
| ASUSTek    | Z170 PRO GAMING             | [01338c4f3c](https://linux-hardware.org/?probe=01338c4f3c) | Oct 19, 2022 |
| ASRock     | B450 Pro4                   | [d7784759fb](https://linux-hardware.org/?probe=d7784759fb) | Oct 19, 2022 |
| MSI        | Z390-A PRO                  | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Gigabyte   | Z390 GAMING X-CF            | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| MSI        | B250M PRO-VD                | [28d9942c9f](https://linux-hardware.org/?probe=28d9942c9f) | Oct 17, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [bf1677e47c](https://linux-hardware.org/?probe=bf1677e47c) | Oct 14, 2022 |
| ASUSTek    | PRIME B560M-A               | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| Gigabyte   | H81M-S2PV                   | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| HP         | 18E4                        | [6603067eba](https://linux-hardware.org/?probe=6603067eba) | Oct 10, 2022 |
| HP         | 18E4                        | [53c6bf7af4](https://linux-hardware.org/?probe=53c6bf7af4) | Oct 06, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [75e1aeaff5](https://linux-hardware.org/?probe=75e1aeaff5) | Oct 02, 2022 |
| ASUSTek    | PRIME Z390-P                | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| MSI        | MPG X570 GAMING EDGE WIF... | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| ASRock     | B450M-HDV R4.0              | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Huanan     | X99-8M-F V1.3               | [6e96f4620a](https://linux-hardware.org/?probe=6e96f4620a) | Sep 25, 2022 |
| Huanan     | X99-8M-F V1.3               | [acb677ddeb](https://linux-hardware.org/?probe=acb677ddeb) | Sep 25, 2022 |
| ASRock     | B450 Pro4                   | [fe99b8a461](https://linux-hardware.org/?probe=fe99b8a461) | Sep 25, 2022 |
| ASUSTek    | SABERTOOTH P67              | [164ad85233](https://linux-hardware.org/?probe=164ad85233) | Sep 23, 2022 |
| AZW        | SEi                         | [579b2be420](https://linux-hardware.org/?probe=579b2be420) | Sep 23, 2022 |
| Gigabyte   | GB-BRR7H-4800               | [d0f94bde46](https://linux-hardware.org/?probe=d0f94bde46) | Sep 21, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [f4f33e2362](https://linux-hardware.org/?probe=f4f33e2362) | Sep 20, 2022 |
| ASUSTek    | SABERTOOTH P67              | [579f73fc88](https://linux-hardware.org/?probe=579f73fc88) | Sep 19, 2022 |
| MSI        | MPG B550 GAMING EDGE WIF... | [543fad9f1c](https://linux-hardware.org/?probe=543fad9f1c) | Sep 18, 2022 |
| HP         | 1998                        | [f3ef7a85fe](https://linux-hardware.org/?probe=f3ef7a85fe) | Sep 16, 2022 |
| MSI        | Z170A KRAIT GAMING 3X       | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| MSI        | MPG Z390M GAMING EDGE AC    | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| ASUSTek    | H170M-PLUS                  | [df80ca89ee](https://linux-hardware.org/?probe=df80ca89ee) | Sep 08, 2022 |
| Dell       | 0HMF7C A01                  | [292123f83b](https://linux-hardware.org/?probe=292123f83b) | Sep 03, 2022 |
| ASUSTek    | PRIME H310M-K               | [2fb52eb1a8](https://linux-hardware.org/?probe=2fb52eb1a8) | Sep 03, 2022 |
| MSI        | X570-A PRO                  | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte   | P55A-UD3                    | [297cab0eb2](https://linux-hardware.org/?probe=297cab0eb2) | Sep 01, 2022 |
| HP         | 18E7                        | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| ASUSTek    | Maximus IX HERO             | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| ASRock     | B550M Pro4                  | [9b5ba9f755](https://linux-hardware.org/?probe=9b5ba9f755) | Aug 18, 2022 |
| MSI        | A320M PRO-E                 | [2aa966d8af](https://linux-hardware.org/?probe=2aa966d8af) | Aug 14, 2022 |
| ASUSTek    | PRIME X570-P                | [94579c3a70](https://linux-hardware.org/?probe=94579c3a70) | Aug 13, 2022 |
| AZW        | U59                         | [33aea75ff4](https://linux-hardware.org/?probe=33aea75ff4) | Aug 07, 2022 |
| Gigabyte   | B550M AORUS PRO             | [7a5337e18d](https://linux-hardware.org/?probe=7a5337e18d) | Jul 28, 2022 |
| ASRock     | A320M-HDV R4.0              | [06dd902359](https://linux-hardware.org/?probe=06dd902359) | Jul 23, 2022 |
| MSI        | PRO Z690-A WIFI             | [00f490c5d0](https://linux-hardware.org/?probe=00f490c5d0) | Jul 22, 2022 |
| Gigabyte   | Z690 GAMING X DDR4          | [b3f65d7c35](https://linux-hardware.org/?probe=b3f65d7c35) | Jul 21, 2022 |
| ASUSTek    | TUF Gaming B550-PRO         | [d7e2758b93](https://linux-hardware.org/?probe=d7e2758b93) | Jul 20, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| Samsung    | DeskTop System              | [d0d33ec330](https://linux-hardware.org/?probe=d0d33ec330) | Jul 19, 2022 |
| Samsung    | DeskTop System              | [3af9bcc9cb](https://linux-hardware.org/?probe=3af9bcc9cb) | Jul 19, 2022 |
| ASUSTek    | TUF B450-PLUS GAMING        | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Gigabyte   | B550 AORUS ELITE            | [85a02f5d41](https://linux-hardware.org/?probe=85a02f5d41) | Jul 15, 2022 |
| Gigabyte   | X470 AORUS GAMING 7 WIFI... | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HP         | 158B                        | [1f3ebf7ecf](https://linux-hardware.org/?probe=1f3ebf7ecf) | Jul 07, 2022 |
| Gigabyte   | N3160TN                     | [b92830b100](https://linux-hardware.org/?probe=b92830b100) | Jul 03, 2022 |
| Gigabyte   | P55A-UD3                    | [36dcdacdb1](https://linux-hardware.org/?probe=36dcdacdb1) | Jul 01, 2022 |
| ASRock     | B450M Pro4                  | [5dd727cd5e](https://linux-hardware.org/?probe=5dd727cd5e) | Jul 01, 2022 |
| ASUSTek    | ROG Maximus Z690 HERO       | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI        | MAG B550 TOMAHAWK           | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| Gigabyte   | B450 AORUS PRO WIFI-CF      | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| ASUSTek    | P8Z77-V                     | [16d7a07f8f](https://linux-hardware.org/?probe=16d7a07f8f) | Jun 20, 2022 |
| Dell       | 040DDP A01                  | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| MSI        | B450 GAMING PRO CARBON A... | [b0cc04798d](https://linux-hardware.org/?probe=b0cc04798d) | Jun 18, 2022 |
| Gigabyte   | B550M AORUS PRO-P           | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| ASUSTek    | SABERTOOTH X99              | [5c7a9690cf](https://linux-hardware.org/?probe=5c7a9690cf) | Jun 05, 2022 |
| ASUSTek    | H110M-E/M.2                 | [cb5ea65a1d](https://linux-hardware.org/?probe=cb5ea65a1d) | Jun 04, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| ASRock     | B450 Pro4                   | [394d112de5](https://linux-hardware.org/?probe=394d112de5) | May 31, 2022 |
| Gigabyte   | X470 AORUS GAMING 7 WIFI... | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| Gigabyte   | B550M AORUS PRO             | [0075e2d9df](https://linux-hardware.org/?probe=0075e2d9df) | May 28, 2022 |
| Dell       | 0K240Y A01                  | [4ef7645f2d](https://linux-hardware.org/?probe=4ef7645f2d) | May 28, 2022 |
| HP         | 0A08h                       | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP         | 0A08h                       | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| ASRock     | A320M/ac                    | [78ee9c8853](https://linux-hardware.org/?probe=78ee9c8853) | May 20, 2022 |
| HP         | 3647h                       | [eccb82bec8](https://linux-hardware.org/?probe=eccb82bec8) | May 20, 2022 |
| HP         | 8906 SMVB                   | [0bc568827c](https://linux-hardware.org/?probe=0bc568827c) | May 18, 2022 |
| ASUSTek    | ROG CROSSHAIR VIII IMPAC... | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| MSI        | B75MA-E33                   | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| ASUSTek    | P8H77-M                     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Lenovo     | 3111 SDK0J40697 WIN 3305... | [7354dedb38](https://linux-hardware.org/?probe=7354dedb38) | May 03, 2022 |
| ASRock     | B450 Pro4                   | [bcc65ca336](https://linux-hardware.org/?probe=bcc65ca336) | May 03, 2022 |
| ASRock     | B450 Pro4                   | [e40e784775](https://linux-hardware.org/?probe=e40e784775) | May 03, 2022 |
| ASRock     | AB350M Pro4                 | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| Gigabyte   | P55A-UD3                    | [b212517217](https://linux-hardware.org/?probe=b212517217) | May 01, 2022 |
| ASRock     | B450M Pro4                  | [79a3d8d3f6](https://linux-hardware.org/?probe=79a3d8d3f6) | May 01, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [e45e120b35](https://linux-hardware.org/?probe=e45e120b35) | Apr 29, 2022 |
| ASUSTek    | TUF B450-PRO GAMING         | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek    | TUF B450-PRO GAMING         | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| Gigabyte   | B450M DS3H-CF               | [a7eeea4f7c](https://linux-hardware.org/?probe=a7eeea4f7c) | Apr 27, 2022 |
| ASRock     | B560 Pro4                   | [5fdc5a8e7b](https://linux-hardware.org/?probe=5fdc5a8e7b) | Apr 21, 2022 |
| ASUSTek    | PRIME H410M-E               | [583693a1a9](https://linux-hardware.org/?probe=583693a1a9) | Apr 17, 2022 |
| Gigabyte   | Z390 AORUS PRO-CF           | [1a48a9a11d](https://linux-hardware.org/?probe=1a48a9a11d) | Apr 13, 2022 |
| Gigabyte   | B450 AORUS ELITE            | [1ff04268cf](https://linux-hardware.org/?probe=1ff04268cf) | Apr 13, 2022 |
| ASRock     | B560 Pro4                   | [bbaa6e145b](https://linux-hardware.org/?probe=bbaa6e145b) | Apr 12, 2022 |
| Dell       | 0WMJ54 A01                  | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| ASUSTek    | PRIME Z390-A                | [0127833323](https://linux-hardware.org/?probe=0127833323) | Apr 03, 2022 |
| MSI        | B450M PRO-VDH PLUS          | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI        | B450M PRO-VDH PLUS          | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| ASUSTek    | TUF Gaming B550-PLUS        | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| ASRock     | B450 Pro4                   | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| ASUSTek    | PRIME B450M-A               | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| Gigabyte   | B450 GAMING X               | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Lenovo     | ThinkStation C20 426593U    | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| ASUSTek    | STRIX Z270F GAMING          | [a0a0ba299e](https://linux-hardware.org/?probe=a0a0ba299e) | Mar 15, 2022 |
| Dell       | 0JP3NX A01                  | [e8f9fb7d24](https://linux-hardware.org/?probe=e8f9fb7d24) | Mar 09, 2022 |
| MSI        | B450M PRO-VDH PLUS          | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte   | P55A-UD3                    | [677fa0d0a3](https://linux-hardware.org/?probe=677fa0d0a3) | Mar 01, 2022 |
| ASRock     | B450M Pro4                  | [e81420b85c](https://linux-hardware.org/?probe=e81420b85c) | Mar 01, 2022 |
| MSI        | B75MA-P45                   | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell       | 0KWVT8 A03                  | [f4bc34ce43](https://linux-hardware.org/?probe=f4bc34ce43) | Feb 23, 2022 |
| ASRock     | B450M Pro4                  | [4f87ec9849](https://linux-hardware.org/?probe=4f87ec9849) | Feb 19, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [7ad21cbc90](https://linux-hardware.org/?probe=7ad21cbc90) | Feb 19, 2022 |
| ASRock     | B450M Pro4                  | [2bfd36f050](https://linux-hardware.org/?probe=2bfd36f050) | Feb 18, 2022 |
| Gigabyte   | B450 AORUS ELITE            | [a8c18662ff](https://linux-hardware.org/?probe=a8c18662ff) | Feb 10, 2022 |
| ASUSTek    | TUF Gaming X570-PLUS        | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [64e32a1354](https://linux-hardware.org/?probe=64e32a1354) | Feb 02, 2022 |
| HP         | 1905                        | [8014fae46e](https://linux-hardware.org/?probe=8014fae46e) | Feb 02, 2022 |
| ASUSTek    | P8H77-V                     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| MSI        | B75MA-P45                   | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [5c5ac9fe1d](https://linux-hardware.org/?probe=5c5ac9fe1d) | Jan 26, 2022 |
| ASRock     | A320M-HD                    | [215b5c3802](https://linux-hardware.org/?probe=215b5c3802) | Jan 23, 2022 |
| MSI        | B150M ECO                   | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| HP         | 8643 SMVB                   | [56e21b8bd6](https://linux-hardware.org/?probe=56e21b8bd6) | Jan 22, 2022 |
| HP         | 8643 SMVB                   | [6586f2d78f](https://linux-hardware.org/?probe=6586f2d78f) | Jan 22, 2022 |
| ASUSTek    | TUF Gaming B560-PLUS WIF... | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| ASRock     | B550M Steel Legend          | [b09195fb3c](https://linux-hardware.org/?probe=b09195fb3c) | Jan 20, 2022 |
| ASUSTek    | TUF Gaming B560M-PLUS WI... | [211aac7b59](https://linux-hardware.org/?probe=211aac7b59) | Jan 18, 2022 |
| MSI        | Z170A GAMING M3             | [57e7500f2a](https://linux-hardware.org/?probe=57e7500f2a) | Jan 17, 2022 |
| MSI        | X370 XPOWER GAMING TITAN... | [e1f153a5e6](https://linux-hardware.org/?probe=e1f153a5e6) | Jan 14, 2022 |
| Gigabyte   | TRX40 AORUS MASTER          | [5ca44fe54c](https://linux-hardware.org/?probe=5ca44fe54c) | Jan 10, 2022 |
| ASUSTek    | Maximus VII GENE            | [0462560ab2](https://linux-hardware.org/?probe=0462560ab2) | Jan 10, 2022 |
| ASRock     | FM2A88X Pro3+               | [1cc054ed3f](https://linux-hardware.org/?probe=1cc054ed3f) | Jan 09, 2022 |
| Dell       | 0K240Y A01                  | [2542ffac8a](https://linux-hardware.org/?probe=2542ffac8a) | Jan 06, 2022 |
| MSI        | Z97 PC Mate                 | [2e5c796311](https://linux-hardware.org/?probe=2e5c796311) | Jan 06, 2022 |
| ASUSTek    | M5A99FX PRO R2.0            | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| ASUSTek    | P8Z77-V LX                  | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| ASUSTek    | ROG STRIX X370-F GAMING     | [aa4f09754b](https://linux-hardware.org/?probe=aa4f09754b) | Jan 04, 2022 |
| ASUSTek    | ROG STRIX X370-F GAMING     | [411cf580b4](https://linux-hardware.org/?probe=411cf580b4) | Jan 04, 2022 |
| Gigabyte   | B550 AORUS ELITE V2         | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| ASRock     | B450M Pro4                  | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| MSI        | Z490-A PRO                  | [ab40f6782f](https://linux-hardware.org/?probe=ab40f6782f) | Jan 04, 2022 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Positivo   | POS-PIH81DI                 | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| ASRock     | B450M Pro4                  | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock     | B450 Gaming-ITX/ac          | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| ASUSTek    | Z97-A                       | [1ebd581629](https://linux-hardware.org/?probe=1ebd581629) | Jan 01, 2022 |
| Gigabyte   | Z97X-Gaming 3               | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| ASRock     | B450 Steel Legend           | [9a67c15230](https://linux-hardware.org/?probe=9a67c15230) | Dec 31, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| LattePanda | Alpha                       | [497e370fc3](https://linux-hardware.org/?probe=497e370fc3) | Dec 26, 2021 |
| Biostar    | G31-M7 TE                   | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| LattePanda | Alpha                       | [442f08d351](https://linux-hardware.org/?probe=442f08d351) | Dec 24, 2021 |
| Gigabyte   | M68M-S2P                    | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Acer       | Aspire XC-1660G V:1.1       | [c460e492aa](https://linux-hardware.org/?probe=c460e492aa) | Dec 23, 2021 |
| Gigabyte   | H110N-CF                    | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| MSI        | Z87-G41 PC Mate             | [aa7388fdd1](https://linux-hardware.org/?probe=aa7388fdd1) | Dec 21, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| Unknown    | Intel X79                   | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| Dell       | 0HD5W2 A01                  | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [8c9d779e45](https://linux-hardware.org/?probe=8c9d779e45) | Dec 14, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [641af2bfa6](https://linux-hardware.org/?probe=641af2bfa6) | Dec 13, 2021 |
| ASUSTek    | ProArt X570-CREATOR WIFI    | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| Gigabyte   | B550M AORUS PRO             | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek    | PRIME B350-PLUS             | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| Gigabyte   | X570 AORUS ELITE            | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| MSI        | B350 PC MATE                | [7fbe80215d](https://linux-hardware.org/?probe=7fbe80215d) | Nov 24, 2021 |
| Gigabyte   | B560M DS3H                  | [89ea080ce0](https://linux-hardware.org/?probe=89ea080ce0) | Nov 20, 2021 |
| ASUSTek    | Z87-DELUXE                  | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte   | B560M DS3H                  | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| Gigabyte   | Z77X-D3H                    | [be03431631](https://linux-hardware.org/?probe=be03431631) | Nov 15, 2021 |
| ASUSTek    | K30AD_M31AD_M51AD_M32AD     | [7ebeace900](https://linux-hardware.org/?probe=7ebeace900) | Nov 13, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Gigabyte   | GA-78LMT-USB3               | [1cfd4ee9f9](https://linux-hardware.org/?probe=1cfd4ee9f9) | Nov 11, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [c9e5138184](https://linux-hardware.org/?probe=c9e5138184) | Nov 07, 2021 |
| ASUSTek    | Maximus VIII HERO           | [22ce2703b9](https://linux-hardware.org/?probe=22ce2703b9) | Nov 07, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [5d0bad7c15](https://linux-hardware.org/?probe=5d0bad7c15) | Nov 06, 2021 |
| ASRock     | H310CM-DVS                  | [79e6ef3655](https://linux-hardware.org/?probe=79e6ef3655) | Oct 29, 2021 |
| ASRock     | H310CM-DVS                  | [6db3b9d661](https://linux-hardware.org/?probe=6db3b9d661) | Oct 29, 2021 |
| Gigabyte   | B450 GAMING X               | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| ASRock     | B550M Pro4                  | [87ab64b604](https://linux-hardware.org/?probe=87ab64b604) | Oct 14, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| UMAX       | J42 Nano                    | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| Gigabyte   | B85M-HD3                    | [cc7d0245a7](https://linux-hardware.org/?probe=cc7d0245a7) | Oct 09, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [849ca2da3d](https://linux-hardware.org/?probe=849ca2da3d) | Oct 06, 2021 |
| Gigabyte   | B550 VISION D               | [e8a2ba9952](https://linux-hardware.org/?probe=e8a2ba9952) | Oct 03, 2021 |
| MSI        | G41M-P33 Combo              | [ec8e63e96e](https://linux-hardware.org/?probe=ec8e63e96e) | Oct 01, 2021 |
| Gigabyte   | B250M-DS3H-CF               | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Gigabyte   | H110M-S2-CF                 | [a20f426eed](https://linux-hardware.org/?probe=a20f426eed) | Sep 25, 2021 |
| Gigabyte   | B450M DS3H-CF               | [35cbc8e5b5](https://linux-hardware.org/?probe=35cbc8e5b5) | Sep 19, 2021 |
| Gigabyte   | B450M DS3H-CF               | [860fb3dc8c](https://linux-hardware.org/?probe=860fb3dc8c) | Sep 19, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [8ffa4dd273](https://linux-hardware.org/?probe=8ffa4dd273) | Sep 18, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [60555ce93d](https://linux-hardware.org/?probe=60555ce93d) | Sep 16, 2021 |
| MSI        | B450M PRO-VDH MAX           | [33cee010e8](https://linux-hardware.org/?probe=33cee010e8) | Sep 12, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [c06b4b30a0](https://linux-hardware.org/?probe=c06b4b30a0) | Sep 10, 2021 |
| MSI        | B450-A PRO MAX              | [12cf057e04](https://linux-hardware.org/?probe=12cf057e04) | Sep 02, 2021 |
| Intel      | DH55HC AAE70933-504         | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [1c75e967eb](https://linux-hardware.org/?probe=1c75e967eb) | Aug 24, 2021 |
| HP         | 8906 SMVB                   | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| MSI        | B450 TOMAHAWK MAX           | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| Gigabyte   | P35-DS3R                    | [421cd7ce36](https://linux-hardware.org/?probe=421cd7ce36) | Aug 09, 2021 |
| MSI        | B450M PRO-VDH MAX           | [8e9d51a941](https://linux-hardware.org/?probe=8e9d51a941) | Aug 07, 2021 |
| Dell       | 0K240Y A01                  | [5cc92cb5ac](https://linux-hardware.org/?probe=5cc92cb5ac) | Aug 04, 2021 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Gigabyte   | X399 AORUS PRO-CF           | [404eae69f4](https://linux-hardware.org/?probe=404eae69f4) | Jul 14, 2021 |
| Gigabyte   | GA-78LMT-S2P                | [f36328f6b3](https://linux-hardware.org/?probe=f36328f6b3) | Jul 12, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [14b3d46ef8](https://linux-hardware.org/?probe=14b3d46ef8) | Jul 03, 2021 |
| ASUSTek    | P7H55D-M EVO                | [62f256e36e](https://linux-hardware.org/?probe=62f256e36e) | Jul 03, 2021 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| Gigabyte   | Z97X-Gaming 5               | [625c876e08](https://linux-hardware.org/?probe=625c876e08) | Jun 30, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [10c5bbf0f8](https://linux-hardware.org/?probe=10c5bbf0f8) | Jun 18, 2021 |
| ASUSTek    | F1A55-M LX                  | [9e7c39435d](https://linux-hardware.org/?probe=9e7c39435d) | Jun 13, 2021 |
| Gigabyte   | X570 I AORUS PRO WIFI       | [ed31182c51](https://linux-hardware.org/?probe=ed31182c51) | Jun 07, 2021 |
| Gigabyte   | B550 AORUS ELITE V2         | [585db3001d](https://linux-hardware.org/?probe=585db3001d) | May 19, 2021 |
| HP         | 2B36                        | [62135f1e45](https://linux-hardware.org/?probe=62135f1e45) | May 19, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [fec75a202e](https://linux-hardware.org/?probe=fec75a202e) | May 19, 2021 |
| ASRock     | A300M-STX                   | [fc96347868](https://linux-hardware.org/?probe=fc96347868) | May 12, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [dd68978e2b](https://linux-hardware.org/?probe=dd68978e2b) | Apr 28, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [7ee064e334](https://linux-hardware.org/?probe=7ee064e334) | Apr 27, 2021 |
| ASUSTek    | STRIX B250F GAMING          | [8276e1fb2f](https://linux-hardware.org/?probe=8276e1fb2f) | Apr 20, 2021 |
| ASUSTek    | K30AD_M31AD_M51AD_M32AD     | [cf4d5786e5](https://linux-hardware.org/?probe=cf4d5786e5) | Apr 19, 2021 |
| Lenovo     | SHARKBAY NOK                | [0685ce717e](https://linux-hardware.org/?probe=0685ce717e) | Apr 16, 2021 |
| Gigabyte   | B550M AORUS PRO             | [a635a3acb3](https://linux-hardware.org/?probe=a635a3acb3) | Apr 13, 2021 |
| MSI        | B450 TOMAHAWK MAX           | [e08e82478f](https://linux-hardware.org/?probe=e08e82478f) | Apr 12, 2021 |
| Gigabyte   | B450 AORUS M                | [d53c2a8b0e](https://linux-hardware.org/?probe=d53c2a8b0e) | Apr 11, 2021 |
| Dell       | 0080PM A00                  | [efc9497e6d](https://linux-hardware.org/?probe=efc9497e6d) | Apr 08, 2021 |
| MSI        | MAG B550 TOMAHAWK           | [63e7ed5aa3](https://linux-hardware.org/?probe=63e7ed5aa3) | Apr 07, 2021 |
| Lenovo     | 36EB NOK                    | [2c6f4de8b9](https://linux-hardware.org/?probe=2c6f4de8b9) | Apr 06, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [08f8da317e](https://linux-hardware.org/?probe=08f8da317e) | Apr 03, 2021 |
| Gigabyte   | Z390 GAMING SLI-CF          | [90f906f5f9](https://linux-hardware.org/?probe=90f906f5f9) | Mar 31, 2021 |
| Gigabyte   | Z390 GAMING SLI-CF          | [b2fa0502d0](https://linux-hardware.org/?probe=b2fa0502d0) | Mar 31, 2021 |
| Samsung    | DT_DM500T8A SAMSUNG_SW_R... | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Lenovo     | 3111 SDK0J40697 WIN 3305... | [31baa57d40](https://linux-hardware.org/?probe=31baa57d40) | Mar 17, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [7c5776953c](https://linux-hardware.org/?probe=7c5776953c) | Mar 15, 2021 |
| Gigabyte   | B550M AORUS PRO             | [41de0a7ee7](https://linux-hardware.org/?probe=41de0a7ee7) | Mar 08, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [f9b4d57c67](https://linux-hardware.org/?probe=f9b4d57c67) | Feb 18, 2021 |
| MSI        | Z87-G45 GAMING              | [67ca38a642](https://linux-hardware.org/?probe=67ca38a642) | Feb 12, 2021 |
| MSI        | Z87-G45 GAMING              | [e6937666ae](https://linux-hardware.org/?probe=e6937666ae) | Feb 11, 2021 |
| ASRock     | B550 Phantom Gaming 4       | [e11200bd19](https://linux-hardware.org/?probe=e11200bd19) | Feb 10, 2021 |
| ASUSTek    | H81-PLUS                    | [75fc956099](https://linux-hardware.org/?probe=75fc956099) | Feb 10, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [cef326fa21](https://linux-hardware.org/?probe=cef326fa21) | Feb 08, 2021 |
| ASRock     | B550M Steel Legend          | [335242ec06](https://linux-hardware.org/?probe=335242ec06) | Jan 20, 2021 |
| ASUSTek    | PRIME X470-PRO              | [396227c9b5](https://linux-hardware.org/?probe=396227c9b5) | Jan 14, 2021 |
| Gigabyte   | X58A-UD3R                   | [3d8c62e8fe](https://linux-hardware.org/?probe=3d8c62e8fe) | Jan 04, 2021 |
| ASUSTek    | Z87-PRO                     | [2ab19967fa](https://linux-hardware.org/?probe=2ab19967fa) | Dec 30, 2020 |
| ASUSTek    | Maximus VIII HERO           | [4d27980548](https://linux-hardware.org/?probe=4d27980548) | Dec 27, 2020 |
| ASUSTek    | Maximus VIII HERO           | [08895b552f](https://linux-hardware.org/?probe=08895b552f) | Dec 27, 2020 |
| HP         | 1905                        | [63771015f5](https://linux-hardware.org/?probe=63771015f5) | Dec 22, 2020 |
| Gigabyte   | H110M-S2-CF                 | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| Gigabyte   | X58A-UD3R                   | [a138dbf3ac](https://linux-hardware.org/?probe=a138dbf3ac) | Dec 08, 2020 |
| ASUSTek    | TUF X470-PLUS GAMING        | [00dc0236a1](https://linux-hardware.org/?probe=00dc0236a1) | Dec 07, 2020 |
| Fujitsu    | D2778-B1 S26361-D2778-B1    | [0ffe9c1f28](https://linux-hardware.org/?probe=0ffe9c1f28) | Nov 27, 2020 |
| Lenovo     | 36EB SDK0J40700 WIN 3258... | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| Dell       | 0KRC95 A02                  | [af91587001](https://linux-hardware.org/?probe=af91587001) | Nov 19, 2020 |
| ASRock     | Z77 Extreme4                | [3de701fc00](https://linux-hardware.org/?probe=3de701fc00) | Nov 12, 2020 |
| ASRock     | Z77 Extreme4                | [64d986c0ec](https://linux-hardware.org/?probe=64d986c0ec) | Nov 12, 2020 |
| Dell       | 0KRC95 A02                  | [6471eccd57](https://linux-hardware.org/?probe=6471eccd57) | Nov 11, 2020 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [7a14486580](https://linux-hardware.org/?probe=7a14486580) | Nov 04, 2020 |
| Gigabyte   | H270-HD3-CF                 | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| HP         | 8455                        | [0671b6f4da](https://linux-hardware.org/?probe=0671b6f4da) | Oct 27, 2020 |
| HP         | 8455                        | [e37d606b6b](https://linux-hardware.org/?probe=e37d606b6b) | Oct 26, 2020 |
| Dell       | 0G214D A00                  | [21319d118b](https://linux-hardware.org/?probe=21319d118b) | Oct 25, 2020 |
| MSI        | MS-7366                     | [ada828f120](https://linux-hardware.org/?probe=ada828f120) | Sep 29, 2020 |
| Dell       | 096JG8 A01                  | [a031f4a8a2](https://linux-hardware.org/?probe=a031f4a8a2) | Sep 29, 2020 |
| MSI        | B450 TOMAHAWK MAX           | [ee969068e8](https://linux-hardware.org/?probe=ee969068e8) | Sep 28, 2020 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [a4e794299b](https://linux-hardware.org/?probe=a4e794299b) | Sep 28, 2020 |
| ASUSTek    | P8P67 DELUXE                | [ba15c37977](https://linux-hardware.org/?probe=ba15c37977) | Sep 28, 2020 |
| MSI        | MS-7366                     | [9938e6501b](https://linux-hardware.org/?probe=9938e6501b) | Sep 24, 2020 |
| Gigabyte   | B450 AORUS M                | [34f1896f7e](https://linux-hardware.org/?probe=34f1896f7e) | Sep 23, 2020 |
| Gigabyte   | B550M AORUS PRO             | [17e933a69c](https://linux-hardware.org/?probe=17e933a69c) | Sep 21, 2020 |
| HP         | 1497                        | [7cb2cee563](https://linux-hardware.org/?probe=7cb2cee563) | Sep 19, 2020 |
| Gigabyte   | B550M AORUS PRO             | [50a3035c47](https://linux-hardware.org/?probe=50a3035c47) | Sep 12, 2020 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [3919584d23](https://linux-hardware.org/?probe=3919584d23) | Sep 06, 2020 |
| ASRock     | X470 Gaming-ITX/ac          | [028f3ba060](https://linux-hardware.org/?probe=028f3ba060) | Sep 03, 2020 |
| ASUSTek    | M5A97 R2.0                  | [662f61d283](https://linux-hardware.org/?probe=662f61d283) | Sep 03, 2020 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [143c679f1a](https://linux-hardware.org/?probe=143c679f1a) | Sep 03, 2020 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [2ab9b15cb6](https://linux-hardware.org/?probe=2ab9b15cb6) | Sep 03, 2020 |
| Gigabyte   | Z170-Gaming K3-CF           | [f70636a60c](https://linux-hardware.org/?probe=f70636a60c) | Sep 02, 2020 |
| ASUSTek    | Z87M-PLUS                   | [844cca1bee](https://linux-hardware.org/?probe=844cca1bee) | Aug 09, 2020 |
| ASUSTek    | PRIME X570-P                | [cb7a700ec4](https://linux-hardware.org/?probe=cb7a700ec4) | Aug 07, 2020 |
| Gigabyte   | B365M DS3H                  | [79c5cea1c1](https://linux-hardware.org/?probe=79c5cea1c1) | Jul 14, 2020 |
| Fujitsu    | D2778-B1 S26361-D2778-B1    | [54774ae912](https://linux-hardware.org/?probe=54774ae912) | Jul 14, 2020 |
| Fujitsu    | D2618-C1 S26361-D2618-C1    | [85295c522b](https://linux-hardware.org/?probe=85295c522b) | Jul 14, 2020 |
| Lenovo     | MAHOBAY NOK                 | [6e3c82fbca](https://linux-hardware.org/?probe=6e3c82fbca) | Jul 13, 2020 |
| ASUSTek    | Z87M-PLUS                   | [d0c246206e](https://linux-hardware.org/?probe=d0c246206e) | Jul 13, 2020 |
| MSI        | MPG X570 GAMING PLUS        | [5ed412893a](https://linux-hardware.org/?probe=5ed412893a) | Jul 12, 2020 |
| Gigabyte   | B365M DS3H                  | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| Gigabyte   | X570 AORUS MASTER           | [b81603bb8b](https://linux-hardware.org/?probe=b81603bb8b) | Jul 12, 2020 |
| MSI        | B450-A PRO MAX              | [22ee76b578](https://linux-hardware.org/?probe=22ee76b578) | Jun 29, 2020 |
| ASUSTek    | TUF Gaming X570-PLUS        | [eb81165361](https://linux-hardware.org/?probe=eb81165361) | May 31, 2020 |
| Biostar    | G31-M7 TE                   | [0ae18cfc51](https://linux-hardware.org/?probe=0ae18cfc51) | May 05, 2020 |
| Gigabyte   | B85M-D3H                    | [adba7e2f11](https://linux-hardware.org/?probe=adba7e2f11) | Apr 24, 2020 |
| ASUSTek    | PRIME A320M-K               | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Gigabyte   | B450M S2H                   | [5a1d01743b](https://linux-hardware.org/?probe=5a1d01743b) | Feb 12, 2020 |
| ASUSTek    | PRIME A320M-K               | [32f5e3b842](https://linux-hardware.org/?probe=32f5e3b842) | Nov 21, 2019 |
| ASUSTek    | PRIME A320M-K               | [4d0de4b06b](https://linux-hardware.org/?probe=4d0de4b06b) | Nov 19, 2019 |
| ASUSTek    | PRIME A320M-K               | [791bd283a6](https://linux-hardware.org/?probe=791bd283a6) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [50ea35444e](https://linux-hardware.org/?probe=50ea35444e) | Nov 17, 2019 |
| ASUSTek    | PRIME A320M-K               | [42a25ee1f6](https://linux-hardware.org/?probe=42a25ee1f6) | Nov 08, 2019 |
| ASUSTek    | PRIME A320M-K               | [587cf1258f](https://linux-hardware.org/?probe=587cf1258f) | Nov 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| EndeavourOS Rolling | 171      | 74.03%  |
| EndeavourOS         | 60       | 25.97%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| EndeavourOS | 230      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.15.12-arch1-1    | 10       | 3.72%   |
| 5.7.7-arch1-1      | 6        | 2.23%   |
| 6.0.2-zen1-1-zen   | 5        | 1.86%   |
| 6.0.2-arch1-1      | 5        | 1.86%   |
| 5.17.5-arch1-1     | 5        | 1.86%   |
| 5.17.1-arch1-1     | 5        | 1.86%   |
| 5.16.2-arch1-1     | 5        | 1.86%   |
| 5.18.12-arch1-1    | 4        | 1.49%   |
| 5.15.74-1-lts      | 4        | 1.49%   |
| 5.15.7-arch1-1     | 4        | 1.49%   |
| 5.11.11-arch1-1    | 4        | 1.49%   |
| 5.19.10-arch1-1    | 3        | 1.12%   |
| 5.18.7-arch1-1     | 3        | 1.12%   |
| 5.18.5-arch1-1     | 3        | 1.12%   |
| 5.17.9-arch1-1     | 3        | 1.12%   |
| 5.16.16-arch1-1    | 3        | 1.12%   |
| 5.16.10-arch1-1    | 3        | 1.12%   |
| 5.15.8-arch1-1     | 3        | 1.12%   |
| 5.15.12-zen1-1-zen | 3        | 1.12%   |
| 5.15.10-arch1-1    | 3        | 1.12%   |
| 5.14.9-arch2-1     | 3        | 1.12%   |
| 5.14.8-arch1-1     | 3        | 1.12%   |
| 5.10.88-2-lts      | 3        | 1.12%   |
| 6.0.6-zen1-1-zen   | 2        | 0.74%   |
| 6.0.6-arch1-1      | 2        | 0.74%   |
| 5.9.14-arch1-1     | 2        | 0.74%   |
| 5.9.12-arch1-1     | 2        | 0.74%   |
| 5.9.1-arch1-1      | 2        | 0.74%   |
| 5.8.11-arch1-1     | 2        | 0.74%   |
| 5.8.10-arch1-1     | 2        | 0.74%   |
| 5.19.9-zen1-1-zen  | 2        | 0.74%   |
| 5.19.5-arch1-1     | 2        | 0.74%   |
| 5.19.13-zen1-1-zen | 2        | 0.74%   |
| 5.18.9-arch1-1     | 2        | 0.74%   |
| 5.18.6-arch1-1     | 2        | 0.74%   |
| 5.18.14-arch1-1    | 2        | 0.74%   |
| 5.17.8-arch1-1     | 2        | 0.74%   |
| 5.17.5-zen1-1-zen  | 2        | 0.74%   |
| 5.16.16-zen1-1-zen | 2        | 0.74%   |
| 5.16.11-arch1-1    | 2        | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.12 | 14       | 5.2%    |
| 6.0.2   | 10       | 3.72%   |
| 5.17.5  | 7        | 2.6%    |
| 5.7.7   | 6        | 2.23%   |
| 5.19.9  | 5        | 1.86%   |
| 5.18.12 | 5        | 1.86%   |
| 5.17.1  | 5        | 1.86%   |
| 5.16.2  | 5        | 1.86%   |
| 5.16.16 | 5        | 1.86%   |
| 5.15.7  | 5        | 1.86%   |
| 6.0.6   | 4        | 1.49%   |
| 5.8.5   | 4        | 1.49%   |
| 5.18.5  | 4        | 1.49%   |
| 5.17.9  | 4        | 1.49%   |
| 5.15.74 | 4        | 1.49%   |
| 5.11.11 | 4        | 1.49%   |
| 5.10.88 | 4        | 1.49%   |
| 5.9.1   | 3        | 1.12%   |
| 5.19.5  | 3        | 1.12%   |
| 5.19.10 | 3        | 1.12%   |
| 5.18.7  | 3        | 1.12%   |
| 5.16.11 | 3        | 1.12%   |
| 5.16.10 | 3        | 1.12%   |
| 5.15.8  | 3        | 1.12%   |
| 5.15.13 | 3        | 1.12%   |
| 5.15.10 | 3        | 1.12%   |
| 5.14.9  | 3        | 1.12%   |
| 5.14.8  | 3        | 1.12%   |
| 5.12.15 | 3        | 1.12%   |
| 6.0.5   | 2        | 0.74%   |
| 5.9.14  | 2        | 0.74%   |
| 5.9.12  | 2        | 0.74%   |
| 5.8.11  | 2        | 0.74%   |
| 5.8.10  | 2        | 0.74%   |
| 5.7.12  | 2        | 0.74%   |
| 5.19.13 | 2        | 0.74%   |
| 5.18.9  | 2        | 0.74%   |
| 5.18.6  | 2        | 0.74%   |
| 5.18.16 | 2        | 0.74%   |
| 5.18.14 | 2        | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 47       | 17.94%  |
| 5.18    | 26       | 9.92%   |
| 5.16    | 25       | 9.54%   |
| 5.19    | 22       | 8.4%    |
| 5.17    | 21       | 8.02%   |
| 5.14    | 17       | 6.49%   |
| 6.0     | 16       | 6.11%   |
| 5.10    | 15       | 5.73%   |
| 5.11    | 14       | 5.34%   |
| 5.9     | 13       | 4.96%   |
| 5.12    | 13       | 4.96%   |
| 5.8     | 10       | 3.82%   |
| 5.7     | 9        | 3.44%   |
| 5.13    | 7        | 2.67%   |
| 5.6     | 3        | 1.15%   |
| 5.5     | 2        | 0.76%   |
| 5.4     | 1        | 0.38%   |
| Unknown | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 230      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 95       | 39.09%  |
| XFCE            | 45       | 18.52%  |
| GNOME           | 44       | 18.11%  |
| X-Cinnamon      | 13       | 5.35%   |
| KDE             | 11       | 4.53%   |
| i3              | 10       | 4.12%   |
| Budgie          | 6        | 2.47%   |
| Cinnamon        | 4        | 1.65%   |
| sway            | 3        | 1.23%   |
| LXQt            | 3        | 1.23%   |
| Unknown         | 3        | 1.23%   |
| MATE            | 2        | 0.82%   |
| jwm             | 1        | 0.41%   |
| herbstluftwm    | 1        | 0.41%   |
| GNOME Flashback | 1        | 0.41%   |
| awesome         | 1        | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 203      | 85.65%  |
| Wayland | 24       | 10.13%  |
| Tty     | 6        | 2.53%   |
| Unknown | 3        | 1.27%   |
| Web     | 1        | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 68       | 28.69%  |
| Unknown | 66       | 27.85%  |
| SDDM    | 58       | 24.47%  |
| GDM     | 25       | 10.55%  |
| TDM     | 20       | 8.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 108      | 46.75%  |
| de_DE   | 21       | 9.09%   |
| en_GB   | 15       | 6.49%   |
| it_IT   | 12       | 5.19%   |
| en_CA   | 10       | 4.33%   |
| ru_RU   | 8        | 3.46%   |
| pl_PL   | 6        | 2.6%    |
| en_DK   | 4        | 1.73%   |
| en_AG   | 4        | 1.73%   |
| nl_NL   | 3        | 1.3%    |
| nl_BE   | 3        | 1.3%    |
| fr_FR   | 3        | 1.3%    |
| es_AR   | 3        | 1.3%    |
| en_AU   | 3        | 1.3%    |
| Unknown | 3        | 1.3%    |
| pt_BR   | 2        | 0.87%   |
| es_MX   | 2        | 0.87%   |
| es_ES   | 2        | 0.87%   |
| en_IN   | 2        | 0.87%   |
| en_HK   | 2        | 0.87%   |
| tr_TR   | 1        | 0.43%   |
| sv_SE   | 1        | 0.43%   |
| sl_SI   | 1        | 0.43%   |
| hu_HU   | 1        | 0.43%   |
| fr_CA   | 1        | 0.43%   |
| fr_BE   | 1        | 0.43%   |
| es_GT   | 1        | 0.43%   |
| es_CR   | 1        | 0.43%   |
| eo      | 1        | 0.43%   |
| en_ZA   | 1        | 0.43%   |
| en_SG   | 1        | 0.43%   |
| en_FI   | 1        | 0.43%   |
| de_CH   | 1        | 0.43%   |
| de_AT   | 1        | 0.43%   |
| cs_CZ   | 1        | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 132      | 56.65%  |
| BIOS | 101      | 43.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 159      | 68.83%  |
| Btrfs   | 67       | 29%     |
| Overlay | 2        | 0.87%   |
| XXX4    | 1        | 0.43%   |
| Xfs     | 1        | 0.43%   |
| F2fs    | 1        | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 141      | 60.52%  |
| Unknown | 72       | 30.9%   |
| MBR     | 20       | 8.58%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 182      | 78.45%  |
| Yes       | 50       | 21.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 141      | 60%     |
| Yes       | 94       | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 64       | 27.83%  |
| Gigabyte Technology | 50       | 21.74%  |
| MSI                 | 44       | 19.13%  |
| ASRock              | 24       | 10.43%  |
| Hewlett-Packard     | 14       | 6.09%   |
| Dell                | 11       | 4.78%   |
| Lenovo              | 6        | 2.61%   |
| Samsung Electronics | 2        | 0.87%   |
| Fujitsu             | 2        | 0.87%   |
| Biostar             | 2        | 0.87%   |
| AZW                 | 2        | 0.87%   |
| Acer                | 2        | 0.87%   |
| UMAX                | 1        | 0.43%   |
| Positivo            | 1        | 0.43%   |
| Medion              | 1        | 0.43%   |
| LattePanda          | 1        | 0.43%   |
| Intel               | 1        | 0.43%   |
| Huanan              | 1        | 0.43%   |
| Unknown             | 1        | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7C37                         | 9        | 3.91%   |
| ASUS All Series                     | 6        | 2.61%   |
| ASUS ROG STRIX X570-E GAMING        | 4        | 1.74%   |
| ASRock B450 Pro4                    | 4        | 1.74%   |
| MSI MS-7C91                         | 3        | 1.3%    |
| MSI MS-7C02                         | 3        | 1.3%    |
| MSI MS-7A38                         | 3        | 1.3%    |
| Gigabyte B550M AORUS PRO            | 3        | 1.3%    |
| ASUS TUF Gaming X570-PLUS           | 3        | 1.3%    |
| ASRock B450M Pro4                   | 3        | 1.3%    |
| MSI MS-7C84                         | 2        | 0.87%   |
| MSI MS-7B86                         | 2        | 0.87%   |
| MSI MS-7850                         | 2        | 0.87%   |
| MSI MS-7798                         | 2        | 0.87%   |
| HP Z230 Tower Workstation           | 2        | 0.87%   |
| HP ProDesk 600 G1 SFF               | 2        | 0.87%   |
| Gigabyte H110M-S2                   | 2        | 0.87%   |
| Gigabyte B550 AORUS ELITE V2        | 2        | 0.87%   |
| Gigabyte B450M DS3H                 | 2        | 0.87%   |
| Gigabyte B450 AORUS ELITE           | 2        | 0.87%   |
| Dell OptiPlex 3020                  | 2        | 0.87%   |
| Biostar G31-M7 TE                   | 2        | 0.87%   |
| ASUS ROG CROSSHAIR VIII DARK HERO   | 2        | 0.87%   |
| ASUS PRIME X570-P                   | 2        | 0.87%   |
| ASUS K30AD_M31AD_M51AD              | 2        | 0.87%   |
| ASRock B550M Steel Legend           | 2        | 0.87%   |
| ASRock B550M Pro4                   | 2        | 0.87%   |
| UMAX J42 Nano                       | 1        | 0.43%   |
| Samsung DeskTop System              | 1        | 0.43%   |
| Samsung 500T8A/500S8A/500T9A/500S9A | 1        | 0.43%   |
| Positivo POS-PIH81DI                | 1        | 0.43%   |
| MSI MS-7D25                         | 1        | 0.43%   |
| MSI MS-7C80                         | 1        | 0.43%   |
| MSI MS-7C75                         | 1        | 0.43%   |
| MSI MS-7B98                         | 1        | 0.43%   |
| MSI MS-7B85                         | 1        | 0.43%   |
| MSI MS-7B50                         | 1        | 0.43%   |
| MSI MS-7A74                         | 1        | 0.43%   |
| MSI MS-7A34                         | 1        | 0.43%   |
| MSI MS-7A32                         | 1        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 15       | 6.52%   |
| ASUS PRIME           | 12       | 5.22%   |
| ASUS TUF             | 11       | 4.78%   |
| MSI MS-7C37          | 9        | 3.91%   |
| Dell OptiPlex        | 8        | 3.48%   |
| ASUS All             | 6        | 2.61%   |
| ASRock B450          | 6        | 2.61%   |
| Gigabyte B450        | 5        | 2.17%   |
| Gigabyte X570        | 4        | 1.74%   |
| Gigabyte B550M       | 4        | 1.74%   |
| Gigabyte B550        | 4        | 1.74%   |
| ASRock B550M         | 4        | 1.74%   |
| MSI MS-7C91          | 3        | 1.3%    |
| MSI MS-7C02          | 3        | 1.3%    |
| MSI MS-7A38          | 3        | 1.3%    |
| Lenovo ThinkCentre   | 3        | 1.3%    |
| Gigabyte Z390        | 3        | 1.3%    |
| Gigabyte B450M       | 3        | 1.3%    |
| ASRock B450M         | 3        | 1.3%    |
| MSI MS-7C84          | 2        | 0.87%   |
| MSI MS-7B86          | 2        | 0.87%   |
| MSI MS-7850          | 2        | 0.87%   |
| MSI MS-7798          | 2        | 0.87%   |
| Lenovo IdeaCentre    | 2        | 0.87%   |
| HP Z230              | 2        | 0.87%   |
| HP ProDesk           | 2        | 0.87%   |
| HP Pavilion          | 2        | 0.87%   |
| HP EliteDesk         | 2        | 0.87%   |
| Gigabyte Z97X-Gaming | 2        | 0.87%   |
| Gigabyte H110M-S2    | 2        | 0.87%   |
| Fujitsu CELSIUS      | 2        | 0.87%   |
| Biostar G31-M7       | 2        | 0.87%   |
| ASUS STRIX           | 2        | 0.87%   |
| ASUS P8Z77-V         | 2        | 0.87%   |
| ASUS Maximus         | 2        | 0.87%   |
| ASUS K30AD           | 2        | 0.87%   |
| UMAX J42             | 1        | 0.43%   |
| Samsung DeskTop      | 1        | 0.43%   |
| Samsung 500T8A       | 1        | 0.43%   |
| Positivo POS-PIH81DI | 1        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 44       | 19.13%  |
| 2019 | 41       | 17.83%  |
| 2020 | 29       | 12.61%  |
| 2013 | 20       | 8.7%    |
| 2021 | 19       | 8.26%   |
| 2012 | 13       | 5.65%   |
| 2017 | 12       | 5.22%   |
| 2016 | 12       | 5.22%   |
| 2014 | 12       | 5.22%   |
| 2011 | 6        | 2.61%   |
| 2009 | 6        | 2.61%   |
| 2015 | 4        | 1.74%   |
| 2007 | 4        | 1.74%   |
| 2022 | 3        | 1.3%    |
| 2008 | 3        | 1.3%    |
| 2010 | 2        | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 230      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 229      | 99.57%  |
| Enabled  | 1        | 0.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 230      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 90       | 38.63%  |
| 32.01-64.0  | 59       | 25.32%  |
| 8.01-16.0   | 35       | 15.02%  |
| 4.01-8.0    | 14       | 6.01%   |
| 24.01-32.0  | 12       | 5.15%   |
| 64.01-256.0 | 12       | 5.15%   |
| 3.01-4.0    | 10       | 4.29%   |
| 1.01-2.0    | 1        | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 65       | 26.21%  |
| 1.01-2.0   | 52       | 20.97%  |
| 2.01-3.0   | 51       | 20.56%  |
| 3.01-4.0   | 45       | 18.15%  |
| 8.01-16.0  | 25       | 10.08%  |
| 0.51-1.0   | 5        | 2.02%   |
| 16.01-24.0 | 3        | 1.21%   |
| 24.01-32.0 | 2        | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 66       | 27.85%  |
| 3      | 52       | 21.94%  |
| 1      | 46       | 19.41%  |
| 4      | 40       | 16.88%  |
| 5      | 22       | 9.28%   |
| 6      | 5        | 2.11%   |
| 7      | 3        | 1.27%   |
| 9      | 1        | 0.42%   |
| 8      | 1        | 0.42%   |
| 0      | 1        | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 179      | 77.49%  |
| Yes       | 52       | 22.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 229      | 99.57%  |
| No        | 1        | 0.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 119      | 51.29%  |
| No        | 113      | 48.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 53.42%  |
| Yes       | 109      | 46.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 55       | 23.91%  |
| Germany             | 30       | 13.04%  |
| Italy               | 15       | 6.52%   |
| Canada              | 13       | 5.65%   |
| France              | 10       | 4.35%   |
| Poland              | 8        | 3.48%   |
| Netherlands         | 8        | 3.48%   |
| Belgium             | 8        | 3.48%   |
| UK                  | 6        | 2.61%   |
| Russia              | 6        | 2.61%   |
| Austria             | 6        | 2.61%   |
| Brazil              | 5        | 2.17%   |
| Sweden              | 4        | 1.74%   |
| Spain               | 4        | 1.74%   |
| Australia           | 4        | 1.74%   |
| Switzerland         | 3        | 1.3%    |
| Slovenia            | 3        | 1.3%    |
| Mexico              | 3        | 1.3%    |
| India               | 3        | 1.3%    |
| Denmark             | 3        | 1.3%    |
| Argentina           | 3        | 1.3%    |
| Turkey              | 2        | 0.87%   |
| Norway              | 2        | 0.87%   |
| Hungary             | 2        | 0.87%   |
| Hong Kong           | 2        | 0.87%   |
| Finland             | 2        | 0.87%   |
| Czechia             | 2        | 0.87%   |
| Vietnam             | 1        | 0.43%   |
| Trinidad and Tobago | 1        | 0.43%   |
| Sri Lanka           | 1        | 0.43%   |
| South Korea         | 1        | 0.43%   |
| South Africa        | 1        | 0.43%   |
| Singapore           | 1        | 0.43%   |
| Serbia              | 1        | 0.43%   |
| Saudi Arabia        | 1        | 0.43%   |
| Portugal            | 1        | 0.43%   |
| Malaysia            | 1        | 0.43%   |
| Lithuania           | 1        | 0.43%   |
| Jordan              | 1        | 0.43%   |
| Guatemala           | 1        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 5        | 2.05%   |
| Leipzig           | 4        | 1.64%   |
| Turin             | 3        | 1.23%   |
| St Petersburg     | 3        | 1.23%   |
| Ottawa            | 3        | 1.23%   |
| Montreal          | 3        | 1.23%   |
| Zurich            | 2        | 0.82%   |
| Wroclaw           | 2        | 0.82%   |
| Warsaw            | 2        | 0.82%   |
| Tuen Mun          | 2        | 0.82%   |
| Toronto           | 2        | 0.82%   |
| Snohomish         | 2        | 0.82%   |
| Schiedam          | 2        | 0.82%   |
| Porth             | 2        | 0.82%   |
| North Little Rock | 2        | 0.82%   |
| Ljubljana         | 2        | 0.82%   |
| Istanbul          | 2        | 0.82%   |
| Houston           | 2        | 0.82%   |
| Hamburg           | 2        | 0.82%   |
| Geesteren         | 2        | 0.82%   |
| Barbentane        | 2        | 0.82%   |
| Amsterdam         | 2        | 0.82%   |
| Zuidlaren         | 1        | 0.41%   |
| Zapopan           | 1        | 0.41%   |
| Wimauma           | 1        | 0.41%   |
| Whiteville        | 1        | 0.41%   |
| Weybridge         | 1        | 0.41%   |
| Westminster       | 1        | 0.41%   |
| West Haddon       | 1        | 0.41%   |
| Wasmes            | 1        | 0.41%   |
| Virar             | 1        | 0.41%   |
| Vilnius           | 1        | 0.41%   |
| Villanova         | 1        | 0.41%   |
| Villa Ballester   | 1        | 0.41%   |
| Vienna            | 1        | 0.41%   |
| Vicar             | 1        | 0.41%   |
| Union             | 1        | 0.41%   |
| Tubbergen         | 1        | 0.41%   |
| Toledo            | 1        | 0.41%   |
| The Colony        | 1        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 99       | 172    | 19.22%  |
| WDC                       | 93       | 155    | 18.06%  |
| Seagate                   | 85       | 125    | 16.5%   |
| Kingston                  | 39       | 64     | 7.57%   |
| Crucial                   | 31       | 51     | 6.02%   |
| Toshiba                   | 21       | 28     | 4.08%   |
| SanDisk                   | 20       | 26     | 3.88%   |
| Hitachi                   | 12       | 13     | 2.33%   |
| Phison                    | 11       | 12     | 2.14%   |
| Intel                     | 8        | 10     | 1.55%   |
| Corsair                   | 7        | 7      | 1.36%   |
| A-DATA Technology         | 6        | 12     | 1.17%   |
| SPCC                      | 5        | 5      | 0.97%   |
| Micron Technology         | 5        | 7      | 0.97%   |
| XPG                       | 4        | 4      | 0.78%   |
| PNY                       | 4        | 4      | 0.78%   |
| Intenso                   | 4        | 5      | 0.78%   |
| China                     | 4        | 4      | 0.78%   |
| Unknown                   | 3        | 4      | 0.58%   |
| OCZ                       | 3        | 3      | 0.58%   |
| Micron/Crucial Technology | 3        | 4      | 0.58%   |
| Gigabyte Technology       | 3        | 4      | 0.58%   |
| Transcend                 | 2        | 3      | 0.39%   |
| SK hynix                  | 2        | 2      | 0.39%   |
| SABRENT                   | 2        | 3      | 0.39%   |
| Plextor                   | 2        | 3      | 0.39%   |
| Phison Electronics        | 2        | 2      | 0.39%   |
| Lexar                     | 2        | 2      | 0.39%   |
| Leven                     | 2        | 3      | 0.39%   |
| JMicron Technology        | 2        | 2      | 0.39%   |
| HGST                      | 2        | 2      | 0.39%   |
| ASMT                      | 2        | 4      | 0.39%   |
| USB3.1                    | 1        | 1      | 0.19%   |
| UMAX                      | 1        | 1      | 0.19%   |
| Timetec                   | 1        | 2      | 0.19%   |
| T-FORCE                   | 1        | 1      | 0.19%   |
| Realtek Semiconductor     | 1        | 1      | 0.19%   |
| Realtek                   | 1        | 1      | 0.19%   |
| Pioneer                   | 1        | 3      | 0.19%   |
| PI-041                    | 1        | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB   | 18       | 2.88%   |
| Samsung SSD 860 EVO 1TB          | 11       | 1.76%   |
| Kingston SA400S37120G 120GB SSD  | 10       | 1.6%    |
| Crucial CT500MX500SSD1 500GB     | 10       | 1.6%    |
| WDC WD10EZEX-08WN4A0 1TB         | 9        | 1.44%   |
| Seagate ST4000DM004-2CV104 4TB   | 8        | 1.28%   |
| Samsung SSD 860 EVO 500GB        | 8        | 1.28%   |
| Samsung SSD 850 EVO 250GB        | 8        | 1.28%   |
| Samsung SSD 850 EVO 500GB        | 7        | 1.12%   |
| WDC WD10EZEX-00BN5A0 1TB         | 6        | 0.96%   |
| Seagate ST2000DM006-2DM164 2TB   | 6        | 0.96%   |
| Seagate ST1000DM010-2EP102 1TB   | 6        | 0.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 5        | 0.8%    |
| Samsung SSD 870 QVO 1TB          | 5        | 0.8%    |
| Seagate Expansion Desk 8TB       | 4        | 0.64%   |
| Samsung SSD 980 500GB            | 4        | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB   | 4        | 0.64%   |
| Samsung SSD 970 EVO 500GB        | 4        | 0.64%   |
| Samsung SSD 860 EVO 250GB        | 4        | 0.64%   |
| Samsung NVMe SSD Drive 250GB     | 4        | 0.64%   |
| Samsung NVMe SSD Drive 1TB       | 4        | 0.64%   |
| Kingston SA400S37480G 480GB SSD  | 4        | 0.64%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 0.64%   |
| Kingston NVMe SSD Drive 1TB      | 4        | 0.64%   |
| Crucial CT240BX500SSD1 240GB     | 4        | 0.64%   |
| Crucial CT1000MX500SSD1 1TB      | 4        | 0.64%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 3        | 0.48%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 3        | 0.48%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 3        | 0.48%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 3        | 0.48%   |
| WDC WD20EARS-42S0XB0 2TB         | 3        | 0.48%   |
| WDC WD10EZEX-22MFCA0 1TB         | 3        | 0.48%   |
| WDC WD10EZEX-00RKKA0 1TB         | 3        | 0.48%   |
| Toshiba HDWD110 1TB              | 3        | 0.48%   |
| Toshiba DT01ACA050 500GB         | 3        | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB   | 3        | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.48%   |
| SanDisk SSD PLUS 240GB           | 3        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB     | 3        | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 84       | 124    | 40.58%  |
| WDC                 | 72       | 108    | 34.78%  |
| Toshiba             | 17       | 20     | 8.21%   |
| Hitachi             | 12       | 13     | 5.8%    |
| Samsung Electronics | 8        | 17     | 3.86%   |
| Unknown             | 2        | 2      | 0.97%   |
| SABRENT             | 2        | 3      | 0.97%   |
| HGST                | 2        | 2      | 0.97%   |
| ASMT                | 2        | 4      | 0.97%   |
| PI-041              | 1        | 1      | 0.48%   |
| Maxtor              | 1        | 1      | 0.48%   |
| Maxone              | 1        | 1      | 0.48%   |
| JMicron Technology  | 1        | 1      | 0.48%   |
| HPE                 | 1        | 1      | 0.48%   |
| ASMedia             | 1        | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 69       | 98     | 32.55%  |
| Kingston            | 28       | 48     | 13.21%  |
| Crucial             | 27       | 39     | 12.74%  |
| WDC                 | 19       | 26     | 8.96%   |
| SanDisk             | 13       | 18     | 6.13%   |
| Micron Technology   | 5        | 7      | 2.36%   |
| Toshiba             | 4        | 6      | 1.89%   |
| Intenso             | 4        | 5      | 1.89%   |
| Intel               | 4        | 5      | 1.89%   |
| China               | 4        | 4      | 1.89%   |
| SPCC                | 3        | 3      | 1.42%   |
| PNY                 | 3        | 3      | 1.42%   |
| OCZ                 | 3        | 3      | 1.42%   |
| Corsair             | 3        | 3      | 1.42%   |
| Phison              | 2        | 2      | 0.94%   |
| Leven               | 2        | 3      | 0.94%   |
| Gigabyte Technology | 2        | 2      | 0.94%   |
| A-DATA Technology   | 2        | 2      | 0.94%   |
| UMAX                | 1        | 1      | 0.47%   |
| Transcend           | 1        | 1      | 0.47%   |
| Timetec             | 1        | 2      | 0.47%   |
| Plextor             | 1        | 2      | 0.47%   |
| Pioneer             | 1        | 3      | 0.47%   |
| Patriot             | 1        | 2      | 0.47%   |
| NGFF                | 1        | 1      | 0.47%   |
| Mushkin             | 1        | 1      | 0.47%   |
| LITEONIT            | 1        | 1      | 0.47%   |
| Lexar               | 1        | 1      | 0.47%   |
| LDLC                | 1        | 1      | 0.47%   |
| Kingmax             | 1        | 2      | 0.47%   |
| Imation             | 1        | 1      | 0.47%   |
| Hewlett-Packard     | 1        | 1      | 0.47%   |
| Drevo               | 1        | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 155      | 299    | 36.82%  |
| SSD     | 154      | 298    | 36.58%  |
| NVMe    | 108      | 173    | 25.65%  |
| Unknown | 4        | 5      | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 206      | 569    | 60.77%  |
| NVMe | 107      | 171    | 31.56%  |
| SAS  | 26       | 35     | 7.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 142      | 288    | 39.12%  |
| 0.51-1.0   | 110      | 162    | 30.3%   |
| 1.01-2.0   | 59       | 79     | 16.25%  |
| 3.01-4.0   | 24       | 37     | 6.61%   |
| 2.01-3.0   | 13       | 14     | 3.58%   |
| 4.01-10.0  | 12       | 14     | 3.31%   |
| 10.01-20.0 | 3        | 3      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 56       | 23.53%  |
| More than 3000 | 44       | 18.49%  |
| 501-1000       | 33       | 13.87%  |
| 251-500        | 26       | 10.92%  |
| 2001-3000      | 26       | 10.92%  |
| 101-250        | 26       | 10.92%  |
| Unknown        | 16       | 6.72%   |
| 51-100         | 5        | 2.1%    |
| 1-20           | 4        | 1.68%   |
| 21-50          | 2        | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 37       | 14.8%   |
| 1001-2000      | 35       | 14%     |
| 101-250        | 33       | 13.2%   |
| 1-20           | 32       | 12.8%   |
| 251-500        | 31       | 12.4%   |
| 51-100         | 24       | 9.6%    |
| 21-50          | 19       | 7.6%    |
| Unknown        | 16       | 6.4%    |
| More than 3000 | 14       | 5.6%    |
| 2001-3000      | 9        | 3.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Desktops | Drives | Percent |
|-----------------------------------------------------------------|----------|--------|---------|
| XPG GAMMIX S11 480GB                                            | 1        | 1      | 3.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1        | 1      | 3.23%   |
| WDC WD5000AZRX-00A8LB0 500GB                                    | 1        | 1      | 3.23%   |
| WDC WD40EFRX-68WT0N0 4TB                                        | 1        | 2      | 3.23%   |
| WDC WD20EARX-00PASB0 2TB                                        | 1        | 1      | 3.23%   |
| WDC WD2003FZEX-00Z4SA0 2TB                                      | 1        | 1      | 3.23%   |
| WDC WD2002FYPS-01U1B0 2TB                                       | 1        | 1      | 3.23%   |
| WDC WD10EACS-00D6B1 1TB                                         | 1        | 1      | 3.23%   |
| Toshiba DT01ACA100 1TB                                          | 1        | 1      | 3.23%   |
| Seagate ST9320325AS 320GB                                       | 1        | 4      | 3.23%   |
| Seagate ST6000VX0023-2EF110 6TB                                 | 1        | 1      | 3.23%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 1        | 1      | 3.23%   |
| Seagate ST3320620AS 320GB                                       | 1        | 1      | 3.23%   |
| Seagate ST2000DX002-2DV164 2TB                                  | 1        | 1      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 1        | 2      | 3.23%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 1        | 2      | 3.23%   |
| Samsung Electronics SSD 970 EVO 500GB                           | 1        | 1      | 3.23%   |
| Samsung Electronics SSD 960 EVO 500GB                           | 1        | 1      | 3.23%   |
| Samsung Electronics SSD 840 Series 120GB                        | 1        | 1      | 3.23%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 500GB | 1        | 1      | 3.23%   |
| Samsung Electronics HD103SI 1TB                                 | 1        | 1      | 3.23%   |
| OCZ VERTEX3 240GB SSD                                           | 1        | 1      | 3.23%   |
| Kingston SV300S37A120G 120GB SSD                                | 1        | 1      | 3.23%   |
| Hitachi HTS547575A9E384 752GB                                   | 1        | 1      | 3.23%   |
| Hitachi HTS545050A7E380 500GB                                   | 1        | 1      | 3.23%   |
| Hitachi HDT725025VLA380 250GB                                   | 1        | 1      | 3.23%   |
| Drevo X1 SSD 64GB                                               | 1        | 1      | 3.23%   |
| Crucial CT500MX500SSD1 500GB                                    | 1        | 5      | 3.23%   |
| Crucial CT1050MX300SSD1 1050GB                                  | 1        | 1      | 3.23%   |
| Corsair Force LS SSD 120GB                                      | 1        | 1      | 3.23%   |
| ASMT ASM1156-PM 4TB                                             | 1        | 2      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 23.33%  |
| Seagate             | 6        | 12     | 20%     |
| Samsung Electronics | 5        | 5      | 16.67%  |
| Hitachi             | 3        | 3      | 10%     |
| Crucial             | 2        | 6      | 6.67%   |
| XPG                 | 1        | 1      | 3.33%   |
| Toshiba             | 1        | 1      | 3.33%   |
| OCZ                 | 1        | 1      | 3.33%   |
| Kingston            | 1        | 1      | 3.33%   |
| Drevo               | 1        | 1      | 3.33%   |
| Corsair             | 1        | 1      | 3.33%   |
| ASMT                | 1        | 2      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 33.33%  |
| Seagate             | 6        | 12     | 33.33%  |
| Hitachi             | 3        | 3      | 16.67%  |
| Toshiba             | 1        | 1      | 5.56%   |
| Samsung Electronics | 1        | 1      | 5.56%   |
| ASMT                | 1        | 2      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 26     | 62.07%  |
| SSD  | 7        | 12     | 24.14%  |
| NVMe | 4        | 4      | 13.79%  |

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
| Works    | 156      | 467    | 56.73%  |
| Detected | 89       | 264    | 32.36%  |
| Malfunc  | 28       | 42     | 10.18%  |
| Failed   | 2        | 2      | 0.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 119      | 30.51%  |
| AMD                            | 107      | 27.44%  |
| Samsung Electronics            | 43       | 11.03%  |
| SanDisk                        | 24       | 6.15%   |
| ASMedia Technology             | 23       | 5.9%    |
| Phison Electronics             | 18       | 4.62%   |
| Kingston Technology Company    | 12       | 3.08%   |
| Micron/Crucial Technology      | 7        | 1.79%   |
| Marvell Technology Group       | 6        | 1.54%   |
| Realtek Semiconductor          | 5        | 1.28%   |
| JMicron Technology             | 5        | 1.28%   |
| ADATA Technology               | 4        | 1.03%   |
| Silicon Motion                 | 3        | 0.77%   |
| Nvidia                         | 3        | 0.77%   |
| Toshiba America Info Systems   | 2        | 0.51%   |
| SK hynix                       | 2        | 0.51%   |
| Transcend                      | 1        | 0.26%   |
| Solid State Storage Technology | 1        | 0.26%   |
| Seagate Technology             | 1        | 0.26%   |
| Micron Technology              | 1        | 0.26%   |
| LSI Logic / Symbios Logic      | 1        | 0.26%   |
| KIOXIA                         | 1        | 0.26%   |
| Broadcom / LSI                 | 1        | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 68       | 15.04%  |
| AMD 400 Series Chipset SATA Controller                                         | 38       | 8.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 23       | 5.09%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 23       | 5.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22       | 4.87%   |
| AMD 500 Series Chipset SATA Controller                                         | 19       | 4.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12       | 2.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 11       | 2.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 11       | 2.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 10       | 2.21%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9        | 1.99%   |
| Samsung NVMe SSD Controller 980                                                | 8        | 1.77%   |
| Phison E12 NVMe Controller                                                     | 8        | 1.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7        | 1.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7        | 1.55%   |
| Phison E16 PCIe4 NVMe Controller                                               | 7        | 1.55%   |
| Intel SATA Controller [RAID mode]                                              | 7        | 1.55%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 6        | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6        | 1.33%   |
| Kingston Company A2000 NVMe SSD                                                | 6        | 1.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6        | 1.33%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5        | 1.11%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5        | 1.11%   |
| AMD FCH SATA Controller D                                                      | 5        | 1.11%   |
| Realtek Realtek Non-Volatile memory controller                                 | 4        | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4        | 0.88%   |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 0.66%   |
| Kingston Company KC2000 NVMe SSD                                               | 3        | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                             | 3        | 0.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 0.66%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 0.66%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 0.66%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3        | 0.66%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 0.66%   |
| AMD X370 Series Chipset SATA Controller                                        | 3        | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 0.66%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2        | 0.44%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                        | 2        | 0.44%   |
| Nvidia MCP73 IDE Controller                                                    | 2        | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 209      | 60.23%  |
| NVMe | 107      | 30.84%  |
| IDE  | 19       | 5.48%   |
| RAID | 10       | 2.88%   |
| SAS  | 2        | 0.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 121      | 52.61%  |
| AMD    | 109      | 47.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 13       | 5.65%   |
| AMD Ryzen 5 3600 6-Core Processor           | 13       | 5.65%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 10       | 4.35%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 3.91%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 7        | 3.04%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 5        | 2.17%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 2.17%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 1.74%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 1.74%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 1.74%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 1.74%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 1.74%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 1.74%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.3%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.3%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 1.3%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 1.3%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.3%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 0.87%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.87%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.87%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.87%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.87%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.87%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 2        | 0.87%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.87%   |
| Intel 12th Gen Core i5-12600K               | 2        | 0.87%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 0.87%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 0.87%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 0.87%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 2        | 0.87%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2        | 0.87%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 0.87%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 0.87%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.43%   |
| Intel Xeon CPU W5580 @ 3.20GHz              | 1        | 0.43%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.43%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1        | 0.43%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 48       | 20.87%  |
| Intel Core i5           | 44       | 19.13%  |
| Intel Core i7           | 34       | 14.78%  |
| AMD Ryzen 7             | 29       | 12.61%  |
| AMD Ryzen 9             | 17       | 7.39%   |
| Intel Xeon              | 10       | 4.35%   |
| Other                   | 7        | 3.04%   |
| Intel Core i3           | 7        | 3.04%   |
| AMD Ryzen 3             | 5        | 2.17%   |
| Intel Celeron           | 4        | 1.74%   |
| Intel Core 2 Quad       | 3        | 1.3%    |
| Intel Core 2 Duo        | 3        | 1.3%    |
| AMD Ryzen Threadripper  | 3        | 1.3%    |
| AMD FX                  | 3        | 1.3%    |
| Intel Pentium           | 2        | 0.87%   |
| Intel Core i9           | 2        | 0.87%   |
| Intel Pentium Gold      | 1        | 0.43%   |
| Intel Pentium Dual-Core | 1        | 0.43%   |
| Intel Pentium Dual      | 1        | 0.43%   |
| Intel Core m3           | 1        | 0.43%   |
| Intel Core 2            | 1        | 0.43%   |
| AMD Phenom II X4        | 1        | 0.43%   |
| AMD Athlon X4           | 1        | 0.43%   |
| AMD Athlon II X4        | 1        | 0.43%   |
| AMD A8                  | 1        | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 84       | 36.36%  |
| 6      | 63       | 27.27%  |
| 8      | 36       | 15.58%  |
| 2      | 20       | 8.66%   |
| 12     | 17       | 7.36%   |
| 16     | 5        | 2.16%   |
| 10     | 3        | 1.3%    |
| 3      | 2        | 0.87%   |
| 32     | 1        | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 227      | 98.27%  |
| 2      | 4        | 1.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 165      | 71.74%  |
| 1      | 65       | 28.26%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 230      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 89       | 37.87%  |
| 0x08701021 | 24       | 10.21%  |
| 0x306c3    | 18       | 7.66%   |
| 0x0a201009 | 9        | 3.83%   |
| 0x506e3    | 8        | 3.4%    |
| 0x08701013 | 8        | 3.4%    |
| 0x306a9    | 7        | 2.98%   |
| 0x906ea    | 6        | 2.55%   |
| 0x906e9    | 6        | 2.55%   |
| 0x0a50000c | 5        | 2.13%   |
| 0x0a201016 | 5        | 2.13%   |
| 0x0800820d | 4        | 1.7%    |
| 0xa0655    | 3        | 1.28%   |
| 0x106a5    | 3        | 1.28%   |
| 0x08108109 | 3        | 1.28%   |
| 0x08001138 | 3        | 1.28%   |
| 0x08001137 | 3        | 1.28%   |
| 0xa0671    | 2        | 0.85%   |
| 0xa0653    | 2        | 0.85%   |
| 0x906ec    | 2        | 0.85%   |
| 0x6fd      | 2        | 0.85%   |
| 0x306f2    | 2        | 0.85%   |
| 0x106e5    | 2        | 0.85%   |
| 0x08101016 | 2        | 0.85%   |
| 0x906ed    | 1        | 0.43%   |
| 0x906eb    | 1        | 0.43%   |
| 0x90672    | 1        | 0.43%   |
| 0x706a8    | 1        | 0.43%   |
| 0x6fb      | 1        | 0.43%   |
| 0x6f6      | 1        | 0.43%   |
| 0x6f2      | 1        | 0.43%   |
| 0x406c4    | 1        | 0.43%   |
| 0x206c2    | 1        | 0.43%   |
| 0x206a7    | 1        | 0.43%   |
| 0x20652    | 1        | 0.43%   |
| 0x1067a    | 1        | 0.43%   |
| 0x0a50000b | 1        | 0.43%   |
| 0x0a20120a | 1        | 0.43%   |
| 0x08600103 | 1        | 0.43%   |
| 0x06000852 | 1        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 47       | 20.35%  |
| Haswell          | 31       | 13.42%  |
| Zen 3            | 30       | 12.99%  |
| KabyLake         | 26       | 11.26%  |
| Zen+             | 13       | 5.63%   |
| Skylake          | 13       | 5.63%   |
| Zen              | 12       | 5.19%   |
| IvyBridge        | 12       | 5.19%   |
| CometLake        | 8        | 3.46%   |
| Core             | 7        | 3.03%   |
| Unknown          | 6        | 2.6%    |
| Nehalem          | 5        | 2.16%   |
| SandyBridge      | 4        | 1.73%   |
| Penryn           | 3        | 1.3%    |
| Westmere         | 2        | 0.87%   |
| Piledriver       | 2        | 0.87%   |
| Icelake          | 2        | 0.87%   |
| Steamroller      | 1        | 0.43%   |
| Silvermont       | 1        | 0.43%   |
| K10 Llano        | 1        | 0.43%   |
| K10              | 1        | 0.43%   |
| Goldmont plus    | 1        | 0.43%   |
| Excavator        | 1        | 0.43%   |
| Bulldozer        | 1        | 0.43%   |
| Alderlake Hybrid | 1        | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 117      | 46.43%  |
| AMD    | 93       | 36.9%   |
| Intel  | 42       | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 25       | 9.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15       | 5.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 3.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9        | 3.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 3.13%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 8        | 3.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 3.13%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 8        | 3.13%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 2.73%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 6        | 2.34%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 2.34%   |
| AMD Cezanne                                                                 | 6        | 2.34%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 5        | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 1.95%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.95%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 1.56%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 1.56%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 4        | 1.56%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 1.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.17%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 1.17%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 1.17%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 3        | 1.17%   |
| Intel HD Graphics 630                                                       | 3        | 1.17%   |
| Intel HD Graphics 530                                                       | 3        | 1.17%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 1.17%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.17%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.78%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.78%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.78%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 0.78%   |
| Intel AlderLake-S GT1                                                       | 2        | 0.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 0.78%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 2        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 106      | 45.3%   |
| 1 x AMD        | 80       | 34.19%  |
| 1 x Intel      | 28       | 11.97%  |
| AMD + Nvidia   | 6        | 2.56%   |
| Intel + AMD    | 5        | 2.14%   |
| 2 x AMD        | 4        | 1.71%   |
| Intel + Nvidia | 4        | 1.71%   |
| 2 x Nvidia     | 1        | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 131      | 56.96%  |
| Proprietary | 99       | 43.04%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 76       | 32.2%   |
| 7.01-8.0   | 47       | 19.92%  |
| 3.01-4.0   | 30       | 12.71%  |
| 1.01-2.0   | 24       | 10.17%  |
| 5.01-6.0   | 20       | 8.47%   |
| 8.01-16.0  | 18       | 7.63%   |
| 0.51-1.0   | 10       | 4.24%   |
| 0.01-0.5   | 9        | 3.81%   |
| 2.01-3.0   | 1        | 0.42%   |
| 16.01-24.0 | 1        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 54       | 18.06%  |
| Dell                 | 32       | 10.7%   |
| Goldstar             | 27       | 9.03%   |
| Acer                 | 23       | 7.69%   |
| AOC                  | 22       | 7.36%   |
| Ancor Communications | 20       | 6.69%   |
| BenQ                 | 19       | 6.35%   |
| Hewlett-Packard      | 12       | 4.01%   |
| ASUSTek Computer     | 11       | 3.68%   |
| Iiyama               | 7        | 2.34%   |
| Vizio                | 6        | 2.01%   |
| Lenovo               | 6        | 2.01%   |
| ViewSonic            | 5        | 1.67%   |
| Philips              | 5        | 1.67%   |
| Gigabyte Technology  | 4        | 1.34%   |
| LG Electronics       | 3        | 1%      |
| Fujitsu Siemens      | 3        | 1%      |
| Eizo                 | 3        | 1%      |
| Valve                | 2        | 0.67%   |
| Sony                 | 2        | 0.67%   |
| Lenovo Group Limited | 2        | 0.67%   |
| VOXICON              | 1        | 0.33%   |
| Unknown (XXX)        | 1        | 0.33%   |
| Unknown              | 1        | 0.33%   |
| UGD                  | 1        | 0.33%   |
| Sceptre Tech         | 1        | 0.33%   |
| SAC                  | 1        | 0.33%   |
| RTK                  | 1        | 0.33%   |
| RS                   | 1        | 0.33%   |
| Planar               | 1        | 0.33%   |
| Pixio                | 1        | 0.33%   |
| Panasonic            | 1        | 0.33%   |
| Orion                | 1        | 0.33%   |
| NEC Computers        | 1        | 0.33%   |
| MSI                  | 1        | 0.33%   |
| Mi                   | 1        | 0.33%   |
| Insignia             | 1        | 0.33%   |
| Idek Iiyama          | 1        | 0.33%   |
| Hyundai ImageQuest   | 1        | 0.33%   |
| HVR                  | 1        | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch   | 4        | 1.27%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch              | 4        | 1.27%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                    | 4        | 1.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch   | 3        | 0.95%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch   | 3        | 0.95%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 3        | 0.95%   |
| AOC 24G1WG3 AOC2401 1920x1080 521x293mm 23.5-inch                   | 3        | 0.95%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch    | 3        | 0.95%   |
| Valve Index HMD VLV91A8                                             | 2        | 0.63%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch | 2        | 0.63%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 530x300mm 24.0-inch   | 2        | 0.63%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch   | 2        | 0.63%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch            | 2        | 0.63%   |
| Iiyama PL2792Q IVM6637 2560x1440 600x340mm 27.2-inch                | 2        | 0.63%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch            | 2        | 0.63%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch      | 2        | 0.63%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch      | 2        | 0.63%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                   | 2        | 0.63%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                 | 2        | 0.63%   |
| BenQ RL2455 BNQ7F1C 1920x1080 530x300mm 24.0-inch                   | 2        | 0.63%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                   | 2        | 0.63%   |
| BenQ G2450H BNQ78AB 1920x1080 531x298mm 24.0-inch                   | 2        | 0.63%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                  | 2        | 0.63%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                  | 2        | 0.63%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch        | 2        | 0.63%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                   | 2        | 0.63%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch    | 2        | 0.63%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch    | 2        | 0.63%   |
| Acer XB270HU ACR0408 2560x1440 598x336mm 27.0-inch                  | 2        | 0.63%   |
| Acer R251 ACR0505 1920x1080 553x309mm 24.9-inch                     | 2        | 0.63%   |
| VOXICON D32QO DUS3200 2560x1440 708x398mm 32.0-inch                 | 1        | 0.32%   |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                 | 1        | 0.32%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                  | 1        | 0.32%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                   | 1        | 0.32%   |
| Vizio E240AR VIZ0089 1360x768 477x268mm 21.5-inch                   | 1        | 0.32%   |
| Vizio D55x-G1 VIZ1033 3840x2160                                     | 1        | 0.32%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                 | 1        | 0.32%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch       | 1        | 0.32%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch              | 1        | 0.32%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch       | 1        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 128      | 44.91%  |
| 2560x1440 (QHD)    | 42       | 14.74%  |
| 3840x2160 (4K)     | 35       | 12.28%  |
| 1280x1024 (SXGA)   | 11       | 3.86%   |
| 1920x1200 (WUXGA)  | 10       | 3.51%   |
| 1680x1050 (WSXGA+) | 8        | 2.81%   |
| Unknown            | 8        | 2.81%   |
| 1600x900 (HD+)     | 7        | 2.46%   |
| 3440x1440          | 5        | 1.75%   |
| 2560x1080          | 5        | 1.75%   |
| 1440x900 (WXGA+)   | 4        | 1.4%    |
| 1366x768 (WXGA)    | 4        | 1.4%    |
| 1360x768           | 3        | 1.05%   |
| 3840x1600          | 2        | 0.7%    |
| 3840x1080          | 2        | 0.7%    |
| 1920x540           | 2        | 0.7%    |
| 9840x3840          | 1        | 0.35%   |
| 4480x1440          | 1        | 0.35%   |
| 3840x1200          | 1        | 0.35%   |
| 3520x1080          | 1        | 0.35%   |
| 3200x1080          | 1        | 0.35%   |
| 2880x1700          | 1        | 0.35%   |
| 2560x1600          | 1        | 0.35%   |
| 1600x1200          | 1        | 0.35%   |
| 1024x768 (XGA)     | 1        | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 66       | 22.45%  |
| 27      | 61       | 20.75%  |
| 23      | 29       | 9.86%   |
| 21      | 23       | 7.82%   |
| Unknown | 21       | 7.14%   |
| 31      | 16       | 5.44%   |
| 34      | 13       | 4.42%   |
| 19      | 11       | 3.74%   |
| 22      | 10       | 3.4%    |
| 20      | 5        | 1.7%    |
| 18      | 5        | 1.7%    |
| 54      | 4        | 1.36%   |
| 32      | 4        | 1.36%   |
| 17      | 4        | 1.36%   |
| 84      | 3        | 1.02%   |
| 72      | 2        | 0.68%   |
| 49      | 2        | 0.68%   |
| 37      | 2        | 0.68%   |
| 74      | 1        | 0.34%   |
| 69      | 1        | 0.34%   |
| 60      | 1        | 0.34%   |
| 52      | 1        | 0.34%   |
| 48      | 1        | 0.34%   |
| 46      | 1        | 0.34%   |
| 42      | 1        | 0.34%   |
| 33      | 1        | 0.34%   |
| 28      | 1        | 0.34%   |
| 16      | 1        | 0.34%   |
| 15      | 1        | 0.34%   |
| 13      | 1        | 0.34%   |
| 10      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 133      | 48.19%  |
| 401-500     | 47       | 17.03%  |
| 601-700     | 24       | 8.7%    |
| Unknown     | 21       | 7.61%   |
| 701-800     | 18       | 6.52%   |
| 1001-1500   | 10       | 3.62%   |
| 1501-2000   | 7        | 2.54%   |
| 301-350     | 6        | 2.17%   |
| 351-400     | 5        | 1.81%   |
| 801-900     | 2        | 0.72%   |
| 201-300     | 2        | 0.72%   |
| 901-1000    | 1        | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 180      | 70.31%  |
| 16/10   | 31       | 12.11%  |
| Unknown | 18       | 7.03%   |
| 21/9    | 12       | 4.69%   |
| 5/4     | 8        | 3.13%   |
| 32/9    | 3        | 1.17%   |
| 6/5     | 2        | 0.78%   |
| 4/3     | 2        | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 96       | 33.92%  |
| 301-350        | 61       | 21.55%  |
| 351-500        | 32       | 11.31%  |
| 251-300        | 22       | 7.77%   |
| Unknown        | 21       | 7.42%   |
| 151-200        | 17       | 6.01%   |
| More than 1000 | 14       | 4.95%   |
| 141-150        | 8        | 2.83%   |
| 501-1000       | 8        | 2.83%   |
| 71-80          | 1        | 0.35%   |
| 41-50          | 1        | 0.35%   |
| 131-140        | 1        | 0.35%   |
| 111-120        | 1        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 154      | 59.92%  |
| 101-120       | 52       | 20.23%  |
| Unknown       | 21       | 8.17%   |
| 1-50          | 12       | 4.67%   |
| 121-160       | 9        | 3.5%    |
| 161-240       | 8        | 3.11%   |
| More than 240 | 1        | 0.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 157      | 67.38%  |
| 2     | 62       | 26.61%  |
| 3     | 12       | 5.15%   |
| 4     | 2        | 0.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 155      | 45.86%  |
| Intel                                 | 110      | 32.54%  |
| Qualcomm Atheros                      | 15       | 4.44%   |
| Broadcom                              | 9        | 2.66%   |
| Microsoft                             | 8        | 2.37%   |
| TP-Link                               | 5        | 1.48%   |
| Ralink Technology                     | 5        | 1.48%   |
| ASIX Electronics                      | 5        | 1.48%   |
| Ralink                                | 3        | 0.89%   |
| Aquantia                              | 3        | 0.89%   |
| Xiaomi                                | 2        | 0.59%   |
| Nvidia                                | 2        | 0.59%   |
| Microchip Technology                  | 2        | 0.59%   |
| Wilocity                              | 1        | 0.3%    |
| Samsung Electronics                   | 1        | 0.3%    |
| Qualcomm Atheros Communications       | 1        | 0.3%    |
| OPPO Electronics                      | 1        | 0.3%    |
| NetGear                               | 1        | 0.3%    |
| Motorola PCS                          | 1        | 0.3%    |
| MediaTek                              | 1        | 0.3%    |
| InterBiometrics                       | 1        | 0.3%    |
| Huawei Technologies                   | 1        | 0.3%    |
| Exar                                  | 1        | 0.3%    |
| Edimax Technology                     | 1        | 0.3%    |
| D-Link                                | 1        | 0.3%    |
| Broadcom Limited                      | 1        | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 114      | 28.36%  |
| Realtek RTL8125 2.5GbE Controller                                 | 29       | 7.21%   |
| Intel Wi-Fi 6 AX200                                               | 27       | 6.72%   |
| Intel I211 Gigabit Network Connection                             | 27       | 6.72%   |
| Intel Ethernet Connection (2) I219-V                              | 12       | 2.99%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 2.24%   |
| Intel Wireless-AC 9260                                            | 8        | 1.99%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 1.99%   |
| Intel Ethernet Controller I225-V                                  | 7        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 1.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 1.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 1%      |
| Intel Ethernet Connection I217-V                                  | 4        | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 1%      |
| ASIX AX88179 Gigabit Ethernet                                     | 4        | 1%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 0.75%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 3        | 0.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 0.75%   |
| Realtek 802.11ac NIC                                              | 3        | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3        | 0.75%   |
| Microsoft XBOX ACC                                                | 3        | 0.75%   |
| Microsoft Wireless XBox Controller Dongle                         | 3        | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3        | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 0.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 0.75%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.5%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 0.5%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                              | 2        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.5%    |
| Microsoft Xbox 360 Wireless Adapter                               | 2        | 0.5%    |
| Intel Wireless 8260                                               | 2        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 62       | 47.33%  |
| Realtek Semiconductor                 | 27       | 20.61%  |
| Qualcomm Atheros                      | 8        | 6.11%   |
| Microsoft                             | 8        | 6.11%   |
| Broadcom                              | 7        | 5.34%   |
| Ralink Technology                     | 5        | 3.82%   |
| TP-Link                               | 4        | 3.05%   |
| Ralink                                | 3        | 2.29%   |
| Wilocity                              | 1        | 0.76%   |
| Qualcomm Atheros Communications       | 1        | 0.76%   |
| NetGear                               | 1        | 0.76%   |
| MediaTek                              | 1        | 0.76%   |
| Edimax Technology                     | 1        | 0.76%   |
| D-Link                                | 1        | 0.76%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 27       | 20.45%  |
| Intel Wireless-AC 9260                                              | 8        | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 5        | 3.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 5        | 3.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 4        | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 4        | 3.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 3        | 2.27%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 3        | 2.27%   |
| Realtek 802.11ac NIC                                                | 3        | 2.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 3        | 2.27%   |
| Microsoft XBOX ACC                                                  | 3        | 2.27%   |
| Microsoft Wireless XBox Controller Dongle                           | 3        | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3        | 2.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 3        | 2.27%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 3        | 2.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 1.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 2        | 1.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2        | 1.52%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 2        | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 1.52%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 1.52%   |
| Intel Wireless 8260                                                 | 2        | 1.52%   |
| Intel Wireless 7265                                                 | 2        | 1.52%   |
| Intel Wireless 3165                                                 | 2        | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 2        | 1.52%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 0.76%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 1        | 0.76%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.76%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 0.76%   |
| Realtek 802.11n WLAN Adapter                                        | 1        | 0.76%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 0.76%   |
| Ralink RT2870 Wireless Adapter                                      | 1        | 0.76%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1        | 0.76%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.76%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 148      | 57.14%  |
| Intel                 | 84       | 32.43%  |
| Qualcomm Atheros      | 8        | 3.09%   |
| ASIX Electronics      | 5        | 1.93%   |
| Aquantia              | 3        | 1.16%   |
| Xiaomi                | 2        | 0.77%   |
| Nvidia                | 2        | 0.77%   |
| Broadcom              | 2        | 0.77%   |
| TP-Link               | 1        | 0.39%   |
| Samsung Electronics   | 1        | 0.39%   |
| OPPO Electronics      | 1        | 0.39%   |
| Motorola PCS          | 1        | 0.39%   |
| Broadcom Limited      | 1        | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 114      | 43.02%  |
| Realtek RTL8125 2.5GbE Controller                                   | 29       | 10.94%  |
| Intel I211 Gigabit Network Connection                               | 27       | 10.19%  |
| Intel Ethernet Connection (2) I219-V                                | 12       | 4.53%   |
| Intel Ethernet Connection (7) I219-V                                | 9        | 3.4%    |
| Intel Ethernet Connection I217-LM                                   | 8        | 3.02%   |
| Intel Ethernet Controller I225-V                                    | 7        | 2.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 4        | 1.51%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.51%   |
| ASIX AX88179 Gigabit Ethernet                                       | 4        | 1.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 1.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.13%   |
| Intel 82579V Gigabit Network Connection                             | 3        | 1.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                               | 2        | 0.75%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.75%   |
| Intel Ethernet Connection (14) I219-V                               | 2        | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.75%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.38%   |
| OPPO RMX2180                                                        | 1        | 0.38%   |
| Nvidia MCP73 Ethernet                                               | 1        | 0.38%   |
| Nvidia MCP61 Ethernet                                               | 1        | 0.38%   |
| Motorola PCS moto g(6) plus                                         | 1        | 0.38%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 0.38%   |
| Intel 82578DC Gigabit Network Connection                            | 1        | 0.38%   |
| Intel 82574L Gigabit Network Connection                             | 1        | 0.38%   |
| Intel 82541PI Gigabit Ethernet Controller                           | 1        | 0.38%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express             | 1        | 0.38%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express               | 1        | 0.38%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express     | 1        | 0.38%   |
| ASIX AX88772B                                                       | 1        | 0.38%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 229      | 65.06%  |
| WiFi     | 118      | 33.52%  |
| Modem    | 5        | 1.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 189      | 77.14%  |
| WiFi     | 56       | 22.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 132      | 56.65%  |
| 2     | 80       | 34.33%  |
| 3     | 16       | 6.87%   |
| 4     | 4        | 1.72%   |
| 0     | 1        | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 182      | 77.45%  |
| Yes  | 53       | 22.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 57       | 49.14%  |
| Cambridge Silicon Radio  | 20       | 17.24%  |
| Realtek Semiconductor    | 17       | 14.66%  |
| ASUSTek Computer         | 8        | 6.9%    |
| Broadcom                 | 7        | 6.03%   |
| IMC Networks             | 2        | 1.72%   |
| HTC (High Tech Computer) | 2        | 1.72%   |
| TP-Link                  | 1        | 0.86%   |
| Toshiba                  | 1        | 0.86%   |
| Dynex                    | 1        | 0.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 25       | 21.55%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 20       | 17.24%  |
| Realtek Bluetooth Radio                                              | 16       | 13.79%  |
| Intel Bluetooth wireless interface                                   | 9        | 7.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 7        | 6.03%   |
| Intel AX210 Bluetooth                                                | 5        | 4.31%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 4.31%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 4        | 3.45%   |
| Intel AX201 Bluetooth                                                | 4        | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 4        | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 1.72%   |
| IMC Networks Bluetooth Radio                                         | 2        | 1.72%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 1.72%   |
| ASUS Bluetooth Device                                                | 2        | 1.72%   |
| TP-Link TPuLink UB500 Adapter                                        | 1        | 0.86%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 1        | 0.86%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.86%   |
| Intel Bluetooth Device                                               | 1        | 0.86%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.86%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 0.86%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 0.86%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.86%   |
| ASUS BCM20702A0                                                      | 1        | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 134      | 27.4%   |
| Intel                                           | 115      | 23.52%  |
| Nvidia                                          | 114      | 23.31%  |
| C-Media Electronics                             | 16       | 3.27%   |
| SteelSeries ApS                                 | 12       | 2.45%   |
| Logitech                                        | 11       | 2.25%   |
| Creative Labs                                   | 8        | 1.64%   |
| Texas Instruments                               | 7        | 1.43%   |
| JMTek                                           | 6        | 1.23%   |
| Sony                                            | 5        | 1.02%   |
| Razer USA                                       | 5        | 1.02%   |
| Kingston Technology                             | 5        | 1.02%   |
| Focusrite-Novation                              | 4        | 0.82%   |
| Blue Microphones                                | 4        | 0.82%   |
| Valve Software                                  | 3        | 0.61%   |
| RODE Microphones                                | 3        | 0.61%   |
| Thesycon Systemsoftware & Consulting            | 2        | 0.41%   |
| Sennheiser Communications                       | 2        | 0.41%   |
| Samson Technologies                             | 2        | 0.41%   |
| KTMicro                                         | 2        | 0.41%   |
| Creative Technology                             | 2        | 0.41%   |
| Corsair                                         | 2        | 0.41%   |
| Xilinx                                          | 1        | 0.2%    |
| VIA Technologies                                | 1        | 0.2%    |
| Trust                                           | 1        | 0.2%    |
| Solid State System                              | 1        | 0.2%    |
| Pro-Ject                                        | 1        | 0.2%    |
| Plantronics                                     | 1        | 0.2%    |
| No brand                                        | 1        | 0.2%    |
| Native Instruments                              | 1        | 0.2%    |
| NAD Electronics                                 | 1        | 0.2%    |
| M-Audio                                         | 1        | 0.2%    |
| Licensed by Sony Computer Entertainment America | 1        | 0.2%    |
| iConnectivity                                   | 1        | 0.2%    |
| Hewlett-Packard                                 | 1        | 0.2%    |
| GYROCOM C&C                                     | 1        | 0.2%    |
| GN Netcom                                       | 1        | 0.2%    |
| Giga-Byte Technology                            | 1        | 0.2%    |
| Generalplus Technology                          | 1        | 0.2%    |
| FiiO Electronics Technology                     | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 64       | 11.31%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 25       | 4.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 24       | 4.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 21       | 3.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 17       | 3%      |
| Nvidia GP104 High Definition Audio Controller                       | 16       | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 16       | 2.83%   |
| AMD Family 17h/19h HD Audio Controller                              | 15       | 2.65%   |
| Nvidia GP107GL High Definition Audio Controller                     | 13       | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 13       | 2.3%    |
| Nvidia GA104 High Definition Audio Controller                       | 12       | 2.12%   |
| Intel 200 Series PCH HD Audio                                       | 12       | 2.12%   |
| AMD Navi 10 HDMI Audio                                              | 12       | 2.12%   |
| Intel Cannon Lake PCH cAVS                                          | 11       | 1.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 10       | 1.77%   |
| Nvidia TU106 High Definition Audio Controller                       | 9        | 1.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 9        | 1.59%   |
| Nvidia GP106 High Definition Audio Controller                       | 8        | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 8        | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 7        | 1.24%   |
| Nvidia GK104 HDMI Audio Controller                                  | 6        | 1.06%   |
| Nvidia GA102 High Definition Audio Controller                       | 6        | 1.06%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]       | 6        | 1.06%   |
| Texas Instruments PCM2902 Audio Codec                               | 5        | 0.88%   |
| SteelSeries ApS Arctis Pro Wireless                                 | 5        | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                       | 5        | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 5        | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 5        | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                       | 4        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 4        | 0.71%   |
| JMTek USB PnP Audio Device                                          | 4        | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                              | 4        | 0.71%   |
| Blue Microphones Yeti Stereo Microphone                             | 4        | 0.71%   |
| Valve Software Valve VR Radio & HMD Mic                             | 3        | 0.53%   |
| SteelSeries ApS Arctis 7 wireless adapter                           | 3        | 0.53%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 3        | 0.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 3        | 0.53%   |
| Nvidia TU104 HD Audio Controller                                    | 3        | 0.53%   |
| Kingston Technology HyperX 7.1 Audio                                | 3        | 0.53%   |
| Intel Comet Lake PCH-V cAVS                                         | 3        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 37       | 19.68%  |
| Corsair             | 37       | 19.68%  |
| Kingston            | 22       | 11.7%   |
| Crucial             | 20       | 10.64%  |
| Samsung Electronics | 15       | 7.98%   |
| Unknown             | 12       | 6.38%   |
| SK hynix            | 9        | 4.79%   |
| Patriot             | 8        | 4.26%   |
| Team                | 6        | 3.19%   |
| Micron Technology   | 5        | 2.66%   |
| A-DATA Technology   | 3        | 1.6%    |
| Ramaxel Technology  | 2        | 1.06%   |
| GOODRAM             | 2        | 1.06%   |
| Unknown             | 2        | 1.06%   |
| Unknown (ABCD)      | 1        | 0.53%   |
| Unknown (0x5846)    | 1        | 0.53%   |
| Strontium           | 1        | 0.53%   |
| PNY                 | 1        | 0.53%   |
| Neo Forza           | 1        | 0.53%   |
| Golden Empire       | 1        | 0.53%   |
| GeIL                | 1        | 0.53%   |
| AMD                 | 1        | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 9        | 4.21%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 5        | 2.34%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 4        | 1.87%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 3        | 1.4%    |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 0.93%   |
| SK hynix RAM HMT41GU6AFR8C-PB 8GB DIMM DDR3 1600MT/s     | 2        | 0.93%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s  | 2        | 0.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 2        | 0.93%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.93%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s      | 2        | 0.93%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s      | 2        | 0.93%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s   | 2        | 0.93%   |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s      | 2        | 0.93%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 2        | 0.93%   |
| Patriot RAM PSD34G16002 4GB DIMM DDR3 1600MT/s           | 2        | 0.93%   |
| G.Skill RAM F4-3600C18-16GTZR 16GB DIMM DDR4 3600MT/s    | 2        | 0.93%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s   | 2        | 0.93%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 2        | 0.93%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 2        | 0.93%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 2        | 0.93%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 2        | 0.93%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s     | 2        | 0.93%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 2        | 0.93%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2733MT/s   | 2        | 0.93%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s    | 2        | 0.93%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 2        | 0.93%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 2        | 0.93%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s             | 2        | 0.93%   |
| Unknown                                                  | 2        | 0.93%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 0.47%   |
| Unknown RAM Module 1GB DIMM DDR2                         | 1        | 0.47%   |
| Unknown RAM Module 1GB DIMM 800MT/s                      | 1        | 0.47%   |
| Unknown RAM 04S2666CL19DM 4GB DIMM DDR4 2667MT/s         | 1        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 112      | 67.47%  |
| DDR3    | 36       | 21.69%  |
| Unknown | 6        | 3.61%   |
| SDRAM   | 4        | 2.41%   |
| DDR2    | 4        | 2.41%   |
| LPDDR4  | 3        | 1.81%   |
| DDR     | 1        | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 152      | 94.41%  |
| SODIMM  | 7        | 4.35%   |
| RIMM    | 1        | 0.62%   |
| FB-DIMM | 1        | 0.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 88       | 49.44%  |
| 16384 | 34       | 19.1%   |
| 4096  | 33       | 18.54%  |
| 2048  | 12       | 6.74%   |
| 32768 | 9        | 5.06%   |
| 1024  | 2        | 1.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 40       | 21.28%  |
| 3600    | 28       | 14.89%  |
| 1600    | 24       | 12.77%  |
| 1333    | 13       | 6.91%   |
| 2133    | 9        | 4.79%   |
| 2667    | 8        | 4.26%   |
| 2400    | 8        | 4.26%   |
| 3466    | 6        | 3.19%   |
| 3400    | 5        | 2.66%   |
| 3866    | 4        | 2.13%   |
| 3000    | 4        | 2.13%   |
| 800     | 4        | 2.13%   |
| 1867    | 3        | 1.6%    |
| 1800    | 3        | 1.6%    |
| 3800    | 2        | 1.06%   |
| 3733    | 2        | 1.06%   |
| 3500    | 2        | 1.06%   |
| 3333    | 2        | 1.06%   |
| 2733    | 2        | 1.06%   |
| 2666    | 2        | 1.06%   |
| Unknown | 2        | 1.06%   |
| 65535   | 1        | 0.53%   |
| 4333    | 1        | 0.53%   |
| 4000    | 1        | 0.53%   |
| 3151    | 1        | 0.53%   |
| 3134    | 1        | 0.53%   |
| 3067    | 1        | 0.53%   |
| 3066    | 1        | 0.53%   |
| 2933    | 1        | 0.53%   |
| 2800    | 1        | 0.53%   |
| 2267    | 1        | 0.53%   |
| 2048    | 1        | 0.53%   |
| 1280    | 1        | 0.53%   |
| 1066    | 1        | 0.53%   |
| 667     | 1        | 0.53%   |
| 400     | 1        | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 3        | 60%     |
| Prolific Technology | 1        | 20%     |
| Pantum              | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Prolific PL2305 Parallel Port | 1        | 20%     |
| Pantum P2500W series          | 1        | 20%     |
| Brother Printer               | 1        | 20%     |
| Brother HL-2130 series        | 1        | 20%     |
| Brother DCP-9015CDW           | 1        | 20%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 33       | 46.48%  |
| Microsoft                     | 5        | 7.04%   |
| Microdia                      | 4        | 5.63%   |
| Valve Software                | 3        | 4.23%   |
| Hewlett-Packard               | 3        | 4.23%   |
| Sunplus Innovation Technology | 2        | 2.82%   |
| Xiaomi                        | 1        | 1.41%   |
| Trust                         | 1        | 1.41%   |
| Tobii Technology AB           | 1        | 1.41%   |
| Sunplus IT                    | 1        | 1.41%   |
| Sony                          | 1        | 1.41%   |
| SN0002                        | 1        | 1.41%   |
| SJ-180517-N                   | 1        | 1.41%   |
| Samsung Electronics           | 1        | 1.41%   |
| Realtek Semiconductor         | 1        | 1.41%   |
| Razer USA                     | 1        | 1.41%   |
| MacroSilicon                  | 1        | 1.41%   |
| LG Electronics                | 1        | 1.41%   |
| Lenovo                        | 1        | 1.41%   |
| Leap Motion                   | 1        | 1.41%   |
| KYE Systems (Mouse Systems)   | 1        | 1.41%   |
| Huawei Technologies           | 1        | 1.41%   |
| HTC (High Tech Computer)      | 1        | 1.41%   |
| GEMBIRD                       | 1        | 1.41%   |
| EVGA                          | 1        | 1.41%   |
| Creative Technology           | 1        | 1.41%   |
| Unknown                       | 1        | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 9        | 12.68%  |
| Logitech Webcam C270                                  | 7        | 9.86%   |
| Logitech C922 Pro Stream Webcam                       | 4        | 5.63%   |
| Valve Software 3D Camera                              | 3        | 4.23%   |
| Microsoft LifeCam HD-3000                             | 2        | 2.82%   |
| Microdia USB 2.0 Camera                               | 2        | 2.82%   |
| Logitech Webcam C310                                  | 2        | 2.82%   |
| Logitech HD Webcam C615                               | 2        | 2.82%   |
| HP Webcam HD 2300                                     | 2        | 2.82%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                    | 1        | 1.41%   |
| Trust Full HD Webcam                                  | 1        | 1.41%   |
| Tobii AB EyeChip                                      | 1        | 1.41%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                    | 1        | 1.41%   |
| Sunplus Full HD webcam                                | 1        | 1.41%   |
| Sunplus EKACOM-K30                                    | 1        | 1.41%   |
| Sony CEVCECM                                          | 1        | 1.41%   |
| SN0002 1080P Web Camera                               | 1        | 1.41%   |
| SJ-180517-N 1080P Webcam                              | 1        | 1.41%   |
| Samsung Galaxy series, misc. (MTP mode)               | 1        | 1.41%   |
| Realtek Webcam                                        | 1        | 1.41%   |
| Razer USA Gaming Webcam [Kiyo]                        | 1        | 1.41%   |
| Microsoft LifeCam VX-5000                             | 1        | 1.41%   |
| Microsoft LifeCam VX-2000                             | 1        | 1.41%   |
| Microsoft LifeCam Cinema                              | 1        | 1.41%   |
| Microdia Webcam Vitade AF                             | 1        | 1.41%   |
| Microdia USB Live camera                              | 1        | 1.41%   |
| MacroSilicon USB Video                                | 1        | 1.41%   |
| Logitech Webcam C600                                  | 1        | 1.41%   |
| Logitech Webcam C170                                  | 1        | 1.41%   |
| Logitech Webcam C110                                  | 1        | 1.41%   |
| Logitech Webcam B500                                  | 1        | 1.41%   |
| Logitech StreamCam                                    | 1        | 1.41%   |
| Logitech HD Webcam C525                               | 1        | 1.41%   |
| Logitech HD Webcam B910                               | 1        | 1.41%   |
| Logitech CrystalCam                                   | 1        | 1.41%   |
| Logitech BRIO Ultra HD Webcam                         | 1        | 1.41%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 1.41%   |
| Lenovo 500 RGB Camera                                 | 1        | 1.41%   |
| Leap Motion Controller                                | 1        | 1.41%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera            | 1        | 1.41%   |

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
| 0     | 203      | 86.75%  |
| 1     | 27       | 11.54%  |
| 2     | 3        | 1.28%   |
| 3     | 1        | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Network               | 6        | 18.75%  |
| Net/wireless          | 5        | 15.63%  |
| Net/ethernet          | 5        | 15.63%  |
| Graphics card         | 5        | 15.63%  |
| Sound                 | 2        | 6.25%   |
| Chipcard              | 2        | 6.25%   |
| Camera                | 2        | 6.25%   |
| Bluetooth             | 2        | 6.25%   |
| Unassigned class      | 1        | 3.13%   |
| Multimedia controller | 1        | 3.13%   |
| Dvb card              | 1        | 3.13%   |


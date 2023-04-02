Linux in Czechia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Czechia/Desktop/README.md) and [notebooks](/Location/Czechia/Notebook/README.md).

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

Total: 2739

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T420s 4173R44      | Notebook    | [84e9a5f3d9](https://linux-hardware.org/?probe=84e9a5f3d9) | Apr 01, 2023 |
| UMAX          | VisionBook 14Wa Plus        | Notebook    | [ea8016c4a5](https://linux-hardware.org/?probe=ea8016c4a5) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0014e52bf3](https://linux-hardware.org/?probe=0014e52bf3) | Mar 31, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [2b23ce3fed](https://linux-hardware.org/?probe=2b23ce3fed) | Mar 31, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [448d1a491c](https://linux-hardware.org/?probe=448d1a491c) | Mar 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0ffc78eac6](https://linux-hardware.org/?probe=0ffc78eac6) | Mar 30, 2023 |
| ASUSTek       | F7L                         | Notebook    | [8d6f90f843](https://linux-hardware.org/?probe=8d6f90f843) | Mar 29, 2023 |
| ASUSTek       | F7L                         | Notebook    | [cdc5ab3b8a](https://linux-hardware.org/?probe=cdc5ab3b8a) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [6599d32d74](https://linux-hardware.org/?probe=6599d32d74) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [64bef0aff5](https://linux-hardware.org/?probe=64bef0aff5) | Mar 29, 2023 |
| ASUSTek       | PN41-S1                     | Mini pc     | [95da0c6b8a](https://linux-hardware.org/?probe=95da0c6b8a) | Mar 28, 2023 |
| Lenovo        | ThinkPad T580 20LAS4L216    | Notebook    | [9c3464baf9](https://linux-hardware.org/?probe=9c3464baf9) | Mar 27, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [eb82e949b2](https://linux-hardware.org/?probe=eb82e949b2) | Mar 27, 2023 |
| MSI           | B250M PRO-VDH 2018-05-07    | Desktop     | [6f7e481d06](https://linux-hardware.org/?probe=6f7e481d06) | Mar 27, 2023 |
| ASRock        | Z87 Killer                  | Desktop     | [53ec55f5ae](https://linux-hardware.org/?probe=53ec55f5ae) | Mar 27, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [b6bd6cab94](https://linux-hardware.org/?probe=b6bd6cab94) | Mar 26, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [df8f872445](https://linux-hardware.org/?probe=df8f872445) | Mar 25, 2023 |
| Lenovo        | G780                        | Notebook    | [1ad87e5add](https://linux-hardware.org/?probe=1ad87e5add) | Mar 23, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [aa102c68bf](https://linux-hardware.org/?probe=aa102c68bf) | Mar 23, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [47992266f4](https://linux-hardware.org/?probe=47992266f4) | Mar 22, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [dc56e35adc](https://linux-hardware.org/?probe=dc56e35adc) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | Notebook    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [7f1e3cf271](https://linux-hardware.org/?probe=7f1e3cf271) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [9b2ff390f6](https://linux-hardware.org/?probe=9b2ff390f6) | Mar 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Acer          | TravelMate 2490             | Notebook    | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| Acer          | TravelMate 7750ZG           | Notebook    | [5108cfe57c](https://linux-hardware.org/?probe=5108cfe57c) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [b7c8484508](https://linux-hardware.org/?probe=b7c8484508) | Mar 14, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [31c28e071b](https://linux-hardware.org/?probe=31c28e071b) | Mar 13, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [e82b110a76](https://linux-hardware.org/?probe=e82b110a76) | Mar 12, 2023 |
| HP            | 09CCh                       | Desktop     | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ef020a54d0](https://linux-hardware.org/?probe=ef020a54d0) | Mar 12, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [e51e1c905c](https://linux-hardware.org/?probe=e51e1c905c) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| HP            | 09CCh                       | Desktop     | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [a0eb3774fc](https://linux-hardware.org/?probe=a0eb3774fc) | Mar 09, 2023 |
| ASUSTek       | K54LY                       | Notebook    | [a846675d7f](https://linux-hardware.org/?probe=a846675d7f) | Mar 09, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | Notebook    | [fda0cb7297](https://linux-hardware.org/?probe=fda0cb7297) | Mar 08, 2023 |
| Dell          | Latitude E6420              | Notebook    | [c3384b7787](https://linux-hardware.org/?probe=c3384b7787) | Mar 07, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | Notebook    | [707155405b](https://linux-hardware.org/?probe=707155405b) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [70d063d399](https://linux-hardware.org/?probe=70d063d399) | Mar 05, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G531GT            | Notebook    | [810e15295b](https://linux-hardware.org/?probe=810e15295b) | Mar 03, 2023 |
| Dell          | Latitude 5421               | Notebook    | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [428377b153](https://linux-hardware.org/?probe=428377b153) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [5dbbffb04e](https://linux-hardware.org/?probe=5dbbffb04e) | Mar 02, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [9e63190b6f](https://linux-hardware.org/?probe=9e63190b6f) | Mar 01, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [10f864cbb0](https://linux-hardware.org/?probe=10f864cbb0) | Mar 01, 2023 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [8c36af11ab](https://linux-hardware.org/?probe=8c36af11ab) | Mar 01, 2023 |
| ASUSTek       | AM1I-A                      | Desktop     | [b5fe605f8b](https://linux-hardware.org/?probe=b5fe605f8b) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 0MH651                      | Desktop     | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [2477ae9a0e](https://linux-hardware.org/?probe=2477ae9a0e) | Feb 27, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [0ea2a54b39](https://linux-hardware.org/?probe=0ea2a54b39) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9b2a57b7d2](https://linux-hardware.org/?probe=9b2a57b7d2) | Feb 26, 2023 |
| Standard      | Unknown                     | Notebook    | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [2029821da8](https://linux-hardware.org/?probe=2029821da8) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [f0fa613cd2](https://linux-hardware.org/?probe=f0fa613cd2) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [8bfeed43ef](https://linux-hardware.org/?probe=8bfeed43ef) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude 5420               | Notebook    | [231c7534d3](https://linux-hardware.org/?probe=231c7534d3) | Feb 21, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [cff33d0b1e](https://linux-hardware.org/?probe=cff33d0b1e) | Feb 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [3dd7359a43](https://linux-hardware.org/?probe=3dd7359a43) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [53ef54922c](https://linux-hardware.org/?probe=53ef54922c) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Dell          | Vostro1710                  | Notebook    | [91b1af7ed6](https://linux-hardware.org/?probe=91b1af7ed6) | Feb 19, 2023 |
| Standard      | Unknown                     | Notebook    | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4fac3ddf27](https://linux-hardware.org/?probe=4fac3ddf27) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [e2facdc650](https://linux-hardware.org/?probe=e2facdc650) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [4c3c50a992](https://linux-hardware.org/?probe=4c3c50a992) | Feb 18, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e6391763b2](https://linux-hardware.org/?probe=e6391763b2) | Feb 17, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [0e2199617b](https://linux-hardware.org/?probe=0e2199617b) | Feb 17, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6c8bdf1f73](https://linux-hardware.org/?probe=6c8bdf1f73) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [89f9d45c66](https://linux-hardware.org/?probe=89f9d45c66) | Feb 17, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | Notebook    | [f546833d76](https://linux-hardware.org/?probe=f546833d76) | Feb 17, 2023 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [1026c10fa9](https://linux-hardware.org/?probe=1026c10fa9) | Feb 16, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [d118fe4ba2](https://linux-hardware.org/?probe=d118fe4ba2) | Feb 16, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [0255141f61](https://linux-hardware.org/?probe=0255141f61) | Feb 15, 2023 |
| HP            | ProBook 470 G4              | Notebook    | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [849a50c7fd](https://linux-hardware.org/?probe=849a50c7fd) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [938edcc32a](https://linux-hardware.org/?probe=938edcc32a) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [ef3ee2ebf2](https://linux-hardware.org/?probe=ef3ee2ebf2) | Feb 14, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cdd9011e76](https://linux-hardware.org/?probe=cdd9011e76) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [934ca9b130](https://linux-hardware.org/?probe=934ca9b130) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [1a76baff0f](https://linux-hardware.org/?probe=1a76baff0f) | Feb 12, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [19547b9a43](https://linux-hardware.org/?probe=19547b9a43) | Feb 12, 2023 |
| MSI           | GX700                       | Notebook    | [11154709fd](https://linux-hardware.org/?probe=11154709fd) | Feb 11, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2b4f9e9f21](https://linux-hardware.org/?probe=2b4f9e9f21) | Feb 11, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [16d6cdad97](https://linux-hardware.org/?probe=16d6cdad97) | Feb 09, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [731d910d0c](https://linux-hardware.org/?probe=731d910d0c) | Feb 08, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [d7157a7862](https://linux-hardware.org/?probe=d7157a7862) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8cb1801046](https://linux-hardware.org/?probe=8cb1801046) | Feb 07, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6490f4cb92](https://linux-hardware.org/?probe=6490f4cb92) | Feb 05, 2023 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [e9082b6ebf](https://linux-hardware.org/?probe=e9082b6ebf) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4214ad8f29](https://linux-hardware.org/?probe=4214ad8f29) | Feb 04, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [330da24dc9](https://linux-hardware.org/?probe=330da24dc9) | Feb 04, 2023 |
| HP            | ProBook 4530s               | Notebook    | [9ff88cbe9a](https://linux-hardware.org/?probe=9ff88cbe9a) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [922ee5ede0](https://linux-hardware.org/?probe=922ee5ede0) | Feb 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | Notebook    | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [3bcca39276](https://linux-hardware.org/?probe=3bcca39276) | Feb 02, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [1651e1e5af](https://linux-hardware.org/?probe=1651e1e5af) | Feb 02, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [87fe173b18](https://linux-hardware.org/?probe=87fe173b18) | Feb 02, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [80e1fa4ed8](https://linux-hardware.org/?probe=80e1fa4ed8) | Feb 01, 2023 |
| ASUSTek       | GL702VT                     | Notebook    | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| Lenovo        | ThinkPad E520 1143JYG       | Notebook    | [87735dd3b0](https://linux-hardware.org/?probe=87735dd3b0) | Feb 01, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b7fce61d74](https://linux-hardware.org/?probe=b7fce61d74) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [63dfd6ca48](https://linux-hardware.org/?probe=63dfd6ca48) | Jan 30, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [36caf406ce](https://linux-hardware.org/?probe=36caf406ce) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| ASUSTek       | V241DA                      | All in one  | [72df681f16](https://linux-hardware.org/?probe=72df681f16) | Jan 28, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [1c1f2d4d5b](https://linux-hardware.org/?probe=1c1f2d4d5b) | Jan 28, 2023 |
| Timi          | A35S                        | Notebook    | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| Lenovo        | MAHOBAY 31900003 STD        | All in one  | [d75e472005](https://linux-hardware.org/?probe=d75e472005) | Jan 26, 2023 |
| UMAX          | VisionBook 10Wr Tab         | Convertible | [6d747e3841](https://linux-hardware.org/?probe=6d747e3841) | Jan 26, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [bb83f545f7](https://linux-hardware.org/?probe=bb83f545f7) | Jan 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 3530              | Notebook    | [f0fa541c85](https://linux-hardware.org/?probe=f0fa541c85) | Jan 24, 2023 |
| HP            | 8750                        | Desktop     | [e8b02ffbb5](https://linux-hardware.org/?probe=e8b02ffbb5) | Jan 23, 2023 |
| Intel         | X79M-S                      | Desktop     | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [60f8946cdf](https://linux-hardware.org/?probe=60f8946cdf) | Jan 21, 2023 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [4e07ace043](https://linux-hardware.org/?probe=4e07ace043) | Jan 21, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [846e3df466](https://linux-hardware.org/?probe=846e3df466) | Jan 21, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [ec12d33bd7](https://linux-hardware.org/?probe=ec12d33bd7) | Jan 21, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [5a32ba3cd1](https://linux-hardware.org/?probe=5a32ba3cd1) | Jan 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [66c806fbfe](https://linux-hardware.org/?probe=66c806fbfe) | Jan 21, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d77bf1f32b](https://linux-hardware.org/?probe=d77bf1f32b) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | Notebook    | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASRock        | X99 Taichi                  | Desktop     | [793777c14e](https://linux-hardware.org/?probe=793777c14e) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [0e8d25f649](https://linux-hardware.org/?probe=0e8d25f649) | Jan 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4932579d3e](https://linux-hardware.org/?probe=4932579d3e) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a1b3ac9ccc](https://linux-hardware.org/?probe=a1b3ac9ccc) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f7fcfb7b18](https://linux-hardware.org/?probe=f7fcfb7b18) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [b11a63e25d](https://linux-hardware.org/?probe=b11a63e25d) | Jan 19, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad E550 20DF0081MC    | Notebook    | [1b7e734f36](https://linux-hardware.org/?probe=1b7e734f36) | Jan 19, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [7427c997d7](https://linux-hardware.org/?probe=7427c997d7) | Jan 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | Notebook    | [5b0e671bb8](https://linux-hardware.org/?probe=5b0e671bb8) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [395a44652b](https://linux-hardware.org/?probe=395a44652b) | Jan 17, 2023 |
| Dynabook      | PORTEGE X30W-K              | Convertible | [5c3d7c049e](https://linux-hardware.org/?probe=5c3d7c049e) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [5f3e7922cd](https://linux-hardware.org/?probe=5f3e7922cd) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [fa4fd9061f](https://linux-hardware.org/?probe=fa4fd9061f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [6841633faf](https://linux-hardware.org/?probe=6841633faf) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [b4bc427969](https://linux-hardware.org/?probe=b4bc427969) | Jan 15, 2023 |
| HP            | 250 G3                      | Notebook    | [717fbc7972](https://linux-hardware.org/?probe=717fbc7972) | Jan 15, 2023 |
| UMAX          | U-Box N42                   | Mini pc     | [4f778e38f0](https://linux-hardware.org/?probe=4f778e38f0) | Jan 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [9d4f877d3d](https://linux-hardware.org/?probe=9d4f877d3d) | Jan 14, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [32f2651aa1](https://linux-hardware.org/?probe=32f2651aa1) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [bd4516127b](https://linux-hardware.org/?probe=bd4516127b) | Jan 14, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [3c475bc193](https://linux-hardware.org/?probe=3c475bc193) | Jan 14, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8f9d1f85ee](https://linux-hardware.org/?probe=8f9d1f85ee) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Lenovo        | ThinkPad T450 20BUA0UG00    | Notebook    | [b0854ecbf8](https://linux-hardware.org/?probe=b0854ecbf8) | Jan 12, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1d6a667a5b](https://linux-hardware.org/?probe=1d6a667a5b) | Jan 11, 2023 |
| HP            | 304Ah                       | Desktop     | [c79a932800](https://linux-hardware.org/?probe=c79a932800) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a02943108d](https://linux-hardware.org/?probe=a02943108d) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [88ffbf550c](https://linux-hardware.org/?probe=88ffbf550c) | Jan 11, 2023 |
| Acer          | Extensa 2519                | Notebook    | [c044faaa05](https://linux-hardware.org/?probe=c044faaa05) | Jan 11, 2023 |
| Dell          | Precision 7710              | Notebook    | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [fa17d61c80](https://linux-hardware.org/?probe=fa17d61c80) | Jan 11, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [fd8d969adb](https://linux-hardware.org/?probe=fd8d969adb) | Jan 11, 2023 |
| UMAX          | VisionBook 15Wg Plus        | Notebook    | [e4c19089b5](https://linux-hardware.org/?probe=e4c19089b5) | Jan 11, 2023 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| Dell          | Precision 5510              | Notebook    | [22a344ddad](https://linux-hardware.org/?probe=22a344ddad) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [42f10f6d45](https://linux-hardware.org/?probe=42f10f6d45) | Jan 09, 2023 |
| Dell          | Precision 7710              | Notebook    | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3e39bca3ed](https://linux-hardware.org/?probe=3e39bca3ed) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2f03fd41c1](https://linux-hardware.org/?probe=2f03fd41c1) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [182a43f2b4](https://linux-hardware.org/?probe=182a43f2b4) | Jan 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [b808a6be1a](https://linux-hardware.org/?probe=b808a6be1a) | Jan 08, 2023 |
| Lenovo        | ThinkPad X230 2320JNG       | Notebook    | [29d3023af5](https://linux-hardware.org/?probe=29d3023af5) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| Dell          | 0C27VV A00                  | Desktop     | [317f136007](https://linux-hardware.org/?probe=317f136007) | Jan 07, 2023 |
| UMAX          | VisionBook N14G Plus        | Notebook    | [412180b4de](https://linux-hardware.org/?probe=412180b4de) | Jan 06, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [c56206ea8a](https://linux-hardware.org/?probe=c56206ea8a) | Jan 05, 2023 |
| Acer          | Aspire E1-531G              | Notebook    | [9b5a0200df](https://linux-hardware.org/?probe=9b5a0200df) | Jan 04, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [3b32e784a3](https://linux-hardware.org/?probe=3b32e784a3) | Jan 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Acer          | Aspire E1-531G              | Notebook    | [47813fa627](https://linux-hardware.org/?probe=47813fa627) | Jan 03, 2023 |
| HP            | ProBook 635 Aero G8         | Notebook    | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Google        | Chell                       | Notebook    | [02a0ae3bea](https://linux-hardware.org/?probe=02a0ae3bea) | Jan 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [dc3612b4e1](https://linux-hardware.org/?probe=dc3612b4e1) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [ce23d2f7cd](https://linux-hardware.org/?probe=ce23d2f7cd) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| Lenovo        | 31900003 STD                | All in one  | [4cc2e8cadd](https://linux-hardware.org/?probe=4cc2e8cadd) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [2b646304f0](https://linux-hardware.org/?probe=2b646304f0) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [8d54484965](https://linux-hardware.org/?probe=8d54484965) | Dec 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [5d0485ba40](https://linux-hardware.org/?probe=5d0485ba40) | Dec 26, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [d68451099d](https://linux-hardware.org/?probe=d68451099d) | Dec 26, 2022 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [7eb49ce0ab](https://linux-hardware.org/?probe=7eb49ce0ab) | Dec 24, 2022 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [4123115ef0](https://linux-hardware.org/?probe=4123115ef0) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Dell          | 0T656F A02                  | Desktop     | [35aa2eee2a](https://linux-hardware.org/?probe=35aa2eee2a) | Dec 23, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [c5cc33f2c6](https://linux-hardware.org/?probe=c5cc33f2c6) | Dec 23, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [ffbf35fd33](https://linux-hardware.org/?probe=ffbf35fd33) | Dec 23, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [3d90b10b72](https://linux-hardware.org/?probe=3d90b10b72) | Dec 22, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| HP            | 09CCh                       | Desktop     | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf62b1c520](https://linux-hardware.org/?probe=cf62b1c520) | Dec 20, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [2a2f618c62](https://linux-hardware.org/?probe=2a2f618c62) | Dec 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c20be92503](https://linux-hardware.org/?probe=c20be92503) | Dec 19, 2022 |
| UMAX          | 13Wr-Flex                   | Convertible | [487bef515a](https://linux-hardware.org/?probe=487bef515a) | Dec 18, 2022 |
| UMAX          | 13Wr-Flex                   | Convertible | [669c43b4f3](https://linux-hardware.org/?probe=669c43b4f3) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [c106327357](https://linux-hardware.org/?probe=c106327357) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [e5525b45b5](https://linux-hardware.org/?probe=e5525b45b5) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [00cc810cfc](https://linux-hardware.org/?probe=00cc810cfc) | Dec 17, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [4471c4a012](https://linux-hardware.org/?probe=4471c4a012) | Dec 11, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [db2a3e8ebb](https://linux-hardware.org/?probe=db2a3e8ebb) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [6e2cf6514a](https://linux-hardware.org/?probe=6e2cf6514a) | Dec 10, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [6b999f972f](https://linux-hardware.org/?probe=6b999f972f) | Dec 10, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [c415ea37d7](https://linux-hardware.org/?probe=c415ea37d7) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [b9ea8b5b2b](https://linux-hardware.org/?probe=b9ea8b5b2b) | Dec 08, 2022 |
| ASUSTek       | X55A                        | Notebook    | [283ef64c76](https://linux-hardware.org/?probe=283ef64c76) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [2b5a2c145c](https://linux-hardware.org/?probe=2b5a2c145c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS2291X    | Notebook    | [312119ddbd](https://linux-hardware.org/?probe=312119ddbd) | Dec 06, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [ca5bc5dfe6](https://linux-hardware.org/?probe=ca5bc5dfe6) | Dec 05, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e39eb3e3b](https://linux-hardware.org/?probe=2e39eb3e3b) | Dec 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [059ed32da0](https://linux-hardware.org/?probe=059ed32da0) | Dec 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e44ba4a41b](https://linux-hardware.org/?probe=e44ba4a41b) | Dec 03, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [2b1a977b21](https://linux-hardware.org/?probe=2b1a977b21) | Dec 02, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [012f2dccba](https://linux-hardware.org/?probe=012f2dccba) | Dec 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4e6ae396d9](https://linux-hardware.org/?probe=4e6ae396d9) | Nov 30, 2022 |
| UMAX          | U-Box N42                   | Mini pc     | [44170ddf90](https://linux-hardware.org/?probe=44170ddf90) | Nov 29, 2022 |
| UMAX          | U-Box N42                   | Mini pc     | [5953c13736](https://linux-hardware.org/?probe=5953c13736) | Nov 29, 2022 |
| HP            | 620                         | Notebook    | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| ASUSTek       | P5WD2-Premium               | Desktop     | [aad7343998](https://linux-hardware.org/?probe=aad7343998) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [53b311f78c](https://linux-hardware.org/?probe=53b311f78c) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [dad186aa07](https://linux-hardware.org/?probe=dad186aa07) | Nov 24, 2022 |
| HP            | 8750                        | Desktop     | [b1ac308187](https://linux-hardware.org/?probe=b1ac308187) | Nov 24, 2022 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [7e844d7172](https://linux-hardware.org/?probe=7e844d7172) | Nov 24, 2022 |
| HP            | 0AACh                       | Desktop     | [9e37ad4151](https://linux-hardware.org/?probe=9e37ad4151) | Nov 23, 2022 |
| HP            | 620                         | Notebook    | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| HP            | 82B4                        | Desktop     | [c56604f389](https://linux-hardware.org/?probe=c56604f389) | Nov 21, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1502b216b8](https://linux-hardware.org/?probe=1502b216b8) | Nov 20, 2022 |
| ASUSTek       | N73SV                       | Notebook    | [10840bac50](https://linux-hardware.org/?probe=10840bac50) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [73c9daf454](https://linux-hardware.org/?probe=73c9daf454) | Nov 19, 2022 |
| Dell          | Precision 5510              | Notebook    | [a9467ec69d](https://linux-hardware.org/?probe=a9467ec69d) | Nov 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [9ed6d8ee1e](https://linux-hardware.org/?probe=9ed6d8ee1e) | Nov 16, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [c8c143ccdd](https://linux-hardware.org/?probe=c8c143ccdd) | Nov 14, 2022 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | Desktop     | [b8da32bca0](https://linux-hardware.org/?probe=b8da32bca0) | Nov 14, 2022 |
| Lenovo        | 0x36C4 SDK0K17763 WIN 18... | All in one  | [7a3f735fc0](https://linux-hardware.org/?probe=7a3f735fc0) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [bc9518dbad](https://linux-hardware.org/?probe=bc9518dbad) | Nov 13, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [a7e35fd231](https://linux-hardware.org/?probe=a7e35fd231) | Nov 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [48572e207b](https://linux-hardware.org/?probe=48572e207b) | Nov 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [350e3f7ee2](https://linux-hardware.org/?probe=350e3f7ee2) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| HP            | 872E                        | Mini pc     | [b2e72a139e](https://linux-hardware.org/?probe=b2e72a139e) | Nov 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5b01559647](https://linux-hardware.org/?probe=5b01559647) | Nov 11, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [558d46bf81](https://linux-hardware.org/?probe=558d46bf81) | Nov 08, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [8a4f5a2c29](https://linux-hardware.org/?probe=8a4f5a2c29) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [9f586bafd4](https://linux-hardware.org/?probe=9f586bafd4) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [1d9cb16e2f](https://linux-hardware.org/?probe=1d9cb16e2f) | Nov 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [82bf0e80f0](https://linux-hardware.org/?probe=82bf0e80f0) | Nov 06, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [28af0c9803](https://linux-hardware.org/?probe=28af0c9803) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [fcb59bae39](https://linux-hardware.org/?probe=fcb59bae39) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [001308a248](https://linux-hardware.org/?probe=001308a248) | Nov 06, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [96bd39af33](https://linux-hardware.org/?probe=96bd39af33) | Nov 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [bd1833650d](https://linux-hardware.org/?probe=bd1833650d) | Nov 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [38b8d5a898](https://linux-hardware.org/?probe=38b8d5a898) | Nov 04, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [f5ac63680f](https://linux-hardware.org/?probe=f5ac63680f) | Nov 04, 2022 |
| HP            | 3029h                       | Desktop     | [2acf620628](https://linux-hardware.org/?probe=2acf620628) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | Notebook    | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Sony          | VPCYB1S1E                   | Notebook    | [54d0a26de9](https://linux-hardware.org/?probe=54d0a26de9) | Nov 03, 2022 |
| UMAX          | VisionBook N15G Plus        | Notebook    | [eba9cd6286](https://linux-hardware.org/?probe=eba9cd6286) | Nov 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f45ab957da](https://linux-hardware.org/?probe=f45ab957da) | Oct 28, 2022 |
| UMAX          | VisionBook 12Wi 64G         | Notebook    | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [8a8967999b](https://linux-hardware.org/?probe=8a8967999b) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [46c9e39101](https://linux-hardware.org/?probe=46c9e39101) | Oct 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [6d3bf37ff3](https://linux-hardware.org/?probe=6d3bf37ff3) | Oct 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [c97e42e738](https://linux-hardware.org/?probe=c97e42e738) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4c6edfec3e](https://linux-hardware.org/?probe=4c6edfec3e) | Oct 18, 2022 |
| HP            | Pavilion dv7                | Notebook    | [22031176a8](https://linux-hardware.org/?probe=22031176a8) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [5335a66143](https://linux-hardware.org/?probe=5335a66143) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [a6e072bc6b](https://linux-hardware.org/?probe=a6e072bc6b) | Oct 15, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [6bc730181f](https://linux-hardware.org/?probe=6bc730181f) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [da04425205](https://linux-hardware.org/?probe=da04425205) | Oct 14, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [00d5f7c4b1](https://linux-hardware.org/?probe=00d5f7c4b1) | Oct 13, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [d105b4c1f7](https://linux-hardware.org/?probe=d105b4c1f7) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [18ac5ede65](https://linux-hardware.org/?probe=18ac5ede65) | Oct 08, 2022 |
| Dell          | Latitude E7250              | Notebook    | [5ecb7bbb6c](https://linux-hardware.org/?probe=5ecb7bbb6c) | Oct 07, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [829a14598f](https://linux-hardware.org/?probe=829a14598f) | Oct 07, 2022 |
| ASUSTek       | 1001PXD                     | Notebook    | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| HP            | EliteBook 1040 G4           | Notebook    | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Dell          | 0D28YY A01                  | Desktop     | [5c85c7623a](https://linux-hardware.org/?probe=5c85c7623a) | Oct 04, 2022 |
| Timi          | A35S                        | Notebook    | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [13f60e066f](https://linux-hardware.org/?probe=13f60e066f) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [e3eb4cd95f](https://linux-hardware.org/?probe=e3eb4cd95f) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ff11bc4efb](https://linux-hardware.org/?probe=ff11bc4efb) | Oct 02, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [7c19c1f557](https://linux-hardware.org/?probe=7c19c1f557) | Oct 02, 2022 |
| Acer          | Aspire 7540                 | Notebook    | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [98197c818f](https://linux-hardware.org/?probe=98197c818f) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [92f9efe077](https://linux-hardware.org/?probe=92f9efe077) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [9377d23abd](https://linux-hardware.org/?probe=9377d23abd) | Sep 28, 2022 |
| Timi          | A35S                        | Notebook    | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | K53SV                       | Notebook    | [d2801f9560](https://linux-hardware.org/?probe=d2801f9560) | Sep 26, 2022 |
| Lenovo        | 3000 V100 076346G           | Notebook    | [0575c1ea4f](https://linux-hardware.org/?probe=0575c1ea4f) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| Timi          | RedmiBook 16                | Notebook    | [0a65bab615](https://linux-hardware.org/?probe=0a65bab615) | Sep 25, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [262ff53f6a](https://linux-hardware.org/?probe=262ff53f6a) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [d1ed6b20cf](https://linux-hardware.org/?probe=d1ed6b20cf) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [9e04fb330b](https://linux-hardware.org/?probe=9e04fb330b) | Sep 24, 2022 |
| Timi          | A35S                        | Notebook    | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | Desktop     | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [ea8ea96269](https://linux-hardware.org/?probe=ea8ea96269) | Sep 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [ea0ab53cac](https://linux-hardware.org/?probe=ea0ab53cac) | Sep 21, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | Notebook    | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6e61a9993](https://linux-hardware.org/?probe=a6e61a9993) | Sep 19, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [b7f881a109](https://linux-hardware.org/?probe=b7f881a109) | Sep 19, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [59e7485a11](https://linux-hardware.org/?probe=59e7485a11) | Sep 19, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [b9693eaf7c](https://linux-hardware.org/?probe=b9693eaf7c) | Sep 17, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [b5a0c6309d](https://linux-hardware.org/?probe=b5a0c6309d) | Sep 17, 2022 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Dell          | Latitude 5430               | Notebook    | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [bfd4a6b00a](https://linux-hardware.org/?probe=bfd4a6b00a) | Sep 13, 2022 |
| Lenovo        | ThinkPad T540p 20BF002CM... | Notebook    | [3343da6005](https://linux-hardware.org/?probe=3343da6005) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | Notebook    | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | Notebook    | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| UMAX          | VisionBook N15G Plus        | Notebook    | [d17fb4f8f9](https://linux-hardware.org/?probe=d17fb4f8f9) | Sep 11, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [be7516b088](https://linux-hardware.org/?probe=be7516b088) | Sep 10, 2022 |
| Dell          | Latitude 5531               | Notebook    | [66eac260ef](https://linux-hardware.org/?probe=66eac260ef) | Sep 09, 2022 |
| Dell          | Precision 3551              | Notebook    | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Dell          | Latitude 5531               | Notebook    | [dff44a5e24](https://linux-hardware.org/?probe=dff44a5e24) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Google        | Coral                       | Notebook    | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [60b4add0a0](https://linux-hardware.org/?probe=60b4add0a0) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [2a3eb4b772](https://linux-hardware.org/?probe=2a3eb4b772) | Sep 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [cc30fbdce2](https://linux-hardware.org/?probe=cc30fbdce2) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [4d1339ef49](https://linux-hardware.org/?probe=4d1339ef49) | Aug 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [fc3200b967](https://linux-hardware.org/?probe=fc3200b967) | Aug 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a01239fd83](https://linux-hardware.org/?probe=a01239fd83) | Aug 29, 2022 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [918418e0fc](https://linux-hardware.org/?probe=918418e0fc) | Aug 29, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [108e0c7803](https://linux-hardware.org/?probe=108e0c7803) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [bddbedffed](https://linux-hardware.org/?probe=bddbedffed) | Aug 29, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| HP            | 8509                        | Desktop     | [0656e40cba](https://linux-hardware.org/?probe=0656e40cba) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| MSI           | GS73VR 6RF                  | Notebook    | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| Dell          | Latitude 5490               | Notebook    | [a37eabe03f](https://linux-hardware.org/?probe=a37eabe03f) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2e77015116](https://linux-hardware.org/?probe=2e77015116) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| HP            | Stream 7 Tablet             | Tablet      | [9d4dabb130](https://linux-hardware.org/?probe=9d4dabb130) | Aug 19, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [ed06ba603c](https://linux-hardware.org/?probe=ed06ba603c) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | Notebook    | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [f89a185aa6](https://linux-hardware.org/?probe=f89a185aa6) | Aug 17, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [8ea61dbd3c](https://linux-hardware.org/?probe=8ea61dbd3c) | Aug 14, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [acf8952e47](https://linux-hardware.org/?probe=acf8952e47) | Aug 13, 2022 |
| HP            | 805B                        | Desktop     | [188fdd3a56](https://linux-hardware.org/?probe=188fdd3a56) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [e93f8de88b](https://linux-hardware.org/?probe=e93f8de88b) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [e429237c05](https://linux-hardware.org/?probe=e429237c05) | Aug 13, 2022 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [0f367345a0](https://linux-hardware.org/?probe=0f367345a0) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad E590 20NB0029MC    | Notebook    | [233b3cdd54](https://linux-hardware.org/?probe=233b3cdd54) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [8b0ede5e40](https://linux-hardware.org/?probe=8b0ede5e40) | Aug 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [9d55b54de7](https://linux-hardware.org/?probe=9d55b54de7) | Aug 10, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [cba7d360f1](https://linux-hardware.org/?probe=cba7d360f1) | Aug 10, 2022 |
| Dell          | Latitude 5421               | Notebook    | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [ee1bdd9333](https://linux-hardware.org/?probe=ee1bdd9333) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [a0243ce6f0](https://linux-hardware.org/?probe=a0243ce6f0) | Aug 09, 2022 |
| Dell          | Latitude 5531               | Notebook    | [64998a7d5a](https://linux-hardware.org/?probe=64998a7d5a) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | Desktop     | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [61e317887a](https://linux-hardware.org/?probe=61e317887a) | Aug 07, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [9c945add4e](https://linux-hardware.org/?probe=9c945add4e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [d1ab7d1d36](https://linux-hardware.org/?probe=d1ab7d1d36) | Aug 06, 2022 |
| Lenovo        | ThinkPad X270 20HN0015GE    | Notebook    | [2577ffae50](https://linux-hardware.org/?probe=2577ffae50) | Aug 06, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [61b30cfde0](https://linux-hardware.org/?probe=61b30cfde0) | Aug 06, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [01430753da](https://linux-hardware.org/?probe=01430753da) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d704ff7364](https://linux-hardware.org/?probe=d704ff7364) | Jul 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82d0a7ace6](https://linux-hardware.org/?probe=82d0a7ace6) | Jul 29, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| HP            | 1494                        | Desktop     | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [55e2c27aaa](https://linux-hardware.org/?probe=55e2c27aaa) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [e8c6448552](https://linux-hardware.org/?probe=e8c6448552) | Jul 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [2986a26253](https://linux-hardware.org/?probe=2986a26253) | Jul 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [7e6502be7c](https://linux-hardware.org/?probe=7e6502be7c) | Jul 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [c000bcc566](https://linux-hardware.org/?probe=c000bcc566) | Jul 20, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [47c85dbefd](https://linux-hardware.org/?probe=47c85dbefd) | Jul 18, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [c6888145e7](https://linux-hardware.org/?probe=c6888145e7) | Jul 18, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [2349372af2](https://linux-hardware.org/?probe=2349372af2) | Jul 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9c06bd996b](https://linux-hardware.org/?probe=9c06bd996b) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9e71693839](https://linux-hardware.org/?probe=9e71693839) | Jul 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [179267a713](https://linux-hardware.org/?probe=179267a713) | Jul 15, 2022 |
| Dell          | G3 3590                     | Notebook    | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [9b66e8ad0e](https://linux-hardware.org/?probe=9b66e8ad0e) | Jul 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | Notebook    | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [e3962f34e4](https://linux-hardware.org/?probe=e3962f34e4) | Jul 11, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [e5316b7d72](https://linux-hardware.org/?probe=e5316b7d72) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [3df269fec9](https://linux-hardware.org/?probe=3df269fec9) | Jul 09, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [90f45f2ebc](https://linux-hardware.org/?probe=90f45f2ebc) | Jul 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [02a8803d9a](https://linux-hardware.org/?probe=02a8803d9a) | Jul 07, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [04cc10b779](https://linux-hardware.org/?probe=04cc10b779) | Jul 07, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [b94f3f8031](https://linux-hardware.org/?probe=b94f3f8031) | Jul 07, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| HP            | ProBook 4530s               | Notebook    | [db207530bc](https://linux-hardware.org/?probe=db207530bc) | Jul 06, 2022 |
| HP            | Notebook                    | Notebook    | [9b87d6ee2d](https://linux-hardware.org/?probe=9b87d6ee2d) | Jul 06, 2022 |
| ASUSTek       | P5B                         | Desktop     | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| Dell          | Latitude 7520               | Notebook    | [531ccedcf2](https://linux-hardware.org/?probe=531ccedcf2) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | Notebook    | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| HP            | 625                         | Notebook    | [0acc5581d4](https://linux-hardware.org/?probe=0acc5581d4) | Jul 03, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [38b91d59e7](https://linux-hardware.org/?probe=38b91d59e7) | Jul 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [8bcc34797b](https://linux-hardware.org/?probe=8bcc34797b) | Jul 02, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [eaf34443c7](https://linux-hardware.org/?probe=eaf34443c7) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [01fb492b9d](https://linux-hardware.org/?probe=01fb492b9d) | Jul 01, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [b4b8457bd9](https://linux-hardware.org/?probe=b4b8457bd9) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bef849e3d1](https://linux-hardware.org/?probe=bef849e3d1) | Jun 29, 2022 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [d5be9c4fca](https://linux-hardware.org/?probe=d5be9c4fca) | Jun 29, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [7b07f30b17](https://linux-hardware.org/?probe=7b07f30b17) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| Gigabyte      | Z690 UD                     | Desktop     | [2c21dadeed](https://linux-hardware.org/?probe=2c21dadeed) | Jun 25, 2022 |
| ASUSTek       | H81M-R 2016-11-08           | Desktop     | [f9ac4d3e81](https://linux-hardware.org/?probe=f9ac4d3e81) | Jun 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Dell          | Precision 5550              | Notebook    | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cf76d2d9a4](https://linux-hardware.org/?probe=cf76d2d9a4) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Dell          | Precision 5550              | Notebook    | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [80ecbe8684](https://linux-hardware.org/?probe=80ecbe8684) | Jun 21, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| Dell          | Latitude E5470              | Notebook    | [e18ba2b5d7](https://linux-hardware.org/?probe=e18ba2b5d7) | Jun 18, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | Notebook    | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| HP            | 8711                        | Mini pc     | [6ceafddb10](https://linux-hardware.org/?probe=6ceafddb10) | Jun 13, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [bbba4fae4b](https://linux-hardware.org/?probe=bbba4fae4b) | Jun 12, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [4a8b021e76](https://linux-hardware.org/?probe=4a8b021e76) | Jun 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [8b02f3e420](https://linux-hardware.org/?probe=8b02f3e420) | Jun 10, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| Lenovo        | ThinkPad T460s 20FA003JM... | Notebook    | [417d162cab](https://linux-hardware.org/?probe=417d162cab) | Jun 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [39ad69783e](https://linux-hardware.org/?probe=39ad69783e) | Jun 08, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [805f88e697](https://linux-hardware.org/?probe=805f88e697) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [77b282aaaa](https://linux-hardware.org/?probe=77b282aaaa) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [b320ea6050](https://linux-hardware.org/?probe=b320ea6050) | Jun 05, 2022 |
| MSI           | GP72 7QF                    | Notebook    | [ad0e85dbf9](https://linux-hardware.org/?probe=ad0e85dbf9) | Jun 05, 2022 |
| MSI           | B85M-G43                    | Desktop     | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [ac88b5f927](https://linux-hardware.org/?probe=ac88b5f927) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| Lenovo        | ThinkCentre M57 00P4496     | Desktop     | [07ba75838a](https://linux-hardware.org/?probe=07ba75838a) | May 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [276f8565dc](https://linux-hardware.org/?probe=276f8565dc) | May 29, 2022 |
| HP            | Pavilion dv6                | Notebook    | [3623a980f8](https://linux-hardware.org/?probe=3623a980f8) | May 28, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0d439f9812](https://linux-hardware.org/?probe=0d439f9812) | May 25, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | ThinkPad T420 42362L0       | Notebook    | [3aa17b879d](https://linux-hardware.org/?probe=3aa17b879d) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [e7c21e067a](https://linux-hardware.org/?probe=e7c21e067a) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [8ed772fb1d](https://linux-hardware.org/?probe=8ed772fb1d) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | Notebook    | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [5f03a4b52d](https://linux-hardware.org/?probe=5f03a4b52d) | May 21, 2022 |
| Acer          | Z2621G                      | All in one  | [139c780029](https://linux-hardware.org/?probe=139c780029) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| MSI           | B85M-G43                    | Desktop     | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [ab5a307891](https://linux-hardware.org/?probe=ab5a307891) | May 18, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [47e42883f4](https://linux-hardware.org/?probe=47e42883f4) | May 18, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [77c7c34b9e](https://linux-hardware.org/?probe=77c7c34b9e) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [798bcbfce3](https://linux-hardware.org/?probe=798bcbfce3) | May 17, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [a532101bbf](https://linux-hardware.org/?probe=a532101bbf) | May 17, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HP            | 22F8                        | Desktop     | [70f6561c5c](https://linux-hardware.org/?probe=70f6561c5c) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [e8915a5023](https://linux-hardware.org/?probe=e8915a5023) | May 15, 2022 |
| ASUSTek       | X555LB                      | Notebook    | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [5f148de534](https://linux-hardware.org/?probe=5f148de534) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [14905c8ec7](https://linux-hardware.org/?probe=14905c8ec7) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Chuwi         | MiniBook X                  | Notebook    | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | Notebook    | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [a70f694f0b](https://linux-hardware.org/?probe=a70f694f0b) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [d2deff798c](https://linux-hardware.org/?probe=d2deff798c) | May 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a3e95474a0](https://linux-hardware.org/?probe=a3e95474a0) | May 08, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [1983ed1d48](https://linux-hardware.org/?probe=1983ed1d48) | May 07, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [97a95fa1af](https://linux-hardware.org/?probe=97a95fa1af) | May 05, 2022 |
| MSI           | B85M-G43                    | Desktop     | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [ab9edfbc39](https://linux-hardware.org/?probe=ab9edfbc39) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [09944d29bf](https://linux-hardware.org/?probe=09944d29bf) | May 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [ff568c874c](https://linux-hardware.org/?probe=ff568c874c) | Apr 30, 2022 |
| Dell          | Latitude 3330               | Notebook    | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [f3b89e43d4](https://linux-hardware.org/?probe=f3b89e43d4) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | Desktop     | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f4a6777382](https://linux-hardware.org/?probe=f4a6777382) | Apr 30, 2022 |
| Gigabyte      | H170-HD3 DDR3-CF            | Desktop     | [b23594dfa0](https://linux-hardware.org/?probe=b23594dfa0) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | Notebook    | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [abc0c5402d](https://linux-hardware.org/?probe=abc0c5402d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [9389a4bd1e](https://linux-hardware.org/?probe=9389a4bd1e) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [3b927afe90](https://linux-hardware.org/?probe=3b927afe90) | Apr 28, 2022 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [97c0bfb76c](https://linux-hardware.org/?probe=97c0bfb76c) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| HP            | 22F8                        | Desktop     | [eb4d49a17b](https://linux-hardware.org/?probe=eb4d49a17b) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [ab5986371d](https://linux-hardware.org/?probe=ab5986371d) | Apr 23, 2022 |
| HP            | 22F8                        | Desktop     | [67dc13d1ad](https://linux-hardware.org/?probe=67dc13d1ad) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | Notebook    | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | Notebook    | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [68d9ef89c7](https://linux-hardware.org/?probe=68d9ef89c7) | Apr 19, 2022 |
| MSI           | B150 PC MATE                | Desktop     | [34c7fe45bc](https://linux-hardware.org/?probe=34c7fe45bc) | Apr 19, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [497807c732](https://linux-hardware.org/?probe=497807c732) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [874e39c8ef](https://linux-hardware.org/?probe=874e39c8ef) | Apr 18, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a2b841241d](https://linux-hardware.org/?probe=a2b841241d) | Apr 17, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [1b9b990e65](https://linux-hardware.org/?probe=1b9b990e65) | Apr 17, 2022 |
| Acer          | Aspire V3-112P              | Notebook    | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa535559e0](https://linux-hardware.org/?probe=fa535559e0) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | Desktop     | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [b1944bf89e](https://linux-hardware.org/?probe=b1944bf89e) | Apr 15, 2022 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [19b11d696f](https://linux-hardware.org/?probe=19b11d696f) | Apr 15, 2022 |
| Lenovo        | ThinkPad T400 6474AH2       | Notebook    | [f5e7108c33](https://linux-hardware.org/?probe=f5e7108c33) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Gigabyte      | Z590 VISION D               | Desktop     | [4bde7cc5cd](https://linux-hardware.org/?probe=4bde7cc5cd) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8a5920ae1a](https://linux-hardware.org/?probe=8a5920ae1a) | Apr 13, 2022 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [46dc99c237](https://linux-hardware.org/?probe=46dc99c237) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | Desktop     | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [d180d3831a](https://linux-hardware.org/?probe=d180d3831a) | Apr 10, 2022 |
| MSI           | H110M ECO                   | Desktop     | [c01d51d1f5](https://linux-hardware.org/?probe=c01d51d1f5) | Apr 09, 2022 |
| Acer          | TravelMate 4670             | Notebook    | [f5067e581b](https://linux-hardware.org/?probe=f5067e581b) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7f4e9c9158](https://linux-hardware.org/?probe=7f4e9c9158) | Apr 09, 2022 |
| HP            | 1495                        | Desktop     | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| Dell          | 0VD5HY A04                  | Desktop     | [8672ef6c18](https://linux-hardware.org/?probe=8672ef6c18) | Apr 07, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [0f8ce13fb9](https://linux-hardware.org/?probe=0f8ce13fb9) | Apr 06, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7249da837c](https://linux-hardware.org/?probe=7249da837c) | Apr 06, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [65e855a6a5](https://linux-hardware.org/?probe=65e855a6a5) | Apr 05, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [046d0eb6c8](https://linux-hardware.org/?probe=046d0eb6c8) | Apr 05, 2022 |
| Acer          | Extensa 5630                | Notebook    | [7ff131392d](https://linux-hardware.org/?probe=7ff131392d) | Apr 05, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [d95c37955a](https://linux-hardware.org/?probe=d95c37955a) | Apr 03, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [487aa8af18](https://linux-hardware.org/?probe=487aa8af18) | Apr 03, 2022 |
| Acer          | Extensa 5630                | Notebook    | [4c6f7067bc](https://linux-hardware.org/?probe=4c6f7067bc) | Apr 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [beb645df2c](https://linux-hardware.org/?probe=beb645df2c) | Apr 02, 2022 |
| Intel         | DG45ID AAE27729-310         | Desktop     | [4a15651672](https://linux-hardware.org/?probe=4a15651672) | Apr 01, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [96e4eca691](https://linux-hardware.org/?probe=96e4eca691) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [54717b42d3](https://linux-hardware.org/?probe=54717b42d3) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| Dell          | OptiPlex 7010               | Desktop     | [f1167c797e](https://linux-hardware.org/?probe=f1167c797e) | Mar 31, 2022 |
| Acer          | Veriton M4610G              | Desktop     | [34ac41051e](https://linux-hardware.org/?probe=34ac41051e) | Mar 30, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | Notebook    | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [b951c3cc48](https://linux-hardware.org/?probe=b951c3cc48) | Mar 29, 2022 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | Notebook    | [4e67f54e53](https://linux-hardware.org/?probe=4e67f54e53) | Mar 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d83c6588f2](https://linux-hardware.org/?probe=d83c6588f2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | Notebook    | [649bc1b13a](https://linux-hardware.org/?probe=649bc1b13a) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | Notebook    | [d1638977bc](https://linux-hardware.org/?probe=d1638977bc) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [67c079dd83](https://linux-hardware.org/?probe=67c079dd83) | Mar 28, 2022 |
| HP            | Compaq 615                  | Notebook    | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [582d76d560](https://linux-hardware.org/?probe=582d76d560) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b02c880a8a](https://linux-hardware.org/?probe=b02c880a8a) | Mar 26, 2022 |
| Le Cube 1     | Unknown                     | Desktop     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6df7f8330c](https://linux-hardware.org/?probe=6df7f8330c) | Mar 25, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [c6ed527183](https://linux-hardware.org/?probe=c6ed527183) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | Notebook    | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ad8feeb6a4](https://linux-hardware.org/?probe=ad8feeb6a4) | Mar 24, 2022 |
| HP            | Compaq 615                  | Notebook    | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [4ee969ac04](https://linux-hardware.org/?probe=4ee969ac04) | Mar 24, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [8ac18b3ae9](https://linux-hardware.org/?probe=8ac18b3ae9) | Mar 24, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3193e91c83](https://linux-hardware.org/?probe=3193e91c83) | Mar 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [3f268da44f](https://linux-hardware.org/?probe=3f268da44f) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [86242fab56](https://linux-hardware.org/?probe=86242fab56) | Mar 21, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [ad4ffeb6d5](https://linux-hardware.org/?probe=ad4ffeb6d5) | Mar 20, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7f37d7148d](https://linux-hardware.org/?probe=7f37d7148d) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a5d1f1ec32](https://linux-hardware.org/?probe=a5d1f1ec32) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | Notebook    | [4824a016cc](https://linux-hardware.org/?probe=4824a016cc) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | Notebook    | [847871aa63](https://linux-hardware.org/?probe=847871aa63) | Mar 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [12249482c6](https://linux-hardware.org/?probe=12249482c6) | Mar 17, 2022 |
| Dell          | Latitude E4200              | Notebook    | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | Notebook    | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| MSI           | B85M-G43                    | Desktop     | [3869d4fdc0](https://linux-hardware.org/?probe=3869d4fdc0) | Mar 14, 2022 |
| MSI           | B85M-E45 2015-08-19         | Desktop     | [90f5d4247e](https://linux-hardware.org/?probe=90f5d4247e) | Mar 13, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [620772c443](https://linux-hardware.org/?probe=620772c443) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [0429db8c01](https://linux-hardware.org/?probe=0429db8c01) | Mar 11, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [84ccdf8375](https://linux-hardware.org/?probe=84ccdf8375) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [62f3b41d12](https://linux-hardware.org/?probe=62f3b41d12) | Mar 09, 2022 |
| Acer          | TP-SW5-012-16UW             | Notebook    | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [c9ba6eb4ae](https://linux-hardware.org/?probe=c9ba6eb4ae) | Mar 09, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [876e876df1](https://linux-hardware.org/?probe=876e876df1) | Mar 09, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [038e9b79ef](https://linux-hardware.org/?probe=038e9b79ef) | Mar 08, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [ce5f22f97a](https://linux-hardware.org/?probe=ce5f22f97a) | Mar 08, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [71d5919c2d](https://linux-hardware.org/?probe=71d5919c2d) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [cd3380a8b4](https://linux-hardware.org/?probe=cd3380a8b4) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [3667f5b9e9](https://linux-hardware.org/?probe=3667f5b9e9) | Mar 07, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ae9c8e47e2](https://linux-hardware.org/?probe=ae9c8e47e2) | Mar 07, 2022 |
| Acer          | Extensa 5620                | Notebook    | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [885cc74a20](https://linux-hardware.org/?probe=885cc74a20) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Dell          | Latitude E5470              | Notebook    | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [3333e54277](https://linux-hardware.org/?probe=3333e54277) | Mar 04, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [047ff4ad80](https://linux-hardware.org/?probe=047ff4ad80) | Mar 04, 2022 |
| MSI           | B85M-G43                    | Desktop     | [d5e3087569](https://linux-hardware.org/?probe=d5e3087569) | Mar 04, 2022 |
| Dell          | Latitude 7520               | Notebook    | [023fba74f0](https://linux-hardware.org/?probe=023fba74f0) | Mar 04, 2022 |
| HP            | 3031h                       | Desktop     | [52a519941d](https://linux-hardware.org/?probe=52a519941d) | Mar 03, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [c4106a59b1](https://linux-hardware.org/?probe=c4106a59b1) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | Notebook    | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [66cdff8786](https://linux-hardware.org/?probe=66cdff8786) | Mar 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [21b4f724b8](https://linux-hardware.org/?probe=21b4f724b8) | Mar 02, 2022 |
| Dell          | Latitude 7520               | Notebook    | [d31adbbcad](https://linux-hardware.org/?probe=d31adbbcad) | Mar 02, 2022 |
| Gigabyte      | G1.Sniper                   | Desktop     | [59b1ae56dd](https://linux-hardware.org/?probe=59b1ae56dd) | Mar 01, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [02b86c4d66](https://linux-hardware.org/?probe=02b86c4d66) | Mar 01, 2022 |
| HP            | 821D                        | Desktop     | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| ASUSTek       | P8Q67-M DO/TPM              | Desktop     | [ee784c0a7e](https://linux-hardware.org/?probe=ee784c0a7e) | Feb 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [36ea5044b6](https://linux-hardware.org/?probe=36ea5044b6) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [cab4f22396](https://linux-hardware.org/?probe=cab4f22396) | Feb 28, 2022 |
| ASRock        | Z370M Pro4                  | Desktop     | [8e08f3846b](https://linux-hardware.org/?probe=8e08f3846b) | Feb 27, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [b2e75d51bb](https://linux-hardware.org/?probe=b2e75d51bb) | Feb 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [477b323b68](https://linux-hardware.org/?probe=477b323b68) | Feb 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [4cb3686ee5](https://linux-hardware.org/?probe=4cb3686ee5) | Feb 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [a6dae44349](https://linux-hardware.org/?probe=a6dae44349) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [245600d3fd](https://linux-hardware.org/?probe=245600d3fd) | Feb 23, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [1a4f0d32ab](https://linux-hardware.org/?probe=1a4f0d32ab) | Feb 22, 2022 |
| Gigabyte      | G1.Sniper                   | Desktop     | [615669f693](https://linux-hardware.org/?probe=615669f693) | Feb 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d32c812d2b](https://linux-hardware.org/?probe=d32c812d2b) | Feb 22, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [bedd29ee73](https://linux-hardware.org/?probe=bedd29ee73) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [56496468de](https://linux-hardware.org/?probe=56496468de) | Feb 21, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [6cb1c24dd7](https://linux-hardware.org/?probe=6cb1c24dd7) | Feb 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [de7189b0d4](https://linux-hardware.org/?probe=de7189b0d4) | Feb 20, 2022 |
| MSI           | A55M-P33                    | Desktop     | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| MSI           | Boston                      | Desktop     | [0f7a7dd744](https://linux-hardware.org/?probe=0f7a7dd744) | Feb 19, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [5651fbf2c8](https://linux-hardware.org/?probe=5651fbf2c8) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Google        | Chell                       | Notebook    | [46b95ce3a4](https://linux-hardware.org/?probe=46b95ce3a4) | Feb 17, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [51dfd147ef](https://linux-hardware.org/?probe=51dfd147ef) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | Notebook    | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Dell          | 073MMW A02                  | Desktop     | [ab6cd0396d](https://linux-hardware.org/?probe=ab6cd0396d) | Feb 14, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5JW0... | Notebook    | [df9633e08e](https://linux-hardware.org/?probe=df9633e08e) | Feb 13, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [bec0b9ac1e](https://linux-hardware.org/?probe=bec0b9ac1e) | Feb 13, 2022 |
| Google        | Homestar (rev3)             | Soc         | [313894dec8](https://linux-hardware.org/?probe=313894dec8) | Feb 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7b2a1e633f](https://linux-hardware.org/?probe=7b2a1e633f) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [b5dd380b9a](https://linux-hardware.org/?probe=b5dd380b9a) | Feb 10, 2022 |
| Dell          | Latitude 5480               | Notebook    | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| HP            | 18E7                        | Desktop     | [11c3f1c67f](https://linux-hardware.org/?probe=11c3f1c67f) | Feb 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [f70763fe0a](https://linux-hardware.org/?probe=f70763fe0a) | Feb 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3fa68165ea](https://linux-hardware.org/?probe=3fa68165ea) | Feb 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4346690bc8](https://linux-hardware.org/?probe=4346690bc8) | Feb 06, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [6375ec93db](https://linux-hardware.org/?probe=6375ec93db) | Feb 05, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [1eceff18e2](https://linux-hardware.org/?probe=1eceff18e2) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| Google        | Homestar (rev3)             | Soc         | [58d09ccbf3](https://linux-hardware.org/?probe=58d09ccbf3) | Feb 04, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [4aece000f1](https://linux-hardware.org/?probe=4aece000f1) | Feb 03, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [09497d2017](https://linux-hardware.org/?probe=09497d2017) | Feb 02, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [77baf7aac1](https://linux-hardware.org/?probe=77baf7aac1) | Feb 02, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [4cf4045deb](https://linux-hardware.org/?probe=4cf4045deb) | Feb 01, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | Notebook    | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [182ad67187](https://linux-hardware.org/?probe=182ad67187) | Feb 01, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [6afebcc975](https://linux-hardware.org/?probe=6afebcc975) | Feb 01, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [8fba4698c9](https://linux-hardware.org/?probe=8fba4698c9) | Feb 01, 2022 |
| Lenovo        | ThinkPad W530 2441B88       | Notebook    | [9c15c47f51](https://linux-hardware.org/?probe=9c15c47f51) | Feb 01, 2022 |
| Dell          | Latitude 7490               | Notebook    | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [dcc55138d2](https://linux-hardware.org/?probe=dcc55138d2) | Jan 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | Notebook    | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [a6e928b122](https://linux-hardware.org/?probe=a6e928b122) | Jan 28, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [ee50dc0bb1](https://linux-hardware.org/?probe=ee50dc0bb1) | Jan 27, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0977601aad](https://linux-hardware.org/?probe=0977601aad) | Jan 27, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [267ee0e693](https://linux-hardware.org/?probe=267ee0e693) | Jan 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [a72f036b05](https://linux-hardware.org/?probe=a72f036b05) | Jan 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d6d51a7ce7](https://linux-hardware.org/?probe=d6d51a7ce7) | Jan 26, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S7D300    | Notebook    | [3fcdce23b5](https://linux-hardware.org/?probe=3fcdce23b5) | Jan 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Acer          | NC-E1-572-54208G            | Notebook    | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | Notebook    | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [a920db9f29](https://linux-hardware.org/?probe=a920db9f29) | Jan 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [c64e8bdde9](https://linux-hardware.org/?probe=c64e8bdde9) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | Notebook    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08320d55cd](https://linux-hardware.org/?probe=08320d55cd) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | Notebook    | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [3f0a902b2e](https://linux-hardware.org/?probe=3f0a902b2e) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [0b31274785](https://linux-hardware.org/?probe=0b31274785) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Dell          | Latitude 5420               | Notebook    | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| Notebook      | NS50MU                      | Notebook    | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [77c7eedd86](https://linux-hardware.org/?probe=77c7eedd86) | Jan 15, 2022 |
| Toshiba       | Satellite C55-A-19N         | Notebook    | [b53c0c9b39](https://linux-hardware.org/?probe=b53c0c9b39) | Jan 14, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [ba41989095](https://linux-hardware.org/?probe=ba41989095) | Jan 14, 2022 |
| Toshiba       | Satellite NB10t-A-103       | Notebook    | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [94d85b9f5b](https://linux-hardware.org/?probe=94d85b9f5b) | Jan 12, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| HP            | ProBook 6450b               | Notebook    | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [c0039193bb](https://linux-hardware.org/?probe=c0039193bb) | Jan 09, 2022 |
| HP            | 18E7                        | Desktop     | [2598720ae1](https://linux-hardware.org/?probe=2598720ae1) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b4f5f6f8da](https://linux-hardware.org/?probe=b4f5f6f8da) | Jan 08, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | Notebook    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | Notebook    | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| Lenovo        | 369A SDK0F82993 WIN         | Desktop     | [e1141045bf](https://linux-hardware.org/?probe=e1141045bf) | Jan 08, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5107953369](https://linux-hardware.org/?probe=5107953369) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [b976b5921e](https://linux-hardware.org/?probe=b976b5921e) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| HP            | ProBook 4510s               | Notebook    | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| HP            | ProBook 4510s               | Notebook    | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| Dell          | Latitude 3470               | Notebook    | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d774f42123](https://linux-hardware.org/?probe=d774f42123) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [c5c108c138](https://linux-hardware.org/?probe=c5c108c138) | Jan 03, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Dell          | Latitude 7480               | Notebook    | [24244e5717](https://linux-hardware.org/?probe=24244e5717) | Jan 02, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [94b665863b](https://linux-hardware.org/?probe=94b665863b) | Jan 02, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [5d1e83c959](https://linux-hardware.org/?probe=5d1e83c959) | Jan 01, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [926c4f82d1](https://linux-hardware.org/?probe=926c4f82d1) | Jan 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [1ba0b3e854](https://linux-hardware.org/?probe=1ba0b3e854) | Jan 01, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [90deec9056](https://linux-hardware.org/?probe=90deec9056) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| HP            | ProBook 4540s               | Notebook    | [20af449f2a](https://linux-hardware.org/?probe=20af449f2a) | Dec 29, 2021 |
| HP            | ProBook 4540s               | Notebook    | [99fb3303bb](https://linux-hardware.org/?probe=99fb3303bb) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| HP            | 18E7                        | Desktop     | [8fe0391d59](https://linux-hardware.org/?probe=8fe0391d59) | Dec 28, 2021 |
| HP            | ProLiant DL380e Gen8        | Server      | [a28b637049](https://linux-hardware.org/?probe=a28b637049) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | Notebook    | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | Notebook    | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [dc6fd4bfc7](https://linux-hardware.org/?probe=dc6fd4bfc7) | Dec 25, 2021 |
| HP            | 872E                        | Mini pc     | [84eb03ce6d](https://linux-hardware.org/?probe=84eb03ce6d) | Dec 25, 2021 |
| HP            | 872E                        | Mini pc     | [c2eff247c6](https://linux-hardware.org/?probe=c2eff247c6) | Dec 25, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [62488dea12](https://linux-hardware.org/?probe=62488dea12) | Dec 25, 2021 |
| HP            | 1905                        | Desktop     | [9e2637fa00](https://linux-hardware.org/?probe=9e2637fa00) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [180954acf2](https://linux-hardware.org/?probe=180954acf2) | Dec 23, 2021 |
| ASUSTek       | P5G41-M                     | Desktop     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 245       | 12.23%  |
| Ubuntu 18.04                 | 151       | 7.53%   |
| OpenMandriva 4.2             | 116       | 5.79%   |
| Ubuntu 22.04                 | 91        | 4.54%   |
| OpenMandriva 4.3             | 68        | 3.39%   |
| OpenMandriva 4.50            | 65        | 3.24%   |
| Ubuntu 21.10                 | 38        | 1.9%    |
| Ubuntu 20.10                 | 35        | 1.75%   |
| Fedora 34                    | 35        | 1.75%   |
| Debian 11                    | 33        | 1.65%   |
| Ubuntu 19.10                 | 28        | 1.4%    |
| Linux Mint 20.1              | 28        | 1.4%    |
| Ubuntu 21.04                 | 27        | 1.35%   |
| Arch                         | 27        | 1.35%   |
| Zorin 16                     | 26        | 1.3%    |
| Linux Mint 20                | 26        | 1.3%    |
| Fedora 35                    | 26        | 1.3%    |
| Arch Rolling                 | 26        | 1.3%    |
| Linux Mint 20.2              | 25        | 1.25%   |
| Fedora 32                    | 25        | 1.25%   |
| Ubuntu 19.04                 | 24        | 1.2%    |
| Fedora 33                    | 23        | 1.15%   |
| Linux Mint 20.3              | 22        | 1.1%    |
| Linux Mint 19.3              | 22        | 1.1%    |
| Zorin 15                     | 21        | 1.05%   |
| Ubuntu 22.10                 | 21        | 1.05%   |
| OpenMandriva 23.01           | 21        | 1.05%   |
| Fedora 37                    | 20        | 1%      |
| Linux Mint 21                | 19        | 0.95%   |
| Fedora 36                    | 19        | 0.95%   |
| Fedora 31                    | 18        | 0.9%    |
| openSUSE Tumbleweed-XXXXXXXX | 17        | 0.85%   |
| Manjaro                      | 17        | 0.85%   |
| Linux Mint 21.1              | 17        | 0.85%   |
| Kubuntu 20.04                | 17        | 0.85%   |
| Xubuntu 20.04                | 16        | 0.8%    |
| Pop!_OS 20.04                | 15        | 0.75%   |
| Xubuntu 18.04                | 14        | 0.7%    |
| Debian 10                    | 14        | 0.7%    |
| KDE neon 20.04               | 13        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 637       | 33.79%  |
| OpenMandriva  | 273       | 14.48%  |
| Linux Mint    | 166       | 8.81%   |
| Fedora        | 165       | 8.75%   |
| Debian        | 60        | 3.18%   |
| Arch          | 53        | 2.81%   |
| Zorin         | 51        | 2.71%   |
| Manjaro       | 51        | 2.71%   |
| Xubuntu       | 44        | 2.33%   |
| Pop!_OS       | 41        | 2.18%   |
| ROSA          | 38        | 2.02%   |
| Kubuntu       | 35        | 1.86%   |
| Gentoo        | 34        | 1.8%    |
| openSUSE      | 22        | 1.17%   |
| Lubuntu       | 18        | 0.95%   |
| KDE neon      | 18        | 0.95%   |
| Kali          | 16        | 0.85%   |
| Endless       | 14        | 0.74%   |
| Elementary    | 14        | 0.74%   |
| RHEL          | 13        | 0.69%   |
| Ubuntu MATE   | 12        | 0.64%   |
| Ubuntu Unity  | 10        | 0.53%   |
| ArcoLinux     | 10        | 0.53%   |
| CentOS        | 9         | 0.48%   |
| Void Linux    | 6         | 0.32%   |
| Parrot        | 5         | 0.27%   |
| EndeavourOS   | 5         | 0.27%   |
| ACI           | 5         | 0.27%   |
| SteamOS       | 4         | 0.21%   |
| Rocky Linux   | 4         | 0.21%   |
| LMDE          | 4         | 0.21%   |
| BlackPanther  | 4         | 0.21%   |
| Nobara        | 3         | 0.16%   |
| NixOS         | 3         | 0.16%   |
| Neptune OS    | 3         | 0.16%   |
| MX            | 3         | 0.16%   |
| LinuxFX       | 3         | 0.16%   |
| Ubuntu Budgie | 2         | 0.11%   |
| Garuda Linux  | 2         | 0.11%   |
| Artix         | 2         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 114       | 5.18%   |
| 5.16.7-desktop-1omv4003  | 67        | 3.05%   |
| 5.14.7-desktop-1omv4050  | 55        | 2.5%    |
| 5.4.0-42-generic         | 34        | 1.55%   |
| 5.4.0-58-generic         | 22        | 1%      |
| 5.4.0-52-generic         | 22        | 1%      |
| 5.15.0-46-generic        | 21        | 0.95%   |
| 5.4.0-26-generic         | 20        | 0.91%   |
| 5.15.0-56-generic        | 20        | 0.91%   |
| 6.1.1-desktop-1omv2290   | 18        | 0.82%   |
| 5.15.0-58-generic        | 17        | 0.77%   |
| 5.15.0-52-generic        | 16        | 0.73%   |
| 5.11.0-27-generic        | 16        | 0.73%   |
| 5.3.0-40-generic         | 15        | 0.68%   |
| 5.0.0-37-generic         | 15        | 0.68%   |
| 5.13.0-30-generic        | 14        | 0.64%   |
| 5.4.0-48-generic         | 12        | 0.55%   |
| 5.4.0-40-generic         | 12        | 0.55%   |
| 5.3.0-28-generic         | 12        | 0.55%   |
| 5.15.0-48-generic        | 12        | 0.55%   |
| 5.4.0-65-generic         | 11        | 0.5%    |
| 5.15.0-41-generic        | 11        | 0.5%    |
| 5.4.0-29-generic         | 10        | 0.45%   |
| 5.11.0-37-generic        | 10        | 0.45%   |
| 5.8.0-53-generic         | 9         | 0.41%   |
| 5.4.0-91-generic         | 9         | 0.41%   |
| 5.4.0-37-generic         | 9         | 0.41%   |
| 5.15.0-43-generic        | 9         | 0.41%   |
| 5.10.0-8-amd64           | 9         | 0.41%   |
| 4.15.0-43-generic        | 9         | 0.41%   |
| 5.8.0-59-generic         | 8         | 0.36%   |
| 5.8.0-50-generic         | 8         | 0.36%   |
| 5.4.0-72-generic         | 8         | 0.36%   |
| 5.4.0-56-generic         | 8         | 0.36%   |
| 5.4.0-33-generic         | 8         | 0.36%   |
| 5.3.0-42-generic         | 8         | 0.36%   |
| 5.15.0-53-generic        | 8         | 0.36%   |
| 5.13.0-22-generic        | 8         | 0.36%   |
| 5.13.0-21-generic        | 8         | 0.36%   |
| 5.0.0-32-generic         | 8         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 310       | 15.06%  |
| 5.15.0  | 156       | 7.58%   |
| 5.10.14 | 114       | 5.54%   |
| 4.15.0  | 111       | 5.39%   |
| 5.8.0   | 101       | 4.91%   |
| 5.11.0  | 96        | 4.66%   |
| 5.3.0   | 92        | 4.47%   |
| 5.13.0  | 91        | 4.42%   |
| 5.0.0   | 71        | 3.45%   |
| 5.16.7  | 68        | 3.3%    |
| 4.18.0  | 57        | 2.77%   |
| 5.14.7  | 56        | 2.72%   |
| 5.10.0  | 39        | 1.89%   |
| 5.19.0  | 37        | 1.8%    |
| 6.1.1   | 24        | 1.17%   |
| 4.19.0  | 17        | 0.83%   |
| 3.10.0  | 11        | 0.53%   |
| 6.0.0   | 10        | 0.49%   |
| 4.9.20  | 9         | 0.44%   |
| 5.16.11 | 8         | 0.39%   |
| 6.1.0   | 7         | 0.34%   |
| 5.17.0  | 7         | 0.34%   |
| 5.15.12 | 7         | 0.34%   |
| 5.11.12 | 7         | 0.34%   |
| 6.0.12  | 6         | 0.29%   |
| 5.9.16  | 6         | 0.29%   |
| 5.9.0   | 6         | 0.29%   |
| 5.18.12 | 6         | 0.29%   |
| 5.14.0  | 6         | 0.29%   |
| 5.12.4  | 6         | 0.29%   |
| 5.10.74 | 6         | 0.29%   |
| 4.4.0   | 6         | 0.29%   |
| 4.13.0  | 6         | 0.29%   |
| 6.2.6   | 5         | 0.24%   |
| 5.8.18  | 5         | 0.24%   |
| 5.17.5  | 5         | 0.24%   |
| 5.14.10 | 5         | 0.24%   |
| 6.1.8   | 4         | 0.19%   |
| 6.1.12  | 4         | 0.19%   |
| 5.7.0   | 4         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 334       | 16.36%  |
| 5.15    | 204       | 10%     |
| 5.10    | 196       | 9.6%    |
| 5.8     | 134       | 6.57%   |
| 5.11    | 129       | 6.32%   |
| 4.15    | 113       | 5.54%   |
| 5.13    | 108       | 5.29%   |
| 5.3     | 103       | 5.05%   |
| 5.16    | 98        | 4.8%    |
| 5.14    | 81        | 3.97%   |
| 5.0     | 77        | 3.77%   |
| 5.19    | 60        | 2.94%   |
| 4.18    | 60        | 2.94%   |
| 6.1     | 57        | 2.79%   |
| 6.0     | 36        | 1.76%   |
| 5.17    | 34        | 1.67%   |
| 5.9     | 25        | 1.22%   |
| 5.18    | 24        | 1.18%   |
| 5.6     | 23        | 1.13%   |
| 4.19    | 22        | 1.08%   |
| 5.12    | 21        | 1.03%   |
| 4.9     | 20        | 0.98%   |
| 6.2     | 14        | 0.69%   |
| 5.7     | 14        | 0.69%   |
| 3.10    | 12        | 0.59%   |
| 5.5     | 11        | 0.54%   |
| 4.4     | 6         | 0.29%   |
| 4.13    | 6         | 0.29%   |
| 5.1     | 4         | 0.2%    |
| 5.2     | 3         | 0.15%   |
| 4.17    | 3         | 0.15%   |
| 4.14    | 3         | 0.15%   |
| 4.1     | 2         | 0.1%    |
| 4.8     | 1         | 0.05%   |
| 4.20    | 1         | 0.05%   |
| 4.10    | 1         | 0.05%   |
| 2.6     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1782      | 96.06%  |
| i686    | 61        | 3.29%   |
| aarch64 | 10        | 0.54%   |
| armv8l  | 1         | 0.05%   |
| armv7l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 764       | 39.87%  |
| KDE5              | 419       | 21.87%  |
| Unknown           | 260       | 13.57%  |
| XFCE              | 141       | 7.36%   |
| X-Cinnamon        | 96        | 5.01%   |
| KDE               | 47        | 2.45%   |
| MATE              | 45        | 2.35%   |
| Cinnamon          | 34        | 1.77%   |
| LXQt              | 17        | 0.89%   |
| Pantheon          | 14        | 0.73%   |
| KDE4              | 13        | 0.68%   |
| Unity             | 11        | 0.57%   |
| LXDE              | 10        | 0.52%   |
| GNOME Flashback   | 10        | 0.52%   |
| i3                | 6         | 0.31%   |
| openbox           | 5         | 0.26%   |
| Budgie            | 4         | 0.21%   |
| awesome           | 4         | 0.21%   |
| sway              | 3         | 0.16%   |
| qtile             | 3         | 0.16%   |
| Yaru:ubuntu:GNOME | 1         | 0.05%   |
| XSession          | 1         | 0.05%   |
| xinitrc           | 1         | 0.05%   |
| xinit-compat      | 1         | 0.05%   |
| GNUstep           | 1         | 0.05%   |
| GNOME Classic     | 1         | 0.05%   |
| Enlightenment     | 1         | 0.05%   |
| DWM               | 1         | 0.05%   |
| custom            | 1         | 0.05%   |
| Core              | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1439      | 75.66%  |
| Wayland | 291       | 15.3%   |
| Unknown | 142       | 7.47%   |
| Tty     | 30        | 1.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 889       | 46.28%  |
| SDDM    | 403       | 20.98%  |
| GDM     | 211       | 10.98%  |
| GDM3    | 178       | 9.27%   |
| LightDM | 144       | 7.5%    |
| TDM     | 71        | 3.7%    |
| KDM     | 12        | 0.62%   |
| XDM     | 5         | 0.26%   |
| SLiM    | 4         | 0.21%   |
| LXDM    | 2         | 0.1%    |
| Ly      | 1         | 0.05%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| cs_CZ   | 1000      | 52.85%  |
| en_US   | 535       | 28.28%  |
| Unknown | 227       | 12%     |
| en_GB   | 41        | 2.17%   |
| C       | 31        | 1.64%   |
| ru_RU   | 20        | 1.06%   |
| sk_SK   | 9         | 0.48%   |
| POSIX   | 5         | 0.26%   |
| pl_PL   | 3         | 0.16%   |
| it_IT   | 3         | 0.16%   |
| fr_FR   | 3         | 0.16%   |
| de_DE   | 3         | 0.16%   |
| uk_UA   | 1         | 0.05%   |
| ro_RO   | 1         | 0.05%   |
| pt_PT   | 1         | 0.05%   |
| fi_FI   | 1         | 0.05%   |
| es_ES   | 1         | 0.05%   |
| en_NG   | 1         | 0.05%   |
| en_CA   | 1         | 0.05%   |
| en_AU   | 1         | 0.05%   |
| en_150  | 1         | 0.05%   |
| el_GR   | 1         | 0.05%   |
| C.UTF8  | 1         | 0.05%   |
| bg_BG   | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1033      | 54.4%   |
| EFI  | 866       | 45.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1294      | 68.32%  |
| Overlay  | 293       | 15.47%  |
| Btrfs    | 166       | 8.76%   |
| Unknown  | 64        | 3.38%   |
| Xfs      | 49        | 2.59%   |
| Zfs      | 11        | 0.58%   |
| Ext2     | 5         | 0.26%   |
| Ext3     | 4         | 0.21%   |
| Tmpfs    | 2         | 0.11%   |
| Reiserfs | 2         | 0.11%   |
| F2fs     | 2         | 0.11%   |
| Aufs     | 2         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 926       | 48.99%  |
| GPT     | 645       | 34.13%  |
| MBR     | 319       | 16.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1638      | 87.27%  |
| Yes       | 239       | 12.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1238      | 65.47%  |
| Yes       | 653       | 34.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 406       | 21.9%   |
| Lenovo                         | 340       | 18.34%  |
| Hewlett-Packard                | 285       | 15.37%  |
| Dell                           | 190       | 10.25%  |
| Gigabyte Technology            | 128       | 6.9%    |
| Acer                           | 119       | 6.42%   |
| MSI                            | 114       | 6.15%   |
| ASRock                         | 50        | 2.7%    |
| Intel                          | 28        | 1.51%   |
| UMAX                           | 20        | 1.08%   |
| Toshiba                        | 16        | 0.86%   |
| Fujitsu                        | 16        | 0.86%   |
| Sony                           | 14        | 0.76%   |
| Raspberry Pi Foundation        | 10        | 0.54%   |
| Unknown                        | 9         | 0.49%   |
| HUAWEI                         | 7         | 0.38%   |
| Fujitsu Siemens                | 7         | 0.38%   |
| Apple                          | 7         | 0.38%   |
| Supermicro                     | 5         | 0.27%   |
| Pegatron                       | 5         | 0.27%   |
| Google                         | 5         | 0.27%   |
| AMI                            | 5         | 0.27%   |
| Valve                          | 4         | 0.22%   |
| Timi                           | 4         | 0.22%   |
| Packard Bell                   | 4         | 0.22%   |
| Microsoft                      | 4         | 0.22%   |
| ZOTAC                          | 3         | 0.16%   |
| TUXEDO                         | 3         | 0.16%   |
| Notebook                       | 2         | 0.11%   |
| Insyde                         | 2         | 0.11%   |
| IBM                            | 2         | 0.11%   |
| Foxconn                        | 2         | 0.11%   |
| Dynabook                       | 2         | 0.11%   |
| Clientron                      | 2         | 0.11%   |
| Chuwi                          | 2         | 0.11%   |
| Biostar                        | 2         | 0.11%   |
| Alienware                      | 2         | 0.11%   |
| Wortmann AG                    | 1         | 0.05%   |
| Standard                       | 1         | 0.05%   |
| SmbiosType1_SystemManufacturer | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS UX31E                            | 117       | 6.31%   |
| Unknown                               | 12        | 0.65%   |
| ASUS All Series                       | 11        | 0.59%   |
| MSI MS-7C91                           | 8         | 0.43%   |
| MSI MS-7693                           | 7         | 0.38%   |
| MSI MS-7A34                           | 6         | 0.32%   |
| HP ProBook 455 G7                     | 6         | 0.32%   |
| RPi Raspberry Pi                      | 5         | 0.27%   |
| MSI MS-7C02                           | 5         | 0.27%   |
| Lenovo ThinkPad E14 20RA001LMC        | 5         | 0.27%   |
| HP ProLiant DL380e Gen8               | 5         | 0.27%   |
| HP ProBook 4530s                      | 5         | 0.27%   |
| HP ProBook 450 G5                     | 5         | 0.27%   |
| Dell Latitude E6400                   | 5         | 0.27%   |
| Dell Latitude 5401                    | 5         | 0.27%   |
| Valve Jupiter                         | 4         | 0.22%   |
| HP ProDesk 405 G6 Desktop Mini PC     | 4         | 0.22%   |
| HP ProBook 4540s                      | 4         | 0.22%   |
| HP Pavilion dv7                       | 4         | 0.22%   |
| HP Notebook                           | 4         | 0.22%   |
| HP EliteBook 840 G6                   | 4         | 0.22%   |
| HP EliteBook 840 G3                   | 4         | 0.22%   |
| HP 250 G6 Notebook PC                 | 4         | 0.22%   |
| Dell XPS 15 7590                      | 4         | 0.22%   |
| Dell Precision M6500                  | 4         | 0.22%   |
| Dell Latitude E6420                   | 4         | 0.22%   |
| Acer Extensa 5620                     | 4         | 0.22%   |
| MSI MS-7592                           | 3         | 0.16%   |
| Lenovo Z50-75 80EC                    | 3         | 0.16%   |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00  | 3         | 0.16%   |
| Lenovo IdeaPad S130-11IGM 81J1        | 3         | 0.16%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL | 3         | 0.16%   |
| Lenovo IdeaPad 5 14ARE05 81YM         | 3         | 0.16%   |
| HP ProBook 4510s                      | 3         | 0.16%   |
| HP Pavilion dv6                       | 3         | 0.16%   |
| HP Laptop 15-bw0xx                    | 3         | 0.16%   |
| HP ENVY x360 Convertible 15-cn0xxx    | 3         | 0.16%   |
| HP EliteBook x360 1030 G2             | 3         | 0.16%   |
| HP EliteBook 855 G7 Notebook PC       | 3         | 0.16%   |
| HP EliteBook 850 G6                   | 3         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 162       | 8.74%   |
| ASUS UX31E         | 117       | 6.31%   |
| Dell Latitude      | 79        | 4.26%   |
| Acer Aspire        | 69        | 3.72%   |
| Lenovo IdeaPad     | 62        | 3.34%   |
| HP ProBook         | 60        | 3.24%   |
| HP EliteBook       | 59        | 3.18%   |
| HP Compaq          | 33        | 1.78%   |
| HP Pavilion        | 30        | 1.62%   |
| ASUS ROG           | 27        | 1.46%   |
| ASUS PRIME         | 27        | 1.46%   |
| Dell Inspiron      | 25        | 1.35%   |
| Dell XPS           | 23        | 1.24%   |
| Dell Precision     | 23        | 1.24%   |
| Lenovo Yoga        | 22        | 1.19%   |
| Dell OptiPlex      | 19        | 1.02%   |
| ASUS TUF           | 18        | 0.97%   |
| Toshiba Satellite  | 15        | 0.81%   |
| UMAX VisionBook    | 14        | 0.76%   |
| Lenovo ThinkCentre | 14        | 0.76%   |
| Acer Extensa       | 14        | 0.76%   |
| Lenovo Legion      | 13        | 0.7%    |
| HP ENVY            | 13        | 0.7%    |
| ASUS Zenbook       | 13        | 0.7%    |
| Acer TravelMate    | 13        | 0.7%    |
| HP Laptop          | 12        | 0.65%   |
| ASUS VivoBook      | 12        | 0.65%   |
| Unknown            | 12        | 0.65%   |
| ASUS All           | 11        | 0.59%   |
| RPi Raspberry      | 10        | 0.54%   |
| HP ProDesk         | 10        | 0.54%   |
| Dell Vostro        | 10        | 0.54%   |
| HP ZBook           | 9         | 0.49%   |
| Fujitsu LIFEBOOK   | 9         | 0.49%   |
| Acer Swift         | 9         | 0.49%   |
| MSI MS-7C91        | 8         | 0.43%   |
| Lenovo ThinkBook   | 8         | 0.43%   |
| HP 250             | 8         | 0.43%   |
| MSI MS-7693        | 7         | 0.38%   |
| Gigabyte B450      | 7         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 227       | 12.24%  |
| 2020    | 181       | 9.76%   |
| 2018    | 165       | 8.9%    |
| 2019    | 154       | 8.31%   |
| 2017    | 127       | 6.85%   |
| 2012    | 127       | 6.85%   |
| 2021    | 125       | 6.74%   |
| 2014    | 111       | 5.99%   |
| 2013    | 97        | 5.23%   |
| 2015    | 95        | 5.12%   |
| 2008    | 90        | 4.85%   |
| 2016    | 73        | 3.94%   |
| 2010    | 73        | 3.94%   |
| 2009    | 65        | 3.51%   |
| 2007    | 64        | 3.45%   |
| 2022    | 30        | 1.62%   |
| 2006    | 25        | 1.35%   |
| Unknown | 12        | 0.65%   |
| 2005    | 8         | 0.43%   |
| 2004    | 4         | 0.22%   |
| 2000    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1125      | 60.68%  |
| Desktop        | 588       | 31.72%  |
| Convertible    | 55        | 2.97%   |
| Mini pc        | 27        | 1.46%   |
| Tablet         | 16        | 0.86%   |
| All in one     | 16        | 0.86%   |
| Server         | 15        | 0.81%   |
| System on chip | 11        | 0.59%   |
| Phone          | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1697      | 90.75%  |
| Enabled  | 173       | 9.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1849      | 99.73%  |
| Yes  | 5         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 489       | 25.86%  |
| 4.01-8.0        | 344       | 18.19%  |
| 8.01-16.0       | 329       | 17.4%   |
| 16.01-24.0      | 321       | 16.98%  |
| 32.01-64.0      | 183       | 9.68%   |
| 1.01-2.0        | 100       | 5.29%   |
| 64.01-256.0     | 38        | 2.01%   |
| 24.01-32.0      | 33        | 1.75%   |
| 2.01-3.0        | 33        | 1.75%   |
| 0.51-1.0        | 17        | 0.9%    |
| More than 256.0 | 2         | 0.11%   |
| 0.01-0.5        | 2         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 783       | 38.18%  |
| 2.01-3.0   | 440       | 21.45%  |
| 4.01-8.0   | 305       | 14.87%  |
| 3.01-4.0   | 227       | 11.07%  |
| 0.51-1.0   | 135       | 6.58%   |
| 8.01-16.0  | 108       | 5.27%   |
| 0.01-0.5   | 26        | 1.27%   |
| 16.01-24.0 | 16        | 0.78%   |
| 32.01-64.0 | 6         | 0.29%   |
| 24.01-32.0 | 4         | 0.2%    |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1254      | 65.52%  |
| 2      | 399       | 20.85%  |
| 3      | 126       | 6.58%   |
| 4      | 52        | 2.72%   |
| 5      | 30        | 1.57%   |
| 0      | 24        | 1.25%   |
| 6      | 14        | 0.73%   |
| 7      | 10        | 0.52%   |
| 8      | 4         | 0.21%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1208      | 64.63%  |
| Yes       | 661       | 35.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1616      | 86.74%  |
| No        | 247       | 13.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1380      | 74.07%  |
| No        | 483       | 25.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1054      | 56.18%  |
| No        | 822       | 43.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Czechia | 1854      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Prague               | 726       | 37.69%  |
| Brno                 | 170       | 8.83%   |
| Ostrava              | 52        | 2.7%    |
| Pilsen               | 40        | 2.08%   |
| Liberec              | 29        | 1.51%   |
| Olomouc              | 25        | 1.3%    |
| Hradec Králové     | 25        | 1.3%    |
| České Budějovice  | 25        | 1.3%    |
| Pardubice            | 23        | 1.19%   |
| Havířov            | 17        | 0.88%   |
| Zlín                | 16        | 0.83%   |
| Znojmo               | 14        | 0.73%   |
| Chomutov             | 13        | 0.67%   |
| Most                 | 12        | 0.62%   |
| Jihlava              | 10        | 0.52%   |
| Přerov              | 9         | 0.47%   |
| Karlovy Vary         | 9         | 0.47%   |
| Ústí nad Labem     | 8         | 0.42%   |
| Mladá Boleslav      | 8         | 0.42%   |
| Frýdek-Místek      | 8         | 0.42%   |
| Uherské Hradiště  | 7         | 0.36%   |
| Třebíč            | 7         | 0.36%   |
| Teplice              | 7         | 0.36%   |
| Praha 10             | 7         | 0.36%   |
| Ponetovice           | 7         | 0.36%   |
| Opava                | 7         | 0.36%   |
| Litoměřice         | 7         | 0.36%   |
| Kladno               | 7         | 0.36%   |
| Česká Lípa        | 7         | 0.36%   |
| Tábor               | 6         | 0.31%   |
| Roznov pod Radhostem | 6         | 0.31%   |
| Příbram            | 6         | 0.31%   |
| Mariánské Lázně  | 6         | 0.31%   |
| Kralupy nad Vltavou  | 6         | 0.31%   |
| Český Těšín     | 6         | 0.31%   |
| As                   | 6         | 0.31%   |
| Uvaly                | 5         | 0.26%   |
| Rumburk              | 5         | 0.26%   |
| Prelouc              | 5         | 0.26%   |
| Odolena Voda         | 5         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 422       | 677    | 16.4%   |
| Samsung Electronics       | 416       | 578    | 16.17%  |
| Seagate                   | 368       | 563    | 14.3%   |
| SanDisk                   | 196       | 210    | 7.62%   |
| Kingston                  | 177       | 219    | 6.88%   |
| Toshiba                   | 151       | 184    | 5.87%   |
| Unknown                   | 108       | 151    | 4.2%    |
| Hitachi                   | 80        | 93     | 3.11%   |
| SK hynix                  | 69        | 83     | 2.68%   |
| A-DATA Technology         | 68        | 82     | 2.64%   |
| Intel                     | 63        | 75     | 2.45%   |
| Crucial                   | 59        | 74     | 2.29%   |
| HGST                      | 51        | 62     | 1.98%   |
| Micron Technology         | 46        | 63     | 1.79%   |
| Patriot                   | 43        | 54     | 1.67%   |
| Transcend                 | 18        | 27     | 0.7%    |
| KIOXIA                    | 15        | 23     | 0.58%   |
| Apacer                    | 15        | 19     | 0.58%   |
| Phison                    | 14        | 26     | 0.54%   |
| Gigabyte Technology       | 11        | 20     | 0.43%   |
| Silicon Motion            | 10        | 10     | 0.39%   |
| OCZ                       | 10        | 33     | 0.39%   |
| Verbatim                  | 9         | 9      | 0.35%   |
| Maxtor                    | 9         | 13     | 0.35%   |
| LITEONIT                  | 9         | 11     | 0.35%   |
| Fujitsu                   | 9         | 10     | 0.35%   |
| China                     | 9         | 14     | 0.35%   |
| Unknown                   | 8         | 9      | 0.31%   |
| XPG                       | 7         | 14     | 0.27%   |
| LITEON                    | 7         | 8      | 0.27%   |
| GOODRAM                   | 7         | 10     | 0.27%   |
| JMicron Technology        | 6         | 7      | 0.23%   |
| Phison Electronics        | 5         | 5      | 0.19%   |
| Micron/Crucial Technology | 5         | 5      | 0.19%   |
| Corsair                   | 5         | 5      | 0.19%   |
| Apple                     | 5         | 8      | 0.19%   |
| UMAX                      | 4         | 4      | 0.16%   |
| Realtek Semiconductor     | 4         | 7      | 0.16%   |
| ASMedia                   | 4         | 6      | 0.16%   |
| Team                      | 3         | 3      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                              | 116       | 4.09%   |
| Samsung SSD 860 EVO 500GB                           | 28        | 0.99%   |
| Kingston SA400S37240G 240GB SSD                     | 27        | 0.95%   |
| Samsung NVMe SSD Drive 512GB                        | 24        | 0.85%   |
| Unknown MMC Card  64GB                              | 20        | 0.71%   |
| Kingston SA400S37120G 120GB SSD                     | 20        | 0.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 19        | 0.67%   |
| Samsung SSD 850 EVO 250GB                           | 19        | 0.67%   |
| Unknown MMC Card  32GB                              | 18        | 0.64%   |
| Kingston SA400S37480G 480GB SSD                     | 18        | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB                      | 17        | 0.6%    |
| HGST HTS721010A9E630 1TB                            | 17        | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 16        | 0.56%   |
| Samsung NVMe SSD Drive 500GB                        | 16        | 0.56%   |
| Toshiba NVMe SSD Drive 256GB                        | 13        | 0.46%   |
| Seagate ST3500418AS 500GB                           | 13        | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB                      | 13        | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB                      | 13        | 0.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 13        | 0.46%   |
| Samsung SSD 860 EVO 1TB                             | 12        | 0.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 12        | 0.42%   |
| Patriot Burst 120GB SSD                             | 12        | 0.42%   |
| Seagate ST500LT012-1DG142 500GB                     | 11        | 0.39%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                      | 11        | 0.39%   |
| Patriot Burst 480GB SSD                             | 11        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                    | 11        | 0.39%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 10        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 10        | 0.35%   |
| Seagate ST500DM002-1BD142 500GB                     | 10        | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 10        | 0.35%   |
| Samsung SSD 850 EVO 500GB                           | 10        | 0.35%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 9         | 0.32%   |
| Unknown MMC Card  128GB                             | 9         | 0.32%   |
| Toshiba MQ01ABF050 500GB                            | 9         | 0.32%   |
| Toshiba MQ01ABD100 1TB                              | 9         | 0.32%   |
| SK hynix NVMe SSD Drive 512GB                       | 9         | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                        | 9         | 0.32%   |
| Samsung SSD 970 EVO 1TB                             | 9         | 0.32%   |
| Kingston SHFS37A120G 120GB SSD                      | 9         | 0.32%   |
| HGST HTS725050A7E630 500GB                          | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 360       | 548    | 36.62%  |
| WDC                 | 322       | 527    | 32.76%  |
| Toshiba             | 91        | 100    | 9.26%   |
| Hitachi             | 80        | 93     | 8.14%   |
| HGST                | 51        | 62     | 5.19%   |
| Samsung Electronics | 46        | 69     | 4.68%   |
| Maxtor              | 9         | 13     | 0.92%   |
| Fujitsu             | 9         | 10     | 0.92%   |
| Unknown             | 4         | 4      | 0.41%   |
| pqi                 | 2         | 2      | 0.2%    |
| ASMedia             | 2         | 3      | 0.2%    |
| USB3.0              | 1         | 1      | 0.1%    |
| SABRENT             | 1         | 1      | 0.1%    |
| IBM/Hitachi         | 1         | 1      | 0.1%    |
| External            | 1         | 1      | 0.1%    |
| ASUSTOR             | 1         | 1      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |
| Apple               | 1         | 4      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 172       | 217    | 19.15%  |
| SanDisk             | 154       | 160    | 17.15%  |
| Kingston            | 139       | 177    | 15.48%  |
| WDC                 | 76        | 99     | 8.46%   |
| A-DATA Technology   | 63        | 75     | 7.02%   |
| Crucial             | 55        | 70     | 6.12%   |
| Patriot             | 42        | 53     | 4.68%   |
| Intel               | 25        | 29     | 2.78%   |
| Micron Technology   | 22        | 34     | 2.45%   |
| Transcend           | 17        | 24     | 1.89%   |
| Apacer              | 15        | 19     | 1.67%   |
| SK hynix            | 14        | 15     | 1.56%   |
| Toshiba             | 13        | 16     | 1.45%   |
| Verbatim            | 9         | 9      | 1%      |
| LITEONIT            | 9         | 11     | 1%      |
| China               | 9         | 14     | 1%      |
| OCZ                 | 8         | 15     | 0.89%   |
| LITEON              | 6         | 7      | 0.67%   |
| GOODRAM             | 6         | 9      | 0.67%   |
| Gigabyte Technology | 5         | 11     | 0.56%   |
| UMAX                | 4         | 4      | 0.45%   |
| Seagate             | 4         | 4      | 0.45%   |
| JMicron Technology  | 3         | 3      | 0.33%   |
| Apple               | 3         | 3      | 0.33%   |
| Unknown             | 2         | 7      | 0.22%   |
| Team                | 2         | 2      | 0.22%   |
| SPCC                | 2         | 2      | 0.22%   |
| WDC WDS1            | 1         | 1      | 0.11%   |
| UMIS                | 1         | 1      | 0.11%   |
| TO Exter            | 1         | 2      | 0.11%   |
| TCSUNBOW            | 1         | 1      | 0.11%   |
| ShanDianZhe         | 1         | 1      | 0.11%   |
| Phison              | 1         | 1      | 0.11%   |
| Netac               | 1         | 1      | 0.11%   |
| Mushkin             | 1         | 1      | 0.11%   |
| Linux               | 1         | 1      | 0.11%   |
| Kingchuxing         | 1         | 1      | 0.11%   |
| Innodisk            | 1         | 1      | 0.11%   |
| HS-SSD-C100         | 1         | 1      | 0.11%   |
| Hewlett-Packard     | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 836       | 1441   | 35.86%  |
| SSD     | 807       | 1109   | 34.62%  |
| NVMe    | 561       | 805    | 24.07%  |
| MMC     | 114       | 156    | 4.89%   |
| Unknown | 13        | 17     | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1368      | 2481   | 64.71%  |
| NVMe | 560       | 804    | 26.49%  |
| MMC  | 114       | 156    | 5.39%   |
| SAS  | 72        | 87     | 3.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1122      | 1625   | 65.23%  |
| 0.51-1.0   | 401       | 572    | 23.31%  |
| 1.01-2.0   | 96        | 185    | 5.58%   |
| 3.01-4.0   | 33        | 45     | 1.92%   |
| 2.01-3.0   | 28        | 41     | 1.63%   |
| 4.01-10.0  | 27        | 58     | 1.57%   |
| 10.01-20.0 | 13        | 24     | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 494       | 25.33%  |
| 251-500        | 401       | 20.56%  |
| 1-20           | 283       | 14.51%  |
| 501-1000       | 231       | 11.85%  |
| 51-100         | 145       | 7.44%   |
| 1001-2000      | 127       | 6.51%   |
| Unknown        | 81        | 4.15%   |
| 21-50          | 77        | 3.95%   |
| More than 3000 | 76        | 3.9%    |
| 2001-3000      | 35        | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 886       | 43.88%  |
| 21-50          | 257       | 12.73%  |
| 101-250        | 244       | 12.09%  |
| 51-100         | 198       | 9.81%   |
| 251-500        | 149       | 7.38%   |
| 501-1000       | 94        | 4.66%   |
| Unknown        | 81        | 4.01%   |
| 1001-2000      | 52        | 2.58%   |
| More than 3000 | 39        | 1.93%   |
| 2001-3000      | 19        | 0.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                | 116       | 116    | 43.61%  |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 1.5%    |
| WDC WD60EFRX-68L0BN1 6TB              | 2         | 3      | 0.75%   |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 0.75%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 2         | 3      | 0.75%   |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.75%   |
| Seagate ST3160318AS 160GB             | 2         | 2      | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 3      | 0.75%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 2      | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 0.75%   |
| Micron Technology 1100 SATA 256GB SSD | 2         | 2      | 0.75%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1      | 0.38%   |
| WDC WD800BB-00JHA0 80GB               | 1         | 1      | 0.38%   |
| WDC WD7500BPVT-22HXZT3 752GB          | 1         | 1      | 0.38%   |
| WDC WD7500AADS-00M2B0 752GB           | 1         | 1      | 0.38%   |
| WDC WD6400BPVT-60HXZT1 640GB          | 1         | 1      | 0.38%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.38%   |
| WDC WD5000AAKS-00V0A0 500GB           | 1         | 1      | 0.38%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.38%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 0.38%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.38%   |
| WDC WD2502ABYS-02B7A0 256GB           | 1         | 1      | 0.38%   |
| WDC WD2500BPVT-22JJ5T0 250GB          | 1         | 1      | 0.38%   |
| WDC WD2500BEVS-22UST0 250GB           | 1         | 1      | 0.38%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1         | 1      | 0.38%   |
| WDC WD2500AAKX-60U6AA0 250GB          | 1         | 1      | 0.38%   |
| WDC WD2500AAKX-603CA0 250GB           | 1         | 1      | 0.38%   |
| WDC WD2500AAKX-083CA1 250GB           | 1         | 1      | 0.38%   |
| WDC WD2500AAKS-00VSA0 250GB           | 1         | 1      | 0.38%   |
| WDC WD2500AAJS-08L7A0 250GB           | 1         | 2      | 0.38%   |
| WDC WD20EARX-008FB0 2TB               | 1         | 2      | 0.38%   |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 1      | 0.38%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 0.38%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1         | 1      | 0.38%   |
| WDC WD10EZEX-75M2NA0 1TB              | 1         | 1      | 0.38%   |
| WDC WD10EZEX-35M2NA0 1TB              | 1         | 1      | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk               | 118       | 118    | 45.04%  |
| Seagate               | 39        | 49     | 14.89%  |
| WDC                   | 31        | 37     | 11.83%  |
| Hitachi               | 15        | 15     | 5.73%   |
| Samsung Electronics   | 13        | 14     | 4.96%   |
| HGST                  | 10        | 10     | 3.82%   |
| Toshiba               | 9         | 10     | 3.44%   |
| Kingston              | 6         | 6      | 2.29%   |
| SK hynix              | 4         | 5      | 1.53%   |
| Micron Technology     | 3         | 3      | 1.15%   |
| Crucial               | 3         | 3      | 1.15%   |
| A-DATA Technology     | 3         | 5      | 1.15%   |
| Intel                 | 2         | 2      | 0.76%   |
| Realtek Semiconductor | 1         | 4      | 0.38%   |
| Maxtor                | 1         | 1      | 0.38%   |
| LITEONIT              | 1         | 1      | 0.38%   |
| IBM/Hitachi           | 1         | 1      | 0.38%   |
| Fujitsu               | 1         | 1      | 0.38%   |
| China                 | 1         | 1      | 0.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 49     | 35.45%  |
| WDC                 | 27        | 32     | 24.55%  |
| Hitachi             | 15        | 15     | 13.64%  |
| HGST                | 10        | 10     | 9.09%   |
| Toshiba             | 9         | 10     | 8.18%   |
| Samsung Electronics | 7         | 7      | 6.36%   |
| Maxtor              | 1         | 1      | 0.91%   |
| IBM/Hitachi         | 1         | 1      | 0.91%   |
| Fujitsu             | 1         | 1      | 0.91%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 147       | 149    | 56.32%  |
| HDD  | 108       | 126    | 41.38%  |
| NVMe | 6         | 11     | 2.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 2         | 3      | 66.67%  |
| Unknown 00000  16GB       | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 66.67%  |
| Unknown | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1040      | 2057   | 52.45%  |
| Works    | 682       | 1181   | 34.39%  |
| Malfunc  | 258       | 286    | 13.01%  |
| Failed   | 3         | 4      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1218      | 53.19%  |
| AMD                              | 364       | 15.9%   |
| Samsung Electronics              | 223       | 9.74%   |
| SanDisk                          | 77        | 3.36%   |
| SK hynix                         | 50        | 2.18%   |
| Toshiba America Info Systems     | 46        | 2.01%   |
| Kingston Technology Company      | 41        | 1.79%   |
| JMicron Technology               | 31        | 1.35%   |
| Phison Electronics               | 28        | 1.22%   |
| ASMedia Technology               | 26        | 1.14%   |
| Nvidia                           | 25        | 1.09%   |
| Micron Technology                | 24        | 1.05%   |
| Marvell Technology Group         | 24        | 1.05%   |
| KIOXIA                           | 18        | 0.79%   |
| Silicon Motion                   | 15        | 0.66%   |
| ADATA Technology                 | 13        | 0.57%   |
| VIA Technologies                 | 8         | 0.35%   |
| Micron/Crucial Technology        | 8         | 0.35%   |
| Hewlett-Packard                  | 6         | 0.26%   |
| Seagate Technology               | 5         | 0.22%   |
| Silicon Image                    | 4         | 0.17%   |
| Realtek Semiconductor            | 4         | 0.17%   |
| Union Memory (Shenzhen)          | 3         | 0.13%   |
| Solid State Storage Technology   | 3         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.13%   |
| LSI Logic / Symbios Logic        | 3         | 0.13%   |
| Lite-On Technology               | 3         | 0.13%   |
| Adaptec                          | 3         | 0.13%   |
| OCZ Technology Group             | 2         | 0.09%   |
| Lenovo                           | 2         | 0.09%   |
| Integrated Technology Express    | 2         | 0.09%   |
| Western Digital                  | 1         | 0.04%   |
| Promise Technology               | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Chelsio Communications           | 1         | 0.04%   |
| Broadcom / LSI                   | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |
| 3ware                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 232       | 8.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 175       | 6.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 111       | 4.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 86        | 3.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 72        | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 69        | 2.59%   |
| Samsung NVMe SSD Controller 980                                                  | 58        | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 54        | 2.02%   |
| AMD 400 Series Chipset SATA Controller                                           | 46        | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 44        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 44        | 1.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 40        | 1.5%    |
| Intel Volume Management Device NVMe RAID Controller                              | 39        | 1.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 39        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 38        | 1.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 35        | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 35        | 1.31%   |
| AMD 500 Series Chipset SATA Controller                                           | 33        | 1.24%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 32        | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 30        | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 29        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 29        | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 28        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 28        | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 26        | 0.97%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 25        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 25        | 0.94%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 25        | 0.94%   |
| Micron NVMe Storage Controller                                                   | 24        | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                            | 24        | 0.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 24        | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 22        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 20        | 0.75%   |
| JMicron JMB363 SATA/IDE Controller                                               | 20        | 0.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 20        | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 20        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 20        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 19        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 18        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1330      | 57.18%  |
| NVMe | 568       | 24.42%  |
| IDE  | 288       | 12.38%  |
| RAID | 131       | 5.63%   |
| SAS  | 5         | 0.21%   |
| SCSI | 4         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1382      | 74.54%  |
| AMD      | 460       | 24.81%  |
| ARM      | 11        | 0.59%   |
| QUALCOMM | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 117       | 6.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 22        | 1.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 17        | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 17        | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 0.81%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 15        | 0.81%   |
| AMD Ryzen 5 3600 6-Core Processor             | 15        | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 0.75%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 0.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 13        | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 11        | 0.59%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 11        | 0.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 0.59%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 11        | 0.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 10        | 0.54%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 10        | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 0.54%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 0.54%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 10        | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 9         | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.48%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.48%   |
| ARM Processor                                 | 9         | 0.48%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 9         | 0.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 8         | 0.43%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 8         | 0.43%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.43%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.43%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 8         | 0.43%   |
| AMD FX-8350 Eight-Core Processor              | 8         | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 411       | 22.06%  |
| Intel Core i5           | 334       | 17.93%  |
| AMD Ryzen 5             | 119       | 6.39%   |
| Intel Core 2 Duo        | 112       | 6.01%   |
| Intel Celeron           | 109       | 5.85%   |
| Intel Core i3           | 99        | 5.31%   |
| Other                   | 97        | 5.21%   |
| AMD Ryzen 7             | 76        | 4.08%   |
| Intel Pentium           | 58        | 3.11%   |
| Intel Atom              | 37        | 1.99%   |
| Intel Xeon              | 35        | 1.88%   |
| AMD FX                  | 35        | 1.88%   |
| AMD Ryzen 7 PRO         | 25        | 1.34%   |
| AMD Ryzen 9             | 23        | 1.23%   |
| Intel Pentium Dual-Core | 21        | 1.13%   |
| AMD A4                  | 16        | 0.86%   |
| AMD A8                  | 15        | 0.81%   |
| AMD Ryzen 3             | 14        | 0.75%   |
| AMD A6                  | 14        | 0.75%   |
| Intel Core 2            | 13        | 0.7%    |
| Intel Pentium Dual      | 12        | 0.64%   |
| AMD Athlon 64 X2        | 12        | 0.64%   |
| Intel Core 2 Quad       | 11        | 0.59%   |
| AMD A10                 | 10        | 0.54%   |
| Intel Pentium Silver    | 9         | 0.48%   |
| AMD Ryzen 5 PRO         | 9         | 0.48%   |
| AMD Phenom II X4        | 9         | 0.48%   |
| AMD Athlon              | 9         | 0.48%   |
| Intel Core i9           | 7         | 0.38%   |
| Intel Celeron M         | 7         | 0.38%   |
| AMD Athlon II X2        | 7         | 0.38%   |
| Intel Pentium Gold      | 6         | 0.32%   |
| Intel Pentium 4         | 5         | 0.27%   |
| Intel Celeron Dual-Core | 5         | 0.27%   |
| AMD Sempron             | 5         | 0.27%   |
| AMD E1                  | 5         | 0.27%   |
| Intel Pentium M         | 4         | 0.21%   |
| Intel Pentium D         | 4         | 0.21%   |
| Intel Genuine           | 4         | 0.21%   |
| AMD Turion II           | 4         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 836       | 44.9%   |
| 4       | 599       | 32.17%  |
| 6       | 191       | 10.26%  |
| 8       | 125       | 6.71%   |
| 1       | 58        | 3.11%   |
| 12      | 23        | 1.24%   |
| 3       | 12        | 0.64%   |
| 16      | 7         | 0.38%   |
| 14      | 3         | 0.16%   |
| 10      | 3         | 0.16%   |
| Unknown | 3         | 0.16%   |
| 32      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1841      | 99.3%   |
| 2      | 13        | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1175      | 63.21%  |
| 1       | 680       | 36.58%  |
| Unknown | 3         | 0.16%   |
| 4       | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1798      | 96.56%  |
| Unknown        | 36        | 1.93%   |
| 32-bit         | 25        | 1.34%   |
| 64-bit         | 3         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 369       | 19.15%  |
| 0x206a7    | 204       | 10.59%  |
| 0x306c3    | 74        | 3.84%   |
| 0x1067a    | 72        | 3.74%   |
| 0x306a9    | 68        | 3.53%   |
| 0x906ea    | 49        | 2.54%   |
| 0x806ec    | 48        | 2.49%   |
| 0x806ea    | 45        | 2.34%   |
| 0x806c1    | 37        | 1.92%   |
| 0x406e3    | 36        | 1.87%   |
| 0x806e9    | 33        | 1.71%   |
| 0x40651    | 32        | 1.66%   |
| 0x08600106 | 32        | 1.66%   |
| 0x6fd      | 30        | 1.56%   |
| 0x506e3    | 30        | 1.56%   |
| 0x0a50000c | 28        | 1.45%   |
| 0x906e9    | 27        | 1.4%    |
| 0x306d4    | 24        | 1.25%   |
| 0x30678    | 23        | 1.19%   |
| 0x6fb      | 21        | 1.09%   |
| 0x10676    | 21        | 1.09%   |
| 0x08701021 | 21        | 1.09%   |
| 0x06000852 | 19        | 0.99%   |
| 0x010000c8 | 19        | 0.99%   |
| 0x406c4    | 18        | 0.93%   |
| 0x706a1    | 17        | 0.88%   |
| 0x20655    | 16        | 0.83%   |
| 0x0800820d | 16        | 0.83%   |
| 0x906ed    | 15        | 0.78%   |
| 0xa0652    | 14        | 0.73%   |
| 0x506c9    | 14        | 0.73%   |
| 0x08701013 | 13        | 0.67%   |
| 0x08600104 | 13        | 0.67%   |
| 0x06001119 | 13        | 0.67%   |
| 0x706a8    | 12        | 0.62%   |
| 0x406c3    | 12        | 0.62%   |
| 0x08608103 | 12        | 0.62%   |
| 0x08108102 | 12        | 0.62%   |
| 0x706e5    | 11        | 0.57%   |
| 0x08001138 | 11        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 278       | 14.97%  |
| SandyBridge      | 239       | 12.87%  |
| Haswell          | 136       | 7.32%   |
| Penryn           | 112       | 6.03%   |
| Zen 2            | 106       | 5.71%   |
| IvyBridge        | 89        | 4.79%   |
| Skylake          | 81        | 4.36%   |
| Core             | 75        | 4.04%   |
| Silvermont       | 70        | 3.77%   |
| Zen 3            | 62        | 3.34%   |
| TigerLake        | 50        | 2.69%   |
| Piledriver       | 45        | 2.42%   |
| Unknown          | 43        | 2.32%   |
| Zen+             | 42        | 2.26%   |
| Zen              | 40        | 2.15%   |
| Westmere         | 37        | 1.99%   |
| K10              | 36        | 1.94%   |
| Goldmont plus    | 35        | 1.88%   |
| CometLake        | 33        | 1.78%   |
| Broadwell        | 30        | 1.62%   |
| K8 Hammer        | 26        | 1.4%    |
| Excavator        | 23        | 1.24%   |
| IceLake          | 19        | 1.02%   |
| Nehalem          | 17        | 0.92%   |
| Goldmont         | 17        | 0.92%   |
| Bonnell          | 16        | 0.86%   |
| Alderlake Hybrid | 14        | 0.75%   |
| Steamroller      | 13        | 0.7%    |
| Puma             | 13        | 0.7%    |
| P6               | 13        | 0.7%    |
| NetBurst         | 11        | 0.59%   |
| Bobcat           | 10        | 0.54%   |
| Jaguar           | 8         | 0.43%   |
| Tremont          | 6         | 0.32%   |
| K10 Llano        | 5         | 0.27%   |
| K8 & K10 hybrid  | 3         | 0.16%   |
| Bulldozer        | 3         | 0.16%   |
| K6               | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1098      | 50.95%  |
| Nvidia                           | 532       | 24.69%  |
| AMD                              | 506       | 23.48%  |
| Matrox Electronics Systems       | 11        | 0.51%   |
| ASPEED Technology                | 4         | 0.19%   |
| Silicon Integrated Systems [SiS] | 2         | 0.09%   |
| VIA Technologies                 | 1         | 0.05%   |
| ATI Technologies                 | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 207       | 9.23%   |
| AMD Renoir                                                                               | 61        | 2.72%   |
| Intel UHD Graphics 620                                                                   | 57        | 2.54%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 57        | 2.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 43        | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 41        | 1.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 1.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 37        | 1.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 36        | 1.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 35        | 1.56%   |
| Intel HD Graphics 620                                                                    | 35        | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 35        | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 34        | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 33        | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 1.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 31        | 1.38%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 27        | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 1.2%    |
| Intel HD Graphics 5500                                                                   | 25        | 1.11%   |
| Intel HD Graphics 630                                                                    | 22        | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 22        | 0.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 0.94%   |
| Intel HD Graphics 530                                                                    | 20        | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 0.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 18        | 0.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 0.8%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 18        | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 17        | 0.76%   |
| AMD Lucienne                                                                             | 17        | 0.76%   |
| Intel HD Graphics 500                                                                    | 16        | 0.71%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14        | 0.62%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13        | 0.58%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 0.58%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.58%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 13        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 819       | 43.91%  |
| 1 x AMD        | 395       | 21.18%  |
| 1 x Nvidia     | 292       | 15.66%  |
| Intel + Nvidia | 213       | 11.42%  |
| Intel + AMD    | 57        | 3.06%   |
| 2 x AMD        | 33        | 1.77%   |
| AMD + Nvidia   | 21        | 1.13%   |
| Other          | 12        | 0.64%   |
| 1 x Matrox     | 10        | 0.54%   |
| 1 x ASPEED     | 4         | 0.21%   |
| 3 x Nvidia     | 2         | 0.11%   |
| 2 x Nvidia     | 2         | 0.11%   |
| 1 x SiS        | 2         | 0.11%   |
| 2 x Intel      | 1         | 0.05%   |
| 1 x VIA        | 1         | 0.05%   |
| AMD + Matrox   | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1562      | 83.09%  |
| Proprietary | 250       | 13.3%   |
| Unknown     | 68        | 3.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1103      | 57.54%  |
| 0.01-0.5   | 246       | 12.83%  |
| 1.01-2.0   | 218       | 11.37%  |
| 0.51-1.0   | 131       | 6.83%   |
| 3.01-4.0   | 98        | 5.11%   |
| 7.01-8.0   | 55        | 2.87%   |
| 5.01-6.0   | 30        | 1.56%   |
| 2.01-3.0   | 19        | 0.99%   |
| 8.01-16.0  | 16        | 0.83%   |
| 16.01-24.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 247       | 11.59%  |
| Samsung Electronics     | 245       | 11.5%   |
| LG Display              | 183       | 8.59%   |
| Chimei Innolux          | 159       | 7.46%   |
| BOE                     | 136       | 6.38%   |
| Dell                    | 133       | 6.24%   |
| CPT                     | 119       | 5.58%   |
| Goldstar                | 83        | 3.89%   |
| BenQ                    | 83        | 3.89%   |
| Acer                    | 75        | 3.52%   |
| Eizo                    | 67        | 3.14%   |
| Hewlett-Packard         | 64        | 3%      |
| Philips                 | 58        | 2.72%   |
| Lenovo                  | 51        | 2.39%   |
| AOC                     | 50        | 2.35%   |
| Ancor Communications    | 41        | 1.92%   |
| Sharp                   | 39        | 1.83%   |
| Chi Mei Optoelectronics | 30        | 1.41%   |
| Iiyama                  | 27        | 1.27%   |
| PANDA                   | 23        | 1.08%   |
| Sony                    | 17        | 0.8%    |
| LG Philips              | 16        | 0.75%   |
| ASUSTek Computer        | 14        | 0.66%   |
| Fujitsu Siemens         | 12        | 0.56%   |
| Panasonic               | 11        | 0.52%   |
| NEC Computers           | 11        | 0.52%   |
| InfoVision              | 10        | 0.47%   |
| CSO                     | 10        | 0.47%   |
| Vestel Elektronik       | 8         | 0.38%   |
| ViewSonic               | 7         | 0.33%   |
| Apple                   | 7         | 0.33%   |
| Unknown                 | 6         | 0.28%   |
| Quanta Display          | 6         | 0.28%   |
| HannStar                | 6         | 0.28%   |
| LG Electronics          | 5         | 0.23%   |
| Toshiba                 | 4         | 0.19%   |
| MSI                     | 4         | 0.19%   |
| Lenovo Group Limited    | 4         | 0.19%   |
| Hitachi                 | 4         | 0.19%   |
| OEM                     | 3         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 117       | 5.26%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 49        | 2.2%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 14        | 0.63%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 12        | 0.54%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 12        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.54%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 12        | 0.54%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 8         | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 7         | 0.31%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 7         | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.31%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 7         | 0.31%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 7         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.31%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 6         | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 6         | 0.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 6         | 0.27%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                      | 6         | 0.27%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 5         | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.22%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 5         | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 5         | 0.22%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 5         | 0.22%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 5         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 5         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.22%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                    | 5         | 0.22%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 5         | 0.22%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                        | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 5         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 884       | 43.83%  |
| 1366x768 (WXGA)    | 251       | 12.44%  |
| 1600x900 (HD+)     | 190       | 9.42%   |
| 3840x2160 (4K)     | 141       | 6.99%   |
| 2560x1440 (QHD)    | 91        | 4.51%   |
| 1280x1024 (SXGA)   | 72        | 3.57%   |
| 1680x1050 (WSXGA+) | 70        | 3.47%   |
| 1920x1200 (WUXGA)  | 68        | 3.37%   |
| 1280x800 (WXGA)    | 61        | 3.02%   |
| 1440x900 (WXGA+)   | 37        | 1.83%   |
| Unknown            | 13        | 0.64%   |
| 1024x768 (XGA)     | 11        | 0.55%   |
| 3440x1440          | 10        | 0.5%    |
| 2560x1600          | 10        | 0.5%    |
| 2560x1080          | 10        | 0.5%    |
| 1360x768           | 9         | 0.45%   |
| 3840x1080          | 8         | 0.4%    |
| 1600x1200          | 7         | 0.35%   |
| 1024x600           | 7         | 0.35%   |
| 1920x540           | 6         | 0.3%    |
| 2880x1800          | 5         | 0.25%   |
| 2288x1287          | 4         | 0.2%    |
| 2160x1350          | 4         | 0.2%    |
| 1400x1050          | 4         | 0.2%    |
| 1280x720 (HD)      | 4         | 0.2%    |
| 3840x2400          | 3         | 0.15%   |
| 3456x2160          | 3         | 0.15%   |
| 3000x2000          | 3         | 0.15%   |
| 2736x1824          | 3         | 0.15%   |
| 2160x1440          | 3         | 0.15%   |
| 3840x1200          | 2         | 0.1%    |
| 3200x1800 (QHD+)   | 2         | 0.1%    |
| 1280x768           | 2         | 0.1%    |
| 9600x2160          | 1         | 0.05%   |
| 8320x2160          | 1         | 0.05%   |
| 800x1280           | 1         | 0.05%   |
| 7680x2160          | 1         | 0.05%   |
| 640x480            | 1         | 0.05%   |
| 6400x2160          | 1         | 0.05%   |
| 6400x1440          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 480       | 22.33%  |
| 13      | 297       | 13.81%  |
| 24      | 205       | 9.53%   |
| 14      | 163       | 7.58%   |
| 27      | 138       | 6.42%   |
| 23      | 124       | 5.77%   |
| 17      | 109       | 5.07%   |
| 21      | 100       | 4.65%   |
| 31      | 83        | 3.86%   |
| 19      | 68        | 3.16%   |
| Unknown | 68        | 3.16%   |
| 22      | 45        | 2.09%   |
| 12      | 35        | 1.63%   |
| 20      | 32        | 1.49%   |
| 11      | 31        | 1.44%   |
| 18      | 22        | 1.02%   |
| 84      | 17        | 0.79%   |
| 34      | 16        | 0.74%   |
| 25      | 11        | 0.51%   |
| 26      | 10        | 0.47%   |
| 16      | 10        | 0.47%   |
| 40      | 9         | 0.42%   |
| 10      | 9         | 0.42%   |
| 54      | 8         | 0.37%   |
| 32      | 8         | 0.37%   |
| 72      | 7         | 0.33%   |
| 33      | 7         | 0.33%   |
| 52      | 5         | 0.23%   |
| 65      | 4         | 0.19%   |
| 47      | 4         | 0.19%   |
| 46      | 4         | 0.19%   |
| 39      | 4         | 0.19%   |
| 49      | 3         | 0.14%   |
| 43      | 3         | 0.14%   |
| 48      | 2         | 0.09%   |
| 142     | 1         | 0.05%   |
| 60      | 1         | 0.05%   |
| 59      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 750       | 35.83%  |
| 501-600        | 431       | 20.59%  |
| 201-300        | 281       | 13.43%  |
| 401-500        | 210       | 10.03%  |
| 351-400        | 150       | 7.17%   |
| 601-700        | 95        | 4.54%   |
| Unknown        | 68        | 3.25%   |
| 1001-1500      | 35        | 1.67%   |
| 701-800        | 30        | 1.43%   |
| 1501-2000      | 24        | 1.15%   |
| 801-900        | 15        | 0.72%   |
| 901-1000       | 2         | 0.1%    |
| More than 2000 | 1         | 0.05%   |
| 1-100          | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1383      | 74.16%  |
| 16/10   | 281       | 15.07%  |
| 5/4     | 77        | 4.13%   |
| Unknown | 58        | 3.11%   |
| 4/3     | 25        | 1.34%   |
| 3/2     | 17        | 0.91%   |
| 21/9    | 15        | 0.8%    |
| 32/9    | 4         | 0.21%   |
| 3.20    | 2         | 0.11%   |
| 3.73    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.67    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 475       | 22.3%   |
| 201-250        | 364       | 17.09%  |
| 81-90          | 260       | 12.21%  |
| 71-80          | 203       | 9.53%   |
| 301-350        | 147       | 6.9%    |
| 151-200        | 123       | 5.77%   |
| 351-500        | 115       | 5.4%    |
| 251-300        | 87        | 4.08%   |
| Unknown        | 68        | 3.19%   |
| 121-130        | 67        | 3.15%   |
| More than 1000 | 46        | 2.16%   |
| 141-150        | 42        | 1.97%   |
| 51-60          | 31        | 1.46%   |
| 61-70          | 30        | 1.41%   |
| 501-1000       | 30        | 1.41%   |
| 131-140        | 15        | 0.7%    |
| 111-120        | 10        | 0.47%   |
| 41-50          | 9         | 0.42%   |
| 91-100         | 7         | 0.33%   |
| 1-40           | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 686       | 34.1%   |
| 121-160       | 679       | 33.75%  |
| 101-120       | 393       | 19.53%  |
| 161-240       | 117       | 5.82%   |
| Unknown       | 68        | 3.38%   |
| 1-50          | 38        | 1.89%   |
| More than 240 | 31        | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1421      | 74.24%  |
| 2     | 358       | 18.7%   |
| 0     | 81        | 4.23%   |
| 3     | 52        | 2.72%   |
| 4     | 2         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 884       | 31.78%  |
| Intel                             | 870       | 31.27%  |
| Qualcomm Atheros                  | 410       | 14.74%  |
| Broadcom                          | 122       | 4.39%   |
| Samsung Electronics               | 121       | 4.35%   |
| Broadcom Limited                  | 51        | 1.83%   |
| Marvell Technology Group          | 35        | 1.26%   |
| MediaTek                          | 30        | 1.08%   |
| TP-Link                           | 26        | 0.93%   |
| Lenovo                            | 21        | 0.75%   |
| Qualcomm Atheros Communications   | 19        | 0.68%   |
| Nvidia                            | 19        | 0.68%   |
| Ralink Technology                 | 18        | 0.65%   |
| Ralink                            | 17        | 0.61%   |
| Dell                              | 13        | 0.47%   |
| ASIX Electronics                  | 12        | 0.43%   |
| Sierra Wireless                   | 11        | 0.4%    |
| DisplayLink                       | 11        | 0.4%    |
| ASUSTek Computer                  | 8         | 0.29%   |
| Microsoft                         | 6         | 0.22%   |
| QLogic                            | 5         | 0.18%   |
| D-Link                            | 5         | 0.18%   |
| Attansic Technology               | 5         | 0.18%   |
| VIA Technologies                  | 4         | 0.14%   |
| Ericsson Business Mobile Networks | 4         | 0.14%   |
| ZyDAS                             | 3         | 0.11%   |
| Xiaomi                            | 3         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.11%   |
| Huawei Technologies               | 3         | 0.11%   |
| Hewlett-Packard                   | 3         | 0.11%   |
| Edimax Technology                 | 3         | 0.11%   |
| Spreadtrum Communications         | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.07%   |
| Qualcomm                          | 2         | 0.07%   |
| Mellanox Technologies             | 2         | 0.07%   |
| Fibocom                           | 2         | 0.07%   |
| Arduino SA                        | 2         | 0.07%   |
| ZyXEL Communications              | 1         | 0.04%   |
| Texas Instruments                 | 1         | 0.04%   |
| Sundance Technology Inc / IC Plus | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 625       | 19.31%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 142       | 4.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 118       | 3.65%   |
| Intel Wi-Fi 6 AX200                                               | 95        | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 81        | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 68        | 2.1%    |
| Intel Wireless 8265 / 8275                                        | 63        | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 1.92%   |
| Intel Wireless 7260                                               | 44        | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 41        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 41        | 1.27%   |
| Intel Wi-Fi 6 AX201                                               | 38        | 1.17%   |
| Intel Wireless 8260                                               | 36        | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 35        | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 34        | 1.05%   |
| Intel I211 Gigabit Network Connection                             | 33        | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 32        | 0.99%   |
| Intel Ethernet Connection I217-LM                                 | 31        | 0.96%   |
| Intel Wireless 7265                                               | 30        | 0.93%   |
| Intel Wireless 3165                                               | 29        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 27        | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 27        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 27        | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 26        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 26        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 24        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 21        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 20        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 19        | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 18        | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 18        | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.56%   |
| Intel Wireless 3160                                               | 17        | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 17        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 17        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 17        | 0.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 16        | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                   | 16        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 691       | 48.05%  |
| Qualcomm Atheros                | 333       | 23.16%  |
| Realtek Semiconductor           | 162       | 11.27%  |
| Broadcom                        | 69        | 4.8%    |
| MediaTek                        | 28        | 1.95%   |
| Broadcom Limited                | 25        | 1.74%   |
| TP-Link                         | 24        | 1.67%   |
| Qualcomm Atheros Communications | 19        | 1.32%   |
| Ralink Technology               | 18        | 1.25%   |
| Ralink                          | 17        | 1.18%   |
| Sierra Wireless                 | 11        | 0.76%   |
| Dell                            | 7         | 0.49%   |
| ASUSTek Computer                | 7         | 0.49%   |
| Microsoft                       | 6         | 0.42%   |
| D-Link                          | 4         | 0.28%   |
| ZyDAS                           | 3         | 0.21%   |
| Edimax Technology               | 3         | 0.21%   |
| Marvell Technology Group        | 2         | 0.14%   |
| Fibocom                         | 2         | 0.14%   |
| ZyXEL Communications            | 1         | 0.07%   |
| Texas Instruments               | 1         | 0.07%   |
| Qualcomm                        | 1         | 0.07%   |
| Mercucys                        | 1         | 0.07%   |
| Intersil                        | 1         | 0.07%   |
| Hewlett-Packard                 | 1         | 0.07%   |
| Fujitsu Siemens Computers       | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 142       | 9.85%   |
| Intel Wi-Fi 6 AX200                                            | 95        | 6.59%   |
| Intel Wireless 8265 / 8275                                     | 63        | 4.37%   |
| Intel Wireless 7260                                            | 44        | 3.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 41        | 2.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 41        | 2.84%   |
| Intel Wi-Fi 6 AX201                                            | 38        | 2.64%   |
| Intel Wireless 8260                                            | 36        | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 35        | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 34        | 2.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 32        | 2.22%   |
| Intel Wireless 7265                                            | 30        | 2.08%   |
| Intel Wireless 3165                                            | 29        | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 27        | 1.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 27        | 1.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 26        | 1.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 26        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 24        | 1.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 19        | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 1.25%   |
| Intel Wireless 3160                                            | 17        | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 17        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 17        | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 17        | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 16        | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                | 16        | 1.11%   |
| Intel WiFi Link 5100                                           | 16        | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 15        | 1.04%   |
| Intel Centrino Wireless-N 2230                                 | 13        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                  | 13        | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 11        | 0.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 11        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 10        | 0.69%   |
| Intel Wireless-AC 9260                                         | 10        | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 10        | 0.69%   |
| Intel Ultimate N WiFi Link 5300                                | 10        | 0.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 9         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 810       | 47.18%  |
| Intel                             | 441       | 25.68%  |
| Samsung Electronics               | 121       | 7.05%   |
| Qualcomm Atheros                  | 116       | 6.76%   |
| Broadcom                          | 60        | 3.49%   |
| Marvell Technology Group          | 34        | 1.98%   |
| Broadcom Limited                  | 26        | 1.51%   |
| Lenovo                            | 21        | 1.22%   |
| Nvidia                            | 19        | 1.11%   |
| ASIX Electronics                  | 12        | 0.7%    |
| DisplayLink                       | 11        | 0.64%   |
| QLogic                            | 5         | 0.29%   |
| Attansic Technology               | 5         | 0.29%   |
| Xiaomi                            | 3         | 0.17%   |
| VIA Technologies                  | 3         | 0.17%   |
| TP-Link                           | 2         | 0.12%   |
| Spreadtrum Communications         | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.12%   |
| Mellanox Technologies             | 2         | 0.12%   |
| MediaTek                          | 2         | 0.12%   |
| Huawei Technologies               | 2         | 0.12%   |
| Sundance Technology Inc / IC Plus | 1         | 0.06%   |
| Qualcomm                          | 1         | 0.06%   |
| MosChip Semiconductor             | 1         | 0.06%   |
| Microchip Technology              | 1         | 0.06%   |
| JMicron Technology                | 1         | 0.06%   |
| ICS Advent                        | 1         | 0.06%   |
| IBM                               | 1         | 0.06%   |
| Hewlett-Packard                   | 1         | 0.06%   |
| Google                            | 1         | 0.06%   |
| Foxconn / Hon Hai                 | 1         | 0.06%   |
| Emulex                            | 1         | 0.06%   |
| D-Link System                     | 1         | 0.06%   |
| D-Link                            | 1         | 0.06%   |
| Chelsio Communications            | 1         | 0.06%   |
| ASUSTek Computer                  | 1         | 0.06%   |
| Aquantia                          | 1         | 0.06%   |
| American Megatrends               | 1         | 0.06%   |
| 3Com                              | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 625       | 35.41%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 118       | 6.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 81        | 4.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 68        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 62        | 3.51%   |
| Intel I211 Gigabit Network Connection                                          | 33        | 1.87%   |
| Realtek RTL8125 2.5GbE Controller                                              | 32        | 1.81%   |
| Intel Ethernet Connection I217-LM                                              | 31        | 1.76%   |
| Intel Ethernet Connection (4) I219-LM                                          | 27        | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 21        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                                           | 20        | 1.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 19        | 1.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 18        | 1.02%   |
| Intel 82567LM Gigabit Network Connection                                       | 18        | 1.02%   |
| Intel Ethernet Controller I225-V                                               | 15        | 0.85%   |
| Intel Ethernet Connection I219-LM                                              | 15        | 0.85%   |
| Intel Ethernet Connection I218-LM                                              | 14        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                          | 13        | 0.74%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 13        | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 12        | 0.68%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 12        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 11        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                           | 11        | 0.62%   |
| Intel Ethernet Connection (6) I219-V                                           | 11        | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                           | 11        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 11        | 0.62%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 10        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                        | 9         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 8         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 8         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 8         | 0.45%   |
| Intel Ethernet Connection (2) I218-V                                           | 8         | 0.45%   |
| Intel Ethernet Connection (10) I219-LM                                         | 8         | 0.45%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 8         | 0.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 8         | 0.45%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 8         | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 0.4%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 7         | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 7         | 0.4%    |
| Intel Ethernet Connection I219-V                                               | 7         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1612      | 53.38%  |
| WiFi     | 1380      | 45.7%   |
| Modem    | 23        | 0.76%   |
| Unknown  | 5         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 982       | 51.09%  |
| Ethernet | 940       | 48.91%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 945       | 50.72%  |
| 1     | 831       | 44.61%  |
| 0     | 45        | 2.42%   |
| 3     | 30        | 1.61%   |
| 4     | 5         | 0.27%   |
| 8     | 4         | 0.21%   |
| 5     | 2         | 0.11%   |
| 10    | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1656      | 87.99%  |
| Yes  | 226       | 12.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 519       | 48.78%  |
| Realtek Semiconductor           | 92        | 8.65%   |
| Qualcomm Atheros Communications | 70        | 6.58%   |
| IMC Networks                    | 69        | 6.48%   |
| Broadcom                        | 60        | 5.64%   |
| Cambridge Silicon Radio         | 54        | 5.08%   |
| Foxconn / Hon Hai               | 38        | 3.57%   |
| Lite-On Technology              | 36        | 3.38%   |
| ASUSTek Computer                | 36        | 3.38%   |
| Hewlett-Packard                 | 25        | 2.35%   |
| Dell                            | 16        | 1.5%    |
| Ralink                          | 8         | 0.75%   |
| MediaTek                        | 7         | 0.66%   |
| Apple                           | 6         | 0.56%   |
| Alps Electric                   | 5         | 0.47%   |
| Toshiba                         | 4         | 0.38%   |
| Realtek                         | 4         | 0.38%   |
| Integrated System Solution      | 3         | 0.28%   |
| Ralink Technology               | 2         | 0.19%   |
| Micro Star International        | 2         | 0.19%   |
| Marvell Semiconductor           | 2         | 0.19%   |
| TP-Link                         | 1         | 0.09%   |
| Mobile Action Technology        | 1         | 0.09%   |
| Fujitsu Siemens Computers       | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |
| Creative Technology             | 1         | 0.09%   |
| Askey Computer                  | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 210       | 19.74%  |
| Intel AX200 Bluetooth                               | 92        | 8.65%   |
| Intel AX201 Bluetooth                               | 90        | 8.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 65        | 6.11%   |
| Realtek Bluetooth Radio                             | 57        | 5.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 54        | 5.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 26        | 2.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 24        | 2.26%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 21        | 1.97%   |
| IMC Networks Bluetooth Device                       | 19        | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 1.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 17        | 1.6%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1.41%   |
| IMC Networks Bluetooth Radio                        | 15        | 1.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 14        | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 1.22%   |
| IMC Networks Wireless_Device                        | 12        | 1.13%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 1.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 1.03%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 0.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 10        | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.85%   |
| Intel AX210 Bluetooth                               | 9         | 0.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.85%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 0.85%   |
| Ralink RT3290 Bluetooth                             | 8         | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.75%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 8         | 0.75%   |
| ASUS ASUS USB-BT500                                 | 8         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 0.66%   |
| Intel Bluetooth Device                              | 7         | 0.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.66%   |
| Qualcomm Atheros Bluetooth                          | 6         | 0.56%   |
| Lite-On Bluetooth Device                            | 6         | 0.56%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 6         | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.47%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.47%   |
| Realtek Bluetooth Radio                             | 4         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1316      | 53.67%  |
| AMD                                  | 537       | 21.9%   |
| Nvidia                               | 346       | 14.11%  |
| C-Media Electronics                  | 48        | 1.96%   |
| Lenovo                               | 27        | 1.1%    |
| Realtek Semiconductor                | 22        | 0.9%    |
| Creative Labs                        | 15        | 0.61%   |
| Logitech                             | 14        | 0.57%   |
| Creative Technology                  | 13        | 0.53%   |
| VIA Technologies                     | 10        | 0.41%   |
| JMTek                                | 10        | 0.41%   |
| GN Netcom                            | 9         | 0.37%   |
| Hewlett-Packard                      | 7         | 0.29%   |
| Plantronics                          | 6         | 0.24%   |
| Kingston Technology                  | 5         | 0.2%    |
| Dell                                 | 5         | 0.2%    |
| Razer USA                            | 4         | 0.16%   |
| GYROCOM C&C                          | 4         | 0.16%   |
| Focusrite-Novation                   | 4         | 0.16%   |
| Trust                                | 3         | 0.12%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.12%   |
| DSEA A/S                             | 3         | 0.12%   |
| BEHRINGER International              | 3         | 0.12%   |
| ASUSTek Computer                     | 3         | 0.12%   |
| Samson Technologies                  | 2         | 0.08%   |
| RODE Microphones                     | 2         | 0.08%   |
| M-Audio                              | 2         | 0.08%   |
| DigiTech                             | 2         | 0.08%   |
| Conexant Systems                     | 2         | 0.08%   |
| Yealink Network Technology           | 1         | 0.04%   |
| Toshiba                              | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| Texas Instruments                    | 1         | 0.04%   |
| Tenx Technology                      | 1         | 0.04%   |
| Syntek                               | 1         | 0.04%   |
| SteelSeries ApS                      | 1         | 0.04%   |
| Sony                                 | 1         | 0.04%   |
| Sennheiser Communications            | 1         | 0.04%   |
| Orbbec 3D Technology International   | 1         | 0.04%   |
| Microsoft                            | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 216       | 7.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 163       | 5.59%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 137       | 4.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 105       | 3.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 96        | 3.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 81        | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 77        | 2.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 74        | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 67        | 2.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 65        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 64        | 2.19%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 63        | 2.16%   |
| AMD FCH Azalia Controller                                                                         | 59        | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 50        | 1.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 46        | 1.58%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 41        | 1.41%   |
| Intel 8 Series HD Audio Controller                                                                | 41        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 41        | 1.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 39        | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 38        | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 36        | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 36        | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 36        | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 35        | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 35        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 34        | 1.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 33        | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 31        | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 30        | 1.03%   |
| Intel Broadwell-U Audio Controller                                                                | 29        | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 28        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 27        | 0.93%   |
| Intel 200 Series PCH HD Audio                                                                     | 24        | 0.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 24        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 23        | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 22        | 0.75%   |
| Intel Comet Lake PCH cAVS                                                                         | 21        | 0.72%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 21        | 0.72%   |
| Realtek Semiconductor USB Audio                                                                   | 19        | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 19        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 235       | 19.97%  |
| Kingston             | 205       | 17.42%  |
| SK hynix             | 183       | 15.55%  |
| Elpida               | 132       | 11.21%  |
| Unknown              | 119       | 10.11%  |
| Micron Technology    | 110       | 9.35%   |
| Crucial              | 44        | 3.74%   |
| Corsair              | 33        | 2.8%    |
| Ramaxel Technology   | 26        | 2.21%   |
| Patriot              | 20        | 1.7%    |
| A-DATA Technology    | 20        | 1.7%    |
| Unknown (ABCD)       | 14        | 1.19%   |
| Nanya Technology     | 8         | 0.68%   |
| G.Skill              | 8         | 0.68%   |
| Transcend            | 5         | 0.42%   |
| GOODRAM              | 2         | 0.17%   |
| Unknown (AB)         | 1         | 0.08%   |
| Toshiba              | 1         | 0.08%   |
| Team                 | 1         | 0.08%   |
| ProMos/Mosel Vitelic | 1         | 0.08%   |
| PDPSystems           | 1         | 0.08%   |
| OnBoard              | 1         | 0.08%   |
| Nayna                | 1         | 0.08%   |
| Kingmax              | 1         | 0.08%   |
| Kimtigo              | 1         | 0.08%   |
| H                    | 1         | 0.08%   |
| Golden Empire        | 1         | 0.08%   |
| Apacer               | 1         | 0.08%   |
| AMD                  | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 116       | 9.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 1.11%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 10        | 0.8%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 0.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.56%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 7         | 0.56%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 7         | 0.56%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 7         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.48%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 6         | 0.48%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 6         | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.48%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.48%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 6         | 0.48%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.4%    |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 5         | 0.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.4%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.4%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 5         | 0.4%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 5         | 0.4%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 4         | 0.32%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 4         | 0.32%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 3200MT/s                  | 4         | 0.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 446       | 43.09%  |
| DDR3    | 401       | 38.74%  |
| DDR2    | 55        | 5.31%   |
| LPDDR4  | 51        | 4.93%   |
| Unknown | 31        | 3%      |
| LPDDR3  | 21        | 2.03%   |
| SDRAM   | 18        | 1.74%   |
| DDR     | 6         | 0.58%   |
| LPDDR5  | 3         | 0.29%   |
| DDR5    | 2         | 0.19%   |
| DRAM    | 1         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 657       | 63.29%  |
| DIMM         | 301       | 29%     |
| Row Of Chips | 65        | 6.26%   |
| Chip         | 12        | 1.16%   |
| RIMM         | 2         | 0.19%   |
| Unknown      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 374       | 33.63%  |
| 4096  | 256       | 23.02%  |
| 2048  | 238       | 21.4%   |
| 16384 | 162       | 14.57%  |
| 32768 | 39        | 3.51%   |
| 1024  | 35        | 3.15%   |
| 512   | 4         | 0.36%   |
| 256   | 2         | 0.18%   |
| 6144  | 1         | 0.09%   |
| 3072  | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1333    | 180       | 16.14%  |
| 1600    | 179       | 16.05%  |
| 3200    | 161       | 14.44%  |
| 2667    | 136       | 12.2%   |
| 2400    | 87        | 7.8%    |
| 2133    | 54        | 4.84%   |
| 800     | 35        | 3.14%   |
| 1334    | 32        | 2.87%   |
| 3600    | 31        | 2.78%   |
| 667     | 22        | 1.97%   |
| Unknown | 20        | 1.79%   |
| 4267    | 19        | 1.7%    |
| 1867    | 16        | 1.43%   |
| 3266    | 15        | 1.35%   |
| 1067    | 12        | 1.08%   |
| 3400    | 9         | 0.81%   |
| 3466    | 8         | 0.72%   |
| 2666    | 7         | 0.63%   |
| 1866    | 7         | 0.63%   |
| 1066    | 7         | 0.63%   |
| 4266    | 6         | 0.54%   |
| 4199    | 5         | 0.45%   |
| 3733    | 5         | 0.45%   |
| 3000    | 5         | 0.45%   |
| 2933    | 5         | 0.45%   |
| 533     | 5         | 0.45%   |
| 3800    | 4         | 0.36%   |
| 3333    | 4         | 0.36%   |
| 975     | 4         | 0.36%   |
| 400     | 4         | 0.36%   |
| 6400    | 3         | 0.27%   |
| 4800    | 3         | 0.27%   |
| 8400    | 2         | 0.18%   |
| 4133    | 2         | 0.18%   |
| 3666    | 2         | 0.18%   |
| 3334    | 2         | 0.18%   |
| 2800    | 2         | 0.18%   |
| 2048    | 2         | 0.18%   |
| 1400    | 2         | 0.18%   |
| 4600    | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 10        | 27.03%  |
| Hewlett-Packard     | 9         | 24.32%  |
| Samsung Electronics | 6         | 16.22%  |
| Brother Industries  | 5         | 13.51%  |
| Xerox               | 1         | 2.7%    |
| Seiko Epson         | 1         | 2.7%    |
| QinHeng Electronics | 1         | 2.7%    |
| Prolific Technology | 1         | 2.7%    |
| Pantum              | 1         | 2.7%    |
| Minolta             | 1         | 2.7%    |
| ICS Advent          | 1         | 2.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP DeskJet 2600 series                  | 3         | 7.89%   |
| Samsung M2070 Series                    | 2         | 5.26%   |
| Xerox Phaser 3260                       | 1         | 2.63%   |
| Seiko Epson L365 Series                 | 1         | 2.63%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 2.63%   |
| Samsung M267x 287x Series               | 1         | 2.63%   |
| Samsung M2020 Series                    | 1         | 2.63%   |
| Samsung C460 Series                     | 1         | 2.63%   |
| QinHeng CH340S                          | 1         | 2.63%   |
| Prolific PL2305 Parallel Port           | 1         | 2.63%   |
| Pantum P2000                            | 1         | 2.63%   |
| Minolta PagePro 1300W                   | 1         | 2.63%   |
| ICS Advent Parallel Adapter             | 1         | 2.63%   |
| HP Officejet 4500 G510g-m               | 1         | 2.63%   |
| HP Neverstop Laser 100x                 | 1         | 2.63%   |
| HP LaserJet Professional P 1102w        | 1         | 2.63%   |
| HP LaserJet P2014                       | 1         | 2.63%   |
| HP LaserJet 1018                        | 1         | 2.63%   |
| HP Deskjet 3050 J610 series             | 1         | 2.63%   |
| Canon TS6300 series                     | 1         | 2.63%   |
| Canon PIXMA MX920 Series                | 1         | 2.63%   |
| Canon PIXMA MX720 Series                | 1         | 2.63%   |
| Canon PIXMA MP280                       | 1         | 2.63%   |
| Canon PIXMA MG3500 Series               | 1         | 2.63%   |
| Canon PIXMA MG2500 Series               | 1         | 2.63%   |
| Canon MG5600 series                     | 1         | 2.63%   |
| Canon MF4100 series                     | 1         | 2.63%   |
| Canon LBP3010/LBP3018/LBP3050           | 1         | 2.63%   |
| Canon iP7200 series                     | 1         | 2.63%   |
| Canon CanoScan LiDE 300                 | 1         | 2.63%   |
| Brother MFC-J3930DW                     | 1         | 2.63%   |
| Brother HL-2030 Laser Printer           | 1         | 2.63%   |
| Brother HL-1430 Laser Printer           | 1         | 2.63%   |
| Brother DCP-J105                        | 1         | 2.63%   |
| Brother DCP-1610W                       | 1         | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 6         | 85.71%  |
| Mustek Systems | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25              | 2         | 28.57%  |
| Canon CanoScan LiDE 210             | 2         | 28.57%  |
| Mustek Systems BearPaw 1200 CU Plus | 1         | 14.29%  |
| Canon CanoScan LiDE 200             | 1         | 14.29%  |
| Canon CanoScan LiDE 100             | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 257       | 24.62%  |
| Realtek Semiconductor                  | 105       | 10.06%  |
| IMC Networks                           | 93        | 8.91%   |
| Acer                                   | 80        | 7.66%   |
| Microdia                               | 77        | 7.38%   |
| Sunplus Innovation Technology          | 61        | 5.84%   |
| Cheng Uei Precision Industry (Foxlink) | 46        | 4.41%   |
| Lite-On Technology                     | 43        | 4.12%   |
| Quanta                                 | 41        | 3.93%   |
| Suyin                                  | 31        | 2.97%   |
| Syntek                                 | 29        | 2.78%   |
| Logitech                               | 23        | 2.2%    |
| Apple                                  | 15        | 1.44%   |
| Bison Electronics                      | 13        | 1.25%   |
| Samsung Electronics                    | 12        | 1.15%   |
| KYE Systems (Mouse Systems)            | 12        | 1.15%   |
| Lenovo                                 | 11        | 1.05%   |
| Alcor Micro                            | 11        | 1.05%   |
| Ricoh                                  | 10        | 0.96%   |
| Z-Star Microelectronics                | 9         | 0.86%   |
| Microsoft                              | 8         | 0.77%   |
| Creative Technology                    | 8         | 0.77%   |
| GEMBIRD                                | 5         | 0.48%   |
| Primax Electronics                     | 4         | 0.38%   |
| Luxvisions Innotech Limited            | 4         | 0.38%   |
| Hopewin Electronic Material            | 4         | 0.38%   |
| Generalplus Technology                 | 3         | 0.29%   |
| USB Camera                             | 2         | 0.19%   |
| Sonix Technology                       | 2         | 0.19%   |
| MacroSilicon                           | 2         | 0.19%   |
| Intel                                  | 2         | 0.19%   |
| Hewlett-Packard                        | 2         | 0.19%   |
| YGTek                                  | 1         | 0.1%    |
| WaveRider Communications               | 1         | 0.1%    |
| SunplusIT                              | 1         | 0.1%    |
| Sunplus Technology                     | 1         | 0.1%    |
| Smartronix                             | 1         | 0.1%    |
| Silicon Motion                         | 1         | 0.1%    |
| Ruision                                | 1         | 0.1%    |
| Pixart Imaging                         | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 70        | 6.63%   |
| IMC Networks Integrated Camera                      | 42        | 3.98%   |
| Realtek Integrated_Webcam_HD                        | 32        | 3.03%   |
| Microdia Integrated_Webcam_HD                       | 32        | 3.03%   |
| Chicony HD Webcam                                   | 25        | 2.37%   |
| Chicony HP HD Camera                                | 24        | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 20        | 1.89%   |
| Acer Lenovo EasyCamera                              | 20        | 1.89%   |
| Lite-On HP HD Camera                                | 19        | 1.8%    |
| Acer Integrated Camera                              | 17        | 1.61%   |
| Sunplus Integrated_Webcam_HD                        | 15        | 1.42%   |
| Syntek Integrated Camera                            | 14        | 1.33%   |
| Chicony Integrated Camera (1280x720@30)             | 14        | 1.33%   |
| Samsung Galaxy A5 (MTP)                             | 12        | 1.14%   |
| Lite-On Integrated Camera                           | 12        | 1.14%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 12        | 1.14%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 10        | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 10        | 0.95%   |
| Chicony USB2.0 VGA UVC WebCam                       | 10        | 0.95%   |
| Quanta HD User Facing                               | 9         | 0.85%   |
| Syntek Lenovo EasyCamera                            | 8         | 0.76%   |
| Realtek Integrated Webcam HD                        | 8         | 0.76%   |
| Quanta HP Wide Vision HD Camera                     | 8         | 0.76%   |
| Quanta HP HD Camera                                 | 8         | 0.76%   |
| Microdia Integrated Webcam                          | 8         | 0.76%   |
| Chicony Lenovo EasyCamera                           | 8         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 8         | 0.76%   |
| Acer SunplusIT Integrated Camera                    | 8         | 0.76%   |
| Acer EasyCamera                                     | 8         | 0.76%   |
| Sunplus HD WebCam                                   | 7         | 0.66%   |
| Sunplus Asus Webcam                                 | 7         | 0.66%   |
| Logitech Webcam C270                                | 7         | 0.66%   |
| Lenovo Integrated Webcam                            | 7         | 0.66%   |
| Chicony HP HD Webcam                                | 7         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 7         | 0.66%   |
| Acer Lenovo Integrated Webcam                       | 7         | 0.66%   |
| Sunplus Laptop Integrated WebCam HD                 | 6         | 0.57%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 0.57%   |
| Realtek USB2.0 HD UVC WebCam                        | 6         | 0.57%   |
| Realtek USB2.0 camera                               | 6         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 97        | 34.04%  |
| Validity Sensors                   | 93        | 32.63%  |
| Shenzhen Goodix Technology         | 34        | 11.93%  |
| AuthenTec                          | 27        | 9.47%   |
| Upek                               | 13        | 4.56%   |
| Elan Microelectronics              | 13        | 4.56%   |
| LighTuning Technology              | 5         | 1.75%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.35%   |
| Microsoft                          | 1         | 0.35%   |
| Dell                               | 1         | 0.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 29        | 10.18%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 8.77%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 18        | 6.32%   |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 5.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 4.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 4.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 12        | 4.21%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 4.21%   |
| AuthenTec AES2810                                                          | 11        | 3.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.16%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.16%   |
| Elan ELAN:Fingerprint                                                      | 9         | 3.16%   |
| Validity Sensors VFS491                                                    | 8         | 2.81%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 8         | 2.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.46%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 2.46%   |
| AuthenTec AES1600                                                          | 7         | 2.46%   |
| Synaptics UWP WBDI                                                         | 6         | 2.11%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.75%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.75%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.75%   |
| Synaptics WBDI                                                             | 4         | 1.4%    |
| Synaptics  WBDI                                                            | 4         | 1.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.4%    |
| Elan ELAN:ARM-M4                                                           | 4         | 1.4%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.05%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 1.05%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.05%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.05%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.05%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.7%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.35%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.35%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.35%   |
| Synaptics WBDI Device                                                      | 1         | 0.35%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.35%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.35%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 57        | 47.9%   |
| Alcor Micro               | 37        | 31.09%  |
| O2 Micro                  | 9         | 7.56%   |
| Lenovo                    | 5         | 4.2%    |
| Upek                      | 2         | 1.68%   |
| SCM Microsystems          | 2         | 1.68%   |
| Realtek Semiconductor     | 2         | 1.68%   |
| Aladdin Knowledge Systems | 2         | 1.68%   |
| Purism, SPC               | 1         | 0.84%   |
| OmniKey                   | 1         | 0.84%   |
| Fujitsu Siemens Computers | 1         | 0.84%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 37        | 31.09%  |
| Broadcom 58200                                                               | 18        | 15.13%  |
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 12.61%  |
| Broadcom 5880                                                                | 13        | 10.92%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 9.24%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 6.72%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.2%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.68%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.68%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.68%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.68%   |
| Purism, SPC Librem Key                                                       | 1         | 0.84%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.84%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.84%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.84%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1267      | 67.18%  |
| 1     | 470       | 24.92%  |
| 2     | 119       | 6.31%   |
| 3     | 22        | 1.17%   |
| 4     | 5         | 0.27%   |
| 5     | 3         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 279       | 35.95%  |
| Graphics card            | 168       | 21.65%  |
| Chipcard                 | 104       | 13.4%   |
| Net/wireless             | 54        | 6.96%   |
| Multimedia controller    | 36        | 4.64%   |
| Communication controller | 20        | 2.58%   |
| Bluetooth                | 20        | 2.58%   |
| Storage                  | 19        | 2.45%   |
| Camera                   | 17        | 2.19%   |
| Unassigned class         | 10        | 1.29%   |
| Net/ethernet             | 9         | 1.16%   |
| Card reader              | 9         | 1.16%   |
| Sound                    | 8         | 1.03%   |
| Flash memory             | 7         | 0.9%    |
| Modem                    | 6         | 0.77%   |
| Network                  | 4         | 0.52%   |
| Storage/ata              | 2         | 0.26%   |
| Dvb card                 | 2         | 0.26%   |
| Storage/raid             | 1         | 0.13%   |
| Storage/ide              | 1         | 0.13%   |


Pop!_OS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 5569

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | Z97 Killer                  | [f575f3121e](https://linux-hardware.org/?probe=f575f3121e) | Nov 06, 2023 |
| ASRock        | Z68 Pro3                    | [e6c695d4a7](https://linux-hardware.org/?probe=e6c695d4a7) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [6f11758faa](https://linux-hardware.org/?probe=6f11758faa) | Nov 04, 2023 |
| Gigabyte      | H410M S2H V2                | [8bbce8a378](https://linux-hardware.org/?probe=8bbce8a378) | Nov 04, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [f27bded4c1](https://linux-hardware.org/?probe=f27bded4c1) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | [26aff1917e](https://linux-hardware.org/?probe=26aff1917e) | Nov 04, 2023 |
| Intel         | X79 V1.0                    | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [d35fc5aa78](https://linux-hardware.org/?probe=d35fc5aa78) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [9a5c45e54b](https://linux-hardware.org/?probe=9a5c45e54b) | Nov 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [fc0052213d](https://linux-hardware.org/?probe=fc0052213d) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | [7812f09d39](https://linux-hardware.org/?probe=7812f09d39) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | [b45e25ec01](https://linux-hardware.org/?probe=b45e25ec01) | Nov 02, 2023 |
| HP            | 2AF7                        | [65ac8348d7](https://linux-hardware.org/?probe=65ac8348d7) | Nov 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [cd018c7ab7](https://linux-hardware.org/?probe=cd018c7ab7) | Nov 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [523fd59139](https://linux-hardware.org/?probe=523fd59139) | Nov 01, 2023 |
| ASRock        | X470 Taichi Ultimate        | [d85d5f59c2](https://linux-hardware.org/?probe=d85d5f59c2) | Nov 01, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [39f8a7c959](https://linux-hardware.org/?probe=39f8a7c959) | Nov 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [38d664802f](https://linux-hardware.org/?probe=38d664802f) | Nov 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [037e92aebd](https://linux-hardware.org/?probe=037e92aebd) | Nov 01, 2023 |
| ASRock        | B85M Pro4                   | [0ea7f00b4e](https://linux-hardware.org/?probe=0ea7f00b4e) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [7d5fd28d41](https://linux-hardware.org/?probe=7d5fd28d41) | Nov 01, 2023 |
| Unknown       | Unknown                     | [d58a78a617](https://linux-hardware.org/?probe=d58a78a617) | Oct 31, 2023 |
| eMachines     | EL1352G                     | [e133fecf3e](https://linux-hardware.org/?probe=e133fecf3e) | Oct 31, 2023 |
| ASRock        | A520M Phantom Gaming 4      | [a63d934992](https://linux-hardware.org/?probe=a63d934992) | Oct 31, 2023 |
| HP            | 8299                        | [e45f46df9d](https://linux-hardware.org/?probe=e45f46df9d) | Oct 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [e231035f6e](https://linux-hardware.org/?probe=e231035f6e) | Oct 30, 2023 |
| MSI           | PRO Z790-P WIFI             | [b62cfa508b](https://linux-hardware.org/?probe=b62cfa508b) | Oct 30, 2023 |
| HP            | 2AF7                        | [1960b3a243](https://linux-hardware.org/?probe=1960b3a243) | Oct 29, 2023 |
| Gigabyte      | B450 GAMING X               | [c1785bec94](https://linux-hardware.org/?probe=c1785bec94) | Oct 29, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [6b8560a943](https://linux-hardware.org/?probe=6b8560a943) | Oct 28, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | [fdb96441a0](https://linux-hardware.org/?probe=fdb96441a0) | Oct 27, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | [dde83d5de1](https://linux-hardware.org/?probe=dde83d5de1) | Oct 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [880bf38f49](https://linux-hardware.org/?probe=880bf38f49) | Oct 27, 2023 |
| ASUSTek       | PRIME X570-PRO              | [815b0a4bc4](https://linux-hardware.org/?probe=815b0a4bc4) | Oct 27, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [61bdfadaa0](https://linux-hardware.org/?probe=61bdfadaa0) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [13ad3bb316](https://linux-hardware.org/?probe=13ad3bb316) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [a8d850eef8](https://linux-hardware.org/?probe=a8d850eef8) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [023bd4d497](https://linux-hardware.org/?probe=023bd4d497) | Oct 25, 2023 |
| MSI           | PRO Z690-A DDR4             | [638386d33c](https://linux-hardware.org/?probe=638386d33c) | Oct 25, 2023 |
| HP            | 3047h                       | [cdd7fbc37f](https://linux-hardware.org/?probe=cdd7fbc37f) | Oct 25, 2023 |
| HP            | 3047h                       | [4235f287b2](https://linux-hardware.org/?probe=4235f287b2) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [b7447f21b5](https://linux-hardware.org/?probe=b7447f21b5) | Oct 25, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [5ad24eb928](https://linux-hardware.org/?probe=5ad24eb928) | Oct 24, 2023 |
| Danuri        | B550M-PX                    | [e24df1ad61](https://linux-hardware.org/?probe=e24df1ad61) | Oct 24, 2023 |
| Intel         | H61 V124                    | [034689793f](https://linux-hardware.org/?probe=034689793f) | Oct 24, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [b1f52f8dc1](https://linux-hardware.org/?probe=b1f52f8dc1) | Oct 23, 2023 |
| Gigabyte      | 970A-DS3P                   | [a9af589ace](https://linux-hardware.org/?probe=a9af589ace) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | [cf347b4567](https://linux-hardware.org/?probe=cf347b4567) | Oct 23, 2023 |
| Dell          | 096JG8 A01                  | [ce5ff412d1](https://linux-hardware.org/?probe=ce5ff412d1) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | [e0f48fec00](https://linux-hardware.org/?probe=e0f48fec00) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [58a9a7a091](https://linux-hardware.org/?probe=58a9a7a091) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [9b380c5e6a](https://linux-hardware.org/?probe=9b380c5e6a) | Oct 22, 2023 |
| ASRock        | N68C-S UCC                  | [6468bd6335](https://linux-hardware.org/?probe=6468bd6335) | Oct 21, 2023 |
| Dell          | 00V62H A01                  | [85894d27fe](https://linux-hardware.org/?probe=85894d27fe) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3b8a5a44c7](https://linux-hardware.org/?probe=3b8a5a44c7) | Oct 21, 2023 |
| Dell          | 06FW8P A01                  | [356c2f38aa](https://linux-hardware.org/?probe=356c2f38aa) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | [ca61a8649a](https://linux-hardware.org/?probe=ca61a8649a) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | [6108985945](https://linux-hardware.org/?probe=6108985945) | Oct 21, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [e7cd525d35](https://linux-hardware.org/?probe=e7cd525d35) | Oct 21, 2023 |
| Intel         | DG965RY AAD41691-301        | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ed3ce7aaa6](https://linux-hardware.org/?probe=ed3ce7aaa6) | Oct 18, 2023 |
| MSI           | X470 GAMING PRO             | [e275cfc499](https://linux-hardware.org/?probe=e275cfc499) | Oct 18, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [d652b15856](https://linux-hardware.org/?probe=d652b15856) | Oct 17, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME E... | [3d5d8ee9e6](https://linux-hardware.org/?probe=3d5d8ee9e6) | Oct 17, 2023 |
| Gigabyte      | Z590 VISION D               | [f9d3acd4e2](https://linux-hardware.org/?probe=f9d3acd4e2) | Oct 16, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | [5631fc0230](https://linux-hardware.org/?probe=5631fc0230) | Oct 16, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [04afaee575](https://linux-hardware.org/?probe=04afaee575) | Oct 15, 2023 |
| ASUSTek       | PRIME B450M-A II            | [98224c65b6](https://linux-hardware.org/?probe=98224c65b6) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [47788537bf](https://linux-hardware.org/?probe=47788537bf) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [30723700f1](https://linux-hardware.org/?probe=30723700f1) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [e4dc0eeb72](https://linux-hardware.org/?probe=e4dc0eeb72) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | [abc6dc18ab](https://linux-hardware.org/?probe=abc6dc18ab) | Oct 15, 2023 |
| HP            | 212B                        | [c0b9765d6e](https://linux-hardware.org/?probe=c0b9765d6e) | Oct 15, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [5bbd5682e8](https://linux-hardware.org/?probe=5bbd5682e8) | Oct 15, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [5a1df4c4df](https://linux-hardware.org/?probe=5a1df4c4df) | Oct 14, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a8e7e9b968](https://linux-hardware.org/?probe=a8e7e9b968) | Oct 14, 2023 |
| Gigabyte      | Z590I VISION D              | [725929fa07](https://linux-hardware.org/?probe=725929fa07) | Oct 14, 2023 |
| ASRock        | H97M Anniversary            | [7df48c5c5d](https://linux-hardware.org/?probe=7df48c5c5d) | Oct 14, 2023 |
| Dell          | 0NW6H5 A00                  | [0594aaa28b](https://linux-hardware.org/?probe=0594aaa28b) | Oct 13, 2023 |
| Dell          | 0NW6H5 A00                  | [596e3973bc](https://linux-hardware.org/?probe=596e3973bc) | Oct 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [4d6379353d](https://linux-hardware.org/?probe=4d6379353d) | Oct 13, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [52fdfb249e](https://linux-hardware.org/?probe=52fdfb249e) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | [d7d6c5206f](https://linux-hardware.org/?probe=d7d6c5206f) | Oct 12, 2023 |
| Biostar       | B550GTQ                     | [63f1b39dd4](https://linux-hardware.org/?probe=63f1b39dd4) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | [5e2f8bdc4d](https://linux-hardware.org/?probe=5e2f8bdc4d) | Oct 12, 2023 |
| Shenzhen M... | F6BFC                       | [e71b9295ca](https://linux-hardware.org/?probe=e71b9295ca) | Oct 11, 2023 |
| System76      | Thelio Mega thelio-mega-... | [abb07364c1](https://linux-hardware.org/?probe=abb07364c1) | Oct 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4ce0d26e3c](https://linux-hardware.org/?probe=4ce0d26e3c) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [835f369588](https://linux-hardware.org/?probe=835f369588) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [9acd34e892](https://linux-hardware.org/?probe=9acd34e892) | Oct 11, 2023 |
| ASUSTek       | PRIME Z590-V                | [ee15914a37](https://linux-hardware.org/?probe=ee15914a37) | Oct 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [3d02079672](https://linux-hardware.org/?probe=3d02079672) | Oct 10, 2023 |
| Gigabyte      | X570 GAMING X               | [b09f4a3a8a](https://linux-hardware.org/?probe=b09f4a3a8a) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO             | [c39ce018d6](https://linux-hardware.org/?probe=c39ce018d6) | Oct 10, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2d033cba6c](https://linux-hardware.org/?probe=2d033cba6c) | Oct 08, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3d510e53b4](https://linux-hardware.org/?probe=3d510e53b4) | Oct 08, 2023 |
| MSI           | B450M-A PRO MAX             | [3ac34a911c](https://linux-hardware.org/?probe=3ac34a911c) | Oct 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [a3190a6c6d](https://linux-hardware.org/?probe=a3190a6c6d) | Oct 07, 2023 |
| Gigabyte      | B75M-D3V                    | [17cdd65d6b](https://linux-hardware.org/?probe=17cdd65d6b) | Oct 07, 2023 |
| Huanan        | X99-BD4 V1.33               | [9477d90e51](https://linux-hardware.org/?probe=9477d90e51) | Oct 07, 2023 |
| MSI           | PRO Z690-A WIFI             | [5ec4f81683](https://linux-hardware.org/?probe=5ec4f81683) | Oct 06, 2023 |
| Dell          | 0WR7PY A02                  | [6507df947b](https://linux-hardware.org/?probe=6507df947b) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a308ec4180](https://linux-hardware.org/?probe=a308ec4180) | Oct 06, 2023 |
| Gigabyte      | X570 GAMING X               | [ebbd23f352](https://linux-hardware.org/?probe=ebbd23f352) | Oct 05, 2023 |
| Unknown       | Unknown                     | [3f779c87f6](https://linux-hardware.org/?probe=3f779c87f6) | Oct 05, 2023 |
| HP            | 0AA4h                       | [8e4a645689](https://linux-hardware.org/?probe=8e4a645689) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5932daaa4e](https://linux-hardware.org/?probe=5932daaa4e) | Oct 03, 2023 |
| ASRock        | Z790 PG Riptide             | [82630a534f](https://linux-hardware.org/?probe=82630a534f) | Oct 03, 2023 |
| Kllisre       | X79 V1.2                    | [fb9b29c804](https://linux-hardware.org/?probe=fb9b29c804) | Oct 03, 2023 |
| ASUSTek       | P8H77-M PRO                 | [bc03d7f758](https://linux-hardware.org/?probe=bc03d7f758) | Oct 02, 2023 |
| ASUSTek       | B150M-C/BR                  | [2435f20a18](https://linux-hardware.org/?probe=2435f20a18) | Oct 02, 2023 |
| MSI           | B450M-A PRO MAX             | [57ddb0f758](https://linux-hardware.org/?probe=57ddb0f758) | Oct 01, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [d16a64a7e1](https://linux-hardware.org/?probe=d16a64a7e1) | Oct 01, 2023 |
| Gigabyte      | H61M-S2PV                   | [691c015f6f](https://linux-hardware.org/?probe=691c015f6f) | Oct 01, 2023 |
| HP            | 8054                        | [20f337b1e7](https://linux-hardware.org/?probe=20f337b1e7) | Sep 29, 2023 |
| AZW           | SER V1                      | [10660522cb](https://linux-hardware.org/?probe=10660522cb) | Sep 28, 2023 |
| ASRock        | A520M-HDV                   | [d19f334f02](https://linux-hardware.org/?probe=d19f334f02) | Sep 28, 2023 |
| MSI           | PRO Z690-A WIFI             | [2ede90f6eb](https://linux-hardware.org/?probe=2ede90f6eb) | Sep 28, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [240ff7b72a](https://linux-hardware.org/?probe=240ff7b72a) | Sep 27, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5a73611f4d](https://linux-hardware.org/?probe=5a73611f4d) | Sep 26, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [0a5cc18946](https://linux-hardware.org/?probe=0a5cc18946) | Sep 26, 2023 |
| ASUSTek       | P5QPL-AM                    | [4259a21921](https://linux-hardware.org/?probe=4259a21921) | Sep 26, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | [2fe436c443](https://linux-hardware.org/?probe=2fe436c443) | Sep 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [a58111d9ae](https://linux-hardware.org/?probe=a58111d9ae) | Sep 25, 2023 |
| ASUSTek       | M4A79T Deluxe               | [ac151127e1](https://linux-hardware.org/?probe=ac151127e1) | Sep 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [3346cccd71](https://linux-hardware.org/?probe=3346cccd71) | Sep 24, 2023 |
| MSI           | B350 TOMAHAWK               | [7119229a1b](https://linux-hardware.org/?probe=7119229a1b) | Sep 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [a3e2e5f3c0](https://linux-hardware.org/?probe=a3e2e5f3c0) | Sep 24, 2023 |
| Unknown       | Unknown                     | [9be7572b83](https://linux-hardware.org/?probe=9be7572b83) | Sep 23, 2023 |
| Unknown       | Unknown                     | [b063963175](https://linux-hardware.org/?probe=b063963175) | Sep 23, 2023 |
| MSI           | X399 SLI PLUS               | [1c755bb49f](https://linux-hardware.org/?probe=1c755bb49f) | Sep 23, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | [32b162a364](https://linux-hardware.org/?probe=32b162a364) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [6656c28ec7](https://linux-hardware.org/?probe=6656c28ec7) | Sep 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [9867cb03bb](https://linux-hardware.org/?probe=9867cb03bb) | Sep 23, 2023 |
| Dell          | 0GWHMW A00                  | [d344d1e396](https://linux-hardware.org/?probe=d344d1e396) | Sep 23, 2023 |
| ASUSTek       | Crosshair IV Formula        | [4679088d4e](https://linux-hardware.org/?probe=4679088d4e) | Sep 22, 2023 |
| Hardkernel    | ODROID-H3                   | [19d1333b4f](https://linux-hardware.org/?probe=19d1333b4f) | Sep 21, 2023 |
| Dell          | 0F6X5P A00                  | [5e45e8b196](https://linux-hardware.org/?probe=5e45e8b196) | Sep 21, 2023 |
| ASUSTek       | M5A78L/USB3                 | [e1805d26c3](https://linux-hardware.org/?probe=e1805d26c3) | Sep 17, 2023 |
| ASRockRack    | Z490D4U-2L2T                | [0d43dbb11d](https://linux-hardware.org/?probe=0d43dbb11d) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [e0371fc03e](https://linux-hardware.org/?probe=e0371fc03e) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [43bf92a01b](https://linux-hardware.org/?probe=43bf92a01b) | Sep 17, 2023 |
| Gigabyte      | Z270X-UD5-CF                | [5c77a043ae](https://linux-hardware.org/?probe=5c77a043ae) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [efda5ec51a](https://linux-hardware.org/?probe=efda5ec51a) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [ebac37bdbd](https://linux-hardware.org/?probe=ebac37bdbd) | Sep 14, 2023 |
| ASRock        | X470 Taichi                 | [49aca37979](https://linux-hardware.org/?probe=49aca37979) | Sep 13, 2023 |
| Lenovo        | 3717 NO DPK                 | [13870a17b4](https://linux-hardware.org/?probe=13870a17b4) | Sep 13, 2023 |
| Dell          | 0YXT71 A01                  | [36991ac5a6](https://linux-hardware.org/?probe=36991ac5a6) | Sep 11, 2023 |
| Shenzhen M... | F6BFC                       | [ca89a07b9e](https://linux-hardware.org/?probe=ca89a07b9e) | Sep 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [56bef39b59](https://linux-hardware.org/?probe=56bef39b59) | Sep 10, 2023 |
| ASUSTek       | Z170-A                      | [a812c1659b](https://linux-hardware.org/?probe=a812c1659b) | Sep 09, 2023 |
| MSI           | MAG B560M BAZOOKA           | [c3ba2033e2](https://linux-hardware.org/?probe=c3ba2033e2) | Sep 09, 2023 |
| Gigabyte      | Q87M-MK                     | [1c45c834fe](https://linux-hardware.org/?probe=1c45c834fe) | Sep 09, 2023 |
| HP            | 1495                        | [b56f622d7a](https://linux-hardware.org/?probe=b56f622d7a) | Sep 09, 2023 |
| Gigabyte      | F2A68HM-H                   | [bad7c8bf82](https://linux-hardware.org/?probe=bad7c8bf82) | Sep 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [3221a3e5dd](https://linux-hardware.org/?probe=3221a3e5dd) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bae1c4e9](https://linux-hardware.org/?probe=13bae1c4e9) | Sep 07, 2023 |
| Dell          | 0WN7Y6 A02                  | [aaf64e4624](https://linux-hardware.org/?probe=aaf64e4624) | Sep 07, 2023 |
| Biostar       | A58MD                       | [40f078fcfc](https://linux-hardware.org/?probe=40f078fcfc) | Sep 06, 2023 |
| MSI           | H310M PRO-VH PLUS           | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| Gigabyte      | Z590 AORUS MASTER           | [40785211e9](https://linux-hardware.org/?probe=40785211e9) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B460-H GAMING     | [865ce7b55b](https://linux-hardware.org/?probe=865ce7b55b) | Sep 04, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [a30ea8885d](https://linux-hardware.org/?probe=a30ea8885d) | Sep 03, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [e9faf4759d](https://linux-hardware.org/?probe=e9faf4759d) | Sep 03, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | [ffc201e884](https://linux-hardware.org/?probe=ffc201e884) | Sep 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [b4907a6220](https://linux-hardware.org/?probe=b4907a6220) | Sep 02, 2023 |
| MSI           | A320M-A PRO M2              | [6745b7e37d](https://linux-hardware.org/?probe=6745b7e37d) | Sep 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [6ddc9b767d](https://linux-hardware.org/?probe=6ddc9b767d) | Sep 01, 2023 |
| MSI           | 760GM-P23                   | [76b83d4e93](https://linux-hardware.org/?probe=76b83d4e93) | Sep 01, 2023 |
| System76      | Thelio thelio-r3            | [d0cdea5d23](https://linux-hardware.org/?probe=d0cdea5d23) | Sep 01, 2023 |
| Gigabyte      | H97-HD3                     | [ba11958a48](https://linux-hardware.org/?probe=ba11958a48) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | [158ed240bf](https://linux-hardware.org/?probe=158ed240bf) | Aug 31, 2023 |
| ASRock        | Q1900B-ITX                  | [875427cd72](https://linux-hardware.org/?probe=875427cd72) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [085b3d4330](https://linux-hardware.org/?probe=085b3d4330) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [98b18bb67a](https://linux-hardware.org/?probe=98b18bb67a) | Aug 31, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [45f86c066d](https://linux-hardware.org/?probe=45f86c066d) | Aug 30, 2023 |
| Unknown       | Unknown                     | [ebebe5ddf7](https://linux-hardware.org/?probe=ebebe5ddf7) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [0be67de1c9](https://linux-hardware.org/?probe=0be67de1c9) | Aug 29, 2023 |
| Dell          | 0VRWRC A00                  | [e3a47f55c9](https://linux-hardware.org/?probe=e3a47f55c9) | Aug 26, 2023 |
| MSI           | PRO Z790-A WIFI             | [f3874bf2fc](https://linux-hardware.org/?probe=f3874bf2fc) | Aug 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [8d952e28e1](https://linux-hardware.org/?probe=8d952e28e1) | Aug 25, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [51d4eefbc9](https://linux-hardware.org/?probe=51d4eefbc9) | Aug 25, 2023 |
| System76      | Thelio Major thelio-majo... | [e5caa63b77](https://linux-hardware.org/?probe=e5caa63b77) | Aug 25, 2023 |
| HP            | 0B4Ch D                     | [958521d2be](https://linux-hardware.org/?probe=958521d2be) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [254f8aee40](https://linux-hardware.org/?probe=254f8aee40) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [6f72852248](https://linux-hardware.org/?probe=6f72852248) | Aug 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c0bf920a5b](https://linux-hardware.org/?probe=c0bf920a5b) | Aug 24, 2023 |
| ASRock        | B450 Steel Legend           | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| HP            | 0B4Ch D                     | [5abce3a991](https://linux-hardware.org/?probe=5abce3a991) | Aug 23, 2023 |
| HP            | 18E7                        | [a78496c36e](https://linux-hardware.org/?probe=a78496c36e) | Aug 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [145d800029](https://linux-hardware.org/?probe=145d800029) | Aug 23, 2023 |
| ASUSTek       | P7P55-M                     | [0f5028d5fc](https://linux-hardware.org/?probe=0f5028d5fc) | Aug 22, 2023 |
| AZW           | GTR V02                     | [d699113f95](https://linux-hardware.org/?probe=d699113f95) | Aug 21, 2023 |
| NZXT          | N7 B550                     | [1f105eadd8](https://linux-hardware.org/?probe=1f105eadd8) | Aug 20, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [31861c8357](https://linux-hardware.org/?probe=31861c8357) | Aug 20, 2023 |
| Gigabyte      | Z270X-UD5-CF                | [04df52e837](https://linux-hardware.org/?probe=04df52e837) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [63d06430e4](https://linux-hardware.org/?probe=63d06430e4) | Aug 18, 2023 |
| HP            | 0266                        | [636546711d](https://linux-hardware.org/?probe=636546711d) | Aug 18, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [53c4af621d](https://linux-hardware.org/?probe=53c4af621d) | Aug 18, 2023 |
| HP            | 2AF7                        | [4e55d08586](https://linux-hardware.org/?probe=4e55d08586) | Aug 17, 2023 |
| MSI           | Z87-GD65 GAMING             | [7c09135f98](https://linux-hardware.org/?probe=7c09135f98) | Aug 17, 2023 |
| Positivo      | POS-RIQ470EN 11190998       | [1eec60309a](https://linux-hardware.org/?probe=1eec60309a) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0927025cfc](https://linux-hardware.org/?probe=0927025cfc) | Aug 15, 2023 |
| Intel         | B75A                        | [c081fb2ca8](https://linux-hardware.org/?probe=c081fb2ca8) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0b194349eb](https://linux-hardware.org/?probe=0b194349eb) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [9a8e4bc08d](https://linux-hardware.org/?probe=9a8e4bc08d) | Aug 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [302fb03dce](https://linux-hardware.org/?probe=302fb03dce) | Aug 13, 2023 |
| ASUSTek       | PRIME B350M-A               | [2c2aca991d](https://linux-hardware.org/?probe=2c2aca991d) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [ee66d3a81c](https://linux-hardware.org/?probe=ee66d3a81c) | Aug 13, 2023 |
| MSI           | X99A GODLIKE GAMING         | [b87f112952](https://linux-hardware.org/?probe=b87f112952) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | [edf714498f](https://linux-hardware.org/?probe=edf714498f) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | [213d229837](https://linux-hardware.org/?probe=213d229837) | Aug 13, 2023 |
| Intel         | B75A                        | [91f9e56ace](https://linux-hardware.org/?probe=91f9e56ace) | Aug 12, 2023 |
| HP            | 8643 SMVB                   | [2832e701f2](https://linux-hardware.org/?probe=2832e701f2) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [2c92ed92eb](https://linux-hardware.org/?probe=2c92ed92eb) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [580fda2e6b](https://linux-hardware.org/?probe=580fda2e6b) | Aug 12, 2023 |
| MSI           | A55M-E33                    | [7d538db764](https://linux-hardware.org/?probe=7d538db764) | Aug 12, 2023 |
| MSI           | A55M-E33                    | [9e64865fbc](https://linux-hardware.org/?probe=9e64865fbc) | Aug 12, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [a6d2358585](https://linux-hardware.org/?probe=a6d2358585) | Aug 11, 2023 |
| Unknown       | Unknown                     | [cf0d6729b4](https://linux-hardware.org/?probe=cf0d6729b4) | Aug 11, 2023 |
| ASRock        | B650M-HDV/M.2               | [ffd395aee0](https://linux-hardware.org/?probe=ffd395aee0) | Aug 11, 2023 |
| Gigabyte      | H410M S2 V2                 | [d4c5a12d06](https://linux-hardware.org/?probe=d4c5a12d06) | Aug 10, 2023 |
| HP            | 2AF9                        | [b31b796804](https://linux-hardware.org/?probe=b31b796804) | Aug 10, 2023 |
| Gigabyte      | B450 AORUS M                | [739bc450b8](https://linux-hardware.org/?probe=739bc450b8) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | [b1a8fc0704](https://linux-hardware.org/?probe=b1a8fc0704) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | [920797388b](https://linux-hardware.org/?probe=920797388b) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [13b739e83a](https://linux-hardware.org/?probe=13b739e83a) | Aug 09, 2023 |
| NZXT          | N7 Z590                     | [3831033bdc](https://linux-hardware.org/?probe=3831033bdc) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [c4ac4952a4](https://linux-hardware.org/?probe=c4ac4952a4) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [62a5817462](https://linux-hardware.org/?probe=62a5817462) | Aug 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6abad99081](https://linux-hardware.org/?probe=6abad99081) | Aug 08, 2023 |
| ASUSTek       | P5Q                         | [f485bf4b6e](https://linux-hardware.org/?probe=f485bf4b6e) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [58208c1f16](https://linux-hardware.org/?probe=58208c1f16) | Aug 08, 2023 |
| Unknown       | Unknown                     | [45fe14954d](https://linux-hardware.org/?probe=45fe14954d) | Aug 07, 2023 |
| Unknown       | Unknown                     | [d1bca9ae8b](https://linux-hardware.org/?probe=d1bca9ae8b) | Aug 07, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [ac2bdfc67b](https://linux-hardware.org/?probe=ac2bdfc67b) | Aug 06, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [93917e587f](https://linux-hardware.org/?probe=93917e587f) | Aug 06, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [4e0084cd74](https://linux-hardware.org/?probe=4e0084cd74) | Aug 05, 2023 |
| MSI           | 760GM-P23                   | [5746742389](https://linux-hardware.org/?probe=5746742389) | Aug 04, 2023 |
| ASRock        | X370 Taichi                 | [af453d6ef1](https://linux-hardware.org/?probe=af453d6ef1) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [92ef92268a](https://linux-hardware.org/?probe=92ef92268a) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [ca1a97268c](https://linux-hardware.org/?probe=ca1a97268c) | Aug 04, 2023 |
| Dell          | 0KWVT8 A03                  | [6ec952b536](https://linux-hardware.org/?probe=6ec952b536) | Aug 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [983329d56b](https://linux-hardware.org/?probe=983329d56b) | Aug 03, 2023 |
| JHZD          | X830                        | [7de7f6bb75](https://linux-hardware.org/?probe=7de7f6bb75) | Aug 03, 2023 |
| JHZD          | X830                        | [4fed3648c0](https://linux-hardware.org/?probe=4fed3648c0) | Aug 03, 2023 |
| ASUSTek       | P5QPL-AM                    | [2254be2ae2](https://linux-hardware.org/?probe=2254be2ae2) | Aug 03, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [1a9566fa0a](https://linux-hardware.org/?probe=1a9566fa0a) | Aug 03, 2023 |
| Dell          | 07PR60 A00                  | [590695e09f](https://linux-hardware.org/?probe=590695e09f) | Aug 02, 2023 |
| HP            | 8054                        | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| HP            | 8309                        | [6cb1cfc925](https://linux-hardware.org/?probe=6cb1cfc925) | Aug 02, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [41d4bd6cfe](https://linux-hardware.org/?probe=41d4bd6cfe) | Aug 01, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [3a655f04e1](https://linux-hardware.org/?probe=3a655f04e1) | Aug 01, 2023 |
| ASRock        | B450M/ac                    | [82be4b3dfb](https://linux-hardware.org/?probe=82be4b3dfb) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1c44863a1c](https://linux-hardware.org/?probe=1c44863a1c) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [030f8afe2d](https://linux-hardware.org/?probe=030f8afe2d) | Jul 31, 2023 |
| ASUSTek       | Z87-K                       | [ed53779d9a](https://linux-hardware.org/?probe=ed53779d9a) | Jul 31, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [d1d59592c3](https://linux-hardware.org/?probe=d1d59592c3) | Jul 30, 2023 |
| ASUSTek       | Z170-PRO                    | [ac4682042f](https://linux-hardware.org/?probe=ac4682042f) | Jul 30, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [44937ea360](https://linux-hardware.org/?probe=44937ea360) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [96b197dffc](https://linux-hardware.org/?probe=96b197dffc) | Jul 29, 2023 |
| HP            | 3646h                       | [e00952810b](https://linux-hardware.org/?probe=e00952810b) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [bc88e3dbae](https://linux-hardware.org/?probe=bc88e3dbae) | Jul 28, 2023 |
| ASRock        | X670E PG Lightning          | [b5fec7d5ff](https://linux-hardware.org/?probe=b5fec7d5ff) | Jul 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [f4941e530b](https://linux-hardware.org/?probe=f4941e530b) | Jul 28, 2023 |
| System76      | Thelio Mira thelio-mira-... | [785fb534be](https://linux-hardware.org/?probe=785fb534be) | Jul 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [aac37c9ed6](https://linux-hardware.org/?probe=aac37c9ed6) | Jul 27, 2023 |
| Gigabyte      | H61M-S2PV                   | [0be5bf84c6](https://linux-hardware.org/?probe=0be5bf84c6) | Jul 27, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [b9bba11373](https://linux-hardware.org/?probe=b9bba11373) | Jul 27, 2023 |
| Gigabyte      | B550 VISION D-P             | [2c300ff820](https://linux-hardware.org/?probe=2c300ff820) | Jul 27, 2023 |
| Dell          | 07PR60 A00                  | [67ef05bdd5](https://linux-hardware.org/?probe=67ef05bdd5) | Jul 27, 2023 |
| Intel         | H81                         | [6fa9f0cd2d](https://linux-hardware.org/?probe=6fa9f0cd2d) | Jul 27, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [247f6d8816](https://linux-hardware.org/?probe=247f6d8816) | Jul 27, 2023 |
| Dell          | 0YXG0N A00                  | [fb365f50a0](https://linux-hardware.org/?probe=fb365f50a0) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Gigabyte      | H81M-H                      | [50cf88ae28](https://linux-hardware.org/?probe=50cf88ae28) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bf4dff1328](https://linux-hardware.org/?probe=bf4dff1328) | Jul 23, 2023 |
| MSI           | Boston                      | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| ASRock        | B550M Pro4                  | [46283ad18b](https://linux-hardware.org/?probe=46283ad18b) | Jul 22, 2023 |
| MSI           | Z97 PC Mate                 | [f4cddb5e86](https://linux-hardware.org/?probe=f4cddb5e86) | Jul 22, 2023 |
| Intel         | X99H                        | [474e78b162](https://linux-hardware.org/?probe=474e78b162) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| MSI           | Z370-A PRO                  | [9a1d731109](https://linux-hardware.org/?probe=9a1d731109) | Jul 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d23dfad700](https://linux-hardware.org/?probe=d23dfad700) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ebb1eed757](https://linux-hardware.org/?probe=ebb1eed757) | Jul 20, 2023 |
| ASUSTek       | Z97-A                       | [fe36d4fde0](https://linux-hardware.org/?probe=fe36d4fde0) | Jul 19, 2023 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [1dc0977942](https://linux-hardware.org/?probe=1dc0977942) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1f57cb78e8](https://linux-hardware.org/?probe=1f57cb78e8) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d3413475e2](https://linux-hardware.org/?probe=d3413475e2) | Jul 18, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | [199e0d2e12](https://linux-hardware.org/?probe=199e0d2e12) | Jul 18, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [69f0859638](https://linux-hardware.org/?probe=69f0859638) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [25737bce66](https://linux-hardware.org/?probe=25737bce66) | Jul 17, 2023 |
| MSI           | MAG B550M MORTAR            | [83175318ff](https://linux-hardware.org/?probe=83175318ff) | Jul 16, 2023 |
| Alienware     | 0XJKKD A01                  | [b47699e30d](https://linux-hardware.org/?probe=b47699e30d) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| Dell          | 02YYK5 A01                  | [e984f2562d](https://linux-hardware.org/?probe=e984f2562d) | Jul 16, 2023 |
| Gigabyte      | 970A-DS3P                   | [32b56b85c4](https://linux-hardware.org/?probe=32b56b85c4) | Jul 15, 2023 |
| MSI           | PRO Z790-A WIFI             | [c1dba9e7b8](https://linux-hardware.org/?probe=c1dba9e7b8) | Jul 14, 2023 |
| HP            | 0B40h                       | [b452ab2c8d](https://linux-hardware.org/?probe=b452ab2c8d) | Jul 14, 2023 |
| ASUSTek       | B85M-G                      | [2afe11b7e4](https://linux-hardware.org/?probe=2afe11b7e4) | Jul 13, 2023 |
| HP            | 0AA8h                       | [297e7364cb](https://linux-hardware.org/?probe=297e7364cb) | Jul 13, 2023 |
| ASUSTek       | P8B75-M                     | [df7a7f2c36](https://linux-hardware.org/?probe=df7a7f2c36) | Jul 13, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [2f5bf1f247](https://linux-hardware.org/?probe=2f5bf1f247) | Jul 12, 2023 |
| HP            | 0AA8h                       | [db16057ca8](https://linux-hardware.org/?probe=db16057ca8) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | [a95cc808e9](https://linux-hardware.org/?probe=a95cc808e9) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | [d962460a5e](https://linux-hardware.org/?probe=d962460a5e) | Jul 12, 2023 |
| ASUSTek       | PRIME B550M-A               | [d08295d5f4](https://linux-hardware.org/?probe=d08295d5f4) | Jul 12, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [ee2dc6ac7b](https://linux-hardware.org/?probe=ee2dc6ac7b) | Jul 11, 2023 |
| Biostar       | A960D+V2                    | [e6bfab517b](https://linux-hardware.org/?probe=e6bfab517b) | Jul 10, 2023 |
| Positivo      | POS-MIH61CF POSITIVO        | [02113d0b75](https://linux-hardware.org/?probe=02113d0b75) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [b581326f50](https://linux-hardware.org/?probe=b581326f50) | Jul 10, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [a4650f89f7](https://linux-hardware.org/?probe=a4650f89f7) | Jul 10, 2023 |
| Gigabyte      | Z270-Gaming K3              | [3937b5d17a](https://linux-hardware.org/?probe=3937b5d17a) | Jul 09, 2023 |
| Gigabyte      | Z270-Gaming K3              | [0aea3d9721](https://linux-hardware.org/?probe=0aea3d9721) | Jul 09, 2023 |
| HP            | 8918                        | [af366ea249](https://linux-hardware.org/?probe=af366ea249) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [80164b7a44](https://linux-hardware.org/?probe=80164b7a44) | Jul 07, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [d122a1cedc](https://linux-hardware.org/?probe=d122a1cedc) | Jul 07, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [88649252eb](https://linux-hardware.org/?probe=88649252eb) | Jul 06, 2023 |
| MSI           | Z97 PC Mate                 | [495b6e6e4a](https://linux-hardware.org/?probe=495b6e6e4a) | Jul 06, 2023 |
| MSI           | B350 GAMING PLUS            | [8115e08748](https://linux-hardware.org/?probe=8115e08748) | Jul 05, 2023 |
| MSI           | Z97 PC Mate                 | [0d9ce2b3d2](https://linux-hardware.org/?probe=0d9ce2b3d2) | Jul 05, 2023 |
| Unknown       | 1.31                        | [d34eb9e5d4](https://linux-hardware.org/?probe=d34eb9e5d4) | Jul 05, 2023 |
| Gigabyte      | A320M-H-CF                  | [e2706e4472](https://linux-hardware.org/?probe=e2706e4472) | Jul 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [6013dcdf1e](https://linux-hardware.org/?probe=6013dcdf1e) | Jul 04, 2023 |
| ASUSTek       | PRIME B365M-A               | [bc423a1cb9](https://linux-hardware.org/?probe=bc423a1cb9) | Jul 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [a44e9e946f](https://linux-hardware.org/?probe=a44e9e946f) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [cc5348e995](https://linux-hardware.org/?probe=cc5348e995) | Jul 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b8ff99b486](https://linux-hardware.org/?probe=b8ff99b486) | Jul 03, 2023 |
| ASRock        | B450M/ac                    | [1f5703db9b](https://linux-hardware.org/?probe=1f5703db9b) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [73015ee7be](https://linux-hardware.org/?probe=73015ee7be) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [6db9b5e42a](https://linux-hardware.org/?probe=6db9b5e42a) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [73d4fb6c33](https://linux-hardware.org/?probe=73d4fb6c33) | Jul 02, 2023 |
| Dell          | 02GDWG A00                  | [228db73d17](https://linux-hardware.org/?probe=228db73d17) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | [38e6f08816](https://linux-hardware.org/?probe=38e6f08816) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | [7797ece08f](https://linux-hardware.org/?probe=7797ece08f) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [18b6484d81](https://linux-hardware.org/?probe=18b6484d81) | Jul 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [a70ec8bdf1](https://linux-hardware.org/?probe=a70ec8bdf1) | Jul 01, 2023 |
| Gigabyte      | B550 UD AC                  | [7d7d37522c](https://linux-hardware.org/?probe=7d7d37522c) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [878e617ba4](https://linux-hardware.org/?probe=878e617ba4) | Jun 30, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [cdb77bf9b6](https://linux-hardware.org/?probe=cdb77bf9b6) | Jun 30, 2023 |
| Dell          | 0M6C7G A00                  | [d7dfcc4a38](https://linux-hardware.org/?probe=d7dfcc4a38) | Jun 30, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [323464eebb](https://linux-hardware.org/?probe=323464eebb) | Jun 28, 2023 |
| Dell          | 08NPPY A00                  | [b1b4052442](https://linux-hardware.org/?probe=b1b4052442) | Jun 28, 2023 |
| ASUSTek       | GA35DX                      | [a91acc04b6](https://linux-hardware.org/?probe=a91acc04b6) | Jun 28, 2023 |
| Dell          | 02YYK5 A01                  | [4054ebeac8](https://linux-hardware.org/?probe=4054ebeac8) | Jun 28, 2023 |
| Dell          | 0F6X5P A00                  | [cad43414b4](https://linux-hardware.org/?probe=cad43414b4) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [1bd3b2b912](https://linux-hardware.org/?probe=1bd3b2b912) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d436c6bcdf](https://linux-hardware.org/?probe=d436c6bcdf) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [3907252056](https://linux-hardware.org/?probe=3907252056) | Jun 25, 2023 |
| MSI           | B450M MORTAR                | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| Shenzhen M... | F6BFC                       | [7f13c620bf](https://linux-hardware.org/?probe=7f13c620bf) | Jun 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| MSI           | H77MA-G43                   | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [082d9a4988](https://linux-hardware.org/?probe=082d9a4988) | Jun 22, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [3c27e4a91d](https://linux-hardware.org/?probe=3c27e4a91d) | Jun 22, 2023 |
| ASUSTek       | PRIME Z490-A                | [f7c2ec659b](https://linux-hardware.org/?probe=f7c2ec659b) | Jun 22, 2023 |
| Intel         | H55                         | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| HP            | 89B5 A                      | [01e8a85a35](https://linux-hardware.org/?probe=01e8a85a35) | Jun 21, 2023 |
| ASUSTek       | Maximus VI HERO             | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | [4a18635ad7](https://linux-hardware.org/?probe=4a18635ad7) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | [1d14950f1e](https://linux-hardware.org/?probe=1d14950f1e) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | [46baecef13](https://linux-hardware.org/?probe=46baecef13) | Jun 20, 2023 |
| BESSTAR Te... | HM90                        | [796769b68a](https://linux-hardware.org/?probe=796769b68a) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | [d2550efee5](https://linux-hardware.org/?probe=d2550efee5) | Jun 19, 2023 |
| ASRock        | B450 Steel Legend           | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| ASUSTek       | Maximus VI HERO             | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| HP            | 8949 11                     | [bd6b95fc23](https://linux-hardware.org/?probe=bd6b95fc23) | Jun 18, 2023 |
| Biostar       | A320MH                      | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| ASRock        | Z77 Extreme4                | [c45aea7474](https://linux-hardware.org/?probe=c45aea7474) | Jun 18, 2023 |
| BESSTAR Te... | B550                        | [6c2811bbf5](https://linux-hardware.org/?probe=6c2811bbf5) | Jun 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | [c2f10ad55c](https://linux-hardware.org/?probe=c2f10ad55c) | Jun 17, 2023 |
| ASUSTek       | P5QPL-AM                    | [2b3a058830](https://linux-hardware.org/?probe=2b3a058830) | Jun 17, 2023 |
| MSI           | H67MA-E35                   | [8b37f91738](https://linux-hardware.org/?probe=8b37f91738) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| Gigabyte      | B450M S2H                   | [1bcfd50d08](https://linux-hardware.org/?probe=1bcfd50d08) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | [04b5148080](https://linux-hardware.org/?probe=04b5148080) | Jun 15, 2023 |
| ASUSTek       | P6T DELUXE V2               | [887bfc11d5](https://linux-hardware.org/?probe=887bfc11d5) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [5281ad2271](https://linux-hardware.org/?probe=5281ad2271) | Jun 13, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| Pegatron      | NARRA5                      | [3e7cbbb991](https://linux-hardware.org/?probe=3e7cbbb991) | Jun 12, 2023 |
| MSI           | MEG X570 UNIFY              | [1f4d0ebdc1](https://linux-hardware.org/?probe=1f4d0ebdc1) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [a9bb4cfb62](https://linux-hardware.org/?probe=a9bb4cfb62) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9c0f9bf219](https://linux-hardware.org/?probe=9c0f9bf219) | Jun 12, 2023 |
| BESSTAR Te... | B550                        | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| Pegatron      | NARRA5                      | [609c2921d3](https://linux-hardware.org/?probe=609c2921d3) | Jun 11, 2023 |
| BESSTAR Te... | HM90                        | [86c52dcc7a](https://linux-hardware.org/?probe=86c52dcc7a) | Jun 11, 2023 |
| HP            | 89B5 A                      | [7bf638dc35](https://linux-hardware.org/?probe=7bf638dc35) | Jun 10, 2023 |
| MSI           | X99A GODLIKE GAMING         | [19511501c7](https://linux-hardware.org/?probe=19511501c7) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| HP            | 8949 11                     | [f5e1f4b6c9](https://linux-hardware.org/?probe=f5e1f4b6c9) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [cac24c37e5](https://linux-hardware.org/?probe=cac24c37e5) | Jun 10, 2023 |
| Gigabyte      | B450 AORUS M                | [280baa2765](https://linux-hardware.org/?probe=280baa2765) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS M                | [50b022f065](https://linux-hardware.org/?probe=50b022f065) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1189f6696f](https://linux-hardware.org/?probe=1189f6696f) | Jun 09, 2023 |
| ASUSTek       | M4A785G-HTPC                | [76304dfb4a](https://linux-hardware.org/?probe=76304dfb4a) | Jun 09, 2023 |
| AZW           | SEi                         | [2b085e7ed2](https://linux-hardware.org/?probe=2b085e7ed2) | Jun 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | [70c409a2b8](https://linux-hardware.org/?probe=70c409a2b8) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| System76      | Thelio Mira thelio-mira-... | [d7d155d89d](https://linux-hardware.org/?probe=d7d155d89d) | Jun 07, 2023 |
| HP            | 8949 11                     | [06bca18276](https://linux-hardware.org/?probe=06bca18276) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| MSI           | A55M-E33                    | [336b7f877d](https://linux-hardware.org/?probe=336b7f877d) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Foxconn       | A74ML-K                     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| HP            | 8949 11                     | [f06749002f](https://linux-hardware.org/?probe=f06749002f) | Jun 03, 2023 |
| ASUSTek       | PRIME B365M-A               | [5c280bbd6c](https://linux-hardware.org/?probe=5c280bbd6c) | Jun 03, 2023 |
| MSI           | B150M MORTAR                | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [b86be4f1de](https://linux-hardware.org/?probe=b86be4f1de) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| Dell          | 0GY6Y8 A02                  | [7f2c514dff](https://linux-hardware.org/?probe=7f2c514dff) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| HP            | 212A                        | [a0e56b03e2](https://linux-hardware.org/?probe=a0e56b03e2) | Jun 01, 2023 |
| MSI           | B350M BAZOOKA               | [a494d94087](https://linux-hardware.org/?probe=a494d94087) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| MSI           | B350M PRO-VD PLUS           | [ca4e5a8f82](https://linux-hardware.org/?probe=ca4e5a8f82) | May 30, 2023 |
| BESSTAR Te... | HM90                        | [cb78f83d80](https://linux-hardware.org/?probe=cb78f83d80) | May 30, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | [4cbc2f9044](https://linux-hardware.org/?probe=4cbc2f9044) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | [1793fc9d72](https://linux-hardware.org/?probe=1793fc9d72) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | [94fda2dea0](https://linux-hardware.org/?probe=94fda2dea0) | May 30, 2023 |
| ASUSTek       | M5A97                       | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Dell          | 0NM64V A01                  | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | [6729d5ffa7](https://linux-hardware.org/?probe=6729d5ffa7) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8b1445b47c](https://linux-hardware.org/?probe=8b1445b47c) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [06318d2354](https://linux-hardware.org/?probe=06318d2354) | May 29, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [c24eb2f7dd](https://linux-hardware.org/?probe=c24eb2f7dd) | May 29, 2023 |
| ASUSTek       | Crosshair IV Formula        | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| AZW           | EQ                          | [8e6c18ebbb](https://linux-hardware.org/?probe=8e6c18ebbb) | May 28, 2023 |
| AZW           | EQ                          | [98e5ea581c](https://linux-hardware.org/?probe=98e5ea581c) | May 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [46460561e1](https://linux-hardware.org/?probe=46460561e1) | May 27, 2023 |
| ASRock        | X670E Steel Legend          | [b2672eb1db](https://linux-hardware.org/?probe=b2672eb1db) | May 27, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ea5ba11b48](https://linux-hardware.org/?probe=ea5ba11b48) | May 27, 2023 |
| Gigabyte      | H61M-S2PV                   | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| ASRock        | X300M-STX                   | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 0AA4h                       | [41ec821e77](https://linux-hardware.org/?probe=41ec821e77) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| ASUSTek       | G20AJ                       | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [31ea0c4ab8](https://linux-hardware.org/?probe=31ea0c4ab8) | May 24, 2023 |
| HP            | 212A                        | [87b3c9809f](https://linux-hardware.org/?probe=87b3c9809f) | May 23, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [8604115d8b](https://linux-hardware.org/?probe=8604115d8b) | May 23, 2023 |
| MSI           | B150M MORTAR                | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [e781194fb3](https://linux-hardware.org/?probe=e781194fb3) | May 23, 2023 |
| Gigabyte      | B660M AORUS PRO DDR4        | [6a3afbb593](https://linux-hardware.org/?probe=6a3afbb593) | May 20, 2023 |
| Dell          | 0VTJVC A00                  | [1acd938f30](https://linux-hardware.org/?probe=1acd938f30) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [7384b29d21](https://linux-hardware.org/?probe=7384b29d21) | May 20, 2023 |
| Samsung       | DeskTop System              | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [e16a632eca](https://linux-hardware.org/?probe=e16a632eca) | May 20, 2023 |
| Gigabyte      | H61M-S2PV                   | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a100e90e0b](https://linux-hardware.org/?probe=a100e90e0b) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [986792e4f0](https://linux-hardware.org/?probe=986792e4f0) | May 19, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [75d3691dae](https://linux-hardware.org/?probe=75d3691dae) | May 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [994adfd229](https://linux-hardware.org/?probe=994adfd229) | May 18, 2023 |
| Dell          | 0KWVT8 A03                  | [e28f96322d](https://linux-hardware.org/?probe=e28f96322d) | May 18, 2023 |
| Gigabyte      | H410M S2 V2                 | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [06003cbcc2](https://linux-hardware.org/?probe=06003cbcc2) | May 18, 2023 |
| PS            | X570 Pro4                   | [cde38918e6](https://linux-hardware.org/?probe=cde38918e6) | May 18, 2023 |
| Gigabyte      | B450M H                     | [a1cb84300e](https://linux-hardware.org/?probe=a1cb84300e) | May 18, 2023 |
| Dell          | 048DY8 A01                  | [aaf390dad1](https://linux-hardware.org/?probe=aaf390dad1) | May 17, 2023 |
| EVGA          | 151-HE-E999                 | [aa87f447d5](https://linux-hardware.org/?probe=aa87f447d5) | May 16, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [9a08def3ae](https://linux-hardware.org/?probe=9a08def3ae) | May 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [d35caae2b6](https://linux-hardware.org/?probe=d35caae2b6) | May 15, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [829665d7bf](https://linux-hardware.org/?probe=829665d7bf) | May 15, 2023 |
| HP            | 3398                        | [7339f433ef](https://linux-hardware.org/?probe=7339f433ef) | May 15, 2023 |
| MSI           | H61M-P23                    | [e6b643867b](https://linux-hardware.org/?probe=e6b643867b) | May 15, 2023 |
| Dell          | 02GDWG A00                  | [38a459c2e0](https://linux-hardware.org/?probe=38a459c2e0) | May 14, 2023 |
| EVGA          | 151-HE-E999                 | [a431f34e2b](https://linux-hardware.org/?probe=a431f34e2b) | May 14, 2023 |
| MSI           | H110I PRO                   | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [676c25e644](https://linux-hardware.org/?probe=676c25e644) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1d4c35daa6](https://linux-hardware.org/?probe=1d4c35daa6) | May 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [415306aabf](https://linux-hardware.org/?probe=415306aabf) | May 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cf7c801d5c](https://linux-hardware.org/?probe=cf7c801d5c) | May 12, 2023 |
| Apple         | Mac-F221BEC8                | [ffffd119fb](https://linux-hardware.org/?probe=ffffd119fb) | May 12, 2023 |
| MSI           | 970A-G46                    | [6ad3215735](https://linux-hardware.org/?probe=6ad3215735) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| HP            | 158A                        | [a085c7a516](https://linux-hardware.org/?probe=a085c7a516) | May 11, 2023 |
| Dell          | 0T2HR0 A01                  | [96c6b065e8](https://linux-hardware.org/?probe=96c6b065e8) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [5d50ca41ef](https://linux-hardware.org/?probe=5d50ca41ef) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [0e8fab037b](https://linux-hardware.org/?probe=0e8fab037b) | May 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4276c0fd28](https://linux-hardware.org/?probe=4276c0fd28) | May 11, 2023 |
| Gigabyte      | H97N-WIFI                   | [ceebdc263a](https://linux-hardware.org/?probe=ceebdc263a) | May 10, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [5f3555ab64](https://linux-hardware.org/?probe=5f3555ab64) | May 10, 2023 |
| ASUSTek       | Z170-K                      | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [c40e865226](https://linux-hardware.org/?probe=c40e865226) | May 08, 2023 |
| ASUSTek       | M3N WS                      | [fb7920c5f9](https://linux-hardware.org/?probe=fb7920c5f9) | May 08, 2023 |
| ASUSTek       | P8P67-M                     | [386d7c9de4](https://linux-hardware.org/?probe=386d7c9de4) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | [1945ccd76d](https://linux-hardware.org/?probe=1945ccd76d) | May 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [894029cc14](https://linux-hardware.org/?probe=894029cc14) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | [a5c758152f](https://linux-hardware.org/?probe=a5c758152f) | May 07, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [8c5b603452](https://linux-hardware.org/?probe=8c5b603452) | May 07, 2023 |
| ASUSTek       | M4A87TD EVO                 | [ecb5894e85](https://linux-hardware.org/?probe=ecb5894e85) | May 06, 2023 |
| Gigabyte      | H310M H x.x                 | [fec056072d](https://linux-hardware.org/?probe=fec056072d) | May 05, 2023 |
| Dell          | 02GDWG A00                  | [7b9a0196b1](https://linux-hardware.org/?probe=7b9a0196b1) | May 05, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [95f75e1344](https://linux-hardware.org/?probe=95f75e1344) | May 04, 2023 |
| Gigabyte      | H410M H                     | [3e13b2bc4a](https://linux-hardware.org/?probe=3e13b2bc4a) | May 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b3ed654fde](https://linux-hardware.org/?probe=b3ed654fde) | May 04, 2023 |
| Dell          | 02GDWG A00                  | [46abb3e5c7](https://linux-hardware.org/?probe=46abb3e5c7) | May 03, 2023 |
| MSI           | B450M MORTAR                | [691239a442](https://linux-hardware.org/?probe=691239a442) | May 03, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [eae11b1ac4](https://linux-hardware.org/?probe=eae11b1ac4) | May 02, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [ee33a17baa](https://linux-hardware.org/?probe=ee33a17baa) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [d817c9a53f](https://linux-hardware.org/?probe=d817c9a53f) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [a14544f923](https://linux-hardware.org/?probe=a14544f923) | May 02, 2023 |
| EVGA          | 151-HE-E999                 | [b293ade39d](https://linux-hardware.org/?probe=b293ade39d) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [37ba71ddb4](https://linux-hardware.org/?probe=37ba71ddb4) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [b61c6e5277](https://linux-hardware.org/?probe=b61c6e5277) | May 01, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [9b6f7cea89](https://linux-hardware.org/?probe=9b6f7cea89) | May 01, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [0d5e9310d3](https://linux-hardware.org/?probe=0d5e9310d3) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4ac7cbf111](https://linux-hardware.org/?probe=4ac7cbf111) | Apr 29, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| Intel         | DB75EN AAG39650-303         | [713c422641](https://linux-hardware.org/?probe=713c422641) | Apr 29, 2023 |
| HP            | 8054                        | [81a57b4a2f](https://linux-hardware.org/?probe=81a57b4a2f) | Apr 29, 2023 |
| Gigabyte      | H410M H                     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| MSI           | PRO X670-P WIFI             | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f1679a62d0](https://linux-hardware.org/?probe=f1679a62d0) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [4363ca582a](https://linux-hardware.org/?probe=4363ca582a) | Apr 26, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [f5de49d5b3](https://linux-hardware.org/?probe=f5de49d5b3) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [83453e6960](https://linux-hardware.org/?probe=83453e6960) | Apr 26, 2023 |
| Gigabyte      | B550M DS3H                  | [208a0fc365](https://linux-hardware.org/?probe=208a0fc365) | Apr 26, 2023 |
| Intel         | B75                         | [72a3677ac2](https://linux-hardware.org/?probe=72a3677ac2) | Apr 26, 2023 |
| Foxconn       | 2ABF                        | [d040f4ff16](https://linux-hardware.org/?probe=d040f4ff16) | Apr 26, 2023 |
| Intel         | X99H                        | [d0f8c22128](https://linux-hardware.org/?probe=d0f8c22128) | Apr 26, 2023 |
| ASRock        | Z370 Extreme4               | [0e46ae0751](https://linux-hardware.org/?probe=0e46ae0751) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [517a694a82](https://linux-hardware.org/?probe=517a694a82) | Apr 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | [a06d7e1f82](https://linux-hardware.org/?probe=a06d7e1f82) | Apr 25, 2023 |
| Gigabyte      | B450M S2H                   | [db176db0db](https://linux-hardware.org/?probe=db176db0db) | Apr 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [0d6740c2a8](https://linux-hardware.org/?probe=0d6740c2a8) | Apr 24, 2023 |
| G7-2011       | X79                         | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| ASRock        | A320M Pro4                  | [bfe26862f0](https://linux-hardware.org/?probe=bfe26862f0) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [074135d4f4](https://linux-hardware.org/?probe=074135d4f4) | Apr 24, 2023 |
| Gigabyte      | B450M S2H                   | [f3c853b789](https://linux-hardware.org/?probe=f3c853b789) | Apr 23, 2023 |
| ASUSTek       | AM1M-A/BR                   | [0b29ee62f9](https://linux-hardware.org/?probe=0b29ee62f9) | Apr 23, 2023 |
| Packard Be... | IPOWER G3610                | [05de2306b0](https://linux-hardware.org/?probe=05de2306b0) | Apr 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [cd11cc0e25](https://linux-hardware.org/?probe=cd11cc0e25) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1b475eaa99](https://linux-hardware.org/?probe=1b475eaa99) | Apr 23, 2023 |
| Dell          | 0FDY5C A00                  | [c35628b7c7](https://linux-hardware.org/?probe=c35628b7c7) | Apr 22, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| MSI           | H110M PRO-D                 | [cc76c44731](https://linux-hardware.org/?probe=cc76c44731) | Apr 19, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [4abccb30eb](https://linux-hardware.org/?probe=4abccb30eb) | Apr 18, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [e84a6f3538](https://linux-hardware.org/?probe=e84a6f3538) | Apr 18, 2023 |
| Dell          | 08WKV3 A00                  | [091f305ccb](https://linux-hardware.org/?probe=091f305ccb) | Apr 18, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| ASRock        | X670E Pro RS                | [cfc2be8311](https://linux-hardware.org/?probe=cfc2be8311) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | [be0c962cda](https://linux-hardware.org/?probe=be0c962cda) | Apr 16, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [8888f53504](https://linux-hardware.org/?probe=8888f53504) | Apr 16, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [e405d73576](https://linux-hardware.org/?probe=e405d73576) | Apr 15, 2023 |
| Dell          | 0HY9JP A02                  | [25a1ee5a25](https://linux-hardware.org/?probe=25a1ee5a25) | Apr 15, 2023 |
| Biostar       | A960D+V2                    | [da262e3956](https://linux-hardware.org/?probe=da262e3956) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [87b5989939](https://linux-hardware.org/?probe=87b5989939) | Apr 13, 2023 |
| HP            | 8433 11                     | [911f2844c9](https://linux-hardware.org/?probe=911f2844c9) | Apr 13, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [df59296148](https://linux-hardware.org/?probe=df59296148) | Apr 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [df185fb277](https://linux-hardware.org/?probe=df185fb277) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | [3acd31b3be](https://linux-hardware.org/?probe=3acd31b3be) | Apr 12, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [0d8eb6aa86](https://linux-hardware.org/?probe=0d8eb6aa86) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | [7a1d69f216](https://linux-hardware.org/?probe=7a1d69f216) | Apr 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | [d3ecd3c066](https://linux-hardware.org/?probe=d3ecd3c066) | Apr 12, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | [29ed28536e](https://linux-hardware.org/?probe=29ed28536e) | Apr 12, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [4c217a8a03](https://linux-hardware.org/?probe=4c217a8a03) | Apr 11, 2023 |
| Gigabyte      | G41MT-S2                    | [73233d1c4c](https://linux-hardware.org/?probe=73233d1c4c) | Apr 11, 2023 |
| MSI           | MEG X570 UNIFY              | [02d670e0db](https://linux-hardware.org/?probe=02d670e0db) | Apr 11, 2023 |
| MSI           | B350 GAMING PLUS            | [df2f924a6e](https://linux-hardware.org/?probe=df2f924a6e) | Apr 11, 2023 |
| MSI           | H81M-P33                    | [129abe0b90](https://linux-hardware.org/?probe=129abe0b90) | Apr 10, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [8302310eaf](https://linux-hardware.org/?probe=8302310eaf) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [645fe56eb3](https://linux-hardware.org/?probe=645fe56eb3) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [c963121074](https://linux-hardware.org/?probe=c963121074) | Apr 06, 2023 |
| Dell          | 09KPNV A01                  | [06d1f0e63f](https://linux-hardware.org/?probe=06d1f0e63f) | Apr 06, 2023 |
| Apple         | Mac-F221BEC8                | [d1f4197f52](https://linux-hardware.org/?probe=d1f4197f52) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [eb35e0beff](https://linux-hardware.org/?probe=eb35e0beff) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [d89431372f](https://linux-hardware.org/?probe=d89431372f) | Apr 05, 2023 |
| MSI           | 970 GAMING                  | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| PS            | X570 Pro4                   | [f67323ef28](https://linux-hardware.org/?probe=f67323ef28) | Apr 05, 2023 |
| ASUSTek       | M4A87TD EVO                 | [6f3f9cf977](https://linux-hardware.org/?probe=6f3f9cf977) | Apr 05, 2023 |
| ASRock        | B450M Steel Legend          | [fb0dc3cc20](https://linux-hardware.org/?probe=fb0dc3cc20) | Apr 05, 2023 |
| Unknown       | X99-GT                      | [d4b6b3ebe8](https://linux-hardware.org/?probe=d4b6b3ebe8) | Apr 05, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [29dc58335f](https://linux-hardware.org/?probe=29dc58335f) | Apr 04, 2023 |
| Gigabyte      | B550M DS3H                  | [7a5ee5da76](https://linux-hardware.org/?probe=7a5ee5da76) | Apr 04, 2023 |
| Dell          | 0DF42J A00                  | [056818267b](https://linux-hardware.org/?probe=056818267b) | Apr 04, 2023 |
| MSI           | H310M PRO-VH PLUS           | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [b65273209b](https://linux-hardware.org/?probe=b65273209b) | Apr 03, 2023 |
| Dell          | 0KWVT8 A03                  | [1e66b2ab37](https://linux-hardware.org/?probe=1e66b2ab37) | Apr 03, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [daa2099403](https://linux-hardware.org/?probe=daa2099403) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | [0385e01f4d](https://linux-hardware.org/?probe=0385e01f4d) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | [20b1ee364f](https://linux-hardware.org/?probe=20b1ee364f) | Apr 02, 2023 |
| Dell          | 0KWVT8 A03                  | [a700fbd33d](https://linux-hardware.org/?probe=a700fbd33d) | Apr 02, 2023 |
| MSI           | B350 GAMING PRO CARBON      | [0ffb7303f2](https://linux-hardware.org/?probe=0ffb7303f2) | Apr 02, 2023 |
| HP            | 0AA4h                       | [9b84d8c935](https://linux-hardware.org/?probe=9b84d8c935) | Apr 02, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [cf9da855fc](https://linux-hardware.org/?probe=cf9da855fc) | Apr 02, 2023 |
| BESSTAR Te... | HM80                        | [4242425ada](https://linux-hardware.org/?probe=4242425ada) | Apr 01, 2023 |
| BESSTAR Te... | HM80                        | [702890870e](https://linux-hardware.org/?probe=702890870e) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [5dddcdcb25](https://linux-hardware.org/?probe=5dddcdcb25) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [277d3c7f43](https://linux-hardware.org/?probe=277d3c7f43) | Apr 01, 2023 |
| Lenovo        | 4030                        | [7a23fd4fb4](https://linux-hardware.org/?probe=7a23fd4fb4) | Apr 01, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [f7c90851ac](https://linux-hardware.org/?probe=f7c90851ac) | Apr 01, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | [fc44ad8c07](https://linux-hardware.org/?probe=fc44ad8c07) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [61e2653466](https://linux-hardware.org/?probe=61e2653466) | Mar 31, 2023 |
| ASUSTek       | P8H67-M LE                  | [11b3a7cdb1](https://linux-hardware.org/?probe=11b3a7cdb1) | Mar 31, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [c346cf16d3](https://linux-hardware.org/?probe=c346cf16d3) | Mar 30, 2023 |
| HP            | 0AA4h                       | [97457bb10c](https://linux-hardware.org/?probe=97457bb10c) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| Foxconn       | 2AB1 DVT                    | [a9e8e4d4b0](https://linux-hardware.org/?probe=a9e8e4d4b0) | Mar 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [81dda92e58](https://linux-hardware.org/?probe=81dda92e58) | Mar 30, 2023 |
| HP            | 8433 11                     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [78046d9b99](https://linux-hardware.org/?probe=78046d9b99) | Mar 29, 2023 |
| HP            | 0AA4h                       | [801f843749](https://linux-hardware.org/?probe=801f843749) | Mar 29, 2023 |
| Win elemen... | M600                        | [7cf2343b6f](https://linux-hardware.org/?probe=7cf2343b6f) | Mar 29, 2023 |
| ASUSTek       | H81M-A/BR                   | [c994f20b64](https://linux-hardware.org/?probe=c994f20b64) | Mar 29, 2023 |
| HP            | 09F0h                       | [540ec71101](https://linux-hardware.org/?probe=540ec71101) | Mar 28, 2023 |
| ASRock        | H510M-HVS                   | [97744fad07](https://linux-hardware.org/?probe=97744fad07) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [f17c95f91b](https://linux-hardware.org/?probe=f17c95f91b) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [1b67e2c4fd](https://linux-hardware.org/?probe=1b67e2c4fd) | Mar 28, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [cde470cb39](https://linux-hardware.org/?probe=cde470cb39) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c4bba42d7b](https://linux-hardware.org/?probe=c4bba42d7b) | Mar 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [adee3bbdde](https://linux-hardware.org/?probe=adee3bbdde) | Mar 28, 2023 |
| MSI           | B450M BAZOOKA V2            | [f6236c5962](https://linux-hardware.org/?probe=f6236c5962) | Mar 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [878fa94b87](https://linux-hardware.org/?probe=878fa94b87) | Mar 26, 2023 |
| MSI           | Z490 PLUS                   | [06032b5e04](https://linux-hardware.org/?probe=06032b5e04) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [fc01cd79a4](https://linux-hardware.org/?probe=fc01cd79a4) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c08caf1dee](https://linux-hardware.org/?probe=c08caf1dee) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [f6f4996c63](https://linux-hardware.org/?probe=f6f4996c63) | Mar 26, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [0f7d28bd43](https://linux-hardware.org/?probe=0f7d28bd43) | Mar 25, 2023 |
| ASUSTek       | SABERTOOTH X79              | [6c64b62e05](https://linux-hardware.org/?probe=6c64b62e05) | Mar 25, 2023 |
| Dell          | 0PC5F7 A01                  | [61550296b7](https://linux-hardware.org/?probe=61550296b7) | Mar 24, 2023 |
| HP            | 212B                        | [266912cedd](https://linux-hardware.org/?probe=266912cedd) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | [7a3319972e](https://linux-hardware.org/?probe=7a3319972e) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [c06eaca849](https://linux-hardware.org/?probe=c06eaca849) | Mar 23, 2023 |
| Dell          | 0RK936                      | [af3e7f60cb](https://linux-hardware.org/?probe=af3e7f60cb) | Mar 22, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| Dell          | 0RK936                      | [6c2680e4e9](https://linux-hardware.org/?probe=6c2680e4e9) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [d4e033725b](https://linux-hardware.org/?probe=d4e033725b) | Mar 21, 2023 |
| Supermicro    | X9SAE                       | [01195f072e](https://linux-hardware.org/?probe=01195f072e) | Mar 21, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [5ea7504472](https://linux-hardware.org/?probe=5ea7504472) | Mar 21, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | [3fe3c818f7](https://linux-hardware.org/?probe=3fe3c818f7) | Mar 20, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d0079fa594](https://linux-hardware.org/?probe=d0079fa594) | Mar 19, 2023 |
| Gigabyte      | X79-UD3                     | [0139691951](https://linux-hardware.org/?probe=0139691951) | Mar 19, 2023 |
| Dell          | 0WMJ54 A00                  | [bcb1a34cf2](https://linux-hardware.org/?probe=bcb1a34cf2) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c4bebd7028](https://linux-hardware.org/?probe=c4bebd7028) | Mar 17, 2023 |
| Unknown       | Unknown                     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| Intel         | X99 V1.x                    | [9b471dcdcf](https://linux-hardware.org/?probe=9b471dcdcf) | Mar 17, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [557a99333f](https://linux-hardware.org/?probe=557a99333f) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| HP            | 843F                        | [e444e0d76a](https://linux-hardware.org/?probe=e444e0d76a) | Mar 17, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [b20fcd6878](https://linux-hardware.org/?probe=b20fcd6878) | Mar 17, 2023 |
| Dell          | 02GDWG A00                  | [c81ac4434e](https://linux-hardware.org/?probe=c81ac4434e) | Mar 16, 2023 |
| ASUSTek       | Z87-K                       | [fe2d844bfb](https://linux-hardware.org/?probe=fe2d844bfb) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [88c4c221af](https://linux-hardware.org/?probe=88c4c221af) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | [e8bbe7a962](https://linux-hardware.org/?probe=e8bbe7a962) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [0c74f7b048](https://linux-hardware.org/?probe=0c74f7b048) | Mar 15, 2023 |
| ASRock        | B550 Extreme4               | [9a139b5bad](https://linux-hardware.org/?probe=9a139b5bad) | Mar 14, 2023 |
| Gigabyte      | X58A-UD7                    | [95248fc9a0](https://linux-hardware.org/?probe=95248fc9a0) | Mar 14, 2023 |
| Dell          | 0RK936                      | [59cbc1f071](https://linux-hardware.org/?probe=59cbc1f071) | Mar 14, 2023 |
| ASUSTek       | PRIME A320M-K               | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| ASUSTek       | H97-PRO                     | [b03c056ee1](https://linux-hardware.org/?probe=b03c056ee1) | Mar 13, 2023 |
| Gateway       | WG43M                       | [c1ab165971](https://linux-hardware.org/?probe=c1ab165971) | Mar 13, 2023 |
| MSI           | A68HM-E33 V2                | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| Dell          | 0DFRFW A01                  | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| Acer          | Aspire X1935                | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| Dell          | 0KC9NP A00                  | [873a2bf50c](https://linux-hardware.org/?probe=873a2bf50c) | Mar 11, 2023 |
| ASRock        | FM2A68M-HD+                 | [ccba86bda3](https://linux-hardware.org/?probe=ccba86bda3) | Mar 10, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [dbdadff4f2](https://linux-hardware.org/?probe=dbdadff4f2) | Mar 10, 2023 |
| ASRock        | B450 Steel Legend           | [e183f14e7e](https://linux-hardware.org/?probe=e183f14e7e) | Mar 10, 2023 |
| Positivo      | POS-PIQ77CL                 | [789838055a](https://linux-hardware.org/?probe=789838055a) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| MSI           | A68HM-E33 V2                | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| Gigabyte      | H110M-DS2V DDR3-CF          | [d101f34459](https://linux-hardware.org/?probe=d101f34459) | Mar 09, 2023 |
| MSI           | X58 PLATINUM SLI            | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [b99222314c](https://linux-hardware.org/?probe=b99222314c) | Mar 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4f64764c75](https://linux-hardware.org/?probe=4f64764c75) | Mar 08, 2023 |
| Dell          | 051FJ8 A02                  | [4c15877e95](https://linux-hardware.org/?probe=4c15877e95) | Mar 08, 2023 |
| Dell          | 0KWVT8 A03                  | [6ddf3ecd86](https://linux-hardware.org/?probe=6ddf3ecd86) | Mar 08, 2023 |
| ASRock        | 890GX Extreme3              | [4d59bfb158](https://linux-hardware.org/?probe=4d59bfb158) | Mar 08, 2023 |
| HP            | 83E9                        | [9a756f9158](https://linux-hardware.org/?probe=9a756f9158) | Mar 07, 2023 |
| ASRock        | G41M-GS3                    | [9e11e1f2af](https://linux-hardware.org/?probe=9e11e1f2af) | Mar 07, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [bfc1bf412e](https://linux-hardware.org/?probe=bfc1bf412e) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [da3b20e7c1](https://linux-hardware.org/?probe=da3b20e7c1) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [eb3f7a337f](https://linux-hardware.org/?probe=eb3f7a337f) | Mar 05, 2023 |
| Gigabyte      | B450M GAMING                | [b75483941a](https://linux-hardware.org/?probe=b75483941a) | Mar 05, 2023 |
| HP            | 339A                        | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [efd2d0c074](https://linux-hardware.org/?probe=efd2d0c074) | Mar 05, 2023 |
| MSI           | B350 GAMING PLUS            | [c3d6a142c0](https://linux-hardware.org/?probe=c3d6a142c0) | Mar 04, 2023 |
| ASUSTek       | PRIME Z390-A                | [87cdc5bd5a](https://linux-hardware.org/?probe=87cdc5bd5a) | Mar 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ca004eceae](https://linux-hardware.org/?probe=ca004eceae) | Mar 03, 2023 |
| Acer          | Aspire M3970                | [2708d5fa99](https://linux-hardware.org/?probe=2708d5fa99) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [141faab02f](https://linux-hardware.org/?probe=141faab02f) | Mar 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [c2d6b5218e](https://linux-hardware.org/?probe=c2d6b5218e) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [840dab3a7c](https://linux-hardware.org/?probe=840dab3a7c) | Mar 03, 2023 |
| Biostar       | H81MHV3 5.0                 | [6ea9159a52](https://linux-hardware.org/?probe=6ea9159a52) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [8ce5103cac](https://linux-hardware.org/?probe=8ce5103cac) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [62c37af17b](https://linux-hardware.org/?probe=62c37af17b) | Mar 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [f942bae731](https://linux-hardware.org/?probe=f942bae731) | Mar 02, 2023 |
| ASRockRack    | X570D4U                     | [9c4b25d5dc](https://linux-hardware.org/?probe=9c4b25d5dc) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | [4207bf1ee6](https://linux-hardware.org/?probe=4207bf1ee6) | Mar 02, 2023 |
| ASUSTek       | Crosshair IV Formula        | [ed4f0e394a](https://linux-hardware.org/?probe=ed4f0e394a) | Mar 02, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [5b94fc8fa8](https://linux-hardware.org/?probe=5b94fc8fa8) | Mar 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [85456379c1](https://linux-hardware.org/?probe=85456379c1) | Mar 02, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [6126e81a28](https://linux-hardware.org/?probe=6126e81a28) | Mar 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b6930e4615](https://linux-hardware.org/?probe=b6930e4615) | Mar 01, 2023 |
| Gigabyte      | Z77X-UP4 TH                 | [b80cb49656](https://linux-hardware.org/?probe=b80cb49656) | Mar 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [0e0b3360ba](https://linux-hardware.org/?probe=0e0b3360ba) | Feb 28, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [7f53a53eba](https://linux-hardware.org/?probe=7f53a53eba) | Feb 28, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [13edc00539](https://linux-hardware.org/?probe=13edc00539) | Feb 27, 2023 |
| Dell          | 03KWTV A02                  | [8b6eae9fd5](https://linux-hardware.org/?probe=8b6eae9fd5) | Feb 26, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [a3b8430bad](https://linux-hardware.org/?probe=a3b8430bad) | Feb 26, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [fe1c90a3aa](https://linux-hardware.org/?probe=fe1c90a3aa) | Feb 26, 2023 |
| MSI           | B450-A PRO MAX              | [f081452f55](https://linux-hardware.org/?probe=f081452f55) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| Gigabyte      | 970A-DS3P                   | [87647b8c76](https://linux-hardware.org/?probe=87647b8c76) | Feb 26, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [42fe607d11](https://linux-hardware.org/?probe=42fe607d11) | Feb 25, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [59b7e1da6d](https://linux-hardware.org/?probe=59b7e1da6d) | Feb 25, 2023 |
| ZOTAC         | MEK1                        | [a61a52d794](https://linux-hardware.org/?probe=a61a52d794) | Feb 24, 2023 |
| HP            | 8433 11                     | [881b062090](https://linux-hardware.org/?probe=881b062090) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [59d0e692ef](https://linux-hardware.org/?probe=59d0e692ef) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [27a3c3c4c1](https://linux-hardware.org/?probe=27a3c3c4c1) | Feb 24, 2023 |
| Dell          | 0M6C7G A00                  | [8d8af65e26](https://linux-hardware.org/?probe=8d8af65e26) | Feb 23, 2023 |
| Dell          | 0M6C7G A00                  | [f8f5ea8885](https://linux-hardware.org/?probe=f8f5ea8885) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [ec6ab709e5](https://linux-hardware.org/?probe=ec6ab709e5) | Feb 22, 2023 |
| Lenovo        | 102F SBB0J05441 WIN 3305... | [ea890b85f3](https://linux-hardware.org/?probe=ea890b85f3) | Feb 22, 2023 |
| Gigabyte      | H81M-HD3                    | [d19e079879](https://linux-hardware.org/?probe=d19e079879) | Feb 22, 2023 |
| ASRock        | B550 Extreme4               | [db2686086b](https://linux-hardware.org/?probe=db2686086b) | Feb 21, 2023 |
| ASUSTek       | PRIME B450M-A               | [8c97a04c10](https://linux-hardware.org/?probe=8c97a04c10) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [7dd9134373](https://linux-hardware.org/?probe=7dd9134373) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [fafea002be](https://linux-hardware.org/?probe=fafea002be) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | [c0c41ca089](https://linux-hardware.org/?probe=c0c41ca089) | Feb 21, 2023 |
| Alienware     | 0NWN7M A00                  | [eef5c2f68f](https://linux-hardware.org/?probe=eef5c2f68f) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | [2ea45a0d80](https://linux-hardware.org/?probe=2ea45a0d80) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [edbf6ce468](https://linux-hardware.org/?probe=edbf6ce468) | Feb 20, 2023 |
| ASRock        | A520M-HVS                   | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| Dell          | 09KPNV A01                  | [b335ec1cc3](https://linux-hardware.org/?probe=b335ec1cc3) | Feb 20, 2023 |
| ASRock        | H87 Performance             | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | [9805ab5764](https://linux-hardware.org/?probe=9805ab5764) | Feb 19, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [8df8fe9ae8](https://linux-hardware.org/?probe=8df8fe9ae8) | Feb 19, 2023 |
| Lenovo        | 1036 NO DPK                 | [b99541f6ad](https://linux-hardware.org/?probe=b99541f6ad) | Feb 19, 2023 |
| Dell          | 0NNNCT A01                  | [a301dac224](https://linux-hardware.org/?probe=a301dac224) | Feb 18, 2023 |
| HP            | 8437                        | [f8f0f71bf5](https://linux-hardware.org/?probe=f8f0f71bf5) | Feb 18, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4101f152f5](https://linux-hardware.org/?probe=4101f152f5) | Feb 17, 2023 |
| ASRock        | B550M-HDV                   | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| MSI           | G41M-P33 Combo              | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c82882e708](https://linux-hardware.org/?probe=c82882e708) | Feb 15, 2023 |
| Intel         | X99 V1.x                    | [31da77bea8](https://linux-hardware.org/?probe=31da77bea8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Gigabyte      | G41MT-S2                    | [9dfc369401](https://linux-hardware.org/?probe=9dfc369401) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [2ca590a85e](https://linux-hardware.org/?probe=2ca590a85e) | Feb 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [27c2ee6ee0](https://linux-hardware.org/?probe=27c2ee6ee0) | Feb 14, 2023 |
| Dell          | 0Y7WYT A00                  | [d94084bbee](https://linux-hardware.org/?probe=d94084bbee) | Feb 12, 2023 |
| ASRock        | B550M Steel Legend          | [2a6f501cb1](https://linux-hardware.org/?probe=2a6f501cb1) | Feb 12, 2023 |
| Dell          | 08WKV3 A00                  | [89ba42b53e](https://linux-hardware.org/?probe=89ba42b53e) | Feb 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [687ecdce15](https://linux-hardware.org/?probe=687ecdce15) | Feb 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [2c1562b21f](https://linux-hardware.org/?probe=2c1562b21f) | Feb 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [2d776f8810](https://linux-hardware.org/?probe=2d776f8810) | Feb 11, 2023 |
| Gigabyte      | X399 AORUS Gaming 7         | [b82ab8816d](https://linux-hardware.org/?probe=b82ab8816d) | Feb 11, 2023 |
| HP            | 18E4                        | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [0b14ee6551](https://linux-hardware.org/?probe=0b14ee6551) | Feb 11, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [181c0e03e2](https://linux-hardware.org/?probe=181c0e03e2) | Feb 10, 2023 |
| Dell          | 0Y7WYT A00                  | [e4369afe1e](https://linux-hardware.org/?probe=e4369afe1e) | Feb 10, 2023 |
| ASUSTek       | A55BM-PLUS                  | [7c9763c23f](https://linux-hardware.org/?probe=7c9763c23f) | Feb 10, 2023 |
| Samsung       | DeskTop System              | [2437c4afda](https://linux-hardware.org/?probe=2437c4afda) | Feb 10, 2023 |
| Biostar       | H81MHV3 5.0                 | [390c8dd03a](https://linux-hardware.org/?probe=390c8dd03a) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [17bf959fd0](https://linux-hardware.org/?probe=17bf959fd0) | Feb 09, 2023 |
| Acer          | Aspire M3970                | [718cc13462](https://linux-hardware.org/?probe=718cc13462) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [16af8175a4](https://linux-hardware.org/?probe=16af8175a4) | Feb 08, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [1c07b901bb](https://linux-hardware.org/?probe=1c07b901bb) | Feb 08, 2023 |
| HP            | 2129                        | [80920d0d75](https://linux-hardware.org/?probe=80920d0d75) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d8dcaddb54](https://linux-hardware.org/?probe=d8dcaddb54) | Feb 08, 2023 |
| ASRock        | B660 Pro-C/ax               | [31e10f0e68](https://linux-hardware.org/?probe=31e10f0e68) | Feb 07, 2023 |
| ASRock        | FM2A68M-HD+                 | [8588a36683](https://linux-hardware.org/?probe=8588a36683) | Feb 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | [81ece9483e](https://linux-hardware.org/?probe=81ece9483e) | Feb 07, 2023 |
| Gigabyte      | F2A55M-HD2                  | [fe95bfe3d3](https://linux-hardware.org/?probe=fe95bfe3d3) | Feb 07, 2023 |
| Dell          | 0HHV7N A00                  | [e67a1c86b7](https://linux-hardware.org/?probe=e67a1c86b7) | Feb 07, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [03a392d41f](https://linux-hardware.org/?probe=03a392d41f) | Feb 07, 2023 |
| Dell          | 02GDWG A00                  | [c0660c15fb](https://linux-hardware.org/?probe=c0660c15fb) | Feb 07, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [25fbfe1d66](https://linux-hardware.org/?probe=25fbfe1d66) | Feb 07, 2023 |
| System76      | Thelio thelio-r2            | [4cdf7d2895](https://linux-hardware.org/?probe=4cdf7d2895) | Feb 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [42dba6bdb3](https://linux-hardware.org/?probe=42dba6bdb3) | Feb 06, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [a9bfc9669d](https://linux-hardware.org/?probe=a9bfc9669d) | Feb 06, 2023 |
| ASUSTek       | H81M-K                      | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| HP            | 8054                        | [c709653825](https://linux-hardware.org/?probe=c709653825) | Feb 05, 2023 |
| MSI           | PRO Z690-A DDR4             | [403785d1ec](https://linux-hardware.org/?probe=403785d1ec) | Feb 05, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [c66fb39891](https://linux-hardware.org/?probe=c66fb39891) | Feb 04, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [cd9d867630](https://linux-hardware.org/?probe=cd9d867630) | Feb 04, 2023 |
| Biostar       | H81MHV3 5.0                 | [084eee2317](https://linux-hardware.org/?probe=084eee2317) | Feb 03, 2023 |
| HP            | 834F                        | [9a4a1839d3](https://linux-hardware.org/?probe=9a4a1839d3) | Feb 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [6d4ee8a3c6](https://linux-hardware.org/?probe=6d4ee8a3c6) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ffabf45521](https://linux-hardware.org/?probe=ffabf45521) | Feb 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [33ae030343](https://linux-hardware.org/?probe=33ae030343) | Jan 31, 2023 |
| MSI           | PRO Z690-P DDR4             | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [a96d93846a](https://linux-hardware.org/?probe=a96d93846a) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3d555e69f7](https://linux-hardware.org/?probe=3d555e69f7) | Jan 30, 2023 |
| Intel         | H61                         | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [b07e189d3c](https://linux-hardware.org/?probe=b07e189d3c) | Jan 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [6b71ec1a01](https://linux-hardware.org/?probe=6b71ec1a01) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASUSTek       | GA35DX                      | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| ASUSTek       | PRIME B560M-K               | [c74b6b90f0](https://linux-hardware.org/?probe=c74b6b90f0) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [55d50f6d18](https://linux-hardware.org/?probe=55d50f6d18) | Jan 27, 2023 |
| HP            | 1495                        | [8c1f7b5fbd](https://linux-hardware.org/?probe=8c1f7b5fbd) | Jan 27, 2023 |
| ASRock        | B450 Steel Legend           | [c2a36422b4](https://linux-hardware.org/?probe=c2a36422b4) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [df315d8050](https://linux-hardware.org/?probe=df315d8050) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [14a0252d88](https://linux-hardware.org/?probe=14a0252d88) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | [0b70a364b7](https://linux-hardware.org/?probe=0b70a364b7) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | [a42ba7ef9e](https://linux-hardware.org/?probe=a42ba7ef9e) | Jan 26, 2023 |
| ASUSTek       | P8B75-V                     | [1f8bd6b38e](https://linux-hardware.org/?probe=1f8bd6b38e) | Jan 26, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [e32b0f2c79](https://linux-hardware.org/?probe=e32b0f2c79) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| Acer          | Aspire M3970                | [c822a510e5](https://linux-hardware.org/?probe=c822a510e5) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3221475cc8](https://linux-hardware.org/?probe=3221475cc8) | Jan 24, 2023 |
| MSI           | B450M MORTAR MAX            | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| ASUSTek       | Rampage II GENE             | [112b5304d9](https://linux-hardware.org/?probe=112b5304d9) | Jan 23, 2023 |
| MACHINIST     | X79 Z9-D7 V2.0              | [9d5d06d342](https://linux-hardware.org/?probe=9d5d06d342) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [75acbba6b1](https://linux-hardware.org/?probe=75acbba6b1) | Jan 23, 2023 |
| ASRock        | AM1H-ITX                    | [82b094a66b](https://linux-hardware.org/?probe=82b094a66b) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [bfb889f5d5](https://linux-hardware.org/?probe=bfb889f5d5) | Jan 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [6597dd71bc](https://linux-hardware.org/?probe=6597dd71bc) | Jan 23, 2023 |
| Gigabyte      | G41MT-S2                    | [8f19cbfb31](https://linux-hardware.org/?probe=8f19cbfb31) | Jan 22, 2023 |
| MSI           | H81M-E34                    | [c11041ba13](https://linux-hardware.org/?probe=c11041ba13) | Jan 22, 2023 |
| ASUSTek       | H61M-E                      | [eec3fddef5](https://linux-hardware.org/?probe=eec3fddef5) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | [758ea69493](https://linux-hardware.org/?probe=758ea69493) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [d1b63bbd2d](https://linux-hardware.org/?probe=d1b63bbd2d) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [ebab459512](https://linux-hardware.org/?probe=ebab459512) | Jan 22, 2023 |
| ASUSTek       | G10DK                       | [1a27b660c2](https://linux-hardware.org/?probe=1a27b660c2) | Jan 21, 2023 |
| ASUSTek       | P8H77-V LE                  | [6dd531590e](https://linux-hardware.org/?probe=6dd531590e) | Jan 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [bd601f83d3](https://linux-hardware.org/?probe=bd601f83d3) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [d203633f83](https://linux-hardware.org/?probe=d203633f83) | Jan 21, 2023 |
| Dell          | 0KC9NP A01                  | [ce0ba337df](https://linux-hardware.org/?probe=ce0ba337df) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [e47d5b2419](https://linux-hardware.org/?probe=e47d5b2419) | Jan 21, 2023 |
| ASUSTek       | P6T SE                      | [011553878f](https://linux-hardware.org/?probe=011553878f) | Jan 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | [b7b8f92df1](https://linux-hardware.org/?probe=b7b8f92df1) | Jan 21, 2023 |
| ASUSTek       | P8Z77-V LK                  | [a10fc5f5a9](https://linux-hardware.org/?probe=a10fc5f5a9) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | [266b8bc492](https://linux-hardware.org/?probe=266b8bc492) | Jan 20, 2023 |
| Alienware     | 0N43JM A00                  | [06a6ec74c0](https://linux-hardware.org/?probe=06a6ec74c0) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | [0fbcb3df67](https://linux-hardware.org/?probe=0fbcb3df67) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [cbad1c4df4](https://linux-hardware.org/?probe=cbad1c4df4) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [3ff2eaf5ed](https://linux-hardware.org/?probe=3ff2eaf5ed) | Jan 19, 2023 |
| ASUSTek       | P6T SE                      | [d13ca33fcf](https://linux-hardware.org/?probe=d13ca33fcf) | Jan 18, 2023 |
| ASRock        | H510M-HVS R2.0              | [3ee772766c](https://linux-hardware.org/?probe=3ee772766c) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | [ebc45fdfd5](https://linux-hardware.org/?probe=ebc45fdfd5) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | [0eae2f92fa](https://linux-hardware.org/?probe=0eae2f92fa) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | [f908807ed9](https://linux-hardware.org/?probe=f908807ed9) | Jan 17, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [564482477e](https://linux-hardware.org/?probe=564482477e) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6e8f360d6e](https://linux-hardware.org/?probe=6e8f360d6e) | Jan 17, 2023 |
| ASRock        | H87 Performance             | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| Gigabyte      | B550M DS3H AC               | [22fca13d2b](https://linux-hardware.org/?probe=22fca13d2b) | Jan 17, 2023 |
| Gigabyte      | B450M S2H                   | [2ba8d32a71](https://linux-hardware.org/?probe=2ba8d32a71) | Jan 17, 2023 |
| Gateway       | WG43M                       | [af3a009366](https://linux-hardware.org/?probe=af3a009366) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | [48cc2e0e69](https://linux-hardware.org/?probe=48cc2e0e69) | Jan 17, 2023 |
| Gateway       | WG43M                       | [b0aa3af22f](https://linux-hardware.org/?probe=b0aa3af22f) | Jan 17, 2023 |
| ASRock        | H87 Performance             | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| ASRock        | B450 Pro4                   | [2e65fc8357](https://linux-hardware.org/?probe=2e65fc8357) | Jan 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [ba736834cd](https://linux-hardware.org/?probe=ba736834cd) | Jan 16, 2023 |
| HC            | HCAR357-MI V1.0             | [ef934af180](https://linux-hardware.org/?probe=ef934af180) | Jan 16, 2023 |
| ASRock        | B550 Extreme4               | [01f850d2fb](https://linux-hardware.org/?probe=01f850d2fb) | Jan 15, 2023 |
| Dell          | 0PXWHK A00                  | [82f04ecd77](https://linux-hardware.org/?probe=82f04ecd77) | Jan 15, 2023 |
| Dell          | 0PXWHK A00                  | [25db796fd6](https://linux-hardware.org/?probe=25db796fd6) | Jan 14, 2023 |
| MAXSUN        | MS-TZZ B460M                | [14758fc3e7](https://linux-hardware.org/?probe=14758fc3e7) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [d3896698c8](https://linux-hardware.org/?probe=d3896698c8) | Jan 14, 2023 |
| ASUSTek       | G10DK                       | [a92296f2e7](https://linux-hardware.org/?probe=a92296f2e7) | Jan 14, 2023 |
| Acer          | Aspire XC-603G              | [21e24944ad](https://linux-hardware.org/?probe=21e24944ad) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| ASUSTek       | P9X79-E WS                  | [e868d6909e](https://linux-hardware.org/?probe=e868d6909e) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [c01da2fcf9](https://linux-hardware.org/?probe=c01da2fcf9) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [d4a8ff871f](https://linux-hardware.org/?probe=d4a8ff871f) | Jan 14, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [1921b19009](https://linux-hardware.org/?probe=1921b19009) | Jan 13, 2023 |
| HP            | 8299                        | [e4e0920f71](https://linux-hardware.org/?probe=e4e0920f71) | Jan 12, 2023 |
| ASUSTek       | H61M-E                      | [38691cf2cc](https://linux-hardware.org/?probe=38691cf2cc) | Jan 11, 2023 |
| Lenovo        | ThinkCentre M71e 3157W8B    | [70078ceabd](https://linux-hardware.org/?probe=70078ceabd) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [ae12526ceb](https://linux-hardware.org/?probe=ae12526ceb) | Jan 11, 2023 |
| ASUSTek       | P9X79-E WS                  | [f3b4e5135f](https://linux-hardware.org/?probe=f3b4e5135f) | Jan 10, 2023 |
| HP            | 8433 11                     | [5e26cba33b](https://linux-hardware.org/?probe=5e26cba33b) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [b39213e4d0](https://linux-hardware.org/?probe=b39213e4d0) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [3982bc570e](https://linux-hardware.org/?probe=3982bc570e) | Jan 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | [e64cca399f](https://linux-hardware.org/?probe=e64cca399f) | Jan 09, 2023 |
| MSI           | B350M BAZOOKA               | [e7d2bcfcfb](https://linux-hardware.org/?probe=e7d2bcfcfb) | Jan 09, 2023 |
| ASRock        | X370 Gaming K4              | [0ed2f96ba8](https://linux-hardware.org/?probe=0ed2f96ba8) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [36ed66f057](https://linux-hardware.org/?probe=36ed66f057) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [1b055dc79d](https://linux-hardware.org/?probe=1b055dc79d) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [0b85968e35](https://linux-hardware.org/?probe=0b85968e35) | Jan 08, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [15f31fc9a5](https://linux-hardware.org/?probe=15f31fc9a5) | Jan 07, 2023 |
| HP            | 2B4B                        | [57273c7b72](https://linux-hardware.org/?probe=57273c7b72) | Jan 07, 2023 |
| Dell          | 04GJJT A00                  | [85142569a6](https://linux-hardware.org/?probe=85142569a6) | Jan 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f2024a8808](https://linux-hardware.org/?probe=f2024a8808) | Jan 06, 2023 |
| Acer          | Aspire M3970                | [2ef35b6d4b](https://linux-hardware.org/?probe=2ef35b6d4b) | Jan 05, 2023 |
| MSI           | B250M PRO-VD                | [0abf746107](https://linux-hardware.org/?probe=0abf746107) | Jan 05, 2023 |
| Intel         | HM570                       | [8728d2372a](https://linux-hardware.org/?probe=8728d2372a) | Jan 05, 2023 |
| AZW           | GTR V02                     | [2cf7a814cb](https://linux-hardware.org/?probe=2cf7a814cb) | Jan 05, 2023 |
| Gigabyte      | X570S AERO G                | [04ca884448](https://linux-hardware.org/?probe=04ca884448) | Jan 05, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [98fafd877d](https://linux-hardware.org/?probe=98fafd877d) | Jan 04, 2023 |
| HP            | 3047h                       | [2c75b0b4ee](https://linux-hardware.org/?probe=2c75b0b4ee) | Jan 04, 2023 |
| ASRock        | 760GM-HDV                   | [f994e91031](https://linux-hardware.org/?probe=f994e91031) | Jan 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6da268e22f](https://linux-hardware.org/?probe=6da268e22f) | Jan 03, 2023 |
| System76      | Thelio Mira thelio-mira-... | [78367dd37f](https://linux-hardware.org/?probe=78367dd37f) | Jan 03, 2023 |
| ASRock        | FM2A55M-VG3+                | [741f0d79a1](https://linux-hardware.org/?probe=741f0d79a1) | Jan 03, 2023 |
| ASRock        | B550M Steel Legend          | [e8ad216a59](https://linux-hardware.org/?probe=e8ad216a59) | Jan 02, 2023 |
| ASUSTek       | P6T                         | [e648b2523e](https://linux-hardware.org/?probe=e648b2523e) | Jan 02, 2023 |
| Acer          | Aspire XC-603G              | [b2e25a20de](https://linux-hardware.org/?probe=b2e25a20de) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0e4b6aa6c2](https://linux-hardware.org/?probe=0e4b6aa6c2) | Jan 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e26cc7285f](https://linux-hardware.org/?probe=e26cc7285f) | Jan 02, 2023 |
| Win elemen... | M600                        | [5d4320db68](https://linux-hardware.org/?probe=5d4320db68) | Jan 02, 2023 |
| MSI           | PRO B550-VC                 | [f5574e6e00](https://linux-hardware.org/?probe=f5574e6e00) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [28f9b91b32](https://linux-hardware.org/?probe=28f9b91b32) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6b98637c82](https://linux-hardware.org/?probe=6b98637c82) | Jan 01, 2023 |
| Acer          | Aspire XC-603G              | [660548d31c](https://linux-hardware.org/?probe=660548d31c) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| Acer          | Predator PO3-600 V:1.1      | [e5f5073bcd](https://linux-hardware.org/?probe=e5f5073bcd) | Dec 31, 2022 |
| MSI           | B250M BAZOOKA               | [5b204eade4](https://linux-hardware.org/?probe=5b204eade4) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | [ad32666c8c](https://linux-hardware.org/?probe=ad32666c8c) | Dec 31, 2022 |
| ASUSTek       | Z97-A                       | [6f61aac097](https://linux-hardware.org/?probe=6f61aac097) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | [17fc3a4abc](https://linux-hardware.org/?probe=17fc3a4abc) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| ASUSTek       | Z87-PLUS                    | [85bfa942e6](https://linux-hardware.org/?probe=85bfa942e6) | Dec 30, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | [4b3cfd1d9c](https://linux-hardware.org/?probe=4b3cfd1d9c) | Dec 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [17f72460f6](https://linux-hardware.org/?probe=17f72460f6) | Dec 29, 2022 |
| Intel         | DP55WB AAE64798-206         | [2373b5141b](https://linux-hardware.org/?probe=2373b5141b) | Dec 29, 2022 |
| Acer          | Aspire XC-603G              | [08dc8ac6b7](https://linux-hardware.org/?probe=08dc8ac6b7) | Dec 29, 2022 |
| ASRock        | Z790 PG Riptide             | [19c8814aba](https://linux-hardware.org/?probe=19c8814aba) | Dec 29, 2022 |
| Dell          | 0NNGP2 A00                  | [12638171d9](https://linux-hardware.org/?probe=12638171d9) | Dec 28, 2022 |
| Lenovo        | No DPK                      | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASRock        | Z790M-ITX WiFi              | [c1c0ab5824](https://linux-hardware.org/?probe=c1c0ab5824) | Dec 28, 2022 |
| Dell          | 00CV7F A00                  | [49a36278c4](https://linux-hardware.org/?probe=49a36278c4) | Dec 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [2522f716da](https://linux-hardware.org/?probe=2522f716da) | Dec 28, 2022 |
| HP            | 2B4B                        | [b07e2ecc23](https://linux-hardware.org/?probe=b07e2ecc23) | Dec 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1522e4a536](https://linux-hardware.org/?probe=1522e4a536) | Dec 28, 2022 |
| Acer          | Aspire XC-603G              | [e8adbb63a4](https://linux-hardware.org/?probe=e8adbb63a4) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [20ca7dd779](https://linux-hardware.org/?probe=20ca7dd779) | Dec 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [dab993d989](https://linux-hardware.org/?probe=dab993d989) | Dec 27, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ee1658b320](https://linux-hardware.org/?probe=ee1658b320) | Dec 27, 2022 |
| HP            | 876C SMVB                   | [7926807626](https://linux-hardware.org/?probe=7926807626) | Dec 27, 2022 |
| ASUSTek       | Z87-K                       | [9c65749eb1](https://linux-hardware.org/?probe=9c65749eb1) | Dec 27, 2022 |
| MSI           | B450M PRO-M2                | [89d9265559](https://linux-hardware.org/?probe=89d9265559) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Gigabyte      | H61M-S2PV                   | [4403153e04](https://linux-hardware.org/?probe=4403153e04) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [c49123106a](https://linux-hardware.org/?probe=c49123106a) | Dec 24, 2022 |
| Gigabyte      | MJPLNBB-00                  | [17c300ac96](https://linux-hardware.org/?probe=17c300ac96) | Dec 22, 2022 |
| ASUSTek       | P7P55D PRO                  | [7402ac8671](https://linux-hardware.org/?probe=7402ac8671) | Dec 22, 2022 |
| MSI           | B85M-E45                    | [b60edb092f](https://linux-hardware.org/?probe=b60edb092f) | Dec 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [07dc9b96c1](https://linux-hardware.org/?probe=07dc9b96c1) | Dec 21, 2022 |
| Dell          | 02GDWG A00                  | [d20f5b0751](https://linux-hardware.org/?probe=d20f5b0751) | Dec 21, 2022 |
| Intel         | X99 V1.x                    | [5e961d12dc](https://linux-hardware.org/?probe=5e961d12dc) | Dec 21, 2022 |
| Supermicro    | X9DR3-F                     | [0a1557ab4a](https://linux-hardware.org/?probe=0a1557ab4a) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [33fce09f33](https://linux-hardware.org/?probe=33fce09f33) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [858931394a](https://linux-hardware.org/?probe=858931394a) | Dec 20, 2022 |
| HP            | 18E7                        | [c3b91e80df](https://linux-hardware.org/?probe=c3b91e80df) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [03dfcb8079](https://linux-hardware.org/?probe=03dfcb8079) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1f6885ef2f](https://linux-hardware.org/?probe=1f6885ef2f) | Dec 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c7b01f9875](https://linux-hardware.org/?probe=c7b01f9875) | Dec 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pop!_OS 22.04 | 1233     | 31.36%  |
| Pop!_OS 20.04 | 861      | 21.9%   |
| Pop!_OS 21.04 | 719      | 18.29%  |
| Pop!_OS 20.10 | 672      | 17.09%  |
| Pop!_OS 21.10 | 421      | 10.71%  |
| Pop!_OS 19.10 | 15       | 0.38%   |
| Pop!_OS 19.04 | 6        | 0.15%   |
| Pop!_OS 18.04 | 4        | 0.1%    |
| Pop!_OS 18.10 | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Pop!_OS | 3710     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.11.0-7620-generic      | 340      | 7.94%   |
| 5.8.0-7630-generic       | 315      | 7.36%   |
| 6.2.6-76060206-generic   | 301      | 7.03%   |
| 5.4.0-7634-generic       | 281      | 6.56%   |
| 5.8.0-7642-generic       | 203      | 4.74%   |
| 5.13.0-7614-generic      | 203      | 4.74%   |
| 5.4.0-7642-generic       | 187      | 4.37%   |
| 5.11.0-7614-generic      | 181      | 4.23%   |
| 5.17.5-76051705-generic  | 179      | 4.18%   |
| 6.0.12-76060006-generic  | 175      | 4.09%   |
| 5.13.0-7620-generic      | 171      | 3.99%   |
| 5.19.0-76051900-generic  | 144      | 3.36%   |
| 5.16.11-76051611-generic | 112      | 2.62%   |
| 5.15.15-76051515-generic | 109      | 2.55%   |
| 6.0.6-76060006-generic   | 102      | 2.38%   |
| 5.15.5-76051505-generic  | 92       | 2.15%   |
| 6.4.6-76060406-generic   | 88       | 2.06%   |
| 5.11.0-7612-generic      | 87       | 2.03%   |
| 5.8.0-7625-generic       | 78       | 1.82%   |
| 5.18.10-76051810-generic | 75       | 1.75%   |
| 5.11.0-7633-generic      | 71       | 1.66%   |
| 5.17.15-76051715-generic | 69       | 1.61%   |
| 5.16.19-76051619-generic | 65       | 1.52%   |
| 5.15.8-76051508-generic  | 63       | 1.47%   |
| 5.16.15-76051615-generic | 56       | 1.31%   |
| 5.15.11-76051511-generic | 47       | 1.1%    |
| 6.5.4-76060504-generic   | 45       | 1.05%   |
| 5.4.0-7626-generic       | 43       | 1%      |
| 6.2.0-76060200-generic   | 37       | 0.86%   |
| 6.5.6-76060506-generic   | 35       | 0.82%   |
| 5.15.23-76051523-generic | 29       | 0.68%   |
| 6.1.11-76060111-generic  | 28       | 0.65%   |
| 6.0.2-76060002-generic   | 28       | 0.65%   |
| 5.4.0-7625-generic       | 24       | 0.56%   |
| 5.4.0-7629-generic       | 21       | 0.49%   |
| 5.19.16-76051916-generic | 18       | 0.42%   |
| 6.0.3-76060003-generic   | 14       | 0.33%   |
| 5.3.0-7629-generic       | 5        | 0.12%   |
| 5.3.0-7625-generic       | 5        | 0.12%   |
| 5.8.5-xanmod1            | 4        | 0.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 651      | 15.53%  |
| 5.8.0   | 568      | 13.55%  |
| 5.4.0   | 537      | 12.81%  |
| 5.13.0  | 371      | 8.85%   |
| 6.2.6   | 301      | 7.18%   |
| 5.17.5  | 179      | 4.27%   |
| 6.0.12  | 178      | 4.25%   |
| 5.19.0  | 144      | 3.44%   |
| 5.16.11 | 112      | 2.67%   |
| 5.15.15 | 110      | 2.62%   |
| 6.0.6   | 103      | 2.46%   |
| 5.15.5  | 92       | 2.2%    |
| 6.4.6   | 88       | 2.1%    |
| 5.18.10 | 75       | 1.79%   |
| 5.17.15 | 69       | 1.65%   |
| 5.16.19 | 65       | 1.55%   |
| 5.15.8  | 63       | 1.5%    |
| 5.16.15 | 56       | 1.34%   |
| 5.15.11 | 47       | 1.12%   |
| 6.5.4   | 45       | 1.07%   |
| 6.2.0   | 37       | 0.88%   |
| 6.5.6   | 35       | 0.84%   |
| 6.0.2   | 29       | 0.69%   |
| 5.15.23 | 29       | 0.69%   |
| 6.1.11  | 28       | 0.67%   |
| 5.19.16 | 18       | 0.43%   |
| 5.3.0   | 17       | 0.41%   |
| 6.0.3   | 14       | 0.33%   |
| 5.8.5   | 8        | 0.19%   |
| 5.0.0   | 6        | 0.14%   |
| 5.8.12  | 5        | 0.12%   |
| 6.3.7   | 3        | 0.07%   |
| 6.1.0   | 3        | 0.07%   |
| 5.7.8   | 3        | 0.07%   |
| 5.7.0   | 3        | 0.07%   |
| 5.6.16  | 3        | 0.07%   |
| 5.15.0  | 3        | 0.07%   |
| 6.3.4   | 2        | 0.05%   |
| 5.9.1   | 2        | 0.05%   |
| 5.8.6   | 2        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 653      | 15.76%  |
| 5.8     | 590      | 14.24%  |
| 5.4     | 539      | 13.01%  |
| 5.13    | 376      | 9.07%   |
| 5.15    | 343      | 8.28%   |
| 6.2     | 335      | 8.08%   |
| 6.0     | 319      | 7.7%    |
| 5.17    | 246      | 5.94%   |
| 5.16    | 224      | 5.41%   |
| 5.19    | 162      | 3.91%   |
| 6.4     | 89       | 2.15%   |
| 6.5     | 82       | 1.98%   |
| 5.18    | 77       | 1.86%   |
| 6.1     | 34       | 0.82%   |
| 5.3     | 17       | 0.41%   |
| 5.7     | 14       | 0.34%   |
| 5.6     | 8        | 0.19%   |
| 5.10    | 8        | 0.19%   |
| 6.3     | 6        | 0.14%   |
| 5.0     | 6        | 0.14%   |
| 5.9     | 5        | 0.12%   |
| 5.14    | 5        | 0.12%   |
| 5.12    | 4        | 0.1%    |
| 4.18    | 1        | 0.02%   |
| 4.15    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3710     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 3583     | 95.98%  |
| KDE5            | 41       | 1.1%    |
| KDE             | 33       | 0.88%   |
| X-Cinnamon      | 19       | 0.51%   |
| Unknown         | 17       | 0.46%   |
| MATE            | 9        | 0.24%   |
| XFCE            | 8        | 0.21%   |
| GNOME Flashback | 6        | 0.16%   |
| Cinnamon        | 5        | 0.13%   |
| i3              | 4        | 0.11%   |
| LXQt            | 3        | 0.08%   |
| Budgie          | 2        | 0.05%   |
| Unity           | 1        | 0.03%   |
| UKUI            | 1        | 0.03%   |
| Pantheon        | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3643     | 97.82%  |
| Wayland | 68       | 1.83%   |
| Unknown | 7        | 0.19%   |
| Tty     | 6        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3158     | 84.55%  |
| GDM     | 345      | 9.24%   |
| GDM3    | 217      | 5.81%   |
| SDDM    | 10       | 0.27%   |
| TDM     | 3        | 0.08%   |
| LightDM | 2        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2111     | 56.37%  |
| en_GB   | 283      | 7.56%   |
| pt_BR   | 265      | 7.08%   |
| de_DE   | 206      | 5.5%    |
| C       | 132      | 3.52%   |
| en_AU   | 115      | 3.07%   |
| en_CA   | 106      | 2.83%   |
| fr_FR   | 75       | 2%      |
| it_IT   | 47       | 1.26%   |
| ru_RU   | 45       | 1.2%    |
| es_ES   | 42       | 1.12%   |
| pl_PL   | 34       | 0.91%   |
| nl_NL   | 28       | 0.75%   |
| sv_SE   | 24       | 0.64%   |
| Unknown | 20       | 0.53%   |
| fi_FI   | 15       | 0.4%    |
| pt_PT   | 14       | 0.37%   |
| es_AR   | 11       | 0.29%   |
| da_DK   | 11       | 0.29%   |
| fr_CA   | 10       | 0.27%   |
| es_CL   | 10       | 0.27%   |
| en_DK   | 9        | 0.24%   |
| zh_TW   | 8        | 0.21%   |
| ja_JP   | 8        | 0.21%   |
| nl_BE   | 7        | 0.19%   |
| en_ZA   | 7        | 0.19%   |
| en_IN   | 7        | 0.19%   |
| sk_SK   | 6        | 0.16%   |
| nb_NO   | 6        | 0.16%   |
| en_NZ   | 6        | 0.16%   |
| es_MX   | 5        | 0.13%   |
| de_AT   | 5        | 0.13%   |
| cs_CZ   | 5        | 0.13%   |
| tr_TR   | 4        | 0.11%   |
| hu_HU   | 4        | 0.11%   |
| hr_HR   | 4        | 0.11%   |
| fr_CH   | 4        | 0.11%   |
| zh_CN   | 3        | 0.08%   |
| uk_UA   | 3        | 0.08%   |
| ro_RO   | 3        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3030     | 80.82%  |
| EFI  | 719      | 19.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3570     | 95.81%  |
| Overlay | 71       | 1.91%   |
| Btrfs   | 64       | 1.72%   |
| Xfs     | 8        | 0.21%   |
| Zfs     | 6        | 0.16%   |
| Unknown | 6        | 0.16%   |
| Tmpfs   | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3149     | 84.38%  |
| GPT     | 505      | 13.53%  |
| MBR     | 78       | 2.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3597     | 96.49%  |
| Yes       | 131      | 3.51%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3386     | 90.78%  |
| Yes       | 344      | 9.22%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1055     | 28.44%  |
| Gigabyte Technology                  | 717      | 19.33%  |
| MSI                                  | 555      | 14.96%  |
| ASRock                               | 364      | 9.81%   |
| Dell                                 | 282      | 7.6%    |
| Hewlett-Packard                      | 191      | 5.15%   |
| Lenovo                               | 92       | 2.48%   |
| Intel                                | 70       | 1.89%   |
| System76                             | 36       | 0.97%   |
| Acer                                 | 30       | 0.81%   |
| Pegatron                             | 25       | 0.67%   |
| Unknown                              | 25       | 0.67%   |
| Biostar                              | 21       | 0.57%   |
| Alienware                            | 20       | 0.54%   |
| Fujitsu                              | 18       | 0.49%   |
| Foxconn                              | 18       | 0.49%   |
| ECS                                  | 15       | 0.4%    |
| Apple                                | 15       | 0.4%    |
| Huanan                               | 13       | 0.35%   |
| Positivo                             | 12       | 0.32%   |
| Supermicro                           | 10       | 0.27%   |
| Medion                               | 10       | 0.27%   |
| BESSTAR Tech                         | 9        | 0.24%   |
| PCWare                               | 8        | 0.22%   |
| Gateway                              | 7        | 0.19%   |
| MACHINIST                            | 6        | 0.16%   |
| EVGA                                 | 6        | 0.16%   |
| Minix                                | 5        | 0.13%   |
| AZW                                  | 5        | 0.13%   |
| NZXT                                 | 4        | 0.11%   |
| Samsung Electronics                  | 3        | 0.08%   |
| OEM                                  | 3        | 0.08%   |
| MAXSUN                               | 3        | 0.08%   |
| eMachines                            | 3        | 0.08%   |
| TYAN Computer                        | 2        | 0.05%   |
| T-bao                                | 2        | 0.05%   |
| Shuttle                              | 2        | 0.05%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.05%   |
| Packard Bell                         | 2        | 0.05%   |
| Megaware                             | 2        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 91       | 2.45%   |
| ASUS TUF Gaming X570-PLUS      | 42       | 1.13%   |
| Gigabyte B450M DS3H            | 34       | 0.92%   |
| MSI MS-7C02                    | 31       | 0.84%   |
| ASUS ROG STRIX B550-F GAMING   | 31       | 0.84%   |
| MSI MS-7C37                    | 30       | 0.81%   |
| ASUS ROG STRIX B450-F GAMING   | 30       | 0.81%   |
| MSI MS-7B86                    | 28       | 0.75%   |
| Unknown                        | 26       | 0.7%    |
| Dell OptiPlex 9020             | 25       | 0.67%   |
| ASUS PRIME B450M-A             | 24       | 0.65%   |
| System76 Thelio                | 21       | 0.57%   |
| Gigabyte X570 AORUS ELITE      | 21       | 0.57%   |
| Dell OptiPlex 7010             | 18       | 0.49%   |
| MSI MS-7C91                    | 17       | 0.46%   |
| Gigabyte A320M-S2H             | 17       | 0.46%   |
| ASRock B450M Steel Legend      | 16       | 0.43%   |
| ASRock B450M Pro4              | 16       | 0.43%   |
| Gigabyte B450 AORUS PRO WIFI   | 14       | 0.38%   |
| ASUS ROG STRIX B550-I GAMING   | 14       | 0.38%   |
| MSI MS-7B89                    | 13       | 0.35%   |
| MSI MS-7B79                    | 13       | 0.35%   |
| Gigabyte X570 AORUS MASTER     | 13       | 0.35%   |
| Gigabyte B450 I AORUS PRO WIFI | 13       | 0.35%   |
| Gigabyte B450 AORUS M          | 13       | 0.35%   |
| MSI MS-7C84                    | 12       | 0.32%   |
| ASUS TUF Gaming B550M-PLUS     | 12       | 0.32%   |
| ASUS PRIME B450M-GAMING/BR     | 12       | 0.32%   |
| MSI MS-7A38                    | 11       | 0.3%    |
| MSI MS-7A34                    | 11       | 0.3%    |
| MSI MS-7817                    | 11       | 0.3%    |
| MSI MS-7693                    | 11       | 0.3%    |
| HP Compaq 8200 Elite SFF PC    | 11       | 0.3%    |
| Gigabyte B75M-D3H              | 11       | 0.3%    |
| Gigabyte B550I AORUS PRO AX    | 11       | 0.3%    |
| Dell OptiPlex 3020             | 11       | 0.3%    |
| Dell OptiPlex 3010             | 11       | 0.3%    |
| ASUS TUF Gaming X570-PRO       | 11       | 0.3%    |
| ASUS TUF Gaming B550-PLUS      | 11       | 0.3%    |
| ASUS ROG STRIX X570-E GAMING   | 11       | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 251      | 6.77%   |
| ASUS PRIME             | 196      | 5.28%   |
| Dell OptiPlex          | 157      | 4.23%   |
| ASUS TUF               | 136      | 3.67%   |
| ASUS All               | 91       | 2.45%   |
| Gigabyte X570          | 76       | 2.05%   |
| HP Compaq              | 60       | 1.62%   |
| Gigabyte B450          | 54       | 1.46%   |
| Lenovo ThinkCentre     | 51       | 1.37%   |
| Dell Precision         | 50       | 1.35%   |
| Gigabyte B450M         | 49       | 1.32%   |
| ASRock B450M           | 38       | 1.02%   |
| System76 Thelio        | 36       | 0.97%   |
| ASRock X570            | 35       | 0.94%   |
| Gigabyte B550          | 33       | 0.89%   |
| MSI MS-7C02            | 31       | 0.84%   |
| MSI MS-7C37            | 30       | 0.81%   |
| Dell Inspiron          | 29       | 0.78%   |
| MSI MS-7B86            | 28       | 0.75%   |
| Unknown                | 26       | 0.7%    |
| ASRock B450            | 24       | 0.65%   |
| ASUS SABERTOOTH        | 23       | 0.62%   |
| HP EliteDesk           | 22       | 0.59%   |
| Gigabyte A320M-S2H     | 21       | 0.57%   |
| Dell XPS               | 21       | 0.57%   |
| Gigabyte Z390          | 20       | 0.54%   |
| Acer Aspire            | 20       | 0.54%   |
| Gigabyte GA-78LMT-USB3 | 18       | 0.49%   |
| MSI MS-7C91            | 17       | 0.46%   |
| Gigabyte B550M         | 17       | 0.46%   |
| ASUS M5A97             | 17       | 0.46%   |
| ASUS M5A78L-M          | 17       | 0.46%   |
| ASUS P8Z77-V           | 16       | 0.43%   |
| Lenovo IdeaCentre      | 15       | 0.4%    |
| ASUS Crosshair         | 15       | 0.4%    |
| MSI MS-7B89            | 13       | 0.35%   |
| MSI MS-7B79            | 13       | 0.35%   |
| HP ProDesk             | 13       | 0.35%   |
| ASUS P8H61-M           | 13       | 0.35%   |
| Alienware Aurora       | 13       | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 574      | 15.47%  |
| 2020    | 428      | 11.54%  |
| 2019    | 423      | 11.4%   |
| 2012    | 293      | 7.9%    |
| 2017    | 261      | 7.04%   |
| 2013    | 256      | 6.9%    |
| 2014    | 224      | 6.04%   |
| 2011    | 215      | 5.8%    |
| 2021    | 202      | 5.44%   |
| 2015    | 155      | 4.18%   |
| 2016    | 145      | 3.91%   |
| 2010    | 137      | 3.69%   |
| 2009    | 123      | 3.32%   |
| 2022    | 113      | 3.05%   |
| 2008    | 71       | 1.91%   |
| 2007    | 54       | 1.46%   |
| 2023    | 22       | 0.59%   |
| 2006    | 12       | 0.32%   |
| 2005    | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3710     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3707     | 99.89%  |
| Enabled  | 4        | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3708     | 99.95%  |
| Yes  | 2        | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1215     | 32.07%  |
| 32.01-64.0      | 832      | 21.96%  |
| 8.01-16.0       | 671      | 17.71%  |
| 4.01-8.0        | 354      | 9.34%   |
| 3.01-4.0        | 270      | 7.13%   |
| 64.01-256.0     | 261      | 6.89%   |
| 24.01-32.0      | 133      | 3.51%   |
| 1.01-2.0        | 32       | 0.84%   |
| 2.01-3.0        | 12       | 0.32%   |
| More than 256.0 | 8        | 0.21%   |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 1059     | 25.84%  |
| 4.01-8.0    | 996      | 24.3%   |
| 1.01-2.0    | 930      | 22.69%  |
| 3.01-4.0    | 728      | 17.76%  |
| 8.01-16.0   | 305      | 7.44%   |
| 16.01-24.0  | 37       | 0.9%    |
| 24.01-32.0  | 17       | 0.41%   |
| 32.01-64.0  | 16       | 0.39%   |
| 0.51-1.0    | 8        | 0.2%    |
| 64.01-256.0 | 3        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1242     | 32.31%  |
| 2      | 1158     | 30.12%  |
| 3      | 695      | 18.08%  |
| 4      | 407      | 10.59%  |
| 5      | 178      | 4.63%   |
| 6      | 76       | 1.98%   |
| 7      | 32       | 0.83%   |
| 0      | 18       | 0.47%   |
| 8      | 12       | 0.31%   |
| 11     | 8        | 0.21%   |
| 9      | 8        | 0.21%   |
| 10     | 3        | 0.08%   |
| 26     | 1        | 0.03%   |
| 23     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 19     | 1        | 0.03%   |
| 14     | 1        | 0.03%   |
| 13     | 1        | 0.03%   |
| 12     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2545     | 68.03%  |
| Yes       | 1196     | 31.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3664     | 98.73%  |
| No        | 47       | 1.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2003     | 53.44%  |
| No        | 1745     | 46.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2232     | 59.46%  |
| Yes       | 1522     | 40.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1286     | 34.48%  |
| Brazil       | 341      | 9.14%   |
| Germany      | 284      | 7.61%   |
| UK           | 205      | 5.5%    |
| Canada       | 202      | 5.42%   |
| Australia    | 139      | 3.73%   |
| Netherlands  | 84       | 2.25%   |
| France       | 83       | 2.23%   |
| Italy        | 82       | 2.2%    |
| Sweden       | 70       | 1.88%   |
| Poland       | 63       | 1.69%   |
| Russia       | 54       | 1.45%   |
| Spain        | 41       | 1.1%    |
| Finland      | 40       | 1.07%   |
| South Africa | 39       | 1.05%   |
| India        | 38       | 1.02%   |
| Switzerland  | 31       | 0.83%   |
| Austria      | 31       | 0.83%   |
| Mexico       | 30       | 0.8%    |
| Romania      | 29       | 0.78%   |
| Norway       | 29       | 0.78%   |
| Denmark      | 28       | 0.75%   |
| Greece       | 27       | 0.72%   |
| Portugal     | 26       | 0.7%    |
| New Zealand  | 25       | 0.67%   |
| Belgium      | 25       | 0.67%   |
| Argentina    | 24       | 0.64%   |
| Philippines  | 20       | 0.54%   |
| Bulgaria     | 18       | 0.48%   |
| Czechia      | 17       | 0.46%   |
| Japan        | 16       | 0.43%   |
| Hungary      | 16       | 0.43%   |
| Chile        | 16       | 0.43%   |
| Serbia       | 13       | 0.35%   |
| Malaysia     | 13       | 0.35%   |
| Ireland      | 13       | 0.35%   |
| Slovakia     | 12       | 0.32%   |
| Ukraine      | 11       | 0.29%   |
| Lithuania    | 11       | 0.29%   |
| Israel       | 11       | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 43       | 1.11%   |
| Sydney         | 40       | 1.03%   |
| Berlin         | 30       | 0.77%   |
| Melbourne      | 26       | 0.67%   |
| Rio de Janeiro | 22       | 0.57%   |
| Brisbane       | 21       | 0.54%   |
| Miami          | 20       | 0.52%   |
| Helsinki       | 20       | 0.52%   |
| Vienna         | 17       | 0.44%   |
| Seattle        | 17       | 0.44%   |
| Denver         | 17       | 0.44%   |
| Chicago        | 16       | 0.41%   |
| Browning       | 16       | 0.41%   |
| Milan          | 15       | 0.39%   |
| Warsaw         | 14       | 0.36%   |
| Perth          | 14       | 0.36%   |
| Moscow         | 14       | 0.36%   |
| Edmonton       | 14       | 0.36%   |
| Toronto        | 13       | 0.34%   |
| Phoenix        | 13       | 0.34%   |
| Dallas         | 13       | 0.34%   |
| Sofia          | 12       | 0.31%   |
| Montreal       | 12       | 0.31%   |
| London         | 12       | 0.31%   |
| Hamburg        | 12       | 0.31%   |
| Auckland       | 12       | 0.31%   |
| Athens         | 12       | 0.31%   |
| Amsterdam      | 12       | 0.31%   |
| Adelaide       | 12       | 0.31%   |
| Washington     | 11       | 0.28%   |
| St Louis       | 11       | 0.28%   |
| Calgary        | 11       | 0.28%   |
| New York       | 10       | 0.26%   |
| Johannesburg   | 10       | 0.26%   |
| Cape Town      | 10       | 0.26%   |
| Brasília      | 10       | 0.26%   |
| Atlanta        | 10       | 0.26%   |
| Vancouver      | 9        | 0.23%   |
| Rome           | 9        | 0.23%   |
| Porto Alegre   | 9        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 1290     | 2210   | 17.59%  |
| Seagate                     | 1263     | 1980   | 17.22%  |
| WDC                         | 1190     | 1831   | 16.23%  |
| SanDisk                     | 459      | 616    | 6.26%   |
| Kingston                    | 448      | 592    | 6.11%   |
| Crucial                     | 344      | 487    | 4.69%   |
| Toshiba                     | 307      | 390    | 4.19%   |
| Hitachi                     | 179      | 246    | 2.44%   |
| Phison                      | 152      | 225    | 2.07%   |
| Intel                       | 148      | 214    | 2.02%   |
| A-DATA Technology           | 115      | 144    | 1.57%   |
| Micron/Crucial Technology   | 87       | 117    | 1.19%   |
| PNY                         | 86       | 111    | 1.17%   |
| Silicon Motion              | 84       | 116    | 1.15%   |
| China                       | 83       | 122    | 1.13%   |
| Unknown                     | 65       | 103    | 0.89%   |
| Phison Electronics          | 63       | 93     | 0.86%   |
| HGST                        | 58       | 78     | 0.79%   |
| SK hynix                    | 54       | 76     | 0.74%   |
| OCZ                         | 48       | 66     | 0.65%   |
| SPCC                        | 41       | 56     | 0.56%   |
| XPG                         | 39       | 52     | 0.53%   |
| Realtek Semiconductor       | 36       | 41     | 0.49%   |
| Micron Technology           | 36       | 51     | 0.49%   |
| Patriot                     | 33       | 47     | 0.45%   |
| Corsair                     | 32       | 45     | 0.44%   |
| Maxtor                      | 31       | 32     | 0.42%   |
| Team                        | 30       | 37     | 0.41%   |
| Intenso                     | 23       | 30     | 0.31%   |
| Kingston Technology Company | 20       | 25     | 0.27%   |
| Lexar                       | 18       | 21     | 0.25%   |
| Gigabyte Technology         | 18       | 18     | 0.25%   |
| JMicron Technology          | 16       | 26     | 0.22%   |
| Hewlett-Packard             | 16       | 24     | 0.22%   |
| Transcend                   | 15       | 18     | 0.2%    |
| KingSpec                    | 15       | 18     | 0.2%    |
| Apple                       | 15       | 18     | 0.2%    |
| ADATA Technology            | 15       | 18     | 0.2%    |
| Apacer                      | 14       | 18     | 0.19%   |
| SABRENT                     | 13       | 14     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                         | 131      | 1.53%   |
| Samsung NVMe SSD Drive 500GB                       | 117      | 1.37%   |
| Kingston SA400S37240G 240GB SSD                    | 116      | 1.36%   |
| Seagate ST2000DM008-2FR102 2TB                     | 109      | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB                     | 101      | 1.18%   |
| Samsung SSD 850 EVO 250GB                          | 100      | 1.17%   |
| Samsung SSD 850 EVO 500GB                          | 84       | 0.98%   |
| Seagate ST500DM002-1BD142 500GB                    | 83       | 0.97%   |
| Samsung SSD 860 EVO 1TB                            | 81       | 0.95%   |
| Samsung SSD 860 EVO 500GB                          | 80       | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 73       | 0.85%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 70       | 0.82%   |
| Kingston SA400S37120G 120GB SSD                    | 70       | 0.82%   |
| SanDisk NVMe SSD Drive 1TB                         | 67       | 0.78%   |
| SanDisk NVMe SSD Drive 500GB                       | 66       | 0.77%   |
| Kingston SA400S37480G 480GB SSD                    | 56       | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                        | 56       | 0.66%   |
| Seagate ST4000DM004-2CV104 4TB                     | 51       | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB                     | 49       | 0.57%   |
| Toshiba DT01ACA100 1TB                             | 47       | 0.55%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB             | 47       | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 47       | 0.55%   |
| Crucial CT500MX500SSD1 500GB                       | 45       | 0.53%   |
| Phison NVMe SSD Drive 1TB                          | 43       | 0.5%    |
| Kingston SV300S37A120G 120GB SSD                   | 42       | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB                     | 41       | 0.48%   |
| Micron/Crucial NVMe SSD Drive 1TB                  | 37       | 0.43%   |
| Crucial CT240BX500SSD1 240GB                       | 37       | 0.43%   |
| Samsung SSD 870 QVO 1TB                            | 35       | 0.41%   |
| Samsung SSD 860 EVO 250GB                          | 34       | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                       | 33       | 0.39%   |
| Samsung SSD 840 EVO 250GB                          | 33       | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB                     | 32       | 0.37%   |
| Toshiba HDWD110 1TB                                | 31       | 0.36%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 30       | 0.35%   |
| Toshiba DT01ACA200 2TB                             | 30       | 0.35%   |
| Samsung SSD 860 QVO 1TB                            | 30       | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB                     | 29       | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB                     | 29       | 0.34%   |
| Samsung NVMe SSD Drive 2TB                         | 29       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1227     | 1881   | 41%     |
| WDC                 | 1031     | 1556   | 34.45%  |
| Toshiba             | 275      | 349    | 9.19%   |
| Hitachi             | 179      | 246    | 5.98%   |
| Samsung Electronics | 119      | 145    | 3.98%   |
| HGST                | 58       | 78     | 1.94%   |
| Maxtor              | 27       | 28     | 0.9%    |
| Unknown             | 22       | 31     | 0.74%   |
| Apple               | 11       | 13     | 0.37%   |
| Fujitsu             | 5        | 9      | 0.17%   |
| ASMT                | 5        | 5      | 0.17%   |
| USB                 | 3        | 4      | 0.1%    |
| SABRENT             | 3        | 4      | 0.1%    |
| JMicron Technology  | 3        | 10     | 0.1%    |
| Hewlett-Packard     | 3        | 5      | 0.1%    |
| External            | 3        | 3      | 0.1%    |
| ExcelStor           | 3        | 3      | 0.1%    |
| Magnetic Data       | 2        | 2      | 0.07%   |
| LaCie               | 2        | 3      | 0.07%   |
| Unknown             | 2        | 3      | 0.07%   |
| WD MediaMax         | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| OEM                 | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 2      | 0.03%   |
| HPE                 | 1        | 1      | 0.03%   |
| HGST HTS            | 1        | 1      | 0.03%   |
| H/W                 | 1        | 1      | 0.03%   |
| Glyph               | 1        | 2      | 0.03%   |
| ASMT109x            | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 715      | 1130   | 26.53%  |
| Kingston            | 376      | 492    | 13.95%  |
| Crucial             | 313      | 437    | 11.61%  |
| SanDisk             | 232      | 304    | 8.61%   |
| WDC                 | 184      | 235    | 6.83%   |
| A-DATA Technology   | 101      | 128    | 3.75%   |
| PNY                 | 85       | 110    | 3.15%   |
| China               | 82       | 121    | 3.04%   |
| Intel               | 64       | 90     | 2.37%   |
| OCZ                 | 47       | 62     | 1.74%   |
| SPCC                | 36       | 44     | 1.34%   |
| Patriot             | 33       | 47     | 1.22%   |
| SK hynix            | 29       | 43     | 1.08%   |
| Team                | 27       | 33     | 1%      |
| Corsair             | 25       | 32     | 0.93%   |
| Micron Technology   | 22       | 26     | 0.82%   |
| Seagate             | 19       | 34     | 0.71%   |
| Toshiba             | 18       | 19     | 0.67%   |
| Lexar               | 16       | 19     | 0.59%   |
| Intenso             | 16       | 23     | 0.59%   |
| Transcend           | 15       | 18     | 0.56%   |
| KingSpec            | 15       | 18     | 0.56%   |
| Apacer              | 14       | 18     | 0.52%   |
| Hewlett-Packard     | 12       | 18     | 0.45%   |
| Gigabyte Technology | 12       | 12     | 0.45%   |
| SABRENT             | 10       | 10     | 0.37%   |
| GOODRAM             | 10       | 11     | 0.37%   |
| Netac               | 9        | 11     | 0.33%   |
| LITEONIT            | 9        | 9      | 0.33%   |
| Plextor             | 8        | 10     | 0.3%    |
| TO Exter            | 7        | 10     | 0.26%   |
| Mushkin             | 7        | 9      | 0.26%   |
| LITEON              | 7        | 12     | 0.26%   |
| KingDian            | 6        | 8      | 0.22%   |
| Verbatim            | 5        | 9      | 0.19%   |
| ASMT                | 5        | 9      | 0.19%   |
| OWC                 | 4        | 13     | 0.15%   |
| Maxtor              | 4        | 4      | 0.15%   |
| XPG                 | 3        | 4      | 0.11%   |
| PNY USB             | 3        | 10     | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2339     | 4390   | 38.09%  |
| SSD     | 2172     | 3762   | 35.37%  |
| NVMe    | 1480     | 2484   | 24.1%   |
| Unknown | 133      | 217    | 2.17%   |
| MMC     | 17       | 21     | 0.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3243     | 7883   | 64.43%  |
| NVMe | 1473     | 2464   | 29.27%  |
| SAS  | 300      | 506    | 5.96%   |
| MMC  | 17       | 21     | 0.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 2352     | 4056   | 47.43%  |
| 0.51-1.0        | 1440     | 2253   | 29.04%  |
| 1.01-2.0        | 625      | 922    | 12.6%   |
| 3.01-4.0        | 230      | 394    | 4.64%   |
| 2.01-3.0        | 165      | 236    | 3.33%   |
| 4.01-10.0       | 127      | 243    | 2.56%   |
| 10.01-20.0      | 19       | 47     | 0.38%   |
| More than 100.0 | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 884      | 22.63%  |
| 501-1000       | 773      | 19.79%  |
| 251-500        | 772      | 19.76%  |
| 1001-2000      | 535      | 13.7%   |
| More than 3000 | 412      | 10.55%  |
| 2001-3000      | 229      | 5.86%   |
| 51-100         | 127      | 3.25%   |
| 1-20           | 91       | 2.33%   |
| 21-50          | 59       | 1.51%   |
| Unknown        | 24       | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1253     | 30.67%  |
| 21-50          | 695      | 17.01%  |
| 101-250        | 519      | 12.7%   |
| 51-100         | 423      | 10.35%  |
| 251-500        | 392      | 9.59%   |
| 501-1000       | 304      | 7.44%   |
| 1001-2000      | 235      | 5.75%   |
| More than 3000 | 154      | 3.77%   |
| 2001-3000      | 87       | 2.13%   |
| Unknown        | 24       | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4        | 4      | 2.48%   |
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 1.86%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3        | 4      | 1.86%   |
| Seagate ST1000DM003-9YN162 1TB        | 3        | 3      | 1.86%   |
| Samsung Electronics HD502HI 500GB     | 3        | 4      | 1.86%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 5      | 1.86%   |
| Kingston SA400S37120G 120GB SSD       | 3        | 5      | 1.86%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2        | 2      | 1.24%   |
| WDC WD10EZEX-60WN4A0 1TB              | 2        | 2      | 1.24%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 1.24%   |
| Toshiba HDWD110 1TB                   | 2        | 2      | 1.24%   |
| Seagate ST3250310AS 250GB             | 2        | 4      | 1.24%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 1.24%   |
| Samsung Electronics SSD 850 EVO 250GB | 2        | 2      | 1.24%   |
| Samsung Electronics HD103SJ 1TB       | 2        | 2      | 1.24%   |
| Hitachi HDS721010CLA332 1TB           | 2        | 2      | 1.24%   |
| Hitachi HDP725050GLA360 500GB         | 2        | 2      | 1.24%   |
| Crucial CT525MX300SSD1 528GB          | 2        | 2      | 1.24%   |
| China SSD 240GB                       | 2        | 2      | 1.24%   |
| WDC WD7500BPVT-60HXZT1 752GB          | 1        | 1      | 0.62%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1        | 1      | 0.62%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1        | 1      | 0.62%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1        | 1      | 0.62%   |
| WDC WD5001AALS-00J7B1 500GB           | 1        | 1      | 0.62%   |
| WDC WD5000LPLX-00ZNTT0 500GB          | 1        | 2      | 0.62%   |
| WDC WD5000BEVT-75A0RT0 500GB          | 1        | 2      | 0.62%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1        | 1      | 0.62%   |
| WDC WD5000AAKX-753CA1 500GB           | 1        | 1      | 0.62%   |
| WDC WD5000AAKS-41YGA1 500GB           | 1        | 1      | 0.62%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 0.62%   |
| WDC WD5000AADS-00M2B0 500GB           | 1        | 1      | 0.62%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 0.62%   |
| WDC WD30EZRX-00SPEB0 3TB              | 1        | 1      | 0.62%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1        | 1      | 0.62%   |
| WDC WD20PURZ-85AKKY0 2TB              | 1        | 1      | 0.62%   |
| WDC WD20PURX-64P6ZY0 2TB              | 1        | 1      | 0.62%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 7      | 0.62%   |
| WDC WD2003FYYS-05T9B0 2TB             | 1        | 1      | 0.62%   |
| WDC WD15EVDS-73V9B0 1TB               | 1        | 1      | 0.62%   |
| WDC WD15EADS-11P8B1 1TB               | 1        | 1      | 0.62%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 44       | 54     | 28.21%  |
| WDC                         | 40       | 50     | 25.64%  |
| Samsung Electronics         | 22       | 28     | 14.1%   |
| Kingston                    | 8        | 12     | 5.13%   |
| Toshiba                     | 7        | 7      | 4.49%   |
| Hitachi                     | 6        | 7      | 3.85%   |
| HGST                        | 6        | 6      | 3.85%   |
| Crucial                     | 4        | 4      | 2.56%   |
| SanDisk                     | 2        | 2      | 1.28%   |
| Intel                       | 2        | 2      | 1.28%   |
| China                       | 2        | 2      | 1.28%   |
| Team                        | 1        | 1      | 0.64%   |
| SPCC                        | 1        | 1      | 0.64%   |
| SABRENT                     | 1        | 1      | 0.64%   |
| S3+                         | 1        | 1      | 0.64%   |
| Plextor                     | 1        | 1      | 0.64%   |
| Micron Technology           | 1        | 1      | 0.64%   |
| Maxtor                      | 1        | 1      | 0.64%   |
| Kingston Technology Company | 1        | 1      | 0.64%   |
| Intenso                     | 1        | 1      | 0.64%   |
| BAITITON                    | 1        | 1      | 0.64%   |
| ASMT                        | 1        | 1      | 0.64%   |
| Apple                       | 1        | 1      | 0.64%   |
| A-DATA Technology           | 1        | 1      | 0.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 44       | 54     | 38.26%  |
| WDC                 | 40       | 50     | 34.78%  |
| Samsung Electronics | 10       | 11     | 8.7%    |
| Toshiba             | 7        | 7      | 6.09%   |
| Hitachi             | 6        | 7      | 5.22%   |
| HGST                | 6        | 6      | 5.22%   |
| Maxtor              | 1        | 1      | 0.87%   |
| Apple               | 1        | 1      | 0.87%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 103      | 137    | 71.53%  |
| SSD  | 35       | 44     | 24.31%  |
| NVMe | 6        | 6      | 4.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 50%     |
| Patriot Pyro SSD 120GB          | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| Patriot | 1        | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3190     | 9201   | 81.19%  |
| Works    | 601      | 1482   | 15.3%   |
| Malfunc  | 135      | 187    | 3.44%   |
| Failed   | 2        | 3      | 0.05%   |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2000     | 33.98%  |
| AMD                              | 1680     | 28.54%  |
| Samsung Electronics              | 655      | 11.13%  |
| SanDisk                          | 260      | 4.42%   |
| Phison Electronics               | 223      | 3.79%   |
| ASMedia Technology               | 223      | 3.79%   |
| Micron/Crucial Technology        | 120      | 2.04%   |
| Kingston Technology Company      | 97       | 1.65%   |
| Marvell Technology Group         | 93       | 1.58%   |
| Silicon Motion                   | 91       | 1.55%   |
| JMicron Technology               | 85       | 1.44%   |
| Nvidia                           | 64       | 1.09%   |
| ADATA Technology                 | 59       | 1%      |
| Realtek Semiconductor            | 46       | 0.78%   |
| SK hynix                         | 26       | 0.44%   |
| Broadcom / LSI                   | 23       | 0.39%   |
| Seagate Technology               | 18       | 0.31%   |
| Toshiba America Info Systems     | 17       | 0.29%   |
| Micron Technology                | 17       | 0.29%   |
| LSI Logic / Symbios Logic        | 17       | 0.29%   |
| VIA Technologies                 | 12       | 0.2%    |
| Lite-On Technology               | 9        | 0.15%   |
| Silicon Image                    | 6        | 0.1%    |
| Solidigm                         | 5        | 0.08%   |
| Shenzhen Longsys Electronics     | 5        | 0.08%   |
| MAXIO Technology (Hangzhou)      | 5        | 0.08%   |
| INNOGRIT                         | 5        | 0.08%   |
| Adaptec                          | 5        | 0.08%   |
| KIOXIA                           | 3        | 0.05%   |
| HighPoint Technologies           | 3        | 0.05%   |
| Union Memory (Shenzhen)          | 2        | 0.03%   |
| Solid State Storage Technology   | 2        | 0.03%   |
| Silicon Integrated Systems [SiS] | 2        | 0.03%   |
| Hewlett-Packard                  | 2        | 0.03%   |
| OCZ Technology Group             | 1        | 0.02%   |
| Netac Technology                 | 1        | 0.02%   |
| Integrated Technology Express    | 1        | 0.02%   |
| Biwin Storage Technology         | 1        | 0.02%   |
| Beijing Starblaze Technology     | 1        | 0.02%   |
| Apple                            | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1096     | 15.22%  |
| AMD 400 Series Chipset SATA Controller                                                  | 464      | 6.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 404      | 5.61%   |
| AMD 500 Series Chipset SATA Controller                                                  | 265      | 3.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 224      | 3.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 211      | 2.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 172      | 2.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 162      | 2.25%   |
| Intel SATA Controller [RAID mode]                                                       | 161      | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 161      | 2.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 139      | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 118      | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 116      | 1.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 115      | 1.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 107      | 1.49%   |
| Phison E12 NVMe Controller                                                              | 104      | 1.44%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 85       | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 84       | 1.17%   |
| AMD 300 Series Chipset SATA Controller                                                  | 84       | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 80       | 1.11%   |
| AMD FCH SATA Controller D                                                               | 77       | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 76       | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 76       | 1.06%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 73       | 1.01%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 73       | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 67       | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 67       | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 59       | 0.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 59       | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 53       | 0.74%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 52       | 0.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 50       | 0.69%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 50       | 0.69%   |
| Intel SSD 660P Series                                                                   | 49       | 0.68%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 48       | 0.67%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 46       | 0.64%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 46       | 0.64%   |
| Nvidia MCP61 SATA Controller                                                            | 45       | 0.62%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 45       | 0.62%   |
| AMD X370 Series Chipset SATA Controller                                                 | 42       | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3169     | 57.15%  |
| NVMe | 1466     | 26.44%  |
| IDE  | 592      | 10.68%  |
| RAID | 269      | 4.85%   |
| SAS  | 36       | 0.65%   |
| SCSI | 13       | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1970     | 53.1%   |
| AMD    | 1740     | 46.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 155      | 4.15%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 120      | 3.22%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 72       | 1.93%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 72       | 1.93%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 62       | 1.66%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 60       | 1.61%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 59       | 1.58%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 56       | 1.5%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 52       | 1.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 51       | 1.37%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 46       | 1.23%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 44       | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 43       | 1.15%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 42       | 1.13%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 41       | 1.1%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 40       | 1.07%   |
| AMD FX-8350 Eight-Core Processor            | 39       | 1.05%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 38       | 1.02%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 37       | 0.99%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 37       | 0.99%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 35       | 0.94%   |
| AMD FX-6300 Six-Core Processor              | 35       | 0.94%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 34       | 0.91%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 32       | 0.86%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 31       | 0.83%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 31       | 0.83%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 30       | 0.8%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 30       | 0.8%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 27       | 0.72%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 26       | 0.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 25       | 0.67%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 25       | 0.67%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 24       | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 23       | 0.62%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 23       | 0.62%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 22       | 0.59%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 21       | 0.56%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 21       | 0.56%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 21       | 0.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 20       | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 604      | 16.21%  |
| AMD Ryzen 5             | 595      | 15.96%  |
| Intel Core i7           | 566      | 15.19%  |
| AMD Ryzen 7             | 413      | 11.08%  |
| AMD Ryzen 9             | 218      | 5.85%   |
| Intel Core i3           | 183      | 4.91%   |
| Intel Xeon              | 181      | 4.86%   |
| AMD FX                  | 131      | 3.51%   |
| Other                   | 101      | 2.71%   |
| AMD Ryzen 3             | 67       | 1.8%    |
| Intel Core i9           | 60       | 1.61%   |
| Intel Core 2 Duo        | 58       | 1.56%   |
| AMD Ryzen Threadripper  | 52       | 1.4%    |
| Intel Pentium           | 49       | 1.31%   |
| Intel Core 2 Quad       | 49       | 1.31%   |
| Intel Celeron           | 42       | 1.13%   |
| AMD Phenom II X4        | 35       | 0.94%   |
| Intel Pentium Dual-Core | 31       | 0.83%   |
| AMD A10                 | 29       | 0.78%   |
| AMD A8                  | 27       | 0.72%   |
| AMD Athlon II X2        | 26       | 0.7%    |
| AMD Athlon              | 18       | 0.48%   |
| Intel Core 2            | 17       | 0.46%   |
| AMD Athlon II X4        | 17       | 0.46%   |
| AMD A6                  | 15       | 0.4%    |
| AMD Phenom II X6        | 14       | 0.38%   |
| AMD A4                  | 13       | 0.35%   |
| Intel Atom              | 10       | 0.27%   |
| AMD Ryzen 5 PRO         | 10       | 0.27%   |
| AMD Athlon 64 X2        | 10       | 0.27%   |
| AMD Phenom              | 9        | 0.24%   |
| Intel Pentium Dual      | 8        | 0.21%   |
| AMD Athlon X4           | 8        | 0.21%   |
| Intel Pentium Gold      | 7        | 0.19%   |
| Intel Pentium D         | 6        | 0.16%   |
| AMD Sempron             | 5        | 0.13%   |
| AMD Ryzen 7 PRO         | 4        | 0.11%   |
| AMD Ryzen 3 PRO         | 4        | 0.11%   |
| AMD Athlon II X3        | 4        | 0.11%   |
| AMD Athlon 64           | 4        | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1375     | 36.9%   |
| 6      | 788      | 21.15%  |
| 8      | 571      | 15.32%  |
| 2      | 509      | 13.66%  |
| 12     | 183      | 4.91%   |
| 16     | 112      | 3.01%   |
| 3      | 54       | 1.45%   |
| 10     | 46       | 1.23%   |
| 1      | 32       | 0.86%   |
| 24     | 20       | 0.54%   |
| 32     | 16       | 0.43%   |
| 14     | 12       | 0.32%   |
| 64     | 4        | 0.11%   |
| 18     | 2        | 0.05%   |
| 36     | 1        | 0.03%   |
| 28     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3668     | 98.87%  |
| 2      | 42       | 1.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2562     | 68.93%  |
| 1      | 1155     | 31.07%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3706     | 99.89%  |
| Unknown        | 4        | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2756     | 72.68%  |
| 0x08701021 | 109      | 2.87%   |
| 0x306c3    | 77       | 2.03%   |
| 0x0800820d | 76       | 2%      |
| 0x08701013 | 73       | 1.93%   |
| 0x306a9    | 63       | 1.66%   |
| 0x206a7    | 50       | 1.32%   |
| 0x506e3    | 42       | 1.11%   |
| 0x906ea    | 38       | 1%      |
| 0x906e9    | 30       | 0.79%   |
| 0x08001138 | 28       | 0.74%   |
| 0x1067a    | 27       | 0.71%   |
| 0x0a201016 | 26       | 0.69%   |
| 0x08108109 | 25       | 0.66%   |
| 0x06000852 | 25       | 0.66%   |
| 0x0a601203 | 16       | 0.42%   |
| 0x0a201009 | 16       | 0.42%   |
| 0x906ec    | 15       | 0.4%    |
| 0x906ed    | 14       | 0.37%   |
| 0x08301039 | 14       | 0.37%   |
| 0x08001137 | 12       | 0.32%   |
| 0xa0655    | 11       | 0.29%   |
| 0x06001119 | 11       | 0.29%   |
| 0x010000c8 | 11       | 0.29%   |
| 0x306f2    | 9        | 0.24%   |
| 0x106a5    | 9        | 0.24%   |
| 0x0a20120a | 9        | 0.24%   |
| 0x06003106 | 9        | 0.24%   |
| 0xa0653    | 8        | 0.21%   |
| 0x206c2    | 8        | 0.21%   |
| 0xa0671    | 7        | 0.18%   |
| 0x906eb    | 7        | 0.18%   |
| 0x0a50000c | 7        | 0.18%   |
| 0x90672    | 6        | 0.16%   |
| 0x6fd      | 6        | 0.16%   |
| 0x206d7    | 6        | 0.16%   |
| 0x20655    | 6        | 0.16%   |
| 0x0a50000d | 6        | 0.16%   |
| 0x08101016 | 6        | 0.16%   |
| 0x6fb      | 5        | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 532      | 14.29%  |
| Haswell          | 390      | 10.48%  |
| KabyLake         | 324      | 8.7%    |
| Zen 3            | 323      | 8.68%   |
| Zen+             | 285      | 7.66%   |
| IvyBridge        | 258      | 6.93%   |
| SandyBridge      | 235      | 6.31%   |
| Skylake          | 188      | 5.05%   |
| Zen              | 185      | 4.97%   |
| Piledriver       | 156      | 4.19%   |
| Unknown          | 134      | 3.6%    |
| Penryn           | 116      | 3.12%   |
| K10              | 115      | 3.09%   |
| CometLake        | 104      | 2.79%   |
| Nehalem          | 78       | 2.1%    |
| Westmere         | 61       | 1.64%   |
| Core             | 59       | 1.58%   |
| Steamroller      | 27       | 0.73%   |
| Silvermont       | 21       | 0.56%   |
| K8 Hammer        | 18       | 0.48%   |
| Excavator        | 17       | 0.46%   |
| Alderlake Hybrid | 15       | 0.4%    |
| Bulldozer        | 14       | 0.38%   |
| K10 Llano        | 13       | 0.35%   |
| Broadwell        | 11       | 0.3%    |
| NetBurst         | 9        | 0.24%   |
| Icelake          | 8        | 0.21%   |
| Goldmont plus    | 8        | 0.21%   |
| Jaguar           | 7        | 0.19%   |
| Goldmont         | 4        | 0.11%   |
| Bobcat           | 4        | 0.11%   |
| Bonnell          | 2        | 0.05%   |
| Tremont          | 1        | 0.03%   |
| Puma             | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 1950     | 48.53%  |
| AMD                              | 1356     | 33.75%  |
| Intel                            | 705      | 17.55%  |
| Matrox Electronics Systems       | 5        | 0.12%   |
| Silicon Integrated Systems [SiS] | 2        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 270      | 6.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 141      | 3.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 124      | 2.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 113      | 2.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 85       | 2.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 84       | 2.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 82       | 1.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 72       | 1.73%   |
| Nvidia GK208B [GeForce GT 710]                                              | 70       | 1.68%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 66       | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 66       | 1.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 63       | 1.51%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 59       | 1.42%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 58       | 1.39%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 56       | 1.34%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 52       | 1.25%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 52       | 1.25%   |
| Intel HD Graphics 530                                                       | 52       | 1.25%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 45       | 1.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 45       | 1.08%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 45       | 1.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 45       | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 43       | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 41       | 0.98%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 39       | 0.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 38       | 0.91%   |
| AMD Raphael                                                                 | 38       | 0.91%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 38       | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 35       | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 33       | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 33       | 0.79%   |
| Nvidia GT218 [GeForce 210]                                                  | 33       | 0.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 33       | 0.79%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 33       | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 32       | 0.77%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 32       | 0.77%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 30       | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 30       | 0.72%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 30       | 0.72%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 30       | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1791     | 47.46%  |
| 1 x AMD              | 1208     | 32.01%  |
| 1 x Intel            | 512      | 13.57%  |
| 2 x AMD              | 66       | 1.75%   |
| Intel + Nvidia       | 60       | 1.59%   |
| AMD + Nvidia         | 58       | 1.54%   |
| 2 x Nvidia           | 36       | 0.95%   |
| Intel + AMD          | 28       | 0.74%   |
| 1 x Matrox           | 4        | 0.11%   |
| 1 x SiS              | 2        | 0.05%   |
| Intel + 2 x Nvidia   | 2        | 0.05%   |
| Other                | 1        | 0.03%   |
| 5 x Nvidia           | 1        | 0.03%   |
| 4 x Nvidia           | 1        | 0.03%   |
| 3 x Nvidia           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.03%   |
| AMD + 2 x Nvidia     | 1        | 0.03%   |
| AMD + Matrox         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1965     | 52.11%  |
| Proprietary | 1591     | 42.19%  |
| Unknown     | 215      | 5.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2098     | 55.09%  |
| 7.01-8.0   | 479      | 12.58%  |
| 1.01-2.0   | 307      | 8.06%   |
| 3.01-4.0   | 296      | 7.77%   |
| 5.01-6.0   | 245      | 6.43%   |
| 8.01-16.0  | 165      | 4.33%   |
| 0.51-1.0   | 87       | 2.28%   |
| 2.01-3.0   | 50       | 1.31%   |
| 0.01-0.5   | 50       | 1.31%   |
| 16.01-24.0 | 26       | 0.68%   |
| 4.01-5.0   | 3        | 0.08%   |
| 32.01-64.0 | 1        | 0.03%   |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 674      | 16.35%  |
| Goldstar             | 467      | 11.33%  |
| Dell                 | 450      | 10.92%  |
| Acer                 | 366      | 8.88%   |
| Hewlett-Packard      | 255      | 6.19%   |
| AOC                  | 242      | 5.87%   |
| Ancor Communications | 196      | 4.75%   |
| BenQ                 | 187      | 4.54%   |
| ASUSTek Computer     | 145      | 3.52%   |
| Philips              | 123      | 2.98%   |
| ViewSonic            | 71       | 1.72%   |
| Lenovo               | 66       | 1.6%    |
| Iiyama               | 66       | 1.6%    |
| MSI                  | 56       | 1.36%   |
| Sony                 | 54       | 1.31%   |
| Sceptre Tech         | 42       | 1.02%   |
| Vizio                | 32       | 0.78%   |
| Gigabyte Technology  | 31       | 0.75%   |
| Toshiba              | 25       | 0.61%   |
| Unknown              | 23       | 0.56%   |
| Panasonic            | 20       | 0.49%   |
| Eizo                 | 19       | 0.46%   |
| NEC Computers        | 18       | 0.44%   |
| Insignia             | 17       | 0.41%   |
| Fujitsu Siemens      | 17       | 0.41%   |
| LG Electronics       | 14       | 0.34%   |
| Hitachi              | 14       | 0.34%   |
| MStar                | 13       | 0.32%   |
| Vestel Elektronik    | 11       | 0.27%   |
| Mi                   | 11       | 0.27%   |
| ONN                  | 10       | 0.24%   |
| HannStar             | 10       | 0.24%   |
| Pixio                | 9        | 0.22%   |
| Medion               | 9        | 0.22%   |
| HKC                  | 9        | 0.22%   |
| Viotek               | 8        | 0.19%   |
| Videoseven           | 8        | 0.19%   |
| Sharp                | 8        | 0.19%   |
| CVT                  | 8        | 0.19%   |
| ___                  | 7        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 43       | 0.98%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 35       | 0.8%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 26       | 0.59%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 21       | 0.48%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 20       | 0.46%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 16       | 0.36%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 16       | 0.36%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 16       | 0.36%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 15       | 0.34%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 13       | 0.3%    |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 13       | 0.3%    |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 13       | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 12       | 0.27%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 12       | 0.27%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 12       | 0.27%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 12       | 0.27%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 11       | 0.25%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 11       | 0.25%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 11       | 0.25%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 10       | 0.23%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 10       | 0.23%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 10       | 0.23%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 10       | 0.23%   |
| Acer V246HQL ACR0424 1920x1080 521x293mm 23.5-inch                    | 10       | 0.23%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 9        | 0.21%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 9        | 0.21%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 9        | 0.21%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 9        | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 9        | 0.21%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 9        | 0.21%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 9        | 0.21%   |
| AOC Q2770 AOC2770 2560x1440 597x336mm 27.0-inch                       | 9        | 0.21%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 9        | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 9        | 0.21%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch               | 8        | 0.18%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 8        | 0.18%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 8        | 0.18%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 8        | 0.18%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch               | 8        | 0.18%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 8        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1796     | 45.64%  |
| 3840x2160 (4K)     | 518      | 13.16%  |
| 2560x1440 (QHD)    | 411      | 10.44%  |
| 3440x1440          | 155      | 3.94%   |
| 1680x1050 (WSXGA+) | 154      | 3.91%   |
| 1280x1024 (SXGA)   | 142      | 3.61%   |
| 1366x768 (WXGA)    | 135      | 3.43%   |
| 2560x1080          | 122      | 3.1%    |
| 1440x900 (WXGA+)   | 90       | 2.29%   |
| 1920x1200 (WUXGA)  | 89       | 2.26%   |
| 1600x900 (HD+)     | 85       | 2.16%   |
| 1360x768           | 47       | 1.19%   |
| 3840x1080          | 35       | 0.89%   |
| 1920x540           | 33       | 0.84%   |
| Unknown            | 28       | 0.71%   |
| 3840x1600          | 15       | 0.38%   |
| 1024x768 (XGA)     | 12       | 0.3%    |
| 1600x1200          | 11       | 0.28%   |
| 1280x720 (HD)      | 11       | 0.28%   |
| 2560x1600          | 8        | 0.2%    |
| 4480x1440          | 4        | 0.1%    |
| 2048x1152          | 4        | 0.1%    |
| 5120x1440          | 2        | 0.05%   |
| 3840x1200          | 2        | 0.05%   |
| 2288x1287          | 2        | 0.05%   |
| 9840x3840          | 1        | 0.03%   |
| 8320x2160          | 1        | 0.03%   |
| 8160x4627          | 1        | 0.03%   |
| 7680x2160          | 1        | 0.03%   |
| 6400x1440          | 1        | 0.03%   |
| 5280x1080          | 1        | 0.03%   |
| 5200x2160          | 1        | 0.03%   |
| 4096x2160          | 1        | 0.03%   |
| 4080x2030          | 1        | 0.03%   |
| 4080x2026          | 1        | 0.03%   |
| 3360x1080          | 1        | 0.03%   |
| 3280x2048          | 1        | 0.03%   |
| 3280x1080          | 1        | 0.03%   |
| 3040x900           | 1        | 0.03%   |
| 2960x1050          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 718      | 17.42%  |
| 24      | 630      | 15.28%  |
| 23      | 489      | 11.86%  |
| 21      | 388      | 9.41%   |
| 31      | 267      | 6.48%   |
| 34      | 231      | 5.6%    |
| 19      | 161      | 3.91%   |
| Unknown | 136      | 3.3%    |
| 22      | 114      | 2.77%   |
| 18      | 113      | 2.74%   |
| 20      | 92       | 2.23%   |
| 84      | 87       | 2.11%   |
| 17      | 74       | 1.8%    |
| 32      | 67       | 1.63%   |
| 72      | 64       | 1.55%   |
| 15      | 53       | 1.29%   |
| 40      | 44       | 1.07%   |
| 54      | 41       | 0.99%   |
| 48      | 31       | 0.75%   |
| 26      | 31       | 0.75%   |
| 25      | 28       | 0.68%   |
| 28      | 26       | 0.63%   |
| 35      | 21       | 0.51%   |
| 65      | 20       | 0.49%   |
| 52      | 18       | 0.44%   |
| 37      | 17       | 0.41%   |
| 49      | 16       | 0.39%   |
| 29      | 16       | 0.39%   |
| 46      | 12       | 0.29%   |
| 36      | 12       | 0.29%   |
| 33      | 11       | 0.27%   |
| 42      | 9        | 0.22%   |
| 12      | 8        | 0.19%   |
| 74      | 7        | 0.17%   |
| 55      | 7        | 0.17%   |
| 43      | 6        | 0.15%   |
| 38      | 6        | 0.15%   |
| 57      | 4        | 0.1%    |
| 47      | 4        | 0.1%    |
| 44      | 4        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1645     | 41.74%  |
| 401-500        | 767      | 19.46%  |
| 601-700        | 401      | 10.18%  |
| 701-800        | 313      | 7.94%   |
| 1001-1500      | 168      | 4.26%   |
| 1501-2000      | 162      | 4.11%   |
| Unknown        | 136      | 3.45%   |
| 301-350        | 116      | 2.94%   |
| 351-400        | 100      | 2.54%   |
| 801-900        | 96       | 2.44%   |
| 901-1000       | 19       | 0.48%   |
| 201-300        | 17       | 0.43%   |
| More than 2000 | 1        | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2642     | 72.5%   |
| 16/10   | 397      | 10.89%  |
| 21/9    | 283      | 7.77%   |
| 5/4     | 139      | 3.81%   |
| Unknown | 79       | 2.17%   |
| 4/3     | 40       | 1.1%    |
| 32/9    | 39       | 1.07%   |
| 3/2     | 10       | 0.27%   |
| 6/5     | 7        | 0.19%   |
| 1.96    | 5        | 0.14%   |
| 3.20    | 2        | 0.05%   |
| 1.00    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1267     | 31.57%  |
| 301-350        | 738      | 18.39%  |
| 351-500        | 606      | 15.1%   |
| 151-200        | 362      | 9.02%   |
| More than 1000 | 273      | 6.8%    |
| 251-300        | 241      | 6.01%   |
| 501-1000       | 155      | 3.86%   |
| 141-150        | 154      | 3.84%   |
| Unknown        | 136      | 3.39%   |
| 101-110        | 43       | 1.07%   |
| 71-80          | 11       | 0.27%   |
| 131-140        | 8        | 0.2%    |
| 111-120        | 6        | 0.15%   |
| 91-100         | 6        | 0.15%   |
| 51-60          | 4        | 0.1%    |
| 121-130        | 3        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2305     | 61.53%  |
| 101-120       | 807      | 21.54%  |
| 121-160       | 210      | 5.61%   |
| 1-50          | 200      | 5.34%   |
| Unknown       | 136      | 3.63%   |
| 161-240       | 87       | 2.32%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2638     | 69.46%  |
| 2     | 794      | 20.91%  |
| 0     | 248      | 6.53%   |
| 3     | 103      | 2.71%   |
| 4     | 13       | 0.34%   |
| 6     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 2207     | 40.16%  |
| Intel                                 | 1810     | 32.93%  |
| Qualcomm Atheros                      | 317      | 5.77%   |
| Broadcom                              | 184      | 3.35%   |
| TP-Link                               | 108      | 1.97%   |
| Ralink Technology                     | 105      | 1.91%   |
| Microsoft                             | 71       | 1.29%   |
| MediaTek                              | 67       | 1.22%   |
| Nvidia                                | 52       | 0.95%   |
| Ralink                                | 49       | 0.89%   |
| Samsung Electronics                   | 46       | 0.84%   |
| NetGear                               | 39       | 0.71%   |
| InterBiometrics                       | 38       | 0.69%   |
| Aquantia                              | 38       | 0.69%   |
| Qualcomm Atheros Communications       | 37       | 0.67%   |
| Marvell Technology Group              | 24       | 0.44%   |
| Google                                | 23       | 0.42%   |
| Xiaomi                                | 22       | 0.4%    |
| Linksys                               | 19       | 0.35%   |
| D-Link                                | 19       | 0.35%   |
| Huawei Technologies                   | 17       | 0.31%   |
| Broadcom Limited                      | 17       | 0.31%   |
| ASIX Electronics                      | 15       | 0.27%   |
| ASUSTek Computer                      | 14       | 0.25%   |
| D-Link System                         | 11       | 0.2%    |
| Edimax Technology                     | 9        | 0.16%   |
| Belkin Components                     | 9        | 0.16%   |
| OPPO Electronics                      | 8        | 0.15%   |
| OnePlus Technology (Shenzhen)         | 8        | 0.15%   |
| Motorola PCS                          | 7        | 0.13%   |
| Mellanox Technologies                 | 6        | 0.11%   |
| DisplayLink                           | 6        | 0.11%   |
| AVM                                   | 6        | 0.11%   |
| VIA Technologies                      | 5        | 0.09%   |
| Sitecom Europe                        | 5        | 0.09%   |
| Gemtek                                | 5        | 0.09%   |
| Mercucys                              | 4        | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.07%   |
| Qualcomm                              | 3        | 0.05%   |
| Microchip Technology                  | 3        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1689     | 26.38%  |
| Intel I211 Gigabit Network Connection                             | 426      | 6.65%   |
| Intel Wi-Fi 6 AX200                                               | 378      | 5.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 269      | 4.2%    |
| Intel Ethernet Controller I225-V                                  | 170      | 2.66%   |
| Intel Ethernet Connection (2) I219-V                              | 156      | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 133      | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 105      | 1.64%   |
| Intel Wireless-AC 9260                                            | 101      | 1.58%   |
| Intel Ethernet Connection (7) I219-V                              | 92       | 1.44%   |
| Intel Ethernet Connection I217-LM                                 | 86       | 1.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 63       | 0.98%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 61       | 0.95%   |
| Realtek 802.11ac NIC                                              | 58       | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 54       | 0.84%   |
| Intel 82579V Gigabit Network Connection                           | 54       | 0.84%   |
| Intel Ethernet Connection (2) I218-V                              | 50       | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 48       | 0.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47       | 0.73%   |
| Ralink MT7601U Wireless Adapter                                   | 46       | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 46       | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 44       | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 42       | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 41       | 0.64%   |
| Nvidia MCP61 Ethernet                                             | 39       | 0.61%   |
| InterBiometrics Io                                                | 37       | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 34       | 0.53%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 33       | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                   | 31       | 0.48%   |
| Intel Wireless 7265                                               | 31       | 0.48%   |
| Intel 82574L Gigabit Network Connection                           | 31       | 0.48%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 29       | 0.45%   |
| Intel Wireless 8265 / 8275                                        | 29       | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 28       | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 28       | 0.44%   |
| Microsoft Xbox 360 Wireless Adapter                               | 28       | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 28       | 0.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 27       | 0.42%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 26       | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 879      | 40.69%  |
| Realtek Semiconductor                 | 421      | 19.49%  |
| Qualcomm Atheros                      | 164      | 7.59%   |
| Broadcom                              | 111      | 5.14%   |
| Ralink Technology                     | 105      | 4.86%   |
| TP-Link                               | 102      | 4.72%   |
| Microsoft                             | 71       | 3.29%   |
| MediaTek                              | 63       | 2.92%   |
| Ralink                                | 49       | 2.27%   |
| NetGear                               | 39       | 1.81%   |
| Qualcomm Atheros Communications       | 37       | 1.71%   |
| Linksys                               | 18       | 0.83%   |
| D-Link                                | 18       | 0.83%   |
| ASUSTek Computer                      | 14       | 0.65%   |
| Edimax Technology                     | 9        | 0.42%   |
| Belkin Components                     | 9        | 0.42%   |
| D-Link System                         | 7        | 0.32%   |
| Broadcom Limited                      | 7        | 0.32%   |
| AVM                                   | 6        | 0.28%   |
| Sitecom Europe                        | 5        | 0.23%   |
| Gemtek                                | 5        | 0.23%   |
| Mercucys                              | 4        | 0.19%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.19%   |
| IMC Networks                          | 3        | 0.14%   |
| ZyDAS                                 | 1        | 0.05%   |
| Wilocity                              | 1        | 0.05%   |
| Wacom                                 | 1        | 0.05%   |
| TRENDnet                              | 1        | 0.05%   |
| Texas Instruments                     | 1        | 0.05%   |
| Samsung Electronics                   | 1        | 0.05%   |
| Ovislink                              | 1        | 0.05%   |
| Micro Star International              | 1        | 0.05%   |
| BUFFALO                               | 1        | 0.05%   |
| Accton Technology                     | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 378      | 17.32%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 105      | 4.81%   |
| Intel Wireless-AC 9260                                         | 101      | 4.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 63       | 2.89%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 61       | 2.79%   |
| Realtek 802.11ac NIC                                           | 58       | 2.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 54       | 2.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 48       | 2.2%    |
| Ralink MT7601U Wireless Adapter                                | 46       | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 44       | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 34       | 1.56%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 33       | 1.51%   |
| Qualcomm Atheros AR9271 802.11n                                | 31       | 1.42%   |
| Intel Wireless 7265                                            | 31       | 1.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 29       | 1.33%   |
| Intel Wireless 8265 / 8275                                     | 29       | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 28       | 1.28%   |
| Microsoft Xbox 360 Wireless Adapter                            | 28       | 1.28%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 26       | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 24       | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23       | 1.05%   |
| Intel Wireless 7260                                            | 23       | 1.05%   |
| Intel Wireless 8260                                            | 22       | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 22       | 1.01%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 21       | 0.96%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 21       | 0.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 19       | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 18       | 0.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 18       | 0.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17       | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 17       | 0.78%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 17       | 0.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 16       | 0.73%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 16       | 0.73%   |
| Ralink RT5370 Wireless Adapter                                 | 15       | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 15       | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 14       | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 14       | 0.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 13       | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 13       | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 2037     | 50.52%  |
| Intel                            | 1429     | 35.44%  |
| Qualcomm Atheros                 | 166      | 4.12%   |
| Broadcom                         | 80       | 1.98%   |
| Nvidia                           | 52       | 1.29%   |
| Samsung Electronics              | 45       | 1.12%   |
| Aquantia                         | 38       | 0.94%   |
| Marvell Technology Group         | 24       | 0.6%    |
| Google                           | 23       | 0.57%   |
| Xiaomi                           | 22       | 0.55%   |
| Huawei Technologies              | 17       | 0.42%   |
| ASIX Electronics                 | 15       | 0.37%   |
| Broadcom Limited                 | 10       | 0.25%   |
| OPPO Electronics                 | 8        | 0.2%    |
| TP-Link                          | 6        | 0.15%   |
| DisplayLink                      | 6        | 0.15%   |
| VIA Technologies                 | 5        | 0.12%   |
| OnePlus Technology (Shenzhen)    | 5        | 0.12%   |
| Motorola PCS                     | 5        | 0.12%   |
| Mellanox Technologies            | 4        | 0.1%    |
| MediaTek                         | 4        | 0.1%    |
| D-Link System                    | 4        | 0.1%    |
| Qualcomm                         | 3        | 0.07%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.05%   |
| Lenovo                           | 2        | 0.05%   |
| ICS Advent                       | 2        | 0.05%   |
| 3Com                             | 2        | 0.05%   |
| Tehuti Networks                  | 1        | 0.02%   |
| T & A Mobile Phones              | 1        | 0.02%   |
| Solarflare Communications        | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| QLogic                           | 1        | 0.02%   |
| Netchip Technology               | 1        | 0.02%   |
| Linksys                          | 1        | 0.02%   |
| LG Electronics                   | 1        | 0.02%   |
| JMicron Technology               | 1        | 0.02%   |
| HMD Global                       | 1        | 0.02%   |
| Hangzhou Silan Microelectronics  | 1        | 0.02%   |
| Emulex                           | 1        | 0.02%   |
| D-Link                           | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1689     | 40.74%  |
| Intel I211 Gigabit Network Connection                             | 426      | 10.27%  |
| Realtek RTL8125 2.5GbE Controller                                 | 269      | 6.49%   |
| Intel Ethernet Controller I225-V                                  | 170      | 4.1%    |
| Intel Ethernet Connection (2) I219-V                              | 156      | 3.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 133      | 3.21%   |
| Intel Ethernet Connection (7) I219-V                              | 92       | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 86       | 2.07%   |
| Intel 82579V Gigabit Network Connection                           | 54       | 1.3%    |
| Intel Ethernet Connection (2) I218-V                              | 50       | 1.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47       | 1.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 46       | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 42       | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 41       | 0.99%   |
| Nvidia MCP61 Ethernet                                             | 39       | 0.94%   |
| Intel 82574L Gigabit Network Connection                           | 31       | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 28       | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 28       | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 27       | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25       | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 25       | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 24       | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22       | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19       | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 18       | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 17       | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 16       | 0.39%   |
| Huawei ALP-AL00                                                   | 15       | 0.36%   |
| Google Nexus/Pixel Device (tether)                                | 15       | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.34%   |
| Intel Ethernet Connection (2) I218-LM                             | 13       | 0.31%   |
| Intel Ethernet Connection (14) I219-V                             | 13       | 0.31%   |
| Intel 82578DM Gigabit Network Connection                          | 13       | 0.31%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 13       | 0.31%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12       | 0.29%   |
| Intel Ethernet Connection (11) I219-V                             | 11       | 0.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10       | 0.24%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10       | 0.24%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 9        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3665     | 63.82%  |
| WiFi     | 2005     | 34.91%  |
| Modem    | 58       | 1.01%   |
| Unknown  | 15       | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2787     | 70.84%  |
| WiFi     | 1145     | 29.11%  |
| Unknown  | 2        | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2139     | 57.27%  |
| 2     | 1339     | 35.85%  |
| 3     | 188      | 5.03%   |
| 0     | 35       | 0.94%   |
| 4     | 24       | 0.64%   |
| 5     | 6        | 0.16%   |
| 10    | 2        | 0.05%   |
| 6     | 2        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2911     | 76.87%  |
| Yes  | 876      | 23.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 811      | 52.15%  |
| Cambridge Silicon Radio         | 304      | 19.55%  |
| ASUSTek Computer                | 91       | 5.85%   |
| Realtek Semiconductor           | 82       | 5.27%   |
| Broadcom                        | 65       | 4.18%   |
| Qualcomm Atheros Communications | 47       | 3.02%   |
| MediaTek                        | 38       | 2.44%   |
| Apple                           | 30       | 1.93%   |
| TP-Link                         | 14       | 0.9%    |
| IMC Networks                    | 14       | 0.9%    |
| Foxconn / Hon Hai               | 12       | 0.77%   |
| Dynex                           | 8        | 0.51%   |
| Realtek                         | 4        | 0.26%   |
| Lite-On Technology              | 4        | 0.26%   |
| Integrated System Solution      | 4        | 0.26%   |
| HTC (High Tech Computer)        | 4        | 0.26%   |
| Actions                         | 3        | 0.19%   |
| SINO WEALTH                     | 2        | 0.13%   |
| Ralink                          | 2        | 0.13%   |
| Logitech                        | 2        | 0.13%   |
| Hewlett-Packard                 | 2        | 0.13%   |
| Edimax Technology               | 2        | 0.13%   |
| Dell                            | 2        | 0.13%   |
| Creative Technology             | 2        | 0.13%   |
| Conwise Technology              | 2        | 0.13%   |
| Belkin Components               | 2        | 0.13%   |
| Primax Electronics              | 1        | 0.06%   |
| Micro Star International        | 1        | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 349      | 22.39%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 304      | 19.5%   |
| Intel Bluetooth wireless interface                                   | 104      | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 102      | 6.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 95       | 6.09%   |
| Realtek Bluetooth Radio                                              | 56       | 3.59%   |
| Intel AX201 Bluetooth                                                | 52       | 3.34%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 49       | 3.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 46       | 2.95%   |
| Intel AX210 Bluetooth                                                | 43       | 2.76%   |
| MediaTek Wireless_Device                                             | 38       | 2.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 31       | 1.99%   |
| Qualcomm Atheros  Bluetooth Device                                   | 25       | 1.6%    |
| ASUS Bluetooth Radio                                                 | 25       | 1.6%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 19       | 1.22%   |
| Intel Bluetooth Device                                               | 19       | 1.22%   |
| TP-Link UB500 Adapter                                                | 14       | 0.9%    |
| Apple Bluetooth Host Controller                                      | 14       | 0.9%    |
| ASUS ASUS USB-BT500                                                  | 12       | 0.77%   |
| IMC Networks Bluetooth Radio                                         | 9        | 0.58%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 8        | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.45%   |
| ASUS BCM20702A0                                                      | 7        | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 7        | 0.45%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 6        | 0.38%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.38%   |
| Realtek RTL8821A Bluetooth                                           | 5        | 0.32%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 5        | 0.32%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 5        | 0.32%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 5        | 0.32%   |
| Apple Bluetooth HCI                                                  | 5        | 0.32%   |
| Realtek Bluetooth Radio                                              | 4        | 0.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 0.26%   |
| IMC Networks Wireless_Device                                         | 4        | 0.26%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.26%   |
| Foxconn / Hon Hai Wireless_Device                                    | 4        | 0.26%   |
| Apple Bluetooth USB Host Controller                                  | 4        | 0.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 3        | 0.19%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 3        | 0.19%   |
| ASUS Bluetooth Device                                                | 3        | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 2072     | 28.83%  |
| Nvidia                                          | 1888     | 26.27%  |
| Intel                                           | 1878     | 26.13%  |
| C-Media Electronics                             | 209      | 2.91%   |
| Logitech                                        | 102      | 1.42%   |
| Creative Labs                                   | 74       | 1.03%   |
| Kingston Technology                             | 61       | 0.85%   |
| Razer USA                                       | 60       | 0.83%   |
| JMTek                                           | 51       | 0.71%   |
| Corsair                                         | 50       | 0.7%    |
| SteelSeries ApS                                 | 49       | 0.68%   |
| ASUSTek Computer                                | 46       | 0.64%   |
| Focusrite-Novation                              | 44       | 0.61%   |
| Texas Instruments                               | 42       | 0.58%   |
| Creative Technology                             | 31       | 0.43%   |
| Blue Microphones                                | 29       | 0.4%    |
| Micro Star International                        | 25       | 0.35%   |
| Generalplus Technology                          | 25       | 0.35%   |
| Giga-Byte Technology                            | 19       | 0.26%   |
| GN Netcom                                       | 17       | 0.24%   |
| Astro Gaming                                    | 16       | 0.22%   |
| Sony                                            | 15       | 0.21%   |
| DSEA A/S                                        | 14       | 0.19%   |
| Plantronics                                     | 13       | 0.18%   |
| Tenx Technology                                 | 12       | 0.17%   |
| Samson Technologies                             | 12       | 0.17%   |
| Realtek Semiconductor                           | 12       | 0.17%   |
| M-Audio                                         | 12       | 0.17%   |
| Turtle Beach                                    | 11       | 0.15%   |
| SAVITECH                                        | 11       | 0.15%   |
| Valve Software                                  | 10       | 0.14%   |
| Yamaha                                          | 9        | 0.13%   |
| Thesycon Systemsoftware & Consulting            | 9        | 0.13%   |
| FiiO Electronics Technology                     | 9        | 0.13%   |
| BEHRINGER International                         | 9        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 8        | 0.11%   |
| Audio-Technica                                  | 7        | 0.1%    |
| VIA Technologies                                | 6        | 0.08%   |
| Schiit Audio                                    | 6        | 0.08%   |
| PreSonus Audio Electronics                      | 6        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 740      | 8.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 320      | 3.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 275      | 3.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 264      | 3.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 252      | 3%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 239      | 2.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 202      | 2.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 189      | 2.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 183      | 2.18%   |
| Intel 200 Series PCH HD Audio                                              | 181      | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 175      | 2.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 166      | 1.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 152      | 1.81%   |
| AMD Navi 10 HDMI Audio                                                     | 151      | 1.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 150      | 1.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 146      | 1.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 131      | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 131      | 1.56%   |
| Nvidia TU104 HD Audio Controller                                           | 120      | 1.43%   |
| Nvidia GA104 High Definition Audio Controller                              | 109      | 1.3%    |
| Nvidia TU106 High Definition Audio Controller                              | 108      | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 100      | 1.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 99       | 1.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 95       | 1.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 94       | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 91       | 1.08%   |
| AMD FCH Azalia Controller                                                  | 89       | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 87       | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 86       | 1.02%   |
| Nvidia GA102 High Definition Audio Controller                              | 83       | 0.99%   |
| Nvidia GM204 High Definition Audio Controller                              | 77       | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 67       | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 64       | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                              | 59       | 0.7%    |
| Nvidia GP102 HDMI Audio Controller                                         | 54       | 0.64%   |
| Nvidia GK104 HDMI Audio Controller                                         | 53       | 0.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 53       | 0.63%   |
| Nvidia GA106 High Definition Audio Controller                              | 49       | 0.58%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 48       | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                              | 47       | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 165      | 22.76%  |
| Kingston                     | 130      | 17.93%  |
| G.Skill                      | 111      | 15.31%  |
| Crucial                      | 72       | 9.93%   |
| Unknown                      | 55       | 7.59%   |
| Samsung Electronics          | 43       | 5.93%   |
| SK hynix                     | 33       | 4.55%   |
| Team                         | 29       | 4%      |
| Micron Technology            | 22       | 3.03%   |
| A-DATA Technology            | 20       | 2.76%   |
| Patriot                      | 11       | 1.52%   |
| Ramaxel Technology           | 3        | 0.41%   |
| Patriot Memory               | 2        | 0.28%   |
| OLOY                         | 2        | 0.28%   |
| Neo Forza                    | 2        | 0.28%   |
| Avant                        | 2        | 0.28%   |
| Apacer                       | 2        | 0.28%   |
| Unknown                      | 2        | 0.28%   |
| Unifosa                      | 1        | 0.14%   |
| Transcend                    | 1        | 0.14%   |
| Toshiba                      | 1        | 0.14%   |
| Teikon                       | 1        | 0.14%   |
| Smart                        | 1        | 0.14%   |
| Silicon Power                | 1        | 0.14%   |
| Patriot Memory (PDP Systems) | 1        | 0.14%   |
| Nanya Technology             | 1        | 0.14%   |
| HMD                          | 1        | 0.14%   |
| GOODRAM                      | 1        | 0.14%   |
| Goldkey                      | 1        | 0.14%   |
| GLOWAY                       | 1        | 0.14%   |
| GeIL                         | 1        | 0.14%   |
| EVGA                         | 1        | 0.14%   |
| Elpida                       | 1        | 0.14%   |
| CSX                          | 1        | 0.14%   |
| ASint Technology             | 1        | 0.14%   |
| Asgard                       | 1        | 0.14%   |
| AMD                          | 1        | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 23       | 2.99%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s   | 14       | 1.82%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 12       | 1.56%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 10       | 1.3%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s     | 9        | 1.17%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s     | 9        | 1.17%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s  | 8        | 1.04%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 7        | 0.91%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 6        | 0.78%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s  | 6        | 0.78%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 6        | 0.78%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s            | 6        | 0.78%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 5        | 0.65%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s      | 5        | 0.65%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 5        | 0.65%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 5        | 0.65%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 5        | 0.65%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s   | 5        | 0.65%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s    | 5        | 0.65%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s             | 5        | 0.65%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3733MT/s   | 4        | 0.52%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 4        | 0.52%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 4        | 0.52%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 4        | 0.52%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s | 4        | 0.52%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s    | 4        | 0.52%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 4        | 0.52%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s  | 4        | 0.52%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 4        | 0.52%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s  | 4        | 0.52%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s   | 4        | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 3        | 0.39%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 0.39%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 3        | 0.39%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 0.39%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s     | 3        | 0.39%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 3        | 0.39%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s       | 3        | 0.39%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s     | 3        | 0.39%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 3        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 471      | 70.61%  |
| DDR3    | 135      | 20.24%  |
| DDR5    | 23       | 3.45%   |
| Unknown | 16       | 2.4%    |
| DDR2    | 12       | 1.8%    |
| SDRAM   | 7        | 1.05%   |
| DDR     | 2        | 0.3%    |
| LPDDR4  | 1        | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 639      | 96.38%  |
| SODIMM       | 22       | 3.32%   |
| Row Of Chips | 1        | 0.15%   |
| RIMM         | 1        | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 317      | 44.96%  |
| 16384 | 175      | 24.82%  |
| 4096  | 110      | 15.6%   |
| 32768 | 64       | 9.08%   |
| 2048  | 28       | 3.97%   |
| 1024  | 9        | 1.28%   |
| 512   | 2        | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 126      | 17.4%   |
| 3200    | 83       | 11.46%  |
| 1600    | 74       | 10.22%  |
| 1333    | 46       | 6.35%   |
| 2400    | 44       | 6.08%   |
| 3000    | 27       | 3.73%   |
| 2667    | 25       | 3.45%   |
| 2133    | 25       | 3.45%   |
| 3800    | 24       | 3.31%   |
| 3733    | 22       | 3.04%   |
| 3400    | 18       | 2.49%   |
| 3866    | 16       | 2.21%   |
| 3533    | 15       | 2.07%   |
| 1867    | 15       | 2.07%   |
| 2933    | 13       | 1.8%    |
| 2800    | 11       | 1.52%   |
| 2666    | 11       | 1.52%   |
| 800     | 10       | 1.38%   |
| 4800    | 8        | 1.1%    |
| 3534    | 8        | 1.1%    |
| 1866    | 8        | 1.1%    |
| 1800    | 8        | 1.1%    |
| 3466    | 7        | 0.97%   |
| 6000    | 6        | 0.83%   |
| 667     | 6        | 0.83%   |
| 4000    | 5        | 0.69%   |
| 3666    | 5        | 0.69%   |
| 3266    | 5        | 0.69%   |
| Unknown | 5        | 0.69%   |
| 4400    | 4        | 0.55%   |
| 5200    | 3        | 0.41%   |
| 3333    | 3        | 0.41%   |
| 3100    | 3        | 0.41%   |
| 6400    | 2        | 0.28%   |
| 5600    | 2        | 0.28%   |
| 4266    | 2        | 0.28%   |
| 3334    | 2        | 0.28%   |
| 3151    | 2        | 0.28%   |
| 3066    | 2        | 0.28%   |
| 2733    | 2        | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 50       | 32.05%  |
| Brother Industries    | 30       | 19.23%  |
| Canon                 | 24       | 15.38%  |
| Samsung Electronics   | 19       | 12.18%  |
| Seiko Epson           | 15       | 9.62%   |
| Dymo-CoStar           | 4        | 2.56%   |
| Fuji Xerox            | 3        | 1.92%   |
| STMicroelectronics    | 2        | 1.28%   |
| QinHeng Electronics   | 2        | 1.28%   |
| Xerox                 | 1        | 0.64%   |
| Prolific Technology   | 1        | 0.64%   |
| Oki Data              | 1        | 0.64%   |
| Lexmark International | 1        | 0.64%   |
| Kyocera               | 1        | 0.64%   |
| Dell                  | 1        | 0.64%   |
| Apple                 | 1        | 0.64%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| HP Deskjet 3050 J610 series                                | 4        | 2.55%   |
| Samsung SCX-3400 Series                                    | 3        | 1.91%   |
| HP LaserJet Professional P 1102w                           | 3        | 1.91%   |
| Brother Printer                                            | 3        | 1.91%   |
| Brother HL-2130 series                                     | 3        | 1.91%   |
| Seiko Epson WF-4830 Series                                 | 2        | 1.27%   |
| Seiko Epson L355 Series                                    | 2        | 1.27%   |
| Seiko Epson ET-2700 Series                                 | 2        | 1.27%   |
| Seiko Epson ET-2600 Series                                 | 2        | 1.27%   |
| Samsung ML-1640 Series Laser Printer                       | 2        | 1.27%   |
| Samsung M2070 Series                                       | 2        | 1.27%   |
| Samsung M2020 Series                                       | 2        | 1.27%   |
| QinHeng CH340S                                             | 2        | 1.27%   |
| HP ENVY Pro 6400 series                                    | 2        | 1.27%   |
| HP ENVY Photo 6200 series                                  | 2        | 1.27%   |
| HP ENVY 4500 series                                        | 2        | 1.27%   |
| HP DeskJet F4100 Printer series                            | 2        | 1.27%   |
| HP Deskjet F2280 series                                    | 2        | 1.27%   |
| HP DeskJet 2600 series                                     | 2        | 1.27%   |
| HP Deskjet 1000 J110 series                                | 2        | 1.27%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2        | 1.27%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2        | 1.27%   |
| Canon PIXMA MX920 Series                                   | 2        | 1.27%   |
| Canon PIXMA MG2500 Series                                  | 2        | 1.27%   |
| Brother HL-L3230CDW series                                 | 2        | 1.27%   |
| Brother HL-2270DW Laser Printer                            | 2        | 1.27%   |
| Brother HL-1110 series                                     | 2        | 1.27%   |
| Xerox Phaser 6000B                                         | 1        | 0.64%   |
| STMicroelectronics USB Printer P                           | 1        | 0.64%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1        | 0.64%   |
| Seiko Epson WF-3520 Series                                 | 1        | 0.64%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]               | 1        | 0.64%   |
| Seiko Epson L365 Series                                    | 1        | 0.64%   |
| Seiko Epson L3110 Series                                   | 1        | 0.64%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 0.64%   |
| Seiko Epson ET-3760 Series                                 | 1        | 0.64%   |
| Seiko Epson ET-2800 Series                                 | 1        | 0.64%   |
| Samsung SCX-4500 Laser Printer                             | 1        | 0.64%   |
| Samsung SCX-4200 series                                    | 1        | 0.64%   |
| Samsung ML-2540 Series Laser Printer                       | 1        | 0.64%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 50%     |
| Seiko Epson     | 6        | 27.27%  |
| Hewlett-Packard | 4        | 18.18%  |
| Mustek Systems  | 1        | 4.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30                           | 2        | 9.09%   |
| Canon CanoScan LiDE 210                                 | 2        | 9.09%   |
| Seiko Epson Scanner                                     | 1        | 4.55%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1        | 4.55%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 4.55%   |
| Seiko Epson GT-X700 [Perfection 4870]                   | 1        | 4.55%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 4.55%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1        | 4.55%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 4.55%   |
| HP Scanjet G2710                                        | 1        | 4.55%   |
| HP ScanJet 82x0C                                        | 1        | 4.55%   |
| HP Scanjet 300                                          | 1        | 4.55%   |
| HP ScanJet 2400c                                        | 1        | 4.55%   |
| Canon CanoScan N650U/N656U                              | 1        | 4.55%   |
| Canon CanoScan LiDE 60                                  | 1        | 4.55%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1        | 4.55%   |
| Canon CanoScan LiDE 220                                 | 1        | 4.55%   |
| Canon CanoScan LiDE 200                                 | 1        | 4.55%   |
| Canon CanoScan LiDE 110                                 | 1        | 4.55%   |
| Canon CanoScan 9000F Mark II                            | 1        | 4.55%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 317      | 44.34%  |
| Microdia                      | 61       | 8.53%   |
| Microsoft                     | 37       | 5.17%   |
| Sunplus Innovation Technology | 27       | 3.78%   |
| Apple                         | 22       | 3.08%   |
| Generalplus Technology        | 20       | 2.8%    |
| Samsung Electronics           | 15       | 2.1%    |
| ARC International             | 15       | 2.1%    |
| Razer USA                     | 13       | 1.82%   |
| Realtek Semiconductor         | 12       | 1.68%   |
| Chicony Electronics           | 12       | 1.68%   |
| Z-Star Microelectronics       | 11       | 1.54%   |
| MacroSilicon                  | 10       | 1.4%    |
| Jieli Technology              | 10       | 1.4%    |
| Creative Technology           | 10       | 1.4%    |
| Valve Software                | 9        | 1.26%   |
| KYE Systems (Mouse Systems)   | 8        | 1.12%   |
| Hewlett-Packard               | 6        | 0.84%   |
| Cubeternet                    | 6        | 0.84%   |
| LG Electronics                | 5        | 0.7%    |
| Huawei Technologies           | 5        | 0.7%    |
| AVerMedia Technologies        | 5        | 0.7%    |
| Aveo Technology               | 4        | 0.56%   |
| YGTek                         | 3        | 0.42%   |
| Trust                         | 3        | 0.42%   |
| HD 2MP WEBCAM                 | 3        | 0.42%   |
| A4Tech                        | 3        | 0.42%   |
| WCM_USB                       | 2        | 0.28%   |
| ValueHD                       | 2        | 0.28%   |
| Unknown                       | 2        | 0.28%   |
| Sunplus IT                    | 2        | 0.28%   |
| SN0002                        | 2        | 0.28%   |
| Ruision                       | 2        | 0.28%   |
| Novatek Microelectronics      | 2        | 0.28%   |
| Intel                         | 2        | 0.28%   |
| HTC (High Tech Computer)      | 2        | 0.28%   |
| GenesysLogic Technology       | 2        | 0.28%   |
| Genesys Logic                 | 2        | 0.28%   |
| GEMBIRD                       | 2        | 0.28%   |
| eMeet                         | 2        | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 70       | 9.74%   |
| Logitech Webcam C270                    | 62       | 8.62%   |
| Microdia Webcam Vitade AF               | 24       | 3.34%   |
| Logitech C922 Pro Stream Webcam         | 24       | 3.34%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 21       | 2.92%   |
| Logitech BRIO Ultra HD Webcam           | 18       | 2.5%    |
| Samsung Galaxy series, misc. (MTP mode) | 15       | 2.09%   |
| Logitech HD Webcam C525                 | 15       | 2.09%   |
| Generalplus GENERAL WEBCAM              | 15       | 2.09%   |
| ARC International Camera                | 15       | 2.09%   |
| Microsoft LifeCam HD-3000               | 14       | 1.95%   |
| Logitech HD Webcam C615                 | 14       | 1.95%   |
| Logitech Webcam C925e                   | 11       | 1.53%   |
| Logitech C920 PRO HD Webcam             | 11       | 1.53%   |
| Razer USA Gaming Webcam [Kiyo]          | 10       | 1.39%   |
| Logitech Webcam C930e                   | 10       | 1.39%   |
| Jieli USB PHY 2.0                       | 10       | 1.39%   |
| Valve Software 3D Camera                | 9        | 1.25%   |
| Microdia USB 2.0 Camera                 | 9        | 1.25%   |
| Logitech Webcam C310                    | 9        | 1.25%   |
| Sunplus Full HD webcam                  | 8        | 1.11%   |
| Microsoft LifeCam Cinema                | 8        | 1.11%   |
| MacroSilicon USB Video                  | 8        | 1.11%   |
| Logitech Webcam Pro 9000                | 8        | 1.11%   |
| Logitech Webcam C170                    | 8        | 1.11%   |
| Logitech StreamCam                      | 8        | 1.11%   |
| Microdia Integrated Camera              | 7        | 0.97%   |
| Microdia Camera                         | 6        | 0.83%   |
| Chicony HP High Definition 1MP Webcam   | 6        | 0.83%   |
| Realtek Full HD webcam                  | 5        | 0.7%    |
| Logitech HD Webcam C510                 | 5        | 0.7%    |
| Huawei UVC Camera                       | 5        | 0.7%    |
| AVerMedia Live Streamer CAM 313         | 5        | 0.7%    |
| Sunplus USB 2.0 Camera                  | 4        | 0.56%   |
| Microdia Sonix USB 2.0 Camera           | 4        | 0.56%   |
| Logitech Logi Webcam C920e              | 4        | 0.56%   |
| Logitech HD Webcam C910                 | 4        | 0.56%   |
| Logitech BRIO 4K Stream Edition         | 4        | 0.56%   |
| Logitech B525 HD Webcam                 | 4        | 0.56%   |
| Z-Star Venus USB2.0 Camera              | 3        | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 25%     |
| Elan Microelectronics | 2        | 25%     |
| Validity Sensors      | 1        | 12.5%   |
| LighTuning Technology | 1        | 12.5%   |
| DigitalPersona        | 1        | 12.5%   |
| AuthenTec             | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 2        | 25%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 12.5%   |
| LighTuning Fingerprint Sensor                               | 1        | 12.5%   |
| DigitalPersona Fingerprint Reader                           | 1        | 12.5%   |
| AuthenTec Fingerprint Sensor                                | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 6        | 35.29%  |
| Realtek Semiconductor | 3        | 17.65%  |
| OmniKey               | 3        | 17.65%  |
| Alcor Micro           | 3        | 17.65%  |
| Chicony Electronics   | 1        | 5.88%   |
| Advanced Card Systems | 1        | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 4        | 23.53%  |
| Realtek Semiconductor Smart Card Reader Interface      | 3        | 17.65%  |
| OmniKey CardMan 3021 / 3121                            | 2        | 11.76%  |
| Alcor Micro Watchdata W 1981                           | 2        | 11.76%  |
| SCM Microsystems SCR3500 A Contact Reader              | 1        | 5.88%   |
| SCM Microsystems SCR331 SmartCard Reader               | 1        | 5.88%   |
| OmniKey CardMan 1021                                   | 1        | 5.88%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 5.88%   |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 5.88%   |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3057     | 80.53%  |
| 1     | 663      | 17.47%  |
| 2     | 65       | 1.71%   |
| 3     | 8        | 0.21%   |
| 7     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |
| 4     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 289      | 35.99%  |
| Graphics card            | 281      | 34.99%  |
| Unassigned class         | 53       | 6.6%    |
| Sound                    | 26       | 3.24%   |
| Multimedia controller    | 26       | 3.24%   |
| Communication controller | 22       | 2.74%   |
| Bluetooth                | 22       | 2.74%   |
| Storage/raid             | 16       | 1.99%   |
| Net/ethernet             | 15       | 1.87%   |
| Chipcard                 | 13       | 1.62%   |
| Network                  | 11       | 1.37%   |
| Fingerprint reader       | 8        | 1%      |
| Camera                   | 7        | 0.87%   |
| Storage/ide              | 4        | 0.5%    |
| Card reader              | 4        | 0.5%    |
| Storage/nvme             | 3        | 0.37%   |
| Firewire controller      | 2        | 0.25%   |
| Dvb card                 | 1        | 0.12%   |

